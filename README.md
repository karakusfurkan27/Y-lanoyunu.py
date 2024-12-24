 Yılan Oyunu - README

Bu proje, **Pygame** kullanarak geliştirilmiş klasik bir Yılan Oyunu'dur. Oyuncu, yılanı ekranda yönlendirerek yiyecekleri toplar ve yılanın boyunu uzatmaya çalışır. Oyun, yılanın kendisine çarpması veya ekranın dışına çıkması durumunda sona erer.

 Özellikler

- **Yılan Kontrolü:** Yılan, ok tuşları (sol, sağ, yukarı, aşağı) ile yönlendirilir.
- **Yılan Uzunluğu:** Yılan, yediği her yemle birlikte uzar.
- **Ekran Sonlandırma:** Eğer yılan kendisine çarparsa veya ekranın sınırlarına ulaşırsa oyun sona erer.
- **Yeniden Başlatma ve Çıkış:** Oyun bittiğinde, oyuncuya tekrar başlama veya çıkma seçeneği sunulur.
  
 Kurulum

1. **Gerekli Kütüphaneler:**
   - Pygame kütüphanesinin yüklü olması gerekir. Pygame'i yüklemek için terminal veya komut istemcisine aşağıdaki komutu yazın:
     ```bash
     pip install pygame
     ```

2. **Dosyayı İndirme:**
   - Bu projeyi bir Python dosyası olarak bilgisayarınıza indirin ve çalıştırmaya başlayın.

 Oyun Kontrolleri

**Ok Tuşları:** Yılanı yönlendirmek için kullanılır.
  - Sol: Yılanı sola hareket ettirir.
  - Sağ: Yılanı sağa hareket ettirir.
  - Yukarı: Yılanı yukarı hareket ettirir.
  - Aşağı: Yılanı aşağı hareket ettirir.
  
  **Oyun Bittiğinde:**
  - **Q:** Oyundan çıkmak için kullanılır.
  - **C:** Oyunu yeniden başlatmak için kullanılır.

Oyun Ekranı

- **Yılan:** Beyaz renk ile gösterilen yılan, yılanın hareket ettiği her kareyi temsil eder.
- **Yem:** Yeşil renk ile gösterilen yiyecekler, yılanın yemesi gereken nesneler olup her yendikçe yılanın uzunluğu artar.

## Oyun Kuralları

1. Oyuncu, yılanı yönlendirerek ekrandaki yemleri toplar.
2. Yılanın boyu her yem yedikçe uzar.
3. Eğer yılan kendisine çarparsa veya ekranın dışına çıkarsa, oyun sona erer ve oyuncuya "Oyun Bitti!" mesajı verilir.
4. Oyuncu, oyun bittiğinde 'Q' tuşuna basarak çıkabilir veya 'C' tuşuna basarak oyuna devam edebilir.

 Oyun Kaynak Kodu

Proje, Python ve Pygame kütüphanesi kullanılarak yazılmıştır. Ana oyun fonksiyonu, yılanın hareketini ve yemleri oluşturmayı yönetir. Oyun sona erdiğinde kullanıcıya yeniden başlama veya çıkma seçenekleri sunulmaktadır.

Geliştirme ve İleri Seviye Özellikler

- Oyun, temel bir yılan hareketi ve yem toplama mantığına dayanır. Geliştirilmesi için ek özellikler şunlar olabilir:
- Yılanın hızının zamanla artması.
- Farklı seviyeler veya engeller eklenmesi.
- Oyun puanının ve yılanın uzunluğunun gösterilmesi.

Lisans

Bu proje, **MIT Lisansı** ile lisanslanmıştır.
