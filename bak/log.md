# 20230815 16:26:01

## /root/FIL/strategy/amihud/log.txt ----- -----

--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=373746.4768026, self.flagDict['side']='sell', self.tradeCount=2, self.count=26848
self.closeSec=1692087599, self.tradeDate='20230815', self.openTime='161500', self.closeTime='161959', self.symbol='BTCUSDT', self.open=29392.6, self.close=29411.7, self.high=29411.8, self.low=29392.6, self.vol=654.841, self.amt=19253501.8371 
127.0.0.1 - - [15/Aug/2023 16:20:01] "POST / HTTP/1.1" 200 -
2023-08-15 16:20:06,812:INFO:amihud:main.py:172:handleKline:2219019: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5951  20230815   155500    155959  ...         0.0        0.0       0
5952  20230815   160000    160459  ...         0.0        0.0       0
5953  20230815   160500    160959  ...         0.0        0.0       0
5954  20230815   161000    161459  ...         0.0        0.0       0
5955  20230815   161500    161959  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-08-15 16:20:06,842:INFO:amihud:main.py:175:handleKline:2219019: self.closeSec=1692087599, self.tradeDate='20230815', self.openTime='161500', self.closeTime='161959',self.symbol='BTCUSDT',self.open=29392.6, self.close=29411.7, self.high=29411.8, self.low=29392.6, self.vol=654.841, self.amt=19253501.8371, ukdf['pct'].iloc[-1]=0.00065 , ukdf['amount'].iloc[-1]=19253501.8371, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5955, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '13.926', 'enterprice': '26864.9', 'countrevence': '0', 'unrealprofit': '-35428.98371884014', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '29408.98902189', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1
127.0.0.1 - - [15/Aug/2023 16:25:00] "POST / HTTP/1.1" 200 -
--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=373746.4768026, self.flagDict['side']='sell', self.tradeCount=2, self.count=26849
self.closeSec=1692087899, self.tradeDate='20230815', self.openTime='162000', self.closeTime='162459', self.symbol='BTCUSDT', self.open=29409.1, self.close=29411.5, self.high=29411.6, self.low=29405.5, self.vol=237.048, self.amt=6971328.8627 
2023-08-15 16:25:00,805:INFO:amihud:main.py:172:handleKline:2219019: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5952  20230815   160000    160459  ...         0.0        0.0       0
5953  20230815   160500    160959  ...         0.0        0.0       0
5954  20230815   161000    161459  ...         0.0        0.0       0
5955  20230815   161500    161959  ...         0.0        0.0       0
5956  20230815   162000    162459  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-08-15 16:25:00,806:INFO:amihud:main.py:175:handleKline:2219019: self.closeSec=1692087899, self.tradeDate='20230815', self.openTime='162000', self.closeTime='162459',self.symbol='BTCUSDT',self.open=29409.1, self.close=29411.5, self.high=29411.6, self.low=29405.5, self.vol=237.048, self.amt=6971328.8627, ukdf['pct'].iloc[-1]=-7e-06 , ukdf['amount'].iloc[-1]=6971328.8627, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5956, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '13.926', 'enterprice': '26864.9', 'countrevence': '0', 'unrealprofit': '-35463.9516', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '29411.5', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1


## /root/FIL/strategy/factorcheck/log.txt ----- -----


self.closeSec=1692087599, self.tradeDate='20230815', self.openTime='161500', self.closeTime='161959', self.symbol='BTCUSDT', self.open=29392.6, self.close=29411.7, self.high=29411.8, self.low=29392.6 
127.0.0.1 - - [15/Aug/2023 16:20:01] "POST / HTTP/1.1" 200 -
2023-08-15 16:20:04,502:INFO:factorcheck2:main.py:126:handleKline:2218005: self.closeSec=1692087599, self.tradeDate='20230815', self.openTime='161500', self.closeTime='161959',self.symbol='BTCUSDT',self.open=29392.6, self.close=29411.7, self.high=29411.8, self.low=29392.6   
2023-08-15 16:20:05,771:INFO:factorcheck2:main.py:127:handleKline:2218005: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime    closeSec  ...      low       pct  index  idx
1631  20230815   155500    155959  1692086399  ...  29394.4 -0.000269   1631    5
1632  20230815   160000    160459  1692086699  ...  29389.1 -0.000143   1632    0
1633  20230815   160500    160959  1692086999  ...  29388.3 -0.000061   1633    1
1634  20230815   161000    161459  1692087299  ...  29390.7  0.000061   1634    2
1635  20230815   161500    161959  1692087599  ...  29392.6  0.000650   1635    3

