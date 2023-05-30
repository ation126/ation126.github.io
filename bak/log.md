# 20230530 16:26:01

## /root/FIL/strategy/amihud/log.txt ----- -----

--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=373746.4768026, self.flagDict['side']='sell', self.tradeCount=2, self.count=4672
self.closeSec=1685434799, self.tradeDate='20230530', self.openTime='161500', self.closeTime='161959', self.symbol='BTCUSDT', self.open=27719.0, self.close=27774.2, self.high=27774.6, self.low=27712.7, self.vol=1239.688, self.amt=34400109.2136 
127.0.0.1 - - [30/May/2023 16:20:01] "POST / HTTP/1.1" 200 -
2023-05-30 16:20:07,316:INFO:amihud:main.py:172:handleKline:2219019: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5951  20230530   155500    155959  ...         0.0        0.0       0
5952  20230530   160000    160459  ...         0.0        0.0       0
5953  20230530   160500    160959  ...         0.0        0.0       0
5954  20230530   161000    161459  ...         0.0        0.0       0
5955  20230530   161500    161959  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-05-30 16:20:07,335:INFO:amihud:main.py:175:handleKline:2219019: self.closeSec=1685434799, self.tradeDate='20230530', self.openTime='161500', self.closeTime='161959',self.symbol='BTCUSDT',self.open=27719.0, self.close=27774.2, self.high=27774.6, self.low=27712.7, self.vol=1239.688, self.amt=34400109.2136, ukdf['pct'].iloc[-1]=0.001995 , ukdf['amount'].iloc[-1]=34400109.2136, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5955, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '13.926', 'enterprice': '26864.9', 'countrevence': '0', 'unrealprofit': '-12650.3784', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '27773.3', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1
127.0.0.1 - - [30/May/2023 16:25:00] "POST / HTTP/1.1" 200 -
--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=373746.4768026, self.flagDict['side']='sell', self.tradeCount=2, self.count=4673
self.closeSec=1685435099, self.tradeDate='20230530', self.openTime='162000', self.closeTime='162459', self.symbol='BTCUSDT', self.open=27774.2, self.close=27769.2, self.high=27774.2, self.low=27750.0, self.vol=628.854, self.amt=17458133.195 
2023-05-30 16:25:00,780:INFO:amihud:main.py:172:handleKline:2219019: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5952  20230530   160000    160459  ...         0.0        0.0       0
5953  20230530   160500    160959  ...         0.0        0.0       0
5954  20230530   161000    161459  ...         0.0        0.0       0
5955  20230530   161500    161959  ...         0.0        0.0       0
5956  20230530   162000    162459  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-05-30 16:25:00,781:INFO:amihud:main.py:175:handleKline:2219019: self.closeSec=1685435099, self.tradeDate='20230530', self.openTime='162000', self.closeTime='162459',self.symbol='BTCUSDT',self.open=27774.2, self.close=27769.2, self.high=27774.2, self.low=27750.0, self.vol=628.854, self.amt=17458133.195, ukdf['pct'].iloc[-1]=-0.00018 , ukdf['amount'].iloc[-1]=17458133.195, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5956, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '13.926', 'enterprice': '26864.9', 'countrevence': '0', 'unrealprofit': '-12603.573114', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '27769.939', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1


## /root/FIL/strategy/factorcheck/log.txt ----- -----


self.closeSec=1685434799, self.tradeDate='20230530', self.openTime='161500', self.closeTime='161959', self.symbol='BTCUSDT', self.open=27719.0, self.close=27774.2, self.high=27774.6, self.low=27712.7 
127.0.0.1 - - [30/May/2023 16:20:01] "POST / HTTP/1.1" 200 -
2023-05-30 16:20:04,895:INFO:factorcheck2:main.py:126:handleKline:2218005: self.closeSec=1685434799, self.tradeDate='20230530', self.openTime='161500', self.closeTime='161959',self.symbol='BTCUSDT',self.open=27719.0, self.close=27774.2, self.high=27774.6, self.low=27712.7   
2023-05-30 16:20:06,435:INFO:factorcheck2:main.py:127:handleKline:2218005: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime    closeSec  ...      low       pct  index  idx
1631  20230530   155500    155959  1685433599  ...  27721.0 -0.000144   1631    5
1632  20230530   160000    160459  1685433899  ...  27720.1  0.000473   1632    0
1633  20230530   160500    160959  1685434199  ...  27731.9  0.000007   1633    1
1634  20230530   161000    161459  1685434499  ...  27697.1 -0.000559   1634    2
1635  20230530   161500    161959  1685434799  ...  27712.7  0.001995   1635    3

