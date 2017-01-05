# tilted-image-with-css
Adding interactivity to your website is always a value add. Static images are boring yet for some reason they're still everywhere on the web. Good design principles include adding as much interactivity to your images as possible so they stand out. There are many ways to do this using different hover effects with JavaScript. However, in this article, [Solodev](https://www.solodev.com/blog/) will show you how to add a tilt effect to your images onHover using CSS.

## Tutorial

For detailed instructions, view Solodev's [Adding a Tilt to your Images onHover with CSS](https://www.solodev.com/blog/web-design/adding-a-tilt-to-your-images-on-hover-with-css.stml) article.

## Demo

Try out a working example on [JSFiddle](https://jsfiddle.net/solodev/y5g0pvfk/).

## HTML

The tilted image grid contains the following basic HTML markup.

```
<div class="container sectional-wrapper" >
   <div class="row" >
      <div class="col-md-12" >
         <!-- sample.html -->
         <div class="dynamicDiv" id="dd.0.2.0" >
            <div class="row" >
               <div class="col-md-12 pagingBorder" >
                  <div id="theImageGrid" >
                     <ul class="row imagegrid" id="imagegrid" >
                        <li class="col-xs-12 col-sm-6 col-md-4" id="167" >
                           <div class="imgHolder" >
                              <div class="fauxCrop" >
                                 <a href="#" ><img src="https://www.solodev.com/assets/fancy/travel3.jpg" class="grid-image img-responsive" ></a>
                              </div>
                             
                           </div>
                         
                        </li>
                        <li class="col-xs-12 col-sm-6 col-md-4" id="27" >
                           <div class="imgHolder" >
                              <div class="fauxCrop" >
                                 <a href="#" ><img src="https://www.solodev.com/assets/fancy/travel2.jpg" class="grid-image img-responsive" ></a>
                              </div>
                              
                           </div>
                           <div class="clearfix" ></div>
                        </li>
                        <li class="col-xs-12 col-sm-6 col-md-4" id="23" >
                           <div class="imgHolder" >
                              <div class="fauxCrop" >
                                 <a href="#" ><img src="https://www.solodev.com/assets/fancy/travel4.jpg" class="grid-image img-responsive" ></a>
                              </div>
                             
                           </div>
                           <div class="clearfix" ></div>
                        </li>
                        <li class="col-xs-12 col-sm-6 col-md-4" id="22" >
                           <div class="imgHolder" >
                              <div class="fauxCrop" >
                                 <a href="#" ><img src="https://www.solodev.com/assets/fancy/travel5.jpg" class="grid-image img-responsive" ></a>
                              </div>
                              
                           </div>
                           <div class="clearfix" ></div>
                        </li>
                        <li class="col-xs-12 col-sm-6 col-md-4" id="105" >
                           <div class="imgHolder" >
                              <div class="fauxCrop" >
                                 <a href="#" ><img src="https://www.solodev.com/assets/fancy/travel6.jpg" class="grid-image img-responsive" ></a>
                              </div>
                             
                           </div>
                           <div class="clearfix" ></div>
                        </li>
                        <li class="col-xs-12 col-sm-6 col-md-4" id="106" >
                           <div class="imgHolder" >
                              <div class="fauxCrop" >
                                 <a href="#" ><img src="https://www.solodev.com/assets/fancy/travel7.jpg" class="grid-image img-responsive" ></a>
                              </div>
                              
                           </div>
                           <div class="clearfix" ></div>
                        </li>
                     </ul>
                  </div>
               </div>
            </div>
         </div>
         <!-- end sample -->
      </div>
   </div>
</div>
```
## CSS

All necessarry CSS is included in the file tilted-image.css

## External Includes

```
<script src="https://ajax.googleapis.com/ajax/libs/jquery/3.1.1/jquery.min.js"></script>
<script src="https://maxcdn.bootstrapcdn.com/bootstrap/3.3.7/js/bootstrap.min.js"></script>
<link href="https://maxcdn.bootstrapcdn.com/bootstrap/3.3.7/css/bootstrap.min.css" rel="stylehseet" >
<link href="tilted-image.css" rel="stylehseet">
```
