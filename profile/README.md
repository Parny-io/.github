<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <link href="https://fonts.googleapis.com/css2?family=Poppins:wght@400;600&display=swap" rel="stylesheet">
    <style>
        body, html {
            margin: 0;
            padding: 0;
            font-family: 'Poppins', Arial, Helvetica, sans-serif;
            background-color: #f4f4f4;
        }
        .container {
            max-width: 600px;
            margin: 0 auto;
            background-color: #ffffff;
            box-shadow: 0 0 10px rgba(0, 0, 0, 0.1);
            border-radius: 8px;
            overflow: hidden;
        }
        .header {
            background-color: #5e4099;
            color: white;
            text-align: center;
            padding: 20px 0;
        }
        .header img {
            max-width: 250px;
        }
        .content {
            padding: 20px;
            color: #333333;
            line-height: 1.6;
        }
        .content a {
            color: #f16822;
            text-decoration: none;
            display: block;
            margin-bottom: 10px;
        }
        .divider {
            border-top: 1px solid #e0e0e0;
            margin: 20px 0;
        }
        .footer {
            text-align: center;
            padding: 10px;
            font-size: 12px;
            color: #999999;
        }
        .social-icons {
            margin-top: 10px;
        }
        .social-icons img {
            margin: 0 5px;
        }
    </style>
</head>
<body>
    <div class="container">
        <div class="header">
            <img src="https://cdn.parny.io/parny/PARNY_1_white.png" alt="Parny Logo">
        </div>
        <div class="content">
          <h4>Interactive On-Call Management & Alerting Service</h4>
          <p>Manage on-call, respond to alerts, follow incident flow like social media timeline and get reports of your status on Analytics page.</p>
        </div>
        <div class="divider"></div>
        <div class="footer">
            <div class="social-icons">
                <a href="https://twitter.com/parnyio" target="_blank"><img src="https://cdn.parny.io/parny/square-twitter.png" alt="Twitter" height="32px"></a>
                <a href="https://www.linkedin.com/company/parny-io" target="_blank"><img src="https://cdn.parny.io/parny/linkedin.png" alt="LinkedIn" height="32px"></a>
                <a href="https://www.instagram.com/parny.io" target="_blank"><img src="https://cdn.parny.io/parny/square-instagram.png" alt="Instagram" height="32px"></a>
                <a href="mailto:support@parny.io" target="_blank"><img src="https://cdn.parny.io/parny/square-mail.png" alt="Contact Support" height="32px"></a>
            </div>
            <p>&copy; <span id="currentYear"></span> Parny. All rights reserved.</p>
        </div>
    </div>
    <script>
        document.getElementById('currentYear').textContent = new Date().getFullYear();
    </script>
</body>
</html>
