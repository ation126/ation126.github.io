# 20230224 00:26:01

## /root/FIL/strategy/amihud/log.txt ----- -----

127.0.0.1 - - [24/Feb/2023 00:20:01] "POST / HTTP/1.1" 200 -
--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=993672.4896432, self.flagDict['side']='sell', self.tradeCount=2, self.count=25468
self.closeSec=1677169199, self.tradeDate='20230224', self.openTime='001500', self.closeTime='001959', self.symbol='BTCUSDT', self.open=23907.1, self.close=23864.4, self.high=23923.7, self.low=23859.6, self.vol=2768.989, self.amt=66164314.6437 
2023-02-24 00:20:01,691:INFO:amihud:main.py:172:handleKline:200676: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5759  20230223   235500    235959  ...         0.0        0.0       0
5760  20230224   000000    000459  ...         0.0        0.0       0
5761  20230224   000500    000959  ...         0.0        0.0       0
5762  20230224   001000    001459  ...         0.0        0.0       0
5763  20230224   001500    001959  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-02-24 00:20:01,698:INFO:amihud:main.py:175:handleKline:200676: self.closeSec=1677169199, self.tradeDate='20230224', self.openTime='001500', self.closeTime='001959',self.symbol='BTCUSDT',self.open=23907.1, self.close=23864.4, self.high=23923.7, self.low=23859.6, self.vol=2768.989, self.amt=66164314.6437, ukdf['pct'].iloc[-1]=-0.001786 , ukdf['amount'].iloc[-1]=66164314.6437, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5763, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '60.176', 'enterprice': '16529.3', 'countrevence': '0', 'unrealprofit': '-441390.96', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '23864.3', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1
--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=993672.4896432, self.flagDict['side']='sell', self.tradeCount=2, self.count=25469
self.closeSec=1677169499, self.tradeDate='20230224', self.openTime='002000', self.closeTime='002459', self.symbol='BTCUSDT', self.open=23864.3, self.close=23919.6, self.high=23925.0, self.low=23850.0, self.vol=2666.979, self.amt=63705183.2307 
127.0.0.1 - - [24/Feb/2023 00:25:01] "POST / HTTP/1.1" 200 -
2023-02-24 00:25:01,754:INFO:amihud:main.py:172:handleKline:200676: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5760  20230224   000000    000459  ...         0.0        0.0       0
5761  20230224   000500    000959  ...         0.0        0.0       0
5762  20230224   001000    001459  ...         0.0        0.0       0
5763  20230224   001500    001959  ...         0.0        0.0       0
5764  20230224   002000    002459  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-02-24 00:25:01,754:INFO:amihud:main.py:175:handleKline:200676: self.closeSec=1677169499, self.tradeDate='20230224', self.openTime='002000', self.closeTime='002459',self.symbol='BTCUSDT',self.open=23864.3, self.close=23919.6, self.high=23925.0, self.low=23850.0, self.vol=2666.979, self.amt=63705183.2307, ukdf['pct'].iloc[-1]=0.002313 , ukdf['amount'].iloc[-1]=63705183.2307, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5764, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '60.176', 'enterprice': '16529.3', 'countrevence': '0', 'unrealprofit': '-444820.992', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '23921.3', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1


## /root/FIL/strategy/factorcheck/log.txt ----- -----

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=26, self.factor=0.5183452230433916, self.count=26034 

self.closeSec=1677169199, self.tradeDate='20230224', self.openTime='001500', self.closeTime='001959', self.symbol='BTCUSDT', self.open=23907.1, self.close=23864.4, self.high=23923.7, self.low=23859.6 
2023-02-24 00:20:01,562:INFO:factorcheck2:main.py:126:handleKline:185239: self.closeSec=1677169199, self.tradeDate='20230224', self.openTime='001500', self.closeTime='001959',self.symbol='BTCUSDT',self.open=23907.1, self.close=23864.4, self.high=23923.7, self.low=23859.6   
2023-02-24 00:20:01,627:INFO:factorcheck2:main.py:127:handleKline:185239: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime    closeSec  ...      low       pct  index  idx
1439  20230223   235500    235959  1677167999  ...  23914.1 -0.000205   1727    5
1440  20230224   000000    000459  1677168299  ...  23931.9  0.000443   1440    0
1441  20230224   000500    000959  1677168599  ...  23885.0 -0.002125   1441    1
1442  20230224   001000    001459  1677168899  ...  23894.7  0.000310   1442    2
1443  20230224   001500    001959  1677169199  ...  23859.6 -0.001786   1443    3

