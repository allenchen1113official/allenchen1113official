+++ 
draft = false
date = 2023-04-02T23:33:52+08:00
title = "每天5億則推文twitter之推薦演算法3個秘密"
description = "這是twitter之推薦演算法3個秘密"
slug = "twitter-reco-algo"
authors = "AllenChen"
tags = ["twitter","Recommendation Algorithm"]
categories = ["twitter","科技"]
externalLink = ""
series = []
+++

![image](/images/post/A-rabbit-looking-iPhone-and-open-twitter-App-with-big-blue-eyes-with-Van-Gogh-style.jpeg)


Twitter Recommendation Algorithm 於2023/3/31開源 [@GitHub](https://github.com/twitter/the-algorithm)

三個秘密：

1.使用程式語言排行：第1名 Scala 53.8% ，第2名 Java 29.7% 第3名 Starlark
6.3%。
![image](/images/post/twitter_algo_lang.png)

2.排名參數(權重值)：按讚(+30)，轉推(+20)，回復(+1)
Source from: [Aakash Gupta's tweet](https://twitter.com/aakashg0/status/1641976892885540865?fbclid=IwAR1_JFXU_7sl8IhFEbBYeKDPZ4N91EJUMu0KOsam6wjMX093yhzc4Sv9nKI )

3.使用GraphJet，一種圖形處理引擎，維護用戶和推文之間的實時交互Graph。
Source from:[Twitter's blog](https://blog.twitter.com/engineering/en_us/topics/open-source/2023/twitter-recommendation-algorithm)

<p><span class="nowrap"><span class="emojify">🙈</span> <code>:see_no_evil:</code></span>  <span class="nowrap"><span class="emojify">🙉</span> <code>:hear_no_evil:</code></span>  <span class="nowrap"><span class="emojify">🙊</span> <code>:speak_no_evil:</code></span></p>
<br>
    

{{< css.inline >}}
<style>
.emojify {
	font-family: Apple Color Emoji, Segoe UI Emoji, NotoColorEmoji, Segoe UI Symbol, Android Emoji, EmojiSymbols;
	font-size: 2rem;
	vertical-align: middle;
}
@media screen and (max-width:650px) {
  .nowrap {
    display: block;
    margin: 25px 0;
  }
}
</style>
{{< /css.inline >}}
