# 20230309 16:26:01

## /root/FIL/strategy/amihud/log.txt ----- -----

--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=993672.4896432, self.flagDict['side']='sell', self.tradeCount=2, self.count=29404
self.closeSec=1678349999, self.tradeDate='20230309', self.openTime='161500', self.closeTime='161959', self.symbol='BTCUSDT', self.open=21647.0, self.close=21642.0, self.high=21658.9, self.low=21640.0, self.vol=1166.273, self.amt=25250619.6278 
127.0.0.1 - - [09/Mar/2023 16:20:01] "POST / HTTP/1.1" 200 -
2023-03-09 16:20:01,609:INFO:amihud:main.py:172:handleKline:200676: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5951  20230309   155500    155959  ...         0.0        0.0       0
5952  20230309   160000    160459  ...         0.0        0.0       0
5953  20230309   160500    160959  ...         0.0        0.0       0
5954  20230309   161000    161459  ...         0.0        0.0       0
5955  20230309   161500    161959  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-03-09 16:20:01,613:INFO:amihud:main.py:175:handleKline:200676: self.closeSec=1678349999, self.tradeDate='20230309', self.openTime='161500', self.closeTime='161959',self.symbol='BTCUSDT',self.open=21647.0, self.close=21642.0, self.high=21658.9, self.low=21640.0, self.vol=1166.273, self.amt=25250619.6278, ukdf['pct'].iloc[-1]=-0.000231 , ukdf['amount'].iloc[-1]=25250619.6278, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5955, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '60.176', 'enterprice': '16529.3', 'countrevence': '0', 'unrealprofit': '-307776.1614371256', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '21643.89986435', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1
--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=993672.4896432, self.flagDict['side']='sell', self.tradeCount=2, self.count=29405
self.closeSec=1678350299, self.tradeDate='20230309', self.openTime='162000', self.closeTime='162459', self.symbol='BTCUSDT', self.open=21642.0, self.close=21627.4, self.high=21642.1, self.low=21626.0, self.vol=1075.543, self.amt=23268785.7055 
127.0.0.1 - - [09/Mar/2023 16:25:01] "POST / HTTP/1.1" 200 -
2023-03-09 16:25:01,573:INFO:amihud:main.py:172:handleKline:200676: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5952  20230309   160000    160459  ...         0.0        0.0       0
5953  20230309   160500    160959  ...         0.0        0.0       0
5954  20230309   161000    161459  ...         0.0        0.0       0
5955  20230309   161500    161959  ...         0.0        0.0       0
5956  20230309   162000    162459  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-03-09 16:25:01,585:INFO:amihud:main.py:175:handleKline:200676: self.closeSec=1678350299, self.tradeDate='20230309', self.openTime='162000', self.closeTime='162459',self.symbol='BTCUSDT',self.open=21642.0, self.close=21627.4, self.high=21642.1, self.low=21626.0, self.vol=1075.543, self.amt=23268785.7055, ukdf['pct'].iloc[-1]=-0.000675 , ukdf['amount'].iloc[-1]=23268785.7055, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5956, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '60.176', 'enterprice': '16529.3', 'countrevence': '0', 'unrealprofit': '-306755.3750138952', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '21626.93651645', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1


## /root/FIL/strategy/factorcheck/log.txt ----- -----

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=0, self.factor=0.7057720568442897, self.count=29970 

self.closeSec=1678349999, self.tradeDate='20230309', self.openTime='161500', self.closeTime='161959', self.symbol='BTCUSDT', self.open=21647.0, self.close=21642.0, self.high=21658.9, self.low=21640.0 
2023-03-09 16:20:01,500:INFO:factorcheck2:main.py:126:handleKline:185239: self.closeSec=1678349999, self.tradeDate='20230309', self.openTime='161500', self.closeTime='161959',self.symbol='BTCUSDT',self.open=21647.0, self.close=21642.0, self.high=21658.9, self.low=21640.0   
2023-03-09 16:20:01,541:INFO:factorcheck2:main.py:127:handleKline:185239: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime    closeSec  ...      low       pct  index  idx
1631  20230309   155500    155959  1678348799  ...  21673.7  0.000305   1631    5
1632  20230309   160000    160459  1678349099  ...  21638.0 -0.001351   1632    0
1633  20230309   160500    160959  1678349399  ...  21582.0 -0.000998   1633    1
1634  20230309   161000    161459  1678349699  ...  21628.8  0.000786   1634    2
1635  20230309   161500    161959  1678349999  ...  21640.0 -0.000231   1635    3

