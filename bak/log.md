# 20230113 16:16:01

## /root/FIL/strategy/amihud/log.txt ----- -----

--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=993672.4896432, self.flagDict['side']='sell', self.tradeCount=2, self.count=13562
self.closeSec=1673597399, self.tradeDate='20230113', self.openTime='160500', self.closeTime='160959', self.symbol='BTCUSDT', self.open=18822.9, self.close=18813.3, self.high=18823.1, self.low=18813.1, self.vol=385.521, self.amt=7255011.1345 
127.0.0.1 - - [13/Jan/2023 16:10:01] "POST / HTTP/1.1" 200 -
2023-01-13 16:10:01,470:INFO:amihud:main.py:172:handleKline:200676: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5949  20230113   154500    154959  ...         0.0        0.0       0
5950  20230113   155000    155459  ...         0.0        0.0       0
5951  20230113   155500    155959  ...         0.0        0.0       0
5952  20230113   160000    160459  ...         0.0        0.0       0
5953  20230113   160500    160959  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-01-13 16:10:01,470:INFO:amihud:main.py:175:handleKline:200676: self.closeSec=1673597399, self.tradeDate='20230113', self.openTime='160500', self.closeTime='160959',self.symbol='BTCUSDT',self.open=18822.9, self.close=18813.3, self.high=18823.1, self.low=18813.1, self.vol=385.521, self.amt=7255011.1345, ukdf['pct'].iloc[-1]=-0.00051 , ukdf['amount'].iloc[-1]=7255011.1345, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5953, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '60.176', 'enterprice': '16529.3', 'countrevence': '0', 'unrealprofit': '-137544.31481466512', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '18815.00052537', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1
127.0.0.1 - - [13/Jan/2023 16:15:00] "POST / HTTP/1.1" 200 -
--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=993672.4896432, self.flagDict['side']='sell', self.tradeCount=2, self.count=13563
self.closeSec=1673597699, self.tradeDate='20230113', self.openTime='161000', self.closeTime='161459', self.symbol='BTCUSDT', self.open=18813.3, self.close=18815.2, self.high=18823.7, self.low=18803.9, self.vol=536.993, self.amt=10103403.2635 
2023-01-13 16:15:00,940:INFO:amihud:main.py:172:handleKline:200676: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5950  20230113   155000    155459  ...         0.0        0.0       0
5951  20230113   155500    155959  ...         0.0        0.0       0
5952  20230113   160000    160459  ...         0.0        0.0       0
5953  20230113   160500    160959  ...         0.0        0.0       0
5954  20230113   161000    161459  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-01-13 16:15:00,941:INFO:amihud:main.py:175:handleKline:200676: self.closeSec=1673597699, self.tradeDate='20230113', self.openTime='161000', self.closeTime='161459',self.symbol='BTCUSDT',self.open=18813.3, self.close=18815.2, self.high=18823.7, self.low=18803.9, self.vol=536.993, self.amt=10103403.2635, ukdf['pct'].iloc[-1]=0.000101 , ukdf['amount'].iloc[-1]=10103403.2635, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5954, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '60.176', 'enterprice': '16529.3', 'countrevence': '0', 'unrealprofit': '-137645.36465920768', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '18816.67976368', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1


## /root/FIL/strategy/factorcheck/log.txt ----- -----

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=271, self.factor=0.2124752335592761, self.count=14128 

self.closeSec=1673597399, self.tradeDate='20230113', self.openTime='160500', self.closeTime='160959', self.symbol='BTCUSDT', self.open=18822.9, self.close=18813.3, self.high=18823.1, self.low=18813.1 
2023-01-13 16:10:01,444:INFO:factorcheck2:main.py:126:handleKline:185239: self.closeSec=1673597399, self.tradeDate='20230113', self.openTime='160500', self.closeTime='160959',self.symbol='BTCUSDT',self.open=18822.9, self.close=18813.3, self.high=18823.1, self.low=18813.1   
2023-01-13 16:10:01,542:INFO:factorcheck2:main.py:127:handleKline:185239: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime    closeSec  ...      low       pct  index  idx
1629  20230113   154500    154959  1673596199  ...  18802.2  0.000218   1629    3
1630  20230113   155000    155459  1673596499  ...  18806.3  0.000755   1630    4
1631  20230113   155500    155959  1673596799  ...  18812.0 -0.000154   1631    5
1632  20230113   160000    160459  1673597099  ...  18810.2  0.000276   1632    0
1633  20230113   160500    160959  1673597399  ...  18813.1 -0.000510   1633    1

