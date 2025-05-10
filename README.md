# Nikhil's Jeans - Next.js E-commerce Website

A modern, responsive e-commerce website built with Next.js and React. This project is a conversion of a static HTML/CSS website into a dynamic, component-based application with TypeScript.

## Features

- Modern React components with TypeScript
- Next.js for server-side rendering and static site generation
- Responsive design for mobile and desktop
- Dynamic product pages
- Shopping cart functionality
- CSS Modules for component-based styling

## Getting Started

### Prerequisites

- Node.js 14.x or later
- npm or yarn

### Installation

1. Clone the repository
```bash
git clone <repository-url>
cd jeans-nextjs
```

2. Install dependencies
```bash
npm install
# or
yarn install
```

3. Run the development server
```bash
npm run dev
# or
yarn dev
```

4. Open [http://localhost:3000](http://localhost:3000) with your browser to see the website.

## Project Structure

- `/components` - Reusable React components (Header, Footer, ProductCard, etc.)
- `/data` - Static data files for products and navigation
- `/pages` - Next.js pages and routing including index, cart, and products pages
- `/public` - Static assets (images, icons, etc.)
- `/styles` - CSS modules and global styles

## Technology Stack

- **Next.js**: React framework for server-side rendering and static site generation
- **TypeScript**: For type-safe JavaScript development
- **CSS Modules**: For component-scoped styling
- **React Icons**: For iconography

## Features Implemented

- Responsive navigation with mobile menu
- Dynamic product listing with filter and sort options
- Product detail pages with image gallery and related products
- Shopping cart with quantity adjustment and price calculations
- Breadcrumb navigation for user wayfinding

## Future Enhancements

Some ideas for enhancing the e-commerce functionality:

- User authentication with NextAuth.js
- Payment gateway integration
- Admin dashboard for managing products
- Search functionality
- User reviews and ratings
- Wishlist functionality

## Deployment

This Next.js app can be deployed to various platforms:

- Vercel (recommended for Next.js apps)
- Netlify
- AWS Amplify
- Traditional hosting with `npm run build` and `npm start`

## Design Principles

- **Symmetry**: All elements are carefully aligned and balanced
- **Whitespace**: Generous spacing for improved readability and focus
- **Typography**: Clear hierarchy with premium font selections
- **Color Palette**: Limited, premium palette for consistent branding
- **Animations**: Subtle transitions for enhanced user experience

## Browser Compatibility

- Chrome (latest)
- Firefox (latest)
- Safari (latest)
- Edge (latest)

## Project Overview

This is a static website for a clothing brand based on the design reference from dland.co.in. The website features a clean, modern design with a focus on showcasing jeans and other clothing products.

## Image Requirements

For this website to display properly, you'll need to add appropriate images to the `images` directory:

- `logo.png`: The DLAND logo
- `hero.jpg`: A large banner image for the hero section
- `product-1.jpg` to `product-4.jpg`: Product images for jeans
- `shirt-1.jpg` to `shirt-4.jpg`: Product images for shirts
- `banner-1.jpg` and `banner-2.jpg`: Banner images for promotional sections
- `full-banner.jpg`: A wide banner image for the "Made in India" section
- `community-1.jpg` to `community-5.jpg`: Community/customer images

## Credits

- Design inspiration: [DLAND](https://dland.co.in/)
- Font: Poppins (Google Fonts)
- Icons: Font Awesome
