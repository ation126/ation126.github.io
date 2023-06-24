# 20230625 00:26:01

## /root/FIL/strategy/amihud/log.txt ----- -----

--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=373746.4768026, self.flagDict['side']='sell', self.tradeCount=2, self.count=11968
self.closeSec=1687623599, self.tradeDate='20230625', self.openTime='001500', self.closeTime='001959', self.symbol='BTCUSDT', self.open=30441.9, self.close=30450.5, self.high=30496.7, self.low=30432.4, self.vol=3538.162, self.amt=107795583.92375 
127.0.0.1 - - [25/Jun/2023 00:20:01] "POST / HTTP/1.1" 200 -
2023-06-25 00:20:07,393:INFO:amihud:main.py:172:handleKline:2219019: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5759  20230624   235500    235959  ...         0.0        0.0       0
5760  20230625   000000    000459  ...         0.0        0.0       0
5761  20230625   000500    000959  ...         0.0        0.0       0
5762  20230625   001000    001459  ...         0.0        0.0       0
5763  20230625   001500    001959  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-06-25 00:20:07,434:INFO:amihud:main.py:175:handleKline:2219019: self.closeSec=1687623599, self.tradeDate='20230625', self.openTime='001500', self.closeTime='001959',self.symbol='BTCUSDT',self.open=30441.9, self.close=30450.5, self.high=30496.7, self.low=30432.4, self.vol=3538.162, self.amt=107795583.92375, ukdf['pct'].iloc[-1]=0.000283 , ukdf['amount'].iloc[-1]=107795583.92375, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5763, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '13.926', 'enterprice': '26864.9', 'countrevence': '0', 'unrealprofit': '-50024.9772', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '30457.1', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1
127.0.0.1 - - [25/Jun/2023 00:25:00] "POST / HTTP/1.1" 200 -
--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=373746.4768026, self.flagDict['side']='sell', self.tradeCount=2, self.count=11969
self.closeSec=1687623899, self.tradeDate='20230625', self.openTime='002000', self.closeTime='002459', self.symbol='BTCUSDT', self.open=30450.5, self.close=30425.0, self.high=30463.7, self.low=30422.0, self.vol=1131.436, self.amt=34445071.1517 
2023-06-25 00:25:00,828:INFO:amihud:main.py:172:handleKline:2219019: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5760  20230625   000000    000459  ...         0.0        0.0       0
5761  20230625   000500    000959  ...         0.0        0.0       0
5762  20230625   001000    001459  ...         0.0        0.0       0
5763  20230625   001500    001959  ...         0.0        0.0       0
5764  20230625   002000    002459  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-06-25 00:25:00,829:INFO:amihud:main.py:175:handleKline:2219019: self.closeSec=1687623899, self.tradeDate='20230625', self.openTime='002000', self.closeTime='002459',self.symbol='BTCUSDT',self.open=30450.5, self.close=30425.0, self.high=30463.7, self.low=30422.0, self.vol=1131.436, self.amt=34445071.1517, ukdf['pct'].iloc[-1]=-0.000837 , ukdf['amount'].iloc[-1]=34445071.1517, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5764, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '13.926', 'enterprice': '26864.9', 'countrevence': '0', 'unrealprofit': '-49606.68372345246', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '30427.06312821', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1


## /root/FIL/strategy/factorcheck/log.txt ----- -----


self.closeSec=1687623599, self.tradeDate='20230625', self.openTime='001500', self.closeTime='001959', self.symbol='BTCUSDT', self.open=30441.9, self.close=30450.5, self.high=30496.7, self.low=30432.4 
127.0.0.1 - - [25/Jun/2023 00:20:01] "POST / HTTP/1.1" 200 -
2023-06-25 00:20:04,993:INFO:factorcheck2:main.py:126:handleKline:2218005: self.closeSec=1687623599, self.tradeDate='20230625', self.openTime='001500', self.closeTime='001959',self.symbol='BTCUSDT',self.open=30441.9, self.close=30450.5, self.high=30496.7, self.low=30432.4   
2023-06-25 00:20:06,553:INFO:factorcheck2:main.py:127:handleKline:2218005: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime    closeSec  ...      low       pct  index  idx
1439  20230624   235500    235959  1687622399  ...  30347.8  0.000883   1727    5
1440  20230625   000000    000459  1687622699  ...  30222.0 -0.002403   1440    0
1441  20230625   000500    000959  1687622999  ...  30283.0  0.002270   1441    1
1442  20230625   001000    001459  1687623299  ...  30360.6  0.002034   1442    2
1443  20230625   001500    001959  1687623599  ...  30432.4  0.000283   1443    3

