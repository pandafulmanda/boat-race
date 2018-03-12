## クラッシュ！

現時点では、ボートは木の障害物を通りぬけることができてしまいます！直してみましょう。

+ ボートのコスチュームとして、普通のコスチュームとクラッシュしたときのコスチュームが必要になります。「boat」コスチュームを複製して一方を「normal」に、もう一方を「hit」という名前にしてください。

+ 「hit」コスチュームをクリックし、「選択」ツールを使ってボートのいろいろな部分をつまんで、動かしたり回したりしてボートがこわれているようにしてください。
    
    ![screenshot](images/boat-hit-costume.png)

+ これからボートにコードを追加して、茶色の木の部分に触れるとクラッシュして壊れるようにしましょう。

\--- hints \--- \--- hint \--- ボートの`ずっと`ループ内にボートがクラッシュするかチェックしつづけるコードを追加するします。 `もし`ボートが木の茶色に`触れた`ら`コスチュームを「hit」に`して`Noooooo! と2秒言`い、`コスチュームを「normal」に戻`します。 最後に、`上向き`にして`開始位置に移動`します。 \--- /hint \--- \--- hint \--- 必要になるコードブロックはこちらです。 ![screenshot](images/boat-hit-blocks.png) \--- /hint \--- \--- hint \--- コードの見本はこちらです。 ![screenshot](images/boat-hit-code.png) \--- /hint \--- \--- /hints \---

+ ボートが常に「normal」からスタートするように確認する必要があります。
    
    木の障害物を通りぬけようとすると、ボートはクラッシュしスタートへもどります。
    
    ![screenshot](images/boat-crash.png)