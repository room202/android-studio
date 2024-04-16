# Android Studio

## インストールの手順

### ダウンロード

下記サイトからAndroid Studioをダウンロードする  
https://developer.android.com/studio?hl=ja

![](images/001.png)
![](images/002.png)

`上記の利用規約～同意します。`にチェックを入れて`ダウンロード Android Studio～`をクリック
![](images/003.png)

`ダウンロード`フォルダに保存する  
![](images/004.png)

### インストール

ダウンロードしたファイルを実行  
![](images/005.png)

`Next`をクリック  
![](images/006.png)

`Next`をクリック  
![](images/007.png)

`Next`をクリック  
![](images/008.png)

`Install`をクリック  
![](images/009.png)

インストールが始まるの待つ  
![](images/010.png)

インストールができたら`Next`をクリック  
![](images/011.png)

`Finish`をクリック  
![](images/012.png)

## 初期設定

`Do not import settings`のまま`OK`をクリック  
![](images/013.png)

`Help improve Android Studio`は`Don't send`をクリック  
![](images/014.png)

`Next`をクリック  
![](images/015.png)

`Next`をクリック  
![](images/016.png)

`Next`をクリック  
![](images/017.png)

`Accept`にチェックを入れて`Finish`をクリック  
![](images/018.png)

必要なファイルのダウンロードが始まるの待つ  
![](images/019.png)

ダウンロードが終わったら`Finish`をクリック  
![](images/020.png)

## 新しいプロジェクトの作成

`New Project`をクリック  
![](images/022.png)

今回は参考までに`Bottom Navigation Views Activity`をクリックして`Next`をクリック  
![](images/023.png)

下記設定に変更して`Finish`をクリック
- Language : Java
- Build configuration language : Groovy DSL (build.gradle)

![](images/024.png)

Android Studioで新規プロジェクトが起動する  
![](images/025.png)

## Android端末のエミュレーター設定

パソコン上でAndroidスマホを仮想的に動かすエミュレーターを作る

`Device Manager`アイコンをクリック  
![](images/026.png)

`Create virtual device`をクリック  
![](images/027.png)

今回は参考までに`Pixel 8 Pro`で作る  
`Pixel 8 Pro`をクリックして`Next`をクリック  
![](images/028.png)

今回は参考までに`Pixel 8 Pro`にAndroid OS Ver11.0を乗せる  
`R`の右のダウンロードボタンをクリックする  
![](images/029.png)

ダウンロードが始まるの待つ  
![](images/030.png)

ダウンロードが終わったら`Finish`をクリック  
![](images/031.png)

`Next`をクリック  
![](images/032.png)

`Finish`をクリック  
![](images/033.png)

`Device Manager`に今回作った`Pixel 8 Pro`が表示される  
表示が確認できたら上の緑の再生ボタンをクリック
![](images/034.png)

しばらくすると`Pixel 8 Pro`のエミュレーターが起動する  
![](images/035.png)

## Android Studioの日本語化

### Android Studioのバージョンを確認する  

メニューバーから`Help`→`About`  
![](images/036.png)

`Build`の記載を確認する  
今回は`#AI-232.10300`  
![](images/037.png)

### 日本語化ファイルをダウンロード  

下記サイトからAndroid Studioの日本語化ファイルをダウンロードする  
https://plugins.jetbrains.com/plugin/13964-japanese-language-pack------/versions/stable

確認したバージョンに近いバージョンを探す  
下へスクロール  
![](images/038.png)

`Show More`をクリックして、過去のバージョンも表示する  
![](images/039.png)

今回は`232.105`が近いので、これをダウンロードする  
ダウンロードボタンをクリック  
![](images/041.png)

`Download`をクリックしてダウンロードする  
![](images/042.png)

`ダウンロード`フォルダに保存する
![](images/043.png)

### 日本語化ファイルを所定の位置に移動  

ダウンロードしたファイルを解凍(展開)する  
`Shiftキーを押しながら右クリック`→`7-Zp`→`ここに展開`をクリック  
![](images/044.png)

展開されたフォルダ(今回は`ja.232.105`フォルダ)を下記フォルダに移動する  
`C:\Program Files\Android\Android Studio\plugins`  
![](images/045.png)
![](images/046.png)

### 日本語化

これから日本語に設定する

Android Studioの右上の歯車アイコンをクリックして`Plugins`をクリック  
![](images/047.png)

`Install Plugin from Disk...`をクリック  
![](images/048.png)

先ほど移動した`ja.232.105`フォルダを探す  
そのフォルダの中の`lib\ja.232.105.jar`を選択して`OK`をクリック  
`C:\Program Files\Android\Android Studio\plugins\ja.232.105\lib\ja.232.105.jar`  
![](images/049.png)

`OK`をクリック  
![](images/050.png)

Android Studioを再起動するか確認されるので`Restart`をクリックして再起動  
![](images/051.png)

Android Studioがある程度日本語化される  
![](images/052.png)
