# Project1-Demo

Project1-Demo is a Single Page Application built with:

* **ASP.NET Core 3.1** (Backend API)
* **Angular 8** (Frontend)

The Angular application is hosted inside the ASP.NET Core project using the SPA template.

## Prerequisites

Ensure the following are installed:

* **.NET Core SDK 3.1**
* **Node.js v14.21.3**
* **Angular CLI 8**

Verify installations:

```bash
dotnet --version
node --version
npm --version
ng version
```

## Installation

1. Restore .NET dependencies:

```bash
dotnet restore
```

2. Install frontend dependencies:

```bash
cd Project1-Demo/ClientApp
npm install
```

## Running the Application

From the backend root directory:

```bash
dotnet run
```

In development mode, ASP.NET Core will automatically start the Angular development server.

Default URL:

```
https://localhost:5001
```

## Production Build

Build Angular:

```bash
cd Project1-Demo/ClientApp
npm run build -- --prod
```
