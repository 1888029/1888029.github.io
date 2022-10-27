# 프로젝트명: Find a member      

Find a member(이현준) 1888029 이현준

# [ 목차 ]
### [1. 컨셉](#컨셉)
### [2. 관련 이미지와 동영상](#관련-이미지-동영상)
### [3. 대표 이미지 그리고 컨셉과 대표이미지 기반 작품 묘사](#대표-이미지)
### [4. Find a member의 구성 요소](#구성-요소)
### [5. 게임 시스템 디자인](#게임-시스템-디자인)

- [5-1. 게임 오브젝트 분해](#게임-오브젝트-분해 )
- [5-2. 파라미터 속성](#파라미터-속성 )
- [5-3. 행동](#행동 )
- [5-4. 상태 뽑아 보기](#상태-뽑아-보기 )
- [5-5. 플레이어 캐릭터 속성](#플레이어-캐릭터-속성 )
- [5-6. 게임의 규칙](#게임의-규칙 )
- [5-7. 게임에서 사용될 공식](#게임에서-사용될-공식 )

### [6. 개발 요구사항 & 흐름도](#개발-요구사항)
- [6-1. 요구사항](#요구-사항)
- [6-2. 키보드 이벤트](#키보드-이벤트)

### [7. 스토리 보드](#스토리-보드)

### [8. 프로토타입 개발 요구사항 (6주개발)](#개발)



# 1.컨셉  <a name='컨셉'></a>


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

# 2.관련 이미지 동영상  <a name='관련-이미지-동영상'></a>


<br>

던그리드

<br>
<img src="https://user-images.githubusercontent.com/114119568/191636784-7eda47b5-42ba-484d-b3c3-aeebfcebdf34.jpg"  width="300" height="200"/>
<br>



<br>

[<img src="https://user-images.githubusercontent.com/114119568/191642147-cd732a4d-32ec-4df8-892a-9d08943b0b47.jpg"  width="350" height="200"/>](https://youtu.be/90P0zAMKJmE)






<br><br>




# 3. 대표 이미지  <a name='대표-이미지'></a>

<img src="https://user-images.githubusercontent.com/114119568/191642704-fa1c2f83-d826-4875-a71d-ad64f31490f3.jpg"  width="300" height="200"/><img src="https://user-images.githubusercontent.com/114119568/191642755-fae9189b-b49e-41d6-a3c4-6a4f0844cdb8.jpg"  width="150" height="200"/>


<br><br>

# [컨셉 & 대표이미지 기반 작품묘사]

> ### 대표이미지 기반 : 
 
UI : UI의 사용을 자신의 중요한 정보만 표시해서 플레이에 집중 할수 있게한다

우측상단 : 미니맵을 배치하여 적의 위치를 알려주게 합니다.

우측하단 : 캐릭터가 들고있는 무기와 보유하고있는 골드를 표시합니다.

좌측 하단 : 캐릭터의 체력, 스킬, 레벨, 대쉬 표기 할것입니다.

화면상단: 보스가 나올 때 보스의 체력바을 표시합니다.

<br>
인벤토리
<br>
무기1, 무기2: 지금 내가 쓸 수 있는 무기를 표시합니다.

인벤토리: 무기들을 보관할수있으며 바꿔서 사용할수있게 합니다.





<br><br>


# 4. Find a member의 구성 요소  <a name='구성-요소'></a>

다양한 무기들의 조합으로 적을 쓰러트리는 액션로그라이크 

## [도전 과제] 
1) 자신의 컨트롤로 점프 또는 대쉬로 적의 공격을 회피하여 상황에 맞게 근접무기 또는 원거리무기를 사용해서 적들을 제압해라

2) 적을 죽여 골드를 모아서 음식점 또는 상점에서 아이템을 구매해서 자신을 보안해라

3) 원거리무기는 장탄은 제한이 있지만 총알은 무한이며 재장전을 해야한다.

4) 캐릭터가 죽으면 보유하던 골드로 자신을 강화해라. 



## [재미 요소]
1) 다양한 무기들을 있어 그 무기를 사용하는 재미를 느낄수 있다.

2) 캐릭터의 스킬을 활용해 그 캐릭터의 재미를 보여줄수있다.

3) 게임오버 하면 던전에서 얻은 골드로 캐릭터를 레벨업을 하여 강해진 캐릭터를 보는 재미가 있다.

4) 여러가지의 스테이지와 보스가 있을것이며 지루하지 않을것이다.

## [키 조작]
WASD: 캐릭터 이동키

SpaceBar : 점프

마우스 좌클릭: 공격

마우스 우클릭: 대쉬

R : 재장전

Q: 스킬1

E: 스킬2

I : 인벤토리

F: 상호작용(상점캐릭터 말걸기, 상자열기, 다음스테이지 )

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

[디자인][컬러]
전체적으로 자연 속 숲배경이지만 밝은 분위기를 가진 느낌으로 제작할 예정입니다.  


[음향]
마을, 상점스테이지, 몬스터스테이지, 보스스테이지로 각각에 맞는 가벼운 배경음악과 무기랑 어울리는 사운드로 제작할 예정입니다.




## 4. 기술

PC게임으로 유니티를 이용해 제작할것이며 오브젝트들은 도트로 제작할 예정입니다.  




<br><br>


# 5. 게임 시스템 디자인  <a name='게임-시스템-디자인'></a>


<br>

## 5-1. 게임 오브젝트 분해  <a name='게임-오브젝트-분해'></a>

<br>

### 1. 플레이어 


|연번|오브젝트 이름|오브젝트 영문명|오브젝트 이미지|
|:----:|:----:|:----:|:----:|
|1|플레이어|player|<img src="https://user-images.githubusercontent.com/114119568/195470895-feda565f-0fce-43a7-9879-354ca9a0dbe8.png"  width="200" height="200"/>|


<br>

### 2. 몬스터

|연번|오브젝트 이름|오브젝트 영문명|오브젝트 이미지|
|:----:|:----:|:----:|:----:|
|1|침팬지|chimpanzeeA|<img src="https://user-images.githubusercontent.com/114119568/196628882-ed646e9b-5310-40c6-9746-0799267ce6d7.png"  width="200" height="200"/>|
|2|침팬지(원거리형)|chimpanzeeB|<img src="https://user-images.githubusercontent.com/114119568/195470850-a3de8ff3-92ab-4911-b331-9fae3e481b24.png"  width="200" height="200"/>|
|3|일반박쥐|bat|<img src="https://user-images.githubusercontent.com/114119568/195470713-40a43dd1-ac6b-4fe8-aeb6-93e63fcd55ee.png"  width="200" height="200"/>|
|4|아기박쥐|babybat|<img src="https://user-images.githubusercontent.com/114119568/195470771-646b4f09-af18-4738-a3bc-175369609513.png"  width="200" height="200"/>|






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

### 4. 던전 입구    

|연번|오브젝트 이름|오브젝트 영문명|오브젝트 이미지|
|:----:|:----:|:----:|:----:|
|1|아이템문|itmeDoor|<img src="https://user-images.githubusercontent.com/114119568/196474762-24c51dab-0963-4bf1-9557-ffbcb9cf2330.png"  width="200" height="200"/>|
|2|골드문|GoldDoor|<img src="https://user-images.githubusercontent.com/114119568/196218279-d36bfb77-35b4-4a99-a1e8-81a3f28046df.png"  width="200" height="200"/>|
|3|상점문|shopDoor|<img src="https://user-images.githubusercontent.com/114119568/196659088-721f7080-f1ec-4a5f-a1df-214fc1e33f75.png"  width="200" height="200"/>|
|4|보스문|bossDoor|<img src="https://user-images.githubusercontent.com/114119568/196684357-51716d48-e28f-41ed-929c-357b61198d0e.png"  width="200" height="200"/>|










<br>

### 5. 상점    

|연번|오브젝트 이름|오브젝트 영문명|오브젝트 이미지|
|:----:|:----:|:----:|:----:|
|1|무기상점|weaponShop||
|2|음식상점|foodShop|<img src="https://user-images.githubusercontent.com/114119568/197971789-0ebd1ec2-b9a3-435c-b173-42deb8646fdc.png"  width="200" height="200"/>|



<br>

### 6. 근접무기    


|연번|오브젝트 이름|오브젝트 영문명|오브젝트 이미지|
|:----:|:----:|:----:|:----:|
|1|일반검|knife|<img src="https://user-images.githubusercontent.com/114119568/195651099-73651989-a59b-4af9-86ba-87b80bb95c4e.png"  width="200" height="200"/>|
|2|빠루|crowbar|<img src="https://user-images.githubusercontent.com/114119568/195470377-049ef523-4b9a-492a-9a5d-27a0e8232ce3.png"  width="200" height="200"/>|
|3|채찍|whip|<img src="https://user-images.githubusercontent.com/114119568/195628095-dfae8a3a-161b-4638-9b6e-bdcac08abe9d.png"  width="200" height="200"/>|
|4|카타나|katana|<img src="https://user-images.githubusercontent.com/114119568/195470254-223218a5-0ee3-4f4d-a04b-19718ceea1d5.png"  width="200" height="200"/>|
|5|글라디우스|gladius|<img src="https://user-images.githubusercontent.com/114119568/195802818-57c7b070-632a-4cf3-bf2f-5c9bb90c591e.png"  width="200" height="200"/>|




<br>

### 7. 원거리무기    

|연번|오브젝트 이름|오브젝트 영문명|오브젝트 이미지|
|:----:|:----:|:----:|:----:|
|1|권총|Gun|<img src="https://user-images.githubusercontent.com/114119568/196693101-792c85ad-4c27-48da-be85-e5b8e7e398c8.png"  width="200" height="200"/>|
|2|리볼버|revolver|<img src="https://user-images.githubusercontent.com/114119568/196733825-ea818f16-043d-4a2f-8ede-4c084cadaa19.png"  width="200" height="200"/>|
|3|샷건|shotgun|<img src="https://user-images.githubusercontent.com/114119568/196703159-8fc4ed3b-5c9a-4800-a253-2947933517c1.png"  width="200" height="200"/>|
|4|돌격소총|assaultRifle||
|5|기관단총|submachineGun|<img src="https://user-images.githubusercontent.com/114119568/198011741-6b62e290-fb64-4df2-b21b-aead11bbd180.png"  width="200" height="200"/>|
|6|저격총|sniperRifle|<img src="https://user-images.githubusercontent.com/114119568/195470134-902bb245-0c00-46ed-ad4c-152a92df4960.png"  width="200" height="200"/>|
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
|2|대쉬칸|DashGauge||
|3|소유골드|MyCoin||
|4|소유무기|MyWeapon||
|5|스킬1,2|skill1,2||
|6|인벤토리|Inventory||
|7|조준점|aiming point|<img src="https://user-images.githubusercontent.com/114119568/197977148-d8f610bb-7061-479c-a5a6-86fe303e6421.png"  width="200" height="200"/>|
|8|미니맵|MiniMap||





<br>

### 10. 보스     

|연번|오브젝트 이름|오브젝트 영문명|오브젝트 이미지|
|:----:|:----:|:----:|:----:|
|1|보스|Boss|<img src="https://user-images.githubusercontent.com/114119568/195469728-ab9fafa6-172e-4e19-bd46-6bf1edc0b39d.png"  width="200" height="200"/>|


<br>

##   5-2. 파라미터 속성  <a name='파라미터-속성'></a>
 


### 1) 오브젝트 이름 :knife, crowbar, whip, katana, gladius, Gun, revolver, shotgun, assaultRifle,  sniperRifle, submachineGun, grenade

|속성|영문명칭|설명|비고|
|:----:|:----:|:----:|:----:|
|공격력|Damage|적에게 얼마나 줄 수 있는 데미지||
|공격속도|Attack Speed|무기들의 데미지를 줄 수 있는 속도||
|범위|Range|총알의 사거리와 근접무기의 범위를 설정하는것||
|탄창|Bullet|총알을 보유하는 수치||
|재장전|Reload|탄창이 다 떨어졌을 때 다시 수급하게하는것||
|총알속도|BulletSpeed|총알이 적에게 언제도달하는지 알 수 있는 속도||
|조준정확도|Aim|탄퍼짐이 있는 설정||

### 2) 오브젝트 이름 :chimpanzeeA, chimpanzeeB, bat, babybat

|속성|영문명칭|설명|비고|
|:----:|:----:|:----:|:----:|
|최대체력|MaxHp|최대체력을 설정||
|현재체력|CurrentHp|남은 체력을 설정||
|피해량|Damage|데미지를 설정한다||
|투사체속도|Projectile Speed|원거리공격의 속도를 설정한다||
|감지범위|DetectionRange|플레이어가 감지범위에 들어오는지 설정한다||
|이동속도|Speed|적의 이동속도가 어느정도로 할지 설정한다||
|공격속도|AttackSpeed|적의 공격이 초당몇번공격할지 설정하는것||

### 3) 오브젝트 이름 :Boss

|속성|영문명칭|설명|비고|
|:----:|:----:|:----:|:----:|
|최대체력|MaxHp|최대체력을 설정||
|현재체력|CurrentHp|남은 체력을 설정||
|피해량|Damage|데미지 설정||
|투사체속도|ProjectileSpeed|원거리공격의 속도를 설정한다||
|패턴|Pattern|보스의 공격패턴을 설정||

### 3) 오브젝트 이름 :foodShop

|속성|영문명칭|설명|비고|
|:----:|:----:|:----:|:----:|
|체력회복|Heel|플레이어 체력을 회복한다.||


<br>

## 5-3. 행동  <a name='행동'></a>
   


### 1) 오브젝트 이름 :player

|속성|영문명칭|설명|
|:----:|:----:|:----:|
|앞으로걷기|Walk|조준점을 오른쪽기준으로 향하면서 d키를 버튼입력 시 앞으로 이동한다.|
|뒤로걷기|BackWalk|조준점을 오른쪽기준으로 향하면서 a키를 버튼입력 시 뒤로 이동한다.|
|점프|Jump|SpaceBar를 버튼입력시 위로 점프한다.|
|아래점프|JumpDown|앏은간판같은곳은 밑으로 갈수있게 s키와 SpaceBar를 버튼입력시 아래로 내려간다.|
|대쉬|Dash|마우스우클릭 입력시 마우스커서 방향으로 캐릭터기준 3미터 고속이동한다.|
|공격|Attack|마우스좌클릭 입력시 자신이 들고있는 무기를 휘두르거나 사격한다.|
|대쉬공격|DashAttack|근접무기 장착 후 적에게 대쉬하면 대미지를 줄 수 있다.|
|상호작용|Interaction|스테이지이동,상점,무기구매,아이템박스열기,아이템구매를 할 때 사용한다.|
|가만히서있기|StandStill|아무 행동도 하지 않는 모습|
|사망|Dead|체력이 0이하가 되면 게임오버한다.|


### 2) 오브젝트 이름 :chimpanzeeA, chimpanzeeB, bat, babybat

|속성|영문명칭|설명|
|:----:|:----:|:----:|
|움직이기|Move|플레이어가 범위에 들어오거나 공격하면 움직인다. 또는 공중에있는 몬스터들은 범위에 없어도 움직일때가 있다.|
|공격|Attack|플레이어에게 가까이가면 공격을 한다.|
|가만히서있기|StandStill|플레이어가 범위에 들어오지않거나 공격하지않으면 아무행동하지 않는다.|
|사망|Die|몬스터가 체력이 0이하가 되면 터지면서 죽는다.|

<br>

## 5-4. 상태 뽑아 보기  <a name='상태-뽑아-보기'></a>
   

### 1) 오브젝트 이름 : player

|현상태|전이상태|전이조건|
|:----:|:----:|:----:|
|평상시|1초 무적|적에게 피격받았을때|
|1초 무적|평상시|1초무적이 끝났을때|
|평상시|0.3초무적|대쉬로 이동했을때|
|0.3초 무적|평상시|대쉬이동이 끝났을때
|평상시|사망|체력이 0이하가 되었을 때|
|사망|평상시|사망 후 마을스테이지로 이동했을 때|


### 2) 오브젝트 이름 : chimpanzeeA, chimpanzeeB, bat, babybat

|현상태|전이상태|전이조건|
|:----:|:----:|:----:|
|평상시|전투|플레이어가 감지범위안에 들어오거나 공격했을때|
|전투|이동|근접 몬스터가 플레이어 공격범위에 안들어올때|
|이동|전투|근접 몬스터가 플레이어 공격범위에 들어올때|
|평상시|사망|몬스터의 체력이 0이하가 되었을때|


### 3) 오브젝트 이름 : CoinBox, itemBox

|현상태|전이상태|전이조건|
|:----:|:----:|:----:|
|평상시|열음|플레이어가 상자를 열었을 때|
|열음|아이템|상자를 열을 때 아이템이 나올때|


### 4) 오브젝트 이름 : itmeDoor, GoldDoor, ShopDoor, BossDoor

|현상태|전이상태|전이조건|
|:----:|:----:|:----:|
|평상시|열음|플레이어가 스테이지에있는 몬스터를 다잡았을때|
|열음|다음스테이지이동|문 앞에서 상호작용(F키)를 눌렀을때|


<br>

## 5-5. 플레이어 캐릭터 속성  <a name='플레이어-캐릭터-속성'></a>

|속성|영문명칭|설명|
|:----:|:----:|:----:|
|최대체력|MaxHp|처음시작한 최대체력|
|현제체력|CurrentHp|체력이 얼마나 남았는지 보는 수치|
|최대대쉬|MaxDash|대쉬의 최대갯수|
|현제대쉬|CurrentDash|대쉬가 얼마나 남았는지 보는 수치|
|최대레벨|MaxLevrl|자신의 최대레벨을 보는 수치|
|현제레벨|CurrentLevrl|자신의 현제레벨을 보는 수치|
|스킬1|Skill1|자신이 사용할 수 있는 첫 번째 스킬|
|스킬2|Skill2|자신이 사용할 수 있는 두 번째 스킬|
|쿨타임|CoolTime|스킬,대쉬 사용시 다시 사용할수있는 남은시간|
|소유골드|MyCoin|내가 던전을 돌면서 골드를 얼마나 보유하는지 볼 수 있는 수치|
|소유무기|MyWeapon|자신이 어떤 무기를 소유하고있는지 볼수있는 수치|




<br>

## 5-6. 게임의 규칙 <a name='게임의-규칙'></a>


### 1) 핵심 규칙

1. 마을에서 던전으로 입장할 때 아이템이 나오는 스테이지와 돈을 주는 스테이지중 하나를 골라서 입장한다.
2. 던전에 입장하면 몬스터들이 스폰됩니다.
3. 아이템스테이지를 클리어시 아이템상자를 얻을 수 있고 골드스테이지를 클리어시 코인상자를 얻을 수 있다.
4. 7스테이지와 11스테이지에는 확정적으로 상점스테이지로 갈 수 있다.
5. 상점스테이지에는 음식상점과 무기상점이 있다.
6. 플레이어가 죽으면 얻은 아이템들은 전부 잃고 일부골드만 가져오고 마을로 이동한다.
7. 마을에서 자신의 캐릭터를 레벨업을 시켜 난이도를 줄인다.
8. 14스테이지는 보스입장문이 있으며 15스테이지는 보스방이다.
9. 마지막 보스를 해치우면 게임은 클리어한다.



### 2) 보조 규칙

1. 스테이지에 있는 몬스터들을 전부 해치워야 다음 스테이지로 이동할 수 있다.
2. 음식상점에서는 음식 1개를 먹으면 더 이상 못먹게 된다.
3. 전투때는 인벤토리창을 열 수 없다. 



<br>

## 5-7. 게임에서 사용될 공식 <a name='게임에서-사용될-공식'></a>


1. 체력감소 CurrentHp -= damage
2. 체력회복  CurrentHp += MaxHp*heel/100
3. 대쉬사용: CurrentDash -= Dash
4. 대쉬회복 CurrentDash += CoolTime
5. 무기구매, 음식구매: MyCoin -= weaponShop, foodShop
6. 스킬사용 Skill -= CoolTime
7. 스킬복구 Skill += CoolTime
8. 레벨업 CurrentLevrl += 1
9. 대쉬횟수증가 CurrentLevrl % 10 += 1 
10. 최대체력증가 MaxHp += CurrentLevrl




<br>

# 6. 개발 요구사항 & 흐름도 <a name='개발-요구사항'></a>


## 6-1 요구 사항 <a name='요구-사항'></a>



### 화면은 메인, 설정, 키보드설정, 게임, 인게임설정, 게임오버, 게임클리어가 있습니다.
1. 게임시작시 메인화면에는 게임 시작,설정,종료 버튼이 3개있다.
2. 종료 클릭시 바로 게임이 종료된다.
3. 설정 클릭시 설정화면으로 이동한다.
4. 설정화면에는 음악사운드,효과음 사운드를 조절할수있으며 키보드설정, 돌아가기 버튼이 있다.
5. 키보드 설정 클릭시 키보드설정 화면으로 이동해 키조작을 바꿀수있다.
6. 돌아가기 클릭시 설정화면은 종료됩니다.
7. 게임 시작 클릭시 게임화면으로 이동한다. 
8. 메인화면, 설정, 종료, 돌아가기 버튼이 있다.
9. 메인화면 클릭시 메인화면으로 이동합니다.
10. 설정 클릭시 설정화면으로 이동합니다.
11. 종료 클릭시 게임이 종료됩니다.
12. 돌아가기 클릭시 플레이 하고있던 인게임설정화면은 종료됩니다.
13. 게임화면에는 플레이어,체력, 대쉬게이지, 스킬1, 스킬2, 소유무기, 소유골드, 미니맵이 표시되며 튜토리얼이 시작된다.
14. 조작은 wasd키가 이동키이며 점프는 스페이스바, 공격, 재장전, 상호작용, 스킬1, 스킬2, 인벤토리, 대쉬를 알려주고 마을에 도착한다.
15. ESC키를 누르면 인게임설정화면이 생깁니다.
16. 메인화면, 설정, 종료, 돌아가기 버튼이 있다.
17. 메인화면 클릭시 메인화면으로 이동합니다.
18. 설정 클릭시 설정화면으로 이동합니다.
19. 종료 클릭시 게임이 종료됩니다.
20. 돌아가기 클릭시 플레이 하고있던 인게임설정화면은 종료됩니다
21. 마을 오른쪽 끝부분으로 가면 던전으로가는 입구가 있다.
22. 던전으로 가는 입구에는 2가지의 문이 있습니다.
23. 2가지의 문 중 하나를 선택하여 상호작용을 해서 입장합니다.
24. 입장 후 스테이지에는 몬스터들이 스폰됩니다.
25. 몬스터들은 감지범위에 플레이어가 들어오지않는다면 움직이지 않고 플레이어가 감지범위밖에서 몬스터들을 때린다면 움직입니다.
26. 스폰된 몬스터들을 전부 해치우면 문앞에 아이템상자 or 코인상자가 스폰되며 상호작용시 상자가 열립니다.
27. 상자에는 아이템상자면 아이템이 랜덤으로 나오고 코인상자에는 돈을 줍니다.
28. 상점스테이지에는 무기상점과 음식상점이 있다.
29. 무기상점과 음식상점에 캐릭터들이 있으며 캐릭터들 앞에서 상호작용을 하면 상품구입창이 뜹니다.
30. 플레이어가 죽으면 게임오버 팝업이 뜨면서 골드일부만 가져오고 나머지는 전부 잃게된고 마을로 스폰한다.
31. 마지막 보스를 해치우면 상호작용 버튼이 표시된다.
32. 상호작용을 하면 게임클리어화면이 뜬다. 



## 6-2 키보드 이벤트 <a name='키보드-이벤트'></a>


# 7 스토리 보드 <a name='스토리-보드'></a>



# 8. 프로토타입 개발 요구사항 (6주개발)]<a name='개발'></a>

