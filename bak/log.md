# 20230808 16:26:01

## /root/FIL/strategy/amihud/log.txt ----- -----

--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=373746.4768026, self.flagDict['side']='sell', self.tradeCount=2, self.count=24832
self.closeSec=1691482799, self.tradeDate='20230808', self.openTime='161500', self.closeTime='161959', self.symbol='BTCUSDT', self.open=29177.6, self.close=29190.0, self.high=29194.0, self.low=29177.1, self.vol=351.596, self.amt=10262212.47 
127.0.0.1 - - [08/Aug/2023 16:20:01] "POST / HTTP/1.1" 200 -
2023-08-08 16:20:06,619:INFO:amihud:main.py:172:handleKline:2219019: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5951  20230808   155500    155959  ...         0.0        0.0       0
5952  20230808   160000    160459  ...         0.0        0.0       0
5953  20230808   160500    160959  ...         0.0        0.0       0
5954  20230808   161000    161459  ...         0.0        0.0       0
5955  20230808   161500    161959  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-08-08 16:20:06,650:INFO:amihud:main.py:175:handleKline:2219019: self.closeSec=1691482799, self.tradeDate='20230808', self.openTime='161500', self.closeTime='161959',self.symbol='BTCUSDT',self.open=29177.6, self.close=29190.0, self.high=29194.0, self.low=29177.1, self.vol=351.596, self.amt=10262212.47, ukdf['pct'].iloc[-1]=0.000411 , ukdf['amount'].iloc[-1]=10262212.47, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5955, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '13.926', 'enterprice': '26864.9', 'countrevence': '0', 'unrealprofit': '-32387.47875074976', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '29190.58424176', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1
--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=373746.4768026, self.flagDict['side']='sell', self.tradeCount=2, self.count=24833
self.closeSec=1691483099, self.tradeDate='20230808', self.openTime='162000', self.closeTime='162459', self.symbol='BTCUSDT', self.open=29190.1, self.close=29184.0, self.high=29191.7, self.low=29184.0, self.vol=255.115, self.amt=7446566.2838 
127.0.0.1 - - [08/Aug/2023 16:25:00] "POST / HTTP/1.1" 200 -
2023-08-08 16:25:00,807:INFO:amihud:main.py:172:handleKline:2219019: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5952  20230808   160000    160459  ...         0.0        0.0       0
5953  20230808   160500    160959  ...         0.0        0.0       0
5954  20230808   161000    161459  ...         0.0        0.0       0
5955  20230808   161500    161959  ...         0.0        0.0       0
5956  20230808   162000    162459  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-08-08 16:25:00,807:INFO:amihud:main.py:175:handleKline:2219019: self.closeSec=1691483099, self.tradeDate='20230808', self.openTime='162000', self.closeTime='162459',self.symbol='BTCUSDT',self.open=29190.1, self.close=29184.0, self.high=29191.7, self.low=29184.0, self.vol=255.115, self.amt=7446566.2838, ukdf['pct'].iloc[-1]=-0.000206 , ukdf['amount'].iloc[-1]=7446566.2838, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5956, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '13.926', 'enterprice': '26864.9', 'countrevence': '0', 'unrealprofit': '-32322.99025028172', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '29185.95344322', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1


## /root/FIL/strategy/factorcheck/log.txt ----- -----


self.closeSec=1691482799, self.tradeDate='20230808', self.openTime='161500', self.closeTime='161959', self.symbol='BTCUSDT', self.open=29177.6, self.close=29190.0, self.high=29194.0, self.low=29177.1 
127.0.0.1 - - [08/Aug/2023 16:20:01] "POST / HTTP/1.1" 200 -
2023-08-08 16:20:04,461:INFO:factorcheck2:main.py:126:handleKline:2218005: self.closeSec=1691482799, self.tradeDate='20230808', self.openTime='161500', self.closeTime='161959',self.symbol='BTCUSDT',self.open=29177.6, self.close=29190.0, self.high=29194.0, self.low=29177.1   
2023-08-08 16:20:05,780:INFO:factorcheck2:main.py:127:handleKline:2218005: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime    closeSec  ...      low       pct  index  idx
1631  20230808   155500    155959  1691481599  ...  29172.5 -0.000360   1631    5
1632  20230808   160000    160459  1691481899  ...  29173.6  0.000497   1632    0
1633  20230808   160500    160959  1691482199  ...  29175.7 -0.000497   1633    1
1634  20230808   161000    161459  1691482499  ...  29174.0  0.000079   1634    2
1635  20230808   161500    161959  1691482799  ...  29177.1  0.000411   1635    3

