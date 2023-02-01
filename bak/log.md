# 20230201 16:35:40

## /root/FIL/strategy/amihud/log.txt ----- -----

--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=993672.4896432, self.flagDict['side']='sell', self.tradeCount=2, self.count=19038
self.closeSec=1675240199, self.tradeDate='20230201', self.openTime='162500', self.closeTime='162959', self.symbol='BTCUSDT', self.open=22990.8, self.close=22962.2, self.high=23004.2, self.low=22933.8, self.vol=2974.897, self.amt=68325632.276 
127.0.0.1 - - [01/Feb/2023 16:30:00] "POST / HTTP/1.1" 200 -
2023-02-01 16:30:01,064:INFO:amihud:main.py:172:handleKline:200676: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5953  20230201   160500    160959  ...         0.0        0.0       0
5954  20230201   161000    161459  ...         0.0        0.0       0
5955  20230201   161500    161959  ...         0.0        0.0       0
5956  20230201   162000    162459  ...         0.0        0.0       0
5957  20230201   162500    162959  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-02-01 16:30:01,073:INFO:amihud:main.py:175:handleKline:200676: self.closeSec=1675240199, self.tradeDate='20230201', self.openTime='162500', self.closeTime='162959',self.symbol='BTCUSDT',self.open=22990.8, self.close=22962.2, self.high=23004.2, self.low=22933.8, self.vol=2974.897, self.amt=68325632.276, ukdf['pct'].iloc[-1]=-0.0013 , ukdf['amount'].iloc[-1]=68325632.276, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5957, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '60.176', 'enterprice': '16529.3', 'countrevence': '0', 'unrealprofit': '-387106.1904', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '22962.2', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1
127.0.0.1 - - [01/Feb/2023 16:35:00] "POST / HTTP/1.1" 200 -
--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=993672.4896432, self.flagDict['side']='sell', self.tradeCount=2, self.count=19039
self.closeSec=1675240499, self.tradeDate='20230201', self.openTime='163000', self.closeTime='163459', self.symbol='BTCUSDT', self.open=22962.3, self.close=22985.6, self.high=22992.8, self.low=22936.3, self.vol=2414.936, self.amt=55464313.6127 
2023-02-01 16:35:00,542:INFO:amihud:main.py:172:handleKline:200676: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5954  20230201   161000    161459  ...         0.0        0.0       0
5955  20230201   161500    161959  ...         0.0        0.0       0
5956  20230201   162000    162459  ...         0.0        0.0       0
5957  20230201   162500    162959  ...         0.0        0.0       0
5958  20230201   163000    163459  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-02-01 16:35:00,542:INFO:amihud:main.py:175:handleKline:200676: self.closeSec=1675240499, self.tradeDate='20230201', self.openTime='163000', self.closeTime='163459',self.symbol='BTCUSDT',self.open=22962.3, self.close=22985.6, self.high=22992.8, self.low=22936.3, self.vol=2414.936, self.amt=55464313.6127, ukdf['pct'].iloc[-1]=0.001019 , ukdf['amount'].iloc[-1]=55464313.6127, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5958, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '60.176', 'enterprice': '16529.3', 'countrevence': '0', 'unrealprofit': '-388514.3088', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '22985.6', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1


## /root/FIL/strategy/factorcheck/log.txt ----- -----

1636  20230201   162000    162459  1675239899  ...  22944.5 -0.001325   1636    4
1637  20230201   162500    162959  1675240199  ...  22933.8 -0.001300   1637    5

[5 rows x 11 columns]
2023-02-01 16:30:01,023:INFO:factorcheck2:main.py:128:handleKline:185239: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': True, 'isOpenSell': False, 'isCloseBuy': False, 'isCloseSell': False, 'isOpen': True, 'isClose': False, 'isTrig': True}
2023-02-01 16:30:01,109:INFO:factorcheck2:main.py:145:handleKline:185239: df_panel.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec  ...       pct  index  idx    factor
229  20230201   142500    142959  1675232999  ... -0.000177   1613    5  0.414339
230  20230201   145500    145959  1675234799  ... -0.000923   1619    5  0.414559
231  20230201   152500    152959  1675236599  ...  0.000862   1625    5  0.412820
232  20230201   155500    155959  1675238399  ... -0.000632   1631    5  0.414177
233  20230201   162500    162959  1675240199  ... -0.001300   1637    5  0.422922

