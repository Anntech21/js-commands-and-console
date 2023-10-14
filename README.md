# JavaScript - Commands and Console

### Create + Connect A JavaScript File

1. After forking and cloning this repo, navigate into the repository's directory (use `cd`!) and create an `index.html` file there.
2. Create a folder called `js`.
3. In your `js` folder, create a file called `custom.js`.
4. Connect your `js` file to your `index.html`.
   - In `index.html`, in the `head`, add your `script` tag. Remember that you need the path to the file—it's in the `js` folder!
   - If you're not sure how to do the above, find an article online that describes how to connect your JS to your HTML—remember that the internet is your best friend for refreshers!

### Dev Tools + Console.Log

1. Back in your `custom.js` file, write this command: `console.log(“Hello, World!”);`
2. Start Live Server.
3. Go to your browser.
   1. Open Dev Tools.
   2. Click on the "Console" tab.
   3. What do you see?
4. In your `custom.js` file, take away the quotes from your `console.log`, so it reads: `console.log(Hello, World!);`
   1. What happens in the console?
   2. Read the error very carefully.
   3. Remember errors are your friend!
5. Add the quotes back to your `console.log`.
6. Add another `console.log` so that your name appears in the browser’s dev tools.
7. Add `2+2` in a `console.log` and check your answer in the console.
   1. What happens when you add quotes around each number?
   2. What happens when you don’t?

### Alerts

1. In your JS file, write `alert(“Hello, World!”);`
2. Refresh the page in the browser - what happens?
3. What are some real-life alerts you have seen?
4. Write another alert that copies one you might see on a website.
5. What happens to the first alert? (You can comment them out if they get annoying.)

### Prompts (And Declaring Your First Variable!)

1. In your JS file, write:

```javascript
let firstName = prompt(“What is your first name?”);
console.log(firstName);
```

2. Back in your browser, refresh the page.
3. Answer the prompt.
4. Look in the console, what do you see?
5. What happens when you add quotes to `firstName`?

```javascript
console.log(“firstName”)
```