[5 rows x 11 columns]
2023-02-24 00:20:01,628:INFO:factorcheck2:main.py:128:handleKline:185239: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': True, 'isOpenSell': False, 'isCloseBuy': False, 'isCloseSell': False, 'isOpen': True, 'isClose': False, 'isTrig': True}

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=26, self.factor=0.5183452230433916, self.count=26035 

self.closeSec=1677169499, self.tradeDate='20230224', self.openTime='002000', self.closeTime='002459', self.symbol='BTCUSDT', self.open=23864.3, self.close=23919.6, self.high=23925.0, self.low=23850.0 
2023-02-24 00:25:01,651:INFO:factorcheck2:main.py:126:handleKline:185239: self.closeSec=1677169499, self.tradeDate='20230224', self.openTime='002000', self.closeTime='002459',self.symbol='BTCUSDT',self.open=23864.3, self.close=23919.6, self.high=23925.0, self.low=23850.0   
127.0.0.1 - - [24/Feb/2023 00:25:01] "POST / HTTP/1.1" 200 -
2023-02-24 00:25:01,674:INFO:factorcheck2:main.py:127:handleKline:185239: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime    closeSec  ...      low       pct  index  idx
1440  20230224   000000    000459  1677168299  ...  23931.9  0.000443   1440    0
1441  20230224   000500    000959  1677168599  ...  23885.0 -0.002125   1441    1
1442  20230224   001000    001459  1677168899  ...  23894.7  0.000310   1442    2
1443  20230224   001500    001959  1677169199  ...  23859.6 -0.001786   1443    3
1444  20230224   002000    002459  1677169499  ...  23850.0  0.002313   1444    4

[5 rows x 11 columns]
2023-02-24 00:25:01,674:INFO:factorcheck2:main.py:128:handleKline:185239: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': True, 'isOpenSell': False, 'isCloseBuy': False, 'isCloseSell': False, 'isOpen': True, 'isClose': False, 'isTrig': True}


## /root/FIL/strategy/logic/log.txt ----- -----

2023-02-24 00:00:35,991:DEBUG:logic:main.py:463:getModel:885513: df_s.iloc[-5:,:] :
          date closeTime     open  ...    alpha58   alpha67   alpha72
5802  20230223    212959  23900.4  ...  48.750000  0.485436  0.405050
5803  20230223    215959  24133.3  ...  48.750000  0.467836  0.417239
5804  20230223    222959  24001.3  ...  48.750000  0.472629  0.426450
5805  20230223    225959  24033.8  ...  48.333333  0.467799  0.437479
5806  20230223    232959  23997.4  ...  48.333333  0.465492  0.448928

[5 rows x 33 columns]
0.5257352941176471
acc is : 0.5257352941176471
2023-02-24 00:00:36,182:INFO:logic:main.py:468:getModel:885513: df_pred.iloc[-5:,:] :
     pred    prob_0    prob_1  actual  ...       nav  sign  cost_        bm
539     0  0.544783  0.455217       0  ...  1.052399  -1.0    0.0  1.101573
540     0  0.504397  0.495603       1  ...  1.050979  -1.0    0.0  1.103060
541     0  0.539935  0.460065       0  ...  1.052570  -1.0    0.0  1.101390
542     0  0.520739  0.479261       0  ...  1.053329  -1.0    0.0  1.100596
543     0  0.515839  0.484161       0  ...  1.055086  -1.0    0.0  1.098760

[5 rows x 10 columns]
2023-02-24 00:00:36,205:INFO:logic:main.py:478:getModel:885513: df_panel.iloc[-5:,:] :
    pred    prob_0    prob_1  actual  ...       nav  sign  cost_        bm
