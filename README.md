# React Step-by-Step Guide

This project is a simple React application that provides an interactive step-by-step guide. It demonstrates the use of React's core features, including state management with the `useState` hook, conditional rendering, and reusable components.

## Features

- **Dynamic Step Navigation**: Users can navigate through three steps using "Previous" and "Next" buttons.
- **State Management with `useState`**: The app uses the `useState` hook to manage the current step and the visibility of the guide.
- **Conditional Rendering**: The guide is displayed or hidden based on the state, allowing for a dynamic user experience.
- **Reusable Button Component**: A customizable `Button` component is used for navigation, showcasing component reusability.
- **Dynamic Styling**: Active steps are visually highlighted using conditional class names.

## How It Works

1. **State Management**:

   - The `step` state tracks the current step (1, 2, or 3) and updates dynamically when users navigate between steps.
   - The `isOpen` state controls the visibility of the guide, toggled by a close button.

2. **Step Navigation**:

   - Users can move to the next or previous step using buttons. Navigation is restricted to valid steps (1 to 3).

3. **Dynamic Styling**:

   - The current step is visually highlighted using conditional class names, providing a clear indication of progress.

4. **Reusable Components**:
   - The `Button` component is designed to be reusable, with customizable styles and behavior.

## Getting Started

### Prerequisites

Ensure you have the following installed:

- Node.js (v14 or later)
- npm (v6 or later)

### Installation

1. Clone the repository:

   git clone <repository-url>
   cd <repository-folder>

2. Install dependencies:

   npm install

### Running the App

Start the development server:

npm start

Open [http://localhost:3000](http://localhost:3000) in your browser to view the app.

### Building for Production

To create a production build:

npm run build

The build will be available in the `build/` folder.

## Learn More

To learn more about React, visit the [React documentation](https://reactjs.org/).

## License

This project is licensed under the MIT License. Feel free to use and modify it as needed.
