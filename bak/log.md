# 20230404 00:26:02

## /root/FIL/strategy/amihud/log.txt ----- -----

--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=993672.4896432, self.flagDict['side']='sell', self.tradeCount=2, self.count=36700
self.closeSec=1680538799, self.tradeDate='20230404', self.openTime='001500', self.closeTime='001959', self.symbol='BTCUSDT', self.open=28081.9, self.close=28078.9, self.high=28088.6, self.low=28057.0, self.vol=951.772, self.amt=26718152.3293 
127.0.0.1 - - [04/Apr/2023 00:20:04] "POST / HTTP/1.1" 200 -
2023-04-04 00:20:09,356:INFO:amihud:main.py:172:handleKline:200676: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5759  20230403   235500    235959  ...         0.0        0.0       0
5760  20230404   000000    000459  ...         0.0        0.0       0
5761  20230404   000500    000959  ...         0.0        0.0       0
5762  20230404   001000    001459  ...         0.0        0.0       0
5763  20230404   001500    001959  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-04-04 00:20:09,377:INFO:amihud:main.py:175:handleKline:200676: self.closeSec=1680538799, self.tradeDate='20230404', self.openTime='001500', self.closeTime='001959',self.symbol='BTCUSDT',self.open=28081.9, self.close=28078.9, self.high=28088.6, self.low=28057.0, self.vol=951.772, self.amt=26718152.3293, ukdf['pct'].iloc[-1]=-0.000107 , ukdf['amount'].iloc[-1]=26718152.3293, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5763, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '60.176', 'enterprice': '16529.3', 'countrevence': '0', 'unrealprofit': '-695436.64853885152', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '28086.01112302', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1
127.0.0.1 - - [04/Apr/2023 00:25:01] "POST / HTTP/1.1" 200 -
--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=993672.4896432, self.flagDict['side']='sell', self.tradeCount=2, self.count=36701
self.closeSec=1680539099, self.tradeDate='20230404', self.openTime='002000', self.closeTime='002459', self.symbol='BTCUSDT', self.open=28079.0, self.close=28043.4, self.high=28090.0, self.low=28041.2, self.vol=1804.476, self.amt=50637807.4031 
2023-04-04 00:25:01,592:INFO:amihud:main.py:172:handleKline:200676: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5760  20230404   000000    000459  ...         0.0        0.0       0
5761  20230404   000500    000959  ...         0.0        0.0       0
5762  20230404   001000    001459  ...         0.0        0.0       0
5763  20230404   001500    001959  ...         0.0        0.0       0
5764  20230404   002000    002459  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-04-04 00:25:01,592:INFO:amihud:main.py:175:handleKline:200676: self.closeSec=1680539099, self.tradeDate='20230404', self.openTime='002000', self.closeTime='002459',self.symbol='BTCUSDT',self.open=28079.0, self.close=28043.4, self.high=28090.0, self.low=28041.2, self.vol=1804.476, self.amt=50637807.4031, ukdf['pct'].iloc[-1]=-0.001264 , ukdf['amount'].iloc[-1]=50637807.4031, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5764, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '60.176', 'enterprice': '16529.3', 'countrevence': '0', 'unrealprofit': '-692945.8237266824', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '28044.61879365', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1


## /root/FIL/strategy/factorcheck/log.txt ----- -----


self.closeSec=1680538799, self.tradeDate='20230404', self.openTime='001500', self.closeTime='001959', self.symbol='BTCUSDT', self.open=28081.9, self.close=28078.9, self.high=28088.6, self.low=28057.0 
127.0.0.1 - - [04/Apr/2023 00:20:03] "POST / HTTP/1.1" 200 -
2023-04-04 00:20:06,497:INFO:factorcheck2:main.py:126:handleKline:185239: self.closeSec=1680538799, self.tradeDate='20230404', self.openTime='001500', self.closeTime='001959',self.symbol='BTCUSDT',self.open=28081.9, self.close=28078.9, self.high=28088.6, self.low=28057.0   
2023-04-04 00:20:07,658:INFO:factorcheck2:main.py:127:handleKline:185239: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime    closeSec  ...      low       pct  index  idx
1439  20230403   235500    235959  1680537599  ...  27980.1  0.001161   1727    5
1440  20230404   000000    000459  1680537899  ...  28017.7  0.000389   1440    0
1441  20230404   000500    000959  1680538199  ...  28034.0  0.001886   1441    1
1442  20230404   001000    001459  1680538499  ...  28068.8 -0.000513   1442    2
1443  20230404   001500    001959  1680538799  ...  28057.0 -0.000107   1443    3

