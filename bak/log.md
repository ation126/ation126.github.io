# 20221230 16:16:02

## /root/FIL/strategy/amihud/log.txt ----- -----

--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=993672.4896432, self.flagDict['side']='sell', self.tradeCount=2, self.count=9530
self.closeSec=1672387799, self.tradeDate='20221230', self.openTime='160500', self.closeTime='160959', self.symbol='BTCUSDT', self.open=16485.2, self.close=16477.7, self.high=16485.3, self.low=16473.5, self.vol=735.124, self.amt=12114268.0597 
127.0.0.1 - - [30/Dec/2022 16:10:01] "POST / HTTP/1.1" 200 -
2022-12-30 16:10:01,497:INFO:amihud:main.py:172:handleKline:200676: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5949  20221230   154500    154959  ...         0.0        0.0       0
5950  20221230   155000    155459  ...         0.0        0.0       0
5951  20221230   155500    155959  ...         0.0        0.0       0
5952  20221230   160000    160459  ...         0.0        0.0       0
5953  20221230   160500    160959  ...         0.0        0.0       0

[5 rows x 18 columns]
2022-12-30 16:10:01,497:INFO:amihud:main.py:175:handleKline:200676: self.closeSec=1672387799, self.tradeDate='20221230', self.openTime='160500', self.closeTime='160959',self.symbol='BTCUSDT',self.open=16485.2, self.close=16477.7, self.high=16485.3, self.low=16473.5, self.vol=735.124, self.amt=12114268.0597, ukdf['pct'].iloc[-1]=-0.000461 , ukdf['amount'].iloc[-1]=12114268.0597, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5953, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '60.176', 'enterprice': '16529.3', 'countrevence': '0', 'unrealprofit': '3068.21142420384', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '16478.31270566', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1
127.0.0.1 - - [30/Dec/2022 16:15:00] "POST / HTTP/1.1" 200 -
--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=993672.4896432, self.flagDict['side']='sell', self.tradeCount=2, self.count=9531
self.closeSec=1672388099, self.tradeDate='20221230', self.openTime='161000', self.closeTime='161459', self.symbol='BTCUSDT', self.open=16477.7, self.close=16477.7, self.high=16479.9, self.low=16474.0, self.vol=510.369, self.amt=8409095.2881 
2022-12-30 16:15:00,640:INFO:amihud:main.py:172:handleKline:200676: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5950  20221230   155000    155459  ...         0.0        0.0       0
5951  20221230   155500    155959  ...         0.0        0.0       0
5952  20221230   160000    160459  ...         0.0        0.0       0
5953  20221230   160500    160959  ...         0.0        0.0       0
5954  20221230   161000    161459  ...         0.0        0.0       0

[5 rows x 18 columns]
2022-12-30 16:15:00,641:INFO:amihud:main.py:175:handleKline:200676: self.closeSec=1672388099, self.tradeDate='20221230', self.openTime='161000', self.closeTime='161459',self.symbol='BTCUSDT',self.open=16477.7, self.close=16477.7, self.high=16479.9, self.low=16474.0, self.vol=510.369, self.amt=8409095.2881, ukdf['pct'].iloc[-1]=0.0 , ukdf['amount'].iloc[-1]=8409095.2881, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5954, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '60.176', 'enterprice': '16529.3', 'countrevence': '0', 'unrealprofit': '3111.0992', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '16477.6', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1


## /root/FIL/strategy/factorcheck/log.txt ----- -----

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=36, self.factor=0.47057262796380417, self.count=10096 

self.closeSec=1672387799, self.tradeDate='20221230', self.openTime='160500', self.closeTime='160959', self.symbol='BTCUSDT', self.open=16485.2, self.close=16477.7, self.high=16485.3, self.low=16473.5 
2022-12-30 16:10:01,443:INFO:factorcheck2:main.py:126:handleKline:185239: self.closeSec=1672387799, self.tradeDate='20221230', self.openTime='160500', self.closeTime='160959',self.symbol='BTCUSDT',self.open=16485.2, self.close=16477.7, self.high=16485.3, self.low=16473.5   
2022-12-30 16:10:01,472:INFO:factorcheck2:main.py:127:handleKline:185239: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime    closeSec  ...      low       pct  index  idx
1629  20221230   154500    154959  1672386599  ...  16470.3  0.000079   1629    3
1630  20221230   155000    155459  1672386899  ...  16472.7 -0.000400   1630    4
1631  20221230   155500    155959  1672387199  ...  16457.6 -0.000480   1631    5
1632  20221230   160000    160459  1672387499  ...  16466.6  0.001081   1632    0
1633  20221230   160500    160959  1672387799  ...  16473.5 -0.000461   1633    1

