# 20230408 16:26:02

## /root/FIL/strategy/amihud/log.txt ----- -----

--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=993672.4896432, self.flagDict['side']='sell', self.tradeCount=2, self.count=38044
self.closeSec=1680941999, self.tradeDate='20230408', self.openTime='161500', self.closeTime='161959', self.symbol='BTCUSDT', self.open=28079.9, self.close=28086.5, self.high=28107.7, self.low=28079.8, self.vol=1236.837, self.amt=34750567.4277 
127.0.0.1 - - [08/Apr/2023 16:20:04] "POST / HTTP/1.1" 200 -
2023-04-08 16:20:10,038:INFO:amihud:main.py:172:handleKline:200676: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5951  20230408   155500    155959  ...         0.0        0.0       0
5952  20230408   160000    160459  ...         0.0        0.0       0
5953  20230408   160500    160959  ...         0.0        0.0       0
5954  20230408   161000    161459  ...         0.0        0.0       0
5955  20230408   161500    161959  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-04-08 16:20:10,058:INFO:amihud:main.py:175:handleKline:200676: self.closeSec=1680941999, self.tradeDate='20230408', self.openTime='161500', self.closeTime='161959',self.symbol='BTCUSDT',self.open=28079.9, self.close=28086.5, self.high=28107.7, self.low=28079.8, self.vol=1236.837, self.amt=34750567.4277, ukdf['pct'].iloc[-1]=0.000235 , ukdf['amount'].iloc[-1]=34750567.4277, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5955, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '60.176', 'enterprice': '16529.3', 'countrevence': '0', 'unrealprofit': '-695432.63583166992', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '28085.94444017', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1
127.0.0.1 - - [08/Apr/2023 16:25:01] "POST / HTTP/1.1" 200 -
--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=993672.4896432, self.flagDict['side']='sell', self.tradeCount=2, self.count=38045
self.closeSec=1680942299, self.tradeDate='20230408', self.openTime='162000', self.closeTime='162459', self.symbol='BTCUSDT', self.open=28086.5, self.close=28086.9, self.high=28091.9, self.low=28084.8, self.vol=314.009, self.amt=8819897.9342 
2023-04-08 16:25:01,611:INFO:amihud:main.py:172:handleKline:200676: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5952  20230408   160000    160459  ...         0.0        0.0       0
5953  20230408   160500    160959  ...         0.0        0.0       0
5954  20230408   161000    161459  ...         0.0        0.0       0
5955  20230408   161500    161959  ...         0.0        0.0       0
5956  20230408   162000    162459  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-04-08 16:25:01,612:INFO:amihud:main.py:175:handleKline:200676: self.closeSec=1680942299, self.tradeDate='20230408', self.openTime='162000', self.closeTime='162459',self.symbol='BTCUSDT',self.open=28086.5, self.close=28086.9, self.high=28091.9, self.low=28084.8, self.vol=314.009, self.amt=8819897.9342, ukdf['pct'].iloc[-1]=1.4e-05 , ukdf['amount'].iloc[-1]=8819897.9342, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5956, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '60.176', 'enterprice': '16529.3', 'countrevence': '0', 'unrealprofit': '-695566.4878286408', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '28088.16878205', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1


## /root/FIL/strategy/factorcheck/log.txt ----- -----


self.closeSec=1680941999, self.tradeDate='20230408', self.openTime='161500', self.closeTime='161959', self.symbol='BTCUSDT', self.open=28079.9, self.close=28086.5, self.high=28107.7, self.low=28079.8 
127.0.0.1 - - [08/Apr/2023 16:20:04] "POST / HTTP/1.1" 200 -
2023-04-08 16:20:07,758:INFO:factorcheck2:main.py:126:handleKline:185239: self.closeSec=1680941999, self.tradeDate='20230408', self.openTime='161500', self.closeTime='161959',self.symbol='BTCUSDT',self.open=28079.9, self.close=28086.5, self.high=28107.7, self.low=28079.8   
2023-04-08 16:20:08,919:INFO:factorcheck2:main.py:127:handleKline:185239: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime    closeSec  ...      low       pct  index  idx
1631  20230408   155500    155959  1680940799  ...  28065.3  0.000299   1631    5
1632  20230408   160000    160459  1680941099  ...  28060.7 -0.000178   1632    0
1633  20230408   160500    160959  1680941399  ...  28064.4  0.000078   1633    1
1634  20230408   161000    161459  1680941699  ...  28070.9  0.000317   1634    2
1635  20230408   161500    161959  1680941999  ...  28079.8  0.000235   1635    3

