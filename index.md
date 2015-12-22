# Learning JavaScript

This book's goal is to teach you JavaScript. On the way, you'll be introduced to other concepts that are necessary for you to properly appreciate JavaScript and programming as a whole. It's important to note that some concepts have been simplified to make them easier for a beginner to understand. If you're understanding of some sections is better than this book's, then you may be able to skip over it. Just remember to refer back to previous sections if you feel there is something you are missing. To start out, we're going to need to become a little more familiar with our web browser.

## What's a web browser?

A **web browser** is what you use to browse the "World Wide Web". The "World Wide Web" is a fancy name for the web also sometimes called the internet. Google, Facebook, Youtube, Baidu, and Amazon are all websites that make up a significant portion of the web. To access these websites, you use a web browser. Here are the names of some web browsers you may recognize:
* Chrome
* Safari
* Internet Explorer
* Firefox
* Edge

If you use any of the above, you're already fairly familiar with the basics of the web browser. It's important to distinguish the desktop version of these apps from the mobile version that's available on phones and tablets. For this book, we will need to have the desktop version because the mobile version does not have all of the features we'll require. Make sure you have any of the above desktop web browsers available for the rest of the book. We'll find that there's a lot we can do with these web browsers.

## Finding the JavaScript Console

Every web browser is going to be a little bit different on this so find the section that you use regularly.

### Chrome

* Make sure Chrome is open and that you can see it.
* Find the "tools button" in the top right part of your screen (it should look like three horizontal bars)
* Click on the tools button which will open a menu and hover over "More tools" opening a submenu.
* Click on "Developer Tools" in the submenu which will open up a horizontal sidebar.
* There will be a button that says "Console" between "Elements" and "Source". Click it.

## First lines of JavaScript

Now that you have the JavaScript Console open you can type JavaScript into the console and it will evaluate it immediately.

To make sure everything is set up, try typing your name. It should appear on the line like it does in Word or other text editing apps. Once you've finished typing your name, press "Enter" to tell the JavaScript console to execute this line of JavaScript. Look at the next line to see how the JavaScript Console evaluated it. The next line should read something like "Uncaught ReferenceError: Matthew is not defined". This means that the JavaScript Console has tried to execute the JavaScript line but resulted in an error. You can see that the red text indicates an error has occured. Remember this for later on.

Now let's try some code that will actually do something. Below is some text to try typing into the JavaScript console.

```js
alert('hello world')
```

After you've typed this out, you can press enter again to see what the result is. "alert" in JavaScript means open a small window with the text within the quotes. Pressing enter should open that window immediately and you can press ok to close it. If all is well, the next line should read undefined.
