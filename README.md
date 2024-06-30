<div align="center">
  
  ![GitHub repo size](https://img.shields.io/github/repo-size/abhishekprajapati29/assign-project)
  ![GitHub stars](https://img.shields.io/github/stars/abhishekprajapati29/assign-project?style=social)
  ![GitHub forks](https://img.shields.io/github/forks/abhishekprajapati29/assign-project?style=social)
  [![Maintenance](https://img.shields.io/badge/maintained-yes-green.svg)](https://github.com/abhishekprajapati29/assign-project/commits/main)
  [![Website shields.io](https://img.shields.io/badge/website-up-yellow)](https://assign-project.onrender.com/)
  [![Ask Me Anything !](https://img.shields.io/badge/ask%20me-linkedin-1abc9c.svg)](https://www.linkedin.com/in/abhishekprajapati29/)
  [![License](http://img.shields.io/:license-mit-blue.svg?style=flat-square)](http://badges.mit-license.org)

  <br />
  <br />
  <img src="https://github.com/abhishekprajapati29/Image-text-extraction-project/assets/45328242/9303bd7b-6bbc-4fc3-bbd3-d4907c2162b8" width="500" height="300" />
  <h2 align="center">Extracting Text from Images: A Machine Learning Project using Google Vision API</h2>

  This project leverages the power of Google Cloud Vision API to automate text extraction from images. Here's a deeper dive into the functionalities:

</div>

<br />

## 🔥 Website Preview
https://github.com/abhishekprajapati29/Image-text-extraction-project/assets/45328242/19e813c4-cad7-4633-b098-c2a0af5fb230

## About the feature:

### 1. Text Detection with Optical Character Recognition (OCR):

* Utilizes Google Vision's OCR capabilities to accurately recognize text within images.
* Supports various image formats and handles diverse font styles and orientations.

### 2. Seamless Integration with Python Libraries:

* Employs user-friendly Python libraries to facilitate interaction with the Google Vision API.
* Simplifies the process of sending image data and retrieving extracted text.

### 3. Potential Applications:

* Automating data entry from scanned documents like receipts and invoices.
* Simplifying image caption generation for visually impaired users.
* Building content moderation tools for filtering inappropriate text within images.

## 📋 Key Features
⚡️ **Dashboard**: Get a comprehensive overview of your extract images and counts in one centralized dashboard.\
⚡️ **Drag and Drop**: Effortlessly extract images with simple steps, with easy select and drag and drop feature to select.\
⚡️ **Extract Image**: Quickly extract images text info with just single click and after that view it from there only.\
⚡️ **Profile**: Organize and access user informated are provided on the user .\
⚡️ **Login and Logout**: login and logout functionality for security and isolated work.

## 💡 Tech Stack
* **MongoDB** ([https://www.mongodb.com/](https://www.mongodb.com/)): A NoSQL database that provides high performance, high availability, and easy scalability.
* **Flask** ([https://expressjs.com/](https://expressjs.com/)): A fast, unopinionated, minimalist web framework for Node.js, providing a robust set of features.
* **React** ([https://react.dev/](https://react.dev/)): A JavaScript library for building user interfaces, enabling the creation of dynamic and interactive web applications.
* **Node.js** ([https://nodejs.org/en/download/package-manager](https://nodejs.org/en/download/package-manager)): A JavaScript runtime environment built on Chrome's V8 JavaScript engine, facilitating server-side development.
- And more...


## 🌐 NPM Package
### Frontend

| Package Name | Version | Description |
|---|---|---|
| React | ^18.3.1 | A JavaScript library for building user interfaces. |
| Material-UI | ^5.15.21 | A popular React UI framework implementing Material Design. |
| Axios | ^1.7.2 | A promise-based HTTP client for the browser and Node.js. |
| Styled Components | ^6.1.11 | A CSS-in-JS library for styling React components. |
| Chart.js | ^4.4.3 | A flexible JavaScript charting library. |
| React Table | ^7.8.0 | A lightweight, fast, and extendable data grid for React. |
| Web Vitals | ^2.1.4 | A library for measuring web performance metrics. |
| Testing Libraries (Jest and Testing Library) | Various | Libraries for testing JavaScript and React applications. |
| @emotion/react | ^11.11.4 | A CSS-in-JS library for styling React components. |


## 🛠️ Prerequisites
Before you begin, ensure you have met the following requirements:

- [Git](https://git-scm.com/downloads "Download Git") must be installed on your operating system.
- npm (comes with Node.js) or yarn (Recommended: [Yarn](https://yarnpkg.com/))

## ⭐ Environment Variables
To run the project locally, you need to set up the following environment variables. Create a `.env` file in the root of your project and add the following:

### Frontend ENV

```env
REACT_APP_BACKEND_URL=[http://127/](http://127.0.0.1:5000)
```

### Backend ENV

```env
SECRET_KEY=<secret-key>
GOOGLE_APPLICATION_CREDENTIALS=<imageextract.json>
```


## 📦 Installation
1. **Clone the repository:**

   ```bash
   git clone https://github.com/abhishekprajapati29/Image-text-extraction-project.git
   ```
   
2. **Navigate to the project directory:**

   ```bash
   cd Image-text-extraction-project
   ```
   
3. **Navigate to the frontend project directory:**

   ```bash
   cd client
   ```
   
4. **Install dependencies:**

   ```bash
   npm install   # or yarn install
   ```
   
5. **Start the development server:**

   ```bash
   npm start     # or yarn start
   ```
   
6. **Navigate to the backend project directory:**
   ```bash
   cd client
   ```
  
7. **Install dependencies:**

   ```bash
   pip install -r requirements.txt
   ```
   
8. **Start the development server:**

   ```bash
   flask run
   ```


## 📜 Routes for Frontend

The `routes` array contains configurations for different routes in the application. Each route object has the following properties:

- `type`: Describes the type of route (collapse, title, divider).
- `name`: Name of the route or title.
- `key`: Unique key for the route.
- `icon`: Material-UI icon component.
- `isAuth`: Boolean indicating whether authentication is required.
- `route`: The route location for React Router.
- `href`: External link location.
- `title`: Title text for the Sidenav.
- `component`: React component associated with the route.


## ✨ Components

- Various components used throughout the application.

## 🧪 How to Add a New Route

To add a new route, follow the existing routes in the `routes` array. Use the provided keys like `type`, `name`, `key`, `icon`, etc. Make sure to specify the `component` property with the associated React component.

Feel free to adjust the project structure based on specific requirements.


## 🚶 Contributing

Feel free to contribute to this project! Whether it's reporting bugs, suggesting enhancements, or adding new features, your contributions are welcome. Please follow the [contribution guidelines](CONTRIBUTING.md).

### 📝 License

This project is licensed under the [MIT License](LICENSE).

---

Thank you for visiting my portfolio! If you have any questions or suggestions, feel free to reach out.

