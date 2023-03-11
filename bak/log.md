# 20230312 00:26:01

## /root/FIL/strategy/amihud/log.txt ----- -----

--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=993672.4896432, self.flagDict['side']='sell', self.tradeCount=2, self.count=30076
self.closeSec=1678551599, self.tradeDate='20230312', self.openTime='001500', self.closeTime='001959', self.symbol='BTCUSDT', self.open=20025.0, self.close=20039.3, self.high=20070.2, self.low=20017.3, self.vol=1793.159, self.amt=35945189.4156 
127.0.0.1 - - [12/Mar/2023 00:20:01] "POST / HTTP/1.1" 200 -
2023-03-12 00:20:04,672:INFO:amihud:main.py:172:handleKline:200676: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5759  20230311   235500    235959  ...         0.0        0.0       0
5760  20230312   000000    000459  ...         0.0        0.0       0
5761  20230312   000500    000959  ...         0.0        0.0       0
5762  20230312   001000    001459  ...         0.0        0.0       0
5763  20230312   001500    001959  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-03-12 00:20:04,683:INFO:amihud:main.py:175:handleKline:200676: self.closeSec=1678551599, self.tradeDate='20230312', self.openTime='001500', self.closeTime='001959',self.symbol='BTCUSDT',self.open=20025.0, self.close=20039.3, self.high=20070.2, self.low=20017.3, self.vol=1793.159, self.amt=35945189.4156, ukdf['pct'].iloc[-1]=0.000714 , ukdf['amount'].iloc[-1]=35945189.4156, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5763, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '60.176', 'enterprice': '16529.3', 'countrevence': '0', 'unrealprofit': '-211483.59606892048', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '20043.71764273', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1
--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=993672.4896432, self.flagDict['side']='sell', self.tradeCount=2, self.count=30077
self.closeSec=1678551899, self.tradeDate='20230312', self.openTime='002000', self.closeTime='002459', self.symbol='BTCUSDT', self.open=20039.4, self.close=20036.6, self.high=20066.7, self.low=20035.8, self.vol=1064.145, self.amt=21338402.611 
127.0.0.1 - - [12/Mar/2023 00:25:01] "POST / HTTP/1.1" 200 -
2023-03-12 00:25:01,705:INFO:amihud:main.py:172:handleKline:200676: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5760  20230312   000000    000459  ...         0.0        0.0       0
5761  20230312   000500    000959  ...         0.0        0.0       0
5762  20230312   001000    001459  ...         0.0        0.0       0
5763  20230312   001500    001959  ...         0.0        0.0       0
5764  20230312   002000    002459  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-03-12 00:25:01,707:INFO:amihud:main.py:175:handleKline:200676: self.closeSec=1678551899, self.tradeDate='20230312', self.openTime='002000', self.closeTime='002459',self.symbol='BTCUSDT',self.open=20039.4, self.close=20036.6, self.high=20066.7, self.low=20035.8, self.vol=1064.145, self.amt=21338402.611, ukdf['pct'].iloc[-1]=-0.000135 , ukdf['amount'].iloc[-1]=21338402.611, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5764, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '60.176', 'enterprice': '16529.3', 'countrevence': '0', 'unrealprofit': '-211063.99880712768', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '20036.74480868', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1


## /root/FIL/strategy/factorcheck/log.txt ----- -----


self.closeSec=1678551599, self.tradeDate='20230312', self.openTime='001500', self.closeTime='001959', self.symbol='BTCUSDT', self.open=20025.0, self.close=20039.3, self.high=20070.2, self.low=20017.3 
127.0.0.1 - - [12/Mar/2023 00:20:01] "POST / HTTP/1.1" 200 -
2023-03-12 00:20:02,992:INFO:factorcheck2:main.py:126:handleKline:185239: self.closeSec=1678551599, self.tradeDate='20230312', self.openTime='001500', self.closeTime='001959',self.symbol='BTCUSDT',self.open=20025.0, self.close=20039.3, self.high=20070.2, self.low=20017.3   
2023-03-12 00:20:03,612:INFO:factorcheck2:main.py:127:handleKline:185239: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime    closeSec  ...      low       pct  index  idx
1439  20230311   235500    235959  1678550399  ...  20052.2 -0.000045   1727    5
1440  20230312   000000    000459  1678550699  ...  20051.7  0.000668   1440    0
1441  20230312   000500    000959  1678550999  ...  19968.3 -0.002686   1441    1
1442  20230312   001000    001459  1678551299  ...  20009.8  0.000660   1442    2
1443  20230312   001500    001959  1678551599  ...  20017.3  0.000714   1443    3

