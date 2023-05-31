# 20230531 16:26:01

## /root/FIL/strategy/amihud/log.txt ----- -----

--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=373746.4768026, self.flagDict['side']='sell', self.tradeCount=2, self.count=4960
self.closeSec=1685521199, self.tradeDate='20230531', self.openTime='161500', self.closeTime='161959', self.symbol='BTCUSDT', self.open=27177.0, self.close=27173.0, self.high=27190.9, self.low=27173.0, self.vol=726.223, self.amt=19740667.9002 
127.0.0.1 - - [31/May/2023 16:20:01] "POST / HTTP/1.1" 200 -
2023-05-31 16:20:07,054:INFO:amihud:main.py:172:handleKline:2219019: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5951  20230531   155500    155959  ...         0.0        0.0       0
5952  20230531   160000    160459  ...         0.0        0.0       0
5953  20230531   160500    160959  ...         0.0        0.0       0
5954  20230531   161000    161459  ...         0.0        0.0       0
5955  20230531   161500    161959  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-05-31 16:20:07,075:INFO:amihud:main.py:175:handleKline:2219019: self.closeSec=1685521199, self.tradeDate='20230531', self.openTime='161500', self.closeTime='161959',self.symbol='BTCUSDT',self.open=27177.0, self.close=27173.0, self.high=27190.9, self.low=27173.0, self.vol=726.223, self.amt=19740667.9002, ukdf['pct'].iloc[-1]=-0.000147 , ukdf['amount'].iloc[-1]=19740667.9002, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5955, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '13.926', 'enterprice': '26864.9', 'countrevence': '0', 'unrealprofit': '-4107.28420320834', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '27159.83639259', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1
127.0.0.1 - - [31/May/2023 16:25:00] "POST / HTTP/1.1" 200 -
--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=373746.4768026, self.flagDict['side']='sell', self.tradeCount=2, self.count=4961
self.closeSec=1685521499, self.tradeDate='20230531', self.openTime='162000', self.closeTime='162459', self.symbol='BTCUSDT', self.open=27173.1, self.close=27152.2, self.high=27173.7, self.low=27147.3, self.vol=955.439, self.amt=25948241.1348 
2023-05-31 16:25:00,815:INFO:amihud:main.py:172:handleKline:2219019: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5952  20230531   160000    160459  ...         0.0        0.0       0
5953  20230531   160500    160959  ...         0.0        0.0       0
5954  20230531   161000    161459  ...         0.0        0.0       0
5955  20230531   161500    161959  ...         0.0        0.0       0
5956  20230531   162000    162459  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-05-31 16:25:00,815:INFO:amihud:main.py:175:handleKline:2219019: self.closeSec=1685521499, self.tradeDate='20230531', self.openTime='162000', self.closeTime='162459',self.symbol='BTCUSDT',self.open=27173.1, self.close=27152.2, self.high=27173.7, self.low=27147.3, self.vol=955.439, self.amt=25948241.1348, ukdf['pct'].iloc[-1]=-0.000765 , ukdf['amount'].iloc[-1]=25948241.1348, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5956, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '13.926', 'enterprice': '26864.9', 'countrevence': '0', 'unrealprofit': '-4002.43814318172', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '27152.30759322', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1


## /root/FIL/strategy/factorcheck/log.txt ----- -----


