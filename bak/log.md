# 20230529 16:26:01

## /root/FIL/strategy/amihud/log.txt ----- -----

--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=373746.4768026, self.flagDict['side']='sell', self.tradeCount=2, self.count=4384
self.closeSec=1685348399, self.tradeDate='20230529', self.openTime='161500', self.closeTime='161959', self.symbol='BTCUSDT', self.open=27901.0, self.close=27892.2, self.high=27923.2, self.low=27886.8, self.vol=579.648, self.amt=16174643.6763 
127.0.0.1 - - [29/May/2023 16:20:01] "POST / HTTP/1.1" 200 -
2023-05-29 16:20:05,965:INFO:amihud:main.py:172:handleKline:2219019: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5951  20230529   155500    155959  ...         0.0        0.0       0
5952  20230529   160000    160459  ...         0.0        0.0       0
5953  20230529   160500    160959  ...         0.0        0.0       0
5954  20230529   161000    161459  ...         0.0        0.0       0
5955  20230529   161500    161959  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-05-29 16:20:05,975:INFO:amihud:main.py:175:handleKline:2219019: self.closeSec=1685348399, self.tradeDate='20230529', self.openTime='161500', self.closeTime='161959',self.symbol='BTCUSDT',self.open=27901.0, self.close=27892.2, self.high=27923.2, self.low=27886.8, self.vol=579.648, self.amt=16174643.6763, ukdf['pct'].iloc[-1]=-0.000312 , ukdf['amount'].iloc[-1]=16174643.6763, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5955, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '13.926', 'enterprice': '26864.9', 'countrevence': '0', 'unrealprofit': '-14300.18212970952', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '27891.76931852', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1
--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=373746.4768026, self.flagDict['side']='sell', self.tradeCount=2, self.count=4385
self.closeSec=1685348699, self.tradeDate='20230529', self.openTime='162000', self.closeTime='162459', self.symbol='BTCUSDT', self.open=27892.2, self.close=27878.9, self.high=27892.3, self.low=27878.9, self.vol=723.727, self.amt=20179962.1764 
127.0.0.1 - - [29/May/2023 16:25:00] "POST / HTTP/1.1" 200 -
2023-05-29 16:25:00,823:INFO:amihud:main.py:172:handleKline:2219019: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5952  20230529   160000    160459  ...         0.0        0.0       0
5953  20230529   160500    160959  ...         0.0        0.0       0
5954  20230529   161000    161459  ...         0.0        0.0       0
5955  20230529   161500    161959  ...         0.0        0.0       0
5956  20230529   162000    162459  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-05-29 16:25:00,826:INFO:amihud:main.py:175:handleKline:2219019: self.closeSec=1685348699, self.tradeDate='20230529', self.openTime='162000', self.closeTime='162459',self.symbol='BTCUSDT',self.open=27892.2, self.close=27878.9, self.high=27892.3, self.low=27878.9, self.vol=723.727, self.amt=20179962.1764, ukdf['pct'].iloc[-1]=-0.000477 , ukdf['amount'].iloc[-1]=20179962.1764, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5956, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '13.926', 'enterprice': '26864.9', 'countrevence': '0', 'unrealprofit': '-14122.3566', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '27879', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1


## /root/FIL/strategy/factorcheck/log.txt ----- -----


self.closeSec=1685348399, self.tradeDate='20230529', self.openTime='161500', self.closeTime='161959', self.symbol='BTCUSDT', self.open=27901.0, self.close=27892.2, self.high=27923.2, self.low=27886.8 
127.0.0.1 - - [29/May/2023 16:20:01] "POST / HTTP/1.1" 200 -
2023-05-29 16:20:04,055:INFO:factorcheck2:main.py:126:handleKline:2218005: self.closeSec=1685348399, self.tradeDate='20230529', self.openTime='161500', self.closeTime='161959',self.symbol='BTCUSDT',self.open=27901.0, self.close=27892.2, self.high=27923.2, self.low=27886.8   
2023-05-29 16:20:05,045:INFO:factorcheck2:main.py:127:handleKline:2218005: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime    closeSec  ...      low       pct  index  idx
1631  20230529   155500    155959  1685347199  ...  27894.1 -0.000401   1631    5
1632  20230529   160000    160459  1685347499  ...  27893.9  0.001122   1632    0
1633  20230529   160500    160959  1685347799  ...  27913.5 -0.000455   1633    1
1634  20230529   161000    161459  1685348099  ...  27898.6 -0.000455   1634    2
1635  20230529   161500    161959  1685348399  ...  27886.8 -0.000312   1635    3

