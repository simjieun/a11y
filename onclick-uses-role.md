# onclick-uses-role

상호작용 가능한 태그 `input`, `button`
상호작용 가능하지 않은 태그 `div`, `section`, `span`

<span onclick={fn} role="button"></span>
<span onclick={fn} aria-hidden="true"></span>

<button onClick={fn}></button>

<!-- X -->
<span onclick={fn}></span>