[5 rows x 11 columns]
2023-06-25 00:20:06,563:INFO:factorcheck2:main.py:128:handleKline:2218005: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}
127.0.0.1 - - [25/Jun/2023 00:25:00] "POST / HTTP/1.1" 200 -

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=373, self.factor=0.5103423219819158, self.count=11971 

self.closeSec=1687623899, self.tradeDate='20230625', self.openTime='002000', self.closeTime='002459', self.symbol='BTCUSDT', self.open=30450.5, self.close=30425.0, self.high=30463.7, self.low=30422.0 
2023-06-25 00:25:00,773:INFO:factorcheck2:main.py:126:handleKline:2218005: self.closeSec=1687623899, self.tradeDate='20230625', self.openTime='002000', self.closeTime='002459',self.symbol='BTCUSDT',self.open=30450.5, self.close=30425.0, self.high=30463.7, self.low=30422.0   
2023-06-25 00:25:00,794:INFO:factorcheck2:main.py:127:handleKline:2218005: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime    closeSec  ...      low       pct  index  idx
1440  20230625   000000    000459  1687622699  ...  30222.0 -0.002403   1440    0
1441  20230625   000500    000959  1687622999  ...  30283.0  0.002270   1441    1
1442  20230625   001000    001459  1687623299  ...  30360.6  0.002034   1442    2
1443  20230625   001500    001959  1687623599  ...  30432.4  0.000283   1443    3
1444  20230625   002000    002459  1687623899  ...  30422.0 -0.000837   1444    4

[5 rows x 11 columns]
2023-06-25 00:25:00,794:INFO:factorcheck2:main.py:128:handleKline:2218005: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}


## /root/FIL/strategy/logic/log.txt ----- -----

2023-06-25 00:00:17,908:DEBUG:logic:main.py:463:getModel:2218526: df_s.iloc[-5:,:] :
          date closeTime     open  ...    alpha58   alpha67   alpha72
5802  20230624    212959  30685.0  ...  54.166667  0.540352  0.567233
5803  20230624    215959  30618.0  ...  54.583333  0.541994  0.577700
5804  20230624    222959  30631.1  ...  54.583333  0.541090  0.581690
5805  20230624    225959  30625.1  ...  55.000000  0.548148  0.574594
5806  20230624    232959  30680.1  ...  55.000000  0.529552  0.582731

[5 rows x 33 columns]
0.5606617647058824
acc is : 0.5606617647058824
2023-06-25 00:00:18,001:INFO:logic:main.py:468:getModel:2218526: df_pred.iloc[-5:,:] :
     pred    prob_0    prob_1  actual  ...       nav  sign  cost_        bm
539     1  0.474488  0.525512       1  ...  1.182751  -1.0    0.0  1.175393
540     1  0.492320  0.507680       0  ...  1.182983  -1.0    0.0  1.175163
541     1  0.488054  0.511946       1  ...  1.180854  -1.0    0.0  1.177277
542     1  0.497212  0.502788       0  ...  1.185600  -1.0    0.0  1.172546
543     1  0.466230  0.533770       0  ...  1.192041  -1.0    0.0  1.166176

[5 rows x 10 columns]
2023-06-25 00:00:18,025:INFO:logic:main.py:478:getModel:2218526: df_panel.iloc[-5:,:] :
    pred    prob_0    prob_1  actual  ...       nav  sign  cost_        bm
45     1  0.474524  0.525476       1  ...  1.182751  -1.0    0.0  1.173515
46     1  0.492327  0.507673       0  ...  1.182983  -1.0    0.0  1.174802
47     1  0.488067  0.511933       1  ...  1.180854  -1.0    0.0  1.176916
48     1  0.497214  0.502786       0  ...  1.185600  -1.0    0.0  1.171588
49     1  0.466230  0.533770       0  ...  1.192041  -1.0    0.0  1.166176

