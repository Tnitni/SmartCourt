# XnovaV2 FrontEnd

This is the frontend project for XnovaV2 a smart web platform for sports court booking and management. It features role-based access control (Admin, Owner, User), schedule management, and secure online payments.

## Features
- Modern React (JSX, hooks, context)
- Vite for fast development and build
- Modular component structure
- API proxying via Vite
- Environment variable support

## Getting Started

### Prerequisites
- Node.js (v16+ recommended)
- npm or yarn

### Installation
```bash
npm install
# hoặc
yarn install
```

### Development
```bash
npm run dev
# hoặc
yarn dev
```

### Build
```bash
npm run build
# hoặc
yarn build
```

### Environment Variables
Tạo file `.env` ở thư mục gốc và thêm biến sau:
```
VITE_API_URL=https://your-api-url.com
```

## Thư mục chính
- `src/` - Source code chính
- `src/app/components/` - Các component giao diện
- `src/pages/` - Các trang chính
- `src/services/` - Gọi API và các service
- `src/utils/` - Tiện ích chung

## License
MIT