45     0  0.544402  0.455598       0  ...  1.052399  -1.0    0.0  1.101376
46     0  0.503552  0.496448       1  ...  1.011411  -1.0    0.0  1.102317
47     0  0.539672  0.460328       0  ...  1.052570  -1.0    0.0  1.100647
48     0  0.520271  0.479729       0  ...  1.013673  -1.0    0.0  1.100081
49     0  0.515839  0.484161       0  ...  1.055086  -1.0    0.0  1.098760

[5 rows x 10 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '33.736', 'enterprice': '23749.2', 'countrevence': '0', 'unrealprofit': '-6686.4752', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '23947.4', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}


## /root/FIL/strategy/modifiedmom/log.txt ----- -----

127.0.0.1 - - [24/Feb/2023 00:00:03] "POST / HTTP/1.1" 200 -
2023-02-24 00:00:03,333:INFO:modifiedmom:main.py:319:handleOrderFilled:185213: handleOrderFilled: data=OrderType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'clientorderid': '41810F1677168002875I0L59', 'symbol': 'BTCUSDT', 'gatewayorderid': 1677168003042043, 'quantity': '39.592', 'price': '23934.6', 'stopprice': '0', 'ordertype': '', 'side': 'BUY', 'status': 'FILLED', 'positionside': 'LONG', 'createtime': 1677168002409, 'updatetime': 1677168003042, 'tradetype': 'usdt', 'selfid': 41810, 'filltrades': [TradeType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'tradeid': 1677168003042, 'clientorderid': '41810F1677168002875I0L59', 'price': '23934.6', 'quantity': '39.592', 'commission': '947.6186832', 'commissionasset': 'USDT', 'tradetime': 1677168003042, 'tradetype': 'usdt', 'gatetype': 'simulator', 'handletime': 1677168003042}], 'gatetype': 'simulator', 'handletime': 0}

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=13016 

self.closeSec=1677168599, self.tradeDate='20230224', self.openTime='000000', self.closeTime='000959', self.symbol='BTCUSDT', self.open='23940', self.close='23899.7'
127.0.0.1 - - [24/Feb/2023 00:10:01] "POST / HTTP/1.1" 200 -
2023-02-24 00:10:01,782:INFO:modifiedmom:main.py:144:handleKline:185213: self.closeSec=1677168599, self.tradeDate='20230224', self.openTime='000000', self.closeTime='000959',self.symbol='BTCUSDT',self.open='23940', self.close='23899.7'
2023-02-24 00:10:01,794:INFO:modifiedmom:main.py:145:handleKline:185213: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec     open    close       pct
572  20230223   232000    232959  1677166199  23897.8  23980.1  0.003511
573  20230223   233000    233959  1677166799  23980.1  24014.1  0.001418
574  20230223   234000    234959  1677167399    24014  23923.3 -0.003781
575  20230223   235000    235959  1677167999  23923.4    23940  0.000698
576  20230224   000000    000959  1677168599    23940  23899.7 -0.001683
2023-02-24 00:10:01,794:INFO:modifiedmom:main.py:146:handleKline:185213: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': True, 'isOpen': False, 'isClose': True, 'isTrig': False}

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=13017 

self.closeSec=1677169199, self.tradeDate='20230224', self.openTime='001000', self.closeTime='001959', self.symbol='BTCUSDT', self.open='23899.7', self.close='23864.4'
127.0.0.1 - - [24/Feb/2023 00:20:01] "POST / HTTP/1.1" 200 -
2023-02-24 00:20:01,665:INFO:modifiedmom:main.py:144:handleKline:185213: self.closeSec=1677169199, self.tradeDate='20230224', self.openTime='001000', self.closeTime='001959',self.symbol='BTCUSDT',self.open='23899.7', self.close='23864.4'
2023-02-24 00:20:01,764:INFO:modifiedmom:main.py:145:handleKline:185213: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec     open    close       pct
573  20230223   233000    233959  1677166799  23980.1  24014.1  0.001418
574  20230223   234000    234959  1677167399    24014  23923.3 -0.003781
575  20230223   235000    235959  1677167999  23923.4    23940  0.000698
576  20230224   000000    000959  1677168599    23940  23899.7 -0.001683
577  20230224   001000    001959  1677169199  23899.7  23864.4 -0.001477
2023-02-24 00:20:01,765:INFO:modifiedmom:main.py:146:handleKline:185213: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': True, 'isOpen': False, 'isClose': True, 'isTrig': False}


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

