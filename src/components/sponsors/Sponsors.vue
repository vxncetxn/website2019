<template>
  <div id="thankees">
    <div class="thankees-body">
      <h3>Sponsors</h3>
      <div class="thankees-content"></div>
    </div>
    <svg
      style="transform: translateY(-6px);"
      viewBox="0 0 1440 215.44"
      xmlns="http://www.w3.org/2000/svg"
    >
      <path
        d="m-92.45-323.12h60c60 0 180 0 300 16s240 48 360 37.3c120-10.3 240-64.3 360-85.3s240-11 300-5.3l60 5.3v-128h-1440z"
        fill="#79c89f"
        fill-opacity="0.4"
        transform="translate(92.45 483.12)"
      ></path>
    </svg>
  </div>
</template>

<script>
export default {
  name: "thankees"
};
</script>

<style scoped>
#thankees {
  /* border: 1px solid purple; */
}

.thankees-body {
  background-color: var(--slope-body-color);
  width: 100%;
  height: 800px;
  padding-top: 100px;
  transform: translateY(-6px);
}

h3 {
  font-family: var(--font-secondary), sans-serif;
  font-size: calc(24px + 2vw);
  font-weight: 700;
  padding-left: 150px;
  color: var(--color-section-title-text);
  margin-bottom: 50px;
  /* border: 1px solid yellow; */
}

.thankees-content {
  height: 500px;
  margin: 0 150px;
  border: 1px solid red;
}

@media only screen and (max-width: 1000px) {
  h3 {
    padding-left: 100px;
  }

  .thankees-content {
    margin: 0 100px;
  }
}

@media only screen and (max-width: 1000px) {
  h3 {
    padding-left: 100px;
  }

  .schedule-content {
    margin: 0 100px;
  }
}

@media only screen and (max-width: 791px) {
}

@media only screen and (max-width: 570px) {
  h3 {
    padding-left: 30px;
  }

  p {
    font-size: 20px;
  }

  .thankees-content {
    margin: 0 30px;
  }
}
</style>

