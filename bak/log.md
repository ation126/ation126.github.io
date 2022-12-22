# 20221222 16:16:01

## /root/FIL/strategy/amihud/log.txt ----- -----

--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=993672.4896432, self.flagDict['side']='sell', self.tradeCount=2, self.count=7226
self.closeSec=1671696599, self.tradeDate='20221222', self.openTime='160500', self.closeTime='160959', self.symbol='BTCUSDT', self.open=16795.2, self.close=16808.1, self.high=16809.9, self.low=16795.2, self.vol=367.517, self.amt=6174432.2137 
127.0.0.1 - - [22/Dec/2022 16:10:01] "POST / HTTP/1.1" 200 -
2022-12-22 16:10:01,503:INFO:amihud:main.py:172:handleKline:200676: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5949  20221222   154500    154959  ...         0.0        0.0       0
5950  20221222   155000    155459  ...         0.0        0.0       0
5951  20221222   155500    155959  ...         0.0        0.0       0
5952  20221222   160000    160459  ...         0.0        0.0       0
5953  20221222   160500    160959  ...         0.0        0.0       0

[5 rows x 18 columns]
2022-12-22 16:10:01,503:INFO:amihud:main.py:175:handleKline:200676: self.closeSec=1671696599, self.tradeDate='20221222', self.openTime='160500', self.closeTime='160959',self.symbol='BTCUSDT',self.open=16795.2, self.close=16808.1, self.high=16809.9, self.low=16795.2, self.vol=367.517, self.amt=6174432.2137, ukdf['pct'].iloc[-1]=0.000768 , ukdf['amount'].iloc[-1]=6174432.2137, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5953, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '60.176', 'enterprice': '16529.3', 'countrevence': '0', 'unrealprofit': '-16783.0864', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '16808.2', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1
127.0.0.1 - - [22/Dec/2022 16:15:00] "POST / HTTP/1.1" 200 -
--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=993672.4896432, self.flagDict['side']='sell', self.tradeCount=2, self.count=7227
self.closeSec=1671696899, self.tradeDate='20221222', self.openTime='161000', self.closeTime='161459', self.symbol='BTCUSDT', self.open=16808.2, self.close=16810.5, self.high=16811.3, self.low=16808.1, self.vol=251.615, self.amt=4229555.3564 
2022-12-22 16:15:00,615:INFO:amihud:main.py:172:handleKline:200676: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5950  20221222   155000    155459  ...         0.0        0.0       0
5951  20221222   155500    155959  ...         0.0        0.0       0
5952  20221222   160000    160459  ...         0.0        0.0       0
5953  20221222   160500    160959  ...         0.0        0.0       0
5954  20221222   161000    161459  ...         0.0        0.0       0

[5 rows x 18 columns]
2022-12-22 16:15:00,615:INFO:amihud:main.py:175:handleKline:200676: self.closeSec=1671696899, self.tradeDate='20221222', self.openTime='161000', self.closeTime='161459',self.symbol='BTCUSDT',self.open=16808.2, self.close=16810.5, self.high=16811.3, self.low=16808.1, self.vol=251.615, self.amt=4229555.3564, ukdf['pct'].iloc[-1]=0.000143 , ukdf['amount'].iloc[-1]=4229555.3564, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5954, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '60.176', 'enterprice': '16529.3', 'countrevence': '0', 'unrealprofit': '-16945.42889807952', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '16810.89779477', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1


## /root/FIL/strategy/factorcheck/log.txt ----- -----

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=54, self.factor=0.4458452702402322, self.count=7792 

self.closeSec=1671696599, self.tradeDate='20221222', self.openTime='160500', self.closeTime='160959', self.symbol='BTCUSDT', self.open=16795.2, self.close=16808.1, self.high=16809.9, self.low=16795.2 
2022-12-22 16:10:01,431:INFO:factorcheck2:main.py:126:handleKline:185239: self.closeSec=1671696599, self.tradeDate='20221222', self.openTime='160500', self.closeTime='160959',self.symbol='BTCUSDT',self.open=16795.2, self.close=16808.1, self.high=16809.9, self.low=16795.2   
2022-12-22 16:10:01,494:INFO:factorcheck2:main.py:127:handleKline:185239: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime    closeSec  ...      low       pct  index  idx
1629  20221222   154500    154959  1671695399  ...  16814.9 -0.000345   1629    3
1630  20221222   155000    155459  1671695699  ...  16807.1  0.000000   1630    4
1631  20221222   155500    155959  1671695999  ...  16815.0  0.000297   1631    5
1632  20221222   160000    160459  1671696299  ...  16794.2 -0.001474   1632    0
1633  20221222   160500    160959  1671696599  ...  16795.2  0.000768   1633    1

