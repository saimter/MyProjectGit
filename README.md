## 오디오 소스

> 씬에서 오디오 클립을 재생하는 도구

>재생을 하기 위해서 오디오 리스너나 오디오 믹서를 통해서 재생이 가능

>믹서의 경우 따로 만들어야 하며 오디오 리스너의 경우에는 메인 카메라에 붙어 있습니다

>컴포넌트 프로 퍼티

![audiosource](https://github.com/saimter/MyProjectGit/blob/main/audiosource.png)

>>Audio Resource : 재생을 진행할사운드 클립에 대한 등록

>>Ouptup : 기본적으로는 오디오 리스너에 직접 출력

>>>만든 오디오 믹서가 있다면 그 믹서르 통해 출력

>>Mute : 체크시 음소거

>>Bypass Effect : 오디오 ㅗ스에 적용되어 있는 필터 효과를 분리

>>Bypass Reverb Zones : 리법 존을 키거나 끄는 효과

>>리버브 존 : 오디오 리스너의위치에 따라 잔향 효과를 설정하는 도구

>>Play On Awake: 해당 옵션을 체크했을 경우 씬이 실행되는 시점에 사운드 재싱이 처리가 됩니다. 해당 기능 비활성화 시 스크립트를 통해 Play() 명령을 진행해 사운드를 재생

>Loop : 옵션 활성화 시 재생이 끝날때 오디오 클립을 루프

>Priority : 오디오 소스 우선 순위

>>0 우선 순위

>>128 기본

>>256 - 최하위

>Volumn : 리스너 기준으로 거리 기준 소리에 대한 수치

>Pitch : 재생 속도가 빨라지거나 느려질때 의 피치 변화량

>>1은 일반 속도

>>최대 수치는 3

>>StreoPan 소리 재생시 좌우 스피커 간의 소리 분포를 조절 가능

>>-1 : 왼쪽 스피커

>>0 : 균등

>>1 : 오른쪽 스피커

>Stereo Blend

>>0 : 사운드가 거리와 상관없이 일정하게 들어갑니다.

>>1 : 사운드가 사운드 또는 도구의 거리에 따라 변화

>Reverb Zone mix : 리버브 존에 대한 출력 신호 양을 조절 합니다

>>수치 옵션

>>>0 : 영향을 받지 않는다

>>>1 : 오디오 소스와 리버브 존 사이 신호를 최대치로 설정

>>>1.1 : 10db 증폭

>>동굴에서 소리가 울리는 효과 연출

>>건물 등에서 다른 부분을 반해서 울리는 소리에 대한 설정

>3D Sound Setting

>>Doppler Level - 거리에 따른 사운드 높낮이

>>>0 : 효과가 없음

>>Spread : 사운드가퍼지는 각도 0 ~ 360

>>>0 한점에서 사운드가 나오는 방식

>>>360 모든 방향에서 사운드가 퍼지는 방식

>>Volumn Rollff

>>Min Distance

>>Max Distance
