# 20230710 16:26:01

## /root/FIL/strategy/amihud/log.txt ----- -----

--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=373746.4768026, self.flagDict['side']='sell', self.tradeCount=2, self.count=16480
self.closeSec=1688977199, self.tradeDate='20230710', self.openTime='161500', self.closeTime='161959', self.symbol='BTCUSDT', self.open=30074.5, self.close=30051.5, self.high=30084.8, self.low=30027.1, self.vol=1314.943, self.amt=39509322.9407 
127.0.0.1 - - [10/Jul/2023 16:20:01] "POST / HTTP/1.1" 200 -
2023-07-10 16:20:07,169:INFO:amihud:main.py:172:handleKline:2219019: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5951  20230710   155500    155959  ...         0.0        0.0       0
5952  20230710   160000    160459  ...         0.0        0.0       0
5953  20230710   160500    160959  ...         0.0        0.0       0
5954  20230710   161000    161459  ...         0.0        0.0       0
5955  20230710   161500    161959  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-07-10 16:20:07,191:INFO:amihud:main.py:175:handleKline:2219019: self.closeSec=1688977199, self.tradeDate='20230710', self.openTime='161500', self.closeTime='161959',self.symbol='BTCUSDT',self.open=30074.5, self.close=30051.5, self.high=30084.8, self.low=30027.1, self.vol=1314.943, self.amt=39509322.9407, ukdf['pct'].iloc[-1]=-0.000765 , ukdf['amount'].iloc[-1]=39509322.9407, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5955, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '13.926', 'enterprice': '26864.9', 'countrevence': '0', 'unrealprofit': '-44287.4652', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '30045.1', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1
127.0.0.1 - - [10/Jul/2023 16:25:00] "POST / HTTP/1.1" 200 -
--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=373746.4768026, self.flagDict['side']='sell', self.tradeCount=2, self.count=16481
self.closeSec=1688977499, self.tradeDate='20230710', self.openTime='162000', self.closeTime='162459', self.symbol='BTCUSDT', self.open=30050.0, self.close=30061.1, self.high=30075.0, self.low=29966.6, self.vol=3258.28, self.amt=97825681.702 
2023-07-10 16:25:00,808:INFO:amihud:main.py:172:handleKline:2219019: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5952  20230710   160000    160459  ...         0.0        0.0       0
5953  20230710   160500    160959  ...         0.0        0.0       0
5954  20230710   161000    161459  ...         0.0        0.0       0
5955  20230710   161500    161959  ...         0.0        0.0       0
5956  20230710   162000    162459  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-07-10 16:25:00,810:INFO:amihud:main.py:175:handleKline:2219019: self.closeSec=1688977499, self.tradeDate='20230710', self.openTime='162000', self.closeTime='162459',self.symbol='BTCUSDT',self.open=30050.0, self.close=30061.1, self.high=30075.0, self.low=29966.6, self.vol=3258.28, self.amt=97825681.702, ukdf['pct'].iloc[-1]=0.000319 , ukdf['amount'].iloc[-1]=97825681.702, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5956, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '13.926', 'enterprice': '26864.9', 'countrevence': '0', 'unrealprofit': '-44510.2812', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '30061.1', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1


## /root/FIL/strategy/factorcheck/log.txt ----- -----


self.closeSec=1688977199, self.tradeDate='20230710', self.openTime='161500', self.closeTime='161959', self.symbol='BTCUSDT', self.open=30074.5, self.close=30051.5, self.high=30084.8, self.low=30027.1 
127.0.0.1 - - [10/Jul/2023 16:20:01] "POST / HTTP/1.1" 200 -
2023-07-10 16:20:04,780:INFO:factorcheck2:main.py:126:handleKline:2218005: self.closeSec=1688977199, self.tradeDate='20230710', self.openTime='161500', self.closeTime='161959',self.symbol='BTCUSDT',self.open=30074.5, self.close=30051.5, self.high=30084.8, self.low=30027.1   
2023-07-10 16:20:06,320:INFO:factorcheck2:main.py:127:handleKline:2218005: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime    closeSec  ...      low       pct  index  idx
1631  20230710   155500    155959  1688975999  ...  30069.9  0.000998   1631    5
1632  20230710   160000    160459  1688976299  ...  30077.4 -0.000744   1632    0
1633  20230710   160500    160959  1688976599  ...  30074.7  0.000276   1633    1
1634  20230710   161000    161459  1688976899  ...  30070.1 -0.000376   1634    2
1635  20230710   161500    161959  1688977199  ...  30027.1 -0.000765   1635    3

