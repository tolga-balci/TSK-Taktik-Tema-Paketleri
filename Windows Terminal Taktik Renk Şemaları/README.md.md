# Windows Terminal Taktik Renk Şemaları

Bu klasör, Windows Terminal uygulamanıza doğrudan entegre edebileceğiniz, TSK ve Bayraktar askeri renk paletlerine ait bağımsız `.json` şemalarını içerir.

## 📂 Klasör İçeriği

* `Windows Terminal - TSK Kara Kuvvetleri Nano.json` - Kara Kuvvetleri piksel kamuflaj renkleri.

![TSK  Kara Kuvvetleri Nano](/Grafikler/Fastfetch-TSK-Kara-Kuvvetleri-Nano.png)

* `Windows Terminal - TSK Deniz Kuvvetleri Mavi.json` - Deniz Kuvvetleri ve SAT/SAS marin renkleri.

![TSK Deniz Kuvvetleri Mavi](/Grafikler/Fastfetch-TSK-Deniz-Kuvvetleri-Mavi.png)

* `Windows Terminal - TSK Çöl Nano.json` - Güneydoğu ve sınır ötesi kurak bölge renkleri.

![TSK Çöl Nano](/Grafikler/Fastfetch-TSK-Çöl-Nano.png)

* `Windows Terminal - TSK Kış Nano (Açık Mod).json` - Kış dağ operasyonları gündüz safhası renkleri.

![TSK Kış Nano (Açık Mod)](/Grafikler/Fastfetch-TSK-Kış-Nano-(Açık-Mod).png)

* `Windows Terminal - TSK Kış Gece Operasyonu.json` - Kış dağ operasyonları gece safhası tonları.

![TSK Kış Gece Operasyonu](/Grafikler/Fastfetch-TSK-Kış-Gece-Operasyonu.png)

* `Windows Terminal - Bayraktar Taktik` - Baykar İHA/SİHA sistem arayüz ve gövde renkleri.

![Bayraktar Taktik](/Grafikler/Fastfetch-Bayraktar-Taktik.png)

## ⚙️ Kurulum Adımları

1. Windows Terminal uygulamasını açın.
2. `Ctrl + ,` kısayolunu kullanarak veya sekme çubuğundaki aşağı ok simgesine tıklayıp **Ayarlar**'ı seçin.
3. Sol menünün en altında bulunan **JSON dosyasını aç** seçeneğine tıklayın.
4. Açılan `settings.json` dosyası içinde `"schemes": []` dizisini (array) bulun.
5. Bu klasör içindeki şemalardan kullanmak istediğiniz dosyanın içeriğini kopyalayarak köşeli parantezlerin `[]` içine yapıştırın.
   * *Not: Birden fazla şema ekliyorsanız, şema bloklarının arasına virgül koymayı unutmayın.*
6. Dosyayı kaydedin (`Ctrl + S`).
7. Windows Terminal ayarlar arayüzüne geri dönün. Profilinizin (örn. PowerShell veya Ubuntu) **Görünüm (Appearance)** sekmesine gelerek eklediğiniz yeni TSK temasını seçip uygulayın.