
# Bozuk Para Tespiti ve Değer Hesaplama Projesi

Bu proje, OpenCV ve Python kullanarak bir görüntüdeki bozuk paraları tespit etmeyi, saymayı ve toplam değerlerini hesaplamayı amaçlamaktadır.

## Özellikler

-   Görüntü önişleme: Gri tonlama, bulanıklaştırma, adaptif eşikleme.
-   Morfolojik işlemler: Kapatma işlemi ile gürültü giderme.
-   Kontur analizi: Bozuk paraların tespiti ve alan hesaplaması.
-   Bozuk para sınıflandırması: Alan büyüklüğüne göre farklı bozuk para türlerinin tanımlanması.
-   Toplam değer hesaplama: Tespit edilen bozuk paraların toplam değerinin hesaplanması.

## Gereksinimler

-   Python 3.x
-   OpenCV
-   NumPy
-   Matplotlib


## Kullanım

1.  Projeyi klonlayın veya indirin.
    
2.  Bozuk para içeren görüntüyü proje dizinine ekleyin ve dosya adını `img_path` değişkenine atayın.
    
3.  Program, tespit edilen bozuk paraların sayısını ve toplam değerini ekranda gösterecek ve sonuçları bir grafik arayüzünde görselleştirecektir.
    

## Notlar

-   Bozuk paraların doğru tespiti için görüntü kalitesi ve ışıklandırma önemlidir. Gerekirse görüntü önişleme adımlarını ayarlayabilirsiniz.
-   Bozuk para türlerinin **alan aralıkları**, **kullanılan görüntülerin çözünürlüğüne** ve **bozuk paraların boyutlarına** bağlı olarak değişebilir. `coin_values` sözlüğündeki `area_range` değerlerini ihtiyaçlarınıza göre güncelleyebilirsiniz.
