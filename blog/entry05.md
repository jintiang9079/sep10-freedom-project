# Entry 5
##### 04/11/25

# Content
During this blog, I've started to learn more things outside of CSS Variables, I learnt Aframe, I tinkered with these tools combined together with CSS, HTML, AVD and AWD. Here's a simple mini website I did with them:
``` html css
<!DOCTYPE html>
<html>
<head>
  <meta charset="utf-8">
  <meta name="viewport" content="width=device-width">
  <title>JS Bin</title>
  <link href="https://cdn.jsdelivr.net/npm/bootstrap@5.3.0/dist/css/bootstrap.min.css" rel="stylesheet">

<script src="https://cdn.jsdelivr.net/npm/bootstrap@5.3.0/dist/js/bootstrap.bundle.min.js"></script>
   <link href="https://cdn.jsdelivr.net/npm/bootstrap@5.3.0-alpha1/dist/css/bootstrap.min.css" rel="stylesheet" integrity="sha384-GLhlTQ8iRABdZLl6O3oVMWSktQOp6b7In1Zl3/Jr59b6EGGoI1aFkw7cmDA6j6gD" crossorigin="anonymous">
  <script src="https://aframe.io/releases/1.7.0/aframe.min.js"></script>
</head>
<body>
          <script>
            document.addEventListener("DOMContentLoaded", function() {
              let navLinks = document.querySelectorAll(".nav-link");
              let navCollapse = document.querySelector("#navbarNav");

              navLinks.forEach(function(link) {
                link.addEventListener("click", function() {
                  if (navCollapse.classList.contains("show")) {
                    new bootstrap.Collapse(navCollapse).hide();
                  }
                });
              });
            });
            

          </script>
  
  
  
         <nav id="navbar" class="navbar navbar-expand-lg navbar-dark bg-dark fixed-top">
            <div class="container-fluid">
                <a class="navbar-brand" href="#">
                    <img id="hot-air-ballon-img" src="img/hot-air-balloon-clipart.png" width="30" height="30" class="d-inline-block align-top" alt="">
                    <strong>Lorem Ipsum</strong>
                </a>


                <button class="navbar-toggler" type="button" data-bs-toggle="collapse" data-bs-target="#navbarNav"
                    aria-controls="navbarNav" aria-expanded="false" aria-label="Toggle navigation">
                    <span class="navbar-toggler-icon"></span>
                </button>


                <div class="collapse navbar-collapse" id="navbarNav">
                    <ul class="navbar-nav ms-auto">
                        <li class="nav-item"><a class="nav-link" href="#intro">Intro</a></li>
                        <li class="nav-item"><a class="nav-link" href="#box">Aframe</a></li>

                            </ul>
                        </li>
                    </ul>
                </div>
            </div>
        </nav>
  <div id="skibidi"> 
    <h1 id="intro"> Lorem Ipsum </h1>
    <p> This is about a box, Lorem ipsum dolor sit amet, consectetur adipiscing elit. Integer sollicitudin sapien a dictum facilisis. Suspendisse quis lectus id velit dignissim porttitor. Nullam non ultricies dui, eu vestibulum nulla. Integer sed eros auctor, ultrices turpis non, dapibus risus. Nam efficitur lobortis augue elementum maximus. Fusce dapibus sapien et aliquet lobortis. Nullam sodales pulvinar viverra. Donec non felis imperdiet nisi porta porttitor. Fusce eu justo vel eros mollis efficitur. Vestibulum convallis a nulla quis placerat.
      <p> This is about a box, Lorem ipsum dolor sit amet, consectetur adipiscing elit. Integer sollicitudin sapien a dictum facilisis. Suspendisse quis lectus id velit dignissim porttitor. Nullam non ultricies dui, eu vestibulum nulla. Integer sed eros auctor, ultrices turpis non, dapibus risus. Nam efficitur lobortis augue elementum maximus. Fusce dapibus sapien et aliquet lobortis. Nullam sodales pulvinar viverra. Donec non felis imperdiet nisi porta porttitor. Fusce eu justo vel eros mollis efficitur. Vestibulum convallis a nulla quis placerat.
        <p> This is about a box, Lorem ipsum dolor sit amet, consectetur adipiscing elit. Integer sollicitudin sapien a dictum facilisis. Suspendisse quis lectus id velit dignissim porttitor. Nullam non ultricies dui, eu vestibulum nulla. Integer sed eros auctor, ultrices turpis non, dapibus risus. Nam efficitur lobortis augue elementum maximus. Fusce dapibus sapien et aliquet lobortis. Nullam sodales pulvinar viverra. Donec non felis imperdiet nisi porta porttitor. Fusce eu justo vel eros mollis efficitur. Vestibulum convallis a nulla quis placerat.
          <p> This is about a box, Lorem ipsum dolor sit amet, consectetur adipiscing elit. Integer sollicitudin sapien a dictum facilisis. Suspendisse quis lectus id velit dignissim porttitor. Nullam non ultricies dui, eu vestibulum nulla. Integer sed eros auctor, ultrices turpis non, dapibus risus. Nam efficitur lobortis augue elementum maximus. Fusce dapibus sapien et aliquet lobortis. Nullam sodales pulvinar viverra. Donec non felis imperdiet nisi porta porttitor. Fusce eu justo vel eros mollis efficitur. Vestibulum convallis a nulla quis placerat.
    <a-scene embedded>
      <a-sky color="lightblue">  </a-sky>
      <a-box id="box" color="blue" position="0, 2, -3" > </a-box>
     </a-scene>
  </div>
</body>
</html>
```
This mini website I did was to test my knowledge on all of them so I can get a refreshed memory of them. In the website, I included navbar, animation, aframe. I learnt aframe by going to their official website and looking up how to do certain things, this helped me to understand Aframe much better, and for CSS variable I basically did the same thing but going into w3school for guidance. I learned how CSS variables could help me and make my life easier, while aframe can give a clear demonstration on my project.
# Sources
The source I've used to learn Aframe is their [official website](https://aframe.io/docs/1.7.0/introduction/), and in order for me to rewash my memory with css, awd, avd and html I used google searching engine to help me find the solutions to my problems, but in general I used [W3Schools](www.w3schools.com) as much as I could as this website included many things that helped me a lot during my tinkering, I used [JSBin](https://jsbin.com/?html,output) in order to tinker my ideas, and create some mini websites, I also used **CS50** for tinkering.

# Skills
Since my last blog entry, this time I've learned two skills for my future, first skill that I learnt during this blog was me knowing how to actually understand coding, this may look confusing but, in the past I was understanding coding in a whole different way than now, back then I would just think coding is random illogical words, but now that I think about it, if I think about code just like a language, it makes a lot more sense and logic, so it helped me improve in coding a lot. Second skill I learnt from this blog was on how to properly search for guidance, from the past, I would just google my problems, sure it helped but some problems were way to specific for it to appear on google, so this time I went to the official websites and searched up the code, and I understood them there by reading the definitions of what they do as the websites give you clear demonstrations, so this skill helped me to understand how to rely on myself and the resources provided by the world.


[Previous](entry04.md) | [Next](entry06.md)

[Home](../README.md)
