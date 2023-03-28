# 20230329 00:26:01

## /root/FIL/strategy/amihud/log.txt ----- -----

--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=993672.4896432, self.flagDict['side']='sell', self.tradeCount=2, self.count=34972
self.closeSec=1680020399, self.tradeDate='20230329', self.openTime='001500', self.closeTime='001959', self.symbol='BTCUSDT', self.open=26911.4, self.close=26873.9, self.high=26916.1, self.low=26855.0, self.vol=2073.78, self.amt=55744031.9004 
127.0.0.1 - - [29/Mar/2023 00:20:04] "POST / HTTP/1.1" 200 -
2023-03-29 00:20:08,401:INFO:amihud:main.py:172:handleKline:200676: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5759  20230328   235500    235959  ...         0.0        0.0       0
5760  20230329   000000    000459  ...         0.0        0.0       0
5761  20230329   000500    000959  ...         0.0        0.0       0
5762  20230329   001000    001459  ...         0.0        0.0       0
5763  20230329   001500    001959  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-03-29 00:20:08,420:INFO:amihud:main.py:175:handleKline:200676: self.closeSec=1680020399, self.tradeDate='20230329', self.openTime='001500', self.closeTime='001959',self.symbol='BTCUSDT',self.open=26911.4, self.close=26873.9, self.high=26916.1, self.low=26855.0, self.vol=2073.78, self.amt=55744031.9004, ukdf['pct'].iloc[-1]=-0.001393 , ukdf['amount'].iloc[-1]=55744031.9004, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5763, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '60.176', 'enterprice': '16529.3', 'countrevence': '0', 'unrealprofit': '-622490.632', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '26873.8', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1
127.0.0.1 - - [29/Mar/2023 00:25:01] "POST / HTTP/1.1" 200 -
--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=993672.4896432, self.flagDict['side']='sell', self.tradeCount=2, self.count=34973
self.closeSec=1680020699, self.tradeDate='20230329', self.openTime='002000', self.closeTime='002459', self.symbol='BTCUSDT', self.open=26873.8, self.close=26877.5, self.high=26916.2, self.low=26859.7, self.vol=2164.24, self.amt=58181586.9058 
2023-03-29 00:25:01,631:INFO:amihud:main.py:172:handleKline:200676: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5760  20230329   000000    000459  ...         0.0        0.0       0
5761  20230329   000500    000959  ...         0.0        0.0       0
5762  20230329   001000    001459  ...         0.0        0.0       0
5763  20230329   001500    001959  ...         0.0        0.0       0
5764  20230329   002000    002459  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-03-29 00:25:01,632:INFO:amihud:main.py:175:handleKline:200676: self.closeSec=1680020699, self.tradeDate='20230329', self.openTime='002000', self.closeTime='002459',self.symbol='BTCUSDT',self.open=26873.8, self.close=26877.5, self.high=26916.2, self.low=26859.7, self.vol=2164.24, self.amt=58181586.9058, ukdf['pct'].iloc[-1]=0.000134 , ukdf['amount'].iloc[-1]=58181586.9058, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5764, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '60.176', 'enterprice': '16529.3', 'countrevence': '0', 'unrealprofit': '-622713.2832', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '26877.5', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1


## /root/FIL/strategy/factorcheck/log.txt ----- -----


self.closeSec=1680020399, self.tradeDate='20230329', self.openTime='001500', self.closeTime='001959', self.symbol='BTCUSDT', self.open=26911.4, self.close=26873.9, self.high=26916.1, self.low=26855.0 
127.0.0.1 - - [29/Mar/2023 00:20:03] "POST / HTTP/1.1" 200 -
2023-03-29 00:20:06,542:INFO:factorcheck2:main.py:126:handleKline:185239: self.closeSec=1680020399, self.tradeDate='20230329', self.openTime='001500', self.closeTime='001959',self.symbol='BTCUSDT',self.open=26911.4, self.close=26873.9, self.high=26916.1, self.low=26855.0   
2023-03-29 00:20:07,505:INFO:factorcheck2:main.py:127:handleKline:185239: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime    closeSec  ...      low       pct  index  idx
1439  20230328   235500    235959  1680019199  ...  26949.8  0.000749   1727    5
1440  20230329   000000    000459  1680019499  ...  26947.5 -0.001326   1440    0
1441  20230329   000500    000959  1680019799  ...  26894.6 -0.002026   1441    1
1442  20230329   001000    001459  1680020099  ...  26891.2  0.000435   1442    2
1443  20230329   001500    001959  1680020399  ...  26855.0 -0.001393   1443    3

