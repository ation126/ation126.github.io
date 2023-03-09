# 20230310 00:26:02

## /root/FIL/strategy/amihud/log.txt ----- -----

--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=993672.4896432, self.flagDict['side']='sell', self.tradeCount=2, self.count=29500
self.closeSec=1678378799, self.tradeDate='20230310', self.openTime='001500', self.closeTime='001959', self.symbol='BTCUSDT', self.open=21639.8, self.close=21638.3, self.high=21666.4, self.low=21638.3, self.vol=2617.83, self.amt=56690739.5667 
127.0.0.1 - - [10/Mar/2023 00:20:01] "POST / HTTP/1.1" 200 -
2023-03-10 00:20:01,775:INFO:amihud:main.py:172:handleKline:200676: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5759  20230309   235500    235959  ...         0.0        0.0       0
5760  20230310   000000    000459  ...         0.0        0.0       0
5761  20230310   000500    000959  ...         0.0        0.0       0
5762  20230310   001000    001459  ...         0.0        0.0       0
5763  20230310   001500    001959  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-03-10 00:20:01,778:INFO:amihud:main.py:175:handleKline:200676: self.closeSec=1678378799, self.tradeDate='20230310', self.openTime='001500', self.closeTime='001959',self.symbol='BTCUSDT',self.open=21639.8, self.close=21638.3, self.high=21666.4, self.low=21638.3, self.vol=2617.83, self.amt=56690739.5667, ukdf['pct'].iloc[-1]=-6.9e-05 , ukdf['amount'].iloc[-1]=56690739.5667, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5763, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '60.176', 'enterprice': '16529.3', 'countrevence': '0', 'unrealprofit': '-307584.11622731952', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '21640.70847227', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1
127.0.0.1 - - [10/Mar/2023 00:25:01] "POST / HTTP/1.1" 200 -
--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=993672.4896432, self.flagDict['side']='sell', self.tradeCount=2, self.count=29501
self.closeSec=1678379099, self.tradeDate='20230310', self.openTime='002000', self.closeTime='002459', self.symbol='BTCUSDT', self.open=21638.3, self.close=21638.7, self.high=21644.1, self.low=21614.7, self.vol=1442.831, self.amt=31208408.3327 
2023-03-10 00:25:01,600:INFO:amihud:main.py:172:handleKline:200676: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5760  20230310   000000    000459  ...         0.0        0.0       0
5761  20230310   000500    000959  ...         0.0        0.0       0
5762  20230310   001000    001459  ...         0.0        0.0       0
5763  20230310   001500    001959  ...         0.0        0.0       0
5764  20230310   002000    002459  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-03-10 00:25:01,600:INFO:amihud:main.py:175:handleKline:200676: self.closeSec=1678379099, self.tradeDate='20230310', self.openTime='002000', self.closeTime='002459',self.symbol='BTCUSDT',self.open=21638.3, self.close=21638.7, self.high=21644.1, self.low=21614.7, self.vol=1442.831, self.amt=31208408.3327, ukdf['pct'].iloc[-1]=1.8e-05 , ukdf['amount'].iloc[-1]=31208408.3327, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5764, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '60.176', 'enterprice': '16529.3', 'countrevence': '0', 'unrealprofit': '-307541.4832', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '21640', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1


## /root/FIL/strategy/factorcheck/log.txt ----- -----


self.closeSec=1678378799, self.tradeDate='20230310', self.openTime='001500', self.closeTime='001959', self.symbol='BTCUSDT', self.open=21639.8, self.close=21638.3, self.high=21666.4, self.low=21638.3 
127.0.0.1 - - [10/Mar/2023 00:20:01] "POST / HTTP/1.1" 200 -
2023-03-10 00:20:01,633:INFO:factorcheck2:main.py:126:handleKline:185239: self.closeSec=1678378799, self.tradeDate='20230310', self.openTime='001500', self.closeTime='001959',self.symbol='BTCUSDT',self.open=21639.8, self.close=21638.3, self.high=21666.4, self.low=21638.3   
2023-03-10 00:20:01,722:INFO:factorcheck2:main.py:127:handleKline:185239: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime    closeSec  ...      low       pct  index  idx
1439  20230309   235500    235959  1678377599  ...  21625.4 -0.001620   1727    5
1440  20230310   000000    000459  1678377899  ...  21629.0 -0.000333   1440    0
1441  20230310   000500    000959  1678378199  ...  21563.1 -0.000656   1441    1
1442  20230310   001000    001459  1678378499  ...  21613.7  0.001101   1442    2
1443  20230310   001500    001959  1678378799  ...  21638.3 -0.000069   1443    3

