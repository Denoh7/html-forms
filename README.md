<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>Student Registration Form</title>
</head>
<body>

<h2>Student Registration Form</h2>

<form action="submit_registration.php" method="post">
    <div>
        <label for="name">Name:</label>
        <input type="text" id="name" name="name" required>
    </div>
    <div>
        <label for="dob">Date of Birth:</label>
        <input type="date" id="dob" name="dob" required>
    </div>
    <div>
        <label for="gender">Gender:</label>
        <select id="gender" name="gender" required>
            <option value="">Select Gender</option>
            <option value="male">Male</option>
            <option value="female">Female</option>
            <option value="other">Other</option>
        </select>
    </div>
    <div>
        <label for="address">Address:</label>
        <textarea id="address" name="address" required></textarea>
    </div>
    <div>
        <label for="telephone">Telephone:</label>
        <input type="tel" id="telephone" name="telephone" required>
    </div>
    <div>
        <label for="email">Email Address:</label>
        <input type="email" id="email" name="email" required>
    </div>
    <div>
        <label for="course">Course:</label>
        <input type="text" id="course" name="course" required>
    </div>
    <div>
        <button type="submit">Register</button>
        <button type="button" onclick="cancel()">Cancel</button>
    </div>
</form>
</body>
</html>
