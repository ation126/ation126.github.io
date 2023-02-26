# 20230226 16:26:01

## /root/FIL/strategy/amihud/log.txt ----- -----

--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=993672.4896432, self.flagDict['side']='sell', self.tradeCount=2, self.count=26236
self.closeSec=1677399599, self.tradeDate='20230226', self.openTime='161500', self.closeTime='161959', self.symbol='BTCUSDT', self.open=23129.7, self.close=23104.4, self.high=23129.8, self.low=23103.3, self.vol=842.989, self.amt=19485689.4937 
127.0.0.1 - - [26/Feb/2023 16:20:01] "POST / HTTP/1.1" 200 -
2023-02-26 16:20:01,637:INFO:amihud:main.py:172:handleKline:200676: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5951  20230226   155500    155959  ...         0.0        0.0       0
5952  20230226   160000    160459  ...         0.0        0.0       0
5953  20230226   160500    160959  ...         0.0        0.0       0
5954  20230226   161000    161459  ...         0.0        0.0       0
5955  20230226   161500    161959  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-02-26 16:20:01,638:INFO:amihud:main.py:175:handleKline:200676: self.closeSec=1677399599, self.tradeDate='20230226', self.openTime='161500', self.closeTime='161959',self.symbol='BTCUSDT',self.open=23129.7, self.close=23104.4, self.high=23129.8, self.low=23103.3, self.vol=842.989, self.amt=19485689.4937, ukdf['pct'].iloc[-1]=-0.001094 , ukdf['amount'].iloc[-1]=19485689.4937, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5955, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '60.176', 'enterprice': '16529.3', 'countrevence': '0', 'unrealprofit': '-395869.54183022896', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '23107.82867971', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1
--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=993672.4896432, self.flagDict['side']='sell', self.tradeCount=2, self.count=26237
self.closeSec=1677399899, self.tradeDate='20230226', self.openTime='162000', self.closeTime='162459', self.symbol='BTCUSDT', self.open=23104.3, self.close=23118.1, self.high=23128.2, self.low=23104.3, self.vol=454.457, self.amt=10506974.4665 
127.0.0.1 - - [26/Feb/2023 16:25:01] "POST / HTTP/1.1" 200 -
2023-02-26 16:25:01,557:INFO:amihud:main.py:172:handleKline:200676: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5952  20230226   160000    160459  ...         0.0        0.0       0
5953  20230226   160500    160959  ...         0.0        0.0       0
5954  20230226   161000    161459  ...         0.0        0.0       0
5955  20230226   161500    161959  ...         0.0        0.0       0
5956  20230226   162000    162459  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-02-26 16:25:01,560:INFO:amihud:main.py:175:handleKline:200676: self.closeSec=1677399899, self.tradeDate='20230226', self.openTime='162000', self.closeTime='162459',self.symbol='BTCUSDT',self.open=23104.3, self.close=23118.1, self.high=23128.2, self.low=23104.3, self.vol=454.457, self.amt=10506974.4665, ukdf['pct'].iloc[-1]=0.000593 , ukdf['amount'].iloc[-1]=10506974.4665, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5956, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '60.176', 'enterprice': '16529.3', 'countrevence': '0', 'unrealprofit': '-396481.6112', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '23118', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1


## /root/FIL/strategy/factorcheck/log.txt ----- -----

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=4, self.factor=0.5672898502524312, self.count=26802 

self.closeSec=1677399599, self.tradeDate='20230226', self.openTime='161500', self.closeTime='161959', self.symbol='BTCUSDT', self.open=23129.7, self.close=23104.4, self.high=23129.8, self.low=23103.3 
2023-02-26 16:20:01,518:INFO:factorcheck2:main.py:126:handleKline:185239: self.closeSec=1677399599, self.tradeDate='20230226', self.openTime='161500', self.closeTime='161959',self.symbol='BTCUSDT',self.open=23129.7, self.close=23104.4, self.high=23129.8, self.low=23103.3   
2023-02-26 16:20:01,576:INFO:factorcheck2:main.py:127:handleKline:185239: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime    closeSec  ...      low       pct  index  idx
1631  20230226   155500    155959  1677398399  ...  23127.5  0.000121   1631    5
1632  20230226   160000    160459  1677398699  ...  23133.4 -0.000398   1632    0
1633  20230226   160500    160959  1677398999  ...  23119.9 -0.000255   1633    1
1634  20230226   161000    161459  1677399299  ...  23127.6  0.000091   1634    2
1635  20230226   161500    161959  1677399599  ...  23103.3 -0.001094   1635    3

