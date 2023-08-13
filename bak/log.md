# 20230814 00:26:01

## /root/FIL/strategy/amihud/log.txt ----- -----

--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=373746.4768026, self.flagDict['side']='sell', self.tradeCount=2, self.count=26368
self.closeSec=1691943599, self.tradeDate='20230814', self.openTime='001500', self.closeTime='001959', self.symbol='BTCUSDT', self.open=29320.1, self.close=29331.7, self.high=29334.5, self.low=29316.2, self.vol=942.613, self.amt=27645339.7267 
127.0.0.1 - - [14/Aug/2023 00:20:01] "POST / HTTP/1.1" 200 -
2023-08-14 00:20:06,287:INFO:amihud:main.py:172:handleKline:2219019: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5759  20230813   235500    235959  ...         0.0        0.0       0
5760  20230814   000000    000459  ...         0.0        0.0       0
5761  20230814   000500    000959  ...         0.0        0.0       0
5762  20230814   001000    001459  ...         0.0        0.0       0
5763  20230814   001500    001959  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-08-14 00:20:06,328:INFO:amihud:main.py:175:handleKline:2219019: self.closeSec=1691943599, self.tradeDate='20230814', self.openTime='001500', self.closeTime='001959',self.symbol='BTCUSDT',self.open=29320.1, self.close=29331.7, self.high=29334.5, self.low=29316.2, self.vol=942.613, self.amt=27645339.7267, ukdf['pct'].iloc[-1]=0.000396 , ukdf['amount'].iloc[-1]=27645339.7267, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5763, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '13.926', 'enterprice': '26864.9', 'countrevence': '0', 'unrealprofit': '-34384.7349587313', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '29334.00347255', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1
127.0.0.1 - - [14/Aug/2023 00:25:00] "POST / HTTP/1.1" 200 -
--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=373746.4768026, self.flagDict['side']='sell', self.tradeCount=2, self.count=26369
self.closeSec=1691943899, self.tradeDate='20230814', self.openTime='002000', self.closeTime='002459', self.symbol='BTCUSDT', self.open=29331.7, self.close=29346.1, self.high=29346.2, self.low=29330.4, self.vol=629.411, self.amt=18464942.1322 
2023-08-14 00:25:00,787:INFO:amihud:main.py:172:handleKline:2219019: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5760  20230814   000000    000459  ...         0.0        0.0       0
5761  20230814   000500    000959  ...         0.0        0.0       0
5762  20230814   001000    001459  ...         0.0        0.0       0
5763  20230814   001500    001959  ...         0.0        0.0       0
5764  20230814   002000    002459  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-08-14 00:25:00,788:INFO:amihud:main.py:175:handleKline:2219019: self.closeSec=1691943899, self.tradeDate='20230814', self.openTime='002000', self.closeTime='002459',self.symbol='BTCUSDT',self.open=29331.7, self.close=29346.1, self.high=29346.2, self.low=29330.4, self.vol=629.411, self.amt=18464942.1322, ukdf['pct'].iloc[-1]=0.000491 , ukdf['amount'].iloc[-1]=18464942.1322, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5764, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '13.926', 'enterprice': '26864.9', 'countrevence': '0', 'unrealprofit': '-34554.5838', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '29346.2', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1


## /root/FIL/strategy/factorcheck/log.txt ----- -----


self.closeSec=1691943599, self.tradeDate='20230814', self.openTime='001500', self.closeTime='001959', self.symbol='BTCUSDT', self.open=29320.1, self.close=29331.7, self.high=29334.5, self.low=29316.2 
127.0.0.1 - - [14/Aug/2023 00:20:01] "POST / HTTP/1.1" 200 -
2023-08-14 00:20:04,337:INFO:factorcheck2:main.py:126:handleKline:2218005: self.closeSec=1691943599, self.tradeDate='20230814', self.openTime='001500', self.closeTime='001959',self.symbol='BTCUSDT',self.open=29320.1, self.close=29331.7, self.high=29334.5, self.low=29316.2   
2023-08-14 00:20:05,368:INFO:factorcheck2:main.py:127:handleKline:2218005: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime    closeSec  ...      low       pct  index  idx
1439  20230813   235500    235959  1691942399  ...  29362.8  0.000000   1727    5
1440  20230814   000000    000459  1691942699  ...  29344.0 -0.000552   1440    0
1441  20230814   000500    000959  1691942999  ...  29322.0 -0.000838   1441    1
1442  20230814   001000    001459  1691943299  ...  29320.1 -0.000065   1442    2
1443  20230814   001500    001959  1691943599  ...  29316.2  0.000396   1443    3

