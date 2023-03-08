# 20230309 00:26:01

## /root/FIL/strategy/amihud/log.txt ----- -----

127.0.0.1 - - [09/Mar/2023 00:20:01] "POST / HTTP/1.1" 200 -
--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=993672.4896432, self.flagDict['side']='sell', self.tradeCount=2, self.count=29212
self.closeSec=1678292399, self.tradeDate='20230309', self.openTime='001500', self.closeTime='001959', self.symbol='BTCUSDT', self.open=22122.6, self.close=22116.7, self.high=22140.1, self.low=22112.2, self.vol=2519.367, self.amt=55736655.4214 
2023-03-09 00:20:01,795:INFO:amihud:main.py:172:handleKline:200676: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5759  20230308   235500    235959  ...         0.0        0.0       0
5760  20230309   000000    000459  ...         0.0        0.0       0
5761  20230309   000500    000959  ...         0.0        0.0       0
5762  20230309   001000    001459  ...         0.0        0.0       0
5763  20230309   001500    001959  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-03-09 00:20:01,798:INFO:amihud:main.py:175:handleKline:200676: self.closeSec=1678292399, self.tradeDate='20230309', self.openTime='001500', self.closeTime='001959',self.symbol='BTCUSDT',self.open=22122.6, self.close=22116.7, self.high=22140.1, self.low=22112.2, self.vol=2519.367, self.amt=55736655.4214, ukdf['pct'].iloc[-1]=-0.000271 , ukdf['amount'].iloc[-1]=55736655.4214, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5763, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '60.176', 'enterprice': '16529.3', 'countrevence': '0', 'unrealprofit': '-336227.3824', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '22116.7', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1
127.0.0.1 - - [09/Mar/2023 00:25:01] "POST / HTTP/1.1" 200 -
--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=993672.4896432, self.flagDict['side']='sell', self.tradeCount=2, self.count=29213
self.closeSec=1678292699, self.tradeDate='20230309', self.openTime='002000', self.closeTime='002459', self.symbol='BTCUSDT', self.open=22116.7, self.close=22108.2, self.high=22129.8, self.low=22107.0, self.vol=1401.711, self.amt=30996668.8009 
2023-03-09 00:25:01,636:INFO:amihud:main.py:172:handleKline:200676: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5760  20230309   000000    000459  ...         0.0        0.0       0
5761  20230309   000500    000959  ...         0.0        0.0       0
5762  20230309   001000    001459  ...         0.0        0.0       0
5763  20230309   001500    001959  ...         0.0        0.0       0
5764  20230309   002000    002459  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-03-09 00:25:01,638:INFO:amihud:main.py:175:handleKline:200676: self.closeSec=1678292699, self.tradeDate='20230309', self.openTime='002000', self.closeTime='002459',self.symbol='BTCUSDT',self.open=22116.7, self.close=22108.2, self.high=22129.8, self.low=22107.0, self.vol=1401.711, self.amt=30996668.8009, ukdf['pct'].iloc[-1]=-0.000384 , ukdf['amount'].iloc[-1]=30996668.8009, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5764, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '60.176', 'enterprice': '16529.3', 'countrevence': '0', 'unrealprofit': '-335818.1856', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '22109.9', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1


## /root/FIL/strategy/factorcheck/log.txt ----- -----

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=0, self.factor=0.701083231489087, self.count=29778 

self.closeSec=1678292399, self.tradeDate='20230309', self.openTime='001500', self.closeTime='001959', self.symbol='BTCUSDT', self.open=22122.6, self.close=22116.7, self.high=22140.1, self.low=22112.2 
2023-03-09 00:20:01,650:INFO:factorcheck2:main.py:126:handleKline:185239: self.closeSec=1678292399, self.tradeDate='20230309', self.openTime='001500', self.closeTime='001959',self.symbol='BTCUSDT',self.open=22122.6, self.close=22116.7, self.high=22140.1, self.low=22112.2   
2023-03-09 00:20:01,718:INFO:factorcheck2:main.py:127:handleKline:185239: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime    closeSec  ...      low       pct  index  idx
1439  20230308   235500    235959  1678291199  ...  22125.9  0.000086   1727    5
1440  20230309   000000    000459  1678291499  ...  22125.0  0.001066   1440    0
1441  20230309   000500    000959  1678291799  ...  22153.0  0.000776   1441    1
1442  20230309   001000    001459  1678292099  ...  22122.2 -0.002147   1442    2
1443  20230309   001500    001959  1678292399  ...  22112.2 -0.000271   1443    3

