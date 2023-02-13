# 20230213 08:36:02

## /root/FIL/strategy/amihud/log.txt ----- -----

--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=993672.4896432, self.flagDict['side']='sell', self.tradeCount=2, self.count=22398
self.closeSec=1676248199, self.tradeDate='20230213', self.openTime='082500', self.closeTime='082959', self.symbol='BTCUSDT', self.open=21721.7, self.close=21726.2, self.high=21734.0, self.low=21718.2, self.vol=635.684, self.amt=13810788.7075 
127.0.0.1 - - [13/Feb/2023 08:30:00] "POST / HTTP/1.1" 200 -
2023-02-13 08:30:00,698:INFO:amihud:main.py:172:handleKline:200676: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5857  20230213   080500    080959  ...         0.0        0.0       0
5858  20230213   081000    081459  ...         0.0        0.0       0
5859  20230213   081500    081959  ...         0.0        0.0       0
5860  20230213   082000    082459  ...         0.0        0.0       0
5861  20230213   082500    082959  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-02-13 08:30:00,701:INFO:amihud:main.py:175:handleKline:200676: self.closeSec=1676248199, self.tradeDate='20230213', self.openTime='082500', self.closeTime='082959',self.symbol='BTCUSDT',self.open=21721.7, self.close=21726.2, self.high=21734.0, self.low=21718.2, self.vol=635.684, self.amt=13810788.7075, ukdf['pct'].iloc[-1]=0.000212 , ukdf['amount'].iloc[-1]=13810788.7075, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5861, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '60.176', 'enterprice': '16529.3', 'countrevence': '0', 'unrealprofit': '-312797.9212906192', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '21727.3510717', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1
127.0.0.1 - - [13/Feb/2023 08:35:00] "POST / HTTP/1.1" 200 -
--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=993672.4896432, self.flagDict['side']='sell', self.tradeCount=2, self.count=22399
self.closeSec=1676248499, self.tradeDate='20230213', self.openTime='083000', self.closeTime='083459', self.symbol='BTCUSDT', self.open=21726.3, self.close=21728.5, self.high=21755.9, self.low=21719.4, self.vol=980.826, self.amt=21320764.6552 
2023-02-13 08:35:00,549:INFO:amihud:main.py:172:handleKline:200676: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5858  20230213   081000    081459  ...         0.0        0.0       0
5859  20230213   081500    081959  ...         0.0        0.0       0
5860  20230213   082000    082459  ...         0.0        0.0       0
5861  20230213   082500    082959  ...         0.0        0.0       0
5862  20230213   083000    083459  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-02-13 08:35:00,551:INFO:amihud:main.py:175:handleKline:200676: self.closeSec=1676248499, self.tradeDate='20230213', self.openTime='083000', self.closeTime='083459',self.symbol='BTCUSDT',self.open=21726.3, self.close=21728.5, self.high=21755.9, self.low=21719.4, self.vol=980.826, self.amt=21320764.6552, ukdf['pct'].iloc[-1]=0.000106 , ukdf['amount'].iloc[-1]=21320764.6552, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5862, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '60.176', 'enterprice': '16529.3', 'countrevence': '0', 'unrealprofit': '-312867.0592', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '21728.5', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1


## /root/FIL/strategy/factorcheck/log.txt ----- -----

1540  20230213   082000    082459  1676247899  ...  21718.0 -0.000258   1540    4
1541  20230213   082500    082959  1676248199  ...  21718.2  0.000212   1541    5

[5 rows x 11 columns]
2023-02-13 08:30:00,618:INFO:factorcheck2:main.py:128:handleKline:185239: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}
2023-02-13 08:30:00,723:INFO:factorcheck2:main.py:145:handleKline:185239: df_panel.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec  ...       pct  index  idx    factor
213  20230213   062500    062959  1676240999  ...  0.002402   1517    5  0.366975
214  20230213   065500    065959  1676242799  ... -0.000986   1523    5  0.377397
215  20230213   072500    072959  1676244599  ... -0.001140   1529    5  0.390976
216  20230213   075500    075959  1676246399  ...  0.001343   1535    5  0.401582
217  20230213   082500    082959  1676248199  ...  0.000212   1541    5  0.415577