[5 rows x 11 columns]
2023-03-10 00:20:01,722:INFO:factorcheck2:main.py:128:handleKline:185239: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': True, 'isOpenSell': False, 'isCloseBuy': False, 'isCloseSell': False, 'isOpen': True, 'isClose': False, 'isTrig': True}

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=0, self.factor=0.7507777356795268, self.count=30067 

self.closeSec=1678379099, self.tradeDate='20230310', self.openTime='002000', self.closeTime='002459', self.symbol='BTCUSDT', self.open=21638.3, self.close=21638.7, self.high=21644.1, self.low=21614.7 
2023-03-10 00:25:01,483:INFO:factorcheck2:main.py:126:handleKline:185239: self.closeSec=1678379099, self.tradeDate='20230310', self.openTime='002000', self.closeTime='002459',self.symbol='BTCUSDT',self.open=21638.3, self.close=21638.7, self.high=21644.1, self.low=21614.7   
127.0.0.1 - - [10/Mar/2023 00:25:01] "POST / HTTP/1.1" 200 -
2023-03-10 00:25:01,496:INFO:factorcheck2:main.py:127:handleKline:185239: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime    closeSec  ...      low       pct  index  idx
1440  20230310   000000    000459  1678377899  ...  21629.0 -0.000333   1440    0
1441  20230310   000500    000959  1678378199  ...  21563.1 -0.000656   1441    1
1442  20230310   001000    001459  1678378499  ...  21613.7  0.001101   1442    2
1443  20230310   001500    001959  1678378799  ...  21638.3 -0.000069   1443    3
1444  20230310   002000    002459  1678379099  ...  21614.7  0.000018   1444    4

[5 rows x 11 columns]
2023-03-10 00:25:01,496:INFO:factorcheck2:main.py:128:handleKline:185239: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': True, 'isOpenSell': False, 'isCloseBuy': False, 'isCloseSell': False, 'isOpen': True, 'isClose': False, 'isTrig': True}


## /root/FIL/strategy/logic/log.txt ----- -----

2023-03-10 00:00:34,974:DEBUG:logic:main.py:463:getModel:885513: df_s.iloc[-5:,:] :
          date closeTime     open  ...    alpha58   alpha67   alpha72
5802  20230309    212959  21603.6  ...  42.916667  0.385328  0.764692
5803  20230309    215959  21575.0  ...  43.333333  0.428968  0.760097
5804  20230309    222959  21698.7  ...  43.750000  0.443325  0.751049
5805  20230309    225959  21742.6  ...  43.750000  0.436529  0.745492
5806  20230309    232959  21716.0  ...  44.166667  0.437320  0.740046

[5 rows x 33 columns]
0.5533088235294118
acc is : 0.5533088235294118
2023-03-10 00:00:35,132:INFO:logic:main.py:468:getModel:885513: df_pred.iloc[-5:,:] :
     pred    prob_0    prob_1  actual  ...       nav  sign  cost_        bm
539     1  0.490557  0.509443       1  ...  0.899570   1.0    0.0  0.937600
540     0  0.578582  0.421418       1  ...  0.901394   1.0    0.0  0.939501
541     0  0.543900  0.456100       0  ...  0.900287   1.0    0.0  0.938348
542     0  0.514162  0.485838       1  ...  0.900387   1.0    0.0  0.938451
543     0  0.530848  0.469152       0  ...  0.897033   1.0    0.0  0.934956

[5 rows x 10 columns]
2023-03-10 00:00:35,166:INFO:logic:main.py:478:getModel:885513: df_panel.iloc[-5:,:] :
    pred    prob_0    prob_1  actual  ...       nav  sign  cost_        bm