[5 rows x 11 columns]
2023-03-09 00:20:01,718:INFO:factorcheck2:main.py:128:handleKline:185239: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': True, 'isOpenSell': False, 'isCloseBuy': False, 'isCloseSell': False, 'isOpen': True, 'isClose': False, 'isTrig': True}

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=0, self.factor=0.701083231489087, self.count=29779 

self.closeSec=1678292699, self.tradeDate='20230309', self.openTime='002000', self.closeTime='002459', self.symbol='BTCUSDT', self.open=22116.7, self.close=22108.2, self.high=22129.8, self.low=22107.0 
2023-03-09 00:25:01,513:INFO:factorcheck2:main.py:126:handleKline:185239: self.closeSec=1678292699, self.tradeDate='20230309', self.openTime='002000', self.closeTime='002459',self.symbol='BTCUSDT',self.open=22116.7, self.close=22108.2, self.high=22129.8, self.low=22107.0   
127.0.0.1 - - [09/Mar/2023 00:25:01] "POST / HTTP/1.1" 200 -
2023-03-09 00:25:01,599:INFO:factorcheck2:main.py:127:handleKline:185239: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime    closeSec  ...      low       pct  index  idx
1440  20230309   000000    000459  1678291499  ...  22125.0  0.001066   1440    0
1441  20230309   000500    000959  1678291799  ...  22153.0  0.000776   1441    1
1442  20230309   001000    001459  1678292099  ...  22122.2 -0.002147   1442    2
1443  20230309   001500    001959  1678292399  ...  22112.2 -0.000271   1443    3
1444  20230309   002000    002459  1678292699  ...  22107.0 -0.000384   1444    4

[5 rows x 11 columns]
2023-03-09 00:25:01,599:INFO:factorcheck2:main.py:128:handleKline:185239: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': True, 'isOpenSell': False, 'isCloseBuy': False, 'isCloseSell': False, 'isOpen': True, 'isClose': False, 'isTrig': True}


## /root/FIL/strategy/logic/log.txt ----- -----

2023-03-09 00:00:34,951:DEBUG:logic:main.py:463:getModel:885513: df_s.iloc[-5:,:] :
          date closeTime     open  ...    alpha58   alpha67   alpha72
5802  20230308    212959  22007.1  ...  43.333333  0.430850  0.641255
5803  20230308    215959  22001.8  ...  42.916667  0.425444  0.641819
5804  20230308    222959  21981.8  ...  42.916667  0.423141  0.641446
5805  20230308    225959  21974.7  ...  42.916667  0.420085  0.642666
5806  20230308    232959  21963.0  ...  43.333333  0.466955  0.625108

[5 rows x 33 columns]
0.5533088235294118
acc is : 0.5533088235294118
2023-03-09 00:00:35,055:INFO:logic:main.py:468:getModel:885513: df_pred.iloc[-5:,:] :
     pred    prob_0    prob_1  actual  ...       nav  sign  cost_        bm
539     1  0.494914  0.505086       0  ...  0.933954   1.0    0.0  0.951235
540     1  0.488347  0.511653       0  ...  0.933593   1.0    0.0  0.950867
541     1  0.495446  0.504554       0  ...  0.933117   1.0    0.0  0.950382
542     1  0.497273  0.502727       1  ...  0.938793   1.0    0.0  0.956164
543     0  0.584194  0.415806       1  ...  0.940229   1.0    0.0  0.957626

[5 rows x 10 columns]
2023-03-09 00:00:35,066:INFO:logic:main.py:478:getModel:885513: df_panel.iloc[-5:,:] :
    pred    prob_0    prob_1  actual  ...       nav  sign  cost_        bm
