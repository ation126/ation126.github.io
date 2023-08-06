# 20230806 08:26:01

## /root/FIL/strategy/amihud/log.txt ----- -----

--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=373746.4768026, self.flagDict['side']='sell', self.tradeCount=2, self.count=24160
self.closeSec=1691281199, self.tradeDate='20230806', self.openTime='081500', self.closeTime='081959', self.symbol='BTCUSDT', self.open=29048.1, self.close=29049.8, self.high=29049.9, self.low=29045.5, self.vol=108.506, self.amt=3151698.0212 
127.0.0.1 - - [06/Aug/2023 08:20:01] "POST / HTTP/1.1" 200 -
2023-08-06 08:20:06,828:INFO:amihud:main.py:172:handleKline:2219019: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5855  20230806   075500    075959  ...         0.0        0.0       0
5856  20230806   080000    080459  ...         0.0        0.0       0
5857  20230806   080500    080959  ...         0.0        0.0       0
5858  20230806   081000    081459  ...         0.0        0.0       0
5859  20230806   081500    081959  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-08-06 08:20:06,847:INFO:amihud:main.py:175:handleKline:2219019: self.closeSec=1691281199, self.tradeDate='20230806', self.openTime='081500', self.closeTime='081959',self.symbol='BTCUSDT',self.open=29048.1, self.close=29049.8, self.high=29049.9, self.low=29045.5, self.vol=108.506, self.amt=3151698.0212, ukdf['pct'].iloc[-1]=6.2e-05 , ukdf['amount'].iloc[-1]=3151698.0212, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5859, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '13.926', 'enterprice': '26864.9', 'countrevence': '0', 'unrealprofit': '-30426.9174', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '29049.8', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1
--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=373746.4768026, self.flagDict['side']='sell', self.tradeCount=2, self.count=24161
self.closeSec=1691281499, self.tradeDate='20230806', self.openTime='082000', self.closeTime='082459', self.symbol='BTCUSDT', self.open=29049.8, self.close=29051.9, self.high=29051.9, self.low=29049.8, self.vol=136.152, self.amt=3955357.2736 
127.0.0.1 - - [06/Aug/2023 08:25:00] "POST / HTTP/1.1" 200 -
2023-08-06 08:25:00,836:INFO:amihud:main.py:172:handleKline:2219019: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5856  20230806   080000    080459  ...         0.0        0.0       0
5857  20230806   080500    080959  ...         0.0        0.0       0
5858  20230806   081000    081459  ...         0.0        0.0       0
5859  20230806   081500    081959  ...         0.0        0.0       0
5860  20230806   082000    082459  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-08-06 08:25:00,837:INFO:amihud:main.py:175:handleKline:2219019: self.closeSec=1691281499, self.tradeDate='20230806', self.openTime='082000', self.closeTime='082459',self.symbol='BTCUSDT',self.open=29049.8, self.close=29051.9, self.high=29051.9, self.low=29049.8, self.vol=136.152, self.amt=3955357.2736, ukdf['pct'].iloc[-1]=7.2e-05 , ukdf['amount'].iloc[-1]=3955357.2736, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5860, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '13.926', 'enterprice': '26864.9', 'countrevence': '0', 'unrealprofit': '-30456.162', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '29051.9', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1


## /root/FIL/strategy/factorcheck/log.txt ----- -----


self.closeSec=1691281199, self.tradeDate='20230806', self.openTime='081500', self.closeTime='081959', self.symbol='BTCUSDT', self.open=29048.1, self.close=29049.8, self.high=29049.9, self.low=29045.5 
127.0.0.1 - - [06/Aug/2023 08:20:01] "POST / HTTP/1.1" 200 -
2023-08-06 08:20:04,692:INFO:factorcheck2:main.py:126:handleKline:2218005: self.closeSec=1691281199, self.tradeDate='20230806', self.openTime='081500', self.closeTime='081959',self.symbol='BTCUSDT',self.open=29048.1, self.close=29049.8, self.high=29049.9, self.low=29045.5   
2023-08-06 08:20:06,031:INFO:factorcheck2:main.py:127:handleKline:2218005: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime    closeSec  ...      low       pct  index  idx
1535  20230806   075500    075959  1691279999  ...  29057.7 -0.000200   1535    5
1536  20230806   080000    080459  1691280299  ...  29053.0 -0.000165   1536    0
1537  20230806   080500    080959  1691280599  ...  29047.5 -0.000189   1537    1
1538  20230806   081000    081459  1691280899  ...  29047.5  0.000017   1538    2
1539  20230806   081500    081959  1691281199  ...  29045.5  0.000062   1539    3

