# 20230623 00:26:01

## /root/FIL/strategy/amihud/log.txt ----- -----

--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=373746.4768026, self.flagDict['side']='sell', self.tradeCount=2, self.count=11392
self.closeSec=1687450799, self.tradeDate='20230623', self.openTime='001500', self.closeTime='001959', self.symbol='BTCUSDT', self.open=29936.1, self.close=29880.6, self.high=29936.8, self.low=29856.5, self.vol=2440.204, self.amt=72959827.8367 
127.0.0.1 - - [23/Jun/2023 00:20:02] "POST / HTTP/1.1" 200 -
2023-06-23 00:20:07,665:INFO:amihud:main.py:172:handleKline:2219019: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5759  20230622   235500    235959  ...         0.0        0.0       0
5760  20230623   000000    000459  ...         0.0        0.0       0
5761  20230623   000500    000959  ...         0.0        0.0       0
5762  20230623   001000    001459  ...         0.0        0.0       0
5763  20230623   001500    001959  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-06-23 00:20:07,705:INFO:amihud:main.py:175:handleKline:2219019: self.closeSec=1687450799, self.tradeDate='20230623', self.openTime='001500', self.closeTime='001959',self.symbol='BTCUSDT',self.open=29936.1, self.close=29880.6, self.high=29936.8, self.low=29856.5, self.vol=2440.204, self.amt=72959827.8367, ukdf['pct'].iloc[-1]=-0.001857 , ukdf['amount'].iloc[-1]=72959827.8367, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5763, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '13.926', 'enterprice': '26864.9', 'countrevence': '0', 'unrealprofit': '-42037.0236', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '29883.5', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1
--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=373746.4768026, self.flagDict['side']='sell', self.tradeCount=2, self.count=11393
self.closeSec=1687451099, self.tradeDate='20230623', self.openTime='002000', self.closeTime='002459', self.symbol='BTCUSDT', self.open=29880.7, self.close=29957.0, self.high=29968.2, self.low=29880.6, self.vol=1908.253, self.amt=57110382.6695 
127.0.0.1 - - [23/Jun/2023 00:25:00] "POST / HTTP/1.1" 200 -
2023-06-23 00:25:00,809:INFO:amihud:main.py:172:handleKline:2219019: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5760  20230623   000000    000459  ...         0.0        0.0       0
5761  20230623   000500    000959  ...         0.0        0.0       0
5762  20230623   001000    001459  ...         0.0        0.0       0
5763  20230623   001500    001959  ...         0.0        0.0       0
5764  20230623   002000    002459  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-06-23 00:25:00,809:INFO:amihud:main.py:175:handleKline:2219019: self.closeSec=1687451099, self.tradeDate='20230623', self.openTime='002000', self.closeTime='002459',self.symbol='BTCUSDT',self.open=29880.7, self.close=29957.0, self.high=29968.2, self.low=29880.6, self.vol=1908.253, self.amt=57110382.6695, ukdf['pct'].iloc[-1]=0.002557 , ukdf['amount'].iloc[-1]=57110382.6695, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5764, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '13.926', 'enterprice': '26864.9', 'countrevence': '0', 'unrealprofit': '-43056.4068', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '29956.7', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1


## /root/FIL/strategy/factorcheck/log.txt ----- -----


self.closeSec=1687450799, self.tradeDate='20230623', self.openTime='001500', self.closeTime='001959', self.symbol='BTCUSDT', self.open=29936.1, self.close=29880.6, self.high=29936.8, self.low=29856.5 
127.0.0.1 - - [23/Jun/2023 00:20:01] "POST / HTTP/1.1" 200 -
2023-06-23 00:20:05,114:INFO:factorcheck2:main.py:126:handleKline:2218005: self.closeSec=1687450799, self.tradeDate='20230623', self.openTime='001500', self.closeTime='001959',self.symbol='BTCUSDT',self.open=29936.1, self.close=29880.6, self.high=29936.8, self.low=29856.5   
2023-06-23 00:20:06,575:INFO:factorcheck2:main.py:127:handleKline:2218005: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime    closeSec  ...      low       pct  index  idx
1439  20230622   235500    235959  1687449599  ...  29818.9 -0.000268   1727    5
1440  20230623   000000    000459  1687449899  ...  29811.9  0.000684   1440    0
1441  20230623   000500    000959  1687450199  ...  29856.0  0.002435   1441    1
1442  20230623   001000    001459  1687450499  ...  29891.0  0.000194   1442    2
1443  20230623   001500    001959  1687450799  ...  29856.5 -0.001857   1443    3

