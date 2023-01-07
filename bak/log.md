# 20230107 16:16:01

## /root/FIL/strategy/amihud/log.txt ----- -----

--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=993672.4896432, self.flagDict['side']='sell', self.tradeCount=2, self.count=11834
self.closeSec=1673078999, self.tradeDate='20230107', self.openTime='160500', self.closeTime='160959', self.symbol='BTCUSDT', self.open=16945.8, self.close=16939.7, self.high=16945.9, self.low=16939.7, self.vol=418.335, self.amt=7087559.6369 
127.0.0.1 - - [07/Jan/2023 16:10:01] "POST / HTTP/1.1" 200 -
2023-01-07 16:10:01,508:INFO:amihud:main.py:172:handleKline:200676: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5949  20230107   154500    154959  ...         0.0        0.0       0
5950  20230107   155000    155459  ...         0.0        0.0       0
5951  20230107   155500    155959  ...         0.0        0.0       0
5952  20230107   160000    160459  ...         0.0        0.0       0
5953  20230107   160500    160959  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-01-07 16:10:01,514:INFO:amihud:main.py:175:handleKline:200676: self.closeSec=1673078999, self.tradeDate='20230107', self.openTime='160500', self.closeTime='160959',self.symbol='BTCUSDT',self.open=16945.8, self.close=16939.7, self.high=16945.9, self.low=16939.7, self.vol=418.335, self.amt=7087559.6369, ukdf['pct'].iloc[-1]=-0.00036 , ukdf['amount'].iloc[-1]=7087559.6369, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5953, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '60.176', 'enterprice': '16529.3', 'countrevence': '0', 'unrealprofit': '-24710.66157243008', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '16939.93981608', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1
127.0.0.1 - - [07/Jan/2023 16:15:00] "POST / HTTP/1.1" 200 -
--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=993672.4896432, self.flagDict['side']='sell', self.tradeCount=2, self.count=11835
self.closeSec=1673079299, self.tradeDate='20230107', self.openTime='161000', self.closeTime='161459', self.symbol='BTCUSDT', self.open=16939.7, self.close=16929.3, self.high=16939.8, self.low=16929.3, self.vol=449.836, self.amt=7617430.8263 
2023-01-07 16:15:00,857:INFO:amihud:main.py:172:handleKline:200676: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5950  20230107   155000    155459  ...         0.0        0.0       0
5951  20230107   155500    155959  ...         0.0        0.0       0
5952  20230107   160000    160459  ...         0.0        0.0       0
5953  20230107   160500    160959  ...         0.0        0.0       0
5954  20230107   161000    161459  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-01-07 16:15:00,858:INFO:amihud:main.py:175:handleKline:200676: self.closeSec=1673079299, self.tradeDate='20230107', self.openTime='161000', self.closeTime='161459',self.symbol='BTCUSDT',self.open=16939.7, self.close=16929.3, self.high=16939.8, self.low=16929.3, self.vol=449.836, self.amt=7617430.8263, ukdf['pct'].iloc[-1]=-0.000614 , ukdf['amount'].iloc[-1]=7617430.8263, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5954, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '60.176', 'enterprice': '16529.3', 'countrevence': '0', 'unrealprofit': '-24070.4', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '16929.3', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1


## /root/FIL/strategy/factorcheck/log.txt ----- -----


self.closeSec=1673078999, self.tradeDate='20230107', self.openTime='160500', self.closeTime='160959', self.symbol='BTCUSDT', self.open=16945.8, self.close=16939.7, self.high=16945.9, self.low=16939.7 
2023-01-07 16:10:01,435:INFO:factorcheck2:main.py:126:handleKline:185239: self.closeSec=1673078999, self.tradeDate='20230107', self.openTime='160500', self.closeTime='160959',self.symbol='BTCUSDT',self.open=16945.8, self.close=16939.7, self.high=16945.9, self.low=16939.7   
127.0.0.1 - - [07/Jan/2023 16:10:01] "POST / HTTP/1.1" 200 -
2023-01-07 16:10:01,489:INFO:factorcheck2:main.py:127:handleKline:185239: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime    closeSec  ...      low       pct  index  idx
1629  20230107   154500    154959  1673077799  ...  16940.1 -0.000041   1629    3
1630  20230107   155000    155459  1673078099  ...  16939.9 -0.000012   1630    4
1631  20230107   155500    155959  1673078399  ...  16939.8  0.000000   1631    5
1632  20230107   160000    160459  1673078699  ...  16939.8  0.000348   1632    0
1633  20230107   160500    160959  1673078999  ...  16939.7 -0.000360   1633    1

