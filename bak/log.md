# 20230406 00:26:02

## /root/FIL/strategy/amihud/log.txt ----- -----

--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=993672.4896432, self.flagDict['side']='sell', self.tradeCount=2, self.count=37276
self.closeSec=1680711599, self.tradeDate='20230406', self.openTime='001500', self.closeTime='001959', self.symbol='BTCUSDT', self.open=27881.6, self.close=27905.0, self.high=27905.0, self.low=27775.0, self.vol=9712.692, self.amt=270368502.4485 
127.0.0.1 - - [06/Apr/2023 00:20:04] "POST / HTTP/1.1" 200 -
2023-04-06 00:20:09,626:INFO:amihud:main.py:172:handleKline:200676: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5759  20230405   235500    235959  ...         0.0        0.0       0
5760  20230406   000000    000459  ...         0.0        0.0       0
5761  20230406   000500    000959  ...         0.0        0.0       0
5762  20230406   001000    001459  ...         0.0        0.0       0
5763  20230406   001500    001959  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-04-06 00:20:09,646:INFO:amihud:main.py:175:handleKline:200676: self.closeSec=1680711599, self.tradeDate='20230406', self.openTime='001500', self.closeTime='001959',self.symbol='BTCUSDT',self.open=27881.6, self.close=27905.0, self.high=27905.0, self.low=27775.0, self.vol=9712.692, self.amt=270368502.4485, ukdf['pct'].iloc[-1]=0.000836 , ukdf['amount'].iloc[-1]=270368502.4485, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5763, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '60.176', 'enterprice': '16529.3', 'countrevence': '0', 'unrealprofit': '-684707.84060474336', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '27907.72064286', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1
127.0.0.1 - - [06/Apr/2023 00:25:01] "POST / HTTP/1.1" 200 -
--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=993672.4896432, self.flagDict['side']='sell', self.tradeCount=2, self.count=37277
self.closeSec=1680711899, self.tradeDate='20230406', self.openTime='002000', self.closeTime='002459', self.symbol='BTCUSDT', self.open=27905.0, self.close=27934.0, self.high=27937.5, self.low=27875.4, self.vol=2654.023, self.amt=74063466.3167 
2023-04-06 00:25:01,582:INFO:amihud:main.py:172:handleKline:200676: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5760  20230406   000000    000459  ...         0.0        0.0       0
5761  20230406   000500    000959  ...         0.0        0.0       0
5762  20230406   001000    001459  ...         0.0        0.0       0
5763  20230406   001500    001959  ...         0.0        0.0       0
5764  20230406   002000    002459  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-04-06 00:25:01,583:INFO:amihud:main.py:175:handleKline:200676: self.closeSec=1680711899, self.tradeDate='20230406', self.openTime='002000', self.closeTime='002459',self.symbol='BTCUSDT',self.open=27905.0, self.close=27934.0, self.high=27937.5, self.low=27875.4, self.vol=2654.023, self.amt=74063466.3167, ukdf['pct'].iloc[-1]=0.001039 , ukdf['amount'].iloc[-1]=74063466.3167, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5764, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '60.176', 'enterprice': '16529.3', 'countrevence': '0', 'unrealprofit': '-686291.55663221632', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '27934.03871032', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1


## /root/FIL/strategy/factorcheck/log.txt ----- -----


self.closeSec=1680711599, self.tradeDate='20230406', self.openTime='001500', self.closeTime='001959', self.symbol='BTCUSDT', self.open=27881.6, self.close=27905.0, self.high=27905.0, self.low=27775.0 
127.0.0.1 - - [06/Apr/2023 00:20:03] "POST / HTTP/1.1" 200 -
2023-04-06 00:20:06,666:INFO:factorcheck2:main.py:126:handleKline:185239: self.closeSec=1680711599, self.tradeDate='20230406', self.openTime='001500', self.closeTime='001959',self.symbol='BTCUSDT',self.open=27881.6, self.close=27905.0, self.high=27905.0, self.low=27775.0   
2023-04-06 00:20:07,936:INFO:factorcheck2:main.py:127:handleKline:185239: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime    closeSec  ...      low       pct  index  idx
1439  20230405   235500    235959  1680710399  ...  28000.0 -0.002837   1727    5
1440  20230406   000000    000459  1680710699  ...  27957.2  0.000568   1440    0
1441  20230406   000500    000959  1680710999  ...  27900.0 -0.003988   1441    1
1442  20230406   001000    001459  1680711299  ...  27862.4 -0.001336   1442    2
1443  20230406   001500    001959  1680711599  ...  27775.0  0.000836   1443    3

