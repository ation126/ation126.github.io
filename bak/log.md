# 20230805 16:26:02

## /root/FIL/strategy/amihud/log.txt ----- -----

--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=373746.4768026, self.flagDict['side']='sell', self.tradeCount=2, self.count=23968
self.closeSec=1691223599, self.tradeDate='20230805', self.openTime='161500', self.closeTime='161959', self.symbol='BTCUSDT', self.open=29037.3, self.close=29037.3, self.high=29045.3, self.low=29037.3, self.vol=218.032, self.amt=6331655.484 
127.0.0.1 - - [05/Aug/2023 16:20:01] "POST / HTTP/1.1" 200 -
2023-08-05 16:20:06,272:INFO:amihud:main.py:172:handleKline:2219019: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5951  20230805   155500    155959  ...         0.0        0.0       0
5952  20230805   160000    160459  ...         0.0        0.0       0
5953  20230805   160500    160959  ...         0.0        0.0       0
5954  20230805   161000    161459  ...         0.0        0.0       0
5955  20230805   161500    161959  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-08-05 16:20:06,292:INFO:amihud:main.py:175:handleKline:2219019: self.closeSec=1691223599, self.tradeDate='20230805', self.openTime='161500', self.closeTime='161959',self.symbol='BTCUSDT',self.open=29037.3, self.close=29037.3, self.high=29045.3, self.low=29037.3, self.vol=218.032, self.amt=6331655.484, ukdf['pct'].iloc[-1]=0.0 , ukdf['amount'].iloc[-1]=6331655.484, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5955, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '13.926', 'enterprice': '26864.9', 'countrevence': '0', 'unrealprofit': '-30278.34162012528', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '29039.13105128', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1
127.0.0.1 - - [05/Aug/2023 16:25:00] "POST / HTTP/1.1" 200 -
--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=373746.4768026, self.flagDict['side']='sell', self.tradeCount=2, self.count=23969
self.closeSec=1691223899, self.tradeDate='20230805', self.openTime='162000', self.closeTime='162459', self.symbol='BTCUSDT', self.open=29037.3, self.close=29037.9, self.high=29045.3, self.low=29037.3, self.vol=224.912, self.amt=6531815.3423 
2023-08-05 16:25:00,776:INFO:amihud:main.py:172:handleKline:2219019: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5952  20230805   160000    160459  ...         0.0        0.0       0
5953  20230805   160500    160959  ...         0.0        0.0       0
5954  20230805   161000    161459  ...         0.0        0.0       0
5955  20230805   161500    161959  ...         0.0        0.0       0
5956  20230805   162000    162459  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-08-05 16:25:00,777:INFO:amihud:main.py:175:handleKline:2219019: self.closeSec=1691223899, self.tradeDate='20230805', self.openTime='162000', self.closeTime='162459',self.symbol='BTCUSDT',self.open=29037.3, self.close=29037.9, self.high=29045.3, self.low=29037.3, self.vol=224.912, self.amt=6531815.3423, ukdf['pct'].iloc[-1]=2.1e-05 , ukdf['amount'].iloc[-1]=6531815.3423, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5956, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '13.926', 'enterprice': '26864.9', 'countrevence': '0', 'unrealprofit': '-30284.88444262512', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '29039.60087912', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1


## /root/FIL/strategy/factorcheck/log.txt ----- -----


self.closeSec=1691223599, self.tradeDate='20230805', self.openTime='161500', self.closeTime='161959', self.symbol='BTCUSDT', self.open=29037.3, self.close=29037.3, self.high=29045.3, self.low=29037.3 
127.0.0.1 - - [05/Aug/2023 16:20:01] "POST / HTTP/1.1" 200 -
2023-08-05 16:20:04,493:INFO:factorcheck2:main.py:126:handleKline:2218005: self.closeSec=1691223599, self.tradeDate='20230805', self.openTime='161500', self.closeTime='161959',self.symbol='BTCUSDT',self.open=29037.3, self.close=29037.3, self.high=29045.3, self.low=29037.3   
2023-08-05 16:20:05,483:INFO:factorcheck2:main.py:127:handleKline:2218005: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime    closeSec  ...      low       pct  index  idx
1631  20230805   155500    155959  1691222399  ...  29037.8 -0.000121   1631    5
1632  20230805   160000    160459  1691222699  ...  29030.1  0.000072   1632    0
1633  20230805   160500    160959  1691222999  ...  29033.8 -0.000210   1633    1
1634  20230805   161000    161459  1691223299  ...  29033.7  0.000121   1634    2
1635  20230805   161500    161959  1691223599  ...  29037.3  0.000000   1635    3

