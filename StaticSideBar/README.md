# SideBar Technical Documentation

## This document will be updated over time to reflect improvements applied to the template.

To start with, this is a sample of what the end product will look like, obviously with the new details added of the user.
<img src="img/billboard-demo.png"/>

### Technologies

- \*HTML
- \*CSS
- \*JavaScript

### Initial Change

Once successfully downloaded, you'll need to change the Name of the file within the "Title" tags shown in the code snippet below, from Static Site 01 to the name of your site.

```html
<html>
  <head>
    <meta charset="utf-8" />
    <meta http-equiv="X-UA-Compatible" content="IE=edge" />
    <title>Static Site 01</title>
  </head>
</html>
```

Following this, you'd then need to change the Profile Image within the `img scr=` tags also Name between the `<h3>` tags shown in the code block below.

```html
<body>
  <!--[if lt IE 7]>
    <p class="browsehappy">
      You are using an <strong>outdated</strong> browser. Please
      <a href="#">upgrade your browser</a> to improve your experience.
    </p>
  <![endif]-->
  <div id="wrapper">
    <!-- START OF SIDEBAR -->
    <div id="sideBar" class="sidebar">
      <section id="developerImage" class="devImg" alt="Developer Image">
        <img
          src="https://images.unsplash.com/photo-1511367461989-f85a21fda167?ixlib=rb-4.0.3&ixid=MnwxMjA3fDB8MHxzZWFyY2h8Mnx8cHJvZmlsZXxlbnwwfHwwfHw%3D&w=1000&q=80"
          alt="Alvan Chance"
          width="1000"
          height="563"
        />
      </section>
      <h3>Alvan Chance</h3>
    </div>
  </div>
</body>
```
