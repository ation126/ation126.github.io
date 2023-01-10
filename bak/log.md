# 20230110 16:16:01

## /root/FIL/strategy/amihud/log.txt ----- -----

127.0.0.1 - - [10/Jan/2023 16:10:01] "POST / HTTP/1.1" 200 -
--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=993672.4896432, self.flagDict['side']='sell', self.tradeCount=2, self.count=12698
self.closeSec=1673338199, self.tradeDate='20230110', self.openTime='160500', self.closeTime='160959', self.symbol='BTCUSDT', self.open=17190.5, self.close=17182.1, self.high=17196.8, self.low=17181.2, self.vol=668.333, self.amt=11487869.4677 
2023-01-10 16:10:01,487:INFO:amihud:main.py:172:handleKline:200676: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5949  20230110   154500    154959  ...         0.0        0.0       0
5950  20230110   155000    155459  ...         0.0        0.0       0
5951  20230110   155500    155959  ...         0.0        0.0       0
5952  20230110   160000    160459  ...         0.0        0.0       0
5953  20230110   160500    160959  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-01-10 16:10:01,488:INFO:amihud:main.py:175:handleKline:200676: self.closeSec=1673338199, self.tradeDate='20230110', self.openTime='160500', self.closeTime='160959',self.symbol='BTCUSDT',self.open=17190.5, self.close=17182.1, self.high=17196.8, self.low=17181.2, self.vol=668.333, self.amt=11487869.4677, ukdf['pct'].iloc[-1]=-0.000489 , ukdf['amount'].iloc[-1]=11487869.4677, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5953, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '60.176', 'enterprice': '16529.3', 'countrevence': '0', 'unrealprofit': '-39282.8928', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '17182.1', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1
--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=993672.4896432, self.flagDict['side']='sell', self.tradeCount=2, self.count=12699
self.closeSec=1673338499, self.tradeDate='20230110', self.openTime='161000', self.closeTime='161459', self.symbol='BTCUSDT', self.open=17182.0, self.close=17186.8, self.high=17189.5, self.low=17182.0, self.vol=391.269, self.amt=6724630.02 
127.0.0.1 - - [10/Jan/2023 16:15:00] "POST / HTTP/1.1" 200 -
2023-01-10 16:15:00,606:INFO:amihud:main.py:172:handleKline:200676: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5950  20230110   155000    155459  ...         0.0        0.0       0
5951  20230110   155500    155959  ...         0.0        0.0       0
5952  20230110   160000    160459  ...         0.0        0.0       0
5953  20230110   160500    160959  ...         0.0        0.0       0
5954  20230110   161000    161459  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-01-10 16:15:00,606:INFO:amihud:main.py:175:handleKline:200676: self.closeSec=1673338499, self.tradeDate='20230110', self.openTime='161000', self.closeTime='161459',self.symbol='BTCUSDT',self.open=17182.0, self.close=17186.8, self.high=17189.5, self.low=17182.0, self.vol=391.269, self.amt=6724630.02, ukdf['pct'].iloc[-1]=0.000274 , ukdf['amount'].iloc[-1]=6724630.02, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5954, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '60.176', 'enterprice': '16529.3', 'countrevence': '0', 'unrealprofit': '-39573.20788983616', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '17186.92443316', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1


## /root/FIL/strategy/factorcheck/log.txt ----- -----

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=127, self.factor=0.510192557970662, self.count=13264 

self.closeSec=1673338199, self.tradeDate='20230110', self.openTime='160500', self.closeTime='160959', self.symbol='BTCUSDT', self.open=17190.5, self.close=17182.1, self.high=17196.8, self.low=17181.2 
2023-01-10 16:10:01,439:INFO:factorcheck2:main.py:126:handleKline:185239: self.closeSec=1673338199, self.tradeDate='20230110', self.openTime='160500', self.closeTime='160959',self.symbol='BTCUSDT',self.open=17190.5, self.close=17182.1, self.high=17196.8, self.low=17181.2   
2023-01-10 16:10:01,477:INFO:factorcheck2:main.py:127:handleKline:185239: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime    closeSec  ...      low       pct  index  idx
1629  20230110   154500    154959  1673336999  ...  17198.6  0.000087   1629    3
1630  20230110   155000    155459  1673337299  ...  17191.3 -0.000407   1630    4
1631  20230110   155500    155959  1673337599  ...  17191.9  0.000070   1631    5
1632  20230110   160000    160459  1673337899  ...  17190.5 -0.000244   1632    0
1633  20230110   160500    160959  1673338199  ...  17181.2 -0.000489   1633    1

