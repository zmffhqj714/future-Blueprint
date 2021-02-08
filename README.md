# future-Blueprint

#필요한 돈
money = 3000000 #한달에 필요한 돈
inflation = 200000 #인플레이션으로 소득 약 20만원씩 증가필요
result = 0


for i in range(29,121) :#age
    result += money
    money += inflation
print(result)
