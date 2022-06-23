# CSS This repo is everything you need to understand about CSS

================ External links =============

    <link rel="stylesheet" type="text/css" src="directory" />

================ Selection ==================

    <div id="test"></div>          ==>    #test {....}
    <div class="test"></div>       ==>    .test {....}

================ Box Model ==================
     
    . Margin
    . Border
    . Padding
    . Content

============= Padding and margin =============

    margin-top: 50px;
    margin-left: auto;     
    margin-right: auto; 

    Top => Right => Bottom => Left

    margin:    10px      |    auto;     __
             top/bottom      right/left

    NB: One value: applied for all four sides
        Two values: One value for top/bottom second right/left
        Three values: for top, right,  bottom
        Four values: top, right, bottom, left

================= Center ====================

    margin: 0 auto;
    justify-content: center;

================= Alignment & Position =================

    line-height: 1.5;
    text-align: center;
    justify-content: center, space-around, start, end...;

    -------------------------------------------------

    display: block, flex, inline or inline-block;
    line-height: 24px;

    NB: It's even cooler when we want to manipulate
        the position of a child element from it parent one
        by fixing the position of the parent as: relative
        and the child as: absolute;

    <div position: relative>
       <div position: absolute></div>
    </div>

================= Forms & Borders ===========

    width: 300px;
    height: 10px;
    -----------------------
    border: 4px solid blue;
    border-radius: 100px; 
    border-bottom, border-right, border-left...

================= Colors ====================

    color: #222 or black;
    background: lightgray;


================== Flexbox ===================
     
    NB: If the parent div has a display flex that mean, every childs
        inside of it will inherit from the display position.

    display: flex;
    justify-content: center, start, end, space-around, space-between;

================== Image =====================

    Background-image: url("");
    background-size: cover;

=================== Text =====================

     font-weight: bold;
     font-family: Verdana, Geneva, Tahoma, sans-serif;
     font-size: 80px;
     text-shadow: 5px 0px 10 black; => Horizontal, Vertical, blur, color;

     NB: If we are using a ttf font, we can just use:
   
     @font-face {
         src: url("Corleone.ttf");
         font-family: Corleone;
     }

     h1 {
          font-family: Corleone;
     }
}

============= Projects screenshot ============

      Project 1: Google Search Page
![](/images/google-interface.png?raw=true "Google Search Page")

      Project 2: Header Navigation
![](/images/navigation.png?raw=true "Header Navigation")

      Project 3: Business Card
![](/images/business-card.png?raw=true "Business Card")

      Project 4: Space website
![](/images/spacer.png?raw=true "Space website")

      Project 5: Birthday website
![](/images/spacer.png?raw=true "Birthday website")
