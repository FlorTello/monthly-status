<template>
  <div>
    <nuxt />
  </div>
</template>

<style>
@font-face {
  font-family: "Avenir";
  src: url("../assets/fonts/avenir/AvenirLTStd-Book.otf");
  font-weight: lighter;
}
@font-face {
  font-family: "Avenir";
  src: url("../assets/fonts/avenir/AvenirLTStd-Roman.otf");
  font-weight: normal;
}
@font-face {
  font-family: "Avenir";
  src: url("../assets/fonts/avenir/AvenirLTStd-black.otf");
  font-weight: bold;
}

html,
* {
  font-family: "Avenir", Arial, sans-serif;
  font-weight: normal;
  font-size: 16px;
  word-spacing: 1px;
  -ms-text-size-adjust: 100%;
  -webkit-text-size-adjust: 100%;
  -moz-osx-font-smoothing: grayscale;
  -webkit-font-smoothing: antialiased;
  box-sizing: border-box;
}

*,
*:before,
*:after {
  box-sizing: border-box;
  margin: 0;
}

.icon--answer {
  display: inline-block;
  background-image: url("../assets/imgs/answer-icon.svg");
  background-repeat: no-repeat;
  height: 1rem;
  width: 1rem;
  background-size: contain;
}
.icon--check {
  display: inline-block;
  background-image: url("../assets/imgs/check-icon.svg");
  background-repeat: no-repeat;
  height: 0.8rem;
  width: 0.8rem;
  background-size: contain;
}

.icon--arrow {
  display: inline-block;
  background-image: url("../assets/imgs/arrow-right-icon.svg");
  background-repeat: no-repeat;
  height: 0.8rem;
  width: 0.8rem;
  background-size: contain;
}

.icon--play {
  display: inline-block;
  background-image: url("../assets/imgs/play-icon.svg");
  background-repeat: no-repeat;
  height: 1.4rem;
  width: 1.4rem;
  background-size: contain;
}

.button-icon {
  min-width: 9rem;
  display: flex;
  justify-content: space-between;
  align-items: center;
}

.btn-outline-dark {
  border-color: #18618f;
}
.text-5 {
  font-size: 5px;
}
.text-6 {
  font-size: 6px;
}
.text-7 {
  font-size: 7px;
}
.text-8 {
  font-size: 8px;
}
.text-9 {
  font-size: 9px;
}
.text-10 {
  font-size: 10px;
}

.blue-color {
  color: #18618f;
}

.text-grey {
  color: #575756;
}

.light-blue-color {
  color: #5a9cbc;
}

.text-bold {
  font-weight: bold;
}
</style>
