# Food Ordering & Restaurant Management System (C)
# Restoran Sipariş ve Yönetim Sistemi (C)

This is a console-based restaurant management system written in C. It simulates customer orders, kitchen operations, and restaurant administration.
Bu proje, C programlama dili ile geliştirilmiş terminal tabanlı bir restoran yönetim sistemidir. Müşteri siparişleri, mutfak işlemleri ve restoran yönetimi simüle edilmektedir.

---

## 🧭 Menu Structure
## 🧭 Menü Yapısı

### 🍽 Main Menu
- Customer Operations
- Restaurant Operations
- Kitchen Operations
- Exit

### 🍽 Ana Menü
- Müşteri İşlemleri
- Restoran İşlemleri
- Mutfak İşlemleri
- Çıkış

---

### 👤 Customer Operations
- Add a new order
- View current active order
- List all past orders

### 👤 Müşteri İşlemleri
- Yeni sipariş ekle
- Aktif siparişi görüntüle
- Önceki siparişleri listele

---

### 🏪 Restaurant Operations
- Manage food items (add, update, delete)
- Approve or reject customer orders
- View daily report
- View analytics
- Add kitchen staff

### 🏪 Restoran İşlemleri
- Yemekleri yönet (ekle, güncelle, sil)
- Siparişleri onayla veya reddet
- Günlük rapor görüntüle
- Analizleri görüntüle
- Aşçı ekle

---

### 📊 Restaurant Analytics
- Calculate daily and monthly income
- Earnings between specific dates
- Most frequent customer
- Most ordered dish

### 📊 Restoran Analizleri
- Günlük ve aylık gelir hesaplama
- Belirli tarih aralığında kazanç
- En çok sipariş veren müşteri
- En çok sipariş edilen yemek

---

### 👨‍🍳 Kitchen Operations
- View and process active orders

### 👨‍🍳 Mutfak İşlemleri
- Aktif siparişleri görüntüle ve işle

---

## 🛠 Technologies Used
## 🛠 Kullanılan Teknolojiler

- Language: C  
- Interface: Terminal (CLI)  
- Structure: Modular (header files such as `musteri.h`, `restoran.h`, `mutfak.h`)

- Programlama Dili: C  
- Arayüz: Terminal (Komut Satırı)  
- Yapı: Modüler (başlık dosyaları: `musteri.h`, `restoran.h`, `mutfak.h`)

---

## 🚀 How to Compile and Run
## 🚀 Derleme ve Çalıştırma

```bash
gcc main.c -o restaurant_app
./restaurant_app
