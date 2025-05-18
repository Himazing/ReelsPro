# 🎥 ReelsPro
Reels Pro is a Next.js-based social media application where users can upload and share short videos (reels). It uses NextAuth for authentication, ImageKit for media storage, and TypeScript for type safety. A modern Next.js application for managing and selling video content using ImageKit integration. This project provides a full-featured platform with user authentication, video upload capabilities.

## <a name="live-demo"> 🚀 Live Demo [Live Website Link](https://reelspro-sand.vercel.app/)
Try the live app now and experience the power of ReelsPro in action!

## Features

- 🔐 User Authentication (NextAuth.js)
- 📹 Video Upload and Management (ImageKit)
- 💳 Payment Processing (Razorpay)
- 🎨 Modern UI with Tailwind CSS and DaisyUI
- 📱 Fully Responsive Design
- 🔒 Secure API Routes
- 📧 Email Notifications (Nodemailer)
- 🗄️ MongoDB Database Integration

## 🛠 Tech Stack

| Tech                  | Description                      |
| --------------------- | -------------------------------- |
| ⚛️ **Frontend**       | Next.js 15, React 19, TypeScript |
| 🎨 **Styling**        | Tailwind CSS, DaisyUI            |
| 🔐 **Auth**           | NextAuth.js, JWT                 |
| 🧮 **Database**       | MongoDB + Mongoose               |
| 🖼️ **Media Storage**  | ImageKit                         |
| 💰 **Payments**       | Razorpay                         |
| 📬 **Emails**         | Nodemailer                       |
| 📋 **Forms**          | React Hook Form                  |

## Prerequisites

- Node.js (Latest LTS version)
- MongoDB Database
- ImageKit Account
- Razorpay Account
- SMTP Server (for email notifications)

## Getting Started

1. Clone the repository:
```bash
git clone https://github.com/Himazing/ReelsPro.git
cd imagekit-video-main
```

2. Install dependencies:
```bash
npm install
```

3. Configure environment variables:
   - Copy `.env.example` to `.env`
   - Fill in the required environment variables

4. Run the development server:
```bash
npm run dev
```

5. Open [http://localhost:3000](http://localhost:3000) in your browser

## Environment Variables

Create a `.env` file with the following variables:

```env
# Database
MONGODB_URI=

# Authentication
NEXTAUTH_SECRET=
NEXTAUTH_URL=

# ImageKit
IMAGEKIT_PUBLIC_KEY=
IMAGEKIT_PRIVATE_KEY=
IMAGEKIT_URL_ENDPOINT=
```

## Project Structure

```
├── app/                  # Next.js app directory
│   ├── api/             # API routes
│   ├── components/      # Reusable components
│   ├── login/          # Login page
│   ├── register/       # Registration page
│   └── upload/         # Video upload page
├── lib/                # Utility functions
├── models/             # MongoDB models
├── public/            # Static assets
└── types.d.ts         # TypeScript declarations
```


## 📬 Contact

Feel free to reach out to me through any of the following channels:

- **Email**: [jhahim11@gmail.com](mailto:jhahim11@gmail.com)
- **LinkedIn**: [linkedin.com/in/himazing](https://www.linkedin.com/in/himazing/)

### 🔥 Made with ❤️ by **Himanshu Kumar**

## 🌟 Support & Contribution

If you find this project helpful, consider giving it a ⭐️!
Feel free to fork, raise issues, or contribute with PRs — contributions are welcome! 🤝