[5 rows x 12 columns]
127.0.0.1 - - [13/Feb/2023 08:35:00] "POST / HTTP/1.1" 200 -

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=17, self.factor=0.41557677586893654, self.count=22965 

self.closeSec=1676248499, self.tradeDate='20230213', self.openTime='083000', self.closeTime='083459', self.symbol='BTCUSDT', self.open=21726.3, self.close=21728.5, self.high=21755.9, self.low=21719.4 
2023-02-13 08:35:00,435:INFO:factorcheck2:main.py:126:handleKline:185239: self.closeSec=1676248499, self.tradeDate='20230213', self.openTime='083000', self.closeTime='083459',self.symbol='BTCUSDT',self.open=21726.3, self.close=21728.5, self.high=21755.9, self.low=21719.4   
2023-02-13 08:35:00,508:INFO:factorcheck2:main.py:127:handleKline:185239: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime    closeSec  ...      low       pct  index  idx
1538  20230213   081000    081459  1676247299  ...  21738.5 -0.001767   1538    2
1539  20230213   081500    081959  1676247599  ...  21720.1 -0.000966   1539    3
1540  20230213   082000    082459  1676247899  ...  21718.0 -0.000258   1540    4
1541  20230213   082500    082959  1676248199  ...  21718.2  0.000212   1541    5
1542  20230213   083000    083459  1676248499  ...  21719.4  0.000106   1542    0

[5 rows x 11 columns]
2023-02-13 08:35:00,508:INFO:factorcheck2:main.py:128:handleKline:185239: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}


## /root/FIL/strategy/logic/log.txt ----- -----

2023-02-13 08:30:31,984:DEBUG:logic:main.py:463:getModel:885513: df_s.iloc[-5:,:] :
          date closeTime     open  ...    alpha58   alpha67   alpha72
5771  20230213    055959  21888.1  ...  44.583333  0.454369  0.367636
5772  20230213    062959  21728.0  ...  45.000000  0.473980  0.386131
5773  20230213    065959  21782.3  ...  44.583333  0.473980  0.403393
5774  20230213    072959  21782.2  ...  44.166667  0.460276  0.425726
5775  20230213    075959  21739.2  ...  44.583333  0.472277  0.441775

[5 rows x 33 columns]
0.5194085027726433
acc is : 0.5194085027726433
2023-02-13 08:30:32,139:INFO:logic:main.py:468:getModel:885513: df_pred.iloc[-5:,:] :
     pred    prob_0    prob_1  actual  ...       nav  sign  cost_        bm
536     1  0.442427  0.557573       1  ...  1.007387  -1.0    0.0  0.947501
537     1  0.487024  0.512976       0  ...  1.007387  -1.0    0.0  0.947501
538     1  0.475962  0.524038       0  ...  1.009385  -1.0    0.0  0.945622
539     1  0.465890  0.534110       1  ...  1.007839  -1.0    0.0  0.947071
540     1  0.489868  0.510132       0  ...  1.009978  -1.0    0.0  0.945061

[5 rows x 10 columns]
2023-02-13 08:30:32,165:INFO:logic:main.py:478:getModel:885513: df_panel.iloc[-5:,:] :
    pred    prob_0    prob_1  actual  ...       nav  sign  cost_        bm
45     1  0.442033  0.557967       1  ...  1.007387  -1.0    0.0  0.946476
46     1  0.487133  0.512867       0  ...  1.007387  -1.0    0.0  0.947024
47     1  0.475477  0.524523       0  ...  1.009385  -1.0    0.0  0.944895
48     1  0.465413  0.534587       1  ...  1.007839  -1.0    0.0  0.946342
49     1  0.489868  0.510132       0  ...  1.009978  -1.0    0.0  0.945061

[5 rows x 10 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '32.252', 'enterprice': '22924.6', 'countrevence': '0', 'unrealprofit': '38579.8424', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '21728.4', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}


## /root/FIL/strategy/modifiedmom/log.txt ----- -----

