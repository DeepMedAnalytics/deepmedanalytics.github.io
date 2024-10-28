---
layout: page
permalink: /contact/
title: Contact
description:
nav: true
nav_order: 7
---


<form action="https://formspree.io/f/xnnqjbge" method="POST">
    <label for="name">Name:</label><br>
    <input type="text" id="name" name="name" required><br><br>
    
    <label for="email">Email:  </label><br>
    <input type="email" id="email" name="_replyto" required><br><br>
    
    <label for="inquiry_type">Choose type of inquiry:</label><br>
    <select id="inquiry_type" name="inquiry_type" required>
        <option value="General Inquiry">General Inquiry</option>
        <option value="Clinical AI">Clinical AI</option>
        <option value="Clinical Trials">Clinical Trials</option>
        <option value="Biostatistics">Biostatistics</option>
        <option value="Bioinformatics">Bioinformatics</option>
        <option value="Genomics">Genomics</option>
    </select><br><br>

    <label for="message">Message:</label><br>
    <textarea id="message" name="message" rows="5" columns="100" required></textarea><br><br>
    
    <input type="submit" value="Send">
</form>

