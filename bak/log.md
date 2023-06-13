# 20230614 00:26:01

## /root/FIL/strategy/amihud/log.txt ----- -----

--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=373746.4768026, self.flagDict['side']='sell', self.tradeCount=2, self.count=8800
self.closeSec=1686673199, self.tradeDate='20230614', self.openTime='001500', self.closeTime='001959', self.symbol='BTCUSDT', self.open=25800.0, self.close=25834.4, self.high=25834.4, self.low=25788.1, self.vol=2100.289, self.amt=54218604.7935 
127.0.0.1 - - [14/Jun/2023 00:20:01] "POST / HTTP/1.1" 200 -
2023-06-14 00:20:07,953:INFO:amihud:main.py:172:handleKline:2219019: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5759  20230613   235500    235959  ...         0.0        0.0       0
5760  20230614   000000    000459  ...         0.0        0.0       0
5761  20230614   000500    000959  ...         0.0        0.0       0
5762  20230614   001000    001459  ...         0.0        0.0       0
5763  20230614   001500    001959  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-06-14 00:20:07,984:INFO:amihud:main.py:175:handleKline:2219019: self.closeSec=1686673199, self.tradeDate='20230614', self.openTime='001500', self.closeTime='001959',self.symbol='BTCUSDT',self.open=25800.0, self.close=25834.4, self.high=25834.4, self.low=25788.1, self.vol=2100.289, self.amt=54218604.7935, ukdf['pct'].iloc[-1]=0.00145 , ukdf['amount'].iloc[-1]=54218604.7935, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5763, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '13.926', 'enterprice': '26864.9', 'countrevence': '0', 'unrealprofit': '14476.8838153434', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '25825.3420641', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1
127.0.0.1 - - [14/Jun/2023 00:25:00] "POST / HTTP/1.1" 200 -
--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=373746.4768026, self.flagDict['side']='sell', self.tradeCount=2, self.count=8801
self.closeSec=1686673499, self.tradeDate='20230614', self.openTime='002000', self.closeTime='002459', self.symbol='BTCUSDT', self.open=25834.4, self.close=25798.4, self.high=25834.4, self.low=25793.4, self.vol=1202.141, self.amt=31025716.1301 
2023-06-14 00:25:00,803:INFO:amihud:main.py:172:handleKline:2219019: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5760  20230614   000000    000459  ...         0.0        0.0       0
5761  20230614   000500    000959  ...         0.0        0.0       0
5762  20230614   001000    001459  ...         0.0        0.0       0
5763  20230614   001500    001959  ...         0.0        0.0       0
5764  20230614   002000    002459  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-06-14 00:25:00,804:INFO:amihud:main.py:175:handleKline:2219019: self.closeSec=1686673499, self.tradeDate='20230614', self.openTime='002000', self.closeTime='002459',self.symbol='BTCUSDT',self.open=25834.4, self.close=25798.4, self.high=25834.4, self.low=25793.4, self.vol=1202.141, self.amt=31025716.1301, ukdf['pct'].iloc[-1]=-0.001393 , ukdf['amount'].iloc[-1]=31025716.1301, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5764, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '13.926', 'enterprice': '26864.9', 'countrevence': '0', 'unrealprofit': '14852.079', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '25798.4', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1


## /root/FIL/strategy/factorcheck/log.txt ----- -----


self.closeSec=1686673199, self.tradeDate='20230614', self.openTime='001500', self.closeTime='001959', self.symbol='BTCUSDT', self.open=25800.0, self.close=25834.4, self.high=25834.4, self.low=25788.1 
127.0.0.1 - - [14/Jun/2023 00:20:01] "POST / HTTP/1.1" 200 -
2023-06-14 00:20:05,174:INFO:factorcheck2:main.py:126:handleKline:2218005: self.closeSec=1686673199, self.tradeDate='20230614', self.openTime='001500', self.closeTime='001959',self.symbol='BTCUSDT',self.open=25800.0, self.close=25834.4, self.high=25834.4, self.low=25788.1   
2023-06-14 00:20:06,875:INFO:factorcheck2:main.py:127:handleKline:2218005: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime    closeSec  ...      low       pct  index  idx
1439  20230613   235500    235959  1686671999  ...  25708.0 -0.000737   1727    5
1440  20230614   000000    000459  1686672299  ...  25727.0  0.001662   1440    0
1441  20230614   000500    000959  1686672599  ...  25774.2  0.000167   1441    1
1442  20230614   001000    001459  1686672899  ...  25786.1 -0.000043   1442    2
1443  20230614   001500    001959  1686673199  ...  25788.1  0.001450   1443    3

