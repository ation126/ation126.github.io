# 20230209 16:36:03

## /root/FIL/strategy/amihud/log.txt ----- -----

--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=993672.4896432, self.flagDict['side']='sell', self.tradeCount=2, self.count=21342
self.closeSec=1675931399, self.tradeDate='20230209', self.openTime='162500', self.closeTime='162959', self.symbol='BTCUSDT', self.open=22735.6, self.close=22737.1, self.high=22766.0, self.low=22727.1, self.vol=2948.911, self.amt=67064689.3004 
127.0.0.1 - - [09/Feb/2023 16:30:00] "POST / HTTP/1.1" 200 -
2023-02-09 16:30:00,605:INFO:amihud:main.py:172:handleKline:200676: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5953  20230209   160500    160959  ...         0.0        0.0       0
5954  20230209   161000    161459  ...         0.0        0.0       0
5955  20230209   161500    161959  ...         0.0        0.0       0
5956  20230209   162000    162459  ...         0.0        0.0       0
5957  20230209   162500    162959  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-02-09 16:30:00,605:INFO:amihud:main.py:175:handleKline:200676: self.closeSec=1675931399, self.tradeDate='20230209', self.openTime='162500', self.closeTime='162959',self.symbol='BTCUSDT',self.open=22735.6, self.close=22737.1, self.high=22766.0, self.low=22727.1, self.vol=2948.911, self.amt=67064689.3004, ukdf['pct'].iloc[-1]=6.6e-05 , ukdf['amount'].iloc[-1]=67064689.3004, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5957, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '60.176', 'enterprice': '16529.3', 'countrevence': '0', 'unrealprofit': '-373557.47841348048', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '22737.04857773', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1
127.0.0.1 - - [09/Feb/2023 16:35:00] "POST / HTTP/1.1" 200 -
--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=993672.4896432, self.flagDict['side']='sell', self.tradeCount=2, self.count=21343
self.closeSec=1675931699, self.tradeDate='20230209', self.openTime='163000', self.closeTime='163459', self.symbol='BTCUSDT', self.open=22735.4, self.close=22704.8, self.high=22742.1, self.low=22692.4, self.vol=1645.926, self.amt=37385418.5501 
2023-02-09 16:35:00,511:INFO:amihud:main.py:172:handleKline:200676: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5954  20230209   161000    161459  ...         0.0        0.0       0
5955  20230209   161500    161959  ...         0.0        0.0       0
5956  20230209   162000    162459  ...         0.0        0.0       0
5957  20230209   162500    162959  ...         0.0        0.0       0
5958  20230209   163000    163459  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-02-09 16:35:00,511:INFO:amihud:main.py:175:handleKline:200676: self.closeSec=1675931699, self.tradeDate='20230209', self.openTime='163000', self.closeTime='163459',self.symbol='BTCUSDT',self.open=22735.4, self.close=22704.8, self.high=22742.1, self.low=22692.4, self.vol=1645.926, self.amt=37385418.5501, ukdf['pct'].iloc[-1]=-0.001421 , ukdf['amount'].iloc[-1]=37385418.5501, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5958, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '60.176', 'enterprice': '16529.3', 'countrevence': '0', 'unrealprofit': '-371633.11064263984', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '22705.06958659', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1


## /root/FIL/strategy/factorcheck/log.txt ----- -----

1636  20230209   162000    162459  1675931099  ...  22701.1  0.000973   1636    4
1637  20230209   162500    162959  1675931399  ...  22727.1  0.000066   1637    5

[5 rows x 11 columns]
2023-02-09 16:30:00,643:INFO:factorcheck2:main.py:128:handleKline:185239: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}
2023-02-09 16:30:00,716:INFO:factorcheck2:main.py:145:handleKline:185239: df_panel.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec  ...       pct  index  idx    factor
229  20230209   142500    142959  1675924199  ... -0.000544   1613    5  0.534898
230  20230209   145500    145959  1675925999  ...  0.000269   1619    5  0.538114
231  20230209   152500    152959  1675927799  ... -0.000534   1625    5  0.543648
232  20230209   155500    155959  1675929599  ...  0.000706   1631    5  0.548145
233  20230209   162500    162959  1675931399  ...  0.000066   1637    5  0.549399

[5 rows x 12 columns]

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=79, self.factor=0.5493987013604638, self.count=21909 

