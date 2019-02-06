# ReadMore.Js
ReadMore მოდული საშუალებას გაძლევთ დამალოთ ტექსტის ნაწილი, თუ იგი აღემატება მითითებულ სიგრძეს. აქვე ემათება მას ბმული Button-ის სტილში და აჩვენებს დაფარულ ტექსტს. 
# ატვირთეთ სიატზე ფაილი : readmore.js

მოათავსეთ კოდი საიტის მთავარ გვერდზე :
<!-- ReadMore ინტეგრაცია -->
    <script src="http://ajax.googleapis.com/ajax/libs/jquery/1.9.1/jquery.min.js"></script>
    <script src="js/readmore.js"></script>
    <script>
        $('article').readmore({
            maxHeight: 200,
            moreLink: '<a  href="#" >სრულიად </a>',
            lessLink: '<a href="#" >წავიკითხე </a>'
        });
    </script>


მოათავსეთ ტექსტის დასაწყისში და დასასრულში: <pre class="box"><code> დასაწყისი (&lt;article&gt;) დასასრული (&lt;/article&gt;)</code></pre>

მაგ: 
    &lt;article&gt;
     &lt;p&gt; Lorem ipsum dolor sit amet, consectetur adipisicing elit, sed do eiusmod
      tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam,
      quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo
      consequat. Duis aute irure dolor in reprehenderit in voluptate velit esse
      cillum dolore eu fugiat nulla pariatur. Excepteur sint occaecat cupidatat non
      proident, sunt in culpa qui officia deserunt mollit anim id est laborum.&lt;/p&gt;
   &lt;/article&gt;
