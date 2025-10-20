# JAVA-FULL-STACK-DEVELOPMENT
Learning Content

# HTML & CSS
Save the below file as HTML on VS Code and then open the file in web browser

<!DOCTYPE html>
<html>
<head>
 <title>My First JavaScript</title>
</head>
<body>
<h2>My First JavaScript Program</h2>
<button onclick=”displayMessage()”>Click
me
</button>
<p id=”demo”></p>
<script>
function displayMessage() {
 document.querySelector(“#demo”).
textContent = “Welcome to your first
JavaScript program.”;
}
</script>
</body>
</html>
</html>

It will display the page - file:///C:/Users/Sumayya/Desktop/Summ-Resume/HTML.html 


<!DOCTYPE html> - The declaration is not an HTML tag. It is an "information" to the browser about what document type to expect. In HTML 5, the declaration is simple: <!DOCTYPE html>. In older documents (HTML 4 or XHTML), the declaration is more complicated because the declaration must refer to a DTD (Document Type Definition).

# Worked on VS CODE & Run it using live server
<!DOCTYPE html>
<html>
    <head>
        <title>My first Webpage</title>
        <style>
            img {
                width: 100px;
                border-radius: 60px; 
            float: left; 
        margin-right: 10px;         }
        p.username {
            font-weight: bold;
            color: blue;
        }
        </style>
        <body>
            <img src="images/Anass.png">
            <p class="username">@MohammadAnas</p>
            <p>I love my husband too much!</p>
        </body>
    </head>
</html>

