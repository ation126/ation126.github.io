# 20230314 00:26:01

## /root/FIL/strategy/amihud/log.txt ----- -----

--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=993672.4896432, self.flagDict['side']='sell', self.tradeCount=2, self.count=30652
self.closeSec=1678724399, self.tradeDate='20230314', self.openTime='001500', self.closeTime='001959', self.symbol='BTCUSDT', self.open=24073.7, self.close=24082.7, self.high=24138.6, self.low=24067.5, self.vol=3436.199, self.amt=82818055.3047 
127.0.0.1 - - [14/Mar/2023 00:20:01] "POST / HTTP/1.1" 200 -
2023-03-14 00:20:03,722:INFO:amihud:main.py:172:handleKline:200676: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5759  20230313   235500    235959  ...         0.0        0.0       0
5760  20230314   000000    000459  ...         0.0        0.0       0
5761  20230314   000500    000959  ...         0.0        0.0       0
5762  20230314   001000    001459  ...         0.0        0.0       0
5763  20230314   001500    001959  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-03-14 00:20:03,744:INFO:amihud:main.py:175:handleKline:200676: self.closeSec=1678724399, self.tradeDate='20230314', self.openTime='001500', self.closeTime='001959',self.symbol='BTCUSDT',self.open=24073.7, self.close=24082.7, self.high=24138.6, self.low=24067.5, self.vol=3436.199, self.amt=82818055.3047, ukdf['pct'].iloc[-1]=0.000374 , ukdf['amount'].iloc[-1]=82818055.3047, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5763, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '60.176', 'enterprice': '16529.3', 'countrevence': '0', 'unrealprofit': '-455008.7888', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '24090.6', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1
127.0.0.1 - - [14/Mar/2023 00:25:01] "POST / HTTP/1.1" 200 -
--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=993672.4896432, self.flagDict['side']='sell', self.tradeCount=2, self.count=30653
self.closeSec=1678724699, self.tradeDate='20230314', self.openTime='002000', self.closeTime='002459', self.symbol='BTCUSDT', self.open=24082.7, self.close=24074.3, self.high=24233.7, self.low=24050.0, self.vol=8640.982, self.amt=208715824.5415 
2023-03-14 00:25:01,571:INFO:amihud:main.py:172:handleKline:200676: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5760  20230314   000000    000459  ...         0.0        0.0       0
5761  20230314   000500    000959  ...         0.0        0.0       0
5762  20230314   001000    001459  ...         0.0        0.0       0
5763  20230314   001500    001959  ...         0.0        0.0       0
5764  20230314   002000    002459  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-03-14 00:25:01,571:INFO:amihud:main.py:175:handleKline:200676: self.closeSec=1678724699, self.tradeDate='20230314', self.openTime='002000', self.closeTime='002459',self.symbol='BTCUSDT',self.open=24082.7, self.close=24074.3, self.high=24233.7, self.low=24050.0, self.vol=8640.982, self.amt=208715824.5415, ukdf['pct'].iloc[-1]=-0.000349 , ukdf['amount'].iloc[-1]=208715824.5415, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5764, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '60.176', 'enterprice': '16529.3', 'countrevence': '0', 'unrealprofit': '-454235.38485307024', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '24077.74763449', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1


## /root/FIL/strategy/factorcheck/log.txt ----- -----


self.closeSec=1678724399, self.tradeDate='20230314', self.openTime='001500', self.closeTime='001959', self.symbol='BTCUSDT', self.open=24073.7, self.close=24082.7, self.high=24138.6, self.low=24067.5 
127.0.0.1 - - [14/Mar/2023 00:20:01] "POST / HTTP/1.1" 200 -
2023-03-14 00:20:02,382:INFO:factorcheck2:main.py:126:handleKline:185239: self.closeSec=1678724399, self.tradeDate='20230314', self.openTime='001500', self.closeTime='001959',self.symbol='BTCUSDT',self.open=24073.7, self.close=24082.7, self.high=24138.6, self.low=24067.5   
2023-03-14 00:20:02,972:INFO:factorcheck2:main.py:127:handleKline:185239: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime    closeSec  ...      low       pct  index  idx
1439  20230313   235500    235959  1678723199  ...  23970.5  0.000805   1727    5
1440  20230314   000000    000459  1678723499  ...  23975.0  0.000054   1440    0
1441  20230314   000500    000959  1678723799  ...  23987.6  0.005583   1441    1
1442  20230314   001000    001459  1678724099  ...  24017.8 -0.002623   1442    2
1443  20230314   001500    001959  1678724399  ...  24067.5  0.000374   1443    3

