![chart](https://www.chartjs.org/img/chartjs-logo.svg)

# Chart.js
Chart.js is a free open-source JavaScript library for data visualization, which supports 8 chart types: bar, line, area, pie, bubble, radar, polar, and scatter.

## Installation
* [npm](https://npmjs.com/package/chart.js)
* [GitHub](https://github.com/chartjs/Chart.js/releases/latest)
* [CDN](https://www.jsdelivr.com/package/npm/chart.js)

## Creating a Chart
It's easy to get started with Chart.js. All that's required is the script included in your page along with a single <canvas> node to render the chart.
    
### Example
```
<canvas id="myChart" width="400" height="400"></canvas>
<script>
var ctx = document.getElementById('myChart').getContext('2d');
var myChart = new Chart(ctx, {
    type: 'bar',
    data: {
        labels: ['Red', 'Blue', 'Yellow', 'Green', 'Purple', 'Orange'],
        datasets: [{
            label: '# of Votes',
            data: [12, 19, 3, 5, 2, 3],
            backgroundColor: [
                'rgba(255, 99, 132, 0.2)',
                'rgba(54, 162, 235, 0.2)',
                'rgba(255, 206, 86, 0.2)',
                'rgba(75, 192, 192, 0.2)',
                'rgba(153, 102, 255, 0.2)',
                'rgba(255, 159, 64, 0.2)'
            ],
            borderColor: [
                'rgba(255, 99, 132, 1)',
                'rgba(54, 162, 235, 1)',
                'rgba(255, 206, 86, 1)',
                'rgba(75, 192, 192, 1)',
                'rgba(153, 102, 255, 1)',
                'rgba(255, 159, 64, 1)'
            ],
            borderWidth: 1
        }]
    },
    options: {
        scales: {
            y: {
                beginAtZero: true
            }
        }
    }
});
</script>
```
## License
Chart.js is available under the [MIT license](https://opensource.org/licenses/MIT) .
# Canvas
At first sight a `<canvas>` looks like the` <img>` element, with the only clear difference being that it doesn't have the src and alt attributes.Indeed, the `<canvas>` element has only two attributes, `width` and` height` and These are both optional .
``` 
    <canvas id="tutorial" width="150" height="150"></canvas> 
```
## What is Canvas?
The HTML `<canvas>` element is used to draw graphics, on the fly, via scripting The `<canvas>` element is only a container for graphics. You must use a script to actually draw the graphics.Canvas has several methods for drawing paths, boxes, circles, text, and adding images.

## Helpful resources:
* [Basic usage](https://developer.mozilla.org/en-US/docs/Web/API/Canvas_API/Tutorial/Basic_usage)
* [Drawing shapes with canvas](https://developer.mozilla.org/en-US/docs/Web/API/Canvas_API/Tutorial/Drawing_shapes)
* [Applying styles and colors](https://developer.mozilla.org/en-US/docs/Web/API/Canvas_API/Tutorial/Applying_styles_and_colors)
* [Drawing text](https://developer.mozilla.org/en-US/docs/Web/API/Canvas_API/Tutorial/Drawing_text)
* [chart.js](https://www.chartjs.org/)
