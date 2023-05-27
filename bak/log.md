# 20230527 16:26:02

## /root/FIL/strategy/amihud/log.txt ----- -----

--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=373746.4768026, self.flagDict['side']='sell', self.tradeCount=2, self.count=3808
self.closeSec=1685175599, self.tradeDate='20230527', self.openTime='161500', self.closeTime='161959', self.symbol='BTCUSDT', self.open=26683.0, self.close=26676.4, self.high=26693.8, self.low=26675.2, self.vol=514.315, self.amt=13724616.975 
127.0.0.1 - - [27/May/2023 16:20:01] "POST / HTTP/1.1" 200 -
2023-05-27 16:20:07,558:INFO:amihud:main.py:172:handleKline:2219019: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5951  20230527   155500    155959  ...         0.0        0.0       0
5952  20230527   160000    160459  ...         0.0        0.0       0
5953  20230527   160500    160959  ...         0.0        0.0       0
5954  20230527   161000    161459  ...         0.0        0.0       0
5955  20230527   161500    161959  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-05-27 16:20:07,588:INFO:amihud:main.py:175:handleKline:2219019: self.closeSec=1685175599, self.tradeDate='20230527', self.openTime='161500', self.closeTime='161959',self.symbol='BTCUSDT',self.open=26683.0, self.close=26676.4, self.high=26693.8, self.low=26675.2, self.vol=514.315, self.amt=13724616.975, ukdf['pct'].iloc[-1]=-0.000251 , ukdf['amount'].iloc[-1]=13724616.975, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5955, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '13.926', 'enterprice': '26864.9', 'countrevence': '0', 'unrealprofit': '2598.5916', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '26678.3', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1
127.0.0.1 - - [27/May/2023 16:25:00] "POST / HTTP/1.1" 200 -
--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=373746.4768026, self.flagDict['side']='sell', self.tradeCount=2, self.count=3809
self.closeSec=1685175899, self.tradeDate='20230527', self.openTime='162000', self.closeTime='162459', self.symbol='BTCUSDT', self.open=26676.5, self.close=26692.8, self.high=26693.7, self.low=26676.4, self.vol=359.882, self.amt=9602840.2931 
2023-05-27 16:25:00,888:INFO:amihud:main.py:172:handleKline:2219019: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5952  20230527   160000    160459  ...         0.0        0.0       0
5953  20230527   160500    160959  ...         0.0        0.0       0
5954  20230527   161000    161459  ...         0.0        0.0       0
5955  20230527   161500    161959  ...         0.0        0.0       0
5956  20230527   162000    162459  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-05-27 16:25:00,888:INFO:amihud:main.py:175:handleKline:2219019: self.closeSec=1685175899, self.tradeDate='20230527', self.openTime='162000', self.closeTime='162459',self.symbol='BTCUSDT',self.open=26676.5, self.close=26692.8, self.high=26693.7, self.low=26676.4, self.vol=359.882, self.amt=9602840.2931, ukdf['pct'].iloc[-1]=0.000615 , ukdf['amount'].iloc[-1]=9602840.2931, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5956, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '13.926', 'enterprice': '26864.9', 'countrevence': '0', 'unrealprofit': '2381.346', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '26693.9', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1


## /root/FIL/strategy/factorcheck/log.txt ----- -----


self.closeSec=1685175599, self.tradeDate='20230527', self.openTime='161500', self.closeTime='161959', self.symbol='BTCUSDT', self.open=26683.0, self.close=26676.4, self.high=26693.8, self.low=26675.2 
127.0.0.1 - - [27/May/2023 16:20:01] "POST / HTTP/1.1" 200 -
2023-05-27 16:20:04,978:INFO:factorcheck2:main.py:126:handleKline:2218005: self.closeSec=1685175599, self.tradeDate='20230527', self.openTime='161500', self.closeTime='161959',self.symbol='BTCUSDT',self.open=26683.0, self.close=26676.4, self.high=26693.8, self.low=26675.2   
2023-05-27 16:20:06,098:INFO:factorcheck2:main.py:127:handleKline:2218005: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime    closeSec  ...      low       pct  index  idx
1631  20230527   155500    155959  1685174399  ...  26706.9  0.000311   1631    5
1632  20230527   160000    160459  1685174699  ...  26696.6 -0.000674   1632    0
1633  20230527   160500    160959  1685174999  ...  26674.1 -0.000502   1633    1
1634  20230527   161000    161459  1685175299  ...  26670.0 -0.000030   1634    2
1635  20230527   161500    161959  1685175599  ...  26675.2 -0.000251   1635    3

