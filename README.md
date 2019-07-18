# mini-lesson.funny-text
1. Go to the [project's GitHub ](https://github.com/alvarotrigo/funnyText.js)
1. Click the green clone or download button and copy the link
1. In the terminal inside your `final-project` folder run `git clone https://github.com/alvarotrigo/funnyText.js.git`
1. Inside your `index.html` add these links to your `<head>`. *Note: put these links above your `<script src="script.js"></script>`.

          <script src="http://ajax.googleapis.com/ajax/libs/jquery/1.8.3/jquery.min.js"></script>
          <script type="text/javascript" src="funnyText.js/jquery.funnyText.js"></script>
          <link rel="stylesheet" type="text/css" href="funnyText.js/jquery.funnyText.css" />
          
1. Inside your `index.html` add an element that you would like to style with funny text. Put a class on it, such as "funny-text".
         
          <h1 class="funny-text">funnyText is applied here</h1>
          
1. Inside your `script.js` select the class using jQuery and call the `funnyText()` function on it.

            $('.funny-text').funnyText();
            
1. Change your function to pass some options to it to change colors on your styles!
          
            $('.funny-text').funnyText({
              speed: 700,
              borderColor: 'red',
              activeColor: 'white',
              color: 'blue',
              fontSize: '2em',
              direction: 'both'
            });
