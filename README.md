<h2>Bottle of Experience</h2>
<h3>概要</h3>
<p>・経験値をエンチャントの瓶に変換することができます
<br>・エンチャントの瓶を使用した際の経験値量が10に固定されます
<br>・ディスペンサーにより発射されたエンチャントの瓶の経験値量はデフォルトのままになっています</p>
<h3>コマンド</h3>
<p>経験値を[数]個のエンチャントの瓶に変換</p>
<code>/trigger bottle-get set [数]</code>
<br><br><br><p>経験値をすべてエンチャントの瓶に変換</p>
<code>/trigger bottle-get</code><br><br><br>

<h2>Sethome</h2>
<h3>概要</h3>
<p>・5つまで「ホーム」をセットできます
<br>・いつでもホームにテレポートできます
<br>・ディメンションを超えたテレポートはできません</p>
<h3>コマンド</h3>
<p>現在の位置をホームとして[id]のスロットに設定</p>
<code>/trigger sethome set [id]</code>
<br><br><br><p>[id]のスロットに設定されているホームにテレポート</p>
<code>/trigger gohome set [id]</code>
<br><br><br><p>[id]のスロットに設定されているホームを削除</p>
<code>/trigger delhome set [id]</code>
<br><br><br><p>設定されているホームをすべて表示</p>
<code>/trigger sethome</code><p></p><code>/trigger gohome</code><p></p><code>/trigger delhome</code><br><br><br>

<h2>Common Timer</h2>
<h3>概要</h3>
<p>・シンプルで見やすいタイマーを作成できます
<br>・タイマーの速さはサーバーのラグと関係なく進みます
<br>・シングルプレイのとき、一時停止していてもタイマーは進みます</p>
<h3>コマンド</h3>
<p>タイマーの設定画面を表示</p>
<code>/function common_timer:set_timer</code>
<br><br><br><p>タイマーの開始・中止</p>
<code>/trigger start set 1</code><p></p><code>/trigger start set -1</code>
<br><br><br><p>タイマーの時間を変更</p>
<code>/trigger hours set [数]</code><p></p><code>/trigger minutes set [数]</code><p></p><code>/trigger seconds set [数]</code><br><br><br>
