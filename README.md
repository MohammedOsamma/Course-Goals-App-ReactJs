# React Course Goals App

## Description

A simple React application that allows users to add and manage course goals. Users can add new goals and remove them by clicking on them. The app utilizes React hooks for state management and styled components for styling.

## Features

- Add course goals to the list.
- Remove goals by clicking on them.
- Display a message when no goals are available.
- Uses styled-components for dynamic styling.

## Technologies Used

- React.js
- React Hooks (useState)
- Styled-components for dynamic styling
- CSS Modules for component-specific styling

## Installation & Setup

1. Clone the repository:

   ```bash
   git clone https://github.com/your-username/your-repository.git
   ```

2. Navigate to the project directory:

   ```bash
   cd your-repository
   ```

3. Install dependencies:

   ```bash
   npm install
   ```

4. Start the development server:
   ```bash
   npm start
   ```

## Project Structure

```
/src
│── components
│   ├── CourseGoal
│   │   ├── CourseGoalItem
│   │   ├── CourseGoalList
│   │   ├── CourseInput
│   ├── UI
│       ├── Button
│── App.js
│── index.js
│── styles
```

## Usage

- Enter a goal in the input field and click "Add Goal" to add it to the list.
- Click on a goal to remove it from the list.
- If no goals are available, a message will be displayed.

## Future Enhancements

- Add persistence using local storage.
- Implement animations for better UI experience.
- Add user authentication to save goals for individual users.

## Author

Developed by Mohamed Osama Elkhateeb.
