docker run --rm --name pg-docker -e POSTGRES_PASSWORD=docker -d -p 5432:5432 -v $HOME/IdeaProjects/codeblog/db:/var/lib/postgresql/data postgres


#Tutorial
https://www.youtube.com/watch?v=c4AvqxnSJT8