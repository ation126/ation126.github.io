# 20230313 16:26:02

## /root/FIL/strategy/amihud/log.txt ----- -----

--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=993672.4896432, self.flagDict['side']='sell', self.tradeCount=2, self.count=30556
self.closeSec=1678695599, self.tradeDate='20230313', self.openTime='161500', self.closeTime='161959', self.symbol='BTCUSDT', self.open=22388.4, self.close=22369.6, self.high=22419.9, self.low=22363.4, self.vol=2436.074, self.amt=54552711.8412 
127.0.0.1 - - [13/Mar/2023 16:20:02] "POST / HTTP/1.1" 200 -
2023-03-13 16:20:07,437:INFO:amihud:main.py:172:handleKline:200676: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5951  20230313   155500    155959  ...         0.0        0.0       0
5952  20230313   160000    160459  ...         0.0        0.0       0
5953  20230313   160500    160959  ...         0.0        0.0       0
5954  20230313   161000    161459  ...         0.0        0.0       0
5955  20230313   161500    161959  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-03-13 16:20:07,459:INFO:amihud:main.py:175:handleKline:200676: self.closeSec=1678695599, self.tradeDate='20230313', self.openTime='161500', self.closeTime='161959',self.symbol='BTCUSDT',self.open=22388.4, self.close=22369.6, self.high=22419.9, self.low=22363.4, self.vol=2436.074, self.amt=54552711.8412, ukdf['pct'].iloc[-1]=-0.000911 , ukdf['amount'].iloc[-1]=54552711.8412, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5955, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '60.176', 'enterprice': '16529.3', 'countrevence': '0', 'unrealprofit': '-351740.7552', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '22374.5', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1
127.0.0.1 - - [13/Mar/2023 16:25:01] "POST / HTTP/1.1" 200 -
--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=993672.4896432, self.flagDict['side']='sell', self.tradeCount=2, self.count=30557
self.closeSec=1678695899, self.tradeDate='20230313', self.openTime='162000', self.closeTime='162459', self.symbol='BTCUSDT', self.open=22369.6, self.close=22386.2, self.high=22397.3, self.low=22355.0, self.vol=2157.118, self.amt=48268457.7992 
2023-03-13 16:25:01,571:INFO:amihud:main.py:172:handleKline:200676: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5952  20230313   160000    160459  ...         0.0        0.0       0
5953  20230313   160500    160959  ...         0.0        0.0       0
5954  20230313   161000    161459  ...         0.0        0.0       0
5955  20230313   161500    161959  ...         0.0        0.0       0
5956  20230313   162000    162459  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-03-13 16:25:01,572:INFO:amihud:main.py:175:handleKline:200676: self.closeSec=1678695899, self.tradeDate='20230313', self.openTime='162000', self.closeTime='162459',self.symbol='BTCUSDT',self.open=22369.6, self.close=22386.2, self.high=22397.3, self.low=22355.0, self.vol=2157.118, self.amt=48268457.7992, ukdf['pct'].iloc[-1]=0.000742 , ukdf['amount'].iloc[-1]=48268457.7992, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5956, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '60.176', 'enterprice': '16529.3', 'countrevence': '0', 'unrealprofit': '-352444.8144', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '22386.2', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1


## /root/FIL/strategy/factorcheck/log.txt ----- -----


self.closeSec=1678695599, self.tradeDate='20230313', self.openTime='161500', self.closeTime='161959', self.symbol='BTCUSDT', self.open=22388.4, self.close=22369.6, self.high=22419.9, self.low=22363.4 
127.0.0.1 - - [13/Mar/2023 16:20:01] "POST / HTTP/1.1" 200 -
2023-03-13 16:20:02,248:INFO:factorcheck2:main.py:126:handleKline:185239: self.closeSec=1678695599, self.tradeDate='20230313', self.openTime='161500', self.closeTime='161959',self.symbol='BTCUSDT',self.open=22388.4, self.close=22369.6, self.high=22419.9, self.low=22363.4   
2023-03-13 16:20:03,698:INFO:factorcheck2:main.py:127:handleKline:185239: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime    closeSec  ...      low       pct  index  idx
1631  20230313   155500    155959  1678694399  ...  22421.6  0.001307   1631    5
1632  20230313   160000    160459  1678694699  ...  22435.8  0.001073   1632    0
1633  20230313   160500    160959  1678694999  ...  22356.0 -0.003301   1633    1
1634  20230313   161000    161459  1678695299  ...  22367.7 -0.000513   1634    2
1635  20230313   161500    161959  1678695599  ...  22363.4 -0.000911   1635    3