[5 rows x 10 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '26.697', 'enterprice': '30938.2', 'countrevence': '0', 'unrealprofit': '14899.60435463346', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '30380.09967582', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}


## /root/FIL/strategy/modifiedmom/log.txt ----- -----

127.0.0.1 - - [25/Jun/2023 00:00:04] "POST / HTTP/1.1" 200 -
2023-06-25 00:00:04,247:INFO:modifiedmom:main.py:319:handleOrderFilled:2218259: handleOrderFilled: data=OrderType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'clientorderid': '42456F1687622403593I0L59', 'symbol': 'BTCUSDT', 'gatewayorderid': 1687622403999187, 'quantity': '26.055', 'price': '30390.9', 'stopprice': '0', 'ordertype': '', 'side': 'BUY', 'status': 'FILLED', 'positionside': 'LONG', 'createtime': 1687622402678, 'updatetime': 1687622403999, 'tradetype': 'usdt', 'selfid': 42456, 'filltrades': [TradeType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'tradeid': 1687622403999, 'clientorderid': '42456F1687622403593I0L59', 'price': '30390.9', 'quantity': '26.055', 'commission': '791.8348995', 'commissionasset': 'USDT', 'tradetime': 1687622403999, 'tradetype': 'usdt', 'gatetype': 'simulator', 'handletime': 1687622403999}], 'gatetype': 'simulator', 'handletime': 0}

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=5984 

self.closeSec=1687622999, self.tradeDate='20230625', self.openTime='000000', self.closeTime='000959', self.symbol='BTCUSDT', self.open='30390.8', self.close='30380.1'
127.0.0.1 - - [25/Jun/2023 00:10:01] "POST / HTTP/1.1" 200 -
2023-06-25 00:10:01,151:INFO:modifiedmom:main.py:144:handleKline:2218259: self.closeSec=1687622999, self.tradeDate='20230625', self.openTime='000000', self.closeTime='000959',self.symbol='BTCUSDT',self.open='30390.8', self.close='30380.1'
2023-06-25 00:10:01,166:INFO:modifiedmom:main.py:145:handleKline:2218259: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec     open    close       pct
572  20230624   232000    232959  1687620599  30527.4  30556.9  0.000970
573  20230624   233000    233959  1687621199  30556.8  30413.8 -0.004683
574  20230624   234000    234959  1687621799  30413.9  30449.5  0.001174
575  20230624   235000    235959  1687622399  30449.5  30390.9 -0.001924
576  20230625   000000    000959  1687622999  30390.8  30380.1 -0.000355
2023-06-25 00:10:01,166:INFO:modifiedmom:main.py:146:handleKline:2218259: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': True, 'isOpen': False, 'isClose': True, 'isTrig': False}

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=5985 

self.closeSec=1687623599, self.tradeDate='20230625', self.openTime='001000', self.closeTime='001959', self.symbol='BTCUSDT', self.open='30382.4', self.close='30450.5'
127.0.0.1 - - [25/Jun/2023 00:20:04] "POST / HTTP/1.1" 200 -
2023-06-25 00:20:07,185:INFO:modifiedmom:main.py:144:handleKline:2218259: self.closeSec=1687623599, self.tradeDate='20230625', self.openTime='001000', self.closeTime='001959',self.symbol='BTCUSDT',self.open='30382.4', self.close='30450.5'
2023-06-25 00:20:07,883:INFO:modifiedmom:main.py:145:handleKline:2218259: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec     open    close       pct
573  20230624   233000    233959  1687621199  30556.8  30413.8 -0.004683
574  20230624   234000    234959  1687621799  30413.9  30449.5  0.001174
575  20230624   235000    235959  1687622399  30449.5  30390.9 -0.001924
576  20230625   000000    000959  1687622999  30390.8  30380.1 -0.000355
577  20230625   001000    001959  1687623599  30382.4  30450.5  0.002317
2023-06-25 00:20:07,884:INFO:modifiedmom:main.py:146:handleKline:2218259: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': True, 'isOpen': False, 'isClose': True, 'isTrig': False}


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

