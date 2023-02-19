# 20230220 00:26:02

## /root/FIL/strategy/amihud/log.txt ----- -----

127.0.0.1 - - [20/Feb/2023 00:20:01] "POST / HTTP/1.1" 200 -
--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=993672.4896432, self.flagDict['side']='sell', self.tradeCount=2, self.count=24316
self.closeSec=1676823599, self.tradeDate='20230220', self.openTime='001500', self.closeTime='001959', self.symbol='BTCUSDT', self.open=25168.2, self.close=25078.4, self.high=25200.0, self.low=25055.1, self.vol=9559.1, self.amt=240069409.4716 
2023-02-20 00:20:01,760:INFO:amihud:main.py:172:handleKline:200676: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5759  20230219   235500    235959  ...         0.0        0.0       0
5760  20230220   000000    000459  ...         0.0        0.0       0
5761  20230220   000500    000959  ...         0.0        0.0       0
5762  20230220   001000    001459  ...         0.0        0.0       0
5763  20230220   001500    001959  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-02-20 00:20:01,762:INFO:amihud:main.py:175:handleKline:200676: self.closeSec=1676823599, self.tradeDate='20230220', self.openTime='001500', self.closeTime='001959',self.symbol='BTCUSDT',self.open=25168.2, self.close=25078.4, self.high=25200.0, self.low=25055.1, self.vol=9559.1, self.amt=240069409.4716, ukdf['pct'].iloc[-1]=-0.003987 , ukdf['amount'].iloc[-1]=240069409.4716, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5763, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '60.176', 'enterprice': '16529.3', 'countrevence': '0', 'unrealprofit': '-514444.624', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '25078.3', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1
--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=993672.4896432, self.flagDict['side']='sell', self.tradeCount=2, self.count=24317
self.closeSec=1676823899, self.tradeDate='20230220', self.openTime='002000', self.closeTime='002459', self.symbol='BTCUSDT', self.open=25078.4, self.close=25101.9, self.high=25146.6, self.low=25030.1, self.vol=6160.109, self.amt=154602520.4271 
127.0.0.1 - - [20/Feb/2023 00:25:01] "POST / HTTP/1.1" 200 -
2023-02-20 00:25:01,628:INFO:amihud:main.py:172:handleKline:200676: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5760  20230220   000000    000459  ...         0.0        0.0       0
5761  20230220   000500    000959  ...         0.0        0.0       0
5762  20230220   001000    001459  ...         0.0        0.0       0
5763  20230220   001500    001959  ...         0.0        0.0       0
5764  20230220   002000    002459  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-02-20 00:25:01,632:INFO:amihud:main.py:175:handleKline:200676: self.closeSec=1676823899, self.tradeDate='20230220', self.openTime='002000', self.closeTime='002459',self.symbol='BTCUSDT',self.open=25078.4, self.close=25101.9, self.high=25146.6, self.low=25030.1, self.vol=6160.109, self.amt=154602520.4271, ukdf['pct'].iloc[-1]=0.000937 , ukdf['amount'].iloc[-1]=154602520.4271, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5764, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '60.176', 'enterprice': '16529.3', 'countrevence': '0', 'unrealprofit': '-515835.14230525152', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '25101.40752302', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1


## /root/FIL/strategy/factorcheck/log.txt ----- -----

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=231, self.factor=0.45746576585814036, self.count=24882 

self.closeSec=1676823599, self.tradeDate='20230220', self.openTime='001500', self.closeTime='001959', self.symbol='BTCUSDT', self.open=25168.2, self.close=25078.4, self.high=25200.0, self.low=25055.1 
2023-02-20 00:20:01,668:INFO:factorcheck2:main.py:126:handleKline:185239: self.closeSec=1676823599, self.tradeDate='20230220', self.openTime='001500', self.closeTime='001959',self.symbol='BTCUSDT',self.open=25168.2, self.close=25078.4, self.high=25200.0, self.low=25055.1   
2023-02-20 00:20:01,742:INFO:factorcheck2:main.py:127:handleKline:185239: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime    closeSec  ...      low       pct  index  idx
1439  20230219   235500    235959  1676822399  ...  24904.6  0.000052   1727    5
1440  20230220   000000    000459  1676822699  ...  24929.7 -0.000096   1440    0
1441  20230220   000500    000959  1676822999  ...  24901.5  0.000967   1441    1
1442  20230220   001000    001459  1676823299  ...  24950.0  0.009017   1442    2
1443  20230220   001500    001959  1676823599  ...  25055.1 -0.003987   1443    3

