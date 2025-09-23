# Akbank Derin Öğrenme Bootcamp Projesi
Bu proje, CNN (Convolutional Neural Network) kullanılarak NEU Steel Surface Defect Classification System veri setinde AI-Powered Industrial Quality Control sistemini başarıyla çalıştırmayı hedefler.
# Veri Seti
NEU Steel Surface Defect Classification veri seti Kaggle üzerinden temin edilmiştir. 
# Kullanılan Yöntemler
Proje kapsamında; veri önişleme, veri çoğaltma (data augmentation), CNN tabanlı model oluşturma,  sample count, hiperparametre optimizasyonu ve model değerlendirmesi gibi adımlar uygulanacaktır.
# Elde Edilen Sonuçlar ve Yorumlama
* Test Doğruluğu
Eğitilen model, %99.63 oranında eğitildi. Bu oran modelimizin daha önce hiç görmediği görüntüleri neredeyse kusursuz bir şekilde ayırabildiğini gösterir.
* Sınıf Bazlı Performans Analizi
Sınıflandırma raporu ile modelimizin her bir sınıf için performansını daha net görebiliriz.
1.000 DOĞRULUK ORANINA ULAŞMIŞ SINIFLAR: Crazing (Yüzey Çatlaması - İnce Çizgisel Kusurlar), Inclusion (Dahil Edilmiş Yabancı Madde Kusurları), Rolled (Haddeleme Kaynaklı Kusurlar) ve Straches (Çizik ve Kazınma Kusurları)
0.99 DOĞRULUK ORANINA ULAŞMIŞ SINIFLAR: Patches (Yama Benzeri Yüzey Kusurları) ve Pitted (Çukurlu Yüzey Kusurları)
* SONUÇLARIN ÖZETİ
Genel olarak, model tüm sınıflarda dengeli ve başarılı bir performans göstermiştir. Bu sonuçlar, projenin amacına ulaştığını ve geliştirilen CNN modelinin kalite kontrol problemi için etkili bir çözüm sunduğunu göstermektedir.