[5 rows x 12 columns]
127.0.0.1 - - [01/Feb/2023 16:35:00] "POST / HTTP/1.1" 200 -

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=35, self.factor=0.42292242547413467, self.count=19605 

self.closeSec=1675240499, self.tradeDate='20230201', self.openTime='163000', self.closeTime='163459', self.symbol='BTCUSDT', self.open=22962.3, self.close=22985.6, self.high=22992.8, self.low=22936.3 
2023-02-01 16:35:00,431:INFO:factorcheck2:main.py:126:handleKline:185239: self.closeSec=1675240499, self.tradeDate='20230201', self.openTime='163000', self.closeTime='163459',self.symbol='BTCUSDT',self.open=22962.3, self.close=22985.6, self.high=22992.8, self.low=22936.3   
2023-02-01 16:35:00,496:INFO:factorcheck2:main.py:127:handleKline:185239: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime    closeSec  ...      low       pct  index  idx
1634  20230201   161000    161459  1675239299  ...  23045.0 -0.001252   1634    2
1635  20230201   161500    161959  1675239599  ...  23017.9 -0.001015   1635    3
1636  20230201   162000    162459  1675239899  ...  22944.5 -0.001325   1636    4
1637  20230201   162500    162959  1675240199  ...  22933.8 -0.001300   1637    5
1638  20230201   163000    163459  1675240499  ...  22936.3  0.001019   1638    0

[5 rows x 11 columns]
2023-02-01 16:35:00,496:INFO:factorcheck2:main.py:128:handleKline:185239: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': True, 'isOpenSell': False, 'isCloseBuy': False, 'isCloseSell': False, 'isOpen': True, 'isClose': False, 'isTrig': True}


## /root/FIL/strategy/logic/log.txt ----- -----

2023-02-01 16:30:31,821:DEBUG:logic:main.py:463:getModel:885513: df_s.iloc[-5:,:] :
          date closeTime     open  ...    alpha58   alpha67   alpha72
5787  20230201    135959  23155.3  ...  50.000000  0.506746  0.384196
5788  20230201    142959  23113.4  ...  49.583333  0.502801  0.388172
5789  20230201    145959  23097.2  ...  49.583333  0.494581  0.396527
5790  20230201    152959  23060.0  ...  50.000000  0.505519  0.398242
5791  20230201    155959  23107.9  ...  49.583333  0.497080  0.404519

[5 rows x 33 columns]
0.5424354243542435
acc is : 0.5424354243542435
2023-02-01 16:30:31,964:INFO:logic:main.py:468:getModel:885513: df_pred.iloc[-5:,:] :
     pred    prob_0    prob_1  actual  ...       nav  sign  cost_        bm
537     1  0.489532  0.510468       0  ...  0.973098   1.0    0.0  1.023228
538     1  0.487970  0.512030       0  ...  0.971573   1.0    0.0  1.021624
539     1  0.482217  0.517783       1  ...  0.973595   1.0    0.0  1.023751
540     1  0.499744  0.500256       0  ...  0.972040   1.0    0.0  1.022116
541     1  0.481697  0.518303       0  ...  0.967456   1.0    0.0  1.017296

[5 rows x 10 columns]
2023-02-01 16:30:31,995:INFO:logic:main.py:478:getModel:885513: df_panel.iloc[-5:,:] :
    pred    prob_0    prob_1  actual  ...       nav  sign  cost_        bm
45     1  0.489605  0.510395       0  ...  0.973098   1.0    0.0  1.019948
46     1  0.487292  0.512708       0  ...  0.914131   1.0    0.0  1.017450
47     1  0.481849  0.518151       1  ...  0.916034   1.0    0.0  1.022795
48     0  0.500495  0.499505       0  ...  0.972040   1.0    0.0  1.022130
49     1  0.481697  0.518303       0  ...  0.967456   1.0    0.0  1.017296

[5 rows x 10 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '30.955', 'enterprice': '23100.3', 'countrevence': '0', 'unrealprofit': '-4469.902', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '22955.9', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}


## /root/FIL/strategy/modifiedmom/log.txt ----- -----

528  20230201   160000    160959  1675238999  23070.9    23075  0.000173
2023-02-01 16:10:01,555:INFO:modifiedmom:main.py:146:handleKline:185213: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': True, 'isOpenSell': False, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True}
127.0.0.1 - - [01/Feb/2023 16:20:00] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=9801 

