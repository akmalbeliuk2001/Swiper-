<template>
  <div class="header">
    <div class="max-width">
      <div class="header-content">
        <a class="logo">A</a>
        <ul class="header-sosmed">
          <li class="instagram">
            <a href="https://www.instagram.com/akmal_beliuk" target="blank"
              ><i class="fa-brands fa-instagram"></i
            ></a>
          </li>
          <li class="twitter">
            <a href="https://www.twitter.com/" target="blank"
              ><i class="fa-brands fa-twitter"></i
            ></a>
          </li>
        </ul>
      </div>
    </div>
  </div>
</template>

<script>
export default {
  name: "HeaderComponenet",
};
</script>

<style lang="scss" scoped>
.header {
  position: fixed;
  width: 100%;
  z-index: 3;
  .max-width {
    padding: 0 1rem;
  }
  .header-content {
    display: flex;
    align-items: center;
    justify-content: space-between;
    .logo {
      padding: 10px 15px;
      background-color: #fa7070;
      color: #fff;
      border-radius: 10px;
      font-weight: 700;
      font-size: 18px;
    }
    .header-sosmed {
      display: flex;
      li {
        list-style: none;
      }
      .fa-brands {
        font-size: 18px;
        color: #fff;
        padding: 10px;
        border-radius: 10px;
        background: #fa7070;
        margin-left: 10px;
      }
    }
  }
}
</style>