self.closeSec=1685521199, self.tradeDate='20230531', self.openTime='161500', self.closeTime='161959', self.symbol='BTCUSDT', self.open=27177.0, self.close=27173.0, self.high=27190.9, self.low=27173.0 
127.0.0.1 - - [31/May/2023 16:20:01] "POST / HTTP/1.1" 200 -
2023-05-31 16:20:04,755:INFO:factorcheck2:main.py:126:handleKline:2218005: self.closeSec=1685521199, self.tradeDate='20230531', self.openTime='161500', self.closeTime='161959',self.symbol='BTCUSDT',self.open=27177.0, self.close=27173.0, self.high=27190.9, self.low=27173.0   
2023-05-31 16:20:06,045:INFO:factorcheck2:main.py:127:handleKline:2218005: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime    closeSec  ...      low       pct  index  idx
1631  20230531   155500    155959  1685519999  ...  27150.4 -0.000357   1631    5
1632  20230531   160000    160459  1685520299  ...  27110.0 -0.001330   1632    0
1633  20230531   160500    160959  1685520599  ...  27114.2  0.002235   1633    1
1634  20230531   161000    161459  1685520899  ...  27170.2  0.000077   1634    2
1635  20230531   161500    161959  1685521199  ...  27173.0 -0.000147   1635    3

[5 rows x 11 columns]
2023-05-31 16:20:06,054:INFO:factorcheck2:main.py:128:handleKline:2218005: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': True, 'isOpenSell': False, 'isCloseBuy': False, 'isCloseSell': False, 'isOpen': True, 'isClose': False, 'isTrig': True}
127.0.0.1 - - [31/May/2023 16:25:00] "POST / HTTP/1.1" 200 -

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=0, self.factor=0.6352085279256919, self.count=4963 

self.closeSec=1685521499, self.tradeDate='20230531', self.openTime='162000', self.closeTime='162459', self.symbol='BTCUSDT', self.open=27173.1, self.close=27152.2, self.high=27173.7, self.low=27147.3 
2023-05-31 16:25:00,737:INFO:factorcheck2:main.py:126:handleKline:2218005: self.closeSec=1685521499, self.tradeDate='20230531', self.openTime='162000', self.closeTime='162459',self.symbol='BTCUSDT',self.open=27173.1, self.close=27152.2, self.high=27173.7, self.low=27147.3   
2023-05-31 16:25:00,797:INFO:factorcheck2:main.py:127:handleKline:2218005: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime    closeSec  ...      low       pct  index  idx
1632  20230531   160000    160459  1685520299  ...  27110.0 -0.001330   1632    0
1633  20230531   160500    160959  1685520599  ...  27114.2  0.002235   1633    1
1634  20230531   161000    161459  1685520899  ...  27170.2  0.000077   1634    2
1635  20230531   161500    161959  1685521199  ...  27173.0 -0.000147   1635    3
1636  20230531   162000    162459  1685521499  ...  27147.3 -0.000765   1636    4

[5 rows x 11 columns]
2023-05-31 16:25:00,797:INFO:factorcheck2:main.py:128:handleKline:2218005: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': True, 'isOpenSell': False, 'isCloseBuy': False, 'isCloseSell': False, 'isOpen': True, 'isClose': False, 'isTrig': True}


## /root/FIL/strategy/logic/log.txt ----- -----

2023-05-31 16:00:34,792:DEBUG:logic:main.py:463:getModel:2218526: df_s.iloc[-5:,:] :
          date closeTime     open  ...    alpha58   alpha67   alpha72
5786  20230531    132959  27243.4  ...  50.833333  0.394848  0.663794
5787  20230531    135959  27162.0  ...  50.833333  0.381733  0.681422
5788  20230531    142959  27080.4  ...  50.833333  0.394928  0.691049
5789  20230531    145959  27133.0  ...  50.833333  0.399165  0.698886
5790  20230531    152959  27150.0  ...  50.833333  0.403651  0.705103

[5 rows x 33 columns]
0.522140221402214
acc is : 0.522140221402214
2023-05-31 16:00:34,984:INFO:logic:main.py:468:getModel:2218526: df_pred.iloc[-5:,:] :
     pred    prob_0    prob_1  actual  ...       nav  sign  cost_        bm
