# Pico Developer
欢迎来到Pico Developer，这里是Pico开发者部门所维护的官方开源示例库。你可以在这里找到基于Pico XR SDK在Unity、Unreal、Native以及WebXR等开发平台上基于相同目标的不同的代码实现，包括基础功能的使用、渲染效果、性能展示、交互范例以及其他的研发资源。我们希望这些示例项目，可以帮助你快速地了解、上手Pico设备的研发工作，我们也会持续地对项目进行维护和更新。

你也可以访问我们的[开发者官网](https://developer.pico-interactive.com/)，获得更多的咨询内容


## SDK & Resources

|Platform |  SDK | Documentation | API Reference|
|  ----   | ---- |      ----     |     ----     |
| Unity   | [Pico Unity Integration SDK](https://developer.pico-interactive.com/sdk?deviceId=1&platformId=1&itemId=12) | [Documentation](https://developer.pico-interactive.com/document/unity)|[XR](https://pdocor.pico-interactive.com/reference/unity/xr/2.05/) [Platform](https://pdocor.pico-interactive.com/reference/unity/platform/1.0/)|
| Unreal  | [Pico Unreal Integration SDK](https://developer.pico-interactive.com/sdk?deviceId=1&platformId=2&itemId=13)| [Documentation](https://developer.pico-interactive.com/document/unreal)|[XR](https://pdocor.pico-interactive.com/reference/unreal/xr/12832/240774/) [Platform](https://pdocor.pico-interactive.com/reference/unreal/platform/1.0/)|
| Native  | [Android Native XR SDK](https://developer.pico-interactive.com/sdk?deviceId=1&platformId=3&itemId=16)| [Documentation](https://developer.pico-interactive.com/docs/native/en/13158/android-native-xr-quickstart/#overview)|[API Reference](https://pdocor.pico-interactive.com/reference/native/xr/2.0.1/)|
| Native  | [OpenXR Mobile SDK](https://developer.pico-interactive.com/sdk?deviceId=1&platformId=3&itemId=11)| [Documentation](https://developer.pico-interactive.com/docs/native/en/13158/openxr-mobile-sdk-overview/#introduction-to-openxr)||



# Unity Sample
Unity Sample 是基于Unity引擎及Pico Unity Integration SDK进行开发的代码示例内容。当前Sample开发使用的Unity版本是 `2020.3 LTS`，但其功能同样可以在 `Unity 2019.4 LTS` 及以上版本实现并运行

## Get Started

基于 Pico Unity Integration SDK 及 Unity Interaction Toolkit 实现的基础场景，包含了SDK的引用、基础配置以及一个接入了头戴和控制器的空白场景，搭建过程请参考[开发文档](https://developer.pico-interactive.com/document/unity)的 **快速开始** 章节

**开发环境**

| Name  | Version    |
| ----  |  ----      |
| Unity Editor | `2020.3.35f` |
| Pico Unity Integration SDK | `2.0.5` |
| XR Interaction Toolkit | `2.1.0` |

[项目地址]()


## Basic Sample

以 Pico Unity Integration SDK 及 Unity Interaction Toolkit 实现的一系列基础功能展示，你需要在你的项目中引入这两个依赖，才可以导入对应的`.unitypackage`并正确运行。你也可以直接基于[Get started]()项目引入package，这是被测试过的

**Sample列表**

| Feature | Description |
| -----   |    ----     |
| Controller   |  Pico控制器及震动的使用方法  |
| UI      |  使用射线与Uinty的UI进行基础交互的方法展示  |
| Interaction |  包含平滑移动、传送及物体抓取、射击的基础交互Sample，基于Unity Interaction Toolkit实现 |


[项目地址]()

## Advanced Sample

这是一系列为不同目的所制作的综合性示例，它们可能包含了渲染、交互及复合功能展示等多方面内容。

### Auto show

包含高精度车辆模型及相关Shader的展示Demo，展示了Pico VR基于高面数模型的渲染能力

**开发环境**

| Name  | Version    |
| ----  |  ----      |
| Unity Editor | `2020.3.35f` |
| Pico Unity Integration SDK | `2.0.5` |

[项目地址|()

