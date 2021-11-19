# Install

This is **Boockstack Wiki App**. The original repo is [BookStackApp/BookStack](https://github.com/BookStackApp/BookStack). In this version you can deploy your own boockstack with **docker-compose**

For install this app:
 1. Clone this repo
 2. copy *.env.example* to *.env*
 3. fill environment variables with your custom data
 4. execute `docker-compose up -d`
 5. access with **`admin@admin.com`** and password **`password`**
 6. docker compose has mapped port **81:80** you must write `https://your-domain:81`
 7. **Enjoy it**

----

> Original Docker Hub Repo [https://hub.docker.com/r/linuxserver/bookstack](https://hub.docker.com/r/linuxserver/bookstack)
