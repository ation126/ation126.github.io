# 20230203 08:35:49

## /root/FIL/strategy/amihud/log.txt ----- -----

--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=993672.4896432, self.flagDict['side']='sell', self.tradeCount=2, self.count=19518
self.closeSec=1675384199, self.tradeDate='20230203', self.openTime='082500', self.closeTime='082959', self.symbol='BTCUSDT', self.open=23564.2, self.close=23561.8, self.high=23564.3, self.low=23548.5, self.vol=542.474, self.amt=12778806.3529 
127.0.0.1 - - [03/Feb/2023 08:30:00] "POST / HTTP/1.1" 200 -
2023-02-03 08:30:01,018:INFO:amihud:main.py:172:handleKline:200676: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5857  20230203   080500    080959  ...         0.0        0.0       0
5858  20230203   081000    081459  ...         0.0        0.0       0
5859  20230203   081500    081959  ...         0.0        0.0       0
5860  20230203   082000    082459  ...         0.0        0.0       0
5861  20230203   082500    082959  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-02-03 08:30:01,019:INFO:amihud:main.py:175:handleKline:200676: self.closeSec=1675384199, self.tradeDate='20230203', self.openTime='082500', self.closeTime='082959',self.symbol='BTCUSDT',self.open=23564.2, self.close=23561.8, self.high=23564.3, self.low=23548.5, self.vol=542.474, self.amt=12778806.3529, ukdf['pct'].iloc[-1]=-0.000106 , ukdf['amount'].iloc[-1]=12778806.3529, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5861, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '60.176', 'enterprice': '16529.3', 'countrevence': '0', 'unrealprofit': '-423176.7611320064', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '23561.6178864', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1
--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=993672.4896432, self.flagDict['side']='sell', self.tradeCount=2, self.count=19519
self.closeSec=1675384499, self.tradeDate='20230203', self.openTime='083000', self.closeTime='083459', self.symbol='BTCUSDT', self.open=23561.8, self.close=23500.1, self.high=23561.9, self.low=23494.1, self.vol=1704.4, self.amt=40089612.6052 
127.0.0.1 - - [03/Feb/2023 08:35:00] "POST / HTTP/1.1" 200 -
2023-02-03 08:35:00,575:INFO:amihud:main.py:172:handleKline:200676: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5858  20230203   081000    081459  ...         0.0        0.0       0
5859  20230203   081500    081959  ...         0.0        0.0       0
5860  20230203   082000    082459  ...         0.0        0.0       0
5861  20230203   082500    082959  ...         0.0        0.0       0
5862  20230203   083000    083459  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-02-03 08:35:00,579:INFO:amihud:main.py:175:handleKline:200676: self.closeSec=1675384499, self.tradeDate='20230203', self.openTime='083000', self.closeTime='083459',self.symbol='BTCUSDT',self.open=23561.8, self.close=23500.1, self.high=23561.9, self.low=23494.1, self.vol=1704.4, self.amt=40089612.6052, ukdf['pct'].iloc[-1]=-0.002619 , ukdf['amount'].iloc[-1]=40089612.6052, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5862, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '60.176', 'enterprice': '16529.3', 'countrevence': '0', 'unrealprofit': '-419410.00244466224', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '23499.02218899', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1


## /root/FIL/strategy/factorcheck/log.txt ----- -----

1540  20230203   082000    082459  1675383899  ...  23556.7  0.000323   1540    4
1541  20230203   082500    082959  1675384199  ...  23548.5 -0.000106   1541    5

[5 rows x 11 columns]
2023-02-03 08:30:00,983:INFO:factorcheck2:main.py:128:handleKline:185239: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}
2023-02-03 08:30:01,051:INFO:factorcheck2:main.py:145:handleKline:185239: df_panel.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec  ...       pct  index  idx    factor
213  20230203   062500    062959  1675376999  ... -0.002608   1517    5  0.413080
214  20230203   065500    065959  1675378799  ... -0.000628   1523    5  0.422241
215  20230203   072500    072959  1675380599  ... -0.000999   1529    5  0.433523
216  20230203   075500    075959  1675382399  ...  0.000319   1535    5  0.444492
217  20230203   082500    082959  1675384199  ... -0.000106   1541    5  0.452770

[5 rows x 12 columns]
127.0.0.1 - - [03/Feb/2023 08:35:00] "POST / HTTP/1.1" 200 -

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=67, self.factor=0.45276981856568, self.count=20085 