[5 rows x 11 columns]
2022-12-22 16:10:01,494:INFO:factorcheck2:main.py:128:handleKline:185239: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}
127.0.0.1 - - [22/Dec/2022 16:15:00] "POST / HTTP/1.1" 200 -

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=54, self.factor=0.4458452702402322, self.count=7793 

self.closeSec=1671696899, self.tradeDate='20221222', self.openTime='161000', self.closeTime='161459', self.symbol='BTCUSDT', self.open=16808.2, self.close=16810.5, self.high=16811.3, self.low=16808.1 
2022-12-22 16:15:00,553:INFO:factorcheck2:main.py:126:handleKline:185239: self.closeSec=1671696899, self.tradeDate='20221222', self.openTime='161000', self.closeTime='161459',self.symbol='BTCUSDT',self.open=16808.2, self.close=16810.5, self.high=16811.3, self.low=16808.1   
2022-12-22 16:15:00,592:INFO:factorcheck2:main.py:127:handleKline:185239: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime    closeSec  ...      low       pct  index  idx
1630  20221222   155000    155459  1671695699  ...  16807.1  0.000000   1630    4
1631  20221222   155500    155959  1671695999  ...  16815.0  0.000297   1631    5
1632  20221222   160000    160459  1671696299  ...  16794.2 -0.001474   1632    0
1633  20221222   160500    160959  1671696599  ...  16795.2  0.000768   1633    1
1634  20221222   161000    161459  1671696899  ...  16808.1  0.000143   1634    2

[5 rows x 11 columns]
2022-12-22 16:15:00,593:INFO:factorcheck2:main.py:128:handleKline:185239: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}


## /root/FIL/strategy/logic/log.txt ----- -----

2022-12-22 16:00:18,682:DEBUG:logic:main.py:454:getModel:174970: df_s.iloc[-5:,:] :
          date closeTime     open  ...    alpha58   alpha67   alpha72
5786  20221222    132959  16827.5  ...  50.416667  0.509239  0.487390
5787  20221222    135959  16820.6  ...  50.416667  0.506908  0.486260
5788  20221222    142959  16816.1  ...  50.000000  0.496773  0.491031
5789  20221222    145959  16795.9  ...  50.000000  0.499314  0.494035
5790  20221222    152959  16800.8  ...  50.416667  0.501881  0.495389

[5 rows x 33 columns]
0.533210332103321
acc is : 0.533210332103321
2022-12-22 16:00:18,773:INFO:logic:main.py:459:getModel:174970: df_pred.iloc[-5:,:] :
     pred    prob_0    prob_1  actual  ...       nav  sign  cost_        bm
537     1  0.492145  0.507855       0  ...  1.098967   1.0    0.0  0.981417
538     1  0.493504  0.506496       0  ...  1.097654   1.0    0.0  0.980244
539     1  0.486614  0.513386       1  ...  1.097980   1.0    0.0  0.980536
540     1  0.492272  0.507728       1  ...  1.098307   1.0    0.0  0.980828
541     1  0.494957  0.505043       1  ...  1.099229   1.0    0.0  0.981651

[5 rows x 10 columns]
2022-12-22 16:00:18,785:INFO:logic:main.py:469:getModel:174970: df_panel.iloc[-5:,:] :
    pred    prob_0    prob_1  actual  ...       nav  sign  cost_        bm
45     1  0.492129  0.507871       0  ...  1.098967   1.0    0.0  0.981899
46     1  0.493765  0.506235       0  ...  1.097654   1.0    0.0  0.981315
47     1  0.486479  0.513521       1  ...  1.097980   1.0    0.0  0.981361
48     1  0.492023  0.507977       1  ...  1.098307   1.0    0.0  0.980822
49     1  0.494957  0.505043       1  ...  1.099229   1.0    0.0  0.981651

[5 rows x 10 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '42.528', 'enterprice': '16701.5', 'countrevence': '0', 'unrealprofit': '5170.3025465376', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '16823.0740817', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}


## /root/FIL/strategy/modifiedmom/log.txt ----- -----

526  20221222   154000    154959  1671695399  16809.6    16815  0.000321
2022-12-22 15:50:00,568:INFO:modifiedmom:main.py:146:handleKline:185213: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': True, 'isOpenSell': False, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True}

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=3895 

