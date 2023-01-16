# 20230116 16:16:01

## /root/FIL/strategy/amihud/log.txt ----- -----

--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=993672.4896432, self.flagDict['side']='sell', self.tradeCount=2, self.count=14426
self.closeSec=1673856599, self.tradeDate='20230116', self.openTime='160500', self.closeTime='160959', self.symbol='BTCUSDT', self.open=21112.5, self.close=20691.1, self.high=21117.3, self.low=20691.1, self.vol=17655.376, self.amt=368215771.71719 
127.0.0.1 - - [16/Jan/2023 16:10:01] "POST / HTTP/1.1" 200 -
2023-01-16 16:10:01,508:INFO:amihud:main.py:172:handleKline:200676: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5949  20230116   154500    154959  ...         0.0        0.0       0
5950  20230116   155000    155459  ...         0.0        0.0       0
5951  20230116   155500    155959  ...         0.0        0.0       0
5952  20230116   160000    160459  ...         0.0        0.0       0
5953  20230116   160500    160959  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-01-16 16:10:01,509:INFO:amihud:main.py:175:handleKline:200676: self.closeSec=1673856599, self.tradeDate='20230116', self.openTime='160500', self.closeTime='160959',self.symbol='BTCUSDT',self.open=21112.5, self.close=20691.1, self.high=21117.3, self.low=20691.1, self.vol=17655.376, self.amt=368215771.71719, ukdf['pct'].iloc[-1]=-0.01996 , ukdf['amount'].iloc[-1]=368215771.71719, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5953, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '60.176', 'enterprice': '16529.3', 'countrevence': '0', 'unrealprofit': '-249663.68345912656', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '20678.19130981', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1
127.0.0.1 - - [16/Jan/2023 16:15:00] "POST / HTTP/1.1" 200 -
--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=993672.4896432, self.flagDict['side']='sell', self.tradeCount=2, self.count=14427
self.closeSec=1673856899, self.tradeDate='20230116', self.openTime='161000', self.closeTime='161459', self.symbol='BTCUSDT', self.open=20670.0, self.close=20804.2, self.high=20820.1, self.low=20619.0, self.vol=13401.562, self.amt=278149201.00012 
2023-01-16 16:15:00,840:INFO:amihud:main.py:172:handleKline:200676: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5950  20230116   155000    155459  ...         0.0        0.0       0
5951  20230116   155500    155959  ...         0.0        0.0       0
5952  20230116   160000    160459  ...         0.0        0.0       0
5953  20230116   160500    160959  ...         0.0        0.0       0
5954  20230116   161000    161459  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-01-16 16:15:00,843:INFO:amihud:main.py:175:handleKline:200676: self.closeSec=1673856899, self.tradeDate='20230116', self.openTime='161000', self.closeTime='161459',self.symbol='BTCUSDT',self.open=20670.0, self.close=20804.2, self.high=20820.1, self.low=20619.0, self.vol=13401.562, self.amt=278149201.00012, ukdf['pct'].iloc[-1]=0.005466 , ukdf['amount'].iloc[-1]=278149201.00012, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5954, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '60.176', 'enterprice': '16529.3', 'countrevence': '0', 'unrealprofit': '-256951.52', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '20799.3', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1


## /root/FIL/strategy/factorcheck/log.txt ----- -----

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=415, self.factor=0.37131070944096484, self.count=14992 

self.closeSec=1673856599, self.tradeDate='20230116', self.openTime='160500', self.closeTime='160959', self.symbol='BTCUSDT', self.open=21112.5, self.close=20691.1, self.high=21117.3, self.low=20691.1 
2023-01-16 16:10:01,411:INFO:factorcheck2:main.py:126:handleKline:185239: self.closeSec=1673856599, self.tradeDate='20230116', self.openTime='160500', self.closeTime='160959',self.symbol='BTCUSDT',self.open=21112.5, self.close=20691.1, self.high=21117.3, self.low=20691.1   
2023-01-16 16:10:01,471:INFO:factorcheck2:main.py:127:handleKline:185239: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime    closeSec  ...      low       pct  index  idx
1629  20230116   154500    154959  1673855399  ...  21073.2 -0.000199   1629    3
1630  20230116   155000    155459  1673855699  ...  21082.1  0.001243   1630    4
1631  20230116   155500    155959  1673855999  ...  21104.7  0.000327   1631    5
1632  20230116   160000    160459  1673856299  ...  21097.5 -0.000166   1632    0
1633  20230116   160500    160959  1673856599  ...  20691.1 -0.019960   1633    1