[5 rows x 11 columns]
2023-08-15 16:20:05,782:INFO:factorcheck2:main.py:128:handleKline:2218005: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}
127.0.0.1 - - [15/Aug/2023 16:25:00] "POST / HTTP/1.1" 200 -

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=4, self.factor=0.5523254116999019, self.count=26851 

self.closeSec=1692087899, self.tradeDate='20230815', self.openTime='162000', self.closeTime='162459', self.symbol='BTCUSDT', self.open=29409.1, self.close=29411.5, self.high=29411.6, self.low=29405.5 
2023-08-15 16:25:00,782:INFO:factorcheck2:main.py:126:handleKline:2218005: self.closeSec=1692087899, self.tradeDate='20230815', self.openTime='162000', self.closeTime='162459',self.symbol='BTCUSDT',self.open=29409.1, self.close=29411.5, self.high=29411.6, self.low=29405.5   
2023-08-15 16:25:00,796:INFO:factorcheck2:main.py:127:handleKline:2218005: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime    closeSec  ...      low       pct  index  idx
1632  20230815   160000    160459  1692086699  ...  29389.1 -0.000143   1632    0
1633  20230815   160500    160959  1692086999  ...  29388.3 -0.000061   1633    1
1634  20230815   161000    161459  1692087299  ...  29390.7  0.000061   1634    2
1635  20230815   161500    161959  1692087599  ...  29392.6  0.000650   1635    3
1636  20230815   162000    162459  1692087899  ...  29405.5 -0.000007   1636    4

[5 rows x 11 columns]
2023-08-15 16:25:00,796:INFO:factorcheck2:main.py:128:handleKline:2218005: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}


## /root/FIL/strategy/logic/log.txt ----- -----

2023-08-15 16:00:19,831:DEBUG:logic:main.py:463:getModel:2218526: df_s.iloc[-5:,:] :
          date closeTime     open  ...    alpha58   alpha67   alpha72
5786  20230815    132959  29366.4  ...  46.666667  0.490425  0.539453
5787  20230815    135959  29382.9  ...  46.250000  0.481071  0.551436
5788  20230815    142959  29360.3  ...  46.250000  0.477231  0.563987
5789  20230815    145959  29351.1  ...  46.666667  0.482936  0.573849
5790  20230815    152959  29363.8  ...  46.250000  0.475830  0.585538

[5 rows x 33 columns]
0.544280442804428
acc is : 0.544280442804428
2023-08-15 16:00:19,906:INFO:logic:main.py:468:getModel:2218526: df_pred.iloc[-5:,:] :
     pred    prob_0    prob_1  actual  ...       nav  sign  cost_        bm
537     0  0.509469  0.490531       0  ...  1.013972  -1.0    0.0  1.004733
538     0  0.500073  0.499927       0  ...  1.014293  -1.0    0.0  1.004414
539     0  0.503114  0.496886       1  ...  1.013857  -1.0    0.0  1.004846
540     0  0.511623  0.488377       0  ...  1.014441  -1.0    0.0  1.004267
541     0  0.504320  0.495680       1  ...  1.012709  -1.0    0.0  1.005982

[5 rows x 10 columns]
2023-08-15 16:00:19,920:INFO:logic:main.py:478:getModel:2218526: df_panel.iloc[-5:,:] :
    pred    prob_0    prob_1  actual  ...       nav  sign  cost_        bm
45     0  0.509511  0.490489       0  ...  1.013972  -1.0    0.0  1.004777
46     0  0.501882  0.498118       0  ...  0.993456   1.0    0.0  1.005553
47     0  0.503387  0.496613       1  ...  1.013857  -1.0    0.0  1.006292
48     0  0.512031  0.487969       0  ...  1.014441  -1.0    0.0  1.005823
49     0  0.504320  0.495680       1  ...  1.012709  -1.0    0.0  1.005982

[5 rows x 10 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '23.741', 'enterprice': '29362.7', 'countrevence': '0', 'unrealprofit': '-840.4314', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '29398.1', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}


## /root/FIL/strategy/modifiedmom/log.txt ----- -----

