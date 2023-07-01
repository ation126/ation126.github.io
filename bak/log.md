# 20230701 16:26:01

## /root/FIL/strategy/amihud/log.txt ----- -----

--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=373746.4768026, self.flagDict['side']='sell', self.tradeCount=2, self.count=13888
self.closeSec=1688199599, self.tradeDate='20230701', self.openTime='161500', self.closeTime='161959', self.symbol='BTCUSDT', self.open=30436.0, self.close=30423.1, self.high=30439.6, self.low=30423.0, self.vol=200.452, self.amt=6099869.0294 
127.0.0.1 - - [01/Jul/2023 16:20:02] "POST / HTTP/1.1" 200 -
2023-07-01 16:20:08,077:INFO:amihud:main.py:172:handleKline:2219019: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5951  20230701   155500    155959  ...         0.0        0.0       0
5952  20230701   160000    160459  ...         0.0        0.0       0
5953  20230701   160500    160959  ...         0.0        0.0       0
5954  20230701   161000    161459  ...         0.0        0.0       0
5955  20230701   161500    161959  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-07-01 16:20:08,108:INFO:amihud:main.py:175:handleKline:2219019: self.closeSec=1688199599, self.tradeDate='20230701', self.openTime='161500', self.closeTime='161959',self.symbol='BTCUSDT',self.open=30436.0, self.close=30423.1, self.high=30439.6, self.low=30423.0, self.vol=200.452, self.amt=6099869.0294, ukdf['pct'].iloc[-1]=-0.000424 , ukdf['amount'].iloc[-1]=6099869.0294, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5955, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '13.926', 'enterprice': '26864.9', 'countrevence': '0', 'unrealprofit': '-49643.4048', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '30429.7', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1
127.0.0.1 - - [01/Jul/2023 16:25:00] "POST / HTTP/1.1" 200 -
--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=373746.4768026, self.flagDict['side']='sell', self.tradeCount=2, self.count=13889
self.closeSec=1688199899, self.tradeDate='20230701', self.openTime='162000', self.closeTime='162459', self.symbol='BTCUSDT', self.open=30423.0, self.close=30438.0, self.high=30439.4, self.low=30423.0, self.vol=148.813, self.amt=4528795.2841 
2023-07-01 16:25:00,836:INFO:amihud:main.py:172:handleKline:2219019: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5952  20230701   160000    160459  ...         0.0        0.0       0
5953  20230701   160500    160959  ...         0.0        0.0       0
5954  20230701   161000    161459  ...         0.0        0.0       0
5955  20230701   161500    161959  ...         0.0        0.0       0
5956  20230701   162000    162459  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-07-01 16:25:00,838:INFO:amihud:main.py:175:handleKline:2219019: self.closeSec=1688199899, self.tradeDate='20230701', self.openTime='162000', self.closeTime='162459',self.symbol='BTCUSDT',self.open=30423.0, self.close=30438.0, self.high=30439.4, self.low=30423.0, self.vol=148.813, self.amt=4528795.2841, ukdf['pct'].iloc[-1]=0.00049 , ukdf['amount'].iloc[-1]=4528795.2841, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5956, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '13.926', 'enterprice': '26864.9', 'countrevence': '0', 'unrealprofit': '-49763.59404415146', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '30438.33056471', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1


## /root/FIL/strategy/factorcheck/log.txt ----- -----


self.closeSec=1688199599, self.tradeDate='20230701', self.openTime='161500', self.closeTime='161959', self.symbol='BTCUSDT', self.open=30436.0, self.close=30423.1, self.high=30439.6, self.low=30423.0 
127.0.0.1 - - [01/Jul/2023 16:20:02] "POST / HTTP/1.1" 200 -
2023-07-01 16:20:05,566:INFO:factorcheck2:main.py:126:handleKline:2218005: self.closeSec=1688199599, self.tradeDate='20230701', self.openTime='161500', self.closeTime='161959',self.symbol='BTCUSDT',self.open=30436.0, self.close=30423.1, self.high=30439.6, self.low=30423.0   
2023-07-01 16:20:07,096:INFO:factorcheck2:main.py:127:handleKline:2218005: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime    closeSec  ...      low       pct  index  idx
1631  20230701   155500    155959  1688198399  ...  30434.0  0.000463   1631    5
1632  20230701   160000    160459  1688198699  ...  30439.0  0.000263   1632    0
1633  20230701   160500    160959  1688198999  ...  30444.0 -0.000338   1633    1
1634  20230701   161000    161459  1688199299  ...  30431.4 -0.000322   1634    2
1635  20230701   161500    161959  1688199599  ...  30423.0 -0.000424   1635    3

