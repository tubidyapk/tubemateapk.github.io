---
layout: page
title: Hakkımızda
permalink: /about/
---

<p>Sitemizdeki içerikler sadece faydalı olmak için paylaşılmaktadır ve tamemen ücretsizdir. TubeMate uygulaması taramadan geçirilmiştir. Fakat kullanıcılarımızın tekrar tarama yapmasını tavsiye ediyoruz. İletişim için aşağıdaki formu kullanabilirsiniz.</p>

### İletişim

  <form action="/">

    <label for="fname">İsim</label>
    <input type="text" id="fname" placeholder="İsminiz..">

    <label for="subject">Mesaj</label>
    <textarea id="subject" placeholder="Mesajınız.." style="height:200px"></textarea>

    <input type="submit" value="Gönder">

  </form>

<style>
input[type=text], select, textarea {
    width: 100%;
    padding: 12px;
    border: 1px solid #ccc;
    border-radius: 4px;
    box-sizing: border-box;
    margin-top: 6px;
    margin-bottom: 16px;
    resize: vertical;
}

input[type=submit] {
    background-color: #4CAF50;
    color: white;
    padding: 12px 20px;
    border: none;
    border-radius: 4px;
    cursor: pointer;
}

input[type=submit]:hover {
    background-color: #45a049;
}
</style>
