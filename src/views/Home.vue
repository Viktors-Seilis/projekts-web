<template>
  <div class="home">
    <div class="container-fluid">
      <br>
      <h1 class="virsraksts">Pieslēgšanās logs</h1>
      <div class="row align-items-center">
        <div class="col-md-3"></div>
        <div class="col-md-6">
          <div class="login">
            <div class="container">
              <form>
            <div class="mb-3">
              <label for="exampleInputEmail1" class="form-label">Lietotājvārds</label>
              <input type="email" class="form-control" id="exampleInputEmail1" aria-describedby="emailHelp">
            </div>
            <div class="mb-3">
              <label for="exampleInputPassword1" class="form-label">Parole</label>
              <input type="password" class="form-control" id="exampleInputPassword1">
            </div>
            <button type="submit" class="btn btn-primary">Pieslēgties</button>
          </form>
            </div>
          </div>
          </div>
        </div>
        <div class="col-md-3"></div>
      </div>
      <footer class="text-center text-white fixed-bottom" style="background-color: #222;">
        <!-- Grid container -->
        <div class="container pt-4">
          <!-- Section: Social media -->
          <section class="mb-4">
            <!-- Facebook -->
            <!--
            <a
                class="btn btn-link btn-floating btn-lg text-dark m-1"
                href="#!"
                role="button"
                data-mdb-ripple-color="dark"
            ><i class="fab fa-facebook-f"></i
            ></a>

            <-- Twitter -->
            <!--
            <a
                class="btn btn-link btn-floating btn-lg text-dark m-1"
                href="#!"
                role="button"
                data-mdb-ripple-color="dark"
            ><i class="fab fa-twitter"></i
            ></a>

            <-- Google -->
            <!--
            <a
                class="btn btn-link btn-floating btn-lg text-dark m-1"
                href="#!"
                role="button"
                data-mdb-ripple-color="dark"
            ><i class="fab fa-google"></i
            ></a>

            <-- Instagram -->
            <!--
            <a
                class="btn btn-link btn-floating btn-lg text-dark m-1"
                href="#!"
                role="button"
                data-mdb-ripple-color="dark"
            ><i class="fab fa-instagram"></i
            ></a>

            <-- Linkedin -->
            <!--
            <a
                class="btn btn-link btn-floating btn-lg text-dark m-1"
                href="#!"
                role="button"
                data-mdb-ripple-color="dark"
            ><i class="fab fa-linkedin"></i
            ></a>
            <-- Github -->
            <!--
            <a
                class="btn btn-link btn-floating btn-lg text-dark m-1"
                href="#!"
                role="button"
                data-mdb-ripple-color="dark"
            ><i class="fab fa-github"></i
            ></a> -->

          </section>
          <!-- Section: Social media -->
        </div>
        <!-- Grid container -->

        <!-- Copyright -->
        <div class="text-center text-white p-3" style="background-color: #222;">
          © 2021 Copyright:
          <a class="text-white" href="https://rvt.lv/">Rīgas valsts tehnikums</a>
        </div>
        <!-- Copyright -->
      </footer>
    </div>
</template>

<script>
// @ is an alias to /src

export default {
  name: 'Home',
  components: { },
}
</script>
<style scoped>

  .btn-primary{
    color: white;
    background: green;
  }

  .login{
    background: white;
    padding-top: 20px;
    padding-bottom: 20px;
  }

  .virsraksts{
    color: white;
  }
  .row{
    background-color: green;
  }
</style>