# 20230722 16:26:01

## /root/FIL/strategy/amihud/log.txt ----- -----

--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=373746.4768026, self.flagDict['side']='sell', self.tradeCount=2, self.count=19936
self.closeSec=1690013999, self.tradeDate='20230722', self.openTime='161500', self.closeTime='161959', self.symbol='BTCUSDT', self.open=29945.9, self.close=29958.5, self.high=29959.0, self.low=29945.9, self.vol=455.661, self.amt=13648671.4235 
127.0.0.1 - - [22/Jul/2023 16:20:01] "POST / HTTP/1.1" 200 -
2023-07-22 16:20:05,267:INFO:amihud:main.py:172:handleKline:2219019: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5951  20230722   155500    155959  ...         0.0        0.0       0
5952  20230722   160000    160459  ...         0.0        0.0       0
5953  20230722   160500    160959  ...         0.0        0.0       0
5954  20230722   161000    161459  ...         0.0        0.0       0
5955  20230722   161500    161959  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-07-22 16:20:05,286:INFO:amihud:main.py:175:handleKline:2219019: self.closeSec=1690013999, self.tradeDate='20230722', self.openTime='161500', self.closeTime='161959',self.symbol='BTCUSDT',self.open=29945.9, self.close=29958.5, self.high=29959.0, self.low=29945.9, self.vol=455.661, self.amt=13648671.4235, ukdf['pct'].iloc[-1]=0.000421 , ukdf['amount'].iloc[-1]=13648671.4235, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5955, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '13.926', 'enterprice': '26864.9', 'countrevence': '0', 'unrealprofit': '-43111.6018123593', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '29960.66345055', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1
127.0.0.1 - - [22/Jul/2023 16:25:00] "POST / HTTP/1.1" 200 -
--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=373746.4768026, self.flagDict['side']='sell', self.tradeCount=2, self.count=19937
self.closeSec=1690014299, self.tradeDate='20230722', self.openTime='162000', self.closeTime='162459', self.symbol='BTCUSDT', self.open=29958.5, self.close=29969.5, self.high=29969.5, self.low=29954.7, self.vol=650.63, self.amt=19495712.03 
2023-07-22 16:25:00,761:INFO:amihud:main.py:172:handleKline:2219019: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5952  20230722   160000    160459  ...         0.0        0.0       0
5953  20230722   160500    160959  ...         0.0        0.0       0
5954  20230722   161000    161459  ...         0.0        0.0       0
5955  20230722   161500    161959  ...         0.0        0.0       0
5956  20230722   162000    162459  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-07-22 16:25:00,762:INFO:amihud:main.py:175:handleKline:2219019: self.closeSec=1690014299, self.tradeDate='20230722', self.openTime='162000', self.closeTime='162459',self.symbol='BTCUSDT',self.open=29958.5, self.close=29969.5, self.high=29969.5, self.low=29954.7, self.vol=650.63, self.amt=19495712.03, ukdf['pct'].iloc[-1]=0.000367 , ukdf['amount'].iloc[-1]=19495712.03, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5956, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '13.926', 'enterprice': '26864.9', 'countrevence': '0', 'unrealprofit': '-43234.6596', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '29969.5', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1


## /root/FIL/strategy/factorcheck/log.txt ----- -----


self.closeSec=1690013999, self.tradeDate='20230722', self.openTime='161500', self.closeTime='161959', self.symbol='BTCUSDT', self.open=29945.9, self.close=29958.5, self.high=29959.0, self.low=29945.9 
127.0.0.1 - - [22/Jul/2023 16:20:01] "POST / HTTP/1.1" 200 -
2023-07-22 16:20:03,896:INFO:factorcheck2:main.py:126:handleKline:2218005: self.closeSec=1690013999, self.tradeDate='20230722', self.openTime='161500', self.closeTime='161959',self.symbol='BTCUSDT',self.open=29945.9, self.close=29958.5, self.high=29959.0, self.low=29945.9   
2023-07-22 16:20:04,746:INFO:factorcheck2:main.py:127:handleKline:2218005: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime    closeSec  ...      low       pct  index  idx
1631  20230722   155500    155959  1690012799  ...  29932.5 -0.000230   1631    5
1632  20230722   160000    160459  1690013099  ...  29931.0  0.000084   1632    0
1633  20230722   160500    160959  1690013399  ...  29932.0  0.000017   1633    1
1634  20230722   161000    161459  1690013699  ...  29935.9  0.000331   1634    2
1635  20230722   161500    161959  1690013999  ...  29945.9  0.000421   1635    3

