# 20230208 08:36:01

## /root/FIL/strategy/amihud/log.txt ----- -----

127.0.0.1 - - [08/Feb/2023 08:30:00] "POST / HTTP/1.1" 200 -
--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=993672.4896432, self.flagDict['side']='sell', self.tradeCount=2, self.count=20958
self.closeSec=1675816199, self.tradeDate='20230208', self.openTime='082500', self.closeTime='082959', self.symbol='BTCUSDT', self.open=23261.6, self.close=23247.8, self.high=23265.7, self.low=23246.3, self.vol=536.682, self.amt=12481666.9468 
2023-02-08 08:30:00,575:INFO:amihud:main.py:172:handleKline:200676: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5857  20230208   080500    080959  ...         0.0        0.0       0
5858  20230208   081000    081459  ...         0.0        0.0       0
5859  20230208   081500    081959  ...         0.0        0.0       0
5860  20230208   082000    082459  ...         0.0        0.0       0
5861  20230208   082500    082959  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-02-08 08:30:00,577:INFO:amihud:main.py:175:handleKline:200676: self.closeSec=1675816199, self.tradeDate='20230208', self.openTime='082500', self.closeTime='082959',self.symbol='BTCUSDT',self.open=23261.6, self.close=23247.8, self.high=23265.7, self.low=23246.3, self.vol=536.682, self.amt=12481666.9468, ukdf['pct'].iloc[-1]=-0.000598 , ukdf['amount'].iloc[-1]=12481666.9468, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5861, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '60.176', 'enterprice': '16529.3', 'countrevence': '0', 'unrealprofit': '-404346.6144', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '23248.7', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1
--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=993672.4896432, self.flagDict['side']='sell', self.tradeCount=2, self.count=20959
self.closeSec=1675816499, self.tradeDate='20230208', self.openTime='083000', self.closeTime='083459', self.symbol='BTCUSDT', self.open=23248.7, self.close=23238.4, self.high=23251.0, self.low=23226.2, self.vol=582.943, self.amt=13544912.524 
127.0.0.1 - - [08/Feb/2023 08:35:00] "POST / HTTP/1.1" 200 -
2023-02-08 08:35:00,527:INFO:amihud:main.py:172:handleKline:200676: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5858  20230208   081000    081459  ...         0.0        0.0       0
5859  20230208   081500    081959  ...         0.0        0.0       0
5860  20230208   082000    082459  ...         0.0        0.0       0
5861  20230208   082500    082959  ...         0.0        0.0       0
5862  20230208   083000    083459  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-02-08 08:35:00,527:INFO:amihud:main.py:175:handleKline:200676: self.closeSec=1675816499, self.tradeDate='20230208', self.openTime='083000', self.closeTime='083459',self.symbol='BTCUSDT',self.open=23248.7, self.close=23238.4, self.high=23251.0, self.low=23226.2, self.vol=582.943, self.amt=13544912.524, ukdf['pct'].iloc[-1]=-0.000404 , ukdf['amount'].iloc[-1]=13544912.524, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5862, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '60.176', 'enterprice': '16529.3', 'countrevence': '0', 'unrealprofit': '-403730.12366301728', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '23238.45520578', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1


## /root/FIL/strategy/factorcheck/log.txt ----- -----

1540  20230208   082000    082459  1675815899  ...  23228.6  0.001429   1540    4
1541  20230208   082500    082959  1675816199  ...  23246.3 -0.000598   1541    5

[5 rows x 11 columns]
2023-02-08 08:30:00,567:INFO:factorcheck2:main.py:128:handleKline:185239: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}
2023-02-08 08:30:00,688:INFO:factorcheck2:main.py:145:handleKline:185239: df_panel.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec  ...       pct  index  idx    factor
213  20230208   062500    062959  1675808999  ...  0.000488   1517    5  0.428567
214  20230208   065500    065959  1675810799  ... -0.000284   1523    5  0.422603
215  20230208   072500    072959  1675812599  ... -0.000382   1529    5  0.414948
216  20230208   075500    075959  1675814399  ... -0.000890   1535    5  0.408810
217  20230208   082500    082959  1675816199  ... -0.000598   1541    5  0.402298

[5 rows x 12 columns]

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=15, self.factor=0.40229781031154754, self.count=21525 

