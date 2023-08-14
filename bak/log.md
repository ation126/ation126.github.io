# 20230814 16:26:01

## /root/FIL/strategy/amihud/log.txt ----- -----

--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=373746.4768026, self.flagDict['side']='sell', self.tradeCount=2, self.count=26560
self.closeSec=1692001199, self.tradeDate='20230814', self.openTime='161500', self.closeTime='161959', self.symbol='BTCUSDT', self.open=29445.0, self.close=29436.4, self.high=29459.8, self.low=29436.4, self.vol=774.089, self.amt=22797443.8532 
127.0.0.1 - - [14/Aug/2023 16:20:02] "POST / HTTP/1.1" 200 -
2023-08-14 16:20:06,689:INFO:amihud:main.py:172:handleKline:2219019: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5951  20230814   155500    155959  ...         0.0        0.0       0
5952  20230814   160000    160459  ...         0.0        0.0       0
5953  20230814   160500    160959  ...         0.0        0.0       0
5954  20230814   161000    161459  ...         0.0        0.0       0
5955  20230814   161500    161959  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-08-14 16:20:06,708:INFO:amihud:main.py:175:handleKline:2219019: self.closeSec=1692001199, self.tradeDate='20230814', self.openTime='161500', self.closeTime='161959',self.symbol='BTCUSDT',self.open=29445.0, self.close=29436.4, self.high=29459.8, self.low=29436.4, self.vol=774.089, self.amt=22797443.8532, ukdf['pct'].iloc[-1]=-0.000295 , ukdf['amount'].iloc[-1]=22797443.8532, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5955, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '13.926', 'enterprice': '26864.9', 'countrevence': '0', 'unrealprofit': '-35863.75148878236', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '29440.20888186', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1
127.0.0.1 - - [14/Aug/2023 16:25:00] "POST / HTTP/1.1" 200 -
--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=373746.4768026, self.flagDict['side']='sell', self.tradeCount=2, self.count=26561
self.closeSec=1692001499, self.tradeDate='20230814', self.openTime='162000', self.closeTime='162459', self.symbol='BTCUSDT', self.open=29436.5, self.close=29434.1, self.high=29450.0, self.low=29429.9, self.vol=435.195, self.amt=12811703.4578 
2023-08-14 16:25:00,760:INFO:amihud:main.py:172:handleKline:2219019: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5952  20230814   160000    160459  ...         0.0        0.0       0
5953  20230814   160500    160959  ...         0.0        0.0       0
5954  20230814   161000    161459  ...         0.0        0.0       0
5955  20230814   161500    161959  ...         0.0        0.0       0
5956  20230814   162000    162459  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-08-14 16:25:00,760:INFO:amihud:main.py:175:handleKline:2219019: self.closeSec=1692001499, self.tradeDate='20230814', self.openTime='162000', self.closeTime='162459',self.symbol='BTCUSDT',self.open=29436.5, self.close=29434.1, self.high=29450.0, self.low=29429.9, self.vol=435.195, self.amt=12811703.4578, ukdf['pct'].iloc[-1]=-7.8e-05 , ukdf['amount'].iloc[-1]=12811703.4578, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5956, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '13.926', 'enterprice': '26864.9', 'countrevence': '0', 'unrealprofit': '-35826.0276', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '29437.5', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1


## /root/FIL/strategy/factorcheck/log.txt ----- -----


self.closeSec=1692001199, self.tradeDate='20230814', self.openTime='161500', self.closeTime='161959', self.symbol='BTCUSDT', self.open=29445.0, self.close=29436.4, self.high=29459.8, self.low=29436.4 
127.0.0.1 - - [14/Aug/2023 16:20:01] "POST / HTTP/1.1" 200 -
2023-08-14 16:20:04,660:INFO:factorcheck2:main.py:126:handleKline:2218005: self.closeSec=1692001199, self.tradeDate='20230814', self.openTime='161500', self.closeTime='161959',self.symbol='BTCUSDT',self.open=29445.0, self.close=29436.4, self.high=29459.8, self.low=29436.4   
2023-08-14 16:20:05,769:INFO:factorcheck2:main.py:127:handleKline:2218005: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime    closeSec  ...      low       pct  index  idx
1631  20230814   155500    155959  1691999999  ...  29396.0  0.000493   1631    5
1632  20230814   160000    160459  1692000299  ...  29410.4  0.000901   1632    0
1633  20230814   160500    160959  1692000599  ...  29435.0  0.000649   1633    1
1634  20230814   161000    161459  1692000899  ...  29436.0 -0.000373   1634    2
1635  20230814   161500    161959  1692001199  ...  29436.4 -0.000295   1635    3

