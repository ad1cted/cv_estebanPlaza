<template>
  <section id="btn-pdf">

    <link href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/4.7.0/css/font-awesome.min.css" rel="stylesheet">
    <button
        class="btn"
        onclick="location.href='https://v2.convertapi.com/d/ks9bga6bengo1gw7d9ttixjynpr6wgkg/ad1cted-github-io-cv_estebanPlaza-.pdf'"><i class="fa fa-download"></i> Generar Pdf
    </button>

  </section>
</template>
<script>
export default {
  name: "ButtonPdf",
  components: {},
  data() {
    return {
      click: false
    }
  },
}


</script>

<style>
#btn-pdf {
  text-align: right;
}

/* Style buttons */
.btn {
  background-color: DodgerBlue;
  border: none;
  color: white;
  padding: 12px 30px;
  cursor: pointer;
  font-size: 20px;
}

.btn:hover {
  background-color: RoyalBlue;
}
</style>