[5 rows x 11 columns]
2023-03-29 00:20:07,506:INFO:factorcheck2:main.py:128:handleKline:185239: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': True, 'isOpenSell': False, 'isCloseBuy': False, 'isCloseSell': False, 'isOpen': True, 'isClose': False, 'isTrig': True}
127.0.0.1 - - [29/Mar/2023 00:25:01] "POST / HTTP/1.1" 200 -

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=0, self.factor=0.6441896405986209, self.count=35539 

self.closeSec=1680020699, self.tradeDate='20230329', self.openTime='002000', self.closeTime='002459', self.symbol='BTCUSDT', self.open=26873.8, self.close=26877.5, self.high=26916.2, self.low=26859.7 
2023-03-29 00:25:01,504:INFO:factorcheck2:main.py:126:handleKline:185239: self.closeSec=1680020699, self.tradeDate='20230329', self.openTime='002000', self.closeTime='002459',self.symbol='BTCUSDT',self.open=26873.8, self.close=26877.5, self.high=26916.2, self.low=26859.7   
2023-03-29 00:25:01,552:INFO:factorcheck2:main.py:127:handleKline:185239: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime    closeSec  ...      low       pct  index  idx
1440  20230329   000000    000459  1680019499  ...  26947.5 -0.001326   1440    0
1441  20230329   000500    000959  1680019799  ...  26894.6 -0.002026   1441    1
1442  20230329   001000    001459  1680020099  ...  26891.2  0.000435   1442    2
1443  20230329   001500    001959  1680020399  ...  26855.0 -0.001393   1443    3
1444  20230329   002000    002459  1680020699  ...  26859.7  0.000134   1444    4

[5 rows x 11 columns]
2023-03-29 00:25:01,553:INFO:factorcheck2:main.py:128:handleKline:185239: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': True, 'isOpenSell': False, 'isCloseBuy': False, 'isCloseSell': False, 'isOpen': True, 'isClose': False, 'isTrig': True}


## /root/FIL/strategy/logic/log.txt ----- -----

2023-03-29 00:00:35,572:DEBUG:logic:main.py:463:getModel:885513: df_s.iloc[-5:,:] :
          date closeTime     open  ...    alpha58   alpha67   alpha72
5802  20230328    212959  26967.3  ...  47.916667  0.442357  0.609949
5803  20230328    215959  26900.8  ...  47.500000  0.438448  0.608611
5804  20230328    222959  26871.3  ...  47.916667  0.458520  0.594583
5805  20230328    225959  26993.3  ...  47.500000  0.450011  0.588115
5806  20230328    232959  26930.0  ...  47.500000  0.457572  0.577200

[5 rows x 33 columns]
0.5165441176470589
acc is : 0.5165441176470589
2023-03-29 00:00:35,744:INFO:logic:main.py:468:getModel:885513: df_pred.iloc[-5:,:] :
     pred    prob_0    prob_1  actual  ...       nav  sign  cost_        bm
539     0  0.546403  0.453597       0  ...  0.941517   1.0    0.0  1.031647
540     0  0.538505  0.461495       1  ...  0.945795   1.0    0.0  1.036334
541     0  0.567074  0.432926       0  ...  0.943577   1.0    0.0  1.033904
542     0  0.538867  0.461133       1  ...  0.945210   1.0    0.0  1.035693
543     0  0.557825  0.442175       1  ...  0.945500   1.0    0.0  1.036012

[5 rows x 10 columns]
2023-03-29 00:00:35,784:INFO:logic:main.py:478:getModel:885513: df_panel.iloc[-5:,:] :
    pred    prob_0    prob_1  actual  ...       nav  sign  cost_        bm
