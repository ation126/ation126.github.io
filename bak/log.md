# 20230615 16:26:01

## /root/FIL/strategy/amihud/log.txt ----- -----

--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=373746.4768026, self.flagDict['side']='sell', self.tradeCount=2, self.count=9280
self.closeSec=1686817199, self.tradeDate='20230615', self.openTime='161500', self.closeTime='161959', self.symbol='BTCUSDT', self.open=25010.2, self.close=24998.9, self.high=25012.1, self.low=24985.8, self.vol=792.061, self.amt=19799009.2189 
127.0.0.1 - - [15/Jun/2023 16:20:01] "POST / HTTP/1.1" 200 -
2023-06-15 16:20:07,040:INFO:amihud:main.py:172:handleKline:2219019: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5951  20230615   155500    155959  ...         0.0        0.0       0
5952  20230615   160000    160459  ...         0.0        0.0       0
5953  20230615   160500    160959  ...         0.0        0.0       0
5954  20230615   161000    161459  ...         0.0        0.0       0
5955  20230615   161500    161959  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-06-15 16:20:07,080:INFO:amihud:main.py:175:handleKline:2219019: self.closeSec=1686817199, self.tradeDate='20230615', self.openTime='161500', self.closeTime='161959',self.symbol='BTCUSDT',self.open=25010.2, self.close=24998.9, self.high=25012.1, self.low=24985.8, self.vol=792.061, self.amt=19799009.2189, ukdf['pct'].iloc[-1]=-0.000456 , ukdf['amount'].iloc[-1]=19799009.2189, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5955, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '13.926', 'enterprice': '26864.9', 'countrevence': '0', 'unrealprofit': '25967.83014003024', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '25000.19871176', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1
--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=373746.4768026, self.flagDict['side']='sell', self.tradeCount=2, self.count=9281
self.closeSec=1686817499, self.tradeDate='20230615', self.openTime='162000', self.closeTime='162459', self.symbol='BTCUSDT', self.open=24999.0, self.close=25012.1, self.high=25016.0, self.low=24998.8, self.vol=892.988, self.amt=22333462.1347 
127.0.0.1 - - [15/Jun/2023 16:25:00] "POST / HTTP/1.1" 200 -
2023-06-15 16:25:00,824:INFO:amihud:main.py:172:handleKline:2219019: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5952  20230615   160000    160459  ...         0.0        0.0       0
5953  20230615   160500    160959  ...         0.0        0.0       0
5954  20230615   161000    161459  ...         0.0        0.0       0
5955  20230615   161500    161959  ...         0.0        0.0       0
5956  20230615   162000    162459  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-06-15 16:25:00,824:INFO:amihud:main.py:175:handleKline:2219019: self.closeSec=1686817499, self.tradeDate='20230615', self.openTime='162000', self.closeTime='162459',self.symbol='BTCUSDT',self.open=24999.0, self.close=25012.1, self.high=25016.0, self.low=24998.8, self.vol=892.988, self.amt=22333462.1347, ukdf['pct'].iloc[-1]=0.000528 , ukdf['amount'].iloc[-1]=22333462.1347, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5956, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '13.926', 'enterprice': '26864.9', 'countrevence': '0', 'unrealprofit': '25849.36949474748', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '25008.70514902', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1


## /root/FIL/strategy/factorcheck/log.txt ----- -----