[5 rows x 11 columns]
2023-08-05 16:20:05,484:INFO:factorcheck2:main.py:128:handleKline:2218005: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=43, self.factor=0.5778516745798601, self.count=23971 

self.closeSec=1691223899, self.tradeDate='20230805', self.openTime='162000', self.closeTime='162459', self.symbol='BTCUSDT', self.open=29037.3, self.close=29037.9, self.high=29045.3, self.low=29037.3 
127.0.0.1 - - [05/Aug/2023 16:25:00] "POST / HTTP/1.1" 200 -
2023-08-05 16:25:00,765:INFO:factorcheck2:main.py:126:handleKline:2218005: self.closeSec=1691223899, self.tradeDate='20230805', self.openTime='162000', self.closeTime='162459',self.symbol='BTCUSDT',self.open=29037.3, self.close=29037.9, self.high=29045.3, self.low=29037.3   
2023-08-05 16:25:00,784:INFO:factorcheck2:main.py:127:handleKline:2218005: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime    closeSec  ...      low       pct  index  idx
1632  20230805   160000    160459  1691222699  ...  29030.1  0.000072   1632    0
1633  20230805   160500    160959  1691222999  ...  29033.8 -0.000210   1633    1
1634  20230805   161000    161459  1691223299  ...  29033.7  0.000121   1634    2
1635  20230805   161500    161959  1691223599  ...  29037.3  0.000000   1635    3
1636  20230805   162000    162459  1691223899  ...  29037.3  0.000021   1636    4

[5 rows x 11 columns]
2023-08-05 16:25:00,784:INFO:factorcheck2:main.py:128:handleKline:2218005: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}


## /root/FIL/strategy/logic/log.txt ----- -----

2023-08-05 16:00:18,073:DEBUG:logic:main.py:463:getModel:2218526: df_s.iloc[-5:,:] :
          date closeTime     open  ...    alpha58   alpha67   alpha72
5786  20230805    132959  29045.0  ...  45.416667  0.470925  0.503658
5787  20230805    135959  29074.8  ...  45.833333  0.475424  0.499123
5788  20230805    142959  29086.9  ...  45.416667  0.468338  0.497478
5789  20230805    145959  29065.7  ...  45.416667  0.465053  0.497143
5790  20230805    152959  29055.9  ...  45.416667  0.458160  0.499356

[5 rows x 33 columns]
0.5608856088560885
acc is : 0.5608856088560885
2023-08-05 16:00:18,146:INFO:logic:main.py:468:getModel:2218526: df_pred.iloc[-5:,:] :
     pred    prob_0    prob_1  actual  ...       nav  sign  cost_        bm
537     0  0.510350  0.489650       1  ...  0.945085   1.0    0.0  0.999436
538     0  0.506715  0.493285       0  ...  0.944399   1.0    0.0  0.998711
539     1  0.497687  0.502313       0  ...  0.944081   1.0    0.0  0.998375
540     1  0.499712  0.500288       0  ...  0.943411   1.0    0.0  0.997667
541     1  0.497620  0.502380       1  ...  0.943493   1.0    0.0  0.997753

[5 rows x 10 columns]
2023-08-05 16:00:18,160:INFO:logic:main.py:478:getModel:2218526: df_panel.iloc[-5:,:] :
    pred    prob_0    prob_1  actual  ...       nav  sign  cost_        bm
45     0  0.510001  0.489999       1  ...  0.945085   1.0    0.0  0.997760
46     0  0.506453  0.493547       0  ...  0.944399   1.0    0.0  0.996237
47     1  0.497599  0.502401       0  ...  0.944081   1.0    0.0  0.996304
48     1  0.499789  0.500211       0  ...  0.943411   1.0    0.0  0.995655
49     1  0.497620  0.502380       1  ...  0.943493   1.0    0.0  0.997753

[5 rows x 10 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '24.06', 'enterprice': '29131.5', 'countrevence': '0', 'unrealprofit': '-2341.9140424044', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '29034.16358926', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}


## /root/FIL/strategy/modifiedmom/log.txt ----- -----

527  20230805   155000    155959  1691222399  29049.5  29037.9 -0.000399
2023-08-05 16:00:02,051:INFO:modifiedmom:main.py:146:handleKline:2218259: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': True, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True}

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=11984 

