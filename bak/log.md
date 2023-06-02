# 20230602 16:26:01

## /root/FIL/strategy/amihud/log.txt ----- -----

--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=373746.4768026, self.flagDict['side']='sell', self.tradeCount=2, self.count=5536
self.closeSec=1685693999, self.tradeDate='20230602', self.openTime='161500', self.closeTime='161959', self.symbol='BTCUSDT', self.open=27073.3, self.close=27083.4, self.high=27100.9, self.low=27073.3, self.vol=748.448, self.amt=20276049.384 
127.0.0.1 - - [02/Jun/2023 16:20:01] "POST / HTTP/1.1" 200 -
2023-06-02 16:20:06,691:INFO:amihud:main.py:172:handleKline:2219019: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5951  20230602   155500    155959  ...         0.0        0.0       0
5952  20230602   160000    160459  ...         0.0        0.0       0
5953  20230602   160500    160959  ...         0.0        0.0       0
5954  20230602   161000    161459  ...         0.0        0.0       0
5955  20230602   161500    161959  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-06-02 16:20:06,721:INFO:amihud:main.py:175:handleKline:2219019: self.closeSec=1685693999, self.tradeDate='20230602', self.openTime='161500', self.closeTime='161959',self.symbol='BTCUSDT',self.open=27073.3, self.close=27083.4, self.high=27100.9, self.low=27073.3, self.vol=748.448, self.amt=20276049.384, ukdf['pct'].iloc[-1]=0.000369 , ukdf['amount'].iloc[-1]=20276049.384, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5955, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '13.926', 'enterprice': '26864.9', 'countrevence': '0', 'unrealprofit': '-3097.65134154564', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '27087.33654614', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1
--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=373746.4768026, self.flagDict['side']='sell', self.tradeCount=2, self.count=5537
self.closeSec=1685694299, self.tradeDate='20230602', self.openTime='162000', self.closeTime='162459', self.symbol='BTCUSDT', self.open=27083.3, self.close=27081.1, self.high=27089.0, self.low=27077.4, self.vol=320.837, self.amt=8688931.2066 
127.0.0.1 - - [02/Jun/2023 16:25:00] "POST / HTTP/1.1" 200 -
2023-06-02 16:25:00,783:INFO:amihud:main.py:172:handleKline:2219019: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5952  20230602   160000    160459  ...         0.0        0.0       0
5953  20230602   160500    160959  ...         0.0        0.0       0
5954  20230602   161000    161459  ...         0.0        0.0       0
5955  20230602   161500    161959  ...         0.0        0.0       0
5956  20230602   162000    162459  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-06-02 16:25:00,783:INFO:amihud:main.py:175:handleKline:2219019: self.closeSec=1685694299, self.tradeDate='20230602', self.openTime='162000', self.closeTime='162459',self.symbol='BTCUSDT',self.open=27083.3, self.close=27081.1, self.high=27089.0, self.low=27077.4, self.vol=320.837, self.amt=8688931.2066, ukdf['pct'].iloc[-1]=-8.5e-05 , ukdf['amount'].iloc[-1]=8688931.2066, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5956, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '13.926', 'enterprice': '26864.9', 'countrevence': '0', 'unrealprofit': '-3018.46756619166', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '27081.65050741', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1


## /root/FIL/strategy/factorcheck/log.txt ----- -----


