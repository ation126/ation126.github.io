# 20230810 08:26:02

## /root/FIL/strategy/amihud/log.txt ----- -----

--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=373746.4768026, self.flagDict['side']='sell', self.tradeCount=2, self.count=25312
self.closeSec=1691626799, self.tradeDate='20230810', self.openTime='081500', self.closeTime='081959', self.symbol='BTCUSDT', self.open=29579.2, self.close=29601.1, self.high=29602.4, self.low=29572.2, self.vol=878.996, self.amt=26008969.1099 
127.0.0.1 - - [10/Aug/2023 08:20:01] "POST / HTTP/1.1" 200 -
2023-08-10 08:20:06,279:INFO:amihud:main.py:172:handleKline:2219019: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5855  20230810   075500    075959  ...         0.0        0.0       0
5856  20230810   080000    080459  ...         0.0        0.0       0
5857  20230810   080500    080959  ...         0.0        0.0       0
5858  20230810   081000    081459  ...         0.0        0.0       0
5859  20230810   081500    081959  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-08-10 08:20:06,300:INFO:amihud:main.py:175:handleKline:2219019: self.closeSec=1691626799, self.tradeDate='20230810', self.openTime='081500', self.closeTime='081959',self.symbol='BTCUSDT',self.open=29579.2, self.close=29601.1, self.high=29602.4, self.low=29572.2, self.vol=878.996, self.amt=26008969.1099, ukdf['pct'].iloc[-1]=0.000852 , ukdf['amount'].iloc[-1]=26008969.1099, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5859, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '13.926', 'enterprice': '26864.9', 'countrevence': '0', 'unrealprofit': '-38104.3212', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '29601.1', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1
127.0.0.1 - - [10/Aug/2023 08:25:00] "POST / HTTP/1.1" 200 -
--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=373746.4768026, self.flagDict['side']='sell', self.tradeCount=2, self.count=25313
self.closeSec=1691627099, self.tradeDate='20230810', self.openTime='082000', self.closeTime='082459', self.symbol='BTCUSDT', self.open=29601.1, self.close=29605.2, self.high=29619.2, self.low=29600.7, self.vol=904.263, self.amt=26775772.3542 
2023-08-10 08:25:00,816:INFO:amihud:main.py:172:handleKline:2219019: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5856  20230810   080000    080459  ...         0.0        0.0       0
5857  20230810   080500    080959  ...         0.0        0.0       0
5858  20230810   081000    081459  ...         0.0        0.0       0
5859  20230810   081500    081959  ...         0.0        0.0       0
5860  20230810   082000    082459  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-08-10 08:25:00,816:INFO:amihud:main.py:175:handleKline:2219019: self.closeSec=1691627099, self.tradeDate='20230810', self.openTime='082000', self.closeTime='082459',self.symbol='BTCUSDT',self.open=29601.1, self.close=29605.2, self.high=29619.2, self.low=29600.7, self.vol=904.263, self.amt=26775772.3542, ukdf['pct'].iloc[-1]=0.000139 , ukdf['amount'].iloc[-1]=26775772.3542, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5860, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '13.926', 'enterprice': '26864.9', 'countrevence': '0', 'unrealprofit': '-38164.84668214086', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '29605.44622161', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1


## /root/FIL/strategy/factorcheck/log.txt ----- -----


self.closeSec=1691626799, self.tradeDate='20230810', self.openTime='081500', self.closeTime='081959', self.symbol='BTCUSDT', self.open=29579.2, self.close=29601.1, self.high=29602.4, self.low=29572.2 
127.0.0.1 - - [10/Aug/2023 08:20:01] "POST / HTTP/1.1" 200 -
2023-08-10 08:20:04,300:INFO:factorcheck2:main.py:126:handleKline:2218005: self.closeSec=1691626799, self.tradeDate='20230810', self.openTime='081500', self.closeTime='081959',self.symbol='BTCUSDT',self.open=29579.2, self.close=29601.1, self.high=29602.4, self.low=29572.2   
2023-08-10 08:20:05,450:INFO:factorcheck2:main.py:127:handleKline:2218005: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime    closeSec  ...      low       pct  index  idx
1535  20230810   075500    075959  1691625599  ...  29548.5 -0.000341   1535    5
1536  20230810   080000    080459  1691625899  ...  29555.5 -0.000264   1536    0
1537  20230810   080500    080959  1691626199  ...  29563.5  0.000666   1537    1
1538  20230810   081000    081459  1691626499  ...  29575.1 -0.000297   1538    2
1539  20230810   081500    081959  1691626799  ...  29572.2  0.000852   1539    3