self.closeSec=1686817199, self.tradeDate='20230615', self.openTime='161500', self.closeTime='161959', self.symbol='BTCUSDT', self.open=25010.2, self.close=24998.9, self.high=25012.1, self.low=24985.8 
127.0.0.1 - - [15/Jun/2023 16:20:01] "POST / HTTP/1.1" 200 -
2023-06-15 16:20:04,730:INFO:factorcheck2:main.py:126:handleKline:2218005: self.closeSec=1686817199, self.tradeDate='20230615', self.openTime='161500', self.closeTime='161959',self.symbol='BTCUSDT',self.open=25010.2, self.close=24998.9, self.high=25012.1, self.low=24985.8   
2023-06-15 16:20:06,132:INFO:factorcheck2:main.py:127:handleKline:2218005: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime    closeSec  ...      low       pct  index  idx
1631  20230615   155500    155959  1686815999  ...  24959.0 -0.000176   1631    5
1632  20230615   160000    160459  1686816299  ...  24950.0  0.000573   1632    0
1633  20230615   160500    160959  1686816599  ...  24986.7  0.000652   1633    1
1634  20230615   161000    161459  1686816899  ...  25001.3  0.000204   1634    2
1635  20230615   161500    161959  1686817199  ...  24985.8 -0.000456   1635    3

[5 rows x 11 columns]
2023-06-15 16:20:06,149:INFO:factorcheck2:main.py:128:handleKline:2218005: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': True, 'isOpenSell': False, 'isCloseBuy': False, 'isCloseSell': False, 'isOpen': True, 'isClose': False, 'isTrig': True}

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=0, self.factor=0.6366072276261995, self.count=9283 

self.closeSec=1686817499, self.tradeDate='20230615', self.openTime='162000', self.closeTime='162459', self.symbol='BTCUSDT', self.open=24999.0, self.close=25012.1, self.high=25016.0, self.low=24998.8 
127.0.0.1 - - [15/Jun/2023 16:25:00] "POST / HTTP/1.1" 200 -
2023-06-15 16:25:00,759:INFO:factorcheck2:main.py:126:handleKline:2218005: self.closeSec=1686817499, self.tradeDate='20230615', self.openTime='162000', self.closeTime='162459',self.symbol='BTCUSDT',self.open=24999.0, self.close=25012.1, self.high=25016.0, self.low=24998.8   
2023-06-15 16:25:00,819:INFO:factorcheck2:main.py:127:handleKline:2218005: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime    closeSec  ...      low       pct  index  idx
1632  20230615   160000    160459  1686816299  ...  24950.0  0.000573   1632    0
1633  20230615   160500    160959  1686816599  ...  24986.7  0.000652   1633    1
1634  20230615   161000    161459  1686816899  ...  25001.3  0.000204   1634    2
1635  20230615   161500    161959  1686817199  ...  24985.8 -0.000456   1635    3
1636  20230615   162000    162459  1686817499  ...  24998.8  0.000528   1636    4

[5 rows x 11 columns]
2023-06-15 16:25:00,819:INFO:factorcheck2:main.py:128:handleKline:2218005: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': True, 'isOpenSell': False, 'isCloseBuy': False, 'isCloseSell': False, 'isOpen': True, 'isClose': False, 'isTrig': True}


## /root/FIL/strategy/logic/log.txt ----- -----

2023-06-15 16:00:19,109:DEBUG:logic:main.py:463:getModel:2218526: df_s.iloc[-5:,:] :
          date closeTime     open  ...    alpha58   alpha67   alpha72
5786  20230615    132959  25015.9  ...  49.166667  0.369043  0.710415
5787  20230615    135959  25028.8  ...  49.166667  0.367549  0.718347
5788  20230615    142959  25019.1  ...  48.750000  0.363694  0.727051
5789  20230615    145959  24993.6  ...  48.750000  0.352379  0.739075
5790  20230615    152959  24917.4  ...  48.750000  0.358658  0.749095

[5 rows x 33 columns]
0.533210332103321
acc is : 0.533210332103321
2023-06-15 16:00:19,195:INFO:logic:main.py:468:getModel:2218526: df_pred.iloc[-5:,:] :
     pred    prob_0    prob_1  actual  ...       nav  sign  cost_        bm
