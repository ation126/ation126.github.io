# 20221219 16:16:02

## /root/FIL/strategy/amihud/log.txt ----- -----

127.0.0.1 - - [19/Dec/2022 16:10:01] "POST / HTTP/1.1" 200 -
--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=993672.4896432, self.flagDict['side']='sell', self.tradeCount=2, self.count=6362
self.closeSec=1671437399, self.tradeDate='20221219', self.openTime='160500', self.closeTime='160959', self.symbol='BTCUSDT', self.open=16718.7, self.close=16704.0, self.high=16726.2, self.low=16704.0, self.vol=623.461, self.amt=10423190.7576 
2022-12-19 16:10:01,474:INFO:amihud:main.py:172:handleKline:200676: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5949  20221219   154500    154959  ...         0.0        0.0       0
5950  20221219   155000    155459  ...         0.0        0.0       0
5951  20221219   155500    155959  ...         0.0        0.0       0
5952  20221219   160000    160459  ...         0.0        0.0       0
5953  20221219   160500    160959  ...         0.0        0.0       0

[5 rows x 18 columns]
2022-12-19 16:10:01,476:INFO:amihud:main.py:175:handleKline:200676: self.closeSec=1671437399, self.tradeDate='20221219', self.openTime='160500', self.closeTime='160959',self.symbol='BTCUSDT',self.open=16718.7, self.close=16704.0, self.high=16726.2, self.low=16704.0, self.vol=623.461, self.amt=10423190.7576, ukdf['pct'].iloc[-1]=-0.000879 , ukdf['amount'].iloc[-1]=10423190.7576, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5953, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '60.176', 'enterprice': '16529.3', 'countrevence': '0', 'unrealprofit': '-10456.05461774016', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '16703.05788716', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1
--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=993672.4896432, self.flagDict['side']='sell', self.tradeCount=2, self.count=6363
self.closeSec=1671437699, self.tradeDate='20221219', self.openTime='161000', self.closeTime='161459', self.symbol='BTCUSDT', self.open=16702.8, self.close=16707.8, self.high=16712.2, self.low=16702.7, self.vol=457.67, self.amt=7646295.7132 
127.0.0.1 - - [19/Dec/2022 16:15:00] "POST / HTTP/1.1" 200 -
2022-12-19 16:15:00,617:INFO:amihud:main.py:172:handleKline:200676: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5950  20221219   155000    155459  ...         0.0        0.0       0
5951  20221219   155500    155959  ...         0.0        0.0       0
5952  20221219   160000    160459  ...         0.0        0.0       0
5953  20221219   160500    160959  ...         0.0        0.0       0
5954  20221219   161000    161459  ...         0.0        0.0       0

[5 rows x 18 columns]
2022-12-19 16:15:00,617:INFO:amihud:main.py:175:handleKline:200676: self.closeSec=1671437699, self.tradeDate='20221219', self.openTime='161000', self.closeTime='161459',self.symbol='BTCUSDT',self.open=16702.8, self.close=16707.8, self.high=16712.2, self.low=16702.7, self.vol=457.67, self.amt=7646295.7132, ukdf['pct'].iloc[-1]=0.000227 , ukdf['amount'].iloc[-1]=7646295.7132, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5954, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '60.176', 'enterprice': '16529.3', 'countrevence': '0', 'unrealprofit': '-10797.44338111008', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '16708.73105858', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1


## /root/FIL/strategy/factorcheck/log.txt ----- -----


self.closeSec=1671437399, self.tradeDate='20221219', self.openTime='160500', self.closeTime='160959', self.symbol='BTCUSDT', self.open=16718.7, self.close=16704.0, self.high=16726.2, self.low=16704.0 
2022-12-19 16:10:01,433:INFO:factorcheck2:main.py:126:handleKline:185239: self.closeSec=1671437399, self.tradeDate='20221219', self.openTime='160500', self.closeTime='160959',self.symbol='BTCUSDT',self.open=16718.7, self.close=16704.0, self.high=16726.2, self.low=16704.0   
127.0.0.1 - - [19/Dec/2022 16:10:01] "POST / HTTP/1.1" 200 -
2022-12-19 16:10:01,464:INFO:factorcheck2:main.py:127:handleKline:185239: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime    closeSec  ...      low       pct  index  idx
1629  20221219   154500    154959  1671436199  ...  16694.6 -0.000640   1629    3
1630  20221219   155000    155459  1671436499  ...  16690.4  0.000018   1630    4
1631  20221219   155500    155959  1671436799  ...  16692.4  0.000832   1631    5
1632  20221219   160000    160459  1671437099  ...  16713.3  0.000257   1632    0
1633  20221219   160500    160959  1671437399  ...  16704.0 -0.000879   1633    1