2023-02-24 00:00:02,167:INFO:pyemd2:main.py:127:handleKline:185189: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}
2023-02-24 00:00:02,419:INFO:pyemd2:main.py:190:insertFactor:185189: curDateTime:2240000, name:pyemd2, symbol:BTCUSDT, tradeDate:20230223, closeTime:235959, close:23940, total:979069.1011917, pct_pre:0.022738667531778, thd:-0.1868240846344535, side:sell 

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=13017 

self.closeSec=1677168599, self.tradeDate='20230224', self.openTime='000000', self.closeTime='000959', self.symbol='BTCUSDT', self.open='23940', self.close='23899.7'
2023-02-24 00:10:01,776:INFO:pyemd2:main.py:125:handleKline:185189: self.closeSec=1677168599, self.tradeDate='20230224', self.openTime='000000', self.closeTime='000959',self.symbol='BTCUSDT',self.open='23940', self.close='23899.7'
127.0.0.1 - - [24/Feb/2023 00:10:01] "POST / HTTP/1.1" 200 -
2023-02-24 00:10:01,801:INFO:pyemd2:main.py:126:handleKline:185189: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
17420  20230223   232000    232959  1677166199  23897.8  23980.1
17421  20230223   233000    233959  1677166799  23980.1  24014.1
17422  20230223   234000    234959  1677167399    24014  23923.3
17423  20230223   235000    235959  1677167999  23923.4    23940
17424  20230224   000000    000959  1677168599    23940  23899.7
2023-02-24 00:10:01,802:INFO:pyemd2:main.py:127:handleKline:185189: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}
127.0.0.1 - - [24/Feb/2023 00:20:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=13018 

self.closeSec=1677169199, self.tradeDate='20230224', self.openTime='001000', self.closeTime='001959', self.symbol='BTCUSDT', self.open='23899.7', self.close='23864.4'
2023-02-24 00:20:01,738:INFO:pyemd2:main.py:125:handleKline:185189: self.closeSec=1677169199, self.tradeDate='20230224', self.openTime='001000', self.closeTime='001959',self.symbol='BTCUSDT',self.open='23899.7', self.close='23864.4'
2023-02-24 00:20:01,788:INFO:pyemd2:main.py:126:handleKline:185189: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
17421  20230223   233000    233959  1677166799  23980.1  24014.1
17422  20230223   234000    234959  1677167399    24014  23923.3
17423  20230223   235000    235959  1677167999  23923.4    23940
17424  20230224   000000    000959  1677168599    23940  23899.7
17425  20230224   001000    001959  1677169199  23899.7  23864.4
2023-02-24 00:20:01,788:INFO:pyemd2:main.py:127:handleKline:185189: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}


## /root/FIL/strategy/similarity/log.txt ----- -----

127.0.0.1 - - [24/Feb/2023 00:00:03] "POST / HTTP/1.1" 200 -
2023-02-24 00:00:03,512:INFO:testStrategy:main.py:308:handleOrderFilled:185174: handleOrderFilled: data=OrderType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'clientorderid': '41809F1677168002861I0L2', 'symbol': 'BTCUSDT', 'gatewayorderid': 1677168003136452, 'quantity': '47.965', 'price': '23934.5', 'stopprice': '0', 'ordertype': '', 'side': 'SELL', 'status': 'FILLED', 'positionside': 'SHORT', 'createtime': 1677168002449, 'updatetime': 1677168003136, 'tradetype': 'usdt', 'selfid': 41809, 'filltrades': [TradeType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'tradeid': 1677168003136, 'clientorderid': '41809F1677168002861I0L2', 'price': '23934.5', 'quantity': '47.965', 'commission': '1148.0182925', 'commissionasset': 'USDT', 'tradetime': 1677168003136, 'tradetype': 'usdt', 'gatetype': 'simulator', 'handletime': 1677168003136}], 'gatetype': 'simulator', 'handletime': 0}

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=13017 

