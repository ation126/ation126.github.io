# 20230719 08:26:02

## /root/FIL/strategy/amihud/log.txt ----- -----

--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=373746.4768026, self.flagDict['side']='sell', self.tradeCount=2, self.count=18976
self.closeSec=1689725999, self.tradeDate='20230719', self.openTime='081500', self.closeTime='081959', self.symbol='BTCUSDT', self.open=29864.4, self.close=29883.5, self.high=29883.5, self.low=29848.8, self.vol=557.565, self.amt=16654040.2125 
127.0.0.1 - - [19/Jul/2023 08:20:01] "POST / HTTP/1.1" 200 -
2023-07-19 08:20:05,618:INFO:amihud:main.py:172:handleKline:2219019: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5855  20230719   075500    075959  ...         0.0        0.0       0
5856  20230719   080000    080459  ...         0.0        0.0       0
5857  20230719   080500    080959  ...         0.0        0.0       0
5858  20230719   081000    081459  ...         0.0        0.0       0
5859  20230719   081500    081959  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-07-19 08:20:05,638:INFO:amihud:main.py:175:handleKline:2219019: self.closeSec=1689725999, self.tradeDate='20230719', self.openTime='081500', self.closeTime='081959',self.symbol='BTCUSDT',self.open=29864.4, self.close=29883.5, self.high=29883.5, self.low=29848.8, self.vol=557.565, self.amt=16654040.2125, ukdf['pct'].iloc[-1]=0.00064 , ukdf['amount'].iloc[-1]=16654040.2125, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5859, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '13.926', 'enterprice': '26864.9', 'countrevence': '0', 'unrealprofit': '-42039.8088', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '29883.7', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1
--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=373746.4768026, self.flagDict['side']='sell', self.tradeCount=2, self.count=18977
self.closeSec=1689726299, self.tradeDate='20230719', self.openTime='082000', self.closeTime='082459', self.symbol='BTCUSDT', self.open=29883.6, self.close=29901.2, self.high=29928.2, self.low=29870.5, self.vol=1679.946, self.amt=50237475.6075 
127.0.0.1 - - [19/Jul/2023 08:25:00] "POST / HTTP/1.1" 200 -
2023-07-19 08:25:00,758:INFO:amihud:main.py:172:handleKline:2219019: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5856  20230719   080000    080459  ...         0.0        0.0       0
5857  20230719   080500    080959  ...         0.0        0.0       0
5858  20230719   081000    081459  ...         0.0        0.0       0
5859  20230719   081500    081959  ...         0.0        0.0       0
5860  20230719   082000    082459  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-07-19 08:25:00,758:INFO:amihud:main.py:175:handleKline:2219019: self.closeSec=1689726299, self.tradeDate='20230719', self.openTime='082000', self.closeTime='082459',self.symbol='BTCUSDT',self.open=29883.6, self.close=29901.2, self.high=29928.2, self.low=29870.5, self.vol=1679.946, self.amt=50237475.6075, ukdf['pct'].iloc[-1]=0.000592 , ukdf['amount'].iloc[-1]=50237475.6075, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5860, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '13.926', 'enterprice': '26864.9', 'countrevence': '0', 'unrealprofit': '-42311.23319690652', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '29903.19047802', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1


## /root/FIL/strategy/factorcheck/log.txt ----- -----