[5 rows x 11 columns]
2023-03-12 00:20:03,621:INFO:factorcheck2:main.py:128:handleKline:185239: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': True, 'isOpenSell': False, 'isCloseBuy': False, 'isCloseSell': False, 'isOpen': True, 'isClose': False, 'isTrig': True}
127.0.0.1 - - [12/Mar/2023 00:25:01] "POST / HTTP/1.1" 200 -

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=0, self.factor=0.6074143805398481, self.count=30643 

self.closeSec=1678551899, self.tradeDate='20230312', self.openTime='002000', self.closeTime='002459', self.symbol='BTCUSDT', self.open=20039.4, self.close=20036.6, self.high=20066.7, self.low=20035.8 
2023-03-12 00:25:01,624:INFO:factorcheck2:main.py:126:handleKline:185239: self.closeSec=1678551899, self.tradeDate='20230312', self.openTime='002000', self.closeTime='002459',self.symbol='BTCUSDT',self.open=20039.4, self.close=20036.6, self.high=20066.7, self.low=20035.8   
2023-03-12 00:25:01,669:INFO:factorcheck2:main.py:127:handleKline:185239: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime    closeSec  ...      low       pct  index  idx
1440  20230312   000000    000459  1678550699  ...  20051.7  0.000668   1440    0
1441  20230312   000500    000959  1678550999  ...  19968.3 -0.002686   1441    1
1442  20230312   001000    001459  1678551299  ...  20009.8  0.000660   1442    2
1443  20230312   001500    001959  1678551599  ...  20017.3  0.000714   1443    3
1444  20230312   002000    002459  1678551899  ...  20035.8 -0.000135   1444    4

[5 rows x 11 columns]
2023-03-12 00:25:01,672:INFO:factorcheck2:main.py:128:handleKline:185239: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': True, 'isOpenSell': False, 'isCloseBuy': False, 'isCloseSell': False, 'isOpen': True, 'isClose': False, 'isTrig': True}


## /root/FIL/strategy/logic/log.txt ----- -----

2023-03-12 00:00:35,397:DEBUG:logic:main.py:463:getModel:885513: df_s.iloc[-5:,:] :
          date closeTime     open  ...    alpha58   alpha67   alpha72
5802  20230311    212959  20020.2  ...  42.916667  0.455821  0.522974
5803  20230311    215959  20100.4  ...  42.500000  0.451998  0.531811
5804  20230311    222959  20070.0  ...  42.916667  0.460967  0.535800
5805  20230311    225959  20128.9  ...  42.500000  0.457452  0.541483
5806  20230311    232959  20102.0  ...  42.500000  0.456600  0.547257

[5 rows x 33 columns]
0.5551470588235294
acc is : 0.5551470588235294
2023-03-12 00:00:35,539:INFO:logic:main.py:468:getModel:885513: df_pred.iloc[-5:,:] :
     pred    prob_0    prob_1  actual  ...       nav  sign  cost_        bm
539     0  0.553569  0.446431       0  ...  0.906434   1.0    0.0  0.864223
540     1  0.490082  0.509918       1  ...  0.909095   1.0    0.0  0.866759
541     0  0.538273  0.461727       0  ...  0.907871   1.0    0.0  0.865592
542     1  0.491147  0.508853       0  ...  0.907577   1.0    0.0  0.865312
543     0  0.510999  0.489001       0  ...  0.905631   1.0    0.0  0.863456

[5 rows x 10 columns]
2023-03-12 00:00:35,576:INFO:logic:main.py:478:getModel:885513: df_panel.iloc[-5:,:] :
    pred    prob_0    prob_1  actual  ...       nav  sign  cost_        bm
45     0  0.554068  0.445932       0  ...  0.906434   1.0    0.0  0.859132
46     1  0.489887  0.510113       1  ...  0.909095   1.0    0.0  0.860942
47     0  0.538594  0.461406       0  ...  0.907871   1.0    0.0  0.859783
48     1  0.491035  0.508965       0  ...  0.907577   1.0    0.0  0.860805
49     0  0.510999  0.489001       0  ...  0.905631   1.0    0.0  0.863456

