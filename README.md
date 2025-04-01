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
<!DOCTYPE html><html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Advanced HTML5 Elements</title>
    <style>
        table, th, td {
            border: 1px solid black;
            border-collapse: collapse;
            padding: 8px;
        }
    </style>
</head>
<body>
    <header>
        <h1>Advanced HTML5 Elements and Forms</h1>
    </header><!-- Ordered List with Roman Numerals -->
<section>
    <h2>Ordered List</h2>
    <ol type="I">
        <li>First Item</li>
        <li>Second Item</li>
        <li>Third Item</li>
        <li>Fourth Item</li>
        <li>Fifth Item</li>
    </ol>
</section>

<!-- External Image -->
<section>
    <h2>Image from Pexels</h2>
    <img src="https://www.pexels.com/photo/sample-image.jpg" alt="Sample Image from Pexels" width="600">
</section>

<!-- Contacts Table -->
<section>
    <h2>Contacts Table</h2>
    <table>
        <tr>
            <th>Name</th>
            <th>Address</th>
            <th>Mobile</th>
            <th>Email</th>
        </tr>
        <tr>
            <td>John Doe</td>
            <td>123 Main St</td>
            <td>123-456-7890</td>
            <td>johndoe@example.com</td>
        </tr>
        <tr>
            <td>Jane Smith</td>
            <td>456 Elm St</td>
            <td>987-654-3210</td>
            <td>janesmith@example.com</td>
        </tr>
        <tr>
            <td>Michael Brown</td>
            <td>789 Oak St</td>
            <td>555-666-7777</td>
            <td>michaelbrown@example.com</td>
        </tr>
        <tr>
            <td>Emily White</td>
            <td>321 Pine St</td>
            <td>444-555-6666</td>
            <td>emilywhite@example.com</td>
        </tr>
        <tr>
            <td>Chris Black</td>
            <td>654 Cedar St</td>
            <td>222-333-4444</td>
            <td>chrisblack@example.com</td>
        </tr>
    </table>
</section>

<!-- Registration Form -->
<section>
    <h2>Registration Form</h2>
    <form action="#" method="post">
        <label for="name">Full Name:</label>
        <input type="text" id="name" name="name" placeholder="Enter your full name" required>
        <br><br>
        
        <label for="email">Email:</label>
        <input type="email" id="email" name="email" placeholder="Enter your email" required>
        <br><br>
        
        <label for="password">Password:</label>
        <input type="password" id="password" name="password" placeholder="Enter your password" required>
        <br><br>
        
        <label for="dob">Date of Birth:</label>
        <input type="date" id="dob" name="dob" required>
        <br><br>
        
        <label for="gender">Gender:</label>
        <input type="radio" id="male" name="gender" value="male"> <label for="male">Male</label>
        <input type="radio" id="female" name="gender" value="female"> <label for="female">Female</label>
        <br><br>
        
        <label for="country">Country:</label>
        <select id="country" name="country">
            <option value="us">United States</option>
            <option value="uk">United Kingdom</option>
            <option value="ca">Canada</option>
            <option value="au">Australia</option>
        </select>
        <br><br>
        
        <label>Interests:</label>
        <input type="checkbox" id="sports" name="interests" value="sports"> <label for="sports">Sports</label>
        <input type="checkbox" id="music" name="interests" value="music"> <label for="music">Music</label>
        <input type="checkbox" id="travel" name="interests" value="travel"> <label for="travel">Travel</label>
        <br><br>
        
        <input type="submit" value="Register">
    </form>
</section>

</body>
</html>
