<template>
  <section id="top-head" class="py-3 bg-primary text-white fixed-top">
    <div class="container">
      <div class="row">
        <div class="col-md-4 pt-4">
          <h3>SkillForte</h3>
        </div>
        <div class="col-md-4 pt-2 nav-container">
<!--          <h6><i class="bi bi-envelope"></i> About</h6>-->
<!--          <h6><i class="bi bi-envelope"></i> About</h6>-->
<!--          <h6><i class="bi bi-envelope"></i> FAQs</h6>-->
<!--          <h6><i class="bi bi-envelope"></i> Contact</h6>-->
          <nav class="navbar navbar-light flex-row ">
            <div class="container-fluid ">
              <ul class="navbar-nav flex-row">
                <li class="nav-item mx-3">
                  <a class="nav-link active text-white" aria-current="page" href="#">Programs</a>
                </li>
                <li class="nav-item">
                  <a class="nav-link mx-3 text-white" href="#">About</a>
                </li>
                <li class="nav-item">
                  <a class="nav-link mx-3 text-white" href="#">Faqs</a>
                </li>
                <li class="nav-item">
                  <a class="nav-link mx-3 text-white" href="#">Contact</a>
                </li>
              </ul>
            </div>
          </nav>
        </div>
        <div class="col-md-4 text-end pt-4 d-none d-md-block">
          <a class="btn btn-primary text-white" style="background-color: #3b5998;" href=""> <i class="fab fa-twitter"></i></a>
          <a class="btn btn-primary text-white" style="background-color: #A9379A;" href=""> <i class="fab fa-facebook-square"></i></a>
        </div>
      </div>
    </div>
  </section>

</template>

<script>
export default {
  name: "Header"
}
</script>

<style scoped>
.nav-container{
  display: flex;
  justify-content: space-around;
}
li a:hover{
  font-weight: bolder;
}
</style>