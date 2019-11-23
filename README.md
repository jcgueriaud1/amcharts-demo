[![Gitter](https://badges.gitter.im/Join%20Chat.svg)](https://gitter.im/vaadin-flow/Lobby#?utm_source=badge&utm_medium=badge&utm_campaign=pr-badge)

# Demo to integrate AmCharts in a Vaadin project

A simple demo to integrate [https://www.amcharts.com/](https://www.amcharts.com/) in a Vaadin project.
You will need to do some javascript to configure the example graph but you can set the data from the Java side.
The JS files of AmCharts used during the run are from CDN.

To access it directly from github, clone the repository and import the project to the IDE of your choice as a Maven project. You need to have Java 8 or 11 installed.

Run using `mvn jetty:run` and open [http://localhost:8080](http://localhost:8080) in the browser.

If you want to run your app locally in the production mode, run `mvn jetty:run -Pproduction`.
