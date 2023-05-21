# 20230522 00:26:01

## /root/FIL/strategy/amihud/log.txt ----- -----

--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=373746.4768026, self.flagDict['side']='sell', self.tradeCount=2, self.count=2176
self.closeSec=1684685999, self.tradeDate='20230522', self.openTime='001500', self.closeTime='001959', self.symbol='BTCUSDT', self.open=26884.0, self.close=26864.0, self.high=26889.5, self.low=26864.0, self.vol=630.797, self.amt=16953138.6684 
127.0.0.1 - - [22/May/2023 00:20:01] "POST / HTTP/1.1" 200 -
2023-05-22 00:20:05,635:INFO:amihud:main.py:172:handleKline:2219019: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5759  20230521   235500    235959  ...    0.261515   0.325385       0
5760  20230522   000000    000459  ...    0.261365   0.325381       0
5761  20230522   000500    000959  ...    0.261215   0.325376       0
5762  20230522   001000    001459  ...    0.261074   0.325380       0
5763  20230522   001500    001959  ...    0.260933   0.325383       0

[5 rows x 18 columns]
2023-05-22 00:20:05,642:INFO:amihud:main.py:175:handleKline:2219019: self.closeSec=1684685999, self.tradeDate='20230522', self.openTime='001500', self.closeTime='001959',self.symbol='BTCUSDT',self.open=26884.0, self.close=26864.0, self.high=26889.5, self.low=26864.0, self.vol=630.797, self.amt=16953138.6684, ukdf['pct'].iloc[-1]=-0.00074 , ukdf['amount'].iloc[-1]=16953138.6684, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5763, value=0.0, value_mean=0.2609333767161623, signal=0, value_std=0.3253833331608191 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '13.926', 'enterprice': '26864.9', 'countrevence': '0', 'unrealprofit': '-0.37428882348', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '26864.92687698', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1
127.0.0.1 - - [22/May/2023 00:25:00] "POST / HTTP/1.1" 200 -
--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=373746.4768026, self.flagDict['side']='sell', self.tradeCount=2, self.count=2177
self.closeSec=1684686299, self.tradeDate='20230522', self.openTime='002000', self.closeTime='002459', self.symbol='BTCUSDT', self.open=26863.9, self.close=26853.2, self.high=26868.6, self.low=26853.1, self.vol=744.543, self.amt=19997498.0869 
2023-05-22 00:25:00,434:INFO:amihud:main.py:172:handleKline:2219019: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5760  20230522   000000    000459  ...    0.261365   0.325381       0
5761  20230522   000500    000959  ...    0.261215   0.325376       0
5762  20230522   001000    001459  ...    0.261074   0.325380       0
5763  20230522   001500    001959  ...    0.260933   0.325383       0
5764  20230522   002000    002459  ...    0.260797   0.325390       0

[5 rows x 18 columns]
2023-05-22 00:25:00,437:INFO:amihud:main.py:175:handleKline:2219019: self.closeSec=1684686299, self.tradeDate='20230522', self.openTime='002000', self.closeTime='002459',self.symbol='BTCUSDT',self.open=26863.9, self.close=26853.2, self.high=26868.6, self.low=26853.1, self.vol=744.543, self.amt=19997498.0869, ukdf['pct'].iloc[-1]=-0.000402 , ukdf['amount'].iloc[-1]=19997498.0869, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5764, value=0.0, value_mean=0.26079686363219684, signal=0, value_std=0.3253896856746001 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '13.926', 'enterprice': '26864.9', 'countrevence': '0', 'unrealprofit': '148.17844254642', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '26854.25958333', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1


## /root/FIL/strategy/factorcheck/log.txt ----- -----


