> ## 🧩 Overview
> MythBuster is a React-based educational web app that lets users explore, review, and add myths or claims, along with verdicts such as TRUE, PLAUSIBLE, BUSTED, or UNKNOWN. It presents each myth with an automated check showing verdict, confidence score, and explanation, using a clean, card-style interface with a simple modal form for adding new entries.
>
> ## ✨ Features
> - View detailed information about a selected myth, including verdict, confidence (in %), and explanation.
> - Add new myths through a modal form with fields for claim, verdict, explanation, and tags.
> - Verdicts are visually distinguished using color-coded badges (green, amber, red, slate).
> - Responsive layout built with utility classes for modern styling.
> - Educational disclaimer clearly stating that the app does not provide medical advice.
>
> ## 🛠 Technologies / Tools Used
> - **React** with functional components and hooks (`useState`, `useEffect`).
> - **JavaScript (ES6+)** for component logic and state updates.
> - **Tailwind CSS–style utility classes** for styling (e.g., `bg-slate-50`, `mt-3`, `rounded`).
> - **Node.js + npm** for dependency management and running the development server.
>
> ## 🚀 Installation & Running the Project
> 1. Clone the repository:  
>    `git clone https://github.com/your-username/mythbuster-react.git`  
>    `cd mythbuster-react`
> 2. Install dependencies:  
>    `npm install`
> 3. Start the development server:  
>    `npm start` (or `npm run dev` if using Vite)
> 4. Open the app in your browser at `http://localhost:3000` (or the port shown in your terminal).
>
> ## ✅ Testing Instructions
> - **Manual testing**
>   - Select an existing myth and verify that the verdict, confidence, and explanation render correctly.
>   - Add a new myth using the modal and confirm it appears in the list with the chosen verdict and tags.
>   - Check that the badge color matches the selected verdict (TRUE, PLAUSIBLE, BUSTED, UNKNOWN).
> - **Automated testing (optional)**
>   - Set up Jest and React Testing Library.
>   - Write tests for:
>     - Rendering of the myth list and detail panel.
>     - Form validation (required fields: claim and explanation).
>     - Correct behavior of the `badgeColor(verdict)` helper.
>
> ## 🖼 Screenshots 
>   `![Myth list view](./screenshots/code1.jpg)`  
>   `![Add myth modal](./screenshots/code2.jpg)`
    `![Add myth modal](./screenshots/code3.jpg)`
    `![Add myth modal](./screenshots/code4.jpg)`
    `![Add myth modal](./screenshots/result.jpg)`# Health-Myth-Buster
