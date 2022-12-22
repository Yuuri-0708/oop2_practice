1.	GitHubユーザー名<br>
Yuri-0708<br><br>

2.	担当箇所 (できる限り詳しく書くこと)<br>
Webインタフェースを担当しました。<br>
Flaskを利用し、他のメンバーが作成したhtmlファイルへのルーティング処理を記述し、ファイルの保存を行う処理を記述しました。<br>(前回の時間では、ファイルの保存を行う処理の中でエラーが発生して作業がストップしてしまいました。)<br>
3. チーム作業のログ<br>
mainブランチを最新の状態にして $ git --no-pager log --graph
した結果を <pre> タグと組み合わせて貼り付ける

<pre>
*   commit 36716edb8b76089137b72046ad9de4b8dde46bfa (HEAD -> main, origin/main, origin/HEAD)
|\  Merge: e43ae40 90e3388
| | Author: makim0939 <95673492+makim0939@users.noreply.github.com>
| | Date:   Wed Dec 21 22:39:23 2022 +0900
| | 
| |     Merge pull request #16 from 2022AIT-OOP2-G11/anser_reference
| |     
| |     解答を参考に一部作成しました。
| | 
| * commit 90e3388db85566b04d75ac9fb3228150c56ce0e2 (origin/anser_reference)
| | Author: k20235nagata <miru10yuzu@gmail.com>
| | Date:   Tue Dec 20 23:30:52 2022 +0900
| | 
| |     解答に合わせて作成
| |     
| |     解答に合わせてHTMLを作成しました。
| | 
| * commit 09fffe96c955a361a5ac1670be58c7b32c0a41db
|/  Author: k20235nagata <miru10yuzu@gmail.com>
|   Date:   Tue Dec 20 23:30:07 2022 +0900
|   
|       解答を参考に作成
|       
|       解答を参考に作成しました
| 
* commit e43ae408ccdc50d8d0a0edc442777ebbd589d0bf
| Author: makim0939 <95673492+makim0939@users.noreply.github.com>
| Date:   Fri Dec 16 09:49:08 2022 +0900
| 
|     Update README.md
|   
*   commit 3644f17cce0592953674a159ad311b77e2d5e3a7
|\  Merge: 946b006 4cb0f74
| | Author: makim0939 <95673492+makim0939@users.noreply.github.com>
| | Date:   Fri Dec 16 08:22:20 2022 +0900
| | 
| |     Merge pull request #14 from 2022AIT-OOP2-G11/web_widow
| |     
| |     flask側追加
| | 
| * commit 4cb0f746761797a3684c41ae5b74febbb6aa9c23 (origin/web_widow, web_widow)
| | Author: Yuri-0708 <yuuri2313@gmail.com>
| | Date:   Thu Dec 15 16:10:15 2022 +0900
| | 
| |     main修正
| | 
| * commit 0d3748e6b4a64fd5fb6e53d48047d97b67b4ac3a
| | Author: Yuri-0708 <yuuri2313@gmail.com>
| | Date:   Thu Dec 15 15:18:24 2022 +0900
| | 
| |     修正
| | 
| * commit 3c3be230e98b35a467017986342f9287eafa1dd0
| | Author: Yuri-0708 <yuuri2313@gmail.com>
| | Date:   Thu Dec 15 15:05:11 2022 +0900
| | 
| |     Update main.py
| | 
| * commit 43e84c12003b6500e0940f4d5acd29b278635d6c
| | Author: k20235nagata <miru10yuzu@gmail.com>
| | Date:   Thu Dec 15 15:43:31 2022 +0900
| | 
| |     HTMLコード変更
| |     
| |     送信とメッセージのコード追加
| |   
| *   commit 31bb1ce0da862ba3a4173585fcd132919975d4c8
| |\  Merge: dd7e638 ebed70d
| | | Author: k20235nagata <miru10yuzu@gmail.com>
| | | Date:   Thu Dec 15 15:04:26 2022 +0900
| | | 
| | |     Merge branch 'web_widow' of https://github.com/2022AIT-OOP2-G11/oop2_11 into web_widow
| | | 
| * | commit dd7e638f4962c61bd9f54562714b469be3a43a5d
| | | Author: k20235nagata <miru10yuzu@gmail.com>
| | | Date:   Thu Dec 15 15:04:23 2022 +0900
| | | 
| | |     インターフェース追加
| | |     
| | |     ファイル選択と送信メッセージ追加
| | | 
* | | commit 946b0063522936995526fc9cdf77ffb9e1512005
| | | Author: makim0939 <95673492+makim0939@users.noreply.github.com>
| | | Date:   Thu Dec 15 23:04:55 2022 +0900
| | | 
| | |     observer.pyをちょこっと修正
| | |   
* | |   commit e2bfae52c5f7c886b9b16aef7ad36955fd671b00
|\ \ \  Merge: 3373a0d 0fb4bac
| | | | Author: makim0939 <95673492+makim0939@users.noreply.github.com>
| | | | Date:   Thu Dec 15 18:05:46 2022 +0900
| | | | 
| | | |     Merge branch 'main' of https://github.com/2022AIT-OOP2-G11/oop2_11
| | | |   
| * | |   commit 0fb4bac0e2769d99403fffdcb4ee56dbf5c11530
| |\ \ \  Merge: d4d905c 9bb579f
| | | | | Author: makim0939 <95673492+makim0939@users.noreply.github.com>
| | | | | Date:   Thu Dec 15 18:05:06 2022 +0900
| | | | | 
| | | | |     Merge pull request #13 from 2022AIT-OOP2-G11/takoyaki
| | | | |     
| | | | |     a.pyついかしました！！！
| | | | | 
| | * | | commit 9bb579fbc1563b7f5fa055c6f7ab2f6b14c53f8e (origin/takoyaki)
| | | | | Author: kuzuyatowa <k21045kk@aitech.ac.jp>
| | | | | Date:   Thu Dec 15 16:25:48 2022 +0900
| | | | | 
| | | | |     a.pyついかしました！！！
| | | | | 
* | | | | commit 3373a0d599f35e7c5292652a2cf444f1d7813ec3
|/ / / /  Author: makim0939 <95673492+makim0939@users.noreply.github.com>
| | | |   Date:   Thu Dec 15 18:05:42 2022 +0900
| | | |   
| | | |       Delete a.py
| | | |   
* | | |   commit d4d905c44dec4b9948a720106c478fbb99cc4ab9
|\ \ \ \  Merge: 35fcfd1 bd93a86
| |/ / /  Author: makim0939 <95673492+makim0939@users.noreply.github.com>
|/| | |   Date:   Thu Dec 15 18:00:00 2022 +0900
| | | |   
| | | |       Merge pull request #12 from 2022AIT-OOP2-G11/takoyaki
| | | |       
| | | |       名前残し！！！！！
| | | | 
| * | | commit bd93a86f11259d5d141165cc52d0848782f6fe1f
| | | | Author: kuzuyatowa <k21045kk@aitech.ac.jp>
| | | | Date:   Thu Dec 15 16:25:48 2022 +0900
| | | | 
| | | |     a.pyついかしました！！！
| | | | 
* | | | commit 35fcfd1286b42dab9b4b716809c61f43d9ba4143
| | | | Author: makim0939 <95673492+makim0939@users.noreply.github.com>
| | | | Date:   Thu Dec 15 17:56:50 2022 +0900
| | | | 
| | | |     observer.pyをちょっと修正しました
| | | |   
* | | |   commit 47255986c34f44aa54225f2e624279f0d98a0e98
|\ \ \ \  Merge: b0e7801 e12798a
| |/ / /  Author: makim0939 <95673492+makim0939@users.noreply.github.com>
|/| | |   Date:   Thu Dec 15 17:53:11 2022 +0900
| | | |   
| | | |       Merge pull request #11 from 2022AIT-OOP2-G11/frame_face
| | | |       
| | | |       関数足しました
| | | | 
| * | | commit e12798aa2a2c8064845917017d37e634080f8e4d (origin/frame_face)
| | | | Author: nano-33 <k21081kk@aitech.ac.jp>
| | | | Date:   Thu Dec 15 16:06:27 2022 +0900
| | | | 
| | | |     関数足しました
| | | |   
| * | |   commit 851870991ccdd1331fd649ca373e7ceaad5ac5b4
| |\ \ \  Merge: 5249907 9226282
| | | | | Author: nano-33 <k21081kk@aitech.ac.jp>
| | | | | Date:   Thu Dec 15 15:46:48 2022 +0900
| | | | | 
| | | | |     Merge branch 'main' into frame_face
| | | | | 
* | | | | commit b0e7801b4b85c430f575d0299bfb3784aa341cf3
| | | | | Author: makim0939 <95673492+makim0939@users.noreply.github.com>
| | | | | Date:   Thu Dec 15 16:05:16 2022 +0900
| | | | | 
| | | | |     canny.pyをメインブランチから追加しました。
| | | | | 
* | | | | commit 01cdb31a547f0900c8eddeeeee8f9c9d94acf392
|\| | | | Merge: 1896dea 5249907
| | | | | Author: makim0939 <95673492+makim0939@users.noreply.github.com>
| | | | | Date:   Thu Dec 15 15:54:51 2022 +0900
| | | | | 
| | | | |     Merge pull request #9 from 2022AIT-OOP2-G11/frame_face
| | | | |     
| | | | |     顔に枠つけました
| | | | | 
| * | | | commit 524990747067b80a1d7fd9e5e62b1ff0681f9af8
| | | | | Author: nano-33 <k21081kk@aitech.ac.jp>
| | | | | Date:   Thu Dec 15 15:33:45 2022 +0900
| | | | | 
| | | | |     顔に枠つけました
| | | | |   
* | | | |   commit 1896dea5fef6db45aad1fd53bfa66e20812ce2a5
|\ \ \ \ \  Merge: 9226282 ed2d7ad
| |_|/ / /  Author: makim0939 <95673492+makim0939@users.noreply.github.com>
|/| | | |   Date:   Thu Dec 15 15:51:32 2022 +0900
| | | | |   
| | | | |       Merge pull request #7 from 2022AIT-OOP2-G11/mosaic
| | | | |       
| | | | |       モザイク処理&関数化
| | | | | 
| * | | | commit ed2d7ad0a8ef2f1fbb0e617f3a346de371e4a4f5 (origin/mosaic)
| | | | | Author: Pengin <fierce0728birds@gmail.com>
| | | | | Date:   Thu Dec 15 15:43:19 2022 +0900
| | | | | 
| | | | |     関数に写した
| | | | | 
| * | | | commit 4b0945c16db541718cf7b7d5ec36e42ebadc4a5e
| | | | | Author: Pengin <fierce0728birds@gmail.com>
| | | | | Date:   Thu Dec 15 15:38:31 2022 +0900
| | | | | 
| | | | |     パスなんか変えた
| | | | | 
| * | | | commit b8726332b571948f2d20767363af1d735705e830
| | | | | Author: Pengin <fierce0728birds@gmail.com>
| | | | | Date:   Thu Dec 15 15:21:09 2022 +0900
| | | | | 
| | | | |     関数化
| | | | | 
| * | | | commit 9545bf77f6f9d371544f59c25d8af8e8337d9b65
| | | | | Author: Pengin <fierce0728birds@gmail.com>
| | | | | Date:   Thu Dec 15 15:10:12 2022 +0900
| | | | | 
| | | | |     モザイク処理追加
| | | | |   
* | | | |   commit 922628297c4194e33e0e4c5e51c63b46e8b9f84a
|\ \ \ \ \  Merge: ce0bf50 d724dae
| | | | | | Author: makim0939 <95673492+makim0939@users.noreply.github.com>
| | | | | | Date:   Thu Dec 15 15:28:58 2022 +0900
| | | | | | 
| | | | | |     Merge pull request #8 from 2022AIT-OOP2-G11/observer
| | | | | |     
| | | | | |     Observer
| | | | | | 
| * | | | | commit d724dae09245ad22c04a4c18adc6acae97476c7c (origin/observer)
| | | | | | Author: makim0939 <95673492+makim0939@users.noreply.github.com>
| | | | | | Date:   Thu Dec 15 15:23:42 2022 +0900
| | | | | | 
| | | | | |     フォルダを監視するプログラムを追加しました
| | | | | | 
| * | | | | commit 636a59afebd97bc14aad8d11856f1f83d1ab424a
| | | | | | Author: makim0939 <95673492+makim0939@users.noreply.github.com>
| | | | | | Date:   Thu Dec 15 14:56:24 2022 +0900
| | | | | | 
| | | | | |     add observer
| | | | | |   
* | | | | |   commit ce0bf50732883893e94b2e34529834a78b2f5928
|\ \ \ \ \ \  Merge: a28b7e6 6c3110b
| | | | | | | Author: makim0939 <95673492+makim0939@users.noreply.github.com>
| | | | | | | Date:   Thu Dec 15 15:28:33 2022 +0900
| | | | | | | 
| | | | | | |     Merge pull request #6 from 2022AIT-OOP2-G11/grayscale
| | | | | | |     
| | | | | | |     グレースケールできました
| | | | | | | 
| * | | | | | commit 6c3110ba684bb4aaa15cc8b9ec23f0c887bdacb2 (origin/grayscale)
| | |_|/ / /  Author: rinrintyan <k21108kk@aitech.ac.jp>
| |/| | | |   Date:   Thu Dec 15 15:21:18 2022 +0900
| | | | | |   
| | | | | |       グレースケールできました
| | | | | |   
* | | | | |   commit a28b7e62564200fbe672f27fa2d266a6a4606cf7
|\ \ \ \ \ \  Merge: f362b24 ebed70d
| | |_|_|_|/  Author: makim0939 <95673492+makim0939@users.noreply.github.com>
| |/| | | |   Date:   Thu Dec 15 14:55:56 2022 +0900
| | | | | |   
| | | | | |       Merge pull request #5 from 2022AIT-OOP2-G11/web_widow
| | | | | |       
| | | | | |       main.pyの修正
| | | | | | 
| * | | | | commit ebed70d6ca478585d1ab9c30a580380ee52f67c7
| | |_|_|/  Author: Yuri-0708 <yuuri2313@gmail.com>
| |/| | |   Date:   Thu Dec 15 14:51:34 2022 +0900
| | | | |   
| | | | |       Update main.py
| | | | |   
| * | | |   commit 9cf76277dd6328e6f66d99bdf4ba1eb28a12a5b0
| |\ \ \ \  Merge: e9fd9fb 4ae339c
| | | | | | Author: k20235nagata <miru10yuzu@gmail.com>
| | | | | | Date:   Thu Dec 15 14:29:01 2022 +0900
| | | | | | 
| | | | | |     Merge branch 'main' into web_widow
| | | | | | 
| * | | | | commit e9fd9fbb78e0b69413b7cbff96103b4487dfade5
| | | | | | Author: k20235nagata <miru10yuzu@gmail.com>
| | | | | | Date:   Thu Dec 15 14:22:21 2022 +0900
| | | | | | 
| | | | | |     HTML追加
| | | | | |     
| | | | | |     HTMLのテンプレートを追加
| | | | | | 
| * | | | | commit 1b304141eedd146cb106961405f36c4114f87beb
| | | | | | Author: k20235nagata <miru10yuzu@gmail.com>
| | | | | | Date:   Thu Dec 15 14:13:42 2022 +0900
| | | | | | 
| | | | | |     追加と削除
| | | | | |     
| | | | | |     HTMLにわかりやすい名前をつけてテンプレートを再作成しました。
| | | | | | 
| * | | | | commit 9378858b80154c2a6000c40711b6e7afcf96b6c9
| | | | | | Author: k20235nagata <miru10yuzu@gmail.com>
| | | | | | Date:   Thu Dec 15 14:04:20 2022 +0900
| | | | | | 
| | | | | |     HTMLテンプレート追加
| | | | | |     
| | | | | |     HTMLのテンプレートを追加しました。
| | | | | |   
* | | | | |   commit f362b24de8bfa9ba4f70b1d89b87a098107f29a8
|\ \ \ \ \ \  Merge: fd4648c 6bff5d6
| |_|_|_|/ /  Author: makim0939 <95673492+makim0939@users.noreply.github.com>
|/| | | | |   Date:   Thu Dec 15 14:38:30 2022 +0900
| | | | | |   
| | | | | |       Merge pull request #4 from 2022AIT-OOP2-G11/edit_readme
| | | | | |       
| | | | | |       Update README.md
| | | | | | 
| * | | | | commit 6bff5d6bf2664f961d303ef7f18989591b9799f6 (origin/edit_readme)
| | | | | | Author: makim0939 <95673492+makim0939@users.noreply.github.com>
| | | | | | Date:   Thu Dec 15 14:38:06 2022 +0900
| | | | | | 
| | | | | |     Update README.md
| | | | | | 
* | | | | | commit fd4648c98fd5c1c6cbca3e030b2ff37ed7fb251b
|\| | | | | Merge: 4ae339c 44cf5ce
| |_|/ / /  Author: makim0939 <95673492+makim0939@users.noreply.github.com>
|/| | | |   Date:   Thu Dec 15 14:36:53 2022 +0900
| | | | |   
| | | | |       Merge pull request #3 from 2022AIT-OOP2-G11/edit_readme
| | | | |       
| | | | |       Update README.md
| | | | | 
| * | | | commit 44cf5cefb03203159be88127555df4a96819f24c
|/ / / /  Author: makim0939 <95673492+makim0939@users.noreply.github.com>
| | | |   Date:   Thu Dec 15 14:36:02 2022 +0900
| | | |   
| | | |       Update README.md
| | | | 
* | | | commit 4ae339cf95a6ea13ec7232945f90414a3ac8aa75
|\| | | Merge: 8196690 149a456
| |/ /  Author: makim0939 <95673492+makim0939@users.noreply.github.com>
|/| |   Date:   Thu Dec 15 13:59:49 2022 +0900
| | |   
| | |       Merge pull request #2 from 2022AIT-OOP2-G11/web_widow
| | |       
| | |       Create main.py
| | | 
| * | commit 149a456ff59d7108c7528648ac7329ef6ae4e3d1
| | | Author: Yuri-0708 <yuuri2313@gmail.com>
| | | Date:   Thu Dec 15 13:53:17 2022 +0900
| | | 
| | |     Create main.py
| | |   
* | |   commit 819669038ca967d78c50187cca167e1a5f2bb027
|\ \ \  Merge: a970b39 06fbd9c
| |/ /  Author: makim0939 <95673492+makim0939@users.noreply.github.com>
|/| /   Date:   Thu Dec 15 13:51:47 2022 +0900
| |/    
| |         Merge pull request #1 from 2022AIT-OOP2-G11/mosaic
| |         
| |         フォルダの追加
| | 
| * commit 06fbd9c272aa3d64e8faa3ceee189460efc4f85f
|/  Author: Pengin <fierce0728birds@gmail.com>
|   Date:   Thu Dec 15 13:50:30 2022 +0900
|   
|       フォルダの追加
| 
* commit a970b3939703c7e7de65c687ce4a7644473b5fed (origin/cannyfilter)
  Author: makim0939 <95673492+makim0939@users.noreply.github.com>
  Date:   Thu Dec 15 13:27:07 2022 +0900
  
      Initial commit
 </pre>
<br>
4. 感想 (次に活かせる反省等あればここに書いておくと良い)<br>
　今回、グループワークでWebインタフェースを担当し、webインタフェース側担当グループのみでもソースファイルの名前やinputタグのname属性の名前など共有しなければならない情報が多く、一人で作業する場合と比較し、難しさを感じました。また、エラーが発生した場面などでグループメンバー複数が1つのエラーの解決に当たっているという状況が発生しました。これにより作業がストップしてしまったため、次の作業時からは分担を徹底して行い無駄な時間を発生させないよう心がけたいです。
　この１週間の期間でグループで自由課題の内容を決定しました。リーダーがかなり頼もしく指揮をおこなってくれているため、できる範囲で補助して取り組んでいきます。
