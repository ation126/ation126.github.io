# 20230224 16:26:02

## /root/FIL/strategy/amihud/log.txt ----- -----

--handleKline--:  127.0.0.1 - - [24/Feb/2023 16:20:01] "POST / HTTP/1.1" 200 -
version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=993672.4896432, self.flagDict['side']='sell', self.tradeCount=2, self.count=25660
self.closeSec=1677226799, self.tradeDate='20230224', self.openTime='161500', self.closeTime='161959', self.symbol='BTCUSDT', self.open=23750.4, self.close=23777.6, self.high=23783.4, self.low=23741.5, self.vol=2274.045, self.amt=54042305.3599 
2023-02-24 16:20:01,589:INFO:amihud:main.py:172:handleKline:200676: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5951  20230224   155500    155959  ...         0.0        0.0       0
5952  20230224   160000    160459  ...         0.0        0.0       0
5953  20230224   160500    160959  ...         0.0        0.0       0
5954  20230224   161000    161459  ...         0.0        0.0       0
5955  20230224   161500    161959  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-02-24 16:20:01,591:INFO:amihud:main.py:175:handleKline:200676: self.closeSec=1677226799, self.tradeDate='20230224', self.openTime='161500', self.closeTime='161959',self.symbol='BTCUSDT',self.open=23750.4, self.close=23777.6, self.high=23783.4, self.low=23741.5, self.vol=2274.045, self.amt=54042305.3599, ukdf['pct'].iloc[-1]=0.001141 , ukdf['amount'].iloc[-1]=54042305.3599, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5955, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '60.176', 'enterprice': '16529.3', 'countrevence': '0', 'unrealprofit': '-436167.6832', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '23777.5', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1
--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=993672.4896432, self.flagDict['side']='sell', self.tradeCount=2, self.count=25661
self.closeSec=1677227099, self.tradeDate='20230224', self.openTime='162000', self.closeTime='162459', self.symbol='BTCUSDT', self.open=23777.6, self.close=23784.8, self.high=23805.5, self.low=23770.1, self.vol=1178.016, self.amt=28020608.8258 
127.0.0.1 - - [24/Feb/2023 16:25:01] "POST / HTTP/1.1" 200 -
2023-02-24 16:25:01,560:INFO:amihud:main.py:172:handleKline:200676: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5952  20230224   160000    160459  ...         0.0        0.0       0
5953  20230224   160500    160959  ...         0.0        0.0       0
5954  20230224   161000    161459  ...         0.0        0.0       0
5955  20230224   161500    161959  ...         0.0        0.0       0
5956  20230224   162000    162459  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-02-24 16:25:01,560:INFO:amihud:main.py:175:handleKline:200676: self.closeSec=1677227099, self.tradeDate='20230224', self.openTime='162000', self.closeTime='162459',self.symbol='BTCUSDT',self.open=23777.6, self.close=23784.8, self.high=23805.5, self.low=23770.1, self.vol=1178.016, self.amt=28020608.8258, ukdf['pct'].iloc[-1]=0.000303 , ukdf['amount'].iloc[-1]=28020608.8258, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5956, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '60.176', 'enterprice': '16529.3', 'countrevence': '0', 'unrealprofit': '-436606.968', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '23784.8', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1


## /root/FIL/strategy/factorcheck/log.txt ----- -----

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=0, self.factor=0.6339438213341415, self.count=26226 

self.closeSec=1677226799, self.tradeDate='20230224', self.openTime='161500', self.closeTime='161959', self.symbol='BTCUSDT', self.open=23750.4, self.close=23777.6, self.high=23783.4, self.low=23741.5 
2023-02-24 16:20:01,517:INFO:factorcheck2:main.py:126:handleKline:185239: self.closeSec=1677226799, self.tradeDate='20230224', self.openTime='161500', self.closeTime='161959',self.symbol='BTCUSDT',self.open=23750.4, self.close=23777.6, self.high=23783.4, self.low=23741.5   
2023-02-24 16:20:01,547:INFO:factorcheck2:main.py:127:handleKline:185239: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime    closeSec  ...      low       pct  index  idx
1631  20230224   155500    155959  1677225599  ...  23809.1 -0.001300   1631    5
1632  20230224   160000    160459  1677225899  ...  23807.7  0.000777   1632    0
1633  20230224   160500    160959  1677226199  ...  23780.0 -0.002450   1633    1
1634  20230224   161000    161459  1677226499  ...  23750.4 -0.001308   1634    2
1635  20230224   161500    161959  1677226799  ...  23741.5  0.001141   1635    3

