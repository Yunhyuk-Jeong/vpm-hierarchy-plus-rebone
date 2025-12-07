# **Hierarchy Plus Rebone**

### _A modernized, refactored version of the discontinued HierarchyPlus tool_

`Hierarchy Plus Rebone` is a rebuilt and fully namespaced-safe version of the original **HierarchyPlus** tool, which is no longer maintained.  
This version restores compatibility with modern Unity (2022.3+), updates menu paths & namespaces, and packages everything cleanly for VPM/VCC usage.

✔ 100% Editor-only tool  
✔ No runtime footprint  
✔ GPL-3.0 compliant (original license preserved)

---

## 🔧 **Features**

Hierarchy Plus Rebone enhances Unity's default Hierarchy window with:

### 🎨 **Visual Improvements**

-   Colored rows based on transform depth
-   Colored icons for active/inactive GameObjects
-   Optional style presets

### 🧭 **Structural Indicators**

-   Guide lines for parent/child indentation
-   Clearer hierarchy depth visualization
-   Foldout styling

### 🗂 **Content Enhancements**

-   Component icons in the hierarchy
-   Tag & Layer labels
-   Toggleable indicators for various states

### 🔍 **Filtering & Tools**

-   Regex-based filtering & comparison (RegexComparison)
-   Quick management tools via toolbar
-   Saved settings system with persistent configuration

### 🧱 **Fully modular code structure**

Rebuilt under the namespace:

```
IyanKim.HierarchyPlusRebone
```

This prevents conflicts with the abandoned original version.

---

## 🚀 Installation (VPM / VCC)

### **Add repository to VCC**

Click:

👉 **[Add Iyan-Kim VPM Repository to VCC](vcc://vpm/addRepo?url=https://raw.githubusercontent.com/Yunhyuk-Jeong/iyan-vpm/main/vpm.json)**

Or add manually:

```
https://raw.githubusercontent.com/Yunhyuk-Jeong/iyan-vpm/main/vpm.json
```

Then install:

### **Package ID**

```
com.iyankim.hierarchyplusrebone
```

---

## 📁 Repository Structure

```
com.iyankim.hierarchyplusrebone/
  Editor/
    HierarchyPlus.cs
    RegexComparison.cs
    SavedSettings.cs
    StylesContainer.cs
    ColoredScope.cs
    ContentContainer.cs
    IndentScope.cs
    com.iyankim.hierarchyplusrebone.Editor.asmdef
LICENSE (GPL-3.0)
README.md
package.json
```

---

## 🛠 Changes From Original HierarchyPlus

### ✔ Updated Namespace

```
DreadScripts.HierarchyPlus
→
IyanKim.HierarchyPlusRebone
```

### ✔ Updated Menu Path

```
DreadTools/HierarchyPlus
→
IyanTools/Hierarchy Plus Rebone
```

### ✔ Updated PRODUCT_NAME

Used across UI & editor window titles.

### ✔ Added asmdef

Fully compliant with Unity package format; Editor-only isolation.

### ✔ Reformatted for VPM distribution

Package.json included & repository structure aligned.

### ✔ Removed dependencies on the original asset

Fully standalone.

---

## 📜 License

This project is licensed under the **GPL-3.0** license, inherited from the original HierarchyPlus.  
The license file from the original distribution is included in this package.

---

## 🙏 Credits

**Original Author**: _DreadScripts_ (HierarchyPlus)  
**Rebone & Rebuild**: _Iyan-Kim_  
**Purpose**: Preserve functionality of a discontinued but highly useful Unity extension.

---

## ❤️ Support / Feedback

If you have feature requests or bug reports, feel free to open an issue in this repository!
