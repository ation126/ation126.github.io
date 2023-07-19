# 20230720 00:26:01

## /root/FIL/strategy/amihud/log.txt ----- -----

--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=373746.4768026, self.flagDict['side']='sell', self.tradeCount=2, self.count=19168
self.closeSec=1689783599, self.tradeDate='20230720', self.openTime='001500', self.closeTime='001959', self.symbol='BTCUSDT', self.open=29918.0, self.close=29885.0, self.high=29918.0, self.low=29875.0, self.vol=1193.404, self.amt=35668206.8373 
127.0.0.1 - - [20/Jul/2023 00:20:01] "POST / HTTP/1.1" 200 -
2023-07-20 00:20:05,624:INFO:amihud:main.py:172:handleKline:2219019: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5759  20230719   235500    235959  ...         0.0        0.0       0
5760  20230720   000000    000459  ...         0.0        0.0       0
5761  20230720   000500    000959  ...         0.0        0.0       0
5762  20230720   001000    001459  ...         0.0        0.0       0
5763  20230720   001500    001959  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-07-20 00:20:05,634:INFO:amihud:main.py:175:handleKline:2219019: self.closeSec=1689783599, self.tradeDate='20230720', self.openTime='001500', self.closeTime='001959',self.symbol='BTCUSDT',self.open=29918.0, self.close=29885.0, self.high=29918.0, self.low=29875.0, self.vol=1193.404, self.amt=35668206.8373, ukdf['pct'].iloc[-1]=-0.001103 , ukdf['amount'].iloc[-1]=35668206.8373, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5763, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '13.926', 'enterprice': '26864.9', 'countrevence': '0', 'unrealprofit': '-42057.9126', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '29885', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1
127.0.0.1 - - [20/Jul/2023 00:25:00] "POST / HTTP/1.1" 200 -
--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=373746.4768026, self.flagDict['side']='sell', self.tradeCount=2, self.count=19169
self.closeSec=1689783899, self.tradeDate='20230720', self.openTime='002000', self.closeTime='002459', self.symbol='BTCUSDT', self.open=29885.1, self.close=29903.1, self.high=29915.9, self.low=29855.5, self.vol=1424.424, self.amt=42568882.4732 
2023-07-20 00:25:00,771:INFO:amihud:main.py:172:handleKline:2219019: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5760  20230720   000000    000459  ...         0.0        0.0       0
5761  20230720   000500    000959  ...         0.0        0.0       0
5762  20230720   001000    001459  ...         0.0        0.0       0
5763  20230720   001500    001959  ...         0.0        0.0       0
5764  20230720   002000    002459  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-07-20 00:25:00,772:INFO:amihud:main.py:175:handleKline:2219019: self.closeSec=1689783899, self.tradeDate='20230720', self.openTime='002000', self.closeTime='002459',self.symbol='BTCUSDT',self.open=29885.1, self.close=29903.1, self.high=29915.9, self.low=29855.5, self.vol=1424.424, self.amt=42568882.4732, ukdf['pct'].iloc[-1]=0.000606 , ukdf['amount'].iloc[-1]=42568882.4732, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5764, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '13.926', 'enterprice': '26864.9', 'countrevence': '0', 'unrealprofit': '-42330.34415795262', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '29904.56280037', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1


## /root/FIL/strategy/factorcheck/log.txt ----- -----


self.closeSec=1689783599, self.tradeDate='20230720', self.openTime='001500', self.closeTime='001959', self.symbol='BTCUSDT', self.open=29918.0, self.close=29885.0, self.high=29918.0, self.low=29875.0 
127.0.0.1 - - [20/Jul/2023 00:20:01] "POST / HTTP/1.1" 200 -
2023-07-20 00:20:03,873:INFO:factorcheck2:main.py:126:handleKline:2218005: self.closeSec=1689783599, self.tradeDate='20230720', self.openTime='001500', self.closeTime='001959',self.symbol='BTCUSDT',self.open=29918.0, self.close=29885.0, self.high=29918.0, self.low=29875.0   
2023-07-20 00:20:04,803:INFO:factorcheck2:main.py:127:handleKline:2218005: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime    closeSec  ...      low       pct  index  idx
1439  20230719   235500    235959  1689782399  ...  29926.6 -0.000688   1727    5
1440  20230720   000000    000459  1689782699  ...  29929.3 -0.000371   1440    0
1441  20230720   000500    000959  1689782999  ...  29896.0  0.000080   1441    1
1442  20230720   001000    001459  1689783299  ...  29894.4 -0.000458   1442    2
1443  20230720   001500    001959  1689783599  ...  29875.0 -0.001103   1443    3