[5 rows x 11 columns]
2023-06-14 00:20:06,893:INFO:factorcheck2:main.py:128:handleKline:2218005: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}
127.0.0.1 - - [14/Jun/2023 00:25:00] "POST / HTTP/1.1" 200 -

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=58, self.factor=0.35982730109821986, self.count=8803 

self.closeSec=1686673499, self.tradeDate='20230614', self.openTime='002000', self.closeTime='002459', self.symbol='BTCUSDT', self.open=25834.4, self.close=25798.4, self.high=25834.4, self.low=25793.4 
2023-06-14 00:25:00,749:INFO:factorcheck2:main.py:126:handleKline:2218005: self.closeSec=1686673499, self.tradeDate='20230614', self.openTime='002000', self.closeTime='002459',self.symbol='BTCUSDT',self.open=25834.4, self.close=25798.4, self.high=25834.4, self.low=25793.4   
2023-06-14 00:25:00,786:INFO:factorcheck2:main.py:127:handleKline:2218005: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime    closeSec  ...      low       pct  index  idx
1440  20230614   000000    000459  1686672299  ...  25727.0  0.001662   1440    0
1441  20230614   000500    000959  1686672599  ...  25774.2  0.000167   1441    1
1442  20230614   001000    001459  1686672899  ...  25786.1 -0.000043   1442    2
1443  20230614   001500    001959  1686673199  ...  25788.1  0.001450   1443    3
1444  20230614   002000    002459  1686673499  ...  25793.4 -0.001393   1444    4

[5 rows x 11 columns]
2023-06-14 00:25:00,786:INFO:factorcheck2:main.py:128:handleKline:2218005: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}


## /root/FIL/strategy/logic/log.txt ----- -----

2023-06-14 00:00:19,285:DEBUG:logic:main.py:463:getModel:2218526: df_s.iloc[-5:,:] :
          date closeTime     open  ...    alpha58   alpha67   alpha72
5802  20230613    212959  26070.6  ...  49.583333  0.533319  0.272241
5803  20230613    215959  26112.6  ...  49.166667  0.512604  0.293299
5804  20230613    222959  26025.3  ...  48.750000  0.505519  0.316456
5805  20230613    225959  25994.6  ...  48.333333  0.501182  0.339921
5806  20230613    232959  25975.7  ...  48.333333  0.455097  0.382427

[5 rows x 33 columns]
0.5275735294117647
acc is : 0.5275735294117647
2023-06-14 00:00:19,382:INFO:logic:main.py:468:getModel:2218526: df_pred.iloc[-5:,:] :
     pred    prob_0    prob_1  actual  ...       nav  sign  cost_        bm
539     0  0.504214  0.495786       0  ...  1.001174  -1.0    0.0  0.962538
540     1  0.472994  0.527006       0  ...  1.002359  -1.0    0.0  0.961399
541     1  0.476733  0.523267       0  ...  1.003088  -1.0    0.0  0.960700
542     1  0.472616  0.527384       0  ...  1.011530  -1.0    0.0  0.952615
543     1  0.431791  0.568209       0  ...  1.011769  -1.0    0.0  0.952390

[5 rows x 10 columns]
2023-06-14 00:00:19,405:INFO:logic:main.py:478:getModel:2218526: df_panel.iloc[-5:,:] :
    pred    prob_0    prob_1  actual  ...       nav  sign  cost_        bm
45     0  0.504363  0.495637       0  ...  1.001174  -1.0    0.0  0.959112
46     1  0.473084  0.526916       0  ...  1.002359  -1.0    0.0  0.960593
47     1  0.476736  0.523264       0  ...  1.003088  -1.0    0.0  0.959894
48     1  0.472508  0.527492       0  ...  1.011530  -1.0    0.0  0.950503
49     1  0.431791  0.568209       0  ...  1.011769  -1.0    0.0  0.952390