[5 rows x 11 columns]
2023-07-01 16:20:07,107:INFO:factorcheck2:main.py:128:handleKline:2218005: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=46, self.factor=0.498939643369892, self.count=13891 

self.closeSec=1688199899, self.tradeDate='20230701', self.openTime='162000', self.closeTime='162459', self.symbol='BTCUSDT', self.open=30423.0, self.close=30438.0, self.high=30439.4, self.low=30423.0 
127.0.0.1 - - [01/Jul/2023 16:25:00] "POST / HTTP/1.1" 200 -
2023-07-01 16:25:00,750:INFO:factorcheck2:main.py:126:handleKline:2218005: self.closeSec=1688199899, self.tradeDate='20230701', self.openTime='162000', self.closeTime='162459',self.symbol='BTCUSDT',self.open=30423.0, self.close=30438.0, self.high=30439.4, self.low=30423.0   
2023-07-01 16:25:00,810:INFO:factorcheck2:main.py:127:handleKline:2218005: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime    closeSec  ...      low       pct  index  idx
1632  20230701   160000    160459  1688198699  ...  30439.0  0.000263   1632    0
1633  20230701   160500    160959  1688198999  ...  30444.0 -0.000338   1633    1
1634  20230701   161000    161459  1688199299  ...  30431.4 -0.000322   1634    2
1635  20230701   161500    161959  1688199599  ...  30423.0 -0.000424   1635    3
1636  20230701   162000    162459  1688199899  ...  30423.0  0.000490   1636    4

[5 rows x 11 columns]
2023-07-01 16:25:00,810:INFO:factorcheck2:main.py:128:handleKline:2218005: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}


## /root/FIL/strategy/logic/log.txt ----- -----

2023-07-01 16:00:18,442:DEBUG:logic:main.py:463:getModel:2218526: df_s.iloc[-5:,:] :
          date closeTime     open  ...    alpha58   alpha67   alpha72
5786  20230701    132959  30381.3  ...  52.500000  0.487061  0.462982
5787  20230701    135959  30385.4  ...  52.916667  0.491716  0.461289
5788  20230701    142959  30415.3  ...  52.500000  0.491471  0.459775
5789  20230701    145959  30413.6  ...  52.500000  0.495944  0.457219
5790  20230701    152959  30441.4  ...  52.500000  0.491971  0.455862

[5 rows x 33 columns]
0.5129151291512916
acc is : 0.5129151291512916
2023-07-01 16:00:18,524:INFO:logic:main.py:468:getModel:2218526: df_pred.iloc[-5:,:] :
     pred    prob_0    prob_1  actual  ...       nav  sign  cost_        bm
537     0  0.516607  0.483393       1  ...  1.076715   1.0    0.0  1.127683
538     0  0.522917  0.477083       0  ...  1.076658   1.0    0.0  1.127624
539     0  0.518457  0.481543       1  ...  1.077646   1.0    0.0  1.128659
540     0  0.528597  0.471403       0  ...  1.076757   1.0    0.0  1.127728
541     0  0.517618  0.482382       1  ...  1.077879   1.0    0.0  1.128903

[5 rows x 10 columns]
2023-07-01 16:00:18,536:INFO:logic:main.py:478:getModel:2218526: df_panel.iloc[-5:,:] :
    pred    prob_0    prob_1  actual  ...       nav  sign  cost_        bm
45     0  0.516540  0.483460       1  ...  1.076715   1.0    0.0  1.137289
46     0  0.522758  0.477242       0  ...  1.076658   1.0    0.0  1.136294
47     0  0.518307  0.481693       1  ...  1.077646   1.0    0.0  1.134666
48     0  0.528696  0.471304       0  ...  1.076757   1.0    0.0  1.130255
49     0  0.517618  0.482382       1  ...  1.077879   1.0    0.0  1.128903

[5 rows x 10 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '25.53', 'enterprice': '30560', 'countrevence': '0', 'unrealprofit': '-2792.982', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '30450.6', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}


## /root/FIL/strategy/modifiedmom/log.txt ----- -----

