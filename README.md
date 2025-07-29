Step 1: Create the React app

Open a terminal and run:

npm create vite@latest hello-world-app -- --template react

Then go into the project folder:

cd hello-world-app

⚙️ Step 2: Install dependencies

npm install

🚀 Step 3: Start the development server

npm run dev

Open the browser and go to the link shown in the terminal (usually http://localhost:5173/).


---

✅ 2. Replace Code to Show "Hello World"

Edit src/App.jsx to:

function App() {
  return (
    <div style={{ textAlign: 'center', marginTop: '100px', fontSize: '2rem' }}>
      Hello World
    </div>
  );
}

export default App;

That’s it! 🎉 You should now see "Hello World" in the browser.


---

📦 Alternative: Using Create React App (CRA)

npx create-react-app hello-world-app
cd hello-world-app
npm start

Then edit src/App.js to:

function App() {
  return <h1>Hello World</h1>;
}

export default App;
