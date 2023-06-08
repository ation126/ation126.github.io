# 20230608 16:26:01

## /root/FIL/strategy/amihud/log.txt ----- -----

--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=373746.4768026, self.flagDict['side']='sell', self.tradeCount=2, self.count=7264
self.closeSec=1686212399, self.tradeDate='20230608', self.openTime='161500', self.closeTime='161959', self.symbol='BTCUSDT', self.open=26399.9, self.close=26416.0, self.high=26417.9, self.low=26399.9, self.vol=354.193, self.amt=9354751.6214 
127.0.0.1 - - [08/Jun/2023 16:20:01] "POST / HTTP/1.1" 200 -
2023-06-08 16:20:02,177:INFO:amihud:main.py:172:handleKline:2219019: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5951  20230608   155500    155959  ...         0.0        0.0       0
5952  20230608   160000    160459  ...         0.0        0.0       0
5953  20230608   160500    160959  ...         0.0        0.0       0
5954  20230608   161000    161459  ...         0.0        0.0       0
5955  20230608   161500    161959  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-06-08 16:20:02,188:INFO:amihud:main.py:175:handleKline:2219019: self.closeSec=1686212399, self.tradeDate='20230608', self.openTime='161500', self.closeTime='161959',self.symbol='BTCUSDT',self.open=26399.9, self.close=26416.0, self.high=26417.9, self.low=26399.9, self.vol=354.193, self.amt=9354751.6214, ukdf['pct'].iloc[-1]=0.00061 , ukdf['amount'].iloc[-1]=9354751.6214, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5955, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '13.926', 'enterprice': '26864.9', 'countrevence': '0', 'unrealprofit': '6251.3814', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '26416', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1
--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=373746.4768026, self.flagDict['side']='sell', self.tradeCount=2, self.count=7265
self.closeSec=1686212699, self.tradeDate='20230608', self.openTime='162000', self.closeTime='162459', self.symbol='BTCUSDT', self.open=26415.9, self.close=26399.9, self.high=26420.8, self.low=26399.6, self.vol=461.398, self.amt=12186156.0084 
127.0.0.1 - - [08/Jun/2023 16:25:01] "POST / HTTP/1.1" 200 -
2023-06-08 16:25:04,216:INFO:amihud:main.py:172:handleKline:2219019: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5952  20230608   160000    160459  ...         0.0        0.0       0
5953  20230608   160500    160959  ...         0.0        0.0       0
5954  20230608   161000    161459  ...         0.0        0.0       0
5955  20230608   161500    161959  ...         0.0        0.0       0
5956  20230608   162000    162459  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-06-08 16:25:04,226:INFO:amihud:main.py:175:handleKline:2219019: self.closeSec=1686212699, self.tradeDate='20230608', self.openTime='162000', self.closeTime='162459',self.symbol='BTCUSDT',self.open=26415.9, self.close=26399.9, self.high=26420.8, self.low=26399.6, self.vol=461.398, self.amt=12186156.0084, ukdf['pct'].iloc[-1]=-0.000609 , ukdf['amount'].iloc[-1]=12186156.0084, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5956, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '13.926', 'enterprice': '26864.9', 'countrevence': '0', 'unrealprofit': '6397.6044', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '26405.5', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1


## /root/FIL/strategy/factorcheck/log.txt ----- -----