[5 rows x 11 columns]
2023-05-29 16:20:05,045:INFO:factorcheck2:main.py:128:handleKline:2218005: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=131, self.factor=0.19196572826517025, self.count=4387 

self.closeSec=1685348699, self.tradeDate='20230529', self.openTime='162000', self.closeTime='162459', self.symbol='BTCUSDT', self.open=27892.2, self.close=27878.9, self.high=27892.3, self.low=27878.9 
127.0.0.1 - - [29/May/2023 16:25:00] "POST / HTTP/1.1" 200 -
2023-05-29 16:25:00,753:INFO:factorcheck2:main.py:126:handleKline:2218005: self.closeSec=1685348699, self.tradeDate='20230529', self.openTime='162000', self.closeTime='162459',self.symbol='BTCUSDT',self.open=27892.2, self.close=27878.9, self.high=27892.3, self.low=27878.9   
2023-05-29 16:25:00,798:INFO:factorcheck2:main.py:127:handleKline:2218005: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime    closeSec  ...      low       pct  index  idx
1632  20230529   160000    160459  1685347499  ...  27893.9  0.001122   1632    0
1633  20230529   160500    160959  1685347799  ...  27913.5 -0.000455   1633    1
1634  20230529   161000    161459  1685348099  ...  27898.6 -0.000455   1634    2
1635  20230529   161500    161959  1685348399  ...  27886.8 -0.000312   1635    3
1636  20230529   162000    162459  1685348699  ...  27878.9 -0.000477   1636    4

[5 rows x 11 columns]
2023-05-29 16:25:00,798:INFO:factorcheck2:main.py:128:handleKline:2218005: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}


## /root/FIL/strategy/logic/log.txt ----- -----

2023-05-29 16:00:31,803:DEBUG:logic:main.py:463:getModel:2218526: df_s.iloc[-5:,:] :
          date closeTime     open  ...    alpha58   alpha67   alpha72
5786  20230529    132959  27944.7  ...  49.583333  0.659092  0.239616
5787  20230529    135959  28013.3  ...  49.583333  0.650381  0.246122
5788  20230529    142959  27983.3  ...  50.000000  0.656116  0.250376
5789  20230529    145959  28020.5  ...  50.000000  0.650132  0.255346
5790  20230529    152959  28000.0  ...  50.000000  0.618526  0.265474

[5 rows x 33 columns]
0.5276752767527675
acc is : 0.5276752767527675
2023-05-29 16:00:31,959:INFO:logic:main.py:468:getModel:2218526: df_pred.iloc[-5:,:] :
     pred    prob_0    prob_1  actual  ...       nav  sign  cost_        bm
537     1  0.485112  0.514888       0  ...  0.969100  -1.0    0.0  1.023226
538     1  0.464470  0.535530       1  ...  0.967815  -1.0    0.0  1.024583
539     1  0.491559  0.508441       0  ...  0.968520  -1.0    0.0  1.023837
540     1  0.483246  0.516754       0  ...  0.972394  -1.0    0.0  1.019742
541     1  0.458160  0.541840       1  ...  0.972150  -1.0    0.0  1.019998

[5 rows x 10 columns]
2023-05-29 16:00:31,985:INFO:logic:main.py:478:getModel:2218526: df_panel.iloc[-5:,:] :
    pred    prob_0    prob_1  actual  ...       nav  sign  cost_        bm
45     1  0.484628  0.515372       0  ...  0.969100  -1.0    0.0  1.024200
46     1  0.463861  0.536139       1  ...  0.967815  -1.0    0.0  1.022351
47     1  0.491304  0.508696       0  ...  0.968520  -1.0    0.0  1.022054
48     1  0.483062  0.516938       0  ...  0.972394  -1.0    0.0  1.018033
49     1  0.458160  0.541840       1  ...  0.972150  -1.0    0.0  1.019998

[5 rows x 10 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '25.849', 'enterprice': '27935.3', 'countrevence': '0', 'unrealprofit': '956.0046814413', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '27898.3157963', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}


## /root/FIL/strategy/modifiedmom/log.txt ----- -----