2023-06-25 00:00:02,066:INFO:pyemd2:main.py:127:handleKline:2217508: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}
2023-06-25 00:00:02,168:INFO:pyemd2:main.py:190:insertFactor:2217508: curDateTime:6250000, name:pyemd2, symbol:BTCUSDT, tradeDate:20230624, closeTime:235959, close:30390.9, total:996664.8960504, pct_pre:-0.022137333874177156, thd:0.055219779618982445, side:sell 
127.0.0.1 - - [25/Jun/2023 00:10:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=5987 

self.closeSec=1687622999, self.tradeDate='20230625', self.openTime='000000', self.closeTime='000959', self.symbol='BTCUSDT', self.open='30390.8', self.close='30380.1'
2023-06-25 00:10:01,168:INFO:pyemd2:main.py:125:handleKline:2217508: self.closeSec=1687622999, self.tradeDate='20230625', self.openTime='000000', self.closeTime='000959',self.symbol='BTCUSDT',self.open='30390.8', self.close='30380.1'
2023-06-25 00:10:01,185:INFO:pyemd2:main.py:126:handleKline:2217508: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
17420  20230624   232000    232959  1687620599  30527.4  30556.9
17421  20230624   233000    233959  1687621199  30556.8  30413.8
17422  20230624   234000    234959  1687621799  30413.9  30449.5
17423  20230624   235000    235959  1687622399  30449.5  30390.9
17424  20230625   000000    000959  1687622999  30390.8  30380.1
2023-06-25 00:10:01,185:INFO:pyemd2:main.py:127:handleKline:2217508: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=5988 

self.closeSec=1687623599, self.tradeDate='20230625', self.openTime='001000', self.closeTime='001959', self.symbol='BTCUSDT', self.open='30382.4', self.close='30450.5'
127.0.0.1 - - [25/Jun/2023 00:20:04] "POST / HTTP/1.1" 200 -
2023-06-25 00:20:09,205:INFO:pyemd2:main.py:125:handleKline:2217508: self.closeSec=1687623599, self.tradeDate='20230625', self.openTime='001000', self.closeTime='001959',self.symbol='BTCUSDT',self.open='30382.4', self.close='30450.5'
2023-06-25 00:20:09,333:INFO:pyemd2:main.py:126:handleKline:2217508: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
17421  20230624   233000    233959  1687621199  30556.8  30413.8
17422  20230624   234000    234959  1687621799  30413.9  30449.5
17423  20230624   235000    235959  1687622399  30449.5  30390.9
17424  20230625   000000    000959  1687622999  30390.8  30380.1
17425  20230625   001000    001959  1687623599  30382.4  30450.5
2023-06-25 00:20:09,334:INFO:pyemd2:main.py:127:handleKline:2217508: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}


## /root/FIL/strategy/similarity/log.txt ----- -----

127.0.0.1 - - [25/Jun/2023 00:00:04] "POST / HTTP/1.1" 200 -
2023-06-25 00:00:04,423:INFO:testStrategy:main.py:308:handleOrderFilled:2217133: handleOrderFilled: data=OrderType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'clientorderid': '42457F1687622403626I0L2', 'symbol': 'BTCUSDT', 'gatewayorderid': 1687622404044079, 'quantity': '38.138', 'price': '30390.8', 'stopprice': '0', 'ordertype': '', 'side': 'SELL', 'status': 'FILLED', 'positionside': 'SHORT', 'createtime': 1687622402666, 'updatetime': 1687622404044, 'tradetype': 'usdt', 'selfid': 42457, 'filltrades': [TradeType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'tradeid': 1687622404044, 'clientorderid': '42457F1687622403626I0L2', 'price': '30390.8', 'quantity': '38.138', 'commission': '1159.0443304', 'commissionasset': 'USDT', 'tradetime': 1687622404044, 'tradetype': 'usdt', 'gatetype': 'simulator', 'handletime': 1687622404044}], 'gatetype': 'simulator', 'handletime': 0}

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=5987 