[5 rows x 11 columns]
2023-08-08 16:20:05,790:INFO:factorcheck2:main.py:128:handleKline:2218005: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}
127.0.0.1 - - [08/Aug/2023 16:25:00] "POST / HTTP/1.1" 200 -

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=187, self.factor=0.3535559070518388, self.count=24835 

self.closeSec=1691483099, self.tradeDate='20230808', self.openTime='162000', self.closeTime='162459', self.symbol='BTCUSDT', self.open=29190.1, self.close=29184.0, self.high=29191.7, self.low=29184.0 
2023-08-08 16:25:00,775:INFO:factorcheck2:main.py:126:handleKline:2218005: self.closeSec=1691483099, self.tradeDate='20230808', self.openTime='162000', self.closeTime='162459',self.symbol='BTCUSDT',self.open=29190.1, self.close=29184.0, self.high=29191.7, self.low=29184.0   
2023-08-08 16:25:00,803:INFO:factorcheck2:main.py:127:handleKline:2218005: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime    closeSec  ...      low       pct  index  idx
1632  20230808   160000    160459  1691481899  ...  29173.6  0.000497   1632    0
1633  20230808   160500    160959  1691482199  ...  29175.7 -0.000497   1633    1
1634  20230808   161000    161459  1691482499  ...  29174.0  0.000079   1634    2
1635  20230808   161500    161959  1691482799  ...  29177.1  0.000411   1635    3
1636  20230808   162000    162459  1691483099  ...  29184.0 -0.000206   1636    4

[5 rows x 11 columns]
2023-08-08 16:25:00,803:INFO:factorcheck2:main.py:128:handleKline:2218005: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}


## /root/FIL/strategy/logic/log.txt ----- -----

2023-08-08 16:00:19,205:DEBUG:logic:main.py:463:getModel:2218526: df_s.iloc[-5:,:] :
          date closeTime     open  ...    alpha58   alpha67   alpha72
5786  20230808    132959  29216.8  ...  48.750000  0.547999  0.237103
5787  20230808    135959  29261.7  ...  48.333333  0.538347  0.231311
5788  20230808    142959  29232.8  ...  48.750000  0.543924  0.223867
5789  20230808    145959  29252.5  ...  48.750000  0.530224  0.221191
5790  20230808    152959  29211.0  ...  48.750000  0.524925  0.220371

[5 rows x 33 columns]
0.5498154981549815
acc is : 0.5498154981549815
2023-08-08 16:00:19,283:INFO:logic:main.py:468:getModel:2218526: df_pred.iloc[-5:,:] :
     pred    prob_0    prob_1  actual  ...       nav  sign  cost_        bm
537     0  0.520378  0.479622       0  ...  0.954062   1.0    0.0  0.999207
538     1  0.498536  0.501464       1  ...  0.954708   1.0    0.0  0.999884
539     0  0.510869  0.489131       0  ...  0.953354   1.0    0.0  0.998465
540     1  0.489323  0.510677       0  ...  0.952822   1.0    0.0  0.997908
541     1  0.490189  0.509811       0  ...  0.952244   1.0    0.0  0.997303

[5 rows x 10 columns]
2023-08-08 16:00:19,298:INFO:logic:main.py:478:getModel:2218526: df_panel.iloc[-5:,:] :
    pred    prob_0    prob_1  actual  ...       nav  sign  cost_        bm
45     0  0.520616  0.479384       0  ...  0.954062   1.0    0.0  1.001579
46     1  0.498854  0.501146       1  ...  0.954708   1.0    0.0  1.002306
47     0  0.510763  0.489237       0  ...  0.953354   1.0    0.0  1.000045
48     1  0.489398  0.510602       0  ...  0.952822   1.0    0.0  0.998912
49     1  0.490189  0.509811       0  ...  0.952244   1.0    0.0  0.997303

[5 rows x 10 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '24.06', 'enterprice': '29131.5', 'countrevence': '0', 'unrealprofit': '1112.5719441864', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '29177.74156044', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}


## /root/FIL/strategy/modifiedmom/log.txt ----- -----

527  20230808   155000    155959  1691481599    29190    29177 -0.000445
2023-08-08 16:00:02,056:INFO:modifiedmom:main.py:146:handleKline:2218259: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': True, 'isOpenSell': False, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True}

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=12416 

