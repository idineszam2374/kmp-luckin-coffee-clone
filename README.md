<div align="center">

# ☕ Luckin Coffee Clone

### Kotlin Multiplatform + Compose Multiplatform

**1 Codebase → 4 Platforms: Android • iOS • Web • Desktop**

[![Kotlin](https://img.shields.io/badge/Kotlin-2.1-7F52FF?logo=kotlin&logoColor=white)](https://kotlinlang.org)
[![Compose](https://img.shields.io/badge/Compose_Multiplatform-1.7.1-4285F4?logo=jetpackcompose&logoColor=white)](https://www.jetbrains.com/lp/compose-multiplatform/)
[![License](https://img.shields.io/badge/License-MIT-green.svg)](LICENSE)
[![Platform](https://img.shields.io/badge/Platform-Android%20|%20iOS%20|%20Web%20|%20Desktop-blue)]()

</div>

---

## 🎯 Giới thiệu

Đây là dự án **clone UI ứng dụng Luckin Coffee** được xây dựng hoàn toàn bằng **Kotlin Multiplatform (KMP)** và **Compose Multiplatform** - công nghệ cho phép viết 1 lần, chạy trên nhiều nền tảng.

> 💡 **Mục đích**: Học tập, nghiên cứu và chia sẻ kiến thức về cross-platform development với Kotlin.

---

## ✨ Tính năng nổi bật

| Feature | Mô tả |
|---------|-------|
| 🎨 **Premium UI** | Giao diện cao cấp với animations mượt mà |
| 🎠 **Hero Carousel** | Banner slider với lerp transitions |
| ✨ **Shimmer Effect** | Loading skeleton hiện đại |
| 📱 **Edge-to-Edge** | Tận dụng toàn bộ màn hình, xử lý safe area |
| 🎯 **Canvas Icons** | Icons tự vẽ bằng code, không cần assets |
| 🌈 **Luckin Blue Theme** | Hệ thống theme chuẩn brand identity |

---

## 🛠️ Tech Stack

```
📦 Kotlin Multiplatform (KMP)
├── 🎨 Compose Multiplatform 1.7.1
├── 🧭 Voyager Navigation
├── 🎯 Material 3 Design
├── 📐 Window Insets (Safe Area)
└── 🔤 Custom Typography (Poppins)
```

---

## 📱 Các màn hình

| Màn hình | Mô tả |
|----------|-------|
| 🏠 **Home** | Hero banner, product grid, category sidebar |
| 🛒 **Order** | Danh sách đơn hàng với animations |
| 👤 **Account** | Thông tin tài khoản, settings |
| 📦 **Product Detail** | Popup chi tiết sản phẩm |

---

## 🚀 Cài đặt & Chạy

### Yêu cầu
- JDK 17+
- Android Studio Hedgehog (2023.1.1) trở lên
- Kotlin 2.1+

### Clone project

```bash
git clone https://github.com/salem98/kmp-luckin-coffee-clone.git
cd kmp-luckin-coffee-clone
```

### Chạy Android

```bash
./gradlew :composeApp:installDebug
```

### Chạy Desktop

```bash
./gradlew :composeApp:run
```

### Chạy Web (WASM)

```bash
./gradlew :composeApp:wasmJsBrowserDevelopmentRun
```

---

## 📂 Cấu trúc dự án

```
composeApp/
├── src/
│   ├── commonMain/          # 🎯 Code dùng chung cho tất cả platforms
│   │   └── kotlin/
│   │       └── com/luckin/clone/
│   │           ├── ui/
│   │           │   ├── components/   # UI Components
│   │           │   ├── screens/      # Các màn hình
│   │           │   └── theme/        # Theme, Colors, Typography
│   │           ├── data/             # Models, Mock data
│   │           └── navigation/       # Navigation setup
│   │
│   ├── androidMain/         # 📱 Code riêng Android
│   ├── iosMain/             # 🍎 Code riêng iOS
│   ├── desktopMain/         # 🖥️ Code riêng Desktop
│   └── wasmJsMain/          # 🌐 Code riêng Web
```

---

## 🎨 UI Components

### Đã implement:
- ✅ `HeroBannerCarousel` - Auto-sliding banner với page indicators
- ✅ `AnimatedProductCard` - Card sản phẩm với hover/press animations
- ✅ `CategorySidebar` - Sidebar phân loại với scroll fade
- ✅ `ShimmerEffect` - Loading placeholder
- ✅ `LuckinIcons` - Custom Canvas-drawn icons
- ✅ `ProductDetailPopup` - Bottom sheet chi tiết sản phẩm
- ✅ `ScreenScaffold` - Base layout với safe area handling

---

## 📚 Học được gì từ dự án này?

1. **Kotlin Multiplatform Architecture** - Cách tổ chức code shared/platform-specific
2. **Compose Multiplatform** - Xây dựng UI declarative cho multi-platform
3. **Custom Animations** - Lerp transitions, spring animations
4. **Canvas Drawing** - Vẽ icons/graphics bằng code
5. **Theme System** - Xây dựng Design System hoàn chỉnh
6. **Edge-to-Edge UI** - Xử lý safe area insets đúng cách

---

## 🤝 Đóng góp

Mọi đóng góp đều được chào đón! Hãy:

1. ⭐ **Star** repo nếu thấy hữu ích
2. 🍴 **Fork** và tạo Pull Request
3. 🐛 **Report bugs** qua Issues
4. 💡 **Đề xuất features** mới

---

## 📞 Liên hệ

Có thắc mắc gì về KMP/Compose Multiplatform? Liên hệ mình qua:

<div align="center">

[![Facebook](https://img.shields.io/badge/Facebook-Phan_Thanh_Nhân-1877F2?style=for-the-badge&logo=facebook&logoColor=white)](https://fb.me/ptnhan98)

</div>

---

## 📄 License

```
MIT License

Copyright (c) 2026 Phan Thanh Nhân

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.
```

---

<div align="center">

**Made with ❤️ and ☕ in Vietnam**

*Nếu dự án này giúp ích cho bạn, hãy cho mình một ⭐ nhé!*

</div>
