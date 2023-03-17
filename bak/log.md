# 20230318 00:26:01

## /root/FIL/strategy/amihud/log.txt ----- -----

--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=993672.4896432, self.flagDict['side']='sell', self.tradeCount=2, self.count=31804127.0.0.1 - - [18/Mar/2023 00:20:01] "POST / HTTP/1.1" 200 -

self.closeSec=1679069999, self.tradeDate='20230318', self.openTime='001500', self.closeTime='001959', self.symbol='BTCUSDT', self.open=26506.5, self.close=26465.0, self.high=26525.1, self.low=26440.0, self.vol=3648.713, self.amt=96640493.4864 
2023-03-18 00:20:01,912:INFO:amihud:main.py:172:handleKline:200676: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5759  20230317   235500    235959  ...         0.0        0.0       0
5760  20230318   000000    000459  ...         0.0        0.0       0
5761  20230318   000500    000959  ...         0.0        0.0       0
5762  20230318   001000    001459  ...         0.0        0.0       0
5763  20230318   001500    001959  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-03-18 00:20:01,918:INFO:amihud:main.py:175:handleKline:200676: self.closeSec=1679069999, self.tradeDate='20230318', self.openTime='001500', self.closeTime='001959',self.symbol='BTCUSDT',self.open=26506.5, self.close=26465.0, self.high=26525.1, self.low=26440.0, self.vol=3648.713, self.amt=96640493.4864, ukdf['pct'].iloc[-1]=-0.001562 , ukdf['amount'].iloc[-1]=96640493.4864, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5763, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '60.176', 'enterprice': '16529.3', 'countrevence': '0', 'unrealprofit': '-597832.8742139336', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '26464.03933485', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1
--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=993672.4896432, self.flagDict['side']='sell', self.tradeCount=2, self.count=31805
self.closeSec=1679070299, self.tradeDate='20230318', self.openTime='002000', self.closeTime='002459', self.symbol='BTCUSDT', self.open=26465.0, self.close=26400.1, self.high=26495.7, self.low=26381.6, self.vol=2812.764, self.amt=74317534.5928 
127.0.0.1 - - [18/Mar/2023 00:25:01] "POST / HTTP/1.1" 200 -
2023-03-18 00:25:01,621:INFO:amihud:main.py:172:handleKline:200676: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5760  20230318   000000    000459  ...         0.0        0.0       0
5761  20230318   000500    000959  ...         0.0        0.0       0
5762  20230318   001000    001459  ...         0.0        0.0       0
5763  20230318   001500    001959  ...         0.0        0.0       0
5764  20230318   002000    002459  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-03-18 00:25:01,622:INFO:amihud:main.py:175:handleKline:200676: self.closeSec=1679070299, self.tradeDate='20230318', self.openTime='002000', self.closeTime='002459',self.symbol='BTCUSDT',self.open=26465.0, self.close=26400.1, self.high=26495.7, self.low=26381.6, self.vol=2812.764, self.amt=74317534.5928, ukdf['pct'].iloc[-1]=-0.002452 , ukdf['amount'].iloc[-1]=74317534.5928, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5764, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '60.176', 'enterprice': '16529.3', 'countrevence': '0', 'unrealprofit': '-593840.8384', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '26397.7', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1


## /root/FIL/strategy/factorcheck/log.txt ----- -----

 version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=12, self.factor=0.2566324753224135, self.count=32370 

self.closeSec=1679069999, self.tradeDate='20230318', self.openTime='001500', self.closeTime='001959', self.symbol='BTCUSDT', self.open=26506.5, self.close=26465.0, self.high=26525.1, self.low=26440.0 
2023-03-18 00:20:01,536:INFO:factorcheck2:main.py:126:handleKline:185239: self.closeSec=1679069999, self.tradeDate='20230318', self.openTime='001500', self.closeTime='001959',self.symbol='BTCUSDT',self.open=26506.5, self.close=26465.0, self.high=26525.1, self.low=26440.0   
2023-03-18 00:20:01,603:INFO:factorcheck2:main.py:127:handleKline:185239: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime    closeSec  ...      low       pct  index  idx
1439  20230317   235500    235959  1679068799  ...  26360.0  0.001498   1727    5
1440  20230318   000000    000459  1679069099  ...  26385.7  0.000776   1440    0
1441  20230318   000500    000959  1679069399  ...  26384.1  0.001347   1441    1
1442  20230318   001000    001459  1679069699  ...  26420.1  0.001299   1442    2
1443  20230318   001500    001959  1679069999  ...  26440.0 -0.001562   1443    3

