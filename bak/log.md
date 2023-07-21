# 20230722 00:26:01

## /root/FIL/strategy/amihud/log.txt ----- -----

--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=373746.4768026, self.flagDict['side']='sell', self.tradeCount=2, self.count=19744
self.closeSec=1689956399, self.tradeDate='20230722', self.openTime='001500', self.closeTime='001959', self.symbol='BTCUSDT', self.open=29814.1, self.close=29824.0, self.high=29824.0, self.low=29795.0, self.vol=1011.796, self.amt=30160344.6914 
127.0.0.1 - - [22/Jul/2023 00:20:01] "POST / HTTP/1.1" 200 -
2023-07-22 00:20:05,204:INFO:amihud:main.py:172:handleKline:2219019: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5759  20230721   235500    235959  ...         0.0        0.0       0
5760  20230722   000000    000459  ...         0.0        0.0       0
5761  20230722   000500    000959  ...         0.0        0.0       0
5762  20230722   001000    001459  ...         0.0        0.0       0
5763  20230722   001500    001959  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-07-22 00:20:05,223:INFO:amihud:main.py:175:handleKline:2219019: self.closeSec=1689956399, self.tradeDate='20230722', self.openTime='001500', self.closeTime='001959',self.symbol='BTCUSDT',self.open=29814.1, self.close=29824.0, self.high=29824.0, self.low=29795.0, self.vol=1011.796, self.amt=30160344.6914, ukdf['pct'].iloc[-1]=0.000329 , ukdf['amount'].iloc[-1]=30160344.6914, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5763, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '13.926', 'enterprice': '26864.9', 'countrevence': '0', 'unrealprofit': '-41207.034', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '29823.9', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1
127.0.0.1 - - [22/Jul/2023 00:25:00] "POST / HTTP/1.1" 200 -
--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=373746.4768026, self.flagDict['side']='sell', self.tradeCount=2, self.count=19745
self.closeSec=1689956699, self.tradeDate='20230722', self.openTime='002000', self.closeTime='002459', self.symbol='BTCUSDT', self.open=29824.0, self.close=29817.8, self.high=29830.6, self.low=29812.3, self.vol=293.448, self.amt=8750554.0857 
2023-07-22 00:25:00,752:INFO:amihud:main.py:172:handleKline:2219019: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5760  20230722   000000    000459  ...         0.0        0.0       0
5761  20230722   000500    000959  ...         0.0        0.0       0
5762  20230722   001000    001459  ...         0.0        0.0       0
5763  20230722   001500    001959  ...         0.0        0.0       0
5764  20230722   002000    002459  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-07-22 00:25:00,752:INFO:amihud:main.py:175:handleKline:2219019: self.closeSec=1689956699, self.tradeDate='20230722', self.openTime='002000', self.closeTime='002459',self.symbol='BTCUSDT',self.open=29824.0, self.close=29817.8, self.high=29830.6, self.low=29812.3, self.vol=293.448, self.amt=8750554.0857, ukdf['pct'].iloc[-1]=-0.000208 , ukdf['amount'].iloc[-1]=8750554.0857, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5764, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '13.926', 'enterprice': '26864.9', 'countrevence': '0', 'unrealprofit': '-41120.6928', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '29817.7', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1


## /root/FIL/strategy/factorcheck/log.txt ----- -----


self.closeSec=1689956399, self.tradeDate='20230722', self.openTime='001500', self.closeTime='001959', self.symbol='BTCUSDT', self.open=29814.1, self.close=29824.0, self.high=29824.0, self.low=29795.0 
127.0.0.1 - - [22/Jul/2023 00:20:01] "POST / HTTP/1.1" 200 -
2023-07-22 00:20:04,043:INFO:factorcheck2:main.py:126:handleKline:2218005: self.closeSec=1689956399, self.tradeDate='20230722', self.openTime='001500', self.closeTime='001959',self.symbol='BTCUSDT',self.open=29814.1, self.close=29824.0, self.high=29824.0, self.low=29795.0   
2023-07-22 00:20:04,845:INFO:factorcheck2:main.py:127:handleKline:2218005: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime    closeSec  ...      low       pct  index  idx
1439  20230721   235500    235959  1689955199  ...  29845.0 -0.000003   1727    5
1440  20230722   000000    000459  1689955499  ...  29844.1 -0.000067   1440    0
1441  20230722   000500    000959  1689955799  ...  29816.4 -0.001039   1441    1
1442  20230722   001000    001459  1689956099  ...  29812.4 -0.000161   1442    2
1443  20230722   001500    001959  1689956399  ...  29795.0  0.000329   1443    3

