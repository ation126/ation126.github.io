# 20230603 16:26:01

## /root/FIL/strategy/amihud/log.txt ----- -----

--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=373746.4768026, self.flagDict['side']='sell', self.tradeCount=2, self.count=5824
self.closeSec=1685780399, self.tradeDate='20230603', self.openTime='161500', self.closeTime='161959', self.symbol='BTCUSDT', self.open=27167.2, self.close=27170.1, self.high=27171.2, self.low=27162.6, self.vol=271.125, self.amt=7365954.6143 
127.0.0.1 - - [03/Jun/2023 16:20:01] "POST / HTTP/1.1" 200 -
2023-06-03 16:20:06,774:INFO:amihud:main.py:172:handleKline:2219019: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5951  20230603   155500    155959  ...         0.0        0.0       0
5952  20230603   160000    160459  ...         0.0        0.0       0
5953  20230603   160500    160959  ...         0.0        0.0       0
5954  20230603   161000    161459  ...         0.0        0.0       0
5955  20230603   161500    161959  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-06-03 16:20:06,795:INFO:amihud:main.py:175:handleKline:2219019: self.closeSec=1685780399, self.tradeDate='20230603', self.openTime='161500', self.closeTime='161959',self.symbol='BTCUSDT',self.open=27167.2, self.close=27170.1, self.high=27171.2, self.low=27162.6, self.vol=271.125, self.amt=7365954.6143, ukdf['pct'].iloc[-1]=0.000107 , ukdf['amount'].iloc[-1]=7365954.6143, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5955, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '13.926', 'enterprice': '26864.9', 'countrevence': '0', 'unrealprofit': '-4250.2152', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '27170.1', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1
--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=373746.4768026, self.flagDict['side']='sell', self.tradeCount=2, self.count=5825
self.closeSec=1685780699, self.tradeDate='20230603', self.openTime='162000', self.closeTime='162459', self.symbol='BTCUSDT', self.open=27170.1, self.close=27169.2, self.high=27170.1, self.low=27169.2, self.vol=121.25, self.amt=3294290.2759 
127.0.0.1 - - [03/Jun/2023 16:25:00] "POST / HTTP/1.1" 200 -
2023-06-03 16:25:00,830:INFO:amihud:main.py:172:handleKline:2219019: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5952  20230603   160000    160459  ...         0.0        0.0       0
5953  20230603   160500    160959  ...         0.0        0.0       0
5954  20230603   161000    161459  ...         0.0        0.0       0
5955  20230603   161500    161959  ...         0.0        0.0       0
5956  20230603   162000    162459  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-06-03 16:25:00,831:INFO:amihud:main.py:175:handleKline:2219019: self.closeSec=1685780699, self.tradeDate='20230603', self.openTime='162000', self.closeTime='162459',self.symbol='BTCUSDT',self.open=27170.1, self.close=27169.2, self.high=27170.1, self.low=27169.2, self.vol=121.25, self.amt=3294290.2759, ukdf['pct'].iloc[-1]=-3.3e-05 , ukdf['amount'].iloc[-1]=3294290.2759, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5956, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '13.926', 'enterprice': '26864.9', 'countrevence': '0', 'unrealprofit': '-4240.59453096576', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '27169.40915776', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1


## /root/FIL/strategy/factorcheck/log.txt ----- -----


self.closeSec=1685780399, self.tradeDate='20230603', self.openTime='161500', self.closeTime='161959', self.symbol='BTCUSDT', self.open=27167.2, self.close=27170.1, self.high=27171.2, self.low=27162.6 
127.0.0.1 - - [03/Jun/2023 16:20:01] "POST / HTTP/1.1" 200 -
2023-06-03 16:20:04,465:INFO:factorcheck2:main.py:126:handleKline:2218005: self.closeSec=1685780399, self.tradeDate='20230603', self.openTime='161500', self.closeTime='161959',self.symbol='BTCUSDT',self.open=27167.2, self.close=27170.1, self.high=27171.2, self.low=27162.6   
2023-06-03 16:20:05,865:INFO:factorcheck2:main.py:127:handleKline:2218005: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime    closeSec  ...      low       pct  index  idx
1631  20230603   155500    155959  1685779199  ...  27158.4 -0.000022   1631    5
1632  20230603   160000    160459  1685779499  ...  27157.4  0.000018   1632    0
1633  20230603   160500    160959  1685779799  ...  27161.7  0.000331   1633    1
1634  20230603   161000    161459  1685780099  ...  27167.1 -0.000132   1634    2
1635  20230603   161500    161959  1685780399  ...  27162.6  0.000107   1635    3

