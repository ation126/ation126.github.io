# 20230808 00:26:01

## /root/FIL/strategy/amihud/log.txt ----- -----

--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=373746.4768026, self.flagDict['side']='sell', self.tradeCount=2, self.count=24640
self.closeSec=1691425199, self.tradeDate='20230808', self.openTime='001500', self.closeTime='001959', self.symbol='BTCUSDT', self.open=28783.7, self.close=28788.6, self.high=28791.9, self.low=28682.3, self.vol=9281.313, self.amt=266760009.79601 
127.0.0.1 - - [08/Aug/2023 00:20:01] "POST / HTTP/1.1" 200 -
2023-08-08 00:20:06,422:INFO:amihud:main.py:172:handleKline:2219019: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5759  20230807   235500    235959  ...         0.0        0.0       0
5760  20230808   000000    000459  ...         0.0        0.0       0
5761  20230808   000500    000959  ...         0.0        0.0       0
5762  20230808   001000    001459  ...         0.0        0.0       0
5763  20230808   001500    001959  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-08-08 00:20:06,443:INFO:amihud:main.py:175:handleKline:2219019: self.closeSec=1691425199, self.tradeDate='20230808', self.openTime='001500', self.closeTime='001959',self.symbol='BTCUSDT',self.open=28783.7, self.close=28788.6, self.high=28791.9, self.low=28682.3, self.vol=9281.313, self.amt=266760009.79601, ukdf['pct'].iloc[-1]=0.000295 , ukdf['amount'].iloc[-1]=266760009.79601, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5763, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '13.926', 'enterprice': '26864.9', 'countrevence': '0', 'unrealprofit': '-26850.7206', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '28793', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1
127.0.0.1 - - [08/Aug/2023 00:25:00] "POST / HTTP/1.1" 200 -
--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=373746.4768026, self.flagDict['side']='sell', self.tradeCount=2, self.count=24641
self.closeSec=1691425499, self.tradeDate='20230808', self.openTime='002000', self.closeTime='002459', self.symbol='BTCUSDT', self.open=28788.7, self.close=28924.3, self.high=28930.4, self.low=28787.8, self.vol=7196.529, self.amt=207740998.0402 
2023-08-08 00:25:00,798:INFO:amihud:main.py:172:handleKline:2219019: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5760  20230808   000000    000459  ...         0.0        0.0       0
5761  20230808   000500    000959  ...         0.0        0.0       0
5762  20230808   001000    001459  ...         0.0        0.0       0
5763  20230808   001500    001959  ...         0.0        0.0       0
5764  20230808   002000    002459  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-08-08 00:25:00,798:INFO:amihud:main.py:175:handleKline:2219019: self.closeSec=1691425499, self.tradeDate='20230808', self.openTime='002000', self.closeTime='002459',self.symbol='BTCUSDT',self.open=28788.7, self.close=28924.3, self.high=28930.4, self.low=28787.8, self.vol=7196.529, self.amt=207740998.0402, ukdf['pct'].iloc[-1]=0.004714 , ukdf['amount'].iloc[-1]=207740998.0402, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5764, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '13.926', 'enterprice': '26864.9', 'countrevence': '0', 'unrealprofit': '-28686.1674', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '28924.8', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1


## /root/FIL/strategy/factorcheck/log.txt ----- -----


self.closeSec=1691425199, self.tradeDate='20230808', self.openTime='001500', self.closeTime='001959', self.symbol='BTCUSDT', self.open=28783.7, self.close=28788.6, self.high=28791.9, self.low=28682.3 
127.0.0.1 - - [08/Aug/2023 00:20:01] "POST / HTTP/1.1" 200 -
2023-08-08 00:20:04,402:INFO:factorcheck2:main.py:126:handleKline:2218005: self.closeSec=1691425199, self.tradeDate='20230808', self.openTime='001500', self.closeTime='001959',self.symbol='BTCUSDT',self.open=28783.7, self.close=28788.6, self.high=28791.9, self.low=28682.3   
2023-08-08 00:20:05,662:INFO:factorcheck2:main.py:127:handleKline:2218005: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime    closeSec  ...      low       pct  index  idx
1439  20230807   235500    235959  1691423999  ...  28771.0  0.000753   1727    5
1440  20230808   000000    000459  1691424299  ...  28728.0 -0.000904   1440    0
1441  20230808   000500    000959  1691424599  ...  28822.2 -0.000035   1441    1
1442  20230808   001000    001459  1691424899  ...  28747.0 -0.001765   1442    2
1443  20230808   001500    001959  1691425199  ...  28682.3  0.000295   1443    3