[5 rows x 11 columns]
2022-12-30 16:10:01,479:INFO:factorcheck2:main.py:128:handleKline:185239: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': True, 'isOpenSell': False, 'isCloseBuy': False, 'isCloseSell': False, 'isOpen': True, 'isClose': False, 'isTrig': True}

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=36, self.factor=0.47057262796380417, self.count=10097 

self.closeSec=1672388099, self.tradeDate='20221230', self.openTime='161000', self.closeTime='161459', self.symbol='BTCUSDT', self.open=16477.7, self.close=16477.7, self.high=16479.9, self.low=16474.0 
2022-12-30 16:15:00,529:INFO:factorcheck2:main.py:126:handleKline:185239: self.closeSec=1672388099, self.tradeDate='20221230', self.openTime='161000', self.closeTime='161459',self.symbol='BTCUSDT',self.open=16477.7, self.close=16477.7, self.high=16479.9, self.low=16474.0   
127.0.0.1 - - [30/Dec/2022 16:15:00] "POST / HTTP/1.1" 200 -
2022-12-30 16:15:00,543:INFO:factorcheck2:main.py:127:handleKline:185239: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime    closeSec  ...      low       pct  index  idx
1630  20221230   155000    155459  1672386899  ...  16472.7 -0.000400   1630    4
1631  20221230   155500    155959  1672387199  ...  16457.6 -0.000480   1631    5
1632  20221230   160000    160459  1672387499  ...  16466.6  0.001081   1632    0
1633  20221230   160500    160959  1672387799  ...  16473.5 -0.000461   1633    1
1634  20221230   161000    161459  1672388099  ...  16474.0  0.000000   1634    2

[5 rows x 11 columns]
2022-12-30 16:15:00,543:INFO:factorcheck2:main.py:128:handleKline:185239: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': True, 'isOpenSell': False, 'isCloseBuy': False, 'isCloseSell': False, 'isOpen': True, 'isClose': False, 'isTrig': True}


## /root/FIL/strategy/logic/log.txt ----- -----

2022-12-30 16:00:21,163:DEBUG:logic:main.py:454:getModel:174970: df_s.iloc[-5:,:] :
          date closeTime     open  ...    alpha58   alpha67   alpha72
5786  20221230    132959  16608.5  ...  43.750000  0.474036  0.378805
5787  20221230    135959  16589.0  ...  43.333333  0.445866  0.403293
5788  20221230    142959  16548.1  ...  43.750000  0.447836  0.425071
5789  20221230    145959  16550.6  ...  43.333333  0.438169  0.451952
5790  20221230    152959  16535.9  ...  43.333333  0.391770  0.475771

[5 rows x 33 columns]
0.5055350553505535
acc is : 0.5055350553505535
2022-12-30 16:00:21,271:INFO:logic:main.py:459:getModel:174970: df_pred.iloc[-5:,:] :
     pred    prob_0    prob_1  actual  ...       nav  sign  cost_        bm
537     1  0.492058  0.507942       0  ...  0.988560   1.0    0.0  0.986956
538     1  0.483878  0.516122       1  ...  0.988703   1.0    0.0  0.987100
539     1  0.492515  0.507485       0  ...  0.987831   1.0    0.0  0.986229
540     1  0.487624  0.512376       0  ...  0.983142   1.0    0.0  0.981547
541     1  0.464682  0.535318       1  ...  0.983650   1.0    0.0  0.982054

[5 rows x 10 columns]
2022-12-30 16:00:21,283:INFO:logic:main.py:469:getModel:174970: df_panel.iloc[-5:,:] :
    pred    prob_0    prob_1  actual  ...       nav  sign  cost_        bm
45     1  0.492112  0.507888       0  ...  0.988560   1.0    0.0  0.987722
46     1  0.483699  0.516301       1  ...  0.988703   1.0    0.0  0.986023
47     1  0.492554  0.507446       0  ...  0.987831   1.0    0.0  0.988386
48     1  0.487353  0.512647       0  ...  0.983142   1.0    0.0  0.980056
49     1  0.464682  0.535318       1  ...  0.983650   1.0    0.0  0.982054

[5 rows x 10 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '42.528', 'enterprice': '16701.5', 'countrevence': '0', 'unrealprofit': '-9828.2208', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '16470.4', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}


## /root/FIL/strategy/modifiedmom/log.txt ----- -----

526  20221230   154000    154959  1672386599  16493.8    16482 -0.000709
2022-12-30 15:50:00,582:INFO:modifiedmom:main.py:146:handleKline:185213: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': True, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True}

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=5047 