527  20230701   155000    155959  1688198399  30433.7  30448.1  0.000473
2023-07-01 16:00:02,039:INFO:modifiedmom:main.py:146:handleKline:2218259: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': True, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True}
127.0.0.1 - - [01/Jul/2023 16:10:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=6944 

self.closeSec=1688198999, self.tradeDate='20230701', self.openTime='160000', self.closeTime='160959', self.symbol='BTCUSDT', self.open='30448.1', self.close='30445.8'
2023-07-01 16:10:01,077:INFO:modifiedmom:main.py:144:handleKline:2218259: self.closeSec=1688198999, self.tradeDate='20230701', self.openTime='160000', self.closeTime='160959',self.symbol='BTCUSDT',self.open='30448.1', self.close='30445.8'
2023-07-01 16:10:01,088:INFO:modifiedmom:main.py:145:handleKline:2218259: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec     open    close       pct
524  20230701   152000    152959  1688196599  30404.4  30416.4  0.000398
525  20230701   153000    153959  1688197199  30416.4  30427.1  0.000352
526  20230701   154000    154959  1688197799  30427.1  30433.7  0.000217
527  20230701   155000    155959  1688198399  30433.7  30448.1  0.000473
528  20230701   160000    160959  1688198999  30448.1  30445.8 -0.000076
2023-07-01 16:10:01,089:INFO:modifiedmom:main.py:146:handleKline:2218259: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': True, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True}

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=6945 

self.closeSec=1688199599, self.tradeDate='20230701', self.openTime='161000', self.closeTime='161959', self.symbol='BTCUSDT', self.open='30445.8', self.close='30423.1'
127.0.0.1 - - [01/Jul/2023 16:20:04] "POST / HTTP/1.1" 200 -
2023-07-01 16:20:07,828:INFO:modifiedmom:main.py:144:handleKline:2218259: self.closeSec=1688199599, self.tradeDate='20230701', self.openTime='161000', self.closeTime='161959',self.symbol='BTCUSDT',self.open='30445.8', self.close='30423.1'
2023-07-01 16:20:08,647:INFO:modifiedmom:main.py:145:handleKline:2218259: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec     open    close       pct
525  20230701   153000    153959  1688197199  30416.4  30427.1  0.000352
526  20230701   154000    154959  1688197799  30427.1  30433.7  0.000217
527  20230701   155000    155959  1688198399  30433.7  30448.1  0.000473
528  20230701   160000    160959  1688198999  30448.1  30445.8 -0.000076
529  20230701   161000    161959  1688199599  30445.8  30423.1 -0.000746
2023-07-01 16:20:08,657:INFO:modifiedmom:main.py:146:handleKline:2218259: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': True, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True}


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

17519  20230701   155000    155959  1688198399  30433.7  30448.1
2023-07-01 16:00:02,088:INFO:pyemd2:main.py:127:handleKline:2217508: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}
127.0.0.1 - - [01/Jul/2023 16:10:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=6947 

self.closeSec=1688198999, self.tradeDate='20230701', self.openTime='160000', self.closeTime='160959', self.symbol='BTCUSDT', self.open='30448.1', self.close='30445.8'
2023-07-01 16:10:01,102:INFO:pyemd2:main.py:125:handleKline:2217508: self.closeSec=1688198999, self.tradeDate='20230701', self.openTime='160000', self.closeTime='160959',self.symbol='BTCUSDT',self.open='30448.1', self.close='30445.8'
2023-07-01 16:10:01,112:INFO:pyemd2:main.py:126:handleKline:2217508: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
17516  20230701   152000    152959  1688196599  30404.4  30416.4
17517  20230701   153000    153959  1688197199  30416.4  30427.1
17518  20230701   154000    154959  1688197799  30427.1  30433.7
17519  20230701   155000    155959  1688198399  30433.7  30448.1
17520  20230701   160000    160959  1688198999  30448.1  30445.8
2023-07-01 16:10:01,113:INFO:pyemd2:main.py:127:handleKline:2217508: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=6948 

self.closeSec=1688199599, self.tradeDate='20230701', self.openTime='161000', self.closeTime='161959', self.symbol='BTCUSDT', self.open='30445.8', self.close='30423.1'
127.0.0.1 - - [01/Jul/2023 16:20:05] "POST / HTTP/1.1" 200 -
2023-07-01 16:20:10,287:INFO:pyemd2:main.py:125:handleKline:2217508: self.closeSec=1688199599, self.tradeDate='20230701', self.openTime='161000', self.closeTime='161959',self.symbol='BTCUSDT',self.open='30445.8', self.close='30423.1'
2023-07-01 16:20:10,426:INFO:pyemd2:main.py:126:handleKline:2217508: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
17517  20230701   153000    153959  1688197199  30416.4  30427.1
17518  20230701   154000    154959  1688197799  30427.1  30433.7
17519  20230701   155000    155959  1688198399  30433.7  30448.1
17520  20230701   160000    160959  1688198999  30448.1  30445.8
17521  20230701   161000    161959  1688199599  30445.8  30423.1
2023-07-01 16:20:10,427:INFO:pyemd2:main.py:127:handleKline:2217508: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}


