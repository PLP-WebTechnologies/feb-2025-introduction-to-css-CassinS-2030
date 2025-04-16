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
 - Link an external CSS file.
 - Apply at least 3 different selectors.
 - Improve readability and aesthetics.

Happy Coding! 💻✨


/* Style for the body */
body {
    font-family: 'Arial', sans-serif;  /* Different font */
    background-color: #f4f4f4;
    margin: 0;
    padding: 0;
}

/* Style for an element with the class 'header' */
.header {
    background-color: #3498db;  /* Blue background */
    color: white;
    text-align: center;
    padding: 20px;
    font-size: 24px;
}

/* Style for an element with the ID 'content' */
#content {
    margin: 30px;
    padding: 20px;
    background-color: #fff;
    border: 2px solid #3498db;
    border-radius: 10px;
}

/* Style for a paragraph inside 'content' */
#content p {
    font-size: 18px;
    line-height: 1.6;
    color: #333;
}

/* Style for images */
img {
    width: 100%;  /* Make images responsive */
    max-width: 500px;
    border: 5px solid #3498db; /* Border around the image */
    border-radius: 10px;
    margin: 20px 0;
}


<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Styled Page</title>
    <link rel="stylesheet" href="style.css">  <!-- Linking the external CSS file -->
</head>
<body>

    <div class="header">
        <h1>Welcome to My Styled Page</h1>
    </div>

    <div id="content">
        <h2>This is the content section</h2>
        <p>This is a paragraph inside the content section. It has some styling applied to it like margins, padding, and borders.</p>

        <!-- Styled image -->
        <img src="https://via.placeholder.com/500" alt="Placeholder Image">

        <p>Here is another paragraph. Notice how the margins and paddings make the content look spaced out and well-aligned.</p>
    </div>

</body>
</html>