[5 rows x 11 columns]
2023-03-14 00:20:02,981:INFO:factorcheck2:main.py:128:handleKline:185239: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}
127.0.0.1 - - [14/Mar/2023 00:25:01] "POST / HTTP/1.1" 200 -

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=39, self.factor=0.20263541479941816, self.count=31219 

self.closeSec=1678724699, self.tradeDate='20230314', self.openTime='002000', self.closeTime='002459', self.symbol='BTCUSDT', self.open=24082.7, self.close=24074.3, self.high=24233.7, self.low=24050.0 
2023-03-14 00:25:01,503:INFO:factorcheck2:main.py:126:handleKline:185239: self.closeSec=1678724699, self.tradeDate='20230314', self.openTime='002000', self.closeTime='002459',self.symbol='BTCUSDT',self.open=24082.7, self.close=24074.3, self.high=24233.7, self.low=24050.0   
2023-03-14 00:25:01,561:INFO:factorcheck2:main.py:127:handleKline:185239: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime    closeSec  ...      low       pct  index  idx
1440  20230314   000000    000459  1678723499  ...  23975.0  0.000054   1440    0
1441  20230314   000500    000959  1678723799  ...  23987.6  0.005583   1441    1
1442  20230314   001000    001459  1678724099  ...  24017.8 -0.002623   1442    2
1443  20230314   001500    001959  1678724399  ...  24067.5  0.000374   1443    3
1444  20230314   002000    002459  1678724699  ...  24050.0 -0.000349   1444    4

[5 rows x 11 columns]
2023-03-14 00:25:01,561:INFO:factorcheck2:main.py:128:handleKline:185239: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}


## /root/FIL/strategy/logic/log.txt ----- -----

2023-03-14 00:00:35,505:DEBUG:logic:main.py:463:getModel:885513: df_s.iloc[-5:,:] :
          date closeTime     open  ...    alpha58   alpha67   alpha72
5802  20230313    212959  22123.0  ...  49.583333  0.645089  0.184906
5803  20230313    215959  22430.5  ...  50.000000  0.648353  0.177127
5804  20230313    222959  22467.2  ...  50.416667  0.712116  0.169894
5805  20230313    225959  23345.1  ...  50.833333  0.719571  0.160716
5806  20230313    232959  23472.9  ...  50.833333  0.766792  0.150861

[5 rows x 33 columns]
0.5625
acc is : 0.5625
2023-03-14 00:00:35,698:INFO:logic:main.py:468:getModel:885513: df_pred.iloc[-5:,:] :
     pred    prob_0    prob_1  actual  ...       nav  sign   cost_        bm
539     0  0.640050  0.359950       1  ...  0.985849   1.0 -0.0016  0.960880
540     0  0.535413  0.464587       1  ...  1.024266   1.0  0.0000  0.998323
541     0  0.880561  0.119439       1  ...  1.029786   1.0  0.0000  1.003704
542     0  0.681662  0.318338       1  ...  1.072081   1.0  0.0000  1.044928
543     0  0.931647  0.068353       0  ...  1.053182   1.0  0.0000  1.026508

[5 rows x 10 columns]
2023-03-14 00:00:35,738:INFO:logic:main.py:478:getModel:885513: df_panel.iloc[-5:,:] :
    pred    prob_0    prob_1  actual  ...       nav  sign   cost_        bm
45     0  0.639378  0.360622       1  ...  0.985849   1.0 -0.0016  0.957812
46     0  0.535140  0.464860       1  ...  1.024266   1.0  0.0000  0.996410
47     0  0.880370  0.119630       1  ...  1.029786   1.0  0.0000  1.001780
48     0  0.681405  0.318595       1  ...  1.072081   1.0  0.0000  1.045236
49     0  0.931647  0.068353       0  ...  1.053182   1.0  0.0000  1.026508

