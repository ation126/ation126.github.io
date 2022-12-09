# 20221209 16:16:01

## /root/FIL/strategy/amihud/log.txt ----- -----

--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=993672.4896432, self.flagDict['side']='sell', self.tradeCount=2, self.count=3482
self.closeSec=1670573399, self.tradeDate='20221209', self.openTime='160500', self.closeTime='160959', self.symbol='BTCUSDT', self.open=17198.5, self.close=17197.1, self.high=17200.4, self.low=17197.1, self.vol=577.656, self.amt=9934947.3191 
127.0.0.1 - - [09/Dec/2022 16:10:01] "POST / HTTP/1.1" 200 -
2022-12-09 16:10:01,453:INFO:amihud:main.py:172:handleKline:200676: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5949  20221209   154500    154959  ...    0.050490   0.189521       0
5950  20221209   155000    155459  ...    0.050346   0.189363       0
5951  20221209   155500    155959  ...    0.050203   0.189206       0
5952  20221209   160000    160459  ...    0.050060   0.189048       0
5953  20221209   160500    160959  ...    0.049916   0.188890       0

[5 rows x 18 columns]
2022-12-09 16:10:01,453:INFO:amihud:main.py:175:handleKline:200676: self.closeSec=1670573399, self.tradeDate='20221209', self.openTime='160500', self.closeTime='160959',self.symbol='BTCUSDT',self.open=17198.5, self.close=17197.1, self.high=17200.4, self.low=17197.1, self.vol=577.656, self.amt=9934947.3191, ukdf['pct'].iloc[-1]=-7.6e-05 , ukdf['amount'].iloc[-1]=9934947.3191, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5953, value=0.0, value_mean=0.04991633810933266, signal=0, value_std=0.1888899011990013 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '60.176', 'enterprice': '16529.3', 'countrevence': '0', 'unrealprofit': '-40245.93883720224', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '17198.10382274', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1
--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=993672.4896432, self.flagDict['side']='sell', self.tradeCount=2, self.count=3483
self.closeSec=1670573699, self.tradeDate='20221209', self.openTime='161000', self.closeTime='161459', self.symbol='BTCUSDT', self.open=17197.2, self.close=17199.2, self.high=17199.3, self.low=17197.1, self.vol=361.373, self.amt=6215155.7147 
127.0.0.1 - - [09/Dec/2022 16:15:00] "POST / HTTP/1.1" 200 -
2022-12-09 16:15:00,629:INFO:amihud:main.py:172:handleKline:200676: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5950  20221209   155000    155459  ...    0.050346   0.189363       0
5951  20221209   155500    155959  ...    0.050203   0.189206       0
5952  20221209   160000    160459  ...    0.050060   0.189048       0
5953  20221209   160500    160959  ...    0.049916   0.188890       0
5954  20221209   161000    161459  ...    0.049773   0.188731       0

[5 rows x 18 columns]
2022-12-09 16:15:00,629:INFO:amihud:main.py:175:handleKline:200676: self.closeSec=1670573699, self.tradeDate='20221209', self.openTime='161000', self.closeTime='161459',self.symbol='BTCUSDT',self.open=17197.2, self.close=17199.2, self.high=17199.3, self.low=17197.1, self.vol=361.373, self.amt=6215155.7147, ukdf['pct'].iloc[-1]=0.000122 , ukdf['amount'].iloc[-1]=6215155.7147, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5954, value=0.0, value_mean=0.049772737692682055, signal=0, value_std=0.18873122232689837 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '60.176', 'enterprice': '16529.3', 'countrevence': '0', 'unrealprofit': '-40311.9024', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '17199.2', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1


## /root/FIL/strategy/factorcheck/log.txt ----- -----

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=32, self.factor=0.3436676689923467, self.count=4048 

