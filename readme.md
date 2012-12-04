# QMFood
## 青石千梦的伪春菜通用食物系统

---

作者主页：[http://thousandmoe.github.com/](http://thousandmoe.github.com/)  
配布地址：[http://thousandmoe.github.com/qmfood](http://thousandmoe.github.com/qmfood)  
反馈地址：[http://ainou.liaoliaolan.eu.org/ainou/9/3.1](http://ainou.liaoliaolan.eu.org/ainou/9/3.1)  

---

### 利用规约 ###
* 你可以在任何公开配布或者不公开配布的人格中使用QMFood，唯需在readme中加上QMFood的作者信息和链接
* 你可以对QMFood进行任何形式的修改，但必须保留原版权和链接
* 你不可以将你对QMFood的修改版本以任何形式独立发布
* 你不可以对QMFood进行任何形式的二次配布，包括但不限于QQ，邮箱等

### 注意事项 ###
* 本脚本仅可用于AYA
* 使用本脚本需要了解一定的伪春菜制作基础
* 作者不提供任何形式的技术支持
* 作者不对使用该脚本造成的任何影响负责

### 功能主治 ###
大概就是一个通用的简陋的喂食系统。喜爱度和饥饿值是相关的，并且喜爱度可以动态变化。能够自己定义食物的名字，对喂食以后的反应，以及喜好度的变化规则等。总之是一个简易加入喂食系统的好方式，只不过还是要自己仔细的编辑反应对话才能做出有爱的作品。

### 安装方法 ###
1. 将所有的文件复制到dic/qmfood下
2. 修改yaya.txt，在最后加上下面的代码：  
`//↓从下面这行开始复制  
dic, dic/qmfood/config.dic  
dic, dic/qmfood/lang.dic  
dic, dic/qmfood/debug.dic  
dic, dic/qmfood/status.dic  
dic, dic/qmfood/general.dic  
dic, dic/qmfood/use.dic  
//↑复制到上面这行`
3. 在菜单中加入`\q[喂食,OnQMFMenu]`
4. 开始使用吧=w=

###高级功能###
1. 修改config.dic能够得到不同的饥饿值算法，食物等。
2. 修改lang.dic能够得到不同的反应对话。
3. 在菜单中加入`\q[千梦食物系统调试菜单,OnTMFDebug]`，可以打开调试菜单。