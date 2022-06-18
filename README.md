
<!DOCTYPE html>
<html>
    <head>
        <title>Alcheringa WebOps</title>
        <link rel="preconnect" href="https://fonts.googleapis.com">
        <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
        <link href="https://fonts.googleapis.com/css2?family=Roboto:wght@100;300;500;700&display=swap" rel="stylesheet">
        <style>
            p{
                margin: 0;
            }
            .alcherdiv{
                margin-top: 20px;
                display: inline-block;
                width: 200px;
                font-weight: bold;
                font-family: Arial, Helvetica, sans-serif;
                margin-bottom: 10px;
            }
            .searchdiv{
                font-family: Arial, Helvetica, sans-serif;
                display: inline-block;
                margin-left: 360px;
            }
            .searchbar{
                display: inline-block;
                padding-left: 15px;
                height:30px;
                width:300px;
                border-radius: 5px;
                border-width: 1px;
                border-color: rgb(197, 191, 191);
                border-style: solid;
                font-size: 15px;
                margin-left: 10px;

            }
            .home{
                font-family: Arial, Helvetica, sans-serif;
                margin-left: 400px;
                display: inline-block;
                cursor: pointer;
            }
            .about{
                font-family: Arial, Helvetica, sans-serif;
                display: inline-block;
                margin-left: 30px;
                cursor: pointer;
            }
            .contact{
                font-family: Arial, Helvetica, sans-serif;
                display: inline-block;
                margin-left: 30px;
            }
            .home:active{
                font-weight: bold;
                font-size: 15px;
            }
            .about:active{
                font-weight: bold;
                font-size: 15px;
            }
            .contact:active{
                font-weight: bold;
             font-size: 15px;
            }  
            .loremlorem{
                margin-top: 50px;
                margin-bottom: 30px;
                text-align: center;
                font-size: 50px;
                font-weight: bold;
                font-family: Arial, Helvetica, sans-serif;
            }
            mark.black{
                color: black;
                background: none;
            }
            mark.blue{
                color: #0d6efd;
                background: none;
            }
            .line1{
                text-align: center;
                font-family: Arial, Helvetica, sans-serif;
                font-weight: 300;
                color: rgb(118, 117, 117);
                margin-bottom: 5px;
            }
            .line2{
                text-align: center;
                font-family: Arial, Helvetica, sans-serif;
                font-weight: 300;
                color: rgb(118, 117, 117);

            }
            .line1div{
                margin-bottom: 2px;
            }
            .line2div{
                margin-top: 2px;
            }
            .b1{
                background-color:#0d6efd;
                border-color: #0d6efd;
                border-style: solid;
                border-width: 1px;
                font-family: Arial, Helvetica, sans-serif;
                box-shadow: 0 0 2px rgba(0,0,0,0.4);
                color: white; 
                padding: 12px 25px;
                border-radius: 6px;
                cursor: pointer;
                transition: background-color 0.15s, color 0,15s;
            }
            .b2{
                background-color: white;
                border-style: solid;
                border-width: 1px;
                padding: 12px 25px;
                font-family: Arial, Helvetica, sans-serif;
                border: none;
                box-shadow: 0 0 2px rgba(0,0,0,0.4);
                color:#0d6efd; 
                border-radius: 6px;
                cursor: pointer;
                transition: background-color 0.15s, color 0,15s;
            }
            .b1:hover{
               background-color: rgb(18, 18, 151);
            }
            .b2:hover{
               background-color: rgb(239, 233, 233);
            }
            .button{
                margin-top: 30px;
                text-align: center;
            }
            .b1div{
                display: inline-block;
            }
            .b2div{
                display: inline-block;
            }
            .text{
                vertical-align: top;
                margin-left: 50px;
                width: 450px;
                display: inline-block;
                vertical-align: top;
                margin-top: 20px;
            }
            .l1{
                font-weight: bold;
                font-family: Arial, Helvetica, sans-serif;
            }
            .l2{
                margin-top: 5px;
                font-style: italic;
                font-family: Arial, Helvetica, sans-serif;
                font-weight: 300;

            }
            .l3{
                margin-top: 5px;
                font-family: Arial, Helvetica, sans-serif;
                font-weight: 300;
            }
            .l31{

                font-family: Arial, Helvetica, sans-serif;
                background-color: yellow;
                font-weight: 300;
            }
            .l4{
                margin-top: 5px;
                font-family: Arial, Helvetica, sans-serif;
                font-weight: 300;

            }
            .l5{
                margin-top: 10px;
                font-family: Arial, Helvetica, sans-serif;
                font-weight: 300;
            }
            .l6{
                margin-top: 10px;
                font-family: Arial, Helvetica, sans-serif;
                font-weight: 300;
                text-decoration: line-through;
            }
            .l7{
                margin-top: 10px;
                font-family: Arial, Helvetica, sans-serif;
                font-weight: bold;
            }
            .iframe{
                vertical-align: top;
                display: inline-block;
                margin-left: 50px;
                margin-top: 0;
            }
            .pic{

                display: inline-block;
                margin-left: 100px;
                vertical-align: top;
            }
            .wall{
                margin-top: 20px;
                width: 400px;
                cursor: pointer;
                border-radius: 5px;

            }
            table,th,td{
                border:1px solid rgb(198, 195, 195);
                border-collapse: collapse;
                padding-top: 8px;
                padding-bottom: 8px;
                padding-left: 4px;
                padding-right: 2px;
                text-align: left;
                margin-top: 7px;
                font-size: large; 
            }
            .links{
                text-align: center;
            }
            .iframehead{
                margin-top: 12px;
                font-family: Arial, Helvetica, sans-serif;
                font-weight: bold;
            }
            .allign{
                margin-top: 20px;
                height: 300px;
            }
            .template{
                overflow-y: scroll;
                overflow-x: scroll;
            }
        </style>

    </head>
    <body>
        <div>
            <div class="alcherdiv">
                <p class="alcher">
                    Alcheringa WebOps
                </p>
            </div>
            <div class="searchdiv">
                <input class="searchbar" type="text" placeholder="Search something here">

            </div>
            <div class="home">
                Home
            </div>
            <div class="about">
                About
            </div>
            <div class="contact">
                Contact
            </div>
        </div>
        <div>
            <hr>
        </div>
        <div>
            <p class="loremlorem">
                <mark class="black">Lorem Ipsum Dolor </mark><mark class="blue">Lorem Ipsum</mark>
            </p>
        </div>
        <div class="line1div">
            <p class="line1">
              Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ac eleifend sapien. In ac arcu nec diam tincidunt cursus
            </p> 
        </div>
        <div class="line2div">
            <p class="line2">
              Pellentesque quis tortor sit amet erat condimentum molestie ut nec sapien
            </p>
        </div>
        <div class="button">
            <div class="b1div" >
                <button class="b1">Button 1</button>
            </div>
            <div class="b2div">
               
                <button class="b2">Button 2</button>
            </div>
        </div>
        <div class="allign">
            <div class="text">
               <p class="l1">
                 HTML Formatting:
               </p>
               <p class="l2">
                 This is an italic text
               </p>
               <p class="l3">
                This text is <mark class="l31">highlighted</mark>
               </p>
               <p class="l4">
                This is a <sub>subsrcipt</sub> and a <sup>superscript</sup>
               </p>
               <p class="l5">
                 "This is a quotation"
               </p>
               <p class="l6">
                This is done using del tag
               </p>
               <p class="l7">
                 HTML Table
               </p>
               <table class="table" style="width:80%">
                 <tr>
                    <th>Company</th>
                    <th>Contact</th>
                    <th>Country</th>
                 </tr>
                 <tr>
                    <td>Alfreds Futterkiste</td>
                    <td>Maria Anders</td>
                    <td>Germany</td>
                 </tr>
                </table>
            </div>
            <div class="iframe">
                <p class="iframehead">
                    HTML iframes
                </p>
                <iframe class="template" height="200" width="400" src="https://www.alcheringa.in/" scrolling="yes"></iframe>
            </div>
            <div class="pic">
                <img class="wall" src="55-557580_8k-hd-wallpapers-backgrounds-images-high-resolution-beautiful.jpg">
            </div>
        </div>
       </br>
       </br>
       </br>
       <div class="links">
        <a target="_blank" href="https://www.facebook.com/alcheringaiitg/photos/alcheringa-proudly-announces-the-news-mill-as-the-digital-media-partneralchering/3824108330960311/" class="fb">Facebook |</a>
        <a target="_blank" href="https://www.instagram.com/alcheringaiitg/?hl=en" class="ig">Instagram |</a>
        <a target="_blank" href="https://www.youtube.com/c/AlcheringaIITG" class="yt">Youtube</a>
       </div>
    </body>
</html>