[5 rows x 10 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '32.476', 'enterprice': '20021.1', 'countrevence': '0', 'unrealprofit': '1126.96362574104', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '20055.80142954', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}


## /root/FIL/strategy/modifiedmom/log.txt ----- -----

127.0.0.1 - - [12/Mar/2023 00:00:03] "POST / HTTP/1.1" 200 -
2023-03-12 00:00:03,813:INFO:modifiedmom:main.py:319:handleOrderFilled:185213: handleOrderFilled: data=OrderType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'clientorderid': '41957F1678550402818I0L59', 'symbol': 'BTCUSDT', 'gatewayorderid': 1678550402949303, 'quantity': '49.98', 'price': '20052.2', 'stopprice': '0', 'ordertype': '', 'side': 'SELL', 'status': 'FILLED', 'positionside': 'SHORT', 'createtime': 1678550402391, 'updatetime': 1678550402949, 'tradetype': 'usdt', 'selfid': 41957, 'filltrades': [TradeType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'tradeid': 1678550402949, 'clientorderid': '41957F1678550402818I0L59', 'price': '20052.2', 'quantity': '49.98', 'commission': '1002.208956', 'commissionasset': 'USDT', 'tradetime': 1678550402949, 'tradetype': 'usdt', 'gatetype': 'simulator', 'handletime': 1678550402949}], 'gatetype': 'simulator', 'handletime': 0}

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=15320 

self.closeSec=1678550999, self.tradeDate='20230312', self.openTime='000000', self.closeTime='000959', self.symbol='BTCUSDT', self.open='20052.3', self.close='20011.8'
127.0.0.1 - - [12/Mar/2023 00:10:01] "POST / HTTP/1.1" 200 -
2023-03-12 00:10:01,743:INFO:modifiedmom:main.py:144:handleKline:185213: self.closeSec=1678550999, self.tradeDate='20230312', self.openTime='000000', self.closeTime='000959',self.symbol='BTCUSDT',self.open='20052.3', self.close='20011.8'
2023-03-12 00:10:01,773:INFO:modifiedmom:main.py:145:handleKline:185213: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec     open    close       pct
572  20230311   232000    232959  1678548599  20092.4  20095.4  0.000149
573  20230311   233000    233959  1678549199  20095.5  20080.6 -0.000736
574  20230311   234000    234959  1678549799  20080.6  20072.7 -0.000393
575  20230311   235000    235959  1678550399  20072.8  20052.3 -0.001016
576  20230312   000000    000959  1678550999  20052.3  20011.8 -0.002020
2023-03-12 00:10:01,773:INFO:modifiedmom:main.py:146:handleKline:185213: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': True, 'isOpen': False, 'isClose': True, 'isTrig': False}

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=15321 

self.closeSec=1678551599, self.tradeDate='20230312', self.openTime='001000', self.closeTime='001959', self.symbol='BTCUSDT', self.open='20011.8', self.close='20039.3'
127.0.0.1 - - [12/Mar/2023 00:20:02] "POST / HTTP/1.1" 200 -
2023-03-12 00:20:03,441:INFO:modifiedmom:main.py:144:handleKline:185213: self.closeSec=1678551599, self.tradeDate='20230312', self.openTime='001000', self.closeTime='001959',self.symbol='BTCUSDT',self.open='20011.8', self.close='20039.3'
2023-03-12 00:20:03,772:INFO:modifiedmom:main.py:145:handleKline:185213: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec     open    close       pct
573  20230311   233000    233959  1678549199  20095.5  20080.6 -0.000736
574  20230311   234000    234959  1678549799  20080.6  20072.7 -0.000393
575  20230311   235000    235959  1678550399  20072.8  20052.3 -0.001016
576  20230312   000000    000959  1678550999  20052.3  20011.8 -0.002020
577  20230312   001000    001959  1678551599  20011.8  20039.3  0.001374
2023-03-12 00:20:03,772:INFO:modifiedmom:main.py:146:handleKline:185213: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': True, 'isOpen': False, 'isClose': True, 'isTrig': False}


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

