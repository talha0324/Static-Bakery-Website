# Sample Static Bakery Items Website

## Usage

- To add new items copy/paste the template file in items folder and rename it to something new. Make the following changes.
    1.  Image url. i.e. on line:27 of the file. Replace **{image_link}** with your image link 
    
        `data-menu-name="PREVIEW_INLINE_IMAGE" style="background-image:url({image_link});"`
    2. Title in line:43. Replace **{title}** with the desired title

        `data-menu-name="PREVIEW_SUBTITLE">{title}</h3>`
    3. Price in line:50. Replace **{price}** with desired price
            
        `data-menu-name="PREVIEW_TITLE">{price}</h2>`
    4. Description starts from line:59. Replace **{description}** with desired description
        
        ```
        data-menu-name="PREVIEW_BODY">
                <p>
                    {description}
                </p>
            </div>
        ```
        
- Now to show this item on menu page
    1. Open file on root onload.js
    2. Add new file name in the array on line:3
        a) let's say we have items before 
        
                ```
                let items = [
                    'item1.html', 'item2.html',
                ];
                ```
        b) if we want to add another item that we saved in a file named item3.html, the array will be
        
                ```
                let items = [
                    'item1.html', 'item2.html', 'item3.html',
                ];
                ```
- Lastly To change the logo of the website. Change the file under images/logo.png  to the new image with the same name