[5 rows x 11 columns]
2023-07-22 16:20:04,747:INFO:factorcheck2:main.py:128:handleKline:2218005: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}
127.0.0.1 - - [22/Jul/2023 16:25:00] "POST / HTTP/1.1" 200 -

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=108, self.factor=0.4350166926295255, self.count=19939 

self.closeSec=1690014299, self.tradeDate='20230722', self.openTime='162000', self.closeTime='162459', self.symbol='BTCUSDT', self.open=29958.5, self.close=29969.5, self.high=29969.5, self.low=29954.7 
2023-07-22 16:25:00,720:INFO:factorcheck2:main.py:126:handleKline:2218005: self.closeSec=1690014299, self.tradeDate='20230722', self.openTime='162000', self.closeTime='162459',self.symbol='BTCUSDT',self.open=29958.5, self.close=29969.5, self.high=29969.5, self.low=29954.7   
2023-07-22 16:25:00,733:INFO:factorcheck2:main.py:127:handleKline:2218005: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime    closeSec  ...      low       pct  index  idx
1632  20230722   160000    160459  1690013099  ...  29931.0  0.000084   1632    0
1633  20230722   160500    160959  1690013399  ...  29932.0  0.000017   1633    1
1634  20230722   161000    161459  1690013699  ...  29935.9  0.000331   1634    2
1635  20230722   161500    161959  1690013999  ...  29945.9  0.000421   1635    3
1636  20230722   162000    162459  1690014299  ...  29954.7  0.000367   1636    4

[5 rows x 11 columns]
2023-07-22 16:25:00,733:INFO:factorcheck2:main.py:128:handleKline:2218005: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}


## /root/FIL/strategy/logic/log.txt ----- -----

2023-07-22 16:00:18,479:DEBUG:logic:main.py:463:getModel:2218526: df_s.iloc[-5:,:] :
          date closeTime     open  ...    alpha58   alpha67   alpha72
5786  20230722    132959  29870.9  ...  49.583333  0.486184  0.440388
5787  20230722    135959  29851.1  ...  50.000000  0.486854  0.450135
5788  20230722    142959  29853.3  ...  50.000000  0.490210  0.457227
5789  20230722    145959  29863.7  ...  50.416667  0.493558  0.461861
5790  20230722    152959  29873.9  ...  50.416667  0.504455  0.461050

[5 rows x 33 columns]
0.503690036900369
acc is : 0.503690036900369
2023-07-22 16:00:18,538:INFO:logic:main.py:468:getModel:2218526: df_pred.iloc[-5:,:] :
     pred    prob_0    prob_1  actual  ...       nav  sign  cost_        bm
537     1  0.494845  0.505155       1  ...  0.971869   1.0    0.0  0.981836
538     0  0.502033  0.497967       1  ...  0.972207   1.0    0.0  0.982178
539     0  0.509706  0.490294       1  ...  0.972543   1.0    0.0  0.982516
540     0  0.508890  0.491110       1  ...  0.973643   1.0    0.0  0.983628
541     0  0.518629  0.481371       1  ...  0.974463   1.0    0.0  0.984457

[5 rows x 10 columns]
2023-07-22 16:00:18,549:INFO:logic:main.py:478:getModel:2218526: df_panel.iloc[-5:,:] :
    pred    prob_0    prob_1  actual  ...       nav  sign  cost_        bm
45     1  0.495191  0.504809       1  ...  0.962677   1.0    0.0  0.984215
46     0  0.501945  0.498055       1  ...  0.972207   1.0    0.0  0.983653
47     0  0.509318  0.490682       1  ...  0.972543   1.0    0.0  0.982801
48     0  0.508641  0.491359       1  ...  0.973643   1.0    0.0  0.983356
49     0  0.518629  0.481371       1  ...  0.974463   1.0    0.0  0.984457

[5 rows x 10 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '23.444', 'enterprice': '29839.3', 'countrevence': '0', 'unrealprofit': '2297.83416182144', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '29937.31374176', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}


## /root/FIL/strategy/modifiedmom/log.txt ----- -----

527  20230722   155000    155959  1690012799    29960    29933 -0.000905
2023-07-22 16:00:02,138:INFO:modifiedmom:main.py:146:handleKline:2218259: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': True, 'isOpenSell': False, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True}

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=9968 