[5 rows x 11 columns]
2023-04-04 00:20:07,667:INFO:factorcheck2:main.py:128:handleKline:185239: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': True, 'isOpenSell': False, 'isCloseBuy': False, 'isCloseSell': False, 'isOpen': True, 'isClose': False, 'isTrig': True}

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=10, self.factor=0.5548546794466533, self.count=37267 

self.closeSec=1680539099, self.tradeDate='20230404', self.openTime='002000', self.closeTime='002459', self.symbol='BTCUSDT', self.open=28079.0, self.close=28043.4, self.high=28090.0, self.low=28041.2 
127.0.0.1 - - [04/Apr/2023 00:25:01] "POST / HTTP/1.1" 200 -
2023-04-04 00:25:01,513:INFO:factorcheck2:main.py:126:handleKline:185239: self.closeSec=1680539099, self.tradeDate='20230404', self.openTime='002000', self.closeTime='002459',self.symbol='BTCUSDT',self.open=28079.0, self.close=28043.4, self.high=28090.0, self.low=28041.2   
2023-04-04 00:25:01,556:INFO:factorcheck2:main.py:127:handleKline:185239: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime    closeSec  ...      low       pct  index  idx
1440  20230404   000000    000459  1680537899  ...  28017.7  0.000389   1440    0
1441  20230404   000500    000959  1680538199  ...  28034.0  0.001886   1441    1
1442  20230404   001000    001459  1680538499  ...  28068.8 -0.000513   1442    2
1443  20230404   001500    001959  1680538799  ...  28057.0 -0.000107   1443    3
1444  20230404   002000    002459  1680539099  ...  28041.2 -0.001264   1444    4

[5 rows x 11 columns]
2023-04-04 00:25:01,556:INFO:factorcheck2:main.py:128:handleKline:185239: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': True, 'isOpenSell': False, 'isCloseBuy': False, 'isCloseSell': False, 'isOpen': True, 'isClose': False, 'isTrig': True}


## /root/FIL/strategy/logic/log.txt ----- -----

2023-04-04 00:00:34,361:DEBUG:logic:main.py:463:getModel:885513: df_s.iloc[-5:,:] :
          date closeTime     open  ...    alpha58   alpha67   alpha72
5802  20230403    212959  28150.0  ...  52.083333  0.506746  0.469877
5803  20230403    215959  28204.1  ...  52.083333  0.514144  0.458270
5804  20230403    222959  28247.9  ...  52.083333  0.510948  0.448645
5805  20230403    225959  28230.0  ...  52.083333  0.469754  0.456368
5806  20230403    232959  27982.7  ...  52.083333  0.482584  0.458541

[5 rows x 33 columns]
0.5551470588235294
acc is : 0.5551470588235294
2023-04-04 00:00:34,522:INFO:logic:main.py:468:getModel:885513: df_pred.iloc[-5:,:] :
     pred    prob_0    prob_1  actual  ...       nav  sign  cost_        bm
539     0  0.522668  0.477332       1  ...  0.860993   1.0    0.0  1.022867
540     0  0.524051  0.475949       0  ...  0.860448   1.0    0.0  1.022219
541     0  0.513018  0.486982       0  ...  0.852904   1.0    0.0  1.013257
542     1  0.463788  0.536212       1  ...  0.855178   1.0    0.0  1.015958
543     0  0.524713  0.475287       0  ...  0.854428   1.0    0.0  1.015067

[5 rows x 10 columns]
2023-04-04 00:00:34,556:INFO:logic:main.py:478:getModel:885513: df_panel.iloc[-5:,:] :
    pred    prob_0    prob_1  actual  ...       nav  sign  cost_        bm
45     0  0.523052  0.476948       1  ...  0.860993   1.0    0.0  1.022352
46     0  0.524067  0.475933       0  ...  0.860448   1.0    0.0  1.021608
47     0  0.513452  0.486548       0  ...  0.852904   1.0    0.0  1.012652
48     1  0.464639  0.535361       1  ...  0.855178   1.0    0.0  1.017446
49     0  0.524713  0.475287       0  ...  0.854428   1.0    0.0  1.015067

