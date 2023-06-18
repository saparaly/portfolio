<template>
  <div class="edu mb">
    <h2>Education</h2>
    <div class="edu__container ">
        <div class="edu__item flex">
            <div class="left">
                <p>software engineer</p>
                <div class="bg">2020-2023</div>
            </div>
            <div class="right">
                <p> <a href="https://astanait.edu.kz/">Astana It University</a></p>
                <span>
                    GPA:3.0
                    <br><br>
                    The term of study at AITU is 3 years. 
                    <br><br>
                    The Bachelor programme is taught entirely in English
                </span>
            </div>
        </div>
        <div class="edu__item flex">
            <div class="left">
                <p>Golang Back-end developer</p>
                <div class="bg">2022-now</div>
            </div>
            <div class="right">
                <p> <a href="https://alem.school/">Alem School</a></p>
                <span>alem is the first programming school in Central Asia based on the principles of mutual learning.
                    <br><br>
                There are no teachers and boring lectures at alem, instead, learning is built on projects and the interaction of talented students with each other.</span>
                <br><br>
                <a href="../assets/alumni.pdf" class="btn" download>download certificate</a>
                <!-- <div class="btn">qw</div>
                <img src="../assets/" alt=""> -->
            </div>
        </div>
    </div>
  </div>
</template>

<script>
export default {

}
</script>

<style scoped lang="scss">
.left {
    width: 250px;
}

.edu__item{
    position: relative;
    padding: 20px 0;
    &::before{
        position: absolute;
        content: "";
        top: 100%;
        left: 0;
        width: 100%;
        background: #F0F0F6;
        height: 2px;
    }
}
.edu__container {
    background: var(--white);
    padding: 35px;
}
h2{
    text-align: center;
    width: 100%;
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