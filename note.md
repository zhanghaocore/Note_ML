#笔记
##数学-线性代数
###矩阵
+ n阶行列式的性质。

    + **性质1** 行列式的行与列（按原顺序）互换，其值不变。

    + **性质2** 行列式对任意一行按下式展开，其值相等
    ![alt text](https://github.com/zhanghaocore/Note_ML/blob/Note_ML_local/mathImg/matrix_nature_2.png "n阶行列式的性质2")
    + **性质3**（线性性质）有以下两条：
    ![alt text](https://github.com/zhanghaocore/Note_ML/blob/Note_ML_local/mathImg/matrix_nature_3.png "n阶行列式的性质3")
    + **推论1** 某行元素全为零的行列式其值为零。
    + **性质4** 行列式中两行对应元素相等，其值为零，即当 
    ![alt text](https://github.com/zhanghaocore/Note_ML/blob/Note_ML_local/mathImg/matrix_nature_4_1.png "n阶行列式的性质3")时有
    
    ![alt text](https://github.com/zhanghaocore/Note_ML/blob/Note_ML_local/mathImg/matrix_nature_4.png "n阶行列式的性质4")
    + **推论2** 行列式中两行对应元素成比例，其值为零
    + **性质5** 在行行列式中，把某行各元素分别乘非零常数k，再加到另一行的对应元素上，行列式的值不变（简称：对行列式做倍加行变换，其值不变），即：
    ![alt text](https://github.com/zhanghaocore/Note_ML/blob/Note_ML_local/mathImg/matrix_nature_5.png "n阶行列式的性质5")
    + **性质6** （反对称性质） 行列式的两行对换，行列式的值反号。
    + **性质7** 行列式某行的元素乘另一行对应元素的代数余子式之和等于零，即：
    ![alt text](https://github.com/zhanghaocore/Note_ML/blob/Note_ML_local/mathImg/matrix_nature_7.png "n阶行列式的性质7")
+ 克拉默(Cramer)法则。
    + **定义** n个未知量n个方程的线性方程组，在系数行列式不等于零时的行列式解法，通常称为**克拉默(Cramer)法则**
