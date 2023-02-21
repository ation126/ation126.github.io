# 20230222 00:26:02

## /root/FIL/strategy/amihud/log.txt ----- -----

--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=993672.4896432, self.flagDict['side']='sell', self.tradeCount=2, self.count=24892
self.closeSec=1676996399, self.tradeDate='20230222', self.openTime='001500', self.closeTime='001959', self.symbol='BTCUSDT', self.open=24448.8, self.close=24348.1, self.high=24466.1, self.low=24305.0, self.vol=13338.541, self.amt=325044381.3154 
127.0.0.1 - - [22/Feb/2023 00:20:01] "POST / HTTP/1.1" 200 -
2023-02-22 00:20:01,727:INFO:amihud:main.py:172:handleKline:200676: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5759  20230221   235500    235959  ...         0.0        0.0       0
5760  20230222   000000    000459  ...         0.0        0.0       0
5761  20230222   000500    000959  ...         0.0        0.0       0
5762  20230222   001000    001459  ...         0.0        0.0       0
5763  20230222   001500    001959  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-02-22 00:20:01,731:INFO:amihud:main.py:175:handleKline:200676: self.closeSec=1676996399, self.tradeDate='20230222', self.openTime='001500', self.closeTime='001959',self.symbol='BTCUSDT',self.open=24448.8, self.close=24348.1, self.high=24466.1, self.low=24305.0, self.vol=13338.541, self.amt=325044381.3154, ukdf['pct'].iloc[-1]=-0.004115 , ukdf['amount'].iloc[-1]=325044381.3154, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5763, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '60.176', 'enterprice': '16529.3', 'countrevence': '0', 'unrealprofit': '-470618.4432', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '24350', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1
127.0.0.1 - - [22/Feb/2023 00:25:01] "POST / HTTP/1.1" 200 -
--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=993672.4896432, self.flagDict['side']='sell', self.tradeCount=2, self.count=24893
self.closeSec=1676996699, self.tradeDate='20230222', self.openTime='002000', self.closeTime='002459', self.symbol='BTCUSDT', self.open=24348.0, self.close=24358.1, self.high=24384.2, self.low=24321.0, self.vol=4247.501, self.amt=103469282.6139 
2023-02-22 00:25:01,737:INFO:amihud:main.py:172:handleKline:200676: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5760  20230222   000000    000459  ...         0.0        0.0       0
5761  20230222   000500    000959  ...         0.0        0.0       0
5762  20230222   001000    001459  ...         0.0        0.0       0
5763  20230222   001500    001959  ...         0.0        0.0       0
5764  20230222   002000    002459  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-02-22 00:25:01,738:INFO:amihud:main.py:175:handleKline:200676: self.closeSec=1676996699, self.tradeDate='20230222', self.openTime='002000', self.closeTime='002459',self.symbol='BTCUSDT',self.open=24348.0, self.close=24358.1, self.high=24384.2, self.low=24321.0, self.vol=4247.501, self.amt=103469282.6139, ukdf['pct'].iloc[-1]=0.000411 , ukdf['amount'].iloc[-1]=103469282.6139, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5764, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '60.176', 'enterprice': '16529.3', 'countrevence': '0', 'unrealprofit': '-471310.4672', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '24361.5', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1


## /root/FIL/strategy/factorcheck/log.txt ----- -----


self.closeSec=1676996399, self.tradeDate='20230222', self.openTime='001500', self.closeTime='001959', self.symbol='BTCUSDT', self.open=24448.8, self.close=24348.1, self.high=24466.1, self.low=24305.0 
2023-02-22 00:20:01,636:INFO:factorcheck2:main.py:126:handleKline:185239: self.closeSec=1676996399, self.tradeDate='20230222', self.openTime='001500', self.closeTime='001959',self.symbol='BTCUSDT',self.open=24448.8, self.close=24348.1, self.high=24466.1, self.low=24305.0   
127.0.0.1 - - [22/Feb/2023 00:20:01] "POST / HTTP/1.1" 200 -
2023-02-22 00:20:01,677:INFO:factorcheck2:main.py:127:handleKline:185239: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime    closeSec  ...      low       pct  index  idx
1439  20230221   235500    235959  1676995199  ...  24535.7 -0.000798   1727    5
1440  20230222   000000    000459  1676995499  ...  24535.9 -0.000757   1440    0
1441  20230222   000500    000959  1676995799  ...  24479.3 -0.001838   1441    1
1442  20230222   001000    001459  1676996099  ...  24366.0 -0.001768   1442    2
1443  20230222   001500    001959  1676996399  ...  24305.0 -0.004115   1443    3

