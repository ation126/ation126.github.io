# 20230720 16:26:01

## /root/FIL/strategy/amihud/log.txt ----- -----

--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=373746.4768026, self.flagDict['side']='sell', self.tradeCount=2, self.count=19360
self.closeSec=1689841199, self.tradeDate='20230720', self.openTime='161500', self.closeTime='161959', self.symbol='BTCUSDT', self.open=30186.7, self.close=30157.9, self.high=30189.6, self.low=30151.6, self.vol=747.362, self.amt=22546184.9641 
127.0.0.1 - - [20/Jul/2023 16:20:01] "POST / HTTP/1.1" 200 -
2023-07-20 16:20:05,340:INFO:amihud:main.py:172:handleKline:2219019: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5951  20230720   155500    155959  ...         0.0        0.0       0
5952  20230720   160000    160459  ...         0.0        0.0       0
5953  20230720   160500    160959  ...         0.0        0.0       0
5954  20230720   161000    161459  ...         0.0        0.0       0
5955  20230720   161500    161959  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-07-20 16:20:05,360:INFO:amihud:main.py:175:handleKline:2219019: self.closeSec=1689841199, self.tradeDate='20230720', self.openTime='161500', self.closeTime='161959',self.symbol='BTCUSDT',self.open=30186.7, self.close=30157.9, self.high=30189.6, self.low=30151.6, self.vol=747.362, self.amt=22546184.9641, ukdf['pct'].iloc[-1]=-0.000954 , ukdf['amount'].iloc[-1]=22546184.9641, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5955, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '13.926', 'enterprice': '26864.9', 'countrevence': '0', 'unrealprofit': '-46010.1114', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '30168.8', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1
--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=373746.4768026, self.flagDict['side']='sell', self.tradeCount=2, self.count=19361
self.closeSec=1689841499, self.tradeDate='20230720', self.openTime='162000', self.closeTime='162459', self.symbol='BTCUSDT', self.open=30158.0, self.close=30181.6, self.high=30183.5, self.low=30157.9, self.vol=516.58, self.amt=15586803.0978 
127.0.0.1 - - [20/Jul/2023 16:25:00] "POST / HTTP/1.1" 200 -
2023-07-20 16:25:00,804:INFO:amihud:main.py:172:handleKline:2219019: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5952  20230720   160000    160459  ...         0.0        0.0       0
5953  20230720   160500    160959  ...         0.0        0.0       0
5954  20230720   161000    161459  ...         0.0        0.0       0
5955  20230720   161500    161959  ...         0.0        0.0       0
5956  20230720   162000    162459  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-07-20 16:25:00,805:INFO:amihud:main.py:175:handleKline:2219019: self.closeSec=1689841499, self.tradeDate='20230720', self.openTime='162000', self.closeTime='162459',self.symbol='BTCUSDT',self.open=30158.0, self.close=30181.6, self.high=30183.5, self.low=30157.9, self.vol=516.58, self.amt=15586803.0978, ukdf['pct'].iloc[-1]=0.000786 , ukdf['amount'].iloc[-1]=15586803.0978, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5956, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '13.926', 'enterprice': '26864.9', 'countrevence': '0', 'unrealprofit': '-46186.9716', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '30181.5', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1


## /root/FIL/strategy/factorcheck/log.txt ----- -----


self.closeSec=1689841199, self.tradeDate='20230720', self.openTime='161500', self.closeTime='161959', self.symbol='BTCUSDT', self.open=30186.7, self.close=30157.9, self.high=30189.6, self.low=30151.6 
127.0.0.1 - - [20/Jul/2023 16:20:01] "POST / HTTP/1.1" 200 -
2023-07-20 16:20:03,369:INFO:factorcheck2:main.py:126:handleKline:2218005: self.closeSec=1689841199, self.tradeDate='20230720', self.openTime='161500', self.closeTime='161959',self.symbol='BTCUSDT',self.open=30186.7, self.close=30157.9, self.high=30189.6, self.low=30151.6   
2023-07-20 16:20:04,529:INFO:factorcheck2:main.py:127:handleKline:2218005: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime    closeSec  ...      low       pct  index  idx
1631  20230720   155500    155959  1689839999  ...  30181.5 -0.000238   1631    5
1632  20230720   160000    160459  1689840299  ...  30195.5  0.000417   1632    0
1633  20230720   160500    160959  1689840599  ...  30162.0 -0.001324   1633    1
1634  20230720   161000    161459  1689840899  ...  30162.3  0.000617   1634    2
1635  20230720   161500    161959  1689841199  ...  30151.6 -0.000954   1635    3

