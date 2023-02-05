# 20230205 08:35:52

## /root/FIL/strategy/amihud/log.txt ----- -----

127.0.0.1 - - [05/Feb/2023 08:30:00] "POST / HTTP/1.1" 200 -
--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=993672.4896432, self.flagDict['side']='sell', self.tradeCount=2, self.count=20094
self.closeSec=1675556999, self.tradeDate='20230205', self.openTime='082500', self.closeTime='082959', self.symbol='BTCUSDT', self.open=23286.3, self.close=23313.2, self.high=23316.1, self.low=23280.5, self.vol=844.469, self.amt=19674454.9288 
2023-02-05 08:30:00,989:INFO:amihud:main.py:172:handleKline:200676: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5857  20230205   080500    080959  ...         0.0        0.0       0
5858  20230205   081000    081459  ...         0.0        0.0       0
5859  20230205   081500    081959  ...         0.0        0.0       0
5860  20230205   082000    082459  ...         0.0        0.0       0
5861  20230205   082500    082959  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-02-05 08:30:00,989:INFO:amihud:main.py:175:handleKline:200676: self.closeSec=1675556999, self.tradeDate='20230205', self.openTime='082500', self.closeTime='082959',self.symbol='BTCUSDT',self.open=23286.3, self.close=23313.2, self.high=23316.1, self.low=23280.5, self.vol=844.469, self.amt=19674454.9288, ukdf['pct'].iloc[-1]=0.001159 , ukdf['amount'].iloc[-1]=19674454.9288, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5861, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '60.176', 'enterprice': '16529.3', 'countrevence': '0', 'unrealprofit': '-408227.9664', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '23313.2', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1
127.0.0.1 - - [05/Feb/2023 08:35:00] "POST / HTTP/1.1" 200 -
--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=993672.4896432, self.flagDict['side']='sell', self.tradeCount=2, self.count=20095
self.closeSec=1675557299, self.tradeDate='20230205', self.openTime='083000', self.closeTime='083459', self.symbol='BTCUSDT', self.open=23313.2, self.close=23292.6, self.high=23313.2, self.low=23288.5, self.vol=620.843, self.amt=14463885.662 
2023-02-05 08:35:00,732:INFO:amihud:main.py:172:handleKline:200676: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5858  20230205   081000    081459  ...         0.0        0.0       0
5859  20230205   081500    081959  ...         0.0        0.0       0
5860  20230205   082000    082459  ...         0.0        0.0       0
5861  20230205   082500    082959  ...         0.0        0.0       0
5862  20230205   083000    083459  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-02-05 08:35:00,732:INFO:amihud:main.py:175:handleKline:200676: self.closeSec=1675557299, self.tradeDate='20230205', self.openTime='083000', self.closeTime='083459',self.symbol='BTCUSDT',self.open=23313.2, self.close=23292.6, self.high=23313.2, self.low=23288.5, self.vol=620.843, self.amt=14463885.662, ukdf['pct'].iloc[-1]=-0.000884 , ukdf['amount'].iloc[-1]=14463885.662, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5862, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '60.176', 'enterprice': '16529.3', 'countrevence': '0', 'unrealprofit': '-407015.311938948', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '23293.04820425', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1


## /root/FIL/strategy/factorcheck/log.txt ----- -----

1540  20230205   082000    082459  1675556699  ...  23282.4 -0.001997   1540    4
1541  20230205   082500    082959  1675556999  ...  23280.5  0.001159   1541    5

[5 rows x 11 columns]
2023-02-05 08:30:00,945:INFO:factorcheck2:main.py:128:handleKline:185239: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': True, 'isOpenSell': False, 'isCloseBuy': False, 'isCloseSell': False, 'isOpen': True, 'isClose': False, 'isTrig': True}
2023-02-05 08:30:00,992:INFO:factorcheck2:main.py:145:handleKline:185239: df_panel.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec  ...       pct  index  idx    factor
213  20230205   062500    062959  1675549799  ...  0.000128   1517    5  0.584426
214  20230205   065500    065959  1675551599  ... -0.001191   1523    5  0.582782
215  20230205   072500    072959  1675553399  ... -0.000047   1529    5  0.579766
216  20230205   075500    075959  1675555199  ...  0.000523   1535    5  0.585115
217  20230205   082500    082959  1675556999  ...  0.001159   1541    5  0.591150

[5 rows x 12 columns]

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=10, self.factor=0.5911501822257221, self.count=20661 

