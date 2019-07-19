---
layout: post
title: Apache Spark 소개
tags: [spark]
comments: true
---
#Spark Study (1) - Apache Spark 개요
[Apache Spark](http://spark.apache.org//)를 사용해오면서 느낀 건 Spark Application은 매우 간단한 코드로 구현이 가능하지만 Low Level에서 어떤 로직으로 동작하는지 이해하기 어려웠다.
따라서 Spark의 기능과 내부구조를 더 정확히 공부하여 정리하고자 블로그를 시작하게 되었다.

## Spark란?
Spark는 **범용 고속 분산 컴퓨팅 프레임워크**로 인메모리 데이터 프로세싱을 다양한 영역에 활용 가능하다.

## Spark 주요 특징
Spark 공식 홈페이지에서 소개하는 주요 특징은 아래와 같다.

| 주요 특징 | 설명 |
| :---- |:--- |
| Speed | 말 그대로 속도가 빠르다! Spark측의 주장에 따르면 Hadoop MR 대비 약 100배의 속도 향상이 있다고 한다. |
| Ease of Use | 데이터 프로세싱에 일반적으로 사용되는 Java, Scala, Python, R, SQL등의 언어를 활용해 어플리케이션 작성이 가능하다. | 
| Generality | SQL, 스트리밍, 머신러닝, 그래프 프로세싱 등 다양한 영역에서 활용 가능하다. 실제로 SQL과 스트리밍, 머신러닝은 활용 사례를 많이 보았으며 그래프의 경우는 아직 분야가 한정적인 듯 하다. |
| Runs Everywhere | Spark 단독으로도 실행이 가능하나 YARN, Mesos, Kubernetes 등 다양한 환경에서 동작한다고 한다. |






Here's a code chunk:

~~~
var foo = function(x) {
  return(x + 5);
}
foo(3)
~~~

And here is the same code with syntax highlighting:

```javascript
var foo = function(x) {
  return(x + 5);
}
foo(3)
```

And here is the same code yet again but with line numbers:

{% highlight javascript linenos %}
var foo = function(x) {
  return(x + 5);
}
foo(3)
{% endhighlight %}

## Boxes
You can add notification, warning and error boxes like this:

### Notification

{: .box-note}
**Note:** This is a notification box.

### Warning

{: .box-warning}
**Warning:** This is a warning box.

### Error

{: .box-error}
**Error:** This is an error box.
