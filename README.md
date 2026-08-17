

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
      <td><img src="s1.jpeg" width="200"/></td>
      <td><img src="s2.jpeg" width="200"/></td>
      <td><img src="s3.jpeg" width="200"/></td>
    </tr>
    <tr>
      <td align="center"><b>Service Details</b></td>
      <td align="center"><b>Login Required</b></td>
      <td align="center"><b>Create Account</b></td>
    </tr>
    <tr>
      <td><img src="s4.jpeg" width="200"/></td>
      <td><img src="s5.jpeg" width="200"/></td>
      <td><img src="s6.jpeg" width="200"/></td>
    </tr>
    <tr>
      <td align="center"><b>Logged In</b></td>
      <td align="center"><b>Booking Screen</b></td>
      <td align="center"><b>Select Worker</b></td>
    </tr>
    <tr>
      <td><img src="s7.jpeg" width="200"/></td>
      <td><img src="s8.jpeg" width="200"/></td>
      <td><img src="s9.jpeg" width="200"/></td>
    </tr>
    <tr>
      <td align="center"><b>Set Location</b></td>
      <td align="center"><b>Pick Time</b></td>
      <td align="center"><b>Confirm Booking</b></td>
    </tr>
    <tr>
      <td><img src="s10.jpeg" width="200"/></td>
      <td><img src="s11.jpeg" width="200"/></td>
      <td><img src="s12.jpeg" width="200"/></td>
    </tr>
    <tr>
      <td align="center"><b>My Bookings</b></td>
      <td align="center"><b>Cancel Dialog</b></td>
      <td align="center"><b>Rating Dialog</b></td>
    </tr>
    <tr>
      <td><img src="s13.jpeg" width="200"/></td>
      <td><img src="s14.jpeg" width="200"/></td>
      <td><img src="s15.jpeg" width="200"/></td>
    </tr>
    <tr>
      <td align="center"><b>Completed Bookings</b></td>
      <td align="center"><b>Booking Details</b></td>
      <td align="center"><b>Profile Screen</b></td>
    </tr>
    <tr>
      <td><img src="s16.jpeg" width="200"/></td>
      <td><img src="s17.jpeg" width="200"/></td>
      <td><img src="s18.jpeg" width="200"/></td>
    </tr>
  </table>
</div>
## 🎥 Video Demo

Watch a full walkthrough of the app in action:

