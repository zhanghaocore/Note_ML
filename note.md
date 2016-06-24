<script type="text/javascript" src="http://cdn.mathjax.org/mathjax/latest/MathJax.js?config=TeX-AMS-MML_HTMLorMML">
</script>
#笔记
##数学-线性代数
###矩阵
+ n阶行列式的性质。

    + **性质1**行列式的行与列（按原顺序）互换，其值不变。

    + **性质2**行列式对任意一行按下式展开，其值相等
    ![alt text](https://github.com/zhanghaocore/Note_ML/blob/Note_ML_local/mathImg/matrix_nature_2.png "n阶行列式的性质2")
    + **性质3**（线性性质）有以下两条：
    ![alt text](https://github.com/zhanghaocore/Note_ML/blob/Note_ML_local/mathImg/matrix_nature_3.png "n阶行列式的性质3")
    + **推论1** 某行元素全为零的行列式其值为零。
    + **性质4** 行列式中两行对应元素相等，其值为零，即当 
    ![alt text](https://chart.googleapis.com/chart?cht=tx&chl=a_{il}=a_{jl({i\neqj,l=1,2,...,n})} "n阶行列式的性质3")时有
$$a_{il}=a_{jl({i\neq j,l=1,2,...,n})}$$
