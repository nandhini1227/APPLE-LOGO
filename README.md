HTML Structure:

<!DOCTYPE html>: Declares the document type and version of HTML being used.
<html>: The root element of the HTML document.
<head>: Contains meta-information about the HTML document, including the title.
<title>: Specifies the title of the HTML document displayed in the browser.
<style>: Contains the CSS code for styling the HTML elements.
<body>: Contains the content of the HTML document, which will be displayed in the browser.
  
CSS Styling:

Body Styling:

body: Sets the margin, padding, and background color for the entire document.

Container Styling:

.container: Sets the margin and maximum width for the container div.

Apple Logo Styling:

.apple: Represents the main apple shape.
Background color: silver.
Width: 208px, Height: 198px.
Position: Absolute.
Border-radius: Creates a rounded shape for the apple.

.apple::before: Represents a smaller circular shape on the apple.
Background color: silver.
Content: Empty content generated.
Width: 55px, Height: 55px.
Position: Absolute, positioned relative to the .apple.
Margin: Adjusts the position of the circular shape.
Border-radius: Creates a rounded shape for the circular element.
Z-index: Sets the stacking order of the element.