self.closeSec=1686212399, self.tradeDate='20230608', self.openTime='161500', self.closeTime='161959', self.symbol='BTCUSDT', self.open=26399.9, self.close=26416.0, self.high=26417.9, self.low=26399.9 
127.0.0.1 - - [08/Jun/2023 16:20:01] "POST / HTTP/1.1" 200 -
2023-06-08 16:20:01,299:INFO:factorcheck2:main.py:126:handleKline:2218005: self.closeSec=1686212399, self.tradeDate='20230608', self.openTime='161500', self.closeTime='161959',self.symbol='BTCUSDT',self.open=26399.9, self.close=26416.0, self.high=26417.9, self.low=26399.9   
2023-06-08 16:20:01,578:INFO:factorcheck2:main.py:127:handleKline:2218005: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime    closeSec  ...      low       pct  index  idx
1631  20230608   155500    155959  1686211199  ...  26417.3  0.000541   1631    5
1632  20230608   160000    160459  1686211499  ...  26409.2 -0.000620   1632    0
1633  20230608   160500    160959  1686211799  ...  26385.5  0.000068   1633    1
1634  20230608   161000    161459  1686212099  ...  26394.5 -0.000647   1634    2
1635  20230608   161500    161959  1686212399  ...  26399.9  0.000610   1635    3

[5 rows x 11 columns]
2023-06-08 16:20:01,578:INFO:factorcheck2:main.py:128:handleKline:2218005: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': True, 'isOpenSell': False, 'isCloseBuy': False, 'isCloseSell': False, 'isOpen': True, 'isClose': False, 'isTrig': True}

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=0, self.factor=0.6016588218210852, self.count=7267 

self.closeSec=1686212699, self.tradeDate='20230608', self.openTime='162000', self.closeTime='162459', self.symbol='BTCUSDT', self.open=26415.9, self.close=26399.9, self.high=26420.8, self.low=26399.6 
127.0.0.1 - - [08/Jun/2023 16:25:01] "POST / HTTP/1.1" 200 -
2023-06-08 16:25:03,024:INFO:factorcheck2:main.py:126:handleKline:2218005: self.closeSec=1686212699, self.tradeDate='20230608', self.openTime='162000', self.closeTime='162459',self.symbol='BTCUSDT',self.open=26415.9, self.close=26399.9, self.high=26420.8, self.low=26399.6   
2023-06-08 16:25:03,764:INFO:factorcheck2:main.py:127:handleKline:2218005: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime    closeSec  ...      low       pct  index  idx
1632  20230608   160000    160459  1686211499  ...  26409.2 -0.000620   1632    0
1633  20230608   160500    160959  1686211799  ...  26385.5  0.000068   1633    1
1634  20230608   161000    161459  1686212099  ...  26394.5 -0.000647   1634    2
1635  20230608   161500    161959  1686212399  ...  26399.9  0.000610   1635    3
1636  20230608   162000    162459  1686212699  ...  26399.6 -0.000609   1636    4

[5 rows x 11 columns]
2023-06-08 16:25:03,765:INFO:factorcheck2:main.py:128:handleKline:2218005: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': True, 'isOpenSell': False, 'isCloseBuy': False, 'isCloseSell': False, 'isOpen': True, 'isClose': False, 'isTrig': True}


## /root/FIL/strategy/logic/log.txt ----- -----

2023-06-08 16:00:40,358:DEBUG:logic:main.py:463:getModel:2218526: df_s.iloc[-5:,:] :
          date closeTime     open  ...    alpha58   alpha67   alpha72
5786  20230608    132959  26389.7  ...  49.166667  0.489206  0.699881
5787  20230608    135959  26416.5  ...  48.750000  0.481665  0.700099
5788  20230608    142959  26365.3  ...  48.333333  0.477920  0.702278
5789  20230608    145959  26340.0  ...  48.750000  0.489604  0.698610
5790  20230608    152959  26413.3  ...  49.166667  0.500892  0.689539

[5 rows x 33 columns]
0.518450184501845
acc is : 0.518450184501845
2023-06-08 16:00:40,500:INFO:logic:main.py:468:getModel:2218526: df_pred.iloc[-5:,:] :
     pred    prob_0    prob_1  actual  ...       nav  sign  cost_        bm
