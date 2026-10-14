# 💰 Modern Bütçe ve Finans Planlama Uygulaması

Kişisel bütçenizi, gelir ve giderlerinizi, kategori bazlı limitlerinizi ve birikim hedeflerinizi takip edebileceğiniz modern ve responsive web uygulaması.

---

## 🚀 Özellikler

1. **📊 Genel Bakış (Dashboard):**
   - Anlık Net Bakiye, Bu Ayki Gelir, Bu Ayki Gider ve Tasarruf Oranı kartları.
   - Kategori bazlı harcama dağılımı (İnteraktif Doughnut Grafiği).
   - Son 6 aya ait gelir ve gider trendi (İkili Bar Grafiği).
   - Kategori bütçe sınırları ve son 5 işlem akışı.

2. **💳 Gelir ve Gider Takibi:**
   - Kategori, ödeme yöntemi, tutar ve tarih bazlı işlem ekleme / düzenleme / silme.
   - Anlık metin araması (açıklama ve not içinde arama).
   - Tür (Gelir/Gider), Kategori ve Dönem (Bu Ay, Önceki Ay, Tüm Zamanlar) filtreleri.
   - Filtrelenen sonuçların anlık toplam gelir, gider ve net fark hesaplaması.

3. **🎯 Kategori Bütçe Limitleri:**
   - Her gider kategorisi için özel aylık tavan harcama limiti belirleme.
   - İlerleme çubukları (Güvenli, %85+ Uyarı, %100+ Aşım Uyarısı).
   - Limit aşıldığında dinamik uyarı bannerı ve animasyonlu rozetler.
   - Planlanan bütçe vs fiili harcama karşılaştırma grafiği.

4. **🏆 Birikim ve Gelecek Hedefleri:**
   - Hedef tutar, mevcut birikim ve hedef tarih ile fon oluşturma.
   - Hızlı para yatırma ve çekme aksiyonları.
   - Kalan gün sayacı ve ilerleme yüzdesi.
   - Hedefe (%100) ulaşıldığında konfeti kutlaması! 🎉

5. **📈 Raporlar ve Analiz:**
   - Günlük ortalama harcama tutarı.
   - Ayın en yüksek tekil harcaması.
   - En çok harcanan kategori ve sıralı kategori harcama dağılım listesi.

6. **⚙️ Veri Yönetimi ve Dışa Aktarma:**
   - Microsoft Excel uyumlu UTF-8 CSV dökümü alma.
   - Tam JSON yedeği oluşturma ve dosyadan geri yükleme.
   - Tek tıkla demo verilerini geri yükleme veya tüm verileri temizleme.
   - Tarayıcının `LocalStorage` belleğinde tamamen yerel ve güvenli saklama.

---

## 💻 Nasıl Çalıştırılır?

Hiçbir harici bağımlılık veya `npm install` gerektirmez.

1. **Doğrudan Tarayıcıda Açma:**
   - `index.html` dosyasına çift tıklayarak istediğiniz tarayıcıda (Chrome, Safari, Edge, vb.) açabilirsiniz.

2. **Yerel Sunucu ile Çalıştırma (Önerilen):**
   ```bash
   # Python ile:
   python3 -m http.server 8080

   # veya npx serve ile:
   npx serve .
   ```
   Ardından tarayıcınızdan `http://localhost:8080` adresine gidin.
