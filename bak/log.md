# 20230204 08:35:50

## /root/FIL/strategy/amihud/log.txt ----- -----

--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=993672.4896432, self.flagDict['side']='sell', self.tradeCount=2, self.count=19806
self.closeSec=1675470599, self.tradeDate='20230204', self.openTime='082500', self.closeTime='082959', self.symbol='BTCUSDT', self.open=23417.7, self.close=23439.4, self.high=23439.4, self.low=23417.7, self.vol=503.438, self.amt=11794814.3533 
127.0.0.1 - - [04/Feb/2023 08:30:00] "POST / HTTP/1.1" 200 -
2023-02-04 08:30:00,915:INFO:amihud:main.py:172:handleKline:200676: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5857  20230204   080500    080959  ...         0.0        0.0       0
5858  20230204   081000    081459  ...         0.0        0.0       0
5859  20230204   081500    081959  ...         0.0        0.0       0
5860  20230204   082000    082459  ...         0.0        0.0       0
5861  20230204   082500    082959  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-02-04 08:30:00,915:INFO:amihud:main.py:175:handleKline:200676: self.closeSec=1675470599, self.tradeDate='20230204', self.openTime='082500', self.closeTime='082959',self.symbol='BTCUSDT',self.open=23417.7, self.close=23439.4, self.high=23439.4, self.low=23417.7, self.vol=503.438, self.amt=11794814.3533, ukdf['pct'].iloc[-1]=0.000922 , ukdf['amount'].iloc[-1]=11794814.3533, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5861, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '60.176', 'enterprice': '16529.3', 'countrevence': '0', 'unrealprofit': '-415822.1776', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '23439.4', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1
--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=993672.4896432, self.flagDict['side']='sell', self.tradeCount=2, self.count=19807
self.closeSec=1675470899, self.tradeDate='20230204', self.openTime='083000', self.closeTime='083459', self.symbol='BTCUSDT', self.open=23439.3, self.close=23446.8, self.high=23446.8, self.low=23435.6, self.vol=551.481, self.amt=12927567.6083 
127.0.0.1 - - [04/Feb/2023 08:35:00] "POST / HTTP/1.1" 200 -
2023-02-04 08:35:00,693:INFO:amihud:main.py:172:handleKline:200676: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5858  20230204   081000    081459  ...         0.0        0.0       0
5859  20230204   081500    081959  ...         0.0        0.0       0
5860  20230204   082000    082459  ...         0.0        0.0       0
5861  20230204   082500    082959  ...         0.0        0.0       0
5862  20230204   083000    083459  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-02-04 08:35:00,694:INFO:amihud:main.py:175:handleKline:200676: self.closeSec=1675470899, self.tradeDate='20230204', self.openTime='083000', self.closeTime='083459',self.symbol='BTCUSDT',self.open=23439.3, self.close=23446.8, self.high=23446.8, self.low=23435.6, self.vol=551.481, self.amt=12927567.6083, ukdf['pct'].iloc[-1]=0.000316 , ukdf['amount'].iloc[-1]=12927567.6083, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5862, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '60.176', 'enterprice': '16529.3', 'countrevence': '0', 'unrealprofit': '-416267.48', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '23446.8', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1


## /root/FIL/strategy/factorcheck/log.txt ----- -----

1541  20230204   082500    082959  1675470599  ...  23417.7  0.000922   1541    5

[5 rows x 11 columns]
2023-02-04 08:30:00,957:INFO:factorcheck2:main.py:128:handleKline:185239: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': True, 'isOpenSell': False, 'isCloseBuy': False, 'isCloseSell': False, 'isOpen': True, 'isClose': False, 'isTrig': True}
2023-02-04 08:30:01,008:INFO:factorcheck2:main.py:145:handleKline:185239: df_panel.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec  ...       pct  index  idx    factor
213  20230204   062500    062959  1675463399  ... -0.001563   1517    5  0.636597
214  20230204   065500    065959  1675465199  ...  0.000397   1523    5  0.635737
215  20230204   072500    072959  1675466999  ...  0.000128   1529    5  0.633528
216  20230204   075500    075959  1675468799  ...  0.000132   1535    5  0.632363
217  20230204   082500    082959  1675470599  ...  0.000922   1541    5  0.630478

[5 rows x 12 columns]
2023-02-04 08:30:01,027:INFO:factorcheck2:main.py:201:insertFactor:185239: curDateTime:2040830, name:factorcheck2, symbol:BTCUSDT, tradeDate:20230204, closeTime:082959, close:23439.4, total:928613.5591976999, factor:0.6304776367019345, factorCnt:0, side:buy 
127.0.0.1 - - [04/Feb/2023 08:35:00] "POST / HTTP/1.1" 200 -

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=0, self.factor=0.6304776367019345, self.count=20373 

