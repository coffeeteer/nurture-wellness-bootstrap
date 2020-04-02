<template>
  <div class="home-div">
    <div>
      <img src="/../imgs/fontana-yoga.jpg" id="home-yoga-img" alt />
      <!-- <div class="home-box rounded">
        <h4 class="home-text text-muted text-left">A Collaborative Effort by Talented Local Healing Practitioners to Create A Nurturing Space.</h4>
      </div>-->
      <!-- <div class="home-box-stretch ">
        <div class="row">
          <div class="col-sm-8 bg-white ">
            <p class="ml-5 text-muted text-left home-text">A Collaborative Effort by Talented Local Healing Practitioners to Create A Nurturing Space.</p>
          </div>
          <div class="col-sm-4 bg-success">
            <p>Sed ut perspiciatis...</p>
          </div>
        </div>
      </div>-->
      <div class="container-fluid">
        <div class="row">
          <div class="col-12 mt-3">
            <div class="card">
              <div class="card-horizontal">
                
                <div class="card-body my-auto">
                  <h4 class="card-title ">A Collaborative Effort by Talented Local Healing Practitioners to Create A Nurturing Space.</h4>
                  <!-- <p
                    class="card-text"
                  >A Collaborative Effort by Talented Local Healing Practitioners to Create A Nurturing Space.</p> -->
                </div>
                <div class="img-square-wrapper bg-success">
                  <!-- <img class src="http://via.placeholder.com/300x180" alt="Card image cap" /> -->
                  <div class="col-sm-6">
                    <i class="fas fa-users"></i>
                  </div>
                  <div class="col-sm-6">
                    <h4>Meet OUr Healing Practiioners</h4>
                  </div>
                </div>
              </div>
              <div class="card-footer">
                <small class="text-muted">Last updated 3 mins ago</small>
              </div>
            </div>
          </div>
        </div>
      </div>
    </div>
  </div>
</template>

<script>
export default {};
</script>

<style scoped>
/* #home-jumbotron {
  background-image: url("/../imgs/fontana-yoga.jpg") no-repeat center center fixed;
  -webkit-background-size: cover;
  -moz-background-size: cover;
  -o-background-size: cover;
  background-size: cover;
} */
.home-div {
  z-index: -1;
  position: relative;
}

#home-yoga-img {
  margin-top: -200px;
}

.home-box {
  height: 150px;
  width: 500px;
  background-color: #fff;
  padding: 25px 15px;
  position: absolute;
  margin-top: -100px;
  margin-left: 100px;
  border: solid black thin;
}

.home-text {
  color: #999;
  font-size: 23px;
}

.home-box-stretch {
  padding: 0 20px;
  position: relative;
  bottom: 50px;
  right: 1px;
}

.card-horizontal {
    display: flex;
    flex: 1 1 auto;
}

.card-body{
  padding-top: 55px;
}
</style>