[5 rows x 11 columns]
2023-05-27 16:20:06,108:INFO:factorcheck2:main.py:128:handleKline:2218005: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}
127.0.0.1 - - [27/May/2023 16:25:00] "POST / HTTP/1.1" 200 -

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=35, self.factor=0.2952540592660336, self.count=3811 

self.closeSec=1685175899, self.tradeDate='20230527', self.openTime='162000', self.closeTime='162459', self.symbol='BTCUSDT', self.open=26676.5, self.close=26692.8, self.high=26693.7, self.low=26676.4 
2023-05-27 16:25:00,734:INFO:factorcheck2:main.py:126:handleKline:2218005: self.closeSec=1685175899, self.tradeDate='20230527', self.openTime='162000', self.closeTime='162459',self.symbol='BTCUSDT',self.open=26676.5, self.close=26692.8, self.high=26693.7, self.low=26676.4   
2023-05-27 16:25:00,839:INFO:factorcheck2:main.py:127:handleKline:2218005: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime    closeSec  ...      low       pct  index  idx
1632  20230527   160000    160459  1685174699  ...  26696.6 -0.000674   1632    0
1633  20230527   160500    160959  1685174999  ...  26674.1 -0.000502   1633    1
1634  20230527   161000    161459  1685175299  ...  26670.0 -0.000030   1634    2
1635  20230527   161500    161959  1685175599  ...  26675.2 -0.000251   1635    3
1636  20230527   162000    162459  1685175899  ...  26676.4  0.000615   1636    4

[5 rows x 11 columns]
2023-05-27 16:25:00,839:INFO:factorcheck2:main.py:128:handleKline:2218005: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}


## /root/FIL/strategy/logic/log.txt ----- -----

2023-05-27 16:00:32,568:DEBUG:logic:main.py:463:getModel:2218526: df_s.iloc[-5:,:] :
          date closeTime     open  ...    alpha58   alpha67   alpha72
5786  20230527    132959  26746.7  ...  47.083333  0.545714  0.357549
5787  20230527    135959  26728.9  ...  46.666667  0.541017  0.357775
5788  20230527    142959  26714.9  ...  46.250000  0.537711  0.359108
5789  20230527    145959  26705.1  ...  46.666667  0.546681  0.356790
5790  20230527    152959  26736.2  ...  46.250000  0.538251  0.357444

[5 rows x 33 columns]
0.540590405904059
acc is : 0.540590405904059
2023-05-27 16:00:32,750:INFO:logic:main.py:468:getModel:2218526: df_pred.iloc[-5:,:] :
     pred    prob_0    prob_1  actual  ...       nav  sign  cost_        bm
537     1  0.493803  0.506197       0  ...  0.898656   1.0    0.0  0.982379
538     1  0.495141  0.504859       0  ...  0.898327   1.0    0.0  0.982018
539     1  0.493420  0.506580       1  ...  0.899373   1.0    0.0  0.983162
540     0  0.503339  0.496661       0  ...  0.898545   1.0    0.0  0.982257
541     1  0.490484  0.509516       1  ...  0.898670   1.0    0.0  0.982393

[5 rows x 10 columns]
2023-05-27 16:00:32,773:INFO:logic:main.py:478:getModel:2218526: df_panel.iloc[-5:,:] :
    pred    prob_0    prob_1  actual  ...       nav  sign  cost_        bm
45     1  0.493723  0.506277       0  ...  0.907361   1.0    0.0  0.978622
46     1  0.495203  0.504797       0  ...  0.907029   1.0    0.0  0.979321
47     1  0.493432  0.506568       1  ...  0.908085   1.0    0.0  0.984668
48     0  0.503177  0.496823       0  ...  0.907249   1.0    0.0  0.979430
49     1  0.490484  0.509516       1  ...  0.898670   1.0    0.0  0.982393

[5 rows x 10 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '25.918', 'enterprice': '26792.4', 'countrevence': '0', 'unrealprofit': '-2000.8696', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '26715.2', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}


## /root/FIL/strategy/modifiedmom/log.txt ----- -----

