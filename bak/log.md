# 20230610 08:26:01

## /root/FIL/strategy/amihud/log.txt ----- -----

--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=373746.4768026, self.flagDict['side']='sell', self.tradeCount=2, self.count=7744
self.closeSec=1686356399, self.tradeDate='20230610', self.openTime='081500', self.closeTime='081959', self.symbol='BTCUSDT', self.open=26463.9, self.close=26457.8, self.high=26476.8, self.low=26456.3, self.vol=503.06, self.amt=13313411.213 
127.0.0.1 - - [10/Jun/2023 08:20:01] "POST / HTTP/1.1" 200 -
2023-06-10 08:20:04,795:INFO:amihud:main.py:172:handleKline:2219019: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5855  20230610   075500    075959  ...         0.0        0.0       0
5856  20230610   080000    080459  ...         0.0        0.0       0
5857  20230610   080500    080959  ...         0.0        0.0       0
5858  20230610   081000    081459  ...         0.0        0.0       0
5859  20230610   081500    081959  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-06-10 08:20:04,814:INFO:amihud:main.py:175:handleKline:2219019: self.closeSec=1686356399, self.tradeDate='20230610', self.openTime='081500', self.closeTime='081959',self.symbol='BTCUSDT',self.open=26463.9, self.close=26457.8, self.high=26476.8, self.low=26456.3, self.vol=503.06, self.amt=13313411.213, ukdf['pct'].iloc[-1]=-0.000227 , ukdf['amount'].iloc[-1]=13313411.213, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5859, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '13.926', 'enterprice': '26864.9', 'countrevence': '0', 'unrealprofit': '5616.81803610906', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '26461.56680769', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1
--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=373746.4768026, self.flagDict['side']='sell', self.tradeCount=2, self.count=7745
self.closeSec=1686356699, self.tradeDate='20230610', self.openTime='082000', self.closeTime='082459', self.symbol='BTCUSDT', self.open=26457.8, self.close=26462.3, self.high=26467.7, self.low=26447.9, self.vol=304.313, self.amt=8051036.1318 
127.0.0.1 - - [10/Jun/2023 08:25:01] "POST / HTTP/1.1" 200 -
2023-06-10 08:25:04,477:INFO:amihud:main.py:172:handleKline:2219019: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5856  20230610   080000    080459  ...         0.0        0.0       0
5857  20230610   080500    080959  ...         0.0        0.0       0
5858  20230610   081000    081459  ...         0.0        0.0       0
5859  20230610   081500    081959  ...         0.0        0.0       0
5860  20230610   082000    082459  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-06-10 08:25:04,490:INFO:amihud:main.py:175:handleKline:2219019: self.closeSec=1686356699, self.tradeDate='20230610', self.openTime='082000', self.closeTime='082459',self.symbol='BTCUSDT',self.open=26457.8, self.close=26462.3, self.high=26467.7, self.low=26447.9, self.vol=304.313, self.amt=8051036.1318, ukdf['pct'].iloc[-1]=0.00017 , ukdf['amount'].iloc[-1]=8051036.1318, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5860, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '13.926', 'enterprice': '26864.9', 'countrevence': '0', 'unrealprofit': '5606.6076', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '26462.3', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1


## /root/FIL/strategy/factorcheck/log.txt ----- -----


self.closeSec=1686356399, self.tradeDate='20230610', self.openTime='081500', self.closeTime='081959', self.symbol='BTCUSDT', self.open=26463.9, self.close=26457.8, self.high=26476.8, self.low=26456.3 
127.0.0.1 - - [10/Jun/2023 08:20:01] "POST / HTTP/1.1" 200 -
2023-06-10 08:20:02,892:INFO:factorcheck2:main.py:126:handleKline:2218005: self.closeSec=1686356399, self.tradeDate='20230610', self.openTime='081500', self.closeTime='081959',self.symbol='BTCUSDT',self.open=26463.9, self.close=26457.8, self.high=26476.8, self.low=26456.3   
2023-06-10 08:20:04,114:INFO:factorcheck2:main.py:127:handleKline:2218005: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime    closeSec  ...      low       pct  index  idx
1535  20230610   075500    075959  1686355199  ...  26465.5 -0.000431   1535    5
1536  20230610   080000    080459  1686355499  ...  26464.0  0.000026   1536    0
1537  20230610   080500    080959  1686355799  ...  26460.4 -0.000185   1537    1
1538  20230610   081000    081459  1686356099  ...  26462.0 -0.000004   1538    2
1539  20230610   081500    081959  1686356399  ...  26456.3 -0.000227   1539    3

