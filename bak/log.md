# 20230115 16:16:01

## /root/FIL/strategy/amihud/log.txt ----- -----

--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=993672.4896432, self.flagDict['side']='sell', self.tradeCount=2, self.count=14138
self.closeSec=1673770199, self.tradeDate='20230115', self.openTime='160500', self.closeTime='160959', self.symbol='BTCUSDT', self.open=20750.9, self.close=20750.8, self.high=20765.8, self.low=20750.2, self.vol=629.138, self.amt=13059150.8296 
127.0.0.1 - - [15/Jan/2023 16:10:01] "POST / HTTP/1.1" 200 -
2023-01-15 16:10:01,514:INFO:amihud:main.py:172:handleKline:200676: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5949  20230115   154500    154959  ...         0.0        0.0       0
5950  20230115   155000    155459  ...         0.0        0.0       0
5951  20230115   155500    155959  ...         0.0        0.0       0
5952  20230115   160000    160459  ...         0.0        0.0       0
5953  20230115   160500    160959  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-01-15 16:10:01,520:INFO:amihud:main.py:175:handleKline:200676: self.closeSec=1673770199, self.tradeDate='20230115', self.openTime='160500', self.closeTime='160959',self.symbol='BTCUSDT',self.open=20750.9, self.close=20750.8, self.high=20765.8, self.low=20750.2, self.vol=629.138, self.amt=13059150.8296, ukdf['pct'].iloc[-1]=3.4e-05 , ukdf['amount'].iloc[-1]=13059150.8296, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5953, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '60.176', 'enterprice': '16529.3', 'countrevence': '0', 'unrealprofit': '-254026.9664', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '20750.7', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1
127.0.0.1 - - [15/Jan/2023 16:15:00] "POST / HTTP/1.1" 200 -
--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=993672.4896432, self.flagDict['side']='sell', self.tradeCount=2, self.count=14139
self.closeSec=1673770499, self.tradeDate='20230115', self.openTime='161000', self.closeTime='161459', self.symbol='BTCUSDT', self.open=20750.8, self.close=20745.0, self.high=20750.8, self.low=20733.8, self.vol=630.888, self.amt=13085519.9766 
2023-01-15 16:15:00,661:INFO:amihud:main.py:172:handleKline:200676: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5950  20230115   155000    155459  ...         0.0        0.0       0
5951  20230115   155500    155959  ...         0.0        0.0       0
5952  20230115   160000    160459  ...         0.0        0.0       0
5953  20230115   160500    160959  ...         0.0        0.0       0
5954  20230115   161000    161459  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-01-15 16:15:00,661:INFO:amihud:main.py:175:handleKline:200676: self.closeSec=1673770499, self.tradeDate='20230115', self.openTime='161000', self.closeTime='161459',self.symbol='BTCUSDT',self.open=20750.8, self.close=20745.0, self.high=20750.8, self.low=20733.8, self.vol=630.888, self.amt=13085519.9766, ukdf['pct'].iloc[-1]=-0.00028 , ukdf['amount'].iloc[-1]=13085519.9766, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5954, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '60.176', 'enterprice': '16529.3', 'countrevence': '0', 'unrealprofit': '-253689.9808', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '20745.1', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1


## /root/FIL/strategy/factorcheck/log.txt ----- -----

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=367, self.factor=0.2707722017603847, self.count=14704 

self.closeSec=1673770199, self.tradeDate='20230115', self.openTime='160500', self.closeTime='160959', self.symbol='BTCUSDT', self.open=20750.9, self.close=20750.8, self.high=20765.8, self.low=20750.2 
2023-01-15 16:10:01,463:INFO:factorcheck2:main.py:126:handleKline:185239: self.closeSec=1673770199, self.tradeDate='20230115', self.openTime='160500', self.closeTime='160959',self.symbol='BTCUSDT',self.open=20750.9, self.close=20750.8, self.high=20765.8, self.low=20750.2   
2023-01-15 16:10:01,576:INFO:factorcheck2:main.py:127:handleKline:185239: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime    closeSec  ...      low       pct  index  idx
1629  20230115   154500    154959  1673768999  ...  20730.0  0.000545   1629    3
1630  20230115   155000    155459  1673769299  ...  20732.5 -0.000265   1630    4
1631  20230115   155500    155959  1673769599  ...  20737.1  0.000627   1631    5
1632  20230115   160000    160459  1673769899  ...  20744.3  0.000000   1632    0
1633  20230115   160500    160959  1673770199  ...  20750.2  0.000034   1633    1