[5 rows x 11 columns]
2023-07-22 00:20:04,854:INFO:factorcheck2:main.py:128:handleKline:2218005: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}
127.0.0.1 - - [22/Jul/2023 00:25:00] "POST / HTTP/1.1" 200 -

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=76, self.factor=0.5042953690069141, self.count=19747 

self.closeSec=1689956699, self.tradeDate='20230722', self.openTime='002000', self.closeTime='002459', self.symbol='BTCUSDT', self.open=29824.0, self.close=29817.8, self.high=29830.6, self.low=29812.3 
2023-07-22 00:25:00,718:INFO:factorcheck2:main.py:126:handleKline:2218005: self.closeSec=1689956699, self.tradeDate='20230722', self.openTime='002000', self.closeTime='002459',self.symbol='BTCUSDT',self.open=29824.0, self.close=29817.8, self.high=29830.6, self.low=29812.3   
2023-07-22 00:25:00,739:INFO:factorcheck2:main.py:127:handleKline:2218005: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime    closeSec  ...      low       pct  index  idx
1440  20230722   000000    000459  1689955499  ...  29844.1 -0.000067   1440    0
1441  20230722   000500    000959  1689955799  ...  29816.4 -0.001039   1441    1
1442  20230722   001000    001459  1689956099  ...  29812.4 -0.000161   1442    2
1443  20230722   001500    001959  1689956399  ...  29795.0  0.000329   1443    3
1444  20230722   002000    002459  1689956699  ...  29812.3 -0.000208   1444    4

[5 rows x 11 columns]
2023-07-22 00:25:00,739:INFO:factorcheck2:main.py:128:handleKline:2218005: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}


## /root/FIL/strategy/logic/log.txt ----- -----

2023-07-22 00:00:17,749:DEBUG:logic:main.py:463:getModel:2218526: df_s.iloc[-5:,:] :
          date closeTime     open  ...    alpha58   alpha67   alpha72
5802  20230721    212959  29854.4  ...  50.000000  0.486750  0.517159
5803  20230721    215959  29848.4  ...  49.583333  0.474628  0.504943
5804  20230721    222959  29799.4  ...  49.166667  0.471595  0.499144
5805  20230721    225959  29787.1  ...  49.583333  0.492286  0.484960
5806  20230721    232959  29864.4  ...  49.166667  0.490641  0.473182

[5 rows x 33 columns]
0.5073529411764706
acc is : 0.5073529411764706
2023-07-22 00:00:17,812:INFO:logic:main.py:468:getModel:2218526: df_pred.iloc[-5:,:] :
     pred    prob_0    prob_1  actual  ...       nav  sign  cost_        bm
539     0  0.505682  0.494318       0  ...  0.950409   1.0    0.0  0.990013
540     1  0.494056  0.505944       0  ...  0.950014   1.0    0.0  0.989601
541     1  0.498601  0.501399       1  ...  0.952486   1.0    0.0  0.992176
542     0  0.522038  0.477962       0  ...  0.952278   1.0    0.0  0.991960
543     1  0.496715  0.503285       0  ...  0.952087   1.0    0.0  0.991761

[5 rows x 10 columns]
2023-07-22 00:00:17,825:INFO:logic:main.py:478:getModel:2218526: df_panel.iloc[-5:,:] :
    pred    prob_0    prob_1  actual  ...       nav  sign  cost_        bm
45     0  0.505963  0.494037       0  ...  0.921712   1.0    0.0  0.990757
46     1  0.494600  0.505400       0  ...  0.921328   1.0    0.0  0.990460
47     1  0.499150  0.500850       1  ...  0.923725   1.0    0.0  0.993037
48     0  0.522313  0.477687       0  ...  0.923524   1.0    0.0  0.992623
49     1  0.496715  0.503285       0  ...  0.952087   1.0    0.0  0.991761

