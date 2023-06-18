<template>
  <div class="banner flex justify-center mb">
    <div class="left">
        <h1>
            I’m Assel Saparaly <span>Front-end</span> Developer 
        </h1>
        <span class="mt">
            I am interested in gaining in-depth
            knowledge and experience in any projects
            that you may want to offer.
            And also I would welcome the opportunity to discuss how I can contribute to your team, even as a beginner,
            and continue to develop my skills and knowledge. 
            <br><br>
            Though I am not yet experienced, I am committed to investing my time and effort to become
            proficient and produce high-quality, scalable, and maintainable code.
        </span>
        <a href="" class="btn">HIRE ME
            <svg width="16" height="16" viewBox="0 0 16 16" fill="none" xmlns="http://www.w3.org/2000/svg">
                <g clip-path="url(#clip0_228_31)">
                <path d="M10.7812 7.33312L7.20517 3.75712L8.14784 2.81445L13.3332 7.99979L8.14784 13.1851L7.20517 12.2425L10.7812 8.66645H2.6665V7.33312H10.7812Z" fill="#2B2B2B"/>
                </g>
                <defs>
                <clipPath id="clip0_228_31">
                <rect width="16" height="16" fill="white"/>
                </clipPath>
                </defs>
            </svg>
        </a>
    </div>
    <div class="right">
        <img data-v-6dec5f19="" src="https://img.freepik.com/premium-vector/3d-young-woman-avatar-happy-smiling-face-icon_313242-1241.jpg?w=2000" alt=""/>
    </div>
  </div>
</template>

<script>
export default {

}
</script>

<style scoped lang="scss">
.banner {
    width: 100%;
    background: var(--white);
    padding: 60px 90px;
    align-items: center;
}

.mt{
    margin: 20px 0;
    display: block;
}

h1 {
    font-weight: 700;
    font-size: 48px;
    line-height: 123.6%;
    color: #2B2B2B;
    span{
        color: var(--v1-primary);
        }
}

.right {
    width: 400px;
    img{
        width: 100%;
        height: 100%;
        object-fit: contain;
    }
}

.left {
    width: 50%;
}
</style>