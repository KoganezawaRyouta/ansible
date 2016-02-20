# ansible

## Xcodeのインストール
# app store でXcodeをinstallする

# ライセンス同意
$ sudo xcodebuild -license

# Command Line Developer Tools install
# App StoreからXcodeをインストール。
# その際に普通のXcodeではなく、バージョンが7.0のXcode betaをインストールする必要があるようです。
# Xcodeのメニューから Open Developer Tool > More Developer Tools を選択。
# Safariでダウンロードできるツール一覧が表示されるので、
# そこからXcodeのバージョン(7.2) OS.10.11に合わせた Command Line Tools をダウンロード・インストール。
# http://qiita.com/marmot1123/items/688adc739eacf67ddb7d

## Homebrewのインストール
$ ruby -e "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/master/install)"

## Ansibleのインストール
$ brew doctor

$ brew update

$ brew upgrade

$ brew install python
$ vi ~/.bash_profile
$ export PATH=/usr/local/bin:$PATH

$ brew install ansible

## Ansibleの実行
$ ansible-playbook -i hosts -vv mac.yml