[5 rows x 11 columns]
2023-08-08 00:20:05,671:INFO:factorcheck2:main.py:128:handleKline:2218005: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}
127.0.0.1 - - [08/Aug/2023 00:25:00] "POST / HTTP/1.1" 200 -

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=155, self.factor=0.5536391175465031, self.count=24643 

self.closeSec=1691425499, self.tradeDate='20230808', self.openTime='002000', self.closeTime='002459', self.symbol='BTCUSDT', self.open=28788.7, self.close=28924.3, self.high=28930.4, self.low=28787.8 
2023-08-08 00:25:00,746:INFO:factorcheck2:main.py:126:handleKline:2218005: self.closeSec=1691425499, self.tradeDate='20230808', self.openTime='002000', self.closeTime='002459',self.symbol='BTCUSDT',self.open=28788.7, self.close=28924.3, self.high=28930.4, self.low=28787.8   
2023-08-08 00:25:00,772:INFO:factorcheck2:main.py:127:handleKline:2218005: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime    closeSec  ...      low       pct  index  idx
1440  20230808   000000    000459  1691424299  ...  28728.0 -0.000904   1440    0
1441  20230808   000500    000959  1691424599  ...  28822.2 -0.000035   1441    1
1442  20230808   001000    001459  1691424899  ...  28747.0 -0.001765   1442    2
1443  20230808   001500    001959  1691425199  ...  28682.3  0.000295   1443    3
1444  20230808   002000    002459  1691425499  ...  28787.8  0.004714   1444    4

[5 rows x 11 columns]
2023-08-08 00:25:00,772:INFO:factorcheck2:main.py:128:handleKline:2218005: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}


## /root/FIL/strategy/logic/log.txt ----- -----

2023-08-08 00:00:17,617:DEBUG:logic:main.py:463:getModel:2218526: df_s.iloc[-5:,:] :
          date closeTime     open  ...    alpha58   alpha67   alpha72
5802  20230807    212959  29070.3  ...  48.333333  0.488544  0.546627
5803  20230807    215959  29060.8  ...  47.916667  0.471588  0.572546
5804  20230807    222959  29019.3  ...  47.916667  0.461418  0.597248
5805  20230807    225959  28991.4  ...  48.333333  0.472572  0.607587
5806  20230807    232959  29018.3  ...  47.916667  0.438542  0.628008

[5 rows x 33 columns]
0.5422794117647058
acc is : 0.5422794117647058
2023-08-08 00:00:17,676:INFO:logic:main.py:468:getModel:2218526: df_pred.iloc[-5:,:] :
     pred    prob_0    prob_1  actual  ...       nav  sign  cost_        bm
539     1  0.495639  0.504361       0  ...  0.987078   1.0    0.0  0.987159
540     1  0.485647  0.514353       0  ...  0.986204   1.0    0.0  0.986284
541     1  0.487214  0.512786       1  ...  0.987044   1.0    0.0  0.987124
542     0  0.506025  0.493975       0  ...  0.983959   1.0    0.0  0.984039
543     1  0.466212  0.533788       0  ...  0.981425   1.0    0.0  0.981505

[5 rows x 10 columns]
2023-08-08 00:00:17,687:INFO:logic:main.py:478:getModel:2218526: df_panel.iloc[-5:,:] :
    pred    prob_0    prob_1  actual  ...       nav  sign  cost_        bm
45     1  0.495825  0.504175       0  ...  0.987078   1.0    0.0  0.985985
46     1  0.485696  0.514304       0  ...  0.986204   1.0    0.0  0.987238
47     1  0.487249  0.512751       1  ...  0.987044   1.0    0.0  0.988079
48     0  0.505910  0.494090       0  ...  0.983959   1.0    0.0  0.983303
49     1  0.466212  0.533788       0  ...  0.981425   1.0    0.0  0.981505

[5 rows x 10 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '24.06', 'enterprice': '29131.5', 'countrevence': '0', 'unrealprofit': '-7116.0378621696', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '28835.73782784', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}


