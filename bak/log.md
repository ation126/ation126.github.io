# 20230609 08:26:01

## /root/FIL/strategy/amihud/log.txt ----- -----

--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=373746.4768026, self.flagDict['side']='sell', self.tradeCount=2, self.count=7456
self.closeSec=1686269999, self.tradeDate='20230609', self.openTime='081500', self.closeTime='081959', self.symbol='BTCUSDT', self.open=26487.6, self.close=26475.0, self.high=26487.7, self.low=26464.4, self.vol=386.283, self.amt=10225904.564 
127.0.0.1 - - [09/Jun/2023 08:20:01] "POST / HTTP/1.1" 200 -
2023-06-09 08:20:03,060:INFO:amihud:main.py:172:handleKline:2219019: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5855  20230609   075500    075959  ...         0.0        0.0       0
5856  20230609   080000    080459  ...         0.0        0.0       0
5857  20230609   080500    080959  ...         0.0        0.0       0
5858  20230609   081000    081459  ...         0.0        0.0       0
5859  20230609   081500    081959  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-06-09 08:20:03,089:INFO:amihud:main.py:175:handleKline:2219019: self.closeSec=1686269999, self.tradeDate='20230609', self.openTime='081500', self.closeTime='081959',self.symbol='BTCUSDT',self.open=26487.6, self.close=26475.0, self.high=26487.7, self.low=26464.4, self.vol=386.283, self.amt=10225904.564, ukdf['pct'].iloc[-1]=-0.000479 , ukdf['amount'].iloc[-1]=10225904.564, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5859, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '13.926', 'enterprice': '26864.9', 'countrevence': '0', 'unrealprofit': '5429.7474', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '26475', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1
--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=373746.4768026, self.flagDict['side']='sell', self.tradeCount=2, self.count=7457
self.closeSec=1686270299, self.tradeDate='20230609', self.openTime='082000', self.closeTime='082459', self.symbol='BTCUSDT', self.open=26475.0, self.close=26440.4, self.high=26481.8, self.low=26409.4, self.vol=1561.741, self.amt=41287992.377 
127.0.0.1 - - [09/Jun/2023 08:25:01] "POST / HTTP/1.1" 200 -
2023-06-09 08:25:04,194:INFO:amihud:main.py:172:handleKline:2219019: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5856  20230609   080000    080459  ...         0.0        0.0       0
5857  20230609   080500    080959  ...         0.0        0.0       0
5858  20230609   081000    081459  ...         0.0        0.0       0
5859  20230609   081500    081959  ...         0.0        0.0       0
5860  20230609   082000    082459  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-06-09 08:25:04,207:INFO:amihud:main.py:175:handleKline:2219019: self.closeSec=1686270299, self.tradeDate='20230609', self.openTime='082000', self.closeTime='082459',self.symbol='BTCUSDT',self.open=26475.0, self.close=26440.4, self.high=26481.8, self.low=26409.4, self.vol=1561.741, self.amt=41287992.377, ukdf['pct'].iloc[-1]=-0.001307 , ukdf['amount'].iloc[-1]=41287992.377, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5860, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '13.926', 'enterprice': '26864.9', 'countrevence': '0', 'unrealprofit': '5910.1944', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '26440.5', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1


## /root/FIL/strategy/factorcheck/log.txt ----- -----


self.closeSec=1686269999, self.tradeDate='20230609', self.openTime='081500', self.closeTime='081959', self.symbol='BTCUSDT', self.open=26487.6, self.close=26475.0, self.high=26487.7, self.low=26464.4 
127.0.0.1 - - [09/Jun/2023 08:20:01] "POST / HTTP/1.1" 200 -
2023-06-09 08:20:01,245:INFO:factorcheck2:main.py:126:handleKline:2218005: self.closeSec=1686269999, self.tradeDate='20230609', self.openTime='081500', self.closeTime='081959',self.symbol='BTCUSDT',self.open=26487.6, self.close=26475.0, self.high=26487.7, self.low=26464.4   
2023-06-09 08:20:02,380:INFO:factorcheck2:main.py:127:handleKline:2218005: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime    closeSec  ...      low       pct  index  idx
1535  20230609   075500    075959  1686268799  ...  26480.9  0.000147   1535    5
1536  20230609   080000    080459  1686269099  ...  26477.5  0.000480   1536    0
1537  20230609   080500    080959  1686269399  ...  26447.1 -0.001540   1537    1
1538  20230609   081000    081459  1686269699  ...  26438.1  0.001130   1538    2
1539  20230609   081500    081959  1686269999  ...  26464.4 -0.000479   1539    3

