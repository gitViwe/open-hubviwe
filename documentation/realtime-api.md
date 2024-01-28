<!-- PROJECT LOGO -->
<br />
<div align="center">
  <a href="https://github.com/gitViwe/the-base">
    <img src="../images/Logo.svg" alt="Logo" width="160" height="90">
  </a>

<h3 align="center">The Base Project</h3>

  <p align="center">
    A look at the Realtime API
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

You can access the swagger documentation through the gateway API, just select the definition `Realtime API` from the drop-down and fire a request.
* [Swagger endpoint](http://localhost:5128/swagger)

### Traces

You can access the traces through the Jaeger UI.
* [Jaeger UI endpoint](http://localhost:16686/)

### Logs

You can access the logs through the Seq UI.
* [Seq UI endpoint](http://localhost:81/)

### Metrics

So... the Prometheus metrics store is set up and a single Grafana dashgboard. You can view the dashboard by logingin with the following credentials: `username: admin | password: admin`
* [Grafana endpoint](http://localhost:3000/)


<!-- MARKDOWN LINKS & IMAGES -->
<!-- https://www.markdownguide.org/basic-syntax/#reference-style-links -->

[auth-api-diagram-screenshot]: ../images/realtime-api-diagram.svg
