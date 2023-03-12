# 20230313 00:26:02

## /root/FIL/strategy/amihud/log.txt ----- -----

--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=993672.4896432, self.flagDict['side']='sell', self.tradeCount=2, self.count=30364
self.closeSec=1678637999, self.tradeDate='20230313', self.openTime='001500', self.closeTime='001959', self.symbol='BTCUSDT', self.open=20354.3, self.close=20358.0, self.high=20364.5, self.low=20332.5, self.vol=1150.027, self.amt=23402703.358 
127.0.0.1 - - [13/Mar/2023 00:20:02] "POST / HTTP/1.1" 200 -
2023-03-13 00:20:05,754:INFO:amihud:main.py:172:handleKline:200676: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5759  20230312   235500    235959  ...         0.0        0.0       0
5760  20230313   000000    000459  ...         0.0        0.0       0
5761  20230313   000500    000959  ...         0.0        0.0       0
5762  20230313   001000    001459  ...         0.0        0.0       0
5763  20230313   001500    001959  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-03-13 00:20:05,775:INFO:amihud:main.py:175:handleKline:200676: self.closeSec=1678637999, self.tradeDate='20230313', self.openTime='001500', self.closeTime='001959',self.symbol='BTCUSDT',self.open=20354.3, self.close=20358.0, self.high=20364.5, self.low=20332.5, self.vol=1150.027, self.amt=23402703.358, ukdf['pct'].iloc[-1]=0.000187 , ukdf['amount'].iloc[-1]=23402703.358, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5763, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '60.176', 'enterprice': '16529.3', 'countrevence': '0', 'unrealprofit': '-230438.90606348656', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '20358.71548231', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1
--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=993672.4896432, self.flagDict['side']='sell', self.tradeCount=2, self.count=30365
self.closeSec=1678638299, self.tradeDate='20230313', self.openTime='002000', self.closeTime='002459', self.symbol='BTCUSDT', self.open=20357.9, self.close=20370.2, self.high=20379.2, self.low=20355.0, self.vol=822.921, self.amt=16760204.6001 
127.0.0.1 - - [13/Mar/2023 00:25:01] "POST / HTTP/1.1" 200 -
2023-03-13 00:25:01,599:INFO:amihud:main.py:172:handleKline:200676: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5760  20230313   000000    000459  ...         0.0        0.0       0
5761  20230313   000500    000959  ...         0.0        0.0       0
5762  20230313   001000    001459  ...         0.0        0.0       0
5763  20230313   001500    001959  ...         0.0        0.0       0
5764  20230313   002000    002459  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-03-13 00:25:01,602:INFO:amihud:main.py:175:handleKline:200676: self.closeSec=1678638299, self.tradeDate='20230313', self.openTime='002000', self.closeTime='002459',self.symbol='BTCUSDT',self.open=20357.9, self.close=20370.2, self.high=20379.2, self.low=20355.0, self.vol=822.921, self.amt=16760204.6001, ukdf['pct'].iloc[-1]=0.000599 , ukdf['amount'].iloc[-1]=16760204.6001, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5764, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '60.176', 'enterprice': '16529.3', 'countrevence': '0', 'unrealprofit': '-231129.9984', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '20370.2', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1


## /root/FIL/strategy/factorcheck/log.txt ----- -----

 version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=39, self.factor=0.3833782278373514, self.count=30930 

self.closeSec=1678637999, self.tradeDate='20230313', self.openTime='001500', self.closeTime='001959', self.symbol='BTCUSDT', self.open=20354.3, self.close=20358.0, self.high=20364.5, self.low=20332.5 
2023-03-13 00:20:01,930:INFO:factorcheck2:main.py:126:handleKline:185239: self.closeSec=1678637999, self.tradeDate='20230313', self.openTime='001500', self.closeTime='001959',self.symbol='BTCUSDT',self.open=20354.3, self.close=20358.0, self.high=20364.5, self.low=20332.5   
2023-03-13 00:20:02,509:INFO:factorcheck2:main.py:127:handleKline:185239: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime    closeSec  ...      low       pct  index  idx
1439  20230312   235500    235959  1678636799  ...  20346.8 -0.000074   1727    5
1440  20230313   000000    000459  1678637099  ...  20333.8 -0.000295   1440    0
1441  20230313   000500    000959  1678637399  ...  20341.9  0.000973   1441    1
1442  20230313   001000    001459  1678637699  ...  20353.6 -0.000368   1442    2
1443  20230313   001500    001959  1678637999  ...  20332.5  0.000187   1443    3