[5 rows x 11 columns]
2023-03-09 16:20:01,542:INFO:factorcheck2:main.py:128:handleKline:185239: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': True, 'isOpenSell': False, 'isCloseBuy': False, 'isCloseSell': False, 'isOpen': True, 'isClose': False, 'isTrig': True}

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=0, self.factor=0.7057720568442897, self.count=29971 

self.closeSec=1678350299, self.tradeDate='20230309', self.openTime='162000', self.closeTime='162459', self.symbol='BTCUSDT', self.open=21642.0, self.close=21627.4, self.high=21642.1, self.low=21626.0 
2023-03-09 16:25:01,488:INFO:factorcheck2:main.py:126:handleKline:185239: self.closeSec=1678350299, self.tradeDate='20230309', self.openTime='162000', self.closeTime='162459',self.symbol='BTCUSDT',self.open=21642.0, self.close=21627.4, self.high=21642.1, self.low=21626.0   
127.0.0.1 - - [09/Mar/2023 16:25:01] "POST / HTTP/1.1" 200 -
2023-03-09 16:25:01,551:INFO:factorcheck2:main.py:127:handleKline:185239: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime    closeSec  ...      low       pct  index  idx
1632  20230309   160000    160459  1678349099  ...  21638.0 -0.001351   1632    0
1633  20230309   160500    160959  1678349399  ...  21582.0 -0.000998   1633    1
1634  20230309   161000    161459  1678349699  ...  21628.8  0.000786   1634    2
1635  20230309   161500    161959  1678349999  ...  21640.0 -0.000231   1635    3
1636  20230309   162000    162459  1678350299  ...  21626.0 -0.000675   1636    4

[5 rows x 11 columns]
2023-03-09 16:25:01,558:INFO:factorcheck2:main.py:128:handleKline:185239: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': True, 'isOpenSell': False, 'isCloseBuy': False, 'isCloseSell': False, 'isOpen': True, 'isClose': False, 'isTrig': True}


## /root/FIL/strategy/logic/log.txt ----- -----

2023-03-09 16:00:34,989:DEBUG:logic:main.py:463:getModel:885513: df_s.iloc[-5:,:] :
          date closeTime     open  ...    alpha58   alpha67   alpha72
5786  20230309    132959  21729.9  ...  43.750000  0.410256  0.647927
5787  20230309    135959  21732.3  ...  43.333333  0.409555  0.652929
5788  20230309    142959  21729.3  ...  42.916667  0.407902  0.658302
5789  20230309    145959  21722.1  ...  43.333333  0.412172  0.662075
5790  20230309    152959  21734.9  ...  42.916667  0.404530  0.668785

[5 rows x 33 columns]
0.5535055350553506
acc is : 0.5535055350553506
2023-03-09 16:00:35,116:INFO:logic:main.py:468:getModel:885513: df_pred.iloc[-5:,:] :
     pred    prob_0    prob_1  actual  ...       nav  sign  cost_        bm
537     0  0.510258  0.489742       0  ...  0.888358   1.0    0.0  0.941147
538     0  0.509719  0.490281       0  ...  0.888063   1.0    0.0  0.940835
539     0  0.505290  0.494710       1  ...  0.888582   1.0    0.0  0.941385
540     0  0.523026  0.476974       0  ...  0.887250   1.0    0.0  0.939973
541     1  0.496387  0.503613       0  ...  0.886379   1.0    0.0  0.939051

[5 rows x 10 columns]
2023-03-09 16:00:35,139:INFO:logic:main.py:478:getModel:885513: df_panel.iloc[-5:,:] :
    pred    prob_0    prob_1  actual  ...       nav  sign  cost_        bm
45     0  0.509845  0.490155       0  ...  0.915303   1.0    0.0  0.940259
46     0  0.509214  0.490786       0  ...  0.912388   1.0    0.0  0.937271
47     0  0.505123  0.494877       1  ...  0.910937   1.0    0.0  0.939022
48     0  0.523168  0.476832       0  ...  0.909570   1.0    0.0  0.939335
49     1  0.496387  0.503613       0  ...  0.886379   1.0    0.0  0.939051

[5 rows x 10 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '31.291', 'enterprice': '21761.4', 'countrevence': '0', 'unrealprofit': '-2392.33499181105', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '21684.94558845', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}


## /root/FIL/strategy/modifiedmom/log.txt ----- -----

527  20230309   155000    155959  1678348799  21689.6  21680.9 -0.000406
2023-03-09 16:00:02,066:INFO:modifiedmom:main.py:146:handleKline:185213: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': True, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True}

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=14984 

