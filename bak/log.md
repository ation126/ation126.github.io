# 20230714 16:26:01

## /root/FIL/strategy/amihud/log.txt ----- -----

--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=373746.4768026, self.flagDict['side']='sell', self.tradeCount=2, self.count=17632
self.closeSec=1689322799, self.tradeDate='20230714', self.openTime='161500', self.closeTime='161959', self.symbol='BTCUSDT', self.open=31220.4, self.close=31201.9, self.high=31225.0, self.low=31194.7, self.vol=1317.879, self.amt=41133927.6009 
127.0.0.1 - - [14/Jul/2023 16:20:01] "POST / HTTP/1.1" 200 -
2023-07-14 16:20:06,011:INFO:amihud:main.py:172:handleKline:2219019: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5951  20230714   155500    155959  ...         0.0        0.0       0
5952  20230714   160000    160459  ...         0.0        0.0       0
5953  20230714   160500    160959  ...         0.0        0.0       0
5954  20230714   161000    161459  ...         0.0        0.0       0
5955  20230714   161500    161959  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-07-14 16:20:06,050:INFO:amihud:main.py:175:handleKline:2219019: self.closeSec=1689322799, self.tradeDate='20230714', self.openTime='161500', self.closeTime='161959',self.symbol='BTCUSDT',self.open=31220.4, self.close=31201.9, self.high=31225.0, self.low=31194.7, self.vol=1317.879, self.amt=41133927.6009, ukdf['pct'].iloc[-1]=-0.000593 , ukdf['amount'].iloc[-1]=41133927.6009, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5955, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '13.926', 'enterprice': '26864.9', 'countrevence': '0', 'unrealprofit': '-60433.2696', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '31204.5', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1
127.0.0.1 - - [14/Jul/2023 16:25:00] "POST / HTTP/1.1" 200 -
--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=373746.4768026, self.flagDict['side']='sell', self.tradeCount=2, self.count=17633
self.closeSec=1689323099, self.tradeDate='20230714', self.openTime='162000', self.closeTime='162459', self.symbol='BTCUSDT', self.open=31201.9, self.close=31234.8, self.high=31237.5, self.low=31190.5, self.vol=1014.199, self.amt=31659147.0162 
2023-07-14 16:25:00,800:INFO:amihud:main.py:172:handleKline:2219019: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5952  20230714   160000    160459  ...         0.0        0.0       0
5953  20230714   160500    160959  ...         0.0        0.0       0
5954  20230714   161000    161459  ...         0.0        0.0       0
5955  20230714   161500    161959  ...         0.0        0.0       0
5956  20230714   162000    162459  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-07-14 16:25:00,801:INFO:amihud:main.py:175:handleKline:2219019: self.closeSec=1689323099, self.tradeDate='20230714', self.openTime='162000', self.closeTime='162459',self.symbol='BTCUSDT',self.open=31201.9, self.close=31234.8, self.high=31237.5, self.low=31190.5, self.vol=1014.199, self.amt=31659147.0162, ukdf['pct'].iloc[-1]=0.001054 , ukdf['amount'].iloc[-1]=31659147.0162, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5956, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '13.926', 'enterprice': '26864.9', 'countrevence': '0', 'unrealprofit': '-60878.9016', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '31236.5', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1


## /root/FIL/strategy/factorcheck/log.txt ----- -----


self.closeSec=1689322799, self.tradeDate='20230714', self.openTime='161500', self.closeTime='161959', self.symbol='BTCUSDT', self.open=31220.4, self.close=31201.9, self.high=31225.0, self.low=31194.7 
127.0.0.1 - - [14/Jul/2023 16:20:01] "POST / HTTP/1.1" 200 -
2023-07-14 16:20:03,730:INFO:factorcheck2:main.py:126:handleKline:2218005: self.closeSec=1689322799, self.tradeDate='20230714', self.openTime='161500', self.closeTime='161959',self.symbol='BTCUSDT',self.open=31220.4, self.close=31201.9, self.high=31225.0, self.low=31194.7   
2023-07-14 16:20:05,140:INFO:factorcheck2:main.py:127:handleKline:2218005: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime    closeSec  ...      low       pct  index  idx
1631  20230714   155500    155959  1689321599  ...  31068.5 -0.000986   1631    5
1632  20230714   160000    160459  1689321899  ...  31076.5  0.001782   1632    0
1633  20230714   160500    160959  1689322199  ...  31139.3  0.001188   1633    1
1634  20230714   161000    161459  1689322499  ...  31185.8  0.001029   1634    2
1635  20230714   161500    161959  1689322799  ...  31194.7 -0.000593   1635    3