[5 rows x 11 columns]
2023-02-24 16:20:01,547:INFO:factorcheck2:main.py:128:handleKline:185239: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': True, 'isOpenSell': False, 'isCloseBuy': False, 'isCloseSell': False, 'isOpen': True, 'isClose': False, 'isTrig': True}
127.0.0.1 - - [24/Feb/2023 16:25:01] "POST / HTTP/1.1" 200 -

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=0, self.factor=0.6339438213341415, self.count=26227 

self.closeSec=1677227099, self.tradeDate='20230224', self.openTime='162000', self.closeTime='162459', self.symbol='BTCUSDT', self.open=23777.6, self.close=23784.8, self.high=23805.5, self.low=23770.1 
2023-02-24 16:25:01,510:INFO:factorcheck2:main.py:126:handleKline:185239: self.closeSec=1677227099, self.tradeDate='20230224', self.openTime='162000', self.closeTime='162459',self.symbol='BTCUSDT',self.open=23777.6, self.close=23784.8, self.high=23805.5, self.low=23770.1   
2023-02-24 16:25:01,534:INFO:factorcheck2:main.py:127:handleKline:185239: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime    closeSec  ...      low       pct  index  idx
1632  20230224   160000    160459  1677225899  ...  23807.7  0.000777   1632    0
1633  20230224   160500    160959  1677226199  ...  23780.0 -0.002450   1633    1
1634  20230224   161000    161459  1677226499  ...  23750.4 -0.001308   1634    2
1635  20230224   161500    161959  1677226799  ...  23741.5  0.001141   1635    3
1636  20230224   162000    162459  1677227099  ...  23770.1  0.000303   1636    4

[5 rows x 11 columns]
2023-02-24 16:25:01,549:INFO:factorcheck2:main.py:128:handleKline:185239: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': True, 'isOpenSell': False, 'isCloseBuy': False, 'isCloseSell': False, 'isOpen': True, 'isClose': False, 'isTrig': True}


## /root/FIL/strategy/logic/log.txt ----- -----

2023-02-24 16:00:37,912:DEBUG:logic:main.py:463:getModel:885513: df_s.iloc[-5:,:] :
          date closeTime     open  ...    alpha58   alpha67   alpha72
5786  20230224    132959  23928.6  ...  49.583333  0.466786  0.604899
5787  20230224    135959  23906.9  ...  49.583333  0.463520  0.603296
5788  20230224    142959  23887.7  ...  49.583333  0.457969  0.604860
5789  20230224    145959  23855.0  ...  50.000000  0.463161  0.602228
5790  20230224    152959  23880.8  ...  50.000000  0.447513  0.607573

[5 rows x 33 columns]
0.5295202952029521
acc is : 0.5295202952029521
2023-02-24 16:00:38,099:INFO:logic:main.py:468:getModel:885513: df_pred.iloc[-5:,:] :
     pred    prob_0    prob_1  actual  ...       nav  sign  cost_        bm
537     0  0.509610  0.490390       0  ...  0.991094   1.0    0.0  1.095761
538     0  0.506558  0.493442       0  ...  0.989741   1.0    0.0  1.094266
539     0  0.502243  0.497757       1  ...  0.990812   1.0    0.0  1.095450
540     0  0.514657  0.485343       0  ...  0.986982   1.0    0.0  1.091216
541     1  0.487698  0.512302       1  ...  0.988352   1.0    0.0  1.092729

[5 rows x 10 columns]
2023-02-24 16:00:38,143:INFO:logic:main.py:478:getModel:885513: df_panel.iloc[-5:,:] :
    pred    prob_0    prob_1  actual  ...       nav  sign  cost_        bm
45     0  0.509606  0.490394       0  ...  1.029867   1.0    0.0  1.096652
46     0  0.507476  0.492524       0  ...  0.967002   1.0    0.0  1.097332
47     0  0.502232  0.497768       1  ...  1.029574   1.0    0.0  1.096838
48     0  0.515604  0.484396       0  ...  0.964306   1.0    0.0  1.094922
49     1  0.487698  0.512302       1  ...  0.988352   1.0    0.0  1.092729

[5 rows x 10 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '33.103', 'enterprice': '23978.6', 'countrevence': '0', 'unrealprofit': '-5025.0354', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '23826.8', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}


## /root/FIL/strategy/modifiedmom/log.txt ----- -----

527  20230224   155000    155959  1677225599  23844.8  23821.5 -0.000969
2023-02-24 16:00:02,238:INFO:modifiedmom:main.py:146:handleKline:185213: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': True, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True}

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=13112 

