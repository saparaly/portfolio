<template>
    <div class="edu mb">
      <h2>Work History</h2>
      <!-- <span class="center">Amet minim mollit non deserunt ullamco est sit aliqua dolor do amet sint. Velit officia consequat duis enim velit mollit. lorem ipsum</span> -->
      <div class="edu__container ">
          <div class="edu__item flex">
              <div class="left">
                  <p>Junior Front-end Developer </p>
                  <div class="bg">Apr 2022 - Dec 2022</div>
              </div>
              <div class="right">
                  <p><a href="http://acnew.113.kz/" target="_blank">astana-creative</a></p>
                  <span>Lorem ipsum dolor sit amet, consectetur adipiscing elit. Amet dapibus nibh ut faucibus nunc, egestas id amet porttitor. Pulvinar quisque sed amet, nulla nunc. Eleifend sodales posuere fusce tempus etiam et pellentesque. Molestie risus enim neque eget dui.</span>
              </div>
          </div>
      </div>
    </div>
</template>
  
<style scoped lang="scss">
  .edu__container {
      background: var(--white);
      padding: 35px;
  }
  h2{
      text-align: center;
      width: 100%;
      margin-bottom: 40px;
  }
  
  .center{
      margin: 25px auto 50px auto;
      width: 400px;
      display: block;
      text-align: center;
  }
  .left {
      margin-right: 150px;
      flex-shrink: 0;
  }
</style>