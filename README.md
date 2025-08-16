# Groq API - Free AI Tool Tutorial

This repository contains a detailed guide and examples on how to use the **Groq API**,  
a free and fast AI tool for developers, researchers, and AI enthusiasts.

---

##  What is Groq API?
Groq API is an AI inference service that provides ultra-fast response times and is completely free for certain usage tiers.  
It supports LLM (Large Language Models) like LLaMA, Gemma, and Mixtral.

Official website: [https://groq.com](https://groq.com)

---

##  Features
- **Free access** for developers
- **Ultra-low latency** AI responses
- Supports multiple open-source models
- Easy integration with Python, JavaScript, and other languages

---

##  How to Use
1. Sign up at [https://console.groq.com](https://console.groq.com)
2. Generate your **API Key**
3. Install the required library (Python example):
```bash
pip install groq


---

from groq import Groq

client = Groq(api_key="YOUR_API_KEY")

chat_completion = client.chat.completions.create(
    model="llama3-8b-8192",
    messages=[
        {"role": "system", "content": "You are a helpful assistant."},
        {"role": "user", "content": "Hello Groq!"}
    ]
)

print(chat_completion.choices[0].message)


---



---

# Groq API - Ücretsiz Yapay Zeka Aracı Rehberi

Bu depo, geliştiriciler, araştırmacılar ve yapay zeka meraklıları için **Groq API**’nin  
nasıl kullanılacağına dair detaylı bir rehber ve örnekler içerir.

---

##  Groq API Nedir?
Groq API, ultra hızlı yanıt süreleri sunan ve belirli kullanım kotalarında tamamen ücretsiz olan bir yapay zeka servisidir.  
LLaMA, Gemma ve Mixtral gibi büyük dil modellerini (LLM) destekler.

Resmi site: [https://groq.com](https://groq.com)

---

##  Özellikler
- **Geliştiriciler için ücretsiz erişim**
- **Ultra düşük gecikmeli** yapay zeka yanıtları
- Birden fazla açık kaynak modeli destekleme
- Python, JavaScript ve diğer dillerle kolay entegrasyon

---

##  Nasıl Kullanılır?
1. [https://console.groq.com](https://console.groq.com) adresine kayıt ol
2. **API Anahtarını** oluştur
3. Gerekli kütüphaneyi yükle (Python örneği):
```bash
pip install groq


from groq import Groq

client = Groq(api_key="API_ANAHTARINIZ")

chat_completion = client.chat.completions.create(
    model="llama3-8b-8192",
    messages=[
        {"role": "system", "content": "Yardımcı bir asistansın."},
        {"role": "user", "content": "Merhaba Groq!"}
    ]
)

print(chat_completion.choices[0].message)


