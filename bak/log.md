# 20230812 08:26:02

## /root/FIL/strategy/amihud/log.txt ----- -----

--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=373746.4768026, self.flagDict['side']='sell', self.tradeCount=2, self.count=25888
self.closeSec=1691799599, self.tradeDate='20230812', self.openTime='081500', self.closeTime='081959', self.symbol='BTCUSDT', self.open=29397.5, self.close=29399.6, self.high=29401.0, self.low=29397.4, self.vol=196.371, self.amt=5773242.1973 
127.0.0.1 - - [12/Aug/2023 08:20:01] "POST / HTTP/1.1" 200 -
2023-08-12 08:20:06,880:INFO:amihud:main.py:172:handleKline:2219019: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5855  20230812   075500    075959  ...         0.0        0.0       0
5856  20230812   080000    080459  ...         0.0        0.0       0
5857  20230812   080500    080959  ...         0.0        0.0       0
5858  20230812   081000    081459  ...         0.0        0.0       0
5859  20230812   081500    081959  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-08-12 08:20:06,910:INFO:amihud:main.py:175:handleKline:2219019: self.closeSec=1691799599, self.tradeDate='20230812', self.openTime='081500', self.closeTime='081959',self.symbol='BTCUSDT',self.open=29397.5, self.close=29399.6, self.high=29401.0, self.low=29397.4, self.vol=196.371, self.amt=5773242.1973, ukdf['pct'].iloc[-1]=7.5e-05 , ukdf['amount'].iloc[-1]=5773242.1973, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5859, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '13.926', 'enterprice': '26864.9', 'countrevence': '0', 'unrealprofit': '-35314.4628945108', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '29400.7654958', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1
127.0.0.1 - - [12/Aug/2023 08:25:00] "POST / HTTP/1.1" 200 -
--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=373746.4768026, self.flagDict['side']='sell', self.tradeCount=2, self.count=25889
self.closeSec=1691799899, self.tradeDate='20230812', self.openTime='082000', self.closeTime='082459', self.symbol='BTCUSDT', self.open=29399.6, self.close=29402.6, self.high=29402.6, self.low=29399.6, self.vol=157.369, self.amt=4626756.1659 
2023-08-12 08:25:00,779:INFO:amihud:main.py:172:handleKline:2219019: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5856  20230812   080000    080459  ...         0.0        0.0       0
5857  20230812   080500    080959  ...         0.0        0.0       0
5858  20230812   081000    081459  ...         0.0        0.0       0
5859  20230812   081500    081959  ...         0.0        0.0       0
5860  20230812   082000    082459  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-08-12 08:25:00,779:INFO:amihud:main.py:175:handleKline:2219019: self.closeSec=1691799899, self.tradeDate='20230812', self.openTime='082000', self.closeTime='082459',self.symbol='BTCUSDT',self.open=29399.6, self.close=29402.6, self.high=29402.6, self.low=29399.6, self.vol=157.369, self.amt=4626756.1659, ukdf['pct'].iloc[-1]=0.000102 , ukdf['amount'].iloc[-1]=4626756.1659, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5860, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '13.926', 'enterprice': '26864.9', 'countrevence': '0', 'unrealprofit': '-35342.6007298386', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '29402.7860211', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1


## /root/FIL/strategy/factorcheck/log.txt ----- -----


self.closeSec=1691799599, self.tradeDate='20230812', self.openTime='081500', self.closeTime='081959', self.symbol='BTCUSDT', self.open=29397.5, self.close=29399.6, self.high=29401.0, self.low=29397.4 
127.0.0.1 - - [12/Aug/2023 08:20:01] "POST / HTTP/1.1" 200 -
2023-08-12 08:20:04,600:INFO:factorcheck2:main.py:126:handleKline:2218005: self.closeSec=1691799599, self.tradeDate='20230812', self.openTime='081500', self.closeTime='081959',self.symbol='BTCUSDT',self.open=29397.5, self.close=29399.6, self.high=29401.0, self.low=29397.4   
2023-08-12 08:20:05,830:INFO:factorcheck2:main.py:127:handleKline:2218005: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime    closeSec  ...      low       pct  index  idx
1535  20230812   075500    075959  1691798399  ...  29415.5 -0.000014   1535    5
1536  20230812   080000    080459  1691798699  ...  29406.0 -0.000326   1536    0
1537  20230812   080500    080959  1691798999  ...  29397.4 -0.000289   1537    1
1538  20230812   081000    081459  1691799299  ...  29393.1 -0.000003   1538    2
1539  20230812   081500    081959  1691799599  ...  29397.4  0.000075   1539    3