2023-03-12 00:00:03,481:INFO:pyemd2:main.py:303:handleOrderFilled:185189: handleOrderFilled: data=OrderType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'clientorderid': '41956F1678550402798I0L57', 'symbol': 'BTCUSDT', 'gatewayorderid': 1678550402901812, 'quantity': '48.956', 'price': '20052.2', 'stopprice': '0', 'ordertype': '', 'side': 'SELL', 'status': 'FILLED', 'positionside': 'SHORT', 'createtime': 1678550402407, 'updatetime': 1678550402901, 'tradetype': 'usdt', 'selfid': 41956, 'filltrades': [TradeType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'tradeid': 1678550402901, 'clientorderid': '41956F1678550402798I0L57', 'price': '20052.2', 'quantity': '48.956', 'commission': '981.6755032', 'commissionasset': 'USDT', 'tradetime': 1678550402901, 'tradetype': 'usdt', 'gatetype': 'simulator', 'handletime': 1678550402901}], 'gatetype': 'simulator', 'handletime': 0}
127.0.0.1 - - [12/Mar/2023 00:00:03] "POST / HTTP/1.1" 200 -
127.0.0.1 - - [12/Mar/2023 00:10:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=15321 

self.closeSec=1678550999, self.tradeDate='20230312', self.openTime='000000', self.closeTime='000959', self.symbol='BTCUSDT', self.open='20052.3', self.close='20011.8'
2023-03-12 00:10:01,766:INFO:pyemd2:main.py:125:handleKline:185189: self.closeSec=1678550999, self.tradeDate='20230312', self.openTime='000000', self.closeTime='000959',self.symbol='BTCUSDT',self.open='20052.3', self.close='20011.8'
2023-03-12 00:10:01,804:INFO:pyemd2:main.py:126:handleKline:185189: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
17420  20230311   232000    232959  1678548599  20092.4  20095.4
17421  20230311   233000    233959  1678549199  20095.5  20080.6
17422  20230311   234000    234959  1678549799  20080.6  20072.7
17423  20230311   235000    235959  1678550399  20072.8  20052.3
17424  20230312   000000    000959  1678550999  20052.3  20011.8
2023-03-12 00:10:01,804:INFO:pyemd2:main.py:127:handleKline:185189: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=15322 

self.closeSec=1678551599, self.tradeDate='20230312', self.openTime='001000', self.closeTime='001959', self.symbol='BTCUSDT', self.open='20011.8', self.close='20039.3'
127.0.0.1 - - [12/Mar/2023 00:20:02] "POST / HTTP/1.1" 200 -
2023-03-12 00:20:05,055:INFO:pyemd2:main.py:125:handleKline:185189: self.closeSec=1678551599, self.tradeDate='20230312', self.openTime='001000', self.closeTime='001959',self.symbol='BTCUSDT',self.open='20011.8', self.close='20039.3'
2023-03-12 00:20:05,164:INFO:pyemd2:main.py:126:handleKline:185189: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
17421  20230311   233000    233959  1678549199  20095.5  20080.6
17422  20230311   234000    234959  1678549799  20080.6  20072.7
17423  20230311   235000    235959  1678550399  20072.8  20052.3
17424  20230312   000000    000959  1678550999  20052.3  20011.8
17425  20230312   001000    001959  1678551599  20011.8  20039.3
2023-03-12 00:20:05,164:INFO:pyemd2:main.py:127:handleKline:185189: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}


## /root/FIL/strategy/similarity/log.txt ----- -----

127.0.0.1 - - [12/Mar/2023 00:00:03] "POST / HTTP/1.1" 200 -
2023-03-12 00:00:03,219:INFO:testStrategy:main.py:308:handleOrderFilled:185174: handleOrderFilled: data=OrderType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'clientorderid': '41955F1678550402728I0L2', 'symbol': 'BTCUSDT', 'gatewayorderid': 1678550402839526, 'quantity': '56.636', 'price': '20052.2', 'stopprice': '0', 'ordertype': '', 'side': 'SELL', 'status': 'FILLED', 'positionside': 'SHORT', 'createtime': 1678550402375, 'updatetime': 1678550402839, 'tradetype': 'usdt', 'selfid': 41955, 'filltrades': [TradeType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'tradeid': 1678550402839, 'clientorderid': '41955F1678550402728I0L2', 'price': '20052.2', 'quantity': '56.636', 'commission': '1135.6763992', 'commissionasset': 'USDT', 'tradetime': 1678550402839, 'tradetype': 'usdt', 'gatetype': 'simulator', 'handletime': 1678550402839}], 'gatetype': 'simulator', 'handletime': 0}

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=15321 

