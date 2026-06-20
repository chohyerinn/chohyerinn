<h1 align="center">Chohyerin</h1>

<p align="center">
  <b>AI Student · LLM / RAG · AI Evaluation · Multimodal</b><br/>
  <i>사람에게 닿는 AI 서비스를 만듭니다.</i>
</p>

<p align="center">
  <img src="https://img.shields.io/badge/Gachon%20Univ.-Artificial%20Intelligence-00C2A8?style=flat-square&logo=googlescholar&logoColor=white" alt="Gachon AI"/>
  <img src="https://komarev.com/ghpvc/?username=chohyerinn&style=flat-square&color=00C2A8&label=profile+views" alt="profile views"/>
</p>

---

### 🌱 About Me

```python
class HyerinCho:
    def __init__(self):
        self.role = "AI Student @ Gachon University"
        self.major = "Department of Artificial Intelligence"
        self.focus = ["LLM", "RAG", "AI Evaluation", "Korean NLP", "Multimodal"]
        self.belief = "이기는 모델보다, 쓰이는 서비스를 만든다."

    def how_i_work(self):
        return [
            "리더보드 1등을 만든 건 화려한 모델이 아니라 꼼꼼한 앙상블·캘리브레이션",
            "전처리 32개 조합을 끝까지 비교하는 실험 설계",
            "데모까지 돌아가야 비로소 '완성'이라고 부른다",
        ]
```

- 🔭 **관심 분야** — 한국어 NLP 평가, RAG 파이프라인, 음성·청각 접근성, 재현 가능한 ML 실험
- 🛰️ **요즘 하는 일** — 멀티모달(음성+표정+맥락) 대화 보조, 근사 필터링 알고리즘 비교 연구
- 📫 **Contact** — chohyerinn03@gmail.com

---

### 🛠️ Tech Stack

**Languages**

<p>
  <img src="https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white"/>
  <img src="https://img.shields.io/badge/Kotlin-7F52FF?style=flat-square&logo=kotlin&logoColor=white"/>
  <img src="https://img.shields.io/badge/JavaScript-F7DF1E?style=flat-square&logo=javascript&logoColor=black"/>
  <img src="https://img.shields.io/badge/Shell-4EAA25?style=flat-square&logo=gnubash&logoColor=white"/>
</p>

**ML / AI**

<p>
  <img src="https://img.shields.io/badge/PyTorch-EE4C2C?style=flat-square&logo=pytorch&logoColor=white"/>
  <img src="https://img.shields.io/badge/Hugging%20Face-FFD21E?style=flat-square&logo=huggingface&logoColor=black"/>
  <img src="https://img.shields.io/badge/Whisper-412991?style=flat-square&logo=openai&logoColor=white"/>
  <img src="https://img.shields.io/badge/scikit--learn-F7931E?style=flat-square&logo=scikitlearn&logoColor=white"/>
  <img src="https://img.shields.io/badge/pandas-150458?style=flat-square&logo=pandas&logoColor=white"/>
  <img src="https://img.shields.io/badge/MediaPipe-0097A7?style=flat-square&logo=google&logoColor=white"/>
</p>

**Serving / App**

<p>
  <img src="https://img.shields.io/badge/FastAPI-009688?style=flat-square&logo=fastapi&logoColor=white"/>
  <img src="https://img.shields.io/badge/Android-3DDC84?style=flat-square&logo=android&logoColor=white"/>
  <img src="https://img.shields.io/badge/MCP-000000?style=flat-square&logo=anthropic&logoColor=white"/>
  <img src="https://img.shields.io/badge/Jupyter-F37626?style=flat-square&logo=jupyter&logoColor=white"/>
</p>

---

### 📌 Featured Projects

<table>
  <tr>
    <td width="50%" valign="top">

#### 🤟 [MUTON](https://github.com/Ai-pre/MUTON) · [Android](https://github.com/chohyerinn/MUTON-Android)
청각장애인을 위한 **실시간 멀티모달 대화 보조** 시스템.
음성(Whisper) + 표정(MediaPipe) + 맥락(Qwen2.5-Omni)을 결합해
실시간 자막·감정·요약을 제공하고, **날짜별 대화 기록**을
캘린더로 관리.
<br/><br/>
`Python` `FastAPI` `Qwen2.5-Omni` `Whisper` `Kotlin`

</td>
    <td width="50%" valign="top">

#### 🏆 [certainty-inference](https://github.com/chohyerinn/certainty-inference)
NIKL/말평 **확실성 추론 리더보드 1위** (MSE −0.0757).
KLUE-RoBERTa-large 다중 시드 + 그리디 앙상블 + 다항 캘리브레이션.
<br/><br/>
`PyTorch` `Transformers` `Ensemble` `Calibration`

</td>
  </tr>
  <tr>
    <td width="50%" valign="top">

#### 🔍 [filter-mcp-server](https://github.com/chohyerinn/filter-mcp-server)
Bloom · Counting Bloom · Cuckoo · SuRF **근사 필터 비교**를
동일한 MCP 도구 인터페이스로 실험. 정확도·메모리·FPR 트레이드오프 분석.
<br/><br/>
`Python` `MCP` `Data Structures`

</td>
    <td width="50%" valign="top">

#### 🏨 [DataScience_HotelBooking](https://github.com/chohyerinn/DataScience_HotelBooking)
호텔 예약 취소 예측. 전처리·인코딩 **32개 조합 교차검증**.
Best: ROC-AUC 0.92 · F1 0.79 + 로컬 데모 제공.
<br/><br/>
`scikit-learn` `pandas` `Jupyter`

</td>
  </tr>
</table>

---

### 🤟 MUTON in Action

<p align="center">
  <img src="assets/muton-login.png"  width="18%" alt="login"/>
  <img src="assets/muton-main.png"   width="18%" alt="main"/>
  <img src="assets/muton-camera.png" width="18%" alt="camera"/>
  <img src="assets/muton-record.png" width="18%" alt="record"/>
  <img src="assets/muton-detail.png" width="18%" alt="record detail"/>
</p>
<p align="center">
  <sub>로그인 → 실시간 대화 보조 → 카메라(표정 분석) → 날짜별 대화 기록 → 요약 상세</sub>
</p>

---

### 📊 GitHub Stats

<p align="center">
  <img src="https://github-readme-stats.vercel.app/api?username=chohyerinn&show_icons=true&theme=transparent&hide_border=true&title_color=00C2A8&icon_color=00C2A8" alt="stats" height="165"/>
  <img src="https://github-readme-stats.vercel.app/api/top-langs/?username=chohyerinn&layout=compact&theme=transparent&hide_border=true&title_color=00C2A8&langs_count=8" alt="top langs" height="165"/>
</p>

<p align="center">
  <img src="https://github-readme-streak-stats.herokuapp.com/?user=chohyerinn&theme=transparent&hide_border=true&ring=00C2A8&fire=00C2A8&currStreakLabel=00C2A8" alt="streak"/>
</p>

---

<p align="center">
  <i>✨ 기술이 누군가의 대화를 잇는 일에 관심이 많습니다. 함께 만들어요! ✨</i>
</p>