self.closeSec=1671695999, self.tradeDate='20221222', self.openTime='155000', self.closeTime='155959', self.symbol='BTCUSDT', self.open='16814.9', self.close='16820'
127.0.0.1 - - [22/Dec/2022 16:00:01] "POST / HTTP/1.1" 200 -
2022-12-22 16:00:01,090:INFO:modifiedmom:main.py:144:handleKline:185213: self.closeSec=1671695999, self.tradeDate='20221222', self.openTime='155000', self.closeTime='155959',self.symbol='BTCUSDT',self.open='16814.9', self.close='16820'
2022-12-22 16:00:01,141:INFO:modifiedmom:main.py:145:handleKline:185213: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec     open    close       pct
523  20221222   151000    151959  1671693599  16785.4  16812.4  0.001615
524  20221222   152000    152959  1671694199  16812.5  16805.9 -0.000387
525  20221222   153000    153959  1671694799  16805.9  16809.6  0.000220
526  20221222   154000    154959  1671695399  16809.6    16815  0.000321
527  20221222   155000    155959  1671695999  16814.9    16820  0.000297
2022-12-22 16:00:01,141:INFO:modifiedmom:main.py:146:handleKline:185213: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': True, 'isOpenSell': False, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True}

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=3896 

self.closeSec=1671696599, self.tradeDate='20221222', self.openTime='160000', self.closeTime='160959', self.symbol='BTCUSDT', self.open='16820', self.close='16808.1'
2022-12-22 16:10:01,539:INFO:modifiedmom:main.py:144:handleKline:185213: self.closeSec=1671696599, self.tradeDate='20221222', self.openTime='160000', self.closeTime='160959',self.symbol='BTCUSDT',self.open='16820', self.close='16808.1'
127.0.0.1 - - [22/Dec/2022 16:10:01] "POST / HTTP/1.1" 200 -
2022-12-22 16:10:01,575:INFO:modifiedmom:main.py:145:handleKline:185213: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec     open    close       pct
524  20221222   152000    152959  1671694199  16812.5  16805.9 -0.000387
525  20221222   153000    153959  1671694799  16805.9  16809.6  0.000220
526  20221222   154000    154959  1671695399  16809.6    16815  0.000321
527  20221222   155000    155959  1671695999  16814.9    16820  0.000297
528  20221222   160000    160959  1671696599    16820  16808.1 -0.000707
2022-12-22 16:10:01,577:INFO:modifiedmom:main.py:146:handleKline:185213: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': True, 'isOpenSell': False, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True}


## /root/FIL/strategy/pyemd/log.txt ----- -----

17518  20221222   154000    154959  1671695399  16809.6    16815
2022-12-22 15:50:00,585:INFO:pyemd2:main.py:127:handleKline:185189: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=3896 

self.closeSec=1671695999, self.tradeDate='20221222', self.openTime='155000', self.closeTime='155959', self.symbol='BTCUSDT', self.open='16814.9', self.close='16820'
127.0.0.1 - - [22/Dec/2022 16:00:01] "POST / HTTP/1.1" 200 -
2022-12-22 16:00:01,114:INFO:pyemd2:main.py:125:handleKline:185189: self.closeSec=1671695999, self.tradeDate='20221222', self.openTime='155000', self.closeTime='155959',self.symbol='BTCUSDT',self.open='16814.9', self.close='16820'
2022-12-22 16:00:01,174:INFO:pyemd2:main.py:126:handleKline:185189: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
17515  20221222   151000    151959  1671693599  16785.4  16812.4
17516  20221222   152000    152959  1671694199  16812.5  16805.9
17517  20221222   153000    153959  1671694799  16805.9  16809.6
17518  20221222   154000    154959  1671695399  16809.6    16815
17519  20221222   155000    155959  1671695999  16814.9    16820
2022-12-22 16:00:01,174:INFO:pyemd2:main.py:127:handleKline:185189: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=3897 

self.closeSec=1671696599, self.tradeDate='20221222', self.openTime='160000', self.closeTime='160959', self.symbol='BTCUSDT', self.open='16820', self.close='16808.1'
127.0.0.1 - - [22/Dec/2022 16:10:01] "POST / HTTP/1.1" 200 -
2022-12-22 16:10:01,559:INFO:pyemd2:main.py:125:handleKline:185189: self.closeSec=1671696599, self.tradeDate='20221222', self.openTime='160000', self.closeTime='160959',self.symbol='BTCUSDT',self.open='16820', self.close='16808.1'
2022-12-22 16:10:01,579:INFO:pyemd2:main.py:126:handleKline:185189: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
17516  20221222   152000    152959  1671694199  16812.5  16805.9
17517  20221222   153000    153959  1671694799  16805.9  16809.6
17518  20221222   154000    154959  1671695399  16809.6    16815
17519  20221222   155000    155959  1671695999  16814.9    16820
17520  20221222   160000    160959  1671696599    16820  16808.1
2022-12-22 16:10:01,579:INFO:pyemd2:main.py:127:handleKline:185189: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}


