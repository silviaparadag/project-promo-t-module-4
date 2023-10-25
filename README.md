
<img width="981" alt="pjw" src="https://github.com/silviaparadag/project-promo-t-module-4/assets/130361802/73637819-bae9-4f77-be7c-2b5ba3ba09c9">

# "Programadoras Junior" An Adalabers portfolio platform

## Summary
We have been asked to create a website to create a digital portfolio of projects for Adalabers developers to present their best projects.

On the website it will be possible to fill in the data form about the author and the project, uploading the image of the project and the user. Once the data form is completed, users will be able to share the project details through a URL, so that the community will have access to the projects created by all Adalabers.

The website, according to the client's request indicated by our Product Owner, consists of two pages, both interactive and with a responsive design based on a mobile first design.

At the same time, all data, both existing and newly created, are stored in a FreeDB database.

## How it works

1. The front-end part is structure 
The objectives were to create a **landing page** that briefly presents the web, and from which there is a button to access the **forms page**, from which you can upload your projects, and on the other hand, a page where you can see all the projects and another where you can see each one in detail.

The three parts of the form page are as follows:
  - Data Form, with all required fields, such as Project Name, Demo Link, Repo Link, User Name, etc.
  - Preview section, to preview in advance the final look and feel.
  - Hero, with a functionality to access all the uploaded projects. For now, as there are no projects uploaded, a warning message has been left, until the backend development team allows to save them all.
With the creation of a digital project file, which as mentioned before, can be shared with a link created with the information filled in.

In addition, if the user can finish completing the form later, the data is saved in the Local Storage, so that she can continue with the fields already filled in.

Both from the Landing page and from the Project creation page, you can access the page where you can view the collection of projects. 
From this page, you can view each project individually.

2.  The back-end part is located in the src folder with its main file "index.js", and static server files. 
For the detail page a template engine has been used, which helps to render the detail page of the projects directly, each time a new project is saved or created. 
In this case, EJS has been used for template creation.

All data is stored in a FreeDB database, which we have worked on connected through MySQL Workbench,

## ⚒️ | Tools

- `HTML`
- `CSS, Saas`
- `JavaScript`
- `React`
- `JSX`
- `EJS`
- `NodeJS`
- `MySQL Workbench`
- `FreeDB`
- `Render`
- `Visual Studio Code`
- `Zeplin`
- `GitHub`
- `GitHub Pages`
- `Agile-Scrum` with GitHub Projects for team organization & coordination *(sprints/dailies/board panel/backlog)*

&nbsp;

## 🎲 | Getting started

1. To start the project, download or fork the repository.

2. To install NPM packages & dependencies, run the following line in your terminal:

~~~
npm install
~~~

3. To be able to view the page in the browser, run:

~~~
npm start
~~~

> **Note** In this project, we can find the following files and folders:
>
>- The folder 📂 `src/` is the files of this web page: HTML, SCSS, JavaScript and images.
>- The folders 📚 `public/` and `docs/`, are generated automatically when we start the project. GULP reads the files found in the src/ folder, processes them and then generates them inside `public/` and `docs/`.
>- Other 📝 files found in the repository root as 'gulpfile.js', 'package.json', etc. are configuration files and we don't need to modify them.
>- To publish on GitHub Pages and generate your page for production run the command: `npm run githubpages`

&nbsp;

## MODULE 3 | 👩🏻‍💻👩🏻‍💻👩🏼‍💻👩🏻‍💻👩🏻‍💻👩🏻‍💻 Team project

&nbsp;
🔸 **Aida Blaya** @Aidablaya

&nbsp;
🔸 **Andrea Ferreiro** @AndreaFerreiro

&nbsp;
🔸 **Silvia Parada** @silviaparadag

&nbsp;
🔸 **Rebeca Serrano** @rebanada

&nbsp;
🔸 **Celia Suarez** @CeliaMSB

&nbsp;
🔸 **Irene Talaver<img width="981" alt="pjw" src="https://github.com/silviaparadag/project-promo-t-module-4/assets/130361802/42e56142-c679-44b9-813a-40cb0f30075e">
o** @IreneTaPa

&nbsp;

This project has been supervised by:

&nbsp;
🔹 **Dayana Romero** @dayanare

&nbsp;
🔹 **Iván Garrido** @igarrido-adalab

&nbsp;
🔹 **Yanelis Serrano** @ytaylordev

© Adalab 2023 | Trótula Promotion