45     1  0.490332  0.509668       1  ...  0.899570   1.0    0.0  0.938293
46     0  0.578005  0.421995       1  ...  0.901394   1.0    0.0  0.938852
47     0  0.543834  0.456166       0  ...  0.900287   1.0    0.0  0.937699
48     0  0.513899  0.486101       1  ...  0.900387   1.0    0.0  0.938285
49     0  0.530848  0.469152       0  ...  0.897033   1.0    0.0  0.934956

[5 rows x 10 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '31.291', 'enterprice': '21761.4', 'countrevence': '0', 'unrealprofit': '-3673.5634', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '21644', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}


## /root/FIL/strategy/modifiedmom/log.txt ----- -----

127.0.0.1 - - [10/Mar/2023 00:00:03] "POST / HTTP/1.1" 200 -
2023-03-10 00:00:03,082:INFO:modifiedmom:main.py:319:handleOrderFilled:185213: handleOrderFilled: data=OrderType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'clientorderid': '41924F1678377602646I0L59', 'symbol': 'BTCUSDT', 'gatewayorderid': 1678377602768073, 'quantity': '46.564', 'price': '21637.4', 'stopprice': '0', 'ordertype': '', 'side': 'BUY', 'status': 'FILLED', 'positionside': 'LONG', 'createtime': 1678377602111, 'updatetime': 1678377602768, 'tradetype': 'usdt', 'selfid': 41924, 'filltrades': [TradeType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'tradeid': 1678377602768, 'clientorderid': '41924F1678377602646I0L59', 'price': '21637.4', 'quantity': '46.564', 'commission': '1007.5238936', 'commissionasset': 'USDT', 'tradetime': 1678377602768, 'tradetype': 'usdt', 'gatetype': 'simulator', 'handletime': 1678377602768}], 'gatetype': 'simulator', 'handletime': 0}
127.0.0.1 - - [10/Mar/2023 00:10:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=15032 

self.closeSec=1678378199, self.tradeDate='20230310', self.openTime='000000', self.closeTime='000959', self.symbol='BTCUSDT', self.open='21637.4', self.close='21616'
2023-03-10 00:10:01,592:INFO:modifiedmom:main.py:144:handleKline:185213: self.closeSec=1678378199, self.tradeDate='20230310', self.openTime='000000', self.closeTime='000959',self.symbol='BTCUSDT',self.open='21637.4', self.close='21616'
2023-03-10 00:10:01,607:INFO:modifiedmom:main.py:145:handleKline:185213: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec     open    close       pct
572  20230309   232000    232959  1678375799  21670.1  21718.3  0.002206
573  20230309   233000    233959  1678376399  21718.3  21694.3 -0.001105
574  20230309   234000    234959  1678376999  21694.2  21710.8  0.000761
575  20230309   235000    235959  1678377599  21710.9  21637.4 -0.003381
576  20230310   000000    000959  1678378199  21637.4    21616 -0.000989
2023-03-10 00:10:01,607:INFO:modifiedmom:main.py:146:handleKline:185213: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': True, 'isOpen': False, 'isClose': True, 'isTrig': False}
127.0.0.1 - - [10/Mar/2023 00:20:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=15033 

self.closeSec=1678378799, self.tradeDate='20230310', self.openTime='001000', self.closeTime='001959', self.symbol='BTCUSDT', self.open='21616', self.close='21638.3'
2023-03-10 00:20:01,761:INFO:modifiedmom:main.py:144:handleKline:185213: self.closeSec=1678378799, self.tradeDate='20230310', self.openTime='001000', self.closeTime='001959',self.symbol='BTCUSDT',self.open='21616', self.close='21638.3'
2023-03-10 00:20:01,801:INFO:modifiedmom:main.py:145:handleKline:185213: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec     open    close       pct
573  20230309   233000    233959  1678376399  21718.3  21694.3 -0.001105
574  20230309   234000    234959  1678376999  21694.2  21710.8  0.000761
575  20230309   235000    235959  1678377599  21710.9  21637.4 -0.003381
576  20230310   000000    000959  1678378199  21637.4    21616 -0.000989
577  20230310   001000    001959  1678378799    21616  21638.3  0.001032
2023-03-10 00:20:01,801:INFO:modifiedmom:main.py:146:handleKline:185213: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': True, 'isOpen': False, 'isClose': True, 'isTrig': False}


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

2023-03-10 00:00:01,916:INFO:pyemd2:main.py:127:handleKline:185189: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}
2023-03-10 00:00:02,110:INFO:pyemd2:main.py:190:insertFactor:185189: curDateTime:3100000, name:pyemd2, symbol:BTCUSDT, tradeDate:20230309, closeTime:235959, close:21637.4, total:984062.1980325, pct_pre:-0.02432533614790955, thd:-0.2557799678288929, side:sell 
127.0.0.1 - - [10/Mar/2023 00:10:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=15033 

self.closeSec=1678378199, self.tradeDate='20230310', self.openTime='000000', self.closeTime='000959', self.symbol='BTCUSDT', self.open='21637.4', self.close='21616'
2023-03-10 00:10:01,636:INFO:pyemd2:main.py:125:handleKline:185189: self.closeSec=1678378199, self.tradeDate='20230310', self.openTime='000000', self.closeTime='000959',self.symbol='BTCUSDT',self.open='21637.4', self.close='21616'
2023-03-10 00:10:01,677:INFO:pyemd2:main.py:126:handleKline:185189: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
17420  20230309   232000    232959  1678375799  21670.1  21718.3
17421  20230309   233000    233959  1678376399  21718.3  21694.3
17422  20230309   234000    234959  1678376999  21694.2  21710.8
17423  20230309   235000    235959  1678377599  21710.9  21637.4
17424  20230310   000000    000959  1678378199  21637.4    21616
2023-03-10 00:10:01,677:INFO:pyemd2:main.py:127:handleKline:185189: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}
127.0.0.1 - - [10/Mar/2023 00:20:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=15034 

self.closeSec=1678378799, self.tradeDate='20230310', self.openTime='001000', self.closeTime='001959', self.symbol='BTCUSDT', self.open='21616', self.close='21638.3'
2023-03-10 00:20:01,778:INFO:pyemd2:main.py:125:handleKline:185189: self.closeSec=1678378799, self.tradeDate='20230310', self.openTime='001000', self.closeTime='001959',self.symbol='BTCUSDT',self.open='21616', self.close='21638.3'
2023-03-10 00:20:01,822:INFO:pyemd2:main.py:126:handleKline:185189: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
17421  20230309   233000    233959  1678376399  21718.3  21694.3
17422  20230309   234000    234959  1678376999  21694.2  21710.8
17423  20230309   235000    235959  1678377599  21710.9  21637.4
17424  20230310   000000    000959  1678378199  21637.4    21616
17425  20230310   001000    001959  1678378799    21616  21638.3
2023-03-10 00:20:01,822:INFO:pyemd2:main.py:127:handleKline:185189: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}


## /root/FIL/strategy/similarity/log.txt ----- -----

127.0.0.1 - - [10/Mar/2023 00:00:03] "POST / HTTP/1.1" 200 -
2023-03-10 00:00:03,444:INFO:testStrategy:main.py:308:handleOrderFilled:185174: handleOrderFilled: data=OrderType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'clientorderid': '41925F1678377602774I0L2', 'symbol': 'BTCUSDT', 'gatewayorderid': 1678377603144701, 'quantity': '53.509', 'price': '21637.3', 'stopprice': '0', 'ordertype': '', 'side': 'SELL', 'status': 'FILLED', 'positionside': 'SHORT', 'createtime': 1678377602286, 'updatetime': 1678377603144, 'tradetype': 'usdt', 'selfid': 41925, 'filltrades': [TradeType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'tradeid': 1678377603144, 'clientorderid': '41925F1678377602774I0L2', 'price': '21637.3', 'quantity': '53.509', 'commission': '1157.7902857', 'commissionasset': 'USDT', 'tradetime': 1678377603144, 'tradetype': 'usdt', 'gatetype': 'simulator', 'handletime': 1678377603144}], 'gatetype': 'simulator', 'handletime': 0}

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=15033 

