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

  ### NVM - this is a  veconst something = require("./file") → for default/single export

  ### Importing module in React Node files
  const { something } = require("./file") → for named/multiple exportsrsion manager of node
  refer the path - /node.exe type, other paths than this create issue, shouldb e removed

  @@@ data?.response means:
👉 “If data exists (not null or undefined), then access response.
👉 Otherwise, just return undefined instead of throwing an error.”


### Keep Common Js and ES6 separate - =
ES6 = export abc async = ()=>{} delcare and export together
CommonnJs - import - const abs = require(bcabc") export - module.export


### JSON.stringify() and JSON.parse() -
These methods are used tranform data type of data to transfer and store it optimally
JSON.stringify(obj) take a json object and return a string 
JSON.parse(str) is completely opposite of above, converts string of object to json object
note : JSON.parese() return object for Null value even type of Null is object itself - this is historic quirk

### Map
const map = new Map() // declaration, having methods -
map.set(key, value), map.get(key), map.has(key), map.delete()

### response?.data 
checks wheather response is undefined ot not if yes then access data, help to avoid unnecessary erros

### Request and Response methods -
request- 
req.method – "GET" | "POST" | "PUT" | "PATCH" | "DELETE" | ..."
req.path / req.originalUrl – route path vs full URL (good for logging).
req.params – path variables from the route pattern.
Route: /users/:id → req.params.id
req.query – from the URL’s ?key=value (always strings by default).
/users?page=2&limit=20 → req.query.page, req.query.limit
req.body – JSON/form data from the request body (needs parsers).

response- 
res.status(code) – set HTTP status.
res.json(obj) – send JSON (sets Content-Type: application/json).
res.send(body) – send string/Buffer/JSON.

### Socket api - 
socket - call for specific user
io - global call
socekt.emit(apiname, {})
// post request 
socket.on(apiname, (data)=>{...}) // get request

### Git in collaboration -
on start of work get pull for latest code - git pull origin branch_name
check conflict and choose changes according to prefrences and merge
after completing your work push in you branch - 
git add .
git commit -m "message"
get pull origin regular_pull_branch
git push

to check current branch - git status
to change branck - git checkout branch_name


### use ref and use memo hook
useRef - useRef helps to create a variable whose value is set once and stored in  DOM, that remains same across component renders without causing re-renders when the value changes.
useHook - useMemo is a React Hook that allows for the memoization of a value, preventing its recalculation on every render unless its dependencies change.

### AuthN & AuthZ - jwt, cookie, token injection
Cookie Login: You can log in on new browsers by copying session cookies, but the HttpOnly flag often blocks this.
Token Secrets: A JWT's middle part can be decoded to find its expiration time, but not its secret signing key.
Role Forgery: Changing your role from "user" to "admin" in a token will fail because it invalidates the server's signature.
Mass Assignment Flaw: Old or rushed websites might have a bug allowing you to set your own role upon registration.

### Populate method in mongoose
module.find({field1}).populate({field2}) use a field as refrence to replace a that field with data of other modal in that modal


### .includes method in array 
This method helps to check weather a variable holds value that lie in an array
eg. let a = 4 then [2,4,6,8].includes(a) will return true







  