[5 rows x 11 columns]
2023-06-09 08:20:02,380:INFO:factorcheck2:main.py:128:handleKline:2218005: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': True, 'isOpenSell': False, 'isCloseBuy': False, 'isCloseSell': False, 'isOpen': True, 'isClose': False, 'isTrig': True}

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=29, self.factor=0.4632772386159953, self.count=7459 

self.closeSec=1686270299, self.tradeDate='20230609', self.openTime='082000', self.closeTime='082459', self.symbol='BTCUSDT', self.open=26475.0, self.close=26440.4, self.high=26481.8, self.low=26409.4 
127.0.0.1 - - [09/Jun/2023 08:25:01] "POST / HTTP/1.1" 200 -
2023-06-09 08:25:02,997:INFO:factorcheck2:main.py:126:handleKline:2218005: self.closeSec=1686270299, self.tradeDate='20230609', self.openTime='082000', self.closeTime='082459',self.symbol='BTCUSDT',self.open=26475.0, self.close=26440.4, self.high=26481.8, self.low=26409.4   
2023-06-09 08:25:03,747:INFO:factorcheck2:main.py:127:handleKline:2218005: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime    closeSec  ...      low       pct  index  idx
1536  20230609   080000    080459  1686269099  ...  26477.5  0.000480   1536    0
1537  20230609   080500    080959  1686269399  ...  26447.1 -0.001540   1537    1
1538  20230609   081000    081459  1686269699  ...  26438.1  0.001130   1538    2
1539  20230609   081500    081959  1686269999  ...  26464.4 -0.000479   1539    3
1540  20230609   082000    082459  1686270299  ...  26409.4 -0.001307   1540    4

[5 rows x 11 columns]
2023-06-09 08:25:03,748:INFO:factorcheck2:main.py:128:handleKline:2218005: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': True, 'isOpenSell': False, 'isCloseBuy': False, 'isCloseSell': False, 'isOpen': True, 'isClose': False, 'isTrig': True}


## /root/FIL/strategy/logic/log.txt ----- -----

2023-06-09 08:00:38,619:DEBUG:logic:main.py:463:getModel:2218526: df_s.iloc[-5:,:] :
          date closeTime     open  ...    alpha58   alpha67   alpha72
5770  20230609    052959  26626.0  ...  50.833333  0.515695  0.431168
5771  20230609    055959  26577.2  ...  50.833333  0.512657  0.428854
5772  20230609    062959  26560.3  ...  50.833333  0.514904  0.425250
5773  20230609    065959  26573.5  ...  50.416667  0.507793  0.426187
5774  20230609    072959  26534.4  ...  50.000000  0.506457  0.428694

[5 rows x 33 columns]
0.5101663585951941
acc is : 0.5101663585951941
2023-06-09 08:00:38,884:INFO:logic:main.py:468:getModel:2218526: df_pred.iloc[-5:,:] :
     pred    prob_0    prob_1  actual  ...       nav  sign  cost_        bm
536     1  0.494438  0.505562       0  ...  1.076055   1.0    0.0  0.974304
537     0  0.501085  0.498915       1  ...  1.076586   1.0    0.0  0.974784
538     0  0.507137  0.492863       0  ...  1.075006   1.0    0.0  0.973354
539     1  0.488529  0.511471       0  ...  1.074710   1.0    0.0  0.973086
540     1  0.489706  0.510294       0  ...  1.073041   1.0    0.0  0.971575

[5 rows x 10 columns]
2023-06-09 08:00:38,921:INFO:logic:main.py:478:getModel:2218526: df_panel.iloc[-5:,:] :
    pred    prob_0    prob_1  actual  ...       nav  sign  cost_        bm
45     1  0.494340  0.505660       0  ...  1.076055   1.0    0.0  0.974186
46     0  0.501296  0.498704       1  ...  1.076586   1.0    0.0  0.975378
47     0  0.507277  0.492723       0  ...  1.075006   1.0    0.0  0.973993
48     1  0.488529  0.511471       0  ...  1.074710   1.0    0.0  0.973086
49     1  0.489706  0.510294       0  ...  1.073041   1.0    0.0  0.971575

[5 rows x 10 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '28.647', 'enterprice': '26630.1', 'countrevence': '0', 'unrealprofit': '-4148.46173625588', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '26485.28686996', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}


## /root/FIL/strategy/modifiedmom/log.txt ----- -----

