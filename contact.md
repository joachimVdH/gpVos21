---
layout: page
title: Contact
permalink: /contact
section: contact
intro_paragraph: |-

  The contact form on this page uses
  [Netlify Forms](https://www.netlify.com/docs/form-handling/) to process
  submissions, and saves them in your Netlify account where you can optionally
  set up notifications. Each submission is passed through a spam filter and if
  flagged, will display a CAPTCHA challenge to the user.
---

**Stuur ons een bericht**

<form name="contact" method="POST" netlify>
  <label for="name">Naam</label><br>
  <input type="text" name="name" id="name" autocomplete="name" placeholder="Je naam" title="Gelieve je naam in te vullen" required><br>
  <label for="email">Email</label><br>
  <input type="email" name="email" id="email" autocomplete="email" placeholder="Je email adres" title="The domain portion of the email address is invalid (the portion after the @)." pattern="^([^\x00-\x20\x22\x28\x29\x2c\x2e\x3a-\x3c\x3e\x40\x5b-\x5d\x7f-\xff]+|\x22([^\x0d\x22\x5c\x80-\xff]|\x5c[\x00-\x7f])*\x22)(\x2e([^\x00-\x20\x22\x28\x29\x2c\x2e\x3a-\x3c\x3e\x40\x5b-\x5d\x7f-\xff]+|\x22([^\x0d\x22\x5c\x80-\xff]|\x5c[\x00-\x7f])*\x22))*\x40([^\x00-\x20\x22\x28\x29\x2c\x2e\x3a-\x3c\x3e\x40\x5b-\x5d\x7f-\xff]+|\x5b([^\x0d\x5b-\x5d\x80-\xff]|\x5c[\x00-\x7f])*\x5d)(\x2e([^\x00-\x20\x22\x28\x29\x2c\x2e\x3a-\x3c\x3e\x40\x5b-\x5d\x7f-\xff]+|\x5b([^\x0d\x5b-\x5d\x80-\xff]|\x5c[\x00-\x7f])*\x5d))*(\.\w{2,})+$" required><br>
  <label for="phone">Telefoon</label><br>
  <input type="text" name="phone" id="phone" autocomplete="tel-national" placeholder="Je telefoon nummer"><br>
  <label for="message">Bericht</label><br>
  <textarea name="message" id="message" placeholder="Schrijf je bericht hier" rows="7" required></textarea><br>
  <button type="submit" name="submit">Verstuur je bericht</button><br>
</form>