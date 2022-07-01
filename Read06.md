# Dynamic Webpages With JavaScript

JavaScript was invented by Brendan Eich in 1995. It is a lightweight programming language that is used to make dynamic and interactive websites. In order to use JS you must start by linking a JavaScript file to your html document or opening up a "script" tag in your HTML document. From there you are able to execute your script through variables, functions, input, and many other elements. Variables and functions both run inside your script tags or JS document where as input is something directly entered into your HTML document. There are so many different variations of these elements allowing users to create seemingly unlimited possibilites of code.

## JavaScript Examples

-function getFavoriteBoxer() {

    let favoriteBoxer = prompt('Who is your favorite boxer?');
    
    let message = "Hmmm, " + favoriteBoxer + ", that's a good one!";
    
    alert(message);
    
    document.getElementById('favorite-boxer').innerHTML = favoriteBoxer;
}

-

