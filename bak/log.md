# 20230305 16:26:01

## /root/FIL/strategy/amihud/log.txt ----- -----

--handleKline--: 127.0.0.1 - - [05/Mar/2023 16:20:01] "POST / HTTP/1.1" 200 -
 version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=993672.4896432, self.flagDict['side']='sell', self.tradeCount=2, self.count=28252
self.closeSec=1678004399, self.tradeDate='20230305', self.openTime='161500', self.closeTime='161959', self.symbol='BTCUSDT', self.open=22382.9, self.close=22367.6, self.high=22386.0, self.low=22361.3, self.vol=683.67, self.amt=15295314.3909 
2023-03-05 16:20:02,370:INFO:amihud:main.py:172:handleKline:200676: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5951  20230305   155500    155959  ...         0.0        0.0       0
5952  20230305   160000    160459  ...         0.0        0.0       0
5953  20230305   160500    160959  ...         0.0        0.0       0
5954  20230305   161000    161459  ...         0.0        0.0       0
5955  20230305   161500    161959  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-03-05 16:20:02,373:INFO:amihud:main.py:175:handleKline:200676: self.closeSec=1678004399, self.tradeDate='20230305', self.openTime='161500', self.closeTime='161959',self.symbol='BTCUSDT',self.open=22382.9, self.close=22367.6, self.high=22386.0, self.low=22361.3, self.vol=683.67, self.amt=15295314.3909, ukdf['pct'].iloc[-1]=-0.000679 , ukdf['amount'].iloc[-1]=15295314.3909, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5955, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '60.176', 'enterprice': '16529.3', 'countrevence': '0', 'unrealprofit': '-351397.17988209584', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '22368.79049259', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1
--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=993672.4896432, self.flagDict['side']='sell', self.tradeCount=2, self.count=28253
self.closeSec=1678004699, self.tradeDate='20230305', self.openTime='162000', self.closeTime='162459', self.symbol='BTCUSDT', self.open=22367.7, self.close=22359.3, self.high=22374.8, self.low=22358.0, self.vol=511.29, self.amt=11435029.605 
127.0.0.1 - - [05/Mar/2023 16:25:01] "POST / HTTP/1.1" 200 -
2023-03-05 16:25:01,601:INFO:amihud:main.py:172:handleKline:200676: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5952  20230305   160000    160459  ...         0.0        0.0       0
5953  20230305   160500    160959  ...         0.0        0.0       0
5954  20230305   161000    161459  ...         0.0        0.0       0
5955  20230305   161500    161959  ...         0.0        0.0       0
5956  20230305   162000    162459  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-03-05 16:25:01,601:INFO:amihud:main.py:175:handleKline:200676: self.closeSec=1678004699, self.tradeDate='20230305', self.openTime='162000', self.closeTime='162459',self.symbol='BTCUSDT',self.open=22367.7, self.close=22359.3, self.high=22374.8, self.low=22358.0, self.vol=511.29, self.amt=11435029.605, ukdf['pct'].iloc[-1]=-0.000371 , ukdf['amount'].iloc[-1]=11435029.605, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5956, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '60.176', 'enterprice': '16529.3', 'countrevence': '0', 'unrealprofit': '-350868.84928744688', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '22360.01073663', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1


## /root/FIL/strategy/factorcheck/log.txt ----- -----


self.closeSec=1678004399, self.tradeDate='20230305', self.openTime='161500', self.closeTime='161959', self.symbol='BTCUSDT', self.open=22382.9, self.close=22367.6, self.high=22386.0, self.low=22361.3 
127.0.0.1 - - [05/Mar/2023 16:20:01] "POST / HTTP/1.1" 200 -
2023-03-05 16:20:01,667:INFO:factorcheck2:main.py:126:handleKline:185239: self.closeSec=1678004399, self.tradeDate='20230305', self.openTime='161500', self.closeTime='161959',self.symbol='BTCUSDT',self.open=22382.9, self.close=22367.6, self.high=22386.0, self.low=22361.3   
2023-03-05 16:20:01,771:INFO:factorcheck2:main.py:127:handleKline:185239: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime    closeSec  ...      low       pct  index  idx
1631  20230305   155500    155959  1678003199  ...  22358.6  0.000112   1631    5
1632  20230305   160000    160459  1678003499  ...  22355.6 -0.000300   1632    0
1633  20230305   160500    160959  1678003799  ...  22358.4  0.000425   1633    1
1634  20230305   161000    161459  1678004099  ...  22367.8  0.000666   1634    2
1635  20230305   161500    161959  1678004399  ...  22361.3 -0.000679   1635    3