[5 rows x 10 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '23.444', 'enterprice': '29839.3', 'countrevence': '0', 'unrealprofit': '308.06566725296', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '29852.44049084', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}


## /root/FIL/strategy/modifiedmom/log.txt ----- -----

127.0.0.1 - - [22/Jul/2023 00:00:04] "POST / HTTP/1.1" 200 -
2023-07-22 00:00:04,178:INFO:modifiedmom:main.py:319:handleOrderFilled:2218259: handleOrderFilled: data=OrderType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'clientorderid': '42706F1689955203587I0L59', 'symbol': 'BTCUSDT', 'gatewayorderid': 1689955203955553, 'quantity': '24.908', 'price': '29851.9', 'stopprice': '0', 'ordertype': '', 'side': 'SELL', 'status': 'FILLED', 'positionside': 'SHORT', 'createtime': 1689955202614, 'updatetime': 1689955203955, 'tradetype': 'usdt', 'selfid': 42706, 'filltrades': [TradeType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'tradeid': 1689955203955, 'clientorderid': '42706F1689955203587I0L59', 'price': '29851.9', 'quantity': '24.908', 'commission': '743.5511252', 'commissionasset': 'USDT', 'tradetime': 1689955203955, 'tradetype': 'usdt', 'gatetype': 'simulator', 'handletime': 1689955203955}], 'gatetype': 'simulator', 'handletime': 0}
127.0.0.1 - - [22/Jul/2023 00:10:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=9872 

self.closeSec=1689955799, self.tradeDate='20230722', self.openTime='000000', self.closeTime='000959', self.symbol='BTCUSDT', self.open='29852', self.close='29819'
2023-07-22 00:10:01,085:INFO:modifiedmom:main.py:144:handleKline:2218259: self.closeSec=1689955799, self.tradeDate='20230722', self.openTime='000000', self.closeTime='000959',self.symbol='BTCUSDT',self.open='29852', self.close='29819'
2023-07-22 00:10:01,096:INFO:modifiedmom:main.py:145:handleKline:2218259: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec     open    close       pct
572  20230721   232000    232959  1689953399  29852.9    29858  0.000167
573  20230721   233000    233959  1689953999    29858  29850.9 -0.000238
574  20230721   234000    234959  1689954599  29854.1  29863.4  0.000419
575  20230721   235000    235959  1689955199  29863.5    29852 -0.000382
576  20230722   000000    000959  1689955799    29852    29819 -0.001105
2023-07-22 00:10:01,098:INFO:modifiedmom:main.py:146:handleKline:2218259: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': True, 'isOpen': False, 'isClose': True, 'isTrig': False}

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=9873 

self.closeSec=1689956399, self.tradeDate='20230722', self.openTime='001000', self.closeTime='001959', self.symbol='BTCUSDT', self.open='29818.9', self.close='29824'
127.0.0.1 - - [22/Jul/2023 00:20:04] "POST / HTTP/1.1" 200 -
2023-07-22 00:20:08,206:INFO:modifiedmom:main.py:144:handleKline:2218259: self.closeSec=1689956399, self.tradeDate='20230722', self.openTime='001000', self.closeTime='001959',self.symbol='BTCUSDT',self.open='29818.9', self.close='29824'
2023-07-22 00:20:08,219:INFO:modifiedmom:main.py:145:handleKline:2218259: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec     open    close       pct
573  20230721   233000    233959  1689953999    29858  29850.9 -0.000238
574  20230721   234000    234959  1689954599  29854.1  29863.4  0.000419
575  20230721   235000    235959  1689955199  29863.5    29852 -0.000382
576  20230722   000000    000959  1689955799    29852    29819 -0.001105
577  20230722   001000    001959  1689956399  29818.9    29824  0.000168
2023-07-22 00:20:08,220:INFO:modifiedmom:main.py:146:handleKline:2218259: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': True, 'isOpen': False, 'isClose': True, 'isTrig': False}


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

2023-07-22 00:00:02,108:INFO:pyemd2:main.py:127:handleKline:2217508: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}
2023-07-22 00:00:02,164:INFO:pyemd2:main.py:190:insertFactor:2217508: curDateTime:7220000, name:pyemd2, symbol:BTCUSDT, tradeDate:20230721, closeTime:235959, close:29852, total:1009051.1255403, pct_pre:-0.0033071531007492494, thd:0.09211998780301456, side:sell 

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=9875 

