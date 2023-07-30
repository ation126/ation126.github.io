# 20230730 08:26:01

## /root/FIL/strategy/amihud/log.txt ----- -----

--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=373746.4768026, self.flagDict['side']='sell', self.tradeCount=2, self.count=22144
self.closeSec=1690676399, self.tradeDate='20230730', self.openTime='081500', self.closeTime='081959', self.symbol='BTCUSDT', self.open=29324.0, self.close=29341.6, self.high=29341.6, self.low=29320.0, self.vol=362.64, self.amt=10636007.5936 
127.0.0.1 - - [30/Jul/2023 08:20:01] "POST / HTTP/1.1" 200 -
2023-07-30 08:20:06,053:INFO:amihud:main.py:172:handleKline:2219019: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5855  20230730   075500    075959  ...         0.0        0.0       0
5856  20230730   080000    080459  ...         0.0        0.0       0
5857  20230730   080500    080959  ...         0.0        0.0       0
5858  20230730   081000    081459  ...         0.0        0.0       0
5859  20230730   081500    081959  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-07-30 08:20:06,082:INFO:amihud:main.py:175:handleKline:2219019: self.closeSec=1690676399, self.tradeDate='20230730', self.openTime='081500', self.closeTime='081959',self.symbol='BTCUSDT',self.open=29324.0, self.close=29341.6, self.high=29341.6, self.low=29320.0, self.vol=362.64, self.amt=10636007.5936, ukdf['pct'].iloc[-1]=0.0006 , ukdf['amount'].iloc[-1]=10636007.5936, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5859, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '13.926', 'enterprice': '26864.9', 'countrevence': '0', 'unrealprofit': '-34489.1316', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '29341.5', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1
--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=373746.4768026, self.flagDict['side']='sell', self.tradeCount=2, self.count=22145
self.closeSec=1690676699, self.tradeDate='20230730', self.openTime='082000', self.closeTime='082459', self.symbol='BTCUSDT', self.open=29341.6, self.close=29319.9, self.high=29345.9, self.low=29319.0, self.vol=405.179, self.amt=11884353.0835 
127.0.0.1 - - [30/Jul/2023 08:25:00] "POST / HTTP/1.1" 200 -
2023-07-30 08:25:00,802:INFO:amihud:main.py:172:handleKline:2219019: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5856  20230730   080000    080459  ...         0.0        0.0       0
5857  20230730   080500    080959  ...         0.0        0.0       0
5858  20230730   081000    081459  ...         0.0        0.0       0
5859  20230730   081500    081959  ...         0.0        0.0       0
5860  20230730   082000    082459  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-07-30 08:25:00,802:INFO:amihud:main.py:175:handleKline:2219019: self.closeSec=1690676699, self.tradeDate='20230730', self.openTime='082000', self.closeTime='082459',self.symbol='BTCUSDT',self.open=29341.6, self.close=29319.9, self.high=29345.9, self.low=29319.0, self.vol=405.179, self.amt=11884353.0835, ukdf['pct'].iloc[-1]=-0.00074 , ukdf['amount'].iloc[-1]=11884353.0835, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5860, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '13.926', 'enterprice': '26864.9', 'countrevence': '0', 'unrealprofit': '-34190.43127018728', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '29320.05088828', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1


## /root/FIL/strategy/factorcheck/log.txt ----- -----


self.closeSec=1690676399, self.tradeDate='20230730', self.openTime='081500', self.closeTime='081959', self.symbol='BTCUSDT', self.open=29324.0, self.close=29341.6, self.high=29341.6, self.low=29320.0 
127.0.0.1 - - [30/Jul/2023 08:20:01] "POST / HTTP/1.1" 200 -
2023-07-30 08:20:04,182:INFO:factorcheck2:main.py:126:handleKline:2218005: self.closeSec=1690676399, self.tradeDate='20230730', self.openTime='081500', self.closeTime='081959',self.symbol='BTCUSDT',self.open=29324.0, self.close=29341.6, self.high=29341.6, self.low=29320.0   
2023-07-30 08:20:05,472:INFO:factorcheck2:main.py:127:handleKline:2218005: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime    closeSec  ...      low       pct  index  idx
1535  20230730   075500    075959  1690675199  ...  29339.1 -0.000269   1535    5
1536  20230730   080000    080459  1690675499  ...  29336.7 -0.000068   1536    0
1537  20230730   080500    080959  1690675799  ...  29333.0 -0.000092   1537    1
1538  20230730   081000    081459  1690676099  ...  29324.0 -0.000358   1538    2
1539  20230730   081500    081959  1690676399  ...  29320.0  0.000600   1539    3

