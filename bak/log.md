# 20230715 08:26:02

## /root/FIL/strategy/amihud/log.txt ----- -----

--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=373746.4768026, self.flagDict['side']='sell', self.tradeCount=2, self.count=17824
self.closeSec=1689380399, self.tradeDate='20230715', self.openTime='081500', self.closeTime='081959', self.symbol='BTCUSDT', self.open=30249.5, self.close=30250.2, self.high=30265.2, self.low=30244.7, self.vol=371.964, self.amt=11253485.1728 
127.0.0.1 - - [15/Jul/2023 08:20:01] "POST / HTTP/1.1" 200 -
2023-07-15 08:20:05,834:INFO:amihud:main.py:172:handleKline:2219019: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5855  20230715   075500    075959  ...         0.0        0.0       0
5856  20230715   080000    080459  ...         0.0        0.0       0
5857  20230715   080500    080959  ...         0.0        0.0       0
5858  20230715   081000    081459  ...         0.0        0.0       0
5859  20230715   081500    081959  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-07-15 08:20:05,864:INFO:amihud:main.py:175:handleKline:2219019: self.closeSec=1689380399, self.tradeDate='20230715', self.openTime='081500', self.closeTime='081959',self.symbol='BTCUSDT',self.open=30249.5, self.close=30250.2, self.high=30265.2, self.low=30244.7, self.vol=371.964, self.amt=11253485.1728, ukdf['pct'].iloc[-1]=3e-06 , ukdf['amount'].iloc[-1]=11253485.1728, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5859, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '13.926', 'enterprice': '26864.9', 'countrevence': '0', 'unrealprofit': '-47101.55662535994', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '30247.17463919', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1
127.0.0.1 - - [15/Jul/2023 08:25:00] "POST / HTTP/1.1" 200 -
--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=373746.4768026, self.flagDict['side']='sell', self.tradeCount=2, self.count=17825
self.closeSec=1689380699, self.tradeDate='20230715', self.openTime='082000', self.closeTime='082459', self.symbol='BTCUSDT', self.open=30250.1, self.close=30241.9, self.high=30250.2, self.low=30220.2, self.vol=937.386, self.amt=28343697.9984 
2023-07-15 08:25:00,733:INFO:amihud:main.py:172:handleKline:2219019: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5856  20230715   080000    080459  ...         0.0        0.0       0
5857  20230715   080500    080959  ...         0.0        0.0       0
5858  20230715   081000    081459  ...         0.0        0.0       0
5859  20230715   081500    081959  ...         0.0        0.0       0
5860  20230715   082000    082459  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-07-15 08:25:00,734:INFO:amihud:main.py:175:handleKline:2219019: self.closeSec=1689380699, self.tradeDate='20230715', self.openTime='082000', self.closeTime='082459',self.symbol='BTCUSDT',self.open=30250.1, self.close=30241.9, self.high=30250.2, self.low=30220.2, self.vol=937.386, self.amt=28343697.9984, ukdf['pct'].iloc[-1]=-0.000274 , ukdf['amount'].iloc[-1]=28343697.9984, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5860, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '13.926', 'enterprice': '26864.9', 'countrevence': '0', 'unrealprofit': '-47028.102', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '30241.9', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1


## /root/FIL/strategy/factorcheck/log.txt ----- -----


self.closeSec=1689380399, self.tradeDate='20230715', self.openTime='081500', self.closeTime='081959', self.symbol='BTCUSDT', self.open=30249.5, self.close=30250.2, self.high=30265.2, self.low=30244.7 
127.0.0.1 - - [15/Jul/2023 08:20:01] "POST / HTTP/1.1" 200 -
2023-07-15 08:20:03,904:INFO:factorcheck2:main.py:126:handleKline:2218005: self.closeSec=1689380399, self.tradeDate='20230715', self.openTime='081500', self.closeTime='081959',self.symbol='BTCUSDT',self.open=30249.5, self.close=30250.2, self.high=30265.2, self.low=30244.7   
2023-07-15 08:20:05,124:INFO:factorcheck2:main.py:127:handleKline:2218005: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime    closeSec  ...      low       pct  index  idx
1535  20230715   075500    075959  1689379199  ...  30284.0  0.000185   1535    5
1536  20230715   080000    080459  1689379499  ...  30265.5 -0.000568   1536    0
1537  20230715   080500    080959  1689379799  ...  30246.0 -0.000380   1537    1
1538  20230715   081000    081459  1689380099  ...  30246.6 -0.000479   1538    2
1539  20230715   081500    081959  1689380399  ...  30244.7  0.000003   1539    3

