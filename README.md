# Project Shadow

> 一个探索动态阴影与空间交互机制的个人游戏原型项目。

## 项目简介

Project Shadow 是一个基于 Unreal Engine 开发的个人游戏原型项目，主要探索动态光照、阴影遮挡、物理碰撞和场景交互之间的结合。

本仓库是私有项目的公开展示快照，主要用于展示项目开发进度、运行效果和部分可公开的技术实现，不代表完整项目内容。

## 项目展示

<!-- 在这里放置项目封面图或代表性截图 -->

## 演示视频

### 动态阴影交互

展示动态光源、阴影遮罩生成以及阴影物理碰撞之间的完整交互流程。

视频重点包括：

- 动态光源移动和阴影变化
- 阴影遮罩的实时生成与更新
- 阴影区域参与物理碰撞检测
- 角色与阴影区域之间的交互效果

https://github.com/user-attachments/assets/55b69a0d-40d9-40a0-90d1-addba9d616be

<!-- 在这里添加演示视频链接或视频封面 -->

### 相机遮挡处理

展示玩家移动过程中，相机视野与场景遮挡效果之间的联动。

视频重点包括：

- 相机根据玩家位置进行实时跟随
- 根据玩家在屏幕空间中的位置更新遮挡参数
- 场景材质根据遮挡参数动态调整显示效果
- 在复杂场景中保持玩家区域的可见性

https://github.com/user-attachments/assets/6ddc432a-4a1d-4010-87af-02fcfa5212a0

<!-- 在这里添加演示视频链接或视频封面 -->

## 视觉与交互亮点

- 动态光源驱动的实时阴影变化
- 阴影遮挡关系的实时更新
- 阴影区域参与角色物理交互
- 场景物体对光照和阴影的动态反馈
- 相机视野与场景遮挡效果的联动

## 算法与技术实现

- 基于二维离散栅格的阴影遮罩构建
- 基于碰撞法线聚合的接触面计算
- 基于重叠区域的碰撞修正与脱离处理
- 基于动态生成阴影遮罩的物理碰撞检测
- Mask 边界裁剪和越界采样处理
- 通过材质参数驱动场景遮挡显示

## 我的工作

- 独立设计并实现动态阴影交互原型
- 设计阴影遮罩的数据结构和生成流程
- 实现阴影遮挡、碰撞检测和碰撞修正逻辑
- 实现动态光源和阴影接收平面
- 实现场景遮挡和材质参数更新
- 搭建开发场景与调试可视化资源
- 负责功能验证、问题定位和效果迭代

## 开发进度

| 功能模块     | 当前状态 |
| ------------ | -------- |
| 动态光照     | 原型完成 |
| 阴影遮罩     | 原型完成 |
| 阴影物理碰撞 | 开发中   |
| 碰撞修正     | 开发中   |
| 相机遮挡处理 | 开发中   |
| 场景交互     | 计划中   |

## 后续计划

- 优化阴影遮罩的生成和更新性能
- 完善复杂遮挡情况下的碰撞处理
- 增加更多阴影交互机制
- 扩展开发场景和可视化效果
- 持续上传项目运行演示视频

---

# English Version

> A personal game prototype exploring dynamic shadows and spatial interaction.

## Overview

Project Shadow is a personal game prototype built with Unreal Engine. The project explores the combination of dynamic lighting, shadow occlusion, physics collision, and scene interaction.

This repository is a public showcase snapshot of a private project. It is mainly used to present development progress, runtime demonstrations, and selected technical implementations. It does not contain the complete project.

## Showcase

<!-- Add a project cover image or representative screenshot here -->

## Demo Video

### Dynamic Shadow Interaction

This demo presents the complete interaction flow from dynamic lighting to shadow mask generation and shadow-based physics collision.

The video focuses on:

- Dynamic light movement and shadow changes
- Runtime shadow mask generation and updates
- Physics collision based on shadow regions
- Interaction between the character and shadow regions

https://github.com/user-attachments/assets/55b69a0d-40d9-40a0-90d1-addba9d616be

<!-- Add the demo video link or thumbnail here -->

### Camera Occlusion

This demo shows how camera positioning and scene occlusion interact while the player moves through the environment.

The video focuses on:

- Real-time camera following based on the player's position
- Updating occlusion parameters from the player's screen-space position
- Dynamically adjusting scene visibility through material parameters
- Preserving visibility around the player in complex scenes

https://github.com/user-attachments/assets/6ddc432a-4a1d-4010-87af-02fcfa5212a0

<!-- Add the demo video link or thumbnail here -->

## Visual and Interaction Highlights

- Real-time shadow changes driven by dynamic lighting
- Runtime updates of shadow occlusion relationships
- Physics interaction based on shadow regions
- Dynamic visual feedback from scene objects
- Interaction between camera visibility and scene occlusion

## Algorithms and Technical Implementation

- 2D discrete grid-based shadow mask construction
- Contact surface calculation based on collision normal aggregation
- Overlap-based collision correction and depenetration
- Physics collision detection based on dynamically generated shadow masks
- Mask boundary clipping and out-of-bounds sampling handling
- Material parameter-driven scene occlusion rendering

## My Contributions

- Independently designed and implemented the dynamic shadow interaction prototype
- Designed the shadow mask data structure and generation workflow
- Implemented shadow occlusion, collision detection, and collision correction
- Implemented dynamic lighting and shadow receiver behavior
- Implemented scene occlusion and material parameter updates
- Built development scenes and debug visualization resources
- Performed functional validation, debugging, and iteration

## Development Progress

| Feature                  | Status             |
| ------------------------ | ------------------ |
| Dynamic Lighting         | Prototype Complete |
| Shadow Mask              | Prototype Complete |
| Shadow Physics Collision | In Progress        |
| Collision Correction     | In Progress        |
| Camera Occlusion         | In Progress        |
| Scene Interaction        | Planned            |

## Roadmap

- Optimize shadow mask generation and update performance
- Improve collision handling in complex occlusion cases
- Add more shadow-based interaction mechanics
- Expand development scenes and visualization features
- Continue publishing runtime demonstration videos