[5 rows x 11 columns]
2023-07-20 00:20:04,803:INFO:factorcheck2:main.py:128:handleKline:2218005: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': True, 'isOpenSell': False, 'isCloseBuy': False, 'isCloseSell': False, 'isOpen': True, 'isClose': False, 'isTrig': True}

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=29, self.factor=0.4594432949788754, self.count=19171 

self.closeSec=1689783899, self.tradeDate='20230720', self.openTime='002000', self.closeTime='002459', self.symbol='BTCUSDT', self.open=29885.1, self.close=29903.1, self.high=29915.9, self.low=29855.5 
127.0.0.1 - - [20/Jul/2023 00:25:00] "POST / HTTP/1.1" 200 -
2023-07-20 00:25:00,749:INFO:factorcheck2:main.py:126:handleKline:2218005: self.closeSec=1689783899, self.tradeDate='20230720', self.openTime='002000', self.closeTime='002459',self.symbol='BTCUSDT',self.open=29885.1, self.close=29903.1, self.high=29915.9, self.low=29855.5   
2023-07-20 00:25:00,770:INFO:factorcheck2:main.py:127:handleKline:2218005: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime    closeSec  ...      low       pct  index  idx
1440  20230720   000000    000459  1689782699  ...  29929.3 -0.000371   1440    0
1441  20230720   000500    000959  1689782999  ...  29896.0  0.000080   1441    1
1442  20230720   001000    001459  1689783299  ...  29894.4 -0.000458   1442    2
1443  20230720   001500    001959  1689783599  ...  29875.0 -0.001103   1443    3
1444  20230720   002000    002459  1689783899  ...  29855.5  0.000606   1444    4

[5 rows x 11 columns]
2023-07-20 00:25:00,771:INFO:factorcheck2:main.py:128:handleKline:2218005: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': True, 'isOpenSell': False, 'isCloseBuy': False, 'isCloseSell': False, 'isOpen': True, 'isClose': False, 'isTrig': True}


## /root/FIL/strategy/logic/log.txt ----- -----

2023-07-20 00:00:17,021:DEBUG:logic:main.py:463:getModel:2218526: df_s.iloc[-5:,:] :
          date closeTime     open  ...    alpha58   alpha67   alpha72
5802  20230719    212959  29939.3  ...  50.416667  0.482168  0.296219
5803  20230719    215959  29938.7  ...  50.416667  0.493415  0.301437
5804  20230719    222959  29984.4  ...  50.416667  0.462761  0.323454
5805  20230719    225959  29850.0  ...  50.000000  0.454080  0.349173
5806  20230719    232959  29810.9  ...  50.000000  0.468161  0.366026

[5 rows x 33 columns]
0.5183823529411765
acc is : 0.5183823529411765
2023-07-20 00:00:17,086:INFO:logic:main.py:468:getModel:2218526: df_pred.iloc[-5:,:] :
     pred    prob_0    prob_1  actual  ...       nav  sign  cost_        bm
539     1  0.499354  0.500646       1  ...  0.934554   1.0    0.0  0.993690
540     0  0.516532  0.483468       0  ...  0.930399   1.0    0.0  0.989273
541     1  0.454294  0.545706       0  ...  0.929147   1.0    0.0  0.987940
542     1  0.482037  0.517963       1  ...  0.930879   1.0    0.0  0.989783
543     0  0.511659  0.488341       1  ...  0.933183   1.0    0.0  0.992232

[5 rows x 10 columns]
2023-07-20 00:00:17,097:INFO:logic:main.py:478:getModel:2218526: df_panel.iloc[-5:,:] :
    pred    prob_0    prob_1  actual  ...       nav  sign  cost_        bm
45     1  0.499479  0.500521       1  ...  0.934554   1.0    0.0  0.993407
46     0  0.516531  0.483469       0  ...  0.930399   1.0    0.0  0.989715
47     1  0.454412  0.545588       0  ...  0.929147   1.0    0.0  0.988382
48     1  0.481778  0.518222       1  ...  0.918678   1.0    0.0  0.989344
49     0  0.511659  0.488341       1  ...  0.933183   1.0    0.0  0.992232

