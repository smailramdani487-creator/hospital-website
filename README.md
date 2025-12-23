# 🏥 Emergency Hospital Website

A modern, professional Emergency & Urgent Care Center website built with React, Framer Motion, and Tailwind CSS.

## ✨ Features

### 🎨 Design & Animations
- **Full Page Animations**: Smooth page transitions using Framer Motion
- **Micro-interactions**: Every button, card, and element has hover effects and animations
- **Loading Animations**: Professional loading screen with animated heartbeat logo
- **Scroll Animations**: Elements animate into view as you scroll
- **Gradient Backgrounds**: Modern gradient designs with emergency theme colors (Red, White, Dark Blue)

### 📱 Pages & Sections

1. **Home Page**
   - Animated hero section with emergency message
   - Professional call-to-action buttons with pulse animations
   - Feature cards with hover effects
   - Quick action section with ambulance animation

2. **Emergency Services**
   - 6 comprehensive services with animated cards
   - Ambulance Services, Trauma Care, ICU, Surgery, Pediatric Emergency, Critical Care
   - Interactive hover effects on each service card
   - Animated statistics section

3. **Doctors & Staff**
   - Animated doctor profile cards
   - Specialty information, experience, education
   - Achievement badges and ratings
   - Hover effects revealing more details

4. **Book Emergency Appointment**
   - Interactive form with real-time validation
   - Animated error messages
   - Success animation on submission
   - Multiple input fields: name, email, phone, date, time, department, urgency, symptoms

5. **Location & Map**
   - Interactive map with animated markers
   - 3 location options with full details
   - Smooth transitions between locations
   - Contact information and available services

6. **Contact Us**
   - Fully working contact form with validation
   - Contact information cards with icons
   - Emergency alert section
   - Animated submission states

### 🎯 Functionality

- ✅ **All Buttons Functional**: Navigation, emergency calls, appointments, forms
- ✅ **Form Validation**: Real-time validation with React Hook Form
- ✅ **Responsive Design**: Mobile, tablet, and desktop optimized
- ✅ **Emergency Modal**: Animated modal for emergency actions
- ✅ **Smooth Navigation**: Section-based routing with animated transitions
- ✅ **Professional UI/UX**: Clean, accessible, and user-friendly interface

### 🎨 Theme Colors

- **Emergency Red**: `#DC2626` (Primary emergency color)
- **Dark Red**: `#991B1B` (Accent)
- **Hospital Blue**: `#1E3A8A` (Professional medical color)
- **Light Blue**: `#1E40AF` (Secondary accent)
- **White**: Clean backgrounds and text

### 🚀 Technologies Used

- **React 18.3.1**: Modern UI framework
- **Framer Motion (motion/react)**: Advanced animations
- **Tailwind CSS 4**: Utility-first styling
- **React Hook Form**: Form validation
- **Lucide React**: Beautiful icons
- **TypeScript**: Type-safe development

## 🛠️ Installation & Setup

### Prerequisites
- Node.js 16+ installed
- npm or pnpm package manager

### Steps to Run Locally

1. **Install Dependencies**
   ```bash
   npm install
   # or
   pnpm install
   ```

2. **Start Development Server**
   ```bash
   npm run dev
   # or
   pnpm dev
   ```

3. **Open in Browser**
   - The application will automatically open at `http://localhost:5173`
   - If not, manually navigate to the URL shown in your terminal

4. **Build for Production**
   ```bash
   npm run build
   # or
   pnpm build
   ```

## 📂 Project Structure

```
/src
  /app
    /components
      - Navigation.tsx          # Sticky navigation with animations
      - LoadingScreen.tsx       # Initial loading animation
      - HeroSection.tsx         # Home page hero section
      - EmergencyServices.tsx   # Services page
      - DoctorsStaff.tsx        # Doctors & staff page
      - BookAppointment.tsx     # Appointment booking form
      - LocationMap.tsx         # Interactive location map
      - ContactUs.tsx           # Contact form
      - EmergencyModal.tsx      # Emergency action modal
    - App.tsx                   # Main app component
  /styles
    - theme.css                 # Custom CSS variables & emergency colors
    - index.css                 # Global styles
    - tailwind.css              # Tailwind imports
```

## 🎮 How to Use

### Navigation
- Click any menu item in the header to navigate between sections
- Mobile users: Tap the hamburger menu for navigation options
- All navigation is smooth with animated transitions

### Emergency Features
1. **Emergency Call Button**: Click the red "Emergency: 911" button in the header
2. **Emergency Modal**: Opens with three options:
   - Call 911 directly
   - Request an ambulance
   - Find nearest emergency room

### Booking Appointments
1. Navigate to "Appointment" section
2. Fill out the form with all required fields
3. Select department and urgency level
4. Submit with animated feedback

### Contact Form
1. Go to "Contact" section
2. Fill in name, email, subject, and message
3. Submit with real-time validation
4. Success animation on submission

## 🎨 Animation Details

### Types of Animations Used:

1. **Page Transitions**: Fade and slide animations between sections
2. **Hover Effects**: Scale, rotate, and color transitions on all interactive elements
3. **Loading Animations**: Rotating spinners and progress bars
4. **Heartbeat Animation**: Pulsing effect on emergency icons
5. **Float Animations**: Subtle up/down movement on key elements
6. **Slide-in Animations**: Elements appear from sides on scroll
7. **Pulse Animations**: Emergency alerts and badges
8. **Form Animations**: Smooth error messages and success states

## 📱 Responsive Breakpoints

- **Mobile**: < 768px
- **Tablet**: 768px - 1024px
- **Desktop**: > 1024px

All components are fully responsive with mobile-first design approach.

## 🔒 Important Notes

- This is a **demo application** for educational purposes
- Real emergency services should be contacted via 911 or local emergency numbers
- Forms submit data to console (no backend integration)
- Map is a visual placeholder (not connected to real mapping services)

## 🎯 Key Features Checklist

✅ Full animations everywhere  
✅ Smooth GSAP/Framer Motion animations  
✅ All buttons functional  
✅ Responsive design (mobile, tablet, desktop)  
✅ Fast loading & clean UI/UX  
✅ Emergency services section  
✅ Doctors & staff with animated cards  
✅ Book appointment form with validation  
✅ Live emergency call button  
✅ Location & map section  
✅ Contact form  
✅ Red, White, Dark Blue color scheme  
✅ Animated icons (heartbeat, ambulance, siren)  
✅ Animated modals  
✅ Loading animations  
✅ Accessible and clean code  

## 🚀 Performance

- Optimized animations for 60fps
- Lazy loading of components
- Efficient re-renders with React optimization
- Smooth scroll behavior
- Fast page transitions

## 🎨 Customization

### Change Colors
Edit `/src/styles/theme.css` and modify these CSS variables:
- `--emergency-red`
- `--hospital-blue`
- `--emergency-red-light`
- `--hospital-blue-light`

### Add New Sections
1. Create component in `/src/app/components/`
2. Import in `App.tsx`
3. Add to navigation in `Navigation.tsx`
4. Add to section switch in `App.tsx`

## 📄 License

This is a demo project created for educational purposes.

## 🤝 Support

For questions or issues, use the contact form in the application or reach out through the provided contact information.

---

**Built with ❤️ for Emergency Medical Services**
