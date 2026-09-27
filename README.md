# Gold Project

Gold Project is a web app for tracking gold prices. It shows current gold prices, price history, and includes a calculator to help estimate gold value. It's built with **Angular 22** and styled using **Tailwind CSS**.

## Prerequisites

Before you start, make sure you have the following installed:

- [Node.js](https://nodejs.org/) (includes npm)
- npm (comes with Node.js)
- Angular CLI — install it globally with:

  ```bash
  npm install -g @angular/cli
  ```

## Getting Started

### 1. Install dependencies

```bash
npm install
```

### 2. Run the project

```bash
ng serve
```

### 3. Open the app

Once the server is running, open your browser and go to:

```
http://localhost:4200
```

The app will automatically reload whenever you edit a source file.

## Creating a New Component

To generate a new component, run:

```bash
ng generate component component-name
```

This creates a new folder with the component's files inside `src/app/components`.

## Building the Project

To build the app for production:

```bash
ng build
```

The compiled output will be placed in the `dist/` folder.

## Project Structure

Here's a quick overview of the main folders inside `src/app`:

| Folder | Purpose |
| --- | --- |
| `components/` | UI components (e.g. gold price card, calculator, chart, header) |
| `services/` | Handles data fetching and business logic (e.g. `gold.service.ts`) |
| `models/` | TypeScript interfaces/types describing data shapes (e.g. `gold.model.ts`) |
| `data/` | Static or mock data used by the app (e.g. `gold-data.ts`) |

Each component folder typically contains an `.html` (template), `.css` (styles), `.ts` (logic), and `.spec.ts` (tests) file.

## Troubleshooting

**`npm install` fails**

- Make sure you're using a supported Node.js version.
- Delete `node_modules` and `package-lock.json`, then run `npm install` again.

**`ng serve` doesn't start**

- Make sure Angular CLI is installed (`ng version` to check).
- Check that port `4200` isn't already in use by another process.
- Try restarting your terminal and running `ng serve` again.
