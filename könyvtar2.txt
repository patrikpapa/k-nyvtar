def gyűjtő(mennyiség):
    if mennyiség >= 800000:
        return True
    else:
        return False
        
while True:
    könyvtár=input('Add meg a könyvtár nevét! ')
    gykm=int(input('Add meg a gyűjtött kötetek mennyiségét! (ezer)! '))
    if könyvtár == '':
        break
    if gyűjtő(gykm):
        print(f'{könyvtár} egy ügyes gyűjtő! ')
    else:
        print(f'{könyvtár} kevésbé szorgalmas! ')