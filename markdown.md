# 五、 光学设计  

安徽创谱仪器科技有限公司根据客户的技术指标要求，已完成光学系统核算和优化，最终的光学设计方案如下。  

# 5.1 设计要求  

表 5.束线指标要求  


<html><body><table><tr><td rowspan="2">序号</td><td rowspan="2">项目</td><td rowspan="2">验收指标</td><td colspan="2">内部指标</td></tr><tr><td>主线</td><td>支线</td></tr><tr><td>１</td><td>光谱范围</td><td>5~200 nm 6~250 eV</td><td>1.2~50 nm 25~1000 eV</td><td>40~200 nm 6~31 eV</td></tr><tr><td>２</td><td>波长重复精度</td><td>0.01 nm @ 13.5 nm</td><td>机构重复性按1/2000波长重复性设计</td><td></td></tr><tr><td>3</td><td>分辨本领</td><td>1000 @ 13.5 nm</td><td>1000 @ 13.5 nm 全波段 >800</td><td>全波段 >800</td></tr><tr><td>４</td><td>光谱纯度</td><td>≥ 90%</td><td>滤片</td><td>气体滤波</td></tr><tr><td>５</td><td>新建反射率计</td><td>Φ1m， 1x105 Pa</td><td></td><td></td></tr><tr><td>６</td><td>光子通量 (photons/s)</td><td>/</td><td>8x10° @120 eV 3x10° @ 200 eV, 500 eV</td><td>3x10l0 @ 14 eV 5x100 @ 25 eV</td></tr></table></body></html>  

# 5.2 光源特性  

# 5.2.1 NSRL 机器参数  

$\mathrm{E}=0.8\:\mathrm{GeV}\:\:\:\mathrm{I}=300\:\mathrm{mA}$ $\operatorname{\varepsilonx}=38\mathrm{nm.rad}\quad\mathrm{{\varepsilon}}\mathrm{{y}}=1.9\mathrm{nm.rad}$  

表 6.第四块弯铁（B4） $\mathbf{15^{\circ}}$ 角处束流参数  


<html><body><table><tr><td>Length</td><td>1.7m</td></tr><tr><td>B</td><td>1.23T</td></tr><tr><td>P</td><td>2.16451m</td></tr><tr><td>0</td><td>45°</td></tr><tr><td colspan="2">15°偏角处束流参数</td></tr><tr><td>βx</td><td>0.923 m</td></tr><tr><td>β</td><td>7.686 m</td></tr></table></body></html>  

<html><body><table><tr><td>ax</td><td>1.378</td></tr><tr><td>αy</td><td>-2.100</td></tr><tr><td>Yx</td><td>3.142 (1/m)</td></tr><tr><td>Yy</td><td>0.703 (1/m)</td></tr><tr><td>nx</td><td>0.279 m</td></tr><tr><td>nx</td><td>-0.475</td></tr><tr><td>x</td><td>0.229mm</td></tr><tr><td>x</td><td>0.412 mrad</td></tr><tr><td></td><td>0.121mm</td></tr><tr><td></td><td>0.0366mrad</td></tr></table></body></html>  

# 5.2.2 光源性能  

在弯铁光源中，由于圆周运动的电子在水平方向的辐射是均匀的，因而可以用单位水平毫弧度内每秒的光谱通量 $\mathrm{(phs/s/mrad.300mA.0.1\%bw)}$ ）得到光通量与能量之间的关系，称为通量谱，可写成下面的形式：  

$$
\frac{d F_{_B}}{d\theta}=2.457\times10^{13}E\big[G e V\big]I\big[A\big]y\int\displaylimits_{y}^{\infty}K_{5/3}\big(y^{\prime}\big)d y^{\prime}
$$

下图给出了系统在不同水平接收角的情况下的光子通量。  

