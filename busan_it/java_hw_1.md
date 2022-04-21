# Ch1

## 1분 복습

```java
package hello;

public class HelloJava {
    public static void main(String[] args) {
        // 화면에 문장을 출력함
        System.out.println("자바 프로그래밍 재미있다!");
    }
}
```

## 연습문제

- 프로그램(코드)을 기계가 이해할 수 있는 언어로 바꾸는 작업을 컴파일 이라고 합니다.
- 객체지향 언어는 자바나 C++와 같이 대상이 되는 객체를 기반으로 프로그램을 구현하는 언어입니다.
- 자바로 만든 프로그램은 자바 가상머신이 설치되오 있으면 운영체제와 상관없이 실행할 수 있습니다.
- 자바 개발을 위해 설치하는 자바 라이브러리를 JDK라고 합니다.
- 자바 프로그램이 실행되는 자바 실행 환경을 JRE라고 합니다.
- 두 번째 자바 프로그램을 만들어 보세요. 이클립스에서 'Hello, Java'대신 여러분의 이름을 출력해 보세요.

```java
package hello;

public class HelloJava {
    public static void main(String[] args) {
        // 화면에 문장을 출력함
        System.out.println("김보경");
    }
}
```

# Ch2

## 1분 복습

- 조금 전 예제에서 나이를 뜻하는 age로 변수 이름을 바꾸고 여러분의 나이를 대입해 보세요.

```java
package chapter2;

public class Variable2 {
    public static void main(String[] args) {
        int age;
        age = 26;
        System.out.println(age);
    }
}
```

- int형 변수 year에 값 2018을 대입하다를 의미하는 코드를 완성해 보세요.
  - `int year = 2018;`
- 다음 중 적합하지 않은 변수 이름을 모두 고르세요.
  - `2018`, `int`
- 다음 설명과 일치하는 자료형을 찾아 연결해 보세요.
  - `4 byte demical` - `int`
  - `2 byte string` - `char`
  - `8 byte demical` - `long`

- 조금 전 예제에서 `ch1 = 'Z'`, `ch2 = 38`, `ch3 = 97`로 바꾸어 대입하면 출력 결과가 어떻게 될까요?
  - `Z, 90, &, 97`
- MY_AGE 상수를 선언하고 출력하도록 코드를 완성해 보세요.

```java
public class Constant {
    public static void main(String[] args) {
        final int MY_AGE = 22;
        System.out.println(MY_AGE);
    }
}
```

- 문자형 연습 예제에서 형 변환을 사용했던 것을 기억하고 있나요? 주석 내용에 맞게 코드를 완성해 보세요.

```java
public class CharacterEx1 {
    public static void main(String[] args) {
        char ch1 = 'A';
        System.out.println((int)ch1);

        int ch2 = 67;
        System.out.println((char)ch2);
    }
}
```

## 연습문제

- 바이트 크기가 작은 자료형을 더 큰 자료형으로 대입하는 형 변환은 자동으로 이루어집니다.
  - `예`
- 실수를 정수형 변수에 대입하는 경우에 형 변환이 자동으로 이루어지고, 소수점 이하 부분만 없어집니다.
  - `아니오`
- 더 많은 실수를 표현하기 위해 가수부와 지수부로 비트를 나누어 표현하는 방식을 **부동 소수점 방식**이라고 합니다.
- 변수 두 개를 선언해서 10과 2.0을 대입하고 두 변수의 사칙 연산 결과를 정수로 출력해 보세요.

```java
public class Conversoin {
    public static void main(String[] args) {
        int x = 10;
        double y = 2.0;
        System.out.println(x + (int)y);
    }
}
```

- '글'이라는 한글 문자의 유니코드 값을 찾아서 char형으로 선언한 변수에 저장한 뒤 그 변수를 출력하여 확인해 보세요.

```java
public class CharacterEx2 {
    public static void main(String[] args) {
        char c = '글';
        System.out.println(c);
        System.out.println((int)c);
    }
}
```

# Ch3

## 1분 복습

- 조금 전에 작성한 예제 코드에 국어 점수를 의미하는 korScore 변수를 추가하고 여러분이 원하는 점수를 대입해 보세요. 그리고 국어 점수까지 포함한 총점(totalScore)과 평균 점수(avgScore)를 구해서 결과 값을 출력하도록 예제를 수정해 보세요.

```java
package operator;

public class OperationEx1 {
    public static void main(String[] args) {
        int mathScore = 90;
        int engScore = 70;
        int korScore = 100;
        
        int totalScore = mathScore + engScore + korScore;
        System.out.println(totalScore);
        
        double avgScore = totalScore / 3.0;
        System.out.println(avgScore);
    }
}
```

- 조금 전 실습에서 7행의 ++gameScore를 gameScore++로, 10행의 --gameScore를 gameScore--로 바꾼 후 출력해 보세요. 결과가 어떻게 나오나요?

```java
package operator;

public class OperationEx2 {
    public static void main(String[] args) {
        int gameScore = 150;

//        int lastScore1 = ++gameScore;
        int lastScore1 = gameScore++;
        System.out.println(lastScore1); // 150

//        int lastScore2 = --gameScore;
        int lastScore2 = gameScore--;
        System.out.println(lastScore2); // 151
    }
}
```

- 다음 예제에서 단락 회로 평가에 주의하여 출력 결과를 예상해 보세요.

```java
package operator;

public class OperationEx2 {
    public static void main(String[] args) {
        int num = 5;
        int i = 10;

        boolean value = ((num = num * 10) > 45) || ((i = i - 5) < 10);
        System.out.println(value); // true
        System.out.println(num); // 50
        System.out.println(i); // 10
    }
}
```