[5 rows x 11 columns]
2023-03-13 00:20:02,510:INFO:factorcheck2:main.py:128:handleKline:185239: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': True, 'isOpenSell': False, 'isCloseBuy': False, 'isCloseSell': False, 'isOpen': True, 'isClose': False, 'isTrig': True}

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=39, self.factor=0.3833782278373514, self.count=30931 

self.closeSec=1678638299, self.tradeDate='20230313', self.openTime='002000', self.closeTime='002459', self.symbol='BTCUSDT', self.open=20357.9, self.close=20370.2, self.high=20379.2, self.low=20355.0 
127.0.0.1 - - [13/Mar/2023 00:25:01] "POST / HTTP/1.1" 200 -
2023-03-13 00:25:01,507:INFO:factorcheck2:main.py:126:handleKline:185239: self.closeSec=1678638299, self.tradeDate='20230313', self.openTime='002000', self.closeTime='002459',self.symbol='BTCUSDT',self.open=20357.9, self.close=20370.2, self.high=20379.2, self.low=20355.0   
2023-03-13 00:25:01,571:INFO:factorcheck2:main.py:127:handleKline:185239: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime    closeSec  ...      low       pct  index  idx
1440  20230313   000000    000459  1678637099  ...  20333.8 -0.000295   1440    0
1441  20230313   000500    000959  1678637399  ...  20341.9  0.000973   1441    1
1442  20230313   001000    001459  1678637699  ...  20353.6 -0.000368   1442    2
1443  20230313   001500    001959  1678637999  ...  20332.5  0.000187   1443    3
1444  20230313   002000    002459  1678638299  ...  20355.0  0.000599   1444    4

[5 rows x 11 columns]
2023-03-13 00:25:01,571:INFO:factorcheck2:main.py:128:handleKline:185239: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': True, 'isOpenSell': False, 'isCloseBuy': False, 'isCloseSell': False, 'isOpen': True, 'isClose': False, 'isTrig': True}


## /root/FIL/strategy/logic/log.txt ----- -----

2023-03-13 00:00:33,934:DEBUG:logic:main.py:463:getModel:885513: df_s.iloc[-5:,:] :
          date closeTime     open  ...    alpha58   alpha67   alpha72
5802  20230312    212959  20373.5  ...  45.833333  0.508576  0.287026
5803  20230312    215959  20405.1  ...  45.833333  0.501536  0.294214
5804  20230312    222959  20371.6  ...  45.833333  0.499514  0.302508
5805  20230312    225959  20362.0  ...  45.833333  0.493132  0.315237
5806  20230312    232959  20331.3  ...  46.250000  0.498244  0.325784

[5 rows x 33 columns]
0.5698529411764706
acc is : 0.5698529411764706
2023-03-13 00:00:34,087:INFO:logic:main.py:468:getModel:885513: df_pred.iloc[-5:,:] :
     pred    prob_0    prob_1  actual  ...       nav  sign  cost_        bm
539     0  0.509359  0.490641       0  ...  0.900523  -1.0    0.0  0.859213
540     1  0.463640  0.536360       0  ...  0.900947  -1.0    0.0  0.858808
541     1  0.477087  0.522913       0  ...  0.902283  -1.0    0.0  0.857535
542     1  0.473363  0.526637       1  ...  0.901236  -1.0    0.0  0.858530
543     0  0.502728  0.497272       0  ...  0.901568  -1.0    0.0  0.858214

[5 rows x 10 columns]
2023-03-13 00:00:34,123:INFO:logic:main.py:478:getModel:885513: df_panel.iloc[-5:,:] :
    pred    prob_0    prob_1  actual  ...       nav  sign  cost_        bm
