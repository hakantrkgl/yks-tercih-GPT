# YKS Tercih Verileri Deposu

Bu depo, 2023 yılı için Türkiye'deki üniversite programlarına ilişkin kapsamlı veri setlerini içermektedir. Veriler, farklı puan türleri ve alanlara göre kategorize edilmiştir. Bu veri setleri, YÖK Atlas'ın açık verilerinden alınmış olup, üniversite programları hakkında yerleştirme puanları, kontenjanlar, doluluk oranları ve daha fazlasını içeren detaylı bilgiler sunmaktadır. Bu veriler, yükseköğrenim istatistikleri ve Türkiye'deki eğitim trendleri ile ilgilenen öğrenciler, eğitimciler ve araştırmacılar için hayati öneme sahiptir.

## İçerik

- **Sayısal Program Verileri.json:** Sayısal (numerik) kategorideki programlar için puanlar, kontenjanlar ve yerleştirmeler hakkında bilgiler içerir.
- **Eşit Ağırlık Program Verileri.json:** Eşit ağırlık kategorisindeki programlar için kapsamlı bilgiler sunar.
- **Sözel Program Verileri.json:** Sözel kategorideki programlar hakkında puanlar ve öğrenci yerleştirmeleri detaylarını içerir.
- **Dil Program Verileri.json:** Dil puanı türüne dayalı programlar için öğrenci kabulleri ve program kontenjanları hakkında detaylı bilgiler içerir.

## Dosya Yapısı

Bu depo, her bir kategorideki programlar için ayrıntılı bilgiler sunan çeşitli JSON dosyalarını içermektedir:

- **Sayısal Program Verileri:**
- **Eşit Ağırlık Program Verileri:**  
- **Sözel Program Verileri:**
- **Dil Program Verileri:**
  

## Veri Setlerinin İçeriği

Her bir JSON dosyası, ilgili kategoriye ait programlar hakkında aşağıdaki bilgileri içermektedir:

- **Program ID:** Her programın benzersiz kimliği.
- **Üniversite Adı:** Programın sunulduğu üniversitenin adı.
- **Program Adı:** Programın tam adı.
- **Fakülte / Yüksekokul:** Programın bağlı olduğu fakülte veya yüksekokul.
- **Öğretim Dili ve Süresi:** Programın öğretim dili ve süresi (örneğin, İngilizce, 4 Yıllık).
- **Burs Durumu:** Programın burs durumu (örneğin, Burslu, %50 İndirimli, Ücretsiz).
- **Şehir:** Programın bulunduğu şehir.
- **Üniversite Türü:** Üniversitenin türü (örneğin, Devlet, Vakıf).
- **Kontenjanlar:** Programın yıllara göre genel ve okul birincisi kontenjanları.
  - **Genel Kontenjan:** Genel yerleştirme için ayrılan kontenjan.
  - **Okul Birincisi Kontenjanı:** Okul birincileri için ayrılan kontenjan.
  - **Toplam Kontenjan:** Genel ve okul birincisi kontenjanlarının toplamı.
- **Yerleşen Öğrenci Sayıları:** Programın yıllara göre yerleşen öğrenci sayıları.
  - **Genel Kontenjana Yerleşen:** Genel kontenjana yerleşen öğrenci sayısı.
  - **Okul Birincisi Kontenjanına Yerleşen:** Okul birincisi kontenjanına yerleşen öğrenci sayısı.
  - **Toplam Yerleşen:** Genel ve okul birincisi kontenjanlarına yerleşen toplam öğrenci sayısı.
- **Taban Puanlar:** Programın yıllara göre taban puanları.
  - **0.12 Katsayı ile Yerleşen Son Kişinin Puanı:** 0.12 katsayısı ile yerleşen son kişinin puanı.
  - **0.12 + 0.06 Katsayı ile Yerleşen Son Kişinin Puanı:** 0.12 + 0.06 katsayısı ile yerleşen son kişinin puanı.
