# 20230209 08:36:06

## /root/FIL/strategy/amihud/log.txt ----- -----

--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=993672.4896432, self.flagDict['side']='sell', self.tradeCount=2, self.count=21246
self.closeSec=1675902599, self.tradeDate='20230209', self.openTime='082500', self.closeTime='082959', self.symbol='BTCUSDT', self.open=22929.6, self.close=22981.5, self.high=22990.4, self.low=22921.8, self.vol=1422.403, self.amt=32664106.3762 
127.0.0.1 - - [09/Feb/2023 08:30:00] "POST / HTTP/1.1" 200 -
2023-02-09 08:30:00,826:INFO:amihud:main.py:172:handleKline:200676: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5857  20230209   080500    080959  ...         0.0        0.0       0
5858  20230209   081000    081459  ...         0.0        0.0       0
5859  20230209   081500    081959  ...         0.0        0.0       0
5860  20230209   082000    082459  ...         0.0        0.0       0
5861  20230209   082500    082959  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-02-09 08:30:00,828:INFO:amihud:main.py:175:handleKline:200676: self.closeSec=1675902599, self.tradeDate='20230209', self.openTime='082500', self.closeTime='082959',self.symbol='BTCUSDT',self.open=22929.6, self.close=22981.5, self.high=22990.4, self.low=22921.8, self.vol=1422.403, self.amt=32664106.3762, ukdf['pct'].iloc[-1]=0.002263 , ukdf['amount'].iloc[-1]=32664106.3762, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5861, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '60.176', 'enterprice': '16529.3', 'countrevence': '0', 'unrealprofit': '-388352.66806480432', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '22982.91386707', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1
--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=993672.4896432, self.flagDict['side']='sell', self.tradeCount=2, self.count=21247
self.closeSec=1675902899, self.tradeDate='20230209', self.openTime='083000', self.closeTime='083459', self.symbol='BTCUSDT', self.open=22981.1, self.close=22959.8, self.high=22981.1, self.low=22956.5, self.vol=730.282, self.amt=16775524.812 
127.0.0.1 - - [09/Feb/2023 08:35:00] "POST / HTTP/1.1" 200 -
2023-02-09 08:35:00,526:INFO:amihud:main.py:172:handleKline:200676: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5858  20230209   081000    081459  ...         0.0        0.0       0
5859  20230209   081500    081959  ...         0.0        0.0       0
5860  20230209   082000    082459  ...         0.0        0.0       0
5861  20230209   082500    082959  ...         0.0        0.0       0
5862  20230209   083000    083459  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-02-09 08:35:00,526:INFO:amihud:main.py:175:handleKline:200676: self.closeSec=1675902899, self.tradeDate='20230209', self.openTime='083000', self.closeTime='083459',self.symbol='BTCUSDT',self.open=22981.1, self.close=22959.8, self.high=22981.1, self.low=22956.5, self.vol=730.282, self.amt=16775524.812, ukdf['pct'].iloc[-1]=-0.000944 , ukdf['amount'].iloc[-1]=16775524.812, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5862, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '60.176', 'enterprice': '16529.3', 'countrevence': '0', 'unrealprofit': '-387083.28879724448', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '22961.81942298', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1


## /root/FIL/strategy/factorcheck/log.txt ----- -----

1540  20230209   082000    082459  1675902299  ...  22929.6 -0.000540   1540    4
1541  20230209   082500    082959  1675902599  ...  22921.8  0.002263   1541    5

[5 rows x 11 columns]
2023-02-09 08:30:00,762:INFO:factorcheck2:main.py:128:handleKline:185239: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}
2023-02-09 08:30:00,818:INFO:factorcheck2:main.py:145:handleKline:185239: df_panel.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec  ...       pct  index  idx    factor
213  20230209   062500    062959  1675895399  ... -0.000205   1517    5  0.443314
214  20230209   065500    065959  1675897199  ... -0.000031   1523    5  0.446542
215  20230209   072500    072959  1675898999  ... -0.000467   1529    5  0.450426
216  20230209   075500    075959  1675900799  ...  0.000593   1535    5  0.452115
217  20230209   082500    082959  1675902599  ...  0.002263   1541    5  0.452246