537     0  0.508847  0.491153       0  ...  1.040366  -1.0    0.0  0.926633
538     0  0.506623  0.493377       0  ...  1.041423  -1.0    0.0  0.925692
539     0  0.501319  0.498681       0  ...  1.044598  -1.0    0.0  0.922870
540     1  0.491333  0.508667       1  ...  1.043612  -1.0    0.0  0.923740
541     0  0.509442  0.490558       1  ...  1.042202  -1.0    0.0  0.924989

[5 rows x 10 columns]
2023-06-15 16:00:19,206:INFO:logic:main.py:478:getModel:2218526: df_panel.iloc[-5:,:] :
    pred    prob_0    prob_1  actual  ...       nav  sign  cost_        bm
45     0  0.508592  0.491408       0  ...  1.040366  -1.0    0.0  0.924561
46     0  0.505110  0.494890       0  ...  1.041423  -1.0    0.0  0.923534
47     0  0.500057  0.499943       0  ...  1.044598  -1.0    0.0  0.920994
48     1  0.489943  0.510057       1  ...  1.043612  -1.0    0.0  0.922050
49     0  0.509442  0.490558       1  ...  1.042202  -1.0    0.0  0.924989

[5 rows x 10 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '27.898', 'enterprice': '25555.4', 'countrevence': '0', 'unrealprofit': '16281.2728', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '24971.8', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}


## /root/FIL/strategy/modifiedmom/log.txt ----- -----

