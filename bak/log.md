# 20230816 08:26:01

## /root/FIL/strategy/amihud/log.txt ----- -----

--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=373746.4768026, self.flagDict['side']='sell', self.tradeCount=2, self.count=27040
self.closeSec=1692145199, self.tradeDate='20230816', self.openTime='081500', self.closeTime='081959', self.symbol='BTCUSDT', self.open=29219.1, self.close=29227.0, self.high=29228.9, self.low=29219.0, self.vol=344.389, self.amt=10064672.146 
127.0.0.1 - - [16/Aug/2023 08:20:01] "POST / HTTP/1.1" 200 -
2023-08-16 08:20:07,512:INFO:amihud:main.py:172:handleKline:2219019: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5855  20230816   075500    075959  ...         0.0        0.0       0
5856  20230816   080000    080459  ...         0.0        0.0       0
5857  20230816   080500    080959  ...         0.0        0.0       0
5858  20230816   081000    081459  ...         0.0        0.0       0
5859  20230816   081500    081959  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-08-16 08:20:07,542:INFO:amihud:main.py:175:handleKline:2219019: self.closeSec=1692145199, self.tradeDate='20230816', self.openTime='081500', self.closeTime='081959',self.symbol='BTCUSDT',self.open=29219.1, self.close=29227.0, self.high=29228.9, self.low=29219.0, self.vol=344.389, self.amt=10064672.146, ukdf['pct'].iloc[-1]=0.00027 , ukdf['amount'].iloc[-1]=10064672.146, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5859, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '13.926', 'enterprice': '26864.9', 'countrevence': '0', 'unrealprofit': '-32904.66450259428', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '29227.72238278', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1
127.0.0.1 - - [16/Aug/2023 08:25:00] "POST / HTTP/1.1" 200 -
--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=373746.4768026, self.flagDict['side']='sell', self.tradeCount=2, self.count=27041
self.closeSec=1692145499, self.tradeDate='20230816', self.openTime='082000', self.closeTime='082459', self.symbol='BTCUSDT', self.open=29227.0, self.close=29204.9, self.high=29227.1, self.low=29204.8, self.vol=592.409, self.amt=17310521.6917 
2023-08-16 08:25:00,782:INFO:amihud:main.py:172:handleKline:2219019: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5856  20230816   080000    080459  ...         0.0        0.0       0
5857  20230816   080500    080959  ...         0.0        0.0       0
5858  20230816   081000    081459  ...         0.0        0.0       0
5859  20230816   081500    081959  ...         0.0        0.0       0
5860  20230816   082000    082459  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-08-16 08:25:00,782:INFO:amihud:main.py:175:handleKline:2219019: self.closeSec=1692145499, self.tradeDate='20230816', self.openTime='082000', self.closeTime='082459',self.symbol='BTCUSDT',self.open=29227.0, self.close=29204.9, self.high=29227.1, self.low=29204.8, self.vol=592.409, self.amt=17310521.6917, ukdf['pct'].iloc[-1]=-0.000756 , ukdf['amount'].iloc[-1]=17310521.6917, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5860, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '13.926', 'enterprice': '26864.9', 'countrevence': '0', 'unrealprofit': '-32621.08343490348', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '29207.35895698', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1


## /root/FIL/strategy/factorcheck/log.txt ----- -----


