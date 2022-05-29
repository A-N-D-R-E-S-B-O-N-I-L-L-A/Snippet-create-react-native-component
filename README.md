# Snippet to create React Native component

To use this snippet you will need to follow the steps below: 

1. copy the following code:

``` 
"React Native Component": {
	"prefix": "rnafc", // name of the snippet
	"body": [
		 "import React from 'react'",
		 "import { StyleSheet, Text, View } from 'react-native'",
		 "",
		 "export const $1 = () => {",
		 "  return (",
		 "    <View>",
		 "        <Text>$1 is working</Text>",
		 "    </View>",
		 "  )",
		 "}",
		 "",
		 "const styles = StyleSheet.create({",
		 "",
		 "});"
		]
} 
```

2. go to the top left in the visual estudio code and there click on View

3. Once you click on it, a menu of options will appear, where you will have to click on: Command Palette...

4. then you will get a kind of search bar where you will type the following: Configure user snippets. and then press enter.

5. after hitting enter you should get options like ```javascriptreact.json``` or ```typescriptreact.json```, then click on the one you prefer, this will depend if you work react with typescript or with javascript. 

6. after you click on it, an object will appear with a comment where you will paste the code you copied.

7. once copied save the file and this will be enough, remember that the ````"prefix"```` is the prefix of what you will call your snippet, in this case I call it ```rnafc```.

8. ready that's all remember that to use it just put ```rnafc``` or the prefix you put in the file and hit enter to complete the code. if it doesn't work close the VScode and reopen it.

9. And last but not least, good luck

