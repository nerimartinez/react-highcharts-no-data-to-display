## Welcome to react-highcharts-no-data-to-display

This is a version of [highcharts-no-data-to-display](https://www.npmjs.com/package/highcharts-no-data-to-display). I was developing and I needed that, but the only way to use it was through require.
So I created this in order to import it :)

### How to use?

- First you have to install it
_npm install react-highcharts-no-data-to-display --save_

- Then you should import it and initialize it in the file you have the render of react-highcharts

_import { NoDataToDisplay } from "react-highcharts-no-data-to-display";

NoDataToDisplay ( ReactHighcharts.Highcharts );_

Just that!

### Customization

In the highcharts configuration:

_lang:{
            noData: 'no data!' //the text to be displayed
          },
          noData: {
                  position: {
                      "x": 0,
                      "y": 0,
                      "align": "center",
                      "verticalAlign": "middle"
                  }
          }_

For more information you can contact me :)