self.closeSec=1692145199, self.tradeDate='20230816', self.openTime='081500', self.closeTime='081959', self.symbol='BTCUSDT', self.open=29219.1, self.close=29227.0, self.high=29228.9, self.low=29219.0 
127.0.0.1 - - [16/Aug/2023 08:20:01] "POST / HTTP/1.1" 200 -
2023-08-16 08:20:04,882:INFO:factorcheck2:main.py:126:handleKline:2218005: self.closeSec=1692145199, self.tradeDate='20230816', self.openTime='081500', self.closeTime='081959',self.symbol='BTCUSDT',self.open=29219.1, self.close=29227.0, self.high=29228.9, self.low=29219.0   
2023-08-16 08:20:06,292:INFO:factorcheck2:main.py:127:handleKline:2218005: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime    closeSec  ...      low       pct  index  idx
1535  20230816   075500    075959  1692143999  ...  29187.5  0.000027   1535    5
1536  20230816   080000    080459  1692144299  ...  29184.6  0.000380   1536    0
1537  20230816   080500    080959  1692144599  ...  29199.9  0.000380   1537    1
1538  20230816   081000    081459  1692144899  ...  29211.0  0.000274   1538    2
1539  20230816   081500    081959  1692145199  ...  29219.0  0.000270   1539    3

[5 rows x 11 columns]
2023-08-16 08:20:06,302:INFO:factorcheck2:main.py:128:handleKline:2218005: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': True, 'isOpenSell': False, 'isCloseBuy': False, 'isCloseSell': False, 'isOpen': True, 'isClose': False, 'isTrig': True}

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=0, self.factor=0.6571487585317491, self.count=27043 

self.closeSec=1692145499, self.tradeDate='20230816', self.openTime='082000', self.closeTime='082459', self.symbol='BTCUSDT', self.open=29227.0, self.close=29204.9, self.high=29227.1, self.low=29204.8 
127.0.0.1 - - [16/Aug/2023 08:25:00] "POST / HTTP/1.1" 200 -
2023-08-16 08:25:00,769:INFO:factorcheck2:main.py:126:handleKline:2218005: self.closeSec=1692145499, self.tradeDate='20230816', self.openTime='082000', self.closeTime='082459',self.symbol='BTCUSDT',self.open=29227.0, self.close=29204.9, self.high=29227.1, self.low=29204.8   
2023-08-16 08:25:00,790:INFO:factorcheck2:main.py:127:handleKline:2218005: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime    closeSec  ...      low       pct  index  idx
1536  20230816   080000    080459  1692144299  ...  29184.6  0.000380   1536    0
1537  20230816   080500    080959  1692144599  ...  29199.9  0.000380   1537    1
1538  20230816   081000    081459  1692144899  ...  29211.0  0.000274   1538    2
1539  20230816   081500    081959  1692145199  ...  29219.0  0.000270   1539    3
1540  20230816   082000    082459  1692145499  ...  29204.8 -0.000756   1540    4

[5 rows x 11 columns]
2023-08-16 08:25:00,790:INFO:factorcheck2:main.py:128:handleKline:2218005: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': True, 'isOpenSell': False, 'isCloseBuy': False, 'isCloseSell': False, 'isOpen': True, 'isClose': False, 'isTrig': True}


## /root/FIL/strategy/logic/log.txt ----- -----

2023-08-16 08:00:16,934:DEBUG:logic:main.py:463:getModel:2218526: df_s.iloc[-5:,:] :
          date closeTime     open  ...    alpha58   alpha67   alpha72
5770  20230816    052959  29191.8  ...  47.083333  0.446851  0.647648
5771  20230816    055959  29226.8  ...  46.666667  0.442920  0.646287
5772  20230816    062959  29214.8  ...  46.250000  0.442853  0.645047
5773  20230816    065959  29214.7  ...  46.250000  0.428474  0.650464
5774  20230816    072959  29171.0  ...  46.250000  0.432913  0.653967

[5 rows x 33 columns]
0.5378927911275416
acc is : 0.5378927911275416
2023-08-16 08:00:16,994:INFO:logic:main.py:468:getModel:2218526: df_pred.iloc[-5:,:] :
     pred    prob_0    prob_1  actual  ...       nav  sign  cost_        bm
