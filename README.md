## Notes:
# HTML is skeleton of web projects, CSS is the skin of web projects and JavaScript is the controller of the web projects
Even single error can cause abnormal changes in the file.
We can use validator.w3.org for errors in html file.

# headars
In html headers are h1, h2, h3 and so on. We use headers mainly defining topics and subtopics in web pages. we can change the pixel size of the headers with CSS.

# paragraphs
In paragraphs, the space are by default removed with one. This is called white space collapsing. we can use &lt;br&gt; tags for line breaks.

# Elements
In HTML, &lt;p&gt;, &lt;h1&gt; etc., are called as block level elements. &lt;em&gt;, &lt;strong&gt; etc., are inline elements and used within block level elements.

# HTML entities
These are the character that cannot be typed and managed like want to have more whitespaces, greater than(&gt;), less than(&lt;) symbols etc., HTML entities usually start with &.

# Lists
The list tags are used to display data with bullet points, numbers etc., Examples for list tags are &lt;ol&gt;,&lt;ul&gt;,&lt;dl&gt; etc., 

# Links
'link' tag is used to access the resources wheather they are local or some other resources from the internet.<br>
'anchor' tags is used to move between different pages. <br>
### Best practices using links
<ul>
<li> don't put click here things. minimize them if you can.</li>
<li> don't put phrases like "links to" because links are highlighted and users are aware of it.</li>
<li> Avoid putting full web address as a link.</li>
<li> Keep link text short and exact topic not sentences.</li>
</ul>

# Images
The images can be added with 'img' tag.<br>
It is common to put width, height for reserving place for that image.<br>
we can enclose the 'img' inside 'figure' tag for more options.<br>
We can specify loading type of the image i.e., either eager or lazy.<br>
All other things like color and styling can be done with css. 

# semantics 
It is important to have semantics to the HTML. It increase readability and maintable while developing projects. <br>
Avoid using 'div', 'span' etc., which has no semantic meaning and we have to add id's each one of them to manage.<br>
Semantic tags that are commonly used in web are main, header, footer, section, article, aside, nav etc.,

# Tables
Tables are the common way to visualize the data for data analysis.<br>
By using appropriate semantics tags like 'thead', 'tbody', 'tfoot' etc., will make the code more readable and make it easy to update the table.

# Forms
Forms are used to send HTTP POST and HTTP GET request to servers. They are commonly used for signup, login etc.,
