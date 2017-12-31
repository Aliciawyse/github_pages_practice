# My first portfolio

In this assignment, I built a professional portfolio site. The primary purpose of this assignment is to build a portfolio that matches a provided style guide. 

## Built With

* HTML5/CSS3
* jQuery 3.2.1

## Development Process

1. Getting started

    I created a new repository in GitHub called `my_basic_portfolio` and created the following: 

   * 5 HTML documents: `index.html`, `contact.html`, `portfolio.html` `header.html` and `footer.html`.
   * A folder called `assets`.
   * Inside the assets directory, make two additional folders: `css` and `images`.
     * In the `css` folder, there's a file called `style.css`.
     * In the `css` folder, there's a file called `reset.css`, and include the code found from the Meyerweb reset located [here](http://meyerweb.com/eric/tools/css/reset/reset.css).
     * In the `images` folder, save the images I use (like my profile image, the placeholder images for the portfolio, and the social icon images).
     
   Here are some of the provided screenshots.
 
   ![Portfolio About](assets/images/Portfolio_About.png)

   ![Portfolio Contact](assets/images/Portfolio_Contact.png)

   ![Portfolio Gallery](assets/images/Portfolio_Gallery.png)

2. Challenges and successes
    
   The code I wrote successfully validates. I used W3's validator to confirm. [Validate my code here](https://validator.w3.org/#validate_by_input). 
   
   I used jQuery so that I could edit my header and footer in their respective html files `header.html` and `footer.html`. This allowed me to edit the header and footer in a single spot versus across each and every html file. Here's how I made that happen. 
   
   At the bottom of every file that has a header and footer I have the following:
   
   
   ```javascript   
<script>
    $("#my_header").load("header.html");
    $("#my_footer").load("footer.html");
</script>
```

   The  `.load()` method sets the HTML contents in `header.html` or `footer.html` to the elements with the id `#my_header` or `#my_footer`.
   
   Implementing a sticky footer was more complicated than I thought. While it works, it blocks content in on the portfolios page (see `portfolio.html`). I plan on revisiting this code to make the sticky footer work properly on this page. 
   
## Use It
Git clone this repository to your local machine. 
