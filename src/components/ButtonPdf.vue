<template>
  <section id="btn-pdf">

    <link href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/4.7.0/css/font-awesome.min.css" rel="stylesheet">
    <button
        class="btn"
        onclick="location.href='https://downloads3.sejda.com/api/tasks/0LA5UB05-202201101842/download/ad1cted_github_io_cv_estebanPlaza.pdf?s=web-PmhLnfZA8lWr3EMuJhWMyNyEfOVChcT3TJ4xe&v=true&_s=2'"><i class="fa fa-download"></i> Generar Pdf
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