self.closeSec=1675557299, self.tradeDate='20230205', self.openTime='083000', self.closeTime='083459', self.symbol='BTCUSDT', self.open=23313.2, self.close=23292.6, self.high=23313.2, self.low=23288.5 
2023-02-05 08:35:00,639:INFO:factorcheck2:main.py:126:handleKline:185239: self.closeSec=1675557299, self.tradeDate='20230205', self.openTime='083000', self.closeTime='083459',self.symbol='BTCUSDT',self.open=23313.2, self.close=23292.6, self.high=23313.2, self.low=23288.5   
127.0.0.1 - - [05/Feb/2023 08:35:00] "POST / HTTP/1.1" 200 -
2023-02-05 08:35:00,670:INFO:factorcheck2:main.py:127:handleKline:185239: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime    closeSec  ...      low       pct  index  idx
1538  20230205   081000    081459  1675556099  ...  23320.6 -0.000728   1538    2
1539  20230205   081500    081959  1675556399  ...  23286.0 -0.000099   1539    3
1540  20230205   082000    082459  1675556699  ...  23282.4 -0.001997   1540    4
1541  20230205   082500    082959  1675556999  ...  23280.5  0.001159   1541    5
1542  20230205   083000    083459  1675557299  ...  23288.5 -0.000884   1542    0

[5 rows x 11 columns]
2023-02-05 08:35:00,670:INFO:factorcheck2:main.py:128:handleKline:185239: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': True, 'isOpenSell': False, 'isCloseBuy': False, 'isCloseSell': False, 'isOpen': True, 'isClose': False, 'isTrig': True}


## /root/FIL/strategy/logic/log.txt ----- -----

2023-02-05 08:30:32,329:DEBUG:logic:main.py:463:getModel:885513: df_s.iloc[-5:,:] :
          date closeTime     open  ...    alpha58   alpha67   alpha72
5771  20230205    055959  23406.6  ...  46.250000  0.493578  0.533677
5772  20230205    062959  23414.7  ...  46.250000  0.493078  0.532935
5773  20230205    065959  23413.1  ...  45.833333  0.489414  0.534509
5774  20230205    072959  23401.4  ...  45.833333  0.494764  0.532813
5775  20230205    075959  23417.6  ...  45.416667  0.465570  0.549782

[5 rows x 33 columns]
0.5249537892791127
acc is : 0.5249537892791127
2023-02-05 08:30:32,499:INFO:logic:main.py:468:getModel:885513: df_pred.iloc[-5:,:] :
     pred    prob_0    prob_1  actual  ...       nav  sign  cost_        bm
536     1  0.496716  0.503284       0  ...  0.992752  -1.0    0.0  1.022138
537     1  0.496315  0.503685       0  ...  0.993244  -1.0    0.0  1.021632
538     1  0.491937  0.508063       1  ...  0.992557  -1.0    0.0  1.022339
539     1  0.499449  0.500551       0  ...  0.996583  -1.0    0.0  1.018192
540     1  0.472893  0.527107       0  ...  0.996985  -1.0    0.0  1.017781

[5 rows x 10 columns]
2023-02-05 08:30:32,536:INFO:logic:main.py:478:getModel:885513: df_panel.iloc[-5:,:] :
    pred    prob_0    prob_1  actual  ...       nav  sign  cost_        bm
45     1  0.497873  0.502127       0  ...  0.992752  -1.0    0.0  1.020686
46     1  0.498297  0.501703       0  ...  0.993244  -1.0    0.0  1.023240
47     1  0.493048  0.506952       1  ...  0.992557  -1.0    0.0  1.022620
48     0  0.500568  0.499432       0  ...  0.996583  -1.0    0.0  1.018472
49     1  0.472893  0.527107       0  ...  0.996985  -1.0    0.0  1.017781

[5 rows x 10 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '30.907', 'enterprice': '23688.5', 'countrevence': '0', 'unrealprofit': '11945.5555', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '23302', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}


## /root/FIL/strategy/modifiedmom/log.txt ----- -----

624  20230205   080000    080959  1675555799  23322.6  23352.1  0.001265
2023-02-05 08:10:01,528:INFO:modifiedmom:main.py:146:handleKline:185213: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': True, 'isOpen': False, 'isClose': True, 'isTrig': False}
127.0.0.1 - - [05/Feb/2023 08:20:00] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=10329 