[5 rows x 12 columns]
127.0.0.1 - - [09/Feb/2023 08:35:00] "POST / HTTP/1.1" 200 -

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=63, self.factor=0.4522455276326451, self.count=21813 

self.closeSec=1675902899, self.tradeDate='20230209', self.openTime='083000', self.closeTime='083459', self.symbol='BTCUSDT', self.open=22981.1, self.close=22959.8, self.high=22981.1, self.low=22956.5 
2023-02-09 08:35:00,421:INFO:factorcheck2:main.py:126:handleKline:185239: self.closeSec=1675902899, self.tradeDate='20230209', self.openTime='083000', self.closeTime='083459',self.symbol='BTCUSDT',self.open=22981.1, self.close=22959.8, self.high=22981.1, self.low=22956.5   
2023-02-09 08:35:00,503:INFO:factorcheck2:main.py:127:handleKline:185239: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime    closeSec  ...      low       pct  index  idx
1538  20230209   081000    081459  1675901699  ...  22939.9 -0.001275   1538    2
1539  20230209   081500    081959  1675901999  ...  22933.9 -0.000144   1539    3
1540  20230209   082000    082459  1675902299  ...  22929.6 -0.000540   1540    4
1541  20230209   082500    082959  1675902599  ...  22921.8  0.002263   1541    5
1542  20230209   083000    083459  1675902899  ...  22956.5 -0.000944   1542    0

[5 rows x 11 columns]
2023-02-09 08:35:00,504:INFO:factorcheck2:main.py:128:handleKline:185239: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}


## /root/FIL/strategy/logic/log.txt ----- -----

2023-02-09 08:30:32,182:DEBUG:logic:main.py:463:getModel:885513: df_s.iloc[-5:,:] :
          date closeTime     open  ...    alpha58   alpha67   alpha72
5771  20230209    055959  22913.4  ...  47.083333  0.476738  0.597736
5772  20230209    062959  22948.2  ...  47.083333  0.477229  0.594024
5773  20230209    065959  22950.3  ...  46.666667  0.471046  0.593159
5774  20230209    072959  22923.0  ...  46.250000  0.467034  0.594264
5775  20230209    075959  22905.0  ...  46.666667  0.479957  0.589828

[5 rows x 33 columns]
0.4898336414048059
acc is : 0.4898336414048059
2023-02-09 08:30:32,337:INFO:logic:main.py:468:getModel:885513: df_pred.iloc[-5:,:] :
     pred    prob_0    prob_1  actual  ...       nav  sign  cost_        bm
536     1  0.497678  0.502322       1  ...  0.989516  -1.0    0.0  0.997284
537     1  0.490980  0.509020       0  ...  0.990697  -1.0    0.0  0.996093
538     1  0.483515  0.516485       0  ...  0.991467  -1.0    0.0  0.995320
539     1  0.486954  0.513046       1  ...  0.989263  -1.0    0.0  0.997532
540     0  0.501439  0.498561       1  ...  0.988169  -1.0    0.0  0.998636

[5 rows x 10 columns]
2023-02-09 08:30:32,371:INFO:logic:main.py:478:getModel:885513: df_panel.iloc[-5:,:] :
    pred    prob_0    prob_1  actual  ...       nav  sign  cost_        bm
45     1  0.496933  0.503067       1  ...  0.989516  -1.0    0.0  0.996782
46     1  0.490942  0.509058       0  ...  0.990697  -1.0    0.0  0.996228
47     1  0.484212  0.515788       0  ...  0.991467  -1.0    0.0  0.995896
48     1  0.487688  0.512312       1  ...  0.989263  -1.0    0.0  0.998109
49     0  0.501439  0.498561       1  ...  0.988169  -1.0    0.0  0.998636

[5 rows x 10 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '32.252', 'enterprice': '22924.6', 'countrevence': '0', 'unrealprofit': '-1563.15929692252', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '22973.06705001', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}


## /root/FIL/strategy/modifiedmom/log.txt ----- -----

624  20230209   080000    080959  1675901399  22955.9  22974.6  0.000810
2023-02-09 08:10:01,563:INFO:modifiedmom:main.py:146:handleKline:185213: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': True, 'isOpen': False, 'isClose': True, 'isTrig': False}
127.0.0.1 - - [09/Feb/2023 08:20:00] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=10905 

