# 20230716 16:26:01

## /root/FIL/strategy/amihud/log.txt ----- -----

--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=373746.4768026, self.flagDict['side']='sell', self.tradeCount=2, self.count=18208
self.closeSec=1689495599, self.tradeDate='20230716', self.openTime='161500', self.closeTime='161959', self.symbol='BTCUSDT', self.open=30266.2, self.close=30270.5, self.high=30274.4, self.low=30265.5, self.vol=150.049, self.amt=4541749.2765 
127.0.0.1 - - [16/Jul/2023 16:20:01] "POST / HTTP/1.1" 200 -
2023-07-16 16:20:06,440:INFO:amihud:main.py:172:handleKline:2219019: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5951  20230716   155500    155959  ...         0.0        0.0       0
5952  20230716   160000    160459  ...         0.0        0.0       0
5953  20230716   160500    160959  ...         0.0        0.0       0
5954  20230716   161000    161459  ...         0.0        0.0       0
5955  20230716   161500    161959  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-07-16 16:20:06,461:INFO:amihud:main.py:175:handleKline:2219019: self.closeSec=1689495599, self.tradeDate='20230716', self.openTime='161500', self.closeTime='161959',self.symbol='BTCUSDT',self.open=30266.2, self.close=30270.5, self.high=30274.4, self.low=30265.5, self.vol=150.049, self.amt=4541749.2765, ukdf['pct'].iloc[-1]=0.000139 , ukdf['amount'].iloc[-1]=4541749.2765, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5955, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '13.926', 'enterprice': '26864.9', 'countrevence': '0', 'unrealprofit': '-47470.68976623402', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '30273.68139927', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1
127.0.0.1 - - [16/Jul/2023 16:25:00] "POST / HTTP/1.1" 200 -
--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=373746.4768026, self.flagDict['side']='sell', self.tradeCount=2, self.count=18209
self.closeSec=1689495899, self.tradeDate='20230716', self.openTime='162000', self.closeTime='162459', self.symbol='BTCUSDT', self.open=30270.6, self.close=30289.9, self.high=30290.0, self.low=30270.0, self.vol=271.772, self.amt=8228893.6823 
2023-07-16 16:25:00,821:INFO:amihud:main.py:172:handleKline:2219019: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5952  20230716   160000    160459  ...         0.0        0.0       0
5953  20230716   160500    160959  ...         0.0        0.0       0
5954  20230716   161000    161459  ...         0.0        0.0       0
5955  20230716   161500    161959  ...         0.0        0.0       0
5956  20230716   162000    162459  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-07-16 16:25:00,822:INFO:amihud:main.py:175:handleKline:2219019: self.closeSec=1689495899, self.tradeDate='20230716', self.openTime='162000', self.closeTime='162459',self.symbol='BTCUSDT',self.open=30270.6, self.close=30289.9, self.high=30290.0, self.low=30270.0, self.vol=271.772, self.amt=8228893.6823, ukdf['pct'].iloc[-1]=0.000641 , ukdf['amount'].iloc[-1]=8228893.6823, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5956, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '13.926', 'enterprice': '26864.9', 'countrevence': '0', 'unrealprofit': '-47696.55', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '30289.9', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1


## /root/FIL/strategy/factorcheck/log.txt ----- -----


self.closeSec=1689495599, self.tradeDate='20230716', self.openTime='161500', self.closeTime='161959', self.symbol='BTCUSDT', self.open=30266.2, self.close=30270.5, self.high=30274.4, self.low=30265.5 
127.0.0.1 - - [16/Jul/2023 16:20:01] "POST / HTTP/1.1" 200 -
2023-07-16 16:20:04,299:INFO:factorcheck2:main.py:126:handleKline:2218005: self.closeSec=1689495599, self.tradeDate='20230716', self.openTime='161500', self.closeTime='161959',self.symbol='BTCUSDT',self.open=30266.2, self.close=30270.5, self.high=30274.4, self.low=30265.5   
2023-07-16 16:20:05,569:INFO:factorcheck2:main.py:127:handleKline:2218005: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime    closeSec  ...      low       pct  index  idx
1631  20230716   155500    155959  1689494399  ...  30248.0 -0.000291   1631    5
1632  20230716   160000    160459  1689494699  ...  30250.0  0.000205   1632    0
1633  20230716   160500    160959  1689494999  ...  30253.3 -0.000106   1633    1
1634  20230716   161000    161459  1689495299  ...  30256.0  0.000340   1634    2
1635  20230716   161500    161959  1689495599  ...  30265.5  0.000139   1635    3

