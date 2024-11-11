<!DOCTYPE html>
<html lang="en" dir="ltr">
<head>
    <meta charset="UTF-8">
    <title>Meme Review Channel - Home</title>
    <style>
        /* CSS Styling */
        body {
            background-color: #95f5ff;
            font-family: Arial, sans-serif;
            color: #333;
            text-align: center;
        }
        .header {
            background-color: #b900ff;
            padding: 20px 0;
        }
        .header-text {
            font-size: 32px;
            color: #ffffff;
        }
        .sub-heading {
            font-size: 24px;
            color: #333;
            margin-top: 20px;
        }
        .intro-text {
            font-size: 18px;
            color: #333;
            margin-top: 30px;
            line-height: 1.6;
        }
        .goals-title {
            font-size: 28px;
            color: #333;
            margin-top: 40px;
            margin-bottom: 20px;
        }
        .goals-button {
            background-color: #b900ff;
            color: #fff;
            padding: 15px 30px;
            font-size: 20px;
            margin: 10px;
            border: none;
            cursor: pointer;
            border-radius: 5px;
            width: 250px;
        }
        .goals-button:hover {
            background-color: #95f5ff;
            color: #b900ff;
        }
        #goal-description {
            font-size: 16px;
            color: #333;
            padding: 20px;
            border: 1px solid #333;
            margin-top: 20px;
            background-color: #eaffea;
            display: none;
        }
        .footer {
            background-color: #b900ff;
            color: white;
            padding: 20px 0;
            margin-top: 40px;
        }
        .footer-text {
            font-size: 16px;
        }
        .footer-text a {
            color: white;
            text-decoration: none;
        }
    </style>
</head>

<body>

    <!-- Header Section -->
    <div class="header">
        <div class="header-text"><b>RUHUL AHAMED</b></div>
    </div>

    <!-- Introduction Section -->
    <div class="intro-text">
        <p><b>HI, I AM RUHUL AHAMED</b></p>
        <p>I am a Bachelor of Arts student in Political Science. My goal is to become an IBPS PO.</p>
        <p>I am very interested in programming language learning and website development.</p>
        <p>Feel free to connect with me:</p>
        <p>WhatsApp: <a href="tel:+9775872522">9775872522</a></p>
        <p>Email: <a href="mailto:ruhulahamed279@gmail.com">ruhulahamed279@gmail.com</a></p>
    </div>

    <!-- Future Goals Section -->
    <div class="goals-title"><b>FUTURE GOALS</b></div>

    <!-- Buttons for each goal -->
    <button class="goals-button" onclick="showGoal('IBPS_PO')">IBPS PO</button>
    <button class="goals-button" onclick="window.location.href='https://youtube.com/@lanchoasmr?si=EGOMjjrHT0M0g68A'">YOUTUBE</button>
    <button class="goals-button" onclick="showGoal('IBPS_CLERK')">IBPS CLERK</button>
    <button class="goals-button" onclick="showGoal('SBI_CLERK')">SBI CLERK</button>

    <!-- Description section -->
    <div id="goal-description"></div>

    <script>
        // JavaScript to display goal details based on the button clicked
        function showGoal(goal) {
            let description = document.getElementById("goal-description");
            description.style.display = "block"; // Show the description box

            // Set description based on goal
            if (goal === "IBPS_PO") {
                description.innerHTML = "<b>IBPS PO:</b> IBPS PO Exam is conducted every year by the Institute of Banking Personnel Selection (IBPS) to select eligible candidates for the post of Probationary Officers...";
            } else if (goal === "SBI_PO") {
                description.innerHTML = "<b>SBI PO:</b> SBI PO Exam is conducted by the State Bank of India (SBI) to select eligible candidates for the Probationary Officers (PO) vacancies...";
            } else if (goal === "IBPS_CLERK") {
                description.innerHTML = "<b>IBPS CLERK:</b> IBPS Clerk exam is conducted every year by the Institute of Banking Personnel Selection to recruit clerical posts...";
            } else if (goal === "SBI_CLERK") {
                description.innerHTML = "<b>SBI CLERK:</b> The SBI Clerk Exam is held annually by the State Bank of India to recruit candidates for the position of Junior Associate...";
            }
        }
    </script>

    <!-- Footer Section -->
    <div class="footer">
        <div class="footer-text">
            <p><b>Contact Us</b></p>
            <p>Email: <a href="mailto:support@gmail.com">support@gmail.com</a></p>
            <p>Phone: <a href="tel:+919775872522">+91 9775872522</a>, <a href="tel:+919883000980">+91 9883000980</a></p>
            <p><b>Location:</b> BATRIGACHH, PO: DINHATA, District: COOCHBEHAR</p>
            <p><b>Developer:</b> RUHUL AHAMED</p>
            <p><b>FIRST WEBSITE</b> - NEW</p>
            <p><b>Others</b></p>
            <p><a href="#">FAQ</a> | <a href="#">BUILD SOFTWARE</a> | <a href="#">Help site</a> | <a href="#">News</a> | <a href="#">Contact</a></p>
            <p>© 2024 Ruhul Ahamed. All rights reserved. This website and its content are for educational purposes only.</p>
        </div>
    </div>

</body>
</html>
