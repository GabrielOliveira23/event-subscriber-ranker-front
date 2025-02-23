# Event Subscriber Tracker 🚀

This is the front-end build with **Next.js** of a project built with **Node.js**, with the back-end hosted in [server-back](https://github.com/GabrielOliveira23/event-subscriber-tracker-back). The system focuses on **registration and ranking by referral**, where users who sign up receive a unique link to share. Each new registration through this link earns points, allowing users to climb the ranking.

## 🛠️ Technologies Used

- [Next.js](https://nextjs.org/) - React framework for server-side rendering and static site generation.
- [TypeScript](https://www.typescriptlang.org/) - A superset of JavaScript that adds static typing.
- [Tailwind CSS](https://tailwindcss.com/) - Utility-first CSS framework for fast and responsive styling.
- [Orval](https://orval.dev/) - Code generator for OpenAPI specifications, simplifying API integration.

## 📦 Installation

1. Clone the repository:

    ```bash
      git clone https://github.com/GabrielOliveira/event-subscriber-tracker-front.git
    ```

2. Navigate to the project folder:

    ```sh
      cd nome-do-projeto
    ```

3. Install dependencies:
  
   ```sh
   npm install
   # ou
   yarn install
   ```

## 🔥 Como Rodar o Projeto

To start the development server:

```sh
npm run dev
# ou
yarn dev
```

The project will be running at: [localhost - 3000](http://localhost:3000)

## 📁 Folder Structure

```bash
.
├── public/             # static assets
├── src/
|   ├── app/            # Next.js Pages/Routes
│   ├── components/     # Reusable components
│   ├── assets/         # App icons
├── tailwind.config.js  # Tailwind CSS configuration
├── tsconfig.json       # TypeScript configuration
└── next.config.js      # Next.js configuration
```

## 🎨 Styling with Tailwind CSS

Styles are applied using Tailwind utility classes. The `tailwind.config.js` file can be customized as needed.

Example usage:

```tsx
export default function Button() {
  return (
    <button className="bg-blue-500 text-white px-4 py-2 rounded-lg hover:bg-blue-700">
      Click here
    </button>
  );
}
```
