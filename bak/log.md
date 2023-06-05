# 20230605 16:26:02

## /root/FIL/strategy/amihud/log.txt ----- -----

--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=373746.4768026, self.flagDict['side']='sell', self.tradeCount=2, self.count=6400
self.closeSec=1685953199, self.tradeDate='20230605', self.openTime='161500', self.closeTime='161959', self.symbol='BTCUSDT', self.open=26819.9, self.close=26818.9, self.high=26820.0, self.low=26813.7, self.vol=359.947, self.amt=9652808.1375 
127.0.0.1 - - [05/Jun/2023 16:20:01] "POST / HTTP/1.1" 200 -
2023-06-05 16:20:07,109:INFO:amihud:main.py:172:handleKline:2219019: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5951  20230605   155500    155959  ...         0.0        0.0       0
5952  20230605   160000    160459  ...         0.0        0.0       0
5953  20230605   160500    160959  ...         0.0        0.0       0
5954  20230605   161000    161459  ...         0.0        0.0       0
5955  20230605   161500    161959  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-06-05 16:20:07,129:INFO:amihud:main.py:175:handleKline:2219019: self.closeSec=1685953199, self.tradeDate='20230605', self.openTime='161500', self.closeTime='161959',self.symbol='BTCUSDT',self.open=26819.9, self.close=26818.9, self.high=26820.0, self.low=26813.7, self.vol=359.947, self.amt=9652808.1375, ukdf['pct'].iloc[-1]=-3.7e-05 , ukdf['amount'].iloc[-1]=9652808.1375, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5955, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '13.926', 'enterprice': '26864.9', 'countrevence': '0', 'unrealprofit': '640.596', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '26818.9', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1
127.0.0.1 - - [05/Jun/2023 16:25:00] "POST / HTTP/1.1" 200 -
--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=373746.4768026, self.flagDict['side']='sell', self.tradeCount=2, self.count=6401
self.closeSec=1685953499, self.tradeDate='20230605', self.openTime='162000', self.closeTime='162459', self.symbol='BTCUSDT', self.open=26819.0, self.close=26791.7, self.high=26819.0, self.low=26790.0, self.vol=772.387, self.amt=20701522.119 
2023-06-05 16:25:00,793:INFO:amihud:main.py:172:handleKline:2219019: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5952  20230605   160000    160459  ...         0.0        0.0       0
5953  20230605   160500    160959  ...         0.0        0.0       0
5954  20230605   161000    161459  ...         0.0        0.0       0
5955  20230605   161500    161959  ...         0.0        0.0       0
5956  20230605   162000    162459  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-06-05 16:25:00,793:INFO:amihud:main.py:175:handleKline:2219019: self.closeSec=1685953499, self.tradeDate='20230605', self.openTime='162000', self.closeTime='162459',self.symbol='BTCUSDT',self.open=26819.0, self.close=26791.7, self.high=26819.0, self.low=26790.0, self.vol=772.387, self.amt=20701522.119, ukdf['pct'].iloc[-1]=-0.001014 , ukdf['amount'].iloc[-1]=20701522.119, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5956, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '13.926', 'enterprice': '26864.9', 'countrevence': '0', 'unrealprofit': '1015.40743019166', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '26791.98549259', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1


## /root/FIL/strategy/factorcheck/log.txt ----- -----


self.closeSec=1685953199, self.tradeDate='20230605', self.openTime='161500', self.closeTime='161959', self.symbol='BTCUSDT', self.open=26819.9, self.close=26818.9, self.high=26820.0, self.low=26813.7 
127.0.0.1 - - [05/Jun/2023 16:20:01] "POST / HTTP/1.1" 200 -
2023-06-05 16:20:04,714:INFO:factorcheck2:main.py:126:handleKline:2218005: self.closeSec=1685953199, self.tradeDate='20230605', self.openTime='161500', self.closeTime='161959',self.symbol='BTCUSDT',self.open=26819.9, self.close=26818.9, self.high=26820.0, self.low=26813.7   
2023-06-05 16:20:06,086:INFO:factorcheck2:main.py:127:handleKline:2218005: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime    closeSec  ...      low       pct  index  idx
1631  20230605   155500    155959  1685951999  ...  26805.8  0.000388   1631    5
1632  20230605   160000    160459  1685952299  ...  26810.0  0.000321   1632    0
1633  20230605   160500    160959  1685952599  ...  26811.2 -0.000317   1633    1
1634  20230605   161000    161459  1685952899  ...  26815.3  0.000022   1634    2
1635  20230605   161500    161959  1685953199  ...  26813.7 -0.000037   1635    3