self.closeSec=1675384499, self.tradeDate='20230203', self.openTime='083000', self.closeTime='083459', self.symbol='BTCUSDT', self.open=23561.8, self.close=23500.1, self.high=23561.9, self.low=23494.1 
2023-02-03 08:35:00,429:INFO:factorcheck2:main.py:126:handleKline:185239: self.closeSec=1675384499, self.tradeDate='20230203', self.openTime='083000', self.closeTime='083459',self.symbol='BTCUSDT',self.open=23561.8, self.close=23500.1, self.high=23561.9, self.low=23494.1   
2023-02-03 08:35:00,521:INFO:factorcheck2:main.py:127:handleKline:185239: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime    closeSec  ...      low       pct  index  idx
1538  20230203   081000    081459  1675383299  ...  23558.6  0.000119   1538    2
1539  20230203   081500    081959  1675383599  ...  23555.0 -0.000772   1539    3
1540  20230203   082000    082459  1675383899  ...  23556.7  0.000323   1540    4
1541  20230203   082500    082959  1675384199  ...  23548.5 -0.000106   1541    5
1542  20230203   083000    083459  1675384499  ...  23494.1 -0.002619   1542    0

[5 rows x 11 columns]
2023-02-03 08:35:00,527:INFO:factorcheck2:main.py:128:handleKline:185239: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}


## /root/FIL/strategy/logic/log.txt ----- -----

2023-02-03 08:30:33,896:DEBUG:logic:main.py:463:getModel:885513: df_s.iloc[-5:,:] :
          date closeTime     open  ...    alpha58   alpha67   alpha72
5771  20230203    055959  23759.3  ...  48.333333  0.484908  0.470438
5772  20230203    062959  23456.2  ...  48.750000  0.495451  0.492213
5773  20230203    065959  23524.0  ...  49.166667  0.500795  0.509569
5774  20230203    072959  23559.1  ...  48.750000  0.490512  0.531525
5775  20230203    075959  23491.4  ...  48.750000  0.490796  0.551863

[5 rows x 33 columns]
0.532347504621072
acc is : 0.532347504621072
2023-02-03 08:30:34,064:INFO:logic:main.py:468:getModel:885513: df_pred.iloc[-5:,:] :
     pred    prob_0    prob_1  actual  ...       nav  sign  cost_        bm
536     1  0.399724  0.600276       1  ...  0.924035  -1.0    0.0  1.026164
537     1  0.467989  0.532011       1  ...  0.922665  -1.0    0.0  1.027687
538     1  0.466903  0.533097       0  ...  0.925316  -1.0    0.0  1.024734
539     1  0.439326  0.560674       1  ...  0.925245  -1.0    0.0  1.024812
540     1  0.458386  0.541614       1  ...  0.922539  -1.0    0.0  1.027809

[5 rows x 10 columns]
2023-02-03 08:30:34,086:INFO:logic:main.py:478:getModel:885513: df_panel.iloc[-5:,:] :
    pred    prob_0    prob_1  actual  ...       nav  sign  cost_        bm
45     1  0.401094  0.598906       1  ...  0.924035  -1.0    0.0  1.030552
46     1  0.470224  0.529776       1  ...  0.922665  -1.0    0.0  1.032637
47     1  0.468120  0.531880       0  ...  0.925316  -1.0    0.0  1.026628
48     1  0.440306  0.559694       1  ...  0.925245  -1.0    0.0  1.026707
49     1  0.458386  0.541614       1  ...  0.922539  -1.0    0.0  1.027809

[5 rows x 10 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '30.907', 'enterprice': '23688.5', 'countrevence': '0', 'unrealprofit': '4107.5403', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '23555.6', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}


## /root/FIL/strategy/modifiedmom/log.txt ----- -----

624  20230203   080000    080959  1675382999    23493  23572.1  0.003363
2023-02-03 08:10:01,517:INFO:modifiedmom:main.py:146:handleKline:185213: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': True, 'isOpen': False, 'isClose': True, 'isTrig': False}
127.0.0.1 - - [03/Feb/2023 08:20:00] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=10041 