45     0  0.547000  0.453000       0  ...  0.943798   1.0    0.0  1.039682
46     0  0.538633  0.461367       1  ...  0.948087   1.0    0.0  1.032853
47     0  0.566656  0.433344       0  ...  0.929733   1.0    0.0  1.030431
48     0  0.539319  0.460681       1  ...  0.934847   1.0    0.0  1.040218
49     0  0.557825  0.442175       1  ...  0.945500   1.0    0.0  1.036012

[5 rows x 10 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': []}


## /root/FIL/strategy/modifiedmom/log.txt ----- -----

127.0.0.1 - - [29/Mar/2023 00:00:03] "POST / HTTP/1.1" 200 -
2023-03-29 00:00:03,203:INFO:modifiedmom:main.py:319:handleOrderFilled:185213: handleOrderFilled: data=OrderType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'clientorderid': '42071F1680019202790I0L59', 'symbol': 'BTCUSDT', 'gatewayorderid': 1680019202891092, 'quantity': '26.407', 'price': '26988.3', 'stopprice': '0', 'ordertype': '', 'side': 'BUY', 'status': 'FILLED', 'positionside': 'LONG', 'createtime': 1680019202443, 'updatetime': 1680019202891, 'tradetype': 'usdt', 'selfid': 42071, 'filltrades': [TradeType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'tradeid': 1680019202891, 'clientorderid': '42071F1680019202790I0L59', 'price': '26988.3', 'quantity': '26.407', 'commission': '712.6800381', 'commissionasset': 'USDT', 'tradetime': 1680019202891, 'tradetype': 'usdt', 'gatetype': 'simulator', 'handletime': 1680019202891}], 'gatetype': 'simulator', 'handletime': 0}

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=17768 

self.closeSec=1680019799, self.tradeDate='20230329', self.openTime='000000', self.closeTime='000959', self.symbol='BTCUSDT', self.open='26984.8', self.close='26896.8'
127.0.0.1 - - [29/Mar/2023 00:10:01] "POST / HTTP/1.1" 200 -
2023-03-29 00:10:01,599:INFO:modifiedmom:main.py:144:handleKline:185213: self.closeSec=1680019799, self.tradeDate='20230329', self.openTime='000000', self.closeTime='000959',self.symbol='BTCUSDT',self.open='26984.8', self.close='26896.8'
2023-03-29 00:10:01,609:INFO:modifiedmom:main.py:145:handleKline:185213: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec     open    close       pct
572  20230328   232000    232959  1680017399    26971  26976.6  0.000211
573  20230328   233000    233959  1680017999  26976.7  27057.3  0.002991
574  20230328   234000    234959  1680018599  27052.9  26951.4 -0.003914
575  20230328   235000    235959  1680019199  26951.4  26984.9  0.001243
576  20230329   000000    000959  1680019799  26984.8  26896.8 -0.003265
2023-03-29 00:10:01,610:INFO:modifiedmom:main.py:146:handleKline:185213: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': True, 'isOpen': False, 'isClose': True, 'isTrig': False}

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=17769 

self.closeSec=1680020399, self.tradeDate='20230329', self.openTime='001000', self.closeTime='001959', self.symbol='BTCUSDT', self.open='26896.9', self.close='26873.9'
127.0.0.1 - - [29/Mar/2023 00:20:04] "POST / HTTP/1.1" 200 -
2023-03-29 00:20:07,231:INFO:modifiedmom:main.py:144:handleKline:185213: self.closeSec=1680020399, self.tradeDate='20230329', self.openTime='001000', self.closeTime='001959',self.symbol='BTCUSDT',self.open='26896.9', self.close='26873.9'
2023-03-29 00:20:07,919:INFO:modifiedmom:main.py:145:handleKline:185213: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec     open    close       pct
573  20230328   233000    233959  1680017999  26976.7  27057.3  0.002991
574  20230328   234000    234959  1680018599  27052.9  26951.4 -0.003914
575  20230328   235000    235959  1680019199  26951.4  26984.9  0.001243
576  20230329   000000    000959  1680019799  26984.8  26896.8 -0.003265
577  20230329   001000    001959  1680020399  26896.9  26873.9 -0.000851
2023-03-29 00:20:07,920:INFO:modifiedmom:main.py:146:handleKline:185213: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': True, 'isOpen': False, 'isClose': True, 'isTrig': False}


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