self.closeSec=1687622999, self.tradeDate='20230625', self.openTime='000000', self.closeTime='000959', self.symbol='BTCUSDT', self.open='30390.8', self.close='30380.1'
127.0.0.1 - - [25/Jun/2023 00:10:01] "POST / HTTP/1.1" 200 -
2023-06-25 00:10:01,148:INFO:testStrategy:main.py:101:handleKline:2217133: self.closeSec=1687622999, self.tradeDate='20230625', self.openTime='000000', self.closeTime='000959',self.symbol='BTCUSDT',self.open='30390.8', self.close='30380.1'
2023-06-25 00:10:01,168:INFO:testStrategy:main.py:102:handleKline:2217133: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
12236  20230624   232000    232959  1687620599  30527.4  30556.9
12237  20230624   233000    233959  1687621199  30556.8  30413.8
12238  20230624   234000    234959  1687621799  30413.9  30449.5
12239  20230624   235000    235959  1687622399  30449.5  30390.9
12240  20230625   000000    000959  1687622999  30390.8  30380.1
2023-06-25 00:10:01,168:INFO:testStrategy:main.py:103:handleKline:2217133: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': True, 'isOpen': False, 'isClose': True, 'isTrig': False, 'isCorr': False}

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=5988 

self.closeSec=1687623599, self.tradeDate='20230625', self.openTime='001000', self.closeTime='001959', self.symbol='BTCUSDT', self.open='30382.4', self.close='30450.5'
127.0.0.1 - - [25/Jun/2023 00:20:04] "POST / HTTP/1.1" 200 -
2023-06-25 00:20:08,776:INFO:testStrategy:main.py:101:handleKline:2217133: self.closeSec=1687623599, self.tradeDate='20230625', self.openTime='001000', self.closeTime='001959',self.symbol='BTCUSDT',self.open='30382.4', self.close='30450.5'
2023-06-25 00:20:09,095:INFO:testStrategy:main.py:102:handleKline:2217133: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
12237  20230624   233000    233959  1687621199  30556.8  30413.8
12238  20230624   234000    234959  1687621799  30413.9  30449.5
12239  20230624   235000    235959  1687622399  30449.5  30390.9
12240  20230625   000000    000959  1687622999  30390.8  30380.1
12241  20230625   001000    001959  1687623599  30382.4  30450.5
2023-06-25 00:20:09,096:INFO:testStrategy:main.py:103:handleKline:2217133: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': True, 'isOpen': False, 'isClose': True, 'isTrig': False, 'isCorr': False}


## /root/FIL/strategy/sr_min/log.txt ----- -----

--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=1, self.total=996015.990996, self.flagDict['side']='buy', self.tradeCount=1, self.count=11968
self.closeSec=1687623599, self.tradeDate='20230625', self.openTime='001500', self.closeTime='001959', self.symbol='BTCUSDT', self.open=30441.9, self.close=30450.5, self.high=30496.7, self.low=30432.4, self.vol=3538.162, self.amt=107795583.92375 
127.0.0.1 - - [25/Jun/2023 00:20:01] "POST / HTTP/1.1" 200 -
2023-06-25 00:20:07,383:INFO:sr_min:main.py:172:handleKline:2219263: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5759  20230624   235500    235959  ...         0.0        0.0       0
5760  20230625   000000    000459  ...         0.0        0.0       0
5761  20230625   000500    000959  ...         0.0        0.0       0
5762  20230625   001000    001459  ...         0.0        0.0       0
5763  20230625   001500    001959  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-06-25 00:20:07,424:INFO:sr_min:main.py:175:handleKline:2219263: self.closeSec=1687623599, self.tradeDate='20230625', self.openTime='001500', self.closeTime='001959',self.symbol='BTCUSDT',self.open=30441.9, self.close=30450.5, self.high=30496.7, self.low=30432.4, self.vol=3538.162, self.amt=107795583.92375, ukdf['pct'].iloc[-1]=0.000283 , ukdf['amount'].iloc[-1]=107795583.92375, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5763, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '37.141', 'enterprice': '26844', 'countrevence': '0', 'unrealprofit': '134194.1471', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '30457.1', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=1
127.0.0.1 - - [25/Jun/2023 00:25:00] "POST / HTTP/1.1" 200 -
--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=1, self.total=996015.990996, self.flagDict['side']='buy', self.tradeCount=1, self.count=11969
self.closeSec=1687623899, self.tradeDate='20230625', self.openTime='002000', self.closeTime='002459', self.symbol='BTCUSDT', self.open=30450.5, self.close=30425.0, self.high=30463.7, self.low=30422.0, self.vol=1131.436, self.amt=34445071.1517 
2023-06-25 00:25:00,823:INFO:sr_min:main.py:172:handleKline:2219263: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5760  20230625   000000    000459  ...         0.0        0.0       0
5761  20230625   000500    000959  ...         0.0        0.0       0
5762  20230625   001000    001459  ...         0.0        0.0       0
5763  20230625   001500    001959  ...         0.0        0.0       0
5764  20230625   002000    002459  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-06-25 00:25:00,824:INFO:sr_min:main.py:175:handleKline:2219263: self.closeSec=1687623899, self.tradeDate='20230625', self.openTime='002000', self.closeTime='002459',self.symbol='BTCUSDT',self.open=30450.5, self.close=30425.0, self.high=30463.7, self.low=30422.0, self.vol=1131.436, self.amt=34445071.1517, ukdf['pct'].iloc[-1]=-0.000837 , ukdf['amount'].iloc[-1]=34445071.1517, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5764, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '37.141', 'enterprice': '26844', 'countrevence': '0', 'unrealprofit': '133078.54764484761', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '30427.06312821', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=1


