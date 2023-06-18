<template>
  <div class="projects mb">
    <h2>Portfolio</h2>
        <div class="small">* If the project doesn't have a link, you can see screenshots of the pages in the GitHub repository.</div>
        <div class="tabs flex">
            <div
            class="tab__item"
            :class="{ active: activeTab === 'vue' }"
            @click="changeTab('vue')"
            >
            Vue.js
            </div>
            <div
            class="tab__item"
            :class="{ active: activeTab === 'html-css-js' }"
            @click="changeTab('html-css-js')"
            >
            HTML, CSS, JS
            </div>
            <div
            class="tab__item"
            :class="{ active: activeTab === 'golang' }"
            @click="changeTab('golang')"
            >
            Golang
            </div>
        </div>

    <div class="tab__content" v-if="activeTab === 'vue'">
        <div class="tab__content-item" >
            <div class="img"><img src="../assets//projects/social.png" alt=""></div>
            <p><a href="https://github.com/saparaly/social-media">Social-Media</a> </p>
            <span class="mb-3">
                Social media app is developed using Golang and Vue.js with a PostgreSQL database
                <br><br>
                -  user registration
                <br>
                - user authentication
                <br>
                - users can create, edit, and delete posts<br>
                - react to posts and comments (like/dislike) <br>
                - also supports commenting on posts<br>
                - user profiles,<br>
                - search functionality, enabling users to search for specific content, including posts, users<br>
                - Various filters are available <br>
                - chat feature that utilizes ChatEngine technology<br>
            </span>
            <div class="flex">
                <a href="" target="_blank"><div class="tab__item btn">demo</div></a>
                <a href="" target="_blank"><div class="tab__item btn">code</div></a>
            </div>
        </div>
        <div class="tab__content-item">
            <div class="img"><img src="../assets//projects/movie.png" alt=""></div>
            <p><a href="https://github.com/saparaly/social-media">Movie App API</a> </p>
            <span class="mb-3">
                This is a simple movie app API that uses the OMDB API to fetch movie data. It is built using Vue.js, Axios, and a swiper slider.
                <br><br>
                - Search for movies by title
                <br>
                - View detailed information about each movie
                <br>
                - Use a swiper slider to browse through movie posters<br>
                - Use router to navigate between different pages <br><br>
            </span>
            <div class="flex">
                <a href="" target="_blank"><div class="tab__item btn">demo</div></a>
                <a href="" target="_blank"><div class="tab__item btn">code</div></a>
            </div>
        </div>
        <div class="tab__content-item">
            <div class="img"><img src="../assets/projects/weather.png" alt=""></div>
            <p><a href="https://github.com/saparaly/social-media">Weather App</a> </p>
            <span class="mb-3">
                This is a weather app built using Vue.js that allows users to 
                <br><br>
                - search for cities
                <br>
                - view the history of searched cities
                <br>
                - clear the search history. <br>
                - search for locations  <br>
                - add them to favorites  <br>
                - delete favorites  <br>
                - identify their own geolocation  <br><br>
                The app provides various weather data for each city, including the current temperature, hourly temperature, wind speed, and humidity
            </span>
            <div class="flex">
                <a href="" target="_blank"><div class="tab__item btn">demo</div></a>
                <a href="" target="_blank"><div class="tab__item btn">code</div></a>
            </div>
        </div>
    </div>
    <div class="tab__content" v-if="activeTab === 'html-css-js'">
        <div class="tab__content-item newim" >
            <div class="img"><img src="../assets/projects/sardar.png" alt=""></div>
            <p><a href="https://sardar-group.kz/">SARDAR GROUP</a> </p>
            <span class="mb-3">
                SARDAR Construction Group, a construction company.
                <br><br>
                -  this website has 9 pages
                <br>
                - this is my first commercial website
            </span>
            <div class="flex">
                <a href="https://sardar-group.kz/" target="_blank"><div class="tab__item btn">demo</div></a>
            </div>
        </div>
        <div class="tab__content-item newim" >
            <div class="img"><img src="../assets/projects/aventura.png" alt=""></div>
            <p><a href="https://aventura.kz/">aventura travel</a> </p>
            <span class="mb-3">
                Travel agency "Let's go!"
                <br><br>
                -  this website has 11 pages
            </span>
            <div class="flex">
                <a href="https://aventura.kz/" target="_blank"><div class="tab__item btn">demo</div></a>
            </div>
        </div>
        <div class="tab__content-item newim" >
            <div class="img"><img src="../assets/projects/beles.png" alt=""></div>
            <p><a href="https://belesholding.kz/">beles holding</a> </p>
            <span class="mb-3">
                Belec holding, a construction company.
                <br><br>
                -  this website has 11 pages
            </span>
            <div class="flex">
                <a href="https://belesholding.kz/" target="_blank"><div class="tab__item btn">demo</div></a>
            </div>
        </div>
        <div class="tab__content-item newim" >
            <div class="img"><img src="../assets//projects/edd.png" alt=""></div>
            <p><a href="http://edd.kz/">ENGINEERING DESIGN DEVELOPMENT</a> </p>
            <span class="mb-3">
                The EDD Group of Companies operates in the field of power station construction in Kazakhstan since 2014.
                <br><br>
                -  this website has 10 pages
            </span>
            <div class="flex">
                <a href="http://edd.kz/" target="_blank"><div class="tab__item btn">demo</div></a>
            </div>
        </div>
        <div class="tab__content-item newim" >
            <div class="img"><img src="../assets/projects/has.png" alt=""></div>
            <p><a href="http://has.113.kz/">HAS</a> </p>
            <span class="mb-3">
                Railway container transportation of consolidated and complete cargoes from China.
                <br><br>
                -  landing page
            </span>
            <div class="flex">
                <a href="http://has.113.kz/" target="_blank"><div class="tab__item btn">demo</div></a>
            </div>
        </div>
    </div>
    <div class="tab__content" v-if="activeTab === 'golang'">
        <p>project coming soon</p>
    </div>
  </div>
</template>

<script>
export default {
  data() {
    return {
      activeTab: 'vue'
    };
  },
  methods: {
    changeTab(tab) {
      this.activeTab = tab;
    }
  }
}

</script>

<style scoped lang="scss">
.small{
    font-size: 14px;
    color: var(--v1-primary);
    margin-bottom: 20px;
}
.img {
    width: 100%;
    height: 300px;
    margin-bottom: 20px;
    border: 1px solid;
    img {
        width: 100%;
        height: 100%;
        object-fit: contain;
    }
}

.tab__content-item.newim {
    .img {
        overflow: hidden;
        img {
            width: unset;
            height: unset;
            object-fit: unset;
            transition: transform 4s ease;
        }
        &:hover img{
            transform: translateY(-65%);
        }
    }
}
.tabs {
    margin-bottom: 30px;
}
.tab__item {
    margin-right: 20px;
    cursor: pointer;
}
.tab__item.active{
    color: var(--v1-primary);
    font-weight: bold;
}

span{
    display: block;
}

.tab__content {
    display: grid;
    grid-template-columns: repeat(3, 1fr);
    grid-gap: 50px;
}
</style>