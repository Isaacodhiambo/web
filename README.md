# web
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Kenyan Page</title>
</head>
<body>
    <h1>Welcome to Kenya</h1>

    <h2>Top Kenyan Cities</h2>
    <ol type="I">
        <li>Nairobi</li>
        <li>Mombasa</li>
        <li>Kisumu</li>
        <li>Nakuru</li>
        <li>Eldoret</li>
    </ol>

    <h2>Beautiful Kenya</h2>
    <img src="https://www.pexels.com/photo/kenya-safari-123456/" alt="Kenyan Safari" width="600">

    <h2>Contact List</h2>
    <table border="1">
        <tr><th>Name</th><th>Address</th><th>Mobile</th><th>Email</th></tr>
        <tr><td>Wanjiku Mwangi</td><td>Nairobi</td><td>+254712345678</td><td>wanjiku@example.com</td></tr>
        <tr><td>Otieno Odhiambo</td><td>Kisumu</td><td>+254798765432</td><td>otieno@example.com</td></tr>
    </table>

    <h2>Registration Form</h2>
    <form>
        <label>Name: <input type="text" required></label><br>
        <label>Email: <input type="email" required></label><br>
        <label>Password: <input type="password" required></label><br>
        <label>County:
            <select required>
                <option>Nairobi</option>
                <option>Mombasa</option>
                <option>Kisumu</option>
            </select>
        </label><br>
        <input type="submit" value="Register">
    </form>
</body>
</html>