45     1  0.495858  0.504142       0  ...  0.933954   1.0    0.0  0.953058
46     1  0.488939  0.511061       0  ...  0.926076   1.0    0.0  0.952054
47     1  0.496377  0.503623       0  ...  0.933117   1.0    0.0  0.951568
48     1  0.497713  0.502287       1  ...  0.938793   1.0    0.0  0.957344
49     0  0.584194  0.415806       1  ...  0.940229   1.0    0.0  0.957626

[5 rows x 10 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '31.51', 'enterprice': '22084.5', 'countrevence': '0', 'unrealprofit': '1405.346', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '22129.1', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}


## /root/FIL/strategy/modifiedmom/log.txt ----- -----

2023-03-09 00:00:03,081:INFO:modifiedmom:main.py:319:handleOrderFilled:185213: handleOrderFilled: data=OrderType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'clientorderid': '41916F1678291202681I0L59', 'symbol': 'BTCUSDT', 'gatewayorderid': 1678291202785419, 'quantity': '45.758', 'price': '22129.6', 'stopprice': '0', 'ordertype': '', 'side': 'BUY', 'status': 'FILLED', 'positionside': 'LONG', 'createtime': 1678291202339, 'updatetime': 1678291202785, 'tradetype': 'usdt', 'selfid': 41916, 'filltrades': [TradeType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'tradeid': 1678291202785, 'clientorderid': '41916F1678291202681I0L59', 'price': '22129.6', 'quantity': '45.758', 'commission': '1012.6062368', 'commissionasset': 'USDT', 'tradetime': 1678291202785, 'tradetype': 'usdt', 'gatetype': 'simulator', 'handletime': 1678291202785}], 'gatetype': 'simulator', 'handletime': 0}
127.0.0.1 - - [09/Mar/2023 00:00:03] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=14888 

self.closeSec=1678291799, self.tradeDate='20230309', self.openTime='000000', self.closeTime='000959', self.symbol='BTCUSDT', self.open='22129.6', self.close='22170.3'
2023-03-09 00:10:01,721:INFO:modifiedmom:main.py:144:handleKline:185213: self.closeSec=1678291799, self.tradeDate='20230309', self.openTime='000000', self.closeTime='000959',self.symbol='BTCUSDT',self.open='22129.6', self.close='22170.3'
127.0.0.1 - - [09/Mar/2023 00:10:01] "POST / HTTP/1.1" 200 -
2023-03-09 00:10:01,730:INFO:modifiedmom:main.py:145:handleKline:185213: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec     open    close       pct
572  20230308   232000    232959  1678289399  22078.1  22095.7  0.000983
573  20230308   233000    233959  1678289999  22091.3    22161  0.002955
574  20230308   234000    234959  1678290599    22161  22102.2 -0.002653
575  20230308   235000    235959  1678291199    22103  22129.5  0.001235
576  20230309   000000    000959  1678291799  22129.6  22170.3  0.001844
2023-03-09 00:10:01,731:INFO:modifiedmom:main.py:146:handleKline:185213: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': True, 'isOpen': False, 'isClose': True, 'isTrig': False}

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=14889 

self.closeSec=1678292399, self.tradeDate='20230309', self.openTime='001000', self.closeTime='001959', self.symbol='BTCUSDT', self.open='22170.2', self.close='22116.7'
127.0.0.1 - - [09/Mar/2023 00:20:01] "POST / HTTP/1.1" 200 -
2023-03-09 00:20:01,758:INFO:modifiedmom:main.py:144:handleKline:185213: self.closeSec=1678292399, self.tradeDate='20230309', self.openTime='001000', self.closeTime='001959',self.symbol='BTCUSDT',self.open='22170.2', self.close='22116.7'
2023-03-09 00:20:01,830:INFO:modifiedmom:main.py:145:handleKline:185213: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec     open    close       pct
573  20230308   233000    233959  1678289999  22091.3    22161  0.002955
574  20230308   234000    234959  1678290599    22161  22102.2 -0.002653
575  20230308   235000    235959  1678291199    22103  22129.5  0.001235
576  20230309   000000    000959  1678291799  22129.6  22170.3  0.001844
577  20230309   001000    001959  1678292399  22170.2  22116.7 -0.002418
2023-03-09 00:20:01,830:INFO:modifiedmom:main.py:146:handleKline:185213: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': True, 'isOpen': False, 'isClose': True, 'isTrig': False}


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