[5 rows x 11 columns]
2023-06-23 00:20:06,585:INFO:factorcheck2:main.py:128:handleKline:2218005: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}
127.0.0.1 - - [23/Jun/2023 00:25:00] "POST / HTTP/1.1" 200 -

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=277, self.factor=0.35246255753522054, self.count=11395 

self.closeSec=1687451099, self.tradeDate='20230623', self.openTime='002000', self.closeTime='002459', self.symbol='BTCUSDT', self.open=29880.7, self.close=29957.0, self.high=29968.2, self.low=29880.6 
2023-06-23 00:25:00,747:INFO:factorcheck2:main.py:126:handleKline:2218005: self.closeSec=1687451099, self.tradeDate='20230623', self.openTime='002000', self.closeTime='002459',self.symbol='BTCUSDT',self.open=29880.7, self.close=29957.0, self.high=29968.2, self.low=29880.6   
2023-06-23 00:25:00,787:INFO:factorcheck2:main.py:127:handleKline:2218005: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime    closeSec  ...      low       pct  index  idx
1440  20230623   000000    000459  1687449899  ...  29811.9  0.000684   1440    0
1441  20230623   000500    000959  1687450199  ...  29856.0  0.002435   1441    1
1442  20230623   001000    001459  1687450499  ...  29891.0  0.000194   1442    2
1443  20230623   001500    001959  1687450799  ...  29856.5 -0.001857   1443    3
1444  20230623   002000    002459  1687451099  ...  29880.6  0.002557   1444    4

[5 rows x 11 columns]
2023-06-23 00:25:00,787:INFO:factorcheck2:main.py:128:handleKline:2218005: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}


## /root/FIL/strategy/logic/log.txt ----- -----

2023-06-23 00:00:18,409:DEBUG:logic:main.py:463:getModel:2218526: df_s.iloc[-5:,:] :
          date closeTime     open  ...    alpha58   alpha67   alpha72
5802  20230622    212959  30099.1  ...  57.916667  0.609067  0.415253
5803  20230622    215959  30231.0  ...  57.500000  0.608503  0.411688
5804  20230622    222959  30226.9  ...  57.500000  0.597344  0.416209
5805  20230622    225959  30146.7  ...  57.083333  0.548423  0.439168
5806  20230622    232959  29735.4  ...  56.666667  0.546844  0.461542

[5 rows x 33 columns]
0.5661764705882353
acc is : 0.5661764705882353
2023-06-23 00:00:18,495:INFO:logic:main.py:468:getModel:2218526: df_pred.iloc[-5:,:] :
     pred    prob_0    prob_1  actual  ...       nav  sign  cost_        bm
539     0  0.513328  0.486672       0  ...  1.137947  -1.0    0.0  1.174860
540     0  0.507951  0.492049       0  ...  1.141147  -1.0    0.0  1.171556
541     1  0.498687  0.501313       0  ...  1.156488  -1.0    0.0  1.155807
542     1  0.414750  0.585250       0  ...  1.157032  -1.0    0.0  1.155263
543     1  0.463081  0.536919       1  ...  1.152567  -1.0    0.0  1.159721

[5 rows x 10 columns]
2023-06-23 00:00:18,521:INFO:logic:main.py:478:getModel:2218526: df_panel.iloc[-5:,:] :
    pred    prob_0    prob_1  actual  ...       nav  sign  cost_        bm
45     0  0.513865  0.486135       0  ...  1.137947  -1.0    0.0  1.172540
46     0  0.507416  0.492584       0  ...  1.141147  -1.0    0.0  1.169375
47     1  0.498365  0.501635       0  ...  1.156488  -1.0    0.0  1.153655
48     1  0.415426  0.584574       0  ...  1.157032  -1.0    0.0  1.153340
49     1  0.463081  0.536919       1  ...  1.152567  -1.0    0.0  1.159721

[5 rows x 10 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '26.839', 'enterprice': '29991.1', 'countrevence': '0', 'unrealprofit': '4412.3316', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '29826.7', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}


