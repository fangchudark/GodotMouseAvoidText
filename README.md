# MouseAvoidText
一个基于 Godot 4 C# 的自定义控件，支持文字避让鼠标效果，可用于制作有趣的交互文本。


## 功能简介
- 支持多行文本显示

- 支持自定义字体、字号、颜色

- 支持水平/垂直对齐与 Fill 模式

- 支持设置鼠标避让半径、最大偏移量、平滑系数

- 文字会根据鼠标位置动态避让，带有平滑动画

## 使用方法
将 [MouseAvoidText.cs](/MouseAvoidText.cs) 脚本添加到 Godot 工程中。

在场景中添加一个 `MouseAvoidText` 节点。

在 Inspector 面板中设置文本内容、字体、字号、颜色等参数。

运行项目，即可看到文字会根据鼠标位置动态避让。

## 属性说明
- `Text`：显示的文本内容，支持多行。

- `Language`：文本语言设置（如 "en"、"zh"）。

- `HorizontalAlignment`：水平对齐方式（依据控件大小）（Left/Center/Right/Fill）。

- `VerticalAlignment`：垂直对齐方式（依据控件大小）（Top/Center/Bottom/Fill）。

- `Font`：自定义字体资源。未设置时使用默认字体。

- `FontSize`：字体大小。

- `FontColor`：字体颜色。

- `AvoidRadius`：鼠标避让半径，单位为像素。

- `MaxOffset`：最大避让偏移量，单位为像素。

- `SmoothFactor`：避让动画的平滑系数，数值越大动画越快。

## 依赖
`Godot 4.4+ (Mono/C#)`

`.NET 8.0`

## 许可证

`MIT License`