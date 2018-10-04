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
<form action="mailto:secondsouffle@pm.me?subject=ContactSiteWeb" name="envoi" method=POST enctype="text/plain">

<table border="0">
  <tr>
    <td>
    <b>Nom : </b><input name="nom"size=50 maxlength=50><br />
    <b>Prénom : </b><input name="PRENOM"size=50 maxlength=50><br />
    <textarea name="message" cols="60" rows="5"></textarea>
    </td>
  </tr>
</table><br />

Est-ce votre 1ère visite sur <i>Second&nbsp;Souffle</i>&nbsp;?
<input type="radio" name="Visite" value="PremiereFois">Oui - &nbsp;
<input type="radio" name="Visite" value="Parfois">Non, je viens parfois - &nbsp;
<input type="radio" name="Visite" value="Souvent">Non, je viens souvent
<br /><br />

<input type="submit" value="Envoyer" name="Envoyer">
<input type="reset" name="Submit" value="Effacer">
</form>
