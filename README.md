# 💼 JobBridge – Job Board

JobBridge is a job board platform developed as a **university group assignment project**. This project was created as part of our academic coursework, providing an opportunity to collaborate and apply our web development skills in building a job platform.

## 👥 Contributors

- Huang Wan Jun
- Lee Mun Onn
- Shia Kah Yee
- Yu Xiao Shi

---

## ⚙️ Project Setup Guide

Follow the steps below to set up and run the project locally.

### 1. Install Dependencies

Install the required backend and frontend dependencies:

```bash
npm install
composer install
```

### 2. Environment Configuration

Create your environment file:

```bash
cp .env.example .env
```

Update the `.env` file with the appropriate configuration for your local environment.

### 3. Broadcast Configuration

Add the following configuration to your `.env` file to enable broadcasting:

```env
BROADCAST_DRIVER=pusher
PUSHER_APP_ID="2130607"
PUSHER_APP_KEY="YOUR_PUSHER_APP_KEY"
PUSHER_APP_SECRET="YOUR_PUSHER_APP_SECRET"
PUSHER_APP_CLUSTER="ap1"
```

### 4. Generate Application Key

```bash
php artisan key:generate
```

### 5. Run the Project

Start the frontend development server:

```bash
npm run dev
```

In another terminal, start the Laravel development server:

```bash
php artisan serve
```

The application will be available at:

```text
http://127.0.0.1:8000
```

---

<p align="center">
  Developed as a university group assignment. 💻
</p>