[5 rows x 11 columns]
2023-08-12 08:20:05,839:INFO:factorcheck2:main.py:128:handleKline:2218005: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': True, 'isOpenSell': False, 'isCloseBuy': False, 'isCloseSell': False, 'isOpen': True, 'isClose': False, 'isTrig': True}

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=0, self.factor=0.6666145302475172, self.count=25891 

self.closeSec=1691799899, self.tradeDate='20230812', self.openTime='082000', self.closeTime='082459', self.symbol='BTCUSDT', self.open=29399.6, self.close=29402.6, self.high=29402.6, self.low=29399.6 
127.0.0.1 - - [12/Aug/2023 08:25:00] "POST / HTTP/1.1" 200 -
2023-08-12 08:25:00,765:INFO:factorcheck2:main.py:126:handleKline:2218005: self.closeSec=1691799899, self.tradeDate='20230812', self.openTime='082000', self.closeTime='082459',self.symbol='BTCUSDT',self.open=29399.6, self.close=29402.6, self.high=29402.6, self.low=29399.6   
2023-08-12 08:25:00,786:INFO:factorcheck2:main.py:127:handleKline:2218005: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime    closeSec  ...      low       pct  index  idx
1536  20230812   080000    080459  1691798699  ...  29406.0 -0.000326   1536    0
1537  20230812   080500    080959  1691798999  ...  29397.4 -0.000289   1537    1
1538  20230812   081000    081459  1691799299  ...  29393.1 -0.000003   1538    2
1539  20230812   081500    081959  1691799599  ...  29397.4  0.000075   1539    3
1540  20230812   082000    082459  1691799899  ...  29399.6  0.000102   1540    4

[5 rows x 11 columns]
2023-08-12 08:25:00,786:INFO:factorcheck2:main.py:128:handleKline:2218005: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': True, 'isOpenSell': False, 'isCloseBuy': False, 'isCloseSell': False, 'isOpen': True, 'isClose': False, 'isTrig': True}


## /root/FIL/strategy/logic/log.txt ----- -----

2023-08-12 08:00:18,503:DEBUG:logic:main.py:463:getModel:2218526: df_s.iloc[-5:,:] :
          date closeTime     open  ...    alpha58   alpha67   alpha72
5770  20230812    052959  29407.3  ...  47.500000  0.488258  0.569584
5771  20230812    055959  29422.0  ...  47.500000  0.480726  0.563216
5772  20230812    062959  29401.6  ...  47.500000  0.484722  0.555322
5773  20230812    065959  29411.6  ...  47.916667  0.488065  0.546331
5774  20230812    072959  29420.1  ...  47.916667  0.485235  0.539369

[5 rows x 33 columns]
0.5194085027726433
acc is : 0.5194085027726433
2023-08-12 08:00:18,562:INFO:logic:main.py:468:getModel:2218526: df_pred.iloc[-5:,:] :
     pred    prob_0    prob_1  actual  ...       nav  sign  cost_        bm
536     0  0.511347  0.488653       0  ...  0.981857  -1.0    0.0  1.007770
537     0  0.501821  0.498179       1  ...  0.981519  -1.0    0.0  1.008117
538     0  0.509136  0.490864       1  ...  0.981239  -1.0    0.0  1.008405
539     0  0.508991  0.491009       0  ...  0.981486  -1.0    0.0  1.008151
540     0  0.504597  0.495403       1  ...  0.981386  -1.0    0.0  1.008254

[5 rows x 10 columns]
2023-08-12 08:00:18,573:INFO:logic:main.py:478:getModel:2218526: df_panel.iloc[-5:,:] :
    pred    prob_0    prob_1  actual  ...       nav  sign  cost_        bm
45     0  0.511175  0.488825       0  ...  0.981857  -1.0    0.0  1.005823
46     0  0.501552  0.498448       1  ...  0.981519  -1.0    0.0  1.006134
47     0  0.508977  0.491023       1  ...  0.981239  -1.0    0.0  1.007013
48     0  0.508994  0.491006       0  ...  0.981486  -1.0    0.0  1.008151
49     0  0.504597  0.495403       1  ...  0.981386  -1.0    0.0  1.008254

[5 rows x 10 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '24.049', 'enterprice': '29479.7', 'countrevence': '0', 'unrealprofit': '1532.08466317357', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '29415.99320707', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}


## /root/FIL/strategy/modifiedmom/log.txt ----- -----

