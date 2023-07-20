# 20230720 08:26:02

## /root/FIL/strategy/amihud/log.txt ----- -----

--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=373746.4768026, self.flagDict['side']='sell', self.tradeCount=2, self.count=19264
self.closeSec=1689812399, self.tradeDate='20230720', self.openTime='081500', self.closeTime='081959', self.symbol='BTCUSDT', self.open=29916.4, self.close=29912.0, self.high=29916.4, self.low=29896.9, self.vol=247.949, self.amt=7415719.9931 
127.0.0.1 - - [20/Jul/2023 08:20:01] "POST / HTTP/1.1" 200 -
2023-07-20 08:20:06,494:INFO:amihud:main.py:172:handleKline:2219019: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5855  20230720   075500    075959  ...         0.0        0.0       0
5856  20230720   080000    080459  ...         0.0        0.0       0
5857  20230720   080500    080959  ...         0.0        0.0       0
5858  20230720   081000    081459  ...         0.0        0.0       0
5859  20230720   081500    081959  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-07-20 08:20:06,504:INFO:amihud:main.py:175:handleKline:2219019: self.closeSec=1689812399, self.tradeDate='20230720', self.openTime='081500', self.closeTime='081959',self.symbol='BTCUSDT',self.open=29916.4, self.close=29912.0, self.high=29916.4, self.low=29896.9, self.vol=247.949, self.amt=7415719.9931, ukdf['pct'].iloc[-1]=-0.000144 , ukdf['amount'].iloc[-1]=7415719.9931, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5859, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '13.926', 'enterprice': '26864.9', 'countrevence': '0', 'unrealprofit': '-42470.1222', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '29914.6', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1
127.0.0.1 - - [20/Jul/2023 08:25:00] "POST / HTTP/1.1" 200 -
--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=373746.4768026, self.flagDict['side']='sell', self.tradeCount=2, self.count=19265
self.closeSec=1689812699, self.tradeDate='20230720', self.openTime='082000', self.closeTime='082459', self.symbol='BTCUSDT', self.open=29912.0, self.close=29903.7, self.high=29931.7, self.low=29903.7, self.vol=499.868, self.amt=14955879.6969 
2023-07-20 08:25:00,761:INFO:amihud:main.py:172:handleKline:2219019: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5856  20230720   080000    080459  ...         0.0        0.0       0
5857  20230720   080500    080959  ...         0.0        0.0       0
5858  20230720   081000    081459  ...         0.0        0.0       0
5859  20230720   081500    081959  ...         0.0        0.0       0
5860  20230720   082000    082459  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-07-20 08:25:00,762:INFO:amihud:main.py:175:handleKline:2219019: self.closeSec=1689812699, self.tradeDate='20230720', self.openTime='082000', self.closeTime='082459',self.symbol='BTCUSDT',self.open=29912.0, self.close=29903.7, self.high=29931.7, self.low=29903.7, self.vol=499.868, self.amt=14955879.6969, ukdf['pct'].iloc[-1]=-0.000277 , ukdf['amount'].iloc[-1]=14955879.6969, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5860, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '13.926', 'enterprice': '26864.9', 'countrevence': '0', 'unrealprofit': '-42352.52603135994', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '29906.15563919', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1


## /root/FIL/strategy/factorcheck/log.txt ----- -----