[5 rows x 11 columns]
2023-06-05 16:20:06,094:INFO:factorcheck2:main.py:128:handleKline:2218005: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': True, 'isOpenSell': False, 'isCloseBuy': False, 'isCloseSell': False, 'isOpen': True, 'isClose': False, 'isTrig': True}
127.0.0.1 - - [05/Jun/2023 16:25:00] "POST / HTTP/1.1" 200 -

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=0, self.factor=0.610620448872727, self.count=6403 

self.closeSec=1685953499, self.tradeDate='20230605', self.openTime='162000', self.closeTime='162459', self.symbol='BTCUSDT', self.open=26819.0, self.close=26791.7, self.high=26819.0, self.low=26790.0 
2023-06-05 16:25:00,740:INFO:factorcheck2:main.py:126:handleKline:2218005: self.closeSec=1685953499, self.tradeDate='20230605', self.openTime='162000', self.closeTime='162459',self.symbol='BTCUSDT',self.open=26819.0, self.close=26791.7, self.high=26819.0, self.low=26790.0   
2023-06-05 16:25:00,780:INFO:factorcheck2:main.py:127:handleKline:2218005: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime    closeSec  ...      low       pct  index  idx
1632  20230605   160000    160459  1685952299  ...  26810.0  0.000321   1632    0
1633  20230605   160500    160959  1685952599  ...  26811.2 -0.000317   1633    1
1634  20230605   161000    161459  1685952899  ...  26815.3  0.000022   1634    2
1635  20230605   161500    161959  1685953199  ...  26813.7 -0.000037   1635    3
1636  20230605   162000    162459  1685953499  ...  26790.0 -0.001014   1636    4

[5 rows x 11 columns]
2023-06-05 16:25:00,780:INFO:factorcheck2:main.py:128:handleKline:2218005: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': True, 'isOpenSell': False, 'isCloseBuy': False, 'isCloseSell': False, 'isOpen': True, 'isClose': False, 'isTrig': True}


## /root/FIL/strategy/logic/log.txt ----- -----

2023-06-05 16:00:35,831:DEBUG:logic:main.py:463:getModel:2218526: df_s.iloc[-5:,:] :
          date closeTime     open  ...    alpha58   alpha67   alpha72
5786  20230605    132959  26832.0  ...  47.500000  0.401159  0.637347
5787  20230605    135959  26809.0  ...  47.500000  0.400914  0.653588
5788  20230605    142959  26808.1  ...  47.083333  0.399645  0.669160
5789  20230605    145959  26803.5  ...  46.666667  0.387432  0.687739
5790  20230605    152959  26758.6  ...  46.666667  0.411741  0.699720

[5 rows x 33 columns]
0.533210332103321
acc is : 0.533210332103321
2023-06-05 16:00:35,992:INFO:logic:main.py:468:getModel:2218526: df_pred.iloc[-5:,:] :
     pred    prob_0    prob_1  actual  ...       nav  sign  cost_        bm
537     1  0.489322  0.510678       0  ...  1.026423   1.0    0.0  1.022106
538     1  0.496919  0.503081       0  ...  1.026247   1.0    0.0  1.021931
539     0  0.500143  0.499857       0  ...  1.024528   1.0    0.0  1.020219
540     1  0.490822  0.509178       1  ...  1.026806   1.0    0.0  1.022487
541     0  0.512793  0.487207       1  ...  1.026852   1.0    0.0  1.022533

[5 rows x 10 columns]
2023-06-05 16:00:36,033:INFO:logic:main.py:478:getModel:2218526: df_panel.iloc[-5:,:] :
    pred    prob_0    prob_1  actual  ...       nav  sign  cost_        bm
45     1  0.488949  0.511051       0  ...  1.026423   1.0    0.0  1.017876
46     1  0.496911  0.503089       0  ...  1.026247   1.0    0.0  1.018564
47     0  0.500062  0.499938       0  ...  1.024528   1.0    0.0  1.016900
48     1  0.490843  0.509157       1  ...  1.026806   1.0    0.0  1.020623
49     0  0.512793  0.487207       1  ...  1.026852   1.0    0.0  1.022533

[5 rows x 10 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '27.623', 'enterprice': '26988.6', 'countrevence': '0', 'unrealprofit': '-4792.5905', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '26815.1', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}


## /root/FIL/strategy/modifiedmom/log.txt ----- -----

