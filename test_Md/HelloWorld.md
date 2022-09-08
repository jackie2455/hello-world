# HelloWorld

测试一下HelloWorld怎么样

不过如何都可以试一试[^1]

## 一个二级标题


$$
\boldsymbol{e}_{ij}=\left[ \begin{array}{c}
	e_1\\
	\vdots\\
	e_k\\
	\vdots\\
	e_{16}\\
\end{array} \right] _{ij},e_k=I\left( u_k,v_k \right) -I_j\left( \kappa \left( \pi \left( \boldsymbol{KT}_j\boldsymbol{P}_i \right) \right) \right) 
\\
\pi \text{：表示}3D\text{到}2D\text{的投影变换}
\\
\kappa \text{：表示按预定的规则计算出第}k\text{个像素的位置（本质上就是平面内的平移函数）}
\\
\text{第一步：}\boldsymbol{p}_{i}^{C}=\boldsymbol{T}_j\boldsymbol{P}
\\
\text{第二步：}\boldsymbol{x}^{ij}=\pi \left( \boldsymbol{Kp}_{i}^{C} \right) 
\\
\text{第三步：}\boldsymbol{x}^k=\kappa \left( \boldsymbol{x}^{ij} \right) 
\\
\text{因此，雅可比矩阵计算：}
\\
\frac{\partial \boldsymbol{e}_k}{\partial \left[ \begin{array}{c}
	\boldsymbol{\xi }_j\\
	\boldsymbol{P}\\
\end{array} \right]}=-\underset{\begin{array}{c}
	\text{数值求解}\\
	\text{见课本}\\
\end{array}}{\underbrace{\frac{\partial I_j}{\partial \boldsymbol{x}^k}}}\underset{\mathbf{1}_2}{\underbrace{\frac{\partial \boldsymbol{x}^k}{\partial \boldsymbol{x}^{ij}}}}\underset{\begin{array}{c}
	\text{可解析}\\
	\text{见课本}\\
\end{array}}{\underbrace{\frac{\partial \boldsymbol{x}^{ij}}{\partial \boldsymbol{p}_{i}^{C}}}}\underset{\begin{array}{c}
	\text{可解析}\\
	\text{见课本}\\
\end{array}}{\underbrace{\frac{\partial \boldsymbol{p}_{i}^{C}}{\partial \left[ \begin{array}{c}
	\boldsymbol{\xi }_j\\
	\boldsymbol{P}\\
\end{array} \right]}}}
$$

## 这是另一个二级标题

发发打发啊发的链接发拉地府

插入一个视频：

<video src="assets\bandicam 2022-09-08 08-41-27-738.mp4"></video>


[^1]:  a;fjlsjfal;falsfdja;fjalf