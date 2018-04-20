---
layout: post
title:  "Mail form Table"
date:   2018-04-12
img: html.gif
categories: [html, table, mail form]
---

####  메일폼을 html 의 table을 사용하여 보낼 때

메일을 html로 작성해서 전달할때에는 몇가지 주의 사항이 필요하다.
1. css 는 인라인 스타일로만 작성한다.
2. 블럭요소를 사용할때에는 부모요소에있는 스타일 속성을 똑같이 한번더 적용해준다.
3. 태그가 가지는 기본 속성이 있으면 그걸 우선으로 지정해준다.
4. 아웃룩에서는 `padding` 값이 먹지 않는다.
5. `font-family` 는 기본 폰트만 사용한다.
6. 주석은 제거한다.
7. 테이블의 기본 배경은 투명이다.
8. 이미지의 높이값은 1000px 미만으로 슬라이스하여 업로드한다.
9. 링크 또는 이미지 경로를 입력할때는 상대경로가 아닌 절대 경로를 입력한다.


{% highlight html %}
    <table cellpadding="0" cellspacing="0" style="border-collapse:collapse;background:#ffffff;">
  <tr>
    <td style="padding:0;margin:0;">
      <img src="이미지 경로1" alt="" style="display:block;vertical-align:top;border:none;" border="0">
      <!-- 이미지 자체가 td의 내부에 빈틈없이 꽉 차도록 만들어 주는것이 좋음  -->
    </td>
  </tr>
  <tr>
    <td style="padding:0;margin:0;">
      <img src="이미지 경로2" alt="" style="display:block;vertical-align:top;border:none;" border="0">
    </td>
  </tr>
</table>
{% endhighlight %}
