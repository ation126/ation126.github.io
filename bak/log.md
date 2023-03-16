# 20230317 00:26:02

## /root/FIL/strategy/amihud/log.txt ----- -----

--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=993672.4896432, self.flagDict['side']='sell', self.tradeCount=2, self.count=31516
self.closeSec=1678983599, self.tradeDate='20230317', self.openTime='001500', self.closeTime='001959', self.symbol='BTCUSDT', self.open=24806.4, self.close=24809.4, self.high=24815.0, self.low=24782.5, self.vol=1419.08, self.amt=35193292.1297 
127.0.0.1 - - [17/Mar/2023 00:20:03] "POST / HTTP/1.1" 200 -
2023-03-17 00:20:09,786:INFO:amihud:main.py:172:handleKline:200676: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5759  20230316   235500    235959  ...         0.0        0.0       0
5760  20230317   000000    000459  ...         0.0        0.0       0
5761  20230317   000500    000959  ...         0.0        0.0       0
5762  20230317   001000    001459  ...         0.0        0.0       0
5763  20230317   001500    001959  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-03-17 00:20:09,816:INFO:amihud:main.py:175:handleKline:200676: self.closeSec=1678983599, self.tradeDate='20230317', self.openTime='001500', self.closeTime='001959',self.symbol='BTCUSDT',self.open=24806.4, self.close=24809.4, self.high=24815.0, self.low=24782.5, self.vol=1419.08, self.amt=35193292.1297, ukdf['pct'].iloc[-1]=0.000125 , ukdf['amount'].iloc[-1]=35193292.1297, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5763, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '60.176', 'enterprice': '16529.3', 'countrevence': '0', 'unrealprofit': '-498256.93342415088', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '24809.29424063', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1
--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=993672.4896432, self.flagDict['side']='sell', self.tradeCount=2, self.count=31517
self.closeSec=1678983899, self.tradeDate='20230317', self.openTime='002000', self.closeTime='002459', self.symbol='BTCUSDT', self.open=24809.4, self.close=24778.6, self.high=24811.0, self.low=24726.5, self.vol=2388.372, self.amt=59149743.8017 
127.0.0.1 - - [17/Mar/2023 00:25:01] "POST / HTTP/1.1" 200 -
2023-03-17 00:25:01,651:INFO:amihud:main.py:172:handleKline:200676: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5760  20230317   000000    000459  ...         0.0        0.0       0
5761  20230317   000500    000959  ...         0.0        0.0       0
5762  20230317   001000    001459  ...         0.0        0.0       0
5763  20230317   001500    001959  ...         0.0        0.0       0
5764  20230317   002000    002459  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-03-17 00:25:01,651:INFO:amihud:main.py:175:handleKline:200676: self.closeSec=1678983899, self.tradeDate='20230317', self.openTime='002000', self.closeTime='002459',self.symbol='BTCUSDT',self.open=24809.4, self.close=24778.6, self.high=24811.0, self.low=24726.5, self.vol=2388.372, self.amt=59149743.8017, ukdf['pct'].iloc[-1]=-0.001241 , ukdf['amount'].iloc[-1]=59149743.8017, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5764, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '60.176', 'enterprice': '16529.3', 'countrevence': '0', 'unrealprofit': '-496403.8592', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '24778.5', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1


## /root/FIL/strategy/factorcheck/log.txt ----- -----


self.closeSec=1678983599, self.tradeDate='20230317', self.openTime='001500', self.closeTime='001959', self.symbol='BTCUSDT', self.open=24806.4, self.close=24809.4, self.high=24815.0, self.low=24782.5 
127.0.0.1 - - [17/Mar/2023 00:20:02] "POST / HTTP/1.1" 200 -
2023-03-17 00:20:04,706:INFO:factorcheck2:main.py:126:handleKline:185239: self.closeSec=1678983599, self.tradeDate='20230317', self.openTime='001500', self.closeTime='001959',self.symbol='BTCUSDT',self.open=24806.4, self.close=24809.4, self.high=24815.0, self.low=24782.5   
2023-03-17 00:20:06,026:INFO:factorcheck2:main.py:127:handleKline:185239: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime    closeSec  ...      low       pct  index  idx
1439  20230316   235500    235959  1678982399  ...  24855.0 -0.000454   1727    5
1440  20230317   000000    000459  1678982699  ...  24814.0 -0.001363   1440    0
1441  20230317   000500    000959  1678982999  ...  24793.1 -0.001525   1441    1
1442  20230317   001000    001459  1678983299  ...  24752.7 -0.000105   1442    2
1443  20230317   001500    001959  1678983599  ...  24782.5  0.000125   1443    3