## /root/FIL/strategy/modifiedmom/log.txt ----- -----

127.0.0.1 - - [08/Aug/2023 00:00:04] "POST / HTTP/1.1" 200 -
2023-08-08 00:00:04,235:INFO:modifiedmom:main.py:319:handleOrderFilled:2218259: handleOrderFilled: data=OrderType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'clientorderid': '42823F1691424003508I0L59', 'symbol': 'BTCUSDT', 'gatewayorderid': 1691424003929849, 'quantity': '24.919', 'price': '28851.5', 'stopprice': '0', 'ordertype': '', 'side': 'SELL', 'status': 'FILLED', 'positionside': 'SHORT', 'createtime': 1691424002600, 'updatetime': 1691424003929, 'tradetype': 'usdt', 'selfid': 42823, 'filltrades': [TradeType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'tradeid': 1691424003929, 'clientorderid': '42823F1691424003508I0L59', 'price': '28851.5', 'quantity': '24.919', 'commission': '718.9505285', 'commissionasset': 'USDT', 'tradetime': 1691424003929, 'tradetype': 'usdt', 'gatetype': 'simulator', 'handletime': 1691424003929}], 'gatetype': 'simulator', 'handletime': 0}
127.0.0.1 - - [08/Aug/2023 00:10:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=12320 

self.closeSec=1691424599, self.tradeDate='20230808', self.openTime='000000', self.closeTime='000959', self.symbol='BTCUSDT', self.open='28853.2', self.close='28831'
2023-08-08 00:10:01,142:INFO:modifiedmom:main.py:144:handleKline:2218259: self.closeSec=1691424599, self.tradeDate='20230808', self.openTime='000000', self.closeTime='000959',self.symbol='BTCUSDT',self.open='28853.2', self.close='28831'
2023-08-08 00:10:01,151:INFO:modifiedmom:main.py:145:handleKline:2218259: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec     open    close       pct
572  20230807   232000    232959  1691422199  28920.1  28927.7  0.000259
573  20230807   233000    233959  1691422799  28927.7  28843.9 -0.002897
574  20230807   234000    234959  1691423399    28844  28850.3  0.000222
575  20230807   235000    235959  1691423999  28850.2  28853.2  0.000101
576  20230808   000000    000959  1691424599  28853.2    28831 -0.000769
2023-08-08 00:10:01,151:INFO:modifiedmom:main.py:146:handleKline:2218259: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': True, 'isOpen': False, 'isClose': True, 'isTrig': False}

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=12321 

self.closeSec=1691425199, self.tradeDate='20230808', self.openTime='001000', self.closeTime='001959', self.symbol='BTCUSDT', self.open='28831', self.close='28788.6'
127.0.0.1 - - [08/Aug/2023 00:20:04] "POST / HTTP/1.1" 200 -
2023-08-08 00:20:06,902:INFO:modifiedmom:main.py:144:handleKline:2218259: self.closeSec=1691425199, self.tradeDate='20230808', self.openTime='001000', self.closeTime='001959',self.symbol='BTCUSDT',self.open='28831', self.close='28788.6'
2023-08-08 00:20:07,633:INFO:modifiedmom:main.py:145:handleKline:2218259: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec     open    close       pct
573  20230807   233000    233959  1691422799  28927.7  28843.9 -0.002897
574  20230807   234000    234959  1691423399    28844  28850.3  0.000222
575  20230807   235000    235959  1691423999  28850.2  28853.2  0.000101
576  20230808   000000    000959  1691424599  28853.2    28831 -0.000769
577  20230808   001000    001959  1691425199    28831  28788.6 -0.001471
2023-08-08 00:20:07,641:INFO:modifiedmom:main.py:146:handleKline:2218259: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': True, 'isOpen': False, 'isClose': True, 'isTrig': False}


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

127.0.0.1 - - [08/Aug/2023 00:00:03] "POST / HTTP/1.1" 200 -
2023-08-08 00:00:03,955:INFO:pyemd2:main.py:303:handleOrderFilled:2217508: handleOrderFilled: data=OrderType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'clientorderid': '42821F1691424003376I0L57', 'symbol': 'BTCUSDT', 'gatewayorderid': 1691424003787327, 'quantity': '33.93', 'price': '28851.5', 'stopprice': '0', 'ordertype': '', 'side': 'SELL', 'status': 'FILLED', 'positionside': 'SHORT', 'createtime': 1691424002505, 'updatetime': 1691424003787, 'tradetype': 'usdt', 'selfid': 42821, 'filltrades': [TradeType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'tradeid': 1691424003787, 'clientorderid': '42821F1691424003376I0L57', 'price': '28851.5', 'quantity': '33.93', 'commission': '978.931395', 'commissionasset': 'USDT', 'tradetime': 1691424003787, 'tradetype': 'usdt', 'gatetype': 'simulator', 'handletime': 1691424003787}], 'gatetype': 'simulator', 'handletime': 0}
127.0.0.1 - - [08/Aug/2023 00:10:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=12323 

self.closeSec=1691424599, self.tradeDate='20230808', self.openTime='000000', self.closeTime='000959', self.symbol='BTCUSDT', self.open='28853.2', self.close='28831'
2023-08-08 00:10:01,136:INFO:pyemd2:main.py:125:handleKline:2217508: self.closeSec=1691424599, self.tradeDate='20230808', self.openTime='000000', self.closeTime='000959',self.symbol='BTCUSDT',self.open='28853.2', self.close='28831'
2023-08-08 00:10:01,143:INFO:pyemd2:main.py:126:handleKline:2217508: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
17420  20230807   232000    232959  1691422199  28920.1  28927.7
17421  20230807   233000    233959  1691422799  28927.7  28843.9
17422  20230807   234000    234959  1691423399    28844  28850.3
17423  20230807   235000    235959  1691423999  28850.2  28853.2
17424  20230808   000000    000959  1691424599  28853.2    28831
2023-08-08 00:10:01,144:INFO:pyemd2:main.py:127:handleKline:2217508: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=12324 

self.closeSec=1691425199, self.tradeDate='20230808', self.openTime='001000', self.closeTime='001959', self.symbol='BTCUSDT', self.open='28831', self.close='28788.6'
127.0.0.1 - - [08/Aug/2023 00:20:04] "POST / HTTP/1.1" 200 -
2023-08-08 00:20:08,745:INFO:pyemd2:main.py:125:handleKline:2217508: self.closeSec=1691425199, self.tradeDate='20230808', self.openTime='001000', self.closeTime='001959',self.symbol='BTCUSDT',self.open='28831', self.close='28788.6'
2023-08-08 00:20:08,823:INFO:pyemd2:main.py:126:handleKline:2217508: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
17421  20230807   233000    233959  1691422799  28927.7  28843.9
17422  20230807   234000    234959  1691423399    28844  28850.3
17423  20230807   235000    235959  1691423999  28850.2  28853.2
17424  20230808   000000    000959  1691424599  28853.2    28831
17425  20230808   001000    001959  1691425199    28831  28788.6
2023-08-08 00:20:08,825:INFO:pyemd2:main.py:127:handleKline:2217508: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}