[5 rows x 11 columns]
2023-02-22 00:20:01,677:INFO:factorcheck2:main.py:128:handleKline:185239: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=327, self.factor=0.4966853986773503, self.count=25459 

self.closeSec=1676996699, self.tradeDate='20230222', self.openTime='002000', self.closeTime='002459', self.symbol='BTCUSDT', self.open=24348.0, self.close=24358.1, self.high=24384.2, self.low=24321.0 
2023-02-22 00:25:01,635:INFO:factorcheck2:main.py:126:handleKline:185239: self.closeSec=1676996699, self.tradeDate='20230222', self.openTime='002000', self.closeTime='002459',self.symbol='BTCUSDT',self.open=24348.0, self.close=24358.1, self.high=24384.2, self.low=24321.0   
127.0.0.1 - - [22/Feb/2023 00:25:01] "POST / HTTP/1.1" 200 -
2023-02-22 00:25:01,658:INFO:factorcheck2:main.py:127:handleKline:185239: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime    closeSec  ...      low       pct  index  idx
1440  20230222   000000    000459  1676995499  ...  24535.9 -0.000757   1440    0
1441  20230222   000500    000959  1676995799  ...  24479.3 -0.001838   1441    1
1442  20230222   001000    001459  1676996099  ...  24366.0 -0.001768   1442    2
1443  20230222   001500    001959  1676996399  ...  24305.0 -0.004115   1443    3
1444  20230222   002000    002459  1676996699  ...  24321.0  0.000411   1444    4

[5 rows x 11 columns]
2023-02-22 00:25:01,658:INFO:factorcheck2:main.py:128:handleKline:185239: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}


## /root/FIL/strategy/logic/log.txt ----- -----

2023-02-22 00:00:34,229:DEBUG:logic:main.py:463:getModel:885513: df_s.iloc[-5:,:] :
          date closeTime     open  ...    alpha58   alpha67   alpha72
5802  20230221    212959  24634.1  ...  49.166667  0.485714  0.555951
5803  20230221    215959  24634.4  ...  49.166667  0.474077  0.578489
5804  20230221    222959  24568.6  ...  49.583333  0.487338  0.593818
5805  20230221    225959  24642.1  ...  49.583333  0.495061  0.604734
5806  20230221    232959  24686.3  ...  49.166667  0.467897  0.622005

[5 rows x 33 columns]
0.5183823529411765
acc is : 0.5183823529411765
2023-02-22 00:00:34,389:INFO:logic:main.py:468:getModel:885513: df_pred.iloc[-5:,:] :
     pred    prob_0    prob_1  actual  ...       nav  sign  cost_        bm
539     0  0.503803  0.496197       0  ...  1.069755  -1.0    0.0  1.121692
540     1  0.482395  0.517605       1  ...  1.066502  -1.0    0.0  1.125103
541     0  0.525009  0.474991       1  ...  1.064580  -1.0    0.0  1.127130
542     0  0.521264  0.478736       0  ...  1.071812  -1.0    0.0  1.119473
543     1  0.469117  0.530883       1  ...  1.070269  -1.0    0.0  1.121085

[5 rows x 10 columns]
2023-02-22 00:00:34,430:INFO:logic:main.py:478:getModel:885513: df_panel.iloc[-5:,:] :
    pred    prob_0    prob_1  actual  ...       nav  sign  cost_        bm
45     0  0.504314  0.495686       0  ...  1.061969  -1.0    0.0  1.124794
46     1  0.482449  0.517551       1  ...  1.066502  -1.0    0.0  1.126703
47     0  0.525755  0.474245       1  ...  1.023149  -1.0    0.0  1.128733
48     0  0.521794  0.478206       0  ...  1.064012  -1.0    0.0  1.123171
49     1  0.469117  0.530883       1  ...  1.070269  -1.0    0.0  1.121085

