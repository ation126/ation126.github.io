# 20230806 16:26:01

## /root/FIL/strategy/amihud/log.txt ----- -----

--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=373746.4768026, self.flagDict['side']='sell', self.tradeCount=2, self.count=24256
self.closeSec=1691309999, self.tradeDate='20230806', self.openTime='161500', self.closeTime='161959', self.symbol='BTCUSDT', self.open=29086.5, self.close=29093.0, self.high=29093.1, self.low=29086.4, self.vol=215.753, self.amt=6276217.3195 
127.0.0.1 - - [06/Aug/2023 16:20:01] "POST / HTTP/1.1" 200 -
2023-08-06 16:20:06,571:INFO:amihud:main.py:172:handleKline:2219019: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5951  20230806   155500    155959  ...         0.0        0.0       0
5952  20230806   160000    160459  ...         0.0        0.0       0
5953  20230806   160500    160959  ...         0.0        0.0       0
5954  20230806   161000    161459  ...         0.0        0.0       0
5955  20230806   161500    161959  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-08-06 16:20:06,592:INFO:amihud:main.py:175:handleKline:2219019: self.closeSec=1691309999, self.tradeDate='20230806', self.openTime='161500', self.closeTime='161959',self.symbol='BTCUSDT',self.open=29086.5, self.close=29093.0, self.high=29093.1, self.low=29086.4, self.vol=215.753, self.amt=6276217.3195, ukdf['pct'].iloc[-1]=0.000223 , ukdf['amount'].iloc[-1]=6276217.3195, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5955, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '13.926', 'enterprice': '26864.9', 'countrevence': '0', 'unrealprofit': '-31028.5206', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '29093', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1
--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=373746.4768026, self.flagDict['side']='sell', self.tradeCount=2, self.count=24257
self.closeSec=1691310299, self.tradeDate='20230806', self.openTime='162000', self.closeTime='162459', self.symbol='BTCUSDT', self.open=29093.1, self.close=29093.0, self.high=29104.5, self.low=29093.0, self.vol=632.922, self.amt=18417357.7499 
127.0.0.1 - - [06/Aug/2023 16:25:00] "POST / HTTP/1.1" 200 -
2023-08-06 16:25:00,782:INFO:amihud:main.py:172:handleKline:2219019: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5952  20230806   160000    160459  ...         0.0        0.0       0
5953  20230806   160500    160959  ...         0.0        0.0       0
5954  20230806   161000    161459  ...         0.0        0.0       0
5955  20230806   161500    161959  ...         0.0        0.0       0
5956  20230806   162000    162459  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-08-06 16:25:00,782:INFO:amihud:main.py:175:handleKline:2219019: self.closeSec=1691310299, self.tradeDate='20230806', self.openTime='162000', self.closeTime='162459',self.symbol='BTCUSDT',self.open=29093.1, self.close=29093.0, self.high=29104.5, self.low=29093.0, self.vol=632.922, self.amt=18417357.7499, ukdf['pct'].iloc[-1]=0.0 , ukdf['amount'].iloc[-1]=18417357.7499, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5956, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '13.926', 'enterprice': '26864.9', 'countrevence': '0', 'unrealprofit': '-31111.23498971004', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '29098.93956554', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1


## /root/FIL/strategy/factorcheck/log.txt ----- -----


self.closeSec=1691309999, self.tradeDate='20230806', self.openTime='161500', self.closeTime='161959', self.symbol='BTCUSDT', self.open=29086.5, self.close=29093.0, self.high=29093.1, self.low=29086.4 
127.0.0.1 - - [06/Aug/2023 16:20:01] "POST / HTTP/1.1" 200 -
2023-08-06 16:20:04,402:INFO:factorcheck2:main.py:126:handleKline:2218005: self.closeSec=1691309999, self.tradeDate='20230806', self.openTime='161500', self.closeTime='161959',self.symbol='BTCUSDT',self.open=29086.5, self.close=29093.0, self.high=29093.1, self.low=29086.4   
2023-08-06 16:20:05,611:INFO:factorcheck2:main.py:127:handleKline:2218005: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime    closeSec  ...      low       pct  index  idx
1631  20230806   155500    155959  1691308799  ...  29075.0 -0.000340   1631    5
1632  20230806   160000    160459  1691309099  ...  29081.3  0.000131   1632    0
1633  20230806   160500    160959  1691309399  ...  29084.4  0.000028   1633    1
1634  20230806   161000    161459  1691309699  ...  29085.8  0.000021   1634    2
1635  20230806   161500    161959  1691309999  ...  29086.4  0.000223   1635    3