self.closeSec=1689725999, self.tradeDate='20230719', self.openTime='081500', self.closeTime='081959', self.symbol='BTCUSDT', self.open=29864.4, self.close=29883.5, self.high=29883.5, self.low=29848.8 
127.0.0.1 - - [19/Jul/2023 08:20:01] "POST / HTTP/1.1" 200 -
2023-07-19 08:20:03,829:INFO:factorcheck2:main.py:126:handleKline:2218005: self.closeSec=1689725999, self.tradeDate='20230719', self.openTime='081500', self.closeTime='081959',self.symbol='BTCUSDT',self.open=29864.4, self.close=29883.5, self.high=29883.5, self.low=29848.8   
2023-07-19 08:20:04,978:INFO:factorcheck2:main.py:127:handleKline:2218005: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime    closeSec  ...      low       pct  index  idx
1535  20230719   075500    075959  1689724799  ...  29836.0  0.000302   1535    5
1536  20230719   080000    080459  1689725099  ...  29826.7  0.000369   1536    0
1537  20230719   080500    080959  1689725399  ...  29830.0 -0.000291   1537    1
1538  20230719   081000    081459  1689725699  ...  29847.9  0.000553   1538    2
1539  20230719   081500    081959  1689725999  ...  29848.8  0.000640   1539    3

[5 rows x 11 columns]
2023-07-19 08:20:04,987:INFO:factorcheck2:main.py:128:handleKline:2218005: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': True, 'isOpenSell': False, 'isCloseBuy': False, 'isCloseSell': False, 'isOpen': True, 'isClose': False, 'isTrig': True}
127.0.0.1 - - [19/Jul/2023 08:25:00] "POST / HTTP/1.1" 200 -

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=0, self.factor=0.6281384215308918, self.count=18979 

self.closeSec=1689726299, self.tradeDate='20230719', self.openTime='082000', self.closeTime='082459', self.symbol='BTCUSDT', self.open=29883.6, self.close=29901.2, self.high=29928.2, self.low=29870.5 
2023-07-19 08:25:00,731:INFO:factorcheck2:main.py:126:handleKline:2218005: self.closeSec=1689726299, self.tradeDate='20230719', self.openTime='082000', self.closeTime='082459',self.symbol='BTCUSDT',self.open=29883.6, self.close=29901.2, self.high=29928.2, self.low=29870.5   
2023-07-19 08:25:00,757:INFO:factorcheck2:main.py:127:handleKline:2218005: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime    closeSec  ...      low       pct  index  idx
1536  20230719   080000    080459  1689725099  ...  29826.7  0.000369   1536    0
1537  20230719   080500    080959  1689725399  ...  29830.0 -0.000291   1537    1
1538  20230719   081000    081459  1689725699  ...  29847.9  0.000553   1538    2
1539  20230719   081500    081959  1689725999  ...  29848.8  0.000640   1539    3
1540  20230719   082000    082459  1689726299  ...  29870.5  0.000592   1540    4

[5 rows x 11 columns]
2023-07-19 08:25:00,758:INFO:factorcheck2:main.py:128:handleKline:2218005: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': True, 'isOpenSell': False, 'isCloseBuy': False, 'isCloseSell': False, 'isOpen': True, 'isClose': False, 'isTrig': True}


## /root/FIL/strategy/logic/log.txt ----- -----

2023-07-19 08:00:18,373:DEBUG:logic:main.py:463:getModel:2218526: df_s.iloc[-5:,:] :
          date closeTime     open  ...    alpha58   alpha67   alpha72
5770  20230719    052959  29766.8  ...  48.750000  0.451752  0.543115
5771  20230719    055959  29816.3  ...  48.333333  0.447515  0.541345
5772  20230719    062959  29794.0  ...  47.916667  0.444216  0.538026
5773  20230719    065959  29776.7  ...  47.916667  0.451819  0.531889
5774  20230719    072959  29808.6  ...  47.916667  0.456173  0.524211

[5 rows x 33 columns]
0.5249537892791127
acc is : 0.5249537892791127
2023-07-19 08:00:18,430:INFO:logic:main.py:468:getModel:2218526: df_pred.iloc[-5:,:] :
     pred    prob_0    prob_1  actual  ...       nav  sign  cost_        bm
