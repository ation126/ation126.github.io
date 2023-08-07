# 20230807 16:26:01

## /root/FIL/strategy/amihud/log.txt ----- -----

--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=373746.4768026, self.flagDict['side']='sell', self.tradeCount=2, self.count=24544
self.closeSec=1691396399, self.tradeDate='20230807', self.openTime='161500', self.closeTime='161959', self.symbol='BTCUSDT', self.open=29058.0, self.close=29051.6, self.high=29059.7, self.low=29050.5, self.vol=293.421, self.amt=8525584.819 
127.0.0.1 - - [07/Aug/2023 16:20:01] "POST / HTTP/1.1" 200 -
2023-08-07 16:20:06,403:INFO:amihud:main.py:172:handleKline:2219019: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5951  20230807   155500    155959  ...         0.0        0.0       0
5952  20230807   160000    160459  ...         0.0        0.0       0
5953  20230807   160500    160959  ...         0.0        0.0       0
5954  20230807   161000    161459  ...         0.0        0.0       0
5955  20230807   161500    161959  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-08-07 16:20:06,423:INFO:amihud:main.py:175:handleKline:2219019: self.closeSec=1691396399, self.tradeDate='20230807', self.openTime='161500', self.closeTime='161959',self.symbol='BTCUSDT',self.open=29058.0, self.close=29051.6, self.high=29059.7, self.low=29050.5, self.vol=293.421, self.amt=8525584.819, ukdf['pct'].iloc[-1]=-0.00022 , ukdf['amount'].iloc[-1]=8525584.819, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5955, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '13.926', 'enterprice': '26864.9', 'countrevence': '0', 'unrealprofit': '-30470.25376841952', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '29052.91190352', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1
127.0.0.1 - - [07/Aug/2023 16:25:00] "POST / HTTP/1.1" 200 -
--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=373746.4768026, self.flagDict['side']='sell', self.tradeCount=2, self.count=24545
self.closeSec=1691396699, self.tradeDate='20230807', self.openTime='162000', self.closeTime='162459', self.symbol='BTCUSDT', self.open=29051.7, self.close=29064.0, self.high=29068.1, self.low=29051.6, self.vol=299.211, self.amt=8695911.6355 
2023-08-07 16:25:00,810:INFO:amihud:main.py:172:handleKline:2219019: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5952  20230807   160000    160459  ...         0.0        0.0       0
5953  20230807   160500    160959  ...         0.0        0.0       0
5954  20230807   161000    161459  ...         0.0        0.0       0
5955  20230807   161500    161959  ...         0.0        0.0       0
5956  20230807   162000    162459  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-08-07 16:25:00,810:INFO:amihud:main.py:175:handleKline:2219019: self.closeSec=1691396699, self.tradeDate='20230807', self.openTime='162000', self.closeTime='162459',self.symbol='BTCUSDT',self.open=29051.7, self.close=29064.0, self.high=29068.1, self.low=29051.6, self.vol=299.211, self.amt=8695911.6355, ukdf['pct'].iloc[-1]=0.000427 , ukdf['amount'].iloc[-1]=8695911.6355, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5956, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '13.926', 'enterprice': '26864.9', 'countrevence': '0', 'unrealprofit': '-30659.20300354626', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '29066.47999451', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1


## /root/FIL/strategy/factorcheck/log.txt ----- -----


self.closeSec=1691396399, self.tradeDate='20230807', self.openTime='161500', self.closeTime='161959', self.symbol='BTCUSDT', self.open=29058.0, self.close=29051.6, self.high=29059.7, self.low=29050.5 
127.0.0.1 - - [07/Aug/2023 16:20:01] "POST / HTTP/1.1" 200 -
2023-08-07 16:20:04,295:INFO:factorcheck2:main.py:126:handleKline:2218005: self.closeSec=1691396399, self.tradeDate='20230807', self.openTime='161500', self.closeTime='161959',self.symbol='BTCUSDT',self.open=29058.0, self.close=29051.6, self.high=29059.7, self.low=29050.5   
2023-08-07 16:20:05,545:INFO:factorcheck2:main.py:127:handleKline:2218005: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime    closeSec  ...      low       pct  index  idx
1631  20230807   155500    155959  1691395199  ...  29052.7  0.001101   1631    5
1632  20230807   160000    160459  1691395499  ...  29062.8 -0.000471   1632    0
1633  20230807   160500    160959  1691395799  ...  29062.1 -0.000172   1633    1
1634  20230807   161000    161459  1691396099  ...  29058.0 -0.000275   1634    2
1635  20230807   161500    161959  1691396399  ...  29050.5 -0.000220   1635    3