self.closeSec=1691482199, self.tradeDate='20230808', self.openTime='160000', self.closeTime='160959', self.symbol='BTCUSDT', self.open='29177', self.close='29175.7'
127.0.0.1 - - [08/Aug/2023 16:10:01] "POST / HTTP/1.1" 200 -
2023-08-08 16:10:01,138:INFO:modifiedmom:main.py:144:handleKline:2218259: self.closeSec=1691482199, self.tradeDate='20230808', self.openTime='160000', self.closeTime='160959',self.symbol='BTCUSDT',self.open='29177', self.close='29175.7'
2023-08-08 16:10:01,152:INFO:modifiedmom:main.py:145:handleKline:2218259: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec     open    close       pct
524  20230808   152000    152959  1691479799    29211  29194.7 -0.000558
525  20230808   153000    153959  1691480399  29194.8  29180.1 -0.000500
526  20230808   154000    154959  1691480999  29180.1    29190  0.000339
527  20230808   155000    155959  1691481599    29190    29177 -0.000445
528  20230808   160000    160959  1691482199    29177  29175.7 -0.000045
2023-08-08 16:10:01,152:INFO:modifiedmom:main.py:146:handleKline:2218259: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': True, 'isOpenSell': False, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True}

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=12417 

self.closeSec=1691482799, self.tradeDate='20230808', self.openTime='161000', self.closeTime='161959', self.symbol='BTCUSDT', self.open='29175.8', self.close='29190'
127.0.0.1 - - [08/Aug/2023 16:20:04] "POST / HTTP/1.1" 200 -
2023-08-08 16:20:07,070:INFO:modifiedmom:main.py:144:handleKline:2218259: self.closeSec=1691482799, self.tradeDate='20230808', self.openTime='161000', self.closeTime='161959',self.symbol='BTCUSDT',self.open='29175.8', self.close='29190'
2023-08-08 16:20:07,760:INFO:modifiedmom:main.py:145:handleKline:2218259: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec     open    close       pct
525  20230808   153000    153959  1691480399  29194.8  29180.1 -0.000500
526  20230808   154000    154959  1691480999  29180.1    29190  0.000339
527  20230808   155000    155959  1691481599    29190    29177 -0.000445
528  20230808   160000    160959  1691482199    29177  29175.7 -0.000045
529  20230808   161000    161959  1691482799  29175.8    29190  0.000490
2023-08-08 16:20:07,760:INFO:modifiedmom:main.py:146:handleKline:2218259: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': True, 'isOpenSell': False, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True}


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

17519  20230808   155000    155959  1691481599    29190    29177
2023-08-08 16:00:02,094:INFO:pyemd2:main.py:127:handleKline:2217508: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}
127.0.0.1 - - [08/Aug/2023 16:10:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=12419 

self.closeSec=1691482199, self.tradeDate='20230808', self.openTime='160000', self.closeTime='160959', self.symbol='BTCUSDT', self.open='29177', self.close='29175.7'
2023-08-08 16:10:01,135:INFO:pyemd2:main.py:125:handleKline:2217508: self.closeSec=1691482199, self.tradeDate='20230808', self.openTime='160000', self.closeTime='160959',self.symbol='BTCUSDT',self.open='29177', self.close='29175.7'
2023-08-08 16:10:01,143:INFO:pyemd2:main.py:126:handleKline:2217508: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
17516  20230808   152000    152959  1691479799    29211  29194.7
17517  20230808   153000    153959  1691480399  29194.8  29180.1
17518  20230808   154000    154959  1691480999  29180.1    29190
17519  20230808   155000    155959  1691481599    29190    29177
17520  20230808   160000    160959  1691482199    29177  29175.7
2023-08-08 16:10:01,143:INFO:pyemd2:main.py:127:handleKline:2217508: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=12420 

self.closeSec=1691482799, self.tradeDate='20230808', self.openTime='161000', self.closeTime='161959', self.symbol='BTCUSDT', self.open='29175.8', self.close='29190'
127.0.0.1 - - [08/Aug/2023 16:20:04] "POST / HTTP/1.1" 200 -
2023-08-08 16:20:08,922:INFO:pyemd2:main.py:125:handleKline:2217508: self.closeSec=1691482799, self.tradeDate='20230808', self.openTime='161000', self.closeTime='161959',self.symbol='BTCUSDT',self.open='29175.8', self.close='29190'
2023-08-08 16:20:09,028:INFO:pyemd2:main.py:126:handleKline:2217508: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
17517  20230808   153000    153959  1691480399  29194.8  29180.1
17518  20230808   154000    154959  1691480999  29180.1    29190
17519  20230808   155000    155959  1691481599    29190    29177
17520  20230808   160000    160959  1691482199    29177  29175.7
17521  20230808   161000    161959  1691482799  29175.8    29190
2023-08-08 16:20:09,029:INFO:pyemd2:main.py:127:handleKline:2217508: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}


