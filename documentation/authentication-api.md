<!-- PROJECT LOGO -->
<br />
<div align="center">
  <a href="https://github.com/gitViwe/the-base">
    <img src="../images/Logo.svg" alt="Logo" width="160" height="90">
  </a>

<h3 align="center">The Base Project</h3>

  <p align="center">
    A look at the Authentication API
    <br />
    <a href="../README.md"><strong>Back to README »</strong></a>
  </p>
</div>

---
<!-- ABOUT THE API -->

![Product Name Screen Shot][auth-api-diagram-screenshot]

<!-- GETTING STARTED -->
## Getting Started

Once you have the local docker environment up and running, follow these simple steps to start playing.

### Swagger

You can access the swagger documentation through the gateway API, just select the definition `Athentication API` from the drop-down and fire a request.
* [Swagger endpoint](http://localhost:5128/swagger/index.html?urls.primaryName=Authentication%20API)
![Swagger Screen Shot][auth-api-swagger-screenshot]

### Traces

You can access the traces through the Jaeger UI and explore how the services communicate.
* [Jaeger UI endpoint](http://localhost:16686/)
* ---
![Jaeger Screen Shot][auth-api-jaeger-screenshot]

### Logs

You can access the logs through the Seq UI.
* [Seq UI endpoint](http://localhost:81/)

### Metrics

So... the Prometheus metrics store is set up and a single Grafana dashgboard. You can view the dashboard by logingin with the following credentials: `username: admin | password: admin`
* [Grafana dashboard endpoint](http://localhost:3000/d/KdDACDp4z/asp-net-core)
![grafana-screenshot][grafana-screenshot]


<!-- MARKDOWN LINKS & IMAGES -->
<!-- https://www.markdownguide.org/basic-syntax/#reference-style-links -->

[auth-api-diagram-screenshot]: ../images/authentication/auth-api-diagram.svg
[auth-api-swagger-screenshot]: ../images/authentication/auth-api-swagger.png
[auth-api-jaeger-screenshot]: ../images/authentication/auth-api-jaeger.png
[grafana-screenshot]: ../images/grafana.png