[5 rows x 11 columns]
2023-03-05 16:20:01,771:INFO:factorcheck2:main.py:128:handleKline:185239: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=4, self.factor=0.4987675716585382, self.count=28819 

self.closeSec=1678004699, self.tradeDate='20230305', self.openTime='162000', self.closeTime='162459', self.symbol='BTCUSDT', self.open=22367.7, self.close=22359.3, self.high=22374.8, self.low=22358.0 
127.0.0.1 - - [05/Mar/2023 16:25:01] "POST / HTTP/1.1" 200 -
2023-03-05 16:25:01,494:INFO:factorcheck2:main.py:126:handleKline:185239: self.closeSec=1678004699, self.tradeDate='20230305', self.openTime='162000', self.closeTime='162459',self.symbol='BTCUSDT',self.open=22367.7, self.close=22359.3, self.high=22374.8, self.low=22358.0   
2023-03-05 16:25:01,538:INFO:factorcheck2:main.py:127:handleKline:185239: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime    closeSec  ...      low       pct  index  idx
1632  20230305   160000    160459  1678003499  ...  22355.6 -0.000300   1632    0
1633  20230305   160500    160959  1678003799  ...  22358.4  0.000425   1633    1
1634  20230305   161000    161459  1678004099  ...  22367.8  0.000666   1634    2
1635  20230305   161500    161959  1678004399  ...  22361.3 -0.000679   1635    3
1636  20230305   162000    162459  1678004699  ...  22358.0 -0.000371   1636    4

[5 rows x 11 columns]
2023-03-05 16:25:01,538:INFO:factorcheck2:main.py:128:handleKline:185239: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}


## /root/FIL/strategy/logic/log.txt ----- -----

2023-03-05 16:00:34,722:DEBUG:logic:main.py:463:getModel:885513: df_s.iloc[-5:,:] :
          date closeTime     open  ...    alpha58   alpha67   alpha72
5786  20230305    132959  22428.6  ...  47.083333  0.480956  0.429460
5787  20230305    135959  22416.2  ...  47.083333  0.478455  0.432976
5788  20230305    142959  22407.7  ...  47.083333  0.475339  0.437649
5789  20230305    145959  22397.2  ...  47.083333  0.478114  0.440897
5790  20230305    152959  22405.6  ...  47.083333  0.469667  0.447644

[5 rows x 33 columns]
0.5424354243542435
acc is : 0.5424354243542435
2023-03-05 16:00:34,907:INFO:logic:main.py:468:getModel:885513: df_pred.iloc[-5:,:] :
     pred    prob_0    prob_1  actual  ...       nav  sign  cost_        bm
537     0  0.511051  0.488949       0  ...  0.957779  -1.0    0.0  0.917972
538     0  0.502942  0.497058       0  ...  0.958228  -1.0    0.0  0.917542
539     0  0.504525  0.495475       1  ...  0.957869  -1.0    0.0  0.917886
540     0  0.504054  0.495946       0  ...  0.959066  -1.0    0.0  0.916739
541     1  0.486027  0.513973       0  ...  0.959601  -1.0    0.0  0.916227

[5 rows x 10 columns]
2023-03-05 16:00:34,933:INFO:logic:main.py:478:getModel:885513: df_panel.iloc[-5:,:] :
    pred    prob_0    prob_1  actual  ...       nav  sign  cost_        bm
45     0  0.510362  0.489638       0  ...  0.945667  -1.0    0.0  0.919143
46     0  0.502703  0.497297       0  ...  0.946110  -1.0    0.0  0.919822
47     0  0.503899  0.496101       1  ...  0.945755  -1.0    0.0  0.916632
48     0  0.503837  0.496163       0  ...  0.959066  -1.0    0.0  0.916551
49     1  0.486027  0.513973       0  ...  0.959601  -1.0    0.0  0.916227

[5 rows x 10 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '31.887', 'enterprice': '22396.9', 'countrevence': '0', 'unrealprofit': '1014.0066', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '22365.1', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}


## /root/FIL/strategy/modifiedmom/log.txt ----- -----

