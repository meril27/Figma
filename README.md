# Ex09 Event Registration Web Application
## Date: 18.12.2024

## AIM:
To design, develop and deploy a web application for event registration.

## DESIGN STEPS:

### Step 1:
Create a new frame.

### Step 2:
Select any one preset size of your choice.

### Step 3:
Select the shapes you need.

### Step 4:
Import images as needed.

### Step 5:
Create pages based on your need and link them.

### Step 6:

Validate the HTML and CSS code.

### Step 6:

Publish the website in the given URL.

## DESIGN TOOL:
Figma

## CODE:
```
Home Page

<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Zazzle '24 - Home Page</title>
    <link rel="stylesheet" href="style.css">
</head>
<body>
    <div class="container">
        <h1>Zazzle '24</h1>
        <img src="logo.png" alt="College Logo" class="logo">
        <h2 class="highlight">DANCE EVENTS</h2>
        <div>
            <a href="events.html"><button>View Events</button></a>
            <a href="register.html"><button>Register</button></a>
        </div>
        <p class="quote">"Where tripping over your feet is considered a signature move."</p>
    </div>
</body>
</html>

Events Page 

<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Zazzle '24 - Events Page</title>
    <link rel="stylesheet" href="style.css">
</head>
<body>
    <div class="container">
        <h1>DANCE EVENTS</h1>
        <ul class="event-list">
            <li>Folk Dance</li>
            <li>Western Dance</li>
            <li>Classical Dance</li>
            <li>Hip Hop</li>
            <li>Ballet</li>
        </ul>
    </div>
</body>
</html>

Registration Page

<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Zazzle '24 - Registration Page</title>
    <link rel="stylesheet" href="style.css">
</head>
<body>
    <div class="container">
        <h1>Registration Form</h1>
        <form>
            <label>Name:</label>
            <input type="text" name="name" required>

            <label>Register No:</label>
            <input type="text" name="register_no" required>

            <label>Department:</label>
            <input type="text" name="department" required>

            <label>Email:</label>
            <input type="email" name="email" required>

            <label>Events to Register:</label>
            <input type="text" name="events" required>

            <button type="submit">Submit</button>
        </form>
    </div>
</body>
</html>

Contact Page

<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Zazzle '24 - Contact Page</title>
    <link rel="stylesheet" href="style.css">
</head>
<body>
    <div class="container">
        <h1>THANK YOU!</h1>
        <p>Ignite your passion for dance at this electrifying celebration!</p>
        <h2>Contact Us</h2>
        <p>Email: saveethaengineeringcollege@gmail.com</p>
        <p>Phone: +91 95674 36568 <br> +044 56789057</p>
    </div>
</body>
</html>

* {
    margin: 0;
    padding: 0;
    box-sizing: border-box;
    font-family: Arial, sans-serif;
}

body {
    background: linear-gradient(to bottom, #e2f4f9, #ffdde1);
    color: #333;
    text-align: center;
    min-height: 100vh;
    display: flex;
    justify-content: center;
    align-items: center;
}

.container {
    width: 350px;
    background: #fff;
    border-radius: 12px;
    box-shadow: 0 4px 8px rgba(0, 0, 0, 0.2);
    padding: 20px;
}

h1 {
    font-size: 26px;
    color: #4b0082;
    margin-bottom: 10px;
}

h2.highlight {
    color: #009933;
    margin: 10px 0;
}

img.logo {
    width: 80px;
    margin: 10px auto;
    display: block;
}

button {
    background-color: #036bb9;
    color: white;
    border: none;
    padding: 10px 20px;
    margin: 10px;
    border-radius: 8px;
    cursor: pointer;
    font-size: 16px;
}

button:hover {
    background-color: #02569c;
}

.quote {
    font-size: 14px;
    font-style: italic;
    color: #555;
    margin-top: 20px;
}

ul.event-list {
    list-style: none;
    padding: 0;
}

ul.event-list li {
    font-size: 18px;
    margin: 10px 0;
    color: #036bb9;
}

form {
    display: flex;
    flex-direction: column;
    text-align: left;
}

label {
    margin: 10px 0 5px;
    font-weight: bold;
}

input {
    padding: 8px;
    border: 1px solid #ccc;
    border-radius: 5px;
}

footer {
    margin-top: 20px;
    font-size: 14px;
    color: #555;
}
```

## OUTPUT:
![alt text](<Screenshot 2024-12-18 201342.png>)

## RESULT:
The program to design, develop and deploy a web application for event registration is completed successfully.
