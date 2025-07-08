# Styled_Profile_Card
## Date:08-07-2025.

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
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>My Profile Card</title>
    <style>
        body {
            background-color: #a0e7e5;
            margin: 0;
            font-family: Arial, sans-serif;
            color: #333;
        }

        h1 {
            text-align: center;
            color: #0b3d91;
            margin-top: 20px;
        }

        h2 {
            text-align: center;
            color: #003366;
        }

        .flex-container {
            display: flex;
            justify-content: center;
            align-items: flex-start;
            flex-direction: row;
            padding: 30px;
            gap: 50px;
        }

        img {
            border-radius: 75%;
        }

        p {
            font-size: 16px;
            line-height: 1.6;
            max-width: 500px;
            color: #003049;
        }

        p:hover {
            background-color: #ffffff;
            padding: 10px;
            border-radius: 10px;
            transition: 0.3s;
        }

        hr {
            border: 1px solid #0077b6;
            margin: 20px auto;
            width: 80%;
        }

        section {
            padding: 20px;
        }
    </style>
</head>
<body>
    <section>
        <h1>Profile card</h1>
        <hr>
        <div class="flex-container">
            <div>
                <img src="myimg.jpg" alt="Profile Picture" width="200" height="200">
                <h2>Pavithra R</h2>
            </div>
            <div>
                <p>
                    Eager to venture into the horizons of Artificial Intelligence and Machine Learning.With a problem-solving
attitude of curiosity and a solid background in data-driven technologies,My goal is to address actual global issues using
intelligent, scalable, and responsible AI solutions.I am interested in model optimization, healthcare analytics, and
deep learning.I'm ever prepared to embrace challenges that lead to technological progress and social benefit.
                </p>
            </div>
        </div>
        <hr>
    </section>
</body>
</html>


```
## Output:

![Screenshot 2025-07-08 204016](https://github.com/user-attachments/assets/3afc10f4-05ef-43d4-8dca-f5d6bc68118e)


## Result:
A visually appealing profile card that demonstrates the use of background color, typography, spacing, and layout alignment techniques is designed.