[5 rows x 11 columns]
2023-02-26 16:20:01,576:INFO:factorcheck2:main.py:128:handleKline:185239: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': True, 'isOpenSell': False, 'isCloseBuy': False, 'isCloseSell': False, 'isOpen': True, 'isClose': False, 'isTrig': True}

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=4, self.factor=0.5672898502524312, self.count=26803 

self.closeSec=1677399899, self.tradeDate='20230226', self.openTime='162000', self.closeTime='162459', self.symbol='BTCUSDT', self.open=23104.3, self.close=23118.1, self.high=23128.2, self.low=23104.3 
2023-02-26 16:25:01,493:INFO:factorcheck2:main.py:126:handleKline:185239: self.closeSec=1677399899, self.tradeDate='20230226', self.openTime='162000', self.closeTime='162459',self.symbol='BTCUSDT',self.open=23104.3, self.close=23118.1, self.high=23128.2, self.low=23104.3   
127.0.0.1 - - [26/Feb/2023 16:25:01] "POST / HTTP/1.1" 200 -
2023-02-26 16:25:01,536:INFO:factorcheck2:main.py:127:handleKline:185239: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime    closeSec  ...      low       pct  index  idx
1632  20230226   160000    160459  1677398699  ...  23133.4 -0.000398   1632    0
1633  20230226   160500    160959  1677398999  ...  23119.9 -0.000255   1633    1
1634  20230226   161000    161459  1677399299  ...  23127.6  0.000091   1634    2
1635  20230226   161500    161959  1677399599  ...  23103.3 -0.001094   1635    3
1636  20230226   162000    162459  1677399899  ...  23104.3  0.000593   1636    4

[5 rows x 11 columns]
2023-02-26 16:25:01,538:INFO:factorcheck2:main.py:128:handleKline:185239: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': True, 'isOpenSell': False, 'isCloseBuy': False, 'isCloseSell': False, 'isOpen': True, 'isClose': False, 'isTrig': True}


## /root/FIL/strategy/logic/log.txt ----- -----

2023-02-26 16:00:35,990:DEBUG:logic:main.py:463:getModel:885513: df_s.iloc[-5:,:] :
          date closeTime     open  ...    alpha58   alpha67   alpha72
5786  20230226    132959  23180.2  ...  47.916667  0.470182  0.308853
5787  20230226    135959  23149.9  ...  47.500000  0.462123  0.304120
5788  20230226    142959  23114.0  ...  47.916667  0.465137  0.298278
5789  20230226    145959  23125.6  ...  47.916667  0.473724  0.288763
5790  20230226    152959  23158.7  ...  47.916667  0.470950  0.281344

[5 rows x 33 columns]
0.551660516605166
acc is : 0.551660516605166
2023-02-26 16:00:36,163:INFO:logic:main.py:468:getModel:885513: df_pred.iloc[-5:,:] :
     pred    prob_0    prob_1  actual  ...       nav  sign  cost_        bm
537     0  0.507463  0.492537       0  ...  0.957401   1.0    0.0  1.044130
538     0  0.505172  0.494828       1  ...  0.957882   1.0    0.0  1.044654
539     0  0.514744  0.485256       1  ...  0.959253   1.0    0.0  1.046149
540     0  0.521888  0.478112       0  ...  0.958760   1.0    0.0  1.045611
541     0  0.513839  0.486161       0  ...  0.958590   1.0    0.0  1.045426

[5 rows x 10 columns]
2023-02-26 16:00:36,199:INFO:logic:main.py:478:getModel:885513: df_panel.iloc[-5:,:] :
    pred    prob_0    prob_1  actual  ...       nav  sign  cost_        bm
45     0  0.506595  0.493405       0  ...  0.949835   1.0    0.0  1.042265
46     0  0.503987  0.496013       1  ...  0.950312   1.0    0.0  1.041417
47     0  0.513919  0.486081       1  ...  0.951672   1.0    0.0  1.043777
48     0  0.521358  0.478642       0  ...  0.951183   1.0    0.0  1.044295
49     0  0.513839  0.486161       0  ...  0.958590   1.0    0.0  1.045426

[5 rows x 10 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '32.793', 'enterprice': '23035.2', 'countrevence': '0', 'unrealprofit': '3580.9956', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '23144.4', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}


## /root/FIL/strategy/modifiedmom/log.txt ----- -----

527  20230226   155000    155959  1677398399    23169  23142.7 -0.001139
2023-02-26 16:00:02,276:INFO:modifiedmom:main.py:146:handleKline:185213: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': True, 'isOpenSell': False, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True}

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=13400 