[5 rows x 11 columns]
2023-07-14 16:20:05,150:INFO:factorcheck2:main.py:128:handleKline:2218005: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': True, 'isOpenSell': False, 'isCloseBuy': False, 'isCloseSell': False, 'isOpen': True, 'isClose': False, 'isTrig': True}
127.0.0.1 - - [14/Jul/2023 16:25:00] "POST / HTTP/1.1" 200 -

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=40, self.factor=0.3881061693557334, self.count=17635 

self.closeSec=1689323099, self.tradeDate='20230714', self.openTime='162000', self.closeTime='162459', self.symbol='BTCUSDT', self.open=31201.9, self.close=31234.8, self.high=31237.5, self.low=31190.5 
2023-07-14 16:25:00,746:INFO:factorcheck2:main.py:126:handleKline:2218005: self.closeSec=1689323099, self.tradeDate='20230714', self.openTime='162000', self.closeTime='162459',self.symbol='BTCUSDT',self.open=31201.9, self.close=31234.8, self.high=31237.5, self.low=31190.5   
2023-07-14 16:25:00,788:INFO:factorcheck2:main.py:127:handleKline:2218005: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime    closeSec  ...      low       pct  index  idx
1632  20230714   160000    160459  1689321899  ...  31076.5  0.001782   1632    0
1633  20230714   160500    160959  1689322199  ...  31139.3  0.001188   1633    1
1634  20230714   161000    161459  1689322499  ...  31185.8  0.001029   1634    2
1635  20230714   161500    161959  1689322799  ...  31194.7 -0.000593   1635    3
1636  20230714   162000    162459  1689323099  ...  31190.5  0.001054   1636    4

[5 rows x 11 columns]
2023-07-14 16:25:00,788:INFO:factorcheck2:main.py:128:handleKline:2218005: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': True, 'isOpenSell': False, 'isCloseBuy': False, 'isCloseSell': False, 'isOpen': True, 'isClose': False, 'isTrig': True}


## /root/FIL/strategy/logic/log.txt ----- -----

2023-07-14 16:00:20,799:DEBUG:logic:main.py:463:getModel:2218526: df_s.iloc[-5:,:] :
          date closeTime     open  ...    alpha58   alpha67   alpha72
5786  20230714    132959  31378.3  ...  53.750000  0.592310  0.309777
5787  20230714    135959  31366.4  ...  53.750000  0.589771  0.312674
5788  20230714    142959  31354.2  ...  53.750000  0.584387  0.316599
5789  20230714    145959  31328.5  ...  53.333333  0.575378  0.322314
5790  20230714    152959  31285.6  ...  52.916667  0.568811  0.329153

[5 rows x 33 columns]
0.5424354243542435
acc is : 0.5424354243542435
2023-07-14 16:00:20,895:INFO:logic:main.py:468:getModel:2218526: df_pred.iloc[-5:,:] :
     pred    prob_0    prob_1  actual  ...       nav  sign  cost_        bm
537     1  0.488556  0.511444       0  ...  0.965458   1.0    0.0  1.023620
538     1  0.481758  0.518242       0  ...  0.964666   1.0    0.0  1.022781
539     1  0.488102  0.511898       0  ...  0.963336   1.0    0.0  1.021371
540     1  0.482248  0.517752       0  ...  0.962360   1.0    0.0  1.020336
541     1  0.488918  0.511082       0  ...  0.957504   1.0    0.0  1.015187

[5 rows x 10 columns]
2023-07-14 16:00:20,909:INFO:logic:main.py:478:getModel:2218526: df_panel.iloc[-5:,:] :
    pred    prob_0    prob_1  actual  ...       nav  sign  cost_        bm
45     1  0.488577  0.511423       0  ...  0.965458   1.0    0.0  1.023082
46     1  0.482288  0.517712       0  ...  0.986852   1.0    0.0  1.023995
47     1  0.487227  0.512773       0  ...  0.970708  -1.0    0.0  1.021971
48     1  0.481760  0.518240       0  ...  0.958588   1.0    0.0  1.019460
49     1  0.488918  0.511082       0  ...  0.957504   1.0    0.0  1.015187

[5 rows x 10 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '23.999', 'enterprice': '31244.1', 'countrevence': '0', 'unrealprofit': '-3566.2514', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '31095.5', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}


## /root/FIL/strategy/modifiedmom/log.txt ----- -----

527  20230714   155000    155959  1689321599    31175    31096 -0.002537
2023-07-14 16:00:02,151:INFO:modifiedmom:main.py:146:handleKline:2218259: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': True, 'isOpenSell': False, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True}

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=8816 