624  20230213   080000    080959  1676246999    21771  21786.7  0.000717
2023-02-13 08:10:01,599:INFO:modifiedmom:main.py:146:handleKline:185213: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': True, 'isOpen': False, 'isClose': True, 'isTrig': False}

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=11481 

self.closeSec=1676247599, self.tradeDate='20230213', self.openTime='081000', self.closeTime='081959', self.symbol='BTCUSDT', self.open='21786.7', self.close='21727.2'
2023-02-13 08:20:00,563:INFO:modifiedmom:main.py:144:handleKline:185213: self.closeSec=1676247599, self.tradeDate='20230213', self.openTime='081000', self.closeTime='081959',self.symbol='BTCUSDT',self.open='21786.7', self.close='21727.2'
127.0.0.1 - - [13/Feb/2023 08:20:00] "POST / HTTP/1.1" 200 -
2023-02-13 08:20:00,603:INFO:modifiedmom:main.py:145:handleKline:185213: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec     open    close       pct
621  20230213   073000    073959  1676245199  21739.2  21760.3  0.000975
622  20230213   074000    074959  1676245799  21760.4  21746.2 -0.000648
623  20230213   075000    075959  1676246399  21746.2  21771.1  0.001145
624  20230213   080000    080959  1676246999    21771  21786.7  0.000717
625  20230213   081000    081959  1676247599  21786.7  21727.2 -0.002731
2023-02-13 08:20:00,603:INFO:modifiedmom:main.py:146:handleKline:185213: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': True, 'isOpen': False, 'isClose': True, 'isTrig': False}

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=11482 

self.closeSec=1676248199, self.tradeDate='20230213', self.openTime='082000', self.closeTime='082959', self.symbol='BTCUSDT', self.open='21727.2', self.close='21726.2'
2023-02-13 08:30:00,923:INFO:modifiedmom:main.py:144:handleKline:185213: self.closeSec=1676248199, self.tradeDate='20230213', self.openTime='082000', self.closeTime='082959',self.symbol='BTCUSDT',self.open='21727.2', self.close='21726.2'
127.0.0.1 - - [13/Feb/2023 08:30:00] "POST / HTTP/1.1" 200 -
2023-02-13 08:30:00,933:INFO:modifiedmom:main.py:145:handleKline:185213: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec     open    close       pct
622  20230213   074000    074959  1676245799  21760.4  21746.2 -0.000648
623  20230213   075000    075959  1676246399  21746.2  21771.1  0.001145
624  20230213   080000    080959  1676246999    21771  21786.7  0.000717
625  20230213   081000    081959  1676247599  21786.7  21727.2 -0.002731
626  20230213   082000    082959  1676248199  21727.2  21726.2 -0.000046
2023-02-13 08:30:00,954:INFO:modifiedmom:main.py:146:handleKline:185213: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': True, 'isOpen': False, 'isClose': True, 'isTrig': False}


## /root/FIL/strategy/percentile_regression_step2/log.txt ----- -----

    return _evaluate(op, op_str, a, b)  # type: ignore[misc]
  File "/usr/local/lib/python3.8/dist-packages/pandas/core/computation/expressions.py", line 69, in _evaluate_standard
    return op(a, b)
TypeError: unsupported operand type(s) for /: 'str' and 'float'

During handling of the above exception, another exception occurred:

