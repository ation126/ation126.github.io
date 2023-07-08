# 20230708 08:26:02

## /root/FIL/strategy/amihud/log.txt ----- -----

--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=373746.4768026, self.flagDict['side']='sell', self.tradeCount=2, self.count=15808
self.closeSec=1688775599, self.tradeDate='20230708', self.openTime='081500', self.closeTime='081959', self.symbol='BTCUSDT', self.open=30294.9, self.close=30313.0, self.high=30313.1, self.low=30284.7, self.vol=333.477, self.amt=10103267.2724 
127.0.0.1 - - [08/Jul/2023 08:20:01] "POST / HTTP/1.1" 200 -
2023-07-08 08:20:07,439:INFO:amihud:main.py:172:handleKline:2219019: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5855  20230708   075500    075959  ...         0.0        0.0       0
5856  20230708   080000    080459  ...         0.0        0.0       0
5857  20230708   080500    080959  ...         0.0        0.0       0
5858  20230708   081000    081459  ...         0.0        0.0       0
5859  20230708   081500    081959  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-07-08 08:20:07,478:INFO:amihud:main.py:175:handleKline:2219019: self.closeSec=1688775599, self.tradeDate='20230708', self.openTime='081500', self.closeTime='081959',self.symbol='BTCUSDT',self.open=30294.9, self.close=30313.0, self.high=30313.1, self.low=30284.7, self.vol=333.477, self.amt=10103267.2724, ukdf['pct'].iloc[-1]=0.000597 , ukdf['amount'].iloc[-1]=10103267.2724, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5859, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '13.926', 'enterprice': '26864.9', 'countrevence': '0', 'unrealprofit': '-48018.2406', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '30313', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1
127.0.0.1 - - [08/Jul/2023 08:25:00] "POST / HTTP/1.1" 200 -
--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=373746.4768026, self.flagDict['side']='sell', self.tradeCount=2, self.count=15809
self.closeSec=1688775899, self.tradeDate='20230708', self.openTime='082000', self.closeTime='082459', self.symbol='BTCUSDT', self.open=30313.0, self.close=30290.7, self.high=30313.1, self.low=30283.2, self.vol=338.322, self.amt=10249241.625 
2023-07-08 08:25:00,810:INFO:amihud:main.py:172:handleKline:2219019: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5856  20230708   080000    080459  ...         0.0        0.0       0
5857  20230708   080500    080959  ...         0.0        0.0       0
5858  20230708   081000    081459  ...         0.0        0.0       0
5859  20230708   081500    081959  ...         0.0        0.0       0
5860  20230708   082000    082459  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-07-08 08:25:00,810:INFO:amihud:main.py:175:handleKline:2219019: self.closeSec=1688775899, self.tradeDate='20230708', self.openTime='082000', self.closeTime='082459',self.symbol='BTCUSDT',self.open=30313.0, self.close=30290.7, self.high=30313.1, self.low=30283.2, self.vol=338.322, self.amt=10249241.625, ukdf['pct'].iloc[-1]=-0.000736 , ukdf['amount'].iloc[-1]=10249241.625, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5860, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '13.926', 'enterprice': '26864.9', 'countrevence': '0', 'unrealprofit': '-47709.0834', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '30290.8', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1


## /root/FIL/strategy/factorcheck/log.txt ----- -----