[5 rows x 11 columns]
2023-08-06 16:20:05,612:INFO:factorcheck2:main.py:128:handleKline:2218005: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}
127.0.0.1 - - [06/Aug/2023 16:25:00] "POST / HTTP/1.1" 200 -

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=91, self.factor=0.46495479113273186, self.count=24259 

self.closeSec=1691310299, self.tradeDate='20230806', self.openTime='162000', self.closeTime='162459', self.symbol='BTCUSDT', self.open=29093.1, self.close=29093.0, self.high=29104.5, self.low=29093.0 
2023-08-06 16:25:00,751:INFO:factorcheck2:main.py:126:handleKline:2218005: self.closeSec=1691310299, self.tradeDate='20230806', self.openTime='162000', self.closeTime='162459',self.symbol='BTCUSDT',self.open=29093.1, self.close=29093.0, self.high=29104.5, self.low=29093.0   
2023-08-06 16:25:00,765:INFO:factorcheck2:main.py:127:handleKline:2218005: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime    closeSec  ...      low       pct  index  idx
1632  20230806   160000    160459  1691309099  ...  29081.3  0.000131   1632    0
1633  20230806   160500    160959  1691309399  ...  29084.4  0.000028   1633    1
1634  20230806   161000    161459  1691309699  ...  29085.8  0.000021   1634    2
1635  20230806   161500    161959  1691309999  ...  29086.4  0.000223   1635    3
1636  20230806   162000    162459  1691310299  ...  29093.0  0.000000   1636    4

[5 rows x 11 columns]
2023-08-06 16:25:00,766:INFO:factorcheck2:main.py:128:handleKline:2218005: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}


## /root/FIL/strategy/logic/log.txt ----- -----

2023-08-06 16:00:18,445:DEBUG:logic:main.py:463:getModel:2218526: df_s.iloc[-5:,:] :
          date closeTime     open  ...    alpha58   alpha67   alpha72
5786  20230806    132959  29064.8  ...  49.166667  0.490455  0.318753
5787  20230806    135959  29074.4  ...  49.166667  0.500089  0.297603
5788  20230806    142959  29091.8  ...  48.750000  0.479575  0.299126
5789  20230806    145959  29053.0  ...  49.166667  0.483862  0.296800
5790  20230806    152959  29060.8  ...  49.166667  0.488995  0.290152

[5 rows x 33 columns]
0.5479704797047971
acc is : 0.5479704797047971
2023-08-06 16:00:18,522:INFO:logic:main.py:468:getModel:2218526: df_pred.iloc[-5:,:] :
     pred    prob_0    prob_1  actual  ...       nav  sign  cost_        bm
537     0  0.506972  0.493028       1  ...  0.985147   1.0    0.0  0.997825
538     0  0.509605  0.490395       0  ...  0.983833   1.0    0.0  0.996495
539     1  0.489807  0.510193       1  ...  0.984094   1.0    0.0  0.996759
540     0  0.502385  0.497615       1  ...  0.984405   1.0    0.0  0.997074
541     0  0.504244  0.495756       1  ...  0.984788   1.0    0.0  0.997462

[5 rows x 10 columns]
2023-08-06 16:00:18,535:INFO:logic:main.py:478:getModel:2218526: df_panel.iloc[-5:,:] :
    pred    prob_0    prob_1  actual  ...       nav  sign  cost_        bm
45     0  0.506973  0.493027       1  ...  0.985147   1.0    0.0  0.996667
46     0  0.509480  0.490520       0  ...  0.983833   1.0    0.0  0.994996
47     1  0.489540  0.510460       1  ...  0.963472   1.0    0.0  0.994681
48     0  0.502576  0.497424       1  ...  0.984405   1.0    0.0  0.996261
49     0  0.504244  0.495756       1  ...  0.984788   1.0    0.0  0.997462

[5 rows x 10 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '24.06', 'enterprice': '29131.5', 'countrevence': '0', 'unrealprofit': '-1089.918', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '29086.2', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}


## /root/FIL/strategy/modifiedmom/log.txt ----- -----

527  20230806   155000    155959  1691308799  29084.7  29081.4 -0.000113
2023-08-06 16:00:02,031:INFO:modifiedmom:main.py:146:handleKline:2218259: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': True, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True}

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=12128 