536     0  0.511455  0.488545       0  ...  0.962404  -1.0    0.0  0.984155
537     0  0.503765  0.496235       0  ...  0.962963  -1.0    0.0  0.983583
538     0  0.507929  0.492071       1  ...  0.961932  -1.0    0.0  0.984637
539     0  0.522695  0.477305       1  ...  0.961341  -1.0    0.0  0.985241
540     0  0.518583  0.481417       1  ...  0.960738  -1.0    0.0  0.985859

[5 rows x 10 columns]
2023-07-19 08:00:18,441:INFO:logic:main.py:478:getModel:2218526: df_panel.iloc[-5:,:] :
    pred    prob_0    prob_1  actual  ...       nav  sign  cost_        bm
45     0  0.511153  0.488847       0  ...  0.962404  -1.0    0.0  0.980860
46     0  0.503966  0.496034       0  ...  0.962963  -1.0    0.0  0.981825
47     0  0.507712  0.492288       1  ...  0.961932  -1.0    0.0  0.982411
48     0  0.522870  0.477130       1  ...  0.961341  -1.0    0.0  0.985241
49     0  0.518583  0.481417       1  ...  0.960738  -1.0    0.0  0.985859

[5 rows x 10 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '24.019', 'enterprice': '29696', 'countrevence': '0', 'unrealprofit': '-3706.1317', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '29850.3', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}


## /root/FIL/strategy/modifiedmom/log.txt ----- -----

