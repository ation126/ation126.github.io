# 20230202 16:35:47

## /root/FIL/strategy/amihud/log.txt ----- -----

--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=993672.4896432, self.flagDict['side']='sell', self.tradeCount=2, self.count=19326
self.closeSec=1675326599, self.tradeDate='20230202', self.openTime='162500', self.closeTime='162959', self.symbol='BTCUSDT', self.open=23828.6, self.close=23846.5, self.high=23860.0, self.low=23817.6, self.vol=1600.282, self.amt=38153090.8056 
127.0.0.1 - - [02/Feb/2023 16:30:00] "POST / HTTP/1.1" 200 -
2023-02-02 16:30:00,960:INFO:amihud:main.py:172:handleKline:200676: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5953  20230202   160500    160959  ...         0.0        0.0       0
5954  20230202   161000    161459  ...         0.0        0.0       0
5955  20230202   161500    161959  ...         0.0        0.0       0
5956  20230202   162000    162459  ...         0.0        0.0       0
5957  20230202   162500    162959  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-02-02 16:30:00,960:INFO:amihud:main.py:175:handleKline:200676: self.closeSec=1675326599, self.tradeDate='20230202', self.openTime='162500', self.closeTime='162959',self.symbol='BTCUSDT',self.open=23828.6, self.close=23846.5, self.high=23860.0, self.low=23817.6, self.vol=1600.282, self.amt=38153090.8056, ukdf['pct'].iloc[-1]=0.000747 , ukdf['amount'].iloc[-1]=38153090.8056, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5957, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '60.176', 'enterprice': '16529.3', 'countrevence': '0', 'unrealprofit': '-440217.528', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '23844.8', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1
--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=993672.4896432, self.flagDict['side']='sell', self.tradeCount=2, self.count=19327
self.closeSec=1675326899, self.tradeDate='20230202', self.openTime='163000', self.closeTime='163459', self.symbol='BTCUSDT', self.open=23846.5, self.close=23812.7, self.high=23852.3, self.low=23801.4, self.vol=1531.212, self.amt=36477473.9158 
127.0.0.1 - - [02/Feb/2023 16:35:00] "POST / HTTP/1.1" 200 -
2023-02-02 16:35:00,540:INFO:amihud:main.py:172:handleKline:200676: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5954  20230202   161000    161459  ...         0.0        0.0       0
5955  20230202   161500    161959  ...         0.0        0.0       0
5956  20230202   162000    162459  ...         0.0        0.0       0
5957  20230202   162500    162959  ...         0.0        0.0       0
5958  20230202   163000    163459  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-02-02 16:35:00,542:INFO:amihud:main.py:175:handleKline:200676: self.closeSec=1675326899, self.tradeDate='20230202', self.openTime='163000', self.closeTime='163459',self.symbol='BTCUSDT',self.open=23846.5, self.close=23812.7, self.high=23852.3, self.low=23801.4, self.vol=1531.212, self.amt=36477473.9158, ukdf['pct'].iloc[-1]=-0.001417 , ukdf['amount'].iloc[-1]=36477473.9158, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5958, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '60.176', 'enterprice': '16529.3', 'countrevence': '0', 'unrealprofit': '-438264.49034279296', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '23812.34457496', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1


## /root/FIL/strategy/factorcheck/log.txt ----- -----

1636  20230202   162000    162459  1675326299  ...  23813.2  0.000378   1636    4
1637  20230202   162500    162959  1675326599  ...  23817.6  0.000747   1637    5

[5 rows x 11 columns]
2023-02-02 16:30:00,918:INFO:factorcheck2:main.py:128:handleKline:185239: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}
2023-02-02 16:30:01,022:INFO:factorcheck2:main.py:145:handleKline:185239: df_panel.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec  ...       pct  index  idx    factor
229  20230202   142500    142959  1675319399  ...  0.001333   1613    5  0.351601
230  20230202   145500    145959  1675321199  ...  0.000496   1619    5  0.351203
231  20230202   152500    152959  1675322999  ...  0.000025   1625    5  0.350346
232  20230202   155500    155959  1675324799  ...  0.000888   1631    5  0.350113
233  20230202   162500    162959  1675326599  ...  0.000747   1637    5  0.348736

[5 rows x 12 columns]
127.0.0.1 - - [02/Feb/2023 16:35:00] "POST / HTTP/1.1" 200 -

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=35, self.factor=0.3487355996622035, self.count=19893 

