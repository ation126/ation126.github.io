# 20230602 00:26:02

## /root/FIL/strategy/amihud/log.txt ----- -----

--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=373746.4768026, self.flagDict['side']='sell', self.tradeCount=2, self.count=5344
self.closeSec=1685636399, self.tradeDate='20230602', self.openTime='001500', self.closeTime='001959', self.symbol='BTCUSDT', self.open=26905.9, self.close=26919.2, self.high=26920.0, self.low=26895.8, self.vol=489.721, self.amt=13176681.3824 
127.0.0.1 - - [02/Jun/2023 00:20:01] "POST / HTTP/1.1" 200 -
2023-06-02 00:20:07,116:INFO:amihud:main.py:172:handleKline:2219019: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5759  20230601   235500    235959  ...         0.0        0.0       0
5760  20230602   000000    000459  ...         0.0        0.0       0
5761  20230602   000500    000959  ...         0.0        0.0       0
5762  20230602   001000    001459  ...         0.0        0.0       0
5763  20230602   001500    001959  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-06-02 00:20:07,145:INFO:amihud:main.py:175:handleKline:2219019: self.closeSec=1685636399, self.tradeDate='20230602', self.openTime='001500', self.closeTime='001959',self.symbol='BTCUSDT',self.open=26905.9, self.close=26919.2, self.high=26920.0, self.low=26895.8, self.vol=489.721, self.amt=13176681.3824, ukdf['pct'].iloc[-1]=0.000494 , ukdf['amount'].iloc[-1]=13176681.3824, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5763, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '13.926', 'enterprice': '26864.9', 'countrevence': '0', 'unrealprofit': '-740.8632', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '26918.1', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1
127.0.0.1 - - [02/Jun/2023 00:25:00] "POST / HTTP/1.1" 200 -
--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=373746.4768026, self.flagDict['side']='sell', self.tradeCount=2, self.count=5345
self.closeSec=1685636699, self.tradeDate='20230602', self.openTime='002000', self.closeTime='002459', self.symbol='BTCUSDT', self.open=26919.2, self.close=26909.8, self.high=26924.0, self.low=26909.8, self.vol=705.809, self.amt=18998284.8741 
2023-06-02 00:25:00,846:INFO:amihud:main.py:172:handleKline:2219019: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5760  20230602   000000    000459  ...         0.0        0.0       0
5761  20230602   000500    000959  ...         0.0        0.0       0
5762  20230602   001000    001459  ...         0.0        0.0       0
5763  20230602   001500    001959  ...         0.0        0.0       0
5764  20230602   002000    002459  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-06-02 00:25:00,850:INFO:amihud:main.py:175:handleKline:2219019: self.closeSec=1685636699, self.tradeDate='20230602', self.openTime='002000', self.closeTime='002459',self.symbol='BTCUSDT',self.open=26919.2, self.close=26909.8, self.high=26924.0, self.low=26909.8, self.vol=705.809, self.amt=18998284.8741, ukdf['pct'].iloc[-1]=-0.000349 , ukdf['amount'].iloc[-1]=18998284.8741, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5764, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '13.926', 'enterprice': '26864.9', 'countrevence': '0', 'unrealprofit': '-664.40069177262', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '26912.60937037', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1


## /root/FIL/strategy/factorcheck/log.txt ----- -----


self.closeSec=1685636399, self.tradeDate='20230602', self.openTime='001500', self.closeTime='001959', self.symbol='BTCUSDT', self.open=26905.9, self.close=26919.2, self.high=26920.0, self.low=26895.8 
127.0.0.1 - - [02/Jun/2023 00:20:01] "POST / HTTP/1.1" 200 -
2023-06-02 00:20:04,665:INFO:factorcheck2:main.py:126:handleKline:2218005: self.closeSec=1685636399, self.tradeDate='20230602', self.openTime='001500', self.closeTime='001959',self.symbol='BTCUSDT',self.open=26905.9, self.close=26919.2, self.high=26920.0, self.low=26895.8   
2023-06-02 00:20:06,135:INFO:factorcheck2:main.py:127:handleKline:2218005: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime    closeSec  ...      low       pct  index  idx
1439  20230601   235500    235959  1685635199  ...  26860.0  0.000610   1727    5
1440  20230602   000000    000459  1685635499  ...  26879.3  0.000584   1440    0
1441  20230602   000500    000959  1685635799  ...  26885.4 -0.000160   1441    1
1442  20230602   001000    001459  1685636099  ...  26895.6  0.000383   1442    2
1443  20230602   001500    001959  1685636399  ...  26895.8  0.000494   1443    3

