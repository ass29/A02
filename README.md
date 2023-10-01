**Part 1: Directions on Using Git, GitHub, and WebStorm**

WebStorm is a popular IDE used by web developers to make web applications. WebStorm supports many frontend technologies and frameworks. Follow these steps to use WebStorm and develop your first web application:

1. To install WebStorm, go to the following URL: [https://www.jetbrains.com/webstorm/download/#section=windows](url)
2. Select which operating system you are using (Windows, macOS, Linux) and download the correct installer for your machine.
3. Complete all the setup steps. 
4. If you do not have an account with **JetBrains**, you need to make one. Go to this link and register for an account: [https://account.jetbrains.com/login](url)
5. Once WebStorm is installed on your machine, you will be prompted for a license key. If you do not wish to purchase a license, you can sign up for a 30-day free trial. Simply select the option that says **Start Trial** and login to your JetBrains account.
6. Once you have activated the 30-day trial, you can now create your first project.
7. To create a project, you can go to file--> new project or if you are on the home screen, you can just click on **New Project**

To integrate your WebStorm project with GitHub follow these steps:

1. On your IDE, there should be a menu called **VCS.** Go to this menu and select **Enable Version Control Integration...**
2. Select which version control system you want this project to use. In this case, select **Git.**
3. To commit files, select which ones you wish to add to Git.
4. Right click the files you wish to commit and select the option that says **Commit.**
5. Type a commit message in the Commit tool window to describe what changes you made.
6. To view your commits, simply go to your GitHub repository associated with your project on GitHub.

**If you are new to using Git and GitHub, follow these steps to get started:**

1. If you do not have an account with GitHub yet, go to this link and register:
   [https://github.com/signup?ref_cta=Sign+up&ref_loc=header+logged+out&ref_page=%2F&source=header-home](url)
   
2. If you do not have Git, go to this link to download Git: [https://git-scm.com/downloads](url)
3. Select your operating system and download the correct installer for your machine.
4. Go through the installation process.
5. After Git is installed, you need to configure your name and email address with Git. Type these commands:

     `git config --global user.name "<YourName>"`
   
     `git config --global user.email "<YourEmail>"`
   
     `git config --global init.default branch main`
   

7. To integrate your project files with Git, simply retrieve the file path your project files are located in.
8. Change your directory in Git by typing


     `cd <YourProjectDirectory>`

   
10. To put this into a repository, type this command:

        git clone
    
   This will create a new repository for your project.

12. Now on Github, you have to create a repository.
13. Go to the option that says **New** and follow the steps for creating a repository on GitHub.
14. If you followed the previous steps, you can also push your existing repository into GitHub instead.
15. To add an existing repository into GitHub, type this command:

         git remote add origin <remoteRepositoryURL>

16. For more information on how to use Git and Github, please refer to this highly informative video on Youtube: [https://www.youtube.com/watch?v=tRZGeaHPoaw&t=1077s](url)
 




**References**

1.[https://www.jetbrains.com/webstorm/download/#section=windows](url)

2. [https://account.jetbrains.com/login](url)
   
3. [https://github.com/signup?ref_cta=Sign+up&ref_loc=header+logged+out&ref_page=%2F&source=header-home](url)
   
4. [https://git-scm.com/downloads](url)
   
5. [https://www.youtube.com/watch?v=tRZGeaHPoaw&t=1077s](url)
   