[5 rows x 11 columns]
2023-07-10 16:20:06,330:INFO:factorcheck2:main.py:128:handleKline:2218005: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=79, self.factor=0.572076264185821, self.count=16483 

self.closeSec=1688977499, self.tradeDate='20230710', self.openTime='162000', self.closeTime='162459', self.symbol='BTCUSDT', self.open=30050.0, self.close=30061.1, self.high=30075.0, self.low=29966.6 
127.0.0.1 - - [10/Jul/2023 16:25:00] "POST / HTTP/1.1" 200 -
2023-07-10 16:25:00,758:INFO:factorcheck2:main.py:126:handleKline:2218005: self.closeSec=1688977499, self.tradeDate='20230710', self.openTime='162000', self.closeTime='162459',self.symbol='BTCUSDT',self.open=30050.0, self.close=30061.1, self.high=30075.0, self.low=29966.6   
2023-07-10 16:25:00,793:INFO:factorcheck2:main.py:127:handleKline:2218005: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime    closeSec  ...      low       pct  index  idx
1632  20230710   160000    160459  1688976299  ...  30077.4 -0.000744   1632    0
1633  20230710   160500    160959  1688976599  ...  30074.7  0.000276   1633    1
1634  20230710   161000    161459  1688976899  ...  30070.1 -0.000376   1634    2
1635  20230710   161500    161959  1688977199  ...  30027.1 -0.000765   1635    3
1636  20230710   162000    162459  1688977499  ...  29966.6  0.000319   1636    4

[5 rows x 11 columns]
2023-07-10 16:25:00,793:INFO:factorcheck2:main.py:128:handleKline:2218005: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}


## /root/FIL/strategy/logic/log.txt ----- -----

2023-07-10 16:00:19,445:DEBUG:logic:main.py:463:getModel:2218526: df_s.iloc[-5:,:] :
          date closeTime     open  ...    alpha58   alpha67   alpha72
5786  20230710    132959  30108.4  ...  45.416667  0.456297  0.623087
5787  20230710    135959  30099.1  ...  45.416667  0.446310  0.630181
5788  20230710    142959  30068.1  ...  45.833333  0.450023  0.635584
5789  20230710    145959  30077.5  ...  45.416667  0.448879  0.641081
5790  20230710    152959  30073.9  ...  45.833333  0.451318  0.645434

[5 rows x 33 columns]
0.5701107011070111
acc is : 0.5701107011070111
2023-07-10 16:00:19,550:INFO:logic:main.py:468:getModel:2218526: df_pred.iloc[-5:,:] :
     pred    prob_0    prob_1  actual  ...       nav  sign  cost_        bm
537     1  0.497457  0.502543       0  ...  0.970972   1.0    0.0  0.999924
538     1  0.491609  0.508391       1  ...  0.971275   1.0    0.0  1.000236
539     0  0.505743  0.494257       0  ...  0.971162   1.0    0.0  1.000120
540     0  0.502587  0.497413       1  ...  0.971356   1.0    0.0  1.000319
541     0  0.506016  0.493984       1  ...  0.972005   1.0    0.0  1.000988

[5 rows x 10 columns]
2023-07-10 16:00:19,579:INFO:logic:main.py:478:getModel:2218526: df_panel.iloc[-5:,:] :
    pred    prob_0    prob_1  actual  ...       nav  sign  cost_        bm
45     1  0.497430  0.502570       0  ...  0.970972   1.0    0.0  0.999249
46     1  0.491271  0.508729       1  ...  0.972786  -1.0    0.0  0.998831
47     0  0.505702  0.494298       0  ...  0.971162   1.0    0.0  1.000249
48     0  0.502124  0.497876       1  ...  0.971356   1.0    0.0  0.998003
49     0  0.506016  0.493984       1  ...  0.972005   1.0    0.0  1.000988

[5 rows x 10 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '24.788', 'enterprice': '30083.1', 'countrevence': '0', 'unrealprofit': '411.25338298976', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '30099.69082552', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}


## /root/FIL/strategy/modifiedmom/log.txt ----- -----

527  20230710   155000    155959  1688975999  30099.4    30100  0.000017
2023-07-10 16:00:02,195:INFO:modifiedmom:main.py:146:handleKline:2218259: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': True, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True}

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=8240 