self.closeSec=1678550999, self.tradeDate='20230312', self.openTime='000000', self.closeTime='000959', self.symbol='BTCUSDT', self.open='20052.3', self.close='20011.8'
127.0.0.1 - - [12/Mar/2023 00:10:01] "POST / HTTP/1.1" 200 -
2023-03-12 00:10:01,727:INFO:testStrategy:main.py:101:handleKline:185174: self.closeSec=1678550999, self.tradeDate='20230312', self.openTime='000000', self.closeTime='000959',self.symbol='BTCUSDT',self.open='20052.3', self.close='20011.8'
2023-03-12 00:10:01,771:INFO:testStrategy:main.py:102:handleKline:185174: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
12236  20230311   232000    232959  1678548599  20092.4  20095.4
12237  20230311   233000    233959  1678549199  20095.5  20080.6
12238  20230311   234000    234959  1678549799  20080.6  20072.7
12239  20230311   235000    235959  1678550399  20072.8  20052.3
12240  20230312   000000    000959  1678550999  20052.3  20011.8
2023-03-12 00:10:01,774:INFO:testStrategy:main.py:103:handleKline:185174: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': True, 'isOpen': False, 'isClose': True, 'isTrig': False, 'isCorr': False}

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=15322 

self.closeSec=1678551599, self.tradeDate='20230312', self.openTime='001000', self.closeTime='001959', self.symbol='BTCUSDT', self.open='20011.8', self.close='20039.3'
127.0.0.1 - - [12/Mar/2023 00:20:02] "POST / HTTP/1.1" 200 -
2023-03-12 00:20:04,571:INFO:testStrategy:main.py:101:handleKline:185174: self.closeSec=1678551599, self.tradeDate='20230312', self.openTime='001000', self.closeTime='001959',self.symbol='BTCUSDT',self.open='20011.8', self.close='20039.3'
2023-03-12 00:20:04,814:INFO:testStrategy:main.py:102:handleKline:185174: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
12237  20230311   233000    233959  1678549199  20095.5  20080.6
12238  20230311   234000    234959  1678549799  20080.6  20072.7
12239  20230311   235000    235959  1678550399  20072.8  20052.3
12240  20230312   000000    000959  1678550999  20052.3  20011.8
12241  20230312   001000    001959  1678551599  20011.8  20039.3
2023-03-12 00:20:04,814:INFO:testStrategy:main.py:103:handleKline:185174: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': True, 'isOpen': False, 'isClose': True, 'isTrig': False, 'isCorr': False}


## /root/FIL/strategy/sr_min/log.txt ----- -----

