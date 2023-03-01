# 20230301 16:26:02

## /root/FIL/strategy/amihud/log.txt ----- -----

--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=993672.4896432, self.flagDict['side']='sell', self.tradeCount=2, self.count=27100
self.closeSec=1677658799, self.tradeDate='20230301', self.openTime='161500', self.closeTime='161959', self.symbol='BTCUSDT', self.open=23766.1, self.close=23762.2, self.high=23778.6, self.low=23735.9, self.vol=1545.56, self.amt=36725506.4801 
127.0.0.1 - - [01/Mar/2023 16:20:03] "POST / HTTP/1.1" 200 -
2023-03-01 16:20:09,332:INFO:amihud:main.py:172:handleKline:200676: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5951  20230301   155500    155959  ...         0.0        0.0       0
5952  20230301   160000    160459  ...         0.0        0.0       0
5953  20230301   160500    160959  ...         0.0        0.0       0
5954  20230301   161000    161459  ...         0.0        0.0       0
5955  20230301   161500    161959  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-03-01 16:20:09,343:INFO:amihud:main.py:175:handleKline:200676: self.closeSec=1677658799, self.tradeDate='20230301', self.openTime='161500', self.closeTime='161959',self.symbol='BTCUSDT',self.open=23766.1, self.close=23762.2, self.high=23778.6, self.low=23735.9, self.vol=1545.56, self.amt=36725506.4801, ukdf['pct'].iloc[-1]=-0.000181 , ukdf['amount'].iloc[-1]=36725506.4801, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5955, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '60.176', 'enterprice': '16529.3', 'countrevence': '0', 'unrealprofit': '-435307.1664', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '23763.2', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1
--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=993672.4896432, self.flagDict['side']='sell', self.tradeCount=2, self.count=27101
self.closeSec=1677659099, self.tradeDate='20230301', self.openTime='162000', self.closeTime='162459', self.symbol='BTCUSDT', self.open=23762.3, self.close=23765.9, self.high=23784.7, self.low=23756.6, self.vol=1247.883, self.amt=29665323.7159 
127.0.0.1 - - [01/Mar/2023 16:25:01] "POST / HTTP/1.1" 200 -
2023-03-01 16:25:01,567:INFO:amihud:main.py:172:handleKline:200676: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5952  20230301   160000    160459  ...         0.0        0.0       0
5953  20230301   160500    160959  ...         0.0        0.0       0
5954  20230301   161000    161459  ...         0.0        0.0       0
5955  20230301   161500    161959  ...         0.0        0.0       0
5956  20230301   162000    162459  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-03-01 16:25:01,567:INFO:amihud:main.py:175:handleKline:200676: self.closeSec=1677659099, self.tradeDate='20230301', self.openTime='162000', self.closeTime='162459',self.symbol='BTCUSDT',self.open=23762.3, self.close=23765.9, self.high=23784.7, self.low=23756.6, self.vol=1247.883, self.amt=29665323.7159, ukdf['pct'].iloc[-1]=0.000156 , ukdf['amount'].iloc[-1]=29665323.7159, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5956, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '60.176', 'enterprice': '16529.3', 'countrevence': '0', 'unrealprofit': '-435489.9017579792', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '23766.2366817', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1


## /root/FIL/strategy/factorcheck/log.txt ----- -----


self.closeSec=1677658799, self.tradeDate='20230301', self.openTime='161500', self.closeTime='161959', self.symbol='BTCUSDT', self.open=23766.1, self.close=23762.2, self.high=23778.6, self.low=23735.9 
127.0.0.1 - - [01/Mar/2023 16:20:03] "POST / HTTP/1.1" 200 -
2023-03-01 16:20:07,512:INFO:factorcheck2:main.py:126:handleKline:185239: self.closeSec=1677658799, self.tradeDate='20230301', self.openTime='161500', self.closeTime='161959',self.symbol='BTCUSDT',self.open=23766.1, self.close=23762.2, self.high=23778.6, self.low=23735.9   
2023-03-01 16:20:08,662:INFO:factorcheck2:main.py:127:handleKline:185239: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime    closeSec  ...      low       pct  index  idx
1631  20230301   155500    155959  1677657599  ...  23698.1 -0.000021   1631    5
1632  20230301   160000    160459  1677657899  ...  23680.0  0.000637   1632    0
1633  20230301   160500    160959  1677658199  ...  23713.1  0.000527   1633    1
1634  20230301   161000    161459  1677658499  ...  23737.1  0.001234   1634    2
1635  20230301   161500    161959  1677658799  ...  23735.9 -0.000181   1635    3

