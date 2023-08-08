# 20230809 00:26:01

## /root/FIL/strategy/amihud/log.txt ----- -----

--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=373746.4768026, self.flagDict['side']='sell', self.tradeCount=2, self.count=24928
self.closeSec=1691511599, self.tradeDate='20230809', self.openTime='001500', self.closeTime='001959', self.symbol='BTCUSDT', self.open=29586.3, self.close=29560.7, self.high=29640.7, self.low=29560.7, self.vol=4665.882, self.amt=138116426.5803 
127.0.0.1 - - [09/Aug/2023 00:20:01] "POST / HTTP/1.1" 200 -
2023-08-09 00:20:06,330:INFO:amihud:main.py:172:handleKline:2219019: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5759  20230808   235500    235959  ...         0.0        0.0       0
5760  20230809   000000    000459  ...         0.0        0.0       0
5761  20230809   000500    000959  ...         0.0        0.0       0
5762  20230809   001000    001459  ...         0.0        0.0       0
5763  20230809   001500    001959  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-08-09 00:20:06,349:INFO:amihud:main.py:175:handleKline:2219019: self.closeSec=1691511599, self.tradeDate='20230809', self.openTime='001500', self.closeTime='001959',self.symbol='BTCUSDT',self.open=29586.3, self.close=29560.7, self.high=29640.7, self.low=29560.7, self.vol=4665.882, self.amt=138116426.5803, ukdf['pct'].iloc[-1]=-0.000835 , ukdf['amount'].iloc[-1]=138116426.5803, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5763, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '13.926', 'enterprice': '26864.9', 'countrevence': '0', 'unrealprofit': '-37626.92100979746', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '29566.81878571', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1
127.0.0.1 - - [09/Aug/2023 00:25:00] "POST / HTTP/1.1" 200 -
--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=373746.4768026, self.flagDict['side']='sell', self.tradeCount=2, self.count=24929
self.closeSec=1691511899, self.tradeDate='20230809', self.openTime='002000', self.closeTime='002459', self.symbol='BTCUSDT', self.open=29560.7, self.close=29577.3, self.high=29577.3, self.low=29546.3, self.vol=1311.691, self.amt=38773678.8576 
2023-08-09 00:25:00,830:INFO:amihud:main.py:172:handleKline:2219019: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5760  20230809   000000    000459  ...         0.0        0.0       0
5761  20230809   000500    000959  ...         0.0        0.0       0
5762  20230809   001000    001459  ...         0.0        0.0       0
5763  20230809   001500    001959  ...         0.0        0.0       0
5764  20230809   002000    002459  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-08-09 00:25:00,830:INFO:amihud:main.py:175:handleKline:2219019: self.closeSec=1691511899, self.tradeDate='20230809', self.openTime='002000', self.closeTime='002459',self.symbol='BTCUSDT',self.open=29560.7, self.close=29577.3, self.high=29577.3, self.low=29546.3, self.vol=1311.691, self.amt=38773678.8576, ukdf['pct'].iloc[-1]=0.000562 , ukdf['amount'].iloc[-1]=38773678.8576, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5764, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '13.926', 'enterprice': '26864.9', 'countrevence': '0', 'unrealprofit': '-37771.4898', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '29577.2', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1


## /root/FIL/strategy/factorcheck/log.txt ----- -----


self.closeSec=1691511599, self.tradeDate='20230809', self.openTime='001500', self.closeTime='001959', self.symbol='BTCUSDT', self.open=29586.3, self.close=29560.7, self.high=29640.7, self.low=29560.7 
127.0.0.1 - - [09/Aug/2023 00:20:01] "POST / HTTP/1.1" 200 -
2023-08-09 00:20:04,434:INFO:factorcheck2:main.py:126:handleKline:2218005: self.closeSec=1691511599, self.tradeDate='20230809', self.openTime='001500', self.closeTime='001959',self.symbol='BTCUSDT',self.open=29586.3, self.close=29560.7, self.high=29640.7, self.low=29560.7   
2023-08-09 00:20:05,549:INFO:factorcheck2:main.py:127:handleKline:2218005: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime    closeSec  ...      low       pct  index  idx
1439  20230808   235500    235959  1691510399  ...  29516.1 -0.000674   1727    5
1440  20230809   000000    000459  1691510699  ...  29516.1  0.000979   1440    0
1441  20230809   000500    000959  1691510999  ...  29540.7  0.000836   1441    1
1442  20230809   001000    001459  1691511299  ...  29566.0  0.000484   1442    2
1443  20230809   001500    001959  1691511599  ...  29560.7 -0.000835   1443    3