self.closeSec=1672387199, self.tradeDate='20221230', self.openTime='155000', self.closeTime='155959', self.symbol='BTCUSDT', self.open='16482.1', self.close='16467.5'
2022-12-30 16:00:01,215:INFO:modifiedmom:main.py:144:handleKline:185213: self.closeSec=1672387199, self.tradeDate='20221230', self.openTime='155000', self.closeTime='155959',self.symbol='BTCUSDT',self.open='16482.1', self.close='16467.5'
127.0.0.1 - - [30/Dec/2022 16:00:01] "POST / HTTP/1.1" 200 -
2022-12-30 16:00:01,305:INFO:modifiedmom:main.py:145:handleKline:185213: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec     open    close       pct
523  20221230   151000    151959  1672384799  16531.6    16521 -0.000641
524  20221230   152000    152959  1672385399  16520.9  16455.3 -0.003977
525  20221230   153000    153959  1672385999  16457.6  16493.7  0.002334
526  20221230   154000    154959  1672386599  16493.8    16482 -0.000709
527  20221230   155000    155959  1672387199  16482.1  16467.5 -0.000880
2022-12-30 16:00:01,305:INFO:modifiedmom:main.py:146:handleKline:185213: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': True, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True}
127.0.0.1 - - [30/Dec/2022 16:10:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=5048 

self.closeSec=1672387799, self.tradeDate='20221230', self.openTime='160000', self.closeTime='160959', self.symbol='BTCUSDT', self.open='16467.6', self.close='16477.7'
2022-12-30 16:10:01,545:INFO:modifiedmom:main.py:144:handleKline:185213: self.closeSec=1672387799, self.tradeDate='20221230', self.openTime='160000', self.closeTime='160959',self.symbol='BTCUSDT',self.open='16467.6', self.close='16477.7'
2022-12-30 16:10:01,576:INFO:modifiedmom:main.py:145:handleKline:185213: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec     open    close       pct
524  20221230   152000    152959  1672385399  16520.9  16455.3 -0.003977
525  20221230   153000    153959  1672385999  16457.6  16493.7  0.002334
526  20221230   154000    154959  1672386599  16493.8    16482 -0.000709
527  20221230   155000    155959  1672387199  16482.1  16467.5 -0.000880
528  20221230   160000    160959  1672387799  16467.6  16477.7  0.000619
2022-12-30 16:10:01,576:INFO:modifiedmom:main.py:146:handleKline:185213: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': True, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True}


## /root/FIL/strategy/pyemd/log.txt ----- -----

17518  20221230   154000    154959  1672386599  16493.8    16482
2022-12-30 15:50:00,575:INFO:pyemd2:main.py:127:handleKline:185189: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}
127.0.0.1 - - [30/Dec/2022 16:00:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=5048 

self.closeSec=1672387199, self.tradeDate='20221230', self.openTime='155000', self.closeTime='155959', self.symbol='BTCUSDT', self.open='16482.1', self.close='16467.5'
2022-12-30 16:00:01,239:INFO:pyemd2:main.py:125:handleKline:185189: self.closeSec=1672387199, self.tradeDate='20221230', self.openTime='155000', self.closeTime='155959',self.symbol='BTCUSDT',self.open='16482.1', self.close='16467.5'
2022-12-30 16:00:01,324:INFO:pyemd2:main.py:126:handleKline:185189: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
17515  20221230   151000    151959  1672384799  16531.6    16521
17516  20221230   152000    152959  1672385399  16520.9  16455.3
17517  20221230   153000    153959  1672385999  16457.6  16493.7
17518  20221230   154000    154959  1672386599  16493.8    16482
17519  20221230   155000    155959  1672387199  16482.1  16467.5
2022-12-30 16:00:01,325:INFO:pyemd2:main.py:127:handleKline:185189: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=5049 

self.closeSec=1672387799, self.tradeDate='20221230', self.openTime='160000', self.closeTime='160959', self.symbol='BTCUSDT', self.open='16467.6', self.close='16477.7'
127.0.0.1 - - [30/Dec/2022 16:10:01] "POST / HTTP/1.1" 200 -
2022-12-30 16:10:01,570:INFO:pyemd2:main.py:125:handleKline:185189: self.closeSec=1672387799, self.tradeDate='20221230', self.openTime='160000', self.closeTime='160959',self.symbol='BTCUSDT',self.open='16467.6', self.close='16477.7'
2022-12-30 16:10:01,583:INFO:pyemd2:main.py:126:handleKline:185189: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
17516  20221230   152000    152959  1672385399  16520.9  16455.3
17517  20221230   153000    153959  1672385999  16457.6  16493.7
17518  20221230   154000    154959  1672386599  16493.8    16482
17519  20221230   155000    155959  1672387199  16482.1  16467.5
17520  20221230   160000    160959  1672387799  16467.6  16477.7
2022-12-30 16:10:01,583:INFO:pyemd2:main.py:127:handleKline:185189: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}


