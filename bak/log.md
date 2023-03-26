# 20230327 00:26:02

## /root/FIL/strategy/amihud/log.txt ----- -----

--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=993672.4896432, self.flagDict['side']='sell', self.tradeCount=2, self.count=34396
self.closeSec=1679847599, self.tradeDate='20230327', self.openTime='001500', self.closeTime='001959', self.symbol='BTCUSDT', self.open=27791.8, self.close=27776.1, self.high=27791.8, self.low=27764.4, self.vol=1231.67, self.amt=34210856.5641 
127.0.0.1 - - [27/Mar/2023 00:20:04] "POST / HTTP/1.1" 200 -
2023-03-27 00:20:08,458:INFO:amihud:main.py:172:handleKline:200676: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5759  20230326   235500    235959  ...         0.0        0.0       0
5760  20230327   000000    000459  ...         0.0        0.0       0
5761  20230327   000500    000959  ...         0.0        0.0       0
5762  20230327   001000    001459  ...         0.0        0.0       0
5763  20230327   001500    001959  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-03-27 00:20:08,459:INFO:amihud:main.py:175:handleKline:200676: self.closeSec=1679847599, self.tradeDate='20230327', self.openTime='001500', self.closeTime='001959',self.symbol='BTCUSDT',self.open=27791.8, self.close=27776.1, self.high=27791.8, self.low=27764.4, self.vol=1231.67, self.amt=34210856.5641, ukdf['pct'].iloc[-1]=-0.000572 , ukdf['amount'].iloc[-1]=34210856.5641, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5763, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '60.176', 'enterprice': '16529.3', 'countrevence': '0', 'unrealprofit': '-676793.4544', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '27776.2', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1
127.0.0.1 - - [27/Mar/2023 00:25:01] "POST / HTTP/1.1" 200 -
--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=993672.4896432, self.flagDict['side']='sell', self.tradeCount=2, self.count=34397
self.closeSec=1679847899, self.tradeDate='20230327', self.openTime='002000', self.closeTime='002459', self.symbol='BTCUSDT', self.open=27776.2, self.close=27795.5, self.high=27800.0, self.low=27753.3, self.vol=966.674, self.amt=26850249.2698 
2023-03-27 00:25:01,642:INFO:amihud:main.py:172:handleKline:200676: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5760  20230327   000000    000459  ...         0.0        0.0       0
5761  20230327   000500    000959  ...         0.0        0.0       0
5762  20230327   001000    001459  ...         0.0        0.0       0
5763  20230327   001500    001959  ...         0.0        0.0       0
5764  20230327   002000    002459  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-03-27 00:25:01,643:INFO:amihud:main.py:175:handleKline:200676: self.closeSec=1679847899, self.tradeDate='20230327', self.openTime='002000', self.closeTime='002459',self.symbol='BTCUSDT',self.open=27776.2, self.close=27795.5, self.high=27800.0, self.low=27753.3, self.vol=966.674, self.amt=26850249.2698, ukdf['pct'].iloc[-1]=0.000698 , ukdf['amount'].iloc[-1]=26850249.2698, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5764, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '60.176', 'enterprice': '16529.3', 'countrevence': '0', 'unrealprofit': '-677954.8512', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '27795.5', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1


## /root/FIL/strategy/factorcheck/log.txt ----- -----


self.closeSec=1679847599, self.tradeDate='20230327', self.openTime='001500', self.closeTime='001959', self.symbol='BTCUSDT', self.open=27791.8, self.close=27776.1, self.high=27791.8, self.low=27764.4 
127.0.0.1 - - [27/Mar/2023 00:20:02] "POST / HTTP/1.1" 200 -
2023-03-27 00:20:06,076:INFO:factorcheck2:main.py:126:handleKline:185239: self.closeSec=1679847599, self.tradeDate='20230327', self.openTime='001500', self.closeTime='001959',self.symbol='BTCUSDT',self.open=27791.8, self.close=27776.1, self.high=27791.8, self.low=27764.4   
2023-03-27 00:20:06,927:INFO:factorcheck2:main.py:127:handleKline:185239: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime    closeSec  ...      low       pct  index  idx
1439  20230326   235500    235959  1679846399  ...  27750.2  0.000695   1727    5
1440  20230327   000000    000459  1679846699  ...  27767.9  0.000676   1440    0
1441  20230327   000500    000959  1679846999  ...  27801.2  0.001622   1441    1
1442  20230327   001000    001459  1679847299  ...  27790.0 -0.002272   1442    2
1443  20230327   001500    001959  1679847599  ...  27764.4 -0.000572   1443    3