[5 rows x 11 columns]
2023-04-06 00:20:07,946:INFO:factorcheck2:main.py:128:handleKline:185239: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=57, self.factor=0.3882143724042621, self.count=37843 

self.closeSec=1680711899, self.tradeDate='20230406', self.openTime='002000', self.closeTime='002459', self.symbol='BTCUSDT', self.open=27905.0, self.close=27934.0, self.high=27937.5, self.low=27875.4 
127.0.0.1 - - [06/Apr/2023 00:25:01] "POST / HTTP/1.1" 200 -
2023-04-06 00:25:01,503:INFO:factorcheck2:main.py:126:handleKline:185239: self.closeSec=1680711899, self.tradeDate='20230406', self.openTime='002000', self.closeTime='002459',self.symbol='BTCUSDT',self.open=27905.0, self.close=27934.0, self.high=27937.5, self.low=27875.4   
2023-04-06 00:25:01,544:INFO:factorcheck2:main.py:127:handleKline:185239: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime    closeSec  ...      low       pct  index  idx
1440  20230406   000000    000459  1680710699  ...  27957.2  0.000568   1440    0
1441  20230406   000500    000959  1680710999  ...  27900.0 -0.003988   1441    1
1442  20230406   001000    001459  1680711299  ...  27862.4 -0.001336   1442    2
1443  20230406   001500    001959  1680711599  ...  27775.0  0.000836   1443    3
1444  20230406   002000    002459  1680711899  ...  27875.4  0.001039   1444    4

[5 rows x 11 columns]
2023-04-06 00:25:01,544:INFO:factorcheck2:main.py:128:handleKline:185239: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}


## /root/FIL/strategy/logic/log.txt ----- -----

2023-04-06 00:00:35,298:DEBUG:logic:main.py:463:getModel:885513: df_s.iloc[-5:,:] :
          date closeTime     open  ...    alpha58   alpha67   alpha72
5802  20230405    212959  28556.4  ...  49.166667  0.539918  0.326138
5803  20230405    215959  28488.9  ...  48.750000  0.521298  0.340710
5804  20230405    222959  28391.3  ...  48.333333  0.481828  0.374498
5805  20230405    225959  28164.1  ...  47.916667  0.470406  0.412378
5806  20230405    232959  28092.7  ...  47.916667  0.455649  0.440074

[5 rows x 33 columns]
0.5441176470588235
acc is : 0.5441176470588235
2023-04-06 00:00:35,451:INFO:logic:main.py:468:getModel:885513: df_pred.iloc[-5:,:] :
     pred    prob_0    prob_1  actual  ...       nav  sign   cost_        bm
539     1  0.496307  0.503693       0  ...  0.969520   1.0  0.0000  1.033407
540     1  0.483176  0.516824       0  ...  0.961762   1.0  0.0000  1.025137
541     1  0.442259  0.557741       0  ...  0.962661  -1.0 -0.0016  1.022538
542     1  0.468000  0.532000       0  ...  0.965937  -1.0  0.0000  1.019058
543     1  0.454333  0.545667       1  ...  0.965323  -1.0  0.0000  1.019706

[5 rows x 10 columns]
2023-04-06 00:00:35,485:INFO:logic:main.py:478:getModel:885513: df_panel.iloc[-5:,:] :
    pred    prob_0    prob_1  actual  ...       nav  sign   cost_        bm
