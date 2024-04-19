---
layout: default
title: Registration
---

<link rel="stylesheet" href="{{ '/assets/css/styles.css' | relative_url }}">

<div class="container">
  <div class="form-container">
    <h1>Conference Registration</h1>

    <form action="https://formspree.io/f/xoqgyeza" method="POST">
      <label for="name">Name:</label>
      <input type="text" id="name" name="name" required><br>

      <label for="email">Email:</label>
      <input type="email" id="email" name="email" required><br>

      <label for="affilitation">Affiliation:</label>
      <textarea id="affilitation" name="affilitation"></textarea><br>

      <label for="notes">Message:</label>
      <textarea id="notes" name="message"></textarea><br>

      <input type="submit" value="Submit">
    </form>
  </div>
</div>