537     1  0.446544  0.553456       0  ...  1.027494  -1.0    0.0  1.009164
538     1  0.438460  0.561540       1  ...  1.025502  -1.0    0.0  1.011120
539     1  0.467868  0.532132       1  ...  1.024859  -1.0    0.0  1.011753
540     1  0.464345  0.535655       1  ...  1.024184  -1.0    0.0  1.012421
541     1  0.499671  0.500329       0  ...  1.024843  -1.0    0.0  1.011768

[5 rows x 10 columns]
2023-05-31 16:00:35,021:INFO:logic:main.py:478:getModel:2218526: df_panel.iloc[-5:,:] :
    pred    prob_0    prob_1  actual  ...       nav  sign  cost_        bm
45     1  0.446410  0.553590       0  ...  1.027494  -1.0    0.0  1.008149
46     1  0.438440  0.561560       1  ...  1.025502  -1.0    0.0  1.009731
47     1  0.467770  0.532230       1  ...  1.024859  -1.0    0.0  1.010417
48     1  0.464529  0.535471       1  ...  1.024184  -1.0    0.0  1.011098
49     1  0.499671  0.500329       0  ...  1.024843  -1.0    0.0  1.011768

[5 rows x 10 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '25.849', 'enterprice': '27935.3', 'countrevence': '0', 'unrealprofit': '20521.5211', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '27141.4', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}


## /root/FIL/strategy/modifiedmom/log.txt ----- -----

527  20230531   155000    155959  1685519999  27153.3  27150.4 -0.000107
2023-05-31 16:00:02,155:INFO:modifiedmom:main.py:146:handleKline:2218259: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': True, 'isOpenSell': False, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True}

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=2480 

self.closeSec=1685520599, self.tradeDate='20230531', self.openTime='160000', self.closeTime='160959', self.symbol='BTCUSDT', self.open='27150.4', self.close='27174.9'
2023-05-31 16:10:01,131:INFO:modifiedmom:main.py:144:handleKline:2218259: self.closeSec=1685520599, self.tradeDate='20230531', self.openTime='160000', self.closeTime='160959',self.symbol='BTCUSDT',self.open='27150.4', self.close='27174.9'
127.0.0.1 - - [31/May/2023 16:10:01] "POST / HTTP/1.1" 200 -
2023-05-31 16:10:01,152:INFO:modifiedmom:main.py:145:handleKline:2218259: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec     open    close       pct
524  20230531   152000    152959  1685518199  27140.2  27167.9  0.001021
525  20230531   153000    153959  1685518799  27167.7  27163.4 -0.000166
526  20230531   154000    154959  1685519399  27163.5  27153.3 -0.000372
527  20230531   155000    155959  1685519999  27153.3  27150.4 -0.000107
528  20230531   160000    160959  1685520599  27150.4  27174.9  0.000902
2023-05-31 16:10:01,152:INFO:modifiedmom:main.py:146:handleKline:2218259: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': True, 'isOpenSell': False, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True}

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=2481 

self.closeSec=1685521199, self.tradeDate='20230531', self.openTime='161000', self.closeTime='161959', self.symbol='BTCUSDT', self.open='27174.9', self.close='27173.1'
127.0.0.1 - - [31/May/2023 16:20:04] "POST / HTTP/1.1" 200 -
2023-05-31 16:20:07,113:INFO:modifiedmom:main.py:144:handleKline:2218259: self.closeSec=1685521199, self.tradeDate='20230531', self.openTime='161000', self.closeTime='161959',self.symbol='BTCUSDT',self.open='27174.9', self.close='27173.1'
2023-05-31 16:20:07,916:INFO:modifiedmom:main.py:145:handleKline:2218259: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec     open    close       pct
525  20230531   153000    153959  1685518799  27167.7  27163.4 -0.000166
526  20230531   154000    154959  1685519399  27163.5  27153.3 -0.000372
527  20230531   155000    155959  1685519999  27153.3  27150.4 -0.000107
528  20230531   160000    160959  1685520599  27150.4  27174.9  0.000902
529  20230531   161000    161959  1685521199  27174.9  27173.1 -0.000066
2023-05-31 16:20:07,918:INFO:modifiedmom:main.py:146:handleKline:2218259: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': True, 'isOpenSell': False, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True}


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

