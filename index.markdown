---
# Feel free to add content and custom Front Matter to this file.
# To modify the layout, see https://jekyllrb.com/docs/themes/#overriding-theme-defaults

layout: home
comments: true
---

<style>
  @import url('https://fonts.googleapis.com/css2?family=Montserrat:wght@500&display=swap');
  
    header {

      background-color: rgba(252, 250, 250, 0.8);
      position: fixed;
      height: 83px;

    }
    .page-link{
      padding:20px ;
      color: white;
    }
    .trigger{
      color: white;
      margin: 15px;
    }
    .page-link:hover {
      border: 2px solid black;
      /* background-color: rgba(1, 1, 1, 0.7); */
      /* color: white; */
    }
   
    header a {
      font-family: 'Montserrat', sans-serif;
      font-weight: 500;
      font-size: 16px;
      color: white;
      text-decoration: none;
      transition: all 0.3s ease 0s;
      margin-top:3px ;
      /* background-color: red; */
      padding: 10px;
     
    }
    header a:hover{
      /* background-color: rgb(170, 160, 160); */
      /* color:white; */
      /* background-color: rgba(1, 1, 1, 0.7); */
      /* border: 2px solid black; */
      /* padding: 10px; */
    }

    footer{
      background-color: rgb(196, 193, 191);
    }
    .page-content{
      /* border: 2px solid red; */
      /* margin: 0px 250px; */
      
    }
    main{
      height: 600px;
    }
    .post-meta{
      color: white;
    }

     body {


      background-image: url("https://i.postimg.cc/MT6FqHWQ/rupee-4395520.jpg");
      background-size: cover;       
      /* background-color: rgba(1, 1, 1);  */
            height:100%;
            width: 100%;
            z-index: -1;
    } 
    
      </style>
  [check this@Instagram](https://www.instagram.com/financial_literate/?hl=en)
 
 

{% if page.comments %}

<div id="disqus_thread"></div>
<script>
(function() { // DON'T EDIT BELOW THIS LINE
var d = document, s = d.createElement('script');
s.src = 'https://https-gupta-anubhav12-github-io-fortheloveofnifty.disqus.com/embed.js';
s.setAttribute('data-timestamp', +new Date());
(d.head || d.body).appendChild(s);
})();
</script>
<noscript>Please enable JavaScript to view the <a href="https://disqus.com/?ref_noscript">comments powered by Disqus.</a></noscript>

{% endif %}