self.closeSec=1689322199, self.tradeDate='20230714', self.openTime='160000', self.closeTime='160959', self.symbol='BTCUSDT', self.open='31095.9', self.close='31188.3'
2023-07-14 16:10:01,074:INFO:modifiedmom:main.py:144:handleKline:2218259: self.closeSec=1689322199, self.tradeDate='20230714', self.openTime='160000', self.closeTime='160959',self.symbol='BTCUSDT',self.open='31095.9', self.close='31188.3'
127.0.0.1 - - [14/Jul/2023 16:10:01] "POST / HTTP/1.1" 200 -
2023-07-14 16:10:01,099:INFO:modifiedmom:main.py:145:handleKline:2218259: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec     open    close       pct
524  20230714   152000    152959  1689319799    31240  31253.6  0.000432
525  20230714   153000    153959  1689320399  31253.5    31175 -0.002515
526  20230714   154000    154959  1689320999    31175  31175.1  0.000003
527  20230714   155000    155959  1689321599    31175    31096 -0.002537
528  20230714   160000    160959  1689322199  31095.9  31188.3  0.002968
2023-07-14 16:10:01,100:INFO:modifiedmom:main.py:146:handleKline:2218259: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': True, 'isOpenSell': False, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True}

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=8817 

self.closeSec=1689322799, self.tradeDate='20230714', self.openTime='161000', self.closeTime='161959', self.symbol='BTCUSDT', self.open='31188.3', self.close='31201.9'
127.0.0.1 - - [14/Jul/2023 16:20:04] "POST / HTTP/1.1" 200 -
2023-07-14 16:20:06,190:INFO:modifiedmom:main.py:144:handleKline:2218259: self.closeSec=1689322799, self.tradeDate='20230714', self.openTime='161000', self.closeTime='161959',self.symbol='BTCUSDT',self.open='31188.3', self.close='31201.9'
2023-07-14 16:20:06,841:INFO:modifiedmom:main.py:145:handleKline:2218259: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec     open    close       pct
525  20230714   153000    153959  1689320399  31253.5    31175 -0.002515
526  20230714   154000    154959  1689320999    31175  31175.1  0.000003
527  20230714   155000    155959  1689321599    31175    31096 -0.002537
528  20230714   160000    160959  1689322199  31095.9  31188.3  0.002968
529  20230714   161000    161959  1689322799  31188.3  31201.9  0.000436
2023-07-14 16:20:06,841:INFO:modifiedmom:main.py:146:handleKline:2218259: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': True, 'isOpenSell': False, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True}


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

17519  20230714   155000    155959  1689321599    31175    31096
2023-07-14 16:00:02,160:INFO:pyemd2:main.py:127:handleKline:2217508: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=8819 

self.closeSec=1689322199, self.tradeDate='20230714', self.openTime='160000', self.closeTime='160959', self.symbol='BTCUSDT', self.open='31095.9', self.close='31188.3'
2023-07-14 16:10:01,084:INFO:pyemd2:main.py:125:handleKline:2217508: self.closeSec=1689322199, self.tradeDate='20230714', self.openTime='160000', self.closeTime='160959',self.symbol='BTCUSDT',self.open='31095.9', self.close='31188.3'
127.0.0.1 - - [14/Jul/2023 16:10:01] "POST / HTTP/1.1" 200 -
2023-07-14 16:10:01,106:INFO:pyemd2:main.py:126:handleKline:2217508: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
17516  20230714   152000    152959  1689319799    31240  31253.6
17517  20230714   153000    153959  1689320399  31253.5    31175
17518  20230714   154000    154959  1689320999    31175  31175.1
17519  20230714   155000    155959  1689321599    31175    31096
17520  20230714   160000    160959  1689322199  31095.9  31188.3
2023-07-14 16:10:01,106:INFO:pyemd2:main.py:127:handleKline:2217508: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=8820 

self.closeSec=1689322799, self.tradeDate='20230714', self.openTime='161000', self.closeTime='161959', self.symbol='BTCUSDT', self.open='31188.3', self.close='31201.9'
127.0.0.1 - - [14/Jul/2023 16:20:04] "POST / HTTP/1.1" 200 -
2023-07-14 16:20:07,680:INFO:pyemd2:main.py:125:handleKline:2217508: self.closeSec=1689322799, self.tradeDate='20230714', self.openTime='161000', self.closeTime='161959',self.symbol='BTCUSDT',self.open='31188.3', self.close='31201.9'
2023-07-14 16:20:07,849:INFO:pyemd2:main.py:126:handleKline:2217508: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
17517  20230714   153000    153959  1689320399  31253.5    31175
17518  20230714   154000    154959  1689320999    31175  31175.1
17519  20230714   155000    155959  1689321599    31175    31096
17520  20230714   160000    160959  1689322199  31095.9  31188.3
17521  20230714   161000    161959  1689322799  31188.3  31201.9
2023-07-14 16:20:07,849:INFO:pyemd2:main.py:127:handleKline:2217508: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}