![](https://cdn-mineru.openxlab.org.cn/extract/93ef50db-586d-4ed2-b2ca-8f4e1c8e1aa9/dc3a4133f23102c98c6268905a49306225d900d76868096af792a5616b9659b3.jpg)  
图 11.光子通量(photon/sec/0.1%b.w.@300mA)  

利用shadow 软件追迹弯铁发出的光的光斑大小，如下图所示，光斑尺寸 $0.542{\times}0.285\mathrm{mm}^{2}$ （FWHM）。  

![](https://cdn-mineru.openxlab.org.cn/extract/93ef50db-586d-4ed2-b2ca-8f4e1c8e1aa9/cb40891f059df30d54a36a2fc98df7e081d14c69aa659a83b332817ddfe4738f.jpg)  
图 12.光源尺寸（FWHM： $\mathbf{0.542times0.285mm}^{2})$  

下图为不同能量情况下垂直发散角，在低能量处的垂直发散角较大，而到 $100\mathrm{eV}$ 以上，其垂直接收角基本不变。  

![](https://cdn-mineru.openxlab.org.cn/extract/93ef50db-586d-4ed2-b2ca-8f4e1c8e1aa9/9d71309df72dede50d648516146872d0583a241c9f2b21727e24c14f83b21abc.jpg)  
图 13.光源发散角  

# 5.3 光束线总体布置  

光束线分主线和支线设计，按光谱范围，其中：  

主线：针对短波段，覆盖波长 $1.2\mathrm{-}50\mathrm{nm}$ ，对应能量范围 $25{\mathrm{-}}1000{\mathrm{eV}}$ ，采用自聚焦平面光栅单色器（SF-VLS-PGM）；  

支线：针对长波段，覆盖波长 $40{-}200\mathrm{nm}$ ，对应能量范围 6-31eV，采用 C-T 型光栅单色器设计，用气体滤波抑制高次谐波。  

光束线单色器采用光栅公称线密度参数及能量范围分布如下：  

表 7.光束线能量范围  


<html><body><table><tr><td></td><td>光栅线密度（1/mm)</td><td>能量范围 (eV)</td><td>波长范围 （nm)</td></tr><tr><td rowspan="2">主线</td><td>300</td><td>25-150</td><td>8.2~50</td></tr><tr><td>1400</td><td>100-1000</td><td>1.24-12.4</td></tr><tr><td rowspan="2">支线</td><td>300</td><td>6-12</td><td>200-103</td></tr><tr><td>600</td><td>11-31</td><td>112-40</td></tr></table></body></html>  

表 8.光束线验收指标  


<html><body><table><tr><td rowspan="2">序号</td><td rowspan="2">项目</td><td rowspan="2">验收指标</td><td colspan="2">内部指标</td></tr><tr><td>主线</td><td>支线</td></tr><tr><td>１</td><td>光谱范围</td><td>5 - 200 nm 6-250 eV</td><td>1.2 -8 - 50 nm 25 -1000 eV</td><td>40-100- 200 nm 6-12-31eV</td></tr><tr><td>２</td><td>波长重复精度 @ 13.5 nm</td><td>0.01 nm</td><td>机构重复性按1/2000 波长重复性设计</td><td></td></tr><tr><td>3</td><td>分辨本领</td><td>1000 @ 13.5 nm</td><td>1000 @ 13.5nm 全波段>800</td><td>全波段>800</td></tr><tr><td>4</td><td>光谱纯度</td><td>≥90%</td><td>滤片</td><td>气体滤波</td></tr><tr><td>5</td><td>新建反射率计</td><td>Φl米，1x10-5Pa</td><td></td><td></td></tr><tr><td>６</td><td>光子通量 (photons/s)</td><td>/</td><td>8x1010 @ 120eV 3x10° @ 200eV,500eV</td><td>3x1010 @ 14eV 5x101° @ 25eV</td></tr></table></body></html>  

下图为束线的总体布局图，从弯铁发出的光，每条分支线分别利用其中 5mrad 的水平发散角，两条分支线的中心夹角 25mrad。  