self.closeSec=1684685999, self.tradeDate='20230522', self.openTime='001500', self.closeTime='001959', self.symbol='BTCUSDT', self.open=26884.0, self.close=26864.0, self.high=26889.5, self.low=26864.0 
127.0.0.1 - - [22/May/2023 00:20:01] "POST / HTTP/1.1" 200 -
2023-05-22 00:20:03,734:INFO:factorcheck2:main.py:126:handleKline:2218005: self.closeSec=1684685999, self.tradeDate='20230522', self.openTime='001500', self.closeTime='001959',self.symbol='BTCUSDT',self.open=26884.0, self.close=26864.0, self.high=26889.5, self.low=26864.0   
2023-05-22 00:20:04,768:INFO:factorcheck2:main.py:127:handleKline:2218005: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime    closeSec  ...      low       pct  index  idx
1439  20230521   235500    235959  1684684799  ...  26840.9  0.001643   1727    5
1440  20230522   000000    000459  1684685099  ...  26879.1 -0.000197   1440    0
1441  20230522   000500    000959  1684685399  ...  26874.6  0.000941   1441    1
1442  20230522   001000    001459  1684685699  ...  26883.9 -0.000784   1442    2
1443  20230522   001500    001959  1684685999  ...  26864.0 -0.000740   1443    3

[5 rows x 11 columns]
2023-05-22 00:20:04,769:INFO:factorcheck2:main.py:128:handleKline:2218005: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=7, self.factor=0.5190040752239495, self.count=2179 

self.closeSec=1684686299, self.tradeDate='20230522', self.openTime='002000', self.closeTime='002459', self.symbol='BTCUSDT', self.open=26863.9, self.close=26853.2, self.high=26868.6, self.low=26853.1 
127.0.0.1 - - [22/May/2023 00:25:00] "POST / HTTP/1.1" 200 -
2023-05-22 00:25:00,363:INFO:factorcheck2:main.py:126:handleKline:2218005: self.closeSec=1684686299, self.tradeDate='20230522', self.openTime='002000', self.closeTime='002459',self.symbol='BTCUSDT',self.open=26863.9, self.close=26853.2, self.high=26868.6, self.low=26853.1   
2023-05-22 00:25:00,409:INFO:factorcheck2:main.py:127:handleKline:2218005: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime    closeSec  ...      low       pct  index  idx
1440  20230522   000000    000459  1684685099  ...  26879.1 -0.000197   1440    0
1441  20230522   000500    000959  1684685399  ...  26874.6  0.000941   1441    1
1442  20230522   001000    001459  1684685699  ...  26883.9 -0.000784   1442    2
1443  20230522   001500    001959  1684685999  ...  26864.0 -0.000740   1443    3
1444  20230522   002000    002459  1684686299  ...  26853.1 -0.000402   1444    4

[5 rows x 11 columns]
2023-05-22 00:25:00,410:INFO:factorcheck2:main.py:128:handleKline:2218005: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}


## /root/FIL/strategy/logic/log.txt ----- -----

2023-05-22 00:00:39,112:DEBUG:logic:main.py:463:getModel:2218526: df_s.iloc[-5:,:] :
          date closeTime     open  ...    alpha58   alpha67   alpha72
5802  20230521    212959  26917.2  ...  48.333333  0.478053  0.552227
5803  20230521    215959  26919.0  ...  48.333333  0.465306  0.565944
5804  20230521    222959  26880.1  ...  48.333333  0.486910  0.571288
5805  20230521    225959  26940.5  ...  48.333333  0.470010  0.582781
5806  20230521    232959  26887.9  ...  48.333333  0.486164  0.587733

[5 rows x 33 columns]
0.5386029411764706
acc is : 0.5386029411764706
2023-05-22 00:00:39,291:INFO:logic:main.py:468:getModel:2218526: df_pred.iloc[-5:,:] :
     pred    prob_0    prob_1  actual  ...       nav  sign  cost_        bm
539     1  0.494583  0.505417       0  ...  0.897282  -1.0    0.0  0.976312
540     1  0.490672  0.509328       1  ...  0.895272  -1.0    0.0  0.978498
541     0  0.518711  0.481289       0  ...  0.897017  -1.0    0.0  0.976591
542     1  0.494478  0.505522       1  ...  0.895462  -1.0    0.0  0.978284
543     0  0.507065  0.492935       0  ...  0.897108  -1.0    0.0  0.976486

[5 rows x 10 columns]
2023-05-22 00:00:39,327:INFO:logic:main.py:478:getModel:2218526: df_panel.iloc[-5:,:] :
    pred    prob_0    prob_1  actual  ...       nav  sign  cost_        bm
