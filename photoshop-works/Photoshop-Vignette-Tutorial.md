# Photoshop Vignette Tutorial

> Goal: Create a soft, natural vignette effect where the center of the image stays bright and the edges darken to draw focus.

A vignette in Photoshop is achieved by:
- Creating a black overlay layer
- Using a **layer mask** to control which parts of the black layer are visible
- Typically, the **center is clear**, and the **edges fade to dark**
- Feathering the selection ensures a **soft transition**

## Full Workflow

### Step 1: Create the Vignette Layer

1. Open your image in Photoshop.
2. In the Layers panel, click the “New Layer” button +.
3. Name this layer `Vignette`.
4. With this layer selected, go to:
   - `Edit` → `Fill` → Contents: **Black**
   - Click `OK`

### Step 2: Create the Elliptical Selection

5. Select the **Elliptical Marquee Tool** from the toolbar (left-hand side).
6. Drag an ellipse over the area you want to stay **bright** (usually the subject or center).
7. Go to `Select` → `Inverse` (so the **edges** are now selected).
8. Then `Select` → `Modify` → `Feather`  
   - Recommended feather radius: **80 to 200 px** depending on image size.

### Step 3: Add a Layer Mask Based on the Selection

9. Ensure the `Vignette` layer is selected and the selection (marching ants) is still active.
10. Click the `Add Layer Mask` button at the bottom of the Layers panel (white square with a hole).

> This will apply the selection as a **gradient vignette mask** on the black layer. The center will appear bright, while the edges fade to black.

### Step 4: Fine-Tune the Vignette

11. With the `Vignette` layer selected, adjust its **Opacity** in the Layers panel:
    - Suggested range: **20% to 50%**
12. Optionally, apply `Filter` → `Blur` → `Gaussian Blur` on the **layer mask** for even smoother transitions.

## Final Layer Structure

Vignette (Black Fill + Mask)
↑ Layer mask shows feathered ellipse
Main Image (Background Layer)

---

# Photoshop 暗角添加教程

> 目标：给图像添加一个「中间亮、四周暗」的聚焦式暗角效果，适合人物照、风景照等营造氛围。

Photoshop 中的暗角，本质是：
- 建一个黑色图层
- 用图层蒙版控制“哪些区域透光”
- 通常是中间透光、四周遮暗
- 为了自然过渡，要对选区进行“羽化”

## 完整操作流程

### Step 1：创建暗角图层

1. 打开你的图像文件。
2. 在图层面板中点击下方【新建图层】按钮 +
3. 命名图层为 `暗角`。
4. 选中该图层，点击顶部菜单栏：
   - `编辑` → `填充` → 内容：**黑色**
   - 点【确定】

### Step 2：创建椭圆选区

5. 在左侧工具栏选择【椭圆选框工具（Elliptical Marquee Tool）】。
6. 在画布中心拖拉一个椭圆（覆盖你想保留亮度的区域）。
7. 顶部菜单 → `选择` → `反选`
8. 接着 → `选择` → `修改` → `羽化`
   - 羽化值建议设置为：**80 ~ 200 px**（分辨率高用大一点）

### Step 3：应用图层蒙版

9. 确保你还选中的是 `暗角` 图层，且选区仍处于激活状态（蚂蚁线还在转动）。
10. 在图层面板下方，点击【添加图层蒙版】按钮（白色小方块带圈图标）。

> 此时暗角图层会添加一个「灰黑羽化的椭圆蒙版」，中间透光、四周发暗。

### Step 4：微调透明度（让暗角更自然）

11. 选中 `暗角` 图层，调节图层的不透明度为：
    - **20% ~ 50%** 之间
12. 如觉得暗角边缘仍不够柔和，可对该图层蒙版使用：
    - `滤镜` → `模糊` → `高斯模糊`

## 最终图层结构

暗角（填黑 + 蒙版）
↑ 图层蒙版呈灰黑椭圆
主图层（背景图像）



