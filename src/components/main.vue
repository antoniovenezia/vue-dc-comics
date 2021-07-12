<template>
  <div class="">
    <ul>
      <li>
        <img src="../assets/buy-comics-digital-comics.png" alt="">
        <span>DIGITAL COMICS</span>
      </li>
      <li>
        <img src="../assets/buy-comics-merchandise.png" alt="">
        <span>DC MERCHANDASE</span>
      </li>
      <li>
        <img src="../assets/buy-comics-shop-locator.png" alt="">
        <span>SUBSCRIPTION</span>
      </li>
      <li>
        <img src="../assets/buy-comics-subscriptions.png" alt="">
        <span>COMIC SHOP LOCATOR</span>
      </li>
      <li>
        <img src="../assets/buy-dc-power-visa.svg" alt="">
        <span>DC POWER VISA</span>
      </li>
    </ul>
  </div>
</template>

<script>
export default {
  name: "Main",
};
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped lang="scss">

.main-container{
  // width: 1200px;
  // margin: 0 auto;
  background-color: #0282f9;
  ul{
    width: 1200px;
    margin: 0 auto;
    display: flex;
    padding: 50px 0;
    justify-content: space-between;
      li{
        list-style: none;

        img{
          height: 50px;
        }
      }
    }
}

</style>