self.closeSec=1688976599, self.tradeDate='20230710', self.openTime='160000', self.closeTime='160959', self.symbol='BTCUSDT', self.open='30100', self.close='30085.8'
2023-07-10 16:10:01,123:INFO:modifiedmom:main.py:144:handleKline:2218259: self.closeSec=1688976599, self.tradeDate='20230710', self.openTime='160000', self.closeTime='160959',self.symbol='BTCUSDT',self.open='30100', self.close='30085.8'
127.0.0.1 - - [10/Jul/2023 16:10:01] "POST / HTTP/1.1" 200 -
2023-07-10 16:10:01,141:INFO:modifiedmom:main.py:145:handleKline:2218259: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec     open    close       pct
524  20230710   152000    152959  1688974199  30076.7  30079.9  0.000106
525  20230710   153000    153959  1688974799  30079.9    30092  0.000402
526  20230710   154000    154959  1688975399  30092.1  30099.5  0.000249
527  20230710   155000    155959  1688975999  30099.4    30100  0.000017
528  20230710   160000    160959  1688976599    30100  30085.8 -0.000472
2023-07-10 16:10:01,143:INFO:modifiedmom:main.py:146:handleKline:2218259: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': True, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True}

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=8241 

self.closeSec=1688977199, self.tradeDate='20230710', self.openTime='161000', self.closeTime='161959', self.symbol='BTCUSDT', self.open='30085.7', self.close='30051.4'
127.0.0.1 - - [10/Jul/2023 16:20:04] "POST / HTTP/1.1" 200 -
2023-07-10 16:20:07,091:INFO:modifiedmom:main.py:144:handleKline:2218259: self.closeSec=1688977199, self.tradeDate='20230710', self.openTime='161000', self.closeTime='161959',self.symbol='BTCUSDT',self.open='30085.7', self.close='30051.4'
2023-07-10 16:20:07,841:INFO:modifiedmom:main.py:145:handleKline:2218259: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec     open    close       pct
525  20230710   153000    153959  1688974799  30079.9    30092  0.000402
526  20230710   154000    154959  1688975399  30092.1  30099.5  0.000249
527  20230710   155000    155959  1688975999  30099.4    30100  0.000017
528  20230710   160000    160959  1688976599    30100  30085.8 -0.000472
529  20230710   161000    161959  1688977199  30085.7  30051.4 -0.001143
2023-07-10 16:20:07,841:INFO:modifiedmom:main.py:146:handleKline:2218259: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': True, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True}


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

17519  20230710   155000    155959  1688975999  30099.4    30100
2023-07-10 16:00:02,206:INFO:pyemd2:main.py:127:handleKline:2217508: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=8243 

self.closeSec=1688976599, self.tradeDate='20230710', self.openTime='160000', self.closeTime='160959', self.symbol='BTCUSDT', self.open='30100', self.close='30085.8'
127.0.0.1 - - [10/Jul/2023 16:10:01] "POST / HTTP/1.1" 200 -
2023-07-10 16:10:01,118:INFO:pyemd2:main.py:125:handleKline:2217508: self.closeSec=1688976599, self.tradeDate='20230710', self.openTime='160000', self.closeTime='160959',self.symbol='BTCUSDT',self.open='30100', self.close='30085.8'
2023-07-10 16:10:01,148:INFO:pyemd2:main.py:126:handleKline:2217508: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
17516  20230710   152000    152959  1688974199  30076.7  30079.9
17517  20230710   153000    153959  1688974799  30079.9    30092
17518  20230710   154000    154959  1688975399  30092.1  30099.5
17519  20230710   155000    155959  1688975999  30099.4    30100
17520  20230710   160000    160959  1688976599    30100  30085.8
2023-07-10 16:10:01,148:INFO:pyemd2:main.py:127:handleKline:2217508: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=8244 

self.closeSec=1688977199, self.tradeDate='20230710', self.openTime='161000', self.closeTime='161959', self.symbol='BTCUSDT', self.open='30085.7', self.close='30051.4'
127.0.0.1 - - [10/Jul/2023 16:20:04] "POST / HTTP/1.1" 200 -
2023-07-10 16:20:08,645:INFO:pyemd2:main.py:125:handleKline:2217508: self.closeSec=1688977199, self.tradeDate='20230710', self.openTime='161000', self.closeTime='161959',self.symbol='BTCUSDT',self.open='30085.7', self.close='30051.4'
2023-07-10 16:20:08,853:INFO:pyemd2:main.py:126:handleKline:2217508: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
17517  20230710   153000    153959  1688974799  30079.9    30092
17518  20230710   154000    154959  1688975399  30092.1  30099.5
17519  20230710   155000    155959  1688975999  30099.4    30100
17520  20230710   160000    160959  1688976599    30100  30085.8
17521  20230710   161000    161959  1688977199  30085.7  30051.4
2023-07-10 16:20:08,853:INFO:pyemd2:main.py:127:handleKline:2217508: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}