45     0  0.509278  0.490722       0  ...  0.905802  -1.0    0.0  0.858710
46     1  0.463431  0.536569       0  ...  0.900947  -1.0    0.0  0.857441
47     1  0.477043  0.522957       0  ...  0.902283  -1.0    0.0  0.856170
48     1  0.473241  0.526759       1  ...  0.901236  -1.0    0.0  0.858200
49     0  0.502728  0.497272       0  ...  0.901568  -1.0    0.0  0.858214

[5 rows x 10 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '32.455', 'enterprice': '20374.9', 'countrevence': '0', 'unrealprofit': '1064.79264723615', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '20342.09172247', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}


## /root/FIL/strategy/modifiedmom/log.txt ----- -----

127.0.0.1 - - [13/Mar/2023 00:00:03] "POST / HTTP/1.1" 200 -
2023-03-13 00:00:03,374:INFO:modifiedmom:main.py:319:handleOrderFilled:185213: handleOrderFilled: data=OrderType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'clientorderid': '41962F1678636802946I0L59', 'symbol': 'BTCUSDT', 'gatewayorderid': 1678636803038649, 'quantity': '49.164', 'price': '20347.8', 'stopprice': '0', 'ordertype': '', 'side': 'SELL', 'status': 'FILLED', 'positionside': 'SHORT', 'createtime': 1678636802266, 'updatetime': 1678636803038, 'tradetype': 'usdt', 'selfid': 41962, 'filltrades': [TradeType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'tradeid': 1678636803038, 'clientorderid': '41962F1678636802946I0L59', 'price': '20347.8', 'quantity': '49.164', 'commission': '1000.3792392', 'commissionasset': 'USDT', 'tradetime': 1678636803038, 'tradetype': 'usdt', 'gatetype': 'simulator', 'handletime': 1678636803038}], 'gatetype': 'simulator', 'handletime': 0}

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=15464 

self.closeSec=1678637399, self.tradeDate='20230313', self.openTime='000000', self.closeTime='000959', self.symbol='BTCUSDT', self.open='20347.8', self.close='20361.7'
127.0.0.1 - - [13/Mar/2023 00:10:01] "POST / HTTP/1.1" 200 -
2023-03-13 00:10:01,789:INFO:modifiedmom:main.py:144:handleKline:185213: self.closeSec=1678637399, self.tradeDate='20230313', self.openTime='000000', self.closeTime='000959',self.symbol='BTCUSDT',self.open='20347.8', self.close='20361.7'
2023-03-13 00:10:01,817:INFO:modifiedmom:main.py:145:handleKline:185213: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec     open    close       pct
572  20230312   232000    232959  1678634999  20358.7  20355.4 -0.000162
573  20230312   233000    233959  1678635599  20355.3  20344.4 -0.000540
574  20230312   234000    234959  1678636199  20344.3  20346.9  0.000123
575  20230312   235000    235959  1678636799  20346.9  20347.9  0.000049
576  20230313   000000    000959  1678637399  20347.8  20361.7  0.000678
2023-03-13 00:10:01,817:INFO:modifiedmom:main.py:146:handleKline:185213: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': True, 'isOpen': False, 'isClose': True, 'isTrig': False}

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=15465 

self.closeSec=1678637999, self.tradeDate='20230313', self.openTime='001000', self.closeTime='001959', self.symbol='BTCUSDT', self.open='20361.7', self.close='20358'
127.0.0.1 - - [13/Mar/2023 00:20:02] "POST / HTTP/1.1" 200 -
2023-03-13 00:20:04,050:INFO:modifiedmom:main.py:144:handleKline:185213: self.closeSec=1678637999, self.tradeDate='20230313', self.openTime='001000', self.closeTime='001959',self.symbol='BTCUSDT',self.open='20361.7', self.close='20358'
2023-03-13 00:20:04,750:INFO:modifiedmom:main.py:145:handleKline:185213: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec     open    close       pct
573  20230312   233000    233959  1678635599  20355.3  20344.4 -0.000540
574  20230312   234000    234959  1678636199  20344.3  20346.9  0.000123
575  20230312   235000    235959  1678636799  20346.9  20347.9  0.000049
576  20230313   000000    000959  1678637399  20347.8  20361.7  0.000678
577  20230313   001000    001959  1678637999  20361.7    20358 -0.000182
2023-03-13 00:20:04,759:INFO:modifiedmom:main.py:146:handleKline:185213: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': True, 'isOpen': False, 'isClose': True, 'isTrig': False}


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

