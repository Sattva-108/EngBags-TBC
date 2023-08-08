# EngBags

## Modifications by Sattva: <br>
- **Fixed** **dropdown** conflict with Zygor 3.3.5 backport.<br>
- **Added** button **"R"** - **Reset New Items**.<br>
- **Auto-open** bag, when talking to banker.<br>
- Enable **mouse wheel** in advanced configuration window.


**Shaman bag screenshot**

![img](https://imgur.com/zQmKP6A.jpg)

**Rogue bag screenshot**

![img](https://imgur.com/JzpVMVG.jpg)


## FAQ

**Q:** I have a non-English WoW client. Why don't I get similar categorization results as in your screenshots/video?<br>
**A:** EngBags' categorization relies heavily on string search patterns, thus being localization dependent. It's the foundation of how the addon works. I could add localization handling for other languages, but I'd need input.

**Q:** I've updated to a newer version, but item list categorization updates have no impact?<br>
**A:** After updating, delete your setting files: \WTF\Account\ACCOUNTNAME\SavedVariables\EngBags.lua and EngBags.lua.bak


## Modifications by [Baroque](https://github.com/Brqje) - 2019 :

- Modified OpenAllBags hook to allow Blizzard "Open All Bags" keybind to actually toggle, instead of just open bags (similar to default UI behaviour)
- Modified default settings: columns from 9 to 10
- Modified default color settings: background and borders from blue to dark gray
- Modified categorization groups
- Modified categorization string search patterns
- Added nearly 400 items to specifically categorize (default override)

