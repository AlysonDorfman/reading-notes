[Back to Homepage](https://alysondorfman.github.io/reading-notes/)

# Read: 05 - Understanding CSS Basics

## What is CSS?

Overview of Cascading Style Sheets (CSS)
Explanation of how CSS works
Introduction to CSS syntax and terminology

## What is CSS for?

Defining the purpose of CSS
Presentation of documents to users
Converting documents into a usable format
Role of web browsers in displaying content

# CSS Syntax

Understanding CSS as a rule-based language
Breakdown of CSS rules, including selectors, properties, and values
Examples illustrating CSS rule structures

## CSS Modules

Explanation of CSS modules and their purpose
Examples of common CSS modules (e.g., Backgrounds and Borders)
How modules organize and categorize CSS properties
V. CSS Specifications

Overview of CSS specifications
Role of standards organizations (e.g., W3C) in defining CSS standards
Ensuring backward compatibility while evolving CSS

## Browser Support Information

Significance of browser support for CSS features
Using the "Browser compatibility" table on MDN to check support
Considerations for cross-browser compatibility and version-specific issues

## Reading Questions Answered

1. Purpose of CSS:
CSS (Cascading Style Sheets) serves the following main purposes:
**Presentation:** CSS is used to control the presentation and styling of web documents, including fonts, colors, spacing, layout, and more. It enables you to define how HTML elements should be displayed on a web page, enhancing its visual appeal and user experience.
**Separation of Concerns:** CSS allows for the separation of content (HTML) and presentation (styling). This separation simplifies web development, making it easier to maintain and update websites, as changes to styling can be made without altering the content.
**Consistency:** CSS enables consistent styling across multiple web pages within a website or across different websites. By defining styles in a centralized manner, you can ensure a uniform look and feel throughout your web project.
**Accessibility:** CSS can be used to enhance accessibility by specifying how content is presented to users with disabilities or using assistive technologies. Proper use of CSS can improve readability and navigation for all users.

2. Three Ways to Insert CSS into Your Project:
CSS can be added to a web project in the following three ways:
Inline CSS: You can apply CSS directly within HTML elements using the style attribute. 

For example:

<p style="color: red;">This is a red paragraph.</p>
Internal CSS: CSS can be placed within the <style> element in the <head> section of an HTML document. This style information applies to the entire document. 

For example:

<!DOCTYPE html>
<html>
<head>
    <style>
        p {
            color: red;
        }
    </style>
</head>
<body>
    <p>This is a red paragraph.</p>
</body>
</html>

External CSS: You can create a separate CSS file with a .css extension and link it to your HTML document using the <link> element. This method allows you to apply the same styles across multiple web pages. For example, in a file named styles.css:
css

/* styles.css */
p {
    color: red;
}
In the HTML document:


\<!DOCTYPE html>
\<html>
\<head>
    <link rel="stylesheet" type="text/css" href="styles.css">
\</head>
\<body>
    \<p>This is a red paragraph.</p>
\</body>
\</html>

3. Example of a CSS Rule for Red Text in Paragraphs:
To make all <p> elements have red text, you can create the following CSS rule:

p {
    color: red;
}
This rule sets the color property to red for all \<p> elements, resulting in red text for all paragraphs in your HTML document.

