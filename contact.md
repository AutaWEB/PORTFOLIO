---
layout: default
title: Contact
permalink: /contact/
---

# Me Contacter

<div style="margin-bottom: 40px;">
  <p><strong>Email :</strong> <a href="mailto:yanis.rouag@epitech.eu">yanis.rouag@epitech.eu</a></p>
  <p><strong>GitHub :</strong> <a href="https://github.com/AutaWEB">@AutaWEB</a></p>
</div>

<h2>M'envoyer un message</h2>

<form action="https://formspree.io/f/ton_form_id" method="POST" style="display: flex; flex-direction: column; gap: 15px; max-width: 500px;">
  <label>
    Votre email :
    <input type="email" name="email" required style="width: 100%; padding: 10px; margin-top: 5px;">
  </label>
  <label>
    Message :
    <textarea name="message" required style="width: 100%; height: 120px; padding: 10px; margin-top: 5px;"></textarea>
  </label>
  <button type="submit" class="btn">Envoyer</button>
</form>