[5 rows x 11 columns]
2023-06-02 00:20:06,145:INFO:factorcheck2:main.py:128:handleKline:2218005: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': True, 'isOpenSell': False, 'isCloseBuy': False, 'isCloseSell': False, 'isOpen': True, 'isClose': False, 'isTrig': True}

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=0, self.factor=0.6790210485601768, self.count=5347 

self.closeSec=1685636699, self.tradeDate='20230602', self.openTime='002000', self.closeTime='002459', self.symbol='BTCUSDT', self.open=26919.2, self.close=26909.8, self.high=26924.0, self.low=26909.8 
127.0.0.1 - - [02/Jun/2023 00:25:00] "POST / HTTP/1.1" 200 -
2023-06-02 00:25:00,736:INFO:factorcheck2:main.py:126:handleKline:2218005: self.closeSec=1685636699, self.tradeDate='20230602', self.openTime='002000', self.closeTime='002459',self.symbol='BTCUSDT',self.open=26919.2, self.close=26909.8, self.high=26924.0, self.low=26909.8   
2023-06-02 00:25:00,773:INFO:factorcheck2:main.py:127:handleKline:2218005: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime    closeSec  ...      low       pct  index  idx
1440  20230602   000000    000459  1685635499  ...  26879.3  0.000584   1440    0
1441  20230602   000500    000959  1685635799  ...  26885.4 -0.000160   1441    1
1442  20230602   001000    001459  1685636099  ...  26895.6  0.000383   1442    2
1443  20230602   001500    001959  1685636399  ...  26895.8  0.000494   1443    3
1444  20230602   002000    002459  1685636699  ...  26909.8 -0.000349   1444    4

[5 rows x 11 columns]
2023-06-02 00:25:00,773:INFO:factorcheck2:main.py:128:handleKline:2218005: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': True, 'isOpenSell': False, 'isCloseBuy': False, 'isCloseSell': False, 'isOpen': True, 'isClose': False, 'isTrig': True}


## /root/FIL/strategy/logic/log.txt ----- -----

2023-06-02 00:00:33,720:DEBUG:logic:main.py:463:getModel:2218526: df_s.iloc[-5:,:] :
          date closeTime     open  ...    alpha58   alpha67   alpha72
5802  20230601    212959  26929.8  ...  50.000000  0.447146  0.665925
5803  20230601    215959  26898.5  ...  50.000000  0.444038  0.663087
5804  20230601    222959  26881.8  ...  49.583333  0.439271  0.662728
5805  20230601    225959  26856.1  ...  50.000000  0.446793  0.659550
5806  20230601    232959  26887.9  ...  50.416667  0.447930  0.656156

[5 rows x 33 columns]
0.5275735294117647
acc is : 0.5275735294117647
2023-06-02 00:00:33,952:INFO:logic:main.py:468:getModel:2218526: df_pred.iloc[-5:,:] :
     pred    prob_0    prob_1  actual  ...       nav  sign  cost_        bm
539     0  0.502677  0.497323       0  ...  1.079897  -1.0    0.0  0.993980
540     0  0.504499  0.495501       0  ...  1.080930  -1.0    0.0  0.993030
541     1  0.497826  0.502174       1  ...  1.079646  -1.0    0.0  0.994210
542     0  0.514218  0.485782       1  ...  1.079453  -1.0    0.0  0.994387
543     0  0.503053  0.496947       0  ...  1.079794  -1.0    0.0  0.994073

[5 rows x 10 columns]
2023-06-02 00:00:33,986:INFO:logic:main.py:478:getModel:2218526: df_panel.iloc[-5:,:] :
    pred    prob_0    prob_1  actual  ...       nav  sign  cost_        bm