[5 rows x 11 columns]
2023-03-01 16:20:08,663:INFO:factorcheck2:main.py:128:handleKline:185239: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}
127.0.0.1 - - [01/Mar/2023 16:25:01] "POST / HTTP/1.1" 200 -

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=100, self.factor=0.49079697341249856, self.count=27667 

self.closeSec=1677659099, self.tradeDate='20230301', self.openTime='162000', self.closeTime='162459', self.symbol='BTCUSDT', self.open=23762.3, self.close=23765.9, self.high=23784.7, self.low=23756.6 
2023-03-01 16:25:01,543:INFO:factorcheck2:main.py:126:handleKline:185239: self.closeSec=1677659099, self.tradeDate='20230301', self.openTime='162000', self.closeTime='162459',self.symbol='BTCUSDT',self.open=23762.3, self.close=23765.9, self.high=23784.7, self.low=23756.6   
2023-03-01 16:25:01,602:INFO:factorcheck2:main.py:127:handleKline:185239: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime    closeSec  ...      low       pct  index  idx
1632  20230301   160000    160459  1677657899  ...  23680.0  0.000637   1632    0
1633  20230301   160500    160959  1677658199  ...  23713.1  0.000527   1633    1
1634  20230301   161000    161459  1677658499  ...  23737.1  0.001234   1634    2
1635  20230301   161500    161959  1677658799  ...  23735.9 -0.000181   1635    3
1636  20230301   162000    162459  1677659099  ...  23756.6  0.000156   1636    4

[5 rows x 11 columns]
2023-03-01 16:25:01,602:INFO:factorcheck2:main.py:128:handleKline:185239: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}


## /root/FIL/strategy/logic/log.txt ----- -----

2023-03-01 16:00:35,356:DEBUG:logic:main.py:463:getModel:885513: df_s.iloc[-5:,:] :
          date closeTime     open  ...    alpha58   alpha67   alpha72
5786  20230301    132959  23788.2  ...  49.583333  0.561877  0.507854
5787  20230301    135959  23675.4  ...  50.000000  0.563676  0.487146
5788  20230301    142959  23686.1  ...  50.416667  0.570035  0.464865
5789  20230301    145959  23723.6  ...  50.416667  0.574082  0.442181
5790  20230301    152959  23747.5  ...  50.416667  0.567536  0.423277

[5 rows x 33 columns]
0.5239852398523985
acc is : 0.5239852398523985
2023-03-01 16:00:35,530:INFO:logic:main.py:468:getModel:885513: df_pred.iloc[-5:,:] :
     pred    prob_0    prob_1  actual  ...       nav  sign  cost_        bm
537     0  0.519692  0.480308       1  ...  0.859347   1.0    0.0  0.961361
538     0  0.534229  0.465771       1  ...  0.860704   1.0    0.0  0.962879
539     0  0.540226  0.459774       1  ...  0.861571   1.0    0.0  0.963849
540     0  0.536409  0.463591       0  ...  0.860530   1.0    0.0  0.962684
541     1  0.493847  0.506153       0  ...  0.860200   1.0    0.0  0.962314

[5 rows x 10 columns]
2023-03-01 16:00:35,556:INFO:logic:main.py:478:getModel:885513: df_panel.iloc[-5:,:] :
    pred    prob_0    prob_1  actual  ...       nav  sign  cost_        bm
45     0  0.519095  0.480905       1  ...  0.871603   1.0    0.0  0.959600
46     0  0.533604  0.466396       1  ...  0.872979   1.0    0.0  0.964303
47     0  0.540128  0.459872       1  ...  0.873858   1.0    0.0  0.966068
48     0  0.535909  0.464091       0  ...  0.872802   1.0    0.0  0.959223
49     1  0.493847  0.506153       0  ...  0.860200   1.0    0.0  0.962314

[5 rows x 10 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '32.563', 'enterprice': '23438.8', 'countrevence': '0', 'unrealprofit': '9052.514', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '23716.8', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}


## /root/FIL/strategy/modifiedmom/log.txt ----- -----

527  20230301   155000    155959  1677657599  23702.8  23709.6  0.000291
2023-03-01 16:00:02,090:INFO:modifiedmom:main.py:146:handleKline:185213: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': True, 'isOpenSell': False, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True}

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=13832 

