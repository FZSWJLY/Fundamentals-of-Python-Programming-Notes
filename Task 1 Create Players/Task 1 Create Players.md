# 任务一：创建玩家

**参考代码**

```python
"""
Game Name:TenHalfPoint
Developer: xuzl
Version： 1.0
Date：2021/2/22 11:01
"""

# 创建一个玩家player1
# 玩家信息应包含玩家姓名、筹码、要牌标志符、一张扑克牌、牌点数、下注数
player1_name = input("请输入玩家的姓名：") # 从键盘输入玩家姓名，属于字符串型。
print("欢迎你，", player1_name) # 打印欢迎信息。
player1_card = input("请输入一张扑克牌：") # 从键盘输入一张扑克牌，属于字符串型。
player1_money = 120 # 初始化玩家的筹码为120
player1_flag = True # 初始化玩家要牌标志符为True
player1_pointsum = 0 # 初始化玩家的牌点数为0
player1_bet = 0 # 初始化玩家的下注数为0

#打印玩家信息
print("玩家姓名：", player1_name)
print("筹码：", player1_money)
print("要牌标志符：", player1_flag)
print("一张扑克牌：", player1_card)
print("牌点数：", player1_pointsum)
print("下注数：", player1_bet)
```

注：

**1.注释**

`"""`

多行

注释

`"""`



`# 单行注释`

2.**输入**：`input()`

输入函数，输入的内容为字符串类型。

**3.变量**

首字母不能是数字，变量可以由数字、字母、下划线（_）组成。Python中变量不需要声明类型。

4.**赋值**

格式：变量 = 值，=为赋值号，右结合型符号，可以赋任何值（如：字符串、整型、布尔型）。

5.**输出**：`print()`

输出函数，格式为print(变量名)或print(" ", 变量名)。


