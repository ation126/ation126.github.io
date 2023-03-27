# 20230327 16:26:01

## /root/FIL/strategy/amihud/log.txt ----- -----

--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=993672.4896432, self.flagDict['side']='sell', self.tradeCount=2, self.count=34588
self.closeSec=1679905199, self.tradeDate='20230327', self.openTime='161500', self.closeTime='161959', self.symbol='BTCUSDT', self.open=27781.6, self.close=27785.3, self.high=27785.4, self.low=27760.1, self.vol=705.547, self.amt=19593425.6862 
127.0.0.1 - - [27/Mar/2023 16:20:03] "POST / HTTP/1.1" 200 -
2023-03-27 16:20:08,889:INFO:amihud:main.py:172:handleKline:200676: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5951  20230327   155500    155959  ...         0.0        0.0       0
5952  20230327   160000    160459  ...         0.0        0.0       0
5953  20230327   160500    160959  ...         0.0        0.0       0
5954  20230327   161000    161459  ...         0.0        0.0       0
5955  20230327   161500    161959  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-03-27 16:20:08,900:INFO:amihud:main.py:175:handleKline:200676: self.closeSec=1679905199, self.tradeDate='20230327', self.openTime='161500', self.closeTime='161959',self.symbol='BTCUSDT',self.open=27781.6, self.close=27785.3, self.high=27785.4, self.low=27760.1, self.vol=705.547, self.amt=19593425.6862, ukdf['pct'].iloc[-1]=0.000133 , ukdf['amount'].iloc[-1]=19593425.6862, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5955, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '60.176', 'enterprice': '16529.3', 'countrevence': '0', 'unrealprofit': '-677611.848', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '27789.8', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1
--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=993672.4896432, self.flagDict['side']='sell', self.tradeCount=2, self.count=34589
self.closeSec=1679905499, self.tradeDate='20230327', self.openTime='162000', self.closeTime='162459', self.symbol='BTCUSDT', self.open=27785.4, self.close=27782.8, self.high=27792.5, self.low=27777.0, self.vol=455.529, self.amt=12656709.7463 
127.0.0.1 - - [27/Mar/2023 16:25:01] "POST / HTTP/1.1" 200 -
2023-03-27 16:25:01,564:INFO:amihud:main.py:172:handleKline:200676: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5952  20230327   160000    160459  ...         0.0        0.0       0
5953  20230327   160500    160959  ...         0.0        0.0       0
5954  20230327   161000    161459  ...         0.0        0.0       0
5955  20230327   161500    161959  ...         0.0        0.0       0
5956  20230327   162000    162459  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-03-27 16:25:01,564:INFO:amihud:main.py:175:handleKline:200676: self.closeSec=1679905499, self.tradeDate='20230327', self.openTime='162000', self.closeTime='162459',self.symbol='BTCUSDT',self.open=27785.4, self.close=27782.8, self.high=27792.5, self.low=27777.0, self.vol=455.529, self.amt=12656709.7463, ukdf['pct'].iloc[-1]=-9e-05 , ukdf['amount'].iloc[-1]=12656709.7463, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5956, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '60.176', 'enterprice': '16529.3', 'countrevence': '0', 'unrealprofit': '-677473.4432', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '27787.5', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1


## /root/FIL/strategy/factorcheck/log.txt ----- -----


self.closeSec=1679905199, self.tradeDate='20230327', self.openTime='161500', self.closeTime='161959', self.symbol='BTCUSDT', self.open=27781.6, self.close=27785.3, self.high=27785.4, self.low=27760.1 
127.0.0.1 - - [27/Mar/2023 16:20:02] "POST / HTTP/1.1" 200 -
2023-03-27 16:20:05,351:INFO:factorcheck2:main.py:126:handleKline:185239: self.closeSec=1679905199, self.tradeDate='20230327', self.openTime='161500', self.closeTime='161959',self.symbol='BTCUSDT',self.open=27781.6, self.close=27785.3, self.high=27785.4, self.low=27760.1   
2023-03-27 16:20:06,669:INFO:factorcheck2:main.py:127:handleKline:185239: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime    closeSec  ...      low       pct  index  idx
1631  20230327   155500    155959  1679903999  ...  27773.3  0.000742   1631    5
1632  20230327   160000    160459  1679904299  ...  27770.7 -0.000856   1632    0
1633  20230327   160500    160959  1679904599  ...  27768.4  0.001635   1633    1
1634  20230327   161000    161459  1679904899  ...  27776.0 -0.001240   1634    2
1635  20230327   161500    161959  1679905199  ...  27760.1  0.000133   1635    3

