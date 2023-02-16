# 20230217 00:26:02

## /root/FIL/strategy/amihud/log.txt ----- -----

--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=993672.4896432, self.flagDict['side']='sell', self.tradeCount=2, self.count=23452
self.closeSec=1676564399, self.tradeDate='20230217', self.openTime='001500', self.closeTime='001959', self.symbol='BTCUSDT', self.open=24761.5, self.close=24849.3, self.high=24880.0, self.low=24655.2, self.vol=12280.797, self.amt=304032909.5373 
127.0.0.1 - - [17/Feb/2023 00:20:01] "POST / HTTP/1.1" 200 -
2023-02-17 00:20:01,793:INFO:amihud:main.py:172:handleKline:200676: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5759  20230216   235500    235959  ...         0.0        0.0       0
5760  20230217   000000    000459  ...         0.0        0.0       0
5761  20230217   000500    000959  ...         0.0        0.0       0
5762  20230217   001000    001459  ...         0.0        0.0       0
5763  20230217   001500    001959  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-02-17 00:20:01,797:INFO:amihud:main.py:175:handleKline:200676: self.closeSec=1676564399, self.tradeDate='20230217', self.openTime='001500', self.closeTime='001959',self.symbol='BTCUSDT',self.open=24761.5, self.close=24849.3, self.high=24880.0, self.low=24655.2, self.vol=12280.797, self.amt=304032909.5373, ukdf['pct'].iloc[-1]=0.00355 , ukdf['amount'].iloc[-1]=304032909.5373, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5763, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '60.176', 'enterprice': '16529.3', 'countrevence': '0', 'unrealprofit': '-500501.8448', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '24846.6', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1
--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=993672.4896432, self.flagDict['side']='sell', self.tradeCount=2, self.count=23453
self.closeSec=1676564699, self.tradeDate='20230217', self.openTime='002000', self.closeTime='002459', self.symbol='BTCUSDT', self.open=24849.2, self.close=24785.6, self.high=24887.5, self.low=24765.0, self.vol=7498.756, self.amt=186129226.199 
127.0.0.1 - - [17/Feb/2023 00:25:01] "POST / HTTP/1.1" 200 -
2023-02-17 00:25:01,645:INFO:amihud:main.py:172:handleKline:200676: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5760  20230217   000000    000459  ...         0.0        0.0       0
5761  20230217   000500    000959  ...         0.0        0.0       0
5762  20230217   001000    001459  ...         0.0        0.0       0
5763  20230217   001500    001959  ...         0.0        0.0       0
5764  20230217   002000    002459  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-02-17 00:25:01,646:INFO:amihud:main.py:175:handleKline:200676: self.closeSec=1676564699, self.tradeDate='20230217', self.openTime='002000', self.closeTime='002459',self.symbol='BTCUSDT',self.open=24849.2, self.close=24785.6, self.high=24887.5, self.low=24765.0, self.vol=7498.756, self.amt=186129226.199, ukdf['pct'].iloc[-1]=-0.002563 , ukdf['amount'].iloc[-1]=186129226.199, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5764, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '60.176', 'enterprice': '16529.3', 'countrevence': '0', 'unrealprofit': '-497117.85592000192', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '24790.36514092', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1


## /root/FIL/strategy/factorcheck/log.txt ----- -----


