# ⚡ WinRaze S-Rank Software Bundle v1.0.0 ⚡
*Developed by: Rohit Kr. Mandal (CyberKun)*

I hope your system is now free from lag! To make your PC ready for future use and safe browsing, I have listed these 3 elite tools.

### 📦 Included S-Rank Assets:

1. **Outbyte Camomile CPU Cooler** (`.exe`)
   * **Purpose:** Cooler Hardware = Longer Life. 
   * **Feature:** Intelligently manages power plans to reduce CPU temperature, keeping your laptop quiet and extending battery life.

2. **Thorium AVX Browser** (`.exe`)
   * **Purpose:** The World's Fastest Browser.
   * **Feature:** A specialized Chromium build optimized with AVX instructions. It uses significantly less RAM and processes web data faster than Chrome, Zen, Edge, Opera, Herond, or Brave.
   ## ⚙️ After installing Thorium Browser, go to:
      `chrome://flags/`
Set the following options:
- **Zero-copy rasterizer** → Enabled  
- **Disable subframe process reuse** → Disabled 

3. **ToolWiz Time Freeze** (`.exe`)
   * **Purpose:** The Ultimate System Shield.
   * **Feature:** Creates a "Virtual Space" for your Windows OS. If you accidentally install a virus, ransomware, or malware from a third-party site, simply restart your PC. All malicious changes are wiped clean instantly.

# 🛠️ Multi-Boot USB Creation Guide  
### Using WinSetupFromUSB

This guide explains how to create a single USB drive that can boot multiple versions of Windows using **WinSetupFromUSB**.

---

## 📋 Requirements
- USB drive with **16 GB or more** capacity  
- I have three Windows ISOs, not Linux. If I had Linux ISOs, I could also add them. But today, I will make a bootable USB with three Windows ISOs:
  - 🟦 Windows 10 Home  
  - 🟦 Windows 10 Pro  
  - 🟦 Windows 11 Pro  
- WinSetupFromUSB (v1.10 or later)

---

## 🚀 Step 1: Extract and Run the Tool
1. Download `WinSetupFromUSB-1-10.zip`.  
2. **Right-click** → **Run as Administrator**.  
3. Extract files to your preferred location.  
4. Open the folder and run the correct version:  
   - `WinSetupFromUSB_1-10` → 32-bit systems  
   - `WinSetupFromUSB_1-10_x64` → 64-bit systems  
5. **Right-click** `_x64` → **Run as Administrator**.

---

## 🔌 Step 2: Insert Your USB Drive
- Plug in your USB drive.  
- Click **Refresh** inside the program.  
- Select your USB from the list.  

⚠️ **Note:** The USB will be formatted in the next step.

---

## 📀 Step 3: Add Windows 10 Home
- ✅ Check: **Auto format it with FBinst**  
- ✅ Select: **FAT32** (best for modern UEFI systems)  
- Select ISO: **Windows Vista/7/8/10/Server 2008/2012 based ISO**  
- Browse and choose your **Windows 10 Home ISO**  
- Set custom menu name:  
  - Folder name: `winH`  
  - Menu name: `Win10 Home`  
- Click **GO** → Wait for “Job done”

---

## ➕ Step 4: Add Windows 10 Pro
- ❌ Uncheck: **Auto format it with FBinst**  
- Select **Windows 10 Pro ISO**  
- Enable custom menu names:  
  - Folder name: `winP`  
  - Menu name: `Win10 Pro`  
- Click **GO** → Wait for “Job done”

---

## ➕ Step 5: Add Windows 11 Pro
- ❌ Keep **Auto format unchecked**  
- Select **Windows 11 Pro ISO**  
- Set custom menu names:  
  - Folder name: `win11P`  
  - Menu name: `Win11 Pro`  
- Click **GO** → Wait until finished

---

## ✅ Final Result
Your USB drive is now ready with:
- 🟦 **Windows 10 Home**  
- 🟦 **Windows 10 Pro**  
- 🟦 **Windows 11 Pro**

---

## 💻 How to Use
1. Restart your PC.  
2. Boot from USB (usually **F12**, **F11**, or **Esc**).  
3. Select your desired OS from the menu.  

---