self.closeSec=1675901999, self.tradeDate='20230209', self.openTime='081000', self.closeTime='081959', self.symbol='BTCUSDT', self.open='22974.6', self.close='22942'
2023-02-09 08:20:00,555:INFO:modifiedmom:main.py:144:handleKline:185213: self.closeSec=1675901999, self.tradeDate='20230209', self.openTime='081000', self.closeTime='081959',self.symbol='BTCUSDT',self.open='22974.6', self.close='22942'
2023-02-09 08:20:00,582:INFO:modifiedmom:main.py:145:handleKline:185213: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec     open    close       pct
621  20230209   073000    073959  1675899599    22905    22943  0.001655
622  20230209   074000    074959  1675900199    22943  22932.8 -0.000445
623  20230209   075000    075959  1675900799  22932.6    22956  0.001012
624  20230209   080000    080959  1675901399  22955.9  22974.6  0.000810
625  20230209   081000    081959  1675901999  22974.6    22942 -0.001419
2023-02-09 08:20:00,582:INFO:modifiedmom:main.py:146:handleKline:185213: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': True, 'isOpen': False, 'isClose': True, 'isTrig': False}

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=10906 

self.closeSec=1675902599, self.tradeDate='20230209', self.openTime='082000', self.closeTime='082959', self.symbol='BTCUSDT', self.open='22942', self.close='22981.4'
127.0.0.1 - - [09/Feb/2023 08:30:00] "POST / HTTP/1.1" 200 -
2023-02-09 08:30:00,909:INFO:modifiedmom:main.py:144:handleKline:185213: self.closeSec=1675902599, self.tradeDate='20230209', self.openTime='082000', self.closeTime='082959',self.symbol='BTCUSDT',self.open='22942', self.close='22981.4'
2023-02-09 08:30:00,978:INFO:modifiedmom:main.py:145:handleKline:185213: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec     open    close       pct
622  20230209   074000    074959  1675900199    22943  22932.8 -0.000445
623  20230209   075000    075959  1675900799  22932.6    22956  0.001012
624  20230209   080000    080959  1675901399  22955.9  22974.6  0.000810
625  20230209   081000    081959  1675901999  22974.6    22942 -0.001419
626  20230209   082000    082959  1675902599    22942  22981.4  0.001717
2023-02-09 08:30:00,978:INFO:modifiedmom:main.py:146:handleKline:185213: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': True, 'isOpen': False, 'isClose': True, 'isTrig': False}


## /root/FIL/strategy/pyemd/log.txt ----- -----

17472  20230209   080000    080959  1675901399  22955.9  22974.6
2023-02-09 08:10:01,547:INFO:pyemd2:main.py:127:handleKline:185189: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=10906 

self.closeSec=1675901999, self.tradeDate='20230209', self.openTime='081000', self.closeTime='081959', self.symbol='BTCUSDT', self.open='22974.6', self.close='22942'
2023-02-09 08:20:00,524:INFO:pyemd2:main.py:125:handleKline:185189: self.closeSec=1675901999, self.tradeDate='20230209', self.openTime='081000', self.closeTime='081959',self.symbol='BTCUSDT',self.open='22974.6', self.close='22942'
127.0.0.1 - - [09/Feb/2023 08:20:00] "POST / HTTP/1.1" 200 -
2023-02-09 08:20:00,555:INFO:pyemd2:main.py:126:handleKline:185189: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
17469  20230209   073000    073959  1675899599    22905    22943
17470  20230209   074000    074959  1675900199    22943  22932.8
17471  20230209   075000    075959  1675900799  22932.6    22956
17472  20230209   080000    080959  1675901399  22955.9  22974.6
17473  20230209   081000    081959  1675901999  22974.6    22942
2023-02-09 08:20:00,555:INFO:pyemd2:main.py:127:handleKline:185189: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}
127.0.0.1 - - [09/Feb/2023 08:30:00] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=10907 

