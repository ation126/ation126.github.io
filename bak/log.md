# 20230211 16:35:59

## /root/FIL/strategy/amihud/log.txt ----- -----

--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=993672.4896432, self.flagDict['side']='sell', self.tradeCount=2, self.count=21918
self.closeSec=1676104199, self.tradeDate='20230211', self.openTime='162500', self.closeTime='162959', self.symbol='BTCUSDT', self.open=21679.9, self.close=21672.4, self.high=21680.0, self.low=21672.4, self.vol=341.749, self.amt=7408036.3946 
127.0.0.1 - - [11/Feb/2023 16:30:00] "POST / HTTP/1.1" 200 -
2023-02-11 16:30:00,634:INFO:amihud:main.py:172:handleKline:200676: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5953  20230211   160500    160959  ...         0.0        0.0       0
5954  20230211   161000    161459  ...         0.0        0.0       0
5955  20230211   161500    161959  ...         0.0        0.0       0
5956  20230211   162000    162459  ...         0.0        0.0       0
5957  20230211   162500    162959  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-02-11 16:30:00,636:INFO:amihud:main.py:175:handleKline:200676: self.closeSec=1676104199, self.tradeDate='20230211', self.openTime='162500', self.closeTime='162959',self.symbol='BTCUSDT',self.open=21679.9, self.close=21672.4, self.high=21680.0, self.low=21672.4, self.vol=341.749, self.amt=7408036.3946, ukdf['pct'].iloc[-1]=-0.000341 , ukdf['amount'].iloc[-1]=7408036.3946, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5957, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '60.176', 'enterprice': '16529.3', 'countrevence': '0', 'unrealprofit': '-309548.4746353384', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '21673.35202465', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1
127.0.0.1 - - [11/Feb/2023 16:35:00] "POST / HTTP/1.1" 200 -
--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=993672.4896432, self.flagDict['side']='sell', self.tradeCount=2, self.count=21919
self.closeSec=1676104499, self.tradeDate='20230211', self.openTime='163000', self.closeTime='163459', self.symbol='BTCUSDT', self.open=21672.4, self.close=21676.2, self.high=21678.8, self.low=21670.0, self.vol=527.507, self.amt=11433465.4182 
2023-02-11 16:35:00,551:INFO:amihud:main.py:172:handleKline:200676: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5954  20230211   161000    161459  ...         0.0        0.0       0
5955  20230211   161500    161959  ...         0.0        0.0       0
5956  20230211   162000    162459  ...         0.0        0.0       0
5957  20230211   162500    162959  ...         0.0        0.0       0
5958  20230211   163000    163459  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-02-11 16:35:00,551:INFO:amihud:main.py:175:handleKline:200676: self.closeSec=1676104499, self.tradeDate='20230211', self.openTime='163000', self.closeTime='163459',self.symbol='BTCUSDT',self.open=21672.4, self.close=21676.2, self.high=21678.8, self.low=21670.0, self.vol=527.507, self.amt=11433465.4182, ukdf['pct'].iloc[-1]=0.000175 , ukdf['amount'].iloc[-1]=11433465.4182, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5958, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '60.176', 'enterprice': '16529.3', 'countrevence': '0', 'unrealprofit': '-309719.8544', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '21676.2', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1


## /root/FIL/strategy/factorcheck/log.txt ----- -----

1637  20230211   162500    162959  1676104199  ...  21672.4 -0.000341   1637    5

[5 rows x 11 columns]
2023-02-11 16:30:00,606:INFO:factorcheck2:main.py:128:handleKline:185239: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': True, 'isOpenSell': False, 'isCloseBuy': False, 'isCloseSell': False, 'isOpen': True, 'isClose': False, 'isTrig': True}
2023-02-11 16:30:00,651:INFO:factorcheck2:main.py:145:handleKline:185239: df_panel.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec  ...       pct  index  idx    factor
229  20230211   142500    142959  1676096999  ... -0.000018   1613    5  0.731691
230  20230211   145500    145959  1676098799  ...  0.000236   1619    5  0.728106
231  20230211   152500    152959  1676100599  ...  0.000721   1625    5  0.724525
232  20230211   155500    155959  1676102399  ... -0.001055   1631    5  0.719384
233  20230211   162500    162959  1676104199  ... -0.000341   1637    5  0.715061

[5 rows x 12 columns]
2023-02-11 16:30:00,690:INFO:factorcheck2:main.py:201:insertFactor:185239: curDateTime:2111630, name:factorcheck2, symbol:BTCUSDT, tradeDate:20230211, closeTime:162959, close:21672.4, total:909224.3076578999, factor:0.7150612107543067, factorCnt:0, side:buy 

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=0, self.factor=0.7150612107543067, self.count=22485 

