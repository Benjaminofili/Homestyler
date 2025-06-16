# HomeStyler

HomeStyler is a React-based web application for exploring interior design styles, browsing designer galleries, viewing products, and sharing feedback. The project leverages [Create React App](https://github.com/facebook/create-react-app) and integrates Bootstrap for responsive UI components.

## Features

- **Design Style Viewer:** Browse and filter interior design styles by category and trend.
- **Gallery:** Explore a curated gallery of designers and their notable works.
- **Products:** View and review home decor products.
- **Feedback:** Submit feedback directly through a styled form.
- **Philosophy & Mission:** Learn about the design philosophy and mission of HomeStyler.
- **Contact:** Contact form for inquiries.
- **Responsive Design:** Optimized for both desktop and mobile devices.
- **Routing:** Client-side routing with React Router.

## Project Structure

```
src/
  ├── COMPONENT/
  │     ├── About.jsx
  │     ├── Contact.jsx
  │     ├── DesignStyleViewer.jsx
  │     ├── DesignStyleViewer.module.css
  │     ├── Feedback.jsx
  │     ├── Feedback.module.css
  │     ├── Footer.jsx
  │     ├── Footer.module.css
  │     ├── Gallery.jsx
  │     ├── Gallerydata.js
  │     ├── Header.jsx
  │     ├── Mission.jsx
  │     ├── Mission.css
  │     ├── Philosophy.jsx
  │     ├── Philosophy.module.css
  │     ├── Products.jsx
  │     └── SiteMap.jsx
  ├── App.js
  ├── App.css
  └── index.js
public/
  ├── index.html
  └── img/
```

## Getting Started

### Prerequisites

- Node.js (v14 or newer recommended)
- npm

### Installation

1. Clone the repository:
   ```sh
   git clone <your-repo-url>
   cd Homestyler
   ```

2. Install dependencies:
   ```sh
   npm install
   ```

3. Start the development server:
   ```sh
   npm start
   ```
   Open [http://localhost:3000](http://localhost:3000) to view it in your browser.

### Available Scripts

- `npm start` – Runs the app in development mode.
- `npm test` – Launches the test runner.
- `npm run build` – Builds the app for production.
- `npm run eject` – Ejects the app for full configuration control (irreversible).

## Technologies Used

- [React](https://reactjs.org/)
- [React Router](https://reactrouter.com/)
- [Bootstrap 5](https://getbootstrap.com/)
- CSS Modules for component-level styling

## Customization

- **Styling:** Custom styles are in `.module.css` files for each component.
- **Images:** Place your images in `public/img/` and reference them as needed.
- **Fonts:** Uses [Kaushan Script](https://fonts.google.com/specimen/Kaushan+Script) for headings.

## Deployment

To build for production:
```sh
npm run build
```
The optimized build will be in the `build/` folder.

## Learn More

- [Create React App Documentation](https://facebook.github.io/create-react-app/docs/getting-started)
- [React Documentation](https://reactjs.org/)

---

© 2025 HomeStyler.