self.closeSec=1688775599, self.tradeDate='20230708', self.openTime='081500', self.closeTime='081959', self.symbol='BTCUSDT', self.open=30294.9, self.close=30313.0, self.high=30313.1, self.low=30284.7 
127.0.0.1 - - [08/Jul/2023 08:20:01] "POST / HTTP/1.1" 200 -
2023-07-08 08:20:04,907:INFO:factorcheck2:main.py:126:handleKline:2218005: self.closeSec=1688775599, self.tradeDate='20230708', self.openTime='081500', self.closeTime='081959',self.symbol='BTCUSDT',self.open=30294.9, self.close=30313.0, self.high=30313.1, self.low=30284.7   
2023-07-08 08:20:06,540:INFO:factorcheck2:main.py:127:handleKline:2218005: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime    closeSec  ...      low       pct  index  idx
1535  20230708   075500    075959  1688774399  ...  30305.9  0.000726   1535    5
1536  20230708   080000    080459  1688774699  ...  30304.8 -0.000762   1536    0
1537  20230708   080500    080959  1688774999  ...  30300.0  0.000251   1537    1
1538  20230708   081000    081459  1688775299  ...  30293.2 -0.000577   1538    2
1539  20230708   081500    081959  1688775599  ...  30284.7  0.000597   1539    3

[5 rows x 11 columns]
2023-07-08 08:20:06,561:INFO:factorcheck2:main.py:128:handleKline:2218005: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': True, 'isOpenSell': False, 'isCloseBuy': False, 'isCloseSell': False, 'isOpen': True, 'isClose': False, 'isTrig': True}
127.0.0.1 - - [08/Jul/2023 08:25:00] "POST / HTTP/1.1" 200 -

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=16, self.factor=0.49177472189812277, self.count=15811 

self.closeSec=1688775899, self.tradeDate='20230708', self.openTime='082000', self.closeTime='082459', self.symbol='BTCUSDT', self.open=30313.0, self.close=30290.7, self.high=30313.1, self.low=30283.2 
2023-07-08 08:25:00,745:INFO:factorcheck2:main.py:126:handleKline:2218005: self.closeSec=1688775899, self.tradeDate='20230708', self.openTime='082000', self.closeTime='082459',self.symbol='BTCUSDT',self.open=30313.0, self.close=30290.7, self.high=30313.1, self.low=30283.2   
2023-07-08 08:25:00,791:INFO:factorcheck2:main.py:127:handleKline:2218005: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime    closeSec  ...      low       pct  index  idx
1536  20230708   080000    080459  1688774699  ...  30304.8 -0.000762   1536    0
1537  20230708   080500    080959  1688774999  ...  30300.0  0.000251   1537    1
1538  20230708   081000    081459  1688775299  ...  30293.2 -0.000577   1538    2
1539  20230708   081500    081959  1688775599  ...  30284.7  0.000597   1539    3
1540  20230708   082000    082459  1688775899  ...  30283.2 -0.000736   1540    4

[5 rows x 11 columns]
2023-07-08 08:25:00,791:INFO:factorcheck2:main.py:128:handleKline:2218005: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': True, 'isOpenSell': False, 'isCloseBuy': False, 'isCloseSell': False, 'isOpen': True, 'isClose': False, 'isTrig': True}


## /root/FIL/strategy/logic/log.txt ----- -----

2023-07-08 08:00:18,898:DEBUG:logic:main.py:463:getModel:2218526: df_s.iloc[-5:,:] :
          date closeTime     open  ...    alpha58   alpha67   alpha72
5770  20230708    052959  30248.8  ...  46.666667  0.499367  0.355834
5771  20230708    055959  30329.4  ...  46.666667  0.489982  0.352747
5772  20230708    062959  30276.6  ...  46.666667  0.494343  0.346936
5773  20230708    065959  30300.4  ...  46.666667  0.492927  0.342476
5774  20230708    072959  30292.7  ...  47.083333  0.497427  0.335359

[5 rows x 33 columns]
0.5471349353049908
acc is : 0.5471349353049908
2023-07-08 08:00:18,975:INFO:logic:main.py:468:getModel:2218526: df_pred.iloc[-5:,:] :
     pred    prob_0    prob_1  actual  ...       nav  sign  cost_        bm
