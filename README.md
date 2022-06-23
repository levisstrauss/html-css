# CSS This repo is everything you need to understand about CSS

==== External links =====

    <link rel="stylesheet" type="text/css" src="directory" />

==== Selection =====

    <div id="test"></div>          ==>    #test {....}
    <div class="test"></div>       ==>    .test {....}

======================= Box Model =================
     
    . Margin
    . Border
    . Padding
    . Content

==== Padding and margin =====

    margin-top: 50px;
    margin-left: auto;     
    margin-right: auto; 

    Top => Right => Bottom => Left

    This can be replace by margin: ? ? ? ?;
    witch is: Top, Right, Bottom, Left => TRBL
    This is also the same when we have 3, 2 values

==== Position ==========

    display: block;
    line-height: 24px;

==== Forms & Borders ====

    width: 300px;
    border: 4px solid blue;
    border-radius: 100px; 
    font-weight: bold;


==== Colors =============

    color: #222 or black;
    background: lightgray;




==== Flexbox =====
     
    NB: If the parent div has a display flex that mean, every childs
        inside of it will inherit from the display position.

    display: flex;
    justify-content: center, start, end, space-around, space-between;
