# 20230405 00:26:02

## /root/FIL/strategy/amihud/log.txt ----- -----

--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=993672.4896432, self.flagDict['side']='sell', self.tradeCount=2, self.count=36988
self.closeSec=1680625199, self.tradeDate='20230405', self.openTime='001500', self.closeTime='001959', self.symbol='BTCUSDT', self.open=27986.3, self.close=28000.1, self.high=28017.7, self.low=27982.0, self.vol=1365.972, self.amt=38251017.0435 
127.0.0.1 - - [05/Apr/2023 00:20:02] "POST / HTTP/1.1" 200 -
2023-04-05 00:20:07,951:INFO:amihud:main.py:172:handleKline:200676: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5759  20230404   235500    235959  ...         0.0        0.0       0
5760  20230405   000000    000459  ...         0.0        0.0       0
5761  20230405   000500    000959  ...         0.0        0.0       0
5762  20230405   001000    001459  ...         0.0        0.0       0
5763  20230405   001500    001959  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-04-05 00:20:07,991:INFO:amihud:main.py:175:handleKline:200676: self.closeSec=1680625199, self.tradeDate='20230405', self.openTime='001500', self.closeTime='001959',self.symbol='BTCUSDT',self.open=27986.3, self.close=28000.1, self.high=28017.7, self.low=27982.0, self.vol=1365.972, self.amt=38251017.0435, ukdf['pct'].iloc[-1]=0.000493 , ukdf['amount'].iloc[-1]=38251017.0435, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5763, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '60.176', 'enterprice': '16529.3', 'countrevence': '0', 'unrealprofit': '-689817.97100294592', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '27992.64038492', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1
--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=993672.4896432, self.flagDict['side']='sell', self.tradeCount=2, self.count=36989
self.closeSec=1680625499, self.tradeDate='20230405', self.openTime='002000', self.closeTime='002459', self.symbol='BTCUSDT', self.open=28000.0, self.close=28024.4, self.high=28024.4, self.low=27964.1, self.vol=1068.719, self.amt=29915807.9877 
127.0.0.1 - - [05/Apr/2023 00:25:01] "POST / HTTP/1.1" 200 -
2023-04-05 00:25:01,936:INFO:amihud:main.py:172:handleKline:200676: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5760  20230405   000000    000459  ...         0.0        0.0       0
5761  20230405   000500    000959  ...         0.0        0.0       0
5762  20230405   001000    001459  ...         0.0        0.0       0
5763  20230405   001500    001959  ...         0.0        0.0       0
5764  20230405   002000    002459  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-04-05 00:25:01,937:INFO:amihud:main.py:175:handleKline:200676: self.closeSec=1680625499, self.tradeDate='20230405', self.openTime='002000', self.closeTime='002459',self.symbol='BTCUSDT',self.open=28000.0, self.close=28024.4, self.high=28024.4, self.low=27964.1, self.vol=1068.719, self.amt=29915807.9877, ukdf['pct'].iloc[-1]=0.000868 , ukdf['amount'].iloc[-1]=29915807.9877, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5764, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '60.176', 'enterprice': '16529.3', 'countrevence': '0', 'unrealprofit': '-691939.7536', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '28027.9', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1


## /root/FIL/strategy/factorcheck/log.txt ----- -----


self.closeSec=1680625199, self.tradeDate='20230405', self.openTime='001500', self.closeTime='001959', self.symbol='BTCUSDT', self.open=27986.3, self.close=28000.1, self.high=28017.7, self.low=27982.0 
127.0.0.1 - - [05/Apr/2023 00:20:02] "POST / HTTP/1.1" 200 -
2023-04-05 00:20:04,201:INFO:factorcheck2:main.py:126:handleKline:185239: self.closeSec=1680625199, self.tradeDate='20230405', self.openTime='001500', self.closeTime='001959',self.symbol='BTCUSDT',self.open=27986.3, self.close=28000.1, self.high=28017.7, self.low=27982.0   
2023-04-05 00:20:05,551:INFO:factorcheck2:main.py:127:handleKline:185239: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime    closeSec  ...      low       pct  index  idx
1439  20230404   235500    235959  1680623999  ...  28000.0 -0.000496   1727    5
1440  20230405   000000    000459  1680624299  ...  27971.0 -0.001449   1440    0
1441  20230405   000500    000959  1680624599  ...  27952.8 -0.000179   1441    1
1442  20230405   001000    001459  1680624899  ...  27963.1  0.000722   1442    2
1443  20230405   001500    001959  1680625199  ...  27982.0  0.000493   1443    3

