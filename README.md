# TAKIM
## **Takım İsmi**
Bootcamp_6 

## **Takım Üyeleri**
- Çağrı Yaman: Product Owner
- Merve Papakçı: Scrum Master
- Didem Bilek: Team Member/Developer
- Larissa Fındık: Team Member/Developer

## **Ürün İle İlgili Bilgiler**
**Ürün Logosu:** 
<img width="1045" height="1024" alt="NORI-LOGO" src="https://github.com/user-attachments/assets/017802d4-9a20-4815-817a-ab4ce3fbda51" />

**Ürün İsmi**: 
**NORI**

**Ürün Açıklaması:**
NORI, kullanıcının çalışma ve planlama eğilimlerini kısa, literatür temelli bir testle ölçüp buna göre kişiye özel bir görev, not ve bildirim kurulumu oluşturan bir başlatma asistanıdır. Test sonucuna göre her ayar (bildirim sıklığı, görev görünümü, hatırlatma tonu gibi) ayrı ayrı ve gerekçesiyle birlikte belirlenir; sistem kullanıcıya bir kişilik etiketi veya tanı koymaz. Böylece kullanıcı, kendi çalışma biçimine baştan uygun kurulmuş bir sistemle başlar.

**Ürün Özellikleri (MVP kapsamı):**
+ Literatür temelli davranış modeli (6 eksen: dışadönüklük, yapı ihtiyacı, zaman algısı, motivasyon kaynağı, başlangıç eğilimi, odaklanma biçimi)
+ Kısa bir davranış testiyle kişiye özel ilk kurulum
+ Kişiye özel görev, not ve bildirim yapısı
+ Hızlı not alma ve serbest notu otomatik aksiyona çeviren yapay zeka desteği (Gemini)
+ Mobil uygulama (Expo/React Native)

**Yol Haritası (MVP sonrası):**
+ Widget özelliğiyle kişiye özel görsel hatırlatıcılar
+ Uygulama kullanım verileriyle davranış yapısının kalibrasyonu
+ Sesli giriş ve web özelliği

**Hedef Kitle:**
* Görevlerini, notlarını ve hatırlatmalarını daha kolay yönetmek isteyen bireysel kullanıcılar.
* Karmaşık üretkenlik uygulamalarını kullanmakta zorlanan kişiler.
* Kendi sistemini kurmak istemeyen, hazır ve sade bir düzen isteyen kullanıcılar.
* Günlük işlerini, fikirlerini ve sorumluluklarını hızlıca kaydetmek isteyen kişiler.
* Unutma, erteleme, dağılma veya başlamakta zorlanma yaşayan kullanıcılar.
* Öğrenciler.
* Yeni mezunlar.
* Yeni işe başlayanlar.
* Freelancer’lar.
* Yoğun çalışan bireyler.
* Kişisel hayatını ve günlük sorumluluklarını takip etmek isteyen kullanıcılar.
* Notion, Trello, Todoist, Calendar gibi araçları fazla detaylı bulan kişiler.
* Basit, kişisel ve düşük eforla kullanılabilecek bir çalışma alanı isteyen kullanıcılar.
* Kişiye göre ayarlanan ama kullanıcıdan fazla kurulum istemeyen bir uygulamaya ihtiyaç duyan kişiler.
* 15 - 65 yaş arası kullanıcılar


## **Product Backlog URL:**
https://docs.google.com/spreadsheets/d/1Oc5r0HrK7seuu4GETN-rs6MKXqWmuY4PbOpDjk-Eme4/edit?usp=sharing


# **Sprint 1**

**Backlog düzeni ve Story seçimleri:**

Backlog'umuz ilk yapılacak story'lere göre düzenlenmiştir. Story'ler yapılacak işlere (task'lere) bölünmüştür. Notion Board'da gözüken yıldızlı görevler önceliklendirilmiştir ve görevlerin kişi ataması yapılmıştır. Story başına çıkan tahmin puanı, toplam puanın yarısından azdır (2. Sprint toplamı 46 puan, en büyük madde 5 puandır). Backlog ve burndown yapısı, ilerlemeyi tek görünümde özetlemek amacıyla Notion'a ek olarak sunum ve paylaşım amacıyla Google Sheets'e de aktarılmıştır.

**Daily Scrum:**

