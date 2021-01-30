## Welcome to react-native-cool-components 

You can use some cool and animated components which might be used in your react native project. More components will get updated in future


### Installation

``` npm i react-native-cool-components or yarn add react-native-cool-components```

### ButtonSwiper

![ButtonSwiper](/images/buttonSwiper.gif)


```import React, { Component } from "react";
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