self.closeSec=1675470899, self.tradeDate='20230204', self.openTime='083000', self.closeTime='083459', self.symbol='BTCUSDT', self.open=23439.3, self.close=23446.8, self.high=23446.8, self.low=23435.6 
2023-02-04 08:35:00,639:INFO:factorcheck2:main.py:126:handleKline:185239: self.closeSec=1675470899, self.tradeDate='20230204', self.openTime='083000', self.closeTime='083459',self.symbol='BTCUSDT',self.open=23439.3, self.close=23446.8, self.high=23446.8, self.low=23435.6   
2023-02-04 08:35:00,685:INFO:factorcheck2:main.py:127:handleKline:185239: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime    closeSec  ...      low       pct  index  idx
1538  20230204   081000    081459  1675469699  ...  23378.4 -0.000303   1538    2
1539  20230204   081500    081959  1675469999  ...  23389.1  0.000427   1539    3
1540  20230204   082000    082459  1675470299  ...  23408.2  0.000192   1540    4
1541  20230204   082500    082959  1675470599  ...  23417.7  0.000922   1541    5
1542  20230204   083000    083459  1675470899  ...  23435.6  0.000316   1542    0

[5 rows x 11 columns]
2023-02-04 08:35:00,685:INFO:factorcheck2:main.py:128:handleKline:185239: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': True, 'isOpenSell': False, 'isCloseBuy': False, 'isCloseSell': False, 'isOpen': True, 'isClose': False, 'isTrig': True}


## /root/FIL/strategy/logic/log.txt ----- -----

2023-02-04 08:30:33,315:DEBUG:logic:main.py:463:getModel:885513: df_s.iloc[-5:,:] :
          date closeTime     open  ...    alpha58   alpha67   alpha72
5771  20230204    055959  23367.9  ...  45.416667  0.475846  0.676758
5772  20230204    062959  23377.6  ...  45.833333  0.476880  0.674963
5773  20230204    065959  23382.7  ...  46.250000  0.483910  0.668856
5774  20230204    072959  23417.3  ...  46.666667  0.489389  0.659687
5775  20230204    075959  23444.1  ...  46.666667  0.485590  0.653634

[5 rows x 33 columns]
0.5175600739371534
acc is : 0.5175600739371534
2023-02-04 08:30:33,494:INFO:logic:main.py:468:getModel:885513: df_pred.iloc[-5:,:] :
     pred    prob_0    prob_1  actual  ...       nav  sign  cost_        bm
536     1  0.495470  0.504530       1  ...  0.935343  -1.0    0.0  1.013919
537     0  0.501468  0.498532       1  ...  0.933963  -1.0    0.0  1.015415
538     0  0.505577  0.494423       1  ...  0.932886  -1.0    0.0  1.016586
539     0  0.508507  0.491493       0  ...  0.933662  -1.0    0.0  1.015740
540     1  0.496962  0.503038       1  ...  0.933076  -1.0    0.0  1.016378

[5 rows x 10 columns]
2023-02-04 08:30:33,527:INFO:logic:main.py:478:getModel:885513: df_panel.iloc[-5:,:] :
    pred    prob_0    prob_1  actual  ...       nav  sign  cost_        bm
45     1  0.496512  0.503488       1  ...  0.935343  -1.0    0.0  1.025139
46     0  0.501784  0.498216       1  ...  0.933963  -1.0    0.0  1.022148
47     0  0.506676  0.493324       1  ...  0.932886  -1.0    0.0  1.023523
48     0  0.509901  0.490099       0  ...  0.933662  -1.0    0.0  1.022672
49     1  0.496962  0.503038       1  ...  0.933076  -1.0    0.0  1.016378

[5 rows x 10 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '30.907', 'enterprice': '23688.5', 'countrevence': '0', 'unrealprofit': '7706.07716506018', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '23439.16887226', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}


## /root/FIL/strategy/modifiedmom/log.txt ----- -----

624  20230204   080000    080959  1675469399  23424.7  23410.4 -0.000610
2023-02-04 08:10:01,563:INFO:modifiedmom:main.py:146:handleKline:185213: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': True, 'isOpen': False, 'isClose': True, 'isTrig': False}
127.0.0.1 - - [04/Feb/2023 08:20:00] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=10185 

