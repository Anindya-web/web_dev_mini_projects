**Little Lemon Restaurant Reservation Page**

This is the code for a simple restaurant reservation page called "Little Lemon." It allows users to book a table for either 2, 4, or 6 people, and to choose between indoor or outdoor seating.

**Technologies Used:**

HTML: Provides the basic structure and content of the webpage.
CSS: Styles the layout, appearance, and user interface elements of the webpage.

**Functionality:**

- Users can select a table size (2, 4, or 6 persons) using radio buttons.
- The default selection is a 4-person table.
- Users can choose their preferred seating location (indoor or outdoor) using radio buttons.
- The default selection is indoor seating.
- A "Book Table" button submits the form (functionality not implemented in this code).

**HTML Structure:**

- The code uses basic HTML elements to create the page structure:
  - `DOCTYPE html`: Declares the document type as HTML.
  - `<html>`: The root element of the HTML document.
  - `<head>`: Contains meta information about the page.
    - `<meta charset="UTF-8">`: Defines the character encoding as UTF-8.
    - `<meta name="viewport" content="width=device-width, initial-scale=1.0">`: Makes the page responsive to different screen sizes.
    - `<link rel="stylesheet" href="styles.css">`: Links to an external stylesheet (not included in this code).
    - `<title>Little Lemon</title>`: Sets the title of the page.
  - `<body>`: Contains the visible content of the page.
    - `<header>`: Likely contains the restaurant logo (not implemented in this code).
    - `<main>`: The main content area of the page.
      - `<h1>Book a Table</h1>`: Heading for the reservation form.
      - `<form>`: The reservation form.
        - `<fieldset id="table_size">`: Fieldset for table size selection.
          - Three radio buttons for table sizes 2, 4 (default), and 6.
        - `<fieldset id="location">`: Fieldset for seating location selection.
          - Two radio buttons for indoor (default) and outdoor seating.
        - `<button type="submit">Book Table</button>`: Submit button for the form.

**Dependencies:**

- This code relies on an external stylesheet (`styles.css`) to style the page elements (not included here).

**CSS Structure:**

**General Styles**

* **Background Color:** The body background color is set to a light gray (#E0E0E2).
* **Unordered Lists:** Unordered lists have no bullet points (`list-style-type: none;`), are centered (`text-align: center;`), and have no padding (`padding: 0px;`).
* **List Items:** List items are displayed inline (`display: inline;`).
* **Text Alignment:** `main` and `footer` elements are centered (`text-align: center;`).

**Headings**

* `h1` and `h2` elements have a maroon color (#721817).

**Custom Class**

* The `.center-text` class centers the text within the element (`text-align: center;`).

**Images**

* Images are displayed as block elements (`display: block;`).
* Images are horizontally centered using `margin-left: auto;` and `margin-right: auto;`.

**Specific Styles**

* Inline spans within `h2` elements have an orange color (#FA9F42) and a smaller font size (0.75em).
* Form elements within a `div` have a top and bottom margin of 0.5em (`margin-top: 0.5em; margin-bottom: 0.5em;`).
* The `#copyright` element has a top padding of 12px and a smaller font size (0.75em).

**Validation Styles**

* Input fields with invalid input when focused will turn red and have a red border (3px solid).