[5 rows x 10 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '34.236', 'enterprice': '24733.9', 'countrevence': '0', 'unrealprofit': '6306.2712', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '24549.7', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}


## /root/FIL/strategy/modifiedmom/log.txt ----- -----

2023-02-22 00:00:03,460:INFO:modifiedmom:main.py:319:handleOrderFilled:185213: handleOrderFilled: data=OrderType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'clientorderid': '41784F1676995203082I0L59', 'symbol': 'BTCUSDT', 'gatewayorderid': 1676995203187233, 'quantity': '37.601', 'price': '24554', 'stopprice': '0', 'ordertype': '', 'side': 'BUY', 'status': 'FILLED', 'positionside': 'LONG', 'createtime': 1676995202595, 'updatetime': 1676995203187, 'tradetype': 'usdt', 'selfid': 41784, 'filltrades': [TradeType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'tradeid': 1676995203187, 'clientorderid': '41784F1676995203082I0L59', 'price': '24554', 'quantity': '37.601', 'commission': '923.254954', 'commissionasset': 'USDT', 'tradetime': 1676995203187, 'tradetype': 'usdt', 'gatetype': 'simulator', 'handletime': 1676995203187}], 'gatetype': 'simulator', 'handletime': 0}
127.0.0.1 - - [22/Feb/2023 00:00:03] "POST / HTTP/1.1" 200 -
127.0.0.1 - - [22/Feb/2023 00:10:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=12728 

self.closeSec=1676995799, self.tradeDate='20230222', self.openTime='000000', self.closeTime='000959', self.symbol='BTCUSDT', self.open='24554', self.close='24492'
2023-02-22 00:10:01,658:INFO:modifiedmom:main.py:144:handleKline:185213: self.closeSec=1676995799, self.tradeDate='20230222', self.openTime='000000', self.closeTime='000959',self.symbol='BTCUSDT',self.open='24554', self.close='24492'
2023-02-22 00:10:01,721:INFO:modifiedmom:main.py:145:handleKline:185213: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec     open    close       pct
572  20230221   232000    232959  1676993399    24524  24518.7 -0.000216
573  20230221   233000    233959  1676993999  24518.8  24587.9  0.002822
574  20230221   234000    234959  1676994599  24587.8  24583.3 -0.000187
575  20230221   235000    235959  1676995199  24583.4    24554 -0.001192
576  20230222   000000    000959  1676995799    24554    24492 -0.002525
2023-02-22 00:10:01,721:INFO:modifiedmom:main.py:146:handleKline:185213: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': True, 'isOpen': False, 'isClose': True, 'isTrig': False}

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=12729 

self.closeSec=1676996399, self.tradeDate='20230222', self.openTime='001000', self.closeTime='001959', self.symbol='BTCUSDT', self.open='24490.2', self.close='24348.1'
127.0.0.1 - - [22/Feb/2023 00:20:01] "POST / HTTP/1.1" 200 -
2023-02-22 00:20:01,798:INFO:modifiedmom:main.py:144:handleKline:185213: self.closeSec=1676996399, self.tradeDate='20230222', self.openTime='001000', self.closeTime='001959',self.symbol='BTCUSDT',self.open='24490.2', self.close='24348.1'
2023-02-22 00:20:01,863:INFO:modifiedmom:main.py:145:handleKline:185213: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec     open    close       pct
573  20230221   233000    233959  1676993999  24518.8  24587.9  0.002822
574  20230221   234000    234959  1676994599  24587.8  24583.3 -0.000187
575  20230221   235000    235959  1676995199  24583.4    24554 -0.001192
576  20230222   000000    000959  1676995799    24554    24492 -0.002525
577  20230222   001000    001959  1676996399  24490.2  24348.1 -0.005875
2023-02-22 00:20:01,863:INFO:modifiedmom:main.py:146:handleKline:185213: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': True, 'isOpen': False, 'isClose': True, 'isTrig': False}


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

2023-02-22 00:00:02,422:INFO:pyemd2:main.py:127:handleKline:185189: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}
2023-02-22 00:00:02,551:INFO:pyemd2:main.py:190:insertFactor:185189: curDateTime:2220000, name:pyemd2, symbol:BTCUSDT, tradeDate:20230221, closeTime:235959, close:24554, total:979069.1011917, pct_pre:-0.002473953095458392, thd:0.18016752698283256, side:sell 

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=12729 

