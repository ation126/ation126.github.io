# 20230215 00:36:27

## /root/FIL/strategy/amihud/log.txt ----- -----

--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=993672.4896432, self.flagDict['side']='sell', self.tradeCount=2, self.count=22878
self.closeSec=1676392199, self.tradeDate='20230215', self.openTime='002500', self.closeTime='002959', self.symbol='BTCUSDT', self.open=22059.9, self.close=21969.6, self.high=22074.3, self.low=21962.9, self.vol=4787.362, self.amt=105319003.2143 
127.0.0.1 - - [15/Feb/2023 00:30:01] "POST / HTTP/1.1" 200 -
2023-02-15 00:30:01,664:INFO:amihud:main.py:172:handleKline:200676: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5761  20230215   000500    000959  ...         0.0        0.0       0
5762  20230215   001000    001459  ...         0.0        0.0       0
5763  20230215   001500    001959  ...         0.0        0.0       0
5764  20230215   002000    002459  ...         0.0        0.0       0
5765  20230215   002500    002959  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-02-15 00:30:01,667:INFO:amihud:main.py:175:handleKline:200676: self.closeSec=1676392199, self.tradeDate='20230215', self.openTime='002500', self.closeTime='002959',self.symbol='BTCUSDT',self.open=22059.9, self.close=21969.6, self.high=22074.3, self.low=21962.9, self.vol=4787.362, self.amt=105319003.2143, ukdf['pct'].iloc[-1]=-0.004093 , ukdf['amount'].iloc[-1]=105319003.2143, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5765, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '60.176', 'enterprice': '16529.3', 'countrevence': '0', 'unrealprofit': '-327688.408', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '21974.8', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1
127.0.0.1 - - [15/Feb/2023 00:35:01] "POST / HTTP/1.1" 200 -
--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=993672.4896432, self.flagDict['side']='sell', self.tradeCount=2, self.count=22879
self.closeSec=1676392499, self.tradeDate='20230215', self.openTime='003000', self.closeTime='003459', self.symbol='BTCUSDT', self.open=21974.8, self.close=21969.8, self.high=21975.0, self.low=21935.0, self.vol=4376.702, self.amt=96091310.2376 
2023-02-15 00:35:01,666:INFO:amihud:main.py:172:handleKline:200676: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5762  20230215   001000    001459  ...         0.0        0.0       0
5763  20230215   001500    001959  ...         0.0        0.0       0
5764  20230215   002000    002459  ...         0.0        0.0       0
5765  20230215   002500    002959  ...         0.0        0.0       0
5766  20230215   003000    003459  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-02-15 00:35:01,666:INFO:amihud:main.py:175:handleKline:200676: self.closeSec=1676392499, self.tradeDate='20230215', self.openTime='003000', self.closeTime='003459',self.symbol='BTCUSDT',self.open=21974.8, self.close=21969.8, self.high=21975.0, self.low=21935.0, self.vol=4376.702, self.amt=96091310.2376, ukdf['pct'].iloc[-1]=9e-06 , ukdf['amount'].iloc[-1]=96091310.2376, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5766, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '60.176', 'enterprice': '16529.3', 'countrevence': '0', 'unrealprofit': '-327387.528', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '21969.8', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1


## /root/FIL/strategy/factorcheck/log.txt ----- -----

1444  20230215   002000    002459  1676391899  ...  22031.1 -0.000236   1444    4
1445  20230215   002500    002959  1676392199  ...  21962.9 -0.004093   1445    5

[5 rows x 11 columns]
2023-02-15 00:30:01,652:INFO:factorcheck2:main.py:128:handleKline:185239: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': True, 'isOpenSell': False, 'isCloseBuy': False, 'isCloseSell': False, 'isOpen': True, 'isClose': False, 'isTrig': True}
2023-02-15 00:30:01,740:INFO:factorcheck2:main.py:145:handleKline:185239: df_panel.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec  ...       pct  index  idx    factor
197  20230214   222500    222959  1676384999  ... -0.002028   1709    5  0.386545
198  20230214   225500    225959  1676386799  ...  0.010199   1715    5  0.377397
199  20230214   232500    232959  1676388599  ... -0.003696   1721    5  0.372263
200  20230214   235500    235959  1676390399  ...  0.003087   1727    5  0.371178
201  20230215   002500    002959  1676392199  ... -0.004093   1445    5  0.372535

