# Google Docs Clone

## Website link:-

https://google-doc-clone.pages.dev/

This project is a frontend clone of Google Docs' single document editor screen using ReactJS. The goal of this project is to replicate the interface and interactions of the document editing view, without implementing the entire functionality of Google Docs.

## Getting Started
To get started with this project, follow the instructions below.

### Prerequisites
You should have the following software installed on your local machine:

Node.js (v12 or higher)
npm (v6 or higher) or yarn (v1.22 or higher)

### Installation
1. Clone this repository to your local machine using the following command:

```
bash


git clone https://github.com/your-username/google-docs-clone.git
```

2. Change to the project directory:

```bash

cd google-docs-clone
```

3. Install the project dependencies:

```bash

npm install
# or
yarn install
```
4. Start the development server:

```bash

npm start
# or
yarn start
```
This will start the development server and open the app in your default browser. If the browser doesn't open automatically, you can visit http://localhost:3000 to view the app.

## Project Structure
The project has the following structure:

```java

├── public
│   ├── index.html
│   └── ...
├── src
│   ├── components
│   │   ├── Editor.js
│   │   ├── Toolbar.js
│   │   └── Sidebar.js
│   ├── App.js
│   ├── index.js
│   └── ...
├── ...
├── .gitignore
├── package.json
└── README.md
```
- The public directory contains the static assets and the index.html file, which is the entry point of the application.
- The src directory contains the main source code of the application.

1.The components directory contains the individual components required for the Google Docs clone.

2.The App.js file is the root component that renders the entire application.

3.The index.js file is the entry point for React and renders the App component.

## Components
### Editor
The Editor component represents the text editor area where the user can edit the document content. It provides functionalities like text formatting, text alignment, and other text-related operations.

### Toolbar
The Toolbar component replicates the Google Docs toolbar. It displays the document name, various formatting options, and the option to share the document.

### Sidebar
The Sidebar component represents the sidebar of the Google Docs interface. It contains links to other Google apps, allowing easy navigation between different applications.

### Contributing
Contributions to this project are welcome. If you find any issues or have suggestions for improvements, please open an issue or submit a pull request.

When contributing to this repository, please follow the existing code style, commit message conventions, and pull request guidelines.


## Acknowledgments
This project is inspired by the Google Docs interface.
Thanks to the ReactJS community for providing an excellent framework for building user interfaces.
