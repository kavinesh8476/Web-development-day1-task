# Web-development-day1-task
## AIM
To develop a Website with a picture and some details with title,paragraph and link .
## CODE:
```
<!DOCTYPE html>
<html>
    <head>
        <title>Kavinesh</title>
        <style>
            body{
                background-image: url(bg.jpg);
                background-repeat: no-repeat;
                background-attachment: fixed;
                background-size: 100% 100%;
            }
            a{
                color: rgb(255, 255, 255);
            }
            .container {
                display: flex;
                align-items: flex-start;
            }
            .image-container {
                margin-right: 20px;
            }
            .lists-container {
                display: flex;
                flex-direction: column;
            }
            .lists-container ul,
            .lists-container ol {
                margin: 800px 30;
                padding: 300;
            }
            p{
                
                color: rgb(255, 255, 255);
                text-align: center;
            }
        </style>
    
    </head>
    <body style ="color: wheat;">

        <h1 style="text-align: center;"><a href="https://lms2.ai.saveetha.in/"> Contact us</a></h1>
            <div class="container">
                <div class="image-container">
                    <img src="pfp.jpg" alt="No Image" width="140   " height="180">
                </div>
                <div class="lists-container">
                    <ul>
                        <p style="text-align: left;">Unordered List(unknown tags)</p>
                        <li>Division</li>
                        <li>Button</li>
                        <li>Video</li>
                    </ul>
                    <ol>
                        <p style="text-align: left;">Ordered List(known tags)</p>
                        <li style="font-family: Impact, Haettenschweiler, 'Arial Narrow Bold', sans-serif;">DOCTYPE:</li>
                        <p style="font-size: medium;text-align: left;"> It specifies the document type and version of HTML</p>
                        <li style="font-family: Impact, Haettenschweiler, 'Arial Narrow Bold', sans-serif;">HTML:</li>
                        <p style="font-size: medium;text-align: left;"> It is an instruction written in HTML code that defines the structure and content of a web page.</p>
                        <li style="font-family: Impact, Haettenschweiler, 'Arial Narrow Bold', sans-serif;">Head:</li>
                        <p style="font-size: medium;text-align: left;"> It defines the head section of a document, containing meta-information such as the title, links to stylesheets, and scripts.</p>
                        <li style="font-family: Impact, Haettenschweiler, 'Arial Narrow Bold', sans-serif;">Anchor:</li>
                        <p style="font-size: medium;text-align: left;"> It creates hyperlinks to other documents or resources</p>
                        <li style="font-family: Impact, Haettenschweiler, 'Arial Narrow Bold', sans-serif;">img src:</li>
                        <p style="font-size: medium;text-align: left;"> It specifies the source URL of an image to be displayed on a web page.</p>
                        <li style="font-family: Impact, Haettenschweiler, 'Arial Narrow Bold', sans-serif;">Style:</li>
                        <p style="font-size: medium;text-align: left;"> It defines CSS styles for the document or a specific section of the document</p>

                    </ol>
                    <p style="font-size: 20px;font-family: 'Lucida Sans', 'Lucida Sans Regular', 'Lucida Grande', 'Lucida Sans Unicode', Geneva, Verdana, sans-serif;">If you need more information about us click the "contact us"</p>
                </div>
            </div>
            <footer>
                <p style="font-family: Impact, Haettenschweiler, 'Arial Narrow Bold', sans-serif;">&copy; 2023 My Website. All rights reserved.</p>
            </footer>
        
        
    </body>
</html>
```
## OUTPUT:
![image](https://github.com/kavinesh8476/Web-development-day1-task/assets/118466561/27f7c9eb-58a7-4fa2-a8c9-31e9426b1125)
