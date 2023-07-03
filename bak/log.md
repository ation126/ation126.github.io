# 20230703 08:26:01

## /root/FIL/strategy/amihud/log.txt ----- -----

--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=373746.4768026, self.flagDict['side']='sell', self.tradeCount=2, self.count=14368
self.closeSec=1688343599, self.tradeDate='20230703', self.openTime='081500', self.closeTime='081959', self.symbol='BTCUSDT', self.open=30647.1, self.close=30674.9, self.high=30683.9, self.low=30647.1, self.vol=1145.822, self.amt=35137132.0011 
127.0.0.1 - - [03/Jul/2023 08:20:01] "POST / HTTP/1.1" 200 -
2023-07-03 08:20:07,755:INFO:amihud:main.py:172:handleKline:2219019: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5855  20230703   075500    075959  ...         0.0        0.0       0
5856  20230703   080000    080459  ...         0.0        0.0       0
5857  20230703   080500    080959  ...         0.0        0.0       0
5858  20230703   081000    081459  ...         0.0        0.0       0
5859  20230703   081500    081959  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-07-03 08:20:07,785:INFO:amihud:main.py:175:handleKline:2219019: self.closeSec=1688343599, self.tradeDate='20230703', self.openTime='081500', self.closeTime='081959',self.symbol='BTCUSDT',self.open=30647.1, self.close=30674.9, self.high=30683.9, self.low=30647.1, self.vol=1145.822, self.amt=35137132.0011, ukdf['pct'].iloc[-1]=0.000904 , ukdf['amount'].iloc[-1]=35137132.0011, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5859, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '13.926', 'enterprice': '26864.9', 'countrevence': '0', 'unrealprofit': '-53066.10589662228', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '30675.47776078', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1
127.0.0.1 - - [03/Jul/2023 08:25:00] "POST / HTTP/1.1" 200 -
--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=373746.4768026, self.flagDict['side']='sell', self.tradeCount=2, self.count=14369
self.closeSec=1688343899, self.tradeDate='20230703', self.openTime='082000', self.closeTime='082459', self.symbol='BTCUSDT', self.open=30674.9, self.close=30655.8, self.high=30675.0, self.low=30602.6, self.vol=1072.918, self.amt=32873341.8397 
2023-07-03 08:25:00,844:INFO:amihud:main.py:172:handleKline:2219019: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5856  20230703   080000    080459  ...         0.0        0.0       0
5857  20230703   080500    080959  ...         0.0        0.0       0
5858  20230703   081000    081459  ...         0.0        0.0       0
5859  20230703   081500    081959  ...         0.0        0.0       0
5860  20230703   082000    082459  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-07-03 08:25:00,844:INFO:amihud:main.py:175:handleKline:2219019: self.closeSec=1688343899, self.tradeDate='20230703', self.openTime='082000', self.closeTime='082459',self.symbol='BTCUSDT',self.open=30674.9, self.close=30655.8, self.high=30675.0, self.low=30602.6, self.vol=1072.918, self.amt=32873341.8397, ukdf['pct'].iloc[-1]=-0.000623 , ukdf['amount'].iloc[-1]=32873341.8397, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5860, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '13.926', 'enterprice': '26864.9', 'countrevence': '0', 'unrealprofit': '-52792.0734', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '30655.8', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1


## /root/FIL/strategy/factorcheck/log.txt ----- -----


self.closeSec=1688343599, self.tradeDate='20230703', self.openTime='081500', self.closeTime='081959', self.symbol='BTCUSDT', self.open=30647.1, self.close=30674.9, self.high=30683.9, self.low=30647.1 
127.0.0.1 - - [03/Jul/2023 08:20:01] "POST / HTTP/1.1" 200 -
2023-07-03 08:20:05,114:INFO:factorcheck2:main.py:126:handleKline:2218005: self.closeSec=1688343599, self.tradeDate='20230703', self.openTime='081500', self.closeTime='081959',self.symbol='BTCUSDT',self.open=30647.1, self.close=30674.9, self.high=30683.9, self.low=30647.1   
2023-07-03 08:20:06,714:INFO:factorcheck2:main.py:127:handleKline:2218005: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime    closeSec  ...      low       pct  index  idx
1535  20230703   075500    075959  1688342399  ...  30609.1 -0.000265   1535    5
1536  20230703   080000    080459  1688342699  ...  30600.0  0.000176   1536    0
1537  20230703   080500    080959  1688342999  ...  30600.0  0.000314   1537    1
1538  20230703   081000    081459  1688343299  ...  30619.1  0.000637   1538    2
1539  20230703   081500    081959  1688343599  ...  30647.1  0.000904   1539    3