[5 rows x 10 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '27.898', 'enterprice': '25555.4', 'countrevence': '0', 'unrealprofit': '-4954.6848', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '25733', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}


## /root/FIL/strategy/modifiedmom/log.txt ----- -----

127.0.0.1 - - [14/Jun/2023 00:00:04] "POST / HTTP/1.1" 200 -
2023-06-14 00:00:04,423:INFO:modifiedmom:main.py:319:handleOrderFilled:2218259: handleOrderFilled: data=OrderType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'clientorderid': '42383F1686672003833I0L59', 'symbol': 'BTCUSDT', 'gatewayorderid': 1686672004210892, 'quantity': '27.701', 'price': '25751', 'stopprice': '0', 'ordertype': '', 'side': 'BUY', 'status': 'FILLED', 'positionside': 'LONG', 'createtime': 1686672002856, 'updatetime': 1686672004210, 'tradetype': 'usdt', 'selfid': 42383, 'filltrades': [TradeType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'tradeid': 1686672004210, 'clientorderid': '42383F1686672003833I0L59', 'price': '25751', 'quantity': '27.701', 'commission': '713.328451', 'commissionasset': 'USDT', 'tradetime': 1686672004210, 'tradetype': 'usdt', 'gatetype': 'simulator', 'handletime': 1686672004210}], 'gatetype': 'simulator', 'handletime': 0}
127.0.0.1 - - [14/Jun/2023 00:10:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=4400 

self.closeSec=1686672599, self.tradeDate='20230614', self.openTime='000000', self.closeTime='000959', self.symbol='BTCUSDT', self.open='25750.9', self.close='25798'
2023-06-14 00:10:01,107:INFO:modifiedmom:main.py:144:handleKline:2218259: self.closeSec=1686672599, self.tradeDate='20230614', self.openTime='000000', self.closeTime='000959',self.symbol='BTCUSDT',self.open='25750.9', self.close='25798'
2023-06-14 00:10:01,126:INFO:modifiedmom:main.py:145:handleKline:2218259: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec     open    close       pct
572  20230613   232000    232959  1686670199  25855.4  25757.1 -0.004137
573  20230613   233000    233959  1686670799  25756.8  25800.3  0.001677
574  20230613   234000    234959  1686671399  25800.3  25782.1 -0.000705
575  20230613   235000    235959  1686671999    25782    25751 -0.001206
576  20230614   000000    000959  1686672599  25750.9    25798  0.001825
2023-06-14 00:10:01,126:INFO:modifiedmom:main.py:146:handleKline:2218259: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': True, 'isOpen': False, 'isClose': True, 'isTrig': False}

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=4401 

self.closeSec=1686673199, self.tradeDate='20230614', self.openTime='001000', self.closeTime='001959', self.symbol='BTCUSDT', self.open='25798', self.close='25834.4'
127.0.0.1 - - [14/Jun/2023 00:20:04] "POST / HTTP/1.1" 200 -
2023-06-14 00:20:07,673:INFO:modifiedmom:main.py:144:handleKline:2218259: self.closeSec=1686673199, self.tradeDate='20230614', self.openTime='001000', self.closeTime='001959',self.symbol='BTCUSDT',self.open='25798', self.close='25834.4'
2023-06-14 00:20:08,564:INFO:modifiedmom:main.py:145:handleKline:2218259: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec     open    close       pct
573  20230613   233000    233959  1686670799  25756.8  25800.3  0.001677
574  20230613   234000    234959  1686671399  25800.3  25782.1 -0.000705
575  20230613   235000    235959  1686671999    25782    25751 -0.001206
576  20230614   000000    000959  1686672599  25750.9    25798  0.001825
577  20230614   001000    001959  1686673199    25798  25834.4  0.001411
2023-06-14 00:20:08,573:INFO:modifiedmom:main.py:146:handleKline:2218259: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': True, 'isOpen': False, 'isClose': True, 'isTrig': False}


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

2023-06-14 00:00:02,223:INFO:pyemd2:main.py:127:handleKline:2217508: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}
2023-06-14 00:00:02,334:INFO:pyemd2:main.py:190:insertFactor:2217508: curDateTime:6140000, name:pyemd2, symbol:BTCUSDT, tradeDate:20230613, closeTime:235959, close:25751, total:981398.7697911, pct_pre:0.011806558252784205, thd:-0.7030317861885236, side:sell 
127.0.0.1 - - [14/Jun/2023 00:10:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=4403 

self.closeSec=1686672599, self.tradeDate='20230614', self.openTime='000000', self.closeTime='000959', self.symbol='BTCUSDT', self.open='25750.9', self.close='25798'
2023-06-14 00:10:01,103:INFO:pyemd2:main.py:125:handleKline:2217508: self.closeSec=1686672599, self.tradeDate='20230614', self.openTime='000000', self.closeTime='000959',self.symbol='BTCUSDT',self.open='25750.9', self.close='25798'
2023-06-14 00:10:01,117:INFO:pyemd2:main.py:126:handleKline:2217508: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
17420  20230613   232000    232959  1686670199  25855.4  25757.1
17421  20230613   233000    233959  1686670799  25756.8  25800.3
17422  20230613   234000    234959  1686671399  25800.3  25782.1
17423  20230613   235000    235959  1686671999    25782    25751
17424  20230614   000000    000959  1686672599  25750.9    25798
2023-06-14 00:10:01,117:INFO:pyemd2:main.py:127:handleKline:2217508: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=4404 

self.closeSec=1686673199, self.tradeDate='20230614', self.openTime='001000', self.closeTime='001959', self.symbol='BTCUSDT', self.open='25798', self.close='25834.4'
127.0.0.1 - - [14/Jun/2023 00:20:04] "POST / HTTP/1.1" 200 -
2023-06-14 00:20:09,806:INFO:pyemd2:main.py:125:handleKline:2217508: self.closeSec=1686673199, self.tradeDate='20230614', self.openTime='001000', self.closeTime='001959',self.symbol='BTCUSDT',self.open='25798', self.close='25834.4'
2023-06-14 00:20:09,966:INFO:pyemd2:main.py:126:handleKline:2217508: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
17421  20230613   233000    233959  1686670799  25756.8  25800.3
17422  20230613   234000    234959  1686671399  25800.3  25782.1
17423  20230613   235000    235959  1686671999    25782    25751
17424  20230614   000000    000959  1686672599  25750.9    25798
17425  20230614   001000    001959  1686673199    25798  25834.4
2023-06-14 00:20:09,967:INFO:pyemd2:main.py:127:handleKline:2217508: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}