[5 rows x 11 columns]
2023-02-20 00:20:01,742:INFO:factorcheck2:main.py:128:handleKline:185239: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}
127.0.0.1 - - [20/Feb/2023 00:25:01] "POST / HTTP/1.1" 200 -

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=231, self.factor=0.45746576585814036, self.count=24883 

self.closeSec=1676823899, self.tradeDate='20230220', self.openTime='002000', self.closeTime='002459', self.symbol='BTCUSDT', self.open=25078.4, self.close=25101.9, self.high=25146.6, self.low=25030.1 
2023-02-20 00:25:01,543:INFO:factorcheck2:main.py:126:handleKline:185239: self.closeSec=1676823899, self.tradeDate='20230220', self.openTime='002000', self.closeTime='002459',self.symbol='BTCUSDT',self.open=25078.4, self.close=25101.9, self.high=25146.6, self.low=25030.1   
2023-02-20 00:25:01,587:INFO:factorcheck2:main.py:127:handleKline:185239: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime    closeSec  ...      low       pct  index  idx
1440  20230220   000000    000459  1676822699  ...  24929.7 -0.000096   1440    0
1441  20230220   000500    000959  1676822999  ...  24901.5  0.000967   1441    1
1442  20230220   001000    001459  1676823299  ...  24950.0  0.009017   1442    2
1443  20230220   001500    001959  1676823599  ...  25055.1 -0.003987   1443    3
1444  20230220   002000    002459  1676823899  ...  25030.1  0.000937   1444    4

[5 rows x 11 columns]
2023-02-20 00:25:01,587:INFO:factorcheck2:main.py:128:handleKline:185239: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}


## /root/FIL/strategy/logic/log.txt ----- -----

2023-02-20 00:00:35,119:DEBUG:logic:main.py:463:getModel:885513: df_s.iloc[-5:,:] :
          date closeTime     open  ...    alpha58   alpha67   alpha72
5802  20230219    212959  24700.4  ...  51.666667  0.540841  0.551449
5803  20230219    215959  24689.3  ...  51.666667  0.535281  0.554510
5804  20230219    222959  24666.1  ...  52.083333  0.549342  0.542621
5805  20230219    225959  24735.7  ...  52.083333  0.553286  0.527744
5806  20230219    232959  24755.6  ...  52.500000  0.563088  0.524649

[5 rows x 33 columns]
0.5055147058823529
acc is : 0.5055147058823529
2023-02-20 00:00:35,283:INFO:logic:main.py:468:getModel:885513: df_pred.iloc[-5:,:] :
     pred    prob_0    prob_1  actual  ...       nav  sign  cost_        bm
539     0  0.504786  0.495214       0  ...  1.113331   1.0    0.0  1.061958
540     1  0.497337  0.502663       1  ...  1.116473   1.0    0.0  1.064955
541     0  0.522721  0.477279       1  ...  1.117371   1.0    0.0  1.065812
542     0  0.515270  0.484730       1  ...  1.119628   1.0    0.0  1.067964
543     0  0.521961  0.478039       1  ...  1.125342   1.0    0.0  1.073415

[5 rows x 10 columns]
2023-02-20 00:00:35,320:INFO:logic:main.py:478:getModel:885513: df_panel.iloc[-5:,:] :
    pred    prob_0    prob_1  actual  ...       nav  sign  cost_        bm
