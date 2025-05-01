# Advanced HTML5 Elements and Forms

## Objectives
Implement HTML5 images, lists, tables, forms and input types.
Use form validation attributes.
Apply multimedia elements such as audio and video.

## Instructions

- Create an index.html file.
- Add an ordered list with roman numerals
- Add an external image from pexels.com
- Add a table of 5 contacts with; name, address, mobile and emails
- Add a registration form

>[!NOTE]
>  The registration form should have:
>- Name, email, password, and date fields.
>- A dropdown, radio buttons, and checkboxes.
>- Proper labels and placeholders.
>- Required fields and validation attributes.
>- Ensure proper indentation and commenting.
 
# Tasks
- Create a well-structured HTML5 document.
- Ensure semantic correctness.

Happy Coding! 💻✨

<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>HTML5 Elements Demo</title>
</head>
<body>
    <!-- Ordered list with Roman numerals -->
    <h1>My Ordered List</h1>
    <ol type="I">
        <li>First item</li>
        <li>Second item</li>
        <li>Third item</li>
    </ol>

    <!-- External image from pexels.com -->
    <h2>Beautiful Nature Image</h2>
    <img src="https://images.pexels.com/photos/414171/pexels-photo-414171.jpeg" alt="Nature Image" width="500">

    <!-- Table of contacts -->
    <h2>Contact List</h2>
    <table border="1">
        <thead>
            <tr>
                <th>Name</th>
                <th>Address</th>
                <th>Mobile</th>
                <th>Email</th>
            </tr>
        </thead>
        <tbody>
            <tr>
                <td>John Doe</td>
                <td>123 Main St</td>
                <td>+1234567890</td>
                <td>john@example.com</td>
            </tr>
            <tr>
                <td>Jane Smith</td>
                <td>456 Elm St</td>
                <td>+1987654321</td>
                <td>jane@example.com</td>
            </tr>
            <tr>
                <td>Mike Brown</td>
                <td>789 Oak St</td>
                <td>+1122334455</td>
                <td>mike@example.com</td>
            </tr>
            <tr>
                <td>Susan Green</td>
                <td>321 Pine St</td>
                <td>+1223344556</td>
                <td>susan@example.com</td>
            </tr>
            <tr>
                <td>Linda White</td>
                <td>654 Maple St</td>
                <td>+1445566778</td>
                <td>linda@example.com</td>
            </tr>
        </tbody>
    </table>

    <!-- Registration form -->
    <h2>Registration Form</h2>
    <form>
        <!-- Name field -->
        <label for="name">Name:</label>
        <input type="text" id="name" name="name" placeholder="Enter your name" required><br><br>

        <!-- Email field -->
        <label for="email">Email:</label>
        <input type="email" id="email" name="email" placeholder="Enter your email" required><br><br>

        <!-- Password field -->
        <label for="password">Password:</label>
        <input type="password" id="password" name="password" placeholder="Enter password" required minlength="6"><br><br>

        <!-- Date field -->
        <label for="dob">Date of Birth:</label>
        <input type="date" id="dob" name="dob" required><br><br>

        <!-- Dropdown -->
        <label for="country">Country:</label>
        <select id="country" name="country" required>
            <option value="">Select your country</option>
            <option value="usa">USA</option>
            <option value="uk">UK</option>
            <option value="canada">Canada</option>
            <option value="australia">Australia</option>
        </select><br><br>

        <!-- Radio buttons -->
        <label>Gender:</label><br>
        <input type="radio" id="male" name="gender" value="male" required>
        <label for="male">Male</label>
        <input type="radio" id="female" name="gender" value="female">
        <label for="female">Female</label>
        <input type="radio" id="other" name="gender" value="other">
        <label for="other">Other</label><br><br>

        <!-- Checkboxes -->
        <label>Interests:</label><br>
        <input type="checkbox" id="sports" name="interests" value="sports">
        <label for="sports">Sports</label>
        <input type="checkbox" id="music" name="interests" value="music">
        <label for="music">Music</label>
        <input type="checkbox" id="travel" name="interests" value="travel">
        <label for="travel">Travel</label><br><br>

        <button type="submit">Register</button>
    </form>

    <!-- Audio and Video elements -->
    <h2>Sample Audio</h2>
    <audio controls>
        <source src="sample-audio.mp3" type="audio/mpeg">
        Your browser does not support the audio element.
    </audio>

    <h2>Sample Video</h2>
    <video width="500" controls>
        <source src="sample-video.mp4" type="video/mp4">
        Your browser does not support the video tag.
    </video>
</body>
</html>