self.closeSec=1670573399, self.tradeDate='20221209', self.openTime='160500', self.closeTime='160959', self.symbol='BTCUSDT', self.open=17198.5, self.close=17197.1, self.high=17200.4, self.low=17197.1 
2022-12-09 16:10:01,424:INFO:factorcheck2:main.py:126:handleKline:185239: self.closeSec=1670573399, self.tradeDate='20221209', self.openTime='160500', self.closeTime='160959',self.symbol='BTCUSDT',self.open=17198.5, self.close=17197.1, self.high=17200.4, self.low=17197.1   
2022-12-09 16:10:01,444:INFO:factorcheck2:main.py:127:handleKline:185239: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime    closeSec  ...      low       pct  index  idx
1629  20221209   154500    154959  1670572199  ...  17211.8  0.000198   1629    3
1630  20221209   155000    155459  1670572499  ...  17203.2 -0.000709   1630    4
1631  20221209   155500    155959  1670572799  ...  17203.0  0.000023   1631    5
1632  20221209   160000    160459  1670573099  ...  17198.4 -0.000308   1632    0
1633  20221209   160500    160959  1670573399  ...  17197.1 -0.000076   1633    1

[5 rows x 11 columns]
2022-12-09 16:10:01,444:INFO:factorcheck2:main.py:128:handleKline:185239: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': True, 'isOpenSell': False, 'isCloseBuy': False, 'isCloseSell': False, 'isOpen': True, 'isClose': False, 'isTrig': True}
127.0.0.1 - - [09/Dec/2022 16:15:00] "POST / HTTP/1.1" 200 -

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=32, self.factor=0.3436676689923467, self.count=4049 

self.closeSec=1670573699, self.tradeDate='20221209', self.openTime='161000', self.closeTime='161459', self.symbol='BTCUSDT', self.open=17197.2, self.close=17199.2, self.high=17199.3, self.low=17197.1 
2022-12-09 16:15:00,543:INFO:factorcheck2:main.py:126:handleKline:185239: self.closeSec=1670573699, self.tradeDate='20221209', self.openTime='161000', self.closeTime='161459',self.symbol='BTCUSDT',self.open=17197.2, self.close=17199.2, self.high=17199.3, self.low=17197.1   
2022-12-09 16:15:00,624:INFO:factorcheck2:main.py:127:handleKline:185239: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime    closeSec  ...      low       pct  index  idx
1630  20221209   155000    155459  1670572499  ...  17203.2 -0.000709   1630    4
1631  20221209   155500    155959  1670572799  ...  17203.0  0.000023   1631    5
1632  20221209   160000    160459  1670573099  ...  17198.4 -0.000308   1632    0
1633  20221209   160500    160959  1670573399  ...  17197.1 -0.000076   1633    1
1634  20221209   161000    161459  1670573699  ...  17197.1  0.000122   1634    2

[5 rows x 11 columns]
2022-12-09 16:15:00,624:INFO:factorcheck2:main.py:128:handleKline:185239: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': True, 'isOpenSell': False, 'isCloseBuy': False, 'isCloseSell': False, 'isOpen': True, 'isClose': False, 'isTrig': True}


## /root/FIL/strategy/logic/log.txt ----- -----

2022-12-09 16:00:18,269:DEBUG:logic:main.py:454:getModel:174970: df_s.iloc[-5:,:] :
          date closeTime     open  ...    alpha58   alpha67   alpha72
5786  20221209    132959  17214.9  ...  53.750000  0.598638  0.186946
5787  20221209    135959  17195.9  ...  54.166667  0.604544  0.184086
5788  20221209    142959  17210.1  ...  53.750000  0.592133  0.183790
5789  20221209    145959  17189.9  ...  54.166667  0.599435  0.181449
5790  20221209    152959  17208.1  ...  54.166667  0.605801  0.177439

[5 rows x 33 columns]
0.5571955719557196
acc is : 0.5571955719557196
2022-12-09 16:00:18,376:INFO:logic:main.py:459:getModel:174970: df_pred.iloc[-5:,:] :
     pred    prob_0    prob_1  actual  ...       nav  sign  cost_        bm
