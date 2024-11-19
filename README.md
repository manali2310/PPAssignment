DYNAMIC WEB APPLICATION PROJECT
DESCRIPTION:
This is a dynamic web application built using Angular, HTML, CSS, and Bootstrap. The application includes user authentication via Firebase, API integration for fetching posts, and protected routes. It follows a clean and modular project structure.
LIVE DEMO:
The application is deployed. Visit the live demo here:
[Provide your deployment link]
FEATURES:
- Home Page (`/`): The landing page of the application.
- Sign-Up Page (`/signup`): Allows users to create an account using Firebase Authentication.
- Login Page (`/login`): Allows users to log in using Firebase Authentication.
- Posts Page (`/posts`): A protected route displaying 100 posts fetched from JSONPlaceholder API.
- Post Details Page (`/posts/:postID`): Displays detailed information about a specific post.
STYLING:
Fully responsive design implemented using HTML, CSS, and Bootstrap. Consistent design and color scheme as per the Figma reference.
TECHNOLOGIES USED:
- Angular
- HTML & CSS
- Bootstrap
- Firebase Authentication
- JSONPlaceholder API
PROJECT STRUCTURE:
src/
├── app/
│   ├── components/
│   │   ├── login/          (Login Page Component)
│   │   ├── signup/         (Sign-Up Page Component)
│   │   ├── posts/          (All Posts Page Component)
│   │   ├── post-detail/    (Single Post Details Component)
│   ├── services/           (Reusable Angular Services)
│   ├── app-routing.module.ts (Routing Configuration)
│   ├── app.module.ts       (Root Angular Module)
│   ├── auth.guard.ts       (Route Guard for Authentication)
├── environments/           (Environment Configurations)
├── assets/                 (Static Assets)
├── index.html              (Main HTML File)
├── styles.css              (Global Styles)
├── main.ts                 (Angular Bootstrap File)
SETUP AND INSTALLATION:
- Clone the Repository:
   - `git clone https://github.com/your-username/your-repo-name.git`
   - `cd your-repo-name`
- Install Dependencies:
   - Run `npm install`
- Configure Firebase:
   - Create a Firebase project in the Firebase Console.
   - Enable Email/Password authentication under 'Sign-in Methods.'
   - Add Firebase credentials to `src/environments/environment.ts`:
     ```typescript
     export const environment = {
    production: false,
    firebaseConfig: {
        apiKey: "AIzaSyDQ47RxT6hmJrqC2f81bTSsWiuRYLguXws",
        authDomain: "login-8ed89.firebaseapp.com",
        projectId: "login-8ed89",
        storageBucket: "login-8ed89.firebasestorage.app",
        messagingSenderId: "2568038090",
        appId: "1:2568038090:web:8d51be37de14ef0a583633",
        measurementId: "G-NFG1FEP2PT"
    }
  };
     ```
- Run the Application Locally:
   - Use the command: `ng serve`
   - Open the application in your browser: `http://localhost:4200`
CONTACT:
For questions or issues, reach out to:
- Email: manalighume2310@gmail.com
