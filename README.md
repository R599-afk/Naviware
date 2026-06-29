# 🛡️ Naviware

Naviware is a specialized optimization utility that syncs your personalized in-game profile data through a fast, cloud-based service. It runs quietly in the background, applies your chosen configuration, and stays out of your way while you play.

---

## 🚀 What's New in v1.2.1

* **Plan line-up clarified** — each license plan now precisely matches its store listing. **Prestige customization is a Full-plan feature**, the **Items** plan focuses on item & inventory control, and the **Skins** plan on cosmetics.
* **Reliability & accuracy fixes** under the hood.

> Building on everything introduced in **v1.2.0**: five preset slots, last-setup memory, the "Violet Glass" sidebar interface, clear plan-lock indicators, instant preset feedback (`✓ Saved` / `✓ Loaded`), the live dashboard, and the built-in auto-updater.

---

## 💻 System Requirements

* **Windows 10 or 11 (64-bit).**
* **Administrator rights** — Naviware needs to run as Administrator (Windows will prompt you).
* **An active internet connection.**
* **No extra installs** — everything Naviware needs is built into the app. You don't have to install .NET or any other software.

---

## ⚠️ First Run: Windows / Antivirus Warning (Important)

The **first** time you open `Naviware.exe`, Windows SmartScreen or your antivirus may show a warning — for example *"Windows protected your PC"*, or your antivirus may quarantine the file. **This is a false positive. Naviware is safe to run.**

Because Naviware is a new tool that connects to our service and adjusts a few Windows network settings while it runs, security software that hasn't seen it before sometimes flags it out of caution. Here's how to get past it:

* **Windows SmartScreen ("Windows protected your PC"):** click **More info → Run anyway**.
* **Antivirus blocked or deleted the file (Windows Defender, Avast, Bitdefender, etc.):** add Naviware — and the folder it lives in — to your antivirus **exclusions / allow-list**, then download it again if it was removed.
* Keep `Naviware.exe` in its **own folder**, and always run it **as Administrator** (click **Yes** on the Windows prompt).

> If your antivirus keeps deleting Naviware after you allow it, make sure you added the **whole folder** to exclusions before re-downloading.

---

## ⚙️ How to Use (Step-by-Step Setup)

> **⚠️ IMPORTANT — order matters!** Game launchers cache system settings when they open. If **Epic Games** or the **Xbox / Microsoft Store** app is opened *before* Naviware, the game may ignore it. Always follow this exact order.

1. **Close your game launcher completely.** Make sure Epic Games or the Xbox app is fully closed — check your system tray (bottom-right) and exit it if it's still running.
2. **Run `Naviware.exe`.** Click **Yes** when Windows asks for Administrator permission.
3. **Activate your license.** Enter your License Key in the popup and click **ACTIVATE**.
4. **Choose your options** on the **Loadout** tab (Target Prestige, Prestige Logic, Inventory Mode, Auto-Launch). Anything not included in your plan will appear greyed out / marked **Locked**.
5. **Click START** on the Dashboard and wait for the console to say it's ready and waiting for the game.
6. **Open your launcher** (Epic Games / Microsoft Store) and start Dead by Daylight.

That's it — Naviware applies your settings automatically once the game connects.

---

## 🧭 Navigating the App

The sidebar on the left switches between five tabs:

* **🏠 Dashboard** — your home screen. Shows live status (System, last refresh, Target Prestige) and a quick summary of your current settings. The big **START** button lives here.
* **🎛️ Loadout** — where you configure everything (prestige, logic, inventory amounts, auto-launch).
* **💾 Presets** — save and load up to five configuration slots.
* **🖥️ Console** — live activity log, plus the **FIX NETWORK** repair tool.
* **⚙️ Settings** — overlay hotkey, Ghost Mode info, and your license key.

Your active plan is shown next to the page title (e.g. **FULL PLAN**), and the status pill (top-right) shows whether Naviware is Idle, in a lobby, in queue, or in a match.

