# Samsung Innovation Campus — Generative AI Lab Assignments

This repository contains my lab assignments for **Chapters 1, 2, and 3** of the Samsung Generative AI course. Each chapter explores a foundational area of modern AI: experiencing generative models, mastering prompt engineering, and understanding foundation models in real-world applications.

## Author

**Berat Erol Çelik** — 22-year-old 4th-year Software Engineering student at Istanbul Aydın University and founder of the AI startup **Coddiom**. Passionate about LLMs, AI agents, automation, and building intelligent systems that bridge research and production.

---

## Kullanılan Teknolojiler

| Araç | Kullanım Amacı |
|------|---------------|
| **OpenCode** | AI-asistan ile proje iskeleti oluşturma, dosya yönetimi ve Git işlemleri |
| **Gemini** | Lab senaryolarındaki text generation ve prompt comparison çıktılarını üretme |
| **VS Code** | Yerel geliştirme ortamı ve dosya düzenleme |
| **Git & GitHub** | Versiyon kontrolü ve uzak depo yönetimi |

---

## Tamamlama Durumu

### 1. `Chapter_1_Introduction_to_GenAI/Lab_1_Experiencing_GenAI.md`
- **Yapılanlar:** Lab 1 için text generation ve image generation bölümleri oluşturuldu. Her bölümde bir prompt tanımlandı ve çıktı için placeholder eklendi.
- **Tamamlamam gereken kısımlar:**
  - **Text Generation (LLM Architecture):** Gemini'ye LLM mimarisini açıklayan promptu (`Explain the architecture of a modern LLM...`) gönder. Gelen cevabı `> **Result:**` satırının altına yapıştır.
  - **Image Generation (Cyberpunk AI Agent):** Gemini veya bir görsel üretme aracına (Imagen vs.) cyberpunk temalı promptu gir. Çıkan görseli proje klasörüne (örn. `Chapter_1_Introduction_to_GenAI/assets/`) kaydet. Markdown'daki placeholder'ı `![Açıklama](assets/gorsel-adi.png)` ile güncelle.
- **Görsel Gereksinimi:** Mevcut. Prompt: *"A futuristic AI agent orchestrating data flows in a terminal interface, cyberpunk style — neon hues, holographic data streams, glowing fiber optics, and cascading code rain reflecting off a dark visor."* Görseli `Chapter_1_Introduction_to_GenAI/` altına kaydedip yolu güncelle.

### 2. `Chapter_1_Introduction_to_GenAI/Lab_2_Personal_Branding.html`
- **Yapılanlar:** Modern, responsive, koyu temalı bir HTML5/CSS3 kişisel sayfa oluşturuldu. "Who I Am", "My Skills" (6 skill tag'i) ve "My Future Goals" (4 madde) bölümleri tam. Canlı olarak tarayıcıda açılıp görüntülenebilir.
- **Tamamlamam gereken kısımlar:** HTML dosyası baştan sona dolu. Herhangi bir placeholder yok. İstersen kendi fotoğrafını eklemek için bir `<img>` etiketi ekleyebilirsin — bu opsiyonel.
- **Görsel Gereksinimi:** Yok.

### 3. `Chapter_2_Prompt_Engineering/Lab_1_Prompt_Comparison.md`
- **Yapılanlar:** A/B test raporu oluşturuldu. Kötü prompt (5 kelime), iyileştirilmiş prompt (6-elementli yapı: Role, Goal, Context, Constraints, Style, Output Format) ve karşılaştırma tablosu eklendi. Baykar stajına özel, hallucination riskini analiz eden bir bölüm var.
- **Tamamlamam gereken kısımlar:**
  - **Kötü Prompt Çıktısı:** Gemini'ye *"Write a motivation letter for a software engineering internship."* yaz. Gelen sonucu "Kötü Prompt Çıktısı" bölümüne yapıştır.
  - **İyileştirilmiş Prompt Çıktısı:** Gemini'ye dosyadaki 6-elementli yapılandırılmış promptu birebir gönder. Gelen motivasyon mektubunu "İyileştirilmiş Prompt Çıktısı" bölümüne yapıştır.
- **Görsel Gereksinimi:** Yok.

### 4. `Chapter_3_Foundation_Models/Lab_1_Industry_Specific_Models.md`
- **Yapılanlar:** 3 slaytlık sunum taslağı tam. Slide 1: Su krizi problemi, Slide 2: Aqua-Adapt dijital ikiz çözümü, Slide 3: Genel amaçlı LLM'ler vs. endüstriye özel modeller karşılaştırması. Tablo ve kapanış cümlesi mevcut.
- **Tamamlamam gereken kısımlar:** Bu dosyada doldurulmamış yer yok. Slayt taslağı olduğu için sunum hazırlığında direkt kullanılabilir.
- **Görsel Gereksinimi:** Yok (isteğe bağlı olarak her slayda bir görsel eklenebilir).

---

## Manuel Düzenleme Yapılması Gereken Dosyalar

| # | Dosya | Ne Yapılacak? |
|---|-------|---------------|
| 1 | `Chapter_1_Introduction_to_GenAI/Lab_1_Experiencing_GenAI.md` | Gemini text çıktısını yapıştır + görsel oluşturup yolu güncelle |
| 2 | `Chapter_2_Prompt_Engineering/Lab_1_Prompt_Comparison.md` | Hem kötü hem iyileştirilmiş promptun Gemini çıktılarını yapıştır |
| 3 | - | - |

## Kullanılacak Gemini Promptları (Lab Senaryolarına Göre)

| Lab | Prompt |
|-----|--------|
| **Lab 1.1 — Text** | *"Explain the architecture of a modern Large Language Model (LLM) — including tokenization, transformer blocks, attention mechanisms, and how autoregressive decoding produces coherent text. Compare decoder-only (GPT) vs. encoder-decoder (T5) architectures."* |
| **Lab 1.1 — Görsel** | *"A futuristic AI agent orchestrating data flows in a terminal interface, cyberpunk style — neon hues, holographic data streams, glowing fiber optics, and cascading code rain reflecting off a dark visor."* |
| **Lab 2.1 — Kötü Prompt** | *"Write a motivation letter for a software engineering internship."* |
| **Lab 2.1 — İyi Prompt** | Dosyadaki 6-elementli yapılandırılmış promptu birebir kullan. |
| **Lab 3.1** | Dosya zaten dolu — sunum için ek içerik gerekmiyor. |
