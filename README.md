# LAB-3-STRUKTUR-KONTROL-dan-MODULAR-PROGAMING
print("RUMAH MAKAN GEPREK ASIK")
print("gratis es teh sepuasnya")
print("==================================")

pakethemat  = int(input("tempe geprek : "))
paketmantap = int(input("telor geprek : "))
paketsultan = int(input("ayam geprek : "))

if pakethemat==paketmantap==paketsultan:
    print('total bayar', paketsultan*20000 + pakethemat*10000 + paketmantap*15000)
elif pakethemat+paketmantap+paketsultan:
    print('total bayar', pakethemat*10000 + paketmantap*15000 + paketsultan*20000)

if pakethemat < paketsultan:
    print('total bayar', paketsultan*20000 + pakethemat*10000 + paketmantap*15000)
elif paketsultan > pakethemat:
    print('total bayar', pakethemat*10000 + paketmantap*15000 + paketsultan*20000)

print("terimakasih atas kunjungannya")
