<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<title>RHEL 8 Hardening</title>

<style>
    body {
        font-family: 'Segoe UI';
        margin: 0;
        background: #121212;
        color: #eee;
    }

    header {
        background: #ff4b2b;
        padding: 20px;
        text-align: center;
        font-size: 28px;
        font-weight: bold;
    }

    .container {
        padding: 40px;
        max-width: 900px;
        margin: auto;
    }

    .card {
        background: #1e1e1e;
        padding: 20px;
        margin-bottom: 20px;
        border-radius: 12px;
        border-left: 5px solid #ff4b2b;
    }

    h3 {
        margin-top: 0;
    }

    code {
        display: block;
        background: #000;
        padding: 10px;
        margin-top: 10px;
        border-radius: 5px;
        color: #00ff9f;
    }

    .back {
        display: inline-block;
        margin-top: 20px;
        color: #ff4b2b;
        text-decoration: none;
    }
</style>
</head>

<body>

<header>RHEL 8 Hardening Guide</header>

<div class="container">

<div class="card">
<h3>🔒 Disable Root Login</h3>
<p><b>Control:</b> Prevent direct root access</p>
<p><b>Solution:</b></p>
<code>vi /etc/ssh/sshd_config</code>
<code>PermitRootLogin no</code>
</div>

<div class="card">
<h3>🔥 Firewall Configuration</h3>
<p><b>Control:</b> Restrict network traffic</p>
<code>systemctl enable firewalld</code>
<code>systemctl start firewalld</code>
</div>

<div class="card">
<h3>🛡 SELinux</h3>
<p><b>Control:</b> Enforce policies</p>
<code>setenforce 1</code>
</div>

<div class="card">
<h3>🔑 Password Policy</h3>
<p><b>Control:</b> Strong passwords</p>
<code>minlen = 12</code>
</div>

<a href="index.html" class="back">⬅ Back</a>

</div>

<footer style="text-align:center; padding:20px;">Repo Author: Kiran Negi</footer>

</body>
</html>
