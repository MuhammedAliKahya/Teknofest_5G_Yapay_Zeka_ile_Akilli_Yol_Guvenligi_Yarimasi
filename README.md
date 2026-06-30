# Teknofest 5G Yapay Zeka ile Akıllı Yol Güvenliği
Burada sizlerle kaynak kodlarını ve kaggle da ki veri setlerini uzaktan indirmemizi sağlayacak python kodlarını paylaşıyorum.

### 📂 Veri Seti İndirme Betikleri (Data Download Scripts)

Projede kullanılan spesifik YOLOv8 veri setlerini doğrudan Roboflow üzerinden lokal ortamınıza (Ubuntu) indirmek için aşağıdaki Python betiklerini kullanabilirsiniz. 

> ⚠️ **Not:** Güvenlik nedeniyle betiklerin içerisindeki `api_key` alanları maskelenmiştir. Çalıştırmadan önce kendi Roboflow API anahtarınızı eklemeniz gerekmektedir.

| Dosya Adı | Görevi / Açıklaması | Hedef Modül |
| :--- | :--- | :--- |
| `telefon_indir.py` | Telefon algılama veri setini Roboflow'dan otomatik indirir. | Sürücü Dikkat Takibi |
| `oyuncak_indir.py` | Oyuncak araba algılama veri setini Roboflow'dan otomatik indirir. | Nesne Tespiti / Test |
| `plaka_indir.py` | Türk plakası algılama veri setini Roboflow'dan otomatik indirir. | Araç Tanıma Sistemi |
| `yorgunluk_sigara_indir.py` | Sürücü yorgunluk ve sigara tüketimi veri setini Roboflow'dan otomatik indirir. | Sürücü İzleme Sistemi (DMS) |
