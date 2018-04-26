## Images
### Static Image Resources

<Image source={require('./my-icon.png')} />

use the @2x and @3x suffixes : @를 이용해서 이미지를 찾을 수 있다.

이름 충돌은 걱정하지 않아도 된다.
실제로 사용된이미지만 앱에 패키지에 포함됨.
이미지 추가 는 컴파일 하지 않아도 된다.
패키저는 이미지의 크기를 알고 있다.
npm 패키지를 통해 관리 할 수 있다.

### Static Non-Image Resources
.mp3, .wav, .mp4, .mov, .html and .pdf 등 오디오 비디오 관련된 것
패키지 관지라 구성을 통해 다른 형식의 파일도 지원 할 수 있다.
크기는 모르므로 절대 위치 지정을 해야한다.

### Images From Hybrid App's Res
하이브리드앱을 빌드 할 경우 번들 이미지를 사용 할 수 있다.

### Network Images
컴파일할떄 사용 할수 없고 동적으로 로드 한다.
이미지크기를 수동으로 만져줘야 한다.

### Uri Data Images
Restful API 로 인코딩된 이미지를 가져 올 수 있다.
매주 작고 동적인 이미지만 가능하다. (DB저장)

### Local Filesystem Images
CameraRoll을 참조하여 폰에 사진을 가져 올 수 있다.

## Animations
View, Text, Image, and ScrollView로 사용하지만 Animated.createAnimatedComponent() 로 만들어서 사용도 가능

## Accessibility
### Native App Accessibility (iOS and Android)
장애인이 앱에 액세스 할 수 있도록 해준다.