2023-03-29 00:00:02,103:INFO:pyemd2:main.py:127:handleKline:185189: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}
2023-03-29 00:00:02,220:INFO:pyemd2:main.py:190:insertFactor:185189: curDateTime:3290000, name:pyemd2, symbol:BTCUSDT, tradeDate:20230328, closeTime:235959, close:26984.9, total:1018676.5234079, pct_pre:-0.010143549837143273, thd:0.24483130686725424, side:sell 
127.0.0.1 - - [29/Mar/2023 00:10:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=17769 

self.closeSec=1680019799, self.tradeDate='20230329', self.openTime='000000', self.closeTime='000959', self.symbol='BTCUSDT', self.open='26984.8', self.close='26896.8'
2023-03-29 00:10:01,633:INFO:pyemd2:main.py:125:handleKline:185189: self.closeSec=1680019799, self.tradeDate='20230329', self.openTime='000000', self.closeTime='000959',self.symbol='BTCUSDT',self.open='26984.8', self.close='26896.8'
2023-03-29 00:10:01,654:INFO:pyemd2:main.py:126:handleKline:185189: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
17420  20230328   232000    232959  1680017399    26971  26976.6
17421  20230328   233000    233959  1680017999  26976.7  27057.3
17422  20230328   234000    234959  1680018599  27052.9  26951.4
17423  20230328   235000    235959  1680019199  26951.4  26984.9
17424  20230329   000000    000959  1680019799  26984.8  26896.8
2023-03-29 00:10:01,654:INFO:pyemd2:main.py:127:handleKline:185189: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=17770 

self.closeSec=1680020399, self.tradeDate='20230329', self.openTime='001000', self.closeTime='001959', self.symbol='BTCUSDT', self.open='26896.9', self.close='26873.9'
127.0.0.1 - - [29/Mar/2023 00:20:04] "POST / HTTP/1.1" 200 -
2023-03-29 00:20:10,022:INFO:pyemd2:main.py:125:handleKline:185189: self.closeSec=1680020399, self.tradeDate='20230329', self.openTime='001000', self.closeTime='001959',self.symbol='BTCUSDT',self.open='26896.9', self.close='26873.9'
2023-03-29 00:20:10,161:INFO:pyemd2:main.py:126:handleKline:185189: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
17421  20230328   233000    233959  1680017999  26976.7  27057.3
17422  20230328   234000    234959  1680018599  27052.9  26951.4
17423  20230328   235000    235959  1680019199  26951.4  26984.9
17424  20230329   000000    000959  1680019799  26984.8  26896.8
17425  20230329   001000    001959  1680020399  26896.9  26873.9
2023-03-29 00:20:10,162:INFO:pyemd2:main.py:127:handleKline:185189: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}


## /root/FIL/strategy/similarity/log.txt ----- -----

