# 20230730 00:26:01

## /root/FIL/strategy/amihud/log.txt ----- -----

--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=373746.4768026, self.flagDict['side']='sell', self.tradeCount=2, self.count=22048
self.closeSec=1690647599, self.tradeDate='20230730', self.openTime='001500', self.closeTime='001959', self.symbol='BTCUSDT', self.open=29277.5, self.close=29283.6, self.high=29283.6, self.low=29277.4, self.vol=158.302, self.amt=4635032.9955 
127.0.0.1 - - [30/Jul/2023 00:20:01] "POST / HTTP/1.1" 200 -
2023-07-30 00:20:05,251:INFO:amihud:main.py:172:handleKline:2219019: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5759  20230729   235500    235959  ...         0.0        0.0       0
5760  20230730   000000    000459  ...         0.0        0.0       0
5761  20230730   000500    000959  ...         0.0        0.0       0
5762  20230730   001000    001459  ...         0.0        0.0       0
5763  20230730   001500    001959  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-07-30 00:20:05,281:INFO:amihud:main.py:175:handleKline:2219019: self.closeSec=1690647599, self.tradeDate='20230730', self.openTime='001500', self.closeTime='001959',self.symbol='BTCUSDT',self.open=29277.5, self.close=29283.6, self.high=29283.6, self.low=29277.4, self.vol=158.302, self.amt=4635032.9955, ukdf['pct'].iloc[-1]=0.000208 , ukdf['amount'].iloc[-1]=4635032.9955, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5763, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '13.926', 'enterprice': '26864.9', 'countrevence': '0', 'unrealprofit': '-33682.8162', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '29283.6', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1
127.0.0.1 - - [30/Jul/2023 00:25:00] "POST / HTTP/1.1" 200 -
--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=373746.4768026, self.flagDict['side']='sell', self.tradeCount=2, self.count=22049
self.closeSec=1690647899, self.tradeDate='20230730', self.openTime='002000', self.closeTime='002459', self.symbol='BTCUSDT', self.open=29283.6, self.close=29286.8, self.high=29286.8, self.low=29283.5, self.vol=155.379, self.amt=4550289.0545 
2023-07-30 00:25:00,767:INFO:amihud:main.py:172:handleKline:2219019: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5760  20230730   000000    000459  ...         0.0        0.0       0
5761  20230730   000500    000959  ...         0.0        0.0       0
5762  20230730   001000    001459  ...         0.0        0.0       0
5763  20230730   001500    001959  ...         0.0        0.0       0
5764  20230730   002000    002459  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-07-30 00:25:00,767:INFO:amihud:main.py:175:handleKline:2219019: self.closeSec=1690647899, self.tradeDate='20230730', self.openTime='002000', self.closeTime='002459',self.symbol='BTCUSDT',self.open=29283.6, self.close=29286.8, self.high=29286.8, self.low=29283.5, self.vol=155.379, self.amt=4550289.0545, ukdf['pct'].iloc[-1]=0.000109 , ukdf['amount'].iloc[-1]=4550289.0545, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5764, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '13.926', 'enterprice': '26864.9', 'countrevence': '0', 'unrealprofit': '-33727.3794', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '29286.8', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1


## /root/FIL/strategy/factorcheck/log.txt ----- -----


self.closeSec=1690647599, self.tradeDate='20230730', self.openTime='001500', self.closeTime='001959', self.symbol='BTCUSDT', self.open=29277.5, self.close=29283.6, self.high=29283.6, self.low=29277.4 
127.0.0.1 - - [30/Jul/2023 00:20:01] "POST / HTTP/1.1" 200 -
2023-07-30 00:20:03,461:INFO:factorcheck2:main.py:126:handleKline:2218005: self.closeSec=1690647599, self.tradeDate='20230730', self.openTime='001500', self.closeTime='001959',self.symbol='BTCUSDT',self.open=29277.5, self.close=29283.6, self.high=29283.6, self.low=29277.4   
2023-07-30 00:20:04,371:INFO:factorcheck2:main.py:127:handleKline:2218005: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime    closeSec  ...      low       pct  index  idx
1439  20230729   235500    235959  1690646399  ...  29278.1  0.000229   1727    5
1440  20230730   000000    000459  1690646699  ...  29282.3 -0.000085   1440    0
1441  20230730   000500    000959  1690646999  ...  29277.4 -0.000167   1441    1
1442  20230730   001000    001459  1690647299  ...  29277.4  0.000003   1442    2
1443  20230730   001500    001959  1690647599  ...  29277.4  0.000208   1443    3

