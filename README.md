<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <title>College Admission Form</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            background: #f0f4f8;
            margin: 0;
            padding: 20px;
        }
        .container {
            max-width: 700px;
            margin: auto;
            background: white;
            padding: 30px;
            box-shadow: 0 0 10px rgba(0,0,0,0.1);
            border-radius: 8px;
        }
        h1 {
            text-align: center;
            color: #2c3e50;
        }
        label {
            display: block;
            margin-top: 15px;
            font-weight: bold;
        }
        input, select, textarea {
            width: 100%;
            padding: 10px;
            margin-top: 5px;
            border: 1px solid #ccc;
            border-radius: 5px;
        }
        button {
            margin-top: 20px;
            width: 100%;
            padding: 12px;
            background-color: #3498db;
            color: white;
            border: none;
            border-radius: 5px;
            font-size: 16px;
        }
        button:hover {
            background-color: #2980b9;
        }
    </style>
</head>
<body>

<div class="container">
    <h1>College Admission Form</h1>
    <form action="#" method="post">
        <label for="name">Full Name:</label>
        <input type="text" id="name" name="name" required>

        <label for="dob">Date of Birth:</label>
        <input type="date" id="dob" name="dob" required>

        <label for="email">Email ID:</label>
        <input type="email" id="email" name="email" required>

        <label for="phone">Contact Number:</label>
        <input type="tel" id="phone" name="phone" required>

        <label for="course">Select Course:</label>
        <select id="course" name="course" required>
            <option value="">--Select--</option>
            <option value="bsc">B.Sc</option>
            <option value="bcom">B.Com</option>
            <option value="ba">B.A</option>
            <option value="btech">B.Tech</option>
            <option value="mba">MBA</option>
        </select>

        <label for="address">Permanent Address:</label>
        <textarea id="address" name="address" rows="4" required></textarea>

        <button type="submit">Submit Application</button>
    </form>
</div>

</body>
</html>