[5 rows x 11 columns]
2023-01-10 16:10:01,479:INFO:factorcheck2:main.py:128:handleKline:185239: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}
127.0.0.1 - - [10/Jan/2023 16:15:00] "POST / HTTP/1.1" 200 -

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=127, self.factor=0.510192557970662, self.count=13265 

self.closeSec=1673338499, self.tradeDate='20230110', self.openTime='161000', self.closeTime='161459', self.symbol='BTCUSDT', self.open=17182.0, self.close=17186.8, self.high=17189.5, self.low=17182.0 
2023-01-10 16:15:00,556:INFO:factorcheck2:main.py:126:handleKline:185239: self.closeSec=1673338499, self.tradeDate='20230110', self.openTime='161000', self.closeTime='161459',self.symbol='BTCUSDT',self.open=17182.0, self.close=17186.8, self.high=17189.5, self.low=17182.0   
2023-01-10 16:15:00,588:INFO:factorcheck2:main.py:127:handleKline:185239: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime    closeSec  ...      low       pct  index  idx
1630  20230110   155000    155459  1673337299  ...  17191.3 -0.000407   1630    4
1631  20230110   155500    155959  1673337599  ...  17191.9  0.000070   1631    5
1632  20230110   160000    160459  1673337899  ...  17190.5 -0.000244   1632    0
1633  20230110   160500    160959  1673338199  ...  17181.2 -0.000489   1633    1
1634  20230110   161000    161459  1673338499  ...  17182.0  0.000274   1634    2

[5 rows x 11 columns]
2023-01-10 16:15:00,588:INFO:factorcheck2:main.py:128:handleKline:185239: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}


## /root/FIL/strategy/logic/log.txt ----- -----

2023-01-10 16:00:16,684:DEBUG:logic:main.py:456:getModel:726423: df_s.iloc[-5:,:] :
          date closeTime     open  ...    alpha58   alpha67   alpha72
5786  20230110    132959  17215.6  ...  52.083333  0.545070  0.574606
5787  20230110    135959  17207.2  ...  52.083333  0.553359  0.577239
5788  20230110    142959  17222.4  ...  52.083333  0.541014  0.584372
5789  20230110    145959  17203.4  ...  52.083333  0.536747  0.592662
5790  20230110    152959  17196.9  ...  52.083333  0.531819  0.602279

[5 rows x 33 columns]
0.5424354243542435
acc is : 0.5424354243542435
2023-01-10 16:00:16,791:INFO:logic:main.py:461:getModel:726423: df_pred.iloc[-5:,:] :
     pred    prob_0    prob_1  actual  ...  nav  sign   cost_        bm
537     0  0.501711  0.498289       1  ...  NaN   NaN -0.0016  1.035996
538     0  0.507664  0.492336       0  ...  NaN   NaN -0.0016  1.034859
539     1  0.496717  0.503283       0  ...  NaN   NaN -0.0016  1.034462
540     1  0.498365  0.501635       0  ...  NaN   NaN -0.0016  1.034005
541     1  0.495079  0.504921       1  ...  NaN   NaN -0.0016  1.034336

[5 rows x 10 columns]
2023-01-10 16:00:16,812:INFO:logic:main.py:471:getModel:726423: df_panel.iloc[-5:,:] :
    pred    prob_0    prob_1  actual  ...  nav  sign   cost_        bm
45     0  0.502089  0.497911       1  ...  NaN   NaN -0.0016  1.036614
46     0  0.507845  0.492155       0  ...  NaN   NaN -0.0016  1.034505
47     1  0.496729  0.503271       0  ...  NaN   NaN -0.0016  1.034064
48     1  0.498187  0.501813       0  ...  NaN   NaN -0.0016  1.033408
49     1  0.495079  0.504921       1  ...  NaN   NaN -0.0016  1.034336

[5 rows x 10 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '42.528', 'enterprice': '16701.5', 'countrevence': '0', 'unrealprofit': '20949.2928', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '17194.1', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}


## /root/FIL/strategy/modifiedmom/log.txt ----- -----

526  20230110   154000    154959  1673336999  17192.7  17200.5  0.000460
2023-01-10 15:50:00,568:INFO:modifiedmom:main.py:146:handleKline:185213: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': True, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True}

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=6631 