[5 rows x 11 columns]
2023-07-03 08:20:06,733:INFO:factorcheck2:main.py:128:handleKline:2218005: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}
127.0.0.1 - - [03/Jul/2023 08:25:00] "POST / HTTP/1.1" 200 -

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=126, self.factor=0.4211181976156454, self.count=14371 

self.closeSec=1688343899, self.tradeDate='20230703', self.openTime='082000', self.closeTime='082459', self.symbol='BTCUSDT', self.open=30674.9, self.close=30655.8, self.high=30675.0, self.low=30602.6 
2023-07-03 08:25:00,791:INFO:factorcheck2:main.py:126:handleKline:2218005: self.closeSec=1688343899, self.tradeDate='20230703', self.openTime='082000', self.closeTime='082459',self.symbol='BTCUSDT',self.open=30674.9, self.close=30655.8, self.high=30675.0, self.low=30602.6   
2023-07-03 08:25:00,827:INFO:factorcheck2:main.py:127:handleKline:2218005: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime    closeSec  ...      low       pct  index  idx
1536  20230703   080000    080459  1688342699  ...  30600.0  0.000176   1536    0
1537  20230703   080500    080959  1688342999  ...  30600.0  0.000314   1537    1
1538  20230703   081000    081459  1688343299  ...  30619.1  0.000637   1538    2
1539  20230703   081500    081959  1688343599  ...  30647.1  0.000904   1539    3
1540  20230703   082000    082459  1688343899  ...  30602.6 -0.000623   1540    4

[5 rows x 11 columns]
2023-07-03 08:25:00,827:INFO:factorcheck2:main.py:128:handleKline:2218005: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}


## /root/FIL/strategy/logic/log.txt ----- -----

2023-07-03 08:00:19,005:DEBUG:logic:main.py:463:getModel:2218526: df_s.iloc[-5:,:] :
          date closeTime     open  ...    alpha58   alpha67   alpha72
5770  20230703    052959  30579.6  ...  53.333333  0.522559  0.426939
5771  20230703    055959  30594.6  ...  52.916667  0.510605  0.416869
5772  20230703    062959  30555.0  ...  53.333333  0.546125  0.400563
5773  20230703    065959  30681.1  ...  53.333333  0.533886  0.389569
5774  20230703    072959  30646.7  ...  52.916667  0.518796  0.384682

[5 rows x 33 columns]
0.532347504621072
acc is : 0.532347504621072
2023-07-03 08:00:19,104:INFO:logic:main.py:468:getModel:2218526: df_pred.iloc[-5:,:] :
     pred    prob_0    prob_1  actual  ...       nav  sign  cost_        bm
536     0  0.523511  0.476489       0  ...  0.959664   1.0    0.0  1.019771
537     0  0.510514  0.489486       1  ...  0.963844   1.0    0.0  1.024214
538     0  0.542931  0.457069       0  ...  0.962550   1.0    0.0  1.022839
539     0  0.517398  0.482602       0  ...  0.960905   1.0    0.0  1.021090
540     0  0.510266  0.489734       1  ...  0.961479   1.0    0.0  1.021700

[5 rows x 10 columns]
2023-07-03 08:00:19,117:INFO:logic:main.py:478:getModel:2218526: df_panel.iloc[-5:,:] :
    pred    prob_0    prob_1  actual  ...       nav  sign  cost_        bm
45     0  0.524024  0.475976       0  ...  0.971510   1.0    0.0  1.024061
46     0  0.510626  0.489374       1  ...  0.950097   1.0    0.0  1.001557
47     0  0.543529  0.456471       0  ...  0.962550   1.0    0.0  1.016036
48     0  0.518249  0.481751       0  ...  0.960905   1.0    0.0  1.021090
49     0  0.510266  0.489734       1  ...  0.961479   1.0    0.0  1.021700

[5 rows x 10 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '25.53', 'enterprice': '30560', 'countrevence': '0', 'unrealprofit': '1585.413', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '30622.1', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}


## /root/FIL/strategy/modifiedmom/log.txt ----- -----