self.closeSec=1675556399, self.tradeDate='20230205', self.openTime='081000', self.closeTime='081959', self.symbol='BTCUSDT', self.open='23352.2', self.close='23332.8'
2023-02-05 08:20:00,545:INFO:modifiedmom:main.py:144:handleKline:185213: self.closeSec=1675556399, self.tradeDate='20230205', self.openTime='081000', self.closeTime='081959',self.symbol='BTCUSDT',self.open='23352.2', self.close='23332.8'
2023-02-05 08:20:00,581:INFO:modifiedmom:main.py:145:handleKline:185213: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec     open    close       pct
621  20230205   073000    073959  1675553999  23417.6  23346.7 -0.003028
622  20230205   074000    074959  1675554599  23346.8  23290.8 -0.002394
623  20230205   075000    075959  1675555199    23288  23322.6  0.001365
624  20230205   080000    080959  1675555799  23322.6  23352.1  0.001265
625  20230205   081000    081959  1675556399  23352.2  23332.8 -0.000826
2023-02-05 08:20:00,581:INFO:modifiedmom:main.py:146:handleKline:185213: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': True, 'isOpen': False, 'isClose': True, 'isTrig': False}
127.0.0.1 - - [05/Feb/2023 08:30:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=10330 

self.closeSec=1675556999, self.tradeDate='20230205', self.openTime='082000', self.closeTime='082959', self.symbol='BTCUSDT', self.open='23332.8', self.close='23313.2'
2023-02-05 08:30:01,137:INFO:modifiedmom:main.py:144:handleKline:185213: self.closeSec=1675556999, self.tradeDate='20230205', self.openTime='082000', self.closeTime='082959',self.symbol='BTCUSDT',self.open='23332.8', self.close='23313.2'
2023-02-05 08:30:01,201:INFO:modifiedmom:main.py:145:handleKline:185213: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec     open    close       pct
622  20230205   074000    074959  1675554599  23346.8  23290.8 -0.002394
623  20230205   075000    075959  1675555199    23288  23322.6  0.001365
624  20230205   080000    080959  1675555799  23322.6  23352.1  0.001265
625  20230205   081000    081959  1675556399  23352.2  23332.8 -0.000826
626  20230205   082000    082959  1675556999  23332.8  23313.2 -0.000840
2023-02-05 08:30:01,201:INFO:modifiedmom:main.py:146:handleKline:185213: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': True, 'isOpen': False, 'isClose': True, 'isTrig': False}


## /root/FIL/strategy/pyemd/log.txt ----- -----

17472  20230205   080000    080959  1675555799  23322.6  23352.1
2023-02-05 08:10:01,592:INFO:pyemd2:main.py:127:handleKline:185189: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}
127.0.0.1 - - [05/Feb/2023 08:20:00] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=10330 

self.closeSec=1675556399, self.tradeDate='20230205', self.openTime='081000', self.closeTime='081959', self.symbol='BTCUSDT', self.open='23352.2', self.close='23332.8'
2023-02-05 08:20:00,557:INFO:pyemd2:main.py:125:handleKline:185189: self.closeSec=1675556399, self.tradeDate='20230205', self.openTime='081000', self.closeTime='081959',self.symbol='BTCUSDT',self.open='23352.2', self.close='23332.8'
2023-02-05 08:20:00,587:INFO:pyemd2:main.py:126:handleKline:185189: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
17469  20230205   073000    073959  1675553999  23417.6  23346.7
17470  20230205   074000    074959  1675554599  23346.8  23290.8
17471  20230205   075000    075959  1675555199    23288  23322.6
17472  20230205   080000    080959  1675555799  23322.6  23352.1
17473  20230205   081000    081959  1675556399  23352.2  23332.8
2023-02-05 08:20:00,587:INFO:pyemd2:main.py:127:handleKline:185189: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=10331 

self.closeSec=1675556999, self.tradeDate='20230205', self.openTime='082000', self.closeTime='082959', self.symbol='BTCUSDT', self.open='23332.8', self.close='23313.2'
2023-02-05 08:30:01,113:INFO:pyemd2:main.py:125:handleKline:185189: self.closeSec=1675556999, self.tradeDate='20230205', self.openTime='082000', self.closeTime='082959',self.symbol='BTCUSDT',self.open='23332.8', self.close='23313.2'
127.0.0.1 - - [05/Feb/2023 08:30:01] "POST / HTTP/1.1" 200 -
2023-02-05 08:30:01,136:INFO:pyemd2:main.py:126:handleKline:185189: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
17470  20230205   074000    074959  1675554599  23346.8  23290.8
17471  20230205   075000    075959  1675555199    23288  23322.6
17472  20230205   080000    080959  1675555799  23322.6  23352.1
17473  20230205   081000    081959  1675556399  23352.2  23332.8
17474  20230205   082000    082959  1675556999  23332.8  23313.2
2023-02-05 08:30:01,136:INFO:pyemd2:main.py:127:handleKline:185189: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}