536     1  0.496349  0.503651       0  ...  1.018960  -1.0    0.0  0.999579
537     1  0.493210  0.506790       0  ...  1.018967  -1.0    0.0  0.999572
538     1  0.494001  0.505999       0  ...  1.020488  -1.0    0.0  0.998081
539     1  0.478279  0.521721       1  ...  1.020127  -1.0    0.0  0.998433
540     1  0.497488  0.502512       1  ...  1.019862  -1.0    0.0  0.998693

[5 rows x 10 columns]
2023-08-16 08:00:17,005:INFO:logic:main.py:478:getModel:2218526: df_panel.iloc[-5:,:] :
    pred    prob_0    prob_1  actual  ...       nav  sign  cost_        bm
45     1  0.496401  0.503599       0  ...  1.018960  -1.0    0.0  0.998496
46     1  0.493295  0.506705       0  ...  1.018967  -1.0    0.0  0.998520
47     1  0.494264  0.505736       0  ...  1.020488  -1.0    0.0  0.997241
48     1  0.478497  0.521503       1  ...  1.020127  -1.0    0.0  0.998433
49     1  0.497488  0.502512       1  ...  1.019862  -1.0    0.0  0.998693

[5 rows x 10 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '23.521', 'enterprice': '29410.3', 'countrevence': '0', 'unrealprofit': '5249.8872', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '29187.1', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}


## /root/FIL/strategy/modifiedmom/log.txt ----- -----

623  20230816   075000    075959  1692143999  29187.2  29188.9  0.000062
2023-08-16 08:00:01,996:INFO:modifiedmom:main.py:146:handleKline:2218259: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': True, 'isOpen': False, 'isClose': True, 'isTrig': False}

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=13520 

self.closeSec=1692144599, self.tradeDate='20230816', self.openTime='080000', self.closeTime='080959', self.symbol='BTCUSDT', self.open='29188.9', self.close='29211.1'
2023-08-16 08:10:01,186:INFO:modifiedmom:main.py:144:handleKline:2218259: self.closeSec=1692144599, self.tradeDate='20230816', self.openTime='080000', self.closeTime='080959',self.symbol='BTCUSDT',self.open='29188.9', self.close='29211.1'
127.0.0.1 - - [16/Aug/2023 08:10:01] "POST / HTTP/1.1" 200 -
2023-08-16 08:10:01,201:INFO:modifiedmom:main.py:145:handleKline:2218259: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec     open    close       pct
620  20230816   072000    072959  1692142199  29185.6  29181.3 -0.000147
621  20230816   073000    073959  1692142799  29181.3  29183.7  0.000082
622  20230816   074000    074959  1692143399  29183.7  29187.1  0.000117
623  20230816   075000    075959  1692143999  29187.2  29188.9  0.000062
624  20230816   080000    080959  1692144599  29188.9  29211.1  0.000761
2023-08-16 08:10:01,201:INFO:modifiedmom:main.py:146:handleKline:2218259: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': True, 'isOpen': False, 'isClose': True, 'isTrig': False}

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=13521 

self.closeSec=1692145199, self.tradeDate='20230816', self.openTime='081000', self.closeTime='081959', self.symbol='BTCUSDT', self.open='29211.1', self.close='29227.1'
127.0.0.1 - - [16/Aug/2023 08:20:04] "POST / HTTP/1.1" 200 -
2023-08-16 08:20:07,643:INFO:modifiedmom:main.py:144:handleKline:2218259: self.closeSec=1692145199, self.tradeDate='20230816', self.openTime='081000', self.closeTime='081959',self.symbol='BTCUSDT',self.open='29211.1', self.close='29227.1'
2023-08-16 08:20:08,463:INFO:modifiedmom:main.py:145:handleKline:2218259: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec     open    close       pct
621  20230816   073000    073959  1692142799  29181.3  29183.7  0.000082
622  20230816   074000    074959  1692143399  29183.7  29187.1  0.000117
623  20230816   075000    075959  1692143999  29187.2  29188.9  0.000062
624  20230816   080000    080959  1692144599  29188.9  29211.1  0.000761
625  20230816   081000    081959  1692145199  29211.1  29227.1  0.000548
2023-08-16 08:20:08,472:INFO:modifiedmom:main.py:146:handleKline:2218259: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': True, 'isOpen': False, 'isClose': True, 'isTrig': False}


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

