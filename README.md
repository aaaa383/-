# -
# データサイエンティスト養成講座　Jリーグコンペ

## 11月9日  
吉岡さんの提出ファイル  
ファイル名:yoshioka_Linear_Regression  
スコア:RMSE= 3,305.1153812  
[yoshioka_Linear_Regression.ipynb](/モデル格納ファイル/yoshioka_Linear_Regression.ipynb)  
[fifa2014mem.csv](/データセット/fifa2014mem.csv)  
[player_prefecture.csv](/データセット/player_prefecture.csv)  

### 工夫点
・説明変数ごとのyの平均や合計のランキングを見てランキング列を作成。  
・平日に試合が行われている試合を'平日'とした曜日列の作成。  
・テレビの放送数列の作成。  
・https://todo-ran.com/t/kiji/19639  　
から都道府県別の25歳以上のサッカー人口のcsvを作成して利用。  

## 11月10日
傍示の提出ファイル  
ファイル名:J1とJ2でモデル分割.ipynb  
スコア:RMSE = 3324.3960363  
[J1とJ2でモデル分割.ipynb](/モデル格納ファイル/J1とJ2でモデル分割.ipynb)

### 工夫点
・J1とJ2でそれぞれ異なるモデルを作成  
・開催節、開催日時、天気、屋内ダミーを作成  
・テレビ局の情報を抽出  
・都道府県を抽出  


## 11月12日
吉岡さんの提出ファイル  
ファイル名:yoshioka_XGBoost_Regressor_2986  
スコア:RMSE=2,986.8891764  
[yoshioka_XGBoost_Regressor_2986.ipynb](/モデル格納ファイル/yoshioka_XGBoost_Regressor_2986.ipynb)

### 工夫点  
・説明変数ごとのyの平均や合計のランキングを見てランキング列を作成。  
・平日に試合が行われている試合を'平日'とした曜日列の作成。  
・テレビの放送数列の作成。  
・'away'をワンホットエンコーディングではなく、yの値でランキング化した列として追加しました。      
・https://todo-ran.com/t/kiji/19639  から都道府県別の25歳以上のサッカー人口のcsvを作成して利用。  
・XGBoostのモデルを作成  
・私がLinear Regressionで作成した特徴量の使いまわし  
・上記に加えて、各スタジアムのcapaに対する収容人数の比率変数を作成  
・stadiumが陸上競技場かそうでないかの変数を作成  

## 11月12日
作成したデータセット  
ファイル名:train_new_20201120, test_new_20201120  
[train_new_20201124](/データセット/train_new_20201124.csv)  
[test_new_20201120](/データセット/test_new_20201120.csv)  
緯度経度からそれぞれの本拠地の距離を計算したファイルになります。

## 11月25日
吉岡さんの提出ファイル   
ファイル名:yoshioka_CatBoost_Regressor_2745,yoshioka_Linear_Regression_2960,yoshioka_XGBoost_Regressor_2957   
[yoshioka_CatBoost_Regressor_2745.ipynb](/モデル格納ファイル/yoshioka_CatBoost_Regressor_2745.ipynb)  
[yoshioka_Linear_Regression_2960](/モデル格納ファイル/yoshioka_Linear_Regression_2960.ipynb)  
[yoshioka_XGBoost_Regressor_2957](/モデル格納ファイル/yoshioka_XGBoost_Regressor_2957.ipynb)  
