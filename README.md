# 🛡️ Naviware

Naviware is an unofficial Windows utility for supported PC editions of Dead by Daylight. It runs locally while you play and applies the prestige, inventory, perk, and cosmetic options included with your Naviware license plan.

Naviware is not affiliated with, endorsed by, or approved by Behaviour Interactive.

---

## ⚠️ Compatibility

### Supported

* **Epic Games Launcher**
* **Microsoft Store / Xbox app on Windows**
* **Windows 10 or Windows 11, 64-bit**

### Not Supported

* **Steam**
* **Xbox, PlayStation, Nintendo Switch, or other consoles**
* **Cloud-gaming platforms**
* **32-bit versions of Windows**

Game and platform updates may affect compatibility. Continued compatibility cannot be guaranteed after an update.

---

## ⚠️ Important Risk Notice

Naviware is unofficial third-party software.

Using unofficial third-party software may violate the Dead by Daylight EULA, game rules, or platform rules. Its use may result in errors, loss of access, temporary suspension, or permanent account suspension.

Naviware does not guarantee that its use is undetectable, ban-safe, or continuously compatible with future game updates. Previous users operating without reported problems does not guarantee the same outcome for another account.

Before using Naviware, review:

* [Dead by Daylight EULA](https://deadbydaylight.com/eula/)
* [Dead by Daylight Game Ban Policy](https://support.deadbydaylight.com/hc/en-us/articles/45521322753428-Game-Bans)

“Session-based” and “revertible” describe how Naviware’s local changes behave. They do not mean that using the software is risk-free.

If an account is suspended, only Behaviour Interactive can provide or confirm the reason. Ban appeals must be submitted directly to Behaviour Interactive.

---

## 🔍 How Naviware Works

Naviware starts a local HTTPS proxy on your computer and temporarily configures Windows to send supported Dead by Daylight service traffic through it.

It processes selected game-service responses according to your active license plan. Other traffic is intended to pass through unchanged.

During first-time setup, Naviware may ask permission to create and trust a local root certificate. This certificate is required so the local proxy can process HTTPS responses.

* **START** activates the local proxy and applies the selected configuration.
* **STOP** restores the previous Windows proxy settings and clears the active session cache.
* The trusted Naviware certificate remains installed after a normal STOP so setup is not repeated every time.
* **FIX NETWORK** restores the proxy settings, clears session data, and removes Naviware and legacy proxy certificates. Certificate approval will be required again on the next START.

Naviware does not directly edit the Dead by Daylight save file. Its effects are applied through selected responses while Naviware is running and do not grant official ownership of content.

---

## ✨ Included Features

Available features depend on your active plan:

* Select a target prestige level from the supported choices.
* Set supported items, add-ons, and offerings to default, fixed, or random quantities.
* Display Tier 3 perks through supported inventory responses.
* Enable supported cosmetics, outfits, and charms.
* Save and load up to five configuration presets.
* View the current Naviware status through the Dashboard and overlay.
* Launch Dead by Daylight manually or request automatic launch through Epic Games.

Naviware does **not** unlock characters, DLC, premium currency, or official account ownership of displayed content.

---

## 🆕 What’s New in v1.2.7

* **Safer updates** — downloaded updates are verified before installation.
* **More reliable cleanup** — shutdown and crash recovery restore Windows connection settings more reliably.
* **Clearer setup prompts** — first-time prompts explain certificate and Windows configuration changes.
* **License reliability improvements** — plan validation, device unlinking, and license checks are stricter.
* **Correct plan separation** — prestige remains exclusive to the Full plan.

This version also includes the preset system, update progress window, in-app device reset, skins toggle, overlay, redesigned Loadout interface, live Dashboard, and built-in updater introduced in earlier v1.2.x releases.

---

## 📥 Download and Tutorial

Download Naviware only from the official GitHub release page:

https://github.com/R599-afk/Naviware/releases/latest

Video tutorial:

https://www.youtube.com/watch?v=i0ogUBX5dTY

Do not download Naviware from file reuploads, private messages, or unofficial mirrors.

---

## 💻 System Requirements

* Windows 10 or Windows 11, 64-bit
* Administrator rights
* An active internet connection
* Epic Games or Microsoft Store/Xbox PC version of Dead by Daylight
* An active Naviware license

Naviware is distributed as a self-contained application. A separate .NET installation is not required.

---

## 🛡️ Windows SmartScreen and Antivirus Warnings

Windows SmartScreen or antivirus software may display a warning when opening Naviware. A warning alone does not prove that a file is either malicious or safe.

Before continuing:

1. Confirm that the file came from the official Naviware GitHub release page.
2. Right-click `Naviware.exe`, open **Properties**, and check that its digital signature is present and valid.
3. Stop if the signature is missing, invalid, or the download source is uncertain.
4. Contact support if the official signed file remains blocked.

Do not disable antivirus protection, exclude an entire folder, or disable other security software solely to run Naviware.

Naviware requires Administrator permission because it manages a local proxy, certificate trust, and Windows network settings. Review the Windows prompt before approving it.

---

## ⚙️ How to Use

> **The order matters. Configure Naviware before launching Dead by Daylight.**

1. **Close Dead by Daylight completely.**
2. **Close the game launcher completely.**
   * Exit Epic Games Launcher or the Xbox app.
   * Check the Windows system tray to make sure the launcher is not still running.
3. **Run `Naviware.exe`.**
   * Approve the Administrator prompt after confirming that you downloaded the official signed release.
4. **Activate your license.**
   * Enter your license key and select **ACTIVATE**.
   * Keep your full license key private.
5. **Configure the Loadout page.**
   * Choose the target prestige and application logic available with your plan.
   * Choose the inventory quantity mode.
   * Enable or disable supported skins.
   * Select manual launch or Epic automatic launch.
6. **Press START on the Dashboard.**
7. **Review the certificate notice on first use.**
   * Continue only if you understand and accept the local HTTPS proxy and certificate configuration.
8. **Wait until the console reports that Naviware is ready and waiting for Dead by Daylight.**
9. **Launch Dead by Daylight.**
   * Epic users may use the automatic launch option.
   * Microsoft Store users should launch through the Xbox/Microsoft Store app after Naviware is ready.
10. **When finished, close Dead by Daylight and its launcher, then press STOP or exit Naviware.**

---

## ⚠️ Do Not Change Settings During an Active Session

Configure all settings before pressing START and while Dead by Daylight is closed.

Changing prestige, prestige logic, skins, inventory mode, or quantities while Naviware and the game are already running is unsupported and may not apply consistently.

To change settings:

1. Close Dead by Daylight.
2. Close the game launcher.
3. Press **STOP** in Naviware.
4. Change the configuration.
5. Press **START** again.
6. Wait until Naviware is ready.
7. Relaunch Dead by Daylight.

Do not manually edit Naviware configuration files while Naviware or Dead by Daylight is running.

---

## 🧭 Navigating the App

### 🏠 Dashboard

Displays:

* Naviware system status
* Lobby, queue, and match state
* Selected prestige
* Inventory configuration
* Skins status
* Last bloodweb refresh
* START and STOP controls

### 🎛️ Loadout

Configure:

* Target prestige
* Prestige application logic
* Inventory quantity mode
* Fixed or random item quantities
* Supported skins
* Game launch mode

Options not included with your license plan appear greyed out or marked **Locked**.

### 💾 Presets

Save and load up to five configuration presets.

* **SAVE** stores the current Loadout settings.
* **LOAD** applies the stored settings.

Loading a preset while Naviware is running does not reliably update the active session. Restart Naviware and the game after loading a different preset.

### 🖥️ Console

Displays current Naviware activity and connection information.

The Console also contains **FIX NETWORK**, which performs a more complete network and certificate reset.

### ⚙️ Settings

Configure:

* Overlay hotkey
* Device unlinking
* License information
* Other application preferences

---

## 🎛️ Settings Explained

### Target Prestige

Available with the **Full** plan.

Choose the prestige value Naviware should display through supported responses.

Your original earned prestige is not directly overwritten in the Dead by Daylight save file.

### Prestige Logic

* **Smart Mode — Keep Higher Legit:** keeps a character’s real prestige when it is higher than the selected target.
* **Force Mode:** applies the selected target through supported responses regardless of the real prestige.

### Inventory Mode

Available with the **Full** and **Items** plans.

* **Default:** sets supported item quantities to 200.
* **Custom Fixed:** applies one selected quantity to supported items.
* **Custom Random Range:** selects quantities between the configured minimum and maximum.

Random quantities are cached per item for the active Naviware session. Restart Naviware before changing the random range.

### Supported Skins

Available with the **Full** and **Skins** plans.

The skins toggle is captured when Naviware starts. Changing it during an active session will not reliably change the running configuration.

Displayed cosmetics do not represent official ownership and may be affected by game updates or enforcement policies.

### Game Launch

* **Manual:** start the supported launcher and Dead by Daylight yourself after pressing START.
* **Epic Auto-Launch:** Naviware requests Dead by Daylight through the installed Epic Games Launcher.

Microsoft Store users should use Manual mode.

### Overlay

* **Overlay Key:** shows or hides the Naviware overlay. Default: `Insert`.
* **Ghost Mode:** press `HOME` to change the overlay’s visibility/opacity.

Ghost Mode affects only the Naviware overlay. It does not make Naviware undetectable and does not change account risk.

### Unlink This PC

Use **Settings → Unlink This PC** before moving the same license to another computer.

If the original computer is no longer accessible, contact support through the marketplace or channel where the license was purchased.

---

## 🔒 License Plans

| Plan | Included | Not Included |
| --- | --- | --- |
| **Full** | Prestige, Tier 3 perks, supported items/add-ons/offerings, inventory quantities, and supported cosmetics | Character/DLC ownership and premium currency |
| **Items** | Tier 3 perks, supported items/add-ons/offerings, and inventory quantities | Prestige and cosmetics |
| **Skins** | Supported cosmetics, outfits, and charms | Prestige, items, inventory quantities, and perks |

Anything outside the active plan appears **Locked** in Naviware.

---

## 🔄 Session Behavior and Cleanup

Naviware’s modifications are session-based:

* Naviware applies supported changes while its local proxy is active.
* Pressing STOP stops further Naviware processing and restores the previous Windows proxy settings.
* Restart Dead by Daylight after stopping Naviware to return to normal game responses.
* Session-based behavior does not guarantee that use is undetectable or risk-free.

If Naviware closes unexpectedly and Windows loses network access:

1. Reopen Naviware as Administrator.
2. Open the **Console** page.
3. Select **FIX NETWORK**.
4. Confirm the reset.
5. Restart Windows if the connection is not restored immediately.

FIX NETWORK removes Naviware’s trusted proxy certificate and legacy proxy artifacts. The certificate setup notice will appear again the next time you press START.

---

## 🛠️ Troubleshooting

### Changes Do Not Appear

1. Close Dead by Daylight and its launcher.
2. Press STOP.
3. Confirm that your platform is supported.
4. Confirm that the feature is included with your license plan.
5. Configure the Loadout before pressing START.
6. Press START and wait for the ready message.
7. Launch Dead by Daylight again.

### Game Cannot Connect

1. Close Dead by Daylight and its launcher.
2. Press STOP and wait for Windows proxy restoration.
3. If the connection remains unavailable, use **FIX NETWORK**.
4. Restart Windows if necessary.
5. Contact support with the Naviware version and sanitized Console output.

### Antivirus or Security Software Blocks Naviware

* Confirm that the file came from the official GitHub release page.
* Check the digital signature.
* Do not disable antivirus, Vanguard, firewall protection, or other security controls.
* Do not create a broad antivirus folder exclusion.
* Contact support if the verified official file remains blocked.

### Network or DNS Problems

Keep Windows DNS and IPv6 at their normal/default settings unless a qualified network administrator has identified a specific problem.

Do not disable IPv6 or uninstall networking/security software simply to make Naviware operate.

### Other Third-Party Tools

Other injectors, unlockers, proxies, overlays, modified configuration files, or third-party utilities are outside Naviware support and may introduce additional compatibility or account risk.

When troubleshooting, test only with the supported official game client and Naviware configuration.

---

## ⚕️ Contact Support

When requesting support, include:

* Naviware version
* Dead by Daylight platform: Epic Games or Microsoft Store
* Active Naviware plan
* Selected settings
* What the status pill displays
* Sanitized Console output
* The exact setup sequence followed
* Any error message or screenshot

Do not send:

* Account passwords
* Authentication tokens
* Full payment