## /root/FIL/strategy/similarity/log.txt ----- -----

12191  20230714   155000    155959  1689321599    31175    31096
2023-07-14 16:00:02,156:INFO:testStrategy:main.py:103:handleKline:2217133: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': True, 'isOpenSell': False, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True, 'isCorr': False}

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=8819 

self.closeSec=1689322199, self.tradeDate='20230714', self.openTime='160000', self.closeTime='160959', self.symbol='BTCUSDT', self.open='31095.9', self.close='31188.3'
2023-07-14 16:10:01,065:INFO:testStrategy:main.py:101:handleKline:2217133: self.closeSec=1689322199, self.tradeDate='20230714', self.openTime='160000', self.closeTime='160959',self.symbol='BTCUSDT',self.open='31095.9', self.close='31188.3'
127.0.0.1 - - [14/Jul/2023 16:10:01] "POST / HTTP/1.1" 200 -
2023-07-14 16:10:01,104:INFO:testStrategy:main.py:102:handleKline:2217133: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
12188  20230714   152000    152959  1689319799    31240  31253.6
12189  20230714   153000    153959  1689320399  31253.5    31175
12190  20230714   154000    154959  1689320999    31175  31175.1
12191  20230714   155000    155959  1689321599    31175    31096
12192  20230714   160000    160959  1689322199  31095.9  31188.3
2023-07-14 16:10:01,104:INFO:testStrategy:main.py:103:handleKline:2217133: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': True, 'isOpenSell': False, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True, 'isCorr': False}

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=8820 

self.closeSec=1689322799, self.tradeDate='20230714', self.openTime='161000', self.closeTime='161959', self.symbol='BTCUSDT', self.open='31188.3', self.close='31201.9'
127.0.0.1 - - [14/Jul/2023 16:20:04] "POST / HTTP/1.1" 200 -
2023-07-14 16:20:07,487:INFO:testStrategy:main.py:101:handleKline:2217133: self.closeSec=1689322799, self.tradeDate='20230714', self.openTime='161000', self.closeTime='161959',self.symbol='BTCUSDT',self.open='31188.3', self.close='31201.9'
2023-07-14 16:20:07,734:INFO:testStrategy:main.py:102:handleKline:2217133: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
12189  20230714   153000    153959  1689320399  31253.5    31175
12190  20230714   154000    154959  1689320999    31175  31175.1
12191  20230714   155000    155959  1689321599    31175    31096
12192  20230714   160000    160959  1689322199  31095.9  31188.3
12193  20230714   161000    161959  1689322799  31188.3  31201.9
2023-07-14 16:20:07,739:INFO:testStrategy:main.py:103:handleKline:2217133: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': True, 'isOpenSell': False, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True, 'isCorr': False}


## /root/FIL/strategy/sr_min/log.txt ----- -----