[5 rows x 11 columns]
2023-08-07 16:20:05,554:INFO:factorcheck2:main.py:128:handleKline:2218005: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}
127.0.0.1 - - [07/Aug/2023 16:25:00] "POST / HTTP/1.1" 200 -

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=139, self.factor=0.45699220522443096, self.count=24547 

self.closeSec=1691396699, self.tradeDate='20230807', self.openTime='162000', self.closeTime='162459', self.symbol='BTCUSDT', self.open=29051.7, self.close=29064.0, self.high=29068.1, self.low=29051.6 
2023-08-07 16:25:00,761:INFO:factorcheck2:main.py:126:handleKline:2218005: self.closeSec=1691396699, self.tradeDate='20230807', self.openTime='162000', self.closeTime='162459',self.symbol='BTCUSDT',self.open=29051.7, self.close=29064.0, self.high=29068.1, self.low=29051.6   
2023-08-07 16:25:00,772:INFO:factorcheck2:main.py:127:handleKline:2218005: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime    closeSec  ...      low       pct  index  idx
1632  20230807   160000    160459  1691395499  ...  29062.8 -0.000471   1632    0
1633  20230807   160500    160959  1691395799  ...  29062.1 -0.000172   1633    1
1634  20230807   161000    161459  1691396099  ...  29058.0 -0.000275   1634    2
1635  20230807   161500    161959  1691396399  ...  29050.5 -0.000220   1635    3
1636  20230807   162000    162459  1691396699  ...  29051.6  0.000427   1636    4

[5 rows x 11 columns]
2023-08-07 16:25:00,772:INFO:factorcheck2:main.py:128:handleKline:2218005: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}


## /root/FIL/strategy/logic/log.txt ----- -----

2023-08-07 16:00:17,055:DEBUG:logic:main.py:463:getModel:2218526: df_s.iloc[-5:,:] :
          date closeTime     open  ...    alpha58   alpha67   alpha72
5786  20230807    132959  29172.2  ...  48.333333  0.519627  0.368582
5787  20230807    135959  29134.9  ...  47.916667  0.510595  0.372966
5788  20230807    142959  29115.5  ...  47.916667  0.495728  0.386087
5789  20230807    145959  29082.6  ...  47.916667  0.477852  0.409701
5790  20230807    152959  29041.3  ...  47.916667  0.491577  0.423401

[5 rows x 33 columns]
0.551660516605166
acc is : 0.551660516605166
2023-08-07 16:00:17,121:INFO:logic:main.py:468:getModel:2218526: df_pred.iloc[-5:,:] :
     pred    prob_0    prob_1  actual  ...       nav  sign  cost_        bm
537     1  0.488281  0.511719       0  ...  0.990347   1.0    0.0  0.992281
538     1  0.492615  0.507385       0  ...  0.989232   1.0    0.0  0.991163
539     1  0.487904  0.512096       0  ...  0.987827   1.0    0.0  0.989755
540     1  0.479139  0.520861       1  ...  0.988857   1.0    0.0  0.990788
541     0  0.502025  0.497975       1  ...  0.989300   1.0    0.0  0.991231

[5 rows x 10 columns]
2023-08-07 16:00:17,135:INFO:logic:main.py:478:getModel:2218526: df_panel.iloc[-5:,:] :
    pred    prob_0    prob_1  actual  ...       nav  sign  cost_        bm
45     1  0.488172  0.511828       0  ...  0.990347   1.0    0.0  0.988420
46     1  0.492877  0.507123       0  ...  0.989232   1.0    0.0  0.990161
47     1  0.488165  0.511835       0  ...  0.987827   1.0    0.0  0.989958
48     1  0.479623  0.520377       1  ...  0.988857   1.0    0.0  0.991170
49     0  0.502025  0.497975       1  ...  0.989300   1.0    0.0  0.991231

[5 rows x 10 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '24.06', 'enterprice': '29131.5', 'countrevence': '0', 'unrealprofit': '-1129.528763559', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '29084.55366735', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}


## /root/FIL/strategy/modifiedmom/log.txt ----- -----

