<h1 align="center">🛒 Nền tảng thương mại điện tử tích hợp AI Chatbot 🤖</h1>

<p align="center">
  <img src="https://img.shields.io/badge/Framework-React-blue?style=flat-square" />
  <img src="https://img.shields.io/badge/Backend-Node.js-green?style=flat-square" />
  <img src="https://img.shields.io/badge/Database-MongoDB-brightgreen?style=flat-square" />
  <img src="https://img.shields.io/badge/AI-Gemini%202.5%20Flash-orange?style=flat-square" />
</p>

<p align="center">
  Dự án thương mại điện tử với chatbot AI giúp người dùng tìm kiếm sản phẩm nhanh chóng, thông minh và tiện lợi.  
  Sức mạnh đến từ mô hình <b>Gemini 2.5 Flash</b> và nền tảng hiện đại <b>React + Node.js + MongoDB</b>.
</p>

---

## 🎬 Demo

https://github.com/user-attachments/assets/138aa1ea-cb0e-49f4-ad37-77276269aed8

---

## 🚀 Tính năng nổi bật

- 🤖 **AI Chatbot tích hợp** – Tư vấn sản phẩm, hỗ trợ người dùng thông minh theo ngữ cảnh.  
- 🧠 **Sử dụng mô hình Gemini 2.5 Flash** – Nhanh, nhẹ và tối ưu cho hội thoại thương mại.  
- 🛍️ **Giao diện hiện đại, thân thiện** – Thiết kế UI trực quan, dễ thao tác.  
- 💾 **Cơ sở dữ liệu MongoDB Atlas** – Lưu trữ an toàn và mở rộng linh hoạt.  
- 🔐 **Xác thực người dùng bằng Clerk** – Đăng nhập/đăng ký bảo mật và tiện lợi.  

---

## ⚙️ Cài đặt & Chạy dự án

### 1️⃣ Clone repository
```bash
git clone https://github.com/tribeti/aichat-web.git
````

### 2️⃣ Cấu hình file môi trường `.env`

Liên hệ mình để nhận file `.env`
*(Hoặc xem mục [FAQ](#faq) để tự tạo các key cần thiết)*

### 3️⃣ Cài đặt và khởi động server

```bash
cd server
npm install
npm run dev
```

### 4️⃣ Cài đặt và khởi động client

```bash
cd client
npm install
npm start
```

### 5️⃣ Mở ứng dụng

Truy cập **[http://localhost:5173](http://localhost:5173)** để bắt đầu trải nghiệm 🚀

---

## 💬 Sử dụng Chatbot

1. Mở giao diện web
2. Click vào **hộp thoại chat** ở góc phải dưới màn hình
3. Nhập tin nhắn và trò chuyện với AI
4. Nếu chatbot không phản hồi:

   * Nhấn `F12` → tab **Console**
   * Xem lỗi `{...}` → click mũi tên để mở rộng
   * Gửi lỗi đó lên Google hoặc ChatGPT để xử lý 🧑‍💻

---

## FAQ

### ❓ Làm sao để tự tạo `.env`?

#### Bước 1: MongoDB

* Truy cập [MongoDB Atlas](https://account.mongodb.com/account/login)
* Tạo cluster → chọn **Driver: Node.js**
* Lấy link `MONGODB_ATLAS_URI`
  (nhớ thay `<db_pass>` bằng mật khẩu thật)

#### Bước 2: Google Gemini API

* Truy cập [Google Cloud Console](https://console.cloud.google.com/)
* Tạo **Project** → vào **APIs & Services → Credentials**
* Chọn **Create credentials → API Key**
* Lấy `GOOGLE_API_KEY`
* Bật API tại đây: [Generative Language API](https://console.cloud.google.com/apis/library/generativelanguage.googleapis.com)

#### Bước 3: Clerk Authentication

* Đăng ký tại [clerk.com](https://clerk.com/)
* Tạo ứng dụng và copy các key

  * `VITE_CLERK_PUBLISHABLE_KEY`
  * `CLERK_SECRET_KEY`

---

## 🧠 Công nghệ sử dụng

| Thành phần               | Mô tả                        |
| ------------------------ | ---------------------------- |
| **React + Vite**         | Front-end nhanh và tối ưu    |
| **Node.js + Express**    | Backend REST API             |
| **MongoDB Atlas**        | Cơ sở dữ liệu đám mây        |
| **Clerk**                | Hệ thống xác thực người dùng |
| **Gemini 2.5 Flash API** | AI Chatbot thông minh        |

---

## 🏗️ Nguồn tham khảo & Credits

* 🎥 **Hướng dẫn gốc**: [Building an AI-Powered E-commerce Chat Assistant with MongoDB – Tutorial](https://www.youtube.com/watch?v=9tANiA0LKn4)
* 💡 **Repo gốc**: [kubowania/ecommerce-chat-helper](https://github.com/kubowania/ecommerce-chat-helper)

---

## 🌟 Giúp dự án phát triển

Nếu bạn thấy dự án hữu ích, hãy **⭐ Star** repo này để ủng hộ nhé!
Mọi ý tưởng hoặc đóng góp đều được chào đón ❤️

---

<p align="center">
  <b>Made with ❤️ by <a href="https://github.com/Hbest1804">Tu tien team</a></b>
</p>