[5 rows x 11 columns]
2023-08-09 00:20:05,550:INFO:factorcheck2:main.py:128:handleKline:2218005: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}
127.0.0.1 - - [09/Aug/2023 00:25:00] "POST / HTTP/1.1" 200 -

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=203, self.factor=0.28779464824754303, self.count=24931 

self.closeSec=1691511899, self.tradeDate='20230809', self.openTime='002000', self.closeTime='002459', self.symbol='BTCUSDT', self.open=29560.7, self.close=29577.3, self.high=29577.3, self.low=29546.3 
2023-08-09 00:25:00,788:INFO:factorcheck2:main.py:126:handleKline:2218005: self.closeSec=1691511899, self.tradeDate='20230809', self.openTime='002000', self.closeTime='002459',self.symbol='BTCUSDT',self.open=29560.7, self.close=29577.3, self.high=29577.3, self.low=29546.3   
2023-08-09 00:25:00,802:INFO:factorcheck2:main.py:127:handleKline:2218005: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime    closeSec  ...      low       pct  index  idx
1440  20230809   000000    000459  1691510699  ...  29516.1  0.000979   1440    0
1441  20230809   000500    000959  1691510999  ...  29540.7  0.000836   1441    1
1442  20230809   001000    001459  1691511299  ...  29566.0  0.000484   1442    2
1443  20230809   001500    001959  1691511599  ...  29560.7 -0.000835   1443    3
1444  20230809   002000    002459  1691511899  ...  29546.3  0.000562   1444    4

[5 rows x 11 columns]
2023-08-09 00:25:00,802:INFO:factorcheck2:main.py:128:handleKline:2218005: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}


## /root/FIL/strategy/logic/log.txt ----- -----

2023-08-09 00:00:18,412:DEBUG:logic:main.py:463:getModel:2218526: df_s.iloc[-5:,:] :
          date closeTime     open  ...    alpha58   alpha67   alpha72
5802  20230808    212959  29561.0  ...  49.583333  0.592438  0.171529
5803  20230808    215959  29481.0  ...  49.166667  0.550176  0.190157
5804  20230808    222959  29347.1  ...  49.166667  0.573572  0.200696
5805  20230808    225959  29447.9  ...  48.750000  0.565871  0.213290
5806  20230808    232959  29422.1  ...  49.166667  0.580966  0.217868

[5 rows x 33 columns]
0.5459558823529411
acc is : 0.5459558823529411
2023-08-09 00:00:18,471:INFO:logic:main.py:468:getModel:2218526: df_pred.iloc[-5:,:] :
     pred    prob_0    prob_1  actual  ...       nav  sign  cost_        bm
539     0  0.502208  0.497792       0  ...  0.957792   1.0    0.0  1.007557
540     1  0.473670  0.526330       1  ...  0.961089   1.0    0.0  1.011024
541     0  0.534908  0.465092       0  ...  0.960243   1.0    0.0  1.010135
542     1  0.499675  0.500325       1  ...  0.962466   1.0    0.0  1.012473
543     0  0.521814  0.478186       1  ...  0.963357   1.0    0.0  1.013410

[5 rows x 10 columns]
2023-08-09 00:00:18,482:INFO:logic:main.py:478:getModel:2218526: df_panel.iloc[-5:,:] :
    pred    prob_0    prob_1  actual  ...       nav  sign  cost_        bm
45     0  0.502107  0.497893       0  ...  0.957792   1.0    0.0  1.005899
46     1  0.473385  0.526615       1  ...  0.961089   1.0    0.0  1.009340
47     0  0.534899  0.465101       0  ...  0.960243   1.0    0.0  1.008452
48     1  0.499548  0.500452       1  ...  0.962466   1.0    0.0  1.010568
49     0  0.521814  0.478186       1  ...  0.963357   1.0    0.0  1.013410

