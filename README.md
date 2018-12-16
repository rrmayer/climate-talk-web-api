# ClimateTalk Web API
Welcome to the project!  This code will ultimately become a series of HTTP (REST) endpoints for communicating with equipment on the ClimateTalk network. 

View the specification for [ClimateTalk here](docs/).

## Contributing
The project is brand-new, and looking for contributors. The following development roadmap is envisioned:

- Create models for ClimateTalk objects
- Create a codec to translate the models to/from the protocol wire
- Create services that operate on the protocl using the codec
- Create web services which abstract the protocol services into something easily consumable by other applications
- If ambitious, develop a client/front-end for setup, testing, and experimentation

None of these items has been accomplished. Work so far has been to define the projects and their contents. Prior to beginning work, you should [open an issue](https://github.com/rrmayer/climate-talk-web-api/issues) where the new addition can be discussed.  Then, create a branch to work the feature, and when done, [submit a pull request](https://github.com/rrmayer/climate-talk-web-api/pulls) with your changes.  These will be integrated to the master branch in an orderly fashion.

## Technology Stack

Development of the code will be done using the [.NET Core 2.2 Framework](https://dotnet.microsoft.com/download/dotnet-core/2.2). This cross-platform framework will run on, and can be developed in, any modern platform (including Windows and Linux). Common development IDEs are [Visual Studio 2017](https://visualstudio.microsoft.com/downloads/) and [Visual Studio Code](https://code.visualstudio.com/), both available free of charge for individual developers and open source products. VS Code will run nicely on Linux, but it is not as full-featured as VS 2017.

## Building and Running

To build, navigate to the `src` directory and type

```dotnet build``` 

at the command line. To run, navigate to `src/WebApi` and type 

```dotnet run``` 

at the command line (PowerShell works well).  Then navigate to http://localhost:5000 (accept browser security warnings).

## For Help

The best option is to [open an issue](https://github.com/rrmayer/climate-talk-web-api/issues).