# THE HTML SKELETON
Ok firstly, what is HTML?

HTML is a programming language the makes up all of the websites you see(actually it just makes the barebones).

It stands for **H**yper **T**ext **M**arkup **L**anguage

What you would need for this tutorial: A text editor, a browser, and intrest learning HTML

Ok lets start coding

A HTML file always starts like this

```html
      <!DOCTYPE html>
      <html lang="en">
          <head>
              <meta charset="UTF-8">
              <meta http-equiv="X-UA-Compatible" content="IE=edge">
              <meta name="viewport" content="width=device-width, initial-scale=1.0">
              <title>Your title</title>
          </head>
          <body>

          </body>
      </html>
```

The `<!DOCTYPE html>` tells the browser this is HTML 5

The `<html lang="en">` tells the broswer hey this is the start of the HTML! The `lang="en"` **_attribute_** tells the broswer the **_tags_** in is written in the computers's default english

The head tag contains like the header information such metadata the title of the tab.

Time to explain the metadata

The first one is the character encoding which is UTF-8

The second one allows this webpage to work on older browsers like IE8 and IE9

The third one just does scaling and dimensions

The `title` tag is the tab name

The `body` tag contains everything the user sees

Ok copy and paste or write the code in your text editor and save it. Double click it in your file manager and WHAT???

It didn't show anything and it's not supposed. It's because we didn't add anything in the body tag.

Quickly add in some text in there and refresh the page in the broswer.

It should show the text