self.closeSec=1677398999, self.tradeDate='20230226', self.openTime='160000', self.closeTime='160959', self.symbol='BTCUSDT', self.open='23142.8', self.close='23127.6'
2023-02-26 16:10:01,616:INFO:modifiedmom:main.py:144:handleKline:185213: self.closeSec=1677398999, self.tradeDate='20230226', self.openTime='160000', self.closeTime='160959',self.symbol='BTCUSDT',self.open='23142.8', self.close='23127.6'
127.0.0.1 - - [26/Feb/2023 16:10:01] "POST / HTTP/1.1" 200 -
2023-02-26 16:10:01,637:INFO:modifiedmom:main.py:145:handleKline:185213: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec     open    close       pct
524  20230226   152000    152959  1677396599  23148.5  23146.8 -0.000073
525  20230226   153000    153959  1677397199  23146.7  23159.5  0.000549
526  20230226   154000    154959  1677397799  23159.4  23169.1  0.000415
527  20230226   155000    155959  1677398399    23169  23142.7 -0.001139
528  20230226   160000    160959  1677398999  23142.8  23127.6 -0.000652
2023-02-26 16:10:01,637:INFO:modifiedmom:main.py:146:handleKline:185213: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': True, 'isOpenSell': False, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True}
127.0.0.1 - - [26/Feb/2023 16:20:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=13401 

self.closeSec=1677399599, self.tradeDate='20230226', self.openTime='161000', self.closeTime='161959', self.symbol='BTCUSDT', self.open='23127.6', self.close='23104.4'
2023-02-26 16:20:01,631:INFO:modifiedmom:main.py:144:handleKline:185213: self.closeSec=1677399599, self.tradeDate='20230226', self.openTime='161000', self.closeTime='161959',self.symbol='BTCUSDT',self.open='23127.6', self.close='23104.4'
2023-02-26 16:20:01,662:INFO:modifiedmom:main.py:145:handleKline:185213: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec     open    close       pct
525  20230226   153000    153959  1677397199  23146.7  23159.5  0.000549
526  20230226   154000    154959  1677397799  23159.4  23169.1  0.000415
527  20230226   155000    155959  1677398399    23169  23142.7 -0.001139
528  20230226   160000    160959  1677398999  23142.8  23127.6 -0.000652
529  20230226   161000    161959  1677399599  23127.6  23104.4 -0.001003
2023-02-26 16:20:01,662:INFO:modifiedmom:main.py:146:handleKline:185213: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': True, 'isOpenSell': False, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True}


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

17519  20230226   155000    155959  1677398399    23169  23142.7
2023-02-26 16:00:02,294:INFO:pyemd2:main.py:127:handleKline:185189: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=13401 

self.closeSec=1677398999, self.tradeDate='20230226', self.openTime='160000', self.closeTime='160959', self.symbol='BTCUSDT', self.open='23142.8', self.close='23127.6'
2023-02-26 16:10:01,599:INFO:pyemd2:main.py:125:handleKline:185189: self.closeSec=1677398999, self.tradeDate='20230226', self.openTime='160000', self.closeTime='160959',self.symbol='BTCUSDT',self.open='23142.8', self.close='23127.6'
127.0.0.1 - - [26/Feb/2023 16:10:01] "POST / HTTP/1.1" 200 -
2023-02-26 16:10:01,641:INFO:pyemd2:main.py:126:handleKline:185189: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
17516  20230226   152000    152959  1677396599  23148.5  23146.8
17517  20230226   153000    153959  1677397199  23146.7  23159.5
17518  20230226   154000    154959  1677397799  23159.4  23169.1
17519  20230226   155000    155959  1677398399    23169  23142.7
17520  20230226   160000    160959  1677398999  23142.8  23127.6
2023-02-26 16:10:01,645:INFO:pyemd2:main.py:127:handleKline:185189: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}
127.0.0.1 - - [26/Feb/2023 16:20:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=13402 

self.closeSec=1677399599, self.tradeDate='20230226', self.openTime='161000', self.closeTime='161959', self.symbol='BTCUSDT', self.open='23127.6', self.close='23104.4'
2023-02-26 16:20:01,625:INFO:pyemd2:main.py:125:handleKline:185189: self.closeSec=1677399599, self.tradeDate='20230226', self.openTime='161000', self.closeTime='161959',self.symbol='BTCUSDT',self.open='23127.6', self.close='23104.4'
2023-02-26 16:20:01,645:INFO:pyemd2:main.py:126:handleKline:185189: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
17517  20230226   153000    153959  1677397199  23146.7  23159.5
17518  20230226   154000    154959  1677397799  23159.4  23169.1
17519  20230226   155000    155959  1677398399    23169  23142.7
17520  20230226   160000    160959  1677398999  23142.8  23127.6
17521  20230226   161000    161959  1677399599  23127.6  23104.4
2023-02-26 16:20:01,647:INFO:pyemd2:main.py:127:handleKline:185189: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}


