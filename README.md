# ServerTest
for test 19-12-10

## 회원가입
userid, password, nickname을
Json형식으로 작성할 것

[POST] body/raw/
<pre>
{
  'userid':'gildong123',
  'password':'bimilbeonho486',
  'nickname':'길동무'
}
</pre>

### 성공
<pre>
{
  'message':'어서와요! 오실 줄 알고 모두들 기다렸어요!'
  'nickname':'길동무'
}
</pre>

### 실패
<pre>
{
  'message':'오류 : 일정시간 후 다시 시도해주십시오'
}
</pre>

## 로그인
userid, password

[POST] body/raw/
<pre>
  'userid':'gildong123',
  'password':'bimilbeonho486'
</pre>

### 성공
<pre>
{
  'message':'얼마나 기다렸다구요!'
}
</pre>

### 실패
<pre>
{
  'message':'로그인 실패'
}
</pre>