## /root/FIL/strategy/similarity/log.txt ----- -----

12191  20230808   155000    155959  1691481599    29190    29177
2023-08-08 16:00:02,081:INFO:testStrategy:main.py:103:handleKline:2217133: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': True, 'isOpenSell': False, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True, 'isCorr': False}

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=12419 

self.closeSec=1691482199, self.tradeDate='20230808', self.openTime='160000', self.closeTime='160959', self.symbol='BTCUSDT', self.open='29177', self.close='29175.7'
2023-08-08 16:10:01,135:INFO:testStrategy:main.py:101:handleKline:2217133: self.closeSec=1691482199, self.tradeDate='20230808', self.openTime='160000', self.closeTime='160959',self.symbol='BTCUSDT',self.open='29177', self.close='29175.7'
127.0.0.1 - - [08/Aug/2023 16:10:01] "POST / HTTP/1.1" 200 -
2023-08-08 16:10:01,155:INFO:testStrategy:main.py:102:handleKline:2217133: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
12188  20230808   152000    152959  1691479799    29211  29194.7
12189  20230808   153000    153959  1691480399  29194.8  29180.1
12190  20230808   154000    154959  1691480999  29180.1    29190
12191  20230808   155000    155959  1691481599    29190    29177
12192  20230808   160000    160959  1691482199    29177  29175.7
2023-08-08 16:10:01,155:INFO:testStrategy:main.py:103:handleKline:2217133: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': True, 'isOpenSell': False, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True, 'isCorr': False}

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=12420 

self.closeSec=1691482799, self.tradeDate='20230808', self.openTime='161000', self.closeTime='161959', self.symbol='BTCUSDT', self.open='29175.8', self.close='29190'
127.0.0.1 - - [08/Aug/2023 16:20:04] "POST / HTTP/1.1" 200 -
2023-08-08 16:20:08,684:INFO:testStrategy:main.py:101:handleKline:2217133: self.closeSec=1691482799, self.tradeDate='20230808', self.openTime='161000', self.closeTime='161959',self.symbol='BTCUSDT',self.open='29175.8', self.close='29190'
2023-08-08 16:20:08,881:INFO:testStrategy:main.py:102:handleKline:2217133: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
12189  20230808   153000    153959  1691480399  29194.8  29180.1
12190  20230808   154000    154959  1691480999  29180.1    29190
12191  20230808   155000    155959  1691481599    29190    29177
12192  20230808   160000    160959  1691482199    29177  29175.7
12193  20230808   161000    161959  1691482799  29175.8    29190
2023-08-08 16:20:08,881:INFO:testStrategy:main.py:103:handleKline:2217133: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': True, 'isOpenSell': False, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True, 'isCorr': False}


## /root/FIL/strategy/sr_min/log.txt ----- -----

--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=1, self.total=996015.990996, self.flagDict['side']='buy', self.tradeCount=1, self.count=24832
self.closeSec=1691482799, self.tradeDate='20230808', self.openTime='161500', self.closeTime='161959', self.symbol='BTCUSDT', self.open=29177.6, self.close=29190.0, self.high=29194.0, self.low=29177.1, self.vol=351.596, self.amt=10262212.47 
127.0.0.1 - - [08/Aug/2023 16:20:01] "POST / HTTP/1.1" 200 -
2023-08-08 16:20:06,611:INFO:sr_min:main.py:172:handleKline:2219263: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5951  20230808   155500    155959  ...         0.0        0.0       0
5952  20230808   160000    160459  ...         0.0        0.0       0
5953  20230808   160500    160959  ...         0.0        0.0       0
5954  20230808   161000    161459  ...         0.0        0.0       0
5955  20230808   161500    161959  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-08-08 16:20:06,631:INFO:sr_min:main.py:175:handleKline:2219263: self.closeSec=1691482799, self.tradeDate='20230808', self.openTime='161500', self.closeTime='161959',self.symbol='BTCUSDT',self.open=29177.6, self.close=29190.0, self.high=29194.0, self.low=29177.1, self.vol=351.596, self.amt=10262212.47, ukdf['pct'].iloc[-1]=0.000411 , ukdf['amount'].iloc[-1]=10262212.47, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5955, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '37.141', 'enterprice': '26844', 'countrevence': '0', 'unrealprofit': '87154.48532320816', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '29190.58424176', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=1
127.0.0.1 - - [08/Aug/2023 16:25:00] "POST / HTTP/1.1" 200 -
--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=1, self.total=996015.990996, self.flagDict['side']='buy', self.tradeCount=1, self.count=24833
self.closeSec=1691483099, self.tradeDate='20230808', self.openTime='162000', self.closeTime='162459', self.symbol='BTCUSDT', self.open=29190.1, self.close=29184.0, self.high=29191.7, self.low=29184.0, self.vol=255.115, self.amt=7446566.2838 
2023-08-08 16:25:00,812:INFO:sr_min:main.py:172:handleKline:2219263: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5952  20230808   160000    160459  ...         0.0        0.0       0
5953  20230808   160500    160959  ...         0.0        0.0       0
5954  20230808   161000    161459  ...         0.0        0.0       0
5955  20230808   161500    161959  ...         0.0        0.0       0
5956  20230808   162000    162459  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-08-08 16:25:00,813:INFO:sr_min:main.py:175:handleKline:2219263: self.closeSec=1691483099, self.tradeDate='20230808', self.openTime='162000', self.closeTime='162459',self.symbol='BTCUSDT',self.open=29190.1, self.close=29184.0, self.high=29191.7, self.low=29184.0, self.vol=255.115, self.amt=7446566.2838, ukdf['pct'].iloc[-1]=-0.000206 , ukdf['amount'].iloc[-1]=7446566.2838, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5956, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '37.141', 'enterprice': '26844', 'countrevence': '0', 'unrealprofit': '86982.49283463402', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '29185.95344322', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=1