527  20230815   155000    155959  1692086399    29422  29396.9 -0.000880
2023-08-15 16:00:02,073:INFO:modifiedmom:main.py:146:handleKline:2218259: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': True, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True}
127.0.0.1 - - [15/Aug/2023 16:10:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=13424 

self.closeSec=1692086999, self.tradeDate='20230815', self.openTime='160000', self.closeTime='160959', self.symbol='BTCUSDT', self.open='29396.9', self.close='29390.8'
2023-08-15 16:10:01,133:INFO:modifiedmom:main.py:144:handleKline:2218259: self.closeSec=1692086999, self.tradeDate='20230815', self.openTime='160000', self.closeTime='160959',self.symbol='BTCUSDT',self.open='29396.9', self.close='29390.8'
2023-08-15 16:10:01,141:INFO:modifiedmom:main.py:145:handleKline:2218259: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec     open    close       pct
524  20230815   152000    152959  1692084599  29358.5  29346.8 -0.000399
525  20230815   153000    153959  1692085199  29346.8  29369.6  0.000777
526  20230815   154000    154959  1692085799  29369.6  29422.8  0.001811
527  20230815   155000    155959  1692086399    29422  29396.9 -0.000880
528  20230815   160000    160959  1692086999  29396.9  29390.8 -0.000208
2023-08-15 16:10:01,142:INFO:modifiedmom:main.py:146:handleKline:2218259: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': True, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True}

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=13425 

self.closeSec=1692087599, self.tradeDate='20230815', self.openTime='161000', self.closeTime='161959', self.symbol='BTCUSDT', self.open='29390.7', self.close='29411.7'
127.0.0.1 - - [15/Aug/2023 16:20:04] "POST / HTTP/1.1" 200 -
2023-08-15 16:20:06,922:INFO:modifiedmom:main.py:144:handleKline:2218259: self.closeSec=1692087599, self.tradeDate='20230815', self.openTime='161000', self.closeTime='161959',self.symbol='BTCUSDT',self.open='29390.7', self.close='29411.7'
2023-08-15 16:20:07,481:INFO:modifiedmom:main.py:145:handleKline:2218259: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec     open    close       pct
525  20230815   153000    153959  1692085199  29346.8  29369.6  0.000777
526  20230815   154000    154959  1692085799  29369.6  29422.8  0.001811
527  20230815   155000    155959  1692086399    29422  29396.9 -0.000880
528  20230815   160000    160959  1692086999  29396.9  29390.8 -0.000208
529  20230815   161000    161959  1692087599  29390.7  29411.7  0.000711
2023-08-15 16:20:07,481:INFO:modifiedmom:main.py:146:handleKline:2218259: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': True, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True}


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

17519  20230815   155000    155959  1692086399    29422  29396.9
2023-08-15 16:00:02,075:INFO:pyemd2:main.py:127:handleKline:2217508: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}
127.0.0.1 - - [15/Aug/2023 16:10:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=13427 

self.closeSec=1692086999, self.tradeDate='20230815', self.openTime='160000', self.closeTime='160959', self.symbol='BTCUSDT', self.open='29396.9', self.close='29390.8'
2023-08-15 16:10:01,147:INFO:pyemd2:main.py:125:handleKline:2217508: self.closeSec=1692086999, self.tradeDate='20230815', self.openTime='160000', self.closeTime='160959',self.symbol='BTCUSDT',self.open='29396.9', self.close='29390.8'
2023-08-15 16:10:01,154:INFO:pyemd2:main.py:126:handleKline:2217508: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
17516  20230815   152000    152959  1692084599  29358.5  29346.8
17517  20230815   153000    153959  1692085199  29346.8  29369.6
17518  20230815   154000    154959  1692085799  29369.6  29422.8
17519  20230815   155000    155959  1692086399    29422  29396.9
17520  20230815   160000    160959  1692086999  29396.9  29390.8
2023-08-15 16:10:01,154:INFO:pyemd2:main.py:127:handleKline:2217508: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=13428 

self.closeSec=1692087599, self.tradeDate='20230815', self.openTime='161000', self.closeTime='161959', self.symbol='BTCUSDT', self.open='29390.7', self.close='29411.7'
127.0.0.1 - - [15/Aug/2023 16:20:04] "POST / HTTP/1.1" 200 -
2023-08-15 16:20:08,809:INFO:pyemd2:main.py:125:handleKline:2217508: self.closeSec=1692087599, self.tradeDate='20230815', self.openTime='161000', self.closeTime='161959',self.symbol='BTCUSDT',self.open='29390.7', self.close='29411.7'
2023-08-15 16:20:08,887:INFO:pyemd2:main.py:126:handleKline:2217508: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
17517  20230815   153000    153959  1692085199  29346.8  29369.6
17518  20230815   154000    154959  1692085799  29369.6  29422.8
17519  20230815   155000    155959  1692086399    29422  29396.9
17520  20230815   160000    160959  1692086999  29396.9  29390.8
17521  20230815   161000    161959  1692087599  29390.7  29411.7
2023-08-15 16:20:08,888:INFO:pyemd2:main.py:127:handleKline:2217508: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}


