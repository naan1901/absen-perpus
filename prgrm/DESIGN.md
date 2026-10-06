---
name: Pustaka Nusa
colors:
  surface: '#faf8ff'
  surface-dim: '#d2d9f4'
  surface-bright: '#faf8ff'
  surface-container-lowest: '#ffffff'
  surface-container-low: '#f2f3ff'
  surface-container: '#eaedff'
  surface-container-high: '#e2e7ff'
  surface-container-highest: '#dae2fd'
  on-surface: '#131b2e'
  on-surface-variant: '#444653'
  inverse-surface: '#283044'
  inverse-on-surface: '#eef0ff'
  outline: '#757684'
  outline-variant: '#c4c5d5'
  surface-tint: '#3755c3'
  primary: '#00288e'
  on-primary: '#ffffff'
  primary-container: '#1e40af'
  on-primary-container: '#a8b8ff'
  inverse-primary: '#b8c4ff'
  secondary: '#006a61'
  on-secondary: '#ffffff'
  secondary-container: '#86f2e4'
  on-secondary-container: '#006f66'
  tertiary: '#665f3d'
  on-tertiary: '#ffffff'
  tertiary-container: '#b4ab84'
  on-tertiary-container: '#453f20'
  error: '#ba1a1a'
  on-error: '#ffffff'
  error-container: '#ffdad6'
  on-error-container: '#93000a'
  primary-fixed: '#dde1ff'
  primary-fixed-dim: '#b8c4ff'
  on-primary-fixed: '#001453'
  on-primary-fixed-variant: '#173bab'
  secondary-fixed: '#89f5e7'
  secondary-fixed-dim: '#6bd8cb'
  on-secondary-fixed: '#00201d'
  on-secondary-fixed-variant: '#005049'
  tertiary-fixed: '#ede3b8'
  tertiary-fixed-dim: '#d1c79d'
  on-tertiary-fixed: '#201c02'
  on-tertiary-fixed-variant: '#4d4727'
  background: '#faf8ff'
  on-background: '#131b2e'
  surface-variant: '#dae2fd'
typography:
  display:
    fontFamily: Plus Jakarta Sans
    fontSize: 40px
    fontWeight: '800'
    lineHeight: 48px
    letterSpacing: -0.02em
  display-mobile:
    fontFamily: Plus Jakarta Sans
    fontSize: 30px
    fontWeight: '800'
    lineHeight: 38px
    letterSpacing: -0.02em
  headline-lg:
    fontFamily: Plus Jakarta Sans
    fontSize: 32px
    fontWeight: '700'
    lineHeight: 40px
    letterSpacing: -0.015em
  headline-lg-mobile:
    fontFamily: Plus Jakarta Sans
    fontSize: 24px
    fontWeight: '700'
    lineHeight: 32px
    letterSpacing: -0.01em
  headline-md:
    fontFamily: Plus Jakarta Sans
    fontSize: 24px
    fontWeight: '600'
    lineHeight: 32px
    letterSpacing: -0.01em
  headline-sm:
    fontFamily: Plus Jakarta Sans
    fontSize: 18px
    fontWeight: '600'
    lineHeight: 26px
    letterSpacing: 0em
  body-lg:
    fontFamily: Inter
    fontSize: 16px
    fontWeight: '400'
    lineHeight: 26px
    letterSpacing: 0em
  body-md:
    fontFamily: Inter
    fontSize: 14px
    fontWeight: '400'
    lineHeight: 22px
    letterSpacing: 0em
  body-sm:
    fontFamily: Inter
    fontSize: 12px
    fontWeight: '400'
    lineHeight: 18px
    letterSpacing: 0.01em
  label-lg:
    fontFamily: Plus Jakarta Sans
    fontSize: 14px
    fontWeight: '600'
    lineHeight: 20px
    letterSpacing: 0.01em
  label-md:
    fontFamily: Plus Jakarta Sans
    fontSize: 12px
    fontWeight: '600'
    lineHeight: 16px
    letterSpacing: 0.02em
  label-sm:
    fontFamily: Plus Jakarta Sans
    fontSize: 10px
    fontWeight: '700'
    lineHeight: 14px
    letterSpacing: 0.05em
rounded:
  sm: 0.25rem
  DEFAULT: 0.5rem
  md: 0.75rem
  lg: 1rem
  xl: 1.5rem
  full: 9999px
