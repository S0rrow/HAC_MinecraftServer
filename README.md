# HAC Minecraft Server Introduction

## 서버 정보

현재 HAC Minecraft 서버는 `Java Edition 26.1.2`를 기준으로 개설된 서버임. (작성일자 26.06.16 기준)

| 항목 | 값 |
|---|---|
| Minecraft | 26.1.2 |
| Loader | Fabric |
| 메모리 | 5GB |
| 음성 채팅 | Simple Voice Chat |
| 서버 형태 | RPG + 탐험 + 생활 + 건축 |

## Mod List

서버의 관리와 모딩의 용이함을 위해 Fabric을 통해 구축하였고, 총 50개의 모드가 현재 설치되어 있음.

설치된 모드들의 목록은 다음과 같음.

### 핵심 라이브러리

|모드|버전|용도|URL|
|---|---|---|---|
|Fabric API|0.152.1|Fabric 필수 라이브러리|https://modrinth.com/mod/fabric-api|
|Balm|26.1.2.7|Waystones 기반 라이브러리|https://modrinth.com/mod/balm|
|Shogi|26.1.2.5|Waystones 의존성 라이브러리|https://modrinth.com/mod/shogi|
|TCDCommonsAPI|5.3.2|Better Stats 의존성|https://www.curseforge.com/minecraft/mc-mods/tcdcommons|
|Framework|0.13.23|Goblin Traders 의존성|https://www.curseforge.com/minecraft/mc-mods/framework|
|Collective|8.25|Inventory Totem 의존성|https://www.curseforge.com/minecraft/mc-mods/collective|
|GeckoLib|5.5.1|JEG 의존성|https://www.curseforge.com/minecraft/mc-mods/geckolib|
|Delight Lib|26.05.18|More Delight 의존성|https://www.curseforge.com/minecraft/mc-mods/delight-lib|
|Fzzy Config|0.7.6|ReArm 의존성|https://www.curseforge.com/minecraft/mc-mods/fzzy-config|
|Cloth Config API|26.1.154|Rustic Delight 의존성|https://www.curseforge.com/minecraft/mc-mods/cloth-config|
|Konfig|0.3.1|Torch Toss 의존성|https://www.curseforge.com/minecraft/mc-mods/konfig|
|Amber Lib|11.0.1|Torch Toss 의존성|https://www.curseforge.com/minecraft/mc-mods/amber-lib|
|Fabric Language Kotlin|1.13.12|VeinMiner 의존성|https://modrinth.com/mod/fabric-language-kotlin|
|Cristel Lib|3.1.7|Towns and Towers 의존성|https://modrinth.com/mod/cristel-lib?version=26.1.2&loader=fabric|
|YetAnotherConfigLib|3.9.4|Xaero's Maps x Waystones, Zoomify 의존성|https://www.curseforge.com/minecraft/mc-mods/yacl|
|Trinkets|4.0.0.beta2|장신구 슬롯 시스템|https://www.curseforge.com/minecraft/mc-mods/trinkets-updated/download/8187944|

### 성능 최적화

|모드|버전|용도|URL|
|---|---|---|---|
|Lithium|0.24.5|서버 틱 최적화|https://modrinth.com/mod/lithium|
|Ferrite Core|9.0.0|메모리 사용량 감소|https://modrinth.com/mod/ferrite-core|
|Krypton|0.3.0|네트워크 최적화|https://modrinth.com/mod/krypton|
|Spark|1.10.172|성능 분석 및 프로파일링|https://modrinth.com/mod/spark|

### 탐험 및 월드 생성

|모드|버전|용도|URL|
|---|---|---|---|
|Towns and Towers|1.13.11|마을 및 구조물 추가|https://www.curseforge.com/minecraft/mc-mods/towns-and-towers|
|Structory|1.3.16|구조물 추가|https://www.curseforge.com/minecraft/mc-mods/structory|
|Dungeons and Taverns|5.2.0|던전 및 건물 추가|https://www.curseforge.com/minecraft/mc-mods/dungeon-and-taverns|
|Lio's Overhauled Villages|0.1.1|마을 개선|https://www.curseforge.com/minecraft/mc-mods/lios-overhauled-villages|
|Explorer's Compass|2.5.1|구조물 탐색|https://www.curseforge.com/minecraft/mc-mods/explorers-compass|
|Nature's Compass|2.5.0|바이옴 탐색|https://www.curseforge.com/minecraft/mc-mods/natures-compass|
|Lootr|1.22.36.109|플레이어별 개별 루팅|https://www.curseforge.com/minecraft/mc-mods/lootr-fabric|

