<template>
  <div>
    <CampIndex></CampIndex>
    <img class="activity-banner" src="~@/assets/title_big_activity.gif" />
    <div class="activity-container">
      <div class="activity-container-left">
        <img src="~@/assets/activity_introduce_images.jpg" />
        <div class="left-bold-texts">
          <p>
            ●小集団生活体験を大切にします。（グループアプローチを取り入れた活動）
          </p>
          <p>
            ●豊かで健康な体験を大切にします。（ウエルネス思想、野外技術の習得)
          </p>
          <p>●自然、友人、自分自身に出会う機会を大切にします。</p>
          <p>
            ●子どもの内なるものへの取り組みを大切にします。（カウンセリング）
          </p>
          <p>
            ●子どもたちの望ましい行動に関心を示すことを大切にします。(行動理論など)
          </p>
        </div>
        <div class="left-normal-texts">
          <p>対象&nbsp;&nbsp;年中（5歳児）〜小学6年生（定員70名）</p>
          <p>姫路YMCA会員登録</p>
          <p>&nbsp;&nbsp;入会金&nbsp;&nbsp;2,000円/年</p>
          <p>&nbsp;&nbsp;年会費&nbsp;&nbsp;5,000円/年</p>
          <p>野外活動クラブ年間登録費&nbsp;&nbsp;12,000円/年</p>
          <p>野外活動クラブ参加費（3,000円〜/月程度）が必要です。</p>
          <p>※入会金・年会費以外は別途消費税が必要です。</p>
        </div>
        <div class="left-small-texts">
          <p>YMCAの野外活動の遊び場は、1万坪もある自然豊かな森「ASOBO」。</p>
          <p>
            四季折々の自然を感じながら、外遊びを満喫できるフィールドがお子様を待っています！
          </p>
          <p>
            そして、お子様の成長を支えるのは、トレーニングを積んだ、若さみなぎる優しい大学生リーダー達です！
          </p>
          <p>野山を駆け巡って遊びましょう！</p>
        </div>
      </div>
      <div class="activity-container-right">
        <img src="~@/assets/activity_memo_image.gif" />
        <p style="font-size: 12.8px">（変更になる場合もあります）</p>
        <div class="activity-right-texts">
          <p style="font-weight: bold">●集合・解散場所</p>
          <p>①YMCA太子遊びと冒険の森&nbsp;ASOBO(現地)</p>
          <p>②JR姫路駅南ロータリー</p>
          <p style="font-weight: bold">●活動場所</p>
          <p>YMCA太子遊びと冒険の森&nbsp;ASOBO</p>
        </div>
        <p class="table-title">2020年度、年間予定</p>
        <div class="activity_table">
          <p>4/19（日）ASOBOの森で、食べられるものを探そう</p>
          <p>5/17（日）ASOBOの森で、食べられるものを探そう</p>
          <p>6/21（日）ASOBOに生息する生き物を探そう</p>
          <p>7/19（日）池やプールで思いっきり水遊びをしよう</p>
          <p>
            <span class="responsive-hide">
              8/9（日）～10（月・休）森のテントで
              <br />
              &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;お泊り一泊キャンプ
            </span>
            <span class="responsive-show">
              8/9（日）～10（月・休）<br />
              森のテントでお泊り一泊キャンプ
            </span>
          </p>
          <p>9/20（日）</p>
          <p>10/18（日）</p>
          <p>11/22（日）</p>
          <p>12/13（日）</p>
          <p>1/24（日）</p>
          <p>2/21（日）</p>
          <p>3/14（日）</p>
        </div>
        <p style="font-size: 12.8px">
          ８月は一泊二日の宿泊キャンプを予定しています。
        </p>
        <CampJampTop></CampJampTop>
      </div>
    </div>
  </div>
</template>

<style scoped>
.activity-banner {
  margin-top: 10px;
}

.activity-container {
  display: flex;
  color: #666666;
  padding: 10px;
}

.activity-container-left {
  width: 535px;
  margin-right: 20px;
}

.activity-container-left img {
  width: 530px;
}

.left-bold-texts {
  font-size: 13.6px;
  font-weight: bold;
  line-height: 26px;
}

.left-normal-texts {
  font-size: 15.2px;
  line-height: 22px;
}

.left-small-texts {
  margin-top: 30px;
  font-size: 12.8px;
  line-height: 22px;
}

.activity_table {
  margin-top: 20px;
  margin-bottom: 20px;
  border-top: #c8dddd 1px solid;
  border-left: #c8dddd 1px solid;
  border-right: #c8dddd 1px solid;
}

.activity_table p {
  font-size: 14.4px;
  padding: 4px;
  font-weight: bold;
  border-bottom: #c8dddd 1px solid;
}

.responsive-show {
  display: none;
}

@media screen and (max-width: 480px) {
  .activity-container {
    display: block;
    padding: 20px;
  }

  .activity-container-left {
    width: 100%;
  }

  .activity-container-left img {
    width: 100%;
  }

  .left-bold-texts {
    margin-top: 20px;
    font-size: 14px;
    line-height: 20px;
  }

  .left-bold-texts p {
    margin-bottom: 8px;
  }

  .left-normal-texts {
    margin-top: 20px;
    font-size: 15.8px;
    line-height: 22px;
  }

  .left-small-texts {
    margin-top: 30px;
    margin-bottom: 40px;
    font-size: 14px;
    line-height: 24px;
  }

  .activity-right-texts {
    margin-bottom: 40px;
  }

  .table-title {
    font-size: 18px;
    font-weight: bold;
  }

  .activity_table {
    margin-top: 5px;
    margin-bottom: 10px;
  }

  .activity_table p {
    font-size: 15px;
    padding: 4px;
  }

  .responsive-hide {
    display: none;
  }

  .responsive-hide {
    display: inline-block;
  }
}
</style>
