# Manage Expense Full Stack App

A full-stack React Native application to manage your personal expenses. Easily add, edit, and track your spending with a clean and intuitive interface.

## Features
- Add, edit, and delete expenses
- View all expenses or filter by recent
- Summary of expenses
- Responsive and user-friendly UI
- Local state management (context API)

## Screenshots
<!-- Add your screenshots here -->
<!-- ![Screenshot1](assets/screenshot1.png) -->

## Getting Started

### Prerequisites
- Node.js (v14 or above recommended)
- npm or yarn
- Expo CLI (for React Native development)

### Installation
1. **Clone the repository:**
   ```bash
   git clone git@github.com:fhassan99/expense-tracker-react-native.git
   cd expense-tracker-react-native
   ```
2. **Install dependencies:**
   ```bash
   npm install
   # or
   yarn install
   ```
3. **Start the development server:**
   ```bash
   npx expo start
   ```
4. **Run on your device:**
   - Use the Expo Go app on your phone to scan the QR code, or
   - Run on an emulator/simulator

## Folder Structure
```
.
├── App.js
├── assets/
├── components/
│   ├── ExpensesOutput/
│   ├── ManageExpense/
│   └── UI/
├── constants/
├── screens/
├── store/
├── util/
├── package.json
└── ...
```
- **components/**: Reusable UI and feature components
- **screens/**: Main app screens (All Expenses, Recent Expenses, Manage Expense)
- **store/**: Context and state management
- **util/**: Utility functions (date, HTTP, etc.)

## Technologies Used
- React Native
- Expo
- Context API (for state management)
- JavaScript (ES6+)

## Contributing
Contributions are welcome! Please open an issue or submit a pull request for any improvements or bug fixes.

## License
This project is open source. Add your license here if needed. 