623  20230719   075000    075959  1689724799  29818.8  29845.6  0.000899
2023-07-19 08:00:02,109:INFO:modifiedmom:main.py:146:handleKline:2218259: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': True, 'isOpen': False, 'isClose': True, 'isTrig': False}
127.0.0.1 - - [19/Jul/2023 08:10:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=9488 

self.closeSec=1689725399, self.tradeDate='20230719', self.openTime='080000', self.closeTime='080959', self.symbol='BTCUSDT', self.open='29845.7', self.close='29847.9'
2023-07-19 08:10:01,158:INFO:modifiedmom:main.py:144:handleKline:2218259: self.closeSec=1689725399, self.tradeDate='20230719', self.openTime='080000', self.closeTime='080959',self.symbol='BTCUSDT',self.open='29845.7', self.close='29847.9'
2023-07-19 08:10:01,168:INFO:modifiedmom:main.py:145:handleKline:2218259: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec     open    close       pct
620  20230719   072000    072959  1689722999  29801.2  29826.9  0.000866
621  20230719   073000    073959  1689723599  29826.9    29805 -0.000734
622  20230719   074000    074959  1689724199    29805  29818.8  0.000463
623  20230719   075000    075959  1689724799  29818.8  29845.6  0.000899
624  20230719   080000    080959  1689725399  29845.7  29847.9  0.000077
2023-07-19 08:10:01,168:INFO:modifiedmom:main.py:146:handleKline:2218259: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': True, 'isOpen': False, 'isClose': True, 'isTrig': False}

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=9489 

self.closeSec=1689725999, self.tradeDate='20230719', self.openTime='081000', self.closeTime='081959', self.symbol='BTCUSDT', self.open='29848', self.close='29883.5'
127.0.0.1 - - [19/Jul/2023 08:20:04] "POST / HTTP/1.1" 200 -
2023-07-19 08:20:06,187:INFO:modifiedmom:main.py:144:handleKline:2218259: self.closeSec=1689725999, self.tradeDate='20230719', self.openTime='081000', self.closeTime='081959',self.symbol='BTCUSDT',self.open='29848', self.close='29883.5'
2023-07-19 08:20:06,768:INFO:modifiedmom:main.py:145:handleKline:2218259: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec     open    close       pct
621  20230719   073000    073959  1689723599  29826.9    29805 -0.000734
622  20230719   074000    074959  1689724199    29805  29818.8  0.000463
623  20230719   075000    075959  1689724799  29818.8  29845.6  0.000899
624  20230719   080000    080959  1689725399  29845.7  29847.9  0.000077
625  20230719   081000    081959  1689725999    29848  29883.5  0.001193
2023-07-19 08:20:06,768:INFO:modifiedmom:main.py:146:handleKline:2218259: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': True, 'isOpen': False, 'isClose': True, 'isTrig': False}


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

17471  20230719   075000    075959  1689724799  29818.8  29845.6
2023-07-19 08:00:02,116:INFO:pyemd2:main.py:127:handleKline:2217508: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}
127.0.0.1 - - [19/Jul/2023 08:10:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=9491 

self.closeSec=1689725399, self.tradeDate='20230719', self.openTime='080000', self.closeTime='080959', self.symbol='BTCUSDT', self.open='29845.7', self.close='29847.9'
2023-07-19 08:10:01,164:INFO:pyemd2:main.py:125:handleKline:2217508: self.closeSec=1689725399, self.tradeDate='20230719', self.openTime='080000', self.closeTime='080959',self.symbol='BTCUSDT',self.open='29845.7', self.close='29847.9'
2023-07-19 08:10:01,170:INFO:pyemd2:main.py:126:handleKline:2217508: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
17468  20230719   072000    072959  1689722999  29801.2  29826.9
17469  20230719   073000    073959  1689723599  29826.9    29805
17470  20230719   074000    074959  1689724199    29805  29818.8
17471  20230719   075000    075959  1689724799  29818.8  29845.6
17472  20230719   080000    080959  1689725399  29845.7  29847.9
2023-07-19 08:10:01,170:INFO:pyemd2:main.py:127:handleKline:2217508: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=9492 

self.closeSec=1689725999, self.tradeDate='20230719', self.openTime='081000', self.closeTime='081959', self.symbol='BTCUSDT', self.open='29848', self.close='29883.5'
127.0.0.1 - - [19/Jul/2023 08:20:04] "POST / HTTP/1.1" 200 -
2023-07-19 08:20:07,409:INFO:pyemd2:main.py:125:handleKline:2217508: self.closeSec=1689725999, self.tradeDate='20230719', self.openTime='081000', self.closeTime='081959',self.symbol='BTCUSDT',self.open='29848', self.close='29883.5'
2023-07-19 08:20:07,593:INFO:pyemd2:main.py:126:handleKline:2217508: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
17469  20230719   073000    073959  1689723599  29826.9    29805
17470  20230719   074000    074959  1689724199    29805  29818.8
17471  20230719   075000    075959  1689724799  29818.8  29845.6
17472  20230719   080000    080959  1689725399  29845.7  29847.9
17473  20230719   081000    081959  1689725999    29848  29883.5
2023-07-19 08:20:07,593:INFO:pyemd2:main.py:127:handleKline:2217508: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}


## /root/FIL/strategy/similarity/log.txt ----- -----

12143  20230719   075000    075959  1689724799  29818.8  29845.6
2023-07-19 08:00:02,096:INFO:testStrategy:main.py:103:handleKline:2217133: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': True, 'isOpenSell': False, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True, 'isCorr': False}

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=9491 

self.closeSec=1689725399, self.tradeDate='20230719', self.openTime='080000', self.closeTime='080959', self.symbol='BTCUSDT', self.open='29845.7', self.close='29847.9'
2023-07-19 08:10:01,153:INFO:testStrategy:main.py:101:handleKline:2217133: self.closeSec=1689725399, self.tradeDate='20230719', self.openTime='080000', self.closeTime='080959',self.symbol='BTCUSDT',self.open='29845.7', self.close='29847.9'
127.0.0.1 - - [19/Jul/2023 08:10:01] "POST / HTTP/1.1" 200 -
2023-07-19 08:10:01,159:INFO:testStrategy:main.py:102:handleKline:2217133: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
12140  20230719   072000    072959  1689722999  29801.2  29826.9
12141  20230719   073000    073959  1689723599  29826.9    29805
12142  20230719   074000    074959  1689724199    29805  29818.8
12143  20230719   075000    075959  1689724799  29818.8  29845.6
12144  20230719   080000    080959  1689725399  29845.7  29847.9
2023-07-19 08:10:01,159:INFO:testStrategy:main.py:103:handleKline:2217133: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': True, 'isOpenSell': False, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True, 'isCorr': False}

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=9492 