127.0.0.1 - - [29/Mar/2023 00:00:03] "POST / HTTP/1.1" 200 -
2023-03-29 00:00:03,412:INFO:testStrategy:main.py:308:handleOrderFilled:185174: handleOrderFilled: data=OrderType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'clientorderid': '42072F1680019202876I0L2', 'symbol': 'BTCUSDT', 'gatewayorderid': 1680019202986174, 'quantity': '45.826', 'price': '26986.2', 'stopprice': '0', 'ordertype': '', 'side': 'SELL', 'status': 'FILLED', 'positionside': 'SHORT', 'createtime': 1680019202429, 'updatetime': 1680019202986, 'tradetype': 'usdt', 'selfid': 42072, 'filltrades': [TradeType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'tradeid': 1680019202986, 'clientorderid': '42072F1680019202876I0L2', 'price': '26986.2', 'quantity': '45.826', 'commission': '1236.6696012', 'commissionasset': 'USDT', 'tradetime': 1680019202986, 'tradetype': 'usdt', 'gatetype': 'simulator', 'handletime': 1680019202986}], 'gatetype': 'simulator', 'handletime': 0}
127.0.0.1 - - [29/Mar/2023 00:10:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=17769 

self.closeSec=1680019799, self.tradeDate='20230329', self.openTime='000000', self.closeTime='000959', self.symbol='BTCUSDT', self.open='26984.8', self.close='26896.8'
2023-03-29 00:10:01,630:INFO:testStrategy:main.py:101:handleKline:185174: self.closeSec=1680019799, self.tradeDate='20230329', self.openTime='000000', self.closeTime='000959',self.symbol='BTCUSDT',self.open='26984.8', self.close='26896.8'
2023-03-29 00:10:01,651:INFO:testStrategy:main.py:102:handleKline:185174: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
12236  20230328   232000    232959  1680017399    26971  26976.6
12237  20230328   233000    233959  1680017999  26976.7  27057.3
12238  20230328   234000    234959  1680018599  27052.9  26951.4
12239  20230328   235000    235959  1680019199  26951.4  26984.9
12240  20230329   000000    000959  1680019799  26984.8  26896.8
2023-03-29 00:10:01,651:INFO:testStrategy:main.py:103:handleKline:185174: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': True, 'isOpen': False, 'isClose': True, 'isTrig': False, 'isCorr': False}

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=17770 

self.closeSec=1680020399, self.tradeDate='20230329', self.openTime='001000', self.closeTime='001959', self.symbol='BTCUSDT', self.open='26896.9', self.close='26873.9'
127.0.0.1 - - [29/Mar/2023 00:20:04] "POST / HTTP/1.1" 200 -
2023-03-29 00:20:09,491:INFO:testStrategy:main.py:101:handleKline:185174: self.closeSec=1680020399, self.tradeDate='20230329', self.openTime='001000', self.closeTime='001959',self.symbol='BTCUSDT',self.open='26896.9', self.close='26873.9'
2023-03-29 00:20:09,790:INFO:testStrategy:main.py:102:handleKline:185174: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
12237  20230328   233000    233959  1680017999  26976.7  27057.3
12238  20230328   234000    234959  1680018599  27052.9  26951.4
12239  20230328   235000    235959  1680019199  26951.4  26984.9
12240  20230329   000000    000959  1680019799  26984.8  26896.8
12241  20230329   001000    001959  1680020399  26896.9  26873.9
2023-03-29 00:20:09,790:INFO:testStrategy:main.py:103:handleKline:185174: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': True, 'isOpen': False, 'isClose': True, 'isTrig': False, 'isCorr': False}


## /root/FIL/strategy/sr_min/log.txt ----- -----

--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=0, self.total=1000000.0, self.flagDict['side']='', self.tradeCount=0, self.count=30970
self.closeSec=1680020399, self.tradeDate='20230329', self.openTime='001500', self.closeTime='001959', self.symbol='BTCUSDT', self.open=26911.4, self.close=26873.9, self.high=26916.1, self.low=26855.0, self.vol=2073.78, self.amt=55744031.9004 
127.0.0.1 - - [29/Mar/2023 00:20:02] "POST / HTTP/1.1" 200 -
2023-03-29 00:20:06,462:INFO:sr_min:main.py:172:handleKline:449472: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5759  20230328   235500    235959  ...         0.0        0.0       0
5760  20230329   000000    000459  ...         0.0        0.0       0
5761  20230329   000500    000959  ...         0.0        0.0       0
5762  20230329   001000    001459  ...         0.0        0.0       0
5763  20230329   001500    001959  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-03-29 00:20:06,492:INFO:sr_min:main.py:175:handleKline:449472: self.closeSec=1680020399, self.tradeDate='20230329', self.openTime='001500', self.closeTime='001959',self.symbol='BTCUSDT',self.open=26911.4, self.close=26873.9, self.high=26916.1, self.low=26855.0, self.vol=2073.78, self.amt=55744031.9004, ukdf['pct'].iloc[-1]=-0.001393 , ukdf['amount'].iloc[-1]=55744031.9004, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5763, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': []}
type(curSign)=<class 'int'>, curSign=0, self.sign=0
127.0.0.1 - - [29/Mar/2023 00:25:01] "POST / HTTP/1.1" 200 -
--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=0, self.total=1000000.0, self.flagDict['side']='', self.tradeCount=0, self.count=30971
self.closeSec=1680020699, self.tradeDate='20230329', self.openTime='002000', self.closeTime='002459', self.symbol='BTCUSDT', self.open=26873.8, self.close=26877.5, self.high=26916.2, self.low=26859.7, self.vol=2164.24, self.amt=58181586.9058 
2023-03-29 00:25:01,636:INFO:sr_min:main.py:172:handleKline:449472: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5760  20230329   000000    000459  ...         0.0        0.0       0
5761  20230329   000500    000959  ...         0.0        0.0       0
5762  20230329   001000    001459  ...         0.0        0.0       0
5763  20230329   001500    001959  ...         0.0        0.0       0
5764  20230329   002000    002459  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-03-29 00:25:01,636:INFO:sr_min:main.py:175:handleKline:449472: self.closeSec=1680020699, self.tradeDate='20230329', self.openTime='002000', self.closeTime='002459',self.symbol='BTCUSDT',self.open=26873.8, self.close=26877.5, self.high=26916.2, self.low=26859.7, self.vol=2164.24, self.amt=58181586.9058, ukdf['pct'].iloc[-1]=0.000134 , ukdf['amount'].iloc[-1]=58181586.9058, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5764, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': []}
type(curSign)=<class 'int'>, curSign=0, self.sign=0


## /root/FIL/strategy/s_rsrs/log.txt ----- -----

723  20230328   120000    155959  1679990399  ...    723  0.178320 -0.876850    -1.0
724  20230328   160000    195959  1680004799  ...    724  0.190310 -0.830932    -1.0

[5 rows x 15 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '53.706', 'enterprice': '28091.1', 'countrevence': '0', 'unrealprofit': '55446.0744', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '27058.7', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'numpy.int64'>, curSign=-1, self.sign=-1
--handleKline--:  127.0.0.1 - - [29/Mar/2023 00:00:01] "POST / HTTP/1.1" 200 -
version='2.0.0', self.name='s_rsrs', self.symbol='BTCUSDT', interval='4h', intervalSec=14400, wid=25, thd=0.6, self.sign=-1, self.total=1507151.9559834, self.flagDict['side']='sell', self.tradeCount=27, self.count=740
self.closeSec=1680019199, self.tradeDate='20230328', self.openTime='200000', self.closeTime='235959', self.symbol='BTCUSDT', self.open=27046.8, self.close=26984.9, self.high=27200.0, self.low=26820.1, self.vol=123639.089, self.amt=3334585294.95625 
2023-03-29 00:00:01,918:INFO:s_rsrs:main.py:141:handleKline:185271: self.closeSec=1680019199, self.tradeDate='20230328', self.openTime='200000', self.closeTime='235959',self.symbol='BTCUSDT',self.open=27046.8, self.close=26984.9, self.high=27200.0, self.low=26820.1, self.vol=123639.089, self.amt=3334585294.95625 
2023-03-29 00:00:01,978:INFO:s_rsrs:main.py:142:handleKline:185271: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime  ...         vol           amt       pct
721  20230328   040000    075959  ...   53997.391  1.461752e+09  0.005802
722  20230328   080000    115959  ...   65014.849  1.755064e+09 -0.005776
723  20230328   120000    155959  ...   58393.922  1.575997e+09 -0.000078
724  20230328   160000    195959  ...  128635.011  3.456745e+09  0.003421
725  20230328   200000    235959  ...  123639.089  3.334585e+09 -0.002244

[5 rows x 11 columns]
2023-03-29 00:00:04,698:INFO:s_rsrs:main.py:151:handleKline:185271: df_s.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec  ...  index      beta    zscore  signal
721  20230328   040000    075959  1679961599  ...    721  0.151166 -0.975929    -1.0
722  20230328   080000    115959  1679975999  ...    722  0.165832 -0.923551    -1.0
723  20230328   120000    155959  1679990399  ...    723  0.178320 -0.876850    -1.0
724  20230328   160000    195959  1680004799  ...    724  0.190310 -0.830932    -1.0
725  20230328   200000    235959  1680019199  ...    725  0.235390 -0.710596    -1.0

[5 rows x 15 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '53.706', 'enterprice': '28091.1', 'countrevence': '0', 'unrealprofit': '59332.49279452548', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '26986.33530342', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'numpy.int64'>, curSign=-1, self.sign=-1