self.closeSec=1673337599, self.tradeDate='20230110', self.openTime='155000', self.closeTime='155959', self.symbol='BTCUSDT', self.open='17198.7', self.close='17194.7'
2023-01-10 16:00:00,952:INFO:modifiedmom:main.py:144:handleKline:185213: self.closeSec=1673337599, self.tradeDate='20230110', self.openTime='155000', self.closeTime='155959',self.symbol='BTCUSDT',self.open='17198.7', self.close='17194.7'
127.0.0.1 - - [10/Jan/2023 16:00:00] "POST / HTTP/1.1" 200 -
2023-01-10 16:00:00,980:INFO:modifiedmom:main.py:145:handleKline:185213: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec     open    close       pct
523  20230110   151000    151959  1673335199  17193.6  17192.2 -0.000087
524  20230110   152000    152959  1673335799  17192.1  17189.2 -0.000174
525  20230110   153000    153959  1673336399  17189.1  17192.6  0.000198
526  20230110   154000    154959  1673336999  17192.7  17200.5  0.000460
527  20230110   155000    155959  1673337599  17198.7  17194.7 -0.000337
2023-01-10 16:00:00,980:INFO:modifiedmom:main.py:146:handleKline:185213: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': True, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True}

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=6632 

self.closeSec=1673338199, self.tradeDate='20230110', self.openTime='160000', self.closeTime='160959', self.symbol='BTCUSDT', self.open='17194.6', self.close='17182.1'
2023-01-10 16:10:01,549:INFO:modifiedmom:main.py:144:handleKline:185213: self.closeSec=1673338199, self.tradeDate='20230110', self.openTime='160000', self.closeTime='160959',self.symbol='BTCUSDT',self.open='17194.6', self.close='17182.1'
127.0.0.1 - - [10/Jan/2023 16:10:01] "POST / HTTP/1.1" 200 -
2023-01-10 16:10:01,588:INFO:modifiedmom:main.py:145:handleKline:185213: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec     open    close       pct
524  20230110   152000    152959  1673335799  17192.1  17189.2 -0.000174
525  20230110   153000    153959  1673336399  17189.1  17192.6  0.000198
526  20230110   154000    154959  1673336999  17192.7  17200.5  0.000460
527  20230110   155000    155959  1673337599  17198.7  17194.7 -0.000337
528  20230110   160000    160959  1673338199  17194.6  17182.1 -0.000733
2023-01-10 16:10:01,588:INFO:modifiedmom:main.py:146:handleKline:185213: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': True, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True}


## /root/FIL/strategy/pyemd/log.txt ----- -----

17518  20230110   154000    154959  1673336999  17192.7  17200.5
2023-01-10 15:50:00,593:INFO:pyemd2:main.py:127:handleKline:185189: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}
127.0.0.1 - - [10/Jan/2023 16:00:00] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=6632 

self.closeSec=1673337599, self.tradeDate='20230110', self.openTime='155000', self.closeTime='155959', self.symbol='BTCUSDT', self.open='17198.7', self.close='17194.7'
2023-01-10 16:00:00,955:INFO:pyemd2:main.py:125:handleKline:185189: self.closeSec=1673337599, self.tradeDate='20230110', self.openTime='155000', self.closeTime='155959',self.symbol='BTCUSDT',self.open='17198.7', self.close='17194.7'
2023-01-10 16:00:00,997:INFO:pyemd2:main.py:126:handleKline:185189: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
17515  20230110   151000    151959  1673335199  17193.6  17192.2
17516  20230110   152000    152959  1673335799  17192.1  17189.2
17517  20230110   153000    153959  1673336399  17189.1  17192.6
17518  20230110   154000    154959  1673336999  17192.7  17200.5
17519  20230110   155000    155959  1673337599  17198.7  17194.7
2023-01-10 16:00:00,997:INFO:pyemd2:main.py:127:handleKline:185189: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}
127.0.0.1 - - [10/Jan/2023 16:10:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=6633 

self.closeSec=1673338199, self.tradeDate='20230110', self.openTime='160000', self.closeTime='160959', self.symbol='BTCUSDT', self.open='17194.6', self.close='17182.1'
2023-01-10 16:10:01,557:INFO:pyemd2:main.py:125:handleKline:185189: self.closeSec=1673338199, self.tradeDate='20230110', self.openTime='160000', self.closeTime='160959',self.symbol='BTCUSDT',self.open='17194.6', self.close='17182.1'
2023-01-10 16:10:01,608:INFO:pyemd2:main.py:126:handleKline:185189: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
17516  20230110   152000    152959  1673335799  17192.1  17189.2
17517  20230110   153000    153959  1673336399  17189.1  17192.6
17518  20230110   154000    154959  1673336999  17192.7  17200.5
17519  20230110   155000    155959  1673337599  17198.7  17194.7
17520  20230110   160000    160959  1673338199  17194.6  17182.1
2023-01-10 16:10:01,609:INFO:pyemd2:main.py:127:handleKline:185189: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}


