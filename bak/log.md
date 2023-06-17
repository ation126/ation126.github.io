# 20230617 16:26:02

## /root/FIL/strategy/amihud/log.txt ----- -----

--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=373746.4768026, self.flagDict['side']='sell', self.tradeCount=2, self.count=9856
self.closeSec=1686989999, self.tradeDate='20230617', self.openTime='161500', self.closeTime='161959', self.symbol='BTCUSDT', self.open=26631.7, self.close=26605.8, self.high=26634.6, self.low=26605.7, self.vol=734.686, self.amt=19557274.737 
127.0.0.1 - - [17/Jun/2023 16:20:02] "POST / HTTP/1.1" 200 -
2023-06-17 16:20:07,715:INFO:amihud:main.py:172:handleKline:2219019: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5951  20230617   155500    155959  ...         0.0        0.0       0
5952  20230617   160000    160459  ...         0.0        0.0       0
5953  20230617   160500    160959  ...         0.0        0.0       0
5954  20230617   161000    161459  ...         0.0        0.0       0
5955  20230617   161500    161959  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-06-17 16:20:07,754:INFO:amihud:main.py:175:handleKline:2219019: self.closeSec=1686989999, self.tradeDate='20230617', self.openTime='161500', self.closeTime='161959',self.symbol='BTCUSDT',self.open=26631.7, self.close=26605.8, self.high=26634.6, self.low=26605.7, self.vol=734.686, self.amt=19557274.737, ukdf['pct'].iloc[-1]=-0.000976 , ukdf['amount'].iloc[-1]=19557274.737, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5955, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '13.926', 'enterprice': '26864.9', 'countrevence': '0', 'unrealprofit': '3509.352', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '26612.9', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1
127.0.0.1 - - [17/Jun/2023 16:25:00] "POST / HTTP/1.1" 200 -
--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=373746.4768026, self.flagDict['side']='sell', self.tradeCount=2, self.count=9857
self.closeSec=1686990299, self.tradeDate='20230617', self.openTime='162000', self.closeTime='162459', self.symbol='BTCUSDT', self.open=26605.7, self.close=26604.9, self.high=26612.9, self.low=26588.8, self.vol=1146.812, self.amt=30502257.9285 
2023-06-17 16:25:00,747:INFO:amihud:main.py:172:handleKline:2219019: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5952  20230617   160000    160459  ...         0.0        0.0       0
5953  20230617   160500    160959  ...         0.0        0.0       0
5954  20230617   161000    161459  ...         0.0        0.0       0
5955  20230617   161500    161959  ...         0.0        0.0       0
5956  20230617   162000    162459  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-06-17 16:25:00,747:INFO:amihud:main.py:175:handleKline:2219019: self.closeSec=1686990299, self.tradeDate='20230617', self.openTime='162000', self.closeTime='162459',self.symbol='BTCUSDT',self.open=26605.7, self.close=26604.9, self.high=26612.9, self.low=26588.8, self.vol=1146.812, self.amt=30502257.9285, ukdf['pct'].iloc[-1]=-3.4e-05 , ukdf['amount'].iloc[-1]=30502257.9285, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5956, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '13.926', 'enterprice': '26864.9', 'countrevence': '0', 'unrealprofit': '3619.3674', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '26605', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1


## /root/FIL/strategy/factorcheck/log.txt ----- -----


self.closeSec=1686989999, self.tradeDate='20230617', self.openTime='161500', self.closeTime='161959', self.symbol='BTCUSDT', self.open=26631.7, self.close=26605.8, self.high=26634.6, self.low=26605.7 
127.0.0.1 - - [17/Jun/2023 16:20:01] "POST / HTTP/1.1" 200 -
2023-06-17 16:20:05,185:INFO:factorcheck2:main.py:126:handleKline:2218005: self.closeSec=1686989999, self.tradeDate='20230617', self.openTime='161500', self.closeTime='161959',self.symbol='BTCUSDT',self.open=26631.7, self.close=26605.8, self.high=26634.6, self.low=26605.7   
2023-06-17 16:20:06,734:INFO:factorcheck2:main.py:127:handleKline:2218005: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime    closeSec  ...      low       pct  index  idx
1631  20230617   155500    155959  1686988799  ...  26572.5  0.000139   1631    5
1632  20230617   160000    160459  1686989099  ...  26579.1  0.002012   1632    0
1633  20230617   160500    160959  1686989399  ...  26622.5 -0.000492   1633    1
1634  20230617   161000    161459  1686989699  ...  26627.3  0.000139   1634    2
1635  20230617   161500    161959  1686989999  ...  26605.7 -0.000976   1635    3