[5 rows x 11 columns]
2023-04-05 00:20:05,551:INFO:factorcheck2:main.py:128:handleKline:185239: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=9, self.factor=0.42523667739784266, self.count=37555 

self.closeSec=1680625499, self.tradeDate='20230405', self.openTime='002000', self.closeTime='002459', self.symbol='BTCUSDT', self.open=28000.0, self.close=28024.4, self.high=28024.4, self.low=27964.1 
127.0.0.1 - - [05/Apr/2023 00:25:01] "POST / HTTP/1.1" 200 -
2023-04-05 00:25:01,866:INFO:factorcheck2:main.py:126:handleKline:185239: self.closeSec=1680625499, self.tradeDate='20230405', self.openTime='002000', self.closeTime='002459',self.symbol='BTCUSDT',self.open=28000.0, self.close=28024.4, self.high=28024.4, self.low=27964.1   
2023-04-05 00:25:01,882:INFO:factorcheck2:main.py:127:handleKline:185239: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime    closeSec  ...      low       pct  index  idx
1440  20230405   000000    000459  1680624299  ...  27971.0 -0.001449   1440    0
1441  20230405   000500    000959  1680624599  ...  27952.8 -0.000179   1441    1
1442  20230405   001000    001459  1680624899  ...  27963.1  0.000722   1442    2
1443  20230405   001500    001959  1680625199  ...  27982.0  0.000493   1443    3
1444  20230405   002000    002459  1680625499  ...  27964.1  0.000868   1444    4

[5 rows x 11 columns]
2023-04-05 00:25:01,882:INFO:factorcheck2:main.py:128:handleKline:185239: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}


## /root/FIL/strategy/logic/log.txt ----- -----

2023-04-05 00:00:34,417:DEBUG:logic:main.py:463:getModel:885513: df_s.iloc[-5:,:] :
          date closeTime     open  ...    alpha58   alpha67   alpha72
5802  20230404    212959  28252.9  ...  50.000000  0.531066  0.304787
5803  20230404    215959  28253.5  ...  50.000000  0.506096  0.302630
5804  20230404    222959  28100.1  ...  50.416667  0.512790  0.298337
5805  20230404    225959  28144.2  ...  50.000000  0.507577  0.296023
5806  20230404    232959  28111.6  ...  50.000000  0.488236  0.300328

[5 rows x 33 columns]
0.5422794117647058
acc is : 0.5422794117647058
2023-04-05 00:00:34,591:INFO:logic:main.py:468:getModel:885513: df_pred.iloc[-5:,:] :
     pred    prob_0    prob_1  actual  ...       nav  sign  cost_        bm
539     0  0.515313  0.484687       0  ...  0.881536   1.0    0.0  0.993997
540     1  0.473459  0.526541       1  ...  0.882913   1.0    0.0  0.995550
541     0  0.517511  0.482489       0  ...  0.881890   1.0    0.0  0.994397
542     1  0.499483  0.500517       0  ...  0.877985   1.0    0.0  0.989993
543     1  0.478237  0.521763       1  ...  0.878760   1.0    0.0  0.990867

[5 rows x 10 columns]
2023-04-05 00:00:34,628:INFO:logic:main.py:478:getModel:885513: df_panel.iloc[-5:,:] :
    pred    prob_0    prob_1  actual  ...       nav  sign  cost_        bm
45     0  0.515019  0.484981       0  ...  0.881536   1.0    0.0  0.992078
46     1  0.473581  0.526419       1  ...  0.882913   1.0    0.0  0.996251
47     0  0.518002  0.481998       0  ...  0.881890   1.0    0.0  0.995097
48     0  0.500026  0.499974       0  ...  0.891009   1.0    0.0  0.992486
49     1  0.478237  0.521763       1  ...  0.878760   1.0    0.0  0.990867