self.closeSec=1675931699, self.tradeDate='20230209', self.openTime='163000', self.closeTime='163459', self.symbol='BTCUSDT', self.open=22735.4, self.close=22704.8, self.high=22742.1, self.low=22692.4 
2023-02-09 16:35:00,426:INFO:factorcheck2:main.py:126:handleKline:185239: self.closeSec=1675931699, self.tradeDate='20230209', self.openTime='163000', self.closeTime='163459',self.symbol='BTCUSDT',self.open=22735.4, self.close=22704.8, self.high=22742.1, self.low=22692.4   
127.0.0.1 - - [09/Feb/2023 16:35:00] "POST / HTTP/1.1" 200 -
2023-02-09 16:35:00,455:INFO:factorcheck2:main.py:127:handleKline:185239: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime    closeSec  ...      low       pct  index  idx
1634  20230209   161000    161459  1675930499  ...  22667.1  0.000071   1634    2
1635  20230209   161500    161959  1675930799  ...  22673.8  0.001751   1635    3
1636  20230209   162000    162459  1675931099  ...  22701.1  0.000973   1636    4
1637  20230209   162500    162959  1675931399  ...  22727.1  0.000066   1637    5
1638  20230209   163000    163459  1675931699  ...  22692.4 -0.001421   1638    0

[5 rows x 11 columns]
2023-02-09 16:35:00,455:INFO:factorcheck2:main.py:128:handleKline:185239: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}


## /root/FIL/strategy/logic/log.txt ----- -----

2023-02-09 16:30:32,924:DEBUG:logic:main.py:463:getModel:885513: df_s.iloc[-5:,:] :
          date closeTime     open  ...    alpha58   alpha67   alpha72
5787  20230209    135959  22571.2  ...  47.500000  0.411511  0.646793
5788  20230209    142959  22595.5  ...  47.083333  0.409697  0.651236
5789  20230209    145959  22585.6  ...  47.083333  0.442926  0.645639
5790  20230209    152959  22710.4  ...  47.083333  0.429762  0.645611
5791  20230209    155959  22643.8  ...  47.500000  0.436165  0.643639

[5 rows x 33 columns]
0.5
acc is : 0.5
2023-02-09 16:30:33,090:INFO:logic:main.py:468:getModel:885513: df_pred.iloc[-5:,:] :
     pred    prob_0    prob_1  actual  ...       nav  sign  cost_        bm
537     0  0.500230  0.499770       0  ...  1.005296  -1.0    0.0  0.965469
538     1  0.494790  0.505210       1  ...  0.999745  -1.0    0.0  0.970799
539     0  0.530223  0.469777       0  ...  1.002673  -1.0    0.0  0.967957
540     1  0.488367  0.511633       1  ...  1.001570  -1.0    0.0  0.969021
541     0  0.504504  0.495496       1  ...  0.998548  -1.0    0.0  0.971945

[5 rows x 10 columns]
2023-02-09 16:30:33,109:INFO:logic:main.py:478:getModel:885513: df_panel.iloc[-5:,:] :
    pred    prob_0    prob_1  actual  ...       nav  sign  cost_        bm
45     0  0.501748  0.498252       0  ...  0.983811  -1.0    0.0  0.982196
46     1  0.495511  0.504489       1  ...  0.999745  -1.0    0.0  0.986722
47     0  0.531735  0.468265       0  ...  0.981244  -1.0    0.0  0.984886
48     1  0.489082  0.510918       1  ...  1.001570  -1.0    0.0  0.981112
49     0  0.504504  0.495496       1  ...  0.998548  -1.0    0.0  0.971945

[5 rows x 10 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '32.252', 'enterprice': '22924.6', 'countrevence': '0', 'unrealprofit': '6514.32692334952', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '22722.61789274', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}


## /root/FIL/strategy/modifiedmom/log.txt ----- -----

528  20230209   160000    160959  1675930199  22668.8  22672.2  0.000154
2023-02-09 16:10:01,567:INFO:modifiedmom:main.py:146:handleKline:185213: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': True, 'isOpenSell': False, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True}

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=10953 

