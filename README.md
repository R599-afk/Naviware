# 🛡️ Naviware

Naviware is a powerful utility designed to securely and seamlessly apply your desired in-game values. 

---

## ⚙️ How to Use (Step-by-Step Setup)
*Crucial: Launchers cache system settings. If Epic Games or the Microsoft Store/Xbox app is opened BEFORE Naviware, the game will ignore the app. Always follow this exact order!*

1. **Close your game launcher completely** (Make sure Epic Games or the Xbox app is NOT running in your system tray).
2. Run `Naviware.exe` (Click 'Yes' when Windows asks for Administrator permissions).
3. Set up your desired options in the app (Target Prestige, Logic, etc.).
4. Click **START** and wait for the console to say `Waiting for game...`.
5. Open your launcher (Epic Games / Microsoft Store) and start Dead by Daylight.

---

## 🎮 Features & UI Explained

### ⚙️ Main Settings
* **Target Prestige:** Select the prestige level you want injected into the game for your characters.
* **Prestige Logic:**
  * **Smart Mode (Keep Higher Legit):** If your actual, legitimate prestige on a character is *higher* than your Target Prestige, the app will keep your real level so you don't downgrade.
  * **Force Mode:** Forces the Target Prestige on all characters, regardless of their real level.
* **Auto-Launch:** Automatically opens your selected launcher once Naviware is successfully running.
* **Overlay Key:** The hotkey used to toggle the in-game overlay (Default: `Insert`).
* **Presets (1, 2, 3):** Save your favorite configurations. Left-click to load a preset, Right-click to save current settings to that slot.

### 🔘 Action Buttons
* **🟣 START:** Initializes the application, secures the connection, and waits for the game to launch.
* **🟠 FIX:** If Naviware crashes or you lose your internet connection after closing the app, click this! It forcefully resets your Windows network settings back to normal.
* **🔵 DEBUG:** A 1-click diagnostic tool that scans your PC for software conflicts, background blockers, or stale configurations.

---

## 🛠️ Troubleshooting & Known Conflicts
If the application is running but the changes aren't applying (e.g., game doesn't connect, or status logo is red), a 3rd-party software or Windows setting is blocking the app. 

### 1. The Final Boss: Riot Vanguard (VALORANT)
* **The Issue:** Vanguard runs at the kernel level 24/7 and strictly blocks third-party background utilities.
* **The Fix:** Right-click the Vanguard icon in your system tray (bottom right) and click **Exit Vanguard**. Restart Naviware.

### 2. OEM "Network Boosters" (Bloatware)
* **The Issue:** Pre-built PCs come with hidden apps that aggressively reroute game connections, preventing Naviware from syncing.
* **The Fix:** Turn OFF or Uninstall:
  * **ASUS:** `GameFirst` or Network Boost in Armoury Crate
  * **Lenovo:** `Lenovo Vantage` (Turn OFF "Network Boost")
  * **MSI/HP:** `Killer Intelligence Center` / `HP Omen Gaming Hub`
  * **Hidden Engines:** `cFosSpeed`

### 3. Encrypted DNS / IPv6 Interference
* **The Fix:** Ensure your Windows DNS is set to **Automatic (DHCP)** in Settings. For IPv6, go to your Network Adapter Properties and **Uncheck** `Internet Protocol Version 6 (TCP/IPv6)`.

### 4. System Validation Error (Red Logo in-game)
* **The Fix (Manual Trust Setup):**
  1. Open the Naviware folder and double-click the `rootCert.pfx` file.
  2. Select **Current User** -> Next (leave password blank).
  3. Select **"Place all certificates in the following store"** -> Browse -> Choose **Trusted Root Certification Authorities**.
  4. Finish and click **Yes** on the Windows prompt.

---

## ⚕️ Built-in Debug Utility
If you followed the steps and the game still doesn't connect, use the built-in troubleshooter!

1. Close your game and launcher.
2. Open `Naviware.exe` and click the **DEBUG** button (before clicking Start).
3. The tool will scan your PC for firewall blocks, network conflicts, running launchers, and configuration errors.
4. It will prompt you (Y/N) to automatically fix the issues it finds.
5. Once finished, it saves a `NaviwareDebug.txt` file to your **Desktop**. If you still need support, send this file to the developer!