[5 rows x 11 columns]
2023-07-16 16:20:05,579:INFO:factorcheck2:main.py:128:handleKline:2218005: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': True, 'isOpenSell': False, 'isCloseBuy': False, 'isCloseSell': False, 'isOpen': True, 'isClose': False, 'isTrig': True}
127.0.0.1 - - [16/Jul/2023 16:25:00] "POST / HTTP/1.1" 200 -

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=4, self.factor=0.5807672283106217, self.count=18211 

self.closeSec=1689495899, self.tradeDate='20230716', self.openTime='162000', self.closeTime='162459', self.symbol='BTCUSDT', self.open=30270.6, self.close=30289.9, self.high=30290.0, self.low=30270.0 
2023-07-16 16:25:00,772:INFO:factorcheck2:main.py:126:handleKline:2218005: self.closeSec=1689495899, self.tradeDate='20230716', self.openTime='162000', self.closeTime='162459',self.symbol='BTCUSDT',self.open=30270.6, self.close=30289.9, self.high=30290.0, self.low=30270.0   
2023-07-16 16:25:00,783:INFO:factorcheck2:main.py:127:handleKline:2218005: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime    closeSec  ...      low       pct  index  idx
1632  20230716   160000    160459  1689494699  ...  30250.0  0.000205   1632    0
1633  20230716   160500    160959  1689494999  ...  30253.3 -0.000106   1633    1
1634  20230716   161000    161459  1689495299  ...  30256.0  0.000340   1634    2
1635  20230716   161500    161959  1689495599  ...  30265.5  0.000139   1635    3
1636  20230716   162000    162459  1689495899  ...  30270.0  0.000641   1636    4

[5 rows x 11 columns]
2023-07-16 16:25:00,783:INFO:factorcheck2:main.py:128:handleKline:2218005: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': True, 'isOpenSell': False, 'isCloseBuy': False, 'isCloseSell': False, 'isOpen': True, 'isClose': False, 'isTrig': True}


## /root/FIL/strategy/logic/log.txt ----- -----

2023-07-16 16:00:16,938:DEBUG:logic:main.py:463:getModel:2218526: df_s.iloc[-5:,:] :
          date closeTime     open  ...    alpha58   alpha67   alpha72
5786  20230716    132959  30143.6  ...  53.750000  0.439237  0.595843
5787  20230716    135959  30202.5  ...  54.166667  0.445810  0.585152
5788  20230716    142959  30225.0  ...  54.166667  0.451322  0.569547
5789  20230716    145959  30243.9  ...  54.166667  0.451646  0.554678
5790  20230716    152959  30245.0  ...  54.583333  0.458673  0.535506

[5 rows x 33 columns]
0.522140221402214
acc is : 0.522140221402214
2023-07-16 16:00:16,996:INFO:logic:main.py:468:getModel:2218526: df_pred.iloc[-5:,:] :
     pred    prob_0    prob_1  actual  ...       nav  sign  cost_        bm
537     0  0.525859  0.474141       1  ...  1.014016  -1.0    0.0  0.982879
538     0  0.523872  0.476128       1  ...  1.013381  -1.0    0.0  0.983493
539     0  0.526775  0.473225       1  ...  1.013345  -1.0    0.0  0.983529
540     0  0.523755  0.476245       1  ...  1.012551  -1.0    0.0  0.984300
541     0  0.532234  0.467766       0  ...  1.013076  -1.0    0.0  0.983789

[5 rows x 10 columns]
2023-07-16 16:00:17,007:INFO:logic:main.py:478:getModel:2218526: df_panel.iloc[-5:,:] :
    pred    prob_0    prob_1  actual  ...       nav  sign  cost_        bm
45     0  0.524760  0.475240       1  ...  1.014016  -1.0    0.0  0.981051
46     0  0.523651  0.476349       1  ...  1.013381  -1.0    0.0  0.981989
47     0  0.526539  0.473461       1  ...  1.013345  -1.0    0.0  0.983379
48     0  0.523295  0.476705       1  ...  1.012551  -1.0    0.0  0.982157
49     0  0.532234  0.467766       0  ...  1.013076  -1.0    0.0  0.983789

[5 rows x 10 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '24.355', 'enterprice': '30274.7', 'countrevence': '0', 'unrealprofit': '593.18748053725', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '30250.34411905', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}


## /root/FIL/strategy/modifiedmom/log.txt ----- -----

527  20230716   155000    155959  1689494399  30268.5    30253 -0.000512
2023-07-16 16:00:02,257:INFO:modifiedmom:main.py:146:handleKline:2218259: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': True, 'isOpenSell': False, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True}

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=9104 

