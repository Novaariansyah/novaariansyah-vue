<template>
 <body>

<div class="container mt-3">
  <h2>BIODATA DIRI</h2>
  <p>Ini Adalah Biodata Singkat Saya:</p>
  <img src="Nova.jpeg" class="rounded" width="100" height="80"><br><br>
  <div class="alert alert-success">
    <strong>Nama :</strong> NOVA ARIANSYAH
  </div>
  <div class="alert alert-info">
    <strong>Umur :</strong> 19Tahun
  </div>
  <div class="alert alert-warning">
    <strong>Tempat Tanggal Lahir :</strong> Palembang, 11 November 2002
  </div>
  <div class="alert alert-danger">
    <strong>Agama :</strong> Buddha
  </div>
  <div class="alert alert-primary">
    <strong>Hobi :</strong> Bermain Game
  </div>
  <div class="alert alert-light">
    <strong>Cerita Singkat :</strong> Hallo Nama Saya Nova Ariansyah, Sekarang Saya Kuliah Di Universitas MDP
    Semester 3, Hobi Saya Bermain Game Online Dan Saya Senang Menonton Anime. 
    Sekian Perkenalan Singkat Dari Saya. Terimah Kasih.
  </div>
  <div class="alert alert-light">
    Berikut Adalah Foto Salah Satu Character Game Yang Saya Mainkan
  </div>
  <img src="Hu Tao.png" class="rounded" width="150" height="100">
</div>

</body>
</template>

<script>
export default {
  name: 'HelloWorld',
  props: {
    msg: String
  }
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
h3 {
  margin: 40px 0 0;
}
ul {
  list-style-type: none;
  padding: 0;
}
li {
  display: inline-block;
  margin: 0 10px;
}
a {
  color: #42b983;
}
</style>