[5 rows x 11 columns]
2023-07-15 08:20:05,134:INFO:factorcheck2:main.py:128:handleKline:2218005: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}

--handleKline--: 127.0.0.1 - - [15/Jul/2023 08:25:00] "POST / HTTP/1.1" 200 -
 version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=23, self.factor=0.5977516420385811, self.count=17827 

self.closeSec=1689380699, self.tradeDate='20230715', self.openTime='082000', self.closeTime='082459', self.symbol='BTCUSDT', self.open=30250.1, self.close=30241.9, self.high=30250.2, self.low=30220.2 
2023-07-15 08:25:00,720:INFO:factorcheck2:main.py:126:handleKline:2218005: self.closeSec=1689380699, self.tradeDate='20230715', self.openTime='082000', self.closeTime='082459',self.symbol='BTCUSDT',self.open=30250.1, self.close=30241.9, self.high=30250.2, self.low=30220.2   
2023-07-15 08:25:00,761:INFO:factorcheck2:main.py:127:handleKline:2218005: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime    closeSec  ...      low       pct  index  idx
1536  20230715   080000    080459  1689379499  ...  30265.5 -0.000568   1536    0
1537  20230715   080500    080959  1689379799  ...  30246.0 -0.000380   1537    1
1538  20230715   081000    081459  1689380099  ...  30246.6 -0.000479   1538    2
1539  20230715   081500    081959  1689380399  ...  30244.7  0.000003   1539    3
1540  20230715   082000    082459  1689380699  ...  30220.2 -0.000274   1540    4

[5 rows x 11 columns]
2023-07-15 08:25:00,761:INFO:factorcheck2:main.py:128:handleKline:2218005: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}


## /root/FIL/strategy/logic/log.txt ----- -----

2023-07-15 08:00:19,534:DEBUG:logic:main.py:463:getModel:2218526: df_s.iloc[-5:,:] :
          date closeTime     open  ...    alpha58   alpha67   alpha72
5770  20230715    052959  30170.4  ...  53.750000  0.406331  0.699960
5771  20230715    055959  30197.4  ...  54.166667  0.410782  0.706814
5772  20230715    062959  30224.4  ...  54.166667  0.408030  0.714110
5773  20230715    065959  30200.6  ...  54.166667  0.409286  0.720641
5774  20230715    072959  30207.9  ...  54.583333  0.422921  0.722560

[5 rows x 33 columns]
0.5249537892791127
acc is : 0.5249537892791127
2023-07-15 08:00:19,624:INFO:logic:main.py:468:getModel:2218526: df_pred.iloc[-5:,:] :
     pred    prob_0    prob_1  actual  ...       nav  sign  cost_        bm
536     0  0.535506  0.464494       1  ...  0.984545  -1.0    0.0  0.974959
537     0  0.530094  0.469906       0  ...  0.985320  -1.0    0.0  0.974191
538     0  0.519312  0.480688       1  ...  0.985079  -1.0    0.0  0.974430
539     0  0.535390  0.464610       1  ...  0.982444  -1.0    0.0  0.977036
540     0  0.547916  0.452084       1  ...  0.982298  -1.0    0.0  0.977181

[5 rows x 10 columns]
2023-07-15 08:00:19,635:INFO:logic:main.py:478:getModel:2218526: df_panel.iloc[-5:,:] :
    pred    prob_0    prob_1  actual  ...       nav  sign  cost_        bm
45     0  0.535146  0.464854       1  ...  0.989062  -1.0    0.0  0.973138
46     0  0.529754  0.470246       0  ...  0.990579  -1.0    0.0  0.974361
47     0  0.518808  0.481192       1  ...  0.990336  -1.0    0.0  0.973334
48     0  0.534792  0.465208       1  ...  0.982444  -1.0    0.0  0.977036
49     0  0.547916  0.452084       1  ...  0.982298  -1.0    0.0  0.977181

[5 rows x 10 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '23.927', 'enterprice': '30608.5', 'countrevence': '0', 'unrealprofit': '7619.05624913801', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '30290.07076737', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}


## /root/FIL/strategy/modifiedmom/log.txt ----- -----

623  20230715   075000    075959  1689379199  30258.3  30293.3  0.001153
2023-07-15 08:00:02,241:INFO:modifiedmom:main.py:146:handleKline:2218259: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': True, 'isOpen': False, 'isClose': True, 'isTrig': False}

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=8912 