self.closeSec=1675930799, self.tradeDate='20230209', self.openTime='161000', self.closeTime='161959', self.symbol='BTCUSDT', self.open='22672.2', self.close='22713.5'
2023-02-09 16:20:00,545:INFO:modifiedmom:main.py:144:handleKline:185213: self.closeSec=1675930799, self.tradeDate='20230209', self.openTime='161000', self.closeTime='161959',self.symbol='BTCUSDT',self.open='22672.2', self.close='22713.5'
127.0.0.1 - - [09/Feb/2023 16:20:00] "POST / HTTP/1.1" 200 -
2023-02-09 16:20:00,562:INFO:modifiedmom:main.py:145:handleKline:185213: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec     open    close       pct
525  20230209   153000    153959  1675928399  22643.8  22669.6  0.001139
526  20230209   154000    154959  1675928999  22669.6  22659.9 -0.000428
527  20230209   155000    155959  1675929599  22659.9  22668.7  0.000388
528  20230209   160000    160959  1675930199  22668.8  22672.2  0.000154
529  20230209   161000    161959  1675930799  22672.2  22713.5  0.001822
2023-02-09 16:20:00,562:INFO:modifiedmom:main.py:146:handleKline:185213: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': True, 'isOpenSell': False, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True}
127.0.0.1 - - [09/Feb/2023 16:30:00] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=10954 

self.closeSec=1675931399, self.tradeDate='20230209', self.openTime='162000', self.closeTime='162959', self.symbol='BTCUSDT', self.open='22713.6', self.close='22737.1'
2023-02-09 16:30:00,754:INFO:modifiedmom:main.py:144:handleKline:185213: self.closeSec=1675931399, self.tradeDate='20230209', self.openTime='162000', self.closeTime='162959',self.symbol='BTCUSDT',self.open='22713.6', self.close='22737.1'
2023-02-09 16:30:00,773:INFO:modifiedmom:main.py:145:handleKline:185213: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec     open    close       pct
526  20230209   154000    154959  1675928999  22669.6  22659.9 -0.000428
527  20230209   155000    155959  1675929599  22659.9  22668.7  0.000388
528  20230209   160000    160959  1675930199  22668.8  22672.2  0.000154
529  20230209   161000    161959  1675930799  22672.2  22713.5  0.001822
530  20230209   162000    162959  1675931399  22713.6  22737.1  0.001039
2023-02-09 16:30:00,773:INFO:modifiedmom:main.py:146:handleKline:185213: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': True, 'isOpenSell': False, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True}


## /root/FIL/strategy/pyemd/log.txt ----- -----

17520  20230209   160000    160959  1675930199  22668.8  22672.2
2023-02-09 16:10:01,554:INFO:pyemd2:main.py:127:handleKline:185189: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}
127.0.0.1 - - [09/Feb/2023 16:20:00] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=10954 

self.closeSec=1675930799, self.tradeDate='20230209', self.openTime='161000', self.closeTime='161959', self.symbol='BTCUSDT', self.open='22672.2', self.close='22713.5'
2023-02-09 16:20:00,541:INFO:pyemd2:main.py:125:handleKline:185189: self.closeSec=1675930799, self.tradeDate='20230209', self.openTime='161000', self.closeTime='161959',self.symbol='BTCUSDT',self.open='22672.2', self.close='22713.5'
2023-02-09 16:20:00,588:INFO:pyemd2:main.py:126:handleKline:185189: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
17517  20230209   153000    153959  1675928399  22643.8  22669.6
17518  20230209   154000    154959  1675928999  22669.6  22659.9
17519  20230209   155000    155959  1675929599  22659.9  22668.7
17520  20230209   160000    160959  1675930199  22668.8  22672.2
17521  20230209   161000    161959  1675930799  22672.2  22713.5
2023-02-09 16:20:00,589:INFO:pyemd2:main.py:127:handleKline:185189: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=10955 

self.closeSec=1675931399, self.tradeDate='20230209', self.openTime='162000', self.closeTime='162959', self.symbol='BTCUSDT', self.open='22713.6', self.close='22737.1'
2023-02-09 16:30:00,776:INFO:pyemd2:main.py:125:handleKline:185189: self.closeSec=1675931399, self.tradeDate='20230209', self.openTime='162000', self.closeTime='162959',self.symbol='BTCUSDT',self.open='22713.6', self.close='22737.1'
127.0.0.1 - - [09/Feb/2023 16:30:00] "POST / HTTP/1.1" 200 -
2023-02-09 16:30:00,801:INFO:pyemd2:main.py:126:handleKline:185189: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
17518  20230209   154000    154959  1675928999  22669.6  22659.9
17519  20230209   155000    155959  1675929599  22659.9  22668.7
17520  20230209   160000    160959  1675930199  22668.8  22672.2
17521  20230209   161000    161959  1675930799  22672.2  22713.5
17522  20230209   162000    162959  1675931399  22713.6  22737.1
2023-02-09 16:30:00,801:INFO:pyemd2:main.py:127:handleKline:185189: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}