[5 rows x 11 columns]
2023-08-10 08:20:05,450:INFO:factorcheck2:main.py:128:handleKline:2218005: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=267, self.factor=0.5344965260513131, self.count=25315 

self.closeSec=1691627099, self.tradeDate='20230810', self.openTime='082000', self.closeTime='082459', self.symbol='BTCUSDT', self.open=29601.1, self.close=29605.2, self.high=29619.2, self.low=29600.7 
127.0.0.1 - - [10/Aug/2023 08:25:00] "POST / HTTP/1.1" 200 -
2023-08-10 08:25:00,768:INFO:factorcheck2:main.py:126:handleKline:2218005: self.closeSec=1691627099, self.tradeDate='20230810', self.openTime='082000', self.closeTime='082459',self.symbol='BTCUSDT',self.open=29601.1, self.close=29605.2, self.high=29619.2, self.low=29600.7   
2023-08-10 08:25:00,782:INFO:factorcheck2:main.py:127:handleKline:2218005: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime    closeSec  ...      low       pct  index  idx
1536  20230810   080000    080459  1691625899  ...  29555.5 -0.000264   1536    0
1537  20230810   080500    080959  1691626199  ...  29563.5  0.000666   1537    1
1538  20230810   081000    081459  1691626499  ...  29575.1 -0.000297   1538    2
1539  20230810   081500    081959  1691626799  ...  29572.2  0.000852   1539    3
1540  20230810   082000    082459  1691627099  ...  29600.7  0.000139   1540    4

[5 rows x 11 columns]
2023-08-10 08:25:00,782:INFO:factorcheck2:main.py:128:handleKline:2218005: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}


## /root/FIL/strategy/logic/log.txt ----- -----

2023-08-10 08:00:17,586:DEBUG:logic:main.py:463:getModel:2218526: df_s.iloc[-5:,:] :
          date closeTime     open  ...    alpha58   alpha67   alpha72
5770  20230810    052959  29493.6  ...  52.083333  0.492106  0.723156
5771  20230810    055959  29519.7  ...  51.666667  0.491182  0.728638
5772  20230810    062959  29515.4  ...  51.666667  0.504219  0.728642
5773  20230810    065959  29575.8  ...  52.083333  0.508411  0.726979
5774  20230810    072959  29595.3  ...  52.083333  0.511130  0.724352

[5 rows x 33 columns]
0.5249537892791127
acc is : 0.5249537892791127
2023-08-10 08:00:17,656:INFO:logic:main.py:468:getModel:2218526: df_pred.iloc[-5:,:] :
     pred    prob_0    prob_1  actual  ...       nav  sign  cost_        bm
536     0  0.512128  0.487872       0  ...  0.960267  -1.0    0.0  1.007541
537     0  0.504210  0.495790       1  ...  0.958302  -1.0    0.0  1.009603
538     0  0.531864  0.468136       1  ...  0.957664  -1.0    0.0  1.010275
539     0  0.515587  0.484413       1  ...  0.957253  -1.0    0.0  1.010709
540     0  0.513226  0.486774       0  ...  0.958394  -1.0    0.0  1.009504

[5 rows x 10 columns]
2023-08-10 08:00:17,668:INFO:logic:main.py:478:getModel:2218526: df_panel.iloc[-5:,:] :
    pred    prob_0    prob_1  actual  ...       nav  sign  cost_        bm
45     0  0.512284  0.487716       0  ...  0.960267  -1.0    0.0  1.007871
46     0  0.504219  0.495781       1  ...  0.958302  -1.0    0.0  1.009861
47     0  0.531656  0.468344       1  ...  0.957664  -1.0    0.0  1.010209
48     0  0.515485  0.484515       1  ...  0.957253  -1.0    0.0  1.010709
49     0  0.513226  0.486774       0  ...  0.958394  -1.0    0.0  1.009504

[5 rows x 10 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '24.049', 'enterprice': '29479.7', 'countrevence': '0', 'unrealprofit': '-2284.655', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '29574.7', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}


## /root/FIL/strategy/modifiedmom/log.txt ----- -----

623  20230810   075000    075959  1691625599    29580  29572.8 -0.000243
2023-08-10 08:00:02,145:INFO:modifiedmom:main.py:146:handleKline:2218259: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': True, 'isOpen': False, 'isClose': True, 'isTrig': False}

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=12656 

