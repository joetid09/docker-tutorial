<header>Docker Setup and Tutorial</header>

<body>
<div classname="about">
    <h3>What is it?</h3>
    <p>This repo was created for the Docker Tutorial which can be found <a href="https://docs.docker.com/get-started/">HERE</a></p>
    <br>
    <h3>Why?</h3>
    <p>In <a href="https://github.com/joetid09/WorthATri">this project repository</a> the application will be containerized, with a PostgrSQL database and Joplin server.
        this Tutorial has been walking me through how to use docker in general as well as setting up a network between multiple containers application and database containers.</p>
    <div>
    <ol>
        <lh>12/15/2021</lh>
        <li>created a network to host two separate containers</li>
        <li>Mounted application to an external .sqlite db</li>
        <li>Created named volumes</li>
    </ol>
    <ol>
        <lh>12/16/2021</lh>
        <li>Create mysql container</li>
        <li>used the new network to connect app to new container</li>
        <li>persisted dated that was created from the app into the mysql database!</li>
        <li>Created Docker-Compose file and had it create a docker app for the db and the application</li>
    </ol>
    </div>
</div>
</body>
