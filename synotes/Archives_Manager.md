# 文献管理
{: id="20210417165355-s1qjgah"}

## Compressive Sensing Spectroscopy Using a Residual Convolutional Neural Network
{: id="20210417165405-ba4upqz"}

Tags: #CS# #ResCNN# #光谱学#
{: id="20210417165442-ygk39e8"}

薄膜滤光片建立压缩感知光谱仪
{: id="20210417165842-d7ousjj"}

给定波长的透过率由以下公式决定
{: id="20210417170000-tkakv22"}

$$
T(\lambda)=1-\frac{1}{2}(|\rho_{TE}(\lambda)|^2+|\rho_{TM}(\lambda)|^2)
$$
{: id="20210417172752-mu8otbi"}

其中， $\rho_{TE}(\lambda)$ 和 $\rho_{TM}(\lambda)$ 为反射系数在对应TE模和TM模下的幅值，可通过**算法1**计算
{: id="20210417172903-a5wp78p" updated="20210418103430"}

观察值$\mathbf{y}\in\mathbb{R}^{M\times1}$ 与入射光原始值$\mathbf{x}\in\mathbb{R}^{N\times1}$的关系如下
{: id="20210418103430-3y0r12e" updated="20210418104645"}

$$
\mathbf{y=Tx}
$$
{: id="20210418104529-x5fqzlz" updated="20210418104531"}

其中$\mathbf{T}\in\mathbb{R}^{M\times N}$为传感矩阵，$M<N$
{: id="20210418104700-kr9b54y" updated="20210418163951"}

使用ResCNN来客服稀疏重建的极限
{: id="20210418163951-nij4xgt" updated="20210418164239"}

![image.png](assets/image-20210418163604-m6o0s02.png)
{: id="20210418111738-zk9arpm" updated="20210418163605"}

{: id="20210418164144-ind2swb"}

{: id="20210418163612-lx8klng"}


{: id="20210417165355-yb2hih8" type="doc"}