[5 rows x 11 columns]
2023-01-16 16:10:01,471:INFO:factorcheck2:main.py:128:handleKline:185239: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}
127.0.0.1 - - [16/Jan/2023 16:15:00] "POST / HTTP/1.1" 200 -

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=415, self.factor=0.37131070944096484, self.count=14993 

self.closeSec=1673856899, self.tradeDate='20230116', self.openTime='161000', self.closeTime='161459', self.symbol='BTCUSDT', self.open=20670.0, self.close=20804.2, self.high=20820.1, self.low=20619.0 
2023-01-16 16:15:00,703:INFO:factorcheck2:main.py:126:handleKline:185239: self.closeSec=1673856899, self.tradeDate='20230116', self.openTime='161000', self.closeTime='161459',self.symbol='BTCUSDT',self.open=20670.0, self.close=20804.2, self.high=20820.1, self.low=20619.0   
2023-01-16 16:15:00,750:INFO:factorcheck2:main.py:127:handleKline:185239: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime    closeSec  ...      low       pct  index  idx
1630  20230116   155000    155459  1673855699  ...  21082.1  0.001243   1630    4
1631  20230116   155500    155959  1673855999  ...  21104.7  0.000327   1631    5
1632  20230116   160000    160459  1673856299  ...  21097.5 -0.000166   1632    0
1633  20230116   160500    160959  1673856599  ...  20691.1 -0.019960   1633    1
1634  20230116   161000    161459  1673856899  ...  20619.0  0.005466   1634    2

[5 rows x 11 columns]
2023-01-16 16:15:00,756:INFO:factorcheck2:main.py:128:handleKline:185239: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}


## /root/FIL/strategy/logic/log.txt ----- -----

2023-01-16 16:00:35,442:DEBUG:logic:main.py:456:getModel:726423: df_s.iloc[-5:,:] :
          date closeTime     open  ...    alpha58   alpha67   alpha72
5786  20230116    132959  21160.2  ...  54.166667  0.586922  0.375571
5787  20230116    135959  21154.9  ...  54.583333  0.592493  0.372008
5788  20230116    142959  21195.5  ...  54.166667  0.584685  0.372007
5789  20230116    145959  21156.4  ...  54.166667  0.584969  0.371836
5790  20230116    152959  21158.1  ...  53.750000  0.575531  0.375652

[5 rows x 33 columns]
0.518450184501845
acc is : 0.518450184501845
2023-01-16 16:00:35,609:INFO:logic:main.py:461:getModel:726423: df_pred.iloc[-5:,:] :
     pred    prob_0    prob_1  actual  ...       nav  sign  cost_        bm
537     0  0.503744  0.496256       1  ...  1.104260   1.0    0.0  1.260146
538     0  0.522764  0.477236       0  ...  1.102212   1.0    0.0  1.257809
539     0  0.506966  0.493034       1  ...  1.102316   1.0    0.0  1.257928
540     0  0.514373  0.485627       0  ...  1.099868   1.0    0.0  1.255134
541     1  0.491628  0.508372       1  ...  1.100123   1.0    0.0  1.255425

[5 rows x 10 columns]
2023-01-16 16:00:35,645:INFO:logic:main.py:471:getModel:726423: df_panel.iloc[-5:,:] :
    pred    prob_0    prob_1  actual  ...       nav  sign  cost_        bm
45     0  0.503722  0.496278       1  ...  1.104260   1.0    0.0  1.260228
46     0  0.522818  0.477182       0  ...  1.102212   1.0    0.0  1.255965
47     0  0.506967  0.493033       1  ...  1.102316   1.0    0.0  1.256263
48     0  0.514363  0.485637       0  ...  1.099868   1.0    0.0  1.252297
49     1  0.491628  0.508372       1  ...  1.100123   1.0    0.0  1.255425