127.0.0.1 - - [12/Mar/2023 00:20:01] "POST / HTTP/1.1" 200 -
--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=0, self.total=1000000.0, self.flagDict['side']='', self.tradeCount=0, self.count=26074
self.closeSec=1678551599, self.tradeDate='20230312', self.openTime='001500', self.closeTime='001959', self.symbol='BTCUSDT', self.open=20025.0, self.close=20039.3, self.high=20070.2, self.low=20017.3, self.vol=1793.159, self.amt=35945189.4156 
2023-03-12 00:20:01,586:INFO:sr_min:main.py:172:handleKline:449472: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5759  20230311   235500    235959  ...         0.0        0.0       0
5760  20230312   000000    000459  ...         0.0        0.0       0
5761  20230312   000500    000959  ...         0.0        0.0       0
5762  20230312   001000    001459  ...         0.0        0.0       0
5763  20230312   001500    001959  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-03-12 00:20:01,590:INFO:sr_min:main.py:175:handleKline:449472: self.closeSec=1678551599, self.tradeDate='20230312', self.openTime='001500', self.closeTime='001959',self.symbol='BTCUSDT',self.open=20025.0, self.close=20039.3, self.high=20070.2, self.low=20017.3, self.vol=1793.159, self.amt=35945189.4156, ukdf['pct'].iloc[-1]=0.000714 , ukdf['amount'].iloc[-1]=35945189.4156, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5763, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': []}
type(curSign)=<class 'int'>, curSign=0, self.sign=0
--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=0, self.total=1000000.0, self.flagDict['side']='', self.tradeCount=0, self.count=26075
self.closeSec=1678551899, self.tradeDate='20230312', self.openTime='002000', self.closeTime='002459', self.symbol='BTCUSDT', self.open=20039.4, self.close=20036.6, self.high=20066.7, self.low=20035.8, self.vol=1064.145, self.amt=21338402.611 
127.0.0.1 - - [12/Mar/2023 00:25:01] "POST / HTTP/1.1" 200 -
2023-03-12 00:25:01,705:INFO:sr_min:main.py:172:handleKline:449472: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5760  20230312   000000    000459  ...         0.0        0.0       0
5761  20230312   000500    000959  ...         0.0        0.0       0
5762  20230312   001000    001459  ...         0.0        0.0       0
5763  20230312   001500    001959  ...         0.0        0.0       0
5764  20230312   002000    002459  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-03-12 00:25:01,705:INFO:sr_min:main.py:175:handleKline:449472: self.closeSec=1678551899, self.tradeDate='20230312', self.openTime='002000', self.closeTime='002459',self.symbol='BTCUSDT',self.open=20039.4, self.close=20036.6, self.high=20066.7, self.low=20035.8, self.vol=1064.145, self.amt=21338402.611, ukdf['pct'].iloc[-1]=-0.000135 , ukdf['amount'].iloc[-1]=21338402.611, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5764, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': []}
type(curSign)=<class 'int'>, curSign=0, self.sign=0


## /root/FIL/strategy/s_rsrs/log.txt ----- -----

