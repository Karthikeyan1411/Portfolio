# Portfolio
<!DOCTYPE html>   <!--declaration defipned that this document is an HTML5 document-->
<html lang="en-us">    <!--Root Element of an HTML Page-->
    <head>   <!--Contains Meta Information about the HTML Page-->
        <!--<style>
            body {background-color: powderblue;}
            h1 {color: blue;}
            p {color: red;}
        </style>    <!--Here we use INTERNAL STYLE - CSS-->
        <!---->
        
        <!--<meta http-equiv="refresh" content="10">-->   <!--this line is used to refresh the page every 10 seconds-->
        <meta charset="UTF-8">
        <meta name="author" content="Karthikeyan"> <!--used to define author of the page-->
        <meta name="viewport" content="width=device-width, initial-scale=1.0">  <!--used to adjust their size/width depending on devices-->

        <link rel="stylesheet" href="ex1_styles.css">  <!--Here we use EXTERNAL STYLE - CSS-->
        <title>  
            EX-ONE
        </title> <!--Title for the page shown in browser's title bar or in the page's tab-->

        <link rel="icon" type="image/x-icon" href="favicon.ico">
    
    </head>

    <body>  <!--It is the container for all the visible contents, such as headings, Pararaphs, images, hyperlinks, tables, lists, etc.-->

        <h1 style="font-size: 100px; text-align: center;">This is a Heading</h1> <!--Here we use INLINE STYLE - CSS -->
        <p style="color: crimson;">This is a Paragraph</p>
        <h2><b>Hi Karthikeyan</b></h2>

        <!--title, href, src, etc... = These are all attributes-->

        <p title="About Karthikeyan">Karthikeyan is a Front End Developer</p>
        <hr>  <!--Used to Separate Content or define a change// thematic break in a page and is most often displayed as a horizontal rule-->

        <a href="https://www.w3schools.com" target="_blank">This is a link</a>   <!--target - used for where to open the page either in new window or same or parent_frame or full body of the window-->

        <figure>
        <a href="kk.jpg"><img src = "kk.jpg" alt = "W3Schools.com" width="104" height="142"></a>  <!--H & W are in Pixels-->
        <figcaption style="color: white;">Karthikeyan</figcaption>
        </figure>    <!--this tag is used to fig 1. kk - like this mentioning-->

        <pre style="background-color: blue; color: coral; font-size: large;" >   <!--Pre formatted Text-->
            <i>Hi, Am a <span style="color: white; font-weight: bold;">Web Developer.</span></i>
            <em>And also learning daily one new things.</em>
            <strong>If you want to become me like this follow me in social pages.</strong>
        </pre>

        <p>The <abbr title="World Health Organization">WHO</abbr> was founded in 1948.</p>

        <div style="background-color: black; color: white; padding: 20px;">
        <address style="border: 3px solid tomato;">
            Written by Karthikeyan M. <br>
            Palkararkadu, Erumapalayam <br>
            Salem <br>
            <a href="mailto:karthikeyan1411m@gmail.com">Email</a>
        </address>
        </div>

        <bdo dir="rtl">This line will be written from right to left</bdo> <br>

        <button onclick="document.location = 'kk.jpg' ">MY PIC PAGE</button>  <!--JS Code for using BUTTON-->

        <table style="width: 100%;">
            <caption>ABOUT ME</caption>  <!--used for table title/heading-->
            <tr>
                <th colspan="2">Name</th> <!--used for attach column-->
                <!--<th>First Name</th>
                <th>Last Name</th>-->
                <th>E-Mail</th>
            </tr>
            <tr>
                <td>Karthikeyan</td>
                <td>Murugesan</td>
                <td>karthikeyan1411m@gmail.com</td>
            </tr>
            <tr>
                <td>Jayaraman</td>
                <td>Murugesan</td>
                <td>jayakarthi26896@gmail.com</td>
            </tr>
        </table>

        <h2 id="myHeader">This line is used by Unique ID</h2>

        <iframe src="https://github.com/Karthikeyan1411" style="height: 200px; width: 300px;" title="HTML Tutorial"></iframe>

        <footer style="max-width: 100%; color: white; text-align: center;">&copy; by Spyde &#128525</footer>


    </body>
</html>
