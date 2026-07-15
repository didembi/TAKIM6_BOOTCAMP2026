**Takım İsmi**
Bootcamp_6 

**Takım Elemanları**
- Çağrı Yaman: Product Owner
- Merve Papakçı: Scrum Master
- Didem Bilek, Larissa Fındık: Team Member/Developer

* **Ürün İle İlgili Bilgiler**

<img width="480" height="480" alt="Nori_App" src="https://github.com/user-attachments/assets/673985e8-caa9-4d39-a88f-e37835373c62" />

* **Ürün İsmi**
NORI

* **Ürün Açıklaması**
NORI, kullanıcının çalışma ve planlama eğilimlerini kısa, literatür temelli bir testle ölçüp buna göre kişiye özel bir görev, not ve bildirim kurulumu oluşturan bir başlatma asistanıdır. Test sonucuna göre her ayar (bildirim sıklığı, görev görünümü, hatırlatma tonu gibi) ayrı ayrı ve gerekçesiyle birlikte belirlenir; sistem kullanıcıya bir kişilik etiketi veya tanı koymaz. Böylece kullanıcı, kendi çalışma biçimine baştan uygun kurulmuş bir sistemle başlar.


* **Ürün Özellikleri**

* **Ürün Özellikleri (MVP kapsamı)**
+ Literatür temelli davranış modeli (6 eksen: dışadönüklük, yapı ihtiyacı, zaman algısı, motivasyon kaynağı, başlangıç eğilimi, odaklanma biçimi)
+ Kısa bir davranış testiyle kişiye özel ilk kurulum
+ Kişiye özel görev, not ve bildirim yapısı
+ Hızlı not alma ve serbest notu otomatik aksiyona çeviren yapay zeka desteği (Gemini)
+ Mobil uygulama (Expo/React Native)

* **Yol Haritası (MVP sonrası)**
+ Widget özelliğiyle kişiye özel görsel hatırlatıcılar
+ Uygulama kullanım verileriyle davranış yapısının kalibrasyonu
+ Sesli giriş ve web özelliği

* **Hedef Kitle**
-Görevlerini, notlarını ve hatırlatmalarını daha kolay yönetmek isteyen bireysel kullanıcılar.
-Karmaşık üretkenlik uygulamalarını kullanmakta zorlanan kişiler.
-Kendi sistemini kurmak istemeyen, hazır ve sade bir düzen isteyen kullanıcılar.
-Günlük işlerini, fikirlerini ve sorumluluklarını hızlıca kaydetmek isteyen kişiler.
-Unutma, erteleme, dağılma veya başlamakta zorlanma yaşayan kullanıcılar.
-Öğrenciler.
-Yeni mezunlar.
-Yeni işe başlayanlar.
-Freelancer’lar.
-Yoğun çalışan bireyler.
-Kişisel hayatını ve günlük sorumluluklarını takip etmek isteyen kullanıcılar.
-Notion, Trello, Todoist, Calendar gibi araçları fazla detaylı bulan kişiler.
-Basit, kişisel ve düşük eforla kullanılabilecek bir çalışma alanı isteyen kullanıcılar.
-Kişiye göre ayarlanan ama kullanıcıdan fazla kurulum istemeyen bir uygulamaya ihtiyaç duyan kişiler.
-15 - 65 yaş arası kullanıcılar


* **Product Backlog URL**
https://docs.google.com/spreadsheets/d/1Oc5r0HrK7seuu4GETN-rs6MKXqWmuY4PbOpDjk-Eme4/edit?usp=sharing


**Sprint 1**

* **Backlog düzeni ve Story seçimleri:** Backlog'umuz ilk yapılacak story'lere göre düzenlenmiştir. Story'ler yapılacak işlere (task'lere) bölünmüştür. Notion Board'da gözüken yıldızlı görevler önceliklendirilmiştir ve görevlerin kişi ataması yapılmıştır. Story başına çıkan tahmin puanı, toplam puanın yarısından azdır (2. Sprint toplamı 46 puan, en büyük madde 5 puandır). Backlog ve burndown yapısı, ilerlemeyi tek görünümde özetlemek amacıyla Notion'a ek olarak sunum ve paylaşım amacıyla Google Sheets'e de aktarılmıştır.

* **Daily Scrum:** Ekip üyelerinin uygunluk saatleri farklı olduğu için canlı günlük toplantı yerine Salı, Perşembe ve gerektiğinde Cumartesi günleri düzenli senkron toplantıları yapılmaktadır. Bu sprintte toplantı araları için ayrı bir günlük check-in uygulanmamıştır.
Daily Scrum toplantı notları Readme'de tarafımızdan paylaşılmaktadır: https://app.notion.com/p/38ff7b8e4c9880eab8cce2a29fef7a3e?v=391f7b8e4c988031b59c000c928786f1&source=copy_link

