<template>
  <div class="navbar">
    <div class="container">
      <p>Daily <quotes> Quotes</quotes></p>
      <div class="action">
        <p>ABOUT</p>
        <img src="~assets/SVG/bookmark.svg" class="bookmark" />
      </div>
    </div>
  </div>
</template>

<style scoped>
.navbar {
    width: 100%;
    height: 60px;
    display: flex;
    flex-direction: row;
    align-items: center;
    /* z-index: 1; */
}

.action {
    display: flex;
    flex-direction: row;
}

.container {
    width: 90%;
    display: flex;
    flex-direction: row;
    align-items: center;
    justify-content: space-between;
    margin: auto;
}

p {
    margin: 0;
}

.bookmark {
    width: 16px;
    margin-left: 20px;
}

quotes {
  font-weight: bold;
  color: #B89A0F;
}
</style>