[5 rows x 10 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '23.547', 'enterprice': '29974.9', 'countrevence': '0', 'unrealprofit': '-661.6707', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '29946.8', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}


## /root/FIL/strategy/modifiedmom/log.txt ----- -----

127.0.0.1 - - [20/Jul/2023 00:00:04] "POST / HTTP/1.1" 200 -
2023-07-20 00:00:04,320:INFO:modifiedmom:main.py:319:handleOrderFilled:2218259: handleOrderFilled: data=OrderType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'clientorderid': '42694F1689782403553I0L59', 'symbol': 'BTCUSDT', 'gatewayorderid': 1689782403940851, 'quantity': '24.799', 'price': '29939.4', 'stopprice': '0', 'ordertype': '', 'side': 'SELL', 'status': 'FILLED', 'positionside': 'SHORT', 'createtime': 1689782402654, 'updatetime': 1689782403940, 'tradetype': 'usdt', 'selfid': 42694, 'filltrades': [TradeType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'tradeid': 1689782403940, 'clientorderid': '42694F1689782403553I0L59', 'price': '29939.4', 'quantity': '24.799', 'commission': '742.4671806', 'commissionasset': 'USDT', 'tradetime': 1689782403940, 'tradetype': 'usdt', 'gatetype': 'simulator', 'handletime': 1689782403940}], 'gatetype': 'simulator', 'handletime': 0}
127.0.0.1 - - [20/Jul/2023 00:10:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=9584 

self.closeSec=1689782999, self.tradeDate='20230720', self.openTime='000000', self.closeTime='000959', self.symbol='BTCUSDT', self.open='29939.7', self.close='29931.7'
2023-07-20 00:10:01,106:INFO:modifiedmom:main.py:144:handleKline:2218259: self.closeSec=1689782999, self.tradeDate='20230720', self.openTime='000000', self.closeTime='000959',self.symbol='BTCUSDT',self.open='29939.7', self.close='29931.7'
2023-07-20 00:10:01,113:INFO:modifiedmom:main.py:145:handleKline:2218259: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec     open    close       pct
572  20230719   232000    232959  1689780599  29852.8  29866.5  0.000459
573  20230719   233000    233959  1689781199  29866.5  29865.8 -0.000023
574  20230719   234000    234959  1689781799  29865.8  29933.9  0.002280
575  20230719   235000    235959  1689782399    29934  29939.8  0.000197
576  20230720   000000    000959  1689782999  29939.7  29931.7 -0.000271
2023-07-20 00:10:01,113:INFO:modifiedmom:main.py:146:handleKline:2218259: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': True, 'isOpen': False, 'isClose': True, 'isTrig': False}

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=9585 

self.closeSec=1689783599, self.tradeDate='20230720', self.openTime='001000', self.closeTime='001959', self.symbol='BTCUSDT', self.open='29932', self.close='29885'
127.0.0.1 - - [20/Jul/2023 00:20:04] "POST / HTTP/1.1" 200 -
2023-07-20 00:20:06,145:INFO:modifiedmom:main.py:144:handleKline:2218259: self.closeSec=1689783599, self.tradeDate='20230720', self.openTime='001000', self.closeTime='001959',self.symbol='BTCUSDT',self.open='29932', self.close='29885'
2023-07-20 00:20:06,654:INFO:modifiedmom:main.py:145:handleKline:2218259: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec     open    close       pct
573  20230719   233000    233959  1689781199  29866.5  29865.8 -0.000023
574  20230719   234000    234959  1689781799  29865.8  29933.9  0.002280
575  20230719   235000    235959  1689782399    29934  29939.8  0.000197
576  20230720   000000    000959  1689782999  29939.7  29931.7 -0.000271
577  20230720   001000    001959  1689783599    29932    29885 -0.001560
2023-07-20 00:20:06,654:INFO:modifiedmom:main.py:146:handleKline:2218259: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': True, 'isOpen': False, 'isClose': True, 'isTrig': False}


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

127.0.0.1 - - [20/Jul/2023 00:00:04] "POST / HTTP/1.1" 200 -
2023-07-20 00:00:04,050:INFO:pyemd2:main.py:303:handleOrderFilled:2217508: handleOrderFilled: data=OrderType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'clientorderid': '42692F1689782403482I0L57', 'symbol': 'BTCUSDT', 'gatewayorderid': 1689782403888059, 'quantity': '33.703', 'price': '29939.4', 'stopprice': '0', 'ordertype': '', 'side': 'SELL', 'status': 'FILLED', 'positionside': 'SHORT', 'createtime': 1689782402600, 'updatetime': 1689782403888, 'tradetype': 'usdt', 'selfid': 42692, 'filltrades': [TradeType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'tradeid': 1689782403888, 'clientorderid': '42692F1689782403482I0L57', 'price': '29939.4', 'quantity': '33.703', 'commission': '1009.0475982', 'commissionasset': 'USDT', 'tradetime': 1689782403888, 'tradetype': 'usdt', 'gatetype': 'simulator', 'handletime': 1689782403888}], 'gatetype': 'simulator', 'handletime': 0}
127.0.0.1 - - [20/Jul/2023 00:10:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=9587 

self.closeSec=1689782999, self.tradeDate='20230720', self.openTime='000000', self.closeTime='000959', self.symbol='BTCUSDT', self.open='29939.7', self.close='29931.7'
2023-07-20 00:10:01,110:INFO:pyemd2:main.py:125:handleKline:2217508: self.closeSec=1689782999, self.tradeDate='20230720', self.openTime='000000', self.closeTime='000959',self.symbol='BTCUSDT',self.open='29939.7', self.close='29931.7'
2023-07-20 00:10:01,123:INFO:pyemd2:main.py:126:handleKline:2217508: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
17420  20230719   232000    232959  1689780599  29852.8  29866.5
17421  20230719   233000    233959  1689781199  29866.5  29865.8
17422  20230719   234000    234959  1689781799  29865.8  29933.9
17423  20230719   235000    235959  1689782399    29934  29939.8
17424  20230720   000000    000959  1689782999  29939.7  29931.7
2023-07-20 00:10:01,123:INFO:pyemd2:main.py:127:handleKline:2217508: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=9588 

self.closeSec=1689783599, self.tradeDate='20230720', self.openTime='001000', self.closeTime='001959', self.symbol='BTCUSDT', self.open='29932', self.close='29885'
127.0.0.1 - - [20/Jul/2023 00:20:04] "POST / HTTP/1.1" 200 -
2023-07-20 00:20:07,323:INFO:pyemd2:main.py:125:handleKline:2217508: self.closeSec=1689783599, self.tradeDate='20230720', self.openTime='001000', self.closeTime='001959',self.symbol='BTCUSDT',self.open='29932', self.close='29885'
2023-07-20 00:20:07,509:INFO:pyemd2:main.py:126:handleKline:2217508: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
17421  20230719   233000    233959  1689781199  29866.5  29865.8
17422  20230719   234000    234959  1689781799  29865.8  29933.9
17423  20230719   235000    235959  1689782399    29934  29939.8
17424  20230720   000000    000959  1689782999  29939.7  29931.7
17425  20230720   001000    001959  1689783599    29932    29885
2023-07-20 00:20:07,510:INFO:pyemd2:main.py:127:handleKline:2217508: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}


