# Wizzard Battle

기술: 3D, C#, Unity, VR
진행 기간: 2022.11 ~ 2023.01
팀 구성: 클라이언트 3명, 디자이너 1명
플랫폼: PC

**유니티 클라이언트, VR 개발자**

**프로젝트 매니저**

🔗 [Github](https://github.com/Wizard-Battle-GSM/WizzardBattle)

---

## Wizard Battle는

<aside>
💡 마법사들이 **1 : 1 fps 구도**로 불, 물, 풀이라는 3개의 속성을 가지고 서로 스킬을 사용해 상대를 이기는 것이 목적인 **멀티 3D 게임**

</aside>

## 🔍 인게임

---

![Untitled](Wizzard%20Battle%206041427a2110471696c975f23c56ad6e/Untitled.png)

![Untitled](Wizzard%20Battle%206041427a2110471696c975f23c56ad6e/Untitled%201.png)

타이틀 화면

게임 참가 화면

![Untitled](Wizzard%20Battle%206041427a2110471696c975f23c56ad6e/Untitled%202.png)

![Untitled](Wizzard%20Battle%206041427a2110471696c975f23c56ad6e/Untitled%203.png)

로비 화면

스킬 선택 화면

![Untitled](Wizzard%20Battle%206041427a2110471696c975f23c56ad6e/Untitled%204.png)

![Untitled](Wizzard%20Battle%206041427a2110471696c975f23c56ad6e/Untitled%205.png)

인게임 화면

게임 결과

## 📝 역할

---

- 플레이어의 이동
    - 움직임이 너무 격하게 움직여 어지러움을 유발하진 않는지 등을 고려하여 개발하였습니다.
    - 마우스의, VR 헤드셋의 움직임을 통해 플레이어의 시야 회전을 구성하였습니다.
    - 키보드와 VR 컨트롤러를 이용하여 플레이어의 움직임 개발하였습니다.
- 장판 · 궁극기 스킬
    - 장판의 경우 사용 시 예상 범위를 보여주고 스킬이 사용됩니다.
    - 궁극 기의 경우 상대의 시야를 흔드는 지진, 상대의 크기를 키우는 커져라, 성스러운 힘으로 플레이어에게 무적을 부여하는 Holy Shit 등을 구현하였습니다.
- 적절한 맵 배치
    - 마법사에 어울리는 맵과, 하늘처럼 맑은 하늘을 배치하려고 노력하였습니다.
- [HTC VIve Pro](https://www.vive.com/kr/product/vive-pro-full-kit/)를 위한 VR 개발하였습니다.
    - [XR Interaction Toolkit](https://docs.unity3d.com/kr/2019.4/Manual/com.unity.xr.interaction.toolkit.html)을 사용하여 VR 기기의 입력을 처리하였습니다.

## 💊 문제 해결

---

- 게임 시작 시 VR이 연동되지 않는 문제가 발생하였습니다.
    - XR Plug-in Management의 설정에서 OpenXR 선택 후 Initialize XR on Startup 선택하여 오류를 해결하였습니다.

## 🎁 느낀 점 및 성과

---

- 적당한 플레이 타임인지, 게임의 최적화가 적절히 이루어졌는지, 파일럿 테스트를 통해 게임의 적당한 밸런스와 두 플랫폼에서 적당한 크기의 UI 인지에 대해 생각하게 되었습니다.
- VR기기의 오작동으로 인해 교내 대회에서 시연 시간의 반 이상을 시연하지 못하게 되어 아쉽게 수상을 하지 못하였습니다.팀장임에도 불구하고 게임의 완성이라는 생각에 너무 긴장을 풀었던 거 같습니다. 그로 인해 마지막의 마지막까지 꼼꼼히 체크하는 습관을 지니게 되었습니다.
- 게임을 직접 기획.제작.수정.요구사항보완 과정을 거치며 지금까지 느껴본 적 없는 뿌듯함과 성취감을 알게 되었습니다.