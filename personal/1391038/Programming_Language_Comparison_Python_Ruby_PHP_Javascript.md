Page : YongJang.github.io

#Python
Python은 변수를 선언할 때 변수가 어떤 자료형인지 명시할 필요가 없다. name="YongJang" num=3 과 같이 선언이 가능하다. 또한 문장 뒤에 굳이 세미콜론(;)을 붙이지 않아도 된다. if 문을 사용할 때 괄호를 꼭 사용하지 않아도 되며 if문의 실행문인 중괄호{} 대신 콜론(:)과 탭을 이용하여 들여쓰기를 하고 그에 따라 문장의 상하관계를 고려한다.
Python은 다른 언어에 비해 가독성이 높다고 생각한다. 언어의 구조가 마치 사람의 언어와 흡사하다는 느낌을 준다. 문장의 구조 역시도 그렇지만 문법 적인 부분에서도 다른 언어에서 사용되는 '그리고'와 '또는'을 && || 대신 'and' 'or'과 같이 표시한다. & 와 |는 비트 연산을 할 때 사용이 된다.
위와 같은 이유에서 Python으로 코딩된 프로그램은 굉장히 간결하다는 느낌을 준다. 특히 Python은 배열이나 스트링을 조건에 따라 출력할 때 다른 언어에서 같은 작업을 할 때 보다 간단하게 출력이 가능하다. 이외에도 클래스 선언이나 메소드를 생성할 때 다른 언어들과는 구조가 꽤 다르다.
Python에서 변수에 자료형을 명시하지 않는 것처럼 Python에서는 변수들의 자료형 변환이 비교적 자유롭다는 느낌을 받는다. 개인적인 생각이지만 다른 언어에 비해 변수 형태의 변환이나 캐스팅이 좀 더 간단한 명령만으로도 수행이 가능한것 같다.
마지막으로 Python은 배열의 효율성이 높은것 같다. 배열을 저장하는 방법부터 배열에 저장된 값을 불러 오는 것까지 간단한 명령만으로 수행이 가능하다. 특히 dictionary라는 기능이 굉장히 멋있었다. 한 가지 변수 안에 key와 value 값을 입력하는데 이를 선언하고나면 변수 내의 데이터에 item, key, value값을 통해 간단히 접근이 가능하다.

#PHP
PHP역시도 변수를 선언할 때 자료형을 명시하지는 않는다. 대신에 PHP에서는 변수 명 앞에 $표시를 하면서 이 단어가 변수임을 명시하는것 같다.
우선 PHP를 하면서 가장 크게 느꼈던 점은 C언와 비슷하다는 점이다. 누구나 C언어를 배워본 사람이라면 PHP를 금방 습득할 수 있을것 같았다.
PHP는 배열의 수정이 굉장히 간편하다고 느꼈다. unset 명령어와 array_push와 같이 배열 안의 데이터를 지우고 데이터를 삽입 하는것이 다른 언어들 보다 간편다고 생각했다.
또한 배열을 정렬할 때에도 sort와 같은 명령어 하나만으로 충분하고 역으로 정렬하는 것도 rsort라는 명령어 하나만으로 충분히 수행이 가능하다.
가장 눈에 들어왔던 것이 join 명령을 통해서 배열의 요소를 나열할 때 요소들 사이에 특정한 문자열을 넣을 수 있다는 점이었다. 사실 배열의 많은 기능들은 다른 언어로도 구현이 가능하긴 하지만 개인적으로 PHP에서 제일 이해가 쉽게 됐던것 같다.
PHP는 자바 스크립트처럼 css 스타일 시트를 코드와 함께 사용하고 웹을 위해 최적화된 언어라는 느낌이 들었다. 또한 PHP는 간결한 문장만으로도 다른 언어에서 많은 문장을 요구하는 프로그램을 짤 수 있기 때문에 굉장히 효율적이라고 생각이 들었다.

#Ruby
Ruby 역시 다른 언어 처럼 변수를 선언할 때 자료형을 명시하지 않아도 된다. Ruby에도 다른 언어처럼 if문이 있지만 true와 false를 구분할 때는 unless문을 사용해도 충분히 구현이 가능하다는 장점이 있다.
항상 조건문이나 반복문에 end와 같이 끝나는 지점을 명시해 주기 때문에 코드를 해석하는데 좀 편리하다는 생각이 들었다. 
다른 언어들 처럼 문자열 변수들을 조작하는데 여러가지 기능이 있다.gets.chomp를 통해 문자열을 읽어 오기도 쉽고, "문자열".length .reverse .upcase .downcase .split와 같이 문자열 메소드를 사용하면 바로 그 결과 값을 볼 수 있다.
Ruby를 하면서 특별히 느꼈던 점은 Ruby는 코멘트 방식이 다른 언어와 다르게 매우 신기하다. 주석을 달 때 #을 써도 되지만 여러 줄을 주석으로 할 때 =begin과 =end를 사용한다.
Ruby는 약간 반복문이 신기하다. 특별히 괄호를 넣지 않고 while문이나 for, foreach문으로 시작하여 end를 사용하여 끝낸다. until과 같이 특정 조건을 만족할 때 까지 반복하는 반복문도 있다. 특히 1부터 10까지를 1...10으로 표현하는게 재미있다.
Ruby는 다른 객체 지향 언어들처럼 여러 데이터들을 객체로서 활용하기 쉽도록 되어있다. 다른 객체 지향 언어들과 구성 방식에서 약간 차이가 있지만 전체적으로 비슷한 역할을 수행하게끔 되어있는것 같다.

#JavaScript
JavaScript도 다른 언어들 처럼 변수를 선언할 때 변수의 자료형을 명시하지 않고 변수임을 나타내는 var만 입력해주면 된다. 그렇다고 해서 데이터 타입이 없는 것은 아니지만 이를 이를 명시하는 것이 중요한 Java에 비해 데이터 형식이 자유롭다는 느낌을 받는다.
confirm과 prompt 명령 처럼 사용자로 부터 데이터를 입력 받는 것이 굉장히 편리하다. 또한 console을 이용해서 데이터를 출력하는것되 굉장히 간편하다.
전체적으로 라이브러리 메소드들이 Java와 비슷하다고 생각한다. 또한 문법적인 구조들도 비슷해서 JavaScript를 배울 때 이러한 점들이 언어를 습득하는데 도움이 되는것 같다.
배열에 대한 기능이 강력한것 같다. 배열이 비어 있어도 배열안에 데이터를 넣는것이 자유롭고 자료형이 다른 데이터들도 같은 배열에 넣을 수 있다. 또한 배열안에 배열을 넣고 또 그 배열을 반복문을 통해 출력하는데서 큰 장점을 갖고 있다.
위와 같은 특징들 덕분에 자료를 배열에서 불러오는 것이 편리한것 같다. 배열에서 원하는 값을 얻고 싶다면 그 값이 저장되어 있는 위치를 알면 쉽게 자료를 찾을 수 있다. 만약 인스턴스가 무수히 많다면 이 기능은 반복문을 통해 더 큰 효율성을 가질것 같다.