[5 rows x 11 columns]
2023-03-27 00:20:06,935:INFO:factorcheck2:main.py:128:handleKline:185239: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}
127.0.0.1 - - [27/Mar/2023 00:25:01] "POST / HTTP/1.1" 200 -

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=444, self.factor=0.4095277009820121, self.count=34963 

self.closeSec=1679847899, self.tradeDate='20230327', self.openTime='002000', self.closeTime='002459', self.symbol='BTCUSDT', self.open=27776.2, self.close=27795.5, self.high=27800.0, self.low=27753.3 
2023-03-27 00:25:01,511:INFO:factorcheck2:main.py:126:handleKline:185239: self.closeSec=1679847899, self.tradeDate='20230327', self.openTime='002000', self.closeTime='002459',self.symbol='BTCUSDT',self.open=27776.2, self.close=27795.5, self.high=27800.0, self.low=27753.3   
2023-03-27 00:25:01,590:INFO:factorcheck2:main.py:127:handleKline:185239: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime    closeSec  ...      low       pct  index  idx
1440  20230327   000000    000459  1679846699  ...  27767.9  0.000676   1440    0
1441  20230327   000500    000959  1679846999  ...  27801.2  0.001622   1441    1
1442  20230327   001000    001459  1679847299  ...  27790.0 -0.002272   1442    2
1443  20230327   001500    001959  1679847599  ...  27764.4 -0.000572   1443    3
1444  20230327   002000    002459  1679847899  ...  27753.3  0.000698   1444    4

[5 rows x 11 columns]
2023-03-27 00:25:01,591:INFO:factorcheck2:main.py:128:handleKline:185239: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}


## /root/FIL/strategy/logic/log.txt ----- -----

2023-03-27 00:00:34,015:DEBUG:logic:main.py:463:getModel:885513: df_s.iloc[-5:,:] :
          date closeTime     open  ...    alpha58   alpha67   alpha72
5802  20230326    212959  27904.2  ...  50.833333  0.545814  0.317847
5803  20230326    215959  27880.4  ...  51.250000  0.582555  0.299943
5804  20230326    222959  28139.4  ...  51.250000  0.546755  0.295983
5805  20230326    225959  27933.1  ...  50.833333  0.522250  0.301828
5806  20230326    232959  27782.1  ...  50.833333  0.526836  0.305262

[5 rows x 33 columns]
0.5257352941176471
acc is : 0.5257352941176471
2023-03-27 00:00:34,262:INFO:logic:main.py:468:getModel:885513: df_pred.iloc[-5:,:] :
     pred    prob_0    prob_1  actual  ...       nav  sign  cost_        bm
539     0  0.538716  0.461284       1  ...  1.087638   1.0    0.0  1.130279
540     0  0.617657  0.382343       0  ...  1.079837   1.0    0.0  1.122172
541     1  0.487220  0.512780       0  ...  1.073999   1.0    0.0  1.116106
542     1  0.487422  0.512578       1  ...  1.075236   1.0    0.0  1.117391
543     0  0.526152  0.473848       0  ...  1.074359   1.0    0.0  1.116479

[5 rows x 10 columns]
2023-03-27 00:00:34,301:INFO:logic:main.py:478:getModel:885513: df_panel.iloc[-5:,:] :
    pred    prob_0    prob_1  actual  ...       nav  sign  cost_        bm
45     0  0.538872  0.461128       1  ...  1.087638   1.0    0.0  1.135837
46     0  0.617584  0.382416       0  ...  1.079837   1.0    0.0  1.126607
47     1  0.487310  0.512690       0  ...  1.073999   1.0    0.0  1.120517
48     1  0.487586  0.512414       1  ...  1.075236   1.0    0.0  1.122183
49     0  0.526152  0.473848       0  ...  1.074359   1.0    0.0  1.116479

