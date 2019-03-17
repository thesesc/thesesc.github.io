---
layout: page
title: Contact
permalink: /contact/
---

<form action="https://formspree.io/{{ site.email }}" method="POST">
  <div>
    <label for="name">Name</label>
    <input type="text" name="name" id="name" />
  </div>
  <div>
    <label for="email">Email</label>
    <input type="text" name="_replyto" id="email" />
  </div>
  <div>
    <label for="message">Message</label>
    <textarea name="message" id="message" rows="6"></textarea>
  </div>
  <ul>
    <li><input type="submit" value="Send Message" /></li>
    <li><input type="reset" value="Clear" /></li>
  </ul>
</form>
