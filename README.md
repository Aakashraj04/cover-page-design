# cover-page-design
## AIM:
To develop a website to display the cover page design of a book

## Design Steps:

### Step 1:
Clone the github repository and create a new django project.

### Step 2:
Make changes in settings.py

### Step 3:
Now build a html code and use CSS for colours and effects.

### Step 4:
Then, run the server and take a screenshot of your book cover page.

## Code:
```html
<!DOCTYPE html>
<html lang="en">
    <head>
         <meta name="viewport" 
         content="width=device-width, initial-scale=1.0">
         <style>
    

        .bookpage{
            width: 500px;
            height: 700px;
            background-color:black;
            color:whitesmoke;
            margin-left: auto;
            margin-right: auto;
            padding: 20px;
            font-family: 'Franklin Gothic Medium', 'Arial Narrow', Arial, sans-serif;
            background-image: url(/static/images/Cover2.jpg);
            background-size: cover;
        }
            

        .toptext{
            color:blue;

        }

        
        .tophr{
            width:115px;
        }
        
        .author{
            color: white;
            display: inline;
            position: relative;
            text-align: left;
            color:black;
            top:428px;
            font-family:Georgia, 'Times New Roman', Times, serif;
            font-size: large;
        }
        
        .booktitle{
            font-family: 'georgia', monospace;
            font-size: x-large;
            text-align: center;
            position: relative;
            color:black;
            top: 30px;
        
        }
        
        .edition{
            color:blue;
            font-size: large;
            font-family: Arial, Helvetica, sans-serif;
            position:relative;
            text-align: left;
            top:345px;

        }

        .points{
            color: black;
            font-family:Tahoma;
            font-size: large;
            position: relative;
            top:110px;
        }

        .space{
            color:rgb(255, 0, 0);
            font-size: large;
            font-family: Arial, Helvetica, sans-serif;
            position:relative;
            text-align: left;
            top:332px;
        }

        .photo
        {
            position: relative;
            top: 173px;
            left: 375px;
            width: 100px;
            height: 100px;
            background-size: cover;
        }

        </style>
        <title>Book Cover Page</title>
    </head>
    <body>
        <div class="bookpage">
            <div class="toptext" class>
                Cyber Security
            </div>
            
            <div class="tophr">
                <hr style="color: red;">
            </div>
            
            <div class="booktitle">
                <h2>"Way to Secure your Data"</h2>
            </div>
                
            <div class="points">
             &bull; Introduction to Cyber
             <br>&bull; Cloud Security
             <br>&bull; Public Wi-Fi
             <br>&bull; Cryptography
             <br>&bull; Network Security
            </div> 

            <div class="author">
               <p><b>Aakashraj M (B.E)</p>
            </div>
            
            <div class="edition">
                <h3>First Edition
                </h3>
            </div>
            
            <div class="space">
                <hr style="color: red;">
            </div>

            <div class="photo">
                <img src="/static/images/AR1.jpg" width="115" height="125" alt="">
            </div>
            
        </div>
    </body>
</html>
```


## Output:

![image](https://github.com/Aakashraj04/cover-page-design/assets/121117266/1556e019-5b67-4d85-853a-4d6a1dbdf26e)


## Server Output:
![serevr output 06](https://github.com/Aakashraj04/cover-page-design/assets/121117266/cf1fc104-1136-44f1-99cf-9e64035009a5)


## Result:
Book Cover Page created successfully.