623  20230609   075000    075959  1686268799    26512  26485.9 -0.000981
2023-06-09 08:00:02,428:INFO:modifiedmom:main.py:146:handleKline:2218259: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': True, 'isOpen': False, 'isClose': True, 'isTrig': False}
127.0.0.1 - - [09/Jun/2023 08:10:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=3728 

self.closeSec=1686269399, self.tradeDate='20230609', self.openTime='080000', self.closeTime='080959', self.symbol='BTCUSDT', self.open='26486', self.close='26457.8'
2023-06-09 08:10:01,136:INFO:modifiedmom:main.py:144:handleKline:2218259: self.closeSec=1686269399, self.tradeDate='20230609', self.openTime='080000', self.closeTime='080959',self.symbol='BTCUSDT',self.open='26486', self.close='26457.8'
2023-06-09 08:10:01,185:INFO:modifiedmom:main.py:145:handleKline:2218259: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec     open    close       pct
620  20230609   072000    072959  1686266999  26533.7    26527 -0.000256
621  20230609   073000    073959  1686267599  26527.1  26510.2 -0.000633
622  20230609   074000    074959  1686268199  26510.1  26511.9  0.000064
623  20230609   075000    075959  1686268799    26512  26485.9 -0.000981
624  20230609   080000    080959  1686269399    26486  26457.8 -0.001061
2023-06-09 08:10:01,185:INFO:modifiedmom:main.py:146:handleKline:2218259: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': True, 'isOpen': False, 'isClose': True, 'isTrig': False}

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=3729 

self.closeSec=1686269999, self.tradeDate='20230609', self.openTime='081000', self.closeTime='081959', self.symbol='BTCUSDT', self.open='26457.9', self.close='26475'
127.0.0.1 - - [09/Jun/2023 08:20:03] "POST / HTTP/1.1" 200 -
2023-06-09 08:20:04,669:INFO:modifiedmom:main.py:144:handleKline:2218259: self.closeSec=1686269999, self.tradeDate='20230609', self.openTime='081000', self.closeTime='081959',self.symbol='BTCUSDT',self.open='26457.9', self.close='26475'
2023-06-09 08:20:05,192:INFO:modifiedmom:main.py:145:handleKline:2218259: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec     open    close       pct
621  20230609   073000    073959  1686267599  26527.1  26510.2 -0.000633
622  20230609   074000    074959  1686268199  26510.1  26511.9  0.000064
623  20230609   075000    075959  1686268799    26512  26485.9 -0.000981
624  20230609   080000    080959  1686269399    26486  26457.8 -0.001061
625  20230609   081000    081959  1686269999  26457.9    26475  0.000650
2023-06-09 08:20:05,204:INFO:modifiedmom:main.py:146:handleKline:2218259: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': True, 'isOpen': False, 'isClose': True, 'isTrig': False}


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

17471  20230609   075000    075959  1686268799    26512  26485.9
2023-06-09 08:00:02,436:INFO:pyemd2:main.py:127:handleKline:2217508: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=3731 

self.closeSec=1686269399, self.tradeDate='20230609', self.openTime='080000', self.closeTime='080959', self.symbol='BTCUSDT', self.open='26486', self.close='26457.8'
127.0.0.1 - - [09/Jun/2023 08:10:01] "POST / HTTP/1.1" 200 -
2023-06-09 08:10:01,145:INFO:pyemd2:main.py:125:handleKline:2217508: self.closeSec=1686269399, self.tradeDate='20230609', self.openTime='080000', self.closeTime='080959',self.symbol='BTCUSDT',self.open='26486', self.close='26457.8'
2023-06-09 08:10:01,193:INFO:pyemd2:main.py:126:handleKline:2217508: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
17468  20230609   072000    072959  1686266999  26533.7    26527
17469  20230609   073000    073959  1686267599  26527.1  26510.2
17470  20230609   074000    074959  1686268199  26510.1  26511.9
17471  20230609   075000    075959  1686268799    26512  26485.9
17472  20230609   080000    080959  1686269399    26486  26457.8
2023-06-09 08:10:01,193:INFO:pyemd2:main.py:127:handleKline:2217508: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=3732 

self.closeSec=1686269999, self.tradeDate='20230609', self.openTime='081000', self.closeTime='081959', self.symbol='BTCUSDT', self.open='26457.9', self.close='26475'
127.0.0.1 - - [09/Jun/2023 08:20:03] "POST / HTTP/1.1" 200 -
2023-06-09 08:20:06,017:INFO:pyemd2:main.py:125:handleKline:2217508: self.closeSec=1686269999, self.tradeDate='20230609', self.openTime='081000', self.closeTime='081959',self.symbol='BTCUSDT',self.open='26457.9', self.close='26475'
2023-06-09 08:20:06,119:INFO:pyemd2:main.py:126:handleKline:2217508: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
17469  20230609   073000    073959  1686267599  26527.1  26510.2
17470  20230609   074000    074959  1686268199  26510.1  26511.9
17471  20230609   075000    075959  1686268799    26512  26485.9
17472  20230609   080000    080959  1686269399    26486  26457.8
17473  20230609   081000    081959  1686269999  26457.9    26475
2023-06-09 08:20:06,120:INFO:pyemd2:main.py:127:handleKline:2217508: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}