[5 rows x 11 columns]
2023-08-14 16:20:05,779:INFO:factorcheck2:main.py:128:handleKline:2218005: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': True, 'isOpenSell': False, 'isCloseBuy': False, 'isCloseSell': False, 'isOpen': True, 'isClose': False, 'isTrig': True}
127.0.0.1 - - [14/Aug/2023 16:25:00] "POST / HTTP/1.1" 200 -

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=5, self.factor=0.5508212306654366, self.count=26563 

self.closeSec=1692001499, self.tradeDate='20230814', self.openTime='162000', self.closeTime='162459', self.symbol='BTCUSDT', self.open=29436.5, self.close=29434.1, self.high=29450.0, self.low=29429.9 
2023-08-14 16:25:00,739:INFO:factorcheck2:main.py:126:handleKline:2218005: self.closeSec=1692001499, self.tradeDate='20230814', self.openTime='162000', self.closeTime='162459',self.symbol='BTCUSDT',self.open=29436.5, self.close=29434.1, self.high=29450.0, self.low=29429.9   
2023-08-14 16:25:00,766:INFO:factorcheck2:main.py:127:handleKline:2218005: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime    closeSec  ...      low       pct  index  idx
1632  20230814   160000    160459  1692000299  ...  29410.4  0.000901   1632    0
1633  20230814   160500    160959  1692000599  ...  29435.0  0.000649   1633    1
1634  20230814   161000    161459  1692000899  ...  29436.0 -0.000373   1634    2
1635  20230814   161500    161959  1692001199  ...  29436.4 -0.000295   1635    3
1636  20230814   162000    162459  1692001499  ...  29429.9 -0.000078   1636    4

[5 rows x 11 columns]
2023-08-14 16:25:00,766:INFO:factorcheck2:main.py:128:handleKline:2218005: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': True, 'isOpenSell': False, 'isCloseBuy': False, 'isCloseSell': False, 'isOpen': True, 'isClose': False, 'isTrig': True}


## /root/FIL/strategy/logic/log.txt ----- -----

2023-08-14 16:00:18,431:DEBUG:logic:main.py:463:getModel:2218526: df_s.iloc[-5:,:] :
          date closeTime     open  ...    alpha58   alpha67   alpha72
5786  20230814    132959  29404.0  ...  46.250000  0.524770  0.485849
5787  20230814    135959  29429.2  ...  46.666667  0.528333  0.458039
5788  20230814    142959  29435.9  ...  46.666667  0.509596  0.438017
5789  20230814    145959  29403.7  ...  46.666667  0.512010  0.418590
5790  20230814    152959  29408.2  ...  46.250000  0.503280  0.403015

[5 rows x 33 columns]
0.5295202952029521
acc is : 0.5295202952029521
2023-08-14 16:00:18,547:INFO:logic:main.py:468:getModel:2218526: df_pred.iloc[-5:,:] :
     pred    prob_0    prob_1  actual  ...       nav  sign  cost_        bm
537     0  0.517065  0.482935       1  ...  1.003009  -1.0    0.0  1.009531
538     0  0.508473  0.491527       0  ...  1.004106  -1.0    0.0  1.008426
539     1  0.496094  0.503906       1  ...  1.003956  -1.0    0.0  1.008577
540     0  0.503320  0.496680       0  ...  1.004475  -1.0    0.0  1.008056
541     1  0.497869  0.502131       1  ...  1.003877  -1.0    0.0  1.008656

[5 rows x 10 columns]
2023-08-14 16:00:18,559:INFO:logic:main.py:478:getModel:2218526: df_panel.iloc[-5:,:] :
    pred    prob_0    prob_1  actual  ...       nav  sign  cost_        bm
45     0  0.517078  0.482922       1  ...  1.003009  -1.0    0.0  1.008981
46     0  0.508570  0.491430       0  ...  1.004106  -1.0    0.0  1.008866
47     1  0.496092  0.503908       1  ...  1.003956  -1.0    0.0  1.008162
48     0  0.503215  0.496785       0  ...  1.004475  -1.0    0.0  1.007300
49     1  0.497869  0.502131       1  ...  1.003877  -1.0    0.0  1.008656

[5 rows x 10 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '24.049', 'enterprice': '29479.7', 'countrevence': '0', 'unrealprofit': '1661.7859', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '29410.6', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}


## /root/FIL/strategy/modifiedmom/log.txt ----- -----