self.closeSec=1691222999, self.tradeDate='20230805', self.openTime='160000', self.closeTime='160959', self.symbol='BTCUSDT', self.open='29037.9', self.close='29033.8'
2023-08-05 16:10:01,119:INFO:modifiedmom:main.py:144:handleKline:2218259: self.closeSec=1691222999, self.tradeDate='20230805', self.openTime='160000', self.closeTime='160959',self.symbol='BTCUSDT',self.open='29037.9', self.close='29033.8'
127.0.0.1 - - [05/Aug/2023 16:10:01] "POST / HTTP/1.1" 200 -
2023-08-05 16:10:01,136:INFO:modifiedmom:main.py:145:handleKline:2218259: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec     open    close       pct
524  20230805   152000    152959  1691220599  29049.4  29035.4 -0.000478
525  20230805   153000    153959  1691221199  29035.4  29047.3  0.000410
526  20230805   154000    154959  1691221799  29047.3  29049.5  0.000076
527  20230805   155000    155959  1691222399  29049.5  29037.9 -0.000399
528  20230805   160000    160959  1691222999  29037.9  29033.8 -0.000141
2023-08-05 16:10:01,136:INFO:modifiedmom:main.py:146:handleKline:2218259: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': True, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True}

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=11985 

self.closeSec=1691223599, self.tradeDate='20230805', self.openTime='161000', self.closeTime='161959', self.symbol='BTCUSDT', self.open='29033.8', self.close='29037.3'
127.0.0.1 - - [05/Aug/2023 16:20:04] "POST / HTTP/1.1" 200 -
2023-08-05 16:20:06,573:INFO:modifiedmom:main.py:144:handleKline:2218259: self.closeSec=1691223599, self.tradeDate='20230805', self.openTime='161000', self.closeTime='161959',self.symbol='BTCUSDT',self.open='29033.8', self.close='29037.3'
2023-08-05 16:20:07,203:INFO:modifiedmom:main.py:145:handleKline:2218259: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec     open    close       pct
525  20230805   153000    153959  1691221199  29035.4  29047.3  0.000410
526  20230805   154000    154959  1691221799  29047.3  29049.5  0.000076
527  20230805   155000    155959  1691222399  29049.5  29037.9 -0.000399
528  20230805   160000    160959  1691222999  29037.9  29033.8 -0.000141
529  20230805   161000    161959  1691223599  29033.8  29037.3  0.000121
2023-08-05 16:20:07,212:INFO:modifiedmom:main.py:146:handleKline:2218259: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': True, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True}


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

17519  20230805   155000    155959  1691222399  29049.5  29037.9
2023-08-05 16:00:02,062:INFO:pyemd2:main.py:127:handleKline:2217508: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}
127.0.0.1 - - [05/Aug/2023 16:10:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=11987 

self.closeSec=1691222999, self.tradeDate='20230805', self.openTime='160000', self.closeTime='160959', self.symbol='BTCUSDT', self.open='29037.9', self.close='29033.8'
2023-08-05 16:10:01,122:INFO:pyemd2:main.py:125:handleKline:2217508: self.closeSec=1691222999, self.tradeDate='20230805', self.openTime='160000', self.closeTime='160959',self.symbol='BTCUSDT',self.open='29037.9', self.close='29033.8'
2023-08-05 16:10:01,131:INFO:pyemd2:main.py:126:handleKline:2217508: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
17516  20230805   152000    152959  1691220599  29049.4  29035.4
17517  20230805   153000    153959  1691221199  29035.4  29047.3
17518  20230805   154000    154959  1691221799  29047.3  29049.5
17519  20230805   155000    155959  1691222399  29049.5  29037.9
17520  20230805   160000    160959  1691222999  29037.9  29033.8
2023-08-05 16:10:01,131:INFO:pyemd2:main.py:127:handleKline:2217508: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=11988 

self.closeSec=1691223599, self.tradeDate='20230805', self.openTime='161000', self.closeTime='161959', self.symbol='BTCUSDT', self.open='29033.8', self.close='29037.3'
127.0.0.1 - - [05/Aug/2023 16:20:04] "POST / HTTP/1.1" 200 -
2023-08-05 16:20:08,317:INFO:pyemd2:main.py:125:handleKline:2217508: self.closeSec=1691223599, self.tradeDate='20230805', self.openTime='161000', self.closeTime='161959',self.symbol='BTCUSDT',self.open='29033.8', self.close='29037.3'
2023-08-05 16:20:08,431:INFO:pyemd2:main.py:126:handleKline:2217508: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
17517  20230805   153000    153959  1691221199  29035.4  29047.3
17518  20230805   154000    154959  1691221799  29047.3  29049.5
17519  20230805   155000    155959  1691222399  29049.5  29037.9
17520  20230805   160000    160959  1691222999  29037.9  29033.8
17521  20230805   161000    161959  1691223599  29033.8  29037.3
2023-08-05 16:20:08,431:INFO:pyemd2:main.py:127:handleKline:2217508: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}


