# THIS IS FORK SHADER. 
Basically, please contact the main repository for FBX model use.
I have also translated the README of the main repository into Japanese and added explanations for Japanese users, such as official examples of its use.

This shader material has been modified for use with PMX models. It's a simple node edit that only removes the reference to vertex colors.

#  Blender/Goo Engine 3.3以上の PMXモデル向け "原神" 再現シェーダー

## トレイラーPV

[![Trailer](https://img.youtube.com/vi/sbmphjUkVsA/maxresdefault.jpg)](https://youtu.be/sbmphjUkVsA)

## プレビュー *(heavily post-processed)*
![Preview](https://pbs.twimg.com/media/FMHJjhOUYAAvPnR?format=jpg)

![Preview](https://pbs.twimg.com/media/FgP2vD1akAAKNgs?format=jpg)

## 概要 by No_Tables *(thank you!)* / translated and add fnoji 

[![Overview by No_Tables](https://i.imgur.com/ktMusVY.jpg)](https://youtu.be/97G7LqFoTdY)

## 使用方法
1. リリースよりマテリアル.blendをダウンロードしてください。
2. 好きなキャラクターメッシュを使用した新規プロジェクトで、ダウンロードしたシェーダーマテリアル.blendを全てアペンドしてください。
3. メッシュの元々のマテリアルを、追加したシェーダーマテリアル.blendに置き換えてください。
4. テクスチャを画像ノードにインポートしてください。
5. *Head Origin* とする空のオブジェクトを **Child Of** コンストレイトを使用して、キャラクターの頭ボーンにコンストレイトしてください。
7. [概要ビデオ１](https://youtu.be/97G7LqFoTdY) made by [No_Tables](https://twitter.com/No_Tables) 概要ビデオ１（少し古い）
8. [概要ビデオ２](https://youtu.be/vWfd3NIezpQ) made by [Bonny](https://twitter.com/BonnyTweetsOFF) 概要ビデオ２（少し古い）
9. シェーダー適用を自動化する[Blenderアドオン](https://github.com/michael-gh1/Addons-And-Tools-For-Blender-miHoYo-Shaders) by Mken が存在しますが、これは全てFBXモデル向けです。PMX向けは現在作成予定となります。

## 問い合わせ
〇ソースリポジトリ
- [Discord server](https://discord.gg/85rP9SpAkF) / Omatsuri [EN]
- [Twitter](https://twitter.com/festivizing) / [EN/PH]

基本的にPMX向けに編集されたこのシェーダーは、**ソースリポジトリの開発者や貢献者とは関係がなく、原則サポートしていません。**
PMXモデルへの適用などの問い合わせについては開発者や貢献者には行わず、以下へ行ってください。
- [Discord server](https://discord.gg/85rP9SpAkF) / Hoyo Animation Creator [JP/EN]
- [Twitter](https://twitter.com/fnoji) / [JP/EN]

## ルール
- このPMX向けシェーダーは、基本的にソースリポジトリのルールが継承されています。
- ライセンスは [GPL-3.0 License](https://github.com/festivize/Blender-miHoYo-Shaders/blob/main/LICENSE) が適用されます。
- このシェーダーをレンダリング、アニメーション、シェーダを直接変更しないメディアで使用する場合、貢献者にクレジットを頂けると有難いです。ただし、強制ではありません。
- このシェーダーを独自のシェーダーの主要資料として使用する場合、適切なクレジット表記を行ってください。
- ライセンスに従い、ソースリポジトリへのリンクを添付することにより、ファイルの転載や再配布は自由です。

## 貢献者
シェーダーの開発貢献者は以下の通りです。
- Arc System Works
- HoYoverse
- [Aerthas Veras](https://github.com/Aerthas/) 
- [Manashiku](https://github.com/Manashiku/)
- The folks over at [知乎专栏](https://zhuanlan.zhihu.com/)
- JTAOO
- [BonnyAnimations](https://twitter.com/BonnyTweetsOFF)
- [Mken](https://twitter.com/Mken_TechArt)
- [Enthralpy](https://www.youtube.com/@Enthralpy)
- [Llama](Https://twitter.com/Llama3D)
- [No_Tables](https://twitter.com/No_Tables)

彼らが貢献しなければこのシェーダーの制作は実現しませんでした。
それにより、学んだことをコミュニティに還元したいと思っています。このシェーダーを使用し、あなたも何かを一緒に学んでくれることを願っています。Enjoy!

## 免責事項

この再現シェーダーは、100％正確な内容であることを保証していません。ゲーム内の見た目をBlender上で可能な限り再現することに特化しています。

また、このシェーダーは解析アセット向け（FBX）用に開発されていますが、フォーク者がPMXモデル向けに適用ができるように一部を改変しています。ただ、FBXモデルに適用する場合より、表現が劣ってしまう点に注意が必要です。

原則的には、ソースリポジトリでFBXモデルへ適用する事を推奨します。

## シェーダーのメーカー公認作品採用例

シェーダーのメーカー公認作品採用例の１例を記載します。

[HoyoFair 1](https://www.youtube.com/live/nCar9SiJFrs?si=NkbxH-n9Ra8UG3C6&t=1843) / No_Tables
[HoyoFair 2](https://www.youtube.com/live/EM9x7y0BNW8?si=zzu1vYTaIqmSh2R7&t=2703) / Subutai Productions

その他、HoYoCreators会員者や、Hoyoverse公式主催の動画コンテスト受賞作品などで幅広く使用された実績が多くあります。
詳細な点は全て [Discord server](https://discord.gg/85rP9SpAkF) / Hoyo Animation Creator [JP/EN] へ記載していますので、問い合わせはこちらへよろしくお願いいたします。

## ソースリポジトリの開発者より
「このシェーダーの利用は、ライセンスを読めば明らかですが、完全に無料です。ただし、もしあなたが少しでも余裕があり、私を支援したいと思ってくださるなら、私のKo-fi [こちら](https://ko-fi.com/festivity) で支援していただけます。 すべての支援に感謝し、それがシェーダーを改善し続けるモチベーションになっています。」