527  20230807   155000    155959  1691395199  29065.9  29084.7  0.000643
2023-08-07 16:00:02,167:INFO:modifiedmom:main.py:146:handleKline:2218259: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': True, 'isOpenSell': False, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True}
127.0.0.1 - - [07/Aug/2023 16:10:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=12272 

self.closeSec=1691395799, self.tradeDate='20230807', self.openTime='160000', self.closeTime='160959', self.symbol='BTCUSDT', self.open='29084.7', self.close='29066'
2023-08-07 16:10:01,121:INFO:modifiedmom:main.py:144:handleKline:2218259: self.closeSec=1691395799, self.tradeDate='20230807', self.openTime='160000', self.closeTime='160959',self.symbol='BTCUSDT',self.open='29084.7', self.close='29066'
2023-08-07 16:10:01,138:INFO:modifiedmom:main.py:145:handleKline:2218259: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec     open    close       pct
524  20230807   152000    152959  1691393399  29087.6  29071.7 -0.000547
525  20230807   153000    153959  1691393999  29071.8    29078  0.000217
526  20230807   154000    154959  1691394599    29078    29066 -0.000413
527  20230807   155000    155959  1691395199  29065.9  29084.7  0.000643
528  20230807   160000    160959  1691395799  29084.7    29066 -0.000643
2023-08-07 16:10:01,138:INFO:modifiedmom:main.py:146:handleKline:2218259: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': True, 'isOpenSell': False, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True}

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=12273 

self.closeSec=1691396399, self.tradeDate='20230807', self.openTime='161000', self.closeTime='161959', self.symbol='BTCUSDT', self.open='29066.1', self.close='29051.6'
127.0.0.1 - - [07/Aug/2023 16:20:04] "POST / HTTP/1.1" 200 -
2023-08-07 16:20:06,784:INFO:modifiedmom:main.py:144:handleKline:2218259: self.closeSec=1691396399, self.tradeDate='20230807', self.openTime='161000', self.closeTime='161959',self.symbol='BTCUSDT',self.open='29066.1', self.close='29051.6'
2023-08-07 16:20:07,404:INFO:modifiedmom:main.py:145:handleKline:2218259: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec     open    close       pct
525  20230807   153000    153959  1691393999  29071.8    29078  0.000217
526  20230807   154000    154959  1691394599    29078    29066 -0.000413
527  20230807   155000    155959  1691395199  29065.9  29084.7  0.000643
528  20230807   160000    160959  1691395799  29084.7    29066 -0.000643
529  20230807   161000    161959  1691396399  29066.1  29051.6 -0.000495
2023-08-07 16:20:07,405:INFO:modifiedmom:main.py:146:handleKline:2218259: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': True, 'isOpenSell': False, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True}


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

17519  20230807   155000    155959  1691395199  29065.9  29084.7
2023-08-07 16:00:02,175:INFO:pyemd2:main.py:127:handleKline:2217508: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}
127.0.0.1 - - [07/Aug/2023 16:10:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=12275 

self.closeSec=1691395799, self.tradeDate='20230807', self.openTime='160000', self.closeTime='160959', self.symbol='BTCUSDT', self.open='29084.7', self.close='29066'
2023-08-07 16:10:01,127:INFO:pyemd2:main.py:125:handleKline:2217508: self.closeSec=1691395799, self.tradeDate='20230807', self.openTime='160000', self.closeTime='160959',self.symbol='BTCUSDT',self.open='29084.7', self.close='29066'
2023-08-07 16:10:01,142:INFO:pyemd2:main.py:126:handleKline:2217508: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
17516  20230807   152000    152959  1691393399  29087.6  29071.7
17517  20230807   153000    153959  1691393999  29071.8    29078
17518  20230807   154000    154959  1691394599    29078    29066
17519  20230807   155000    155959  1691395199  29065.9  29084.7
17520  20230807   160000    160959  1691395799  29084.7    29066
2023-08-07 16:10:01,142:INFO:pyemd2:main.py:127:handleKline:2217508: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=12276 

self.closeSec=1691396399, self.tradeDate='20230807', self.openTime='161000', self.closeTime='161959', self.symbol='BTCUSDT', self.open='29066.1', self.close='29051.6'
127.0.0.1 - - [07/Aug/2023 16:20:04] "POST / HTTP/1.1" 200 -
2023-08-07 16:20:08,759:INFO:pyemd2:main.py:125:handleKline:2217508: self.closeSec=1691396399, self.tradeDate='20230807', self.openTime='161000', self.closeTime='161959',self.symbol='BTCUSDT',self.open='29066.1', self.close='29051.6'
2023-08-07 16:20:08,859:INFO:pyemd2:main.py:126:handleKline:2217508: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
17517  20230807   153000    153959  1691393999  29071.8    29078
17518  20230807   154000    154959  1691394599    29078    29066
17519  20230807   155000    155959  1691395199  29065.9  29084.7
17520  20230807   160000    160959  1691395799  29084.7    29066
17521  20230807   161000    161959  1691396399  29066.1  29051.6
2023-08-07 16:20:08,860:INFO:pyemd2:main.py:127:handleKline:2217508: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}