45     1  0.497295  0.502705       0  ...  0.969520   1.0  0.0000  1.033569
46     1  0.483684  0.516316       0  ...  0.961762   1.0  0.0000  1.024857
47     1  0.442422  0.557578       0  ...  0.962661  -1.0 -0.0016  1.022259
48     1  0.467579  0.532421       0  ...  0.965937  -1.0  0.0000  1.017078
49     1  0.454333  0.545667       1  ...  0.965323  -1.0  0.0000  1.019706

[5 rows x 10 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': []}


## /root/FIL/strategy/modifiedmom/log.txt ----- -----

127.0.0.1 - - [06/Apr/2023 00:00:04] "POST / HTTP/1.1" 200 -
2023-04-06 00:00:04,904:INFO:modifiedmom:main.py:319:handleOrderFilled:185213: handleOrderFilled: data=OrderType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'clientorderid': '42121F1680710404162I0L59', 'symbol': 'BTCUSDT', 'gatewayorderid': 1680710404425134, 'quantity': '24.454', 'price': '28012.2', 'stopprice': '0', 'ordertype': '', 'side': 'SELL', 'status': 'FILLED', 'positionside': 'SHORT', 'createtime': 1680710403482, 'updatetime': 1680710404425, 'tradetype': 'usdt', 'selfid': 42121, 'filltrades': [TradeType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'tradeid': 1680710404425, 'clientorderid': '42121F1680710404162I0L59', 'price': '28012.2', 'quantity': '24.454', 'commission': '685.0103388', 'commissionasset': 'USDT', 'tradetime': 1680710404425, 'tradetype': 'usdt', 'gatetype': 'simulator', 'handletime': 1680710404425}], 'gatetype': 'simulator', 'handletime': 0}
127.0.0.1 - - [06/Apr/2023 00:10:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=18920 

self.closeSec=1680710999, self.tradeDate='20230406', self.openTime='000000', self.closeTime='000959', self.symbol='BTCUSDT', self.open='28015', self.close='27919'
2023-04-06 00:10:01,765:INFO:modifiedmom:main.py:144:handleKline:185213: self.closeSec=1680710999, self.tradeDate='20230406', self.openTime='000000', self.closeTime='000959',self.symbol='BTCUSDT',self.open='28015', self.close='27919'
2023-04-06 00:10:01,846:INFO:modifiedmom:main.py:145:handleKline:185213: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec     open    close       pct
572  20230405   232000    232959  1680708599    27938  27997.1  0.002115
573  20230405   233000    233959  1680709199  27997.1  28064.1  0.002393
574  20230405   234000    234959  1680709799    28064    28085  0.000745
575  20230405   235000    235959  1680710399  28085.1  28014.9 -0.002496
576  20230406   000000    000959  1680710999    28015    27919 -0.003423
2023-04-06 00:10:01,850:INFO:modifiedmom:main.py:146:handleKline:185213: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': True, 'isOpen': False, 'isClose': True, 'isTrig': False}

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=18921 

self.closeSec=1680711599, self.tradeDate='20230406', self.openTime='001000', self.closeTime='001959', self.symbol='BTCUSDT', self.open='27919', self.close='27905'
127.0.0.1 - - [06/Apr/2023 00:20:04] "POST / HTTP/1.1" 200 -
2023-04-06 00:20:07,966:INFO:modifiedmom:main.py:144:handleKline:185213: self.closeSec=1680711599, self.tradeDate='20230406', self.openTime='001000', self.closeTime='001959',self.symbol='BTCUSDT',self.open='27919', self.close='27905'
2023-04-06 00:20:08,837:INFO:modifiedmom:main.py:145:handleKline:185213: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec     open    close       pct
573  20230405   233000    233959  1680709199  27997.1  28064.1  0.002393
574  20230405   234000    234959  1680709799    28064    28085  0.000745
575  20230405   235000    235959  1680710399  28085.1  28014.9 -0.002496
576  20230406   000000    000959  1680710999    28015    27919 -0.003423
577  20230406   001000    001959  1680711599    27919    27905 -0.000501
2023-04-06 00:20:08,845:INFO:modifiedmom:main.py:146:handleKline:185213: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': True, 'isOpen': False, 'isClose': True, 'isTrig': False}


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

2023-04-06 00:00:03,061:INFO:pyemd2:main.py:127:handleKline:185189: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}
2023-04-06 00:00:03,207:INFO:pyemd2:main.py:190:insertFactor:185189: curDateTime:4060000, name:pyemd2, symbol:BTCUSDT, tradeDate:20230405, closeTime:235959, close:28014.9, total:978039.764104, pct_pre:0.019051637518281206, thd:-0.18385274994959394, side:sell 

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=18921 