## /root/FIL/strategy/similarity/log.txt ----- -----

127.0.0.1 - - [20/Jul/2023 00:00:04] "POST / HTTP/1.1" 200 -
2023-07-20 00:00:04,216:INFO:testStrategy:main.py:308:handleOrderFilled:2217133: handleOrderFilled: data=OrderType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'clientorderid': '42693F1689782403524I0L2', 'symbol': 'BTCUSDT', 'gatewayorderid': 1689782403934312, 'quantity': '37.971', 'price': '29939.4', 'stopprice': '0', 'ordertype': '', 'side': 'SELL', 'status': 'FILLED', 'positionside': 'SHORT', 'createtime': 1689782402664, 'updatetime': 1689782403934, 'tradetype': 'usdt', 'selfid': 42693, 'filltrades': [TradeType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'tradeid': 1689782403934, 'clientorderid': '42693F1689782403524I0L2', 'price': '29939.4', 'quantity': '37.971', 'commission': '1136.8289574', 'commissionasset': 'USDT', 'tradetime': 1689782403934, 'tradetype': 'usdt', 'gatetype': 'simulator', 'handletime': 1689782403934}], 'gatetype': 'simulator', 'handletime': 0}
127.0.0.1 - - [20/Jul/2023 00:10:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=9587 

self.closeSec=1689782999, self.tradeDate='20230720', self.openTime='000000', self.closeTime='000959', self.symbol='BTCUSDT', self.open='29939.7', self.close='29931.7'
2023-07-20 00:10:01,108:INFO:testStrategy:main.py:101:handleKline:2217133: self.closeSec=1689782999, self.tradeDate='20230720', self.openTime='000000', self.closeTime='000959',self.symbol='BTCUSDT',self.open='29939.7', self.close='29931.7'
2023-07-20 00:10:01,115:INFO:testStrategy:main.py:102:handleKline:2217133: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
12236  20230719   232000    232959  1689780599  29852.8  29866.5
12237  20230719   233000    233959  1689781199  29866.5  29865.8
12238  20230719   234000    234959  1689781799  29865.8  29933.9
12239  20230719   235000    235959  1689782399    29934  29939.8
12240  20230720   000000    000959  1689782999  29939.7  29931.7
2023-07-20 00:10:01,115:INFO:testStrategy:main.py:103:handleKline:2217133: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': True, 'isOpen': False, 'isClose': True, 'isTrig': False, 'isCorr': False}

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=9588 

self.closeSec=1689783599, self.tradeDate='20230720', self.openTime='001000', self.closeTime='001959', self.symbol='BTCUSDT', self.open='29932', self.close='29885'
127.0.0.1 - - [20/Jul/2023 00:20:04] "POST / HTTP/1.1" 200 -
2023-07-20 00:20:07,174:INFO:testStrategy:main.py:101:handleKline:2217133: self.closeSec=1689783599, self.tradeDate='20230720', self.openTime='001000', self.closeTime='001959',self.symbol='BTCUSDT',self.open='29932', self.close='29885'
2023-07-20 00:20:07,396:INFO:testStrategy:main.py:102:handleKline:2217133: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
12237  20230719   233000    233959  1689781199  29866.5  29865.8
12238  20230719   234000    234959  1689781799  29865.8  29933.9
12239  20230719   235000    235959  1689782399    29934  29939.8
12240  20230720   000000    000959  1689782999  29939.7  29931.7
12241  20230720   001000    001959  1689783599    29932    29885
2023-07-20 00:20:07,396:INFO:testStrategy:main.py:103:handleKline:2217133: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': True, 'isOpen': False, 'isClose': True, 'isTrig': False, 'isCorr': False}


## /root/FIL/strategy/sr_min/log.txt ----- -----

--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=1, self.total=996015.990996, self.flagDict['side']='buy', self.tradeCount=1, self.count=19168
self.closeSec=1689783599, self.tradeDate='20230720', self.openTime='001500', self.closeTime='001959', self.symbol='BTCUSDT', self.open=29918.0, self.close=29885.0, self.high=29918.0, self.low=29875.0, self.vol=1193.404, self.amt=35668206.8373 
127.0.0.1 - - [20/Jul/2023 00:20:01] "POST / HTTP/1.1" 200 -
2023-07-20 00:20:05,574:INFO:sr_min:main.py:172:handleKline:2219263: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5759  20230719   235500    235959  ...         0.0        0.0       0
5760  20230720   000000    000459  ...         0.0        0.0       0
5761  20230720   000500    000959  ...         0.0        0.0       0
5762  20230720   001000    001459  ...         0.0        0.0       0
5763  20230720   001500    001959  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-07-20 00:20:05,593:INFO:sr_min:main.py:175:handleKline:2219263: self.closeSec=1689783599, self.tradeDate='20230720', self.openTime='001500', self.closeTime='001959',self.symbol='BTCUSDT',self.open=29918.0, self.close=29885.0, self.high=29918.0, self.low=29875.0, self.vol=1193.404, self.amt=35668206.8373, ukdf['pct'].iloc[-1]=-0.001103 , ukdf['amount'].iloc[-1]=35668206.8373, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5763, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '37.141', 'enterprice': '26844', 'countrevence': '0', 'unrealprofit': '112945.781', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '29885', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=1
--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=1, self.total=996015.990996, self.flagDict['side']='buy', self.tradeCount=1, self.count=19169
self.closeSec=1689783899, self.tradeDate='20230720', self.openTime='002000', self.closeTime='002459', self.symbol='BTCUSDT', self.open=29885.1, self.close=29903.1, self.high=29915.9, self.low=29855.5, self.vol=1424.424, self.amt=42568882.4732 
127.0.0.1 - - [20/Jul/2023 00:25:00] "POST / HTTP/1.1" 200 -
2023-07-20 00:25:00,766:INFO:sr_min:main.py:172:handleKline:2219263: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5760  20230720   000000    000459  ...         0.0        0.0       0
5761  20230720   000500    000959  ...         0.0        0.0       0
5762  20230720   001000    001459  ...         0.0        0.0       0
5763  20230720   001500    001959  ...         0.0        0.0       0
5764  20230720   002000    002459  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-07-20 00:25:00,767:INFO:sr_min:main.py:175:handleKline:2219263: self.closeSec=1689783899, self.tradeDate='20230720', self.openTime='002000', self.closeTime='002459',self.symbol='BTCUSDT',self.open=29885.1, self.close=29903.1, self.high=29915.9, self.low=29855.5, self.vol=1424.424, self.amt=42568882.4732, ukdf['pct'].iloc[-1]=0.000606 , ukdf['amount'].iloc[-1]=42568882.4732, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5764, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '37.141', 'enterprice': '26844', 'countrevence': '0', 'unrealprofit': '113672.36296854217', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '29904.56280037', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=1


## /root/FIL/strategy/s_rsrs/log.txt ----- -----

723  20230719   120000    155959  1689753599  ...    723  0.187934 -1.089182    -1.0
724  20230719   160000    195959  1689767999  ...    724  0.196178 -1.074812    -1.0

[5 rows x 15 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '52.176', 'enterprice': '29870.6', 'countrevence': '0', 'unrealprofit': '-7090.7184', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '30006.5', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'numpy.int64'>, curSign=-1, self.sign=-1
--handleKline--:  version='2.0.0', self.name='s_rsrs', self.symbol='BTCUSDT', interval='4h', intervalSec=14400, wid=25, thd=0.6, self.sign=-1, self.total=1556969.8971744, self.flagDict['side']='sell', self.tradeCount=12, self.count=399
self.closeSec=1689782399, self.tradeDate='20230719', self.openTime='200000', self.closeTime='235959', self.symbol='BTCUSDT', self.open=30004.7, self.close=29940.4, self.high=30130.0, self.low=29745.0, self.vol=89657.354, self.amt=2682031405.8294 
127.0.0.1 - - [20/Jul/2023 00:00:01] "POST / HTTP/1.1" 200 -
2023-07-20 00:00:01,706:INFO:s_rsrs:main.py:141:handleKline:2218689: self.closeSec=1689782399, self.tradeDate='20230719', self.openTime='200000', self.closeTime='235959',self.symbol='BTCUSDT',self.open=30004.7, self.close=29940.4, self.high=30130.0, self.low=29745.0, self.vol=89657.354, self.amt=2682031405.8294 
2023-07-20 00:00:01,721:INFO:s_rsrs:main.py:142:handleKline:2218689: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime  ...        vol           amt       pct
721  20230719   040000    075959  ...  27128.255  8.078315e+08  0.004628
722  20230719   080000    115959  ...  46282.264  1.387938e+09  0.006782
723  20230719   120000    155959  ...  41398.750  1.244758e+09 -0.002130
724  20230719   160000    195959  ...  36932.397  1.106437e+09  0.000690
725  20230719   200000    235959  ...  89657.354  2.682031e+09 -0.002143

[5 rows x 11 columns]
2023-07-20 00:00:02,505:INFO:s_rsrs:main.py:151:handleKline:2218689: df_s.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec  ...  index      beta    zscore  signal
721  20230719   040000    075959  1689724799  ...    721  0.176731 -1.095059    -1.0
722  20230719   080000    115959  1689739199  ...    722  0.191430 -1.054658    -1.0
723  20230719   120000    155959  1689753599  ...    723  0.187934 -1.089182    -1.0
724  20230719   160000    195959  1689767999  ...    724  0.196178 -1.074812    -1.0
725  20230719   200000    235959  1689782399  ...    725  0.193102 -1.108616    -1.0

[5 rows x 15 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '52.176', 'enterprice': '29870.6', 'countrevence': '0', 'unrealprofit': '-3667.04538568752', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '29940.88222527', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'numpy.int64'>, curSign=-1, self.sign=-1


