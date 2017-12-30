---
title: 解決済み：GitHub のリポジトリを BitBucket に移管できなくてちょっとハマる
date: 2017-12-30T02:34:23.004Z
description: GitHub 側のアカウントに二段階認証が設定されているとインポートできないので一時的に 2FA を切らなければならなかった。
---
# まとめ

GitHub 側のアカウントに二段階認証が設定されているとインポートできないので一時的に 2FA を切らなければならなかった。



# 経緯

GitHub のプライベートリポジトリを BitBucket に移動したかった。



# 発生した問題

インポートができなかった。



# 解決策

GitHub 側の 2FA を一時的に切る（2FA を無効化して終わったら再度有効にする）



# ソース

[How to move private repositories from Github to Bitbucket | BeFused](http://befused.com/git/github-bitbucket-move)

`Note that if you have two-factor authentication enabled you'll need to temporarily disable it for the import to work.`
