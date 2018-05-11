# docker-aspnet-boilerplate


#### Run development server

You can run development server from command line, from Visual Studio Code or
from a docker-compose system.


##### command line method

```bash
cd src
dotnet restore
dotnet build
dotnet run
# or, if you want to watch for source changes
dotnet watch run
```


##### Visual Studio Code method

Inside Visual Studio Code open

`Debug` > `Start Debugging`


##### docker-compose method

Launch docker-compose system with `docker-compose up`