527  20230529   155000    155959  1685347199  27899.4    27895 -0.000158
2023-05-29 16:00:02,358:INFO:modifiedmom:main.py:146:handleKline:2218259: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': True, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True}
127.0.0.1 - - [29/May/2023 16:10:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=2192 

self.closeSec=1685347799, self.tradeDate='20230529', self.openTime='160000', self.closeTime='160959', self.symbol='BTCUSDT', self.open='27895', self.close='27913.6'
2023-05-29 16:10:01,101:INFO:modifiedmom:main.py:144:handleKline:2218259: self.closeSec=1685347799, self.tradeDate='20230529', self.openTime='160000', self.closeTime='160959',self.symbol='BTCUSDT',self.open='27895', self.close='27913.6'
2023-05-29 16:10:01,177:INFO:modifiedmom:main.py:145:handleKline:2218259: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec     open    close       pct
524  20230529   152000    152959  1685345399  27910.4  27888.8 -0.000774
525  20230529   153000    153959  1685345999  27888.9  27886.1 -0.000097
526  20230529   154000    154959  1685346599  27886.1  27899.4  0.000477
527  20230529   155000    155959  1685347199  27899.4    27895 -0.000158
528  20230529   160000    160959  1685347799    27895  27913.6  0.000667
2023-05-29 16:10:01,177:INFO:modifiedmom:main.py:146:handleKline:2218259: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': True, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True}

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=2193 

self.closeSec=1685348399, self.tradeDate='20230529', self.openTime='161000', self.closeTime='161959', self.symbol='BTCUSDT', self.open='27913.5', self.close='27892.2'
127.0.0.1 - - [29/May/2023 16:20:04] "POST / HTTP/1.1" 200 -
2023-05-29 16:20:05,985:INFO:modifiedmom:main.py:144:handleKline:2218259: self.closeSec=1685348399, self.tradeDate='20230529', self.openTime='161000', self.closeTime='161959',self.symbol='BTCUSDT',self.open='27913.5', self.close='27892.2'
2023-05-29 16:20:06,685:INFO:modifiedmom:main.py:145:handleKline:2218259: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec     open    close       pct
525  20230529   153000    153959  1685345999  27888.9  27886.1 -0.000097
526  20230529   154000    154959  1685346599  27886.1  27899.4  0.000477
527  20230529   155000    155959  1685347199  27899.4    27895 -0.000158
528  20230529   160000    160959  1685347799    27895  27913.6  0.000667
529  20230529   161000    161959  1685348399  27913.5  27892.2 -0.000767
2023-05-29 16:20:06,685:INFO:modifiedmom:main.py:146:handleKline:2218259: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': True, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True}


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

17519  20230529   155000    155959  1685347199  27899.4    27895
2023-05-29 16:00:02,359:INFO:pyemd2:main.py:127:handleKline:2217508: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=2195 

self.closeSec=1685347799, self.tradeDate='20230529', self.openTime='160000', self.closeTime='160959', self.symbol='BTCUSDT', self.open='27895', self.close='27913.6'
2023-05-29 16:10:01,101:INFO:pyemd2:main.py:125:handleKline:2217508: self.closeSec=1685347799, self.tradeDate='20230529', self.openTime='160000', self.closeTime='160959',self.symbol='BTCUSDT',self.open='27895', self.close='27913.6'
127.0.0.1 - - [29/May/2023 16:10:01] "POST / HTTP/1.1" 200 -
2023-05-29 16:10:01,136:INFO:pyemd2:main.py:126:handleKline:2217508: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
17516  20230529   152000    152959  1685345399  27910.4  27888.8
17517  20230529   153000    153959  1685345999  27888.9  27886.1
17518  20230529   154000    154959  1685346599  27886.1  27899.4
17519  20230529   155000    155959  1685347199  27899.4    27895
17520  20230529   160000    160959  1685347799    27895  27913.6
2023-05-29 16:10:01,136:INFO:pyemd2:main.py:127:handleKline:2217508: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=2196 

self.closeSec=1685348399, self.tradeDate='20230529', self.openTime='161000', self.closeTime='161959', self.symbol='BTCUSDT', self.open='27913.5', self.close='27892.2'
127.0.0.1 - - [29/May/2023 16:20:04] "POST / HTTP/1.1" 200 -
2023-05-29 16:20:07,457:INFO:pyemd2:main.py:125:handleKline:2217508: self.closeSec=1685348399, self.tradeDate='20230529', self.openTime='161000', self.closeTime='161959',self.symbol='BTCUSDT',self.open='27913.5', self.close='27892.2'
2023-05-29 16:20:07,565:INFO:pyemd2:main.py:126:handleKline:2217508: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
17517  20230529   153000    153959  1685345999  27888.9  27886.1
17518  20230529   154000    154959  1685346599  27886.1  27899.4
17519  20230529   155000    155959  1685347199  27899.4    27895
17520  20230529   160000    160959  1685347799    27895  27913.6
17521  20230529   161000    161959  1685348399  27913.5  27892.2
2023-05-29 16:20:07,565:INFO:pyemd2:main.py:127:handleKline:2217508: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}


