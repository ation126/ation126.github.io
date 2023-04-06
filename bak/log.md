# 20230407 00:26:01

## /root/FIL/strategy/amihud/log.txt ----- -----

--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=993672.4896432, self.flagDict['side']='sell', self.tradeCount=2, self.count=37564
self.closeSec=1680797999, self.tradeDate='20230407', self.openTime='001500', self.closeTime='001959', self.symbol='BTCUSDT', self.open=28091.9, self.close=28113.2, self.high=28129.9, self.low=28091.8, self.vol=1073.491, self.amt=30176906.9101 
127.0.0.1 - - [07/Apr/2023 00:20:04] "POST / HTTP/1.1" 200 -
2023-04-07 00:20:09,740:INFO:amihud:main.py:172:handleKline:200676: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5759  20230406   235500    235959  ...         0.0        0.0       0
5760  20230407   000000    000459  ...         0.0        0.0       0
5761  20230407   000500    000959  ...         0.0        0.0       0
5762  20230407   001000    001459  ...         0.0        0.0       0
5763  20230407   001500    001959  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-04-07 00:20:09,761:INFO:amihud:main.py:175:handleKline:200676: self.closeSec=1680797999, self.tradeDate='20230407', self.openTime='001500', self.closeTime='001959',self.symbol='BTCUSDT',self.open=28091.9, self.close=28113.2, self.high=28129.9, self.low=28091.8, self.vol=1073.491, self.amt=30176906.9101, ukdf['pct'].iloc[-1]=0.000762 , ukdf['amount'].iloc[-1]=30176906.9101, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5763, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '60.176', 'enterprice': '16529.3', 'countrevence': '0', 'unrealprofit': '-696374.7248', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '28101.6', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1
--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=993672.4896432, self.flagDict['side']='sell', self.tradeCount=2, self.count=37565
self.closeSec=1680798299, self.tradeDate='20230407', self.openTime='002000', self.closeTime='002459', self.symbol='BTCUSDT', self.open=28113.1, self.close=28096.7, self.high=28119.5, self.low=28090.3, self.vol=1046.384, self.amt=29405630.0584 
127.0.0.1 - - [07/Apr/2023 00:25:01] "POST / HTTP/1.1" 200 -
2023-04-07 00:25:01,593:INFO:amihud:main.py:172:handleKline:200676: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5760  20230407   000000    000459  ...         0.0        0.0       0
5761  20230407   000500    000959  ...         0.0        0.0       0
5762  20230407   001000    001459  ...         0.0        0.0       0
5763  20230407   001500    001959  ...         0.0        0.0       0
5764  20230407   002000    002459  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-04-07 00:25:01,593:INFO:amihud:main.py:175:handleKline:200676: self.closeSec=1680798299, self.tradeDate='20230407', self.openTime='002000', self.closeTime='002459',self.symbol='BTCUSDT',self.open=28113.1, self.close=28096.7, self.high=28119.5, self.low=28090.3, self.vol=1046.384, self.amt=29405630.0584, ukdf['pct'].iloc[-1]=-0.000587 , ukdf['amount'].iloc[-1]=29405630.0584, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5764, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '60.176', 'enterprice': '16529.3', 'countrevence': '0', 'unrealprofit': '-695923.4048', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '28094.1', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1


## /root/FIL/strategy/factorcheck/log.txt ----- -----


self.closeSec=1680797999, self.tradeDate='20230407', self.openTime='001500', self.closeTime='001959', self.symbol='BTCUSDT', self.open=28091.9, self.close=28113.2, self.high=28129.9, self.low=28091.8 
127.0.0.1 - - [07/Apr/2023 00:20:03] "POST / HTTP/1.1" 200 -
2023-04-07 00:20:06,979:INFO:factorcheck2:main.py:126:handleKline:185239: self.closeSec=1680797999, self.tradeDate='20230407', self.openTime='001500', self.closeTime='001959',self.symbol='BTCUSDT',self.open=28091.9, self.close=28113.2, self.high=28129.9, self.low=28091.8   
2023-04-07 00:20:08,108:INFO:factorcheck2:main.py:127:handleKline:185239: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime    closeSec  ...      low       pct  index  idx
1439  20230406   235500    235959  1680796799  ...  28071.1 -0.000591   1727    5
1440  20230407   000000    000459  1680797099  ...  28078.0  0.000755   1440    0
1441  20230407   000500    000959  1680797399  ...  28071.3 -0.000391   1441    1
1442  20230407   001000    001459  1680797699  ...  28074.9  0.000082   1442    2
1443  20230407   001500    001959  1680797999  ...  28091.8  0.000762   1443    3