## /root/FIL/strategy/similarity/log.txt ----- -----

12190  20221230   154000    154959  1672386599  16493.8    16482
2022-12-30 15:50:00,549:INFO:testStrategy:main.py:103:handleKline:185174: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': True, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True, 'isCorr': False}

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=5048 

self.closeSec=1672387199, self.tradeDate='20221230', self.openTime='155000', self.closeTime='155959', self.symbol='BTCUSDT', self.open='16482.1', self.close='16467.5'
127.0.0.1 - - [30/Dec/2022 16:00:01] "POST / HTTP/1.1" 200 -
2022-12-30 16:00:01,196:INFO:testStrategy:main.py:101:handleKline:185174: self.closeSec=1672387199, self.tradeDate='20221230', self.openTime='155000', self.closeTime='155959',self.symbol='BTCUSDT',self.open='16482.1', self.close='16467.5'
2022-12-30 16:00:01,205:INFO:testStrategy:main.py:102:handleKline:185174: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
12187  20221230   151000    151959  1672384799  16531.6    16521
12188  20221230   152000    152959  1672385399  16520.9  16455.3
12189  20221230   153000    153959  1672385999  16457.6  16493.7
12190  20221230   154000    154959  1672386599  16493.8    16482
12191  20221230   155000    155959  1672387199  16482.1  16467.5
2022-12-30 16:00:01,205:INFO:testStrategy:main.py:103:handleKline:185174: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': True, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True, 'isCorr': False}

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=5049 

self.closeSec=1672387799, self.tradeDate='20221230', self.openTime='160000', self.closeTime='160959', self.symbol='BTCUSDT', self.open='16467.6', self.close='16477.7'
2022-12-30 16:10:01,528:INFO:testStrategy:main.py:101:handleKline:185174: self.closeSec=1672387799, self.tradeDate='20221230', self.openTime='160000', self.closeTime='160959',self.symbol='BTCUSDT',self.open='16467.6', self.close='16477.7'
127.0.0.1 - - [30/Dec/2022 16:10:01] "POST / HTTP/1.1" 200 -
2022-12-30 16:10:01,561:INFO:testStrategy:main.py:102:handleKline:185174: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
12188  20221230   152000    152959  1672385399  16520.9  16455.3
12189  20221230   153000    153959  1672385999  16457.6  16493.7
12190  20221230   154000    154959  1672386599  16493.8    16482
12191  20221230   155000    155959  1672387199  16482.1  16467.5
12192  20221230   160000    160959  1672387799  16467.6  16477.7
2022-12-30 16:10:01,561:INFO:testStrategy:main.py:103:handleKline:185174: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': True, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True, 'isCorr': False}


## /root/FIL/strategy/sr_min/log.txt ----- -----

127.0.0.1 - - [30/Dec/2022 16:10:01] "POST / HTTP/1.1" 200 -
--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=0, self.total=1000000.0, self.flagDict['side']='', self.tradeCount=0, self.count=5528
self.closeSec=1672387799, self.tradeDate='20221230', self.openTime='160500', self.closeTime='160959', self.symbol='BTCUSDT', self.open=16485.2, self.close=16477.7, self.high=16485.3, self.low=16473.5, self.vol=735.124, self.amt=12114268.0597 
2022-12-30 16:10:01,494:INFO:sr_min:main.py:172:handleKline:449472: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5949  20221230   154500    154959  ...         0.0        0.0       0
5950  20221230   155000    155459  ...         0.0        0.0       0
5951  20221230   155500    155959  ...         0.0        0.0       0
5952  20221230   160000    160459  ...         0.0        0.0       0
5953  20221230   160500    160959  ...         0.0        0.0       0