self.closeSec=1676104499, self.tradeDate='20230211', self.openTime='163000', self.closeTime='163459', self.symbol='BTCUSDT', self.open=21672.4, self.close=21676.2, self.high=21678.8, self.low=21670.0 
2023-02-11 16:35:00,419:INFO:factorcheck2:main.py:126:handleKline:185239: self.closeSec=1676104499, self.tradeDate='20230211', self.openTime='163000', self.closeTime='163459',self.symbol='BTCUSDT',self.open=21672.4, self.close=21676.2, self.high=21678.8, self.low=21670.0   
127.0.0.1 - - [11/Feb/2023 16:35:00] "POST / HTTP/1.1" 200 -
2023-02-11 16:35:00,507:INFO:factorcheck2:main.py:127:handleKline:185239: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime    closeSec  ...      low       pct  index  idx
1634  20230211   161000    161459  1676103299  ...  21682.0  0.000475   1634    2
1635  20230211   161500    161959  1676103599  ...  21685.5 -0.000318   1635    3
1636  20230211   162000    162459  1676103899  ...  21677.3 -0.000263   1636    4
1637  20230211   162500    162959  1676104199  ...  21672.4 -0.000341   1637    5
1638  20230211   163000    163459  1676104499  ...  21670.0  0.000175   1638    0

[5 rows x 11 columns]
2023-02-11 16:35:00,508:INFO:factorcheck2:main.py:128:handleKline:185239: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': True, 'isOpenSell': False, 'isCloseBuy': False, 'isCloseSell': False, 'isOpen': True, 'isClose': False, 'isTrig': True}


## /root/FIL/strategy/logic/log.txt ----- -----

2023-02-11 16:30:30,352:DEBUG:logic:main.py:463:getModel:885513: df_s.iloc[-5:,:] :
          date closeTime     open  ...    alpha58   alpha67   alpha72
5787  20230211    135959  21683.2  ...  45.833333  0.414945  0.572265
5788  20230211    142959  21663.3  ...  45.416667  0.414223  0.566242
5789  20230211    145959  21660.2  ...  45.416667  0.413812  0.560877
5790  20230211    152959  21658.0  ...  45.416667  0.414186  0.555707
5791  20230211    155959  21659.2  ...  45.416667  0.421323  0.547807

[5 rows x 33 columns]
0.507380073800738
acc is : 0.507380073800738
2023-02-11 16:30:30,491:INFO:logic:main.py:468:getModel:885513: df_pred.iloc[-5:,:] :
     pred    prob_0    prob_1  actual  ...       nav  sign  cost_        bm
537     1  0.489008  0.510992       0  ...  1.025012  -1.0    0.0  0.950496
538     1  0.493262  0.506738       0  ...  1.025102  -1.0    0.0  0.950412
539     1  0.495734  0.504266       1  ...  1.025045  -1.0    0.0  0.950465
540     1  0.494875  0.505125       1  ...  1.023971  -1.0    0.0  0.951461
541     0  0.501967  0.498033       0  ...  1.024419  -1.0    0.0  0.951044

[5 rows x 10 columns]
2023-02-11 16:30:30,528:INFO:logic:main.py:478:getModel:885513: df_panel.iloc[-5:,:] :
    pred    prob_0    prob_1  actual  ...       nav  sign  cost_        bm
45     1  0.489070  0.510930       0  ...  1.025012  -1.0    0.0  0.950830
46     1  0.492696  0.507304       0  ...  1.025102  -1.0    0.0  0.949084
47     1  0.495737  0.504263       1  ...  1.025045  -1.0    0.0  0.950928
48     1  0.494376  0.505624       1  ...  1.023971  -1.0    0.0  0.949915
49     0  0.501967  0.498033       0  ...  1.024419  -1.0    0.0  0.951044

[5 rows x 10 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '32.252', 'enterprice': '22924.6', 'countrevence': '0', 'unrealprofit': '40260.1716', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '21676.3', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}


## /root/FIL/strategy/modifiedmom/log.txt ----- -----

528  20230211   160000    160959  1676102999  21681.9  21682.1  0.000009
2023-02-11 16:10:01,642:INFO:modifiedmom:main.py:146:handleKline:185213: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': True, 'isOpenSell': False, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True}

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=11241 