[5 rows x 11 columns]
2023-07-30 08:20:05,472:INFO:factorcheck2:main.py:128:handleKline:2218005: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': True, 'isOpenSell': False, 'isCloseBuy': False, 'isCloseSell': False, 'isOpen': True, 'isClose': False, 'isTrig': True}

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=9, self.factor=0.5517207036471482, self.count=22147 

self.closeSec=1690676699, self.tradeDate='20230730', self.openTime='082000', self.closeTime='082459', self.symbol='BTCUSDT', self.open=29341.6, self.close=29319.9, self.high=29345.9, self.low=29319.0 
127.0.0.1 - - [30/Jul/2023 08:25:00] "POST / HTTP/1.1" 200 -
2023-07-30 08:25:00,765:INFO:factorcheck2:main.py:126:handleKline:2218005: self.closeSec=1690676699, self.tradeDate='20230730', self.openTime='082000', self.closeTime='082459',self.symbol='BTCUSDT',self.open=29341.6, self.close=29319.9, self.high=29345.9, self.low=29319.0   
2023-07-30 08:25:00,790:INFO:factorcheck2:main.py:127:handleKline:2218005: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime    closeSec  ...      low       pct  index  idx
1536  20230730   080000    080459  1690675499  ...  29336.7 -0.000068   1536    0
1537  20230730   080500    080959  1690675799  ...  29333.0 -0.000092   1537    1
1538  20230730   081000    081459  1690676099  ...  29324.0 -0.000358   1538    2
1539  20230730   081500    081959  1690676399  ...  29320.0  0.000600   1539    3
1540  20230730   082000    082459  1690676699  ...  29319.0 -0.000740   1540    4

[5 rows x 11 columns]
2023-07-30 08:25:00,790:INFO:factorcheck2:main.py:128:handleKline:2218005: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': True, 'isOpenSell': False, 'isCloseBuy': False, 'isCloseSell': False, 'isOpen': True, 'isClose': False, 'isTrig': True}


## /root/FIL/strategy/logic/log.txt ----- -----

2023-07-30 08:00:17,775:DEBUG:logic:main.py:463:getModel:2218526: df_s.iloc[-5:,:] :
          date closeTime     open  ...    alpha58   alpha67   alpha72
5770  20230730    052959  29338.8  ...  48.333333  0.524786  0.542772
5771  20230730    055959  29350.4  ...  47.916667  0.518916  0.530985
5772  20230730    062959  29339.3  ...  48.333333  0.519112  0.519817
5773  20230730    065959  29339.5  ...  48.333333  0.519910  0.508728
5774  20230730    072959  29341.2  ...  47.916667  0.519910  0.498379

[5 rows x 33 columns]
0.5711645101663586
acc is : 0.5711645101663586
2023-07-30 08:00:17,836:INFO:logic:main.py:468:getModel:2218526: df_pred.iloc[-5:,:] :
     pred    prob_0    prob_1  actual  ...       nav  sign  cost_        bm
536     0  0.506591  0.493409       0  ...  0.921045   1.0    0.0  0.987619
537     1  0.499831  0.500169       0  ...  0.921058   1.0    0.0  0.987633
538     0  0.502280  0.497720       1  ...  0.921108   1.0    0.0  0.987686
539     0  0.500225  0.499775       0  ...  0.921108   1.0    0.0  0.987686
540     0  0.502804  0.497196       0  ...  0.921042   1.0    0.0  0.987616

[5 rows x 10 columns]
2023-07-30 08:00:17,848:INFO:logic:main.py:478:getModel:2218526: df_panel.iloc[-5:,:] :
    pred    prob_0    prob_1  actual  ...       nav  sign  cost_        bm
45     0  0.506391  0.493609       0  ...  0.908634   1.0    0.0  0.981405
46     0  0.500131  0.499869       0  ...  0.908646   1.0    0.0  0.981615
47     0  0.502391  0.497609       1  ...  0.908696   1.0    0.0  0.988319
48     0  0.500225  0.499775       0  ...  0.921108   1.0    0.0  0.987686
49     0  0.502804  0.497196       0  ...  0.921042   1.0    0.0  0.987616

[5 rows x 10 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '23.818', 'enterprice': '29478', 'countrevence': '0', 'unrealprofit': '-3274.58379149362', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '29340.51642491', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}


## /root/FIL/strategy/modifiedmom/log.txt ----- -----