[5 rows x 11 columns]
2023-07-30 00:20:04,380:INFO:factorcheck2:main.py:128:handleKline:2218005: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}
127.0.0.1 - - [30/Jul/2023 00:25:00] "POST / HTTP/1.1" 200 -

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=1, self.factor=0.5973502743900735, self.count=22051 

self.closeSec=1690647899, self.tradeDate='20230730', self.openTime='002000', self.closeTime='002459', self.symbol='BTCUSDT', self.open=29283.6, self.close=29286.8, self.high=29286.8, self.low=29283.5 
2023-07-30 00:25:00,739:INFO:factorcheck2:main.py:126:handleKline:2218005: self.closeSec=1690647899, self.tradeDate='20230730', self.openTime='002000', self.closeTime='002459',self.symbol='BTCUSDT',self.open=29283.6, self.close=29286.8, self.high=29286.8, self.low=29283.5   
2023-07-30 00:25:00,752:INFO:factorcheck2:main.py:127:handleKline:2218005: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime    closeSec  ...      low       pct  index  idx
1440  20230730   000000    000459  1690646699  ...  29282.3 -0.000085   1440    0
1441  20230730   000500    000959  1690646999  ...  29277.4 -0.000167   1441    1
1442  20230730   001000    001459  1690647299  ...  29277.4  0.000003   1442    2
1443  20230730   001500    001959  1690647599  ...  29277.4  0.000208   1443    3
1444  20230730   002000    002459  1690647899  ...  29283.5  0.000109   1444    4

[5 rows x 11 columns]
2023-07-30 00:25:00,753:INFO:factorcheck2:main.py:128:handleKline:2218005: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}


## /root/FIL/strategy/logic/log.txt ----- -----

2023-07-30 00:00:19,572:DEBUG:logic:main.py:463:getModel:2218526: df_s.iloc[-5:,:] :
          date closeTime     open  ...    alpha58   alpha67   alpha72
5802  20230729    212959  29281.3  ...  47.916667  0.497850  0.570706
5803  20230729    215959  29294.0  ...  47.916667  0.493416  0.578003
5804  20230729    222959  29283.8  ...  48.333333  0.493550  0.586810
5805  20230729    225959  29284.1  ...  48.333333  0.488145  0.600141
5806  20230729    232959  29271.7  ...  48.333333  0.494120  0.607181

[5 rows x 33 columns]
0.5808823529411765
acc is : 0.5808823529411765
2023-07-30 00:00:19,669:INFO:logic:main.py:468:getModel:2218526: df_pred.iloc[-5:,:] :
     pred    prob_0    prob_1  actual  ...       nav  sign  cost_        bm
539     0  0.510604  0.489396       0  ...  0.945112   1.0    0.0  0.977691
540     0  0.504218  0.495782       0  ...  0.945122   1.0    0.0  0.977701
541     0  0.508391  0.491609       0  ...  0.944725   1.0    0.0  0.977290
542     0  0.500292  0.499708       1  ...  0.945144   1.0    0.0  0.977724
543     0  0.509591  0.490409       0  ...  0.945148   1.0    0.0  0.977728

[5 rows x 10 columns]
2023-07-30 00:00:19,688:INFO:logic:main.py:478:getModel:2218526: df_panel.iloc[-5:,:] :
    pred    prob_0    prob_1  actual  ...       nav  sign  cost_        bm
45     0  0.510834  0.489166       0  ...  0.906915   1.0    0.0  0.975018
46     0  0.504279  0.495721       0  ...  0.906924   1.0    0.0  0.976886
47     0  0.508445  0.491555       0  ...  0.906543   1.0    0.0  0.976475
48     0  0.500162  0.499838       1  ...  0.945144   1.0    0.0  0.975893
49     0  0.509591  0.490409       0  ...  0.945148   1.0    0.0  0.977728

