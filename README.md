# Simplify App

![](https://github.com/angelsjiang/Simplify/blob/main/logo.png)

# Basic Contents
## [HTML content](https://github.com/angelsjiang/Simplify/blob/main/index.html)

- Text headers
- Paragraphs
- Horizontal ruler
- List
- Images with descriptive alt attributes
- Divider
- Text span

## [CSS styling](https://github.com/angelsjiang/Simplify/blob/main/assets/style.css)

- Modified background color
```css
.nav-link.dropdown-toggle {
    background-color: #fba094;
    font-weight: bold;
}
```

- Modified padding and margins
```css
body {
    padding-top: 70px;
    margin-left: 10%;
    margin-right: 10%;
    padding-bottom: 100px;
}
```

- Google Fonts
```html
<!-- Google Fonts -->
        <link rel="preconnect" href="https://fonts.gstatic.com">
        <link href="https://fonts.googleapis.com/css2?family=Limelight&display=swap" rel="stylesheet">
        <link href="https://fonts.googleapis.com/css2?family=Roboto&display=swap" rel="stylesheet">
        <link href="https://fonts.googleapis.com/css2?family=Lato&display=swap" rel="stylesheet">
```
```css
font-family: 'Roboto', sans-serif;
font-family: 'Limelight', cursive;
font-family: 'Lato', sans-serif;
```

## Advance features
- A table with multiple columns and rows
```html
<table class="table">
    <thead class="table-subheader" id="t">
        <tr>
            <th scope="col" id="c">Categories/Names</th>
            <th scope="col" id="f">Flipp</th>
            <th scope="col" id="g">Grocery Pal</th>
            <th scope="col" id="r">Ralphs</th>
        </tr>    
    </thead>
    <tbody>
        <tr>
            <th scope="row">Direct Competitor</th>
            <td>✓</td>
            <td>✓</td>
            <td></td>
        </tr>
        ...
```
- Navigation bar
```html
<!-- Navbar -->
    <nav class="navbar fixed-top navbar-expand-lg navbar-light">
        <div class="container-fluid">
            <a href="./index.html"><span class="navbar-brand mb-0 h1">SIMPLIFY</span></a>
            <button class="navbar-toggler" type="button" data-bs-toggle="collapse" data-bs-target="#navbarSupportedContent" aria-controls="navbarSupportedContent" aria-expanded="false" aria-label="Toggle navigation">
                <span class="navbar-toggler-icon"></span>
            </button>
            ...
```
- Video
```html
    <video controls>
        <source src="./resources/demo.mp4" type="video/mp4">
        Demo video for Simplify application.<br>
        Your browser does not support HTML5 video.
    </video>
    ...
```

# Online resources links

- [How to write a ux case study](https://www.invisionapp.com/inside-design/how-to-write-a-ux-case-study/)
- [Top 10 most interesting UX design case](https://medium.muz.li/top-10-most-interesting-ux-design-case-studies-to-inspire-your-service-reinvention-in-2018-ea2309e4104b)
- [Fitbit a usability case study](https://uxdesign.cc/fitbit-a-usability-case-study-b23e4c539c3c)
- [UX research is boring and nobody reads it](https://blog.prototypr.io/ux-research-is-boring-and-nobody-reads-it-668edbfc804a)
- [Design basics annotating your work](https://medium.com/wayfair-design/design-basics-annotating-your-work-6eac0562097f)
- [How to rate the serverity of usability problems](https://www.nngroup.com/articles/how-to-rate-the-severity-of-usability-problems/)
- [Ten usability heuristics](https://www.nngroup.com/articles/ten-usability-heuristics/)
- [Android Material Design Guidelines - Theming](https://material.io/develop/android)
- [Android Material Design Guidelines - Material Foundation](https://material.io/design)
- [Android Material Design Guidelines - Components](https://material.io/components)
- [Moms’ Shopping Habits and Their Path to Purchase [Infographic]](https://www.fluentco.com/blog/moms-shopping-habits/)

# Other consulted list
- Professor, Matt Bietz
- TA, Agnes Romhanyi
- TA, Dennis Wang