527  20230605   155000    155959  1685951999  26812.5  26819.2  0.000250
2023-06-05 16:00:02,199:INFO:modifiedmom:main.py:146:handleKline:2218259: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': True, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True}
127.0.0.1 - - [05/Jun/2023 16:10:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=3200 

self.closeSec=1685952599, self.tradeDate='20230605', self.openTime='160000', self.closeTime='160959', self.symbol='BTCUSDT', self.open='26819.2', self.close='26819.3'
2023-06-05 16:10:01,119:INFO:modifiedmom:main.py:144:handleKline:2218259: self.closeSec=1685952599, self.tradeDate='20230605', self.openTime='160000', self.closeTime='160959',self.symbol='BTCUSDT',self.open='26819.2', self.close='26819.3'
2023-06-05 16:10:01,150:INFO:modifiedmom:main.py:145:handleKline:2218259: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec     open    close       pct
524  20230605   152000    152959  1685950199  26799.6  26817.9  0.000683
525  20230605   153000    153959  1685950799    26818  26815.6 -0.000086
526  20230605   154000    154959  1685951399  26815.6  26812.5 -0.000116
527  20230605   155000    155959  1685951999  26812.5  26819.2  0.000250
528  20230605   160000    160959  1685952599  26819.2  26819.3  0.000004
2023-06-05 16:10:01,150:INFO:modifiedmom:main.py:146:handleKline:2218259: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': True, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True}

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=3201 

self.closeSec=1685953199, self.tradeDate='20230605', self.openTime='161000', self.closeTime='161959', self.symbol='BTCUSDT', self.open='26819.3', self.close='26818.9'
127.0.0.1 - - [05/Jun/2023 16:20:04] "POST / HTTP/1.1" 200 -
2023-06-05 16:20:07,079:INFO:modifiedmom:main.py:144:handleKline:2218259: self.closeSec=1685953199, self.tradeDate='20230605', self.openTime='161000', self.closeTime='161959',self.symbol='BTCUSDT',self.open='26819.3', self.close='26818.9'
2023-06-05 16:20:07,821:INFO:modifiedmom:main.py:145:handleKline:2218259: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec     open    close       pct
525  20230605   153000    153959  1685950799    26818  26815.6 -0.000086
526  20230605   154000    154959  1685951399  26815.6  26812.5 -0.000116
527  20230605   155000    155959  1685951999  26812.5  26819.2  0.000250
528  20230605   160000    160959  1685952599  26819.2  26819.3  0.000004
529  20230605   161000    161959  1685953199  26819.3  26818.9 -0.000015
2023-06-05 16:20:07,828:INFO:modifiedmom:main.py:146:handleKline:2218259: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': True, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True}


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

17519  20230605   155000    155959  1685951999  26812.5  26819.2
2023-06-05 16:00:02,224:INFO:pyemd2:main.py:127:handleKline:2217508: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}
127.0.0.1 - - [05/Jun/2023 16:10:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=3203 

self.closeSec=1685952599, self.tradeDate='20230605', self.openTime='160000', self.closeTime='160959', self.symbol='BTCUSDT', self.open='26819.2', self.close='26819.3'
2023-06-05 16:10:01,126:INFO:pyemd2:main.py:125:handleKline:2217508: self.closeSec=1685952599, self.tradeDate='20230605', self.openTime='160000', self.closeTime='160959',self.symbol='BTCUSDT',self.open='26819.2', self.close='26819.3'
2023-06-05 16:10:01,165:INFO:pyemd2:main.py:126:handleKline:2217508: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
17516  20230605   152000    152959  1685950199  26799.6  26817.9
17517  20230605   153000    153959  1685950799    26818  26815.6
17518  20230605   154000    154959  1685951399  26815.6  26812.5
17519  20230605   155000    155959  1685951999  26812.5  26819.2
17520  20230605   160000    160959  1685952599  26819.2  26819.3
2023-06-05 16:10:01,165:INFO:pyemd2:main.py:127:handleKline:2217508: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=3204 

self.closeSec=1685953199, self.tradeDate='20230605', self.openTime='161000', self.closeTime='161959', self.symbol='BTCUSDT', self.open='26819.3', self.close='26818.9'
127.0.0.1 - - [05/Jun/2023 16:20:04] "POST / HTTP/1.1" 200 -
2023-06-05 16:20:08,741:INFO:pyemd2:main.py:125:handleKline:2217508: self.closeSec=1685953199, self.tradeDate='20230605', self.openTime='161000', self.closeTime='161959',self.symbol='BTCUSDT',self.open='26819.3', self.close='26818.9'
2023-06-05 16:20:08,883:INFO:pyemd2:main.py:126:handleKline:2217508: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
17517  20230605   153000    153959  1685950799    26818  26815.6
17518  20230605   154000    154959  1685951399  26815.6  26812.5
17519  20230605   155000    155959  1685951999  26812.5  26819.2
17520  20230605   160000    160959  1685952599  26819.2  26819.3
17521  20230605   161000    161959  1685953199  26819.3  26818.9
2023-06-05 16:20:08,883:INFO:pyemd2:main.py:127:handleKline:2217508: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}


