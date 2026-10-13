蓝红手绘总平面 CAD 转绘

文件
- blue_red_site_plan_mm.dxf：可编辑 DXF，图纸单位为毫米（$INSUNITS=4）。
- blue_red_site_plan_preview.png：DXF 渲染预览。

图层
- A_BUILDING / A_WALL / A_DOOR：建筑与墙线
- A_PAVING / 00_SITE：铺装和场地边界
- L_PLANT：蓝笔植物（每株为独立圆形树冠及枝叶线）
- L_WATER：中央八边形水景/构筑物线
- DIM_RED：红笔尺寸线与尺寸文字
- CENTER / TEXT：中心线与说明文字

转绘说明
1. 蓝色线稿均放在 L_PLANT，红色标注均放在 DIM_RED，便于在 CAD 中单独开关和编辑。
2. 所有坐标以毫米写入 DXF；预览图仅用于核对相对位置和图层颜色。
3. 手写中无法可靠辨认的尺寸保留原读数并加 ?CHECK 标记（7093、472、8819、840、1900 等），没有擅自替换成猜测值。打开 DIM_RED 图层即可复核这些标注。
4. 因原始图片未作为 CAD 底图嵌入，线稿按所给图片的可见相对位置转绘；如需施工级一比一定位，请在 CAD 中将原图作为底图并用现场控制点校核。

DXF 已通过 ezdxf audit 检查：No errors found.