[5 rows x 11 columns]
2023-03-18 00:20:01,603:INFO:factorcheck2:main.py:128:handleKline:185239: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}
127.0.0.1 - - [18/Mar/2023 00:25:01] "POST / HTTP/1.1" 200 -

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=12, self.factor=0.2566324753224135, self.count=32371 

self.closeSec=1679070299, self.tradeDate='20230318', self.openTime='002000', self.closeTime='002459', self.symbol='BTCUSDT', self.open=26465.0, self.close=26400.1, self.high=26495.7, self.low=26381.6 
2023-03-18 00:25:01,522:INFO:factorcheck2:main.py:126:handleKline:185239: self.closeSec=1679070299, self.tradeDate='20230318', self.openTime='002000', self.closeTime='002459',self.symbol='BTCUSDT',self.open=26465.0, self.close=26400.1, self.high=26495.7, self.low=26381.6   
2023-03-18 00:25:01,600:INFO:factorcheck2:main.py:127:handleKline:185239: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime    closeSec  ...      low       pct  index  idx
1440  20230318   000000    000459  1679069099  ...  26385.7  0.000776   1440    0
1441  20230318   000500    000959  1679069399  ...  26384.1  0.001347   1441    1
1442  20230318   001000    001459  1679069699  ...  26420.1  0.001299   1442    2
1443  20230318   001500    001959  1679069999  ...  26440.0 -0.001562   1443    3
1444  20230318   002000    002459  1679070299  ...  26381.6 -0.002452   1444    4

[5 rows x 11 columns]
2023-03-18 00:25:01,600:INFO:factorcheck2:main.py:128:handleKline:185239: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}


## /root/FIL/strategy/logic/log.txt ----- -----

2023-03-18 00:00:34,633:DEBUG:logic:main.py:463:getModel:885513: df_s.iloc[-5:,:] :
          date closeTime     open  ...    alpha58   alpha67   alpha72
5802  20230317    212959  26631.0  ...  52.083333  0.630769  0.137326
5803  20230317    215959  26592.9  ...  52.083333  0.614801  0.142871
5804  20230317    222959  26453.2  ...  52.083333  0.607710  0.149888
5805  20230317    225959  26392.4  ...  52.083333  0.595765  0.159451
5806  20230317    232959  26280.0  ...  52.083333  0.597896  0.167580

[5 rows x 33 columns]
0.5551470588235294
acc is : 0.5551470588235294
2023-03-18 00:00:34,811:INFO:logic:main.py:468:getModel:885513: df_pred.iloc[-5:,:] :
     pred    prob_0    prob_1  actual  ...       nav  sign  cost_        bm
539     1  0.468413  0.531587       0  ...  1.173748  -1.0    0.0  1.181954
540     1  0.424871  0.575129       0  ...  1.176548  -1.0    0.0  1.179135
541     1  0.415524  0.584476       0  ...  1.181341  -1.0    0.0  1.174332
542     1  0.421578  0.578422       1  ...  1.180064  -1.0    0.0  1.175601
543     1  0.466122  0.533878       1  ...  1.175507  -1.0    0.0  1.180140

[5 rows x 10 columns]
2023-03-18 00:00:34,849:INFO:logic:main.py:478:getModel:885513: df_panel.iloc[-5:,:] :
    pred    prob_0    prob_1  actual  ...       nav  sign  cost_        bm