self.closeSec=1675383599, self.tradeDate='20230203', self.openTime='081000', self.closeTime='081959', self.symbol='BTCUSDT', self.open='23570.7', self.close='23556.7'
2023-02-03 08:20:00,721:INFO:modifiedmom:main.py:144:handleKline:185213: self.closeSec=1675383599, self.tradeDate='20230203', self.openTime='081000', self.closeTime='081959',self.symbol='BTCUSDT',self.open='23570.7', self.close='23556.7'
2023-02-03 08:20:00,739:INFO:modifiedmom:main.py:145:handleKline:185213: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec     open    close       pct
621  20230203   073000    073959  1675381199  23491.4    23500  0.000370
622  20230203   074000    074959  1675381799    23500  23492.7 -0.000311
623  20230203   075000    075959  1675382399  23492.6  23493.1  0.000017
624  20230203   080000    080959  1675382999    23493  23572.1  0.003363
625  20230203   081000    081959  1675383599  23570.7  23556.7 -0.000653
2023-02-03 08:20:00,739:INFO:modifiedmom:main.py:146:handleKline:185213: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': True, 'isOpen': False, 'isClose': True, 'isTrig': False}

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=10042 

self.closeSec=1675384199, self.tradeDate='20230203', self.openTime='082000', self.closeTime='082959', self.symbol='BTCUSDT', self.open='23556.7', self.close='23561.8'
2023-02-03 08:30:01,152:INFO:modifiedmom:main.py:144:handleKline:185213: self.closeSec=1675384199, self.tradeDate='20230203', self.openTime='082000', self.closeTime='082959',self.symbol='BTCUSDT',self.open='23556.7', self.close='23561.8'
127.0.0.1 - - [03/Feb/2023 08:30:01] "POST / HTTP/1.1" 200 -
2023-02-03 08:30:01,176:INFO:modifiedmom:main.py:145:handleKline:185213: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec     open    close       pct
622  20230203   074000    074959  1675381799    23500  23492.7 -0.000311
623  20230203   075000    075959  1675382399  23492.6  23493.1  0.000017
624  20230203   080000    080959  1675382999    23493  23572.1  0.003363
625  20230203   081000    081959  1675383599  23570.7  23556.7 -0.000653
626  20230203   082000    082959  1675384199  23556.7  23561.8  0.000216
2023-02-03 08:30:01,181:INFO:modifiedmom:main.py:146:handleKline:185213: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': True, 'isOpen': False, 'isClose': True, 'isTrig': False}


## /root/FIL/strategy/pyemd/log.txt ----- -----

17472  20230203   080000    080959  1675382999    23493  23572.1
2023-02-03 08:10:01,535:INFO:pyemd2:main.py:127:handleKline:185189: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=10042 

self.closeSec=1675383599, self.tradeDate='20230203', self.openTime='081000', self.closeTime='081959', self.symbol='BTCUSDT', self.open='23570.7', self.close='23556.7'
2023-02-03 08:20:00,707:INFO:pyemd2:main.py:125:handleKline:185189: self.closeSec=1675383599, self.tradeDate='20230203', self.openTime='081000', self.closeTime='081959',self.symbol='BTCUSDT',self.open='23570.7', self.close='23556.7'
127.0.0.1 - - [03/Feb/2023 08:20:00] "POST / HTTP/1.1" 200 -
2023-02-03 08:20:00,741:INFO:pyemd2:main.py:126:handleKline:185189: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
17469  20230203   073000    073959  1675381199  23491.4    23500
17470  20230203   074000    074959  1675381799    23500  23492.7
17471  20230203   075000    075959  1675382399  23492.6  23493.1
17472  20230203   080000    080959  1675382999    23493  23572.1
17473  20230203   081000    081959  1675383599  23570.7  23556.7
2023-02-03 08:20:00,742:INFO:pyemd2:main.py:127:handleKline:185189: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}
127.0.0.1 - - [03/Feb/2023 08:30:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=10043 

self.closeSec=1675384199, self.tradeDate='20230203', self.openTime='082000', self.closeTime='082959', self.symbol='BTCUSDT', self.open='23556.7', self.close='23561.8'
2023-02-03 08:30:01,142:INFO:pyemd2:main.py:125:handleKline:185189: self.closeSec=1675384199, self.tradeDate='20230203', self.openTime='082000', self.closeTime='082959',self.symbol='BTCUSDT',self.open='23556.7', self.close='23561.8'
2023-02-03 08:30:01,187:INFO:pyemd2:main.py:126:handleKline:185189: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
17470  20230203   074000    074959  1675381799    23500  23492.7
17471  20230203   075000    075959  1675382399  23492.6  23493.1
17472  20230203   080000    080959  1675382999    23493  23572.1
17473  20230203   081000    081959  1675383599  23570.7  23556.7
17474  20230203   082000    082959  1675384199  23556.7  23561.8
2023-02-03 08:30:01,187:INFO:pyemd2:main.py:127:handleKline:185189: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}


