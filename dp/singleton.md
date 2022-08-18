# 싱글톤 패턴
### 객체의 인스턴스가 오직 1개만 생성되는 패턴을 의미한다.

## 사용하는 이유
### 메모리 측면에서 이점이 있다
### 데이터 공유가 쉽다

## 문제점
### 코드 자체가 많이 필요하다
### 테스트하기 어렵다
### 클라이언트가 구체 클래스에 의존하게 된다

## 예제
<pre>
<code>
public class Singleton {

    private static Singleton instance = new Singleton();
    
    private Singleton() {
        // 생성자는 외부에서 호출못하게 private 으로 지정해야 한다.
    }

    public static Singleton getInstance() {
        return instance;
    }

    public void say() {
        System.out.println("hi, there");
    }
}
</code>
</pre>