[5 rows x 11 columns]
2023-03-27 16:20:06,678:INFO:factorcheck2:main.py:128:handleKline:185239: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}
127.0.0.1 - - [27/Mar/2023 16:25:01] "POST / HTTP/1.1" 200 -

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=476, self.factor=0.4622208915769959, self.count=35155 

self.closeSec=1679905499, self.tradeDate='20230327', self.openTime='162000', self.closeTime='162459', self.symbol='BTCUSDT', self.open=27785.4, self.close=27782.8, self.high=27792.5, self.low=27777.0 
2023-03-27 16:25:01,504:INFO:factorcheck2:main.py:126:handleKline:185239: self.closeSec=1679905499, self.tradeDate='20230327', self.openTime='162000', self.closeTime='162459',self.symbol='BTCUSDT',self.open=27785.4, self.close=27782.8, self.high=27792.5, self.low=27777.0   
2023-03-27 16:25:01,541:INFO:factorcheck2:main.py:127:handleKline:185239: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime    closeSec  ...      low       pct  index  idx
1632  20230327   160000    160459  1679904299  ...  27770.7 -0.000856   1632    0
1633  20230327   160500    160959  1679904599  ...  27768.4  0.001635   1633    1
1634  20230327   161000    161459  1679904899  ...  27776.0 -0.001240   1634    2
1635  20230327   161500    161959  1679905199  ...  27760.1  0.000133   1635    3
1636  20230327   162000    162459  1679905499  ...  27777.0 -0.000090   1636    4

[5 rows x 11 columns]
2023-03-27 16:25:01,541:INFO:factorcheck2:main.py:128:handleKline:185239: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}


## /root/FIL/strategy/logic/log.txt ----- -----

2023-03-27 16:00:35,682:DEBUG:logic:main.py:463:getModel:885513: df_s.iloc[-5:,:] :
          date closeTime     open  ...    alpha58   alpha67   alpha72
5786  20230327    132959  27894.1  ...  50.000000  0.517581  0.415940
5787  20230327    135959  27838.2  ...  50.000000  0.495217  0.441841
5788  20230327    142959  27707.1  ...  50.416667  0.505330  0.459453
5789  20230327    145959  27765.9  ...  50.416667  0.506035  0.475432
5790  20230327    152959  27770.9  ...  50.416667  0.510344  0.487574

[5 rows x 33 columns]
0.5129151291512916
acc is : 0.5129151291512916
2023-03-27 16:00:35,852:INFO:logic:main.py:468:getModel:885513: df_pred.iloc[-5:,:] :
     pred    prob_0    prob_1  actual  ...       nav  sign  cost_        bm
537     0  0.510577  0.489423       0  ...  1.049205   1.0    0.0  1.144533
538     1  0.490345  0.509655       1  ...  1.051428   1.0    0.0  1.146958
539     0  0.531059  0.468941       1  ...  1.051583   1.0    0.0  1.147127
540     0  0.517338  0.482662       1  ...  1.052522   1.0    0.0  1.148152
541     0  0.526024  0.473976       0  ...  1.052511   1.0    0.0  1.148139

[5 rows x 10 columns]
2023-03-27 16:00:35,883:INFO:logic:main.py:478:getModel:885513: df_panel.iloc[-5:,:] :
    pred    prob_0    prob_1  actual  ...       nav  sign  cost_        bm
45     0  0.509773  0.490227       0  ...  1.026647   1.0    0.0  1.137280
46     1  0.489895  0.510105       1  ...  1.063083   1.0    0.0  1.139862
47     0  0.531023  0.468977       1  ...  1.051583   1.0    0.0  1.143363
48     0  0.516948  0.483052       1  ...  1.052522   1.0    0.0  1.141939
49     0  0.526024  0.473976       0  ...  1.052511   1.0    0.0  1.148139