self.closeSec=1675239599, self.tradeDate='20230201', self.openTime='161000', self.closeTime='161959', self.symbol='BTCUSDT', self.open='23075', self.close='23022.6'
2023-02-01 16:20:00,562:INFO:modifiedmom:main.py:144:handleKline:185213: self.closeSec=1675239599, self.tradeDate='20230201', self.openTime='161000', self.closeTime='161959',self.symbol='BTCUSDT',self.open='23075', self.close='23022.6'
2023-02-01 16:20:00,591:INFO:modifiedmom:main.py:145:handleKline:185213: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec     open    close       pct
525  20230201   153000    153959  1675237199  23107.9  23081.9 -0.001125
526  20230201   154000    154959  1675237799  23081.8  23069.3 -0.000546
527  20230201   155000    155959  1675238399  23069.4    23071  0.000074
528  20230201   160000    160959  1675238999  23070.9    23075  0.000173
529  20230201   161000    161959  1675239599    23075  23022.6 -0.002271
2023-02-01 16:20:00,591:INFO:modifiedmom:main.py:146:handleKline:185213: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': True, 'isOpenSell': False, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True}
127.0.0.1 - - [01/Feb/2023 16:30:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=9802 

self.closeSec=1675240199, self.tradeDate='20230201', self.openTime='162000', self.closeTime='162959', self.symbol='BTCUSDT', self.open='23020.7', self.close='22962.2'
2023-02-01 16:30:01,191:INFO:modifiedmom:main.py:144:handleKline:185213: self.closeSec=1675240199, self.tradeDate='20230201', self.openTime='162000', self.closeTime='162959',self.symbol='BTCUSDT',self.open='23020.7', self.close='22962.2'
2023-02-01 16:30:01,240:INFO:modifiedmom:main.py:145:handleKline:185213: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec     open    close       pct
526  20230201   154000    154959  1675237799  23081.8  23069.3 -0.000546
527  20230201   155000    155959  1675238399  23069.4    23071  0.000074
528  20230201   160000    160959  1675238999  23070.9    23075  0.000173
529  20230201   161000    161959  1675239599    23075  23022.6 -0.002271
530  20230201   162000    162959  1675240199  23020.7  22962.2 -0.002624
2023-02-01 16:30:01,242:INFO:modifiedmom:main.py:146:handleKline:185213: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': True, 'isOpenSell': False, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True}


## /root/FIL/strategy/pyemd/log.txt ----- -----

17520  20230201   160000    160959  1675238999  23070.9    23075
2023-02-01 16:10:01,560:INFO:pyemd2:main.py:127:handleKline:185189: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}
127.0.0.1 - - [01/Feb/2023 16:20:00] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=9802 

self.closeSec=1675239599, self.tradeDate='20230201', self.openTime='161000', self.closeTime='161959', self.symbol='BTCUSDT', self.open='23075', self.close='23022.6'
2023-02-01 16:20:00,570:INFO:pyemd2:main.py:125:handleKline:185189: self.closeSec=1675239599, self.tradeDate='20230201', self.openTime='161000', self.closeTime='161959',self.symbol='BTCUSDT',self.open='23075', self.close='23022.6'
2023-02-01 16:20:00,595:INFO:pyemd2:main.py:126:handleKline:185189: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
17517  20230201   153000    153959  1675237199  23107.9  23081.9
17518  20230201   154000    154959  1675237799  23081.8  23069.3
17519  20230201   155000    155959  1675238399  23069.4    23071
17520  20230201   160000    160959  1675238999  23070.9    23075
17521  20230201   161000    161959  1675239599    23075  23022.6
2023-02-01 16:20:00,596:INFO:pyemd2:main.py:127:handleKline:185189: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}
127.0.0.1 - - [01/Feb/2023 16:30:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=9803 

self.closeSec=1675240199, self.tradeDate='20230201', self.openTime='162000', self.closeTime='162959', self.symbol='BTCUSDT', self.open='23020.7', self.close='22962.2'
2023-02-01 16:30:01,210:INFO:pyemd2:main.py:125:handleKline:185189: self.closeSec=1675240199, self.tradeDate='20230201', self.openTime='162000', self.closeTime='162959',self.symbol='BTCUSDT',self.open='23020.7', self.close='22962.2'
2023-02-01 16:30:01,251:INFO:pyemd2:main.py:126:handleKline:185189: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
17518  20230201   154000    154959  1675237799  23081.8  23069.3
17519  20230201   155000    155959  1675238399  23069.4    23071
17520  20230201   160000    160959  1675238999  23070.9    23075
17521  20230201   161000    161959  1675239599    23075  23022.6
17522  20230201   162000    162959  1675240199  23020.7  22962.2
2023-02-01 16:30:01,251:INFO:pyemd2:main.py:127:handleKline:185189: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}


