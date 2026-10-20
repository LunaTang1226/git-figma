# Figma 学习笔记：基础界面与图层逻辑

## 一、 认识 Figma 首页与文件类型
*   **左侧功能栏**：团队和项目（学会管理好自己的设计文件）。
*   **核心文件类型**：
    *   **Design (设计)**：最常用，用于 UI 设计。
    *   **FigJam**：在线协作白板（用于团队头脑风暴、流程设计）。
    *   **Slides**：幻灯片（用于汇报、产品演示）。
    *   **Buzz**：创建海报/广告宣传单。
    *   **Make**：AI 工具。
    *   **Site**：做网站（桌面端、移动端）。

## 二、 Design 界面核心快捷键与视图
*   **放大/缩小**：`Ctrl + 鼠标滚轮`，或 `Shift + "+" / "-"`
*   **左右/上下平移画布**：`Ctrl + 空格 + 鼠标左键拖拽`
*   **界面设置**：右上角可进行各项界面设置。

## 三、 顶部主菜单 (菜单栏)
1.  **Actions**：快捷操作，可搜索插件。
2.  **File**：保存本地副本 (Save local copy)、版本历史 (Show version history)。
3.  **Edit**：撤销 (Undo, `Ctrl+Z`)、重做 (Redo)、复制为 PNG (Copy as PNG)。
4.  **View (视图)**：
    *   Pixel grid (像素网格)：`Shift + '` 建议开启。
    *   Rulers (标尺)：`Shift + R`，拖拽可生成参考线，`Shift + R` 隐藏参考线。
    *   Pixel preview (像素预览)：检查元素对齐精度。
    *   Minimize UI (最小化侧边栏)：`Shift + Ctrl + \`
    *   Show/hide UI (演示模式)：`Ctrl + \`
5.  **Arrange (布局)**：上下左右对齐、像素取整 (Round to Pixel)。
6.  **Plugins**：插件（辅助设计工具）。
7.  **Widget**：嵌入画布的可交互小组件。
8.  **Preferences (偏好设置)**：
    *   Snap to geometry：对齐吸附。
    *   Highlight layers on hover：hover 时高亮图层。
    *   Rename duplicated layers：复制图层时自动重命名。
    *   Show dimensions on layers：显示尺寸。
    *   Use number keys for opacity：用数字键控制不透明度。

## 四、 右侧边栏与设计面板
*   **顶部**：头像（Spotlight me 跟随展示设计）、播放按钮（预览）、下拉箭头（选择设备预览）。
*   **两个 Tab 栏**：`Design` (设计) 与 `Prototype` (原型交互)。
*   **主题与颜色配置**：sRGB（多设备通用，色域偏小）、Display P3（苹果设备）。
*   **Nudge (微调)**：设置小步长（上下左右键）与大步长（Shift+方向键），`Ctrl+方向键` 改变尺寸。
*   **Libraries (资源库)**：管理、共享可复用元件，保持团队一致性。

## 五、 形状绘制工具与属性
*   **矩形**：快捷键 `R`。
    *   `Shift`：等比例缩放。
    *   `Alt`：从中心缩放（或只调整一个圆角）。
    *   `Shift + 旋转`：15度角递增。
*   **椭圆、多边形、星形**：基础图形绘制。
*   **右侧属性设置**：
    *   **位置 (Position)**：X/Y 轴坐标，对齐方式（Tidy up 整理间距）。
    *   **布局 (Layout)**：Width (宽)、Height (高)、锁定比例。
    *   **外观 (Appearance)**：不透明度、圆角半径、Corner smoothing (圆角平滑度)、混合模式。

## 六、 填充与描边 (Fill & Stroke)
*   **Fill (填充)**：
    *   纯色、渐变（线性、径向、角度、菱形）。
    *   可设置颜色节点，拖动调整位置。
    *   支持多层填充，调整叠加顺序。
*   **Stroke (描边)**：
    *   粗细、位置（内部 Inside、居中 Center、外部 Outside）、端点样式。
    *   高级设置：虚线（Dash 越大，间隔越长）、转角（直角、圆滑）。
    *   线条与箭头：线条本质是描边，可设置起点与终点样式。
