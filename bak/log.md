# 20230405 16:26:01

## /root/FIL/strategy/amihud/log.txt ----- -----

--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=993672.4896432, self.flagDict['side']='sell', self.tradeCount=2, self.count=37180
self.closeSec=1680682799, self.tradeDate='20230405', self.openTime='161500', self.closeTime='161959', self.symbol='BTCUSDT', self.open=28452.0, self.close=28463.6, self.high=28468.3, self.low=28432.4, self.vol=1172.143, self.amt=33351694.8349 
127.0.0.1 - - [05/Apr/2023 16:20:04] "POST / HTTP/1.1" 200 -
2023-04-05 16:20:09,935:INFO:amihud:main.py:172:handleKline:200676: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5951  20230405   155500    155959  ...         0.0        0.0       0
5952  20230405   160000    160459  ...         0.0        0.0       0
5953  20230405   160500    160959  ...         0.0        0.0       0
5954  20230405   161000    161459  ...         0.0        0.0       0
5955  20230405   161500    161959  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-04-05 16:20:09,956:INFO:amihud:main.py:175:handleKline:200676: self.closeSec=1680682799, self.tradeDate='20230405', self.openTime='161500', self.closeTime='161959',self.symbol='BTCUSDT',self.open=28452.0, self.close=28463.6, self.high=28468.3, self.low=28432.4, self.vol=1172.143, self.amt=33351694.8349, ukdf['pct'].iloc[-1]=0.000464 , ukdf['amount'].iloc[-1]=33351694.8349, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5955, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '60.176', 'enterprice': '16529.3', 'countrevence': '0', 'unrealprofit': '-718184.21314206096', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '28464.02834921', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1
--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=993672.4896432, self.flagDict['side']='sell', self.tradeCount=2, self.count=37181
self.closeSec=1680683099, self.tradeDate='20230405', self.openTime='162000', self.closeTime='162459', self.symbol='BTCUSDT', self.open=28463.6, self.close=28551.7, self.high=28593.0, self.low=28463.5, self.vol=4294.497, self.amt=122604330.2614 
127.0.0.1 - - [05/Apr/2023 16:25:01] "POST / HTTP/1.1" 200 -
2023-04-05 16:25:01,639:INFO:amihud:main.py:172:handleKline:200676: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5952  20230405   160000    160459  ...         0.0        0.0       0
5953  20230405   160500    160959  ...         0.0        0.0       0
5954  20230405   161000    161459  ...         0.0        0.0       0
5955  20230405   161500    161959  ...         0.0        0.0       0
5956  20230405   162000    162459  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-04-05 16:25:01,641:INFO:amihud:main.py:175:handleKline:200676: self.closeSec=1680683099, self.tradeDate='20230405', self.openTime='162000', self.closeTime='162459',self.symbol='BTCUSDT',self.open=28463.6, self.close=28551.7, self.high=28593.0, self.low=28463.5, self.vol=4294.497, self.amt=122604330.2614, ukdf['pct'].iloc[-1]=0.003095 , ukdf['amount'].iloc[-1]=122604330.2614, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5956, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '60.176', 'enterprice': '16529.3', 'countrevence': '0', 'unrealprofit': '-723778.22186074336', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '28556.98914286', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1


## /root/FIL/strategy/factorcheck/log.txt ----- -----


self.closeSec=1680682799, self.tradeDate='20230405', self.openTime='161500', self.closeTime='161959', self.symbol='BTCUSDT', self.open=28452.0, self.close=28463.6, self.high=28468.3, self.low=28432.4 
127.0.0.1 - - [05/Apr/2023 16:20:04] "POST / HTTP/1.1" 200 -
2023-04-05 16:20:07,495:INFO:factorcheck2:main.py:126:handleKline:185239: self.closeSec=1680682799, self.tradeDate='20230405', self.openTime='161500', self.closeTime='161959',self.symbol='BTCUSDT',self.open=28452.0, self.close=28463.6, self.high=28468.3, self.low=28432.4   
2023-04-05 16:20:08,815:INFO:factorcheck2:main.py:127:handleKline:185239: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime    closeSec  ...      low       pct  index  idx
1631  20230405   155500    155959  1680681599  ...  28482.6  0.000748   1631    5
1632  20230405   160000    160459  1680681899  ...  28506.1 -0.000337   1632    0
1633  20230405   160500    160959  1680682199  ...  28460.6 -0.001407   1633    1
1634  20230405   161000    161459  1680682499  ...  28441.2 -0.000548   1634    2
1635  20230405   161500    161959  1680682799  ...  28432.4  0.000464   1635    3