## /root/FIL/strategy/similarity/log.txt ----- -----

12143  20230609   075000    075959  1686268799    26512  26485.9
2023-06-09 08:00:02,451:INFO:testStrategy:main.py:103:handleKline:2217133: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': True, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True, 'isCorr': False}
127.0.0.1 - - [09/Jun/2023 08:10:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=3731 

self.closeSec=1686269399, self.tradeDate='20230609', self.openTime='080000', self.closeTime='080959', self.symbol='BTCUSDT', self.open='26486', self.close='26457.8'
2023-06-09 08:10:01,127:INFO:testStrategy:main.py:101:handleKline:2217133: self.closeSec=1686269399, self.tradeDate='20230609', self.openTime='080000', self.closeTime='080959',self.symbol='BTCUSDT',self.open='26486', self.close='26457.8'
2023-06-09 08:10:01,185:INFO:testStrategy:main.py:102:handleKline:2217133: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
12140  20230609   072000    072959  1686266999  26533.7    26527
12141  20230609   073000    073959  1686267599  26527.1  26510.2
12142  20230609   074000    074959  1686268199  26510.1  26511.9
12143  20230609   075000    075959  1686268799    26512  26485.9
12144  20230609   080000    080959  1686269399    26486  26457.8
2023-06-09 08:10:01,189:INFO:testStrategy:main.py:103:handleKline:2217133: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': True, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True, 'isCorr': False}

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=3732 

self.closeSec=1686269999, self.tradeDate='20230609', self.openTime='081000', self.closeTime='081959', self.symbol='BTCUSDT', self.open='26457.9', self.close='26475'
127.0.0.1 - - [09/Jun/2023 08:20:03] "POST / HTTP/1.1" 200 -
2023-06-09 08:20:05,692:INFO:testStrategy:main.py:101:handleKline:2217133: self.closeSec=1686269999, self.tradeDate='20230609', self.openTime='081000', self.closeTime='081959',self.symbol='BTCUSDT',self.open='26457.9', self.close='26475'
2023-06-09 08:20:05,996:INFO:testStrategy:main.py:102:handleKline:2217133: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
12141  20230609   073000    073959  1686267599  26527.1  26510.2
12142  20230609   074000    074959  1686268199  26510.1  26511.9
12143  20230609   075000    075959  1686268799    26512  26485.9
12144  20230609   080000    080959  1686269399    26486  26457.8
12145  20230609   081000    081959  1686269999  26457.9    26475
2023-06-09 08:20:05,996:INFO:testStrategy:main.py:103:handleKline:2217133: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': True, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True, 'isCorr': False}


## /root/FIL/strategy/sr_min/log.txt ----- -----

--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=1, self.total=996015.990996, self.flagDict['side']='buy', self.tradeCount=1, self.count=7456
self.closeSec=1686269999, self.tradeDate='20230609', self.openTime='081500', self.closeTime='081959', self.symbol='BTCUSDT', self.open=26487.6, self.close=26475.0, self.high=26487.7, self.low=26464.4, self.vol=386.283, self.amt=10225904.564 
127.0.0.1 - - [09/Jun/2023 08:20:01] "POST / HTTP/1.1" 200 -
2023-06-09 08:20:03,159:INFO:sr_min:main.py:172:handleKline:2219263: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5855  20230609   075500    075959  ...         0.0        0.0       0
5856  20230609   080000    080459  ...         0.0        0.0       0
5857  20230609   080500    080959  ...         0.0        0.0       0
5858  20230609   081000    081459  ...         0.0        0.0       0
5859  20230609   081500    081959  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-06-09 08:20:03,179:INFO:sr_min:main.py:175:handleKline:2219263: self.closeSec=1686269999, self.tradeDate='20230609', self.openTime='081500', self.closeTime='081959',self.symbol='BTCUSDT',self.open=26487.6, self.close=26475.0, self.high=26487.7, self.low=26464.4, self.vol=386.283, self.amt=10225904.564, ukdf['pct'].iloc[-1]=-0.000479 , ukdf['amount'].iloc[-1]=10225904.564, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5859, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '37.141', 'enterprice': '26844', 'countrevence': '0', 'unrealprofit': '-13705.029', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '26475', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=1
--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=1, self.total=996015.990996, self.flagDict['side']='buy', self.tradeCount=1, self.count=7457
self.closeSec=1686270299, self.tradeDate='20230609', self.openTime='082000', self.closeTime='082459', self.symbol='BTCUSDT', self.open=26475.0, self.close=26440.4, self.high=26481.8, self.low=26409.4, self.vol=1561.741, self.amt=41287992.377 
127.0.0.1 - - [09/Jun/2023 08:25:01] "POST / HTTP/1.1" 200 -
2023-06-09 08:25:04,194:INFO:sr_min:main.py:172:handleKline:2219263: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5856  20230609   080000    080459  ...         0.0        0.0       0
5857  20230609   080500    080959  ...         0.0        0.0       0
5858  20230609   081000    081459  ...         0.0        0.0       0
5859  20230609   081500    081959  ...         0.0        0.0       0
5860  20230609   082000    082459  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-06-09 08:25:04,199:INFO:sr_min:main.py:175:handleKline:2219263: self.closeSec=1686270299, self.tradeDate='20230609', self.openTime='082000', self.closeTime='082459',self.symbol='BTCUSDT',self.open=26475.0, self.close=26440.4, self.high=26481.8, self.low=26409.4, self.vol=1561.741, self.amt=41287992.377, ukdf['pct'].iloc[-1]=-0.001307 , ukdf['amount'].iloc[-1]=41287992.377, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5860, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '37.141', 'enterprice': '26844', 'countrevence': '0', 'unrealprofit': '-14986.3935', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '26440.5', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=1


## /root/FIL/strategy/s_rsrs/log.txt ----- -----

719  20230608   200000    235959  1686239999  ...    719  0.535715 -0.238526     NaN
720  20230609   000000    035959  1686254399  ...    720  0.549805 -0.197611     NaN

[5 rows x 15 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '55.166', 'enterprice': '27078.6', 'countrevence': '0', 'unrealprofit': '30337.7437127768', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '26528.6644652', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'numpy.int64'>, curSign=-9223372036854775808, self.sign=-1
--handleKline--:  version='2.0.0', self.name='s_rsrs', self.symbol='BTCUSDT', interval='4h', intervalSec=14400, wid=25, thd=0.6, self.sign=-1, self.total=1492324.2295523998, self.flagDict['side']='sell', self.tradeCount=4, self.count=155
self.closeSec=1686268799, self.tradeDate='20230609', self.openTime='040000', self.closeTime='075959', self.symbol='BTCUSDT', self.open=26526.3, self.close=26485.9, self.high=26645.7, self.low=26472.1, self.vol=27001.036, self.amt=717289757.1943 
2023-06-09 08:00:01,918:INFO:s_rsrs:main.py:141:handleKline:2218689: self.closeSec=1686268799, self.tradeDate='20230609', self.openTime='040000', self.closeTime='075959',self.symbol='BTCUSDT',self.open=26526.3, self.close=26485.9, self.high=26645.7, self.low=26472.1, self.vol=27001.036, self.amt=717289757.1943 
127.0.0.1 - - [09/Jun/2023 08:00:01] "POST / HTTP/1.1" 200 -
2023-06-09 08:00:01,974:INFO:s_rsrs:main.py:142:handleKline:2218689: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime  ...         vol           amt       pct
717  20230608   120000    155959  ...   44715.213  1.180481e+09  0.003779
718  20230608   160000    195959  ...   31664.967  8.364446e+08 -0.000382
719  20230608   200000    235959  ...  127003.344  3.367355e+09  0.010768
720  20230609   000000    035959  ...   56834.492  1.507574e+09 -0.006703
721  20230609   040000    075959  ...   27001.036  7.172898e+08 -0.001546

[5 rows x 11 columns]
2023-06-09 08:00:04,355:INFO:s_rsrs:main.py:151:handleKline:2218689: df_s.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec  ...  index      beta    zscore  signal
717  20230608   120000    155959  1686211199  ...    717  0.517285 -0.282857     NaN
718  20230608   160000    195959  1686225599  ...    718  0.523612 -0.267755     NaN
719  20230608   200000    235959  1686239999  ...    719  0.535715 -0.238526     NaN
720  20230609   000000    035959  1686254399  ...    720  0.549805 -0.197611     NaN
721  20230609   040000    075959  1686268799  ...    721  0.576510 -0.112975     NaN

[5 rows x 15 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '55.166', 'enterprice': '27078.6', 'countrevence': '0', 'unrealprofit': '32598.11792282794', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '26487.69041941', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'numpy.int64'>, curSign=-9223372036854775808, self.sign=-1


