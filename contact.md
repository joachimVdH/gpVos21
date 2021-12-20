---
layout: default
title: Contact
permalink: /contact
intro_paragraph: |-

  The contact form on this page uses
  [Netlify Forms](https://www.netlify.com/docs/form-handling/) to process
  submissions, and saves them in your Netlify account where you can optionally
  set up notifications. Each submission is passed through a spam filter and if
  flagged, will display a CAPTCHA challenge to the user.
---


 <div style="display: flex; flex-wrap: wrap; justify-content: space-around;">
  <div style="width: 40%;  margin-left: 5%; margin-bottom: 2%; text-align:right;">
    <b>Stuur ons een bericht</b>
    <form name="contact" method="POST" netlify data-netlify-recaptcha="true">
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
  </div>
  <div style="width: 50%; margin-left: 5%; margin-bottom: 2%;">
    <b>of bel ons</b><br>
    Logopedie : <a href="tel:+32498701211" itemprop="telephone">0498/ 70.12.11</a><br>  
    Kinesitherapie / Psychomotoriek :  <a href="tel:+32472031696" itemprop="telephone">0472/ 03.16.96</a><br>    
    Diëtiek : <a href="tel:+32494668096" itemprop="telephone">0494/ 66.80.96</a> <br>  
    <br> 
    <iframe src="https://www.google.com/maps/embed?pb=!1m18!1m12!1m3!1d22299.19920226454!2d4.513752365299256!3d51.06496164832233!2m3!1f0!2f0!3f0!3m2!1i1024!2i768!4f13.1!3m3!1m2!1s0x0%3A0xb697ddab5a8c653c!2sGroepspraktijk%20Vos!5e0!3m2!1snl!2snl!4v1640035784921!5m2!1snl!2snl" width="400" height="300" style="border:0;" allowfullscreen="" loading="lazy"></iframe>
  </div>
</div> 