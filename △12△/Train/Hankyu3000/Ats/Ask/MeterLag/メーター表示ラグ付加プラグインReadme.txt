グラスコックピット風メーター表示ラグ付加プラグインReadme

当プラグインは、メーターの表示ラグを再現する際に使うプラグインです。
機械式速度計としても使用できるかも

iniファイルが見つからなかった場合、自動生成されます。
iniファイル内部の説明
[DATA]
UpDateTime		:パネルに値を反映させる周期(ms)
PanelMR			:MR圧の表示インデックス
PanelMRD1		:MR圧の表示インデックスデジタル1桁
PanelMRD10		:MR圧の表示インデックスデジタル2桁
PanelMRD100		:MR圧の表示インデックスデジタル3桁
PanelBC			:BC圧の表示インデックス
PanelBCD1		:BC圧の表示インデックスデジタル1桁
PanelBCD10		:BC圧の表示インデックスデジタル2桁
PanelBCD100		:BC圧の表示インデックスデジタル3桁
PanelER			:ER圧の表示インデックス
PanelERD1		:ER圧の表示インデックスデジタル1桁
PanelERD10		:ER圧の表示インデックスデジタル2桁
PanelERD100		:ER圧の表示インデックスデジタル3桁
PanelBP			:BP圧の表示インデックス
PanelBPD1		:BP圧の表示インデックスデジタル1桁
PanelBPD10		:BP圧の表示インデックスデジタル2桁
PanelBPD100		:BP圧の表示インデックスデジタル3桁
PanelSAP		:SAP圧の表示インデックス
PanelSAPD1		:SAP圧の表示インデックスデジタル1桁
PanelSAPD10		:SAP圧の表示インデックスデジタル2桁
PanelSAPD100		:SAP圧の表示インデックスデジタル3桁
PanelSpeed		:速度の表示インデックス
PanelSpeed1		:速度の表示インデックスデジタル表示1桁
PanelSpeed10		:速度の表示インデックスデジタル表示2桁
PanelSpeed100		:速度の表示インデックスデジタル表示3桁
PanelSpeedMax		:速度の表示インデックス(置針)
PanelCurrent		:電流の表示インデックス
PanelCurrentD1		:電流の表示インデックスデジタル1桁
PanelCurrentD10		:電流の表示インデックスデジタル2桁
PanelCurrentD100	:電流の表示インデックスデジタル3桁
PanelCurrentD1000	:電流の表示インデックスデジタル4桁
PanelCurrentMinus	:負電流の符号表示インデックス
PanelCurrentABS		:電流(+方向のみに振れる)の表示インデックス
LoadSound		:情報更新時に鳴る音(2km/h以上で鳴る)

使わないインデックスは-1にしてください。

プラグイン本体のdllファイル名と同じ名前のiniファイルが読み込まれます。

パネル設定ファイルでの設定箇所
[Needle]
Subject = ats**(iniファイルで設定したインデックス)
NaturalFreq = 0
(DampingRatioは削除)
Bve標準のmr、bc、kmph、er、bp、sap、am、amabsでは表示されませんので注意してください。

二次配布について
当プラグインは素材として公開しておりますので、各自車両データ等に組み込んだり改造パッチにするなどで二次配布を許可しております。
ただし、バグ報告の収集のため、使用した旨を各データのReadme等にお書きのうえ、このReadmeをリネーム等するなどして同梱してください。
プラグインのみの再配布は、そのプラグインが最終更新版である場合のみ許可します。

当プラグインは、Mackoy氏のサンプルプラグインを改造して製作しております。
iniファイルの読み込みにはamedas.氏のinimoniで出力されたソースを使用しています。

製作　秋田の新快速 Twitter:@ASKED757001 E-mail ED757001@gmail.com