[5 rows x 11 columns]
2023-04-05 16:20:08,815:INFO:factorcheck2:main.py:128:handleKline:185239: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}
127.0.0.1 - - [05/Apr/2023 16:25:01] "POST / HTTP/1.1" 200 -

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=41, self.factor=0.33530721133836433, self.count=37747 

self.closeSec=1680683099, self.tradeDate='20230405', self.openTime='162000', self.closeTime='162459', self.symbol='BTCUSDT', self.open=28463.6, self.close=28551.7, self.high=28593.0, self.low=28463.5 
2023-04-05 16:25:01,548:INFO:factorcheck2:main.py:126:handleKline:185239: self.closeSec=1680683099, self.tradeDate='20230405', self.openTime='162000', self.closeTime='162459',self.symbol='BTCUSDT',self.open=28463.6, self.close=28551.7, self.high=28593.0, self.low=28463.5   
2023-04-05 16:25:01,605:INFO:factorcheck2:main.py:127:handleKline:185239: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime    closeSec  ...      low       pct  index  idx
1632  20230405   160000    160459  1680681899  ...  28506.1 -0.000337   1632    0
1633  20230405   160500    160959  1680682199  ...  28460.6 -0.001407   1633    1
1634  20230405   161000    161459  1680682499  ...  28441.2 -0.000548   1634    2
1635  20230405   161500    161959  1680682799  ...  28432.4  0.000464   1635    3
1636  20230405   162000    162459  1680683099  ...  28463.5  0.003095   1636    4

[5 rows x 11 columns]
2023-04-05 16:25:01,605:INFO:factorcheck2:main.py:128:handleKline:185239: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}


## /root/FIL/strategy/logic/log.txt ----- -----

2023-04-05 16:00:35,042:DEBUG:logic:main.py:463:getModel:885513: df_s.iloc[-5:,:] :
          date closeTime     open  ...    alpha58   alpha67   alpha72
5786  20230405    132959  28496.1  ...  50.833333  0.560952  0.303765
5787  20230405    135959  28573.8  ...  50.833333  0.560591  0.301114
5788  20230405    142959  28571.6  ...  50.416667  0.555804  0.300767
5789  20230405    145959  28544.1  ...  50.000000  0.551607  0.302300
5790  20230405    152959  28520.0  ...  50.000000  0.544092  0.307062

[5 rows x 33 columns]
0.5553505535055351
acc is : 0.5553505535055351
2023-04-05 16:00:35,224:INFO:logic:main.py:468:getModel:885513: df_pred.iloc[-5:,:] :
     pred    prob_0    prob_1  actual  ...       nav  sign  cost_        bm
537     0  0.522481  0.477519       0  ...  0.973130   1.0    0.0  1.037537
538     0  0.515555  0.484445       0  ...  0.972190   1.0    0.0  1.036535
539     0  0.502169  0.497831       0  ...  0.971369   1.0    0.0  1.035660
540     0  0.501427  0.498573       0  ...  0.969898   1.0    0.0  1.034091
541     1  0.498983  0.501017       1  ...  0.971222   1.0    0.0  1.035504

[5 rows x 10 columns]
2023-04-05 16:00:35,247:INFO:logic:main.py:478:getModel:885513: df_panel.iloc[-5:,:] :
    pred    prob_0    prob_1  actual  ...       nav  sign  cost_        bm
45     0  0.523241  0.476759       0  ...  0.973130   1.0    0.0  1.047373
46     0  0.516221  0.483779       0  ...  0.972190   1.0    0.0  1.040112
47     0  0.502994  0.497006       0  ...  0.971369   1.0    0.0  1.039400
48     0  0.501815  0.498185       0  ...  0.969898   1.0    0.0  1.035983
49     1  0.498983  0.501017       1  ...  0.971222   1.0    0.0  1.035504

