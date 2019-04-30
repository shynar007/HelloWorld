This project consists of two parts, a .NET Core 2.2 Web API and a ReactJS web app that displays the message from the Web API, "Hello, world".

## HelloWorld.WebAPI
This is a .NET Core 2.2 Web API - nothing special. Restore all NuGet packages to the solution, F5, and you should be off to the races.

## HelloWorld.WebApi.Tests
A simple test of the HelloWorld controller in the HelloWorld.WebAPI project.

## helloworld.webapp
The React app. `npm start` and all that. If it can read the Web API, it should display "Hello, world" - if it can't, it will read "placeholder"

The project directory contains the standard React bootstrapped ReadMe.md