## /root/FIL/strategy/similarity/log.txt ----- -----

12191  20230807   155000    155959  1691395199  29065.9  29084.7
2023-08-07 16:00:02,167:INFO:testStrategy:main.py:103:handleKline:2217133: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': True, 'isOpenSell': False, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True, 'isCorr': False}

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=12275 

self.closeSec=1691395799, self.tradeDate='20230807', self.openTime='160000', self.closeTime='160959', self.symbol='BTCUSDT', self.open='29084.7', self.close='29066'
2023-08-07 16:10:01,136:INFO:testStrategy:main.py:101:handleKline:2217133: self.closeSec=1691395799, self.tradeDate='20230807', self.openTime='160000', self.closeTime='160959',self.symbol='BTCUSDT',self.open='29084.7', self.close='29066'
127.0.0.1 - - [07/Aug/2023 16:10:01] "POST / HTTP/1.1" 200 -
2023-08-07 16:10:01,146:INFO:testStrategy:main.py:102:handleKline:2217133: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
12188  20230807   152000    152959  1691393399  29087.6  29071.7
12189  20230807   153000    153959  1691393999  29071.8    29078
12190  20230807   154000    154959  1691394599    29078    29066
12191  20230807   155000    155959  1691395199  29065.9  29084.7
12192  20230807   160000    160959  1691395799  29084.7    29066
2023-08-07 16:10:01,146:INFO:testStrategy:main.py:103:handleKline:2217133: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': True, 'isOpenSell': False, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True, 'isCorr': False}

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=12276 

self.closeSec=1691396399, self.tradeDate='20230807', self.openTime='161000', self.closeTime='161959', self.symbol='BTCUSDT', self.open='29066.1', self.close='29051.6'
127.0.0.1 - - [07/Aug/2023 16:20:04] "POST / HTTP/1.1" 200 -
2023-08-07 16:20:08,468:INFO:testStrategy:main.py:101:handleKline:2217133: self.closeSec=1691396399, self.tradeDate='20230807', self.openTime='161000', self.closeTime='161959',self.symbol='BTCUSDT',self.open='29066.1', self.close='29051.6'
2023-08-07 16:20:08,723:INFO:testStrategy:main.py:102:handleKline:2217133: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
12189  20230807   153000    153959  1691393999  29071.8    29078
12190  20230807   154000    154959  1691394599    29078    29066
12191  20230807   155000    155959  1691395199  29065.9  29084.7
12192  20230807   160000    160959  1691395799  29084.7    29066
12193  20230807   161000    161959  1691396399  29066.1  29051.6
2023-08-07 16:20:08,724:INFO:testStrategy:main.py:103:handleKline:2217133: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': True, 'isOpenSell': False, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True, 'isCorr': False}


## /root/FIL/strategy/sr_min/log.txt ----- -----

--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=1, self.total=996015.990996, self.flagDict['side']='buy', self.tradeCount=1, self.count=24544
self.closeSec=1691396399, self.tradeDate='20230807', self.openTime='161500', self.closeTime='161959', self.symbol='BTCUSDT', self.open=29058.0, self.close=29051.6, self.high=29059.7, self.low=29050.5, self.vol=293.421, self.amt=8525584.819 
127.0.0.1 - - [07/Aug/2023 16:20:01] "POST / HTTP/1.1" 200 -
2023-08-07 16:20:06,344:INFO:sr_min:main.py:172:handleKline:2219263: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5951  20230807   155500    155959  ...         0.0        0.0       0
5952  20230807   160000    160459  ...         0.0        0.0       0
5953  20230807   160500    160959  ...         0.0        0.0       0
5954  20230807   161000    161459  ...         0.0        0.0       0
5955  20230807   161500    161959  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-08-07 16:20:06,365:INFO:sr_min:main.py:175:handleKline:2219263: self.closeSec=1691396399, self.tradeDate='20230807', self.openTime='161500', self.closeTime='161959',self.symbol='BTCUSDT',self.open=29058.0, self.close=29051.6, self.high=29059.7, self.low=29050.5, self.vol=293.421, self.amt=8525584.819, ukdf['pct'].iloc[-1]=-0.00022 , ukdf['amount'].iloc[-1]=8525584.819, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5955, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '37.141', 'enterprice': '26844', 'countrevence': '0', 'unrealprofit': '82041.19700863632', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '29052.91190352', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=1
127.0.0.1 - - [07/Aug/2023 16:25:00] "POST / HTTP/1.1" 200 -
--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=1, self.total=996015.990996, self.flagDict['side']='buy', self.tradeCount=1, self.count=24545
self.closeSec=1691396699, self.tradeDate='20230807', self.openTime='162000', self.closeTime='162459', self.symbol='BTCUSDT', self.open=29051.7, self.close=29064.0, self.high=29068.1, self.low=29051.6, self.vol=299.211, self.amt=8695911.6355 
2023-08-07 16:25:00,780:INFO:sr_min:main.py:172:handleKline:2219263: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5952  20230807   160000    160459  ...         0.0        0.0       0
5953  20230807   160500    160959  ...         0.0        0.0       0
5954  20230807   161000    161459  ...         0.0        0.0       0
5955  20230807   161500    161959  ...         0.0        0.0       0
5956  20230807   162000    162459  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-08-07 16:25:00,780:INFO:sr_min:main.py:175:handleKline:2219263: self.closeSec=1691396699, self.tradeDate='20230807', self.openTime='162000', self.closeTime='162459',self.symbol='BTCUSDT',self.open=29051.7, self.close=29064.0, self.high=29068.1, self.low=29051.6, self.vol=299.211, self.amt=8695911.6355, ukdf['pct'].iloc[-1]=0.000427 , ukdf['amount'].iloc[-1]=8695911.6355, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5956, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '37.141', 'enterprice': '26844', 'countrevence': '0', 'unrealprofit': '82545.12947609591', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '29066.47999451', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=1


