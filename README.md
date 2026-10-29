# BaniyaBuddhi — Phase 1 User Authentication & Onboarding Mockup

A browser-ready, interactive design prototype created for **BaniyaBuddhi** covering the complete **Phase 1: User Authentication & Onboarding Flow**.

---

## 🎨 Visual Identity & Color System
- **Emerald Green (`#059669` / `#10B981`)**: Represents wealth optimization, savings, liquidity, and security.
- **Amber Gold (`#F59E0B` / `#D97706`)**: Highlights high-value credit card points, airline miles transfer bonuses, and elite rewards.
- **Slate & Deep Obsidian (`#0F172A` / `#022C22`)**: Modern FinTech foundation with high typographic contrast.
- **Typography**: Plus Jakarta Sans for crisp, premium mobile & web readability.

---

## 📱 Interactive User Journey Included in `index.html`

### 1. Mobile Authentication (Login / Sign-up)
- 10-digit Indian mobile number input with `+91` prefix and real-time numeric validation.
- Trust markers: 256-bit encryption, RBI guidelines compliant, no-spam pledge.
- Persona Switcher in the top bar to easily toggle between **New User** and **Existing User** routes during presentations.

### 2. Mobile SMS OTP Verification
- 6 individual OTP input boxes with auto-focusing on typing, backspace support, and copy-paste.
- Simulated resend countdown timer (`0:24s`) and instant "Quick Demo Code: `123456`" button.
- **State Check Bifurcation**:
  - **Existing User**: Verifies OTP $\rightarrow$ restores session $\rightarrow$ jumps immediately to the Dashboard.
  - **New User**: Verifies OTP $\rightarrow$ routes to Profile Setup.

### 3. Profile Setup (New Users Only)
- First Name and Last Name inputs.
- Email address input with interactive **Email OTP verification code (`8888`)** to satisfy the verification requirement before proceeding.
- Visual Step 1 of 3 progress bar (33%).

### 4. User Preferences Questionnaire
- **Step 2 of 3: Core Focus / Intent**:
  - *"What are you most interested in optimizing?"*
  - Multi-select interactive cards with visual tags:
    - *Digital Gift Cards & Vouchers* (Amazon, Swiggy, Flipkart)
    - *Credit Card Reward Points to Airline Miles / Hotel Points* (KrisFlyer, Accor, Taj)
    - *Both / All Rewards*
- **Step 3 of 3: Spending Categories**:
  - *"Which categories do you spend the most on?"*
  - Multi-select chips with emoji icons & brands:
    - Grocery & Daily Needs, Dining & Food Delivery, Shopping & Fashion, Travel & Flight Bookings, Entertainment & Movies, Utilities & Bill Payments.
  - **Prominent "Skip for now" action button** ensuring users are never blocked.

### 5. Completion & Personalized Dashboard
- Dynamic dashboard greeting personalized with the user's name and mobile number.
- Active preferences chips reflecting the exact choices made in the questionnaire.
- Priority deals feed ranked according to their selected intent (instant vouchers vs. airline point multipliers).
- One-click restart button to re-run the demo anytime.

---

## 🚀 How to View
Double-click `index.html` in your file explorer (or open it with Chrome / Edge / Safari / Firefox). No server or build step required!