[5 rows x 10 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '24.06', 'enterprice': '29131.5', 'countrevence': '0', 'unrealprofit': '9366.558', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '29520.8', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}


## /root/FIL/strategy/modifiedmom/log.txt ----- -----

127.0.0.1 - - [09/Aug/2023 00:00:04] "POST / HTTP/1.1" 200 -
2023-08-09 00:00:04,321:INFO:modifiedmom:main.py:319:handleOrderFilled:2218259: handleOrderFilled: data=OrderType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'clientorderid': '42826F1691510403554I0L59', 'symbol': 'BTCUSDT', 'gatewayorderid': 1691510403995158, 'quantity': '24.6', 'price': '29517.5', 'stopprice': '0', 'ordertype': '', 'side': 'SELL', 'status': 'FILLED', 'positionside': 'SHORT', 'createtime': 1691510402657, 'updatetime': 1691510403995, 'tradetype': 'usdt', 'selfid': 42826, 'filltrades': [TradeType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'tradeid': 1691510403995, 'clientorderid': '42826F1691510403554I0L59', 'price': '29517.5', 'quantity': '24.6', 'commission': '726.1305', 'commissionasset': 'USDT', 'tradetime': 1691510403995, 'tradetype': 'usdt', 'gatetype': 'simulator', 'handletime': 1691510403995}], 'gatetype': 'simulator', 'handletime': 0}

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=12464 

self.closeSec=1691510999, self.tradeDate='20230809', self.openTime='000000', self.closeTime='000959', self.symbol='BTCUSDT', self.open='29517.5', self.close='29571.1'
2023-08-09 00:10:01,126:INFO:modifiedmom:main.py:144:handleKline:2218259: self.closeSec=1691510999, self.tradeDate='20230809', self.openTime='000000', self.closeTime='000959',self.symbol='BTCUSDT',self.open='29517.5', self.close='29571.1'
127.0.0.1 - - [09/Aug/2023 00:10:01] "POST / HTTP/1.1" 200 -
2023-08-09 00:10:01,140:INFO:modifiedmom:main.py:145:handleKline:2218259: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec     open    close       pct
572  20230808   232000    232959  1691508599  29485.3  29490.2  0.000346
573  20230808   233000    233959  1691509199  29490.1  29561.6  0.002421
574  20230808   234000    234959  1691509799  29561.6  29554.4 -0.000244
575  20230808   235000    235959  1691510399  29554.4  29517.5 -0.001249
576  20230809   000000    000959  1691510999  29517.5  29571.1  0.001816
2023-08-09 00:10:01,140:INFO:modifiedmom:main.py:146:handleKline:2218259: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': True, 'isOpen': False, 'isClose': True, 'isTrig': False}

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=12465 

self.closeSec=1691511599, self.tradeDate='20230809', self.openTime='001000', self.closeTime='001959', self.symbol='BTCUSDT', self.open='29571.2', self.close='29560.7'
127.0.0.1 - - [09/Aug/2023 00:20:04] "POST / HTTP/1.1" 200 -
2023-08-09 00:20:06,571:INFO:modifiedmom:main.py:144:handleKline:2218259: self.closeSec=1691511599, self.tradeDate='20230809', self.openTime='001000', self.closeTime='001959',self.symbol='BTCUSDT',self.open='29571.2', self.close='29560.7'
2023-08-09 00:20:07,130:INFO:modifiedmom:main.py:145:handleKline:2218259: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec     open    close       pct
573  20230808   233000    233959  1691509199  29490.1  29561.6  0.002421
574  20230808   234000    234959  1691509799  29561.6  29554.4 -0.000244
575  20230808   235000    235959  1691510399  29554.4  29517.5 -0.001249
576  20230809   000000    000959  1691510999  29517.5  29571.1  0.001816
577  20230809   001000    001959  1691511599  29571.2  29560.7 -0.000352
2023-08-09 00:20:07,139:INFO:modifiedmom:main.py:146:handleKline:2218259: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': True, 'isOpen': False, 'isClose': True, 'isTrig': False}


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

