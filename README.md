# Instagram Clone (Basic)

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://github.com/VinayNoogler000/Instagram-Clone/blob/main/LICENSE)
[![GitHub issues](https://img.shields.io/github/issues/VinayNoogler000/QR-Code-Generator)](https://github.com/VinayNoogler000/Instagram-Clone/issues)
[![GitHub stars](https://img.shields.io/github/stars/VinayNoogler000/QR-Code-Generator)](https://github.com/VinayNoogler000/Instagram-Clone/stargazers)
[![HTML5](https://img.shields.io/badge/html5-%23E34F26.svg?style=for-the-badge&logo=html5&logoColor=white)](https://github.com/VinayNoogler000/Instagram-Clone/blob/main/src/index.ejs)
[![CSS](https://img.shields.io/badge/css-%231572B6.svg?style=for-the-badge&logo=css3&logoColor=white)](https://github.com/VinayNoogler000/Instagram-Clone/blob/main/public/style.css)
[![JavaScript](https://img.shields.io/badge/javascript-%23323330.svg?style=for-the-badge&logo=javascript&logoColor=%23F7DF1E)](https://github.com/VinayNoogler000/Instagram-Clone/blob/main/index.js)
[![EJS](https://img.shields.io/badge/ejs-%23B6CC6A.svg?style=for-the-badge&logo=ejs&logoColor=brown)](https://github.com/VinayNoogler000/Instagram-Clone/tree/main/views)
[![Node.js](https://img.shields.io/badge/node.js-339933?style=for-the-badge&logo=nodedotjs&logoColor=white)](https://nodejs.org/)
[![Express.js](https://img.shields.io/badge/express.js-%23404d59.svg?style=for-the-badge&logo=express&logoColor=%2361DAFB)](https://expressjs.com/)
[![UUID](https://img.shields.io/badge/uuid-0078D4?style=for-the-badge&logo=uuid&logoColor=white)](https://www.npmjs.com/package/uuid)
[![Multer](https://img.shields.io/badge/multer-%23008080.svg?style=for-the-badge&logo=multer&logoColor=white)](https://www.npmjs.com/package/multer)
[![Method-Override](https://img.shields.io/badge/method--override-%23FF5733.svg?style=for-the-badge&logo=method-override&logoColor=white)](https://www.npmjs.com/package/method-override)

## 📖 Overview

This project is a basic clone of Instagram built to strengthen my backend web development skills, where user have the basic functionalities of uploading photos with a caption (as posts), edit the post's caption, and delete the post. It demonstrates the fundamental concepts of building a web application by using these backend web technologies.

## 🎥 Demo

![Instagram-Clone-Basic](https://github.com/VinayNoogler000/Instagram-Clone/blob/main/Demo.gif?raw=true)

## 🛠 Technologies Used

- **Node.js**: A JavaScript runtime for building server-side applications.
- **Express.js**: A web application framework for Node.js, used to build the server and handle routing.
- **HTML5**: Provides the structure and content of the web page.
- **EJS (Embedded JavaScript)**: A templating engine used to generate HTML markup with plain JavaScript.
- **Vanilla CSS**: For styling the HTML content.
- **UUID**: A library to generate unique identifiers for each post.
- **Method-Override**: A library to use HTTP verbs such as PUT or DELETE in places where the client doesn't support it.
- **Multer**: A middleware for handling `multipart/form-data`, used for uploading files.

## 🚀 Features

- Upload photos with captions.
- View individual posts.
- Edit post captions.
- Delete posts.

## 🛠️ Planned Features

- Confirmation for deleting post.
- Responsive design.
- Storing posts in database. 
- User authentication.
- Share feature for posts.

## 📚 Learnings

1. **Node.js**: Gained an understanding of how to use Node.js to build server-side applications.
2. **Express.js**: Learned how to use Express.js to create a web server and handle routing.
3. **EJS**: Learned how to use EJS as a templating engine to generate dynamic HTML content.
4. **REST Principles**: Acquired knowledge of REST principles for creating RESTful APIs.
5. **CRUD Operations**: Understood the concepts of Create, Read, Update, and Delete (CRUD) operations.
6. **CRUD on Resources**: Learned to perform CRUD operations on resources (data stored in the database) using HTTP verbs and RESTful APIs.
7. **Redirection**: Learned to redirect client requests using `res.redirect()` in route handlers.
8. **Method Override**: Learned to override HTTP GET and POST methods with PUT, PATCH, and DELETE methods using the 'method-override' library.
9. **Route/Path vs API**: Understood the difference between a route/path and an API. A route/path is an endpoint to handle requests, while an API is a set of rules for communication between client and server.
10. **Multer Library**: Learned how to use the 'multer' library for handling file uploads, including specifying the destination and name of the uploaded files, defining the total number of files the client can send with requests or form-data, parsing the image files uploaded as form-data, and handling multiple file uploads of the same field.

## 📋 Prerequisites

Before you begin, ensure you have met the following requirements:
- You have installed the latest version of [Node.js](https://nodejs.org/).
- You have installed the latest version of [Nodemon](https://www.npmjs.com/package/nodemon), for automatically restarting the server on file changes.
- You have a basic understanding of Frontend (JavaScript, HTML, and CSS) and Backend (Node.js, Express.js, EJS, RESTful APIs) technologies.
- You have a code editor like [VS Code](https://code.visualstudio.com/).

## ⚙️ Setup

1. Clone the repository:
    ```bash
    git clone https://github.com/VinayNoogler000/Instagram-Clone.git
    ```

2. Navigate to project directory:
    ```bash
    cd Instagram-Clone
    ``` 

3. Install dependencies:
    ```bash
    npm install
    ```

4. Start the server:
    ```bash
    npm start # only if 'nodemon' library is installed in your system, else
    node index.js
    ```

5. Open your browser and navigate to `http://localhost:8080/posts`.

## 📁 Project Structure

```
project-root/
├── index.js          # Main entry point of the application.
├── views             # Contains EJS templates.
    ├── posts.ejs     # Homepage of the website.
    ├── show.ejs      # Page to see each post, individually.
    ├── edit.ejs      # Page to edit a specific post.
    ├── new.ejs       # Page to upload a new post.
├── public            # Contains static files such as CSS and images.
    ├── uploads       # Stores all the files uploaded by the client.
        ├── images    # Stores all the images of posts uploaded by the client.
    ├── style.css     # Basic styling for the whole website (all webpages).
├── package.json      # Lists the project dependencies and scripts.
├── .gitignore        # Contains all the files and folders to be ignored (not tracked) by Git.
├── README.md         # Project documentation.
└── LICENSE           # Contains the licensing information for the project
```

## 💬 Seeking Feedback & Improvements

I would love to hear your feedback on this project! If you have suggestions for performance improvements or ideas for new features, please feel free to open an issue on the [GitHub repository](https://github.com/VinayNoogler000/Instagram-Clone/issues).

## 🐛 Found a Bug? Have a Feature Suggestion?

If you find a bug or have a feature suggestion, please open an issue [here](https://github.com/VinayNoogler000/Instagram-Clone/issues) with a clear description and steps to reproduce. Your input helps make this project better for everyone.

## 🤝 Contributing

To contribute to this project, follow these steps:

1. Fork the repository.
2. Create a new branch: `git checkout -b feature-branch-name`.
3. Make your changes and commit them: `git commit -m 'Add some feature'`.
4. Push to the branch: `git push origin feature-branch-name`.
5. Submit a pull request.

## 🙏 Acknowledgements

This project was built using the following with the help of following people and technologies:

- [Apna College Institute](https://www.linkedin.com/company/apna-college/posts/?feedView=all) for building such an amazing full-stack web development course.
- [Aman Dhatterwal Bhaiya](https://www.linkedin.com/in/dhattarwalaman/) for Creating an Institute like Apna College.
- [Shradha Khapra Ma'm](https://www.linkedin.com/in/shradha-khapra/) for Teaching and Instructing Programming Fundamentals, Logic Building, Problem-Solving, Critical Thinking, and Web Development/Software Engineering in such a Interesting way.
- [Node.js](https://nodejs.org/)
- [Express.js](https://expressjs.com/)
- [EJS](https://ejs.co/)
- [UUID](https://www.npmjs.com/package/uuid)
- [Multer](https://www.npmjs.com/package/multer)
- [Method-Override](https://www.npmjs.com/package/method-override)
- [HTML5](https://developer.mozilla.org/en-US/docs/Web/Guide/HTML/HTML5)
- [CSS](https://developer.mozilla.org/en-US/docs/Web/CSS)
- [JavaScript](https://developer.mozilla.org/en-US/docs/Web/JavaScript)

## 💼 Careers

I am currently open to the following roles: 

* 💻 Looking for Internships in Web Development Roles (Frontend/Backend/Full-Stack).
* 👨‍💻 Seeking Full-time Software Developer Engineer (SDE) Positions
* 📍 Specialization: Web Development (Frontend, and Full-Stack)

If you are interested in working with me or have any opportunities, please reach out to me via [LinkedIn](https://www.linkedin.com/in/vinay-tambey/), [Email](mailto:vinaytambey000@gmail.com), or other socials mentioned below.

## 📝 To-Do

1. Giving warning to the user when deleting the post.
2. Make the website responsive.
3. Using Database to store user's data.
4. Implementing User Authentication.
5. Adding a Share feature, which will generate a concise link of the posts to share it easily.

## 🗓️ What My Daily Life Looks Like?
As of now (latest version of this README file), I'm building Projects using Web Devlopement technologies to strengthen my fundamentals, in both Frontend & Backend, thriving to become a Full-Stack Web Developer, while learning Backend Web Development. 

This project/website is my 1st self-made Backend project (as the genuine 1st project was Quora clone, made with the help of my teacher).

In Frontend Web Development, currently I'm working on ['FinTrack'](https://github.com/VinayNoogler000/FinTrack) web app, which is my 8th JS project, and more 2 projects are left (means, total 10 projects), to master the fundamentals of JS.

After, that I will be building atleast 3-5 major Projects using React.js framework with Redux.js library, while learning Backend Web Development.

At last, after Completing Frontend Development Projects, and Learning Backend Development, I'll be making atleast 3 Major Full-Stack Projects, using MERN tech-stack. 

## 📜 License

This project is licensed under the [MIT](https://github.com/VinayNoogler000/Instagram-Clone/blob/main/LICENSE) License.

## 📞 Contact Developer & Owner

**Vinay Tambey**
- LinkedIn: [Vinay Tambey](https://www.linkedin.com/in/vinaytambey)
- Email: [Send Email to Vinay](mailto:vinaytambey000@gmail.com)
- Twitter/X: [@VinayNoogler000](https://x.com/VinayNoogler000)
- GitHub: [@VinayNoogler000](https://github.com/VinayNoogler000)

For any queries or suggestions, feel free to reach out through above mentioned links.   

## 📊 Project Status

This project is, currently, not in development by the Owner, but we're always looking to add new features and improvements!

## 💼 Support

Give a ⭐️ if this project helped you!

---

Made with ❤️ by [Vinay Tambey](https://github.com/VinayNoogler000)