self.closeSec=1690013399, self.tradeDate='20230722', self.openTime='160000', self.closeTime='160959', self.symbol='BTCUSDT', self.open='29932.9', self.close='29936'
2023-07-22 16:10:01,111:INFO:modifiedmom:main.py:144:handleKline:2218259: self.closeSec=1690013399, self.tradeDate='20230722', self.openTime='160000', self.closeTime='160959',self.symbol='BTCUSDT',self.open='29932.9', self.close='29936'
127.0.0.1 - - [22/Jul/2023 16:10:01] "POST / HTTP/1.1" 200 -
2023-07-22 16:10:01,128:INFO:modifiedmom:main.py:145:handleKline:2218259: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec     open    close       pct
524  20230722   152000    152959  1690010999  29855.8  29907.8  0.001738
525  20230722   153000    153959  1690011599  29907.8  29939.5  0.001060
526  20230722   154000    154959  1690012199  29939.4  29960.1  0.000688
527  20230722   155000    155959  1690012799    29960    29933 -0.000905
528  20230722   160000    160959  1690013399  29932.9    29936  0.000100
2023-07-22 16:10:01,128:INFO:modifiedmom:main.py:146:handleKline:2218259: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': True, 'isOpenSell': False, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True}

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=9969 

self.closeSec=1690013999, self.tradeDate='20230722', self.openTime='161000', self.closeTime='161959', self.symbol='BTCUSDT', self.open='29936', self.close='29958.4'
127.0.0.1 - - [22/Jul/2023 16:20:04] "POST / HTTP/1.1" 200 -
2023-07-22 16:20:05,656:INFO:modifiedmom:main.py:144:handleKline:2218259: self.closeSec=1690013999, self.tradeDate='20230722', self.openTime='161000', self.closeTime='161959',self.symbol='BTCUSDT',self.open='29936', self.close='29958.4'
2023-07-22 16:20:06,327:INFO:modifiedmom:main.py:145:handleKline:2218259: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec     open    close       pct
525  20230722   153000    153959  1690011599  29907.8  29939.5  0.001060
526  20230722   154000    154959  1690012199  29939.4  29960.1  0.000688
527  20230722   155000    155959  1690012799    29960    29933 -0.000905
528  20230722   160000    160959  1690013399  29932.9    29936  0.000100
529  20230722   161000    161959  1690013999    29936  29958.4  0.000748
2023-07-22 16:20:06,327:INFO:modifiedmom:main.py:146:handleKline:2218259: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': True, 'isOpenSell': False, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True}


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

17519  20230722   155000    155959  1690012799    29960    29933
2023-07-22 16:00:02,144:INFO:pyemd2:main.py:127:handleKline:2217508: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}
127.0.0.1 - - [22/Jul/2023 16:10:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=9971 

self.closeSec=1690013399, self.tradeDate='20230722', self.openTime='160000', self.closeTime='160959', self.symbol='BTCUSDT', self.open='29932.9', self.close='29936'
2023-07-22 16:10:01,121:INFO:pyemd2:main.py:125:handleKline:2217508: self.closeSec=1690013399, self.tradeDate='20230722', self.openTime='160000', self.closeTime='160959',self.symbol='BTCUSDT',self.open='29932.9', self.close='29936'
2023-07-22 16:10:01,131:INFO:pyemd2:main.py:126:handleKline:2217508: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
17516  20230722   152000    152959  1690010999  29855.8  29907.8
17517  20230722   153000    153959  1690011599  29907.8  29939.5
17518  20230722   154000    154959  1690012199  29939.4  29960.1
17519  20230722   155000    155959  1690012799    29960    29933
17520  20230722   160000    160959  1690013399  29932.9    29936
2023-07-22 16:10:01,131:INFO:pyemd2:main.py:127:handleKline:2217508: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=9972 

self.closeSec=1690013999, self.tradeDate='20230722', self.openTime='161000', self.closeTime='161959', self.symbol='BTCUSDT', self.open='29936', self.close='29958.4'
127.0.0.1 - - [22/Jul/2023 16:20:04] "POST / HTTP/1.1" 200 -
2023-07-22 16:20:06,949:INFO:pyemd2:main.py:125:handleKline:2217508: self.closeSec=1690013999, self.tradeDate='20230722', self.openTime='161000', self.closeTime='161959',self.symbol='BTCUSDT',self.open='29936', self.close='29958.4'
2023-07-22 16:20:07,152:INFO:pyemd2:main.py:126:handleKline:2217508: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
17517  20230722   153000    153959  1690011599  29907.8  29939.5
17518  20230722   154000    154959  1690012199  29939.4  29960.1
17519  20230722   155000    155959  1690012799    29960    29933
17520  20230722   160000    160959  1690013399  29932.9    29936
17521  20230722   161000    161959  1690013999    29936  29958.4
2023-07-22 16:20:07,153:INFO:pyemd2:main.py:127:handleKline:2217508: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}