[5 rows x 11 columns]
2023-04-07 00:20:08,109:INFO:factorcheck2:main.py:128:handleKline:185239: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': True, 'isOpenSell': False, 'isCloseBuy': False, 'isCloseSell': False, 'isOpen': True, 'isClose': False, 'isTrig': True}

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=0, self.factor=0.6427799064335586, self.count=38131 

self.closeSec=1680798299, self.tradeDate='20230407', self.openTime='002000', self.closeTime='002459', self.symbol='BTCUSDT', self.open=28113.1, self.close=28096.7, self.high=28119.5, self.low=28090.3 
127.0.0.1 - - [07/Apr/2023 00:25:01] "POST / HTTP/1.1" 200 -
2023-04-07 00:25:01,542:INFO:factorcheck2:main.py:126:handleKline:185239: self.closeSec=1680798299, self.tradeDate='20230407', self.openTime='002000', self.closeTime='002459',self.symbol='BTCUSDT',self.open=28113.1, self.close=28096.7, self.high=28119.5, self.low=28090.3   
2023-04-07 00:25:01,572:INFO:factorcheck2:main.py:127:handleKline:185239: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime    closeSec  ...      low       pct  index  idx
1440  20230407   000000    000459  1680797099  ...  28078.0  0.000755   1440    0
1441  20230407   000500    000959  1680797399  ...  28071.3 -0.000391   1441    1
1442  20230407   001000    001459  1680797699  ...  28074.9  0.000082   1442    2
1443  20230407   001500    001959  1680797999  ...  28091.8  0.000762   1443    3
1444  20230407   002000    002459  1680798299  ...  28090.3 -0.000587   1444    4

[5 rows x 11 columns]
2023-04-07 00:25:01,572:INFO:factorcheck2:main.py:128:handleKline:185239: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': True, 'isOpenSell': False, 'isCloseBuy': False, 'isCloseSell': False, 'isOpen': True, 'isClose': False, 'isTrig': True}


## /root/FIL/strategy/logic/log.txt ----- -----

2023-04-07 00:00:34,833:DEBUG:logic:main.py:463:getModel:885513: df_s.iloc[-5:,:] :
          date closeTime     open  ...    alpha58   alpha67   alpha72
5802  20230406    212959  27894.7  ...  47.500000  0.461893  0.689754
5803  20230406    215959  27917.3  ...  47.500000  0.454864  0.689554
5804  20230406    222959  27877.0  ...  47.916667  0.463915  0.684647
5805  20230406    225959  27920.7  ...  48.333333  0.466939  0.678486
5806  20230406    232959  27935.4  ...  48.333333  0.491574  0.659431

[5 rows x 33 columns]
0.5367647058823529
acc is : 0.5367647058823529
2023-04-07 00:00:34,994:INFO:logic:main.py:468:getModel:885513: df_pred.iloc[-5:,:] :
     pred    prob_0    prob_1  actual  ...       nav  sign  cost_        bm
539     0  0.534061  0.465939       0  ...  0.943947   1.0    0.0  1.013993
540     0  0.515798  0.484202       1  ...  0.945424   1.0    0.0  1.015579
541     0  0.532022  0.467978       1  ...  0.945918   1.0    0.0  1.016110
542     0  0.523880  0.476120       1  ...  0.950080   1.0    0.0  1.020580
543     0  0.558735  0.441265       1  ...  0.950794   1.0    0.0  1.021348

[5 rows x 10 columns]
2023-04-07 00:00:35,027:INFO:logic:main.py:478:getModel:885513: df_panel.iloc[-5:,:] :
    pred    prob_0    prob_1  actual  ...       nav  sign  cost_        bm
