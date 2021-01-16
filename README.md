# Responsive-Web-Design
The Repository describes the basic html and css concepts

## Basic HTML and HTML5

### Introduction to Basic HTML:

   HTML, or HyperText Markup Language, is a markup language used to describe the structure of a web page. It uses a special syntax or notation to organize and give information        about the page to the browser. Elements usually have opening and closing tags that surround and give meaning to content.
   - Example:

    ```
    <h1>Top level heading: Maybe a page title</h1>

    <p>A paragraph of text. Some information we would like to communicate to the viewer. This can be as long or short as we would like.</p>

    <ol>
      <li>Number one on the list</li>
      <li>Number two</li>
      <li>A third item</li>
    </ol>
    ```
 
 1. Headings
    This element tells the browser about the structure of your website. h1 elements are often used for main headings, while h2 elements are generally used for subheadings. There       are also h3, h4, h5 and h6 elements to indicate different levels of subheadings.
   **Example:**
   ```
   <h1>First Heading</h1>
   <h2>Second Heading</h2>
   <h3>Third Headind</h3>
   <h4>Fourth Heading</h4>
   <h5>Fifth Heading</h5>
   <h6> Sixth Heading</h6>
   ```
   
 2. Paragraph Element
    p elements are the preferred element for paragraph text on websites. p is short for "paragraph". You can create a paragraph element like this:
    ```
      <p> This is Paragraph </p>
    ```
   
 3. Comment in HTML  
    Commenting is a way that you can leave comments for other developers within your code without affecting the resulting output that is displayed to the end user.
    Commenting is also a convenient way to make code inactive without having to delete it entirely. Comments in HTML start with ``` <!-- and end with a --> ```
    
    
    
### Introduction to HTML5 Elements
   HTML5 introduces more descriptive HTML tags. These include main, header, footer, nav, video, article, section and others.
   These tags give a descriptive structure to your HTML, make your HTML easier to read, and help with Search Engine Optimization (SEO) and accessibility.
   
 1. main:
   The main HTML5 tag helps search engines and other developers find the main content of your page.
   **Example:**
   ```
   <main> 
     <h1>Hello World</h1>
     <p>Hello Paragraph</p>
   </main>
   
   ```
   Note: Many of the new HTML5 tags and their benefits are covered in the Applied Accessibility section.
   
 2. Images to Your Website:
    You can add images to your website by using the img element, and point to a specific image's URL using the src attribute.
    **Example:**
    ```
    <img src="https://www.freecatphotoapp.com/your-image.jpg">
    ```
    Note that img elements are self-closing.
    All img elements must have an alt attribute. The text inside an alt attribute is used for screen readers to improve accessibility and is displayed if the image fails to         load. 
    Note: If the image is purely decorative, using an empty alt attribute is a best practice.
    Ideally the alt attribute should not contain special characters unless needed.
    
 3. Link to External Pages with Anchor Elements:
    You can use a (anchor) elements to link to content outside of your web page. a elements need a destination web address called an href attribute. They also need anchor text.     **Example:**
    ```
      <a href="https://freecodecamp.org">this links to freecodecamp.org</a>
    ```
 4. Link to Internal Sections of a Page with Anchor Elements:
    a (anchor) elements can also be used to create internal links to jump to different sections within a webpage.
    To create an internal link, you assign a link's href attribute to a hash symbol # plus the value of the id attribute for the element that you want to internally link to,         usually further down the page. You then need to add the same id attribute to the element you are linking to. An id is an attribute that uniquely describes an element.
    **Exmaple:**
    ```
    <a href="#contacts-header">Contacts</a>
    ...
    <h2 id="contacts-header">Contacts</h2>
    ```
    When users click the Contacts link, they'll be taken to the section of the webpage with the Contacts header element.