2023-03-13 00:00:01,955:INFO:pyemd2:main.py:127:handleKline:185189: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}
2023-03-13 00:00:02,179:INFO:pyemd2:main.py:190:insertFactor:185189: curDateTime:3130000, name:pyemd2, symbol:BTCUSDT, tradeDate:20230312, closeTime:235959, close:20347.9, total:981709.7545293, pct_pre:0.018124306659071276, thd:-0.25448236280458947, side:sell 
127.0.0.1 - - [13/Mar/2023 00:10:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=15465 

self.closeSec=1678637399, self.tradeDate='20230313', self.openTime='000000', self.closeTime='000959', self.symbol='BTCUSDT', self.open='20347.8', self.close='20361.7'
2023-03-13 00:10:01,769:INFO:pyemd2:main.py:125:handleKline:185189: self.closeSec=1678637399, self.tradeDate='20230313', self.openTime='000000', self.closeTime='000959',self.symbol='BTCUSDT',self.open='20347.8', self.close='20361.7'
2023-03-13 00:10:01,813:INFO:pyemd2:main.py:126:handleKline:185189: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
17420  20230312   232000    232959  1678634999  20358.7  20355.4
17421  20230312   233000    233959  1678635599  20355.3  20344.4
17422  20230312   234000    234959  1678636199  20344.3  20346.9
17423  20230312   235000    235959  1678636799  20346.9  20347.9
17424  20230313   000000    000959  1678637399  20347.8  20361.7
2023-03-13 00:10:01,814:INFO:pyemd2:main.py:127:handleKline:185189: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=15466 

self.closeSec=1678637999, self.tradeDate='20230313', self.openTime='001000', self.closeTime='001959', self.symbol='BTCUSDT', self.open='20361.7', self.close='20358'
127.0.0.1 - - [13/Mar/2023 00:20:02] "POST / HTTP/1.1" 200 -
2023-03-13 00:20:06,278:INFO:pyemd2:main.py:125:handleKline:185189: self.closeSec=1678637999, self.tradeDate='20230313', self.openTime='001000', self.closeTime='001959',self.symbol='BTCUSDT',self.open='20361.7', self.close='20358'
2023-03-13 00:20:06,425:INFO:pyemd2:main.py:126:handleKline:185189: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
17421  20230312   233000    233959  1678635599  20355.3  20344.4
17422  20230312   234000    234959  1678636199  20344.3  20346.9
17423  20230312   235000    235959  1678636799  20346.9  20347.9
17424  20230313   000000    000959  1678637399  20347.8  20361.7
17425  20230313   001000    001959  1678637999  20361.7    20358
2023-03-13 00:20:06,425:INFO:pyemd2:main.py:127:handleKline:185189: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}


## /root/FIL/strategy/similarity/log.txt ----- -----

