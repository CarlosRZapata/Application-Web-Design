# Application-Web-Design

---

##  *My data*

1. Carlos Ramiro Zapata de la Cruz
2. Number phone: *9932553344*
3. Semester six
4. My third year of major

## *Subject data*

1. Name: Diseño de paginas web
2. Teacher: José Ricardo Zapata Solis 

**Importance of Markdown**

    Markdown is a lightweight markup language used for formatting text in a simple and easy-to-read manner. It is commonly used in plain text editors for web content. Markdown allows easy application of formatting using special characters. Initially designed for faster web content creation, it can be used for any type of text, regardless of its destination.


# Comands git
---

   - **Check the status of a local repository.**
  
This git exclusive command is useful to be able to see the different types of states in which the files are in the address and work area. To see the committed and uncommitted modifications.

#Comand on terminal:

    git status   

   - **Add individual files or globally.**

To add files or folders to a repository the add command or . command for global will identify the name of the file so it will export it and add it to the workspace.

#Comand on terminal:

    git add "Actividades&T/"

   - **Add comments to the commit.**

When a commit is performed, it can be customized with a short comment to classify what changes were made.

#Comand on terminal:

    git commit -m "I added all my subject files"


   - **Upload your changes to the remote repository.**

It is necessary to download the changes made in the repository to keep the content up to date and the push command is required for this.

#Comand on terminal:

    git push origin main

   - **Create, browse, and delete branches.**

The creation of different branches is useful for team work environments as they help to ensure that the changes made by one teammate are not merged with the others and thus avoid possible modifications and compatibility conflicts. These can be listed, changed to work and deleted if desired.

#Comand on terminal:

    git branch Example


#Comand on terminal:

    git branch -d Example


   - **Roll back a repository to a specific commit.**

One advantage of using git is that it creates a history of the various changes that have been saved and uploaded. With the log command you can see this history so that later with the reset command you can specify the name that was given to the commit to return to that version if necessary.

#Comand on terminal:

    git log

#Comand on terminal:

    git reset commit "WRITE_ID"