self.closeSec=1691626199, self.tradeDate='20230810', self.openTime='080000', self.closeTime='080959', self.symbol='BTCUSDT', self.open='29572.9', self.close='29584.7'
2023-08-10 08:10:01,118:INFO:modifiedmom:main.py:144:handleKline:2218259: self.closeSec=1691626199, self.tradeDate='20230810', self.openTime='080000', self.closeTime='080959',self.symbol='BTCUSDT',self.open='29572.9', self.close='29584.7'
127.0.0.1 - - [10/Aug/2023 08:10:01] "POST / HTTP/1.1" 200 -
2023-08-10 08:10:01,125:INFO:modifiedmom:main.py:145:handleKline:2218259: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec     open    close       pct
620  20230810   072000    072959  1691623799  29604.5  29608.1  0.000125
621  20230810   073000    073959  1691624399  29608.1  29602.3 -0.000196
622  20230810   074000    074959  1691624999  29602.2    29580 -0.000753
623  20230810   075000    075959  1691625599    29580  29572.8 -0.000243
624  20230810   080000    080959  1691626199  29572.9  29584.7  0.000402
2023-08-10 08:10:01,125:INFO:modifiedmom:main.py:146:handleKline:2218259: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': True, 'isOpen': False, 'isClose': True, 'isTrig': False}

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=12657 

self.closeSec=1691626799, self.tradeDate='20230810', self.openTime='081000', self.closeTime='081959', self.symbol='BTCUSDT', self.open='29584.7', self.close='29601.1'
127.0.0.1 - - [10/Aug/2023 08:20:04] "POST / HTTP/1.1" 200 -
2023-08-10 08:20:06,751:INFO:modifiedmom:main.py:144:handleKline:2218259: self.closeSec=1691626799, self.tradeDate='20230810', self.openTime='081000', self.closeTime='081959',self.symbol='BTCUSDT',self.open='29584.7', self.close='29601.1'
2023-08-10 08:20:07,370:INFO:modifiedmom:main.py:145:handleKline:2218259: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec     open    close       pct
621  20230810   073000    073959  1691624399  29608.1  29602.3 -0.000196
622  20230810   074000    074959  1691624999  29602.2    29580 -0.000753
623  20230810   075000    075959  1691625599    29580  29572.8 -0.000243
624  20230810   080000    080959  1691626199  29572.9  29584.7  0.000402
625  20230810   081000    081959  1691626799  29584.7  29601.1  0.000554
2023-08-10 08:20:07,370:INFO:modifiedmom:main.py:146:handleKline:2218259: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': True, 'isOpen': False, 'isClose': True, 'isTrig': False}


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

17471  20230810   075000    075959  1691625599    29580  29572.8
2023-08-10 08:00:02,147:INFO:pyemd2:main.py:127:handleKline:2217508: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=12659 

self.closeSec=1691626199, self.tradeDate='20230810', self.openTime='080000', self.closeTime='080959', self.symbol='BTCUSDT', self.open='29572.9', self.close='29584.7'
2023-08-10 08:10:01,127:INFO:pyemd2:main.py:125:handleKline:2217508: self.closeSec=1691626199, self.tradeDate='20230810', self.openTime='080000', self.closeTime='080959',self.symbol='BTCUSDT',self.open='29572.9', self.close='29584.7'
127.0.0.1 - - [10/Aug/2023 08:10:01] "POST / HTTP/1.1" 200 -
2023-08-10 08:10:01,135:INFO:pyemd2:main.py:126:handleKline:2217508: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
17468  20230810   072000    072959  1691623799  29604.5  29608.1
17469  20230810   073000    073959  1691624399  29608.1  29602.3
17470  20230810   074000    074959  1691624999  29602.2    29580
17471  20230810   075000    075959  1691625599    29580  29572.8
17472  20230810   080000    080959  1691626199  29572.9  29584.7
2023-08-10 08:10:01,135:INFO:pyemd2:main.py:127:handleKline:2217508: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=12660 

self.closeSec=1691626799, self.tradeDate='20230810', self.openTime='081000', self.closeTime='081959', self.symbol='BTCUSDT', self.open='29584.7', self.close='29601.1'
127.0.0.1 - - [10/Aug/2023 08:20:04] "POST / HTTP/1.1" 200 -
2023-08-10 08:20:08,343:INFO:pyemd2:main.py:125:handleKline:2217508: self.closeSec=1691626799, self.tradeDate='20230810', self.openTime='081000', self.closeTime='081959',self.symbol='BTCUSDT',self.open='29584.7', self.close='29601.1'
2023-08-10 08:20:08,433:INFO:pyemd2:main.py:126:handleKline:2217508: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
17469  20230810   073000    073959  1691624399  29608.1  29602.3
17470  20230810   074000    074959  1691624999  29602.2    29580
17471  20230810   075000    075959  1691625599    29580  29572.8
17472  20230810   080000    080959  1691626199  29572.9  29584.7
17473  20230810   081000    081959  1691626799  29584.7  29601.1
2023-08-10 08:20:08,434:INFO:pyemd2:main.py:127:handleKline:2217508: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}