[5 rows x 11 columns]
2023-01-15 16:10:01,582:INFO:factorcheck2:main.py:128:handleKline:185239: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}
127.0.0.1 - - [15/Jan/2023 16:15:00] "POST / HTTP/1.1" 200 -

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=367, self.factor=0.2707722017603847, self.count=14705 

self.closeSec=1673770499, self.tradeDate='20230115', self.openTime='161000', self.closeTime='161459', self.symbol='BTCUSDT', self.open=20750.8, self.close=20745.0, self.high=20750.8, self.low=20733.8 
2023-01-15 16:15:00,609:INFO:factorcheck2:main.py:126:handleKline:185239: self.closeSec=1673770499, self.tradeDate='20230115', self.openTime='161000', self.closeTime='161459',self.symbol='BTCUSDT',self.open=20750.8, self.close=20745.0, self.high=20750.8, self.low=20733.8   
2023-01-15 16:15:00,647:INFO:factorcheck2:main.py:127:handleKline:185239: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime    closeSec  ...      low       pct  index  idx
1630  20230115   155000    155459  1673769299  ...  20732.5 -0.000265   1630    4
1631  20230115   155500    155959  1673769599  ...  20737.1  0.000627   1631    5
1632  20230115   160000    160459  1673769899  ...  20744.3  0.000000   1632    0
1633  20230115   160500    160959  1673770199  ...  20750.2  0.000034   1633    1
1634  20230115   161000    161459  1673770499  ...  20733.8 -0.000280   1634    2

[5 rows x 11 columns]
2023-01-15 16:15:00,647:INFO:factorcheck2:main.py:128:handleKline:185239: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}


## /root/FIL/strategy/logic/log.txt ----- -----

2023-01-15 16:00:45,976:DEBUG:logic:main.py:456:getModel:726423: df_s.iloc[-5:,:] :
          date closeTime     open  ...    alpha58   alpha67   alpha72
5786  20230115    132959  20710.2  ...  55.833333  0.585651  0.419338
5787  20230115    135959  20770.0  ...  55.416667  0.583673  0.424054
5788  20230115    142959  20758.4  ...  55.833333  0.585790  0.429247
5789  20230115    145959  20775.6  ...  55.833333  0.577086  0.446520
5790  20230115    152959  20725.5  ...  55.833333  0.575080  0.467126

[5 rows x 33 columns]
0.511070110701107
acc is : 0.511070110701107
2023-01-15 16:00:46,214:INFO:logic:main.py:461:getModel:726423: df_pred.iloc[-5:,:] :
     pred    prob_0    prob_1  actual  ...       nav  sign  cost_        bm
537     0  0.518096  0.481904       0  ...  1.081492   1.0    0.0  1.246332
538     0  0.507012  0.492988       1  ...  1.082388   1.0    0.0  1.247364
539     0  0.509670  0.490330       0  ...  1.079783   1.0    0.0  1.244362
540     1  0.494311  0.505689       0  ...  1.079184   1.0    0.0  1.243672
541     0  0.500721  0.499279       1  ...  1.081055   1.0    0.0  1.245827

[5 rows x 10 columns]
2023-01-15 16:00:46,255:INFO:logic:main.py:471:getModel:726423: df_panel.iloc[-5:,:] :
    pred    prob_0    prob_1  actual  ...       nav  sign  cost_        bm
45     0  0.517916  0.482084       0  ...  1.081492   1.0    0.0  1.245240
46     0  0.506988  0.493012       1  ...  1.082388   1.0    0.0  1.246257
47     0  0.509644  0.490356       0  ...  1.079783   1.0    0.0  1.243496
48     1  0.494340  0.505660       0  ...  1.079184   1.0    0.0  1.242851
49     0  0.500721  0.499279       1  ...  1.081055   1.0    0.0  1.245827