623  20230730   075000    075959  1690675199    29344  29339.1 -0.000167
2023-07-30 08:00:02,142:INFO:modifiedmom:main.py:146:handleKline:2218259: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': True, 'isOpen': False, 'isClose': True, 'isTrig': False}
127.0.0.1 - - [30/Jul/2023 08:10:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=11072 

self.closeSec=1690675799, self.tradeDate='20230730', self.openTime='080000', self.closeTime='080959', self.symbol='BTCUSDT', self.open='29339.1', self.close='29334.5'
2023-07-30 08:10:01,159:INFO:modifiedmom:main.py:144:handleKline:2218259: self.closeSec=1690675799, self.tradeDate='20230730', self.openTime='080000', self.closeTime='080959',self.symbol='BTCUSDT',self.open='29339.1', self.close='29334.5'
2023-07-30 08:10:01,177:INFO:modifiedmom:main.py:145:handleKline:2218259: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec     open    close       pct
620  20230730   072000    072959  1690673399  29342.8  29341.2 -0.000055
621  20230730   073000    073959  1690673999  29341.2    29348  0.000232
622  20230730   074000    074959  1690674599  29347.9    29344 -0.000136
623  20230730   075000    075959  1690675199    29344  29339.1 -0.000167
624  20230730   080000    080959  1690675799  29339.1  29334.5 -0.000157
2023-07-30 08:10:01,177:INFO:modifiedmom:main.py:146:handleKline:2218259: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': True, 'isOpen': False, 'isClose': True, 'isTrig': False}

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=11073 

self.closeSec=1690676399, self.tradeDate='20230730', self.openTime='081000', self.closeTime='081959', self.symbol='BTCUSDT', self.open='29334.5', self.close='29341.5'
127.0.0.1 - - [30/Jul/2023 08:20:04] "POST / HTTP/1.1" 200 -
2023-07-30 08:20:06,322:INFO:modifiedmom:main.py:144:handleKline:2218259: self.closeSec=1690676399, self.tradeDate='20230730', self.openTime='081000', self.closeTime='081959',self.symbol='BTCUSDT',self.open='29334.5', self.close='29341.5'
2023-07-30 08:20:06,842:INFO:modifiedmom:main.py:145:handleKline:2218259: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec     open    close       pct
621  20230730   073000    073959  1690673999  29341.2    29348  0.000232
622  20230730   074000    074959  1690674599  29347.9    29344 -0.000136
623  20230730   075000    075959  1690675199    29344  29339.1 -0.000167
624  20230730   080000    080959  1690675799  29339.1  29334.5 -0.000157
625  20230730   081000    081959  1690676399  29334.5  29341.5  0.000239
2023-07-30 08:20:06,842:INFO:modifiedmom:main.py:146:handleKline:2218259: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': True, 'isOpen': False, 'isClose': True, 'isTrig': False}


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

17471  20230730   075000    075959  1690675199    29344  29339.1
2023-07-30 08:00:02,145:INFO:pyemd2:main.py:127:handleKline:2217508: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=11075 

self.closeSec=1690675799, self.tradeDate='20230730', self.openTime='080000', self.closeTime='080959', self.symbol='BTCUSDT', self.open='29339.1', self.close='29334.5'
2023-07-30 08:10:01,170:INFO:pyemd2:main.py:125:handleKline:2217508: self.closeSec=1690675799, self.tradeDate='20230730', self.openTime='080000', self.closeTime='080959',self.symbol='BTCUSDT',self.open='29339.1', self.close='29334.5'
2023-07-30 08:10:01,177:INFO:pyemd2:main.py:126:handleKline:2217508: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
17468  20230730   072000    072959  1690673399  29342.8  29341.2
17469  20230730   073000    073959  1690673999  29341.2    29348
17470  20230730   074000    074959  1690674599  29347.9    29344
17471  20230730   075000    075959  1690675199    29344  29339.1
17472  20230730   080000    080959  1690675799  29339.1  29334.5
2023-07-30 08:10:01,177:INFO:pyemd2:main.py:127:handleKline:2217508: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}
127.0.0.1 - - [30/Jul/2023 08:10:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=11076 

self.closeSec=1690676399, self.tradeDate='20230730', self.openTime='081000', self.closeTime='081959', self.symbol='BTCUSDT', self.open='29334.5', self.close='29341.5'
127.0.0.1 - - [30/Jul/2023 08:20:04] "POST / HTTP/1.1" 200 -
2023-07-30 08:20:07,776:INFO:pyemd2:main.py:125:handleKline:2217508: self.closeSec=1690676399, self.tradeDate='20230730', self.openTime='081000', self.closeTime='081959',self.symbol='BTCUSDT',self.open='29334.5', self.close='29341.5'
2023-07-30 08:20:07,865:INFO:pyemd2:main.py:126:handleKline:2217508: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
17469  20230730   073000    073959  1690673999  29341.2    29348
17470  20230730   074000    074959  1690674599  29347.9    29344
17471  20230730   075000    075959  1690675199    29344  29339.1
17472  20230730   080000    080959  1690675799  29339.1  29334.5
17473  20230730   081000    081959  1690676399  29334.5  29341.5
2023-07-30 08:20:07,865:INFO:pyemd2:main.py:127:handleKline:2217508: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}