## /root/FIL/strategy/similarity/log.txt ----- -----

12191  20230815   155000    155959  1692086399    29422  29396.9
2023-08-15 16:00:02,070:INFO:testStrategy:main.py:103:handleKline:2217133: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': True, 'isOpenSell': False, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True, 'isCorr': False}

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=13427 

self.closeSec=1692086999, self.tradeDate='20230815', self.openTime='160000', self.closeTime='160959', self.symbol='BTCUSDT', self.open='29396.9', self.close='29390.8'
2023-08-15 16:10:01,135:INFO:testStrategy:main.py:101:handleKline:2217133: self.closeSec=1692086999, self.tradeDate='20230815', self.openTime='160000', self.closeTime='160959',self.symbol='BTCUSDT',self.open='29396.9', self.close='29390.8'
127.0.0.1 - - [15/Aug/2023 16:10:01] "POST / HTTP/1.1" 200 -
2023-08-15 16:10:01,141:INFO:testStrategy:main.py:102:handleKline:2217133: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
12188  20230815   152000    152959  1692084599  29358.5  29346.8
12189  20230815   153000    153959  1692085199  29346.8  29369.6
12190  20230815   154000    154959  1692085799  29369.6  29422.8
12191  20230815   155000    155959  1692086399    29422  29396.9
12192  20230815   160000    160959  1692086999  29396.9  29390.8
2023-08-15 16:10:01,143:INFO:testStrategy:main.py:103:handleKline:2217133: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': True, 'isOpenSell': False, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True, 'isCorr': False}

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=13428 

self.closeSec=1692087599, self.tradeDate='20230815', self.openTime='161000', self.closeTime='161959', self.symbol='BTCUSDT', self.open='29390.7', self.close='29411.7'
127.0.0.1 - - [15/Aug/2023 16:20:04] "POST / HTTP/1.1" 200 -
2023-08-15 16:20:08,627:INFO:testStrategy:main.py:101:handleKline:2217133: self.closeSec=1692087599, self.tradeDate='20230815', self.openTime='161000', self.closeTime='161959',self.symbol='BTCUSDT',self.open='29390.7', self.close='29411.7'
2023-08-15 16:20:08,784:INFO:testStrategy:main.py:102:handleKline:2217133: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
12189  20230815   153000    153959  1692085199  29346.8  29369.6
12190  20230815   154000    154959  1692085799  29369.6  29422.8
12191  20230815   155000    155959  1692086399    29422  29396.9
12192  20230815   160000    160959  1692086999  29396.9  29390.8
12193  20230815   161000    161959  1692087599  29390.7  29411.7
2023-08-15 16:20:08,784:INFO:testStrategy:main.py:103:handleKline:2217133: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': True, 'isOpenSell': False, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True, 'isCorr': False}


## /root/FIL/strategy/sr_min/log.txt ----- -----

--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=1, self.total=996015.990996, self.flagDict['side']='buy', self.tradeCount=1, self.count=26848
self.closeSec=1692087599, self.tradeDate='20230815', self.openTime='161500', self.closeTime='161959', self.symbol='BTCUSDT', self.open=29392.6, self.close=29411.7, self.high=29411.8, self.low=29392.6, self.vol=654.841, self.amt=19253501.8371 
127.0.0.1 - - [15/Aug/2023 16:20:01] "POST / HTTP/1.1" 200 -
2023-08-15 16:20:06,621:INFO:sr_min:main.py:172:handleKline:2219263: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5951  20230815   155500    155959  ...         0.0        0.0       0
5952  20230815   160000    160459  ...         0.0        0.0       0
5953  20230815   160500    160959  ...         0.0        0.0       0
5954  20230815   161000    161459  ...         0.0        0.0       0
5955  20230815   161500    161959  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-08-15 16:20:06,644:INFO:sr_min:main.py:175:handleKline:2219263: self.closeSec=1692087599, self.tradeDate='20230815', self.openTime='161500', self.closeTime='161959',self.symbol='BTCUSDT',self.open=29392.6, self.close=29411.7, self.high=29411.8, self.low=29392.6, self.vol=654.841, self.amt=19253501.8371, ukdf['pct'].iloc[-1]=0.00065 , ukdf['amount'].iloc[-1]=19253501.8371, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5955, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '37.141', 'enterprice': '26844', 'countrevence': '0', 'unrealprofit': '95266.25726201649', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '29408.98902189', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=1
127.0.0.1 - - [15/Aug/2023 16:25:00] "POST / HTTP/1.1" 200 -
--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=1, self.total=996015.990996, self.flagDict['side']='buy', self.tradeCount=1, self.count=26849
self.closeSec=1692087899, self.tradeDate='20230815', self.openTime='162000', self.closeTime='162459', self.symbol='BTCUSDT', self.open=29409.1, self.close=29411.5, self.high=29411.6, self.low=29405.5, self.vol=237.048, self.amt=6971328.8627 
2023-08-15 16:25:00,812:INFO:sr_min:main.py:172:handleKline:2219263: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5952  20230815   160000    160459  ...         0.0        0.0       0
5953  20230815   160500    160959  ...         0.0        0.0       0
5954  20230815   161000    161459  ...         0.0        0.0       0
5955  20230815   161500    161959  ...         0.0        0.0       0
5956  20230815   162000    162459  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-08-15 16:25:00,812:INFO:sr_min:main.py:175:handleKline:2219263: self.closeSec=1692087899, self.tradeDate='20230815', self.openTime='162000', self.closeTime='162459',self.symbol='BTCUSDT',self.open=29409.1, self.close=29411.5, self.high=29411.6, self.low=29405.5, self.vol=237.048, self.amt=6971328.8627, ukdf['pct'].iloc[-1]=-7e-06 , ukdf['amount'].iloc[-1]=6971328.8627, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5956, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '37.141', 'enterprice': '26844', 'countrevence': '0', 'unrealprofit': '95359.5175', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '29411.5', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=1