2023-08-09 00:00:02,105:INFO:pyemd2:main.py:127:handleKline:2217508: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}
2023-08-09 00:00:02,169:INFO:pyemd2:main.py:190:insertFactor:2217508: curDateTime:8090000, name:pyemd2, symbol:BTCUSDT, tradeDate:20230808, closeTime:235959, close:29517.5, total:978943.3965659, pct_pre:0.012500433561097424, thd:-0.0356398849817538, side:sell 

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=12467 

self.closeSec=1691510999, self.tradeDate='20230809', self.openTime='000000', self.closeTime='000959', self.symbol='BTCUSDT', self.open='29517.5', self.close='29571.1'
2023-08-09 00:10:01,126:INFO:pyemd2:main.py:125:handleKline:2217508: self.closeSec=1691510999, self.tradeDate='20230809', self.openTime='000000', self.closeTime='000959',self.symbol='BTCUSDT',self.open='29517.5', self.close='29571.1'
127.0.0.1 - - [09/Aug/2023 00:10:01] "POST / HTTP/1.1" 200 -
2023-08-09 00:10:01,133:INFO:pyemd2:main.py:126:handleKline:2217508: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
17420  20230808   232000    232959  1691508599  29485.3  29490.2
17421  20230808   233000    233959  1691509199  29490.1  29561.6
17422  20230808   234000    234959  1691509799  29561.6  29554.4
17423  20230808   235000    235959  1691510399  29554.4  29517.5
17424  20230809   000000    000959  1691510999  29517.5  29571.1
2023-08-09 00:10:01,133:INFO:pyemd2:main.py:127:handleKline:2217508: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=12468 

self.closeSec=1691511599, self.tradeDate='20230809', self.openTime='001000', self.closeTime='001959', self.symbol='BTCUSDT', self.open='29571.2', self.close='29560.7'
127.0.0.1 - - [09/Aug/2023 00:20:04] "POST / HTTP/1.1" 200 -
2023-08-09 00:20:08,211:INFO:pyemd2:main.py:125:handleKline:2217508: self.closeSec=1691511599, self.tradeDate='20230809', self.openTime='001000', self.closeTime='001959',self.symbol='BTCUSDT',self.open='29571.2', self.close='29560.7'
2023-08-09 00:20:08,297:INFO:pyemd2:main.py:126:handleKline:2217508: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
17421  20230808   233000    233959  1691509199  29490.1  29561.6
17422  20230808   234000    234959  1691509799  29561.6  29554.4
17423  20230808   235000    235959  1691510399  29554.4  29517.5
17424  20230809   000000    000959  1691510999  29517.5  29571.1
17425  20230809   001000    001959  1691511599  29571.2  29560.7
2023-08-09 00:20:08,297:INFO:pyemd2:main.py:127:handleKline:2217508: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}


## /root/FIL/strategy/similarity/log.txt ----- -----