self.closeSec=1677168599, self.tradeDate='20230224', self.openTime='000000', self.closeTime='000959', self.symbol='BTCUSDT', self.open='23940', self.close='23899.7'
127.0.0.1 - - [24/Feb/2023 00:10:01] "POST / HTTP/1.1" 200 -
2023-02-24 00:10:01,765:INFO:testStrategy:main.py:101:handleKline:185174: self.closeSec=1677168599, self.tradeDate='20230224', self.openTime='000000', self.closeTime='000959',self.symbol='BTCUSDT',self.open='23940', self.close='23899.7'
2023-02-24 00:10:01,795:INFO:testStrategy:main.py:102:handleKline:185174: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
12236  20230223   232000    232959  1677166199  23897.8  23980.1
12237  20230223   233000    233959  1677166799  23980.1  24014.1
12238  20230223   234000    234959  1677167399    24014  23923.3
12239  20230223   235000    235959  1677167999  23923.4    23940
12240  20230224   000000    000959  1677168599    23940  23899.7
2023-02-24 00:10:01,795:INFO:testStrategy:main.py:103:handleKline:185174: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': True, 'isOpen': False, 'isClose': True, 'isTrig': False, 'isCorr': False}

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=13018 

self.closeSec=1677169199, self.tradeDate='20230224', self.openTime='001000', self.closeTime='001959', self.symbol='BTCUSDT', self.open='23899.7', self.close='23864.4'
127.0.0.1 - - [24/Feb/2023 00:20:01] "POST / HTTP/1.1" 200 -
2023-02-24 00:20:01,702:INFO:testStrategy:main.py:101:handleKline:185174: self.closeSec=1677169199, self.tradeDate='20230224', self.openTime='001000', self.closeTime='001959',self.symbol='BTCUSDT',self.open='23899.7', self.close='23864.4'
2023-02-24 00:20:01,775:INFO:testStrategy:main.py:102:handleKline:185174: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
12237  20230223   233000    233959  1677166799  23980.1  24014.1
12238  20230223   234000    234959  1677167399    24014  23923.3
12239  20230223   235000    235959  1677167999  23923.4    23940
12240  20230224   000000    000959  1677168599    23940  23899.7
12241  20230224   001000    001959  1677169199  23899.7  23864.4
2023-02-24 00:20:01,775:INFO:testStrategy:main.py:103:handleKline:185174: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': True, 'isOpen': False, 'isClose': True, 'isTrig': False, 'isCorr': False}


## /root/FIL/strategy/sr_min/log.txt ----- -----

--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=0, self.total=1000000.0, self.flagDict['side']='', self.tradeCount=0, self.count=21466
self.closeSec=1677169199, self.tradeDate='20230224', self.openTime='001500', self.closeTime='001959', self.symbol='BTCUSDT', self.open=23907.1, self.close=23864.4, self.high=23923.7, self.low=23859.6, self.vol=2768.989, self.amt=66164314.6437 
127.0.0.1 - - [24/Feb/2023 00:20:01] "POST / HTTP/1.1" 200 -
2023-02-24 00:20:01,667:INFO:sr_min:main.py:172:handleKline:449472: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5759  20230223   235500    235959  ...         0.0        0.0       0
5760  20230224   000000    000459  ...         0.0        0.0       0
5761  20230224   000500    000959  ...         0.0        0.0       0
5762  20230224   001000    001459  ...         0.0        0.0       0
5763  20230224   001500    001959  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-02-24 00:20:01,674:INFO:sr_min:main.py:175:handleKline:449472: self.closeSec=1677169199, self.tradeDate='20230224', self.openTime='001500', self.closeTime='001959',self.symbol='BTCUSDT',self.open=23907.1, self.close=23864.4, self.high=23923.7, self.low=23859.6, self.vol=2768.989, self.amt=66164314.6437, ukdf['pct'].iloc[-1]=-0.001786 , ukdf['amount'].iloc[-1]=66164314.6437, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5763, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': []}
type(curSign)=<class 'int'>, curSign=0, self.sign=0
127.0.0.1 - - [24/Feb/2023 00:25:01] "POST / HTTP/1.1" 200 -
--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=0, self.total=1000000.0, self.flagDict['side']='', self.tradeCount=0, self.count=21467
self.closeSec=1677169499, self.tradeDate='20230224', self.openTime='002000', self.closeTime='002459', self.symbol='BTCUSDT', self.open=23864.3, self.close=23919.6, self.high=23925.0, self.low=23850.0, self.vol=2666.979, self.amt=63705183.2307 
2023-02-24 00:25:01,770:INFO:sr_min:main.py:172:handleKline:449472: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5760  20230224   000000    000459  ...         0.0        0.0       0
5761  20230224   000500    000959  ...         0.0        0.0       0
5762  20230224   001000    001459  ...         0.0        0.0       0
5763  20230224   001500    001959  ...         0.0        0.0       0
5764  20230224   002000    002459  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-02-24 00:25:01,772:INFO:sr_min:main.py:175:handleKline:449472: self.closeSec=1677169499, self.tradeDate='20230224', self.openTime='002000', self.closeTime='002459',self.symbol='BTCUSDT',self.open=23864.3, self.close=23919.6, self.high=23925.0, self.low=23850.0, self.vol=2666.979, self.amt=63705183.2307, ukdf['pct'].iloc[-1]=0.002313 , ukdf['amount'].iloc[-1]=63705183.2307, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5764, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': []}
type(curSign)=<class 'int'>, curSign=0, self.sign=0