[5 rows x 10 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': []}


## /root/FIL/strategy/modifiedmom/log.txt ----- -----

527  20230405   155000    155959  1680681599  28510.1  28515.7  0.000200
2023-04-05 16:00:01,913:INFO:modifiedmom:main.py:146:handleKline:185213: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': True, 'isOpenSell': False, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True}

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=18872 

self.closeSec=1680682199, self.tradeDate='20230405', self.openTime='160000', self.closeTime='160959', self.symbol='BTCUSDT', self.open='28515.7', self.close='28466'
2023-04-05 16:10:01,579:INFO:modifiedmom:main.py:144:handleKline:185213: self.closeSec=1680682199, self.tradeDate='20230405', self.openTime='160000', self.closeTime='160959',self.symbol='BTCUSDT',self.open='28515.7', self.close='28466'
127.0.0.1 - - [05/Apr/2023 16:10:01] "POST / HTTP/1.1" 200 -
2023-04-05 16:10:01,613:INFO:modifiedmom:main.py:145:handleKline:185213: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec     open    close       pct
524  20230405   152000    152959  1680679799  28469.3  28476.8  0.000376
525  20230405   153000    153959  1680680399  28476.9  28492.3  0.000544
526  20230405   154000    154959  1680680999  28492.3    28510  0.000621
527  20230405   155000    155959  1680681599  28510.1  28515.7  0.000200
528  20230405   160000    160959  1680682199  28515.7    28466 -0.001743
2023-04-05 16:10:01,615:INFO:modifiedmom:main.py:146:handleKline:185213: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': True, 'isOpenSell': False, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True}

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=18873 

self.closeSec=1680682799, self.tradeDate='20230405', self.openTime='161000', self.closeTime='161959', self.symbol='BTCUSDT', self.open='28466', self.close='28463.6'
127.0.0.1 - - [05/Apr/2023 16:20:05] "POST / HTTP/1.1" 200 -
2023-04-05 16:20:08,364:INFO:modifiedmom:main.py:144:handleKline:185213: self.closeSec=1680682799, self.tradeDate='20230405', self.openTime='161000', self.closeTime='161959',self.symbol='BTCUSDT',self.open='28466', self.close='28463.6'
2023-04-05 16:20:09,275:INFO:modifiedmom:main.py:145:handleKline:185213: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec     open    close       pct
525  20230405   153000    153959  1680680399  28476.9  28492.3  0.000544
526  20230405   154000    154959  1680680999  28492.3    28510  0.000621
527  20230405   155000    155959  1680681599  28510.1  28515.7  0.000200
528  20230405   160000    160959  1680682199  28515.7    28466 -0.001743
529  20230405   161000    161959  1680682799    28466  28463.6 -0.000084
2023-04-05 16:20:09,275:INFO:modifiedmom:main.py:146:handleKline:185213: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': True, 'isOpenSell': False, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True}


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

17519  20230405   155000    155959  1680681599  28510.1  28515.7
2023-04-05 16:00:01,916:INFO:pyemd2:main.py:127:handleKline:185189: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}
127.0.0.1 - - [05/Apr/2023 16:10:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=18873 

self.closeSec=1680682199, self.tradeDate='20230405', self.openTime='160000', self.closeTime='160959', self.symbol='BTCUSDT', self.open='28515.7', self.close='28466'
2023-04-05 16:10:01,587:INFO:pyemd2:main.py:125:handleKline:185189: self.closeSec=1680682199, self.tradeDate='20230405', self.openTime='160000', self.closeTime='160959',self.symbol='BTCUSDT',self.open='28515.7', self.close='28466'
2023-04-05 16:10:01,633:INFO:pyemd2:main.py:126:handleKline:185189: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
17516  20230405   152000    152959  1680679799  28469.3  28476.8
17517  20230405   153000    153959  1680680399  28476.9  28492.3
17518  20230405   154000    154959  1680680999  28492.3    28510
17519  20230405   155000    155959  1680681599  28510.1  28515.7
17520  20230405   160000    160959  1680682199  28515.7    28466
2023-04-05 16:10:01,634:INFO:pyemd2:main.py:127:handleKline:185189: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=18874 

self.closeSec=1680682799, self.tradeDate='20230405', self.openTime='161000', self.closeTime='161959', self.symbol='BTCUSDT', self.open='28466', self.close='28463.6'
127.0.0.1 - - [05/Apr/2023 16:20:05] "POST / HTTP/1.1" 200 -
2023-04-05 16:20:11,496:INFO:pyemd2:main.py:125:handleKline:185189: self.closeSec=1680682799, self.tradeDate='20230405', self.openTime='161000', self.closeTime='161959',self.symbol='BTCUSDT',self.open='28466', self.close='28463.6'
2023-04-05 16:20:11,651:INFO:pyemd2:main.py:126:handleKline:185189: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
17517  20230405   153000    153959  1680680399  28476.9  28492.3
17518  20230405   154000    154959  1680680999  28492.3    28510
17519  20230405   155000    155959  1680681599  28510.1  28515.7
17520  20230405   160000    160959  1680682199  28515.7    28466
17521  20230405   161000    161959  1680682799    28466  28463.6
2023-04-05 16:20:11,651:INFO:pyemd2:main.py:127:handleKline:185189: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}


