<!DOCTYPE html>
<html>
  <head>
    <meta charset="utf-8">
    <meta name="viewport" content="width=device-width">
    <title>repl.it</title>
    <link rel="stylesheet" href="https://maxcdn.bootstrapcdn.com/font-awesome/4.7.0/css/font-awesome.min.css" type="text/css" />
    <link href="index.css" rel="stylesheet" type="text/css" />
  </head>
  <body>
    <div id="container">
     <header>
        <h1>How to make winter tea</h1>
        <img src="https://imgur.com/2AsJZr5.jpg">
        <p>Winter tea is a perfect idea for cold nights and to improve your blood circulation!</p>
    </header>
    <section id="ingredients" onmouseover="ingredientsHover()" onmouseout="ingredientsNormal()">
        <h2>Ingredients <i class="fa fa-coffee" aria-hidden="true"></i></h2>
        <ul>
          <li>Tea bag</li>
          <li>Water</li>
          <li>Slice of fresh ginger</li>
          <li>Slice of lemon</li>
          <li>Raspberry Syroup</li>
        </ul>
    </section>
    <section id="preparation" onmouseover="preparationHover()" onmouseout="preparationNormal()">
        <h2>Preparation <i class="fa fa-list-ol" aria-hidden="true"></i></h2>
        <ol>
          <li>Boil about 500 ml of water </li>
          <li>Pop a tea bag into your mug</li>
          <li>Tea needs time to unlock all its flavour, the best is very strong tea! Give it about 3-4 minutes</li>
          <li>Remove the tea bag</li>
          <li>Throw all the ingredients in to your mug and voila, winter tea is ready!</li>
          <li>Optionally you could add some sugar if you like to x</li>
          <li>Enjoy!</li>
        </ol>
    </section>
    <footer>
        <p>Copyright Me 2021</p>
    </footer>
    </div>
    <script>
        function ingredientsHover() {
            document.getElementById('ingredients').firstElementChild.firstElementChild.style.fontSize = '300%';
        }


        function ingredientsNormal() {
            document.getElementById('ingredients').firstElementChild.firstElementChild.style.fontSize = '100%';
            // document.write("Normal");  
        }


        function preparationHover() {
            document.getElementById('preparation').firstElementChild.firstElementChild.style.fontSize = '300%';
        }


        function preparationNormal() {
            document.getElementById('preparation').firstElementChild.firstElementChild.style.fontSize = '100%';
        }
    </script>
  </body>
</html>