self.closeSec=1675326899, self.tradeDate='20230202', self.openTime='163000', self.closeTime='163459', self.symbol='BTCUSDT', self.open=23846.5, self.close=23812.7, self.high=23852.3, self.low=23801.4 
2023-02-02 16:35:00,407:INFO:factorcheck2:main.py:126:handleKline:185239: self.closeSec=1675326899, self.tradeDate='20230202', self.openTime='163000', self.closeTime='163459',self.symbol='BTCUSDT',self.open=23846.5, self.close=23812.7, self.high=23852.3, self.low=23801.4   
2023-02-02 16:35:00,449:INFO:factorcheck2:main.py:127:handleKline:185239: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime    closeSec  ...      low       pct  index  idx
1634  20230202   161000    161459  1675325699  ...  23803.1 -0.000672   1634    2
1635  20230202   161500    161959  1675325999  ...  23807.3  0.000445   1635    3
1636  20230202   162000    162459  1675326299  ...  23813.2  0.000378   1636    4
1637  20230202   162500    162959  1675326599  ...  23817.6  0.000747   1637    5
1638  20230202   163000    163459  1675326899  ...  23801.4 -0.001417   1638    0

[5 rows x 11 columns]
2023-02-02 16:35:00,449:INFO:factorcheck2:main.py:128:handleKline:185239: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}


## /root/FIL/strategy/logic/log.txt ----- -----

2023-02-02 16:30:32,244:DEBUG:logic:main.py:463:getModel:885513: df_s.iloc[-5:,:] :
          date closeTime     open  ...    alpha58   alpha67   alpha72
5787  20230202    135959  23864.1  ...  49.583333  0.588594  0.275362
5788  20230202    142959  23809.9  ...  49.583333  0.573872  0.280545
5789  20230202    145959  23739.7  ...  49.583333  0.582110  0.283023
5790  20230202    152959  23793.9  ...  50.000000  0.585782  0.284275
5791  20230202    155959  23818.3  ...  49.583333  0.579121  0.286804

[5 rows x 33 columns]
0.5313653136531366
acc is : 0.5313653136531366
2023-02-02 16:30:32,403:INFO:logic:main.py:468:getModel:885513: df_pred.iloc[-5:,:] :
     pred    prob_0    prob_1  actual  ...       nav  sign  cost_        bm
537     1  0.479913  0.520087       0  ...  0.927416   1.0    0.0  1.041896
538     1  0.474112  0.525888       1  ...  0.929537   1.0    0.0  1.044279
539     1  0.496175  0.503825       1  ...  0.930491   1.0    0.0  1.045350
540     1  0.493170  0.506830       0  ...  0.929268   1.0    0.0  1.043976
541     1  0.483644  0.516356       1  ...  0.931592   1.0    0.0  1.046588

[5 rows x 10 columns]
2023-02-02 16:30:32,433:INFO:logic:main.py:478:getModel:885513: df_panel.iloc[-5:,:] :
    pred    prob_0    prob_1  actual  ...       nav  sign  cost_        bm
45     1  0.477916  0.522084       0  ...  0.935647   1.0    0.0  1.040973
46     1  0.473081  0.526919       1  ...  0.937788   1.0    0.0  1.044421
47     1  0.494294  0.505706       1  ...  0.938753   1.0    0.0  1.039016
48     1  0.492259  0.507741       0  ...  0.937519   1.0    0.0  1.039732
49     1  0.483644  0.516356       1  ...  0.931592   1.0    0.0  1.046588

[5 rows x 10 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '30.955', 'enterprice': '23100.3', 'countrevence': '0', 'unrealprofit': '23169.8175', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '23848.8', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}


## /root/FIL/strategy/modifiedmom/log.txt ----- -----

528  20230202   160000    160959  1675325399    23787  23825.1  0.001602
2023-02-02 16:10:01,777:INFO:modifiedmom:main.py:146:handleKline:185213: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': True, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True}
127.0.0.1 - - [02/Feb/2023 16:20:00] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=9945 

