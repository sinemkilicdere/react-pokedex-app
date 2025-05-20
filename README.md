README PART UPDATED

How to run it
Clone this repo

git clone https://github.com/sinemkilicdere/react-pokedex-app.git
Go into the project folder

cd react-pokedex-app
Install the dependencies

npm install
Start the app

npm run dev
Open it in browser
Visit http://localhost:5173


What it does
Starts with a default Pokemon ID (0)

When you click the button, it increases the ID by 1

Then it fetches that Pokemon’s data using fetch() and shows the name

Uses useEffect to run the API call whenever the ID changes

react-pokedex-app/
├─ public/
│   └─ …
├─ src/
│   ├─ components/
│   ├─ hooks/         
│   ├─ App.jsx
│   ├─ index.css
│   └─ index.jsx
├─ README.md           
├─ REFLECTION.md       
└─ package.json


src/
├── App.jsx          
├── main.jsx      
├── styles/          
├── components/      
├── hooks/          

Why I made this
This is part of a React + Vite learning lab. The goal was to get more comfortable with using useState, useEffect, and making API calls inside a component.




# 🏙️ React Lab – *Build Your Own Pokédex*  

Pair‑programming‑friendly (1 – 2 students)  
> Master `useEffect`, Promises, & real‑world API data while giving your Pokédex a **NYC‑flavored** vibe.

---

## 📌 Objectives
1. **Spin up** a fresh React app with **Vite**.  
2. **Fetch & display** Pokémon data from the [PokeAPI](https://pokeapi.co/) using `useEffect`.  
3. **Handle** loading and error states with clean Promise logic (`async/await` or `.then/.catch`).  
4. **Design & style** your UI from scratch (JSX + CSS / CSS Modules – no copy‑pasta).  
5. **Reflect** on your process, struggles, and wins in `REFLECTION.md`.

---

## 🔧 Getting Started

```bash
# 1 | Create your project
npm create vite@latest my-pokedex -- --template react
cd my-pokedex
npm install

# 2 | Fire it up
npm run dev
````

> **Push to GitHub now** – commit early & often!

---

## 🚦 Milestones

| ID     | What to build                 | Hints                                                                                           |
| ------ | ----------------------------- | ----------------------------------------------------------------------------------------------- |
| **M0** | Project scaffolding on GitHub |  Keep `src/` tidy (components/, assets/, styles/).                                              |
| **M1** | Pokémon list view             | Fetch `https://pokeapi.co/api/v2/pokemon?limit=151` on mount. Show loading + nice error UI.     |
| **M2** | Detail view                   | Second fetch (`/pokemon/:id`) when a card is clicked. Modal, side‑panel, or route – you decide. |
| **M3** | Custom styling                | Responsive layout, semantic HTML, keyboard‑friendly nav, NYC flair 🍕🗽.                        |
| **M4** | Reflection log                | Answer the questions in **Reflection Prompts** below.                                           |

### Stretch Goals (optional)

* Live **search / filter** by name or type.
* **Pagination / infinite scroll**.
* **Favorites** saved to `localStorage`.
* **React Router** multi‑page flow.
* Global state with **Context API** or Redux.

---

## 📁 File Checklist

```
my-pokedex/
├─ public/
│   └─ …
├─ src/
│   ├─ components/
│   ├─ hooks/           # optional
│   ├─ App.jsx
│   ├─ index.css
│   └─ index.jsx
├─ README.md            # ← you’re here
├─ REFLECTION.md        # ← your write‑up
└─ package.json
```

---

## 📝 Reflection Prompts (put in `REFLECTION.md`)

1. Where did you struggle the most?
2. Step‑by‑step, how did you debug / research the solution?
3. Did you peek at the “last‑resort” sample repo? If yes, **what exactly** did you learn and re‑implement?
4. One improvement you’d tackle with more time.

---

## 🗂 Resources (concept‑only)

* React docs: [`useState`](https://react.dev/reference/react/useState) | [`useEffect`](https://react.dev/reference/react/useEffect) | **Thinking in Effects**
* MDN: [Fetch API](https://developer.mozilla.org/en-US/docs/Web/API/Fetch_API) & [Handling fetch errors](https://developer.mozilla.org/en-US/docs/Web/API/Fetch_API/Using_Fetch#errors)
* Course slide decks:

  * *React Lifecycle & Hooks*
  * *Intro to External API Requests*
  * *Practical Promises*
* PokeAPI docs: [https://pokeapi.co/docs/v2](https://pokeapi.co/docs/v2)

*(Use the sample pens only for inspiration; do **not** copy markup or styles.)*

---

## 📤 Submission

1. **GitHub repo** with complete history.
2. Deployed link (Netlify, Vercel, GH Pages…).
3. `README.md` (this file) updated with screenshots/GIFs.
4. `REFLECTION.md`.

---

## 🏆 Rubric (20 pts)

| Category                    | Pts | Criteria                                                                  |
| --------------------------- | --- | ------------------------------------------------------------------------- |
| Data fetch & error handling |  6  | Correct `useEffect`, robust error UI, no console warnings.                |
| State & props flow          |  4  | Clean architecture, no redundant state, clear prop usage.                 |
| UI/UX & accessibility       |  4  | Responsive design, alt text, keyboard nav works.                          |
| Code quality                |  4  | Lint‑free, meaningful commits, descriptive names, comments where helpful. |
| Reflection                  |  2  | Honest, specific, actionable insights.                                    |

---

### 🗣 “Last‑Resort” Hint Protocol

If stuck **after** pair‑discussion & debugging:

1. Write down the blocker.
2. Skim [https://github.com/hhassan1230/pokemonappttp2025](https://github.com/hhassan1230/pokemonappttp2025) just enough to spark understanding.
3. Close it, implement on your own, document the takeaway in `REFLECTION.md`.

Copy‑pasted code = **zero credit** – keep learning integrity high!

---

Happy hacking & catch ’em all! 🗽⚡️