[5 rows x 11 columns]
2022-12-19 16:10:01,464:INFO:factorcheck2:main.py:128:handleKline:185239: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': True, 'isOpenSell': False, 'isCloseBuy': False, 'isCloseSell': False, 'isOpen': True, 'isClose': False, 'isTrig': True}

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=26, self.factor=0.5575634763518096, self.count=6929 

self.closeSec=1671437699, self.tradeDate='20221219', self.openTime='161000', self.closeTime='161459', self.symbol='BTCUSDT', self.open=16702.8, self.close=16707.8, self.high=16712.2, self.low=16702.7 
127.0.0.1 - - [19/Dec/2022 16:15:00] "POST / HTTP/1.1" 200 -
2022-12-19 16:15:00,573:INFO:factorcheck2:main.py:126:handleKline:185239: self.closeSec=1671437699, self.tradeDate='20221219', self.openTime='161000', self.closeTime='161459',self.symbol='BTCUSDT',self.open=16702.8, self.close=16707.8, self.high=16712.2, self.low=16702.7   
2022-12-19 16:15:00,605:INFO:factorcheck2:main.py:127:handleKline:185239: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime    closeSec  ...      low       pct  index  idx
1630  20221219   155000    155459  1671436499  ...  16690.4  0.000018   1630    4
1631  20221219   155500    155959  1671436799  ...  16692.4  0.000832   1631    5
1632  20221219   160000    160459  1671437099  ...  16713.3  0.000257   1632    0
1633  20221219   160500    160959  1671437399  ...  16704.0 -0.000879   1633    1
1634  20221219   161000    161459  1671437699  ...  16702.7  0.000227   1634    2

[5 rows x 11 columns]
2022-12-19 16:15:00,605:INFO:factorcheck2:main.py:128:handleKline:185239: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': True, 'isOpenSell': False, 'isCloseBuy': False, 'isCloseSell': False, 'isOpen': True, 'isClose': False, 'isTrig': True}


## /root/FIL/strategy/logic/log.txt ----- -----

2022-12-19 16:00:18,681:DEBUG:logic:main.py:454:getModel:174970: df_s.iloc[-5:,:] :
          date closeTime     open  ...    alpha58   alpha67   alpha72
5786  20221219    132959  16702.5  ...  47.500000  0.466735  0.561121
5787  20221219    135959  16715.0  ...  47.083333  0.457769  0.570216
5788  20221219    142959  16696.6  ...  47.500000  0.462157  0.576663
5789  20221219    145959  16704.2  ...  47.500000  0.476365  0.575978
5790  20221219    152959  16729.6  ...  47.500000  0.479250  0.573960

[5 rows x 33 columns]
0.5608856088560885
acc is : 0.5608856088560885
2022-12-19 16:00:18,774:INFO:logic:main.py:459:getModel:174970: df_pred.iloc[-5:,:] :
     pred    prob_0    prob_1  actual  ...       nav  sign  cost_        bm
537     0  0.503476  0.496524       0  ...  1.107461  -1.0    0.0  0.993668
538     1  0.498237  0.501763       1  ...  1.106951  -1.0    0.0  0.994126
539     0  0.504999  0.495001       1  ...  1.105274  -1.0    0.0  0.995632
540     0  0.508852  0.491148       1  ...  1.104930  -1.0    0.0  0.995941
541     0  0.504810  0.495190       0  ...  1.106271  -1.0    0.0  0.994733

[5 rows x 10 columns]
2022-12-19 16:00:18,802:INFO:logic:main.py:469:getModel:174970: df_panel.iloc[-5:,:] :
    pred    prob_0    prob_1  actual  ...       nav  sign  cost_        bm
45     0  0.503264  0.496736       0  ...  1.107461  -1.0    0.0  0.991832
46     1  0.497963  0.502037       1  ...  1.106951  -1.0    0.0  0.991901
47     0  0.504995  0.495005       1  ...  1.105274  -1.0    0.0  0.994147
48     0  0.508546  0.491454       1  ...  1.104930  -1.0    0.0  0.992916
49     0  0.504810  0.495190       0  ...  1.106271  -1.0    0.0  0.994733

[5 rows x 10 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '37.704', 'enterprice': '17770', 'countrevence': '0', 'unrealprofit': '39743.7864', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '16715.9', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}


## /root/FIL/strategy/modifiedmom/log.txt ----- -----