527  20230305   155000    155959  1678003199    22358  22365.1  0.000318
2023-03-05 16:00:02,175:INFO:modifiedmom:main.py:146:handleKline:185213: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': True, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True}
127.0.0.1 - - [05/Mar/2023 16:10:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=14408 

self.closeSec=1678003799, self.tradeDate='20230305', self.openTime='160000', self.closeTime='160959', self.symbol='BTCUSDT', self.open='22365.2', self.close='22367.9'
2023-03-05 16:10:01,633:INFO:modifiedmom:main.py:144:handleKline:185213: self.closeSec=1678003799, self.tradeDate='20230305', self.openTime='160000', self.closeTime='160959',self.symbol='BTCUSDT',self.open='22365.2', self.close='22367.9'
2023-03-05 16:10:01,687:INFO:modifiedmom:main.py:145:handleKline:185213: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec     open    close       pct
524  20230305   152000    152959  1678001399  22390.8  22377.6 -0.000594
525  20230305   153000    153959  1678001999  22377.6  22374.6 -0.000134
526  20230305   154000    154959  1678002599  22374.7    22358 -0.000742
527  20230305   155000    155959  1678003199    22358  22365.1  0.000318
528  20230305   160000    160959  1678003799  22365.2  22367.9  0.000125
2023-03-05 16:10:01,687:INFO:modifiedmom:main.py:146:handleKline:185213: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': True, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True}

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=14409 

self.closeSec=1678004399, self.tradeDate='20230305', self.openTime='161000', self.closeTime='161959', self.symbol='BTCUSDT', self.open='22367.8', self.close='22367.6'
127.0.0.1 - - [05/Mar/2023 16:20:01] "POST / HTTP/1.1" 200 -
2023-03-05 16:20:01,812:INFO:modifiedmom:main.py:144:handleKline:185213: self.closeSec=1678004399, self.tradeDate='20230305', self.openTime='161000', self.closeTime='161959',self.symbol='BTCUSDT',self.open='22367.8', self.close='22367.6'
2023-03-05 16:20:02,112:INFO:modifiedmom:main.py:145:handleKline:185213: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec     open    close       pct
525  20230305   153000    153959  1678001999  22377.6  22374.6 -0.000134
526  20230305   154000    154959  1678002599  22374.7    22358 -0.000742
527  20230305   155000    155959  1678003199    22358  22365.1  0.000318
528  20230305   160000    160959  1678003799  22365.2  22367.9  0.000125
529  20230305   161000    161959  1678004399  22367.8  22367.6 -0.000013
2023-03-05 16:20:02,113:INFO:modifiedmom:main.py:146:handleKline:185213: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': True, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True}


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

17519  20230305   155000    155959  1678003199    22358  22365.1
2023-03-05 16:00:02,197:INFO:pyemd2:main.py:127:handleKline:185189: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}
127.0.0.1 - - [05/Mar/2023 16:10:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=14409 

self.closeSec=1678003799, self.tradeDate='20230305', self.openTime='160000', self.closeTime='160959', self.symbol='BTCUSDT', self.open='22365.2', self.close='22367.9'
2023-03-05 16:10:01,663:INFO:pyemd2:main.py:125:handleKline:185189: self.closeSec=1678003799, self.tradeDate='20230305', self.openTime='160000', self.closeTime='160959',self.symbol='BTCUSDT',self.open='22365.2', self.close='22367.9'
2023-03-05 16:10:01,710:INFO:pyemd2:main.py:126:handleKline:185189: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
17516  20230305   152000    152959  1678001399  22390.8  22377.6
17517  20230305   153000    153959  1678001999  22377.6  22374.6
17518  20230305   154000    154959  1678002599  22374.7    22358
17519  20230305   155000    155959  1678003199    22358  22365.1
17520  20230305   160000    160959  1678003799  22365.2  22367.9
2023-03-05 16:10:01,710:INFO:pyemd2:main.py:127:handleKline:185189: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}
127.0.0.1 - - [05/Mar/2023 16:20:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=14410 

self.closeSec=1678004399, self.tradeDate='20230305', self.openTime='161000', self.closeTime='161959', self.symbol='BTCUSDT', self.open='22367.8', self.close='22367.6'
2023-03-05 16:20:02,265:INFO:pyemd2:main.py:125:handleKline:185189: self.closeSec=1678004399, self.tradeDate='20230305', self.openTime='161000', self.closeTime='161959',self.symbol='BTCUSDT',self.open='22367.8', self.close='22367.6'
2023-03-05 16:20:02,338:INFO:pyemd2:main.py:126:handleKline:185189: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
17517  20230305   153000    153959  1678001999  22377.6  22374.6
17518  20230305   154000    154959  1678002599  22374.7    22358
17519  20230305   155000    155959  1678003199    22358  22365.1
17520  20230305   160000    160959  1678003799  22365.2  22367.9
17521  20230305   161000    161959  1678004399  22367.8  22367.6
2023-03-05 16:20:02,338:INFO:pyemd2:main.py:127:handleKline:185189: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}