self.closeSec=1689494999, self.tradeDate='20230716', self.openTime='160000', self.closeTime='160959', self.symbol='BTCUSDT', self.open='30253', self.close='30256'
2023-07-16 16:10:01,106:INFO:modifiedmom:main.py:144:handleKline:2218259: self.closeSec=1689494999, self.tradeDate='20230716', self.openTime='160000', self.closeTime='160959',self.symbol='BTCUSDT',self.open='30253', self.close='30256'
2023-07-16 16:10:01,125:INFO:modifiedmom:main.py:145:handleKline:2218259: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec     open    close       pct
524  20230716   152000    152959  1689492599  30273.1  30268.7 -0.000145
525  20230716   153000    153959  1689493199  30268.7  30250.2 -0.000611
526  20230716   154000    154959  1689493799  30250.1  30268.5  0.000605
527  20230716   155000    155959  1689494399  30268.5    30253 -0.000512
528  20230716   160000    160959  1689494999    30253    30256  0.000099
2023-07-16 16:10:01,125:INFO:modifiedmom:main.py:146:handleKline:2218259: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': True, 'isOpenSell': False, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True}
127.0.0.1 - - [16/Jul/2023 16:10:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=9105 

self.closeSec=1689495599, self.tradeDate='20230716', self.openTime='161000', self.closeTime='161959', self.symbol='BTCUSDT', self.open='30256', self.close='30270.5'
127.0.0.1 - - [16/Jul/2023 16:20:04] "POST / HTTP/1.1" 200 -
2023-07-16 16:20:07,221:INFO:modifiedmom:main.py:144:handleKline:2218259: self.closeSec=1689495599, self.tradeDate='20230716', self.openTime='161000', self.closeTime='161959',self.symbol='BTCUSDT',self.open='30256', self.close='30270.5'
2023-07-16 16:20:07,909:INFO:modifiedmom:main.py:145:handleKline:2218259: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec     open    close       pct
525  20230716   153000    153959  1689493199  30268.7  30250.2 -0.000611
526  20230716   154000    154959  1689493799  30250.1  30268.5  0.000605
527  20230716   155000    155959  1689494399  30268.5    30253 -0.000512
528  20230716   160000    160959  1689494999    30253    30256  0.000099
529  20230716   161000    161959  1689495599    30256  30270.5  0.000479
2023-07-16 16:20:07,910:INFO:modifiedmom:main.py:146:handleKline:2218259: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': True, 'isOpenSell': False, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True}


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

17519  20230716   155000    155959  1689494399  30268.5    30253
2023-07-16 16:00:02,258:INFO:pyemd2:main.py:127:handleKline:2217508: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=9107 

self.closeSec=1689494999, self.tradeDate='20230716', self.openTime='160000', self.closeTime='160959', self.symbol='BTCUSDT', self.open='30253', self.close='30256'
127.0.0.1 - - [16/Jul/2023 16:10:01] "POST / HTTP/1.1" 200 -
2023-07-16 16:10:01,116:INFO:pyemd2:main.py:125:handleKline:2217508: self.closeSec=1689494999, self.tradeDate='20230716', self.openTime='160000', self.closeTime='160959',self.symbol='BTCUSDT',self.open='30253', self.close='30256'
2023-07-16 16:10:01,125:INFO:pyemd2:main.py:126:handleKline:2217508: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
17516  20230716   152000    152959  1689492599  30273.1  30268.7
17517  20230716   153000    153959  1689493199  30268.7  30250.2
17518  20230716   154000    154959  1689493799  30250.1  30268.5
17519  20230716   155000    155959  1689494399  30268.5    30253
17520  20230716   160000    160959  1689494999    30253    30256
2023-07-16 16:10:01,126:INFO:pyemd2:main.py:127:handleKline:2217508: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=9108 

self.closeSec=1689495599, self.tradeDate='20230716', self.openTime='161000', self.closeTime='161959', self.symbol='BTCUSDT', self.open='30256', self.close='30270.5'
127.0.0.1 - - [16/Jul/2023 16:20:04] "POST / HTTP/1.1" 200 -
2023-07-16 16:20:08,852:INFO:pyemd2:main.py:125:handleKline:2217508: self.closeSec=1689495599, self.tradeDate='20230716', self.openTime='161000', self.closeTime='161959',self.symbol='BTCUSDT',self.open='30256', self.close='30270.5'
2023-07-16 16:20:09,094:INFO:pyemd2:main.py:126:handleKline:2217508: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
17517  20230716   153000    153959  1689493199  30268.7  30250.2
17518  20230716   154000    154959  1689493799  30250.1  30268.5
17519  20230716   155000    155959  1689494399  30268.5    30253
17520  20230716   160000    160959  1689494999    30253    30256
17521  20230716   161000    161959  1689495599    30256  30270.5
2023-07-16 16:20:09,095:INFO:pyemd2:main.py:127:handleKline:2217508: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}