537     0  0.513633  0.486367       0  ...  1.127417  -1.0    0.0  0.974212
538     0  0.503944  0.496056       0  ...  1.128503  -1.0    0.0  0.973274
539     1  0.499066  0.500934       1  ...  1.125363  -1.0    0.0  0.975982
540     0  0.517737  0.482263       1  ...  1.122270  -1.0    0.0  0.978665
541     0  0.520566  0.479434       0  ...  1.124575  -1.0    0.0  0.976655

[5 rows x 10 columns]
2023-06-08 16:00:40,537:INFO:logic:main.py:478:getModel:2218526: df_panel.iloc[-5:,:] :
    pred    prob_0    prob_1  actual  ...       nav  sign  cost_        bm
45     0  0.513811  0.486189       0  ...  1.127417  -1.0    0.0  0.984125
46     0  0.504175  0.495825       0  ...  1.128503  -1.0    0.0  0.982136
47     1  0.499085  0.500915       1  ...  1.125363  -1.0    0.0  0.984043
48     0  0.517958  0.482042       1  ...  1.122270  -1.0    0.0  0.988442
49     0  0.520566  0.479434       0  ...  1.124575  -1.0    0.0  0.976655

[5 rows x 10 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '28.022', 'enterprice': '26938.4', 'countrevence': '0', 'unrealprofit': '14196.57870484302', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '26431.77739259', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}


## /root/FIL/strategy/modifiedmom/log.txt ----- -----

527  20230608   155000    155959  1686211199  26426.5  26431.5  0.000193
2023-06-08 16:00:02,388:INFO:modifiedmom:main.py:146:handleKline:2218259: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': True, 'isOpenSell': False, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True}

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=3632 

self.closeSec=1686211799, self.tradeDate='20230608', self.openTime='160000', self.closeTime='160959', self.symbol='BTCUSDT', self.open='26431.6', self.close='26416.1'
2023-06-08 16:10:01,137:INFO:modifiedmom:main.py:144:handleKline:2218259: self.closeSec=1686211799, self.tradeDate='20230608', self.openTime='160000', self.closeTime='160959',self.symbol='BTCUSDT',self.open='26431.6', self.close='26416.1'
127.0.0.1 - - [08/Jun/2023 16:10:01] "POST / HTTP/1.1" 200 -
2023-06-08 16:10:01,146:INFO:modifiedmom:main.py:145:handleKline:2218259: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec     open    close       pct
524  20230608   152000    152959  1686209399  26426.3  26485.9  0.002255
525  20230608   153000    153959  1686209999  26485.9  26448.4 -0.001416
526  20230608   154000    154959  1686210599  26448.4  26426.4 -0.000832
527  20230608   155000    155959  1686211199  26426.5  26431.5  0.000193
528  20230608   160000    160959  1686211799  26431.6  26416.1 -0.000583
2023-06-08 16:10:01,147:INFO:modifiedmom:main.py:146:handleKline:2218259: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': True, 'isOpenSell': False, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True}

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=3633 

self.closeSec=1686212399, self.tradeDate='20230608', self.openTime='161000', self.closeTime='161959', self.symbol='BTCUSDT', self.open='26416.1', self.close='26415.9'
127.0.0.1 - - [08/Jun/2023 16:20:02] "POST / HTTP/1.1" 200 -
2023-06-08 16:20:04,631:INFO:modifiedmom:main.py:144:handleKline:2218259: self.closeSec=1686212399, self.tradeDate='20230608', self.openTime='161000', self.closeTime='161959',self.symbol='BTCUSDT',self.open='26416.1', self.close='26415.9'
2023-06-08 16:20:05,164:INFO:modifiedmom:main.py:145:handleKline:2218259: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec     open    close       pct
525  20230608   153000    153959  1686209999  26485.9  26448.4 -0.001416
526  20230608   154000    154959  1686210599  26448.4  26426.4 -0.000832
527  20230608   155000    155959  1686211199  26426.5  26431.5  0.000193
528  20230608   160000    160959  1686211799  26431.6  26416.1 -0.000583
529  20230608   161000    161959  1686212399  26416.1  26415.9 -0.000008
2023-06-08 16:20:05,164:INFO:modifiedmom:main.py:146:handleKline:2218259: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': True, 'isOpenSell': False, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True}


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