self.closeSec=1689812399, self.tradeDate='20230720', self.openTime='081500', self.closeTime='081959', self.symbol='BTCUSDT', self.open=29916.4, self.close=29912.0, self.high=29916.4, self.low=29896.9 
127.0.0.1 - - [20/Jul/2023 08:20:01] "POST / HTTP/1.1" 200 -
2023-07-20 08:20:04,466:INFO:factorcheck2:main.py:126:handleKline:2218005: self.closeSec=1689812399, self.tradeDate='20230720', self.openTime='081500', self.closeTime='081959',self.symbol='BTCUSDT',self.open=29916.4, self.close=29912.0, self.high=29916.4, self.low=29896.9   
2023-07-20 08:20:05,624:INFO:factorcheck2:main.py:127:handleKline:2218005: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime    closeSec  ...      low       pct  index  idx
1535  20230720   075500    075959  1689811199  ...  29890.4 -0.000819   1535    5
1536  20230720   080000    080459  1689811499  ...  29880.0  0.000458   1536    0
1537  20230720   080500    080959  1689811799  ...  29895.0 -0.000475   1537    1
1538  20230720   081000    081459  1689812099  ...  29890.8  0.000712   1538    2
1539  20230720   081500    081959  1689812399  ...  29896.9 -0.000144   1539    3

[5 rows x 11 columns]
2023-07-20 08:20:05,634:INFO:factorcheck2:main.py:128:handleKline:2218005: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': True, 'isOpenSell': False, 'isCloseBuy': False, 'isCloseSell': False, 'isOpen': True, 'isClose': False, 'isTrig': True}
127.0.0.1 - - [20/Jul/2023 08:25:00] "POST / HTTP/1.1" 200 -

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=45, self.factor=0.4919117987806642, self.count=19267 

self.closeSec=1689812699, self.tradeDate='20230720', self.openTime='082000', self.closeTime='082459', self.symbol='BTCUSDT', self.open=29912.0, self.close=29903.7, self.high=29931.7, self.low=29903.7 
2023-07-20 08:25:00,725:INFO:factorcheck2:main.py:126:handleKline:2218005: self.closeSec=1689812699, self.tradeDate='20230720', self.openTime='082000', self.closeTime='082459',self.symbol='BTCUSDT',self.open=29912.0, self.close=29903.7, self.high=29931.7, self.low=29903.7   
2023-07-20 08:25:00,736:INFO:factorcheck2:main.py:127:handleKline:2218005: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime    closeSec  ...      low       pct  index  idx
1536  20230720   080000    080459  1689811499  ...  29880.0  0.000458   1536    0
1537  20230720   080500    080959  1689811799  ...  29895.0 -0.000475   1537    1
1538  20230720   081000    081459  1689812099  ...  29890.8  0.000712   1538    2
1539  20230720   081500    081959  1689812399  ...  29896.9 -0.000144   1539    3
1540  20230720   082000    082459  1689812699  ...  29903.7 -0.000277   1540    4

[5 rows x 11 columns]
2023-07-20 08:25:00,736:INFO:factorcheck2:main.py:128:handleKline:2218005: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': True, 'isOpenSell': False, 'isCloseBuy': False, 'isCloseSell': False, 'isOpen': True, 'isClose': False, 'isTrig': True}


## /root/FIL/strategy/logic/log.txt ----- -----

2023-07-20 08:00:17,554:DEBUG:logic:main.py:463:getModel:2218526: df_s.iloc[-5:,:] :
          date closeTime     open  ...    alpha58   alpha67   alpha72
5770  20230720    052959  29951.1  ...  50.833333  0.479042  0.421608
5771  20230720    055959  29907.9  ...  50.833333  0.481652  0.433517
5772  20230720    062959  29918.4  ...  50.833333  0.478617  0.446615
5773  20230720    065959  29905.3  ...  50.416667  0.467142  0.466421
5774  20230720    072959  29856.1  ...  50.416667  0.477895  0.478525

[5 rows x 33 columns]
0.5175600739371534
acc is : 0.5175600739371534
2023-07-20 08:00:17,618:INFO:logic:main.py:468:getModel:2218526: df_pred.iloc[-5:,:] :
     pred    prob_0    prob_1  actual  ...       nav  sign  cost_        bm