[5 rows x 12 columns]
127.0.0.1 - - [15/Feb/2023 00:35:01] "POST / HTTP/1.1" 200 -

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=41, self.factor=0.3725354505815917, self.count=23445 

self.closeSec=1676392499, self.tradeDate='20230215', self.openTime='003000', self.closeTime='003459', self.symbol='BTCUSDT', self.open=21974.8, self.close=21969.8, self.high=21975.0, self.low=21935.0 
2023-02-15 00:35:01,519:INFO:factorcheck2:main.py:126:handleKline:185239: self.closeSec=1676392499, self.tradeDate='20230215', self.openTime='003000', self.closeTime='003459',self.symbol='BTCUSDT',self.open=21974.8, self.close=21969.8, self.high=21975.0, self.low=21935.0   
2023-02-15 00:35:01,609:INFO:factorcheck2:main.py:127:handleKline:185239: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime    closeSec  ...      low       pct  index  idx
1442  20230215   001000    001459  1676391299  ...  22002.2  0.000491   1442    2
1443  20230215   001500    001959  1676391599  ...  22008.5  0.002062   1443    3
1444  20230215   002000    002459  1676391899  ...  22031.1 -0.000236   1444    4
1445  20230215   002500    002959  1676392199  ...  21962.9 -0.004093   1445    5
1446  20230215   003000    003459  1676392499  ...  21935.0  0.000009   1446    0

[5 rows x 11 columns]
2023-02-15 00:35:01,609:INFO:factorcheck2:main.py:128:handleKline:185239: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': True, 'isOpenSell': False, 'isCloseBuy': False, 'isCloseSell': False, 'isOpen': True, 'isClose': False, 'isTrig': True}


## /root/FIL/strategy/logic/log.txt ----- -----

2023-02-15 00:30:35,049:DEBUG:logic:main.py:463:getModel:885513: df_s.iloc[-5:,:] :
          date closeTime     open  ...    alpha58   alpha67   alpha72
5755  20230214    215959  21825.1  ...  45.416667  0.491887  0.257141
5756  20230214    222959  21711.3  ...  45.000000  0.460431  0.287948
5757  20230214    225959  21600.0  ...  45.416667  0.606983  0.269972
5758  20230214    232959  22240.0  ...  45.416667  0.580933  0.266899
5759  20230214    235959  22133.1  ...  45.416667  0.557264  0.272002

[5 rows x 33 columns]
0.5398886827458256
acc is : 0.5398886827458256
2023-02-15 00:30:35,209:INFO:logic:main.py:468:getModel:885513: df_pred.iloc[-5:,:] :
     pred    prob_0    prob_1  actual  ...       nav  sign  cost_        bm
534     1  0.471958  0.528042       0  ...  0.969228   1.0    0.0  0.921616
535     1  0.458979  0.541021       1  ...  0.997766   1.0    0.0  0.948752
536     0  0.660351  0.339649       0  ...  0.993149   1.0    0.0  0.944362
537     0  0.507991  0.492009       0  ...  0.988671   1.0    0.0  0.940104
538     0  0.500653  0.499347       0  ...  0.986050   1.0    0.0  0.937612

[5 rows x 10 columns]
2023-02-15 00:30:35,244:INFO:logic:main.py:478:getModel:885513: df_panel.iloc[-5:,:] :
    pred    prob_0    prob_1  actual  ...       nav  sign  cost_        bm
45     1  0.471156  0.528844       0  ...  0.969228   1.0    0.0  0.918617
46     1  0.458084  0.541916       1  ...  0.997766   1.0    0.0  0.945665
47     0  0.663403  0.336597       0  ...  0.993149   1.0    0.0  0.942769
48     0  0.508314  0.491686       0  ...  0.988671   1.0    0.0  0.939302
49     0  0.500653  0.499347       0  ...  0.986050   1.0    0.0  0.937612

[5 rows x 10 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '35.557', 'enterprice': '21695.5', 'countrevence': '0', 'unrealprofit': '9934.6258', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '21974.9', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}


## /root/FIL/strategy/modifiedmom/log.txt ----- -----