## /root/FIL/strategy/similarity/log.txt ----- -----

12191  20230710   155000    155959  1688975999  30099.4    30100
2023-07-10 16:00:02,205:INFO:testStrategy:main.py:103:handleKline:2217133: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': True, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True, 'isCorr': False}

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=8243 

self.closeSec=1688976599, self.tradeDate='20230710', self.openTime='160000', self.closeTime='160959', self.symbol='BTCUSDT', self.open='30100', self.close='30085.8'
2023-07-10 16:10:01,108:INFO:testStrategy:main.py:101:handleKline:2217133: self.closeSec=1688976599, self.tradeDate='20230710', self.openTime='160000', self.closeTime='160959',self.symbol='BTCUSDT',self.open='30100', self.close='30085.8'
127.0.0.1 - - [10/Jul/2023 16:10:01] "POST / HTTP/1.1" 200 -
2023-07-10 16:10:01,144:INFO:testStrategy:main.py:102:handleKline:2217133: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
12188  20230710   152000    152959  1688974199  30076.7  30079.9
12189  20230710   153000    153959  1688974799  30079.9    30092
12190  20230710   154000    154959  1688975399  30092.1  30099.5
12191  20230710   155000    155959  1688975999  30099.4    30100
12192  20230710   160000    160959  1688976599    30100  30085.8
2023-07-10 16:10:01,145:INFO:testStrategy:main.py:103:handleKline:2217133: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': True, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True, 'isCorr': False}

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=8244 

self.closeSec=1688977199, self.tradeDate='20230710', self.openTime='161000', self.closeTime='161959', self.symbol='BTCUSDT', self.open='30085.7', self.close='30051.4'
127.0.0.1 - - [10/Jul/2023 16:20:04] "POST / HTTP/1.1" 200 -
2023-07-10 16:20:08,424:INFO:testStrategy:main.py:101:handleKline:2217133: self.closeSec=1688977199, self.tradeDate='20230710', self.openTime='161000', self.closeTime='161959',self.symbol='BTCUSDT',self.open='30085.7', self.close='30051.4'
2023-07-10 16:20:08,703:INFO:testStrategy:main.py:102:handleKline:2217133: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
12189  20230710   153000    153959  1688974799  30079.9    30092
12190  20230710   154000    154959  1688975399  30092.1  30099.5
12191  20230710   155000    155959  1688975999  30099.4    30100
12192  20230710   160000    160959  1688976599    30100  30085.8
12193  20230710   161000    161959  1688977199  30085.7  30051.4
2023-07-10 16:20:08,710:INFO:testStrategy:main.py:103:handleKline:2217133: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': True, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True, 'isCorr': False}


## /root/FIL/strategy/sr_min/log.txt ----- -----

--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=1, self.total=996015.990996, self.flagDict['side']='buy', self.tradeCount=1, self.count=16480
self.closeSec=1688977199, self.tradeDate='20230710', self.openTime='161500', self.closeTime='161959', self.symbol='BTCUSDT', self.open=30074.5, self.close=30051.5, self.high=30084.8, self.low=30027.1, self.vol=1314.943, self.amt=39509322.9407 
127.0.0.1 - - [10/Jul/2023 16:20:01] "POST / HTTP/1.1" 200 -
2023-07-10 16:20:07,151:INFO:sr_min:main.py:172:handleKline:2219263: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5951  20230710   155500    155959  ...         0.0        0.0       0
5952  20230710   160000    160459  ...         0.0        0.0       0
5953  20230710   160500    160959  ...         0.0        0.0       0
5954  20230710   161000    161459  ...         0.0        0.0       0
5955  20230710   161500    161959  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-07-10 16:20:07,180:INFO:sr_min:main.py:175:handleKline:2219263: self.closeSec=1688977199, self.tradeDate='20230710', self.openTime='161500', self.closeTime='161959',self.symbol='BTCUSDT',self.open=30074.5, self.close=30051.5, self.high=30084.8, self.low=30027.1, self.vol=1314.943, self.amt=39509322.9407, ukdf['pct'].iloc[-1]=-0.000765 , ukdf['amount'].iloc[-1]=39509322.9407, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5955, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '37.141', 'enterprice': '26844', 'countrevence': '0', 'unrealprofit': '118892.0551', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '30045.1', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=1
--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=1, self.total=996015.990996, self.flagDict['side']='buy', self.tradeCount=1, self.count=16481
self.closeSec=1688977499, self.tradeDate='20230710', self.openTime='162000', self.closeTime='162459', self.symbol='BTCUSDT', self.open=30050.0, self.close=30061.1, self.high=30075.0, self.low=29966.6, self.vol=3258.28, self.amt=97825681.702 
127.0.0.1 - - [10/Jul/2023 16:25:00] "POST / HTTP/1.1" 200 -
2023-07-10 16:25:00,809:INFO:sr_min:main.py:172:handleKline:2219263: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5952  20230710   160000    160459  ...         0.0        0.0       0
5953  20230710   160500    160959  ...         0.0        0.0       0
5954  20230710   161000    161459  ...         0.0        0.0       0
5955  20230710   161500    161959  ...         0.0        0.0       0
5956  20230710   162000    162459  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-07-10 16:25:00,809:INFO:sr_min:main.py:175:handleKline:2219263: self.closeSec=1688977499, self.tradeDate='20230710', self.openTime='162000', self.closeTime='162459',self.symbol='BTCUSDT',self.open=30050.0, self.close=30061.1, self.high=30075.0, self.low=29966.6, self.vol=3258.28, self.amt=97825681.702, ukdf['pct'].iloc[-1]=0.000319 , ukdf['amount'].iloc[-1]=97825681.702, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5956, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '37.141', 'enterprice': '26844', 'countrevence': '0', 'unrealprofit': '119486.3111', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '30061.1', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=1