self.closeSec=1677658199, self.tradeDate='20230301', self.openTime='160000', self.closeTime='160959', self.symbol='BTCUSDT', self.open='23709.6', self.close='23737.2'
2023-03-01 16:10:01,586:INFO:modifiedmom:main.py:144:handleKline:185213: self.closeSec=1677658199, self.tradeDate='20230301', self.openTime='160000', self.closeTime='160959',self.symbol='BTCUSDT',self.open='23709.6', self.close='23737.2'
127.0.0.1 - - [01/Mar/2023 16:10:01] "POST / HTTP/1.1" 200 -
2023-03-01 16:10:01,622:INFO:modifiedmom:main.py:145:handleKline:185213: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec     open    close       pct
524  20230301   152000    152959  1677655799    23717  23718.7  0.000072
525  20230301   153000    153959  1677656399  23718.7  23693.7 -0.001054
526  20230301   154000    154959  1677656999  23693.8  23702.7  0.000380
527  20230301   155000    155959  1677657599  23702.8  23709.6  0.000291
528  20230301   160000    160959  1677658199  23709.6  23737.2  0.001164
2023-03-01 16:10:01,622:INFO:modifiedmom:main.py:146:handleKline:185213: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': True, 'isOpenSell': False, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True}

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=13833 

self.closeSec=1677658799, self.tradeDate='20230301', self.openTime='161000', self.closeTime='161959', self.symbol='BTCUSDT', self.open='23737.1', self.close='23762.2'
127.0.0.1 - - [01/Mar/2023 16:20:04] "POST / HTTP/1.1" 200 -
2023-03-01 16:20:08,202:INFO:modifiedmom:main.py:144:handleKline:185213: self.closeSec=1677658799, self.tradeDate='20230301', self.openTime='161000', self.closeTime='161959',self.symbol='BTCUSDT',self.open='23737.1', self.close='23762.2'
2023-03-01 16:20:08,993:INFO:modifiedmom:main.py:145:handleKline:185213: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec     open    close       pct
525  20230301   153000    153959  1677656399  23718.7  23693.7 -0.001054
526  20230301   154000    154959  1677656999  23693.8  23702.7  0.000380
527  20230301   155000    155959  1677657599  23702.8  23709.6  0.000291
528  20230301   160000    160959  1677658199  23709.6  23737.2  0.001164
529  20230301   161000    161959  1677658799  23737.1  23762.2  0.001053
2023-03-01 16:20:09,002:INFO:modifiedmom:main.py:146:handleKline:185213: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': True, 'isOpenSell': False, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True}


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

17519  20230301   155000    155959  1677657599  23702.8  23709.6
2023-03-01 16:00:02,130:INFO:pyemd2:main.py:127:handleKline:185189: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=13833 

self.closeSec=1677658199, self.tradeDate='20230301', self.openTime='160000', self.closeTime='160959', self.symbol='BTCUSDT', self.open='23709.6', self.close='23737.2'
2023-03-01 16:10:01,612:INFO:pyemd2:main.py:125:handleKline:185189: self.closeSec=1677658199, self.tradeDate='20230301', self.openTime='160000', self.closeTime='160959',self.symbol='BTCUSDT',self.open='23709.6', self.close='23737.2'
127.0.0.1 - - [01/Mar/2023 16:10:01] "POST / HTTP/1.1" 200 -
2023-03-01 16:10:01,638:INFO:pyemd2:main.py:126:handleKline:185189: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
17516  20230301   152000    152959  1677655799    23717  23718.7
17517  20230301   153000    153959  1677656399  23718.7  23693.7
17518  20230301   154000    154959  1677656999  23693.8  23702.7
17519  20230301   155000    155959  1677657599  23702.8  23709.6
17520  20230301   160000    160959  1677658199  23709.6  23737.2
2023-03-01 16:10:01,639:INFO:pyemd2:main.py:127:handleKline:185189: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=13834 

self.closeSec=1677658799, self.tradeDate='20230301', self.openTime='161000', self.closeTime='161959', self.symbol='BTCUSDT', self.open='23737.1', self.close='23762.2'
127.0.0.1 - - [01/Mar/2023 16:20:04] "POST / HTTP/1.1" 200 -
2023-03-01 16:20:11,066:INFO:pyemd2:main.py:125:handleKline:185189: self.closeSec=1677658799, self.tradeDate='20230301', self.openTime='161000', self.closeTime='161959',self.symbol='BTCUSDT',self.open='23737.1', self.close='23762.2'
2023-03-01 16:20:11,284:INFO:pyemd2:main.py:126:handleKline:185189: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
17517  20230301   153000    153959  1677656399  23718.7  23693.7
17518  20230301   154000    154959  1677656999  23693.8  23702.7
17519  20230301   155000    155959  1677657599  23702.8  23709.6
17520  20230301   160000    160959  1677658199  23709.6  23737.2
17521  20230301   161000    161959  1677658799  23737.1  23762.2
2023-03-01 16:20:11,284:INFO:pyemd2:main.py:127:handleKline:185189: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}


