#Sample Static Bakery Items Website
##Usage
- TO add new items copy/paste a new file in items folder. change the following desired things.
    1.  Image url. i.e. on line:22 of the file
            data-menu-name="PREVIEW_INLINE_IMAGE" style="background-image:url(--> this link <--);"
    2. Title in line:37
            data-menu-name="PREVIEW_SUBTITLE"> --> title here <-- </h3>
    3. Price in line:48
            data-menu-name="PREVIEW_TITLE"> --> Price here <-- </h2>
    4. Description starts from line:61
            data-menu-name="PREVIEW_BODY">
                <p>
                    -->Description here<--
                </p>
            </div>

- Now to show this item on menu page
    1. Open file on root onload.js
    2. Add new file name in the array on line:4
        a) let's say we have items before 
                let items = [
                    'item1.html', 'item2.html', 
                ];
        b) if we want to add another item that we saved in a file names item3.html, the array will before
                let items = [
                    'item1.html', 'item2.html', 'item3.html',
                ];
- To change the logo of the website. Change the file under images/logo.png  to the new image with the same name