527  20230814   155000    155959  1691999999  29393.5  29410.5  0.000578
2023-08-14 16:00:02,105:INFO:modifiedmom:main.py:146:handleKline:2218259: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': True, 'isOpenSell': False, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True}
127.0.0.1 - - [14/Aug/2023 16:10:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=13280 

self.closeSec=1692000599, self.tradeDate='20230814', self.openTime='160000', self.closeTime='160959', self.symbol='BTCUSDT', self.open='29410.4', self.close='29456.1'
2023-08-14 16:10:01,123:INFO:modifiedmom:main.py:144:handleKline:2218259: self.closeSec=1692000599, self.tradeDate='20230814', self.openTime='160000', self.closeTime='160959',self.symbol='BTCUSDT',self.open='29410.4', self.close='29456.1'
2023-08-14 16:10:01,132:INFO:modifiedmom:main.py:145:handleKline:2218259: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec     open    close       pct
524  20230814   152000    152959  1691998199  29386.5  29393.1  0.000228
525  20230814   153000    153959  1691998799  29393.1  29426.4  0.001133
526  20230814   154000    154959  1691999399  29425.6  29393.5 -0.001118
527  20230814   155000    155959  1691999999  29393.5  29410.5  0.000578
528  20230814   160000    160959  1692000599  29410.4  29456.1  0.001550
2023-08-14 16:10:01,132:INFO:modifiedmom:main.py:146:handleKline:2218259: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': True, 'isOpenSell': False, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True}

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=13281 

self.closeSec=1692001199, self.tradeDate='20230814', self.openTime='161000', self.closeTime='161959', self.symbol='BTCUSDT', self.open='29456', self.close='29436.4'
127.0.0.1 - - [14/Aug/2023 16:20:04] "POST / HTTP/1.1" 200 -
2023-08-14 16:20:06,729:INFO:modifiedmom:main.py:144:handleKline:2218259: self.closeSec=1692001199, self.tradeDate='20230814', self.openTime='161000', self.closeTime='161959',self.symbol='BTCUSDT',self.open='29456', self.close='29436.4'
2023-08-14 16:20:07,319:INFO:modifiedmom:main.py:145:handleKline:2218259: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec     open    close       pct
525  20230814   153000    153959  1691998799  29393.1  29426.4  0.001133
526  20230814   154000    154959  1691999399  29425.6  29393.5 -0.001118
527  20230814   155000    155959  1691999999  29393.5  29410.5  0.000578
528  20230814   160000    160959  1692000599  29410.4  29456.1  0.001550
529  20230814   161000    161959  1692001199    29456  29436.4 -0.000669
2023-08-14 16:20:07,319:INFO:modifiedmom:main.py:146:handleKline:2218259: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': True, 'isOpenSell': False, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True}


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

17519  20230814   155000    155959  1691999999  29393.5  29410.5
2023-08-14 16:00:02,132:INFO:pyemd2:main.py:127:handleKline:2217508: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}
127.0.0.1 - - [14/Aug/2023 16:10:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=13283 

self.closeSec=1692000599, self.tradeDate='20230814', self.openTime='160000', self.closeTime='160959', self.symbol='BTCUSDT', self.open='29410.4', self.close='29456.1'
2023-08-14 16:10:01,138:INFO:pyemd2:main.py:125:handleKline:2217508: self.closeSec=1692000599, self.tradeDate='20230814', self.openTime='160000', self.closeTime='160959',self.symbol='BTCUSDT',self.open='29410.4', self.close='29456.1'
2023-08-14 16:10:01,145:INFO:pyemd2:main.py:126:handleKline:2217508: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
17516  20230814   152000    152959  1691998199  29386.5  29393.1
17517  20230814   153000    153959  1691998799  29393.1  29426.4
17518  20230814   154000    154959  1691999399  29425.6  29393.5
17519  20230814   155000    155959  1691999999  29393.5  29410.5
17520  20230814   160000    160959  1692000599  29410.4  29456.1
2023-08-14 16:10:01,145:INFO:pyemd2:main.py:127:handleKline:2217508: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=13284 

self.closeSec=1692001199, self.tradeDate='20230814', self.openTime='161000', self.closeTime='161959', self.symbol='BTCUSDT', self.open='29456', self.close='29436.4'
127.0.0.1 - - [14/Aug/2023 16:20:04] "POST / HTTP/1.1" 200 -
2023-08-14 16:20:08,463:INFO:pyemd2:main.py:125:handleKline:2217508: self.closeSec=1692001199, self.tradeDate='20230814', self.openTime='161000', self.closeTime='161959',self.symbol='BTCUSDT',self.open='29456', self.close='29436.4'
2023-08-14 16:20:08,554:INFO:pyemd2:main.py:126:handleKline:2217508: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
17517  20230814   153000    153959  1691998799  29393.1  29426.4
17518  20230814   154000    154959  1691999399  29425.6  29393.5
17519  20230814   155000    155959  1691999999  29393.5  29410.5
17520  20230814   160000    160959  1692000599  29410.4  29456.1
17521  20230814   161000    161959  1692001199    29456  29436.4
2023-08-14 16:20:08,555:INFO:pyemd2:main.py:127:handleKline:2217508: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}