## /root/FIL/strategy/similarity/log.txt ----- -----

12191  20230529   155000    155959  1685347199  27899.4    27895
2023-05-29 16:00:02,375:INFO:testStrategy:main.py:103:handleKline:2217133: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': True, 'isOpenSell': False, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True, 'isCorr': False}
127.0.0.1 - - [29/May/2023 16:10:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=2195 

self.closeSec=1685347799, self.tradeDate='20230529', self.openTime='160000', self.closeTime='160959', self.symbol='BTCUSDT', self.open='27895', self.close='27913.6'
2023-05-29 16:10:01,122:INFO:testStrategy:main.py:101:handleKline:2217133: self.closeSec=1685347799, self.tradeDate='20230529', self.openTime='160000', self.closeTime='160959',self.symbol='BTCUSDT',self.open='27895', self.close='27913.6'
2023-05-29 16:10:01,182:INFO:testStrategy:main.py:102:handleKline:2217133: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
12188  20230529   152000    152959  1685345399  27910.4  27888.8
12189  20230529   153000    153959  1685345999  27888.9  27886.1
12190  20230529   154000    154959  1685346599  27886.1  27899.4
12191  20230529   155000    155959  1685347199  27899.4    27895
12192  20230529   160000    160959  1685347799    27895  27913.6
2023-05-29 16:10:01,182:INFO:testStrategy:main.py:103:handleKline:2217133: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': True, 'isOpenSell': False, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True, 'isCorr': False}

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=2196 

self.closeSec=1685348399, self.tradeDate='20230529', self.openTime='161000', self.closeTime='161959', self.symbol='BTCUSDT', self.open='27913.5', self.close='27892.2'
127.0.0.1 - - [29/May/2023 16:20:04] "POST / HTTP/1.1" 200 -
2023-05-29 16:20:07,177:INFO:testStrategy:main.py:101:handleKline:2217133: self.closeSec=1685348399, self.tradeDate='20230529', self.openTime='161000', self.closeTime='161959',self.symbol='BTCUSDT',self.open='27913.5', self.close='27892.2'
2023-05-29 16:20:07,408:INFO:testStrategy:main.py:102:handleKline:2217133: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
12189  20230529   153000    153959  1685345999  27888.9  27886.1
12190  20230529   154000    154959  1685346599  27886.1  27899.4
12191  20230529   155000    155959  1685347199  27899.4    27895
12192  20230529   160000    160959  1685347799    27895  27913.6
12193  20230529   161000    161959  1685348399  27913.5  27892.2
2023-05-29 16:20:07,414:INFO:testStrategy:main.py:103:handleKline:2217133: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': True, 'isOpenSell': False, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True, 'isCorr': False}


## /root/FIL/strategy/sr_min/log.txt ----- -----

--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=1, self.total=996015.990996, self.flagDict['side']='buy', self.tradeCount=1, self.count=4384
self.closeSec=1685348399, self.tradeDate='20230529', self.openTime='161500', self.closeTime='161959', self.symbol='BTCUSDT', self.open=27901.0, self.close=27892.2, self.high=27923.2, self.low=27886.8, self.vol=579.648, self.amt=16174643.6763 
127.0.0.1 - - [29/May/2023 16:20:01] "POST / HTTP/1.1" 200 -
2023-05-29 16:20:05,944:INFO:sr_min:main.py:172:handleKline:2219263: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5951  20230529   155500    155959  ...         0.0        0.0       0
5952  20230529   160000    160459  ...         0.0        0.0       0
5953  20230529   160500    160959  ...         0.0        0.0       0
5954  20230529   161000    161459  ...         0.0        0.0       0
5955  20230529   161500    161959  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-05-29 16:20:05,964:INFO:sr_min:main.py:175:handleKline:2219263: self.closeSec=1685348399, self.tradeDate='20230529', self.openTime='161500', self.closeTime='161959',self.symbol='BTCUSDT',self.open=27901.0, self.close=27892.2, self.high=27923.2, self.low=27886.8, self.vol=579.648, self.amt=16174643.6763, ukdf['pct'].iloc[-1]=-0.000312 , ukdf['amount'].iloc[-1]=16174643.6763, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5955, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '37.141', 'enterprice': '26844', 'countrevence': '0', 'unrealprofit': '38915.20025915132', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '27891.76931852', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=1
127.0.0.1 - - [29/May/2023 16:25:00] "POST / HTTP/1.1" 200 -
--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=1, self.total=996015.990996, self.flagDict['side']='buy', self.tradeCount=1, self.count=4385
self.closeSec=1685348699, self.tradeDate='20230529', self.openTime='162000', self.closeTime='162459', self.symbol='BTCUSDT', self.open=27892.2, self.close=27878.9, self.high=27892.3, self.low=27878.9, self.vol=723.727, self.amt=20179962.1764 
2023-05-29 16:25:00,819:INFO:sr_min:main.py:172:handleKline:2219263: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5952  20230529   160000    160459  ...         0.0        0.0       0
5953  20230529   160500    160959  ...         0.0        0.0       0
5954  20230529   161000    161459  ...         0.0        0.0       0
5955  20230529   161500    161959  ...         0.0        0.0       0
5956  20230529   162000    162459  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-05-29 16:25:00,819:INFO:sr_min:main.py:175:handleKline:2219263: self.closeSec=1685348699, self.tradeDate='20230529', self.openTime='162000', self.closeTime='162459',self.symbol='BTCUSDT',self.open=27892.2, self.close=27878.9, self.high=27892.3, self.low=27878.9, self.vol=723.727, self.amt=20179962.1764, ukdf['pct'].iloc[-1]=-0.000477 , ukdf['amount'].iloc[-1]=20179962.1764, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5956, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '37.141', 'enterprice': '26844', 'countrevence': '0', 'unrealprofit': '38437.2209', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '27878.9', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=1


## /root/FIL/strategy/s_rsrs/log.txt ----- -----

721  20230529   040000    075959  1685318399  ...    721  0.981724  3.044001     1.0
722  20230529   080000    115959  1685332799  ...    722  1.102658  3.402473     1.0

[5 rows x 15 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '55.249', 'enterprice': '26128.2', 'countrevence': '0', 'unrealprofit': '101232.7427', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '27960.5', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'numpy.int64'>, curSign=1, self.sign=1
--handleKline--:  version='2.0.0', self.name='s_rsrs', self.symbol='BTCUSDT', interval='4h', intervalSec=14400, wid=25, thd=0.6, self.sign=1, self.total=1442113.3648782002, self.flagDict['side']='buy', self.tradeCount=3, self.count=91
self.closeSec=1685347199, self.tradeDate='20230529', self.openTime='120000', self.closeTime='155959', self.symbol='BTCUSDT', self.open=27948.0, self.close=27895.0, self.high=28040.0, self.low=27822.7, self.vol=60707.279, self.amt=1695957796.61591 
127.0.0.1 - - [29/May/2023 16:00:01] "POST / HTTP/1.1" 200 -
2023-05-29 16:00:01,896:INFO:s_rsrs:main.py:141:handleKline:2218689: self.closeSec=1685347199, self.tradeDate='20230529', self.openTime='120000', self.closeTime='155959',self.symbol='BTCUSDT',self.open=27948.0, self.close=27895.0, self.high=28040.0, self.low=27822.7, self.vol=60707.279, self.amt=1695957796.61591 
2023-05-29 16:00:01,925:INFO:s_rsrs:main.py:142:handleKline:2218689: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime  ...         vol           amt       pct
719  20230528   200000    235959  ...   37541.126  1.020329e+09  0.004351
720  20230529   000000    035959  ...  113292.894  3.113995e+09  0.009327
721  20230529   040000    075959  ...  116480.961  3.257902e+09  0.019525
722  20230529   080000    115959  ...  103587.637  2.920579e+09 -0.003842
723  20230529   120000    155959  ...   60707.279  1.695958e+09 -0.001893

[5 rows x 11 columns]
2023-05-29 16:00:03,945:INFO:s_rsrs:main.py:151:handleKline:2218689: df_s.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec  ...  index      beta    zscore  signal
719  20230528   200000    235959  1685289599  ...    719  0.490371  0.530561     NaN
720  20230529   000000    035959  1685303999  ...    720  0.747217  1.936988     1.0
721  20230529   040000    075959  1685318399  ...    721  0.981724  3.044001     1.0
722  20230529   080000    115959  1685332799  ...    722  1.102658  3.402473     1.0
723  20230529   120000    155959  1685347199  ...    723  1.148239  3.355206     1.0

[5 rows x 15 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '55.249', 'enterprice': '26128.2', 'countrevence': '0', 'unrealprofit': '97778.96851111148', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '27897.98711852', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'numpy.int64'>, curSign=1, self.sign=1