## /root/FIL/strategy/modifiedmom/log.txt ----- -----

127.0.0.1 - - [23/Jun/2023 00:00:04] "POST / HTTP/1.1" 200 -
2023-06-23 00:00:04,455:INFO:modifiedmom:main.py:319:handleOrderFilled:2218259: handleOrderFilled: data=OrderType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'clientorderid': '42442F1687449603593I0L59', 'symbol': 'BTCUSDT', 'gatewayorderid': 1687449604002803, 'quantity': '25.087', 'price': '29837.3', 'stopprice': '0', 'ordertype': '', 'side': 'BUY', 'status': 'FILLED', 'positionside': 'LONG', 'createtime': 1687449602696, 'updatetime': 1687449604002, 'tradetype': 'usdt', 'selfid': 42442, 'filltrades': [TradeType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'tradeid': 1687449604002, 'clientorderid': '42442F1687449603593I0L59', 'price': '29837.3', 'quantity': '25.087', 'commission': '748.5283451', 'commissionasset': 'USDT', 'tradetime': 1687449604002, 'tradetype': 'usdt', 'gatetype': 'simulator', 'handletime': 1687449604002}], 'gatetype': 'simulator', 'handletime': 0}
127.0.0.1 - - [23/Jun/2023 00:10:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=5696 

self.closeSec=1687450199, self.tradeDate='20230623', self.openTime='000000', self.closeTime='000959', self.symbol='BTCUSDT', self.open='29837.3', self.close='29930.4'
2023-06-23 00:10:01,123:INFO:modifiedmom:main.py:144:handleKline:2218259: self.closeSec=1687450199, self.tradeDate='20230623', self.openTime='000000', self.closeTime='000959',self.symbol='BTCUSDT',self.open='29837.3', self.close='29930.4'
2023-06-23 00:10:01,135:INFO:modifiedmom:main.py:145:handleKline:2218259: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec     open    close       pct
572  20230622   232000    232959  1687447799  29766.6  29722.6 -0.001478
573  20230622   233000    233959  1687448399  29722.6  29712.7 -0.000333
574  20230622   234000    234959  1687448999  29712.7  29828.1  0.003884
575  20230622   235000    235959  1687449599    29828  29837.3  0.000308
576  20230623   000000    000959  1687450199  29837.3  29930.4  0.003120
2023-06-23 00:10:01,135:INFO:modifiedmom:main.py:146:handleKline:2218259: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': True, 'isOpen': False, 'isClose': True, 'isTrig': False}

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=5697 

self.closeSec=1687450799, self.tradeDate='20230623', self.openTime='001000', self.closeTime='001959', self.symbol='BTCUSDT', self.open='29930.5', self.close='29880.6'
127.0.0.1 - - [23/Jun/2023 00:20:04] "POST / HTTP/1.1" 200 -
2023-06-23 00:20:07,455:INFO:modifiedmom:main.py:144:handleKline:2218259: self.closeSec=1687450799, self.tradeDate='20230623', self.openTime='001000', self.closeTime='001959',self.symbol='BTCUSDT',self.open='29930.5', self.close='29880.6'
2023-06-23 00:20:08,254:INFO:modifiedmom:main.py:145:handleKline:2218259: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec     open    close       pct
573  20230622   233000    233959  1687448399  29722.6  29712.7 -0.000333
574  20230622   234000    234959  1687448999  29712.7  29828.1  0.003884
575  20230622   235000    235959  1687449599    29828  29837.3  0.000308
576  20230623   000000    000959  1687450199  29837.3  29930.4  0.003120
577  20230623   001000    001959  1687450799  29930.5  29880.6 -0.001664
2023-06-23 00:20:08,255:INFO:modifiedmom:main.py:146:handleKline:2218259: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': True, 'isOpen': False, 'isClose': True, 'isTrig': False}


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

127.0.0.1 - - [23/Jun/2023 00:00:04] "POST / HTTP/1.1" 200 -
2023-06-23 00:00:04,149:INFO:pyemd2:main.py:303:handleOrderFilled:2217508: handleOrderFilled: data=OrderType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'clientorderid': '42441F1687449603553I0L57', 'symbol': 'BTCUSDT', 'gatewayorderid': 1687449603916667, 'quantity': '32.26', 'price': '29837.2', 'stopprice': '0', 'ordertype': '', 'side': 'SELL', 'status': 'FILLED', 'positionside': 'SHORT', 'createtime': 1687449602563, 'updatetime': 1687449603916, 'tradetype': 'usdt', 'selfid': 42441, 'filltrades': [TradeType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'tradeid': 1687449603916, 'clientorderid': '42441F1687449603553I0L57', 'price': '29837.2', 'quantity': '32.26', 'commission': '962.548072', 'commissionasset': 'USDT', 'tradetime': 1687449603916, 'tradetype': 'usdt', 'gatetype': 'simulator', 'handletime': 1687449603916}], 'gatetype': 'simulator', 'handletime': 0}
127.0.0.1 - - [23/Jun/2023 00:10:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=5699 

self.closeSec=1687450199, self.tradeDate='20230623', self.openTime='000000', self.closeTime='000959', self.symbol='BTCUSDT', self.open='29837.3', self.close='29930.4'
2023-06-23 00:10:01,139:INFO:pyemd2:main.py:125:handleKline:2217508: self.closeSec=1687450199, self.tradeDate='20230623', self.openTime='000000', self.closeTime='000959',self.symbol='BTCUSDT',self.open='29837.3', self.close='29930.4'
2023-06-23 00:10:01,146:INFO:pyemd2:main.py:126:handleKline:2217508: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
17420  20230622   232000    232959  1687447799  29766.6  29722.6
17421  20230622   233000    233959  1687448399  29722.6  29712.7
17422  20230622   234000    234959  1687448999  29712.7  29828.1
17423  20230622   235000    235959  1687449599    29828  29837.3
17424  20230623   000000    000959  1687450199  29837.3  29930.4
2023-06-23 00:10:01,146:INFO:pyemd2:main.py:127:handleKline:2217508: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=5700 

self.closeSec=1687450799, self.tradeDate='20230623', self.openTime='001000', self.closeTime='001959', self.symbol='BTCUSDT', self.open='29930.5', self.close='29880.6'
127.0.0.1 - - [23/Jun/2023 00:20:04] "POST / HTTP/1.1" 200 -
2023-06-23 00:20:09,520:INFO:pyemd2:main.py:125:handleKline:2217508: self.closeSec=1687450799, self.tradeDate='20230623', self.openTime='001000', self.closeTime='001959',self.symbol='BTCUSDT',self.open='29930.5', self.close='29880.6'
2023-06-23 00:20:09,650:INFO:pyemd2:main.py:126:handleKline:2217508: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
17421  20230622   233000    233959  1687448399  29722.6  29712.7
17422  20230622   234000    234959  1687448999  29712.7  29828.1
17423  20230622   235000    235959  1687449599    29828  29837.3
17424  20230623   000000    000959  1687450199  29837.3  29930.4
17425  20230623   001000    001959  1687450799  29930.5  29880.6
2023-06-23 00:20:09,650:INFO:pyemd2:main.py:127:handleKline:2217508: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}


