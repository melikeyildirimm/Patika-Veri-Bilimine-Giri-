# Patika-Veri-Bilimine-Giris-
Merhabalar,

Bir biyomedikal mühendisi olarak, çalışmalarımızda kullandığımız ROC Analizinden bahsetmek istedim. 



ROC eğrisi, ikili sınıflandırma sistemlerinde ayrım eşik değerinin farklılık gösterdiği durumlarda, hassasiyetin kesnliğe olan oranıyla ortaya çıkmaktadır. ROC daha basit anlamda doğru pozitiflerin, yanlış pozitiflere olan kesri olarak da ifade edilebilir. Her sınıflandırma işleminde yapıldığı gibi, metotlar kesinlik (yanlış pozitifleri eleme kabiliyeti) ve hassasiyet (doğru pozitifleri tespit etme kabiliyeti) arasındaki dengeyi kurmakla uğraşmaktadır. Veri kümesindeki pozitif ve negatif örnekler, eşit bir şekilde dağılım göstermediğinden dolayı, doğrudan kesinlik ve hassasiyet ölçütlerinden önce, ROC kısaltması ile Receiver Operating Characteristics adı verilen eğri, kesinlik ve hassasiyet arasındaki dengeyi değerlendirmek için kullanılmıştır. ROC eğrisi altında kalan alan ROC puanı olarak tanımlanabilir. ROC eğrisi değişen sınıflandırma eşik değerlerine göre doğru pozitiflerin sayısının, yanlış pozitiflerin bir fonksiyonu olarak çizilmesiyle oluşmaktadır. ROC puanı 1 (bir) olduğunda anlamı, pozitifler mükemmel bir şekilde negatiflerden ayrılmıştır, olmaktadır. ROC puanı 0 (sıfır) olduğunda ise herhangi bir pozitif bulunamadı anlamına gelir. 



ROC eğrisi, tanı testinin kendi doğruluğunu tanımlaması ve testler arasında güvenilir bir karşılaştırma yapmaya olanak sağlaması açısından sıklıkla kullanılmaktadır. ROC eğrisinin grafiksel yaklaşımı ölçümlerin duyarlılığı ve özgüllüğü arasındaki ilişkileri kavramayı kolay kılar. ROC eğrisi, tanı koymak amacıyla kullanılan bir değişkenin değişim genişliği içinde aldığı tüm değerlerin sırasıyla kesim noktası kabul edilmesiyle hesaplanacak duyarlılık değerlerinin, testin yanlış pozitif oranına (1 - özgüllük) karşı noktalanması ile elde edilir. ROC eğrisinin oluşturulacağı koordinat sisteminde, Y ekseninde tanı testinin gerçek pozitif değeri (duyarlılık), X ekseninde ise yanlış pozitif değeri (1-özgüllük) yer alır. Her kesim noktasındaki doğru pozitif ve yanlış pozitife karşılık gelen noktalar birleştirilerek ROC eğrisi çizilir. 





 

ROC eğrisinin altında kalan alanın büyüklüğü üzerinde çalışılan tanı testinin ayırma yeteneğinin istatistiksel olarak önemini gösterir. Üzerinde çalışılan tanı testinin hiç ayırma yeteneği olmadığı durumda ROC eğrisi altındaki alanın beklenen değeri 0.50’dir. Mükemmel bir test ise sıfır yanlış pozitif ve sıfır yanlış negatif ile alanın değeri 1.00 olacaktır. Test, bu iki değerin arasında bir alana sahip olmalıdır. Eğri altındaki alanların yorumlanmasında aşağıda verilen derecelendirmeler kullanılabilir.  



90-1.00 = mükemmel.

80-.90 = iyi . 

70-.80 = orta . 

60-.70 = zayıf . 