Ekip üyelerinin uygunluk saatleri farklı olduğu için canlı günlük toplantı yerine Salı, Perşembe ve gerektiğinde Cumartesi günleri düzenli senkron toplantıları yapılmaktadır. Bu sprintte toplantı araları için ayrı bir günlük check-in uygulanmamıştır.
Daily Scrum toplantı notları Readme'de tarafımızdan paylaşılmaktadır: https://app.notion.com/p/38ff7b8e4c9880eab8cce2a29fef7a3e?v=391f7b8e4c988031b59c000c928786f1&source=copy_link

**Sprint board update:**

<img width="882" height="831" alt="Sprint_Board" src="https://github.com/user-attachments/assets/2b92e829-12a1-4955-a8d0-c10f6f07ee10" />


**Uygulama Ekran Görüntüleri:**

<img width="337" height="751" alt="image" src="https://github.com/user-attachments/assets/2de70786-9878-4e43-9f0f-1065ab4b1e59" />

<img width="342" height="732" alt="image" src="https://github.com/user-attachments/assets/7b469177-38c1-4bc8-ba51-8d0437e099e6" />


**Sprint Review:** 

* Ürünün davranışsal eksen yapısı ve puanlama mantığı literatür taramasıyla belirlendi (6 eksen: dışadönüklük, yapı ihtiyacı, zaman algısı, motivasyon kaynağı, başlangıç eğilimi, odaklanma biçimi).
* Preset/argmax tabanlı bir model test edildi, yanlış sonuç ürettiği görülünce derleyici modeline (her ayarın bağımsız kuraldan üretilmesi) geçildi. 15 ayarlık kural tablosu ve 12 soruluk quiz taslağı çıkarıldı.
* MVP'nin 8 modülü ve tech stack'i (Expo, Supabase, Gemini, EAS, Vercel) netleşti.
* Derleyici ve eksen-ayar ilişkisini gösteren iki basit interaktif demo hazırlandı.

**Sprint Review katılımcıları:**
Merve Papakçı , Çağrı Yaman, Larissa Fındık , Didem Bilek

**Sprint Retrospective:**
Takım içindeki görev dağılımıyla ilgili düzenleme yapılması kararı alınmıştır.
Görevlendirilmelerin sistematik ilerlemesi için notion kullanımı aktifleştirilmiştir. 
Rakip uygulamaların geribildirimlerinin gözden geçirilmesi önceliklendirilmiştir.



---

# Sprint 2

**Uygulama Ekran Görüntüleri:**

<img width="682" height="711" alt="NORI_V1" src="https://github.com/user-attachments/assets/e41671e3-1165-41cd-bf62-41e845c991e0" />
<img width="667" height="711" alt="NORI_V2" src="https://github.com/user-attachments/assets/b230f47e-1955-49a0-8c54-232ee25c6bd4" />
<img width="667" height="702" alt="NORI_V3" src="https://github.com/user-attachments/assets/f4639722-bb9e-43b7-8144-f92b9facff19" />
<img width="666" height="706" alt="NORI_V4" src="https://github.com/user-attachments/assets/92879f3e-1014-4638-a807-36903b85f7b7" />




**Sprint board update:**

<img width="781" height="837" alt="image" src="https://github.com/user-attachments/assets/ef600e95-c4de-47d4-bba9-57bec2b6e13c" />

<img width="765" height="848" alt="image" src="https://github.com/user-attachments/assets/7d19e84d-423f-4457-b270-eb0cb4045733" />

<img width="777" height="759" alt="image" src="https://github.com/user-attachments/assets/355569d5-f027-402d-a1ee-ce4d05d4b47b" />



**Burndown Chart:**
https://docs.google.com/spreadsheets/d/1K7aoCyKwaoIPFr4JiVXm1FRCqpFOtzmnwsN72bEN6ls/edit?usp=sharing

**Sprint Review Participants:**
Merve Papakçi, Çağrı Yaman, Larissa Fındık, Didem Bilek

**Sprint Notes:**