## /root/FIL/strategy/similarity/log.txt ----- -----

12191  20230605   155000    155959  1685951999  26812.5  26819.2
2023-06-05 16:00:02,214:INFO:testStrategy:main.py:103:handleKline:2217133: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': True, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True, 'isCorr': False}

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=3203 

self.closeSec=1685952599, self.tradeDate='20230605', self.openTime='160000', self.closeTime='160959', self.symbol='BTCUSDT', self.open='26819.2', self.close='26819.3'
2023-06-05 16:10:01,145:INFO:testStrategy:main.py:101:handleKline:2217133: self.closeSec=1685952599, self.tradeDate='20230605', self.openTime='160000', self.closeTime='160959',self.symbol='BTCUSDT',self.open='26819.2', self.close='26819.3'
127.0.0.1 - - [05/Jun/2023 16:10:01] "POST / HTTP/1.1" 200 -
2023-06-05 16:10:01,171:INFO:testStrategy:main.py:102:handleKline:2217133: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
12188  20230605   152000    152959  1685950199  26799.6  26817.9
12189  20230605   153000    153959  1685950799    26818  26815.6
12190  20230605   154000    154959  1685951399  26815.6  26812.5
12191  20230605   155000    155959  1685951999  26812.5  26819.2
12192  20230605   160000    160959  1685952599  26819.2  26819.3
2023-06-05 16:10:01,173:INFO:testStrategy:main.py:103:handleKline:2217133: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': True, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True, 'isCorr': False}

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=3204 

self.closeSec=1685953199, self.tradeDate='20230605', self.openTime='161000', self.closeTime='161959', self.symbol='BTCUSDT', self.open='26819.3', self.close='26818.9'
127.0.0.1 - - [05/Jun/2023 16:20:04] "POST / HTTP/1.1" 200 -
2023-06-05 16:20:08,510:INFO:testStrategy:main.py:101:handleKline:2217133: self.closeSec=1685953199, self.tradeDate='20230605', self.openTime='161000', self.closeTime='161959',self.symbol='BTCUSDT',self.open='26819.3', self.close='26818.9'
2023-06-05 16:20:08,720:INFO:testStrategy:main.py:102:handleKline:2217133: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
12189  20230605   153000    153959  1685950799    26818  26815.6
12190  20230605   154000    154959  1685951399  26815.6  26812.5
12191  20230605   155000    155959  1685951999  26812.5  26819.2
12192  20230605   160000    160959  1685952599  26819.2  26819.3
12193  20230605   161000    161959  1685953199  26819.3  26818.9
2023-06-05 16:20:08,721:INFO:testStrategy:main.py:103:handleKline:2217133: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': True, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True, 'isCorr': False}


## /root/FIL/strategy/sr_min/log.txt ----- -----

