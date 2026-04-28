# ontoloji_gelistirme

1. Proje Hakkında
Bu proje, içeceklerin hiyerarşik yapısını, özelliklerini ve aralarındaki mantıksal
ilişkileri tanımlamak amacıyla geliştirilmiş bir OWL (Web Ontology Language)
modelidir. Proje, hem sıcak hem de soğuk içecekleri kapsayan geniş bir
taksonomi sunar.

2. Ontolojik Yapı
Sınıf Hiyerarşisi (Class Hierarchy)
icecek: Temel ana sınıf.
sicak_icecek: Çay, Kahve, Sıcak Çikolata.
soguk_icecek: Ayran, Cola, Limonata, Meyve Suyu, Süt.

Özellikler (Properties)
Object Properties: kafeinli, sütlü, raf_omru (kısa/uzun).
Data Properties: omur uzunlugu (sayısal veri girişi için).

3. Mantıksal Kurallar ve Kısıtlamalar
Ontolojide bireyler üzerinde belirli kısıtlamalar (Restrictions) tanımlanmıştır.
Örneğin:

- Kafeinli sıcak içecek bireyi, Arabica sınıfından değerler alacak
şekilde kısıtlanmıştır.

- Sütlü soğuk içecek bireyi, Badem Sütü içerecek şekilde
tanımlanmıştır.

4. Kullanım
Bu dosya Protégé veya benzeri ontoloji editörleri ile açılabilir. SPARQL sorguları
ile içecekler arasında filtreleme yapılabilir.
