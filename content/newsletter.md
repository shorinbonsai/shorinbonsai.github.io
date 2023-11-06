---
title: "Subscribe to Newsletter"
date: 2022-04-26T21:03:59+00:00
draft: false
---

---
Contact form: (Not connected yet)

{{< rawhtml >}}
<form action={FORM_ENDPOINT} method="POST">
  <div class="mb-3 pt-0">
    <input type="text" placeholder="Your name" name="name" required />
  </div>
  <div class="mb-3 pt-0">
    <input type="email" placeholder="Email" name="email" required />
  </div>
  <!-- <div class="mb-3 pt-0">
    <textarea placeholder="Your message" name="message" required></textarea>
  </div> -->
  <div class="mb-3 pt-0">
    <button type="submit">Send a message</button>
  </div>
</form>
{{< /rawhtml >}}