## /root/FIL/strategy/similarity/log.txt ----- -----

12144  20230203   080000    080959  1675382999    23493  23572.1
2023-02-03 08:10:01,542:INFO:testStrategy:main.py:103:handleKline:185174: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': True, 'isOpenSell': False, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True, 'isCorr': False}

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=10042 

self.closeSec=1675383599, self.tradeDate='20230203', self.openTime='081000', self.closeTime='081959', self.symbol='BTCUSDT', self.open='23570.7', self.close='23556.7'
2023-02-03 08:20:00,724:INFO:testStrategy:main.py:101:handleKline:185174: self.closeSec=1675383599, self.tradeDate='20230203', self.openTime='081000', self.closeTime='081959',self.symbol='BTCUSDT',self.open='23570.7', self.close='23556.7'
127.0.0.1 - - [03/Feb/2023 08:20:00] "POST / HTTP/1.1" 200 -
2023-02-03 08:20:00,746:INFO:testStrategy:main.py:102:handleKline:185174: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
12141  20230203   073000    073959  1675381199  23491.4    23500
12142  20230203   074000    074959  1675381799    23500  23492.7
12143  20230203   075000    075959  1675382399  23492.6  23493.1
12144  20230203   080000    080959  1675382999    23493  23572.1
12145  20230203   081000    081959  1675383599  23570.7  23556.7
2023-02-03 08:20:00,746:INFO:testStrategy:main.py:103:handleKline:185174: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': True, 'isOpenSell': False, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True, 'isCorr': False}

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=10043 

self.closeSec=1675384199, self.tradeDate='20230203', self.openTime='082000', self.closeTime='082959', self.symbol='BTCUSDT', self.open='23556.7', self.close='23561.8'
2023-02-03 08:30:01,162:INFO:testStrategy:main.py:101:handleKline:185174: self.closeSec=1675384199, self.tradeDate='20230203', self.openTime='082000', self.closeTime='082959',self.symbol='BTCUSDT',self.open='23556.7', self.close='23561.8'
2023-02-03 08:30:01,168:INFO:testStrategy:main.py:102:handleKline:185174: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
12142  20230203   074000    074959  1675381799    23500  23492.7
12143  20230203   075000    075959  1675382399  23492.6  23493.1
12144  20230203   080000    080959  1675382999    23493  23572.1
12145  20230203   081000    081959  1675383599  23570.7  23556.7
12146  20230203   082000    082959  1675384199  23556.7  23561.8
2023-02-03 08:30:01,168:INFO:testStrategy:main.py:103:handleKline:185174: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': True, 'isOpenSell': False, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True, 'isCorr': False}
127.0.0.1 - - [03/Feb/2023 08:30:01] "POST / HTTP/1.1" 200 -


## /root/FIL/strategy/sr_min/log.txt ----- -----

127.0.0.1 - - [03/Feb/2023 08:30:00] "POST / HTTP/1.1" 200 -
--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=0, self.total=1000000.0, self.flagDict['side']='', self.tradeCount=0, self.count=15516
self.closeSec=1675384199, self.tradeDate='20230203', self.openTime='082500', self.closeTime='082959', self.symbol='BTCUSDT', self.open=23564.2, self.close=23561.8, self.high=23564.3, self.low=23548.5, self.vol=542.474, self.amt=12778806.3529 
2023-02-03 08:30:01,025:INFO:sr_min:main.py:172:handleKline:449472: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5857  20230203   080500    080959  ...         0.0        0.0       0
5858  20230203   081000    081459  ...         0.0        0.0       0
5859  20230203   081500    081959  ...         0.0        0.0       0
5860  20230203   082000    082459  ...         0.0        0.0       0
5861  20230203   082500    082959  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-02-03 08:30:01,026:INFO:sr_min:main.py:175:handleKline:449472: self.closeSec=1675384199, self.tradeDate='20230203', self.openTime='082500', self.closeTime='082959',self.symbol='BTCUSDT',self.open=23564.2, self.close=23561.8, self.high=23564.3, self.low=23548.5, self.vol=542.474, self.amt=12778806.3529, ukdf['pct'].iloc[-1]=-0.000106 , ukdf['amount'].iloc[-1]=12778806.3529, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5861, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': []}
type(curSign)=<class 'int'>, curSign=0, self.sign=0
127.0.0.1 - - [03/Feb/2023 08:35:00] "POST / HTTP/1.1" 200 -
--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=0, self.total=1000000.0, self.flagDict['side']='', self.tradeCount=0, self.count=15517
self.closeSec=1675384499, self.tradeDate='20230203', self.openTime='083000', self.closeTime='083459', self.symbol='BTCUSDT', self.open=23561.8, self.close=23500.1, self.high=23561.9, self.low=23494.1, self.vol=1704.4, self.amt=40089612.6052 
2023-02-03 08:35:00,578:INFO:sr_min:main.py:172:handleKline:449472: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5858  20230203   081000    081459  ...         0.0        0.0       0
5859  20230203   081500    081959  ...         0.0        0.0       0
5860  20230203   082000    082459  ...         0.0        0.0       0
5861  20230203   082500    082959  ...         0.0        0.0       0
5862  20230203   083000    083459  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-02-03 08:35:00,578:INFO:sr_min:main.py:175:handleKline:449472: self.closeSec=1675384499, self.tradeDate='20230203', self.openTime='083000', self.closeTime='083459',self.symbol='BTCUSDT',self.open=23561.8, self.close=23500.1, self.high=23561.9, self.low=23494.1, self.vol=1704.4, self.amt=40089612.6052, ukdf['pct'].iloc[-1]=-0.002619 , ukdf['amount'].iloc[-1]=40089612.6052, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5862, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': []}
type(curSign)=<class 'int'>, curSign=0, self.sign=0