[5 rows x 11 columns]
2023-03-13 16:20:03,707:INFO:factorcheck2:main.py:128:handleKline:185239: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}
127.0.0.1 - - [13/Mar/2023 16:25:01] "POST / HTTP/1.1" 200 -

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=23, self.factor=0.2409768264993001, self.count=31123 

self.closeSec=1678695899, self.tradeDate='20230313', self.openTime='162000', self.closeTime='162459', self.symbol='BTCUSDT', self.open=22369.6, self.close=22386.2, self.high=22397.3, self.low=22355.0 
2023-03-13 16:25:01,531:INFO:factorcheck2:main.py:126:handleKline:185239: self.closeSec=1678695899, self.tradeDate='20230313', self.openTime='162000', self.closeTime='162459',self.symbol='BTCUSDT',self.open=22369.6, self.close=22386.2, self.high=22397.3, self.low=22355.0   
2023-03-13 16:25:01,566:INFO:factorcheck2:main.py:127:handleKline:185239: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime    closeSec  ...      low       pct  index  idx
1632  20230313   160000    160459  1678694699  ...  22435.8  0.001073   1632    0
1633  20230313   160500    160959  1678694999  ...  22356.0 -0.003301   1633    1
1634  20230313   161000    161459  1678695299  ...  22367.7 -0.000513   1634    2
1635  20230313   161500    161959  1678695599  ...  22363.4 -0.000911   1635    3
1636  20230313   162000    162459  1678695899  ...  22355.0  0.000742   1636    4

[5 rows x 11 columns]
2023-03-13 16:25:01,567:INFO:factorcheck2:main.py:128:handleKline:185239: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}


## /root/FIL/strategy/logic/log.txt ----- -----

2023-03-13 16:00:34,922:DEBUG:logic:main.py:463:getModel:885513: df_s.iloc[-5:,:] :
          date closeTime     open  ...    alpha58   alpha67   alpha72
5786  20230313    132959  22309.1  ...  48.333333  0.682197  0.194208
5787  20230313    135959  22330.6  ...  48.750000  0.686779  0.187292
5788  20230313    142959  22387.4  ...  48.333333  0.675115  0.182747
5789  20230313    145959  22320.8  ...  48.333333  0.679454  0.177013
5790  20230313    152959  22372.9  ...  48.333333  0.676763  0.172096

[5 rows x 33 columns]
0.566420664206642
acc is : 0.566420664206642
2023-03-13 16:00:35,085:INFO:logic:main.py:468:getModel:885513: df_pred.iloc[-5:,:] :
     pred    prob_0    prob_1  actual  ...       nav  sign  cost_        bm
537     0  0.500057  0.499943       1  ...  0.988087  -1.0    0.0  0.948783
538     0  0.520196  0.479804       0  ...  0.991031  -1.0    0.0  0.945957
539     1  0.453888  0.546112       1  ...  0.988718  -1.0    0.0  0.948165
540     1  0.497439  0.502561       0  ...  0.989389  -1.0    0.0  0.947521
541     1  0.469588  0.530412       1  ...  0.985230  -1.0    0.0  0.951504

[5 rows x 10 columns]
2023-03-13 16:00:35,123:INFO:logic:main.py:478:getModel:885513: df_panel.iloc[-5:,:] :
    pred    prob_0    prob_1  actual  ...       nav  sign  cost_        bm
45     1  0.499256  0.500744       1  ...  0.980380  -1.0    0.0  0.951659
46     0  0.519763  0.480237       0  ...  0.991031  -1.0    0.0  0.947712
47     1  0.453582  0.546418       1  ...  0.988718  -1.0    0.0  0.947205
48     1  0.497660  0.502340       0  ...  0.989389  -1.0    0.0  0.943904
49     1  0.469588  0.530412       1  ...  0.985230  -1.0    0.0  0.951504

