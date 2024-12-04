print('Казанцев Константин мф 72,средний вариант')

N1

high= int(input('введите длину'))
width = int(input('введите ширину'))
length = int(input('введите высоту'))
print('ещё раз')
high2 = int(input('введите длину'))
width2 = int(input('введите ширину'))
length2= int(input('введите высоту'))
v = high*width*length
v2 = high2*width2*length2
if v < v2:
    print('второй объём больше')
elif v > v2:
    print('второй объём меньше')
elif v == v2:
    print('второй объём равен первому')
