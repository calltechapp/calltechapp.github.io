---
title: "Calltech'ten Akademik Katkı: Türkçe Sesli Verilerde STT Model Karşılaştırması"
layout: single
date: 2025-04-15
author_profile: true
tags: [konuşmadan-metne, whisper, wav2vec2, yapayzeka, çağrı-merkezi]
---

Calltech Ar-Ge ekibi olarak, Türkçe sesli veriler üzerinde gerçekleştirdiğimiz konuşmadan metne çeviri (STT) model karşılaştırma çalışmamız **hakemli bir dergide yayınlandı**!

📄 **Makalenin tamamı burada okunabilir:**  
👉 <a href="https://dergipark.org.tr/tr/pub/tbbmd/issue/80549/1252487" target="_blank" rel="noopener noreferrer">Makaleyi Oku</a>


### 🧪 Araştırmanın Amacı

Çalışmamızda, çok dilli ön eğitimli iki STT modeli olan **Whisper-Small** ve **Wav2Vec2-XLS-R-300M**’i Türkçe ses kayıtları üzerinde ince ayar yaparak karşılaştırdık. Eğitim için Mozilla Common Voice veri seti kullanıldı, değerlendirme ise daha önce eğitimde yer almayan **çağrı merkezi kayıtlarıyla** yapıldı.

| Model               | WER (Test) | CER | Notlar |
|--------------------|------------|-----|--------|
| Whisper-Small      | **0.16**   | 0.04| Daha kısa sürede eğitiliyor, noktalama desteği var |
| Wav2Vec2-XLS-R-300M| 0.28       | 0.06| Daha esnek ama eğitim süresi uzun |

### 🤖 Calltech’e Etkisi

Bu çalışma, **Calltech.app** platformumuzun altyapısındaki konuşmadan metne bileşenini iyileştirmemize yardımcı oldu. Günlük binlerce çağrı kaydını işlerken; duygu analizi ve çalışan performans takibi gibi çıktılarda bu modellerin doğruluğu çok kritik.

Araştırma ile ürün geliştirme arasında köprü kurarak, Türkiye’deki firmalara özel **yapay zeka destekli ses teknolojileri** geliştirmeye devam ediyoruz.

---
🔬 *Bu çalışma, TÜBİTAK TEYDEB 1501 desteğiyle (Proje No: 3210713) gerçekleştirilmiştir.*