[5 rows x 10 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '30.284', 'enterprice': '22463', 'countrevence': '0', 'unrealprofit': '48704.70087409256', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '24071.26511934', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}


## /root/FIL/strategy/modifiedmom/log.txt ----- -----

127.0.0.1 - - [14/Mar/2023 00:00:03] "POST / HTTP/1.1" 200 -
2023-03-14 00:00:03,513:INFO:modifiedmom:main.py:319:handleOrderFilled:185213: handleOrderFilled: data=OrderType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'clientorderid': '41974F1678723202915I0L59', 'symbol': 'BTCUSDT', 'gatewayorderid': 1678723203288269, 'quantity': '45.006', 'price': '24010', 'stopprice': '0', 'ordertype': '', 'side': 'BUY', 'status': 'FILLED', 'positionside': 'LONG', 'createtime': 1678723202435, 'updatetime': 1678723203288, 'tradetype': 'usdt', 'selfid': 41974, 'filltrades': [TradeType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'tradeid': 1678723203288, 'clientorderid': '41974F1678723202915I0L59', 'price': '24010', 'quantity': '45.006', 'commission': '1080.59406', 'commissionasset': 'USDT', 'tradetime': 1678723203288, 'tradetype': 'usdt', 'gatetype': 'simulator', 'handletime': 1678723203288}], 'gatetype': 'simulator', 'handletime': 0}
127.0.0.1 - - [14/Mar/2023 00:10:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=15608 

self.closeSec=1678723799, self.tradeDate='20230314', self.openTime='000000', self.closeTime='000959', self.symbol='BTCUSDT', self.open='24009', self.close='24137'
2023-03-14 00:10:01,778:INFO:modifiedmom:main.py:144:handleKline:185213: self.closeSec=1678723799, self.tradeDate='20230314', self.openTime='000000', self.closeTime='000959',self.symbol='BTCUSDT',self.open='24009', self.close='24137'
2023-03-14 00:10:01,808:INFO:modifiedmom:main.py:145:handleKline:185213: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec     open    close       pct
572  20230313   232000    232959  1678721399    24144  24432.4  0.011974
573  20230313   233000    233959  1678721999  24422.8  24033.6 -0.016323
574  20230313   234000    234959  1678722599  24030.6  23960.2 -0.003054
575  20230313   235000    235959  1678723199    23960    24009  0.002037
576  20230314   000000    000959  1678723799    24009    24137  0.005331
2023-03-14 00:10:01,808:INFO:modifiedmom:main.py:146:handleKline:185213: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': True, 'isOpen': False, 'isClose': True, 'isTrig': False}

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=15609 

self.closeSec=1678724399, self.tradeDate='20230314', self.openTime='001000', self.closeTime='001959', self.symbol='BTCUSDT', self.open='24136.9', self.close='24081.3'
127.0.0.1 - - [14/Mar/2023 00:20:01] "POST / HTTP/1.1" 200 -
2023-03-14 00:20:02,731:INFO:modifiedmom:main.py:144:handleKline:185213: self.closeSec=1678724399, self.tradeDate='20230314', self.openTime='001000', self.closeTime='001959',self.symbol='BTCUSDT',self.open='24136.9', self.close='24081.3'
2023-03-14 00:20:03,091:INFO:modifiedmom:main.py:145:handleKline:185213: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec     open    close       pct
573  20230313   233000    233959  1678721999  24422.8  24033.6 -0.016323
574  20230313   234000    234959  1678722599  24030.6  23960.2 -0.003054
575  20230313   235000    235959  1678723199    23960    24009  0.002037
576  20230314   000000    000959  1678723799    24009    24137  0.005331
577  20230314   001000    001959  1678724399  24136.9  24081.3 -0.002308
2023-03-14 00:20:03,092:INFO:modifiedmom:main.py:146:handleKline:185213: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': True, 'isOpen': False, 'isClose': True, 'isTrig': False}


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

2023-03-14 00:00:02,217:INFO:pyemd2:main.py:127:handleKline:185189: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}
2023-03-14 00:00:02,340:INFO:pyemd2:main.py:190:insertFactor:185189: curDateTime:3140000, name:pyemd2, symbol:BTCUSDT, tradeDate:20230313, closeTime:235959, close:24009, total:981709.7545293, pct_pre:0.07829896324963048, thd:-1.081223638183193, side:sell 

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=15609 