[▶️ Watch the Full App Demo](https://drive.google.com/file/d/1bIblAu1Wh8OObI53C45e_w4QCZtmfJlF/view?usp=sharing)

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
E:\ANDROID_STUDIO\HOME_SERVICES_APP_FOR_SALE\LIB
│   firebase_options.dart
│   main.dart
│
├───core
│   ├───cubit
│   │       theme_cubit.dart
│   │       theme_state.dart
│   │
│   └───theme
│           app_colors.dart
│           app_text_styles.dart
│           app_theme.dart
│           dark_app_colors.dart
│
├───data
│       categories_data.dart
│       categories_items_data.dart
│       how_it_works_data.dart
│       reviews_data.dart
│       technicians_data.dart
│
├───features
│   ├───Auth
│   │   ├───cubit
│   │   │       auth_cubit.dart
│   │   │       auth_state.dart
│   │   │
│   │   ├───presentation
│   │   │       auth_screen.dart
│   │   │
│   │   └───widgets
│   │           auth_actions_widget.dart
│   │           auth_button.dart
│   │           auth_fields_section.dart
│   │           auth_header_widget.dart
│   │           auth_text_field.dart
│   │           signup_form_widget.dart
│   │
│   ├───bookings
│   │   ├───cubit
│   │   │       bookings_cubit.dart
│   │   │       bookings_state.dart
│   │   │
│   │   ├───presentation
│   │   │       bookings_screen.dart
│   │   │
│   │   ├───styles
│   │   │       booking_styles.dart
│   │   │
│   │   └───widgets
│   │       │   swipe_hint.dart
│   │       │   swipe_to_delete.dart
│   │       │
│   │       ├───booking_card
│   │       │       action_button.dart
│   │       │       booking_card.dart
│   │       │       booking_card_actions.dart
│   │       │       booking_card_details.dart
│   │       │       booking_card_header.dart
│   │       │       detail_item.dart
│   │       │       price_tag.dart
│   │       │       service_image.dart
│   │       │       status_badge.dart
│   │       │
│   │       ├───booking_tabs
│   │       │       booking_tabs.dart
│   │       │       tab_button.dart
│   │       │
│   │       └───dialogs
│   │           │   cancel_booking_dialog.dart
│   │           │
│   │           ├───rating_dialog
│   │           │       feedback_chip.dart
│   │           │       option_card.dart
│   │           │       rating_dialog.dart
│   │           │       rating_progress.dart
│   │           │
│   │           └───steps
│   │                   completion_step.dart
│   │                   done_step.dart
│   │                   feedback_step.dart
│   │                   not_completed_dialog.dart
│   │                   rating_step.dart
│   │
│   ├───booking_confirmed
│   │   ├───presentation
│   │   │       booking_confirmed.dart
│   │   │
│   │   └───Widgets
│   │           confirmed_back_button.dart
│   │           confirmed_badge.dart
│   │           confirmed_details_card.dart
│   │           confirmed_divider.dart
│   │           confirmed_footer.dart
│   │           confirmed_info_row.dart
│   │           confirmed_success_icon.dart
│   │           confirmed_title.dart
│   │           full_screen_map_screen.dart
│   │
│   ├───book_now
│   │   ├───cubit
│   │   │       booking_cubit.dart
│   │   │       booking_state.dart
│   │   │
│   │   ├───presentation
│   │   │       book_now_screen.dart
│   │   │       technician_profile_screen.dart
│   │   │
│   │   └───Widgets
│   │       │   analog_clock_painter.dart
│   │       │   booking_address.dart
│   │       │   booking_app_bar.dart
│   │       │   booking_bottom_sheet.dart
│   │       │   booking_date_dialog.dart
│   │       │   booking_date_picker.dart
│   │       │   booking_dialog.dart
│   │       │   booking_payment_method.dart
│   │       │   booking_photo_upload.dart
│   │       │   booking_section_title.dart
│   │       │   booking_service_card.dart
│   │       │   booking_summary.dart
│   │       │   booking_technician_picker.dart
│   │       │   booking_time_dialog.dart
│   │       │   booking_time_picker.dart
│   │       │
│   │       └───technician_picker
│   │               booking_technician_picker.dart
│   │               technician_image_section.dart
│   │               technician_info_section.dart
│   │               technician_picker_card.dart
│   │               technician_pro_badge.dart
│   │               technician_selected_badge.dart
│   │
│   ├───explore
│   │   ├───presentation
│   │   │       explore_screen.dart
│   │   │
│   │   └───widgets
│   │           empty_services_widget.dart
│   │           explore_filter_row_widget.dart
│   │           explore_search_bar_widget.dart
│   │           service_result_tile_widget.dart
│   │
│   ├───home
│   │   ├───cubit
│   │   │       home_cubit.dart
│   │   │       home_state.dart
│   │   │
│   │   ├───presentation
│   │   │       home_screen.dart
│   │   │
│   │   └───widgets
│   │           categories_section.dart
│   │           category_card.dart
│   │           hero_section.dart
│   │           offer_slider.dart
│   │           popular_services_section.dart
│   │           quick_actions.dart
│   │           reviews_section.dart
│   │           review_card.dart
│   │
│   ├───how_it_works
│   │   ├───screens
│   │   │       how_it_works_screen.dart
│   │   │
│   │   └───widgets
│   │           bubble_outline_painter.dart
│   │           how_it_works_dots.dart
│   │           how_it_works_progress_bar.dart
│   │           phone_mockup.dart
│   │           rotating_background_rings.dart
│   │           speech_bubble_clipper.dart
│   │           step_card.dart
│   │
│   ├───location
│   │   ├───cubit
│   │   │       location_cubit.dart
│   │   │       location_state.dart
│   │   │
│   │   ├───data
│   │   │   └───repositories
│   │   │           location_repository.dart
│   │   │
│   │   ├───domain
│   │   │   └───entities
│   │   │           location.dart
│   │   │
│   │   ├───presentation
│   │   │       location_screen.dart
│   │   │
│   │   └───widget
│   │           service_location_card.dart
│   │
│   ├───onboarding
│   │   ├───presentation
│   │   │       onboarding_screen.dart
│   │   │
│   │   └───widget
│   │           onboarding_card_widget.dart
│   │           onboarding_footer_widget.dart
│   │           onboarding_header_widget.dart
│   │
│   ├───profile
│   │   ├───presentation
│   │   │       profile_screen.dart
│   │   │
│   │   └───widgets
│   │           profile_header.dart
│   │           profile_login_prompt.dart
│   │           profile_logout_button.dart
│   │           profile_menu_card.dart
│   │           profile_menu_tile.dart
│   │           profile_section_title.dart
│   │
│   ├───service_details
│   │   │   service_details_screen.dart
│   │   │
│   │   ├───cubit
│   │   │       service_details_cubit.dart
│   │   │       service_details_state.dart
│   │   │
│   │   └───widgets
│   │           service_bottom_bar.dart
│   │           service_description_content.dart
│   │           service_details_app_bar.dart
│   │           service_included_content.dart
│   │           service_stats_row.dart
│   │           service_tabs_section.dart
│   │
│   ├───service_listing
│   │   │   service_listing_screen.dart
│   │   │
│   │   ├───cubit
│   │   │       service_listing_cubit.dart
│   │   │       service_listing_state.dart
│   │   │
│   │   └───widgets
│   │           badge.dart
│   │           category_banner.dart
│   │           duration_chip.dart
│   │           empty_services.dart
│   │           filter_chips.dart
│   │           price_section.dart
│   │           rating_chip.dart
│   │           service_list_card.dart
│   │           view_details_button.dart
│   │
│   └───Splash
│       ├───presentation
│       │       splash_screen.dart
│       │
│       └───widgets
│               splash_content_widget.dart
│
├───models
│       booking_confirmation_model.dart
│       booking_history_model.dart
│       booking_model.dart
│       category_item_model.dart
│       category_model.dart
│       how_it_works_step.dart
│       payment_method.dart
│       review_model.dart
│       service_model.dart
│       technician_model.dart
│       user_model.dart
│
└───widgets
        custom_app_bar.dart
        custom_bottom_nav.dart
        custom_button.dart
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
- **LinkedIn**: [Youmna Khaled](https://www.linkedin.com/in/youmna-khaled-869251375?utm_source=share_via&utm_content=profile&utm_medium=member_android)
- **GitHub**: [@Youmnakhaled20](https://github.com/Youmnakhaled20)

---

<p align="center">
  Made with ❤️ by <a href="https://www.linkedin.com/in/ўỗǘṃňã-khaled-869251375?utm_source=share_via&utm_content=profile&utm_medium=member_android">Youmna Khaled Youssef</a>
  <br>
  ⭐ Don't forget to star this repository!
</p>
