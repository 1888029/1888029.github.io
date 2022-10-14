# 프로젝트명: Find a member      

1888029 이현준

# [ 목차 ]
### [1.컨셉](#컨셉)
### [2.관련 이미지와 동영상](#관련-이미지-동영상)
### [3.대표 이미지 그리고 컨셉과 대표이미지 기반 작품 묘사](#대표-이미지)
### [4.Find a member의 구성 요소](#구성-요소)
### [5.게임 시스템 디자인](#게임-시스템-디자인)

[5-1.게임 오브젝트 분해](#게임-오브젝트-분해 )




# [컨셉]

## 메인컨셉 : 피지컬

- 가지고있는 무기들로 활용하면서 점프나 대쉬로 몬스터의 공격을 회피하는 자신의 실력으로 클리어하는것

### 서브 컨세 1 : 무기

- 다양한 무기들로 색다른 플레이를 할수있게 하는것

### 서브 컨세 2 : 패턴

-  한가지의 모션만 있는게 아닌 여러가지의 공격모션을 가지게 해서 패턴을 외우는 재미

### 서브 컨세 3 : 강화

- 자신을 강화해서 난이도를 낮추게 해서 못하는 사람들도 쉽게 플레이 할수있는 재미

### 서브 컨세 4 : 스테이지

- 한번에 끝나는것이 아닌 여러 스테이지를 플레이 할수있는 재미

### 서브 컨세 5 : 몬스터

- 여러 스테이지가 있는 만큼 다양한 몬스터를 볼수있는 재미

<br><br>

# [관련 이미지 동영상]

- 이미지

<br>

던그리드
이 게임이 제가 만들게임중 가장 유사하다고 해서 넣게 되었습니다. 
<br>
<img src="https://user-images.githubusercontent.com/114119568/191636784-7eda47b5-42ba-484d-b3c3-aeebfcebdf34.jpg"  width="300" height="200"/>
<br>

- 동영상

<br>

[<img src="https://user-images.githubusercontent.com/114119568/191642147-cd732a4d-32ec-4df8-892a-9d08943b0b47.jpg"  width="350" height="200"/>](https://youtu.be/90P0zAMKJmE)


- 이미지

<br>
 
스컬 더 히어로 슬레이어
캐릭터들 보유의 스킬이 있어서 캐릭터의 고유스킬을 넣어보자는 생각이들어서 넣게 되었습니다.
<br>
 
<img src="https://user-images.githubusercontent.com/114119568/192921597-602e2914-a8a9-4ed3-b883-103432b9667c.jpg"  width="300" height="200"/>


<br>

- 동영상
 
<br>

[<img src="https://user-images.githubusercontent.com/114119568/192922247-6dd23512-a746-47ee-bb33-549f19a2b2db.jpg"  width="350" height="200"/>](https://youtu.be/EeXWxCZWqfc)




<br><br>




# [대표 이미지]

<img src="https://user-images.githubusercontent.com/114119568/191642704-fa1c2f83-d826-4875-a71d-ad64f31490f3.jpg"  width="300" height="200"/><img src="https://user-images.githubusercontent.com/114119568/191642755-fae9189b-b49e-41d6-a3c4-6a4f0844cdb8.jpg"  width="150" height="200"/>


<br><br>

# [컨셉 & 대표이미지 기반 작품묘사]

> ### 대표이미지 기반 : 
 
UI : UI의 사용을 자신의 중요한 정보만 표시해서 플레이에 집중 할수 있게한다

우측상단 : 미니맵을 배치하여 적의 위치를 알려주게 합니다.

우측하단 : 캐릭터가 들고있는 무기와 보유하고있는 골드를 표시합니다.

좌측 하단 : 캐릭터의 체력, 스킬, 레벨을 표기 할것입니다.

화면상단: 보스가 나올 때 보스의 체력바을 표시합니다.

<br>
아이템창
<br>
무기1, 무기2: 지금 내가 쓸 수 있는 무기를 표시합니다.

아이템창: 무기들을 보관할수있으며 바꿔서 사용할수있게 합니다.





<br><br>


# [구성 요소]

다양한 무기들의 조합으로 적을 쓰러트리는 액션로그라이크 

## [도전 과제] 
1) 자신의 컨트롤로 점프 또는 대쉬로 적의 공격을 회피하여 상황에 맞게 근접무기 또는 원거리무기를 사용해서 적들을 제압해라

2) 적을 죽여 골드를 모아서 음식점 또는 상점에서 아이템을 구매해서 자신을 보안해라

3) 원거리무기는 장탄은 제한이 있지만 총알은 무한이며 재장전을 해야한다.