[5 rows x 11 columns]
2023-05-30 16:20:06,436:INFO:factorcheck2:main.py:128:handleKline:2218005: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}
127.0.0.1 - - [30/May/2023 16:25:00] "POST / HTTP/1.1" 200 -

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=179, self.factor=0.4729641398501201, self.count=4675 

self.closeSec=1685435099, self.tradeDate='20230530', self.openTime='162000', self.closeTime='162459', self.symbol='BTCUSDT', self.open=27774.2, self.close=27769.2, self.high=27774.2, self.low=27750.0 
2023-05-30 16:25:00,738:INFO:factorcheck2:main.py:126:handleKline:2218005: self.closeSec=1685435099, self.tradeDate='20230530', self.openTime='162000', self.closeTime='162459',self.symbol='BTCUSDT',self.open=27774.2, self.close=27769.2, self.high=27774.2, self.low=27750.0   
2023-05-30 16:25:00,837:INFO:factorcheck2:main.py:127:handleKline:2218005: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime    closeSec  ...      low       pct  index  idx
1632  20230530   160000    160459  1685433899  ...  27720.1  0.000473   1632    0
1633  20230530   160500    160959  1685434199  ...  27731.9  0.000007   1633    1
1634  20230530   161000    161459  1685434499  ...  27697.1 -0.000559   1634    2
1635  20230530   161500    161959  1685434799  ...  27712.7  0.001995   1635    3
1636  20230530   162000    162459  1685435099  ...  27750.0 -0.000180   1636    4

[5 rows x 11 columns]
2023-05-30 16:25:00,837:INFO:factorcheck2:main.py:128:handleKline:2218005: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}


## /root/FIL/strategy/logic/log.txt ----- -----

2023-05-30 16:00:33,234:DEBUG:logic:main.py:463:getModel:2218526: df_s.iloc[-5:,:] :
          date closeTime     open  ...    alpha58   alpha67   alpha72
5786  20230530    132959  27767.0  ...  50.000000  0.531154  0.571518
5787  20230530    135959  27715.1  ...  50.416667  0.537038  0.566500
5788  20230530    142959  27741.8  ...  50.833333  0.542891  0.556039
5789  20230530    145959  27768.5  ...  50.833333  0.546485  0.543744
5790  20230530    152959  27785.0  ...  50.833333  0.544567  0.533380

[5 rows x 33 columns]
0.5295202952029521
acc is : 0.5295202952029521
2023-05-30 16:00:33,408:INFO:logic:main.py:468:getModel:2218526: df_pred.iloc[-5:,:] :
     pred    prob_0    prob_1  actual  ...       nav  sign  cost_        bm
537     1  0.486485  0.513515       1  ...  1.003397  -1.0    0.0  1.032403
538     1  0.493649  0.506351       1  ...  1.002431  -1.0    0.0  1.033396
539     1  0.497368  0.502632       1  ...  1.001839  -1.0    0.0  1.034007
540     1  0.498068  0.501932       0  ...  1.002098  -1.0    0.0  1.033739
541     1  0.494699  0.505301       0  ...  1.004144  -1.0    0.0  1.031629

[5 rows x 10 columns]
2023-05-30 16:00:33,448:INFO:logic:main.py:478:getModel:2218526: df_panel.iloc[-5:,:] :
    pred    prob_0    prob_1  actual  ...       nav  sign  cost_        bm
45     1  0.486558  0.513442       1  ...  1.003397  -1.0    0.0  1.032076
46     1  0.494143  0.505857       1  ...  1.002431  -1.0    0.0  1.034895
47     1  0.497487  0.502513       1  ...  1.001839  -1.0    0.0  1.036390
48     1  0.498180  0.501820       0  ...  1.002098  -1.0    0.0  1.034439
49     1  0.494699  0.505301       0  ...  1.004144  -1.0    0.0  1.031629

[5 rows x 10 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '25.849', 'enterprice': '27935.3', 'countrevence': '0', 'unrealprofit': '5345.5732', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '27728.5', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}


## /root/FIL/strategy/modifiedmom/log.txt ----- -----

527  20230530   155000    155959  1685433599  27746.8    27721 -0.000930
2023-05-30 16:00:02,272:INFO:modifiedmom:main.py:146:handleKline:2218259: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': True, 'isOpenSell': False, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True}

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=2336 