2023-03-11 20:00:11,178:INFO:s_rsrs:main.py:343:handleOrderNew:185271: handleOrderNew: data=OrderType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'clientorderid': '41953F1678536005831I0L65', 'symbol': 'BTCUSDT', 'gatewayorderid': 1678536005927620, 'quantity': '42.135', 'price': '20070', 'stopprice': '0', 'ordertype': '', 'side': 'BUY', 'status': 'FILLED', 'positionside': 'LONG', 'createtime': 1678536005505, 'updatetime': 1678536005927, 'tradetype': 'usdt', 'selfid': 41953, 'filltrades': [TradeType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'tradeid': 1678536005927, 'clientorderid': '41953F1678536005831I0L65', 'price': '20070', 'quantity': '42.135', 'commission': '845.64945', 'commissionasset': 'USDT', 'tradetime': 1678536005927, 'tradetype': 'usdt', 'gatetype': 'simulator', 'handletime': 1678536005927}], 'gatetype': 'simulator', 'handletime': 0}
2023-03-11 20:00:11,178:INFO:s_rsrs:main.py:346:handleOrderFilled:185271: handleOrderFilled: data=OrderType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'clientorderid': '41953F1678536005831I0L65', 'symbol': 'BTCUSDT', 'gatewayorderid': 1678536005927620, 'quantity': '42.135', 'price': '20070', 'stopprice': '0', 'ordertype': '', 'side': 'BUY', 'status': 'FILLED', 'positionside': 'LONG', 'createtime': 1678536005505, 'updatetime': 1678536005927, 'tradetype': 'usdt', 'selfid': 41953, 'filltrades': [TradeType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'tradeid': 1678536005927, 'clientorderid': '41953F1678536005831I0L65', 'price': '20070', 'quantity': '42.135', 'commission': '845.64945', 'commissionasset': 'USDT', 'tradetime': 1678536005927, 'tradetype': 'usdt', 'gatetype': 'simulator', 'handletime': 1678536005927}], 'gatetype': 'simulator', 'handletime': 0}
127.0.0.1 - - [11/Mar/2023 20:00:11] "POST / HTTP/1.1" 200 -
2023-03-11 20:00:11,304:INFO:s_rsrs:main.py:343:handleOrderNew:185271: handleOrderNew: data=OrderType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'clientorderid': '41954F1678536011152I0L65', 'symbol': 'BTCUSDT', 'gatewayorderid': 1678536011247025, 'quantity': '55.825', 'price': '20070', 'stopprice': '0', 'ordertype': '', 'side': 'BUY', 'status': 'FILLED', 'positionside': 'LONG', 'createtime': 1678536010956, 'updatetime': 1678536011247, 'tradetype': 'usdt', 'selfid': 41954, 'filltrades': [TradeType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'tradeid': 1678536011247, 'clientorderid': '41954F1678536011152I0L65', 'price': '20070', 'quantity': '55.825', 'commission': '1120.40775', 'commissionasset': 'USDT', 'tradetime': 1678536011247, 'tradetype': 'usdt', 'gatetype': 'simulator', 'handletime': 1678536011247}], 'gatetype': 'simulator', 'handletime': 0}
127.0.0.1 - - [11/Mar/2023 20:00:11] "POST / HTTP/1.1" 200 -
2023-03-11 20:00:11,553:INFO:s_rsrs:main.py:346:handleOrderFilled:185271: handleOrderFilled: data=OrderType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'clientorderid': '41954F1678536011152I0L65', 'symbol': 'BTCUSDT', 'gatewayorderid': 1678536011247025, 'quantity': '55.825', 'price': '20070', 'stopprice': '0', 'ordertype': '', 'side': 'BUY', 'status': 'FILLED', 'positionside': 'LONG', 'createtime': 1678536010956, 'updatetime': 1678536011247, 'tradetype': 'usdt', 'selfid': 41954, 'filltrades': [TradeType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'tradeid': 1678536011247, 'clientorderid': '41954F1678536011152I0L65', 'price': '20070', 'quantity': '55.825', 'commission': '1120.40775', 'commissionasset': 'USDT', 'tradetime': 1678536011247, 'tradetype': 'usdt', 'gatetype': 'simulator', 'handletime': 1678536011247}], 'gatetype': 'simulator', 'handletime': 0}
--handleKline--:  version='2.0.0', self.name='s_rsrs', self.symbol='BTCUSDT', interval='4h', intervalSec=14400, wid=25, thd=0.6, self.sign=1, self.total=1119287.34225, self.flagDict['side']='buy', self.tradeCount=24, self.count=638
self.closeSec=1678550399, self.tradeDate='20230311', self.openTime='200000', self.closeTime='235959', self.symbol='BTCUSDT', self.open=20077.5, self.close=20052.3, self.high=20195.0, self.low=20017.3, self.vol=70208.55, self.amt=1410859111.1827 
127.0.0.1 - - [12/Mar/2023 00:00:01] "POST / HTTP/1.1" 200 -
2023-03-12 00:00:01,823:INFO:s_rsrs:main.py:141:handleKline:185271: self.closeSec=1678550399, self.tradeDate='20230311', self.openTime='200000', self.closeTime='235959',self.symbol='BTCUSDT',self.open=20077.5, self.close=20052.3, self.high=20195.0, self.low=20017.3, self.vol=70208.55, self.amt=1410859111.1827 
2023-03-12 00:00:01,921:INFO:s_rsrs:main.py:142:handleKline:185271: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime  ...         vol           amt       pct
721  20230311   040000    075959  ...  104598.079  2.097184e+09  0.006451
722  20230311   080000    115959  ...  207973.491  4.246584e+09  0.011961
723  20230311   120000    155959  ...  139731.915  2.816961e+09 -0.026338
724  20230311   160000    195959  ...  150197.076  3.006404e+09  0.011746
725  20230311   200000    235959  ...   70208.550  1.410859e+09 -0.001255

[5 rows x 11 columns]
2023-03-12 00:00:05,248:INFO:s_rsrs:main.py:151:handleKline:185271: df_s.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec  ...  index      beta    zscore  signal
721  20230311   040000    075959  1678492799  ...    721  0.715669  0.541569     NaN
722  20230311   080000    115959  1678507199  ...    722  0.720860  0.553101     NaN
723  20230311   120000    155959  1678521599  ...    723  0.719905  0.545570     NaN
724  20230311   160000    195959  1678535999  ...    724  0.746170  0.634227     1.0
725  20230311   200000    235959  1678550399  ...    725  0.778201  0.737284     1.0

[5 rows x 15 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '55.825', 'enterprice': '20070', 'countrevence': '0', 'unrealprofit': '-835.0056295735', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '20055.04244282', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'numpy.int64'>, curSign=1, self.sign=1


