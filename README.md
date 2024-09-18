# Practice 1.1 - Installing and configuring Web Development Tools

### 2DAW - DWEC Bilingual. 

> **Student Name**: Ouafae Serroukh Essebaiy  

#### Files included in this repository:

Ennumerate and explain each one of the files included in this repo.

- File 1
- File 2
- Etc...

#### Instructions: 

- Fill your name and lastname and answer the questions in the current `README.md` file. You have to submit the activity as a GitHub repo link that has to include the 

- You can add images to this tocument with the syntax:

    ```md
    ![Text to display](link/to/the/image)
    ```

- Any other question about Markdown language you can find in the [Markdown Cheat Sheet](https://www.markdownguide.org/cheat-sheet/)

### Install and configure VSCode

1. **Install `VSCode` in your computer**.
   ```md
   ![screenshot of my vscode screen](screenshot1.png)
   ```
2. **Create a new folder called `p1.1-frontend-tools`and open it as a workspace in VSCode. Copy the current `README.md` inside it**.
    ```md
   ![screenshot of my workspace](screenshot2.png)
   ```
3. **What functionalities do the following VSCode extensions add?**
   - **Bootstrap 5 quick Snippets:** we use B5 snippets to insert Bootstrap code. Last degree, i was used to type bs5-$ in order to get my html template done instantly
   - **Live Server:** we use it to reload feature for dynamic content 
   - **Prettier:** this extension helps us to automatically format our code on JavaScript
   - **Markdown All in One:** adds shortcuts, lets us create a table of contents easily, formatting elements as headings or urls to plaint text without the use of html tags and more. It is very useful if you want to have your work done fast.

4. **Install the extensions listed in the previous point in VSCode**.
- **Bootstrap 5 quick Snippets:**
  ```md
   ![screenshot of my extension](Screenshot3.png)
   ```
- **Live Server:**
  ```md
   ![screenshot of my extension](Screenshot4.png)
   ```
- **Prettier:**
  ```md
   ![screenshot of my extension](Screenshot5.png)
   ```
- **Markdown All in One:**
  ```md
   ![screenshot of my extension](Screenshot6.png)
   ```
1. **What other extensions do you know that you consider interesting for developing in JavaScript?**
I did not know more JavaScript interesting extensions but i've just did a small research and i found out that IntelliCode is largely used, it's an AI-assistant that can help you while coding, i guess it fills up your lines before you finish them so it seems very useful and time-saving. 

2. **Find in VSCode the option in `Settings` to `Format On Save` and activate it. What effect has this option?**
this option enables auto formatting of the code when you save a file.

### Create a Hello World in JS

7. **Create an `index.html` file inside your workspace folder.**
8. **Create the basic html structure using the `!` snippet and change the title to 'Hello World'**

    ````html
    <!DOCTYPE html>
    <html lang="en">
    <head>
      <meta charset="UTF-8">
      <meta name="viewport" content="width=device-width, initial-scale=1.0">
      <title>Hello World</title>
    </head>
    <body>
      
    </body>
    </html>
    ````

9. **Create a new file called `app.js` and add this two lines**

    ````javascript
    console.log("Hello Console!")
    document.body.innerHTML = "<h1>Hello document!<h1>"
    ````

10. **Import the script in your html using one of the techniques explained in class. Explain here the technique, show the code and justify why did you choose this technique.**
   ```md
   ![screenshot of my extension](Screenshot7.png)
   ```
   I used the script method to import the script in my html. My js file has only two lines of code so we could've included them in the same html file. I used it because it's the technique used in our notes.


11. **Launch `index.html` in Live Server and check that the script is running. Click right button and select inspect to show the developer tools and take a look on the console.**
```md
   ![screenshot](Screenshot8.png.png)
   ```
    
12. **Change some message in the JS code and sava changes. You can check that Live Server refreshes the web page.**
![i changed some text!! ](Screenshot9.png.png)

### Create a simple form with Bootstrap 4. 

13. **At this point, we are going to create a page called `form.html` starting from the `Bs5-$` template provided by the Bootstrap extension we added. What files does this template import in the html by default?**
it uses 3 script tags to import a link each one. The links are the bootstrap data that we recall.
    
14. **Create a `<div>`with the class `.container` to wrap all the sections in the web page**



15. **Add a standard navigation bar inside the nav area using the `bs5-navbar-standard` snippet inside the container**


16. **Inside the main area create a form using Bootstrap to collect data from a new user who wants to register at an academy that offers courses. We can copy code from [Bootstrap Documentation](https://getbootstrap.com/docs/5.0/forms/overview/)**. 


### Install Git, and upload your project to GitHub

17. **Install [git](https://git-scm.com/) in your computer**.


18. **Init the git project**


19. **Log in to your GitHub account provided by IES Azarquiel**


20. **Follow the teacher on GitHub at the following link: [https://github.com/jeatzr/](https://github.com/jeatzr/)**


21. **Create a new empty project on GitHub named `p1.1-frontend-tools`.**


22. **Follow the instructions in the command line provided by GitHub to add your files, create the first commit and push it. Notice that in out case we have to add all files to the staged area with `git add .`, not just`git add README.md`** 


23. **To finish, submit the link of your GH repo to the task in our Classroom.**