[5 rows x 10 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '31.131', 'enterprice': '22174.4', 'countrevence': '0', 'unrealprofit': '-8990.6328', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '22463.2', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}


## /root/FIL/strategy/modifiedmom/log.txt ----- -----

527  20230313   155000    155959  1678694399  22463.4  22451.6 -0.000530
2023-03-13 16:00:01,999:INFO:modifiedmom:main.py:146:handleKline:185213: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': True, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True}

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=15560 

self.closeSec=1678694999, self.tradeDate='20230313', self.openTime='160000', self.closeTime='160959', self.symbol='BTCUSDT', self.open='22451.5', self.close='22401.5'
2023-03-13 16:10:01,728:INFO:modifiedmom:main.py:144:handleKline:185213: self.closeSec=1678694999, self.tradeDate='20230313', self.openTime='160000', self.closeTime='160959',self.symbol='BTCUSDT',self.open='22451.5', self.close='22401.5'
127.0.0.1 - - [13/Mar/2023 16:10:01] "POST / HTTP/1.1" 200 -
2023-03-13 16:10:01,751:INFO:modifiedmom:main.py:145:handleKline:185213: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec     open    close       pct
524  20230313   152000    152959  1678692599  22343.1  22357.6  0.000649
525  20230313   153000    153959  1678693199  22357.6    22445  0.003909
526  20230313   154000    154959  1678693799  22445.1  22463.5  0.000824
527  20230313   155000    155959  1678694399  22463.4  22451.6 -0.000530
528  20230313   160000    160959  1678694999  22451.5  22401.5 -0.002231
2023-03-13 16:10:01,751:INFO:modifiedmom:main.py:146:handleKline:185213: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': True, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True}

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=15561 

self.closeSec=1678695599, self.tradeDate='20230313', self.openTime='161000', self.closeTime='161959', self.symbol='BTCUSDT', self.open='22401.6', self.close='22369.5'
127.0.0.1 - - [13/Mar/2023 16:20:02] "POST / HTTP/1.1" 200 -
2023-03-13 16:20:05,106:INFO:modifiedmom:main.py:144:handleKline:185213: self.closeSec=1678695599, self.tradeDate='20230313', self.openTime='161000', self.closeTime='161959',self.symbol='BTCUSDT',self.open='22401.6', self.close='22369.5'
2023-03-13 16:20:06,027:INFO:modifiedmom:main.py:145:handleKline:185213: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec     open    close       pct
525  20230313   153000    153959  1678693199  22357.6    22445  0.003909
526  20230313   154000    154959  1678693799  22445.1  22463.5  0.000824
527  20230313   155000    155959  1678694399  22463.4  22451.6 -0.000530
528  20230313   160000    160959  1678694999  22451.5  22401.5 -0.002231
529  20230313   161000    161959  1678695599  22401.6  22369.5 -0.001428
2023-03-13 16:20:06,028:INFO:modifiedmom:main.py:146:handleKline:185213: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': True, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True}


## /root/FIL/strategy/percentile_regression_step2/log.txt ----- -----

127.0.0.1 - - [21/Feb/2023 09:30:01] "POST / HTTP/1.1" 200 -
2023-02-21 09:30:03,026:DEBUG:percentile_regression_step2:main.py:154:get_signal:1265985: df_id.iloc[-5:,:] :
                 daytime     hms    close  ...  pct_10  pct_20  factor
144  2023/02/21 07:00:00  070000  24795.1  ...     NaN     NaN       0
145  2023/02/21 07:30:00  073000  24849.9  ...     NaN     NaN       0
146  2023/02/21 08:00:00  080000  24819.0  ...     NaN     NaN       0
147  2023/02/21 08:30:00  083000  24860.9  ...     NaN     NaN       0
148  2023/02/21 09:00:00  090000  24831.0  ...     NaN     NaN       0

[5 rows x 10 columns]
127.0.0.1 - - [21/Feb/2023 10:00:02] "POST / HTTP/1.1" 200 -
2023-02-21 10:00:03,553:DEBUG:percentile_regression_step2:main.py:154:get_signal:1265985: df_id.iloc[-5:,:] :
                 daytime     hms    close  ...  pct_10  pct_20  factor