[5 rows x 11 columns]
2023-07-20 16:20:04,539:INFO:factorcheck2:main.py:128:handleKline:2218005: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=12, self.factor=0.4377538923390503, self.count=19363 

self.closeSec=1689841499, self.tradeDate='20230720', self.openTime='162000', self.closeTime='162459', self.symbol='BTCUSDT', self.open=30158.0, self.close=30181.6, self.high=30183.5, self.low=30157.9 
127.0.0.1 - - [20/Jul/2023 16:25:00] "POST / HTTP/1.1" 200 -
2023-07-20 16:25:00,767:INFO:factorcheck2:main.py:126:handleKline:2218005: self.closeSec=1689841499, self.tradeDate='20230720', self.openTime='162000', self.closeTime='162459',self.symbol='BTCUSDT',self.open=30158.0, self.close=30181.6, self.high=30183.5, self.low=30157.9   
2023-07-20 16:25:00,799:INFO:factorcheck2:main.py:127:handleKline:2218005: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime    closeSec  ...      low       pct  index  idx
1632  20230720   160000    160459  1689840299  ...  30195.5  0.000417   1632    0
1633  20230720   160500    160959  1689840599  ...  30162.0 -0.001324   1633    1
1634  20230720   161000    161459  1689840899  ...  30162.3  0.000617   1634    2
1635  20230720   161500    161959  1689841199  ...  30151.6 -0.000954   1635    3
1636  20230720   162000    162459  1689841499  ...  30157.9  0.000786   1636    4

[5 rows x 11 columns]
2023-07-20 16:25:00,799:INFO:factorcheck2:main.py:128:handleKline:2218005: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}


## /root/FIL/strategy/logic/log.txt ----- -----

2023-07-20 16:00:17,048:DEBUG:logic:main.py:463:getModel:2218526: df_s.iloc[-5:,:] :
          date closeTime     open  ...    alpha58   alpha67   alpha72
5786  20230720    132959  29948.4  ...  50.416667  0.511344  0.464867
5787  20230720    135959  30023.8  ...  50.416667  0.532708  0.443586
5788  20230720    142959  30112.2  ...  50.416667  0.548784  0.415386
5789  20230720    145959  30182.8  ...  50.000000  0.529612  0.399923
5790  20230720    152959  30109.9  ...  50.000000  0.548366  0.379373

[5 rows x 33 columns]
0.5129151291512916
acc is : 0.5129151291512916
2023-07-20 16:00:17,113:INFO:logic:main.py:468:getModel:2218526: df_pred.iloc[-5:,:] :
     pred    prob_0    prob_1  actual  ...       nav  sign  cost_        bm
537     0  0.532957  0.467043       1  ...  0.955074   1.0    0.0  0.993019
538     0  0.550149  0.449851       1  ...  0.957313   1.0    0.0  0.995347
539     0  0.550469  0.449531       0  ...  0.955004   1.0    0.0  0.992946
540     0  0.507283  0.492717       1  ...  0.957694   1.0    0.0  0.995743
541     0  0.551806  0.448194       1  ...  0.957719   1.0    0.0  0.995769

[5 rows x 10 columns]
2023-07-20 16:00:17,126:INFO:logic:main.py:478:getModel:2218526: df_panel.iloc[-5:,:] :
    pred    prob_0    prob_1  actual  ...       nav  sign  cost_        bm
45     0  0.533449  0.466551       1  ...  0.938537   1.0    0.0  0.996700
46     0  0.550483  0.449517       1  ...  0.940738   1.0    0.0  0.997877
47     0  0.550505  0.449495       0  ...  0.955004   1.0    0.0  0.994737
48     0  0.507637  0.492363       1  ...  0.928776   1.0    0.0  0.998485
49     0  0.551806  0.448194       1  ...  0.957719   1.0    0.0  0.995769

[5 rows x 10 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '23.547', 'enterprice': '29974.9', 'countrevence': '0', 'unrealprofit': '5260.3998', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '30198.3', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}


## /root/FIL/strategy/modifiedmom/log.txt ----- -----