[5 rows x 11 columns]
2023-08-06 08:20:06,041:INFO:factorcheck2:main.py:128:handleKline:2218005: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=75, self.factor=0.5289802314839163, self.count=24163 

self.closeSec=1691281499, self.tradeDate='20230806', self.openTime='082000', self.closeTime='082459', self.symbol='BTCUSDT', self.open=29049.8, self.close=29051.9, self.high=29051.9, self.low=29049.8 
127.0.0.1 - - [06/Aug/2023 08:25:00] "POST / HTTP/1.1" 200 -
2023-08-06 08:25:00,803:INFO:factorcheck2:main.py:126:handleKline:2218005: self.closeSec=1691281499, self.tradeDate='20230806', self.openTime='082000', self.closeTime='082459',self.symbol='BTCUSDT',self.open=29049.8, self.close=29051.9, self.high=29051.9, self.low=29049.8   
2023-08-06 08:25:00,817:INFO:factorcheck2:main.py:127:handleKline:2218005: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime    closeSec  ...      low       pct  index  idx
1536  20230806   080000    080459  1691280299  ...  29053.0 -0.000165   1536    0
1537  20230806   080500    080959  1691280599  ...  29047.5 -0.000189   1537    1
1538  20230806   081000    081459  1691280899  ...  29047.5  0.000017   1538    2
1539  20230806   081500    081959  1691281199  ...  29045.5  0.000062   1539    3
1540  20230806   082000    082459  1691281499  ...  29049.8  0.000072   1540    4

[5 rows x 11 columns]
2023-08-06 08:25:00,817:INFO:factorcheck2:main.py:128:handleKline:2218005: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}


## /root/FIL/strategy/logic/log.txt ----- -----

2023-08-06 08:00:16,465:DEBUG:logic:main.py:463:getModel:2218526: df_s.iloc[-5:,:] :
          date closeTime     open  ...    alpha58   alpha67   alpha72
5770  20230806    052959  29044.0  ...  48.750000  0.480364  0.441660
5771  20230806    055959  29062.4  ...  48.750000  0.480897  0.428222
5772  20230806    062959  29063.5  ...  48.750000  0.480120  0.416512
5773  20230806    065959  29061.8  ...  49.166667  0.488404  0.397408
5774  20230806    072959  29078.5  ...  49.166667  0.485803  0.380553

[5 rows x 33 columns]
0.5508317929759704
acc is : 0.5508317929759704
2023-08-06 08:00:16,526:INFO:logic:main.py:468:getModel:2218526: df_pred.iloc[-5:,:] :
     pred    prob_0    prob_1  actual  ...       nav  sign  cost_        bm
536     0  0.500945  0.499055       1  ...  0.984185   1.0    0.0  0.993458
537     1  0.496481  0.503519       0  ...  0.984128   1.0    0.0  0.993399
538     1  0.495729  0.504271       1  ...  0.984693   1.0    0.0  0.993970
539     0  0.502158  0.497842       0  ...  0.984507   1.0    0.0  0.993782
540     1  0.497720  0.502280       0  ...  0.983989   1.0    0.0  0.993259

[5 rows x 10 columns]
2023-08-06 08:00:16,537:INFO:logic:main.py:478:getModel:2218526: df_panel.iloc[-5:,:] :
    pred    prob_0    prob_1  actual  ...       nav  sign  cost_        bm
45     0  0.501041  0.498959       1  ...  0.984185   1.0    0.0  0.996451
46     1  0.496467  0.503533       0  ...  0.984128   1.0    0.0  0.994657
47     1  0.495876  0.504124       1  ...  0.984693   1.0    0.0  0.995362
48     0  0.502158  0.497842       0  ...  0.984507   1.0    0.0  0.993782
49     1  0.497720  0.502280       0  ...  0.983989   1.0    0.0  0.993259

[5 rows x 10 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '24.06', 'enterprice': '29131.5', 'countrevence': '0', 'unrealprofit': '-1746.4657707162', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '29058.91206273', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}


## /root/FIL/strategy/modifiedmom/log.txt ----- -----

623  20230806   075000    075959  1691279999  29061.7  29057.7 -0.000138
2023-08-06 08:00:02,125:INFO:modifiedmom:main.py:146:handleKline:2218259: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': True, 'isOpen': False, 'isClose': True, 'isTrig': False}

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=12080 

