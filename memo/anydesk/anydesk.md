# インストールの手順
リポジトリキーをソフトウェア・プロバイダー・リストに登録
`wget -qO - https://keys.anydesk.com/repos/DEB-GPG-KEY | sudo apt-key add -`
リポジトリを追加
`sudo sh -c 'echo "deb http://deb.anydesk.com/ all main" > /etc/apt/sources.list.d/anydesk-stable.list'`
リポジトリを更新
`sudo apt update `
インストールする
` インストール`