self.closeSec=1678378199, self.tradeDate='20230310', self.openTime='000000', self.closeTime='000959', self.symbol='BTCUSDT', self.open='21637.4', self.close='21616'
127.0.0.1 - - [10/Mar/2023 00:10:01] "POST / HTTP/1.1" 200 -
2023-03-10 00:10:01,631:INFO:testStrategy:main.py:101:handleKline:185174: self.closeSec=1678378199, self.tradeDate='20230310', self.openTime='000000', self.closeTime='000959',self.symbol='BTCUSDT',self.open='21637.4', self.close='21616'
2023-03-10 00:10:01,674:INFO:testStrategy:main.py:102:handleKline:185174: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
12236  20230309   232000    232959  1678375799  21670.1  21718.3
12237  20230309   233000    233959  1678376399  21718.3  21694.3
12238  20230309   234000    234959  1678376999  21694.2  21710.8
12239  20230309   235000    235959  1678377599  21710.9  21637.4
12240  20230310   000000    000959  1678378199  21637.4    21616
2023-03-10 00:10:01,675:INFO:testStrategy:main.py:103:handleKline:185174: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': True, 'isOpen': False, 'isClose': True, 'isTrig': False, 'isCorr': False}
127.0.0.1 - - [10/Mar/2023 00:20:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=15034 

self.closeSec=1678378799, self.tradeDate='20230310', self.openTime='001000', self.closeTime='001959', self.symbol='BTCUSDT', self.open='21616', self.close='21638.3'
2023-03-10 00:20:01,752:INFO:testStrategy:main.py:101:handleKline:185174: self.closeSec=1678378799, self.tradeDate='20230310', self.openTime='001000', self.closeTime='001959',self.symbol='BTCUSDT',self.open='21616', self.close='21638.3'
2023-03-10 00:20:01,818:INFO:testStrategy:main.py:102:handleKline:185174: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
12237  20230309   233000    233959  1678376399  21718.3  21694.3
12238  20230309   234000    234959  1678376999  21694.2  21710.8
12239  20230309   235000    235959  1678377599  21710.9  21637.4
12240  20230310   000000    000959  1678378199  21637.4    21616
12241  20230310   001000    001959  1678378799    21616  21638.3
2023-03-10 00:20:01,818:INFO:testStrategy:main.py:103:handleKline:185174: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': True, 'isOpen': False, 'isClose': True, 'isTrig': False, 'isCorr': False}


## /root/FIL/strategy/sr_min/log.txt ----- -----

127.0.0.1 - - [10/Mar/2023 00:20:01] "POST / HTTP/1.1" 200 -
--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=0, self.total=1000000.0, self.flagDict['side']='', self.tradeCount=0, self.count=25498
self.closeSec=1678378799, self.tradeDate='20230310', self.openTime='001500', self.closeTime='001959', self.symbol='BTCUSDT', self.open=21639.8, self.close=21638.3, self.high=21666.4, self.low=21638.3, self.vol=2617.83, self.amt=56690739.5667 
2023-03-10 00:20:01,791:INFO:sr_min:main.py:172:handleKline:449472: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5759  20230309   235500    235959  ...         0.0        0.0       0
5760  20230310   000000    000459  ...         0.0        0.0       0
5761  20230310   000500    000959  ...         0.0        0.0       0
5762  20230310   001000    001459  ...         0.0        0.0       0
5763  20230310   001500    001959  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-03-10 00:20:01,791:INFO:sr_min:main.py:175:handleKline:449472: self.closeSec=1678378799, self.tradeDate='20230310', self.openTime='001500', self.closeTime='001959',self.symbol='BTCUSDT',self.open=21639.8, self.close=21638.3, self.high=21666.4, self.low=21638.3, self.vol=2617.83, self.amt=56690739.5667, ukdf['pct'].iloc[-1]=-6.9e-05 , ukdf['amount'].iloc[-1]=56690739.5667, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5763, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': []}
type(curSign)=<class 'int'>, curSign=0, self.sign=0
127.0.0.1 - - [10/Mar/2023 00:25:01] "POST / HTTP/1.1" 200 -
--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=0, self.total=1000000.0, self.flagDict['side']='', self.tradeCount=0, self.count=25499
self.closeSec=1678379099, self.tradeDate='20230310', self.openTime='002000', self.closeTime='002459', self.symbol='BTCUSDT', self.open=21638.3, self.close=21638.7, self.high=21644.1, self.low=21614.7, self.vol=1442.831, self.amt=31208408.3327 
2023-03-10 00:25:01,542:INFO:sr_min:main.py:172:handleKline:449472: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5760  20230310   000000    000459  ...         0.0        0.0       0
5761  20230310   000500    000959  ...         0.0        0.0       0
5762  20230310   001000    001459  ...         0.0        0.0       0
5763  20230310   001500    001959  ...         0.0        0.0       0
5764  20230310   002000    002459  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-03-10 00:25:01,542:INFO:sr_min:main.py:175:handleKline:449472: self.closeSec=1678379099, self.tradeDate='20230310', self.openTime='002000', self.closeTime='002459',self.symbol='BTCUSDT',self.open=21638.3, self.close=21638.7, self.high=21644.1, self.low=21614.7, self.vol=1442.831, self.amt=31208408.3327, ukdf['pct'].iloc[-1]=1.8e-05 , ukdf['amount'].iloc[-1]=31208408.3327, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5764, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': []}
type(curSign)=<class 'int'>, curSign=0, self.sign=0


## /root/FIL/strategy/s_rsrs/log.txt ----- -----

723  20230309   120000    155959  1678348799  ...    723  0.364721 -0.637468    -1.0
724  20230309   160000    195959  1678363199  ...    724  0.462091 -0.306332     NaN

[5 rows x 15 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '42.135', 'enterprice': '23350.3', 'countrevence': '0', 'unrealprofit': '71030.41422459345', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '21664.51824553', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'numpy.int64'>, curSign=-9223372036854775808, self.sign=-1
--handleKline--:  version='2.0.0', self.name='s_rsrs', self.symbol='BTCUSDT', interval='4h', intervalSec=14400, wid=25, thd=0.6, self.sign=-1, self.total=982881.0256095, self.flagDict['side']='sell', self.tradeCount=23, self.count=626
self.closeSec=1678377599, self.tradeDate='20230309', self.openTime='200000', self.closeTime='235959', self.symbol='BTCUSDT', self.open=21664.4, self.close=21637.4, self.high=21823.0, self.low=21550.0, self.vol=128925.274, self.amt=2797151479.3006 
127.0.0.1 - - [10/Mar/2023 00:00:01] "POST / HTTP/1.1" 200 -
2023-03-10 00:00:01,793:INFO:s_rsrs:main.py:141:handleKline:185271: self.closeSec=1678377599, self.tradeDate='20230309', self.openTime='200000', self.closeTime='235959',self.symbol='BTCUSDT',self.open=21664.4, self.close=21637.4, self.high=21823.0, self.low=21550.0, self.vol=128925.274, self.amt=2797151479.3006 
2023-03-10 00:00:01,837:INFO:s_rsrs:main.py:142:handleKline:185271: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime  ...         vol           amt       pct
721  20230309   040000    075959  ...  124293.667  2.713469e+09 -0.013568
722  20230309   080000    115959  ...   53609.885  1.164707e+09  0.003102
723  20230309   120000    155959  ...   30228.722  6.564517e+08 -0.003750
724  20230309   160000    195959  ...   84936.590  1.837361e+09 -0.000766
725  20230309   200000    235959  ...  128925.274  2.797151e+09 -0.001246

[5 rows x 11 columns]
2023-03-10 00:00:04,582:INFO:s_rsrs:main.py:151:handleKline:185271: df_s.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec  ...  index      beta    zscore  signal
721  20230309   040000    075959  1678319999  ...    721  0.169537 -1.290595    -1.0
722  20230309   080000    115959  1678334399  ...    722  0.268502 -0.961452    -1.0
723  20230309   120000    155959  1678348799  ...    723  0.364721 -0.637468    -1.0
724  20230309   160000    195959  1678363199  ...    724  0.462091 -0.306332     NaN
725  20230309   200000    235959  1678377599  ...    725  0.503191 -0.169857     NaN

[5 rows x 15 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '42.135', 'enterprice': '23350.3', 'countrevence': '0', 'unrealprofit': '72115.52265293115', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '21638.76510851', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'numpy.int64'>, curSign=-9223372036854775808, self.sign=-1