45     0  0.534199  0.465801       0  ...  0.943947   1.0    0.0  1.014148
46     0  0.515848  0.484152       1  ...  0.945424   1.0    0.0  1.015930
47     0  0.532055  0.467945       1  ...  0.945918   1.0    0.0  1.016461
48     0  0.523381  0.476619       1  ...  0.950080   1.0    0.0  1.020001
49     0  0.558735  0.441265       1  ...  0.950794   1.0    0.0  1.021348

[5 rows x 10 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': []}


## /root/FIL/strategy/modifiedmom/log.txt ----- -----

127.0.0.1 - - [07/Apr/2023 00:00:03] "POST / HTTP/1.1" 200 -
2023-04-07 00:00:03,438:INFO:modifiedmom:main.py:319:handleOrderFilled:185213: handleOrderFilled: data=OrderType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'clientorderid': '42126F1680796802918I0L59', 'symbol': 'BTCUSDT', 'gatewayorderid': 1680796803122835, 'quantity': '24.389', 'price': '28085.5', 'stopprice': '0', 'ordertype': '', 'side': 'SELL', 'status': 'FILLED', 'positionside': 'SHORT', 'createtime': 1680796802415, 'updatetime': 1680796803122, 'tradetype': 'usdt', 'selfid': 42126, 'filltrades': [TradeType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'tradeid': 1680796803122, 'clientorderid': '42126F1680796802918I0L59', 'price': '28085.5', 'quantity': '24.389', 'commission': '684.9772595', 'commissionasset': 'USDT', 'tradetime': 1680796803122, 'tradetype': 'usdt', 'gatetype': 'simulator', 'handletime': 1680796803122}], 'gatetype': 'simulator', 'handletime': 0}
127.0.0.1 - - [07/Apr/2023 00:10:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=19064 

self.closeSec=1680797399, self.tradeDate='20230407', self.openTime='000000', self.closeTime='000959', self.symbol='BTCUSDT', self.open='28079.3', self.close='28089.5'
2023-04-07 00:10:01,615:INFO:modifiedmom:main.py:144:handleKline:185213: self.closeSec=1680797399, self.tradeDate='20230407', self.openTime='000000', self.closeTime='000959',self.symbol='BTCUSDT',self.open='28079.3', self.close='28089.5'
2023-04-07 00:10:01,637:INFO:modifiedmom:main.py:145:handleKline:185213: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec     open    close       pct
572  20230406   232000    232959  1680794999  28008.5  28058.2  0.001771
573  20230406   233000    233959  1680795599  28058.2  28141.5  0.002969
574  20230406   234000    234959  1680796199  28141.4  28086.7 -0.001947
575  20230406   235000    235959  1680796799  28086.7  28079.3 -0.000263
576  20230407   000000    000959  1680797399  28079.3  28089.5  0.000363
2023-04-07 00:10:01,637:INFO:modifiedmom:main.py:146:handleKline:185213: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': True, 'isOpen': False, 'isClose': True, 'isTrig': False}

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=19065 

self.closeSec=1680797999, self.tradeDate='20230407', self.openTime='001000', self.closeTime='001959', self.symbol='BTCUSDT', self.open='28089.4', self.close='28113.2'
127.0.0.1 - - [07/Apr/2023 00:20:05] "POST / HTTP/1.1" 200 -
2023-04-07 00:20:08,199:INFO:modifiedmom:main.py:144:handleKline:185213: self.closeSec=1680797999, self.tradeDate='20230407', self.openTime='001000', self.closeTime='001959',self.symbol='BTCUSDT',self.open='28089.4', self.close='28113.2'
2023-04-07 00:20:09,048:INFO:modifiedmom:main.py:145:handleKline:185213: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec     open    close       pct
573  20230406   233000    233959  1680795599  28058.2  28141.5  0.002969
574  20230406   234000    234959  1680796199  28141.4  28086.7 -0.001947
575  20230406   235000    235959  1680796799  28086.7  28079.3 -0.000263
576  20230407   000000    000959  1680797399  28079.3  28089.5  0.000363
577  20230407   001000    001959  1680797999  28089.4  28113.2  0.000844
2023-04-07 00:20:09,051:INFO:modifiedmom:main.py:146:handleKline:185213: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': True, 'isOpen': False, 'isClose': True, 'isTrig': False}


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

2023-04-07 00:00:02,015:INFO:pyemd2:main.py:127:handleKline:185189: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}
2023-04-07 00:00:02,142:INFO:pyemd2:main.py:190:insertFactor:185189: curDateTime:4070000, name:pyemd2, symbol:BTCUSDT, tradeDate:20230406, closeTime:235959, close:28079.3, total:978039.764104, pct_pre:-0.0009742469286149191, thd:0.43954416748385833, side:sell 

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=19065 