## /root/FIL/strategy/similarity/log.txt ----- -----

12190  20230110   154000    154959  1673336999  17192.7  17200.5
2023-01-10 15:50:00,576:INFO:testStrategy:main.py:103:handleKline:185174: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': True, 'isOpenSell': False, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True, 'isCorr': False}

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=6632 

self.closeSec=1673337599, self.tradeDate='20230110', self.openTime='155000', self.closeTime='155959', self.symbol='BTCUSDT', self.open='17198.7', self.close='17194.7'
127.0.0.1 - - [10/Jan/2023 16:00:00] "POST / HTTP/1.1" 200 -
2023-01-10 16:00:00,959:INFO:testStrategy:main.py:101:handleKline:185174: self.closeSec=1673337599, self.tradeDate='20230110', self.openTime='155000', self.closeTime='155959',self.symbol='BTCUSDT',self.open='17198.7', self.close='17194.7'
2023-01-10 16:00:00,988:INFO:testStrategy:main.py:102:handleKline:185174: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
12187  20230110   151000    151959  1673335199  17193.6  17192.2
12188  20230110   152000    152959  1673335799  17192.1  17189.2
12189  20230110   153000    153959  1673336399  17189.1  17192.6
12190  20230110   154000    154959  1673336999  17192.7  17200.5
12191  20230110   155000    155959  1673337599  17198.7  17194.7
2023-01-10 16:00:00,990:INFO:testStrategy:main.py:103:handleKline:185174: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': True, 'isOpenSell': False, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True, 'isCorr': False}

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=6633 

self.closeSec=1673338199, self.tradeDate='20230110', self.openTime='160000', self.closeTime='160959', self.symbol='BTCUSDT', self.open='17194.6', self.close='17182.1'
127.0.0.1 - - [10/Jan/2023 16:10:01] "POST / HTTP/1.1" 200 -
2023-01-10 16:10:01,571:INFO:testStrategy:main.py:101:handleKline:185174: self.closeSec=1673338199, self.tradeDate='20230110', self.openTime='160000', self.closeTime='160959',self.symbol='BTCUSDT',self.open='17194.6', self.close='17182.1'
2023-01-10 16:10:01,617:INFO:testStrategy:main.py:102:handleKline:185174: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
12188  20230110   152000    152959  1673335799  17192.1  17189.2
12189  20230110   153000    153959  1673336399  17189.1  17192.6
12190  20230110   154000    154959  1673336999  17192.7  17200.5
12191  20230110   155000    155959  1673337599  17198.7  17194.7
12192  20230110   160000    160959  1673338199  17194.6  17182.1
2023-01-10 16:10:01,618:INFO:testStrategy:main.py:103:handleKline:185174: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': True, 'isOpenSell': False, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True, 'isCorr': False}


## /root/FIL/strategy/sr_min/log.txt ----- -----

