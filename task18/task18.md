# 任务目的：

        学习与实践JavaScript的基本语法、语言特性
        初步了解JavaScript的事件是什么
        初步了解JavaScript中的DOM是什么
        
# 任务描述

        如图，http://7xrp04.com1.z0.glb.clouddn.com/task_2_18_1.jpg
        模拟一个队列，队列的每个元素是一个数字，初始队列为空
        有一个input输入框，以及4个操作按钮
                点击"左侧入"，将input中输入的数字从左侧插入队列中；
                点击"右侧入"，将input中输入的数字从右侧插入队列中；
                点击"左侧出"，读取并删除队列左侧第一个元素，并弹窗显示元素中数值；
                点击"右侧出"，读取并删除队列又侧第一个元素，并弹窗显示元素中数值；
                点击队列中任何一个元素，则该元素会被从队列中删除
        
## Notes：

        获取输入框的值时最好不要直接在定义变量时赋值，如var txt = document.getElementById('num').value；如果初始化时没有定义value的值，那么后续程序会出现bug。
        
        insertBefore()方法、appendChild()方法
        
        首先创建元素（createElement()）,再创建文本节点（createTextNode()）,再调用元素的插入功能把文本节点插入。

## [结果图](https://lulujianglab.github.io/IFE16/task18/)