self.closeSec=1675325999, self.tradeDate='20230202', self.openTime='161000', self.closeTime='161959', self.symbol='BTCUSDT', self.open='23825', self.close='23819.7'
2023-02-02 16:20:00,758:INFO:modifiedmom:main.py:144:handleKline:185213: self.closeSec=1675325999, self.tradeDate='20230202', self.openTime='161000', self.closeTime='161959',self.symbol='BTCUSDT',self.open='23825', self.close='23819.7'
2023-02-02 16:20:00,785:INFO:modifiedmom:main.py:145:handleKline:185213: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec     open    close       pct
525  20230202   153000    153959  1675323599  23818.3  23772.5 -0.001923
526  20230202   154000    154959  1675324199  23772.5  23755.1 -0.000732
527  20230202   155000    155959  1675324799  23755.1    23787  0.001343
528  20230202   160000    160959  1675325399    23787  23825.1  0.001602
529  20230202   161000    161959  1675325999    23825  23819.7 -0.000227
2023-02-02 16:20:00,785:INFO:modifiedmom:main.py:146:handleKline:185213: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': True, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True}
127.0.0.1 - - [02/Feb/2023 16:30:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=9946 

self.closeSec=1675326599, self.tradeDate='20230202', self.openTime='162000', self.closeTime='162959', self.symbol='BTCUSDT', self.open='23816.8', self.close='23846.5'
2023-02-02 16:30:01,061:INFO:modifiedmom:main.py:144:handleKline:185213: self.closeSec=1675326599, self.tradeDate='20230202', self.openTime='162000', self.closeTime='162959',self.symbol='BTCUSDT',self.open='23816.8', self.close='23846.5'
2023-02-02 16:30:01,095:INFO:modifiedmom:main.py:145:handleKline:185213: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec     open    close       pct
526  20230202   154000    154959  1675324199  23772.5  23755.1 -0.000732
527  20230202   155000    155959  1675324799  23755.1    23787  0.001343
528  20230202   160000    160959  1675325399    23787  23825.1  0.001602
529  20230202   161000    161959  1675325999    23825  23819.7 -0.000227
530  20230202   162000    162959  1675326599  23816.8  23846.5  0.001125
2023-02-02 16:30:01,095:INFO:modifiedmom:main.py:146:handleKline:185213: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': True, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True}


## /root/FIL/strategy/pyemd/log.txt ----- -----

17520  20230202   160000    160959  1675325399    23787  23825.1
2023-02-02 16:10:01,790:INFO:pyemd2:main.py:127:handleKline:185189: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}
127.0.0.1 - - [02/Feb/2023 16:20:00] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=9946 

self.closeSec=1675325999, self.tradeDate='20230202', self.openTime='161000', self.closeTime='161959', self.symbol='BTCUSDT', self.open='23825', self.close='23819.7'
2023-02-02 16:20:00,768:INFO:pyemd2:main.py:125:handleKline:185189: self.closeSec=1675325999, self.tradeDate='20230202', self.openTime='161000', self.closeTime='161959',self.symbol='BTCUSDT',self.open='23825', self.close='23819.7'
2023-02-02 16:20:00,800:INFO:pyemd2:main.py:126:handleKline:185189: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
17517  20230202   153000    153959  1675323599  23818.3  23772.5
17518  20230202   154000    154959  1675324199  23772.5  23755.1
17519  20230202   155000    155959  1675324799  23755.1    23787
17520  20230202   160000    160959  1675325399    23787  23825.1
17521  20230202   161000    161959  1675325999    23825  23819.7
2023-02-02 16:20:00,801:INFO:pyemd2:main.py:127:handleKline:185189: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}
127.0.0.1 - - [02/Feb/2023 16:30:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=9947 

self.closeSec=1675326599, self.tradeDate='20230202', self.openTime='162000', self.closeTime='162959', self.symbol='BTCUSDT', self.open='23816.8', self.close='23846.5'
2023-02-02 16:30:01,075:INFO:pyemd2:main.py:125:handleKline:185189: self.closeSec=1675326599, self.tradeDate='20230202', self.openTime='162000', self.closeTime='162959',self.symbol='BTCUSDT',self.open='23816.8', self.close='23846.5'
2023-02-02 16:30:01,106:INFO:pyemd2:main.py:126:handleKline:185189: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
17518  20230202   154000    154959  1675324199  23772.5  23755.1
17519  20230202   155000    155959  1675324799  23755.1    23787
17520  20230202   160000    160959  1675325399    23787  23825.1
17521  20230202   161000    161959  1675325999    23825  23819.7
17522  20230202   162000    162959  1675326599  23816.8  23846.5
2023-02-02 16:30:01,106:INFO:pyemd2:main.py:127:handleKline:185189: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}