127.0.0.1 - - [10/Jan/2023 16:10:01] "POST / HTTP/1.1" 200 -
--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=0, self.total=1000000.0, self.flagDict['side']='', self.tradeCount=0, self.count=8696
self.closeSec=1673338199, self.tradeDate='20230110', self.openTime='160500', self.closeTime='160959', self.symbol='BTCUSDT', self.open=17190.5, self.close=17182.1, self.high=17196.8, self.low=17181.2, self.vol=668.333, self.amt=11487869.4677 
2023-01-10 16:10:01,443:INFO:sr_min:main.py:172:handleKline:449472: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5949  20230110   154500    154959  ...         0.0        0.0       0
5950  20230110   155000    155459  ...         0.0        0.0       0
5951  20230110   155500    155959  ...         0.0        0.0       0
5952  20230110   160000    160459  ...         0.0        0.0       0
5953  20230110   160500    160959  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-01-10 16:10:01,443:INFO:sr_min:main.py:175:handleKline:449472: self.closeSec=1673338199, self.tradeDate='20230110', self.openTime='160500', self.closeTime='160959',self.symbol='BTCUSDT',self.open=17190.5, self.close=17182.1, self.high=17196.8, self.low=17181.2, self.vol=668.333, self.amt=11487869.4677, ukdf['pct'].iloc[-1]=-0.000489 , ukdf['amount'].iloc[-1]=11487869.4677, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5953, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': []}
type(curSign)=<class 'int'>, curSign=0, self.sign=0
127.0.0.1 - - [10/Jan/2023 16:15:00] "POST / HTTP/1.1" 200 -
--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=0, self.total=1000000.0, self.flagDict['side']='', self.tradeCount=0, self.count=8697
self.closeSec=1673338499, self.tradeDate='20230110', self.openTime='161000', self.closeTime='161459', self.symbol='BTCUSDT', self.open=17182.0, self.close=17186.8, self.high=17189.5, self.low=17182.0, self.vol=391.269, self.amt=6724630.02 
2023-01-10 16:15:00,613:INFO:sr_min:main.py:172:handleKline:449472: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5950  20230110   155000    155459  ...         0.0        0.0       0
5951  20230110   155500    155959  ...         0.0        0.0       0
5952  20230110   160000    160459  ...         0.0        0.0       0
5953  20230110   160500    160959  ...         0.0        0.0       0
5954  20230110   161000    161459  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-01-10 16:15:00,613:INFO:sr_min:main.py:175:handleKline:449472: self.closeSec=1673338499, self.tradeDate='20230110', self.openTime='161000', self.closeTime='161459',self.symbol='BTCUSDT',self.open=17182.0, self.close=17186.8, self.high=17189.5, self.low=17182.0, self.vol=391.269, self.amt=6724630.02, ukdf['pct'].iloc[-1]=0.000274 , ukdf['amount'].iloc[-1]=6724630.02, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5954, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': []}
type(curSign)=<class 'int'>, curSign=0, self.sign=0


## /root/FIL/strategy/s_rsrs/log.txt ----- -----

721  20230110   040000    075959  1673308799  ...    721  0.950988  1.925823     1.0
722  20230110   080000    115959  1673323199  ...    722  0.929235  1.799425     1.0

[5 rows x 15 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '51.136', 'enterprice': '17188.2', 'countrevence': '0', 'unrealprofit': '603.4048', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '17200', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'numpy.int64'>, curSign=1, self.sign=1
--handleKline--:  version='2.0.0', self.name='s_rsrs', self.symbol='BTCUSDT', interval='4h', intervalSec=14400, wid=25, thd=0.6, self.sign=1, self.total=878056.8594048, self.flagDict['side']='buy', self.tradeCount=12, self.count=276
self.closeSec=1673337599, self.tradeDate='20230110', self.openTime='120000', self.closeTime='155959', self.symbol='BTCUSDT', self.open=17199.9, self.close=17194.7, self.high=17228.0, self.low=17181.8, self.vol=18254.506, self.amt=314034010.2968 
127.0.0.1 - - [10/Jan/2023 16:00:00] "POST / HTTP/1.1" 200 -
2023-01-10 16:00:00,760:INFO:s_rsrs:main.py:141:handleKline:185271: self.closeSec=1673337599, self.tradeDate='20230110', self.openTime='120000', self.closeTime='155959',self.symbol='BTCUSDT',self.open=17199.9, self.close=17194.7, self.high=17228.0, self.low=17181.8, self.vol=18254.506, self.amt=314034010.2968 
2023-01-10 16:00:00,784:INFO:s_rsrs:main.py:142:handleKline:185271: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime  ...        vol           amt       pct
719  20230109   200000    235959  ...  80348.391  1.386487e+09  0.001747
720  20230110   000000    035959  ...  77462.066  1.342329e+09  0.001361
721  20230110   040000    075959  ...  70626.832  1.214984e+09 -0.006711
722  20230110   080000    115959  ...  27484.953  4.723608e+08  0.001759
723  20230110   120000    155959  ...  18254.506  3.140340e+08 -0.000302

[5 rows x 11 columns]
2023-01-10 16:00:02,294:INFO:s_rsrs:main.py:151:handleKline:185271: df_s.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec  ...  index      beta    zscore  signal
719  20230109   200000    235959  1673279999  ...    719  0.801034  1.512647     1.0
720  20230110   000000    035959  1673294399  ...    720  0.904541  1.823699     1.0
721  20230110   040000    075959  1673308799  ...    721  0.950988  1.925823     1.0
722  20230110   080000    115959  1673323199  ...    722  0.929235  1.799425     1.0
723  20230110   120000    155959  1673337599  ...    723  0.878976  1.587603     1.0

[5 rows x 15 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '51.136', 'enterprice': '17188.2', 'countrevence': '0', 'unrealprofit': '348.11744419648', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '17195.00767843', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'numpy.int64'>, curSign=1, self.sign=1