536     0  0.549624  0.450376       0  ...  0.987903   1.0    0.0  1.005266
537     0  0.512676  0.487324       1  ...  0.988676   1.0    0.0  1.006053
538     0  0.524381  0.475619       0  ...  0.988422   1.0    0.0  1.005794
539     0  0.517486  0.482514       1  ...  0.989202   1.0    0.0  1.006587
540     0  0.524715  0.475285       1  ...  0.989574   1.0    0.0  1.006966

[5 rows x 10 columns]
2023-07-08 08:00:18,987:INFO:logic:main.py:478:getModel:2218526: df_panel.iloc[-5:,:] :
    pred    prob_0    prob_1  actual  ...       nav  sign  cost_        bm
45     0  0.548926  0.451074       0  ...  0.973908   1.0    0.0  0.995928
46     0  0.512367  0.487633       1  ...  0.974671   1.0    0.0  0.999954
47     0  0.524877  0.475123       0  ...  0.974420   1.0    0.0  1.006670
48     0  0.517486  0.482514       1  ...  0.989202   1.0    0.0  1.006587
49     0  0.524715  0.475285       1  ...  0.989574   1.0    0.0  1.006966

[5 rows x 10 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '24.764', 'enterprice': '30087.2', 'countrevence': '0', 'unrealprofit': '5997.23771042128', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '30329.37564652', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}


## /root/FIL/strategy/modifiedmom/log.txt ----- -----

623  20230708   075000    075959  1688774399  30296.9  30327.9  0.001023
2023-07-08 08:00:02,100:INFO:modifiedmom:main.py:146:handleKline:2218259: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': True, 'isOpen': False, 'isClose': True, 'isTrig': False}

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=7904 

self.closeSec=1688774999, self.tradeDate='20230708', self.openTime='080000', self.closeTime='080959', self.symbol='BTCUSDT', self.open='30328', self.close='30312.4'
2023-07-08 08:10:01,080:INFO:modifiedmom:main.py:144:handleKline:2218259: self.closeSec=1688774999, self.tradeDate='20230708', self.openTime='080000', self.closeTime='080959',self.symbol='BTCUSDT',self.open='30328', self.close='30312.4'
127.0.0.1 - - [08/Jul/2023 08:10:01] "POST / HTTP/1.1" 200 -
2023-07-08 08:10:01,116:INFO:modifiedmom:main.py:145:handleKline:2218259: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec     open    close       pct
620  20230708   072000    072959  1688772599  30313.2  30316.5  0.000106
621  20230708   073000    073959  1688773199  30316.6  30300.5 -0.000528
622  20230708   074000    074959  1688773799  30300.5  30296.9 -0.000119
623  20230708   075000    075959  1688774399  30296.9  30327.9  0.001023
624  20230708   080000    080959  1688774999    30328  30312.4 -0.000511
2023-07-08 08:10:01,116:INFO:modifiedmom:main.py:146:handleKline:2218259: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': True, 'isOpen': False, 'isClose': True, 'isTrig': False}

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=7905 

self.closeSec=1688775599, self.tradeDate='20230708', self.openTime='081000', self.closeTime='081959', self.symbol='BTCUSDT', self.open='30312.5', self.close='30313'
127.0.0.1 - - [08/Jul/2023 08:20:04] "POST / HTTP/1.1" 200 -
2023-07-08 08:20:07,268:INFO:modifiedmom:main.py:144:handleKline:2218259: self.closeSec=1688775599, self.tradeDate='20230708', self.openTime='081000', self.closeTime='081959',self.symbol='BTCUSDT',self.open='30312.5', self.close='30313'
2023-07-08 08:20:08,050:INFO:modifiedmom:main.py:145:handleKline:2218259: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec     open    close       pct
621  20230708   073000    073959  1688773199  30316.6  30300.5 -0.000528
622  20230708   074000    074959  1688773799  30300.5  30296.9 -0.000119
623  20230708   075000    075959  1688774399  30296.9  30327.9  0.001023
624  20230708   080000    080959  1688774999    30328  30312.4 -0.000511
625  20230708   081000    081959  1688775599  30312.5    30313  0.000020
2023-07-08 08:20:08,051:INFO:modifiedmom:main.py:146:handleKline:2218259: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': True, 'isOpen': False, 'isClose': True, 'isTrig': False}


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