45     0  0.502796  0.497204       0  ...  1.079897  -1.0    0.0  0.992754
46     0  0.504419  0.495581       0  ...  1.080930  -1.0    0.0  0.992032
47     1  0.497745  0.502255       1  ...  1.079646  -1.0    0.0  0.993211
48     0  0.514167  0.485833       1  ...  1.079453  -1.0    0.0  0.994189
49     0  0.503053  0.496947       0  ...  1.079794  -1.0    0.0  0.994073

[5 rows x 10 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '25.849', 'enterprice': '27935.3', 'countrevence': '0', 'unrealprofit': '27208.47167002369', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '26882.70718519', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}


## /root/FIL/strategy/modifiedmom/log.txt ----- -----

127.0.0.1 - - [02/Jun/2023 00:00:04] "POST / HTTP/1.1" 200 -
2023-06-02 00:00:04,442:INFO:modifiedmom:main.py:319:handleOrderFilled:2218259: handleOrderFilled: data=OrderType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'clientorderid': '42299F1685635203846I0L59', 'symbol': 'BTCUSDT', 'gatewayorderid': 1685635204213141, 'quantity': '25.229', 'price': '26884.5', 'stopprice': '0', 'ordertype': '', 'side': 'SELL', 'status': 'FILLED', 'positionside': 'SHORT', 'createtime': 1685635203009, 'updatetime': 1685635204213, 'tradetype': 'usdt', 'selfid': 42299, 'filltrades': [TradeType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'tradeid': 1685635204213, 'clientorderid': '42299F1685635203846I0L59', 'price': '26884.5', 'quantity': '25.229', 'commission': '678.2690505', 'commissionasset': 'USDT', 'tradetime': 1685635204213, 'tradetype': 'usdt', 'gatetype': 'simulator', 'handletime': 1685635204213}], 'gatetype': 'simulator', 'handletime': 0}

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=2672 

self.closeSec=1685635799, self.tradeDate='20230602', self.openTime='000000', self.closeTime='000959', self.symbol='BTCUSDT', self.open='26884.2', self.close='26895.6'
127.0.0.1 - - [02/Jun/2023 00:10:01] "POST / HTTP/1.1" 200 -
2023-06-02 00:10:01,094:INFO:modifiedmom:main.py:144:handleKline:2218259: self.closeSec=1685635799, self.tradeDate='20230602', self.openTime='000000', self.closeTime='000959',self.symbol='BTCUSDT',self.open='26884.2', self.close='26895.6'
2023-06-02 00:10:01,111:INFO:modifiedmom:main.py:145:handleKline:2218259: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec     open    close       pct
572  20230601   232000    232959  1685633399  26913.9  26892.6 -0.000795
573  20230601   233000    233959  1685633999  26892.7  26882.2 -0.000387
574  20230601   234000    234959  1685634599  26882.2  26866.5 -0.000584
575  20230601   235000    235959  1685635199  26866.6  26884.2  0.000659
576  20230602   000000    000959  1685635799  26884.2  26895.6  0.000424
2023-06-02 00:10:01,112:INFO:modifiedmom:main.py:146:handleKline:2218259: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': True, 'isOpen': False, 'isClose': True, 'isTrig': False}

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=2673 

self.closeSec=1685636399, self.tradeDate='20230602', self.openTime='001000', self.closeTime='001959', self.symbol='BTCUSDT', self.open='26895.7', self.close='26919.1'
127.0.0.1 - - [02/Jun/2023 00:20:04] "POST / HTTP/1.1" 200 -
2023-06-02 00:20:07,091:INFO:modifiedmom:main.py:144:handleKline:2218259: self.closeSec=1685636399, self.tradeDate='20230602', self.openTime='001000', self.closeTime='001959',self.symbol='BTCUSDT',self.open='26895.7', self.close='26919.1'
2023-06-02 00:20:07,905:INFO:modifiedmom:main.py:145:handleKline:2218259: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec     open    close       pct
573  20230601   233000    233959  1685633999  26892.7  26882.2 -0.000387
574  20230601   234000    234959  1685634599  26882.2  26866.5 -0.000584
575  20230601   235000    235959  1685635199  26866.6  26884.2  0.000659
576  20230602   000000    000959  1685635799  26884.2  26895.6  0.000424
577  20230602   001000    001959  1685636399  26895.7  26919.1  0.000874
2023-06-02 00:20:07,906:INFO:modifiedmom:main.py:146:handleKline:2218259: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': True, 'isOpen': False, 'isClose': True, 'isTrig': False}


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