### 이동 및 편의성

|모드|버전|용도|URL|
|---|---|---|---|
|Waystones|26.1.2.5|텔레포트 거점|https://modrinth.com/mod/waystones|
|Inventory Totem|3.4|인벤토리 보호|https://www.curseforge.com/minecraft/mc-mods/inventory-totem|
|VeinMiner|2.10.3|광맥 일괄 채굴|https://modrinth.com/mod/veinminer|
|Torch Toss|5.0.0|횃불 투척|https://www.curseforge.com/minecraft/mc-mods/torch-toss|
|Better Stats|5.3.0|통계 화면 개선|https://www.curseforge.com/minecraft/mc-mods/betterstats|

### 농사 및 음식

|모드|버전|용도|URL|
|---|---|---|---|
|Farmer's Delight|3.6.5|농사 및 요리|https://www.curseforge.com/minecraft/mc-mods/farmers-delight-refabricated|
|More Delight|26.05.26|Farmer's Delight 확장|https://www.curseforge.com/minecraft/mc-mods/more-delight-fabric|
|Rustic Delight|1.6.0|Farmer's Delight 확장|https://www.curseforge.com/minecraft/mc-mods/rustic-delight|
|Stacked Blocks|26.06.09|아이템 압축|https://www.curseforge.com/minecraft/mc-mods/stacked-blocks|
|Stacked Blocks: Farmer's Delight|26.06.09|Farmer's Delight 호환 확장|https://www.curseforge.com/minecraft/mc-mods/stacked-blocks-farmers-delight|

### RPG 및 전투

|모드|버전|용도|URL|
|---|---|---|---|
|Artifacts|15.0.0|특수 장신구 추가|https://www.curseforge.com/minecraft/mc-mods/artifacts|
|ReArm|2.5.0|전투 시스템 확장|https://www.curseforge.com/minecraft/mc-mods/rearm|
|Goblin Traders|1.12.0|특수 상인 추가|https://www.curseforge.com/minecraft/mc-mods/goblin-traders|
|Just Enough Guns New|1.7.0-hotfix|총기 추가|https://www.curseforge.com/minecraft/mc-mods/just-enough-guns-for-neoforge|

### 지도 및 HUD

|모드|버전|용도|URL|
|---|---|---|---|
|Xaero's Minimap|26.1.0|미니맵|https://www.curseforge.com/minecraft/mc-mods/xaeros-minimap|
|Xaero's Worldmap|1.41.0|월드맵|https://www.curseforge.com/minecraft/mc-mods/xaeros-world-map|
|Xaero's Maps x Waystones|2.10.1|Waystones 연동|https://modrinth.com/mod/xaeros-maps-x-waystones|
|RPG HUD|3.12|RPG 스타일 HUD|https://modrinth.com/mod/rpg-hud|
|AppleSkin|3.0.10|음식 HUD|https://modrinth.com/mod/appleskin|
|Zoomify|2.16.0|확대 기능|https://www.curseforge.com/minecraft/mc-mods/zoomify|
|Lamb Dynamic Lights|4.11.0|동적 광원|https://www.curseforge.com/minecraft/mc-mods/lambdynamiclights|

### 정보 조회

|모드|버전|용도|URL|
|---|---|---|---|
|Just Enough Items (JEI)|29.6.2.31|아이템 및 레시피 조회|https://www.curseforge.com/minecraft/mc-mods/jei|

### 멀티플레이

|모드|버전|용도|URL|
|---|---|---|---|
|Simple Voice Chat|2.6.18|근거리 음성 채팅|https://modrinth.com/mod/simple-voice-chat|

### 모드 수량

|분류|개수|
|---|---:|
|핵심 라이브러리|16|
|성능 최적화|4|
|탐험 및 월드 생성|7|
|이동 및 편의성|5|
|농사 및 음식|5|
|RPG 및 전투|4|
|지도 및 HUD|7|
|정보 조회|1|
|멀티플레이|1|
|**총합**|**50**|

---

## How To Enter

서버에 입장하기 위해서 우선 정품 마인크래프트 런처를 소유하고 있다는 점을 가정하고 설명하겠음.

