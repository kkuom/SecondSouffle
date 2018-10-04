---
title: ""
date: 2018-09-17T15:38:20+02:00
draft: false
metaAlignment: center

categories: []
tags: []
keywords: ["email", "contact"]

showTags: false
showPagination: false
showSocial: false
showDate: false
showMeta: true
comments: false
---
<form method="post" action="/php/mail.php">
  <label for="name">Nom :</label>
  <input type="text" name="name" id="name" required placeholder="Nom" /><br />

  <label for="subject">Objet du message :</label>
  <input type="text" name="subject" id="subject" required placeholder="Sujet" /><br />

  <label for="email">Email :</label>
  <input type="email" name="email" id="email" required placeholder="email@exemple.com" /><br />

  <label for="message">Message :</label>
  <textarea name="message" id="message" required></textarea><br />

  <input type="submit" value="Envoyer Mon Message" />
</form>
