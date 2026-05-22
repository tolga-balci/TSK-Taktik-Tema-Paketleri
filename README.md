# Windows Terminal TSK ve Taktik Savunma Tema Paketi

Bu paket, **Türk Silahlı Kuvvetleri (TSK)** bünyesinde kullanılan resmi kamuflaj desenleri, renk kodları ve **Baykar Bayraktar İHA/SİHA** sistemlerinin kokpit, gövde ve yer kontrol istasyonu arayüzleri esas alınarak hazırlanmış, Windows Terminal için özel taktik renk profillerini içerir. 

Temalar, askeri gerçekçilik ile komut satırı okunabilirliğini, kontrastını ve taranabilirliğini en üst düzeyde tutacak şekilde optimize edilmiştir.

---

## 🎖️ Paket İçeriğindeki Temalar

| Tema Adı | Operasyonel Anlayış ve İlham Kaynağı | Tasarım Modu |
| :--- | :--- | :--- |
| **TSK Kara Kuvvetleri Nano** | TÜBİTAK iş birliğiyle geliştirilen resmi TSK Nano-Kamuflaj deseni. Gri-yeşil, kum-haki ve toprak kahverengi renklerini içerir. | Koyu Mod (Dark) |
| **TSK Deniz Kuvvetleri Mavi** | Dz.K.K. üniforma tasarımları, SAT/SAS dijital deniz kamuflajları ve savaş gemisi mavi-gri (haze-gray) renklerini içerir. | Koyu Mod (Dark) |
| **TSK Çöl Nano** | Sınır ötesi, yüksek rakımlı kurak bölge ve çöl operasyonlarında kullanılan pikselize kum, pembe-haki ve koyu çöl kahvesi renklerini içerir. | Koyu Mod (Dark) |
| **TSK Kış Nano** | Yüksek irtifa kış arama/kurtarma ve dağ komando operasyonları için geliştirilen, alpin beyazını donuk mavi ve kaya gölgeleriyle harmanlayan yüksek kontrastlı renkleri içerir. | Açık Mod (Light) |
| **TSK Kış Gece Operasyonu** | Kış dağ operasyonlarının gece safhası düşünülerek hazırlanan, terminali buzul grisi ve donmuş granit gölgelerine bürüyen renkleri içerir. | Koyu Mod (Dark) |
| **Bayraktar Taktik** | Bayraktar TB2 ve Akıncı TİHA gövde renkleri (mat kompozit gri), telemetri kehribarı, lazer hedefleme turuncusu ve HUD arayüz mavisi (cyan) renklerini içerir. | Koyu Mod (Dark) |

---

## ⚙️ Kurulum Kılavuzu

Bu renk profillerini Windows Terminal ortamınızda kullanmak için aşağıdaki adımları takip edin:

1. **Windows Terminal** uygulamasını açın.
2. `Ctrl + ,` kısayolunu kullanarak veya sekme çubuğundaki aşağı ok simgesine tıklayıp **Ayarlar**'ı seçin.
3. Ayarlar arayüzünün sol alt köşesinde bulunan **JSON dosyasını aç** seçeneceğine tıklayın.
4. Açılan `settings.json` dosyası içinde `"schemes": []` dizisini (array) bulun.
5. Bu depodan kopyaladığınız JSON tema bloklarını köşeli parantezlerin `[]` içine yapıştırın (Birden fazla tema ekliyorsanız, aralarına virgül koymayı unutmayın).
6. Dosyayı kaydedin (`Ctrl + S`).
7. Windows Terminal ayarlar arayüzüne geri dönün. Sol menüden varsayılan profilinizi (örneğin PowerShell veya Komut İstemi) seçin, **Görünüm** sekmesine gelin ve **Renk şeması** açılır menüsünden eklediğiniz taktik temayı seçip kaydedin.

---

## 📄 JSON Tema Kodları

Windows Terminal settings.json dosyanıza kolayca kopyalayıp yapıştırabilmeniz için JSON kod bloklarını aşağıda paylaşıyorum. 
Eğer indirmek isterseniz depomdaki /JSON dizini altından ilgili JSON dosyalarını indirebilirsiniz.


### 1. TSK Kara Kuvvetleri Nano

```json
{
    "name": "TSK Kara Kuvvetleri Nano",
    "cursorColor": "#D0A97E",
    "selectionBackground": "#4E5443",
    "background": "#1E1F1A",
    "foreground": "#E0DCD3",
    "black": "#2A2C24",
    "blue": "#5D6353",
    "cyan": "#8A947E",
    "green": "#465239",
    "purple": "#7A6855",
    "red": "#7E4E43",
    "white": "#D9D6CE",
    "yellow": "#AC926D",
    "brightBlack": "#3D4135",
    "brightBlue": "#7A8270",
    "brightCyan": "#A3B096",
    "brightGreen": "#5F704E",
    "brightPurple": "#96816C",
    "brightRed": "#A16355",
    "brightWhite": "#F2EFE9",
    "brightYellow": "#C7AB82"
}
```

