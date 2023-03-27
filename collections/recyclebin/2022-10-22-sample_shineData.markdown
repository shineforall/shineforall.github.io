---
title:  본문 양식에 대한 샘플 페이지 # 문서 제목

header:
  teaser: https://www.fda.gov/files/COVID%20testing%20policy_1600x900_0.png # 리스트 페이지 썸네일 이미지 주소

##### 목차 설정 #####
toc: true # 페이지내 목차를 사용할지 안할지 설정 true|false
toc_label: 목차  # 목차 제목
toc_icon: cog   # 목차 아이콘 https://fontawesome.com/v5/search?o=r&m=free&s=solid 페이지에서 아이콘 네임. 저자권 확인 할 것.
toc_sticky: true  # 목차가 페이지를 따라다니게 함 true|false
##### 목차 설정 #####
---

본문 양식에 대한 샘플 페이지 입니다. 
해당 사이트는 [minimal-mistakes](https://mmistakes.github.io/minimal-mistakes/about/) 테마로 제작되었습니다.


# 기본 text 양식
## 테이블 넣기
```
  | Employee         | Salary |                                                              |
  | --------         | ------ | ------------------------------------------------------------ |
  | [John Doe](#)    | $1     | Because that's all Steve Jobs needed for a salary.           |
  | [Jane Doe](#)    | $100K  | For all the blogging she does.                               |
  | [Fred Bloggs](#) | $100M  | Pictures are worth a thousand words, right? So Jane × 1,000. |
  | [Jane Bloggs](#) | $100B  | With hair like that?! Enough said.                           |
```

  | Employee         | Salary |                                                              |
  | --------         | ------ | ------------------------------------------------------------ |
  | [John Doe](#)    | $1     | Because that's all Steve Jobs needed for a salary.           |
  | [Jane Doe](#)    | $100K  | For all the blogging she does.                               |
  | [Fred Bloggs](#) | $100M  | Pictures are worth a thousand words, right? So Jane × 1,000. |
  | [Jane Bloggs](#) | $100B  | With hair like that?! Enough said.                           |

```
  | Header1 | Header2 | Header3 |
  |:--------|:-------:|--------:|
  | cell1   | cell2   | cell3   |
  | cell4   | cell5   | cell6   |
  |-----------------------------|
  | cell1   | cell2   | cell3   |
  | cell4   | cell5   | cell6   |
  |=============================|
  | Foot1   | Foot2   | Foot3   |
```

  | Header1 | Header2 | Header3 |
  |:--------|:-------:|--------:|
  | cell1   | cell2   | cell3   |
  | cell4   | cell5   | cell6   |
  |-----------------------------|
  | cell1   | cell2   | cell3   |
  | cell4   | cell5   | cell6   |
  |=============================|
  | Foot1   | Foot2   | Foot3   |

* 주의 : 표 markdown 사용시 위 아래에 한줄씩 띄어 주셔야 합니다.

## 기본 양식 관련자료
[Markup: HTML Tags and Formatting](https://mmistakes.github.io/minimal-mistakes/markup/markup-html-tags-and-formatting/)

------

# 이미지 추가하기
## 기본
```liquid
  {% raw %}{% include figure image_path="https://mmistakes.github.io/minimal-mistakes/assets/images/unsplash-image-10.jpg" alt="this is a placeholder image" caption="This is a figure caption." %}{% endraw %}
```
또는
```html
<img src="https://mmistakes.github.io/minimal-mistakes/assets/images/unsplash-image-10.jpg">
```
{% include figure image_path="https://mmistakes.github.io/minimal-mistakes/assets/images/unsplash-image-10.jpg" alt="this is a placeholder image" caption="This is a figure caption." %}
>

## 중앙 정렬
```md
  ![image-center](https://mmistakes.github.io/minimal-mistakes/assets/images/image-alignment-580x300.jpg){: .align-center}
```
![image-center](https://mmistakes.github.io/minimal-mistakes/assets/images/image-alignment-580x300.jpg){: .align-center}

## 이미지 왼쪽 정렬
```md
![image-left](https://mmistakes.github.io/minimal-mistakes/assets/images/image-alignment-150x150.jpg){: .align-left} 이미지 왼쪽 정렬하고 텍스트를 오른쪽에 알맞은 크기로 배분합니다. 이미지 왼쪽 정렬하고 텍스트를 오른쪽에 알맞은 크기로 배분합니다. 이미지 왼쪽 정렬하고 텍스트를 오른쪽에 알맞은 크기로 배분합니다. 
```
![image-left](https://mmistakes.github.io/minimal-mistakes/assets/images/image-alignment-150x150.jpg){: .align-left} 이미지 왼쪽 정렬하고 텍스트를 오른쪽에 알맞은 크기로 배분합니다. 이미지 왼쪽 정렬하고 텍스트를 오른쪽에 알맞은 크기로 배분합니다. 이미지 왼쪽 정렬하고 텍스트를 오른쪽에 알맞은 크기로 배분합니다. 

이미지 왼쪽 정렬하고 텍스트를 오른쪽에 알맞은 크기로 배분합니다. 이미지 왼쪽 정렬하고 텍스트를 오른쪽에 알맞은 크기로 배분합니다. 이미지 왼쪽 정렬하고 텍스트를 오른쪽에 알맞은 크기로 배분합니다. 

## 이미지 오른쪽 정렬
```md
![image-right](https://mmistakes.github.io/minimal-mistakes/assets/images/image-alignment-150x150.jpg){: .align-right} 이미지 오른쪽 정렬하고 텍스트를 오른쪽에 알맞은 크기로 배분합니다. 이미지 오른쪽 정렬하고 텍스트를 오른쪽에 알맞은 크기로 배분합니다. 이미지 오른쪽 정렬하고 텍스트를 오른쪽에 알맞은 크기로 배분합니다. 
```
![image-right](https://mmistakes.github.io/minimal-mistakes/assets/images/image-alignment-150x150.jpg){: .align-right} 이미지 오른쪽 정렬하고 텍스트를 오른쪽에 알맞은 크기로 배분합니다. 이미지 오른쪽 정렬하고 텍스트를 오른쪽에 알맞은 크기로 배분합니다. 이미지 오른쪽 정렬하고 텍스트를 오른쪽에 알맞은 크기로 배분합니다. 

이미지 오른쪽 정렬하고 텍스트를 오른쪽에 알맞은 크기로 배분합니다. 이미지 오른쪽 정렬하고 텍스트를 오른쪽에 알맞은 크기로 배분합니다. 이미지 오른쪽 정렬하고 텍스트를 오른쪽에 알맞은 크기로 배분합니다. 

------

# 동영상 추가하기
## 유튜브
```liquid
{% raw %}{% include video id="cTuokF7-RXA" provider="youtube" %}{% endraw %}
```
또는
```html
  <iframe width="560" height="315" src="https://www.youtube.com/embed/i0ZabxXmH4Y" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>
```
{% include video id="i0ZabxXmH4Y" provider="youtube" %}



## 비메오
```liquid
{% raw %}{% include video id="417155101" provider="vimeo" %}{% endraw %}
```
또는
```html
<iframe src="https://player.vimeo.com/video/417155101?h=6dda444e0c&color=7ddd00" width="640" height="360" frameborder="0" allow="autoplay; fullscreen; picture-in-picture" allowfullscreen></iframe>
```
{% include video id="417155101" provider="vimeo" %}

## 동영상파일 주소로 넣기
```html
<video controls="" class="videoContainer">
  <source type="video/mp4" src="https://shineforall.org/wp-content/uploads/2021/10/SHINE-홍보영상-1편_KT-감염병-대응-연구-소개_최종.mp4">
</video>
```
<video controls="" class="videoContainer">
  <source type="video/mp4" src="https://shineforall.org/wp-content/uploads/2021/10/SHINE-홍보영상-1편_KT-감염병-대응-연구-소개_최종.mp4">
</video>



# 차트
차트를 넣고 싶은 부분에 아래 소스를 넣으면 됩니다. 그래프 세팅은 [Chart.js Sample](https://www.chartjs.org/docs/latest/samples/information.html) 페이지를 참고하여 자바스크립트 부분을 수정해서 사용해야 합니다. 같은 페이지에 차트를 2개 이상 넣을 경우 canvas id값 "myChart"값을 차트 별로 각각 다른게 설정해 주고 하단의 const myChart = new Chart( 함수 안의 "myChart"값도 canvas id 값에 맞추어 변경해 주어야 합니다.
```html
  <div>
    <canvas id="myChart"></canvas>
  </div>
  <script>
    const labels = [
      'January',
      'February',
      'March',
      'April',
      'May',
      'June',
    ];

    const data = {
      labels: labels,
      datasets: [{
        label: 'My First dataset',
        backgroundColor: 'rgb(255, 99, 132)',
        borderColor: 'rgb(255, 99, 132)',
        data: [0, 10, 5, 2, 20, 30, 45],
      }]
    };

    const config = {
      type: 'line',
      data: data,
      options: {}
    };

    const myChart = new Chart(
      document.getElementById('myChart'),
      config
    );

  </script>
```
<div>
  <canvas id="myChart"></canvas>
</div>
<script>
  const labels = [
    'January',
    'February',
    'March',
    'April',
    'May',
    'June',
  ];

  const data = {
    labels: labels,
    datasets: [{
      label: 'My First dataset',
      backgroundColor: 'rgb(255, 99, 132)',
      borderColor: 'rgb(255, 99, 132)',
      data: [0, 10, 5, 2, 20, 30, 45],
    }]
  };

  const config = {
    type: 'line',
    data: data,
    options: {}
  };

  const myChart = new Chart(
    document.getElementById('myChart'),
    config
  );

</script>

## 차트 참고
[Chart.js](https://www.chartjs.org/docs/latest/getting-started/)


# 목차 만들기
```m
페이지 상단에 아래의 메타태그 설정을 통해 옵션값을 조절 한다음
---
  toc: true # 페이지내 목차를 사용할지 안할지 설정 true|false
  toc_label: "목차"  # 목차 제목
  toc_icon: "cog"   # 목차 아이콘 https://fontawesome.com/v5/search?o=r&m=free&s=solid 페이지에서 아이콘 네임. 저자권 확인 할 것.
  toc_sticky: true  # 목차가 페이지를 따라다니게 함 true|false
---

MD 파일 내용에 #, ##, ### 를 사용하게 되면 해당 값을 기준으로 목차를 자동으로 완성시켜 줍니다.

```

# 리스트 페이지 썸네일 이미지 등록

```m
페이지 상단에 아래의 메타태그 설정을 통해 이미지 주소를 할당합니다. 메타태그내 들어쓰기 위치를 지켜야 합니다.
---
  header:
    teaser: https://shineforall.org/wp-content/uploads/2021/09/img_mainpage_phone01.png # 리스트 페이지 썸네일 이미지 주소
---
```



# 양식 참고 페이지
[Minimal Mistakes](https://mmistakes.github.io/minimal-mistakes/docs/helpers/)