## /root/FIL/strategy/similarity/log.txt ----- -----

12191  20230301   155000    155959  1677657599  23702.8  23709.6
2023-03-01 16:00:02,146:INFO:testStrategy:main.py:103:handleKline:185174: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': True, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True, 'isCorr': False}

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=13833 

self.closeSec=1677658199, self.tradeDate='20230301', self.openTime='160000', self.closeTime='160959', self.symbol='BTCUSDT', self.open='23709.6', self.close='23737.2'
2023-03-01 16:10:01,594:INFO:testStrategy:main.py:101:handleKline:185174: self.closeSec=1677658199, self.tradeDate='20230301', self.openTime='160000', self.closeTime='160959',self.symbol='BTCUSDT',self.open='23709.6', self.close='23737.2'
127.0.0.1 - - [01/Mar/2023 16:10:01] "POST / HTTP/1.1" 200 -
2023-03-01 16:10:01,630:INFO:testStrategy:main.py:102:handleKline:185174: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
12188  20230301   152000    152959  1677655799    23717  23718.7
12189  20230301   153000    153959  1677656399  23718.7  23693.7
12190  20230301   154000    154959  1677656999  23693.8  23702.7
12191  20230301   155000    155959  1677657599  23702.8  23709.6
12192  20230301   160000    160959  1677658199  23709.6  23737.2
2023-03-01 16:10:01,630:INFO:testStrategy:main.py:103:handleKline:185174: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': True, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True, 'isCorr': False}

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=13834 

self.closeSec=1677658799, self.tradeDate='20230301', self.openTime='161000', self.closeTime='161959', self.symbol='BTCUSDT', self.open='23737.1', self.close='23762.2'
127.0.0.1 - - [01/Mar/2023 16:20:05] "POST / HTTP/1.1" 200 -
2023-03-01 16:20:10,505:INFO:testStrategy:main.py:101:handleKline:185174: self.closeSec=1677658799, self.tradeDate='20230301', self.openTime='161000', self.closeTime='161959',self.symbol='BTCUSDT',self.open='23737.1', self.close='23762.2'
2023-03-01 16:20:11,183:INFO:testStrategy:main.py:102:handleKline:185174: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
12189  20230301   153000    153959  1677656399  23718.7  23693.7
12190  20230301   154000    154959  1677656999  23693.8  23702.7
12191  20230301   155000    155959  1677657599  23702.8  23709.6
12192  20230301   160000    160959  1677658199  23709.6  23737.2
12193  20230301   161000    161959  1677658799  23737.1  23762.2
2023-03-01 16:20:11,183:INFO:testStrategy:main.py:103:handleKline:185174: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': True, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True, 'isCorr': False}


## /root/FIL/strategy/sr_min/log.txt ----- -----

