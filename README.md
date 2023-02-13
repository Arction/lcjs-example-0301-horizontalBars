# JavaScript Horizontal Bar Chart

![JavaScript Horizontal Bar Chart](horizontalBars-darkGold.png)

This demo application belongs to the set of examples for LightningChart JS, data visualization library for JavaScript.

LightningChart JS is entirely GPU accelerated and performance optimized charting library for presenting massive amounts of data. It offers an easy way of creating sophisticated and interactive charts and adding them to your website or web application.

The demo can be used as an example or a seed project. Local execution requires the following steps:

-   Make sure that relevant version of [Node.js](https://nodejs.org/en/download/) is installed
-   Open the project folder in a terminal:

          npm install              # fetches dependencies
          npm start                # builds an application and starts the development server

-   The application is available at _http://localhost:8080_ in your browser, webpack-dev-server provides hot reload functionality.


## Description

_Also known as Bar Graph, Column Chart or Column Graph_

Similarly to **_Column Chart or Vertical Bar Chart_**, this example shows the creation of a column chart made on user side by utilizing RectangleSeries, but displays data as horizontal bars. Bar Charts show discrete numerical comparisons across categories, where the value represents the length of a bar.

The following code below shows the creation of a Horizontal Bar Chart using a pre-defined interface. Moreover, the current interface allows visualizing columns with negative values.

The bar series accepts points in format `{ category: string, value: number }`. Any number of points can be added with a single call.

```javascript
// Create Chart.
const chart = barChart()

// Add bars.
chart.addValues([
    { category: 'A', value: 20 },
    { category: 'B', value: -30 },
])
```

The actual Bar Chart logic just serves to provide a starting point for users to create their own API based on their needs and preferences.


## API Links

* [XY cartesian chart]
* [Rectangle series]
* [Solid FillStyle]
* [Empty FillStyle]
* [Solid LineStyle]
* [Empty LineStyle]
* [RGBA color factory]
* [cursor modes]
* [Axis]
* [Scroll strategies]
* [UI position origins]


## Support

If you notice an error in the example code, please open an issue on [GitHub][0] repository of the entire example.

Official [API documentation][1] can be found on [LightningChart][2] website.

If the docs and other materials do not solve your problem as well as implementation help is needed, ask on [StackOverflow][3] (tagged lightningchart).

If you think you found a bug in the LightningChart JavaScript library, please contact support@lightningchart.com.

Direct developer email support can be purchased through a [Support Plan][4] or by contacting sales@lightningchart.com.

[0]: https://github.com/Arction/
[1]: https://lightningchart.com/lightningchart-js-api-documentation/
[2]: https://lightningchart.com
[3]: https://stackoverflow.com/questions/tagged/lightningchart
[4]: https://lightningchart.com/support-services/

© LightningChart Ltd 2009-2022. All rights reserved.


[XY cartesian chart]: https://lightningchart.com/lightningchart-js-api-documentation/v4.0.0/classes/ChartXY.html
[Rectangle series]: https://lightningchart.com/lightningchart-js-api-documentation/v4.0.0/classes/RectangleSeries.html
[Solid FillStyle]: https://lightningchart.com/lightningchart-js-api-documentation/v4.0.0/classes/SolidFill.html
[Empty FillStyle]: https://lightningchart.com/lightningchart-js-api-documentation/v4.0.0/variables/emptyFill-1.html
[Solid LineStyle]: https://lightningchart.com/lightningchart-js-api-documentation/v4.0.0/classes/SolidLine.html
[Empty LineStyle]: https://lightningchart.com/lightningchart-js-api-documentation/v4.0.0/variables/emptyLine.html
[RGBA color factory]: https://lightningchart.com/lightningchart-js-api-documentation/v4.0.0/functions/ColorRGBA.html
[cursor modes]: https://lightningchart.com/lightningchart-js-api-documentation/v4.0.0/enums/AutoCursorModes.html
[Axis]: https://lightningchart.com/lightningchart-js-api-documentation/v4.0.0/classes/Axis.html
[Scroll strategies]: https://lightningchart.com/lightningchart-js-api-documentation/v4.0.0/variables/AxisScrollStrategies.html
[UI position origins]: https://lightningchart.com/lightningchart-js-api-documentation/v4.0.0/variables/UIOrigins.html