self.closeSec=1675816499, self.tradeDate='20230208', self.openTime='083000', self.closeTime='083459', self.symbol='BTCUSDT', self.open=23248.7, self.close=23238.4, self.high=23251.0, self.low=23226.2 
2023-02-08 08:35:00,446:INFO:factorcheck2:main.py:126:handleKline:185239: self.closeSec=1675816499, self.tradeDate='20230208', self.openTime='083000', self.closeTime='083459',self.symbol='BTCUSDT',self.open=23248.7, self.close=23238.4, self.high=23251.0, self.low=23226.2   
127.0.0.1 - - [08/Feb/2023 08:35:00] "POST / HTTP/1.1" 200 -
2023-02-08 08:35:00,538:INFO:factorcheck2:main.py:127:handleKline:185239: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime    closeSec  ...      low       pct  index  idx
1538  20230208   081000    081459  1675815299  ...  23222.6 -0.000318   1538    2
1539  20230208   081500    081959  1675815599  ...  23228.5 -0.000280   1539    3
1540  20230208   082000    082459  1675815899  ...  23228.6  0.001429   1540    4
1541  20230208   082500    082959  1675816199  ...  23246.3 -0.000598   1541    5
1542  20230208   083000    083459  1675816499  ...  23226.2 -0.000404   1542    0

[5 rows x 11 columns]
2023-02-08 08:35:00,538:INFO:factorcheck2:main.py:128:handleKline:185239: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}


## /root/FIL/strategy/logic/log.txt ----- -----

2023-02-08 08:30:32,021:DEBUG:logic:main.py:463:getModel:885513: df_s.iloc[-5:,:] :
          date closeTime     open  ...    alpha58   alpha67   alpha72
5771  20230208    055959  23232.2  ...  47.500000  0.535750  0.371070
5772  20230208    062959  23189.5  ...  47.083333  0.531177  0.368510
5773  20230208    065959  23166.9  ...  47.083333  0.541323  0.359758
5774  20230208    072959  23223.9  ...  47.500000  0.548351  0.347105
5775  20230208    075959  23265.6  ...  47.083333  0.542242  0.338527

[5 rows x 33 columns]
0.5027726432532348
acc is : 0.5027726432532348
2023-02-08 08:30:32,178:INFO:logic:main.py:468:getModel:885513: df_pred.iloc[-5:,:] :
     pred    prob_0    prob_1  actual  ...       nav  sign  cost_        bm
536     1  0.494792  0.505208       0  ...  0.966482  -1.0    0.0  0.998672
537     1  0.493254  0.506746       1  ...  0.964067  -1.0    0.0  1.001168
538     0  0.503037  0.496963       1  ...  0.962373  -1.0    0.0  1.002927
539     0  0.503619  0.496381       0  ...  0.963589  -1.0    0.0  1.001660
540     1  0.486333  0.513667       1  ...  0.963104  -1.0    0.0  1.002164

[5 rows x 10 columns]
2023-02-08 08:30:32,212:INFO:logic:main.py:478:getModel:885513: df_panel.iloc[-5:,:] :
    pred    prob_0    prob_1  actual  ...       nav  sign  cost_        bm
45     1  0.495709  0.504291       0  ...  0.966482  -1.0    0.0  1.003826
46     1  0.493445  0.506555       1  ...  0.964067  -1.0    0.0  1.004238
47     0  0.503804  0.496196       1  ...  0.962373  -1.0    0.0  1.006245
48     0  0.504617  0.495383       0  ...  0.963589  -1.0    0.0  1.004974
49     1  0.486333  0.513667       1  ...  0.963104  -1.0    0.0  1.002164

[5 rows x 10 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '32.252', 'enterprice': '22924.6', 'countrevence': '0', 'unrealprofit': '-10462.1995301912', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '23248.9891706', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}


## /root/FIL/strategy/modifiedmom/log.txt ----- -----

624  20230208   080000    080959  1675814999  23234.1  23242.4  0.000271
2023-02-08 08:10:01,577:INFO:modifiedmom:main.py:146:handleKline:185213: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': True, 'isOpen': False, 'isClose': True, 'isTrig': False}
127.0.0.1 - - [08/Feb/2023 08:20:00] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=10761 