--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=1, self.total=996015.990996, self.flagDict['side']='buy', self.tradeCount=1, self.count=17632
self.closeSec=1689322799, self.tradeDate='20230714', self.openTime='161500', self.closeTime='161959', self.symbol='BTCUSDT', self.open=31220.4, self.close=31201.9, self.high=31225.0, self.low=31194.7, self.vol=1317.879, self.amt=41133927.6009 
127.0.0.1 - - [14/Jul/2023 16:20:01] "POST / HTTP/1.1" 200 -
2023-07-14 16:20:06,020:INFO:sr_min:main.py:172:handleKline:2219263: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5951  20230714   155500    155959  ...         0.0        0.0       0
5952  20230714   160000    160459  ...         0.0        0.0       0
5953  20230714   160500    160959  ...         0.0        0.0       0
5954  20230714   161000    161459  ...         0.0        0.0       0
5955  20230714   161500    161959  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-07-14 16:20:06,050:INFO:sr_min:main.py:175:handleKline:2219263: self.closeSec=1689322799, self.tradeDate='20230714', self.openTime='161500', self.closeTime='161959',self.symbol='BTCUSDT',self.open=31220.4, self.close=31201.9, self.high=31225.0, self.low=31194.7, self.vol=1317.879, self.amt=41133927.6009, ukdf['pct'].iloc[-1]=-0.000593 , ukdf['amount'].iloc[-1]=41133927.6009, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5955, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '37.141', 'enterprice': '26844', 'countrevence': '0', 'unrealprofit': '161953.3305', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '31204.5', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=1
--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=1, self.total=996015.990996, self.flagDict['side']='buy', self.tradeCount=1, self.count=17633
self.closeSec=1689323099, self.tradeDate='20230714', self.openTime='162000', self.closeTime='162459', self.symbol='BTCUSDT', self.open=31201.9, self.close=31234.8, self.high=31237.5, self.low=31190.5, self.vol=1014.199, self.amt=31659147.0162 
127.0.0.1 - - [14/Jul/2023 16:25:00] "POST / HTTP/1.1" 200 -
2023-07-14 16:25:00,762:INFO:sr_min:main.py:172:handleKline:2219263: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5952  20230714   160000    160459  ...         0.0        0.0       0
5953  20230714   160500    160959  ...         0.0        0.0       0
5954  20230714   161000    161459  ...         0.0        0.0       0
5955  20230714   161500    161959  ...         0.0        0.0       0
5956  20230714   162000    162459  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-07-14 16:25:00,762:INFO:sr_min:main.py:175:handleKline:2219263: self.closeSec=1689323099, self.tradeDate='20230714', self.openTime='162000', self.closeTime='162459',self.symbol='BTCUSDT',self.open=31201.9, self.close=31234.8, self.high=31237.5, self.low=31190.5, self.vol=1014.199, self.amt=31659147.0162, ukdf['pct'].iloc[-1]=0.001054 , ukdf['amount'].iloc[-1]=31659147.0162, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5956, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '37.141', 'enterprice': '26844', 'countrevence': '0', 'unrealprofit': '163141.8425', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '31236.5', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=1


## /root/FIL/strategy/s_rsrs/log.txt ----- -----

721  20230714   040000    075959  1689292799  ...    721  1.170617  3.472242     1.0
722  20230714   080000    115959  1689307199  ...    722  0.915208  2.355026     1.0

[5 rows x 15 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '52.241', 'enterprice': '30511.1', 'countrevence': '0', 'unrealprofit': '48886.56922303329', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '31446.88930769', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'numpy.int64'>, curSign=1, self.sign=1
--handleKline--:  version='2.0.0', self.name='s_rsrs', self.symbol='BTCUSDT', interval='4h', intervalSec=14400, wid=25, thd=0.6, self.sign=1, self.total=1592336.4447248997, self.flagDict['side']='buy', self.tradeCount=11, self.count=367
self.closeSec=1689321599, self.tradeDate='20230714', self.openTime='120000', self.closeTime='155959', self.symbol='BTCUSDT', self.open=31445.4, self.close=31096.0, self.high=31457.7, self.low=31068.5, self.vol=47214.511, self.amt=1477015190.46663 127.0.0.1 - - [14/Jul/2023 16:00:01] "POST / HTTP/1.1" 200 -

2023-07-14 16:00:01,706:INFO:s_rsrs:main.py:141:handleKline:2218689: self.closeSec=1689321599, self.tradeDate='20230714', self.openTime='120000', self.closeTime='155959',self.symbol='BTCUSDT',self.open=31445.4, self.close=31096.0, self.high=31457.7, self.low=31068.5, self.vol=47214.511, self.amt=1477015190.46663 
2023-07-14 16:00:01,729:INFO:s_rsrs:main.py:142:handleKline:2218689: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime  ...         vol           amt       pct
719  20230713   200000    235959  ...  176453.536  5.430610e+09  0.012604
720  20230714   000000    035959  ...  291866.546  9.114633e+09  0.022164
721  20230714   040000    075959  ...  113138.840  3.544202e+09 -0.005028
722  20230714   080000    115959  ...   60468.943  1.901094e+09  0.000118
723  20230714   120000    155959  ...   47214.511  1.477015e+09 -0.011111

[5 rows x 11 columns]
2023-07-14 16:00:03,120:INFO:s_rsrs:main.py:151:handleKline:2218689: df_s.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec  ...  index      beta    zscore  signal
719  20230713   200000    235959  1689263999  ...    719  0.416175  0.597722     NaN
720  20230714   000000    035959  1689278399  ...    720  0.909357  2.656956     1.0
721  20230714   040000    075959  1689292799  ...    721  1.170617  3.472242     1.0
722  20230714   080000    115959  1689307199  ...    722  0.915208  2.355026     1.0
723  20230714   120000    155959  1689321599  ...    723  0.884779  2.157640     1.0

[5 rows x 15 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '52.241', 'enterprice': '30511.1', 'countrevence': '0', 'unrealprofit': '30579.10150541351', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '31096.44678711', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'numpy.int64'>, curSign=1, self.sign=1