[5 rows x 10 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '23.818', 'enterprice': '29478', 'countrevence': '0', 'unrealprofit': '-4604.0194', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '29284.7', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}


## /root/FIL/strategy/modifiedmom/log.txt ----- -----

127.0.0.1 - - [30/Jul/2023 00:00:04] "POST / HTTP/1.1" 200 -
2023-07-30 00:00:04,415:INFO:modifiedmom:main.py:319:handleOrderFilled:2218259: handleOrderFilled: data=OrderType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'clientorderid': '42763F1690646403773I0L59', 'symbol': 'BTCUSDT', 'gatewayorderid': 1690646404185131, 'quantity': '25.187', 'price': '29284.7', 'stopprice': '0', 'ordertype': '', 'side': 'SELL', 'status': 'FILLED', 'positionside': 'SHORT', 'createtime': 1690646402870, 'updatetime': 1690646404185, 'tradetype': 'usdt', 'selfid': 42763, 'filltrades': [TradeType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'tradeid': 1690646404185, 'clientorderid': '42763F1690646403773I0L59', 'price': '29284.7', 'quantity': '25.187', 'commission': '737.5937389', 'commissionasset': 'USDT', 'tradetime': 1690646404185, 'tradetype': 'usdt', 'gatetype': 'simulator', 'handletime': 1690646404185}], 'gatetype': 'simulator', 'handletime': 0}
127.0.0.1 - - [30/Jul/2023 00:10:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=11024 

self.closeSec=1690646999, self.tradeDate='20230730', self.openTime='000000', self.closeTime='000959', self.symbol='BTCUSDT', self.open='29284.8', self.close='29277.4'
2023-07-30 00:10:01,129:INFO:modifiedmom:main.py:144:handleKline:2218259: self.closeSec=1690646999, self.tradeDate='20230730', self.openTime='000000', self.closeTime='000959',self.symbol='BTCUSDT',self.open='29284.8', self.close='29277.4'
2023-07-30 00:10:01,142:INFO:modifiedmom:main.py:145:handleKline:2218259: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec     open    close       pct
572  20230729   232000    232959  1690644599    29285  29284.7 -0.000010
573  20230729   233000    233959  1690645199  29284.7  29277.2 -0.000256
574  20230729   234000    234959  1690645799  29277.2  29277.4  0.000007
575  20230729   235000    235959  1690646399  29277.4  29284.8  0.000253
576  20230730   000000    000959  1690646999  29284.8  29277.4 -0.000253
2023-07-30 00:10:01,142:INFO:modifiedmom:main.py:146:handleKline:2218259: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': True, 'isOpen': False, 'isClose': True, 'isTrig': False}

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=11025 

self.closeSec=1690647599, self.tradeDate='20230730', self.openTime='001000', self.closeTime='001959', self.symbol='BTCUSDT', self.open='29277.5', self.close='29283.6'
127.0.0.1 - - [30/Jul/2023 00:20:04] "POST / HTTP/1.1" 200 -
2023-07-30 00:20:05,851:INFO:modifiedmom:main.py:144:handleKline:2218259: self.closeSec=1690647599, self.tradeDate='20230730', self.openTime='001000', self.closeTime='001959',self.symbol='BTCUSDT',self.open='29277.5', self.close='29283.6'
2023-07-30 00:20:06,210:INFO:modifiedmom:main.py:145:handleKline:2218259: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec     open    close       pct
573  20230729   233000    233959  1690645199  29284.7  29277.2 -0.000256
574  20230729   234000    234959  1690645799  29277.2  29277.4  0.000007
575  20230729   235000    235959  1690646399  29277.4  29284.8  0.000253
576  20230730   000000    000959  1690646999  29284.8  29277.4 -0.000253
577  20230730   001000    001959  1690647599  29277.5  29283.6  0.000212
2023-07-30 00:20:06,210:INFO:modifiedmom:main.py:146:handleKline:2218259: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': True, 'isOpen': False, 'isClose': True, 'isTrig': False}


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

2023-07-30 00:00:02,270:INFO:pyemd2:main.py:127:handleKline:2217508: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}
2023-07-30 00:00:02,361:INFO:pyemd2:main.py:190:insertFactor:2217508: curDateTime:7300000, name:pyemd2, symbol:BTCUSDT, tradeDate:20230729, closeTime:235959, close:29284.8, total:996515.1559743, pct_pre:-0.0019741081565785024, thd:0.2726891210408108, side:sell 
127.0.0.1 - - [30/Jul/2023 00:10:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=11027 

self.closeSec=1690646999, self.tradeDate='20230730', self.openTime='000000', self.closeTime='000959', self.symbol='BTCUSDT', self.open='29284.8', self.close='29277.4'
2023-07-30 00:10:01,116:INFO:pyemd2:main.py:125:handleKline:2217508: self.closeSec=1690646999, self.tradeDate='20230730', self.openTime='000000', self.closeTime='000959',self.symbol='BTCUSDT',self.open='29284.8', self.close='29277.4'
2023-07-30 00:10:01,135:INFO:pyemd2:main.py:126:handleKline:2217508: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
17420  20230729   232000    232959  1690644599    29285  29284.7
17421  20230729   233000    233959  1690645199  29284.7  29277.2
17422  20230729   234000    234959  1690645799  29277.2  29277.4
17423  20230729   235000    235959  1690646399  29277.4  29284.8
17424  20230730   000000    000959  1690646999  29284.8  29277.4
2023-07-30 00:10:01,144:INFO:pyemd2:main.py:127:handleKline:2217508: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=11028 

self.closeSec=1690647599, self.tradeDate='20230730', self.openTime='001000', self.closeTime='001959', self.symbol='BTCUSDT', self.open='29277.5', self.close='29283.6'
127.0.0.1 - - [30/Jul/2023 00:20:04] "POST / HTTP/1.1" 200 -
2023-07-30 00:20:06,871:INFO:pyemd2:main.py:125:handleKline:2217508: self.closeSec=1690647599, self.tradeDate='20230730', self.openTime='001000', self.closeTime='001959',self.symbol='BTCUSDT',self.open='29277.5', self.close='29283.6'
2023-07-30 00:20:07,007:INFO:pyemd2:main.py:126:handleKline:2217508: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
17421  20230729   233000    233959  1690645199  29284.7  29277.2
17422  20230729   234000    234959  1690645799  29277.2  29277.4
17423  20230729   235000    235959  1690646399  29277.4  29284.8
17424  20230730   000000    000959  1690646999  29284.8  29277.4
17425  20230730   001000    001959  1690647599  29277.5  29283.6
2023-07-30 00:20:07,007:INFO:pyemd2:main.py:127:handleKline:2217508: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}


