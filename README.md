<!-- # css-gridd2
creating rows in css grid -->
<!--

                           
-->

<html>
    <style>
        .container{
            display: grid;
            
            /*this will apply only in 3 rows only*/
            grid-template-rows: 1fr 1fr 4fr;
            
            /*this will apply in rest of the columns*/
            grid-auto-rows: 3fr;
            
            grid-gap: 5px;
            /*grid-template-columns: 1fr 2fr 1fr;*/
            grid-template-columns: repeat(3,3fr)
        }
        .box{
            background-color: red;
            border: 2px solid black;
            
        }
    </style>
<body>
<div class="container">
    <div class="box"> box1</div>
    <div class="box"> box2</div>
    <div class="box"> box3</div>
    <div class="box"> box4</div>
    <div class="box"> box5</div>
    <div class="box"> box6</div>
    <div class="box"> box7</div>
    <div class="box"> box8</div>
    <div class="box"> box9</div>
    <div class="box"> box10</div>
    <div class="box"> box11</div>
    
</div>
</body>
</html>
