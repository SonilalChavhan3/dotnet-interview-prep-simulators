 ASP.NET Core MVC State Management Simulator
A single-file, interactive HTML learning tool for understanding state management in ASP.NET Core MVC. No installation, no backend, no dependencies — just open and learn.

📋 Overview
This simulator helps beginners, intermediate learners, and interview candidates visually understand how state is stored, transferred, and secured in an ASP.NET Core MVC application. It covers client-side, server-side, and request-scoped state techniques with interactive simulators, code examples, quizzes, flashcards, and interview preparation material.

Target audience:

Beginners learning ASP.NET Core MVC

Developers preparing for .NET interviews

Trainers/mentors teaching state management

Anyone who wants a quick visual reference

🚀 How to Use
Step 1 — Get the file
Save the provided index.html file to any folder on your computer.

Step 2 — Open in a browser
Double-click index.html, or right-click → Open with → any modern browser:

✅ Google Chrome

✅ Microsoft Edge

✅ Mozilla Firefox

✅ Safari

No web server, no Node.js, no build step, no internet connection required.

Step 3 — Start learning
Use the sticky sidebar on the left to jump to any section. Everything is interactive — click, hover, and explore.

🧭 What's Inside (Sections)
#	Section	Purpose
1	Overview	Architecture diagram: Browser → Request → Server → Controller → View → Response
2	Three Categories	Request/MVC View State, Client-Side State, Server-Side/Persistent State
3	Request Lifecycle	Clickable stages: Browser → Routing → Model Binding → Controller → View → Response
4	State Simulator	Choose a technique, see where it's stored, step through the flow
5	Redirect Simulator	Why TempData survives redirects but ViewData/ViewBag do not
6	Cookie + Session	Visual diagram: Browser (Session ID) → Server (Session Store)
7	Multi-Server	Single vs. Multi-server architecture tabs
8	Security	Inspect/Modify/Trust matrix + cookie options (HttpOnly, Secure, SameSite)
9	Comparison Table	Searchable/filterable table of all techniques
10	Real-World Scenarios	Practical use cases with recommended solutions
11–13	Interview Questions	Beginner (15), Intermediate (15), Advanced (15) with expandable answers
14	Rapid-Fire Mode	Quick Q&A with "I Know" / "Need Revision" tracking
15	Quiz	20 multiple-choice questions with instant feedback and scoring
16	Anki Flashcards	41 flashcards — navigate, shuffle, reset, and export to CSV
17	Cheat Sheet	One-line summary of every technique
18	Complete Code Examples	Full ASP.NET Core MVC code for every technique (Program.cs, Controller, Razor, JavaScript)
19	Anti-Patterns	What NOT to do with state
20	Decision Tree	Interactive questionnaire that recommends a technique
🎯 Key Features
🧪 Interactive State Simulator
Select any of 14 state techniques from the dropdown

Instantly see where the state is stored (Browser / Server / Database / Request)

View a working code example for that technique

Run the complete request flow step-by-step with the "▶ Run Complete Flow" button

Toggle Beginner Mode for simple analogies (e.g., "Session is like a locker on the server")

📚 Complete Code Examples
Every technique includes:

Program.cs configuration (when required)

Controller code

Razor view (.cshtml)

JavaScript (when applicable)

Data flow diagram

Explanation, use case, security notes, and interview tip

A "⚡ Simulate Flow" button showing the animated sequence

🧠 Interview Preparation
45+ interview questions across Beginner / Intermediate / Advanced

Rapid-Fire mode with self-assessment tracking

20-question quiz with instant correct/incorrect feedback and score

Cheat Sheet for last-minute revision

📇 Anki Flashcards
41 flashcards covering all state techniques

Show Answer, Next, Previous, Shuffle, Reset

Export to Anki CSV — one click downloads anki_flashcards.csv ready to import into Anki

🌗 Theme & Print
Dark / Light mode toggle

Revision Mode — hides animations and diagrams, shows concise notes only

Print Notes — clean print layout (CSS @media print) for physical revision

🔧 All 14 State Techniques Covered
A. Request / MVC View State
ViewData

ViewBag

TempData

ModelState

B. Client-Side State
Cookies

Query String

Hidden Fields

LocalStorage

SessionStorage

C. Server-Side / Persistent State
Session

IMemoryCache

Distributed Cache

Database (EF Core)

Claims / User Identity

💡 Suggested Learning Path
For beginners:

Start with Overview and Three Categories

Walk through the Request Lifecycle (click each stage)

Try the State Simulator with ViewData → Cookie → Session

Open Complete Code Examples → read ViewData, ViewBag, TempData

Take the Quiz (don't worry about score — learn from feedback)

Review the Cheat Sheet

For interview prep:

Read Comparison Table + Cheat Sheet

Expand all Beginner → Intermediate → Advanced questions

Use Rapid-Fire Mode to test recall

Do the 20-question Quiz — aim for 18+/20

Export Anki flashcards and review daily

Revisit Security and Multi-Server sections for senior-level questions
