# img-uses-alt

`img` `alt` 속성을 이용해서 이미지가 나오지 않을때 이미지 설명을 해준다.

['image', 'picture', 'photo']

<img src="src" alt="logo">

# presentation 은 none이랑 같은 의미한다. 즉, 시맨틱한 의미를 remove 해주는거다.
<img src="src" alt="" role="presentation">

<!-- X -->
<img src="src">
<img src="src" alt="">