[5 rows x 11 columns]
2023-06-03 16:20:05,876:INFO:factorcheck2:main.py:128:handleKline:2218005: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=3, self.factor=0.32377588950160213, self.count=5827 

self.closeSec=1685780699, self.tradeDate='20230603', self.openTime='162000', self.closeTime='162459', self.symbol='BTCUSDT', self.open=27170.1, self.close=27169.2, self.high=27170.1, self.low=27169.2 
127.0.0.1 - - [03/Jun/2023 16:25:00] "POST / HTTP/1.1" 200 -
2023-06-03 16:25:00,770:INFO:factorcheck2:main.py:126:handleKline:2218005: self.closeSec=1685780699, self.tradeDate='20230603', self.openTime='162000', self.closeTime='162459',self.symbol='BTCUSDT',self.open=27170.1, self.close=27169.2, self.high=27170.1, self.low=27169.2   
2023-06-03 16:25:00,811:INFO:factorcheck2:main.py:127:handleKline:2218005: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime    closeSec  ...      low       pct  index  idx
1632  20230603   160000    160459  1685779499  ...  27157.4  0.000018   1632    0
1633  20230603   160500    160959  1685779799  ...  27161.7  0.000331   1633    1
1634  20230603   161000    161459  1685780099  ...  27167.1 -0.000132   1634    2
1635  20230603   161500    161959  1685780399  ...  27162.6  0.000107   1635    3
1636  20230603   162000    162459  1685780699  ...  27169.2 -0.000033   1636    4

[5 rows x 11 columns]
2023-06-03 16:25:00,811:INFO:factorcheck2:main.py:128:handleKline:2218005: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}


## /root/FIL/strategy/logic/log.txt ----- -----

2023-06-03 16:00:35,597:DEBUG:logic:main.py:463:getModel:2218526: df_s.iloc[-5:,:] :
          date closeTime     open  ...    alpha58   alpha67   alpha72
5786  20230603    132959  27151.1  ...  47.500000  0.513921  0.274587
5787  20230603    135959  27142.1  ...  47.916667  0.515611  0.277194
5788  20230603    142959  27149.0  ...  47.916667  0.524593  0.274257
5789  20230603    145959  27185.3  ...  47.916667  0.520296  0.273860
5790  20230603    152959  27169.4  ...  47.916667  0.519225  0.274068

[5 rows x 33 columns]
0.511070110701107
acc is : 0.511070110701107
2023-06-03 16:00:35,764:INFO:logic:main.py:468:getModel:2218526: df_pred.iloc[-5:,:] :
     pred    prob_0    prob_1  actual  ...       nav  sign  cost_        bm
537     1  0.493439  0.506561       1  ...  1.020491   1.0    0.0  1.012437
538     1  0.498695  0.501305       1  ...  1.021852   1.0    0.0  1.013787
539     0  0.506464  0.493536       0  ...  1.021258   1.0    0.0  1.013198
540     1  0.498679  0.501321       0  ...  1.021112   1.0    0.0  1.013052
541     1  0.496680  0.503320       0  ...  1.020954   1.0    0.0  1.012896

[5 rows x 10 columns]
2023-06-03 16:00:35,798:INFO:logic:main.py:478:getModel:2218526: df_panel.iloc[-5:,:] :
    pred    prob_0    prob_1  actual  ...       nav  sign  cost_        bm
45     1  0.493456  0.506544       1  ...  1.020491   1.0    0.0  1.010854
46     1  0.498819  0.501181       1  ...  1.021852   1.0    0.0  1.012801
47     0  0.506453  0.493547       0  ...  1.021258   1.0    0.0  1.012265
48     1  0.498578  0.501422       0  ...  1.021112   1.0    0.0  1.010790
49     1  0.496680  0.503320       0  ...  1.020954   1.0    0.0  1.012896

[5 rows x 10 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '27.623', 'enterprice': '26988.6', 'countrevence': '0', 'unrealprofit': '4784.86475599663', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '27161.82031481', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}


## /root/FIL/strategy/modifiedmom/log.txt ----- -----

