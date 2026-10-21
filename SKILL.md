---
name: artifact-template-rubber-stamp-photo-poster-airy
description: "Create an image using the Rubber Stamp Photo Poster Airy template and its retained reference file. Use when the user selects this template, names Rubber Stamp Photo Poster Airy, or explicitly invokes $artifact-template-rubber-stamp-photo-poster-airy. Create photo-over-print comparison posters with ivory paper, handmade rubber stamp textures, short English poetry, and the approved airy 90 percent design scale."
---

# Rubber Stamp Photo Poster Airy

Create an image from this template. Keep the reference file unchanged.

## Workflow

1. Read `artifact-template.json` and resolve its paths relative to this skill directory.
2. Invoke $imagegen with the retained PNG as a reference image and the user's requested content as the edit or generation brief.
3. Treat the user's prompt and available sources as the content input. Do not invent factual claims merely to fill the composition.
4. Preserve the reference's visual language unless the user explicitly requests a deviation.
5. Visually inspect the generated image for fidelity and defects, then return the final image.

## Fidelity

Preserve the reference image's composition, visual hierarchy, typography, material treatment, and print texture. Derive the palette and subjects from the new source photo; do not copy the reference's lake, tree, or poem into unrelated scenes.

User instructions control requested content and explicit deviations. The retained reference controls layout and formatting where the user has not requested a change.

## 固定版式与最新比例

- 输出一张竖版上下对照海报。默认宽高比 2:3，上下区域高度大致各半、同宽、直接衔接，无分隔线、标签和外框。
- 上半部分展示用户本次提供的原照片，保持原场景、人物、物件、摄影质感和颜色。等比例适配，必要时轻微裁切保留主体，不拉伸。不要把模板内的示范照片当成本次原图。
- 下半部分为温暖象牙白纸底上的手工版画，带细腻纸纤维；四周留白，插画边缘自然融入纸面。
- **以 assets/reference.png 为最新、已确认的布局比例。** 用户确认的是第一版设计宽、高分别缩至 90% 的版本，插画与诗句作为整体缩放，上半照片及上下分区不缩放。不是缩至纸面面积的 90%，也不是此前的 80% 版本。
- 模板参考已经完成 90% 缩放：直接匹配它的占比，不要每次使用再乘 0.9。新图设计组宽度约占下半部分宽度的 80–85%，高度约占下半部分高度的 70–75%；这些是视觉目标而非裁切要求。上下左右均有明显留白，底部保留舒适空隙。
- 插画与诗句形成松散的整体，主体大致居中，可随景物调整重心。保留小字号诗句，避免大标题占据留白。

## 画风与内容

从新照片提取标志性主体、轮廓、空间关系和代表色；简化杂乱背景，允许凝练重组。用少量平面色块、深色剪影和简练线条表现景物。橡皮章与木刻版画结合少量干刷和撕纸拼贴感；边缘粗糙不规则、油墨颗粒明显、斑驳缺墨露白，可有细微刻痕与轻微套印偏移。远景浅淡，避免光滑矢量、三维渲染、照片滤镜感及强烈渐变。

从照片选择约 3–5 种复古、克制的颜色，保留关键点缀色；不将金黄与蓝色固定用于所有照片。天空、雪地、雾气等尽量借纸张本色表达。插画无需填满纸面。

根据新照片情绪原创一句含蓄的英文短诗，分 1–2 行，以小字号深灰或黑色经典衬线字体、略宽字距，安排在下半部分合适留白处。用户指定文字时原样使用。无标志、署名、水印。

## 可复用生成简报

“参考模板的版式与版画质感，用本次照片制作竖版上下对照海报：上半保留本次原照，下半是象牙白纸底的极简橡皮章与木刻版画。提炼照片的辨识性景物，以少量不规则色块、剪影、粗糙刻印和斑驳缺墨表现，提取照片的 3–5 种代表色。匹配模板已确认的 90% 版本的设计占比与四周留白，不再次缩小；插画及英文短诗组成松散整体，纸面宽松。添加符合本次照片意境的一至两行小字号衬线英文诗。不要复制示例场景与诗句，不添加边框、标签、标志、水印。”

## 交付检查

查看生成结果，确认：上方对应本次原照；上下约各半；下方具有真实印刷颗粒与不规则边缘；设计占比接近保留参考，且未重复缩小；留白舒适；英文完整清晰；无水印。比例调整只能修改下半设计组，除非用户同时要求改变分区或原照片。
