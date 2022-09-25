# Laratter 

TwitterのようなSNSWebアプリケーションです


## 授業で実装された機能

ユーザー認証機能
Indexページ（すべてのツイートを表示）
Createページ（新しいツイートを作成）
Timelineページ（自身とフォロワーが作成したツイートのみ表示）
Searchページ（ツイート内容、タイトル、ユーザー名からツイートを検索）
Favorite機能（Favoriteされた回数を表示する）
Follow機能（そのツイートをしたユーザーをフォローし、そのユーザーのツイートをTimelineで表示する）
Edit機能（そのツイートを編集し、もとのツイートを更新する）


## 課題として追加実装した機能
### Userページ

授業ではツイート一覧のユーザー名をクリックすることでUser detailとして追加日時、フォロワー、フォローを表示する仕様であったが、それに加えてその人のツイートを一覧表示するページを作成した。Mypageもこれを流用して追加日時、フォロワー、フォローも表示されるようになった。

### 小さな調整
#### Dashboard 
ログイン後表示されるDashboardにWelcome "ユーザー名" と表示されるようにした。

#### 見出しの変更
index.blade.phpを使用しているページは見出しが同一で現在いるページがわかりにくかったため、Userページ（Mypage含む）ではユーザー名、TimelineページではTimelineと表示されるようにした

#### フォローボタン
自身のツイートに表示されるユーザー名にはフォローボタンが表示されないようにした。

## 作成者
22 石川清之助