- **Başarı Sıraları:** Programın yıllara göre başarı sıraları.
  - **0.12 Katsayı ile Yerleşen Son Kişinin Başarı Sırası:** 0.12 katsayısı ile yerleşen son kişinin başarı sırası.
  - **0.12 + 0.06 Katsayı ile Yerleşen Son Kişinin Başarı Sırası:** 0.12 + 0.06 katsayısı ile yerleşen son kişinin başarı sırası.
- **Doluluk Oranları:** Programın yıllara göre doluluk oranları.
  - **İlk Yerleşme Oranı:** İlk yerleştirme sonucunda doluluk oranı.
  - **Boş Kalan Kontenjan:** Boş kalan kontenjan sayısı.
  - **Yerleşip Kayıt Yaptırmayan:** Yerleşip kayıt yaptırmayan öğrenci sayısı.
  - **Ek Yerleşen:** Ek yerleştirme ile yerleşen öğrenci sayısı.
- **Yerleşenlerin Ortalama OBP'si:** Yerleşen öğrencilerin ortalama OBP (Ortaöğretim Başarı Puanı) puanı.
- **Yerleşenlerin Ortalama Diploma Notu:** Yerleşen öğrencilerin ortalama diploma notu.
- **Tavan Puanlar:** Programın yıllara göre tavan puanları.
  - **0.12 Katsayı ile Yerleşen Son Kişinin Tavan Puanı:** 0.12 katsayısı ile yerleşen son kişinin tavan puanı.
  - **0.12 + 0.06 Katsayı ile Yerleşen Son Kişinin Tavan Puanı:** 0.12 + 0.06 katsayısı ile yerleşen son kişinin tavan puanı.
- **Tavan Başarı Sıraları:** Programın yıllara göre tavan başarı sıraları.
  - **0.12 Katsayı ile Yerleşen Son Kişinin Tavan Başarı Sırası:** 0.12 katsayısı ile yerleşen son kişinin tavan başarı sırası.
  - **0.12 + 0.06 Katsayı ile Yerleşen Son Kişinin Tavan Başarı Sırası:** 0.12 + 0.06 katsayısı ile yerleşen son kişinin tavan başarı sırası.
- **Yerleşenlerin Ortalama Puanları:** Yerleşen öğrencilerin ortalama puanları.
  - **Ortalama OBP:** Ortaöğretim Başarı Puanı ortalaması.
  - **Ortalama Diploma Notu:** Diploma notu ortalaması.

Bu detaylı bilgiler, her bir program hakkında kapsamlı analizler yapmanıza ve karşılaştırmalar gerçekleştirmenize olanak tanır.

## Nasıl Kullanılır?

Bu veri setlerini kullanarak, üniversite programlarının çeşitli metriklerini analiz edebilir, karşılaştırmalar yapabilir ve 2023 yılı için eğitim trendlerini inceleyebilirsiniz. Veriler JSON formatında olduğu için, kolayca işlenebilir ve analiz edilebilir durumdadır.

## YKS Tercih GPT?
Vermiş olduğumuz linkten YKS Tercih GPT'si aracılığıyla da kullanabilirsiniz. Bu GPT'nin amacı, Türkiye'deki üniversiteler ve bölümler hakkında ayrıntılı bilgi sağlamaktır. Özellikle, belirli bir üniversite ve bölüm için taban puanlar, başarı sıralamaları, kontenjanlar, yerleşen öğrenci sayıları ve burs olanakları gibi bilgileri sunmak için tasarlanmıştır. Bu tür bilgiler, üniversite tercihi yapacak öğrenciler için oldukça önemlidir.
https://chatgpt.com/g/g-ZakGOaTOW-yks-tercih

## İletişim
Herhangi bir sorunuz veya geri bildiriminiz için lütfen bizimle iletişime geçin.

https://www.linkedin.com/in/hakanturkgl/
https://twitter.com/hakantrkgl