self.closeSec=1691280599, self.tradeDate='20230806', self.openTime='080000', self.closeTime='080959', self.symbol='BTCUSDT', self.open='29057.7', self.close='29047.5'
2023-08-06 08:10:01,130:INFO:modifiedmom:main.py:144:handleKline:2218259: self.closeSec=1691280599, self.tradeDate='20230806', self.openTime='080000', self.closeTime='080959',self.symbol='BTCUSDT',self.open='29057.7', self.close='29047.5'
127.0.0.1 - - [06/Aug/2023 08:10:01] "POST / HTTP/1.1" 200 -
2023-08-06 08:10:01,157:INFO:modifiedmom:main.py:145:handleKline:2218259: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec     open    close       pct
620  20230806   072000    072959  1691278199  29070.1    29073  0.000100
621  20230806   073000    073959  1691278799    29073  29063.3 -0.000334
622  20230806   074000    074959  1691279399  29063.3  29061.7 -0.000055
623  20230806   075000    075959  1691279999  29061.7  29057.7 -0.000138
624  20230806   080000    080959  1691280599  29057.7  29047.5 -0.000351
2023-08-06 08:10:01,157:INFO:modifiedmom:main.py:146:handleKline:2218259: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': True, 'isOpen': False, 'isClose': True, 'isTrig': False}

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=12081 

self.closeSec=1691281199, self.tradeDate='20230806', self.openTime='081000', self.closeTime='081959', self.symbol='BTCUSDT', self.open='29047.5', self.close='29049.8'
127.0.0.1 - - [06/Aug/2023 08:20:04] "POST / HTTP/1.1" 200 -
2023-08-06 08:20:07,347:INFO:modifiedmom:main.py:144:handleKline:2218259: self.closeSec=1691281199, self.tradeDate='20230806', self.openTime='081000', self.closeTime='081959',self.symbol='BTCUSDT',self.open='29047.5', self.close='29049.8'
2023-08-06 08:20:07,848:INFO:modifiedmom:main.py:145:handleKline:2218259: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec     open    close       pct
621  20230806   073000    073959  1691278799    29073  29063.3 -0.000334
622  20230806   074000    074959  1691279399  29063.3  29061.7 -0.000055
623  20230806   075000    075959  1691279999  29061.7  29057.7 -0.000138
624  20230806   080000    080959  1691280599  29057.7  29047.5 -0.000351
625  20230806   081000    081959  1691281199  29047.5  29049.8  0.000079
2023-08-06 08:20:07,848:INFO:modifiedmom:main.py:146:handleKline:2218259: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': True, 'isOpen': False, 'isClose': True, 'isTrig': False}


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

17471  20230806   075000    075959  1691279999  29061.7  29057.7
2023-08-06 08:00:02,132:INFO:pyemd2:main.py:127:handleKline:2217508: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}
127.0.0.1 - - [06/Aug/2023 08:10:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=12083 

self.closeSec=1691280599, self.tradeDate='20230806', self.openTime='080000', self.closeTime='080959', self.symbol='BTCUSDT', self.open='29057.7', self.close='29047.5'
2023-08-06 08:10:01,151:INFO:pyemd2:main.py:125:handleKline:2217508: self.closeSec=1691280599, self.tradeDate='20230806', self.openTime='080000', self.closeTime='080959',self.symbol='BTCUSDT',self.open='29057.7', self.close='29047.5'
2023-08-06 08:10:01,162:INFO:pyemd2:main.py:126:handleKline:2217508: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
17468  20230806   072000    072959  1691278199  29070.1    29073
17469  20230806   073000    073959  1691278799    29073  29063.3
17470  20230806   074000    074959  1691279399  29063.3  29061.7
17471  20230806   075000    075959  1691279999  29061.7  29057.7
17472  20230806   080000    080959  1691280599  29057.7  29047.5
2023-08-06 08:10:01,162:INFO:pyemd2:main.py:127:handleKline:2217508: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=12084 

self.closeSec=1691281199, self.tradeDate='20230806', self.openTime='081000', self.closeTime='081959', self.symbol='BTCUSDT', self.open='29047.5', self.close='29049.8'
127.0.0.1 - - [06/Aug/2023 08:20:04] "POST / HTTP/1.1" 200 -
2023-08-06 08:20:08,819:INFO:pyemd2:main.py:125:handleKline:2217508: self.closeSec=1691281199, self.tradeDate='20230806', self.openTime='081000', self.closeTime='081959',self.symbol='BTCUSDT',self.open='29047.5', self.close='29049.8'
2023-08-06 08:20:08,918:INFO:pyemd2:main.py:126:handleKline:2217508: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
17469  20230806   073000    073959  1691278799    29073  29063.3
17470  20230806   074000    074959  1691279399  29063.3  29061.7
17471  20230806   075000    075959  1691279999  29061.7  29057.7
17472  20230806   080000    080959  1691280599  29057.7  29047.5
17473  20230806   081000    081959  1691281199  29047.5  29049.8
2023-08-06 08:20:08,918:INFO:pyemd2:main.py:127:handleKline:2217508: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}