[5 rows x 11 columns]
2023-03-17 00:20:06,026:INFO:factorcheck2:main.py:128:handleKline:185239: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': True, 'isOpenSell': False, 'isCloseBuy': False, 'isCloseSell': False, 'isOpen': True, 'isClose': False, 'isTrig': True}
127.0.0.1 - - [17/Mar/2023 00:25:01] "POST / HTTP/1.1" 200 -

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=13, self.factor=0.4789102717079375, self.count=32083 

self.closeSec=1678983899, self.tradeDate='20230317', self.openTime='002000', self.closeTime='002459', self.symbol='BTCUSDT', self.open=24809.4, self.close=24778.6, self.high=24811.0, self.low=24726.5 
2023-03-17 00:25:01,525:INFO:factorcheck2:main.py:126:handleKline:185239: self.closeSec=1678983899, self.tradeDate='20230317', self.openTime='002000', self.closeTime='002459',self.symbol='BTCUSDT',self.open=24809.4, self.close=24778.6, self.high=24811.0, self.low=24726.5   
2023-03-17 00:25:01,594:INFO:factorcheck2:main.py:127:handleKline:185239: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime    closeSec  ...      low       pct  index  idx
1440  20230317   000000    000459  1678982699  ...  24814.0 -0.001363   1440    0
1441  20230317   000500    000959  1678982999  ...  24793.1 -0.001525   1441    1
1442  20230317   001000    001459  1678983299  ...  24752.7 -0.000105   1442    2
1443  20230317   001500    001959  1678983599  ...  24782.5  0.000125   1443    3
1444  20230317   002000    002459  1678983899  ...  24726.5 -0.001241   1444    4

[5 rows x 11 columns]
2023-03-17 00:25:01,595:INFO:factorcheck2:main.py:128:handleKline:185239: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': True, 'isOpenSell': False, 'isCloseBuy': False, 'isCloseSell': False, 'isOpen': True, 'isClose': False, 'isTrig': True}


## /root/FIL/strategy/logic/log.txt ----- -----

2023-03-17 00:00:35,819:DEBUG:logic:main.py:463:getModel:885513: df_s.iloc[-5:,:] :
          date closeTime     open  ...    alpha58   alpha67   alpha72
5802  20230316    212959  24721.6  ...  52.500000  0.525652  0.433761
5803  20230316    215959  24650.1  ...  52.916667  0.542106  0.421619
5804  20230316    222959  24828.4  ...  52.500000  0.541709  0.410541
5805  20230316    225959  24819.9  ...  52.916667  0.543928  0.398542
5806  20230316    232959  24843.5  ...  52.916667  0.542622  0.388151

[5 rows x 33 columns]
0.5606617647058824
acc is : 0.5606617647058824
2023-03-17 00:00:35,989:INFO:logic:main.py:468:getModel:885513: df_pred.iloc[-5:,:] :
     pred    prob_0    prob_1  actual  ...       nav  sign  cost_        bm
539     1  0.461022  0.538978       1  ...  1.107946   1.0    0.0  1.109926
540     0  0.577280  0.422720       0  ...  1.107786   1.0    0.0  1.109765
541     0  0.518589  0.481411       1  ...  1.108830   1.0    0.0  1.110811
542     0  0.523542  0.476458       0  ...  1.108321   1.0    0.0  1.110301
543     0  0.528002  0.471998       1  ...  1.110495   1.0    0.0  1.112479

[5 rows x 10 columns]
2023-03-17 00:00:36,024:INFO:logic:main.py:478:getModel:885513: df_panel.iloc[-5:,:] :
    pred    prob_0    prob_1  actual  ...       nav  sign  cost_        bm
45     1  0.462086  0.537914       1  ...  1.107946   1.0    0.0  1.108335
46     0  0.576645  0.423355       0  ...  1.107786   1.0    0.0  1.107759
47     0  0.518408  0.481592       1  ...  1.108830   1.0    0.0  1.108803
48     0  0.523117  0.476883       0  ...  1.108321   1.0    0.0  1.109681
49     0  0.528002  0.471998       1  ...  1.110495   1.0    0.0  1.112479

