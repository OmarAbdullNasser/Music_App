<template>
  <div class="Sidebar bg-black justify-content-center pb-5 pe-4">
    <div class="container">
      <div class="row options mb-3 pb-3">
        <div class="col-12 py-4 d-flex justify-content-center">
          <img src="../../assets/logo.png" class="mx-auto" alt="" />
        </div>

        <div class="col-12 home d-flex ms-5 align-content-center active">
          <font-awesome-icon icon="fa-solid fa-house " class="fa-xl mx-4" />
          <h5>Home</h5>
        </div>

        <div class="col-12 home d-flex ms-5 align-content-center deactive my-3">
          <font-awesome-icon
            icon="fa-solid fa-magnifying-glass"
            class="fa-xl mx-4"
          />
          <h5>Search</h5>
        </div>

        <div class="col-12 home d-flex ms-5 align-content-center deactive">
          <font-awesome-icon
            icon="fa-solid fa-book-bookmark"
            class="fa-xl mx-4"
          />
          <h5>Your Library</h5>
        </div>
      </div>

      <div class="row playlist pb-5 mb-5">
        <div class="col-12 home d-flex ms-5 align-content-center active">
          <font-awesome-icon
            icon="fa-solid fa-circle-plus"
            class="fa-xl mx-3"
          />
          <h5>Create Playlist</h5>
        </div>

        <div class="col-12 home d-flex ms-5 align-content-center deactive my-3">
          <font-awesome-icon icon="fa-solid fa-heart" class="fa-xl mx-3" />
          <h5>Liked Songs</h5>
        </div>
      </div>

      <div class="row SiteInfo ms-5 pt-5">
        <div class="div1 d-flex text-center">
          <span>Legal</span>
          <span class="flex-grow-1">Privacy Center</span>
        </div>

        <div class="div1 d-flex text-center">
          <span>Privacy Policy</span>
          <span class="flex-grow-1">Cookies</span>
        </div>

        <div class="div1 d-flex text-center">
          <span class="me-5">About Ads</span>
          <img src="../../assets/Frame.png" alt="" class="" />
        </div>

        <div class="div1 d-flex text-center">
          <span>Cookies</span>
        </div>
      </div>

      <div class="row lang mt-5 text-center d-flex justify-content-center">
        <div class="col-6 border rounded-pill p-3">
          <font-awesome-icon icon="fa-solid fa-globe" class="mx-2 fa-lg" />
          <span>English</span>
        </div>
      </div>
    </div>
  </div>
</template>

<script>
export default {};
</script>

<style lang="scss" scoped>
* {
  box-sizing: border-box;
  cursor: pointer;
}
// .Sidebar {
//   height: 100vh;
// }
.options {
  font-size: 13px;
  .active {
    color: #ffff;
  }
  .deactive {
    color: #b3b3b3;
    &:hover {
      color: #fff;
    }
  }
}
.playlist {
  color: #fff;
}
.SiteInfo {
  color: #a7a7a7;
}
.lang {
  color: #fff;
}
</style>
