<template>
  <div class="photo-container">
    <p>
      下記アドレスにて、写真販売をしています。<br />
      写真の閲覧は<span>下記アドレスをクリック</span>してください<br />
      <span>↓</span>
    </p>
    <a href="https://phst.jp/himejiymca/">https://phst.jp/himejiymca/</a>
  </div>
</template>

<style scoped>
.photo-container {
  height: calc(100% - 300px);
  padding-top: 20%;
  padding-bottom: 40%;
  text-align: center;
  color: #666666;
}

.photo-container span {
  color: red;
}

.photo-container a {
  margin-top: 16px;
  color: #0099cc;
  text-decoration: underline;
}

@media screen and (max-width: 480px) {
  .photo-container {
    padding-top: 30%;
    padding-bottom: 60%;
  }
}
</style>