## /root/FIL/strategy/similarity/log.txt ----- -----

12143  20230730   075000    075959  1690675199    29344  29339.1
2023-07-30 08:00:02,167:INFO:testStrategy:main.py:103:handleKline:2217133: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': True, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True, 'isCorr': False}
127.0.0.1 - - [30/Jul/2023 08:10:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=11075 

self.closeSec=1690675799, self.tradeDate='20230730', self.openTime='080000', self.closeTime='080959', self.symbol='BTCUSDT', self.open='29339.1', self.close='29334.5'
2023-07-30 08:10:01,159:INFO:testStrategy:main.py:101:handleKline:2217133: self.closeSec=1690675799, self.tradeDate='20230730', self.openTime='080000', self.closeTime='080959',self.symbol='BTCUSDT',self.open='29339.1', self.close='29334.5'
2023-07-30 08:10:01,165:INFO:testStrategy:main.py:102:handleKline:2217133: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
12140  20230730   072000    072959  1690673399  29342.8  29341.2
12141  20230730   073000    073959  1690673999  29341.2    29348
12142  20230730   074000    074959  1690674599  29347.9    29344
12143  20230730   075000    075959  1690675199    29344  29339.1
12144  20230730   080000    080959  1690675799  29339.1  29334.5
2023-07-30 08:10:01,166:INFO:testStrategy:main.py:103:handleKline:2217133: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': True, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True, 'isCorr': False}

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=11076 

self.closeSec=1690676399, self.tradeDate='20230730', self.openTime='081000', self.closeTime='081959', self.symbol='BTCUSDT', self.open='29334.5', self.close='29341.5'
127.0.0.1 - - [30/Jul/2023 08:20:04] "POST / HTTP/1.1" 200 -
2023-07-30 08:20:07,625:INFO:testStrategy:main.py:101:handleKline:2217133: self.closeSec=1690676399, self.tradeDate='20230730', self.openTime='081000', self.closeTime='081959',self.symbol='BTCUSDT',self.open='29334.5', self.close='29341.5'
2023-07-30 08:20:07,784:INFO:testStrategy:main.py:102:handleKline:2217133: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
12141  20230730   073000    073959  1690673999  29341.2    29348
12142  20230730   074000    074959  1690674599  29347.9    29344
12143  20230730   075000    075959  1690675199    29344  29339.1
12144  20230730   080000    080959  1690675799  29339.1  29334.5
12145  20230730   081000    081959  1690676399  29334.5  29341.5
2023-07-30 08:20:07,784:INFO:testStrategy:main.py:103:handleKline:2217133: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': True, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True, 'isCorr': False}


## /root/FIL/strategy/sr_min/log.txt ----- -----

--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=1, self.total=996015.990996, self.flagDict['side']='buy', self.tradeCount=1, self.count=22144
self.closeSec=1690676399, self.tradeDate='20230730', self.openTime='081500', self.closeTime='081959', self.symbol='BTCUSDT', self.open=29324.0, self.close=29341.6, self.high=29341.6, self.low=29320.0, self.vol=362.64, self.amt=10636007.5936 
127.0.0.1 - - [30/Jul/2023 08:20:01] "POST / HTTP/1.1" 200 -
2023-07-30 08:20:06,082:INFO:sr_min:main.py:172:handleKline:2219263: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5855  20230730   075500    075959  ...         0.0        0.0       0
5856  20230730   080000    080459  ...         0.0        0.0       0
5857  20230730   080500    080959  ...         0.0        0.0       0
5858  20230730   081000    081459  ...         0.0        0.0       0
5859  20230730   081500    081959  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-07-30 08:20:06,093:INFO:sr_min:main.py:175:handleKline:2219263: self.closeSec=1690676399, self.tradeDate='20230730', self.openTime='081500', self.closeTime='081959',self.symbol='BTCUSDT',self.open=29324.0, self.close=29341.6, self.high=29341.6, self.low=29320.0, self.vol=362.64, self.amt=10636007.5936, ukdf['pct'].iloc[-1]=0.0006 , ukdf['amount'].iloc[-1]=10636007.5936, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5859, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '37.141', 'enterprice': '26844', 'countrevence': '0', 'unrealprofit': '92759.6475', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '29341.5', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=1
--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=1, self.total=996015.990996, self.flagDict['side']='buy', self.tradeCount=1, self.count=22145
self.closeSec=1690676699, self.tradeDate='20230730', self.openTime='082000', self.closeTime='082459', self.symbol='BTCUSDT', self.open=29341.6, self.close=29319.9, self.high=29345.9, self.low=29319.0, self.vol=405.179, self.amt=11884353.0835 
127.0.0.1 - - [30/Jul/2023 08:25:00] "POST / HTTP/1.1" 200 -
2023-07-30 08:25:00,792:INFO:sr_min:main.py:172:handleKline:2219263: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5856  20230730   080000    080459  ...         0.0        0.0       0
5857  20230730   080500    080959  ...         0.0        0.0       0
5858  20230730   081000    081459  ...         0.0        0.0       0
5859  20230730   081500    081959  ...         0.0        0.0       0
5860  20230730   082000    082459  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-07-30 08:25:00,793:INFO:sr_min:main.py:175:handleKline:2219263: self.closeSec=1690676699, self.tradeDate='20230730', self.openTime='082000', self.closeTime='082459',self.symbol='BTCUSDT',self.open=29341.6, self.close=29319.9, self.high=29345.9, self.low=29319.0, self.vol=405.179, self.amt=11884353.0835, ukdf['pct'].iloc[-1]=-0.00074 , ukdf['amount'].iloc[-1]=11884353.0835, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5860, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '37.141', 'enterprice': '26844', 'countrevence': '0', 'unrealprofit': '91963.00604160748', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '29320.05088828', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=1


## /root/FIL/strategy/s_rsrs/log.txt ----- -----

719  20230729   200000    235959  1690646399  ...    719  0.164504 -0.841976    -1.0
720  20230730   000000    035959  1690660799  ...    720  0.153205 -0.881509    -1.0

[5 rows x 15 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '54.024', 'enterprice': '29248', 'countrevence': '0', 'unrealprofit': '-4500.1992', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '29331.3', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'numpy.int64'>, curSign=-1, self.sign=-1
127.0.0.1 - - [30/Jul/2023 08:00:01] "POST / HTTP/1.1" 200 -
--handleKline--:  version='2.0.0', self.name='s_rsrs', self.symbol='BTCUSDT', interval='4h', intervalSec=14400, wid=25, thd=0.6, self.sign=-1, self.total=1578513.8580480001, self.flagDict['side']='sell', self.tradeCount=16, self.count=461
self.closeSec=1690675199, self.tradeDate='20230730', self.openTime='040000', self.closeTime='075959', self.symbol='BTCUSDT', self.open=29328.0, self.close=29339.1, self.high=29368.8, self.low=29328.0, self.vol=9865.259, self.amt=289516671.6834 
2023-07-30 08:00:01,744:INFO:s_rsrs:main.py:141:handleKline:2218689: self.closeSec=1690675199, self.tradeDate='20230730', self.openTime='040000', self.closeTime='075959',self.symbol='BTCUSDT',self.open=29328.0, self.close=29339.1, self.high=29368.8, self.low=29328.0, self.vol=9865.259, self.amt=289516671.6834 
2023-07-30 08:00:01,756:INFO:s_rsrs:main.py:142:handleKline:2218689: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime  ...        vol           amt       pct
717  20230729   120000    155959  ...  16468.927  4.830698e+08 -0.002477
718  20230729   160000    195959  ...  17802.940  5.212020e+08 -0.001018
719  20230729   200000    235959  ...  18876.177  5.528415e+08  0.001080
720  20230730   000000    035959  ...  12008.201  3.518909e+08  0.001475
721  20230730   040000    075959  ...   9865.259  2.895167e+08  0.000378

[5 rows x 11 columns]
2023-07-30 08:00:02,443:INFO:s_rsrs:main.py:151:handleKline:2218689: df_s.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec  ...  index      beta    zscore  signal
717  20230729   120000    155959  1690617599  ...    717  0.318044 -0.226289     NaN
718  20230729   160000    195959  1690631999  ...    718  0.206454 -0.681672    -1.0
719  20230729   200000    235959  1690646399  ...    719  0.164504 -0.841976    -1.0
720  20230730   000000    035959  1690660799  ...    720  0.153205 -0.881509    -1.0
721  20230730   040000    075959  1690675199  ...    721  0.116313 -1.023235    -1.0

[5 rows x 15 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '54.024', 'enterprice': '29248', 'countrevence': '0', 'unrealprofit': '-5016.05122293432', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '29340.84857143', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'numpy.int64'>, curSign=-1, self.sign=-1