536     1  0.483840  0.516160       1  ...  0.932494   1.0    0.0  0.989355
537     1  0.499674  0.500326       0  ...  0.932092   1.0    0.0  0.988929
538     1  0.494015  0.505985       0  ...  0.930555   1.0    0.0  0.987298
539     1  0.488749  0.511251       1  ...  0.931849   1.0    0.0  0.988671
540     0  0.518245  0.481755       0  ...  0.931783   1.0    0.0  0.988601

[5 rows x 10 columns]
2023-07-20 08:00:17,629:INFO:logic:main.py:478:getModel:2218526: df_panel.iloc[-5:,:] :
    pred    prob_0    prob_1  actual  ...       nav  sign  cost_        bm
45     1  0.484204  0.515796       1  ...  0.932494   1.0    0.0  0.990780
46     1  0.499656  0.500344       0  ...  0.932092   1.0    0.0  0.989891
47     1  0.493747  0.506253       0  ...  0.918358   1.0    0.0  0.987129
48     1  0.488700  0.511300       1  ...  0.919635   1.0    0.0  0.988671
49     0  0.518245  0.481755       0  ...  0.931783   1.0    0.0  0.988601

[5 rows x 10 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '23.547', 'enterprice': '29974.9', 'countrevence': '0', 'unrealprofit': '-1822.5378', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '29897.5', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}


## /root/FIL/strategy/modifiedmom/log.txt ----- -----

