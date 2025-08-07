# MASSIMO Restaurant Website

A modern, responsive restaurant website built with Next.js 13, TypeScript, and Tailwind CSS. This application provides a complete dining experience with menu browsing, cart functionality, user authentication, and order management.

## 🍕 Features

### Core Functionality
- **Homepage** - Featured products slider, special offers, and promotional content
- **Menu System** - Categorized menu items with detailed product pages
- **Shopping Cart** - Add/remove items, quantity management, and checkout process
- **User Authentication** - Login system with social media integration (Google, Facebook)
- **Order Management** - Track orders and view order history
- **Responsive Design** - Mobile-first approach with Tailwind CSS

### Technical Features
- **Next.js 13** - App Router with server-side rendering
- **TypeScript** - Type-safe development
- **Tailwind CSS** - Utility-first styling
- **React Countdown** - Interactive countdown timers for offers
- **Modern UI/UX** - Clean, intuitive interface design

## 🚀 Getting Started

### Prerequisites
- Node.js 18+ 
- npm or yarn package manager

### Installation

1. **Clone the repository**
   ```bash
   git clone https://github.com/Arin-Tigga/MASSIMO
   cd restaurant-ui-main
   ```

2. **Install dependencies**
   ```bash
   npm install
   # or
   yarn install
   ```

3. **Run the development server**
   ```bash
   npm run dev
   # or
   yarn dev
   ```

4. **Open your browser**
   Navigate to [http://localhost:3000](http://localhost:3000) to view the application.

## 📁 Project Structure

```
restaurant-ui-main/
├── src/
│   ├── app/                    # Next.js App Router pages
│   │   ├── cart/              # Shopping cart functionality
│   │   ├── login/             # Authentication pages
│   │   ├── menu/              # Menu browsing and categories
│   │   ├── orders/            # Order management
│   │   ├── product/           # Individual product pages
│   │   └── layout.tsx         # Root layout component
│   ├── components/            # Reusable React components
│   │   ├── CartIcon.tsx       # Shopping cart icon
│   │   ├── CountDown.tsx      # Countdown timer component
│   │   ├── Featured.tsx       # Featured products section
│   │   ├── Footer.tsx         # Site footer
│   │   ├── Menu.tsx           # Menu display component
│   │   ├── Navbar.tsx         # Navigation bar
│   │   ├── Notification.tsx   # Notification system
│   │   ├── Offer.tsx          # Special offers section
│   │   ├── Price.tsx          # Price display component
│   │   └── Slider.tsx         # Image slider component
│   └── data.ts               # Product and menu data
├── public/                   # Static assets
│   ├── temporary/            # Product images
│   └── [other assets]        # Icons, backgrounds, etc.
└── [config files]           # Next.js, TypeScript, Tailwind configs
```

## 🛠️ Available Scripts

- `npm run dev` - Start development server
- `npm run build` - Build for production
- `npm run start` - Start production server
- `npm run lint` - Run ESLint for code quality

## 🍽️ Menu Categories

The website features a diverse menu with the following categories:
- **Pizzas** - Classic and specialty pizzas
- **Burgers** - Gourmet burgers with premium ingredients
- **Pasta** - Italian pasta dishes
- **Salads** - Fresh and healthy options
- **Beverages** - Drinks and refreshments

## 🎨 Design Features

- **Modern UI** - Clean, professional restaurant website design
- **Responsive Layout** - Optimized for desktop, tablet, and mobile devices
- **Interactive Elements** - Hover effects, animations, and smooth transitions
- **Accessibility** - Built with accessibility best practices in mind

## 🔧 Customization

### Adding New Products
Edit `src/data.ts` to add new menu items:
```typescript
{
  id: [unique_id],
  title: "Product Name",
  desc: "Product description",
  img: "/temporary/product-image.png",
  price: 29.9,
  options: [
    { title: "Small", additionalPrice: 0 },
    { title: "Medium", additionalPrice: 4 },
    { title: "Large", additionalPrice: 6 }
  ]
}
```

### Styling
The project uses Tailwind CSS for styling. Customize the design by modifying:
- `tailwind.config.js` - Tailwind configuration
- `src/app/globals.css` - Global styles
- Component-specific styles in individual component files

## 🌐 Deployment

### Vercel (Recommended)
1. Push your code to GitHub
2. Connect your repository to Vercel
3. Deploy automatically on every push

### Other Platforms
The application can be deployed to any platform that supports Next.js:
- Netlify
- AWS Amplify
- DigitalOcean App Platform
- Railway

## 📱 Browser Support

- Chrome (latest)
- Firefox (latest)
- Safari (latest)
- Edge (latest)

## 🤝 Contributing

1. Fork the repository
2. Create a feature branch (`git checkout -b feature/amazing-feature`)
3. Commit your changes (`git commit -m 'Add some amazing feature'`)
4. Push to the branch (`git push origin feature/amazing-feature`)
5. Open a Pull Request

## 📄 License

This project is licensed under the MIT License - see the LICENSE file for details.

## 🆘 Support

For support and questions:
- Create an issue in the repository
- Contact the development team

---

**MASSIMO Restaurant** - Bringing delicious food to your fingertips! 🍕✨

