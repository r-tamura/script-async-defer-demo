# scriptタグの'async'属性と'defer'属性比較

| | ロード | 実行 |
| ---- | :---- | :---- |
| \<script\> | ブロック | 即実行 |
| \<script async \> | 並列 | 即実行 |
| \<script defer\> | 並列 | DOMContentLoadedの直前 |