2023-06-02 00:00:02,579:INFO:pyemd2:main.py:127:handleKline:2217508: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}
2023-06-02 00:00:02,685:INFO:pyemd2:main.py:190:insertFactor:2217508: curDateTime:6020000, name:pyemd2, symbol:BTCUSDT, tradeDate:20230601, closeTime:235959, close:26884.2, total:971927.4245254, pct_pre:-0.0008952119163477823, thd:0.15367452118142905, side:sell 

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=2675 

self.closeSec=1685635799, self.tradeDate='20230602', self.openTime='000000', self.closeTime='000959', self.symbol='BTCUSDT', self.open='26884.2', self.close='26895.6'
2023-06-02 00:10:01,100:INFO:pyemd2:main.py:125:handleKline:2217508: self.closeSec=1685635799, self.tradeDate='20230602', self.openTime='000000', self.closeTime='000959',self.symbol='BTCUSDT',self.open='26884.2', self.close='26895.6'
127.0.0.1 - - [02/Jun/2023 00:10:01] "POST / HTTP/1.1" 200 -
2023-06-02 00:10:01,116:INFO:pyemd2:main.py:126:handleKline:2217508: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
17420  20230601   232000    232959  1685633399  26913.9  26892.6
17421  20230601   233000    233959  1685633999  26892.7  26882.2
17422  20230601   234000    234959  1685634599  26882.2  26866.5
17423  20230601   235000    235959  1685635199  26866.6  26884.2
17424  20230602   000000    000959  1685635799  26884.2  26895.6
2023-06-02 00:10:01,116:INFO:pyemd2:main.py:127:handleKline:2217508: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=2676 

self.closeSec=1685636399, self.tradeDate='20230602', self.openTime='001000', self.closeTime='001959', self.symbol='BTCUSDT', self.open='26895.7', self.close='26919.1'
127.0.0.1 - - [02/Jun/2023 00:20:04] "POST / HTTP/1.1" 200 -
2023-06-02 00:20:08,900:INFO:pyemd2:main.py:125:handleKline:2217508: self.closeSec=1685636399, self.tradeDate='20230602', self.openTime='001000', self.closeTime='001959',self.symbol='BTCUSDT',self.open='26895.7', self.close='26919.1'
2023-06-02 00:20:09,063:INFO:pyemd2:main.py:126:handleKline:2217508: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
17421  20230601   233000    233959  1685633999  26892.7  26882.2
17422  20230601   234000    234959  1685634599  26882.2  26866.5
17423  20230601   235000    235959  1685635199  26866.6  26884.2
17424  20230602   000000    000959  1685635799  26884.2  26895.6
17425  20230602   001000    001959  1685636399  26895.7  26919.1
2023-06-02 00:20:09,064:INFO:pyemd2:main.py:127:handleKline:2217508: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}


## /root/FIL/strategy/similarity/log.txt ----- -----