self.closeSec=1689379799, self.tradeDate='20230715', self.openTime='080000', self.closeTime='080959', self.symbol='BTCUSDT', self.open='30293.3', self.close='30264.6'
2023-07-15 08:10:01,108:INFO:modifiedmom:main.py:144:handleKline:2218259: self.closeSec=1689379799, self.tradeDate='20230715', self.openTime='080000', self.closeTime='080959',self.symbol='BTCUSDT',self.open='30293.3', self.close='30264.6'
127.0.0.1 - - [15/Jul/2023 08:10:01] "POST / HTTP/1.1" 200 -
2023-07-15 08:10:01,118:INFO:modifiedmom:main.py:145:handleKline:2218259: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec     open    close       pct
620  20230715   072000    072959  1689377399  30257.6  30288.8  0.001031
621  20230715   073000    073959  1689377999  30288.8  30296.5  0.000254
622  20230715   074000    074959  1689378599  30296.5  30258.4 -0.001258
623  20230715   075000    075959  1689379199  30258.3  30293.3  0.001153
624  20230715   080000    080959  1689379799  30293.3  30264.6 -0.000947
2023-07-15 08:10:01,118:INFO:modifiedmom:main.py:146:handleKline:2218259: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': True, 'isOpen': False, 'isClose': True, 'isTrig': False}

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=8913 

self.closeSec=1689380399, self.tradeDate='20230715', self.openTime='081000', self.closeTime='081959', self.symbol='BTCUSDT', self.open='30264.6', self.close='30250.1'
127.0.0.1 - - [15/Jul/2023 08:20:04] "POST / HTTP/1.1" 200 -
2023-07-15 08:20:06,114:INFO:modifiedmom:main.py:144:handleKline:2218259: self.closeSec=1689380399, self.tradeDate='20230715', self.openTime='081000', self.closeTime='081959',self.symbol='BTCUSDT',self.open='30264.6', self.close='30250.1'
2023-07-15 08:20:06,784:INFO:modifiedmom:main.py:145:handleKline:2218259: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec     open    close       pct
621  20230715   073000    073959  1689377999  30288.8  30296.5  0.000254
622  20230715   074000    074959  1689378599  30296.5  30258.4 -0.001258
623  20230715   075000    075959  1689379199  30258.3  30293.3  0.001153
624  20230715   080000    080959  1689379799  30293.3  30264.6 -0.000947
625  20230715   081000    081959  1689380399  30264.6  30250.1 -0.000479
2023-07-15 08:20:06,785:INFO:modifiedmom:main.py:146:handleKline:2218259: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': True, 'isOpen': False, 'isClose': True, 'isTrig': False}


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

17471  20230715   075000    075959  1689379199  30258.3  30293.3
2023-07-15 08:00:02,250:INFO:pyemd2:main.py:127:handleKline:2217508: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}
127.0.0.1 - - [15/Jul/2023 08:10:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=8915 

self.closeSec=1689379799, self.tradeDate='20230715', self.openTime='080000', self.closeTime='080959', self.symbol='BTCUSDT', self.open='30293.3', self.close='30264.6'
2023-07-15 08:10:01,114:INFO:pyemd2:main.py:125:handleKline:2217508: self.closeSec=1689379799, self.tradeDate='20230715', self.openTime='080000', self.closeTime='080959',self.symbol='BTCUSDT',self.open='30293.3', self.close='30264.6'
2023-07-15 08:10:01,128:INFO:pyemd2:main.py:126:handleKline:2217508: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
17468  20230715   072000    072959  1689377399  30257.6  30288.8
17469  20230715   073000    073959  1689377999  30288.8  30296.5
17470  20230715   074000    074959  1689378599  30296.5  30258.4
17471  20230715   075000    075959  1689379199  30258.3  30293.3
17472  20230715   080000    080959  1689379799  30293.3  30264.6
2023-07-15 08:10:01,128:INFO:pyemd2:main.py:127:handleKline:2217508: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=8916 

self.closeSec=1689380399, self.tradeDate='20230715', self.openTime='081000', self.closeTime='081959', self.symbol='BTCUSDT', self.open='30264.6', self.close='30250.1'
127.0.0.1 - - [15/Jul/2023 08:20:04] "POST / HTTP/1.1" 200 -
2023-07-15 08:20:07,427:INFO:pyemd2:main.py:125:handleKline:2217508: self.closeSec=1689380399, self.tradeDate='20230715', self.openTime='081000', self.closeTime='081959',self.symbol='BTCUSDT',self.open='30264.6', self.close='30250.1'
2023-07-15 08:20:07,592:INFO:pyemd2:main.py:126:handleKline:2217508: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
17469  20230715   073000    073959  1689377999  30288.8  30296.5
17470  20230715   074000    074959  1689378599  30296.5  30258.4
17471  20230715   075000    075959  1689379199  30258.3  30293.3
17472  20230715   080000    080959  1689379799  30293.3  30264.6
17473  20230715   081000    081959  1689380399  30264.6  30250.1
2023-07-15 08:20:07,593:INFO:pyemd2:main.py:127:handleKline:2217508: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}