17471  20230708   075000    075959  1688774399  30296.9  30327.9
2023-07-08 08:00:02,121:INFO:pyemd2:main.py:127:handleKline:2217508: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=7907 

self.closeSec=1688774999, self.tradeDate='20230708', self.openTime='080000', self.closeTime='080959', self.symbol='BTCUSDT', self.open='30328', self.close='30312.4'
127.0.0.1 - - [08/Jul/2023 08:10:01] "POST / HTTP/1.1" 200 -
2023-07-08 08:10:01,091:INFO:pyemd2:main.py:125:handleKline:2217508: self.closeSec=1688774999, self.tradeDate='20230708', self.openTime='080000', self.closeTime='080959',self.symbol='BTCUSDT',self.open='30328', self.close='30312.4'
2023-07-08 08:10:01,122:INFO:pyemd2:main.py:126:handleKline:2217508: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
17468  20230708   072000    072959  1688772599  30313.2  30316.5
17469  20230708   073000    073959  1688773199  30316.6  30300.5
17470  20230708   074000    074959  1688773799  30300.5  30296.9
17471  20230708   075000    075959  1688774399  30296.9  30327.9
17472  20230708   080000    080959  1688774999    30328  30312.4
2023-07-08 08:10:01,122:INFO:pyemd2:main.py:127:handleKline:2217508: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=7908 

self.closeSec=1688775599, self.tradeDate='20230708', self.openTime='081000', self.closeTime='081959', self.symbol='BTCUSDT', self.open='30312.5', self.close='30313'
127.0.0.1 - - [08/Jul/2023 08:20:04] "POST / HTTP/1.1" 200 -
2023-07-08 08:20:09,120:INFO:pyemd2:main.py:125:handleKline:2217508: self.closeSec=1688775599, self.tradeDate='20230708', self.openTime='081000', self.closeTime='081959',self.symbol='BTCUSDT',self.open='30312.5', self.close='30313'
2023-07-08 08:20:09,300:INFO:pyemd2:main.py:126:handleKline:2217508: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
17469  20230708   073000    073959  1688773199  30316.6  30300.5
17470  20230708   074000    074959  1688773799  30300.5  30296.9
17471  20230708   075000    075959  1688774399  30296.9  30327.9
17472  20230708   080000    080959  1688774999    30328  30312.4
17473  20230708   081000    081959  1688775599  30312.5    30313
2023-07-08 08:20:09,301:INFO:pyemd2:main.py:127:handleKline:2217508: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}


## /root/FIL/strategy/similarity/log.txt ----- -----

12143  20230708   075000    075959  1688774399  30296.9  30327.9
2023-07-08 08:00:02,116:INFO:testStrategy:main.py:103:handleKline:2217133: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': True, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True, 'isCorr': False}

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=7907 

self.closeSec=1688774999, self.tradeDate='20230708', self.openTime='080000', self.closeTime='080959', self.symbol='BTCUSDT', self.open='30328', self.close='30312.4'
2023-07-08 08:10:01,071:INFO:testStrategy:main.py:101:handleKline:2217133: self.closeSec=1688774999, self.tradeDate='20230708', self.openTime='080000', self.closeTime='080959',self.symbol='BTCUSDT',self.open='30328', self.close='30312.4'
127.0.0.1 - - [08/Jul/2023 08:10:01] "POST / HTTP/1.1" 200 -
2023-07-08 08:10:01,114:INFO:testStrategy:main.py:102:handleKline:2217133: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
12140  20230708   072000    072959  1688772599  30313.2  30316.5
12141  20230708   073000    073959  1688773199  30316.6  30300.5
12142  20230708   074000    074959  1688773799  30300.5  30296.9
12143  20230708   075000    075959  1688774399  30296.9  30327.9
12144  20230708   080000    080959  1688774999    30328  30312.4
2023-07-08 08:10:01,114:INFO:testStrategy:main.py:103:handleKline:2217133: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': True, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True, 'isCorr': False}

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=7908 

