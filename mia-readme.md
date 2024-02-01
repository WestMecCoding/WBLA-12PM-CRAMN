# Project Documentation for Your Name

## Project Summary

Our team project was to create a fashion site about a company called Anissa & Tam CO. They had a mission to create a world where fashion and sustainability can coexist with each other. Furthermore this company also wanted to reduce the industrys carbon footprint and start promoting ethical practices. Anissa & Tam CO. would promote clothes, footwear, and accessories that would be made from sustainable materials like organic cotton, recylcled polyester, and ect.

My contribution to the project was finding images and also fixing the resolution of the images. I would use gimp or paint to resize images to see how it would look and try to fix it before Mirella or Charlene would put it in the website. After I figured out the image issue I would put it back in the folder and work on anything they needed help with. I also was the main creator of the slides who worked on the information and figuring out the order the slides should go. Lastly I started a navbar for the second site but charlene had to finsih it for me since I had to finish working on our presentation.

## Code Descriptions
> code example 1: The code below is the HTML used to create the nav bar for the ABoutUs page. It was also used to create a login button and a cart button that was incorporated in the Nav Bar.
<div class="header-nav">
                <nav>
                    <a class="nav-bar" href="index.html">Home</a>
                    <a class="nav-bar" href="">New Arrivals</a>
                    <a class="nav-bar" href="">Mens</a>
                    <a class="nav-bar" href="">Women</a>
                    <a class="nav-bar" href="">Apparel</a>

                    <i class='bx bx-cart' id="cart"></i>
                    <i class='bx bx-user'></i>
                </nav>
 </div>

> Code example 2: The code below is the CSS used to put the Nav Bar in position.
```css
 div.header-nav {
        /* border: solid blue; */
        text-align: center;
    }
    a, i {
        /* border: solid magenta; */
        color: white;
        margin: 0 1.5rem;
        margin-top: 25px;
        text-decoration: none;
        /* display: inline-block; */
        letter-spacing: 1px;
        font-size: 1rem;
        font-family: 'DM Serif Display', serif;
        transition: all .40s ease;
}
```