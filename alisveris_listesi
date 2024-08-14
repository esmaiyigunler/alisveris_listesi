urunListe = []
fiyatListe = []
butce = int(input("Lütfen bütçenizi giriniz: "))
toplamHarcama = 0

while True:
    urun = input("Lütfen eklemek istediğiniz ürünü giriniz (Durdurmak için 'bitti' yazın): ")
    if urun == 'bitti':
        break
    
    fiyat = int(input("Lütfen eklemek istediğiniz ürünün fiyatını giriniz: "))
    
    if toplamHarcama + fiyat > butce:
        print("Bu ürünü ekleyemezsiniz, çünkü bütçenizi aşıyor.")
        continue

    urunListe.append(urun)
    fiyatListe.append(fiyat)
    toplamHarcama += fiyat

    print("Ürün Listesi:", urunListe)
    print("Fiyat Listesi:", fiyatListe)
    print("Toplam Harcama:", toplamHarcama)
    print("Kalan Bütçe:", butce - toplamHarcama)

print("Alışveriş listeniz tamamlandı.")
print("Toplam Harcama:", toplamHarcama)
print("Kalan Bütçe:", butce - toplamHarcama)
