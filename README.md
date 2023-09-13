# flipkart
https://tanishka-khamesara.github.io/flipkart/flipkart.html



![Screenshot (43)](https://github.com/Tanishka-khamesara/flipkart/assets/127411985/0db8daf7-6aee-465f-b218-2aaf87f66206)
![Screenshot (44)](https://github.com/Tanishka-khamesara/flipkart/assets/127411985/65bc9b3d-e636-4124-9455-bbb2951116e9)
![Screenshot (45)](https://github.com/Tanishka-khamesara/flipkart/assets/127411985/bcd433cb-99a6-4019-a4f9-dd9deaade901)
![Screenshot (46)](https://github.com/Tanishka-khamesara/flipkart/assets/127411985/0a863319-a292-43d3-9c8a-5b78ce05d123)
![Screenshot (47)](https://github.com/Tanishka-khamesara/flipkart/assets/127411985/95b15239-fd3f-4e2b-ac9c-4cbf40ab17cd)
![Screenshot (48)](https://github.com/Tanishka-khamesara/flipkart/assets/127411985/88cca9a2-f53b-4981-922e-2c4236aa3e05)

<!DOCTYPE html>: This is the document type declaration, which specifies that the document is an HTML5 document.

<html lang="en">: This is the opening <html> tag, which encloses the entire HTML document. The lang attribute is set to "en" to specify that the document is in English.

<head>: This is the opening <head> tag, which contains metadata about the document and links to external resources like stylesheets and scripts.

<meta charset="UTF-8">: This <meta> tag defines the character encoding for the document as UTF-8, which is a widely used character encoding for web pages.

<meta name="viewport" content="width=device-width, initial-scale=1.0">: This <meta> tag sets the viewport settings for the page, ensuring that the page is displayed correctly on various devices with different screen sizes. It sets the initial scale to 1.0, meaning that the page should be displayed at its actual size on mobile devices.

<title>flipkart</title>: This <title> tag specifies the title of the web page, which is displayed in the browser's title bar or tab.

<link href="./styles.css" rel="stylesheet">: This <link> tag links an external CSS (Cascading Style Sheets) file named "styles.css" to the HTML document. It's used to apply styles to the HTML elements.

</head>: This is the closing </head> tag, which marks the end of the document's head section.

<body>: This is the opening <body> tag, which contains the content that is displayed in the web page's main area.

<div class="bg">: This <div> element has a class attribute set to "bg." Classes are used to apply CSS styles to elements with this class. In this case, it's likely used to style a background element.

<div class="blue">: Another <div> element with a class attribute set to "blue." It's probably used to style a blue-colored section of the web page.

<div class="navbar">: This <div> element with the class "navbar" represents a navigation bar or menu.

Inside the navigation bar, there are several child elements, including an SVG (Scalable Vector Graphics) image, a "Explore Plus" text with a yellow-colored span, a search input field with an SVG search icon, a "Login" button, "Become a Seller" text, a "More" text with an SVG icon, and a shopping cart icon.

Throughout the code, you can see the use of SVG (Scalable Vector Graphics) for images. SVG allows for high-quality, scalable graphics on web pages.

The <p> and <em> elements are used for text formatting, where <em> is used for emphasizing text.

<input type="text" placeholder="Search for products, brands and more"/>: This is an input field of type "text" used for searching. It has a placeholder attribute that displays a hint text inside the input field.

<button>Login</button>: This is a button element with the label "Login." It's typically used for user authentication.

The code also includes some inline SVG icons for visual elements like a search icon, a shopping cart icon, and a "More" icon.

The document structure is closed with closing </div>, </body>, and </html> tags.
Overall, this HTML code represents a basic structure for a web page with navigation elements, a search bar, and various icons. The styles for these elements are likely defined in an external CSS file referenced in the <link> tag in the <head> section.




![Screenshot (49)](https://github.com/Tanishka-khamesara/flipkart/assets/127411985/e45810f2-e80b-4ee7-9a98-42d7e8bfe918)
![Screenshot (50)](https://github.com/Tanishka-khamesara/flipkart/assets/127411985/c4f9c7aa-d5f9-41d1-a919-9327974c574e)
![Screenshot (51)](https://github.com/Tanishka-khamesara/flipkart/assets/127411985/e21b90bb-bbde-4397-8e19-1f00ccbb4056)
![Screenshot (52)](https://github.com/Tanishka-khamesara/flipkart/assets/127411985/a0c40d93-109a-4efd-944d-24f2906d7409)
The provided CSS code contains styles that define the appearance and layout of elements in an HTML document. Here's an explanation of the CSS code:

*: This is a universal selector, which selects all HTML elements on the page. It's used to apply styles to all elements.

margin: 0;: This sets the margin of all elements to zero, removing any default margins that might be applied by the browser.

box-sizing: border-box;: This changes the box-sizing model to "border-box" for all elements. It means that the total width and height of an element includes padding and borders, not just the content. This can help with consistent sizing and layout.

font-family: 'Trebuchet MS', 'Lucida Sans Unicode', 'Lucida Grande', 'Lucida Sans', Arial, sans-serif;: This sets the default font family for all elements to a list of fonts. If the first font ('Trebuchet MS') isn't available, the browser will use the next one in the list, and so on.

.blue: This is a class selector, which selects elements with the class "blue."

background-color: #3D71E7;: This sets the background color of elements with the "blue" class to a shade of blue (#3D71E7).

height: 60px;: It sets the height of these elements to 60 pixels.

display: flex;: This makes the elements use a flexbox layout, allowing for easy alignment and positioning of child elements.

justify-content: flex-start;: This aligns the child elements to the start of the container (left in a left-to-right context).

align-items: center;: This vertically centers the child elements within the container.

.navbar: This is a class selector for elements with the class "navbar."

margin-left: 100px;: It sets a left margin of 100 pixels for these elements.

display: flex;: This makes the elements use a flexbox layout.

align-items: center;: It vertically centers the child elements within the container.

.navbar > svg: This is a descendant selector, selecting SVG elements that are direct children of elements with the class "navbar."

margin-top: 6px;: It adds a top margin of 6 pixels to these SVG elements.

margin-left: 4px;: It adds a left margin of 4 pixels to these SVG elements.

height: 1.3rem;: It sets the height of these SVG elements to 1.3 times the font size, creating responsive sizing.

fill: rgb(255, 255, 255);: It sets the fill color of these SVG elements to white, changing their color.

.explore: This is a class selector for elements with the class "explore."

display: flex;: It uses a flexbox layout for these elements.
.explore > p: This selects <p> elements that are direct children of elements with the class "explore."

color: white;: It sets the text color of these <p> elements to white.

font-size: 12px;: It sets the font size of these <p> elements to 12 pixels.

margin-left: 62px;: It adds a left margin of 62 pixels to these <p> elements.

margin-right: 5px;: It adds a right margin of 5 pixels to these <p> elements.

.yellow: This is a class selector for elements with the class "yellow."

color: yellow;: It sets the text color of these elements to yellow.
The CSS code continues with styles for other elements, including the search bar, login button, "Become a Seller" text, icons, and more. Each class selector or element selector is followed by a set of style declarations that define how the selected elements should be displayed on the web page. These styles include properties like colors, margins, font sizes, and positioning.
