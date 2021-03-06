---
layout: default
title:  "首页"
permalink: /
---

## 基础知识

* [银行业基础知识点](./post/basic_sense/bank_common_sense.html)
* [证券业基础知识点](./post/basic_sense/security_common_sense.html)
* [基金业基础知识点](./post/basic_sense/fund_common_sense.html)
* [期货业基础知识点](./post/basic_sense/future_common_sense.html)


* [如何简单明了解释升水和贴水的含义？](./post/basic_sense/35163415.html)
* [期货升水和期货贴水分别是什么？](./post/basic_sense/77147031.html)
* [期货贴水的真正原因剖析 - 贴水系列1](./post/basic_sense/164707033.html)
* [商品ETF投资中的滚动收益是怎么实现的？——贴水系列2](./post/basic_sense/164808202.html)
* [滚动收益最大化策略简示 – 贴水系列 4](./post/basic_sense/166112158.html)

---

## 行业新闻

* [支付宝、微信支付收款码禁止商用系误读](./post/news/202111262194624470.html)
* [明年3月1日起 微信、支付宝个人静态收款码不能用于经营收款](./post/news/5697572.html)
* [银保监会1号罚单！农行“六宗罪”被罚420万](./post/news/doc-ikftssap2262605.html)
* [银保监会依法查处中国银行“原油宝”产品风险事件](./post/news/c_1126826000.html)
* [中行“原油宝”案二审上诉被驳回 维持原判](./post/news/c_1127092394.html)
* [持股比例突破限制 多只基金“踩红线”](./post/news/202108242060204595.html)

---

## 行业规定

* [中国人民银行关于加强支付受理终端及相关业务管理的通知（银发〔2021〕259号）](./post/rules/4359567.html)

### 测试区

<ul>
  {% for post in site.posts %}
    <li>
      <a href="{{ post.url }}">{{ post.title }}</a>
    </li>
  {% endfor %}
</ul>

{% for tag in site.tags %}
  <h3>{{ tag[0] }}</h3>
  <ul>
    {% for post in tag[1] %}
      <li><a href="{{ post.url }}">{{ post.title }}</a></li>
    {% endfor %}
  </ul>
  ---
{% endfor %}
