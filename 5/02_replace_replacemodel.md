# 替换与替换模式

#### 替换命令 `r`

`r` 不是操作符，它是等你输入一个字符，然后用这个字符替换当前光标上的字符。 其作用和 `cl` 或者 `s` 命令完成相同的功能，只不过 `r` 不需要使用 &lt;Esc&gt; 退出插入状态。


#### 替换模式 `R`

`R` 命令启动替换模式，在这个模式下，你输入的每个字符都会覆盖当前光标上的字符，这样会一直持续下去直到输入 &lt;Esc&gt; 命令。  

当使用 &lt;BS&gt; 退格键进行修复时，原理被替换的字符又回来了，就好像使用了一个 ”撤销“ 命令一样。  

可以使用 &lt;Insert&gt; 在插入模式和替换模式下切换。  