self.closeSec=1675469999, self.tradeDate='20230204', self.openTime='081000', self.closeTime='081959', self.symbol='BTCUSDT', self.open='23410.4', self.close='23413.3'
2023-02-04 08:20:00,662:INFO:modifiedmom:main.py:144:handleKline:185213: self.closeSec=1675469999, self.tradeDate='20230204', self.openTime='081000', self.closeTime='081959',self.symbol='BTCUSDT',self.open='23410.4', self.close='23413.3'
2023-02-04 08:20:00,710:INFO:modifiedmom:main.py:145:handleKline:185213: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec     open    close       pct
621  20230204   073000    073959  1675467599  23444.1  23442.5 -0.000068
622  20230204   074000    074959  1675468199  23442.4  23438.2 -0.000183
623  20230204   075000    075959  1675468799  23438.2  23424.7 -0.000576
624  20230204   080000    080959  1675469399  23424.7  23410.4 -0.000610
625  20230204   081000    081959  1675469999  23410.4  23413.3  0.000124
2023-02-04 08:20:00,710:INFO:modifiedmom:main.py:146:handleKline:185213: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': True, 'isOpen': False, 'isClose': True, 'isTrig': False}
127.0.0.1 - - [04/Feb/2023 08:30:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=10186 

self.closeSec=1675470599, self.tradeDate='20230204', self.openTime='082000', self.closeTime='082959', self.symbol='BTCUSDT', self.open='23413.2', self.close='23439.4'
2023-02-04 08:30:01,224:INFO:modifiedmom:main.py:144:handleKline:185213: self.closeSec=1675470599, self.tradeDate='20230204', self.openTime='082000', self.closeTime='082959',self.symbol='BTCUSDT',self.open='23413.2', self.close='23439.4'
2023-02-04 08:30:01,263:INFO:modifiedmom:main.py:145:handleKline:185213: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec     open    close       pct
622  20230204   074000    074959  1675468199  23442.4  23438.2 -0.000183
623  20230204   075000    075959  1675468799  23438.2  23424.7 -0.000576
624  20230204   080000    080959  1675469399  23424.7  23410.4 -0.000610
625  20230204   081000    081959  1675469999  23410.4  23413.3  0.000124
626  20230204   082000    082959  1675470599  23413.2  23439.4  0.001115
2023-02-04 08:30:01,268:INFO:modifiedmom:main.py:146:handleKline:185213: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': True, 'isOpen': False, 'isClose': True, 'isTrig': False}


## /root/FIL/strategy/pyemd/log.txt ----- -----

17472  20230204   080000    080959  1675469399  23424.7  23410.4
2023-02-04 08:10:01,569:INFO:pyemd2:main.py:127:handleKline:185189: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=10186 

self.closeSec=1675469999, self.tradeDate='20230204', self.openTime='081000', self.closeTime='081959', self.symbol='BTCUSDT', self.open='23410.4', self.close='23413.3'
2023-02-04 08:20:00,638:INFO:pyemd2:main.py:125:handleKline:185189: self.closeSec=1675469999, self.tradeDate='20230204', self.openTime='081000', self.closeTime='081959',self.symbol='BTCUSDT',self.open='23410.4', self.close='23413.3'
127.0.0.1 - - [04/Feb/2023 08:20:00] "POST / HTTP/1.1" 200 -
2023-02-04 08:20:00,707:INFO:pyemd2:main.py:126:handleKline:185189: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
17469  20230204   073000    073959  1675467599  23444.1  23442.5
17470  20230204   074000    074959  1675468199  23442.4  23438.2
17471  20230204   075000    075959  1675468799  23438.2  23424.7
17472  20230204   080000    080959  1675469399  23424.7  23410.4
17473  20230204   081000    081959  1675469999  23410.4  23413.3
2023-02-04 08:20:00,708:INFO:pyemd2:main.py:127:handleKline:185189: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}
127.0.0.1 - - [04/Feb/2023 08:30:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=10187 

self.closeSec=1675470599, self.tradeDate='20230204', self.openTime='082000', self.closeTime='082959', self.symbol='BTCUSDT', self.open='23413.2', self.close='23439.4'
2023-02-04 08:30:01,229:INFO:pyemd2:main.py:125:handleKline:185189: self.closeSec=1675470599, self.tradeDate='20230204', self.openTime='082000', self.closeTime='082959',self.symbol='BTCUSDT',self.open='23413.2', self.close='23439.4'
2023-02-04 08:30:01,255:INFO:pyemd2:main.py:126:handleKline:185189: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
17470  20230204   074000    074959  1675468199  23442.4  23438.2
17471  20230204   075000    075959  1675468799  23438.2  23424.7
17472  20230204   080000    080959  1675469399  23424.7  23410.4
17473  20230204   081000    081959  1675469999  23410.4  23413.3
17474  20230204   082000    082959  1675470599  23413.2  23439.4
2023-02-04 08:30:01,255:INFO:pyemd2:main.py:127:handleKline:185189: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}