--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=1, self.total=996015.990996, self.flagDict['side']='buy', self.tradeCount=1, self.count=6400
self.closeSec=1685953199, self.tradeDate='20230605', self.openTime='161500', self.closeTime='161959', self.symbol='BTCUSDT', self.open=26819.9, self.close=26818.9, self.high=26820.0, self.low=26813.7, self.vol=359.947, self.amt=9652808.1375 
127.0.0.1 - - [05/Jun/2023 16:20:01] "POST / HTTP/1.1" 200 -
2023-06-05 16:20:07,029:INFO:sr_min:main.py:172:handleKline:2219263: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5951  20230605   155500    155959  ...         0.0        0.0       0
5952  20230605   160000    160459  ...         0.0        0.0       0
5953  20230605   160500    160959  ...         0.0        0.0       0
5954  20230605   161000    161459  ...         0.0        0.0       0
5955  20230605   161500    161959  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-06-05 16:20:07,060:INFO:sr_min:main.py:175:handleKline:2219263: self.closeSec=1685953199, self.tradeDate='20230605', self.openTime='161500', self.closeTime='161959',self.symbol='BTCUSDT',self.open=26819.9, self.close=26818.9, self.high=26820.0, self.low=26813.7, self.vol=359.947, self.amt=9652808.1375, ukdf['pct'].iloc[-1]=-3.7e-05 , ukdf['amount'].iloc[-1]=9652808.1375, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5955, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '37.141', 'enterprice': '26844', 'countrevence': '0', 'unrealprofit': '-932.2391', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '26818.9', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=1
127.0.0.1 - - [05/Jun/2023 16:25:00] "POST / HTTP/1.1" 200 -
--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=1, self.total=996015.990996, self.flagDict['side']='buy', self.tradeCount=1, self.count=6401
self.closeSec=1685953499, self.tradeDate='20230605', self.openTime='162000', self.closeTime='162459', self.symbol='BTCUSDT', self.open=26819.0, self.close=26791.7, self.high=26819.0, self.low=26790.0, self.vol=772.387, self.amt=20701522.119 
2023-06-05 16:25:00,790:INFO:sr_min:main.py:172:handleKline:2219263: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5952  20230605   160000    160459  ...         0.0        0.0       0
5953  20230605   160500    160959  ...         0.0        0.0       0
5954  20230605   161000    161459  ...         0.0        0.0       0
5955  20230605   161500    161959  ...         0.0        0.0       0
5956  20230605   162000    162459  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-06-05 16:25:00,790:INFO:sr_min:main.py:175:handleKline:2219263: self.closeSec=1685953499, self.tradeDate='20230605', self.openTime='162000', self.closeTime='162459',self.symbol='BTCUSDT',self.open=26819.0, self.close=26791.7, self.high=26819.0, self.low=26790.0, self.vol=772.387, self.amt=20701522.119, ukdf['pct'].iloc[-1]=-0.001014 , ukdf['amount'].iloc[-1]=20701522.119, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5956, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '37.141', 'enterprice': '26844', 'countrevence': '0', 'unrealprofit': '-1931.87081971481', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '26791.98549259', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=1


## /root/FIL/strategy/s_rsrs/log.txt ----- -----

721  20230605   040000    075959  1685923199  ...    721  0.045863 -1.488578    -1.0
722  20230605   080000    115959  1685937599  ...    722  0.044106 -1.480460    -1.0

[5 rows x 15 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '55.166', 'enterprice': '27078.6', 'countrevence': '0', 'unrealprofit': '14013.65695525136', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '26824.57293704', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'numpy.int64'>, curSign=-1, self.sign=-1
127.0.0.1 - - [05/Jun/2023 16:00:01] "POST / HTTP/1.1" 200 -
--handleKline--:  version='2.0.0', self.name='s_rsrs', self.symbol='BTCUSDT', interval='4h', intervalSec=14400, wid=25, thd=0.6, self.sign=-1, self.total=1492324.2295523998, self.flagDict['side']='sell', self.tradeCount=4, self.count=133
self.closeSec=1685951999, self.tradeDate='20230605', self.openTime='120000', self.closeTime='155959', self.symbol='BTCUSDT', self.open=26835.8, self.close=26819.2, self.high=26861.4, self.low=26719.9, self.vol=52410.386, self.amt=1404438584.942 
2023-06-05 16:00:01,760:INFO:s_rsrs:main.py:141:handleKline:2218689: self.closeSec=1685951999, self.tradeDate='20230605', self.openTime='120000', self.closeTime='155959',self.symbol='BTCUSDT',self.open=26835.8, self.close=26819.2, self.high=26861.4, self.low=26719.9, self.vol=52410.386, self.amt=1404438584.942 
2023-06-05 16:00:01,797:INFO:s_rsrs:main.py:142:handleKline:2218689: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime  ...        vol           amt       pct
719  20230604   200000    235959  ...  38245.649  1.040603e+09 -0.000883
720  20230605   000000    035959  ...  17756.474  4.826483e+08  0.001402
721  20230605   040000    075959  ...  83709.147  2.280936e+09 -0.003771
722  20230605   080000    115959  ...  80451.139  2.167862e+09 -0.009833
723  20230605   120000    155959  ...  52410.386  1.404439e+09 -0.000622

[5 rows x 11 columns]
2023-06-05 16:00:03,627:INFO:s_rsrs:main.py:151:handleKline:2218689: df_s.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec  ...  index      beta    zscore  signal
719  20230604   200000    235959  1685894399  ...    719  0.040939 -1.528777    -1.0
720  20230605   000000    035959  1685908799  ...    720  0.041719 -1.513107    -1.0
721  20230605   040000    075959  1685923199  ...    721  0.045863 -1.488578    -1.0
722  20230605   080000    115959  1685937599  ...    722  0.044106 -1.480460    -1.0
723  20230605   120000    155959  1685951999  ...    723  0.159485 -1.142144    -1.0

[5 rows x 15 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '55.166', 'enterprice': '27078.6', 'countrevence': '0', 'unrealprofit': '14310.0604', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '26819.2', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'numpy.int64'>, curSign=-1, self.sign=-1


