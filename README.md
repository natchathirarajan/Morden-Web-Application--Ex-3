# Exp-3 Create a Web-Layout using FLEXBOX.
## Aim:
To write html & css code to create Web-Layout using FLEXBOX.
## Algorithm:
### Step 1: 
Create a html code for the Web-Layout.
### Step 2:
Make style for the Web Layout using style tag.
### Step 3:
Include Style in the html using class and id Selector.
### Step 4:
Verify the output by running the Web-Layout in any web browser. 
## Program:
#### HTML & CSS:
```html
<!DOCTYPE html>
<html>
<head>
  <style>
    body {
      margin: 0;
      padding: 0;
      font-family: Arial, sans-serif;
    }
    .container {
      display: flex;
      flex-wrap: wrap;
    }
    .header {
      flex-basis: 100%;
      background-color: #41b3a3;
      padding: 100px;
      text-align: center;
    }
    .sidebar {
      flex-basis: 300px;
      background-color: #85DCB8;
      padding: 50px;
    }
    .main-content {
      flex-grow: 1;
      background-color: #ffffff;
      padding: 50px;
    }
    .footer {
      flex-basis: 100%;
      background-color: #41b3a3;
      padding: 20px;
      text-align: center;
    }
    @media (max-width: 768px) {
      .container {
        flex-direction: column;
      }
      .sidebar, .main-content {
        flex-basis: 100%;
      }
    }
  </style>
</head>
<body>
  <div class="container">
    <div class="header">
      <h1>VM Creators</h1>
    </div>
    <div class="sidebar">
      <h2>Our Works</h2>
      <ul>
        <li>React Webpage</li>
        <li>SpringBoot Webpage</li>
        <li>Angular Webpage</li>
      </ul>
    </div>
    <div class="main-content">
      <h1>Welcome to My Website</h1>
      <p>Lorem ipsum dolor sit amet, consectetur adipiscing elit. Curabitur tristique lectus id neque mollis semper. Sed ac tellus sed ex vulputate ultrices.</p>
    </div>
    <div class="footer">
      <p>&copy; 2023 My Website. All rights reserved.</p>
    </div>
  </div>
</body>
</html>
```
## OUTPUT:
![image](https://github.com/Karthikeyan21001828/MERN_EX03/assets/93427303/b08a1d80-d1e7-4182-bd42-a81cd6328b98)
## RESULT:
Thus the HTML & CSS code to create Web-Layout using FLEXBOX has been created and output has been verified.