가장 먼저 그냥 런처를 실행해서 Java Edition의 최신 릴리스가 플레이 가능한 상태인지 확인하고 진행하는 것이 필요함.

Fabric을 통해 구축한 서버이기 때문에 클라이언트 단에서도 동일한 환경 설정이 필요함.


### Requirements Installation

---

#### 1. `requirements.zip` 다운로드

우선 모드팩의 역할을 하는 [requirements.zip](https://github.com/S0rrow/HAC_MinecraftServer/releases)을 다운로드 받아야 함.


해당 zip 파일 내부에는 `fabric installer`와 `mods` 디렉토리가 존재함.

---

#### 2. fabric installer 실행.

`requirements.zip`의 압축을 해제하고 내부의 fabric installer라는 파일을 실행해야 함.

해당 파일은 fabric profile을 생성하기 위한 실행 파일임.

주의할 점으로 fabric installer를 실행하기 전에 마인크래프트 게임과 런처가 실행중이라면 종료하고 진행해야 함.

실행하면 Client 탭을 보면 되는데, Minecraft Version, Loader Version, Launcher Location이 나올텐데, 크게 건드리지 않는다면 대부분 최신 버전으로 잡혀있을거임.

작성일 26.06.16 기준으로 버전 정보는 다음과 같음.

```
Minecraft Version   : 26.1.2
Loader Version      : 0.19.3
```

Launcher Location의 경우 Windows 기준으로 `%APPDATA%\.minecraft`로 잡힐텐데, 해당 경로를 잘 기억해두셈.

문제가 없다면 Create Profile에 체크박스를 체크하고 Install 버튼을 눌러 설치를 진행하면 됨.

---

#### 3. mods 디렉토리 복사

파일 관리자를 열어서 Launcher Location에서 설정한 위치로 이동하게 되면 여러 디렉토리들이 나올 거임.

기본적으로는 `.minecraft`라는 이름의 디렉토리임.

이 `.minecraft` 디렉토리 아래에 `requirements` 내부의 `mods` 디렉토리를 복사 & 붙여넣기 해주면 됨.

---

#### 4. Fabric Profile 설치

Fabric 설정이 끝나면 이제 마인크래프트 런처를 실행하면 됨.

좌측 Minecraft: Java Edition 버튼을 눌러서 Java Edition 화면으로 진입하셈.

그 후, 설치 설정으로 들어가서 새 설치 설정 버튼을 눌러주셈.

이름의 경우 아무렇게나 지어도 무방하나 기존 설정과의 구분을 위해 __Fabric__ 이라고 짓는 것을 추천.

버전의 경우 클릭하게 되면 여러 버전 snapshot이 나오는데, 이중에 `fabric-loader`라는 이름이 붙은 스냅샷을 선택하면 됨.

게임 디렉토리의 경우, 2번에서 설명한 Launcher Location의 정보를 찾아보면 됨.

만약 직접 타이핑하기 귀찮으면 Windows 기준으로 `%APPDATA%\.minecraft` 이 주소를 복사해서 찾아보기 버튼을 누르면 나오는 파일 관리자의 주소창에 치면 됨.

그럼 Windows를 기준으로 하는 경우 `C:\Users\{유저명}\AppData\Roaming\.minecraft` 같은 이름의 디렉토리가, macOS를 기준으로 하는 경우 `/Users/{유저명}/Library/Application Support/minecraft` 같은 이름의 디렉토리로 나오게 될텐데 그걸 그대로 선택하면 됨.

해상도의 경우 자동으로 설정되어 있을텐데 그대로 두면 됨.

저장하고 실행하면 Mod관련 위험 안내가 나오게 될텐데 그 부분은 무시해도 무방함.

문제가 없다면 정상적으로 게임이 실행될 것임.

---

#### 5. Server 주소 추가

추가적으로 서버 주소의 경우 Discord 채널에 올려둘텐데, 해당 IP로 접속을 시도하면 됨.

마인크래프트 본 게임을 열고 멀티플레이어 버튼을 누른 뒤, Add Server 버튼을 눌러서 새로 서버를 추가하면 됨.

여기서 이름은 아무거나 해도 됨.

주소는 공유된 서버 IP로 입력하면 되고.

모드 파일들이 mods 디렉토리 내부에 잘 배치되었고 fabric launcher로 잘 실행된 상태라면 문제 없이 접속 가능할 것임.