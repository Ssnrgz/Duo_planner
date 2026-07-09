 # DuoPlanner - Ortak Ajanda ve Dijital Hafıza Merkezi 🚀

*(English documentation is available below 👇)*

DuoPlanner, iki kişinin (proje ortakları, ev arkadaşları veya çiftler) ortak izlenecek filmleri, gidilecek şehirleri ve geçmiş anıları tek bir şifreli dijital hafızada tutabilmesi için geliştirilmiş **sunucusuz (serverless)** bir web uygulamasıdır.

🔗 **Canlı Demo Sürümü:** [Uygulamayı Test Edin](https://ssnrgz.github.io/Duo_planner/)  
🔑 **Demo Giriş Şifresi:** `demo`

## 🛠️ Teknolojiler ve Mimari
Bu projede herhangi bir ağır JavaScript framework'ü kullanılmadan, olabildiğince hafif ve hızlı çalışan bir mimari hedeflenmiştir:
* **Frontend:** HTML5, Vanilla JavaScript, Tailwind CSS (CDN)
* **Backend & Veritabanı:** Firebase Realtime Database
* **Veri İletişimi:** Firebase REST API ile istemci (client) üzerinden doğrudan JSON formatında asenkron (Fetch API) CRUD operasyonları.
* **Deployment:** GitHub Pages

## ✨ Öne Çıkan Özellikler
* **Gerçek Zamanlı Senkronizasyon:** Farklı cihazlardan eklenen veriler ortak havuza anında düşer.
* **İstemci Taraflı Algoritmalar:** Kategorilere göre dinamik filtreleme ve tarihe/isme göre çok yönlü sıralama (A-Z, Z-A, Yeniden Eskiye).
* **Responsive UI/UX:** Tailwind CSS ile tamamen mobilden kullanıma uygun, göz yormayan modern arayüz tasarımı.
* **Güvenlik Katmanı:** Arayüz tabanlı erişim şifresi duvarı.
* **Ortam İzolasyonu:** Canlı sürüm ve açık kaynaklı demo ortamı, veri güvenliğini sağlamak için tamamen farklı veritabanı yollarında (nodes) çalışır.
* **Gelişmiş Veritabanı Güvenliği:** Ana dizin erişimi kapatılarak (.read: false), okuma/yazma işlemleri sadece gizlenmiş özel uç noktalar (endpoints) üzerinden yapılır.

## 💻 Kendi Kopyanızı Nasıl Kurarsınız?
Proje tamamen açık kaynak ve bağımsız çalışacak şekilde kurgulanmıştır. Kendi özel ortak ajandanızı oluşturmak için:

1. Bu projeyi bilgisayarınıza indirin (`git clone`).
2. Google Firebase üzerinden ücretsiz bir **Realtime Database** oluşturun.
3. `index.html` içindeki `FIREBASE_BASE_URL` değişkenini kendi Firebase linkinizle güncelleyin.
4. `OZEL_SIFRE` değişkenine kendi belirlediğiniz şifreyi yazın.
5. GitHub Pages, Vercel veya Firebase Hosting ile saniyeler içinde ücretsiz yayınlayın!

---

# DuoPlanner - Shared Agenda and Digital Memory Hub 🚀

DuoPlanner is a **serverless** web application developed for two people (project partners, roommates, or couples) to keep their shared movies to watch, cities to visit, and past memories in a single, encrypted digital memory space.

🔗 **Live Demo:** [Try the App](https://ssnrgz.github.io/Duo_planner/)  
🔑 **Demo Password:** `demo`

## 🛠️ Technologies & Architecture
This project aims for a lightweight and fast-running architecture without using any heavy JavaScript frameworks:
* **Frontend:** HTML5, Vanilla JavaScript, Tailwind CSS (CDN)
* **Backend & Database:** Firebase Realtime Database
* **Data Communication:** Asynchronous CRUD operations via Firebase REST API in JSON format directly from the client (Fetch API).
* **Deployment:** GitHub Pages

## ✨ Key Features
* **Real-time Synchronization:** Data added from different devices instantly appears in the shared pool.
* **Client-Side Algorithms:** Dynamic filtering by category and multi-directional sorting by date/name (A-Z, Z-A, Newest to Oldest).
* **Responsive UI/UX:** A modern, mobile-friendly interface built with Tailwind CSS.
* **Security Layer:** Interface-based password protection wall.
* **Environment Isolation:** Production and demo versions operate on completely separate database nodes to ensure absolute data security.

Advanced Database Security: Root access is restricted (.read: false), securing all CRUD operations through hidden, client-specific endpoints.

## 💻 How to Deploy Your Own Copy
The project is open-source and designed to work independently. To create your own private shared agenda:

1. Clone this repository to your local machine (`git clone`).
2. Create a free **Realtime Database** on Google Firebase.
3. Update the `FIREBASE_BASE_URL` variable in `index.html` with your Firebase link.
4. Set your custom password in the `OZEL_SIFRE` variable.
5. Deploy for free in seconds using GitHub Pages, Vercel, or Firebase Hosting!

---
*Bu proje, günlük bir problemi hafif ve sunucusuz bir mimari ile çözmek amacıyla geliştirilmiş bir mühendislik pratiğidir. 
This project is an engineering practice developed to solve a daily problem using a lightweight and serverless architecture.*

<img width="482" height="843" alt="Screenshot from 2026-07-10 02-15-42" src="https://github.com/user-attachments/assets/888b4988-facb-4626-924e-98c4edbf5661" />
<img width="482" height="843" alt="Screenshot from 2026-07-10 02-15-55" src="https://github.com/user-attachments/assets/16579efe-4f6f-4445-8b9f-a367a832f3f3" />