self.closeSec=1675902599, self.tradeDate='20230209', self.openTime='082000', self.closeTime='082959', self.symbol='BTCUSDT', self.open='22942', self.close='22981.4'
2023-02-09 08:30:00,953:INFO:pyemd2:main.py:125:handleKline:185189: self.closeSec=1675902599, self.tradeDate='20230209', self.openTime='082000', self.closeTime='082959',self.symbol='BTCUSDT',self.open='22942', self.close='22981.4'
2023-02-09 08:30:00,985:INFO:pyemd2:main.py:126:handleKline:185189: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
17470  20230209   074000    074959  1675900199    22943  22932.8
17471  20230209   075000    075959  1675900799  22932.6    22956
17472  20230209   080000    080959  1675901399  22955.9  22974.6
17473  20230209   081000    081959  1675901999  22974.6    22942
17474  20230209   082000    082959  1675902599    22942  22981.4
2023-02-09 08:30:00,986:INFO:pyemd2:main.py:127:handleKline:185189: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}


## /root/FIL/strategy/similarity/log.txt ----- -----

12144  20230209   080000    080959  1675901399  22955.9  22974.6
2023-02-09 08:10:01,576:INFO:testStrategy:main.py:103:handleKline:185174: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': True, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True, 'isCorr': False}
127.0.0.1 - - [09/Feb/2023 08:20:00] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=10906 

self.closeSec=1675901999, self.tradeDate='20230209', self.openTime='081000', self.closeTime='081959', self.symbol='BTCUSDT', self.open='22974.6', self.close='22942'
2023-02-09 08:20:00,532:INFO:testStrategy:main.py:101:handleKline:185174: self.closeSec=1675901999, self.tradeDate='20230209', self.openTime='081000', self.closeTime='081959',self.symbol='BTCUSDT',self.open='22974.6', self.close='22942'
2023-02-09 08:20:00,584:INFO:testStrategy:main.py:102:handleKline:185174: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
12141  20230209   073000    073959  1675899599    22905    22943
12142  20230209   074000    074959  1675900199    22943  22932.8
12143  20230209   075000    075959  1675900799  22932.6    22956
12144  20230209   080000    080959  1675901399  22955.9  22974.6
12145  20230209   081000    081959  1675901999  22974.6    22942
2023-02-09 08:20:00,584:INFO:testStrategy:main.py:103:handleKline:185174: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': True, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True, 'isCorr': False}

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=10907 

self.closeSec=1675902599, self.tradeDate='20230209', self.openTime='082000', self.closeTime='082959', self.symbol='BTCUSDT', self.open='22942', self.close='22981.4'
127.0.0.1 - - [09/Feb/2023 08:30:00] "POST / HTTP/1.1" 200 -
2023-02-09 08:30:00,945:INFO:testStrategy:main.py:101:handleKline:185174: self.closeSec=1675902599, self.tradeDate='20230209', self.openTime='082000', self.closeTime='082959',self.symbol='BTCUSDT',self.open='22942', self.close='22981.4'
2023-02-09 08:30:01,006:INFO:testStrategy:main.py:102:handleKline:185174: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
12142  20230209   074000    074959  1675900199    22943  22932.8
12143  20230209   075000    075959  1675900799  22932.6    22956
12144  20230209   080000    080959  1675901399  22955.9  22974.6
12145  20230209   081000    081959  1675901999  22974.6    22942
12146  20230209   082000    082959  1675902599    22942  22981.4
2023-02-09 08:30:01,006:INFO:testStrategy:main.py:103:handleKline:185174: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': True, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True, 'isCorr': False}


## /root/FIL/strategy/sr_min/log.txt ----- -----