## /root/FIL/strategy/similarity/log.txt ----- -----

12144  20230204   080000    080959  1675469399  23424.7  23410.4
2023-02-04 08:10:01,566:INFO:testStrategy:main.py:103:handleKline:185174: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': True, 'isOpenSell': False, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True, 'isCorr': False}

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=10186 

self.closeSec=1675469999, self.tradeDate='20230204', self.openTime='081000', self.closeTime='081959', self.symbol='BTCUSDT', self.open='23410.4', self.close='23413.3'
2023-02-04 08:20:00,661:INFO:testStrategy:main.py:101:handleKline:185174: self.closeSec=1675469999, self.tradeDate='20230204', self.openTime='081000', self.closeTime='081959',self.symbol='BTCUSDT',self.open='23410.4', self.close='23413.3'
127.0.0.1 - - [04/Feb/2023 08:20:00] "POST / HTTP/1.1" 200 -
2023-02-04 08:20:00,691:INFO:testStrategy:main.py:102:handleKline:185174: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
12141  20230204   073000    073959  1675467599  23444.1  23442.5
12142  20230204   074000    074959  1675468199  23442.4  23438.2
12143  20230204   075000    075959  1675468799  23438.2  23424.7
12144  20230204   080000    080959  1675469399  23424.7  23410.4
12145  20230204   081000    081959  1675469999  23410.4  23413.3
2023-02-04 08:20:00,691:INFO:testStrategy:main.py:103:handleKline:185174: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': True, 'isOpenSell': False, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True, 'isCorr': False}

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=10187 

self.closeSec=1675470599, self.tradeDate='20230204', self.openTime='082000', self.closeTime='082959', self.symbol='BTCUSDT', self.open='23413.2', self.close='23439.4'
2023-02-04 08:30:01,222:INFO:testStrategy:main.py:101:handleKline:185174: self.closeSec=1675470599, self.tradeDate='20230204', self.openTime='082000', self.closeTime='082959',self.symbol='BTCUSDT',self.open='23413.2', self.close='23439.4'
127.0.0.1 - - [04/Feb/2023 08:30:01] "POST / HTTP/1.1" 200 -
2023-02-04 08:30:01,243:INFO:testStrategy:main.py:102:handleKline:185174: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
12142  20230204   074000    074959  1675468199  23442.4  23438.2
12143  20230204   075000    075959  1675468799  23438.2  23424.7
12144  20230204   080000    080959  1675469399  23424.7  23410.4
12145  20230204   081000    081959  1675469999  23410.4  23413.3
12146  20230204   082000    082959  1675470599  23413.2  23439.4
2023-02-04 08:30:01,243:INFO:testStrategy:main.py:103:handleKline:185174: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': True, 'isOpenSell': False, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True, 'isCorr': False}


## /root/FIL/strategy/sr_min/log.txt ----- -----