self.closeSec=1680797399, self.tradeDate='20230407', self.openTime='000000', self.closeTime='000959', self.symbol='BTCUSDT', self.open='28079.3', self.close='28089.5'
127.0.0.1 - - [07/Apr/2023 00:10:01] "POST / HTTP/1.1" 200 -
2023-04-07 00:10:01,593:INFO:pyemd2:main.py:125:handleKline:185189: self.closeSec=1680797399, self.tradeDate='20230407', self.openTime='000000', self.closeTime='000959',self.symbol='BTCUSDT',self.open='28079.3', self.close='28089.5'
2023-04-07 00:10:01,611:INFO:pyemd2:main.py:126:handleKline:185189: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
17420  20230406   232000    232959  1680794999  28008.5  28058.2
17421  20230406   233000    233959  1680795599  28058.2  28141.5
17422  20230406   234000    234959  1680796199  28141.4  28086.7
17423  20230406   235000    235959  1680796799  28086.7  28079.3
17424  20230407   000000    000959  1680797399  28079.3  28089.5
2023-04-07 00:10:01,611:INFO:pyemd2:main.py:127:handleKline:185189: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=19066 

self.closeSec=1680797999, self.tradeDate='20230407', self.openTime='001000', self.closeTime='001959', self.symbol='BTCUSDT', self.open='28089.4', self.close='28113.2'
127.0.0.1 - - [07/Apr/2023 00:20:05] "POST / HTTP/1.1" 200 -
2023-04-07 00:20:11,461:INFO:pyemd2:main.py:125:handleKline:185189: self.closeSec=1680797999, self.tradeDate='20230407', self.openTime='001000', self.closeTime='001959',self.symbol='BTCUSDT',self.open='28089.4', self.close='28113.2'
2023-04-07 00:20:11,611:INFO:pyemd2:main.py:126:handleKline:185189: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
17421  20230406   233000    233959  1680795599  28058.2  28141.5
17422  20230406   234000    234959  1680796199  28141.4  28086.7
17423  20230406   235000    235959  1680796799  28086.7  28079.3
17424  20230407   000000    000959  1680797399  28079.3  28089.5
17425  20230407   001000    001959  1680797999  28089.4  28113.2
2023-04-07 00:20:11,612:INFO:pyemd2:main.py:127:handleKline:185189: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}


## /root/FIL/strategy/similarity/log.txt ----- -----

127.0.0.1 - - [07/Apr/2023 00:00:03] "POST / HTTP/1.1" 200 -
2023-04-07 00:00:03,046:INFO:testStrategy:main.py:308:handleOrderFilled:185174: handleOrderFilled: data=OrderType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'clientorderid': '42125F1680796802649I0L2', 'symbol': 'BTCUSDT', 'gatewayorderid': 1680796802771179, 'quantity': '45.937', 'price': '28085.6', 'stopprice': '0', 'ordertype': '', 'side': 'BUY', 'status': 'FILLED', 'positionside': 'LONG', 'createtime': 1680796802316, 'updatetime': 1680796802771, 'tradetype': 'usdt', 'selfid': 42125, 'filltrades': [TradeType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'tradeid': 1680796802771, 'clientorderid': '42125F1680796802649I0L2', 'price': '28085.6', 'quantity': '45.937', 'commission': '1290.1682072', 'commissionasset': 'USDT', 'tradetime': 1680796802771, 'tradetype': 'usdt', 'gatetype': 'simulator', 'handletime': 1680796802771}], 'gatetype': 'simulator', 'handletime': 0}

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=19065 