self.closeSec=1676103599, self.tradeDate='20230211', self.openTime='161000', self.closeTime='161959', self.symbol='BTCUSDT', self.open='21682.1', self.close='21685.5'
2023-02-11 16:20:00,526:INFO:modifiedmom:main.py:144:handleKline:185213: self.closeSec=1676103599, self.tradeDate='20230211', self.openTime='161000', self.closeTime='161959',self.symbol='BTCUSDT',self.open='21682.1', self.close='21685.5'
127.0.0.1 - - [11/Feb/2023 16:20:00] "POST / HTTP/1.1" 200 -
2023-02-11 16:20:00,553:INFO:modifiedmom:main.py:145:handleKline:185213: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec     open    close       pct
525  20230211   153000    153959  1676101199  21659.2  21653.8 -0.000249
526  20230211   154000    154959  1676101799  21653.9  21690.8  0.001709
527  20230211   155000    155959  1676102399    21691  21681.9 -0.000410
528  20230211   160000    160959  1676102999  21681.9  21682.1  0.000009
529  20230211   161000    161959  1676103599  21682.1  21685.5  0.000157
2023-02-11 16:20:00,553:INFO:modifiedmom:main.py:146:handleKline:185213: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': True, 'isOpenSell': False, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True}

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=11242 

self.closeSec=1676104199, self.tradeDate='20230211', self.openTime='162000', self.closeTime='162959', self.symbol='BTCUSDT', self.open='21685.5', self.close='21672.4'
2023-02-11 16:30:00,799:INFO:modifiedmom:main.py:144:handleKline:185213: self.closeSec=1676104199, self.tradeDate='20230211', self.openTime='162000', self.closeTime='162959',self.symbol='BTCUSDT',self.open='21685.5', self.close='21672.4'
127.0.0.1 - - [11/Feb/2023 16:30:00] "POST / HTTP/1.1" 200 -
2023-02-11 16:30:00,838:INFO:modifiedmom:main.py:145:handleKline:185213: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec     open    close       pct
526  20230211   154000    154959  1676101799  21653.9  21690.8  0.001709
527  20230211   155000    155959  1676102399    21691  21681.9 -0.000410
528  20230211   160000    160959  1676102999  21681.9  21682.1  0.000009
529  20230211   161000    161959  1676103599  21682.1  21685.5  0.000157
530  20230211   162000    162959  1676104199  21685.5  21672.4 -0.000604
2023-02-11 16:30:00,838:INFO:modifiedmom:main.py:146:handleKline:185213: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': True, 'isOpenSell': False, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True}


## /root/FIL/strategy/pyemd/log.txt ----- -----

17520  20230211   160000    160959  1676102999  21681.9  21682.1
2023-02-11 16:10:01,629:INFO:pyemd2:main.py:127:handleKline:185189: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=11242 

self.closeSec=1676103599, self.tradeDate='20230211', self.openTime='161000', self.closeTime='161959', self.symbol='BTCUSDT', self.open='21682.1', self.close='21685.5'
2023-02-11 16:20:00,570:INFO:pyemd2:main.py:125:handleKline:185189: self.closeSec=1676103599, self.tradeDate='20230211', self.openTime='161000', self.closeTime='161959',self.symbol='BTCUSDT',self.open='21682.1', self.close='21685.5'
127.0.0.1 - - [11/Feb/2023 16:20:00] "POST / HTTP/1.1" 200 -
2023-02-11 16:20:00,615:INFO:pyemd2:main.py:126:handleKline:185189: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
17517  20230211   153000    153959  1676101199  21659.2  21653.8
17518  20230211   154000    154959  1676101799  21653.9  21690.8
17519  20230211   155000    155959  1676102399    21691  21681.9
17520  20230211   160000    160959  1676102999  21681.9  21682.1
17521  20230211   161000    161959  1676103599  21682.1  21685.5
2023-02-11 16:20:00,615:INFO:pyemd2:main.py:127:handleKline:185189: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}
127.0.0.1 - - [11/Feb/2023 16:30:00] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=11243 

self.closeSec=1676104199, self.tradeDate='20230211', self.openTime='162000', self.closeTime='162959', self.symbol='BTCUSDT', self.open='21685.5', self.close='21672.4'
2023-02-11 16:30:00,787:INFO:pyemd2:main.py:125:handleKline:185189: self.closeSec=1676104199, self.tradeDate='20230211', self.openTime='162000', self.closeTime='162959',self.symbol='BTCUSDT',self.open='21685.5', self.close='21672.4'
2023-02-11 16:30:00,842:INFO:pyemd2:main.py:126:handleKline:185189: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
17518  20230211   154000    154959  1676101799  21653.9  21690.8
17519  20230211   155000    155959  1676102399    21691  21681.9
17520  20230211   160000    160959  1676102999  21681.9  21682.1
17521  20230211   161000    161959  1676103599  21682.1  21685.5
17522  20230211   162000    162959  1676104199  21685.5  21672.4
2023-02-11 16:30:00,842:INFO:pyemd2:main.py:127:handleKline:185189: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}