[5 rows x 11 columns]
2023-08-14 00:20:05,378:INFO:factorcheck2:main.py:128:handleKline:2218005: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': True, 'isOpenSell': False, 'isCloseBuy': False, 'isCloseSell': False, 'isOpen': True, 'isClose': False, 'isTrig': True}
127.0.0.1 - - [14/Aug/2023 00:25:00] "POST / HTTP/1.1" 200 -

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=0, self.factor=0.6796020063948204, self.count=26371 

self.closeSec=1691943899, self.tradeDate='20230814', self.openTime='002000', self.closeTime='002459', self.symbol='BTCUSDT', self.open=29331.7, self.close=29346.1, self.high=29346.2, self.low=29330.4 
2023-08-14 00:25:00,746:INFO:factorcheck2:main.py:126:handleKline:2218005: self.closeSec=1691943899, self.tradeDate='20230814', self.openTime='002000', self.closeTime='002459',self.symbol='BTCUSDT',self.open=29331.7, self.close=29346.1, self.high=29346.2, self.low=29330.4   
2023-08-14 00:25:00,765:INFO:factorcheck2:main.py:127:handleKline:2218005: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime    closeSec  ...      low       pct  index  idx
1440  20230814   000000    000459  1691942699  ...  29344.0 -0.000552   1440    0
1441  20230814   000500    000959  1691942999  ...  29322.0 -0.000838   1441    1
1442  20230814   001000    001459  1691943299  ...  29320.1 -0.000065   1442    2
1443  20230814   001500    001959  1691943599  ...  29316.2  0.000396   1443    3
1444  20230814   002000    002459  1691943899  ...  29330.4  0.000491   1444    4

[5 rows x 11 columns]
2023-08-14 00:25:00,765:INFO:factorcheck2:main.py:128:handleKline:2218005: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': True, 'isOpenSell': False, 'isCloseBuy': False, 'isCloseSell': False, 'isOpen': True, 'isClose': False, 'isTrig': True}


## /root/FIL/strategy/logic/log.txt ----- -----

2023-08-14 00:00:19,003:DEBUG:logic:main.py:463:getModel:2218526: df_s.iloc[-5:,:] :
          date closeTime     open  ...    alpha58   alpha67   alpha72
5802  20230813    212959  29380.4  ...  47.500000  0.459415  0.623291
5803  20230813    215959  29362.4  ...  47.916667  0.460359  0.635728
5804  20230813    222959  29363.4  ...  47.916667  0.463747  0.644826
5805  20230813    225959  29367.4  ...  47.916667  0.458475  0.657822
5806  20230813    232959  29360.4  ...  47.500000  0.452106  0.675422

[5 rows x 33 columns]
0.5422794117647058
acc is : 0.5422794117647058
2023-08-14 00:00:19,074:INFO:logic:main.py:468:getModel:2218526: df_pred.iloc[-5:,:] :
     pred    prob_0    prob_1  actual  ...       nav  sign  cost_        bm
539     1  0.497269  0.502731       1  ...  1.005182  -1.0    0.0  0.993013
540     0  0.502061  0.497939       1  ...  1.005049  -1.0    0.0  0.993145
541     0  0.504006  0.495994       0  ...  1.005288  -1.0    0.0  0.992908
542     0  0.501267  0.498733       0  ...  1.005579  -1.0    0.0  0.992621
543     1  0.499276  0.500724       1  ...  1.005202  -1.0    0.0  0.992993

[5 rows x 10 columns]
2023-08-14 00:00:19,087:INFO:logic:main.py:478:getModel:2218526: df_panel.iloc[-5:,:] :
    pred    prob_0    prob_1  actual  ...       nav  sign  cost_        bm