623  20230812   075000    075959  1691798399  29412.3  29415.5  0.000112
2023-08-12 08:00:02,096:INFO:modifiedmom:main.py:146:handleKline:2218259: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': True, 'isOpen': False, 'isClose': True, 'isTrig': False}
127.0.0.1 - - [12/Aug/2023 08:10:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=12944 

self.closeSec=1691798999, self.tradeDate='20230812', self.openTime='080000', self.closeTime='080959', self.symbol='BTCUSDT', self.open='29415.5', self.close='29397.5'
2023-08-12 08:10:01,153:INFO:modifiedmom:main.py:144:handleKline:2218259: self.closeSec=1691798999, self.tradeDate='20230812', self.openTime='080000', self.closeTime='080959',self.symbol='BTCUSDT',self.open='29415.5', self.close='29397.5'
2023-08-12 08:10:01,167:INFO:modifiedmom:main.py:145:handleKline:2218259: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec     open    close       pct
620  20230812   072000    072959  1691796599  29402.4  29412.6  0.000344
621  20230812   073000    073959  1691797199  29412.6  29413.4  0.000027
622  20230812   074000    074959  1691797799  29413.5  29412.2 -0.000041
623  20230812   075000    075959  1691798399  29412.3  29415.5  0.000112
624  20230812   080000    080959  1691798999  29415.5  29397.5 -0.000612
2023-08-12 08:10:01,168:INFO:modifiedmom:main.py:146:handleKline:2218259: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': True, 'isOpen': False, 'isClose': True, 'isTrig': False}

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=12945 

self.closeSec=1691799599, self.tradeDate='20230812', self.openTime='081000', self.closeTime='081959', self.symbol='BTCUSDT', self.open='29397.5', self.close='29399.6'
127.0.0.1 - - [12/Aug/2023 08:20:04] "POST / HTTP/1.1" 200 -
2023-08-12 08:20:07,359:INFO:modifiedmom:main.py:144:handleKline:2218259: self.closeSec=1691799599, self.tradeDate='20230812', self.openTime='081000', self.closeTime='081959',self.symbol='BTCUSDT',self.open='29397.5', self.close='29399.6'
2023-08-12 08:20:08,080:INFO:modifiedmom:main.py:145:handleKline:2218259: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec     open    close       pct
621  20230812   073000    073959  1691797199  29412.6  29413.4  0.000027
622  20230812   074000    074959  1691797799  29413.5  29412.2 -0.000041
623  20230812   075000    075959  1691798399  29412.3  29415.5  0.000112
624  20230812   080000    080959  1691798999  29415.5  29397.5 -0.000612
625  20230812   081000    081959  1691799599  29397.5  29399.6  0.000071
2023-08-12 08:20:08,081:INFO:modifiedmom:main.py:146:handleKline:2218259: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': True, 'isOpen': False, 'isClose': True, 'isTrig': False}


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

17471  20230812   075000    075959  1691798399  29412.3  29415.5
2023-08-12 08:00:02,112:INFO:pyemd2:main.py:127:handleKline:2217508: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}
127.0.0.1 - - [12/Aug/2023 08:10:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=12947 

self.closeSec=1691798999, self.tradeDate='20230812', self.openTime='080000', self.closeTime='080959', self.symbol='BTCUSDT', self.open='29415.5', self.close='29397.5'
2023-08-12 08:10:01,159:INFO:pyemd2:main.py:125:handleKline:2217508: self.closeSec=1691798999, self.tradeDate='20230812', self.openTime='080000', self.closeTime='080959',self.symbol='BTCUSDT',self.open='29415.5', self.close='29397.5'
2023-08-12 08:10:01,172:INFO:pyemd2:main.py:126:handleKline:2217508: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
17468  20230812   072000    072959  1691796599  29402.4  29412.6
17469  20230812   073000    073959  1691797199  29412.6  29413.4
17470  20230812   074000    074959  1691797799  29413.5  29412.2
17471  20230812   075000    075959  1691798399  29412.3  29415.5
17472  20230812   080000    080959  1691798999  29415.5  29397.5
2023-08-12 08:10:01,172:INFO:pyemd2:main.py:127:handleKline:2217508: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=12948 

self.closeSec=1691799599, self.tradeDate='20230812', self.openTime='081000', self.closeTime='081959', self.symbol='BTCUSDT', self.open='29397.5', self.close='29399.6'
127.0.0.1 - - [12/Aug/2023 08:20:04] "POST / HTTP/1.1" 200 -
2023-08-12 08:20:09,471:INFO:pyemd2:main.py:125:handleKline:2217508: self.closeSec=1691799599, self.tradeDate='20230812', self.openTime='081000', self.closeTime='081959',self.symbol='BTCUSDT',self.open='29397.5', self.close='29399.6'
2023-08-12 08:20:09,600:INFO:pyemd2:main.py:126:handleKline:2217508: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
17469  20230812   073000    073959  1691797199  29412.6  29413.4
17470  20230812   074000    074959  1691797799  29413.5  29412.2
17471  20230812   075000    075959  1691798399  29412.3  29415.5
17472  20230812   080000    080959  1691798999  29415.5  29397.5
17473  20230812   081000    081959  1691799599  29397.5  29399.6
2023-08-12 08:20:09,601:INFO:pyemd2:main.py:127:handleKline:2217508: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}