## /root/FIL/strategy/similarity/log.txt ----- -----

12192  20230202   160000    160959  1675325399    23787  23825.1
2023-02-02 16:10:01,780:INFO:testStrategy:main.py:103:handleKline:185174: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': True, 'isOpenSell': False, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True, 'isCorr': False}
127.0.0.1 - - [02/Feb/2023 16:20:00] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=9946 

self.closeSec=1675325999, self.tradeDate='20230202', self.openTime='161000', self.closeTime='161959', self.symbol='BTCUSDT', self.open='23825', self.close='23819.7'
2023-02-02 16:20:00,753:INFO:testStrategy:main.py:101:handleKline:185174: self.closeSec=1675325999, self.tradeDate='20230202', self.openTime='161000', self.closeTime='161959',self.symbol='BTCUSDT',self.open='23825', self.close='23819.7'
2023-02-02 16:20:00,795:INFO:testStrategy:main.py:102:handleKline:185174: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
12189  20230202   153000    153959  1675323599  23818.3  23772.5
12190  20230202   154000    154959  1675324199  23772.5  23755.1
12191  20230202   155000    155959  1675324799  23755.1    23787
12192  20230202   160000    160959  1675325399    23787  23825.1
12193  20230202   161000    161959  1675325999    23825  23819.7
2023-02-02 16:20:00,795:INFO:testStrategy:main.py:103:handleKline:185174: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': True, 'isOpenSell': False, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True, 'isCorr': False}

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=9947 

self.closeSec=1675326599, self.tradeDate='20230202', self.openTime='162000', self.closeTime='162959', self.symbol='BTCUSDT', self.open='23816.8', self.close='23846.5'
127.0.0.1 - - [02/Feb/2023 16:30:01] "POST / HTTP/1.1" 200 -
2023-02-02 16:30:01,071:INFO:testStrategy:main.py:101:handleKline:185174: self.closeSec=1675326599, self.tradeDate='20230202', self.openTime='162000', self.closeTime='162959',self.symbol='BTCUSDT',self.open='23816.8', self.close='23846.5'
2023-02-02 16:30:01,102:INFO:testStrategy:main.py:102:handleKline:185174: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
12190  20230202   154000    154959  1675324199  23772.5  23755.1
12191  20230202   155000    155959  1675324799  23755.1    23787
12192  20230202   160000    160959  1675325399    23787  23825.1
12193  20230202   161000    161959  1675325999    23825  23819.7
12194  20230202   162000    162959  1675326599  23816.8  23846.5
2023-02-02 16:30:01,102:INFO:testStrategy:main.py:103:handleKline:185174: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': True, 'isOpenSell': False, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True, 'isCorr': False}


## /root/FIL/strategy/sr_min/log.txt ----- -----

--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=0, self.total=1000000.0, self.flagDict['side']='', self.tradeCount=0, self.count=15324
self.closeSec=1675326599, self.tradeDate='20230202', self.openTime='162500', self.closeTime='162959', self.symbol='BTCUSDT', self.open=23828.6, self.close=23846.5, self.high=23860.0, self.low=23817.6, self.vol=1600.282, self.amt=38153090.8056 
127.0.0.1 - - [02/Feb/2023 16:30:00] "POST / HTTP/1.1" 200 -
2023-02-02 16:30:00,978:INFO:sr_min:main.py:172:handleKline:449472: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5953  20230202   160500    160959  ...         0.0        0.0       0
5954  20230202   161000    161459  ...         0.0        0.0       0
5955  20230202   161500    161959  ...         0.0        0.0       0
5956  20230202   162000    162459  ...         0.0        0.0       0
5957  20230202   162500    162959  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-02-02 16:30:00,983:INFO:sr_min:main.py:175:handleKline:449472: self.closeSec=1675326599, self.tradeDate='20230202', self.openTime='162500', self.closeTime='162959',self.symbol='BTCUSDT',self.open=23828.6, self.close=23846.5, self.high=23860.0, self.low=23817.6, self.vol=1600.282, self.amt=38153090.8056, ukdf['pct'].iloc[-1]=0.000747 , ukdf['amount'].iloc[-1]=38153090.8056, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5957, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': []}
type(curSign)=<class 'int'>, curSign=0, self.sign=0
--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=0, self.total=1000000.0, self.flagDict['side']='', self.tradeCount=0, self.count=15325
self.closeSec=1675326899, self.tradeDate='20230202', self.openTime='163000', self.closeTime='163459', self.symbol='BTCUSDT', self.open=23846.5, self.close=23812.7, self.high=23852.3, self.low=23801.4, self.vol=1531.212, self.amt=36477473.9158 
127.0.0.1 - - [02/Feb/2023 16:35:00] "POST / HTTP/1.1" 200 -
2023-02-02 16:35:00,496:INFO:sr_min:main.py:172:handleKline:449472: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5954  20230202   161000    161459  ...         0.0        0.0       0
5955  20230202   161500    161959  ...         0.0        0.0       0
5956  20230202   162000    162459  ...         0.0        0.0       0
5957  20230202   162500    162959  ...         0.0        0.0       0
5958  20230202   163000    163459  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-02-02 16:35:00,496:INFO:sr_min:main.py:175:handleKline:449472: self.closeSec=1675326899, self.tradeDate='20230202', self.openTime='163000', self.closeTime='163459',self.symbol='BTCUSDT',self.open=23846.5, self.close=23812.7, self.high=23852.3, self.low=23801.4, self.vol=1531.212, self.amt=36477473.9158, ukdf['pct'].iloc[-1]=-0.001417 , ukdf['amount'].iloc[-1]=36477473.9158, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5958, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': []}
type(curSign)=<class 'int'>, curSign=0, self.sign=0


