# Checklist Component

## Overview

This project focuses on translating a design mockup from Figma into a fully responsive web layout using HTML and SCSS, without relying on JS/TS. The primary goal is to accurately replicate the visual and interactive elements specified in the Figma design, ensuring pixel-perfect alignment and consistency across different screen sizes and devices.

## Technologies Used

- **SCSS**
- **HTML**

## Getting Started

### Installation

1. Clone the repository:

   ```sh
   git clone git@github.com:marblehands/checklist-component.git
   cd checklist-component
   ```

2. Install the dependencies:

```sh
npm install
```

### Scripts

```sh
npm run dev        # Start the development server
npm run build      # Build the project for production
npm run preview    # Preview the production build
npm run prepare    # Install Husky hooks
npm run format     # Format the source files using Prettier
npm run ci:format  # Check the formatting using Prettier
```

### Git Hooks with Husky

This project uses Husky to manage Git hooks. Husky is configured to run specific tasks to ensure code quality and consistency.
The pre-commit and pre-push hook runs the following tasks:

- Lint-staged: Runs Stylelint and Prettier formatting on staged files.
- Commitlint: Checks the commit message format.
