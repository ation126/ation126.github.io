# 20230312 16:26:02

## /root/FIL/strategy/amihud/log.txt ----- -----

--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=993672.4896432, self.flagDict['side']='sell', self.tradeCount=2, self.count=30268
self.closeSec=1678609199, self.tradeDate='20230312', self.openTime='161500', self.closeTime='161959', self.symbol='BTCUSDT', self.open=20359.6, self.close=20372.4, self.high=20388.0, self.low=20349.2, self.vol=1644.942, self.amt=33507032.313 
127.0.0.1 - - [12/Mar/2023 16:20:01] "POST / HTTP/1.1" 200 -
2023-03-12 16:20:03,281:INFO:amihud:main.py:172:handleKline:200676: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5951  20230312   155500    155959  ...         0.0        0.0       0
5952  20230312   160000    160459  ...         0.0        0.0       0
5953  20230312   160500    160959  ...         0.0        0.0       0
5954  20230312   161000    161459  ...         0.0        0.0       0
5955  20230312   161500    161959  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-03-12 16:20:03,300:INFO:amihud:main.py:175:handleKline:200676: self.closeSec=1678609199, self.tradeDate='20230312', self.openTime='161500', self.closeTime='161959',self.symbol='BTCUSDT',self.open=20359.6, self.close=20372.4, self.high=20388.0, self.low=20349.2, self.vol=1644.942, self.amt=33507032.313, ukdf['pct'].iloc[-1]=0.000624 , ukdf['amount'].iloc[-1]=33507032.313, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5955, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '60.176', 'enterprice': '16529.3', 'countrevence': '0', 'unrealprofit': '-231256.368', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '20372.3', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1
--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=993672.4896432, self.flagDict['side']='sell', self.tradeCount=2, self.count=30269
self.closeSec=1678609499, self.tradeDate='20230312', self.openTime='162000', self.closeTime='162459', self.symbol='BTCUSDT', self.open=20372.4, self.close=20363.5, self.high=20383.7, self.low=20355.8, self.vol=1051.948, self.amt=21427735.4763 
127.0.0.1 - - [12/Mar/2023 16:25:01] "POST / HTTP/1.1" 200 -
2023-03-12 16:25:01,611:INFO:amihud:main.py:172:handleKline:200676: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5952  20230312   160000    160459  ...         0.0        0.0       0
5953  20230312   160500    160959  ...         0.0        0.0       0
5954  20230312   161000    161459  ...         0.0        0.0       0
5955  20230312   161500    161959  ...         0.0        0.0       0
5956  20230312   162000    162459  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-03-12 16:25:01,614:INFO:amihud:main.py:175:handleKline:200676: self.closeSec=1678609499, self.tradeDate='20230312', self.openTime='162000', self.closeTime='162459',self.symbol='BTCUSDT',self.open=20372.4, self.close=20363.5, self.high=20383.7, self.low=20355.8, self.vol=1051.948, self.amt=21427735.4763, ukdf['pct'].iloc[-1]=-0.000437 , ukdf['amount'].iloc[-1]=21427735.4763, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5956, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '60.176', 'enterprice': '16529.3', 'countrevence': '0', 'unrealprofit': '-230726.8192', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '20363.5', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1


## /root/FIL/strategy/factorcheck/log.txt ----- -----

 version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=23, self.factor=0.4287890319561219, self.count=30834 

self.closeSec=1678609199, self.tradeDate='20230312', self.openTime='161500', self.closeTime='161959', self.symbol='BTCUSDT', self.open=20359.6, self.close=20372.4, self.high=20388.0, self.low=20349.2 
2023-03-12 16:20:01,852:INFO:factorcheck2:main.py:126:handleKline:185239: self.closeSec=1678609199, self.tradeDate='20230312', self.openTime='161500', self.closeTime='161959',self.symbol='BTCUSDT',self.open=20359.6, self.close=20372.4, self.high=20388.0, self.low=20349.2   
2023-03-12 16:20:02,552:INFO:factorcheck2:main.py:127:handleKline:185239: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime    closeSec  ...      low       pct  index  idx
1631  20230312   155500    155959  1678607999  ...  20317.0  0.000650   1631    5
1632  20230312   160000    160459  1678608299  ...  20326.8  0.000816   1632    0
1633  20230312   160500    160959  1678608599  ...  20333.9 -0.000732   1633    1
1634  20230312   161000    161459  1678608899  ...  20337.2  0.001101   1634    2
1635  20230312   161500    161959  1678609199  ...  20349.2  0.000624   1635    3

