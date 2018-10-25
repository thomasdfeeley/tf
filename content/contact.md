---
title: "Reach out, say hi"
metatitle: "Reach out and say hi"
description: "Get in contact with me"
date: 2018-08-21T09:31:19-04:00
layout: contact
draft: true
---

<form name="contact" class="contact black-80" netlify-honeypot="bot-field" action="/success/" method="POST" netlify>
  <p class="u-visually-hidden">
    <label class="f6 b db mb2">Don’t fill this out if you're human: <input name="bot-field"></label>
  </p>
  <label class="f6 b db mb2">What is your name?
    <input name="full-name" type="text" placeholder="Your full name" required class="input-reset ba b--black-20 pa2 mb2 db w-100">
  </label>
  <label class="f6 b db mb2">What is your email address?
    <input name="email-address" type="email" placeholder="Your email" required class="input-reset ba b--black-20 pa2 mb2 db w-100">
  </label>
  <label class="f6 b db mb2">What your message?
    <textarea name="message" type="text" placeholder="Your message..." required class="db border-box hover-black w-100 measure ba b--black-20 pa2 mh4 br2 mb2"></textarea>
  </label>
  <button type="submit" value="Submit" class="button form-button" id="Form-submit"/>Submit</button>  
</form>