## /root/FIL/strategy/similarity/log.txt ----- -----

12192  20230209   160000    160959  1675930199  22668.8  22672.2
2023-02-09 16:10:01,615:INFO:testStrategy:main.py:103:handleKline:185174: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': True, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True, 'isCorr': False}
127.0.0.1 - - [09/Feb/2023 16:20:00] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=10954 

self.closeSec=1675930799, self.tradeDate='20230209', self.openTime='161000', self.closeTime='161959', self.symbol='BTCUSDT', self.open='22672.2', self.close='22713.5'
2023-02-09 16:20:00,512:INFO:testStrategy:main.py:101:handleKline:185174: self.closeSec=1675930799, self.tradeDate='20230209', self.openTime='161000', self.closeTime='161959',self.symbol='BTCUSDT',self.open='22672.2', self.close='22713.5'
2023-02-09 16:20:00,589:INFO:testStrategy:main.py:102:handleKline:185174: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
12189  20230209   153000    153959  1675928399  22643.8  22669.6
12190  20230209   154000    154959  1675928999  22669.6  22659.9
12191  20230209   155000    155959  1675929599  22659.9  22668.7
12192  20230209   160000    160959  1675930199  22668.8  22672.2
12193  20230209   161000    161959  1675930799  22672.2  22713.5
2023-02-09 16:20:00,589:INFO:testStrategy:main.py:103:handleKline:185174: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': True, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True, 'isCorr': False}

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=10955 

self.closeSec=1675931399, self.tradeDate='20230209', self.openTime='162000', self.closeTime='162959', self.symbol='BTCUSDT', self.open='22713.6', self.close='22737.1'
2023-02-09 16:30:00,759:INFO:testStrategy:main.py:101:handleKline:185174: self.closeSec=1675931399, self.tradeDate='20230209', self.openTime='162000', self.closeTime='162959',self.symbol='BTCUSDT',self.open='22713.6', self.close='22737.1'
127.0.0.1 - - [09/Feb/2023 16:30:00] "POST / HTTP/1.1" 200 -
2023-02-09 16:30:00,785:INFO:testStrategy:main.py:102:handleKline:185174: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
12190  20230209   154000    154959  1675928999  22669.6  22659.9
12191  20230209   155000    155959  1675929599  22659.9  22668.7
12192  20230209   160000    160959  1675930199  22668.8  22672.2
12193  20230209   161000    161959  1675930799  22672.2  22713.5
12194  20230209   162000    162959  1675931399  22713.6  22737.1
2023-02-09 16:30:00,785:INFO:testStrategy:main.py:103:handleKline:185174: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': True, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True, 'isCorr': False}


## /root/FIL/strategy/sr_min/log.txt ----- -----

127.0.0.1 - - [09/Feb/2023 16:30:00] "POST / HTTP/1.1" 200 -
--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=0, self.total=1000000.0, self.flagDict['side']='', self.tradeCount=0, self.count=17340
self.closeSec=1675931399, self.tradeDate='20230209', self.openTime='162500', self.closeTime='162959', self.symbol='BTCUSDT', self.open=22735.6, self.close=22737.1, self.high=22766.0, self.low=22727.1, self.vol=2948.911, self.amt=67064689.3004 
2023-02-09 16:30:00,691:INFO:sr_min:main.py:172:handleKline:449472: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5953  20230209   160500    160959  ...         0.0        0.0       0
5954  20230209   161000    161459  ...         0.0        0.0       0
5955  20230209   161500    161959  ...         0.0        0.0       0
5956  20230209   162000    162459  ...         0.0        0.0       0
5957  20230209   162500    162959  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-02-09 16:30:00,696:INFO:sr_min:main.py:175:handleKline:449472: self.closeSec=1675931399, self.tradeDate='20230209', self.openTime='162500', self.closeTime='162959',self.symbol='BTCUSDT',self.open=22735.6, self.close=22737.1, self.high=22766.0, self.low=22727.1, self.vol=2948.911, self.amt=67064689.3004, ukdf['pct'].iloc[-1]=6.6e-05 , ukdf['amount'].iloc[-1]=67064689.3004, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5957, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': []}
type(curSign)=<class 'int'>, curSign=0, self.sign=0
--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=0, self.total=1000000.0, self.flagDict['side']='', self.tradeCount=0, self.count=17341
self.closeSec=1675931699, self.tradeDate='20230209', self.openTime='163000', self.closeTime='163459', self.symbol='BTCUSDT', self.open=22735.4, self.close=22704.8, self.high=22742.1, self.low=22692.4, self.vol=1645.926, self.amt=37385418.5501 
127.0.0.1 - - [09/Feb/2023 16:35:00] "POST / HTTP/1.1" 200 -
2023-02-09 16:35:00,470:INFO:sr_min:main.py:172:handleKline:449472: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5954  20230209   161000    161459  ...         0.0        0.0       0
5955  20230209   161500    161959  ...         0.0        0.0       0
5956  20230209   162000    162459  ...         0.0        0.0       0
5957  20230209   162500    162959  ...         0.0        0.0       0
5958  20230209   163000    163459  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-02-09 16:35:00,472:INFO:sr_min:main.py:175:handleKline:449472: self.closeSec=1675931699, self.tradeDate='20230209', self.openTime='163000', self.closeTime='163459',self.symbol='BTCUSDT',self.open=22735.4, self.close=22704.8, self.high=22742.1, self.low=22692.4, self.vol=1645.926, self.amt=37385418.5501, ukdf['pct'].iloc[-1]=-0.001421 , ukdf['amount'].iloc[-1]=37385418.5501, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5958, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': []}
type(curSign)=<class 'int'>, curSign=0, self.sign=0


