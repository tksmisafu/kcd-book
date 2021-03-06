---
description: 閱讀 這本書籍的心得就是：很硬地～～～
---

# 第十章節：緊急修復

### 第十章節：緊急修復 P.266~

{% tabs %}
{% tab title="理想" %}
```
遇到緊急情況需要修復時，最重要、需要謹記在心的是：任何情況下，都不能破壞流程。
即使面對緊急修復，也要用相同的建置、部署、測試和發佈流程，與一般例行程式上版流程沒有任何差異。
為何這麼說、這麼要求：因為太多案例將修復版本直接放入生產環境中，並因此產生了一個未受控制的版本！
```
{% endtab %}

{% tab title="現實" %}
```text
火都在燒了，顧不了這麼多了～
老闆在催了，麻煩不要堅持這麼多了，好嗎？
總之，我先解決問題再說！
```
{% endtab %}

{% tab title="沒照流程的下場" %}
```text
通常緊急修復，沒有經過適當的測試。
做了程式上的修補但未達修復問題目的，反而引發更多(複雜\嚴重)問題。
沒進入版本控制流程＝＝未記錄在案，反而讓環境(團隊)陷入某種未知狀態。
團隊很難重現問題，造成管理漏洞的情況下進而破壞後續部署(團隊)流程。
```
{% endtab %}

{% tab title="書中寓意" %}
#### 讓每次緊急修復都走完標準部署流程，同時也是另一個應該維持短週期的原因。（迭代）
{% endtab %}

{% tab title="最近心得" %}
```text
流程很重要，但解決問題確實更重要。
流程是僵化的，但也要有脫離流程的備案與堅強。
可解決問題，也可事後追加版本回到版本控制範疇中。
```
{% endtab %}
{% endtabs %}

#### 緊急修復的必要性、考量點：

```text
受到bug影響的人數、範圍
此bug是否經常發生
發生bug後，對使用者影響多大
可否透過還原前一個良好版本，暫時脫離當下問題。
```

#### 面對生產環境中的缺陷時，應該考慮的一些因素：

```text
別深夜自己搞，要有相對關係的部門、夥伴一起參與。
確保能夠～完成測試的緊急修復流程。
避免繞過標準流程 “除非” “除非” “除非” 在極端情況下。
修復成本：有時候回復上個版本，比起人力介入排查問題、解決問題更有效率。
做些分析工作，找到最佳的解決方案(硬實力)。
想想～如果修復過程中，資料遺失了、面對到整合問題、面對到協調問題，當下能夠解決缺陷嗎？
```

{% hint style="info" %}
CD書籍：page 266 ~ 267
{% endhint %}



