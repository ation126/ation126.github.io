# 20230406 16:26:02

## /root/FIL/strategy/amihud/log.txt ----- -----

--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=993672.4896432, self.flagDict['side']='sell', self.tradeCount=2, self.count=37468
self.closeSec=1680769199, self.tradeDate='20230406', self.openTime='161500', self.closeTime='161959', self.symbol='BTCUSDT', self.open=27928.6, self.close=27879.9, self.high=27930.1, self.low=27846.6, self.vol=2184.774, self.amt=60897912.8323 
127.0.0.1 - - [06/Apr/2023 16:20:04] "POST / HTTP/1.1" 200 -
2023-04-06 16:20:09,122:INFO:amihud:main.py:172:handleKline:200676: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5951  20230406   155500    155959  ...         0.0        0.0       0
5952  20230406   160000    160459  ...         0.0        0.0       0
5953  20230406   160500    160959  ...         0.0        0.0       0
5954  20230406   161000    161459  ...         0.0        0.0       0
5955  20230406   161500    161959  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-04-06 16:20:09,140:INFO:amihud:main.py:175:handleKline:200676: self.closeSec=1680769199, self.tradeDate='20230406', self.openTime='161500', self.closeTime='161959',self.symbol='BTCUSDT',self.open=27928.6, self.close=27879.9, self.high=27930.1, self.low=27846.6, self.vol=2184.774, self.amt=60897912.8323, ukdf['pct'].iloc[-1]=-0.00174 , ukdf['amount'].iloc[-1]=60897912.8323, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5955, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '60.176', 'enterprice': '16529.3', 'countrevence': '0', 'unrealprofit': '-683761.8352', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '27892', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1
127.0.0.1 - - [06/Apr/2023 16:25:01] "POST / HTTP/1.1" 200 -
--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=993672.4896432, self.flagDict['side']='sell', self.tradeCount=2, self.count=37469
self.closeSec=1680769499, self.tradeDate='20230406', self.openTime='162000', self.closeTime='162459', self.symbol='BTCUSDT', self.open=27879.9, self.close=27894.3, self.high=27899.1, self.low=27864.3, self.vol=1020.258, self.amt=28446898.02 
2023-04-06 16:25:01,592:INFO:amihud:main.py:172:handleKline:200676: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5952  20230406   160000    160459  ...         0.0        0.0       0
5953  20230406   160500    160959  ...         0.0        0.0       0
5954  20230406   161000    161459  ...         0.0        0.0       0
5955  20230406   161500    161959  ...         0.0        0.0       0
5956  20230406   162000    162459  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-04-06 16:25:01,592:INFO:amihud:main.py:175:handleKline:200676: self.closeSec=1680769499, self.tradeDate='20230406', self.openTime='162000', self.closeTime='162459',self.symbol='BTCUSDT',self.open=27879.9, self.close=27894.3, self.high=27899.1, self.low=27864.3, self.vol=1020.258, self.amt=28446898.02, ukdf['pct'].iloc[-1]=0.000517 , ukdf['amount'].iloc[-1]=28446898.02, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5956, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '60.176', 'enterprice': '16529.3', 'countrevence': '0', 'unrealprofit': '-683900.24', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '27894.3', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1


## /root/FIL/strategy/factorcheck/log.txt ----- -----


self.closeSec=1680769199, self.tradeDate='20230406', self.openTime='161500', self.closeTime='161959', self.symbol='BTCUSDT', self.open=27928.6, self.close=27879.9, self.high=27930.1, self.low=27846.6 
127.0.0.1 - - [06/Apr/2023 16:20:03] "POST / HTTP/1.1" 200 -
2023-04-06 16:20:06,651:INFO:factorcheck2:main.py:126:handleKline:185239: self.closeSec=1680769199, self.tradeDate='20230406', self.openTime='161500', self.closeTime='161959',self.symbol='BTCUSDT',self.open=27928.6, self.close=27879.9, self.high=27930.1, self.low=27846.6   
2023-04-06 16:20:07,801:INFO:factorcheck2:main.py:127:handleKline:185239: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime    closeSec  ...      low       pct  index  idx
1631  20230406   155500    155959  1680767999  ...  27889.0 -0.001475   1631    5
1632  20230406   160000    160459  1680768299  ...  27825.6 -0.000753   1632    0
1633  20230406   160500    160959  1680768599  ...  27852.0  0.001342   1633    1
1634  20230406   161000    161459  1680768899  ...  27891.9  0.000548   1634    2
1635  20230406   161500    161959  1680769199  ...  27846.6 -0.001740   1635    3

