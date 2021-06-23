<template>
  <header class="vcard">
    <h1 class="fn">{{ name }}</h1>
    <h2 class="role">Full-Stack Developer &amp; Data Engineer</h2>
    <ul class="contact">
      <li class="email">✉️
        <a :href="'mailto:'+ email">
          {{ email }}</a>
      </li>
      <li class="tel">
        <a href="https://api.whatsapp.com/send?phone=56968561358&text=Hola%20Esteban%20vi%20tu%20CV%20desde%20tu%20Web">📱+56968561358</a>
      </li>
      <li class="adr"><span class="locality">Santiago</span>, <span class="country-name">Chile </span>🇨🇱</li>
      <li class="url" title="Github">
        <img class="icon" src="https://cdn.icon-icons.com/icons2/936/PNG/32/github-logo_icon-icons.com_73546.png">
        <a href="https://github.com/ad1cted"> GitHub</a>
      </li>
      <li class="url">
        <img class="icon" src="https://app.codesignal.com/img/favicon-16x16.png">
        <a href="https://app.codesignal.com/profile/esteban_i"> CodeSignal</a>
      </li>
      <li class="url">
        <img class="icon" src="https://static.platzi.com/media/favicons/platzi_favicon.png">
        <a href="https://platzi.com/p/TracertRouter/"> Platzi</a>
      </li>
      <li class="url">
        <img class="icon" src="https://cdn.worldvectorlogo.com/logos/hackerrank.svg">
        <a href="https://www.hackerrank.com/ad1cted"> HackerRank</a>
      </li>
      <li class="url">
        <Countdown/>
      </li>

    </ul>

  </header>
</template>

<script>

import Countdown from "./Countdown";

export default {
  name: "HeaderBar",
  props: {
    name: String,
    email: String
  },
  components: {
    Countdown
  },
}
</script>