## /root/FIL/strategy/similarity/log.txt ----- -----

12191  20230226   155000    155959  1677398399    23169  23142.7
2023-02-26 16:00:02,247:INFO:testStrategy:main.py:103:handleKline:185174: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': True, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True, 'isCorr': False}
127.0.0.1 - - [26/Feb/2023 16:10:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=13401 

self.closeSec=1677398999, self.tradeDate='20230226', self.openTime='160000', self.closeTime='160959', self.symbol='BTCUSDT', self.open='23142.8', self.close='23127.6'
2023-02-26 16:10:01,597:INFO:testStrategy:main.py:101:handleKline:185174: self.closeSec=1677398999, self.tradeDate='20230226', self.openTime='160000', self.closeTime='160959',self.symbol='BTCUSDT',self.open='23142.8', self.close='23127.6'
2023-02-26 16:10:01,638:INFO:testStrategy:main.py:102:handleKline:185174: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
12188  20230226   152000    152959  1677396599  23148.5  23146.8
12189  20230226   153000    153959  1677397199  23146.7  23159.5
12190  20230226   154000    154959  1677397799  23159.4  23169.1
12191  20230226   155000    155959  1677398399    23169  23142.7
12192  20230226   160000    160959  1677398999  23142.8  23127.6
2023-02-26 16:10:01,638:INFO:testStrategy:main.py:103:handleKline:185174: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': True, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True, 'isCorr': False}
127.0.0.1 - - [26/Feb/2023 16:20:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=13402 

self.closeSec=1677399599, self.tradeDate='20230226', self.openTime='161000', self.closeTime='161959', self.symbol='BTCUSDT', self.open='23127.6', self.close='23104.4'
2023-02-26 16:20:01,634:INFO:testStrategy:main.py:101:handleKline:185174: self.closeSec=1677399599, self.tradeDate='20230226', self.openTime='161000', self.closeTime='161959',self.symbol='BTCUSDT',self.open='23127.6', self.close='23104.4'
2023-02-26 16:20:01,675:INFO:testStrategy:main.py:102:handleKline:185174: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
12189  20230226   153000    153959  1677397199  23146.7  23159.5
12190  20230226   154000    154959  1677397799  23159.4  23169.1
12191  20230226   155000    155959  1677398399    23169  23142.7
12192  20230226   160000    160959  1677398999  23142.8  23127.6
12193  20230226   161000    161959  1677399599  23127.6  23104.4
2023-02-26 16:20:01,675:INFO:testStrategy:main.py:103:handleKline:185174: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': True, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True, 'isCorr': False}


## /root/FIL/strategy/sr_min/log.txt ----- -----

--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=0, self.total=1000000.0, self.flagDict['side']='', self.tradeCount=0, self.count=22234
self.closeSec=1677399599, self.tradeDate='20230226', self.openTime='161500', self.closeTime='161959', self.symbol='BTCUSDT', self.open=23129.7, self.close=23104.4, self.high=23129.8, self.low=23103.3, self.vol=842.989, self.amt=19485689.4937 
127.0.0.1 - - [26/Feb/2023 16:20:01] "POST / HTTP/1.1" 200 -
2023-02-26 16:20:01,589:INFO:sr_min:main.py:172:handleKline:449472: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5951  20230226   155500    155959  ...         0.0        0.0       0
5952  20230226   160000    160459  ...         0.0        0.0       0
5953  20230226   160500    160959  ...         0.0        0.0       0
5954  20230226   161000    161459  ...         0.0        0.0       0
5955  20230226   161500    161959  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-02-26 16:20:01,589:INFO:sr_min:main.py:175:handleKline:449472: self.closeSec=1677399599, self.tradeDate='20230226', self.openTime='161500', self.closeTime='161959',self.symbol='BTCUSDT',self.open=23129.7, self.close=23104.4, self.high=23129.8, self.low=23103.3, self.vol=842.989, self.amt=19485689.4937, ukdf['pct'].iloc[-1]=-0.001094 , ukdf['amount'].iloc[-1]=19485689.4937, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5955, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': []}
type(curSign)=<class 'int'>, curSign=0, self.sign=0
127.0.0.1 - - [26/Feb/2023 16:25:01] "POST / HTTP/1.1" 200 -
--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=0, self.total=1000000.0, self.flagDict['side']='', self.tradeCount=0, self.count=22235
self.closeSec=1677399899, self.tradeDate='20230226', self.openTime='162000', self.closeTime='162459', self.symbol='BTCUSDT', self.open=23104.3, self.close=23118.1, self.high=23128.2, self.low=23104.3, self.vol=454.457, self.amt=10506974.4665 
2023-02-26 16:25:01,573:INFO:sr_min:main.py:172:handleKline:449472: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5952  20230226   160000    160459  ...         0.0        0.0       0
5953  20230226   160500    160959  ...         0.0        0.0       0
5954  20230226   161000    161459  ...         0.0        0.0       0
5955  20230226   161500    161959  ...         0.0        0.0       0
5956  20230226   162000    162459  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-02-26 16:25:01,573:INFO:sr_min:main.py:175:handleKline:449472: self.closeSec=1677399899, self.tradeDate='20230226', self.openTime='162000', self.closeTime='162459',self.symbol='BTCUSDT',self.open=23104.3, self.close=23118.1, self.high=23128.2, self.low=23104.3, self.vol=454.457, self.amt=10506974.4665, ukdf['pct'].iloc[-1]=0.000593 , ukdf['amount'].iloc[-1]=10506974.4665, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5956, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': []}
type(curSign)=<class 'int'>, curSign=0, self.sign=0


## /root/FIL/strategy/s_rsrs/log.txt ----- -----

721  20230226   040000    075959  1677369599  ...    721  0.976690  0.818508     1.0
722  20230226   080000    115959  1677383999  ...    722  0.978998  0.816343     1.0

[5 rows x 15 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '42.179', 'enterprice': '23108.8', 'countrevence': '0', 'unrealprofit': '3972.0972884248', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '23202.9723912', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'numpy.int64'>, curSign=1, self.sign=1
--handleKline--:  version='2.0.0', self.name='s_rsrs', self.symbol='BTCUSDT', interval='4h', intervalSec=14400, wid=25, thd=0.6, self.sign=1, self.total=973731.3691248, self.flagDict['side']='buy', self.tradeCount=22, self.count=558
self.closeSec=1677398399, self.tradeDate='20230226', self.openTime='120000', self.closeTime='155959', self.symbol='BTCUSDT', self.open=23201.8, self.close=23142.7, self.high=23217.8, self.low=23077.2, self.vol=31491.179, self.amt=729220631.5998 
127.0.0.1 - - [26/Feb/2023 16:00:01] "POST / HTTP/1.1" 200 -
2023-02-26 16:00:01,984:INFO:s_rsrs:main.py:141:handleKline:185271: self.closeSec=1677398399, self.tradeDate='20230226', self.openTime='120000', self.closeTime='155959',self.symbol='BTCUSDT',self.open=23201.8, self.close=23142.7, self.high=23217.8, self.low=23077.2, self.vol=31491.179, self.amt=729220631.5998 
2023-02-26 16:00:02,061:INFO:s_rsrs:main.py:142:handleKline:185271: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime  ...        vol           amt       pct
719  20230225   200000    235959  ...  61274.986  1.407854e+09  0.000975
720  20230226   000000    035959  ...  46659.541  1.072898e+09 -0.000900
721  20230226   040000    075959  ...  83386.846  1.914106e+09  0.007421
722  20230226   080000    115959  ...  38352.322  8.878205e+08  0.002402
723  20230226   120000    155959  ...  31491.179  7.292206e+08 -0.002547

[5 rows x 11 columns]
2023-02-26 16:00:04,691:INFO:s_rsrs:main.py:151:handleKline:185271: df_s.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec  ...  index      beta    zscore  signal
719  20230225   200000    235959  1677340799  ...    719  0.975081  0.835976     1.0
720  20230226   000000    035959  1677355199  ...    720  1.032533  0.967372     1.0
721  20230226   040000    075959  1677369599  ...    721  0.976690  0.818508     1.0
722  20230226   080000    115959  1677383999  ...    722  0.978998  0.816343     1.0
723  20230226   120000    155959  1677398399  ...    723  0.973914  0.797723     1.0

[5 rows x 15 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '42.179', 'enterprice': '23108.8', 'countrevence': '0', 'unrealprofit': '1434.086', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '23142.8', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'numpy.int64'>, curSign=1, self.sign=1


