+++
title = 'Mac Setting'
date = 2023-12-11T11:56:21+09:00
draft = false
+++

이 글은 약 3년간 M1 맥북 프로를 사용하면서 알게 된 추천 앱들과 설정들을 정리한 글입니다.

맥을 처음 사용하는 사용자에게 많은 도움이 되었으면 좋겠습니다. 이 글은 macOS Sonoma(14.1.2) 를 기준으로 작성되었습니다.

## 목차

1. [맥 기본 설정](#1-맥-기본-설정)
2. [필수 앱들](#2-필수-앱들)
3. [그 외 유명한 앱들](#3-그-외-유명한-앱들)


## 1. 맥 기본 설정

기본 설정 이라는 건 사람마다 많이 다를 수 밖에 없습니다. 아래는 제가 사용하면서 이 세팅은 앞으로도 계속 사용할 것 같다는 설정들입니다.

---

### - System Settings

몇 가지 유용한 기본 설정들을 확인해봅시다. 이 부분은 극히 주관적인 내용이므로, 동일하게 설정할 필요는 전혀 없으며 자신에게 맞을 것 같다는 항목만 적용하면 됩니다.

좌상단 ` > System Settings` 로 설정창을 열 수 있습니다.


#### **Control Center**

![Control Center](/img/control-center.png)

`Control Center Modules` 에서 자주 사용하는 항목들을 Menu Bar에 항상 표시하도록 설정할 수 있습니다. 

저는 위와 같이, 대부분 표시하지 않도록 설정했습니다.

배터리는 항상 봐야 하는 정보이지만, [아래](#배터리)에서 말씀드릴 앱을 사용하기 때문에 표시하지 않습니다.


#### **Keyboard**

![Keyboard](/img/keyboard.png)

`Key Repeat` 와 `Delay Until Repeat` 를 최대한 빠르게 설정합니다.

![Keyboard Shortcuts](/img/keyboard-shortcuts.png)
만일 외장 키보드를 사용할 경우, `Option` 키와 `Command` 키가 바뀌어 있는 경우가 많습니다. 
이 경우 `Keyboard Shortcuts > Modifier Keys` 에서 키를 바꿔줄 수 있습니다.

![Input Sources](/img/input-sources.png)
`Text Input` 탭의 `Edit..` 항목에서 모든 텍스트 자동 교정 옵션을 비활성화합니다. 특히 **개발자**분들은 `Smart Quotes` 를 **반드시** 비활성화 하는 것을 추천드립니다. 따옴표가 자동으로 바뀌어 코드 복사/붙여넣기가 제대로 되지 않습니다.

#### **Trackpad**

![Trackpad](/img/trackpad.png)
`Point & Click` 탭의 `Tap to click` 항목을 활성화합니다. 저는 마우스를 주로 사용하고, 트랙패드는 서브로 사용하기 때문에 이 항목이 비활성화 되어 있습니다. 하지만 트랙패드를 주로 사용하시는 분들은 피로도를 줄이기 위해 활성화하는 것을 추천드립니다.

![Trackpad Dragging](/img/trackpad-dragging.png)
추가적으로 `Accessibility > Pointer Control > Trackpad Options > Use trackpad for dragging` 항목을 Three finger drag 로 설정해보세요. 창을 이동시킬 때 세 손가락으로 드래깅이 가능해집니다. 사용해보면 신세계가 열립니다.

---

### - Finder Settings

맥의 기본 파일 탐색기인 Finder 의 설정을 변경해봅시다. `Finder` 를 실행한 후 `⌘ + ,` 를 눌러 설정창을 열 수 있습니다.

#### **General**

![Finder General](/img/finder-general.png)
`New Finder windows show` 를 `사용자 이름` 으로 설정합니다. 이렇게 하면 새로운 Finder 창을 열었을 때, 기본적으로 사용자 폴더가 열리게 됩니다.

#### **Advanced**
![Finder Advanced](/img/finder-advanced.png)
`Show all filename extensions` 를 활성화합니다. 이렇게 하면 파일의 확장자가 항상 표시됩니다.
`When performing a search` 를 `Search the Current Folder` 로 설정합니다. 이렇게 하면 Finder 에서 검색을 할 때, 맥 전체 검색이 아닌 현재 폴더에서만 검색하게 됩니다.

#### **Downloads**

![Finder Downloads](/img/finder-downloads.png)  
`Downloads` 폴더로 이동 후 `⌘ + J` 를 눌러 설정창을 열 수 있습니다.
여기서 파일의 정렬 방식을 변경할 수 있는데, 저는 위와 같이 `Date Added` 로 설정했습니다.
이렇게 하면 날짜별로 파일이 분류되고, 각 날짜 내에서는 파일의 이름 순으로 정렬됩니다.

---

## 2. 필수 앱들

"필수" 라는 단어는 매우 주관적입니다. 맥을 사용하는 목적은 사람마다 다를 것이고, 성격도 다르죠.

저는 **'내가 지금 이 앱이 없으면 불편하겠다'** 라고 생각하는 앱들을 필수 앱으로 정리했습니다.

---

### 생산성 앱

#### **Raycast**

![Raycast](/img/raycast.png)
[Alfred](https://www.alfredapp.com/) 라는 훨씬 오랜 역사를 가진 앱이 있습니다. `⌘ + Space` 로 실행시키는 Spotlight 의 대체 앱인데, `Powerpack` 을 구매해야만 사용할 수 있는 기능들이 많습니다.

이에 대한 대체 앱으로 [Raycast](https://www.raycast.com/) 를 추천드립니다. 이미 Reddit 등 해외 커뮤니티에서 많은 사람들이 이주했다는 글이 올라오고 있습니다. Alfred처럼 유료 플랜인 `Pro` 가 있지만 이를 구매하지 않더라도 대부분의 기능을 사용할 수 있습니다.

`Powerpack`을 이미 구매한 저도 Raycast 로 이주했는데, Extension 도 충분히 많아 사용에 불편함이 없었습니다.

#### **화면 분할**

윈도우에서는 기본적으로 지원하는 화면 분할이 맥은 기본적으로 지원되지 않습니다. 이를 위해 유료 앱인 [Magnet](https://apps.apple.com/us/app/magnet/id441258766?mt=12) 이 존재하지만, 대부분의 사용자들은 무료 앱인 [Rectangle](https://rectangleapp.com/) 의 기능으로도 충분할 것입니다.


#### **Aldente**

많은 분들이 아시다시피, 리튬 이온 배터리는 완충 및 방전 시 배터리 수명이 단축됩니다. [Aldente](https://apphousekitchen.com/) 이를 방지하기 위해 배터리를 일정 수준에서 Limit를 걸어주는 앱입니다. 보통 80%로 설정해두지만, 저처럼 충전기를 꼽아놓고 Clamshell 모드로 사용하는 경우에는 50~60% 정도로 설정해두는 것을 추천드립니다.

#### **압축 앱**

맥의 기본 압축 프로그램은 호환성에서 조금 떨어집니다. 윈도우 사용자들과 파일을 주고받을 때, 압축 파일이 깨지는 경우가 종종 있어, 보통 [Keka](https://www.keka.io/)를 사용합니다. Mac App Store에서 다운받으면 유료지만, 공식 홈페이지의 `다운로드` 에서 무료로 다운받을 수 있습니다.

다른 대안으로 [반디집](https://apps.apple.com/kr/app/bandizip-archiver/id1265704574?l=en-GB&mt=12)이 있지만 유료에 딱히 Keka에 비해 장점이 없어서 윈도우와 똑같은 환경을 구성하고 싶은 것이 아니라면 추천드리지 않습니다.


#### **메뉴 바 관리**

맥을 사용하다 보면 많은 앱들을 깔게 되고, 이 앱들로 인해 메뉴 바가 너무 지저분해집니다. 이를 위해 [Bartender](https://www.macbartender.com/) 라는 앱을 보통 사용합니다. 유료 앱이지만 충분히 돈 값을 하는 앱이라고 생각합니다.

무료 대안으로는 [HiddenBar](https://github.com/dwarvesf/hidden/releases)와 [Dozer](https://github.com/Mortennn/Dozer/releases)가 있지만, Dozer는 업데이트가 멈춰서 무료 중에서는 HiddenBar를 추천드립니다.


#### **키 맵핑**

보통 윈도우에서는 우Alt를 한영키로 사용하는 경우가 많습니다. 맥에서도 이를 사용하고 싶다면 [Karabiner](https://karabiner-elements.pqrs.org/) 라는 앱을 사용하면 됩니다. 

하지만 개발자 분들에겐 `Ctrl + Space` 를 사용한 언어 변환에 적응하는 것을 추천드립니다. Linux에서도 기본 언어 변환 키가 `Ctrl + Space` 이기 때문에, 이에 익숙해지는 것이 좋습니다.

#### **PopClip**

[PopClip](https://www.popclip.app/) 정말 간단한 앱이지만, 생산성과 확장성에서 매우 뛰어난 앱입니다. [Extension](https://pilotmoon.com/popclip/extensions/) 들이 매우 다양하게 존재하여, 여기 있는 대부분의 생산성 앱들과 같이 사용할 수 있어, 익숙해 질 수록 생산성이 엄청 올라갑니다.


#### **Yoink**

{{< figure src="https://eternalstorms.at/yoink/mac/img/yoinkmac.png" width="150px" >}}
[Yoink](https://apps.apple.com/kr/app/yoink-better-drag-and-drop/id457622435?l=en-GB&mt=12) 는 자료를 쉽게 관리할 수 있도록 해 주는 생산성 앱입니다.

파일 및 폴더, 텍스트 등을 끌어다 놓고 작업할 수 있는 임시 공간을 제공하여, 일을 할 때 필요한 자료들을 관리하기 쉽게 해 주는 앱입니다.

이를 위에서 소개한 [PopClip](#popclip) 의 Extension과 함께 사용하면 웹 서핑 등 자료를 찾을 때, 마구잡이로 필요한 정보를 넣어놓고, 나중에 확인하며 정리할 수 있습니다.

