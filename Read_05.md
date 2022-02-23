So you have 3 ways of adding CSS
- External CSS
- Internal CSS
- Inline CSS

<link rel="stylesheet" href="mystyle.css">
so link it to an outside folder 

or use it directly on the elements within the sheet 
body {
  background-color: linen;
}

h1 {
  color: maroon;
  margin-left: 40px;
}
</style>
</head>
<body>

or "inline" which is simply using it element by element 

<h1 style="color:blue;text-align:center;">This is a heading</h1>
<p style="color:red;">This is a paragraph.</p>

If some properties have been defined for the same selector (element) in different style sheets, the value from the last read style sheet will be used. 

so 
<link rel="stylesheet" type="text/css" href="mystyle.css">  is for the entire sheet its not a specific thing even though its above the body? weird 

#################
<!DOCTYPE html>
<html>
<head>
<style>

h1 {
  color: orange;
}
</style>
<link rel="stylesheet" type="text/css" href="mystyle.css">
</head>
<body>

<h1>This is a heading</h1>
<p>The style of this document is a combination of an external stylesheet, and internal style</p>

</body>
</html>

now that you have moved the link down it 
will do the latest style and your h1 for the orange wont matter 
###################


# Colors

so you

body {
  color: hsl(89, 01%, 51%);
}