self.closeSec=1678723799, self.tradeDate='20230314', self.openTime='000000', self.closeTime='000959', self.symbol='BTCUSDT', self.open='24009', self.close='24137'
2023-03-14 00:10:01,793:INFO:pyemd2:main.py:125:handleKline:185189: self.closeSec=1678723799, self.tradeDate='20230314', self.openTime='000000', self.closeTime='000959',self.symbol='BTCUSDT',self.open='24009', self.close='24137'
127.0.0.1 - - [14/Mar/2023 00:10:01] "POST / HTTP/1.1" 200 -
2023-03-14 00:10:01,809:INFO:pyemd2:main.py:126:handleKline:185189: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
17420  20230313   232000    232959  1678721399    24144  24432.4
17421  20230313   233000    233959  1678721999  24422.8  24033.6
17422  20230313   234000    234959  1678722599  24030.6  23960.2
17423  20230313   235000    235959  1678723199    23960    24009
17424  20230314   000000    000959  1678723799    24009    24137
2023-03-14 00:10:01,809:INFO:pyemd2:main.py:127:handleKline:185189: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=15610 

self.closeSec=1678724399, self.tradeDate='20230314', self.openTime='001000', self.closeTime='001959', self.symbol='BTCUSDT', self.open='24136.9', self.close='24081.3'
127.0.0.1 - - [14/Mar/2023 00:20:01] "POST / HTTP/1.1" 200 -
2023-03-14 00:20:04,493:INFO:pyemd2:main.py:125:handleKline:185189: self.closeSec=1678724399, self.tradeDate='20230314', self.openTime='001000', self.closeTime='001959',self.symbol='BTCUSDT',self.open='24136.9', self.close='24081.3'
2023-03-14 00:20:04,604:INFO:pyemd2:main.py:126:handleKline:185189: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
17421  20230313   233000    233959  1678721999  24422.8  24033.6
17422  20230313   234000    234959  1678722599  24030.6  23960.2
17423  20230313   235000    235959  1678723199    23960    24009
17424  20230314   000000    000959  1678723799    24009    24137
17425  20230314   001000    001959  1678724399  24136.9  24081.3
2023-03-14 00:20:04,605:INFO:pyemd2:main.py:127:handleKline:185189: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}


## /root/FIL/strategy/similarity/log.txt ----- -----

127.0.0.1 - - [14/Mar/2023 00:00:03] "POST / HTTP/1.1" 200 -
2023-03-14 00:00:03,218:INFO:testStrategy:main.py:308:handleOrderFilled:185174: handleOrderFilled: data=OrderType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'clientorderid': '41973F1678723202802I0L2', 'symbol': 'BTCUSDT', 'gatewayorderid': 1678723202905024, 'quantity': '52.306', 'price': '24009.9', 'stopprice': '0', 'ordertype': '', 'side': 'SELL', 'status': 'FILLED', 'positionside': 'SHORT', 'createtime': 1678723202514, 'updatetime': 1678723202905, 'tradetype': 'usdt', 'selfid': 41973, 'filltrades': [TradeType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'tradeid': 1678723202905, 'clientorderid': '41973F1678723202802I0L2', 'price': '24009.9', 'quantity': '52.306', 'commission': '1255.8618294', 'commissionasset': 'USDT', 'tradetime': 1678723202905, 'tradetype': 'usdt', 'gatetype': 'simulator', 'handletime': 1678723202905}], 'gatetype': 'simulator', 'handletime': 0}

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=15609 