45     0  0.505177  0.494823       0  ...  1.113331   1.0    0.0  1.063442
46     1  0.498408  0.501592       1  ...  1.119478   1.0    0.0  1.066539
47     0  0.523769  0.476231       1  ...  1.120379   1.0    0.0  1.067397
48     0  0.515796  0.484204       1  ...  1.119628   1.0    0.0  1.068134
49     0  0.521961  0.478039       1  ...  1.125342   1.0    0.0  1.073415

[5 rows x 10 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '35.459', 'enterprice': '24163.6', 'countrevence': '0', 'unrealprofit': '27460.91561299551', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '24938.04134389', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}


## /root/FIL/strategy/modifiedmom/log.txt ----- -----

2023-02-20 00:00:03,729:INFO:modifiedmom:main.py:319:handleOrderFilled:185213: handleOrderFilled: data=OrderType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'clientorderid': '41768F1676822403084I0L59', 'symbol': 'BTCUSDT', 'gatewayorderid': 1676822403362378, 'quantity': '38.534', 'price': '24929.7', 'stopprice': '0', 'ordertype': '', 'side': 'SELL', 'status': 'FILLED', 'positionside': 'SHORT', 'createtime': 1676822402542, 'updatetime': 1676822403362, 'tradetype': 'usdt', 'selfid': 41768, 'filltrades': [TradeType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'tradeid': 1676822403362, 'clientorderid': '41768F1676822403084I0L59', 'price': '24929.7', 'quantity': '38.534', 'commission': '960.6410598', 'commissionasset': 'USDT', 'tradetime': 1676822403362, 'tradetype': 'usdt', 'gatetype': 'simulator', 'handletime': 1676822403362}], 'gatetype': 'simulator', 'handletime': 0}
127.0.0.1 - - [20/Feb/2023 00:00:03] "POST / HTTP/1.1" 200 -
127.0.0.1 - - [20/Feb/2023 00:10:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=12440 

self.closeSec=1676822999, self.tradeDate='20230220', self.openTime='000000', self.closeTime='000959', self.symbol='BTCUSDT', self.open='24929.7', self.close='24953.7'
2023-02-20 00:10:01,723:INFO:modifiedmom:main.py:144:handleKline:185213: self.closeSec=1676822999, self.tradeDate='20230220', self.openTime='000000', self.closeTime='000959',self.symbol='BTCUSDT',self.open='24929.7', self.close='24953.7'
2023-02-20 00:10:01,760:INFO:modifiedmom:main.py:145:handleKline:185213: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec     open    close       pct
572  20230219   232000    232959  1676820599  24924.1  24805.5 -0.004758
573  20230219   233000    233959  1676821199  24805.4  24931.6  0.005084
574  20230219   234000    234959  1676821799  24931.6  24862.9 -0.002756
575  20230219   235000    235959  1676822399  24862.9  24932.1  0.002783
576  20230220   000000    000959  1676822999  24929.7  24953.7  0.000866
2023-02-20 00:10:01,760:INFO:modifiedmom:main.py:146:handleKline:185213: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': True, 'isOpen': False, 'isClose': True, 'isTrig': False}

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=12441 

self.closeSec=1676823599, self.tradeDate='20230220', self.openTime='001000', self.closeTime='001959', self.symbol='BTCUSDT', self.open='24953.8', self.close='25078.4'
127.0.0.1 - - [20/Feb/2023 00:20:01] "POST / HTTP/1.1" 200 -
2023-02-20 00:20:01,888:INFO:modifiedmom:main.py:144:handleKline:185213: self.closeSec=1676823599, self.tradeDate='20230220', self.openTime='001000', self.closeTime='001959',self.symbol='BTCUSDT',self.open='24953.8', self.close='25078.4'
2023-02-20 00:20:01,923:INFO:modifiedmom:main.py:145:handleKline:185213: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec     open    close       pct
573  20230219   233000    233959  1676821199  24805.4  24931.6  0.005084
574  20230219   234000    234959  1676821799  24931.6  24862.9 -0.002756
575  20230219   235000    235959  1676822399  24862.9  24932.1  0.002783
576  20230220   000000    000959  1676822999  24929.7  24953.7  0.000866
577  20230220   001000    001959  1676823599  24953.8  25078.4  0.004997
2023-02-20 00:20:01,923:INFO:modifiedmom:main.py:146:handleKline:185213: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': True, 'isOpen': False, 'isClose': True, 'isTrig': False}


## /root/FIL/strategy/percentile_regression_step2/log.txt ----- -----

127.0.0.1 - - [19/Feb/2023 23:00:01] "POST / HTTP/1.1" 200 -
2023-02-19 23:00:02,382:DEBUG:percentile_regression_step2:main.py:154:get_signal:1265985: df_id.iloc[-5:,:] :
                 daytime     hms    close  ...  pct_10  pct_20  factor
144  2023/02/19 20:30:00  203000  24700.5  ...     NaN     NaN       0
145  2023/02/19 21:00:00  210000  24689.4  ...     NaN     NaN       0
146  2023/02/19 21:30:00  213000  24666.0  ...     NaN     NaN       0
147  2023/02/19 22:00:00  220000  24735.6  ...     NaN     NaN       0
148  2023/02/19 22:30:00  223000  24755.5  ...     NaN     NaN       0

[5 rows x 10 columns]
127.0.0.1 - - [19/Feb/2023 23:30:01] "POST / HTTP/1.1" 200 -
2023-02-19 23:30:02,805:DEBUG:percentile_regression_step2:main.py:154:get_signal:1265985: df_id.iloc[-5:,:] :
                 daytime     hms    close  ...  pct_10  pct_20  factor
144  2023/02/19 21:00:00  210000  24689.4  ...     NaN     NaN       0
145  2023/02/19 21:30:00  213000  24666.0  ...     NaN     NaN       0
146  2023/02/19 22:00:00  220000  24735.6  ...     NaN     NaN       0
147  2023/02/19 22:30:00  223000  24755.5  ...     NaN     NaN       0
148  2023/02/19 23:00:00  230000  24805.5  ...     NaN     NaN       0

[5 rows x 10 columns]
127.0.0.1 - - [20/Feb/2023 00:00:01] "POST / HTTP/1.1" 200 -
2023-02-20 00:00:03,273:DEBUG:percentile_regression_step2:main.py:154:get_signal:1265985: df_id.iloc[-5:,:] :
                 daytime     hms    close  ...  pct_10  pct_20  factor
144  2023/02/19 21:30:00  213000  24666.0  ...     NaN     NaN       0
145  2023/02/19 22:00:00  220000  24735.6  ...     NaN     NaN       0
146  2023/02/19 22:30:00  223000  24755.5  ...     NaN     NaN       0
147  2023/02/19 23:00:00  230000  24805.5  ...     NaN     NaN       0
148  2023/02/19 23:30:00  233000  24932.1  ...     NaN     NaN       0

[5 rows x 10 columns]


## /root/FIL/strategy/pyemd/log.txt ----- -----

2023-02-20 00:00:02,357:INFO:pyemd2:main.py:127:handleKline:185189: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}
2023-02-20 00:00:02,510:INFO:pyemd2:main.py:190:insertFactor:185189: curDateTime:2200000, name:pyemd2, symbol:BTCUSDT, tradeDate:20230219, closeTime:235959, close:24932.1, total:979069.1011917, pct_pre:-0.0026395494520197182, thd:0.3310527377095618, side:sell 

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=12441 