## /root/FIL/strategy/similarity/log.txt ----- -----

12143  20230715   075000    075959  1689379199  30258.3  30293.3
2023-07-15 08:00:02,249:INFO:testStrategy:main.py:103:handleKline:2217133: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': True, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True, 'isCorr': False}
127.0.0.1 - - [15/Jul/2023 08:10:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=8915 

self.closeSec=1689379799, self.tradeDate='20230715', self.openTime='080000', self.closeTime='080959', self.symbol='BTCUSDT', self.open='30293.3', self.close='30264.6'
2023-07-15 08:10:01,096:INFO:testStrategy:main.py:101:handleKline:2217133: self.closeSec=1689379799, self.tradeDate='20230715', self.openTime='080000', self.closeTime='080959',self.symbol='BTCUSDT',self.open='30293.3', self.close='30264.6'
2023-07-15 08:10:01,122:INFO:testStrategy:main.py:102:handleKline:2217133: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
12140  20230715   072000    072959  1689377399  30257.6  30288.8
12141  20230715   073000    073959  1689377999  30288.8  30296.5
12142  20230715   074000    074959  1689378599  30296.5  30258.4
12143  20230715   075000    075959  1689379199  30258.3  30293.3
12144  20230715   080000    080959  1689379799  30293.3  30264.6
2023-07-15 08:10:01,122:INFO:testStrategy:main.py:103:handleKline:2217133: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': True, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True, 'isCorr': False}

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=8916 

self.closeSec=1689380399, self.tradeDate='20230715', self.openTime='081000', self.closeTime='081959', self.symbol='BTCUSDT', self.open='30264.6', self.close='30250.1'
127.0.0.1 - - [15/Jul/2023 08:20:04] "POST / HTTP/1.1" 200 -
2023-07-15 08:20:07,287:INFO:testStrategy:main.py:101:handleKline:2217133: self.closeSec=1689380399, self.tradeDate='20230715', self.openTime='081000', self.closeTime='081959',self.symbol='BTCUSDT',self.open='30264.6', self.close='30250.1'
2023-07-15 08:20:07,480:INFO:testStrategy:main.py:102:handleKline:2217133: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
12141  20230715   073000    073959  1689377999  30288.8  30296.5
12142  20230715   074000    074959  1689378599  30296.5  30258.4
12143  20230715   075000    075959  1689379199  30258.3  30293.3
12144  20230715   080000    080959  1689379799  30293.3  30264.6
12145  20230715   081000    081959  1689380399  30264.6  30250.1
2023-07-15 08:20:07,481:INFO:testStrategy:main.py:103:handleKline:2217133: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': True, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True, 'isCorr': False}


## /root/FIL/strategy/sr_min/log.txt ----- -----

--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=1, self.total=996015.990996, self.flagDict['side']='buy', self.tradeCount=1, self.count=17824
self.closeSec=1689380399, self.tradeDate='20230715', self.openTime='081500', self.closeTime='081959', self.symbol='BTCUSDT', self.open=30249.5, self.close=30250.2, self.high=30265.2, self.low=30244.7, self.vol=371.964, self.amt=11253485.1728 
127.0.0.1 - - [15/Jul/2023 08:20:01] "POST / HTTP/1.1" 200 -
2023-07-15 08:20:05,835:INFO:sr_min:main.py:172:handleKline:2219263: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5855  20230715   075500    075959  ...         0.0        0.0       0
5856  20230715   080000    080459  ...         0.0        0.0       0
5857  20230715   080500    080959  ...         0.0        0.0       0
5858  20230715   081000    081459  ...         0.0        0.0       0
5859  20230715   081500    081959  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-07-15 08:20:05,864:INFO:sr_min:main.py:175:handleKline:2219263: self.closeSec=1689380399, self.tradeDate='20230715', self.openTime='081500', self.closeTime='081959',self.symbol='BTCUSDT',self.open=30249.5, self.close=30250.2, self.high=30265.2, self.low=30244.7, self.vol=371.964, self.amt=11253485.1728, ukdf['pct'].iloc[-1]=3e-06 , ukdf['amount'].iloc[-1]=11253485.1728, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5859, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '37.141', 'enterprice': '26844', 'countrevence': '0', 'unrealprofit': '126393.11356569456', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '30247.06167216', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=1
--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=1, self.total=996015.990996, self.flagDict['side']='buy', self.tradeCount=1, self.count=17825
self.closeSec=1689380699, self.tradeDate='20230715', self.openTime='082000', self.closeTime='082459', self.symbol='BTCUSDT', self.open=30250.1, self.close=30241.9, self.high=30250.2, self.low=30220.2, self.vol=937.386, self.amt=28343697.9984 
127.0.0.1 - - [15/Jul/2023 08:25:00] "POST / HTTP/1.1" 200 -
2023-07-15 08:25:00,775:INFO:sr_min:main.py:172:handleKline:2219263: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5856  20230715   080000    080459  ...         0.0        0.0       0
5857  20230715   080500    080959  ...         0.0        0.0       0
5858  20230715   081000    081459  ...         0.0        0.0       0
5859  20230715   081500    081959  ...         0.0        0.0       0
5860  20230715   082000    082459  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-07-15 08:25:00,776:INFO:sr_min:main.py:175:handleKline:2219263: self.closeSec=1689380699, self.tradeDate='20230715', self.openTime='082000', self.closeTime='082459',self.symbol='BTCUSDT',self.open=30250.1, self.close=30241.9, self.high=30250.2, self.low=30220.2, self.vol=937.386, self.amt=28343697.9984, ukdf['pct'].iloc[-1]=-0.000274 , ukdf['amount'].iloc[-1]=28343697.9984, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5860, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '37.141', 'enterprice': '26844', 'countrevence': '0', 'unrealprofit': '126201.4039', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '30241.9', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=1


## /root/FIL/strategy/s_rsrs/log.txt ----- -----

719  20230714   200000    235959  1689350399  ...    719  0.665636  1.274415     1.0
720  20230715   000000    035959  1689364799  ...    720  0.275558 -0.155933     NaN

[5 rows x 15 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '52.241', 'enterprice': '30511.1', 'countrevence': '0', 'unrealprofit': '-21909.8754', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '30091.7', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'numpy.int64'>, curSign=-9223372036854775808, self.sign=1
--handleKline--:  version='2.0.0', self.name='s_rsrs', self.symbol='BTCUSDT', interval='4h', intervalSec=14400, wid=25, thd=0.6, self.sign=1, self.total=1592336.4447248997, self.flagDict['side']='buy', self.tradeCount=11, self.count=371
self.closeSec=1689379199, self.tradeDate='20230715', self.openTime='040000', self.closeTime='075959', self.symbol='BTCUSDT', self.open=30099.9, self.close=30293.3, self.high=30299.9, self.low=29965.0, self.vol=59521.811, self.amt=1795397869.62615 
2023-07-15 08:00:01,732:INFO:s_rsrs:main.py:141:handleKline:2218689: self.closeSec=1689379199, self.tradeDate='20230715', self.openTime='040000', self.closeTime='075959',self.symbol='BTCUSDT',self.open=30099.9, self.close=30293.3, self.high=30299.9, self.low=29965.0, self.vol=59521.811, self.amt=1795397869.62615 
127.0.0.1 - - [15/Jul/2023 08:00:01] "POST / HTTP/1.1" 200 -
2023-07-15 08:00:01,785:INFO:s_rsrs:main.py:142:handleKline:2218689: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime  ...         vol           amt       pct
717  20230714   120000    155959  ...   47214.511  1.477015e+09 -0.011111
718  20230714   160000    195959  ...   43894.191  1.368772e+09  0.003550
719  20230714   200000    235959  ...   60181.765  1.878756e+09  0.000965
720  20230715   000000    035959  ...  267411.025  8.149555e+09 -0.036387
721  20230715   040000    075959  ...   59521.811  1.795398e+09  0.006425

[5 rows x 11 columns]
2023-07-15 08:00:02,910:INFO:s_rsrs:main.py:151:handleKline:2218689: df_s.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec  ...  index      beta    zscore  signal
717  20230714   120000    155959  1689321599  ...    717  0.884779  2.157640     1.0
718  20230714   160000    195959  1689335999  ...    718  0.725703  1.521613     1.0
719  20230714   200000    235959  1689350399  ...    719  0.665636  1.274415     1.0
720  20230715   000000    035959  1689364799  ...    720  0.275558 -0.155933     NaN
721  20230715   040000    075959  1689379199  ...    721  0.334821  0.061710     NaN

[5 rows x 15 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '52.241', 'enterprice': '30511.1', 'countrevence': '0', 'unrealprofit': '-11275.65562787083', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '30295.26080037', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'numpy.int64'>, curSign=-9223372036854775808, self.sign=1


