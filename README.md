<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>HTML5 Features Demo</title>
  <style>
    body {
      font-family: Arial, sans-serif;
      line-height: 1.6;
      margin: 20px;
    }
    table {
      border-collapse: collapse;
      width: 100%;
    }
    table, th, td {
      border: 1px solid #ccc;
    }
    th, td {
      padding: 10px;
      text-align: left;
    }
    form {
      margin-top: 20px;
    }
  </style>
</head>
<body>

  <!-- Header Section -->
  <header>
    <h1>Welcome to Our HTML5 Demo Page</h1>
    <p>This page demonstrates the use of images, lists, tables, forms, and multimedia using HTML5.</p>
  </header>

  <!-- Ordered List with Roman Numerals -->
  <section>
    <h2>I. Features Overview</h2>
    <ol type="I">
      <li>Images</li>
      <li>Lists</li>
      <li>Tables</li>
      <li>Forms</li>
      <li>Multimedia</li>
    </ol>
  </section>

  <!-- External Image from Pexels -->
  <section>
    <h2>II. Featured Image</h2>
    <img 
      src="https://images.pexels.com/photos/414612/pexels-photo-414612.jpeg" 
      alt="Scenic Landscape" 
      width="600" />
  </section>

  <!-- Table of 5 Contacts -->
  <section>
    <h2>III. Contact List</h2>
    <table>
      <thead>
        <tr>
          <th>Name</th>
          <th>Address</th>
          <th>Mobile</th>
          <th>Email</th>
        </tr>
      </thead>
      <tbody>
        <tr><td>Alice Mwangi</td><td>Nairobi</td><td>0700000001</td><td>alice@example.com</td></tr>
        <tr><td>Brian Otieno</td><td>Kisumu</td><td>0700000002</td><td>brian@example.com</td></tr>
        <tr><td>Carol Wanjiru</td><td>Thika</td><td>0700000003</td><td>carol@example.com</td></tr>
        <tr><td>Daniel Kiptoo</td><td>Eldoret</td><td>0700000004</td><td>daniel@example.com</td></tr>
        <tr><td>Esther Njeri</td><td>Machakos</td><td>0700000005</td><td>esther@example.com</td></tr>
      </tbody>
    </table>
  </section>

  <!-- Registration Form -->
  <section>
    <h2>IV. Registration Form</h2>
    <form action="#" method="post">
      <!-- Name -->
      <label for="name">Full Name:</label><br />
      <input type="text" id="name" name="name" placeholder="Enter your full name" required /><br /><br />

      <!-- Email -->
      <label for="email">Email Address:</label><br />
      <input type="email" id="email" name="email" placeholder="e.g. yourname@example.com" required /><br /><br />

      <!-- Password -->
      <label for="password">Password:</label><br />
      <input type="password" id="password" name="password" minlength="6" placeholder="Enter a strong password" required /><br /><br />

      <!-- Date -->
      <label for="dob">Date of Birth:</label><br />
      <input type="date" id="dob" name="dob" required /><br /><br />

      <!-- Dropdown -->
      <label for="course">Choose a course:</label><br />
      <select id="course" name="course" required>
        <option value="">--Select--</option>
        <option value="cs">Computer Science</option>
        <option value="it">Information Technology</option>
        <option value="ds">Data Science</option>
      </select><br /><br />

      <!-- Radio Buttons -->
      <label>Gender:</label><br />
      <input type="radio" id="male" name="gender" value="male" required />
      <label for="male">Male</label><br />
      <input type="radio" id="female" name="gender" value="female" />
      <label for="female">Female</label><br /><br />

      <!-- Checkboxes -->
      <label>Skills:</label><br />
      <input type="checkbox" id="html" name="skills" value="HTML" />
      <label for="html">HTML</label><br />
      <input type="checkbox" id="css" name="skills" value="CSS" />
      <label for="css">CSS</label><br />
      <input type="checkbox" id="js" name="skills" value="JavaScript" />
      <label for="js">JavaScript</label><br /><br />

      <button type="submit">Register</button>
    </form>
  </section>

  <!-- Multimedia Section -->
  <section>
    <h2>V. Multimedia</h2>

    <!-- Audio Element -->
    <h3>Listen to a Sample Audio:</h3>
    <audio controls>
      <source src="https://www.soundhelix.com/examples/mp3/SoundHelix-Song-1.mp3" type="audio/mpeg">
      Your browser does not support the audio element.
    </audio>

    <!-- Video Element -->
    <h3>Watch a Sample Video:</h3>
    <video width="600" controls>
      <source src="https://www.w3schools.com/html/mov_bbb.mp4" type="video/mp4">
      Your browser does not support the video tag.
    </video>
  </section>

  <!-- Footer -->
  <footer>
    <p>&copy; 2025 HTML5 Demo by Carlos Ndeda Dembede. All rights reserved.</p>
  </footer>

</body>
</html>