self.closeSec=1678349399, self.tradeDate='20230309', self.openTime='160000', self.closeTime='160959', self.symbol='BTCUSDT', self.open='21680.9', self.close='21630'
2023-03-09 16:10:01,726:INFO:modifiedmom:main.py:144:handleKline:185213: self.closeSec=1678349399, self.tradeDate='20230309', self.openTime='160000', self.closeTime='160959',self.symbol='BTCUSDT',self.open='21680.9', self.close='21630'
127.0.0.1 - - [09/Mar/2023 16:10:01] "POST / HTTP/1.1" 200 -
2023-03-09 16:10:01,736:INFO:modifiedmom:main.py:145:handleKline:185213: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec     open    close       pct
524  20230309   152000    152959  1678346999  21708.1  21702.3 -0.000267
525  20230309   153000    153959  1678347599  21702.3  21692.3 -0.000461
526  20230309   154000    154959  1678348199  21692.3  21689.7 -0.000120
527  20230309   155000    155959  1678348799  21689.6  21680.9 -0.000406
528  20230309   160000    160959  1678349399  21680.9    21630 -0.002348
2023-03-09 16:10:01,738:INFO:modifiedmom:main.py:146:handleKline:185213: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': True, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True}
127.0.0.1 - - [09/Mar/2023 16:20:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=14985 

self.closeSec=1678349999, self.tradeDate='20230309', self.openTime='161000', self.closeTime='161959', self.symbol='BTCUSDT', self.open='21629.9', self.close='21642'
2023-03-09 16:20:01,616:INFO:modifiedmom:main.py:144:handleKline:185213: self.closeSec=1678349999, self.tradeDate='20230309', self.openTime='161000', self.closeTime='161959',self.symbol='BTCUSDT',self.open='21629.9', self.close='21642'
2023-03-09 16:20:01,648:INFO:modifiedmom:main.py:145:handleKline:185213: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec     open    close       pct
525  20230309   153000    153959  1678347599  21702.3  21692.3 -0.000461
526  20230309   154000    154959  1678348199  21692.3  21689.7 -0.000120
527  20230309   155000    155959  1678348799  21689.6  21680.9 -0.000406
528  20230309   160000    160959  1678349399  21680.9    21630 -0.002348
529  20230309   161000    161959  1678349999  21629.9    21642  0.000555
2023-03-09 16:20:01,648:INFO:modifiedmom:main.py:146:handleKline:185213: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': True, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True}


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

17519  20230309   155000    155959  1678348799  21689.6  21680.9
2023-03-09 16:00:02,106:INFO:pyemd2:main.py:127:handleKline:185189: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}
127.0.0.1 - - [09/Mar/2023 16:10:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=14985 

self.closeSec=1678349399, self.tradeDate='20230309', self.openTime='160000', self.closeTime='160959', self.symbol='BTCUSDT', self.open='21680.9', self.close='21630'
2023-03-09 16:10:01,764:INFO:pyemd2:main.py:125:handleKline:185189: self.closeSec=1678349399, self.tradeDate='20230309', self.openTime='160000', self.closeTime='160959',self.symbol='BTCUSDT',self.open='21680.9', self.close='21630'
2023-03-09 16:10:01,806:INFO:pyemd2:main.py:126:handleKline:185189: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
17516  20230309   152000    152959  1678346999  21708.1  21702.3
17517  20230309   153000    153959  1678347599  21702.3  21692.3
17518  20230309   154000    154959  1678348199  21692.3  21689.7
17519  20230309   155000    155959  1678348799  21689.6  21680.9
17520  20230309   160000    160959  1678349399  21680.9    21630
2023-03-09 16:10:01,807:INFO:pyemd2:main.py:127:handleKline:185189: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=14986 

self.closeSec=1678349999, self.tradeDate='20230309', self.openTime='161000', self.closeTime='161959', self.symbol='BTCUSDT', self.open='21629.9', self.close='21642'
127.0.0.1 - - [09/Mar/2023 16:20:01] "POST / HTTP/1.1" 200 -
2023-03-09 16:20:01,679:INFO:pyemd2:main.py:125:handleKline:185189: self.closeSec=1678349999, self.tradeDate='20230309', self.openTime='161000', self.closeTime='161959',self.symbol='BTCUSDT',self.open='21629.9', self.close='21642'
2023-03-09 16:20:01,693:INFO:pyemd2:main.py:126:handleKline:185189: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
17517  20230309   153000    153959  1678347599  21702.3  21692.3
17518  20230309   154000    154959  1678348199  21692.3  21689.7
17519  20230309   155000    155959  1678348799  21689.6  21680.9
17520  20230309   160000    160959  1678349399  21680.9    21630
17521  20230309   161000    161959  1678349999  21629.9    21642
2023-03-09 16:20:01,693:INFO:pyemd2:main.py:127:handleKline:185189: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}