## /root/FIL/strategy/similarity/log.txt ----- -----

127.0.0.1 - - [23/Jun/2023 00:00:04] "POST / HTTP/1.1" 200 -
2023-06-23 00:00:04,638:INFO:testStrategy:main.py:308:handleOrderFilled:2217133: handleOrderFilled: data=OrderType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'clientorderid': '42443F1687449603635I0L2', 'symbol': 'BTCUSDT', 'gatewayorderid': 1687449604031165, 'quantity': '41.056', 'price': '29837.2', 'stopprice': '0', 'ordertype': '', 'side': 'SELL', 'status': 'FILLED', 'positionside': 'SHORT', 'createtime': 1687449602646, 'updatetime': 1687449604031, 'tradetype': 'usdt', 'selfid': 42443, 'filltrades': [TradeType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'tradeid': 1687449604031, 'clientorderid': '42443F1687449603635I0L2', 'price': '29837.2', 'quantity': '41.056', 'commission': '1224.9960832', 'commissionasset': 'USDT', 'tradetime': 1687449604031, 'tradetype': 'usdt', 'gatetype': 'simulator', 'handletime': 1687449604031}], 'gatetype': 'simulator', 'handletime': 0}
127.0.0.1 - - [23/Jun/2023 00:10:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=5699 

self.closeSec=1687450199, self.tradeDate='20230623', self.openTime='000000', self.closeTime='000959', self.symbol='BTCUSDT', self.open='29837.3', self.close='29930.4'
2023-06-23 00:10:01,147:INFO:testStrategy:main.py:101:handleKline:2217133: self.closeSec=1687450199, self.tradeDate='20230623', self.openTime='000000', self.closeTime='000959',self.symbol='BTCUSDT',self.open='29837.3', self.close='29930.4'
2023-06-23 00:10:01,161:INFO:testStrategy:main.py:102:handleKline:2217133: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
12236  20230622   232000    232959  1687447799  29766.6  29722.6
12237  20230622   233000    233959  1687448399  29722.6  29712.7
12238  20230622   234000    234959  1687448999  29712.7  29828.1
12239  20230622   235000    235959  1687449599    29828  29837.3
12240  20230623   000000    000959  1687450199  29837.3  29930.4
2023-06-23 00:10:01,161:INFO:testStrategy:main.py:103:handleKline:2217133: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': True, 'isOpen': False, 'isClose': True, 'isTrig': False, 'isCorr': False}

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=5700 

self.closeSec=1687450799, self.tradeDate='20230623', self.openTime='001000', self.closeTime='001959', self.symbol='BTCUSDT', self.open='29930.5', self.close='29880.6'
127.0.0.1 - - [23/Jun/2023 00:20:04] "POST / HTTP/1.1" 200 -
2023-06-23 00:20:09,024:INFO:testStrategy:main.py:101:handleKline:2217133: self.closeSec=1687450799, self.tradeDate='20230623', self.openTime='001000', self.closeTime='001959',self.symbol='BTCUSDT',self.open='29930.5', self.close='29880.6'
2023-06-23 00:20:09,346:INFO:testStrategy:main.py:102:handleKline:2217133: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
12237  20230622   233000    233959  1687448399  29722.6  29712.7
12238  20230622   234000    234959  1687448999  29712.7  29828.1
12239  20230622   235000    235959  1687449599    29828  29837.3
12240  20230623   000000    000959  1687450199  29837.3  29930.4
12241  20230623   001000    001959  1687450799  29930.5  29880.6
2023-06-23 00:20:09,347:INFO:testStrategy:main.py:103:handleKline:2217133: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': True, 'isOpen': False, 'isClose': True, 'isTrig': False, 'isCorr': False}


## /root/FIL/strategy/sr_min/log.txt ----- -----

--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=1, self.total=996015.990996, self.flagDict['side']='buy', self.tradeCount=1, self.count=11392
self.closeSec=1687450799, self.tradeDate='20230623', self.openTime='001500', self.closeTime='001959', self.symbol='BTCUSDT', self.open=29936.1, self.close=29880.6, self.high=29936.8, self.low=29856.5, self.vol=2440.204, self.amt=72959827.8367 
127.0.0.1 - - [23/Jun/2023 00:20:01] "POST / HTTP/1.1" 200 -
2023-06-23 00:20:07,605:INFO:sr_min:main.py:172:handleKline:2219263: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5759  20230622   235500    235959  ...         0.0        0.0       0
5760  20230623   000000    000459  ...         0.0        0.0       0
5761  20230623   000500    000959  ...         0.0        0.0       0
5762  20230623   001000    001459  ...         0.0        0.0       0
5763  20230623   001500    001959  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-06-23 00:20:07,635:INFO:sr_min:main.py:175:handleKline:2219263: self.closeSec=1687450799, self.tradeDate='20230623', self.openTime='001500', self.closeTime='001959',self.symbol='BTCUSDT',self.open=29936.1, self.close=29880.6, self.high=29936.8, self.low=29856.5, self.vol=2440.204, self.amt=72959827.8367, ukdf['pct'].iloc[-1]=-0.001857 , ukdf['amount'].iloc[-1]=72959827.8367, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5763, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '37.141', 'enterprice': '26844', 'countrevence': '0', 'unrealprofit': '112893.7836', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '29883.6', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=1
127.0.0.1 - - [23/Jun/2023 00:25:00] "POST / HTTP/1.1" 200 -
--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=1, self.total=996015.990996, self.flagDict['side']='buy', self.tradeCount=1, self.count=11393
self.closeSec=1687451099, self.tradeDate='20230623', self.openTime='002000', self.closeTime='002459', self.symbol='BTCUSDT', self.open=29880.7, self.close=29957.0, self.high=29968.2, self.low=29880.6, self.vol=1908.253, self.amt=57110382.6695 
2023-06-23 00:25:00,804:INFO:sr_min:main.py:172:handleKline:2219263: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5760  20230623   000000    000459  ...         0.0        0.0       0
5761  20230623   000500    000959  ...         0.0        0.0       0
5762  20230623   001000    001459  ...         0.0        0.0       0
5763  20230623   001500    001959  ...         0.0        0.0       0
5764  20230623   002000    002459  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-06-23 00:25:00,804:INFO:sr_min:main.py:175:handleKline:2219263: self.closeSec=1687451099, self.tradeDate='20230623', self.openTime='002000', self.closeTime='002459',self.symbol='BTCUSDT',self.open=29880.7, self.close=29957.0, self.high=29968.2, self.low=29880.6, self.vol=1908.253, self.amt=57110382.6695, ukdf['pct'].iloc[-1]=0.002557 , ukdf['amount'].iloc[-1]=57110382.6695, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5764, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '37.141', 'enterprice': '26844', 'countrevence': '0', 'unrealprofit': '115608.7907', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '29956.7', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=1


## /root/FIL/strategy/s_rsrs/log.txt ----- -----

723  20230622   120000    155959  1687420799  ...    723  1.187797  2.221400     1.0
724  20230622   160000    195959  1687435199  ...    724  1.158098  2.047588     1.0

[5 rows x 15 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '53.344', 'enterprice': '27977.7', 'countrevence': '0', 'unrealprofit': '103391.3408', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '29915.9', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'numpy.int64'>, curSign=1, self.sign=1
--handleKline--:  version='2.0.0', self.name='s_rsrs', self.symbol='BTCUSDT', interval='4h', intervalSec=14400, wid=25, thd=0.6, self.sign=1, self.total=1490949.9863712, self.flagDict['side']='buy', self.tradeCount=7, self.count=237
self.closeSec=1687449599, self.tradeDate='20230622', self.openTime='200000', self.closeTime='235959', self.symbol='BTCUSDT', self.open=29919.4, self.close=29837.3, self.high=30353.9, self.low=29500.1, self.vol=177543.354, self.amt=5315799274.00747 
127.0.0.1 - - [23/Jun/2023 00:00:01] "POST / HTTP/1.1" 200 -
2023-06-23 00:00:01,698:INFO:s_rsrs:main.py:141:handleKline:2218689: self.closeSec=1687449599, self.tradeDate='20230622', self.openTime='200000', self.closeTime='235959',self.symbol='BTCUSDT',self.open=29919.4, self.close=29837.3, self.high=30353.9, self.low=29500.1, self.vol=177543.354, self.amt=5315799274.00747 
2023-06-23 00:00:01,717:INFO:s_rsrs:main.py:142:handleKline:2218689: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime  ...         vol           amt       pct
721  20230622   040000    075959  ...   81982.531  2.459183e+09 -0.003890
722  20230622   080000    115959  ...   84397.179  2.549850e+09  0.009847
723  20230622   120000    155959  ...   59869.993  1.805752e+09 -0.006248
724  20230622   160000    195959  ...   92709.438  2.784195e+09 -0.005822
725  20230622   200000    235959  ...  177543.354  5.315799e+09 -0.002741

[5 rows x 11 columns]
2023-06-23 00:00:03,224:INFO:s_rsrs:main.py:151:handleKline:2218689: df_s.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec  ...  index      beta    zscore  signal
721  20230622   040000    075959  1687391999  ...    721  1.294642  2.812975     1.0
722  20230622   080000    115959  1687406399  ...    722  1.255200  2.543640     1.0
723  20230622   120000    155959  1687420799  ...    723  1.187797  2.221400     1.0
724  20230622   160000    195959  1687435199  ...    724  1.158098  2.047588     1.0
725  20230622   200000    235959  1687449599  ...    725  1.165810  2.001616     1.0

[5 rows x 15 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '53.344', 'enterprice': '27977.7', 'countrevence': '0', 'unrealprofit': '99198.5024', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '29837.3', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'numpy.int64'>, curSign=1, self.sign=1


