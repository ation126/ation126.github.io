# 20230328 00:26:01

## /root/FIL/strategy/amihud/log.txt ----- -----

--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=993672.4896432, self.flagDict['side']='sell', self.tradeCount=2, self.count=34684
self.closeSec=1679933999, self.tradeDate='20230328', self.openTime='001500', self.closeTime='001959', self.symbol='BTCUSDT', self.open=27144.8, self.close=27243.2, self.high=27300.0, self.low=27144.8, self.vol=10298.693, self.amt=280468819.6649 
127.0.0.1 - - [28/Mar/2023 00:20:04] "POST / HTTP/1.1" 200 -
2023-03-28 00:20:09,421:INFO:amihud:main.py:172:handleKline:200676: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5759  20230327   235500    235959  ...         0.0        0.0       0
5760  20230328   000000    000459  ...         0.0        0.0       0
5761  20230328   000500    000959  ...         0.0        0.0       0
5762  20230328   001000    001459  ...         0.0        0.0       0
5763  20230328   001500    001959  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-03-28 00:20:09,442:INFO:amihud:main.py:175:handleKline:200676: self.closeSec=1679933999, self.tradeDate='20230328', self.openTime='001500', self.closeTime='001959',self.symbol='BTCUSDT',self.open=27144.8, self.close=27243.2, self.high=27300.0, self.low=27144.8, self.vol=10298.693, self.amt=280468819.6649, ukdf['pct'].iloc[-1]=0.003629 , ukdf['amount'].iloc[-1]=280468819.6649, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5763, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '60.176', 'enterprice': '16529.3', 'countrevence': '0', 'unrealprofit': '-644536.7327044272', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '27240.1603547', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1
127.0.0.1 - - [28/Mar/2023 00:25:01] "POST / HTTP/1.1" 200 -
--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=993672.4896432, self.flagDict['side']='sell', self.tradeCount=2, self.count=34685
self.closeSec=1679934299, self.tradeDate='20230328', self.openTime='002000', self.closeTime='002459', self.symbol='BTCUSDT', self.open=27243.9, self.close=27202.5, self.high=27246.0, self.low=27170.0, self.vol=5419.025, self.amt=147440704.4742 
2023-03-28 00:25:01,588:INFO:amihud:main.py:172:handleKline:200676: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5760  20230328   000000    000459  ...         0.0        0.0       0
5761  20230328   000500    000959  ...         0.0        0.0       0
5762  20230328   001000    001459  ...         0.0        0.0       0
5763  20230328   001500    001959  ...         0.0        0.0       0
5764  20230328   002000    002459  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-03-28 00:25:01,589:INFO:amihud:main.py:175:handleKline:200676: self.closeSec=1679934299, self.tradeDate='20230328', self.openTime='002000', self.closeTime='002459',self.symbol='BTCUSDT',self.open=27243.9, self.close=27202.5, self.high=27246.0, self.low=27170.0, self.vol=5419.025, self.amt=147440704.4742, ukdf['pct'].iloc[-1]=-0.001494 , ukdf['amount'].iloc[-1]=147440704.4742, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5764, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '60.176', 'enterprice': '16529.3', 'countrevence': '0', 'unrealprofit': '-641801.1104', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '27194.7', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1


## /root/FIL/strategy/factorcheck/log.txt ----- -----


self.closeSec=1679933999, self.tradeDate='20230328', self.openTime='001500', self.closeTime='001959', self.symbol='BTCUSDT', self.open=27144.8, self.close=27243.2, self.high=27300.0, self.low=27144.8 
127.0.0.1 - - [28/Mar/2023 00:20:02] "POST / HTTP/1.1" 200 -
2023-03-28 00:20:05,471:INFO:factorcheck2:main.py:126:handleKline:185239: self.closeSec=1679933999, self.tradeDate='20230328', self.openTime='001500', self.closeTime='001959',self.symbol='BTCUSDT',self.open=27144.8, self.close=27243.2, self.high=27300.0, self.low=27144.8   
2023-03-28 00:20:06,451:INFO:factorcheck2:main.py:127:handleKline:185239: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime    closeSec  ...      low       pct  index  idx
1439  20230327   235500    235959  1679932799  ...  26864.0 -0.001014   1727    5
1440  20230328   000000    000459  1679933099  ...  26838.8  0.005631   1440    0
1441  20230328   000500    000959  1679933399  ...  27037.2  0.003761   1441    1
1442  20230328   001000    001459  1679933699  ...  27090.0  0.000158   1442    2
1443  20230328   001500    001959  1679933999  ...  27144.8  0.003629   1443    3

