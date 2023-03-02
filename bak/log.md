# 20230302 16:26:01

## /root/FIL/strategy/amihud/log.txt ----- -----

127.0.0.1 - - [02/Mar/2023 16:20:01] "POST / HTTP/1.1" 200 -
--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=993672.4896432, self.flagDict['side']='sell', self.tradeCount=2, self.count=27388
self.closeSec=1677745199, self.tradeDate='20230302', self.openTime='161500', self.closeTime='161959', self.symbol='BTCUSDT', self.open=23385.1, self.close=23387.2, self.high=23397.0, self.low=23379.3, self.vol=849.759, self.amt=19873912.6055 
2023-03-02 16:20:01,647:INFO:amihud:main.py:172:handleKline:200676: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5951  20230302   155500    155959  ...         0.0        0.0       0
5952  20230302   160000    160459  ...         0.0        0.0       0
5953  20230302   160500    160959  ...         0.0        0.0       0
5954  20230302   161000    161459  ...         0.0        0.0       0
5955  20230302   161500    161959  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-03-02 16:20:01,649:INFO:amihud:main.py:175:handleKline:200676: self.closeSec=1677745199, self.tradeDate='20230302', self.openTime='161500', self.closeTime='161959',self.symbol='BTCUSDT',self.open=23385.1, self.close=23387.2, self.high=23397.0, self.low=23379.3, self.vol=849.759, self.amt=19873912.6055, ukdf['pct'].iloc[-1]=8.6e-05 , ukdf['amount'].iloc[-1]=19873912.6055, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5955, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '60.176', 'enterprice': '16529.3', 'countrevence': '0', 'unrealprofit': '-412699.68134602016', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '23387.51060466', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1
127.0.0.1 - - [02/Mar/2023 16:25:01] "POST / HTTP/1.1" 200 -
--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=993672.4896432, self.flagDict['side']='sell', self.tradeCount=2, self.count=27389
self.closeSec=1677745499, self.tradeDate='20230302', self.openTime='162000', self.closeTime='162459', self.symbol='BTCUSDT', self.open=23387.2, self.close=23383.2, self.high=23391.0, self.low=23378.2, self.vol=510.773, self.amt=11944269.2485 
2023-03-02 16:25:01,733:INFO:amihud:main.py:172:handleKline:200676: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5952  20230302   160000    160459  ...         0.0        0.0       0
5953  20230302   160500    160959  ...         0.0        0.0       0
5954  20230302   161000    161459  ...         0.0        0.0       0
5955  20230302   161500    161959  ...         0.0        0.0       0
5956  20230302   162000    162459  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-03-02 16:25:01,733:INFO:amihud:main.py:175:handleKline:200676: self.closeSec=1677745499, self.tradeDate='20230302', self.openTime='162000', self.closeTime='162459',self.symbol='BTCUSDT',self.open=23387.2, self.close=23383.2, self.high=23391.0, self.low=23378.2, self.vol=510.773, self.amt=11944269.2485, ukdf['pct'].iloc[-1]=-0.000171 , ukdf['amount'].iloc[-1]=11944269.2485, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5956, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '60.176', 'enterprice': '16529.3', 'countrevence': '0', 'unrealprofit': '-412428.2512', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '23383', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1


## /root/FIL/strategy/factorcheck/log.txt ----- -----

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=148, self.factor=0.5417556835910005, self.count=27954 

self.closeSec=1677745199, self.tradeDate='20230302', self.openTime='161500', self.closeTime='161959', self.symbol='BTCUSDT', self.open=23385.1, self.close=23387.2, self.high=23397.0, self.low=23379.3 
2023-03-02 16:20:01,548:INFO:factorcheck2:main.py:126:handleKline:185239: self.closeSec=1677745199, self.tradeDate='20230302', self.openTime='161500', self.closeTime='161959',self.symbol='BTCUSDT',self.open=23385.1, self.close=23387.2, self.high=23397.0, self.low=23379.3   
2023-03-02 16:20:01,615:INFO:factorcheck2:main.py:127:handleKline:185239: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime    closeSec  ...      low       pct  index  idx
1631  20230302   155500    155959  1677743999  ...  23368.7 -0.000064   1631    5
1632  20230302   160000    160459  1677744299  ...  23370.1 -0.000150   1632    0
1633  20230302   160500    160959  1677744599  ...  23361.0 -0.000663   1633    1
1634  20230302   161000    161459  1677744899  ...  23360.6  0.000955   1634    2
1635  20230302   161500    161959  1677745199  ...  23379.3  0.000086   1635    3

