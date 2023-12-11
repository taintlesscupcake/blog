+++
title = 'Mac Setting'
date = 2023-12-11T11:56:21+09:00
draft = false
+++

이 글은 약 3년간 M1 맥북 프로를 사용하면서 알게 된 추천 앱들과 설정들을 정리한 글입니다.

맥을 처음 사용하는 사용자에게 많은 도움이 되었으면 좋겠다. 이 글은 macOS Sonoma(14.1.2) 를 기준으로 작성되었습니다.

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