[5 rows x 11 columns]
2023-03-28 00:20:06,452:INFO:factorcheck2:main.py:128:handleKline:185239: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=492, self.factor=0.5268721491995723, self.count=35251 

self.closeSec=1679934299, self.tradeDate='20230328', self.openTime='002000', self.closeTime='002459', self.symbol='BTCUSDT', self.open=27243.9, self.close=27202.5, self.high=27246.0, self.low=27170.0 
127.0.0.1 - - [28/Mar/2023 00:25:01] "POST / HTTP/1.1" 200 -
2023-03-28 00:25:01,499:INFO:factorcheck2:main.py:126:handleKline:185239: self.closeSec=1679934299, self.tradeDate='20230328', self.openTime='002000', self.closeTime='002459',self.symbol='BTCUSDT',self.open=27243.9, self.close=27202.5, self.high=27246.0, self.low=27170.0   
2023-03-28 00:25:01,568:INFO:factorcheck2:main.py:127:handleKline:185239: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime    closeSec  ...      low       pct  index  idx
1440  20230328   000000    000459  1679933099  ...  26838.8  0.005631   1440    0
1441  20230328   000500    000959  1679933399  ...  27037.2  0.003761   1441    1
1442  20230328   001000    001459  1679933699  ...  27090.0  0.000158   1442    2
1443  20230328   001500    001959  1679933999  ...  27144.8  0.003629   1443    3
1444  20230328   002000    002459  1679934299  ...  27170.0 -0.001494   1444    4

[5 rows x 11 columns]
2023-03-28 00:25:01,568:INFO:factorcheck2:main.py:128:handleKline:185239: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}


## /root/FIL/strategy/logic/log.txt ----- -----

2023-03-28 00:00:35,862:DEBUG:logic:main.py:463:getModel:885513: df_s.iloc[-5:,:] :
          date closeTime     open  ...    alpha58   alpha67   alpha72
5802  20230327    212959  27738.0  ...  49.166667  0.502712  0.536532
5803  20230327    215959  27770.8  ...  49.166667  0.484818  0.556660
5804  20230327    222959  27677.0  ...  48.750000  0.428995  0.578274
5805  20230327    225959  27329.4  ...  48.333333  0.378295  0.605194
5806  20230327    232959  26933.0  ...  48.333333  0.378427  0.613274

[5 rows x 33 columns]
0.5091911764705882
acc is : 0.5091911764705882
2023-03-28 00:00:36,044:INFO:logic:main.py:468:getModel:885513: df_pred.iloc[-5:,:] :
     pred    prob_0    prob_1  actual  ...       nav  sign   cost_        bm
539     0  0.525157  0.474843       0  ...  1.015326   1.0  0.0000  1.124414
540     1  0.486751  0.513249       0  ...  1.002578   1.0  0.0000  1.110297
541     1  0.410252  0.589748       0  ...  1.015515  -1.0 -0.0016  1.094192
542     1  0.377967  0.622033       1  ...  1.015489  -1.0  0.0000  1.094221
543     1  0.473143  0.526857       0  ...  1.017238  -1.0  0.0000  1.092336

[5 rows x 10 columns]
2023-03-28 00:00:36,081:INFO:logic:main.py:478:getModel:885513: df_panel.iloc[-5:,:] :
    pred    prob_0    prob_1  actual  ...       nav  sign   cost_        bm