self.closeSec=1677226199, self.tradeDate='20230224', self.openTime='160000', self.closeTime='160959', self.symbol='BTCUSDT', self.open='23821.6', self.close='23781.6'
2023-02-24 16:10:01,795:INFO:modifiedmom:main.py:144:handleKline:185213: self.closeSec=1677226199, self.tradeDate='20230224', self.openTime='160000', self.closeTime='160959',self.symbol='BTCUSDT',self.open='23821.6', self.close='23781.6'
127.0.0.1 - - [24/Feb/2023 16:10:01] "POST / HTTP/1.1" 200 -
2023-02-24 16:10:01,839:INFO:modifiedmom:main.py:145:handleKline:185213: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec     open    close       pct
524  20230224   152000    152959  1677223799  23794.1  23788.5 -0.000135
525  20230224   153000    153959  1677224399  23788.5  23808.9  0.000858
526  20230224   154000    154959  1677224999    23809  23844.6  0.001499
527  20230224   155000    155959  1677225599  23844.8  23821.5 -0.000969
528  20230224   160000    160959  1677226199  23821.6  23781.6 -0.001675
2023-02-24 16:10:01,839:INFO:modifiedmom:main.py:146:handleKline:185213: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': True, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True}

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=13113 

self.closeSec=1677226799, self.tradeDate='20230224', self.openTime='161000', self.closeTime='161959', self.symbol='BTCUSDT', self.open='23778.9', self.close='23777.6'
127.0.0.1 - - [24/Feb/2023 16:20:01] "POST / HTTP/1.1" 200 -
2023-02-24 16:20:01,740:INFO:modifiedmom:main.py:144:handleKline:185213: self.closeSec=1677226799, self.tradeDate='20230224', self.openTime='161000', self.closeTime='161959',self.symbol='BTCUSDT',self.open='23778.9', self.close='23777.6'
2023-02-24 16:20:01,760:INFO:modifiedmom:main.py:145:handleKline:185213: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec     open    close       pct
525  20230224   153000    153959  1677224399  23788.5  23808.9  0.000858
526  20230224   154000    154959  1677224999    23809  23844.6  0.001499
527  20230224   155000    155959  1677225599  23844.8  23821.5 -0.000969
528  20230224   160000    160959  1677226199  23821.6  23781.6 -0.001675
529  20230224   161000    161959  1677226799  23778.9  23777.6 -0.000168
2023-02-24 16:20:01,762:INFO:modifiedmom:main.py:146:handleKline:185213: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': True, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True}


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

17519  20230224   155000    155959  1677225599  23844.8  23821.5
2023-02-24 16:00:02,233:INFO:pyemd2:main.py:127:handleKline:185189: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=13113 

self.closeSec=1677226199, self.tradeDate='20230224', self.openTime='160000', self.closeTime='160959', self.symbol='BTCUSDT', self.open='23821.6', self.close='23781.6'
127.0.0.1 - - [24/Feb/2023 16:10:01] "POST / HTTP/1.1" 200 -
2023-02-24 16:10:01,835:INFO:pyemd2:main.py:125:handleKline:185189: self.closeSec=1677226199, self.tradeDate='20230224', self.openTime='160000', self.closeTime='160959',self.symbol='BTCUSDT',self.open='23821.6', self.close='23781.6'
2023-02-24 16:10:01,862:INFO:pyemd2:main.py:126:handleKline:185189: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
17516  20230224   152000    152959  1677223799  23794.1  23788.5
17517  20230224   153000    153959  1677224399  23788.5  23808.9
17518  20230224   154000    154959  1677224999    23809  23844.6
17519  20230224   155000    155959  1677225599  23844.8  23821.5
17520  20230224   160000    160959  1677226199  23821.6  23781.6
2023-02-24 16:10:01,862:INFO:pyemd2:main.py:127:handleKline:185189: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=13114 

self.closeSec=1677226799, self.tradeDate='20230224', self.openTime='161000', self.closeTime='161959', self.symbol='BTCUSDT', self.open='23778.9', self.close='23777.6'
127.0.0.1 - - [24/Feb/2023 16:20:01] "POST / HTTP/1.1" 200 -
2023-02-24 16:20:01,729:INFO:pyemd2:main.py:125:handleKline:185189: self.closeSec=1677226799, self.tradeDate='20230224', self.openTime='161000', self.closeTime='161959',self.symbol='BTCUSDT',self.open='23778.9', self.close='23777.6'
2023-02-24 16:20:01,761:INFO:pyemd2:main.py:126:handleKline:185189: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
17517  20230224   153000    153959  1677224399  23788.5  23808.9
17518  20230224   154000    154959  1677224999    23809  23844.6
17519  20230224   155000    155959  1677225599  23844.8  23821.5
17520  20230224   160000    160959  1677226199  23821.6  23781.6
17521  20230224   161000    161959  1677226799  23778.9  23777.6
2023-02-24 16:20:01,762:INFO:pyemd2:main.py:127:handleKline:185189: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}