2023-03-09 00:00:02,094:INFO:pyemd2:main.py:127:handleKline:185189: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}
2023-03-09 00:00:02,236:INFO:pyemd2:main.py:190:insertFactor:185189: curDateTime:3090000, name:pyemd2, symbol:BTCUSDT, tradeDate:20230308, closeTime:235959, close:22129.5, total:984062.1980325, pct_pre:-0.01538034698635593, thd:0.13098437905830884, side:sell 
127.0.0.1 - - [09/Mar/2023 00:10:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=14889 

self.closeSec=1678291799, self.tradeDate='20230309', self.openTime='000000', self.closeTime='000959', self.symbol='BTCUSDT', self.open='22129.6', self.close='22170.3'
2023-03-09 00:10:01,757:INFO:pyemd2:main.py:125:handleKline:185189: self.closeSec=1678291799, self.tradeDate='20230309', self.openTime='000000', self.closeTime='000959',self.symbol='BTCUSDT',self.open='22129.6', self.close='22170.3'
2023-03-09 00:10:01,772:INFO:pyemd2:main.py:126:handleKline:185189: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
17420  20230308   232000    232959  1678289399  22078.1  22095.7
17421  20230308   233000    233959  1678289999  22091.3    22161
17422  20230308   234000    234959  1678290599    22161  22102.2
17423  20230308   235000    235959  1678291199    22103  22129.5
17424  20230309   000000    000959  1678291799  22129.6  22170.3
2023-03-09 00:10:01,772:INFO:pyemd2:main.py:127:handleKline:185189: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=14890 

self.closeSec=1678292399, self.tradeDate='20230309', self.openTime='001000', self.closeTime='001959', self.symbol='BTCUSDT', self.open='22170.2', self.close='22116.7'
127.0.0.1 - - [09/Mar/2023 00:20:01] "POST / HTTP/1.1" 200 -
2023-03-09 00:20:01,778:INFO:pyemd2:main.py:125:handleKline:185189: self.closeSec=1678292399, self.tradeDate='20230309', self.openTime='001000', self.closeTime='001959',self.symbol='BTCUSDT',self.open='22170.2', self.close='22116.7'
2023-03-09 00:20:01,806:INFO:pyemd2:main.py:126:handleKline:185189: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
17421  20230308   233000    233959  1678289999  22091.3    22161
17422  20230308   234000    234959  1678290599    22161  22102.2
17423  20230308   235000    235959  1678291199    22103  22129.5
17424  20230309   000000    000959  1678291799  22129.6  22170.3
17425  20230309   001000    001959  1678292399  22170.2  22116.7
2023-03-09 00:20:01,808:INFO:pyemd2:main.py:127:handleKline:185189: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}


## /root/FIL/strategy/similarity/log.txt ----- -----