self.closeSec=1678723799, self.tradeDate='20230314', self.openTime='000000', self.closeTime='000959', self.symbol='BTCUSDT', self.open='24009', self.close='24137'
127.0.0.1 - - [14/Mar/2023 00:10:01] "POST / HTTP/1.1" 200 -
2023-03-14 00:10:01,792:INFO:testStrategy:main.py:101:handleKline:185174: self.closeSec=1678723799, self.tradeDate='20230314', self.openTime='000000', self.closeTime='000959',self.symbol='BTCUSDT',self.open='24009', self.close='24137'
2023-03-14 00:10:01,806:INFO:testStrategy:main.py:102:handleKline:185174: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
12236  20230313   232000    232959  1678721399    24144  24432.4
12237  20230313   233000    233959  1678721999  24422.8  24033.6
12238  20230313   234000    234959  1678722599  24030.6  23960.2
12239  20230313   235000    235959  1678723199    23960    24009
12240  20230314   000000    000959  1678723799    24009    24137
2023-03-14 00:10:01,807:INFO:testStrategy:main.py:103:handleKline:185174: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': True, 'isOpen': False, 'isClose': True, 'isTrig': False, 'isCorr': False}

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=15610 

self.closeSec=1678724399, self.tradeDate='20230314', self.openTime='001000', self.closeTime='001959', self.symbol='BTCUSDT', self.open='24136.9', self.close='24081.3'
127.0.0.1 - - [14/Mar/2023 00:20:01] "POST / HTTP/1.1" 200 -
2023-03-14 00:20:04,092:INFO:testStrategy:main.py:101:handleKline:185174: self.closeSec=1678724399, self.tradeDate='20230314', self.openTime='001000', self.closeTime='001959',self.symbol='BTCUSDT',self.open='24136.9', self.close='24081.3'
2023-03-14 00:20:04,415:INFO:testStrategy:main.py:102:handleKline:185174: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
12237  20230313   233000    233959  1678721999  24422.8  24033.6
12238  20230313   234000    234959  1678722599  24030.6  23960.2
12239  20230313   235000    235959  1678723199    23960    24009
12240  20230314   000000    000959  1678723799    24009    24137
12241  20230314   001000    001959  1678724399  24136.9  24081.3
2023-03-14 00:20:04,415:INFO:testStrategy:main.py:103:handleKline:185174: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': True, 'isOpen': False, 'isClose': True, 'isTrig': False, 'isCorr': False}


## /root/FIL/strategy/sr_min/log.txt ----- -----

--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=0, self.total=1000000.0, self.flagDict['side']='', self.tradeCount=0, self.count=26650
self.closeSec=1678724399, self.tradeDate='20230314', self.openTime='001500', self.closeTime='001959', self.symbol='BTCUSDT', self.open=24073.7, self.close=24082.7, self.high=24138.6, self.low=24067.5, self.vol=3436.199, self.amt=82818055.3047 
127.0.0.1 - - [14/Mar/2023 00:20:01] "POST / HTTP/1.1" 200 -
2023-03-14 00:20:01,576:INFO:sr_min:main.py:172:handleKline:449472: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5759  20230313   235500    235959  ...         0.0        0.0       0
5760  20230314   000000    000459  ...         0.0        0.0       0
5761  20230314   000500    000959  ...         0.0        0.0       0
5762  20230314   001000    001459  ...         0.0        0.0       0
5763  20230314   001500    001959  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-03-14 00:20:01,577:INFO:sr_min:main.py:175:handleKline:449472: self.closeSec=1678724399, self.tradeDate='20230314', self.openTime='001500', self.closeTime='001959',self.symbol='BTCUSDT',self.open=24073.7, self.close=24082.7, self.high=24138.6, self.low=24067.5, self.vol=3436.199, self.amt=82818055.3047, ukdf['pct'].iloc[-1]=0.000374 , ukdf['amount'].iloc[-1]=82818055.3047, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5763, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': []}
type(curSign)=<class 'int'>, curSign=0, self.sign=0
--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=0, self.total=1000000.0, self.flagDict['side']='', self.tradeCount=0, self.count=26651
self.closeSec=1678724699, self.tradeDate='20230314', self.openTime='002000', self.closeTime='002459', self.symbol='BTCUSDT', self.open=24082.7, self.close=24074.3, self.high=24233.7, self.low=24050.0, self.vol=8640.982, self.amt=208715824.5415 
127.0.0.1 - - [14/Mar/2023 00:25:01] "POST / HTTP/1.1" 200 -
2023-03-14 00:25:01,570:INFO:sr_min:main.py:172:handleKline:449472: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5760  20230314   000000    000459  ...         0.0        0.0       0
5761  20230314   000500    000959  ...         0.0        0.0       0
5762  20230314   001000    001459  ...         0.0        0.0       0
5763  20230314   001500    001959  ...         0.0        0.0       0
5764  20230314   002000    002459  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-03-14 00:25:01,570:INFO:sr_min:main.py:175:handleKline:449472: self.closeSec=1678724699, self.tradeDate='20230314', self.openTime='002000', self.closeTime='002459',self.symbol='BTCUSDT',self.open=24082.7, self.close=24074.3, self.high=24233.7, self.low=24050.0, self.vol=8640.982, self.amt=208715824.5415, ukdf['pct'].iloc[-1]=-0.000349 , ukdf['amount'].iloc[-1]=208715824.5415, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5764, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': []}
type(curSign)=<class 'int'>, curSign=0, self.sign=0


