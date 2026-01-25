# Repository Introduction
This showcases the resources and approaches I used to learn web development.

Notes starts here:

## HTML
* **HTML** stands for hyper text markup language. 
* It is used to define the structure of contents in the website.
* It has inbuilt elements which helps to specify differnt content types.

### Close tags and Open tags
* **Close tags:** : Tags which needs a closing tag.
    ```
    <h1></h1>
    <p></p>
    ```
* **Open tags** : Tags which doesn't need a closing tag. 
    ```
    <hr/> : used to draw a horizontal line
    <br/> : used to break into new line
    ```

### Heading element
* This element is used to display any text as heading.
* It has values from h1 to h6; where h1 is largest and h6 is smallest
    ```
    <h1>This is heading 1</h1>
    <h2>This is heading 2</h1>
    .
    .
    .
    <h6>This is heading 6<h6/>
    ``` 

### Paragraph element
* Used to define any content as a paragraph.
* Usually used when need to display a large amount of content.
    ```
    <p>This is a pragraph element</p>
    ```

### List element
* Used to display a list of value or items.
* We have two types of list elements.
    1. **Ordered list** : Display the list items with numeral, roman numeral, or alphabets
        ```
        <ol>
            <li> item1 </li>
            <li> item2 </li>
            <li> item3 </li>
        </ol>
        ```
    2. **Unorder list** : Display the list items with bullet, square, disc, or circles
        ```
        <ul>
            <li> item1 </li>
            <li> item2 </li>
            <li> item3 </li>
        </ul>
        ```
### Anchor Element
* Used to add links to the website. 
* Uses attribute **href**.

    Attributes - Extra information about the tag.

    ```
    <a href="https://www.google.com/"> This is a link</a>
    ```

### Image Element
* Used to add images in our website.
* Uses attribute **src**.
* Other commonly used attributes are: alt, height, width
    * alt - Used to give an alternate text for visual impairment peopel. Hence describing the image.
    * height - To set the height of the image.
    * width - To set the width of the image.

        ```
        <img src= "img_source_url">
        ```

### HTML FORMS
* Are used to make forms in our site which can be filled by user.
* Used to build forms like: Hotel booking, airplane booking, railway booking 
* Below is a simple login form
    ```
    <form action="\login" method="POST">

        <label for="email"> Email </label>
        <input type="text" name="email" required>
        
        <label for="password"> Password </label>
        <input type="text" name="password" required>
        
        <input type="submit" value="Submit">

    </form>
    ```

### File paths
* File paths is an important concept as it helps to define where the file is located
* We categorize file paths into 2 categories
    1. Absolute file path
        * Provides the full path to the file            
            >X:/folder1/project/project1/file1.txt

    2. Relative file path
        * Can be used to access files which are in previous directory
            >../project/project1/file1.txt

        * Can be also be used to access the file in current directory
            >./file1.txt