## /root/FIL/strategy/s_rsrs/log.txt ----- -----

721  20230807   040000    075959  1691366399  ...    721  0.143837 -0.828316    -1.0
722  20230807   080000    115959  1691380799  ...    722  0.135147 -0.865926    -1.0

[5 rows x 15 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '54.719', 'enterprice': '28996.8', 'countrevence': '0', 'unrealprofit': '-8461.46416836945', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '29151.43484655', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'numpy.int64'>, curSign=-1, self.sign=-1
127.0.0.1 - - [07/Aug/2023 16:00:01] "POST / HTTP/1.1" 200 -
--handleKline--:  version='2.0.0', self.name='s_rsrs', self.symbol='BTCUSDT', interval='4h', intervalSec=14400, wid=25, thd=0.6, self.sign=-1, self.total=1585089.2233008002, self.flagDict['side']='sell', self.tradeCount=18, self.count=511
self.closeSec=1691395199, self.tradeDate='20230807', self.openTime='120000', self.closeTime='155959', self.symbol='BTCUSDT', self.open=29148.8, self.close=29084.7, self.high=29186.6, self.low=29036.5, self.vol=22738.52, self.amt=661751201.7519 
2023-08-07 16:00:01,722:INFO:s_rsrs:main.py:141:handleKline:2218689: self.closeSec=1691395199, self.tradeDate='20230807', self.openTime='120000', self.closeTime='155959',self.symbol='BTCUSDT',self.open=29148.8, self.close=29084.7, self.high=29186.6, self.low=29036.5, self.vol=22738.52, self.amt=661751201.7519 
2023-08-07 16:00:01,736:INFO:s_rsrs:main.py:142:handleKline:2218689: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime  ...        vol           amt       pct
719  20230806   200000    235959  ...  18943.151  5.497474e+08 -0.002271
720  20230807   000000    035959  ...  18067.007  5.250492e+08  0.002617
721  20230807   040000    075959  ...  30590.873  8.908952e+08 -0.000031
722  20230807   080000    115959  ...  29960.579  8.727741e+08  0.002504
723  20230807   120000    155959  ...  22738.520  6.617512e+08 -0.002199

[5 rows x 11 columns]
2023-08-07 16:00:02,394:INFO:s_rsrs:main.py:151:handleKline:2218689: df_s.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec  ...  index      beta    zscore  signal
719  20230806   200000    235959  1691337599  ...    719  0.119670 -0.943544    -1.0
720  20230807   000000    035959  1691351999  ...    720  0.042674 -1.290322    -1.0
721  20230807   040000    075959  1691366399  ...    721  0.143837 -0.828316    -1.0
722  20230807   080000    115959  1691380799  ...    722  0.135147 -0.865926    -1.0
723  20230807   120000    155959  1691395199  ...    723  0.120496 -0.929934    -1.0

[5 rows x 15 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '54.719', 'enterprice': '28996.8', 'countrevence': '0', 'unrealprofit': '-4810.71228378727', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '29084.71667033', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'numpy.int64'>, curSign=-1, self.sign=-1