[5 rows x 11 columns]
2023-04-08 16:20:08,927:INFO:factorcheck2:main.py:128:handleKline:185239: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=24, self.factor=0.46403472482283387, self.count=38611 

self.closeSec=1680942299, self.tradeDate='20230408', self.openTime='162000', self.closeTime='162459', self.symbol='BTCUSDT', self.open=28086.5, self.close=28086.9, self.high=28091.9, self.low=28084.8 
127.0.0.1 - - [08/Apr/2023 16:25:01] "POST / HTTP/1.1" 200 -
2023-04-08 16:25:01,517:INFO:factorcheck2:main.py:126:handleKline:185239: self.closeSec=1680942299, self.tradeDate='20230408', self.openTime='162000', self.closeTime='162459',self.symbol='BTCUSDT',self.open=28086.5, self.close=28086.9, self.high=28091.9, self.low=28084.8   
2023-04-08 16:25:01,591:INFO:factorcheck2:main.py:127:handleKline:185239: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime    closeSec  ...      low       pct  index  idx
1632  20230408   160000    160459  1680941099  ...  28060.7 -0.000178   1632    0
1633  20230408   160500    160959  1680941399  ...  28064.4  0.000078   1633    1
1634  20230408   161000    161459  1680941699  ...  28070.9  0.000317   1634    2
1635  20230408   161500    161959  1680941999  ...  28079.8  0.000235   1635    3
1636  20230408   162000    162459  1680942299  ...  28084.8  0.000014   1636    4

[5 rows x 11 columns]
2023-04-08 16:25:01,591:INFO:factorcheck2:main.py:128:handleKline:185239: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}


## /root/FIL/strategy/logic/log.txt ----- -----

2023-04-08 16:00:39,250:DEBUG:logic:main.py:463:getModel:885513: df_s.iloc[-5:,:] :
          date closeTime     open  ...    alpha58   alpha67   alpha72
5786  20230408    132959  27967.3  ...  47.500000  0.508058  0.438560
5787  20230408    135959  27995.7  ...  47.916667  0.542657  0.413141
5788  20230408    142959  28131.9  ...  47.500000  0.536970  0.392970
5789  20230408    145959  28112.0  ...  47.083333  0.533620  0.376230
5790  20230408    152959  28100.0  ...  46.666667  0.530045  0.362816

[5 rows x 33 columns]
0.5498154981549815
acc is : 0.5498154981549815
2023-04-08 16:00:39,428:INFO:logic:main.py:468:getModel:885513: df_pred.iloc[-5:,:] :
     pred    prob_0    prob_1  actual  ...       nav  sign  cost_        bm
537     0  0.526352  0.473648       1  ...  0.955786   1.0    0.0  1.043754
538     0  0.550154  0.449846       0  ...  0.955103   1.0    0.0  1.043009
539     0  0.518673  0.481327       0  ...  0.954702   1.0    0.0  1.042571
540     0  0.521339  0.478661       0  ...  0.954278   1.0    0.0  1.042107
541     0  0.521536  0.478464       0  ...  0.953809   1.0    0.0  1.041595

[5 rows x 10 columns]
2023-04-08 16:00:39,466:INFO:logic:main.py:478:getModel:885513: df_panel.iloc[-5:,:] :
    pred    prob_0    prob_1  actual  ...       nav  sign  cost_        bm
45     0  0.525951  0.474049       1  ...  0.955786   1.0    0.0  1.038660
46     0  0.549371  0.450629       0  ...  0.955103   1.0    0.0  1.036101
47     0  0.518271  0.481729       0  ...  0.954702   1.0    0.0  1.036441
48     0  0.521341  0.478659       0  ...  0.954278   1.0    0.0  1.037718
49     0  0.521536  0.478464       0  ...  0.953809   1.0    0.0  1.041595