537     1  0.485207  0.514793       1  ...  1.006321   1.0    0.0  1.047001
538     1  0.493330  0.506670       0  ...  1.005104   1.0    0.0  1.045735
539     1  0.484992  0.515008       1  ...  1.006163   1.0    0.0  1.046836
540     1  0.493790  0.506210       1  ...  1.007098   1.0    0.0  1.047810
541     1  0.494018  0.505982       0  ...  1.005911   1.0    0.0  1.046575

[5 rows x 10 columns]
2022-12-09 16:00:18,399:INFO:logic:main.py:469:getModel:174970: df_panel.iloc[-5:,:] :
    pred    prob_0    prob_1  actual  ...       nav  sign  cost_        bm
45     1  0.484217  0.515783       1  ...  1.006321   1.0    0.0  1.038955
46     1  0.492769  0.507231       0  ...  1.005104   1.0    0.0  1.044122
47     1  0.484953  0.515047       1  ...  1.006163   1.0    0.0  1.047824
48     1  0.493343  0.506657       1  ...  1.007098   1.0    0.0  1.045672
49     1  0.494018  0.505982       0  ...  1.005911   1.0    0.0  1.046575

[5 rows x 10 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '37.789', 'enterprice': '17212.8', 'countrevence': '0', 'unrealprofit': '-338.05086172475', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '17203.85425225', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}


## /root/FIL/strategy/modifiedmom/log.txt ----- -----

526  20221209   154000    154959  1670572199  17215.8  17215.5 -0.000035
2022-12-09 15:50:00,567:INFO:modifiedmom:main.py:146:handleKline:185213: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': True, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True}
127.0.0.1 - - [09/Dec/2022 16:00:00] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=2023 

self.closeSec=1670572799, self.tradeDate='20221209', self.openTime='155000', self.closeTime='155959', self.symbol='BTCUSDT', self.open='17215.5', self.close='17203.7'
2022-12-09 16:00:01,017:INFO:modifiedmom:main.py:144:handleKline:185213: self.closeSec=1670572799, self.tradeDate='20221209', self.openTime='155000', self.closeTime='155959',self.symbol='BTCUSDT',self.open='17215.5', self.close='17203.7'
2022-12-09 16:00:01,057:INFO:modifiedmom:main.py:145:handleKline:185213: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec     open    close       pct
523  20221209   151000    151959  1670570399  17217.2  17209.2 -0.000465
524  20221209   152000    152959  1670570999  17209.3  17224.1  0.000866
525  20221209   153000    153959  1670571599  17224.1  17216.1 -0.000464
526  20221209   154000    154959  1670572199  17215.8  17215.5 -0.000035
527  20221209   155000    155959  1670572799  17215.5  17203.7 -0.000685
2022-12-09 16:00:01,057:INFO:modifiedmom:main.py:146:handleKline:185213: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': True, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True}

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=2024 

self.closeSec=1670573399, self.tradeDate='20221209', self.openTime='160000', self.closeTime='160959', self.symbol='BTCUSDT', self.open='17203.7', self.close='17197.1'
2022-12-09 16:10:01,518:INFO:modifiedmom:main.py:144:handleKline:185213: self.closeSec=1670573399, self.tradeDate='20221209', self.openTime='160000', self.closeTime='160959',self.symbol='BTCUSDT',self.open='17203.7', self.close='17197.1'
127.0.0.1 - - [09/Dec/2022 16:10:01] "POST / HTTP/1.1" 200 -
2022-12-09 16:10:01,539:INFO:modifiedmom:main.py:145:handleKline:185213: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec     open    close       pct
524  20221209   152000    152959  1670570999  17209.3  17224.1  0.000866
525  20221209   153000    153959  1670571599  17224.1  17216.1 -0.000464
526  20221209   154000    154959  1670572199  17215.8  17215.5 -0.000035
527  20221209   155000    155959  1670572799  17215.5  17203.7 -0.000685
528  20221209   160000    160959  1670573399  17203.7  17197.1 -0.000384
2022-12-09 16:10:01,539:INFO:modifiedmom:main.py:146:handleKline:185213: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': True, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True}


## /root/FIL/strategy/pyemd/log.txt ----- -----