## /root/FIL/strategy/similarity/log.txt ----- -----

12190  20221222   154000    154959  1671695399  16809.6    16815
2022-12-22 15:50:00,569:INFO:testStrategy:main.py:103:handleKline:185174: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': True, 'isOpenSell': False, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True, 'isCorr': False}

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=3896 

self.closeSec=1671695999, self.tradeDate='20221222', self.openTime='155000', self.closeTime='155959', self.symbol='BTCUSDT', self.open='16814.9', self.close='16820'
2022-12-22 16:00:01,087:INFO:testStrategy:main.py:101:handleKline:185174: self.closeSec=1671695999, self.tradeDate='20221222', self.openTime='155000', self.closeTime='155959',self.symbol='BTCUSDT',self.open='16814.9', self.close='16820'
127.0.0.1 - - [22/Dec/2022 16:00:01] "POST / HTTP/1.1" 200 -
2022-12-22 16:00:01,144:INFO:testStrategy:main.py:102:handleKline:185174: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
12187  20221222   151000    151959  1671693599  16785.4  16812.4
12188  20221222   152000    152959  1671694199  16812.5  16805.9
12189  20221222   153000    153959  1671694799  16805.9  16809.6
12190  20221222   154000    154959  1671695399  16809.6    16815
12191  20221222   155000    155959  1671695999  16814.9    16820
2022-12-22 16:00:01,144:INFO:testStrategy:main.py:103:handleKline:185174: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': True, 'isOpenSell': False, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True, 'isCorr': False}

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=3897 

self.closeSec=1671696599, self.tradeDate='20221222', self.openTime='160000', self.closeTime='160959', self.symbol='BTCUSDT', self.open='16820', self.close='16808.1'
2022-12-22 16:10:01,544:INFO:testStrategy:main.py:101:handleKline:185174: self.closeSec=1671696599, self.tradeDate='20221222', self.openTime='160000', self.closeTime='160959',self.symbol='BTCUSDT',self.open='16820', self.close='16808.1'
127.0.0.1 - - [22/Dec/2022 16:10:01] "POST / HTTP/1.1" 200 -
2022-12-22 16:10:01,571:INFO:testStrategy:main.py:102:handleKline:185174: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
12188  20221222   152000    152959  1671694199  16812.5  16805.9
12189  20221222   153000    153959  1671694799  16805.9  16809.6
12190  20221222   154000    154959  1671695399  16809.6    16815
12191  20221222   155000    155959  1671695999  16814.9    16820
12192  20221222   160000    160959  1671696599    16820  16808.1
2022-12-22 16:10:01,571:INFO:testStrategy:main.py:103:handleKline:185174: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': True, 'isOpenSell': False, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True, 'isCorr': False}


## /root/FIL/strategy/sr_min/log.txt ----- -----

--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=0, self.total=1000000.0, self.flagDict['side']='', self.tradeCount=0, self.count=3224
self.closeSec=1671696599, self.tradeDate='20221222', self.openTime='160500', self.closeTime='160959', self.symbol='BTCUSDT', self.open=16795.2, self.close=16808.1, self.high=16809.9, self.low=16795.2, self.vol=367.517, self.amt=6174432.2137 
127.0.0.1 - - [22/Dec/2022 16:10:01] "POST / HTTP/1.1" 200 -
2022-12-22 16:10:01,525:INFO:sr_min:main.py:172:handleKline:449472: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5949  20221222   154500    154959  ...         0.0        0.0       0
5950  20221222   155000    155459  ...         0.0        0.0       0
5951  20221222   155500    155959  ...         0.0        0.0       0
5952  20221222   160000    160459  ...         0.0        0.0       0
5953  20221222   160500    160959  ...         0.0        0.0       0

