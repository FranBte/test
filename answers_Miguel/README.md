#Git & Github Instructions for test

**Note: Test questions can be found on the index.html file**

##Starting the test
1. Fork the test repository. The fork button is on the top-right hand side of your screen. 
2. Once you've finished forking, create a folder on your local for the test. Then, clone the fork into a folder. 
3. Copy and paste the test folder. Rename the copy to answers_yourname e.g. answers_francesca. 


##Finishing the test
1. When you're finished with the test, add your answers to the staging area using "git add filename". 
2. Then, commit the changes using "git commit -m '' ". Do not forget to leave a commit message e.g. git commit -m "yourname test answers". 
3. Finally, push your changes to your forked repository using "git push".

###Creating a pull request
4. Once you have pushed your test answers, go to the original repo and click "New pull request" (middle & left of the page). Once you have clicked "New pull request", click "compare across forks". It is very **important** that you compare the original to your fork. 
5. Then, you can give the pull request a title and description. Once you're ready, click "Create pull request". 

That's it! Good luck :)


 <header>
        <h1>Test!</h1>
        <h2>Try to finish the exercises to the best of your abilities - read the tasks and instructions carefully</h2>
        <h3>You CAN use google, but you cannot ask teachers or other classmates for help</h3>
    </header>

    <main>
        <h3>Tasks</h3>
        <ol>
            <li>Make and link a CSS stylesheet and work from there.</li>

            <li>Align the text in the header to the right of the page. Make the header take up 100% of the width and 10rem in height.</li>

            <li>Give three h4 elements a class, change the font color, font size and font family of the class.</li>
           
            <li>Find the div with 10 span elements nested inside. Change the background color of every odd span element starting from the 5th element using nth-child(). Use a hexadecimal color code for the background color.</li>
           
            <li>Media Query Task</li>
                <ul>
                    <li>Go to the section titled "Media Queries". Give the box with the class of "media-query" a border at the different breakpoints. Look at the instructions for the border below. NOTE: You must also change the border thickness and color at every breakpoint. Then, continue to change the size of the box at the different breakpoints.</li> 
                    <li>Mobile: dotted border, size: 5em x 5em</li>
                    <li>Tablet: dashed border, size: 10em x 10em - BREAKPOINT: 768px.</li>
                    <li>Desktop: solid border, size 12em x 12em - BREAKPOINT: 1024px.</li>
                    <li>Large: double border, size 14em x 14em - BREAKPOINT: 1440px</li>
                </ul>

            <li>Flexbox Task </li>
                <ul>
                    <li>Go to the section titled "Flexbox"</li>
                    <li>Align the "fx-items" in the "fx-container" in a row. </li>
                    <li>Make the flex items take up multiple rows.</li>
                    <li>Position the flex items on the end (right) of the container.</li> 
                    <li>Make the flex items take up all available space at every size of the viewport.</li>
                </ul>  

                <li>Positioning Task</li>
                <ul>
                    <li>Go to the section titled "Positioning"</li>
                    <li>Give the div with the class "position-relative" a relative position. Use positioning to center the div in its parent element (the box - class "position-box").</li>
                    <li>Give the div with class "position-absolute" an absolute position. Use positioning to align the div in the top-left corner of its parent element (the relative container).</li>
                    <li>Make the parent container (class name - "position-box") in this section stick to the top-right of the page.</li>
                </ul>

                <li>Make sure the "position-box" appears beneath all elements on the page.</li>

                <li>Underline ALL the TASK list items. NOTE: ONLY underline the task list items and not any other list items on the page.</li>
        
            <li>Grid Layout Task</li>
                <ul>
                    <li>Go to the section titled "Grid Layout"</li>
                    <li>Make the div with the class "wrapper" a grid.</li>
                    <li>Give it three rows and four columns of equal size.</li> 
                    <li>Give the grid container a border.</li>
                    <li>Give the grid a grid gap of 15px.</li>
                    <li>Give all grid cells a border.</li>
                    <li>Make the first cell twice as high as the rest of the cells.</li>
                    <li>Make the fourth cell twice as wide and twice as high as the rest of the cells.</li>
                    <li>Make the sixth cell twice as wide as the rest of the cells.</li>
                </ul>

                <li>Images Task</li>
                <ul>
                    <li>Find the images section in the HTML file.</li>
                    <li>Find the div with the class of "bg-image" and select it by its class name in CSS.</li>
                    <li>Give the div with the class of "bg-image" a width of 20em and a height of 20em.</li>
                    <li>Give the div with the class of "bg-image" a background image using the image "tree.jpg". The image can be found in the "images" folder</li>
                    <li>Set the background image to contain.</li>
                    <li>Make sure the background image repeats itself</li>
                </ul>
            <li>Make all of the images in the "images section" appear on different lines.</li>
            
            <li>Select the third image (surfer image) by its src attribute value - make sure that it is an EXACT match. Give the image padding and a dashed red border.</li>
            
            <li>Change the color of THIS list item to red. Use an ID to select this HTML element.</li>

            <li>Select all the anchor links in the footer. Select them as DESCENDANTS of the footer using a combinator. Change the color of the footer links on :visited, :active and :hover.</li>

            <li>Give the whole body element padding on the left and the right.</li>
        </ol>