self.closeSec=1676822999, self.tradeDate='20230220', self.openTime='000000', self.closeTime='000959', self.symbol='BTCUSDT', self.open='24929.7', self.close='24953.7'
2023-02-20 00:10:01,723:INFO:pyemd2:main.py:125:handleKline:185189: self.closeSec=1676822999, self.tradeDate='20230220', self.openTime='000000', self.closeTime='000959',self.symbol='BTCUSDT',self.open='24929.7', self.close='24953.7'
127.0.0.1 - - [20/Feb/2023 00:10:01] "POST / HTTP/1.1" 200 -
2023-02-20 00:10:01,740:INFO:pyemd2:main.py:126:handleKline:185189: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
17420  20230219   232000    232959  1676820599  24924.1  24805.5
17421  20230219   233000    233959  1676821199  24805.4  24931.6
17422  20230219   234000    234959  1676821799  24931.6  24862.9
17423  20230219   235000    235959  1676822399  24862.9  24932.1
17424  20230220   000000    000959  1676822999  24929.7  24953.7
2023-02-20 00:10:01,741:INFO:pyemd2:main.py:127:handleKline:185189: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=12442 

self.closeSec=1676823599, self.tradeDate='20230220', self.openTime='001000', self.closeTime='001959', self.symbol='BTCUSDT', self.open='24953.8', self.close='25078.4'
127.0.0.1 - - [20/Feb/2023 00:20:01] "POST / HTTP/1.1" 200 -
2023-02-20 00:20:01,893:INFO:pyemd2:main.py:125:handleKline:185189: self.closeSec=1676823599, self.tradeDate='20230220', self.openTime='001000', self.closeTime='001959',self.symbol='BTCUSDT',self.open='24953.8', self.close='25078.4'
2023-02-20 00:20:01,931:INFO:pyemd2:main.py:126:handleKline:185189: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
17421  20230219   233000    233959  1676821199  24805.4  24931.6
17422  20230219   234000    234959  1676821799  24931.6  24862.9
17423  20230219   235000    235959  1676822399  24862.9  24932.1
17424  20230220   000000    000959  1676822999  24929.7  24953.7
17425  20230220   001000    001959  1676823599  24953.8  25078.4
2023-02-20 00:20:01,932:INFO:pyemd2:main.py:127:handleKline:185189: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}


