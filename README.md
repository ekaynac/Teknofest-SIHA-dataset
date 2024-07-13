### Teknofest 2022 Savaşan İHA Yarışması için OTUS UCAV takımımızca modelimize eğitilen verisetinin ham halidir.


# Veriseti Hakkında Bilgiler
* Olduğu haliyle Ultralytics YOLOv5(v6.2 branch'iyle denenmiştir.) ile uygun formattadır.
* 8815 training, 2650 validation verisi var.
* Bütün videolar tek bir Youtube kanalından (Süleyman Demir - https://www.youtube.com/channel/UC6niKT4b2D9rVnyHpC1O2BQ) toplanıp uçuşun hızına, model uçakların görüntüdeki konumlarının değişim hızına göre 3-10 FPS arası değerlerle çerçevelenmiştir. Dosyaların isimlerinden hangi videoların verisetine dahil edildiği kontrol edilebilir. Bu dataset hazırlandıktan sonra yeni yüklenen videoları da gözden geçirmek isteyebilirsiniz.
* Bütün görüntüler drone yahut model uçak üzerinden alınmış, model uçak görüntüleridir. Bu sayede uygun ışıklandırmada kareler yakalanmış olup ufuk çizgisinin altında ve üstünde dağılıma dikkat edilmiştir.
* Ufuk çizgisinin altındaki arkaplanın yarışmanın da gerçekleşeceği alana (Samsun Çarşamba Havalimanı) uygun olması genelde gözetilmiştir.

# Tavsiyeler 
* Modele eğitmeden önce veriyi gözden geçirmeli, tanımalısınız.
* Güncellenecek yarışma şartnamesi ve isterleri doğrultusunda, kendi yazılım/donanım planınıza göre bu verisetini süzebilirsiniz.
* Kendi etiketledikleriniz yahut internetten bulduğunuz başka setle karabilirsiniz.
* Yüzde kaç boş arkaplan beslediğimizi hatırlamıyorum. Her frame'in bir label dosyası var, boş arkaplanların label dosyaları da var ama içi boş. Boş label dosyaları scriptle saydırılarak bulunabilir.
* Bu verisetiyle hızlı, küçük bir model eğitip (yolov5s gibi) eğittiğiniz bu modelle başka videoları otomatik olarak etiketleyebileceğiniz bir script yazabilirsiniz. Modeliniz ne kadar iyi olursa olsun otomatik etiketlenen verileri her zaman kontrol etmenizde fayda var. Modelin kendi çıktılarıyla aynı modeli tekrar eğitmeye kalkarsanız overfitting yaşanabilir. Elle kontrol edin, küçük de olsa değişiklikler yapın.
* Başka herhangi bir sorunuz olursa, link kırık çıkarsa bana Linkedin üzerinden yahut mail yoluyla ulaşabilirsiniz.

Link: https://drive.google.com/drive/folders/1LCiuzozpEgzTaHTvKu5msNCe9T3KD925?usp=sharing