self.closeSec=1675815599, self.tradeDate='20230208', self.openTime='081000', self.closeTime='081959', self.symbol='BTCUSDT', self.open='23242.4', self.close='23228.5'
2023-02-08 08:20:00,519:INFO:modifiedmom:main.py:144:handleKline:185213: self.closeSec=1675815599, self.tradeDate='20230208', self.openTime='081000', self.closeTime='081959',self.symbol='BTCUSDT',self.open='23242.4', self.close='23228.5'
2023-02-08 08:20:00,568:INFO:modifiedmom:main.py:145:handleKline:185213: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec     open    close       pct
621  20230208   073000    073959  1675813199  23265.6  23241.9 -0.001019
622  20230208   074000    074959  1675813799  23241.9  23265.1  0.000998
623  20230208   075000    075959  1675814399  23265.2  23236.1 -0.001247
624  20230208   080000    080959  1675814999  23234.1  23242.4  0.000271
625  20230208   081000    081959  1675815599  23242.4  23228.5 -0.000598
2023-02-08 08:20:00,568:INFO:modifiedmom:main.py:146:handleKline:185213: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': True, 'isOpen': False, 'isClose': True, 'isTrig': False}
127.0.0.1 - - [08/Feb/2023 08:30:00] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=10762 

self.closeSec=1675816199, self.tradeDate='20230208', self.openTime='082000', self.closeTime='082959', self.symbol='BTCUSDT', self.open='23228.6', self.close='23247.8'
2023-02-08 08:30:00,721:INFO:modifiedmom:main.py:144:handleKline:185213: self.closeSec=1675816199, self.tradeDate='20230208', self.openTime='082000', self.closeTime='082959',self.symbol='BTCUSDT',self.open='23228.6', self.close='23247.8'
2023-02-08 08:30:00,777:INFO:modifiedmom:main.py:145:handleKline:185213: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec     open    close       pct
622  20230208   074000    074959  1675813799  23241.9  23265.1  0.000998
623  20230208   075000    075959  1675814399  23265.2  23236.1 -0.001247
624  20230208   080000    080959  1675814999  23234.1  23242.4  0.000271
625  20230208   081000    081959  1675815599  23242.4  23228.5 -0.000598
626  20230208   082000    082959  1675816199  23228.6  23247.8  0.000831
2023-02-08 08:30:00,777:INFO:modifiedmom:main.py:146:handleKline:185213: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': True, 'isOpen': False, 'isClose': True, 'isTrig': False}


## /root/FIL/strategy/pyemd/log.txt ----- -----

17472  20230208   080000    080959  1675814999  23234.1  23242.4
2023-02-08 08:10:01,624:INFO:pyemd2:main.py:127:handleKline:185189: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}
127.0.0.1 - - [08/Feb/2023 08:20:00] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=10762 

self.closeSec=1675815599, self.tradeDate='20230208', self.openTime='081000', self.closeTime='081959', self.symbol='BTCUSDT', self.open='23242.4', self.close='23228.5'
2023-02-08 08:20:00,532:INFO:pyemd2:main.py:125:handleKline:185189: self.closeSec=1675815599, self.tradeDate='20230208', self.openTime='081000', self.closeTime='081959',self.symbol='BTCUSDT',self.open='23242.4', self.close='23228.5'
2023-02-08 08:20:00,577:INFO:pyemd2:main.py:126:handleKline:185189: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
17469  20230208   073000    073959  1675813199  23265.6  23241.9
17470  20230208   074000    074959  1675813799  23241.9  23265.1
17471  20230208   075000    075959  1675814399  23265.2  23236.1
17472  20230208   080000    080959  1675814999  23234.1  23242.4
17473  20230208   081000    081959  1675815599  23242.4  23228.5
2023-02-08 08:20:00,577:INFO:pyemd2:main.py:127:handleKline:185189: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=10763 

self.closeSec=1675816199, self.tradeDate='20230208', self.openTime='082000', self.closeTime='082959', self.symbol='BTCUSDT', self.open='23228.6', self.close='23247.8'
127.0.0.1 - - [08/Feb/2023 08:30:00] "POST / HTTP/1.1" 200 -
2023-02-08 08:30:00,711:INFO:pyemd2:main.py:125:handleKline:185189: self.closeSec=1675816199, self.tradeDate='20230208', self.openTime='082000', self.closeTime='082959',self.symbol='BTCUSDT',self.open='23228.6', self.close='23247.8'
2023-02-08 08:30:00,739:INFO:pyemd2:main.py:126:handleKline:185189: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
17470  20230208   074000    074959  1675813799  23241.9  23265.1
17471  20230208   075000    075959  1675814399  23265.2  23236.1
17472  20230208   080000    080959  1675814999  23234.1  23242.4
17473  20230208   081000    081959  1675815599  23242.4  23228.5
17474  20230208   082000    082959  1675816199  23228.6  23247.8
2023-02-08 08:30:00,739:INFO:pyemd2:main.py:127:handleKline:185189: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}