623  20230720   075000    075959  1689811199  29882.9  29895.5  0.000422
2023-07-20 08:00:02,112:INFO:modifiedmom:main.py:146:handleKline:2218259: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': True, 'isOpen': False, 'isClose': True, 'isTrig': False}
127.0.0.1 - - [20/Jul/2023 08:10:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=9632 

self.closeSec=1689811799, self.tradeDate='20230720', self.openTime='080000', self.closeTime='080959', self.symbol='BTCUSDT', self.open='29895.5', self.close='29895'
2023-07-20 08:10:01,121:INFO:modifiedmom:main.py:144:handleKline:2218259: self.closeSec=1689811799, self.tradeDate='20230720', self.openTime='080000', self.closeTime='080959',self.symbol='BTCUSDT',self.open='29895.5', self.close='29895'
2023-07-20 08:10:01,128:INFO:modifiedmom:main.py:145:handleKline:2218259: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec     open    close       pct
620  20230720   072000    072959  1689809399  29835.7  29897.6  0.002075
621  20230720   073000    073959  1689809999  29897.6  29920.4  0.000763
622  20230720   074000    074959  1689810599  29920.5  29882.9 -0.001253
623  20230720   075000    075959  1689811199  29882.9  29895.5  0.000422
624  20230720   080000    080959  1689811799  29895.5    29895 -0.000017
2023-07-20 08:10:01,128:INFO:modifiedmom:main.py:146:handleKline:2218259: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': True, 'isOpen': False, 'isClose': True, 'isTrig': False}

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=9633 

self.closeSec=1689812399, self.tradeDate='20230720', self.openTime='081000', self.closeTime='081959', self.symbol='BTCUSDT', self.open='29895.1', self.close='29912'
127.0.0.1 - - [20/Jul/2023 08:20:04] "POST / HTTP/1.1" 200 -
2023-07-20 08:20:07,174:INFO:modifiedmom:main.py:144:handleKline:2218259: self.closeSec=1689812399, self.tradeDate='20230720', self.openTime='081000', self.closeTime='081959',self.symbol='BTCUSDT',self.open='29895.1', self.close='29912'
2023-07-20 08:20:07,826:INFO:modifiedmom:main.py:145:handleKline:2218259: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec     open    close       pct
621  20230720   073000    073959  1689809999  29897.6  29920.4  0.000763
622  20230720   074000    074959  1689810599  29920.5  29882.9 -0.001253
623  20230720   075000    075959  1689811199  29882.9  29895.5  0.000422
624  20230720   080000    080959  1689811799  29895.5    29895 -0.000017
625  20230720   081000    081959  1689812399  29895.1    29912  0.000569
2023-07-20 08:20:07,834:INFO:modifiedmom:main.py:146:handleKline:2218259: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': True, 'isOpen': False, 'isClose': True, 'isTrig': False}


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

17471  20230720   075000    075959  1689811199  29882.9  29895.5
2023-07-20 08:00:02,108:INFO:pyemd2:main.py:127:handleKline:2217508: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=9635 

self.closeSec=1689811799, self.tradeDate='20230720', self.openTime='080000', self.closeTime='080959', self.symbol='BTCUSDT', self.open='29895.5', self.close='29895'
2023-07-20 08:10:01,114:INFO:pyemd2:main.py:125:handleKline:2217508: self.closeSec=1689811799, self.tradeDate='20230720', self.openTime='080000', self.closeTime='080959',self.symbol='BTCUSDT',self.open='29895.5', self.close='29895'
127.0.0.1 - - [20/Jul/2023 08:10:01] "POST / HTTP/1.1" 200 -
2023-07-20 08:10:01,125:INFO:pyemd2:main.py:126:handleKline:2217508: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
17468  20230720   072000    072959  1689809399  29835.7  29897.6
17469  20230720   073000    073959  1689809999  29897.6  29920.4
17470  20230720   074000    074959  1689810599  29920.5  29882.9
17471  20230720   075000    075959  1689811199  29882.9  29895.5
17472  20230720   080000    080959  1689811799  29895.5    29895
2023-07-20 08:10:01,126:INFO:pyemd2:main.py:127:handleKline:2217508: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=9636 

self.closeSec=1689812399, self.tradeDate='20230720', self.openTime='081000', self.closeTime='081959', self.symbol='BTCUSDT', self.open='29895.1', self.close='29912'
127.0.0.1 - - [20/Jul/2023 08:20:04] "POST / HTTP/1.1" 200 -
2023-07-20 08:20:08,658:INFO:pyemd2:main.py:125:handleKline:2217508: self.closeSec=1689812399, self.tradeDate='20230720', self.openTime='081000', self.closeTime='081959',self.symbol='BTCUSDT',self.open='29895.1', self.close='29912'
2023-07-20 08:20:08,885:INFO:pyemd2:main.py:126:handleKline:2217508: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
17469  20230720   073000    073959  1689809999  29897.6  29920.4
17470  20230720   074000    074959  1689810599  29920.5  29882.9
17471  20230720   075000    075959  1689811199  29882.9  29895.5
17472  20230720   080000    080959  1689811799  29895.5    29895
17473  20230720   081000    081959  1689812399  29895.1    29912
2023-07-20 08:20:08,887:INFO:pyemd2:main.py:127:handleKline:2217508: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}


## /root/FIL/strategy/similarity/log.txt ----- -----