[5 rows x 11 columns]
2023-03-02 16:20:01,616:INFO:factorcheck2:main.py:128:handleKline:185239: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=148, self.factor=0.5417556835910005, self.count=27955 

self.closeSec=1677745499, self.tradeDate='20230302', self.openTime='162000', self.closeTime='162459', self.symbol='BTCUSDT', self.open=23387.2, self.close=23383.2, self.high=23391.0, self.low=23378.2 
2023-03-02 16:25:01,655:INFO:factorcheck2:main.py:126:handleKline:185239: self.closeSec=1677745499, self.tradeDate='20230302', self.openTime='162000', self.closeTime='162459',self.symbol='BTCUSDT',self.open=23387.2, self.close=23383.2, self.high=23391.0, self.low=23378.2   
127.0.0.1 - - [02/Mar/2023 16:25:01] "POST / HTTP/1.1" 200 -
2023-03-02 16:25:01,684:INFO:factorcheck2:main.py:127:handleKline:185239: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime    closeSec  ...      low       pct  index  idx
1632  20230302   160000    160459  1677744299  ...  23370.1 -0.000150   1632    0
1633  20230302   160500    160959  1677744599  ...  23361.0 -0.000663   1633    1
1634  20230302   161000    161459  1677744899  ...  23360.6  0.000955   1634    2
1635  20230302   161500    161959  1677745199  ...  23379.3  0.000086   1635    3
1636  20230302   162000    162459  1677745499  ...  23378.2 -0.000171   1636    4

[5 rows x 11 columns]
2023-03-02 16:25:01,684:INFO:factorcheck2:main.py:128:handleKline:185239: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}


## /root/FIL/strategy/logic/log.txt ----- -----

2023-03-02 16:00:35,249:DEBUG:logic:main.py:463:getModel:885513: df_s.iloc[-5:,:] :
          date closeTime     open  ...    alpha58   alpha67   alpha72
5786  20230302    132959  23528.8  ...  50.416667  0.491632  0.575832
5787  20230302    135959  23468.0  ...  50.416667  0.485461  0.586797
5788  20230302    142959  23437.1  ...  50.416667  0.489650  0.594825
5789  20230302    145959  23456.8  ...  50.000000  0.483564  0.605661
5790  20230302    152959  23426.9  ...  49.583333  0.473201  0.621544

[5 rows x 33 columns]
0.544280442804428
acc is : 0.544280442804428
2023-03-02 16:00:35,392:INFO:logic:main.py:468:getModel:885513: df_pred.iloc[-5:,:] :
     pred    prob_0    prob_1  actual  ...       nav  sign  cost_        bm
537     1  0.489378  0.510622       0  ...  0.847129  -1.0    0.0  0.947183
538     1  0.492039  0.507961       1  ...  0.846413  -1.0    0.0  0.947983
539     0  0.505533  0.494467       0  ...  0.847496  -1.0    0.0  0.946771
540     1  0.492720  0.507280       0  ...  0.849370  -1.0    0.0  0.944677
541     1  0.477714  0.522286       1  ...  0.849119  -1.0    0.0  0.944956

[5 rows x 10 columns]
2023-03-02 16:00:35,432:INFO:logic:main.py:478:getModel:885513: df_panel.iloc[-5:,:] :
    pred    prob_0    prob_1  actual  ...       nav  sign  cost_        bm
45     1  0.490355  0.509645       0  ...  0.830320  -1.0    0.0  0.951544
46     1  0.492514  0.507486       1  ...  0.846413  -1.0    0.0  0.951984
47     0  0.506467  0.493533       0  ...  0.830680  -1.0    0.0  0.950883
48     1  0.493159  0.506841       0  ...  0.849370  -1.0    0.0  0.945029
49     1  0.477714  0.522286       1  ...  0.849119  -1.0    0.0  0.944956

[5 rows x 10 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '32.484', 'enterprice': '23376.7', 'countrevence': '0', 'unrealprofit': '58.4712', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '23374.9', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}


## /root/FIL/strategy/modifiedmom/log.txt ----- -----

