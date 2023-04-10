x = int(input("请输入一个三位数:"))
a = x // 100
b = (x // 10) % 10
c = x % 10
print("百位数是：%d十位数是：%d个位数是：%d" % (a,b,c))
x = input ("请输入你要兑换的币种名称:")
d=float(input("请输入兑换汇率:"))
o=int(input("请输入你可兑换的人民币的数量:"))
p=o / d
print("%d人民币可兑换:%.2f美元" % (o,p))