527  20230615   155000    155959  1686815999  24996.2  24974.6 -0.000864
2023-06-15 16:00:02,303:INFO:modifiedmom:main.py:146:handleKline:2218259: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': True, 'isOpenSell': False, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True}
127.0.0.1 - - [15/Jun/2023 16:10:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=4640 

self.closeSec=1686816599, self.tradeDate='20230615', self.openTime='160000', self.closeTime='160959', self.symbol='BTCUSDT', self.open='24974.6', self.close='25005.2'
2023-06-15 16:10:01,142:INFO:modifiedmom:main.py:144:handleKline:2218259: self.closeSec=1686816599, self.tradeDate='20230615', self.openTime='160000', self.closeTime='160959',self.symbol='BTCUSDT',self.open='24974.6', self.close='25005.2'
2023-06-15 16:10:01,171:INFO:modifiedmom:main.py:145:handleKline:2218259: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec     open    close       pct
524  20230615   152000    152959  1686814199  24949.8    24941 -0.000357
525  20230615   153000    153959  1686814799    24941  24953.8  0.000513
526  20230615   154000    154959  1686815399  24953.8  24996.2  0.001699
527  20230615   155000    155959  1686815999  24996.2  24974.6 -0.000864
528  20230615   160000    160959  1686816599  24974.6  25005.2  0.001225
2023-06-15 16:10:01,172:INFO:modifiedmom:main.py:146:handleKline:2218259: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': True, 'isOpenSell': False, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True}

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=4641 

self.closeSec=1686817199, self.tradeDate='20230615', self.openTime='161000', self.closeTime='161959', self.symbol='BTCUSDT', self.open='25005.2', self.close='24998.9'
127.0.0.1 - - [15/Jun/2023 16:20:04] "POST / HTTP/1.1" 200 -
2023-06-15 16:20:06,911:INFO:modifiedmom:main.py:144:handleKline:2218259: self.closeSec=1686817199, self.tradeDate='20230615', self.openTime='161000', self.closeTime='161959',self.symbol='BTCUSDT',self.open='25005.2', self.close='24998.9'
2023-06-15 16:20:07,621:INFO:modifiedmom:main.py:145:handleKline:2218259: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec     open    close       pct
525  20230615   153000    153959  1686814799    24941  24953.8  0.000513
526  20230615   154000    154959  1686815399  24953.8  24996.2  0.001699
527  20230615   155000    155959  1686815999  24996.2  24974.6 -0.000864
528  20230615   160000    160959  1686816599  24974.6  25005.2  0.001225
529  20230615   161000    161959  1686817199  25005.2  24998.9 -0.000252
2023-06-15 16:20:07,630:INFO:modifiedmom:main.py:146:handleKline:2218259: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': True, 'isOpenSell': False, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True}


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

17519  20230615   155000    155959  1686815999  24996.2  24974.6
2023-06-15 16:00:02,320:INFO:pyemd2:main.py:127:handleKline:2217508: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=4643 

self.closeSec=1686816599, self.tradeDate='20230615', self.openTime='160000', self.closeTime='160959', self.symbol='BTCUSDT', self.open='24974.6', self.close='25005.2'
127.0.0.1 - - [15/Jun/2023 16:10:01] "POST / HTTP/1.1" 200 -
2023-06-15 16:10:01,156:INFO:pyemd2:main.py:125:handleKline:2217508: self.closeSec=1686816599, self.tradeDate='20230615', self.openTime='160000', self.closeTime='160959',self.symbol='BTCUSDT',self.open='24974.6', self.close='25005.2'
2023-06-15 16:10:01,176:INFO:pyemd2:main.py:126:handleKline:2217508: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
17516  20230615   152000    152959  1686814199  24949.8    24941
17517  20230615   153000    153959  1686814799    24941  24953.8
17518  20230615   154000    154959  1686815399  24953.8  24996.2
17519  20230615   155000    155959  1686815999  24996.2  24974.6
17520  20230615   160000    160959  1686816599  24974.6  25005.2
2023-06-15 16:10:01,176:INFO:pyemd2:main.py:127:handleKline:2217508: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=4644 

self.closeSec=1686817199, self.tradeDate='20230615', self.openTime='161000', self.closeTime='161959', self.symbol='BTCUSDT', self.open='25005.2', self.close='24998.9'
127.0.0.1 - - [15/Jun/2023 16:20:04] "POST / HTTP/1.1" 200 -
2023-06-15 16:20:08,755:INFO:pyemd2:main.py:125:handleKline:2217508: self.closeSec=1686817199, self.tradeDate='20230615', self.openTime='161000', self.closeTime='161959',self.symbol='BTCUSDT',self.open='25005.2', self.close='24998.9'
2023-06-15 16:20:08,905:INFO:pyemd2:main.py:126:handleKline:2217508: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
17517  20230615   153000    153959  1686814799    24941  24953.8
17518  20230615   154000    154959  1686815399  24953.8  24996.2
17519  20230615   155000    155959  1686815999  24996.2  24974.6
17520  20230615   160000    160959  1686816599  24974.6  25005.2
17521  20230615   161000    161959  1686817199  25005.2  24998.9
2023-06-15 16:20:08,906:INFO:pyemd2:main.py:127:handleKline:2217508: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}


## /root/FIL/strategy/similarity/log.txt ----- -----

12191  20230615   155000    155959  1686815999  24996.2  24974.6
2023-06-15 16:00:02,293:INFO:testStrategy:main.py:103:handleKline:2217133: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': True, 'isOpenSell': False, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True, 'isCorr': False}

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=4643 

self.closeSec=1686816599, self.tradeDate='20230615', self.openTime='160000', self.closeTime='160959', self.symbol='BTCUSDT', self.open='24974.6', self.close='25005.2'
127.0.0.1 - - [15/Jun/2023 16:10:01] "POST / HTTP/1.1" 200 -
2023-06-15 16:10:01,155:INFO:testStrategy:main.py:101:handleKline:2217133: self.closeSec=1686816599, self.tradeDate='20230615', self.openTime='160000', self.closeTime='160959',self.symbol='BTCUSDT',self.open='24974.6', self.close='25005.2'
2023-06-15 16:10:01,175:INFO:testStrategy:main.py:102:handleKline:2217133: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
12188  20230615   152000    152959  1686814199  24949.8    24941
12189  20230615   153000    153959  1686814799    24941  24953.8
12190  20230615   154000    154959  1686815399  24953.8  24996.2
12191  20230615   155000    155959  1686815999  24996.2  24974.6
12192  20230615   160000    160959  1686816599  24974.6  25005.2
2023-06-15 16:10:01,175:INFO:testStrategy:main.py:103:handleKline:2217133: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': True, 'isOpenSell': False, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True, 'isCorr': False}

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=4644 

