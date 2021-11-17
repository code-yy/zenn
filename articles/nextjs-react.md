---
title: "[復習]React Props編"
emoji: "🌊"
type: "tech" # tech: 技術記事 / idea: アイデア
topics: [react,nextjs]
published: false
---

内容で間違ってる点や、変な箇所がございましたら、お知らせください。

## このブログを書く経緯
- チーム開発で、Reactに関してまだまだ理解できていないと感じた
- ただ復習するだけでは効率が悪いと感じ、ブログを書くことにした


### Props

- props は、親から渡ってきたデータ
- props を用いることで、動的にデータを出し分けすることができる
- props はいくつでも渡せる

```jsx
// 例)
// ../components/Header.jsx
export const Header = (props) => {
  return (
    <div>
      <h1>{props.title}</h1>
      <p>{props.description}</p>
    </div>
  );
};

// ./index.jsx
export default Home() => {
  return (
    <div>
      <Header title="Next.js" description="React のフレームワークです" />
    </div>
  );
};

// props.title = "Next.js"
// props.description = "React のフレームワークです"
```