* İkinci sprintte Nori'nin bilgi mimarisi ve temel ürün sınırları netleştirildi. Stable bottom navigation yapısı `Home / Tasks / Add / Notes / Calendar` olarak belirlendi.
* Routines için ayrı bir bottom-navigation alanı oluşturmak yerine Tasks içerisinde sibling bölüm olarak konumlandırılmasına karar verildi.
* Merkezi Add butonunun bulunduğu sayfaya göre contextual çalışması kararlaştırıldı. Home üzerinde içerik türü seçimi; Tasks, Notes ve Calendar üzerinde ise ilgili içerik tipinin doğrudan eklenmesi benimsendi.
* Altı adaptive axis; dışsallaştırma, yapı/özerklik, zaman farkındalığı, sözel-görsel temsil, göreve başlama ve odak/geçiş hassasiyeti olarak yeniden tanımlandı. Sistem persona veya tanı üretmeyecek şekilde continuous score temeline oturtuldu.
* Preset/argmax yaklaşımı bırakılarak her surface ve ayarın bağımsız, deterministic ve açıklanabilir kurallarla derlendiği compiler yapısı detaylandırıldı.
* Home, Tasks, Widget ve Notification compiler davranışları; axis çakışmaları ve kullanıcı override öncelikleriyle birlikte map edildi.
* Home'un execution, Tasks'in ise inventory/organization yüzeyi olması kararlaştırıldı. Tasks layout seçimi kullanıcıya bırakıldı.
* TIME High ve FOCUS High gibi çakışmalarda ihtiyaçlardan birinin silinmesi yerine Plan ve Focus yüzeylerinin birlikte çalıştığı composition modeli oluşturuldu.
* Spatial Planner'ın, takvim ve rutinlerdeki sabit blokların yanında flexible günlük görevlerin zaman çizgisine yerleştirilmesini sağlamasına karar verildi.
* Notes layout'unun compiler tarafından zorunlu değiştirilmemesi, kullanıcının List/Bento tercihini kendisinin yapması kararlaştırıldı.
* AI sisteminin chatbot yerine request fulfiller olarak çalışması; AI çıktılarının uygulamadan önce kullanıcıya gösterilmesi, düzenlenmesi ve onaylanması kararlaştırıldı. Personalized memory, davranış geçmişinden öğrenme ve arka planda otomatik sınıflandırma kapsam dışı bırakıldı.
* Android-first React Native + Expo, local-first encrypted database ve ilerleyen aşamada Supabase sync yönü kesinleştirildi.
* Ürün, domain model, adaptive axes, compiler, AI, design system, teknik mimari, MVP delivery ve karar kayıtlarını içeren kanonik proje dokümantasyonu hazırlandı.
* Codex ve Claude Code'un aynı repository üzerinden çalışabilmesi için ortak AGENTS.md protokolü, WORKLOG handoff yapısı ve Decision Log disiplini oluşturuldu.
* Private GitHub repository oluşturuldu ve production proje yapısı burada başlatıldı.
* npm workspaces tabanlı Expo SDK 57 / React Native 0.86 mobil scaffold'u oluşturuldu.
* İlk production vertical slice uygulandı: görev oluşturma → Tasks → Show on Home → Home → Focus → tamamlama → process restart sonrası state'in korunması.
* Local persistence katmanında Drizzle migration, SecureStore tabanlı key yönetimi ve SQLCipher entegrasyonu uygulandı.
* Windows'taki non-ASCII proje yolunun Node.js prebuild sırasında oluşturduğu hata teşhis edildi. Repository OneDrive/Türkçe karakterli yoldan `C:\Projects\NORI-Productivity-App` konumuna taşındı.
* Pixel 7 API 36 emulator üzerinde clean prebuild ve development build başarıyla tamamlandı.
* DL-034 görev akışı ve process restart persistence emulator üzerinde doğrulandı.
* SQLCipher 4.7.0 runtime doğrulandı. Yanlış veya eksik anahtarın mevcut database'i okuyamadığı, verinin silinmediği ve DB/WAL dosyalarında sentinel içeriğin plaintext bulunmadığı kanıtlandı.
* Final doğrulamada lint, workspace typecheck, 6/6 test, Android build ve Expo Doctor 20/20 kontrolü geçti.
* Fiziksel Android cihaz, gerçek upgrade ve backup/restore doğrulamaları açık gate olarak bir sonraki çalışmaya taşındı.
* Premium plan fikirleri gelecek planına kaydedildi; payment/subscription sistemi MVP kapsamına alınmadı.
* Nori için maskot kullanılmasına karar verildi. Larissa Fındık tarafından hazırlanan görseller ekip görüşmeleri doğrultusunda revize edildi.
* Demo anketi soruları hazırlandı, dağıtıldı ve alınan geri bildirimlerle revize edildi.
* KVKK belgesi hazırlandı ve ekip tarafından ilk kez gözden geçirildi; nihai hukuk/uyum incelemesi açık madde olarak bırakıldı.
* Rakip productivity uygulamalarının onboarding, task organization ve kullanım sürtünmeleri incelendi.
- Sprint 2 sonunda proje yalnız tasarım ve compiler demosu seviyesinde kalmamış, gerçek Android production repository'sine geçirilmiştir. Ürünün stable bilgi mimarisi, altı adaptive axis'i, deterministic compiler sınırları ve Home/Tasks ayrımı belgelenmiştir.
- Expo SDK 57 ve React Native 0.86 tabanlı mobil altyapı oluşturulmuş; ilk uçtan uca görev akışı local encrypted repository üzerinden uygulanmıştır. Pixel 7 API 36 emulator üzerinde development build açılmış, görev akışı ve process restart persistence doğrulanmıştır.-
- SQLCipher runtime testi sonucunda database'in şifreli çalıştığı, yanlış veya eksik anahtarla okunamadığı ve test içeriğinin DB/WAL dosyalarında plaintext bulunmadığı kanıtlanmıştır. Otomatik doğrulamada lint, typecheck, 6/6 test, Android build ve Expo Doctor 20/20 sonucu alınmıştır.
- Fiziksel Android cihaz, upgrade ve backup/restore doğrulamaları tamamlanmadığı için OPEN-DL-005 bütünüyle kapatılmamıştır. Bir sonraki teknik adım fiziksel cihaz kabul testi; sonraki ürün dilimi ise onboarding, 12 soruluk değerlendirme, axis scoring ve deterministic compiler entegrasyonudur.

