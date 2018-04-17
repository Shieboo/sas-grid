# sas-grid
> SAS framework is a 12 Column Grid Framework using CSS Grid.

#### It use:

* [Normalize.css v8.0.0](https://necolas.github.io/normalize.css/) to reset the styles.

* [SASS](http://sass-lang.com/) preprocessor to generate the CSS.

Just include the stylesheet ```style.css``` in the head of your html document:
```
<!DOCTYPE html>
<html lang="en">

<head>
  <meta charset="utf-8" http-equiv="content-type" content="text/html">
  <title>sas-grid</title>
  <link rel="stylesheet" href="../css/style.css" type="text/css" media="screen">
</head>

<body>
  <div class="container">
    <div class="sas-row">
      <div class="sas-col-3">
        25%
      </div>
      <div class="sas-col-6">
        50%
      </div>
      <div class="sas-col-3">
        25%
      </div>
    </div>
  </div>
</body>
</html>
```
Create a new row by adding the class ```sas-row``` and add column
by adding the class ```sas-col-#``` where # is a number between 1 and 12
(the sum of all 'column-size' should be equal to 12).

[Example Grid](https://shieboo.github.io/sas-grid/)
