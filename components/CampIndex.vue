<template>
  <div>
    <div class="camp-index-container">
      <div class="camp-index-item">
        <img src="~@/assets/title_activity.gif" />
        <div class="camp-index-text pink">
          <p>
            野外活動は、子どもたちにとって｢楽しみ｣であり、生活および自然の中での体験そのものがプログラムです。体験の中で気づく、そして学ぶことをＹＭＣＡは大切に考え、未来を担う青少年の育成を目指して活動しています。
          </p>
          <NuxtLink to="/camp">
            <img src="~@/assets/description_button.gif" />
          </NuxtLink>
        </div>
      </div>
      <div class="camp-index-item">
        <img src="~@/assets/title_outdoor.gif" />
        <div class="camp-index-text yellow">
          <p>
            里山の雰囲気が色濃く残る場所で、親子が共に協力して、野外活動や料理など様々な活動に取り組んでいきます。親子の絆を深めると共に、家族間の親睦を深め、日本の文化や環境教育についても考えます。
          </p>
          <NuxtLink to="/outdoor">
            <img src="~@/assets/description_button.gif" />
          </NuxtLink>
        </div>
      </div>
      <div class="camp-index-item">
        <img src="~@/assets/title_daycamp.gif" />
        <div class="camp-index-text yellow">
          <p>
            山あり谷あり池ありの地形を利用した自然探索やハイキングなどのプログラムが常時可能で、専門の指導員や大学生のユースリーダー（大学生ボランティア）によって楽しいプログラムが展開されます。
          </p>
          <NuxtLink to="/daycamp">
            <img src="~@/assets/description_button.gif" />
          </NuxtLink>
        </div>
      </div>
    </div>
    <hr />
  </div>
</template>

<style scoped>
.camp-index-container {
  display: flex;
  padding: 7px;
}

.camp-index-item {
  text-align: center;
  padding: 7px;
}

.camp-index-item img {
  width: 220px;
}

.camp-index-text {
  color: #444444;
  font-size: 12.8px;
  height: 158px;
  padding: 7px;
}

.camp-index-container p {
  text-align: left;
  line-height: 22px;
}

.camp-index-container img {
  width: 180px;
}

.camp-index-container a {
  cursor: pointer;
}

.pink {
  background: #ffe8e8;
}

.yellow {
  background: #ffff9d;
}

hr {
  margin-left: 1%;
  width: 98%;
}

@media screen and (max-width: 480px) {
  .camp-index-container {
    display: block;
    padding: 7px;
    width: 350px;
    margin: 0 auto;
  }

  .camp-index-item {
    margin: 20px auto;
  }

  .camp-index-item img {
    width: 70%;
  }

  .camp-index-text {
    font-size: 14px;
    padding: 10px 15px 190px 15px;
  }

  .camp-index-text img {
    display: block;
    margin: 5px auto auto auto;
  }

  .camp-index-container p {
    line-height: 26px;
  }

  hr {
    display: none;
  }
}
</style>
