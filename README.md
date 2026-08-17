

# 🏠 Home Services App

> **Your One-Stop Solution for All Home Service Needs**

A modern, feature-rich Flutter application that connects users with professional home service providers. Built with clean architecture, BLoC/Cubit state management, and a stunning dark/light theme experience.

---
## 📱 Screenshots

<div align="center">
  <table>
    <tr>
      <td align="center"><b>Home Screen</b></td>
      <td align="center"><b>Search Bar</b></td>
      <td align="center"><b>Search Results</b></td>
    </tr>
    <tr>
      <td><img src="assets/images/s1.jpeg" width="200"/></td>
      <td><img src="assets/images/s2.jpeg" width="200"/></td>
      <td><img src="assets/images/s3.jpeg" width="200"/></td>
    </tr>
    <tr>
      <td align="center"><b>Service Details</b></td>
      <td align="center"><b>Login Required</b></td>
      <td align="center"><b>Create Account</b></td>
    </tr>
    <tr>
      <td><img src="assets/images/s4.jpeg" width="200"/></td>
      <td><img src="assets/images/s5.jpeg" width="200"/></td>
      <td><img src="assets/images/s6.jpeg" width="200"/></td>
    </tr>
    <tr>
      <td align="center"><b>Logged In</b></td>
      <td align="center"><b>Booking Screen</b></td>
      <td align="center"><b>Select Worker</b></td>
    </tr>
    <tr>
      <td><img src="assets/images/s7.jpeg" width="200"/></td>
      <td><img src="assets/images/s8.jpeg" width="200"/></td>
      <td><img src="assets/images/s9.jpeg" width="200"/></td>
    </tr>
    <tr>
      <td align="center"><b>Set Location</b></td>
      <td align="center"><b>Pick Time</b></td>
      <td align="center"><b>Confirm Booking</b></td>
    </tr>
    <tr>
      <td><img src="assets/images/s10.jpeg" width="200"/></td>
      <td><img src="assets/images/s11.jpeg" width="200"/></td>
      <td><img src="assets/images/s12.jpeg" width="200"/></td>
    </tr>
    <tr>
      <td align="center"><b>My Bookings</b></td>
      <td align="center"><b>Cancel Dialog</b></td>
      <td align="center"><b>Rating Dialog</b></td>
    </tr>
    <tr>
      <td><img src="assets/images/s13.jpeg" width="200"/></td>
      <td><img src="assets/images/s14.jpeg" width="200"/></td>
      <td><img src="assets/images/s15.jpeg" width="200"/></td>
    </tr>
    <tr>
      <td align="center"><b>Completed Bookings</b></td>
      <td align="center"><b>Booking Details</b></td>
      <td align="center"><b>Profile Screen</b></td>
    </tr>
    <tr>
      <td><img src="assets/images/s16.jpeg" width="200"/></td>
      <td><img src="assets/images/s17.jpeg" width="200"/></td>
      <td><img src="assets/images/s18.jpeg" width="200"/></td>
    </tr>
  </table>
</div>
## 🎥 Video Demo

Watch a full walkthrough of the app in action:

▶️ [Watch Demo Video](https://drive.google.com/file/d/1ITlBB_11qw-iIgBnZv2_QVBg5gMuql-E/view?usp=drive_link)

---

## ✨ Features

### 🎯 Core Features

| Feature | Description |
|---------|-------------|
| **Browse Services** | Explore services by category (Cleaning, Maintenance, Moving, Security, Outdoor, Finishing) |
| **Service Details** | View detailed information, pricing, duration, and provider ratings |
| **Book Now** | Seamless booking flow with date/time selection using an analog clock picker |
| **Booking Confirmation** | Instant confirmation with booking ID and transaction details |
| **Booking Management** | Track upcoming, completed, and cancelled bookings with swipe-to-delete |
| **Address Management** | Add, edit, and save service addresses |
| **Special Instructions** | Add notes for service providers |
| **Order Summary** | Clear breakdown of costs with total amount |

### 🎨 UI/UX Features

| Feature | Description |
|---------|-------------|
| **Glassmorphism Design** | Modern glass-effect cards |
| **Neon Effects** | Beautiful glowing elements in dark mode |
| **Dark/Light Theme** | Full support with a smooth toggle experience |
| **Responsive Layout** | Works on all screen sizes |
| **Custom Animations** | Smooth transitions and interactions throughout |
| **Custom Font** | Unique typography for brand identity |
| **SVG Icons** | High-quality icons for all categories |

### 🔧 Technical Features

| Feature | Description |
|---------|-------------|
| **Clean Architecture** | Feature-first structure with clear separation of concerns |
| **BLoC/Cubit Pattern** | Predictable, testable state management |
| **Custom Painter** | Analog clock widget for time selection |
| **Swipe to Delete** | Dismissible bookings with undo functionality |
| **Rating System** | Multi-step rating dialog for completed bookings |
| **Cross-Platform** | Android & iOS support |
| **Centralized Routing** | Organized navigation via `AppRoutes` / `AppRouter` |

### 📱 Screen-by-Screen Highlights

<details>
<summary><b>🏠 Home Screen</b></summary>

- Hero section with welcome image
- Categories grid
- Customer reviews section
- Dark/Light mode toggle
</details>

<details>
<summary><b>📋 Service Listing Screen</b></summary>

- Services grouped by category
- Live search bar
- Filter chips
- Glassmorphism service cards
- Empty-state handling
</details>

<details>
<summary><b>📄 Service Details Screen</b></summary>

- Full service details
- Tabs (Description, Included, Reviews)
- Stats row (Rating, Duration, Price)
- Sticky bottom bar with Book Now button
</details>

<details>
<summary><b>📅 Booking Screen</b></summary>

- Service summary card with image and price
- Interactive calendar date picker
- Analog clock time picker
- Address management (add/edit)
- Special notes field for the provider
- Order summary with cost breakdown
- Fixed bottom sheet with total amount + Confirm button
</details>

<details>
<summary><b>✅ Booking Confirmed Screen</b></summary>

- Success animation (Lottie)
- Confirmation message
- Full booking details (ID, date, time, address)
- Provider info (name and rating)
- Amount paid and transaction ID
- Back to Home button
</details>

<details>
<summary><b>📚 My Bookings Screen</b></summary>

- Tabbed interface (Upcoming, Completed, Cancelled)
- Booking cards with provider info
- Swipe-to-delete for completed/cancelled bookings
- Rating dialog with multi-step flow
- Undo delete functionality
</details>

### 🎨 Theme & Colors

| Mode | Palette |
|------|---------|
| 🌞 **Light** | Warm, natural colors · white background · translucent glass cards |
| 🌙 **Dark** | Deep black background (`#0A0A0A`) · neon accent (`#4FE3B2`) · glowing highlights |

---

## 🛠️ Tech Stack

| Technology | Version |
|------------|---------|
| Flutter | ^3.11.4 |
| Dart | ^3.11.4 |
| flutter_bloc | ^8.1.3 |
| iconsax_flutter | ^1.0.0 |
| flutter_svg | ^2.2.1 |
| lottie | ^2.0.0 |
| cupertino_icons | ^1.0.8 |

---

## 📂 Project Structure

```
home_services_app/
├── lib/
│   ├── main.dart
│   ├── firebase_options.dart
│   │
│   ├── core/
│   │   ├── cubit/
│   │   │   ├── theme_cubit.dart
│   │   │   └── theme_state.dart
│   │   └── theme/
│   │       ├── app_colors.dart
│   │       ├── app_text_styles.dart
│   │       ├── app_theme.dart
│   │       └── dark_app_colors.dart
│   │
│   ├── data/
│   │   ├── categories_data.dart
│   │   ├── categories_items_data.dart
│   │   ├── how_it_works_data.dart
│   │   ├── reviews_data.dart
│   │   └── technicians_data.dart
│   │
│   ├── models/
│   │   ├── booking_model.dart
│   │   ├── booking_confirmation_model.dart
│   │   ├── booking_history_model.dart
│   │   ├── category_model.dart
│   │   ├── category_item_model.dart
│   │   ├── how_it_works_step.dart
│   │   ├── payment_method.dart
│   │   ├── review_model.dart
│   │   ├── service_model.dart
│   │   ├── technician_model.dart
│   │   └── user_model.dart
│   │
│   ├── routes/
│   │   ├── app_routes.dart
│   │   └── app_router.dart
│   │
│   ├── widgets/
│   │   ├── custom_app_bar.dart
│   │   ├── custom_bottom_nav.dart
│   │   └── custom_button.dart
│   │
│   └── features/
│       │
│       ├── Splash/
│       │   └── Splash_Screen.dart
│       │
│       ├── onboarding/
│       │   └── Onboarding.dart
│       │
│       ├── Auth/
│       │   ├── auth_screen.dart
│       │   ├── cubit/
│       │   │   ├── auth_cubit.dart
│       │   │   └── auth_state.dart
│       │   └── widgets/
│       │       ├── auth_button.dart
│       │       └── auth_text_field.dart
│       │
│       ├── home/
│       │   ├── cubit/
│       │   │   ├── home_cubit.dart
│       │   │   └── home_state.dart
│       │   ├── presentation/
│       │   │   └── home_screen.dart
│       │   └── widgets/
│       │       ├── categories_section.dart
│       │       ├── category_card.dart
│       │       ├── hero_section.dart
│       │       ├── offer_slider.dart
│       │       ├── popular_services_section.dart
│       │       ├── quick_actions.dart
│       │       ├── reviews_section.dart
│       │       └── review_card.dart
│       │
│       ├── search/
│       │   └── all_services_search_screen.dart
│       │
│       ├── service_listing/
│       │   ├── service_listing_screen.dart
│       │   ├── cubit/
│       │   │   ├── service_listing_cubit.dart
│       │   │   └── service_listing_state.dart
│       │   └── widgets/
│       │       ├── badge.dart
│       │       ├── category_banner.dart
│       │       ├── duration_chip.dart
│       │       ├── empty_services.dart
│       │       ├── filter_chips.dart
│       │       ├── price_section.dart
│       │       ├── rating_chip.dart
│       │       ├── search_bar_widget.dart
│       │       ├── service_list_card.dart
│       │       └── view_details_button.dart
│       │
│       ├── service_details/
│       │   ├── service_details_screen.dart
│       │   ├── cubit/
│       │   │   ├── service_details_cubit.dart
│       │   │   └── service_details_state.dart
│       │   └── widgets/
│       │       ├── service_bottom_bar.dart
│       │       ├── service_description_content.dart
│       │       ├── service_details_app_bar.dart
│       │       ├── service_included_content.dart
│       │       ├── service_stats_row.dart
│       │       └── service_tabs_section.dart
│       │
│       ├── book_now/
│       │   ├── cubit/
│       │   │   ├── booking_cubit.dart
│       │   │   └── booking_state.dart
│       │   ├── presentation/
│       │   │   ├── book_now_screen.dart
│       │   │   └── technician_profile_screen.dart
│       │   └── Widgets/
│       │       ├── analog_clock_painter.dart
│       │       ├── booking_address.dart
│       │       ├── booking_app_bar.dart
│       │       ├── booking_bottom_sheet.dart
│       │       ├── booking_date_dialog.dart
│       │       ├── booking_date_picker.dart
│       │       ├── booking_dialog.dart
│       │       ├── booking_payment_method.dart
│       │       ├── booking_photo_upload.dart
│       │       ├── booking_section_title.dart
│       │       ├── booking_service_card.dart
│       │       ├── booking_summary.dart
│       │       ├── booking_technician_picker.dart
│       │       ├── booking_time_dialog.dart
│       │       └── booking_time_picker.dart
│       │
│       ├── bookings/
│       │   ├── cubit/
│       │   │   ├── bookings_cubit.dart
│       │   │   └── bookings_state.dart
│       │   ├── presentation/
│       │   │   └── bookings_screen.dart
│       │   ├── styles/
│       │   │   └── booking_styles.dart
│       │   └── widgets/
│       │       ├── swipe_hint.dart
│       │       ├── swipe_to_delete.dart
│       │       ├── booking_card/
│       │       │   ├── action_button.dart
│       │       │   ├── booking_card.dart
│       │       │   ├── booking_card_actions.dart
│       │       │   ├── booking_card_details.dart
│       │       │   ├── booking_card_header.dart
│       │       │   ├── detail_item.dart
│       │       │   ├── price_tag.dart
│       │       │   ├── service_image.dart
│       │       │   └── status_badge.dart
│       │       ├── booking_tabs/
│       │       │   ├── booking_tabs.dart
│       │       │   └── tab_button.dart
│       │       └── dialogs/
│       │           ├── cancel_booking_dialog.dart
│       │           ├── rating_dialog/
│       │           │   ├── feedback_chip.dart
│       │           │   ├── option_card.dart
│       │           │   ├── rating_dialog.dart
│       │           │   └── rating_progress.dart
│       │           └── steps/
│       │               ├── completion_step.dart
│       │               ├── done_step.dart
│       │               ├── feedback_step.dart
│       │               └── rating_step.dart
│       │
│       ├── booking_confirmed/
│       │   ├── presentation/
│       │   │   └── booking_confirmed.dart
│       │   └── Widgets/
│       │       ├── confirmed_back_button.dart
│       │       ├── confirmed_badge.dart
│       │       ├── confirmed_details_card.dart
│       │       ├── confirmed_divider.dart
│       │       ├── confirmed_footer.dart
│       │       ├── confirmed_info_row.dart
│       │       ├── confirmed_success_icon.dart
│       │       ├── confirmed_title.dart
│       │       └── full_screen_map_screen.dart
│       │
│       ├── how_it_works/
│       │   ├── screens/
│       │   │   └── how_it_works_screen.dart
│       │   └── widgets/
│       │       ├── bubble_outline_painter.dart
│       │       ├── how_it_works_dots.dart
│       │       ├── how_it_works_progress_bar.dart
│       │       ├── phone_mockup.dart
│       │       ├── rotating_background_rings.dart
│       │       ├── speech_bubble_clipper.dart
│       │       └── step_card.dart
│       │
│       ├── location/
│       │   ├── service_location_card.dart
│       │   ├── cubit/
│       │   │   ├── location_cubit.dart
│       │   │   └── location_state.dart
│       │   ├── data/
│       │   │   └── repositories/
│       │   │       └── location_repository.dart
│       │   ├── domain/
│       │   │   └── entities/
│       │   │       └── location.dart
│       │   └── presentation/
│       │       └── location_screen.dart
│       │
│       └── profile/
│           └── profile_screen.dart
│
├── assets/
├── test/
├── pubspec.yaml
└── README.md
```

---

## 🛠️ Customize Demo Data

All static data is located in `lib/data/`. You can easily modify or add new services, technicians, reviews, and categories.

### 📂 Data Files

| File | Purpose |
|------|---------|
| `categories_data.dart` | Categories and their services |
| `technicians_data.dart` | Service providers |
| `reviews_data.dart` | Customer reviews |
| `how_it_works_data.dart` | Onboarding tutorial steps |

---

### ➕ Add a New Service

1. Open `lib/data/categories_data.dart`
2. Find your category (e.g., `cleaningServices`)
3. Add a new service:

```dart
final newService = ServiceModel(
  id: 's100',                          // Unique ID
  name: 'Premium Cleaning',
  subtitle: 'Deep cleaning service',
  description: 'Full description here...',
  image: 'assets/images/services/cleaning/premium.png',
  price: 'Starting from 300 EGP',
  rating: 4.9,
  duration: '3 Hours',
  categoryId: 'cleaning',
  about: 'About the service...',
  specialistName: 'Ahmed Hassan',
  specialistTitle: 'CLEANING EXPERT',
  specialistRating: 4.9,
  reviewsCount: 150,
  keyPoints: ['Key point 1', 'Key point 2'],
  included: [
    {'title': 'Service 1', 'description': 'Description 1'},
  ],
  statIcon: Icons.cleaning_services,
  statLabel: 'Eco-Friendly',
);

cleaningServices.add(newService);
```

---

### ➕ Add a New Technician

1. Open `lib/data/technicians_data.dart`
2. Add a new technician:

```dart
final newTech = TechnicianModel(
  id: 't10',                    // Unique ID
  name: 'Mohamed Ali',
  photo: 'assets/images/technicians/mohamed.png',
  rating: 4.8,
  completedJobs: 320,
  specialty: 'Plumbing Expert',
);

techniciansData.add(newTech);
```

---

### ➕ Add a New Review

1. Open `lib/data/reviews_data.dart`
2. Add a new review:

```dart
final newReview = ReviewModel(
  name: 'Sara Ahmed',
  image: 'assets/images/user4.png',
  rating: 5.0,
  comment: 'Amazing service! Highly recommended.',
);

reviews.add(newReview);
```

---

### ➕ Add a New Category

1. Open `lib/data/categories_data.dart`
2. Add a new category with its services:

```dart
final newServices = [
  // Add services here
];

categories.add(
  CategoryModel(
    id: 'new_category',
    title: 'New Category',
    heroImage: 'assets/images/categories/new_category_hero.png',
    services: newServices,
  ),
);
```

---

### 🖼️ Image Guidelines

| Type | Location | Size |
|------|----------|------|
| Service | `assets/images/services/category/` | 500x500 |
| Technician | `assets/images/technicians/` | 200x200 |
| Category | `assets/images/categories/` | 800x400 |
| User Avatar | `assets/images/` | 100x100 |

---

### 🔄 After Changes

```bash
flutter clean
flutter pub get
flutter run
```

---

### ⚠️ Important

- ✅ Use **unique IDs** for all new items
- ✅ Follow the **same data structure** as existing items
- ✅ Image paths must match actual file locations
- ✅ Changes reflect immediately with hot reload

---

## 📬 Contact

- **Developer**: Youmna Khaled Youssef
- **LinkedIn**: [Youmna Khaled](https://www.linkedin.com/in/ўỗǘṃňã-khaled-869251375?utm_source=share_via&utm_content=profile&utm_medium=member_android)
- **GitHub**: [@Youmnakhaled20](https://github.com/Youmnakhaled20)

---

<p align="center">
  Made with ❤️ by <a href="https://www.linkedin.com/in/ўỗǘṃňã-khaled-869251375?utm_source=share_via&utm_content=profile&utm_medium=member_android">Youmna Khaled Youssef</a>
  <br>
  ⭐ Don't forget to star this repository!
</p>