[5 rows x 11 columns]
2023-01-07 16:10:01,489:INFO:factorcheck2:main.py:128:handleKline:185239: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': True, 'isOpenSell': False, 'isCloseBuy': False, 'isCloseSell': False, 'isOpen': True, 'isClose': False, 'isTrig': True}

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=32, self.factor=0.334137745661684, self.count=12401 

self.closeSec=1673079299, self.tradeDate='20230107', self.openTime='161000', self.closeTime='161459', self.symbol='BTCUSDT', self.open=16939.7, self.close=16929.3, self.high=16939.8, self.low=16929.3 
2023-01-07 16:15:00,789:INFO:factorcheck2:main.py:126:handleKline:185239: self.closeSec=1673079299, self.tradeDate='20230107', self.openTime='161000', self.closeTime='161459',self.symbol='BTCUSDT',self.open=16939.7, self.close=16929.3, self.high=16939.8, self.low=16929.3   
127.0.0.1 - - [07/Jan/2023 16:15:00] "POST / HTTP/1.1" 200 -
2023-01-07 16:15:00,848:INFO:factorcheck2:main.py:127:handleKline:185239: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime    closeSec  ...      low       pct  index  idx
1630  20230107   155000    155459  1673078099  ...  16939.9 -0.000012   1630    4
1631  20230107   155500    155959  1673078399  ...  16939.8  0.000000   1631    5
1632  20230107   160000    160459  1673078699  ...  16939.8  0.000348   1632    0
1633  20230107   160500    160959  1673078999  ...  16939.7 -0.000360   1633    1
1634  20230107   161000    161459  1673079299  ...  16929.3 -0.000614   1634    2

[5 rows x 11 columns]
2023-01-07 16:15:00,848:INFO:factorcheck2:main.py:128:handleKline:185239: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': True, 'isOpenSell': False, 'isCloseBuy': False, 'isCloseSell': False, 'isOpen': True, 'isClose': False, 'isTrig': True}


## /root/FIL/strategy/logic/log.txt ----- -----

2023-01-07 16:00:17,667:DEBUG:logic:main.py:456:getModel:726423: df_s.iloc[-5:,:] :
          date closeTime     open  ...    alpha58   alpha67   alpha72
5786  20230107    132959  16930.0  ...  48.333333  0.558423  0.291989
5787  20230107    135959  16930.0  ...  47.916667  0.556159  0.291344
5788  20230107    142959  16926.8  ...  47.916667  0.552805  0.291545
5789  20230107    145959  16922.4  ...  48.333333  0.554425  0.291258
5790  20230107    152959  16925.1  ...  48.333333  0.562085  0.288745

[5 rows x 33 columns]
0.540590405904059
acc is : 0.540590405904059
2023-01-07 16:00:17,763:INFO:logic:main.py:461:getModel:726423: df_pred.iloc[-5:,:] :
     pred    prob_0    prob_1  actual  ...  nav  sign   cost_        bm
537     0  0.501600  0.498400       0  ...  NaN   NaN -0.0016  1.003789
538     1  0.499567  0.500433       0  ...  NaN   NaN -0.0016  1.003528
539     1  0.498647  0.501353       1  ...  NaN   NaN -0.0016  1.003683
540     0  0.500248  0.499752       1  ...  NaN   NaN -0.0016  1.004412
541     0  0.504965  0.495035       1  ...  NaN   NaN -0.0016  1.004560

[5 rows x 10 columns]
2023-01-07 16:00:17,782:INFO:logic:main.py:471:getModel:726423: df_panel.iloc[-5:,:] :
    pred    prob_0    prob_1  actual  ...  nav  sign   cost_        bm
45     0  0.501620  0.498380       0  ...  NaN   NaN -0.0016  1.005668
46     1  0.499386  0.500614       0  ...  NaN   NaN -0.0016  1.004088
47     1  0.498280  0.501720       1  ...  NaN   NaN -0.0016  1.000721
48     0  0.500484  0.499516       1  ...  NaN   NaN -0.0016  1.002059
49     0  0.504965  0.495035       1  ...  NaN   NaN -0.0016  1.004560

[5 rows x 10 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '42.528', 'enterprice': '16701.5', 'countrevence': '0', 'unrealprofit': '10138.6752', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '16939.9', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}


## /root/FIL/strategy/modifiedmom/log.txt ----- -----

526  20230107   154000    154959  1673077799  16937.1  16940.1  0.000183
2023-01-07 15:50:00,605:INFO:modifiedmom:main.py:146:handleKline:185213: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': True, 'isOpenSell': False, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True}
127.0.0.1 - - [07/Jan/2023 16:00:00] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=6199 