527  20230527   155000    155959  1685174399  26703.5  26715.3  0.000438
2023-05-27 16:00:02,302:INFO:modifiedmom:main.py:146:handleKline:2218259: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': True, 'isOpenSell': False, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True}
127.0.0.1 - - [27/May/2023 16:10:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=1904 

self.closeSec=1685174999, self.tradeDate='20230527', self.openTime='160000', self.closeTime='160959', self.symbol='BTCUSDT', self.open='26715.2', self.close='26683.9'
2023-05-27 16:10:01,083:INFO:modifiedmom:main.py:144:handleKline:2218259: self.closeSec=1685174999, self.tradeDate='20230527', self.openTime='160000', self.closeTime='160959',self.symbol='BTCUSDT',self.open='26715.2', self.close='26683.9'
2023-05-27 16:10:01,131:INFO:modifiedmom:main.py:145:handleKline:2218259: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec     open    close       pct
524  20230527   152000    152959  1685172599  26713.6  26711.6 -0.000079
525  20230527   153000    153959  1685173199  26711.6  26710.6 -0.000037
526  20230527   154000    154959  1685173799  26710.6  26703.6 -0.000262
527  20230527   155000    155959  1685174399  26703.5  26715.3  0.000438
528  20230527   160000    160959  1685174999  26715.2  26683.9 -0.001175
2023-05-27 16:10:01,131:INFO:modifiedmom:main.py:146:handleKline:2218259: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': True, 'isOpenSell': False, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True}

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=1905 

self.closeSec=1685175599, self.tradeDate='20230527', self.openTime='161000', self.closeTime='161959', self.symbol='BTCUSDT', self.open='26683.9', self.close='26676.4'
127.0.0.1 - - [27/May/2023 16:20:04] "POST / HTTP/1.1" 200 -
2023-05-27 16:20:07,127:INFO:modifiedmom:main.py:144:handleKline:2218259: self.closeSec=1685175599, self.tradeDate='20230527', self.openTime='161000', self.closeTime='161959',self.symbol='BTCUSDT',self.open='26683.9', self.close='26676.4'
2023-05-27 16:20:07,788:INFO:modifiedmom:main.py:145:handleKline:2218259: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec     open    close       pct
525  20230527   153000    153959  1685173199  26711.6  26710.6 -0.000037
526  20230527   154000    154959  1685173799  26710.6  26703.6 -0.000262
527  20230527   155000    155959  1685174399  26703.5  26715.3  0.000438
528  20230527   160000    160959  1685174999  26715.2  26683.9 -0.001175
529  20230527   161000    161959  1685175599  26683.9  26676.4 -0.000281
2023-05-27 16:20:07,797:INFO:modifiedmom:main.py:146:handleKline:2218259: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': True, 'isOpenSell': False, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True}


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

17519  20230527   155000    155959  1685174399  26703.5  26715.3
2023-05-27 16:00:02,289:INFO:pyemd2:main.py:127:handleKline:2217508: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=1907 

self.closeSec=1685174999, self.tradeDate='20230527', self.openTime='160000', self.closeTime='160959', self.symbol='BTCUSDT', self.open='26715.2', self.close='26683.9'
127.0.0.1 - - [27/May/2023 16:10:01] "POST / HTTP/1.1" 200 -
2023-05-27 16:10:01,100:INFO:pyemd2:main.py:125:handleKline:2217508: self.closeSec=1685174999, self.tradeDate='20230527', self.openTime='160000', self.closeTime='160959',self.symbol='BTCUSDT',self.open='26715.2', self.close='26683.9'
2023-05-27 16:10:01,138:INFO:pyemd2:main.py:126:handleKline:2217508: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
17516  20230527   152000    152959  1685172599  26713.6  26711.6
17517  20230527   153000    153959  1685173199  26711.6  26710.6
17518  20230527   154000    154959  1685173799  26710.6  26703.6
17519  20230527   155000    155959  1685174399  26703.5  26715.3
17520  20230527   160000    160959  1685174999  26715.2  26683.9
2023-05-27 16:10:01,140:INFO:pyemd2:main.py:127:handleKline:2217508: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=1908 

self.closeSec=1685175599, self.tradeDate='20230527', self.openTime='161000', self.closeTime='161959', self.symbol='BTCUSDT', self.open='26683.9', self.close='26676.4'
127.0.0.1 - - [27/May/2023 16:20:05] "POST / HTTP/1.1" 200 -
2023-05-27 16:20:08,932:INFO:pyemd2:main.py:125:handleKline:2217508: self.closeSec=1685175599, self.tradeDate='20230527', self.openTime='161000', self.closeTime='161959',self.symbol='BTCUSDT',self.open='26683.9', self.close='26676.4'
2023-05-27 16:20:09,067:INFO:pyemd2:main.py:126:handleKline:2217508: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
17517  20230527   153000    153959  1685173199  26711.6  26710.6
17518  20230527   154000    154959  1685173799  26710.6  26703.6
17519  20230527   155000    155959  1685174399  26703.5  26715.3
17520  20230527   160000    160959  1685174999  26715.2  26683.9
17521  20230527   161000    161959  1685175599  26683.9  26676.4
2023-05-27 16:20:09,067:INFO:pyemd2:main.py:127:handleKline:2217508: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}


