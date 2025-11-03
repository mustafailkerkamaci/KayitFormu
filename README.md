# Kayıt Formu

Frontend Bootcamp projesi kapsamında hazırlanmış, HTML ve CSS kullanılarak oluşturulmuş bir **kayıt formu (survey form)** projesidir.

## 🎯 Amaç
HTML form elemanlarını semantik ve doğru şekilde kullanmak, CSS ile modern ve sade bir kullanıcı arayüzü tasarlamak.

## 🧩 Kullanılan Teknolojiler
- **HTML5:**  
  - `<form>`, `<input>`, `<select>`, `<textarea>`, `<fieldset>`, `<legend>` gibi form elemanları  
  - HTML5 doğrulama özellikleri (`required`, `type="email"`, `min`, `max`)  
  - Erişilebilirlik için `label for`, `id` ve `aria` ilişkileri  
- **CSS3:**  
  - Değişkenler (custom properties)  
  - Responsive yapı  
  - Renk geçişleri (gradient background)  
  - Gölge (box-shadow) ve yuvarlatılmış köşeler (border-radius)  
  - Odak (focus) ve doğrulama (valid/invalid) durum stilleri  


## 🖥️ Sayfa Özellikleri
- Başlık ve açıklama (`<h1 id="title">`, `<p id="description">`)  
- Form (`<form id="survey-form">`)  
- Alanlar:
  - Ad Soyad (`<input type="text">`)
  - E-posta (`<input type="email">`)
  - Yaş (`<input type="number" min="10" max="120">`)
  - Cinsiyet (`<select>`)
  - Üyelik tipi (radyo düğmeleri)
  - Tercihler (onay kutuları)
  - Yorum alanı (`<textarea>`)
  - Gönder butonu (`<input type="submit">`)
- Form gönderildikten sonra **`thanks.html`** yeni sekmede açılır ve “Kayıt Olduğunuz İçin Teşekkürler” mesajı gösterir.

## 🎨 Tema Özellikleri
- **Tema rengi:** Camgöbeği (`#06B6D4`)  
- **Zemin:** Degrade arka plan (radial + linear gradient)  
- **Form kartı:** Koyu mavi zemin, açık metin rengi, sade odak efektleri  
- **Tipografi:** Sistem yazı tipi ailesi (`system-ui, Segoe UI, Roboto, Arial, sans-serif`)  

## ⚙️ Özellik Özeti
- Responsive (mobil uyumlu) yapı  
- Modern odak efektleri (`box-shadow`)  
- HTML5 doğrulama destekli alanlar  
- Erişilebilirlik kurallarına uygun etiketleme  
- Yeni sekmede açılan teşekkür sayfası  

## 🚀 Nasıl Çalıştırılır
1. Tüm dosyaları aynı klasöre koy.  
2. `index.html` dosyasını tarayıcıda aç.  
3. Formu doldur ve “Gönder” butonuna tıkla.  
4. Yeni sekmede `thanks.html` açılarak “Kayıt Olduğunuz İçin Teşekkürler!” mesajı görüntülenir.

##Resimler
#<img width="1268" height="1320" alt="image" src="https://github.com/user-attachments/assets/a1645828-6197-4b87-94eb-12b4a6896459" />
#<img width="1268" height="1320" alt="image" src="https://github.com/user-attachments/assets/102a265d-29e2-43eb-82bc-5d9be74a17f4" />