## /root/FIL/strategy/s_rsrs/log.txt ----- -----

721  20230808   040000    075959  1691452799  ...    721  0.008901 -1.397944    -1.0
722  20230808   080000    115959  1691467199  ...    722  0.004642 -1.402976    -1.0

[5 rows x 15 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '54.719', 'enterprice': '28996.8', 'countrevence': '0', 'unrealprofit': '-10254.3406', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '29184.2', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'numpy.int64'>, curSign=-1, self.sign=-1
127.0.0.1 - - [08/Aug/2023 16:00:01] "POST / HTTP/1.1" 200 -
--handleKline--:  version='2.0.0', self.name='s_rsrs', self.symbol='BTCUSDT', interval='4h', intervalSec=14400, wid=25, thd=0.6, self.sign=-1, self.total=1585089.2233008002, self.flagDict['side']='sell', self.tradeCount=18, self.count=517
self.closeSec=1691481599, self.tradeDate='20230808', self.openTime='120000', self.closeTime='155959', self.symbol='BTCUSDT', self.open=29182.8, self.close=29177.0, self.high=29330.0, self.low=29170.2, self.vol=30110.449, self.amt=880304508.15173 
2023-08-08 16:00:01,581:INFO:s_rsrs:main.py:141:handleKline:2218689: self.closeSec=1691481599, self.tradeDate='20230808', self.openTime='120000', self.closeTime='155959',self.symbol='BTCUSDT',self.open=29182.8, self.close=29177.0, self.high=29330.0, self.low=29170.2, self.vol=30110.449, self.amt=880304508.15173 
2023-08-08 16:00:01,594:INFO:s_rsrs:main.py:142:handleKline:2218689: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime  ...         vol           amt       pct
719  20230807   200000    235959  ...   85465.104  2.475642e+09 -0.007997
720  20230808   000000    035959  ...  101877.164  2.950085e+09  0.010110
721  20230808   040000    075959  ...   34487.020  1.006610e+09  0.001980
722  20230808   080000    115959  ...   21205.290  6.188332e+08 -0.000678
723  20230808   120000    155959  ...   30110.449  8.803045e+08 -0.000199

[5 rows x 11 columns]
2023-08-08 16:00:02,323:INFO:s_rsrs:main.py:151:handleKline:2218689: df_s.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec  ...  index      beta    zscore  signal
719  20230807   200000    235959  1691423999  ...    719  0.060565 -1.198875    -1.0
720  20230808   000000    035959  1691438399  ...    720  0.012625 -1.399162    -1.0
721  20230808   040000    075959  1691452799  ...    721  0.008901 -1.397944    -1.0
722  20230808   080000    115959  1691467199  ...    722  0.004642 -1.402976    -1.0
723  20230808   120000    155959  1691481599  ...    723  0.010176 -1.364017    -1.0

[5 rows x 15 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '54.719', 'enterprice': '28996.8', 'countrevence': '0', 'unrealprofit': '-9919.10218523938', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '29178.07345502', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'numpy.int64'>, curSign=-1, self.sign=-1