## /root/FIL/strategy/s_rsrs/log.txt ----- -----

723  20230313   120000    155959  1678694399  ...    723  0.785806  0.877901     1.0
724  20230313   160000    195959  1678708799  ...    724  0.906902  1.339733     1.0

[5 rows x 15 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '55.825', 'enterprice': '20070', 'countrevence': '0', 'unrealprofit': '113330.0720283655', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '22100.09533414', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'numpy.int64'>, curSign=1, self.sign=1
--handleKline--:  version='2.0.0', self.name='s_rsrs', self.symbol='BTCUSDT', interval='4h', intervalSec=14400, wid=25, thd=0.6, self.sign=1, self.total=1119287.34225, self.flagDict['side']='buy', self.tradeCount=24, self.count=650
self.closeSec=1678723199, self.tradeDate='20230313', self.openTime='200000', self.closeTime='235959', self.symbol='BTCUSDT', self.open=22092.6, self.close=24009.0, self.high=24517.2, self.low=21945.0, self.vol=677353.141, self.amt=15750630876.96101 
127.0.0.1 - - [14/Mar/2023 00:00:02] "POST / HTTP/1.1" 200 -
2023-03-14 00:00:02,058:INFO:s_rsrs:main.py:141:handleKline:185271: self.closeSec=1678723199, self.tradeDate='20230313', self.openTime='200000', self.closeTime='235959',self.symbol='BTCUSDT',self.open=22092.6, self.close=24009.0, self.high=24517.2, self.low=21945.0, self.vol=677353.141, self.amt=15750630876.96101 
2023-03-14 00:00:02,132:INFO:s_rsrs:main.py:142:handleKline:185271: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime  ...         vol           amt       pct
721  20230313   040000    075959  ...  327344.807  7.038856e+09  0.058530
722  20230313   080000    115959  ...  220127.800  4.895808e+09  0.010711
723  20230313   120000    155959  ...  107549.845  2.405123e+09  0.010346
724  20230313   160000    195959  ...  212765.433  4.701409e+09 -0.015990
725  20230313   200000    235959  ...  677353.141  1.575063e+10  0.086744

[5 rows x 11 columns]
2023-03-14 00:00:04,560:INFO:s_rsrs:main.py:151:handleKline:185271: df_s.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec  ...  index      beta    zscore  signal
721  20230313   040000    075959  1678665599  ...    721  0.700134  0.532409     NaN
722  20230313   080000    115959  1678679999  ...    722  0.753174  0.742093     1.0
723  20230313   120000    155959  1678694399  ...    723  0.785806  0.877901     1.0
724  20230313   160000    195959  1678708799  ...    724  0.906902  1.339733     1.0
725  20230313   200000    235959  1678723199  ...    725  1.272734  2.633642     1.0

[5 rows x 15 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '55.825', 'enterprice': '20070', 'countrevence': '0', 'unrealprofit': '219950.5', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '24010', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'numpy.int64'>, curSign=1, self.sign=1


