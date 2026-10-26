<div align="center">

#  chat_shop

**A Flutter app that combines real-time chat, live eBay product search, and location-aware ordering — with a fully adaptive UI.**


</div>

---

##  About

`chat_shop` is a personal Flutter playground built to explore, test, and refine features, architectures, and UI flows for learning and skill improvement.

---

##  Key Features

| Feature | Description |
|---|---|
|  **Authentication Flow** | Complete custom Signup and Login pages. |
|  **Google Integration** | "Link with Google" button that securely initializes and fetches the user's Gmail profile data. |
|  **1-on-1 Chat System** | Search for other registered users and chat privately in real time, with a dedicated Chat History page. |
|  **Live eBay Integration** | Dynamic search bar that fetches and displays real product data from the official eBay API. |
|  **Location-Aware E-Commerce** | Full Cart and Order system that captures and uses real-time GPS coordinates. |
|  **Currency Conversion** | Converts USD prices to INR using a dedicated currency service. |
|  **Adaptive UI** | Responsive layout that adjusts seamlessly to different screen sizes and orientations. |

---

##  Screenshots

###  Shopping

<table>
  <tr>
    <td align="center"><b>Home</b><br><img src="screenshots/home.png" width="220" alt="Home"></td>
     <td align="center"><b>Order View</b><br><img src="screenshots/order_view.png" width="220" alt="Order View"></td>
    
  </tr>
  <tr>
    <td align="center"><b>Item Details</b><br><img src="screenshots/item_details.png" width="220" alt="Item Details"></td>
     <td align="center"><b>Category Selected</b><br><img src="screenshots/category_selected.png" width="220" alt="Category Selected"></td>
     <td align="center"><b>Search Item</b><br><img src="screenshots/search_item.png" width="220" alt="Search Item"></td>
    <td align="center"><b>Order Detail</b><br><img src="screenshots/order_detail.png" width="220" alt="Order Detail"></td>
  </tr>
</table>

###  Chat

<table>
  <tr>
    <td align="center"><b>Chat History</b><br><img src="screenshots/chat_history.png" width="220" alt="Chat History"></td>
    <td align="center"><b>Chat View</b><br><img src="screenshots/chat_view.png" width="220" alt="Chat View"></td>
  </tr>
</table>

###  Adaptive / Desktop Layout

The UI seamlessly adjusts across different screen sizes.

<p align="center">
  <img src="screenshots/desktop_view.png" width="800" alt="Desktop View">
</p>

---

##  Architecture & Project Structure

```text
lib/
├── src/
│   ├── core/
│   │   ├── layout/          # Responsive scaffold components
│   │   └── services/        # Currency service (converts USD rate to INR)
│   ├── features/            # Modular app features (Search Items, Cart, Search Users, Orders, Chat, etc.)
│   └── app.dart             # Responsive layout wrapper (AppLayout)
├── firebase_options.dart    # Firebase auto-generated config
└── main.dart                # App entry point
```

The project follows a **feature-first** structure: each feature is self-contained, while shared pieces (layout, services) live in `core/`.

---

##  Getting Started



### Installation

```bash
# 1. Clone the repository


# 2. Install dependencies
flutter pub get

# 3. Configure Firebase
flutterfire configure

# 4. Run the app
flutter run
```


##  Tech Stack

- **Framework:** Flutter & Dart
- **Backend:** Firebase (Auth, real-time database for chat)
- **Auth:** Email/Password + Google Sign-In
- **APIs:** eBay Browse API, currency conversion service
- **Device:** GPS / location services

---





<div align="center">

 If you found this project useful, consider giving it a star!

</div>