[5 rows x 10 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': []}


## /root/FIL/strategy/modifiedmom/log.txt ----- -----

127.0.0.1 - - [05/Apr/2023 00:00:05] "POST / HTTP/1.1" 200 -
2023-04-05 00:00:05,215:INFO:modifiedmom:main.py:319:handleOrderFilled:185213: handleOrderFilled: data=OrderType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'clientorderid': '42116F1680624004243I0L59', 'symbol': 'BTCUSDT', 'gatewayorderid': 1680624004516690, 'quantity': '25.156', 'price': '28011.8', 'stopprice': '0', 'ordertype': '', 'side': 'BUY', 'status': 'FILLED', 'positionside': 'LONG', 'createtime': 1680624003460, 'updatetime': 1680624004516, 'tradetype': 'usdt', 'selfid': 42116, 'filltrades': [TradeType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'tradeid': 1680624004516, 'clientorderid': '42116F1680624004243I0L59', 'price': '28011.8', 'quantity': '25.156', 'commission': '704.6648408', 'commissionasset': 'USDT', 'tradetime': 1680624004516, 'tradetype': 'usdt', 'gatetype': 'simulator', 'handletime': 1680624004516}], 'gatetype': 'simulator', 'handletime': 0}
127.0.0.1 - - [05/Apr/2023 00:10:02] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=18776 

self.closeSec=1680624599, self.tradeDate='20230405', self.openTime='000000', self.closeTime='000959', self.symbol='BTCUSDT', self.open='28011.7', self.close='27966.1'
2023-04-05 00:10:02,114:INFO:modifiedmom:main.py:144:handleKline:185213: self.closeSec=1680624599, self.tradeDate='20230405', self.openTime='000000', self.closeTime='000959',self.symbol='BTCUSDT',self.open='28011.7', self.close='27966.1'
2023-04-05 00:10:02,136:INFO:modifiedmom:main.py:145:handleKline:185213: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec     open    close       pct
572  20230404   232000    232959  1680622199  27962.6    27987  0.000865
573  20230404   233000    233959  1680622799    27987    28006  0.000679
574  20230404   234000    234959  1680623399    28006  28053.9  0.001710
575  20230404   235000    235959  1680623999  28053.8  28011.7 -0.001504
576  20230405   000000    000959  1680624599  28011.7  27966.1 -0.001628
2023-04-05 00:10:02,136:INFO:modifiedmom:main.py:146:handleKline:185213: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': True, 'isOpen': False, 'isClose': True, 'isTrig': False}

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=18777 

self.closeSec=1680625199, self.tradeDate='20230405', self.openTime='001000', self.closeTime='001959', self.symbol='BTCUSDT', self.open='27966.1', self.close='28000.1'
127.0.0.1 - - [05/Apr/2023 00:20:05] "POST / HTTP/1.1" 200 -
2023-04-05 00:20:08,170:INFO:modifiedmom:main.py:144:handleKline:185213: self.closeSec=1680625199, self.tradeDate='20230405', self.openTime='001000', self.closeTime='001959',self.symbol='BTCUSDT',self.open='27966.1', self.close='28000.1'
2023-04-05 00:20:08,921:INFO:modifiedmom:main.py:145:handleKline:185213: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec     open    close       pct
573  20230404   233000    233959  1680622799    27987    28006  0.000679
574  20230404   234000    234959  1680623399    28006  28053.9  0.001710
575  20230404   235000    235959  1680623999  28053.8  28011.7 -0.001504
576  20230405   000000    000959  1680624599  28011.7  27966.1 -0.001628
577  20230405   001000    001959  1680625199  27966.1  28000.1  0.001216
2023-04-05 00:20:08,921:INFO:modifiedmom:main.py:146:handleKline:185213: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': True, 'isOpen': False, 'isClose': True, 'isTrig': False}


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