144  2023/02/21 07:30:00  073000  24849.9  ...     NaN     NaN       0
145  2023/02/21 08:00:00  080000  24819.0  ...     NaN     NaN       0
146  2023/02/21 08:30:00  083000  24860.9  ...     NaN     NaN       0
147  2023/02/21 09:00:00  090000  24831.0  ...     NaN     NaN       0
148  2023/02/21 09:30:00  093000  24870.0  ...     NaN     NaN       0

[5 rows x 10 columns]
127.0.0.1 - - [21/Feb/2023 10:30:01] "POST / HTTP/1.1" 200 -
2023-02-21 10:30:03,245:DEBUG:percentile_regression_step2:main.py:154:get_signal:1265985: df_id.iloc[-5:,:] :
                 daytime     hms    close  ...  pct_10  pct_20  factor
144  2023/02/21 08:00:00  080000  24819.0  ...     NaN     NaN       0
145  2023/02/21 08:30:00  083000  24860.9  ...     NaN     NaN       0
146  2023/02/21 09:00:00  090000  24831.0  ...     NaN     NaN       0
147  2023/02/21 09:30:00  093000  24870.0  ...     NaN     NaN       0
148  2023/02/21 10:00:00  100000  24936.1  ...     NaN     NaN       0

[5 rows x 10 columns]


## /root/FIL/strategy/pyemd/log.txt ----- -----

17519  20230313   155000    155959  1678694399  22463.4  22451.6
2023-03-13 16:00:01,960:INFO:pyemd2:main.py:127:handleKline:185189: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=15561 

self.closeSec=1678694999, self.tradeDate='20230313', self.openTime='160000', self.closeTime='160959', self.symbol='BTCUSDT', self.open='22451.5', self.close='22401.5'
2023-03-13 16:10:01,738:INFO:pyemd2:main.py:125:handleKline:185189: self.closeSec=1678694999, self.tradeDate='20230313', self.openTime='160000', self.closeTime='160959',self.symbol='BTCUSDT',self.open='22451.5', self.close='22401.5'
127.0.0.1 - - [13/Mar/2023 16:10:01] "POST / HTTP/1.1" 200 -
2023-03-13 16:10:01,761:INFO:pyemd2:main.py:126:handleKline:185189: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
17516  20230313   152000    152959  1678692599  22343.1  22357.6
17517  20230313   153000    153959  1678693199  22357.6    22445
17518  20230313   154000    154959  1678693799  22445.1  22463.5
17519  20230313   155000    155959  1678694399  22463.4  22451.6
17520  20230313   160000    160959  1678694999  22451.5  22401.5
2023-03-13 16:10:01,761:INFO:pyemd2:main.py:127:handleKline:185189: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=15562 

self.closeSec=1678695599, self.tradeDate='20230313', self.openTime='161000', self.closeTime='161959', self.symbol='BTCUSDT', self.open='22401.6', self.close='22369.5'
127.0.0.1 - - [13/Mar/2023 16:20:02] "POST / HTTP/1.1" 200 -
2023-03-13 16:20:08,550:INFO:pyemd2:main.py:125:handleKline:185189: self.closeSec=1678695599, self.tradeDate='20230313', self.openTime='161000', self.closeTime='161959',self.symbol='BTCUSDT',self.open='22401.6', self.close='22369.5'
2023-03-13 16:20:08,721:INFO:pyemd2:main.py:126:handleKline:185189: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
17517  20230313   153000    153959  1678693199  22357.6    22445
17518  20230313   154000    154959  1678693799  22445.1  22463.5
17519  20230313   155000    155959  1678694399  22463.4  22451.6
17520  20230313   160000    160959  1678694999  22451.5  22401.5
17521  20230313   161000    161959  1678695599  22401.6  22369.5
2023-03-13 16:20:08,726:INFO:pyemd2:main.py:127:handleKline:185189: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}


## /root/FIL/strategy/similarity/log.txt ----- -----

12191  20230313   155000    155959  1678694399  22463.4  22451.6
2023-03-13 16:00:02,011:INFO:testStrategy:main.py:103:handleKline:185174: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': True, 'isOpenSell': False, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True, 'isCorr': False}

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=15561 

