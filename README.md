# Introduction to CSS

## Objectives
Link an external CSS file to an HTML document.
Apply basic styling using selectors.
Use colors, fonts, and spacing effectively.

## Instructions

Create a style.css file.
Apply CSS to a HTML page.
Style elements using:
Classes and IDs.
Color and typography.
Margins, paddings, and borders.

>[!NOTE]
>  - Include at least:
>  - Use of 3 selectors
>  - Style an image
>  - Margin, Padding & Borders
>  - Different font

# Tasks
Link an external CSS file.
 - Apply at least 3 different selectors.
 - Improve readability and aesthetics.

Happy Coding! 💻✨




Answers
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Styled HTML Page</title>
    <link rel="stylesheet" href="style.css">
</head>
<body>
    <h1 class="header">Welcome to My Styled Page</h1>

    <!-- Image with class for styling -->
    <img src="https://images.pexels.com/photos/1234567/pexels-photo-1234567.jpeg" alt="Sample Image" class="styled-image">

    <!-- Paragraph with ID for styling -->
    <p id="intro-paragraph">This is an example of a paragraph that will be styled using an ID selector.</p>

    <!-- Div with class for styling -->
    <div class="content">
        <p>This is a content area styled using a class selector.</p>
    </div>
</body>
</html>


Styling with css
/* Styling for the header using a class selector */
.header {
    font-family: 'Arial, sans-serif';
    color: #333;
    text-align: center;
    margin-top: 20px;
}

/* Styling for the image using a class selector */
.styled-image {
    display: block;
    margin: 20px auto;
    border: 5px solid #ddd;
    padding: 10px;
    width: 50%;
}

/* Styling for the paragraph using an ID selector */
#intro-paragraph {
    font-family: 'Georgia, serif';
    color: #666;
    margin: 20px;
    padding: 10px;
    border: 1px solid #ccc;
}

/* Styling for the content div using a class selector */
.content {
    font-family: 'Verdana, sans-serif';
    background-color: #f9f9f9;
    margin: 20px;
    padding: 20px;
    border: 2px solid #eee;
}
 - Link an external CSS file.
 - Apply at least 3 different selectors.
 - Improve readability and aesthetics.

Happy Coding! 💻✨
