# 🌌 Nightfall

**Nightfall** is a Roblox script that started back in early 2023 as a free single-game script made specifically for *Lumber Tycoon 2 🌳*.  
Over the course of a year and a half, it grew into one of the most recognized scripts for Lumber Tycoon 2.  
After a break to work on other projects, **Nightfall is officially back** as a reboot.

---

## 📜 Project History
Nightfall began as a passion project in early 2023 and quickly gained recognition as one of the best free scripts in the LT2 community.  
In mid-2024, I began developing a new premium project called **Astral**, which included a custom website (*astralhub.org*).  
However, Astral didn’t gain the same traction, so I brought back Nightfall as a **free reboot**, continuing its legacy with new updates.

---

## 👥 Credits / Collaborators
- **Scripts:** [@uhhwhatever (Ecstasy) / Nix](https://discord.com/users/1055337846657007648) — Solo Developer from **v1.0 to current**.  
- **UI Library & Assistance:** [@silentben8x](https://discord.com/users/865599038954668042) — Joined to help on **v2.0 to v2.10.5** with UI improvements and added features.  
- **Beta Testers:** N/A

---

## ⚠ Legal Notice
**Permission**  
>Permission is granted to use, copy, and modify Nightfall and its documentation **for personal, educational, and research purposes**, without fee or signed agreement, provided that this notice and the following paragraphs appear in all copies and modifications. *(Jan. 2023)*  

**Restrictions**  
> Commercial use, resale, or redistribution of Nightfall or any of its components (including obfuscated code) is strictly prohibited unless explicitly authorized by the original author (Nix).**
Nightfall is distributed for free unless stated otherwise, and no third-party reseller is permitted to charge for it under any circumstances.  

**Disclaimer**  
> Nightfall is provided **as-is and as-available**, with no representations or warranties of any kind, whether express, implied, statutory, or other.  
This includes, without limitation, warranties of title, merchantability, fitness for a particular purpose, non-infringement, absence of latent defects, accuracy, or the presence/absence of errors, whether known or discoverable.  

**Liability**  
> To the fullest extent possible, the author shall not be liable on any legal theory (including negligence) for any direct, indirect, special, incidental, consequential, punitive, or exemplary damages.  
This includes, but is not limited to, **loss of data, profits, or business interruption**, arising from the use, misuse, or inability to use Nightfall, even if the author has been advised of such risks.

---

## ❤️ Special Thanks
> *Nightfall was built by the community, for the community. Thank you to everyone who supported it from the start.*

---
## 🎨 UI Themes

Nightfall supports customizable UI themes to match your preferences.

### **Installing a Preset Theme**
1. Locate your executor's **workspace folder**.
2. Open the **`Nightfall-Theme.json`** file.
3. Choose your desired theme from [this list](https://github.com/yourpov/Nightfall/tree/main/UIThemes).
4. Replace the current `Nightfall-Theme.json` with the theme you selected.
5. Save the file and close it.
6. Re-execute the script to apply the theme.

---

### **Restoring the Default Theme**
To restore the default theme, delete the **`Nightfall-Theme.json`** file from the workspace folder and re-execute.

---

### **Customizing Themes**
**Q:** *How can I customize Nightfall's theme to my preference?*  
**A:** Open `Nightfall-Theme.json` and modify the **RGB values** for the UI elements (accent, main, secondary, and text colors).  
For example:
- Red: `255, 0, 0`
- Green: `0, 255, 0`
- Blue: `0, 0, 255`

**Default Theme:**
```json
{
  "accent": "31, 31, 31",
  "textcolor": "225, 225, 225",
  "main": "35, 35, 35",
  "secondary": "40, 40, 40"
}
```
You can use an [RGB color picker](https://rgbcolorpicker.com/) to get the colors you want
Simply remove the rgb() wrapper. For example: `rgb(68, 118, 186)` → `68, 118, 186`
