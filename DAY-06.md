## Improving User Experience
- 웹 배경에서 오는 고려하지 않는 많은 세부 사항에 대해서 알아보는 시간.

### Configure text inputs
- 첫 번째 필드에 자동 포커싱
- placeholder 사용
- 자동 대문자 사용 및 자동 교정 사용 or 사용 안함 설정
- 키보드 타입 ( email , numeric )
- 돌아 가기 버튼이 다음 입력란에 초점을 맞추거나 submit form 되는지

### Manage layout when keyboard is visible
- 화면을 가리는 티보드가 노출 될 경우 다음을 사용하여 여전이 엑셀스 할 수 있는지 확인

### Make tappable areas larger
- 버튼을 누를때 정확이 안 눌러지는데 44x44 사이즈 이상인지 확인 해야함.
- padding, minWidth, minHeight 등을 이용하여 영역을 늘릴 수 있다.

### Use Android Ripple
- Android API 21+는 디자인 리플을 사용하여 터치 피드백 제공 한다.
- iOS 나 Android API < 21 에서는 작동하지 않으므로 주의 해야한다.
- iOS 는 다른 구성요소를 통해 사용 가능

### Screen orientation lock
- 세로, 가로 고정 모드 지원

## Timers
- setTimeout, clearTimeout
- setInterval, clearInterval
- setImmediate, clearImmediate
- requestAnimationFrame, cancelAnimationFrame

### InteractionManager
- 부드로운 애니메이션
- requestAnimationFrame : 시간이 지남에 따라 애니메이션
- setImmediate / setTimeout / setInterval : 지연 애니메이션
- runAfterInteractions : 터치가 종료 되거나 취소될떄 콜백 

### TimerMixin
- 구성 요소가 마운트 해제 된 후 타이머가 실행 되는점 유의
- setTimeout -> this.setTimeout 로 사용