## /root/FIL/strategy/similarity/log.txt ----- -----

12191  20230527   155000    155959  1685174399  26703.5  26715.3
2023-05-27 16:00:02,280:INFO:testStrategy:main.py:103:handleKline:2217133: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': True, 'isOpenSell': False, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True, 'isCorr': False}

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=1907 

self.closeSec=1685174999, self.tradeDate='20230527', self.openTime='160000', self.closeTime='160959', self.symbol='BTCUSDT', self.open='26715.2', self.close='26683.9'
2023-05-27 16:10:01,115:INFO:testStrategy:main.py:101:handleKline:2217133: self.closeSec=1685174999, self.tradeDate='20230527', self.openTime='160000', self.closeTime='160959',self.symbol='BTCUSDT',self.open='26715.2', self.close='26683.9'
127.0.0.1 - - [27/May/2023 16:10:01] "POST / HTTP/1.1" 200 -
2023-05-27 16:10:01,142:INFO:testStrategy:main.py:102:handleKline:2217133: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
12188  20230527   152000    152959  1685172599  26713.6  26711.6
12189  20230527   153000    153959  1685173199  26711.6  26710.6
12190  20230527   154000    154959  1685173799  26710.6  26703.6
12191  20230527   155000    155959  1685174399  26703.5  26715.3
12192  20230527   160000    160959  1685174999  26715.2  26683.9
2023-05-27 16:10:01,143:INFO:testStrategy:main.py:103:handleKline:2217133: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': True, 'isOpenSell': False, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True, 'isCorr': False}

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=1908 

self.closeSec=1685175599, self.tradeDate='20230527', self.openTime='161000', self.closeTime='161959', self.symbol='BTCUSDT', self.open='26683.9', self.close='26676.4'
127.0.0.1 - - [27/May/2023 16:20:04] "POST / HTTP/1.1" 200 -
2023-05-27 16:20:08,621:INFO:testStrategy:main.py:101:handleKline:2217133: self.closeSec=1685175599, self.tradeDate='20230527', self.openTime='161000', self.closeTime='161959',self.symbol='BTCUSDT',self.open='26683.9', self.close='26676.4'
2023-05-27 16:20:08,889:INFO:testStrategy:main.py:102:handleKline:2217133: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
12189  20230527   153000    153959  1685173199  26711.6  26710.6
12190  20230527   154000    154959  1685173799  26710.6  26703.6
12191  20230527   155000    155959  1685174399  26703.5  26715.3
12192  20230527   160000    160959  1685174999  26715.2  26683.9
12193  20230527   161000    161959  1685175599  26683.9  26676.4
2023-05-27 16:20:08,898:INFO:testStrategy:main.py:103:handleKline:2217133: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': True, 'isOpenSell': False, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True, 'isCorr': False}


## /root/FIL/strategy/sr_min/log.txt ----- -----

