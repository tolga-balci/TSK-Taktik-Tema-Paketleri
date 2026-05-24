# Gemini-CLI Taktik Renk Şemaları

Bu klasör, `gemini-cli` terminal tabanlı yapay zeka istemcinizin arayüzünü, zengin metin (Markdown) çıktılarını, tablolarını ve sınır çizgilerini TSK ve Bayraktar askeri renk paletleriyle entegre etmek için gereken iç içe geçmiş (nested) JSON şemalarını ve görsel önizlemelerini içerir.

> Farklı ekran görüntüleri için Grafikler dizini altındaki `fastfetch` çıktılarını gösteren ekran görüntülerine bakabilirsiniz.

---
## Kurulum ve Manuel Yapılandırma Kılavuzu

`gemini-cli` yapılandırma motorunun harici dosyaları tararken sorun yaşamaması için en kararlı yöntem, ana ayar dosyası üzerinden doğrudan ilgili tema dosyasını doğrudan hedef göstermektir (hardcoding).

1. Kullanmak istediğiniz temanın JSON dosyasını gemini'ın themes dizini içine kaydedin. Linux/WSL2 için bu dizinin yolu aşağıdaki gibidir:

``` bash
/home/<<your_user_name>>/.gemini/themes/
```

`themes` dizini yoksa sizin oluşturmanız gerekir.

2. Linux/WSL2 ortamınızda `gemini-cli` ana yapılandırma dosyasını düzenlemek için gemini-cli'nin ayarlar dosyasını kullandığınız metin editörü ile açın:

```bash
~/.gemini/settings.json
```


2. Dosya içeriğindeki `"ui"` bloğunu bulun ve `"currentTheme"` değerine kullanmak istediğiniz temanın **tam mutlak dosya yolunu (absolute path)** yazın.

Örnek olarak, aktif temayı **Bayraktar Taktik** yapmak için `settings.json` dosyanızı şu şekilde güncelleyin:

``` json
{
  "security": {
    "auth": {
      "selectedType": "oauth-personal"
    }
  },
  "general": {
    "defaultApprovalMode": "default",
    "sessionRetention": {
      "maxAge": "30d"
    }
  },
  "ui": {
    "currentTheme": "/home/<<your_user_name>>/.gemini/themes/gemini-cli - Bayraktar Taktik.json",
    "enableColors": true
  }
}
```

3. Dosyayı kaydedip çıkın. `gemini-cli` aracını başlattığınızda doğrudan hedef gösterdiğiniz taktik şema yüklenecektir. Başka bir temaya geçmek istediğinizde `"currentTheme"` satırındaki dosya adını değiştirmeniz yeterlidir.
   
## Dizin İçeriği ve Tema Önizlemeleri

Aşağıda, her temanın örnek görünümlerini inceleyebilirsiniz:

- `gemini-cli - TSK Kara Kuvvetleri Nano.json` - Kara Kuvvetleri piksel kamuflaj renkleri.

![TSK Kara Kuvvetleri Nano](/Grafikler/gemini-cli-TSK-Kara-Kuvvetleri-Nano.png)

- `gemini-cli - TSK Çöl Nano.json` - Güneydoğu ve sınır ötesi kurak bölge renkleri.

![TSK Çöl Nano](/Grafikler/gemini-cli-TSK-Çöl-Nano.png)

- `gemini-cli - TSK Kış Nano (Açık Mod).json` Kış dağ operasyonları gündüz safhası renkleri.

![TSK Kış Nano (Açık Mod)](/Grafikler/gemini-cli-TSK-Kış-Nano-(Açık-Mod).png)

- `gemini-cli - TSK Kış Gece Operasyonu.json` - Kış dağ operasyonları gündüz safhası renkleri.

![TSK Kış Gece Operasyonu](/Grafikler/gemini-cli-TSK-Kış-Gece-Operasyonu.png)

- `gemini-cli - TSK Deniz Kuvvetleri Mavi.json` - Deniz Kuvvetleri ve SAT/SAS marin renkleri.

![TSK Deniz Kuvvetleri Mavi](/Grafikler/gemini-cli-TSK-Deniz-Kuvvetleri-Mavi.png)

- `gemini-cli - TSK Hava Kuvvetleri.json` - Geleneksel taktik havacılık grileri ve uzun süreli kullanımlarda gözü dinlendiren soft aviyonik kokpit yeşili.

![Hava Kuvvetleri](/Grafikler/gemini-cli-TSK-Hava-Kuvvetleri.png)

- ``

![Hava Kuvvetleri KAAN Stealth](/Grafikler/gemini-cli-TSK-Hava-Kuvvetleri-Kaan-Stealth.png)

- 

![Hava Kuvvetleri Kızılelma Avionics](/Grafikler/gemini-cli-TSK-Hava-Kuvvetleri-Kızılelma-Avionics.png)

- `gemini-cli - Bayraktar Taktik.json` - Baykar İHA/SİHA sistem arayüz ve gövde renkleri.

![Bayraktar Taktik](Grafikler/gemini-cli-Bayraktar-Taktik.png)