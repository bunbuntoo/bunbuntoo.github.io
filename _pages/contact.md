---
layout: page
permalink: /contact/
title: Get in Touch
description: Let your kindness hop into our inbox.
---
Drop us an email at [bunbuntoo.project@gmail.com](mailto:bunbuntoo.project@gmail.com) or use the form below. Alternatively, you can find us on Instagram, BlueSky, and X (Twitter) @bunbuntoo, though email is the quickest way to reach us :)

<h1>Contact Us</h1>

<p>If you have any questions about rabbit care, collaboration, or just want to say hi, feel free to send us a message using the form below:</p>

<form action="https://formspree.io/f/xeogavev" method="POST">
  <p>
    <label for="name">Your Name:</label><br>
    <input type="text" id="name" name="name" required>
  </p>

  <p>
    <label for="email">Your Email:</label><br>
    <input type="email" id="email" name="email" required>
  </p>

  <p>
    <label for="message">Message:</label><br>
    <textarea id="message" name="message" rows="5" required></textarea>
  </p>

  <!-- Redirect after submission -->
  <input type="hidden" name="_redirect" value="{{ '/thanks.html' | relative_url }}">

  <!-- Spam protection -->
  <input type="text" name="_gotcha" style="display:none">

  <button type="submit">Send Message</button>
</form>
