# Hello World

テスト文書です。

Hello!

大きさの書き方には迷いがある。

相対指定がいいと思うので `font-size: larger;` を使おうかと思うのだけど、一つだけでは大きさが足りないのでネストする。

[date.hta#L17](https://github.com/hs9587/date_calender/blob/20191027-0/date.hta#L17)-L29  
```html
   <span style="font-size: larger;">
   <span style="font-size: larger;">
   <span style="font-size: larger;">
   <span style="font-size: larger;">
   <span style="font-size: larger;">
   <span style="font-size: larger;">
     <span id="view_date">d</span>
   </span>
   </span>
   </span>
   </span>
   </span>
   </span>
```
ちょっと無様。
なら数字一つで指定すると `font-size: 7em;` か  
