# Web Typography Vibes

## Goals

Learn fundamental and accessible web typography practices by creating a scheme with good contrasting font families and colors.

## Learning Objectives

Learn how to write CSS to modify the following properties by creating a typography scheme with CSS variables (`var()`) defined in the `:root {}`:

1. Font Types and Families
2. Importing fonts with `@import url();`
3. Building contrast with font colors, sizing, weights, line height, and style.
4. Building contrast with background and foreground colors.

## Instructions

### 1. Complete the two style guides

1. Copy and rename the `tocopy` folder with your lastname. Be sure that it is in the root of the `3-typography` folder.
2. Read and review the HTML file.
3. Read and review the CSS file.
4. Develop two "vibes" with the respective HTML and CSS files.
5. Once you create the vibes, name them and use that name to rename the files respectively with the following prepended scheme: `style-guide-vibenamehere.html` and `style-guide-vibenamehere.css`.

### 2. Create two 'vibe' pages of your own with the scheme's CSS code

1. In the root of your personal folder, create two new HTML files with the following naming scheme: `vibename.html`.
2. In your personal `style` folder, create two new CSS files: `vibename.css`.
3. Create a simple HTML page for each 'vibe'.
4. Copy and paste the scheme from your style guide to the respective CSS file.
5. Apply any classes from your CSS stylesheet to elements, such as links.
6. Add any and all additional classes/styles to your new pages AFTER the typography scheme code. Document the part of the CSS code with a new comment heading.
  - EXAMPLE: You apply a max-width on the main element with a `margin:auto` horizontal centering rule.
    ```css
    /* ... typography schem code above this code, since the scheme acts as a new general 'default' for the page. */
    /*======
      MAIN
    =======*/
    main {
      max-width: 800px;
      margin: auto;
    }
    ```