self.closeSec=1685693999, self.tradeDate='20230602', self.openTime='161500', self.closeTime='161959', self.symbol='BTCUSDT', self.open=27073.3, self.close=27083.4, self.high=27100.9, self.low=27073.3 
127.0.0.1 - - [02/Jun/2023 16:20:01] "POST / HTTP/1.1" 200 -
2023-06-02 16:20:04,321:INFO:factorcheck2:main.py:126:handleKline:2218005: self.closeSec=1685693999, self.tradeDate='20230602', self.openTime='161500', self.closeTime='161959',self.symbol='BTCUSDT',self.open=27073.3, self.close=27083.4, self.high=27100.9, self.low=27073.3   
2023-06-02 16:20:05,621:INFO:factorcheck2:main.py:127:handleKline:2218005: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime    closeSec  ...      low       pct  index  idx
1631  20230602   155500    155959  1685692799  ...  27033.0 -0.000769   1631    5
1632  20230602   160000    160459  1685693099  ...  27038.3  0.001036   1632    0
1633  20230602   160500    160959  1685693399  ...  27066.2  0.000347   1633    1
1634  20230602   161000    161459  1685693699  ...  27065.7 -0.000085   1634    2
1635  20230602   161500    161959  1685693999  ...  27073.3  0.000369   1635    3

[5 rows x 11 columns]
2023-06-02 16:20:05,631:INFO:factorcheck2:main.py:128:handleKline:2218005: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': True, 'isOpenSell': False, 'isCloseBuy': False, 'isCloseSell': False, 'isOpen': True, 'isClose': False, 'isTrig': True}

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=4, self.factor=0.5655233330952584, self.count=5539 

self.closeSec=1685694299, self.tradeDate='20230602', self.openTime='162000', self.closeTime='162459', self.symbol='BTCUSDT', self.open=27083.3, self.close=27081.1, self.high=27089.0, self.low=27077.4 
127.0.0.1 - - [02/Jun/2023 16:25:00] "POST / HTTP/1.1" 200 -
2023-06-02 16:25:00,735:INFO:factorcheck2:main.py:126:handleKline:2218005: self.closeSec=1685694299, self.tradeDate='20230602', self.openTime='162000', self.closeTime='162459',self.symbol='BTCUSDT',self.open=27083.3, self.close=27081.1, self.high=27089.0, self.low=27077.4   
2023-06-02 16:25:00,769:INFO:factorcheck2:main.py:127:handleKline:2218005: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime    closeSec  ...      low       pct  index  idx
1632  20230602   160000    160459  1685693099  ...  27038.3  0.001036   1632    0
1633  20230602   160500    160959  1685693399  ...  27066.2  0.000347   1633    1
1634  20230602   161000    161459  1685693699  ...  27065.7 -0.000085   1634    2
1635  20230602   161500    161959  1685693999  ...  27073.3  0.000369   1635    3
1636  20230602   162000    162459  1685694299  ...  27077.4 -0.000085   1636    4

[5 rows x 11 columns]
2023-06-02 16:25:00,769:INFO:factorcheck2:main.py:128:handleKline:2218005: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': True, 'isOpenSell': False, 'isCloseBuy': False, 'isCloseSell': False, 'isOpen': True, 'isClose': False, 'isTrig': True}


## /root/FIL/strategy/logic/log.txt ----- -----

2023-06-02 16:00:33,015:DEBUG:logic:main.py:463:getModel:2218526: df_s.iloc[-5:,:] :
          date closeTime     open  ...    alpha58   alpha67   alpha72
5786  20230602    132959  27051.8  ...  48.750000  0.516036  0.472286
5787  20230602    135959  27110.5  ...  48.750000  0.521966  0.446310
5788  20230602    142959  27140.2  ...  48.333333  0.520786  0.422563
5789  20230602    145959  27135.0  ...  48.333333  0.504849  0.407220
5790  20230602    152959  27061.0  ...  48.333333  0.512553  0.389448

[5 rows x 33 columns]
0.5276752767527675
acc is : 0.5276752767527675
2023-06-02 16:00:33,176:INFO:logic:main.py:468:getModel:2218526: df_pred.iloc[-5:,:] :
     pred    prob_0    prob_1  actual  ...       nav  sign  cost_        bm
