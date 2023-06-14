ASGIで動作します。  
deployボタンは追加していく予定です 
blog内に静的サイトを入れると認証されていない時にそのサイトが表示されます。　
掲示板内では画像は使えません。　
cookieにyuki=Trueを設定すると認証され、ホームに飛びます。  
サーバーの起動時に掲示板の公式インスタンスに接続します。定期的にサーバーを再起動してください。  

Renderを使用する場合の手順  
1.githubアカウントを作成する  
2.リポジトリを作る(名前はなんでもいい)(プライベートリポジトリにすることをおすすめします)  
3.「import code」を押して「 https://github.com/mochidukiyukimi/Yuki-Youtube-slim/ 」と入力  
4.「render.yaml」ファイルを開いて編集(鉛筆のマーク)を押し、「name」の横の「yuki-youtube-slim」をサイトのurlの最初の部分にしたい文字列に変更する。(「yuki-y」の場合、urlは「 https://yuki-y.onrender.com 」になります)  
5.「Deploy to render」ボタンを押し、「Service Group Name」に文字列を入れて(適当でも良い)apply(事前にrenderのアカウントを作っておく)
RenderでDeploy<br>
<a href="https://render.com/deploy?repo=https://github.com/mochidukiyukimi/Yuki-Youtube-slim">
<img src="https://render.com/images/deploy-to-render-button.svg" alt="Deploy to Render">
</a>
RailwayでDeploy
[![Deploy on Railway](https://railway.app/button.svg)](https://railway.app/new/template/dSxuA8)
