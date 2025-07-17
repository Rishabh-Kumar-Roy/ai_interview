# NextHirePrep

NextHirePrep is a React + TypeScript web application for practicing technical interviews. The app lets you create custom interviews, generates AI-powered questions and records your answers using your webcam and microphone. After the interview, you can review automated feedback.

## Getting Started

1. **Install dependencies**
   ```bash
   npm install
   ```
2. **Run the development server**
   ```bash
   npm run dev
   ```
   The application will be available at `http://localhost:5173` by default.

## Scripts

- `npm run dev` – start the Vite development server.
- `npm run build` – build the production assets.
- `npm run preview` – preview the production build locally.
- `npm run lint` – run ESLint.

## Deployment

1. Build the optimized production assets:
   ```bash
   npm run build
   ```
2. Deploy the contents of the generated `dist/` folder to your preferred static hosting service. For example, you can push it to a GitHub repository and connect that repo to [Vercel](https://vercel.com/) or [Netlify](https://www.netlify.com/).

## Project Structure

Source code lives in the `src/` directory. Major components include:

- `Dashboard.tsx` – manage interview sessions.
- `Interview.tsx` – ask questions and record answers.
- `Feedback.tsx` – display AI-generated feedback.

Configuration files like `vite.config.ts` and `tailwind.config.js` are in the project root.

## License

This project is provided as-is for demonstration purposes.
