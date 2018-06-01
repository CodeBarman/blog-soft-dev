+++
comments = false
date = "2015-04-14T22:17:00+00:00"
draft = false
noauthor = true
share = false
title = "Связаться со мной"
type = "page"
url = "/ru/contact"
+++

<form class="contact-form" name="contact" netlify>
  <p>
    <label>Ваше имя <input type="text" name="name" required autocomplete="off"/></label>
  </p>
  <p>
    <label>Почта <input type="email" name="email" required autocomplete="off"/></label>
  </p>
  <p>
    <textarea placeholder="Сообщение" rows="4" cols="25" name="message" required></textarea>
  </p>
  <p>
    <button type="submit">Отравить</button>
  </p>
</form>