[5 rows x 10 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': []}


## /root/FIL/strategy/modifiedmom/log.txt ----- -----

127.0.0.1 - - [27/Mar/2023 00:00:03] "POST / HTTP/1.1" 200 -
2023-03-27 00:00:03,092:INFO:modifiedmom:main.py:319:handleOrderFilled:185213: handleOrderFilled: data=OrderType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'clientorderid': '42059F1679846402723I0L59', 'symbol': 'BTCUSDT', 'gatewayorderid': 1679846402834131, 'quantity': '27.179', 'price': '27790.1', 'stopprice': '0', 'ordertype': '', 'side': 'BUY', 'status': 'FILLED', 'positionside': 'LONG', 'createtime': 1679846402341, 'updatetime': 1679846402834, 'tradetype': 'usdt', 'selfid': 42059, 'filltrades': [TradeType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'tradeid': 1679846402834, 'clientorderid': '42059F1679846402723I0L59', 'price': '27790.1', 'quantity': '27.179', 'commission': '755.3071279', 'commissionasset': 'USDT', 'tradetime': 1679846402834, 'tradetype': 'usdt', 'gatetype': 'simulator', 'handletime': 1679846402834}], 'gatetype': 'simulator', 'handletime': 0}
127.0.0.1 - - [27/Mar/2023 00:10:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=17480 

self.closeSec=1679846999, self.tradeDate='20230327', self.openTime='000000', self.closeTime='000959', self.symbol='BTCUSDT', self.open='27790.1', self.close='27855.3'
2023-03-27 00:10:01,586:INFO:modifiedmom:main.py:144:handleKline:185213: self.closeSec=1679846999, self.tradeDate='20230327', self.openTime='000000', self.closeTime='000959',self.symbol='BTCUSDT',self.open='27790.1', self.close='27855.3'
2023-03-27 00:10:01,630:INFO:modifiedmom:main.py:145:handleKline:185213: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec     open    close       pct
572  20230326   232000    232959  1679844599  27796.9  27814.1  0.000615
573  20230326   233000    233959  1679845199    27814  27761.5 -0.001891
574  20230326   234000    234959  1679845799  27761.5  27719.9 -0.001498
575  20230326   235000    235959  1679846399  27719.9  27791.4  0.002579
576  20230327   000000    000959  1679846999  27790.1  27855.3  0.002299
2023-03-27 00:10:01,633:INFO:modifiedmom:main.py:146:handleKline:185213: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': True, 'isOpen': False, 'isClose': True, 'isTrig': False}

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=17481 

self.closeSec=1679847599, self.tradeDate='20230327', self.openTime='001000', self.closeTime='001959', self.symbol='BTCUSDT', self.open='27855.7', self.close='27776.1'
127.0.0.1 - - [27/Mar/2023 00:20:04] "POST / HTTP/1.1" 200 -
2023-03-27 00:20:07,417:INFO:modifiedmom:main.py:144:handleKline:185213: self.closeSec=1679847599, self.tradeDate='20230327', self.openTime='001000', self.closeTime='001959',self.symbol='BTCUSDT',self.open='27855.7', self.close='27776.1'
2023-03-27 00:20:08,162:INFO:modifiedmom:main.py:145:handleKline:185213: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec     open    close       pct
573  20230326   233000    233959  1679845199    27814  27761.5 -0.001891
574  20230326   234000    234959  1679845799  27761.5  27719.9 -0.001498
575  20230326   235000    235959  1679846399  27719.9  27791.4  0.002579
576  20230327   000000    000959  1679846999  27790.1  27855.3  0.002299
577  20230327   001000    001959  1679847599  27855.7  27776.1 -0.002843
2023-03-27 00:20:08,162:INFO:modifiedmom:main.py:146:handleKline:185213: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': True, 'isOpen': False, 'isClose': True, 'isTrig': False}


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

127.0.0.1 - - [27/Mar/2023 00:00:03] "POST / HTTP/1.1" 200 -
2023-03-27 00:00:03,299:INFO:pyemd2:main.py:303:handleOrderFilled:185189: handleOrderFilled: data=OrderType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'clientorderid': '42060F1679846402735I0L57', 'symbol': 'BTCUSDT', 'gatewayorderid': 1679846402871344, 'quantity': '38.095', 'price': '27790', 'stopprice': '0', 'ordertype': '', 'side': 'SELL', 'status': 'FILLED', 'positionside': 'SHORT', 'createtime': 1679846402396, 'updatetime': 1679846402871, 'tradetype': 'usdt', 'selfid': 42060, 'filltrades': [TradeType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'tradeid': 1679846402871, 'clientorderid': '42060F1679846402735I0L57', 'price': '27790', 'quantity': '38.095', 'commission': '1058.66005', 'commissionasset': 'USDT', 'tradetime': 1679846402871, 'tradetype': 'usdt', 'gatetype': 'simulator', 'handletime': 1679846402871}], 'gatetype': 'simulator', 'handletime': 0}

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=17481 