self.closeSec=1688775599, self.tradeDate='20230708', self.openTime='081000', self.closeTime='081959', self.symbol='BTCUSDT', self.open='30312.5', self.close='30313'
127.0.0.1 - - [08/Jul/2023 08:20:04] "POST / HTTP/1.1" 200 -
2023-07-08 08:20:08,801:INFO:testStrategy:main.py:101:handleKline:2217133: self.closeSec=1688775599, self.tradeDate='20230708', self.openTime='081000', self.closeTime='081959',self.symbol='BTCUSDT',self.open='30312.5', self.close='30313'
2023-07-08 08:20:09,109:INFO:testStrategy:main.py:102:handleKline:2217133: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
12141  20230708   073000    073959  1688773199  30316.6  30300.5
12142  20230708   074000    074959  1688773799  30300.5  30296.9
12143  20230708   075000    075959  1688774399  30296.9  30327.9
12144  20230708   080000    080959  1688774999    30328  30312.4
12145  20230708   081000    081959  1688775599  30312.5    30313
2023-07-08 08:20:09,110:INFO:testStrategy:main.py:103:handleKline:2217133: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': True, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True, 'isCorr': False}


## /root/FIL/strategy/sr_min/log.txt ----- -----

--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=1, self.total=996015.990996, self.flagDict['side']='buy', self.tradeCount=1, self.count=15808
self.closeSec=1688775599, self.tradeDate='20230708', self.openTime='081500', self.closeTime='081959', self.symbol='BTCUSDT', self.open=30294.9, self.close=30313.0, self.high=30313.1, self.low=30284.7, self.vol=333.477, self.amt=10103267.2724 
127.0.0.1 - - [08/Jul/2023 08:20:01] "POST / HTTP/1.1" 200 -
2023-07-08 08:20:07,438:INFO:sr_min:main.py:172:handleKline:2219263: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5855  20230708   075500    075959  ...         0.0        0.0       0
5856  20230708   080000    080459  ...         0.0        0.0       0
5857  20230708   080500    080959  ...         0.0        0.0       0
5858  20230708   081000    081459  ...         0.0        0.0       0
5859  20230708   081500    081959  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-07-08 08:20:07,459:INFO:sr_min:main.py:175:handleKline:2219263: self.closeSec=1688775599, self.tradeDate='20230708', self.openTime='081500', self.closeTime='081959',self.symbol='BTCUSDT',self.open=30294.9, self.close=30313.0, self.high=30313.1, self.low=30284.7, self.vol=333.477, self.amt=10103267.2724, ukdf['pct'].iloc[-1]=0.000597 , ukdf['amount'].iloc[-1]=10103267.2724, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5859, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '37.141', 'enterprice': '26844', 'countrevence': '0', 'unrealprofit': '128842.129', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '30313', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=1
127.0.0.1 - - [08/Jul/2023 08:25:00] "POST / HTTP/1.1" 200 -
--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=1, self.total=996015.990996, self.flagDict['side']='buy', self.tradeCount=1, self.count=15809
self.closeSec=1688775899, self.tradeDate='20230708', self.openTime='082000', self.closeTime='082459', self.symbol='BTCUSDT', self.open=30313.0, self.close=30290.7, self.high=30313.1, self.low=30283.2, self.vol=338.322, self.amt=10249241.625 
2023-07-08 08:25:00,809:INFO:sr_min:main.py:172:handleKline:2219263: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5856  20230708   080000    080459  ...         0.0        0.0       0
5857  20230708   080500    080959  ...         0.0        0.0       0
5858  20230708   081000    081459  ...         0.0        0.0       0
5859  20230708   081500    081959  ...         0.0        0.0       0
5860  20230708   082000    082459  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-07-08 08:25:00,811:INFO:sr_min:main.py:175:handleKline:2219263: self.closeSec=1688775899, self.tradeDate='20230708', self.openTime='082000', self.closeTime='082459',self.symbol='BTCUSDT',self.open=30313.0, self.close=30290.7, self.high=30313.1, self.low=30283.2, self.vol=338.322, self.amt=10249241.625, ukdf['pct'].iloc[-1]=-0.000736 , ukdf['amount'].iloc[-1]=10249241.625, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5860, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '37.141', 'enterprice': '26844', 'countrevence': '0', 'unrealprofit': '128017.5988', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '30290.8', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=1