[5 rows x 11 columns]
2023-04-06 16:20:07,801:INFO:factorcheck2:main.py:128:handleKline:185239: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}
127.0.0.1 - - [06/Apr/2023 16:25:01] "POST / HTTP/1.1" 200 -

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=89, self.factor=0.5791439599778199, self.count=38035 

self.closeSec=1680769499, self.tradeDate='20230406', self.openTime='162000', self.closeTime='162459', self.symbol='BTCUSDT', self.open=27879.9, self.close=27894.3, self.high=27899.1, self.low=27864.3 
2023-04-06 16:25:01,498:INFO:factorcheck2:main.py:126:handleKline:185239: self.closeSec=1680769499, self.tradeDate='20230406', self.openTime='162000', self.closeTime='162459',self.symbol='BTCUSDT',self.open=27879.9, self.close=27894.3, self.high=27899.1, self.low=27864.3   
2023-04-06 16:25:01,525:INFO:factorcheck2:main.py:127:handleKline:185239: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime    closeSec  ...      low       pct  index  idx
1632  20230406   160000    160459  1680768299  ...  27825.6 -0.000753   1632    0
1633  20230406   160500    160959  1680768599  ...  27852.0  0.001342   1633    1
1634  20230406   161000    161459  1680768899  ...  27891.9  0.000548   1634    2
1635  20230406   161500    161959  1680769199  ...  27846.6 -0.001740   1635    3
1636  20230406   162000    162459  1680769499  ...  27864.3  0.000517   1636    4

[5 rows x 11 columns]
2023-04-06 16:25:01,525:INFO:factorcheck2:main.py:128:handleKline:185239: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}


## /root/FIL/strategy/logic/log.txt ----- -----

2023-04-06 16:00:33,301:DEBUG:logic:main.py:463:getModel:885513: df_s.iloc[-5:,:] :
          date closeTime     open  ...    alpha58   alpha67   alpha72
5786  20230406    132959  28055.1  ...  47.500000  0.477279  0.657044
5787  20230406    135959  28058.6  ...  47.083333  0.471082  0.662800
5788  20230406    142959  28023.0  ...  47.500000  0.471435  0.668047
5789  20230406    145959  28024.7  ...  47.500000  0.477134  0.670957
5790  20230406    152959  28053.6  ...  47.500000  0.471461  0.675847

[5 rows x 33 columns]
0.5424354243542435
acc is : 0.5424354243542435
2023-04-06 16:00:33,461:INFO:logic:main.py:468:getModel:885513: df_pred.iloc[-5:,:] :
     pred    prob_0    prob_1  actual  ...       nav  sign  cost_        bm
537     0  0.518841  0.481159       0  ...  0.948884   1.0    0.0  1.018304
538     0  0.506499  0.493501       1  ...  0.948945   1.0    0.0  1.018369
539     0  0.511486  0.488514       1  ...  0.949920   1.0    0.0  1.019416
540     0  0.526459  0.473541       0  ...  0.948854   1.0    0.0  1.018271
541     0  0.514133  0.485867       0  ...  0.944614   1.0    0.0  1.013721

[5 rows x 10 columns]
2023-04-06 16:00:33,503:INFO:logic:main.py:478:getModel:885513: df_panel.iloc[-5:,:] :
    pred    prob_0    prob_1  actual  ...       nav  sign  cost_        bm
45     0  0.519448  0.480552       0  ...  0.948884   1.0    0.0  1.021451
46     0  0.507645  0.492355       1  ...  0.948945   1.0    0.0  1.022113
47     0  0.511606  0.488394       1  ...  0.949920   1.0    0.0  1.022086
48     0  0.527576  0.472424       0  ...  0.948854   1.0    0.0  1.021694
49     0  0.514133  0.485867       0  ...  0.944614   1.0    0.0  1.013721

