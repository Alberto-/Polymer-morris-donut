# Polymer-morris-donut


A Polymer web component that allows you to create fast and responsive donut charts with the amazing [Morris.js] library.

You only have to specify an address where retrieve the JSON info about the current chart.

**The component will make an API GET call to that specified endpoint to retrieve data.**



## Instructions

Include morris-donut-chart component:


`<link rel="import" href="../morris-donut-chart.html">`


Create a chart  and specify a correct json file or a specific remote endpoint where read info.

`<morris-donut-chart data="demo.json"></morris-donut-chart>`

you can also specify colors passing hex codes into element's attribute 'colors'.
Following an example of Morris donut with Google colors.

`<morris-donut-chart data="demo.json" colors="#4285f4,#ea4335,#fbbc05,#4285f4,#34a853,#ea4335"></morris-donut-chart>`


### How to try it out

Create a simple http server , eg with [http-server]

`http-server -a 127.0.0.1 -p 5000`

and then open the demo page

http://localhost:5000/demo/

![Alt text](https://github.com/Alberto-/morris-donut-component/blob/master/demo/img/MorrisDonutChartColors.png?raw=true "Morris-donut Google colors example")


![Alt text](https://github.com/Alberto-/morris-donut-component/blob/master/demo/img/MorrisdonutChart.png?raw=true "Morris-donut default version example")


## ONLINE DEMO

 Coming soon ...


### Version

1.0

## License

MIT

   [http-server]: <https://github.com/indexzero/http-server>
   [Morris.js]: <https://github.com/morrisjs/morris.js/>