576  20230215   000000    000959  1676390999  22033.4  22008.3 -0.001135
2023-02-15 00:10:01,908:INFO:modifiedmom:main.py:146:handleKline:185213: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': True, 'isOpen': False, 'isClose': True, 'isTrig': False}

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=11721 

self.closeSec=1676391599, self.tradeDate='20230215', self.openTime='001000', self.closeTime='001959', self.symbol='BTCUSDT', self.open='22008.2', self.close='22065.1'
2023-02-15 00:20:01,653:INFO:modifiedmom:main.py:144:handleKline:185213: self.closeSec=1676391599, self.tradeDate='20230215', self.openTime='001000', self.closeTime='001959',self.symbol='BTCUSDT',self.open='22008.2', self.close='22065.1'
127.0.0.1 - - [15/Feb/2023 00:20:01] "POST / HTTP/1.1" 200 -
2023-02-15 00:20:01,692:INFO:modifiedmom:main.py:145:handleKline:185213: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec     open    close       pct
573  20230214   233000    233959  1676389199  22133.1  21984.3 -0.006723
574  20230214   234000    234959  1676389799  21980.3  22043.2  0.002679
575  20230214   235000    235959  1676390399  22043.2  22033.3 -0.000449
576  20230215   000000    000959  1676390999  22033.4  22008.3 -0.001135
577  20230215   001000    001959  1676391599  22008.2  22065.1  0.002581
2023-02-15 00:20:01,693:INFO:modifiedmom:main.py:146:handleKline:185213: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': True, 'isOpen': False, 'isClose': True, 'isTrig': False}

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=11722 

self.closeSec=1676392199, self.tradeDate='20230215', self.openTime='002000', self.closeTime='002959', self.symbol='BTCUSDT', self.open='22065', self.close='21974.9'
127.0.0.1 - - [15/Feb/2023 00:30:01] "POST / HTTP/1.1" 200 -
2023-02-15 00:30:01,785:INFO:modifiedmom:main.py:144:handleKline:185213: self.closeSec=1676392199, self.tradeDate='20230215', self.openTime='002000', self.closeTime='002959',self.symbol='BTCUSDT',self.open='22065', self.close='21974.9'
2023-02-15 00:30:01,828:INFO:modifiedmom:main.py:145:handleKline:185213: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec     open    close       pct
574  20230214   234000    234959  1676389799  21980.3  22043.2  0.002679
575  20230214   235000    235959  1676390399  22043.2  22033.3 -0.000449
576  20230215   000000    000959  1676390999  22033.4  22008.3 -0.001135
577  20230215   001000    001959  1676391599  22008.2  22065.1  0.002581
578  20230215   002000    002959  1676392199    22065  21974.9 -0.004088
2023-02-15 00:30:01,828:INFO:modifiedmom:main.py:146:handleKline:185213: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': True, 'isOpen': False, 'isClose': True, 'isTrig': False}


## /root/FIL/strategy/percentile_regression_step2/log.txt ----- -----

127.0.0.1 - - [14/Feb/2023 23:30:02] "POST / HTTP/1.1" 200 -
2023-02-14 23:30:04,511:DEBUG:percentile_regression_step2:main.py:154:get_signal:1265985: df_id.iloc[-5:,:] :
                 daytime     hms    close  ...  pct_10  pct_20  factor
144  2023/02/14 21:00:00  210000  21830.9  ...     NaN     NaN       0
145  2023/02/14 21:30:00  213000  21711.3  ...     NaN     NaN       0
146  2023/02/14 22:00:00  220000  21600.0  ...     NaN     NaN       0
147  2023/02/14 22:30:00  223000  22236.0  ...     NaN     NaN       0
148  2023/02/14 23:00:00  230000  22133.1  ...     NaN     NaN       0

[5 rows x 10 columns]
127.0.0.1 - - [15/Feb/2023 00:00:02] "POST / HTTP/1.1" 200 -
2023-02-15 00:00:03,750:DEBUG:percentile_regression_step2:main.py:154:get_signal:1265985: df_id.iloc[-5:,:] :
                 daytime     hms    close  ...  pct_10  pct_20  factor
