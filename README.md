# mysite

필드를 특정 메소드에 따라 조회할떄는 언더스코어 2개를 붙혀서 조회한다.

```shell
>>> Question.objects.filter(question_text__startswith='What')
<QuerySet [<Question: what the fuck!!!!!!>]>
```
