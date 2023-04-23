---
title: 'Contact us'
date: 2018-02-22T17:01:34+07:00
layout: contact
intro_image: "images/illustrations/contact.svg"
intro_image_absolute: true
intro_image_hide_on_mobile: true
---

## Information Request

Please don't hesitate to contact us by email, we will respond within 48 hours.

<form action="https://api.staticforms.xyz/submit" method="post" class="contact">
    <input type="hidden" name="accessKey" value="46a0b83f-5115-418a-bd2f-b1f6d578602d">
    <input type="text" name="fullname" placeholder="Nom" />
    <input type="email" name="email" placeholder="Email" required />
    <textarea name="message" rows="5" placeholder="Message" required></textarea>
    <input type="hidden" name="redirectTo" value="{{< ref "contact-success.md" >}}">
    <button type="submit">Envoyer</button>
</form>
