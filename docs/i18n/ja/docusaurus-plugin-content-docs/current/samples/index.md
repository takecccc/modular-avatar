﻿---
sidebar_position: 3
sidebar_label: サンプルアセット
---

# サンプルアセット

Modular Avatarには、機能の使い方を見せるためのサンプルプレハブがいくつか同封されています。Projectウィンドウの中で、`Packages -> Modular Avatar -> Samples`に入っています。

![サンプルの場所](wheretofind.png)

## 指ペン(Fingerpen)

どこでも使える、便利な指ペンプレハブ。
アバターにオブジェクトを追加するだけで導入が完了します（アクションメニュー直下に導入されます）。
メニュー位置を調整したい場合は、Menu Installerコンポーネントの中のSelect Menuボタンを押して、追加させたいメニューを選んでください。

指ペンプレハブは以下の機能のサンプルとなっています。

* [Merge Animator](../reference/merge-animator.md)でアニメーターをインストール
* [同期パラメーター](../reference/parameters.md)の自動設定
* [メニュー](../reference/menu-installer.md)の自動インストール
* [Bone Proxy](../reference/bone-proxy.md)で、様々のアバターに対応した、アバターのボーンにオブジェクトを導入する方法

## 拍手(Clap)

Clapプレハブをアバターに入れることで、手を合わせると拍手の効果音が流れ、パーティクルがでます。
指ペンと同様、Select MenuでON・OFFスイッチの位置を指定できます。

指ペンでも紹介される機能のほかにも、Contact Receiverの値を内部パラメーターにすることで、他のアセットとの干渉を避ける仕組みのサンプルとなっています。