527  20230603   155000    155959  1685779199  27155.9  27161.3  0.000203
2023-06-03 16:00:02,322:INFO:modifiedmom:main.py:146:handleKline:2218259: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': True, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True}
127.0.0.1 - - [03/Jun/2023 16:10:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=2912 

self.closeSec=1685779799, self.tradeDate='20230603', self.openTime='160000', self.closeTime='160959', self.symbol='BTCUSDT', self.open='27161.4', self.close='27170.8'
2023-06-03 16:10:01,098:INFO:modifiedmom:main.py:144:handleKline:2218259: self.closeSec=1685779799, self.tradeDate='20230603', self.openTime='160000', self.closeTime='160959',self.symbol='BTCUSDT',self.open='27161.4', self.close='27170.8'
2023-06-03 16:10:01,150:INFO:modifiedmom:main.py:145:handleKline:2218259: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec     open    close       pct
524  20230603   152000    152959  1685777399    27178  27165.5 -0.000464
525  20230603   153000    153959  1685777999  27165.6  27177.1  0.000427
526  20230603   154000    154959  1685778599  27177.2  27155.8 -0.000784
527  20230603   155000    155959  1685779199  27155.9  27161.3  0.000203
528  20230603   160000    160959  1685779799  27161.4  27170.8  0.000350
2023-06-03 16:10:01,150:INFO:modifiedmom:main.py:146:handleKline:2218259: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': True, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True}

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=2913 

self.closeSec=1685780399, self.tradeDate='20230603', self.openTime='161000', self.closeTime='161959', self.symbol='BTCUSDT', self.open='27170.8', self.close='27170'
127.0.0.1 - - [03/Jun/2023 16:20:04] "POST / HTTP/1.1" 200 -
2023-06-03 16:20:07,083:INFO:modifiedmom:main.py:144:handleKline:2218259: self.closeSec=1685780399, self.tradeDate='20230603', self.openTime='161000', self.closeTime='161959',self.symbol='BTCUSDT',self.open='27170.8', self.close='27170'
2023-06-03 16:20:07,675:INFO:modifiedmom:main.py:145:handleKline:2218259: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec     open    close       pct
525  20230603   153000    153959  1685777999  27165.6  27177.1  0.000427
526  20230603   154000    154959  1685778599  27177.2  27155.8 -0.000784
527  20230603   155000    155959  1685779199  27155.9  27161.3  0.000203
528  20230603   160000    160959  1685779799  27161.4  27170.8  0.000350
529  20230603   161000    161959  1685780399  27170.8    27170 -0.000029
2023-06-03 16:20:07,676:INFO:modifiedmom:main.py:146:handleKline:2218259: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': True, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True}


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

17519  20230603   155000    155959  1685779199  27155.9  27161.3
2023-06-03 16:00:02,300:INFO:pyemd2:main.py:127:handleKline:2217508: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}
127.0.0.1 - - [03/Jun/2023 16:10:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=2915 

self.closeSec=1685779799, self.tradeDate='20230603', self.openTime='160000', self.closeTime='160959', self.symbol='BTCUSDT', self.open='27161.4', self.close='27170.8'
2023-06-03 16:10:01,128:INFO:pyemd2:main.py:125:handleKline:2217508: self.closeSec=1685779799, self.tradeDate='20230603', self.openTime='160000', self.closeTime='160959',self.symbol='BTCUSDT',self.open='27161.4', self.close='27170.8'
2023-06-03 16:10:01,159:INFO:pyemd2:main.py:126:handleKline:2217508: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
17516  20230603   152000    152959  1685777399    27178  27165.5
17517  20230603   153000    153959  1685777999  27165.6  27177.1
17518  20230603   154000    154959  1685778599  27177.2  27155.8
17519  20230603   155000    155959  1685779199  27155.9  27161.3
17520  20230603   160000    160959  1685779799  27161.4  27170.8
2023-06-03 16:10:01,159:INFO:pyemd2:main.py:127:handleKline:2217508: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=2916 

self.closeSec=1685780399, self.tradeDate='20230603', self.openTime='161000', self.closeTime='161959', self.symbol='BTCUSDT', self.open='27170.8', self.close='27170'
127.0.0.1 - - [03/Jun/2023 16:20:04] "POST / HTTP/1.1" 200 -
2023-06-03 16:20:08,548:INFO:pyemd2:main.py:125:handleKline:2217508: self.closeSec=1685780399, self.tradeDate='20230603', self.openTime='161000', self.closeTime='161959',self.symbol='BTCUSDT',self.open='27170.8', self.close='27170'
2023-06-03 16:20:08,699:INFO:pyemd2:main.py:126:handleKline:2217508: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
17517  20230603   153000    153959  1685777999  27165.6  27177.1
17518  20230603   154000    154959  1685778599  27177.2  27155.8
17519  20230603   155000    155959  1685779199  27155.9  27161.3
17520  20230603   160000    160959  1685779799  27161.4  27170.8
17521  20230603   161000    161959  1685780399  27170.8    27170
2023-06-03 16:20:08,701:INFO:pyemd2:main.py:127:handleKline:2217508: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}