4) 캐릭터가 죽으면 보유하던 골드로 자신을 강화해라. 



## [재미 요소]
1) 다양한 무기들을 있어 그 무기를 사용하는 재미를 느낄수 있다.

2) 캐릭터의 스킬을 활용해 그 캐릭터의 재미를 보여줄수있다.

3) 게임오버를 하면 골드로 캐릭터를 레벨업시켜서 강해진 캐릭터를 보는 재미가 있다.

4) 여러가지의 스테이지와 보스가 있을것이며 지루하지 않을것이다.

## [키 조작]
WASD: 캐릭터 이동키

SpaceBar : 점프

마우스 좌클릭: 공격

마우스 우클릭: 대쉬

R : 재장전

Q: 캐릭터스킬

I : 아이템창

F: 상호작용(아이템드랍, 상점캐릭터 말걸기등등)

1번키: 1번무기

2번키: 2번무기






## 2. 이야기

[만들게 된 배경]
어느 방송인을 보고 이 사람의 주변배경으로 만들면 재미있을거같다 라는 생각이 들어 만들게되었다.

던그리드같은 로그라이크액션게임인 장르를 재밋게 해서 필요한 요소를 알수있어 재밋는게임으로 제작할거라 생각합니다.



## [카메라 관점] 
2개의 카메라를 제공할것이다.

하나는 캐릭터의 관점과 또하나는 미니맵에는 간단한 형태의 관점으로 할것이다.

## 3. 미적요소

[디자인]
배경: 스테이지가 있어 색다른 배경을 찾아야할 예정

캐릭터: 어느 방송인 캐릭터를 참고하여 도트프로그램으로 만들것이다.


## [음향]
배경음악: 계속들어도 질리지 않을 픽셀에 어울릴 노래

무기: 그 무기에 어울리는 가벼운사운드

몬스터: 몬스터를 공격할때 착착감기는 타격감과 공격할때의 사운드, 죽을때의 사운드

이 사운드들을 조절하는 시스템을 할예정



## 4. 기술

유니티를 사용하여 캐릭터들의 디자인들보단 이 게임의 코딩구현을 우선적으로 할것이다.




<br><br>


# [게임 시스템 디자인]


<br>

## [게임 오브젝트 분해] 

<br>

### 1. 플레이어 


|연번|오브젝트 이름|오브젝트 영문명|오브젝트 이미지|
|:----:|:----:|:----:|:----:|
|1|플레이어|player|<img src="https://user-images.githubusercontent.com/114119568/195470895-feda565f-0fce-43a7-9879-354ca9a0dbe8.png"  width="200" height="200"/>|


<br>

### 2. 몬스터

|연번|오브젝트 이름|오브젝트 영문명|오브젝트 이미지|
|:----:|:----:|:----:|:----:|
|1|침팬지|chimpanzeeA||
|2|침팬지(원거리형)|chimpanzeeB|<img src="https://user-images.githubusercontent.com/114119568/195470850-a3de8ff3-92ab-4911-b331-9fae3e481b24.png"  width="200" height="200"/>|
|3|일반박쥐|bat|<img src="https://user-images.githubusercontent.com/114119568/195470713-40a43dd1-ac6b-4fe8-aeb6-93e63fcd55ee.png"  width="200" height="200"/>|
|4|일반박쥐|babybat|<img src="https://user-images.githubusercontent.com/114119568/195470771-646b4f09-af18-4738-a3bc-175369609513.png"  width="200" height="200"/>|





<br>

### 3. 아이템