## /root/FIL/strategy/similarity/log.txt ----- -----

12143  20230806   075000    075959  1691279999  29061.7  29057.7
2023-08-06 08:00:02,117:INFO:testStrategy:main.py:103:handleKline:2217133: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': True, 'isOpenSell': False, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True, 'isCorr': False}

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=12083 

self.closeSec=1691280599, self.tradeDate='20230806', self.openTime='080000', self.closeTime='080959', self.symbol='BTCUSDT', self.open='29057.7', self.close='29047.5'
2023-08-06 08:10:01,136:INFO:testStrategy:main.py:101:handleKline:2217133: self.closeSec=1691280599, self.tradeDate='20230806', self.openTime='080000', self.closeTime='080959',self.symbol='BTCUSDT',self.open='29057.7', self.close='29047.5'
127.0.0.1 - - [06/Aug/2023 08:10:01] "POST / HTTP/1.1" 200 -
2023-08-06 08:10:01,154:INFO:testStrategy:main.py:102:handleKline:2217133: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
12140  20230806   072000    072959  1691278199  29070.1    29073
12141  20230806   073000    073959  1691278799    29073  29063.3
12142  20230806   074000    074959  1691279399  29063.3  29061.7
12143  20230806   075000    075959  1691279999  29061.7  29057.7
12144  20230806   080000    080959  1691280599  29057.7  29047.5
2023-08-06 08:10:01,154:INFO:testStrategy:main.py:103:handleKline:2217133: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': True, 'isOpenSell': False, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True, 'isCorr': False}

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=12084 

self.closeSec=1691281199, self.tradeDate='20230806', self.openTime='081000', self.closeTime='081959', self.symbol='BTCUSDT', self.open='29047.5', self.close='29049.8'
127.0.0.1 - - [06/Aug/2023 08:20:04] "POST / HTTP/1.1" 200 -
2023-08-06 08:20:08,621:INFO:testStrategy:main.py:101:handleKline:2217133: self.closeSec=1691281199, self.tradeDate='20230806', self.openTime='081000', self.closeTime='081959',self.symbol='BTCUSDT',self.open='29047.5', self.close='29049.8'
2023-08-06 08:20:08,810:INFO:testStrategy:main.py:102:handleKline:2217133: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
12141  20230806   073000    073959  1691278799    29073  29063.3
12142  20230806   074000    074959  1691279399  29063.3  29061.7
12143  20230806   075000    075959  1691279999  29061.7  29057.7
12144  20230806   080000    080959  1691280599  29057.7  29047.5
12145  20230806   081000    081959  1691281199  29047.5  29049.8
2023-08-06 08:20:08,810:INFO:testStrategy:main.py:103:handleKline:2217133: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': True, 'isOpenSell': False, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True, 'isCorr': False}


## /root/FIL/strategy/sr_min/log.txt ----- -----

