# 20230525 16:26:01

## /root/FIL/strategy/amihud/log.txt ----- -----

--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=373746.4768026, self.flagDict['side']='sell', self.tradeCount=2, self.count=3232
self.closeSec=1685002799, self.tradeDate='20230525', self.openTime='161500', self.closeTime='161959', self.symbol='BTCUSDT', self.open=26159.6, self.close=26164.2, self.high=26184.7, self.low=26158.0, self.vol=800.524, self.amt=20950622.8489 
127.0.0.1 - - [25/May/2023 16:20:01] "POST / HTTP/1.1" 200 -
2023-05-25 16:20:03,310:INFO:amihud:main.py:172:handleKline:2219019: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5951  20230525   155500    155959  ...    0.096338   0.261346       0
5952  20230525   160000    160459  ...    0.096179   0.261229       0
5953  20230525   160500    160959  ...    0.096021   0.261115       0
5954  20230525   161000    161459  ...    0.095864   0.261003       0
5955  20230525   161500    161959  ...    0.095710   0.260896       0

[5 rows x 18 columns]
2023-05-25 16:20:03,340:INFO:amihud:main.py:175:handleKline:2219019: self.closeSec=1685002799, self.tradeDate='20230525', self.openTime='161500', self.closeTime='161959',self.symbol='BTCUSDT',self.open=26159.6, self.close=26164.2, self.high=26184.7, self.low=26158.0, self.vol=800.524, self.amt=20950622.8489, ukdf['pct'].iloc[-1]=0.000176 , ukdf['amount'].iloc[-1]=20950622.8489, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5955, value=0.0, value_mean=0.09570990850031898, signal=0, value_std=0.26089576106103235 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '13.926', 'enterprice': '26864.9', 'countrevence': '0', 'unrealprofit': '9728.7036', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '26166.3', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1
127.0.0.1 - - [25/May/2023 16:25:00] "POST / HTTP/1.1" 200 -
--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=373746.4768026, self.flagDict['side']='sell', self.tradeCount=2, self.count=3233
self.closeSec=1685003099, self.tradeDate='20230525', self.openTime='162000', self.closeTime='162459', self.symbol='BTCUSDT', self.open=26164.2, self.close=26181.3, self.high=26197.7, self.low=26162.7, self.vol=1405.755, self.amt=36804092.7427 
2023-05-25 16:25:00,884:INFO:amihud:main.py:172:handleKline:2219019: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5952  20230525   160000    160459  ...    0.096179   0.261229       0
5953  20230525   160500    160959  ...    0.096021   0.261115       0
5954  20230525   161000    161459  ...    0.095864   0.261003       0
5955  20230525   161500    161959  ...    0.095710   0.260896       0
5956  20230525   162000    162459  ...    0.095557   0.260790       0

[5 rows x 18 columns]
2023-05-25 16:25:00,884:INFO:amihud:main.py:175:handleKline:2219019: self.closeSec=1685003099, self.tradeDate='20230525', self.openTime='162000', self.closeTime='162459',self.symbol='BTCUSDT',self.open=26164.2, self.close=26181.3, self.high=26197.7, self.low=26162.7, self.vol=1405.755, self.amt=36804092.7427, ukdf['pct'].iloc[-1]=0.000654 , ukdf['amount'].iloc[-1]=36804092.7427, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5956, value=0.0, value_mean=0.09555675813305609, signal=0, value_std=0.2607900545915841 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '13.926', 'enterprice': '26864.9', 'countrevence': '0', 'unrealprofit': '9458.18281597398', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '26185.72559127', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1


## /root/FIL/strategy/factorcheck/log.txt ----- -----