## /root/FIL/strategy/similarity/log.txt ----- -----

127.0.0.1 - - [20/Feb/2023 00:00:03] "POST / HTTP/1.1" 200 -
2023-02-20 00:00:03,919:INFO:testStrategy:main.py:308:handleOrderFilled:185174: handleOrderFilled: data=OrderType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'clientorderid': '41769F1676822403232I0L2', 'symbol': 'BTCUSDT', 'gatewayorderid': 1676822403362600, 'quantity': '48.424', 'price': '24929.8', 'stopprice': '0', 'ordertype': '', 'side': 'BUY', 'status': 'FILLED', 'positionside': 'LONG', 'createtime': 1676822402622, 'updatetime': 1676822403362, 'tradetype': 'usdt', 'selfid': 41769, 'filltrades': [TradeType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'tradeid': 1676822403362, 'clientorderid': '41769F1676822403232I0L2', 'price': '24929.8', 'quantity': '48.424', 'commission': '1207.2006352', 'commissionasset': 'USDT', 'tradetime': 1676822403362, 'tradetype': 'usdt', 'gatetype': 'simulator', 'handletime': 1676822403362}], 'gatetype': 'simulator', 'handletime': 0}

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=12441 

self.closeSec=1676822999, self.tradeDate='20230220', self.openTime='000000', self.closeTime='000959', self.symbol='BTCUSDT', self.open='24929.7', self.close='24953.7'
2023-02-20 00:10:01,683:INFO:testStrategy:main.py:101:handleKline:185174: self.closeSec=1676822999, self.tradeDate='20230220', self.openTime='000000', self.closeTime='000959',self.symbol='BTCUSDT',self.open='24929.7', self.close='24953.7'
127.0.0.1 - - [20/Feb/2023 00:10:01] "POST / HTTP/1.1" 200 -
2023-02-20 00:10:01,707:INFO:testStrategy:main.py:102:handleKline:185174: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
12236  20230219   232000    232959  1676820599  24924.1  24805.5
12237  20230219   233000    233959  1676821199  24805.4  24931.6
12238  20230219   234000    234959  1676821799  24931.6  24862.9
12239  20230219   235000    235959  1676822399  24862.9  24932.1
12240  20230220   000000    000959  1676822999  24929.7  24953.7
2023-02-20 00:10:01,710:INFO:testStrategy:main.py:103:handleKline:185174: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': True, 'isOpen': False, 'isClose': True, 'isTrig': False, 'isCorr': False}

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=12442 

