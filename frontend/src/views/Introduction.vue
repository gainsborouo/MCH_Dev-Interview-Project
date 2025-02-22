<template>
  <div class="introduction">
    <header class="intro-header">
      <img src="/IMG_8437.jpg" alt="picture" class="image">
      <div class="self-intro">
        <h2>陳璽安</h2>
        <br>
        <p>
          我是陳璽安，目前就讀交大資工大二。大一時加入熱舞社，雖然沒有很厲害但會跳一點點舞。興趣是追WEBTOON的漫畫、吃好吃的食物和畫可愛的小東西。
          <br>希望可以加入開發部認識更多人，和大家一起籌備黑客松！
          <br>下面是我的ig和blog，但blog才剛創所以沒什麼東西☹️
        </p>
        <br>
        <div class="others">
          <a href="https://www.instagram.com/annnchen__/" target="_blank">
            <img src="/ig-Icons.png" alt="instagram" class="icons">
            <span> Instagram</span>
          </a>
          <a href="https://annchenn.github.io/">
            <img src="/personal-blog.png" alt="personal blog" class="icons">
            <span> my blog</span>
          </a>
        </div>
      </div>
    </header>
    <section class="about-section">
      <h3>個人特質</h3>
      <ul>
        <li>開發熱忱：願意保持熱情學習各種知識。</li>
        <li>保持開放想法：對任何事情不會有先入為主的成見，願意聆聽他人想法。</li>
        <li>負責任的態度：對於指派的工作都會盡力完成、不拖延。</li>
      </ul>
    </section>
  </div>
</template>


<style scoped>
.others{
  display: flex;
  gap: 20px;
}

p {
  line-height: 1.7;
}

li {
  line-height: 2.5;
}

a {
  color: #333;
  font-size: 15px;
}

.icons{
  width:30px;
  height:30px;
  align-item: center;
}

.introduction {
  padding: 40px 20px;
  max-width: 1200px;
  margin: 0 auto;
}

@media(min-width: 600px){
  .intro-header {
    background-color: #E5E0DC;
    padding: 40px;
    border-radius: 10px;
    display: flex;
    gap: 30px;
  }
}

@media(max-width: 600px){
  .intro-header{
    background-color: #E5E0DC;
    padding: 40px;
    border-radius: 10px;
    gap: 30px;
  }
}



.intro-text h2 {
  font-size: 2rem;
  margin-bottom: 20px;
}

.intro-text p {
  font-size: 1.1rem;
  margin-bottom: 20px;
}

.contact-button {
  padding: 10px 20px;
  background-color: #656d73;
  border: none;
  border-radius: 5px;
  color: #fff;
  cursor: pointer;
}

.contact-button:hover {
  background-color: #36383a;
}

.about-section {
  margin-top: 40px;
  padding: 0 40px;
}

.about-section h3 {
  font-size: 1.6rem;
  margin-top: 20px;
  margin-bottom: 10px;
}

.about-section p {
  font-size: 1rem;
  line-height: 1.6;
}

.image{
  width:150px;
  height:150px;
  border-radius: 50%;
  object-fit: cover;
  border: 5px solid rgba(0, 0, 0, 0.2);
}

@media(min-width: 600px){
  .self-intro{
    flex: 1;
  }
}
</style>