45     1  0.494765  0.505235       0  ...  0.897282  -1.0    0.0  0.974037
46     1  0.490633  0.509367       1  ...  0.895272  -1.0    0.0  0.975628
47     0  0.518747  0.481253       0  ...  0.897017  -1.0    0.0  0.973727
48     1  0.494603  0.505397       1  ...  0.895462  -1.0    0.0  0.978444
49     0  0.507065  0.492935       0  ...  0.897108  -1.0    0.0  0.976486

[5 rows x 10 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '27.758', 'enterprice': '26580.2', 'countrevence': '0', 'unrealprofit': '-8499.49442285542', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '26886.39981349', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}


## /root/FIL/strategy/modifiedmom/log.txt ----- -----

2023-05-22 00:00:03,001:INFO:modifiedmom:main.py:319:handleOrderFilled:2218259: handleOrderFilled: data=OrderType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'clientorderid': '42208F1684684802281I0L59', 'symbol': 'BTCUSDT', 'gatewayorderid': 1684684802699921, 'quantity': '26.22', 'price': '26885.6', 'stopprice': '0', 'ordertype': '', 'side': 'SELL', 'status': 'FILLED', 'positionside': 'SHORT', 'createtime': 1684684800996, 'updatetime': 1684684802699, 'tradetype': 'usdt', 'selfid': 42208, 'filltrades': [TradeType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'tradeid': 1684684802699, 'clientorderid': '42208F1684684802281I0L59', 'price': '26885.6', 'quantity': '26.22', 'commission': '704.940432', 'commissionasset': 'USDT', 'tradetime': 1684684802699, 'tradetype': 'usdt', 'gatetype': 'simulator', 'handletime': 1684684802699}], 'gatetype': 'simulator', 'handletime': 0}
127.0.0.1 - - [22/May/2023 00:00:03] "POST / HTTP/1.1" 200 -
127.0.0.1 - - [22/May/2023 00:10:00] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=1088 

self.closeSec=1684685399, self.tradeDate='20230522', self.openTime='000000', self.closeTime='000959', self.symbol='BTCUSDT', self.open='26885.1', self.close='26905'
2023-05-22 00:10:00,359:INFO:modifiedmom:main.py:144:handleKline:2218259: self.closeSec=1684685399, self.tradeDate='20230522', self.openTime='000000', self.closeTime='000959',self.symbol='BTCUSDT',self.open='26885.1', self.close='26905'
2023-05-22 00:10:00,456:INFO:modifiedmom:main.py:145:handleKline:2218259: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec     open    close       pct
572  20230521   232000    232959  1684682999  26916.8  26934.5  0.000658
573  20230521   233000    233959  1684683599  26934.6  26928.2 -0.000234
574  20230521   234000    234959  1684684199  26928.2  26887.9 -0.001497
575  20230521   235000    235959  1684684799  26887.9    26885 -0.000108
576  20230522   000000    000959  1684685399  26885.1    26905  0.000744
2023-05-22 00:10:00,456:INFO:modifiedmom:main.py:146:handleKline:2218259: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': True, 'isOpen': False, 'isClose': True, 'isTrig': False}

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=1089 

self.closeSec=1684685999, self.tradeDate='20230522', self.openTime='001000', self.closeTime='001959', self.symbol='BTCUSDT', self.open='26904.9', self.close='26864'
127.0.0.1 - - [22/May/2023 00:20:01] "POST / HTTP/1.1" 200 -
2023-05-22 00:20:04,053:INFO:modifiedmom:main.py:144:handleKline:2218259: self.closeSec=1684685999, self.tradeDate='20230522', self.openTime='001000', self.closeTime='001959',self.symbol='BTCUSDT',self.open='26904.9', self.close='26864'
2023-05-22 00:20:04,804:INFO:modifiedmom:main.py:145:handleKline:2218259: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec     open    close       pct
573  20230521   233000    233959  1684683599  26934.6  26928.2 -0.000234
574  20230521   234000    234959  1684684199  26928.2  26887.9 -0.001497
575  20230521   235000    235959  1684684799  26887.9    26885 -0.000108
576  20230522   000000    000959  1684685399  26885.1    26905  0.000744
577  20230522   001000    001959  1684685999  26904.9    26864 -0.001524
2023-05-22 00:20:04,804:INFO:modifiedmom:main.py:146:handleKline:2218259: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': True, 'isOpen': False, 'isClose': True, 'isTrig': False}


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