|연번|오브젝트 이름|오브젝트 영문명|오브젝트 이미지|
|:----:|:----:|:----:|:----:|
|1|동전(100원)|Coin|<img src="https://user-images.githubusercontent.com/114119568/195619774-4641a4fa-72a4-4e3c-9ae2-b215e97266be.png"  width="200" height="200"/>|
|2|돈다발(500원) |silverCoin|<img src="https://user-images.githubusercontent.com/114119568/195619964-674119b2-f671-492c-8592-28b4d67ab72a.png"  width="200" height="200"/>|
|3|돈뭉치(1000원) |goldCoin|<img src="https://user-images.githubusercontent.com/114119568/195620067-32741778-5cac-4c64-9e8b-cdcfdc005ee8.png"  width="200" height="200"/>|
|4|아이템상자|itemBox|<img src="https://user-images.githubusercontent.com/114119568/195478624-bca07ebc-b643-4bd5-88f5-e6f8cdc9bb55.png"  width="200" height="100"/>|
|5|동전상자|CoinBox|<img src="https://user-images.githubusercontent.com/114119568/195478956-08b5f116-8aad-4d0b-a875-5e037aa1332a.png"  width="200" height="120"/>|


<br>

### 4. 스테이지    

|연번|오브젝트 이름|오브젝트 영문명|오브젝트 이미지|
|:----:|:----:|:----:|:----:|
|1|마을|village||
|2|아이템문|itmeDoor||
|3|골드문|GoldDoor||
|4|상점문|shopDoor||
|5|보스문|bossDoor||



<br>

### 5. 상점    

|연번|오브젝트 이름|오브젝트 영문명|오브젝트 이미지|
|:----:|:----:|:----:|:----:|
|1|무기상점|weaponShop||
|2|음식상점|foodShop||

<br>

### 6. 근접무기    


|연번|오브젝트 이름|오브젝트 영문명|오브젝트 이미지|
|:----:|:----:|:----:|:----:|
|1|일반검(일반)|knife|<img src="https://user-images.githubusercontent.com/114119568/195651099-73651989-a59b-4af9-86ba-87b80bb95c4e.png"  width="200" height="200"/>|
|2|빠루|crowbar|<img src="https://user-images.githubusercontent.com/114119568/195470377-049ef523-4b9a-492a-9a5d-27a0e8232ce3.png"  width="200" height="200"/>|
|3|채찍|whip|<img src="https://user-images.githubusercontent.com/114119568/195628095-dfae8a3a-161b-4638-9b6e-bdcac08abe9d.png"  width="200" height="200"/>|
|4|카타나|katana|<img src="https://user-images.githubusercontent.com/114119568/195470254-223218a5-0ee3-4f4d-a04b-19718ceea1d5.png"  width="200" height="200"/>|
|5|글라디우스|gladius|<img src="https://user-images.githubusercontent.com/114119568/195802818-57c7b070-632a-4cf3-bf2f-5c9bb90c591e.png"  width="200" height="200"/>|




<br>

### 7. 원거리무기    

|연번|오브젝트 이름|오브젝트 영문명|오브젝트 이미지|
|:----:|:----:|:----:|:----:|
|1|권총(일반)|Gun||
|2|리볼버|revolver||
|3|샷건|shotgun||
|4|돌격소총|assaultRifle||
|5|기관단총|submachineGun||
|6|저격총(전설)|sniperRifle|<img src="https://user-images.githubusercontent.com/114119568/195470134-902bb245-0c00-46ed-ad4c-152a92df4960.png"  width="200" height="200"/>|
|7|수류탄|grenade|<img src="https://user-images.githubusercontent.com/114119568/195470008-1e9b4b42-c658-4070-9c28-db1fa38fdb7d.png"  width="200" height="200"/>|









<br>

### 8. 함정    

|연번|오브젝트 이름|오브젝트 영문명|오브젝트 이미지|
|:----:|:----:|:----:|:----:|
|1|가시|ThornTrap|<img src="https://user-images.githubusercontent.com/114119568/195470503-68eccd9b-a5eb-45e8-b10e-3f541984accf.png"  width="200" height="200"/>|

<br>

### 9. UI    

|연번|오브젝트 이름|오브젝트 영문명|오브젝트 이미지|
|:----:|:----:|:----:|:----:|
|1|체력,레벨|playerHPandLevel||
|2|대쉬칸|dashGauge||
|3|소유골드|MyCoin||
|4|소유무기|MyWeapon||
|5|스킬1,2|skill1,2||
|6|인벤토리|Inventory||
|7|조준점|aiming point||




<br>

### 10. 보스     