537     0  0.521529  0.478471       1  ...  1.032671   1.0    0.0  1.018711
538     0  0.520716  0.479284       0  ...  1.032466   1.0    0.0  1.018509
539     0  0.509813  0.490187       0  ...  1.029654   1.0    0.0  1.015735
540     1  0.492095  0.507905       1  ...  1.031077   1.0    0.0  1.017138
541     0  0.507895  0.492105       0  ...  1.028790   1.0    0.0  1.014883

[5 rows x 10 columns]
2023-06-02 16:00:33,202:INFO:logic:main.py:478:getModel:2218526: df_panel.iloc[-5:,:] :
    pred    prob_0    prob_1  actual  ...       nav  sign  cost_        bm
45     0  0.521663  0.478337       1  ...  1.032671   1.0    0.0  1.014970
46     0  0.520774  0.479226       0  ...  1.032466   1.0    0.0  1.013642
47     0  0.509919  0.490081       0  ...  1.029654   1.0    0.0  1.012277
48     1  0.492245  0.507755       1  ...  1.031077   1.0    0.0  1.015450
49     0  0.507895  0.492105       0  ...  1.028790   1.0    0.0  1.014883

[5 rows x 10 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '27.623', 'enterprice': '26988.6', 'countrevence': '0', 'unrealprofit': '1657.38', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '27048.6', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}


## /root/FIL/strategy/modifiedmom/log.txt ----- -----

527  20230602   155000    155959  1685692799  27050.1  27038.3 -0.000577
2023-06-02 16:00:02,307:INFO:modifiedmom:main.py:146:handleKline:2218259: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': True, 'isOpenSell': False, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True}

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=2768 

self.closeSec=1685693399, self.tradeDate='20230602', self.openTime='160000', self.closeTime='160959', self.symbol='BTCUSDT', self.open='27038.3', self.close='27075.7'
127.0.0.1 - - [02/Jun/2023 16:10:01] "POST / HTTP/1.1" 200 -
2023-06-02 16:10:01,142:INFO:modifiedmom:main.py:144:handleKline:2218259: self.closeSec=1685693399, self.tradeDate='20230602', self.openTime='160000', self.closeTime='160959',self.symbol='BTCUSDT',self.open='27038.3', self.close='27075.7'
2023-06-02 16:10:01,200:INFO:modifiedmom:main.py:145:handleKline:2218259: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec     open    close       pct
524  20230602   152000    152959  1685690999  27083.1  27098.4  0.000569
525  20230602   153000    153959  1685691599  27098.4  27081.8 -0.000613
526  20230602   154000    154959  1685692199  27081.9  27053.9 -0.001030
527  20230602   155000    155959  1685692799  27050.1  27038.3 -0.000577
528  20230602   160000    160959  1685693399  27038.3  27075.7  0.001383
2023-06-02 16:10:01,200:INFO:modifiedmom:main.py:146:handleKline:2218259: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': True, 'isOpenSell': False, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True}

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=2769 

self.closeSec=1685693999, self.tradeDate='20230602', self.openTime='161000', self.closeTime='161959', self.symbol='BTCUSDT', self.open='27075.7', self.close='27083.4'
127.0.0.1 - - [02/Jun/2023 16:20:04] "POST / HTTP/1.1" 200 -
2023-06-02 16:20:06,683:INFO:modifiedmom:main.py:144:handleKline:2218259: self.closeSec=1685693999, self.tradeDate='20230602', self.openTime='161000', self.closeTime='161959',self.symbol='BTCUSDT',self.open='27075.7', self.close='27083.4'
2023-06-02 16:20:07,262:INFO:modifiedmom:main.py:145:handleKline:2218259: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec     open    close       pct
525  20230602   153000    153959  1685691599  27098.4  27081.8 -0.000613
526  20230602   154000    154959  1685692199  27081.9  27053.9 -0.001030
527  20230602   155000    155959  1685692799  27050.1  27038.3 -0.000577
528  20230602   160000    160959  1685693399  27038.3  27075.7  0.001383
529  20230602   161000    161959  1685693999  27075.7  27083.4  0.000284
2023-06-02 16:20:07,262:INFO:modifiedmom:main.py:146:handleKline:2218259: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': True, 'isOpenSell': False, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True}


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