2023-05-22 00:00:00,460:INFO:pyemd2:main.py:127:handleKline:2217508: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}
2023-05-22 00:00:00,638:INFO:pyemd2:main.py:190:insertFactor:2217508: curDateTime:5220000, name:pyemd2, symbol:BTCUSDT, tradeDate:20230521, closeTime:235959, close:26885, total:973579.8686232, pct_pre:0.0049788186722408145, thd:-0.24895375805215247, side:sell 

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=1091 

self.closeSec=1684685399, self.tradeDate='20230522', self.openTime='000000', self.closeTime='000959', self.symbol='BTCUSDT', self.open='26885.1', self.close='26905'
127.0.0.1 - - [22/May/2023 00:10:00] "POST / HTTP/1.1" 200 -
2023-05-22 00:10:00,408:INFO:pyemd2:main.py:125:handleKline:2217508: self.closeSec=1684685399, self.tradeDate='20230522', self.openTime='000000', self.closeTime='000959',self.symbol='BTCUSDT',self.open='26885.1', self.close='26905'
2023-05-22 00:10:00,465:INFO:pyemd2:main.py:126:handleKline:2217508: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
17420  20230521   232000    232959  1684682999  26916.8  26934.5
17421  20230521   233000    233959  1684683599  26934.6  26928.2
17422  20230521   234000    234959  1684684199  26928.2  26887.9
17423  20230521   235000    235959  1684684799  26887.9    26885
17424  20230522   000000    000959  1684685399  26885.1    26905
2023-05-22 00:10:00,465:INFO:pyemd2:main.py:127:handleKline:2217508: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=1092 

self.closeSec=1684685999, self.tradeDate='20230522', self.openTime='001000', self.closeTime='001959', self.symbol='BTCUSDT', self.open='26904.9', self.close='26864'
127.0.0.1 - - [22/May/2023 00:20:02] "POST / HTTP/1.1" 200 -
2023-05-22 00:20:06,144:INFO:pyemd2:main.py:125:handleKline:2217508: self.closeSec=1684685999, self.tradeDate='20230522', self.openTime='001000', self.closeTime='001959',self.symbol='BTCUSDT',self.open='26904.9', self.close='26864'
2023-05-22 00:20:06,234:INFO:pyemd2:main.py:126:handleKline:2217508: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
17421  20230521   233000    233959  1684683599  26934.6  26928.2
17422  20230521   234000    234959  1684684199  26928.2  26887.9
17423  20230521   235000    235959  1684684799  26887.9    26885
17424  20230522   000000    000959  1684685399  26885.1    26905
17425  20230522   001000    001959  1684685999  26904.9    26864
2023-05-22 00:20:06,234:INFO:pyemd2:main.py:127:handleKline:2217508: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}


## /root/FIL/strategy/similarity/log.txt ----- -----

127.0.0.1 - - [22/May/2023 00:00:03] "POST / HTTP/1.1" 200 -
2023-05-22 00:00:03,257:INFO:testStrategy:main.py:308:handleOrderFilled:2217133: handleOrderFilled: data=OrderType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'clientorderid': '42209F1684684802384I0L2', 'symbol': 'BTCUSDT', 'gatewayorderid': 1684684802817515, 'quantity': '47.278', 'price': '26885.6', 'stopprice': '0', 'ordertype': '', 'side': 'SELL', 'status': 'FILLED', 'positionside': 'SHORT', 'createtime': 1684684801203, 'updatetime': 1684684802817, 'tradetype': 'usdt', 'selfid': 42209, 'filltrades': [TradeType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'tradeid': 1684684802817, 'clientorderid': '42209F1684684802384I0L2', 'price': '26885.6', 'quantity': '47.278', 'commission': '1271.0973968', 'commissionasset': 'USDT', 'tradetime': 1684684802817, 'tradetype': 'usdt', 'gatetype': 'simulator', 'handletime': 1684684802817}], 'gatetype': 'simulator', 'handletime': 0}
127.0.0.1 - - [22/May/2023 00:10:00] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=1091 

