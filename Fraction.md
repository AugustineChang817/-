# -
使用Python做數字乘階計算

u = int(input())
sta = 1
if u == 0:
    print(sta)
    print('定義上零階等於一',end="\t")
    print('0! = 1')
elif u >= 1:
    for i in range(1, u+1):
        sta *= i
    print(sta)
else:
    print('無法計算負數的階乘')