Traceback (most recent call last):
  File "/root/FIL/strategy/percentile_regression_step2/FIL_lib/client.py", line 95, in __start_handle
    handle_call(handle_data)
  File "main.py", line 186, in handleKline
    factor = self.get_signal(data)
  File "main.py", line 138, in get_signal
    df_id['pct'] = df_id['close'] / df_id['close'].shift(1) - 1
  File "/usr/local/lib/python3.8/dist-packages/pandas/core/ops/common.py", line 70, in new_method
    return method(self, other)
  File "/usr/local/lib/python3.8/dist-packages/pandas/core/arraylike.py", line 124, in __truediv__
    return self._arith_method(other, operator.truediv)
  File "/usr/local/lib/python3.8/dist-packages/pandas/core/series.py", line 5639, in _arith_method
    return base.IndexOpsMixin._arith_method(self, other, op)
  File "/usr/local/lib/python3.8/dist-packages/pandas/core/base.py", line 1295, in _arith_method
    result = ops.arithmetic_op(lvalues, rvalues, op)
  File "/usr/local/lib/python3.8/dist-packages/pandas/core/ops/array_ops.py", line 222, in arithmetic_op
    res_values = _na_arithmetic_op(left, right, op)
  File "/usr/local/lib/python3.8/dist-packages/pandas/core/ops/array_ops.py", line 170, in _na_arithmetic_op
    result = _masked_arith_op(left, right, op)
  File "/usr/local/lib/python3.8/dist-packages/pandas/core/ops/array_ops.py", line 108, in _masked_arith_op
    result[mask] = op(xrav[mask], yrav[mask])
TypeError: unsupported operand type(s) for /: 'str' and 'float'
127.0.0.1 - - [11/Feb/2023 22:30:00] "POST / HTTP/1.1" 200 -


## /root/FIL/strategy/pyemd/log.txt ----- -----

17472  20230213   080000    080959  1676246999    21771  21786.7
2023-02-13 08:10:01,577:INFO:pyemd2:main.py:127:handleKline:185189: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=11482 

self.closeSec=1676247599, self.tradeDate='20230213', self.openTime='081000', self.closeTime='081959', self.symbol='BTCUSDT', self.open='21786.7', self.close='21727.2'
127.0.0.1 - - [13/Feb/2023 08:20:00] "POST / HTTP/1.1" 200 -
2023-02-13 08:20:00,545:INFO:pyemd2:main.py:125:handleKline:185189: self.closeSec=1676247599, self.tradeDate='20230213', self.openTime='081000', self.closeTime='081959',self.symbol='BTCUSDT',self.open='21786.7', self.close='21727.2'
2023-02-13 08:20:00,558:INFO:pyemd2:main.py:126:handleKline:185189: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
17469  20230213   073000    073959  1676245199  21739.2  21760.3
17470  20230213   074000    074959  1676245799  21760.4  21746.2
17471  20230213   075000    075959  1676246399  21746.2  21771.1
17472  20230213   080000    080959  1676246999    21771  21786.7
17473  20230213   081000    081959  1676247599  21786.7  21727.2
2023-02-13 08:20:00,558:INFO:pyemd2:main.py:127:handleKline:185189: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=11483 

self.closeSec=1676248199, self.tradeDate='20230213', self.openTime='082000', self.closeTime='082959', self.symbol='BTCUSDT', self.open='21727.2', self.close='21726.2'
127.0.0.1 - - [13/Feb/2023 08:30:00] "POST / HTTP/1.1" 200 -
2023-02-13 08:30:00,927:INFO:pyemd2:main.py:125:handleKline:185189: self.closeSec=1676248199, self.tradeDate='20230213', self.openTime='082000', self.closeTime='082959',self.symbol='BTCUSDT',self.open='21727.2', self.close='21726.2'
2023-02-13 08:30:00,988:INFO:pyemd2:main.py:126:handleKline:185189: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
17470  20230213   074000    074959  1676245799  21760.4  21746.2
17471  20230213   075000    075959  1676246399  21746.2  21771.1
17472  20230213   080000    080959  1676246999    21771  21786.7
17473  20230213   081000    081959  1676247599  21786.7  21727.2
17474  20230213   082000    082959  1676248199  21727.2  21726.2
2023-02-13 08:30:00,988:INFO:pyemd2:main.py:127:handleKline:185189: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}


## /root/FIL/strategy/similarity/log.txt ----- -----

12144  20230213   080000    080959  1676246999    21771  21786.7
2023-02-13 08:10:01,602:INFO:testStrategy:main.py:103:handleKline:185174: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': True, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True, 'isCorr': False}
127.0.0.1 - - [13/Feb/2023 08:20:00] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=11482 

