<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0"/>
  <title>Syed Muhammad Taha - CV</title>
  <style>
    * {
      margin: 0;
      padding: 0;
      box-sizing: border-box;
    }

    body {
      background: #121212;
      color: #ffffff;
      font-family: 'Segoe UI', sans-serif;
      display: flex;
      justify-content: center;
      align-items: center;
      padding: 30px;
      min-height: 100vh;
    }

    .container {
      width: 100%;
      max-width: 800px;
      background-color: #1e1e1e;
      padding: 40px;
      border-radius: 20px;
      box-shadow: 0 0 20px rgba(0, 255, 255, 0.2);
      text-align: center;
    }

    .profile-pic {
      width: 150px;
      height: 150px;
      border-radius: 50%;
      object-fit: cover;
      border: 4px solid #00e5ff;
      box-shadow: 0 0 15px #00e5ff;
      margin-bottom: 20px;
    }

    h1 {
      color: #00e5ff;
      margin-bottom: 10px;
    }

    p {
      margin: 5px 0;
      color: #ccc;
    }

    section {
      margin: 30px 0;
    }

    section h2 {
      color: #00bcd4;
      font-size: 1.5em;
      margin-bottom: 10px;
      border-bottom: 2px solid #00e5ff;
      display: inline-block;
      padding-bottom: 5px;
    }

    ul {
      list-style: none;
      padding: 0;
    }

    ul li {
      margin: 6px 0;
      color: #ddd;
      padding-left: 15px;
      position: relative;
    }

    ul li::before {
      content: "✔️";
      position: absolute;
      left: 0;
      color: #00e5ff;
    }
  </style>
</head>
<body>
  <div class="container">
    <header>
      <img src="TAHA (1).jpg" alt="Profile Picture" class="profile-pic" />
      <h1>Syed Muhammad Taha</h1>
      <p>📅 DOB: 02-Aug-2003</p>
      <p>📞 0300-12345678</p>
      <p>📧 Boss@gmail.com</p>
      <p>📍 Hussain Apartment, Water Pump</p>
    </header>
    
    <section>
      <h2>About Me</h2>
      <p>I am S.M Taha, currently studying Introduction to Programming from SMIT, taught by Sir Zubair.</p>
    </section>

    <section>
      <h2>Education</h2>
      <ul>
        <li><strong>University:</strong> BS Cyber Security from Ham University</li>
        <li><strong>Intermediate:</strong> ZYX College, 2022 Topper of Karachi</li>
        <li><strong>Matriculation:</strong> XYZ School, 2020 Topper of Karachi</li>
      </ul>
    </section>

    <section>
      <h2>Skills</h2>
      <ul>
        <li>Teaching Maths</li>
        <li>Teaching Physics</li>
        <li>Web Development</li>
      </ul>
    </section>

    <section>
      <h2>Hobbies</h2>
      <ul>
        <li>Gaming</li>
        <li>Learning Programming</li>
        <li>Cooking</li>
      </ul>
    </section>
  </div>
</body>
</html>

