# Introduction 
This are the initial custom UI for Azure AD B2C pilot implementation. The deployment was completed April 28, 2020.

# Getting Started
The web app is built and compiled using .NET Core template with .NET 3.1 as target framework.
- The main page is v3-default.html
- All pilot Azure AD B2C users flows use the pages with the prefix "v3-"
- All css declarations are embedded in the pages

# Build and Deploy
The web app is deployed in an Azure App Service named b2csandboxui from a GitHub pipeline. There is a pending work to integrate this repo and decouple the GitHub one.

# Contribution
It is important to leave the <div id="api"> as blank. Customizations can be embedded anywhere else.
