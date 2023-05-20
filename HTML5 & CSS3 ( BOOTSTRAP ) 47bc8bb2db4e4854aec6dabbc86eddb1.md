# HTML5 & CSS3 ( BOOTSTRAP )

![HTML55.png](HTML5%20&%20CSS3%20(%20BOOTSTRAP%20)%2047bc8bb2db4e4854aec6dabbc86eddb1/HTML55.png)

## **WHAT'S NEW ON HTML 5**

HTML5 introduced several new features and improvements over its predecessor, HTML4. Here are some notable advancements:

1. **Semantic Elements**: HTML5 introduced a set of semantic elements that provide clearer structure and meaning to web page content. Examples include `<header>`, `<nav>`, `<section>`, `<article>`, `<footer>`, etc. These elements help improve accessibility, SEO, and code readability.
2. **Audio and Video Support**: HTML5 added native support for embedding audio and video content without the need for third-party plugins like Flash. The `<audio>` and `<video>` elements allow developers to include media files directly into web pages and control playback using JavaScript.
3. **Canvas**: HTML5 introduced the `<canvas>` element, which enables dynamic rendering of graphics, animations, and interactive visualizations using JavaScript. It provides a powerful 2D drawing API that allows developers to create games, data visualizations, and other rich graphical content.
4. **Form Enhancements**: HTML5 introduced new input types, such as date, time, email, URL, number, and range, making form handling more robust and user-friendly. Additionally, new attributes like `placeholder`, `required`, and `pattern` were introduced to enhance form validation and user experience.
5. **Offline Web Applications**: HTML5 introduced the Application Cache (AppCache) feature, allowing developers to create web applications that can be accessed offline. By defining a cache manifest file, developers can specify which files should be stored locally, enabling users to interact with web apps even without an internet connection.
6. **Geolocation**: HTML5 introduced a Geolocation API that allows web applications to access a user's location information with their consent. This enables developers to create location-aware applications and provide personalized experiences based on a user's geographic position.
7. **Web Storage**: HTML5 introduced the Web Storage API, which provides a way to store data locally in the user's browser. It offers two mechanisms: `localStorage` for persistent storage and `sessionStorage` for temporary storage, allowing web applications to store and retrieve data without relying on server-side solutions like cookies.
8. **Drag and Drop**: HTML5 introduced native support for drag-and-drop interactions, making it easier to implement intuitive user interfaces. Developers can use the drag and drop API to enable dragging elements within a web page or between different applications.

*These are just a few of the many new features and improvements introduced in HTML5. Overall, HTML5 aimed to enhance the capabilities of web development, promote standardized practices, and provide a more seamless and interactive web browsing experience.*

![images (40).jpeg](HTML5%20&%20CSS3%20(%20BOOTSTRAP%20)%2047bc8bb2db4e4854aec6dabbc86eddb1/images_(40).jpeg)

## WHAT'S NEW ON CSS 3

CSS3, the latest version of Cascading Style Sheets (CSS), introduced a wide range of new features and enhancements to the styling capabilities of web pages. Here are some notable advancements:

1. **Selectors**: CSS3 introduced several new selector types, expanding the ways elements can be targeted and styled. These include attribute selectors, :nth-child(), :nth-last-child(), :first-child, :last-child, :only-child, :not(), :checked, :enabled, :disabled, :required, and more. These selectors allow for more precise and complex styling rules.
2. **Box Model**: CSS3 introduced the `box-sizing` property, which provides control over how the width and height of elements are calculated. The `box-sizing` property can be set to `content-box` (default), where the width and height include only the content, or `border-box`, where the width and height include the content, padding, and border.
3. **Backgrounds and Borders**: CSS3 introduced new properties and options for background styling and border effects. Some notable additions include multiple backgrounds using `background-image`, `background-size`, `background-origin`, and `background-clip`. Border properties like `border-radius`, `border-image`, and `box-shadow` allow for more intricate and visually appealing borders.
4. **Transitions and Animations**: CSS3 introduced the `transition` property, which enables smooth transitions between different property values over a specified duration. Additionally, CSS3 introduced the `animation` property, allowing the creation of complex animations with keyframes, timing functions, and animation properties.
5. **Flexbox and Grid Layout**: CSS3 introduced two powerful layout modules: Flexbox and CSS Grid Layout. Flexbox provides a flexible way to create responsive and dynamic layouts, while CSS Grid Layout allows for grid-based designs with precise control over rows, columns, and item placement.
6. **Media Queries**: CSS3 introduced media queries, which enable responsive web design by allowing styles to be applied based on the characteristics of the device or viewport. Media queries allow developers to specify different styles for different screen sizes, resolutions, orientations, and more.
7. **Typography**: CSS3 introduced several new properties for advanced typography, including `text-shadow`, `text-overflow`, `word-wrap`, `text-justify`, and `font-face`, which allows custom fonts to be used on websites.
8. **Transforms and Transitions**: CSS3 introduced 2D and 3D transformation properties (`transform`, `translate`, `scale`, `rotate`, `skew`) that enable the manipulation of elements in 2D and 3D space. CSS3 also introduced the `transition` property to create smooth transitions between different element states.
9. **Custom Properties (CSS Variables)**: CSS3 introduced custom properties, also known as CSS variables, which allow developers to define reusable values that can be used throughout the CSS code. This provides flexibility and easier maintenance by centralizing the values in one place.