[5 rows x 10 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': []}


## /root/FIL/strategy/modifiedmom/log.txt ----- -----

527  20230406   155000    155959  1680767999  27920.7  27896.8 -0.000856
2023-04-06 16:00:02,042:INFO:modifiedmom:main.py:146:handleKline:185213: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': True, 'isOpenSell': False, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True}

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=19016 

self.closeSec=1680768599, self.tradeDate='20230406', self.openTime='160000', self.closeTime='160959', self.symbol='BTCUSDT', self.open='27896.7', self.close='27913.2'
2023-04-06 16:10:01,615:INFO:modifiedmom:main.py:144:handleKline:185213: self.closeSec=1680768599, self.tradeDate='20230406', self.openTime='160000', self.closeTime='160959',self.symbol='BTCUSDT',self.open='27896.7', self.close='27913.2'
127.0.0.1 - - [06/Apr/2023 16:10:01] "POST / HTTP/1.1" 200 -
2023-04-06 16:10:01,629:INFO:modifiedmom:main.py:145:handleKline:185213: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec     open    close       pct
524  20230406   152000    152959  1680766199  28023.1    28022 -0.000043
525  20230406   153000    153959  1680766799  28022.1  27994.6 -0.000978
526  20230406   154000    154959  1680767399  27994.6  27920.7 -0.002640
527  20230406   155000    155959  1680767999  27920.7  27896.8 -0.000856
528  20230406   160000    160959  1680768599  27896.7  27913.2  0.000588
2023-04-06 16:10:01,629:INFO:modifiedmom:main.py:146:handleKline:185213: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': True, 'isOpenSell': False, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True}

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=19017 

self.closeSec=1680769199, self.tradeDate='20230406', self.openTime='161000', self.closeTime='161959', self.symbol='BTCUSDT', self.open='27913.2', self.close='27879.9'
127.0.0.1 - - [06/Apr/2023 16:20:04] "POST / HTTP/1.1" 200 -
2023-04-06 16:20:07,761:INFO:modifiedmom:main.py:144:handleKline:185213: self.closeSec=1680769199, self.tradeDate='20230406', self.openTime='161000', self.closeTime='161959',self.symbol='BTCUSDT',self.open='27913.2', self.close='27879.9'
2023-04-06 16:20:08,600:INFO:modifiedmom:main.py:145:handleKline:185213: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec     open    close       pct
525  20230406   153000    153959  1680766799  28022.1  27994.6 -0.000978
526  20230406   154000    154959  1680767399  27994.6  27920.7 -0.002640
527  20230406   155000    155959  1680767999  27920.7  27896.8 -0.000856
528  20230406   160000    160959  1680768599  27896.7  27913.2  0.000588
529  20230406   161000    161959  1680769199  27913.2  27879.9 -0.001193
2023-04-06 16:20:08,600:INFO:modifiedmom:main.py:146:handleKline:185213: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': True, 'isOpenSell': False, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True}


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

17519  20230406   155000    155959  1680767999  27920.7  27896.8
2023-04-06 16:00:02,075:INFO:pyemd2:main.py:127:handleKline:185189: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=19017 

self.closeSec=1680768599, self.tradeDate='20230406', self.openTime='160000', self.closeTime='160959', self.symbol='BTCUSDT', self.open='27896.7', self.close='27913.2'
2023-04-06 16:10:01,606:INFO:pyemd2:main.py:125:handleKline:185189: self.closeSec=1680768599, self.tradeDate='20230406', self.openTime='160000', self.closeTime='160959',self.symbol='BTCUSDT',self.open='27896.7', self.close='27913.2'
127.0.0.1 - - [06/Apr/2023 16:10:01] "POST / HTTP/1.1" 200 -
2023-04-06 16:10:01,635:INFO:pyemd2:main.py:126:handleKline:185189: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
17516  20230406   152000    152959  1680766199  28023.1    28022
17517  20230406   153000    153959  1680766799  28022.1  27994.6
17518  20230406   154000    154959  1680767399  27994.6  27920.7
17519  20230406   155000    155959  1680767999  27920.7  27896.8
17520  20230406   160000    160959  1680768599  27896.7  27913.2
2023-04-06 16:10:01,635:INFO:pyemd2:main.py:127:handleKline:185189: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=19018 

self.closeSec=1680769199, self.tradeDate='20230406', self.openTime='161000', self.closeTime='161959', self.symbol='BTCUSDT', self.open='27913.2', self.close='27879.9'
127.0.0.1 - - [06/Apr/2023 16:20:05] "POST / HTTP/1.1" 200 -
2023-04-06 16:20:10,718:INFO:pyemd2:main.py:125:handleKline:185189: self.closeSec=1680769199, self.tradeDate='20230406', self.openTime='161000', self.closeTime='161959',self.symbol='BTCUSDT',self.open='27913.2', self.close='27879.9'
2023-04-06 16:20:10,869:INFO:pyemd2:main.py:126:handleKline:185189: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
17517  20230406   153000    153959  1680766799  28022.1  27994.6
17518  20230406   154000    154959  1680767399  27994.6  27920.7
17519  20230406   155000    155959  1680767999  27920.7  27896.8
17520  20230406   160000    160959  1680768599  27896.7  27913.2
17521  20230406   161000    161959  1680769199  27913.2  27879.9
2023-04-06 16:20:10,870:INFO:pyemd2:main.py:127:handleKline:185189: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}