17471  20230816   075000    075959  1692143999  29187.2  29188.9
2023-08-16 08:00:02,015:INFO:pyemd2:main.py:127:handleKline:2217508: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}
127.0.0.1 - - [16/Aug/2023 08:10:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=13523 

self.closeSec=1692144599, self.tradeDate='20230816', self.openTime='080000', self.closeTime='080959', self.symbol='BTCUSDT', self.open='29188.9', self.close='29211.1'
2023-08-16 08:10:01,188:INFO:pyemd2:main.py:125:handleKline:2217508: self.closeSec=1692144599, self.tradeDate='20230816', self.openTime='080000', self.closeTime='080959',self.symbol='BTCUSDT',self.open='29188.9', self.close='29211.1'
2023-08-16 08:10:01,198:INFO:pyemd2:main.py:126:handleKline:2217508: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
17468  20230816   072000    072959  1692142199  29185.6  29181.3
17469  20230816   073000    073959  1692142799  29181.3  29183.7
17470  20230816   074000    074959  1692143399  29183.7  29187.1
17471  20230816   075000    075959  1692143999  29187.2  29188.9
17472  20230816   080000    080959  1692144599  29188.9  29211.1
2023-08-16 08:10:01,198:INFO:pyemd2:main.py:127:handleKline:2217508: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=13524 

self.closeSec=1692145199, self.tradeDate='20230816', self.openTime='081000', self.closeTime='081959', self.symbol='BTCUSDT', self.open='29211.1', self.close='29227.1'
127.0.0.1 - - [16/Aug/2023 08:20:04] "POST / HTTP/1.1" 200 -
2023-08-16 08:20:09,884:INFO:pyemd2:main.py:125:handleKline:2217508: self.closeSec=1692145199, self.tradeDate='20230816', self.openTime='081000', self.closeTime='081959',self.symbol='BTCUSDT',self.open='29211.1', self.close='29227.1'
2023-08-16 08:20:10,012:INFO:pyemd2:main.py:126:handleKline:2217508: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
17469  20230816   073000    073959  1692142799  29181.3  29183.7
17470  20230816   074000    074959  1692143399  29183.7  29187.1
17471  20230816   075000    075959  1692143999  29187.2  29188.9
17472  20230816   080000    080959  1692144599  29188.9  29211.1
17473  20230816   081000    081959  1692145199  29211.1  29227.1
2023-08-16 08:20:10,013:INFO:pyemd2:main.py:127:handleKline:2217508: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}


## /root/FIL/strategy/similarity/log.txt ----- -----

