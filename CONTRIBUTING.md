# Katkıda Bulunma Rehberi (Contributing Guidelines)

**Teslimiyet ve Hiçlik** (`teslimiyet-ve-hiclik`) reposuna katkıda bulunmak istediğiniz için teşekkür ederiz! Bu depo, İslam düşünce geleneğinde kurban, teslimiyet, hiçlik (fena) ve adanmışlık kavramları üzerine oluşturulmuş, açık kaynaklı bir bilgi, tefekkür ve felsefe arşividir.

Bu projenin zenginleşmesi için her türlü edebi, tasavvufi, sosyolojik veya sanatsal katkıya açığız. Ancak deponun bütünlüğünü korumak adına lütfen aşağıdaki kurallara dikkat ediniz.

## 📝 Ne Tür Katkılar Bekliyoruz?

- **Tasavvuf ve İrfan:** Büyük mutasavvıfların (İbn Arabi, Mevlana, Şems, Gazzali vb.) teslimiyet ve hiçlik üzerine sözleri, makale çevirileri veya kitap özetleri.
- **Kur'an ve Sünnet:** Kurban ibadetinin felsefesi ve ayet tefsirleri (Hac ve Saffat sureleri merkeze alınarak).
- **Edebi Yansımalar:** Divan edebiyatında veya modern şiirde canı feda etme, aşk uğruna yanma (Şem ve Pervane) temalı incelemeler.
- **Sosyolojik Okumalar:** Modern çağın putları (statü, para, oto-sömürü) ve Ali Şeriati'nin Hacc kavramı ekseninde denemeler.
- **Görsel Sanatlar:** Konuya uygun Hüsn-i Hat (Kaligrafi) çalışmaları, estetik ve mistik dijital çizimler veya banner tasarımları.

## ⚙️ Nasıl Katkıda Bulunabilirsiniz?

1. **Repoyu Fork'layın:** Sağ üst köşedeki "Fork" butonuna tıklayarak projenin bir kopyasını kendi hesabınıza alın.
2. **Dal (Branch) Oluşturun:** Yapacağınız değişiklikler için yeni bir branch açın.
   ```bash
   git checkout -b katki-yeni-makale-adi
   ```
3. **Değişikliklerinizi Yapın:** İlgili klasörün altına `.md` (Markdown) formatında yazınızı ekleyin.
4. **Markdown Kurallarına Uyun:**
   - Dosyalarınızda mutlaka bir ana başlık (`# Başlık`) bulunmalıdır.
   - Uzun metinleri alt başlıklara (`## Alt Başlık`) ayırarak okunabilirliği artırın.
   - Önemli alıntıları `> "Alıntı"` formatında italik olarak vurgulayın.
5. **Commit Edin:** Anlamlı bir commit mesajı yazın.
   ```bash
   git commit -m "Tasavvuf klasörüne Mevlana'nin teslimiyet anlayisi eklendi"
   ```
6. **Push Edin:**
   ```bash
   git push origin katki-yeni-makale-adi
   ```
7. **Pull Request (PR) Açın:** Orijinal repoya gelerek "Compare & pull request" butonuna tıklayın ve katkınızı açıklayan kısa bir metin yazın.

## ⚖️ Lisans ve Telif Hakkı

Bu repoya gönderdiğiniz tüm katkılar **Creative Commons Attribution 4.0 International (CC BY 4.0)** lisansı altında kamuya açık hale gelecektir. Başka kaynaklardan yaptığınız doğrudan alıntılarda mutlaka kaynak (kitap/yazar ismi) belirtmeyi unutmayınız.

*Teslimiyette ve hiçlikte buluşmak dileğiyle...*
