# mouse-events-have-key-events

`onMouseOver`, `onMouseOut`을 사용할 때는
`onFocus`, `onBlur`을 같이 사용해줘야 웹접근성에 좋다.

<div onMouseOver={fn} onFocus={focusFn}>

<div onMouseOut={fn} onBlur={blurFn}>