self.closeSec=1680710999, self.tradeDate='20230406', self.openTime='000000', self.closeTime='000959', self.symbol='BTCUSDT', self.open='28015', self.close='27919'
2023-04-06 00:10:01,753:INFO:pyemd2:main.py:125:handleKline:185189: self.closeSec=1680710999, self.tradeDate='20230406', self.openTime='000000', self.closeTime='000959',self.symbol='BTCUSDT',self.open='28015', self.close='27919'
127.0.0.1 - - [06/Apr/2023 00:10:01] "POST / HTTP/1.1" 200 -
2023-04-06 00:10:01,775:INFO:pyemd2:main.py:126:handleKline:185189: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
17420  20230405   232000    232959  1680708599    27938  27997.1
17421  20230405   233000    233959  1680709199  27997.1  28064.1
17422  20230405   234000    234959  1680709799    28064    28085
17423  20230405   235000    235959  1680710399  28085.1  28014.9
17424  20230406   000000    000959  1680710999    28015    27919
2023-04-06 00:10:01,780:INFO:pyemd2:main.py:127:handleKline:185189: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=18922 

self.closeSec=1680711599, self.tradeDate='20230406', self.openTime='001000', self.closeTime='001959', self.symbol='BTCUSDT', self.open='27919', self.close='27905'
127.0.0.1 - - [06/Apr/2023 00:20:05] "POST / HTTP/1.1" 200 -
2023-04-06 00:20:11,338:INFO:pyemd2:main.py:125:handleKline:185189: self.closeSec=1680711599, self.tradeDate='20230406', self.openTime='001000', self.closeTime='001959',self.symbol='BTCUSDT',self.open='27919', self.close='27905'
2023-04-06 00:20:11,483:INFO:pyemd2:main.py:126:handleKline:185189: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
17421  20230405   233000    233959  1680709199  27997.1  28064.1
17422  20230405   234000    234959  1680709799    28064    28085
17423  20230405   235000    235959  1680710399  28085.1  28014.9
17424  20230406   000000    000959  1680710999    28015    27919
17425  20230406   001000    001959  1680711599    27919    27905
2023-04-06 00:20:11,483:INFO:pyemd2:main.py:127:handleKline:185189: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}


## /root/FIL/strategy/similarity/log.txt ----- -----