self.closeSec=1691309399, self.tradeDate='20230806', self.openTime='160000', self.closeTime='160959', self.symbol='BTCUSDT', self.open='29081.3', self.close='29085.9'
2023-08-06 16:10:01,180:INFO:modifiedmom:main.py:144:handleKline:2218259: self.closeSec=1691309399, self.tradeDate='20230806', self.openTime='160000', self.closeTime='160959',self.symbol='BTCUSDT',self.open='29081.3', self.close='29085.9'
127.0.0.1 - - [06/Aug/2023 16:10:01] "POST / HTTP/1.1" 200 -
2023-08-06 16:10:01,190:INFO:modifiedmom:main.py:145:handleKline:2218259: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec     open    close       pct
524  20230806   152000    152959  1691306999  29063.5    29070  0.000227
525  20230806   153000    153959  1691307599  29069.9  29069.3 -0.000024
526  20230806   154000    154959  1691308199  29070.9  29084.7  0.000530
527  20230806   155000    155959  1691308799  29084.7  29081.4 -0.000113
528  20230806   160000    160959  1691309399  29081.3  29085.9  0.000155
2023-08-06 16:10:01,190:INFO:modifiedmom:main.py:146:handleKline:2218259: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': True, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True}

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=12129 

self.closeSec=1691309999, self.tradeDate='20230806', self.openTime='161000', self.closeTime='161959', self.symbol='BTCUSDT', self.open='29085.9', self.close='29093'
127.0.0.1 - - [06/Aug/2023 16:20:04] "POST / HTTP/1.1" 200 -
2023-08-06 16:20:07,112:INFO:modifiedmom:main.py:144:handleKline:2218259: self.closeSec=1691309999, self.tradeDate='20230806', self.openTime='161000', self.closeTime='161959',self.symbol='BTCUSDT',self.open='29085.9', self.close='29093'
2023-08-06 16:20:07,662:INFO:modifiedmom:main.py:145:handleKline:2218259: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec     open    close       pct
525  20230806   153000    153959  1691307599  29069.9  29069.3 -0.000024
526  20230806   154000    154959  1691308199  29070.9  29084.7  0.000530
527  20230806   155000    155959  1691308799  29084.7  29081.4 -0.000113
528  20230806   160000    160959  1691309399  29081.3  29085.9  0.000155
529  20230806   161000    161959  1691309999  29085.9    29093  0.000244
2023-08-06 16:20:07,664:INFO:modifiedmom:main.py:146:handleKline:2218259: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': True, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True}


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

17519  20230806   155000    155959  1691308799  29084.7  29081.4
2023-08-06 16:00:02,037:INFO:pyemd2:main.py:127:handleKline:2217508: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=12131 

self.closeSec=1691309399, self.tradeDate='20230806', self.openTime='160000', self.closeTime='160959', self.symbol='BTCUSDT', self.open='29081.3', self.close='29085.9'
2023-08-06 16:10:01,170:INFO:pyemd2:main.py:125:handleKline:2217508: self.closeSec=1691309399, self.tradeDate='20230806', self.openTime='160000', self.closeTime='160959',self.symbol='BTCUSDT',self.open='29081.3', self.close='29085.9'
127.0.0.1 - - [06/Aug/2023 16:10:01] "POST / HTTP/1.1" 200 -
2023-08-06 16:10:01,177:INFO:pyemd2:main.py:126:handleKline:2217508: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
17516  20230806   152000    152959  1691306999  29063.5    29070
17517  20230806   153000    153959  1691307599  29069.9  29069.3
17518  20230806   154000    154959  1691308199  29070.9  29084.7
17519  20230806   155000    155959  1691308799  29084.7  29081.4
17520  20230806   160000    160959  1691309399  29081.3  29085.9
2023-08-06 16:10:01,177:INFO:pyemd2:main.py:127:handleKline:2217508: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=12132 

self.closeSec=1691309999, self.tradeDate='20230806', self.openTime='161000', self.closeTime='161959', self.symbol='BTCUSDT', self.open='29085.9', self.close='29093'
127.0.0.1 - - [06/Aug/2023 16:20:04] "POST / HTTP/1.1" 200 -
2023-08-06 16:20:08,979:INFO:pyemd2:main.py:125:handleKline:2217508: self.closeSec=1691309999, self.tradeDate='20230806', self.openTime='161000', self.closeTime='161959',self.symbol='BTCUSDT',self.open='29085.9', self.close='29093'
2023-08-06 16:20:09,100:INFO:pyemd2:main.py:126:handleKline:2217508: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
17517  20230806   153000    153959  1691307599  29069.9  29069.3
17518  20230806   154000    154959  1691308199  29070.9  29084.7
17519  20230806   155000    155959  1691308799  29084.7  29081.4
17520  20230806   160000    160959  1691309399  29081.3  29085.9
17521  20230806   161000    161959  1691309999  29085.9    29093
2023-08-06 16:20:09,100:INFO:pyemd2:main.py:127:handleKline:2217508: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}


