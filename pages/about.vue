<template>
  <div class="about-wrapper">
    <img class="about-title" src="~@/assets/title_big_about.gif" />
    <div class="about-container">
      <p class="title-text">ＹＭＣＡは</p>
      <p class="content-text">
        1844年にイギリスのロンドンで誕生しました。ジョージ・ウイリアムズ（ＹＭＣＡ創立者）を中心とする12名の青年が、産業革命の進む中、非人間的な状況に多くの青年が追い込まれていくのに対し、これを自分たちの手で改善することを願い、青年を啓発する活動を始めたのが発端でした。<br />
        この青年たちのボランタリーな活動は多くの理解者・賛同者を得て、世界最大の青年運動へと発展しています。<br />
        そして、子どもたちの精神（Spirit）・知性（Mind）・身体（Body）の全人的な成長を願い、様々な分野で活動しています。
      </p>
    </div>
    <div class="about-container">
      <p class="title-text">姫路ＹＭＣＡは</p>
      <p class="content-text">
        1949（昭和24）年に設立され、65年にわたって自らの使命に基づき「青少年の健全育成」「豊かな地域社会の形成」「公正で平和な世界の実現」のため、活動を続けています。<br />
        この度、姫路YMCAは、財団法人からNPO法人へ組織変更となり、太子キャンプ場に事務所を移転し、野外活動を中心として、青少年の育成と地域社会の活動をすることになりました。<br />
        ＮＰＯ法人姫路ＹＭＣＡは「自分のいのちとみんなのいのちを大切にすること」「家族、地域のひとりとして責任があること」「ボランティア精神とリーダーシップを身につけること」「すこやかな心とからだを育むこと」を目標とします。<br />
        特に青少年が自然の中で自らの生活を創造する野外活動を通して、心身の発達を促し、社会性を養い、創意と工夫することを学び、青少年の成長に寄与する事業を行います。
      </p>
    </div>
    <div class="about-container">
      <p class="title-text">姫路ＹＭＣＡ太子教育キャンプ場は</p>
      <p class="content-text">
        日本のYMCAの野外活動は、社会の中で野外活動の先駆的な役割を担っています。<br />
        1920年に六甲山の南郷山麓で始まり、2015年で95年目を迎えました。その間、多くの青少年が野外活動を体験して育っていきました。<br />
        太子教育キャンプ場は1973年（昭和48年）に太子町原森林組合の協力のもと設立された姫路ＹＭＣＡ固有の野外活動施設です。<br />
        姫路市市街から約20分という距離にありながら、都会の喧騒の全く届かないロケーションとなっています。<br />
        地域の子ども会を中心に、年間2000名を超える青少年がデイキャンプに参加しています。
      </p>
    </div>
    <div class="about-container">
      <p class="title-text">YMCAキャンプの目的</p>
      <p class="about-purpose">
        １、自然生活を楽しみ、自然に適応する能力を身につける<br />
        ２、良い生活習慣を育て実践する。<br />
        ３、健康のための知識を得て、自分の身体を守る方法を知る。<br />
        ４、生活を豊かにする技術を学び、創造力を育む。<br />
        ５、良き友人を作る方法を学び、互いの存在と生命を尊重する心を育む。<br />
        ６、民主的なグループ経験から、社会に関わる責任感を育む。<br />
        ７、神の恵みを知り、感謝の気持ちを養う。
      </p>
    </div>
    <div class="about-container">
      <p class="title-text">
        YMCAではコーチや先生と呼ばず、リーダーと呼びます。
      </p>
      <p class="content-text">
        リーダーは教え導いたり、管理したりする存在ではなく、子どもとともにチャレンジし、学び合う存在です。<br />
        したがってプログラム中のどんなときにも子どもたちと一緒です。<br />
        まだまだ成長途中の未完成な大学生たちですが、子どもたちは一見完成された「大人」のリーダーシップより発展途上のボランティアリーダーシップに心を開いてゆく、そのことがYMCAでしかありえない大きな魅力です。
      </p>
    </div>
  </div>
</template>

<style scoped>
.about-wrapper {
  padding: 10px 80px;
}

.about-title {
  margin-bottom: 20px;
}

.about-container {
  margin-bottom: 20px;
  color: #666666;
  line-height: 28px;
}

.title-text {
  font-weight: bold;
  line-height: 28px;
}

.content-text {
  font-size: 14.4px;
}

.about-purpose {
  width: 65%;
  padding: 10px 15px;
  margin-top: 10px;
  margin-bottom: 20px;
  font-size: 14.4px;
  background-color: rgb(226, 241, 186);
  border: rgb(209, 218, 196) 3px dotted;
  border-radius: 15px;
}

@media screen and (max-width: 480px) {
  .about-wrapper {
    padding: 0px 20px;
  }

  .about-title {
    width: 90%;
    margin-bottom: 30px;
  }

  .about-container {
    margin-bottom: 60px;
    color: #666666;
    line-height: 28px;
  }

  .title-text {
    font-weight: bold;
    line-height: 24px;
    margin-bottom: 12px;
  }

  .content-text {
    font-size: 16px;
  }

  .about-purpose {
    width: 98%;
    padding: 10px 15px;
    margin-top: 10px;
    margin-bottom: 20px;
    font-size: 16px;
    background-color: rgb(226, 241, 186);
    border: rgb(209, 218, 196) 3px dotted;
    border-radius: 15px;
  }
}
</style>
