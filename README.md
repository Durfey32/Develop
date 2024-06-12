# Sematic Update 

In this website I added semetic structure to make the website follow accessibility stadards. 

##Description

The main goal of this project was to make this website follow accessibility Standards. The way this was done was by adding Sematic Elements to make the HTML webpage more accessible. Examples of the Semeatic updates were elements like < nav> , < header> , < main> , < section> , < aside> ,and < footer>. Another feature we added to make it more accessible is to add the alt descriptions to all 6 of the images on the webpage. The last thing done for the webpage to be more accessible was to clean up the CSS page; there were several features that were repeating on the page that I was able to clean up using multiple elements selected at once. 

## Code Refactor Example

This is the original section of code from the website before adding any sematic elements. 
```html
 <div class="header">
        <h1>Hori<span class="seo">seo</span>n</h1>
        <div>
            <ul>
                <li>
                        <a href="#search-engine-optimization">Search Engine Optimization</a>
                </li>
                <li>
                        <a href="#online-reputation-management">Online Reputation Management</a>
                </li>
                <li>
                        <a href="#social-media-marketing">Social Media Marketing</a>
                </li>
            </ul>
        </div>
```
This is the original section after adding sematic elements to the code. 

```html
    <header>
        <h1>Hori<span class="seo">seo</span>n</h1>
        <div>
            <ul>
             <nav>
                <li>
                        <a href="#search-engine-optimization">Search Engine Optimization</a>
                </li>
                <li>
                        <a href="#online-reputation-management">Online Reputation Management</a>
                </li>
                <li>
                        <a href="#social-media-marketing">Social Media Marketing</a>
                </li>
             </nav>
            </ul>
        </header>
```

After changing the header from a class selector to an element selector the CSS will need to be changed. the original looked like this: 

```css
.header {
    padding: 20px;
    font-family: 'Trebuchet MS', 'Lucida Sans Unicode', 'Lucida Grande', 'Lucida Sans', Arial, sans-serif;
    background-color: #2a607c;
    color: #ffffff;
}
```

The change will happen by removing the period before header, because the header is now an element rather than a class selector. 

```css
header {
    padding: 20px;
    font-family: 'Trebuchet MS', 'Lucida Sans Unicode', 'Lucida Grande', 'Lucida Sans', Arial, sans-serif;
    background-color: #2a607c;
    color: #ffffff;
}

```
## Learning Points

This project taught me about the importants of having a webpage follow accessibility standards. The importants of Sematic elements and the uses of keep the HTML as clean and precise as possible. Doing these things allows for a much smoother transition from coder to coder or even in editting functionality later. I will try to apply this knowledge to all my websites going forward. 

# Thank you

### Spencer Durfey 
```
* [email](durfey_32@yahoo.com)
* [GitHub](https://github.com/Durfey32)
* [LinkedIn](www.linkedin.com/in/spencer-durfey-636579256)
```
