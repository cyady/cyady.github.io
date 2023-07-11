# 이미지 업로드를 테스트(1.03)

---

마크다운 문서에 이미지를 삽입하는 방법에는 두가지가 있는 것 같다.

1. 마크다운형식

2. html의 태그형식

> 마크다운 형식의 이미지 삽입 방식 
> 
> ```markdown
> ![이미지 이름](){: width="" height=""}
> //px단위는 붙이거나 생략 가능, %를 붙여 비율로 조절해도 됨
> //%단위는 이미지의 크기가 아니라 차지할 수 있는 전체범위가 기준인것으로 보
> ```

> html 형식의 이미지 삽입 방식
> 
> ```html
> <img src="이미지 URL">
> <img src="이미지 URL" width="가로 사이즈" height="세로 사이즈">
> ```

> MarkText 에디터
> 명령어를 입력하려고 할때 자동으로 이미지를 넣을 수 있도록 안내함
> 
> \!\[이미지 이름\]\(
> 
> \<img\>

상대경로

![](../images/2023-07-05-image_test/bedbd0dffd2ea6623bc1e5373ee765c512ac509b.png)

copy img

![](C:\Users\cyady\Desktop\project\github_blog\cyady.github.io\images\2023-07-05-image_test\bedbd0dffd2ea6623bc1e5373ee765c512ac509b.png)~~~~

상대경로

![](../images/2023-07-05-image_test/bedbd0dffd2ea6623bc1e5373ee765c512ac509b.png)

테스트 결과 : 이미지는 상대경로만 사용해야하는 것 같다. 아마 C드라이브가 아니라 깃 위에서 파일을 탐색해야하기 때문인 것 같다.