144  2023/02/14 21:30:00  213000  21711.3  ...     NaN     NaN       0
145  2023/02/14 22:00:00  220000  21600.0  ...     NaN     NaN       0
146  2023/02/14 22:30:00  223000  22236.0  ...     NaN     NaN       0
147  2023/02/14 23:00:00  230000  22133.1  ...     NaN     NaN       0
148  2023/02/14 23:30:00  233000  22033.3  ...     NaN     NaN       0

[5 rows x 10 columns]
127.0.0.1 - - [15/Feb/2023 00:30:01] "POST / HTTP/1.1" 200 -
2023-02-15 00:30:02,874:DEBUG:percentile_regression_step2:main.py:154:get_signal:1265985: df_id.iloc[-5:,:] :
                 daytime     hms    close  ...  pct_10  pct_20  factor
144  2023/02/14 22:00:00  220000  21600.0  ...     NaN     NaN       0
145  2023/02/14 22:30:00  223000  22236.0  ...     NaN     NaN       0
146  2023/02/14 23:00:00  230000  22133.1  ...     NaN     NaN       0
147  2023/02/14 23:30:00  233000  22033.3  ...     NaN     NaN       0
148  2023/02/15 00:00:00  000000  21974.9  ...     NaN     NaN       0

[5 rows x 10 columns]


## /root/FIL/strategy/pyemd/log.txt ----- -----

17424  20230215   000000    000959  1676390999  22033.4  22008.3
2023-02-15 00:10:01,915:INFO:pyemd2:main.py:127:handleKline:185189: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}
127.0.0.1 - - [15/Feb/2023 00:20:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=11722 

self.closeSec=1676391599, self.tradeDate='20230215', self.openTime='001000', self.closeTime='001959', self.symbol='BTCUSDT', self.open='22008.2', self.close='22065.1'
2023-02-15 00:20:01,695:INFO:pyemd2:main.py:125:handleKline:185189: self.closeSec=1676391599, self.tradeDate='20230215', self.openTime='001000', self.closeTime='001959',self.symbol='BTCUSDT',self.open='22008.2', self.close='22065.1'
2023-02-15 00:20:01,746:INFO:pyemd2:main.py:126:handleKline:185189: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
17421  20230214   233000    233959  1676389199  22133.1  21984.3
17422  20230214   234000    234959  1676389799  21980.3  22043.2
17423  20230214   235000    235959  1676390399  22043.2  22033.3
17424  20230215   000000    000959  1676390999  22033.4  22008.3
17425  20230215   001000    001959  1676391599  22008.2  22065.1
2023-02-15 00:20:01,746:INFO:pyemd2:main.py:127:handleKline:185189: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=11723 

self.closeSec=1676392199, self.tradeDate='20230215', self.openTime='002000', self.closeTime='002959', self.symbol='BTCUSDT', self.open='22065', self.close='21974.9'
127.0.0.1 - - [15/Feb/2023 00:30:01] "POST / HTTP/1.1" 200 -
2023-02-15 00:30:01,821:INFO:pyemd2:main.py:125:handleKline:185189: self.closeSec=1676392199, self.tradeDate='20230215', self.openTime='002000', self.closeTime='002959',self.symbol='BTCUSDT',self.open='22065', self.close='21974.9'
2023-02-15 00:30:01,872:INFO:pyemd2:main.py:126:handleKline:185189: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
17422  20230214   234000    234959  1676389799  21980.3  22043.2
17423  20230214   235000    235959  1676390399  22043.2  22033.3
17424  20230215   000000    000959  1676390999  22033.4  22008.3
17425  20230215   001000    001959  1676391599  22008.2  22065.1
17426  20230215   002000    002959  1676392199    22065  21974.9
2023-02-15 00:30:01,872:INFO:pyemd2:main.py:127:handleKline:185189: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}


## /root/FIL/strategy/similarity/log.txt ----- -----

