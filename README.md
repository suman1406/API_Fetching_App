# 📱 Flutter API Fetching Application

This Flutter application demonstrates API integration, data fetching, error handling, and responsive UI rendering using ListView. It is developed as part of the **Flutter Developer Assignment** for Zylentrix.

---

## 🚀 Features

- ✅ Fetches data from a **public REST API**: [JSONPlaceholder Posts API](https://jsonplaceholder.typicode.com/posts)
- ✅ Displays post **titles** in a scrollable, responsive `ListView`
- ✅ Shows a **loading indicator (CircularProgressIndicator)** while fetching data
- ✅ Gracefully handles **API failures and displays error messages**
- ✅ **Dark Mode & Light Mode Toggle** included
- ✅ Beautiful and **modern UI with gradients and Google Fonts**
- ✅ Clean, modular, and well-documented code

---

## 📂 Project Structure

```
lib/
├── models/
│   └── post_model.dart
├── services/
│   └── api_service.dart
├── screens/
│   ├── home_screen.dart
│   └── post_detail_screen.dart
├── widgets/
│   └── post_card.dart
└── main.dart
```

---

## 🧑‍💻 Technologies & Packages Used

| Package               | Purpose                        |
|-----------------------|--------------------------------|
| `http`                | Fetching data from API         |
| `google_fonts`        | Typography enhancement         |
| `flutter/material.dart` | UI rendering                 |

---

## 📦 Getting Started

### 🔧 Project Setup Instructions

1. **Clone the Repository** or **Download ZIP**
   ```
   git clone https://github.com/your-username/flutter-api-fetching-app.git
   cd flutter-api-fetching-app
   ```

2. **Install Dependencies**
   ```
   flutter pub get
   ```

3. **Run the App**
   ```
   flutter run
   ```

---

## 📌 Assumptions & Enhancements

- Only **Post Titles** are shown on the home screen as per assignment requirements.
- **Dark Mode Toggle & Detail View Navigation** are **additional enhancements** to improve user experience.
- Used **Material 3 design system** for a modern and sleek UI.

---

## ⚠️ Error Handling

- If API fails or network issues occur, a **clear error message is displayed to the user** instead of crashing the app.
- Handled using try-catch blocks and `FutureBuilder` error state.

---

## 📃 Assignment Objective Checklist

| Requirement                                      | Status |
|--------------------------------------------------|--------|
| API Integration with HTTP                        | ✅     |
| Data display in ListView                         | ✅     |
| Loading Indicator                                | ✅     |
| Error Handling                                   | ✅     |
| Clean, Modular Code                              | ✅     |
| README Documentation                             | ✅     |
| Additional Enhancements (Dark Mode, Detail View) | ✅     |

---

## 📎 Submission Instructions

- Upload the project as **GitHub Repository or ZIP file**
- Fill in the **Google Form Submission Link** shared by the company
- Ensure README.md and code documentation are included

---

## 👨‍💻 Developer Info

**Name:** Suman Panigrahi  
**Email:** psuman7155@gmail.com