## /root/FIL/strategy/similarity/log.txt ----- -----

127.0.0.1 - - [30/Jul/2023 00:00:04] "POST / HTTP/1.1" 200 -
2023-07-30 00:00:04,295:INFO:testStrategy:main.py:308:handleOrderFilled:2217133: handleOrderFilled: data=OrderType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'clientorderid': '42762F1690646403676I0L2', 'symbol': 'BTCUSDT', 'gatewayorderid': 1690646404119268, 'quantity': '37.134', 'price': '29284.8', 'stopprice': '0', 'ordertype': '', 'side': 'BUY', 'status': 'FILLED', 'positionside': 'LONG', 'createtime': 1690646402807, 'updatetime': 1690646404119, 'tradetype': 'usdt', 'selfid': 42762, 'filltrades': [TradeType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'tradeid': 1690646404119, 'clientorderid': '42762F1690646403676I0L2', 'price': '29284.8', 'quantity': '37.134', 'commission': '1087.4617632', 'commissionasset': 'USDT', 'tradetime': 1690646404119, 'tradetype': 'usdt', 'gatetype': 'simulator', 'handletime': 1690646404119}], 'gatetype': 'simulator', 'handletime': 0}
127.0.0.1 - - [30/Jul/2023 00:10:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=11027 

self.closeSec=1690646999, self.tradeDate='20230730', self.openTime='000000', self.closeTime='000959', self.symbol='BTCUSDT', self.open='29284.8', self.close='29277.4'
2023-07-30 00:10:01,113:INFO:testStrategy:main.py:101:handleKline:2217133: self.closeSec=1690646999, self.tradeDate='20230730', self.openTime='000000', self.closeTime='000959',self.symbol='BTCUSDT',self.open='29284.8', self.close='29277.4'
2023-07-30 00:10:01,121:INFO:testStrategy:main.py:102:handleKline:2217133: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
12236  20230729   232000    232959  1690644599    29285  29284.7
12237  20230729   233000    233959  1690645199  29284.7  29277.2
12238  20230729   234000    234959  1690645799  29277.2  29277.4
12239  20230729   235000    235959  1690646399  29277.4  29284.8
12240  20230730   000000    000959  1690646999  29284.8  29277.4
2023-07-30 00:10:01,121:INFO:testStrategy:main.py:103:handleKline:2217133: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': True, 'isOpen': False, 'isClose': True, 'isTrig': False, 'isCorr': False}

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=11028 

self.closeSec=1690647599, self.tradeDate='20230730', self.openTime='001000', self.closeTime='001959', self.symbol='BTCUSDT', self.open='29277.5', self.close='29283.6'
127.0.0.1 - - [30/Jul/2023 00:20:04] "POST / HTTP/1.1" 200 -
2023-07-30 00:20:06,742:INFO:testStrategy:main.py:101:handleKline:2217133: self.closeSec=1690647599, self.tradeDate='20230730', self.openTime='001000', self.closeTime='001959',self.symbol='BTCUSDT',self.open='29277.5', self.close='29283.6'
2023-07-30 00:20:06,879:INFO:testStrategy:main.py:102:handleKline:2217133: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
12237  20230729   233000    233959  1690645199  29284.7  29277.2
12238  20230729   234000    234959  1690645799  29277.2  29277.4
12239  20230729   235000    235959  1690646399  29277.4  29284.8
12240  20230730   000000    000959  1690646999  29284.8  29277.4
12241  20230730   001000    001959  1690647599  29277.5  29283.6
2023-07-30 00:20:06,880:INFO:testStrategy:main.py:103:handleKline:2217133: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': True, 'isOpen': False, 'isClose': True, 'isTrig': False, 'isCorr': False}


## /root/FIL/strategy/sr_min/log.txt ----- -----

--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=1, self.total=996015.990996, self.flagDict['side']='buy', self.tradeCount=1, self.count=22048
self.closeSec=1690647599, self.tradeDate='20230730', self.openTime='001500', self.closeTime='001959', self.symbol='BTCUSDT', self.open=29277.5, self.close=29283.6, self.high=29283.6, self.low=29277.4, self.vol=158.302, self.amt=4635032.9955 
127.0.0.1 - - [30/Jul/2023 00:20:01] "POST / HTTP/1.1" 200 -
2023-07-30 00:20:05,191:INFO:sr_min:main.py:172:handleKline:2219263: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5759  20230729   235500    235959  ...         0.0        0.0       0
5760  20230730   000000    000459  ...         0.0        0.0       0
5761  20230730   000500    000959  ...         0.0        0.0       0
5762  20230730   001000    001459  ...         0.0        0.0       0
5763  20230730   001500    001959  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-07-30 00:20:05,212:INFO:sr_min:main.py:175:handleKline:2219263: self.closeSec=1690647599, self.tradeDate='20230730', self.openTime='001500', self.closeTime='001959',self.symbol='BTCUSDT',self.open=29277.5, self.close=29283.6, self.high=29283.6, self.low=29277.4, self.vol=158.302, self.amt=4635032.9955, ukdf['pct'].iloc[-1]=0.000208 , ukdf['amount'].iloc[-1]=4635032.9955, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5763, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '37.141', 'enterprice': '26844', 'countrevence': '0', 'unrealprofit': '90609.1836', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '29283.6', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=1
127.0.0.1 - - [30/Jul/2023 00:25:00] "POST / HTTP/1.1" 200 -
--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=1, self.total=996015.990996, self.flagDict['side']='buy', self.tradeCount=1, self.count=22049
self.closeSec=1690647899, self.tradeDate='20230730', self.openTime='002000', self.closeTime='002459', self.symbol='BTCUSDT', self.open=29283.6, self.close=29286.8, self.high=29286.8, self.low=29283.5, self.vol=155.379, self.amt=4550289.0545 
2023-07-30 00:25:00,770:INFO:sr_min:main.py:172:handleKline:2219263: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5760  20230730   000000    000459  ...         0.0        0.0       0
5761  20230730   000500    000959  ...         0.0        0.0       0
5762  20230730   001000    001459  ...         0.0        0.0       0
5763  20230730   001500    001959  ...         0.0        0.0       0
5764  20230730   002000    002459  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-07-30 00:25:00,770:INFO:sr_min:main.py:175:handleKline:2219263: self.closeSec=1690647899, self.tradeDate='20230730', self.openTime='002000', self.closeTime='002459',self.symbol='BTCUSDT',self.open=29283.6, self.close=29286.8, self.high=29286.8, self.low=29283.5, self.vol=155.379, self.amt=4550289.0545, ukdf['pct'].iloc[-1]=0.000109 , ukdf['amount'].iloc[-1]=4550289.0545, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5764, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '37.141', 'enterprice': '26844', 'countrevence': '0', 'unrealprofit': '90728.0348', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '29286.8', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=1


## /root/FIL/strategy/s_rsrs/log.txt ----- -----

2023-07-29 20:00:10,802:INFO:s_rsrs:main.py:343:handleOrderNew:2218689: handleOrderNew: data=OrderType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'clientorderid': '42759F1690632005229I0L65', 'symbol': 'BTCUSDT', 'gatewayorderid': 1690632005626938, 'quantity': '54.079', 'price': '29250.1', 'stopprice': '0', 'ordertype': '', 'side': 'SELL', 'status': 'FILLED', 'positionside': 'SHORT', 'createtime': 1690632004371, 'updatetime': 1690632005626, 'tradetype': 'usdt', 'selfid': 42759, 'filltrades': [TradeType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'tradeid': 1690632005626, 'clientorderid': '42759F1690632005229I0L65', 'price': '29250.1', 'quantity': '54.079', 'commission': '1581.8161579', 'commissionasset': 'USDT', 'tradetime': 1690632005626, 'tradetype': 'usdt', 'gatetype': 'simulator', 'handletime': 1690632005626}], 'gatetype': 'simulator', 'handletime': 0}
2023-07-29 20:00:10,803:INFO:s_rsrs:main.py:346:handleOrderFilled:2218689: handleOrderFilled: data=OrderType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'clientorderid': '42759F1690632005229I0L65', 'symbol': 'BTCUSDT', 'gatewayorderid': 1690632005626938, 'quantity': '54.079', 'price': '29250.1', 'stopprice': '0', 'ordertype': '', 'side': 'SELL', 'status': 'FILLED', 'positionside': 'SHORT', 'createtime': 1690632004371, 'updatetime': 1690632005626, 'tradetype': 'usdt', 'selfid': 42759, 'filltrades': [TradeType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'tradeid': 1690632005626, 'clientorderid': '42759F1690632005229I0L65', 'price': '29250.1', 'quantity': '54.079', 'commission': '1581.8161579', 'commissionasset': 'USDT', 'tradetime': 1690632005626, 'tradetype': 'usdt', 'gatetype': 'simulator', 'handletime': 1690632005626}], 'gatetype': 'simulator', 'handletime': 0}
127.0.0.1 - - [29/Jul/2023 20:00:11] "POST / HTTP/1.1" 200 -
2023-07-29 20:00:11,231:INFO:s_rsrs:main.py:343:handleOrderNew:2218689: handleOrderNew: data=OrderType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'clientorderid': '42760F1690632010777I0L65', 'symbol': 'BTCUSDT', 'gatewayorderid': 1690632011181537, 'quantity': '54.024', 'price': '29248', 'stopprice': '0', 'ordertype': '', 'side': 'SELL', 'status': 'FILLED', 'positionside': 'SHORT', 'createtime': 1690632010305, 'updatetime': 1690632011181, 'tradetype': 'usdt', 'selfid': 42760, 'filltrades': [TradeType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'tradeid': 1690632011181, 'clientorderid': '42760F1690632010777I0L65', 'price': '29248', 'quantity': '54.024', 'commission': '1580.093952', 'commissionasset': 'USDT', 'tradetime': 1690632011181, 'tradetype': 'usdt', 'gatetype': 'simulator', 'handletime': 1690632011181}], 'gatetype': 'simulator', 'handletime': 0}
2023-07-29 20:00:11,353:INFO:s_rsrs:main.py:346:handleOrderFilled:2218689: handleOrderFilled: data=OrderType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'clientorderid': '42760F1690632010777I0L65', 'symbol': 'BTCUSDT', 'gatewayorderid': 1690632011181537, 'quantity': '54.024', 'price': '29248', 'stopprice': '0', 'ordertype': '', 'side': 'SELL', 'status': 'FILLED', 'positionside': 'SHORT', 'createtime': 1690632010305, 'updatetime': 1690632011181, 'tradetype': 'usdt', 'selfid': 42760, 'filltrades': [TradeType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'tradeid': 1690632011181, 'clientorderid': '42760F1690632010777I0L65', 'price': '29248', 'quantity': '54.024', 'commission': '1580.093952', 'commissionasset': 'USDT', 'tradetime': 1690632011181, 'tradetype': 'usdt', 'gatetype': 'simulator', 'handletime': 1690632011181}], 'gatetype': 'simulator', 'handletime': 0}
127.0.0.1 - - [29/Jul/2023 20:00:11] "POST / HTTP/1.1" 200 -
--handleKline--:  version='2.0.0', self.name='s_rsrs', self.symbol='BTCUSDT', interval='4h', intervalSec=14400, wid=25, thd=0.6, self.sign=-1, self.total=1578513.8580480001, self.flagDict['side']='sell', self.tradeCount=16, self.count=459
self.closeSec=1690646399, self.tradeDate='20230729', self.openTime='200000', self.closeTime='235959', self.symbol='BTCUSDT', self.open=29253.2, self.close=29284.8, self.high=29334.4, self.low=29246.2, self.vol=18876.177, self.amt=552841498.2707 
127.0.0.1 - - [30/Jul/2023 00:00:01] "POST / HTTP/1.1" 200 -
2023-07-30 00:00:01,856:INFO:s_rsrs:main.py:141:handleKline:2218689: self.closeSec=1690646399, self.tradeDate='20230729', self.openTime='200000', self.closeTime='235959',self.symbol='BTCUSDT',self.open=29253.2, self.close=29284.8, self.high=29334.4, self.low=29246.2, self.vol=18876.177, self.amt=552841498.2707 
2023-07-30 00:00:01,869:INFO:s_rsrs:main.py:142:handleKline:2218689: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime  ...        vol           amt       pct
721  20230729   040000    075959  ...  12323.584  3.611651e+08 -0.000119
722  20230729   080000    115959  ...  12079.215  3.544538e+08  0.001904
723  20230729   120000    155959  ...  16468.927  4.830698e+08 -0.002477
724  20230729   160000    195959  ...  17802.940  5.212020e+08 -0.001018
725  20230729   200000    235959  ...  18876.177  5.528415e+08  0.001080

[5 rows x 11 columns]
2023-07-30 00:00:02,623:INFO:s_rsrs:main.py:151:handleKline:2218689: df_s.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec  ...  index      beta    zscore  signal
721  20230729   040000    075959  1690588799  ...    721  0.527794  0.581327     NaN
722  20230729   080000    115959  1690603199  ...    722  0.415546  0.156173     NaN
723  20230729   120000    155959  1690617599  ...    723  0.318044 -0.226289     NaN
724  20230729   160000    195959  1690631999  ...    724  0.206454 -0.681672    -1.0
725  20230729   200000    235959  1690646399  ...    725  0.164504 -0.841976    -1.0

[5 rows x 15 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '54.024', 'enterprice': '29248', 'countrevence': '0', 'unrealprofit': '-1988.0832', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '29284.8', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'numpy.int64'>, curSign=-1, self.sign=-1


