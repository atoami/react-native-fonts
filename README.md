## Available Fonts

- HelveticaNeue-Bold
- HelveticaNeue-Medium
- Lato-Black
- Roboto-Bold
- Roboto-Light
- Roboto-Medium
- Roboto-Regular
- SFProDisplay-Black
- SFProDisplay-Bold
- SFProDisplay-Heavy
- SFProDisplay-Light
- SFProDisplay-Medium
- SFProDisplay-Regular
- SFProDisplay-Semibold
- SFProDisplay-Thin
- SFProDisplay-Ultralight
- SFProText-Bold
- SFProText-Regular
- SFProText-Semibold

## How to use?

##### 1. Add the following lines in your project's package.json.
```javascript
"rnpm": {
    "assets": [
      "app/fonts" // Folder including all font files(otf, ttf, ...)
    ]
}
```

##### 2. Add font files.
Add font files(otf, ttf, ...) in font assets folder.

##### 3. Run the following command.
```shell
react-native link
```
This links all fonts(`app/fonts` in example) to iOS & Android projects.

##### 4. Add font component.
Add font components(`SFProDisplayMedium.js`, ...) in your project.

##### 5. Rebuild the project.
You must rebuild the project after add font files.

##### 6. Now, you can use the fonts anywhere in your project.
```typescript jsx
import { SFProDisplayMedium } from '../SFProDisplayMedium.js';
...
<SFProDisplayMedium style={styles.fontStyle}>
  Text Here
</SFProDisplayMedium>
```

## Demo
You can find demo [here](https://github.com/atoami/react-native-navigation-redux-starter-kit).

Welcome to Pull Request!
