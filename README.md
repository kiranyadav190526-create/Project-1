# FoodHub - Food Delivery Website

A modern, premium food delivery web interface for browsing restaurants, selecting food items, and managing orders.

## Features

### ✨ Core Functionality
- **Restaurant Listing** - Browse through multiple restaurants with ratings and delivery times
- **Menu Display** - View detailed menus with item descriptions and prices
- **Cart System** - Add items to cart, adjust quantities, and manage your order
- **Order Summary** - Review and confirm orders with detailed breakdown

### 🎨 Design Highlights
- **Premium UI/UX** - Modern gradient design with smooth animations
- **Responsive Layout** - Works seamlessly on desktop, tablet, and mobile
- **Interactive Elements** - Hover effects, micro-animations, and smooth transitions
- **Glassmorphism Effects** - Beautiful backdrop blur and transparency effects
- **Dynamic Animations** - Floating cards, slide-ins, and bounce effects

### 🍕 Categories
- Pizza
- Burgers
- Asian Cuisine
- Sushi
- Desserts
- Healthy Options

### 🏪 Sample Restaurants
1. **Pizza Paradise** - Italian, Pizza (Fast Delivery)
2. **Burger House** - American, Burgers (Top Rated)
3. **Asian Fusion** - Asian, Chinese, Thai (Offers)
4. **Sushi Master** - Japanese, Sushi (Top Rated)
5. **Sweet Treats** - Desserts, Bakery (Fast Delivery)
6. **Healthy Bowl** - Healthy, Salads (Offers)

## Technologies Used

- **HTML5** - Semantic markup with SEO optimization
- **CSS3** - Custom design system with CSS variables
- **JavaScript** - Vanilla JS for all interactions
- **JSON Data** - Restaurant and menu data structure

## File Structure

```
food-delivery/
├── index.html          # Main HTML file
├── styles.css          # Complete styling with design system
├── script.js           # JavaScript functionality
└── README.md          # This file
```

## Design System

### Color Palette
- **Primary**: Orange gradient (#FF6B6B to #FF8E53)
- **Secondary**: Purple gradient (#667eea to #764ba2)
- **Success**: Green (#10B981)
- **Warning**: Yellow (#FFA500)
- **Error**: Red (#EF4444)

### Typography
- **Primary Font**: Inter
- **Display Font**: Outfit

### Key Features
- Custom CSS variables for consistency
- Smooth transitions and animations
- Box shadows and glows for depth
- Responsive grid layouts
- Flexible spacing system

## How to Use

1. **Browse Restaurants**: Scroll through the restaurant listings or use category filters
2. **Filter Options**: Use chips to filter by "Fast Delivery", "Top Rated", or "Offers"
3. **View Menu**: Click on any restaurant card to open the menu modal
4. **Add to Cart**: Browse menu items and click "Add to Cart"
5. **Manage Cart**: Click the cart icon to view and modify your order
6. **Checkout**: Click "Proceed to Checkout" to place your order
7. **Order Confirmation**: View your order summary with order ID and estimated delivery time

## Interactive Elements

### Header
- Sticky navigation with blur effect
- Search button
- Cart with item count badge
- Sign in button

### Hero Section
- Animated background pattern
- Floating food emoji cards
- Address search functionality

### Categories
- 6 food category cards
- Hover animations with rotation
- Click to filter restaurants

### Restaurant Cards
- Image with gradient overlay on hover
- Rating and delivery time
- Category badges
- Smooth lift animation on hover

### Menu Modal
- Tabbed menu categories
- Item images and descriptions
- Add to cart functionality
- Smooth slide-in animation

### Cart Sidebar
- Slide-in from right
- Quantity controls
- Remove items
- Real-time total calculation

### Order Summary
- Success animation
- Order details breakdown
- Items list
- Track order button

## Customization

### Adding New Restaurants
Edit the `restaurantsData` array in `script.js`:

```javascript
{
    id: 7,
    name: "Your Restaurant",
    cuisine: "Cuisine Type",
    rating: 4.5,
    deliveryTime: "30-40 min",
    image: "image-url",
    badge: "Badge Text",
    category: "category-name",
    menu: [...]
}
```

### Changing Colors
Modify CSS variables in `styles.css`:

```css
:root {
    --primary-500: hsl(12, 100%, 67%);
    /* Add your custom colors */
}
```

## Browser Compatibility

- Chrome (recommended)
- Firefox
- Safari
- Edge
- Opera

## Performance

- Lightweight vanilla JavaScript (no frameworks)
- Optimized CSS with minimal specificity
- Efficient DOM manipulation
- Smooth 60fps animations

## Future Enhancements

- User authentication
- Real-time order tracking
- Payment integration
- Restaurant search
- Favorites/wishlist
- Order history
- Reviews and ratings
- Delivery address management
- Multiple payment methods
- Promotional codes

## License

This project is open source and available for educational purposes.

## Credits

Created with modern web development best practices, focusing on user experience and visual excellence.

---

**Enjoy your food delivery experience! 🍕🍔🍜**
