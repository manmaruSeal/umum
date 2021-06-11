# umum
### RentalVideo
#### レンタルビデオの金額と延滞料金を計算するシステム
・新作か旧作を選んで、借りる日と返却日を入力して、レンタル料金と延滞料金を表示する<br>
・1週間以内に返却した場合は新作1000円、旧作500円<br>
・1週間を超えたら1日あたりレンタル料金の1割の延滞料金が追加される<br>
・入力チェックとして、全ての項目が入力されていること、日付が逆転していないこと、存在する日付が入力されていることをチェックしてエラーメッセージを表示する<br>
（例：新作借りる日1/1、返却日1/10、レンタル料金1000円、延滞料金300円）<br>

### MatchingGame
#### 絵合わせゲーム(MicroSoftチュートリアル)
・起動すると開始するストップウォッチを作成する。<br>
・アイコンのオブジェクトを Listに格納する。<br>
・ループを使用して、リスト内のアイコンにランダムに値を付与、アイコンの値を見えなくする。<br>
・アイコンのクリックイベントを作成する。<br>
・public変数を使用してアイコン状態を保持し、クリックされた2つアイコンの値が同じ場合はアイコンの値を可視化、異なる場合は見えなくする。<br>
・リスト内のアイコンをループで確認し、全て可視化されていたら、クリアメッセージ、タイムを表示する。