127.0.0.1 - - [05/Apr/2023 00:00:04] "POST / HTTP/1.1" 200 -
2023-04-05 00:00:04,679:INFO:pyemd2:main.py:303:handleOrderFilled:185189: handleOrderFilled: data=OrderType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'clientorderid': '42115F1680624004057I0L57', 'symbol': 'BTCUSDT', 'gatewayorderid': 1680624004384376, 'quantity': '34.92', 'price': '28011.7', 'stopprice': '0', 'ordertype': '', 'side': 'SELL', 'status': 'FILLED', 'positionside': 'SHORT', 'createtime': 1680624003384, 'updatetime': 1680624004384, 'tradetype': 'usdt', 'selfid': 42115, 'filltrades': [TradeType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'tradeid': 1680624004384, 'clientorderid': '42115F1680624004057I0L57', 'price': '28011.7', 'quantity': '34.92', 'commission': '978.168564', 'commissionasset': 'USDT', 'tradetime': 1680624004384, 'tradetype': 'usdt', 'gatetype': 'simulator', 'handletime': 1680624004384}], 'gatetype': 'simulator', 'handletime': 0}
127.0.0.1 - - [05/Apr/2023 00:10:02] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=18777 

self.closeSec=1680624599, self.tradeDate='20230405', self.openTime='000000', self.closeTime='000959', self.symbol='BTCUSDT', self.open='28011.7', self.close='27966.1'
2023-04-05 00:10:02,120:INFO:pyemd2:main.py:125:handleKline:185189: self.closeSec=1680624599, self.tradeDate='20230405', self.openTime='000000', self.closeTime='000959',self.symbol='BTCUSDT',self.open='28011.7', self.close='27966.1'
2023-04-05 00:10:02,141:INFO:pyemd2:main.py:126:handleKline:185189: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
17420  20230404   232000    232959  1680622199  27962.6    27987
17421  20230404   233000    233959  1680622799    27987    28006
17422  20230404   234000    234959  1680623399    28006  28053.9
17423  20230404   235000    235959  1680623999  28053.8  28011.7
17424  20230405   000000    000959  1680624599  28011.7  27966.1
2023-04-05 00:10:02,141:INFO:pyemd2:main.py:127:handleKline:185189: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=18778 

self.closeSec=1680625199, self.tradeDate='20230405', self.openTime='001000', self.closeTime='001959', self.symbol='BTCUSDT', self.open='27966.1', self.close='28000.1'
127.0.0.1 - - [05/Apr/2023 00:20:05] "POST / HTTP/1.1" 200 -
2023-04-05 00:20:10,816:INFO:pyemd2:main.py:125:handleKline:185189: self.closeSec=1680625199, self.tradeDate='20230405', self.openTime='001000', self.closeTime='001959',self.symbol='BTCUSDT',self.open='27966.1', self.close='28000.1'
2023-04-05 00:20:10,979:INFO:pyemd2:main.py:126:handleKline:185189: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
17421  20230404   233000    233959  1680622799    27987    28006
17422  20230404   234000    234959  1680623399    28006  28053.9
17423  20230404   235000    235959  1680623999  28053.8  28011.7
17424  20230405   000000    000959  1680624599  28011.7  27966.1
17425  20230405   001000    001959  1680625199  27966.1  28000.1
2023-04-05 00:20:10,979:INFO:pyemd2:main.py:127:handleKline:185189: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}


## /root/FIL/strategy/similarity/log.txt ----- -----

127.0.0.1 - - [05/Apr/2023 00:00:05] "POST / HTTP/1.1" 200 -
2023-04-05 00:00:05,399:INFO:testStrategy:main.py:308:handleOrderFilled:185174: handleOrderFilled: data=OrderType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'clientorderid': '42117F1680624004281I0L2', 'symbol': 'BTCUSDT', 'gatewayorderid': 1680624004614725, 'quantity': '46.54', 'price': '28011.7', 'stopprice': '0', 'ordertype': '', 'side': 'SELL', 'status': 'FILLED', 'positionside': 'SHORT', 'createtime': 1680624003622, 'updatetime': 1680624004614, 'tradetype': 'usdt', 'selfid': 42117, 'filltrades': [TradeType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'tradeid': 1680624004614, 'clientorderid': '42117F1680624004281I0L2', 'price': '28011.7', 'quantity': '46.54', 'commission': '1303.664518', 'commissionasset': 'USDT', 'tradetime': 1680624004614, 'tradetype': 'usdt', 'gatetype': 'simulator', 'handletime': 1680624004614}], 'gatetype': 'simulator', 'handletime': 0}

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=18777 