## /root/FIL/strategy/similarity/log.txt ----- -----

12191  20230405   155000    155959  1680681599  28510.1  28515.7
2023-04-05 16:00:01,917:INFO:testStrategy:main.py:103:handleKline:185174: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': True, 'isOpenSell': False, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True, 'isCorr': False}

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=18873 

self.closeSec=1680682199, self.tradeDate='20230405', self.openTime='160000', self.closeTime='160959', self.symbol='BTCUSDT', self.open='28515.7', self.close='28466'
2023-04-05 16:10:01,607:INFO:testStrategy:main.py:101:handleKline:185174: self.closeSec=1680682199, self.tradeDate='20230405', self.openTime='160000', self.closeTime='160959',self.symbol='BTCUSDT',self.open='28515.7', self.close='28466'
127.0.0.1 - - [05/Apr/2023 16:10:01] "POST / HTTP/1.1" 200 -
2023-04-05 16:10:01,638:INFO:testStrategy:main.py:102:handleKline:185174: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
12188  20230405   152000    152959  1680679799  28469.3  28476.8
12189  20230405   153000    153959  1680680399  28476.9  28492.3
12190  20230405   154000    154959  1680680999  28492.3    28510
12191  20230405   155000    155959  1680681599  28510.1  28515.7
12192  20230405   160000    160959  1680682199  28515.7    28466
2023-04-05 16:10:01,638:INFO:testStrategy:main.py:103:handleKline:185174: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': True, 'isOpenSell': False, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True, 'isCorr': False}

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=18874 

self.closeSec=1680682799, self.tradeDate='20230405', self.openTime='161000', self.closeTime='161959', self.symbol='BTCUSDT', self.open='28466', self.close='28463.6'
127.0.0.1 - - [05/Apr/2023 16:20:05] "POST / HTTP/1.1" 200 -
2023-04-05 16:20:10,917:INFO:testStrategy:main.py:101:handleKline:185174: self.closeSec=1680682799, self.tradeDate='20230405', self.openTime='161000', self.closeTime='161959',self.symbol='BTCUSDT',self.open='28466', self.close='28463.6'
2023-04-05 16:20:11,295:INFO:testStrategy:main.py:102:handleKline:185174: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
12189  20230405   153000    153959  1680680399  28476.9  28492.3
12190  20230405   154000    154959  1680680999  28492.3    28510
12191  20230405   155000    155959  1680681599  28510.1  28515.7
12192  20230405   160000    160959  1680682199  28515.7    28466
12193  20230405   161000    161959  1680682799    28466  28463.6
2023-04-05 16:20:11,296:INFO:testStrategy:main.py:103:handleKline:185174: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': True, 'isOpenSell': False, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True, 'isCorr': False}


## /root/FIL/strategy/sr_min/log.txt ----- -----

--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=0, self.total=1000000.0, self.flagDict['side']='', self.tradeCount=0, self.count=33178
self.closeSec=1680682799, self.tradeDate='20230405', self.openTime='161500', self.closeTime='161959', self.symbol='BTCUSDT', self.open=28452.0, self.close=28463.6, self.high=28468.3, self.low=28432.4, self.vol=1172.143, self.amt=33351694.8349 
127.0.0.1 - - [05/Apr/2023 16:20:04] "POST / HTTP/1.1" 200 -
2023-04-05 16:20:09,174:INFO:sr_min:main.py:172:handleKline:449472: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5951  20230405   155500    155959  ...         0.0        0.0       0
5952  20230405   160000    160459  ...         0.0        0.0       0
5953  20230405   160500    160959  ...         0.0        0.0       0
5954  20230405   161000    161459  ...         0.0        0.0       0
5955  20230405   161500    161959  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-04-05 16:20:09,195:INFO:sr_min:main.py:175:handleKline:449472: self.closeSec=1680682799, self.tradeDate='20230405', self.openTime='161500', self.closeTime='161959',self.symbol='BTCUSDT',self.open=28452.0, self.close=28463.6, self.high=28468.3, self.low=28432.4, self.vol=1172.143, self.amt=33351694.8349, ukdf['pct'].iloc[-1]=0.000464 , ukdf['amount'].iloc[-1]=33351694.8349, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5955, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': []}
type(curSign)=<class 'int'>, curSign=0, self.sign=0
127.0.0.1 - - [05/Apr/2023 16:25:01] "POST / HTTP/1.1" 200 -
--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=0, self.total=1000000.0, self.flagDict['side']='', self.tradeCount=0, self.count=33179
self.closeSec=1680683099, self.tradeDate='20230405', self.openTime='162000', self.closeTime='162459', self.symbol='BTCUSDT', self.open=28463.6, self.close=28551.7, self.high=28593.0, self.low=28463.5, self.vol=4294.497, self.amt=122604330.2614 
2023-04-05 16:25:01,646:INFO:sr_min:main.py:172:handleKline:449472: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5952  20230405   160000    160459  ...         0.0        0.0       0
5953  20230405   160500    160959  ...         0.0        0.0       0
5954  20230405   161000    161459  ...         0.0        0.0       0
5955  20230405   161500    161959  ...         0.0        0.0       0
5956  20230405   162000    162459  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-04-05 16:25:01,647:INFO:sr_min:main.py:175:handleKline:449472: self.closeSec=1680683099, self.tradeDate='20230405', self.openTime='162000', self.closeTime='162459',self.symbol='BTCUSDT',self.open=28463.6, self.close=28551.7, self.high=28593.0, self.low=28463.5, self.vol=4294.497, self.amt=122604330.2614, ukdf['pct'].iloc[-1]=0.003095 , ukdf['amount'].iloc[-1]=122604330.2614, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5956, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': []}
type(curSign)=<class 'int'>, curSign=0, self.sign=0