self.closeSec=1686817199, self.tradeDate='20230615', self.openTime='161000', self.closeTime='161959', self.symbol='BTCUSDT', self.open='25005.2', self.close='24998.9'
127.0.0.1 - - [15/Jun/2023 16:20:04] "POST / HTTP/1.1" 200 -
2023-06-15 16:20:08,382:INFO:testStrategy:main.py:101:handleKline:2217133: self.closeSec=1686817199, self.tradeDate='20230615', self.openTime='161000', self.closeTime='161959',self.symbol='BTCUSDT',self.open='25005.2', self.close='24998.9'
2023-06-15 16:20:08,700:INFO:testStrategy:main.py:102:handleKline:2217133: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
12189  20230615   153000    153959  1686814799    24941  24953.8
12190  20230615   154000    154959  1686815399  24953.8  24996.2
12191  20230615   155000    155959  1686815999  24996.2  24974.6
12192  20230615   160000    160959  1686816599  24974.6  25005.2
12193  20230615   161000    161959  1686817199  25005.2  24998.9
2023-06-15 16:20:08,701:INFO:testStrategy:main.py:103:handleKline:2217133: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': True, 'isOpenSell': False, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True, 'isCorr': False}


## /root/FIL/strategy/sr_min/log.txt ----- -----

--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=1, self.total=996015.990996, self.flagDict['side']='buy', self.tradeCount=1, self.count=9280
self.closeSec=1686817199, self.tradeDate='20230615', self.openTime='161500', self.closeTime='161959', self.symbol='BTCUSDT', self.open=25010.2, self.close=24998.9, self.high=25012.1, self.low=24985.8, self.vol=792.061, self.amt=19799009.2189 
127.0.0.1 - - [15/Jun/2023 16:20:01] "POST / HTTP/1.1" 200 -
2023-06-15 16:20:07,031:INFO:sr_min:main.py:172:handleKline:2219263: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5951  20230615   155500    155959  ...         0.0        0.0       0
5952  20230615   160000    160459  ...         0.0        0.0       0
5953  20230615   160500    160959  ...         0.0        0.0       0
5954  20230615   161000    161459  ...         0.0        0.0       0
5955  20230615   161500    161959  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-06-15 16:20:07,060:INFO:sr_min:main.py:175:handleKline:2219263: self.closeSec=1686817199, self.tradeDate='20230615', self.openTime='161500', self.closeTime='161959',self.symbol='BTCUSDT',self.open=25010.2, self.close=24998.9, self.high=25012.1, self.low=24985.8, self.vol=792.061, self.amt=19799009.2189, ukdf['pct'].iloc[-1]=-0.000456 , ukdf['amount'].iloc[-1]=19799009.2189, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5955, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '37.141', 'enterprice': '26844', 'countrevence': '0', 'unrealprofit': '-68480.62364652184', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '25000.19871176', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=1
--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=1, self.total=996015.990996, self.flagDict['side']='buy', self.tradeCount=1, self.count=9281
self.closeSec=1686817499, self.tradeDate='20230615', self.openTime='162000', self.closeTime='162459', self.symbol='BTCUSDT', self.open=24999.0, self.close=25012.1, self.high=25016.0, self.low=24998.8, self.vol=892.988, self.amt=22333462.1347 
127.0.0.1 - - [15/Jun/2023 16:25:00] "POST / HTTP/1.1" 200 -
2023-06-15 16:25:00,833:INFO:sr_min:main.py:172:handleKline:2219263: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5952  20230615   160000    160459  ...         0.0        0.0       0
5953  20230615   160500    160959  ...         0.0        0.0       0
5954  20230615   161000    161459  ...         0.0        0.0       0
5955  20230615   161500    161959  ...         0.0        0.0       0
5956  20230615   162000    162459  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-06-15 16:25:00,834:INFO:sr_min:main.py:175:handleKline:2219263: self.closeSec=1686817499, self.tradeDate='20230615', self.openTime='162000', self.closeTime='162459',self.symbol='BTCUSDT',self.open=24999.0, self.close=25012.1, self.high=25016.0, self.low=24998.8, self.vol=892.988, self.amt=22333462.1347, ukdf['pct'].iloc[-1]=0.000528 , ukdf['amount'].iloc[-1]=22333462.1347, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5956, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '37.141', 'enterprice': '26844', 'countrevence': '0', 'unrealprofit': '-68164.68606024818', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '25008.70514902', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=1