[5 rows x 11 columns]
2023-01-13 16:10:01,551:INFO:factorcheck2:main.py:128:handleKline:185239: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}
127.0.0.1 - - [13/Jan/2023 16:15:00] "POST / HTTP/1.1" 200 -

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=271, self.factor=0.2124752335592761, self.count=14129 

self.closeSec=1673597699, self.tradeDate='20230113', self.openTime='161000', self.closeTime='161459', self.symbol='BTCUSDT', self.open=18813.3, self.close=18815.2, self.high=18823.7, self.low=18803.9 
2023-01-13 16:15:00,826:INFO:factorcheck2:main.py:126:handleKline:185239: self.closeSec=1673597699, self.tradeDate='20230113', self.openTime='161000', self.closeTime='161459',self.symbol='BTCUSDT',self.open=18813.3, self.close=18815.2, self.high=18823.7, self.low=18803.9   
2023-01-13 16:15:00,884:INFO:factorcheck2:main.py:127:handleKline:185239: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime    closeSec  ...      low       pct  index  idx
1630  20230113   155000    155459  1673596499  ...  18806.3  0.000755   1630    4
1631  20230113   155500    155959  1673596799  ...  18812.0 -0.000154   1631    5
1632  20230113   160000    160459  1673597099  ...  18810.2  0.000276   1632    0
1633  20230113   160500    160959  1673597399  ...  18813.1 -0.000510   1633    1
1634  20230113   161000    161459  1673597699  ...  18803.9  0.000101   1634    2

[5 rows x 11 columns]
2023-01-13 16:15:00,884:INFO:factorcheck2:main.py:128:handleKline:185239: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}


## /root/FIL/strategy/logic/log.txt ----- -----

2023-01-13 16:00:32,883:DEBUG:logic:main.py:456:getModel:726423: df_s.iloc[-5:,:] :
          date closeTime     open  ...    alpha58   alpha67   alpha72
5786  20230113    132959  18814.7  ...  57.083333  0.634618  0.227963
5787  20230113    135959  18815.0  ...  56.666667  0.625199  0.231484
5788  20230113    142959  18780.2  ...  57.083333  0.631225  0.232671
5789  20230113    145959  18817.7  ...  57.083333  0.635345  0.232332
5790  20230113    152959  18844.1  ...  56.666667  0.618824  0.235402

[5 rows x 33 columns]
0.5424354243542435
acc is : 0.5424354243542435
2023-01-13 16:00:33,086:INFO:logic:main.py:461:getModel:726423: df_pred.iloc[-5:,:] :
     pred    prob_0    prob_1  actual  ...       nav  sign  cost_        bm
537     0  0.508611  0.491389       0  ...  1.012807   1.0    0.0  1.132796
538     1  0.498956  0.501044       1  ...  1.014867   1.0    0.0  1.135101
539     0  0.513204  0.486796       1  ...  1.016286   1.0    0.0  1.136687
540     0  0.515661  0.484339       0  ...  1.012964   1.0    0.0  1.132971
541     1  0.493919  0.506081       1  ...  1.014867   1.0    0.0  1.135101

[5 rows x 10 columns]
2023-01-13 16:00:33,116:INFO:logic:main.py:471:getModel:726423: df_panel.iloc[-5:,:] :
    pred    prob_0    prob_1  actual  ...       nav  sign  cost_        bm
45     0  0.507690  0.492310       0  ...  1.012807   1.0    0.0  1.131677
46     1  0.498773  0.501227       1  ...  1.014867   1.0    0.0  1.133617
47     0  0.512899  0.487101       1  ...  1.016286   1.0    0.0  1.134477
48     0  0.515331  0.484669       0  ...  1.012964   1.0    0.0  1.132814
49     1  0.493919  0.506081       1  ...  1.014867   1.0    0.0  1.135101