[5 rows x 11 columns]
2023-06-10 08:20:04,125:INFO:factorcheck2:main.py:128:handleKline:2218005: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=33, self.factor=0.5321475148243496, self.count=7747 

self.closeSec=1686356699, self.tradeDate='20230610', self.openTime='082000', self.closeTime='082459', self.symbol='BTCUSDT', self.open=26457.8, self.close=26462.3, self.high=26467.7, self.low=26447.9 
127.0.0.1 - - [10/Jun/2023 08:25:01] "POST / HTTP/1.1" 200 -
2023-06-10 08:25:03,288:INFO:factorcheck2:main.py:126:handleKline:2218005: self.closeSec=1686356699, self.tradeDate='20230610', self.openTime='082000', self.closeTime='082459',self.symbol='BTCUSDT',self.open=26457.8, self.close=26462.3, self.high=26467.7, self.low=26447.9   
2023-06-10 08:25:04,039:INFO:factorcheck2:main.py:127:handleKline:2218005: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime    closeSec  ...      low       pct  index  idx
1536  20230610   080000    080459  1686355499  ...  26464.0  0.000026   1536    0
1537  20230610   080500    080959  1686355799  ...  26460.4 -0.000185   1537    1
1538  20230610   081000    081459  1686356099  ...  26462.0 -0.000004   1538    2
1539  20230610   081500    081959  1686356399  ...  26456.3 -0.000227   1539    3
1540  20230610   082000    082459  1686356699  ...  26447.9  0.000170   1540    4

[5 rows x 11 columns]
2023-06-10 08:25:04,040:INFO:factorcheck2:main.py:128:handleKline:2218005: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}


## /root/FIL/strategy/logic/log.txt ----- -----

2023-06-10 08:00:43,808:DEBUG:logic:main.py:463:getModel:2218526: df_s.iloc[-5:,:] :
          date closeTime     open  ...    alpha58   alpha67   alpha72
5770  20230610    052959  26442.9  ...  49.166667  0.483912  0.504460
5771  20230610    055959  26438.1  ...  49.583333  0.490103  0.509407
5772  20230610    062959  26463.2  ...  49.166667  0.487795  0.524621
5773  20230610    065959  26453.5  ...  49.583333  0.494653  0.538194
5774  20230610    072959  26480.9  ...  49.583333  0.487962  0.555400

[5 rows x 33 columns]
0.5046210720887245
acc is : 0.5046210720887245
2023-06-10 08:00:44,043:INFO:logic:main.py:468:getModel:2218526: df_pred.iloc[-5:,:] :
     pred    prob_0    prob_1  actual  ...       nav  sign  cost_        bm
536     1  0.497783  0.502217       1  ...  1.042122   1.0    0.0  0.956344
537     0  0.508389  0.491611       0  ...  1.041740   1.0    0.0  0.955994
538     0  0.501905  0.498095       1  ...  1.042819   1.0    0.0  0.956984
539     0  0.506332  0.493668       0  ...  1.041736   1.0    0.0  0.955990
540     1  0.495459  0.504541       1  ...  1.042319   1.0    0.0  0.956525

[5 rows x 10 columns]
2023-06-10 08:00:44,092:INFO:logic:main.py:478:getModel:2218526: df_panel.iloc[-5:,:] :
    pred    prob_0    prob_1  actual  ...       nav  sign  cost_        bm
45     1  0.497871  0.502129       1  ...  1.042122   1.0    0.0  0.958044
46     0  0.508480  0.491520       0  ...  1.041740   1.0    0.0  0.959855
47     0  0.501779  0.498221       1  ...  1.042819   1.0    0.0  0.959832
48     0  0.506332  0.493668       0  ...  1.041736   1.0    0.0  0.955990
49     1  0.495459  0.504541       1  ...  1.042319   1.0    0.0  0.956525

[5 rows x 10 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '28.647', 'enterprice': '26630.1', 'countrevence': '0', 'unrealprofit': '-4600.56118732011', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '26469.50513187', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}


## /root/FIL/strategy/modifiedmom/log.txt ----- -----