self.closeSec=1689725999, self.tradeDate='20230719', self.openTime='081000', self.closeTime='081959', self.symbol='BTCUSDT', self.open='29848', self.close='29883.5'
127.0.0.1 - - [19/Jul/2023 08:20:04] "POST / HTTP/1.1" 200 -
2023-07-19 08:20:07,279:INFO:testStrategy:main.py:101:handleKline:2217133: self.closeSec=1689725999, self.tradeDate='20230719', self.openTime='081000', self.closeTime='081959',self.symbol='BTCUSDT',self.open='29848', self.close='29883.5'
2023-07-19 08:20:07,482:INFO:testStrategy:main.py:102:handleKline:2217133: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
12141  20230719   073000    073959  1689723599  29826.9    29805
12142  20230719   074000    074959  1689724199    29805  29818.8
12143  20230719   075000    075959  1689724799  29818.8  29845.6
12144  20230719   080000    080959  1689725399  29845.7  29847.9
12145  20230719   081000    081959  1689725999    29848  29883.5
2023-07-19 08:20:07,487:INFO:testStrategy:main.py:103:handleKline:2217133: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': True, 'isOpenSell': False, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True, 'isCorr': False}


## /root/FIL/strategy/sr_min/log.txt ----- -----

--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=1, self.total=996015.990996, self.flagDict['side']='buy', self.tradeCount=1, self.count=18976
self.closeSec=1689725999, self.tradeDate='20230719', self.openTime='081500', self.closeTime='081959', self.symbol='BTCUSDT', self.open=29864.4, self.close=29883.5, self.high=29883.5, self.low=29848.8, self.vol=557.565, self.amt=16654040.2125 
127.0.0.1 - - [19/Jul/2023 08:20:01] "POST / HTTP/1.1" 200 -
2023-07-19 08:20:05,608:INFO:sr_min:main.py:172:handleKline:2219263: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5855  20230719   075500    075959  ...         0.0        0.0       0
5856  20230719   080000    080459  ...         0.0        0.0       0
5857  20230719   080500    080959  ...         0.0        0.0       0
5858  20230719   081000    081459  ...         0.0        0.0       0
5859  20230719   081500    081959  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-07-19 08:20:05,638:INFO:sr_min:main.py:175:handleKline:2219263: self.closeSec=1689725999, self.tradeDate='20230719', self.openTime='081500', self.closeTime='081959',self.symbol='BTCUSDT',self.open=29864.4, self.close=29883.5, self.high=29883.5, self.low=29848.8, self.vol=557.565, self.amt=16654040.2125, ukdf['pct'].iloc[-1]=0.00064 , ukdf['amount'].iloc[-1]=16654040.2125, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5859, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '37.141', 'enterprice': '26844', 'countrevence': '0', 'unrealprofit': '112897.4977', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '29883.7', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=1
127.0.0.1 - - [19/Jul/2023 08:25:00] "POST / HTTP/1.1" 200 -
--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=1, self.total=996015.990996, self.flagDict['side']='buy', self.tradeCount=1, self.count=18977
self.closeSec=1689726299, self.tradeDate='20230719', self.openTime='082000', self.closeTime='082459', self.symbol='BTCUSDT', self.open=29883.6, self.close=29901.2, self.high=29928.2, self.low=29870.5, self.vol=1679.946, self.amt=50237475.6075 
2023-07-19 08:25:00,767:INFO:sr_min:main.py:172:handleKline:2219263: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5856  20230719   080000    080459  ...         0.0        0.0       0
5857  20230719   080500    080959  ...         0.0        0.0       0
5858  20230719   081000    081459  ...         0.0        0.0       0
5859  20230719   081500    081959  ...         0.0        0.0       0
5860  20230719   082000    082459  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-07-19 08:25:00,767:INFO:sr_min:main.py:175:handleKline:2219263: self.closeSec=1689726299, self.tradeDate='20230719', self.openTime='082000', self.closeTime='082459',self.symbol='BTCUSDT',self.open=29883.6, self.close=29901.2, self.high=29928.2, self.low=29870.5, self.vol=1679.946, self.amt=50237475.6075, ukdf['pct'].iloc[-1]=0.000592 , ukdf['amount'].iloc[-1]=50237475.6075, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5860, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '37.141', 'enterprice': '26844', 'countrevence': '0', 'unrealprofit': '113621.39354414082', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '29903.19047802', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=1


