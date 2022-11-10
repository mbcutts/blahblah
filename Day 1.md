# Portfolio Site Guide Day 1

###### Author(s):  Shawn E.

### Objectives
 
- Learn the basics of the HTML
<br>

- Start your portfolio site with just HTML

### Steps

- First head over to your `index.html` file.
<br>
- Next lets create a `h1` tag with the text *Hello World*, then run the project it should look somthink like this.
```html
<h1>Hello World</h1>
```
<br>

- Now you can delete that *Hello World* and replace it with your name.


<br>

- Now lets add a little description about you, try using a **paragraph** tag to add this.
> *Hint*: Use google to find your answer

<br>

- Create a heading for this section you can call it *Skills*
- Add your skills to this using a **unordered list**.

<br>

- Lets now create a section to show off projects you have made use what you have learned previously to make this section.

<br>

- Now lets try adding some links to the page using a *anchor* tag.

<br>

- Now we are going to take a step back and divide our sections using the HTML `div` element
  - To do this find a section for this we are going to use the about section and put a div around it something like this.
    ```html
    <!DOCTYPE html>
    <html>
    
    <head>
      <meta charset="utf-8">
      <meta name="viewport" content="width=device-width">
      <title>Portfolio Project</title>
      <link href="style.css" rel="stylesheet" type="text/css" />
    </head>
    
    <body>
      <h1>Name Here</h1>
      <div>
          
        <p> Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore  et dolore magna aliqua. Sed pulvinar proin gravida hendrerit lectus. Diam in arcu cursus euismod quis viverra nibh cras pulvinar. Pellentesque habitant morbi tristique senectus et. Eget nulla facilisi etiam dignissim diam quis enim lobortis. Ac tortor vitae purus faucibus ornare suspendisse. Fringilla ut morbi tincidunt augue interdum velit euismod in. Et leo duis ut diam quam nulla porttitor massa. In vitae turpis massa sed elementum. Laoreet sit amet cursus sit. Habitant morbi tristique senectus et netus et. Varius duis at consectetur lorem donec massa sapien faucibus et. Consectetur adipiscing elit duis tristique sollicitudin nibh sit amet. Euismod elementum nisi quis eleifend quam adipiscing vitae proin. Sollicitudin ac orci phasellus egestas. Nulla posuere sollicitudin aliquam ultrices sagittis orci a scelerisque. Elit eget gravida cum sociis natoque. </p>
        
      </div>
    </body>
    
    </html> 
    ```
  - Now that we have done that lets give the div that you made a class the div should now look something like this
    ```html
    ...
    <div class="about">
      <p>...</p>
    </div>
    ...
    ```
    > *Note:* This class name could be anything that you would like.

  - Now that we have put our content in a div lets get each element inside of that div a id so, later we can style our tags easier. Your code should be somthing like what is shown below.
    ```html
    ...
    <div class="about">
      <p id="about-text">...</p>
    </div>
    ...
    ```
  <br>
  
  - Now go ahead and add divs around all your section and id's to most if not all your elements
   
<br>

- Ok, so by now you sould have a pretty good amount of text on the page, lets add some more
    - Find a portfolio online that you like and find a section that they have that you dont *Example:* `Education`.
    - > *Note:* You are not looking for the design rather you are looking for the actual content 
    - Implement this section into your portfolio where ever you would like
    
    <br>
    
    > If you can't find a portfolio that you like or that has diffrent sections here are some to check out.
  > 
  > <br> [Shawn Engmann's Portfolio](https://shawnengmann.com)
  > <br> [Luis Quezada's Portfolio](https://quezada.nl)
  > <br> [Hyperz#0001 Portfolio](https://hyperz.net)
  > <br> [Jack's Portfolio](http://jacekjeznach.com)
  > <br> [Tazio de Bruin's Portfolio](https://en.tazio.nl/)
