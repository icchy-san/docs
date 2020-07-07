# KBOYのFlutter大学アプリ（サロンアプリ）開発

ようこそ！  
サロンアプリの開発に参加する場合は、下記をお読みください。

## 開発スタイル

[スクラム開発](https://ja.wikipedia.org/wiki/%E3%82%B9%E3%82%AF%E3%83%A9%E3%83%A0_(%E3%82%BD%E3%83%95%E3%83%88%E3%82%A6%E3%82%A7%E3%82%A2%E9%96%8B%E7%99%BA))におけるプロダクトオーナーと複数のスクラムマスター（のような人）がいて、スクラムマスターが都度タスクをエンジニアチームに照会し、対応ができるエンジニアが立候補してタスクを消化してくスタイルをとっています。  
これは、メンバーの入れ替わりが起こることを想定して、できる限り個人に依存することは避けるためです。  
この開発スタイルを**オープンスクラム開発**（造語）と呼んでいます。

<img width="75%" alt="全体図" src="https://user-images.githubusercontent.com/13707135/86811252-a7cd8180-c0b8-11ea-9685-8823661bdf70.png">

開発の流れを大まかに説明します。  
定期的に開催されるスプリントプランニングと呼ばれるオンライン会議で、直近で対応するストーリーを洗い出し、スクラムマスターにアサインします。  
各スクラムマスターはストーリーをタスクに分割し、slackの [#proj_salon_app](https://kboy.slack.com/archives/C016RAU4H52) に照会し、対応してくれるエンジニアを募集します。基本的には早い者勝ちで、手を上げてくれたエンジニアにアサインされます。比較的簡単なタスクもありますので、積極的に手を上げましょう。 
エンジニアはタスクを複数掛け持ちすることも可能です。  
わからないことがあればスクラムマスターと相談して解決していきます。  
タスクが全部終わり、ストーリーを満たすアウトプットができあがれば、プロダクトオーナーのレビューを受けて完了になります。  

## ロールとルールの定義

### プロダクトオーナー：KBOY
* プロダクトに責任を持つ
* ストーリーのOpen/Closeとスクラムマスターへのアサインの権限を持つ
* スクラムマスターのアウトプットをレビューしフィードバックをする
* 各ストーリーを横断する問題を解決する

### スクラムマスター
* ストーリーに責任を持つ
* タスクのOpen/Closeとエンジニアへのアサインの権限を持つ
* アサインせずにエンジニアから担当者を募集してよい
* エンジニアのアウトプットをレビューしフィードバックをする

### エンジニア
* アサインされたタスクに責任を持つ
* わからないことがあればスクラムマスターと相談して解決していく

## [サロンアプリの概要](./overview)

サロンアプリの開発に参加するみなさまはこのページをお読みください。サロンアプリ全体のアーキテクチャ、サロンアプリの概要が説明されています。

## [開発の流れ（エンジニア向け）](./explanation/engineer)

エンジニアの方はこのページをお読みください。スクラムマスターからタスクを受取り、ソースコードを修正してサロンアプリにデプロイするまでの一連の手順が説明されています。

## [開発の流れ（スクラムマスター向け）](./explanation/scrum_master)

スクラムマスターの方はこのページをお読みください。プロダクトオーナーからストーリーをアサインされ、タスクを作成し、エンジニアと協力をしながら開発を進める一連の手順が説明されています。