17519  20230608   155000    155959  1686211199  26426.5  26431.5
2023-06-08 16:00:02,425:INFO:pyemd2:main.py:127:handleKline:2217508: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}
127.0.0.1 - - [08/Jun/2023 16:10:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=3635 

self.closeSec=1686211799, self.tradeDate='20230608', self.openTime='160000', self.closeTime='160959', self.symbol='BTCUSDT', self.open='26431.6', self.close='26416.1'
2023-06-08 16:10:01,198:INFO:pyemd2:main.py:125:handleKline:2217508: self.closeSec=1686211799, self.tradeDate='20230608', self.openTime='160000', self.closeTime='160959',self.symbol='BTCUSDT',self.open='26431.6', self.close='26416.1'
2023-06-08 16:10:01,238:INFO:pyemd2:main.py:126:handleKline:2217508: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
17516  20230608   152000    152959  1686209399  26426.3  26485.9
17517  20230608   153000    153959  1686209999  26485.9  26448.4
17518  20230608   154000    154959  1686210599  26448.4  26426.4
17519  20230608   155000    155959  1686211199  26426.5  26431.5
17520  20230608   160000    160959  1686211799  26431.6  26416.1
2023-06-08 16:10:01,238:INFO:pyemd2:main.py:127:handleKline:2217508: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=3636 

self.closeSec=1686212399, self.tradeDate='20230608', self.openTime='161000', self.closeTime='161959', self.symbol='BTCUSDT', self.open='26416.1', self.close='26415.9'
127.0.0.1 - - [08/Jun/2023 16:20:02] "POST / HTTP/1.1" 200 -
2023-06-08 16:20:06,442:INFO:pyemd2:main.py:125:handleKline:2217508: self.closeSec=1686212399, self.tradeDate='20230608', self.openTime='161000', self.closeTime='161959',self.symbol='BTCUSDT',self.open='26416.1', self.close='26415.9'
2023-06-08 16:20:06,630:INFO:pyemd2:main.py:126:handleKline:2217508: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
17517  20230608   153000    153959  1686209999  26485.9  26448.4
17518  20230608   154000    154959  1686210599  26448.4  26426.4
17519  20230608   155000    155959  1686211199  26426.5  26431.5
17520  20230608   160000    160959  1686211799  26431.6  26416.1
17521  20230608   161000    161959  1686212399  26416.1  26415.9
2023-06-08 16:20:06,631:INFO:pyemd2:main.py:127:handleKline:2217508: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}


## /root/FIL/strategy/similarity/log.txt ----- -----

12191  20230608   155000    155959  1686211199  26426.5  26431.5
2023-06-08 16:00:02,338:INFO:testStrategy:main.py:103:handleKline:2217133: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': True, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True, 'isCorr': False}

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=3635 

self.closeSec=1686211799, self.tradeDate='20230608', self.openTime='160000', self.closeTime='160959', self.symbol='BTCUSDT', self.open='26431.6', self.close='26416.1'
127.0.0.1 - - [08/Jun/2023 16:10:01] "POST / HTTP/1.1" 200 -
2023-06-08 16:10:01,194:INFO:testStrategy:main.py:101:handleKline:2217133: self.closeSec=1686211799, self.tradeDate='20230608', self.openTime='160000', self.closeTime='160959',self.symbol='BTCUSDT',self.open='26431.6', self.close='26416.1'
2023-06-08 16:10:01,246:INFO:testStrategy:main.py:102:handleKline:2217133: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
12188  20230608   152000    152959  1686209399  26426.3  26485.9
12189  20230608   153000    153959  1686209999  26485.9  26448.4
12190  20230608   154000    154959  1686210599  26448.4  26426.4
12191  20230608   155000    155959  1686211199  26426.5  26431.5
12192  20230608   160000    160959  1686211799  26431.6  26416.1
2023-06-08 16:10:01,246:INFO:testStrategy:main.py:103:handleKline:2217133: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': True, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True, 'isCorr': False}

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=3636 