[5 rows x 10 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': []}


## /root/FIL/strategy/modifiedmom/log.txt ----- -----

526  20230115   154000    154959  1673768999  20737.7  20746.4  0.000420
2023-01-15 15:50:00,590:INFO:modifiedmom:main.py:146:handleKline:185213: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': True, 'isOpenSell': False, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True}
127.0.0.1 - - [15/Jan/2023 16:00:00] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=7351 

self.closeSec=1673769599, self.tradeDate='20230115', self.openTime='155000', self.closeTime='155959', self.symbol='BTCUSDT', self.open='20742.6', self.close='20750'
2023-01-15 16:00:00,990:INFO:modifiedmom:main.py:144:handleKline:185213: self.closeSec=1673769599, self.tradeDate='20230115', self.openTime='155000', self.closeTime='155959',self.symbol='BTCUSDT',self.open='20742.6', self.close='20750'
2023-01-15 16:00:01,046:INFO:modifiedmom:main.py:145:handleKline:185213: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec     open    close       pct
523  20230115   151000    151959  1673767199  20706.9  20712.5  0.000266
524  20230115   152000    152959  1673767799  20712.6  20714.1  0.000077
525  20230115   153000    153959  1673768399  20714.2  20737.7  0.001139
526  20230115   154000    154959  1673768999  20737.7  20746.4  0.000420
527  20230115   155000    155959  1673769599  20742.6    20750  0.000174
2023-01-15 16:00:01,046:INFO:modifiedmom:main.py:146:handleKline:185213: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': True, 'isOpenSell': False, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True}
127.0.0.1 - - [15/Jan/2023 16:10:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=7352 

self.closeSec=1673770199, self.tradeDate='20230115', self.openTime='160000', self.closeTime='160959', self.symbol='BTCUSDT', self.open='20750.1', self.close='20750.8'
2023-01-15 16:10:01,544:INFO:modifiedmom:main.py:144:handleKline:185213: self.closeSec=1673770199, self.tradeDate='20230115', self.openTime='160000', self.closeTime='160959',self.symbol='BTCUSDT',self.open='20750.1', self.close='20750.8'
2023-01-15 16:10:01,583:INFO:modifiedmom:main.py:145:handleKline:185213: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec     open    close       pct
524  20230115   152000    152959  1673767799  20712.6  20714.1  0.000077
525  20230115   153000    153959  1673768399  20714.2  20737.7  0.001139
526  20230115   154000    154959  1673768999  20737.7  20746.4  0.000420
527  20230115   155000    155959  1673769599  20742.6    20750  0.000174
528  20230115   160000    160959  1673770199  20750.1  20750.8  0.000039
2023-01-15 16:10:01,583:INFO:modifiedmom:main.py:146:handleKline:185213: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': True, 'isOpenSell': False, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True}


## /root/FIL/strategy/pyemd/log.txt ----- -----

17518  20230115   154000    154959  1673768999  20737.7  20746.4
2023-01-15 15:50:00,566:INFO:pyemd2:main.py:127:handleKline:185189: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}
127.0.0.1 - - [15/Jan/2023 16:00:00] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=7352 

self.closeSec=1673769599, self.tradeDate='20230115', self.openTime='155000', self.closeTime='155959', self.symbol='BTCUSDT', self.open='20742.6', self.close='20750'
2023-01-15 16:00:01,019:INFO:pyemd2:main.py:125:handleKline:185189: self.closeSec=1673769599, self.tradeDate='20230115', self.openTime='155000', self.closeTime='155959',self.symbol='BTCUSDT',self.open='20742.6', self.close='20750'
2023-01-15 16:00:01,085:INFO:pyemd2:main.py:126:handleKline:185189: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
17515  20230115   151000    151959  1673767199  20706.9  20712.5
17516  20230115   152000    152959  1673767799  20712.6  20714.1
17517  20230115   153000    153959  1673768399  20714.2  20737.7
17518  20230115   154000    154959  1673768999  20737.7  20746.4
17519  20230115   155000    155959  1673769599  20742.6    20750
2023-01-15 16:00:01,085:INFO:pyemd2:main.py:127:handleKline:185189: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}
127.0.0.1 - - [15/Jan/2023 16:10:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=7353 

self.closeSec=1673770199, self.tradeDate='20230115', self.openTime='160000', self.closeTime='160959', self.symbol='BTCUSDT', self.open='20750.1', self.close='20750.8'
2023-01-15 16:10:01,567:INFO:pyemd2:main.py:125:handleKline:185189: self.closeSec=1673770199, self.tradeDate='20230115', self.openTime='160000', self.closeTime='160959',self.symbol='BTCUSDT',self.open='20750.1', self.close='20750.8'
2023-01-15 16:10:01,579:INFO:pyemd2:main.py:126:handleKline:185189: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
17516  20230115   152000    152959  1673767799  20712.6  20714.1
17517  20230115   153000    153959  1673768399  20714.2  20737.7
17518  20230115   154000    154959  1673768999  20737.7  20746.4
17519  20230115   155000    155959  1673769599  20742.6    20750
17520  20230115   160000    160959  1673770199  20750.1  20750.8
2023-01-15 16:10:01,581:INFO:pyemd2:main.py:127:handleKline:185189: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}


