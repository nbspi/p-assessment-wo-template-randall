# **Practical Assessment**
The Lou Geh Playlist
The the lou geh playlist stores details of a personal music library, and could be used to manage your MP3, CD, or vinyl collection. Because this database is for a personal collection, it’s relatively simple and stores only the relationships between artists, albums, and tracks. It ignores the requirements of many music genres, making it most useful for storing popular music and less useful for storing jazz or classical music.
List of requirements for Lou geh Playlist
-    The collection consists of albums.
-    An album is made by exactly one artist.
-    An artist makes one or more albums.
-    An album contains one or more tracks
-    Artists, albums, and tracks each have a name.
-    Each track is on exactly one album.
-    Each track has a time length, measured in seconds.
-    When a track is played, the date and time the playback began (to the nearest second) should be recorded; this is used for reporting when a track was last played, as well as the number of times music by an artist, from an album, or a track has been played.

Problems:
-	Create Process Flow (Swim lane) of the Current Process (manual process)
-	Create Process Flow (Swim lane) of the Proposed Process (system process)
-	Create Context Diagram
-	Create Dataflow Diagram
-	Create Use-case Diagram
-	Create Hierarchical Chart
-	Design Data Model
-	Create User Interface Design/ Prototype
-	Create Requirement Traceability Matrix(RTM)

## **Task**
1. Create a prototype based on the attached problem
2. Technologies and design to be used are the following:
    * Backend -  PHP
    * Database - MySQL
    * Frontend - Basic HTML, CSS and Javascript
3. As for your application documentations you need to provide the ff:
   1. ERD
   2. DFD
4. Provide a ```README.md``` containing the setup guide.
5. The application should be published in Github via forked repository and for final version of your prototype will create a ```Pull request``` in Github 
6. You will send the Github link to us thru our email devops@biotechfarms.com on or before **23-03-2025** 12:00 PM


    ### **Directory structure**
    ```
    my-app/
    ├── configs                      (Config scripts)
    |   └── db.php
    ├── controllers                      (PHP Controller scripts)
    |   └── UserController.php
    ├── js/
    |   └── app.js                       (Javascript scripts)
    ├── css/
    |   └── style.css                    (CSS scripts)
    ├── index.html                       (Entry point)
    ├── documentation/                   (Documentation files and assessts)
    |   └── UserController.php
    └── README.md                        (Project documentation)
    ```
    ### **Submission format**
    - Repository should show codebase directory directly **DO NOT PUT YOUR CODE BASE IN A ZIP FILE** use git commands instead to push your code-base and further updates.
    - Prototype's latest version should be the default branch of the repository.
    - Provide a READ.ME file on how to install and deploy your prototype, and its prerequisite, software, sdk(if needed), and driver.