17519  20230531   155000    155959  1685519999  27153.3  27150.4
2023-05-31 16:00:02,178:INFO:pyemd2:main.py:127:handleKline:2217508: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}
127.0.0.1 - - [31/May/2023 16:10:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=2483 

self.closeSec=1685520599, self.tradeDate='20230531', self.openTime='160000', self.closeTime='160959', self.symbol='BTCUSDT', self.open='27150.4', self.close='27174.9'
2023-05-31 16:10:01,138:INFO:pyemd2:main.py:125:handleKline:2217508: self.closeSec=1685520599, self.tradeDate='20230531', self.openTime='160000', self.closeTime='160959',self.symbol='BTCUSDT',self.open='27150.4', self.close='27174.9'
2023-05-31 16:10:01,158:INFO:pyemd2:main.py:126:handleKline:2217508: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
17516  20230531   152000    152959  1685518199  27140.2  27167.9
17517  20230531   153000    153959  1685518799  27167.7  27163.4
17518  20230531   154000    154959  1685519399  27163.5  27153.3
17519  20230531   155000    155959  1685519999  27153.3  27150.4
17520  20230531   160000    160959  1685520599  27150.4  27174.9
2023-05-31 16:10:01,158:INFO:pyemd2:main.py:127:handleKline:2217508: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=2484 

self.closeSec=1685521199, self.tradeDate='20230531', self.openTime='161000', self.closeTime='161959', self.symbol='BTCUSDT', self.open='27174.9', self.close='27173.1'
127.0.0.1 - - [31/May/2023 16:20:04] "POST / HTTP/1.1" 200 -
2023-05-31 16:20:08,833:INFO:pyemd2:main.py:125:handleKline:2217508: self.closeSec=1685521199, self.tradeDate='20230531', self.openTime='161000', self.closeTime='161959',self.symbol='BTCUSDT',self.open='27174.9', self.close='27173.1'
2023-05-31 16:20:08,951:INFO:pyemd2:main.py:126:handleKline:2217508: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
17517  20230531   153000    153959  1685518799  27167.7  27163.4
17518  20230531   154000    154959  1685519399  27163.5  27153.3
17519  20230531   155000    155959  1685519999  27153.3  27150.4
17520  20230531   160000    160959  1685520599  27150.4  27174.9
17521  20230531   161000    161959  1685521199  27174.9  27173.1
2023-05-31 16:20:08,951:INFO:pyemd2:main.py:127:handleKline:2217508: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}


## /root/FIL/strategy/similarity/log.txt ----- -----

12191  20230531   155000    155959  1685519999  27153.3  27150.4
2023-05-31 16:00:02,168:INFO:testStrategy:main.py:103:handleKline:2217133: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': True, 'isOpenSell': False, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True, 'isCorr': False}

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=2483 

self.closeSec=1685520599, self.tradeDate='20230531', self.openTime='160000', self.closeTime='160959', self.symbol='BTCUSDT', self.open='27150.4', self.close='27174.9'
2023-05-31 16:10:01,123:INFO:testStrategy:main.py:101:handleKline:2217133: self.closeSec=1685520599, self.tradeDate='20230531', self.openTime='160000', self.closeTime='160959',self.symbol='BTCUSDT',self.open='27150.4', self.close='27174.9'
127.0.0.1 - - [31/May/2023 16:10:01] "POST / HTTP/1.1" 200 -
2023-05-31 16:10:01,157:INFO:testStrategy:main.py:102:handleKline:2217133: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
12188  20230531   152000    152959  1685518199  27140.2  27167.9
12189  20230531   153000    153959  1685518799  27167.7  27163.4
12190  20230531   154000    154959  1685519399  27163.5  27153.3
12191  20230531   155000    155959  1685519999  27153.3  27150.4
12192  20230531   160000    160959  1685520599  27150.4  27174.9
2023-05-31 16:10:01,158:INFO:testStrategy:main.py:103:handleKline:2217133: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': True, 'isOpenSell': False, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True, 'isCorr': False}

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=2484 

