---
layout: default
title: Contact
permalink: /contact
nav_order: 6
---
 
 <form action="https://getform.io/f/7a547488-c2b9-4756-a2e1-5bba8faaa1af" method="POST">
    <input type="text" name="name">
    <input type="email" name="email">
    <input type="text" name="message">
    <!-- checkbox handle --> 
    <input type="checkbox" name="subscribe" value="yes" checked>
    <input type="hidden" name="subscribe" value="no">
    <!-- radio button handle --> 
    <input type="radio" name="gender" value="male" checked>
    <input type="radio" name="gender" value="female">
    <input type="radio" name="gender" value="other">
    <!-- select field handle --> 
    <select name="work-experience">
        <option value="one-year">0-1 years</option>
        <option value="one-five-years">1-5 years</option>
        <option value="five-plus-years">5+ years</option>
    </select>
    <button type="submit">Send</button>
</form>

<form action="https://getform.io/f/7a547488-c2b9-4756-a2e1-5bba8faaa1af" method="POST" enctype="multipart/form-data">
   <input type="file" name="file">
   <button type="submit">Send</button>
</form>
