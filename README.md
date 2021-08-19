# Basic_HTML_Tags
## Zen Class - Day 9 Task

1.Fix the bugs in below snippet
```
    <html lang="en">
    <head>
        <title>
        Document Guvi
        </title>
    </head>
    <body>
        <div>
            Lorem ipsum dolor sit amet consectetur adipisicing elit
            <div>
                Guvi Geek Network
            </div>
        </div>
    </body>
    </html>
    
```

2. Try the below one
```
    <html lang="en">
    <head>
        <title>
        Document Guvi
        </title>
    </head>
    <body>
        <div style=color:"red";>
            Lorem ipsum dolor sit amet consectetur adipisicing elit
            <div>
                Guvi Geek Network
            </div>
        </div>
    </body>
    </html>

```

3.Design a contact us form with all fields as required.



4.Use certain HTML elements to display the following in a HTML page.

```
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Document</title>
</head>
<body>
    <ul style="list-style:disc;">
        <li>Programming Languages 
            <ul style="list-style:circle;">
                <li>javascript
                    <ol style="list-style-type: lower-alpha;">
                        <li>Angular</li>
                        <li>React</li>
                        <li>Vue.js</li>    
                    </ol>
                </li>
                <li>Python
                    <ol style="list-style-type: lower-alpha;">
                        <li>Django Framework</li>
                        <li>Flask Framework</li>   
                    </ol>
                </li>
                <li>java
                    <ol style="list-style-type: lower-alpha;">
                        <li>Spring</li>
                        <li>Maven</li>
                        <li>Hibernate</li>    
                    </ol>
                </li>
            </ul>
        </li>
        <li>Database
            <ul style="list-style:circle;">
                <li>MySQL</li>
                <li>MongoDB</li>
                <li>Cansandra</li>
            </ul>
        </li>
    </ul>
</body>
</html>

```
### Output:

<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
</head>
<body>
    <ul style="list-style:disc;">
        <li>Programming Languages 
            <ul style="list-style:circle;">
                <li>javascript
                    <ol style="list-style-type: lower-alpha;">
                        <li>Angular</li>
                        <li>React</li>
                        <li>Vue.js</li>    
                    </ol>
                </li>
                <li>Python
                    <ol style="list-style-type: lower-alpha;">
                        <li>Django Framework</li>
                        <li>Flask Framework</li>   
                    </ol>
                </li>
                <li>java
                    <ol style="list-style-type: lower-alpha;">
                        <li>Spring</li>
                        <li>Maven</li>
                        <li>Hibernate</li>    
                    </ol>
                </li>
            </ul>
        </li>
        <li>Database
            <ul style="list-style:circle;">
                <li>MySQL</li>
                <li>MongoDB</li>
                <li>Cansandra</li>
            </ul>
        </li>
    </ul>
</body>
</html>


5. Create an element that helps you to open the https://google.com in separate new tab.

```
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Document</title>
</head>
<body>
    <a href="https://google.com" target="_blanck" style="text-decoration: none;">Click Here to visit Google</a>
</body>
</html>

```

### Output:

<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
</head>
<body>
    <a href="https://google.com" target="_blanck" style="text-decoration: none;">Click Here to visit Google</a><br><br><br>
</body>
</html>

10. In your, HTML page add the below line and Highlight it without using any CSS.

```
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Document</title>
</head>
<body>
    <mark><em>"HTML & CSS is awesome"<em></mark>
</body>
</html>

```

### output:

<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
</head>
<body>
    <mark><em>"HTML & CSS is awesome"</em></mark><br><br><br>
</body>
</html>

11. Create an HTML page, which should contain all types of input elements.

```
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
</head>
<body>
    <ol>Displaying All Input Types

        <li><label> Button:</label><input type="button" style="margin-left: 25px;"></li><br>
        <li><label> Check:</label><input type="checkbox" style="margin-left: 25px;"></li><br>
        <li><label> Color:</label><input type="color" style="margin-left: 25px;"></li><br>
        <li><label> Date:</label><input type="date" style="margin-left: 25px;"></li><br>
        <li><label> Date Time:</label><input type="datetime-local" style="margin-left: 25px;"></li><br>
        <li><label> email:</label><input type="email" style="margin-left: 25px;"></li><br>
        <li><label> File:</label><input type="file" style="margin-left: 25px;"></li><br>
        <li><label> Hidden:</label><input type="hidden" style="margin-left: 25px;"></li><br>
        <li><label> Image:</label><input type="image" style="margin-left: 25px;"></li><br>
        <li><label> Month:</label><input type="month" style="margin-left: 25px;"></li><br>
        <li><label> Number:</label><input type="number" style="margin-left: 25px;"></li><br>
        <li><label> Password:</label><input type="password" style="margin-left: 25px;"></li><br>
        <li><label> Radio:</label><input type="radio" style="margin-left: 25px;"></li><br>
        <li><label> Range:</label><input type="range" style="margin-left: 25px;"></li><br>
        <li><label> Reset:</label><input type="reset" style="margin-left: 25px;"></li><br>
        <li><label> Search:</label><input type="search" style="margin-left: 25px;"></li><br>
        <li><label> Submit:</label><input type="submit" style="margin-left: 25px;"></li><br>
        <li><label> Telephone:</label><input type="tel" style="margin-left: 25px;"></li><br>
        <li><label> Text:</label><input type="text" style="margin-left: 25px;"></li><br>
        <li><label> Time:</label><input type="time" style="margin-left: 25px;"></li><br>
        <li><label> url:</label><input type="url" style="margin-left: 25px;"></li><br>
        <li><label> Week:</label><input type="week" style="margin-left: 25px;"></li><br>

    </ol>
</body>
</html>

```