self.closeSec=1684685399, self.tradeDate='20230522', self.openTime='000000', self.closeTime='000959', self.symbol='BTCUSDT', self.open='26885.1', self.close='26905'
2023-05-22 00:10:00,401:INFO:testStrategy:main.py:101:handleKline:2217133: self.closeSec=1684685399, self.tradeDate='20230522', self.openTime='000000', self.closeTime='000959',self.symbol='BTCUSDT',self.open='26885.1', self.close='26905'
2023-05-22 00:10:00,468:INFO:testStrategy:main.py:102:handleKline:2217133: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
12236  20230521   232000    232959  1684682999  26916.8  26934.5
12237  20230521   233000    233959  1684683599  26934.6  26928.2
12238  20230521   234000    234959  1684684199  26928.2  26887.9
12239  20230521   235000    235959  1684684799  26887.9    26885
12240  20230522   000000    000959  1684685399  26885.1    26905
2023-05-22 00:10:00,468:INFO:testStrategy:main.py:103:handleKline:2217133: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': True, 'isOpen': False, 'isClose': True, 'isTrig': False, 'isCorr': False}

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=1092 

self.closeSec=1684685999, self.tradeDate='20230522', self.openTime='001000', self.closeTime='001959', self.symbol='BTCUSDT', self.open='26904.9', self.close='26864'
127.0.0.1 - - [22/May/2023 00:20:01] "POST / HTTP/1.1" 200 -
2023-05-22 00:20:05,731:INFO:testStrategy:main.py:101:handleKline:2217133: self.closeSec=1684685999, self.tradeDate='20230522', self.openTime='001000', self.closeTime='001959',self.symbol='BTCUSDT',self.open='26904.9', self.close='26864'
2023-05-22 00:20:06,092:INFO:testStrategy:main.py:102:handleKline:2217133: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
12237  20230521   233000    233959  1684683599  26934.6  26928.2
12238  20230521   234000    234959  1684684199  26928.2  26887.9
12239  20230521   235000    235959  1684684799  26887.9    26885
12240  20230522   000000    000959  1684685399  26885.1    26905
12241  20230522   001000    001959  1684685999  26904.9    26864
2023-05-22 00:20:06,093:INFO:testStrategy:main.py:103:handleKline:2217133: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': True, 'isOpen': False, 'isClose': True, 'isTrig': False, 'isCorr': False}


## /root/FIL/strategy/sr_min/log.txt ----- -----

--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=1, self.total=996015.990996, self.flagDict['side']='buy', self.tradeCount=1, self.count=2176
self.closeSec=1684685999, self.tradeDate='20230522', self.openTime='001500', self.closeTime='001959', self.symbol='BTCUSDT', self.open=26884.0, self.close=26864.0, self.high=26889.5, self.low=26864.0, self.vol=630.797, self.amt=16953138.6684 
127.0.0.1 - - [22/May/2023 00:20:01] "POST / HTTP/1.1" 200 -
2023-05-22 00:20:05,690:INFO:sr_min:main.py:172:handleKline:2219263: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5759  20230521   235500    235959  ...         0.0        0.0       0
5760  20230522   000000    000459  ...         0.0        0.0       0
5761  20230522   000500    000959  ...         0.0        0.0       0
5762  20230522   001000    001459  ...         0.0        0.0       0
5763  20230522   001500    001959  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-05-22 00:20:05,700:INFO:sr_min:main.py:175:handleKline:2219263: self.closeSec=1684685999, self.tradeDate='20230522', self.openTime='001500', self.closeTime='001959',self.symbol='BTCUSDT',self.open=26884.0, self.close=26864.0, self.high=26889.5, self.low=26864.0, self.vol=630.797, self.amt=16953138.6684, ukdf['pct'].iloc[-1]=-0.00074 , ukdf['amount'].iloc[-1]=16953138.6684, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5763, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '37.141', 'enterprice': '26844', 'countrevence': '0', 'unrealprofit': '777.24513791418', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '26864.92687698', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=1
--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=1, self.total=996015.990996, self.flagDict['side']='buy', self.tradeCount=1, self.count=2177
self.closeSec=1684686299, self.tradeDate='20230522', self.openTime='002000', self.closeTime='002459', self.symbol='BTCUSDT', self.open=26863.9, self.close=26853.2, self.high=26868.6, self.low=26853.1, self.vol=744.543, self.amt=19997498.0869 
127.0.0.1 - - [22/May/2023 00:25:00] "POST / HTTP/1.1" 200 -
2023-05-22 00:25:00,424:INFO:sr_min:main.py:172:handleKline:2219263: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5760  20230522   000000    000459  ...         0.0        0.0       0
5761  20230522   000500    000959  ...         0.0        0.0       0
5762  20230522   001000    001459  ...         0.0        0.0       0
5763  20230522   001500    001959  ...         0.0        0.0       0
5764  20230522   002000    002459  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-05-22 00:25:00,424:INFO:sr_min:main.py:175:handleKline:2219263: self.closeSec=1684686299, self.tradeDate='20230522', self.openTime='002000', self.closeTime='002459',self.symbol='BTCUSDT',self.open=26863.9, self.close=26853.2, self.high=26868.6, self.low=26853.1, self.vol=744.543, self.amt=19997498.0869, ukdf['pct'].iloc[-1]=-0.000402 , ukdf['amount'].iloc[-1]=19997498.0869, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5764, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '37.141', 'enterprice': '26844', 'countrevence': '0', 'unrealprofit': '381.05118445953', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '26854.25958333', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=1