127.0.0.1 - - [06/Apr/2023 00:00:04] "POST / HTTP/1.1" 200 -
2023-04-06 00:00:04,691:INFO:testStrategy:main.py:308:handleOrderFilled:185174: handleOrderFilled: data=OrderType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'clientorderid': '42120F1680710404142I0L2', 'symbol': 'BTCUSDT', 'gatewayorderid': 1680710404422163, 'quantity': '46.226', 'price': '28012.2', 'stopprice': '0', 'ordertype': '', 'side': 'SELL', 'status': 'FILLED', 'positionside': 'SHORT', 'createtime': 1680710403434, 'updatetime': 1680710404422, 'tradetype': 'usdt', 'selfid': 42120, 'filltrades': [TradeType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'tradeid': 1680710404422, 'clientorderid': '42120F1680710404142I0L2', 'price': '28012.2', 'quantity': '46.226', 'commission': '1294.8919572', 'commissionasset': 'USDT', 'tradetime': 1680710404422, 'tradetype': 'usdt', 'gatetype': 'simulator', 'handletime': 1680710404422}], 'gatetype': 'simulator', 'handletime': 0}
127.0.0.1 - - [06/Apr/2023 00:10:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=18921 

self.closeSec=1680710999, self.tradeDate='20230406', self.openTime='000000', self.closeTime='000959', self.symbol='BTCUSDT', self.open='28015', self.close='27919'
2023-04-06 00:10:01,775:INFO:testStrategy:main.py:101:handleKline:185174: self.closeSec=1680710999, self.tradeDate='20230406', self.openTime='000000', self.closeTime='000959',self.symbol='BTCUSDT',self.open='28015', self.close='27919'
2023-04-06 00:10:01,856:INFO:testStrategy:main.py:102:handleKline:185174: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
12236  20230405   232000    232959  1680708599    27938  27997.1
12237  20230405   233000    233959  1680709199  27997.1  28064.1
12238  20230405   234000    234959  1680709799    28064    28085
12239  20230405   235000    235959  1680710399  28085.1  28014.9
12240  20230406   000000    000959  1680710999    28015    27919
2023-04-06 00:10:01,856:INFO:testStrategy:main.py:103:handleKline:185174: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': True, 'isOpen': False, 'isClose': True, 'isTrig': False, 'isCorr': False}

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=18922 

self.closeSec=1680711599, self.tradeDate='20230406', self.openTime='001000', self.closeTime='001959', self.symbol='BTCUSDT', self.open='27919', self.close='27905'
127.0.0.1 - - [06/Apr/2023 00:20:05] "POST / HTTP/1.1" 200 -
2023-04-06 00:20:10,755:INFO:testStrategy:main.py:101:handleKline:185174: self.closeSec=1680711599, self.tradeDate='20230406', self.openTime='001000', self.closeTime='001959',self.symbol='BTCUSDT',self.open='27919', self.close='27905'
2023-04-06 00:20:11,096:INFO:testStrategy:main.py:102:handleKline:185174: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
12237  20230405   233000    233959  1680709199  27997.1  28064.1
12238  20230405   234000    234959  1680709799    28064    28085
12239  20230405   235000    235959  1680710399  28085.1  28014.9
12240  20230406   000000    000959  1680710999    28015    27919
12241  20230406   001000    001959  1680711599    27919    27905
2023-04-06 00:20:11,097:INFO:testStrategy:main.py:103:handleKline:185174: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': True, 'isOpen': False, 'isClose': True, 'isTrig': False, 'isCorr': False}


## /root/FIL/strategy/sr_min/log.txt ----- -----

--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=0, self.total=1000000.0, self.flagDict['side']='', self.tradeCount=0, self.count=33274
self.closeSec=1680711599, self.tradeDate='20230406', self.openTime='001500', self.closeTime='001959', self.symbol='BTCUSDT', self.open=27881.6, self.close=27905.0, self.high=27905.0, self.low=27775.0, self.vol=9712.692, self.amt=270368502.4485 
127.0.0.1 - - [06/Apr/2023 00:20:03] "POST / HTTP/1.1" 200 -
2023-04-06 00:20:08,436:INFO:sr_min:main.py:172:handleKline:449472: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5759  20230405   235500    235959  ...         0.0        0.0       0
5760  20230406   000000    000459  ...         0.0        0.0       0
5761  20230406   000500    000959  ...         0.0        0.0       0
5762  20230406   001000    001459  ...         0.0        0.0       0
5763  20230406   001500    001959  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-04-06 00:20:08,466:INFO:sr_min:main.py:175:handleKline:449472: self.closeSec=1680711599, self.tradeDate='20230406', self.openTime='001500', self.closeTime='001959',self.symbol='BTCUSDT',self.open=27881.6, self.close=27905.0, self.high=27905.0, self.low=27775.0, self.vol=9712.692, self.amt=270368502.4485, ukdf['pct'].iloc[-1]=0.000836 , ukdf['amount'].iloc[-1]=270368502.4485, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5763, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': []}
type(curSign)=<class 'int'>, curSign=0, self.sign=0
--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=0, self.total=1000000.0, self.flagDict['side']='', self.tradeCount=0, self.count=33275
self.closeSec=1680711899, self.tradeDate='20230406', self.openTime='002000', self.closeTime='002459', self.symbol='BTCUSDT', self.open=27905.0, self.close=27934.0, self.high=27937.5, self.low=27875.4, self.vol=2654.023, self.amt=74063466.3167 
127.0.0.1 - - [06/Apr/2023 00:25:01] "POST / HTTP/1.1" 200 -
2023-04-06 00:25:01,578:INFO:sr_min:main.py:172:handleKline:449472: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5760  20230406   000000    000459  ...         0.0        0.0       0
5761  20230406   000500    000959  ...         0.0        0.0       0
5762  20230406   001000    001459  ...         0.0        0.0       0
5763  20230406   001500    001959  ...         0.0        0.0       0
5764  20230406   002000    002459  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-04-06 00:25:01,578:INFO:sr_min:main.py:175:handleKline:449472: self.closeSec=1680711899, self.tradeDate='20230406', self.openTime='002000', self.closeTime='002459',self.symbol='BTCUSDT',self.open=27905.0, self.close=27934.0, self.high=27937.5, self.low=27875.4, self.vol=2654.023, self.amt=74063466.3167, ukdf['pct'].iloc[-1]=0.001039 , ukdf['amount'].iloc[-1]=74063466.3167, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5764, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': []}
type(curSign)=<class 'int'>, curSign=0, self.sign=0


## /root/FIL/strategy/s_rsrs/log.txt ----- -----

723  20230405   120000    155959  1680681599  ...    723  0.171421 -0.410539     NaN
724  20230405   160000    195959  1680695999  ...    724  0.165510 -0.420636     NaN

[5 rows x 15 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '52.088', 'enterprice': '28398.8', 'countrevence': '0', 'unrealprofit': '-7662.1448', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '28545.9', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'numpy.int64'>, curSign=-9223372036854775808, self.sign=-1
127.0.0.1 - - [06/Apr/2023 00:00:02] "POST / HTTP/1.1" 200 -
--handleKline--:  version='2.0.0', self.name='s_rsrs', self.symbol='BTCUSDT', interval='4h', intervalSec=14400, wid=25, thd=0.6, self.sign=-1, self.total=1477757.4577056, self.flagDict['side']='sell', self.tradeCount=29, self.count=788
self.closeSec=1680710399, self.tradeDate='20230405', self.openTime='200000', self.closeTime='235959', self.symbol='BTCUSDT', self.open=28543.9, self.close=28014.9, self.high=28741.0, self.low=27830.1, self.vol=208759.52, self.amt=5901306122.13175 
2023-04-06 00:00:02,654:INFO:s_rsrs:main.py:141:handleKline:185271: self.closeSec=1680710399, self.tradeDate='20230405', self.openTime='200000', self.closeTime='235959',self.symbol='BTCUSDT',self.open=28543.9, self.close=28014.9, self.high=28741.0, self.low=27830.1, self.vol=208759.52, self.amt=5901306122.13175 
2023-04-06 00:00:02,677:INFO:s_rsrs:main.py:142:handleKline:185271: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime  ...         vol           amt       pct
721  20230405   040000    075959  ...   40576.232  1.143864e+09 -0.000564
722  20230405   080000    115959  ...  125905.052  3.592485e+09  0.013529
723  20230405   120000    155959  ...   38202.006  1.089692e+09 -0.000715
724  20230405   160000    195959  ...   37263.294  1.062696e+09  0.000992
725  20230405   200000    235959  ...  208759.520  5.901306e+09 -0.018536

[5 rows x 11 columns]
2023-04-06 00:00:05,077:INFO:s_rsrs:main.py:151:handleKline:185271: df_s.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec  ...  index      beta    zscore  signal
721  20230405   040000    075959  1680652799  ...    721  0.225672 -0.217109     NaN
722  20230405   080000    115959  1680667199  ...    722  0.199048 -0.310848     NaN
723  20230405   120000    155959  1680681599  ...    723  0.171421 -0.410539     NaN
724  20230405   160000    195959  1680695999  ...    724  0.165510 -0.420636     NaN
725  20230405   200000    235959  1680710399  ...    725  0.119619 -0.602008    -1.0

[5 rows x 15 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '52.088', 'enterprice': '28398.8', 'countrevence': '0', 'unrealprofit': '19953.33424399072', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '28015.73030556', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'numpy.int64'>, curSign=-1, self.sign=-1