45     1  0.497470  0.502530       1  ...  1.005182  -1.0    0.0  0.990728
46     0  0.502041  0.497959       1  ...  1.005049  -1.0    0.0  0.993743
47     0  0.503983  0.496017       0  ...  1.005288  -1.0    0.0  0.993506
48     0  0.501137  0.498863       0  ...  1.005579  -1.0    0.0  0.991009
49     1  0.499276  0.500724       1  ...  1.005202  -1.0    0.0  0.992993

[5 rows x 10 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '24.049', 'enterprice': '29479.7', 'countrevence': '0', 'unrealprofit': '2758.4203', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '29365', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}


## /root/FIL/strategy/modifiedmom/log.txt ----- -----

2023-08-14 00:00:04,087:INFO:modifiedmom:main.py:319:handleOrderFilled:2218259: handleOrderFilled: data=OrderType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'clientorderid': '42853F1691942403477I0L59', 'symbol': 'BTCUSDT', 'gatewayorderid': 1691942403886175, 'quantity': '24.56', 'price': '29362.9', 'stopprice': '0', 'ordertype': '', 'side': 'BUY', 'status': 'FILLED', 'positionside': 'LONG', 'createtime': 1691942402629, 'updatetime': 1691942403886, 'tradetype': 'usdt', 'selfid': 42853, 'filltrades': [TradeType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'tradeid': 1691942403886, 'clientorderid': '42853F1691942403477I0L59', 'price': '29362.9', 'quantity': '24.56', 'commission': '721.152824', 'commissionasset': 'USDT', 'tradetime': 1691942403886, 'tradetype': 'usdt', 'gatetype': 'simulator', 'handletime': 1691942403886}], 'gatetype': 'simulator', 'handletime': 0}
127.0.0.1 - - [14/Aug/2023 00:00:04] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=13184 

self.closeSec=1691942999, self.tradeDate='20230814', self.openTime='000000', self.closeTime='000959', self.symbol='BTCUSDT', self.open='29362.8', self.close='29324.8'
127.0.0.1 - - [14/Aug/2023 00:10:01] "POST / HTTP/1.1" 200 -
2023-08-14 00:10:01,131:INFO:modifiedmom:main.py:144:handleKline:2218259: self.closeSec=1691942999, self.tradeDate='20230814', self.openTime='000000', self.closeTime='000959',self.symbol='BTCUSDT',self.open='29362.8', self.close='29324.8'
2023-08-14 00:10:01,139:INFO:modifiedmom:main.py:145:handleKline:2218259: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec     open    close       pct
572  20230813   232000    232959  1691940599  29363.9  29351.9 -0.000405
573  20230813   233000    233959  1691941199  29351.9    29362  0.000344
574  20230813   234000    234959  1691941799  29362.1  29366.8  0.000163
575  20230813   235000    235959  1691942399  29366.8  29362.8 -0.000136
576  20230814   000000    000959  1691942999  29362.8  29324.8 -0.001294
2023-08-14 00:10:01,139:INFO:modifiedmom:main.py:146:handleKline:2218259: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': True, 'isOpen': False, 'isClose': True, 'isTrig': False}

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=13185 

self.closeSec=1691943599, self.tradeDate='20230814', self.openTime='001000', self.closeTime='001959', self.symbol='BTCUSDT', self.open='29324.8', self.close='29331.7'
127.0.0.1 - - [14/Aug/2023 00:20:04] "POST / HTTP/1.1" 200 -
2023-08-14 00:20:06,338:INFO:modifiedmom:main.py:144:handleKline:2218259: self.closeSec=1691943599, self.tradeDate='20230814', self.openTime='001000', self.closeTime='001959',self.symbol='BTCUSDT',self.open='29324.8', self.close='29331.7'
2023-08-14 00:20:06,937:INFO:modifiedmom:main.py:145:handleKline:2218259: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec     open    close       pct
573  20230813   233000    233959  1691941199  29351.9    29362  0.000344
574  20230813   234000    234959  1691941799  29362.1  29366.8  0.000163
575  20230813   235000    235959  1691942399  29366.8  29362.8 -0.000136
576  20230814   000000    000959  1691942999  29362.8  29324.8 -0.001294
577  20230814   001000    001959  1691943599  29324.8  29331.7  0.000235
2023-08-14 00:20:06,946:INFO:modifiedmom:main.py:146:handleKline:2218259: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': True, 'isOpen': False, 'isClose': True, 'isTrig': False}


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

