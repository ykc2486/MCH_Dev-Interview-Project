<template>
  <div class="introduction">
    <header class="intro-header">
      <div class="intro-container">
        <img src="./imgs/pic.jpg" alt="godtone" class="selfie"> </img>
        <div class="text">
          <h2 class="title-text">自我介紹</h2>
          <p class="Iansui">
            我是邱元廣，目前就讀交大資工一年級。我在高中時有接觸過一些javascript來管理資料表單的小專案。上學期修過計網概後也有嘗試去了解網路的細節與原理，並且有嘗試建立自己的VPN與DNS伺服器。盡管我在網頁開發的經驗不足，但我認為我是一個願意學習新知的人，我可以學習來補足這點。並且我也沒有團隊開發的經驗，因此我希望我可以加入梅竹黑客松的開發部，為我無趣的生活增添一些挑戰，並磨練我的技能，與同伴們一同開發出有趣又實用的專案。
          </p>
        </div>
      </div>
    </header>
    <section class="about-section">
      <h3 class="title-text">個人資訊補充</h3>
      <ul class="custom-list">
        <li class="li-color">希望可以挑戰自己</li>
        <li class="li-color">樂於學習</li>
        <li class="li-color">拜託請錄取我了 我什麼都會做的</li>
      </ul>
    </section>
  </div>
</template>


<style scoped>
@font-face {
  font-family: 'Iansui';
  src: url('../assets/Iansui-Regular.ttf') format('truetype');
  font-weight: normal;
  font-style: normal;
}

.Iansui {
  font-family: 'Iansui', sans-serif;
  font-size: 22px;
}

.introduction {
  padding: 40px 20px;
  max-width: 1200px;
  margin: 0 auto;
}

.intro-header {
  display: flex;
  background-color: #F7F3E9;
  padding: 40px;
  border-radius: 10px;
}

.intro-container {
  display: flex;
  align-items: center;
  /* background-color: aquamarine; */
  gap: 40px;
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
  color: #7a1515;
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

.title-text {
  color: #1E3A8A
}

.selfie {
  width: 200px;
  height: 200px;
  border-radius: 50%;
  object-fit: cover;
  border: 5px solid white;
  object-fit: cover;
}

.li-color {
  color: #FF7043;
}

.text {
  display: block;
  gap: 40px;
}

.custom-list {
  list-style: none;
  padding-left: 0;
}

.custom-list li::before {
  content: "";
  display: inline-block;
  width: 16px;
  height: 16px;
  background-image: url('https://icons.veryicon.com/png/o/business/my-library/light-bulb-14.png');
  background-size: contain;
  background-repeat: no-repeat;
  margin-right: 8px;
}
</style>