[5 rows x 10 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': []}


## /root/FIL/strategy/modifiedmom/log.txt ----- -----

2023-04-04 00:00:03,055:INFO:modifiedmom:main.py:319:handleOrderFilled:185213: handleOrderFilled: data=OrderType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'clientorderid': '42108F1680537602607I0L59', 'symbol': 'BTCUSDT', 'gatewayorderid': 1680537602709577, 'quantity': '25.55', 'price': '28034.2', 'stopprice': '0', 'ordertype': '', 'side': 'BUY', 'status': 'FILLED', 'positionside': 'LONG', 'createtime': 1680537602162, 'updatetime': 1680537602709, 'tradetype': 'usdt', 'selfid': 42108, 'filltrades': [TradeType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'tradeid': 1680537602709, 'clientorderid': '42108F1680537602607I0L59', 'price': '28034.2', 'quantity': '25.55', 'commission': '716.27381', 'commissionasset': 'USDT', 'tradetime': 1680537602709, 'tradetype': 'usdt', 'gatetype': 'simulator', 'handletime': 1680537602709}], 'gatetype': 'simulator', 'handletime': 0}
127.0.0.1 - - [04/Apr/2023 00:00:03] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=18632 

self.closeSec=1680538199, self.tradeDate='20230404', self.openTime='000000', self.closeTime='000959', self.symbol='BTCUSDT', self.open='28034.1', self.close='28096.3'
2023-04-04 00:10:01,572:INFO:modifiedmom:main.py:144:handleKline:185213: self.closeSec=1680538199, self.tradeDate='20230404', self.openTime='000000', self.closeTime='000959',self.symbol='BTCUSDT',self.open='28034.1', self.close='28096.3'
127.0.0.1 - - [04/Apr/2023 00:10:01] "POST / HTTP/1.1" 200 -
2023-04-04 00:10:01,593:INFO:modifiedmom:main.py:145:handleKline:185213: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec     open    close       pct
572  20230403   232000    232959  1680535799  28014.3  28057.1  0.001528
573  20230403   233000    233959  1680536399  28057.1  28059.2  0.000075
574  20230403   234000    234959  1680536999  28059.2  28051.9 -0.000260
575  20230403   235000    235959  1680537599    28052  28032.5 -0.000692
576  20230404   000000    000959  1680538199  28034.1  28096.3  0.002276
2023-04-04 00:10:01,593:INFO:modifiedmom:main.py:146:handleKline:185213: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': True, 'isOpen': False, 'isClose': True, 'isTrig': False}

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=18633 

self.closeSec=1680538799, self.tradeDate='20230404', self.openTime='001000', self.closeTime='001959', self.symbol='BTCUSDT', self.open='28096.3', self.close='28078.9'
127.0.0.1 - - [04/Apr/2023 00:20:04] "POST / HTTP/1.1" 200 -
2023-04-04 00:20:07,858:INFO:modifiedmom:main.py:144:handleKline:185213: self.closeSec=1680538799, self.tradeDate='20230404', self.openTime='001000', self.closeTime='001959',self.symbol='BTCUSDT',self.open='28096.3', self.close='28078.9'
2023-04-04 00:20:08,687:INFO:modifiedmom:main.py:145:handleKline:185213: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec     open    close       pct
573  20230403   233000    233959  1680536399  28057.1  28059.2  0.000075
574  20230403   234000    234959  1680536999  28059.2  28051.9 -0.000260
575  20230403   235000    235959  1680537599    28052  28032.5 -0.000692
576  20230404   000000    000959  1680538199  28034.1  28096.3  0.002276
577  20230404   001000    001959  1680538799  28096.3  28078.9 -0.000619
2023-04-04 00:20:08,697:INFO:modifiedmom:main.py:146:handleKline:185213: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': True, 'isOpen': False, 'isClose': True, 'isTrig': False}


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

