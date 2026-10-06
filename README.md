# IT-_DEPARTMENT-
<!DOCTYPE html>
<html>
<head>
    <title>Department of Information Technology - KCA University</title>
    <style>
        body {
            font-family: Arial;
            margin: 0;
            background-color: #f2f2f2;
        }
        header {
            background-color: #14275e;
            color: white;
            text-align: center;
            padding: 25px;
        }
        nav {
            background-color: white;
            text-align: center;
            padding: 15px;
        }
        nav a {
            margin: 15px;
            text-decoration: none;
            color: #14275e;
        }
        main {
            width: 80%;
            margin: auto;
        }
        section {
            background-color: white;
            padding: 20px;
            margin: 20px 0;
        }
        h2 {
            color: #14275e;
        }
        table {
            width: 100%;
            border-collapse: collapse;
        }
        th, td {
            border: 1px solid black;
            padding: 10px;
            text-align: left;
        }
        th {
            background-color: #14275e;
            color: white;
        }
        footer {
            background-color: #14275e;
            color: white;
            text-align: center;
            padding: 15px;
        }
    </style>
</head>
<body>
<header>
    <h1>Department of Information Technology</h1>
    <p>KCA University</p>
</header>
<nav>
    <a href="#home">Home</a>
    <a href="#courses">Courses</a>
    <a href="#contact">Contact</a>
</nav>
<main>
    <section id="home">
        <h2>Welcome</h2>
        <p>
            The Department of Information Technology at KCA University
            teaches students skills in software development, networking,
            databases and cybersecurity.
        </p>
        <p>
            Students also get practical skills that help them understand
            how technology is used in modern organisations.
        </p>
        <h3>IT Laboratory</h3>
        <img src="it-lab.jpg" alt="KCA University IT Laboratory" width="500">
        <p>
            Our IT laboratory provides students with computers and
            other equipment for practical learning.
        </p>
    </section>
    <section id="courses">
        <h2>Courses Offered</h2>
        <ul>
            <li>Bachelor of Science in Information Technology</li>
            <li>Bachelor of Science in Software Development</li>
            <li>Diploma in Information Technology</li>
            <li>Certificate in Networking and Cybersecurity</li>
        </ul>
        <h3>Course Codes</h3>
        <table>
            <tr>
                <th>Course Code</th>
                <th>Course Name</th>
            </tr>
            <tr>
                <td>BIT 1101</td>
                <td>Introduction to Information Technology</td>
            </tr>
            <tr>
                <td>BIT 1201</td>
                <td>Web Development with HTML and CSS</td>
            </tr>
            <tr>
                <td>BIT 2101</td>
                <td>Database Systems</td>
            </tr>
            <tr>
                <td>BIT 2202</td>
                <td>Computer Networks</td>
            </tr>
            <tr>
                <td>BIT 3101</td>
                <td>Cybersecurity Fundamentals</td>
            </tr>
        </table>
    </section>
    <section id="contact">
        <h2>Contact / Student Enquiry</h2>
        <form>
            <label>Name:</label><br>
            <input type="text" name="name"><br><br>
            <label>Email:</label><br>
            <input type="email" name="email"><br><br>
            <label>Message:</label><br>
            <textarea name="message" rows="5" cols="40"></textarea><br><br>
            <input type="submit" value="Send Enquiry">
        </form>
    </section>
</main>
<footer>
    <p>© 2026 Department of Information Technology, KCA University</p>
</footer>
</body>
</html>