---

## 🎛️ Settings Explained

### Loadout tab
* **Target Prestige** — the prestige level you want shown for your characters. *(Full plan.)*
* **Prestige Logic:**
  * *Smart Mode (Keep Higher Legit):* if your real prestige on a character is **higher** than your Target Prestige, Naviware keeps your real level so you never appear to downgrade.
  * *Force Mode:* applies the Target Prestige to **all** characters regardless of their real level.
* **Inventory Mode** — how item quantities are set: **Default**, **Custom Fixed Amount**, or **Custom Random Range** (min/max). *Available on Full / Items plans.*
* **Auto-Launch** — optionally open your launcher automatically once Naviware is running.

### Settings tab
* **Overlay Key** — the hotkey that toggles the in-game overlay. Default: **`Insert`**. Choose **Custom…** and press any key to rebind it.
* **Ghost Mode** — press **`HOME`** in-game to toggle the overlay's transparency.
* **License Key** — shows the key currently activated on this device.

### Presets tab
* **SAVE** — stores your current Loadout settings into that slot (an on-screen `✓ Saved` confirms it).
* **LOAD** — applies the settings stored in that slot (`✓ Loaded` confirms it).

---

## 🔘 Action Buttons

* 🟣 **START** *(Dashboard)* — starts Naviware, prepares the connection, and waits for the game. Becomes **STOP** while running.
* 🔴 **FIX NETWORK** *(Console)* — if Naviware ever closes unexpectedly or you lose internet after using it, click this to reset your Windows network settings back to normal.

---

## 🔒 License Plans

Naviware adjusts what's available based on your plan. Anything outside your plan is clearly marked **Locked** in the app:

* **Full** — everything unlocked (prestige, item/inventory, and cosmetics).
* **Items** — item/inventory features (prestige and cosmetic features locked).
* **Skins** — cosmetic features (prestige and inventory features locked).

If something looks greyed out or says **Locked**, it simply isn't part of your current plan.

---

## 🛠️ Troubleshooting

If Naviware is running but your changes aren't showing up (status looks red, or the game won't connect), something on your PC is usually getting in the way. The most common causes:

### 1. Riot Vanguard (VALORANT)
Vanguard runs at all times and blocks third-party background utilities.
**Fix:** Right-click the Vanguard icon in your system tray and choose **Exit Vanguard**, then restart Naviware.

### 2. OEM "Network Booster" apps (pre-built / gaming PCs)
Many pre-built PCs ship with apps that reroute game traffic.
**Fix:** Turn off or uninstall things like:
* **ASUS:** *GameFirst* / Network Boost (Armoury Crate)
* **Lenovo:** *Lenovo Vantage* → turn off "Network Boost"
* **MSI / HP:** *Killer Intelligence Center* / *HP Omen Gaming Hub*
* **Other:** *cFosSpeed*

### 3. DNS / IPv6 interference
**Fix:** Set your Windows DNS to **Automatic (DHCP)**. If issues persist, open your network adapter properties and **uncheck** `Internet Protocol Version 6 (TCP/IPv6)`.

### 4. Run as Administrator
Always launch Naviware with Administrator rights (click **Yes** on the Windows prompt). If you previously denied a first-run setup prompt, close everything and relaunch, accepting the prompt this time.

---

## ⚕️ Still Stuck? Contact Support

If you've worked through the steps above and Naviware still isn't applying your changes:

1. Click **FIX NETWORK** on the **Console** tab to reset your Windows network settings.
2. Restart your PC, then try the setup again in the correct order (launcher fully closed → run Naviware → **START** → open launcher).
3. Join our community via the **Buy License / Join Discord** link in the app and let us know:
   * which **plan** you're on,
   * what the **Console** log and the **status pill** (top-right) are showing,
   * which troubleshooting steps you've already tried.

Our team will take it from there.

---

*Need help or a license? Join our community via the **Buy License** / **Join Discord** links in the app.*
