$$
\Gamma(z)=\frac{Z_{in}(z)-Z_0}{Z_{in}(z)+Z_0}\\
\rho=\frac{1+|\Gamma|}{1-|\Gamma|}\Rightarrow |\Gamma|=\frac{\rho-1}{\rho+1}\\
Z_{in}(z)=Z_0\frac{Z_L+jZ_0\tan\beta z}{Z_0+jZ_L\tan\beta z}\\
$$

## Smith 圆图

$\Gamma(z) \hArr Z_{in}(z) \hArr \rho \hArr \varphi$

### 特性参量无量纲化  

$$
\widetilde{Z}_{in}=\frac{Z_{in}(z)}{Z_0}\\
Z_{in}(z)=Z_0\frac{1+\Gamma}{1-\Gamma}\\
\widetilde{Z}_{in}=\frac{1+\Gamma}{1-\Gamma}\\
\Gamma=\frac{\widetilde{Z}_{in}-1}{\widetilde{Z}_{in}+1}
$$
无量纲电长度
$$
\tau=\frac{l}{\lambda}
$$  
圆图以$|\Gamma(z)|$为基底
$$
0\le |\Gamma(z)|\le 1
$$

将阻抗(导纳),$\rho$套在等$|\Gamma|$圆上
$$
\Gamma=\Gamma_u+j\Gamma_v\\
\Gamma(z)=\Gamma_L e^{-2\beta z}=|\Gamma_L|e^{j(\phi_L-2\beta z)}\\
\Gamma(z)周期为\frac{\lambda}{2},\tau 周期为\frac{1}{2}\\
$$
套覆阻抗圆
$$
\left\{
\begin{array}{l}
\widetilde{Z}_{in}(z)=\frac{1+\Gamma(z)}{1-\Gamma(z)}=\widetilde{R}+j\widetilde{X}\\
\Gamma=\Gamma_u+j\Gamma_v
\end{array}\right.\\
$$
等$\widetilde{R}圆$
$$
(\Gamma_u-\frac{\widetilde{R}}{1+\widetilde{R}})^2+\Gamma_v^2=(\frac{1}{1+\widetilde{R}})^2
$$
等$\widetilde{X}$圆
$$
(\Gamma_u-1)^2+(\Gamma_v-\frac{1}{\widetilde{X}})^2=(\frac{1}{\widetilde{X}})^2
$$

### $\rho$的标定

$$
\rho=\frac{1+|\Gamma|}{1-|
\Gamma|}
$$
作圆交实轴

### 圆图上特殊的点线面
匹配点(0,0)
$$
\Gamma=0,\widetilde{R}=1,\widetilde{X}=0
$$
短路点(-1,0)
$$
\Gamma=-1,\widetilde{R}=\widetilde{X}=0\\
$$
开路点(1,0)
$$
\Gamma=1,\varphi=0
$$
单位圆
$$
|\Gamma|=1,\widetilde{Z_{in}}=j\widetilde{X}
$$
正实轴
$$
\widetilde{R}=\rho,1\lt\widetilde{R}\lt \infty
$$
负半轴
$$
\widetilde{R}=k
$$

## 导纳圆图
$$
\widetilde{Y}_{in}(z)=\frac{1}{\widetilde{Z_{in}}}=\frac{1-\Gamma(z)}{1+\Gamma(z)}=\frac{1+(-\Gamma(z))}{1-(-\Gamma(z))}=\frac{1+\Gamma_i(z)}{1-\Gamma_i(z)}\\
\widetilde{Y}_{in}(z)=\widetilde{G}+j\widetilde{B}\\
\widetilde{R}\hArr\widetilde{G}\\
\widetilde{X}\hArr\widetilde{B}\\
\Gamma(z)\hArr\Gamma_i(z)
$$
短路开路对换
感性容性对换
波腹波节对换

由阻抗求导纳，只需将阻抗点在圆图上以原点为中心转$\pi$再读数