127.0.0.1 - - [04/Apr/2023 00:00:03] "POST / HTTP/1.1" 200 -
2023-04-04 00:00:03,315:INFO:pyemd2:main.py:303:handleOrderFilled:185189: handleOrderFilled: data=OrderType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'clientorderid': '42109F1680537602629I0L57', 'symbol': 'BTCUSDT', 'gatewayorderid': 1680537602732432, 'quantity': '35.142', 'price': '28034.1', 'stopprice': '0', 'ordertype': '', 'side': 'SELL', 'status': 'FILLED', 'positionside': 'SHORT', 'createtime': 1680537602105, 'updatetime': 1680537602732, 'tradetype': 'usdt', 'selfid': 42109, 'filltrades': [TradeType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'tradeid': 1680537602732, 'clientorderid': '42109F1680537602629I0L57', 'price': '28034.1', 'quantity': '35.142', 'commission': '985.1743422', 'commissionasset': 'USDT', 'tradetime': 1680537602732, 'tradetype': 'usdt', 'gatetype': 'simulator', 'handletime': 1680537602732}], 'gatetype': 'simulator', 'handletime': 0}

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=18633 

self.closeSec=1680538199, self.tradeDate='20230404', self.openTime='000000', self.closeTime='000959', self.symbol='BTCUSDT', self.open='28034.1', self.close='28096.3'
2023-04-04 00:10:01,586:INFO:pyemd2:main.py:125:handleKline:185189: self.closeSec=1680538199, self.tradeDate='20230404', self.openTime='000000', self.closeTime='000959',self.symbol='BTCUSDT',self.open='28034.1', self.close='28096.3'
127.0.0.1 - - [04/Apr/2023 00:10:01] "POST / HTTP/1.1" 200 -
2023-04-04 00:10:01,609:INFO:pyemd2:main.py:126:handleKline:185189: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
17420  20230403   232000    232959  1680535799  28014.3  28057.1
17421  20230403   233000    233959  1680536399  28057.1  28059.2
17422  20230403   234000    234959  1680536999  28059.2  28051.9
17423  20230403   235000    235959  1680537599    28052  28032.5
17424  20230404   000000    000959  1680538199  28034.1  28096.3
2023-04-04 00:10:01,609:INFO:pyemd2:main.py:127:handleKline:185189: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=18634 

self.closeSec=1680538799, self.tradeDate='20230404', self.openTime='001000', self.closeTime='001959', self.symbol='BTCUSDT', self.open='28096.3', self.close='28078.9'
127.0.0.1 - - [04/Apr/2023 00:20:05] "POST / HTTP/1.1" 200 -
2023-04-04 00:20:11,171:INFO:pyemd2:main.py:125:handleKline:185189: self.closeSec=1680538799, self.tradeDate='20230404', self.openTime='001000', self.closeTime='001959',self.symbol='BTCUSDT',self.open='28096.3', self.close='28078.9'
2023-04-04 00:20:11,302:INFO:pyemd2:main.py:126:handleKline:185189: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
17421  20230403   233000    233959  1680536399  28057.1  28059.2
17422  20230403   234000    234959  1680536999  28059.2  28051.9
17423  20230403   235000    235959  1680537599    28052  28032.5
17424  20230404   000000    000959  1680538199  28034.1  28096.3
17425  20230404   001000    001959  1680538799  28096.3  28078.9
2023-04-04 00:20:11,302:INFO:pyemd2:main.py:127:handleKline:185189: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}


## /root/FIL/strategy/similarity/log.txt ----- -----

127.0.0.1 - - [04/Apr/2023 00:00:03] "POST / HTTP/1.1" 200 -
2023-04-04 00:00:03,546:INFO:testStrategy:main.py:308:handleOrderFilled:185174: handleOrderFilled: data=OrderType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'clientorderid': '42110F1680537602721I0L2', 'symbol': 'BTCUSDT', 'gatewayorderid': 1680537603087551, 'quantity': '46.185', 'price': '28034.1', 'stopprice': '0', 'ordertype': '', 'side': 'SELL', 'status': 'FILLED', 'positionside': 'SHORT', 'createtime': 1680537602319, 'updatetime': 1680537603087, 'tradetype': 'usdt', 'selfid': 42110, 'filltrades': [TradeType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'tradeid': 1680537603087, 'clientorderid': '42110F1680537602721I0L2', 'price': '28034.1', 'quantity': '46.185', 'commission': '1294.7549085', 'commissionasset': 'USDT', 'tradetime': 1680537603087, 'tradetype': 'usdt', 'gatetype': 'simulator', 'handletime': 1680537603087}], 'gatetype': 'simulator', 'handletime': 0}

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=18633 