self.closeSec=1678694999, self.tradeDate='20230313', self.openTime='160000', self.closeTime='160959', self.symbol='BTCUSDT', self.open='22451.5', self.close='22401.5'
127.0.0.1 - - [13/Mar/2023 16:10:01] "POST / HTTP/1.1" 200 -
2023-03-13 16:10:01,761:INFO:testStrategy:main.py:101:handleKline:185174: self.closeSec=1678694999, self.tradeDate='20230313', self.openTime='160000', self.closeTime='160959',self.symbol='BTCUSDT',self.open='22451.5', self.close='22401.5'
2023-03-13 16:10:01,807:INFO:testStrategy:main.py:102:handleKline:185174: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
12188  20230313   152000    152959  1678692599  22343.1  22357.6
12189  20230313   153000    153959  1678693199  22357.6    22445
12190  20230313   154000    154959  1678693799  22445.1  22463.5
12191  20230313   155000    155959  1678694399  22463.4  22451.6
12192  20230313   160000    160959  1678694999  22451.5  22401.5
2023-03-13 16:10:01,811:INFO:testStrategy:main.py:103:handleKline:185174: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': True, 'isOpenSell': False, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True, 'isCorr': False}

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=15562 

self.closeSec=1678695599, self.tradeDate='20230313', self.openTime='161000', self.closeTime='161959', self.symbol='BTCUSDT', self.open='22401.6', self.close='22369.5'
127.0.0.1 - - [13/Mar/2023 16:20:02] "POST / HTTP/1.1" 200 -
2023-03-13 16:20:07,709:INFO:testStrategy:main.py:101:handleKline:185174: self.closeSec=1678695599, self.tradeDate='20230313', self.openTime='161000', self.closeTime='161959',self.symbol='BTCUSDT',self.open='22401.6', self.close='22369.5'
2023-03-13 16:20:08,426:INFO:testStrategy:main.py:102:handleKline:185174: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
12189  20230313   153000    153959  1678693199  22357.6    22445
12190  20230313   154000    154959  1678693799  22445.1  22463.5
12191  20230313   155000    155959  1678694399  22463.4  22451.6
12192  20230313   160000    160959  1678694999  22451.5  22401.5
12193  20230313   161000    161959  1678695599  22401.6  22369.5
2023-03-13 16:20:08,427:INFO:testStrategy:main.py:103:handleKline:185174: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': True, 'isOpenSell': False, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True, 'isCorr': False}


## /root/FIL/strategy/sr_min/log.txt ----- -----

--handleKline--: 127.0.0.1 - - [13/Mar/2023 16:20:01] "POST / HTTP/1.1" 200 -
 version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=0, self.total=1000000.0, self.flagDict['side']='', self.tradeCount=0, self.count=26554
self.closeSec=1678695599, self.tradeDate='20230313', self.openTime='161500', self.closeTime='161959', self.symbol='BTCUSDT', self.open=22388.4, self.close=22369.6, self.high=22419.9, self.low=22363.4, self.vol=2436.074, self.amt=54552711.8412 
2023-03-13 16:20:01,697:INFO:sr_min:main.py:172:handleKline:449472: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5951  20230313   155500    155959  ...         0.0        0.0       0
5952  20230313   160000    160459  ...         0.0        0.0       0
5953  20230313   160500    160959  ...         0.0        0.0       0
5954  20230313   161000    161459  ...         0.0        0.0       0
5955  20230313   161500    161959  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-03-13 16:20:01,699:INFO:sr_min:main.py:175:handleKline:449472: self.closeSec=1678695599, self.tradeDate='20230313', self.openTime='161500', self.closeTime='161959',self.symbol='BTCUSDT',self.open=22388.4, self.close=22369.6, self.high=22419.9, self.low=22363.4, self.vol=2436.074, self.amt=54552711.8412, ukdf['pct'].iloc[-1]=-0.000911 , ukdf['amount'].iloc[-1]=54552711.8412, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5955, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': []}
type(curSign)=<class 'int'>, curSign=0, self.sign=0
127.0.0.1 - - [13/Mar/2023 16:25:01] "POST / HTTP/1.1" 200 -
--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=0, self.total=1000000.0, self.flagDict['side']='', self.tradeCount=0, self.count=26555
self.closeSec=1678695899, self.tradeDate='20230313', self.openTime='162000', self.closeTime='162459', self.symbol='BTCUSDT', self.open=22369.6, self.close=22386.2, self.high=22397.3, self.low=22355.0, self.vol=2157.118, self.amt=48268457.7992 
2023-03-13 16:25:01,631:INFO:sr_min:main.py:172:handleKline:449472: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5952  20230313   160000    160459  ...         0.0        0.0       0
5953  20230313   160500    160959  ...         0.0        0.0       0
5954  20230313   161000    161459  ...         0.0        0.0       0
5955  20230313   161500    161959  ...         0.0        0.0       0
5956  20230313   162000    162459  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-03-13 16:25:01,636:INFO:sr_min:main.py:175:handleKline:449472: self.closeSec=1678695899, self.tradeDate='20230313', self.openTime='162000', self.closeTime='162459',self.symbol='BTCUSDT',self.open=22369.6, self.close=22386.2, self.high=22397.3, self.low=22355.0, self.vol=2157.118, self.amt=48268457.7992, ukdf['pct'].iloc[-1]=0.000742 , ukdf['amount'].iloc[-1]=48268457.7992, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5956, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': []}
type(curSign)=<class 'int'>, curSign=0, self.sign=0