--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=0, self.total=1000000.0, self.flagDict['side']='', self.tradeCount=0, self.count=17244
self.closeSec=1675902599, self.tradeDate='20230209', self.openTime='082500', self.closeTime='082959', self.symbol='BTCUSDT', self.open=22929.6, self.close=22981.5, self.high=22990.4, self.low=22921.8, self.vol=1422.403, self.amt=32664106.3762 
127.0.0.1 - - [09/Feb/2023 08:30:00] "POST / HTTP/1.1" 200 -
2023-02-09 08:30:00,794:INFO:sr_min:main.py:172:handleKline:449472: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5857  20230209   080500    080959  ...         0.0        0.0       0
5858  20230209   081000    081459  ...         0.0        0.0       0
5859  20230209   081500    081959  ...         0.0        0.0       0
5860  20230209   082000    082459  ...         0.0        0.0       0
5861  20230209   082500    082959  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-02-09 08:30:00,797:INFO:sr_min:main.py:175:handleKline:449472: self.closeSec=1675902599, self.tradeDate='20230209', self.openTime='082500', self.closeTime='082959',self.symbol='BTCUSDT',self.open=22929.6, self.close=22981.5, self.high=22990.4, self.low=22921.8, self.vol=1422.403, self.amt=32664106.3762, ukdf['pct'].iloc[-1]=0.002263 , ukdf['amount'].iloc[-1]=32664106.3762, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5861, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': []}
type(curSign)=<class 'int'>, curSign=0, self.sign=0
127.0.0.1 - - [09/Feb/2023 08:35:00] "POST / HTTP/1.1" 200 -
--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=0, self.total=1000000.0, self.flagDict['side']='', self.tradeCount=0, self.count=17245
self.closeSec=1675902899, self.tradeDate='20230209', self.openTime='083000', self.closeTime='083459', self.symbol='BTCUSDT', self.open=22981.1, self.close=22959.8, self.high=22981.1, self.low=22956.5, self.vol=730.282, self.amt=16775524.812 
2023-02-09 08:35:00,548:INFO:sr_min:main.py:172:handleKline:449472: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5858  20230209   081000    081459  ...         0.0        0.0       0
5859  20230209   081500    081959  ...         0.0        0.0       0
5860  20230209   082000    082459  ...         0.0        0.0       0
5861  20230209   082500    082959  ...         0.0        0.0       0
5862  20230209   083000    083459  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-02-09 08:35:00,548:INFO:sr_min:main.py:175:handleKline:449472: self.closeSec=1675902899, self.tradeDate='20230209', self.openTime='083000', self.closeTime='083459',self.symbol='BTCUSDT',self.open=22981.1, self.close=22959.8, self.high=22981.1, self.low=22956.5, self.vol=730.282, self.amt=16775524.812, ukdf['pct'].iloc[-1]=-0.000944 , ukdf['amount'].iloc[-1]=16775524.812, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5862, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': []}
type(curSign)=<class 'int'>, curSign=0, self.sign=0


## /root/FIL/strategy/s_rsrs/log.txt ----- -----