## /root/FIL/strategy/similarity/log.txt ----- -----

12190  20230115   154000    154959  1673768999  20737.7  20746.4
2023-01-15 15:50:00,596:INFO:testStrategy:main.py:103:handleKline:185174: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': True, 'isOpenSell': False, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True, 'isCorr': False}
127.0.0.1 - - [15/Jan/2023 16:00:00] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=7352 

self.closeSec=1673769599, self.tradeDate='20230115', self.openTime='155000', self.closeTime='155959', self.symbol='BTCUSDT', self.open='20742.6', self.close='20750'
2023-01-15 16:00:00,996:INFO:testStrategy:main.py:101:handleKline:185174: self.closeSec=1673769599, self.tradeDate='20230115', self.openTime='155000', self.closeTime='155959',self.symbol='BTCUSDT',self.open='20742.6', self.close='20750'
2023-01-15 16:00:01,086:INFO:testStrategy:main.py:102:handleKline:185174: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
12187  20230115   151000    151959  1673767199  20706.9  20712.5
12188  20230115   152000    152959  1673767799  20712.6  20714.1
12189  20230115   153000    153959  1673768399  20714.2  20737.7
12190  20230115   154000    154959  1673768999  20737.7  20746.4
12191  20230115   155000    155959  1673769599  20742.6    20750
2023-01-15 16:00:01,087:INFO:testStrategy:main.py:103:handleKline:185174: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': True, 'isOpenSell': False, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True, 'isCorr': False}
127.0.0.1 - - [15/Jan/2023 16:10:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=7353 

self.closeSec=1673770199, self.tradeDate='20230115', self.openTime='160000', self.closeTime='160959', self.symbol='BTCUSDT', self.open='20750.1', self.close='20750.8'
2023-01-15 16:10:01,562:INFO:testStrategy:main.py:101:handleKline:185174: self.closeSec=1673770199, self.tradeDate='20230115', self.openTime='160000', self.closeTime='160959',self.symbol='BTCUSDT',self.open='20750.1', self.close='20750.8'
2023-01-15 16:10:01,578:INFO:testStrategy:main.py:102:handleKline:185174: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
12188  20230115   152000    152959  1673767799  20712.6  20714.1
12189  20230115   153000    153959  1673768399  20714.2  20737.7
12190  20230115   154000    154959  1673768999  20737.7  20746.4
12191  20230115   155000    155959  1673769599  20742.6    20750
12192  20230115   160000    160959  1673770199  20750.1  20750.8
2023-01-15 16:10:01,578:INFO:testStrategy:main.py:103:handleKline:185174: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': True, 'isOpenSell': False, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True, 'isCorr': False}


## /root/FIL/strategy/sr_min/log.txt ----- -----

127.0.0.1 - - [15/Jan/2023 16:10:01] "POST / HTTP/1.1" 200 -
--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=0, self.total=1000000.0, self.flagDict['side']='', self.tradeCount=0, self.count=10136
self.closeSec=1673770199, self.tradeDate='20230115', self.openTime='160500', self.closeTime='160959', self.symbol='BTCUSDT', self.open=20750.9, self.close=20750.8, self.high=20765.8, self.low=20750.2, self.vol=629.138, self.amt=13059150.8296 
2023-01-15 16:10:01,509:INFO:sr_min:main.py:172:handleKline:449472: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5949  20230115   154500    154959  ...         0.0        0.0       0
5950  20230115   155000    155459  ...         0.0        0.0       0
5951  20230115   155500    155959  ...         0.0        0.0       0
5952  20230115   160000    160459  ...         0.0        0.0       0
5953  20230115   160500    160959  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-01-15 16:10:01,509:INFO:sr_min:main.py:175:handleKline:449472: self.closeSec=1673770199, self.tradeDate='20230115', self.openTime='160500', self.closeTime='160959',self.symbol='BTCUSDT',self.open=20750.9, self.close=20750.8, self.high=20765.8, self.low=20750.2, self.vol=629.138, self.amt=13059150.8296, ukdf['pct'].iloc[-1]=3.4e-05 , ukdf['amount'].iloc[-1]=13059150.8296, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5953, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': []}
type(curSign)=<class 'int'>, curSign=0, self.sign=0
--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=0, self.total=1000000.0, self.flagDict['side']='', self.tradeCount=0, self.count=10137
self.closeSec=1673770499, self.tradeDate='20230115', self.openTime='161000', self.closeTime='161459', self.symbol='BTCUSDT', self.open=20750.8, self.close=20745.0, self.high=20750.8, self.low=20733.8, self.vol=630.888, self.amt=13085519.9766 
127.0.0.1 - - [15/Jan/2023 16:15:00] "POST / HTTP/1.1" 200 -
2023-01-15 16:15:00,660:INFO:sr_min:main.py:172:handleKline:449472: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5950  20230115   155000    155459  ...         0.0        0.0       0
5951  20230115   155500    155959  ...         0.0        0.0       0
5952  20230115   160000    160459  ...         0.0        0.0       0
5953  20230115   160500    160959  ...         0.0        0.0       0
5954  20230115   161000    161459  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-01-15 16:15:00,660:INFO:sr_min:main.py:175:handleKline:449472: self.closeSec=1673770499, self.tradeDate='20230115', self.openTime='161000', self.closeTime='161459',self.symbol='BTCUSDT',self.open=20750.8, self.close=20745.0, self.high=20750.8, self.low=20733.8, self.vol=630.888, self.amt=13085519.9766, ukdf['pct'].iloc[-1]=-0.00028 , ukdf['amount'].iloc[-1]=13085519.9766, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5954, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': []}
type(curSign)=<class 'int'>, curSign=0, self.sign=0


## /root/FIL/strategy/s_rsrs/log.txt ----- -----

721  20230115   040000    075959  1673740799  ...    721  1.161411  1.034070     1.0
722  20230115   080000    115959  1673755199  ...    722  1.134716  0.954694     1.0

[5 rows x 15 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '51.136', 'enterprice': '17188.2', 'countrevence': '0', 'unrealprofit': '181445.8688', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '20736.5', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'numpy.int64'>, curSign=1, self.sign=1
--handleKline--:  version='2.0.0', self.name='s_rsrs', self.symbol='BTCUSDT', interval='4h', intervalSec=14400, wid=25, thd=0.6, self.sign=1, self.total=878056.8594048, self.flagDict['side']='buy', self.tradeCount=12, self.count=306
self.closeSec=1673769599, self.tradeDate='20230115', self.openTime='120000', self.closeTime='155959', self.symbol='BTCUSDT', self.open=20736.5, self.close=20750.0, self.high=20798.0, self.low=20673.9, self.vol=34775.593, self.amt=721249177.1872 
2023-01-15 16:00:00,859:INFO:s_rsrs:main.py:141:handleKline:185271: self.closeSec=1673769599, self.tradeDate='20230115', self.openTime='120000', self.closeTime='155959',self.symbol='BTCUSDT',self.open=20736.5, self.close=20750.0, self.high=20798.0, self.low=20673.9, self.vol=34775.593, self.amt=721249177.1872 
127.0.0.1 - - [15/Jan/2023 16:00:00] "POST / HTTP/1.1" 200 -
2023-01-15 16:00:00,929:INFO:s_rsrs:main.py:142:handleKline:185271: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime  ...         vol           amt       pct
719  20230114   200000    235959  ...  186884.918  3.898285e+09  0.003072
720  20230115   000000    035959  ...   78646.183  1.636048e+09  0.000082
721  20230115   040000    075959  ...   59647.002  1.249465e+09  0.007890
722  20230115   080000    115959  ...   96643.658  2.005612e+09 -0.010795
723  20230115   120000    155959  ...   34775.593  7.212492e+08  0.000651

[5 rows x 11 columns]
2023-01-15 16:00:04,029:INFO:s_rsrs:main.py:151:handleKline:185271: df_s.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec  ...  index      beta    zscore  signal
719  20230114   200000    235959  1673711999  ...    719  1.292952  1.376640     1.0
720  20230115   000000    035959  1673726399  ...    720  1.213180  1.171201     1.0
721  20230115   040000    075959  1673740799  ...    721  1.161411  1.034070     1.0
722  20230115   080000    115959  1673755199  ...    722  1.134716  0.954694     1.0
723  20230115   120000    155959  1673769599  ...    723  1.073325  0.800655     1.0

[5 rows x 15 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '51.136', 'enterprice': '17188.2', 'countrevence': '0', 'unrealprofit': '182133.70767520064', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '20749.95116699', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'numpy.int64'>, curSign=1, self.sign=1


