# Java_lec.22

<!DOCTYPE>
<html>
  <head>
    <meta charset="utf-8">
  </head>
  <body>
    <h1>Loop & Array</h1>
    <script>
      var coworkers = ['egoing','leezche','duru', 'taeho'];
    </script>
    <h2>Co workers</h2>
    <ul>
      <script>
       var i = 0;
       while(i < coworkers.length){
         document.write('<li><a href="http://www.naver.com/'+coworkers[i]+'">'+coworkers[i]+'</a></li>');
         i = i + 1;
       }
       </script>
    </ul>
  </body>
</html>