17519  20230602   155000    155959  1685692799  27050.1  27038.3
2023-06-02 16:00:02,332:INFO:pyemd2:main.py:127:handleKline:2217508: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}
127.0.0.1 - - [02/Jun/2023 16:10:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=2771 

self.closeSec=1685693399, self.tradeDate='20230602', self.openTime='160000', self.closeTime='160959', self.symbol='BTCUSDT', self.open='27038.3', self.close='27075.7'
2023-06-02 16:10:01,165:INFO:pyemd2:main.py:125:handleKline:2217508: self.closeSec=1685693399, self.tradeDate='20230602', self.openTime='160000', self.closeTime='160959',self.symbol='BTCUSDT',self.open='27038.3', self.close='27075.7'
2023-06-02 16:10:01,199:INFO:pyemd2:main.py:126:handleKline:2217508: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
17516  20230602   152000    152959  1685690999  27083.1  27098.4
17517  20230602   153000    153959  1685691599  27098.4  27081.8
17518  20230602   154000    154959  1685692199  27081.9  27053.9
17519  20230602   155000    155959  1685692799  27050.1  27038.3
17520  20230602   160000    160959  1685693399  27038.3  27075.7
2023-06-02 16:10:01,199:INFO:pyemd2:main.py:127:handleKline:2217508: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=2772 

self.closeSec=1685693999, self.tradeDate='20230602', self.openTime='161000', self.closeTime='161959', self.symbol='BTCUSDT', self.open='27075.7', self.close='27083.4'
127.0.0.1 - - [02/Jun/2023 16:20:04] "POST / HTTP/1.1" 200 -
2023-06-02 16:20:08,304:INFO:pyemd2:main.py:125:handleKline:2217508: self.closeSec=1685693999, self.tradeDate='20230602', self.openTime='161000', self.closeTime='161959',self.symbol='BTCUSDT',self.open='27075.7', self.close='27083.4'
2023-06-02 16:20:08,456:INFO:pyemd2:main.py:126:handleKline:2217508: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
17517  20230602   153000    153959  1685691599  27098.4  27081.8
17518  20230602   154000    154959  1685692199  27081.9  27053.9
17519  20230602   155000    155959  1685692799  27050.1  27038.3
17520  20230602   160000    160959  1685693399  27038.3  27075.7
17521  20230602   161000    161959  1685693999  27075.7  27083.4
2023-06-02 16:20:08,457:INFO:pyemd2:main.py:127:handleKline:2217508: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}


## /root/FIL/strategy/similarity/log.txt ----- -----