2023-08-14 00:00:02,096:INFO:pyemd2:main.py:127:handleKline:2217508: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}
2023-08-14 00:00:02,165:INFO:pyemd2:main.py:190:insertFactor:2217508: curDateTime:8140000, name:pyemd2, symbol:BTCUSDT, tradeDate:20230813, closeTime:235959, close:29362.8, total:977345.2184116, pct_pre:-0.0013383970487326202, thd:0.1023931047128509, side:sell 

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=13187 

self.closeSec=1691942999, self.tradeDate='20230814', self.openTime='000000', self.closeTime='000959', self.symbol='BTCUSDT', self.open='29362.8', self.close='29324.8'
2023-08-14 00:10:01,142:INFO:pyemd2:main.py:125:handleKline:2217508: self.closeSec=1691942999, self.tradeDate='20230814', self.openTime='000000', self.closeTime='000959',self.symbol='BTCUSDT',self.open='29362.8', self.close='29324.8'
2023-08-14 00:10:01,148:INFO:pyemd2:main.py:126:handleKline:2217508: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
17420  20230813   232000    232959  1691940599  29363.9  29351.9
17421  20230813   233000    233959  1691941199  29351.9    29362
17422  20230813   234000    234959  1691941799  29362.1  29366.8
17423  20230813   235000    235959  1691942399  29366.8  29362.8
17424  20230814   000000    000959  1691942999  29362.8  29324.8
2023-08-14 00:10:01,148:INFO:pyemd2:main.py:127:handleKline:2217508: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}
127.0.0.1 - - [14/Aug/2023 00:10:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=13188 

self.closeSec=1691943599, self.tradeDate='20230814', self.openTime='001000', self.closeTime='001959', self.symbol='BTCUSDT', self.open='29324.8', self.close='29331.7'
127.0.0.1 - - [14/Aug/2023 00:20:04] "POST / HTTP/1.1" 200 -
2023-08-14 00:20:08,199:INFO:pyemd2:main.py:125:handleKline:2217508: self.closeSec=1691943599, self.tradeDate='20230814', self.openTime='001000', self.closeTime='001959',self.symbol='BTCUSDT',self.open='29324.8', self.close='29331.7'
2023-08-14 00:20:08,272:INFO:pyemd2:main.py:126:handleKline:2217508: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
17421  20230813   233000    233959  1691941199  29351.9    29362
17422  20230813   234000    234959  1691941799  29362.1  29366.8
17423  20230813   235000    235959  1691942399  29366.8  29362.8
17424  20230814   000000    000959  1691942999  29362.8  29324.8
17425  20230814   001000    001959  1691943599  29324.8  29331.7
2023-08-14 00:20:08,272:INFO:pyemd2:main.py:127:handleKline:2217508: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}


## /root/FIL/strategy/similarity/log.txt ----- -----

127.0.0.1 - - [14/Aug/2023 00:00:04] "POST / HTTP/1.1" 200 -
2023-08-14 00:00:04,287:INFO:testStrategy:main.py:308:handleOrderFilled:2217133: handleOrderFilled: data=OrderType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'clientorderid': '42854F1691942403515I0L2', 'symbol': 'BTCUSDT', 'gatewayorderid': 1691942403935409, 'quantity': '36.595', 'price': '29362.8', 'stopprice': '0', 'ordertype': '', 'side': 'SELL', 'status': 'FILLED', 'positionside': 'SHORT', 'createtime': 1691942402666, 'updatetime': 1691942403935, 'tradetype': 'usdt', 'selfid': 42854, 'filltrades': [TradeType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'tradeid': 1691942403935, 'clientorderid': '42854F1691942403515I0L2', 'price': '29362.8', 'quantity': '36.595', 'commission': '1074.531666', 'commissionasset': 'USDT', 'tradetime': 1691942403935, 'tradetype': 'usdt', 'gatetype': 'simulator', 'handletime': 1691942403935}], 'gatetype': 'simulator', 'handletime': 0}

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=13187 

