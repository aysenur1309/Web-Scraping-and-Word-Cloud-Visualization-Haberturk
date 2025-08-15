# Web-Scraping-ve-Word-Cloud-G-rselle-tirme-Habert-rk
Bu proje habertürk.com sitesinden web scraping teknikleriyle metinleri çekmeyi ve en sık geçen kelimeleri Word Cloud ile görselleştirerek içerik hakkında hızlı bir genel bakış sağlamayı göstermektedir.

# Türkçe Haber Web Scraping ve Word Cloud Görselleştirme

Bu proje, Python kullanarak **Habertürk sitesinden veri çekme**, **içerik analizi** ve **WordCloud görselleştirmesi** yapmayı göstermektedir.  

Projede kullanılan başlıca teknolojiler:  
- **Python 3**  
- **Requests** (Web sayfası çekme)  
- **BeautifulSoup** (HTML parse etme)  
- **WordCloud** (Kelime bulutu oluşturma)  
- **Matplotlib** (Görselleştirme)  
- **Pandas, NumPy, PIL** (veri işleme ve görselleştirme desteği)

---

##  Özellikler

1. **Web Scraping**  
   - Haber sitelerinden `<h1>`, `<h2>`, `<p>` ve `<a>` etiketleri çekilir.  
   - Resmi haber alanları ve içerik detayları BeautifulSoup ile parse edilir.  

2. **Metin Analizi ve Word Cloud**  
   - Çekilen haber içerikleri bir `.txt` dosyasına kaydedilir veya direkt okunur.  
   - WordCloud ile sık kullanılan kelimeler görselleştirilir.  
   - Stopwords ve arka plan rengi gibi parametreler özelleştirilebilir.  

3. **Türkçe içerik desteği**  
   - Türkçe karakterler (`ç, ğ, ü, ş`) sorunsuz şekilde okunur.  
   - Gerekirse `errors="ignore"` veya `encoding="cp1254"` kullanılarak karakter hataları önlenir.

---

## 📂 Kullanım

1. Proje klasöründe `İş Bankası.txt` veya haber metni dosyasını hazırla.  
2. Gerekli Python kütüphanelerini yükle:  
```bash
pip install requests beautifulsoup4 wordcloud matplotlib pillow numpy pandas