12191  20230602   155000    155959  1685692799  27050.1  27038.3
2023-06-02 16:00:02,324:INFO:testStrategy:main.py:103:handleKline:2217133: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': True, 'isOpenSell': False, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True, 'isCorr': False}
127.0.0.1 - - [02/Jun/2023 16:10:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=2771 

self.closeSec=1685693399, self.tradeDate='20230602', self.openTime='160000', self.closeTime='160959', self.symbol='BTCUSDT', self.open='27038.3', self.close='27075.7'
2023-06-02 16:10:01,159:INFO:testStrategy:main.py:101:handleKline:2217133: self.closeSec=1685693399, self.tradeDate='20230602', self.openTime='160000', self.closeTime='160959',self.symbol='BTCUSDT',self.open='27038.3', self.close='27075.7'
2023-06-02 16:10:01,205:INFO:testStrategy:main.py:102:handleKline:2217133: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
12188  20230602   152000    152959  1685690999  27083.1  27098.4
12189  20230602   153000    153959  1685691599  27098.4  27081.8
12190  20230602   154000    154959  1685692199  27081.9  27053.9
12191  20230602   155000    155959  1685692799  27050.1  27038.3
12192  20230602   160000    160959  1685693399  27038.3  27075.7
2023-06-02 16:10:01,205:INFO:testStrategy:main.py:103:handleKline:2217133: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': True, 'isOpenSell': False, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True, 'isCorr': False}

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=2772 

self.closeSec=1685693999, self.tradeDate='20230602', self.openTime='161000', self.closeTime='161959', self.symbol='BTCUSDT', self.open='27075.7', self.close='27083.4'
127.0.0.1 - - [02/Jun/2023 16:20:04] "POST / HTTP/1.1" 200 -
2023-06-02 16:20:08,073:INFO:testStrategy:main.py:101:handleKline:2217133: self.closeSec=1685693999, self.tradeDate='20230602', self.openTime='161000', self.closeTime='161959',self.symbol='BTCUSDT',self.open='27075.7', self.close='27083.4'
2023-06-02 16:20:08,301:INFO:testStrategy:main.py:102:handleKline:2217133: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
12189  20230602   153000    153959  1685691599  27098.4  27081.8
12190  20230602   154000    154959  1685692199  27081.9  27053.9
12191  20230602   155000    155959  1685692799  27050.1  27038.3
12192  20230602   160000    160959  1685693399  27038.3  27075.7
12193  20230602   161000    161959  1685693999  27075.7  27083.4
2023-06-02 16:20:08,301:INFO:testStrategy:main.py:103:handleKline:2217133: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': True, 'isOpenSell': False, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True, 'isCorr': False}


## /root/FIL/strategy/sr_min/log.txt ----- -----

--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=1, self.total=996015.990996, self.flagDict['side']='buy', self.tradeCount=1, self.count=5536
self.closeSec=1685693999, self.tradeDate='20230602', self.openTime='161500', self.closeTime='161959', self.symbol='BTCUSDT', self.open=27073.3, self.close=27083.4, self.high=27100.9, self.low=27073.3, self.vol=748.448, self.amt=20276049.384 
127.0.0.1 - - [02/Jun/2023 16:20:01] "POST / HTTP/1.1" 200 -
2023-06-02 16:20:06,684:INFO:sr_min:main.py:172:handleKline:2219263: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5951  20230602   155500    155959  ...         0.0        0.0       0
5952  20230602   160000    160459  ...         0.0        0.0       0
5953  20230602   160500    160959  ...         0.0        0.0       0
5954  20230602   161000    161459  ...         0.0        0.0       0
5955  20230602   161500    161959  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-06-02 16:20:06,712:INFO:sr_min:main.py:175:handleKline:2219263: self.closeSec=1685693999, self.tradeDate='20230602', self.openTime='161500', self.closeTime='161959',self.symbol='BTCUSDT',self.open=27073.3, self.close=27083.4, self.high=27100.9, self.low=27073.3, self.vol=748.448, self.amt=20276049.384, ukdf['pct'].iloc[-1]=0.000369 , ukdf['amount'].iloc[-1]=20276049.384, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5955, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '37.141', 'enterprice': '26844', 'countrevence': '0', 'unrealprofit': '9037.76266018574', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '27087.33654614', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=1
127.0.0.1 - - [02/Jun/2023 16:25:00] "POST / HTTP/1.1" 200 -
--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=1, self.total=996015.990996, self.flagDict['side']='buy', self.tradeCount=1, self.count=5537
self.closeSec=1685694299, self.tradeDate='20230602', self.openTime='162000', self.closeTime='162459', self.symbol='BTCUSDT', self.open=27083.3, self.close=27081.1, self.high=27089.0, self.low=27077.4, self.vol=320.837, self.amt=8688931.2066 
2023-06-02 16:25:00,786:INFO:sr_min:main.py:172:handleKline:2219263: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5952  20230602   160000    160459  ...         0.0        0.0       0
5953  20230602   160500    160959  ...         0.0        0.0       0
5954  20230602   161000    161459  ...         0.0        0.0       0
5955  20230602   161500    161959  ...         0.0        0.0       0
5956  20230602   162000    162459  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-06-02 16:25:00,786:INFO:sr_min:main.py:175:handleKline:2219263: self.closeSec=1685694299, self.tradeDate='20230602', self.openTime='162000', self.closeTime='162459',self.symbol='BTCUSDT',self.open=27083.3, self.close=27081.1, self.high=27089.0, self.low=27077.4, self.vol=320.837, self.amt=8688931.2066, ukdf['pct'].iloc[-1]=-8.5e-05 , ukdf['amount'].iloc[-1]=8688931.2066, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5956, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '37.141', 'enterprice': '26844', 'countrevence': '0', 'unrealprofit': '8826.57749571481', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '27081.65050741', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=1


## /root/FIL/strategy/s_rsrs/log.txt ----- -----

721  20230602   040000    075959  1685663999  ...    721  0.777972  0.742572     1.0
722  20230602   080000    115959  1685678399  ...    722  0.727542  0.583283     NaN

[5 rows x 15 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '55.249', 'enterprice': '26128.2', 'countrevence': '0', 'unrealprofit': '48007.94389838361', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '26997.13778889', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'numpy.int64'>, curSign=-9223372036854775808, self.sign=1
127.0.0.1 - - [02/Jun/2023 16:00:01] "POST / HTTP/1.1" 200 -
--handleKline--:  version='2.0.0', self.name='s_rsrs', self.symbol='BTCUSDT', interval='4h', intervalSec=14400, wid=25, thd=0.6, self.sign=1, self.total=1442113.3648782002, self.flagDict['side']='buy', self.tradeCount=3, self.count=115
self.closeSec=1685692799, self.tradeDate='20230602', self.openTime='120000', self.closeTime='155959', self.symbol='BTCUSDT', self.open=26985.2, self.close=27038.3, self.high=27200.0, self.low=26937.3, self.vol=61632.613, self.amt=1669195193.12515 
2023-06-02 16:00:01,863:INFO:s_rsrs:main.py:141:handleKline:2218689: self.closeSec=1685692799, self.tradeDate='20230602', self.openTime='120000', self.closeTime='155959',self.symbol='BTCUSDT',self.open=26985.2, self.close=27038.3, self.high=27200.0, self.low=26937.3, self.vol=61632.613, self.amt=1669195193.12515 
2023-06-02 16:00:01,886:INFO:s_rsrs:main.py:142:handleKline:2218689: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime  ...         vol           amt       pct
719  20230601   200000    235959  ...   59027.609  1.586971e+09  0.000093
720  20230602   000000    035959  ...  111799.742  3.010613e+09 -0.001213
721  20230602   040000    075959  ...   37327.512  1.001886e+09 -0.001724
722  20230602   080000    115959  ...   85456.975  2.287551e+09  0.006708
723  20230602   120000    155959  ...   61632.613  1.669195e+09  0.001971

[5 rows x 11 columns]
2023-06-02 16:00:03,958:INFO:s_rsrs:main.py:151:handleKline:2218689: df_s.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec  ...  index      beta    zscore  signal
719  20230601   200000    235959  1685635199  ...    719  0.774015  0.749031     1.0
720  20230602   000000    035959  1685649599  ...    720  0.722386  0.586507     NaN
721  20230602   040000    075959  1685663999  ...    721  0.777972  0.742572     1.0
722  20230602   080000    115959  1685678399  ...    722  0.727542  0.583283     NaN
723  20230602   120000    155959  1685692799  ...    723  0.670010  0.405017     NaN

[5 rows x 15 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '55.249', 'enterprice': '26128.2', 'countrevence': '0', 'unrealprofit': '50393.86643848361', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '27040.32268889', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'numpy.int64'>, curSign=-9223372036854775808, self.sign=1