self.closeSec=1680538199, self.tradeDate='20230404', self.openTime='000000', self.closeTime='000959', self.symbol='BTCUSDT', self.open='28034.1', self.close='28096.3'
127.0.0.1 - - [04/Apr/2023 00:10:01] "POST / HTTP/1.1" 200 -
2023-04-04 00:10:01,639:INFO:testStrategy:main.py:101:handleKline:185174: self.closeSec=1680538199, self.tradeDate='20230404', self.openTime='000000', self.closeTime='000959',self.symbol='BTCUSDT',self.open='28034.1', self.close='28096.3'
2023-04-04 00:10:01,675:INFO:testStrategy:main.py:102:handleKline:185174: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
12236  20230403   232000    232959  1680535799  28014.3  28057.1
12237  20230403   233000    233959  1680536399  28057.1  28059.2
12238  20230403   234000    234959  1680536999  28059.2  28051.9
12239  20230403   235000    235959  1680537599    28052  28032.5
12240  20230404   000000    000959  1680538199  28034.1  28096.3
2023-04-04 00:10:01,675:INFO:testStrategy:main.py:103:handleKline:185174: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': True, 'isOpen': False, 'isClose': True, 'isTrig': False, 'isCorr': False}

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=18634 

self.closeSec=1680538799, self.tradeDate='20230404', self.openTime='001000', self.closeTime='001959', self.symbol='BTCUSDT', self.open='28096.3', self.close='28078.9'
127.0.0.1 - - [04/Apr/2023 00:20:05] "POST / HTTP/1.1" 200 -
2023-04-04 00:20:10,668:INFO:testStrategy:main.py:101:handleKline:185174: self.closeSec=1680538799, self.tradeDate='20230404', self.openTime='001000', self.closeTime='001959',self.symbol='BTCUSDT',self.open='28096.3', self.close='28078.9'
2023-04-04 00:20:10,971:INFO:testStrategy:main.py:102:handleKline:185174: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
12237  20230403   233000    233959  1680536399  28057.1  28059.2
12238  20230403   234000    234959  1680536999  28059.2  28051.9
12239  20230403   235000    235959  1680537599    28052  28032.5
12240  20230404   000000    000959  1680538199  28034.1  28096.3
12241  20230404   001000    001959  1680538799  28096.3  28078.9
2023-04-04 00:20:10,976:INFO:testStrategy:main.py:103:handleKline:185174: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': True, 'isOpen': False, 'isClose': True, 'isTrig': False, 'isCorr': False}


## /root/FIL/strategy/sr_min/log.txt ----- -----

--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=0, self.total=1000000.0, self.flagDict['side']='', self.tradeCount=0, self.count=32698
self.closeSec=1680538799, self.tradeDate='20230404', self.openTime='001500', self.closeTime='001959', self.symbol='BTCUSDT', self.open=28081.9, self.close=28078.9, self.high=28088.6, self.low=28057.0, self.vol=951.772, self.amt=26718152.3293 
127.0.0.1 - - [04/Apr/2023 00:20:03] "POST / HTTP/1.1" 200 -
2023-04-04 00:20:08,337:INFO:sr_min:main.py:172:handleKline:449472: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5759  20230403   235500    235959  ...         0.0        0.0       0
5760  20230404   000000    000459  ...         0.0        0.0       0
5761  20230404   000500    000959  ...         0.0        0.0       0
5762  20230404   001000    001459  ...         0.0        0.0       0
5763  20230404   001500    001959  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-04-04 00:20:08,368:INFO:sr_min:main.py:175:handleKline:449472: self.closeSec=1680538799, self.tradeDate='20230404', self.openTime='001500', self.closeTime='001959',self.symbol='BTCUSDT',self.open=28081.9, self.close=28078.9, self.high=28088.6, self.low=28057.0, self.vol=951.772, self.amt=26718152.3293, ukdf['pct'].iloc[-1]=-0.000107 , ukdf['amount'].iloc[-1]=26718152.3293, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5763, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': []}
type(curSign)=<class 'int'>, curSign=0, self.sign=0
127.0.0.1 - - [04/Apr/2023 00:25:01] "POST / HTTP/1.1" 200 -
--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=0, self.total=1000000.0, self.flagDict['side']='', self.tradeCount=0, self.count=32699
self.closeSec=1680539099, self.tradeDate='20230404', self.openTime='002000', self.closeTime='002459', self.symbol='BTCUSDT', self.open=28079.0, self.close=28043.4, self.high=28090.0, self.low=28041.2, self.vol=1804.476, self.amt=50637807.4031 
2023-04-04 00:25:01,607:INFO:sr_min:main.py:172:handleKline:449472: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5760  20230404   000000    000459  ...         0.0        0.0       0
5761  20230404   000500    000959  ...         0.0        0.0       0
5762  20230404   001000    001459  ...         0.0        0.0       0
5763  20230404   001500    001959  ...         0.0        0.0       0
5764  20230404   002000    002459  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-04-04 00:25:01,607:INFO:sr_min:main.py:175:handleKline:449472: self.closeSec=1680539099, self.tradeDate='20230404', self.openTime='002000', self.closeTime='002459',self.symbol='BTCUSDT',self.open=28079.0, self.close=28043.4, self.high=28090.0, self.low=28041.2, self.vol=1804.476, self.amt=50637807.4031, ukdf['pct'].iloc[-1]=-0.001264 , ukdf['amount'].iloc[-1]=50637807.4031, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5764, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': []}
type(curSign)=<class 'int'>, curSign=0, self.sign=0