self.closeSec=1680797399, self.tradeDate='20230407', self.openTime='000000', self.closeTime='000959', self.symbol='BTCUSDT', self.open='28079.3', self.close='28089.5'
127.0.0.1 - - [07/Apr/2023 00:10:01] "POST / HTTP/1.1" 200 -
2023-04-07 00:10:01,616:INFO:testStrategy:main.py:101:handleKline:185174: self.closeSec=1680797399, self.tradeDate='20230407', self.openTime='000000', self.closeTime='000959',self.symbol='BTCUSDT',self.open='28079.3', self.close='28089.5'
2023-04-07 00:10:01,627:INFO:testStrategy:main.py:102:handleKline:185174: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
12236  20230406   232000    232959  1680794999  28008.5  28058.2
12237  20230406   233000    233959  1680795599  28058.2  28141.5
12238  20230406   234000    234959  1680796199  28141.4  28086.7
12239  20230406   235000    235959  1680796799  28086.7  28079.3
12240  20230407   000000    000959  1680797399  28079.3  28089.5
2023-04-07 00:10:01,627:INFO:testStrategy:main.py:103:handleKline:185174: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': True, 'isOpen': False, 'isClose': True, 'isTrig': False, 'isCorr': False}

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=19066 

self.closeSec=1680797999, self.tradeDate='20230407', self.openTime='001000', self.closeTime='001959', self.symbol='BTCUSDT', self.open='28089.4', self.close='28113.2'
127.0.0.1 - - [07/Apr/2023 00:20:05] "POST / HTTP/1.1" 200 -
2023-04-07 00:20:10,942:INFO:testStrategy:main.py:101:handleKline:185174: self.closeSec=1680797999, self.tradeDate='20230407', self.openTime='001000', self.closeTime='001959',self.symbol='BTCUSDT',self.open='28089.4', self.close='28113.2'
2023-04-07 00:20:11,248:INFO:testStrategy:main.py:102:handleKline:185174: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
12237  20230406   233000    233959  1680795599  28058.2  28141.5
12238  20230406   234000    234959  1680796199  28141.4  28086.7
12239  20230406   235000    235959  1680796799  28086.7  28079.3
12240  20230407   000000    000959  1680797399  28079.3  28089.5
12241  20230407   001000    001959  1680797999  28089.4  28113.2
2023-04-07 00:20:11,248:INFO:testStrategy:main.py:103:handleKline:185174: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': True, 'isOpen': False, 'isClose': True, 'isTrig': False, 'isCorr': False}


## /root/FIL/strategy/sr_min/log.txt ----- -----

--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=0, self.total=1000000.0, self.flagDict['side']='', self.tradeCount=0, self.count=33562
self.closeSec=1680797999, self.tradeDate='20230407', self.openTime='001500', self.closeTime='001959', self.symbol='BTCUSDT', self.open=28091.9, self.close=28113.2, self.high=28129.9, self.low=28091.8, self.vol=1073.491, self.amt=30176906.9101 
127.0.0.1 - - [07/Apr/2023 00:20:04] "POST / HTTP/1.1" 200 -
2023-04-07 00:20:09,198:INFO:sr_min:main.py:172:handleKline:449472: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5759  20230406   235500    235959  ...         0.0        0.0       0
5760  20230407   000000    000459  ...         0.0        0.0       0
5761  20230407   000500    000959  ...         0.0        0.0       0
5762  20230407   001000    001459  ...         0.0        0.0       0
5763  20230407   001500    001959  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-04-07 00:20:09,219:INFO:sr_min:main.py:175:handleKline:449472: self.closeSec=1680797999, self.tradeDate='20230407', self.openTime='001500', self.closeTime='001959',self.symbol='BTCUSDT',self.open=28091.9, self.close=28113.2, self.high=28129.9, self.low=28091.8, self.vol=1073.491, self.amt=30176906.9101, ukdf['pct'].iloc[-1]=0.000762 , ukdf['amount'].iloc[-1]=30176906.9101, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5763, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': []}
type(curSign)=<class 'int'>, curSign=0, self.sign=0
--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=0, self.total=1000000.0, self.flagDict['side']='', self.tradeCount=0, self.count=33563
self.closeSec=1680798299, self.tradeDate='20230407', self.openTime='002000', self.closeTime='002459', self.symbol='BTCUSDT', self.open=28113.1, self.close=28096.7, self.high=28119.5, self.low=28090.3, self.vol=1046.384, self.amt=29405630.0584 
127.0.0.1 - - [07/Apr/2023 00:25:01] "POST / HTTP/1.1" 200 -
2023-04-07 00:25:01,580:INFO:sr_min:main.py:172:handleKline:449472: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5760  20230407   000000    000459  ...         0.0        0.0       0
5761  20230407   000500    000959  ...         0.0        0.0       0
5762  20230407   001000    001459  ...         0.0        0.0       0
5763  20230407   001500    001959  ...         0.0        0.0       0
5764  20230407   002000    002459  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-04-07 00:25:01,581:INFO:sr_min:main.py:175:handleKline:449472: self.closeSec=1680798299, self.tradeDate='20230407', self.openTime='002000', self.closeTime='002459',self.symbol='BTCUSDT',self.open=28113.1, self.close=28096.7, self.high=28119.5, self.low=28090.3, self.vol=1046.384, self.amt=29405630.0584, ukdf['pct'].iloc[-1]=-0.000587 , ukdf['amount'].iloc[-1]=29405630.0584, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5764, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': []}
type(curSign)=<class 'int'>, curSign=0, self.sign=0


