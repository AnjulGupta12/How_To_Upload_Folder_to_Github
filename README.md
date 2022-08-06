# How_To_Upload_Folder_to_Github
This repository is for the learning purpose "How to upload Folder to the GitHub". You can't add the whole folder to GitHub but file one by one.  So for that purpose I had created this repository.

<h3>HOW TO ADD FOLDER via GIT BASH</h3>

1. Open Git Bash 
2. git --version
3. open project folder in git bush </br>
  <p>   for eg:- folder path is C\\Users\\Selaniumproject\\Eclipse\\POM_Flipkart_Git   then type this way:</br>
        cd c:</br>
        cd Users</br>
        cd Selaniumproject</br>
        cd Eclipse</br>
        cd Eclipse</br>
        cd POM_Flipkart_Git</p>

4. git init
5. git status</br>
           <p>here it shows some file in red colour it shows thiese files can be uploades
              if not shown then try to delete origin name from here using </br>
                    git remote rm origin</p>
 6. git config --global user.email "anjulgupta1205@gmail.com"
 7. git config --global user.name "AnjulGupta12"</br>
           <p>  name and emailid of git account </p>
 8. git add .
 9. git commit -m "First Commit"
 10. git remote add origin htttp://github.com/Selenium56sen/Jenkin_GitHub_Flipkart.git</br>
    <p>          this is repository link </br>
              this origin word will create problem sometime as i told at 5th as problem to remove this there if it cause prob</p>
 11. git push -u origin master
</br>now refresh your github page
</br>only if till here it is not working go for these two step</br>
12. git config --global http.sslbackend schannel
 13. git push -u origin master