## /root/FIL/strategy/s_rsrs/log.txt ----- -----

721  20230202   040000    075959  1675295999  ...    721  0.558106  0.277750     NaN
722  20230202   080000    115959  1675310399  ...    722  0.690950  0.654160     1.0

[5 rows x 15 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '38.964', 'enterprice': '23700.1', 'countrevence': '0', 'unrealprofit': '6128.2328038056', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '23857.3793554', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'numpy.int64'>, curSign=1, self.sign=1
127.0.0.1 - - [02/Feb/2023 16:00:01] "POST / HTTP/1.1" 200 -
--handleKline--:  version='2.0.0', self.name='s_rsrs', self.symbol='BTCUSDT', interval='4h', intervalSec=14400, wid=25, thd=0.6, self.sign=1, self.total=922527.2457035999, self.flagDict['side']='buy', self.tradeCount=16, self.count=414
self.closeSec=1675324799, self.tradeDate='20230202', self.openTime='120000', self.closeTime='155959', self.symbol='BTCUSDT', self.open=23852.1, self.close=23787.0, self.high=23927.5, self.low=23660.0, self.vol=48942.495, self.amt=1165257382.8579 
2023-02-02 16:00:01,741:INFO:s_rsrs:main.py:141:handleKline:185271: self.closeSec=1675324799, self.tradeDate='20230202', self.openTime='120000', self.closeTime='155959',self.symbol='BTCUSDT',self.open=23852.1, self.close=23787.0, self.high=23927.5, self.low=23660.0, self.vol=48942.495, self.amt=1165257382.8579 
2023-02-02 16:00:01,786:INFO:s_rsrs:main.py:142:handleKline:185271: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime  ...         vol           amt       pct
719  20230201   200000    235959  ...   71259.336  1.643445e+09 -0.004351
720  20230202   000000    035959  ...  215468.368  4.979553e+09  0.017592
721  20230202   040000    075959  ...  160059.153  3.779794e+09  0.014974
722  20230202   080000    115959  ...  136849.095  3.284367e+09  0.005150
723  20230202   120000    155959  ...   48942.495  1.165257e+09 -0.002734

[5 rows x 11 columns]
2023-02-02 16:00:03,672:INFO:s_rsrs:main.py:151:handleKline:185271: df_s.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec  ...  index      beta    zscore  signal
719  20230201   200000    235959  1675267199  ...    719  0.637503  0.529206     NaN
720  20230202   000000    035959  1675281599  ...    720  0.509222  0.146437     NaN
721  20230202   040000    075959  1675295999  ...    721  0.558106  0.277750     NaN
722  20230202   080000    115959  1675310399  ...    722  0.690950  0.654160     1.0
723  20230202   120000    155959  1675324799  ...    723  0.707133  0.686136     1.0

[5 rows x 15 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '38.964', 'enterprice': '23700.1', 'countrevence': '0', 'unrealprofit': '3371.50349609208', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '23786.62868022', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'numpy.int64'>, curSign=1, self.sign=1


