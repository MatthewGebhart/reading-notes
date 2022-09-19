# Class 13 Reading Notes - Local Storage

## Things I want to know more about
- JSON - what is that?
- 
## Local Storage and How to Use it on Websites

- Why would a developer use local storage for a web application?
 - To store responses or preferences
 - caching data to improve load times by reducing server calls
 - To reduce server reads and hosting costs
- What information should not be stored in local storage?
  - sensitive personal information
- Local storage can store what type of data? How would you convert it to that type before storing?
  - it can only store strings in local keys. You can get around this by using JSON.stringify() and JSON.parse() methods. Which are things I don't really understand....


// JSON commands

// read values
localStorage.getItem('key"');

//update values
localStorage.setItem('key', 'Kale');
localStorage.setItem('name', 'Jacob');

//delete
localStorage.removeItem('key');
localStorage.clear(); ///nuke it all


function addToKey (key, value) {
    let currentValue = localStorage.getItem(key);

    let newValue = currentValue + value;

    localStorage.setItem(ket, newValue);
}