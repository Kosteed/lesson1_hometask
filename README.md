# lesson1_hometask
x=34
y=33
f=(x+y)
print(f)

text='Nice'
text1=' to meet you'
print(text+''+text1)

list_of_students=[]
names=['Vlad,Kseniya,Artyom,German,Valerij']
print(names)

'''calculator'''
x=int(input('Press a first number'))
oper=input('What to do?')
y=int(input('Press a second number'))
if oper == '+':
    print(x+y)
elif oper == '-':
    print(x-y)
elif oper == '*':
    print(x*y)
elif oper == '/':
    print(x/y)
elif oper == '**':
    print(x**y)
elif oper == '%':
    print(x%y)
elif oper == '//':
    print(x//y)

x='Kseniya,Vlad,Artyom,German,Valerij'[1:5]
print(x)

Surname="Masienok"
Name="Vlad"
Patronymic="Valerievich"
print(Surname+' '+ Name +' '+Patronymic)

dict={'Vlad':'20'}
print(dict['Vlad'])
