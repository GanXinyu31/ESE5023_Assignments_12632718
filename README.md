# ESE5023\_Assignments\_12632718



HW3 from Lijianghai（47/50）

1\.缺测判断 `xch4.where(xch4 < 1e10)`，阈值写错，文件填充值是 1e20（-1p）



2.`anom.mean(dim=\["lat", "lon"])` 直接算术平均，没有纬度余弦加权（-2p）



3\.建议对数据进行缺测质控，全部是单点 / 格点统计，没有区域面积加权；直方图直接 flatten 三维数组，包含大量海洋低值格点