self.closeSec=1685521199, self.tradeDate='20230531', self.openTime='161000', self.closeTime='161959', self.symbol='BTCUSDT', self.open='27174.9', self.close='27173.1'
127.0.0.1 - - [31/May/2023 16:20:04] "POST / HTTP/1.1" 200 -
2023-05-31 16:20:08,588:INFO:testStrategy:main.py:101:handleKline:2217133: self.closeSec=1685521199, self.tradeDate='20230531', self.openTime='161000', self.closeTime='161959',self.symbol='BTCUSDT',self.open='27174.9', self.close='27173.1'
2023-05-31 16:20:08,845:INFO:testStrategy:main.py:102:handleKline:2217133: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
12189  20230531   153000    153959  1685518799  27167.7  27163.4
12190  20230531   154000    154959  1685519399  27163.5  27153.3
12191  20230531   155000    155959  1685519999  27153.3  27150.4
12192  20230531   160000    160959  1685520599  27150.4  27174.9
12193  20230531   161000    161959  1685521199  27174.9  27173.1
2023-05-31 16:20:08,847:INFO:testStrategy:main.py:103:handleKline:2217133: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': True, 'isOpenSell': False, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True, 'isCorr': False}


## /root/FIL/strategy/sr_min/log.txt ----- -----

--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=1, self.total=996015.990996, self.flagDict['side']='buy', self.tradeCount=1, self.count=4960
self.closeSec=1685521199, self.tradeDate='20230531', self.openTime='161500', self.closeTime='161959', self.symbol='BTCUSDT', self.open=27177.0, self.close=27173.0, self.high=27190.9, self.low=27173.0, self.vol=726.223, self.amt=19740667.9002 
127.0.0.1 - - [31/May/2023 16:20:01] "POST / HTTP/1.1" 200 -
2023-05-31 16:20:07,045:INFO:sr_min:main.py:172:handleKline:2219263: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5951  20230531   155500    155959  ...         0.0        0.0       0
5952  20230531   160000    160459  ...         0.0        0.0       0
5953  20230531   160500    160959  ...         0.0        0.0       0
5954  20230531   161000    161459  ...         0.0        0.0       0
5955  20230531   161500    161959  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-05-31 16:20:07,075:INFO:sr_min:main.py:175:handleKline:2219263: self.closeSec=1685521199, self.tradeDate='20230531', self.openTime='161500', self.closeTime='161959',self.symbol='BTCUSDT',self.open=27177.0, self.close=27173.0, self.high=27190.9, self.low=27173.0, self.vol=726.223, self.amt=19740667.9002, ukdf['pct'].iloc[-1]=-0.000147 , ukdf['amount'].iloc[-1]=19740667.9002, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5955, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '37.141', 'enterprice': '26844', 'countrevence': '0', 'unrealprofit': '11730.47945718519', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '27159.83639259', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=1
--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=1, self.total=996015.990996, self.flagDict['side']='buy', self.tradeCount=1, self.count=4961
self.closeSec=1685521499, self.tradeDate='20230531', self.openTime='162000', self.closeTime='162459', self.symbol='BTCUSDT', self.open=27173.1, self.close=27152.2, self.high=27173.7, self.low=27147.3, self.vol=955.439, self.amt=25948241.1348 
127.0.0.1 - - [31/May/2023 16:25:00] "POST / HTTP/1.1" 200 -
2023-05-31 16:25:00,838:INFO:sr_min:main.py:172:handleKline:2219263: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5952  20230531   160000    160459  ...         0.0        0.0       0
5953  20230531   160500    160959  ...         0.0        0.0       0
5954  20230531   161000    161459  ...         0.0        0.0       0
5955  20230531   161500    161959  ...         0.0        0.0       0
5956  20230531   162000    162459  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-05-31 16:25:00,839:INFO:sr_min:main.py:175:handleKline:2219263: self.closeSec=1685521499, self.tradeDate='20230531', self.openTime='162000', self.closeTime='162459',self.symbol='BTCUSDT',self.open=27173.1, self.close=27152.2, self.high=27173.7, self.low=27147.3, self.vol=955.439, self.amt=25948241.1348, ukdf['pct'].iloc[-1]=-0.000765 , ukdf['amount'].iloc[-1]=25948241.1348, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5956, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '37.141', 'enterprice': '26844', 'countrevence': '0', 'unrealprofit': '11450.85231978402', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '27152.30759322', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=1