527  20230720   155000    155959  1689839999  30178.7  30195.5  0.000646
2023-07-20 16:00:02,198:INFO:modifiedmom:main.py:146:handleKline:2218259: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': True, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True}
127.0.0.1 - - [20/Jul/2023 16:10:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=9680 

self.closeSec=1689840599, self.tradeDate='20230720', self.openTime='160000', self.closeTime='160959', self.symbol='BTCUSDT', self.open='30195.6', self.close='30168.1'
2023-07-20 16:10:01,221:INFO:modifiedmom:main.py:144:handleKline:2218259: self.closeSec=1689840599, self.tradeDate='20230720', self.openTime='160000', self.closeTime='160959',self.symbol='BTCUSDT',self.open='30195.6', self.close='30168.1'
2023-07-20 16:10:01,233:INFO:modifiedmom:main.py:145:handleKline:2218259: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec     open    close       pct
524  20230720   152000    152959  1689838199    30133  30194.8  0.002051
525  20230720   153000    153959  1689838799  30194.8  30180.7 -0.000467
526  20230720   154000    154959  1689839399  30180.7    30176 -0.000156
527  20230720   155000    155959  1689839999  30178.7  30195.5  0.000646
528  20230720   160000    160959  1689840599  30195.6  30168.1 -0.000907
2023-07-20 16:10:01,233:INFO:modifiedmom:main.py:146:handleKline:2218259: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': True, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True}

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=9681 

self.closeSec=1689841199, self.tradeDate='20230720', self.openTime='161000', self.closeTime='161959', self.symbol='BTCUSDT', self.open='30168.1', self.close='30157.9'
127.0.0.1 - - [20/Jul/2023 16:20:04] "POST / HTTP/1.1" 200 -
2023-07-20 16:20:06,309:INFO:modifiedmom:main.py:144:handleKline:2218259: self.closeSec=1689841199, self.tradeDate='20230720', self.openTime='161000', self.closeTime='161959',self.symbol='BTCUSDT',self.open='30168.1', self.close='30157.9'
2023-07-20 16:20:06,872:INFO:modifiedmom:main.py:145:handleKline:2218259: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec     open    close       pct
525  20230720   153000    153959  1689838799  30194.8  30180.7 -0.000467
526  20230720   154000    154959  1689839399  30180.7    30176 -0.000156
527  20230720   155000    155959  1689839999  30178.7  30195.5  0.000646
528  20230720   160000    160959  1689840599  30195.6  30168.1 -0.000907
529  20230720   161000    161959  1689841199  30168.1  30157.9 -0.000338
2023-07-20 16:20:06,879:INFO:modifiedmom:main.py:146:handleKline:2218259: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': True, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True}


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

17519  20230720   155000    155959  1689839999  30178.7  30195.5
2023-07-20 16:00:02,234:INFO:pyemd2:main.py:127:handleKline:2217508: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=9683 

self.closeSec=1689840599, self.tradeDate='20230720', self.openTime='160000', self.closeTime='160959', self.symbol='BTCUSDT', self.open='30195.6', self.close='30168.1'
2023-07-20 16:10:01,225:INFO:pyemd2:main.py:125:handleKline:2217508: self.closeSec=1689840599, self.tradeDate='20230720', self.openTime='160000', self.closeTime='160959',self.symbol='BTCUSDT',self.open='30195.6', self.close='30168.1'
127.0.0.1 - - [20/Jul/2023 16:10:01] "POST / HTTP/1.1" 200 -
2023-07-20 16:10:01,233:INFO:pyemd2:main.py:126:handleKline:2217508: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
17516  20230720   152000    152959  1689838199    30133  30194.8
17517  20230720   153000    153959  1689838799  30194.8  30180.7
17518  20230720   154000    154959  1689839399  30180.7    30176
17519  20230720   155000    155959  1689839999  30178.7  30195.5
17520  20230720   160000    160959  1689840599  30195.6  30168.1
2023-07-20 16:10:01,233:INFO:pyemd2:main.py:127:handleKline:2217508: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=9684 

self.closeSec=1689841199, self.tradeDate='20230720', self.openTime='161000', self.closeTime='161959', self.symbol='BTCUSDT', self.open='30168.1', self.close='30157.9'
127.0.0.1 - - [20/Jul/2023 16:20:04] "POST / HTTP/1.1" 200 -
2023-07-20 16:20:07,582:INFO:pyemd2:main.py:125:handleKline:2217508: self.closeSec=1689841199, self.tradeDate='20230720', self.openTime='161000', self.closeTime='161959',self.symbol='BTCUSDT',self.open='30168.1', self.close='30157.9'
2023-07-20 16:20:07,775:INFO:pyemd2:main.py:126:handleKline:2217508: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
17517  20230720   153000    153959  1689838799  30194.8  30180.7
17518  20230720   154000    154959  1689839399  30180.7    30176
17519  20230720   155000    155959  1689839999  30178.7  30195.5
17520  20230720   160000    160959  1689840599  30195.6  30168.1
17521  20230720   161000    161959  1689841199  30168.1  30157.9
2023-07-20 16:20:07,775:INFO:pyemd2:main.py:127:handleKline:2217508: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}