127.0.0.1 - - [02/Jun/2023 00:00:04] "POST / HTTP/1.1" 200 -
2023-06-02 00:00:04,695:INFO:testStrategy:main.py:308:handleOrderFilled:2217133: handleOrderFilled: data=OrderType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'clientorderid': '42300F1685635203948I0L2', 'symbol': 'BTCUSDT', 'gatewayorderid': 1685635204344167, 'quantity': '44.153', 'price': '26884.5', 'stopprice': '0', 'ordertype': '', 'side': 'SELL', 'status': 'FILLED', 'positionside': 'SHORT', 'createtime': 1685635203095, 'updatetime': 1685635204344, 'tradetype': 'usdt', 'selfid': 42300, 'filltrades': [TradeType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'tradeid': 1685635204344, 'clientorderid': '42300F1685635203948I0L2', 'price': '26884.5', 'quantity': '44.153', 'commission': '1187.0313285', 'commissionasset': 'USDT', 'tradetime': 1685635204344, 'tradetype': 'usdt', 'gatetype': 'simulator', 'handletime': 1685635204344}], 'gatetype': 'simulator', 'handletime': 0}
127.0.0.1 - - [02/Jun/2023 00:10:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=2675 

self.closeSec=1685635799, self.tradeDate='20230602', self.openTime='000000', self.closeTime='000959', self.symbol='BTCUSDT', self.open='26884.2', self.close='26895.6'
2023-06-02 00:10:01,077:INFO:testStrategy:main.py:101:handleKline:2217133: self.closeSec=1685635799, self.tradeDate='20230602', self.openTime='000000', self.closeTime='000959',self.symbol='BTCUSDT',self.open='26884.2', self.close='26895.6'
2023-06-02 00:10:01,090:INFO:testStrategy:main.py:102:handleKline:2217133: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
12236  20230601   232000    232959  1685633399  26913.9  26892.6
12237  20230601   233000    233959  1685633999  26892.7  26882.2
12238  20230601   234000    234959  1685634599  26882.2  26866.5
12239  20230601   235000    235959  1685635199  26866.6  26884.2
12240  20230602   000000    000959  1685635799  26884.2  26895.6
2023-06-02 00:10:01,090:INFO:testStrategy:main.py:103:handleKline:2217133: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': True, 'isOpen': False, 'isClose': True, 'isTrig': False, 'isCorr': False}

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=2676 

self.closeSec=1685636399, self.tradeDate='20230602', self.openTime='001000', self.closeTime='001959', self.symbol='BTCUSDT', self.open='26895.7', self.close='26919.1'
127.0.0.1 - - [02/Jun/2023 00:20:04] "POST / HTTP/1.1" 200 -
2023-06-02 00:20:08,647:INFO:testStrategy:main.py:101:handleKline:2217133: self.closeSec=1685636399, self.tradeDate='20230602', self.openTime='001000', self.closeTime='001959',self.symbol='BTCUSDT',self.open='26895.7', self.close='26919.1'
2023-06-02 00:20:08,881:INFO:testStrategy:main.py:102:handleKline:2217133: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
12237  20230601   233000    233959  1685633999  26892.7  26882.2
12238  20230601   234000    234959  1685634599  26882.2  26866.5
12239  20230601   235000    235959  1685635199  26866.6  26884.2
12240  20230602   000000    000959  1685635799  26884.2  26895.6
12241  20230602   001000    001959  1685636399  26895.7  26919.1
2023-06-02 00:20:08,881:INFO:testStrategy:main.py:103:handleKline:2217133: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': True, 'isOpen': False, 'isClose': True, 'isTrig': False, 'isCorr': False}


## /root/FIL/strategy/sr_min/log.txt ----- -----

--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=1, self.total=996015.990996, self.flagDict['side']='buy', self.tradeCount=1, self.count=5344
self.closeSec=1685636399, self.tradeDate='20230602', self.openTime='001500', self.closeTime='001959', self.symbol='BTCUSDT', self.open=26905.9, self.close=26919.2, self.high=26920.0, self.low=26895.8, self.vol=489.721, self.amt=13176681.3824 
127.0.0.1 - - [02/Jun/2023 00:20:01] "POST / HTTP/1.1" 200 -
2023-06-02 00:20:07,090:INFO:sr_min:main.py:172:handleKline:2219263: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5759  20230601   235500    235959  ...         0.0        0.0       0
5760  20230602   000000    000459  ...         0.0        0.0       0
5761  20230602   000500    000959  ...         0.0        0.0       0
5762  20230602   001000    001459  ...         0.0        0.0       0
5763  20230602   001500    001959  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-06-02 00:20:07,125:INFO:sr_min:main.py:175:handleKline:2219263: self.closeSec=1685636399, self.tradeDate='20230602', self.openTime='001500', self.closeTime='001959',self.symbol='BTCUSDT',self.open=26905.9, self.close=26919.2, self.high=26920.0, self.low=26895.8, self.vol=489.721, self.amt=13176681.3824, ukdf['pct'].iloc[-1]=0.000494 , ukdf['amount'].iloc[-1]=13176681.3824, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5763, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '37.141', 'enterprice': '26844', 'countrevence': '0', 'unrealprofit': '2752.1481', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '26918.1', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=1
127.0.0.1 - - [02/Jun/2023 00:25:00] "POST / HTTP/1.1" 200 -
--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=1, self.total=996015.990996, self.flagDict['side']='buy', self.tradeCount=1, self.count=5345
self.closeSec=1685636699, self.tradeDate='20230602', self.openTime='002000', self.closeTime='002459', self.symbol='BTCUSDT', self.open=26919.2, self.close=26909.8, self.high=26924.0, self.low=26909.8, self.vol=705.809, self.amt=18998284.8741 
2023-06-02 00:25:00,841:INFO:sr_min:main.py:172:handleKline:2219263: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5760  20230602   000000    000459  ...         0.0        0.0       0
5761  20230602   000500    000959  ...         0.0        0.0       0
5762  20230602   001000    001459  ...         0.0        0.0       0
5763  20230602   001500    001959  ...         0.0        0.0       0
5764  20230602   002000    002459  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-06-02 00:25:00,846:INFO:sr_min:main.py:175:handleKline:2219263: self.closeSec=1685636699, self.tradeDate='20230602', self.openTime='002000', self.closeTime='002459',self.symbol='BTCUSDT',self.open=26919.2, self.close=26909.8, self.high=26924.0, self.low=26909.8, self.vol=705.809, self.amt=18998284.8741, ukdf['pct'].iloc[-1]=-0.000349 , ukdf['amount'].iloc[-1]=18998284.8741, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5764, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '37.141', 'enterprice': '26844', 'countrevence': '0', 'unrealprofit': '2548.30316038519', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '26912.61159259', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=1


## /root/FIL/strategy/s_rsrs/log.txt ----- -----

723  20230601   120000    155959  1685606399  ...    723  0.684852  0.484603     NaN
724  20230601   160000    195959  1685620799  ...    724  0.732305  0.626848     1.0

[5 rows x 15 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '55.249', 'enterprice': '26128.2', 'countrevence': '0', 'unrealprofit': '41723.62388438852', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '26883.39238148', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'numpy.int64'>, curSign=1, self.sign=1
--handleKline--:  version='2.0.0', self.name='s_rsrs', self.symbol='BTCUSDT', interval='4h', intervalSec=14400, wid=25, thd=0.6, self.sign=1, self.total=1442113.3648782002, self.flagDict['side']='buy', self.tradeCount=3, self.count=111127.0.0.1 - - [02/Jun/2023 00:00:02] "POST / HTTP/1.1" 200 -

self.closeSec=1685635199, self.tradeDate='20230601', self.openTime='200000', self.closeTime='235959', self.symbol='BTCUSDT', self.open=26881.6, self.close=26884.2, self.high=26974.0, self.low=26773.2, self.vol=59027.609, self.amt=1586971251.1695 
2023-06-02 00:00:02,123:INFO:s_rsrs:main.py:141:handleKline:2218689: self.closeSec=1685635199, self.tradeDate='20230601', self.openTime='200000', self.closeTime='235959',self.symbol='BTCUSDT',self.open=26881.6, self.close=26884.2, self.high=26974.0, self.low=26773.2, self.vol=59027.609, self.amt=1586971251.1695 
2023-06-02 00:00:02,158:INFO:s_rsrs:main.py:142:handleKline:2218689: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime  ...         vol           amt       pct
721  20230601   040000    075959  ...   40645.961  1.103126e+09  0.007523
722  20230601   080000    115959  ...  121061.589  3.261094e+09 -0.015900
723  20230601   120000    155959  ...   39306.804  1.053711e+09  0.000803
724  20230601   160000    195959  ...   36263.422  9.746964e+08  0.003419
725  20230601   200000    235959  ...   59027.609  1.586971e+09  0.000093

[5 rows x 11 columns]
2023-06-02 00:00:04,133:INFO:s_rsrs:main.py:151:handleKline:2218689: df_s.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec  ...  index      beta    zscore  signal
721  20230601   040000    075959  1685577599  ...    721  0.807567  0.836682     1.0
722  20230601   080000    115959  1685591999  ...    722  0.590263  0.196307     NaN
723  20230601   120000    155959  1685606399  ...    723  0.684852  0.484603     NaN
724  20230601   160000    195959  1685620799  ...    724  0.732305  0.626848     1.0
725  20230601   200000    235959  1685635199  ...    725  0.774015  0.749031     1.0

[5 rows x 15 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '55.249', 'enterprice': '26128.2', 'countrevence': '0', 'unrealprofit': '41790.3436', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '26884.6', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'numpy.int64'>, curSign=1, self.sign=1