## /root/FIL/strategy/s_rsrs/log.txt ----- -----

721  20230313   040000    075959  1678665599  ...    721  0.700134  0.532409     NaN
722  20230313   080000    115959  1678679999  ...    722  0.753174  0.742093     1.0

[5 rows x 15 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '55.825', 'enterprice': '20070', 'countrevence': '0', 'unrealprofit': '120333.11223889725', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '22225.54164333', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'numpy.int64'>, curSign=1, self.sign=1
--handleKline--:  version='2.0.0', self.name='s_rsrs', self.symbol='BTCUSDT', interval='4h', intervalSec=14400, wid=25, thd=0.6, self.sign=1, self.total=1119287.34225, self.flagDict['side']='buy', self.tradeCount=24, self.count=648
self.closeSec=1678694399, self.tradeDate='20230313', self.openTime='120000', self.closeTime='155959', self.symbol='BTCUSDT', self.open=22221.8, self.close=22451.6, self.high=22500.0, self.low=22213.8, self.vol=107549.845, self.amt=2405122560.26451 
127.0.0.1 - - [13/Mar/2023 16:00:01] "POST / HTTP/1.1" 200 -
2023-03-13 16:00:01,794:INFO:s_rsrs:main.py:141:handleKline:185271: self.closeSec=1678694399, self.tradeDate='20230313', self.openTime='120000', self.closeTime='155959',self.symbol='BTCUSDT',self.open=22221.8, self.close=22451.6, self.high=22500.0, self.low=22213.8, self.vol=107549.845, self.amt=2405122560.26451 
2023-03-13 16:00:01,825:INFO:s_rsrs:main.py:142:handleKline:185271: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime  ...         vol           amt       pct
719  20230312   200000    235959  ...   73260.469  1.491894e+09 -0.004262
720  20230313   000000    035959  ...  320423.397  6.686396e+09  0.020769
721  20230313   040000    075959  ...  327344.807  7.038856e+09  0.058530
722  20230313   080000    115959  ...  220127.800  4.895808e+09  0.010711
723  20230313   120000    155959  ...  107549.845  2.405123e+09  0.010346

[5 rows x 11 columns]
2023-03-13 16:00:04,257:INFO:s_rsrs:main.py:151:handleKline:185271: df_s.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec  ...  index      beta    zscore  signal
719  20230312   200000    235959  1678636799  ...    719  0.768772  0.738695     1.0
720  20230313   000000    035959  1678651199  ...    720  0.718037  0.579599     NaN
721  20230313   040000    075959  1678665599  ...    721  0.700134  0.532409     NaN
722  20230313   080000    115959  1678679999  ...    722  0.753174  0.742093     1.0
723  20230313   120000    155959  1678694399  ...    723  0.785806  0.877901     1.0

[5 rows x 15 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '55.825', 'enterprice': '20070', 'countrevence': '0', 'unrealprofit': '133050.36304315525', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '22453.34730037', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'numpy.int64'>, curSign=1, self.sign=1


