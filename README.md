# TSK Taktik Terminal ve Ortam Temaları Paketi

Bu paket, **Türk Silahlı Kuvvetleri (TSK)** bünyesinde kullanılan resmi kamuflaj desenleri, renk kodları ve **Baykar Bayraktar İHA/SİHA** yer kontrol istasyonu arayüzleri esas alınarak hazırlanmış taktik renk profillerini ve ortam yapılandırmalarını içerir. Bu projenin temel amacı terminal çerçevelerini ve `gemini-cli` gibi terminal tabanlı yapay zeka/markdown motoru çıktılarını askeri gerçekçilik ile yüksek komut satırı okunabilirliğine uygun şekilde senkronize etmektir. 

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

## 📂 Depo Dizin Yapısı ve Alt Kılavuzlar

Proje mimarisi modüler olarak tasarlanmıştır. Kurulum adımları ve ilgili ham dosyalara erişmek için aşağıdaki dizin bağlantılarını kullanabilirsiniz:
### 💻 [1. Windows Terminal Renk Şemaları (`/windows-terminal`)](./windows-terminal/)
* Windows Terminal `settings.json` profiline eklenebilecek bağımsız `.json` şemalarını ve terminal içi kurulum adımlarını içerir.

### 🤖 [2. Gemini-CLI & Ortam Değişkeni Entegrasyonları (`/gemini-cli`)](./gemini-cli/)
* `gemini-cli` ve diğer markdown tabanlı terminal CLI araçlarının renk düzeninizi ezmesini engellemek için gerekli olan **24-bit TrueColor (`$COLORTERM`)** ortam yapılandırma seçeneklerini (WSL2, PowerShell, CMD) içerir.

> Milli savunma, TSK ve yerli havacılık operasyon estetiğine uygun olarak geliştirilmiştir.

## 📥 Hızlı Kurulum (Git CLI)

Bu depoyu makinenize klonlamak için:

```bash
git clone [https://github.com/tolga-balci/tsk-tactical-terminal-themes.git](https://github.com/tolga-balci/tsk-tactical-terminal-themes.git)
```

## 📚 Referanslar ve Kaynakça (References & Citations)

Bu projede yer alan renk şemaları ve askeri desen profilleri, Türk Silahlı Kuvvetleri'nin modernizasyon projelerine ait resmi akademik kayıtlara, ulusal basın arşivlerine ve tekstil mühendisliği çalışmalarına dayandırılmıştır.

### 1. Ulusal Basın ve Resmi Proje Arşivleri
* **Hürriyet Gazetesi.** (14 Mayıs 2011). *Mehmetçik’e Arzu Kaprol imzalı yeni ’nano’ üniforma.* [Çevrimiçi Erişim]. 
  * *Not: TSK Kara Kuvvetleri'nin pikselize nano-kamuflaj desenlerinin ergonomik tasarımı ve TÜBİTAK Ar-Ge entegrasyonu sürecine ilişkin birincil kaynak haber dökümantasyonu.*
* **Milliyet Gazetesi.** (14 Mayıs 2011). *Mehmetçik yeni ’nano’ üniformasıyla görünmez olacak.* Ekonomi Bölümü.
  * *Not: TÜBİTAK Marmara Araştırma Merkezi (MAM) tarafından geliştirilen ve kızılötesi (IR) görünmezlik sağlayan akıllı kumaş teknolojisinin renk/desen seçimi detayları.*

### 2. Akademik ve Sektörel Yayınlar (Tekstil Mühendisliği ve Savunma)
* **TÜBİTAK Marmara Araştırma Merkezi (MAM).** *Savunma Teknolojileri ve Tekstil Malzemeleri Proje Raporları.* (Malzeme Enstitüsü Arşivi).
  * *Not: Türkiye'nin coğrafi bitki örtüsü ve toprak yapısına uygun renk korelasyon algoritmalarının belirlendiği TSK Nano-Kamuflaj projesinin teknik altyapısı.*
* **Milli Savunma Bakanlığı (MSB).** (2011). *TSK Üniforma ve Teçhizat Modernizasyonu Teknik Şartnameleri.* Ankara.
  * *Not: Kara, Deniz ve Hava Kuvvetleri komutanlıklarının resmi operasyonel kamuflaj standartları (Çöl, Kış ve Deniz operasyon sahaları renk spektrumları).*

### 3. Dijital Atıf Formatı (Repository Citation)
Eğer bu projeyi kendi çalışmalarınızda kaynak olarak göstermek isterseniz, aşağıdaki formatı kullanabilirsiniz:

``` 
Balcı, T. (2026). TSK Taktik Terminal ve Ortam Temaları Paketi (Versiyon 1.0.0). 
GitHub Repository: [https://github.com/tolga-balci/tsk-tactical-terminal-themes](https://github.com/tolga-balci/tsk-tactical-terminal-themes)
```