self.closeSec=1676995799, self.tradeDate='20230222', self.openTime='000000', self.closeTime='000959', self.symbol='BTCUSDT', self.open='24554', self.close='24492'
2023-02-22 00:10:01,661:INFO:pyemd2:main.py:125:handleKline:185189: self.closeSec=1676995799, self.tradeDate='20230222', self.openTime='000000', self.closeTime='000959',self.symbol='BTCUSDT',self.open='24554', self.close='24492'
127.0.0.1 - - [22/Feb/2023 00:10:01] "POST / HTTP/1.1" 200 -
2023-02-22 00:10:01,715:INFO:pyemd2:main.py:126:handleKline:185189: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
17420  20230221   232000    232959  1676993399    24524  24518.7
17421  20230221   233000    233959  1676993999  24518.8  24587.9
17422  20230221   234000    234959  1676994599  24587.8  24583.3
17423  20230221   235000    235959  1676995199  24583.4    24554
17424  20230222   000000    000959  1676995799    24554    24492
2023-02-22 00:10:01,715:INFO:pyemd2:main.py:127:handleKline:185189: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=12730 

self.closeSec=1676996399, self.tradeDate='20230222', self.openTime='001000', self.closeTime='001959', self.symbol='BTCUSDT', self.open='24490.2', self.close='24348.1'
127.0.0.1 - - [22/Feb/2023 00:20:01] "POST / HTTP/1.1" 200 -
2023-02-22 00:20:01,837:INFO:pyemd2:main.py:125:handleKline:185189: self.closeSec=1676996399, self.tradeDate='20230222', self.openTime='001000', self.closeTime='001959',self.symbol='BTCUSDT',self.open='24490.2', self.close='24348.1'
2023-02-22 00:20:01,862:INFO:pyemd2:main.py:126:handleKline:185189: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
17421  20230221   233000    233959  1676993999  24518.8  24587.9
17422  20230221   234000    234959  1676994599  24587.8  24583.3
17423  20230221   235000    235959  1676995199  24583.4    24554
17424  20230222   000000    000959  1676995799    24554    24492
17425  20230222   001000    001959  1676996399  24490.2  24348.1
2023-02-22 00:20:01,862:INFO:pyemd2:main.py:127:handleKline:185189: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}


## /root/FIL/strategy/similarity/log.txt ----- -----

2023-02-22 00:00:03,772:INFO:testStrategy:main.py:308:handleOrderFilled:185174: handleOrderFilled: data=OrderType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'clientorderid': '41785F1676995203165I0L2', 'symbol': 'BTCUSDT', 'gatewayorderid': 1676995203337197, 'quantity': '48.489', 'price': '24553.9', 'stopprice': '0', 'ordertype': '', 'side': 'SELL', 'status': 'FILLED', 'positionside': 'SHORT', 'createtime': 1676995202619, 'updatetime': 1676995203337, 'tradetype': 'usdt', 'selfid': 41785, 'filltrades': [TradeType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'tradeid': 1676995203337, 'clientorderid': '41785F1676995203165I0L2', 'price': '24553.9', 'quantity': '48.489', 'commission': '1190.5940571', 'commissionasset': 'USDT', 'tradetime': 1676995203337, 'tradetype': 'usdt', 'gatetype': 'simulator', 'handletime': 1676995203337}], 'gatetype': 'simulator', 'handletime': 0}
127.0.0.1 - - [22/Feb/2023 00:00:03] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=12729 