45     1  0.468164  0.531836       0  ...  1.173748  -1.0    0.0  1.180367
46     1  0.424961  0.575039       0  ...  1.176548  -1.0    0.0  1.178240
47     1  0.415630  0.584370       0  ...  1.181341  -1.0    0.0  1.173440
48     1  0.421500  0.578500       1  ...  1.180064  -1.0    0.0  1.173922
49     1  0.466122  0.533878       1  ...  1.175507  -1.0    0.0  1.180140

[5 rows x 10 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': []}


## /root/FIL/strategy/modifiedmom/log.txt ----- -----

127.0.0.1 - - [18/Mar/2023 00:00:02] "POST / HTTP/1.1" 200 -
2023-03-18 00:00:02,995:INFO:modifiedmom:main.py:319:handleOrderFilled:185213: handleOrderFilled: data=OrderType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'clientorderid': '42012F1679068802583I0L59', 'symbol': 'BTCUSDT', 'gatewayorderid': 1679068802707532, 'quantity': '32.189', 'price': '26416.2', 'stopprice': '0', 'ordertype': '', 'side': 'BUY', 'status': 'FILLED', 'positionside': 'LONG', 'createtime': 1679068802200, 'updatetime': 1679068802707, 'tradetype': 'usdt', 'selfid': 42012, 'filltrades': [TradeType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'tradeid': 1679068802707, 'clientorderid': '42012F1679068802583I0L59', 'price': '26416.2', 'quantity': '32.189', 'commission': '850.3110618', 'commissionasset': 'USDT', 'tradetime': 1679068802707, 'tradetype': 'usdt', 'gatetype': 'simulator', 'handletime': 1679068802707}], 'gatetype': 'simulator', 'handletime': 0}
127.0.0.1 - - [18/Mar/2023 00:10:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=16184 

self.closeSec=1679069399, self.tradeDate='20230318', self.openTime='000000', self.closeTime='000959', self.symbol='BTCUSDT', self.open='26412.7', self.close='26472'
2023-03-18 00:10:01,925:INFO:modifiedmom:main.py:144:handleKline:185213: self.closeSec=1679069399, self.tradeDate='20230318', self.openTime='000000', self.closeTime='000959',self.symbol='BTCUSDT',self.open='26412.7', self.close='26472'
2023-03-18 00:10:01,959:INFO:modifiedmom:main.py:145:handleKline:185213: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec     open    close       pct
572  20230317   232000    232959  1679066999  26478.7    26311 -0.006330
573  20230317   233000    233959  1679067599  26310.9  26348.7  0.001433
574  20230317   234000    234959  1679068199  26348.7  26348.2 -0.000019
575  20230317   235000    235959  1679068799  26349.9  26412.6  0.002444
576  20230318   000000    000959  1679069399  26412.7    26472  0.002249
2023-03-18 00:10:01,959:INFO:modifiedmom:main.py:146:handleKline:185213: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': True, 'isOpen': False, 'isClose': True, 'isTrig': False}
127.0.0.1 - - [18/Mar/2023 00:20:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=16185 

self.closeSec=1679069999, self.tradeDate='20230318', self.openTime='001000', self.closeTime='001959', self.symbol='BTCUSDT', self.open='26470.9', self.close='26465'
2023-03-18 00:20:01,965:INFO:modifiedmom:main.py:144:handleKline:185213: self.closeSec=1679069999, self.tradeDate='20230318', self.openTime='001000', self.closeTime='001959',self.symbol='BTCUSDT',self.open='26470.9', self.close='26465'
2023-03-18 00:20:02,143:INFO:modifiedmom:main.py:145:handleKline:185213: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec     open    close       pct
573  20230317   233000    233959  1679067599  26310.9  26348.7  0.001433
574  20230317   234000    234959  1679068199  26348.7  26348.2 -0.000019
575  20230317   235000    235959  1679068799  26349.9  26412.6  0.002444
576  20230318   000000    000959  1679069399  26412.7    26472  0.002249
577  20230318   001000    001959  1679069999  26470.9    26465 -0.000264
2023-03-18 00:20:02,143:INFO:modifiedmom:main.py:146:handleKline:185213: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': True, 'isOpen': False, 'isClose': True, 'isTrig': False}


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

2023-03-18 00:00:01,943:INFO:pyemd2:main.py:127:handleKline:185189: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}
2023-03-18 00:00:02,130:INFO:pyemd2:main.py:190:insertFactor:185189: curDateTime:3180000, name:pyemd2, symbol:BTCUSDT, tradeDate:20230317, closeTime:235959, close:26412.6, total:1054769.6042238, pct_pre:0.057322170672621464, thd:-0.8660331277292783, side:sell 
127.0.0.1 - - [18/Mar/2023 00:10:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=16185 

self.closeSec=1679069399, self.tradeDate='20230318', self.openTime='000000', self.closeTime='000959', self.symbol='BTCUSDT', self.open='26412.7', self.close='26472'
2023-03-18 00:10:01,939:INFO:pyemd2:main.py:125:handleKline:185189: self.closeSec=1679069399, self.tradeDate='20230318', self.openTime='000000', self.closeTime='000959',self.symbol='BTCUSDT',self.open='26412.7', self.close='26472'
2023-03-18 00:10:01,980:INFO:pyemd2:main.py:126:handleKline:185189: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
17420  20230317   232000    232959  1679066999  26478.7    26311
17421  20230317   233000    233959  1679067599  26310.9  26348.7
17422  20230317   234000    234959  1679068199  26348.7  26348.2
17423  20230317   235000    235959  1679068799  26349.9  26412.6
17424  20230318   000000    000959  1679069399  26412.7    26472
2023-03-18 00:10:01,980:INFO:pyemd2:main.py:127:handleKline:185189: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=16186 

self.closeSec=1679069999, self.tradeDate='20230318', self.openTime='001000', self.closeTime='001959', self.symbol='BTCUSDT', self.open='26470.9', self.close='26465'
127.0.0.1 - - [18/Mar/2023 00:20:01] "POST / HTTP/1.1" 200 -
2023-03-18 00:20:02,490:INFO:pyemd2:main.py:125:handleKline:185189: self.closeSec=1679069999, self.tradeDate='20230318', self.openTime='001000', self.closeTime='001959',self.symbol='BTCUSDT',self.open='26470.9', self.close='26465'
2023-03-18 00:20:02,594:INFO:pyemd2:main.py:126:handleKline:185189: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
17421  20230317   233000    233959  1679067599  26310.9  26348.7
17422  20230317   234000    234959  1679068199  26348.7  26348.2
17423  20230317   235000    235959  1679068799  26349.9  26412.6
17424  20230318   000000    000959  1679069399  26412.7    26472
17425  20230318   001000    001959  1679069999  26470.9    26465
2023-03-18 00:20:02,594:INFO:pyemd2:main.py:127:handleKline:185189: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}


## /root/FIL/strategy/similarity/log.txt ----- -----

127.0.0.1 - - [18/Mar/2023 00:00:03] "POST / HTTP/1.1" 200 -
2023-03-18 00:00:03,386:INFO:testStrategy:main.py:308:handleOrderFilled:185174: handleOrderFilled: data=OrderType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'clientorderid': '42013F1679068802890I0L2', 'symbol': 'BTCUSDT', 'gatewayorderid': 1679068803080231, 'quantity': '48.027', 'price': '26416.2', 'stopprice': '0', 'ordertype': '', 'side': 'BUY', 'status': 'FILLED', 'positionside': 'LONG', 'createtime': 1679068802378, 'updatetime': 1679068803080, 'tradetype': 'usdt', 'selfid': 42013, 'filltrades': [TradeType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'tradeid': 1679068803080, 'clientorderid': '42013F1679068802890I0L2', 'price': '26416.2', 'quantity': '48.027', 'commission': '1268.6908374', 'commissionasset': 'USDT', 'tradetime': 1679068803080, 'tradetype': 'usdt', 'gatetype': 'simulator', 'handletime': 1679068803080}], 'gatetype': 'simulator', 'handletime': 0}
127.0.0.1 - - [18/Mar/2023 00:10:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=16185 

self.closeSec=1679069399, self.tradeDate='20230318', self.openTime='000000', self.closeTime='000959', self.symbol='BTCUSDT', self.open='26412.7', self.close='26472'
2023-03-18 00:10:01,894:INFO:testStrategy:main.py:101:handleKline:185174: self.closeSec=1679069399, self.tradeDate='20230318', self.openTime='000000', self.closeTime='000959',self.symbol='BTCUSDT',self.open='26412.7', self.close='26472'
2023-03-18 00:10:01,919:INFO:testStrategy:main.py:102:handleKline:185174: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
12236  20230317   232000    232959  1679066999  26478.7    26311
12237  20230317   233000    233959  1679067599  26310.9  26348.7
12238  20230317   234000    234959  1679068199  26348.7  26348.2
12239  20230317   235000    235959  1679068799  26349.9  26412.6
12240  20230318   000000    000959  1679069399  26412.7    26472
2023-03-18 00:10:01,920:INFO:testStrategy:main.py:103:handleKline:185174: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': True, 'isOpen': False, 'isClose': True, 'isTrig': False, 'isCorr': False}

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=16186 

self.closeSec=1679069999, self.tradeDate='20230318', self.openTime='001000', self.closeTime='001959', self.symbol='BTCUSDT', self.open='26470.9', self.close='26465'
127.0.0.1 - - [18/Mar/2023 00:20:01] "POST / HTTP/1.1" 200 -
2023-03-18 00:20:02,377:INFO:testStrategy:main.py:101:handleKline:185174: self.closeSec=1679069999, self.tradeDate='20230318', self.openTime='001000', self.closeTime='001959',self.symbol='BTCUSDT',self.open='26470.9', self.close='26465'
2023-03-18 00:20:02,482:INFO:testStrategy:main.py:102:handleKline:185174: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
12237  20230317   233000    233959  1679067599  26310.9  26348.7
12238  20230317   234000    234959  1679068199  26348.7  26348.2
12239  20230317   235000    235959  1679068799  26349.9  26412.6
12240  20230318   000000    000959  1679069399  26412.7    26472
12241  20230318   001000    001959  1679069999  26470.9    26465
2023-03-18 00:20:02,482:INFO:testStrategy:main.py:103:handleKline:185174: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': True, 'isOpen': False, 'isClose': True, 'isTrig': False, 'isCorr': False}


## /root/FIL/strategy/sr_min/log.txt ----- -----

127.0.0.1 - - [18/Mar/2023 00:20:01] "POST / HTTP/1.1" 200 -
--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=0, self.total=1000000.0, self.flagDict['side']='', self.tradeCount=0, self.count=27802
self.closeSec=1679069999, self.tradeDate='20230318', self.openTime='001500', self.closeTime='001959', self.symbol='BTCUSDT', self.open=26506.5, self.close=26465.0, self.high=26525.1, self.low=26440.0, self.vol=3648.713, self.amt=96640493.4864 
2023-03-18 00:20:01,596:INFO:sr_min:main.py:172:handleKline:449472: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5759  20230317   235500    235959  ...         0.0        0.0       0
5760  20230318   000000    000459  ...         0.0        0.0       0
5761  20230318   000500    000959  ...         0.0        0.0       0
5762  20230318   001000    001459  ...         0.0        0.0       0
5763  20230318   001500    001959  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-03-18 00:20:01,604:INFO:sr_min:main.py:175:handleKline:449472: self.closeSec=1679069999, self.tradeDate='20230318', self.openTime='001500', self.closeTime='001959',self.symbol='BTCUSDT',self.open=26506.5, self.close=26465.0, self.high=26525.1, self.low=26440.0, self.vol=3648.713, self.amt=96640493.4864, ukdf['pct'].iloc[-1]=-0.001562 , ukdf['amount'].iloc[-1]=96640493.4864, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5763, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': []}
type(curSign)=<class 'int'>, curSign=0, self.sign=0
127.0.0.1 - - [18/Mar/2023 00:25:01] "POST / HTTP/1.1" 200 -
--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=0, self.total=1000000.0, self.flagDict['side']='', self.tradeCount=0, self.count=27803
self.closeSec=1679070299, self.tradeDate='20230318', self.openTime='002000', self.closeTime='002459', self.symbol='BTCUSDT', self.open=26465.0, self.close=26400.1, self.high=26495.7, self.low=26381.6, self.vol=2812.764, self.amt=74317534.5928 
2023-03-18 00:25:01,647:INFO:sr_min:main.py:172:handleKline:449472: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5760  20230318   000000    000459  ...         0.0        0.0       0
5761  20230318   000500    000959  ...         0.0        0.0       0
5762  20230318   001000    001459  ...         0.0        0.0       0
5763  20230318   001500    001959  ...         0.0        0.0       0
5764  20230318   002000    002459  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-03-18 00:25:01,647:INFO:sr_min:main.py:175:handleKline:449472: self.closeSec=1679070299, self.tradeDate='20230318', self.openTime='002000', self.closeTime='002459',self.symbol='BTCUSDT',self.open=26465.0, self.close=26400.1, self.high=26495.7, self.low=26381.6, self.vol=2812.764, self.amt=74317534.5928, ukdf['pct'].iloc[-1]=-0.002452 , ukdf['amount'].iloc[-1]=74317534.5928, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5764, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': []}
type(curSign)=<class 'int'>, curSign=0, self.sign=0


## /root/FIL/strategy/s_rsrs/log.txt ----- -----

2023-03-17 20:00:11,204:INFO:s_rsrs:main.py:343:handleOrderNew:185271: handleOrderNew: data=OrderType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'clientorderid': '42010F1679054405898I0L65', 'symbol': 'BTCUSDT', 'gatewayorderid': 1679054406001588, 'quantity': '55.825', 'price': '26922.2', 'stopprice': '0', 'ordertype': '', 'side': 'SELL', 'status': 'FILLED', 'positionside': 'SHORT', 'createtime': 1679054405425, 'updatetime': 1679054406001, 'tradetype': 'usdt', 'selfid': 42010, 'filltrades': [TradeType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'tradeid': 1679054406001, 'clientorderid': '42010F1679054405898I0L65', 'price': '26922.2', 'quantity': '55.825', 'commission': '1502.931815', 'commissionasset': 'USDT', 'tradetime': 1679054406001, 'tradetype': 'usdt', 'gatetype': 'simulator', 'handletime': 1679054406001}], 'gatetype': 'simulator', 'handletime': 0}
2023-03-17 20:00:11,204:INFO:s_rsrs:main.py:346:handleOrderFilled:185271: handleOrderFilled: data=OrderType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'clientorderid': '42010F1679054405898I0L65', 'symbol': 'BTCUSDT', 'gatewayorderid': 1679054406001588, 'quantity': '55.825', 'price': '26922.2', 'stopprice': '0', 'ordertype': '', 'side': 'SELL', 'status': 'FILLED', 'positionside': 'SHORT', 'createtime': 1679054405425, 'updatetime': 1679054406001, 'tradetype': 'usdt', 'selfid': 42010, 'filltrades': [TradeType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'tradeid': 1679054406001, 'clientorderid': '42010F1679054405898I0L65', 'price': '26922.2', 'quantity': '55.825', 'commission': '1502.931815', 'commissionasset': 'USDT', 'tradetime': 1679054406001, 'tradetype': 'usdt', 'gatetype': 'simulator', 'handletime': 1679054406001}], 'gatetype': 'simulator', 'handletime': 0}
127.0.0.1 - - [17/Mar/2023 20:00:11] "POST / HTTP/1.1" 200 -
2023-03-17 20:00:11,297:INFO:s_rsrs:main.py:343:handleOrderNew:185271: handleOrderNew: data=OrderType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'clientorderid': '42011F1679054411175I0L65', 'symbol': 'BTCUSDT', 'gatewayorderid': 1679054411269319, 'quantity': '55.764', 'price': '26915.4', 'stopprice': '0', 'ordertype': '', 'side': 'SELL', 'status': 'FILLED', 'positionside': 'SHORT', 'createtime': 1679054410994, 'updatetime': 1679054411269, 'tradetype': 'usdt', 'selfid': 42011, 'filltrades': [TradeType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'tradeid': 1679054411269, 'clientorderid': '42011F1679054411175I0L65', 'price': '26915.4', 'quantity': '55.764', 'commission': '1500.9103656', 'commissionasset': 'USDT', 'tradetime': 1679054411269, 'tradetype': 'usdt', 'gatetype': 'simulator', 'handletime': 1679054411269}], 'gatetype': 'simulator', 'handletime': 0}
127.0.0.1 - - [17/Mar/2023 20:00:11] "POST / HTTP/1.1" 200 -
2023-03-17 20:00:11,480:INFO:s_rsrs:main.py:346:handleOrderFilled:185271: handleOrderFilled: data=OrderType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'clientorderid': '42011F1679054411175I0L65', 'symbol': 'BTCUSDT', 'gatewayorderid': 1679054411269319, 'quantity': '55.764', 'price': '26915.4', 'stopprice': '0', 'ordertype': '', 'side': 'SELL', 'status': 'FILLED', 'positionside': 'SHORT', 'createtime': 1679054410994, 'updatetime': 1679054411269, 'tradetype': 'usdt', 'selfid': 42011, 'filltrades': [TradeType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'tradeid': 1679054411269, 'clientorderid': '42011F1679054411175I0L65', 'price': '26915.4', 'quantity': '55.764', 'commission': '1500.9103656', 'commissionasset': 'USDT', 'tradetime': 1679054411269, 'tradetype': 'usdt', 'gatetype': 'simulator', 'handletime': 1679054411269}], 'gatetype': 'simulator', 'handletime': 0}
127.0.0.1 - - [18/Mar/2023 00:00:01] "POST / HTTP/1.1" 200 -
--handleKline--:  version='2.0.0', self.name='s_rsrs', self.symbol='BTCUSDT', interval='4h', intervalSec=14400, wid=25, thd=0.6, self.sign=-1, self.total=1499409.4552344002, self.flagDict['side']='sell', self.tradeCount=25, self.count=674
self.closeSec=1679068799, self.tradeDate='20230317', self.openTime='200000', self.closeTime='235959', self.symbol='BTCUSDT', self.open=26914.1, self.close=26412.6, self.high=26930.0, self.low=26120.0, self.vol=264742.761, self.amt=7010303216.71982 
2023-03-18 00:00:01,836:INFO:s_rsrs:main.py:141:handleKline:185271: self.closeSec=1679068799, self.tradeDate='20230317', self.openTime='200000', self.closeTime='235959',self.symbol='BTCUSDT',self.open=26914.1, self.close=26412.6, self.high=26930.0, self.low=26120.0, self.vol=264742.761, self.amt=7010303216.71982 
2023-03-18 00:00:01,901:INFO:s_rsrs:main.py:142:handleKline:185271: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime  ...         vol           amt       pct
721  20230317   040000    075959  ...   91673.471  2.279733e+09  0.001784
722  20230317   080000    115959  ...  202957.831  5.176549e+09  0.031192
723  20230317   120000    155959  ...  159158.385  4.126135e+09  0.010749
724  20230317   160000    195959  ...  276532.318  7.318397e+09  0.033202
725  20230317   200000    235959  ...  264742.761  7.010303e+09 -0.018546

[5 rows x 11 columns]
2023-03-18 00:00:04,602:INFO:s_rsrs:main.py:151:handleKline:185271: df_s.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec  ...  index      beta    zscore  signal
721  20230317   040000    075959  1679011199  ...    721  0.510269 -0.305711     NaN
722  20230317   080000    115959  1679025599  ...    722  0.513413 -0.289174     NaN
723  20230317   120000    155959  1679039999  ...    723  0.437985 -0.501484     NaN
724  20230317   160000    195959  1679054399  ...    724  0.393393 -0.626256    -1.0
725  20230317   200000    235959  1679068799  ...    725  0.301906 -0.883417    -1.0

[5 rows x 15 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '55.764', 'enterprice': '26915.4', 'countrevence': '0', 'unrealprofit': '27837.3888', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '26416.2', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'numpy.int64'>, curSign=-1, self.sign=-1