[5 rows x 10 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': []}


## /root/FIL/strategy/modifiedmom/log.txt ----- -----

127.0.0.1 - - [17/Mar/2023 00:00:03] "POST / HTTP/1.1" 200 -
2023-03-17 00:00:03,811:INFO:modifiedmom:main.py:319:handleOrderFilled:185213: handleOrderFilled: data=OrderType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'clientorderid': '42005F1678982402965I0L59', 'symbol': 'BTCUSDT', 'gatewayorderid': 1678982403321895, 'quantity': '34.974', 'price': '24880.7', 'stopprice': '0', 'ordertype': '', 'side': 'BUY', 'status': 'FILLED', 'positionside': 'LONG', 'createtime': 1678982402650, 'updatetime': 1678982403321, 'tradetype': 'usdt', 'selfid': 42005, 'filltrades': [TradeType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'tradeid': 1678982403321, 'clientorderid': '42005F1678982402965I0L59', 'price': '24880.7', 'quantity': '34.974', 'commission': '870.1776018', 'commissionasset': 'USDT', 'tradetime': 1678982403321, 'tradetype': 'usdt', 'gatetype': 'simulator', 'handletime': 1678982403321}], 'gatetype': 'simulator', 'handletime': 0}

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=16040 

self.closeSec=1678982999, self.tradeDate='20230317', self.openTime='000000', self.closeTime='000959', self.symbol='BTCUSDT', self.open='24880.7', self.close='24808.9'
127.0.0.1 - - [17/Mar/2023 00:10:01] "POST / HTTP/1.1" 200 -
2023-03-17 00:10:01,718:INFO:modifiedmom:main.py:144:handleKline:185213: self.closeSec=1678982999, self.tradeDate='20230317', self.openTime='000000', self.closeTime='000959',self.symbol='BTCUSDT',self.open='24880.7', self.close='24808.9'
2023-03-17 00:10:01,746:INFO:modifiedmom:main.py:145:handleKline:185213: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec     open    close       pct
572  20230316   232000    232959  1678980599  24786.8    24832  0.001828
573  20230316   233000    233959  1678981199  24832.1  24826.8 -0.000209
574  20230316   234000    234959  1678981799  24826.8  24915.6  0.003577
575  20230316   235000    235959  1678982399  24912.1  24880.6 -0.001405
576  20230317   000000    000959  1678982999  24880.7  24808.9 -0.002882
2023-03-17 00:10:01,746:INFO:modifiedmom:main.py:146:handleKline:185213: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': True, 'isOpen': False, 'isClose': True, 'isTrig': False}

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=16041 

self.closeSec=1678983599, self.tradeDate='20230317', self.openTime='001000', self.closeTime='001959', self.symbol='BTCUSDT', self.open='24808.8', self.close='24809.4'
127.0.0.1 - - [17/Mar/2023 00:20:04] "POST / HTTP/1.1" 200 -
2023-03-17 00:20:07,676:INFO:modifiedmom:main.py:144:handleKline:185213: self.closeSec=1678983599, self.tradeDate='20230317', self.openTime='001000', self.closeTime='001959',self.symbol='BTCUSDT',self.open='24808.8', self.close='24809.4'
2023-03-17 00:20:08,635:INFO:modifiedmom:main.py:145:handleKline:185213: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec     open    close       pct
573  20230316   233000    233959  1678981199  24832.1  24826.8 -0.000209
574  20230316   234000    234959  1678981799  24826.8  24915.6  0.003577
575  20230316   235000    235959  1678982399  24912.1  24880.6 -0.001405
576  20230317   000000    000959  1678982999  24880.7  24808.9 -0.002882
577  20230317   001000    001959  1678983599  24808.8  24809.4  0.000020
2023-03-17 00:20:08,636:INFO:modifiedmom:main.py:146:handleKline:185213: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': True, 'isOpen': False, 'isClose': True, 'isTrig': False}


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