--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=1, self.total=996015.990996, self.flagDict['side']='buy', self.tradeCount=1, self.count=24160
self.closeSec=1691281199, self.tradeDate='20230806', self.openTime='081500', self.closeTime='081959', self.symbol='BTCUSDT', self.open=29048.1, self.close=29049.8, self.high=29049.9, self.low=29045.5, self.vol=108.506, self.amt=3151698.0212 
127.0.0.1 - - [06/Aug/2023 08:20:01] "POST / HTTP/1.1" 200 -
2023-08-06 08:20:06,827:INFO:sr_min:main.py:172:handleKline:2219263: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5855  20230806   075500    075959  ...         0.0        0.0       0
5856  20230806   080000    080459  ...         0.0        0.0       0
5857  20230806   080500    080959  ...         0.0        0.0       0
5858  20230806   081000    081459  ...         0.0        0.0       0
5859  20230806   081500    081959  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-08-06 08:20:06,847:INFO:sr_min:main.py:175:handleKline:2219263: self.closeSec=1691281199, self.tradeDate='20230806', self.openTime='081500', self.closeTime='081959',self.symbol='BTCUSDT',self.open=29048.1, self.close=29049.8, self.high=29049.9, self.low=29045.5, self.vol=108.506, self.amt=3151698.0212, ukdf['pct'].iloc[-1]=6.2e-05 , ukdf['amount'].iloc[-1]=3151698.0212, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5859, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '37.141', 'enterprice': '26844', 'countrevence': '0', 'unrealprofit': '81925.6178', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '29049.8', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=1
127.0.0.1 - - [06/Aug/2023 08:25:00] "POST / HTTP/1.1" 200 -
--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=1, self.total=996015.990996, self.flagDict['side']='buy', self.tradeCount=1, self.count=24161
self.closeSec=1691281499, self.tradeDate='20230806', self.openTime='082000', self.closeTime='082459', self.symbol='BTCUSDT', self.open=29049.8, self.close=29051.9, self.high=29051.9, self.low=29049.8, self.vol=136.152, self.amt=3955357.2736 
2023-08-06 08:25:00,835:INFO:sr_min:main.py:172:handleKline:2219263: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5856  20230806   080000    080459  ...         0.0        0.0       0
5857  20230806   080500    080959  ...         0.0        0.0       0
5858  20230806   081000    081459  ...         0.0        0.0       0
5859  20230806   081500    081959  ...         0.0        0.0       0
5860  20230806   082000    082459  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-08-06 08:25:00,836:INFO:sr_min:main.py:175:handleKline:2219263: self.closeSec=1691281499, self.tradeDate='20230806', self.openTime='082000', self.closeTime='082459',self.symbol='BTCUSDT',self.open=29049.8, self.close=29051.9, self.high=29051.9, self.low=29049.8, self.vol=136.152, self.amt=3955357.2736, ukdf['pct'].iloc[-1]=7.2e-05 , ukdf['amount'].iloc[-1]=3955357.2736, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5860, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '37.141', 'enterprice': '26844', 'countrevence': '0', 'unrealprofit': '82003.6139', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '29051.9', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=1


## /root/FIL/strategy/s_rsrs/log.txt ----- -----

719  20230805   200000    235959  1691251199  ...    719  0.554096  1.233047     1.0
720  20230806   000000    035959  1691265599  ...    720  0.660057  1.694509     1.0

[5 rows x 15 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '54.775', 'enterprice': '29034.8', 'countrevence': '0', 'unrealprofit': '1205.05', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '29056.8', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'numpy.int64'>, curSign=1, self.sign=1
127.0.0.1 - - [06/Aug/2023 08:00:01] "POST / HTTP/1.1" 200 -
--handleKline--:  version='2.0.0', self.name='s_rsrs', self.symbol='BTCUSDT', interval='4h', intervalSec=14400, wid=25, thd=0.6, self.sign=1, self.total=1588790.78883, self.flagDict['side']='buy', self.tradeCount=17, self.count=503
self.closeSec=1691279999, self.tradeDate='20230806', self.openTime='040000', self.closeTime='075959', self.symbol='BTCUSDT', self.open=29056.9, self.close=29057.7, self.high=29084.3, self.low=29041.5, self.vol=6586.05, self.amt=191399858.2689 
2023-08-06 08:00:01,673:INFO:s_rsrs:main.py:141:handleKline:2218689: self.closeSec=1691279999, self.tradeDate='20230806', self.openTime='040000', self.closeTime='075959',self.symbol='BTCUSDT',self.open=29056.9, self.close=29057.7, self.high=29084.3, self.low=29041.5, self.vol=6586.05, self.amt=191399858.2689 
2023-08-06 08:00:01,688:INFO:s_rsrs:main.py:142:handleKline:2218689: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime  ...        vol           amt       pct
717  20230805   120000    155959  ...  11796.275  3.427467e+08 -0.001537
718  20230805   160000    195959  ...  10686.415  3.104955e+08  0.000093
719  20230805   200000    235959  ...  25947.755  7.529701e+08 -0.000282
720  20230806   000000    035959  ...  11614.747  3.373902e+08  0.000844
721  20230806   040000    075959  ...   6586.050  1.913999e+08  0.000028

[5 rows x 11 columns]
2023-08-06 08:00:02,440:INFO:s_rsrs:main.py:151:handleKline:2218689: df_s.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec  ...  index      beta    zscore  signal
717  20230805   120000    155959  1691222399  ...    717  0.636616  1.699703     1.0
718  20230805   160000    195959  1691236799  ...    718  0.581010  1.392646     1.0
719  20230805   200000    235959  1691251199  ...    719  0.554096  1.233047     1.0
720  20230806   000000    035959  1691265599  ...    720  0.660057  1.694509     1.0
721  20230806   040000    075959  1691279999  ...    721  0.826976  2.381697     1.0

[5 rows x 15 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '54.775', 'enterprice': '29034.8', 'countrevence': '0', 'unrealprofit': '1330.649802412', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '29059.09301328', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'numpy.int64'>, curSign=1, self.sign=1