self.closeSec=1679846999, self.tradeDate='20230327', self.openTime='000000', self.closeTime='000959', self.symbol='BTCUSDT', self.open='27790.1', self.close='27855.3'
2023-03-27 00:10:01,593:INFO:pyemd2:main.py:125:handleKline:185189: self.closeSec=1679846999, self.tradeDate='20230327', self.openTime='000000', self.closeTime='000959',self.symbol='BTCUSDT',self.open='27790.1', self.close='27855.3'
127.0.0.1 - - [27/Mar/2023 00:10:01] "POST / HTTP/1.1" 200 -
2023-03-27 00:10:01,617:INFO:pyemd2:main.py:126:handleKline:185189: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
17420  20230326   232000    232959  1679844599  27796.9  27814.1
17421  20230326   233000    233959  1679845199    27814  27761.5
17422  20230326   234000    234959  1679845799  27761.5  27719.9
17423  20230326   235000    235959  1679846399  27719.9  27791.4
17424  20230327   000000    000959  1679846999  27790.1  27855.3
2023-03-27 00:10:01,617:INFO:pyemd2:main.py:127:handleKline:185189: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=17482 

self.closeSec=1679847599, self.tradeDate='20230327', self.openTime='001000', self.closeTime='001959', self.symbol='BTCUSDT', self.open='27855.7', self.close='27776.1'
127.0.0.1 - - [27/Mar/2023 00:20:04] "POST / HTTP/1.1" 200 -
2023-03-27 00:20:10,293:INFO:pyemd2:main.py:125:handleKline:185189: self.closeSec=1679847599, self.tradeDate='20230327', self.openTime='001000', self.closeTime='001959',self.symbol='BTCUSDT',self.open='27855.7', self.close='27776.1'
2023-03-27 00:20:10,439:INFO:pyemd2:main.py:126:handleKline:185189: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
17421  20230326   233000    233959  1679845199    27814  27761.5
17422  20230326   234000    234959  1679845799  27761.5  27719.9
17423  20230326   235000    235959  1679846399  27719.9  27791.4
17424  20230327   000000    000959  1679846999  27790.1  27855.3
17425  20230327   001000    001959  1679847599  27855.7  27776.1
2023-03-27 00:20:10,440:INFO:pyemd2:main.py:127:handleKline:185189: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}


## /root/FIL/strategy/similarity/log.txt ----- -----

