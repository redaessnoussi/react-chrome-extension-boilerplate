# React Chrome Extension Boilerplate

This repository contains a boilerplate for creating a Chrome extension using React. It's designed to help you get started quickly with a modern development setup, including TypeScript, Webpack, and Tailwind CSS.

## Features

- **React**: For building the UI of your extension.
- **TypeScript**: For static typing and enhanced developer experience.
- **Webpack**: For bundling your extension's assets.
- **Tailwind CSS**: For styling your extension's UI.
- **PostCSS**: For transforming CSS with JavaScript.
- **Autoprefixer**: For adding vendor prefixes to CSS.
- **Hot Reloading**: For a better development experience.

## Getting Started

### Prerequisites

- Node.js (>= 14.0.0)
- npm (>= 6.0.0)

### Installation

1. Clone the repository:

git clone https://github.com/redaessnoussi/react-chrome-extension-boilerplate.git

2. Navigate to the project directory:

cd react-chrome-extension-boilerplate

3. Install the dependencies:

npm install

### Development

To start the development server and watch for changes:

npm run watch

This will start Webpack in watch mode, recompiling your assets whenever you make changes.

### Building

To build your extension for production:

npm run build

This will create a `dist` directory with your compiled extension.

### Loading the Extension into Chrome

1. Open Chrome and navigate to `chrome://extensions`.
2. Enable "Developer mode" by toggling the switch in the top right corner.
3. Click "Load unpacked" and select the `dist` directory.

Your extension should now be loaded into Chrome and ready to use.

## Contributing

Contributions are welcome! Please feel free to submit a pull request or open an issue if you find any bugs or have suggestions for improvements.