self.closeSec=1676564399, self.tradeDate='20230217', self.openTime='001500', self.closeTime='001959', self.symbol='BTCUSDT', self.open=24761.5, self.close=24849.3, self.high=24880.0, self.low=24655.2 
2023-02-17 00:20:01,659:INFO:factorcheck2:main.py:126:handleKline:185239: self.closeSec=1676564399, self.tradeDate='20230217', self.openTime='001500', self.closeTime='001959',self.symbol='BTCUSDT',self.open=24761.5, self.close=24849.3, self.high=24880.0, self.low=24655.2   
127.0.0.1 - - [17/Feb/2023 00:20:01] "POST / HTTP/1.1" 200 -
2023-02-17 00:20:01,703:INFO:factorcheck2:main.py:127:handleKline:185239: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime    closeSec  ...      low       pct  index  idx
1439  20230216   235500    235959  1676563199  ...  24919.5  0.004652   1727    5
1440  20230217   000000    000459  1676563499  ...  25034.5  0.006487   1440    0
1441  20230217   000500    000959  1676563799  ...  24620.0 -0.020753   1441    1
1442  20230217   001000    001459  1676564099  ...  24688.0  0.001067   1442    2
1443  20230217   001500    001959  1676564399  ...  24655.2  0.003550   1443    3

[5 rows x 11 columns]
2023-02-17 00:20:01,703:INFO:factorcheck2:main.py:128:handleKline:185239: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=87, self.factor=0.13816439170168032, self.count=24019 

self.closeSec=1676564699, self.tradeDate='20230217', self.openTime='002000', self.closeTime='002459', self.symbol='BTCUSDT', self.open=24849.2, self.close=24785.6, self.high=24887.5, self.low=24765.0 
127.0.0.1 - - [17/Feb/2023 00:25:01] "POST / HTTP/1.1" 200 -
2023-02-17 00:25:01,538:INFO:factorcheck2:main.py:126:handleKline:185239: self.closeSec=1676564699, self.tradeDate='20230217', self.openTime='002000', self.closeTime='002459',self.symbol='BTCUSDT',self.open=24849.2, self.close=24785.6, self.high=24887.5, self.low=24765.0   
2023-02-17 00:25:01,557:INFO:factorcheck2:main.py:127:handleKline:185239: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime    closeSec  ...      low       pct  index  idx
1440  20230217   000000    000459  1676563499  ...  25034.5  0.006487   1440    0
1441  20230217   000500    000959  1676563799  ...  24620.0 -0.020753   1441    1
1442  20230217   001000    001459  1676564099  ...  24688.0  0.001067   1442    2
1443  20230217   001500    001959  1676564399  ...  24655.2  0.003550   1443    3
1444  20230217   002000    002459  1676564699  ...  24765.0 -0.002563   1444    4

[5 rows x 11 columns]
2023-02-17 00:25:01,557:INFO:factorcheck2:main.py:128:handleKline:185239: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}


## /root/FIL/strategy/logic/log.txt ----- -----

2023-02-17 00:00:33,534:DEBUG:logic:main.py:463:getModel:885513: df_s.iloc[-5:,:] :
          date closeTime     open  ...    alpha58   alpha67   alpha72
5802  20230216    212959  24607.2  ...  52.500000  0.700945  0.127054
5803  20230216    215959  24592.4  ...  52.083333  0.671970  0.132968
5804  20230216    222959  24465.1  ...  52.083333  0.659695  0.140676
5805  20230216    225959  24412.4  ...  52.083333  0.664085  0.147495
5806  20230216    232959  24448.2  ...  52.500000  0.675950  0.152297

[5 rows x 33 columns]
0.5202205882352942
acc is : 0.5202205882352942
2023-02-17 00:00:33,702:INFO:logic:main.py:468:getModel:885513: df_pred.iloc[-5:,:] :
     pred    prob_0    prob_1  actual  ...       nav  sign   cost_        bm
539     1  0.465675  0.534325       0  ...  1.149346   1.0  0.0000  1.046541
540     1  0.439978  0.560022       0  ...  1.150148  -1.0 -0.0016  1.044137
541     1  0.444202  0.555798       1  ...  1.148291  -1.0  0.0000  1.045823
542     1  0.467322  0.532678       1  ...  1.143143  -1.0  0.0000  1.050511
543     1  0.477408  0.522592       1  ...  1.118072  -1.0  0.0000  1.073551

[5 rows x 10 columns]
2023-02-17 00:00:33,727:INFO:logic:main.py:478:getModel:885513: df_panel.iloc[-5:,:] :
    pred    prob_0    prob_1  actual  ...       nav  sign   cost_        bm