17518  20221209   154000    154959  1670572199  17215.8  17215.5
2022-12-09 15:50:00,559:INFO:pyemd2:main.py:127:handleKline:185189: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}
127.0.0.1 - - [09/Dec/2022 16:00:00] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=2024 

self.closeSec=1670572799, self.tradeDate='20221209', self.openTime='155000', self.closeTime='155959', self.symbol='BTCUSDT', self.open='17215.5', self.close='17203.7'
2022-12-09 16:00:00,998:INFO:pyemd2:main.py:125:handleKline:185189: self.closeSec=1670572799, self.tradeDate='20221209', self.openTime='155000', self.closeTime='155959',self.symbol='BTCUSDT',self.open='17215.5', self.close='17203.7'
2022-12-09 16:00:01,013:INFO:pyemd2:main.py:126:handleKline:185189: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
17515  20221209   151000    151959  1670570399  17217.2  17209.2
17516  20221209   152000    152959  1670570999  17209.3  17224.1
17517  20221209   153000    153959  1670571599  17224.1  17216.1
17518  20221209   154000    154959  1670572199  17215.8  17215.5
17519  20221209   155000    155959  1670572799  17215.5  17203.7
2022-12-09 16:00:01,014:INFO:pyemd2:main.py:127:handleKline:185189: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=2025 

self.closeSec=1670573399, self.tradeDate='20221209', self.openTime='160000', self.closeTime='160959', self.symbol='BTCUSDT', self.open='17203.7', self.close='17197.1'
2022-12-09 16:10:01,531:INFO:pyemd2:main.py:125:handleKline:185189: self.closeSec=1670573399, self.tradeDate='20221209', self.openTime='160000', self.closeTime='160959',self.symbol='BTCUSDT',self.open='17203.7', self.close='17197.1'
127.0.0.1 - - [09/Dec/2022 16:10:01] "POST / HTTP/1.1" 200 -
2022-12-09 16:10:01,558:INFO:pyemd2:main.py:126:handleKline:185189: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
17516  20221209   152000    152959  1670570999  17209.3  17224.1
17517  20221209   153000    153959  1670571599  17224.1  17216.1
17518  20221209   154000    154959  1670572199  17215.8  17215.5
17519  20221209   155000    155959  1670572799  17215.5  17203.7
17520  20221209   160000    160959  1670573399  17203.7  17197.1
2022-12-09 16:10:01,559:INFO:pyemd2:main.py:127:handleKline:185189: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}


## /root/FIL/strategy/similarity/log.txt ----- -----

12190  20221209   154000    154959  1670572199  17215.8  17215.5
2022-12-09 15:50:00,556:INFO:testStrategy:main.py:103:handleKline:185174: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': True, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True, 'isCorr': False}

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=2024 