127.0.0.1 - - [09/Aug/2023 00:00:04] "POST / HTTP/1.1" 200 -
2023-08-09 00:00:04,185:INFO:testStrategy:main.py:308:handleOrderFilled:2217133: handleOrderFilled: data=OrderType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'clientorderid': '42827F1691510403590I0L2', 'symbol': 'BTCUSDT', 'gatewayorderid': 1691510404007340, 'quantity': '36.755', 'price': '29517.5', 'stopprice': '0', 'ordertype': '', 'side': 'SELL', 'status': 'FILLED', 'positionside': 'SHORT', 'createtime': 1691510402643, 'updatetime': 1691510404007, 'tradetype': 'usdt', 'selfid': 42827, 'filltrades': [TradeType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'tradeid': 1691510404007, 'clientorderid': '42827F1691510403590I0L2', 'price': '29517.5', 'quantity': '36.755', 'commission': '1084.9157125', 'commissionasset': 'USDT', 'tradetime': 1691510404007, 'tradetype': 'usdt', 'gatetype': 'simulator', 'handletime': 1691510404007}], 'gatetype': 'simulator', 'handletime': 0}
127.0.0.1 - - [09/Aug/2023 00:10:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=12467 

self.closeSec=1691510999, self.tradeDate='20230809', self.openTime='000000', self.closeTime='000959', self.symbol='BTCUSDT', self.open='29517.5', self.close='29571.1'
2023-08-09 00:10:01,130:INFO:testStrategy:main.py:101:handleKline:2217133: self.closeSec=1691510999, self.tradeDate='20230809', self.openTime='000000', self.closeTime='000959',self.symbol='BTCUSDT',self.open='29517.5', self.close='29571.1'
2023-08-09 00:10:01,142:INFO:testStrategy:main.py:102:handleKline:2217133: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
12236  20230808   232000    232959  1691508599  29485.3  29490.2
12237  20230808   233000    233959  1691509199  29490.1  29561.6
12238  20230808   234000    234959  1691509799  29561.6  29554.4
12239  20230808   235000    235959  1691510399  29554.4  29517.5
12240  20230809   000000    000959  1691510999  29517.5  29571.1
2023-08-09 00:10:01,142:INFO:testStrategy:main.py:103:handleKline:2217133: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': True, 'isOpen': False, 'isClose': True, 'isTrig': False, 'isCorr': False}

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=12468 

self.closeSec=1691511599, self.tradeDate='20230809', self.openTime='001000', self.closeTime='001959', self.symbol='BTCUSDT', self.open='29571.2', self.close='29560.7'
127.0.0.1 - - [09/Aug/2023 00:20:04] "POST / HTTP/1.1" 200 -
2023-08-09 00:20:08,039:INFO:testStrategy:main.py:101:handleKline:2217133: self.closeSec=1691511599, self.tradeDate='20230809', self.openTime='001000', self.closeTime='001959',self.symbol='BTCUSDT',self.open='29571.2', self.close='29560.7'
2023-08-09 00:20:08,181:INFO:testStrategy:main.py:102:handleKline:2217133: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
12237  20230808   233000    233959  1691509199  29490.1  29561.6
12238  20230808   234000    234959  1691509799  29561.6  29554.4
12239  20230808   235000    235959  1691510399  29554.4  29517.5
12240  20230809   000000    000959  1691510999  29517.5  29571.1
12241  20230809   001000    001959  1691511599  29571.2  29560.7
2023-08-09 00:20:08,182:INFO:testStrategy:main.py:103:handleKline:2217133: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': True, 'isOpen': False, 'isClose': True, 'isTrig': False, 'isCorr': False}


## /root/FIL/strategy/sr_min/log.txt ----- -----

--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=1, self.total=996015.990996, self.flagDict['side']='buy', self.tradeCount=1, self.count=24928
self.closeSec=1691511599, self.tradeDate='20230809', self.openTime='001500', self.closeTime='001959', self.symbol='BTCUSDT', self.open=29586.3, self.close=29560.7, self.high=29640.7, self.low=29560.7, self.vol=4665.882, self.amt=138116426.5803 
127.0.0.1 - - [09/Aug/2023 00:20:01] "POST / HTTP/1.1" 200 -
2023-08-09 00:20:06,279:INFO:sr_min:main.py:172:handleKline:2219263: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5759  20230808   235500    235959  ...         0.0        0.0       0
5760  20230809   000000    000459  ...         0.0        0.0       0
5761  20230809   000500    000959  ...         0.0        0.0       0
5762  20230809   001000    001459  ...         0.0        0.0       0
5763  20230809   001500    001959  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-08-09 00:20:06,300:INFO:sr_min:main.py:175:handleKline:2219263: self.closeSec=1691511599, self.tradeDate='20230809', self.openTime='001500', self.closeTime='001959',self.symbol='BTCUSDT',self.open=29586.3, self.close=29560.7, self.high=29640.7, self.low=29560.7, self.vol=4665.882, self.amt=138116426.5803, ukdf['pct'].iloc[-1]=-0.000835 , ukdf['amount'].iloc[-1]=138116426.5803, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5763, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '37.141', 'enterprice': '26844', 'countrevence': '0', 'unrealprofit': '101128.21252005511', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '29566.81878571', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=1
127.0.0.1 - - [09/Aug/2023 00:25:00] "POST / HTTP/1.1" 200 -
--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=1, self.total=996015.990996, self.flagDict['side']='buy', self.tradeCount=1, self.count=24929
self.closeSec=1691511899, self.tradeDate='20230809', self.openTime='002000', self.closeTime='002459', self.symbol='BTCUSDT', self.open=29560.7, self.close=29577.3, self.high=29577.3, self.low=29546.3, self.vol=1311.691, self.amt=38773678.8576 
2023-08-09 00:25:00,825:INFO:sr_min:main.py:172:handleKline:2219263: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5760  20230809   000000    000459  ...         0.0        0.0       0
5761  20230809   000500    000959  ...         0.0        0.0       0
5762  20230809   001000    001459  ...         0.0        0.0       0
5763  20230809   001500    001959  ...         0.0        0.0       0
5764  20230809   002000    002459  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-08-09 00:25:00,825:INFO:sr_min:main.py:175:handleKline:2219263: self.closeSec=1691511899, self.tradeDate='20230809', self.openTime='002000', self.closeTime='002459',self.symbol='BTCUSDT',self.open=29560.7, self.close=29577.3, self.high=29577.3, self.low=29546.3, self.vol=1311.691, self.amt=38773678.8576, ukdf['pct'].iloc[-1]=0.000562 , ukdf['amount'].iloc[-1]=38773678.8576, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5764, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '37.141', 'enterprice': '26844', 'countrevence': '0', 'unrealprofit': '101513.7812', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '29577.2', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=1


## /root/FIL/strategy/s_rsrs/log.txt ----- -----

723  20230808   120000    155959  1691481599  ...    723  0.010176 -1.364017    -1.0
724  20230808   160000    195959  1691495999  ...    724  0.023725 -1.303872    -1.0

[5 rows x 15 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '54.719', 'enterprice': '28996.8', 'countrevence': '0', 'unrealprofit': '-23813.7088', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '29432', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'numpy.int64'>, curSign=-1, self.sign=-1
127.0.0.1 - - [09/Aug/2023 00:00:01] "POST / HTTP/1.1" 200 -
--handleKline--:  version='2.0.0', self.name='s_rsrs', self.symbol='BTCUSDT', interval='4h', intervalSec=14400, wid=25, thd=0.6, self.sign=-1, self.total=1585089.2233008002, self.flagDict['side']='sell', self.tradeCount=18, self.count=519
self.closeSec=1691510399, self.tradeDate='20230808', self.openTime='200000', self.closeTime='235959', self.symbol='BTCUSDT', self.open=29428.1, self.close=29517.5, self.high=29666.0, self.low=29336.6, self.vol=130655.635, self.amt=3852245217.28055 
2023-08-09 00:00:01,627:INFO:s_rsrs:main.py:141:handleKline:2218689: self.closeSec=1691510399, self.tradeDate='20230808', self.openTime='200000', self.closeTime='235959',self.symbol='BTCUSDT',self.open=29428.1, self.close=29517.5, self.high=29666.0, self.low=29336.6, self.vol=130655.635, self.amt=3852245217.28055 
2023-08-09 00:00:01,640:INFO:s_rsrs:main.py:142:handleKline:2218689: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime  ...         vol           amt       pct
721  20230808   040000    075959  ...   34487.020  1.006610e+09  0.001980
722  20230808   080000    115959  ...   21205.290  6.188332e+08 -0.000678
723  20230808   120000    155959  ...   30110.449  8.803045e+08 -0.000199
724  20230808   160000    195959  ...   46193.521  1.353444e+09  0.008603
725  20230808   200000    235959  ...  130655.635  3.852245e+09  0.003041

[5 rows x 11 columns]
2023-08-09 00:00:02,321:INFO:s_rsrs:main.py:151:handleKline:2218689: df_s.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec  ...  index      beta    zscore  signal
721  20230808   040000    075959  1691452799  ...    721  0.008901 -1.397944    -1.0
722  20230808   080000    115959  1691467199  ...    722  0.004642 -1.402976    -1.0
723  20230808   120000    155959  1691481599  ...    723  0.010176 -1.364017    -1.0
724  20230808   160000    195959  1691495999  ...    724  0.023725 -1.303872    -1.0
725  20230808   200000    235959  1691510399  ...    725  0.146329 -0.768183    -1.0

[5 rows x 15 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '54.719', 'enterprice': '28996.8', 'countrevence': '0', 'unrealprofit': '-28590.49279820426', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '29519.29662454', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'numpy.int64'>, curSign=-1, self.sign=-1