623  20230703   075000    075959  1688342399  30569.5  30612.7  0.001413
2023-07-03 08:00:02,037:INFO:modifiedmom:main.py:146:handleKline:2218259: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': True, 'isOpen': False, 'isClose': True, 'isTrig': False}
127.0.0.1 - - [03/Jul/2023 08:10:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=7184 

self.closeSec=1688342999, self.tradeDate='20230703', self.openTime='080000', self.closeTime='080959', self.symbol='BTCUSDT', self.open='30612.7', self.close='30627.7'
2023-07-03 08:10:01,153:INFO:modifiedmom:main.py:144:handleKline:2218259: self.closeSec=1688342999, self.tradeDate='20230703', self.openTime='080000', self.closeTime='080959',self.symbol='BTCUSDT',self.open='30612.7', self.close='30627.7'
2023-07-03 08:10:01,184:INFO:modifiedmom:main.py:145:handleKline:2218259: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec     open    close       pct
620  20230703   072000    072959  1688340599  30566.7  30594.4  0.000906
621  20230703   073000    073959  1688341199  30594.5  30556.6 -0.001236
622  20230703   074000    074959  1688341799  30556.6  30569.5  0.000422
623  20230703   075000    075959  1688342399  30569.5  30612.7  0.001413
624  20230703   080000    080959  1688342999  30612.7  30627.7  0.000490
2023-07-03 08:10:01,184:INFO:modifiedmom:main.py:146:handleKline:2218259: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': True, 'isOpen': False, 'isClose': True, 'isTrig': False}

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=7185 

self.closeSec=1688343599, self.tradeDate='20230703', self.openTime='081000', self.closeTime='081959', self.symbol='BTCUSDT', self.open='30627.2', self.close='30674.9'
127.0.0.1 - - [03/Jul/2023 08:20:04] "POST / HTTP/1.1" 200 -
2023-07-03 08:20:07,734:INFO:modifiedmom:main.py:144:handleKline:2218259: self.closeSec=1688343599, self.tradeDate='20230703', self.openTime='081000', self.closeTime='081959',self.symbol='BTCUSDT',self.open='30627.2', self.close='30674.9'
2023-07-03 08:20:08,695:INFO:modifiedmom:main.py:145:handleKline:2218259: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec     open    close       pct
621  20230703   073000    073959  1688341199  30594.5  30556.6 -0.001236
622  20230703   074000    074959  1688341799  30556.6  30569.5  0.000422
623  20230703   075000    075959  1688342399  30569.5  30612.7  0.001413
624  20230703   080000    080959  1688342999  30612.7  30627.7  0.000490
625  20230703   081000    081959  1688343599  30627.2  30674.9  0.001541
2023-07-03 08:20:08,703:INFO:modifiedmom:main.py:146:handleKline:2218259: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': True, 'isOpen': False, 'isClose': True, 'isTrig': False}


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

17471  20230703   075000    075959  1688342399  30569.5  30612.7
2023-07-03 08:00:02,048:INFO:pyemd2:main.py:127:handleKline:2217508: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}
127.0.0.1 - - [03/Jul/2023 08:10:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=7187 

self.closeSec=1688342999, self.tradeDate='20230703', self.openTime='080000', self.closeTime='080959', self.symbol='BTCUSDT', self.open='30612.7', self.close='30627.7'
2023-07-03 08:10:01,165:INFO:pyemd2:main.py:125:handleKline:2217508: self.closeSec=1688342999, self.tradeDate='20230703', self.openTime='080000', self.closeTime='080959',self.symbol='BTCUSDT',self.open='30612.7', self.close='30627.7'
2023-07-03 08:10:01,194:INFO:pyemd2:main.py:126:handleKline:2217508: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
17468  20230703   072000    072959  1688340599  30566.7  30594.4
17469  20230703   073000    073959  1688341199  30594.5  30556.6
17470  20230703   074000    074959  1688341799  30556.6  30569.5
17471  20230703   075000    075959  1688342399  30569.5  30612.7
17472  20230703   080000    080959  1688342999  30612.7  30627.7
2023-07-03 08:10:01,195:INFO:pyemd2:main.py:127:handleKline:2217508: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=7188 

self.closeSec=1688343599, self.tradeDate='20230703', self.openTime='081000', self.closeTime='081959', self.symbol='BTCUSDT', self.open='30627.2', self.close='30674.9'
127.0.0.1 - - [03/Jul/2023 08:20:05] "POST / HTTP/1.1" 200 -
2023-07-03 08:20:09,639:INFO:pyemd2:main.py:125:handleKline:2217508: self.closeSec=1688343599, self.tradeDate='20230703', self.openTime='081000', self.closeTime='081959',self.symbol='BTCUSDT',self.open='30627.2', self.close='30674.9'
2023-07-03 08:20:09,784:INFO:pyemd2:main.py:126:handleKline:2217508: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
17469  20230703   073000    073959  1688341199  30594.5  30556.6
17470  20230703   074000    074959  1688341799  30556.6  30569.5
17471  20230703   075000    075959  1688342399  30569.5  30612.7
17472  20230703   080000    080959  1688342999  30612.7  30627.7
17473  20230703   081000    081959  1688343599  30627.2  30674.9
2023-07-03 08:20:09,785:INFO:pyemd2:main.py:127:handleKline:2217508: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}


