# Planner 3 on iPhone: setup guide (SideStore)

*Read it in order. Button names in **bold** match the app.*

## What you need

- Your iPhone, with a passcode set
- Your Windows computer, with the iPhone cable
- Wi-Fi
- Your Apple ID email and password
- Your Google account
- About 20 minutes

Planner 3 installs without the App Store, using **SideStore**. Apple makes these apps expire after 7 days. SideStore renews them by itself.

---

## Install

### On your iPhone first

1. Open the **App Store**.
2. Search for **LocalDevVPN**, then install it.
3. Open **LocalDevVPN**.
4. Tap **Connect**.
5. If iOS asks "Allow VPN Configurations", tap **Allow**.
6. Type your passcode if iOS asks.

The VPN symbol stays local. It only lets SideStore renew apps.

### On your computer

1. Install **iTunes** from apple.com.
2. Download the **iloader** installer from github.com/nab138/iloader.
3. Run the installer.
4. Connect your iPhone to the computer with the cable.
5. Unlock the iPhone.
6. If iOS asks "Trust This Computer?", tap **Trust**.
7. Type your iPhone passcode if asked.
8. Open **iloader**.
9. Type your Apple ID email and password. The email is case-sensitive.
10. Type the verification code Apple sends.
11. Select your iPhone from the device list.
12. Choose **Install SideStore (Stable)**.
13. Wait for it to finish.

### On your iPhone again

1. Open **Settings**.
2. Tap **General**.
3. Tap **VPN & Device Management**.
4. Under "Developer App", tap your Apple Account.
5. Tap **Trust [your name]**. On iOS 18 it may say **Allow & Restart**.
6. Type your passcode if asked.
7. Go to **Settings** → **General** → **Privacy & Security**.
8. Turn on **Developer Mode**. The phone restarts once. Skip this on iOS 15.
9. Open **LocalDevVPN**.
10. Tap **Connect**.
11. Open **SideStore**.
12. Sign in with the same Apple ID as before.

### Install Planner 3

1. Open **SideStore**.
2. Tap **Sources**, then the **+** button.
3. Paste this address: `https://raw.githubusercontent.com/Arindam2000/planner-3-ios/main/apps.json`
4. Tap **Add Source**. Planner 3 now shows in SideStore.
5. Tap **Install** next to Planner 3.
6. Wait for it to finish. Planner 3 appears in **My Apps**.

---

## First Open

1. Open **Planner 3** from the Home Screen.
2. If iOS says "Untrusted Developer", repeat the trust steps under Install.
3. Tap the **Settings** gear at the top of the screen.
4. In the **Sync** group, tap **Sign in with Google**.
5. Tap **Open google.com/device**. Safari opens.
6. Sign in with your Google account.
7. Type the code shown in Planner 3.
8. Tap **Allow**.
9. Go back to Planner 3. It carries on by itself within a few seconds.

### If you already have to-dos on another device

1. Look at the **Sync** group in Settings.
2. Tap **Use My Account's To-Dos**.

This replaces this phone's sample to-dos with your account's to-dos.

### Calendar events

1. Open **Upcoming**.
2. Tap **Show Calendar Events**.
3. Allow calendar access when iOS asks.

Planner 3 only reads your events. It changes nothing.

Google calendars appear only if the Google account is added in iPhone **Settings** → **Apps** → **Calendar** → **Calendar Accounts**.

---

## Every Week

- SideStore renews Planner 3 in the background while LocalDevVPN is connected. You do nothing.
- Optional: in the Shortcuts app, make a daily 9:00 automation that opens **SideStore**.

---

## If Something Is Wrong

- **No Sync group in Settings:** Close Planner 3 fully, then open it again.
- **"Can't reach Google Drive":** Check the Wi-Fi. Changes wait on the phone and upload later.
- **"Google Drive refused access":** Tap **Sign Out**, then tap **Sign in with Google**.
- **App stops opening after 7 days:** Connect LocalDevVPN, open SideStore, and refresh Planner 3 in **My Apps**.
- **No Google events in Upcoming:** Add the Google account under iPhone Calendar Accounts, as shown above.

## Honest notes

- Your Apple ID is used only to sign the app. Apple requires this.
- SideStore is open-source community software, not an Apple product.
- Planner 3 keeps its data on your phone and in your own Google Drive.
- The App Store alternative AltStore PAL cannot carry Planner 3.