**Sprint Retrospective:**

- KVKK belgesi hâlâ "tekrar incelenecek" durumda kalmış, 3. Sprint'e açık madde olarak taşınıyor.
- Sprint kapsamı önemli ölçüde büyüdü (Sprint başında 46 puanlık plan, şu an 96 puana çıktı); bunun sebebi netleştirilip 3. Sprint planlamasında kapsam disiplinine dikkat edilmesi kararlaştırıldı.
- Tasarım (maskot, UI/UX), araştırma (anket, KVKK) ve teknik (compiler demo) işlerin paralel yürütülmesi verimli oldu, bu çalışma biçimi sürdürülecek.
- Compiler ve tasarım demosu ile production implementation'ın aynı şey olmadığı netleştirildi. Bundan sonraki sprint raporlarında `tasarlandı`, `kodlandı`, `emulator üzerinde doğrulandı` ve `fiziksel cihazda doğrulandı` statüleri ayrı raporlanacaktır.
- Uzun ve OneDrive tarafından senkronize edilen non-ASCII proje yolunun native build araçlarında hata üretebildiği görüldü. Kalıcı development repository'si kısa ve ASCII bir path'e taşındı.
- Native ve security capability'lerin yalnız config seviyesinde tamamlandı sayılmaması; development build ve runtime kanıtıyla gate kapatılması benimsendi.
- Sprint sırasında kapsamın 46 puandan 96 puana çıkması planlama görünürlüğünü zorlaştırdı. Yeni teknik işlerin sprint board'a eklenmeden “tamamlandı” sayılmaması ve sprint dışı eklemelerin ayrıca işaretlenmesi kararlaştırıldı.
- AI destekli hızlı geliştirme süreci ilerlemeyi hızlandırdı; ancak test, physical-device evidence, security ve decision-log gereksinimlerinin azaltılmaması kararlaştırıldı.

**Expected point completion within Sprint:**

2. Sprint için toplam 96 puanlık iş planlandı/eklendi, bunun 53 puanı bu ara değerlendirmede tamamlanmış durumda (16 puan hâlâ To Do/In Progress'te, geri kalanı Backlog'da bekliyor).

**Point Completion Logic:**

Sprint başında 46 puanlık bir hedef belirlendi. Sprint ilerledikçe kapsamı genişleten yeni işler eklendi (tasarım, KVKK, anket, video, dokümantasyon), toplam 96 puana çıktı. Bu ara değerlendirmede 53 puan tamamlandı, 43 puan kalan iştir. 3. Sprint'te kalan modül testlerinin bitirilmesi ve entegrasyon çalışmalarının yapılması hedeflenmektedir.

**Daily Scrum:** 

Ekip üyelerinin uygunluk saatleri farklı olduğu için toplsntı saatleri ve günleri haftaiçi 3 gün ve aralıklı olacak şekilde ayarlandı, ör; Çarşamba, Cuma, Pazar/ Salı, Perşembe, Pazar
Daily Scrum toplantı notları: 
https://app.notion.com/p/38ff7b8e4c9880eab8cce2a29fef7a3e?v=391f7b8e4c988031b59c000c928786f1&source=copy_link


# Sprint 3

---