## /root/FIL/strategy/similarity/log.txt ----- -----

12191  20230805   155000    155959  1691222399  29049.5  29037.9
2023-08-05 16:00:02,016:INFO:testStrategy:main.py:103:handleKline:2217133: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': True, 'isOpenSell': False, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True, 'isCorr': False}
127.0.0.1 - - [05/Aug/2023 16:10:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=11987 

self.closeSec=1691222999, self.tradeDate='20230805', self.openTime='160000', self.closeTime='160959', self.symbol='BTCUSDT', self.open='29037.9', self.close='29033.8'
2023-08-05 16:10:01,130:INFO:testStrategy:main.py:101:handleKline:2217133: self.closeSec=1691222999, self.tradeDate='20230805', self.openTime='160000', self.closeTime='160959',self.symbol='BTCUSDT',self.open='29037.9', self.close='29033.8'
2023-08-05 16:10:01,140:INFO:testStrategy:main.py:102:handleKline:2217133: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
12188  20230805   152000    152959  1691220599  29049.4  29035.4
12189  20230805   153000    153959  1691221199  29035.4  29047.3
12190  20230805   154000    154959  1691221799  29047.3  29049.5
12191  20230805   155000    155959  1691222399  29049.5  29037.9
12192  20230805   160000    160959  1691222999  29037.9  29033.8
2023-08-05 16:10:01,140:INFO:testStrategy:main.py:103:handleKline:2217133: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': True, 'isOpenSell': False, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True, 'isCorr': False}

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=11988 

self.closeSec=1691223599, self.tradeDate='20230805', self.openTime='161000', self.closeTime='161959', self.symbol='BTCUSDT', self.open='29033.8', self.close='29037.3'
127.0.0.1 - - [05/Aug/2023 16:20:04] "POST / HTTP/1.1" 200 -
2023-08-05 16:20:08,095:INFO:testStrategy:main.py:101:handleKline:2217133: self.closeSec=1691223599, self.tradeDate='20230805', self.openTime='161000', self.closeTime='161959',self.symbol='BTCUSDT',self.open='29033.8', self.close='29037.3'
2023-08-05 16:20:08,304:INFO:testStrategy:main.py:102:handleKline:2217133: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
12189  20230805   153000    153959  1691221199  29035.4  29047.3
12190  20230805   154000    154959  1691221799  29047.3  29049.5
12191  20230805   155000    155959  1691222399  29049.5  29037.9
12192  20230805   160000    160959  1691222999  29037.9  29033.8
12193  20230805   161000    161959  1691223599  29033.8  29037.3
2023-08-05 16:20:08,305:INFO:testStrategy:main.py:103:handleKline:2217133: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': True, 'isOpenSell': False, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True, 'isCorr': False}


## /root/FIL/strategy/sr_min/log.txt ----- -----

--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=1, self.total=996015.990996, self.flagDict['side']='buy', self.tradeCount=1, self.count=23968
self.closeSec=1691223599, self.tradeDate='20230805', self.openTime='161500', self.closeTime='161959', self.symbol='BTCUSDT', self.open=29037.3, self.close=29037.3, self.high=29045.3, self.low=29037.3, self.vol=218.032, self.amt=6331655.484 
127.0.0.1 - - [05/Aug/2023 16:20:01] "POST / HTTP/1.1" 200 -
2023-08-05 16:20:06,253:INFO:sr_min:main.py:172:handleKline:2219263: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5951  20230805   155500    155959  ...         0.0        0.0       0
5952  20230805   160000    160459  ...         0.0        0.0       0
5953  20230805   160500    160959  ...         0.0        0.0       0
5954  20230805   161000    161459  ...         0.0        0.0       0
5955  20230805   161500    161959  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-08-05 16:20:06,272:INFO:sr_min:main.py:175:handleKline:2219263: self.closeSec=1691223599, self.tradeDate='20230805', self.openTime='161500', self.closeTime='161959',self.symbol='BTCUSDT',self.open=29037.3, self.close=29037.3, self.high=29045.3, self.low=29037.3, self.vol=218.032, self.amt=6331655.484, ukdf['pct'].iloc[-1]=0.0 , ukdf['amount'].iloc[-1]=6331655.484, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5955, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '37.141', 'enterprice': '26844', 'countrevence': '0', 'unrealprofit': '81529.36237559048', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '29039.13105128', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=1
127.0.0.1 - - [05/Aug/2023 16:25:00] "POST / HTTP/1.1" 200 -
--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=1, self.total=996015.990996, self.flagDict['side']='buy', self.tradeCount=1, self.count=23969
self.closeSec=1691223899, self.tradeDate='20230805', self.openTime='162000', self.closeTime='162459', self.symbol='BTCUSDT', self.open=29037.3, self.close=29037.9, self.high=29045.3, self.low=29037.3, self.vol=224.912, self.amt=6531815.3423 
2023-08-05 16:25:00,790:INFO:sr_min:main.py:172:handleKline:2219263: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5952  20230805   160000    160459  ...         0.0        0.0       0
5953  20230805   160500    160959  ...         0.0        0.0       0
5954  20230805   161000    161459  ...         0.0        0.0       0
5955  20230805   161500    161959  ...         0.0        0.0       0
5956  20230805   162000    162459  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-08-05 16:25:00,791:INFO:sr_min:main.py:175:handleKline:2219263: self.closeSec=1691223899, self.tradeDate='20230805', self.openTime='162000', self.closeTime='162459',self.symbol='BTCUSDT',self.open=29037.3, self.close=29037.9, self.high=29045.3, self.low=29037.3, self.vol=224.912, self.amt=6531815.3423, ukdf['pct'].iloc[-1]=2.1e-05 , ukdf['amount'].iloc[-1]=6531815.3423, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5956, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '37.141', 'enterprice': '26844', 'countrevence': '0', 'unrealprofit': '81546.81225139592', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '29039.60087912', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=1


## /root/FIL/strategy/s_rsrs/log.txt ----- -----

721  20230805   040000    075959  1691193599  ...    721  0.470379  0.946624     1.0
722  20230805   080000    115959  1691207999  ...    722  0.466129  0.905948     1.0

[5 rows x 15 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '54.775', 'enterprice': '29034.8', 'countrevence': '0', 'unrealprofit': '2618.245', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '29082.6', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'numpy.int64'>, curSign=1, self.sign=1
127.0.0.1 - - [05/Aug/2023 16:00:01] "POST / HTTP/1.1" 200 -
--handleKline--:  version='2.0.0', self.name='s_rsrs', self.symbol='BTCUSDT', interval='4h', intervalSec=14400, wid=25, thd=0.6, self.sign=1, self.total=1588790.78883, self.flagDict['side']='buy', self.tradeCount=17, self.count=499
self.closeSec=1691222399, self.tradeDate='20230805', self.openTime='120000', self.closeTime='155959', self.symbol='BTCUSDT', self.open=29082.6, self.close=29037.9, self.high=29089.2, self.low=29020.5, self.vol=11796.275, self.amt=342746659.6781 
2023-08-05 16:00:01,607:INFO:s_rsrs:main.py:141:handleKline:2218689: self.closeSec=1691222399, self.tradeDate='20230805', self.openTime='120000', self.closeTime='155959',self.symbol='BTCUSDT',self.open=29082.6, self.close=29037.9, self.high=29089.2, self.low=29020.5, self.vol=11796.275, self.amt=342746659.6781 
2023-08-05 16:00:01,619:INFO:s_rsrs:main.py:142:handleKline:2218689: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime  ...        vol           amt       pct
719  20230804   200000    235959  ...  53716.396  1.569762e+09  0.003485
720  20230805   000000    035959  ...  61493.335  1.788545e+09 -0.008127
721  20230805   040000    075959  ...  48349.502  1.401817e+09  0.002760
722  20230805   080000    115959  ...  15877.382  4.618873e+08 -0.000636
723  20230805   120000    155959  ...  11796.275  3.427467e+08 -0.001537

[5 rows x 11 columns]
2023-08-05 16:00:02,297:INFO:s_rsrs:main.py:151:handleKline:2218689: df_s.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec  ...  index      beta    zscore  signal
719  20230804   200000    235959  1691164799  ...    719  0.461738  0.942720     1.0
720  20230805   000000    035959  1691179199  ...    720  0.453520  0.882942     1.0
721  20230805   040000    075959  1691193599  ...    721  0.470379  0.946624     1.0
722  20230805   080000    115959  1691207999  ...    722  0.466129  0.905948     1.0
723  20230805   120000    155959  1691222399  ...    723  0.636616  1.699703     1.0

[5 rows x 15 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '54.775', 'enterprice': '29034.8', 'countrevence': '0', 'unrealprofit': '274.58679181325', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '29039.81299483', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'numpy.int64'>, curSign=1, self.sign=1