## /root/FIL/strategy/similarity/log.txt ----- -----

12191  20230701   155000    155959  1688198399  30433.7  30448.1
2023-07-01 16:00:02,090:INFO:testStrategy:main.py:103:handleKline:2217133: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': True, 'isOpenSell': False, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True, 'isCorr': False}
127.0.0.1 - - [01/Jul/2023 16:10:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=6947 

self.closeSec=1688198999, self.tradeDate='20230701', self.openTime='160000', self.closeTime='160959', self.symbol='BTCUSDT', self.open='30448.1', self.close='30445.8'
2023-07-01 16:10:01,090:INFO:testStrategy:main.py:101:handleKline:2217133: self.closeSec=1688198999, self.tradeDate='20230701', self.openTime='160000', self.closeTime='160959',self.symbol='BTCUSDT',self.open='30448.1', self.close='30445.8'
2023-07-01 16:10:01,097:INFO:testStrategy:main.py:102:handleKline:2217133: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
12188  20230701   152000    152959  1688196599  30404.4  30416.4
12189  20230701   153000    153959  1688197199  30416.4  30427.1
12190  20230701   154000    154959  1688197799  30427.1  30433.7
12191  20230701   155000    155959  1688198399  30433.7  30448.1
12192  20230701   160000    160959  1688198999  30448.1  30445.8
2023-07-01 16:10:01,097:INFO:testStrategy:main.py:103:handleKline:2217133: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': True, 'isOpenSell': False, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True, 'isCorr': False}

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=6948 

self.closeSec=1688199599, self.tradeDate='20230701', self.openTime='161000', self.closeTime='161959', self.symbol='BTCUSDT', self.open='30445.8', self.close='30423.1'
127.0.0.1 - - [01/Jul/2023 16:20:04] "POST / HTTP/1.1" 200 -
2023-07-01 16:20:09,774:INFO:testStrategy:main.py:101:handleKline:2217133: self.closeSec=1688199599, self.tradeDate='20230701', self.openTime='161000', self.closeTime='161959',self.symbol='BTCUSDT',self.open='30445.8', self.close='30423.1'
2023-07-01 16:20:10,116:INFO:testStrategy:main.py:102:handleKline:2217133: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
12189  20230701   153000    153959  1688197199  30416.4  30427.1
12190  20230701   154000    154959  1688197799  30427.1  30433.7
12191  20230701   155000    155959  1688198399  30433.7  30448.1
12192  20230701   160000    160959  1688198999  30448.1  30445.8
12193  20230701   161000    161959  1688199599  30445.8  30423.1
2023-07-01 16:20:10,117:INFO:testStrategy:main.py:103:handleKline:2217133: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': True, 'isOpenSell': False, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True, 'isCorr': False}


## /root/FIL/strategy/sr_min/log.txt ----- -----

--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=1, self.total=996015.990996, self.flagDict['side']='buy', self.tradeCount=1, self.count=13888
self.closeSec=1688199599, self.tradeDate='20230701', self.openTime='161500', self.closeTime='161959', self.symbol='BTCUSDT', self.open=30436.0, self.close=30423.1, self.high=30439.6, self.low=30423.0, self.vol=200.452, self.amt=6099869.0294 
127.0.0.1 - - [01/Jul/2023 16:20:02] "POST / HTTP/1.1" 200 -
2023-07-01 16:20:08,138:INFO:sr_min:main.py:172:handleKline:2219263: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5951  20230701   155500    155959  ...         0.0        0.0       0
5952  20230701   160000    160459  ...         0.0        0.0       0
5953  20230701   160500    160959  ...         0.0        0.0       0
5954  20230701   161000    161459  ...         0.0        0.0       0
5955  20230701   161500    161959  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-07-01 16:20:08,156:INFO:sr_min:main.py:175:handleKline:2219263: self.closeSec=1688199599, self.tradeDate='20230701', self.openTime='161500', self.closeTime='161959',self.symbol='BTCUSDT',self.open=30436.0, self.close=30423.1, self.high=30439.6, self.low=30423.0, self.vol=200.452, self.amt=6099869.0294, ukdf['pct'].iloc[-1]=-0.000424 , ukdf['amount'].iloc[-1]=6099869.0294, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5955, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '37.141', 'enterprice': '26844', 'countrevence': '0', 'unrealprofit': '133176.4837', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '30429.7', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=1
127.0.0.1 - - [01/Jul/2023 16:25:00] "POST / HTTP/1.1" 200 -
--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=1, self.total=996015.990996, self.flagDict['side']='buy', self.tradeCount=1, self.count=13889
self.closeSec=1688199899, self.tradeDate='20230701', self.openTime='162000', self.closeTime='162459', self.symbol='BTCUSDT', self.open=30423.0, self.close=30438.0, self.high=30439.4, self.low=30423.0, self.vol=148.813, self.amt=4528795.2841 
2023-07-01 16:25:00,838:INFO:sr_min:main.py:172:handleKline:2219263: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5952  20230701   160000    160459  ...         0.0        0.0       0
5953  20230701   160500    160959  ...         0.0        0.0       0
5954  20230701   161000    161459  ...         0.0        0.0       0
5955  20230701   161500    161959  ...         0.0        0.0       0
5956  20230701   162000    162459  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-07-01 16:25:00,839:INFO:sr_min:main.py:175:handleKline:2219263: self.closeSec=1688199899, self.tradeDate='20230701', self.openTime='162000', self.closeTime='162459',self.symbol='BTCUSDT',self.open=30423.0, self.close=30438.0, self.high=30439.4, self.low=30423.0, self.vol=148.813, self.amt=4528795.2841, ukdf['pct'].iloc[-1]=0.00049 , ukdf['amount'].iloc[-1]=4528795.2841, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5956, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '37.141', 'enterprice': '26844', 'countrevence': '0', 'unrealprofit': '133497.03150389411', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '30438.33056471', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=1


## /root/FIL/strategy/s_rsrs/log.txt ----- -----

721  20230701   040000    075959  1688169599  ...    721  0.019349 -1.508678    -1.0
722  20230701   080000    115959  1688183999  ...    722  0.013109 -1.494357    -1.0

[5 rows x 15 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '53.268', 'enterprice': '30707', 'countrevence': '0', 'unrealprofit': '16816.7076', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '30391.3', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'numpy.int64'>, curSign=-1, self.sign=-1
--handleKline--:  version='2.0.0', self.name='s_rsrs', self.symbol='BTCUSDT', interval='4h', intervalSec=14400, wid=25, thd=0.6, self.sign=-1, self.total=1634064.775524, self.flagDict['side']='sell', self.tradeCount=8, self.count=289
self.closeSec=1688198399, self.tradeDate='20230701', self.openTime='120000', self.closeTime='155959', self.symbol='BTCUSDT', self.open=30391.2, self.close=30448.1, self.high=30462.8, self.low=30311.3, self.vol=23531.509, self.amt=715304827.50278 
127.0.0.1 - - [01/Jul/2023 16:00:01] "POST / HTTP/1.1" 200 -
2023-07-01 16:00:01,617:INFO:s_rsrs:main.py:141:handleKline:2218689: self.closeSec=1688198399, self.tradeDate='20230701', self.openTime='120000', self.closeTime='155959',self.symbol='BTCUSDT',self.open=30391.2, self.close=30448.1, self.high=30462.8, self.low=30311.3, self.vol=23531.509, self.amt=715304827.50278 
2023-07-01 16:00:01,654:INFO:s_rsrs:main.py:142:handleKline:2218689: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime  ...         vol           amt       pct
719  20230630   200000    235959  ...  346709.184  1.049024e+10 -0.027371
720  20230701   000000    035959  ...  155211.239  4.717005e+09  0.010259
721  20230701   040000    075959  ...   35577.773  1.083165e+09  0.003290
722  20230701   080000    115959  ...   29778.267  9.064876e+08 -0.002265
723  20230701   120000    155959  ...   23531.509  7.153048e+08  0.001872

[5 rows x 11 columns]
2023-07-01 16:00:02,958:INFO:s_rsrs:main.py:151:handleKline:2218689: df_s.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec  ...  index      beta    zscore  signal
719  20230630   200000    235959  1688140799  ...    719  0.035999 -1.527750    -1.0
720  20230701   000000    035959  1688155199  ...    720  0.026872 -1.519883    -1.0
721  20230701   040000    075959  1688169599  ...    721  0.019349 -1.508678    -1.0
722  20230701   080000    115959  1688183999  ...    722  0.013109 -1.494357    -1.0
723  20230701   120000    155959  1688198399  ...    723  0.011212 -1.469111    -1.0

[5 rows x 15 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '53.268', 'enterprice': '30707', 'countrevence': '0', 'unrealprofit': '13791.0852', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '30448.1', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'numpy.int64'>, curSign=-1, self.sign=-1