2023-03-17 00:00:03,262:INFO:pyemd2:main.py:303:handleOrderFilled:185189: handleOrderFilled: data=OrderType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'clientorderid': '42004F1678982402837I0L57', 'symbol': 'BTCUSDT', 'gatewayorderid': 1678982402950874, 'quantity': '42.394', 'price': '24880.6', 'stopprice': '0', 'ordertype': '', 'side': 'SELL', 'status': 'FILLED', 'positionside': 'SHORT', 'createtime': 1678982402472, 'updatetime': 1678982402950, 'tradetype': 'usdt', 'selfid': 42004, 'filltrades': [TradeType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'tradeid': 1678982402950, 'clientorderid': '42004F1678982402837I0L57', 'price': '24880.6', 'quantity': '42.394', 'commission': '1054.7881564', 'commissionasset': 'USDT', 'tradetime': 1678982402950, 'tradetype': 'usdt', 'gatetype': 'simulator', 'handletime': 1678982402950}], 'gatetype': 'simulator', 'handletime': 0}
127.0.0.1 - - [17/Mar/2023 00:00:03] "POST / HTTP/1.1" 200 -
127.0.0.1 - - [17/Mar/2023 00:10:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=16041 

self.closeSec=1678982999, self.tradeDate='20230317', self.openTime='000000', self.closeTime='000959', self.symbol='BTCUSDT', self.open='24880.7', self.close='24808.9'
2023-03-17 00:10:01,779:INFO:pyemd2:main.py:125:handleKline:185189: self.closeSec=1678982999, self.tradeDate='20230317', self.openTime='000000', self.closeTime='000959',self.symbol='BTCUSDT',self.open='24880.7', self.close='24808.9'
2023-03-17 00:10:01,809:INFO:pyemd2:main.py:126:handleKline:185189: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
17420  20230316   232000    232959  1678980599  24786.8    24832
17421  20230316   233000    233959  1678981199  24832.1  24826.8
17422  20230316   234000    234959  1678981799  24826.8  24915.6
17423  20230316   235000    235959  1678982399  24912.1  24880.6
17424  20230317   000000    000959  1678982999  24880.7  24808.9
2023-03-17 00:10:01,809:INFO:pyemd2:main.py:127:handleKline:185189: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=16042 

self.closeSec=1678983599, self.tradeDate='20230317', self.openTime='001000', self.closeTime='001959', self.symbol='BTCUSDT', self.open='24808.8', self.close='24809.4'
127.0.0.1 - - [17/Mar/2023 00:20:04] "POST / HTTP/1.1" 200 -
2023-03-17 00:20:11,752:INFO:pyemd2:main.py:125:handleKline:185189: self.closeSec=1678983599, self.tradeDate='20230317', self.openTime='001000', self.closeTime='001959',self.symbol='BTCUSDT',self.open='24808.8', self.close='24809.4'
2023-03-17 00:20:11,902:INFO:pyemd2:main.py:126:handleKline:185189: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
17421  20230316   233000    233959  1678981199  24832.1  24826.8
17422  20230316   234000    234959  1678981799  24826.8  24915.6
17423  20230316   235000    235959  1678982399  24912.1  24880.6
17424  20230317   000000    000959  1678982999  24880.7  24808.9
17425  20230317   001000    001959  1678983599  24808.8  24809.4
2023-03-17 00:20:11,903:INFO:pyemd2:main.py:127:handleKline:185189: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}


## /root/FIL/strategy/similarity/log.txt ----- -----