## /root/FIL/strategy/similarity/log.txt ----- -----

127.0.0.1 - - [08/Aug/2023 00:00:04] "POST / HTTP/1.1" 200 -
2023-08-08 00:00:04,099:INFO:testStrategy:main.py:308:handleOrderFilled:2217133: handleOrderFilled: data=OrderType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'clientorderid': '42822F1691424003498I0L2', 'symbol': 'BTCUSDT', 'gatewayorderid': 1691424003927761, 'quantity': '37.198', 'price': '28851.5', 'stopprice': '0', 'ordertype': '', 'side': 'SELL', 'status': 'FILLED', 'positionside': 'SHORT', 'createtime': 1691424002597, 'updatetime': 1691424003927, 'tradetype': 'usdt', 'selfid': 42822, 'filltrades': [TradeType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'tradeid': 1691424003927, 'clientorderid': '42822F1691424003498I0L2', 'price': '28851.5', 'quantity': '37.198', 'commission': '1073.218097', 'commissionasset': 'USDT', 'tradetime': 1691424003927, 'tradetype': 'usdt', 'gatetype': 'simulator', 'handletime': 1691424003927}], 'gatetype': 'simulator', 'handletime': 0}
127.0.0.1 - - [08/Aug/2023 00:10:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=12323 

self.closeSec=1691424599, self.tradeDate='20230808', self.openTime='000000', self.closeTime='000959', self.symbol='BTCUSDT', self.open='28853.2', self.close='28831'
2023-08-08 00:10:01,137:INFO:testStrategy:main.py:101:handleKline:2217133: self.closeSec=1691424599, self.tradeDate='20230808', self.openTime='000000', self.closeTime='000959',self.symbol='BTCUSDT',self.open='28853.2', self.close='28831'
2023-08-08 00:10:01,152:INFO:testStrategy:main.py:102:handleKline:2217133: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
12236  20230807   232000    232959  1691422199  28920.1  28927.7
12237  20230807   233000    233959  1691422799  28927.7  28843.9
12238  20230807   234000    234959  1691423399    28844  28850.3
12239  20230807   235000    235959  1691423999  28850.2  28853.2
12240  20230808   000000    000959  1691424599  28853.2    28831
2023-08-08 00:10:01,152:INFO:testStrategy:main.py:103:handleKline:2217133: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': True, 'isOpen': False, 'isClose': True, 'isTrig': False, 'isCorr': False}

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=12324 

self.closeSec=1691425199, self.tradeDate='20230808', self.openTime='001000', self.closeTime='001959', self.symbol='BTCUSDT', self.open='28831', self.close='28788.6'
127.0.0.1 - - [08/Aug/2023 00:20:04] "POST / HTTP/1.1" 200 -
2023-08-08 00:20:08,573:INFO:testStrategy:main.py:101:handleKline:2217133: self.closeSec=1691425199, self.tradeDate='20230808', self.openTime='001000', self.closeTime='001959',self.symbol='BTCUSDT',self.open='28831', self.close='28788.6'
2023-08-08 00:20:08,716:INFO:testStrategy:main.py:102:handleKline:2217133: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
12237  20230807   233000    233959  1691422799  28927.7  28843.9
12238  20230807   234000    234959  1691423399    28844  28850.3
12239  20230807   235000    235959  1691423999  28850.2  28853.2
12240  20230808   000000    000959  1691424599  28853.2    28831
12241  20230808   001000    001959  1691425199    28831  28788.6
2023-08-08 00:20:08,717:INFO:testStrategy:main.py:103:handleKline:2217133: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': True, 'isOpen': False, 'isClose': True, 'isTrig': False, 'isCorr': False}


## /root/FIL/strategy/sr_min/log.txt ----- -----

--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=1, self.total=996015.990996, self.flagDict['side']='buy', self.tradeCount=1, self.count=24640
self.closeSec=1691425199, self.tradeDate='20230808', self.openTime='001500', self.closeTime='001959', self.symbol='BTCUSDT', self.open=28783.7, self.close=28788.6, self.high=28791.9, self.low=28682.3, self.vol=9281.313, self.amt=266760009.79601 
127.0.0.1 - - [08/Aug/2023 00:20:01] "POST / HTTP/1.1" 200 -
2023-08-08 00:20:06,405:INFO:sr_min:main.py:172:handleKline:2219263: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5759  20230807   235500    235959  ...         0.0        0.0       0
5760  20230808   000000    000459  ...         0.0        0.0       0
5761  20230808   000500    000959  ...         0.0        0.0       0
5762  20230808   001000    001459  ...         0.0        0.0       0
5763  20230808   001500    001959  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-08-08 00:20:06,433:INFO:sr_min:main.py:175:handleKline:2219263: self.closeSec=1691425199, self.tradeDate='20230808', self.openTime='001500', self.closeTime='001959',self.symbol='BTCUSDT',self.open=28783.7, self.close=28788.6, self.high=28791.9, self.low=28682.3, self.vol=9281.313, self.amt=266760009.79601, ukdf['pct'].iloc[-1]=0.000295 , ukdf['amount'].iloc[-1]=266760009.79601, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5763, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '37.141', 'enterprice': '26844', 'countrevence': '0', 'unrealprofit': '72406.3795', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '28793.5', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=1
--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=1, self.total=996015.990996, self.flagDict['side']='buy', self.tradeCount=1, self.count=24641
self.closeSec=1691425499, self.tradeDate='20230808', self.openTime='002000', self.closeTime='002459', self.symbol='BTCUSDT', self.open=28788.7, self.close=28924.3, self.high=28930.4, self.low=28787.8, self.vol=7196.529, self.amt=207740998.0402 
127.0.0.1 - - [08/Aug/2023 00:25:00] "POST / HTTP/1.1" 200 -
2023-08-08 00:25:00,783:INFO:sr_min:main.py:172:handleKline:2219263: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5760  20230808   000000    000459  ...         0.0        0.0       0
5761  20230808   000500    000959  ...         0.0        0.0       0
5762  20230808   001000    001459  ...         0.0        0.0       0
5763  20230808   001500    001959  ...         0.0        0.0       0
5764  20230808   002000    002459  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-08-08 00:25:00,783:INFO:sr_min:main.py:175:handleKline:2219263: self.closeSec=1691425499, self.tradeDate='20230808', self.openTime='002000', self.closeTime='002459',self.symbol='BTCUSDT',self.open=28788.7, self.close=28924.3, self.high=28930.4, self.low=28787.8, self.vol=7196.529, self.amt=207740998.0402, ukdf['pct'].iloc[-1]=0.004714 , ukdf['amount'].iloc[-1]=207740998.0402, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5764, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '37.141', 'enterprice': '26844', 'countrevence': '0', 'unrealprofit': '77282.9928', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '28924.8', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=1


## /root/FIL/strategy/s_rsrs/log.txt ----- -----

723  20230807   120000    155959  1691395199  ...    723  0.120496 -0.929934    -1.0
724  20230807   160000    195959  1691409599  ...    724  0.120296 -0.932049    -1.0

[5 rows x 15 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '54.719', 'enterprice': '28996.8', 'countrevence': '0', 'unrealprofit': '-4769.50025799758', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '29083.96351282', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'numpy.int64'>, curSign=-1, self.sign=-1
127.0.0.1 - - [08/Aug/2023 00:00:01] "POST / HTTP/1.1" 200 -
--handleKline--:  version='2.0.0', self.name='s_rsrs', self.symbol='BTCUSDT', interval='4h', intervalSec=14400, wid=25, thd=0.6, self.sign=-1, self.total=1585089.2233008002, self.flagDict['side']='sell', self.tradeCount=18, self.count=513
self.closeSec=1691423999, self.tradeDate='20230807', self.openTime='200000', self.closeTime='235959', self.symbol='BTCUSDT', self.open=29085.9, self.close=28853.2, self.high=29148.8, self.low=28771.0, self.vol=85465.104, self.amt=2475642123.4998 
2023-08-08 00:00:01,644:INFO:s_rsrs:main.py:141:handleKline:2218689: self.closeSec=1691423999, self.tradeDate='20230807', self.openTime='200000', self.closeTime='235959',self.symbol='BTCUSDT',self.open=29085.9, self.close=28853.2, self.high=29148.8, self.low=28771.0, self.vol=85465.104, self.amt=2475642123.4998 
2023-08-08 00:00:01,658:INFO:s_rsrs:main.py:142:handleKline:2218689: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime  ...        vol           amt       pct
721  20230807   040000    075959  ...  30590.873  8.908952e+08 -0.000031
722  20230807   080000    115959  ...  29960.579  8.727741e+08  0.002504
723  20230807   120000    155959  ...  22738.520  6.617512e+08 -0.002199
724  20230807   160000    195959  ...  23220.442  6.754080e+08  0.000038
725  20230807   200000    235959  ...  85465.104  2.475642e+09 -0.007997

[5 rows x 11 columns]
2023-08-08 00:00:02,450:INFO:s_rsrs:main.py:151:handleKline:2218689: df_s.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec  ...  index      beta    zscore  signal
721  20230807   040000    075959  1691366399  ...    721  0.143837 -0.828316    -1.0
722  20230807   080000    115959  1691380799  ...    722  0.135147 -0.865926    -1.0
723  20230807   120000    155959  1691395199  ...    723  0.120496 -0.929934    -1.0
724  20230807   160000    195959  1691409599  ...    724  0.120296 -0.932049    -1.0
725  20230807   200000    235959  1691423999  ...    725  0.060565 -1.198875    -1.0

[5 rows x 15 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '54.719', 'enterprice': '28996.8', 'countrevence': '0', 'unrealprofit': '7950.6707', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '28851.5', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'numpy.int64'>, curSign=-1, self.sign=-1