## /root/FIL/strategy/similarity/log.txt ----- -----

12191  20230309   155000    155959  1678348799  21689.6  21680.9
2023-03-09 16:00:02,102:INFO:testStrategy:main.py:103:handleKline:185174: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': True, 'isOpenSell': False, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True, 'isCorr': False}
127.0.0.1 - - [09/Mar/2023 16:10:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=14985 

self.closeSec=1678349399, self.tradeDate='20230309', self.openTime='160000', self.closeTime='160959', self.symbol='BTCUSDT', self.open='21680.9', self.close='21630'
2023-03-09 16:10:01,766:INFO:testStrategy:main.py:101:handleKline:185174: self.closeSec=1678349399, self.tradeDate='20230309', self.openTime='160000', self.closeTime='160959',self.symbol='BTCUSDT',self.open='21680.9', self.close='21630'
2023-03-09 16:10:01,809:INFO:testStrategy:main.py:102:handleKline:185174: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
12188  20230309   152000    152959  1678346999  21708.1  21702.3
12189  20230309   153000    153959  1678347599  21702.3  21692.3
12190  20230309   154000    154959  1678348199  21692.3  21689.7
12191  20230309   155000    155959  1678348799  21689.6  21680.9
12192  20230309   160000    160959  1678349399  21680.9    21630
2023-03-09 16:10:01,809:INFO:testStrategy:main.py:103:handleKline:185174: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': True, 'isOpenSell': False, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True, 'isCorr': False}

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=14986 

self.closeSec=1678349999, self.tradeDate='20230309', self.openTime='161000', self.closeTime='161959', self.symbol='BTCUSDT', self.open='21629.9', self.close='21642'
127.0.0.1 - - [09/Mar/2023 16:20:01] "POST / HTTP/1.1" 200 -
2023-03-09 16:20:01,644:INFO:testStrategy:main.py:101:handleKline:185174: self.closeSec=1678349999, self.tradeDate='20230309', self.openTime='161000', self.closeTime='161959',self.symbol='BTCUSDT',self.open='21629.9', self.close='21642'
2023-03-09 16:20:01,678:INFO:testStrategy:main.py:102:handleKline:185174: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
12189  20230309   153000    153959  1678347599  21702.3  21692.3
12190  20230309   154000    154959  1678348199  21692.3  21689.7
12191  20230309   155000    155959  1678348799  21689.6  21680.9
12192  20230309   160000    160959  1678349399  21680.9    21630
12193  20230309   161000    161959  1678349999  21629.9    21642
2023-03-09 16:20:01,678:INFO:testStrategy:main.py:103:handleKline:185174: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': True, 'isOpenSell': False, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True, 'isCorr': False}


## /root/FIL/strategy/sr_min/log.txt ----- -----

--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=0, self.total=1000000.0, self.flagDict['side']='', self.tradeCount=0, self.count=25402
self.closeSec=1678349999, self.tradeDate='20230309', self.openTime='161500', self.closeTime='161959', self.symbol='BTCUSDT', self.open=21647.0, self.close=21642.0, self.high=21658.9, self.low=21640.0, self.vol=1166.273, self.amt=25250619.6278 
127.0.0.1 - - [09/Mar/2023 16:20:01] "POST / HTTP/1.1" 200 -
2023-03-09 16:20:01,584:INFO:sr_min:main.py:172:handleKline:449472: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5951  20230309   155500    155959  ...         0.0        0.0       0
5952  20230309   160000    160459  ...         0.0        0.0       0
5953  20230309   160500    160959  ...         0.0        0.0       0
5954  20230309   161000    161459  ...         0.0        0.0       0
5955  20230309   161500    161959  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-03-09 16:20:01,584:INFO:sr_min:main.py:175:handleKline:449472: self.closeSec=1678349999, self.tradeDate='20230309', self.openTime='161500', self.closeTime='161959',self.symbol='BTCUSDT',self.open=21647.0, self.close=21642.0, self.high=21658.9, self.low=21640.0, self.vol=1166.273, self.amt=25250619.6278, ukdf['pct'].iloc[-1]=-0.000231 , ukdf['amount'].iloc[-1]=25250619.6278, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5955, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': []}
type(curSign)=<class 'int'>, curSign=0, self.sign=0
--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=0, self.total=1000000.0, self.flagDict['side']='', self.tradeCount=0, self.count=25403
self.closeSec=1678350299, self.tradeDate='20230309', self.openTime='162000', self.closeTime='162459', self.symbol='BTCUSDT', self.open=21642.0, self.close=21627.4, self.high=21642.1, self.low=21626.0, self.vol=1075.543, self.amt=23268785.7055 
127.0.0.1 - - [09/Mar/2023 16:25:01] "POST / HTTP/1.1" 200 -
2023-03-09 16:25:01,577:INFO:sr_min:main.py:172:handleKline:449472: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5952  20230309   160000    160459  ...         0.0        0.0       0
5953  20230309   160500    160959  ...         0.0        0.0       0
5954  20230309   161000    161459  ...         0.0        0.0       0
5955  20230309   161500    161959  ...         0.0        0.0       0
5956  20230309   162000    162459  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-03-09 16:25:01,577:INFO:sr_min:main.py:175:handleKline:449472: self.closeSec=1678350299, self.tradeDate='20230309', self.openTime='162000', self.closeTime='162459',self.symbol='BTCUSDT',self.open=21642.0, self.close=21627.4, self.high=21642.1, self.low=21626.0, self.vol=1075.543, self.amt=23268785.7055, ukdf['pct'].iloc[-1]=-0.000675 , ukdf['amount'].iloc[-1]=23268785.7055, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5956, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': []}
type(curSign)=<class 'int'>, curSign=0, self.sign=0


## /root/FIL/strategy/s_rsrs/log.txt ----- -----

721  20230309   040000    075959  1678319999  ...    721  0.169537 -1.290595    -1.0
722  20230309   080000    115959  1678334399  ...    722  0.268502 -0.961452    -1.0

[5 rows x 15 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '42.135', 'enterprice': '23350.3', 'countrevence': '0', 'unrealprofit': '66758.694', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '21765.9', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'numpy.int64'>, curSign=-1, self.sign=-1
--handleKline--:  version='2.0.0', self.name='s_rsrs', self.symbol='BTCUSDT', interval='4h', intervalSec=14400, wid=25, thd=0.6, self.sign=-1, self.total=982881.0256095, self.flagDict['side']='sell', self.tradeCount=23, self.count=624
self.closeSec=1678348799, self.tradeDate='20230309', self.openTime='120000', self.closeTime='155959', self.symbol='BTCUSDT', self.open=21762.6, self.close=21681.0, self.high=21766.0, self.low=21660.0, self.vol=30228.722, self.amt=656451671.9533 
127.0.0.1 - - [09/Mar/2023 16:00:01] "POST / HTTP/1.1" 200 -
2023-03-09 16:00:01,926:INFO:s_rsrs:main.py:141:handleKline:185271: self.closeSec=1678348799, self.tradeDate='20230309', self.openTime='120000', self.closeTime='155959',self.symbol='BTCUSDT',self.open=21762.6, self.close=21681.0, self.high=21766.0, self.low=21660.0, self.vol=30228.722, self.amt=656451671.9533 
2023-03-09 16:00:01,985:INFO:s_rsrs:main.py:142:handleKline:185271: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime  ...         vol           amt       pct
719  20230308   200000    235959  ...  148584.459  3.274852e+09  0.003096
720  20230309   000000    035959  ...   77456.277  1.708864e+09 -0.006137
721  20230309   040000    075959  ...  124293.667  2.713469e+09 -0.013568
722  20230309   080000    115959  ...   53609.885  1.164707e+09  0.003102
723  20230309   120000    155959  ...   30228.722  6.564517e+08 -0.003750

[5 rows x 11 columns]
2023-03-09 16:00:04,433:INFO:s_rsrs:main.py:151:handleKline:185271: df_s.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec  ...  index      beta    zscore  signal
719  20230308   200000    235959  1678291199  ...    719  0.142494 -1.353199    -1.0
720  20230309   000000    035959  1678305599  ...    720  0.172296 -1.266241    -1.0
721  20230309   040000    075959  1678319999  ...    721  0.169537 -1.290595    -1.0
722  20230309   080000    115959  1678334399  ...    722  0.268502 -0.961452    -1.0
723  20230309   120000    155959  1678348799  ...    723  0.364721 -0.637468    -1.0

[5 rows x 15 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '42.135', 'enterprice': '23350.3', 'countrevence': '0', 'unrealprofit': '70316.9791196004', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '21681.45037096', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'numpy.int64'>, curSign=-1, self.sign=-1