self.closeSec=1685434199, self.tradeDate='20230530', self.openTime='160000', self.closeTime='160959', self.symbol='BTCUSDT', self.open='27721.1', self.close='27734.4'
2023-05-30 16:10:01,110:INFO:modifiedmom:main.py:144:handleKline:2218259: self.closeSec=1685434199, self.tradeDate='20230530', self.openTime='160000', self.closeTime='160959',self.symbol='BTCUSDT',self.open='27721.1', self.close='27734.4'
2023-05-30 16:10:01,117:INFO:modifiedmom:main.py:145:handleKline:2218259: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec     open    close       pct
524  20230530   152000    152959  1685431799  27796.2  27777.7 -0.000662
525  20230530   153000    153959  1685432399  27777.6  27740.1 -0.001354
526  20230530   154000    154959  1685432999  27740.1  27746.8  0.000242
527  20230530   155000    155959  1685433599  27746.8    27721 -0.000930
528  20230530   160000    160959  1685434199  27721.1  27734.4  0.000483
2023-05-30 16:10:01,117:INFO:modifiedmom:main.py:146:handleKline:2218259: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': True, 'isOpenSell': False, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True}
127.0.0.1 - - [30/May/2023 16:10:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=2337 

self.closeSec=1685434799, self.tradeDate='20230530', self.openTime='161000', self.closeTime='161959', self.symbol='BTCUSDT', self.open='27734.4', self.close='27774.2'
127.0.0.1 - - [30/May/2023 16:20:04] "POST / HTTP/1.1" 200 -
2023-05-30 16:20:07,094:INFO:modifiedmom:main.py:144:handleKline:2218259: self.closeSec=1685434799, self.tradeDate='20230530', self.openTime='161000', self.closeTime='161959',self.symbol='BTCUSDT',self.open='27734.4', self.close='27774.2'
2023-05-30 16:20:07,805:INFO:modifiedmom:main.py:145:handleKline:2218259: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec     open    close       pct
525  20230530   153000    153959  1685432399  27777.6  27740.1 -0.001354
526  20230530   154000    154959  1685432999  27740.1  27746.8  0.000242
527  20230530   155000    155959  1685433599  27746.8    27721 -0.000930
528  20230530   160000    160959  1685434199  27721.1  27734.4  0.000483
529  20230530   161000    161959  1685434799  27734.4  27774.2  0.001435
2023-05-30 16:20:07,806:INFO:modifiedmom:main.py:146:handleKline:2218259: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': True, 'isOpenSell': False, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True}


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

17519  20230530   155000    155959  1685433599  27746.8    27721
2023-05-30 16:00:02,296:INFO:pyemd2:main.py:127:handleKline:2217508: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}
127.0.0.1 - - [30/May/2023 16:10:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=2339 

self.closeSec=1685434199, self.tradeDate='20230530', self.openTime='160000', self.closeTime='160959', self.symbol='BTCUSDT', self.open='27721.1', self.close='27734.4'
2023-05-30 16:10:01,097:INFO:pyemd2:main.py:125:handleKline:2217508: self.closeSec=1685434199, self.tradeDate='20230530', self.openTime='160000', self.closeTime='160959',self.symbol='BTCUSDT',self.open='27721.1', self.close='27734.4'
2023-05-30 16:10:01,135:INFO:pyemd2:main.py:126:handleKline:2217508: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
17516  20230530   152000    152959  1685431799  27796.2  27777.7
17517  20230530   153000    153959  1685432399  27777.6  27740.1
17518  20230530   154000    154959  1685432999  27740.1  27746.8
17519  20230530   155000    155959  1685433599  27746.8    27721
17520  20230530   160000    160959  1685434199  27721.1  27734.4
2023-05-30 16:10:01,136:INFO:pyemd2:main.py:127:handleKline:2217508: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=2340 

self.closeSec=1685434799, self.tradeDate='20230530', self.openTime='161000', self.closeTime='161959', self.symbol='BTCUSDT', self.open='27734.4', self.close='27774.2'
127.0.0.1 - - [30/May/2023 16:20:04] "POST / HTTP/1.1" 200 -
2023-05-30 16:20:08,817:INFO:pyemd2:main.py:125:handleKline:2217508: self.closeSec=1685434799, self.tradeDate='20230530', self.openTime='161000', self.closeTime='161959',self.symbol='BTCUSDT',self.open='27734.4', self.close='27774.2'
2023-05-30 16:20:08,918:INFO:pyemd2:main.py:126:handleKline:2217508: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
17517  20230530   153000    153959  1685432399  27777.6  27740.1
17518  20230530   154000    154959  1685432999  27740.1  27746.8
17519  20230530   155000    155959  1685433599  27746.8    27721
17520  20230530   160000    160959  1685434199  27721.1  27734.4
17521  20230530   161000    161959  1685434799  27734.4  27774.2
2023-05-30 16:20:08,918:INFO:pyemd2:main.py:127:handleKline:2217508: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}


