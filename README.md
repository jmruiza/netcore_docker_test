# .Net Core App 

## Without Docker

### Create netcore console test

```
dotnet new webapi --no-https
```

### Run netcore console test

## With Docker

### Build Image

```
docker build -t mymicroservice .
```

### Run netcore console test

```
docker run -it --rm -p 3000:80 --name mymicroservicecontainer mymicroservice
```

The microservice will be available in path http://localhost:3000/WeatherForecast

## References

* [.NET Tutorial - Hello World Microservice](https://dotnet.microsoft.com/learn/aspnet/microservice-tutorial/intro)
* [Using .NET Core in Visual Studio Code](https://code.visualstudio.com/docs/languages/dotnet)