## /root/FIL/strategy/s_rsrs/log.txt ----- -----

723  20230521   120000    155959  1684655999  ...    723  0.173010 -1.372253    -1.0
724  20230521   160000    195959  1684670399  ...    724  0.177847 -1.320215    -1.0

[5 rows x 15 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '51.549', 'enterprice': '27070.5', 'countrevence': '0', 'unrealprofit': '12993.86785593075', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '26818.43171825', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'numpy.int64'>, curSign=-1, self.sign=-1
--handleKline--:  version='2.0.0', self.name='s_rsrs', self.symbol='BTCUSDT', interval='4h', intervalSec=14400, wid=25, thd=0.6, self.sign=-1, self.total=1394061.7472955, self.flagDict['side']='sell', self.tradeCount=2, self.count=45
self.closeSec=1684684799, self.tradeDate='20230521', self.openTime='200000', self.closeTime='235959', self.symbol='BTCUSDT', self.open=26818.0, self.close=26885.0, self.high=26969.6, self.low=26788.0, self.vol=50401.693, self.amt=1354902581.3394 
127.0.0.1 - - [22/May/2023 00:00:00] "POST / HTTP/1.1" 200 -
2023-05-22 00:00:00,343:INFO:s_rsrs:main.py:141:handleKline:2218689: self.closeSec=1684684799, self.tradeDate='20230521', self.openTime='200000', self.closeTime='235959',self.symbol='BTCUSDT',self.open=26818.0, self.close=26885.0, self.high=26969.6, self.low=26788.0, self.vol=50401.693, self.amt=1354902581.3394 
2023-05-22 00:00:00,373:INFO:s_rsrs:main.py:142:handleKline:2218689: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime  ...        vol           amt       pct
721  20230521   040000    075959  ...  21251.159  5.744749e+08  0.001301
722  20230521   080000    115959  ...  38117.636  1.035943e+09  0.002842
723  20230521   120000    155959  ...  23955.740  6.490055e+08 -0.004491
724  20230521   160000    195959  ...  59909.536  1.612987e+09 -0.008371
725  20230521   200000    235959  ...  50401.693  1.354903e+09  0.002495

[5 rows x 11 columns]
2023-05-22 00:00:02,803:INFO:s_rsrs:main.py:151:handleKline:2218689: df_s.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec  ...  index      beta    zscore  signal
721  20230521   040000    075959  1684627199  ...    721  0.171653 -1.446670    -1.0
722  20230521   080000    115959  1684641599  ...    722  0.183294 -1.352832    -1.0
723  20230521   120000    155959  1684655999  ...    723  0.173010 -1.372253    -1.0
724  20230521   160000    195959  1684670399  ...    724  0.177847 -1.320215    -1.0
725  20230521   200000    235959  1684684799  ...    725  0.170303 -1.343700    -1.0

[5 rows x 15 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '51.549', 'enterprice': '27070.5', 'countrevence': '0', 'unrealprofit': '9398.99094683709', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '26888.16880159', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'numpy.int64'>, curSign=-1, self.sign=-1