[5 rows x 10 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': []}


## /root/FIL/strategy/modifiedmom/log.txt ----- -----

526  20230116   154000    154959  1673855399  21102.2  21082.9 -0.000910
2023-01-16 15:50:00,837:INFO:modifiedmom:main.py:146:handleKline:185213: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': True, 'isOpenSell': False, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True}
127.0.0.1 - - [16/Jan/2023 16:00:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=7495 

self.closeSec=1673855999, self.tradeDate='20230116', self.openTime='155000', self.closeTime='155959', self.symbol='BTCUSDT', self.open='21085.2', self.close='21116'
2023-01-16 16:00:01,459:INFO:modifiedmom:main.py:144:handleKline:185213: self.closeSec=1673855999, self.tradeDate='20230116', self.openTime='155000', self.closeTime='155959',self.symbol='BTCUSDT',self.open='21085.2', self.close='21116'
2023-01-16 16:00:01,526:INFO:modifiedmom:main.py:145:handleKline:185213: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec     open    close       pct
523  20230116   151000    151959  1673853599  21105.4  21108.5  0.000123
524  20230116   152000    152959  1673854199  21108.4  21111.1  0.000123
525  20230116   153000    153959  1673854799    21111  21102.1 -0.000426
526  20230116   154000    154959  1673855399  21102.2  21082.9 -0.000910
527  20230116   155000    155959  1673855999  21085.2    21116  0.001570
2023-01-16 16:00:01,526:INFO:modifiedmom:main.py:146:handleKline:185213: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': True, 'isOpenSell': False, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True}
127.0.0.1 - - [16/Jan/2023 16:10:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=7496 

self.closeSec=1673856599, self.tradeDate='20230116', self.openTime='160000', self.closeTime='160959', self.symbol='BTCUSDT', self.open='21116', self.close='20691.1'
2023-01-16 16:10:01,554:INFO:modifiedmom:main.py:144:handleKline:185213: self.closeSec=1673856599, self.tradeDate='20230116', self.openTime='160000', self.closeTime='160959',self.symbol='BTCUSDT',self.open='21116', self.close='20691.1'
2023-01-16 16:10:01,584:INFO:modifiedmom:main.py:145:handleKline:185213: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec     open    close       pct
524  20230116   152000    152959  1673854199  21108.4  21111.1  0.000123
525  20230116   153000    153959  1673854799    21111  21102.1 -0.000426
526  20230116   154000    154959  1673855399  21102.2  21082.9 -0.000910
527  20230116   155000    155959  1673855999  21085.2    21116  0.001570
528  20230116   160000    160959  1673856599    21116  20691.1 -0.020122
2023-01-16 16:10:01,585:INFO:modifiedmom:main.py:146:handleKline:185213: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': True, 'isOpenSell': False, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True}


## /root/FIL/strategy/pyemd/log.txt ----- -----

17518  20230116   154000    154959  1673855399  21102.2  21082.9
2023-01-16 15:50:00,843:INFO:pyemd2:main.py:127:handleKline:185189: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}
127.0.0.1 - - [16/Jan/2023 16:00:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=7496 

self.closeSec=1673855999, self.tradeDate='20230116', self.openTime='155000', self.closeTime='155959', self.symbol='BTCUSDT', self.open='21085.2', self.close='21116'
2023-01-16 16:00:01,508:INFO:pyemd2:main.py:125:handleKline:185189: self.closeSec=1673855999, self.tradeDate='20230116', self.openTime='155000', self.closeTime='155959',self.symbol='BTCUSDT',self.open='21085.2', self.close='21116'
2023-01-16 16:00:01,530:INFO:pyemd2:main.py:126:handleKline:185189: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
17515  20230116   151000    151959  1673853599  21105.4  21108.5
17516  20230116   152000    152959  1673854199  21108.4  21111.1
17517  20230116   153000    153959  1673854799    21111  21102.1
17518  20230116   154000    154959  1673855399  21102.2  21082.9
17519  20230116   155000    155959  1673855999  21085.2    21116
2023-01-16 16:00:01,530:INFO:pyemd2:main.py:127:handleKline:185189: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}
127.0.0.1 - - [16/Jan/2023 16:10:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=7497 

self.closeSec=1673856599, self.tradeDate='20230116', self.openTime='160000', self.closeTime='160959', self.symbol='BTCUSDT', self.open='21116', self.close='20691.1'
2023-01-16 16:10:01,591:INFO:pyemd2:main.py:125:handleKline:185189: self.closeSec=1673856599, self.tradeDate='20230116', self.openTime='160000', self.closeTime='160959',self.symbol='BTCUSDT',self.open='21116', self.close='20691.1'
2023-01-16 16:10:01,620:INFO:pyemd2:main.py:126:handleKline:185189: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
17516  20230116   152000    152959  1673854199  21108.4  21111.1
17517  20230116   153000    153959  1673854799    21111  21102.1
17518  20230116   154000    154959  1673855399  21102.2  21082.9
17519  20230116   155000    155959  1673855999  21085.2    21116
17520  20230116   160000    160959  1673856599    21116  20691.1
2023-01-16 16:10:01,621:INFO:pyemd2:main.py:127:handleKline:185189: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}


## /root/FIL/strategy/similarity/log.txt ----- -----

12190  20230116   154000    154959  1673855399  21102.2  21082.9
2023-01-16 15:50:00,804:INFO:testStrategy:main.py:103:handleKline:185174: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': True, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True, 'isCorr': False}

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=7496 

self.closeSec=1673855999, self.tradeDate='20230116', self.openTime='155000', self.closeTime='155959', self.symbol='BTCUSDT', self.open='21085.2', self.close='21116'
2023-01-16 16:00:01,455:INFO:testStrategy:main.py:101:handleKline:185174: self.closeSec=1673855999, self.tradeDate='20230116', self.openTime='155000', self.closeTime='155959',self.symbol='BTCUSDT',self.open='21085.2', self.close='21116'
2023-01-16 16:00:01,461:INFO:testStrategy:main.py:102:handleKline:185174: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
12187  20230116   151000    151959  1673853599  21105.4  21108.5
12188  20230116   152000    152959  1673854199  21108.4  21111.1
12189  20230116   153000    153959  1673854799    21111  21102.1
12190  20230116   154000    154959  1673855399  21102.2  21082.9
12191  20230116   155000    155959  1673855999  21085.2    21116
127.0.0.1 - - [16/Jan/2023 16:00:01] "POST / HTTP/1.1" 200 -
2023-01-16 16:00:01,482:INFO:testStrategy:main.py:103:handleKline:185174: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': True, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True, 'isCorr': False}

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=7497 

self.closeSec=1673856599, self.tradeDate='20230116', self.openTime='160000', self.closeTime='160959', self.symbol='BTCUSDT', self.open='21116', self.close='20691.1'
2023-01-16 16:10:01,550:INFO:testStrategy:main.py:101:handleKline:185174: self.closeSec=1673856599, self.tradeDate='20230116', self.openTime='160000', self.closeTime='160959',self.symbol='BTCUSDT',self.open='21116', self.close='20691.1'
127.0.0.1 - - [16/Jan/2023 16:10:01] "POST / HTTP/1.1" 200 -
2023-01-16 16:10:01,580:INFO:testStrategy:main.py:102:handleKline:185174: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
12188  20230116   152000    152959  1673854199  21108.4  21111.1
12189  20230116   153000    153959  1673854799    21111  21102.1
12190  20230116   154000    154959  1673855399  21102.2  21082.9
12191  20230116   155000    155959  1673855999  21085.2    21116
12192  20230116   160000    160959  1673856599    21116  20691.1
2023-01-16 16:10:01,580:INFO:testStrategy:main.py:103:handleKline:185174: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': True, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True, 'isCorr': False}


## /root/FIL/strategy/sr_min/log.txt ----- -----

127.0.0.1 - - [16/Jan/2023 16:10:01] "POST / HTTP/1.1" 200 -
--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=0, self.total=1000000.0, self.flagDict['side']='', self.tradeCount=0, self.count=10424
self.closeSec=1673856599, self.tradeDate='20230116', self.openTime='160500', self.closeTime='160959', self.symbol='BTCUSDT', self.open=21112.5, self.close=20691.1, self.high=21117.3, self.low=20691.1, self.vol=17655.376, self.amt=368215771.71719 
2023-01-16 16:10:01,489:INFO:sr_min:main.py:172:handleKline:449472: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5949  20230116   154500    154959  ...         0.0        0.0       0
5950  20230116   155000    155459  ...         0.0        0.0       0
5951  20230116   155500    155959  ...         0.0        0.0       0
5952  20230116   160000    160459  ...         0.0        0.0       0
5953  20230116   160500    160959  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-01-16 16:10:01,489:INFO:sr_min:main.py:175:handleKline:449472: self.closeSec=1673856599, self.tradeDate='20230116', self.openTime='160500', self.closeTime='160959',self.symbol='BTCUSDT',self.open=21112.5, self.close=20691.1, self.high=21117.3, self.low=20691.1, self.vol=17655.376, self.amt=368215771.71719, ukdf['pct'].iloc[-1]=-0.01996 , ukdf['amount'].iloc[-1]=368215771.71719, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5953, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': []}
type(curSign)=<class 'int'>, curSign=0, self.sign=0
127.0.0.1 - - [16/Jan/2023 16:15:00] "POST / HTTP/1.1" 200 -
--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=0, self.total=1000000.0, self.flagDict['side']='', self.tradeCount=0, self.count=10425
self.closeSec=1673856899, self.tradeDate='20230116', self.openTime='161000', self.closeTime='161459', self.symbol='BTCUSDT', self.open=20670.0, self.close=20804.2, self.high=20820.1, self.low=20619.0, self.vol=13401.562, self.amt=278149201.00012 
2023-01-16 16:15:00,811:INFO:sr_min:main.py:172:handleKline:449472: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5950  20230116   155000    155459  ...         0.0        0.0       0
5951  20230116   155500    155959  ...         0.0        0.0       0
5952  20230116   160000    160459  ...         0.0        0.0       0
5953  20230116   160500    160959  ...         0.0        0.0       0
5954  20230116   161000    161459  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-01-16 16:15:00,812:INFO:sr_min:main.py:175:handleKline:449472: self.closeSec=1673856899, self.tradeDate='20230116', self.openTime='161000', self.closeTime='161459',self.symbol='BTCUSDT',self.open=20670.0, self.close=20804.2, self.high=20820.1, self.low=20619.0, self.vol=13401.562, self.amt=278149201.00012, ukdf['pct'].iloc[-1]=0.005466 , ukdf['amount'].iloc[-1]=278149201.00012, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5954, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': []}
type(curSign)=<class 'int'>, curSign=0, self.sign=0


## /root/FIL/strategy/s_rsrs/log.txt ----- -----

721  20230116   040000    075959  1673827199  ...    721  0.901201  0.351053     NaN
722  20230116   080000    115959  1673841599  ...    722  0.919980  0.377256     NaN

[5 rows x 15 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '51.136', 'enterprice': '17188.2', 'countrevence': '0', 'unrealprofit': '199333.05168703232', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '21086.29628612', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'numpy.int64'>, curSign=-9223372036854775808, self.sign=1
--handleKline--:  version='2.0.0', self.name='s_rsrs', self.symbol='BTCUSDT', interval='4h', intervalSec=14400, wid=25, thd=0.6, self.sign=1, self.total=878056.8594048, self.flagDict['side']='buy', self.tradeCount=12, self.count=312
self.closeSec=1673855999, self.tradeDate='20230116', self.openTime='120000', self.closeTime='155959', self.symbol='BTCUSDT', self.open=21084.3, self.close=21116.0, self.high=21276.0, self.low=21048.0, self.vol=55958.606, self.amt=1183353001.5887 
2023-01-16 16:00:01,213:INFO:s_rsrs:main.py:141:handleKline:185271: self.closeSec=1673855999, self.tradeDate='20230116', self.openTime='120000', self.closeTime='155959',self.symbol='BTCUSDT',self.open=21084.3, self.close=21116.0, self.high=21276.0, self.low=21048.0, self.vol=55958.606, self.amt=1183353001.5887 
127.0.0.1 - - [16/Jan/2023 16:00:01] "POST / HTTP/1.1" 200 -
2023-01-16 16:00:01,249:INFO:s_rsrs:main.py:142:handleKline:185271: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime  ...         vol           amt       pct
719  20230115   200000    235959  ...   82799.747  1.724175e+09  0.009181
720  20230116   000000    035959  ...  106046.834  2.214465e+09 -0.002418
721  20230116   040000    075959  ...   44695.035  9.332903e+08  0.000263
722  20230116   080000    115959  ...  175271.412  3.707107e+09  0.009654
723  20230116   120000    155959  ...   55958.606  1.183353e+09  0.001503

[5 rows x 11 columns]
2023-01-16 16:00:03,320:INFO:s_rsrs:main.py:151:handleKline:185271: df_s.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec  ...  index      beta    zscore  signal
719  20230115   200000    235959  1673798399  ...    719  0.985609  0.573577     NaN
720  20230116   000000    035959  1673812799  ...    720  0.949314  0.476058     NaN
721  20230116   040000    075959  1673827199  ...    721  0.901201  0.351053     NaN
722  20230116   080000    115959  1673841599  ...    722  0.919980  0.377256     NaN
723  20230116   120000    155959  1673855999  ...    723  0.902588  0.320094     NaN

[5 rows x 15 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '51.136', 'enterprice': '17188.2', 'countrevence': '0', 'unrealprofit': '200851.9808', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '21116', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'numpy.int64'>, curSign=-9223372036854775808, self.sign=1