self.closeSec=1685002799, self.tradeDate='20230525', self.openTime='161500', self.closeTime='161959', self.symbol='BTCUSDT', self.open=26159.6, self.close=26164.2, self.high=26184.7, self.low=26158.0 
127.0.0.1 - - [25/May/2023 16:20:01] "POST / HTTP/1.1" 200 -
2023-05-25 16:20:01,410:INFO:factorcheck2:main.py:126:handleKline:2218005: self.closeSec=1685002799, self.tradeDate='20230525', self.openTime='161500', self.closeTime='161959',self.symbol='BTCUSDT',self.open=26159.6, self.close=26164.2, self.high=26184.7, self.low=26158.0   
2023-05-25 16:20:02,390:INFO:factorcheck2:main.py:127:handleKline:2218005: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime    closeSec  ...      low       pct  index  idx
1631  20230525   155500    155959  1685001599  ...  26111.0 -0.000425   1631    5
1632  20230525   160000    160459  1685001899  ...  26107.8  0.001386   1632    0
1633  20230525   160500    160959  1685002199  ...  26155.0  0.000956   1633    1
1634  20230525   161000    161459  1685002499  ...  26159.6 -0.000779   1634    2
1635  20230525   161500    161959  1685002799  ...  26158.0  0.000176   1635    3

[5 rows x 11 columns]
2023-05-25 16:20:02,400:INFO:factorcheck2:main.py:128:handleKline:2218005: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': True, 'isOpenSell': False, 'isCloseBuy': False, 'isCloseSell': False, 'isOpen': True, 'isClose': False, 'isTrig': True}
127.0.0.1 - - [25/May/2023 16:25:00] "POST / HTTP/1.1" 200 -

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=0, self.factor=0.7144210341330298, self.count=3235 

self.closeSec=1685003099, self.tradeDate='20230525', self.openTime='162000', self.closeTime='162459', self.symbol='BTCUSDT', self.open=26164.2, self.close=26181.3, self.high=26197.7, self.low=26162.7 
2023-05-25 16:25:00,778:INFO:factorcheck2:main.py:126:handleKline:2218005: self.closeSec=1685003099, self.tradeDate='20230525', self.openTime='162000', self.closeTime='162459',self.symbol='BTCUSDT',self.open=26164.2, self.close=26181.3, self.high=26197.7, self.low=26162.7   
2023-05-25 16:25:00,866:INFO:factorcheck2:main.py:127:handleKline:2218005: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime    closeSec  ...      low       pct  index  idx
1632  20230525   160000    160459  1685001899  ...  26107.8  0.001386   1632    0
1633  20230525   160500    160959  1685002199  ...  26155.0  0.000956   1633    1
1634  20230525   161000    161459  1685002499  ...  26159.6 -0.000779   1634    2
1635  20230525   161500    161959  1685002799  ...  26158.0  0.000176   1635    3
1636  20230525   162000    162459  1685003099  ...  26162.7  0.000654   1636    4

[5 rows x 11 columns]
2023-05-25 16:25:00,866:INFO:factorcheck2:main.py:128:handleKline:2218005: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': True, 'isOpenSell': False, 'isCloseBuy': False, 'isCloseSell': False, 'isOpen': True, 'isClose': False, 'isTrig': True}


## /root/FIL/strategy/logic/log.txt ----- -----

2023-05-25 16:00:34,658:DEBUG:logic:main.py:463:getModel:2218526: df_s.iloc[-5:,:] :
          date closeTime     open  ...    alpha58   alpha67   alpha72
5786  20230525    132959  26212.8  ...  46.250000  0.421522  0.728985
5787  20230525    135959  26262.9  ...  45.833333  0.419402  0.717571
5788  20230525    142959  26251.2  ...  45.833333  0.417936  0.707506
5789  20230525    145959  26243.0  ...  46.250000  0.420546  0.697369
5790  20230525    152959  26253.2  ...  46.250000  0.408553  0.692056

[5 rows x 33 columns]
0.533210332103321
acc is : 0.533210332103321
2023-05-25 16:00:34,817:INFO:logic:main.py:468:getModel:2218526: df_pred.iloc[-5:,:] :
     pred    prob_0    prob_1  actual  ...       nav  sign  cost_        bm
