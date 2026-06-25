cd ~/Desktop/app/integration/TradeXpress_FullStack
cat > README.md << 'EOF'
# 🚀 TradeXpress IMPACT

**Full-Stack Trading Platform with 6 Core Modules**

[![Node.js](https://img.shields.io/badge/Node.js-18+-green)](https://nodejs.org)
[![React](https://img.shields.io/badge/React-18-blue)](https://react.dev)
[![License](https://img.shields.io/badge/License-MIT-yellow)](LICENSE)

## ✨ Features

### 6 Core Modules
1. **Dashboard** - Real-time analytics
2. **Trading** - Buy/Sell interface
3. **Portfolio** - Asset management
4. **Analytics** - Charts & insights
5. **Wallet** - Deposits & withdrawals
6. **Settings** - Profile & security

### Authentication
- ✅ Email/Password
- ✅ Google OAuth
- ✅ GitHub OAuth

## 🛠️ Tech Stack

**Frontend:** React 18, Vite, Tailwind CSS
**Backend:** Node.js, Express, MongoDB
**DevOps:** Docker, Ubuntu

## 🚀 Quick Start (Ubuntu)

```bash
# 1. Clone
git clone git@github.com:sendtokenwellenterprise-lgtm/tradexpress-impact.git
cd tradexpress-impact

# 2. Setup
chmod +x setup-ubuntu.sh
./setup-ubuntu.sh

# 3. Install
cd backend && npm install
cd ../frontend && npm install

# 4. Run
# Terminal 1
cd backend && npm run dev

# Terminal 2
cd frontend && npm run dev