self.closeSec=1686212399, self.tradeDate='20230608', self.openTime='161000', self.closeTime='161959', self.symbol='BTCUSDT', self.open='26416.1', self.close='26415.9'
127.0.0.1 - - [08/Jun/2023 16:20:02] "POST / HTTP/1.1" 200 -
2023-06-08 16:20:06,166:INFO:testStrategy:main.py:101:handleKline:2217133: self.closeSec=1686212399, self.tradeDate='20230608', self.openTime='161000', self.closeTime='161959',self.symbol='BTCUSDT',self.open='26416.1', self.close='26415.9'
2023-06-08 16:20:06,440:INFO:testStrategy:main.py:102:handleKline:2217133: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
12189  20230608   153000    153959  1686209999  26485.9  26448.4
12190  20230608   154000    154959  1686210599  26448.4  26426.4
12191  20230608   155000    155959  1686211199  26426.5  26431.5
12192  20230608   160000    160959  1686211799  26431.6  26416.1
12193  20230608   161000    161959  1686212399  26416.1  26415.9
2023-06-08 16:20:06,442:INFO:testStrategy:main.py:103:handleKline:2217133: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': True, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True, 'isCorr': False}


## /root/FIL/strategy/sr_min/log.txt ----- -----

--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=1, self.total=996015.990996, self.flagDict['side']='buy', self.tradeCount=1, self.count=7264
self.closeSec=1686212399, self.tradeDate='20230608', self.openTime='161500', self.closeTime='161959', self.symbol='BTCUSDT', self.open=26399.9, self.close=26416.0, self.high=26417.9, self.low=26399.9, self.vol=354.193, self.amt=9354751.6214 
127.0.0.1 - - [08/Jun/2023 16:20:01] "POST / HTTP/1.1" 200 -
2023-06-08 16:20:02,153:INFO:sr_min:main.py:172:handleKline:2219263: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5951  20230608   155500    155959  ...         0.0        0.0       0
5952  20230608   160000    160459  ...         0.0        0.0       0
5953  20230608   160500    160959  ...         0.0        0.0       0
5954  20230608   161000    161459  ...         0.0        0.0       0
5955  20230608   161500    161959  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-06-08 16:20:02,169:INFO:sr_min:main.py:175:handleKline:2219263: self.closeSec=1686212399, self.tradeDate='20230608', self.openTime='161500', self.closeTime='161959',self.symbol='BTCUSDT',self.open=26399.9, self.close=26416.0, self.high=26417.9, self.low=26399.9, self.vol=354.193, self.amt=9354751.6214, ukdf['pct'].iloc[-1]=0.00061 , ukdf['amount'].iloc[-1]=9354751.6214, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5955, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '37.141', 'enterprice': '26844', 'countrevence': '0', 'unrealprofit': '-15896.348', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '26416', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=1
--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=1, self.total=996015.990996, self.flagDict['side']='buy', self.tradeCount=1, self.count=7265
self.closeSec=1686212699, self.tradeDate='20230608', self.openTime='162000', self.closeTime='162459', self.symbol='BTCUSDT', self.open=26415.9, self.close=26399.9, self.high=26420.8, self.low=26399.6, self.vol=461.398, self.amt=12186156.0084 
127.0.0.1 - - [08/Jun/2023 16:25:01] "POST / HTTP/1.1" 200 -
2023-06-08 16:25:04,194:INFO:sr_min:main.py:172:handleKline:2219263: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5952  20230608   160000    160459  ...         0.0        0.0       0
5953  20230608   160500    160959  ...         0.0        0.0       0
5954  20230608   161000    161459  ...         0.0        0.0       0
5955  20230608   161500    161959  ...         0.0        0.0       0
5956  20230608   162000    162459  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-06-08 16:25:04,207:INFO:sr_min:main.py:175:handleKline:2219263: self.closeSec=1686212699, self.tradeDate='20230608', self.openTime='162000', self.closeTime='162459',self.symbol='BTCUSDT',self.open=26415.9, self.close=26399.9, self.high=26420.8, self.low=26399.6, self.vol=461.398, self.amt=12186156.0084, ukdf['pct'].iloc[-1]=-0.000609 , ukdf['amount'].iloc[-1]=12186156.0084, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5956, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '37.141', 'enterprice': '26844', 'countrevence': '0', 'unrealprofit': '-16286.3285', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '26405.5', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=1