## /root/FIL/strategy/s_rsrs/log.txt ----- -----

721  20230710   040000    075959  1688947199  ...    721  0.309598  0.140969     NaN
722  20230710   080000    115959  1688961599  ...    722  0.347591  0.320803     NaN

[5 rows x 15 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '53.05', 'enterprice': '30750.9', 'countrevence': '0', 'unrealprofit': '-32148.3', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '30144.9', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'numpy.int64'>, curSign=-9223372036854775808, self.sign=1
--handleKline--:  version='2.0.0', self.name='s_rsrs', self.symbol='BTCUSDT', interval='4h', intervalSec=14400, wid=25, thd=0.6, self.sign=1, self.total=1629703.909755, self.flagDict['side']='buy', self.tradeCount=9, self.count=343
self.closeSec=1688975999, self.tradeDate='20230710', self.openTime='120000', self.closeTime='155959', self.symbol='BTCUSDT', self.open=30145.0, self.close=30100.0, self.high=30151.0, self.low=30034.2, self.vol=22884.999, self.amt=688719180.2521 
127.0.0.1 - - [10/Jul/2023 16:00:01] "POST / HTTP/1.1" 200 -
2023-07-10 16:00:01,748:INFO:s_rsrs:main.py:141:handleKline:2218689: self.closeSec=1688975999, self.tradeDate='20230710', self.openTime='120000', self.closeTime='155959',self.symbol='BTCUSDT',self.open=30145.0, self.close=30100.0, self.high=30151.0, self.low=30034.2, self.vol=22884.999, self.amt=688719180.2521 
2023-07-10 16:00:01,763:INFO:s_rsrs:main.py:142:handleKline:2218689: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime  ...        vol           amt       pct
719  20230709   200000    235959  ...  52366.130  1.586752e+09  0.002627
720  20230710   000000    035959  ...  20913.947  6.328149e+08 -0.003596
721  20230710   040000    075959  ...  32675.435  9.847616e+08 -0.002643
722  20230710   080000    115959  ...  57315.967  1.724260e+09 -0.000096
723  20230710   120000    155959  ...  22884.999  6.887192e+08 -0.001489

[5 rows x 11 columns]
2023-07-10 16:00:03,117:INFO:s_rsrs:main.py:151:handleKline:2218689: df_s.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec  ...  index      beta    zscore  signal
719  20230709   200000    235959  1688918399  ...    719  0.307437  0.097427     NaN
720  20230710   000000    035959  1688932799  ...    720  0.299840  0.080464     NaN
721  20230710   040000    075959  1688947199  ...    721  0.309598  0.140969     NaN
722  20230710   080000    115959  1688961599  ...    722  0.347591  0.320803     NaN
723  20230710   120000    155959  1688975999  ...    723  0.361744  0.391610     NaN

[5 rows x 15 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '53.05', 'enterprice': '30750.9', 'countrevence': '0', 'unrealprofit': '-34530.245', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '30100', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'numpy.int64'>, curSign=-9223372036854775808, self.sign=1