537     0  0.528646  0.471354       0  ...  0.916613  -1.0    0.0  0.982032
538     0  0.509392  0.490608       0  ...  0.916892  -1.0    0.0  0.981733
539     0  0.511625  0.488375       1  ...  0.916540  -1.0    0.0  0.982111
540     0  0.513030  0.486970       0  ...  0.918802  -1.0    0.0  0.979687
541     1  0.491741  0.508259       0  ...  0.921240  -1.0    0.0  0.977087

[5 rows x 10 columns]
2023-05-25 16:00:34,856:INFO:logic:main.py:478:getModel:2218526: df_panel.iloc[-5:,:] :
    pred    prob_0    prob_1  actual  ...       nav  sign  cost_        bm
45     0  0.528670  0.471330       0  ...  0.916613  -1.0    0.0  0.976632
46     0  0.509677  0.490323       0  ...  0.916892  -1.0    0.0  0.976517
47     0  0.511591  0.488409       1  ...  0.916540  -1.0    0.0  0.980962
48     0  0.513013  0.486987       0  ...  0.918802  -1.0    0.0  0.978263
49     1  0.491741  0.508259       0  ...  0.921240  -1.0    0.0  0.977087

[5 rows x 10 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '27.287', 'enterprice': '26103', 'countrevence': '0', 'unrealprofit': '-769.4934', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '26131.2', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}


## /root/FIL/strategy/modifiedmom/log.txt ----- -----

