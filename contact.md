---
layout: page
title: Contact
---

Interested in setting up an appointment?  Send me an email with preferred date and time.  Include your phone number and I will get back to you shortly.    
<!-- 
     After implementing this contact form make sure
     1. you have defined "email: youremail@email.com" in _config.yml file.
     2. you verify your form on formspree.io.
-->

<form class="wj-contact" action="https://formspree.io/mary@handandheartmassage.com" method="POST">
    <input type="text" name="email" placeholder="Email Address">
     <input type="text" name="name" placeholder="Name">
    <input type="text" name="number" placeholder="Phone Number">
    <textarea type="text" name="content" rows="10" placeholder="Message"></textarea>
    <input type="hidden" name="_next" value="<handandheartmassage.com/thanks> ">
    <input type="hidden" name="_subject" value="New Contact Form Submission">
    <input type="text" name="_gotcha" style="display:none">
    <input type="submit" value="Submit">
</form>

<style>
form.wj-contact input[type="text"], form.wj-contact textarea[type="text"] {
    width: 100%;
    vertical-align: middle;
    margin-top: 0.25em;
    margin-bottom: 0.5em;
    padding: 0.75em;
    font-family: monospace, sans-serif;
    font-weight: lighter;
    border-style: solid;
    border-color: #444;
    outline-color: #2e83e6;
    border-width: 1px;
    border-radius: 3px;
    transition: box-shadow .2s ease;
}
form.wj-contact input[type="submit"] {
    outline: none;
    color: white;
    background-color: #2e83e6;
    border-radius: 3px;
    padding: 0.5em;
    margin: 0.25em 0 0 0;
    border: 1px solid transparent;
    height: auto;
}
</style>