## /root/FIL/strategy/s_rsrs/log.txt ----- -----

721  20230209   040000    075959  1675900799  ...    721  0.326246 -0.642327    -1.0
722  20230209   080000    115959  1675915199  ...    722  0.234313 -1.064918    -1.0

[5 rows x 15 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '38.925', 'enterprice': '22855.7', 'countrevence': '0', 'unrealprofit': '13405.77', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '22511.3', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'numpy.int64'>, curSign=-1, self.sign=-1
--handleKline--:  version='2.0.0', self.name='s_rsrs', self.symbol='BTCUSDT', interval='4h', intervalSec=14400, wid=25, thd=0.6, self.sign=-1, self.total=888768.4643774999, self.flagDict['side']='sell', self.tradeCount=17, self.count=456
self.closeSec=1675929599, self.tradeDate='20230209', self.openTime='120000', self.closeTime='155959', self.symbol='BTCUSDT', self.open=22511.6, self.close=22668.7, self.high=22731.8, self.low=22341.1, self.vol=83990.686, self.amt=1895750519.9733 
127.0.0.1 - - [09/Feb/2023 16:00:01] "POST / HTTP/1.1" 200 -
2023-02-09 16:00:01,135:INFO:s_rsrs:main.py:141:handleKline:185271: self.closeSec=1675929599, self.tradeDate='20230209', self.openTime='120000', self.closeTime='155959',self.symbol='BTCUSDT',self.open=22511.6, self.close=22668.7, self.high=22731.8, self.low=22341.1, self.vol=83990.686, self.amt=1895750519.9733 
2023-02-09 16:00:01,172:INFO:s_rsrs:main.py:142:handleKline:185271: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime  ...         vol           amt       pct
719  20230208   200000    235959  ...  103068.788  2.372762e+09 -0.012547
720  20230209   000000    035959  ...  131915.737  3.015449e+09  0.000219
721  20230209   040000    075959  ...   42038.652  9.621964e+08  0.003879
722  20230209   080000    115959  ...  114797.338  2.601294e+09 -0.019359
723  20230209   120000    155959  ...   83990.686  1.895751e+09  0.006979

[5 rows x 11 columns]
2023-02-09 16:00:03,133:INFO:s_rsrs:main.py:151:handleKline:185271: df_s.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec  ...  index      beta    zscore  signal
719  20230208   200000    235959  1675871999  ...    719  0.380896 -0.375045     NaN
720  20230209   000000    035959  1675886399  ...    720  0.329676 -0.601531    -1.0
721  20230209   040000    075959  1675900799  ...    721  0.326246 -0.642327    -1.0
722  20230209   080000    115959  1675915199  ...    722  0.234313 -1.064918    -1.0
723  20230209   120000    155959  1675929599  ...    723  0.269893 -0.917045    -1.0

[5 rows x 15 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '38.925', 'enterprice': '22855.7', 'countrevence': '0', 'unrealprofit': '7278.975', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '22668.7', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'numpy.int64'>, curSign=-1, self.sign=-1


