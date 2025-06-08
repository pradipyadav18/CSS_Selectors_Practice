<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta http-equiv="X-UA-Compatible" content="IE=edge" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>CSS Assignment</title>
  <link rel="stylesheet" href="Assignment.css">
</head>
<body>

  <h1 id="mainTopic" class="Georgia">CSS Practice</h1>
  <h3  class="Georgia">Let's learn about selectors.</h3>

  <!-- Paragraph 1 -->
  <p>There are multiple selectors in CSS.</p>

  <!-- Paragraph 2 -->
  <p>Some of them include class selector, id selector, etc.</p>

  <!-- Paragraph 3 -->
  <p>And we can also combine these too.</p>

  <div>
   

    <h5  class="Georgia">Did you like the practice set?</h5>
    <input type="checkbox" id="yes" />
    <label for="yes">Yes</label><br />

    <button>Learn next!</button>
  </div>

</body>
</html>

 

///CSS FIle



#mainTopic{
    color: blue;
}

*{
    text-align: center;
}

.Georgia{
    font-family: Georgia, 'Times New Roman', Times, serif;
}

p{
    background-color: cornflowerblue;
    color: white;
}

div button {
    background-color: purple;
    color: azure;
}

h1::first-letter {
    color: red;
}

input{
    background-color: darkgreen;
}

button:hover {
    background-color: yellow;
    color: blue;
  }

p:nth-of-type(odd) {
    color: yellow;
}

#yes:checked + label {
    color: darkgreen;
  }
  
