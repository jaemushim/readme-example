## Settings
- [airbnb](https://github.com/airbnb/javascript/tree/master/react)

⚠️ VSCode Prettier, Eslint 설치되었는지 확인해주세요.(필수)   
Code Spell Checker, TODO HIGHTlight 도 설치하여주세요.

## Used Library
### UI
- [froala-editor](https://github.com/froala/wysiwyg-editor)
- [react-modal](https://github.com/reactjs/react-modal)
- [react-toastify](https://github.com/fkhadra/react-toastify)
- [react-confirm-alert](https://github.com/GA-MO/react-confirm-alert)
- [swiper](https://github.com/nolimits4web/swiper)
- [react-tabs](https://github.com/reactjs/react-tabs)
- [react-menu](https://github.com/szhsin/react-menu)
- [react-range](https://github.com/tajo/react-range)
- [react-textarea-autosize](https://github.com/Andarist/react-textarea-autosize)
- [react-scroll-to-top](https://github.com/HermanNygaard/react-scroll-to-top)

### else...
- [framer](https://github.com/framer/motion)
- [react-swipeable](https://github.com/FormidableLabs/react-swipeable)

## Page Routes

- [/home](http://222.122.26.243:3030/home)          홈 (001_Main_Home_01)
- [/home/community](http://222.122.26.243:3030/home/community)          홈/커뮤니티 (01_커뮤니티_SubMain)
- [/home/recruit](http://222.122.26.243:3030/home/recruit)               홈/초빙정보 (02-1_초빙정보_SubMain)
- [/home/recruit/search](http://222.122.26.243:3030/home/recruit/search)        홈/초빙정보/검색결과 (02-1-0_초빙정보_일반 검색결과)
- [/home/lease/](http://222.122.26.243:3030/home/lease)        홈/임대분양 (03_01_임대분양메인)
- [/home/lease/search](http://222.122.26.243:3030/home/lease)        홈/임대분양/검색 (03_02_01_임대분양검색)
<br /><br />
- [/community](http://222.122.26.243:3030/community)                  커뮤니티 (01-1_커뮤니티_카테고리홈)
- [/community/board-detail](http://222.122.26.243:3030/community/board-detail)     커뮤니티/게시판 상세 (01-1-1_커뮤니티_게시글상세)
- [/community/board-write](http://222.122.26.243:3030/community/board-write)      커뮤니티/게시판 작성 (01-2-1_커뮤니티_무찌마_기본_게시글작성전)
<br /><br />
- [/recruit](http://222.122.26.243:3030/recruit)                    초빙정보 (02-3-1_초빙정보_전체초빙리스트)
- [/recruit/board-detail](http://222.122.26.243:3030/recruit/board-detail)       초빙정보/게시판 상세 (02-4_초빙정보 상세보기)
- [/recruit/resume](http://222.122.26.243:3030/recruit/resume)             초빙정보/온라인이력서 (02-4-3_온라인이력서)
- [/recruit/sub-2](http://222.122.26.243:3030/recruit/sub-2)              초빙정보/맞춤정보 (02-5-0_초빙정보_맞춤정보_설정전)
- [/recruit/sub-2-options](http://222.122.26.243:3030/recruit/sub-2-options)      초빙정보/맞춤정보 옵션설정 (02-5-1_초빙정보_맞춤정보 설정)
- [/recruit/sub-3](http://222.122.26.243:3030/recruit/sub-3)              내이력관리 (02-5-6_초빙정보_입사지원현황)
<br /><br />
- [/lease](http://222.122.26.243:3030/lease)  임대분양 (03_03_01임대분양_전체매물)
- [/lease/board-detail](http://222.122.26.243:3030/lease/board-detail)  임대분양/게시판상세 (03_03_01임대분양_전체매물)
- [/lease/sub-2](http://222.122.26.243:3030/lease/board-detail)  임대분양/맞춤매물 (03_04_01임대분양_맞춤매물)
- [/lease/sub-2-options](http://222.122.26.243:3030/lease/sub-2-options)  임대분양/맞춤매물/조건설정 (03_04_02임대분양_맞춤매물_조건설정_비활성)
- [/lease/sub-3](http://222.122.26.243:3030/lease/sub-3)  임대분양/관심매물 (03_05_01임대분양_관심매물)

## Styles Structure

```sh
styles
|
+-- base            # color, font, heading(h1,h2,h3~), 및 홈페이지 베이스 스타일
|
+-- components        # Checkbox, Radio, Modal, Input, Switch, Select 등 홈페이지 내 공통으로 재사용되는 기본 UI 컴포넌트
|
+-- layouts           # ex) header, footer 스타일
|
+-- libs              # 라이브러리 스타일 커스텀
|
+-- pages             # 페이지 내 사용되는 스타일
|
+-- utilities         # 자주 사용되는 유용한 유틸리티 스타일
     +-- tailwind.css   # tailwind.css 참조하여 일부 사용
     
+-- index.scss        # styles 폴더 내 모든 스타일 >> index.scss로 통합
```

## Note (작업시 유의)
- 풀 땡겼는데 node module 관련하여 에러뜨면 yarn install 하여주세요. 
- 이런식으로 키값 있는거 키값 수정해주셔야합니다. <br/>![image](https://user-images.githubusercontent.com/65330249/207900192-47dbb531-d606-46c9-8282-2afcce078cbd.png)
-  주석 풀었는데 error 뜨면 컴포넌트 import 하지 않아서 그러니 import 하여주세요. <br/>![image](https://user-images.githubusercontent.com/65330249/207900407-048257c3-c412-493c-b9b9-7da8c61ecebc.png)


## Reference
- [SCSS Architecture](https://itnext.io/structuring-your-sass-projects-c8d41fa55ed4) - scss 아키텍처 참조
- [BEM](https://getbem.com/) - html5 클래스네임 컨벤션
- [Google HTML/CSS Style Guide](https://google.github.io/styleguide/htmlcssguide.html) 구글 HTML/CSS 스타일 가이드 
- [Stop using margin, use Spacer component instead!](https://javascript.plainenglish.io/stop-using-margin-use-spacer-component-instead-953d9b2dbacc) - Spacer 컴포넌트 사용
- [tailwindcss](https://tailwindcss.com/) - 유틸리티 스타일 클래스 네임 형식 tailwindcss 사용 (styles/utilities/utilities.css)
- [react-custom-hooks-useboolean](https://marcoghiani.com/blog/react-custom-hooks-usetoggle-useboolean) - useBoolean 훅 사용
