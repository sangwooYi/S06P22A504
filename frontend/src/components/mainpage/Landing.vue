<template>
  <div class="mylanding">
    <div class="sect sect--padding-top">
      <div class="container">
        <div class="row">
          <div class="col-md-12">
            <div class="site">
              <h1 class="site__title">우리 유아를 위한 중고거래 마켓</h1>
              <h2 class="site__subtitle">Milk 토큰으로 거래하세요</h2>
              <div class="site__box-link">
                <router-link to="/shop">
                  <a class="btn btn-blue btn--width">Shop</a>
                </router-link>
                <a class="btn btn--revert btn--width" href="">Contact</a>
              </div>
              <img class="site__img" src="https://image.ibb.co/c7grYb/image3015.png" />
            </div>
          </div>
        </div>
      </div>
    </div>
  </div>
</template>

<script>
export default {
  name: "Landing",
};
</script>

<style scope>
@import url("https://fonts.googleapis.com/css2?family=Black+Han+Sans&display=swap");
@import url("https://fonts.googleapis.com/css?family=Lato:100,100i,300,300i,400,400i,700,700i,900,900i");

.btn .btn-blue {
  color: #fff;
}

.mylanding .sect {
  padding: 90px 0;
  position: relative;
}

.mylanding .sect--padding-top {
  padding-top: 90px;
}

.mylanding .site {
  text-align: center;
}
.mylanding .site__title {
  font-size: 30px;
  margin: 0;
  text-align: center;
  color: #1f4568;
  font-family: "Black Han Sans", sans-serif;
}

.mylanding .site__subtitle {
  font-size: 22px;
  color: #8198ae;
  margin: 15px 0 40px 0;
  text-align: center;
  /* font-family: "Black Han Sans", sans-serif; */
  font-family: "Noto Sans KR", sans-serif;
}

.mylanding .site__img {
  margin-top: 50px;
  display: inline-block;
  width: 77%;
}

.mylanding .site__box-link .btn--revert {
  margin-left: 15px;
}

@media screen and (max-width: 991px) {
}

@media screen and (max-width: 767px) {
  .mylanding .site__img {
    width: 100%;
  }
}

@media screen and (max-width: 480px) {
  .mylanding .sect {
    padding: 20px 0;
  }
  .mylanding .sect--padding-top {
    padding-top: 80px;
  }
  .mylanding .site__title {
    font-size: 24px;
  }
  .mylanding .site__subtitle {
    font-size: 18px;
    margin: 10px 0 20px 0;
  }
  .mylanding .site__img {
    margin-top: 30px;
  }
  /* .mylanding .btn {
    font-size: 12px;
    padding: 8px 8px;
  }
  .mylanding .btn--width {
    width: 100px;
  } */
}
</style>