## /root/FIL/strategy/similarity/log.txt ----- -----

12191  20230406   155000    155959  1680767999  27920.7  27896.8
2023-04-06 16:00:02,062:INFO:testStrategy:main.py:103:handleKline:185174: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': True, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True, 'isCorr': False}

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=19017 

self.closeSec=1680768599, self.tradeDate='20230406', self.openTime='160000', self.closeTime='160959', self.symbol='BTCUSDT', self.open='27896.7', self.close='27913.2'
2023-04-06 16:10:01,593:INFO:testStrategy:main.py:101:handleKline:185174: self.closeSec=1680768599, self.tradeDate='20230406', self.openTime='160000', self.closeTime='160959',self.symbol='BTCUSDT',self.open='27896.7', self.close='27913.2'
127.0.0.1 - - [06/Apr/2023 16:10:01] "POST / HTTP/1.1" 200 -
2023-04-06 16:10:01,630:INFO:testStrategy:main.py:102:handleKline:185174: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
12188  20230406   152000    152959  1680766199  28023.1    28022
12189  20230406   153000    153959  1680766799  28022.1  27994.6
12190  20230406   154000    154959  1680767399  27994.6  27920.7
12191  20230406   155000    155959  1680767999  27920.7  27896.8
12192  20230406   160000    160959  1680768599  27896.7  27913.2
2023-04-06 16:10:01,630:INFO:testStrategy:main.py:103:handleKline:185174: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': True, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True, 'isCorr': False}

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=19018 

self.closeSec=1680769199, self.tradeDate='20230406', self.openTime='161000', self.closeTime='161959', self.symbol='BTCUSDT', self.open='27913.2', self.close='27879.9'
127.0.0.1 - - [06/Apr/2023 16:20:05] "POST / HTTP/1.1" 200 -
2023-04-06 16:20:10,199:INFO:testStrategy:main.py:101:handleKline:185174: self.closeSec=1680769199, self.tradeDate='20230406', self.openTime='161000', self.closeTime='161959',self.symbol='BTCUSDT',self.open='27913.2', self.close='27879.9'
2023-04-06 16:20:10,510:INFO:testStrategy:main.py:102:handleKline:185174: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
12189  20230406   153000    153959  1680766799  28022.1  27994.6
12190  20230406   154000    154959  1680767399  27994.6  27920.7
12191  20230406   155000    155959  1680767999  27920.7  27896.8
12192  20230406   160000    160959  1680768599  27896.7  27913.2
12193  20230406   161000    161959  1680769199  27913.2  27879.9
2023-04-06 16:20:10,510:INFO:testStrategy:main.py:103:handleKline:185174: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': True, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True, 'isCorr': False}


## /root/FIL/strategy/sr_min/log.txt ----- -----

--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=0, self.total=1000000.0, self.flagDict['side']='', self.tradeCount=0, self.count=33466
self.closeSec=1680769199, self.tradeDate='20230406', self.openTime='161500', self.closeTime='161959', self.symbol='BTCUSDT', self.open=27928.6, self.close=27879.9, self.high=27930.1, self.low=27846.6, self.vol=2184.774, self.amt=60897912.8323 
127.0.0.1 - - [06/Apr/2023 16:20:02] "POST / HTTP/1.1" 200 -
2023-04-06 16:20:07,580:INFO:sr_min:main.py:172:handleKline:449472: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5951  20230406   155500    155959  ...         0.0        0.0       0
5952  20230406   160000    160459  ...         0.0        0.0       0
5953  20230406   160500    160959  ...         0.0        0.0       0
5954  20230406   161000    161459  ...         0.0        0.0       0
5955  20230406   161500    161959  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-04-06 16:20:07,621:INFO:sr_min:main.py:175:handleKline:449472: self.closeSec=1680769199, self.tradeDate='20230406', self.openTime='161500', self.closeTime='161959',self.symbol='BTCUSDT',self.open=27928.6, self.close=27879.9, self.high=27930.1, self.low=27846.6, self.vol=2184.774, self.amt=60897912.8323, ukdf['pct'].iloc[-1]=-0.00174 , ukdf['amount'].iloc[-1]=60897912.8323, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5955, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': []}
type(curSign)=<class 'int'>, curSign=0, self.sign=0
127.0.0.1 - - [06/Apr/2023 16:25:01] "POST / HTTP/1.1" 200 -
--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=0, self.total=1000000.0, self.flagDict['side']='', self.tradeCount=0, self.count=33467
self.closeSec=1680769499, self.tradeDate='20230406', self.openTime='162000', self.closeTime='162459', self.symbol='BTCUSDT', self.open=27879.9, self.close=27894.3, self.high=27899.1, self.low=27864.3, self.vol=1020.258, self.amt=28446898.02 
2023-04-06 16:25:01,594:INFO:sr_min:main.py:172:handleKline:449472: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5952  20230406   160000    160459  ...         0.0        0.0       0
5953  20230406   160500    160959  ...         0.0        0.0       0
5954  20230406   161000    161459  ...         0.0        0.0       0
5955  20230406   161500    161959  ...         0.0        0.0       0
5956  20230406   162000    162459  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-04-06 16:25:01,595:INFO:sr_min:main.py:175:handleKline:449472: self.closeSec=1680769499, self.tradeDate='20230406', self.openTime='162000', self.closeTime='162459',self.symbol='BTCUSDT',self.open=27879.9, self.close=27894.3, self.high=27899.1, self.low=27864.3, self.vol=1020.258, self.amt=28446898.02, ukdf['pct'].iloc[-1]=0.000517 , ukdf['amount'].iloc[-1]=28446898.02, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5956, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': []}
type(curSign)=<class 'int'>, curSign=0, self.sign=0


