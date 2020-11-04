# dl-skeleton-api
### Props

|Prop|Type|Default|Options|Description|
|---|---|---|---|---|
|width|number, string|6||The is the width of the loader, and can be either a number or string. This property would be overridden if the `size` props is set|
|height|number, string|2||The is the height of the loader, and can be either a number or string. This property would be overridden if the `size` props is set|
|size|number,string|||This is used to give the loader the same width and height. The property would override the width and height previously set|
|type|string|'rect'|rect, circle, error|This is the type of the loader. circle for a circle, rect for rectangle, error for error component window.|
|errorMessage|string|'Please contact the service desk'||Override the default error message|
|animation|string|'wave'|fade, wave, pulse, pulse-x, pulse-y|The animation to be applied to the loader|
|color|string|rgba(0,0,0,0.12)||The sets the color of the loader. It accepts all valid CSS colors (rgb, hsl, hex included)|
|rounded|boolean|false||Add this prop to give a non-circle loader a border-radius 0f 8px|
|radius|number,string|8||This is used to determine the border radius of the loader|
## Project setup
```
npm install
```

### Compiles and hot-reloads for development
```
npm run serve
```

### Compiles and minifies for production
```
npm run build
```

### Lints and fixes files
```
npm run lint
```

### Customize configuration
See [Configuration Reference](https://cli.vuejs.org/config/).