527  20230302   155000    155959  1677743999  23401.4  23381.9 -0.000833
2023-03-02 16:00:02,073:INFO:modifiedmom:main.py:146:handleKline:185213: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': True, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True}
127.0.0.1 - - [02/Mar/2023 16:10:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=13976 

self.closeSec=1677744599, self.tradeDate='20230302', self.openTime='160000', self.closeTime='160959', self.symbol='BTCUSDT', self.open='23381.8', self.close='23362.9'
2023-03-02 16:10:01,600:INFO:modifiedmom:main.py:144:handleKline:185213: self.closeSec=1677744599, self.tradeDate='20230302', self.openTime='160000', self.closeTime='160959',self.symbol='BTCUSDT',self.open='23381.8', self.close='23362.9'
2023-03-02 16:10:01,633:INFO:modifiedmom:main.py:145:handleKline:185213: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec     open    close       pct
524  20230302   152000    152959  1677742199  23404.7    23375 -0.001269
525  20230302   153000    153959  1677742799    23375  23374.9 -0.000004
526  20230302   154000    154959  1677743399  23374.9  23401.4  0.001134
527  20230302   155000    155959  1677743999  23401.4  23381.9 -0.000833
528  20230302   160000    160959  1677744599  23381.8  23362.9 -0.000813
2023-03-02 16:10:01,640:INFO:modifiedmom:main.py:146:handleKline:185213: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': True, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True}

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=13977 

self.closeSec=1677745199, self.tradeDate='20230302', self.openTime='161000', self.closeTime='161959', self.symbol='BTCUSDT', self.open='23362.9', self.close='23387.2'
2023-03-02 16:20:01,739:INFO:modifiedmom:main.py:144:handleKline:185213: self.closeSec=1677745199, self.tradeDate='20230302', self.openTime='161000', self.closeTime='161959',self.symbol='BTCUSDT',self.open='23362.9', self.close='23387.2'
127.0.0.1 - - [02/Mar/2023 16:20:01] "POST / HTTP/1.1" 200 -
2023-03-02 16:20:01,770:INFO:modifiedmom:main.py:145:handleKline:185213: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec     open    close       pct
525  20230302   153000    153959  1677742799    23375  23374.9 -0.000004
526  20230302   154000    154959  1677743399  23374.9  23401.4  0.001134
527  20230302   155000    155959  1677743999  23401.4  23381.9 -0.000833
528  20230302   160000    160959  1677744599  23381.8  23362.9 -0.000813
529  20230302   161000    161959  1677745199  23362.9  23387.2  0.001040
2023-03-02 16:20:01,772:INFO:modifiedmom:main.py:146:handleKline:185213: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': True, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True}


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

17519  20230302   155000    155959  1677743999  23401.4  23381.9
2023-03-02 16:00:02,093:INFO:pyemd2:main.py:127:handleKline:185189: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}
127.0.0.1 - - [02/Mar/2023 16:10:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=13977 

self.closeSec=1677744599, self.tradeDate='20230302', self.openTime='160000', self.closeTime='160959', self.symbol='BTCUSDT', self.open='23381.8', self.close='23362.9'
2023-03-02 16:10:01,624:INFO:pyemd2:main.py:125:handleKline:185189: self.closeSec=1677744599, self.tradeDate='20230302', self.openTime='160000', self.closeTime='160959',self.symbol='BTCUSDT',self.open='23381.8', self.close='23362.9'
2023-03-02 16:10:01,643:INFO:pyemd2:main.py:126:handleKline:185189: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
17516  20230302   152000    152959  1677742199  23404.7    23375
17517  20230302   153000    153959  1677742799    23375  23374.9
17518  20230302   154000    154959  1677743399  23374.9  23401.4
17519  20230302   155000    155959  1677743999  23401.4  23381.9
17520  20230302   160000    160959  1677744599  23381.8  23362.9
2023-03-02 16:10:01,643:INFO:pyemd2:main.py:127:handleKline:185189: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=13978 

self.closeSec=1677745199, self.tradeDate='20230302', self.openTime='161000', self.closeTime='161959', self.symbol='BTCUSDT', self.open='23362.9', self.close='23387.2'
127.0.0.1 - - [02/Mar/2023 16:20:01] "POST / HTTP/1.1" 200 -
2023-03-02 16:20:01,708:INFO:pyemd2:main.py:125:handleKline:185189: self.closeSec=1677745199, self.tradeDate='20230302', self.openTime='161000', self.closeTime='161959',self.symbol='BTCUSDT',self.open='23362.9', self.close='23387.2'
2023-03-02 16:20:01,761:INFO:pyemd2:main.py:126:handleKline:185189: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
17517  20230302   153000    153959  1677742799    23375  23374.9
17518  20230302   154000    154959  1677743399  23374.9  23401.4
17519  20230302   155000    155959  1677743999  23401.4  23381.9
17520  20230302   160000    160959  1677744599  23381.8  23362.9
17521  20230302   161000    161959  1677745199  23362.9  23387.2
2023-03-02 16:20:01,761:INFO:pyemd2:main.py:127:handleKline:185189: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}


