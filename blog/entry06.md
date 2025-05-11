# Entry 6
##### 5/11/25

# Content
During this blog, I've started to build my freedom project website, I've used HTML, CSS, bootstrap components and some javascript. I've made a carousel with bootstrap, which I learned while building my website. Here's a example of the carousel I built:
```html
            <div class="container">
                <div class="row align-items-center text-center text-lg-start">

                    <div class="col-12 col-lg-6">
                        <p id="info">
                            Art has been around for decades, and it was invented nearly 100,000+ years ago or so, but many people have only seen paper-drawn art. People also believe technology has the potential to bring more people into the art community as it makes it easier for people. This website will show you what <strong>inventions</strong>, <strong>technologies</strong>, and <strong>softwares</strong> will benefit the art community.
                        </p>
                    </div>

                    <div class="col-12 col-lg-6">
                    <div id="drawCarousel" class="carousel slide" data-bs-ride="carousel">

                        <div class="carousel-indicators">
                          <button type="button" data-bs-target="#drawCarousel" data-bs-slide-to="0" class="active" aria-current="true" aria-label="Slide 1"></button>
                          <button type="button" data-bs-target="#drawCarousel" data-bs-slide-to="1" aria-label="Slide 2"></button>
                          <button type="button" data-bs-target="#drawCarousel" data-bs-slide-to="2" aria-label="Slide 3"></button>
                        </div>


                        <div class="carousel-inner">
                          <div class="carousel-item active">
                            <img  src="img/drawsoftware.png" class="d-block w-100 img-fluid mb-2 mx-auto d-block" alt="Drawing Software">
                          </div>
                          <div class="carousel-item">
                            <img src="img/drawold.jpeg" class="d-block w-100 img-fluid mb-2 mx-auto d-block" alt="Old Drawing">
                          </div>
                          <div class="carousel-item">
                            <img src="img/drawingpen.jpeg" class="d-block w-100 img-fluid mb-2 mx-auto d-block" alt="Drawing Pen">
                          </div>
                        </div>

                        <button id="slide11" class="carousel-control-prev" type="button" data-bs-target="#drawCarousel" data-bs-slide="prev">
                          <span class="carousel-control-prev-icon" aria-hidden="true"></span>
                          <span class="visually-hidden">Previous</span>
                        </button>
                        <button id="slide12" class="carousel-control-next" type="button" data-bs-target="#drawCarousel" data-bs-slide="next">
                          <span class="carousel-control-next-icon" aria-hidden="true"></span>
                          <span class="visually-hidden">Next</span>
                        </button>
                      </div>
                      </div>
                </div>
            </div>
```
This carousel I learnt how to give and get data in the carousel to the "next" or "prev" slides, so if I press next it will signal to go to the next image, and if I press prev, it will go to the previous one. 
# Sources
I first began starting to search on google typing "Bootstrap carousel" and it gave me the official Bootstrap website so I used the official [Bootstrap](https://getbootstrap.com/docs/4.0/components/carousel/) to learn how to make carousel's, and then I proceeded to test it in [JSBin](https://jsbin.com/?html,output) to ensure I get the knowledge of how to properly utilze carousel.
# EDP
In this blog, I've learned how to use `data-bs-target`, `data-bs-slide-to`, `data-bs-ride`, `data-bs-slide`, these four codes have helped me learn how to correctly use data points to direct what should my code be doing. The next step I should take would be learning advanced data reaching and receiving.
# Skill
Since my last blog, I've said how I learned to understand coding, but sometimes the codes are unlogical and I'd get confused, but I learnt that the usage of AI could help an individual to understand something better as they contain informations within them that can explain the code specifcally or more simple to the person asking, and this helped me a lot in understanding the data coding which I think this is a skill that I developed.
[Previous](entry05.md) | [Next](entry07.md)

[Home](../README.md)
