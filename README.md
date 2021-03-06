# tesla_0221_accident
特斯拉河南事故简单分析

## 只列数据，不谈立场
从20210422得到的有速度的数据推算加速度：

| 时间  | 速度（km/h) | 速度(m/s)   | 区间速度差(m/s) | 区间时间差(s) | 区间平均加速度(m/s2) | 区间G值  | 区间平均速度(km/h) | 区间行驶距离（米） | 累积行驶距离（米） | 备注                                                         |
| ----- | ----------- | ----------- | --------------- | ------------- | -------------------- | -------- | ------------------ | ------------------ | ------------------ | ------------------------------------------------------------ |
| 22.36 | 118.5       | 32.91666667 | --              | --            | --                   | --       | --                 | --                 | 0                  | --                                                           |
| 23.38 | 116         | 32.22222222 | -0.694444444    | 1.02          | -0.680827887         | -0.06947 | 117.25             | 33.22083333        | 33.22083333        | 1-2区间(23.17)开始踩刹车                                     |
| 24.4  | 109.5       | 30.41666667 | -1.805555556    | 1.02          | -1.770152505         | -0.18063 | 112.75             | 31.94583333        | 65.16666667        |                                                              |
| 25.41 | 94          | 26.11111111 | -4.305555556    | 1.01          | -4.262926293         | -0.43499 | 101.75             | 28.54652778        | 93.71319444        |                                                              |
| 26.43 | 74          | 20.55555556 | -5.555555556    | 1.02          | -5.446623094         | -0.55578 | 84                 | 23.8               | 117.5131944        | 4-5区间中间段(25.87-26.09)开始ABS介入，自动紧急制动(26.39)介入 |
| 27.45 | 48.5        | 13.47222222 | -7.083333333    | 1.02          | -6.944444444         | -0.70862 | 61.25              | 17.35416667        | 134.8673611        | 5-6区间应为全力刹车状态                                      |


需要原始数据的可以直接点进去下载Excel表格[tesla_accident_0221.xlsx](https://github.com/dadongshangu/tesla_0221_accident/blob/main/tesla_accident_0221.xlsx)。

## 从数据得到的直接结论
假设数据是真实的，单纯从数据里边可以得到：
1. 初始速度的确不慢（118km/h)
2. 车的确是在减速，并不存在踩刹车踩错，踩成电门的情况。
3. 刹车有效果，并未失灵。
4. 刹车效果在全力刹车时（最后一个区间段）为-0.708g，与媒体评测的-1g~-1.2g有差距。

## 基于数据不肯定的其他问题（含我个人的倾向与立场）
1. 数据有效性。我觉得这个大概率不会作假。现在是在放大镜下看特斯拉，作假后果没人敢承担。
2. 的确前期减速较慢，有两种情况：2.1 一开始轻踩刹车，后期才重踩刹车。2.2 刹车系统失灵。但是后期看到刹车是有效果的，2.2我个人认为可以排除。同上面直接结论的第3条。
3. 缸压多大算是正常？看前面3秒钟，是从0.3->6(第一秒）， 6->18.3（第二秒） 18.3->40.2(第三秒），ABS、防碰撞主动刹车介入后最终到达140.7。这个我只是吃瓜群众，不明白应该是多少。
4. 全力刹车的-0.70862g的刹车，算是正常吗？（河南地区，沥青路面，满载情况），我也是吃瓜群众，需要专业人士解答。我个人觉得不够优秀，但是不了解天气、地面、温度、胎压、载重等情况，我也不清楚是不是正常的。
