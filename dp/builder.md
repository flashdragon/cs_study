# 빌더 패턴
## 장점
### 필요한 데이터만 설정할 수 있음
### 유연성을 확보할 수 있음
### 가독성을 높일 수 있음
### 변경 가능성을 최소화할 수 있음

## 예제
<pre>
<code>
User user = User.builder()
                .name("김용재")
                .age(27)
                .iq(127).build();
</code>
</pre>