## /root/FIL/strategy/s_rsrs/log.txt ----- -----

721  20230406   040000    075959  1680739199  ...    721  0.117422 -0.580183     NaN
722  20230406   080000    115959  1680753599  ...    722  0.112667 -0.584620     NaN

[5 rows x 15 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '52.088', 'enterprice': '28398.8', 'countrevence': '0', 'unrealprofit': '14655.09077432384', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '28117.44746632', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'numpy.int64'>, curSign=-9223372036854775808, self.sign=-1
--handleKline--:  version='2.0.0', self.name='s_rsrs', self.symbol='BTCUSDT', interval='4h', intervalSec=14400, wid=25, thd=0.6, self.sign=-1, self.total=1477757.4577056, self.flagDict['side']='sell', self.tradeCount=29, self.count=792127.0.0.1 - - [06/Apr/2023 16:00:01] "POST / HTTP/1.1" 200 -

self.closeSec=1680767999, self.tradeDate='20230406', self.openTime='120000', self.closeTime='155959', self.symbol='BTCUSDT', self.open=28117.4, self.close=27896.8, self.high=28117.5, self.low=27889.0, self.vol=36721.731, self.amt=1028840854.89638 
2023-04-06 16:00:01,803:INFO:s_rsrs:main.py:141:handleKline:185271: self.closeSec=1680767999, self.tradeDate='20230406', self.openTime='120000', self.closeTime='155959',self.symbol='BTCUSDT',self.open=28117.4, self.close=27896.8, self.high=28117.5, self.low=27889.0, self.vol=36721.731, self.amt=1028840854.89638 
2023-04-06 16:00:01,854:INFO:s_rsrs:main.py:142:handleKline:185271: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime  ...         vol           amt       pct
719  20230405   200000    235959  ...  208759.520  5.901306e+09 -0.018536
720  20230406   000000    035959  ...   99424.748  2.786311e+09  0.007646
721  20230406   040000    075959  ...   34158.218  9.625166e+08 -0.002660
722  20230406   080000    115959  ...   57949.765  1.623781e+09 -0.001300
723  20230406   120000    155959  ...   36721.731  1.028841e+09 -0.007846

[5 rows x 11 columns]
2023-04-06 16:00:04,893:INFO:s_rsrs:main.py:151:handleKline:185271: df_s.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec  ...  index      beta    zscore  signal
719  20230405   200000    235959  1680710399  ...    719  0.119619 -0.602008    -1.0
720  20230406   000000    035959  1680724799  ...    720  0.120090 -0.583035     NaN
721  20230406   040000    075959  1680739199  ...    721  0.117422 -0.580183     NaN
722  20230406   080000    115959  1680753599  ...    722  0.112667 -0.584620     NaN
723  20230406   120000    155959  1680767999  ...    723  0.109884 -0.581008     NaN

[5 rows x 15 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '52.088', 'enterprice': '28398.8', 'countrevence': '0', 'unrealprofit': '26075.57111549768', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '27898.19388889', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'numpy.int64'>, curSign=-9223372036854775808, self.sign=-1