## /root/FIL/strategy/s_rsrs/log.txt ----- -----

719  20230707   200000    235959  1688745599  ...    719  0.530504  0.507898     NaN
720  20230708   000000    035959  1688759999  ...    720  0.537345  0.564885     NaN

[5 rows x 15 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '53.05', 'enterprice': '30750.9', 'countrevence': '0', 'unrealprofit': '-27728.3413117425', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '30228.21684615', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'numpy.int64'>, curSign=-9223372036854775808, self.sign=1
127.0.0.1 - - [08/Jul/2023 08:00:01] "POST / HTTP/1.1" 200 -
--handleKline--:  version='2.0.0', self.name='s_rsrs', self.symbol='BTCUSDT', interval='4h', intervalSec=14400, wid=25, thd=0.6, self.sign=1, self.total=1629703.909755, self.flagDict['side']='buy', self.tradeCount=9, self.count=329
self.closeSec=1688774399, self.tradeDate='20230708', self.openTime='040000', self.closeTime='075959', self.symbol='BTCUSDT', self.open=30227.8, self.close=30327.9, self.high=30337.0, self.low=30197.1, self.vol=19739.873, self.amt=597713208.2371 
2023-07-08 08:00:01,648:INFO:s_rsrs:main.py:141:handleKline:2218689: self.closeSec=1688774399, self.tradeDate='20230708', self.openTime='040000', self.closeTime='075959',self.symbol='BTCUSDT',self.open=30227.8, self.close=30327.9, self.high=30337.0, self.low=30197.1, self.vol=19739.873, self.amt=597713208.2371 
2023-07-08 08:00:01,698:INFO:s_rsrs:main.py:142:handleKline:2218689: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime  ...         vol           amt       pct
717  20230707   120000    155959  ...   54675.684  1.646778e+09 -0.004286
718  20230707   160000    195959  ...   37803.361  1.137748e+09  0.003701
719  20230707   200000    235959  ...  105396.246  3.188922e+09  0.009015
720  20230708   000000    035959  ...   46214.504  1.398251e+09 -0.004856
721  20230708   040000    075959  ...   19739.873  5.977132e+08  0.003308

[5 rows x 11 columns]
2023-07-08 08:00:03,376:INFO:s_rsrs:main.py:151:handleKline:2218689: df_s.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec  ...  index      beta    zscore  signal
717  20230707   120000    155959  1688716799  ...    717  0.431824  0.158499     NaN
718  20230707   160000    195959  1688731199  ...    718  0.496998  0.374479     NaN
719  20230707   200000    235959  1688745599  ...    719  0.530504  0.507898     NaN
720  20230708   000000    035959  1688759999  ...    720  0.537345  0.564885     NaN
721  20230708   040000    075959  1688774399  ...    721  0.507041  0.506372     NaN

[5 rows x 15 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '53.05', 'enterprice': '30750.9', 'countrevence': '0', 'unrealprofit': '-22220.8755008045', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '30332.03335531', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'numpy.int64'>, curSign=-9223372036854775808, self.sign=1


