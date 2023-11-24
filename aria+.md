# aria-*

`aria-required`

required true 이면 스크린리더 사용자에게 해당 요소가 필수적으로 입력해야한다고 알려주는거다

<input type"text" name="username" id="username" aria-requried="true" />

`aria-describedby`

추가 설명을 제공해준다.

<form>
<labe for="fname">First name</label>
<input name="" type="text" id="fname" aria-describedby="int2">
<p id="int2">A bit of instructions for this field linked with aria-describedby.</p>
</form>

`aria-label`

해당 요소에 대한 설명을 제공해준다.

<button aria-label="send email">send</button>

`aria-expanded`

현재 탭 패널이 펼쳐져있는지 아니면 닫혀있는지를 나타낸다.

<div role="tabpanel" aria-expanded="true">

`aria-pressed`

해당 요소가(토글같은요소) 현재 눌려 있는지 아니면 눌려있지 않은 상태인지를 나타냄
 
<button aria-pressed="true">