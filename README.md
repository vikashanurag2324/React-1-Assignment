# 📝 React + Vite + Bootstrap Todo App

![React 19.1.0](https://img.shields.io/badge/React-19.1.0-61DAFB?logo=react&logoColor=white&style=for-the-badge)
![Vite 7.0.0](https://img.shields.io/badge/Vite-7.0.0-646CFF?logo=vite&logoColor=white&style=for-the-badge)
![Bootstrap 5.3.7](https://img.shields.io/badge/Bootstrap-5.3.7-7952B3?logo=bootstrap&logoColor=white&style=for-the-badge)


### 🚀 Live App
[![Vercel](https://img.shields.io/badge/Deployed%20on-Vercel-black?logo=vercel)](https://to-do-app-madhavp.vercel.app)


## ✨ Features

- 🌓 Dark/Light mode with theme persistence
- 📱 Fully responsive design
- ✍️ Create, edit, and delete tasks
- 🔍 Search tasks by title or category
- 📅 Task scheduling with date and time
- 🖼️ Support for task images (URL or upload)
- 💾 Local storage for data persistence
- 🎯 Category-based task organization
- 🗑️ Bulk delete with confirmation
- 🎨 Smooth animations and transitions

## 🚀 Quick Start

### Prerequisites

Make sure you have Node.js and npm installed:

```bash
node -v
npm -v
```

### Installation

1. Clone the repository:

```bash
git clone https://github.com/Madhav-P-2005/React.Js-ToDo-App.git
cd React.Js-ToDo-App
```

2. Install dependencies:

```bash
npm install
```

3. Start the development server:

```bash
npm run dev
```

## 🛠️ Technologies & Dependencies

### Core Technologies

- **React 19** - UI Library
- **Vite 7** - Build tool and development server
- **Bootstrap 5.3** - CSS Framework

### Additional Dependencies

````json
{
  "@fortawesome/fontawesome-svg-core": "^6.7.2",
  "@fortawesome/free-brands-svg-icons": "^7.0.0",
  "@fortawesome/free-solid-svg-icons": "^6.7.2",
  "@fortawesome/react-fontawesome": "^0.2.2",
  "@popperjs/core": "^2.11.8",
  "flatpickr": "^4.6.13",
  "react-flatpickr": "^4.0.11",
  "sass": "^1.89.2"
}
````

## 📁 Project Structure

```plaintext
To-Do-App/
├── public/
│   └── vite.svg
├── src/
│   ├── components/
│   │   ├── DeleteWarningModal.jsx  # Confirmation dialogs for deletions
│   │   ├── Footer.jsx             # App footer with social links
│   │   ├── Navbar.jsx            # Header with theme toggle
│   │   ├── TaskDelete.jsx       # Delete task functionality
│   │   ├── TaskEdit.jsx        # Task editing form
│   │   ├── TaskGenerate.jsx   # Task creation logic
│   │   ├── TaskLists.jsx     # Task cards display
│   │   ├── TaskModal.jsx    # Task creation/edit modal
│   │   ├── TaskSaveButton.jsx  # Reusable save button
│   │   ├── TaskSearch.jsx     # Search functionality
│   │   └── TaskyModalButton.jsx  # Add/Clear tasks buttons
│   ├── assets/
│   │   ├── react.svg
│   │   └── styles/
│   │       └── main.scss     # Custom SCSS styling
│   ├── App.jsx              # Main app component & state
│   └── main.jsx            # App entry point
├── index.html             # HTML template
├── vite.config.js        # Vite configuration
└── eslint.config.js      # ESLint configuration
```

## ⚛️ React Hooks Used

- **useState**
  - Task list management
  - Dark mode toggle
  - Modal states
  - Form input handling

- **useEffect**
  - LocalStorage persistence
  - Theme synchronization
  - Modal cleanup

- **useRef**
  - Modal focus management
  - Form input references
  - Animation triggers

## 📚 Key Learnings & Implementation Details

### Component Architecture
- Modular component design
- Props and state management
- Parent-child component communication
- Component lifecycle handling

### State Management
- Centralized state in App.jsx
- LocalStorage for data persistence
- State lifting and prop passing
- Event handling patterns

### Advanced Features
- Custom modal implementation
- Dark/Light theme switching
- Responsive design patterns
- Search and filter functionality
- Form validation and handling
- Dynamic UI updates
- Smooth transitions and animations

### Code Organization
- Clean component structure
- Reusable components
- Consistent naming conventions
- Proper event handling
- Performance optimization


## 🤝 Contributing

Feel free to fork this project and customize it for your needs. If you find any bugs or have suggestions, please open an issue.


## 🪪 License

This project is open-source and available under the [MIT License](./LICENSE).


---

Built with 💖 by [Vikash Kumar]