self.closeSec=1680624599, self.tradeDate='20230405', self.openTime='000000', self.closeTime='000959', self.symbol='BTCUSDT', self.open='28011.7', self.close='27966.1'
127.0.0.1 - - [05/Apr/2023 00:10:02] "POST / HTTP/1.1" 200 -
2023-04-05 00:10:02,129:INFO:testStrategy:main.py:101:handleKline:185174: self.closeSec=1680624599, self.tradeDate='20230405', self.openTime='000000', self.closeTime='000959',self.symbol='BTCUSDT',self.open='28011.7', self.close='27966.1'
2023-04-05 00:10:02,153:INFO:testStrategy:main.py:102:handleKline:185174: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
12236  20230404   232000    232959  1680622199  27962.6    27987
12237  20230404   233000    233959  1680622799    27987    28006
12238  20230404   234000    234959  1680623399    28006  28053.9
12239  20230404   235000    235959  1680623999  28053.8  28011.7
12240  20230405   000000    000959  1680624599  28011.7  27966.1
2023-04-05 00:10:02,154:INFO:testStrategy:main.py:103:handleKline:185174: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': True, 'isOpen': False, 'isClose': True, 'isTrig': False, 'isCorr': False}

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=18778 

self.closeSec=1680625199, self.tradeDate='20230405', self.openTime='001000', self.closeTime='001959', self.symbol='BTCUSDT', self.open='27966.1', self.close='28000.1'
127.0.0.1 - - [05/Apr/2023 00:20:05] "POST / HTTP/1.1" 200 -
2023-04-05 00:20:10,262:INFO:testStrategy:main.py:101:handleKline:185174: self.closeSec=1680625199, self.tradeDate='20230405', self.openTime='001000', self.closeTime='001959',self.symbol='BTCUSDT',self.open='27966.1', self.close='28000.1'
2023-04-05 00:20:10,636:INFO:testStrategy:main.py:102:handleKline:185174: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
12237  20230404   233000    233959  1680622799    27987    28006
12238  20230404   234000    234959  1680623399    28006  28053.9
12239  20230404   235000    235959  1680623999  28053.8  28011.7
12240  20230405   000000    000959  1680624599  28011.7  27966.1
12241  20230405   001000    001959  1680625199  27966.1  28000.1
2023-04-05 00:20:10,640:INFO:testStrategy:main.py:103:handleKline:185174: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': True, 'isOpen': False, 'isClose': True, 'isTrig': False, 'isCorr': False}


## /root/FIL/strategy/sr_min/log.txt ----- -----

--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=0, self.total=1000000.0, self.flagDict['side']='', self.tradeCount=0, self.count=32986
self.closeSec=1680625199, self.tradeDate='20230405', self.openTime='001500', self.closeTime='001959', self.symbol='BTCUSDT', self.open=27986.3, self.close=28000.1, self.high=28017.7, self.low=27982.0, self.vol=1365.972, self.amt=38251017.0435 
127.0.0.1 - - [05/Apr/2023 00:20:02] "POST / HTTP/1.1" 200 -
2023-04-05 00:20:06,650:INFO:sr_min:main.py:172:handleKline:449472: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5759  20230404   235500    235959  ...         0.0        0.0       0
5760  20230405   000000    000459  ...         0.0        0.0       0
5761  20230405   000500    000959  ...         0.0        0.0       0
5762  20230405   001000    001459  ...         0.0        0.0       0
5763  20230405   001500    001959  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-04-05 00:20:06,672:INFO:sr_min:main.py:175:handleKline:449472: self.closeSec=1680625199, self.tradeDate='20230405', self.openTime='001500', self.closeTime='001959',self.symbol='BTCUSDT',self.open=27986.3, self.close=28000.1, self.high=28017.7, self.low=27982.0, self.vol=1365.972, self.amt=38251017.0435, ukdf['pct'].iloc[-1]=0.000493 , ukdf['amount'].iloc[-1]=38251017.0435, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5763, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': []}
type(curSign)=<class 'int'>, curSign=0, self.sign=0
127.0.0.1 - - [05/Apr/2023 00:25:01] "POST / HTTP/1.1" 200 -
--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=0, self.total=1000000.0, self.flagDict['side']='', self.tradeCount=0, self.count=32987
self.closeSec=1680625499, self.tradeDate='20230405', self.openTime='002000', self.closeTime='002459', self.symbol='BTCUSDT', self.open=28000.0, self.close=28024.4, self.high=28024.4, self.low=27964.1, self.vol=1068.719, self.amt=29915807.9877 
2023-04-05 00:25:01,939:INFO:sr_min:main.py:172:handleKline:449472: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5760  20230405   000000    000459  ...         0.0        0.0       0
5761  20230405   000500    000959  ...         0.0        0.0       0
5762  20230405   001000    001459  ...         0.0        0.0       0
5763  20230405   001500    001959  ...         0.0        0.0       0
5764  20230405   002000    002459  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-04-05 00:25:01,940:INFO:sr_min:main.py:175:handleKline:449472: self.closeSec=1680625499, self.tradeDate='20230405', self.openTime='002000', self.closeTime='002459',self.symbol='BTCUSDT',self.open=28000.0, self.close=28024.4, self.high=28024.4, self.low=27964.1, self.vol=1068.719, self.amt=29915807.9877, ukdf['pct'].iloc[-1]=0.000868 , ukdf['amount'].iloc[-1]=29915807.9877, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5764, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': []}
type(curSign)=<class 'int'>, curSign=0, self.sign=0


