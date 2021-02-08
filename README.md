## Welcome to react-native-cool-components

You can use some cool and animated components for both android and iOS. More components will get updated in future

### Installation

`npm i react-native-cool-components or yarn add react-native-cool-components`

### ButtonSwiper

![ButtonSwiper](/images/buttonSwiper.gif)

### Usage

```JSX import React, { Component } from "react";
import { SafeAreaView } from "react-native";
import { ButtonSwiper } from "react-native-cool-components";
export class App extends Component {
  render() {
    return (
      <SafeAreaView>
        <ButtonSwiper onSwipeComplete={() => alert("Yo I just triggered")} />
      </SafeAreaView>
    );
  }
}

export default App;
```

### Props

| Prop Name            | Type     | Default           | Description                                                 |
| -------------------- | -------- | ----------------- | ----------------------------------------------------------- |
| backContainerStyle   | Style    | null              | back container wrapper style                                |
| placeHolderStyle     | Style    | null              | specify the width of the button within the string or number |
| buttonContainerStyle | Style    | null              | button container wrapper style                              |
| buttonText           | String   | Completed         | button text                                                 |
| placeHolder          | String   | Swipe to complete | placeholder text                                            |
| onSwipeComplete      | Function | null              | function to be triggered after button swiped to the end     |

### BlurredCarousel

![BlurredCarousel](/images/BlurredCarousel.gif)

### Usage

```JSX import React, { Component } from "react";
import { SafeAreaView } from "react-native";
import { BlurredCarousel } from "react-native-cool-components";

const DATA = [
  "https://images.unsplash.com/photo-1612802687608-49884a90c5e0?ixid=MXwxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHw%3D&ixlib=rb-1.2.1&auto=format&fit=crop&w=700&q=80",
  "https://images.unsplash.com/photo-1612801572917-2f5e80c844bc?ixid=MXwxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHw%3D&ixlib=rb-1.2.1&auto=format&fit=crop&w=634&q=80",
  "https://images.unsplash.com/photo-1612799077072-abec2b27a6e8?ixid=MXwxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHw%3D&ixlib=rb-1.2.1&auto=format&fit=crop&w=634&q=80",
  "https://images.unsplash.com/photo-1612780829124-5180ccf69823?ixid=MXwxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHw%3D&ixlib=rb-1.2.1&auto=format&fit=crop&w=634&q=80",
];

export class App extends Component {


  render() {
    return <BlurredCarousel data={DATA} />
  }
}

export default App;
```

### Props

| Prop Name  | Type  | Default | Description                    |
| ---------- | ----- | ------- | ------------------------------ |
| data       | Array | null    | list of images to be displayed |
| imageStyle | Style | null    | image style                    |




<a href="https://www.buymeacoffee.com/devsonuyadav"><img src="https://img.buymeacoffee.com/button-api/?text=Buy me a coffee&emoji=&slug=devsonuyadav&button_colour=FFDD00&font_colour=000000&font_family=Cookie&outline_colour=000000&coffee_colour=ffffff"></a>