## /root/FIL/strategy/s_rsrs/log.txt ----- -----

721  20230608   040000    075959  1686182399  ...    721  0.500401 -0.323202     NaN
722  20230608   080000    115959  1686196799  ...    722  0.507395 -0.308328     NaN

[5 rows x 15 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '55.166', 'enterprice': '27078.6', 'countrevence': '0', 'unrealprofit': '41247.6182', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '26330.9', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'numpy.int64'>, curSign=-9223372036854775808, self.sign=-1
--handleKline--:  version='2.0.0', self.name='s_rsrs', self.symbol='BTCUSDT', interval='4h', intervalSec=14400, wid=25, thd=0.6, self.sign=-1, self.total=1492324.2295523998, self.flagDict['side']='sell', self.tradeCount=4, self.count=151
self.closeSec=1686211199, self.tradeDate='20230608', self.openTime='120000', self.closeTime='155959', self.symbol='BTCUSDT', self.open=26332.0, self.close=26431.5, self.high=26516.3, self.low=26270.6, self.vol=44715.213, self.amt=1180480981.8653 
127.0.0.1 - - [08/Jun/2023 16:00:01] "POST / HTTP/1.1" 200 -
2023-06-08 16:00:01,845:INFO:s_rsrs:main.py:141:handleKline:2218689: self.closeSec=1686211199, self.tradeDate='20230608', self.openTime='120000', self.closeTime='155959',self.symbol='BTCUSDT',self.open=26332.0, self.close=26431.5, self.high=26516.3, self.low=26270.6, self.vol=44715.213, self.amt=1180480981.8653 
2023-06-08 16:00:01,869:INFO:s_rsrs:main.py:142:handleKline:2218689: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime  ...         vol           amt       pct
719  20230607   200000    235959  ...  202615.316  5.380169e+09 -0.020619
720  20230608   000000    035959  ...   80719.705  2.130781e+09  0.005138
721  20230608   040000    075959  ...   64175.757  1.687819e+09 -0.005414
722  20230608   080000    115959  ...   45884.902  1.209048e+09  0.000232
723  20230608   120000    155959  ...   44715.213  1.180481e+09  0.003779

[5 rows x 11 columns]
2023-06-08 16:00:04,338:INFO:s_rsrs:main.py:151:handleKline:2218689: df_s.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec  ...  index      beta    zscore  signal
719  20230607   200000    235959  1686153599  ...    719  0.502840 -0.313424     NaN
720  20230608   000000    035959  1686167999  ...    720  0.503967 -0.310189     NaN
721  20230608   040000    075959  1686182399  ...    721  0.500401 -0.323202     NaN
722  20230608   080000    115959  1686196799  ...    722  0.507395 -0.308328     NaN
723  20230608   120000    155959  1686211199  ...    723  0.517285 -0.282857     NaN

[5 rows x 15 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '55.166', 'enterprice': '27078.6', 'countrevence': '0', 'unrealprofit': '35667.15384137072', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '26432.05767608', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'numpy.int64'>, curSign=-9223372036854775808, self.sign=-1