self.closeSec=1676247599, self.tradeDate='20230213', self.openTime='081000', self.closeTime='081959', self.symbol='BTCUSDT', self.open='21786.7', self.close='21727.2'
2023-02-13 08:20:00,518:INFO:testStrategy:main.py:101:handleKline:185174: self.closeSec=1676247599, self.tradeDate='20230213', self.openTime='081000', self.closeTime='081959',self.symbol='BTCUSDT',self.open='21786.7', self.close='21727.2'
2023-02-13 08:20:00,611:INFO:testStrategy:main.py:102:handleKline:185174: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
12141  20230213   073000    073959  1676245199  21739.2  21760.3
12142  20230213   074000    074959  1676245799  21760.4  21746.2
12143  20230213   075000    075959  1676246399  21746.2  21771.1
12144  20230213   080000    080959  1676246999    21771  21786.7
12145  20230213   081000    081959  1676247599  21786.7  21727.2
2023-02-13 08:20:00,611:INFO:testStrategy:main.py:103:handleKline:185174: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': True, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True, 'isCorr': False}

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=11483 

self.closeSec=1676248199, self.tradeDate='20230213', self.openTime='082000', self.closeTime='082959', self.symbol='BTCUSDT', self.open='21727.2', self.close='21726.2'
127.0.0.1 - - [13/Feb/2023 08:30:00] "POST / HTTP/1.1" 200 -
2023-02-13 08:30:00,939:INFO:testStrategy:main.py:101:handleKline:185174: self.closeSec=1676248199, self.tradeDate='20230213', self.openTime='082000', self.closeTime='082959',self.symbol='BTCUSDT',self.open='21727.2', self.close='21726.2'
2023-02-13 08:30:00,952:INFO:testStrategy:main.py:102:handleKline:185174: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
12142  20230213   074000    074959  1676245799  21760.4  21746.2
12143  20230213   075000    075959  1676246399  21746.2  21771.1
12144  20230213   080000    080959  1676246999    21771  21786.7
12145  20230213   081000    081959  1676247599  21786.7  21727.2
12146  20230213   082000    082959  1676248199  21727.2  21726.2
2023-02-13 08:30:00,952:INFO:testStrategy:main.py:103:handleKline:185174: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': True, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True, 'isCorr': False}


## /root/FIL/strategy/sr_min/log.txt ----- -----

--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=0, self.total=1000000.0, self.flagDict['side']='', self.tradeCount=0, self.count=18396
self.closeSec=1676248199, self.tradeDate='20230213', self.openTime='082500', self.closeTime='082959', self.symbol='BTCUSDT', self.open=21721.7, self.close=21726.2, self.high=21734.0, self.low=21718.2, self.vol=635.684, self.amt=13810788.7075 
127.0.0.1 - - [13/Feb/2023 08:30:00] "POST / HTTP/1.1" 200 -
2023-02-13 08:30:00,694:INFO:sr_min:main.py:172:handleKline:449472: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5857  20230213   080500    080959  ...         0.0        0.0       0
5858  20230213   081000    081459  ...         0.0        0.0       0
5859  20230213   081500    081959  ...         0.0        0.0       0
5860  20230213   082000    082459  ...         0.0        0.0       0
5861  20230213   082500    082959  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-02-13 08:30:00,695:INFO:sr_min:main.py:175:handleKline:449472: self.closeSec=1676248199, self.tradeDate='20230213', self.openTime='082500', self.closeTime='082959',self.symbol='BTCUSDT',self.open=21721.7, self.close=21726.2, self.high=21734.0, self.low=21718.2, self.vol=635.684, self.amt=13810788.7075, ukdf['pct'].iloc[-1]=0.000212 , ukdf['amount'].iloc[-1]=13810788.7075, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5861, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': []}
type(curSign)=<class 'int'>, curSign=0, self.sign=0
--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=0, self.total=1000000.0, self.flagDict['side']='', self.tradeCount=0, self.count=18397
self.closeSec=1676248499, self.tradeDate='20230213', self.openTime='083000', self.closeTime='083459', self.symbol='BTCUSDT', self.open=21726.3, self.close=21728.5, self.high=21755.9, self.low=21719.4, self.vol=980.826, self.amt=21320764.6552 
127.0.0.1 - - [13/Feb/2023 08:35:00] "POST / HTTP/1.1" 200 -
2023-02-13 08:35:00,539:INFO:sr_min:main.py:172:handleKline:449472: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5858  20230213   081000    081459  ...         0.0        0.0       0
5859  20230213   081500    081959  ...         0.0        0.0       0
5860  20230213   082000    082459  ...         0.0        0.0       0
5861  20230213   082500    082959  ...         0.0        0.0       0
5862  20230213   083000    083459  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-02-13 08:35:00,541:INFO:sr_min:main.py:175:handleKline:449472: self.closeSec=1676248499, self.tradeDate='20230213', self.openTime='083000', self.closeTime='083459',self.symbol='BTCUSDT',self.open=21726.3, self.close=21728.5, self.high=21755.9, self.low=21719.4, self.vol=980.826, self.amt=21320764.6552, ukdf['pct'].iloc[-1]=0.000106 , ukdf['amount'].iloc[-1]=21320764.6552, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5862, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': []}
type(curSign)=<class 'int'>, curSign=0, self.sign=0