--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=1, self.total=996015.990996, self.flagDict['side']='buy', self.tradeCount=1, self.count=3808
self.closeSec=1685175599, self.tradeDate='20230527', self.openTime='161500', self.closeTime='161959', self.symbol='BTCUSDT', self.open=26683.0, self.close=26676.4, self.high=26693.8, self.low=26675.2, self.vol=514.315, self.amt=13724616.975 
127.0.0.1 - - [27/May/2023 16:20:01] "POST / HTTP/1.1" 200 -
2023-05-27 16:20:07,518:INFO:sr_min:main.py:172:handleKline:2219263: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5951  20230527   155500    155959  ...         0.0        0.0       0
5952  20230527   160000    160459  ...         0.0        0.0       0
5953  20230527   160500    160959  ...         0.0        0.0       0
5954  20230527   161000    161459  ...         0.0        0.0       0
5955  20230527   161500    161959  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-05-27 16:20:07,550:INFO:sr_min:main.py:175:handleKline:2219263: self.closeSec=1685175599, self.tradeDate='20230527', self.openTime='161500', self.closeTime='161959',self.symbol='BTCUSDT',self.open=26683.0, self.close=26676.4, self.high=26693.8, self.low=26675.2, self.vol=514.315, self.amt=13724616.975, ukdf['pct'].iloc[-1]=-0.000251 , ukdf['amount'].iloc[-1]=13724616.975, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5955, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '37.141', 'enterprice': '26844', 'countrevence': '0', 'unrealprofit': '-6154.2637', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '26678.3', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=1
--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=1, self.total=996015.990996, self.flagDict['side']='buy', self.tradeCount=1, self.count=3809
self.closeSec=1685175899, self.tradeDate='20230527', self.openTime='162000', self.closeTime='162459', self.symbol='BTCUSDT', self.open=26676.5, self.close=26692.8, self.high=26693.7, self.low=26676.4, self.vol=359.882, self.amt=9602840.2931 
127.0.0.1 - - [27/May/2023 16:25:00] "POST / HTTP/1.1" 200 -
2023-05-27 16:25:00,884:INFO:sr_min:main.py:172:handleKline:2219263: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5952  20230527   160000    160459  ...         0.0        0.0       0
5953  20230527   160500    160959  ...         0.0        0.0       0
5954  20230527   161000    161459  ...         0.0        0.0       0
5955  20230527   161500    161959  ...         0.0        0.0       0
5956  20230527   162000    162459  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-05-27 16:25:00,884:INFO:sr_min:main.py:175:handleKline:2219263: self.closeSec=1685175899, self.tradeDate='20230527', self.openTime='162000', self.closeTime='162459',self.symbol='BTCUSDT',self.open=26676.5, self.close=26692.8, self.high=26693.7, self.low=26676.4, self.vol=359.882, self.amt=9602840.2931, ukdf['pct'].iloc[-1]=0.000615 , ukdf['amount'].iloc[-1]=9602840.2931, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5956, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '37.141', 'enterprice': '26844', 'countrevence': '0', 'unrealprofit': '-5574.8641', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '26693.9', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=1


## /root/FIL/strategy/s_rsrs/log.txt ----- -----

721  20230527   040000    075959  1685145599  ...    721  0.595322  1.166378     1.0
722  20230527   080000    115959  1685159999  ...    722  0.601728  1.176548     1.0

[5 rows x 15 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '55.249', 'enterprice': '26128.2', 'countrevence': '0', 'unrealprofit': '34044.4338', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '26744.4', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'numpy.int64'>, curSign=1, self.sign=1
127.0.0.1 - - [27/May/2023 16:00:01] "POST / HTTP/1.1" 200 -
--handleKline--:  version='2.0.0', self.name='s_rsrs', self.symbol='BTCUSDT', interval='4h', intervalSec=14400, wid=25, thd=0.6, self.sign=1, self.total=1442113.3648782002, self.flagDict['side']='buy', self.tradeCount=3, self.count=79
self.closeSec=1685174399, self.tradeDate='20230527', self.openTime='120000', self.closeTime='155959', self.symbol='BTCUSDT', self.open=26739.6, self.close=26715.3, self.high=26776.4, self.low=26695.2, self.vol=15097.708, self.amt=403550897.7197 
2023-05-27 16:00:01,811:INFO:s_rsrs:main.py:141:handleKline:2218689: self.closeSec=1685174399, self.tradeDate='20230527', self.openTime='120000', self.closeTime='155959',self.symbol='BTCUSDT',self.open=26739.6, self.close=26715.3, self.high=26776.4, self.low=26695.2, self.vol=15097.708, self.amt=403550897.7197 
2023-05-27 16:00:01,870:INFO:s_rsrs:main.py:142:handleKline:2218689: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime  ...         vol           amt       pct
719  20230526   200000    235959  ...  137774.544  3.674536e+09  0.010793
720  20230527   000000    035959  ...   61511.083  1.644152e+09  0.000666
721  20230527   040000    075959  ...   18689.388  4.995218e+08 -0.002441
722  20230527   080000    115959  ...   21434.056  5.720833e+08  0.001858
723  20230527   120000    155959  ...   15097.708  4.035509e+08 -0.000905

[5 rows x 11 columns]
2023-05-27 16:00:03,993:INFO:s_rsrs:main.py:151:handleKline:2218689: df_s.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec  ...  index      beta    zscore  signal
719  20230526   200000    235959  1685116799  ...    719  0.605951  1.281364     1.0
720  20230527   000000    035959  1685131199  ...    720  0.597411  1.205087     1.0
721  20230527   040000    075959  1685145599  ...    721  0.595322  1.166378     1.0
722  20230527   080000    115959  1685159999  ...    722  0.601728  1.176548     1.0
723  20230527   120000    155959  1685174399  ...    723  0.565573  0.949284     1.0

[5 rows x 15 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '55.249', 'enterprice': '26128.2', 'countrevence': '0', 'unrealprofit': '32403.5385', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '26714.7', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'numpy.int64'>, curSign=1, self.sign=1


