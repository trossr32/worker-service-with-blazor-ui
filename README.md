# Worker service with blazor ui and minimal API

Windows/linux service with a blazor UI and minimal API written in .net 6

Exposes an API for interaction with a swagger endpoint.

### Installation

Check out the repository and use the Powershell script to install as a service, e.g.

<code>ExampleApp-Service-AddAndStart -AppWebProjectDir 'C:\Users\Slartibartfast\Github\worker-service-with-blazor-ui\App.Web\App.Web' -DbDir 'C:\Example\App' -LogDir 'C:\Example\App\logs' -RefreshInterval 30</code>

### Dashboard

Find the UI at http://localhost:1337/ when the service is running.

### Swagger

Swagger endpoint is at http://localhost:1337/swagger/, or follow the link in the dashboard UI.