* **Sprint board update:** Sprint board screenshotları:

<img width="882" height="831" alt="Sprint_Board" src="https://github.com/user-attachments/assets/2b92e829-12a1-4955-a8d0-c10f6f07ee10" />


* **Ürün Durumu**:
Ekran görüntüleri:

<img width="337" height="751" alt="image" src="https://github.com/user-attachments/assets/2de70786-9878-4e43-9f0f-1065ab4b1e59" />

<img width="342" height="732" alt="image" src="https://github.com/user-attachments/assets/7b469177-38c1-4bc8-ba51-8d0437e099e6" />

* **Sprint Review:** 
Alınan kararlar: Ürünün davranışsal eksen yapısı ve puanlama mantığı literatür taramasıyla belirlendi (6 eksen: dışadönüklük, yapı ihtiyacı, zaman algısı, motivasyon kaynağı, başlangıç eğilimi, odaklanma biçimi). Preset/argmax tabanlı bir model test edildi, yanlış sonuç ürettiği görülünce derleyici modeline (her ayarın bağımsız kuraldan üretilmesi) geçildi. 15 ayarlık kural tablosu ve 12 soruluk quiz taslağı çıkarıldı. MVP'nin 8 modülü ve tech stack'i (Expo, Supabase, Gemini, EAS, Vercel) netleşti. Derleyici ve eksen-ayar ilişkisini gösteren iki basit interaktif demo hazırlandı.

* **Sprint Review katılımcıları:**
  Merve Papakçı , Çağrı Yaman, Larissa Fındık , Didem Bilek

* **Sprint Retrospective:**

Takım içindeki görev dağılımıyla ilgili düzenleme yapılması kararı alınmıştır.
Görevlendirilmelerin sistematik ilerlemesi için notion kullanımı aktifleştirilmiştir. 
Rakip uygulamaların geribildirimlerinin gözden geçirilmesi önceliklendirilmiştir.



---

# Sprint 2

* **Uygulama Ekran Görüntüleri:**
........

*  **Proje Yönetimi:**
* **Sprint board update:** Sprint board screenshotları:

<img width="781" height="837" alt="image" src="https://github.com/user-attachments/assets/ef600e95-c4de-47d4-bba9-57bec2b6e13c" />

<img width="765" height="848" alt="image" src="https://github.com/user-attachments/assets/7d19e84d-423f-4457-b270-eb0cb4045733" />

<img width="777" height="759" alt="image" src="https://github.com/user-attachments/assets/355569d5-f027-402d-a1ee-ce4d05d4b47b" />


* **Burndown Chart:**
........

* **Sprint Notes:**
* İkinci sprintte, uygulamanın anahatları belirlendi. Demo görüntüleri Çağrı Yaman tarafından hazırlandı.
* Premium plan notları alındı, gelecek planlarına eklendi.
* Nori uygulamamıza maskot eklenmesibe karar verildi, Larissa Fındık görselleri hazırladı ve dailylerde görüntüleri revize edildi.
* Uygulama öncesi demo için hazırlanan anket soruları belirlendi, anket dağıtımı yapıldı ve revizeler yapıldı.
* Compiler demosu hazırlandı.
* Rutin ekleme için ayrı bir kısım eklemek yerine görevler sayfasına eklenmesine karar verildi.
* Önemli görülen görev ekleme butonu (+) alt sekmenin ortasında olmasına karar verildi.
* Anasayfa, görevler, görev ekle butonu, notlar ve takvim sayfalarının UI/UX kısımları revize edildi.
* KVKK belgesi hazırlandı, ekipçe gözden geçirildi, tekrar incelenecek. Demo anketine kısaca KVKK notu eklendi.
* Rakip uygulamaların kullanımı gözden geçirildi.
* 
* 

* **Sprint Review Participants:**
Merve Papakçi, Çağrı Yaman, Larissa Fındık, Didem Bilek

* **Sprint Retrospective:**


* **Expected point completion within Sprint:**
.........
* **Point Completion Logic:**

A total target of ..... points was set. .... points were completed in the first sprint. In the second sprint, the overall completion of the codes was requested, a target of ... points was set and completed. In the third sprint, a target of .... points was set as the remaining tasks would be completed and integration work would be carried out.

* **Daily Scrum:** Ekip üyelerinin uygunluk saatleri farklı olduğu için toplsntı saatleri ve günleri haftaiçi 3 gün ve aralıklı olacakk şekilde ayarlandı, ör; Çarşamba, Cuma, Pazar. 
Daily Scrum toplantı notları: https://app.notion.com/p/38ff7b8e4c9880eab8cce2a29fef7a3e?v=391f7b8e4c988031b59c000c928786f1&source=copy_link


# Sprint 3

---



