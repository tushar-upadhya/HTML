# HTML

Q1. What is HTML?

Ans. HTML stands for Hyper Text Markup Language. HTML is the standard markup language for creating Web pages. HTML describes the structure of a Web page. HTML consists of a series of elements. HTML elements tell the browser how to display the content.

Q2. What do you mean by a markup language?

Ans. Markup languages are computer languages that are used to structure, format, or define relationships between different parts of text documents with the help of symbols or tags inserted in the document.

Q3. Can you share examples of other markup languages and how they differ from HTML?

Ans. Some examples of a markup language are HTML, XML, XHTML, SGML.. .HTML’s full form is Hypertext Markup Language, while XML is an Extensible Markup Language. The purpose of HTML is to display data and focus on how the data looks. Therefore, HTML describes a web page’s structure and displays information, whereas XML structures, stores, and transfers information and describes what the data is.

Q4. What version of HTML do you use in your projects? How is HTML 5 different from HTML 4?

Ans. I use HTML 5 version. .HTML 5 is the latest and more advanced version of HTML 4. HTML5 comes with new tags, new features, and has simplified various functions. While many people considered HTML 4 a bit complicated, HTML5 offers more flexibility to developers in making a stunning website.

Q5. What are attributes in HTML?

Ans. Attributes provide additional information about elements. Attributes are always specified in the start tag. Attributes usually come in name/value pairs like: name="value"

Q6. What are data- attributes good for?

Ans. data-* attributes allow us to store extra information on standard, semantic HTML elements without other hacks such as non-standard attributes, or extra properties on DOM.

Q7. Describe the difference between &<script>, <script async> and <script defer>.

Ans. <script> = used to define a client-side script. The script with async attribute will be executed once it is downloaded. While the script with defer attribute will be executed after completing the DOM parsing.

Q8. Why is it generally a good idea to position CSS s between </head&> and JS <script>s just before ? Do you know any exceptions?

Ans. You usually put the tags in between the to prevent Flash of Unstyled Content which gives the user something to look at while the rest of the page is being parsed.

Since Javascript blocks rendering by default, and the DOM and CSSOM construction can also be delayed, it is usually best to keep scripts at the bottom of the page.

Exceptions are if you grab the scripts asynchronously, or at least defer them to the end of the page.