--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=0, self.total=1000000.0, self.flagDict['side']='', self.tradeCount=0, self.count=23098
self.closeSec=1677658799, self.tradeDate='20230301', self.openTime='161500', self.closeTime='161959', self.symbol='BTCUSDT', self.open=23766.1, self.close=23762.2, self.high=23778.6, self.low=23735.9, self.vol=1545.56, self.amt=36725506.4801 
127.0.0.1 - - [01/Mar/2023 16:20:02] "POST / HTTP/1.1" 200 -
2023-03-01 16:20:07,113:INFO:sr_min:main.py:172:handleKline:449472: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5951  20230301   155500    155959  ...         0.0        0.0       0
5952  20230301   160000    160459  ...         0.0        0.0       0
5953  20230301   160500    160959  ...         0.0        0.0       0
5954  20230301   161000    161459  ...         0.0        0.0       0
5955  20230301   161500    161959  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-03-01 16:20:07,133:INFO:sr_min:main.py:175:handleKline:449472: self.closeSec=1677658799, self.tradeDate='20230301', self.openTime='161500', self.closeTime='161959',self.symbol='BTCUSDT',self.open=23766.1, self.close=23762.2, self.high=23778.6, self.low=23735.9, self.vol=1545.56, self.amt=36725506.4801, ukdf['pct'].iloc[-1]=-0.000181 , ukdf['amount'].iloc[-1]=36725506.4801, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5955, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': []}
type(curSign)=<class 'int'>, curSign=0, self.sign=0
127.0.0.1 - - [01/Mar/2023 16:25:01] "POST / HTTP/1.1" 200 -
--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=0, self.total=1000000.0, self.flagDict['side']='', self.tradeCount=0, self.count=23099
self.closeSec=1677659099, self.tradeDate='20230301', self.openTime='162000', self.closeTime='162459', self.symbol='BTCUSDT', self.open=23762.3, self.close=23765.9, self.high=23784.7, self.low=23756.6, self.vol=1247.883, self.amt=29665323.7159 
2023-03-01 16:25:01,657:INFO:sr_min:main.py:172:handleKline:449472: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5952  20230301   160000    160459  ...         0.0        0.0       0
5953  20230301   160500    160959  ...         0.0        0.0       0
5954  20230301   161000    161459  ...         0.0        0.0       0
5955  20230301   161500    161959  ...         0.0        0.0       0
5956  20230301   162000    162459  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-03-01 16:25:01,658:INFO:sr_min:main.py:175:handleKline:449472: self.closeSec=1677659099, self.tradeDate='20230301', self.openTime='162000', self.closeTime='162459',self.symbol='BTCUSDT',self.open=23762.3, self.close=23765.9, self.high=23784.7, self.low=23756.6, self.vol=1247.883, self.amt=29665323.7159, ukdf['pct'].iloc[-1]=0.000156 , ukdf['amount'].iloc[-1]=29665323.7159, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5956, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': []}
type(curSign)=<class 'int'>, curSign=0, self.sign=0


## /root/FIL/strategy/s_rsrs/log.txt ----- -----

721  20230301   040000    075959  1677628799  ...    721  0.635610 -0.042715     NaN
722  20230301   080000    115959  1677643199  ...    722  0.593669 -0.166411     NaN

[5 rows x 15 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '42.179', 'enterprice': '23108.8', 'countrevence': '0', 'unrealprofit': '13872.6731', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '23437.7', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'numpy.int64'>, curSign=-9223372036854775808, self.sign=1
127.0.0.1 - - [01/Mar/2023 16:00:01] "POST / HTTP/1.1" 200 -
--handleKline--:  version='2.0.0', self.name='s_rsrs', self.symbol='BTCUSDT', interval='4h', intervalSec=14400, wid=25, thd=0.6, self.sign=1, self.total=973731.3691248, self.flagDict['side']='buy', self.tradeCount=22, self.count=576
self.closeSec=1677657599, self.tradeDate='20230301', self.openTime='120000', self.closeTime='155959', self.symbol='BTCUSDT', self.open=23431.6, self.close=23709.6, self.high=23852.6, self.low=23414.8, self.vol=119744.837, self.amt=2837105454.75648 
2023-03-01 16:00:01,952:INFO:s_rsrs:main.py:141:handleKline:185271: self.closeSec=1677657599, self.tradeDate='20230301', self.openTime='120000', self.closeTime='155959',self.symbol='BTCUSDT',self.open=23431.6, self.close=23709.6, self.high=23852.6, self.low=23414.8, self.vol=119744.837, self.amt=2837105454.75648 
2023-03-01 16:00:02,047:INFO:s_rsrs:main.py:142:handleKline:185271: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime  ...         vol           amt       pct
719  20230228   200000    235959  ...  126298.911  2.961352e+09  0.005543
720  20230301   000000    035959  ...   90462.656  2.118301e+09 -0.011067
721  20230301   040000    075959  ...  100091.272  2.318269e+09 -0.005221
722  20230301   080000    115959  ...   94869.432  2.207722e+09  0.013057
723  20230301   120000    155959  ...  119744.837  2.837105e+09  0.011864

[5 rows x 11 columns]
2023-03-01 16:00:04,891:INFO:s_rsrs:main.py:151:handleKline:185271: df_s.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec  ...  index      beta    zscore  signal
719  20230228   200000    235959  1677599999  ...    719  0.558675 -0.210626     NaN
720  20230301   000000    035959  1677614399  ...    720  0.490960 -0.389624     NaN
721  20230301   040000    075959  1677628799  ...    721  0.635610 -0.042715     NaN
722  20230301   080000    115959  1677643199  ...    722  0.593669 -0.166411     NaN
723  20230301   120000    155959  1677657599  ...    723  0.676162  0.028418     NaN

[5 rows x 15 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '42.179', 'enterprice': '23108.8', 'countrevence': '0', 'unrealprofit': '25212.19171249443', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '23706.54275617', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'numpy.int64'>, curSign=-9223372036854775808, self.sign=1