## /root/FIL/strategy/similarity/log.txt ----- -----

12191  20230716   155000    155959  1689494399  30268.5    30253
2023-07-16 16:00:02,258:INFO:testStrategy:main.py:103:handleKline:2217133: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': True, 'isOpenSell': False, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True, 'isCorr': False}
127.0.0.1 - - [16/Jul/2023 16:10:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=9107 

self.closeSec=1689494999, self.tradeDate='20230716', self.openTime='160000', self.closeTime='160959', self.symbol='BTCUSDT', self.open='30253', self.close='30256'
2023-07-16 16:10:01,108:INFO:testStrategy:main.py:101:handleKline:2217133: self.closeSec=1689494999, self.tradeDate='20230716', self.openTime='160000', self.closeTime='160959',self.symbol='BTCUSDT',self.open='30253', self.close='30256'
2023-07-16 16:10:01,120:INFO:testStrategy:main.py:102:handleKline:2217133: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
12188  20230716   152000    152959  1689492599  30273.1  30268.7
12189  20230716   153000    153959  1689493199  30268.7  30250.2
12190  20230716   154000    154959  1689493799  30250.1  30268.5
12191  20230716   155000    155959  1689494399  30268.5    30253
12192  20230716   160000    160959  1689494999    30253    30256
2023-07-16 16:10:01,120:INFO:testStrategy:main.py:103:handleKline:2217133: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': True, 'isOpenSell': False, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True, 'isCorr': False}

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=9108 

self.closeSec=1689495599, self.tradeDate='20230716', self.openTime='161000', self.closeTime='161959', self.symbol='BTCUSDT', self.open='30256', self.close='30270.5'
127.0.0.1 - - [16/Jul/2023 16:20:04] "POST / HTTP/1.1" 200 -
2023-07-16 16:20:08,629:INFO:testStrategy:main.py:101:handleKline:2217133: self.closeSec=1689495599, self.tradeDate='20230716', self.openTime='161000', self.closeTime='161959',self.symbol='BTCUSDT',self.open='30256', self.close='30270.5'
2023-07-16 16:20:08,920:INFO:testStrategy:main.py:102:handleKline:2217133: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
12189  20230716   153000    153959  1689493199  30268.7  30250.2
12190  20230716   154000    154959  1689493799  30250.1  30268.5
12191  20230716   155000    155959  1689494399  30268.5    30253
12192  20230716   160000    160959  1689494999    30253    30256
12193  20230716   161000    161959  1689495599    30256  30270.5
2023-07-16 16:20:08,922:INFO:testStrategy:main.py:103:handleKline:2217133: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': True, 'isOpenSell': False, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True, 'isCorr': False}


## /root/FIL/strategy/sr_min/log.txt ----- -----

--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=1, self.total=996015.990996, self.flagDict['side']='buy', self.tradeCount=1, self.count=18208
self.closeSec=1689495599, self.tradeDate='20230716', self.openTime='161500', self.closeTime='161959', self.symbol='BTCUSDT', self.open=30266.2, self.close=30270.5, self.high=30274.4, self.low=30265.5, self.vol=150.049, self.amt=4541749.2765 
127.0.0.1 - - [16/Jul/2023 16:20:01] "POST / HTTP/1.1" 200 -
2023-07-16 16:20:06,389:INFO:sr_min:main.py:172:handleKline:2219263: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5951  20230716   155500    155959  ...         0.0        0.0       0
5952  20230716   160000    160459  ...         0.0        0.0       0
5953  20230716   160500    160959  ...         0.0        0.0       0
5954  20230716   161000    161459  ...         0.0        0.0       0
5955  20230716   161500    161959  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-07-16 16:20:06,420:INFO:sr_min:main.py:175:handleKline:2219263: self.closeSec=1689495599, self.tradeDate='20230716', self.openTime='161500', self.closeTime='161959',self.symbol='BTCUSDT',self.open=30266.2, self.close=30270.5, self.high=30274.4, self.low=30265.5, self.vol=150.049, self.amt=4541749.2765, ukdf['pct'].iloc[-1]=0.000139 , ukdf['amount'].iloc[-1]=4541749.2765, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5955, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '37.141', 'enterprice': '26844', 'countrevence': '0', 'unrealprofit': '127381.79685028707', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '30273.68139927', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=1
127.0.0.1 - - [16/Jul/2023 16:25:00] "POST / HTTP/1.1" 200 -
--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=1, self.total=996015.990996, self.flagDict['side']='buy', self.tradeCount=1, self.count=18209
self.closeSec=1689495899, self.tradeDate='20230716', self.openTime='162000', self.closeTime='162459', self.symbol='BTCUSDT', self.open=30270.6, self.close=30289.9, self.high=30290.0, self.low=30270.0, self.vol=271.772, self.amt=8228893.6823 
2023-07-16 16:25:00,794:INFO:sr_min:main.py:172:handleKline:2219263: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5952  20230716   160000    160459  ...         0.0        0.0       0
5953  20230716   160500    160959  ...         0.0        0.0       0
5954  20230716   161000    161459  ...         0.0        0.0       0
5955  20230716   161500    161959  ...         0.0        0.0       0
5956  20230716   162000    162459  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-07-16 16:25:00,795:INFO:sr_min:main.py:175:handleKline:2219263: self.closeSec=1689495899, self.tradeDate='20230716', self.openTime='162000', self.closeTime='162459',self.symbol='BTCUSDT',self.open=30270.6, self.close=30289.9, self.high=30290.0, self.low=30270.0, self.vol=271.772, self.amt=8228893.6823, ukdf['pct'].iloc[-1]=0.000641 , ukdf['amount'].iloc[-1]=8228893.6823, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5956, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '37.141', 'enterprice': '26844', 'countrevence': '0', 'unrealprofit': '127984.1719', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '30289.9', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=1


## /root/FIL/strategy/s_rsrs/log.txt ----- -----

721  20230716   040000    075959  1689465599  ...    721  0.585894  0.953976     1.0
722  20230716   080000    115959  1689479999  ...    722  0.619016  1.055122     1.0

[5 rows x 15 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '52.241', 'enterprice': '30511.1', 'countrevence': '0', 'unrealprofit': '-17675.73747016819', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '30172.75009341', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'numpy.int64'>, curSign=1, self.sign=1
--handleKline--:  version='2.0.0', self.name='s_rsrs', self.symbol='BTCUSDT', interval='4h', intervalSec=14400, wid=25, thd=0.6, self.sign=1, self.total=1592336.4447248997, self.flagDict['side']='buy', self.tradeCount=11, self.count=379127.0.0.1 - - [16/Jul/2023 16:00:01] "POST / HTTP/1.1" 200 -

self.closeSec=1689494399, self.tradeDate='20230716', self.openTime='120000', self.closeTime='155959', self.symbol='BTCUSDT', self.open=30174.1, self.close=30253.0, self.high=30300.9, self.low=30120.0, self.vol=20092.465, self.amt=606939163.8735 
2023-07-16 16:00:01,800:INFO:s_rsrs:main.py:141:handleKline:2218689: self.closeSec=1689494399, self.tradeDate='20230716', self.openTime='120000', self.closeTime='155959',self.symbol='BTCUSDT',self.open=30174.1, self.close=30253.0, self.high=30300.9, self.low=30120.0, self.vol=20092.465, self.amt=606939163.8735 
2023-07-16 16:00:01,834:INFO:s_rsrs:main.py:142:handleKline:2218689: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime  ...        vol           amt       pct
719  20230715   200000    235959  ...  19740.322  5.980437e+08 -0.000264
720  20230716   000000    035959  ...  16143.855  4.889786e+08  0.000634
721  20230716   040000    075959  ...  10464.590  3.168499e+08 -0.001099
722  20230716   080000    115959  ...  43029.584  1.299547e+09 -0.003379
723  20230716   120000    155959  ...  20092.465  6.069392e+08  0.002615

[5 rows x 11 columns]
2023-07-16 16:00:02,546:INFO:s_rsrs:main.py:151:handleKline:2218689: df_s.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec  ...  index      beta    zscore  signal
719  20230715   200000    235959  1689436799  ...    719  0.515319  0.731175     1.0
720  20230716   000000    035959  1689451199  ...    720  0.560820  0.881317     1.0
721  20230716   040000    075959  1689465599  ...    721  0.585894  0.953976     1.0
722  20230716   080000    115959  1689479999  ...    722  0.619016  1.055122     1.0
723  20230716   120000    155959  1689494399  ...    723  0.655815  1.167779     1.0

[5 rows x 15 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '52.241', 'enterprice': '30511.1', 'countrevence': '0', 'unrealprofit': '-13483.4021', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '30253', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'numpy.int64'>, curSign=1, self.sign=1


