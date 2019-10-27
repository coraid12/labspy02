# 3 Buah Bilangan ( Mencari Bilangan Terbesar dan Terkecil )

print ('program untuk menentukan bilangan terbesar dan terkecil')

def pengulangan():

    print ('masukkan 3 bilangan yang diinginkan!')
    
    a=int(input('bilangan1 = '))
    
    b=int(input('bilangan2 = '))
    
    c=int(input('bilangan3 = '))

    if a>b and a>c:
        if b>c:
            print (a, 'terbesar dan', c, 'terkecil')
        else:
            print (a, 'terbesar dan', b, 'terkecil')
    elif b>a and b>c:
        if a>c:
            print (b, 'terbesar dan', c, 'terkecil')
        else:
            print (b, 'terbesar dan', a, 'terkecil')
    else:
        if a>b:
            print (c, 'terbesar dan', b, 'terkecil')
        else:
            print (c, 'terbesar dan', a, 'terkecil')

    print ('')
    print ('ingin coba lagi? (ya/tidak)')
    x=input()
    if x=='ya':
        return pengulangan()
    if x=='tidak':
        print('Selesai.')

pengulangan()

# Contoh 1
![contoh1](https://user-images.githubusercontent.com/56239989/67631537-71552b00-f8ca-11e9-8609-0481e12d7141.jpg)

# Contoh 2
![contoh2](https://user-images.githubusercontent.com/56239989/67631545-88941880-f8ca-11e9-857f-80b7b788bc9f.jpg)

# Contoh 3
![contoh3](https://user-images.githubusercontent.com/56239989/67631547-8cc03600-f8ca-11e9-9c1a-cc5a2cc6d7be.jpg)

# Flow Chartnya
![FLOW CHART](https://user-images.githubusercontent.com/56239989/67632120-dbbd9980-f8d1-11e9-91ba-66117a553507.jpg)
