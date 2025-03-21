### スピンターゲット作成方法

## (1) MgO 基板のアニール (エレボン)
- Fil1: 2.52 A, Vol: 500 V, Emis: 15 mA, ~620 ℃ 
- アニール中の Pressure が 10<super>-8</super> Pa 代になるまで放置する
- アニールを切ってから 30 分以上放置して室温になるまでよく冷ます

## (2) Fe 蒸着源の DEGAS 及び蒸着
- 水を流していることをよく確認！！
- 蒸着していないときはシャッターを必ず閉める！！
- MgO基板はちゃんとアースに落とす！！
- DEGAS をしっかり！</b></span>（蒸着条件で 10^-8 Pa 代に入っていることが望ましい)
- ~50 nA 程度の Flux で 2-3 分放置して真空度を確認→もし真空度が 10-8 Pa 代なら 0.5 nA にして 1 時間ぐらい放置して蒸着本番に備える。
- Fil: 1.96 A, Vol: 800 V, Emis: ~7mA, =>Flux: ~50 nA，これで 90 分蒸着 
- もし Emis や Flux が増えないのであれば，蒸着源を近づける
- 蒸着位置：Stage1 に MgO を載せる。 シャッターを開け，ステージを前後させ下側にある ICF70 窓から垂直に覗き，フィラメント反射が MgO 中心に来ることを確認。ステージロッドにも黒線でマークしてある。

## (3) ソフトアニール
- V1のBNC端子を付け替える。
- 右側(フィラメント)のパワーのスイッチをオンにして、アウトプットボタンを押す。カレントを少しずつ2.52Aまで上げる。この時真空度を気にしながらあげていく。その後、左側(アニール用サンプル電圧)のパワーのスイッチ、アウトプットのスイッチの順につけて、ボルテージを550Vまで少しずつ上げる。この時真空が10-7乗に入らないようにする！温度が600℃にいかないときはボルテージを上げる。
- 15分経ったら左側の電圧を0にして、アウトプットスイッチをオフ、パワースイッチをオフ、右側のカレントを0にして、アウトプットボタンを押す、パワースイッチをオフにする
  
(薄膜の原子配列を整えるためにソフトアニール 600 ℃、
Fil: 2.52 A, Vol: 500V, Emis: 13 mA, ~600℃になることを確認、
この温度で 15 min 待つ。もし温度が時間で変化するようであれば，その都度微調整、
アニール後，冷めるまで 20 分以上待つ。アニール直後にステージ動作を使用とすると，配線が切れる可能性があるため)
<img src="https://github.com/ko5656/spin_target_create/blob/main/picture/IMG_0333.jpg" alt="サンマの塩焼き" height="40%" width="40%" />

## (4) O<sub>2</sub> 曝露
- バリアリークバルブをゆっくり開けながら(反時計回り)酸素ガスを導入。
- 真空度をよく確認して事故のないように！！
- 開けて行くと急に真空度が下がるところがあるのでゆっくりやる！
- 1.4×10<super>-5</super> Pa で固定して，5 min 待つ。
- バルブを閉める(時計回り)
<img src="https://github.com/ko5656/spin_target_create/blob/main/picture/IMG_0334.jpg" alt="サンマの塩焼き" height="20%" width="20%" /><img src="https://github.com/ko5656/spin_target_create/blob/main/picture/IMG_0335.jpg" alt="サンマの塩焼き" height="20%" width="20%" />

## (5) フラッシュアニール
- 表面に残った余分酸素分子を飛ばすため
- 条件：Fil1: 2.52 A, Vol: 500 V, Emis: 15 mA, ~600 ℃, 到達してから 1 min でソフトアニールと同じ手順で切る。 
- アニール後，冷めるまで 20 分以上待つ。アニール後にステージ動作を使用とすると，配線が切れる可能性があるため

## (6) LEED で p(1×1) を確認
- LEED で p(1×1) を確認
- LEEDの配線を繋ぐ
- BNC端子を繋ぐ
- V1を繋がってないBNC端子に変える
- アルミで暗くする
<img src="https://github.com/ko5656/spin_target_create/blob/main/picture/IMG_0336.jpg" alt="サンマの塩焼き" height="20%" width="20%" /><img src="https://github.com/ko5656/spin_target_create/blob/main/picture/IMG_0337.jpg" alt="サンマの塩焼き" height="20%" width="20%" /><img src="https://github.com/ko5656/spin_target_create/blob/main/picture/IMG_0338.jpg" alt="サンマの塩焼き" height="20%" width="20%" /><img src="https://github.com/ko5656/spin_target_create/blob/main/picture/IMG_0339.jpg" alt="サンマの塩焼き" height="20%" width="20%" /><img src="https://github.com/ko5656/spin_target_create/blob/main/picture/IMG_0341.jpg" alt="サンマの塩焼き" height="20%" width="20%" /><img src="https://github.com/ko5656/spin_target_create/blob/main/picture/IMG_0342.jpg" alt="サンマの塩焼き" height="20%" width="20%" /><img src="https://github.com/ko5656/spin_target_create/blob/main/picture/IMG_0343.jpg" alt="サンマの塩焼き" height="20%" width="20%" /><img src="https://github.com/ko5656/spin_target_create/blob/main/picture/IMG_0346.jpg" alt="サンマの塩焼き" height="20%" width="20%" /><img src="https://github.com/ko5656/spin_target_create/blob/main/picture/IMG_0350.jpg" alt="サンマの塩焼き" height="20%" width="20%" />

- パワースイッチをオンにする
- BEAM ENERGY CONTROLを回して電子数を調整する。
- SETTINGのボタンを長押しすると値が0になる。
- POWERのスイッチをオフにする
<img src="https://github.com/ko5656/spin_target_create/blob/main/picture/IMG_0354.jpg" alt="サンマの塩焼き" height="40%" width="40%" />

- 低エネルギーから上げていき、十字にリードが見えるとおっけい, バツにリードが見えると汚れている。エネルギーをあげすぎると汚れてなくても干渉でバツに見えるので低エネルギーでやる！
- もし c(2×2)が見えてしまったら，ターゲットとして使えないので基板を交換してやり直し
<img src="https://github.com/ko5656/spin_target_create/blob/main/picture/IMG_0355.jpg" alt="サンマの塩焼き" height="40%" width="40%" />
<img src="https://github.com/Hikaribussei-lab/homepage/blob/440db5b5bdc722eae09fbdac4a48a22bdc2a10c3/target/img/MgOFe.jpg" alt="サンマの塩焼き" height="40%" width="40%" />