self.closeSec=1691942999, self.tradeDate='20230814', self.openTime='000000', self.closeTime='000959', self.symbol='BTCUSDT', self.open='29362.8', self.close='29324.8'
127.0.0.1 - - [14/Aug/2023 00:10:01] "POST / HTTP/1.1" 200 -
2023-08-14 00:10:01,130:INFO:testStrategy:main.py:101:handleKline:2217133: self.closeSec=1691942999, self.tradeDate='20230814', self.openTime='000000', self.closeTime='000959',self.symbol='BTCUSDT',self.open='29362.8', self.close='29324.8'
2023-08-14 00:10:01,150:INFO:testStrategy:main.py:102:handleKline:2217133: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
12236  20230813   232000    232959  1691940599  29363.9  29351.9
12237  20230813   233000    233959  1691941199  29351.9    29362
12238  20230813   234000    234959  1691941799  29362.1  29366.8
12239  20230813   235000    235959  1691942399  29366.8  29362.8
12240  20230814   000000    000959  1691942999  29362.8  29324.8
2023-08-14 00:10:01,150:INFO:testStrategy:main.py:103:handleKline:2217133: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': True, 'isOpen': False, 'isClose': True, 'isTrig': False, 'isCorr': False}

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=13188 

self.closeSec=1691943599, self.tradeDate='20230814', self.openTime='001000', self.closeTime='001959', self.symbol='BTCUSDT', self.open='29324.8', self.close='29331.7'
127.0.0.1 - - [14/Aug/2023 00:20:04] "POST / HTTP/1.1" 200 -
2023-08-14 00:20:07,930:INFO:testStrategy:main.py:101:handleKline:2217133: self.closeSec=1691943599, self.tradeDate='20230814', self.openTime='001000', self.closeTime='001959',self.symbol='BTCUSDT',self.open='29324.8', self.close='29331.7'
2023-08-14 00:20:08,155:INFO:testStrategy:main.py:102:handleKline:2217133: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
12237  20230813   233000    233959  1691941199  29351.9    29362
12238  20230813   234000    234959  1691941799  29362.1  29366.8
12239  20230813   235000    235959  1691942399  29366.8  29362.8
12240  20230814   000000    000959  1691942999  29362.8  29324.8
12241  20230814   001000    001959  1691943599  29324.8  29331.7
2023-08-14 00:20:08,157:INFO:testStrategy:main.py:103:handleKline:2217133: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': True, 'isOpen': False, 'isClose': True, 'isTrig': False, 'isCorr': False}


## /root/FIL/strategy/sr_min/log.txt ----- -----

--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=1, self.total=996015.990996, self.flagDict['side']='buy', self.tradeCount=1, self.count=26368
self.closeSec=1691943599, self.tradeDate='20230814', self.openTime='001500', self.closeTime='001959', self.symbol='BTCUSDT', self.open=29320.1, self.close=29331.7, self.high=29334.5, self.low=29316.2, self.vol=942.613, self.amt=27645339.7267 
127.0.0.1 - - [14/Aug/2023 00:20:01] "POST / HTTP/1.1" 200 -
2023-08-14 00:20:06,217:INFO:sr_min:main.py:172:handleKline:2219263: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5759  20230813   235500    235959  ...         0.0        0.0       0
5760  20230814   000000    000459  ...         0.0        0.0       0
5761  20230814   000500    000959  ...         0.0        0.0       0
5762  20230814   001000    001459  ...         0.0        0.0       0
5763  20230814   001500    001959  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-08-14 00:20:06,247:INFO:sr_min:main.py:175:handleKline:2219263: self.closeSec=1691943599, self.tradeDate='20230814', self.openTime='001500', self.closeTime='001959',self.symbol='BTCUSDT',self.open=29320.1, self.close=29331.7, self.high=29334.5, self.low=29316.2, self.vol=942.613, self.amt=27645339.7267, ukdf['pct'].iloc[-1]=0.000396 , ukdf['amount'].iloc[-1]=27645339.7267, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5763, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '37.141', 'enterprice': '26844', 'countrevence': '0', 'unrealprofit': '92481.21897397955', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '29334.00347255', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=1
--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=1, self.total=996015.990996, self.flagDict['side']='buy', self.tradeCount=1, self.count=26369
self.closeSec=1691943899, self.tradeDate='20230814', self.openTime='002000', self.closeTime='002459', self.symbol='BTCUSDT', self.open=29331.7, self.close=29346.1, self.high=29346.2, self.low=29330.4, self.vol=629.411, self.amt=18464942.1322 
127.0.0.1 - - [14/Aug/2023 00:25:00] "POST / HTTP/1.1" 200 -
2023-08-14 00:25:00,787:INFO:sr_min:main.py:172:handleKline:2219263: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5760  20230814   000000    000459  ...         0.0        0.0       0
5761  20230814   000500    000959  ...         0.0        0.0       0
5762  20230814   001000    001459  ...         0.0        0.0       0
5763  20230814   001500    001959  ...         0.0        0.0       0
5764  20230814   002000    002459  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-08-14 00:25:00,787:INFO:sr_min:main.py:175:handleKline:2219263: self.closeSec=1691943899, self.tradeDate='20230814', self.openTime='002000', self.closeTime='002459',self.symbol='BTCUSDT',self.open=29331.7, self.close=29346.1, self.high=29346.2, self.low=29330.4, self.vol=629.411, self.amt=18464942.1322, ukdf['pct'].iloc[-1]=0.000491 , ukdf['amount'].iloc[-1]=18464942.1322, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5764, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '37.141', 'enterprice': '26844', 'countrevence': '0', 'unrealprofit': '92934.2102', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '29346.2', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=1