## /root/FIL/strategy/similarity/log.txt ----- -----

12191  20230603   155000    155959  1685779199  27155.9  27161.3
2023-06-03 16:00:02,310:INFO:testStrategy:main.py:103:handleKline:2217133: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': True, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True, 'isCorr': False}
127.0.0.1 - - [03/Jun/2023 16:10:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=2915 

self.closeSec=1685779799, self.tradeDate='20230603', self.openTime='160000', self.closeTime='160959', self.symbol='BTCUSDT', self.open='27161.4', self.close='27170.8'
2023-06-03 16:10:01,124:INFO:testStrategy:main.py:101:handleKline:2217133: self.closeSec=1685779799, self.tradeDate='20230603', self.openTime='160000', self.closeTime='160959',self.symbol='BTCUSDT',self.open='27161.4', self.close='27170.8'
2023-06-03 16:10:01,153:INFO:testStrategy:main.py:102:handleKline:2217133: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
12188  20230603   152000    152959  1685777399    27178  27165.5
12189  20230603   153000    153959  1685777999  27165.6  27177.1
12190  20230603   154000    154959  1685778599  27177.2  27155.8
12191  20230603   155000    155959  1685779199  27155.9  27161.3
12192  20230603   160000    160959  1685779799  27161.4  27170.8
2023-06-03 16:10:01,155:INFO:testStrategy:main.py:103:handleKline:2217133: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': True, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True, 'isCorr': False}

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=2916 

self.closeSec=1685780399, self.tradeDate='20230603', self.openTime='161000', self.closeTime='161959', self.symbol='BTCUSDT', self.open='27170.8', self.close='27170'
127.0.0.1 - - [03/Jun/2023 16:20:04] "POST / HTTP/1.1" 200 -
2023-06-03 16:20:08,276:INFO:testStrategy:main.py:101:handleKline:2217133: self.closeSec=1685780399, self.tradeDate='20230603', self.openTime='161000', self.closeTime='161959',self.symbol='BTCUSDT',self.open='27170.8', self.close='27170'
2023-06-03 16:20:08,513:INFO:testStrategy:main.py:102:handleKline:2217133: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
12189  20230603   153000    153959  1685777999  27165.6  27177.1
12190  20230603   154000    154959  1685778599  27177.2  27155.8
12191  20230603   155000    155959  1685779199  27155.9  27161.3
12192  20230603   160000    160959  1685779799  27161.4  27170.8
12193  20230603   161000    161959  1685780399  27170.8    27170
2023-06-03 16:20:08,514:INFO:testStrategy:main.py:103:handleKline:2217133: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': True, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True, 'isCorr': False}


## /root/FIL/strategy/sr_min/log.txt ----- -----

--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=1, self.total=996015.990996, self.flagDict['side']='buy', self.tradeCount=1, self.count=5824
self.closeSec=1685780399, self.tradeDate='20230603', self.openTime='161500', self.closeTime='161959', self.symbol='BTCUSDT', self.open=27167.2, self.close=27170.1, self.high=27171.2, self.low=27162.6, self.vol=271.125, self.amt=7365954.6143 
127.0.0.1 - - [03/Jun/2023 16:20:01] "POST / HTTP/1.1" 200 -
2023-06-03 16:20:06,745:INFO:sr_min:main.py:172:handleKline:2219263: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5951  20230603   155500    155959  ...         0.0        0.0       0
5952  20230603   160000    160459  ...         0.0        0.0       0
5953  20230603   160500    160959  ...         0.0        0.0       0
5954  20230603   161000    161459  ...         0.0        0.0       0
5955  20230603   161500    161959  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-06-03 16:20:06,765:INFO:sr_min:main.py:175:handleKline:2219263: self.closeSec=1685780399, self.tradeDate='20230603', self.openTime='161500', self.closeTime='161959',self.symbol='BTCUSDT',self.open=27167.2, self.close=27170.1, self.high=27171.2, self.low=27162.6, self.vol=271.125, self.amt=7365954.6143, ukdf['pct'].iloc[-1]=0.000107 , ukdf['amount'].iloc[-1]=7365954.6143, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5955, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '37.141', 'enterprice': '26844', 'countrevence': '0', 'unrealprofit': '12111.6801', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '27170.1', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=1
--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=1, self.total=996015.990996, self.flagDict['side']='buy', self.tradeCount=1, self.count=5825
self.closeSec=1685780699, self.tradeDate='20230603', self.openTime='162000', self.closeTime='162459', self.symbol='BTCUSDT', self.open=27170.1, self.close=27169.2, self.high=27170.1, self.low=27169.2, self.vol=121.25, self.amt=3294290.2759 
127.0.0.1 - - [03/Jun/2023 16:25:00] "POST / HTTP/1.1" 200 -
2023-06-03 16:25:00,833:INFO:sr_min:main.py:172:handleKline:2219263: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5952  20230603   160000    160459  ...         0.0        0.0       0
5953  20230603   160500    160959  ...         0.0        0.0       0
5954  20230603   161000    161459  ...         0.0        0.0       0
5955  20230603   161500    161959  ...         0.0        0.0       0
5956  20230603   162000    162459  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-06-03 16:25:00,833:INFO:sr_min:main.py:175:handleKline:2219263: self.closeSec=1685780699, self.tradeDate='20230603', self.openTime='162000', self.closeTime='162459',self.symbol='BTCUSDT',self.open=27170.1, self.close=27169.2, self.high=27170.1, self.low=27169.2, self.vol=121.25, self.amt=3294290.2759, ukdf['pct'].iloc[-1]=-3.3e-05 , ukdf['amount'].iloc[-1]=3294290.2759, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5956, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '37.141', 'enterprice': '26844', 'countrevence': '0', 'unrealprofit': '12086.02152836416', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '27169.40915776', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=1


## /root/FIL/strategy/s_rsrs/log.txt ----- -----

721  20230603   040000    075959  1685750399  ...    721  0.642910  0.283739     NaN
722  20230603   080000    115959  1685764799  ...    722  0.629723  0.233845     NaN

[5 rows x 15 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '55.249', 'enterprice': '26128.2', 'countrevence': '0', 'unrealprofit': '55465.05581066431', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '27132.11058319', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'numpy.int64'>, curSign=-9223372036854775808, self.sign=1
--handleKline--:  version='2.0.0', self.name='s_rsrs', self.symbol='BTCUSDT', interval='4h', intervalSec=14400, wid=25, thd=0.6, self.sign=1, self.total=1442113.3648782002, self.flagDict['side']='buy', self.tradeCount=3, self.count=121
self.closeSec=1685779199, self.tradeDate='20230603', self.openTime='120000', self.closeTime='155959', self.symbol='BTCUSDT', self.open=27130.9, self.close=27161.3, self.high=27209.2, self.low=27098.0, self.vol=17689.692, self.amt=480317730.6182 
127.0.0.1 - - [03/Jun/2023 16:00:01] "POST / HTTP/1.1" 200 -
2023-06-03 16:00:01,861:INFO:s_rsrs:main.py:141:handleKline:2218689: self.closeSec=1685779199, self.tradeDate='20230603', self.openTime='120000', self.closeTime='155959',self.symbol='BTCUSDT',self.open=27130.9, self.close=27161.3, self.high=27209.2, self.low=27098.0, self.vol=17689.692, self.amt=480317730.6182 
2023-06-03 16:00:01,887:INFO:s_rsrs:main.py:142:handleKline:2218689: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime  ...         vol           amt       pct
719  20230602   200000    235959  ...  120542.039  3.257226e+09 -0.001372
720  20230603   000000    035959  ...   57272.534  1.553672e+09  0.005550
721  20230603   040000    075959  ...   30013.032  8.167713e+08 -0.000140
722  20230603   080000    115959  ...   25058.623  6.803387e+08 -0.003559
723  20230603   120000    155959  ...   17689.692  4.803177e+08  0.001120

[5 rows x 11 columns]
2023-06-03 16:00:04,174:INFO:s_rsrs:main.py:151:handleKline:2218689: df_s.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec  ...  index      beta    zscore  signal
719  20230602   200000    235959  1685721599  ...    719  0.666727  0.377153     NaN
720  20230603   000000    035959  1685735999  ...    720  0.645171  0.301626     NaN
721  20230603   040000    075959  1685750399  ...    721  0.642910  0.283739     NaN
722  20230603   080000    115959  1685764799  ...    722  0.629723  0.233845     NaN
723  20230603   120000    155959  1685779199  ...    723  0.580259  0.077345     NaN

[5 rows x 15 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '55.249', 'enterprice': '26128.2', 'countrevence': '0', 'unrealprofit': '57122.0573273213', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '27162.1021037', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'numpy.int64'>, curSign=-9223372036854775808, self.sign=1