[5 rows x 10 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': []}


## /root/FIL/strategy/modifiedmom/log.txt ----- -----

527  20230408   155000    155959  1680940799  28080.3  28073.8 -0.000235
2023-04-08 16:00:01,981:INFO:modifiedmom:main.py:146:handleKline:185213: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': True, 'isOpenSell': False, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True}
127.0.0.1 - - [08/Apr/2023 16:10:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=19304 

self.closeSec=1680941399, self.tradeDate='20230408', self.openTime='160000', self.closeTime='160959', self.symbol='BTCUSDT', self.open='28073.8', self.close='28071'
2023-04-08 16:10:01,580:INFO:modifiedmom:main.py:144:handleKline:185213: self.closeSec=1680941399, self.tradeDate='20230408', self.openTime='160000', self.closeTime='160959',self.symbol='BTCUSDT',self.open='28073.8', self.close='28071'
2023-04-08 16:10:01,606:INFO:modifiedmom:main.py:145:handleKline:185213: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec     open    close       pct
524  20230408   152000    152959  1680938999    28090  28087.6 -0.000089
525  20230408   153000    153959  1680939599  28087.6  28085.3 -0.000082
526  20230408   154000    154959  1680940199  28085.3  28080.4 -0.000174
527  20230408   155000    155959  1680940799  28080.3  28073.8 -0.000235
528  20230408   160000    160959  1680941399  28073.8    28071 -0.000100
2023-04-08 16:10:01,607:INFO:modifiedmom:main.py:146:handleKline:185213: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': True, 'isOpenSell': False, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True}

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=19305 

self.closeSec=1680941999, self.tradeDate='20230408', self.openTime='161000', self.closeTime='161959', self.symbol='BTCUSDT', self.open='28070.9', self.close='28086.5'
127.0.0.1 - - [08/Apr/2023 16:20:05] "POST / HTTP/1.1" 200 -
2023-04-08 16:20:08,568:INFO:modifiedmom:main.py:144:handleKline:185213: self.closeSec=1680941999, self.tradeDate='20230408', self.openTime='161000', self.closeTime='161959',self.symbol='BTCUSDT',self.open='28070.9', self.close='28086.5'
2023-04-08 16:20:09,438:INFO:modifiedmom:main.py:145:handleKline:185213: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec     open    close       pct
525  20230408   153000    153959  1680939599  28087.6  28085.3 -0.000082
526  20230408   154000    154959  1680940199  28085.3  28080.4 -0.000174
527  20230408   155000    155959  1680940799  28080.3  28073.8 -0.000235
528  20230408   160000    160959  1680941399  28073.8    28071 -0.000100
529  20230408   161000    161959  1680941999  28070.9  28086.5  0.000552
2023-04-08 16:20:09,438:INFO:modifiedmom:main.py:146:handleKline:185213: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': True, 'isOpenSell': False, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True}


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

17519  20230408   155000    155959  1680940799  28080.3  28073.8
2023-04-08 16:00:02,023:INFO:pyemd2:main.py:127:handleKline:185189: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}
127.0.0.1 - - [08/Apr/2023 16:10:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=19305 

self.closeSec=1680941399, self.tradeDate='20230408', self.openTime='160000', self.closeTime='160959', self.symbol='BTCUSDT', self.open='28073.8', self.close='28071'
2023-04-08 16:10:01,616:INFO:pyemd2:main.py:125:handleKline:185189: self.closeSec=1680941399, self.tradeDate='20230408', self.openTime='160000', self.closeTime='160959',self.symbol='BTCUSDT',self.open='28073.8', self.close='28071'
2023-04-08 16:10:01,646:INFO:pyemd2:main.py:126:handleKline:185189: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
17516  20230408   152000    152959  1680938999    28090  28087.6
17517  20230408   153000    153959  1680939599  28087.6  28085.3
17518  20230408   154000    154959  1680940199  28085.3  28080.4
17519  20230408   155000    155959  1680940799  28080.3  28073.8
17520  20230408   160000    160959  1680941399  28073.8    28071
2023-04-08 16:10:01,646:INFO:pyemd2:main.py:127:handleKline:185189: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=19306 

self.closeSec=1680941999, self.tradeDate='20230408', self.openTime='161000', self.closeTime='161959', self.symbol='BTCUSDT', self.open='28070.9', self.close='28086.5'
127.0.0.1 - - [08/Apr/2023 16:20:05] "POST / HTTP/1.1" 200 -
2023-04-08 16:20:11,900:INFO:pyemd2:main.py:125:handleKline:185189: self.closeSec=1680941999, self.tradeDate='20230408', self.openTime='161000', self.closeTime='161959',self.symbol='BTCUSDT',self.open='28070.9', self.close='28086.5'
2023-04-08 16:20:12,056:INFO:pyemd2:main.py:126:handleKline:185189: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
17517  20230408   153000    153959  1680939599  28087.6  28085.3
17518  20230408   154000    154959  1680940199  28085.3  28080.4
17519  20230408   155000    155959  1680940799  28080.3  28073.8
17520  20230408   160000    160959  1680941399  28073.8    28071
17521  20230408   161000    161959  1680941999  28070.9  28086.5
2023-04-08 16:20:12,057:INFO:pyemd2:main.py:127:handleKline:185189: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}


## /root/FIL/strategy/similarity/log.txt ----- -----

12191  20230408   155000    155959  1680940799  28080.3  28073.8
2023-04-08 16:00:01,996:INFO:testStrategy:main.py:103:handleKline:185174: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': True, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True, 'isCorr': False}

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=19305 

self.closeSec=1680941399, self.tradeDate='20230408', self.openTime='160000', self.closeTime='160959', self.symbol='BTCUSDT', self.open='28073.8', self.close='28071'
2023-04-08 16:10:01,596:INFO:testStrategy:main.py:101:handleKline:185174: self.closeSec=1680941399, self.tradeDate='20230408', self.openTime='160000', self.closeTime='160959',self.symbol='BTCUSDT',self.open='28073.8', self.close='28071'
127.0.0.1 - - [08/Apr/2023 16:10:01] "POST / HTTP/1.1" 200 -
2023-04-08 16:10:01,628:INFO:testStrategy:main.py:102:handleKline:185174: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
12188  20230408   152000    152959  1680938999    28090  28087.6
12189  20230408   153000    153959  1680939599  28087.6  28085.3
12190  20230408   154000    154959  1680940199  28085.3  28080.4
12191  20230408   155000    155959  1680940799  28080.3  28073.8
12192  20230408   160000    160959  1680941399  28073.8    28071
2023-04-08 16:10:01,629:INFO:testStrategy:main.py:103:handleKline:185174: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': True, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True, 'isCorr': False}

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=19306 

self.closeSec=1680941999, self.tradeDate='20230408', self.openTime='161000', self.closeTime='161959', self.symbol='BTCUSDT', self.open='28070.9', self.close='28086.5'
127.0.0.1 - - [08/Apr/2023 16:20:05] "POST / HTTP/1.1" 200 -
2023-04-08 16:20:11,400:INFO:testStrategy:main.py:101:handleKline:185174: self.closeSec=1680941999, self.tradeDate='20230408', self.openTime='161000', self.closeTime='161959',self.symbol='BTCUSDT',self.open='28070.9', self.close='28086.5'
2023-04-08 16:20:11,735:INFO:testStrategy:main.py:102:handleKline:185174: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
12189  20230408   153000    153959  1680939599  28087.6  28085.3
12190  20230408   154000    154959  1680940199  28085.3  28080.4
12191  20230408   155000    155959  1680940799  28080.3  28073.8
12192  20230408   160000    160959  1680941399  28073.8    28071
12193  20230408   161000    161959  1680941999  28070.9  28086.5
2023-04-08 16:20:11,736:INFO:testStrategy:main.py:103:handleKline:185174: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': True, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True, 'isCorr': False}


## /root/FIL/strategy/sr_min/log.txt ----- -----

--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=0, self.total=1000000.0, self.flagDict['side']='', self.tradeCount=0, self.count=34042
self.closeSec=1680941999, self.tradeDate='20230408', self.openTime='161500', self.closeTime='161959', self.symbol='BTCUSDT', self.open=28079.9, self.close=28086.5, self.high=28107.7, self.low=28079.8, self.vol=1236.837, self.amt=34750567.4277 
127.0.0.1 - - [08/Apr/2023 16:20:04] "POST / HTTP/1.1" 200 -
2023-04-08 16:20:09,497:INFO:sr_min:main.py:172:handleKline:449472: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5951  20230408   155500    155959  ...         0.0        0.0       0
5952  20230408   160000    160459  ...         0.0        0.0       0
5953  20230408   160500    160959  ...         0.0        0.0       0
5954  20230408   161000    161459  ...         0.0        0.0       0
5955  20230408   161500    161959  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-04-08 16:20:09,519:INFO:sr_min:main.py:175:handleKline:449472: self.closeSec=1680941999, self.tradeDate='20230408', self.openTime='161500', self.closeTime='161959',self.symbol='BTCUSDT',self.open=28079.9, self.close=28086.5, self.high=28107.7, self.low=28079.8, self.vol=1236.837, self.amt=34750567.4277, ukdf['pct'].iloc[-1]=0.000235 , ukdf['amount'].iloc[-1]=34750567.4277, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5955, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': []}
type(curSign)=<class 'int'>, curSign=0, self.sign=0
127.0.0.1 - - [08/Apr/2023 16:25:01] "POST / HTTP/1.1" 200 -
--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=0, self.total=1000000.0, self.flagDict['side']='', self.tradeCount=0, self.count=34043
self.closeSec=1680942299, self.tradeDate='20230408', self.openTime='162000', self.closeTime='162459', self.symbol='BTCUSDT', self.open=28086.5, self.close=28086.9, self.high=28091.9, self.low=28084.8, self.vol=314.009, self.amt=8819897.9342 
2023-04-08 16:25:01,624:INFO:sr_min:main.py:172:handleKline:449472: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5952  20230408   160000    160459  ...         0.0        0.0       0
5953  20230408   160500    160959  ...         0.0        0.0       0
5954  20230408   161000    161459  ...         0.0        0.0       0
5955  20230408   161500    161959  ...         0.0        0.0       0
5956  20230408   162000    162459  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-04-08 16:25:01,624:INFO:sr_min:main.py:175:handleKline:449472: self.closeSec=1680942299, self.tradeDate='20230408', self.openTime='162000', self.closeTime='162459',self.symbol='BTCUSDT',self.open=28086.5, self.close=28086.9, self.high=28091.9, self.low=28084.8, self.vol=314.009, self.amt=8819897.9342, ukdf['pct'].iloc[-1]=1.4e-05 , ukdf['amount'].iloc[-1]=8819897.9342, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5956, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': []}
type(curSign)=<class 'int'>, curSign=0, self.sign=0


## /root/FIL/strategy/s_rsrs/log.txt ----- -----

721  20230408   040000    075959  1680911999  ...    721  0.124757 -0.517900     NaN
722  20230408   080000    115959  1680926399  ...    722  0.297441  0.263230     NaN

[5 rows x 15 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '52.088', 'enterprice': '28398.8', 'countrevence': '0', 'unrealprofit': '20371.6168', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '28007.7', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'numpy.int64'>, curSign=-9223372036854775808, self.sign=-1
--handleKline--:  version='2.0.0', self.name='s_rsrs', self.symbol='BTCUSDT', interval='4h', intervalSec=14400, wid=25, thd=0.6, self.sign=-1, self.total=1477757.4577056, self.flagDict['side']='sell', self.tradeCount=29, self.count=804
self.closeSec=1680940799, self.tradeDate='20230408', self.openTime='120000', self.closeTime='155959', self.symbol='BTCUSDT', self.open=28005.9, self.close=28073.8, self.high=28153.6, self.low=27954.0, self.vol=38189.946, self.amt=1072168967.69424 
127.0.0.1 - - [08/Apr/2023 16:00:01] "POST / HTTP/1.1" 200 -
2023-04-08 16:00:01,827:INFO:s_rsrs:main.py:141:handleKline:185271: self.closeSec=1680940799, self.tradeDate='20230408', self.openTime='120000', self.closeTime='155959',self.symbol='BTCUSDT',self.open=28005.9, self.close=28073.8, self.high=28153.6, self.low=27954.0, self.vol=38189.946, self.amt=1072168967.69424 
2023-04-08 16:00:01,873:INFO:s_rsrs:main.py:142:handleKline:185271: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime  ...        vol           amt       pct
719  20230407   200000    235959  ...  58901.765  1.642831e+09  0.003629
720  20230408   000000    035959  ...  18629.237  5.195600e+08 -0.001568
721  20230408   040000    075959  ...  21815.597  6.086249e+08  0.000154
722  20230408   080000    115959  ...  26709.114  7.463568e+08  0.004130
723  20230408   120000    155959  ...  38189.946  1.072169e+09  0.002424

[5 rows x 11 columns]
2023-04-08 16:00:04,329:INFO:s_rsrs:main.py:151:handleKline:185271: df_s.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec  ...  index      beta    zscore  signal
719  20230407   200000    235959  1680883199  ...    719  0.126587 -0.494260     NaN
720  20230408   000000    035959  1680897599  ...    720  0.122962 -0.518480     NaN
721  20230408   040000    075959  1680911999  ...    721  0.124757 -0.517900     NaN
722  20230408   080000    115959  1680926399  ...    722  0.297441  0.263230     NaN
723  20230408   120000    155959  1680940799  ...    723  0.257239  0.065334     NaN

[5 rows x 15 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '52.088', 'enterprice': '28398.8', 'countrevence': '0', 'unrealprofit': '16738.98365304328', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '28077.44030769', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'numpy.int64'>, curSign=-9223372036854775808, self.sign=-1