## /root/FIL/strategy/similarity/log.txt ----- -----

12144  20230205   080000    080959  1675555799  23322.6  23352.1
2023-02-05 08:10:01,589:INFO:testStrategy:main.py:103:handleKline:185174: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': True, 'isOpenSell': False, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True, 'isCorr': False}
127.0.0.1 - - [05/Feb/2023 08:20:00] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=10330 

self.closeSec=1675556399, self.tradeDate='20230205', self.openTime='081000', self.closeTime='081959', self.symbol='BTCUSDT', self.open='23352.2', self.close='23332.8'
2023-02-05 08:20:00,549:INFO:testStrategy:main.py:101:handleKline:185174: self.closeSec=1675556399, self.tradeDate='20230205', self.openTime='081000', self.closeTime='081959',self.symbol='BTCUSDT',self.open='23352.2', self.close='23332.8'
2023-02-05 08:20:00,600:INFO:testStrategy:main.py:102:handleKline:185174: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
12141  20230205   073000    073959  1675553999  23417.6  23346.7
12142  20230205   074000    074959  1675554599  23346.8  23290.8
12143  20230205   075000    075959  1675555199    23288  23322.6
12144  20230205   080000    080959  1675555799  23322.6  23352.1
12145  20230205   081000    081959  1675556399  23352.2  23332.8
2023-02-05 08:20:00,603:INFO:testStrategy:main.py:103:handleKline:185174: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': True, 'isOpenSell': False, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True, 'isCorr': False}
127.0.0.1 - - [05/Feb/2023 08:30:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=10331 

self.closeSec=1675556999, self.tradeDate='20230205', self.openTime='082000', self.closeTime='082959', self.symbol='BTCUSDT', self.open='23332.8', self.close='23313.2'
2023-02-05 08:30:01,154:INFO:testStrategy:main.py:101:handleKline:185174: self.closeSec=1675556999, self.tradeDate='20230205', self.openTime='082000', self.closeTime='082959',self.symbol='BTCUSDT',self.open='23332.8', self.close='23313.2'
2023-02-05 08:30:01,205:INFO:testStrategy:main.py:102:handleKline:185174: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
12142  20230205   074000    074959  1675554599  23346.8  23290.8
12143  20230205   075000    075959  1675555199    23288  23322.6
12144  20230205   080000    080959  1675555799  23322.6  23352.1
12145  20230205   081000    081959  1675556399  23352.2  23332.8
12146  20230205   082000    082959  1675556999  23332.8  23313.2
2023-02-05 08:30:01,206:INFO:testStrategy:main.py:103:handleKline:185174: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': True, 'isOpenSell': False, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True, 'isCorr': False}


## /root/FIL/strategy/sr_min/log.txt ----- -----

--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=0, self.total=1000000.0, self.flagDict['side']='', self.tradeCount=0, self.count=16092
self.closeSec=1675556999, self.tradeDate='20230205', self.openTime='082500', self.closeTime='082959', self.symbol='BTCUSDT', self.open=23286.3, self.close=23313.2, self.high=23316.1, self.low=23280.5, self.vol=844.469, self.amt=19674454.9288 
127.0.0.1 - - [05/Feb/2023 08:30:00] "POST / HTTP/1.1" 200 -
2023-02-05 08:30:00,991:INFO:sr_min:main.py:172:handleKline:449472: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5857  20230205   080500    080959  ...         0.0        0.0       0
5858  20230205   081000    081459  ...         0.0        0.0       0
5859  20230205   081500    081959  ...         0.0        0.0       0
5860  20230205   082000    082459  ...         0.0        0.0       0
5861  20230205   082500    082959  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-02-05 08:30:00,993:INFO:sr_min:main.py:175:handleKline:449472: self.closeSec=1675556999, self.tradeDate='20230205', self.openTime='082500', self.closeTime='082959',self.symbol='BTCUSDT',self.open=23286.3, self.close=23313.2, self.high=23316.1, self.low=23280.5, self.vol=844.469, self.amt=19674454.9288, ukdf['pct'].iloc[-1]=0.001159 , ukdf['amount'].iloc[-1]=19674454.9288, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5861, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': []}
type(curSign)=<class 'int'>, curSign=0, self.sign=0
127.0.0.1 - - [05/Feb/2023 08:35:00] "POST / HTTP/1.1" 200 -
--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=0, self.total=1000000.0, self.flagDict['side']='', self.tradeCount=0, self.count=16093
self.closeSec=1675557299, self.tradeDate='20230205', self.openTime='083000', self.closeTime='083459', self.symbol='BTCUSDT', self.open=23313.2, self.close=23292.6, self.high=23313.2, self.low=23288.5, self.vol=620.843, self.amt=14463885.662 
2023-02-05 08:35:00,683:INFO:sr_min:main.py:172:handleKline:449472: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5858  20230205   081000    081459  ...         0.0        0.0       0
5859  20230205   081500    081959  ...         0.0        0.0       0
5860  20230205   082000    082459  ...         0.0        0.0       0
5861  20230205   082500    082959  ...         0.0        0.0       0
5862  20230205   083000    083459  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-02-05 08:35:00,684:INFO:sr_min:main.py:175:handleKline:449472: self.closeSec=1675557299, self.tradeDate='20230205', self.openTime='083000', self.closeTime='083459',self.symbol='BTCUSDT',self.open=23313.2, self.close=23292.6, self.high=23313.2, self.low=23288.5, self.vol=620.843, self.amt=14463885.662, ukdf['pct'].iloc[-1]=-0.000884 , ukdf['amount'].iloc[-1]=14463885.662, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5862, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': []}
type(curSign)=<class 'int'>, curSign=0, self.sign=0


## /root/FIL/strategy/s_rsrs/log.txt ----- -----

719  20230204   200000    235959  1675526399  ...    719  0.606331  0.137386     NaN
720  20230205   000000    035959  1675540799  ...    720  0.578135  0.034442     NaN

[5 rows x 15 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '38.964', 'enterprice': '23700.1', 'countrevence': '0', 'unrealprofit': '-10629.3792', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '23427.3', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'numpy.int64'>, curSign=-9223372036854775808, self.sign=1
127.0.0.1 - - [05/Feb/2023 08:00:02] "POST / HTTP/1.1" 200 -
--handleKline--:  version='2.0.0', self.name='s_rsrs', self.symbol='BTCUSDT', interval='4h', intervalSec=14400, wid=25, thd=0.6, self.sign=1, self.total=922527.2457035999, self.flagDict['side']='buy', self.tradeCount=16, self.count=430
self.closeSec=1675555199, self.tradeDate='20230205', self.openTime='040000', self.closeTime='075959', self.symbol='BTCUSDT', self.open=23427.4, self.close=23322.6, self.high=23450.0, self.low=23258.0, self.vol=27115.818, self.amt=633530709.5999 
2023-02-05 08:00:02,265:INFO:s_rsrs:main.py:141:handleKline:185271: self.closeSec=1675555199, self.tradeDate='20230205', self.openTime='040000', self.closeTime='075959',self.symbol='BTCUSDT',self.open=23427.4, self.close=23322.6, self.high=23450.0, self.low=23258.0, self.vol=27115.818, self.amt=633530709.5999 
2023-02-05 08:00:02,309:INFO:s_rsrs:main.py:142:handleKline:185271: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime  ...        vol           amt       pct
717  20230204   120000    155959  ...  28301.188  6.598631e+08 -0.000788
718  20230204   160000    195959  ...  19759.758  4.610801e+08  0.001578
719  20230204   200000    235959  ...  70032.864  1.643729e+09  0.002607
720  20230205   000000    035959  ...  25724.048  6.025431e+08  0.000307
721  20230205   040000    075959  ...  27115.818  6.335307e+08 -0.004469

[5 rows x 11 columns]
2023-02-05 08:00:04,315:INFO:s_rsrs:main.py:151:handleKline:185271: df_s.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec  ...  index      beta    zscore  signal
717  20230204   120000    155959  1675497599  ...    717  0.743165  0.596458     NaN
718  20230204   160000    195959  1675511999  ...    718  0.675291  0.369137     NaN
719  20230204   200000    235959  1675526399  ...    719  0.606331  0.137386     NaN
720  20230205   000000    035959  1675540799  ...    720  0.578135  0.034442     NaN
721  20230205   040000    075959  1675555199  ...    721  0.548186 -0.055113     NaN

[5 rows x 15 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '38.964', 'enterprice': '23700.1', 'countrevence': '0', 'unrealprofit': '-14708.91', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '23322.6', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'numpy.int64'>, curSign=-9223372036854775808, self.sign=1