## /root/FIL/strategy/similarity/log.txt ----- -----

12191  20230530   155000    155959  1685433599  27746.8    27721
2023-05-30 16:00:02,272:INFO:testStrategy:main.py:103:handleKline:2217133: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': True, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True, 'isCorr': False}
127.0.0.1 - - [30/May/2023 16:10:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=2339 

self.closeSec=1685434199, self.tradeDate='20230530', self.openTime='160000', self.closeTime='160959', self.symbol='BTCUSDT', self.open='27721.1', self.close='27734.4'
2023-05-30 16:10:01,119:INFO:testStrategy:main.py:101:handleKline:2217133: self.closeSec=1685434199, self.tradeDate='20230530', self.openTime='160000', self.closeTime='160959',self.symbol='BTCUSDT',self.open='27721.1', self.close='27734.4'
2023-05-30 16:10:01,128:INFO:testStrategy:main.py:102:handleKline:2217133: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
12188  20230530   152000    152959  1685431799  27796.2  27777.7
12189  20230530   153000    153959  1685432399  27777.6  27740.1
12190  20230530   154000    154959  1685432999  27740.1  27746.8
12191  20230530   155000    155959  1685433599  27746.8    27721
12192  20230530   160000    160959  1685434199  27721.1  27734.4
2023-05-30 16:10:01,128:INFO:testStrategy:main.py:103:handleKline:2217133: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': True, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True, 'isCorr': False}

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=2340 

self.closeSec=1685434799, self.tradeDate='20230530', self.openTime='161000', self.closeTime='161959', self.symbol='BTCUSDT', self.open='27734.4', self.close='27774.2'
127.0.0.1 - - [30/May/2023 16:20:04] "POST / HTTP/1.1" 200 -
2023-05-30 16:20:08,446:INFO:testStrategy:main.py:101:handleKline:2217133: self.closeSec=1685434799, self.tradeDate='20230530', self.openTime='161000', self.closeTime='161959',self.symbol='BTCUSDT',self.open='27734.4', self.close='27774.2'
2023-05-30 16:20:08,757:INFO:testStrategy:main.py:102:handleKline:2217133: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
12189  20230530   153000    153959  1685432399  27777.6  27740.1
12190  20230530   154000    154959  1685432999  27740.1  27746.8
12191  20230530   155000    155959  1685433599  27746.8    27721
12192  20230530   160000    160959  1685434199  27721.1  27734.4
12193  20230530   161000    161959  1685434799  27734.4  27774.2
2023-05-30 16:20:08,758:INFO:testStrategy:main.py:103:handleKline:2217133: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': True, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True, 'isCorr': False}


## /root/FIL/strategy/sr_min/log.txt ----- -----

--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=1, self.total=996015.990996, self.flagDict['side']='buy', self.tradeCount=1, self.count=4672
self.closeSec=1685434799, self.tradeDate='20230530', self.openTime='161500', self.closeTime='161959', self.symbol='BTCUSDT', self.open=27719.0, self.close=27774.2, self.high=27774.6, self.low=27712.7, self.vol=1239.688, self.amt=34400109.2136 
127.0.0.1 - - [30/May/2023 16:20:01] "POST / HTTP/1.1" 200 -
2023-05-30 16:20:07,296:INFO:sr_min:main.py:172:handleKline:2219263: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5951  20230530   155500    155959  ...         0.0        0.0       0
5952  20230530   160000    160459  ...         0.0        0.0       0
5953  20230530   160500    160959  ...         0.0        0.0       0
5954  20230530   161000    161459  ...         0.0        0.0       0
5955  20230530   161500    161959  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-05-30 16:20:07,315:INFO:sr_min:main.py:175:handleKline:2219263: self.closeSec=1685434799, self.tradeDate='20230530', self.openTime='161500', self.closeTime='161959',self.symbol='BTCUSDT',self.open=27719.0, self.close=27774.2, self.high=27774.6, self.low=27712.7, self.vol=1239.688, self.amt=34400109.2136, ukdf['pct'].iloc[-1]=0.001995 , ukdf['amount'].iloc[-1]=34400109.2136, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5955, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '37.141', 'enterprice': '26844', 'countrevence': '0', 'unrealprofit': '34515.1313', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '27773.3', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=1
127.0.0.1 - - [30/May/2023 16:25:00] "POST / HTTP/1.1" 200 -
--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=1, self.total=996015.990996, self.flagDict['side']='buy', self.tradeCount=1, self.count=4673
self.closeSec=1685435099, self.tradeDate='20230530', self.openTime='162000', self.closeTime='162459', self.symbol='BTCUSDT', self.open=27774.2, self.close=27769.2, self.high=27774.2, self.low=27750.0, self.vol=628.854, self.amt=17458133.195 
2023-05-30 16:25:00,871:INFO:sr_min:main.py:172:handleKline:2219263: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5952  20230530   160000    160459  ...         0.0        0.0       0
5953  20230530   160500    160959  ...         0.0        0.0       0
5954  20230530   161000    161459  ...         0.0        0.0       0
5955  20230530   161500    161959  ...         0.0        0.0       0
5956  20230530   162000    162459  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-05-30 16:25:00,871:INFO:sr_min:main.py:175:handleKline:2219263: self.closeSec=1685435099, self.tradeDate='20230530', self.openTime='162000', self.closeTime='162459',self.symbol='BTCUSDT',self.open=27774.2, self.close=27769.2, self.high=27774.2, self.low=27750.0, self.vol=628.854, self.amt=17458133.195, ukdf['pct'].iloc[-1]=-0.00018 , ukdf['amount'].iloc[-1]=17458133.195, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5956, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '37.141', 'enterprice': '26844', 'countrevence': '0', 'unrealprofit': '34390.300399', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '27769.939', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=1


## /root/FIL/strategy/s_rsrs/log.txt ----- -----

721  20230530   040000    075959  1685404799  ...    721  1.159886  2.726214     1.0
722  20230530   080000    115959  1685419199  ...    722  1.147408  2.547483     1.0

[5 rows x 15 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '55.249', 'enterprice': '26128.2', 'countrevence': '0', 'unrealprofit': '93508.9325', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '27820.7', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'numpy.int64'>, curSign=1, self.sign=1
127.0.0.1 - - [30/May/2023 16:00:01] "POST / HTTP/1.1" 200 -
--handleKline--:  version='2.0.0', self.name='s_rsrs', self.symbol='BTCUSDT', interval='4h', intervalSec=14400, wid=25, thd=0.6, self.sign=1, self.total=1442113.3648782002, self.flagDict['side']='buy', self.tradeCount=3, self.count=97
self.closeSec=1685433599, self.tradeDate='20230530', self.openTime='120000', self.closeTime='155959', self.symbol='BTCUSDT', self.open=27815.0, self.close=27721.1, self.high=27839.3, self.low=27659.3, self.vol=36390.572, self.amt=1010080465.75202 
2023-05-30 16:00:01,816:INFO:s_rsrs:main.py:141:handleKline:2218689: self.closeSec=1685433599, self.tradeDate='20230530', self.openTime='120000', self.closeTime='155959',self.symbol='BTCUSDT',self.open=27815.0, self.close=27721.1, self.high=27839.3, self.low=27659.3, self.vol=36390.572, self.amt=1010080465.75202 
2023-05-30 16:00:01,869:INFO:s_rsrs:main.py:142:handleKline:2218689: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime  ...        vol           amt       pct
719  20230529   200000    235959  ...  81223.202  2.254190e+09 -0.010252
720  20230530   000000    035959  ...  75215.644  2.077855e+09  0.000072
721  20230530   040000    075959  ...  41577.115  1.150710e+09  0.003548
722  20230530   080000    115959  ...  45946.311  1.275505e+09  0.003355
723  20230530   120000    155959  ...  36390.572  1.010080e+09 -0.003376

[5 rows x 11 columns]
2023-05-30 16:00:03,804:INFO:s_rsrs:main.py:151:handleKline:2218689: df_s.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec  ...  index      beta    zscore  signal
719  20230529   200000    235959  1685375999  ...    719  1.106273  2.811384     1.0
720  20230530   000000    035959  1685390399  ...    720  1.107363  2.667881     1.0
721  20230530   040000    075959  1685404799  ...    721  1.159886  2.726214     1.0
722  20230530   080000    115959  1685419199  ...    722  1.147408  2.547483     1.0
723  20230530   120000    155959  1685433599  ...    723  1.104430  2.288963     1.0

[5 rows x 15 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '55.249', 'enterprice': '26128.2', 'countrevence': '0', 'unrealprofit': '88210.18486872787', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '27724.79332963', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'numpy.int64'>, curSign=1, self.sign=1