45     1  0.466198  0.533802       0  ...  1.149346   1.0  0.0000  1.047518
46     1  0.439211  0.560789       0  ...  1.150148  -1.0 -0.0016  1.043526
47     1  0.444347  0.555653       1  ...  1.148291  -1.0  0.0000  1.045210
48     1  0.466969  0.533031       1  ...  1.143143  -1.0  0.0000  1.050165
49     1  0.477408  0.522592       1  ...  1.118072  -1.0  0.0000  1.073551

[5 rows x 10 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '35.555', 'enterprice': '24439', 'countrevence': '0', 'unrealprofit': '-22065.433', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '25059.6', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}


## /root/FIL/strategy/modifiedmom/log.txt ----- -----

127.0.0.1 - - [17/Feb/2023 00:00:03] "POST / HTTP/1.1" 200 -
2023-02-17 00:00:03,794:INFO:modifiedmom:main.py:319:handleOrderFilled:185213: handleOrderFilled: data=OrderType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'clientorderid': '41748F1676563203186I0L59', 'symbol': 'BTCUSDT', 'gatewayorderid': 1676563203456836, 'quantity': '38.542', 'price': '25091.6', 'stopprice': '0', 'ordertype': '', 'side': 'SELL', 'status': 'FILLED', 'positionside': 'SHORT', 'createtime': 1676563202555, 'updatetime': 1676563203456, 'tradetype': 'usdt', 'selfid': 41748, 'filltrades': [TradeType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'tradeid': 1676563203456, 'clientorderid': '41748F1676563203186I0L59', 'price': '25091.6', 'quantity': '38.542', 'commission': '967.0804472', 'commissionasset': 'USDT', 'tradetime': 1676563203456, 'tradetype': 'usdt', 'gatetype': 'simulator', 'handletime': 1676563203456}], 'gatetype': 'simulator', 'handletime': 0}
127.0.0.1 - - [17/Feb/2023 00:10:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=12008 

self.closeSec=1676563799, self.tradeDate='20230217', self.openTime='000000', self.closeTime='000959', self.symbol='BTCUSDT', self.open='25090.2', self.close='24742.3'
2023-02-17 00:10:01,800:INFO:modifiedmom:main.py:144:handleKline:185213: self.closeSec=1676563799, self.tradeDate='20230217', self.openTime='000000', self.closeTime='000959',self.symbol='BTCUSDT',self.open='25090.2', self.close='24742.3'
2023-02-17 00:10:01,855:INFO:modifiedmom:main.py:145:handleKline:185213: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec     open    close       pct
572  20230216   232000    232959  1676561399  24545.6  24557.9  0.000501
573  20230216   233000    233959  1676561999  24557.9  24608.5  0.002060
574  20230216   234000    234959  1676562599  24608.5  24957.3  0.014174
575  20230216   235000    235959  1676563199  24958.6  25096.4  0.005574
576  20230217   000000    000959  1676563799  25090.2  24742.3 -0.014110
2023-02-17 00:10:01,855:INFO:modifiedmom:main.py:146:handleKline:185213: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': True, 'isOpen': False, 'isClose': True, 'isTrig': False}
127.0.0.1 - - [17/Feb/2023 00:20:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=12009 

self.closeSec=1676564399, self.tradeDate='20230217', self.openTime='001000', self.closeTime='001959', self.symbol='BTCUSDT', self.open='24741.5', self.close='24849.3'
2023-02-17 00:20:01,760:INFO:modifiedmom:main.py:144:handleKline:185213: self.closeSec=1676564399, self.tradeDate='20230217', self.openTime='001000', self.closeTime='001959',self.symbol='BTCUSDT',self.open='24741.5', self.close='24849.3'
2023-02-17 00:20:01,799:INFO:modifiedmom:main.py:145:handleKline:185213: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec     open    close       pct
573  20230216   233000    233959  1676561999  24557.9  24608.5  0.002060
574  20230216   234000    234959  1676562599  24608.5  24957.3  0.014174
575  20230216   235000    235959  1676563199  24958.6  25096.4  0.005574
576  20230217   000000    000959  1676563799  25090.2  24742.3 -0.014110
577  20230217   001000    001959  1676564399  24741.5  24849.3  0.004325
2023-02-17 00:20:01,800:INFO:modifiedmom:main.py:146:handleKline:185213: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': True, 'isOpen': False, 'isClose': True, 'isTrig': False}


## /root/FIL/strategy/percentile_regression_step2/log.txt ----- -----

127.0.0.1 - - [16/Feb/2023 23:00:02] "POST / HTTP/1.1" 200 -
2023-02-16 23:00:02,899:DEBUG:percentile_regression_step2:main.py:154:get_signal:1265985: df_id.iloc[-5:,:] :
                 daytime     hms    close  ...  pct_10  pct_20  factor
144  2023/02/16 20:30:00  203000  24607.1  ...     NaN     NaN       0
145  2023/02/16 21:00:00  210000  24592.4  ...     NaN     NaN       0
146  2023/02/16 21:30:00  213000  24465.0  ...     NaN     NaN       0
147  2023/02/16 22:00:00  220000  24408.8  ...     NaN     NaN       0
148  2023/02/16 22:30:00  223000  24448.2  ...     NaN     NaN       0

[5 rows x 10 columns]
127.0.0.1 - - [16/Feb/2023 23:30:02] "POST / HTTP/1.1" 200 -
2023-02-16 23:30:02,931:DEBUG:percentile_regression_step2:main.py:154:get_signal:1265985: df_id.iloc[-5:,:] :
                 daytime     hms    close  ...  pct_10  pct_20  factor
144  2023/02/16 21:00:00  210000  24592.4  ...     NaN     NaN       0
145  2023/02/16 21:30:00  213000  24465.0  ...     NaN     NaN       0
146  2023/02/16 22:00:00  220000  24408.8  ...     NaN     NaN       0
147  2023/02/16 22:30:00  223000  24448.2  ...     NaN     NaN       0
148  2023/02/16 23:00:00  230000  24557.8  ...     NaN     NaN       0

[5 rows x 10 columns]
127.0.0.1 - - [17/Feb/2023 00:00:02] "POST / HTTP/1.1" 200 -
2023-02-17 00:00:02,984:DEBUG:percentile_regression_step2:main.py:154:get_signal:1265985: df_id.iloc[-5:,:] :
                 daytime     hms    close  ...  pct_10  pct_20  factor
144  2023/02/16 21:30:00  213000  24465.0  ...     NaN     NaN       0
145  2023/02/16 22:00:00  220000  24408.8  ...     NaN     NaN       0
146  2023/02/16 22:30:00  223000  24448.2  ...     NaN     NaN       0
147  2023/02/16 23:00:00  230000  24557.8  ...     NaN     NaN       0
148  2023/02/16 23:30:00  233000  25096.4  ...     NaN     NaN       0

[5 rows x 10 columns]


## /root/FIL/strategy/pyemd/log.txt ----- -----

2023-02-17 00:00:02,348:INFO:pyemd2:main.py:127:handleKline:185189: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}
2023-02-17 00:00:02,456:INFO:pyemd2:main.py:190:insertFactor:185189: curDateTime:2170000, name:pyemd2, symbol:BTCUSDT, tradeDate:20230216, closeTime:235959, close:25096.4, total:975512.8470093, pct_pre:0.0799964967595026, thd:-1.4689960720490636, side:sell 
127.0.0.1 - - [17/Feb/2023 00:10:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=12009 

self.closeSec=1676563799, self.tradeDate='20230217', self.openTime='000000', self.closeTime='000959', self.symbol='BTCUSDT', self.open='25090.2', self.close='24742.3'
2023-02-17 00:10:01,804:INFO:pyemd2:main.py:125:handleKline:185189: self.closeSec=1676563799, self.tradeDate='20230217', self.openTime='000000', self.closeTime='000959',self.symbol='BTCUSDT',self.open='25090.2', self.close='24742.3'
2023-02-17 00:10:01,815:INFO:pyemd2:main.py:126:handleKline:185189: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
17420  20230216   232000    232959  1676561399  24545.6  24557.9
17421  20230216   233000    233959  1676561999  24557.9  24608.5
17422  20230216   234000    234959  1676562599  24608.5  24957.3
17423  20230216   235000    235959  1676563199  24958.6  25096.4
17424  20230217   000000    000959  1676563799  25090.2  24742.3
2023-02-17 00:10:01,816:INFO:pyemd2:main.py:127:handleKline:185189: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}
127.0.0.1 - - [17/Feb/2023 00:20:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=12010 

self.closeSec=1676564399, self.tradeDate='20230217', self.openTime='001000', self.closeTime='001959', self.symbol='BTCUSDT', self.open='24741.5', self.close='24849.3'
2023-02-17 00:20:01,785:INFO:pyemd2:main.py:125:handleKline:185189: self.closeSec=1676564399, self.tradeDate='20230217', self.openTime='001000', self.closeTime='001959',self.symbol='BTCUSDT',self.open='24741.5', self.close='24849.3'
2023-02-17 00:20:01,810:INFO:pyemd2:main.py:126:handleKline:185189: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
17421  20230216   233000    233959  1676561999  24557.9  24608.5
17422  20230216   234000    234959  1676562599  24608.5  24957.3
17423  20230216   235000    235959  1676563199  24958.6  25096.4
17424  20230217   000000    000959  1676563799  25090.2  24742.3
17425  20230217   001000    001959  1676564399  24741.5  24849.3
2023-02-17 00:20:01,810:INFO:pyemd2:main.py:127:handleKline:185189: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}


## /root/FIL/strategy/similarity/log.txt ----- -----

127.0.0.1 - - [17/Feb/2023 00:00:03] "POST / HTTP/1.1" 200 -
2023-02-17 00:00:03,998:INFO:testStrategy:main.py:308:handleOrderFilled:185174: handleOrderFilled: data=OrderType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'clientorderid': '41749F1676563203411I0L2', 'symbol': 'BTCUSDT', 'gatewayorderid': 1676563203541838, 'quantity': '47.466', 'price': '25091.6', 'stopprice': '0', 'ordertype': '', 'side': 'SELL', 'status': 'FILLED', 'positionside': 'SHORT', 'createtime': 1676563202727, 'updatetime': 1676563203541, 'tradetype': 'usdt', 'selfid': 41749, 'filltrades': [TradeType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'tradeid': 1676563203541, 'clientorderid': '41749F1676563203411I0L2', 'price': '25091.6', 'quantity': '47.466', 'commission': '1190.9978856', 'commissionasset': 'USDT', 'tradetime': 1676563203541, 'tradetype': 'usdt', 'gatetype': 'simulator', 'handletime': 1676563203541}], 'gatetype': 'simulator', 'handletime': 0}
127.0.0.1 - - [17/Feb/2023 00:10:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=12009 

self.closeSec=1676563799, self.tradeDate='20230217', self.openTime='000000', self.closeTime='000959', self.symbol='BTCUSDT', self.open='25090.2', self.close='24742.3'
2023-02-17 00:10:01,831:INFO:testStrategy:main.py:101:handleKline:185174: self.closeSec=1676563799, self.tradeDate='20230217', self.openTime='000000', self.closeTime='000959',self.symbol='BTCUSDT',self.open='25090.2', self.close='24742.3'
2023-02-17 00:10:01,863:INFO:testStrategy:main.py:102:handleKline:185174: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
12236  20230216   232000    232959  1676561399  24545.6  24557.9
12237  20230216   233000    233959  1676561999  24557.9  24608.5
12238  20230216   234000    234959  1676562599  24608.5  24957.3
12239  20230216   235000    235959  1676563199  24958.6  25096.4
12240  20230217   000000    000959  1676563799  25090.2  24742.3
2023-02-17 00:10:01,863:INFO:testStrategy:main.py:103:handleKline:185174: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': True, 'isOpen': False, 'isClose': True, 'isTrig': False, 'isCorr': False}

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=12010 

self.closeSec=1676564399, self.tradeDate='20230217', self.openTime='001000', self.closeTime='001959', self.symbol='BTCUSDT', self.open='24741.5', self.close='24849.3'
2023-02-17 00:20:01,746:INFO:testStrategy:main.py:101:handleKline:185174: self.closeSec=1676564399, self.tradeDate='20230217', self.openTime='001000', self.closeTime='001959',self.symbol='BTCUSDT',self.open='24741.5', self.close='24849.3'
127.0.0.1 - - [17/Feb/2023 00:20:01] "POST / HTTP/1.1" 200 -
2023-02-17 00:20:01,752:INFO:testStrategy:main.py:102:handleKline:185174: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
12237  20230216   233000    233959  1676561999  24557.9  24608.5
12238  20230216   234000    234959  1676562599  24608.5  24957.3
12239  20230216   235000    235959  1676563199  24958.6  25096.4
12240  20230217   000000    000959  1676563799  25090.2  24742.3
12241  20230217   001000    001959  1676564399  24741.5  24849.3
2023-02-17 00:20:01,753:INFO:testStrategy:main.py:103:handleKline:185174: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': True, 'isOpen': False, 'isClose': True, 'isTrig': False, 'isCorr': False}


## /root/FIL/strategy/sr_min/log.txt ----- -----

--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=0, self.total=1000000.0, self.flagDict['side']='', self.tradeCount=0, self.count=19450
self.closeSec=1676564399, self.tradeDate='20230217', self.openTime='001500', self.closeTime='001959', self.symbol='BTCUSDT', self.open=24761.5, self.close=24849.3, self.high=24880.0, self.low=24655.2, self.vol=12280.797, self.amt=304032909.5373 
127.0.0.1 - - [17/Feb/2023 00:20:01] "POST / HTTP/1.1" 200 -
2023-02-17 00:20:01,735:INFO:sr_min:main.py:172:handleKline:449472: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5759  20230216   235500    235959  ...         0.0        0.0       0
5760  20230217   000000    000459  ...         0.0        0.0       0
5761  20230217   000500    000959  ...         0.0        0.0       0
5762  20230217   001000    001459  ...         0.0        0.0       0
5763  20230217   001500    001959  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-02-17 00:20:01,736:INFO:sr_min:main.py:175:handleKline:449472: self.closeSec=1676564399, self.tradeDate='20230217', self.openTime='001500', self.closeTime='001959',self.symbol='BTCUSDT',self.open=24761.5, self.close=24849.3, self.high=24880.0, self.low=24655.2, self.vol=12280.797, self.amt=304032909.5373, ukdf['pct'].iloc[-1]=0.00355 , ukdf['amount'].iloc[-1]=304032909.5373, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5763, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': []}
type(curSign)=<class 'int'>, curSign=0, self.sign=0
127.0.0.1 - - [17/Feb/2023 00:25:01] "POST / HTTP/1.1" 200 -
--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=0, self.total=1000000.0, self.flagDict['side']='', self.tradeCount=0, self.count=19451
self.closeSec=1676564699, self.tradeDate='20230217', self.openTime='002000', self.closeTime='002459', self.symbol='BTCUSDT', self.open=24849.2, self.close=24785.6, self.high=24887.5, self.low=24765.0, self.vol=7498.756, self.amt=186129226.199 
2023-02-17 00:25:01,640:INFO:sr_min:main.py:172:handleKline:449472: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5760  20230217   000000    000459  ...         0.0        0.0       0
5761  20230217   000500    000959  ...         0.0        0.0       0
5762  20230217   001000    001459  ...         0.0        0.0       0
5763  20230217   001500    001959  ...         0.0        0.0       0
5764  20230217   002000    002459  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-02-17 00:25:01,644:INFO:sr_min:main.py:175:handleKline:449472: self.closeSec=1676564699, self.tradeDate='20230217', self.openTime='002000', self.closeTime='002459',self.symbol='BTCUSDT',self.open=24849.2, self.close=24785.6, self.high=24887.5, self.low=24765.0, self.vol=7498.756, self.amt=186129226.199, ukdf['pct'].iloc[-1]=-0.002563 , ukdf['amount'].iloc[-1]=186129226.199, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5764, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': []}
type(curSign)=<class 'int'>, curSign=0, self.sign=0


## /root/FIL/strategy/s_rsrs/log.txt ----- -----

723  20230216   120000    155959  1676534399  ...    723  1.216220  2.090231     1.0
724  20230216   160000    195959  1676548799  ...    724  1.095735  1.639745     1.0

[5 rows x 15 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '36.518', 'enterprice': '23318.2', 'countrevence': '0', 'unrealprofit': '46082.0642', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '24580.1', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'numpy.int64'>, curSign=1, self.sign=1
127.0.0.1 - - [17/Feb/2023 00:00:02] "POST / HTTP/1.1" 200 -
--handleKline--:  version='2.0.0', self.name='s_rsrs', self.symbol='BTCUSDT', interval='4h', intervalSec=14400, wid=25, thd=0.6, self.sign=1, self.total=850682.4935724001, self.flagDict['side']='buy', self.tradeCount=20, self.count=500
self.closeSec=1676563199, self.tradeDate='20230216', self.openTime='200000', self.closeTime='235959', self.symbol='BTCUSDT', self.open=24580.0, self.close=25096.4, self.high=25104.8, self.low=24312.0, self.vol=214136.439, self.amt=5270859916.47488 
2023-02-17 00:00:02,207:INFO:s_rsrs:main.py:141:handleKline:185271: self.closeSec=1676563199, self.tradeDate='20230216', self.openTime='200000', self.closeTime='235959',self.symbol='BTCUSDT',self.open=24580.0, self.close=25096.4, self.high=25104.8, self.low=24312.0, self.vol=214136.439, self.amt=5270859916.47488 
2023-02-17 00:00:02,262:INFO:s_rsrs:main.py:142:handleKline:185271: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime  ...         vol           amt       pct
721  20230216   040000    075959  ...  306935.488  7.368613e+09  0.043699
722  20230216   080000    115959  ...  149506.526  3.687049e+09  0.016784
723  20230216   120000    155959  ...   85116.457  2.096381e+09 -0.004454
724  20230216   160000    195959  ...   48543.148  1.194716e+09 -0.002062
725  20230216   200000    235959  ...  214136.439  5.270860e+09  0.021009

[5 rows x 11 columns]
2023-02-17 00:00:04,510:INFO:s_rsrs:main.py:151:handleKline:185271: df_s.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec  ...  index      beta    zscore  signal
721  20230216   040000    075959  1676505599  ...    721  1.530634  3.435158     1.0
722  20230216   080000    115959  1676519999  ...    722  1.379617  2.733619     1.0
723  20230216   120000    155959  1676534399  ...    723  1.216220  2.090231     1.0
724  20230216   160000    195959  1676548799  ...    724  1.095735  1.639745     1.0
725  20230216   200000    235959  1676563199  ...    725  1.148644  1.765325     1.0

[5 rows x 15 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '36.518', 'enterprice': '23318.2', 'countrevence': '0', 'unrealprofit': '64374.84516969194', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '25081.02504983', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'numpy.int64'>, curSign=1, self.sign=1


