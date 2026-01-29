# Equip Wellness Shopify Theme

A clean, minimalist Shopify theme inspired by holistic wellness and Japanese aesthetics. This theme is designed to showcase wellness products, particularly massage supplies and traditional remedies like Hagina Japanese Mint Oil.

## Features

- **Clean, Minimalist Design**: Inspired by Japanese wellness aesthetics with a focus on simplicity and functionality
- **Fully Responsive**: Optimized for all devices - mobile, tablet, and desktop
- **Shopify Compatible**: Built with Shopify Liquid templating and best practices
- **Product Showcase**: Beautiful product grid with quick add functionality
- **Customizable**: Easy to customize colors, fonts, and layout through Shopify theme editor
- **Performance Optimized**: Lazy loading images, optimized CSS, and minimal JavaScript
- **SEO Friendly**: Proper semantic HTML, meta tags, and structured data

## Theme Structure

```
shopify-theme/
├── theme.liquid              # Main theme template
├── assets/
│   ├── base.css             # Main stylesheet
│   └── base.js              # Main JavaScript file
├── sections/
│   ├── header.liquid        # Header section
│   └── footer.liquid        # Footer section
├── templates/
│   ├── index.liquid         # Homepage template
│   └── product.liquid       # Product page template
└── README.md                # This file
```

## Installation

1. **Download the theme files** to your local machine
2. **Log in to your Shopify admin** panel
3. **Navigate to Online Store > Themes**
4. **Click "Upload theme"** in the top right corner
5. **Select the theme ZIP file** (you'll need to ZIP the shopify-theme folder first)
6. **Wait for upload** and then click "Publish theme" on the new theme

## Customization

### Through Shopify Theme Editor

Most customization can be done directly through the Shopify theme editor:

1. Go to **Online Store > Themes**
2. Click **Customize** on your active theme
3. Use the sidebar to modify:
   - **Header**: Logo, navigation menu
   - **Homepage**: Hero content, featured products, about section
   - **Product Pages**: Layout, related products, features
   - **Footer**: About text, links, newsletter signup

### Advanced Customization

For more advanced changes, you can edit the theme files directly:

#### Colors and Typography
Edit `assets/base.css` to modify:
- CSS custom properties (colors, spacing, typography)
- Component styles
- Responsive breakpoints

#### Layout and Structure
Edit template files to modify:
- Page layouts (`templates/`)
- Section components (`sections/`)
- Overall theme structure (`theme.liquid`)

#### Functionality
Edit `assets/base.js` to:
- Add new interactive features
- Modify existing behavior
- Integrate third-party services

## Key Features

### Homepage Sections

- **Hero Section**: Eye-catching title and call-to-action buttons
- **Featured Products**: Showcase your best-selling or featured items
- **About Section**: Tell your brand story
- **Features**: Highlight key benefits of your products
- **Testimonials**: Build trust with customer reviews

### Product Pages

- **Image Gallery**: Multiple product images with zoom functionality
- **Variant Selection**: Easy variant picker for different options
- **Quick Add**: Add to cart directly from product pages
- **Related Products**: Cross-sell related items
- **Social Sharing**: Built-in social media sharing buttons

### Responsive Design

- **Mobile-First**: Optimized for mobile devices
- **Touch-Friendly**: Large tap targets and intuitive navigation
- **Fast Loading**: Optimized images and minimal code

## Browser Support

- Chrome (latest)
- Firefox (latest)
- Safari (latest)
- Edge (latest)
- iOS Safari (latest)
- Chrome Mobile (latest)

## Performance

The theme is optimized for performance with:

- **Lazy Loading**: Images load as needed
- **Minimal JavaScript**: Only essential functionality
- **Optimized CSS**: Efficient styling with minimal redundancy
- **Compressed Assets**: Minified CSS and JS files

## Support

For support or questions:

1. **Check Shopify Documentation**: [Shopify Theme Development](https://shopify.dev/docs/themes)
2. **Review Theme Code**: All files are well-commented
3. **Test Changes**: Always test changes in a development environment first

## License

This theme is provided as-is for use with Shopify stores. Please ensure you have the right to use any images, fonts, or third-party assets included in your implementation.

## Custom Development

If you need custom features or modifications beyond what's available in the theme editor, consider:

1. **Hiring a Shopify Expert**: [Shopify Experts Marketplace](https://experts.shopify.com/)
2. **Learning Liquid**: [Shopify Liquid Documentation](https://shopify.dev/docs/themes/liquid)
3. **Using Shopify Apps**: Extend functionality with apps from the Shopify App Store

## Best Practices

- **Regular Backups**: Always backup your theme before making changes
- **Test Thoroughly**: Test all functionality after making changes
- **Monitor Performance**: Keep an eye on page load times
- **Stay Updated**: Keep your theme and Shopify platform updated

## File Structure Details

### `theme.liquid`
The main template file that wraps all pages. Includes:
- HTML head with meta tags and fonts
- Shopify required tags (`{{ content_for_header }}`, `{{ content_for_footer }}`)
- Main layout structure with header, content area, and footer

### `assets/base.css`
Complete stylesheet with:
- CSS custom properties for easy theming
- Component styles (buttons, cards, forms)
- Responsive design utilities
- Animation and transition effects

### `assets/base.js`
JavaScript functionality including:
- Mobile navigation
- Product interactions
- Form handling
- Cart management
- Image lazy loading
- Notification system

### `sections/`
Reusable sections that can be customized through the theme editor:
- **Header**: Navigation, logo, cart
- **Footer**: Links, newsletter signup, social media

### `templates/`
Page-specific templates:
- **Index**: Homepage with multiple sections
- **Product**: Individual product pages with full functionality

This theme provides a solid foundation for a wellness-focused Shopify store with a clean, professional appearance that emphasizes product quality and user experience.