527  20230525   155000    155959  1685001599  26152.5  26118.9 -0.001289
2023-05-25 16:00:02,406:INFO:modifiedmom:main.py:146:handleKline:2218259: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': True, 'isOpenSell': False, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True}
127.0.0.1 - - [25/May/2023 16:10:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=1616 

self.closeSec=1685002199, self.tradeDate='20230525', self.openTime='160000', self.closeTime='160959', self.symbol='BTCUSDT', self.open='26118.9', self.close='26180'
2023-05-25 16:10:01,129:INFO:modifiedmom:main.py:144:handleKline:2218259: self.closeSec=1685002199, self.tradeDate='20230525', self.openTime='160000', self.closeTime='160959',self.symbol='BTCUSDT',self.open='26118.9', self.close='26180'
2023-05-25 16:10:01,154:INFO:modifiedmom:main.py:145:handleKline:2218259: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec     open    close       pct
524  20230525   152000    152959  1684999799  26220.9  26188.4 -0.001239
525  20230525   153000    153959  1685000399  26188.4  26123.1 -0.002493
526  20230525   154000    154959  1685000999  26123.2  26152.6  0.001129
527  20230525   155000    155959  1685001599  26152.5  26118.9 -0.001289
528  20230525   160000    160959  1685002199  26118.9    26180  0.002339
2023-05-25 16:10:01,155:INFO:modifiedmom:main.py:146:handleKline:2218259: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': True, 'isOpenSell': False, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True}

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=1617 

self.closeSec=1685002799, self.tradeDate='20230525', self.openTime='161000', self.closeTime='161959', self.symbol='BTCUSDT', self.open='26180.1', self.close='26164.1'
127.0.0.1 - - [25/May/2023 16:20:02] "POST / HTTP/1.1" 200 -
2023-05-25 16:20:04,510:INFO:modifiedmom:main.py:144:handleKline:2218259: self.closeSec=1685002799, self.tradeDate='20230525', self.openTime='161000', self.closeTime='161959',self.symbol='BTCUSDT',self.open='26180.1', self.close='26164.1'
2023-05-25 16:20:04,991:INFO:modifiedmom:main.py:145:handleKline:2218259: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec     open    close       pct
525  20230525   153000    153959  1685000399  26188.4  26123.1 -0.002493
526  20230525   154000    154959  1685000999  26123.2  26152.6  0.001129
527  20230525   155000    155959  1685001599  26152.5  26118.9 -0.001289
528  20230525   160000    160959  1685002199  26118.9    26180  0.002339
529  20230525   161000    161959  1685002799  26180.1  26164.1 -0.000607
2023-05-25 16:20:05,000:INFO:modifiedmom:main.py:146:handleKline:2218259: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': True, 'isOpenSell': False, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True}


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

17519  20230525   155000    155959  1685001599  26152.5  26118.9
2023-05-25 16:00:02,421:INFO:pyemd2:main.py:127:handleKline:2217508: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=1619 

self.closeSec=1685002199, self.tradeDate='20230525', self.openTime='160000', self.closeTime='160959', self.symbol='BTCUSDT', self.open='26118.9', self.close='26180'
2023-05-25 16:10:01,142:INFO:pyemd2:main.py:125:handleKline:2217508: self.closeSec=1685002199, self.tradeDate='20230525', self.openTime='160000', self.closeTime='160959',self.symbol='BTCUSDT',self.open='26118.9', self.close='26180'
127.0.0.1 - - [25/May/2023 16:10:01] "POST / HTTP/1.1" 200 -
2023-05-25 16:10:01,161:INFO:pyemd2:main.py:126:handleKline:2217508: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
17516  20230525   152000    152959  1684999799  26220.9  26188.4
17517  20230525   153000    153959  1685000399  26188.4  26123.1
17518  20230525   154000    154959  1685000999  26123.2  26152.6
17519  20230525   155000    155959  1685001599  26152.5  26118.9
17520  20230525   160000    160959  1685002199  26118.9    26180
2023-05-25 16:10:01,161:INFO:pyemd2:main.py:127:handleKline:2217508: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=1620 

self.closeSec=1685002799, self.tradeDate='20230525', self.openTime='161000', self.closeTime='161959', self.symbol='BTCUSDT', self.open='26180.1', self.close='26164.1'
127.0.0.1 - - [25/May/2023 16:20:02] "POST / HTTP/1.1" 200 -
2023-05-25 16:20:05,805:INFO:pyemd2:main.py:125:handleKline:2217508: self.closeSec=1685002799, self.tradeDate='20230525', self.openTime='161000', self.closeTime='161959',self.symbol='BTCUSDT',self.open='26180.1', self.close='26164.1'
2023-05-25 16:20:05,924:INFO:pyemd2:main.py:126:handleKline:2217508: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
17517  20230525   153000    153959  1685000399  26188.4  26123.1
17518  20230525   154000    154959  1685000999  26123.2  26152.6
17519  20230525   155000    155959  1685001599  26152.5  26118.9
17520  20230525   160000    160959  1685002199  26118.9    26180
17521  20230525   161000    161959  1685002799  26180.1  26164.1
2023-05-25 16:20:05,925:INFO:pyemd2:main.py:127:handleKline:2217508: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}


## /root/FIL/strategy/similarity/log.txt ----- -----