## /root/FIL/strategy/similarity/log.txt ----- -----

12192  20230201   160000    160959  1675238999  23070.9    23075
2023-02-01 16:10:01,589:INFO:testStrategy:main.py:103:handleKline:185174: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': True, 'isOpenSell': False, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True, 'isCorr': False}
127.0.0.1 - - [01/Feb/2023 16:20:00] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=9802 

self.closeSec=1675239599, self.tradeDate='20230201', self.openTime='161000', self.closeTime='161959', self.symbol='BTCUSDT', self.open='23075', self.close='23022.6'
2023-02-01 16:20:00,536:INFO:testStrategy:main.py:101:handleKline:185174: self.closeSec=1675239599, self.tradeDate='20230201', self.openTime='161000', self.closeTime='161959',self.symbol='BTCUSDT',self.open='23075', self.close='23022.6'
2023-02-01 16:20:00,558:INFO:testStrategy:main.py:102:handleKline:185174: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
12189  20230201   153000    153959  1675237199  23107.9  23081.9
12190  20230201   154000    154959  1675237799  23081.8  23069.3
12191  20230201   155000    155959  1675238399  23069.4    23071
12192  20230201   160000    160959  1675238999  23070.9    23075
12193  20230201   161000    161959  1675239599    23075  23022.6
2023-02-01 16:20:00,559:INFO:testStrategy:main.py:103:handleKline:185174: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': True, 'isOpenSell': False, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True, 'isCorr': False}
127.0.0.1 - - [01/Feb/2023 16:30:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=9803 

self.closeSec=1675240199, self.tradeDate='20230201', self.openTime='162000', self.closeTime='162959', self.symbol='BTCUSDT', self.open='23020.7', self.close='22962.2'
2023-02-01 16:30:01,158:INFO:testStrategy:main.py:101:handleKline:185174: self.closeSec=1675240199, self.tradeDate='20230201', self.openTime='162000', self.closeTime='162959',self.symbol='BTCUSDT',self.open='23020.7', self.close='22962.2'
2023-02-01 16:30:01,178:INFO:testStrategy:main.py:102:handleKline:185174: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
12190  20230201   154000    154959  1675237799  23081.8  23069.3
12191  20230201   155000    155959  1675238399  23069.4    23071
12192  20230201   160000    160959  1675238999  23070.9    23075
12193  20230201   161000    161959  1675239599    23075  23022.6
12194  20230201   162000    162959  1675240199  23020.7  22962.2
2023-02-01 16:30:01,179:INFO:testStrategy:main.py:103:handleKline:185174: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': True, 'isOpenSell': False, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True, 'isCorr': False}


## /root/FIL/strategy/sr_min/log.txt ----- -----

--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=0, self.total=1000000.0, self.flagDict['side']='', self.tradeCount=0, self.count=15036
self.closeSec=1675240199, self.tradeDate='20230201', self.openTime='162500', self.closeTime='162959', self.symbol='BTCUSDT', self.open=22990.8, self.close=22962.2, self.high=23004.2, self.low=22933.8, self.vol=2974.897, self.amt=68325632.276 
127.0.0.1 - - [01/Feb/2023 16:30:01] "POST / HTTP/1.1" 200 -
2023-02-01 16:30:01,111:INFO:sr_min:main.py:172:handleKline:449472: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5953  20230201   160500    160959  ...         0.0        0.0       0
5954  20230201   161000    161459  ...         0.0        0.0       0
5955  20230201   161500    161959  ...         0.0        0.0       0
5956  20230201   162000    162459  ...         0.0        0.0       0
5957  20230201   162500    162959  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-02-01 16:30:01,112:INFO:sr_min:main.py:175:handleKline:449472: self.closeSec=1675240199, self.tradeDate='20230201', self.openTime='162500', self.closeTime='162959',self.symbol='BTCUSDT',self.open=22990.8, self.close=22962.2, self.high=23004.2, self.low=22933.8, self.vol=2974.897, self.amt=68325632.276, ukdf['pct'].iloc[-1]=-0.0013 , ukdf['amount'].iloc[-1]=68325632.276, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5957, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': []}
type(curSign)=<class 'int'>, curSign=0, self.sign=0
--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=0, self.total=1000000.0, self.flagDict['side']='', self.tradeCount=0, self.count=15037
self.closeSec=1675240499, self.tradeDate='20230201', self.openTime='163000', self.closeTime='163459', self.symbol='BTCUSDT', self.open=22962.3, self.close=22985.6, self.high=22992.8, self.low=22936.3, self.vol=2414.936, self.amt=55464313.6127 
127.0.0.1 - - [01/Feb/2023 16:35:00] "POST / HTTP/1.1" 200 -
2023-02-01 16:35:00,543:INFO:sr_min:main.py:172:handleKline:449472: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5954  20230201   161000    161459  ...         0.0        0.0       0
5955  20230201   161500    161959  ...         0.0        0.0       0
5956  20230201   162000    162459  ...         0.0        0.0       0
5957  20230201   162500    162959  ...         0.0        0.0       0
5958  20230201   163000    163459  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-02-01 16:35:00,543:INFO:sr_min:main.py:175:handleKline:449472: self.closeSec=1675240499, self.tradeDate='20230201', self.openTime='163000', self.closeTime='163459',self.symbol='BTCUSDT',self.open=22962.3, self.close=22985.6, self.high=22992.8, self.low=22936.3, self.vol=2414.936, self.amt=55464313.6127, ukdf['pct'].iloc[-1]=0.001019 , ukdf['amount'].iloc[-1]=55464313.6127, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5958, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': []}
type(curSign)=<class 'int'>, curSign=0, self.sign=0


## /root/FIL/strategy/s_rsrs/log.txt ----- -----

721  20230201   040000    075959  1675209599  ...    721  0.611552  0.441319     NaN
722  20230201   080000    115959  1675223999  ...    722  0.640645  0.537671     NaN

[5 rows x 15 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '38.964', 'enterprice': '23700.1', 'countrevence': '0', 'unrealprofit': '-22330.2684', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '23127', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'numpy.int64'>, curSign=-9223372036854775808, self.sign=1
127.0.0.1 - - [01/Feb/2023 16:00:02] "POST / HTTP/1.1" 200 -
--handleKline--:  version='2.0.0', self.name='s_rsrs', self.symbol='BTCUSDT', interval='4h', intervalSec=14400, wid=25, thd=0.6, self.sign=1, self.total=922527.2457035999, self.flagDict['side']='buy', self.tradeCount=16, self.count=408
self.closeSec=1675238399, self.tradeDate='20230201', self.openTime='120000', self.closeTime='155959', self.symbol='BTCUSDT', self.open=23127.4, self.close=23071.0, self.high=23160.4, self.low=23011.5, self.vol=33068.509, self.amt=763819416.1376 
2023-02-01 16:00:02,321:INFO:s_rsrs:main.py:141:handleKline:185271: self.closeSec=1675238399, self.tradeDate='20230201', self.openTime='120000', self.closeTime='155959',self.symbol='BTCUSDT',self.open=23127.4, self.close=23071.0, self.high=23160.4, self.low=23011.5, self.vol=33068.509, self.amt=763819416.1376 
2023-02-01 16:00:02,365:INFO:s_rsrs:main.py:142:handleKline:185271: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime  ...         vol           amt       pct
719  20230131   200000    235959  ...  113354.585  2.613078e+09  0.011244
720  20230201   000000    035959  ...   49408.861  1.142916e+09  0.001761
721  20230201   040000    075959  ...  105553.545  2.432205e+09 -0.001520
722  20230201   080000    115959  ...   41016.975  9.469843e+08  0.000342
723  20230201   120000    155959  ...   33068.509  7.638194e+08 -0.002434

[5 rows x 11 columns]
2023-02-01 16:00:04,346:INFO:s_rsrs:main.py:151:handleKline:185271: df_s.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec  ...  index      beta    zscore  signal
719  20230131   200000    235959  1675180799  ...    719  0.665860  0.579371     NaN
720  20230201   000000    035959  1675195199  ...    720  0.649389  0.538291     NaN
721  20230201   040000    075959  1675209599  ...    721  0.611552  0.441319     NaN
722  20230201   080000    115959  1675223999  ...    722  0.640645  0.537671     NaN
723  20230201   120000    155959  1675238399  ...    723  0.643037  0.550769     NaN

[5 rows x 15 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '38.964', 'enterprice': '23700.1', 'countrevence': '0', 'unrealprofit': '-24516.1488', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '23070.9', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'numpy.int64'>, curSign=-9223372036854775808, self.sign=1