12143  20230720   075000    075959  1689811199  29882.9  29895.5
2023-07-20 08:00:02,101:INFO:testStrategy:main.py:103:handleKline:2217133: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': True, 'isOpenSell': False, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True, 'isCorr': False}
127.0.0.1 - - [20/Jul/2023 08:10:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=9635 

self.closeSec=1689811799, self.tradeDate='20230720', self.openTime='080000', self.closeTime='080959', self.symbol='BTCUSDT', self.open='29895.5', self.close='29895'
2023-07-20 08:10:01,107:INFO:testStrategy:main.py:101:handleKline:2217133: self.closeSec=1689811799, self.tradeDate='20230720', self.openTime='080000', self.closeTime='080959',self.symbol='BTCUSDT',self.open='29895.5', self.close='29895'
2023-07-20 08:10:01,113:INFO:testStrategy:main.py:102:handleKline:2217133: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
12140  20230720   072000    072959  1689809399  29835.7  29897.6
12141  20230720   073000    073959  1689809999  29897.6  29920.4
12142  20230720   074000    074959  1689810599  29920.5  29882.9
12143  20230720   075000    075959  1689811199  29882.9  29895.5
12144  20230720   080000    080959  1689811799  29895.5    29895
2023-07-20 08:10:01,113:INFO:testStrategy:main.py:103:handleKline:2217133: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': True, 'isOpenSell': False, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True, 'isCorr': False}

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=9636 

self.closeSec=1689812399, self.tradeDate='20230720', self.openTime='081000', self.closeTime='081959', self.symbol='BTCUSDT', self.open='29895.1', self.close='29912'
127.0.0.1 - - [20/Jul/2023 08:20:04] "POST / HTTP/1.1" 200 -
2023-07-20 08:20:08,518:INFO:testStrategy:main.py:101:handleKline:2217133: self.closeSec=1689812399, self.tradeDate='20230720', self.openTime='081000', self.closeTime='081959',self.symbol='BTCUSDT',self.open='29895.1', self.close='29912'
2023-07-20 08:20:08,748:INFO:testStrategy:main.py:102:handleKline:2217133: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
12141  20230720   073000    073959  1689809999  29897.6  29920.4
12142  20230720   074000    074959  1689810599  29920.5  29882.9
12143  20230720   075000    075959  1689811199  29882.9  29895.5
12144  20230720   080000    080959  1689811799  29895.5    29895
12145  20230720   081000    081959  1689812399  29895.1    29912
2023-07-20 08:20:08,754:INFO:testStrategy:main.py:103:handleKline:2217133: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': True, 'isOpenSell': False, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True, 'isCorr': False}


## /root/FIL/strategy/sr_min/log.txt ----- -----

--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=1, self.total=996015.990996, self.flagDict['side']='buy', self.tradeCount=1, self.count=19264
self.closeSec=1689812399, self.tradeDate='20230720', self.openTime='081500', self.closeTime='081959', self.symbol='BTCUSDT', self.open=29916.4, self.close=29912.0, self.high=29916.4, self.low=29896.9, self.vol=247.949, self.amt=7415719.9931 
127.0.0.1 - - [20/Jul/2023 08:20:01] "POST / HTTP/1.1" 200 -
2023-07-20 08:20:06,425:INFO:sr_min:main.py:172:handleKline:2219263: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5855  20230720   075500    075959  ...         0.0        0.0       0
5856  20230720   080000    080459  ...         0.0        0.0       0
5857  20230720   080500    080959  ...         0.0        0.0       0
5858  20230720   081000    081459  ...         0.0        0.0       0
5859  20230720   081500    081959  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-07-20 08:20:06,444:INFO:sr_min:main.py:175:handleKline:2219263: self.closeSec=1689812399, self.tradeDate='20230720', self.openTime='081500', self.closeTime='081959',self.symbol='BTCUSDT',self.open=29916.4, self.close=29912.0, self.high=29916.4, self.low=29896.9, self.vol=247.949, self.amt=7415719.9931, ukdf['pct'].iloc[-1]=-0.000144 , ukdf['amount'].iloc[-1]=7415719.9931, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5859, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '37.141', 'enterprice': '26844', 'countrevence': '0', 'unrealprofit': '114045.1546', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '29914.6', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=1
--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=1, self.total=996015.990996, self.flagDict['side']='buy', self.tradeCount=1, self.count=19265
self.closeSec=1689812699, self.tradeDate='20230720', self.openTime='082000', self.closeTime='082459', self.symbol='BTCUSDT', self.open=29912.0, self.close=29903.7, self.high=29931.7, self.low=29903.7, self.vol=499.868, self.amt=14955879.6969 
127.0.0.1 - - [20/Jul/2023 08:25:00] "POST / HTTP/1.1" 200 -
2023-07-20 08:25:00,747:INFO:sr_min:main.py:172:handleKline:2219263: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5856  20230720   080000    080459  ...         0.0        0.0       0
5857  20230720   080500    080959  ...         0.0        0.0       0
5858  20230720   081000    081459  ...         0.0        0.0       0
5859  20230720   081500    081959  ...         0.0        0.0       0
5860  20230720   082000    082459  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-07-20 08:25:00,747:INFO:sr_min:main.py:175:handleKline:2219263: self.closeSec=1689812699, self.tradeDate='20230720', self.openTime='082000', self.closeTime='082459',self.symbol='BTCUSDT',self.open=29912.0, self.close=29903.7, self.high=29931.7, self.low=29903.7, self.vol=499.868, self.amt=14955879.6969, ukdf['pct'].iloc[-1]=-0.000277 , ukdf['amount'].iloc[-1]=14955879.6969, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5860, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '37.141', 'enterprice': '26844', 'countrevence': '0', 'unrealprofit': '113731.52259515579', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '29906.15563919', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=1


## /root/FIL/strategy/s_rsrs/log.txt ----- -----

719  20230719   200000    235959  1689782399  ...    719  0.193102 -1.108616    -1.0
720  20230720   000000    035959  1689796799  ...    720  0.197121 -1.073679    -1.0

[5 rows x 15 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '52.176', 'enterprice': '29870.6', 'countrevence': '0', 'unrealprofit': '-8447.2944', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '30032.5', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'numpy.int64'>, curSign=-1, self.sign=-1
--handleKline--:  version='2.0.0', self.name='s_rsrs', self.symbol='BTCUSDT', interval='4h', intervalSec=14400, wid=25, thd=0.6, self.sign=-1, self.total=1556969.8971744, self.flagDict['side']='sell', self.tradeCount=12, self.count=401
self.closeSec=1689811199, self.tradeDate='20230720', self.openTime='040000', self.closeTime='075959', self.symbol='BTCUSDT', self.open=30032.4, self.close=29895.5, self.high=30042.0, self.low=29811.0, self.vol=33370.022, self.amt=998031447.949 
127.0.0.1 - - [20/Jul/2023 08:00:01] "POST / HTTP/1.1" 200 -
2023-07-20 08:00:01,689:INFO:s_rsrs:main.py:141:handleKline:2218689: self.closeSec=1689811199, self.tradeDate='20230720', self.openTime='040000', self.closeTime='075959',self.symbol='BTCUSDT',self.open=30032.4, self.close=29895.5, self.high=30042.0, self.low=29811.0, self.vol=33370.022, self.amt=998031447.949 
2023-07-20 08:00:01,704:INFO:s_rsrs:main.py:142:handleKline:2218689: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime  ...        vol           amt       pct
717  20230719   120000    155959  ...  41398.750  1.244758e+09 -0.002130
718  20230719   160000    195959  ...  36932.397  1.106437e+09  0.000690
719  20230719   200000    235959  ...  89657.354  2.682031e+09 -0.002143
720  20230720   000000    035959  ...  50777.186  1.522327e+09  0.003073
721  20230720   040000    075959  ...  33370.022  9.980314e+08 -0.004558

[5 rows x 11 columns]
2023-07-20 08:00:02,436:INFO:s_rsrs:main.py:151:handleKline:2218689: df_s.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec  ...  index      beta    zscore  signal
717  20230719   120000    155959  1689753599  ...    717  0.187934 -1.089182    -1.0
718  20230719   160000    195959  1689767999  ...    718  0.196178 -1.074812    -1.0
719  20230719   200000    235959  1689782399  ...    719  0.193102 -1.108616    -1.0
720  20230720   000000    035959  1689796799  ...    720  0.197121 -1.073679    -1.0
721  20230720   040000    075959  1689811199  ...    721  0.205868 -1.016732    -1.0

[5 rows x 15 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '52.176', 'enterprice': '29870.6', 'countrevence': '0', 'unrealprofit': '-1299.1824', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '29895.5', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'numpy.int64'>, curSign=-1, self.sign=-1


