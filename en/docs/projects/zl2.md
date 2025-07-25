# Zalith Launcher 2

**Zalith Launcher 2** is a newly designed launcher for **Android devices** tailored for [Minecraft: Java Edition](https://www.minecraft.net/). The project uses [PojavLauncher](https://github.com/PojavLauncherTeam/PojavLauncher/tree/v3_openjdk/app_pojavlauncher/src/main/jni) as its core launching engine and features a modern UI built with **Jetpack Compose** and **Material Design 3**.

::: warning Reminder
This project is completely separate from [ZalithLauncher](/en/docs/projects/zl1).  
The project is currently in early development, with features continuously being added. Feel free to follow updates on [Github](https://github.com/ZalithLauncher/ZalithLauncher2)!  
:::

## 📅 Development Progress

Below is the current plan and status of feature modules.

### ✅ Completed Features

* 🟢 Launcher core framework (themes, animations, settings, etc.)  
* 🟢 Game version download and installation  
* 🟢 Launch and render Minecraft game  
* 🟢 Control modes: virtual mouse pointer / physical mouse & keyboard / gesture control  
* 🟢 Version management: version list, overview, configuration  
* 🟢 Custom game installation directory  
* 🟢 Account system: Microsoft OAuth login, offline accounts, authentication server support  
* 🟢 Java environment management  

### 🛠️ In Development / Planned Features

* 🟡 Full control system (custom control layouts, control layout management, etc.)  
* 🟡 Game version download extensions:
  - 🟡 Install OptiFine with OptiFabric and Fabric
  - 🟡 Install Fabric with the Fabric API mod
  - 🟡 Install Quilt with the Quilted Fabric API mod
* 🟡 Modpack download and automatic installation  
* 🟡 Mod download and automatic installation  
* 🟡 Resource pack download and automatic installation  
* 🟡 Save file download and installation  
* 🟡 Shader pack download and automatic installation  
* 🟡 Content manager: mods / resource packs / saves / shaders management UI  
* 🟡 Gamepad support  

## 🌐 Language and Translation Support

Zalith Launcher 2 currently provides support for the following two languages:

* **English** (default)  
* **Simplified Chinese**  

These two languages are **officially maintained and guaranteed complete** by Zalith Launcher 2.  
Community contributions for other languages are welcome, but please note the following:

### 📌 Why only English and Simplified Chinese?

* Zalith Launcher 2 targets a **global user base**, so English is the default interface language. However, since the developer is not a native English speaker, English translations rely heavily on AI assistance and may contain minor inaccuracies.  
* The developer [@MovTery](https://github.com/MovTery) is Chinese and ensures the quality and completeness of the **Simplified Chinese** translation.  
* Due to limited manpower, the completeness of other language translations cannot be guaranteed and depends on community contributions.

### ✍️ How to participate in translations?

If you want to add support for your native language in Zalith Launcher 2, please submit translation files via Pull Requests. See details here:  
[Github#Language and Translation Support](https://github.com/ZalithLauncher/ZalithLauncher2/blob/main/README_ZH_CN.md#-%E8%AF%AD%E8%A8%80%E4%B8%8E%E7%BF%BB%E8%AF%91%E6%94%AF%E6%8C%81)

We plan to open a Weblate project in the future to make it easier for translators to contribute!

## 👨‍💻 Developer

Zalith Launcher 2 is currently independently developed by [@MovTery](https://github.com/MovTery).  
Suggestions and issue reports are welcome. Due to limited personal resources, some features may be implemented slowly—thank you for your understanding!

## 📜 License

Zalith Launcher 2 follows the **[GPL-3.0 license](https://github.com/ZalithLauncher/ZalithLauncher2/blob/main/LICENSE)** open source license.