## /root/FIL/strategy/similarity/log.txt ----- -----

12143  20230810   075000    075959  1691625599    29580  29572.8
2023-08-10 08:00:02,152:INFO:testStrategy:main.py:103:handleKline:2217133: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': True, 'isOpenSell': False, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True, 'isCorr': False}
127.0.0.1 - - [10/Aug/2023 08:10:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=12659 

self.closeSec=1691626199, self.tradeDate='20230810', self.openTime='080000', self.closeTime='080959', self.symbol='BTCUSDT', self.open='29572.9', self.close='29584.7'
2023-08-10 08:10:01,120:INFO:testStrategy:main.py:101:handleKline:2217133: self.closeSec=1691626199, self.tradeDate='20230810', self.openTime='080000', self.closeTime='080959',self.symbol='BTCUSDT',self.open='29572.9', self.close='29584.7'
2023-08-10 08:10:01,132:INFO:testStrategy:main.py:102:handleKline:2217133: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
12140  20230810   072000    072959  1691623799  29604.5  29608.1
12141  20230810   073000    073959  1691624399  29608.1  29602.3
12142  20230810   074000    074959  1691624999  29602.2    29580
12143  20230810   075000    075959  1691625599    29580  29572.8
12144  20230810   080000    080959  1691626199  29572.9  29584.7
2023-08-10 08:10:01,132:INFO:testStrategy:main.py:103:handleKline:2217133: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': True, 'isOpenSell': False, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True, 'isCorr': False}

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=12660 

self.closeSec=1691626799, self.tradeDate='20230810', self.openTime='081000', self.closeTime='081959', self.symbol='BTCUSDT', self.open='29584.7', self.close='29601.1'
127.0.0.1 - - [10/Aug/2023 08:20:04] "POST / HTTP/1.1" 200 -
2023-08-10 08:20:08,180:INFO:testStrategy:main.py:101:handleKline:2217133: self.closeSec=1691626799, self.tradeDate='20230810', self.openTime='081000', self.closeTime='081959',self.symbol='BTCUSDT',self.open='29584.7', self.close='29601.1'
2023-08-10 08:20:08,331:INFO:testStrategy:main.py:102:handleKline:2217133: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
12141  20230810   073000    073959  1691624399  29608.1  29602.3
12142  20230810   074000    074959  1691624999  29602.2    29580
12143  20230810   075000    075959  1691625599    29580  29572.8
12144  20230810   080000    080959  1691626199  29572.9  29584.7
12145  20230810   081000    081959  1691626799  29584.7  29601.1
2023-08-10 08:20:08,331:INFO:testStrategy:main.py:103:handleKline:2217133: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': True, 'isOpenSell': False, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True, 'isCorr': False}


## /root/FIL/strategy/sr_min/log.txt ----- -----

--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=1, self.total=996015.990996, self.flagDict['side']='buy', self.tradeCount=1, self.count=25312
self.closeSec=1691626799, self.tradeDate='20230810', self.openTime='081500', self.closeTime='081959', self.symbol='BTCUSDT', self.open=29579.2, self.close=29601.1, self.high=29602.4, self.low=29572.2, self.vol=878.996, self.amt=26008969.1099 
127.0.0.1 - - [10/Aug/2023 08:20:01] "POST / HTTP/1.1" 200 -
2023-08-10 08:20:06,290:INFO:sr_min:main.py:172:handleKline:2219263: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5855  20230810   075500    075959  ...         0.0        0.0       0
5856  20230810   080000    080459  ...         0.0        0.0       0
5857  20230810   080500    080959  ...         0.0        0.0       0
5858  20230810   081000    081459  ...         0.0        0.0       0
5859  20230810   081500    081959  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-08-10 08:20:06,310:INFO:sr_min:main.py:175:handleKline:2219263: self.closeSec=1691626799, self.tradeDate='20230810', self.openTime='081500', self.closeTime='081959',self.symbol='BTCUSDT',self.open=29579.2, self.close=29601.1, self.high=29602.4, self.low=29572.2, self.vol=878.996, self.amt=26008969.1099, ukdf['pct'].iloc[-1]=0.000852 , ukdf['amount'].iloc[-1]=26008969.1099, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5859, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '37.141', 'enterprice': '26844', 'countrevence': '0', 'unrealprofit': '102401.4511', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '29601.1', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=1
--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=1, self.total=996015.990996, self.flagDict['side']='buy', self.tradeCount=1, self.count=25313
self.closeSec=1691627099, self.tradeDate='20230810', self.openTime='082000', self.closeTime='082459', self.symbol='BTCUSDT', self.open=29601.1, self.close=29605.2, self.high=29619.2, self.low=29600.7, self.vol=904.263, self.amt=26775772.3542 
127.0.0.1 - - [10/Aug/2023 08:25:00] "POST / HTTP/1.1" 200 -
2023-08-10 08:25:00,802:INFO:sr_min:main.py:172:handleKline:2219263: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5856  20230810   080000    080459  ...         0.0        0.0       0
5857  20230810   080500    080959  ...         0.0        0.0       0
5858  20230810   081000    081459  ...         0.0        0.0       0
5859  20230810   081500    081959  ...         0.0        0.0       0
5860  20230810   082000    082459  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-08-10 08:25:00,803:INFO:sr_min:main.py:175:handleKline:2219263: self.closeSec=1691627099, self.tradeDate='20230810', self.openTime='082000', self.closeTime='082459',self.symbol='BTCUSDT',self.open=29601.1, self.close=29605.2, self.high=29619.2, self.low=29600.7, self.vol=904.263, self.amt=26775772.3542, ukdf['pct'].iloc[-1]=0.000139 , ukdf['amount'].iloc[-1]=26775772.3542, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5860, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '37.141', 'enterprice': '26844', 'countrevence': '0', 'unrealprofit': '102562.87411681701', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '29605.44622161', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=1


## /root/FIL/strategy/s_rsrs/log.txt ----- -----

719  20230809   200000    235959  1691596799  ...    719  1.205164  2.821489     1.0
720  20230810   000000    035959  1691611199  ...    720  1.211631  2.705132     1.0

[5 rows x 15 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '51.457', 'enterprice': '29884.4', 'countrevence': '0', 'unrealprofit': '-24406.0551', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '29410.1', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'numpy.int64'>, curSign=1, self.sign=1
--handleKline--:  version='2.0.0', self.name='s_rsrs', self.symbol='BTCUSDT', interval='4h', intervalSec=14400, wid=25, thd=0.6, self.sign=1, self.total=1536223.8092292, self.flagDict['side']='buy', self.tradeCount=19, self.count=527
self.closeSec=1691625599, self.tradeDate='20230810', self.openTime='040000', self.closeTime='075959', self.symbol='BTCUSDT', self.open=29404.3, self.close=29572.8, self.high=29619.7, self.low=29362.0, self.vol=37603.98, self.amt=1109495783.6495 
127.0.0.1 - - [10/Aug/2023 08:00:01] "POST / HTTP/1.1" 200 -
2023-08-10 08:00:01,718:INFO:s_rsrs:main.py:141:handleKline:2218689: self.closeSec=1691625599, self.tradeDate='20230810', self.openTime='040000', self.closeTime='075959',self.symbol='BTCUSDT',self.open=29404.3, self.close=29572.8, self.high=29619.7, self.low=29362.0, self.vol=37603.98, self.amt=1109495783.6495 
2023-08-10 08:00:01,730:INFO:s_rsrs:main.py:142:handleKline:2218689: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime  ...         vol           amt       pct
717  20230809   120000    155959  ...   33679.663  1.001345e+09  0.003295
718  20230809   160000    195959  ...   39109.948  1.165713e+09  0.002322
719  20230809   200000    235959  ...  112574.075  3.364375e+09 -0.004274
720  20230810   000000    035959  ...   94943.349  2.804365e+09 -0.011604
721  20230810   040000    075959  ...   37603.980  1.109496e+09  0.005734

[5 rows x 11 columns]
2023-08-10 08:00:02,461:INFO:s_rsrs:main.py:151:handleKline:2218689: df_s.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec  ...  index      beta    zscore  signal
717  20230809   120000    155959  1691567999  ...    717  1.152400  2.924316     1.0
718  20230809   160000    195959  1691582399  ...    718  1.097325  2.599960     1.0
719  20230809   200000    235959  1691596799  ...    719  1.205164  2.821489     1.0
720  20230810   000000    035959  1691611199  ...    720  1.211631  2.705132     1.0
721  20230810   040000    075959  1691625599  ...    721  1.191976  2.528315     1.0

[5 rows x 15 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '51.457', 'enterprice': '29884.4', 'countrevence': '0', 'unrealprofit': '-16028.8555', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '29572.9', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'numpy.int64'>, curSign=1, self.sign=1