self.closeSec=1676823599, self.tradeDate='20230220', self.openTime='001000', self.closeTime='001959', self.symbol='BTCUSDT', self.open='24953.8', self.close='25078.4'
127.0.0.1 - - [20/Feb/2023 00:20:01] "POST / HTTP/1.1" 200 -
2023-02-20 00:20:01,902:INFO:testStrategy:main.py:101:handleKline:185174: self.closeSec=1676823599, self.tradeDate='20230220', self.openTime='001000', self.closeTime='001959',self.symbol='BTCUSDT',self.open='24953.8', self.close='25078.4'
2023-02-20 00:20:01,933:INFO:testStrategy:main.py:102:handleKline:185174: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
12237  20230219   233000    233959  1676821199  24805.4  24931.6
12238  20230219   234000    234959  1676821799  24931.6  24862.9
12239  20230219   235000    235959  1676822399  24862.9  24932.1
12240  20230220   000000    000959  1676822999  24929.7  24953.7
12241  20230220   001000    001959  1676823599  24953.8  25078.4
2023-02-20 00:20:01,933:INFO:testStrategy:main.py:103:handleKline:185174: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': True, 'isOpen': False, 'isClose': True, 'isTrig': False, 'isCorr': False}


## /root/FIL/strategy/sr_min/log.txt ----- -----

--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=0, self.total=1000000.0, self.flagDict['side']='', self.tradeCount=0, self.count=20314
self.closeSec=1676823599, self.tradeDate='20230220', self.openTime='001500', self.closeTime='001959', self.symbol='BTCUSDT', self.open=25168.2, self.close=25078.4, self.high=25200.0, self.low=25055.1, self.vol=9559.1, self.amt=240069409.4716 
127.0.0.1 - - [20/Feb/2023 00:20:01] "POST / HTTP/1.1" 200 -
2023-02-20 00:20:01,790:INFO:sr_min:main.py:172:handleKline:449472: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5759  20230219   235500    235959  ...         0.0        0.0       0
5760  20230220   000000    000459  ...         0.0        0.0       0
5761  20230220   000500    000959  ...         0.0        0.0       0
5762  20230220   001000    001459  ...         0.0        0.0       0
5763  20230220   001500    001959  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-02-20 00:20:01,792:INFO:sr_min:main.py:175:handleKline:449472: self.closeSec=1676823599, self.tradeDate='20230220', self.openTime='001500', self.closeTime='001959',self.symbol='BTCUSDT',self.open=25168.2, self.close=25078.4, self.high=25200.0, self.low=25055.1, self.vol=9559.1, self.amt=240069409.4716, ukdf['pct'].iloc[-1]=-0.003987 , ukdf['amount'].iloc[-1]=240069409.4716, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5763, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': []}
type(curSign)=<class 'int'>, curSign=0, self.sign=0
--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=0, self.total=1000000.0, self.flagDict['side']='', self.tradeCount=0, self.count=20315
self.closeSec=1676823899, self.tradeDate='20230220', self.openTime='002000', self.closeTime='002459', self.symbol='BTCUSDT', self.open=25078.4, self.close=25101.9, self.high=25146.6, self.low=25030.1, self.vol=6160.109, self.amt=154602520.4271 
127.0.0.1 - - [20/Feb/2023 00:25:01] "POST / HTTP/1.1" 200 -
2023-02-20 00:25:01,622:INFO:sr_min:main.py:172:handleKline:449472: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5760  20230220   000000    000459  ...         0.0        0.0       0
5761  20230220   000500    000959  ...         0.0        0.0       0
5762  20230220   001000    001459  ...         0.0        0.0       0
5763  20230220   001500    001959  ...         0.0        0.0       0
5764  20230220   002000    002459  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-02-20 00:25:01,628:INFO:sr_min:main.py:175:handleKline:449472: self.closeSec=1676823899, self.tradeDate='20230220', self.openTime='002000', self.closeTime='002459',self.symbol='BTCUSDT',self.open=25078.4, self.close=25101.9, self.high=25146.6, self.low=25030.1, self.vol=6160.109, self.amt=154602520.4271, ukdf['pct'].iloc[-1]=0.000937 , ukdf['amount'].iloc[-1]=154602520.4271, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5764, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': []}
type(curSign)=<class 'int'>, curSign=0, self.sign=0