*CSS3 brought significant improvements and expanded the capabilities of CSS, empowering developers to create more sophisticated and engaging web designs with less reliance on external tools or JavaScript.*

### More on CSS 3 Selectors

1. **Attribute Selectors**: CSS3 introduced attribute selectors that allow you to select elements based on their attributes. For example, `[attribute]` selects elements with the specified attribute, `[attribute="value"]` selects elements with the attribute and matching value, and `[attribute^="value"]` selects elements where the attribute starts with the specified value.
2. :**nth-child() and :nth-of-type()**: These selectors allow you to select elements based on their position within a parent element. `:nth-child(n)` matches elements that are the nth child of their parent, while `:nth-of-type(n)` matches elements that are the nth child of their type within the parent.

```css
/* Selects elements that are the nth child of their parent */
:nth-child(n) {
  /* Styles */
}

/* Selects elements that are the nth child of their type within the parent */
:nth-of-type(n) {
  /* Styles */
}
```

1. :**not**(): The `:not()` selector allows you to select elements that do not match a specific selector. For example, `:not(.class)` selects elements that do not have the specified class.

```css
/* Selects elements that do not have the specified class */
:not(.class) {
  /* Styles */
}
```

1. :**first-child**, :**last-child**, :**only-child**: These selectors target elements based on their relationship with their parent. `:first-child` selects the first child element, `:last-child` selects the last child element, and `:only-child` selects elements that are the only child of their parent.

```css
/* Selects the first child element */
:first-child {
  /* Styles */
}

/* Selects the last child element */
:last-child {
  /* Styles */
}

/* Selects elements that are the only child of their parent */
:only-child {
  /* Styles */
}
```

1. :**empty**: The `:empty` selector targets elements that have no children or text content. It can be useful for styling or selecting specific elements that don't contain any content.

```css
/* Selects elements that have no children or text content */
:empty {
  /* Styles */
}
```

1. :**checked**, :**enabled**, :**disabled**, :**required**: These selectors target form elements based on their states. `:checked` selects checked radio buttons or checkboxes, `:enabled` selects enabled form elements, `:disabled` selects disabled form elements, and `:required` selects required form elements.

```css
/* Selects checked radio buttons or checkboxes */
:checked {
  /* Styles */
}

/* Selects enabled form elements */
:enabled {
  /* Styles */
}

/* Selects disabled form elements */
:disabled {
  /* Styles */
}

/* Selects required form elements */
:required {
  /* Styles */
}
```

1. :**target**: The `:target` selector matches the targeted element in a URL fragment identifier (anchor link). It can be used to apply specific styles to the targeted element.

```css
/* Selects the targeted element in a URL fragment identifier */
:target {
  /* Styles */
}
```

1. ::**selection**: The `::selection` selector targets the portion of text that a user has selected on the page. It allows you to style the selected text.

```css
/* Styles the selected text */
::selection {
  /* Styles */
}
```

These CSS3 selectors provide more granular control over element targeting, allowing us to apply styles to specific elements based on their attributes, position, relationship with parents, or states. They enhance the versatility of CSS and enable more precise styling and customization of web pages.

![bootstrap-social.png](HTML5%20&%20CSS3%20(%20BOOTSTRAP%20)%2047bc8bb2db4e4854aec6dabbc86eddb1/bootstrap-social.png)

## BOOTSTRAP

From working with Bootstrap, i have learned the following:

1. **Responsive Design**: Bootstrap emphasizes responsive web design, allowing us to create websites that adapt to different screen sizes and devices. I learned how to use Bootstrap's grid system and responsive utility classes to build responsive layouts that automatically adjust and stack content based on the viewport size.

### Example : Responsive Container’s

- **A**

```html
<div class="container-sm">100% wide until small breakpoint</div>
<div class="container-md">100% wide until medium breakpoint</div>
<div class="container-lg">100% wide until large breakpoint</div>
<div class="container-xl">100% wide until extra large breakpoint</div>
<div class="container-xxl">100% wide until extra extra large breakpoint</div>
```

- **B**

```html
<div class="container text-center">
  <div class="row">
    <div class="col">
      Column
    </div>
    <div class="col">
      Column
    </div>
    <div class="col">
      Column
    </div>
  </div>
</div>
```

1. **CSS Components**: Bootstrap provides a wide range of pre-built CSS components, such as navigation bars, buttons, forms, modals, carousels, and more. By using these components, I learned how to quickly and easily incorporate common UI elements into our website without having to build them from scratch.

### Example : Navigation Bar

- **A**

```html
<nav class="navbar navbar-expand-lg bg-body-tertiary">
  <div class="container-fluid">
    <a class="navbar-brand" href="#">Navbar</a>
    <button class="navbar-toggler" type="button" data-bs-toggle="collapse" data-bs-target="#navbarSupportedContent" aria-controls="navbarSupportedContent" aria-expanded="false" aria-label="Toggle navigation">
      <span class="navbar-toggler-icon"></span>
    </button>
    <div class="collapse navbar-collapse" id="navbarSupportedContent">
      <ul class="navbar-nav me-auto mb-2 mb-lg-0">
        <li class="nav-item">
          <a class="nav-link active" aria-current="page" href="#">Home</a>
        </li>
        <li class="nav-item">
          <a class="nav-link" href="#">Link</a>
        </li>
        <li class="nav-item dropdown">
          <a class="nav-link dropdown-toggle" href="#" role="button" data-bs-toggle="dropdown" aria-expanded="false">
            Dropdown
          </a>
          <ul class="dropdown-menu">
            <li><a class="dropdown-item" href="#">Action</a></li>
            <li><a class="dropdown-item" href="#">Another action</a></li>
            <li><hr class="dropdown-divider"></li>
            <li><a class="dropdown-item" href="#">Something else here</a></li>
          </ul>
        </li>
        <li class="nav-item">
          <a class="nav-link disabled">Disabled</a>
        </li>
      </ul>
      <form class="d-flex" role="search">
        <input class="form-control me-2" type="search" placeholder="Search" aria-label="Search">
        <button class="btn btn-outline-success" type="submit">Search</button>
      </form>
    </div>
  </div>
</nav>
```

1. **Cross-Browser Compatibility**: Bootstrap is designed to be compatible with various web browsers, ensuring consistent and reliable rendering across different platforms. By using Bootstrap, I have gained knowledge about building websites that work well across different browsers and versions, reducing the need for extensive cross-browser testing and troubleshooting.

![pngegg.png](HTML5%20&%20CSS3%20(%20BOOTSTRAP%20)%2047bc8bb2db4e4854aec6dabbc86eddb1/pngegg.png)

1. **Rapid Prototyping**: Bootstrap's ready-to-use components and responsive grid system enable rapid prototyping of websites and web applications. I learned how to leverage Bootstrap's tools to quickly create prototypes, test ideas, and iterate on our designs, speeding up the development process.

```html
<div class="grid text-center">
  <div class="g-col-4">.g-col-4</div>
  <div class="g-col-4">.g-col-4</div>
  <div class="g-col-4">.g-col-4</div>
</div>
```

1. **Mobile-First Approach**: Bootstrap encourages a mobile-first approach to design, prioritizing the development of mobile-friendly websites and then progressively enhancing them for larger screens. I have learned how to structure my code and use Bootstrap's responsive classes to create mobile-optimized experiences that scale up for desktop and tablet devices.
    
    
    | Breakpoint | Class infix | Dimensions |
    | --- | --- | --- |
    | Extra small | None | <576px |
    | Small | sm | ≥576px |
    | Medium | md | ≥768px |
    | Large | lg | ≥992px |
    | Extra large | xl | ≥1200px |
    | Extra extra large | xxl | ≥1400px |

*Working with Bootstrap provides a solid foundation in front-end web development, equipping with responsive design skills, a library of reusable components, and a community-driven ecosystem that can accelerate our development process.*