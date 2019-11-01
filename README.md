# Rails / docker-compose / postgres skeleton.

Here is a skeleton of a base project to start developing rails application into a docker environment.

All you need to do is:

    docker-compose up

After that, your application will be available on localhost:3000

You can run any rails command in web docker container like this:

    docker-compose run web rails g model noga