|연번|오브젝트 이름|오브젝트 영문명|오브젝트 이미지|
|:----:|:----:|:----:|:----:|
|1|진짜왁굳|RealWakgood|<img src="https://user-images.githubusercontent.com/114119568/195469728-ab9fafa6-172e-4e19-bd46-6bf1edc0b39d.png"  width="200" height="200"/>|


<br>

## 2. 파라미터(속성)    


1) 오브젝트 이름 :knife, crowbar, whip, katana, gladius, Gun, revolver, shotgun, assaultRifle,  sniperRifle, 
submachineGun, grenade

|속성|영문명칭|설명|비고|
|:----:|:----:|:----:|:----:|
|공격력|damage|적에게 얼마나 줄 수 있는 데미지||
|공격속도|attack speed|무기들의 데미지를 줄 수 있는 속도||
|범위|range|총알의 사거리와 근접무기의 범위를 설정하는것||
|탄창|bullet|총알을 보유하는 수치||
|재장전|reload|탄창이 다 떨어졌을 때 다시 수급하게하는것||
|총알속도|bullet speed|총알이 적에게 언제도달하는지 알 수 있는 속도||
|조준정확도|Aim|탄퍼짐이 있는 설정||

2) 오브젝트 이름 :chimpanzeeA, chimpanzeeB, bat, babybat

|속성|영문명칭|설명|비고|
|:----:|:----:|:----:|:----:|
|체력|enemyHP|적의 체력을 설정하는 것||
|공격력|damage|적의 데미지를 설정한다||
|투사체속도|projectile speed|원거리공격의 속도를 설정한다||
|감지범위|detection range|플레이어가 감지범위에 들어오는지 설정한다||
|이동속도|speed|적의 이동속도가 어느정도로 할지 설정한다||
|공격속도|attack speed|적의 공격이 초당몇번공격할지 설정하는것||


<br>

## 3. 행동   


1) 오브젝트 이름 :player

|속성|영문명칭|설명|
|:----:|:----:|:----:|
|앞으로걷기|walk|오른쪽기준 d키를 버튼입력 시 앞으로 이동한다.|
|뒤로걷기|backwalk|오른쪽기준 a키를 버튼입력 시 뒤로 이동한다.|
|점프|jump|SpaceBar를 버튼입력시 위로 점프한다.|
|대쉬|dash|마우스우클릭 입력시 마우스커서 방향으로 캐릭터기준 3미터 고속이동한다.|
|공격|attack|마우스좌클릭 입력시 자신이 들고있는 무기를 휘두르거나 사격한다.|
|상호작용|Interaction|상점,무기구매,아이템박스열기,아이템구매를 할 때 사용한다.|
|가만히서있기|stand still|아무 행동도 하지 않는 모습|
|아래점프|jump down|앏은간판같은곳은 밑으로 갈수있게 s키와 SpaceBar를 버튼입력시 아래로 내려간다.|
|사망|Dead|체력이 0이하가 되면 게임오버한다.|
|대쉬공격|dash attack|근접무기 장착 후 적에게 대쉬하면 대미지를 줄 수 있다.|


2) 오브젝트 이름 :chimpanzeeA, chimpanzeeB, bat, babybat

|속성|영문명칭|설명|
|:----:|:----:|:----:|
|움직이기|move|플레이어가 범위에 들어오거나 공격하면 움직인다. 또는 공중에있는 몬스터들은 범위에 없어도 움직일때가 있다.|
|공격|attack|플레이어에게 가까이가면 공격을 한다.|
|가만히서있기|stand still|플레이어가 범위에 들어오지않거나 공격하지않으면 아무행동하지 않는다.|
|사망|die|몬스터가 체력이 0이하가 되면 터지면서 죽는다.|

<br>

## 4. 상태 뽑아 보기

1) 오브젝트 이름 : player

|현상태|전이상태|전이조건|
|:----:|:----:|:----:|
|평상시|1초 무적|적에게 피격받았을때|
|1초 무적|평상시|1초무적이 끝났을때|
|평상시|0.3초무적|대쉬로 이동했을때|
|0.3초 무적|평상시|대쉬이동이 끝났을때
|평상시|사망|체력이 0이하가 되었을 때|
|사망|평상시|사망 후 마을스테이지로 이동했을 때|