127.0.0.1 - - [09/Mar/2023 00:00:03] "POST / HTTP/1.1" 200 -
2023-03-09 00:00:03,478:INFO:testStrategy:main.py:308:handleOrderFilled:185174: handleOrderFilled: data=OrderType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'clientorderid': '41917F1678291202903I0L2', 'symbol': 'BTCUSDT', 'gatewayorderid': 1678291203155916, 'quantity': '52.754', 'price': '22129.5', 'stopprice': '0', 'ordertype': '', 'side': 'SELL', 'status': 'FILLED', 'positionside': 'SHORT', 'createtime': 1678291202591, 'updatetime': 1678291203155, 'tradetype': 'usdt', 'selfid': 41917, 'filltrades': [TradeType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'tradeid': 1678291203155, 'clientorderid': '41917F1678291202903I0L2', 'price': '22129.5', 'quantity': '52.754', 'commission': '1167.419643', 'commissionasset': 'USDT', 'tradetime': 1678291203155, 'tradetype': 'usdt', 'gatetype': 'simulator', 'handletime': 1678291203155}], 'gatetype': 'simulator', 'handletime': 0}
127.0.0.1 - - [09/Mar/2023 00:10:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=14889 

self.closeSec=1678291799, self.tradeDate='20230309', self.openTime='000000', self.closeTime='000959', self.symbol='BTCUSDT', self.open='22129.6', self.close='22170.3'
2023-03-09 00:10:01,760:INFO:testStrategy:main.py:101:handleKline:185174: self.closeSec=1678291799, self.tradeDate='20230309', self.openTime='000000', self.closeTime='000959',self.symbol='BTCUSDT',self.open='22129.6', self.close='22170.3'
2023-03-09 00:10:01,794:INFO:testStrategy:main.py:102:handleKline:185174: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
12236  20230308   232000    232959  1678289399  22078.1  22095.7
12237  20230308   233000    233959  1678289999  22091.3    22161
12238  20230308   234000    234959  1678290599    22161  22102.2
12239  20230308   235000    235959  1678291199    22103  22129.5
12240  20230309   000000    000959  1678291799  22129.6  22170.3
2023-03-09 00:10:01,795:INFO:testStrategy:main.py:103:handleKline:185174: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': True, 'isOpen': False, 'isClose': True, 'isTrig': False, 'isCorr': False}
127.0.0.1 - - [09/Mar/2023 00:20:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=14890 

self.closeSec=1678292399, self.tradeDate='20230309', self.openTime='001000', self.closeTime='001959', self.symbol='BTCUSDT', self.open='22170.2', self.close='22116.7'
2023-03-09 00:20:01,792:INFO:testStrategy:main.py:101:handleKline:185174: self.closeSec=1678292399, self.tradeDate='20230309', self.openTime='001000', self.closeTime='001959',self.symbol='BTCUSDT',self.open='22170.2', self.close='22116.7'
2023-03-09 00:20:01,841:INFO:testStrategy:main.py:102:handleKline:185174: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
12237  20230308   233000    233959  1678289999  22091.3    22161
12238  20230308   234000    234959  1678290599    22161  22102.2
12239  20230308   235000    235959  1678291199    22103  22129.5
12240  20230309   000000    000959  1678291799  22129.6  22170.3
12241  20230309   001000    001959  1678292399  22170.2  22116.7
2023-03-09 00:20:01,841:INFO:testStrategy:main.py:103:handleKline:185174: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': True, 'isOpen': False, 'isClose': True, 'isTrig': False, 'isCorr': False}


## /root/FIL/strategy/sr_min/log.txt ----- -----

127.0.0.1 - - [09/Mar/2023 00:20:01] "POST / HTTP/1.1" 200 -
--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=0, self.total=1000000.0, self.flagDict['side']='', self.tradeCount=0, self.count=25210
self.closeSec=1678292399, self.tradeDate='20230309', self.openTime='001500', self.closeTime='001959', self.symbol='BTCUSDT', self.open=22122.6, self.close=22116.7, self.high=22140.1, self.low=22112.2, self.vol=2519.367, self.amt=55736655.4214 
2023-03-09 00:20:01,732:INFO:sr_min:main.py:172:handleKline:449472: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5759  20230308   235500    235959  ...         0.0        0.0       0
5760  20230309   000000    000459  ...         0.0        0.0       0
5761  20230309   000500    000959  ...         0.0        0.0       0
5762  20230309   001000    001459  ...         0.0        0.0       0
5763  20230309   001500    001959  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-03-09 00:20:01,736:INFO:sr_min:main.py:175:handleKline:449472: self.closeSec=1678292399, self.tradeDate='20230309', self.openTime='001500', self.closeTime='001959',self.symbol='BTCUSDT',self.open=22122.6, self.close=22116.7, self.high=22140.1, self.low=22112.2, self.vol=2519.367, self.amt=55736655.4214, ukdf['pct'].iloc[-1]=-0.000271 , ukdf['amount'].iloc[-1]=55736655.4214, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5763, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': []}
type(curSign)=<class 'int'>, curSign=0, self.sign=0
127.0.0.1 - - [09/Mar/2023 00:25:01] "POST / HTTP/1.1" 200 -
--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=0, self.total=1000000.0, self.flagDict['side']='', self.tradeCount=0, self.count=25211
self.closeSec=1678292699, self.tradeDate='20230309', self.openTime='002000', self.closeTime='002459', self.symbol='BTCUSDT', self.open=22116.7, self.close=22108.2, self.high=22129.8, self.low=22107.0, self.vol=1401.711, self.amt=30996668.8009 
2023-03-09 00:25:01,635:INFO:sr_min:main.py:172:handleKline:449472: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5760  20230309   000000    000459  ...         0.0        0.0       0
5761  20230309   000500    000959  ...         0.0        0.0       0
5762  20230309   001000    001459  ...         0.0        0.0       0
5763  20230309   001500    001959  ...         0.0        0.0       0
5764  20230309   002000    002459  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-03-09 00:25:01,638:INFO:sr_min:main.py:175:handleKline:449472: self.closeSec=1678292699, self.tradeDate='20230309', self.openTime='002000', self.closeTime='002459',self.symbol='BTCUSDT',self.open=22116.7, self.close=22108.2, self.high=22129.8, self.low=22107.0, self.vol=1401.711, self.amt=30996668.8009, ukdf['pct'].iloc[-1]=-0.000384 , ukdf['amount'].iloc[-1]=30996668.8009, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5764, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': []}
type(curSign)=<class 'int'>, curSign=0, self.sign=0


## /root/FIL/strategy/s_rsrs/log.txt ----- -----

723  20230308   120000    155959  1678262399  ...    723  0.067822 -1.613690    -1.0
724  20230308   160000    195959  1678276799  ...    724  0.111385 -1.452801    -1.0

[5 rows x 15 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '42.135', 'enterprice': '23350.3', 'countrevence': '0', 'unrealprofit': '54260.30423346675', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '22062.52726395', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'numpy.int64'>, curSign=-1, self.sign=-1
--handleKline--:  version='2.0.0', self.name='s_rsrs', self.symbol='BTCUSDT', interval='4h', intervalSec=14400, wid=25, thd=0.6, self.sign=-1, self.total=982881.0256095, self.flagDict['side']='sell', self.tradeCount=23, self.count=620
self.closeSec=1678291199, self.tradeDate='20230308', self.openTime='200000', self.closeTime='235959', self.symbol='BTCUSDT', self.open=22061.1, self.close=22129.5, self.high=22222.0, self.low=21880.0, self.vol=148584.459, self.amt=3274851861.0329 
127.0.0.1 - - [09/Mar/2023 00:00:01] "POST / HTTP/1.1" 200 -
2023-03-09 00:00:01,827:INFO:s_rsrs:main.py:141:handleKline:185271: self.closeSec=1678291199, self.tradeDate='20230308', self.openTime='200000', self.closeTime='235959',self.symbol='BTCUSDT',self.open=22061.1, self.close=22129.5, self.high=22222.0, self.low=21880.0, self.vol=148584.459, self.amt=3274851861.0329 
2023-03-09 00:00:01,888:INFO:s_rsrs:main.py:142:handleKline:185271: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime  ...         vol           amt       pct
721  20230308   040000    075959  ...   95482.633  2.106800e+09  0.003047
722  20230308   080000    115959  ...   51149.471  1.134599e+09 -0.002042
723  20230308   120000    155959  ...   89535.701  1.968240e+09 -0.008111
724  20230308   160000    195959  ...   56848.317  1.252963e+09  0.004508
725  20230308   200000    235959  ...  148584.459  3.274852e+09  0.003096

[5 rows x 11 columns]
2023-03-09 00:00:04,540:INFO:s_rsrs:main.py:151:handleKline:185271: df_s.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec  ...  index      beta    zscore  signal
721  20230308   040000    075959  1678233599  ...    721  0.012961 -1.878141    -1.0
722  20230308   080000    115959  1678247999  ...    722  0.019556 -1.809312    -1.0
723  20230308   120000    155959  1678262399  ...    723  0.067822 -1.613690    -1.0
724  20230308   160000    195959  1678276799  ...    724  0.111385 -1.452801    -1.0
725  20230308   200000    235959  1678291199  ...    725  0.142494 -1.353199    -1.0

[5 rows x 15 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '42.135', 'enterprice': '23350.3', 'countrevence': '0', 'unrealprofit': '51352.0453070787', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '22131.54966638', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'numpy.int64'>, curSign=-1, self.sign=-1