623  20230610   075000    075959  1686355199  26457.1  26468.1  0.000420
2023-06-10 08:00:02,241:INFO:modifiedmom:main.py:146:handleKline:2218259: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': True, 'isOpen': False, 'isClose': True, 'isTrig': False}
127.0.0.1 - - [10/Jun/2023 08:10:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=3872 

self.closeSec=1686355799, self.tradeDate='20230610', self.openTime='080000', self.closeTime='080959', self.symbol='BTCUSDT', self.open='26468.2', self.close='26463.9'
2023-06-10 08:10:01,139:INFO:modifiedmom:main.py:144:handleKline:2218259: self.closeSec=1686355799, self.tradeDate='20230610', self.openTime='080000', self.closeTime='080959',self.symbol='BTCUSDT',self.open='26468.2', self.close='26463.9'
2023-06-10 08:10:01,223:INFO:modifiedmom:main.py:145:handleKline:2218259: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec     open    close       pct
620  20230610   072000    072959  1686353399    26441  26453.3  0.000465
621  20230610   073000    073959  1686353999  26453.4    26443 -0.000389
622  20230610   074000    074959  1686354599    26443    26457  0.000529
623  20230610   075000    075959  1686355199  26457.1  26468.1  0.000420
624  20230610   080000    080959  1686355799  26468.2  26463.9 -0.000159
2023-06-10 08:10:01,223:INFO:modifiedmom:main.py:146:handleKline:2218259: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': True, 'isOpen': False, 'isClose': True, 'isTrig': False}

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=3873 

self.closeSec=1686356399, self.tradeDate='20230610', self.openTime='081000', self.closeTime='081959', self.symbol='BTCUSDT', self.open='26464', self.close='26457.8'
127.0.0.1 - - [10/Jun/2023 08:20:04] "POST / HTTP/1.1" 200 -
2023-06-10 08:20:06,274:INFO:modifiedmom:main.py:144:handleKline:2218259: self.closeSec=1686356399, self.tradeDate='20230610', self.openTime='081000', self.closeTime='081959',self.symbol='BTCUSDT',self.open='26464', self.close='26457.8'
2023-06-10 08:20:06,866:INFO:modifiedmom:main.py:145:handleKline:2218259: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec     open    close       pct
621  20230610   073000    073959  1686353999  26453.4    26443 -0.000389
622  20230610   074000    074959  1686354599    26443    26457  0.000529
623  20230610   075000    075959  1686355199  26457.1  26468.1  0.000420
624  20230610   080000    080959  1686355799  26468.2  26463.9 -0.000159
625  20230610   081000    081959  1686356399    26464  26457.8 -0.000231
2023-06-10 08:20:06,874:INFO:modifiedmom:main.py:146:handleKline:2218259: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': True, 'isOpen': False, 'isClose': True, 'isTrig': False}


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

17471  20230610   075000    075959  1686355199  26457.1  26468.1
2023-06-10 08:00:02,249:INFO:pyemd2:main.py:127:handleKline:2217508: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}
127.0.0.1 - - [10/Jun/2023 08:10:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=3875 

self.closeSec=1686355799, self.tradeDate='20230610', self.openTime='080000', self.closeTime='080959', self.symbol='BTCUSDT', self.open='26468.2', self.close='26463.9'
2023-06-10 08:10:01,161:INFO:pyemd2:main.py:125:handleKline:2217508: self.closeSec=1686355799, self.tradeDate='20230610', self.openTime='080000', self.closeTime='080959',self.symbol='BTCUSDT',self.open='26468.2', self.close='26463.9'
2023-06-10 08:10:01,238:INFO:pyemd2:main.py:126:handleKline:2217508: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
17468  20230610   072000    072959  1686353399    26441  26453.3
17469  20230610   073000    073959  1686353999  26453.4    26443
17470  20230610   074000    074959  1686354599    26443    26457
17471  20230610   075000    075959  1686355199  26457.1  26468.1
17472  20230610   080000    080959  1686355799  26468.2  26463.9
2023-06-10 08:10:01,238:INFO:pyemd2:main.py:127:handleKline:2217508: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=3876 

self.closeSec=1686356399, self.tradeDate='20230610', self.openTime='081000', self.closeTime='081959', self.symbol='BTCUSDT', self.open='26464', self.close='26457.8'
127.0.0.1 - - [10/Jun/2023 08:20:04] "POST / HTTP/1.1" 200 -
2023-06-10 08:20:07,528:INFO:pyemd2:main.py:125:handleKline:2217508: self.closeSec=1686356399, self.tradeDate='20230610', self.openTime='081000', self.closeTime='081959',self.symbol='BTCUSDT',self.open='26464', self.close='26457.8'
2023-06-10 08:20:07,744:INFO:pyemd2:main.py:126:handleKline:2217508: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
17469  20230610   073000    073959  1686353999  26453.4    26443
17470  20230610   074000    074959  1686354599    26443    26457
17471  20230610   075000    075959  1686355199  26457.1  26468.1
17472  20230610   080000    080959  1686355799  26468.2  26463.9
17473  20230610   081000    081959  1686356399    26464  26457.8
2023-06-10 08:20:07,745:INFO:pyemd2:main.py:127:handleKline:2217508: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}