45     0  0.525135  0.474865       0  ...  1.046788   1.0  0.0000  1.132257
46     1  0.486297  0.513703       0  ...  1.028369   1.0  0.0000  1.112339
47     1  0.410088  0.589912       0  ...  1.019244  -1.0 -0.0016  1.096205
48     1  0.378256  0.621744       1  ...  1.016957  -1.0  0.0000  1.093808
49     1  0.473143  0.526857       0  ...  1.017238  -1.0  0.0000  1.092336

[5 rows x 10 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': []}


## /root/FIL/strategy/modifiedmom/log.txt ----- -----

127.0.0.1 - - [28/Mar/2023 00:00:03] "POST / HTTP/1.1" 200 -
2023-03-28 00:00:03,416:INFO:modifiedmom:main.py:319:handleOrderFilled:185213: handleOrderFilled: data=OrderType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'clientorderid': '42067F1679932802873I0L59', 'symbol': 'BTCUSDT', 'gatewayorderid': 1679932803115938, 'quantity': '26.526', 'price': '26884.6', 'stopprice': '0', 'ordertype': '', 'side': 'SELL', 'status': 'FILLED', 'positionside': 'SHORT', 'createtime': 1679932802387, 'updatetime': 1679932803115, 'tradetype': 'usdt', 'selfid': 42067, 'filltrades': [TradeType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'tradeid': 1679932803115, 'clientorderid': '42067F1679932802873I0L59', 'price': '26884.6', 'quantity': '26.526', 'commission': '713.1408996', 'commissionasset': 'USDT', 'tradetime': 1679932803115, 'tradetype': 'usdt', 'gatetype': 'simulator', 'handletime': 1679932803115}], 'gatetype': 'simulator', 'handletime': 0}
127.0.0.1 - - [28/Mar/2023 00:10:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=17624 

self.closeSec=1679933399, self.tradeDate='20230328', self.openTime='000000', self.closeTime='000959', self.symbol='BTCUSDT', self.open='26887.3', self.close='27140.4'
2023-03-28 00:10:01,639:INFO:modifiedmom:main.py:144:handleKline:185213: self.closeSec=1679933399, self.tradeDate='20230328', self.openTime='000000', self.closeTime='000959',self.symbol='BTCUSDT',self.open='26887.3', self.close='27140.4'
2023-03-28 00:10:01,681:INFO:modifiedmom:main.py:145:handleKline:185213: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec     open    close       pct
572  20230327   232000    232959  1679930999  26800.4  26933.7  0.005341
573  20230327   233000    233959  1679931599  26934.1  26880.6 -0.001972
574  20230327   234000    234959  1679932199  26880.6  26884.4  0.000141
575  20230327   235000    235959  1679932799  26884.4  26887.3  0.000108
576  20230328   000000    000959  1679933399  26887.3  27140.4  0.009413
2023-03-28 00:10:01,686:INFO:modifiedmom:main.py:146:handleKline:185213: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': True, 'isOpen': False, 'isClose': True, 'isTrig': False}

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=17625 

self.closeSec=1679933999, self.tradeDate='20230328', self.openTime='001000', self.closeTime='001959', self.symbol='BTCUSDT', self.open='27140.4', self.close='27243.8'
127.0.0.1 - - [28/Mar/2023 00:20:04] "POST / HTTP/1.1" 200 -
2023-03-28 00:20:08,001:INFO:modifiedmom:main.py:144:handleKline:185213: self.closeSec=1679933999, self.tradeDate='20230328', self.openTime='001000', self.closeTime='001959',self.symbol='BTCUSDT',self.open='27140.4', self.close='27243.8'
2023-03-28 00:20:08,902:INFO:modifiedmom:main.py:145:handleKline:185213: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec     open    close       pct
573  20230327   233000    233959  1679931599  26934.1  26880.6 -0.001972
574  20230327   234000    234959  1679932199  26880.6  26884.4  0.000141
575  20230327   235000    235959  1679932799  26884.4  26887.3  0.000108
576  20230328   000000    000959  1679933399  26887.3  27140.4  0.009413
577  20230328   001000    001959  1679933999  27140.4  27243.8  0.003810
2023-03-28 00:20:08,911:INFO:modifiedmom:main.py:146:handleKline:185213: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': True, 'isOpen': False, 'isClose': True, 'isTrig': False}


## /root/FIL/strategy/percentile_regression_step2/log.txt ----- -----

127.0.0.1 - - [21/Feb/2023 09:30:01] "POST / HTTP/1.1" 200 -
2023-02-21 09:30:03,026:DEBUG:percentile_regression_step2:main.py:154:get_signal:1265985: df_id.iloc[-5:,:] :
                 daytime     hms    close  ...  pct_10  pct_20  factor
144  2023/02/21 07:00:00  070000  24795.1  ...     NaN     NaN       0
145  2023/02/21 07:30:00  073000  24849.9  ...     NaN     NaN       0
146  2023/02/21 08:00:00  080000  24819.0  ...     NaN     NaN       0
147  2023/02/21 08:30:00  083000  24860.9  ...     NaN     NaN       0
148  2023/02/21 09:00:00  090000  24831.0  ...     NaN     NaN       0

[5 rows x 10 columns]
127.0.0.1 - - [21/Feb/2023 10:00:02] "POST / HTTP/1.1" 200 -
2023-02-21 10:00:03,553:DEBUG:percentile_regression_step2:main.py:154:get_signal:1265985: df_id.iloc[-5:,:] :
                 daytime     hms    close  ...  pct_10  pct_20  factor
144  2023/02/21 07:30:00  073000  24849.9  ...     NaN     NaN       0
145  2023/02/21 08:00:00  080000  24819.0  ...     NaN     NaN       0
146  2023/02/21 08:30:00  083000  24860.9  ...     NaN     NaN       0
147  2023/02/21 09:00:00  090000  24831.0  ...     NaN     NaN       0
148  2023/02/21 09:30:00  093000  24870.0  ...     NaN     NaN       0

[5 rows x 10 columns]
127.0.0.1 - - [21/Feb/2023 10:30:01] "POST / HTTP/1.1" 200 -
2023-02-21 10:30:03,245:DEBUG:percentile_regression_step2:main.py:154:get_signal:1265985: df_id.iloc[-5:,:] :
                 daytime     hms    close  ...  pct_10  pct_20  factor
144  2023/02/21 08:00:00  080000  24819.0  ...     NaN     NaN       0
145  2023/02/21 08:30:00  083000  24860.9  ...     NaN     NaN       0
146  2023/02/21 09:00:00  090000  24831.0  ...     NaN     NaN       0
147  2023/02/21 09:30:00  093000  24870.0  ...     NaN     NaN       0
148  2023/02/21 10:00:00  100000  24936.1  ...     NaN     NaN       0

[5 rows x 10 columns]


## /root/FIL/strategy/pyemd/log.txt ----- -----

2023-03-28 00:00:03,626:INFO:pyemd2:main.py:303:handleOrderFilled:185189: handleOrderFilled: data=OrderType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'clientorderid': '42066F1679932802782I0L57', 'symbol': 'BTCUSDT', 'gatewayorderid': 1679932803121872, 'quantity': '37.889', 'price': '26884.6', 'stopprice': '0', 'ordertype': '', 'side': 'SELL', 'status': 'FILLED', 'positionside': 'SHORT', 'createtime': 1679932802335, 'updatetime': 1679932803121, 'tradetype': 'usdt', 'selfid': 42066, 'filltrades': [TradeType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'tradeid': 1679932803121, 'clientorderid': '42066F1679932802782I0L57', 'price': '26884.6', 'quantity': '37.889', 'commission': '1018.6306094', 'commissionasset': 'USDT', 'tradetime': 1679932803121, 'tradetype': 'usdt', 'gatetype': 'simulator', 'handletime': 1679932803121}], 'gatetype': 'simulator', 'handletime': 0}
127.0.0.1 - - [28/Mar/2023 00:00:03] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=17625 

