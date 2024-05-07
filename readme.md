🚀 Hello SCE6 🚀

- Step 1: `fork` this repository
- Step 2: `clone` it into your "code" folder
- Step 3: access to the folder with `cd`
- Step 4: create an index.js file


## Independent Practice


### Function 1:
- **Description**:Find the last occurrence of a substring in a string.

- **Instructions**: Define a function that receives two strings. If the second parameter is inside the first one, only once, it has to return true. If the word is more than once or it does not appear, it has to return false.

-**Requirements**: You have to use indexOf, lastIndexOf, and includes methods.

```js
onlyOnce(“This is the sentence” , “is”) // false
onlyOnce(“This is the sentence” , “sente”) // true
```

### Function 2:
- **Description**: Define a function that receives two strings. 

- **Instructions**: You have to return an empty string if the second parameter is not inside the first one or return a string from the beginning of the first string until the second string is shown for the first time.

-**Requirements**: You have to use slice.
```js
isThere('This is the sentence' , 'is') // 'This'
isThere('This is the sentence' , 'are') // ''
isThere('This is the sentence' , 'sent') // 'This is the sent'
```


______
Made with 🩷 by [DTR](https://github.com/tabraue) for SCE6

    - Belongs to Reboot Academy -