526  20221219   154000    154959  1671436199  16710.4  16700.2 -0.000610
2022-12-19 15:50:00,563:INFO:modifiedmom:main.py:146:handleKline:185213: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': True, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True}
127.0.0.1 - - [19/Dec/2022 16:00:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=3463 

self.closeSec=1671436799, self.tradeDate='20221219', self.openTime='155000', self.closeTime='155959', self.symbol='BTCUSDT', self.open='16700.1', self.close='16714.4'
2022-12-19 16:00:01,217:INFO:modifiedmom:main.py:144:handleKline:185213: self.closeSec=1671436799, self.tradeDate='20221219', self.openTime='155000', self.closeTime='155959',self.symbol='BTCUSDT',self.open='16700.1', self.close='16714.4'
2022-12-19 16:00:01,249:INFO:modifiedmom:main.py:145:handleKline:185213: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec     open    close       pct
523  20221219   151000    151959  1671434399  16736.2  16725.6 -0.000633
524  20221219   152000    152959  1671434999  16725.6  16734.7  0.000544
525  20221219   153000    153959  1671435599  16734.7  16710.4 -0.001452
526  20221219   154000    154959  1671436199  16710.4  16700.2 -0.000610
527  20221219   155000    155959  1671436799  16700.1  16714.4  0.000850
2022-12-19 16:00:01,249:INFO:modifiedmom:main.py:146:handleKline:185213: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': True, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True}
127.0.0.1 - - [19/Dec/2022 16:10:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=3464 

self.closeSec=1671437399, self.tradeDate='20221219', self.openTime='160000', self.closeTime='160959', self.symbol='BTCUSDT', self.open='16714.5', self.close='16702.8'
2022-12-19 16:10:01,537:INFO:modifiedmom:main.py:144:handleKline:185213: self.closeSec=1671437399, self.tradeDate='20221219', self.openTime='160000', self.closeTime='160959',self.symbol='BTCUSDT',self.open='16714.5', self.close='16702.8'
2022-12-19 16:10:01,558:INFO:modifiedmom:main.py:145:handleKline:185213: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec     open    close       pct
524  20221219   152000    152959  1671434999  16725.6  16734.7  0.000544
525  20221219   153000    153959  1671435599  16734.7  16710.4 -0.001452
526  20221219   154000    154959  1671436199  16710.4  16700.2 -0.000610
527  20221219   155000    155959  1671436799  16700.1  16714.4  0.000850
528  20221219   160000    160959  1671437399  16714.5  16702.8 -0.000694
2022-12-19 16:10:01,559:INFO:modifiedmom:main.py:146:handleKline:185213: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': True, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True}


## /root/FIL/strategy/pyemd/log.txt ----- -----

17518  20221219   154000    154959  1671436199  16710.4  16700.2
2022-12-19 15:50:00,569:INFO:pyemd2:main.py:127:handleKline:185189: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}
127.0.0.1 - - [19/Dec/2022 16:00:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=3464 

self.closeSec=1671436799, self.tradeDate='20221219', self.openTime='155000', self.closeTime='155959', self.symbol='BTCUSDT', self.open='16700.1', self.close='16714.4'
2022-12-19 16:00:01,187:INFO:pyemd2:main.py:125:handleKline:185189: self.closeSec=1671436799, self.tradeDate='20221219', self.openTime='155000', self.closeTime='155959',self.symbol='BTCUSDT',self.open='16700.1', self.close='16714.4'
2022-12-19 16:00:01,246:INFO:pyemd2:main.py:126:handleKline:185189: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
17515  20221219   151000    151959  1671434399  16736.2  16725.6
17516  20221219   152000    152959  1671434999  16725.6  16734.7
17517  20221219   153000    153959  1671435599  16734.7  16710.4
17518  20221219   154000    154959  1671436199  16710.4  16700.2
17519  20221219   155000    155959  1671436799  16700.1  16714.4
2022-12-19 16:00:01,247:INFO:pyemd2:main.py:127:handleKline:185189: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=3465 

self.closeSec=1671437399, self.tradeDate='20221219', self.openTime='160000', self.closeTime='160959', self.symbol='BTCUSDT', self.open='16714.5', self.close='16702.8'
2022-12-19 16:10:01,521:INFO:pyemd2:main.py:125:handleKline:185189: self.closeSec=1671437399, self.tradeDate='20221219', self.openTime='160000', self.closeTime='160959',self.symbol='BTCUSDT',self.open='16714.5', self.close='16702.8'
127.0.0.1 - - [19/Dec/2022 16:10:01] "POST / HTTP/1.1" 200 -
2022-12-19 16:10:01,556:INFO:pyemd2:main.py:126:handleKline:185189: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
17516  20221219   152000    152959  1671434999  16725.6  16734.7
17517  20221219   153000    153959  1671435599  16734.7  16710.4
17518  20221219   154000    154959  1671436199  16710.4  16700.2
17519  20221219   155000    155959  1671436799  16700.1  16714.4
17520  20221219   160000    160959  1671437399  16714.5  16702.8
2022-12-19 16:10:01,556:INFO:pyemd2:main.py:127:handleKline:185189: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}


## /root/FIL/strategy/similarity/log.txt ----- -----

12190  20221219   154000    154959  1671436199  16710.4  16700.2
2022-12-19 15:50:00,556:INFO:testStrategy:main.py:103:handleKline:185174: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': True, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True, 'isCorr': False}
127.0.0.1 - - [19/Dec/2022 16:00:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=3464 

self.closeSec=1671436799, self.tradeDate='20221219', self.openTime='155000', self.closeTime='155959', self.symbol='BTCUSDT', self.open='16700.1', self.close='16714.4'
2022-12-19 16:00:01,180:INFO:testStrategy:main.py:101:handleKline:185174: self.closeSec=1671436799, self.tradeDate='20221219', self.openTime='155000', self.closeTime='155959',self.symbol='BTCUSDT',self.open='16700.1', self.close='16714.4'
2022-12-19 16:00:01,201:INFO:testStrategy:main.py:102:handleKline:185174: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
12187  20221219   151000    151959  1671434399  16736.2  16725.6
12188  20221219   152000    152959  1671434999  16725.6  16734.7
12189  20221219   153000    153959  1671435599  16734.7  16710.4
12190  20221219   154000    154959  1671436199  16710.4  16700.2
12191  20221219   155000    155959  1671436799  16700.1  16714.4
2022-12-19 16:00:01,219:INFO:testStrategy:main.py:103:handleKline:185174: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': True, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True, 'isCorr': False}
127.0.0.1 - - [19/Dec/2022 16:10:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=3465 

self.closeSec=1671437399, self.tradeDate='20221219', self.openTime='160000', self.closeTime='160959', self.symbol='BTCUSDT', self.open='16714.5', self.close='16702.8'
2022-12-19 16:10:01,528:INFO:testStrategy:main.py:101:handleKline:185174: self.closeSec=1671437399, self.tradeDate='20221219', self.openTime='160000', self.closeTime='160959',self.symbol='BTCUSDT',self.open='16714.5', self.close='16702.8'
2022-12-19 16:10:01,539:INFO:testStrategy:main.py:102:handleKline:185174: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
12188  20221219   152000    152959  1671434999  16725.6  16734.7
12189  20221219   153000    153959  1671435599  16734.7  16710.4
12190  20221219   154000    154959  1671436199  16710.4  16700.2
12191  20221219   155000    155959  1671436799  16700.1  16714.4
12192  20221219   160000    160959  1671437399  16714.5  16702.8
2022-12-19 16:10:01,539:INFO:testStrategy:main.py:103:handleKline:185174: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': True, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True, 'isCorr': False}


## /root/FIL/strategy/sr_min/log.txt ----- -----

--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=0, self.total=1000000.0, self.flagDict['side']='', self.tradeCount=0, self.count=2360
self.closeSec=1671437399, self.tradeDate='20221219', self.openTime='160500', self.closeTime='160959', self.symbol='BTCUSDT', self.open=16718.7, self.close=16704.0, self.high=16726.2, self.low=16704.0, self.vol=623.461, self.amt=10423190.7576 
127.0.0.1 - - [19/Dec/2022 16:10:01] "POST / HTTP/1.1" 200 -
2022-12-19 16:10:01,477:INFO:sr_min:main.py:172:handleKline:449472: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5949  20221219   154500    154959  ...         0.0        0.0       0
5950  20221219   155000    155459  ...         0.0        0.0       0
5951  20221219   155500    155959  ...         0.0        0.0       0
5952  20221219   160000    160459  ...         0.0        0.0       0
5953  20221219   160500    160959  ...         0.0        0.0       0

[5 rows x 18 columns]
2022-12-19 16:10:01,483:INFO:sr_min:main.py:175:handleKline:449472: self.closeSec=1671437399, self.tradeDate='20221219', self.openTime='160500', self.closeTime='160959',self.symbol='BTCUSDT',self.open=16718.7, self.close=16704.0, self.high=16726.2, self.low=16704.0, self.vol=623.461, self.amt=10423190.7576, ukdf['pct'].iloc[-1]=-0.000879 , ukdf['amount'].iloc[-1]=10423190.7576, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5953, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': []}
type(curSign)=<class 'int'>, curSign=0, self.sign=0
127.0.0.1 - - [19/Dec/2022 16:15:00] "POST / HTTP/1.1" 200 -
--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=0, self.total=1000000.0, self.flagDict['side']='', self.tradeCount=0, self.count=2361
self.closeSec=1671437699, self.tradeDate='20221219', self.openTime='161000', self.closeTime='161459', self.symbol='BTCUSDT', self.open=16702.8, self.close=16707.8, self.high=16712.2, self.low=16702.7, self.vol=457.67, self.amt=7646295.7132 
2022-12-19 16:15:00,638:INFO:sr_min:main.py:172:handleKline:449472: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5950  20221219   155000    155459  ...         0.0        0.0       0
5951  20221219   155500    155959  ...         0.0        0.0       0
5952  20221219   160000    160459  ...         0.0        0.0       0
5953  20221219   160500    160959  ...         0.0        0.0       0
5954  20221219   161000    161459  ...         0.0        0.0       0

[5 rows x 18 columns]
2022-12-19 16:15:00,639:INFO:sr_min:main.py:175:handleKline:449472: self.closeSec=1671437699, self.tradeDate='20221219', self.openTime='161000', self.closeTime='161459',self.symbol='BTCUSDT',self.open=16702.8, self.close=16707.8, self.high=16712.2, self.low=16702.7, self.vol=457.67, self.amt=7646295.7132, ukdf['pct'].iloc[-1]=0.000227 , ukdf['amount'].iloc[-1]=7646295.7132, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5954, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': []}
type(curSign)=<class 'int'>, curSign=0, self.sign=0


## /root/FIL/strategy/s_rsrs/log.txt ----- -----

721  20221219   040000    075959  1671407999  ...    721  0.986301  0.804651     1.0
722  20221219   080000    115959  1671422399  ...    722  0.938078  0.640522     1.0

[5 rows x 15 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '53.436', 'enterprice': '17756.3', 'countrevence': '0', 'unrealprofit': '-57860.5008', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '16673.5', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'numpy.int64'>, curSign=1, self.sign=1
127.0.0.1 - - [19/Dec/2022 16:00:01] "POST / HTTP/1.1" 200 -
--handleKline--:  version='2.0.0', self.name='s_rsrs', self.symbol='BTCUSDT', interval='4h', intervalSec=14400, wid=25, thd=0.6, self.sign=1, self.total=947876.8211532, self.flagDict['side']='buy', self.tradeCount=6, self.count=144
self.closeSec=1671436799, self.tradeDate='20221219', self.openTime='120000', self.closeTime='155959', self.symbol='BTCUSDT', self.open=16673.5, self.close=16714.4, self.high=16744.0, self.low=16664.0, self.vol=28214.603, self.amt=471400027.3681 
2022-12-19 16:00:01,076:INFO:s_rsrs:main.py:141:handleKline:185271: self.closeSec=1671436799, self.tradeDate='20221219', self.openTime='120000', self.closeTime='155959',self.symbol='BTCUSDT',self.open=16673.5, self.close=16714.4, self.high=16744.0, self.low=16664.0, self.vol=28214.603, self.amt=471400027.3681 
2022-12-19 16:00:01,129:INFO:s_rsrs:main.py:142:handleKline:185271: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime  ...        vol           amt       pct
719  20221218   200000    235959  ...  25280.386  4.220179e+08 -0.001545
720  20221219   000000    035959  ...  41996.189  7.028551e+08  0.004150
721  20221219   040000    075959  ...  37334.568  6.261975e+08 -0.000914
722  20221219   080000    115959  ...  49601.728  8.289811e+08 -0.003389
723  20221219   120000    155959  ...  28214.603  4.714000e+08  0.002447

[5 rows x 11 columns]
2022-12-19 16:00:02,684:INFO:s_rsrs:main.py:151:handleKline:185271: df_s.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec  ...  index      beta    zscore  signal
719  20221218   200000    235959  1671379199  ...    719  1.132630  1.292668     1.0
720  20221219   000000    035959  1671393599  ...    720  1.127079  1.248861     1.0
721  20221219   040000    075959  1671407999  ...    721  0.986301  0.804651     1.0
722  20221219   080000    115959  1671422399  ...    722  0.938078  0.640522     1.0
723  20221219   120000    155959  1671436799  ...    723  0.895413  0.487981     NaN

[5 rows x 15 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '53.436', 'enterprice': '17756.3', 'countrevence': '0', 'unrealprofit': '-55669.6248', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '16714.5', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'numpy.int64'>, curSign=-9223372036854775808, self.sign=1


