# 🛒 Grocery Management System

<div align="center">

![React](https://img.shields.io/badge/React-19.0-blue?logo=react&logoColor=white)
![TypeScript](https://img.shields.io/badge/TypeScript-5.8-blue?logo=typescript&logoColor=white)
![Vite](https://img.shields.io/badge/Vite-6.2-purple?logo=vite&logoColor=white)
![TailwindCSS](https://img.shields.io/badge/TailwindCSS-4.1-38B2AC?logo=tailwindcss&logoColor=white)
![Express](https://img.shields.io/badge/Express-4.21-90c53f?logo=express&logoColor=white)
![License](https://img.shields.io/badge/License-MIT-green)

An intelligent grocery management application powered by **Google Gemini AI** for smart inventory management and recommendations.

</div>

---

## ✨ Features

- 🤖 **AI-Powered Recommendations** - Get smart suggestions using Google Gemini AI
- 📊 **Inventory Management** - Track and manage grocery items efficiently
- 🎨 **Modern UI** - Beautiful, responsive design with TailwindCSS
- ⚡ **Fast Performance** - Built with Vite for lightning-fast development and production builds
- 🔐 **Secure Configuration** - Environment-based configuration for API keys
- 🎬 **Smooth Animations** - Enhanced user experience with Motion animations

---

## 🛠️ Tech Stack

### Frontend
- **React 19** - Modern UI library
- **TypeScript** - Type-safe development
- **Vite 6** - Next-generation build tool
- **TailwindCSS 4** - Utility-first CSS framework
- **Lucide React** - Beautiful icon library
- **Motion** - Smooth animations

### Backend
- **Express.js** - Web server framework
- **Node.js** - Runtime environment
- **Google GenAI API** - AI capabilities

---

## 📋 Prerequisites

Before you begin, ensure you have the following installed:
- **Node.js** (v16 or higher)
- **npm** or **yarn**
- A **Google Gemini API Key** ([Get one here](https://ai.google.dev/))

---

## 🚀 Quick Start

### 1. Clone the Repository
```bash
git clone https://github.com/Manukumarrr/Grocery-Management.git
cd Grocery-Management
```

### 2. Install Dependencies
```bash
npm install
```

### 3. Configure Environment Variables
Create or update the `.env.local` file in the root directory:
```env
GEMINI_API_KEY=your_gemini_api_key_here
APP_URL=http://localhost:3000
```

> 📝 **Note:** Copy `.env.example` and rename to `.env.local` if needed

### 4. Start Development Server
```bash
npm run dev
```

The application will be available at `http://localhost:3000`

---

## 📦 Available Scripts

| Command | Description |
|---------|-------------|
| `npm run dev` | Start development server with hot module reloading |
| `npm run build` | Build for production with optimized output |
| `npm start` | Run the production build |
| `npm run clean` | Clean build artifacts and generated files |
| `npm run lint` | Run TypeScript type checking |

---

## 📁 Project Structure

```
Grocery-Management/
├── src/                    # Source files (React components)
├── server.ts              # Express server configuration
├── vite.config.ts         # Vite configuration
├── tsconfig.json          # TypeScript configuration
├── package.json           # Project dependencies
├── index.html             # Entry HTML file
├── db.json               # Sample database file
├── metadata.json         # Metadata configuration
├── .env.example          # Environment variables template
└── README.md             # This file
```

---

## 🌐 Environment Variables

The application requires the following environment variables:

| Variable | Description | Required |
|----------|-------------|----------|
| `GEMINI_API_KEY` | Google Gemini API key for AI features | ✅ Yes |
| `APP_URL` | Base URL of the application | ✅ Yes |

---

## 💻 Development

### Type Checking
Ensure your code passes TypeScript checks:
```bash
npm run lint
```

### Building for Production
```bash
npm run build
npm start
```

This creates optimized bundles in the `dist/` directory.

---

## 📚 API Configuration

The application uses the **Google Gemini API** for intelligent recommendations and grocery management suggestions. Make sure your API key has access to:
- Generative models
- Text generation capabilities

---

## 🤝 Contributing

Contributions are welcome! Here's how to contribute:

1. Fork the repository
2. Create a feature branch (`git checkout -b feature/amazing-feature`)
3. Commit your changes (`git commit -m 'Add amazing feature'`)
4. Push to the branch (`git push origin feature/amazing-feature`)
5. Open a Pull Request

---

## 📄 License

This project is licensed under the **MIT License** - see the LICENSE file for details.

---

## 🎯 Roadmap

- [ ] Mobile app support
- [ ] User authentication
- [ ] Shopping list sharing
- [ ] Price comparison features
- [ ] Barcode scanning
- [ ] Offline mode

---

## 📧 Support

For support, questions, or feedback, please:
- Open an [issue](https://github.com/Manukumarrr/Grocery-Management/issues)
- Contact me on GitHub [@Manukumarrr](https://github.com/Manukumarrr)

---

## 🙌 Acknowledgments

- [Google Gemini API](https://ai.google.dev/) for AI capabilities
- [Vite](https://vitejs.dev/) for the amazing build tool
- [React](https://react.dev/) for the UI framework
- [TailwindCSS](https://tailwindcss.com/) for styling

---

<div align="center">

**Made with ❤️ by [Manukumarrr](https://github.com/Manukumarrr)**

⭐ If you find this project helpful, please consider giving it a star!

</div>
