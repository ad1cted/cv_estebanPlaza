<template>
  <header class="vcard">
    <h1 class="fn">{{ name }}</h1>
    <h2 class="role">Data Engineer &amp; Full-Stack Developer </h2>
    <ul class="contact">
      <li class="email">✉️
        <a :href="'mailto:'+ email">
          {{ email }}</a>
      </li>
      <li class="tel">
        <a href="https://api.whatsapp.com/send?phone=56968561358&text=Hola%20Esteban%20vi%20tu%20CV%20desde%20tu%20Web%20https://ad1cted.github.io/cv_estebanPlaza/">📱+56968561358</a>
      </li>
      <li class="adr"><span class="locality">Santiago</span>, <span class="country-name">Chile </span>🇨🇱</li>
      <li class="url" title="Github">
        <img alt="github_logo" class="icon" src="../../static/github_logo.png">
        <a href="https://github.com/ad1cted"> GitHub</a>
      </li>
      <li class="url">
        <img alt="codesignal_logo" class="icon" src="../../static/codesignal_logo.png">
        <a href="https://app.codesignal.com/profile/esteban_i"> CodeSignal</a>
      </li>
      <li class="url">
        <img alt="platzi_logo" class="icon" src="../../static/platzi_logo.webp">
        <a href="https://platzi.com/p/TracertRouter/"> Platzi</a>
      </li>
      <li class="url">
        <img alt="hackerrank_logo" class="icon" src="../../static/hackerrank_logo.svg">
        <a href="https://www.hackerrank.com/ad1cted"> HackerRank</a>
      </li>
      <li class="url">
        <img alt="linkedin_logo" class="icon" src="../../static/linkedin_ico.svg">
        <a href="https://www.linkedin.com/in/esteban-isaias-plaza-aranda-702779115/"> Linkedin</a>
      </li>
      <li class="url">
        <img alt="topcoder_logo" class="icon" src="../../static/topcoder_logo.png">
        <a href="https://www.topcoder.com/members/ad1cted"> TopCoder</a>
      </li>
      <li class="url">
        <Countdown/>
      </li>


    </ul>
    <locale-changer></locale-changer>

  </header>
</template>

<script>


import Countdown from "@/components/Countdown";
import LocaleChanger from "./LocaleChanger";

export default {
  name: "HeaderBar",
  props: {
    name: String,
    email: String
  }, components: {
    LocaleChanger,
    Countdown

  }

}
</script>