## /root/FIL/strategy/similarity/log.txt ----- -----

12191  20230814   155000    155959  1691999999  29393.5  29410.5
2023-08-14 16:00:02,124:INFO:testStrategy:main.py:103:handleKline:2217133: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': True, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True, 'isCorr': False}
127.0.0.1 - - [14/Aug/2023 16:10:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=13283 

self.closeSec=1692000599, self.tradeDate='20230814', self.openTime='160000', self.closeTime='160959', self.symbol='BTCUSDT', self.open='29410.4', self.close='29456.1'
2023-08-14 16:10:01,137:INFO:testStrategy:main.py:101:handleKline:2217133: self.closeSec=1692000599, self.tradeDate='20230814', self.openTime='160000', self.closeTime='160959',self.symbol='BTCUSDT',self.open='29410.4', self.close='29456.1'
2023-08-14 16:10:01,143:INFO:testStrategy:main.py:102:handleKline:2217133: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
12188  20230814   152000    152959  1691998199  29386.5  29393.1
12189  20230814   153000    153959  1691998799  29393.1  29426.4
12190  20230814   154000    154959  1691999399  29425.6  29393.5
12191  20230814   155000    155959  1691999999  29393.5  29410.5
12192  20230814   160000    160959  1692000599  29410.4  29456.1
2023-08-14 16:10:01,144:INFO:testStrategy:main.py:103:handleKline:2217133: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': True, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True, 'isCorr': False}

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=13284 

self.closeSec=1692001199, self.tradeDate='20230814', self.openTime='161000', self.closeTime='161959', self.symbol='BTCUSDT', self.open='29456', self.close='29436.4'
127.0.0.1 - - [14/Aug/2023 16:20:04] "POST / HTTP/1.1" 200 -
2023-08-14 16:20:08,262:INFO:testStrategy:main.py:101:handleKline:2217133: self.closeSec=1692001199, self.tradeDate='20230814', self.openTime='161000', self.closeTime='161959',self.symbol='BTCUSDT',self.open='29456', self.close='29436.4'
2023-08-14 16:20:08,427:INFO:testStrategy:main.py:102:handleKline:2217133: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
12189  20230814   153000    153959  1691998799  29393.1  29426.4
12190  20230814   154000    154959  1691999399  29425.6  29393.5
12191  20230814   155000    155959  1691999999  29393.5  29410.5
12192  20230814   160000    160959  1692000599  29410.4  29456.1
12193  20230814   161000    161959  1692001199    29456  29436.4
2023-08-14 16:20:08,428:INFO:testStrategy:main.py:103:handleKline:2217133: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': True, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True, 'isCorr': False}


## /root/FIL/strategy/sr_min/log.txt ----- -----

--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=1, self.total=996015.990996, self.flagDict['side']='buy', self.tradeCount=1, self.count=26560
self.closeSec=1692001199, self.tradeDate='20230814', self.openTime='161500', self.closeTime='161959', self.symbol='BTCUSDT', self.open=29445.0, self.close=29436.4, self.high=29459.8, self.low=29436.4, self.vol=774.089, self.amt=22797443.8532 
127.0.0.1 - - [14/Aug/2023 16:20:01] "POST / HTTP/1.1" 200 -
2023-08-14 16:20:06,649:INFO:sr_min:main.py:172:handleKline:2219263: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5951  20230814   155500    155959  ...         0.0        0.0       0
5952  20230814   160000    160459  ...         0.0        0.0       0
5953  20230814   160500    160959  ...         0.0        0.0       0
5954  20230814   161000    161459  ...         0.0        0.0       0
5955  20230814   161500    161959  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-08-14 16:20:06,670:INFO:sr_min:main.py:175:handleKline:2219263: self.closeSec=1692001199, self.tradeDate='20230814', self.openTime='161500', self.closeTime='161959',self.symbol='BTCUSDT',self.open=29445.0, self.close=29436.4, self.high=29459.8, self.low=29436.4, self.vol=774.089, self.amt=22797443.8532, ukdf['pct'].iloc[-1]=-0.000295 , ukdf['amount'].iloc[-1]=22797443.8532, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5955, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '37.141', 'enterprice': '26844', 'countrevence': '0', 'unrealprofit': '96420.86404424786', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '29440.07614346', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=1
127.0.0.1 - - [14/Aug/2023 16:25:00] "POST / HTTP/1.1" 200 -
--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=1, self.total=996015.990996, self.flagDict['side']='buy', self.tradeCount=1, self.count=26561
self.closeSec=1692001499, self.tradeDate='20230814', self.openTime='162000', self.closeTime='162459', self.symbol='BTCUSDT', self.open=29436.5, self.close=29434.1, self.high=29450.0, self.low=29429.9, self.vol=435.195, self.amt=12811703.4578 
2023-08-14 16:25:00,775:INFO:sr_min:main.py:172:handleKline:2219263: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5952  20230814   160000    160459  ...         0.0        0.0       0
5953  20230814   160500    160959  ...         0.0        0.0       0
5954  20230814   161000    161459  ...         0.0        0.0       0
5955  20230814   161500    161959  ...         0.0        0.0       0
5956  20230814   162000    162459  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-08-14 16:25:00,775:INFO:sr_min:main.py:175:handleKline:2219263: self.closeSec=1692001499, self.tradeDate='20230814', self.openTime='162000', self.closeTime='162459',self.symbol='BTCUSDT',self.open=29436.5, self.close=29434.1, self.high=29450.0, self.low=29429.9, self.vol=435.195, self.amt=12811703.4578, ukdf['pct'].iloc[-1]=-7.8e-05 , ukdf['amount'].iloc[-1]=12811703.4578, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5956, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '37.141', 'enterprice': '26844', 'countrevence': '0', 'unrealprofit': '96325.1835', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '29437.5', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=1


## /root/FIL/strategy/s_rsrs/log.txt ----- -----

721  20230814   040000    075959  1691971199  ...    721  0.104590 -0.935304    -1.0
722  20230814   080000    115959  1691985599  ...    722  0.050683 -1.058488    -1.0

[5 rows x 15 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '51.388', 'enterprice': '29432.6', 'countrevence': '0', 'unrealprofit': '2070.9364', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '29392.3', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'numpy.int64'>, curSign=-1, self.sign=-1
--handleKline--:  version='2.0.0', self.name='s_rsrs', self.symbol='BTCUSDT', interval='4h', intervalSec=14400, wid=25, thd=0.6, self.sign=-1, self.total=1510969.9663512, self.flagDict['side']='sell', self.tradeCount=20, self.count=553
self.closeSec=1691999999, self.tradeDate='20230814', self.openTime='120000', self.closeTime='155959', self.symbol='BTCUSDT', self.open=29390.0, self.close=29410.5, self.high=29466.3, self.low=29379.4, self.vol=22168.394, self.amt=652098086.6225 
127.0.0.1 - - [14/Aug/2023 16:00:01] "POST / HTTP/1.1" 200 -
2023-08-14 16:00:01,664:INFO:s_rsrs:main.py:141:handleKline:2218689: self.closeSec=1691999999, self.tradeDate='20230814', self.openTime='120000', self.closeTime='155959',self.symbol='BTCUSDT',self.open=29390.0, self.close=29410.5, self.high=29466.3, self.low=29379.4, self.vol=22168.394, self.amt=652098086.6225 
2023-08-14 16:00:01,678:INFO:s_rsrs:main.py:142:handleKline:2218689: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime  ...        vol           amt       pct
719  20230813   200000    235959  ...   9903.451  2.908476e+08 -0.000378
720  20230814   000000    035959  ...  20860.595  6.130015e+08  0.002152
721  20230814   040000    075959  ...  24677.795  7.239654e+08 -0.004513
722  20230814   080000    115959  ...  68307.498  1.998169e+09  0.003301
723  20230814   120000    155959  ...  22168.394  6.520981e+08  0.000698

[5 rows x 11 columns]
2023-08-14 16:00:02,413:INFO:s_rsrs:main.py:151:handleKline:2218689: df_s.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec  ...  index      beta    zscore  signal
719  20230813   200000    235959  1691942399  ...    719  1.041921  1.239832     1.0
720  20230814   000000    035959  1691956799  ...    720  0.068942 -1.018602    -1.0
721  20230814   040000    075959  1691971199  ...    721  0.104590 -0.935304    -1.0
722  20230814   080000    115959  1691985599  ...    722  0.050683 -1.058488    -1.0
723  20230814   120000    155959  1691999999  ...    723  0.015864 -1.133319    -1.0

[5 rows x 15 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '51.388', 'enterprice': '29432.6', 'countrevence': '0', 'unrealprofit': '1135.6748', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '29410.5', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'numpy.int64'>, curSign=-1, self.sign=-1