spacing:
  gutter: 1.5rem
  gutter-mobile: 1rem
  margin: 2rem
  margin-mobile: 1rem
  space-xs: 0.25rem
  space-sm: 0.5rem
  space-md: 1rem
  space-lg: 1.5rem
  space-xl: 2rem
---

## Brand & Style

This design system serves Indonesian high school students (SMA/SMK) and educators navigating modern digital library catalogs, digital book loans, and collaborative reading challenges. The brand personality balances studious focus with youthful, approachable optimism—shifting library interactions away from bureaucratic formality toward an engaging, vibrant intellectual space. 

The aesthetic synthesizes modern corporate clarity with tactile, friendly educational utility:
- **Clean Structure**: High legibility, crisp boundary definitions, and generous white space reduce visual cognitive load during study hours.
- **Youthful Academic Energy**: Rich royal blue anchors institutional trust and school identity, balanced by lively fresh teal and comforting warm cream tones.
- **Physical-to-Digital Bridge**: Micro-interactions echo physical paper, library stamps, and textured bookmark tags without falling into skeuomorphic excess.

## Colors

The palette pairs high-contrast scholastic blues with energetic teal accents, grounded on an ultra-soft, warm canvas that mitigates glare during prolonged reading.

- **Primary (`#1E40AF` - Royal Academic Blue)**: Encapsulates academic authority, institutional credibility, and core actionable states (primary CTAs, selected tabs, progress bars).
- **Secondary (`#0D9488` - Fresh Teal)**: Delivers a refreshing, modern Indonesian youth touchpoint. Used for secondary actions, active borrowing status badges, success indicators, and interactive highlights.
- **Tertiary (`#FEF3C7` - Warm Cream / Manila Accent)**: Evokes archival paper, sticky notes, and physical library cards. Deployed as a background tint for featured books, alert banners, and bookmark indicators.
- **Neutral (`#0F172A` - Deep Slate)**: Replaces stark black with a readable slate tone for body text, deep surfaces, and crisp borders.
- **Canvas & Surface Backgrounds**: The base surface operates at `#F8FAFC`, with book cards resting on pure white `#FFFFFF` layered over subtle borders (`#E2E8F0`).

## Typography

The typographic hierarchy combines the friendly geometric energy of **Plus Jakarta Sans** with the utilitarian precision of **Inter**.

- **Display & Headings (Plus Jakarta Sans)**: Designed for Indonesian character structures, diacritics, and title cases. Provides structural charm in book titles, hero borrowing metrics, and section headers.
- **Body & Continuous Reading (Inter)**: Handles long book synopses, borrowing terms, librarian notes, and metadata grids with neutral legibility.
- **Labels & Microcopy (Plus Jakarta Sans)**: Medium-to-bold weights ensure status badges, category chips, shelf tags (e.g., *Kurikulum Merdeka*, *Fiksi Remaja*), and form field labels remain legible on mobile displays.

## Layout & Spacing

A 12-column responsive fluid grid manages information density across desktop web platforms (librarian dashboards, desktop catalog search) and reflows into a single or 2-column view on student mobile devices.

- **Desktop (1024px and up)**: 12 columns, 1.5rem gutters, and 2rem outer canvas margins. Multi-pane arrangements support a persistent left-hand navigation bar, central catalog scroll, and a right-hand active loan rail.
- **Tablet (768px – 1023px)**: 8 columns with 1.25rem gutters. The borrowing summary becomes an overlay sheet.
- **Mobile (< 768px)**: 4 columns with 1rem gutters and 1rem edge margins. Book cover grids display in 2 columns with horizontal overflow rails for curated lists (e.g., *Rekomendasi Minggu Ini*).
- **Rhythm Rules**: All spacing adheres strictly to an 8pt base grid (with 4pt sub-steps for compact badge paddings and inline field labels).

## Elevation & Depth

Visual hierarchy leverages crisp surface separation via low-contrast borders combined with colored ambient shadows, avoiding heavy drops.

- **Flat / Zero Level (Surface Base)**: Base background `#F8FAFC`. Used behind grid layouts and main layout scaffolds.
- **Level 1 (Card & Content Blocks)**: White background `#FFFFFF`, bordered by 1px solid `#E2E8F0`. Soft ambient shadow: `0 2px 8px -2px rgba(15, 23, 42, 0.05)`.
- **Level 2 (Interactive Floating Elements & Dropdowns)**: Custom select overlays, user notifications, and hover states for book cards. Elevated with `0 10px 25px -5px rgba(30, 64, 175, 0.08), 0 4px 6px -2px rgba(15, 23, 42, 0.04)`.
- **Level 3 (Modals & Confirmation Sheets)**: Borrowing confirmation dialogues, student ID scan cards, and reading mode overlays. Utilizes `0 20px 35px -10px rgba(15, 23, 42, 0.16)` with a backdrop blur of `4px` tinting `#0F172A` at 30% opacity.

