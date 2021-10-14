# 使えそうなやつ

## 図形をアニメーションさせる
- transform: scale
- delayは0.3sくらいが一般的

## transition-timing-function
- ease
- ease-out
- ease-in-out

## その他色々
- animation-fill-mode
    - アニメーション後の位置に止める
- animation-iteration-count
    - 繰り返す数を指定できる
    - infiniteとすることでアニメーションを無限に繰り返す
- animation-direction: alternate;
    - 折り返してアニメーションが再生される
- @keyframesの100％の時に消えるアニメーション（メッセージポップアップなど）
    - 下にボタンなどのクリック要素があった場合、消えたポップアップの方が邪魔でクリックできない
        - pointer-events: none;を指定
            - すると、クリックイベントが発生しなくなり、下の要素がクリックできるようになる