## /root/FIL/strategy/similarity/log.txt ----- -----

12191  20230305   155000    155959  1678003199    22358  22365.1
2023-03-05 16:00:02,212:INFO:testStrategy:main.py:103:handleKline:185174: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': True, 'isOpenSell': False, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True, 'isCorr': False}
127.0.0.1 - - [05/Mar/2023 16:10:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=14409 

self.closeSec=1678003799, self.tradeDate='20230305', self.openTime='160000', self.closeTime='160959', self.symbol='BTCUSDT', self.open='22365.2', self.close='22367.9'
2023-03-05 16:10:01,647:INFO:testStrategy:main.py:101:handleKline:185174: self.closeSec=1678003799, self.tradeDate='20230305', self.openTime='160000', self.closeTime='160959',self.symbol='BTCUSDT',self.open='22365.2', self.close='22367.9'
2023-03-05 16:10:01,701:INFO:testStrategy:main.py:102:handleKline:185174: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
12188  20230305   152000    152959  1678001399  22390.8  22377.6
12189  20230305   153000    153959  1678001999  22377.6  22374.6
12190  20230305   154000    154959  1678002599  22374.7    22358
12191  20230305   155000    155959  1678003199    22358  22365.1
12192  20230305   160000    160959  1678003799  22365.2  22367.9
2023-03-05 16:10:01,701:INFO:testStrategy:main.py:103:handleKline:185174: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': True, 'isOpenSell': False, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True, 'isCorr': False}

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=14410 

self.closeSec=1678004399, self.tradeDate='20230305', self.openTime='161000', self.closeTime='161959', self.symbol='BTCUSDT', self.open='22367.8', self.close='22367.6'
127.0.0.1 - - [05/Mar/2023 16:20:01] "POST / HTTP/1.1" 200 -
2023-03-05 16:20:02,199:INFO:testStrategy:main.py:101:handleKline:185174: self.closeSec=1678004399, self.tradeDate='20230305', self.openTime='161000', self.closeTime='161959',self.symbol='BTCUSDT',self.open='22367.8', self.close='22367.6'
2023-03-05 16:20:02,240:INFO:testStrategy:main.py:102:handleKline:185174: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
12189  20230305   153000    153959  1678001999  22377.6  22374.6
12190  20230305   154000    154959  1678002599  22374.7    22358
12191  20230305   155000    155959  1678003199    22358  22365.1
12192  20230305   160000    160959  1678003799  22365.2  22367.9
12193  20230305   161000    161959  1678004399  22367.8  22367.6
2023-03-05 16:20:02,241:INFO:testStrategy:main.py:103:handleKline:185174: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': True, 'isOpenSell': False, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True, 'isCorr': False}


## /root/FIL/strategy/sr_min/log.txt ----- -----

127.0.0.1 - - [05/Mar/2023 16:20:01] "POST / HTTP/1.1" 200 -
--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=0, self.total=1000000.0, self.flagDict['side']='', self.tradeCount=0, self.count=24250
self.closeSec=1678004399, self.tradeDate='20230305', self.openTime='161500', self.closeTime='161959', self.symbol='BTCUSDT', self.open=22382.9, self.close=22367.6, self.high=22386.0, self.low=22361.3, self.vol=683.67, self.amt=15295314.3909 
2023-03-05 16:20:01,568:INFO:sr_min:main.py:172:handleKline:449472: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5951  20230305   155500    155959  ...         0.0        0.0       0
5952  20230305   160000    160459  ...         0.0        0.0       0
5953  20230305   160500    160959  ...         0.0        0.0       0
5954  20230305   161000    161459  ...         0.0        0.0       0
5955  20230305   161500    161959  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-03-05 16:20:01,575:INFO:sr_min:main.py:175:handleKline:449472: self.closeSec=1678004399, self.tradeDate='20230305', self.openTime='161500', self.closeTime='161959',self.symbol='BTCUSDT',self.open=22382.9, self.close=22367.6, self.high=22386.0, self.low=22361.3, self.vol=683.67, self.amt=15295314.3909, ukdf['pct'].iloc[-1]=-0.000679 , ukdf['amount'].iloc[-1]=15295314.3909, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5955, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': []}
type(curSign)=<class 'int'>, curSign=0, self.sign=0
--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=0, self.total=1000000.0, self.flagDict['side']='', self.tradeCount=0, self.count=24251
self.closeSec=1678004699, self.tradeDate='20230305', self.openTime='162000', self.closeTime='162459', self.symbol='BTCUSDT', self.open=22367.7, self.close=22359.3, self.high=22374.8, self.low=22358.0, self.vol=511.29, self.amt=11435029.605 
127.0.0.1 - - [05/Mar/2023 16:25:01] "POST / HTTP/1.1" 200 -
2023-03-05 16:25:01,583:INFO:sr_min:main.py:172:handleKline:449472: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5952  20230305   160000    160459  ...         0.0        0.0       0
5953  20230305   160500    160959  ...         0.0        0.0       0
5954  20230305   161000    161459  ...         0.0        0.0       0
5955  20230305   161500    161959  ...         0.0        0.0       0
5956  20230305   162000    162459  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-03-05 16:25:01,585:INFO:sr_min:main.py:175:handleKline:449472: self.closeSec=1678004699, self.tradeDate='20230305', self.openTime='162000', self.closeTime='162459',self.symbol='BTCUSDT',self.open=22367.7, self.close=22359.3, self.high=22374.8, self.low=22358.0, self.vol=511.29, self.amt=11435029.605, ukdf['pct'].iloc[-1]=-0.000371 , ukdf['amount'].iloc[-1]=11435029.605, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5956, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': []}
type(curSign)=<class 'int'>, curSign=0, self.sign=0


## /root/FIL/strategy/s_rsrs/log.txt ----- -----

721  20230305   040000    075959  1677974399  ...    721  0.733079  0.486015     NaN
722  20230305   080000    115959  1677988799  ...    722  0.717200  0.456806     NaN

[5 rows x 15 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '42.135', 'enterprice': '23350.3', 'countrevence': '0', 'unrealprofit': '41085.8385', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '22375.2', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'numpy.int64'>, curSign=-9223372036854775808, self.sign=-1
127.0.0.1 - - [05/Mar/2023 16:00:01] "POST / HTTP/1.1" 200 -
--handleKline--:  version='2.0.0', self.name='s_rsrs', self.symbol='BTCUSDT', interval='4h', intervalSec=14400, wid=25, thd=0.6, self.sign=-1, self.total=982881.0256095, self.flagDict['side']='sell', self.tradeCount=23, self.count=600
self.closeSec=1678003199, self.tradeDate='20230305', self.openTime='120000', self.closeTime='155959', self.symbol='BTCUSDT', self.open=22374.2, self.close=22365.1, self.high=22461.8, self.low=22354.2, self.vol=30138.059, self.amt=675270132.6564 
2023-03-05 16:00:01,905:INFO:s_rsrs:main.py:141:handleKline:185271: self.closeSec=1678003199, self.tradeDate='20230305', self.openTime='120000', self.closeTime='155959',self.symbol='BTCUSDT',self.open=22374.2, self.close=22365.1, self.high=22461.8, self.low=22354.2, self.vol=30138.059, self.amt=675270132.6564 
2023-03-05 16:00:01,960:INFO:s_rsrs:main.py:142:handleKline:185271: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime  ...         vol           amt       pct
719  20230304   200000    235959  ...   22528.758  5.033403e+08 -0.001424
720  20230305   000000    035959  ...   29510.497  6.576456e+08 -0.003035
721  20230305   040000    075959  ...   51628.209  1.148461e+09  0.004366
722  20230305   080000    115959  ...  113479.717  2.546072e+09  0.001724
723  20230305   120000    155959  ...   30138.059  6.752701e+08 -0.000407

[5 rows x 11 columns]
2023-03-05 16:00:04,224:INFO:s_rsrs:main.py:151:handleKline:185271: df_s.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec  ...  index      beta    zscore  signal
719  20230304   200000    235959  1677945599  ...    719  0.685684  0.274947     NaN
720  20230305   000000    035959  1677959999  ...    720  0.719534  0.411752     NaN
721  20230305   040000    075959  1677974399  ...    721  0.733079  0.486015     NaN
722  20230305   080000    115959  1677988799  ...    722  0.717200  0.456806     NaN
723  20230305   120000    155959  1678003199  ...    723  0.723793  0.502248     NaN

[5 rows x 15 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '42.135', 'enterprice': '23350.3', 'countrevence': '0', 'unrealprofit': '41511.402', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '22365.1', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'numpy.int64'>, curSign=-9223372036854775808, self.sign=-1


