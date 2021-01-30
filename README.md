## Welcome to react-native-cool-components 

You can use some cool and animated components for both android and iOS. More components will get updated in future


### Installation

```npm i react-native-cool-components or yarn add react-native-cool-components```

### ButtonSwiper

![ButtonSwiper](/images/buttonSwiper.gif)


### Usage

```JSX import React, { Component } from "react";
import { SafeAreaView} from "react-native";
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



| Prop Name    | Type             | Default                                    | Description                                                 |
| ------------ | ---------------- | ------------------------------------------ | ----------------------------------------------------------- |
| backContainerStyle | Style      | null                                       | back container wrapper style                                |
| placeHolderStyle        | Style | null                                       | specify the width of the button within the string or number |
| buttonContainerStyle | Style    | null                                       | button container wrapper style                              |
| buttonText       | String       | Completed                                  | button text                                                 |
| placeHolder  | String           | Swipe to complete                          | placeholder text                                            |
| onSwipeComplete  | Function     | null                                       | function to be triggered  after button swiped to the end    |


<a href="https://www.buymeacoffee.com/devsonuyadav"><img src="https://img.buymeacoffee.com/button-api/?text=Buy me a coffee&emoji=&slug=devsonuyadav&button_colour=FFDD00&font_colour=000000&font_family=Cookie&outline_colour=000000&coffee_colour=ffffff"></a>




