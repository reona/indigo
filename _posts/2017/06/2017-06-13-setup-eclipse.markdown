---
title: "Eclipse の初期設定"
layout: post
date: 2017-06-13 15:30
tag:
- eclipse
- setup
category: blog
author: reona
description: eclipseの初期セットアップについて
published: true
---

## 概要

Eclipseをインストール後行った初期設定になります

### インストールしたプラグイン

- Vrapper[^1]
- Spring Tool Suite(STS)
- Autodetect Encoding
- Eclipse Color Theme
- Buildship Gradle
- Egit

### 設定項目

- Eclipseの日本語化[^2]

#### 雑感

インストール直後行った設定は上記だけになります  
Vrapperは、$HOMEいかに.vrapperrcファイルを設定することで自由にカスタマイズできるということで
とりあえずないと困りそうなものだけ設定

```
:set smartcase
:set number
:set cursorline
:set tabstop=2
:set shiftwidth=4
:set softtabstop=2
:set wrap
:set list
:set showmatch
```

Eclipseのアクションも追加できるようなので（リファクタリング、整形）とか徐々に増やす

#### 参考記事

[^1]: [Eclipseのキーバインドをvim風にできるVrapperが素晴らしすぎる件について](http://yuroyoro.hatenablog.com/entry/20100218/1266477264)
[^2]: [Eclipse プラグイン日本語化プラグイン](http://mergedoc.osdn.jp/)