self.closeSec=1673078399, self.tradeDate='20230107', self.openTime='155000', self.closeTime='155959', self.symbol='BTCUSDT', self.open='16940.2', self.close='16939.9'
2023-01-07 16:00:00,885:INFO:modifiedmom:main.py:144:handleKline:185213: self.closeSec=1673078399, self.tradeDate='20230107', self.openTime='155000', self.closeTime='155959',self.symbol='BTCUSDT',self.open='16940.2', self.close='16939.9'
2023-01-07 16:00:00,895:INFO:modifiedmom:main.py:145:handleKline:185213: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec     open    close       pct
523  20230107   151000    151959  1673075999    16929    16929  0.000006
524  20230107   152000    152959  1673076599  16928.9  16937.4  0.000496
525  20230107   153000    153959  1673077199  16937.4    16937 -0.000024
526  20230107   154000    154959  1673077799  16937.1  16940.1  0.000183
527  20230107   155000    155959  1673078399  16940.2  16939.9 -0.000012
2023-01-07 16:00:00,896:INFO:modifiedmom:main.py:146:handleKline:185213: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': True, 'isOpenSell': False, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True}

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=6200 

self.closeSec=1673078999, self.tradeDate='20230107', self.openTime='160000', self.closeTime='160959', self.symbol='BTCUSDT', self.open='16939.8', self.close='16939.7'
2023-01-07 16:10:01,525:INFO:modifiedmom:main.py:144:handleKline:185213: self.closeSec=1673078999, self.tradeDate='20230107', self.openTime='160000', self.closeTime='160959',self.symbol='BTCUSDT',self.open='16939.8', self.close='16939.7'
127.0.0.1 - - [07/Jan/2023 16:10:01] "POST / HTTP/1.1" 200 -
2023-01-07 16:10:01,536:INFO:modifiedmom:main.py:145:handleKline:185213: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec     open    close       pct
524  20230107   152000    152959  1673076599  16928.9  16937.4  0.000496
525  20230107   153000    153959  1673077199  16937.4    16937 -0.000024
526  20230107   154000    154959  1673077799  16937.1  16940.1  0.000183
527  20230107   155000    155959  1673078399  16940.2  16939.9 -0.000012
528  20230107   160000    160959  1673078999  16939.8  16939.7 -0.000012
2023-01-07 16:10:01,536:INFO:modifiedmom:main.py:146:handleKline:185213: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': True, 'isOpenSell': False, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True}


## /root/FIL/strategy/pyemd/log.txt ----- -----

17518  20230107   154000    154959  1673077799  16937.1  16940.1
2023-01-07 15:50:00,609:INFO:pyemd2:main.py:127:handleKline:185189: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=6200 

self.closeSec=1673078399, self.tradeDate='20230107', self.openTime='155000', self.closeTime='155959', self.symbol='BTCUSDT', self.open='16940.2', self.close='16939.9'
127.0.0.1 - - [07/Jan/2023 16:00:00] "POST / HTTP/1.1" 200 -
2023-01-07 16:00:00,919:INFO:pyemd2:main.py:125:handleKline:185189: self.closeSec=1673078399, self.tradeDate='20230107', self.openTime='155000', self.closeTime='155959',self.symbol='BTCUSDT',self.open='16940.2', self.close='16939.9'
2023-01-07 16:00:00,992:INFO:pyemd2:main.py:126:handleKline:185189: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
17515  20230107   151000    151959  1673075999    16929    16929
17516  20230107   152000    152959  1673076599  16928.9  16937.4
17517  20230107   153000    153959  1673077199  16937.4    16937
17518  20230107   154000    154959  1673077799  16937.1  16940.1
17519  20230107   155000    155959  1673078399  16940.2  16939.9
2023-01-07 16:00:00,992:INFO:pyemd2:main.py:127:handleKline:185189: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=6201 

self.closeSec=1673078999, self.tradeDate='20230107', self.openTime='160000', self.closeTime='160959', self.symbol='BTCUSDT', self.open='16939.8', self.close='16939.7'
2023-01-07 16:10:01,545:INFO:pyemd2:main.py:125:handleKline:185189: self.closeSec=1673078999, self.tradeDate='20230107', self.openTime='160000', self.closeTime='160959',self.symbol='BTCUSDT',self.open='16939.8', self.close='16939.7'
127.0.0.1 - - [07/Jan/2023 16:10:01] "POST / HTTP/1.1" 200 -
2023-01-07 16:10:01,552:INFO:pyemd2:main.py:126:handleKline:185189: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
17516  20230107   152000    152959  1673076599  16928.9  16937.4
17517  20230107   153000    153959  1673077199  16937.4    16937
17518  20230107   154000    154959  1673077799  16937.1  16940.1
17519  20230107   155000    155959  1673078399  16940.2  16939.9
17520  20230107   160000    160959  1673078999  16939.8  16939.7
2023-01-07 16:10:01,552:INFO:pyemd2:main.py:127:handleKline:185189: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}