## /root/FIL/strategy/s_rsrs/log.txt ----- -----

721  20230531   040000    075959  1685491199  ...    721  1.202865  2.249407     1.0
722  20230531   080000    115959  1685505599  ...    722  1.168339  2.062901     1.0

[5 rows x 15 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '55.249', 'enterprice': '26128.2', 'countrevence': '0', 'unrealprofit': '83884.5567', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '27646.5', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'numpy.int64'>, curSign=1, self.sign=1
--handleKline--:  version='2.0.0', self.name='s_rsrs', self.symbol='BTCUSDT', interval='4h', intervalSec=14400, wid=25, thd=0.6, self.sign=1, self.total=1442113.3648782002, self.flagDict['side']='buy', self.tradeCount=3, self.count=103
self.closeSec=1685519999, self.tradeDate='20230531', self.openTime='120000', self.closeTime='155959', self.symbol='BTCUSDT', self.open=27646.5, self.close=27150.4, self.high=27668.7, self.low=26942.0, self.vol=156776.296, self.amt=4265624684.6277 
127.0.0.1 - - [31/May/2023 16:00:01] "POST / HTTP/1.1" 200 -
2023-05-31 16:00:01,752:INFO:s_rsrs:main.py:141:handleKline:2218689: self.closeSec=1685519999, self.tradeDate='20230531', self.openTime='120000', self.closeTime='155959',self.symbol='BTCUSDT',self.open=27646.5, self.close=27150.4, self.high=27668.7, self.low=26942.0, self.vol=156776.296, self.amt=4265624684.6277 
2023-05-31 16:00:01,778:INFO:s_rsrs:main.py:142:handleKline:2218689: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime  ...         vol           amt       pct
719  20230530   200000    235959  ...  102527.366  2.848859e+09 -0.012172
720  20230531   000000    035959  ...   56921.116  1.576800e+09  0.006127
721  20230531   040000    075959  ...   29233.913  8.106674e+08 -0.005547
722  20230531   080000    115959  ...   39039.737  1.080384e+09 -0.001214
723  20230531   120000    155959  ...  156776.296  4.265625e+09 -0.017944

[5 rows x 11 columns]
2023-05-31 16:00:03,850:INFO:s_rsrs:main.py:151:handleKline:2218689: df_s.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec  ...  index      beta    zscore  signal
719  20230530   200000    235959  1685462399  ...    719  1.086280  2.058788     1.0
720  20230531   000000    035959  1685476799  ...    720  1.226887  2.422773     1.0
721  20230531   040000    075959  1685491199  ...    721  1.202865  2.249407     1.0
722  20230531   080000    115959  1685505599  ...    722  1.168339  2.062901     1.0
723  20230531   120000    155959  1685519999  ...    723  1.026520  1.580231     1.0

[5 rows x 15 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '55.249', 'enterprice': '26128.2', 'countrevence': '0', 'unrealprofit': '56575.85200383444', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '27152.21585556', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'numpy.int64'>, curSign=1, self.sign=1