## /root/FIL/strategy/similarity/log.txt ----- -----

12191  20230302   155000    155959  1677743999  23401.4  23381.9
2023-03-02 16:00:02,072:INFO:testStrategy:main.py:103:handleKline:185174: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': True, 'isOpenSell': False, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True, 'isCorr': False}

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=13977 

self.closeSec=1677744599, self.tradeDate='20230302', self.openTime='160000', self.closeTime='160959', self.symbol='BTCUSDT', self.open='23381.8', self.close='23362.9'
127.0.0.1 - - [02/Mar/2023 16:10:01] "POST / HTTP/1.1" 200 -
2023-03-02 16:10:01,623:INFO:testStrategy:main.py:101:handleKline:185174: self.closeSec=1677744599, self.tradeDate='20230302', self.openTime='160000', self.closeTime='160959',self.symbol='BTCUSDT',self.open='23381.8', self.close='23362.9'
2023-03-02 16:10:01,637:INFO:testStrategy:main.py:102:handleKline:185174: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
12188  20230302   152000    152959  1677742199  23404.7    23375
12189  20230302   153000    153959  1677742799    23375  23374.9
12190  20230302   154000    154959  1677743399  23374.9  23401.4
12191  20230302   155000    155959  1677743999  23401.4  23381.9
12192  20230302   160000    160959  1677744599  23381.8  23362.9
2023-03-02 16:10:01,637:INFO:testStrategy:main.py:103:handleKline:185174: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': True, 'isOpenSell': False, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True, 'isCorr': False}

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=13978 

self.closeSec=1677745199, self.tradeDate='20230302', self.openTime='161000', self.closeTime='161959', self.symbol='BTCUSDT', self.open='23362.9', self.close='23387.2'
127.0.0.1 - - [02/Mar/2023 16:20:01] "POST / HTTP/1.1" 200 -
2023-03-02 16:20:01,756:INFO:testStrategy:main.py:101:handleKline:185174: self.closeSec=1677745199, self.tradeDate='20230302', self.openTime='161000', self.closeTime='161959',self.symbol='BTCUSDT',self.open='23362.9', self.close='23387.2'
2023-03-02 16:20:01,782:INFO:testStrategy:main.py:102:handleKline:185174: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
12189  20230302   153000    153959  1677742799    23375  23374.9
12190  20230302   154000    154959  1677743399  23374.9  23401.4
12191  20230302   155000    155959  1677743999  23401.4  23381.9
12192  20230302   160000    160959  1677744599  23381.8  23362.9
12193  20230302   161000    161959  1677745199  23362.9  23387.2
2023-03-02 16:20:01,782:INFO:testStrategy:main.py:103:handleKline:185174: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': True, 'isOpenSell': False, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True, 'isCorr': False}


## /root/FIL/strategy/sr_min/log.txt ----- -----

--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=0, self.total=1000000.0, self.flagDict['side']='', self.tradeCount=0, self.count=23386
self.closeSec=1677745199, self.tradeDate='20230302', self.openTime='161500', self.closeTime='161959', self.symbol='BTCUSDT', self.open=23385.1, self.close=23387.2, self.high=23397.0, self.low=23379.3, self.vol=849.759, self.amt=19873912.6055 
127.0.0.1 - - [02/Mar/2023 16:20:01] "POST / HTTP/1.1" 200 -
2023-03-02 16:20:01,561:INFO:sr_min:main.py:172:handleKline:449472: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5951  20230302   155500    155959  ...         0.0        0.0       0
5952  20230302   160000    160459  ...         0.0        0.0       0
5953  20230302   160500    160959  ...         0.0        0.0       0
5954  20230302   161000    161459  ...         0.0        0.0       0
5955  20230302   161500    161959  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-03-02 16:20:01,562:INFO:sr_min:main.py:175:handleKline:449472: self.closeSec=1677745199, self.tradeDate='20230302', self.openTime='161500', self.closeTime='161959',self.symbol='BTCUSDT',self.open=23385.1, self.close=23387.2, self.high=23397.0, self.low=23379.3, self.vol=849.759, self.amt=19873912.6055, ukdf['pct'].iloc[-1]=8.6e-05 , ukdf['amount'].iloc[-1]=19873912.6055, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5955, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': []}
type(curSign)=<class 'int'>, curSign=0, self.sign=0
127.0.0.1 - - [02/Mar/2023 16:25:01] "POST / HTTP/1.1" 200 -
--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=0, self.total=1000000.0, self.flagDict['side']='', self.tradeCount=0, self.count=23387
self.closeSec=1677745499, self.tradeDate='20230302', self.openTime='162000', self.closeTime='162459', self.symbol='BTCUSDT', self.open=23387.2, self.close=23383.2, self.high=23391.0, self.low=23378.2, self.vol=510.773, self.amt=11944269.2485 
2023-03-02 16:25:01,735:INFO:sr_min:main.py:172:handleKline:449472: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5952  20230302   160000    160459  ...         0.0        0.0       0
5953  20230302   160500    160959  ...         0.0        0.0       0
5954  20230302   161000    161459  ...         0.0        0.0       0
5955  20230302   161500    161959  ...         0.0        0.0       0
5956  20230302   162000    162459  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-03-02 16:25:01,735:INFO:sr_min:main.py:175:handleKline:449472: self.closeSec=1677745499, self.tradeDate='20230302', self.openTime='162000', self.closeTime='162459',self.symbol='BTCUSDT',self.open=23387.2, self.close=23383.2, self.high=23391.0, self.low=23378.2, self.vol=510.773, self.amt=11944269.2485, ukdf['pct'].iloc[-1]=-0.000171 , ukdf['amount'].iloc[-1]=11944269.2485, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5956, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': []}
type(curSign)=<class 'int'>, curSign=0, self.sign=0