## /root/FIL/strategy/similarity/log.txt ----- -----

12144  20230208   080000    080959  1675814999  23234.1  23242.4
2023-02-08 08:10:01,611:INFO:testStrategy:main.py:103:handleKline:185174: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': True, 'isOpenSell': False, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True, 'isCorr': False}
127.0.0.1 - - [08/Feb/2023 08:20:00] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=10762 

self.closeSec=1675815599, self.tradeDate='20230208', self.openTime='081000', self.closeTime='081959', self.symbol='BTCUSDT', self.open='23242.4', self.close='23228.5'
2023-02-08 08:20:00,533:INFO:testStrategy:main.py:101:handleKline:185174: self.closeSec=1675815599, self.tradeDate='20230208', self.openTime='081000', self.closeTime='081959',self.symbol='BTCUSDT',self.open='23242.4', self.close='23228.5'
2023-02-08 08:20:00,572:INFO:testStrategy:main.py:102:handleKline:185174: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
12141  20230208   073000    073959  1675813199  23265.6  23241.9
12142  20230208   074000    074959  1675813799  23241.9  23265.1
12143  20230208   075000    075959  1675814399  23265.2  23236.1
12144  20230208   080000    080959  1675814999  23234.1  23242.4
12145  20230208   081000    081959  1675815599  23242.4  23228.5
2023-02-08 08:20:00,572:INFO:testStrategy:main.py:103:handleKline:185174: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': True, 'isOpenSell': False, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True, 'isCorr': False}
127.0.0.1 - - [08/Feb/2023 08:30:00] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=10763 

self.closeSec=1675816199, self.tradeDate='20230208', self.openTime='082000', self.closeTime='082959', self.symbol='BTCUSDT', self.open='23228.6', self.close='23247.8'
2023-02-08 08:30:00,735:INFO:testStrategy:main.py:101:handleKline:185174: self.closeSec=1675816199, self.tradeDate='20230208', self.openTime='082000', self.closeTime='082959',self.symbol='BTCUSDT',self.open='23228.6', self.close='23247.8'
2023-02-08 08:30:00,785:INFO:testStrategy:main.py:102:handleKline:185174: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
12142  20230208   074000    074959  1675813799  23241.9  23265.1
12143  20230208   075000    075959  1675814399  23265.2  23236.1
12144  20230208   080000    080959  1675814999  23234.1  23242.4
12145  20230208   081000    081959  1675815599  23242.4  23228.5
12146  20230208   082000    082959  1675816199  23228.6  23247.8
2023-02-08 08:30:00,785:INFO:testStrategy:main.py:103:handleKline:185174: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': True, 'isOpenSell': False, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True, 'isCorr': False}


## /root/FIL/strategy/sr_min/log.txt ----- -----

--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=0, self.total=1000000.0, self.flagDict['side']='', self.tradeCount=0, self.count=16956
self.closeSec=1675816199, self.tradeDate='20230208', self.openTime='082500', self.closeTime='082959', self.symbol='BTCUSDT', self.open=23261.6, self.close=23247.8, self.high=23265.7, self.low=23246.3, self.vol=536.682, self.amt=12481666.9468 
127.0.0.1 - - [08/Feb/2023 08:30:00] "POST / HTTP/1.1" 200 -
2023-02-08 08:30:00,554:INFO:sr_min:main.py:172:handleKline:449472: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5857  20230208   080500    080959  ...         0.0        0.0       0
5858  20230208   081000    081459  ...         0.0        0.0       0
5859  20230208   081500    081959  ...         0.0        0.0       0
5860  20230208   082000    082459  ...         0.0        0.0       0
5861  20230208   082500    082959  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-02-08 08:30:00,554:INFO:sr_min:main.py:175:handleKline:449472: self.closeSec=1675816199, self.tradeDate='20230208', self.openTime='082500', self.closeTime='082959',self.symbol='BTCUSDT',self.open=23261.6, self.close=23247.8, self.high=23265.7, self.low=23246.3, self.vol=536.682, self.amt=12481666.9468, ukdf['pct'].iloc[-1]=-0.000598 , ukdf['amount'].iloc[-1]=12481666.9468, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5861, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': []}
type(curSign)=<class 'int'>, curSign=0, self.sign=0
127.0.0.1 - - [08/Feb/2023 08:35:00] "POST / HTTP/1.1" 200 -
--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=0, self.total=1000000.0, self.flagDict['side']='', self.tradeCount=0, self.count=16957
self.closeSec=1675816499, self.tradeDate='20230208', self.openTime='083000', self.closeTime='083459', self.symbol='BTCUSDT', self.open=23248.7, self.close=23238.4, self.high=23251.0, self.low=23226.2, self.vol=582.943, self.amt=13544912.524 
2023-02-08 08:35:00,518:INFO:sr_min:main.py:172:handleKline:449472: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5858  20230208   081000    081459  ...         0.0        0.0       0
5859  20230208   081500    081959  ...         0.0        0.0       0
5860  20230208   082000    082459  ...         0.0        0.0       0
5861  20230208   082500    082959  ...         0.0        0.0       0
5862  20230208   083000    083459  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-02-08 08:35:00,519:INFO:sr_min:main.py:175:handleKline:449472: self.closeSec=1675816499, self.tradeDate='20230208', self.openTime='083000', self.closeTime='083459',self.symbol='BTCUSDT',self.open=23248.7, self.close=23238.4, self.high=23251.0, self.low=23226.2, self.vol=582.943, self.amt=13544912.524, ukdf['pct'].iloc[-1]=-0.000404 , ukdf['amount'].iloc[-1]=13544912.524, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5862, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': []}
type(curSign)=<class 'int'>, curSign=0, self.sign=0