2023-02-09 04:00:09,359:INFO:s_rsrs:main.py:346:handleOrderFilled:185271: handleOrderFilled: data=OrderType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'clientorderid': '41694F1675886403751I0L65', 'symbol': 'BTCUSDT', 'gatewayorderid': 1675886403851332, 'quantity': '38.964', 'price': '22864.2', 'stopprice': '0', 'ordertype': '', 'side': 'SELL', 'status': 'FILLED', 'positionside': 'SHORT', 'createtime': 1675886403441, 'updatetime': 1675886403851, 'tradetype': 'usdt', 'selfid': 41694, 'filltrades': [TradeType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'tradeid': 1675886403851, 'clientorderid': '41694F1675886403751I0L65', 'price': '22864.2', 'quantity': '38.964', 'commission': '890.8806888', 'commissionasset': 'USDT', 'tradetime': 1675886403851, 'tradetype': 'usdt', 'gatetype': 'simulator', 'handletime': 1675886403851}], 'gatetype': 'simulator', 'handletime': 0}
127.0.0.1 - - [09/Feb/2023 04:00:09] "POST / HTTP/1.1" 200 -
2023-02-09 04:00:09,517:INFO:s_rsrs:main.py:343:handleOrderNew:185271: handleOrderNew: data=OrderType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'clientorderid': '41695F1675886409337I0L65', 'symbol': 'BTCUSDT', 'gatewayorderid': 1675886409481251, 'quantity': '38.925', 'price': '22855.7', 'stopprice': '0', 'ordertype': '', 'side': 'SELL', 'status': 'FILLED', 'positionside': 'SHORT', 'createtime': 1675886408931, 'updatetime': 1675886409481, 'tradetype': 'usdt', 'selfid': 41695, 'filltrades': [TradeType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'tradeid': 1675886409481, 'clientorderid': '41695F1675886409337I0L65', 'price': '22855.7', 'quantity': '38.925', 'commission': '889.6581225', 'commissionasset': 'USDT', 'tradetime': 1675886409481, 'tradetype': 'usdt', 'gatetype': 'simulator', 'handletime': 1675886409481}], 'gatetype': 'simulator', 'handletime': 0}
127.0.0.1 - - [09/Feb/2023 04:00:09] "POST / HTTP/1.1" 200 -
2023-02-09 04:00:09,763:INFO:s_rsrs:main.py:346:handleOrderFilled:185271: handleOrderFilled: data=OrderType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'clientorderid': '41695F1675886409337I0L65', 'symbol': 'BTCUSDT', 'gatewayorderid': 1675886409481251, 'quantity': '38.925', 'price': '22855.7', 'stopprice': '0', 'ordertype': '', 'side': 'SELL', 'status': 'FILLED', 'positionside': 'SHORT', 'createtime': 1675886408931, 'updatetime': 1675886409481, 'tradetype': 'usdt', 'selfid': 41695, 'filltrades': [TradeType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'tradeid': 1675886409481, 'clientorderid': '41695F1675886409337I0L65', 'price': '22855.7', 'quantity': '38.925', 'commission': '889.6581225', 'commissionasset': 'USDT', 'tradetime': 1675886409481, 'tradetype': 'usdt', 'gatetype': 'simulator', 'handletime': 1675886409481}], 'gatetype': 'simulator', 'handletime': 0}
127.0.0.1 - - [09/Feb/2023 04:00:09] "POST / HTTP/1.1" 200 -
--handleKline--:  version='2.0.0', self.name='s_rsrs', self.symbol='BTCUSDT', interval='4h', intervalSec=14400, wid=25, thd=0.6, self.sign=-1, self.total=888768.4643774999, self.flagDict['side']='sell', self.tradeCount=17, self.count=454
self.closeSec=1675900799, self.tradeDate='20230209', self.openTime='040000', self.closeTime='075959', self.symbol='BTCUSDT', self.open=22867.4, self.close=22956.0, self.high=22977.0, self.low=22766.4, self.vol=42038.652, self.amt=962196407.69 
127.0.0.1 - - [09/Feb/2023 08:00:00] "POST / HTTP/1.1" 200 -
2023-02-09 08:00:00,995:INFO:s_rsrs:main.py:141:handleKline:185271: self.closeSec=1675900799, self.tradeDate='20230209', self.openTime='040000', self.closeTime='075959',self.symbol='BTCUSDT',self.open=22867.4, self.close=22956.0, self.high=22977.0, self.low=22766.4, self.vol=42038.652, self.amt=962196407.69 
2023-02-09 08:00:01,041:INFO:s_rsrs:main.py:142:handleKline:185271: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime  ...         vol           amt       pct
717  20230208   120000    155959  ...   24681.986  5.730485e+08 -0.001019
718  20230208   160000    195959  ...   32606.039  7.556279e+08 -0.003190
719  20230208   200000    235959  ...  103068.788  2.372762e+09 -0.012547
720  20230209   000000    035959  ...  131915.737  3.015449e+09  0.000219
721  20230209   040000    075959  ...   42038.652  9.621964e+08  0.003879

[5 rows x 11 columns]
2023-02-09 08:00:03,098:INFO:s_rsrs:main.py:151:handleKline:185271: df_s.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec  ...  index      beta    zscore  signal
717  20230208   120000    155959  1675843199  ...    717  0.382526 -0.392084     NaN
718  20230208   160000    195959  1675857599  ...    718  0.378819 -0.393258     NaN
719  20230208   200000    235959  1675871999  ...    719  0.380896 -0.375045     NaN
720  20230209   000000    035959  1675886399  ...    720  0.329676 -0.601531    -1.0
721  20230209   040000    075959  1675900799  ...    721  0.326246 -0.642327    -1.0

[5 rows x 15 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '38.925', 'enterprice': '22855.7', 'countrevence': '0', 'unrealprofit': '-3900.285', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '22955.9', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'numpy.int64'>, curSign=-1, self.sign=-1