[5 rows x 10 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': []}


## /root/FIL/strategy/modifiedmom/log.txt ----- -----

526  20230113   154000    154959  1673596199  18786.7  18806.4  0.001049
2023-01-13 15:50:00,581:INFO:modifiedmom:main.py:146:handleKline:185213: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': True, 'isOpenSell': False, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True}
127.0.0.1 - - [13/Jan/2023 16:00:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=7063 

self.closeSec=1673596799, self.tradeDate='20230113', self.openTime='155000', self.closeTime='155959', self.symbol='BTCUSDT', self.open='18806.4', self.close='18817.7'
2023-01-13 16:00:01,301:INFO:modifiedmom:main.py:144:handleKline:185213: self.closeSec=1673596799, self.tradeDate='20230113', self.openTime='155000', self.closeTime='155959',self.symbol='BTCUSDT',self.open='18806.4', self.close='18817.7'
2023-01-13 16:00:01,356:INFO:modifiedmom:main.py:145:handleKline:185213: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec     open    close       pct
523  20230113   151000    151959  1673594399  18838.7  18811.8 -0.001423
524  20230113   152000    152959  1673594999  18811.8  18783.1 -0.001526
525  20230113   153000    153959  1673595599  18783.1  18786.7  0.000192
526  20230113   154000    154959  1673596199  18786.7  18806.4  0.001049
527  20230113   155000    155959  1673596799  18806.4  18817.7  0.000601
2023-01-13 16:00:01,361:INFO:modifiedmom:main.py:146:handleKline:185213: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': True, 'isOpenSell': False, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True}

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=7064 

self.closeSec=1673597399, self.tradeDate='20230113', self.openTime='160000', self.closeTime='160959', self.symbol='BTCUSDT', self.open='18817.7', self.close='18813.3'
2023-01-13 16:10:01,556:INFO:modifiedmom:main.py:144:handleKline:185213: self.closeSec=1673597399, self.tradeDate='20230113', self.openTime='160000', self.closeTime='160959',self.symbol='BTCUSDT',self.open='18817.7', self.close='18813.3'
127.0.0.1 - - [13/Jan/2023 16:10:01] "POST / HTTP/1.1" 200 -
2023-01-13 16:10:01,570:INFO:modifiedmom:main.py:145:handleKline:185213: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec     open    close       pct
524  20230113   152000    152959  1673594999  18811.8  18783.1 -0.001526
525  20230113   153000    153959  1673595599  18783.1  18786.7  0.000192
526  20230113   154000    154959  1673596199  18786.7  18806.4  0.001049
527  20230113   155000    155959  1673596799  18806.4  18817.7  0.000601
528  20230113   160000    160959  1673597399  18817.7  18813.3 -0.000234
2023-01-13 16:10:01,570:INFO:modifiedmom:main.py:146:handleKline:185213: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': True, 'isOpenSell': False, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True}


## /root/FIL/strategy/pyemd/log.txt ----- -----

17518  20230113   154000    154959  1673596199  18786.7  18806.4
2023-01-13 15:50:00,599:INFO:pyemd2:main.py:127:handleKline:185189: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=7064 

self.closeSec=1673596799, self.tradeDate='20230113', self.openTime='155000', self.closeTime='155959', self.symbol='BTCUSDT', self.open='18806.4', self.close='18817.7'
127.0.0.1 - - [13/Jan/2023 16:00:01] "POST / HTTP/1.1" 200 -
2023-01-13 16:00:01,331:INFO:pyemd2:main.py:125:handleKline:185189: self.closeSec=1673596799, self.tradeDate='20230113', self.openTime='155000', self.closeTime='155959',self.symbol='BTCUSDT',self.open='18806.4', self.close='18817.7'
2023-01-13 16:00:01,373:INFO:pyemd2:main.py:126:handleKline:185189: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
17515  20230113   151000    151959  1673594399  18838.7  18811.8
17516  20230113   152000    152959  1673594999  18811.8  18783.1
17517  20230113   153000    153959  1673595599  18783.1  18786.7
17518  20230113   154000    154959  1673596199  18786.7  18806.4
17519  20230113   155000    155959  1673596799  18806.4  18817.7
2023-01-13 16:00:01,373:INFO:pyemd2:main.py:127:handleKline:185189: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=7065 

self.closeSec=1673597399, self.tradeDate='20230113', self.openTime='160000', self.closeTime='160959', self.symbol='BTCUSDT', self.open='18817.7', self.close='18813.3'
2023-01-13 16:10:01,553:INFO:pyemd2:main.py:125:handleKline:185189: self.closeSec=1673597399, self.tradeDate='20230113', self.openTime='160000', self.closeTime='160959',self.symbol='BTCUSDT',self.open='18817.7', self.close='18813.3'
127.0.0.1 - - [13/Jan/2023 16:10:01] "POST / HTTP/1.1" 200 -
2023-01-13 16:10:01,576:INFO:pyemd2:main.py:126:handleKline:185189: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
17516  20230113   152000    152959  1673594999  18811.8  18783.1
17517  20230113   153000    153959  1673595599  18783.1  18786.7
17518  20230113   154000    154959  1673596199  18786.7  18806.4
17519  20230113   155000    155959  1673596799  18806.4  18817.7
17520  20230113   160000    160959  1673597399  18817.7  18813.3
2023-01-13 16:10:01,576:INFO:pyemd2:main.py:127:handleKline:185189: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}


## /root/FIL/strategy/similarity/log.txt ----- -----

12190  20230113   154000    154959  1673596199  18786.7  18806.4
2023-01-13 15:50:00,583:INFO:testStrategy:main.py:103:handleKline:185174: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': True, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True, 'isCorr': False}

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=7064 

self.closeSec=1673596799, self.tradeDate='20230113', self.openTime='155000', self.closeTime='155959', self.symbol='BTCUSDT', self.open='18806.4', self.close='18817.7'
127.0.0.1 - - [13/Jan/2023 16:00:01] "POST / HTTP/1.1" 200 -
2023-01-13 16:00:01,287:INFO:testStrategy:main.py:101:handleKline:185174: self.closeSec=1673596799, self.tradeDate='20230113', self.openTime='155000', self.closeTime='155959',self.symbol='BTCUSDT',self.open='18806.4', self.close='18817.7'
2023-01-13 16:00:01,303:INFO:testStrategy:main.py:102:handleKline:185174: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
12187  20230113   151000    151959  1673594399  18838.7  18811.8
12188  20230113   152000    152959  1673594999  18811.8  18783.1
12189  20230113   153000    153959  1673595599  18783.1  18786.7
12190  20230113   154000    154959  1673596199  18786.7  18806.4
12191  20230113   155000    155959  1673596799  18806.4  18817.7
2023-01-13 16:00:01,303:INFO:testStrategy:main.py:103:handleKline:185174: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': True, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True, 'isCorr': False}

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=7065 

self.closeSec=1673597399, self.tradeDate='20230113', self.openTime='160000', self.closeTime='160959', self.symbol='BTCUSDT', self.open='18817.7', self.close='18813.3'
2023-01-13 16:10:01,537:INFO:testStrategy:main.py:101:handleKline:185174: self.closeSec=1673597399, self.tradeDate='20230113', self.openTime='160000', self.closeTime='160959',self.symbol='BTCUSDT',self.open='18817.7', self.close='18813.3'
127.0.0.1 - - [13/Jan/2023 16:10:01] "POST / HTTP/1.1" 200 -
2023-01-13 16:10:01,561:INFO:testStrategy:main.py:102:handleKline:185174: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
12188  20230113   152000    152959  1673594999  18811.8  18783.1
12189  20230113   153000    153959  1673595599  18783.1  18786.7
12190  20230113   154000    154959  1673596199  18786.7  18806.4
12191  20230113   155000    155959  1673596799  18806.4  18817.7
12192  20230113   160000    160959  1673597399  18817.7  18813.3
2023-01-13 16:10:01,561:INFO:testStrategy:main.py:103:handleKline:185174: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': True, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True, 'isCorr': False}


## /root/FIL/strategy/sr_min/log.txt ----- -----

127.0.0.1 - - [13/Jan/2023 16:10:01] "POST / HTTP/1.1" 200 -
--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=0, self.total=1000000.0, self.flagDict['side']='', self.tradeCount=0, self.count=9560
self.closeSec=1673597399, self.tradeDate='20230113', self.openTime='160500', self.closeTime='160959', self.symbol='BTCUSDT', self.open=18822.9, self.close=18813.3, self.high=18823.1, self.low=18813.1, self.vol=385.521, self.amt=7255011.1345 
2023-01-13 16:10:01,514:INFO:sr_min:main.py:172:handleKline:449472: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5949  20230113   154500    154959  ...         0.0        0.0       0
5950  20230113   155000    155459  ...         0.0        0.0       0
5951  20230113   155500    155959  ...         0.0        0.0       0
5952  20230113   160000    160459  ...         0.0        0.0       0
5953  20230113   160500    160959  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-01-13 16:10:01,515:INFO:sr_min:main.py:175:handleKline:449472: self.closeSec=1673597399, self.tradeDate='20230113', self.openTime='160500', self.closeTime='160959',self.symbol='BTCUSDT',self.open=18822.9, self.close=18813.3, self.high=18823.1, self.low=18813.1, self.vol=385.521, self.amt=7255011.1345, ukdf['pct'].iloc[-1]=-0.00051 , ukdf['amount'].iloc[-1]=7255011.1345, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5953, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': []}
type(curSign)=<class 'int'>, curSign=0, self.sign=0
127.0.0.1 - - [13/Jan/2023 16:15:00] "POST / HTTP/1.1" 200 -
--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=0, self.total=1000000.0, self.flagDict['side']='', self.tradeCount=0, self.count=9561
self.closeSec=1673597699, self.tradeDate='20230113', self.openTime='161000', self.closeTime='161459', self.symbol='BTCUSDT', self.open=18813.3, self.close=18815.2, self.high=18823.7, self.low=18803.9, self.vol=536.993, self.amt=10103403.2635 
2023-01-13 16:15:00,944:INFO:sr_min:main.py:172:handleKline:449472: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5950  20230113   155000    155459  ...         0.0        0.0       0
5951  20230113   155500    155959  ...         0.0        0.0       0
5952  20230113   160000    160459  ...         0.0        0.0       0
5953  20230113   160500    160959  ...         0.0        0.0       0
5954  20230113   161000    161459  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-01-13 16:15:00,945:INFO:sr_min:main.py:175:handleKline:449472: self.closeSec=1673597699, self.tradeDate='20230113', self.openTime='161000', self.closeTime='161459',self.symbol='BTCUSDT',self.open=18813.3, self.close=18815.2, self.high=18823.7, self.low=18803.9, self.vol=536.993, self.amt=10103403.2635, ukdf['pct'].iloc[-1]=0.000101 , ukdf['amount'].iloc[-1]=10103403.2635, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5954, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': []}
type(curSign)=<class 'int'>, curSign=0, self.sign=0


## /root/FIL/strategy/s_rsrs/log.txt ----- -----

721  20230113   040000    075959  1673567999  ...    721  1.431327  2.104170     1.0
722  20230113   080000    115959  1673582399  ...    722  1.302623  1.722950     1.0

[5 rows x 15 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '51.136', 'enterprice': '17188.2', 'countrevence': '0', 'unrealprofit': '86082.3424', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '18871.6', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'numpy.int64'>, curSign=1, self.sign=1
127.0.0.1 - - [13/Jan/2023 16:00:01] "POST / HTTP/1.1" 200 -
--handleKline--:  version='2.0.0', self.name='s_rsrs', self.symbol='BTCUSDT', interval='4h', intervalSec=14400, wid=25, thd=0.6, self.sign=1, self.total=878056.8594048, self.flagDict['side']='buy', self.tradeCount=12, self.count=294
self.closeSec=1673596799, self.tradeDate='20230113', self.openTime='120000', self.closeTime='155959', self.symbol='BTCUSDT', self.open=18871.5, self.close=18817.7, self.high=18875.4, self.low=18770.5, self.vol=30968.56, self.amt=582771161.8809 
2023-01-13 16:00:01,206:INFO:s_rsrs:main.py:141:handleKline:185271: self.closeSec=1673596799, self.tradeDate='20230113', self.openTime='120000', self.closeTime='155959',self.symbol='BTCUSDT',self.open=18871.5, self.close=18817.7, self.high=18875.4, self.low=18770.5, self.vol=30968.56, self.amt=582771161.8809 
2023-01-13 16:00:01,254:INFO:s_rsrs:main.py:142:handleKline:185271: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime  ...         vol           amt       pct
719  20230112   200000    235959  ...  322077.456  5.844744e+09 -0.006425
720  20230113   000000    035959  ...  328471.599  6.135608e+09  0.044232
721  20230113   040000    075959  ...  124572.563  2.353820e+09 -0.002077
722  20230113   080000    115959  ...   48452.132  9.110449e+08  0.001784
723  20230113   120000    155959  ...   30968.560  5.827712e+08 -0.002856

[5 rows x 11 columns]
2023-01-13 16:00:03,366:INFO:s_rsrs:main.py:151:handleKline:185271: df_s.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec  ...  index      beta    zscore  signal
719  20230112   200000    235959  1673539199  ...    719  1.297220  1.946828     1.0
720  20230113   000000    035959  1673553599  ...    720  1.612741  2.660284     1.0
721  20230113   040000    075959  1673567999  ...    721  1.431327  2.104170     1.0
722  20230113   080000    115959  1673582399  ...    722  1.302623  1.722950     1.0
723  20230113   120000    155959  1673596799  ...    723  1.171585  1.361232     1.0

[5 rows x 15 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '51.136', 'enterprice': '17188.2', 'countrevence': '0', 'unrealprofit': '83326.112', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '18817.7', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'numpy.int64'>, curSign=1, self.sign=1