## /root/FIL/strategy/s_rsrs/log.txt ----- -----

723  20230624   120000    155959  1687593599  ...    723  0.910667  0.909653     1.0
724  20230624   160000    195959  1687607999  ...    724  0.831920  0.673413     1.0

[5 rows x 15 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '53.344', 'enterprice': '27977.7', 'countrevence': '0', 'unrealprofit': '144205.297612464', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '30681.0086685', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'numpy.int64'>, curSign=1, self.sign=1
127.0.0.1 - - [25/Jun/2023 00:00:01] "POST / HTTP/1.1" 200 -
--handleKline--:  version='2.0.0', self.name='s_rsrs', self.symbol='BTCUSDT', interval='4h', intervalSec=14400, wid=25, thd=0.6, self.sign=1, self.total=1490949.9863712, self.flagDict['side']='buy', self.tradeCount=7, self.count=249
self.closeSec=1687622399, self.tradeDate='20230624', self.openTime='200000', self.closeTime='235959', self.symbol='BTCUSDT', self.open=30674.8, self.close=30384.3, self.high=30796.5, self.low=30262.0, self.vol=72296.954, self.amt=2209367522.7908 
2023-06-25 00:00:01,584:INFO:s_rsrs:main.py:141:handleKline:2218689: self.closeSec=1687622399, self.tradeDate='20230624', self.openTime='200000', self.closeTime='235959',self.symbol='BTCUSDT',self.open=30674.8, self.close=30384.3, self.high=30796.5, self.low=30262.0, self.vol=72296.954, self.amt=2209367522.7908 
2023-06-25 00:00:01,619:INFO:s_rsrs:main.py:142:handleKline:2218689: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime  ...        vol           amt       pct
721  20230624   040000    075959  ...  66965.089  2.054059e+09 -0.006488
722  20230624   080000    115959  ...  57323.090  1.754468e+09  0.001503
723  20230624   120000    155959  ...  29137.580  8.935192e+08 -0.005081
724  20230624   160000    195959  ...  30744.164  9.420450e+08  0.003648
725  20230624   200000    235959  ...  72296.954  2.209368e+09 -0.009474

[5 rows x 11 columns]
2023-06-25 00:00:03,067:INFO:s_rsrs:main.py:151:handleKline:2218689: df_s.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec  ...  index      beta    zscore  signal
721  20230624   040000    075959  1687564799  ...    721  1.016542  1.251985     1.0
722  20230624   080000    115959  1687579199  ...    722  0.965802  1.084653     1.0
723  20230624   120000    155959  1687593599  ...    723  0.910667  0.909653     1.0
724  20230624   160000    195959  1687607999  ...    724  0.831920  0.673413     1.0
725  20230624   200000    235959  1687622399  ...    725  0.734894  0.390758     NaN

[5 rows x 15 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '53.344', 'enterprice': '27977.7', 'countrevence': '0', 'unrealprofit': '128869.6283079072', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '30393.5223663', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'numpy.int64'>, curSign=-9223372036854775808, self.sign=1