[5 rows x 11 columns]
2023-03-12 16:20:02,552:INFO:factorcheck2:main.py:128:handleKline:185239: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': True, 'isOpenSell': False, 'isCloseBuy': False, 'isCloseSell': False, 'isOpen': True, 'isClose': False, 'isTrig': True}
127.0.0.1 - - [12/Mar/2023 16:25:01] "POST / HTTP/1.1" 200 -

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=23, self.factor=0.4287890319561219, self.count=30835 

self.closeSec=1678609499, self.tradeDate='20230312', self.openTime='162000', self.closeTime='162459', self.symbol='BTCUSDT', self.open=20372.4, self.close=20363.5, self.high=20383.7, self.low=20355.8 
2023-03-12 16:25:01,516:INFO:factorcheck2:main.py:126:handleKline:185239: self.closeSec=1678609499, self.tradeDate='20230312', self.openTime='162000', self.closeTime='162459',self.symbol='BTCUSDT',self.open=20372.4, self.close=20363.5, self.high=20383.7, self.low=20355.8   
2023-03-12 16:25:01,580:INFO:factorcheck2:main.py:127:handleKline:185239: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime    closeSec  ...      low       pct  index  idx
1632  20230312   160000    160459  1678608299  ...  20326.8  0.000816   1632    0
1633  20230312   160500    160959  1678608599  ...  20333.9 -0.000732   1633    1
1634  20230312   161000    161459  1678608899  ...  20337.2  0.001101   1634    2
1635  20230312   161500    161959  1678609199  ...  20349.2  0.000624   1635    3
1636  20230312   162000    162459  1678609499  ...  20355.8 -0.000437   1636    4

[5 rows x 11 columns]
2023-03-12 16:25:01,580:INFO:factorcheck2:main.py:128:handleKline:185239: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': True, 'isOpenSell': False, 'isCloseBuy': False, 'isCloseSell': False, 'isOpen': True, 'isClose': False, 'isTrig': True}


## /root/FIL/strategy/logic/log.txt ----- -----

2023-03-12 16:00:33,726:DEBUG:logic:main.py:463:getModel:885513: df_s.iloc[-5:,:] :
          date closeTime     open  ...    alpha58   alpha67   alpha72
5786  20230312    132959  20378.3  ...  43.750000  0.504866  0.315044
5787  20230312    135959  20386.1  ...  43.750000  0.497467  0.316060
5788  20230312    142959  20343.5  ...  44.166667  0.501527  0.314284
5789  20230312    145959  20366.6  ...  44.166667  0.493479  0.318016
5790  20230312    152959  20320.8  ...  44.583333  0.498541  0.318176

[5 rows x 33 columns]
0.5608856088560885
acc is : 0.5608856088560885
2023-03-12 16:00:33,886:INFO:logic:main.py:468:getModel:885513: df_pred.iloc[-5:,:] :
     pred    prob_0    prob_1  actual  ...       nav  sign  cost_        bm
537     0  0.503623  0.496377       0  ...  0.927295  -1.0    0.0  0.881041
538     1  0.476260  0.523740       1  ...  0.926238  -1.0    0.0  0.882046
539     0  0.509820  0.490180       0  ...  0.928325  -1.0    0.0  0.880058
540     1  0.473969  0.526031       1  ...  0.927032  -1.0    0.0  0.881283
541     0  0.509606  0.490394       0  ...  0.927647  -1.0    0.0  0.880699

[5 rows x 10 columns]
2023-03-12 16:00:33,913:INFO:logic:main.py:478:getModel:885513: df_panel.iloc[-5:,:] :
    pred    prob_0    prob_1  actual  ...       nav  sign  cost_        bm
45     0  0.503636  0.496364       0  ...  0.927295  -1.0    0.0  0.878780
46     1  0.476462  0.523538       1  ...  0.926238  -1.0    0.0  0.881004
47     0  0.509597  0.490403       0  ...  0.928325  -1.0    0.0  0.878563
48     1  0.473907  0.526093       1  ...  0.927032  -1.0    0.0  0.878703
49     0  0.509606  0.490394       0  ...  0.927647  -1.0    0.0  0.880699

[5 rows x 10 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '32.455', 'enterprice': '20374.9', 'countrevence': '0', 'unrealprofit': '1462.1093585044', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '20329.84964232', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}


## /root/FIL/strategy/modifiedmom/log.txt ----- -----

