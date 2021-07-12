<template>
  <div>
    <div class="list-item">
      <ul>
        <li>DC COMICS</li>
        <li>Characters</li>
        <li>Comics</li>
        <li>Movies</li>
        <li>TV</li>
        <li>Games</li>
        <li>Videos</li>
        <li>News</li>
      </ul>

      <ul>
        <li>SHOP</li>
        <li>Shop DC</li>
        <li>Shop DC Collectibles</li>
      </ul>
    </div>

    <div class="list-item">
      <ul>
        <li>DC</li>
        <li>Terms Of Use</li>
        <li>Privacy policy (New)</li>
        <li>Ad Choices</li>
        <li>Advertising</li>
        <li>Jobs</li>
        <li>Subscriptions</li>
        <li>Talent Workshops</li>
        <li>CPSC Certificates</li>
        <li>Ratings</li>
        <li>Shop Help</li>
        <li>Contact Us</li>
      </ul>
    </div>

    <div class="list-item">
      <ul>
        <li>SITES</li>
        <li>DC</li>
        <li>MAD Magazine</li>
        <li>DC Kids</li>
        <li>DC Universe</li>
        <li>DC Power Visa</li>
      </ul>
    </div>
  </div>
</template>

<script>
export default {
  name: "Footer",
};
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped lang="scss">
.footer-container {
  width: 1200px;
  margin: 0 auto;
  display: flex;
  color: gray;
  font-size: 14px;
  background-image: url(../assets/footer-bg.jpg);
    ul {
      text-align: left;
      li {
        // text-align: left;
        padding: 3px 0;
        list-style: none;
          &:first-child {
          font-weight: bold;
          font-size: 20px;
          color: white;
          margin-bottom: 20px;
        }
      }
    }
}
</style>