127.0.0.1 - - [17/Mar/2023 00:00:03] "POST / HTTP/1.1" 200 -
2023-03-17 00:00:03,552:INFO:testStrategy:main.py:308:handleOrderFilled:185174: handleOrderFilled: data=OrderType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'clientorderid': '42006F1678982403170I0L2', 'symbol': 'BTCUSDT', 'gatewayorderid': 1678982403306514, 'quantity': '48.249', 'price': '24880.6', 'stopprice': '0', 'ordertype': '', 'side': 'SELL', 'status': 'FILLED', 'positionside': 'SHORT', 'createtime': 1678982402794, 'updatetime': 1678982403306, 'tradetype': 'usdt', 'selfid': 42006, 'filltrades': [TradeType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'tradeid': 1678982403306, 'clientorderid': '42006F1678982403170I0L2', 'price': '24880.6', 'quantity': '48.249', 'commission': '1200.4640694', 'commissionasset': 'USDT', 'tradetime': 1678982403306, 'tradetype': 'usdt', 'gatetype': 'simulator', 'handletime': 1678982403306}], 'gatetype': 'simulator', 'handletime': 0}
127.0.0.1 - - [17/Mar/2023 00:10:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=16041 

self.closeSec=1678982999, self.tradeDate='20230317', self.openTime='000000', self.closeTime='000959', self.symbol='BTCUSDT', self.open='24880.7', self.close='24808.9'
2023-03-17 00:10:01,733:INFO:testStrategy:main.py:101:handleKline:185174: self.closeSec=1678982999, self.tradeDate='20230317', self.openTime='000000', self.closeTime='000959',self.symbol='BTCUSDT',self.open='24880.7', self.close='24808.9'
2023-03-17 00:10:01,744:INFO:testStrategy:main.py:102:handleKline:185174: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
12236  20230316   232000    232959  1678980599  24786.8    24832
12237  20230316   233000    233959  1678981199  24832.1  24826.8
12238  20230316   234000    234959  1678981799  24826.8  24915.6
12239  20230316   235000    235959  1678982399  24912.1  24880.6
12240  20230317   000000    000959  1678982999  24880.7  24808.9
2023-03-17 00:10:01,744:INFO:testStrategy:main.py:103:handleKline:185174: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': True, 'isOpen': False, 'isClose': True, 'isTrig': False, 'isCorr': False}

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=16042 

self.closeSec=1678983599, self.tradeDate='20230317', self.openTime='001000', self.closeTime='001959', self.symbol='BTCUSDT', self.open='24808.8', self.close='24809.4'
127.0.0.1 - - [17/Mar/2023 00:20:04] "POST / HTTP/1.1" 200 -
2023-03-17 00:20:11,068:INFO:testStrategy:main.py:101:handleKline:185174: self.closeSec=1678983599, self.tradeDate='20230317', self.openTime='001000', self.closeTime='001959',self.symbol='BTCUSDT',self.open='24808.8', self.close='24809.4'
2023-03-17 00:20:11,495:INFO:testStrategy:main.py:102:handleKline:185174: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
12237  20230316   233000    233959  1678981199  24832.1  24826.8
12238  20230316   234000    234959  1678981799  24826.8  24915.6
12239  20230316   235000    235959  1678982399  24912.1  24880.6
12240  20230317   000000    000959  1678982999  24880.7  24808.9
12241  20230317   001000    001959  1678983599  24808.8  24809.4
2023-03-17 00:20:11,496:INFO:testStrategy:main.py:103:handleKline:185174: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': True, 'isOpen': False, 'isClose': True, 'isTrig': False, 'isCorr': False}


## /root/FIL/strategy/sr_min/log.txt ----- -----

--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=0, self.total=1000000.0, self.flagDict['side']='', self.tradeCount=0, self.count=27514
self.closeSec=1678983599, self.tradeDate='20230317', self.openTime='001500', self.closeTime='001959', self.symbol='BTCUSDT', self.open=24806.4, self.close=24809.4, self.high=24815.0, self.low=24782.5, self.vol=1419.08, self.amt=35193292.1297 
127.0.0.1 - - [17/Mar/2023 00:20:03] "POST / HTTP/1.1" 200 -
2023-03-17 00:20:08,566:INFO:sr_min:main.py:172:handleKline:449472: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5759  20230316   235500    235959  ...         0.0        0.0       0
5760  20230317   000000    000459  ...         0.0        0.0       0
5761  20230317   000500    000959  ...         0.0        0.0       0
5762  20230317   001000    001459  ...         0.0        0.0       0
5763  20230317   001500    001959  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-03-17 00:20:08,616:INFO:sr_min:main.py:175:handleKline:449472: self.closeSec=1678983599, self.tradeDate='20230317', self.openTime='001500', self.closeTime='001959',self.symbol='BTCUSDT',self.open=24806.4, self.close=24809.4, self.high=24815.0, self.low=24782.5, self.vol=1419.08, self.amt=35193292.1297, ukdf['pct'].iloc[-1]=0.000125 , ukdf['amount'].iloc[-1]=35193292.1297, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5763, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': []}
type(curSign)=<class 'int'>, curSign=0, self.sign=0
127.0.0.1 - - [17/Mar/2023 00:25:01] "POST / HTTP/1.1" 200 -
--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=0, self.total=1000000.0, self.flagDict['side']='', self.tradeCount=0, self.count=27515
self.closeSec=1678983899, self.tradeDate='20230317', self.openTime='002000', self.closeTime='002459', self.symbol='BTCUSDT', self.open=24809.4, self.close=24778.6, self.high=24811.0, self.low=24726.5, self.vol=2388.372, self.amt=59149743.8017 
2023-03-17 00:25:01,642:INFO:sr_min:main.py:172:handleKline:449472: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5760  20230317   000000    000459  ...         0.0        0.0       0
5761  20230317   000500    000959  ...         0.0        0.0       0
5762  20230317   001000    001459  ...         0.0        0.0       0
5763  20230317   001500    001959  ...         0.0        0.0       0
5764  20230317   002000    002459  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-03-17 00:25:01,643:INFO:sr_min:main.py:175:handleKline:449472: self.closeSec=1678983899, self.tradeDate='20230317', self.openTime='002000', self.closeTime='002459',self.symbol='BTCUSDT',self.open=24809.4, self.close=24778.6, self.high=24811.0, self.low=24726.5, self.vol=2388.372, self.amt=59149743.8017, ukdf['pct'].iloc[-1]=-0.001241 , ukdf['amount'].iloc[-1]=59149743.8017, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5764, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': []}
type(curSign)=<class 'int'>, curSign=0, self.sign=0


## /root/FIL/strategy/s_rsrs/log.txt ----- -----

723  20230316   120000    155959  1678953599  ...    723  0.936352  0.935144     1.0
724  20230316   160000    195959  1678967999  ...    724  0.861833  0.712518     1.0

[5 rows x 15 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '55.825', 'enterprice': '20070', 'countrevence': '0', 'unrealprofit': '265431.1275', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '24824.7', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'numpy.int64'>, curSign=1, self.sign=1
--handleKline--:  version='2.0.0', self.name='s_rsrs', self.symbol='BTCUSDT', interval='4h', intervalSec=14400, wid=25, thd=0.6, self.sign=1, self.total=1119287.34225, self.flagDict['side']='buy', self.tradeCount=24, self.count=668
self.closeSec=1678982399, self.tradeDate='20230316', self.openTime='200000', self.closeTime='235959', self.symbol='BTCUSDT', self.open=24821.4, self.close=24880.6, self.high=25030.0, self.low=24516.0, self.vol=182794.492, self.amt=4529335417.62231 
127.0.0.1 - - [17/Mar/2023 00:00:02] "POST / HTTP/1.1" 200 -
2023-03-17 00:00:02,108:INFO:s_rsrs:main.py:141:handleKline:185271: self.closeSec=1678982399, self.tradeDate='20230316', self.openTime='200000', self.closeTime='235959',self.symbol='BTCUSDT',self.open=24821.4, self.close=24880.6, self.high=25030.0, self.low=24516.0, self.vol=182794.492, self.amt=4529335417.62231 
2023-03-17 00:00:02,183:INFO:s_rsrs:main.py:142:handleKline:185271: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime  ...         vol           amt       pct
721  20230316   040000    075959  ...   78584.034  1.916961e+09 -0.003765
722  20230316   080000    115959  ...   68553.169  1.664733e+09 -0.000663
723  20230316   120000    155959  ...   88010.463  2.152492e+09  0.014115
724  20230316   160000    195959  ...  175784.630  4.349630e+09  0.008406
725  20230316   200000    235959  ...  182794.492  4.529335e+09  0.002385

[5 rows x 11 columns]
2023-03-17 00:00:05,452:INFO:s_rsrs:main.py:151:handleKline:185271: df_s.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec  ...  index      beta    zscore  signal
721  20230316   040000    075959  1678924799  ...    721  1.054196  1.316485     1.0
722  20230316   080000    115959  1678939199  ...    722  0.999147  1.132247     1.0
723  20230316   120000    155959  1678953599  ...    723  0.936352  0.935144     1.0
724  20230316   160000    195959  1678967999  ...    724  0.861833  0.712518     1.0
725  20230316   200000    235959  1678982399  ...    725  0.754877  0.400662     NaN

[5 rows x 15 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '55.825', 'enterprice': '20070', 'countrevence': '0', 'unrealprofit': '268551.745', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '24880.6', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'numpy.int64'>, curSign=-9223372036854775808, self.sign=1