## /root/FIL/strategy/s_rsrs/log.txt ----- -----

719  20230718   200000    235959  1689695999  ...    719  0.126414 -1.279727    -1.0
720  20230719   000000    035959  1689710399  ...    720  0.008772 -1.763798    -1.0

[5 rows x 15 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '52.176', 'enterprice': '29870.6', 'countrevence': '0', 'unrealprofit': '8635.128', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '29705.1', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'numpy.int64'>, curSign=-1, self.sign=-1
127.0.0.1 - - [19/Jul/2023 08:00:01] "POST / HTTP/1.1" 200 -
--handleKline--:  version='2.0.0', self.name='s_rsrs', self.symbol='BTCUSDT', interval='4h', intervalSec=14400, wid=25, thd=0.6, self.sign=-1, self.total=1556969.8971744, self.flagDict['side']='sell', self.tradeCount=12, self.count=395
self.closeSec=1689724799, self.tradeDate='20230719', self.openTime='040000', self.closeTime='075959', self.symbol='BTCUSDT', self.open=29708.2, self.close=29845.6, self.high=29859.0, self.low=29678.0, self.vol=27128.255, self.amt=807831514.2721 
2023-07-19 08:00:01,691:INFO:s_rsrs:main.py:141:handleKline:2218689: self.closeSec=1689724799, self.tradeDate='20230719', self.openTime='040000', self.closeTime='075959',self.symbol='BTCUSDT',self.open=29708.2, self.close=29845.6, self.high=29859.0, self.low=29678.0, self.vol=27128.255, self.amt=807831514.2721 
2023-07-19 08:00:01,703:INFO:s_rsrs:main.py:142:handleKline:2218689: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime  ...        vol           amt       pct
717  20230718   120000    155959  ...  38504.713  1.155475e+09 -0.003722
718  20230718   160000    195959  ...  60543.472  1.813636e+09 -0.002668
719  20230718   200000    235959  ...  98912.984  2.951515e+09  0.000773
720  20230719   000000    035959  ...  88550.243  2.633595e+09 -0.006255
721  20230719   040000    075959  ...  27128.255  8.078315e+08  0.004628

[5 rows x 11 columns]
2023-07-19 08:00:02,444:INFO:s_rsrs:main.py:151:handleKline:2218689: df_s.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec  ...  index      beta    zscore  signal
717  20230718   120000    155959  1689667199  ...    717  0.375309 -0.236925     NaN
718  20230718   160000    195959  1689681599  ...    718  0.239216 -0.804205    -1.0
719  20230718   200000    235959  1689695999  ...    719  0.126414 -1.279727    -1.0
720  20230719   000000    035959  1689710399  ...    720  0.008772 -1.763798    -1.0
721  20230719   040000    075959  1689724799  ...    721  0.176731 -1.095059    -1.0

[5 rows x 15 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '52.176', 'enterprice': '29870.6', 'countrevence': '0', 'unrealprofit': '1142.3857796904', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '29848.70514835', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'numpy.int64'>, curSign=-1, self.sign=-1