self.closeSec=1689955799, self.tradeDate='20230722', self.openTime='000000', self.closeTime='000959', self.symbol='BTCUSDT', self.open='29852', self.close='29819'
127.0.0.1 - - [22/Jul/2023 00:10:01] "POST / HTTP/1.1" 200 -
2023-07-22 00:10:01,088:INFO:pyemd2:main.py:125:handleKline:2217508: self.closeSec=1689955799, self.tradeDate='20230722', self.openTime='000000', self.closeTime='000959',self.symbol='BTCUSDT',self.open='29852', self.close='29819'
2023-07-22 00:10:01,103:INFO:pyemd2:main.py:126:handleKline:2217508: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
17420  20230721   232000    232959  1689953399  29852.9    29858
17421  20230721   233000    233959  1689953999    29858  29850.9
17422  20230721   234000    234959  1689954599  29854.1  29863.4
17423  20230721   235000    235959  1689955199  29863.5    29852
17424  20230722   000000    000959  1689955799    29852    29819
2023-07-22 00:10:01,103:INFO:pyemd2:main.py:127:handleKline:2217508: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=9876 

self.closeSec=1689956399, self.tradeDate='20230722', self.openTime='001000', self.closeTime='001959', self.symbol='BTCUSDT', self.open='29818.9', self.close='29824'
127.0.0.1 - - [22/Jul/2023 00:20:04] "POST / HTTP/1.1" 200 -
2023-07-22 00:20:07,055:INFO:pyemd2:main.py:125:handleKline:2217508: self.closeSec=1689956399, self.tradeDate='20230722', self.openTime='001000', self.closeTime='001959',self.symbol='BTCUSDT',self.open='29818.9', self.close='29824'
2023-07-22 00:20:07,385:INFO:pyemd2:main.py:126:handleKline:2217508: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
17421  20230721   233000    233959  1689953999    29858  29850.9
17422  20230721   234000    234959  1689954599  29854.1  29863.4
17423  20230721   235000    235959  1689955199  29863.5    29852
17424  20230722   000000    000959  1689955799    29852    29819
17425  20230722   001000    001959  1689956399  29818.9    29824
2023-07-22 00:20:07,386:INFO:pyemd2:main.py:127:handleKline:2217508: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}


## /root/FIL/strategy/similarity/log.txt ----- -----