## /root/FIL/strategy/similarity/log.txt ----- -----

12191  20230806   155000    155959  1691308799  29084.7  29081.4
2023-08-06 16:00:02,048:INFO:testStrategy:main.py:103:handleKline:2217133: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': True, 'isOpenSell': False, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True, 'isCorr': False}

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=12131 

self.closeSec=1691309399, self.tradeDate='20230806', self.openTime='160000', self.closeTime='160959', self.symbol='BTCUSDT', self.open='29081.3', self.close='29085.9'
127.0.0.1 - - [06/Aug/2023 16:10:01] "POST / HTTP/1.1" 200 -
2023-08-06 16:10:01,171:INFO:testStrategy:main.py:101:handleKline:2217133: self.closeSec=1691309399, self.tradeDate='20230806', self.openTime='160000', self.closeTime='160959',self.symbol='BTCUSDT',self.open='29081.3', self.close='29085.9'
2023-08-06 16:10:01,188:INFO:testStrategy:main.py:102:handleKline:2217133: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
12188  20230806   152000    152959  1691306999  29063.5    29070
12189  20230806   153000    153959  1691307599  29069.9  29069.3
12190  20230806   154000    154959  1691308199  29070.9  29084.7
12191  20230806   155000    155959  1691308799  29084.7  29081.4
12192  20230806   160000    160959  1691309399  29081.3  29085.9
2023-08-06 16:10:01,188:INFO:testStrategy:main.py:103:handleKline:2217133: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': True, 'isOpenSell': False, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True, 'isCorr': False}

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=12132 

self.closeSec=1691309999, self.tradeDate='20230806', self.openTime='161000', self.closeTime='161959', self.symbol='BTCUSDT', self.open='29085.9', self.close='29093'
127.0.0.1 - - [06/Aug/2023 16:20:04] "POST / HTTP/1.1" 200 -
2023-08-06 16:20:08,631:INFO:testStrategy:main.py:101:handleKline:2217133: self.closeSec=1691309999, self.tradeDate='20230806', self.openTime='161000', self.closeTime='161959',self.symbol='BTCUSDT',self.open='29085.9', self.close='29093'
2023-08-06 16:20:08,897:INFO:testStrategy:main.py:102:handleKline:2217133: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
12189  20230806   153000    153959  1691307599  29069.9  29069.3
12190  20230806   154000    154959  1691308199  29070.9  29084.7
12191  20230806   155000    155959  1691308799  29084.7  29081.4
12192  20230806   160000    160959  1691309399  29081.3  29085.9
12193  20230806   161000    161959  1691309999  29085.9    29093
2023-08-06 16:20:08,899:INFO:testStrategy:main.py:103:handleKline:2217133: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': True, 'isOpenSell': False, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True, 'isCorr': False}


## /root/FIL/strategy/sr_min/log.txt ----- -----

