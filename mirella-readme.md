# Project Documentaion for Mirella Solis Lopez

## Project Summary
Our project, Anissa & Tam Co., is an eco-friendly fashion website who's mission is to offer stylish clothing and sustainable clothing. Our company is not only focused on keeping the environment unharmed but also giving it's customers the best quality of clothing, acccessories, and footwear. For example, all the products in Anissa & Tam Co are produced from recyled polyester, organic cotton, and natural dyes thus diminishing their carbon footprint  which is one of the most important values for Anissa & Tam Co. To continue on, this website incorporates a fresh color palate in which it illustartes a calmn environment freindly website thus contributing to the initial value of the company and conveying to the customer a welcoming and friendly company.

My contribution to the project was the breakpoints, footer, and nav bar of the homepage. Getting started on the project was the most challenging portion for me due to the fact my group and I were trying to figure out how we were going to inplement our ideas into the project but at the same time keeping our ideas intertwined with the theme of the page. Once we got our desgin down I started working on the footer and nav bar which were the easiest portion for me. Although once I got to the breakpoints I struggled a little bit due to the constant change of code and images added from my team memebers. 


## Code Descriptions 
> Code example 1: On the code below I did the footers content to make an animation when you hover over a link it'll go up with the one, one as seleted. And to make this happen I incorporated "transform: translateY(-3px) translateX(-5px);"  in .footer-content li a:hover in order for the links to go up and then down and in order for it to look clean when it goes up or down I added the "transition: all .40s ease;".
```css 
.footer-content li a {
    padding: 5px;
    display: block;
    color:  white;
    font-size: 15px;
    font-weight: 400;
    transition: all .40s ease;
}
.footer-content li a:hover{
    transform: translateY(-3px) translateX(-5px);
    color: white;
}
```

> Code example 2: In the code below I created a tablet breakpoint. I created this breakpoint by putting the minimum width of the screen as 684px and the max width of the screen 880px in order to handle the browser size of a tablet. In addition, the content inside the curly brackets help ajust the content so a user on a tablet will be able be vosually appealing and not look all choppy.
```css
@media (min-width: 684px) and (max-width: 880px){
    .footer-btn{
      width:100px;
    }
    .img-size{
      height: 350px;
      width: 200px;
    }
    #img-sider{
      width: 300px;
      margin-left: 30px;
      /* border: 1px solid red; */
    }
```

>Code example 3: In the code below I created the nav bar. I surrounded it by a nav tag so I could access it altogether when I worked on it in css. In the nav tag I implemented the links of each link I wanted the customer to access and then added icons one for the cart and log in icon.
```html
 <nav>
                <a class="nav-bar" href="">New Arrivals</a>
                <a class="nav-bar" href="">Mens</a>
                <a class="nav-bar" href="">Women</a>
                <a class="nav-bar" href="">Kids </a>
                <a class="nav-bar" href="">Apparel </a>

                <i class='bx bx-cart icon' id="cart"></i>
                <i class='bx bx-user icon' ></i>
            </nav>
``