127.0.0.1 - - [27/Mar/2023 00:00:03] "POST / HTTP/1.1" 200 -
2023-03-27 00:00:03,501:INFO:testStrategy:main.py:308:handleOrderFilled:185174: handleOrderFilled: data=OrderType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'clientorderid': '42061F1679846402776I0L2', 'symbol': 'BTCUSDT', 'gatewayorderid': 1679846402884298, 'quantity': '42.985', 'price': '27790', 'stopprice': '0', 'ordertype': '', 'side': 'SELL', 'status': 'FILLED', 'positionside': 'SHORT', 'createtime': 1679846402378, 'updatetime': 1679846402884, 'tradetype': 'usdt', 'selfid': 42061, 'filltrades': [TradeType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'tradeid': 1679846402884, 'clientorderid': '42061F1679846402776I0L2', 'price': '27790', 'quantity': '42.985', 'commission': '1194.55315', 'commissionasset': 'USDT', 'tradetime': 1679846402884, 'tradetype': 'usdt', 'gatetype': 'simulator', 'handletime': 1679846402884}], 'gatetype': 'simulator', 'handletime': 0}
127.0.0.1 - - [27/Mar/2023 00:10:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=17481 

self.closeSec=1679846999, self.tradeDate='20230327', self.openTime='000000', self.closeTime='000959', self.symbol='BTCUSDT', self.open='27790.1', self.close='27855.3'
2023-03-27 00:10:01,606:INFO:testStrategy:main.py:101:handleKline:185174: self.closeSec=1679846999, self.tradeDate='20230327', self.openTime='000000', self.closeTime='000959',self.symbol='BTCUSDT',self.open='27790.1', self.close='27855.3'
2023-03-27 00:10:01,659:INFO:testStrategy:main.py:102:handleKline:185174: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
12236  20230326   232000    232959  1679844599  27796.9  27814.1
12237  20230326   233000    233959  1679845199    27814  27761.5
12238  20230326   234000    234959  1679845799  27761.5  27719.9
12239  20230326   235000    235959  1679846399  27719.9  27791.4
12240  20230327   000000    000959  1679846999  27790.1  27855.3
2023-03-27 00:10:01,661:INFO:testStrategy:main.py:103:handleKline:185174: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': True, 'isOpen': False, 'isClose': True, 'isTrig': False, 'isCorr': False}

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=17482 

self.closeSec=1679847599, self.tradeDate='20230327', self.openTime='001000', self.closeTime='001959', self.symbol='BTCUSDT', self.open='27855.7', self.close='27776.1'
127.0.0.1 - - [27/Mar/2023 00:20:05] "POST / HTTP/1.1" 200 -
2023-03-27 00:20:09,744:INFO:testStrategy:main.py:101:handleKline:185174: self.closeSec=1679847599, self.tradeDate='20230327', self.openTime='001000', self.closeTime='001959',self.symbol='BTCUSDT',self.open='27855.7', self.close='27776.1'
2023-03-27 00:20:10,072:INFO:testStrategy:main.py:102:handleKline:185174: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
12237  20230326   233000    233959  1679845199    27814  27761.5
12238  20230326   234000    234959  1679845799  27761.5  27719.9
12239  20230326   235000    235959  1679846399  27719.9  27791.4
12240  20230327   000000    000959  1679846999  27790.1  27855.3
12241  20230327   001000    001959  1679847599  27855.7  27776.1
2023-03-27 00:20:10,072:INFO:testStrategy:main.py:103:handleKline:185174: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': True, 'isOpen': False, 'isClose': True, 'isTrig': False, 'isCorr': False}


## /root/FIL/strategy/sr_min/log.txt ----- -----

--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=0, self.total=1000000.0, self.flagDict['side']='', self.tradeCount=0, self.count=30394
self.closeSec=1679847599, self.tradeDate='20230327', self.openTime='001500', self.closeTime='001959', self.symbol='BTCUSDT', self.open=27791.8, self.close=27776.1, self.high=27791.8, self.low=27764.4, self.vol=1231.67, self.amt=34210856.5641 
127.0.0.1 - - [27/Mar/2023 00:20:02] "POST / HTTP/1.1" 200 -
2023-03-27 00:20:05,626:INFO:sr_min:main.py:172:handleKline:449472: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5759  20230326   235500    235959  ...         0.0        0.0       0
5760  20230327   000000    000459  ...         0.0        0.0       0
5761  20230327   000500    000959  ...         0.0        0.0       0
5762  20230327   001000    001459  ...         0.0        0.0       0
5763  20230327   001500    001959  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-03-27 00:20:05,646:INFO:sr_min:main.py:175:handleKline:449472: self.closeSec=1679847599, self.tradeDate='20230327', self.openTime='001500', self.closeTime='001959',self.symbol='BTCUSDT',self.open=27791.8, self.close=27776.1, self.high=27791.8, self.low=27764.4, self.vol=1231.67, self.amt=34210856.5641, ukdf['pct'].iloc[-1]=-0.000572 , ukdf['amount'].iloc[-1]=34210856.5641, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5763, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': []}
type(curSign)=<class 'int'>, curSign=0, self.sign=0
127.0.0.1 - - [27/Mar/2023 00:25:01] "POST / HTTP/1.1" 200 -
--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=0, self.total=1000000.0, self.flagDict['side']='', self.tradeCount=0, self.count=30395
self.closeSec=1679847899, self.tradeDate='20230327', self.openTime='002000', self.closeTime='002459', self.symbol='BTCUSDT', self.open=27776.2, self.close=27795.5, self.high=27800.0, self.low=27753.3, self.vol=966.674, self.amt=26850249.2698 
2023-03-27 00:25:01,605:INFO:sr_min:main.py:172:handleKline:449472: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5760  20230327   000000    000459  ...         0.0        0.0       0
5761  20230327   000500    000959  ...         0.0        0.0       0
5762  20230327   001000    001459  ...         0.0        0.0       0
5763  20230327   001500    001959  ...         0.0        0.0       0
5764  20230327   002000    002459  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-03-27 00:25:01,606:INFO:sr_min:main.py:175:handleKline:449472: self.closeSec=1679847899, self.tradeDate='20230327', self.openTime='002000', self.closeTime='002459',self.symbol='BTCUSDT',self.open=27776.2, self.close=27795.5, self.high=27800.0, self.low=27753.3, self.vol=966.674, self.amt=26850249.2698, ukdf['pct'].iloc[-1]=0.000698 , ukdf['amount'].iloc[-1]=26850249.2698, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5764, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': []}
type(curSign)=<class 'int'>, curSign=0, self.sign=0


## /root/FIL/strategy/s_rsrs/log.txt ----- -----

723  20230326   120000    155959  1679817599  ...    723  0.037986 -1.514059    -1.0
724  20230326   160000    195959  1679831999  ...    724  0.035285 -1.482784    -1.0

[5 rows x 15 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '53.706', 'enterprice': '28091.1', 'countrevence': '0', 'unrealprofit': '10751.9412', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '27890.9', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'numpy.int64'>, curSign=-1, self.sign=-1
127.0.0.1 - - [27/Mar/2023 00:00:01] "POST / HTTP/1.1" 200 -
--handleKline--:  version='2.0.0', self.name='s_rsrs', self.symbol='BTCUSDT', interval='4h', intervalSec=14400, wid=25, thd=0.6, self.sign=-1, self.total=1507151.9559834, self.flagDict['side']='sell', self.tradeCount=27, self.count=728
self.closeSec=1679846399, self.tradeDate='20230326', self.openTime='200000', self.closeTime='235959', self.symbol='BTCUSDT', self.open=27852.0, self.close=27791.4, self.high=28186.9, self.low=27677.3, self.vol=146714.908, self.amt=4094085904.11387 
2023-03-27 00:00:01,971:INFO:s_rsrs:main.py:141:handleKline:185271: self.closeSec=1679846399, self.tradeDate='20230326', self.openTime='200000', self.closeTime='235959',self.symbol='BTCUSDT',self.open=27852.0, self.close=27791.4, self.high=28186.9, self.low=27677.3, self.vol=146714.908, self.amt=4094085904.11387 
2023-03-27 00:00:02,094:INFO:s_rsrs:main.py:142:handleKline:185271: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime  ...         vol           amt       pct
721  20230326   040000    075959  ...   46178.862  1.264141e+09  0.009853
722  20230326   080000    115959  ...   38527.410  1.061184e+09  0.002550
723  20230326   120000    155959  ...   25075.949  6.894752e+08 -0.000905
724  20230326   160000    195959  ...   73218.713  2.027381e+09  0.013084
725  20230326   200000    235959  ...  146714.908  4.094086e+09 -0.002179

[5 rows x 11 columns]
2023-03-27 00:00:04,628:INFO:s_rsrs:main.py:151:handleKline:185271: df_s.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec  ...  index      beta    zscore  signal
721  20230326   040000    075959  1679788799  ...    721  0.041372 -1.584813    -1.0
722  20230326   080000    115959  1679803199  ...    722  0.042398 -1.541904    -1.0
723  20230326   120000    155959  1679817599  ...    723  0.037986 -1.514059    -1.0
724  20230326   160000    195959  1679831999  ...    724  0.035285 -1.482784    -1.0
725  20230326   200000    235959  1679846399  ...    725  0.036491 -1.443176    -1.0

[5 rows x 15 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '53.706', 'enterprice': '28091.1', 'countrevence': '0', 'unrealprofit': '15979.67180277024', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '27793.56021296', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'numpy.int64'>, curSign=-1, self.sign=-1