## /root/FIL/strategy/s_rsrs/log.txt ----- -----

723  20230404   120000    155959  1680595199  ...    723  0.198068 -0.405388     NaN
724  20230404   160000    195959  1680609599  ...    724  0.209935 -0.342453     NaN

[5 rows x 15 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '52.088', 'enterprice': '28398.8', 'countrevence': '0', 'unrealprofit': '6109.9224', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '28281.5', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'numpy.int64'>, curSign=-9223372036854775808, self.sign=-1
127.0.0.1 - - [05/Apr/2023 00:00:02] "POST / HTTP/1.1" 200 -
--handleKline--:  version='2.0.0', self.name='s_rsrs', self.symbol='BTCUSDT', interval='4h', intervalSec=14400, wid=25, thd=0.6, self.sign=-1, self.total=1477757.4577056, self.flagDict['side']='sell', self.tradeCount=29, self.count=782
self.closeSec=1680623999, self.tradeDate='20230404', self.openTime='200000', self.closeTime='235959', self.symbol='BTCUSDT', self.open=28274.7, self.close=28011.7, self.high=28392.5, self.low=27935.2, self.vol=113740.253, self.amt=3202796349.30024 
2023-04-05 00:00:02,686:INFO:s_rsrs:main.py:141:handleKline:185271: self.closeSec=1680623999, self.tradeDate='20230404', self.openTime='200000', self.closeTime='235959',self.symbol='BTCUSDT',self.open=28274.7, self.close=28011.7, self.high=28392.5, self.low=27935.2, self.vol=113740.253, self.amt=3202796349.30024 
2023-04-05 00:00:02,709:INFO:s_rsrs:main.py:142:handleKline:185271: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime  ...         vol           amt       pct
721  20230404   040000    075959  ...  178714.809  4.945557e+09 -0.010174
722  20230404   080000    115959  ...   57048.555  1.586313e+09  0.002073
723  20230404   120000    155959  ...   58199.402  1.627344e+09  0.006088
724  20230404   160000    195959  ...  106225.317  2.997957e+09  0.009331
725  20230404   200000    235959  ...  113740.253  3.202796e+09 -0.009298

[5 rows x 11 columns]
2023-04-05 00:00:05,090:INFO:s_rsrs:main.py:151:handleKline:185271: df_s.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec  ...  index      beta    zscore  signal
721  20230404   040000    075959  1680566399  ...    721  0.172701 -0.528990     NaN
722  20230404   080000    115959  1680580799  ...    722  0.188907 -0.456086     NaN
723  20230404   120000    155959  1680595199  ...    723  0.198068 -0.405388     NaN
724  20230404   160000    195959  1680609599  ...    724  0.209935 -0.342453     NaN
725  20230404   200000    235959  1680623999  ...    725  0.185268 -0.417809     NaN

[5 rows x 15 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '52.088', 'enterprice': '28398.8', 'countrevence': '0', 'unrealprofit': '20021.73612329168', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '28014.41710714', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'numpy.int64'>, curSign=-9223372036854775808, self.sign=-1