## /root/FIL/strategy/similarity/log.txt ----- -----

12192  20230211   160000    160959  1676102999  21681.9  21682.1
2023-02-11 16:10:01,649:INFO:testStrategy:main.py:103:handleKline:185174: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': True, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True, 'isCorr': False}

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=11242 

self.closeSec=1676103599, self.tradeDate='20230211', self.openTime='161000', self.closeTime='161959', self.symbol='BTCUSDT', self.open='21682.1', self.close='21685.5'
2023-02-11 16:20:00,528:INFO:testStrategy:main.py:101:handleKline:185174: self.closeSec=1676103599, self.tradeDate='20230211', self.openTime='161000', self.closeTime='161959',self.symbol='BTCUSDT',self.open='21682.1', self.close='21685.5'
127.0.0.1 - - [11/Feb/2023 16:20:00] "POST / HTTP/1.1" 200 -
2023-02-11 16:20:00,574:INFO:testStrategy:main.py:102:handleKline:185174: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
12189  20230211   153000    153959  1676101199  21659.2  21653.8
12190  20230211   154000    154959  1676101799  21653.9  21690.8
12191  20230211   155000    155959  1676102399    21691  21681.9
12192  20230211   160000    160959  1676102999  21681.9  21682.1
12193  20230211   161000    161959  1676103599  21682.1  21685.5
2023-02-11 16:20:00,574:INFO:testStrategy:main.py:103:handleKline:185174: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': True, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True, 'isCorr': False}

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=11243 

self.closeSec=1676104199, self.tradeDate='20230211', self.openTime='162000', self.closeTime='162959', self.symbol='BTCUSDT', self.open='21685.5', self.close='21672.4'
2023-02-11 16:30:00,768:INFO:testStrategy:main.py:101:handleKline:185174: self.closeSec=1676104199, self.tradeDate='20230211', self.openTime='162000', self.closeTime='162959',self.symbol='BTCUSDT',self.open='21685.5', self.close='21672.4'
127.0.0.1 - - [11/Feb/2023 16:30:00] "POST / HTTP/1.1" 200 -
2023-02-11 16:30:00,778:INFO:testStrategy:main.py:102:handleKline:185174: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
12190  20230211   154000    154959  1676101799  21653.9  21690.8
12191  20230211   155000    155959  1676102399    21691  21681.9
12192  20230211   160000    160959  1676102999  21681.9  21682.1
12193  20230211   161000    161959  1676103599  21682.1  21685.5
12194  20230211   162000    162959  1676104199  21685.5  21672.4
2023-02-11 16:30:00,778:INFO:testStrategy:main.py:103:handleKline:185174: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': True, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True, 'isCorr': False}


## /root/FIL/strategy/sr_min/log.txt ----- -----

