# freecodecamp
1. <h1> ... </h1> // LARGEST HEADING

2. <h2> ... </h2> // SUB-HEADING

3. <p>  ... </p>  // PARAGRAPH

4. <!--      -->  // COMMENTING

5. <h2 style="color:red">CatPhotoApp</h2> // CHANGES THE COLOR OF h2 TO RED

6. <style>  
  h2{
    color : blue;
  }       
</style>       // SEPERATING THE STYLE FROM HTML

7. // CLASSES ARE "REUSALE" CODES 

8. <style>
  .red-text
  {
    color:red;
  }
</style>

9. <h2 class="red-text">CatPhotoApp</h2>   // CREATION OF A CLASS AND ITS USE

10. <style>
  p
  {
  font-size: 16px   // change the font size of paragraph
  font-family: Monospace // specify the font family
  }
 </style>
 
11. <link href="https://fonts.googleapis.com/css?family=Lobster" rel="stylesheet" type="text/css"> // import a font-family and then inport in <style> ... </style>

12.     font-family: Lobster, Monospace; // if one font is not available then "DEGRADE" to the next available

13. <img src= "https://bit.ly/fcc-relaxing-cat" 
     alt= "Hello Kitty"> // THE IMAGE TAG, always add alt for description incase image not available
     
14. <img class="class1 class2"> // MULTIPLE CLASSES

15. // BORDER RADIUS 
    border-radius: 10px;  // square with circular edges
    border-radius: 50%;   // circular image (perfectly circular)
    
16. // ADDING EXTERNAL LINKS WITH SUBJECTS
<p> <a href="http://freecatphotoapp.com">cat photos </a> </p>
<a href=""> some text </a>

17.// Nesting just means putting one element inside of another element.
<p>View more
<a href="http://www.freecatphotoapp.com">cat photos</a>
</p>

// VIEW MORE cat photos .  (cat photos becomes a link to another site)
 
 18. // DEAD LINKS TO PLACE LINKS LATER
 <a href = "#"> </a>
 
 19. // TURNING IMAGES INTO LINKS
 <a href="#">
  <img class="smaller-image thick-green-border" src="https://bit.ly/fcc-relaxing-cat" alt="A cute orange cat lying on its back. ">
  </a>
  
 20. // BULLETTED UNORDERED LIST
 <ul>
  <li>milk</li>
  <li>cheese</li>
</ul>

21. // ORDERED LIST
<ol>
  <li>Garfield</li> // 1.    2.     3.     4. 
  <li>Sylvester</li>
</ol>
 
22. // CREATING TEXT FIELDS FOR USER TO ENTER INFORMATION (BOXES)
 <input type="text">

23. // PLACEHOLDERS FOR INPUT FIELDS
<input type="text" placeholder="this is placeholder text">

24. // You can build web forms that actually submit data to a server using nothing more than pure HTML. You can do this by specifying an action on your form element.

//For example:

<form action="/url-where-you-want-to-submit-form-data"></form>

<form action="/submit-cat-photo">
  
<input type="text" placeholder="cat photo URL">

</form>

25. // Add a Submit Button to a Form

<form action="/submit-cat-photo"> // what it will do
  
  <input type="text" placeholder="cat photo URL"> // information input and information holder
  
  <button type="submit">submit</button> // button to submit the information
  
</form>

26. // Use HTML5 to Require a Field

<input type="text" required>

// unless text is entered, nothing will happen

27. // CREATING RADIO BUTTONS
<form>
  <label>
    <input type="radio" name= "indoor-outdoor">
    Indoor
  </label>
    
  <label>
    <input type="radio" name= "indoor-outdoor">
    Outdoor
  </label>
  
  </form>