self.closeSec=1670572799, self.tradeDate='20221209', self.openTime='155000', self.closeTime='155959', self.symbol='BTCUSDT', self.open='17215.5', self.close='17203.7'
127.0.0.1 - - [09/Dec/2022 16:00:00] "POST / HTTP/1.1" 200 -
2022-12-09 16:00:00,983:INFO:testStrategy:main.py:101:handleKline:185174: self.closeSec=1670572799, self.tradeDate='20221209', self.openTime='155000', self.closeTime='155959',self.symbol='BTCUSDT',self.open='17215.5', self.close='17203.7'
2022-12-09 16:00:00,996:INFO:testStrategy:main.py:102:handleKline:185174: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
12187  20221209   151000    151959  1670570399  17217.2  17209.2
12188  20221209   152000    152959  1670570999  17209.3  17224.1
12189  20221209   153000    153959  1670571599  17224.1  17216.1
12190  20221209   154000    154959  1670572199  17215.8  17215.5
12191  20221209   155000    155959  1670572799  17215.5  17203.7
2022-12-09 16:00:00,996:INFO:testStrategy:main.py:103:handleKline:185174: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': True, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True, 'isCorr': False}
127.0.0.1 - - [09/Dec/2022 16:10:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=2025 

self.closeSec=1670573399, self.tradeDate='20221209', self.openTime='160000', self.closeTime='160959', self.symbol='BTCUSDT', self.open='17203.7', self.close='17197.1'
2022-12-09 16:10:01,524:INFO:testStrategy:main.py:101:handleKline:185174: self.closeSec=1670573399, self.tradeDate='20221209', self.openTime='160000', self.closeTime='160959',self.symbol='BTCUSDT',self.open='17203.7', self.close='17197.1'
2022-12-09 16:10:01,556:INFO:testStrategy:main.py:102:handleKline:185174: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
12188  20221209   152000    152959  1670570999  17209.3  17224.1
12189  20221209   153000    153959  1670571599  17224.1  17216.1
12190  20221209   154000    154959  1670572199  17215.8  17215.5
12191  20221209   155000    155959  1670572799  17215.5  17203.7
12192  20221209   160000    160959  1670573399  17203.7  17197.1
2022-12-09 16:10:01,556:INFO:testStrategy:main.py:103:handleKline:185174: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': True, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True, 'isCorr': False}


## /root/FIL/strategy/s_rsrs/log.txt ----- -----

721  20221209   040000    075959  1670543999  ...    721  0.876128  1.378563     1.0
722  20221209   080000    115959  1670558399  ...    722  0.843817  1.237965     1.0

[5 rows x 15 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '58.622', 'enterprice': '17301.5', 'countrevence': '0', 'unrealprofit': '-6173.02706384722', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '17196.19777449', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'numpy.int64'>, curSign=1, self.sign=1
--handleKline--:  version='2.0.0', self.name='s_rsrs', self.symbol='BTCUSDT', interval='4h', intervalSec=14400, wid=25, thd=0.6, self.sign=1, self.total=1013234.284467, self.flagDict['side']='buy', self.tradeCount=4, self.count=84
self.closeSec=1670572799, self.tradeDate='20221209', self.openTime='120000', self.closeTime='155959', self.symbol='BTCUSDT', self.open=17194.0, self.close=17203.7, self.high=17227.1, self.low=17180.5, self.vol=23221.849, self.amt=399508692.6447 
2022-12-09 16:00:00,846:INFO:s_rsrs:main.py:141:handleKline:185271: self.closeSec=1670572799, self.tradeDate='20221209', self.openTime='120000', self.closeTime='155959',self.symbol='BTCUSDT',self.open=17194.0, self.close=17203.7, self.high=17227.1, self.low=17180.5, self.vol=23221.849, self.amt=399508692.6447 
127.0.0.1 - - [09/Dec/2022 16:00:00] "POST / HTTP/1.1" 200 -
2022-12-09 16:00:00,891:INFO:s_rsrs:main.py:142:handleKline:185271: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime  ...         vol           amt       pct
719  20221208   200000    235959  ...   88430.186  1.491772e+09  0.003907
720  20221209   000000    035959  ...  143901.415  2.463060e+09  0.019766
721  20221209   040000    075959  ...   58532.020  1.007112e+09 -0.001502
722  20221209   080000    115959  ...   42568.695  7.331506e+08 -0.001278
723  20221209   120000    155959  ...   23221.849  3.995087e+08  0.000564

[5 rows x 11 columns]
2022-12-09 16:00:02,480:INFO:s_rsrs:main.py:151:handleKline:185271: df_s.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec  ...  index      beta    zscore  signal
719  20221208   200000    235959  1670515199  ...    719  0.958119  1.745379     1.0
720  20221209   000000    035959  1670529599  ...    720  0.890290  1.460099     1.0
721  20221209   040000    075959  1670543999  ...    721  0.876128  1.378563     1.0
722  20221209   080000    115959  1670558399  ...    722  0.843817  1.237965     1.0
723  20221209   120000    155959  1670572799  ...    723  0.723998  0.798378     1.0

[5 rows x 15 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '58.622', 'enterprice': '17301.5', 'countrevence': '0', 'unrealprofit': '-5708.33750038368', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '17204.12465456', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'numpy.int64'>, curSign=1, self.sign=1