## /root/FIL/strategy/s_rsrs/log.txt ----- -----

723  20230813   120000    155959  1691913599  ...    723  0.960580  1.105825     1.0
724  20230813   160000    195959  1691927999  ...    724  1.004451  1.181638     1.0

[5 rows x 15 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '51.457', 'enterprice': '29884.4', 'countrevence': '0', 'unrealprofit': '-26211.55224891294', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '29375.01250658', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'numpy.int64'>, curSign=1, self.sign=1
127.0.0.1 - - [14/Aug/2023 00:00:01] "POST / HTTP/1.1" 200 -
--handleKline--:  version='2.0.0', self.name='s_rsrs', self.symbol='BTCUSDT', interval='4h', intervalSec=14400, wid=25, thd=0.6, self.sign=1, self.total=1536223.8092292, self.flagDict['side']='buy', self.tradeCount=19, self.count=549
self.closeSec=1691942399, self.tradeDate='20230813', self.openTime='200000', self.closeTime='235959', self.symbol='BTCUSDT', self.open=29374.0, self.close=29362.9, self.high=29382.6, self.low=29349.0, self.vol=9903.451, self.amt=290847556.2893 
2023-08-14 00:00:01,671:INFO:s_rsrs:main.py:141:handleKline:2218689: self.closeSec=1691942399, self.tradeDate='20230813', self.openTime='200000', self.closeTime='235959',self.symbol='BTCUSDT',self.open=29374.0, self.close=29362.9, self.high=29382.6, self.low=29349.0, self.vol=9903.451, self.amt=290847556.2893 
2023-08-14 00:00:01,685:INFO:s_rsrs:main.py:142:handleKline:2218689: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime  ...        vol           amt       pct
721  20230813   040000    075959  ...   5810.372  1.708853e+08  0.000449
722  20230813   080000    115959  ...   9679.096  2.847198e+08 -0.000642
723  20230813   120000    155959  ...  11731.661  3.446410e+08 -0.000554
724  20230813   160000    195959  ...   7336.398  2.156099e+08 -0.000391
725  20230813   200000    235959  ...   9903.451  2.908476e+08 -0.000378

[5 rows x 11 columns]
2023-08-14 00:00:02,529:INFO:s_rsrs:main.py:151:handleKline:2218689: df_s.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec  ...  index      beta    zscore  signal
721  20230813   040000    075959  1691884799  ...    721  1.431491  2.280324     1.0
722  20230813   080000    115959  1691899199  ...    722  1.023916  1.279311     1.0
723  20230813   120000    155959  1691913599  ...    723  0.960580  1.105825     1.0
724  20230813   160000    195959  1691927999  ...    724  1.004451  1.181638     1.0
725  20230813   200000    235959  1691942399  ...    725  1.041921  1.239832     1.0

[5 rows x 15 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '51.457', 'enterprice': '29884.4', 'countrevence': '0', 'unrealprofit': '-26797.84201467429', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '29363.61872603', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'numpy.int64'>, curSign=1, self.sign=1