127.0.0.1 - - [22/Jul/2023 00:00:04] "POST / HTTP/1.1" 200 -
2023-07-22 00:00:04,298:INFO:testStrategy:main.py:308:handleOrderFilled:2217133: handleOrderFilled: data=OrderType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'clientorderid': '42707F1689955203625I0L2', 'symbol': 'BTCUSDT', 'gatewayorderid': 1689955204013616, 'quantity': '37.995', 'price': '29851.9', 'stopprice': '0', 'ordertype': '', 'side': 'SELL', 'status': 'FILLED', 'positionside': 'SHORT', 'createtime': 1689955202616, 'updatetime': 1689955204013, 'tradetype': 'usdt', 'selfid': 42707, 'filltrades': [TradeType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'tradeid': 1689955204013, 'clientorderid': '42707F1689955203625I0L2', 'price': '29851.9', 'quantity': '37.995', 'commission': '1134.2229405', 'commissionasset': 'USDT', 'tradetime': 1689955204013, 'tradetype': 'usdt', 'gatetype': 'simulator', 'handletime': 1689955204013}], 'gatetype': 'simulator', 'handletime': 0}
127.0.0.1 - - [22/Jul/2023 00:10:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=9875 

self.closeSec=1689955799, self.tradeDate='20230722', self.openTime='000000', self.closeTime='000959', self.symbol='BTCUSDT', self.open='29852', self.close='29819'
2023-07-22 00:10:01,090:INFO:testStrategy:main.py:101:handleKline:2217133: self.closeSec=1689955799, self.tradeDate='20230722', self.openTime='000000', self.closeTime='000959',self.symbol='BTCUSDT',self.open='29852', self.close='29819'
2023-07-22 00:10:01,096:INFO:testStrategy:main.py:102:handleKline:2217133: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
12236  20230721   232000    232959  1689953399  29852.9    29858
12237  20230721   233000    233959  1689953999    29858  29850.9
12238  20230721   234000    234959  1689954599  29854.1  29863.4
12239  20230721   235000    235959  1689955199  29863.5    29852
12240  20230722   000000    000959  1689955799    29852    29819
2023-07-22 00:10:01,096:INFO:testStrategy:main.py:103:handleKline:2217133: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': True, 'isOpen': False, 'isClose': True, 'isTrig': False, 'isCorr': False}

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=9876 

self.closeSec=1689956399, self.tradeDate='20230722', self.openTime='001000', self.closeTime='001959', self.symbol='BTCUSDT', self.open='29818.9', self.close='29824'
127.0.0.1 - - [22/Jul/2023 00:20:04] "POST / HTTP/1.1" 200 -
2023-07-22 00:20:06,845:INFO:testStrategy:main.py:101:handleKline:2217133: self.closeSec=1689956399, self.tradeDate='20230722', self.openTime='001000', self.closeTime='001959',self.symbol='BTCUSDT',self.open='29818.9', self.close='29824'
2023-07-22 00:20:07,184:INFO:testStrategy:main.py:102:handleKline:2217133: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
12237  20230721   233000    233959  1689953999    29858  29850.9
12238  20230721   234000    234959  1689954599  29854.1  29863.4
12239  20230721   235000    235959  1689955199  29863.5    29852
12240  20230722   000000    000959  1689955799    29852    29819
12241  20230722   001000    001959  1689956399  29818.9    29824
2023-07-22 00:20:07,184:INFO:testStrategy:main.py:103:handleKline:2217133: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': True, 'isOpen': False, 'isClose': True, 'isTrig': False, 'isCorr': False}


## /root/FIL/strategy/sr_min/log.txt ----- -----

--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=1, self.total=996015.990996, self.flagDict['side']='buy', self.tradeCount=1, self.count=19744
self.closeSec=1689956399, self.tradeDate='20230722', self.openTime='001500', self.closeTime='001959', self.symbol='BTCUSDT', self.open=29814.1, self.close=29824.0, self.high=29824.0, self.low=29795.0, self.vol=1011.796, self.amt=30160344.6914 
127.0.0.1 - - [22/Jul/2023 00:20:01] "POST / HTTP/1.1" 200 -
2023-07-22 00:20:05,274:INFO:sr_min:main.py:172:handleKline:2219263: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5759  20230721   235500    235959  ...         0.0        0.0       0
5760  20230722   000000    000459  ...         0.0        0.0       0
5761  20230722   000500    000959  ...         0.0        0.0       0
5762  20230722   001000    001459  ...         0.0        0.0       0
5763  20230722   001500    001959  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-07-22 00:20:05,284:INFO:sr_min:main.py:175:handleKline:2219263: self.closeSec=1689956399, self.tradeDate='20230722', self.openTime='001500', self.closeTime='001959',self.symbol='BTCUSDT',self.open=29814.1, self.close=29824.0, self.high=29824.0, self.low=29795.0, self.vol=1011.796, self.amt=30160344.6914, ukdf['pct'].iloc[-1]=0.000329 , ukdf['amount'].iloc[-1]=30160344.6914, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5763, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '37.141', 'enterprice': '26844', 'countrevence': '0', 'unrealprofit': '110676.4659', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '29823.9', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=1
127.0.0.1 - - [22/Jul/2023 00:25:00] "POST / HTTP/1.1" 200 -
--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=1, self.total=996015.990996, self.flagDict['side']='buy', self.tradeCount=1, self.count=19745
self.closeSec=1689956699, self.tradeDate='20230722', self.openTime='002000', self.closeTime='002459', self.symbol='BTCUSDT', self.open=29824.0, self.close=29817.8, self.high=29830.6, self.low=29812.3, self.vol=293.448, self.amt=8750554.0857 
2023-07-22 00:25:00,754:INFO:sr_min:main.py:172:handleKline:2219263: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5760  20230722   000000    000459  ...         0.0        0.0       0
5761  20230722   000500    000959  ...         0.0        0.0       0
5762  20230722   001000    001459  ...         0.0        0.0       0
5763  20230722   001500    001959  ...         0.0        0.0       0
5764  20230722   002000    002459  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-07-22 00:25:00,755:INFO:sr_min:main.py:175:handleKline:2219263: self.closeSec=1689956699, self.tradeDate='20230722', self.openTime='002000', self.closeTime='002459',self.symbol='BTCUSDT',self.open=29824.0, self.close=29817.8, self.high=29830.6, self.low=29812.3, self.vol=293.448, self.amt=8750554.0857, ukdf['pct'].iloc[-1]=-0.000208 , ukdf['amount'].iloc[-1]=8750554.0857, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5764, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '37.141', 'enterprice': '26844', 'countrevence': '0', 'unrealprofit': '110446.1917', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '29817.7', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=1


## /root/FIL/strategy/s_rsrs/log.txt ----- -----

723  20230721   120000    155959  1689926399  ...    723  0.141051 -1.114406    -1.0
724  20230721   160000    195959  1689940799  ...    724  0.146010 -1.068862    -1.0

[5 rows x 15 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '52.176', 'enterprice': '29870.6', 'countrevence': '0', 'unrealprofit': '5486.41572124224', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '29765.44790476', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'numpy.int64'>, curSign=-1, self.sign=-1
--handleKline--:  version='2.0.0', self.name='s_rsrs', self.symbol='BTCUSDT', interval='4h', intervalSec=14400, wid=25, thd=0.6, self.sign=-1, self.total=1556969.8971744, self.flagDict['side']='sell', self.tradeCount=12, self.count=411
self.closeSec=1689955199, self.tradeDate='20230721', self.openTime='200000', self.closeTime='235959', self.symbol='BTCUSDT', self.open=29764.8, self.close=29852.0, self.high=29904.7, self.low=29764.7, self.vol=46739.642, self.amt=1394601576.622 
127.0.0.1 - - [22/Jul/2023 00:00:01] "POST / HTTP/1.1" 200 -
2023-07-22 00:00:01,717:INFO:s_rsrs:main.py:141:handleKline:2218689: self.closeSec=1689955199, self.tradeDate='20230721', self.openTime='200000', self.closeTime='235959',self.symbol='BTCUSDT',self.open=29764.8, self.close=29852.0, self.high=29904.7, self.low=29764.7, self.vol=46739.642, self.amt=1394601576.622 
2023-07-22 00:00:01,732:INFO:s_rsrs:main.py:142:handleKline:2218689: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime  ...        vol           amt       pct
721  20230721   040000    075959  ...  28490.094  8.484414e+08  0.001567
722  20230721   080000    115959  ...  38621.219  1.152736e+09  0.003132
723  20230721   120000    155959  ...  26891.176  8.016709e+08 -0.004233
724  20230721   160000    195959  ...  28024.428  8.344178e+08  0.000235
725  20230721   200000    235959  ...  46739.642  1.394602e+09  0.002930

[5 rows x 11 columns]
2023-07-22 00:00:02,528:INFO:s_rsrs:main.py:151:handleKline:2218689: df_s.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec  ...  index      beta    zscore  signal
721  20230721   040000    075959  1689897599  ...    721  0.156485 -1.097778    -1.0
722  20230721   080000    115959  1689911999  ...    722  0.148863 -1.105886    -1.0
723  20230721   120000    155959  1689926399  ...    723  0.141051 -1.114406    -1.0
724  20230721   160000    195959  1689940799  ...    724  0.146010 -1.068862    -1.0
725  20230721   200000    235959  1689955199  ...    725  0.127920 -1.135281    -1.0

[5 rows x 15 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '52.176', 'enterprice': '29870.6', 'countrevence': '0', 'unrealprofit': '967.88429451888', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '29852.04962637', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'numpy.int64'>, curSign=-1, self.sign=-1


