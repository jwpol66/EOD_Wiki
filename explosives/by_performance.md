<style>
  .btn-container {
    display: flex;
    flex-wrap: wrap; /* 화면 좁으면 자동으로 줄바꿈 */
    gap: 10px; /* 버튼 사이 간격을 촘촘하게 붙임 */
    margin-top: 10px;
  }
  .eod-btn {
    background: #ffffff;
    border: 1px solid #ccc;
    border-radius: 20px; /* 둥근 알약 모양 버튼 */
    padding: 8px 16px;
    text-decoration: none !important;
    color: #0056b3 !important;
    font-weight: bold;
    font-size: 15px;
    transition: all 0.2s ease;
    box-shadow: 0 2px 4px rgba(0,0,0,0.05);
  }
  .eod-btn:hover {
    background: #28a745;
    color: white !important;
    border-color: #28a745;
    transform: translateY(-2px);
  }
</style>

# 성능에 의한 분류 🧨

폭발의 형태(연소 vs 폭굉)와 충격파의 속도에 따라 크게 '화약'과 '폭약'으로 분류합니다. 

### 1. 화약 / 완성화약류 (Low Explosives)
연소 또는 **폭연(Deflagration)** 형태로 반응. (음속 이하, 추진력/발사력 목적)

<div class="btn-container">
  <a href="#/explosives/black_powder" class="eod-btn">🔥 흑색화약</a>
  <a href="#/explosives/smokeless_powder" class="eod-btn">💨 무연화약</a>
</div>

<br>

### 2. 폭약 / 맹성화약류 (High Explosives)
**폭굉(Detonation)** 형태로 반응. (음속 초과 충격파 발생, 파괴/절단 목적)

<div class="btn-container">
  <a href="#/explosives/tnt" class="eod-btn">💣 TNT</a>
  <a href="#/explosives/c4" class="eod-btn">🧱 C4</a>
  <a href="#/explosives/dynamite" class="eod-btn">🧨 다이너마이트</a>
  <a href="#/explosives/tetryl" class="eod-btn">💥 테트릴</a>
  <a href="#/explosives/anfo" class="eod-btn">🍚 초안폭약</a>
</div>