[5 rows x 11 columns]
2023-06-17 16:20:06,744:INFO:factorcheck2:main.py:128:handleKline:2218005: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}
127.0.0.1 - - [17/Jun/2023 16:25:00] "POST / HTTP/1.1" 200 -

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=21, self.factor=0.20942523715566827, self.count=9859 

self.closeSec=1686990299, self.tradeDate='20230617', self.openTime='162000', self.closeTime='162459', self.symbol='BTCUSDT', self.open=26605.7, self.close=26604.9, self.high=26612.9, self.low=26588.8 
2023-06-17 16:25:00,717:INFO:factorcheck2:main.py:126:handleKline:2218005: self.closeSec=1686990299, self.tradeDate='20230617', self.openTime='162000', self.closeTime='162459',self.symbol='BTCUSDT',self.open=26605.7, self.close=26604.9, self.high=26612.9, self.low=26588.8   
2023-06-17 16:25:00,758:INFO:factorcheck2:main.py:127:handleKline:2218005: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime    closeSec  ...      low       pct  index  idx
1632  20230617   160000    160459  1686989099  ...  26579.1  0.002012   1632    0
1633  20230617   160500    160959  1686989399  ...  26622.5 -0.000492   1633    1
1634  20230617   161000    161459  1686989699  ...  26627.3  0.000139   1634    2
1635  20230617   161500    161959  1686989999  ...  26605.7 -0.000976   1635    3
1636  20230617   162000    162459  1686990299  ...  26588.8 -0.000034   1636    4

[5 rows x 11 columns]
2023-06-17 16:25:00,758:INFO:factorcheck2:main.py:128:handleKline:2218005: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}


## /root/FIL/strategy/logic/log.txt ----- -----

2023-06-17 16:00:20,152:DEBUG:logic:main.py:463:getModel:2218526: df_s.iloc[-5:,:] :
          date closeTime     open  ...    alpha58   alpha67   alpha72
5786  20230617    132959  26348.1  ...  51.250000  0.614725  0.169776
5787  20230617    135959  26383.9  ...  51.666667  0.656433  0.166691
5788  20230617    142959  26679.6  ...  51.250000  0.655029  0.164032
5789  20230617    145959  26675.3  ...  51.250000  0.649531  0.162403
5790  20230617    152959  26654.6  ...  51.250000  0.644721  0.161626

[5 rows x 33 columns]
0.5571955719557196
acc is : 0.5571955719557196
2023-06-17 16:00:20,239:INFO:logic:main.py:468:getModel:2218526: df_pred.iloc[-5:,:] :
     pred    prob_0    prob_1  actual  ...       nav  sign  cost_        bm
537     0  0.505102  0.494898       1  ...  1.118466   1.0    0.0  1.039086
538     0  0.574403  0.425597       0  ...  1.118223   1.0    0.0  1.038860
539     0  0.524109  0.475891       0  ...  1.117280   1.0    0.0  1.037984
540     0  0.519111  0.480889       0  ...  1.116458   1.0    0.0  1.037221
541     0  0.511625  0.488375       0  ...  1.114471   1.0    0.0  1.035375

[5 rows x 10 columns]
2023-06-17 16:00:20,252:INFO:logic:main.py:478:getModel:2218526: df_panel.iloc[-5:,:] :
    pred    prob_0    prob_1  actual  ...       nav  sign  cost_        bm
45     0  0.505212  0.494788       1  ...  1.121255   1.0    0.0  1.038411
46     0  0.574291  0.425709       0  ...  1.121011   1.0    0.0  1.032479
47     0  0.524687  0.475313       0  ...  1.117280   1.0    0.0  1.036555
48     0  0.519542  0.480458       0  ...  1.116458   1.0    0.0  1.036575
49     0  0.511625  0.488375       0  ...  1.114471   1.0    0.0  1.035375

[5 rows x 10 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '28.127', 'enterprice': '25424', 'countrevence': '0', 'unrealprofit': '33068.9139', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '26599.7', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}


## /root/FIL/strategy/modifiedmom/log.txt ----- -----