[5 rows x 10 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': []}


## /root/FIL/strategy/modifiedmom/log.txt ----- -----

527  20230327   155000    155959  1679903999  27752.1  27794.5  0.001528
2023-03-27 16:00:02,131:INFO:modifiedmom:main.py:146:handleKline:185213: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': True, 'isOpenSell': False, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True}
127.0.0.1 - - [27/Mar/2023 16:10:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=17576 

self.closeSec=1679904599, self.tradeDate='20230327', self.openTime='160000', self.closeTime='160959', self.symbol='BTCUSDT', self.open='27794.5', self.close='27816.1'
2023-03-27 16:10:01,872:INFO:modifiedmom:main.py:144:handleKline:185213: self.closeSec=1679904599, self.tradeDate='20230327', self.openTime='160000', self.closeTime='160959',self.symbol='BTCUSDT',self.open='27794.5', self.close='27816.1'
2023-03-27 16:10:01,924:INFO:modifiedmom:main.py:145:handleKline:185213: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec     open    close       pct
524  20230327   152000    152959  1679902199  27842.2  27794.8 -0.001706
525  20230327   153000    153959  1679902799  27794.8  27803.6  0.000317
526  20230327   154000    154959  1679903399  27803.5  27752.1 -0.001852
527  20230327   155000    155959  1679903999  27752.1  27794.5  0.001528
528  20230327   160000    160959  1679904599  27794.5  27816.1  0.000777
2023-03-27 16:10:01,924:INFO:modifiedmom:main.py:146:handleKline:185213: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': True, 'isOpenSell': False, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True}

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=17577 

self.closeSec=1679905199, self.tradeDate='20230327', self.openTime='161000', self.closeTime='161959', self.symbol='BTCUSDT', self.open='27816.1', self.close='27785.3'
127.0.0.1 - - [27/Mar/2023 16:20:04] "POST / HTTP/1.1" 200 -
2023-03-27 16:20:07,349:INFO:modifiedmom:main.py:144:handleKline:185213: self.closeSec=1679905199, self.tradeDate='20230327', self.openTime='161000', self.closeTime='161959',self.symbol='BTCUSDT',self.open='27816.1', self.close='27785.3'
2023-03-27 16:20:08,339:INFO:modifiedmom:main.py:145:handleKline:185213: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec     open    close       pct
525  20230327   153000    153959  1679902799  27794.8  27803.6  0.000317
526  20230327   154000    154959  1679903399  27803.5  27752.1 -0.001852
527  20230327   155000    155959  1679903999  27752.1  27794.5  0.001528
528  20230327   160000    160959  1679904599  27794.5  27816.1  0.000777
529  20230327   161000    161959  1679905199  27816.1  27785.3 -0.001107
2023-03-27 16:20:08,348:INFO:modifiedmom:main.py:146:handleKline:185213: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': True, 'isOpenSell': False, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True}


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

17519  20230327   155000    155959  1679903999  27752.1  27794.5
2023-03-27 16:00:02,072:INFO:pyemd2:main.py:127:handleKline:185189: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=17577 

self.closeSec=1679904599, self.tradeDate='20230327', self.openTime='160000', self.closeTime='160959', self.symbol='BTCUSDT', self.open='27794.5', self.close='27816.1'
2023-03-27 16:10:01,878:INFO:pyemd2:main.py:125:handleKline:185189: self.closeSec=1679904599, self.tradeDate='20230327', self.openTime='160000', self.closeTime='160959',self.symbol='BTCUSDT',self.open='27794.5', self.close='27816.1'
127.0.0.1 - - [27/Mar/2023 16:10:01] "POST / HTTP/1.1" 200 -
2023-03-27 16:10:01,937:INFO:pyemd2:main.py:126:handleKline:185189: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
17516  20230327   152000    152959  1679902199  27842.2  27794.8
17517  20230327   153000    153959  1679902799  27794.8  27803.6
17518  20230327   154000    154959  1679903399  27803.5  27752.1
17519  20230327   155000    155959  1679903999  27752.1  27794.5
17520  20230327   160000    160959  1679904599  27794.5  27816.1
2023-03-27 16:10:01,937:INFO:pyemd2:main.py:127:handleKline:185189: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=17578 

self.closeSec=1679905199, self.tradeDate='20230327', self.openTime='161000', self.closeTime='161959', self.symbol='BTCUSDT', self.open='27816.1', self.close='27785.3'
127.0.0.1 - - [27/Mar/2023 16:20:04] "POST / HTTP/1.1" 200 -
2023-03-27 16:20:10,701:INFO:pyemd2:main.py:125:handleKline:185189: self.closeSec=1679905199, self.tradeDate='20230327', self.openTime='161000', self.closeTime='161959',self.symbol='BTCUSDT',self.open='27816.1', self.close='27785.3'
2023-03-27 16:20:10,848:INFO:pyemd2:main.py:126:handleKline:185189: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
17517  20230327   153000    153959  1679902799  27794.8  27803.6
17518  20230327   154000    154959  1679903399  27803.5  27752.1
17519  20230327   155000    155959  1679903999  27752.1  27794.5
17520  20230327   160000    160959  1679904599  27794.5  27816.1
17521  20230327   161000    161959  1679905199  27816.1  27785.3
2023-03-27 16:20:10,849:INFO:pyemd2:main.py:127:handleKline:185189: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}


## /root/FIL/strategy/similarity/log.txt ----- -----

12191  20230327   155000    155959  1679903999  27752.1  27794.5
2023-03-27 16:00:02,143:INFO:testStrategy:main.py:103:handleKline:185174: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': True, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True, 'isCorr': False}

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=17577 

self.closeSec=1679904599, self.tradeDate='20230327', self.openTime='160000', self.closeTime='160959', self.symbol='BTCUSDT', self.open='27794.5', self.close='27816.1'
2023-03-27 16:10:01,896:INFO:testStrategy:main.py:101:handleKline:185174: self.closeSec=1679904599, self.tradeDate='20230327', self.openTime='160000', self.closeTime='160959',self.symbol='BTCUSDT',self.open='27794.5', self.close='27816.1'
127.0.0.1 - - [27/Mar/2023 16:10:01] "POST / HTTP/1.1" 200 -
2023-03-27 16:10:01,938:INFO:testStrategy:main.py:102:handleKline:185174: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
12188  20230327   152000    152959  1679902199  27842.2  27794.8
12189  20230327   153000    153959  1679902799  27794.8  27803.6
12190  20230327   154000    154959  1679903399  27803.5  27752.1
12191  20230327   155000    155959  1679903999  27752.1  27794.5
12192  20230327   160000    160959  1679904599  27794.5  27816.1
2023-03-27 16:10:01,938:INFO:testStrategy:main.py:103:handleKline:185174: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': True, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True, 'isCorr': False}

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=17578 

self.closeSec=1679905199, self.tradeDate='20230327', self.openTime='161000', self.closeTime='161959', self.symbol='BTCUSDT', self.open='27816.1', self.close='27785.3'
127.0.0.1 - - [27/Mar/2023 16:20:04] "POST / HTTP/1.1" 200 -
2023-03-27 16:20:10,140:INFO:testStrategy:main.py:101:handleKline:185174: self.closeSec=1679905199, self.tradeDate='20230327', self.openTime='161000', self.closeTime='161959',self.symbol='BTCUSDT',self.open='27816.1', self.close='27785.3'
2023-03-27 16:20:10,481:INFO:testStrategy:main.py:102:handleKline:185174: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
12189  20230327   153000    153959  1679902799  27794.8  27803.6
12190  20230327   154000    154959  1679903399  27803.5  27752.1
12191  20230327   155000    155959  1679903999  27752.1  27794.5
12192  20230327   160000    160959  1679904599  27794.5  27816.1
12193  20230327   161000    161959  1679905199  27816.1  27785.3
2023-03-27 16:20:10,482:INFO:testStrategy:main.py:103:handleKline:185174: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': True, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True, 'isCorr': False}


## /root/FIL/strategy/sr_min/log.txt ----- -----

--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=0, self.total=1000000.0, self.flagDict['side']='', self.tradeCount=0, self.count=30586
self.closeSec=1679905199, self.tradeDate='20230327', self.openTime='161500', self.closeTime='161959', self.symbol='BTCUSDT', self.open=27781.6, self.close=27785.3, self.high=27785.4, self.low=27760.1, self.vol=705.547, self.amt=19593425.6862 
127.0.0.1 - - [27/Mar/2023 16:20:02] "POST / HTTP/1.1" 200 -
2023-03-27 16:20:07,249:INFO:sr_min:main.py:172:handleKline:449472: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5951  20230327   155500    155959  ...         0.0        0.0       0
5952  20230327   160000    160459  ...         0.0        0.0       0
5953  20230327   160500    160959  ...         0.0        0.0       0
5954  20230327   161000    161459  ...         0.0        0.0       0
5955  20230327   161500    161959  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-03-27 16:20:07,279:INFO:sr_min:main.py:175:handleKline:449472: self.closeSec=1679905199, self.tradeDate='20230327', self.openTime='161500', self.closeTime='161959',self.symbol='BTCUSDT',self.open=27781.6, self.close=27785.3, self.high=27785.4, self.low=27760.1, self.vol=705.547, self.amt=19593425.6862, ukdf['pct'].iloc[-1]=0.000133 , ukdf['amount'].iloc[-1]=19593425.6862, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5955, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': []}
type(curSign)=<class 'int'>, curSign=0, self.sign=0
127.0.0.1 - - [27/Mar/2023 16:25:01] "POST / HTTP/1.1" 200 -
--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=0, self.total=1000000.0, self.flagDict['side']='', self.tradeCount=0, self.count=30587
self.closeSec=1679905499, self.tradeDate='20230327', self.openTime='162000', self.closeTime='162459', self.symbol='BTCUSDT', self.open=27785.4, self.close=27782.8, self.high=27792.5, self.low=27777.0, self.vol=455.529, self.amt=12656709.7463 
2023-03-27 16:25:01,596:INFO:sr_min:main.py:172:handleKline:449472: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5952  20230327   160000    160459  ...         0.0        0.0       0
5953  20230327   160500    160959  ...         0.0        0.0       0
5954  20230327   161000    161459  ...         0.0        0.0       0
5955  20230327   161500    161959  ...         0.0        0.0       0
5956  20230327   162000    162459  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-03-27 16:25:01,598:INFO:sr_min:main.py:175:handleKline:449472: self.closeSec=1679905499, self.tradeDate='20230327', self.openTime='162000', self.closeTime='162459',self.symbol='BTCUSDT',self.open=27785.4, self.close=27782.8, self.high=27792.5, self.low=27777.0, self.vol=455.529, self.amt=12656709.7463, ukdf['pct'].iloc[-1]=-9e-05 , ukdf['amount'].iloc[-1]=12656709.7463, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5956, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': []}
type(curSign)=<class 'int'>, curSign=0, self.sign=0


## /root/FIL/strategy/s_rsrs/log.txt ----- -----

721  20230327   040000    075959  1679875199  ...    721  0.210632 -0.969475    -1.0
722  20230327   080000    115959  1679889599  ...    722  0.191668 -0.994625    -1.0

[5 rows x 15 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '53.706', 'enterprice': '28091.1', 'countrevence': '0', 'unrealprofit': '11421.55826380746', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '27878.43180159', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'numpy.int64'>, curSign=-1, self.sign=-1
--handleKline--:  version='2.0.0', self.name='s_rsrs', self.symbol='BTCUSDT', interval='4h', intervalSec=14400, wid=25, thd=0.6, self.sign=-1, self.total=1507151.9559834, self.flagDict['side']='sell', self.tradeCount=27, self.count=732
self.closeSec=1679903999, self.tradeDate='20230327', self.openTime='120000', self.closeTime='155959', self.symbol='BTCUSDT', self.open=27878.4, self.close=27794.5, self.high=27929.2, self.low=27650.0, self.vol=50007.614, self.amt=1389256323.59022 127.0.0.1 - - [27/Mar/2023 16:00:01] "POST / HTTP/1.1" 200 -

2023-03-27 16:00:01,953:INFO:s_rsrs:main.py:141:handleKline:185271: self.closeSec=1679903999, self.tradeDate='20230327', self.openTime='120000', self.closeTime='155959',self.symbol='BTCUSDT',self.open=27878.4, self.close=27794.5, self.high=27929.2, self.low=27650.0, self.vol=50007.614, self.amt=1389256323.59022 
2023-03-27 16:00:02,001:INFO:s_rsrs:main.py:142:handleKline:185271: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime  ...         vol           amt       pct
719  20230326   200000    235959  ...  146714.908  4.094086e+09 -0.002179
720  20230327   000000    035959  ...   49048.115  1.362723e+09  0.000817
721  20230327   040000    075959  ...   67164.517  1.875763e+09  0.005041
722  20230327   080000    115959  ...   44345.130  1.236390e+09 -0.002715
723  20230327   120000    155959  ...   50007.614  1.389256e+09 -0.003009

[5 rows x 11 columns]
2023-03-27 16:00:04,462:INFO:s_rsrs:main.py:151:handleKline:185271: df_s.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec  ...  index      beta    zscore  signal
719  20230326   200000    235959  1679846399  ...    719  0.036491 -1.443176    -1.0
720  20230327   000000    035959  1679860799  ...    720  0.013753 -1.460918    -1.0
721  20230327   040000    075959  1679875199  ...    721  0.210632 -0.969475    -1.0
722  20230327   080000    115959  1679889599  ...    722  0.191668 -0.994625    -1.0
723  20230327   120000    155959  1679903999  ...    723  0.136958 -1.101054    -1.0

[5 rows x 15 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '53.706', 'enterprice': '28091.1', 'countrevence': '0', 'unrealprofit': '15943.0896338007', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '27794.24136905', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'numpy.int64'>, curSign=-1, self.sign=-1


