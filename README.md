print('合計値を２１にしたほうが負け')
print('1~3の間の値を足していく')
n = 0
sum = 0
while True:
    n = int(input('整数値：'))
    sum += n
    print('正の整数の合計は', sum, 'です。')
    if sum >= 20:
        print('YOUR LOSE')
        break
