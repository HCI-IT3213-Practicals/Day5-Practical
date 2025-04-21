# Day 05 Practical Sessions - Dynamic Panels & Animations 🎬

Welcome to **Day 05** of the IT3213 Human-Computer Interaction (HCI) practical sessions! This session focuses on building interactive UI elements using **dynamic panels** and **animations** in **Axure RP 9**. Our goal is to create a fixed navigation bar and animated icon interactions that enhance the user experience across multiple pages.

---

## 🚀 Practical Overview

In this session, we:

- Implemented a **fixed navigation bar** using dynamic panels.
- Created scroll-triggered interactions.
- Designed a **looping bell icon animation** using Axure’s interaction logic.

The project now consists of **two interactive pages** showcasing scroll behavior, icon animations, and smart layout handling with Axure RP 9.

---

## ✅ Day 05 – Fixed Navbar & Bell Icon Animation 🛎️

### 🔝 01: Fixed Navigation Bar with Dynamic Panel

**Dynamic Panel Setup:**

- Grouped navigation icons: `Product`, `Design`, `Code`.
- Converted into a **dynamic panel**.
- **Pinned to Browser**: Positioned at the top-center of the screen.

**Scroll Interaction:**

- Used the `Window.scrollY` condition to **show/hide the navbar** dynamically based on scroll position.

📸 **Screenshots :**

> _Fixed Navigation Bar Example_
![Scrolled nav bar Output 1](https://github.com/user-attachments/assets/77a79a82-0f0c-427b-a18c-fd891c65ffd4)

![Scrolled nav bar Output 2](https://github.com/user-attachments/assets/411555a3-fa7c-4298-8a71-987932eb330f)

---

### 🔔 02: Animated Navigation Bar with Bell Icon

**UI Elements:**

- Search Button
- Axure Logo
- Bell Icon (animated)

**Bell Icon Animation Logic:**

- **Trigger:** On Page Load
- **Sequence:**
  - Rotate bell icon **-60°** (linear, 100ms)
  - Wait **100ms**
  - Rotate bell icon **+60°** (linear, 100ms)
  - **Trigger "Loaded"** event again to **loop the animation infinitely**

📸 **Screenshot :**

> _Animated Navbar with Bell Icon_
![Animation Bell Output](https://github.com/user-attachments/assets/527b8d29-86af-4c99-8ec9-889718ebd25a)

---

## 🔄 Interaction Logic: Bell Icon Animation

```plaintext
On Page Load:
→ Rotate Bell by -60° (linear 100ms)
→ Wait 100ms
→ Rotate Bell by +60° (linear 100ms)
→ Fire "Loaded" event again (loop animation)
```

---

## 📂 How to Use the Axure RP 9 File

1. Install **Axure RP 9** (if not already installed).
2. Download the `.rp` file from this repository.
3. Open the file and navigate between **Page 01** and **Page 02** using the Page Navigator.
4. Click **Preview** in Axure to see all interactions in action.

---

## 📜 License

This project is licensed under the **MIT License**.  
Please refer to the `LICENSE` file for more information.