## /root/FIL/strategy/s_rsrs/log.txt ----- -----

723  20230403   120000    155959  1680508799  ...    723  0.249354 -0.352679     NaN
724  20230403   160000    195959  1680523199  ...    724  0.214565 -0.443444     NaN

[5 rows x 15 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '52.088', 'enterprice': '28398.8', 'countrevence': '0', 'unrealprofit': '8068.4312', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '28243.9', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'numpy.int64'>, curSign=-9223372036854775808, self.sign=-1
127.0.0.1 - - [04/Apr/2023 00:00:01] "POST / HTTP/1.1" 200 -
--handleKline--:  version='2.0.0', self.name='s_rsrs', self.symbol='BTCUSDT', interval='4h', intervalSec=14400, wid=25, thd=0.6, self.sign=-1, self.total=1477757.4577056, self.flagDict['side']='sell', self.tradeCount=29, self.count=776
self.closeSec=1680537599, self.tradeDate='20230403', self.openTime='200000', self.closeTime='235959', self.symbol='BTCUSDT', self.open=28243.3, self.close=28032.5, self.high=28370.0, self.low=27933.0, self.vol=141711.342, self.amt=3985695604.78644 
2023-04-04 00:00:01,794:INFO:s_rsrs:main.py:141:handleKline:185271: self.closeSec=1680537599, self.tradeDate='20230403', self.openTime='200000', self.closeTime='235959',self.symbol='BTCUSDT',self.open=28243.3, self.close=28032.5, self.high=28370.0, self.low=27933.0, self.vol=141711.342, self.amt=3985695604.78644 
2023-04-04 00:00:01,852:INFO:s_rsrs:main.py:142:handleKline:185271: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime  ...         vol           amt       pct
721  20230403   040000    075959  ...   59221.178  1.659291e+09  0.008144
722  20230403   080000    115959  ...   92246.758  2.562180e+09 -0.015024
723  20230403   120000    155959  ...   59552.703  1.652843e+09  0.007510
724  20230403   160000    195959  ...  169914.981  4.806848e+09  0.010627
725  20230403   200000    235959  ...  141711.342  3.985696e+09 -0.007467

[5 rows x 11 columns]
2023-04-04 00:00:04,432:INFO:s_rsrs:main.py:151:handleKline:185271: df_s.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec  ...  index      beta    zscore  signal
721  20230403   040000    075959  1680479999  ...    721  0.119203 -0.783243    -1.0
722  20230403   080000    115959  1680494399  ...    722  0.133327 -0.724516    -1.0
723  20230403   120000    155959  1680508799  ...    723  0.249354 -0.352679     NaN
724  20230403   160000    195959  1680523199  ...    724  0.214565 -0.443444     NaN
725  20230403   200000    235959  1680537599  ...    725  0.195187 -0.487681     NaN

[5 rows x 15 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '52.088', 'enterprice': '28398.8', 'countrevence': '0', 'unrealprofit': '18688.04127921064', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '28040.02175397', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'numpy.int64'>, curSign=-9223372036854775808, self.sign=-1