[5 rows x 18 columns]
2022-12-22 16:10:01,532:INFO:sr_min:main.py:175:handleKline:449472: self.closeSec=1671696599, self.tradeDate='20221222', self.openTime='160500', self.closeTime='160959',self.symbol='BTCUSDT',self.open=16795.2, self.close=16808.1, self.high=16809.9, self.low=16795.2, self.vol=367.517, self.amt=6174432.2137, ukdf['pct'].iloc[-1]=0.000768 , ukdf['amount'].iloc[-1]=6174432.2137, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5953, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': []}
type(curSign)=<class 'int'>, curSign=0, self.sign=0
127.0.0.1 - - [22/Dec/2022 16:15:00] "POST / HTTP/1.1" 200 -
--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=0, self.total=1000000.0, self.flagDict['side']='', self.tradeCount=0, self.count=3225
self.closeSec=1671696899, self.tradeDate='20221222', self.openTime='161000', self.closeTime='161459', self.symbol='BTCUSDT', self.open=16808.2, self.close=16810.5, self.high=16811.3, self.low=16808.1, self.vol=251.615, self.amt=4229555.3564 
2022-12-22 16:15:00,620:INFO:sr_min:main.py:172:handleKline:449472: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5950  20221222   155000    155459  ...         0.0        0.0       0
5951  20221222   155500    155959  ...         0.0        0.0       0
5952  20221222   160000    160459  ...         0.0        0.0       0
5953  20221222   160500    160959  ...         0.0        0.0       0
5954  20221222   161000    161459  ...         0.0        0.0       0

[5 rows x 18 columns]
2022-12-22 16:15:00,620:INFO:sr_min:main.py:175:handleKline:449472: self.closeSec=1671696899, self.tradeDate='20221222', self.openTime='161000', self.closeTime='161459',self.symbol='BTCUSDT',self.open=16808.2, self.close=16810.5, self.high=16811.3, self.low=16808.1, self.vol=251.615, self.amt=4229555.3564, ukdf['pct'].iloc[-1]=0.000143 , ukdf['amount'].iloc[-1]=4229555.3564, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5954, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': []}
type(curSign)=<class 'int'>, curSign=0, self.sign=0


## /root/FIL/strategy/s_rsrs/log.txt ----- -----

721  20221222   040000    075959  1671667199  ...    721  0.036546 -1.883876    -1.0
722  20221222   080000    115959  1671681599  ...    722  0.035492 -1.830501    -1.0

[5 rows x 15 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '53.372', 'enterprice': '16723.1', 'countrevence': '0', 'unrealprofit': '-6536.53079795364', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '16845.57116087', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'numpy.int64'>, curSign=-1, self.sign=-1
127.0.0.1 - - [22/Dec/2022 16:00:00] "POST / HTTP/1.1" 200 -
--handleKline--:  version='2.0.0', self.name='s_rsrs', self.symbol='BTCUSDT', interval='4h', intervalSec=14400, wid=25, thd=0.6, self.sign=-1, self.total=891652.7479068, self.flagDict['side']='sell', self.tradeCount=7, self.count=162
self.closeSec=1671695999, self.tradeDate='20221222', self.openTime='120000', self.closeTime='155959', self.symbol='BTCUSDT', self.open=16844.5, self.close=16820.0, self.high=16850.0, self.low=16778.0, self.vol=20542.365, self.amt=345377995.3921 
2022-12-22 16:00:00,986:INFO:s_rsrs:main.py:141:handleKline:185271: self.closeSec=1671695999, self.tradeDate='20221222', self.openTime='120000', self.closeTime='155959',self.symbol='BTCUSDT',self.open=16844.5, self.close=16820.0, self.high=16850.0, self.low=16778.0, self.vol=20542.365, self.amt=345377995.3921 
2022-12-22 16:00:01,004:INFO:s_rsrs:main.py:142:handleKline:185271: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime  ...        vol           amt       pct
719  20221221   200000    235959  ...  72649.874  1.222429e+09 -0.001049
720  20221222   000000    035959  ...  36319.230  6.097925e+08 -0.006396
721  20221222   040000    075959  ...  26341.897  4.417508e+08  0.004646
722  20221222   080000    115959  ...  19468.471  3.276365e+08  0.001183
723  20221222   120000    155959  ...  20542.365  3.453780e+08 -0.001454

[5 rows x 11 columns]
2022-12-22 16:00:02,503:INFO:s_rsrs:main.py:151:handleKline:185271: df_s.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec  ...  index      beta    zscore  signal
719  20221221   200000    235959  1671638399  ...    719  0.037568 -2.003620    -1.0
720  20221222   000000    035959  1671652799  ...    720  0.037600 -1.940573    -1.0
721  20221222   040000    075959  1671667199  ...    721  0.036546 -1.883876    -1.0
722  20221222   080000    115959  1671681599  ...    722  0.035492 -1.830501    -1.0
723  20221222   120000    155959  1671695999  ...    723  0.036387 -1.774678    -1.0

[5 rows x 15 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '53.372', 'enterprice': '16723.1', 'countrevence': '0', 'unrealprofit': '-5203.71974812712', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '16820.59905846', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'numpy.int64'>, curSign=-1, self.sign=-1


