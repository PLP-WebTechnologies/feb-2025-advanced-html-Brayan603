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
    <title>Advanced HTML5 Elements</title>
    <style>
        table {
            width: 100%;
            border-collapse: collapse;
            margin-top: 20px;
        }
        th, td {
            border: 1px solid black;
            padding: 10px;
            text-align: left;
        }
        th {
            background-color: #f4f4f4;
        }
        form {
            max-width: 400px;
            margin-top: 20px;
        }
        label {
            display: block;
            margin-top: 10px;
        }
    </style>
</head>
<body>
    <h1>Advanced HTML5 Elements</h1>
    
    <!-- Ordered List with Roman Numerals -->
    <h2>Ordered List</h2>
    <ol type="I">
        <li>First Item</li>
        <li>Second Item</li>
        <li>Third Item</li>
    </ol>
    
    <!-- External Image -->
    <h2>External Image</h2>
    <img src="https://images.pexels.com/photos/12345/pexels-photo-12345.jpeg" alt="Sample Image from Pexels" width="500">
    
    <!-- Table with Contacts -->
    <h2>Contact List</h2>
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
            <td>+1234567890</td>
            <td>john@example.com</td>
        </tr>
        <tr>
            <td>Jane Smith</td>
            <td>456 Oak Ave</td>
            <td>+0987654321</td>
            <td>jane@example.com</td>
        </tr>
        <tr>
            <td>Michael Brown</td>
            <td>789 Pine Rd</td>
            <td>+1122334455</td>
            <td>michael@example.com</td>
        </tr>
        <tr>
            <td>Emily Johnson</td>
            <td>321 Cedar Ln</td>
            <td>+5566778899</td>
            <td>emily@example.com</td>
        </tr>
        <tr>
            <td>David Wilson</td>
            <td>654 Birch Blvd</td>
            <td>+6677889900</td>
            <td>david@example.com</td>
        </tr>
    </table>
    
    <!-- Registration Form -->
    <h2>Registration Form</h2>
    <form>
        <label for="name">Full Name:</label>
        <input type="text" id="name" name="name" placeholder="Enter your full name" required>
        
        <label for="email">Email:</label>
        <input type="email" id="email" name="email" placeholder="Enter your email" required>
        
        <label for="password">Password:</label>
        <input type="password" id="password" name="password" placeholder="Enter your password" required>
        
        <label for="dob">Date of Birth:</label>
        <input type="date" id="dob" name="dob" required>
        
        <label for="gender">Gender:</label>
        <input type="radio" id="male" name="gender" value="male" required> Male
        <input type="radio" id="female" name="gender" value="female" required> Female
        
        <label for="country">Country:</label>
        <select id="country" name="country" required>
            <option value="">Select your country</option>
            <option value="usa">USA</option>
            <option value="uk">UK</option>
            <option value="canada">Canada</option>
            <option value="australia">Australia</option>
        </select>
        
        <label>Interests:</label>
        <input type="checkbox" name="interest" value="sports"> Sports
        <input type="checkbox" name="interest" value="music"> Music
        <input type="checkbox" name="interest" value="travel"> Travel
        
        <br><br>
        <button type="submit">Register</button>
    </form>
</body>
</html>