## /root/FIL/strategy/similarity/log.txt ----- -----

12143  20230703   075000    075959  1688342399  30569.5  30612.7
2023-07-03 08:00:02,057:INFO:testStrategy:main.py:103:handleKline:2217133: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': True, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True, 'isCorr': False}
127.0.0.1 - - [03/Jul/2023 08:10:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=7187 

self.closeSec=1688342999, self.tradeDate='20230703', self.openTime='080000', self.closeTime='080959', self.symbol='BTCUSDT', self.open='30612.7', self.close='30627.7'
2023-07-03 08:10:01,170:INFO:testStrategy:main.py:101:handleKline:2217133: self.closeSec=1688342999, self.tradeDate='20230703', self.openTime='080000', self.closeTime='080959',self.symbol='BTCUSDT',self.open='30612.7', self.close='30627.7'
2023-07-03 08:10:01,190:INFO:testStrategy:main.py:102:handleKline:2217133: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
12140  20230703   072000    072959  1688340599  30566.7  30594.4
12141  20230703   073000    073959  1688341199  30594.5  30556.6
12142  20230703   074000    074959  1688341799  30556.6  30569.5
12143  20230703   075000    075959  1688342399  30569.5  30612.7
12144  20230703   080000    080959  1688342999  30612.7  30627.7
2023-07-03 08:10:01,190:INFO:testStrategy:main.py:103:handleKline:2217133: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': True, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True, 'isCorr': False}

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=7188 

self.closeSec=1688343599, self.tradeDate='20230703', self.openTime='081000', self.closeTime='081959', self.symbol='BTCUSDT', self.open='30627.2', self.close='30674.9'
127.0.0.1 - - [03/Jul/2023 08:20:04] "POST / HTTP/1.1" 200 -
2023-07-03 08:20:09,247:INFO:testStrategy:main.py:101:handleKline:2217133: self.closeSec=1688343599, self.tradeDate='20230703', self.openTime='081000', self.closeTime='081959',self.symbol='BTCUSDT',self.open='30627.2', self.close='30674.9'
2023-07-03 08:20:09,523:INFO:testStrategy:main.py:102:handleKline:2217133: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
12141  20230703   073000    073959  1688341199  30594.5  30556.6
12142  20230703   074000    074959  1688341799  30556.6  30569.5
12143  20230703   075000    075959  1688342399  30569.5  30612.7
12144  20230703   080000    080959  1688342999  30612.7  30627.7
12145  20230703   081000    081959  1688343599  30627.2  30674.9
2023-07-03 08:20:09,524:INFO:testStrategy:main.py:103:handleKline:2217133: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': True, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True, 'isCorr': False}


## /root/FIL/strategy/sr_min/log.txt ----- -----

--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=1, self.total=996015.990996, self.flagDict['side']='buy', self.tradeCount=1, self.count=14368
self.closeSec=1688343599, self.tradeDate='20230703', self.openTime='081500', self.closeTime='081959', self.symbol='BTCUSDT', self.open=30647.1, self.close=30674.9, self.high=30683.9, self.low=30647.1, self.vol=1145.822, self.amt=35137132.0011 
127.0.0.1 - - [03/Jul/2023 08:20:01] "POST / HTTP/1.1" 200 -
2023-07-03 08:20:07,764:INFO:sr_min:main.py:172:handleKline:2219263: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5855  20230703   075500    075959  ...         0.0        0.0       0
5856  20230703   080000    080459  ...         0.0        0.0       0
5857  20230703   080500    080959  ...         0.0        0.0       0
5858  20230703   081000    081459  ...         0.0        0.0       0
5859  20230703   081500    081959  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-07-03 08:20:07,804:INFO:sr_min:main.py:175:handleKline:2219263: self.closeSec=1688343599, self.tradeDate='20230703', self.openTime='081500', self.closeTime='081959',self.symbol='BTCUSDT',self.open=30647.1, self.close=30674.9, self.high=30683.9, self.low=30647.1, self.vol=1145.822, self.amt=35137132.0011, ukdf['pct'].iloc[-1]=0.000904 , ukdf['amount'].iloc[-1]=35137132.0011, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5859, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '37.141', 'enterprice': '26844', 'countrevence': '0', 'unrealprofit': '142304.71451495182', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '30675.47234902', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=1
127.0.0.1 - - [03/Jul/2023 08:25:00] "POST / HTTP/1.1" 200 -
--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=1, self.total=996015.990996, self.flagDict['side']='buy', self.tradeCount=1, self.count=14369
self.closeSec=1688343899, self.tradeDate='20230703', self.openTime='082000', self.closeTime='082459', self.symbol='BTCUSDT', self.open=30674.9, self.close=30655.8, self.high=30675.0, self.low=30602.6, self.vol=1072.918, self.amt=32873341.8397 
2023-07-03 08:25:00,840:INFO:sr_min:main.py:172:handleKline:2219263: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5856  20230703   080000    080459  ...         0.0        0.0       0
5857  20230703   080500    080959  ...         0.0        0.0       0
5858  20230703   081000    081459  ...         0.0        0.0       0
5859  20230703   081500    081959  ...         0.0        0.0       0
5860  20230703   082000    082459  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-07-03 08:25:00,840:INFO:sr_min:main.py:175:handleKline:2219263: self.closeSec=1688343899, self.tradeDate='20230703', self.openTime='082000', self.closeTime='082459',self.symbol='BTCUSDT',self.open=30674.9, self.close=30655.8, self.high=30675.0, self.low=30602.6, self.vol=1072.918, self.amt=32873341.8397, ukdf['pct'].iloc[-1]=-0.000623 , ukdf['amount'].iloc[-1]=32873341.8397, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5860, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '37.141', 'enterprice': '26844', 'countrevence': '0', 'unrealprofit': '141574.0638', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '30655.8', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=1


## /root/FIL/strategy/s_rsrs/log.txt ----- -----

719  20230702   200000    235959  1688313599  ...    719  0.001147 -1.277853    -1.0
720  20230703   000000    035959  1688327999  ...    720  0.000765 -1.252254    -1.0

[5 rows x 15 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '53.268', 'enterprice': '30707', 'countrevence': '0', 'unrealprofit': '8179.5333768132', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '30553.4456451', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'numpy.int64'>, curSign=-1, self.sign=-1
127.0.0.1 - - [03/Jul/2023 08:00:01] "POST / HTTP/1.1" 200 -
--handleKline--:  version='2.0.0', self.name='s_rsrs', self.symbol='BTCUSDT', interval='4h', intervalSec=14400, wid=25, thd=0.6, self.sign=-1, self.total=1634064.775524, self.flagDict['side']='sell', self.tradeCount=8, self.count=299
self.closeSec=1688342399, self.tradeDate='20230703', self.openTime='040000', self.closeTime='075959', self.symbol='BTCUSDT', self.open=30552.7, self.close=30612.7, self.high=30800.0, self.low=30425.0, self.vol=65600.069, self.amt=2008247498.50334 
2023-07-03 08:00:01,603:INFO:s_rsrs:main.py:141:handleKline:2218689: self.closeSec=1688342399, self.tradeDate='20230703', self.openTime='040000', self.closeTime='075959',self.symbol='BTCUSDT',self.open=30552.7, self.close=30612.7, self.high=30800.0, self.low=30425.0, self.vol=65600.069, self.amt=2008247498.50334 
2023-07-03 08:00:01,629:INFO:s_rsrs:main.py:142:handleKline:2218689: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime  ...        vol           amt       pct
717  20230702   120000    155959  ...  16551.148  5.048320e+08 -0.000016
718  20230702   160000    195959  ...  13555.768  4.136838e+08  0.001065
719  20230702   200000    235959  ...  61816.394  1.882440e+09 -0.001497
720  20230703   000000    035959  ...  47231.098  1.441850e+09  0.002010
721  20230703   040000    075959  ...  65600.069  2.008247e+09  0.001961

[5 rows x 11 columns]
2023-07-03 08:00:02,933:INFO:s_rsrs:main.py:151:handleKline:2218689: df_s.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec  ...  index      beta    zscore  signal
717  20230702   120000    155959  1688284799  ...    717  0.002523 -1.329504    -1.0
718  20230702   160000    195959  1688299199  ...    718  0.001655 -1.303934    -1.0
719  20230702   200000    235959  1688313599  ...    719  0.001147 -1.277853    -1.0
720  20230703   000000    035959  1688327999  ...    720  0.000765 -1.252254    -1.0
721  20230703   040000    075959  1688342399  ...    721  0.000300 -1.227609    -1.0

[5 rows x 15 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '53.268', 'enterprice': '30707', 'countrevence': '0', 'unrealprofit': '5011.61397536964', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '30612.91698627', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'numpy.int64'>, curSign=-1, self.sign=-1