## /root/FIL/strategy/s_rsrs/log.txt ----- -----

721  20230615   040000    075959  1686787199  ...    721  0.012039 -1.782105    -1.0
722  20230615   080000    115959  1686801599  ...    722  0.109595 -1.395185    -1.0

[5 rows x 15 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '55.166', 'enterprice': '27078.6', 'countrevence': '0', 'unrealprofit': '111650.4674', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '25054.7', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'numpy.int64'>, curSign=-1, self.sign=-1
127.0.0.1 - - [15/Jun/2023 16:00:01] "POST / HTTP/1.1" 200 -
--handleKline--:  version='2.0.0', self.name='s_rsrs', self.symbol='BTCUSDT', interval='4h', intervalSec=14400, wid=25, thd=0.6, self.sign=-1, self.total=1492324.2295523998, self.flagDict['side']='sell', self.tradeCount=4, self.count=193
self.closeSec=1686815999, self.tradeDate='20230615', self.openTime='120000', self.closeTime='155959', self.symbol='BTCUSDT', self.open=25054.8, self.close=24974.6, self.high=25063.4, self.low=24856.0, self.vol=67274.308, self.amt=1680180915.7274 
2023-06-15 16:00:01,828:INFO:s_rsrs:main.py:141:handleKline:2218689: self.closeSec=1686815999, self.tradeDate='20230615', self.openTime='120000', self.closeTime='155959',self.symbol='BTCUSDT',self.open=25054.8, self.close=24974.6, self.high=25063.4, self.low=24856.0, self.vol=67274.308, self.amt=1680180915.7274 
2023-06-15 16:00:01,854:INFO:s_rsrs:main.py:142:handleKline:2218689: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime  ...         vol           amt       pct
719  20230614   200000    235959  ...   41580.783  1.080340e+09  0.000354
720  20230615   000000    035959  ...  105000.310  2.720728e+09 -0.004458
721  20230615   040000    075959  ...  225751.005  5.685134e+09 -0.028797
722  20230615   080000    115959  ...   41759.388  1.048287e+09 -0.002433
723  20230615   120000    155959  ...   67274.308  1.680181e+09 -0.003201

[5 rows x 11 columns]
2023-06-15 16:00:03,102:INFO:s_rsrs:main.py:151:handleKline:2218689: df_s.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec  ...  index      beta    zscore  signal
719  20230614   200000    235959  1686758399  ...    719  0.012297 -1.782169    -1.0
720  20230615   000000    035959  1686772799  ...    720  0.004196 -1.811403    -1.0
721  20230615   040000    075959  1686787199  ...    721  0.012039 -1.782105    -1.0
722  20230615   080000    115959  1686801599  ...    722  0.109595 -1.395185    -1.0
723  20230615   120000    155959  1686815999  ...    723  0.274178 -0.697865    -1.0

[5 rows x 15 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '55.166', 'enterprice': '27078.6', 'countrevence': '0', 'unrealprofit': '116069.264', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '24974.6', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'numpy.int64'>, curSign=-1, self.sign=-1