self.closeSec=1676995799, self.tradeDate='20230222', self.openTime='000000', self.closeTime='000959', self.symbol='BTCUSDT', self.open='24554', self.close='24492'
2023-02-22 00:10:01,676:INFO:testStrategy:main.py:101:handleKline:185174: self.closeSec=1676995799, self.tradeDate='20230222', self.openTime='000000', self.closeTime='000959',self.symbol='BTCUSDT',self.open='24554', self.close='24492'
127.0.0.1 - - [22/Feb/2023 00:10:01] "POST / HTTP/1.1" 200 -
2023-02-22 00:10:01,724:INFO:testStrategy:main.py:102:handleKline:185174: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
12236  20230221   232000    232959  1676993399    24524  24518.7
12237  20230221   233000    233959  1676993999  24518.8  24587.9
12238  20230221   234000    234959  1676994599  24587.8  24583.3
12239  20230221   235000    235959  1676995199  24583.4    24554
12240  20230222   000000    000959  1676995799    24554    24492
2023-02-22 00:10:01,724:INFO:testStrategy:main.py:103:handleKline:185174: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': True, 'isOpen': False, 'isClose': True, 'isTrig': False, 'isCorr': False}
127.0.0.1 - - [22/Feb/2023 00:20:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=12730 

self.closeSec=1676996399, self.tradeDate='20230222', self.openTime='001000', self.closeTime='001959', self.symbol='BTCUSDT', self.open='24490.2', self.close='24348.1'
2023-02-22 00:20:01,819:INFO:testStrategy:main.py:101:handleKline:185174: self.closeSec=1676996399, self.tradeDate='20230222', self.openTime='001000', self.closeTime='001959',self.symbol='BTCUSDT',self.open='24490.2', self.close='24348.1'
2023-02-22 00:20:01,848:INFO:testStrategy:main.py:102:handleKline:185174: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
12237  20230221   233000    233959  1676993999  24518.8  24587.9
12238  20230221   234000    234959  1676994599  24587.8  24583.3
12239  20230221   235000    235959  1676995199  24583.4    24554
12240  20230222   000000    000959  1676995799    24554    24492
12241  20230222   001000    001959  1676996399  24490.2  24348.1
2023-02-22 00:20:01,848:INFO:testStrategy:main.py:103:handleKline:185174: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': True, 'isOpen': False, 'isClose': True, 'isTrig': False, 'isCorr': False}


## /root/FIL/strategy/sr_min/log.txt ----- -----

--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=0, self.total=1000000.0, self.flagDict['side']='', self.tradeCount=0, self.count=20890
self.closeSec=1676996399, self.tradeDate='20230222', self.openTime='001500', self.closeTime='001959', self.symbol='BTCUSDT', self.open=24448.8, self.close=24348.1, self.high=24466.1, self.low=24305.0, self.vol=13338.541, self.amt=325044381.3154 
127.0.0.1 - - [22/Feb/2023 00:20:01] "POST / HTTP/1.1" 200 -
2023-02-22 00:20:01,723:INFO:sr_min:main.py:172:handleKline:449472: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5759  20230221   235500    235959  ...         0.0        0.0       0
5760  20230222   000000    000459  ...         0.0        0.0       0
5761  20230222   000500    000959  ...         0.0        0.0       0
5762  20230222   001000    001459  ...         0.0        0.0       0
5763  20230222   001500    001959  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-02-22 00:20:01,725:INFO:sr_min:main.py:175:handleKline:449472: self.closeSec=1676996399, self.tradeDate='20230222', self.openTime='001500', self.closeTime='001959',self.symbol='BTCUSDT',self.open=24448.8, self.close=24348.1, self.high=24466.1, self.low=24305.0, self.vol=13338.541, self.amt=325044381.3154, ukdf['pct'].iloc[-1]=-0.004115 , ukdf['amount'].iloc[-1]=325044381.3154, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5763, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': []}
type(curSign)=<class 'int'>, curSign=0, self.sign=0
127.0.0.1 - - [22/Feb/2023 00:25:01] "POST / HTTP/1.1" 200 -
--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=0, self.total=1000000.0, self.flagDict['side']='', self.tradeCount=0, self.count=20891
self.closeSec=1676996699, self.tradeDate='20230222', self.openTime='002000', self.closeTime='002459', self.symbol='BTCUSDT', self.open=24348.0, self.close=24358.1, self.high=24384.2, self.low=24321.0, self.vol=4247.501, self.amt=103469282.6139 
2023-02-22 00:25:01,752:INFO:sr_min:main.py:172:handleKline:449472: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5760  20230222   000000    000459  ...         0.0        0.0       0
5761  20230222   000500    000959  ...         0.0        0.0       0
5762  20230222   001000    001459  ...         0.0        0.0       0
5763  20230222   001500    001959  ...         0.0        0.0       0
5764  20230222   002000    002459  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-02-22 00:25:01,759:INFO:sr_min:main.py:175:handleKline:449472: self.closeSec=1676996699, self.tradeDate='20230222', self.openTime='002000', self.closeTime='002459',self.symbol='BTCUSDT',self.open=24348.0, self.close=24358.1, self.high=24384.2, self.low=24321.0, self.vol=4247.501, self.amt=103469282.6139, ukdf['pct'].iloc[-1]=0.000411 , ukdf['amount'].iloc[-1]=103469282.6139, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5764, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': []}
type(curSign)=<class 'int'>, curSign=0, self.sign=0


## /root/FIL/strategy/s_rsrs/log.txt ----- -----

723  20230221   120000    155959  1676966399  ...    723  0.332460 -0.788208    -1.0
724  20230221   160000    195959  1676980799  ...    724  0.230000 -1.036031    -1.0

[5 rows x 15 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '36.465', 'enterprice': '24934.8', 'countrevence': '0', 'unrealprofit': '13327.51744512045', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '24569.31206787', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'numpy.int64'>, curSign=-1, self.sign=-1
127.0.0.1 - - [22/Feb/2023 00:00:02] "POST / HTTP/1.1" 200 -
--handleKline--:  version='2.0.0', self.name='s_rsrs', self.symbol='BTCUSDT', interval='4h', intervalSec=14400, wid=25, thd=0.6, self.sign=-1, self.total=908338.234518, self.flagDict['side']='sell', self.tradeCount=21, self.count=530
self.closeSec=1676995199, self.tradeDate='20230221', self.openTime='200000', self.closeTime='235959', self.symbol='BTCUSDT', self.open=24572.6, self.close=24554.0, self.high=24786.6, self.low=24388.0, self.vol=141571.537, self.amt=3482794208.27499 
2023-02-22 00:00:02,198:INFO:s_rsrs:main.py:141:handleKline:185271: self.closeSec=1676995199, self.tradeDate='20230221', self.openTime='200000', self.closeTime='235959',self.symbol='BTCUSDT',self.open=24572.6, self.close=24554.0, self.high=24786.6, self.low=24388.0, self.vol=141571.537, self.amt=3482794208.27499 
2023-02-22 00:00:02,273:INFO:s_rsrs:main.py:142:handleKline:185271: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime  ...         vol           amt       pct
721  20230221   040000    075959  ...   38879.181  9.633554e+08 -0.001150
722  20230221   080000    115959  ...   76679.867  1.912971e+09  0.003070
723  20230221   120000    155959  ...   46758.131  1.167208e+09  0.003145
724  20230221   160000    195959  ...  217838.830  5.409969e+09 -0.017273
725  20230221   200000    235959  ...  141571.537  3.482794e+09 -0.000761

[5 rows x 11 columns]
2023-02-22 00:00:04,968:INFO:s_rsrs:main.py:151:handleKline:185271: df_s.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec  ...  index      beta    zscore  signal
721  20230221   040000    075959  1676937599  ...    721  0.197351 -1.167501    -1.0
722  20230221   080000    115959  1676951999  ...    722  0.389758 -0.650516    -1.0
723  20230221   120000    155959  1676966399  ...    723  0.332460 -0.788208    -1.0
724  20230221   160000    195959  1676980799  ...    724  0.230000 -1.036031    -1.0
725  20230221   200000    235959  1676995199  ...    725  0.092406 -1.360631    -1.0

[5 rows x 15 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '36.465', 'enterprice': '24934.8', 'countrevence': '0', 'unrealprofit': '13858.6216726815', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '24554.7473009', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'numpy.int64'>, curSign=-1, self.sign=-1


