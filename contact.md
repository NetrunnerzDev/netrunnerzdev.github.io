---
title: Contact
layout: contact
description: Get in touch with Netrunnerz for IT and network solutions. We’ll help you plan the right solution for your business.
---

Not sure what you need yet? Contact us and we’ll help you plan the right IT or network solution for your business.

![About Us](/images/contact.jpg)

<!-- <form action="https://formspree.io/f/your-form-id" method="POST">
  <label for="name">Name</label><br>
  <input type="text" id="name" name="name" required><br><br>

  <label for="email">Email</label><br>
  <input type="email" id="email" name="email" required><br><br>

  <label for="company">Company</label><br>
  <input type="text" id="company" name="company"><br><br>

  <label for="message">Message</label><br>
  <textarea id="message" name="message" rows="6" required></textarea><br><br>

  <button type="submit">Send Message</button>
</form> -->


<form
  action="https://formspree.io/f/{FORM_ID}"
  class="fs-form"
  target="_top"
  method="POST"
>
  <div class="fs-field">
    <label class="fs-label" for="name">Your Name</label>
    <input class="fs-input" id="name" name="name" required />
  </div>
  <div class="fs-field">
    <label class="fs-label" for="email">Email</label>
    <input class="fs-input" id="email" name="email" required />
    <p class="fs-description">
      This will help us respond to your query via an email.
    </p>
  </div>
  <div class="fs-field">
    <label class="fs-label" for="message">Message</label>
    <textarea
      class="fs-textarea"
      id="message"
      name="message"
      required
    ></textarea>
    <p class="fs-description">What would you like to discuss?</p>
  </div>
  <div class="fs-button-group">
    <button class="fs-button" type="submit">Send Message</button>
  </div>
</form>