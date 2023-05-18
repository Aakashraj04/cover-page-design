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
            color:white;
            margin-left: auto;
            margin-right: auto;
            padding: 20px;
            font-family: 'Franklin Gothic Medium', 'Arial Narrow', Arial, sans-serif;
            background-image: url(/static/images/Martin.jpg);
            background-size: cover;
        }
            

        .toptext{
            color:white;

        }

        
        .tophr{
            width:125px;
        }
        
        .author{
            color: white;
            display: inline;
            position: relative;
            text-align: left;
            color:white;
            top:500px;
            font-family:Georgia, 'Times New Roman', Times, serif;
            font-size: large;
        }
        
        .booktitle{
            font-family: 'georgia', monospace;
            font-size: x-large;
            text-align: center;
            position: relative;
            color:lightgreen;
            top: 19px;
        
        }
        
        .edition{
            color:orange;
            font-size: large;
            font-family: Arial, Helvetica, sans-serif;
            position:relative;
            text-align: left;
            top:410px;

        }
        

        .text-container {
             position: absolute;
             top: 320px;
             left: 50px; 
             color: black;
             font-size: x-large;
             font-family: 'franklin gothic', sans-serif; 
        }
        
        .text-containers {
             position: absolute;
             top: 360px;
             left: 80px; 
             color: black;
             font-size: x-large;
             font-family: 'franklin gothic', sans-serif; 
        }
        
        .space {
            color:orange;
            font-size: large;
            font-family: Arial, Helvetica, sans-serif;
            position:relative;
            text-align: left;
            top:380px;


        }
        .text-containerss {
             position: absolute;
             top: 400px;
             left: 115px; 
             color: black;
             font-size: x-large;
             font-family: 'georgia', sans-serif; 
        }

        </style>
        <title>Book Cover Page</title>
    </head>
    <body>
        <div class="bookpage">
            <div class="toptext" class>
                Martin Scorsese
            </div>
            
            <div class="tophr">
                <hr style="color: red;">
            </div>
            
            <div class="booktitle">
                <h2>"An Introduction to the Craft of the Director"</h2>
            </div>
                
            <div class="subtitle">
             
            </div>  
            
            
            
            <div class="text-container">
                <p>  </p>
            </div>
            
            <div class="text-containers">
                <p>  </p> 
            </div>
            
            <div class="text-containerss">
                <p>  </p>                  
            </div>

            <div class="author">
               <p><b>Dr.Aakashraj</b></p>
            </div>
            <div class="publisher">
                
            </div>
            
            <div class="edition">
                <h3>First Edition
                </h3>
            </div>
            
            <div class="space">
                <b>_____________________________________________</b>
            </div>
            
        </div>
    </body>
</html>
```


## Output:

![Book cover page](https://github.com/Aakashraj04/cover-page-design/assets/121117266/88004344-f8c3-404c-8f9d-7af1c33a9423)

## Server Output:
![serevr output 06](https://github.com/Aakashraj04/cover-page-design/assets/121117266/cf1fc104-1136-44f1-99cf-9e64035009a5)


## Result:
Book Cover Page created successfully.