527  20230312   155000    155959  1678607999  20286.5  20335.6  0.002425
2023-03-12 16:00:02,155:INFO:modifiedmom:main.py:146:handleKline:185213: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': True, 'isOpenSell': False, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True}
127.0.0.1 - - [12/Mar/2023 16:10:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=15416 

self.closeSec=1678608599, self.tradeDate='20230312', self.openTime='160000', self.closeTime='160959', self.symbol='BTCUSDT', self.open='20335.6', self.close='20337.3'
2023-03-12 16:10:01,630:INFO:modifiedmom:main.py:144:handleKline:185213: self.closeSec=1678608599, self.tradeDate='20230312', self.openTime='160000', self.closeTime='160959',self.symbol='BTCUSDT',self.open='20335.6', self.close='20337.3'
2023-03-12 16:10:01,690:INFO:modifiedmom:main.py:145:handleKline:185213: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec     open    close       pct
524  20230312   152000    152959  1678606199  20346.9  20349.1  0.000113
525  20230312   153000    153959  1678606799    20349    20337 -0.000595
526  20230312   154000    154959  1678607399    20337  20286.4 -0.002488
527  20230312   155000    155959  1678607999  20286.5  20335.6  0.002425
528  20230312   160000    160959  1678608599  20335.6  20337.3  0.000084
2023-03-12 16:10:01,690:INFO:modifiedmom:main.py:146:handleKline:185213: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': True, 'isOpenSell': False, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True}

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=15417 

self.closeSec=1678609199, self.tradeDate='20230312', self.openTime='161000', self.closeTime='161959', self.symbol='BTCUSDT', self.open='20337.3', self.close='20372.4'
127.0.0.1 - - [12/Mar/2023 16:20:01] "POST / HTTP/1.1" 200 -
2023-03-12 16:20:02,042:INFO:modifiedmom:main.py:144:handleKline:185213: self.closeSec=1678609199, self.tradeDate='20230312', self.openTime='161000', self.closeTime='161959',self.symbol='BTCUSDT',self.open='20337.3', self.close='20372.4'
2023-03-12 16:20:02,351:INFO:modifiedmom:main.py:145:handleKline:185213: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec     open    close       pct
525  20230312   153000    153959  1678606799    20349    20337 -0.000595
526  20230312   154000    154959  1678607399    20337  20286.4 -0.002488
527  20230312   155000    155959  1678607999  20286.5  20335.6  0.002425
528  20230312   160000    160959  1678608599  20335.6  20337.3  0.000084
529  20230312   161000    161959  1678609199  20337.3  20372.4  0.001726
2023-03-12 16:20:02,351:INFO:modifiedmom:main.py:146:handleKline:185213: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': True, 'isOpenSell': False, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True}


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

17519  20230312   155000    155959  1678607999  20286.5  20335.6
2023-03-12 16:00:02,162:INFO:pyemd2:main.py:127:handleKline:185189: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=15417 

self.closeSec=1678608599, self.tradeDate='20230312', self.openTime='160000', self.closeTime='160959', self.symbol='BTCUSDT', self.open='20335.6', self.close='20337.3'
2023-03-12 16:10:01,612:INFO:pyemd2:main.py:125:handleKline:185189: self.closeSec=1678608599, self.tradeDate='20230312', self.openTime='160000', self.closeTime='160959',self.symbol='BTCUSDT',self.open='20335.6', self.close='20337.3'
127.0.0.1 - - [12/Mar/2023 16:10:01] "POST / HTTP/1.1" 200 -
2023-03-12 16:10:01,631:INFO:pyemd2:main.py:126:handleKline:185189: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
17516  20230312   152000    152959  1678606199  20346.9  20349.1
17517  20230312   153000    153959  1678606799    20349    20337
17518  20230312   154000    154959  1678607399    20337  20286.4
17519  20230312   155000    155959  1678607999  20286.5  20335.6
17520  20230312   160000    160959  1678608599  20335.6  20337.3
2023-03-12 16:10:01,633:INFO:pyemd2:main.py:127:handleKline:185189: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=15418 

self.closeSec=1678609199, self.tradeDate='20230312', self.openTime='161000', self.closeTime='161959', self.symbol='BTCUSDT', self.open='20337.3', self.close='20372.4'
127.0.0.1 - - [12/Mar/2023 16:20:01] "POST / HTTP/1.1" 200 -
2023-03-12 16:20:03,428:INFO:pyemd2:main.py:125:handleKline:185189: self.closeSec=1678609199, self.tradeDate='20230312', self.openTime='161000', self.closeTime='161959',self.symbol='BTCUSDT',self.open='20337.3', self.close='20372.4'
2023-03-12 16:20:03,473:INFO:pyemd2:main.py:126:handleKline:185189: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
17517  20230312   153000    153959  1678606799    20349    20337
17518  20230312   154000    154959  1678607399    20337  20286.4
17519  20230312   155000    155959  1678607999  20286.5  20335.6
17520  20230312   160000    160959  1678608599  20335.6  20337.3
17521  20230312   161000    161959  1678609199  20337.3  20372.4
2023-03-12 16:20:03,474:INFO:pyemd2:main.py:127:handleKline:185189: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}


