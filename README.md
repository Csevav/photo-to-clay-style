# Photo to Clay Style

[English](README.en.md)

将用户上传的照片转换成柔和、圆润、具有手工质感的 clay 立体模型。

这是一个 Codex Skill，适合把店铺、建筑、街景、物品、宠物或人物照片重新表现为可爱的 clay 微缩模型，同时尽量保留原照片的主体、构图和识别特征。

## 示例

以下示例均由本 Skill 的照片转换流程生成。它们展示了不同建筑照片的 clay 模型效果，不代表照片中不可见结构的真实还原。

### Costa Coffee

![Costa Coffee clay 模型](examples/costa-coffee.jpg)

咖啡店门面转换为可爱的 clay 收藏模型，并放置在简洁的白色圆形底座上。

### 爷爷不泡茶

![爷爷不泡茶 clay 模型](examples/no-yeye-no-tea.jpg)

保留蓝色立面、胡子标志和植物层次的 clay 微缩模型。

### Serene Hill 山墨堂

![Serene Hill 山墨堂 clay 模型](examples/serene-hill.jpg)

保留悬挑屋顶、夜景灯光和玻璃体块的 clay 建筑模型。

### 天坛

![天坛 clay 模型](examples/temple-of-heaven.jpg)

将屋顶层叠、彩色装饰、台基和中轴线转换为可爱的 clay 纪念模型。

## 能做什么

- 将照片转换为 handcrafted clay / polymer-clay miniature
- 保留主体轮廓、关键物体、相对布局和可读招牌
- 使用接近正面观看的平行透视，保留自然纵深
- 生成柔和的哑光材质、圆润边缘、手工捏塑细节和产品摄影效果
- 可选添加独立的收藏品展示底座

## 可选展示底座

默认不添加底座。用户选择收藏模型或产品展示效果时，可以添加略大于模型整体的薄型圆形底座。

底座可使用干净的银色钛金属或不锈钢材质，并采用精密、均匀、无污渍的高级产品质感。标题和收藏编号应直接蚀刻在底座前沿，不使用厚重台座、外挂铭牌、纸盒或透明包装。

## 使用方式

在 Codex 中显式调用：

```text
Use $photo-to-clay-style to transform the uploaded photo into a clay miniature model.
```

也可以直接用中文描述需求：

```text
把这张照片转换成可爱的 clay 微缩模型，保留原来的构图，并使用平行透视。
```

如果需要收藏展示效果：

```text
把这张照片转换成 clay 收藏模型，并添加一个略大于模型的薄型圆形银色金属底座。
```

## 视觉方向

- 圆润、柔和、略带手工不规则感
- 哑光或轻微缎面 clay 材质
- 温暖的工作室灯光和柔和接触阴影
- 清晰的分层结构和适度细节
- 平行透视：接近正面观看，但保留自然空间纵深

避免使用完全正交投影、明显斜拍、过度广角畸变、金属 CGI 光泽、扁平插画和无关背景杂物。

## 项目结构

```text
photo-to-clay-style/
├── SKILL.md
├── LICENSE
├── README.md
├── README.en.md
├── examples/
│   ├── costa-coffee.jpg
│   ├── no-yeye-no-tea.jpg
│   ├── serene-hill.jpg
│   └── temple-of-heaven.jpg
└── agents/
    └── openai.yaml
```

## 限制

这个 Skill 依赖当前环境可用的图像生成或图像编辑能力。单张照片可以生成风格化的合理推测，但照片中不可见的侧面、背面或室内结构不一定是真实还原。

照片中的小字号文字可能无法逐字准确保留；Skill 会尽量保留其位置、层级和视觉形状，避免凭空生成确定内容。

## License

MIT License，详见 [LICENSE](LICENSE)。
