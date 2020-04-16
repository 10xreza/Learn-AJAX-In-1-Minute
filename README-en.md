# Learn AJAX in 1 minute. ([Persian Version!] (./README.md))

## What's AJAX?

AJAX is a developer's dream, because you can:

    * Read data from a web server - after a web page has loaded
    * Update a web page without reloading the page
    * Send data to a web server - in the background

## How to code AJAX Program?!

```
var request = new XMLHttpRequest() // Create XML Object

request.open("GET","file.txt") // Configure your reuqest
request.onreadystatechange = () => { // Handle Event!
    if(request.state === 200 && request.readyState === 4) { // Go on only when server said okay!
        console.log("Bla Bla Bla!")
    }
}

request.send() // Send Request!

```
