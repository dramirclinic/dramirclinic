<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1">
<title>Dr Amir Clinic</title>

<style>
  body {
    font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
    background: #f0f8ff;
    margin: 0;
    padding: 0;
    line-height: 1.6;
  }

  header {
    background: linear-gradient(90deg, #007acc, #00bcd4);
    color: white;
    padding: 30px 20px;
    text-align: center;
  }

  header h1 {
    margin-bottom: 5px;
  }

  section {
    padding: 20px;
    max-width: 1000px;
    margin: auto;
  }

  h2 {
    color: #007acc;
    border-bottom: 2px solid #007acc;
    padding-bottom: 5px;
  }

  ul {
    list-style-type: disc;
    padding-left: 20px;
  }

  img {
    max-width: 100%;
    height: auto;
    border-radius: 12px;
    margin: 15px 0;
  }

  iframe {
    width: 100%;
    height: 300px;
    border: 0;
    border-radius: 10px;
  }

  form {
    background-color: #e6f2ff;
    padding: 20px;
    border-radius: 8px;
    margin-top: 15px;
  }

  input, textarea {
    width: 100%;
    padding: 12px;
    margin-top: 8px;
    margin-bottom: 15px;
    border: 1px solid #ccc;
    border-radius: 6px;
  }

  button {
    background-color: #007acc;
    color: white;
    padding: 12px 18px;
    border: none;
    border-radius: 6px;
    cursor: pointer;
    width: 100%;
    font-size: 16px;
  }

  button:hover {
    background-color: #005f99;
  }

  footer {
    background: #007acc;
    color: white;
    text-align: center;
    padding: 15px 10px;
    margin-top: 40px;
  }

  .whatsapp-button {
    position: fixed;
    bottom: 80px;
    right: 20px;
    background-color: #25d366;
    color: white;
    border-radius: 50px;
    padding: 14px 24px;
    text-decoration: none;
    font-weight: bold;
    box-shadow: 0 2px 5px rgba(0,0,0,0.2);
  }

  @media (max-width: 600px) {
    header h1 {
      font-size: 24px;
    }
    .whatsapp-button {
      padding: 10px 18px;
      font-size: 14px;
    }
  }
</style>
</head>

<body>

<header>
  <h1>Dr Amir Clinic</h1>
  <p>Your Health, Our Priority</p>
</header>

<section>
  <h2>About Us</h2>
  <p>We provide quality healthcare services for you and your family. Our experienced doctors and staff ensure the best medical care for all age groups.</p>

  <img src="https://via.placeholder.com/800x300?text=Dr+Amir+Clinic" alt="Clinic Image">

  <h2>Our Services</h2>
  <ul>
    <li>General Checkup</li>
    <li>Dental Care</li>
    <li>Pediatrics</li>
    <li>Cardiology</li>
  </ul>

  <h2>Contact Us</h2>
  <p><strong>Address:</strong> 123 Health Street, Your City</p>
  <p><strong>Phone:</strong> +92 123 4567890</p>
  <p><strong>Email:</strong> info@dramircinic.com</p>

  <h2>Our Location</h2>
  <iframe src="https://www.google.com/maps/embed?pb=!1m18!1m12!1m3!1d13604.609905368605!2d74.3232064!3d31.5203696!2m3!1f0!2f0!3f0!3m2!1i1024!2i768!4f13.1!3m3!1m2!1s0x391904d4c41b2e21%3A0x29fdb0a63d175d2c!2sLahore!5e0!3m2!1sen!2s!4v1715160000000" allowfullscreen></iframe>

  <h2>Book an Appointment</h2>

  <form action="https://formsubmit.co/YOUR_EMAIL_HERE" method="POST">
    <input type="hidden" name="_captcha" value="false">
    <label for="name">Name:</label>
    <input type="text" id="name" name="name" placeholder="Your Name" required>

    <label for="email">Email:</label>
    <input type="email" id="email" name="email" placeholder="Your Email" required>

    <label for="message">Message:</label>
    <textarea id="message" name="message" placeholder="Your message..." rows="4" required></textarea>

    <button type="submit">Submit</button>
  </form>

</section>

<a class="whatsapp-button" href="https://wa.me/923001234567" target="_blank">Chat on WhatsApp</a>

<footer>
  &copy; 2025 Dr Amir Clinic | All rights reserved
</footer>

</body>
</html>
