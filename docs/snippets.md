# Code Snippets

## HTML Website Skeleton
Below is a basic HTML template for a website:
```html title="index.html" linenums="1"
<!DOCTYPE html>
<head>
    <title>My Website</title>
    <link rel="stylesheet" type="text/css" href="style.css">
</head>
<html>
    <body>
        <header>
            <nav>
                <li><a href = "index.html">Home</a></li>
                <li><a href = "about.html">About</a></li>
                <li><a href = "contact.html">Contact</a></li>
            </nav>
        </header>

        <main>
            <div class = "home-header">
                <h1>Welcome to my website</h1>
                <p>Explore my webpage and what it has to offer.</p>
            </div>
        </main>

        <footer>
            <p>Created by @nornfang058 on https://nornfang058.github.io/wiki-docs/</p>
        </footer>
    </body>
</html>
```

## Java Program Skeleton
Below is a basic Java template for a program:
```java title="MyProgram.java" linenums="1"
public class MyProgram
{
    public static void main(String[] args)
    {
        System.out.println("Hello World");
    }

    public static void myMethod(String myName)
    {
        System.out.println("My name is " + myName);
    }
}
```