## /root/FIL/strategy/similarity/log.txt ----- -----

12191  20230722   155000    155959  1690012799    29960    29933
2023-07-22 16:00:02,142:INFO:testStrategy:main.py:103:handleKline:2217133: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': True, 'isOpenSell': False, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True, 'isCorr': False}
127.0.0.1 - - [22/Jul/2023 16:10:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=9971 

self.closeSec=1690013399, self.tradeDate='20230722', self.openTime='160000', self.closeTime='160959', self.symbol='BTCUSDT', self.open='29932.9', self.close='29936'
2023-07-22 16:10:01,112:INFO:testStrategy:main.py:101:handleKline:2217133: self.closeSec=1690013399, self.tradeDate='20230722', self.openTime='160000', self.closeTime='160959',self.symbol='BTCUSDT',self.open='29932.9', self.close='29936'
2023-07-22 16:10:01,121:INFO:testStrategy:main.py:102:handleKline:2217133: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
12188  20230722   152000    152959  1690010999  29855.8  29907.8
12189  20230722   153000    153959  1690011599  29907.8  29939.5
12190  20230722   154000    154959  1690012199  29939.4  29960.1
12191  20230722   155000    155959  1690012799    29960    29933
12192  20230722   160000    160959  1690013399  29932.9    29936
2023-07-22 16:10:01,121:INFO:testStrategy:main.py:103:handleKline:2217133: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': True, 'isOpenSell': False, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True, 'isCorr': False}

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=9972 

self.closeSec=1690013999, self.tradeDate='20230722', self.openTime='161000', self.closeTime='161959', self.symbol='BTCUSDT', self.open='29936', self.close='29958.4'
127.0.0.1 - - [22/Jul/2023 16:20:03] "POST / HTTP/1.1" 200 -
2023-07-22 16:20:06,840:INFO:testStrategy:main.py:101:handleKline:2217133: self.closeSec=1690013999, self.tradeDate='20230722', self.openTime='161000', self.closeTime='161959',self.symbol='BTCUSDT',self.open='29936', self.close='29958.4'
2023-07-22 16:20:07,049:INFO:testStrategy:main.py:102:handleKline:2217133: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
12189  20230722   153000    153959  1690011599  29907.8  29939.5
12190  20230722   154000    154959  1690012199  29939.4  29960.1
12191  20230722   155000    155959  1690012799    29960    29933
12192  20230722   160000    160959  1690013399  29932.9    29936
12193  20230722   161000    161959  1690013999    29936  29958.4
2023-07-22 16:20:07,049:INFO:testStrategy:main.py:103:handleKline:2217133: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': True, 'isOpenSell': False, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True, 'isCorr': False}


## /root/FIL/strategy/sr_min/log.txt ----- -----

--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=1, self.total=996015.990996, self.flagDict['side']='buy', self.tradeCount=1, self.count=19936
self.closeSec=1690013999, self.tradeDate='20230722', self.openTime='161500', self.closeTime='161959', self.symbol='BTCUSDT', self.open=29945.9, self.close=29958.5, self.high=29959.0, self.low=29945.9, self.vol=455.661, self.amt=13648671.4235 
127.0.0.1 - - [22/Jul/2023 16:20:01] "POST / HTTP/1.1" 200 -
2023-07-22 16:20:05,287:INFO:sr_min:main.py:172:handleKline:2219263: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5951  20230722   155500    155959  ...         0.0        0.0       0
5952  20230722   160000    160459  ...         0.0        0.0       0
5953  20230722   160500    160959  ...         0.0        0.0       0
5954  20230722   161000    161459  ...         0.0        0.0       0
5955  20230722   161500    161959  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-07-22 16:20:05,307:INFO:sr_min:main.py:175:handleKline:2219263: self.closeSec=1690013999, self.tradeDate='20230722', self.openTime='161500', self.closeTime='161959',self.symbol='BTCUSDT',self.open=29945.9, self.close=29958.5, self.high=29959.0, self.low=29945.9, self.vol=455.661, self.amt=13648671.4235, ukdf['pct'].iloc[-1]=0.000421 , ukdf['amount'].iloc[-1]=13648671.4235, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5955, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '37.141', 'enterprice': '26844', 'countrevence': '0', 'unrealprofit': '115755.99721687755', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '29960.66345055', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=1
127.0.0.1 - - [22/Jul/2023 16:25:00] "POST / HTTP/1.1" 200 -
--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=1, self.total=996015.990996, self.flagDict['side']='buy', self.tradeCount=1, self.count=19937
self.closeSec=1690014299, self.tradeDate='20230722', self.openTime='162000', self.closeTime='162459', self.symbol='BTCUSDT', self.open=29958.5, self.close=29969.5, self.high=29969.5, self.low=29954.7, self.vol=650.63, self.amt=19495712.03 
2023-07-22 16:25:00,747:INFO:sr_min:main.py:172:handleKline:2219263: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5952  20230722   160000    160459  ...         0.0        0.0       0
5953  20230722   160500    160959  ...         0.0        0.0       0
5954  20230722   161000    161459  ...         0.0        0.0       0
5955  20230722   161500    161959  ...         0.0        0.0       0
5956  20230722   162000    162459  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-07-22 16:25:00,747:INFO:sr_min:main.py:175:handleKline:2219263: self.closeSec=1690014299, self.tradeDate='20230722', self.openTime='162000', self.closeTime='162459',self.symbol='BTCUSDT',self.open=29958.5, self.close=29969.5, self.high=29969.5, self.low=29954.7, self.vol=650.63, self.amt=19495712.03, ukdf['pct'].iloc[-1]=0.000367 , ukdf['amount'].iloc[-1]=19495712.03, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5956, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '37.141', 'enterprice': '26844', 'countrevence': '0', 'unrealprofit': '116084.1955', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '29969.5', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=1


## /root/FIL/strategy/s_rsrs/log.txt ----- -----

721  20230722   040000    075959  1689983999  ...    721  0.140332 -1.050430    -1.0
722  20230722   080000    115959  1689998399  ...    722  0.115788 -1.133400    -1.0

[5 rows x 15 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '52.176', 'enterprice': '29870.6', 'countrevence': '0', 'unrealprofit': '-856.35312527664', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '29887.01277839', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'numpy.int64'>, curSign=-1, self.sign=-1
--handleKline--:  version='2.0.0', self.name='s_rsrs', self.symbol='BTCUSDT', interval='4h', intervalSec=14400, wid=25, thd=0.6, self.sign=-1, self.total=1556969.8971744, self.flagDict['side']='sell', self.tradeCount=12, self.count=415
self.closeSec=1690012799, self.tradeDate='20230722', self.openTime='120000', self.closeTime='155959', self.symbol='BTCUSDT', self.open=29886.7, self.close=29933.0, self.high=29986.0, self.low=29822.0, self.vol=26673.54, self.amt=797482120.3321 
127.0.0.1 - - [22/Jul/2023 16:00:01] "POST / HTTP/1.1" 200 -
2023-07-22 16:00:01,745:INFO:s_rsrs:main.py:141:handleKline:2218689: self.closeSec=1690012799, self.tradeDate='20230722', self.openTime='120000', self.closeTime='155959',self.symbol='BTCUSDT',self.open=29886.7, self.close=29933.0, self.high=29986.0, self.low=29822.0, self.vol=26673.54, self.amt=797482120.3321 
2023-07-22 16:00:01,759:INFO:s_rsrs:main.py:142:handleKline:2218689: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime  ...        vol           amt       pct
719  20230721   200000    235959  ...  46739.642  1.394602e+09  0.002930
720  20230722   000000    035959  ...  63156.101  1.888720e+09  0.000439
721  20230722   040000    075959  ...  17712.508  5.293798e+08  0.000881
722  20230722   080000    115959  ...  18181.062  5.440819e+08 -0.000161
723  20230722   120000    155959  ...  26673.540  7.974821e+08  0.001553

[5 rows x 11 columns]
2023-07-22 16:00:02,473:INFO:s_rsrs:main.py:151:handleKline:2218689: df_s.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec  ...  index      beta    zscore  signal
719  20230721   200000    235959  1689955199  ...    719  0.127920 -1.135281    -1.0
720  20230722   000000    035959  1689969599  ...    720  0.102436 -1.226806    -1.0
721  20230722   040000    075959  1689983999  ...    721  0.140332 -1.050430    -1.0
722  20230722   080000    115959  1689998399  ...    722  0.115788 -1.133400    -1.0
723  20230722   120000    155959  1690012799  ...    723  0.092641 -1.205199    -1.0

[5 rows x 15 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '52.176', 'enterprice': '29870.6', 'countrevence': '0', 'unrealprofit': '-3352.62019613952', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '29934.85598352', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'numpy.int64'>, curSign=-1, self.sign=-1