2) 오브젝트 이름 : chimpanzeeA, chimpanzeeB, bat, babybat

|현상태|전이상태|전이조건|
|:----:|:----:|:----:|
|평상시|전투|플레이어가 감지범위안에 들어오거나 공격했을때|
|전투|이동|근접 몬스터가 플레이어 공격범위에 안들어올때|
|이동|전투|근접 몬스터가 플레이어 공격범위에 들어올때|
|평상시|사망|몬스터의 체력이 0이하가 되었을때|


3) 오브젝트 이름 : CoinBox, itemBox

|현상태|전이상태|전이조건|
|:----:|:----:|:----:|
|평상시|열음|플레이어가 상자를 열었을 때|
|열음|아이템|상자를 열을 때 아이템이 나올때|


4) 오브젝트 이름 : itmeDoor, GoldDoor, ShopDoor, BossDoor

|현상태|전이상태|전이조건|
|:----:|:----:|:----:|
|평상시|열음|플레이어가 스테이지에있는 몬스터를 다잡았을때|
|열음|다음스테이지이동|문 앞에서 상호작용(F키)를 눌렀을때|


<br>

## 5. 플레이어 캐릭터 속성(파라미터)

|속성|영문명칭|설명|
|:----:|:----:|:----:|
|체력|playerHP|자신의 체력을 알 수 있는 수치|
|레벨|dashGauge|대쉬가 얼마나 남아있는지 볼 수 있는 수치|
|스킬1|skill1|자신이 사용할 수 있는 첫 번째 스킬|
|스킬2|skill2|자신이 사용할 수 있는 두 번째 스킬|
|소유골드|MyCoin|내가 던전을 돌면서 골드를 얼마나 보유하는지 볼 수 있는 수치|
|소유무기|MyWeapon|자신이 아이템을 얼마나 소유하고있는지 볼 수 있는 창(껐다 켰다할 수 있다)|


<br>

## 6. 게임의 규칙

1) 핵심 규칙
던전의 방들을 들어가서 몬스터들이 스폰됩니다. 그 스폰된 몬스터들을 전부 해치워야 다음방을 갈 수 있으면 보상상자를 얻을수 있다.
입장할 수 있는 방은 2가지의 문으로 정해져있는데 첫 번째 문은 아이템상자를 얻을수 있는 아이템스테이지와 두 번 째 문은 돈상자를 주는 골드스테이지가 있다. 그중에서 선택해서 입장하면 다음스테이지로 이동한다. 그리고 중간쯤에는 한가지의 문으로 갈 수밖에 없는 스테이지가 있는데 그것이 상점스테이지이다. 상점스테이지에는 몬스터들이 없으며 골드로 구매하는 음식상점과, 무기상점이 있다. 음식상점에는 체력을 회복시켜주는 음식들이 있는데 그중에서 한가지만 먹을 수 있으며 무기상점은 다양한 무기들이 판매되고 있다. 
몬스터들은 감지범위 밖에 있을 땐 공격을 안 하고 가만히 있거나 조금씩 움직인다. 그러나 플레이어가 감지범위 밖에서 공격하거나 또는 감지범위 안에 들어왔을 때 플레이어를 추격해서 공격 또는 원거리 공격을 한다.
몬스터들의 공격을 회피하거나 또는 공격하기전에 자신의 무기로 해치워야 합니다.
체력이 0이되면 사망하게 된다. 만약 보스전때 동시에 0이되도 플레이어가 사망처리로 인하여 게임오버가 된다.
플레이어가 죽으면 마을로 돈은 일부만 가져오고 아이템들은 전부 사라지게된다. 
마을로 온 돈으로 레벨업을 해서 플레이어를 강화시킨다.


<br>

## 7. 게임에서 사용될 공식

적의 체력은 40인데 나의 무기 데미지는 8~10를 랜덤으로 줄 수 있는 무기이다. 평균4~5대를 때려야 죽일 수 있다.
그리고 랜덤이 아닌 확정 데미지줄 수 있는 무기도 있다. 기본권총은 데미지가 5이며 8대를 맞춰야 죽일 수 있다.
자신의 피통은 80인데 40데미지를 입어서 40이 되었는데 음식상점에서 음식을 먹을 때 30%회복된다면 전체피통기준으로 체력은 24를 회복합니다.