## /root/FIL/strategy/similarity/log.txt ----- -----

12143  20230610   075000    075959  1686355199  26457.1  26468.1
2023-06-10 08:00:02,295:INFO:testStrategy:main.py:103:handleKline:2217133: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': True, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True, 'isCorr': False}
127.0.0.1 - - [10/Jun/2023 08:10:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=3875 

self.closeSec=1686355799, self.tradeDate='20230610', self.openTime='080000', self.closeTime='080959', self.symbol='BTCUSDT', self.open='26468.2', self.close='26463.9'
2023-06-10 08:10:01,168:INFO:testStrategy:main.py:101:handleKline:2217133: self.closeSec=1686355799, self.tradeDate='20230610', self.openTime='080000', self.closeTime='080959',self.symbol='BTCUSDT',self.open='26468.2', self.close='26463.9'
2023-06-10 08:10:01,233:INFO:testStrategy:main.py:102:handleKline:2217133: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
12140  20230610   072000    072959  1686353399    26441  26453.3
12141  20230610   073000    073959  1686353999  26453.4    26443
12142  20230610   074000    074959  1686354599    26443    26457
12143  20230610   075000    075959  1686355199  26457.1  26468.1
12144  20230610   080000    080959  1686355799  26468.2  26463.9
2023-06-10 08:10:01,233:INFO:testStrategy:main.py:103:handleKline:2217133: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': True, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True, 'isCorr': False}

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=3876 

self.closeSec=1686356399, self.tradeDate='20230610', self.openTime='081000', self.closeTime='081959', self.symbol='BTCUSDT', self.open='26464', self.close='26457.8'
127.0.0.1 - - [10/Jun/2023 08:20:03] "POST / HTTP/1.1" 200 -
2023-06-10 08:20:07,126:INFO:testStrategy:main.py:101:handleKline:2217133: self.closeSec=1686356399, self.tradeDate='20230610', self.openTime='081000', self.closeTime='081959',self.symbol='BTCUSDT',self.open='26464', self.close='26457.8'
2023-06-10 08:20:07,485:INFO:testStrategy:main.py:102:handleKline:2217133: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
12141  20230610   073000    073959  1686353999  26453.4    26443
12142  20230610   074000    074959  1686354599    26443    26457
12143  20230610   075000    075959  1686355199  26457.1  26468.1
12144  20230610   080000    080959  1686355799  26468.2  26463.9
12145  20230610   081000    081959  1686356399    26464  26457.8
2023-06-10 08:20:07,485:INFO:testStrategy:main.py:103:handleKline:2217133: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': True, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True, 'isCorr': False}


## /root/FIL/strategy/sr_min/log.txt ----- -----

--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=1, self.total=996015.990996, self.flagDict['side']='buy', self.tradeCount=1, self.count=7744
self.closeSec=1686356399, self.tradeDate='20230610', self.openTime='081500', self.closeTime='081959', self.symbol='BTCUSDT', self.open=26463.9, self.close=26457.8, self.high=26476.8, self.low=26456.3, self.vol=503.06, self.amt=13313411.213 
127.0.0.1 - - [10/Jun/2023 08:20:01] "POST / HTTP/1.1" 200 -
2023-06-10 08:20:04,804:INFO:sr_min:main.py:172:handleKline:2219263: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5855  20230610   075500    075959  ...         0.0        0.0       0
5856  20230610   080000    080459  ...         0.0        0.0       0
5857  20230610   080500    080959  ...         0.0        0.0       0
5858  20230610   081000    081459  ...         0.0        0.0       0
5859  20230610   081500    081959  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-06-10 08:20:04,823:INFO:sr_min:main.py:175:handleKline:2219263: self.closeSec=1686356399, self.tradeDate='20230610', self.openTime='081500', self.closeTime='081959',self.symbol='BTCUSDT',self.open=26463.9, self.close=26457.8, self.high=26476.8, self.low=26456.3, self.vol=503.06, self.amt=13313411.213, ukdf['pct'].iloc[-1]=-0.000227 , ukdf['amount'].iloc[-1]=13313411.213, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5859, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '37.141', 'enterprice': '26844', 'countrevence': '0', 'unrealprofit': '-14201.50233829184', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '26461.63274176', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=1
--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=1, self.total=996015.990996, self.flagDict['side']='buy', self.tradeCount=1, self.count=7745
self.closeSec=1686356699, self.tradeDate='20230610', self.openTime='082000', self.closeTime='082459', self.symbol='BTCUSDT', self.open=26457.8, self.close=26462.3, self.high=26467.7, self.low=26447.9, self.vol=304.313, self.amt=8051036.1318 
127.0.0.1 - - [10/Jun/2023 08:25:01] "POST / HTTP/1.1" 200 -
2023-06-10 08:25:04,440:INFO:sr_min:main.py:172:handleKline:2219263: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5856  20230610   080000    080459  ...         0.0        0.0       0
5857  20230610   080500    080959  ...         0.0        0.0       0
5858  20230610   081000    081459  ...         0.0        0.0       0
5859  20230610   081500    081959  ...         0.0        0.0       0
5860  20230610   082000    082459  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-06-10 08:25:04,449:INFO:sr_min:main.py:175:handleKline:2219263: self.closeSec=1686356699, self.tradeDate='20230610', self.openTime='082000', self.closeTime='082459',self.symbol='BTCUSDT',self.open=26457.8, self.close=26462.3, self.high=26467.7, self.low=26447.9, self.vol=304.313, self.amt=8051036.1318, ukdf['pct'].iloc[-1]=0.00017 , ukdf['amount'].iloc[-1]=8051036.1318, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5860, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '37.141', 'enterprice': '26844', 'countrevence': '0', 'unrealprofit': '-14176.7197', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '26462.3', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=1


## /root/FIL/strategy/s_rsrs/log.txt ----- -----

719  20230609   200000    235959  1686326399  ...    719  0.527936 -0.271627     NaN
720  20230610   000000    035959  1686340799  ...    720  0.551065 -0.193631     NaN

[5 rows x 15 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '55.166', 'enterprice': '27078.6', 'countrevence': '0', 'unrealprofit': '37308.7658', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '26402.3', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'numpy.int64'>, curSign=-9223372036854775808, self.sign=-1
127.0.0.1 - - [10/Jun/2023 08:00:01] "POST / HTTP/1.1" 200 -
--handleKline--:  version='2.0.0', self.name='s_rsrs', self.symbol='BTCUSDT', interval='4h', intervalSec=14400, wid=25, thd=0.6, self.sign=-1, self.total=1492324.2295523998, self.flagDict['side']='sell', self.tradeCount=4, self.count=161
self.closeSec=1686355199, self.tradeDate='20230610', self.openTime='040000', self.closeTime='075959', self.symbol='BTCUSDT', self.open=26399.9, self.close=26468.1, self.high=26490.0, self.low=26385.0, self.vol=17679.394, self.amt=467605934.5811 
2023-06-10 08:00:01,779:INFO:s_rsrs:main.py:141:handleKline:2218689: self.closeSec=1686355199, self.tradeDate='20230610', self.openTime='040000', self.closeTime='075959',self.symbol='BTCUSDT',self.open=26399.9, self.close=26468.1, self.high=26490.0, self.low=26385.0, self.vol=17679.394, self.amt=467605934.5811 
2023-06-10 08:00:01,818:INFO:s_rsrs:main.py:142:handleKline:2218689: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime  ...        vol           amt       pct
717  20230609   120000    155959  ...  33723.828  8.930172e+08  0.000499
718  20230609   160000    195959  ...  49448.532  1.315238e+09  0.004422
719  20230609   200000    235959  ...  78006.116  2.075992e+09 -0.005064
720  20230610   000000    035959  ...  45711.815  1.209032e+09 -0.002460
721  20230610   040000    075959  ...  17679.394  4.676059e+08  0.002580

[5 rows x 11 columns]
2023-06-10 08:00:04,042:INFO:s_rsrs:main.py:151:handleKline:2218689: df_s.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec  ...  index      beta    zscore  signal
717  20230609   120000    155959  1686297599  ...    717  0.493077 -0.392767     NaN
718  20230609   160000    195959  1686311999  ...    718  0.505577 -0.348308     NaN
719  20230609   200000    235959  1686326399  ...    719  0.527936 -0.271627     NaN
720  20230610   000000    035959  1686340799  ...    720  0.551065 -0.193631     NaN
721  20230610   040000    075959  1686355199  ...    721  0.589680 -0.064565     NaN

[5 rows x 15 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '55.166', 'enterprice': '27078.6', 'countrevence': '0', 'unrealprofit': '33651.974620364', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '26468.587046', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'numpy.int64'>, curSign=-9223372036854775808, self.sign=-1