127.0.0.1 - - [11/Feb/2023 16:30:00] "POST / HTTP/1.1" 200 -
--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=0, self.total=1000000.0, self.flagDict['side']='', self.tradeCount=0, self.count=17916
self.closeSec=1676104199, self.tradeDate='20230211', self.openTime='162500', self.closeTime='162959', self.symbol='BTCUSDT', self.open=21679.9, self.close=21672.4, self.high=21680.0, self.low=21672.4, self.vol=341.749, self.amt=7408036.3946 
2023-02-11 16:30:00,671:INFO:sr_min:main.py:172:handleKline:449472: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5953  20230211   160500    160959  ...         0.0        0.0       0
5954  20230211   161000    161459  ...         0.0        0.0       0
5955  20230211   161500    161959  ...         0.0        0.0       0
5956  20230211   162000    162459  ...         0.0        0.0       0
5957  20230211   162500    162959  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-02-11 16:30:00,671:INFO:sr_min:main.py:175:handleKline:449472: self.closeSec=1676104199, self.tradeDate='20230211', self.openTime='162500', self.closeTime='162959',self.symbol='BTCUSDT',self.open=21679.9, self.close=21672.4, self.high=21680.0, self.low=21672.4, self.vol=341.749, self.amt=7408036.3946, ukdf['pct'].iloc[-1]=-0.000341 , ukdf['amount'].iloc[-1]=7408036.3946, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5957, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': []}
type(curSign)=<class 'int'>, curSign=0, self.sign=0
--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=0, self.total=1000000.0, self.flagDict['side']='', self.tradeCount=0, self.count=17917
self.closeSec=1676104499, self.tradeDate='20230211', self.openTime='163000', self.closeTime='163459', self.symbol='BTCUSDT', self.open=21672.4, self.close=21676.2, self.high=21678.8, self.low=21670.0, self.vol=527.507, self.amt=11433465.4182 
127.0.0.1 - - [11/Feb/2023 16:35:00] "POST / HTTP/1.1" 200 -
2023-02-11 16:35:00,483:INFO:sr_min:main.py:172:handleKline:449472: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5954  20230211   161000    161459  ...         0.0        0.0       0
5955  20230211   161500    161959  ...         0.0        0.0       0
5956  20230211   162000    162459  ...         0.0        0.0       0
5957  20230211   162500    162959  ...         0.0        0.0       0
5958  20230211   163000    163459  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-02-11 16:35:00,484:INFO:sr_min:main.py:175:handleKline:449472: self.closeSec=1676104499, self.tradeDate='20230211', self.openTime='163000', self.closeTime='163459',self.symbol='BTCUSDT',self.open=21672.4, self.close=21676.2, self.high=21678.8, self.low=21670.0, self.vol=527.507, self.amt=11433465.4182, ukdf['pct'].iloc[-1]=0.000175 , ukdf['amount'].iloc[-1]=11433465.4182, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5958, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': []}
type(curSign)=<class 'int'>, curSign=0, self.sign=0


## /root/FIL/strategy/s_rsrs/log.txt ----- -----

721  20230211   040000    075959  1676073599  ...    721  0.751064  1.182652     1.0
722  20230211   080000    115959  1676087999  ...    722  0.785671  1.324595     1.0

[5 rows x 15 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '42.94', 'enterprice': '21730.2', 'countrevence': '0', 'unrealprofit': '-2584.988', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '21670', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'numpy.int64'>, curSign=1, self.sign=1
127.0.0.1 - - [11/Feb/2023 16:00:01] "POST / HTTP/1.1" 200 -
--handleKline--:  version='2.0.0', self.name='s_rsrs', self.symbol='BTCUSDT', interval='4h', intervalSec=14400, wid=25, thd=0.6, self.sign=1, self.total=932161.693212, self.flagDict['side']='buy', self.tradeCount=18, self.count=468
self.closeSec=1676102399, self.tradeDate='20230211', self.openTime='120000', self.closeTime='155959', self.symbol='BTCUSDT', self.open=21668.8, self.close=21681.9, self.high=21704.9, self.low=21630.6, self.vol=17658.503, self.amt=382614573.8557 
2023-02-11 16:00:01,433:INFO:s_rsrs:main.py:141:handleKline:185271: self.closeSec=1676102399, self.tradeDate='20230211', self.openTime='120000', self.closeTime='155959',self.symbol='BTCUSDT',self.open=21668.8, self.close=21681.9, self.high=21704.9, self.low=21630.6, self.vol=17658.503, self.amt=382614573.8557 
2023-02-11 16:00:01,488:INFO:s_rsrs:main.py:142:handleKline:185271: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime  ...         vol           amt       pct
719  20230210   200000    235959  ...  120581.027  2.621305e+09 -0.003572
720  20230211   000000    035959  ...   86728.383  1.878822e+09  0.005275
721  20230211   040000    075959  ...   69883.004  1.508450e+09 -0.006644
722  20230211   080000    115959  ...   34548.958  7.481311e+08  0.002322
723  20230211   120000    155959  ...   17658.503  3.826146e+08  0.000605

[5 rows x 11 columns]
2023-02-11 16:00:03,311:INFO:s_rsrs:main.py:151:handleKline:185271: df_s.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec  ...  index      beta    zscore  signal
719  20230210   200000    235959  1676044799  ...    719  0.696660  0.969925     1.0
720  20230211   000000    035959  1676059199  ...    720  0.736998  1.139375     1.0
721  20230211   040000    075959  1676073599  ...    721  0.751064  1.182652     1.0
722  20230211   080000    115959  1676087999  ...    722  0.785671  1.324595     1.0
723  20230211   120000    155959  1676102399  ...    723  0.829825  1.509562     1.0

[5 rows x 15 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '42.94', 'enterprice': '21730.2', 'countrevence': '0', 'unrealprofit': '-2072.6283979222', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '21681.93198887', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'numpy.int64'>, curSign=1, self.sign=1