--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=0, self.total=1000000.0, self.flagDict['side']='', self.tradeCount=0, self.count=15804
self.closeSec=1675470599, self.tradeDate='20230204', self.openTime='082500', self.closeTime='082959', self.symbol='BTCUSDT', self.open=23417.7, self.close=23439.4, self.high=23439.4, self.low=23417.7, self.vol=503.438, self.amt=11794814.3533 
127.0.0.1 - - [04/Feb/2023 08:30:00] "POST / HTTP/1.1" 200 -
2023-02-04 08:30:00,946:INFO:sr_min:main.py:172:handleKline:449472: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5857  20230204   080500    080959  ...         0.0        0.0       0
5858  20230204   081000    081459  ...         0.0        0.0       0
5859  20230204   081500    081959  ...         0.0        0.0       0
5860  20230204   082000    082459  ...         0.0        0.0       0
5861  20230204   082500    082959  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-02-04 08:30:00,948:INFO:sr_min:main.py:175:handleKline:449472: self.closeSec=1675470599, self.tradeDate='20230204', self.openTime='082500', self.closeTime='082959',self.symbol='BTCUSDT',self.open=23417.7, self.close=23439.4, self.high=23439.4, self.low=23417.7, self.vol=503.438, self.amt=11794814.3533, ukdf['pct'].iloc[-1]=0.000922 , ukdf['amount'].iloc[-1]=11794814.3533, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5861, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': []}
type(curSign)=<class 'int'>, curSign=0, self.sign=0
127.0.0.1 - - [04/Feb/2023 08:35:00] "POST / HTTP/1.1" 200 -
--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=0, self.total=1000000.0, self.flagDict['side']='', self.tradeCount=0, self.count=15805
self.closeSec=1675470899, self.tradeDate='20230204', self.openTime='083000', self.closeTime='083459', self.symbol='BTCUSDT', self.open=23439.3, self.close=23446.8, self.high=23446.8, self.low=23435.6, self.vol=551.481, self.amt=12927567.6083 
2023-02-04 08:35:00,740:INFO:sr_min:main.py:172:handleKline:449472: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5858  20230204   081000    081459  ...         0.0        0.0       0
5859  20230204   081500    081959  ...         0.0        0.0       0
5860  20230204   082000    082459  ...         0.0        0.0       0
5861  20230204   082500    082959  ...         0.0        0.0       0
5862  20230204   083000    083459  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-02-04 08:35:00,740:INFO:sr_min:main.py:175:handleKline:449472: self.closeSec=1675470899, self.tradeDate='20230204', self.openTime='083000', self.closeTime='083459',self.symbol='BTCUSDT',self.open=23439.3, self.close=23446.8, self.high=23446.8, self.low=23435.6, self.vol=551.481, self.amt=12927567.6083, ukdf['pct'].iloc[-1]=0.000316 , ukdf['amount'].iloc[-1]=12927567.6083, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5862, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': []}
type(curSign)=<class 'int'>, curSign=0, self.sign=0


## /root/FIL/strategy/s_rsrs/log.txt ----- -----

719  20230203   200000    235959  1675439999  ...    719  0.735980  0.650313     1.0
720  20230204   000000    035959  1675454399  ...    720  0.744472  0.659472     1.0

[5 rows x 15 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '38.964', 'enterprice': '23700.1', 'countrevence': '0', 'unrealprofit': '-15590.75763623628', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '23299.96763073', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'numpy.int64'>, curSign=1, self.sign=1
127.0.0.1 - - [04/Feb/2023 08:00:02] "POST / HTTP/1.1" 200 -
--handleKline--:  version='2.0.0', self.name='s_rsrs', self.symbol='BTCUSDT', interval='4h', intervalSec=14400, wid=25, thd=0.6, self.sign=1, self.total=922527.2457035999, self.flagDict['side']='buy', self.tradeCount=16, self.count=424
self.closeSec=1675468799, self.tradeDate='20230204', self.openTime='040000', self.closeTime='075959', self.symbol='BTCUSDT', self.open=23308.2, self.close=23424.7, self.high=23465.4, self.low=23201.0, self.vol=51798.392, self.amt=1209501718.34468 
2023-02-04 08:00:02,117:INFO:s_rsrs:main.py:141:handleKline:185271: self.closeSec=1675468799, self.tradeDate='20230204', self.openTime='040000', self.closeTime='075959',self.symbol='BTCUSDT',self.open=23308.2, self.close=23424.7, self.high=23465.4, self.low=23201.0, self.vol=51798.392, self.amt=1209501718.34468 
2023-02-04 08:00:02,166:INFO:s_rsrs:main.py:142:handleKline:185271: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime  ...         vol           amt       pct
717  20230203   120000    155959  ...   25571.080  6.012727e+08 -0.003306
718  20230203   160000    195959  ...   57784.896  1.353723e+09  0.003231
719  20230203   200000    235959  ...  189870.022  4.455432e+09  0.002898
720  20230204   000000    035959  ...   91933.801  2.160911e+09 -0.012410
721  20230204   040000    075959  ...   51798.392  1.209502e+09  0.004998

[5 rows x 11 columns]
2023-02-04 08:00:03,979:INFO:s_rsrs:main.py:151:handleKline:185271: df_s.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec  ...  index      beta    zscore  signal
717  20230203   120000    155959  1675411199  ...    717  0.675625  0.497663     NaN
718  20230203   160000    195959  1675425599  ...    718  0.691835  0.532151     NaN
719  20230203   200000    235959  1675439999  ...    719  0.735980  0.650313     1.0
720  20230204   000000    035959  1675454399  ...    720  0.744472  0.659472     1.0
721  20230204   040000    075959  1675468799  ...    721  0.846087  0.951234     1.0

[5 rows x 15 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '38.964', 'enterprice': '23700.1', 'countrevence': '0', 'unrealprofit': '-10666.7461903248', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '23426.3409868', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'numpy.int64'>, curSign=1, self.sign=1