12240  20230215   000000    000959  1676390999  22033.4  22008.3
2023-02-15 00:10:01,829:INFO:testStrategy:main.py:103:handleKline:185174: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': True, 'isOpen': False, 'isClose': True, 'isTrig': False, 'isCorr': False}
127.0.0.1 - - [15/Feb/2023 00:20:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=11722 

self.closeSec=1676391599, self.tradeDate='20230215', self.openTime='001000', self.closeTime='001959', self.symbol='BTCUSDT', self.open='22008.2', self.close='22065.1'
2023-02-15 00:20:01,684:INFO:testStrategy:main.py:101:handleKline:185174: self.closeSec=1676391599, self.tradeDate='20230215', self.openTime='001000', self.closeTime='001959',self.symbol='BTCUSDT',self.open='22008.2', self.close='22065.1'
2023-02-15 00:20:01,739:INFO:testStrategy:main.py:102:handleKline:185174: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
12237  20230214   233000    233959  1676389199  22133.1  21984.3
12238  20230214   234000    234959  1676389799  21980.3  22043.2
12239  20230214   235000    235959  1676390399  22043.2  22033.3
12240  20230215   000000    000959  1676390999  22033.4  22008.3
12241  20230215   001000    001959  1676391599  22008.2  22065.1
2023-02-15 00:20:01,739:INFO:testStrategy:main.py:103:handleKline:185174: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': True, 'isOpen': False, 'isClose': True, 'isTrig': False, 'isCorr': False}

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=11723 

self.closeSec=1676392199, self.tradeDate='20230215', self.openTime='002000', self.closeTime='002959', self.symbol='BTCUSDT', self.open='22065', self.close='21974.9'
127.0.0.1 - - [15/Feb/2023 00:30:01] "POST / HTTP/1.1" 200 -
2023-02-15 00:30:01,825:INFO:testStrategy:main.py:101:handleKline:185174: self.closeSec=1676392199, self.tradeDate='20230215', self.openTime='002000', self.closeTime='002959',self.symbol='BTCUSDT',self.open='22065', self.close='21974.9'
2023-02-15 00:30:01,856:INFO:testStrategy:main.py:102:handleKline:185174: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
12238  20230214   234000    234959  1676389799  21980.3  22043.2
12239  20230214   235000    235959  1676390399  22043.2  22033.3
12240  20230215   000000    000959  1676390999  22033.4  22008.3
12241  20230215   001000    001959  1676391599  22008.2  22065.1
12242  20230215   002000    002959  1676392199    22065  21974.9
2023-02-15 00:30:01,856:INFO:testStrategy:main.py:103:handleKline:185174: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': True, 'isOpen': False, 'isClose': True, 'isTrig': False, 'isCorr': False}


## /root/FIL/strategy/sr_min/log.txt ----- -----

127.0.0.1 - - [15/Feb/2023 00:30:01] "POST / HTTP/1.1" 200 -
--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=0, self.total=1000000.0, self.flagDict['side']='', self.tradeCount=0, self.count=18876
self.closeSec=1676392199, self.tradeDate='20230215', self.openTime='002500', self.closeTime='002959', self.symbol='BTCUSDT', self.open=22059.9, self.close=21969.6, self.high=22074.3, self.low=21962.9, self.vol=4787.362, self.amt=105319003.2143 
2023-02-15 00:30:01,736:INFO:sr_min:main.py:172:handleKline:449472: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5761  20230215   000500    000959  ...         0.0        0.0       0
5762  20230215   001000    001459  ...         0.0        0.0       0
5763  20230215   001500    001959  ...         0.0        0.0       0
5764  20230215   002000    002459  ...         0.0        0.0       0
5765  20230215   002500    002959  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-02-15 00:30:01,741:INFO:sr_min:main.py:175:handleKline:449472: self.closeSec=1676392199, self.tradeDate='20230215', self.openTime='002500', self.closeTime='002959',self.symbol='BTCUSDT',self.open=22059.9, self.close=21969.6, self.high=22074.3, self.low=21962.9, self.vol=4787.362, self.amt=105319003.2143, ukdf['pct'].iloc[-1]=-0.004093 , ukdf['amount'].iloc[-1]=105319003.2143, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5765, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': []}
type(curSign)=<class 'int'>, curSign=0, self.sign=0
127.0.0.1 - - [15/Feb/2023 00:35:01] "POST / HTTP/1.1" 200 -
--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=0, self.total=1000000.0, self.flagDict['side']='', self.tradeCount=0, self.count=18877
self.closeSec=1676392499, self.tradeDate='20230215', self.openTime='003000', self.closeTime='003459', self.symbol='BTCUSDT', self.open=21974.8, self.close=21969.8, self.high=21975.0, self.low=21935.0, self.vol=4376.702, self.amt=96091310.2376 
2023-02-15 00:35:01,678:INFO:sr_min:main.py:172:handleKline:449472: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5762  20230215   001000    001459  ...         0.0        0.0       0
5763  20230215   001500    001959  ...         0.0        0.0       0
5764  20230215   002000    002459  ...         0.0        0.0       0
5765  20230215   002500    002959  ...         0.0        0.0       0
5766  20230215   003000    003459  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-02-15 00:35:01,680:INFO:sr_min:main.py:175:handleKline:449472: self.closeSec=1676392499, self.tradeDate='20230215', self.openTime='003000', self.closeTime='003459',self.symbol='BTCUSDT',self.open=21974.8, self.close=21969.8, self.high=21975.0, self.low=21935.0, self.vol=4376.702, self.amt=96091310.2376, ukdf['pct'].iloc[-1]=9e-06 , ukdf['amount'].iloc[-1]=96091310.2376, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5766, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': []}
type(curSign)=<class 'int'>, curSign=0, self.sign=0


## /root/FIL/strategy/s_rsrs/log.txt ----- -----

723  20230214   120000    155959  1676361599  ...    723  0.050675 -2.624902    -1.0
724  20230214   160000    195959  1676375999  ...    724  0.055872 -2.478920    -1.0

[5 rows x 15 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '42.891', 'enterprice': '21599.9', 'countrevence': '0', 'unrealprofit': '-8556.7545', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '21799.4', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'numpy.int64'>, curSign=-1, self.sign=-1
--handleKline--:  version='2.0.0', self.name='s_rsrs', self.symbol='BTCUSDT', interval='4h', intervalSec=14400, wid=25, thd=0.6, self.sign=-1, self.total=925514.8695891, self.flagDict['side']='sell', self.tradeCount=19, self.count=488
self.closeSec=1676390399, self.tradeDate='20230214', self.openTime='200000', self.closeTime='235959', self.symbol='BTCUSDT', self.open=21798.9, self.close=22033.3, self.high=22320.0, self.low=21485.2, self.vol=325421.325, self.amt=7131807451.37556 
127.0.0.1 - - [15/Feb/2023 00:00:02] "POST / HTTP/1.1" 200 -
2023-02-15 00:00:02,214:INFO:s_rsrs:main.py:141:handleKline:185271: self.closeSec=1676390399, self.tradeDate='20230214', self.openTime='200000', self.closeTime='235959',self.symbol='BTCUSDT',self.open=21798.9, self.close=22033.3, self.high=22320.0, self.low=21485.2, self.vol=325421.325, self.amt=7131807451.37556 
2023-02-15 00:00:02,256:INFO:s_rsrs:main.py:142:handleKline:185271: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime  ...         vol           amt       pct
721  20230214   040000    075959  ...   54964.095  1.192266e+09  0.007797
722  20230214   080000    115959  ...   31405.193  6.823670e+08 -0.003418
723  20230214   120000    155959  ...   24174.292  5.252535e+08  0.003139
724  20230214   160000    195959  ...   47434.581  1.032453e+09  0.001792
725  20230214   200000    235959  ...  325421.325  7.131807e+09  0.010753

[5 rows x 11 columns]
2023-02-15 00:00:04,664:INFO:s_rsrs:main.py:151:handleKline:185271: df_s.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec  ...  index      beta    zscore  signal
721  20230214   040000    075959  1676332799  ...    721  0.070486 -2.822363    -1.0
722  20230214   080000    115959  1676347199  ...    722  0.062182 -2.710728    -1.0
723  20230214   120000    155959  1676361599  ...    723  0.050675 -2.624902    -1.0
724  20230214   160000    195959  1676375999  ...    724  0.055872 -2.478920    -1.0
725  20230214   200000    235959  1676390399  ...    725  0.003743 -2.580120    -1.0

[5 rows x 15 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '42.891', 'enterprice': '21599.9', 'countrevence': '0', 'unrealprofit': '-18658.83802882566', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '22034.92921426', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'numpy.int64'>, curSign=-1, self.sign=-1