12191  20230525   155000    155959  1685001599  26152.5  26118.9
2023-05-25 16:00:02,413:INFO:testStrategy:main.py:103:handleKline:2217133: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': True, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True, 'isCorr': False}
127.0.0.1 - - [25/May/2023 16:10:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=1619 

self.closeSec=1685002199, self.tradeDate='20230525', self.openTime='160000', self.closeTime='160959', self.symbol='BTCUSDT', self.open='26118.9', self.close='26180'
2023-05-25 16:10:01,151:INFO:testStrategy:main.py:101:handleKline:2217133: self.closeSec=1685002199, self.tradeDate='20230525', self.openTime='160000', self.closeTime='160959',self.symbol='BTCUSDT',self.open='26118.9', self.close='26180'
2023-05-25 16:10:01,182:INFO:testStrategy:main.py:102:handleKline:2217133: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
12188  20230525   152000    152959  1684999799  26220.9  26188.4
12189  20230525   153000    153959  1685000399  26188.4  26123.1
12190  20230525   154000    154959  1685000999  26123.2  26152.6
12191  20230525   155000    155959  1685001599  26152.5  26118.9
12192  20230525   160000    160959  1685002199  26118.9    26180
2023-05-25 16:10:01,182:INFO:testStrategy:main.py:103:handleKline:2217133: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': True, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True, 'isCorr': False}

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=1620 

self.closeSec=1685002799, self.tradeDate='20230525', self.openTime='161000', self.closeTime='161959', self.symbol='BTCUSDT', self.open='26180.1', self.close='26164.1'
127.0.0.1 - - [25/May/2023 16:20:02] "POST / HTTP/1.1" 200 -
2023-05-25 16:20:05,462:INFO:testStrategy:main.py:101:handleKline:2217133: self.closeSec=1685002799, self.tradeDate='20230525', self.openTime='161000', self.closeTime='161959',self.symbol='BTCUSDT',self.open='26180.1', self.close='26164.1'
2023-05-25 16:20:05,725:INFO:testStrategy:main.py:102:handleKline:2217133: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
12189  20230525   153000    153959  1685000399  26188.4  26123.1
12190  20230525   154000    154959  1685000999  26123.2  26152.6
12191  20230525   155000    155959  1685001599  26152.5  26118.9
12192  20230525   160000    160959  1685002199  26118.9    26180
12193  20230525   161000    161959  1685002799  26180.1  26164.1
2023-05-25 16:20:05,729:INFO:testStrategy:main.py:103:handleKline:2217133: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': True, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True, 'isCorr': False}


## /root/FIL/strategy/sr_min/log.txt ----- -----

--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=1, self.total=996015.990996, self.flagDict['side']='buy', self.tradeCount=1, self.count=3232
self.closeSec=1685002799, self.tradeDate='20230525', self.openTime='161500', self.closeTime='161959', self.symbol='BTCUSDT', self.open=26159.6, self.close=26164.2, self.high=26184.7, self.low=26158.0, self.vol=800.524, self.amt=20950622.8489 
127.0.0.1 - - [25/May/2023 16:20:01] "POST / HTTP/1.1" 200 -
2023-05-25 16:20:03,569:INFO:sr_min:main.py:172:handleKline:2219263: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5951  20230525   155500    155959  ...         0.0        0.0       0
5952  20230525   160000    160459  ...         0.0        0.0       0
5953  20230525   160500    160959  ...         0.0        0.0       0
5954  20230525   161000    161459  ...         0.0        0.0       0
5955  20230525   161500    161959  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-05-25 16:20:03,590:INFO:sr_min:main.py:175:handleKline:2219263: self.closeSec=1685002799, self.tradeDate='20230525', self.openTime='161500', self.closeTime='161959',self.symbol='BTCUSDT',self.open=26159.6, self.close=26164.2, self.high=26184.7, self.low=26158.0, self.vol=800.524, self.amt=20950622.8489, ukdf['pct'].iloc[-1]=0.000176 , ukdf['amount'].iloc[-1]=20950622.8489, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5955, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '37.141', 'enterprice': '26844', 'countrevence': '0', 'unrealprofit': '-25170.4557', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '26166.3', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=1
--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=1, self.total=996015.990996, self.flagDict['side']='buy', self.tradeCount=1, self.count=3233
self.closeSec=1685003099, self.tradeDate='20230525', self.openTime='162000', self.closeTime='162459', self.symbol='BTCUSDT', self.open=26164.2, self.close=26181.3, self.high=26197.7, self.low=26162.7, self.vol=1405.755, self.amt=36804092.7427 
127.0.0.1 - - [25/May/2023 16:25:00] "POST / HTTP/1.1" 200 -
2023-05-25 16:25:00,911:INFO:sr_min:main.py:172:handleKline:2219263: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5952  20230525   160000    160459  ...         0.0        0.0       0
5953  20230525   160500    160959  ...         0.0        0.0       0
5954  20230525   161000    161459  ...         0.0        0.0       0
5955  20230525   161500    161959  ...         0.0        0.0       0
5956  20230525   162000    162459  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-05-25 16:25:00,914:INFO:sr_min:main.py:175:handleKline:2219263: self.closeSec=1685003099, self.tradeDate='20230525', self.openTime='162000', self.closeTime='162459',self.symbol='BTCUSDT',self.open=26164.2, self.close=26181.3, self.high=26197.7, self.low=26162.7, self.vol=1405.755, self.amt=36804092.7427, ukdf['pct'].iloc[-1]=0.000654 , ukdf['amount'].iloc[-1]=36804092.7427, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5956, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '37.141', 'enterprice': '26844', 'countrevence': '0', 'unrealprofit': '-24448.96981464093', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '26185.72559127', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=1


## /root/FIL/strategy/s_rsrs/log.txt ----- -----

720  20230525   000000    035959  ...   69968.498  1.837039e+09 -0.002482
721  20230525   040000    075959  ...   50565.341  1.333426e+09  0.002751
722  20230525   080000    115959  ...   94944.153  2.478461e+09 -0.005427
723  20230525   120000    155959  ...   40575.044  1.063439e+09 -0.001991

[5 rows x 11 columns]
2023-05-25 16:00:03,982:INFO:s_rsrs:main.py:151:handleKline:2218689: df_s.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec  ...  index      beta    zscore  signal
719  20230524   200000    235959  1684943999  ...    719  0.282606 -0.560483     NaN
720  20230525   000000    035959  1684958399  ...    720  0.402509  0.062808     NaN
721  20230525   040000    075959  1684972799  ...    721  0.463025  0.405514     NaN
722  20230525   080000    115959  1684987199  ...    722  0.467197  0.467010     NaN
723  20230525   120000    155959  1685001599  ...    723  0.521366  0.807871     1.0

[5 rows x 15 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '51.549', 'enterprice': '27070.5', 'countrevence': '0', 'unrealprofit': '48847.8324', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '26122.9', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'numpy.int64'>, curSign=1, self.sign=-1
handlebackTrade > queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '51.549', 'enterprice': '27070.5', 'countrevence': '0', 'unrealprofit': '48847.8324', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '26122.9', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
2023-05-25 16:00:10,892:INFO:s_rsrs:main.py:182:queryContractAssets:2218689: queryContractAssets: assets=ContractAssetReturn{'result': [ContractAsset{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'asset': 'USDT', 'free': '1447404.3953126', 'total': '1447404.3953126', 'margin': '0', 'unreal': '0', 'type': 'AssetType_ucontract'}]}
2023-05-25 16:00:11,453:DEBUG:s_rsrs:main.py:253:openBuy:2218689: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': True, 'isOpenSell': True, 'isCloseBuy': False, 'isCloseSell': False, 'isOpen': True, 'isClose': False, 'isTrig': False}
2023-05-25 16:00:11,453:INFO:s_rsrs:main.py:254:openBuy:2218689: ret = self.client.insertMarketUOrder("simulator", "BTCUSDT", 55.249, "buy"), ret=InsertOrderReturn{'result': 'success', 'clientorderid': '42260F1685001611451I0L65'}
2023-05-25 16:00:11,468:INFO:s_rsrs:main.py:176:insertFactor:2218689: curDateTime:5251600, name:s_rsrs, symbol:BTCUSDT, tradeDate:20230525, closeTime:155959, close:26118.9, sign:1, total:1447404.3953126, side:buy  
127.0.0.1 - - [25/May/2023 16:00:11] "POST / HTTP/1.1" 200 -
127.0.0.1 - - [25/May/2023 16:00:11] "POST / HTTP/1.1" 200 -
2023-05-25 16:00:11,471:INFO:s_rsrs:main.py:343:handleOrderNew:2218689: handleOrderNew: data=OrderType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'clientorderid': '42259F1685001605807I0L65', 'symbol': 'BTCUSDT', 'gatewayorderid': 1685001606254045, 'quantity': '51.549', 'price': '26123', 'stopprice': '0', 'ordertype': '', 'side': 'BUY', 'status': 'FILLED', 'positionside': 'LONG', 'createtime': 1685001604932, 'updatetime': 1685001606254, 'tradetype': 'usdt', 'selfid': 42259, 'filltrades': [TradeType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'tradeid': 1685001606254, 'clientorderid': '42259F1685001605807I0L65', 'price': '26123', 'quantity': '51.549', 'commission': '1346.614527', 'commissionasset': 'USDT', 'tradetime': 1685001606254, 'tradetype': 'usdt', 'gatetype': 'simulator', 'handletime': 1685001606254}], 'gatetype': 'simulator', 'handletime': 0}
2023-05-25 16:00:11,471:INFO:s_rsrs:main.py:346:handleOrderFilled:2218689: handleOrderFilled: data=OrderType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'clientorderid': '42259F1685001605807I0L65', 'symbol': 'BTCUSDT', 'gatewayorderid': 1685001606254045, 'quantity': '51.549', 'price': '26123', 'stopprice': '0', 'ordertype': '', 'side': 'BUY', 'status': 'FILLED', 'positionside': 'LONG', 'createtime': 1685001604932, 'updatetime': 1685001606254, 'tradetype': 'usdt', 'selfid': 42259, 'filltrades': [TradeType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'tradeid': 1685001606254, 'clientorderid': '42259F1685001605807I0L65', 'price': '26123', 'quantity': '51.549', 'commission': '1346.614527', 'commissionasset': 'USDT', 'tradetime': 1685001606254, 'tradetype': 'usdt', 'gatetype': 'simulator', 'handletime': 1685001606254}], 'gatetype': 'simulator', 'handletime': 0}
127.0.0.1 - - [25/May/2023 16:00:11] "POST / HTTP/1.1" 200 -
2023-05-25 16:00:11,923:INFO:s_rsrs:main.py:343:handleOrderNew:2218689: handleOrderNew: data=OrderType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'clientorderid': '42260F1685001611451I0L65', 'symbol': 'BTCUSDT', 'gatewayorderid': 1685001611894994, 'quantity': '55.249', 'price': '26128.2', 'stopprice': '0', 'ordertype': '', 'side': 'BUY', 'status': 'FILLED', 'positionside': 'LONG', 'createtime': 1685001610906, 'updatetime': 1685001611894, 'tradetype': 'usdt', 'selfid': 42260, 'filltrades': [TradeType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'tradeid': 1685001611894, 'clientorderid': '42260F1685001611451I0L65', 'price': '26128.2', 'quantity': '55.249', 'commission': '1443.5569218', 'commissionasset': 'USDT', 'tradetime': 1685001611894, 'tradetype': 'usdt', 'gatetype': 'simulator', 'handletime': 1685001611894}], 'gatetype': 'simulator', 'handletime': 0}
127.0.0.1 - - [25/May/2023 16:00:12] "POST / HTTP/1.1" 200 -
2023-05-25 16:00:12,106:INFO:s_rsrs:main.py:346:handleOrderFilled:2218689: handleOrderFilled: data=OrderType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'clientorderid': '42260F1685001611451I0L65', 'symbol': 'BTCUSDT', 'gatewayorderid': 1685001611894994, 'quantity': '55.249', 'price': '26128.2', 'stopprice': '0', 'ordertype': '', 'side': 'BUY', 'status': 'FILLED', 'positionside': 'LONG', 'createtime': 1685001610906, 'updatetime': 1685001611894, 'tradetype': 'usdt', 'selfid': 42260, 'filltrades': [TradeType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'tradeid': 1685001611894, 'clientorderid': '42260F1685001611451I0L65', 'price': '26128.2', 'quantity': '55.249', 'commission': '1443.5569218', 'commissionasset': 'USDT', 'tradetime': 1685001611894, 'tradetype': 'usdt', 'gatetype': 'simulator', 'handletime': 1685001611894}], 'gatetype': 'simulator', 'handletime': 0}


