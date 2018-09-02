# ansible_fujitsu_K5
## quick start
clouds.yml.sample を clouds.yml にリネームし、自分のK5のアカウントに合うように編集してください。

## single-web-WP.yml
シンプルなインスタンスを起動し、WordPressをインストールするサンプルです。
まっさらの状態からの作成を想定しています。
SSH鍵をtaskの中で作成してそれを利用して接続します。
もし自分の鍵を利用したい場合、
./id_rsa_ansible.pub
./id_rsa_ansible
という名前でファイルが先に存在すれば、その鍵をK5に登録します。
single-web-WP_vars.yml.sample を single-web-WP_vars.yml にリネームし、WordPressで使用するDBのパスワード等を指定してください。