## /root/FIL/strategy/s_rsrs/log.txt ----- -----

721  20230219   040000    075959  ...   22736.718  5.595636e+08  0.001089
722  20230219   080000    115959  ...   29006.051  7.166029e+08  0.002034
723  20230219   120000    155959  ...   59061.967  1.459276e+09 -0.004468
724  20230219   160000    195959  ...   34964.341  8.610220e+08  0.003609
725  20230219   200000    235959  ...  103278.998  2.564951e+09  0.010813

[5 rows x 11 columns]
2023-02-20 00:00:04,756:INFO:s_rsrs:main.py:151:handleKline:185271: df_s.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec  ...  index      beta    zscore  signal
721  20230219   040000    075959  1676764799  ...    721  0.922795  0.690896     1.0
722  20230219   080000    115959  1676779199  ...    722  0.831049  0.434007     NaN
723  20230219   120000    155959  1676793599  ...    723  0.730658  0.154030     NaN
724  20230219   160000    195959  1676807999  ...    724  0.569196 -0.293501     NaN
725  20230219   200000    235959  1676822399  ...    725  0.433753 -0.664721    -1.0

[5 rows x 15 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '36.518', 'enterprice': '23318.2', 'countrevence': '0', 'unrealprofit': '58829.48841278178', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '24929.17235371', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'numpy.int64'>, curSign=-1, self.sign=1
handlebackTrade > queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '36.518', 'enterprice': '23318.2', 'countrevence': '0', 'unrealprofit': '58829.48841278178', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '24929.17235371', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
2023-02-20 00:00:10,581:INFO:s_rsrs:main.py:182:queryContractAssets:185271: queryContractAssets: assets=ContractAssetReturn{'result': [ContractAsset{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'asset': 'USDT', 'free': '911894.5464177', 'total': '911894.5464177', 'margin': '0', 'unreal': '0', 'type': 'AssetType_ucontract'}]}
2023-02-20 00:00:10,860:INFO:s_rsrs:main.py:269:openSell:185271: ret = self.client.insertMarketUOrder("simulator", "BTCUSDT", 36.465, "sell"), ret=InsertOrderReturn{'result': 'success', 'clientorderid': '41771F1676822410858I0L65'}
2023-02-20 00:00:10,876:INFO:s_rsrs:main.py:176:insertFactor:185271: curDateTime:2200000, name:s_rsrs, symbol:BTCUSDT, tradeDate:20230219, closeTime:235959, close:24932.1, sign:-1, total:911894.5464177, side:sell  
127.0.0.1 - - [20/Feb/2023 00:00:10] "POST / HTTP/1.1" 200 -
127.0.0.1 - - [20/Feb/2023 00:00:10] "POST / HTTP/1.1" 200 -
2023-02-20 00:00:10,881:INFO:s_rsrs:main.py:343:handleOrderNew:185271: handleOrderNew: data=OrderType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'clientorderid': '41770F1676822405417I0L65', 'symbol': 'BTCUSDT', 'gatewayorderid': 1676822405528150, 'quantity': '36.518', 'price': '24929.7', 'stopprice': '0', 'ordertype': '', 'side': 'SELL', 'status': 'FILLED', 'positionside': 'SHORT', 'createtime': 1676822405066, 'updatetime': 1676822405528, 'tradetype': 'usdt', 'selfid': 41770, 'filltrades': [TradeType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'tradeid': 1676822405528, 'clientorderid': '41770F1676822405417I0L65', 'price': '24929.7', 'quantity': '36.518', 'commission': '910.3827846', 'commissionasset': 'USDT', 'tradetime': 1676822405528, 'tradetype': 'usdt', 'gatetype': 'simulator', 'handletime': 1676822405528}], 'gatetype': 'simulator', 'handletime': 0}
2023-02-20 00:00:10,882:INFO:s_rsrs:main.py:346:handleOrderFilled:185271: handleOrderFilled: data=OrderType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'clientorderid': '41770F1676822405417I0L65', 'symbol': 'BTCUSDT', 'gatewayorderid': 1676822405528150, 'quantity': '36.518', 'price': '24929.7', 'stopprice': '0', 'ordertype': '', 'side': 'SELL', 'status': 'FILLED', 'positionside': 'SHORT', 'createtime': 1676822405066, 'updatetime': 1676822405528, 'tradetype': 'usdt', 'selfid': 41770, 'filltrades': [TradeType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'tradeid': 1676822405528, 'clientorderid': '41770F1676822405417I0L65', 'price': '24929.7', 'quantity': '36.518', 'commission': '910.3827846', 'commissionasset': 'USDT', 'tradetime': 1676822405528, 'tradetype': 'usdt', 'gatetype': 'simulator', 'handletime': 1676822405528}], 'gatetype': 'simulator', 'handletime': 0}
2023-02-20 00:00:11,022:INFO:s_rsrs:main.py:343:handleOrderNew:185271: handleOrderNew: data=OrderType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'clientorderid': '41771F1676822410858I0L65', 'symbol': 'BTCUSDT', 'gatewayorderid': 1676822410983436, 'quantity': '36.465', 'price': '24934.8', 'stopprice': '0', 'ordertype': '', 'side': 'SELL', 'status': 'FILLED', 'positionside': 'SHORT', 'createtime': 1676822410594, 'updatetime': 1676822410983, 'tradetype': 'usdt', 'selfid': 41771, 'filltrades': [TradeType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'tradeid': 1676822410983, 'clientorderid': '41771F1676822410858I0L65', 'price': '24934.8', 'quantity': '36.465', 'commission': '909.247482', 'commissionasset': 'USDT', 'tradetime': 1676822410983, 'tradetype': 'usdt', 'gatetype': 'simulator', 'handletime': 1676822410983}], 'gatetype': 'simulator', 'handletime': 0}
127.0.0.1 - - [20/Feb/2023 00:00:11] "POST / HTTP/1.1" 200 -
2023-02-20 00:00:11,274:INFO:s_rsrs:main.py:346:handleOrderFilled:185271: handleOrderFilled: data=OrderType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'clientorderid': '41771F1676822410858I0L65', 'symbol': 'BTCUSDT', 'gatewayorderid': 1676822410983436, 'quantity': '36.465', 'price': '24934.8', 'stopprice': '0', 'ordertype': '', 'side': 'SELL', 'status': 'FILLED', 'positionside': 'SHORT', 'createtime': 1676822410594, 'updatetime': 1676822410983, 'tradetype': 'usdt', 'selfid': 41771, 'filltrades': [TradeType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'tradeid': 1676822410983, 'clientorderid': '41771F1676822410858I0L65', 'price': '24934.8', 'quantity': '36.465', 'commission': '909.247482', 'commissionasset': 'USDT', 'tradetime': 1676822410983, 'tradetype': 'usdt', 'gatetype': 'simulator', 'handletime': 1676822410983}], 'gatetype': 'simulator', 'handletime': 0}
127.0.0.1 - - [20/Feb/2023 00:00:11] "POST / HTTP/1.1" 200 -


