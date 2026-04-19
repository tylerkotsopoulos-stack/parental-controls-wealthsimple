# Parental Controls - Wealthsimple Design System

Complete end-to-end mobile prototype built with authentic Wealthsimple design system.

## 🎨 Authentic Wealthsimple Design

This prototype uses **real Wealthsimple design system** colors, typography, and UI patterns.

### Brand Colors

- **Primary Background:** `#ffffff` (White)
- **Primary Text/Dark:** `#32302f` (Dune)
- **Card Background:** `#F5F5F5` (Light gray)
- **Toggle Inactive:** `#D1D1D6` (Gray)
- **Toggle Active:** `#34C759` (Green)
- **Error Background:** `#FFEBEE` (Light red)
- **Error Text:** `#C62828` (Dark red)
- **Error Border:** `#EF5350` (Red)

### Typography

- **Font Family:** Futura PT (Wealthsimple's primary typeface)
- **Title Size:** 32px, weight 500, letter-spacing -0.5px
- **Body Size:** 17px, weight 500
- **Subtitle Size:** 16px, weight 400
- **Secondary Size:** 14px, weight 500

### Design Principles

- **Minimalist:** Clean white backgrounds with high contrast
- **Simple:** Limited color palette (black, white, gray, green)
- **Modern:** Generous white space, clean typography
- **Approachable:** Human-centered design, non-intimidating

### UI Components

**Toggle Switches:**
- 51px × 31px
- 16px border radius
- Gray inactive (#D1D1D6)
- Green active (#34C759)
- Smooth 300ms transition

**Cards:**
- Background: #F5F5F5
- Border radius: 12px
- Padding: 16px 20px
- Subtle hover states

**Buttons:**
- Background: #32302f (Dune)
- Color: white
- Border radius: 8px
- Padding: 16px
- Font weight: 500

**Input Fields:**
- Border: 1px solid #D1D1D6
- Border radius: 8px
- Padding: 12px 16px
- Focus border: #32302f

## 📱 Pages

### 1. Parental Controls Landing (`index.html`)
- Clean white interface with Dune text
- Light gray card backgrounds
- Green status badges
- Minimal icons and chevrons

### 2. Notifications (`notifications.html`)
- Toggle switches with Wealthsimple green
- Dynamic amount fields
- Clean card-based layout
- Dark Dune save button

### 3. Spend Limits (`spend-limits.html`)
- Real-time validation with error states
- Light red error backgrounds
- Clean error messaging
- Smart validation logic

### 4. Spend Restrictions (`spend-restrictions.html`)
- Transaction and category restrictions
- Master "Restrict all" toggle
- Disabled state for locked categories
- Icon-based category list

### 5. International Spending (`international-spending.html`)
- Simple single toggle
- Clean minimal interface
- Consistent with design system

## 🚀 How to Use

Open `/Users/tyler.kotsopoulos/parental-controls-wealthsimple/index.html` in your browser.

## 🎯 Key Features

✅ **Authentic Wealthsimple styling**
✅ **Futura PT typography**
✅ **Real brand colors (#32302f Dune, #34C759 green)**
✅ **Minimalist high-contrast design**
✅ **Clean white backgrounds**
✅ **Smooth transitions and interactions**
✅ **iPhone 17 Pro dimensions (393px)**
✅ **State persistence via localStorage**
✅ **Full validation on Spend Limits**
✅ **Dynamic field visibility**

## 📚 Sources

Design system based on research from:
- [Wealthsimple Brand Colors](https://mobbin.com/colors/brand/wealthsimple)
- [Wealthsimple Color Palette](https://colorfyi.com/brands/wealthsimple/)
- [Typography Details](https://www.typewolf.com/blog/favorite-sites-of-march-2016)
- [Wealthsimple Design System 2025 (Figma)](https://www.figma.com/community/file/1553208141755439461/wealthsimple-design-system-2025-ui-kit)

## 🔍 Design Details

**Status Bar:**
- Height: 54px
- Icons use #32302f (Dune) color

**Page Titles:**
- 32px, weight 500, -0.5px letter spacing
- Color: #32302f (Dune)

**Cards:**
- Background: #F5F5F5 (not pure white)
- Creates subtle depth without heavy shadows
- 12px border radius (not overly rounded)

**Toggles:**
- Inactive: #D1D1D6 (system gray)
- Active: #34C759 (iOS green)
- Matches native iOS feel

**Buttons:**
- Primary action: #32302f (Dune)
- White text for maximum contrast
- 8px border radius (subtly rounded)
- 16px padding (comfortable tap target)

**Error States:**
- Background: #FFEBEE (light red tint)
- Border: #EF5350 (red)
- Text: #C62828 (dark red)
- Non-aggressive, informative

This design maintains Wealthsimple's sophisticated, approachable aesthetic while ensuring excellent usability for parental controls.
