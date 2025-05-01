 # 🎮 Unity Ads Plugin for Godot (Android)

Integrate **Unity Ads** into your **Godot** Android projects seamlessly with this easy-to-use plugin. Whether you're showing **rewarded videos**, **interstitials**, or **banner ads**, this plugin gives you full control with minimal setup and supports signals for all major ad events.

---

## ✅ Features

- Support for **rewarded**, **interstitial**, and **banner ads**
- **Test mode** for safe ad integration
- Exposed methods and **signals** for all ad lifecycle events
- Simple and native Android integration for **Godot Engine**

---

## 🛠️ Installation & Usage

### 1. Download and Install

Download the addon from itch.io - https://gamifiedsoul.itch.io/godot-unity-ads-plugin



### 2. Enable the Plugin

Go to **Project > Project Settings > Plugins**, then enable `GodotUnityAds`.

### 3. Add the UnityAds Node

Add a `UnityAds` node to your scene.

### 4. Configure Test Mode or Real Ads

- To test ads, enable **Test Mode** in the **Inspector**. This automatically uses Unity's test ad IDs.
- To use **real ads**, disable **Test Mode** and enter your actual **Game ID** and **Ad Unit IDs** in the inspector.

### 5. Initialize Unity Ads

In your script, initialize the plugin by calling:

```gdscript
$UnityAds.initialize()