![TSK  Kara Kuvvetleri Nano](/Grafikler/TSK-Kara-Kuvvetleri-Nano.png)


2. TSK Deniz Kuvvetleri Mavi

``` json
{
    "name": "TSK Deniz Kuvvetleri Mavi",
    "cursorColor": "#4EA8DE",
    "selectionBackground": "#1D2D44",
    "background": "#0D131A",
    "foreground": "#E1E5EB",
    "black": "#1A232E",
    "blue": "#214E75",
    "cyan": "#4A90E2",
    "green": "#2B7A78",
    "purple": "#52677A",
    "red": "#8B2635",
    "white": "#F8F9FA",
    "yellow": "#E5A93C",
    "brightBlack": "#2E3D52",
    "brightBlue": "#3A7CA5",
    "brightCyan": "#70A6FF",
    "brightGreen": "#3AA6A3",
    "brightPurple": "#708090",
    "brightRed": "#B23B4E",
    "brightWhite": "#FFFFFF",
    "brightYellow": "#F4D03F"
}
```
![TSK Deniz Kuvvetleri Mavi](/Grafikler/TSK-Deniz-Kuvvetleri-Mavi.png)

3. TSK Çöl Nano

```json
{
    "name": "TSK Col Nano",
    "cursorColor": "#D9A066",
    "selectionBackground": "#8B7355",
    "background": "#1F1B16",
    "foreground": "#EEDC82",
    "black": "#3A322A",
    "blue": "#857560",
    "cyan": "#C5B358",
    "green": "#9F815B",
    "purple": "#A67B5B",
    "red": "#8C4F43",
    "white": "#F4E3B1",
    "yellow": "#D2B48C",
    "brightBlack": "#52463B",
    "brightBlue": "#9E8E77",
    "brightCyan": "#DEC974",
    "brightGreen": "#BC9B6A",
    "brightPurple": "#C29372",
    "brightRed": "#A86557",
    "brightWhite": "#FFF5D6",
    "brightYellow": "#E6C280"
}
```

![TSK Çöl Nano](/Grafikler/TSK-Çöl-Nano.png)

4. TSK Kış Nano (Açık Mod)

``` json
{
    "name": "TSK Kis Nano",
    "cursorColor": "#2C3E50",
    "selectionBackground": "#CBD5E1",
    "background": "#F4F7F6",
    "foreground": "#2A2F35",
    "black": "#3A4146",
    "blue": "#6C7A89",
    "cyan": "#7B9095",
    "green": "#5E6B65",
    "purple": "#8A7D75",
    "red": "#9E4A42",
    "white": "#FFFFFF",
    "yellow": "#B59975",
    "brightBlack": "#4F5B62",
    "brightBlue": "#8FA3B5",
    "brightCyan": "#99AAB0",
    "brightGreen": "#798A81",
    "brightPurple": "#A3968E",
    "brightRed": "#BA5A50",
    "brightWhite": "#F8FAFC",
    "brightYellow": "#CCA677"
}
```
![TSK Kış Nano (Açık Mod)](/Grafikler/TSK-Kış-Nano-(Açık-Mod).png)


5. TSK Kış Gece Operasyonu

``` json
{
    "name": "TSK Kis Gece Operasyonu",
    "cursorColor": "#E2E8F0",
    "selectionBackground": "#334155",
    "background": "#14171A",
    "foreground": "#EAF0F1",
    "black": "#1E2326",
    "blue": "#4F6272",
    "cyan": "#5C768D",
    "green": "#4D5B54",
    "purple": "#736861",
    "red": "#943D3D",
    "white": "#D1DCDA",
    "yellow": "#9A8161",
    "brightBlack": "#323A3E",
    "brightBlue": "#6C8296",
    "brightCyan": "#7CA1C1",
    "brightGreen": "#657A6F",
    "brightPurple": "#8C7E76",
    "brightRed": "#B54F4F",
    "brightWhite": "#FFFFFF",
    "brightYellow": "#BAA082"
}
```

![TSK Kış Gece Operasyonu](/Grafikler/TSK-Kış-Gece-Operasyonu.png)

6. Bayraktar Taktik

``` json
{
    "name": "Bayraktar Taktik",
    "cursorColor": "#F39C12",
    "selectionBackground": "#2C3E50",
    "background": "#1A1D20",
    "foreground": "#E5E8E8",
    "black": "#2B3035",
    "blue": "#34495E",
    "cyan": "#1ABC9C",
    "green": "#2ECC71",
    "purple": "#7D3C98",
    "red": "#C0392B",
    "white": "#BDC3C7",
    "yellow": "#D35400",
    "brightBlack": "#4F565E",
    "brightBlue": "#5D6D7E",
    "brightCyan": "#48C9B0",
    "brightGreen": "#58D68D",
    "brightPurple": "#9B59B6",
    "brightRed": "#E74C3C",
    "brightWhite": "#F4F6F6",
    "brightYellow": "#F39C12"
}
```
![Bayraktar Taktik](/Grafikler/Bayraktar-Taktik.png)