127.0.0.1 - - [13/Mar/2023 00:00:03] "POST / HTTP/1.1" 200 -
2023-03-13 00:00:03,689:INFO:testStrategy:main.py:308:handleOrderFilled:185174: handleOrderFilled: data=OrderType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'clientorderid': '41963F1678636802966I0L2', 'symbol': 'BTCUSDT', 'gatewayorderid': 1678636803059530, 'quantity': '55.823', 'price': '20347.8', 'stopprice': '0', 'ordertype': '', 'side': 'SELL', 'status': 'FILLED', 'positionside': 'SHORT', 'createtime': 1678636802585, 'updatetime': 1678636803059, 'tradetype': 'usdt', 'selfid': 41963, 'filltrades': [TradeType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'tradeid': 1678636803059, 'clientorderid': '41963F1678636802966I0L2', 'price': '20347.8', 'quantity': '55.823', 'commission': '1135.8752394', 'commissionasset': 'USDT', 'tradetime': 1678636803059, 'tradetype': 'usdt', 'gatetype': 'simulator', 'handletime': 1678636803059}], 'gatetype': 'simulator', 'handletime': 0}
127.0.0.1 - - [13/Mar/2023 00:10:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=15465 

self.closeSec=1678637399, self.tradeDate='20230313', self.openTime='000000', self.closeTime='000959', self.symbol='BTCUSDT', self.open='20347.8', self.close='20361.7'
2023-03-13 00:10:01,763:INFO:testStrategy:main.py:101:handleKline:185174: self.closeSec=1678637399, self.tradeDate='20230313', self.openTime='000000', self.closeTime='000959',self.symbol='BTCUSDT',self.open='20347.8', self.close='20361.7'
2023-03-13 00:10:01,817:INFO:testStrategy:main.py:102:handleKline:185174: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
12236  20230312   232000    232959  1678634999  20358.7  20355.4
12237  20230312   233000    233959  1678635599  20355.3  20344.4
12238  20230312   234000    234959  1678636199  20344.3  20346.9
12239  20230312   235000    235959  1678636799  20346.9  20347.9
12240  20230313   000000    000959  1678637399  20347.8  20361.7
2023-03-13 00:10:01,817:INFO:testStrategy:main.py:103:handleKline:185174: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': True, 'isOpen': False, 'isClose': True, 'isTrig': False, 'isCorr': False}

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=15466 

self.closeSec=1678637999, self.tradeDate='20230313', self.openTime='001000', self.closeTime='001959', self.symbol='BTCUSDT', self.open='20361.7', self.close='20358'
127.0.0.1 - - [13/Mar/2023 00:20:02] "POST / HTTP/1.1" 200 -
2023-03-13 00:20:05,727:INFO:testStrategy:main.py:101:handleKline:185174: self.closeSec=1678637999, self.tradeDate='20230313', self.openTime='001000', self.closeTime='001959',self.symbol='BTCUSDT',self.open='20361.7', self.close='20358'
2023-03-13 00:20:06,124:INFO:testStrategy:main.py:102:handleKline:185174: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
12237  20230312   233000    233959  1678635599  20355.3  20344.4
12238  20230312   234000    234959  1678636199  20344.3  20346.9
12239  20230312   235000    235959  1678636799  20346.9  20347.9
12240  20230313   000000    000959  1678637399  20347.8  20361.7
12241  20230313   001000    001959  1678637999  20361.7    20358
2023-03-13 00:20:06,124:INFO:testStrategy:main.py:103:handleKline:185174: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': True, 'isOpen': False, 'isClose': True, 'isTrig': False, 'isCorr': False}


## /root/FIL/strategy/sr_min/log.txt ----- -----

127.0.0.1 - - [13/Mar/2023 00:20:01] "POST / HTTP/1.1" 200 -
--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=0, self.total=1000000.0, self.flagDict['side']='', self.tradeCount=0, self.count=26362
self.closeSec=1678637999, self.tradeDate='20230313', self.openTime='001500', self.closeTime='001959', self.symbol='BTCUSDT', self.open=20354.3, self.close=20358.0, self.high=20364.5, self.low=20332.5, self.vol=1150.027, self.amt=23402703.358 
2023-03-13 00:20:01,785:INFO:sr_min:main.py:172:handleKline:449472: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5759  20230312   235500    235959  ...         0.0        0.0       0
5760  20230313   000000    000459  ...         0.0        0.0       0
5761  20230313   000500    000959  ...         0.0        0.0       0
5762  20230313   001000    001459  ...         0.0        0.0       0
5763  20230313   001500    001959  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-03-13 00:20:01,787:INFO:sr_min:main.py:175:handleKline:449472: self.closeSec=1678637999, self.tradeDate='20230313', self.openTime='001500', self.closeTime='001959',self.symbol='BTCUSDT',self.open=20354.3, self.close=20358.0, self.high=20364.5, self.low=20332.5, self.vol=1150.027, self.amt=23402703.358, ukdf['pct'].iloc[-1]=0.000187 , ukdf['amount'].iloc[-1]=23402703.358, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5763, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': []}
type(curSign)=<class 'int'>, curSign=0, self.sign=0
--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=0, self.total=1000000.0, self.flagDict['side']='', self.tradeCount=0, self.count=26363
self.closeSec=1678638299, self.tradeDate='20230313', self.openTime='002000', self.closeTime='002459', self.symbol='BTCUSDT', self.open=20357.9, self.close=20370.2, self.high=20379.2, self.low=20355.0, self.vol=822.921, self.amt=16760204.6001 
127.0.0.1 - - [13/Mar/2023 00:25:01] "POST / HTTP/1.1" 200 -
2023-03-13 00:25:01,603:INFO:sr_min:main.py:172:handleKline:449472: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5760  20230313   000000    000459  ...         0.0        0.0       0
5761  20230313   000500    000959  ...         0.0        0.0       0
5762  20230313   001000    001459  ...         0.0        0.0       0
5763  20230313   001500    001959  ...         0.0        0.0       0
5764  20230313   002000    002459  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-03-13 00:25:01,604:INFO:sr_min:main.py:175:handleKline:449472: self.closeSec=1678638299, self.tradeDate='20230313', self.openTime='002000', self.closeTime='002459',self.symbol='BTCUSDT',self.open=20357.9, self.close=20370.2, self.high=20379.2, self.low=20355.0, self.vol=822.921, self.amt=16760204.6001, ukdf['pct'].iloc[-1]=0.000599 , ukdf['amount'].iloc[-1]=16760204.6001, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5764, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': []}
type(curSign)=<class 'int'>, curSign=0, self.sign=0


## /root/FIL/strategy/s_rsrs/log.txt ----- -----

723  20230312   120000    155959  1678607999  ...    723  0.772872  0.718523     1.0
724  20230312   160000    195959  1678622399  ...    724  0.763021  0.703887     1.0

[5 rows x 15 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '55.825', 'enterprice': '20070', 'countrevence': '0', 'unrealprofit': '20444.65461833025', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '20436.22757937', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'numpy.int64'>, curSign=1, self.sign=1
--handleKline--:  version='2.0.0', self.name='s_rsrs', self.symbol='BTCUSDT', interval='4h', intervalSec=14400, wid=25, thd=0.6, self.sign=1, self.total=1119287.34225, self.flagDict['side']='buy', self.tradeCount=24, self.count=644
self.closeSec=1678636799, self.tradeDate='20230312', self.openTime='200000', self.closeTime='235959', self.symbol='BTCUSDT', self.open=20434.9, self.close=20347.9, self.high=20452.3, self.low=20270.0, self.vol=73260.469, self.amt=1491893812.3364 
127.0.0.1 - - [13/Mar/2023 00:00:01] "POST / HTTP/1.1" 200 -
2023-03-13 00:00:01,838:INFO:s_rsrs:main.py:141:handleKline:185271: self.closeSec=1678636799, self.tradeDate='20230312', self.openTime='200000', self.closeTime='235959',self.symbol='BTCUSDT',self.open=20434.9, self.close=20347.9, self.high=20452.3, self.low=20270.0, self.vol=73260.469, self.amt=1491893812.3364 
2023-03-13 00:00:01,904:INFO:s_rsrs:main.py:142:handleKline:185271: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime  ...        vol           amt       pct
721  20230312   040000    075959  ...  88653.535  1.804986e+09  0.011742
722  20230312   080000    115959  ...  69581.272  1.418949e+09 -0.003908
723  20230312   120000    155959  ...  39349.368  8.007788e+08 -0.001561
724  20230312   160000    195959  ...  51563.089  1.052004e+09  0.004888
725  20230312   200000    235959  ...  73260.469  1.491894e+09 -0.004262

[5 rows x 11 columns]
2023-03-13 00:00:04,385:INFO:s_rsrs:main.py:151:handleKline:185271: df_s.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec  ...  index      beta    zscore  signal
721  20230312   040000    075959  1678579199  ...    721  0.762446  0.673127     1.0
722  20230312   080000    115959  1678593599  ...    722  0.763955  0.680360     1.0
723  20230312   120000    155959  1678607999  ...    723  0.772872  0.718523     1.0
724  20230312   160000    195959  1678622399  ...    724  0.763021  0.703887     1.0
725  20230312   200000    235959  1678636799  ...    725  0.768772  0.738695     1.0

[5 rows x 15 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '55.825', 'enterprice': '20070', 'countrevence': '0', 'unrealprofit': '15522.020239264', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '20348.04783232', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'numpy.int64'>, curSign=1, self.sign=1


