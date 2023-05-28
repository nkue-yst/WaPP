# 和++（日本語プログラミング用ライブラリ）
 <img src="https://github.com/nkue-yst/WaPP/assets/39930174/34e2c7d4-ea40-42e8-97af-e2c7d98d2cc8" width="300">

こちらは、C++のプログラムを日本語で書くためのヘッダオンリライブラリです。  
`int` や `return` などの予約語や、 `std::cout` などの関数を日本語に置き換えることができるようになります。

## 使い方
ヘッダファイルの `WaPP.h` をインクルードしてください。

## C++ - 日本語 キーワード等対応表
### 予約語
| C++       | 日本語             |
| --------- | ------------------ |
| bool      | 真偽値             |
| char      | 文字               |
| double    | 倍精度浮動小数点数 |
| false     | 偽                 |
| float     | 浮動小数点数       |
| int       | 整数               |
| long      | 長整数             |
| short     | 短整数             |
| true      | 真                 |
| void      | 無し               |
|           |                    |
| class     | クラス             |
| const     | 定数               |
| constexpr | 定数式             |
| enum      | 列挙               |
| signed    | 符号あり           |
| static    | 静的               |
| struct    | 構造体             |
| union     | 共用体             |
| unsigned  | 符号なし           |
|           |                    |
| this      | これ               |
| ->        | の                 |
| =         | 代入する           |
| >         | 大なり             |
| <         | 小なり             |
|           |                    |
| new       | 生成               |
| delete    | 削除               |
|           |                    |
| private   | 非公開             |
| public    | 公開               |
|           |                    |
| break     | 中断               |
| case      | 場合               |
| continue  | 続ける             |
| default   | 既定               |
| do        | 行う               |
| else      | そうでなければ     |
| for       | 繰り返す           |
| if        | もし               |
| sizeof    | サイズ             |
| switch    | 選択               |
| while     | その間             |
| return    | 戻り値             |

### 標準関数
| C++            | 日本語                         | 
| -------------- | ------------------------------ | 
| std::cin       | 標準入力                       | 
| std::cout      | 標準出力                       | 
| std::cerr      | 標準エラー出力                 |
| std::endl      | 行終端                         |
|                |                                |
| std::stoi      | 文字列から整数へ               |
| std::stod      | 文字列から倍精度浮動小数点数へ |
| std::to_string | 整数から文字列へ               |
|                |                                |
| std::sqrt      | 平方根                         |
| std::pow       | べき乗                         |
| std::sin       | 正弦                           |
| std::cos       | 余弦                           |
| std::tan       | 正接                           |
| std::log       | 自然対数                       |
| std::exp       | 指数関数                       |
| std::abs       | 絶対値                         |
| std::max       | 最大値                         |
| std::min       | 最小値                         |