## /root/FIL/strategy/s_rsrs/log.txt ----- -----

723  20230223   120000    155959  1677139199  ...    723  0.515010 -0.206087     NaN
724  20230223   160000    195959  1677153599  ...    724  0.446420 -0.377574     NaN

[5 rows x 15 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '36.465', 'enterprice': '24934.8', 'countrevence': '0', 'unrealprofit': '42514.5435', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '23768.9', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'numpy.int64'>, curSign=-9223372036854775808, self.sign=-1
--handleKline--:  version='2.0.0', self.name='s_rsrs', self.symbol='BTCUSDT', interval='4h', intervalSec=14400, wid=25, thd=0.6, self.sign=-1, self.total=908338.234518, self.flagDict['side']='sell', self.tradeCount=21, self.count=542
self.closeSec=1677167999, self.tradeDate='20230223', self.openTime='200000', self.closeTime='235959', self.symbol='BTCUSDT', self.open=23767.6, self.close=23940.0, self.high=24215.0, self.low=23590.0, self.vol=246653.418, self.amt=5911671167.71542 
127.0.0.1 - - [24/Feb/2023 00:00:01] "POST / HTTP/1.1" 200 -
2023-02-24 00:00:01,995:INFO:s_rsrs:main.py:141:handleKline:185271: self.closeSec=1677167999, self.tradeDate='20230223', self.openTime='200000', self.closeTime='235959',self.symbol='BTCUSDT',self.open=23767.6, self.close=23940.0, self.high=24215.0, self.low=23590.0, self.vol=246653.418, self.amt=5911671167.71542 
2023-02-24 00:00:02,034:INFO:s_rsrs:main.py:142:handleKline:185271: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime  ...         vol           amt       pct
721  20230223   040000    075959  ...   82007.956  1.966414e+09  0.016382
722  20230223   080000    115959  ...  105146.844  2.561934e+09  0.011294
723  20230223   120000    155959  ...   53133.370  1.296761e+09 -0.003232
724  20230223   160000    195959  ...  159749.202  3.839201e+09 -0.024547
725  20230223   200000    235959  ...  246653.418  5.911671e+09  0.007271

[5 rows x 11 columns]
2023-02-24 00:00:04,638:INFO:s_rsrs:main.py:151:handleKline:185271: df_s.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec  ...  index      beta    zscore  signal
721  20230223   040000    075959  1677110399  ...    721  0.459757 -0.335653     NaN
722  20230223   080000    115959  1677124799  ...    722  0.487210 -0.270709     NaN
723  20230223   120000    155959  1677139199  ...    723  0.515010 -0.206087     NaN
724  20230223   160000    195959  1677153599  ...    724  0.446420 -0.377574     NaN
725  20230223   200000    235959  1677167999  ...    725  0.487523 -0.279294     NaN

[5 rows x 15 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '36.465', 'enterprice': '24934.8', 'countrevence': '0', 'unrealprofit': '36475.09436199915', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '23934.52317669', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'numpy.int64'>, curSign=-9223372036854775808, self.sign=-1