## /root/FIL/strategy/s_rsrs/log.txt ----- -----

719  20230212   200000    235959  1676217599  ...    719  1.041296  2.195449     1.0
720  20230213   000000    035959  1676231999  ...    720  1.011027  2.006100     1.0

[5 rows x 15 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '42.94', 'enterprice': '21730.2', 'countrevence': '0', 'unrealprofit': '10870.8517324504', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '21983.36375716', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'numpy.int64'>, curSign=1, self.sign=1
--handleKline--:  version='2.0.0', self.name='s_rsrs', self.symbol='BTCUSDT', interval='4h', intervalSec=14400, wid=25, thd=0.6, self.sign=1, self.total=932161.693212, self.flagDict['side']='buy', self.tradeCount=18, self.count=478
self.closeSec=1676246399, self.tradeDate='20230213', self.openTime='040000', self.closeTime='075959', self.symbol='BTCUSDT', self.open=21983.1, self.close=21771.1, self.high=22018.5, self.low=21618.0, self.vol=76306.684, self.amt=1662002474.35437 
127.0.0.1 - - [13/Feb/2023 08:00:00] "POST / HTTP/1.1" 200 -
2023-02-13 08:00:00,915:INFO:s_rsrs:main.py:141:handleKline:185271: self.closeSec=1676246399, self.tradeDate='20230213', self.openTime='040000', self.closeTime='075959',self.symbol='BTCUSDT',self.open=21983.1, self.close=21771.1, self.high=22018.5, self.low=21618.0, self.vol=76306.684, self.amt=1662002474.35437 
2023-02-13 08:00:00,965:INFO:s_rsrs:main.py:142:handleKline:185271: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime  ...        vol           amt       pct
717  20230212   120000    155959  ...  13806.384  3.007564e+08  0.000739
718  20230212   160000    195959  ...  38816.768  8.486016e+08  0.004103
719  20230212   200000    235959  ...  66423.188  1.452623e+09  0.002455
720  20230213   000000    035959  ...  57543.929  1.265239e+09  0.002362
721  20230213   040000    075959  ...  76306.684  1.662002e+09 -0.009644

[5 rows x 11 columns]
2023-02-13 08:00:03,139:INFO:s_rsrs:main.py:151:handleKline:185271: df_s.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec  ...  index      beta    zscore  signal
717  20230212   120000    155959  1676188799  ...    717  0.916684  1.695624     1.0
718  20230212   160000    195959  1676203199  ...    718  0.964438  1.883472     1.0
719  20230212   200000    235959  1676217599  ...    719  1.041296  2.195449     1.0
720  20230213   000000    035959  1676231999  ...    720  1.011027  2.006100     1.0
721  20230213   040000    075959  1676246399  ...    721  0.937283  1.627230     1.0

[5 rows x 15 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '42.94', 'enterprice': '21730.2', 'countrevence': '0', 'unrealprofit': '1872.3810533776', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '21773.80458904', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'numpy.int64'>, curSign=1, self.sign=1