12143  20230816   075000    075959  1692143999  29187.2  29188.9
2023-08-16 08:00:02,003:INFO:testStrategy:main.py:103:handleKline:2217133: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': True, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True, 'isCorr': False}
127.0.0.1 - - [16/Aug/2023 08:10:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=13523 

self.closeSec=1692144599, self.tradeDate='20230816', self.openTime='080000', self.closeTime='080959', self.symbol='BTCUSDT', self.open='29188.9', self.close='29211.1'
2023-08-16 08:10:01,195:INFO:testStrategy:main.py:101:handleKline:2217133: self.closeSec=1692144599, self.tradeDate='20230816', self.openTime='080000', self.closeTime='080959',self.symbol='BTCUSDT',self.open='29188.9', self.close='29211.1'
2023-08-16 08:10:01,206:INFO:testStrategy:main.py:102:handleKline:2217133: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
12140  20230816   072000    072959  1692142199  29185.6  29181.3
12141  20230816   073000    073959  1692142799  29181.3  29183.7
12142  20230816   074000    074959  1692143399  29183.7  29187.1
12143  20230816   075000    075959  1692143999  29187.2  29188.9
12144  20230816   080000    080959  1692144599  29188.9  29211.1
2023-08-16 08:10:01,206:INFO:testStrategy:main.py:103:handleKline:2217133: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': True, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True, 'isCorr': False}

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=13524 

self.closeSec=1692145199, self.tradeDate='20230816', self.openTime='081000', self.closeTime='081959', self.symbol='BTCUSDT', self.open='29211.1', self.close='29227.1'
127.0.0.1 - - [16/Aug/2023 08:20:04] "POST / HTTP/1.1" 200 -
2023-08-16 08:20:09,643:INFO:testStrategy:main.py:101:handleKline:2217133: self.closeSec=1692145199, self.tradeDate='20230816', self.openTime='081000', self.closeTime='081959',self.symbol='BTCUSDT',self.open='29211.1', self.close='29227.1'
2023-08-16 08:20:09,836:INFO:testStrategy:main.py:102:handleKline:2217133: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
12141  20230816   073000    073959  1692142799  29181.3  29183.7
12142  20230816   074000    074959  1692143399  29183.7  29187.1
12143  20230816   075000    075959  1692143999  29187.2  29188.9
12144  20230816   080000    080959  1692144599  29188.9  29211.1
12145  20230816   081000    081959  1692145199  29211.1  29227.1
2023-08-16 08:20:09,842:INFO:testStrategy:main.py:103:handleKline:2217133: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': True, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True, 'isCorr': False}


## /root/FIL/strategy/sr_min/log.txt ----- -----

--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=1, self.total=996015.990996, self.flagDict['side']='buy', self.tradeCount=1, self.count=27040
self.closeSec=1692145199, self.tradeDate='20230816', self.openTime='081500', self.closeTime='081959', self.symbol='BTCUSDT', self.open=29219.1, self.close=29227.0, self.high=29228.9, self.low=29219.0, self.vol=344.389, self.amt=10064672.146 
127.0.0.1 - - [16/Aug/2023 08:20:01] "POST / HTTP/1.1" 200 -
2023-08-16 08:20:07,313:INFO:sr_min:main.py:172:handleKline:2219263: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5855  20230816   075500    075959  ...         0.0        0.0       0
5856  20230816   080000    080459  ...         0.0        0.0       0
5857  20230816   080500    080959  ...         0.0        0.0       0
5858  20230816   081000    081459  ...         0.0        0.0       0
5859  20230816   081500    081959  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-08-16 08:20:07,343:INFO:sr_min:main.py:175:handleKline:2219263: self.closeSec=1692145199, self.tradeDate='20230816', self.openTime='081500', self.closeTime='081959',self.symbol='BTCUSDT',self.open=29219.1, self.close=29227.0, self.high=29228.9, self.low=29219.0, self.vol=344.389, self.amt=10064672.146, ukdf['pct'].iloc[-1]=0.00027 , ukdf['amount'].iloc[-1]=10064672.146, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5859, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '37.141', 'enterprice': '26844', 'countrevence': '0', 'unrealprofit': '88533.99627618299', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '29227.72677839', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=1
127.0.0.1 - - [16/Aug/2023 08:25:00] "POST / HTTP/1.1" 200 -
--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=1, self.total=996015.990996, self.flagDict['side']='buy', self.tradeCount=1, self.count=27041
self.closeSec=1692145499, self.tradeDate='20230816', self.openTime='082000', self.closeTime='082459', self.symbol='BTCUSDT', self.open=29227.0, self.close=29204.9, self.high=29227.1, self.low=29204.8, self.vol=592.409, self.amt=17310521.6917 
2023-08-16 08:25:00,801:INFO:sr_min:main.py:172:handleKline:2219263: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5856  20230816   080000    080459  ...         0.0        0.0       0
5857  20230816   080500    080959  ...         0.0        0.0       0
5858  20230816   081000    081459  ...         0.0        0.0       0
5859  20230816   081500    081959  ...         0.0        0.0       0
5860  20230816   082000    082459  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-08-16 08:25:00,801:INFO:sr_min:main.py:175:handleKline:2219263: self.closeSec=1692145499, self.tradeDate='20230816', self.openTime='082000', self.closeTime='082459',self.symbol='BTCUSDT',self.open=29227.0, self.close=29204.9, self.high=29227.1, self.low=29204.8, self.vol=592.409, self.amt=17310521.6917, ukdf['pct'].iloc[-1]=-0.000756 , ukdf['amount'].iloc[-1]=17310521.6917, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5860, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '37.141', 'enterprice': '26844', 'countrevence': '0', 'unrealprofit': '87777.51502119418', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '29207.35895698', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=1


## /root/FIL/strategy/s_rsrs/log.txt ----- -----

719  20230815   200000    235959  1692115199  ...    719  0.000410 -1.130170    -1.0
720  20230816   000000    035959  1692129599  ...    720  0.000004 -1.128381    -1.0

[5 rows x 15 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '51.388', 'enterprice': '29432.6', 'countrevence': '0', 'unrealprofit': '13557.6011700438', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '29168.77184615', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'numpy.int64'>, curSign=-1, self.sign=-1
127.0.0.1 - - [16/Aug/2023 08:00:01] "POST / HTTP/1.1" 200 -
--handleKline--:  version='2.0.0', self.name='s_rsrs', self.symbol='BTCUSDT', interval='4h', intervalSec=14400, wid=25, thd=0.6, self.sign=-1, self.total=1510969.9663512, self.flagDict['side']='sell', self.tradeCount=20, self.count=563
self.closeSec=1692143999, self.tradeDate='20230816', self.openTime='040000', self.closeTime='075959', self.symbol='BTCUSDT', self.open=29172.4, self.close=29188.9, self.high=29234.6, self.low=29125.8, self.vol=22102.685, self.amt=645245653.3646 
2023-08-16 08:00:01,582:INFO:s_rsrs:main.py:141:handleKline:2218689: self.closeSec=1692143999, self.tradeDate='20230816', self.openTime='040000', self.closeTime='075959',self.symbol='BTCUSDT',self.open=29172.4, self.close=29188.9, self.high=29234.6, self.low=29125.8, self.vol=22102.685, self.amt=645245653.3646 
2023-08-16 08:00:01,595:INFO:s_rsrs:main.py:142:handleKline:2218689: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime  ...        vol           amt       pct
717  20230815   120000    155959  ...  14399.120  4.229356e+08  0.000337
718  20230815   160000    195959  ...  22179.354  6.520325e+08 -0.001350
719  20230815   200000    235959  ...  46749.748  1.373552e+09 -0.001427
720  20230816   000000    035959  ...  71364.668  2.084812e+09 -0.004868
721  20230816   040000    075959  ...  22102.685  6.452457e+08  0.000562

[5 rows x 11 columns]
2023-08-16 08:00:02,229:INFO:s_rsrs:main.py:151:handleKline:2218689: df_s.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec  ...  index      beta    zscore  signal
717  20230815   120000    155959  1692086399  ...    717  0.000267 -1.136717    -1.0
718  20230815   160000    195959  1692100799  ...    718  0.000333 -1.132243    -1.0
719  20230815   200000    235959  1692115199  ...    719  0.000410 -1.130170    -1.0
720  20230816   000000    035959  1692129599  ...    720  0.000004 -1.128381    -1.0
721  20230816   040000    075959  1692143999  ...    721  0.002208 -1.120043    -1.0

[5 rows x 15 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '51.388', 'enterprice': '29432.6', 'countrevence': '0', 'unrealprofit': '12523.2556', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '29188.9', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'numpy.int64'>, curSign=-1, self.sign=-1


