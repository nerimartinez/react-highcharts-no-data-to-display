## Welcome to react-highcharts-no-data-to-display

This is a version of [highcharts-no-data-to-display](https://www.npmjs.com/package/highcharts-no-data-to-display). I was developing and I needed that, but the only way to use it was through require.
So I created this in order to import it :)

### How to use?

1 First you have to install it

```
npm install react-highcharts-no-data-to-display --save
```

2 Then you should import it and initialize it in the file you have the render of react-highcharts

```
import { NoDataToDisplay } from "react-highcharts-no-data-to-display";

NoDataToDisplay ( ReactHighcharts.Highcharts );
```

Just that!

### Customization

In the highcharts configuration:

```
lang:{
  noData: 'no data!' //the text to be displayed
},
noData: {
  position: {
      "x": 0,
      "y": 0,
      "align": "center",
      "verticalAlign": "middle"
      }
}
```

For more information you can contact me :)