527  20230617   155000    155959  1686988799  26609.4  26587.6 -0.000816
2023-06-17 16:00:02,211:INFO:modifiedmom:main.py:146:handleKline:2218259: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': True, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True}
127.0.0.1 - - [17/Jun/2023 16:10:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=4928 

self.closeSec=1686989399, self.tradeDate='20230617', self.openTime='160000', self.closeTime='160959', self.symbol='BTCUSDT', self.open='26587.7', self.close='26628.1'
2023-06-17 16:10:01,069:INFO:modifiedmom:main.py:144:handleKline:2218259: self.closeSec=1686989399, self.tradeDate='20230617', self.openTime='160000', self.closeTime='160959',self.symbol='BTCUSDT',self.open='26587.7', self.close='26628.1'
2023-06-17 16:10:01,107:INFO:modifiedmom:main.py:145:handleKline:2218259: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec     open    close       pct
524  20230617   152000    152959  1686986999  26631.7    26635  0.000128
525  20230617   153000    153959  1686987599    26635  26596.8 -0.001434
526  20230617   154000    154959  1686988199  26596.8  26609.3  0.000470
527  20230617   155000    155959  1686988799  26609.4  26587.6 -0.000816
528  20230617   160000    160959  1686989399  26587.7  26628.1  0.001523
2023-06-17 16:10:01,114:INFO:modifiedmom:main.py:146:handleKline:2218259: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': True, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True}

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=4929 

self.closeSec=1686989999, self.tradeDate='20230617', self.openTime='161000', self.closeTime='161959', self.symbol='BTCUSDT', self.open='26628.1', self.close='26605.8'
127.0.0.1 - - [17/Jun/2023 16:20:04] "POST / HTTP/1.1" 200 -
2023-06-17 16:20:07,535:INFO:modifiedmom:main.py:144:handleKline:2218259: self.closeSec=1686989999, self.tradeDate='20230617', self.openTime='161000', self.closeTime='161959',self.symbol='BTCUSDT',self.open='26628.1', self.close='26605.8'
2023-06-17 16:20:08,415:INFO:modifiedmom:main.py:145:handleKline:2218259: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec     open    close       pct
525  20230617   153000    153959  1686987599    26635  26596.8 -0.001434
526  20230617   154000    154959  1686988199  26596.8  26609.3  0.000470
527  20230617   155000    155959  1686988799  26609.4  26587.6 -0.000816
528  20230617   160000    160959  1686989399  26587.7  26628.1  0.001523
529  20230617   161000    161959  1686989999  26628.1  26605.8 -0.000837
2023-06-17 16:20:08,424:INFO:modifiedmom:main.py:146:handleKline:2218259: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': True, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True}


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

17519  20230617   155000    155959  1686988799  26609.4  26587.6
2023-06-17 16:00:02,179:INFO:pyemd2:main.py:127:handleKline:2217508: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}
127.0.0.1 - - [17/Jun/2023 16:10:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=4931 

self.closeSec=1686989399, self.tradeDate='20230617', self.openTime='160000', self.closeTime='160959', self.symbol='BTCUSDT', self.open='26587.7', self.close='26628.1'
2023-06-17 16:10:01,081:INFO:pyemd2:main.py:125:handleKline:2217508: self.closeSec=1686989399, self.tradeDate='20230617', self.openTime='160000', self.closeTime='160959',self.symbol='BTCUSDT',self.open='26587.7', self.close='26628.1'
2023-06-17 16:10:01,090:INFO:pyemd2:main.py:126:handleKline:2217508: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
17516  20230617   152000    152959  1686986999  26631.7    26635
17517  20230617   153000    153959  1686987599    26635  26596.8
17518  20230617   154000    154959  1686988199  26596.8  26609.3
17519  20230617   155000    155959  1686988799  26609.4  26587.6
17520  20230617   160000    160959  1686989399  26587.7  26628.1
2023-06-17 16:10:01,090:INFO:pyemd2:main.py:127:handleKline:2217508: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=4932 

self.closeSec=1686989999, self.tradeDate='20230617', self.openTime='161000', self.closeTime='161959', self.symbol='BTCUSDT', self.open='26628.1', self.close='26605.8'
127.0.0.1 - - [17/Jun/2023 16:20:04] "POST / HTTP/1.1" 200 -
2023-06-17 16:20:09,869:INFO:pyemd2:main.py:125:handleKline:2217508: self.closeSec=1686989999, self.tradeDate='20230617', self.openTime='161000', self.closeTime='161959',self.symbol='BTCUSDT',self.open='26628.1', self.close='26605.8'
2023-06-17 16:20:10,016:INFO:pyemd2:main.py:126:handleKline:2217508: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
17517  20230617   153000    153959  1686987599    26635  26596.8
17518  20230617   154000    154959  1686988199  26596.8  26609.3
17519  20230617   155000    155959  1686988799  26609.4  26587.6
17520  20230617   160000    160959  1686989399  26587.7  26628.1
17521  20230617   161000    161959  1686989999  26628.1  26605.8
2023-06-17 16:20:10,017:INFO:pyemd2:main.py:127:handleKline:2217508: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}


