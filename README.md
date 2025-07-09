# TradeNest - AI-Powered Global Trade Platform

A comprehensive supply chain and trade management platform powered by Claude AI and Hugging Face, built with Next.js and deployed on Vercel.

## 🚀 Features

- **AI-Powered Classification**: Intelligent product classification with Claude AI
- **Smart Inventory Management**: Real-time inventory tracking with automated AI analysis
- **Automated Compliance**: Generate trade documents and ensure regulatory compliance
- **Intelligent Billing**: Real-time tax calculations and duty assessments
- **Advanced Logistics**: Global shipment tracking with route optimization
- **Enterprise Security**: Bank-grade security with encrypted data transmission

## 🛠️ Tech Stack

- **Frontend**: Next.js 13, React 18, TypeScript
- **Styling**: Tailwind CSS, shadcn/ui components
- **AI Integration**: Claude AI (Anthropic)
- **Deployment**: Vercel
- **Icons**: Lucide React
- **Animations**: Framer Motion

## 🚀 Quick Start

### Prerequisites

- Node.js 18+ 
- npm or yarn
- Claude AI API key (from Anthropic Console)

### Local Development

1. **Clone the repository**
   ```bash
   git clone <your-repo-url>
   cd tradenest
   ```

2. **Install dependencies**
   ```bash
   npm install
   ```

3. **Set up environment variables**
   ```bash
   cp .env.example .env.local
   ```
   
   Edit `.env.local` and add your API keys:
   ```env
   NEXT_PUBLIC_CLAUDE_API_KEY=your_claude_api_key_here
   NEXT_PUBLIC_API_BASE_URL=https://api.anthropic.com
   ```

4. **Run the development server**
   ```bash
   npm run dev
   ```

5. **Open your browser**
   Navigate to [http://localhost:3000](http://localhost:3000)

## 🌐 Deployment on Vercel

### Method 1: Deploy from GitHub (Recommended)

1. **Push your code to GitHub**
   ```bash
   git add .
   git commit -m "Initial commit"
   git push origin main
   ```

2. **Connect to Vercel**
   - Go to [vercel.com](https://vercel.com)
   - Sign in with your GitHub account
   - Click "New Project"
   - Import your TradeNest repository

3. **Configure Environment Variables**
   In your Vercel project settings, add:
   ```
   NEXT_PUBLIC_CLAUDE_API_KEY=your_claude_api_key_here
   NEXT_PUBLIC_API_BASE_URL=https://api.anthropic.com
   ```

4. **Deploy**
   - Click "Deploy"
   - Vercel will automatically build and deploy your app
   - Your app will be live at `https://your-app-name.vercel.app`

### Method 2: Deploy with Vercel CLI

1. **Install Vercel CLI**
   ```bash
   npm i -g vercel
   ```

2. **Login to Vercel**
   ```bash
   vercel login
   ```

3. **Deploy**
   ```bash
   vercel
   ```

4. **Set Environment Variables**
   ```bash
   vercel env add NEXT_PUBLIC_CLAUDE_API_KEY
   vercel env add NEXT_PUBLIC_API_BASE_URL
   ```

5. **Redeploy with Environment Variables**
   ```bash
   vercel --prod
   ```

## 🔧 Configuration

### API Keys Setup

1. **Claude AI API Key**
   - Visit [Anthropic Console](https://console.anthropic.com)
   - Create an account or sign in
   - Generate a new API key
   - Add it to your environment variables

2. **Hugging Face API Key** (Optional)

### Application Settings

- Configure API keys in Settings → API Keys within the app
- Upload inventory CSV files for AI analysis
- Customize dashboard widgets and layouts
- Set up business information and preferences

## 📁 Project Structure

```
tradenest/
├── app/                    # Next.js 13 app directory
│   ├── (dashboard)/       # Dashboard routes
│   │   ├── dashboard/     # Main dashboard
│   │   ├── inventory/     # Inventory management
│   │   ├── compliance/    # Compliance & documents
│   │   ├── billing/       # Billing & taxes
│   │   ├── logistics/     # Logistics tracking
│   │   └── settings/      # Application settings
│   ├── globals.css        # Global styles
│   ├── layout.tsx         # Root layout
│   └── page.tsx          # Landing page
├── components/            # Reusable components
│   ├── ui/               # shadcn/ui components
│   ├── ai-assistant.tsx  # Claude AI chat interface
│   ├── csv-upload.tsx    # CSV upload component
│   └── ...
├── lib/                  # Utility libraries
│   ├── claude.ts         # Claude AI integration
│   ├── export-utils.ts   # Data export utilities
│   └── ...
└── public/               # Static assets
```

## 🎯 Key Features

### AI Assistant
- Powered by Claude AI for intelligent trade insights
- Real-time product classification and HS code generation
- Tax calculations and compliance guidance
- Market analysis and optimization recommendations

### Inventory Management
- CSV upload with Claude AI analysis
- Real-time synchronization across all components
- Smart categorization and stock management
- AI-powered market demand analysis

### Compliance & Documentation
- Automated trade document generation
- Regulatory compliance checking
- Country-specific requirements
- AI-powered risk assessment

### Billing & Taxes
- Real-time tax calculations with Claude AI
- Multi-country duty and VAT calculations
- Trade agreement optimization
- Comprehensive billing reports

### Logistics Tracking
- Global shipment tracking
- Warehouse management
- Route optimization
- Carrier performance analytics

## 🔒 Security

- API keys stored securely in environment variables
- Client-side encryption for sensitive data
- No server-side storage of API keys
- Secure communication with AI services

## 📊 Data Export

- CSV, Excel, and PDF export capabilities
- Comprehensive reporting across all modules
- Real-time data synchronization
- Professional document formatting

## 🤝 Contributing

1. Fork the repository
2. Create a feature branch (`git checkout -b feature/amazing-feature`)
3. Commit your changes (`git commit -m 'Add amazing feature'`)
4. Push to the branch (`git push origin feature/amazing-feature`)
5. Open a Pull Request

## 📝 License

This project is licensed under the MIT License - see the LICENSE file for details.

## 🆘 Support

- **Documentation**: Check this README and in-app help
- **Issues**: Create an issue on GitHub
- **API Keys**: Get Claude AI key from [Anthropic Console](https://console.anthropic.com)

## 🚀 Live Demo

Visit the live application: [https://your-app-name.vercel.app](https://your-app-name.vercel.app)

---

**Built with ❤️ by the TradeNest Team**

*Revolutionizing global trade with AI-powered automation and intelligence.*