self.closeSec=1679933399, self.tradeDate='20230328', self.openTime='000000', self.closeTime='000959', self.symbol='BTCUSDT', self.open='26887.3', self.close='27140.4'
2023-03-28 00:10:01,615:INFO:pyemd2:main.py:125:handleKline:185189: self.closeSec=1679933399, self.tradeDate='20230328', self.openTime='000000', self.closeTime='000959',self.symbol='BTCUSDT',self.open='26887.3', self.close='27140.4'
127.0.0.1 - - [28/Mar/2023 00:10:01] "POST / HTTP/1.1" 200 -
2023-03-28 00:10:01,644:INFO:pyemd2:main.py:126:handleKline:185189: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
17420  20230327   232000    232959  1679930999  26800.4  26933.7
17421  20230327   233000    233959  1679931599  26934.1  26880.6
17422  20230327   234000    234959  1679932199  26880.6  26884.4
17423  20230327   235000    235959  1679932799  26884.4  26887.3
17424  20230328   000000    000959  1679933399  26887.3  27140.4
2023-03-28 00:10:01,646:INFO:pyemd2:main.py:127:handleKline:185189: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=17626 

self.closeSec=1679933999, self.tradeDate='20230328', self.openTime='001000', self.closeTime='001959', self.symbol='BTCUSDT', self.open='27140.4', self.close='27243.8'
127.0.0.1 - - [28/Mar/2023 00:20:04] "POST / HTTP/1.1" 200 -
2023-03-28 00:20:11,147:INFO:pyemd2:main.py:125:handleKline:185189: self.closeSec=1679933999, self.tradeDate='20230328', self.openTime='001000', self.closeTime='001959',self.symbol='BTCUSDT',self.open='27140.4', self.close='27243.8'
2023-03-28 00:20:11,281:INFO:pyemd2:main.py:126:handleKline:185189: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
17421  20230327   233000    233959  1679931599  26934.1  26880.6
17422  20230327   234000    234959  1679932199  26880.6  26884.4
17423  20230327   235000    235959  1679932799  26884.4  26887.3
17424  20230328   000000    000959  1679933399  26887.3  27140.4
17425  20230328   001000    001959  1679933999  27140.4  27243.8
2023-03-28 00:20:11,282:INFO:pyemd2:main.py:127:handleKline:185189: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}


