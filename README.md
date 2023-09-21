# Media Queries Ass-9 CSS

## Project Description
The "Media Queries Project" is a responsive web page that showcases the use of media queries to adapt the layout and design for different screen sizes. It features a coffee-related content section with an image and text, along with a "Learn More" button.

## HTML Structure

### Container and Content Sections:
- `<main>`: The main content section.
  - `<div class="white-bg">`: White background header.
  - `<div class="container">`: Container for the content.
    - `<div class="content-wrapper">`: Wrapper for content alignment.
      - `<div class="image-box">`: Container for the background image.
      - `<div class="content-box">`: Container for text content.
        - `<h1>`: Heading for the content.
        - `<p>`: Paragraph text.
        - `<p>`: Paragraph text with a link.
        - `<a href="#" class="btn">`: Learn More button.

## CSS Styles

### Global Styles (`*`)
- `margin: 0;`: Resets margin for all elements.
- `padding: 0;`: Resets padding for all elements.
- `box-sizing: border-box;`: Ensures elements include padding and borders in their total width.
- `font-family: 'Open Sans', sans-serif;`: Specifies the default font for the entire document.

### Body and Typography Styles
- `font-family: 'Roboto', sans-serif;`: Specifies the font for headings.
- `img`: Sets the maximum width of images to 100%.

### Main Section (`main`)
- `width: 100%;`: Makes the main section span the entire width.
- `height: 100vh;`: Sets the main section's height to 100% of the viewport.
- `color: #111111;`: Sets the text color.
- `background-color: #f1c50e;`: Sets the background color.

### Container (`div.container`)
- `.container`:
  - `width: 80%;`: Sets the maximum width of the container.
  - `max-width: 1045px;`: Sets the maximum width of the container to 1045 pixels.
  - `margin: -80px auto;`: Centers the container vertically by adding negative margin.
  - `height: calc(100%-100px);`: Sets the height of the container.

### White Background Header (`div.white-bg`)
- `.white-bg`:
  - `width: 100%;`: Makes the white background header span the entire width.
  - `height: 100px;`: Sets the height of the header.
  - `background: white;`: Sets the background color to white.

### Content Wrapper (`div.content-wrapper`)
- `.content-wrapper`:
  - `width: 100%;`: Makes the content wrapper span the entire width.
  - `display: flex;`: Arranges items in a row.
  - `justify-content: center;`: Centers items horizontally.
  - `align-items: center;`: Centers items vertically.
  - `flex-wrap: wrap;`: Allows items to wrap to the next line on smaller screens.

### Image Box (`div.image-box`)
- `.image-box`:
  - `width: 50%;`: Sets the width of the image box.
  - `max-width: 500px;`: Sets the maximum width of the image box.
  - `height: 590px;`: Sets the height of the image box.
  - `background: url(/images/person-serving-cup-coffee_1286-227.jpg);`: Sets the background image.
  - `background-position: 50% 50%;`: Centers the background image.

### Content Box (`div.content-box`)
- `.content-box`:
  - `width: 50%;`: Sets the width of the content box.
  - `padding: 80px 30px 0 30px;`: Sets padding for the content box.
  - `text-align: center;`: Centers text content.
  - `height: max-content;`: Adjusts the height to fit content.

### Heading Styles (`h1`)
- `font-size: 3.125rem;`: Sets the font size.
- `font-weight: 700;`: Sets the font weight.

### Paragraph Styles (`p`)
- `font-size: 1.25rem;`: Sets the font size.
- `font-weight: 700;`: Sets the font weight.

### Link Styles (`a`)
- `color: #111111;`: Sets the link color.

### Button Styles (`.btn`)
- `color: #ffffff;`: Sets the text color.
- `background: #000000;`: Sets the background color.
- `text-decoration: none;`: Removes underlines from links.
- `padding: 10px 57px;`: Sets padding for the button.