## /root/FIL/strategy/similarity/log.txt ----- -----

12191  20230312   155000    155959  1678607999  20286.5  20335.6
2023-03-12 16:00:02,145:INFO:testStrategy:main.py:103:handleKline:185174: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': True, 'isOpenSell': False, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True, 'isCorr': False}
127.0.0.1 - - [12/Mar/2023 16:10:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=15417 

self.closeSec=1678608599, self.tradeDate='20230312', self.openTime='160000', self.closeTime='160959', self.symbol='BTCUSDT', self.open='20335.6', self.close='20337.3'
2023-03-12 16:10:01,619:INFO:testStrategy:main.py:101:handleKline:185174: self.closeSec=1678608599, self.tradeDate='20230312', self.openTime='160000', self.closeTime='160959',self.symbol='BTCUSDT',self.open='20335.6', self.close='20337.3'
2023-03-12 16:10:01,696:INFO:testStrategy:main.py:102:handleKline:185174: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
12188  20230312   152000    152959  1678606199  20346.9  20349.1
12189  20230312   153000    153959  1678606799    20349    20337
12190  20230312   154000    154959  1678607399    20337  20286.4
12191  20230312   155000    155959  1678607999  20286.5  20335.6
12192  20230312   160000    160959  1678608599  20335.6  20337.3
2023-03-12 16:10:01,697:INFO:testStrategy:main.py:103:handleKline:185174: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': True, 'isOpenSell': False, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True, 'isCorr': False}

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=15418 

self.closeSec=1678609199, self.tradeDate='20230312', self.openTime='161000', self.closeTime='161959', self.symbol='BTCUSDT', self.open='20337.3', self.close='20372.4'
127.0.0.1 - - [12/Mar/2023 16:20:01] "POST / HTTP/1.1" 200 -
2023-03-12 16:20:03,101:INFO:testStrategy:main.py:101:handleKline:185174: self.closeSec=1678609199, self.tradeDate='20230312', self.openTime='161000', self.closeTime='161959',self.symbol='BTCUSDT',self.open='20337.3', self.close='20372.4'
2023-03-12 16:20:03,351:INFO:testStrategy:main.py:102:handleKline:185174: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
12189  20230312   153000    153959  1678606799    20349    20337
12190  20230312   154000    154959  1678607399    20337  20286.4
12191  20230312   155000    155959  1678607999  20286.5  20335.6
12192  20230312   160000    160959  1678608599  20335.6  20337.3
12193  20230312   161000    161959  1678609199  20337.3  20372.4
2023-03-12 16:20:03,351:INFO:testStrategy:main.py:103:handleKline:185174: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': True, 'isOpenSell': False, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True, 'isCorr': False}


## /root/FIL/strategy/sr_min/log.txt ----- -----

--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=0, self.total=1000000.0, self.flagDict['side']='', self.tradeCount=0, self.count=26266
self.closeSec=1678609199, self.tradeDate='20230312', self.openTime='161500', self.closeTime='161959', self.symbol='BTCUSDT', self.open=20359.6, self.close=20372.4, self.high=20388.0, self.low=20349.2, self.vol=1644.942, self.amt=33507032.313 
127.0.0.1 - - [12/Mar/2023 16:20:01] "POST / HTTP/1.1" 200 -
2023-03-12 16:20:01,604:INFO:sr_min:main.py:172:handleKline:449472: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5951  20230312   155500    155959  ...         0.0        0.0       0
5952  20230312   160000    160459  ...         0.0        0.0       0
5953  20230312   160500    160959  ...         0.0        0.0       0
5954  20230312   161000    161459  ...         0.0        0.0       0
5955  20230312   161500    161959  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-03-12 16:20:01,606:INFO:sr_min:main.py:175:handleKline:449472: self.closeSec=1678609199, self.tradeDate='20230312', self.openTime='161500', self.closeTime='161959',self.symbol='BTCUSDT',self.open=20359.6, self.close=20372.4, self.high=20388.0, self.low=20349.2, self.vol=1644.942, self.amt=33507032.313, ukdf['pct'].iloc[-1]=0.000624 , ukdf['amount'].iloc[-1]=33507032.313, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5955, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': []}
type(curSign)=<class 'int'>, curSign=0, self.sign=0
--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=0, self.total=1000000.0, self.flagDict['side']='', self.tradeCount=0, self.count=26267
self.closeSec=1678609499, self.tradeDate='20230312', self.openTime='162000', self.closeTime='162459', self.symbol='BTCUSDT', self.open=20372.4, self.close=20363.5, self.high=20383.7, self.low=20355.8, self.vol=1051.948, self.amt=21427735.4763 
127.0.0.1 - - [12/Mar/2023 16:25:01] "POST / HTTP/1.1" 200 -
2023-03-12 16:25:01,552:INFO:sr_min:main.py:172:handleKline:449472: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5952  20230312   160000    160459  ...         0.0        0.0       0
5953  20230312   160500    160959  ...         0.0        0.0       0
5954  20230312   161000    161459  ...         0.0        0.0       0
5955  20230312   161500    161959  ...         0.0        0.0       0
5956  20230312   162000    162459  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-03-12 16:25:01,553:INFO:sr_min:main.py:175:handleKline:449472: self.closeSec=1678609499, self.tradeDate='20230312', self.openTime='162000', self.closeTime='162459',self.symbol='BTCUSDT',self.open=20372.4, self.close=20363.5, self.high=20383.7, self.low=20355.8, self.vol=1051.948, self.amt=21427735.4763, ukdf['pct'].iloc[-1]=-0.000437 , ukdf['amount'].iloc[-1]=21427735.4763, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5956, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': []}
type(curSign)=<class 'int'>, curSign=0, self.sign=0


## /root/FIL/strategy/s_rsrs/log.txt ----- -----

721  20230312   040000    075959  1678579199  ...    721  0.762446  0.673127     1.0
722  20230312   080000    115959  1678593599  ...    722  0.763955  0.680360     1.0

[5 rows x 15 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '55.825', 'enterprice': '20070', 'countrevence': '0', 'unrealprofit': '16702.84', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '20369.2', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'numpy.int64'>, curSign=1, self.sign=1
--handleKline--:  version='2.0.0', self.name='s_rsrs', self.symbol='BTCUSDT', interval='4h', intervalSec=14400, wid=25, thd=0.6, self.sign=1, self.total=1119287.34225, self.flagDict['side']='buy', self.tradeCount=24, self.count=642
self.closeSec=1678607999, self.tradeDate='20230312', self.openTime='120000', self.closeTime='155959', self.symbol='BTCUSDT', self.open=20367.7, self.close=20335.6, self.high=20429.7, self.low=20262.2, self.vol=39349.368, self.amt=800778847.814 
127.0.0.1 - - [12/Mar/2023 16:00:01] "POST / HTTP/1.1" 200 -
2023-03-12 16:00:01,952:INFO:s_rsrs:main.py:141:handleKline:185271: self.closeSec=1678607999, self.tradeDate='20230312', self.openTime='120000', self.closeTime='155959',self.symbol='BTCUSDT',self.open=20367.7, self.close=20335.6, self.high=20429.7, self.low=20262.2, self.vol=39349.368, self.amt=800778847.814 
2023-03-12 16:00:01,998:INFO:s_rsrs:main.py:142:handleKline:185271: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime  ...        vol           amt       pct
719  20230311   200000    235959  ...  70208.550  1.410859e+09 -0.001255
720  20230312   000000    035959  ...  96711.737  1.950538e+09  0.007864
721  20230312   040000    075959  ...  88653.535  1.804986e+09  0.011742
722  20230312   080000    115959  ...  69581.272  1.418949e+09 -0.003908
723  20230312   120000    155959  ...  39349.368  8.007788e+08 -0.001561

[5 rows x 11 columns]
2023-03-12 16:00:03,831:INFO:s_rsrs:main.py:151:handleKline:185271: df_s.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec  ...  index      beta    zscore  signal
719  20230311   200000    235959  1678550399  ...    719  0.778201  0.737284     1.0
720  20230312   000000    035959  1678564799  ...    720  0.766253  0.689669     1.0
721  20230312   040000    075959  1678579199  ...    721  0.762446  0.673127     1.0
722  20230312   080000    115959  1678593599  ...    722  0.763955  0.680360     1.0
723  20230312   120000    155959  1678607999  ...    723  0.772872  0.718523     1.0

[5 rows x 15 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '55.825', 'enterprice': '20070', 'countrevence': '0', 'unrealprofit': '14905.1900823595', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '20336.99847886', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'numpy.int64'>, curSign=1, self.sign=1


