# 🎥 Django_Netflix

추천 시스템을 이용한 영화 추천 사이트(Netflix)

<br/>

# 📃 프로젝트 정보

### 1. 제작기간

> 2022.06.02 ~ 2022.06.14

### 2. 참여 인원

> |                    Name                    |  Position   |
> | :----------------------------------------: | :---------: |
> | [김성호](https://github.com/Kim-sung-ho) | Back, Front |
> |   [김주훈](https://github.com/joohuun)    | Back, Front |
> |     [박진우](https://github.com/J1NU2)     | Back, Front |
> |    [최희원](https://github.com/wonbbnote)     | Back, Front |

### 3. 역할 분담

> - 김성호 : 상세 페이지(Front, Back), 좋아요 기능
> - 김주훈 : 로그인/회원가입(Front, Back), 데이터 크롤링
> - 박진우 : 상세 페이지(Front, Back), 댓글 기능
> - 최희원 : 메인 페이지(Front, Back), 추천 시스템 구현

<br/>

# 📚 기술 스택

### 1. Backend

> Python3  
> Django  
> MySQL  
> Pandas  
> Scikit-learn

### 2. Frontend

> HTML  
> CSS  
> Javascript

<br/>

# 📊 ERD

<details>
<summary>ERD</summary>
<div markdown="1" style="padding-left: 15px;">
<img src="https://s3.us-west-2.amazonaws.com/secure.notion-static.com/53ddeeee-901b-443e-98d0-61c5446d621a/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=AKIAT73L2G45EIPT3X45%2F20220823%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20220823T094517Z&X-Amz-Expires=86400&X-Amz-Signature=7266a86cd416327cc3b5827ef6e6049145d2967285ce706c132aeb3776ee9324&X-Amz-SignedHeaders=host&response-content-disposition=filename%20%3D%22Untitled.png%22&x-id=GetObject" width="800px"/>
</div>
</details>

<br />

# 🔑 핵심기능

### 1. 컨텐츠 기반 필터링을 통한 영화 추천

> 사용자가 해당 영화를 선택하면 해당 영화와 유사한 영화를 추천해줍니다.  
> [코드 보러가기](https://github.com/J1NU2/Django_Netflix/blob/c433f2b5b3a69c58f8430297e1b46530fa835ae8/movie/recommender_ml.py#L13)

<br/>

# 📕 기타 자료

### 1. 기획문서

> [Django_Netflix - Notion](https://www.notion.so/8abe3134758744a8bf4a850fc175712e)

### 2. 컨텐츠 기반 필터링

> [Content-based filtering - Google Colab](https://colab.research.google.com/drive/1JmVcMfKDPEMGhUyB12sCDCZlyFj0BM2P?usp=sharing#scrollTo=hKHvr_aEUEZy)

### 3. 발표영상

<table>
  <tbody>
    <tr>
      <td>
        <p align="center"> 22.06.14 발표 </p>
        <a href="/" title="Django_Netflix 발표">
          <img align="center" src="https://s3.us-west-2.amazonaws.com/secure.notion-static.com/192001d3-4530-4b6f-962a-838a86625e4a/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=AKIAT73L2G45EIPT3X45%2F20220823%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20220823T100728Z&X-Amz-Expires=86400&X-Amz-Signature=61c4ad479c72719a8ce1bbef6e0bdd57047f34c8f5d1a643571cc41c4025ccfb&X-Amz-SignedHeaders=host&response-content-disposition=filename%20%3D%22Untitled.png%22&x-id=GetObject" width="300" >
        </a>
      </td>
    </tr>
  </tbody>
</table>
