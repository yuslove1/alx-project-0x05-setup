# StateCraft: Task 2 - Global State with Context API (alx-project-0x05-setup)

This task expands upon the previous counter app by implementing global state management using React's Context API. It demonstrates how to share state between components without prop drilling, allowing changes in one component to reflect in others.


## Getting Started

1. **Clone the repository:**

```bash
git clone git@github.com:yuslove1/alx-project-0x05-setup.git

```
2. **Install dependencies:**

```bash
cd alx-project-0x05
npm install

```
3. **Run the development seraver:**

```bash
npm run dev

```

Open http://localhost:3000/counter-app in your browser.

## Functionality
The counter app now uses Context API to manage the count state globally. Both the Header and CounterApp components access and update this shared state. Clicking the increment/decrement buttons in CounterApp will update the count displayed in both components simultaneously.

## Key Technologies
**React:** JavaScript library for building user interfaces.
**Context Api:** React API for managing global application state.

## Key Improvements
**Global State Management:** Eliminates prop drilling by providing a central state accessible to all components.
**Synchronized Updates:** Changes to the count are reflected in both Header and CounterApp components.


## Next Steps
This task sets the stage for learning more advanced state management solutions like Redux, which will be covered in subsequent tasks.