## /root/FIL/strategy/similarity/log.txt ----- -----

12191  20230720   155000    155959  1689839999  30178.7  30195.5
2023-07-20 16:00:02,200:INFO:testStrategy:main.py:103:handleKline:2217133: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': True, 'isOpenSell': False, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True, 'isCorr': False}
127.0.0.1 - - [20/Jul/2023 16:10:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=9683 

self.closeSec=1689840599, self.tradeDate='20230720', self.openTime='160000', self.closeTime='160959', self.symbol='BTCUSDT', self.open='30195.6', self.close='30168.1'
2023-07-20 16:10:01,217:INFO:testStrategy:main.py:101:handleKline:2217133: self.closeSec=1689840599, self.tradeDate='20230720', self.openTime='160000', self.closeTime='160959',self.symbol='BTCUSDT',self.open='30195.6', self.close='30168.1'
2023-07-20 16:10:01,228:INFO:testStrategy:main.py:102:handleKline:2217133: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
12188  20230720   152000    152959  1689838199    30133  30194.8
12189  20230720   153000    153959  1689838799  30194.8  30180.7
12190  20230720   154000    154959  1689839399  30180.7    30176
12191  20230720   155000    155959  1689839999  30178.7  30195.5
12192  20230720   160000    160959  1689840599  30195.6  30168.1
2023-07-20 16:10:01,228:INFO:testStrategy:main.py:103:handleKline:2217133: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': True, 'isOpenSell': False, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True, 'isCorr': False}

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=9684 

self.closeSec=1689841199, self.tradeDate='20230720', self.openTime='161000', self.closeTime='161959', self.symbol='BTCUSDT', self.open='30168.1', self.close='30157.9'
127.0.0.1 - - [20/Jul/2023 16:20:04] "POST / HTTP/1.1" 200 -
2023-07-20 16:20:07,432:INFO:testStrategy:main.py:101:handleKline:2217133: self.closeSec=1689841199, self.tradeDate='20230720', self.openTime='161000', self.closeTime='161959',self.symbol='BTCUSDT',self.open='30168.1', self.close='30157.9'
2023-07-20 16:20:07,659:INFO:testStrategy:main.py:102:handleKline:2217133: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
12189  20230720   153000    153959  1689838799  30194.8  30180.7
12190  20230720   154000    154959  1689839399  30180.7    30176
12191  20230720   155000    155959  1689839999  30178.7  30195.5
12192  20230720   160000    160959  1689840599  30195.6  30168.1
12193  20230720   161000    161959  1689841199  30168.1  30157.9
2023-07-20 16:20:07,659:INFO:testStrategy:main.py:103:handleKline:2217133: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': True, 'isOpenSell': False, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True, 'isCorr': False}


## /root/FIL/strategy/sr_min/log.txt ----- -----

--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=1, self.total=996015.990996, self.flagDict['side']='buy', self.tradeCount=1, self.count=19360
self.closeSec=1689841199, self.tradeDate='20230720', self.openTime='161500', self.closeTime='161959', self.symbol='BTCUSDT', self.open=30186.7, self.close=30157.9, self.high=30189.6, self.low=30151.6, self.vol=747.362, self.amt=22546184.9641 
127.0.0.1 - - [20/Jul/2023 16:20:01] "POST / HTTP/1.1" 200 -
2023-07-20 16:20:05,280:INFO:sr_min:main.py:172:handleKline:2219263: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5951  20230720   155500    155959  ...         0.0        0.0       0
5952  20230720   160000    160459  ...         0.0        0.0       0
5953  20230720   160500    160959  ...         0.0        0.0       0
5954  20230720   161000    161459  ...         0.0        0.0       0
5955  20230720   161500    161959  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-07-20 16:20:05,301:INFO:sr_min:main.py:175:handleKline:2219263: self.closeSec=1689841199, self.tradeDate='20230720', self.openTime='161500', self.closeTime='161959',self.symbol='BTCUSDT',self.open=30186.7, self.close=30157.9, self.high=30189.6, self.low=30151.6, self.vol=747.362, self.amt=22546184.9641, ukdf['pct'].iloc[-1]=-0.000954 , ukdf['amount'].iloc[-1]=22546184.9641, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5955, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '37.141', 'enterprice': '26844', 'countrevence': '0', 'unrealprofit': '123486.3968', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '30168.8', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=1
127.0.0.1 - - [20/Jul/2023 16:25:00] "POST / HTTP/1.1" 200 -
--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=1, self.total=996015.990996, self.flagDict['side']='buy', self.tradeCount=1, self.count=19361
self.closeSec=1689841499, self.tradeDate='20230720', self.openTime='162000', self.closeTime='162459', self.symbol='BTCUSDT', self.open=30158.0, self.close=30181.6, self.high=30183.5, self.low=30157.9, self.vol=516.58, self.amt=15586803.0978 
2023-07-20 16:25:00,788:INFO:sr_min:main.py:172:handleKline:2219263: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5952  20230720   160000    160459  ...         0.0        0.0       0
5953  20230720   160500    160959  ...         0.0        0.0       0
5954  20230720   161000    161459  ...         0.0        0.0       0
5955  20230720   161500    161959  ...         0.0        0.0       0
5956  20230720   162000    162459  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-07-20 16:25:00,789:INFO:sr_min:main.py:175:handleKline:2219263: self.closeSec=1689841499, self.tradeDate='20230720', self.openTime='162000', self.closeTime='162459',self.symbol='BTCUSDT',self.open=30158.0, self.close=30181.6, self.high=30183.5, self.low=30157.9, self.vol=516.58, self.amt=15586803.0978, ukdf['pct'].iloc[-1]=0.000786 , ukdf['amount'].iloc[-1]=15586803.0978, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5956, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '37.141', 'enterprice': '26844', 'countrevence': '0', 'unrealprofit': '123958.0875', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '30181.5', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=1


## /root/FIL/strategy/s_rsrs/log.txt ----- -----

721  20230720   040000    075959  1689811199  ...    721  0.205868 -1.016732    -1.0
722  20230720   080000    115959  1689825599  ...    722  0.220827 -0.931568    -1.0

[5 rows x 15 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '52.176', 'enterprice': '29870.6', 'countrevence': '0', 'unrealprofit': '-3699.2784', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '29941.5', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'numpy.int64'>, curSign=-1, self.sign=-1
--handleKline--:  version='2.0.0', self.name='s_rsrs', self.symbol='BTCUSDT', interval='4h', intervalSec=14400, wid=25, thd=0.6, self.sign=-1, self.total=1556969.8971744, self.flagDict['side']='sell', self.tradeCount=12, self.count=403
self.closeSec=1689839999, self.tradeDate='20230720', self.openTime='120000', self.closeTime='155959', self.symbol='BTCUSDT', self.open=29937.0, self.close=30195.6, self.high=30240.2, self.low=29912.1, self.vol=54428.275, self.amt=1638943494.27447 
127.0.0.1 - - [20/Jul/2023 16:00:01] "POST / HTTP/1.1" 200 -
2023-07-20 16:00:01,785:INFO:s_rsrs:main.py:141:handleKline:2218689: self.closeSec=1689839999, self.tradeDate='20230720', self.openTime='120000', self.closeTime='155959',self.symbol='BTCUSDT',self.open=29937.0, self.close=30195.6, self.high=30240.2, self.low=29912.1, self.vol=54428.275, self.amt=1638943494.27447 
2023-07-20 16:00:01,800:INFO:s_rsrs:main.py:142:handleKline:2218689: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime  ...        vol           amt       pct
719  20230719   200000    235959  ...  89657.354  2.682031e+09 -0.002143
720  20230720   000000    035959  ...  50777.186  1.522327e+09  0.003073
721  20230720   040000    075959  ...  33370.022  9.980314e+08 -0.004558
722  20230720   080000    115959  ...  23383.135  7.005775e+08  0.001388
723  20230720   120000    155959  ...  54428.275  1.638943e+09  0.008638

[5 rows x 11 columns]
2023-07-20 16:00:02,568:INFO:s_rsrs:main.py:151:handleKline:2218689: df_s.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec  ...  index      beta    zscore  signal
719  20230719   200000    235959  1689782399  ...    719  0.193102 -1.108616    -1.0
720  20230720   000000    035959  1689796799  ...    720  0.197121 -1.073679    -1.0
721  20230720   040000    075959  1689811199  ...    721  0.205868 -1.016732    -1.0
722  20230720   080000    115959  1689825599  ...    722  0.220827 -0.931568    -1.0
723  20230720   120000    155959  1689839999  ...    723  0.212172 -0.948531    -1.0

[5 rows x 15 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '52.176', 'enterprice': '29870.6', 'countrevence': '0', 'unrealprofit': '-16957.2', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '30195.6', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'numpy.int64'>, curSign=-1, self.sign=-1


