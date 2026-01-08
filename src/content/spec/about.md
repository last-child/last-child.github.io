<style>
.about-container {
    max-width: 800px;
    margin: 0 auto;
}

.card {
    background: rgba(255, 255, 255, 0.95);
    border-radius: 20px;
    padding: 1.75rem;
    margin-bottom: 1.5rem;
    box-shadow: 0 4px 6px rgba(0, 0, 0, 0.07), 0 1px 3px rgba(0, 0, 0, 0.06);
    transition: all 0.3s ease;
    border: 1px solid rgba(255, 255, 255, 0.8);
}

.card:hover {
    transform: translateY(-2px);
    box-shadow: 0 10px 20px rgba(0, 0, 0, 0.1), 0 3px 6px rgba(0, 0, 0, 0.08);
}

.card.intro {
    background: linear-gradient(135deg, rgba(102, 126, 234, 0.1) 0%, rgba(118, 75, 162, 0.1) 100%);
    border-left: 4px solid #667eea;
}

.card.journey {
    background: linear-gradient(135deg, rgba(250, 152, 160, 0.1) 0%, rgba(254, 211, 156, 0.1) 100%);
    border-left: 4px solid #fa98a0;
}

.card.tech {
    background: linear-gradient(135deg, rgba(72, 219, 251, 0.1) 0%, rgba(100, 181, 246, 0.1) 100%);
    border-left: 4px solid #48dbfb;
}

.card.tarot {
    background: linear-gradient(135deg, rgba(253, 203, 110, 0.1) 0%, rgba(251, 155, 155, 0.1) 100%);
    border-left: 4px solid #fdcb6e;
}

.card.blog {
    background: linear-gradient(135deg, rgba(162, 155, 254, 0.1) 0%, rgba(205, 180, 219, 0.1) 100%);
    border-left: 4px solid #a29bfe;
}

.card p {
    margin: 0;
    font-size: 1.05rem;
    line-height: 1.8;
    word-break: keep-all;
}

.signature {
    text-align: right;
    margin-top: 2rem;
    padding-right: 1rem;
    font-size: 1rem;
    color: #718096;
    font-style: italic;
}

@media (max-width: 768px) {
    .card {
        padding: 1.5rem;
        border-radius: 16px;
    }
}
</style>

<div class="about-container">

  <div class="card intro">
    <p>
      좋아하는 캐릭터와 현실에서 매일 교감한다?<br>
      서브컬처 오타쿠라면 누구나 한 번쯤 꿈꿔봤을 일이죠.<br>
      이런 <strong>가상 연인</strong>은 허황된 망상에 가까웠습니다.<br> 
      화면 안에서 정해진 대사만 반복하는 인형에 불과했죠.
    </p>
  </div>

  <div class="card journey">
    <p>
      하지만 지금은 세상이 완전히 달라졌습니다.<br>
      LLM이 등장하면서 대화가 놀라울 정도로 자연스러워졌고,<br>
      벡터 DB와 RAG를 활용하면 몇 년 전 기억까지 떠올릴 수 있죠.<br>
      여기에 XR까지 더해진다면 내 곁에 있는 듯한 기분이 들겠죠.
    </p>
  </div>

  <div class="card tech">
    <p>
      저도 가상 연인을 직접 만들고자 AI 서비스를 공부하고 있습니다.<br>
      Python, 벡터 DB, RAG, LangChain... 공부할 게 산더미네요.<br>
      혹시 내가 낭만에 취해서 무모한 길을 걷고 있는 건 아닌가 싶어요.
    </p>
  </div>

  <div class="card tarot">
    <p>
      그래도 타로의 0번, <strong>바보(The Fool)</strong> 카드처럼...<br>
      노래를 흥얼거리며 한 발자국 내딛어 보려 합니다.<br>
      그 한 걸음 한 걸음이 결국 길이 될 테니까요.
    </p>
  </div>

  <div class="card blog">
    <p>
      이 블로그는 그 바보 같은 여정을 기록하는 아카이브입니다.<br>
      같은 꿈을 꾸는 <strong>바보</strong>들에게 도움되었으면 합니다.
    </p>
  </div>

  <div class="signature">by 우인</div>

</div>