## /root/FIL/strategy/similarity/log.txt ----- -----

127.0.0.1 - - [28/Mar/2023 00:00:03] "POST / HTTP/1.1" 200 -
2023-03-28 00:00:03,036:INFO:testStrategy:main.py:308:handleOrderFilled:185174: handleOrderFilled: data=OrderType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'clientorderid': '42065F1679932802564I0L2', 'symbol': 'BTCUSDT', 'gatewayorderid': 1679932802657109, 'quantity': '42.582', 'price': '26884.7', 'stopprice': '0', 'ordertype': '', 'side': 'BUY', 'status': 'FILLED', 'positionside': 'LONG', 'createtime': 1679932802196, 'updatetime': 1679932802657, 'tradetype': 'usdt', 'selfid': 42065, 'filltrades': [TradeType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'tradeid': 1679932802657, 'clientorderid': '42065F1679932802564I0L2', 'price': '26884.7', 'quantity': '42.582', 'commission': '1144.8042954', 'commissionasset': 'USDT', 'tradetime': 1679932802657, 'tradetype': 'usdt', 'gatetype': 'simulator', 'handletime': 1679932802657}], 'gatetype': 'simulator', 'handletime': 0}
127.0.0.1 - - [28/Mar/2023 00:10:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=17625 

self.closeSec=1679933399, self.tradeDate='20230328', self.openTime='000000', self.closeTime='000959', self.symbol='BTCUSDT', self.open='26887.3', self.close='27140.4'
2023-03-28 00:10:01,605:INFO:testStrategy:main.py:101:handleKline:185174: self.closeSec=1679933399, self.tradeDate='20230328', self.openTime='000000', self.closeTime='000959',self.symbol='BTCUSDT',self.open='26887.3', self.close='27140.4'
2023-03-28 00:10:01,642:INFO:testStrategy:main.py:102:handleKline:185174: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
12236  20230327   232000    232959  1679930999  26800.4  26933.7
12237  20230327   233000    233959  1679931599  26934.1  26880.6
12238  20230327   234000    234959  1679932199  26880.6  26884.4
12239  20230327   235000    235959  1679932799  26884.4  26887.3
12240  20230328   000000    000959  1679933399  26887.3  27140.4
2023-03-28 00:10:01,642:INFO:testStrategy:main.py:103:handleKline:185174: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': True, 'isOpen': False, 'isClose': True, 'isTrig': False, 'isCorr': False}

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=17626 

self.closeSec=1679933999, self.tradeDate='20230328', self.openTime='001000', self.closeTime='001959', self.symbol='BTCUSDT', self.open='27140.4', self.close='27243.8'
127.0.0.1 - - [28/Mar/2023 00:20:04] "POST / HTTP/1.1" 200 -
2023-03-28 00:20:10,573:INFO:testStrategy:main.py:101:handleKline:185174: self.closeSec=1679933999, self.tradeDate='20230328', self.openTime='001000', self.closeTime='001959',self.symbol='BTCUSDT',self.open='27140.4', self.close='27243.8'
2023-03-28 00:20:10,950:INFO:testStrategy:main.py:102:handleKline:185174: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
12237  20230327   233000    233959  1679931599  26934.1  26880.6
12238  20230327   234000    234959  1679932199  26880.6  26884.4
12239  20230327   235000    235959  1679932799  26884.4  26887.3
12240  20230328   000000    000959  1679933399  26887.3  27140.4
12241  20230328   001000    001959  1679933999  27140.4  27243.8
2023-03-28 00:20:10,951:INFO:testStrategy:main.py:103:handleKline:185174: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': True, 'isOpen': False, 'isClose': True, 'isTrig': False, 'isCorr': False}


## /root/FIL/strategy/sr_min/log.txt ----- -----

--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=0, self.total=1000000.0, self.flagDict['side']='', self.tradeCount=0, self.count=30682
self.closeSec=1679933999, self.tradeDate='20230328', self.openTime='001500', self.closeTime='001959', self.symbol='BTCUSDT', self.open=27144.8, self.close=27243.2, self.high=27300.0, self.low=27144.8, self.vol=10298.693, self.amt=280468819.6649 
127.0.0.1 - - [28/Mar/2023 00:20:02] "POST / HTTP/1.1" 200 -
2023-03-28 00:20:07,431:INFO:sr_min:main.py:172:handleKline:449472: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5759  20230327   235500    235959  ...         0.0        0.0       0
5760  20230328   000000    000459  ...         0.0        0.0       0
5761  20230328   000500    000959  ...         0.0        0.0       0
5762  20230328   001000    001459  ...         0.0        0.0       0
5763  20230328   001500    001959  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-03-28 00:20:07,481:INFO:sr_min:main.py:175:handleKline:449472: self.closeSec=1679933999, self.tradeDate='20230328', self.openTime='001500', self.closeTime='001959',self.symbol='BTCUSDT',self.open=27144.8, self.close=27243.2, self.high=27300.0, self.low=27144.8, self.vol=10298.693, self.amt=280468819.6649, ukdf['pct'].iloc[-1]=0.003629 , ukdf['amount'].iloc[-1]=280468819.6649, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5763, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': []}
type(curSign)=<class 'int'>, curSign=0, self.sign=0
--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=0, self.total=1000000.0, self.flagDict['side']='', self.tradeCount=0, self.count=30683
self.closeSec=1679934299, self.tradeDate='20230328', self.openTime='002000', self.closeTime='002459', self.symbol='BTCUSDT', self.open=27243.9, self.close=27202.5, self.high=27246.0, self.low=27170.0, self.vol=5419.025, self.amt=147440704.4742 
127.0.0.1 - - [28/Mar/2023 00:25:01] "POST / HTTP/1.1" 200 -
2023-03-28 00:25:01,590:INFO:sr_min:main.py:172:handleKline:449472: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5760  20230328   000000    000459  ...         0.0        0.0       0
5761  20230328   000500    000959  ...         0.0        0.0       0
5762  20230328   001000    001459  ...         0.0        0.0       0
5763  20230328   001500    001959  ...         0.0        0.0       0
5764  20230328   002000    002459  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-03-28 00:25:01,590:INFO:sr_min:main.py:175:handleKline:449472: self.closeSec=1679934299, self.tradeDate='20230328', self.openTime='002000', self.closeTime='002459',self.symbol='BTCUSDT',self.open=27243.9, self.close=27202.5, self.high=27246.0, self.low=27170.0, self.vol=5419.025, self.amt=147440704.4742, ukdf['pct'].iloc[-1]=-0.001494 , ukdf['amount'].iloc[-1]=147440704.4742, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5764, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': []}
type(curSign)=<class 'int'>, curSign=0, self.sign=0


## /root/FIL/strategy/s_rsrs/log.txt ----- -----

723  20230327   120000    155959  1679903999  ...    723  0.136958 -1.101054    -1.0
724  20230327   160000    195959  1679918399  ...    724  0.110154 -1.139628    -1.0

[5 rows x 15 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '53.706', 'enterprice': '28091.1', 'countrevence': '0', 'unrealprofit': '11308.51118323986', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '27880.53672619', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'numpy.int64'>, curSign=-1, self.sign=-1
--handleKline--:  version='2.0.0', self.name='s_rsrs', self.symbol='BTCUSDT', interval='4h', intervalSec=14400, wid=25, thd=0.6, self.sign=-1, self.total=1507151.9559834, self.flagDict['side']='sell', self.tradeCount=27, self.count=734
self.closeSec=1679932799, self.tradeDate='20230327', self.openTime='200000', self.closeTime='235959', self.symbol='BTCUSDT', self.open=27879.9, self.close=26887.3, self.high=27917.4, self.low=26480.0, self.vol=308699.095, self.amt=8393002104.32141 
127.0.0.1 - - [28/Mar/2023 00:00:01] "POST / HTTP/1.1" 200 -
2023-03-28 00:00:01,783:INFO:s_rsrs:main.py:141:handleKline:185271: self.closeSec=1679932799, self.tradeDate='20230327', self.openTime='200000', self.closeTime='235959',self.symbol='BTCUSDT',self.open=27879.9, self.close=26887.3, self.high=27917.4, self.low=26480.0, self.vol=308699.095, self.amt=8393002104.32141 
2023-03-28 00:00:01,846:INFO:s_rsrs:main.py:142:handleKline:185271: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime  ...         vol           amt       pct
721  20230327   040000    075959  ...   67164.517  1.875763e+09  0.005041
722  20230327   080000    115959  ...   44345.130  1.236390e+09 -0.002715
723  20230327   120000    155959  ...   50007.614  1.389256e+09 -0.003009
724  20230327   160000    195959  ...   51239.037  1.428795e+09  0.003073
725  20230327   200000    235959  ...  308699.095  8.393002e+09 -0.035603

[5 rows x 11 columns]
2023-03-28 00:00:04,425:INFO:s_rsrs:main.py:151:handleKline:185271: df_s.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec  ...  index      beta    zscore  signal
721  20230327   040000    075959  1679875199  ...    721  0.210632 -0.969475    -1.0
722  20230327   080000    115959  1679889599  ...    722  0.191668 -0.994625    -1.0
723  20230327   120000    155959  1679903999  ...    723  0.136958 -1.101054    -1.0
724  20230327   160000    195959  1679918399  ...    724  0.110154 -1.139628    -1.0
725  20230327   200000    235959  1679932799  ...    725  0.038575 -1.277641    -1.0

[5 rows x 15 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '53.706', 'enterprice': '28091.1', 'countrevence': '0', 'unrealprofit': '64790.9184', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '26884.7', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'numpy.int64'>, curSign=-1, self.sign=-1