## Shapes

The design system incorporates rounded corners (Level 2) to maintain a friendly, approachable classroom feel while preserving architectural structure.

- **Base Radius (0.5rem / 8px)**: Applied to buttons, form inputs, category chips, and dropdown menus.
- **Large Radius (`rounded-lg` / 1rem / 16px)**: Applied to book cards, metric summary banners, modal containers, and book cover preview containers.
- **Extra Large Radius (`rounded-xl` / 1.5rem / 24px)**: Applied to bottom sheets, highlighted promotion containers, and reading challenge cards.
- **Pill (`full`)**: Applied strictly to status badges (e.g., *Tersedia*, *Dipinjam*, *Jatuh Tempo*) and student profile avatar wraps.

## Components

### Buttons
- **Primary**: Solid royal blue background (`#1E40AF`), white text (`#FFFFFF`), `font-weight: 600`, 0.5rem corner radius. Hover shifts to `#1D4ED8`. Active state scales down gently (`transform: scale(0.98)`).
- **Secondary**: Tinted teal background (`#F0FDFA`), teal text (`#0D9488`), border 1px solid (`#99F6E4`). Hover darkens to `#CCFBF1`.
- **Ghost/Tertiary**: Transparent background, slate text (`#334155`), with hover state `#F1F5F9`.

### Chips & Badges
- **Status Badges**: Pill-shaped with tight padding (`0.25rem 0.75rem`).
  - *Tersedia (Available)*: Emerald soft tint (`#ECFDF5`), emerald text (`#047857`), dot indicator (`#10B981`).
  - *Dipinjam (Borrowed)*: Amber warm cream tint (`#FEF3C7`), dark amber text (`#B45309`).
  - *Terlambat (Overdue)*: Rose tint (`#FFE4E6`), crimson text (`#BE123C`).
- **Category Chips**: Rectangular with 0.5rem radius, light slate background (`#F1F5F9`), slate text (`#475569`). Selected state toggles to `#1E40AF` with crisp white text.

### Form Inputs & Custom Dropdowns
- **Input Fields**: 0.5rem rounded corners, white background, bordered by 1.5px solid `#CBD5E1`. Padding `0.625rem 0.875rem`. Focus ring emits a 3px soft blue glow: `0 0 0 3px rgba(30, 64, 175, 0.15)` with border color changing to `#1E40AF`.
- **Search Bar**: Generous pill shape with left-aligned magnifying glass icon and warm cream clear button (`x`).
- **Custom Dropdowns**: Menu options nest inside an elevated Level 2 container. Each item provides a 0.5rem hover highlight with teal check indicators for active selections (e.g., filtering by Class: *Kelas X*, *Kelas XI*, *Kelas XII*).

### Checkboxes & Radio Buttons
- **Checkboxes**: 0.25rem rounded squares, 1.5px solid slate. Checked state fills with `#1E40AF` displaying a clean white checkmark vector.
- **Radio Buttons**: Dual circular boundary with 2px offset; active radio centers a solid `#1E40AF` disc.

### Book Cards
- **Catalog Card**: Vertical stack on Level 1 surface. Aspect ratio 3:4 rounded cover image at top with subtle inner border overlay (`rgba(0,0,0,0.04)`), book title (Plus Jakarta Sans 14px bold, 2-line clamp), author text (Inter 12px muted), and a bottom row displaying shelf location code (e.g., *Rak B-04*) alongside real-time availability badge.
- **Active Loan Card**: Horizontal orientation displaying miniature book cover, return due date warning, reading progress bar (teal `#0D9488`), and a one-click "Perpanjang" (Extend Loan) secondary button.

### Additional Domain Components
- **Due Date Countdown Ribbon**: Manila-cream banner (`#FEF3C7`) with contrasting maroon text showing remaining days before return due date.
- **Digital Library Card Modal**: Displays dynamic barcode / QR code for self-service physical scanner integration at the school library exit gate, styled with school badge watermark accents.