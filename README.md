# デジタルラグーンPythonスクール
このリポジトリにはPythonスクールの追加演習問題とその解答例を載せています。
適宜チャレンジしてみてください！

## 問題
1. 次のリストから、2の倍数のみを取り出して新しいリストを作成してください。  
`numbers = [1, 2, 3, 4, 5, 6, 7, 8, 9, 10]`

2. リストに”a”, ”b”, ”up”の3種類の文字列が入っているとします。  
このとき、自分で適当にリストを作成し、そのリストを順番に読み込んで、”a”であれば”パンチ”、”b”であれば”キック”、”up”であれば”ジャンプ”と表示しましょう。  
また可能であれば、リストの順番に応じて「1番目：パンチ」「2番目：キック」のように、n番目の情報も表示してみましょう。  

3. 5日間の売上がリストで `sales = [100, 120, 90, 150, 130]` となっているとします。  
このとき、当日の売上が前日から何%増えたか（または減少したか）を計算して表示しましょう。  
出力形式は「〇〇%増加」または「〇〇%減少」とし、また初日は出力せず2日目から5日目までを表示することにします。

4. 次のデータフレームを作成してnullがないことを確認し、Age, Scoreの平均を計算してください。
   
| Name     | Age | Score | Class |
|----------|-----|-------|-------|
| Alice    | 24  | 85    | A     |
| Bob      | 22  | 78    | A     |
| Charlie  | 23  | 92    | B     |
| David    | 19  | 70    | B     |

5. 4のデータフレームにおいて、Class = "A"のときの行のみを表示してください。
次に、Ageが20以上の行のみを表示してください。
最後に、ClassごとのScoreの平均、最大、最小を計算してください。

6. 以下のデータフレームを使用して、pandas の pivot_table を作成し、Product ごとの合計 Sales を計算してください。  

| Product | Region | Sales |
|---------|--------|-------|
| A       | East   | 100   |
| B       | West   | 200   |
| A       | West   | 150   |
| B       | East   | 300   |

7. 6のデータフレームにおいて、Regionのユニークな値とその数を出力してください。
また、Salesによって降順ソート、昇順ソートをそれぞれ実施してください。

8. 6のデータフレームに対して、以下のデータフレームを新たな行として下側に結合してください。  

| Product | Region | Sales |
|---------|--------|-------|
| C       | North  | 500   |

また、新たに次のリストを使って`shop_name = ["SHOP_X", "SHOP_Y", "SHOP_Y", "SHOP_X", "SHOP_Z"]`をshop列を作成してください。

9. 8で作成したデータフレームにおいて、列名を全て漢字で"商品", "地域", "売上", "店名"に変更してください。  
最後に"地域"列を削除してください。

10. 9で作成したデータフレームに対し、商品列をキーにして、以下のデータフレームをleft joinしてください。

| 商品     | 商品名 | 
|---------|-------|
| A       | Pen   |
| B       | Eraser|

また、inner joinも行い、結果を比較してください。