## /root/FIL/strategy/s_rsrs/log.txt ----- -----

723  20230406   120000    155959  1680767999  ...    723  0.109884 -0.581008     NaN
724  20230406   160000    195959  1680782399  ...    724  0.129378 -0.479627     NaN

[5 rows x 15 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '52.088', 'enterprice': '28398.8', 'countrevence': '0', 'unrealprofit': '24293.8432', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '27932.4', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'numpy.int64'>, curSign=-9223372036854775808, self.sign=-1
--handleKline--:  version='2.0.0', self.name='s_rsrs', self.symbol='BTCUSDT', interval='4h', intervalSec=14400, wid=25, thd=0.6, self.sign=-1, self.total=1477757.4577056, self.flagDict['side']='sell', self.tradeCount=29, self.count=794
self.closeSec=1680796799, self.tradeDate='20230406', self.openTime='200000', self.closeTime='235959', self.symbol='BTCUSDT', self.open=27935.0, self.close=28079.3, self.high=28175.0, self.low=27724.0, self.vol=102413.306, self.amt=2862261445.91764 
127.0.0.1 - - [07/Apr/2023 00:00:01] "POST / HTTP/1.1" 200 -
2023-04-07 00:00:01,812:INFO:s_rsrs:main.py:141:handleKline:185271: self.closeSec=1680796799, self.tradeDate='20230406', self.openTime='200000', self.closeTime='235959',self.symbol='BTCUSDT',self.open=27935.0, self.close=28079.3, self.high=28175.0, self.low=27724.0, self.vol=102413.306, self.amt=2862261445.91764 
2023-04-07 00:00:01,918:INFO:s_rsrs:main.py:142:handleKline:185271: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime  ...         vol           amt       pct
721  20230406   040000    075959  ...   34158.218  9.625166e+08 -0.002660
722  20230406   080000    115959  ...   57949.765  1.623781e+09 -0.001300
723  20230406   120000    155959  ...   36721.731  1.028841e+09 -0.007846
724  20230406   160000    195959  ...   78981.475  2.200855e+09  0.001366
725  20230406   200000    235959  ...  102413.306  2.862261e+09  0.005169

[5 rows x 11 columns]
2023-04-07 00:00:04,854:INFO:s_rsrs:main.py:151:handleKline:185271: df_s.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec  ...  index      beta    zscore  signal
721  20230406   040000    075959  1680739199  ...    721  0.117422 -0.580183     NaN
722  20230406   080000    115959  1680753599  ...    722  0.112667 -0.584620     NaN
723  20230406   120000    155959  1680767999  ...    723  0.109884 -0.581008     NaN
724  20230406   160000    195959  1680782399  ...    724  0.129378 -0.479627     NaN
725  20230406   200000    235959  1680796799  ...    725  0.143949 -0.399815     NaN

[5 rows x 15 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '52.088', 'enterprice': '28398.8', 'countrevence': '0', 'unrealprofit': '16319.1704', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '28085.5', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'numpy.int64'>, curSign=-9223372036854775808, self.sign=-1


