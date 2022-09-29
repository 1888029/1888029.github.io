# 프로젝트명: Find a member

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

# [관련 이미지 & 동영상]

- 이미지
던그리드
<img src="https://user-images.githubusercontent.com/114119568/191636784-7eda47b5-42ba-484d-b3c3-aeebfcebdf34.jpg"  width="300" height="200"/>


- 동영상


[<img src="https://user-images.githubusercontent.com/114119568/191642147-cd732a4d-32ec-4df8-892a-9d08943b0b47.jpg"  width="350" height="200"/>](https://youtu.be/90P0zAMKJmE)


- 이미지
스컬 더 히어로 슬레이어
<img src="https://user-images.githubusercontent.com/114119568/192921597-602e2914-a8a9-4ed3-b883-103432b9667c.jpg"  width="300" height="200"/>

- 동영상


[<img src="https://user-images.githubusercontent.com/114119568/191642147-cd732a4d-32ec-4df8-892a-9d08943b0b47.jpg"  width="350" height="200"/>](https://youtu.be/EeXWxCZWqfc)



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

# [< Find a member > 구성 요소]

- 다양한 무기들의 조합으로 적을 쓰러트리는 액션 로그라이크 

<br>

## 1. 메커니즘

[도전 과제]

1. 자신의 컨트롤로 점프 또는 대쉬로 적의 공격을 회피하여 상황에 맞게 근접무기 또는 원거리무기를 사용해서 적들을 제압해라
2. 적을 죽여 골드를 모아서 음식점 또는 상점에서 아이템을 구매해서 자신을 보안해라
3. 원거리무기는 장탄은 제한이 있지만 총알은 무한이며 재장전을 해야한다.
4. 캐릭터가 죽으면 보유하던 골드로 자신을 강화해라. 

[재미 요소]

1. 다양한 무기들을 있어 그 무기를 사용하는 재미를 느낄수 있다.
2. 캐릭터의 스킬을 활용해 그 캐릭터의 재미를 보여줄수있다.
3. 게임오버를 하면 골드로 캐릭터를 레벨업시켜서 강해진 캐릭터를 보는 재미가 있다.
4. 여러가지의 스테이지와 보스가 있을것이며 지루하지 않을것이다.


[키 조작]

WASD: 캐릭터 이동키

SpaceBar : 점프

마우스 좌클릭: 공격

마우스 우클릭: 대쉬

R : 재장전

Q: 캐릭터스킬

I : 아이템창

F: 상호작용(아이템드랍, 상점캐릭터 말걸기등등)

만약 다른사람들의 이 키조작이 
불편할 경우를 생각해서 키설정을 구현


<br>

## 2. 이야기

[만들게 된 배경]  
어느 방송인을 보고 '이 사람의 주변배경으로 만들면 재미있을거같다.' 라는 생각이 들어 만들게되었다.
던그리드같은 로그라이크액션게임인 장르를 재밋게 해서 필요한 요소를 알수있어 재밋는게임으로 제작할거라 생각합니다

[카메라 관점]  
2개의 카메라를 제공할것이다.
하나는 캐릭터의 관점과 또하나는 미니맵에는 간단한 형태의 관점으로 할것이다.

<br>

## 3. 미적요소

[디자인]
배경: 스테이지가 있어 색다른 배경을 찾아야할 예정
[컬러]  
