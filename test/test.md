
<style>

  /* code要素の設定。バッククォーテーションで囲まれた要素に対する設定。 */
  .markdown-body code {
    font-family: 'Roboto Mono', menlo, monospace;
    font-size: 0.9em;
    line-height: 1em;
    color: #0177aa !important;
    background-color: transparent !important;
  }
  
  /* codeの前後に挿入される空白を消す */
  .markdown-body code::before,
  .markdown-body code::after { content: ""; }
  
  /* code block */
  .markdown-body pre code {
    color: black !important;
  }
  
  /* リンクの見た目 */
  .markdown-body a {
    color: inherit; /* 色は本文と同じ */
    text-decoration: underline dashed #BDBDBD 0.1em; /* 下線のスタイル */
    text-underline-offset: 0.3em; /* 下線の位置の調整 */
  }
  
  /* リンク要素の上にマウスが乗ったときの見た目 */
  .markdown-body a:hover {
    text-decoration: underline dashed #E080A0 0.1em;
    text-underline-offset: 0.3em;
  }
  
  /* 下線の設定。++で囲まれた要素につく下線のスタイルを設定する。 */
  ins {
    text-decoration: underline solid black 0.05em;
    text-underline-offset: 0.25em;
  }
  
  p {
    font-family: Roboto Condensed;
  }
  
  .markdown-body mark {
    padding: 0;
    background: linear-gradient(transparent 60%, #FDBF60 60%);
  }
  
</style>



# これはテストです。

このメモはテストです。GitHubとHackMDの同期を行うために作成しました。
