# Styled_Profile_Card
## Date:08.07.2025

## Objective:
To practice HTML and CSS fundamentals by designing a visually appealing profile card that demonstrates the use of background color, typography, spacing, and layout alignment techniques.

## Tasks:
#### 1. Create the HTML Structure:
Use ```<!DOCTYPE html>, <html>, <head>, and <body>``` to define the structure.
Add a ```<title>``` like "My Profile Card".

#### 2. Add Content:
Include name, title (e.g., Developer, Student), and a short bio using semantic tags such as ```<h1>```, ```<h2>```, and ```<p>```.

#### 3. Add a Profile Image:
Use the ```<img>``` tag to include a profile picture with appropriate alt, width, and height attributes.

#### 4. Apply Background Color:
Use a CSS class to style the card with a background color.

#### 5. Style Typography:
Use CSS to apply different font families, sizes, and text colors for the name and bio.

#### 6. Add Spacing:
Apply margin and padding to improve spacing between elements using CSS.

#### 7. Center the Card:
Use flexbox or margin: auto to center the card vertically and horizontally on the page.

#### 8. Add Hover Effects:
Enhance interactivity with simple hover effects like border changes or background transition using CSS.

## HTML Code:
```
<!DOCTYPE html>
<html lang="en">
<head>
    <title>My Profile</title>
     <link href="style.css" rel="stylesheet">
</head>
<body>

    <h1>S.Yogabharathi</h1>
    <h2>Student,Web developer</h2>
    
    <img src="profile.png" alt="Profile Picture of Yogabharathi" width="200" height="200">
    
    <hr>
    
    <section>
        <h3>About Me</h3>
        <p>
            I am currently pursuing Artificial Intelligence and Data Science. I am passionate about artificial intelligence, natural language generation, and developing solutions that connect data with decision-making. I have a keen interest in data-driven problem solving.
        </p>
    </section>

    <hr>

    <section>
        <h3>Interests</h3>
        <p>
        Reading books,Colouring,Playing Chess
        </p>
    </section>

    <hr>

  <section>
        <h3>Soft Skills</h3>
        <p>Communication,Problem Solving,Leadership</p>
    </section>
</hr>
<hr>
     <section>
        <h3>Technical Skills</h3>
        <p>Java,Python,C programming</p>

    </section>
    </hr>
    <hr>
    <section>
        <h3>Contact</h3>
        <p>Email:yogabharathi76@gmail.com</p>
        <p>Location: Chennai, Tamil Nadu</p>
    </section>
</hr>
</body>
</html>
```
## CSS code

```
body {
    font-family: Arial, sans-serif;
    background-color: white;
    margin: 20px;
}
h1, h2, h3 {
    text-align: center;
    color: black;
}
img {
    display: block;
    border-radius: 10px;
    margin: 0 auto;
    border: 3px solid grey;
}
section {
    background-color:white;
    padding: 15px;
    margin: 20px auto;
    width: 80%;
    border-radius: 8px;
}
p {
    line-height: 1.6;
}
hr {
    border: none;
    height: 2px;
    background-color:grey;
    margin: 20px 0;
}
```

## Output:
![image](https://github.com/user-attachments/assets/f08e5277-1b9c-4c0b-ba79-40bb9641d7fe)

## Result:
A visually appealing profile card that demonstrates the use of background color, typography, spacing, and layout alignment techniques is designed.
