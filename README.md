# Bedrock Model + 基岩模型+
[中文](README.md) | [English](README.en.md)  
[Gitee](https://gitee.com/anecansaitin/bedrock-model-plus) | [Github](https://github.com/AnECanSaiTin/Bedrock-Model-Plus?tab=readme-ov-file)
### 介绍
我的世界基岩模型拓展规范  
不修改原有模型、动画数据结构，添加拓展内容。
### 特性（待定）
**变量输入：** *在动画中添加变量，可在代码中获取值。支持绑定为指定骨骼以获取骨骼对应属性。*  
**骨骼（组）绑定变更：** *在动画中可变更骨骼的父骨骼。*  
**分离模型绑定插槽：** *通过Slot与Plug为模型设置绑定关系，实现模型的分离。如实体手持武器，只需给实体设置slot，武器设置plug，渲染时会将武器附着到slot对应位置上。*
***
[动画示例](animation.json) | [模型示例](model.json)