## /root/FIL/strategy/similarity/log.txt ----- -----

127.0.0.1 - - [14/Jun/2023 00:00:04] "POST / HTTP/1.1" 200 -
2023-06-14 00:00:04,650:INFO:testStrategy:main.py:308:handleOrderFilled:2217133: handleOrderFilled: data=OrderType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'clientorderid': '42382F1686672003818I0L2', 'symbol': 'BTCUSDT', 'gatewayorderid': 1686672004228338, 'quantity': '49.775', 'price': '25751', 'stopprice': '0', 'ordertype': '', 'side': 'BUY', 'status': 'FILLED', 'positionside': 'LONG', 'createtime': 1686672002816, 'updatetime': 1686672004228, 'tradetype': 'usdt', 'selfid': 42382, 'filltrades': [TradeType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'tradeid': 1686672004228, 'clientorderid': '42382F1686672003818I0L2', 'price': '25751', 'quantity': '49.775', 'commission': '1281.756025', 'commissionasset': 'USDT', 'tradetime': 1686672004228, 'tradetype': 'usdt', 'gatetype': 'simulator', 'handletime': 1686672004228}], 'gatetype': 'simulator', 'handletime': 0}
127.0.0.1 - - [14/Jun/2023 00:10:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=4403 

self.closeSec=1686672599, self.tradeDate='20230614', self.openTime='000000', self.closeTime='000959', self.symbol='BTCUSDT', self.open='25750.9', self.close='25798'
2023-06-14 00:10:01,094:INFO:testStrategy:main.py:101:handleKline:2217133: self.closeSec=1686672599, self.tradeDate='20230614', self.openTime='000000', self.closeTime='000959',self.symbol='BTCUSDT',self.open='25750.9', self.close='25798'
2023-06-14 00:10:01,120:INFO:testStrategy:main.py:102:handleKline:2217133: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
12236  20230613   232000    232959  1686670199  25855.4  25757.1
12237  20230613   233000    233959  1686670799  25756.8  25800.3
12238  20230613   234000    234959  1686671399  25800.3  25782.1
12239  20230613   235000    235959  1686671999    25782    25751
12240  20230614   000000    000959  1686672599  25750.9    25798
2023-06-14 00:10:01,121:INFO:testStrategy:main.py:103:handleKline:2217133: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': True, 'isOpen': False, 'isClose': True, 'isTrig': False, 'isCorr': False}

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=4404 

self.closeSec=1686673199, self.tradeDate='20230614', self.openTime='001000', self.closeTime='001959', self.symbol='BTCUSDT', self.open='25798', self.close='25834.4'
127.0.0.1 - - [14/Jun/2023 00:20:04] "POST / HTTP/1.1" 200 -
2023-06-14 00:20:09,437:INFO:testStrategy:main.py:101:handleKline:2217133: self.closeSec=1686673199, self.tradeDate='20230614', self.openTime='001000', self.closeTime='001959',self.symbol='BTCUSDT',self.open='25798', self.close='25834.4'
2023-06-14 00:20:09,754:INFO:testStrategy:main.py:102:handleKline:2217133: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
12237  20230613   233000    233959  1686670799  25756.8  25800.3
12238  20230613   234000    234959  1686671399  25800.3  25782.1
12239  20230613   235000    235959  1686671999    25782    25751
12240  20230614   000000    000959  1686672599  25750.9    25798
12241  20230614   001000    001959  1686673199    25798  25834.4
2023-06-14 00:20:09,755:INFO:testStrategy:main.py:103:handleKline:2217133: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': True, 'isOpen': False, 'isClose': True, 'isTrig': False, 'isCorr': False}


## /root/FIL/strategy/sr_min/log.txt ----- -----

--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=1, self.total=996015.990996, self.flagDict['side']='buy', self.tradeCount=1, self.count=8800
self.closeSec=1686673199, self.tradeDate='20230614', self.openTime='001500', self.closeTime='001959', self.symbol='BTCUSDT', self.open=25800.0, self.close=25834.4, self.high=25834.4, self.low=25788.1, self.vol=2100.289, self.amt=54218604.7935 
127.0.0.1 - - [14/Jun/2023 00:20:01] "POST / HTTP/1.1" 200 -
2023-06-14 00:20:07,954:INFO:sr_min:main.py:172:handleKline:2219263: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5759  20230613   235500    235959  ...         0.0        0.0       0
5760  20230614   000000    000459  ...         0.0        0.0       0
5761  20230614   000500    000959  ...         0.0        0.0       0
5762  20230614   001000    001459  ...         0.0        0.0       0
5763  20230614   001500    001959  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-06-14 00:20:07,983:INFO:sr_min:main.py:175:handleKline:2219263: self.closeSec=1686673199, self.tradeDate='20230614', self.openTime='001500', self.closeTime='001959',self.symbol='BTCUSDT',self.open=25800.0, self.close=25834.4, self.high=25834.4, self.low=25788.1, self.vol=2100.289, self.amt=54218604.7935, ukdf['pct'].iloc[-1]=0.00145 , ukdf['amount'].iloc[-1]=54218604.7935, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5763, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '37.141', 'enterprice': '26844', 'countrevence': '0', 'unrealprofit': '-37747.70932270273', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '25827.66470147', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=1
127.0.0.1 - - [14/Jun/2023 00:25:00] "POST / HTTP/1.1" 200 -
--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=1, self.total=996015.990996, self.flagDict['side']='buy', self.tradeCount=1, self.count=8801
self.closeSec=1686673499, self.tradeDate='20230614', self.openTime='002000', self.closeTime='002459', self.symbol='BTCUSDT', self.open=25834.4, self.close=25798.4, self.high=25834.4, self.low=25793.4, self.vol=1202.141, self.amt=31025716.1301 
2023-06-14 00:25:00,804:INFO:sr_min:main.py:172:handleKline:2219263: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5760  20230614   000000    000459  ...         0.0        0.0       0
5761  20230614   000500    000959  ...         0.0        0.0       0
5762  20230614   001000    001459  ...         0.0        0.0       0
5763  20230614   001500    001959  ...         0.0        0.0       0
5764  20230614   002000    002459  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-06-14 00:25:00,804:INFO:sr_min:main.py:175:handleKline:2219263: self.closeSec=1686673499, self.tradeDate='20230614', self.openTime='002000', self.closeTime='002459',self.symbol='BTCUSDT',self.open=25834.4, self.close=25798.4, self.high=25834.4, self.low=25793.4, self.vol=1202.141, self.amt=31025716.1301, ukdf['pct'].iloc[-1]=-0.001393 , ukdf['amount'].iloc[-1]=31025716.1301, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5764, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '37.141', 'enterprice': '26844', 'countrevence': '0', 'unrealprofit': '-38834.6296', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '25798.4', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=1


## /root/FIL/strategy/s_rsrs/log.txt ----- -----

723  20230613   120000    155959  1686643199  ...    723  0.362114 -0.726321    -1.0
724  20230613   160000    195959  1686657599  ...    724  0.341905 -0.779007    -1.0

[5 rows x 15 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '55.166', 'enterprice': '27078.6', 'countrevence': '0', 'unrealprofit': '49613.9430133884', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '26179.2427326', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'numpy.int64'>, curSign=-1, self.sign=-1
127.0.0.1 - - [14/Jun/2023 00:00:01] "POST / HTTP/1.1" 200 -
--handleKline--:  version='2.0.0', self.name='s_rsrs', self.symbol='BTCUSDT', interval='4h', intervalSec=14400, wid=25, thd=0.6, self.sign=-1, self.total=1492324.2295523998, self.flagDict['side']='sell', self.tradeCount=4, self.count=183
self.closeSec=1686671999, self.tradeDate='20230613', self.openTime='200000', self.closeTime='235959', self.symbol='BTCUSDT', self.open=26178.1, self.close=25751.0, self.high=26430.5, self.low=25708.0, self.vol=185012.495, self.amt=4820442070.05443 
2023-06-14 00:00:01,788:INFO:s_rsrs:main.py:141:handleKline:2218689: self.closeSec=1686671999, self.tradeDate='20230613', self.openTime='200000', self.closeTime='235959',self.symbol='BTCUSDT',self.open=26178.1, self.close=25751.0, self.high=26430.5, self.low=25708.0, self.vol=185012.495, self.amt=4820442070.05443 
2023-06-14 00:00:01,823:INFO:s_rsrs:main.py:142:handleKline:2218689: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime  ...         vol           amt       pct
721  20230613   040000    075959  ...   25186.398  6.521044e+08  0.003017
722  20230613   080000    115959  ...   70391.032  1.830381e+09  0.006175
723  20230613   120000    155959  ...   34095.200  8.883871e+08  0.000215
724  20230613   160000    195959  ...   67198.597  1.757390e+09  0.004524
725  20230613   200000    235959  ...  185012.495  4.820442e+09 -0.016315

[5 rows x 11 columns]
2023-06-14 00:00:03,219:INFO:s_rsrs:main.py:151:handleKline:2218689: df_s.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec  ...  index      beta    zscore  signal
721  20230613   040000    075959  1686614399  ...    721  0.422349 -0.556833     NaN
722  20230613   080000    115959  1686628799  ...    722  0.400757 -0.611843    -1.0
723  20230613   120000    155959  1686643199  ...    723  0.362114 -0.726321    -1.0
724  20230613   160000    195959  1686657599  ...    724  0.341905 -0.779007    -1.0
725  20230613   200000    235959  1686671999  ...    725  0.245567 -1.098139    -1.0

[5 rows x 15 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '55.166', 'enterprice': '27078.6', 'countrevence': '0', 'unrealprofit': '73243.8982', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '25750.9', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'numpy.int64'>, curSign=-1, self.sign=-1


