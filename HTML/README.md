# HTML and CSS
- They are not a real <it>programming</it> langauge. :( 
    <strong>Why?</strong>: because, they are only presentational languages. Present the information, no need to have a logic. 
    
## HTML (HyperText Markup Language)
- Defines the structure and content of webpages.
- It is the raw data that the webpage is built of.
- Kind of the barebones (may not be the best word for it) i.e: texts, links, images, buttons are created in HTML.

## CSS (Cascading Style Sheets)
- Styling part.

<strong>Thus</strong>;
 HTML puts informations on the page, the CSS styles it by assigning positions, colors, font and etc.

 ## JavaScript
 - It's the programming language that makes websites do stuff.
 - Allows us to change CSS and HTML elements. Make it more interactive...


<figure> 
<img src="https://web.archive.org/web/20220814090513im_/https://brytdesigns.com/wp-content/uploads/2019/12/html_css_javascript_infographic-1024x614.png" alt="infographic about the HTML,JS and CSS">
<figcaption> This image is retrieved from <a href="https://web.archive.org/web/20220814090513/https://brytdesigns.com/html-css-javascript-whats-the-difference/">brytdesigns.com </a></figcaption>
</figure>


# HTML in more depth
### Elements and Tags
 Most of the information is wrapped in openning and closing tags. Angle brackets `<>` are the indicators of tags and they inform browsers about the HTML elements.

 `<`: openning tag --> indicates the start of a HTML element.
 `<`: closing tag --> indicates the end of a HTML element.
 - The keywords, or letters express the type of the elements.

 <it> For example </it>, `<p> this is a paragraf </p>` 

 - Not all HTML elements have closing tags. Some of them are self-closing such as `<br>` and `<img>`.

 <a href="https://developer.mozilla.org/en-US/docs/Web/HTML/Element#main_root">This mozilla article </a> lists a huge collection of HTML tags.

HTML elements have <strong> 3 parts</strong>;
        <ul>
          <li>openning tag </li>
          <li>content</li>
          <li>closing tag</li>
        </ul>

#### Some rule of thumbs
- when creating a webpage, it is a rule of thumb to name your html file as index.html 
- do not use `<b>` and `<i>`, use `<strong>` and `<em>` instead. 
- always create a folder for your:
    - images
    - create a css folder
    - create a javascript folder
- use lowercase sytnax for all the folders,files and scripts.
- always avoid using space, you can use "-" instead.
- Divs are better as the main frame, since they are like the building blocks. Spans can be used for the sake of styling.
- classes (.class) are more general.
- ids  (#id) are more unique
- if you are using an anchor `<a>`, the order for the css sytling should be:
    - a: link {color:black;}
    - a:visited {color:pink;}
    - a:hover {color:yellow;}
    - a:active {color:blue;}
    
_for being able to see all the actions active. In here, the link will be in black as default and it will become yellow when there is a mouse hovering over it. While it is being clicking down, the color will be blue and it will turn to pink when it is clicked once._
- always resort to specificity
    - .body-text, .body-text .specific-rule { something: something; } 
- `!important` case should be the last scenario.