## /root/FIL/strategy/s_rsrs/log.txt ----- -----

721  20230302   040000    075959  1677715199  ...    721  0.605781 -0.246234     NaN
722  20230302   080000    115959  1677729599  ...    722  0.744600  0.123421     NaN

[5 rows x 15 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '42.179', 'enterprice': '23108.8', 'countrevence': '0', 'unrealprofit': '15913.27941646469', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '23486.07967511', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'numpy.int64'>, curSign=-9223372036854775808, self.sign=1
127.0.0.1 - - [02/Mar/2023 16:00:01] "POST / HTTP/1.1" 200 -
--handleKline--:  version='2.0.0', self.name='s_rsrs', self.symbol='BTCUSDT', interval='4h', intervalSec=14400, wid=25, thd=0.6, self.sign=1, self.total=973731.3691248, self.flagDict['side']='buy', self.tradeCount=22, self.count=582
self.closeSec=1677743999, self.tradeDate='20230302', self.openTime='120000', self.closeTime='155959', self.symbol='BTCUSDT', self.open=23487.1, self.close=23381.9, self.high=23535.9, self.low=23325.0, self.vol=49671.496, self.amt=1163425392.2782 
2023-03-02 16:00:01,942:INFO:s_rsrs:main.py:141:handleKline:185271: self.closeSec=1677743999, self.tradeDate='20230302', self.openTime='120000', self.closeTime='155959',self.symbol='BTCUSDT',self.open=23487.1, self.close=23381.9, self.high=23535.9, self.low=23325.0, self.vol=49671.496, self.amt=1163425392.2782 
2023-03-02 16:00:02,014:INFO:s_rsrs:main.py:142:handleKline:185271: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime  ...         vol           amt       pct
719  20230301   200000    235959  ...  137452.515  3.257164e+09 -0.001432
720  20230302   000000    035959  ...   97637.359  2.302435e+09 -0.015184
721  20230302   040000    075959  ...   79548.850  1.867409e+09  0.011862
722  20230302   080000    115959  ...   66503.537  1.567660e+09 -0.005618
723  20230302   120000    155959  ...   49671.496  1.163425e+09 -0.004479

[5 rows x 11 columns]
2023-03-02 16:00:04,103:INFO:s_rsrs:main.py:151:handleKline:185271: df_s.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec  ...  index      beta    zscore  signal
719  20230301   200000    235959  1677686399  ...    719  0.744879  0.171695     NaN
720  20230302   000000    035959  1677700799  ...    720  0.693070  0.012446     NaN
721  20230302   040000    075959  1677715199  ...    721  0.605781 -0.246234     NaN
722  20230302   080000    115959  1677729599  ...    722  0.744600  0.123421     NaN
723  20230302   120000    155959  1677743999  ...    723  0.643526 -0.179710     NaN

[5 rows x 15 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '42.179', 'enterprice': '23108.8', 'countrevence': '0', 'unrealprofit': '11519.0849', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '23381.9', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'numpy.int64'>, curSign=-9223372036854775808, self.sign=1


