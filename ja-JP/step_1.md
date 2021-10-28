**時間の遅れた会話**: [中を見る](https://scratch.mit.edu/projects/591173089/editor){:target="_blank"}

<div class="scratch-preview">
  <iframe allowtransparency="true" width="485" height="402" src="https://scratch.mit.edu/projects/embed/591173089/?autostart=false" frameborder="0"></iframe>
</div>

緑の旗がクリックされてから数秒後にスクリプトを実行させることができます。

```blocks3
when [timer v] > [5] // 遅れを変更する
```

これは、会話やアニメーションを複数のスプライトと調整したり、長いスクリプトを整理したりするのに役立ちます。

タイマーを使う際に、`緑の旗が押されたとき`{:class="block3events"}にそれを`リセット`{:class="block3sensing"}することは、プロジェクトが開かれたときにタイマーが始まるのでよいアイデアです。

```blocks3
when flag clicked
reset timer
```

遅れを追加する別の方法は、 `待つ`{:class="block3control"}ブロックを使用することです。

```blocks3
when flag clicked
wait [5] seconds // 遅れを変更する
```

