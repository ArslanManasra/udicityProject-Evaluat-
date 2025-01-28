# Evaluate A News Article with Natural Language Processing

4th project in the [Udacity](https://www.udacity.com/course/front-end-web-developer-nanodegree--nd0011) Front-End Web Developer Nanodegree program.

This project focuses on creating a web application that allows users to analyze the sentiment of articles or blog posts from other websites using Natural Language Processing (NLP). Users can input a URL of an article, and the page will display the sentiment analysis results provided by the [MeaningCloud API](https://www.meaningcloud.com/products/sentiment-analysis), based on the article's content.

## Tools and Technologies Used
* HTML
* CSS
* JavaScript
* Node.js
* Express.js
* Webpack
* MeaningCloud API
* Jest
* Workbox

## Steps to Set Up

Ensure that Node.js and npm are installed on your system. Check their versions using:
```
node -v
npm -v
```

### 1. Navigate to the Project Directory
```
cd <project-folder>
```

### 2. Clone the Repository
```
git clone <repository-url>
```

### 3. Install npm Dependencies
```
npm install
```

### 4. Install Necessary Loaders and Plugins
Install the required packages for your chosen development mode:
```
npm i -D @babel/core @babel/preset-env babel-loader
npm i -D style-loader node-sass css-loader sass-loader
npm i -D clean-webpack-plugin
npm i -D html-webpack-plugin
npm i -D mini-css-extract-plugin
npm i -D optimize-css-assets-webpack-plugin terser-webpack-plugin
```

### 5. Obtain an API Key
Sign up for a free API key at [MeaningCloud](https://www.meaningcloud.com/developer/create-account).

### 6. Configure Environment Variables
Use the `dotenv` package to securely store your API key.

1. Install the `dotenv` package:
```
npm install dotenv
```
2. Create a `.env` file in the root directory of the project.
3. Add your API key to the `.env` file:
```
API_KEY=your_api_key_here
```

### 7. Run the Application
Use the following commands to build and run the project:

| Command             | Description              |
|---------------------|--------------------------|
| `npm run build-prod` | Build the project for production |
| `npm start`          | Start the project locally |

### 8. Open the Application
Open your browser and navigate to:
```
http://localhost:8081/
```