## /root/FIL/strategy/s_rsrs/log.txt ----- -----

719  20230207   200000    235959  1675785599  ...    719  0.575800  0.331884     NaN
720  20230208   000000    035959  1675799999  ...    720  0.445139 -0.181049     NaN

[5 rows x 15 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '38.964', 'enterprice': '23700.1', 'countrevence': '0', 'unrealprofit': '-23775.8328', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '23089.9', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'numpy.int64'>, curSign=-9223372036854775808, self.sign=1
127.0.0.1 - - [08/Feb/2023 08:00:00] "POST / HTTP/1.1" 200 -
--handleKline--:  version='2.0.0', self.name='s_rsrs', self.symbol='BTCUSDT', interval='4h', intervalSec=14400, wid=25, thd=0.6, self.sign=1, self.total=922527.2457035999, self.flagDict['side']='buy', self.tradeCount=16, self.count=448
self.closeSec=1675814399, self.tradeDate='20230208', self.openTime='040000', self.closeTime='075959', self.symbol='BTCUSDT', self.open=23086.1, self.close=23236.1, self.high=23300.0, self.low=23024.3, self.vol=68836.763, self.amt=1596655517.06808 
2023-02-08 08:00:00,960:INFO:s_rsrs:main.py:141:handleKline:185271: self.closeSec=1675814399, self.tradeDate='20230208', self.openTime='040000', self.closeTime='075959',self.symbol='BTCUSDT',self.open=23086.1, self.close=23236.1, self.high=23300.0, self.low=23024.3, self.vol=68836.763, self.amt=1596655517.06808 
2023-02-08 08:00:00,999:INFO:s_rsrs:main.py:142:handleKline:185271: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime  ...         vol           amt       pct
717  20230207   120000    155959  ...   30655.972  7.023361e+08  0.001517
718  20230207   160000    195959  ...   48654.335  1.117097e+09  0.002829
719  20230207   200000    235959  ...   52655.269  1.208872e+09 -0.003117
720  20230208   000000    035959  ...  209737.864  4.833662e+09  0.008179
721  20230208   040000    075959  ...   68836.763  1.596656e+09  0.006497

[5 rows x 11 columns]
2023-02-08 08:00:03,167:INFO:s_rsrs:main.py:151:handleKline:185271: df_s.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec  ...  index      beta    zscore  signal
717  20230207   120000    155959  1675756799  ...    717  0.552062  0.189306     NaN
718  20230207   160000    195959  1675771199  ...    718  0.573397  0.297555     NaN
719  20230207   200000    235959  1675785599  ...    719  0.575800  0.331884     NaN
720  20230208   000000    035959  1675799999  ...    720  0.445139 -0.181049     NaN
721  20230208   040000    075959  1675814399  ...    721  0.400748 -0.347794     NaN

[5 rows x 15 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '38.964', 'enterprice': '23700.1', 'countrevence': '0', 'unrealprofit': '-18116.89711798728', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '23235.13497798', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'numpy.int64'>, curSign=-9223372036854775808, self.sign=1


