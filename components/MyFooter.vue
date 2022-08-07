<template>
  <div class="footer">
    <div class="social-icons">
      <div><img src="~/assets/icons/fb.png" alt="Facebook" /></div>
      <div>
        <img src="~/assets/icons/insta.png" alt="Instagram" />
      </div>
      <div>
        <img src="~/assets/icons/Group.png" alt="Twitter" />
      </div>
      <div>
        <img src="~/assets/icons/Linkedin.png" alt="Linkedin" />
      </div>
    </div>

    <div class="footer-text">
      <p class="text-center">Copyright ©2020 All rights reserved</p>
    </div>
  </div>
</template>

<script>
export default { name: 'MyFooter' }
</script>

<style lang="scss" scoped>
.footer {
  height: 182px;
  display: flex;
  flex-direction: column;
  justify-content: center;
  .social-icons {
    display: flex;
    justify-content: center;
    img {
      margin-right: 20px;
    }
  }
  &-text {
    margin-top: 26.5px;
    font-weight: 400;
    font-size: 14px;
    line-height: 21px;
    text-align: center;
  }
}
</style>
