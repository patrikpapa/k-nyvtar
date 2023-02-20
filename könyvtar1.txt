oldal=int(input('Adj meg az egyik könyv oldalszámát! '))
oldal2=int(input('Adjon meg egy másik könyv oldalszámát! '))

if oldal >= oldal2:
    print(f'A könyv oldalszáma az egyik könyvben több, {oldal}')

elif oldal2 >= oldal:
    print(f'A könyv oldalszáma a másik könyvben több, {oldal2}')
    
else:
    print('A két könyv egyenlő oldalszámú. ')