## /root/FIL/strategy/s_rsrs/log.txt ----- -----

721  20230405   040000    075959  1680652799  ...    721  0.225672 -0.217109     NaN
722  20230405   080000    115959  1680667199  ...    722  0.199048 -0.310848     NaN

[5 rows x 15 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '52.088', 'enterprice': '28398.8', 'countrevence': '0', 'unrealprofit': '-7531.9248', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '28543.4', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'numpy.int64'>, curSign=-9223372036854775808, self.sign=-1
--handleKline--: 127.0.0.1 - - [05/Apr/2023 16:00:01] "POST / HTTP/1.1" 200 -
 version='2.0.0', self.name='s_rsrs', self.symbol='BTCUSDT', interval='4h', intervalSec=14400, wid=25, thd=0.6, self.sign=-1, self.total=1477757.4577056, self.flagDict['side']='sell', self.tradeCount=29, self.count=786
self.closeSec=1680681599, self.tradeDate='20230405', self.openTime='120000', self.closeTime='155959', self.symbol='BTCUSDT', self.open=28536.1, self.close=28515.7, self.high=28615.0, self.low=28433.4, self.vol=38202.006, self.amt=1089691515.2192 
2023-04-05 16:00:01,795:INFO:s_rsrs:main.py:141:handleKline:185271: self.closeSec=1680681599, self.tradeDate='20230405', self.openTime='120000', self.closeTime='155959',self.symbol='BTCUSDT',self.open=28536.1, self.close=28515.7, self.high=28615.0, self.low=28433.4, self.vol=38202.006, self.amt=1089691515.2192 
2023-04-05 16:00:01,820:INFO:s_rsrs:main.py:142:handleKline:185271: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime  ...         vol           amt       pct
719  20230404   200000    235959  ...  113740.253  3.202796e+09 -0.009298
720  20230405   000000    035959  ...   56580.848  1.590656e+09  0.005690
721  20230405   040000    075959  ...   40576.232  1.143864e+09 -0.000564
722  20230405   080000    115959  ...  125905.052  3.592485e+09  0.013529
723  20230405   120000    155959  ...   38202.006  1.089692e+09 -0.000715

[5 rows x 11 columns]
2023-04-05 16:00:04,516:INFO:s_rsrs:main.py:151:handleKline:185271: df_s.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec  ...  index      beta    zscore  signal
719  20230404   200000    235959  1680623999  ...    719  0.185268 -0.417809     NaN
720  20230405   000000    035959  1680638399  ...    720  0.234090 -0.204340     NaN
721  20230405   040000    075959  1680652799  ...    721  0.225672 -0.217109     NaN
722  20230405   080000    115959  1680667199  ...    722  0.199048 -0.310848     NaN
723  20230405   120000    155959  1680681599  ...    723  0.171421 -0.410539     NaN

[5 rows x 15 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '52.088', 'enterprice': '28398.8', 'countrevence': '0', 'unrealprofit': '-6094.296', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '28515.8', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'numpy.int64'>, curSign=-9223372036854775808, self.sign=-1


