# Profin
![](./sample.png)

Profinは、小さなプロフィールページのテンプレートです。HTMLの編集のみで簡単にプロフィールを作成できます。

## 使い方

### プロフィール
```html
<div class="profile">
    <img src="./icon.webp">
    <span>名前(省略可)</span>
    <span>一言(省略可)</span>
</div>
```

### テキスト
```html
<div class="write">
    <h1>タイトル(省略可)</h1>
    <p>文章(省略可)</p>
</div>
```

### リンク
```html
<div class="links">
    <a href="リンク先">
        <span>タイトル</span>
        <p>説明</p>
    </a>

    <a href="https://example.com/">
        <span>Example</span>
        <p>example.com</p>
    </a>
</div>
```

### タイルリンク
```html
<div class="tile-links">
    <a href="リンク先">
        <img src="画像パス">
        <span>タイトル</span>
    </a>

    <a href="https://example.com/">
        <img src="./icon.png">
        <span>Example</span>
    </a>
</div>
```

### 埋め込み動画クラス
各動画共有サービスにより差があります。サービスの共有項目などにある「埋め込み」で指定されたコードに`class="embed-video"`を加えることで利用可能です。`width="000"`や`height="000"`のような物が含まれている場合は、それを削除してください。以下はYoutubeでの例です。

```html
<iframe class="embed-video" src="https://www.youtube-nocookie.com/embed/ywXQ9SqsaBQ" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" allowfullscreen></iframe>
```

## 変更履歴

### v1.0.0 / 2024-01-16
- プロフィールブロック追加
- テキストブロックを追加
- リンクブロックを追加

## v1.1.0 / 2024-01-19
- タイルリンクブロックを追加
- 埋め込み動画クラスを追加
- フッターのスタイルを調整
- その他スタイルの微調整
- `template.html`を作成