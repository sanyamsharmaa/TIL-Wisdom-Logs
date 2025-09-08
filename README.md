### This repository is my personal “Today I Learnt” log — a growing collection of insights, lessons, and discoveries I encounter each day. From small sparks of curiosity to deeper breakthroughs, each entry captures a moment of learning and growth. Think of it as a knowledge garden where ideas are planted daily, nurtured over time, and open for others to explore, reflect on, and learn from.


#### 1. Cursor Ai - local AI agent
its is a powerful Ai integrated IDE that allows you to develop anything no matter how complex and big it is, just explain it want you want, more detailed promt -> more classic result. Import a folder, tell him for changes and those changes will automatically reflect in original code until you revert it

### API for sending object to server - 
The data is stored in object called payload and given as argument to handler function along with headers -
const (ishandle, handleSend) = HandlerFunc; // declared at top
// middle code
res = await handleSend(payload, headers);

### Checking of API - after hitting an API we can check it in two ways - 
Devtools - inspect>newtork > clear it using 🚫 icon >  hit api through application > click on newly appeared link > check status code and response

### Explored the most optimised state management library Redux with Redux tool kit (RTK), having following main utilities - 
- Action - An Action is a plain message that describes what happened in your app. It’s like sending a simple note that says, "Please add milk to the shopping list."
- Dispatch - To send that "note" (the action) to the store, you dispatch it. This function is like a mailbox that officially delivers your action to the Redux store.
- Reducer - A Reducer is the special function inside the store that receives the action. It's a rulebook that knows what to do for each action and returns the new, updated information.
- Provider - The Provider wraps your whole app, making the Redux "store" (your app's data) available to every single component, no matter how deeply nested it is.
- createStore - This function creates the actual store, which is like a single, big brain for your application that holds all the important information (called "state").
- createSlice - A slice helps you organize your store by bundling together the logic and actions for a specific feature, like a user's profile or a shopping cart.
- useSelector - This hook lets your components peek into the store and select a specific piece of data to read and display, like getting the current user's name.