--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=1, self.total=996015.990996, self.flagDict['side']='buy', self.tradeCount=1, self.count=24256
self.closeSec=1691309999, self.tradeDate='20230806', self.openTime='161500', self.closeTime='161959', self.symbol='BTCUSDT', self.open=29086.5, self.close=29093.0, self.high=29093.1, self.low=29086.4, self.vol=215.753, self.amt=6276217.3195 
127.0.0.1 - - [06/Aug/2023 16:20:01] "POST / HTTP/1.1" 200 -
2023-08-06 16:20:06,671:INFO:sr_min:main.py:172:handleKline:2219263: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5951  20230806   155500    155959  ...         0.0        0.0       0
5952  20230806   160000    160459  ...         0.0        0.0       0
5953  20230806   160500    160959  ...         0.0        0.0       0
5954  20230806   161000    161459  ...         0.0        0.0       0
5955  20230806   161500    161959  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-08-06 16:20:06,691:INFO:sr_min:main.py:175:handleKline:2219263: self.closeSec=1691309999, self.tradeDate='20230806', self.openTime='161500', self.closeTime='161959',self.symbol='BTCUSDT',self.open=29086.5, self.close=29093.0, self.high=29093.1, self.low=29086.4, self.vol=215.753, self.amt=6276217.3195, ukdf['pct'].iloc[-1]=0.000223 , ukdf['amount'].iloc[-1]=6276217.3195, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5955, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '37.141', 'enterprice': '26844', 'countrevence': '0', 'unrealprofit': '83567.25', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '29094', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=1
--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=1, self.total=996015.990996, self.flagDict['side']='buy', self.tradeCount=1, self.count=24257
self.closeSec=1691310299, self.tradeDate='20230806', self.openTime='162000', self.closeTime='162459', self.symbol='BTCUSDT', self.open=29093.1, self.close=29093.0, self.high=29104.5, self.low=29093.0, self.vol=632.922, self.amt=18417357.7499 
127.0.0.1 - - [06/Aug/2023 16:25:00] "POST / HTTP/1.1" 200 -
2023-08-06 16:25:00,783:INFO:sr_min:main.py:172:handleKline:2219263: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5952  20230806   160000    160459  ...         0.0        0.0       0
5953  20230806   160500    160959  ...         0.0        0.0       0
5954  20230806   161000    161459  ...         0.0        0.0       0
5955  20230806   161500    161959  ...         0.0        0.0       0
5956  20230806   162000    162459  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-08-06 16:25:00,783:INFO:sr_min:main.py:175:handleKline:2219263: self.closeSec=1691310299, self.tradeDate='20230806', self.openTime='162000', self.closeTime='162459',self.symbol='BTCUSDT',self.open=29093.1, self.close=29093.0, self.high=29104.5, self.low=29093.0, self.vol=632.922, self.amt=18417357.7499, ukdf['pct'].iloc[-1]=0.0 , ukdf['amount'].iloc[-1]=18417357.7499, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5956, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '37.141', 'enterprice': '26844', 'countrevence': '0', 'unrealprofit': '83750.71040372114', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '29098.93956554', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=1


## /root/FIL/strategy/s_rsrs/log.txt ----- -----

721  20230806   040000    075959  1691279999  ...    721  0.826976  2.381697     1.0
722  20230806   080000    115959  1691294399  ...    722  0.845992  2.364724     1.0

[5 rows x 15 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '54.775', 'enterprice': '29034.8', 'countrevence': '0', 'unrealprofit': '1018.815', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '29053.4', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'numpy.int64'>, curSign=1, self.sign=1
--handleKline--:  version='2.0.0', self.name='s_rsrs', self.symbol='BTCUSDT', interval='4h', intervalSec=14400, wid=25, thd=0.6, self.sign=1, self.total=1588790.78883, self.flagDict['side']='buy', self.tradeCount=17, self.count=505
self.closeSec=1691308799, self.tradeDate='20230806', self.openTime='120000', self.closeTime='155959', self.symbol='BTCUSDT', self.open=29053.5, self.close=29081.3, self.high=29100.0, self.low=29028.0, self.vol=11457.436, self.amt=333044294.0906 
127.0.0.1 - - [06/Aug/2023 16:00:01] "POST / HTTP/1.1" 200 -
2023-08-06 16:00:01,620:INFO:s_rsrs:main.py:141:handleKline:2218689: self.closeSec=1691308799, self.tradeDate='20230806', self.openTime='120000', self.closeTime='155959',self.symbol='BTCUSDT',self.open=29053.5, self.close=29081.3, self.high=29100.0, self.low=29028.0, self.vol=11457.436, self.amt=333044294.0906 
2023-08-06 16:00:01,637:INFO:s_rsrs:main.py:142:handleKline:2218689: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime  ...        vol           amt       pct
719  20230805   200000    235959  ...  25947.755  7.529701e+08 -0.000282
720  20230806   000000    035959  ...  11614.747  3.373902e+08  0.000844
721  20230806   040000    075959  ...   6586.050  1.913999e+08  0.000028
722  20230806   080000    115959  ...   8174.351  2.374513e+08 -0.000145
723  20230806   120000    155959  ...  11457.436  3.330443e+08  0.000957

[5 rows x 11 columns]
2023-08-06 16:00:02,409:INFO:s_rsrs:main.py:151:handleKline:2218689: df_s.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec  ...  index      beta    zscore  signal
719  20230805   200000    235959  1691251199  ...    719  0.554096  1.233047     1.0
720  20230806   000000    035959  1691265599  ...    720  0.660057  1.694509     1.0
721  20230806   040000    075959  1691279999  ...    721  0.826976  2.381697     1.0
722  20230806   080000    115959  1691294399  ...    722  0.845992  2.364724     1.0
723  20230806   120000    155959  1691308799  ...    723  0.439198  0.519806     NaN

[5 rows x 15 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '54.775', 'enterprice': '29034.8', 'countrevence': '0', 'unrealprofit': '2547.0375', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '29081.3', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'numpy.int64'>, curSign=-9223372036854775808, self.sign=1