## /root/FIL/strategy/s_rsrs/log.txt ----- -----

719  20230202   200000    235959  1675353599  ...    719  0.692199  0.611737     1.0
720  20230203   000000    035959  1675367999  ...    720  0.734255  0.721104     1.0

[5 rows x 15 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '38.964', 'enterprice': '23700.1', 'countrevence': '0', 'unrealprofit': '4020.12901580748', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '23803.27547007', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'numpy.int64'>, curSign=1, self.sign=1
127.0.0.1 - - [03/Feb/2023 08:00:01] "POST / HTTP/1.1" 200 -
--handleKline--:  version='2.0.0', self.name='s_rsrs', self.symbol='BTCUSDT', interval='4h', intervalSec=14400, wid=25, thd=0.6, self.sign=1, self.total=922527.2457035999, self.flagDict['side']='buy', self.tradeCount=16, self.count=418
self.closeSec=1675382399, self.tradeDate='20230203', self.openTime='040000', self.closeTime='075959', self.symbol='BTCUSDT', self.open=23804.8, self.close=23493.1, self.high=23933.5, self.low=23365.0, self.vol=111289.486, self.amt=2630096416.557 
2023-02-03 08:00:01,964:INFO:s_rsrs:main.py:141:handleKline:185271: self.closeSec=1675382399, self.tradeDate='20230203', self.openTime='040000', self.closeTime='075959',self.symbol='BTCUSDT',self.open=23804.8, self.close=23493.1, self.high=23933.5, self.low=23365.0, self.vol=111289.486, self.amt=2630096416.557 
2023-02-03 08:00:02,014:INFO:s_rsrs:main.py:142:handleKline:185271: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime  ...         vol           amt       pct
717  20230202   120000    155959  ...   48942.495  1.165257e+09 -0.002734
718  20230202   160000    195959  ...   34286.886  8.163629e+08  0.001682
719  20230202   200000    235959  ...  152792.644  3.629087e+09  0.000684
720  20230203   000000    035959  ...  131578.698  3.146825e+09 -0.001611
721  20230203   040000    075959  ...  111289.486  2.630096e+09 -0.013098

[5 rows x 11 columns]
2023-02-03 08:00:03,800:INFO:s_rsrs:main.py:151:handleKline:185271: df_s.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec  ...  index      beta    zscore  signal
717  20230202   120000    155959  1675324799  ...    717  0.707133  0.686136     1.0
718  20230202   160000    195959  1675339199  ...    718  0.662503  0.537956     NaN
719  20230202   200000    235959  1675353599  ...    719  0.692199  0.611737     1.0
720  20230203   000000    035959  1675367999  ...    720  0.734255  0.721104     1.0
721  20230203   040000    075959  1675382399  ...    721  0.727334  0.683564     1.0

[5 rows x 15 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '38.964', 'enterprice': '23700.1', 'countrevence': '0', 'unrealprofit': '-6544.59203288412', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '23532.13490317', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'numpy.int64'>, curSign=1, self.sign=1