## /root/FIL/strategy/similarity/log.txt ----- -----

12143  20230812   075000    075959  1691798399  29412.3  29415.5
2023-08-12 08:00:02,098:INFO:testStrategy:main.py:103:handleKline:2217133: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': True, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True, 'isCorr': False}
127.0.0.1 - - [12/Aug/2023 08:10:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=12947 

self.closeSec=1691798999, self.tradeDate='20230812', self.openTime='080000', self.closeTime='080959', self.symbol='BTCUSDT', self.open='29415.5', self.close='29397.5'
2023-08-12 08:10:01,156:INFO:testStrategy:main.py:101:handleKline:2217133: self.closeSec=1691798999, self.tradeDate='20230812', self.openTime='080000', self.closeTime='080959',self.symbol='BTCUSDT',self.open='29415.5', self.close='29397.5'
2023-08-12 08:10:01,162:INFO:testStrategy:main.py:102:handleKline:2217133: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
12140  20230812   072000    072959  1691796599  29402.4  29412.6
12141  20230812   073000    073959  1691797199  29412.6  29413.4
12142  20230812   074000    074959  1691797799  29413.5  29412.2
12143  20230812   075000    075959  1691798399  29412.3  29415.5
12144  20230812   080000    080959  1691798999  29415.5  29397.5
2023-08-12 08:10:01,163:INFO:testStrategy:main.py:103:handleKline:2217133: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': True, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True, 'isCorr': False}

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=12948 

self.closeSec=1691799599, self.tradeDate='20230812', self.openTime='081000', self.closeTime='081959', self.symbol='BTCUSDT', self.open='29397.5', self.close='29399.6'
127.0.0.1 - - [12/Aug/2023 08:20:04] "POST / HTTP/1.1" 200 -
2023-08-12 08:20:09,254:INFO:testStrategy:main.py:101:handleKline:2217133: self.closeSec=1691799599, self.tradeDate='20230812', self.openTime='081000', self.closeTime='081959',self.symbol='BTCUSDT',self.open='29397.5', self.close='29399.6'
2023-08-12 08:20:09,450:INFO:testStrategy:main.py:102:handleKline:2217133: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
12141  20230812   073000    073959  1691797199  29412.6  29413.4
12142  20230812   074000    074959  1691797799  29413.5  29412.2
12143  20230812   075000    075959  1691798399  29412.3  29415.5
12144  20230812   080000    080959  1691798999  29415.5  29397.5
12145  20230812   081000    081959  1691799599  29397.5  29399.6
2023-08-12 08:20:09,452:INFO:testStrategy:main.py:103:handleKline:2217133: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': True, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True, 'isCorr': False}


## /root/FIL/strategy/sr_min/log.txt ----- -----

--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=1, self.total=996015.990996, self.flagDict['side']='buy', self.tradeCount=1, self.count=25888
self.closeSec=1691799599, self.tradeDate='20230812', self.openTime='081500', self.closeTime='081959', self.symbol='BTCUSDT', self.open=29397.5, self.close=29399.6, self.high=29401.0, self.low=29397.4, self.vol=196.371, self.amt=5773242.1973 
127.0.0.1 - - [12/Aug/2023 08:20:01] "POST / HTTP/1.1" 200 -
2023-08-12 08:20:06,799:INFO:sr_min:main.py:172:handleKline:2219263: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5855  20230812   075500    075959  ...         0.0        0.0       0
5856  20230812   080000    080459  ...         0.0        0.0       0
5857  20230812   080500    080959  ...         0.0        0.0       0
5858  20230812   081000    081459  ...         0.0        0.0       0
5859  20230812   081500    081959  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-08-12 08:20:06,821:INFO:sr_min:main.py:175:handleKline:2219263: self.closeSec=1691799599, self.tradeDate='20230812', self.openTime='081500', self.closeTime='081959',self.symbol='BTCUSDT',self.open=29397.5, self.close=29399.6, self.high=29401.0, self.low=29397.4, self.vol=196.371, self.amt=5773242.1973, ukdf['pct'].iloc[-1]=7.5e-05 , ukdf['amount'].iloc[-1]=5773242.1973, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5859, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '37.141', 'enterprice': '26844', 'countrevence': '0', 'unrealprofit': '94960.8272795078', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '29400.7654958', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=1
--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=1, self.total=996015.990996, self.flagDict['side']='buy', self.tradeCount=1, self.count=25889
self.closeSec=1691799899, self.tradeDate='20230812', self.openTime='082000', self.closeTime='082459', self.symbol='BTCUSDT', self.open=29399.6, self.close=29402.6, self.high=29402.6, self.low=29399.6, self.vol=157.369, self.amt=4626756.1659 
127.0.0.1 - - [12/Aug/2023 08:25:00] "POST / HTTP/1.1" 200 -
2023-08-12 08:25:00,800:INFO:sr_min:main.py:172:handleKline:2219263: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5856  20230812   080000    080459  ...         0.0        0.0       0
5857  20230812   080500    080959  ...         0.0        0.0       0
5858  20230812   081000    081459  ...         0.0        0.0       0
5859  20230812   081500    081959  ...         0.0        0.0       0
5860  20230812   082000    082459  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-08-12 08:25:00,800:INFO:sr_min:main.py:175:handleKline:2219263: self.closeSec=1691799899, self.tradeDate='20230812', self.openTime='082000', self.closeTime='082459',self.symbol='BTCUSDT',self.open=29399.6, self.close=29402.6, self.high=29402.6, self.low=29399.6, self.vol=157.369, self.amt=4626756.1659, ukdf['pct'].iloc[-1]=0.000102 , ukdf['amount'].iloc[-1]=4626756.1659, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5860, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '37.141', 'enterprice': '26844', 'countrevence': '0', 'unrealprofit': '95035.8716096751', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '29402.7860211', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=1


## /root/FIL/strategy/s_rsrs/log.txt ----- -----

719  20230811   200000    235959  1691769599  ...    719  0.661498  0.717812     1.0
720  20230812   000000    035959  1691783999  ...    720  0.721001  0.884221     1.0

[5 rows x 15 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '51.457', 'enterprice': '29884.4', 'countrevence': '0', 'unrealprofit': '-25388.8838', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '29391', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'numpy.int64'>, curSign=1, self.sign=1
--handleKline--:  version='2.0.0', self.name='s_rsrs', self.symbol='BTCUSDT', interval='4h', intervalSec=14400, wid=25, thd=0.6, self.sign=1, self.total=1536223.8092292, self.flagDict['side']='buy', self.tradeCount=19, self.count=539
self.closeSec=1691798399, self.tradeDate='20230812', self.openTime='040000', self.closeTime='075959', self.symbol='BTCUSDT', self.open=29387.8, self.close=29415.5, self.high=29437.2, self.low=29382.9, self.vol=10294.37, self.amt=302753374.199 127.0.0.1 - - [12/Aug/2023 08:00:01] "POST / HTTP/1.1" 200 -

2023-08-12 08:00:01,655:INFO:s_rsrs:main.py:141:handleKline:2218689: self.closeSec=1691798399, self.tradeDate='20230812', self.openTime='040000', self.closeTime='075959',self.symbol='BTCUSDT',self.open=29387.8, self.close=29415.5, self.high=29437.2, self.low=29382.9, self.vol=10294.37, self.amt=302753374.199 
2023-08-12 08:00:01,671:INFO:s_rsrs:main.py:142:handleKline:2218689: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime  ...        vol           amt       pct
717  20230811   120000    155959  ...  18382.821  5.409012e+08  0.000204
718  20230811   160000    195959  ...  21936.641  6.448357e+08  0.000962
719  20230811   200000    235959  ...  67828.797  1.997330e+09 -0.001767
720  20230812   000000    035959  ...  41293.164  1.211417e+09  0.000163
721  20230812   040000    075959  ...  10294.370  3.027534e+08  0.000943

[5 rows x 11 columns]
2023-08-12 08:00:02,533:INFO:s_rsrs:main.py:151:handleKline:2218689: df_s.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec  ...  index      beta    zscore  signal
717  20230811   120000    155959  1691740799  ...    717  0.760064  1.001768     1.0
718  20230811   160000    195959  1691755199  ...    718  0.716036  0.872106     1.0
719  20230811   200000    235959  1691769599  ...    719  0.661498  0.717812     1.0
720  20230812   000000    035959  1691783999  ...    720  0.721001  0.884221     1.0
721  20230812   040000    075959  1691798399  ...    721  1.177032  2.091827     1.0

[5 rows x 15 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '51.457', 'enterprice': '29884.4', 'countrevence': '0', 'unrealprofit': '-24118.17413674669', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '29415.69459283', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'numpy.int64'>, curSign=1, self.sign=1


