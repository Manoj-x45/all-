# 1. Create a New Maven Project
2. Set Up the pom.xml File:
3. Add Dependencies for Selenium and TestNG:
4. Create a Simple Website (HTML, CSS, and
Logo):
5. Upload the Website to GitHub
a.git init
b. git add
c.git commit -m "IniƟal commit"
d. git remote add origin “url”
e.git push -u origin master
6.Modify Maven ConfiguraƟon to Copy StaƟc Files to
your staƟc files ( index.html , style.css , /docs Folder:
First, you need to ensure that Maven places logo.png
) into the /docs folder instead of the target directory.
Deployment
1. Build the Project: mvn clean install
2. Push Changes to GitHub: git add docs/*
git commit -m "Deploy site to GitHub Pages"
3. git push origin master # Or the branch you are
using, maybe 'main' in some cases
4. Enable GitHub Pages:
5. . Access Your Website:
Step 1: Install Gradle :- choco install gradle
Step 2: Verify InstallaƟon:- gradle -v
gradle –version
Step 3: Open IntelliJ IDEA and Create a New Project
1. Click on "New Project".
 2. Select "Gradle" (under Java/Kotlin).
 3. Choose Groovy or Kotlin DSL (Domain Specific Language) for
the build script.
 4. Set the Group ID (e.g., com.example ).
 5. Click Finish.
Step 2: Understanding Project Structure
 1 my-gradle-project
 2 │── build.gradle (Groovy Build Script)
3 │── seƫngs.gradle
4 │── src
5 │ ├── main
 6 │ │ ├── java
 7 │ │ └── resources
8 │ ├── test
 9 │ │ ├── java
10 │ │ └── resources
  Build and Run a Simple Java ApplicaƟon
Step 1: Modify build.gradle (Groovy DSL)
Step 2: Build and Run the Project In IntelliJ IDEA, open the
Gradle tool window (View → Tool Windows → Gradle). Click
Tasks > applicaƟon > run . Or run from terminal:
> gradle run 
