# Trexy-TimeSpa

# Arquitectura:

Para la arquitectura se utilizarán los siguientes proyectos:

## Proyecto Web API:

- Se utiliza tecnología .NET 8
- Preconfigurado para HTTPS
- Preconfigurado con Open Api (Swagger)

## Proyecto Blazor Web Assembly:

- Se utiliza tecnología .NET 8
- Preconfigurado para HTTPS

## Proyecto Class Library C#:

- Se utiliza tecnología .NET 8

-----------------------------------------

Dónde los proyectos Web API y Blazor Web Assembly tienen referencia de proyecto al Class Library.

# Nugets:

## Trexy.TimeSpa.API:

- Swashbuckle.AspNetCore - Version 6.4.0
- Microsoft.EntityFrameworkCore - Version 8.0.3
- Microsoft.EntityFrameworkCore.SqlServer - Version 8.0.3
- Microsoft.EntityFrameworkCore.Tools - Version 8.0.3
- Microsoft.AspNetCore.Identity.EntityFrameworkCore - Version 8.0.3
- Microsoft.AspNetCore.Authentication.JwtBearer - Version 8.0.3

## Trexy.TimeSpa.Web:

- Microsoft.AspNetCore.Components.WebAssembly -Version 8.0.2
- Microsoft.AspNetCore.Components.WebAssembly.DevServer - Version 8.0.2
- Microsoft.NET.ILLink.Tasks - Version 8.0.2
- Microsoft.NET.Sdk.WebAssembly.Pack - Version 8.0.2
- Microsoft.AspNetCore.Components.WebAssembly.Authentication - Version 8.0.3
- CurrieTechnologies.Razor.SweetAlert2 - Version 5.5.0

## Trexy.TimeSpa.Shared:

- Microsoft.AspNetCore.Identity.EntityFrameworkCore - Version 8.0.3
- Newtonsoft.Json - Version 13.0.3