![](https://cdn-mineru.openxlab.org.cn/extract/93ef50db-586d-4ed2-b2ca-8f4e1c8e1aa9/dae2a35b2a940d9d24d2c78d2bb077609607dc15d801a077ad7b4d6a11387b7c.jpg)  
图 14.两条束线布局  

![](https://cdn-mineru.openxlab.org.cn/extract/93ef50db-586d-4ed2-b2ca-8f4e1c8e1aa9/4ec0fe87582d0b82775920e92e8ea9d7138f263a72d359677a32dc3da060f99a.jpg)  
图 15.束线总体布局图  

# 5.4 主线物理设计  

# 5.4.1 光学系统设计  

光学系统示意图见下图。前置镜接收角为4.5mrad(水平) $\lceil\times1.4$ mard (竖直) 。从光源发出的光以 $3^{\circ}.$ 入射竖直安装的距离光源 $6000\ \mathrm{mm}$ 的前置聚焦镜 M1,将光在系统竖直方向以 2:1 聚焦在入射狭缝 S1 上，在水平方向聚焦在出射实验站处。所有光学元件表面镀 $\mathrm{\Au}$ 。  

从入射狭缝出射的光入射单色器内的平面镜，其反射光打在 $3001/\mathrm{mm}$ 或 $14001/\mathrm{mm}$ 中心线密度的变间距光栅（VLS-PG）中心，出射光聚焦在出射狭缝上。 $25\mathrm{-}150\mathrm{eV}$ 使用 $300\mathrm{l/mm}$ 中心线密度， $100{-}1000{\mathrm{eV}}$ 使用 $14001/\mathrm{{mm}}$ 中心线密度。后置镜球面镜或柱面镜，将出射狭缝光斑聚焦到实验站处。光束线整体长度约为 $18.5\mathrm{m}$ 。  

![](https://cdn-mineru.openxlab.org.cn/extract/93ef50db-586d-4ed2-b2ca-8f4e1c8e1aa9/5d4009c601293f9447d9daa172abcfa20ea8c3dc6f24f38aa683219f7f361139.jpg)  
图 16.主线光路布置图  

# 5.4.2 变线距参数  

自聚焦光栅单色器中，分光光学元件为变线距光栅，变间距平面光栅中从光栅中心到坐标w 处刻线总数可以表示为：  

$$
N=N_{0}\left(1+a_{1}w+a_{2}w^{2}+a_{3}w^{3}+\cdots\right)
$$

w 的方向定义为逆着光路的方向， $\mathbf{n}_{0}$ 是展开系数。  

对于 $14001/\mathrm{mm}$ 光栅，覆盖 100\~1000eV。59.37 eV 处光栅包含角 $2\mathrm{K}{=}160^{\circ}$ ， $600\mathrm{eV}$ 处光栅包含角 $2\mathrm{K}=173.787^{\circ}$ ，且在 $200\mathrm{eV}$ 处消除慧差，计算得到：  

$$
\mathbf{a}_{1}=-8.245{\times}10^{-4}\mathrm{mm}^{-1},\mathbf{a}_{2}=3.002{\times}10^{-7}\mathrm{mm}^{-2};
$$

$300~\mathrm{l/mm}$ 光栅，覆盖 $25{\sim}150\mathrm{eV}$ 。 $25\mathrm{eV}$ 处光栅包含角 $2\mathrm{K}{=}160^{\circ}$ ， $150\mathrm{eV}$ 处光栅包含角$2\mathrm{K}{=}171.88^{\circ}$ ，且在 $90\mathrm{eV}\ (13.6\mathrm{nm})$ ）处消除光栅慧差，计算得到：  

$$
\mathbf{a}_{1}=-1.426{\times}10^{-3}\mathbf{m}\mathbf{m}^{-1},\mathbf{a}_{2}=2.712{\times}10^{-7}\mathbf{m}\mathbf{m}^{-2};
$$

# 5.4.3 光学系统参数  

平面镜的掠入射角 $\theta=(180^{\circ}-(a-\beta))/2$ ，根据光栅方程求出不同能量时候的入射角 $\mathbf{\ensuremath{a}}$ 、出射角 $\upbeta$ 以及平面镜的掠入射角 θ 和光栅接收角 $\upphi$ （光栅按 $180\mathrm{mm}$ 计算）。如下图所示，如果考虑将平面镜和光栅转至水平位置，平面镜的转动范围为 $10.0^{\circ}$ ，光栅转动范围为 $12.5^{\circ}$ 。整个系统  

垂直接收角主要限制因素为光栅尺寸，在低能段由于光栅入射角相对较小，则垂直接收角相对较大，而在高能段系统的垂直接收角较小。  

![](https://cdn-mineru.openxlab.org.cn/extract/93ef50db-586d-4ed2-b2ca-8f4e1c8e1aa9/b79b14770122cc5f87e154a1d98a9ac625fe1edb6e0da212e457148d9b5779c1.jpg)  
图 17.光栅的入射角、衍射角以及平面镜的掠入射角  

![](https://cdn-mineru.openxlab.org.cn/extract/93ef50db-586d-4ed2-b2ca-8f4e1c8e1aa9/b789211110fa04b9dcdcfc73b143f332641a0f55a26e84c1fecef23514e50766.jpg)  
图 18.不同能量对应的垂直接收角  

# 5.4.4 光学系统分辨率  

在光栅单色器中光谱展宽的来源于像差、入射狭缝、出射狭缝、元件面型误差、衍射极限等。根据系统设置，前置系统收光缩放聚焦后，理论上在入射狭缝处的光斑为 $120\upmu\mathrm{m}$ ，考虑到超环面镜像差的因素，实际的光斑尺寸会比理论值大，如下图所示，追迹结果显示光斑尺寸接近 $200\upmu\mathrm{m}$ (FWHM)。  

![](https://cdn-mineru.openxlab.org.cn/extract/93ef50db-586d-4ed2-b2ca-8f4e1c8e1aa9/fcf0fddbd330890bdda6f81ad7fbec75f0aff64010d1527433c74a6467d14138.jpg)  
图 19.入射狭缝处光斑大小  

由于光学系统不同光子能量的缩放比不同，则相同开口的入射狭缝在不同能量处对应的出射狭缝宽度会不相同。  

光栅的面型误差： $\upsigma\mathrm{G}{=}0.2{^{\prime\prime}}$ 平面镜的面形误差： $\upsigma\mathrm{M}{=}0.2\mathrm{\Omega}^{\prime\prime}$  

由于两块光栅的缩放比不同，对于 $300\mathrm{l/mm}$ 光栅，入射狭缝宽度设置为 $100\upmu\mathrm{m}$ ，对于$14001/\mathrm{{mm}}$ 光栅，入射狭缝宽度可以设置为 $150\upmu\mathrm{m}$ 。  

从下图可以看出入射狭缝开口宽度对光谱分辨率影响最大。可以通过减小入射狭缝的开口尺寸来提高系统的能量分辨本领。  

![](https://cdn-mineru.openxlab.org.cn/extract/93ef50db-586d-4ed2-b2ca-8f4e1c8e1aa9/8de8bdd06ec1d3a6086de1b2fa188a73ff6b3c4149864a1ff41afcb76c4e1658.jpg)  
图 $\mathbf{20.300l/mm}$ -各项因素对分辨率的影响  

![](https://cdn-mineru.openxlab.org.cn/extract/93ef50db-586d-4ed2-b2ca-8f4e1c8e1aa9/389407a930ee0521d108ae4ccca89002e58eb3d828e86c022bbfcbac51e4bcd6.jpg)  
图 $\mathbf{21.1400l/mm}$ -各种因素对分辨率的影响  

下图给出了两块光栅的光谱分辨率，理论上可以到 $1000\mathrm{eV}$ ，同时由于狭缝处的光斑较大，可以适当的通过增加狭缝开口大小而提高光通量。  

![](https://cdn-mineru.openxlab.org.cn/extract/93ef50db-586d-4ed2-b2ca-8f4e1c8e1aa9/b4ad401b86d989ccb27918e7834904a7cbd8df02d88ce2429a222fb0fc087db8.jpg)  
图 22.光栅单色器的分辨本领  

通过SHADOW 软件可以对系统进行光学追迹，如下图所示：  

![](https://cdn-mineru.openxlab.org.cn/extract/93ef50db-586d-4ed2-b2ca-8f4e1c8e1aa9/8dde64f92ba929b018c0463908e610fd85edd44aee00ee8939466558e70a03ad.jpg)  
图 $23.220{\scriptstyle\pm0.100}$ ，Res.P=2200@1400l/mm  

![](https://cdn-mineru.openxlab.org.cn/extract/93ef50db-586d-4ed2-b2ca-8f4e1c8e1aa9/76dfe5218db0681d4b6555135d216a5fc03125f7c3267c914b816aaf8e242864.jpg)  
图 24.13.5±0.011nm，Res.P=1200@300l/mm  

# 5.4.5 光学系统效率  

光学系统的效率，主要由前置镜，平面镜，后置镜的反射率，光栅的衍射效率，狭缝的通过率决定，下面给出光学元件的效率、系统的几何效率以及最终的总效率。  

# 5.4.5.1 反射镜反射率  

前置镜和后置镜的掠入射角为 $3^{\circ}$ ，镀膜厚度设为 $40\mathrm{nm}$ ，反射率由XOP 软件计算给出, 下图给出了使用 Au 镀层在全波段的效率对比，其中对不同偏振

态的反射率变化不大，后续计算按照无偏振考虑。  

![](https://cdn-mineru.openxlab.org.cn/extract/93ef50db-586d-4ed2-b2ca-8f4e1c8e1aa9/ab3a346cb2ddd22e29278f4762e8ad3fb021714b8099b54893221592b6f1fb1d.jpg)  
图 25.光学元件反射率（镀层厚度 $\mathbf{40nm}$ ，表面粗糙度 $\mathbf{0.5nm}^{\mathrm{'}}$ ）  

# 5.4.5.2 平面镜反射率  

平面镜掠入射角在扫描过程中不断的变化，两块光栅相同能量时平面镜的掠入射角不同，通过 XOP 软件计算平面镜的反射率。  

![](https://cdn-mineru.openxlab.org.cn/extract/93ef50db-586d-4ed2-b2ca-8f4e1c8e1aa9/6794fb55a84d9fac0bafab3afd07a01d4315966b3302f4a7cb0d282dd950b7f4.jpg)  
图 26.平面镜反射率  

# 5.4.5.3 光栅衍射效率  

分别计算闪耀光栅和矩形光栅效率以及不同衍射级次的效率，闪耀光栅效率明显高于矩形槽光栅。但矩形槽光栅高次谐波抑制效果较好，用户希望选择矩形槽光栅。  

![](https://cdn-mineru.openxlab.org.cn/extract/93ef50db-586d-4ed2-b2ca-8f4e1c8e1aa9/4ad992b7df175f3b72d169c5f8705fc6ff3550c37a602d8c12bb6d85f5720f9c.jpg)  
图 $\mathbf{27.300l/mm}$ -不同槽型光栅效率  

![](https://cdn-mineru.openxlab.org.cn/extract/93ef50db-586d-4ed2-b2ca-8f4e1c8e1aa9/effbc2a96a9510a7d7db06f50edbf96e5462eb4b7b0065dfd3e6c295d09fb4c0.jpg)  
图 $\mathbf{28.300l/mm}$ -不同衍射级次效率  

![](https://cdn-mineru.openxlab.org.cn/extract/93ef50db-586d-4ed2-b2ca-8f4e1c8e1aa9/3b547ac17d262f62b14b1f48ae8b94c010fe65a4c9ad454bc63e1d9260a86623.jpg)  
图 $\mathbf{29.1400l/mm}$ -不同槽型光栅效率  

![](https://cdn-mineru.openxlab.org.cn/extract/93ef50db-586d-4ed2-b2ca-8f4e1c8e1aa9/f2ebf22c837b4394a2503277ff33b99544d5d4ef59b5e67a366cca1aafd48114.jpg)  
图 $\mathbf{30.1400l/mm}$ -不同衍射级次效率  

# 5.4.5.4 几何效率  

系统几何效率主要由两部分组成，一部分是尺寸维度，另一维度是角度维度，由于光栅的尺寸有限，而不同能量处光栅的入射角不同，因此会导致垂直接收角发生变化，则对应不同能量情况时的接受效率会有所不同。  

![](https://cdn-mineru.openxlab.org.cn/extract/93ef50db-586d-4ed2-b2ca-8f4e1c8e1aa9/da5bd925ef6fb00012c33c0f5b2fa3c87380dc1c6ff3d0a3d94d99b57b0262bb.jpg)  
图 31.不同能量下的接收效率  

前置镜收光聚焦到入射狭缝，由于像差的存在，导致狭缝光斑偏大，如下图所示。通过追迹模拟的手段分别获得不同狭缝开口大小的情况下，入射狭缝的透光效率。  

![](https://cdn-mineru.openxlab.org.cn/extract/93ef50db-586d-4ed2-b2ca-8f4e1c8e1aa9/6ca80ed318f2d7b7c325619b02f2e7996230c2653f23fd03711d3974c1ec3e0f.jpg)  
图 32.入射狭缝处光斑  

![](https://cdn-mineru.openxlab.org.cn/extract/93ef50db-586d-4ed2-b2ca-8f4e1c8e1aa9/18525ea53669c35e1b4412b92289dcf7b3099e489b22c14bcf5651c48714006c.jpg)  
图 33.入射狭缝透过率  

# 5.4.5.5 系统总效率及光通量  

将各光学元件的效率和几何效率相乘得到光束线总效率，下图给出的是各个能量点的传输效率，在低能段较高，但是在高能段，由于光学元件反射率低，同时几何传输效率也低，导致传输效率很低，可以适当的根据需求来调节入射狭缝的尺寸大小。  

![](https://cdn-mineru.openxlab.org.cn/extract/93ef50db-586d-4ed2-b2ca-8f4e1c8e1aa9/9e65a01aa31d4cb784794647b173533d69ed3009d6c45f6b828704c67c451383.jpg)  
图 34.系统传输效率  

将总效率与光源光子通量相乘，同时考虑各个能量点的分辨率，得到系统的光通量，对于$3001/\mathrm{mm}$ 光栅，理论上最高通量接近 $10^{12}\mathrm{phs}/\mathrm{s}(\underline{{{\omega}}}120\mathrm{eV}\ @300\mathrm{mA}$ ，对于 $14001/\mathrm{{mm}}$ 光栅，理论上最高通量为 $2{\times}10^{11}\mathrm{phs}/\mathrm{s}@130\mathrm{eV}@300\mathrm{mA}$ 左右。设计需求值是 $8{\times}10^{10}\mathrm{phs}/\mathrm{s}\textcircled{\omega}120\mathrm{eV}$ ， $3{\times}10^{9}$ $\textcircled{a}200\:\mathrm{eV}$ ，各有1 个量子左右的余量。  

![](https://cdn-mineru.openxlab.org.cn/extract/93ef50db-586d-4ed2-b2ca-8f4e1c8e1aa9/68c5c6cf0e92958b1c730fbe1b49ce2716304785e127d8a6581cad19e2ad6b54.jpg)  
图 35.光束线的输出光通量  

# 5.4.6 离轴转动参数  

变包含角光栅单色器一般采用平面镜离轴转动来改变包含角。  

![](https://cdn-mineru.openxlab.org.cn/extract/93ef50db-586d-4ed2-b2ca-8f4e1c8e1aa9/a2583990759d173fd2e234f65a61c3bf86f4cffa9c1216a40b94ff9481dec743.jpg)  
图 36.离轴转动模型  

见图36，建立以平面光栅中心为坐标原点 O，出射光为 $\mathbf{x}$ 轴，垂直方向为 y 轴的坐标系。为了保证平面镜(PM)反射光轴经过 O 点，PM 需离轴转动，设转动中心为 M(XM,YM)，转动中心与平面镜垂直距离为 RM，也就是离轴转动半径。最终得到离轴转动参数为：  

$\mathrm{YH}{=}31\mathrm{mm}$ ， $\scriptstyle\mathrm{XM=0mm}$ ， $\mathrm{RM}{=}31.1\mathrm{mm}$ ， $\mathrm{YM=-}15.6\mathrm{mm}$  

下图给出了各个能量点中心光线偏离光栅中心尺寸 Wg，基本可以控制在 $20\upmu\mathrm{m}$ 以内，对系统性能影响较小，可以忽略。  

![](https://cdn-mineru.openxlab.org.cn/extract/93ef50db-586d-4ed2-b2ca-8f4e1c8e1aa9/e372afff749174c637994c6ffd16b6b0f9c79906d84ba2aab7f1e6353dbfcbf8.jpg)  
图 37.光斑偏离中心量  

下图出了各个能量点在平面镜上的光斑尺寸，由于光栅尺寸固定，光栅充当了光阑的作用，假定光栅有用长度为 $180\mathrm{mm}$ ，则对与 $14001/\mathrm{mm}$ 光栅对应的平面镜上的光斑尺寸约为 $92\mathrm{mm}$ 。对与 $3001/\mathrm{mm}$ 光栅对应的平面镜上的光斑尺寸约为 $136\mathrm{mm}$ 。  

计算得到平面镜有效长度 $391.7\mathrm{mm}$ ，实际平面镜长度为 $400\mathrm{{mm}}$ ，由于平面镜端面距离光栅中心较近，工程设计时需要重点考虑防碰撞的设计。  

![](https://cdn-mineru.openxlab.org.cn/extract/93ef50db-586d-4ed2-b2ca-8f4e1c8e1aa9/cadef2df6758aede2cdc554ee5db8f679e89d457ef405399ff0351929f46d8c3.jpg)  
图 38.平面镜安装尺寸示意图  

# 5.4.7 光斑大小  

追迹模拟不同位置的光斑大小，确认光学元件参数。  

![](https://cdn-mineru.openxlab.org.cn/extract/93ef50db-586d-4ed2-b2ca-8f4e1c8e1aa9/7f474125c7569da52970e5fe20d2c6c803dd5a00ce6a6b4e4c1da05b28e747b4.jpg)  
图 39.前置镜 $\mathbf{5}22\times18.5\mathbf{mm}^{2}$  

![](https://cdn-mineru.openxlab.org.cn/extract/93ef50db-586d-4ed2-b2ca-8f4e1c8e1aa9/d14fec76296098e1dd25a3a4cde3dfcb9e6351884a732f66afb8d6ab3605c099.jpg)  
图 40.光栅 $\mathbf{156}{\times}\mathbf{10}\mathbf{m}\mathbf{m}^{2}$  

![](https://cdn-mineru.openxlab.org.cn/extract/93ef50db-586d-4ed2-b2ca-8f4e1c8e1aa9/8db3320743abc41386ca781414e0c7d84a2ea504bb16c7e8f1078678b063ee49.jpg)  
图 41.后置镜 $\mathbf{112\times6.8mm^{2}}$  

下图给样品点处的光斑大小追迹情况模拟，从图中可以看出，聚焦光斑尺寸约为$0.18\times1.25\mathrm{mm}^{2}$ ，满足用户指标要求。  

![](https://cdn-mineru.openxlab.org.cn/extract/93ef50db-586d-4ed2-b2ca-8f4e1c8e1aa9/8fb3031c87adf654c57bc654d48bdcdd38a2260896cec423007d54768356af33.jpg)  
图 42.实验站光斑(FWHM:0.18×1.25mm2)  

谱学线站距离计量线站的距离为 1.4 米，后续的发散角为 $2.0{\times}2.0\mathrm{mrad}^{2}$ ,如下图所示:  

![](https://cdn-mineru.openxlab.org.cn/extract/93ef50db-586d-4ed2-b2ca-8f4e1c8e1aa9/f5b4fb27b55297fdbccda1f86f1d435f787f8af05a812db09f34f6cf99d8cf38.jpg)  
图 43.实验站处光斑大小 $\mathbf{2.0{\times}2.0m r a d}^{2}$  

则相应的实验站光斑如下图所示，光斑接近 $1.52\times1.88\mathrm{mm}^{2}$  

![](https://cdn-mineru.openxlab.org.cn/extract/93ef50db-586d-4ed2-b2ca-8f4e1c8e1aa9/26176c3be7a27680594abbc4a3be8d3efb08aceb1f27d670fdc7f9779b798395.jpg)  
图 44.谱学实验站处的光斑大小  

# 5.4.8 光学元件  

表 9.光学元件参数表  

<html><body><table><tr><td></td><td>前置聚焦镜 M1</td><td>后置聚焦镜 M2</td><td>平面镜</td><td>300 l/mm光栅</td><td>14001/mm光栅</td></tr><tr><td>面型</td><td>超环面</td><td>柱面镜</td><td>平面</td><td>平面</td><td>平面</td></tr><tr><td>元件尺寸(lxwxh) 有效尺寸(Ixw)</td><td>550×50×50 530x30</td><td>150x40×30 140×20</td><td>400×50×50 380×40</td><td>185× 40 ×25 175x30</td><td>185× 40 × 25 175x30</td></tr><tr><td>面型参数(mm)</td><td>R= 155280 p= 184.72</td><td>p= 89.7</td><td></td><td>/</td><td>/</td></tr><tr><td>线密度</td><td></td><td></td><td></td><td>no =300 1/mm a = -1.426×10-3 mm-1 a= 2.712×10-7 mm-²</td><td>no =1400 1/mm a = -8.245×10-4 mm-1 a = 3.0020×10-7</td></tr><tr><td>光栅类型 (blaze/laminar)</td><td></td><td></td><td></td><td>Laminar</td><td>Laminar mm-²</td></tr><tr><td>闪耀角</td><td></td><td></td><td></td><td>c/d=0.6，h=35nm</td><td>c/d=0.65，h=8nm</td></tr><tr><td>弧矢/子午面型误 差</td><td>1"/0.2"</td><td>1"/0.2"</td><td>1"/0.2"</td><td>0.2"</td><td>0.2"</td></tr><tr><td>(arcsec RMS) 镀膜</td><td>Au</td><td>Au</td><td>Au</td><td>Au</td><td>Au</td></tr><tr><td>覆盖能量范围</td><td>25~1000 eV</td><td>25~ 1000 eV</td><td>25~1000 eV</td><td>25~150 eV</td><td>100~1000eV</td></tr><tr><td>入射角</td><td>87°</td><td>87°</td><td>80°-90°</td><td>82.455°-86.944°</td><td>86.071°-88.78°</td></tr></table></body></html>  

|                               |                     |                  |                  |                                                      |                                                    |
| ----------------------------- | ------------------- | ---------------- | ---------------- | ---------------------------------------------------- | -------------------------------------------------- |
|                               | 前置聚焦镜 M1       | 后置聚焦镜 M2    | 平面镜           | 300 l/mm光栅                                         | 14001/mm光栅                                       |
| 面型                          | 超环面              | 柱面镜           | 平面             | 平面                                                 | 平面                                               |
| 元件尺寸(lxwxh) 有效尺寸(Ixw) | 550×50×50 530x30    | 150x40×30 140×20 | 400×50×50 380×40 | 185× 40 ×25 175x30                                   | 185× 40 × 25 175x30                                |
| 面型参数(mm)                  | R= 155280 p= 184.72 | p= 89.7          |                  | /                                                    | /                                                  |
| 线密度                        |                     |                  |                  | no =300 1/mm a = -1.426×10-3 mm-1 a= 2.712×10-7 mm-² | no =1400 1/mm a = -8.245×10-4 mm-1 a = 3.0020×10-7 |
| 光栅类型 (blaze/laminar)      |                     |                  |                  | Laminar                                              | Laminar mm-²                                       |
| 闪耀角                        |                     |                  |                  | c/d=0.6，h=35nm                                      | c/d=0.65，h=8nm                                    |
| 弧矢/子午面型误 差            | 1"/0.2"             | 1"/0.2"          | 1"/0.2"          | 0.2"                                                 | 0.2"                                               |
| (arcsec RMS) 镀膜             | Au                  | Au               | Au               | Au                                                   | Au                                                 |
| 覆盖能量范围                  | 25~1000 eV          | 25~ 1000 eV      | 25~1000 eV       | 25~150 eV                                            | 100~1000eV                                         |
| 入射角                        | 87°                 | 87°              | 80°-90°          | 82.455°-86.944°                                      | 86.071°-88.78°                                     |