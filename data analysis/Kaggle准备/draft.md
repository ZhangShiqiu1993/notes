
#### Kaggle 准备

1.安装`Anaconda`

安装没什么好说的。

就是一点小问题。我用的`shell`是`zsh`，安装完之后不能在`terminal`使用`conda`命令。
因为默认`conda`会把自己的加载路径写进`~/.bashrc`或者`~/.bash_profile`。这里需要手动复制粘贴到`~/.zshrc` *(我寻思`fish`也会有这个问题)*

另外`conda`会自动启动`base`环境，这个有点不好了。因为我会有多个project同时在开发，依赖不同的环境。所以可以用下面这条关闭。
```bash
conda config --set auto_activate_base false
```

2.注册Kaggle & 下载数据集

#### 思路

>1.这是一个什么类型的问题？<br>
>以`house price`为例，是靠回归做预测<br>
>2.哪些算法可以做回归<br>
>线性回归等<br>
>3.线性回归需要什么样的数据<br>
>4.数据中是否有字符串，或者缺失值？如何变为数值型？<br>
>5.数据特征工程思路：EDA、特征选择、特征组合、特征分割……<br>
>6.算法的选择

#### 数据探索

```python

```
