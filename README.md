# 어플 종류

하이브리드 앱Permalink
웹 뷰를 감싸고 있는 웹사이트
HTML, CSS, JS
웹 뷰 - 브라우저의 윈도우다. 그라나 네이게이션이 없다!

HTML, CSS, JS 이 3가지를 가지고 웹 뷰를 감싼후 그걸 스토어로 보내는 거다. 예시
내가 모바일 폰에서 보는건 구글 크롬 윈도우!!
단 네이게이션 바가 없는 형태
🤗 추가사항
네이티브로 만들되, 그 앱에 브라우저 창을 둬서 일부 또는 대부분의 기능을 웹 형태로 제공하는 거야
보다 쉽게 말하자면, 안드로이드나 iOS 전용으로 각각 스토어에 올리는 네이티브 앱을 만드는데 그 앱 안에 크롬이나 사파리 같은 브라우저처럼 웹사이트를 보여주는 창을 하나 넣는거야

둘다 웹뷰라고 부른다!!! 웹사이트에서 구현할수 없는 레벨은 네이티브 레벨에서 처리하도록 하는거야

흔히 볼수 있는 예 > 네이버 앱🐱‍💻

하이브리드 앱 장점Permalink
네이티브 앱에 대한 지식이 필요 없다.


하이브리드 앱 단점Permalink
UI를 한땀한땀 다 짜야한다
버튼, 타이틀, 네이게이션 등등 말그대로 웹사이트를 0에서 만드는 것

폰의 강력한 기능을 활용하지 못한다.
하드코어한 비디오 프로세싱 JS로 모두 짜는 건 어렵다. 결국 만드는 건 웹사이트

하이브리드 앱을 만들고 싶다면, apache cordova & phonegap를 살펴보자

이 두가지는 HTML, 웹뷰를 감싸는 기능을 제공


크로스플랫폼 앱Permalink
네이티브 코드가 아닌걸로 코딩을 한 후, 나중에 ios/android가 이해할 수 있는 코드로 변환된다.
예를 들어 리액트 네이티브, 일단 리액트로 코딩을 하고 이는 자바스크립트 코드로 컴파일 되고 이후 ios/android가 이를 각자의 자바스크립트 엔진으로 실행시키는 것

Flutter의 경우. Dart코드로 쓰고 이는 C,C++로 컴파일 된다.
결국 이는 android/ios 둘다 이해할 수 있는 언어!!!🎈
Xamarin의 경우 C#으로 작성하고 이는 ios/android 둘다 이해하는 intermediate 언어로 컴파일 된다
보다시피 네이티브 코드로 작성하진 않지만, 나중에는 변환 된다

크로스플랫폼 앱 장점Permalink
코드를 한번만 작성하면 이를 2개의 플랫폼에서 확인이 가능하다.
시간을 아낄 수 있다.
다양한 배경의 개발자를 끌어모은다.
백엔드 개발자, Java 개발자
덕분에 다양한 형태의 라이브러리, 튜토리얼, 커뮤니티가 발전하고 있다.

크로스플랫폼 앱 단점Permalink
여전히 네이티브가 아니다.
퍼포먼스 이슈가 생길 수 있다.(퍼포먼스가 중요하면) 속도가 느려질 수 있다. ㅜㅜ
속도가 느려지는 이유는 여전히 변환하는 프로세스가 있고 결국 폰의 파워 에 미치지 못할 수 있다. 필요한 곳에 적절하게 쓰이면, 베스트 솔루션이다. 인스타그램 일부는 리액트 네이티브로 돌아가고 있다.

네이티브 앱Permalink
말그래도 android, ios 코드를 쓰는 거야
ios라면 swift를 배우고, android는 java 혹은 kotlin이 필요하다
네이티브 앱 장점Permalink
폰이 갖고있는 파워만큼 파워를 갖게 된다.
가능한 어떠한 API든 쓸 수 있다. 이유는 내가 쓴 코드와 휴대폰 사이에 중간단계가 없기 때문이다.

네이티브 앱 단점Permalink
2개의 플랫폼 언어를 배워야한다.
위의 예시 플러스 ios(xcode) android(android studio) 도 배워야 되

집중하는 것이 퍼포먼스이면 네이티브는 좋은 선택이다!!🎉

예를 들어 내 얼굴에 3D 마스크를 입히는 앱