## /root/FIL/strategy/similarity/log.txt ----- -----

12191  20230224   155000    155959  1677225599  23844.8  23821.5
2023-02-24 16:00:02,221:INFO:testStrategy:main.py:103:handleKline:185174: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': True, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True, 'isCorr': False}
127.0.0.1 - - [24/Feb/2023 16:10:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=13113 

self.closeSec=1677226199, self.tradeDate='20230224', self.openTime='160000', self.closeTime='160959', self.symbol='BTCUSDT', self.open='23821.6', self.close='23781.6'
2023-02-24 16:10:01,792:INFO:testStrategy:main.py:101:handleKline:185174: self.closeSec=1677226199, self.tradeDate='20230224', self.openTime='160000', self.closeTime='160959',self.symbol='BTCUSDT',self.open='23821.6', self.close='23781.6'
2023-02-24 16:10:01,848:INFO:testStrategy:main.py:102:handleKline:185174: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
12188  20230224   152000    152959  1677223799  23794.1  23788.5
12189  20230224   153000    153959  1677224399  23788.5  23808.9
12190  20230224   154000    154959  1677224999    23809  23844.6
12191  20230224   155000    155959  1677225599  23844.8  23821.5
12192  20230224   160000    160959  1677226199  23821.6  23781.6
2023-02-24 16:10:01,848:INFO:testStrategy:main.py:103:handleKline:185174: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': True, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True, 'isCorr': False}

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=13114 

self.closeSec=1677226799, self.tradeDate='20230224', self.openTime='161000', self.closeTime='161959', self.symbol='BTCUSDT', self.open='23778.9', self.close='23777.6'
127.0.0.1 - - [24/Feb/2023 16:20:01] "POST / HTTP/1.1" 200 -
2023-02-24 16:20:01,737:INFO:testStrategy:main.py:101:handleKline:185174: self.closeSec=1677226799, self.tradeDate='20230224', self.openTime='161000', self.closeTime='161959',self.symbol='BTCUSDT',self.open='23778.9', self.close='23777.6'
2023-02-24 16:20:01,770:INFO:testStrategy:main.py:102:handleKline:185174: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
12189  20230224   153000    153959  1677224399  23788.5  23808.9
12190  20230224   154000    154959  1677224999    23809  23844.6
12191  20230224   155000    155959  1677225599  23844.8  23821.5
12192  20230224   160000    160959  1677226199  23821.6  23781.6
12193  20230224   161000    161959  1677226799  23778.9  23777.6
2023-02-24 16:20:01,770:INFO:testStrategy:main.py:103:handleKline:185174: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': True, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True, 'isCorr': False}


## /root/FIL/strategy/sr_min/log.txt ----- -----

--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=0, self.total=1000000.0, self.flagDict['side']='', self.tradeCount=0, self.count=21658
self.closeSec=1677226799, self.tradeDate='20230224', self.openTime='161500', self.closeTime='161959', self.symbol='BTCUSDT', self.open=23750.4, self.close=23777.6, self.high=23783.4, self.low=23741.5, self.vol=2274.045, self.amt=54042305.3599 
127.0.0.1 - - [24/Feb/2023 16:20:01] "POST / HTTP/1.1" 200 -
2023-02-24 16:20:01,561:INFO:sr_min:main.py:172:handleKline:449472: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5951  20230224   155500    155959  ...         0.0        0.0       0
5952  20230224   160000    160459  ...         0.0        0.0       0
5953  20230224   160500    160959  ...         0.0        0.0       0
5954  20230224   161000    161459  ...         0.0        0.0       0
5955  20230224   161500    161959  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-02-24 16:20:01,572:INFO:sr_min:main.py:175:handleKline:449472: self.closeSec=1677226799, self.tradeDate='20230224', self.openTime='161500', self.closeTime='161959',self.symbol='BTCUSDT',self.open=23750.4, self.close=23777.6, self.high=23783.4, self.low=23741.5, self.vol=2274.045, self.amt=54042305.3599, ukdf['pct'].iloc[-1]=0.001141 , ukdf['amount'].iloc[-1]=54042305.3599, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5955, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': []}
type(curSign)=<class 'int'>, curSign=0, self.sign=0
--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=0, self.total=1000000.0, self.flagDict['side']='', self.tradeCount=0, self.count=21659
self.closeSec=1677227099, self.tradeDate='20230224', self.openTime='162000', self.closeTime='162459', self.symbol='BTCUSDT', self.open=23777.6, self.close=23784.8, self.high=23805.5, self.low=23770.1, self.vol=1178.016, self.amt=28020608.8258 
127.0.0.1 - - [24/Feb/2023 16:25:01] "POST / HTTP/1.1" 200 -
2023-02-24 16:25:01,557:INFO:sr_min:main.py:172:handleKline:449472: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5952  20230224   160000    160459  ...         0.0        0.0       0
5953  20230224   160500    160959  ...         0.0        0.0       0
5954  20230224   161000    161459  ...         0.0        0.0       0
5955  20230224   161500    161959  ...         0.0        0.0       0
5956  20230224   162000    162459  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-02-24 16:25:01,558:INFO:sr_min:main.py:175:handleKline:449472: self.closeSec=1677227099, self.tradeDate='20230224', self.openTime='162000', self.closeTime='162459',self.symbol='BTCUSDT',self.open=23777.6, self.close=23784.8, self.high=23805.5, self.low=23770.1, self.vol=1178.016, self.amt=28020608.8258, ukdf['pct'].iloc[-1]=0.000303 , ukdf['amount'].iloc[-1]=28020608.8258, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5956, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': []}
type(curSign)=<class 'int'>, curSign=0, self.sign=0


## /root/FIL/strategy/s_rsrs/log.txt ----- -----

721  20230224   040000    075959  1677196799  ...    721  0.559513 -0.113242     NaN
722  20230224   080000    115959  1677211199  ...    722  0.576195 -0.081610     NaN

[5 rows x 15 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '36.465', 'enterprice': '24934.8', 'countrevence': '0', 'unrealprofit': '36049.299', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '23946.2', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'numpy.int64'>, curSign=-9223372036854775808, self.sign=-1
127.0.0.1 - - [24/Feb/2023 16:00:02] "POST / HTTP/1.1" 200 -
--handleKline--:  version='2.0.0', self.name='s_rsrs', self.symbol='BTCUSDT', interval='4h', intervalSec=14400, wid=25, thd=0.6, self.sign=-1, self.total=908338.234518, self.flagDict['side']='sell', self.tradeCount=21, self.count=546
self.closeSec=1677225599, self.tradeDate='20230224', self.openTime='120000', self.closeTime='155959', self.symbol='BTCUSDT', self.open=23945.1, self.close=23821.5, self.high=23974.6, self.low=23754.0, self.vol=55400.746, self.amt=1321313508.4031 
2023-02-24 16:00:02,090:INFO:s_rsrs:main.py:141:handleKline:185271: self.closeSec=1677225599, self.tradeDate='20230224', self.openTime='120000', self.closeTime='155959',self.symbol='BTCUSDT',self.open=23945.1, self.close=23821.5, self.high=23974.6, self.low=23754.0, self.vol=55400.746, self.amt=1321313508.4031 
2023-02-24 16:00:02,161:INFO:s_rsrs:main.py:142:handleKline:185271: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime  ...         vol           amt       pct
719  20230223   200000    235959  ...  246653.418  5.911671e+09  0.007271
720  20230224   000000    035959  ...  126451.880  3.018235e+09  0.000927
721  20230224   040000    075959  ...   60185.891  1.438425e+09 -0.001398
722  20230224   080000    115959  ...   59502.415  1.427399e+09  0.000685
723  20230224   120000    155959  ...   55400.746  1.321314e+09 -0.005162

[5 rows x 11 columns]
2023-02-24 16:00:05,065:INFO:s_rsrs:main.py:151:handleKline:185271: df_s.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec  ...  index      beta    zscore  signal
719  20230223   200000    235959  1677167999  ...    719  0.487523 -0.279294     NaN
720  20230224   000000    035959  1677182399  ...    720  0.513627 -0.220280     NaN
721  20230224   040000    075959  1677196799  ...    721  0.559513 -0.113242     NaN
722  20230224   080000    115959  1677211199  ...    722  0.576195 -0.081610     NaN
723  20230224   120000    155959  1677225599  ...    723  0.630339  0.043797     NaN

[5 rows x 15 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '36.465', 'enterprice': '24934.8', 'countrevence': '0', 'unrealprofit': '40596.4845', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '23821.5', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'numpy.int64'>, curSign=-9223372036854775808, self.sign=-1