## /root/FIL/strategy/similarity/log.txt ----- -----

12191  20230617   155000    155959  1686988799  26609.4  26587.6
2023-06-17 16:00:02,213:INFO:testStrategy:main.py:103:handleKline:2217133: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': True, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True, 'isCorr': False}
127.0.0.1 - - [17/Jun/2023 16:10:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=4931 

self.closeSec=1686989399, self.tradeDate='20230617', self.openTime='160000', self.closeTime='160959', self.symbol='BTCUSDT', self.open='26587.7', self.close='26628.1'
2023-06-17 16:10:01,091:INFO:testStrategy:main.py:101:handleKline:2217133: self.closeSec=1686989399, self.tradeDate='20230617', self.openTime='160000', self.closeTime='160959',self.symbol='BTCUSDT',self.open='26587.7', self.close='26628.1'
2023-06-17 16:10:01,110:INFO:testStrategy:main.py:102:handleKline:2217133: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
12188  20230617   152000    152959  1686986999  26631.7    26635
12189  20230617   153000    153959  1686987599    26635  26596.8
12190  20230617   154000    154959  1686988199  26596.8  26609.3
12191  20230617   155000    155959  1686988799  26609.4  26587.6
12192  20230617   160000    160959  1686989399  26587.7  26628.1
2023-06-17 16:10:01,110:INFO:testStrategy:main.py:103:handleKline:2217133: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': True, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True, 'isCorr': False}

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=4932 

self.closeSec=1686989999, self.tradeDate='20230617', self.openTime='161000', self.closeTime='161959', self.symbol='BTCUSDT', self.open='26628.1', self.close='26605.8'
127.0.0.1 - - [17/Jun/2023 16:20:04] "POST / HTTP/1.1" 200 -
2023-06-17 16:20:09,416:INFO:testStrategy:main.py:101:handleKline:2217133: self.closeSec=1686989999, self.tradeDate='20230617', self.openTime='161000', self.closeTime='161959',self.symbol='BTCUSDT',self.open='26628.1', self.close='26605.8'
2023-06-17 16:20:09,746:INFO:testStrategy:main.py:102:handleKline:2217133: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
12189  20230617   153000    153959  1686987599    26635  26596.8
12190  20230617   154000    154959  1686988199  26596.8  26609.3
12191  20230617   155000    155959  1686988799  26609.4  26587.6
12192  20230617   160000    160959  1686989399  26587.7  26628.1
12193  20230617   161000    161959  1686989999  26628.1  26605.8
2023-06-17 16:20:09,754:INFO:testStrategy:main.py:103:handleKline:2217133: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': True, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True, 'isCorr': False}


## /root/FIL/strategy/sr_min/log.txt ----- -----

--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=1, self.total=996015.990996, self.flagDict['side']='buy', self.tradeCount=1, self.count=9856
self.closeSec=1686989999, self.tradeDate='20230617', self.openTime='161500', self.closeTime='161959', self.symbol='BTCUSDT', self.open=26631.7, self.close=26605.8, self.high=26634.6, self.low=26605.7, self.vol=734.686, self.amt=19557274.737 
127.0.0.1 - - [17/Jun/2023 16:20:02] "POST / HTTP/1.1" 200 -
2023-06-17 16:20:07,715:INFO:sr_min:main.py:172:handleKline:2219263: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5951  20230617   155500    155959  ...         0.0        0.0       0
5952  20230617   160000    160459  ...         0.0        0.0       0
5953  20230617   160500    160959  ...         0.0        0.0       0
5954  20230617   161000    161459  ...         0.0        0.0       0
5955  20230617   161500    161959  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-06-17 16:20:07,735:INFO:sr_min:main.py:175:handleKline:2219263: self.closeSec=1686989999, self.tradeDate='20230617', self.openTime='161500', self.closeTime='161959',self.symbol='BTCUSDT',self.open=26631.7, self.close=26605.8, self.high=26634.6, self.low=26605.7, self.vol=734.686, self.amt=19557274.737, ukdf['pct'].iloc[-1]=-0.000976 , ukdf['amount'].iloc[-1]=19557274.737, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5955, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '37.141', 'enterprice': '26844', 'countrevence': '0', 'unrealprofit': '-8583.2851', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '26612.9', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=1
127.0.0.1 - - [17/Jun/2023 16:25:00] "POST / HTTP/1.1" 200 -
--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=1, self.total=996015.990996, self.flagDict['side']='buy', self.tradeCount=1, self.count=9857
self.closeSec=1686990299, self.tradeDate='20230617', self.openTime='162000', self.closeTime='162459', self.symbol='BTCUSDT', self.open=26605.7, self.close=26604.9, self.high=26612.9, self.low=26588.8, self.vol=1146.812, self.amt=30502257.9285 
2023-06-17 16:25:00,752:INFO:sr_min:main.py:172:handleKline:2219263: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5952  20230617   160000    160459  ...         0.0        0.0       0
5953  20230617   160500    160959  ...         0.0        0.0       0
5954  20230617   161000    161459  ...         0.0        0.0       0
5955  20230617   161500    161959  ...         0.0        0.0       0
5956  20230617   162000    162459  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-06-17 16:25:00,753:INFO:sr_min:main.py:175:handleKline:2219263: self.closeSec=1686990299, self.tradeDate='20230617', self.openTime='162000', self.closeTime='162459',self.symbol='BTCUSDT',self.open=26605.7, self.close=26604.9, self.high=26612.9, self.low=26588.8, self.vol=1146.812, self.amt=30502257.9285, ukdf['pct'].iloc[-1]=-3.4e-05 , ukdf['amount'].iloc[-1]=30502257.9285, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5956, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '37.141', 'enterprice': '26844', 'countrevence': '0', 'unrealprofit': '-8876.699', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '26605', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=1


## /root/FIL/strategy/s_rsrs/log.txt ----- -----

720  20230617   000000    035959  ...  216896.427  5.674569e+09  0.020753
721  20230617   040000    075959  ...   37660.921  9.924992e+08 -0.001233
722  20230617   080000    115959  ...   36661.055  9.628664e+08 -0.003136
723  20230617   120000    155959  ...  107938.264  2.873805e+09  0.012730

[5 rows x 11 columns]
2023-06-17 16:00:03,223:INFO:s_rsrs:main.py:151:handleKline:2218689: df_s.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec  ...  index      beta    zscore  signal
719  20230616   200000    235959  1686931199  ...    719  0.386754 -0.095560     NaN
720  20230617   000000    035959  1686945599  ...    720  0.404326  0.008649     NaN
721  20230617   040000    075959  1686959999  ...    721  0.422262  0.120551     NaN
722  20230617   080000    115959  1686974399  ...    722  0.440066  0.231394     NaN
723  20230617   120000    155959  1686988799  ...    723  0.515413  0.637007     1.0

[5 rows x 15 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '55.166', 'enterprice': '27078.6', 'countrevence': '0', 'unrealprofit': '27080.9894', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '26587.7', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'numpy.int64'>, curSign=1, self.sign=-1
handlebackTrade > queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '55.166', 'enterprice': '27078.6', 'countrevence': '0', 'unrealprofit': '27080.9894', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '26587.7', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
2023-06-17 16:00:10,091:INFO:s_rsrs:main.py:182:queryContractAssets:2218689: queryContractAssets: assets=ContractAssetReturn{'result': [ContractAsset{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'asset': 'USDT', 'free': '1524721.3619245', 'total': '1524721.3619245', 'margin': '0', 'unreal': '0', 'type': 'AssetType_ucontract'}]}
2023-06-17 16:00:10,551:DEBUG:s_rsrs:main.py:253:openBuy:2218689: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': True, 'isOpenSell': True, 'isCloseBuy': False, 'isCloseSell': False, 'isOpen': True, 'isClose': False, 'isTrig': False}
2023-06-17 16:00:10,551:INFO:s_rsrs:main.py:254:openBuy:2218689: ret = self.client.insertMarketUOrder("simulator", "BTCUSDT", 57.175, "buy"), ret=InsertOrderReturn{'result': 'success', 'clientorderid': '42405F1686988810546I0L65'}
2023-06-17 16:00:10,567:INFO:s_rsrs:main.py:176:insertFactor:2218689: curDateTime:6171600, name:s_rsrs, symbol:BTCUSDT, tradeDate:20230617, closeTime:155959, close:26587.6, sign:1, total:1524721.3619245, side:buy  
127.0.0.1 - - [17/Jun/2023 16:00:10] "POST / HTTP/1.1" 200 -
127.0.0.1 - - [17/Jun/2023 16:00:10] "POST / HTTP/1.1" 200 -
2023-06-17 16:00:10,572:INFO:s_rsrs:main.py:343:handleOrderNew:2218689: handleOrderNew: data=OrderType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'clientorderid': '42404F1686988804964I0L65', 'symbol': 'BTCUSDT', 'gatewayorderid': 1686988805405798, 'quantity': '55.166', 'price': '26580.1', 'stopprice': '0', 'ordertype': '', 'side': 'BUY', 'status': 'FILLED', 'positionside': 'LONG', 'createtime': 1686988804086, 'updatetime': 1686988805405, 'tradetype': 'usdt', 'selfid': 42404, 'filltrades': [TradeType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'tradeid': 1686988805405, 'clientorderid': '42404F1686988804964I0L65', 'price': '26580.1', 'quantity': '55.166', 'commission': '1466.3177966', 'commissionasset': 'USDT', 'tradetime': 1686988805405, 'tradetype': 'usdt', 'gatetype': 'simulator', 'handletime': 1686988805405}], 'gatetype': 'simulator', 'handletime': 0}
2023-06-17 16:00:10,573:INFO:s_rsrs:main.py:346:handleOrderFilled:2218689: handleOrderFilled: data=OrderType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'clientorderid': '42404F1686988804964I0L65', 'symbol': 'BTCUSDT', 'gatewayorderid': 1686988805405798, 'quantity': '55.166', 'price': '26580.1', 'stopprice': '0', 'ordertype': '', 'side': 'BUY', 'status': 'FILLED', 'positionside': 'LONG', 'createtime': 1686988804086, 'updatetime': 1686988805405, 'tradetype': 'usdt', 'selfid': 42404, 'filltrades': [TradeType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'tradeid': 1686988805405, 'clientorderid': '42404F1686988804964I0L65', 'price': '26580.1', 'quantity': '55.166', 'commission': '1466.3177966', 'commissionasset': 'USDT', 'tradetime': 1686988805405, 'tradetype': 'usdt', 'gatetype': 'simulator', 'handletime': 1686988805405}], 'gatetype': 'simulator', 'handletime': 0}
127.0.0.1 - - [17/Jun/2023 16:00:11] "POST / HTTP/1.1" 200 -
2023-06-17 16:00:11,000:INFO:s_rsrs:main.py:343:handleOrderNew:2218689: handleOrderNew: data=OrderType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'clientorderid': '42405F1686988810546I0L65', 'symbol': 'BTCUSDT', 'gatewayorderid': 1686988810947354, 'quantity': '57.175', 'price': '26590', 'stopprice': '0', 'ordertype': '', 'side': 'BUY', 'status': 'FILLED', 'positionside': 'LONG', 'createtime': 1686988810102, 'updatetime': 1686988810947, 'tradetype': 'usdt', 'selfid': 42405, 'filltrades': [TradeType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'tradeid': 1686988810947, 'clientorderid': '42405F1686988810546I0L65', 'price': '26590', 'quantity': '57.175', 'commission': '1520.28325', 'commissionasset': 'USDT', 'tradetime': 1686988810947, 'tradetype': 'usdt', 'gatetype': 'simulator', 'handletime': 1686988810947}], 'gatetype': 'simulator', 'handletime': 0}
2023-06-17 16:00:11,182:INFO:s_rsrs:main.py:346:handleOrderFilled:2218689: handleOrderFilled: data=OrderType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'clientorderid': '42405F1686988810546I0L65', 'symbol': 'BTCUSDT', 'gatewayorderid': 1686988810947354, 'quantity': '57.175', 'price': '26590', 'stopprice': '0', 'ordertype': '', 'side': 'BUY', 'status': 'FILLED', 'positionside': 'LONG', 'createtime': 1686988810102, 'updatetime': 1686988810947, 'tradetype': 'usdt', 'selfid': 42405, 'filltrades': [TradeType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'tradeid': 1686988810947, 'clientorderid': '42405F1686988810546I0L65', 'price': '26590', 'quantity': '57.175', 'commission': '1520.28325', 'commissionasset': 'USDT', 'tradetime': 1686988810947, 'tradetype': 'usdt', 'gatetype': 'simulator', 'handletime': 1686988810947}], 'gatetype': 'simulator', 'handletime': 0}
127.0.0.1 - - [17/Jun/2023 16:00:11] "POST / HTTP/1.1" 200 -