[5 rows x 18 columns]
2022-12-30 16:10:01,495:INFO:sr_min:main.py:175:handleKline:449472: self.closeSec=1672387799, self.tradeDate='20221230', self.openTime='160500', self.closeTime='160959',self.symbol='BTCUSDT',self.open=16485.2, self.close=16477.7, self.high=16485.3, self.low=16473.5, self.vol=735.124, self.amt=12114268.0597, ukdf['pct'].iloc[-1]=-0.000461 , ukdf['amount'].iloc[-1]=12114268.0597, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5953, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': []}
type(curSign)=<class 'int'>, curSign=0, self.sign=0
--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=0, self.total=1000000.0, self.flagDict['side']='', self.tradeCount=0, self.count=5529
self.closeSec=1672388099, self.tradeDate='20221230', self.openTime='161000', self.closeTime='161459', self.symbol='BTCUSDT', self.open=16477.7, self.close=16477.7, self.high=16479.9, self.low=16474.0, self.vol=510.369, self.amt=8409095.2881 
127.0.0.1 - - [30/Dec/2022 16:15:00] "POST / HTTP/1.1" 200 -
2022-12-30 16:15:00,603:INFO:sr_min:main.py:172:handleKline:449472: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5950  20221230   155000    155459  ...         0.0        0.0       0
5951  20221230   155500    155959  ...         0.0        0.0       0
5952  20221230   160000    160459  ...         0.0        0.0       0
5953  20221230   160500    160959  ...         0.0        0.0       0
5954  20221230   161000    161459  ...         0.0        0.0       0

[5 rows x 18 columns]
2022-12-30 16:15:00,604:INFO:sr_min:main.py:175:handleKline:449472: self.closeSec=1672388099, self.tradeDate='20221230', self.openTime='161000', self.closeTime='161459',self.symbol='BTCUSDT',self.open=16477.7, self.close=16477.7, self.high=16479.9, self.low=16474.0, self.vol=510.369, self.amt=8409095.2881, ukdf['pct'].iloc[-1]=0.0 , ukdf['amount'].iloc[-1]=8409095.2881, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5954, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': []}
type(curSign)=<class 'int'>, curSign=0, self.sign=0


## /root/FIL/strategy/s_rsrs/log.txt ----- -----

721  20221230   040000    075959  1672358399  ...    721  0.637508  0.605011     1.0
722  20221230   080000    115959  1672372799  ...    722  0.648691  0.657817     1.0

[5 rows x 15 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '53.898', 'enterprice': '16630.1', 'countrevence': '0', 'unrealprofit': '-1923.94903325742', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '16594.40388821', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'numpy.int64'>, curSign=1, self.sign=1
127.0.0.1 - - [30/Dec/2022 16:00:01] "POST / HTTP/1.1" 200 -
--handleKline--:  version='2.0.0', self.name='s_rsrs', self.symbol='BTCUSDT', interval='4h', intervalSec=14400, wid=25, thd=0.6, self.sign=1, self.total=895432.8006702, self.flagDict['side']='buy', self.tradeCount=8, self.count=210
self.closeSec=1672387199, self.tradeDate='20221230', self.openTime='120000', self.closeTime='155959', self.symbol='BTCUSDT', self.open=16593.9, self.close=16467.5, self.high=16608.5, self.low=16410.0, self.vol=62732.71, self.amt=1035994592.7762 
2022-12-30 16:00:01,103:INFO:s_rsrs:main.py:141:handleKline:185271: self.closeSec=1672387199, self.tradeDate='20221230', self.openTime='120000', self.closeTime='155959',self.symbol='BTCUSDT',self.open=16593.9, self.close=16467.5, self.high=16608.5, self.low=16410.0, self.vol=62732.71, self.amt=1035994592.7762 
2022-12-30 16:00:01,150:INFO:s_rsrs:main.py:142:handleKline:185271: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime  ...        vol           amt       pct
719  20221229   200000    235959  ...  52351.625  8.702267e+08  0.000982
720  20221230   000000    035959  ...  26803.582  4.453796e+08 -0.000120
721  20221230   040000    075959  ...  32491.913  5.394451e+08  0.001337
722  20221230   080000    115959  ...  19882.213  3.302067e+08 -0.002189
723  20221230   120000    155959  ...  62732.710  1.035995e+09 -0.007617

[5 rows x 11 columns]
2022-12-30 16:00:02,729:INFO:s_rsrs:main.py:151:handleKline:185271: df_s.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec  ...  index      beta    zscore  signal
719  20221229   200000    235959  1672329599  ...    719  0.610035  0.494206     NaN
720  20221230   000000    035959  1672343999  ...    720  0.624418  0.549845     NaN
721  20221230   040000    075959  1672358399  ...    721  0.637508  0.605011     1.0
722  20221230   080000    115959  1672372799  ...    722  0.648691  0.657817     1.0
723  20221230   120000    155959  1672387199  ...    723  0.592312  0.542793     NaN

[5 rows x 15 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '53.898', 'enterprice': '16630.1', 'countrevence': '0', 'unrealprofit': '-8722.47647523252', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '16468.26697326', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'numpy.int64'>, curSign=-9223372036854775808, self.sign=1


