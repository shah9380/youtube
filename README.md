1. **HTML Structure:**
   
   Open the provided HTML code in a text editor (e.g., Visual Studio Code) and save it as an HTML file (e.g., `index.html`). Then, open the HTML file in a web browser (e.g., Google Chrome).

   In your browser, you can right-click on the webpage and select "Inspect" (or press `Ctrl + Shift + I` or `Cmd + Option + I` on macOS) to open the browser's developer tools.

   Now, you can navigate through the HTML structure and see how the tags are organized.

2. **Header Section:**

   - `<html>`: The root HTML element.
   - `<head>`: Contains metadata about the document.
   - `<meta>`: Defines document metadata like charset and viewport.
   - `<title>`: Sets the document title.
   - `<link>`: Links external resources (Google Fonts and CSS).
   - `<body>`: Contains the visible content of the webpage.
  
    ![header](https://github.com/shah9380/youtube/assets/130676464/95632404-e2a2-4175-9ab1-796fd10ed9dc)


3. **Header Content:**

   - `<div class="header">`: Represents the header section.
   - `<div class="header_left">`: Contains the left side of the header.
   - `<i class="material-icons">`: Material Icons for the menu.
   - `<img src="...">`: Image for the YouTube logo.
   - `<div class="header_search">`: Contains the search bar.
   - `<form>`: A form element for input and button.
   - `<input type="text">`: Input field for search.
   - `<button>`: Button for search.
   - `<div class="header_icons">`: Contains various icons.

4. **Main Section:**

   - `<div class="main">`: Represents the main content area.
   - `<div class="sidebar">`: The sidebar for navigation.
   - `<div class="videos">`: Section for displaying videos.

![main](https://github.com/shah9380/youtube/assets/130676464/97918b79-f637-422b-a35f-3eafdd00559d)

5. **Sidebar:**

   - `<div class="sidebar_categories">`: Container for sidebar categories.
   - `<div class="sidebar_category">`: Individual sidebar category.
   - `<span>`: Text within the sidebar categories.
   - `<hr>`: Horizontal line as a separator.

![sidebar](https://github.com/shah9380/youtube/assets/130676464/258b6dd8-ed20-4077-b0c9-482cab3a2db0)

6. **Video Section:**

   - `<h1>`: Heading for video section.
   - `<div class="videos_container">`: Container for displaying videos.
   - `<div class="video">`: Individual video container.
   - `<div class="video_thumbnail">`: Container for the video thumbnail.
   - `<img>`: Image for the video thumbnail.
   - `<div class="video_details">`: Container for video details.
   - `<div class="author">`: Container for the video author.
   - `<img>`: Image for the author's profile picture.
   - `<div class="title">`: Container for video title and information.
   - `<h3>`: Video title.
   - `<a>`: Video author's name.
   - `<span>`: Additional video information.

![video](https://github.com/shah9380/youtube/assets/130676464/baba4b75-1ec4-44bb-acfb-26b19ea90d19)
These are the key HTML tags used in the provided code to structure the YouTube clone webpage. You can use a web browser and its developer tools to explore the live HTML structure visually.

Certainly! Here's an explanation of some of the CSS properties used in the provided CSS (`style.css`) along with their purposes:

1. `*` Selector:
   - `margin: 0; padding: 0; box-sizing: border-box;`: This selector applies these styles to all elements, ensuring there is no default margin or padding around elements, and the `box-sizing` property is set to `border-box` to include padding and borders in the element's total width and height.

2. `body` Selector:
   - `font-family: 'Roboto', sans-serif;`: Sets the font family for the entire document to 'Roboto' with a fallback of a generic sans-serif font.

3. `.material-icons` Selector:
   - `color: rgb(96, 96, 96);`: Sets the color of elements with the class `.material-icons` to a shade of gray.

4. `.header` Selector:
   - `display: flex; justify-content: space-between; align-items: center; height: 70px; padding: 15px;`: Styles the header section to display as a flex container with specific alignment, height, and padding properties.

5. `.header_left` Selector:
   - `display: flex; align-items: center;`: Styles the left side of the header to be a flex container with centered alignment.

6. `.header_left img` Selector:
   - `width: 50px; margin-left: 10px;`: Sets the width and left margin of the image within the header's left section.

7. `.header_left i` Selector:
   - `padding: 0 10px; cursor: pointer;`: Styles the Material Icons in the header with padding and a pointer cursor.

8. `.header_search` Selector:
   - `border: 1px solid #ddd; height: 35px;`: Styles the search bar with a border and specific height.

9. `.header_search input` Selector:
   - `width: 500px; padding: 10px; margin: 0; height: 100%; border: none; border-radius: 0;`: Styles the search input field with specific width, padding, height, and border properties.

10. `.header_search button` Selector:
    - `padding: 0; margin: 0; height: 100%; border: none; border-radius: 0;`: Styles the search button with specific padding, height, and border properties.

11. `.main` Selector:
    - `display: flex; overflow: hidden; height: calc(100vh - 70px);`: Styles the main content area as a flex container with a specific height, and `overflow: hidden` hides content that overflows.

12. `.sidebar` Selector:
    - `height: 100%; width: 230px; background-color: white; overflow-y: scroll;`: Styles the sidebar with a specific width, background color, and vertical scroll overflow.

13. `.sidebar_categories` Selector:
    - `width: 100%; display: flex; flex-direction: column; margin-bottom: 15px; margin-top: 15px;`: Styles the sidebar categories container as a flex container with specific margins.

14. `.sidebar_category` Selector:
    - `display: flex; align-items: center; padding: 15px 25px;`: Styles individual sidebar categories as flex containers with centered alignment and padding.

15. `.sidebar_category span` Selector:
    - `margin-left: 15px;`: Adds left margin to text within sidebar categories.

16. `.sidebar_category:hover` Selector:
    - `background-color: #e5e5e5; cursor: pointer;`: Styles sidebar categories on hover with a background color change and pointer cursor.

17. `.sidebar::-webkit-scrollbar` Selector:
    - `display: none;`: Hides scrollbars in the sidebar when using WebKit-based browsers (like Chrome).

18. `.videos` Selector:
    - `background-color: #f9f9f9; width: 100%; height: 100%; overflow-y: scroll; padding: 15px 15px; border-top: 1px solid #ddd;`: Styles the videos section with a background color, padding, and scroll overflow.

19. `.videos_container` Selector:
    - `display: flex; flex-direction: row; justify-content: space-around; flex-wrap: wrap;`: Styles the video container as a flex container with specific layout properties.

20. `.video` Selector:
    - `width: 310px; margin-bottom: 30px;`: Styles individual video containers with specific width and margin.

21. `.video_thumbnail` Selector:
    - `width: 100%; height: 170px;`: Styles the video thumbnail container with a specific width and height.

22. `.video_thumbnail img` Selector:
    - `object-fit: cover; height: 100%; width: 100%;`: Styles video thumbnail images to cover their containers while maintaining aspect ratio.

23. `.author img` Selector:
    - `object-fit: cover; border-radius: 50%; height: 40px; width: 40px; margin-right: 10px;`: Styles author profile images with circular borders and specific dimensions.

24. `.title` Selector:
    - `display: flex; flex-direction: column;`: Styles the video title and information container as a flex container with a column layout.

25. `.title h3` Selector:
    - `color: rgb(3, 3, 3); line-height: 18px; font-size: 14px; margin-bottom: 6px;`: Styles video titles with specific text properties.

26. `.title a, span` Selector:
    - `text-decoration: none; color: rgb(96, 96, 96); font-size: 14px;`: Styles links and spans within video details with specific text properties.

27. `h1` Selector:
    - `font-size: 20px; margin-bottom: 10px; color: rgb(3, 3, 3);`: Styles the heading with specific font size, margin, and text color.

These CSS properties help define the layout, style, and appearance of the HTML elements on the YouTube clone webpage. They provide visual consistency and structure to the page.

[FEEL FREE TO EXPLORE](https://shah9380.github.io/youtube/)