## /root/FIL/strategy/s_rsrs/log.txt ----- -----

721  20230815   040000    075959  1692057599  ...    721  0.000146 -1.148049    -1.0
722  20230815   080000    115959  1692071999  ...    722  0.000251 -1.142154    -1.0

[5 rows x 15 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '51.388', 'enterprice': '29432.6', 'countrevence': '0', 'unrealprofit': '2269.11190799836', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '29388.44354503', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'numpy.int64'>, curSign=-1, self.sign=-1
--handleKline--:  version='2.0.0', self.name='s_rsrs', self.symbol='BTCUSDT', interval='4h', intervalSec=14400, wid=25, thd=0.6, self.sign=-1, self.total=1510969.9663512, self.flagDict['side']='sell', self.tradeCount=20, self.count=559
self.closeSec=1692086399, self.tradeDate='20230815', self.openTime='120000', self.closeTime='155959', self.symbol='BTCUSDT', self.open=29386.9, self.close=29396.8, self.high=29422.9, self.low=29338.9, self.vol=14399.12, self.amt=422935622.2463 
127.0.0.1 - - [15/Aug/2023 16:00:01] "POST / HTTP/1.1" 200 -
2023-08-15 16:00:01,617:INFO:s_rsrs:main.py:141:handleKline:2218689: self.closeSec=1692086399, self.tradeDate='20230815', self.openTime='120000', self.closeTime='155959',self.symbol='BTCUSDT',self.open=29386.9, self.close=29396.8, self.high=29422.9, self.low=29338.9, self.vol=14399.12, self.amt=422935622.2463 
2023-08-15 16:00:01,635:INFO:s_rsrs:main.py:142:handleKline:2218689: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime  ...        vol           amt       pct
719  20230814   200000    235959  ...  80846.779  2.385466e+09  0.006568
720  20230815   000000    035959  ...  81315.670  2.394447e+09 -0.008080
721  20230815   040000    075959  ...  17851.488  5.248545e+08  0.002238
722  20230815   080000    115959  ...  14493.260  4.260585e+08 -0.001108
723  20230815   120000    155959  ...  14399.120  4.229356e+08  0.000337

[5 rows x 11 columns]
2023-08-15 16:00:02,471:INFO:s_rsrs:main.py:151:handleKline:2218689: df_s.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec  ...  index      beta    zscore  signal
719  20230814   200000    235959  1692028799  ...    719  0.000513 -1.156555    -1.0
720  20230815   000000    035959  1692043199  ...    720  0.000152 -1.153554    -1.0
721  20230815   040000    075959  1692057599  ...    721  0.000146 -1.148049    -1.0
722  20230815   080000    115959  1692071999  ...    722  0.000251 -1.142154    -1.0
723  20230815   120000    155959  1692086399  ...    723  0.000267 -1.136717    -1.0

[5 rows x 15 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '51.388', 'enterprice': '29432.6', 'countrevence': '0', 'unrealprofit': '1772.886', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '29398.1', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'numpy.int64'>, curSign=-1, self.sign=-1