## /root/FIL/strategy/similarity/log.txt ----- -----

12190  20230107   154000    154959  1673077799  16937.1  16940.1
2023-01-07 15:50:00,610:INFO:testStrategy:main.py:103:handleKline:185174: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': True, 'isOpenSell': False, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True, 'isCorr': False}

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=6200 

self.closeSec=1673078399, self.tradeDate='20230107', self.openTime='155000', self.closeTime='155959', self.symbol='BTCUSDT', self.open='16940.2', self.close='16939.9'
127.0.0.1 - - [07/Jan/2023 16:00:00] "POST / HTTP/1.1" 200 -
2023-01-07 16:00:00,879:INFO:testStrategy:main.py:101:handleKline:185174: self.closeSec=1673078399, self.tradeDate='20230107', self.openTime='155000', self.closeTime='155959',self.symbol='BTCUSDT',self.open='16940.2', self.close='16939.9'
2023-01-07 16:00:00,904:INFO:testStrategy:main.py:102:handleKline:185174: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
12187  20230107   151000    151959  1673075999    16929    16929
12188  20230107   152000    152959  1673076599  16928.9  16937.4
12189  20230107   153000    153959  1673077199  16937.4    16937
12190  20230107   154000    154959  1673077799  16937.1  16940.1
12191  20230107   155000    155959  1673078399  16940.2  16939.9
2023-01-07 16:00:00,905:INFO:testStrategy:main.py:103:handleKline:185174: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': True, 'isOpenSell': False, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True, 'isCorr': False}
127.0.0.1 - - [07/Jan/2023 16:10:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=6201 

self.closeSec=1673078999, self.tradeDate='20230107', self.openTime='160000', self.closeTime='160959', self.symbol='BTCUSDT', self.open='16939.8', self.close='16939.7'
2023-01-07 16:10:01,531:INFO:testStrategy:main.py:101:handleKline:185174: self.closeSec=1673078999, self.tradeDate='20230107', self.openTime='160000', self.closeTime='160959',self.symbol='BTCUSDT',self.open='16939.8', self.close='16939.7'
2023-01-07 16:10:01,567:INFO:testStrategy:main.py:102:handleKline:185174: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
12188  20230107   152000    152959  1673076599  16928.9  16937.4
12189  20230107   153000    153959  1673077199  16937.4    16937
12190  20230107   154000    154959  1673077799  16937.1  16940.1
12191  20230107   155000    155959  1673078399  16940.2  16939.9
12192  20230107   160000    160959  1673078999  16939.8  16939.7
2023-01-07 16:10:01,567:INFO:testStrategy:main.py:103:handleKline:185174: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': True, 'isOpenSell': False, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True, 'isCorr': False}


## /root/FIL/strategy/sr_min/log.txt ----- -----

127.0.0.1 - - [07/Jan/2023 16:10:01] "POST / HTTP/1.1" 200 -
--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=0, self.total=1000000.0, self.flagDict['side']='', self.tradeCount=0, self.count=7832
self.closeSec=1673078999, self.tradeDate='20230107', self.openTime='160500', self.closeTime='160959', self.symbol='BTCUSDT', self.open=16945.8, self.close=16939.7, self.high=16945.9, self.low=16939.7, self.vol=418.335, self.amt=7087559.6369 
2023-01-07 16:10:01,500:INFO:sr_min:main.py:172:handleKline:449472: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5949  20230107   154500    154959  ...         0.0        0.0       0
5950  20230107   155000    155459  ...         0.0        0.0       0
5951  20230107   155500    155959  ...         0.0        0.0       0
5952  20230107   160000    160459  ...         0.0        0.0       0
5953  20230107   160500    160959  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-01-07 16:10:01,500:INFO:sr_min:main.py:175:handleKline:449472: self.closeSec=1673078999, self.tradeDate='20230107', self.openTime='160500', self.closeTime='160959',self.symbol='BTCUSDT',self.open=16945.8, self.close=16939.7, self.high=16945.9, self.low=16939.7, self.vol=418.335, self.amt=7087559.6369, ukdf['pct'].iloc[-1]=-0.00036 , ukdf['amount'].iloc[-1]=7087559.6369, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5953, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': []}
type(curSign)=<class 'int'>, curSign=0, self.sign=0
127.0.0.1 - - [07/Jan/2023 16:15:00] "POST / HTTP/1.1" 200 -
--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=0, self.total=1000000.0, self.flagDict['side']='', self.tradeCount=0, self.count=7833
self.closeSec=1673079299, self.tradeDate='20230107', self.openTime='161000', self.closeTime='161459', self.symbol='BTCUSDT', self.open=16939.7, self.close=16929.3, self.high=16939.8, self.low=16929.3, self.vol=449.836, self.amt=7617430.8263 
2023-01-07 16:15:00,870:INFO:sr_min:main.py:172:handleKline:449472: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5950  20230107   155000    155459  ...         0.0        0.0       0
5951  20230107   155500    155959  ...         0.0        0.0       0
5952  20230107   160000    160459  ...         0.0        0.0       0
5953  20230107   160500    160959  ...         0.0        0.0       0
5954  20230107   161000    161459  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-01-07 16:15:00,871:INFO:sr_min:main.py:175:handleKline:449472: self.closeSec=1673079299, self.tradeDate='20230107', self.openTime='161000', self.closeTime='161459',self.symbol='BTCUSDT',self.open=16939.7, self.close=16929.3, self.high=16939.8, self.low=16929.3, self.vol=449.836, self.amt=7617430.8263, ukdf['pct'].iloc[-1]=-0.000614 , ukdf['amount'].iloc[-1]=7617430.8263, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5954, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': []}
type(curSign)=<class 'int'>, curSign=0, self.sign=0


## /root/FIL/strategy/s_rsrs/log.txt ----- -----

721  20230107   040000    075959  1673049599  ...    721  0.505149  0.661141     1.0
722  20230107   080000    115959  1673063999  ...    722  0.510513  0.662980     1.0

[5 rows x 15 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '52.77', 'enterprice': '16723.1', 'countrevence': '0', 'unrealprofit': '11727.9627510471', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '16945.34678323', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'numpy.int64'>, curSign=1, self.sign=1
--handleKline--:  version='2.0.0', self.name='s_rsrs', self.symbol='BTCUSDT', interval='4h', intervalSec=14400, wid=25, thd=0.6, self.sign=1, self.total=881595.509013, self.flagDict['side']='buy', self.tradeCount=10, self.count=258
self.closeSec=1673078399, self.tradeDate='20230107', self.openTime='120000', self.closeTime='155959', self.symbol='BTCUSDT', self.open=16944.3, self.close=16939.9, self.high=16945.0, self.low=16915.8, self.vol=10555.757, self.amt=178710767.0296 
2023-01-07 16:00:00,784:INFO:s_rsrs:main.py:141:handleKline:185271: self.closeSec=1673078399, self.tradeDate='20230107', self.openTime='120000', self.closeTime='155959',self.symbol='BTCUSDT',self.open=16944.3, self.close=16939.9, self.high=16945.0, self.low=16915.8, self.vol=10555.757, self.amt=178710767.0296 
127.0.0.1 - - [07/Jan/2023 16:00:00] "POST / HTTP/1.1" 200 -
2023-01-07 16:00:00,827:INFO:s_rsrs:main.py:142:handleKline:185271: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime  ...         vol           amt       pct
719  20230106   200000    235959  ...  102292.442  1.714161e+09  0.006132
720  20230107   000000    035959  ...   57986.610  9.782164e+08  0.005851
721  20230107   040000    075959  ...   68235.521  1.156656e+09  0.000661
722  20230107   080000    115959  ...   18044.046  3.057485e+08  0.000030
723  20230107   120000    155959  ...   10555.757  1.787108e+08 -0.000260

[5 rows x 11 columns]
2023-01-07 16:00:02,117:INFO:s_rsrs:main.py:151:handleKline:185271: df_s.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec  ...  index      beta    zscore  signal
719  20230106   200000    235959  1673020799  ...    719  0.364248  0.223422     NaN
720  20230107   000000    035959  1673035199  ...    720  0.393304  0.307458     NaN
721  20230107   040000    075959  1673049599  ...    721  0.505149  0.661141     1.0
722  20230107   080000    115959  1673063999  ...    722  0.510513  0.662980     1.0
723  20230107   120000    155959  1673078399  ...    723  0.415503  0.335738     NaN

[5 rows x 15 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '52.77', 'enterprice': '16723.1', 'countrevence': '0', 'unrealprofit': '11463.3188870826', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '16940.33173938', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'numpy.int64'>, curSign=-9223372036854775808, self.sign=1


