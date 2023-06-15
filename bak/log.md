# 20230615 08:26:02

## /root/FIL/strategy/amihud/log.txt ----- -----

--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=373746.4768026, self.flagDict['side']='sell', self.tradeCount=2, self.count=9184
self.closeSec=1686788399, self.tradeDate='20230615', self.openTime='081500', self.closeTime='081959', self.symbol='BTCUSDT', self.open=25115.7, self.close=25132.9, self.high=25137.0, self.low=25092.1, self.vol=1412.004, self.amt=35469568.147 
127.0.0.1 - - [15/Jun/2023 08:20:01] "POST / HTTP/1.1" 200 -
2023-06-15 08:20:07,791:INFO:amihud:main.py:172:handleKline:2219019: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5855  20230615   075500    075959  ...         0.0        0.0       0
5856  20230615   080000    080459  ...         0.0        0.0       0
5857  20230615   080500    080959  ...         0.0        0.0       0
5858  20230615   081000    081459  ...         0.0        0.0       0
5859  20230615   081500    081959  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-06-15 08:20:07,811:INFO:amihud:main.py:175:handleKline:2219019: self.closeSec=1686788399, self.tradeDate='20230615', self.openTime='081500', self.closeTime='081959',self.symbol='BTCUSDT',self.open=25115.7, self.close=25132.9, self.high=25137.0, self.low=25092.1, self.vol=1412.004, self.amt=35469568.147, ukdf['pct'].iloc[-1]=0.000685 , ukdf['amount'].iloc[-1]=35469568.147, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5859, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '13.926', 'enterprice': '26864.9', 'countrevence': '0', 'unrealprofit': '24118.4394', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '25133', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1
127.0.0.1 - - [15/Jun/2023 08:25:00] "POST / HTTP/1.1" 200 -
--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=373746.4768026, self.flagDict['side']='sell', self.tradeCount=2, self.count=9185
self.closeSec=1686788699, self.tradeDate='20230615', self.openTime='082000', self.closeTime='082459', self.symbol='BTCUSDT', self.open=25132.9, self.close=25132.8, self.high=25135.0, self.low=25126.2, self.vol=772.82, self.amt=19421357.2988 
2023-06-15 08:25:00,792:INFO:amihud:main.py:172:handleKline:2219019: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5856  20230615   080000    080459  ...         0.0        0.0       0
5857  20230615   080500    080959  ...         0.0        0.0       0
5858  20230615   081000    081459  ...         0.0        0.0       0
5859  20230615   081500    081959  ...         0.0        0.0       0
5860  20230615   082000    082459  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-06-15 08:25:00,792:INFO:amihud:main.py:175:handleKline:2219019: self.closeSec=1686788699, self.tradeDate='20230615', self.openTime='082000', self.closeTime='082459',self.symbol='BTCUSDT',self.open=25132.9, self.close=25132.8, self.high=25135.0, self.low=25126.2, self.vol=772.82, self.amt=19421357.2988, ukdf['pct'].iloc[-1]=-4e-06 , ukdf['amount'].iloc[-1]=19421357.2988, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5860, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '13.926', 'enterprice': '26864.9', 'countrevence': '0', 'unrealprofit': '24119.832', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '25132.9', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1


## /root/FIL/strategy/factorcheck/log.txt ----- -----


self.closeSec=1686788399, self.tradeDate='20230615', self.openTime='081500', self.closeTime='081959', self.symbol='BTCUSDT', self.open=25115.7, self.close=25132.9, self.high=25137.0, self.low=25092.1 
127.0.0.1 - - [15/Jun/2023 08:20:01] "POST / HTTP/1.1" 200 -
2023-06-15 08:20:05,041:INFO:factorcheck2:main.py:126:handleKline:2218005: self.closeSec=1686788399, self.tradeDate='20230615', self.openTime='081500', self.closeTime='081959',self.symbol='BTCUSDT',self.open=25115.7, self.close=25132.9, self.high=25137.0, self.low=25092.1   
2023-06-15 08:20:06,671:INFO:factorcheck2:main.py:127:handleKline:2218005: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime    closeSec  ...      low       pct  index  idx
1535  20230615   075500    075959  1686787199  ...  25103.0  0.000275   1535    5
1536  20230615   080000    080459  1686787499  ...  25079.5 -0.001210   1536    0
1537  20230615   080500    080959  1686787799  ...  25071.0  0.000395   1537    1
1538  20230615   081000    081459  1686788099  ...  25096.3  0.000805   1538    2
1539  20230615   081500    081959  1686788399  ...  25092.1  0.000685   1539    3

[5 rows x 11 columns]
2023-06-15 08:20:06,680:INFO:factorcheck2:main.py:128:handleKline:2218005: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}
127.0.0.1 - - [15/Jun/2023 08:25:00] "POST / HTTP/1.1" 200 -

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=122, self.factor=0.5407750444660282, self.count=9187 

self.closeSec=1686788699, self.tradeDate='20230615', self.openTime='082000', self.closeTime='082459', self.symbol='BTCUSDT', self.open=25132.9, self.close=25132.8, self.high=25135.0, self.low=25126.2 
2023-06-15 08:25:00,729:INFO:factorcheck2:main.py:126:handleKline:2218005: self.closeSec=1686788699, self.tradeDate='20230615', self.openTime='082000', self.closeTime='082459',self.symbol='BTCUSDT',self.open=25132.9, self.close=25132.8, self.high=25135.0, self.low=25126.2   
2023-06-15 08:25:00,768:INFO:factorcheck2:main.py:127:handleKline:2218005: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime    closeSec  ...      low       pct  index  idx
1536  20230615   080000    080459  1686787499  ...  25079.5 -0.001210   1536    0
1537  20230615   080500    080959  1686787799  ...  25071.0  0.000395   1537    1
1538  20230615   081000    081459  1686788099  ...  25096.3  0.000805   1538    2
1539  20230615   081500    081959  1686788399  ...  25092.1  0.000685   1539    3
1540  20230615   082000    082459  1686788699  ...  25126.2 -0.000004   1540    4

[5 rows x 11 columns]
2023-06-15 08:25:00,768:INFO:factorcheck2:main.py:128:handleKline:2218005: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}


## /root/FIL/strategy/logic/log.txt ----- -----

2023-06-15 08:00:22,104:DEBUG:logic:main.py:463:getModel:2218526: df_s.iloc[-5:,:] :
          date closeTime     open  ...    alpha58   alpha67   alpha72
5770  20230615    052959  24920.1  ...  47.916667  0.343849  0.541284
5771  20230615    055959  25069.7  ...  47.916667  0.352456  0.556101
5772  20230615    062959  25104.8  ...  47.916667  0.345112  0.572786
5773  20230615    065959  25049.5  ...  47.500000  0.341341  0.589842
5774  20230615    072959  25020.1  ...  47.916667  0.352251  0.603520

[5 rows x 33 columns]
0.5286506469500925
acc is : 0.5286506469500925
2023-06-15 08:00:22,198:INFO:logic:main.py:468:getModel:2218526: df_pred.iloc[-5:,:] :
     pred    prob_0    prob_1  actual  ...       nav  sign  cost_        bm
536     1  0.454750  0.545250       1  ...  1.036863  -1.0    0.0  0.924136
537     1  0.438992  0.561008       0  ...  1.039168  -1.0    0.0  0.922082
538     1  0.421412  0.578588       0  ...  1.040371  -1.0    0.0  0.921014
539     1  0.452554  0.547446       1  ...  1.038550  -1.0    0.0  0.922627
540     0  0.525100  0.474900       1  ...  1.036387  -1.0    0.0  0.924548

[5 rows x 10 columns]
2023-06-15 08:00:22,211:INFO:logic:main.py:478:getModel:2218526: df_panel.iloc[-5:,:] :
    pred    prob_0    prob_1  actual  ...       nav  sign  cost_        bm
45     1  0.455298  0.544702       1  ...  1.036863  -1.0    0.0  0.919836
46     1  0.439681  0.560319       0  ...  1.107205  -1.0    0.0  0.917526
47     1  0.422080  0.577920       0  ...  1.040371  -1.0    0.0  0.918519
48     1  0.452914  0.547086       1  ...  1.038550  -1.0    0.0  0.922627
49     0  0.525100  0.474900       1  ...  1.036387  -1.0    0.0  0.924548

[5 rows x 10 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '27.898', 'enterprice': '25555.4', 'countrevence': '0', 'unrealprofit': '12784.41729374212', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '25097.14430806', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}


## /root/FIL/strategy/modifiedmom/log.txt ----- -----

623  20230615   075000    075959  1686787199  25122.8  25115.9 -0.000163
2023-06-15 08:00:02,376:INFO:modifiedmom:main.py:146:handleKline:2218259: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': True, 'isOpen': False, 'isClose': True, 'isTrig': False}
127.0.0.1 - - [15/Jun/2023 08:10:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=4592 

self.closeSec=1686787799, self.tradeDate='20230615', self.openTime='080000', self.closeTime='080959', self.symbol='BTCUSDT', self.open='25115.9', self.close='25095.5'
2023-06-15 08:10:01,096:INFO:modifiedmom:main.py:144:handleKline:2218259: self.closeSec=1686787799, self.tradeDate='20230615', self.openTime='080000', self.closeTime='080959',self.symbol='BTCUSDT',self.open='25115.9', self.close='25095.5'
2023-06-15 08:10:01,118:INFO:modifiedmom:main.py:145:handleKline:2218259: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec     open    close       pct
620  20230615   072000    072959  1686785399  25071.3  25063.8 -0.000295
621  20230615   073000    073959  1686785999  25063.8  25085.7  0.000874
622  20230615   074000    074959  1686786599  25085.7    25120  0.001367
623  20230615   075000    075959  1686787199  25122.8  25115.9 -0.000163
624  20230615   080000    080959  1686787799  25115.9  25095.5 -0.000812
2023-06-15 08:10:01,118:INFO:modifiedmom:main.py:146:handleKline:2218259: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': True, 'isOpen': False, 'isClose': True, 'isTrig': False}

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=4593 

self.closeSec=1686788399, self.tradeDate='20230615', self.openTime='081000', self.closeTime='081959', self.symbol='BTCUSDT', self.open='25097.6', self.close='25132.9'
127.0.0.1 - - [15/Jun/2023 08:20:04] "POST / HTTP/1.1" 200 -
2023-06-15 08:20:07,730:INFO:modifiedmom:main.py:144:handleKline:2218259: self.closeSec=1686788399, self.tradeDate='20230615', self.openTime='081000', self.closeTime='081959',self.symbol='BTCUSDT',self.open='25097.6', self.close='25132.9'
2023-06-15 08:20:08,591:INFO:modifiedmom:main.py:145:handleKline:2218259: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec     open    close       pct
621  20230615   073000    073959  1686785999  25063.8  25085.7  0.000874
622  20230615   074000    074959  1686786599  25085.7    25120  0.001367
623  20230615   075000    075959  1686787199  25122.8  25115.9 -0.000163
624  20230615   080000    080959  1686787799  25115.9  25095.5 -0.000812
625  20230615   081000    081959  1686788399  25097.6  25132.9  0.001490
2023-06-15 08:20:08,601:INFO:modifiedmom:main.py:146:handleKline:2218259: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': True, 'isOpen': False, 'isClose': True, 'isTrig': False}


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

17471  20230615   075000    075959  1686787199  25122.8  25115.9
2023-06-15 08:00:02,392:INFO:pyemd2:main.py:127:handleKline:2217508: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=4595 

self.closeSec=1686787799, self.tradeDate='20230615', self.openTime='080000', self.closeTime='080959', self.symbol='BTCUSDT', self.open='25115.9', self.close='25095.5'
2023-06-15 08:10:01,107:INFO:pyemd2:main.py:125:handleKline:2217508: self.closeSec=1686787799, self.tradeDate='20230615', self.openTime='080000', self.closeTime='080959',self.symbol='BTCUSDT',self.open='25115.9', self.close='25095.5'
127.0.0.1 - - [15/Jun/2023 08:10:01] "POST / HTTP/1.1" 200 -
2023-06-15 08:10:01,121:INFO:pyemd2:main.py:126:handleKline:2217508: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
17468  20230615   072000    072959  1686785399  25071.3  25063.8
17469  20230615   073000    073959  1686785999  25063.8  25085.7
17470  20230615   074000    074959  1686786599  25085.7    25120
17471  20230615   075000    075959  1686787199  25122.8  25115.9
17472  20230615   080000    080959  1686787799  25115.9  25095.5
2023-06-15 08:10:01,121:INFO:pyemd2:main.py:127:handleKline:2217508: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=4596 

self.closeSec=1686788399, self.tradeDate='20230615', self.openTime='081000', self.closeTime='081959', self.symbol='BTCUSDT', self.open='25097.6', self.close='25132.9'
127.0.0.1 - - [15/Jun/2023 08:20:05] "POST / HTTP/1.1" 200 -
2023-06-15 08:20:09,684:INFO:pyemd2:main.py:125:handleKline:2217508: self.closeSec=1686788399, self.tradeDate='20230615', self.openTime='081000', self.closeTime='081959',self.symbol='BTCUSDT',self.open='25097.6', self.close='25132.9'
2023-06-15 08:20:09,847:INFO:pyemd2:main.py:126:handleKline:2217508: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
17469  20230615   073000    073959  1686785999  25063.8  25085.7
17470  20230615   074000    074959  1686786599  25085.7    25120
17471  20230615   075000    075959  1686787199  25122.8  25115.9
17472  20230615   080000    080959  1686787799  25115.9  25095.5
17473  20230615   081000    081959  1686788399  25097.6  25132.9
2023-06-15 08:20:09,848:INFO:pyemd2:main.py:127:handleKline:2217508: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}


## /root/FIL/strategy/similarity/log.txt ----- -----

12143  20230615   075000    075959  1686787199  25122.8  25115.9
2023-06-15 08:00:02,341:INFO:testStrategy:main.py:103:handleKline:2217133: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': True, 'isOpenSell': False, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True, 'isCorr': False}
127.0.0.1 - - [15/Jun/2023 08:10:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=4595 

self.closeSec=1686787799, self.tradeDate='20230615', self.openTime='080000', self.closeTime='080959', self.symbol='BTCUSDT', self.open='25115.9', self.close='25095.5'
2023-06-15 08:10:01,105:INFO:testStrategy:main.py:101:handleKline:2217133: self.closeSec=1686787799, self.tradeDate='20230615', self.openTime='080000', self.closeTime='080959',self.symbol='BTCUSDT',self.open='25115.9', self.close='25095.5'
2023-06-15 08:10:01,123:INFO:testStrategy:main.py:102:handleKline:2217133: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
12140  20230615   072000    072959  1686785399  25071.3  25063.8
12141  20230615   073000    073959  1686785999  25063.8  25085.7
12142  20230615   074000    074959  1686786599  25085.7    25120
12143  20230615   075000    075959  1686787199  25122.8  25115.9
12144  20230615   080000    080959  1686787799  25115.9  25095.5
2023-06-15 08:10:01,123:INFO:testStrategy:main.py:103:handleKline:2217133: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': True, 'isOpenSell': False, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True, 'isCorr': False}

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=4596 

self.closeSec=1686788399, self.tradeDate='20230615', self.openTime='081000', self.closeTime='081959', self.symbol='BTCUSDT', self.open='25097.6', self.close='25132.9'
127.0.0.1 - - [15/Jun/2023 08:20:04] "POST / HTTP/1.1" 200 -
2023-06-15 08:20:09,332:INFO:testStrategy:main.py:101:handleKline:2217133: self.closeSec=1686788399, self.tradeDate='20230615', self.openTime='081000', self.closeTime='081959',self.symbol='BTCUSDT',self.open='25097.6', self.close='25132.9'
2023-06-15 08:20:09,640:INFO:testStrategy:main.py:102:handleKline:2217133: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
12141  20230615   073000    073959  1686785999  25063.8  25085.7
12142  20230615   074000    074959  1686786599  25085.7    25120
12143  20230615   075000    075959  1686787199  25122.8  25115.9
12144  20230615   080000    080959  1686787799  25115.9  25095.5
12145  20230615   081000    081959  1686788399  25097.6  25132.9
2023-06-15 08:20:09,641:INFO:testStrategy:main.py:103:handleKline:2217133: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': True, 'isOpenSell': False, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True, 'isCorr': False}


## /root/FIL/strategy/sr_min/log.txt ----- -----

--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=1, self.total=996015.990996, self.flagDict['side']='buy', self.tradeCount=1, self.count=9184
self.closeSec=1686788399, self.tradeDate='20230615', self.openTime='081500', self.closeTime='081959', self.symbol='BTCUSDT', self.open=25115.7, self.close=25132.9, self.high=25137.0, self.low=25092.1, self.vol=1412.004, self.amt=35469568.147 
127.0.0.1 - - [15/Jun/2023 08:20:01] "POST / HTTP/1.1" 200 -
2023-06-15 08:20:07,790:INFO:sr_min:main.py:172:handleKline:2219263: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5855  20230615   075500    075959  ...         0.0        0.0       0
5856  20230615   080000    080459  ...         0.0        0.0       0
5857  20230615   080500    080959  ...         0.0        0.0       0
5858  20230615   081000    081459  ...         0.0        0.0       0
5859  20230615   081500    081959  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-06-15 08:20:07,812:INFO:sr_min:main.py:175:handleKline:2219263: self.closeSec=1686788399, self.tradeDate='20230615', self.openTime='081500', self.closeTime='081959',self.symbol='BTCUSDT',self.open=25115.7, self.close=25132.9, self.high=25137.0, self.low=25092.1, self.vol=1412.004, self.amt=35469568.147, ukdf['pct'].iloc[-1]=0.000685 , ukdf['amount'].iloc[-1]=35469568.147, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5859, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '37.141', 'enterprice': '26844', 'countrevence': '0', 'unrealprofit': '-63548.251', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '25133', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=1
--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=1, self.total=996015.990996, self.flagDict['side']='buy', self.tradeCount=1, self.count=9185
self.closeSec=1686788699, self.tradeDate='20230615', self.openTime='082000', self.closeTime='082459', self.symbol='BTCUSDT', self.open=25132.9, self.close=25132.8, self.high=25135.0, self.low=25126.2, self.vol=772.82, self.amt=19421357.2988 
127.0.0.1 - - [15/Jun/2023 08:25:00] "POST / HTTP/1.1" 200 -
2023-06-15 08:25:00,794:INFO:sr_min:main.py:172:handleKline:2219263: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5856  20230615   080000    080459  ...         0.0        0.0       0
5857  20230615   080500    080959  ...         0.0        0.0       0
5858  20230615   081000    081459  ...         0.0        0.0       0
5859  20230615   081500    081959  ...         0.0        0.0       0
5860  20230615   082000    082459  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-06-15 08:25:00,795:INFO:sr_min:main.py:175:handleKline:2219263: self.closeSec=1686788699, self.tradeDate='20230615', self.openTime='082000', self.closeTime='082459',self.symbol='BTCUSDT',self.open=25132.9, self.close=25132.8, self.high=25135.0, self.low=25126.2, self.vol=772.82, self.amt=19421357.2988, ukdf['pct'].iloc[-1]=-4e-06 , ukdf['amount'].iloc[-1]=19421357.2988, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5860, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '37.141', 'enterprice': '26844', 'countrevence': '0', 'unrealprofit': '-63551.9651', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '25132.9', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=1


## /root/FIL/strategy/s_rsrs/log.txt ----- -----

719  20230614   200000    235959  1686758399  ...    719  0.012297 -1.782169    -1.0
720  20230615   000000    035959  1686772799  ...    720  0.004196 -1.811403    -1.0

[5 rows x 15 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '55.166', 'enterprice': '27078.6', 'countrevence': '0', 'unrealprofit': '67207.79189507768', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '25860.31714652', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'numpy.int64'>, curSign=-1, self.sign=-1
127.0.0.1 - - [15/Jun/2023 08:00:01] "POST / HTTP/1.1" 200 -
--handleKline--:  version='2.0.0', self.name='s_rsrs', self.symbol='BTCUSDT', interval='4h', intervalSec=14400, wid=25, thd=0.6, self.sign=-1, self.total=1492324.2295523998, self.flagDict['side']='sell', self.tradeCount=4, self.count=191
self.closeSec=1686787199, self.tradeDate='20230615', self.openTime='040000', self.closeTime='075959', self.symbol='BTCUSDT', self.open=25860.5, self.close=25115.9, self.high=25872.9, self.low=24796.8, self.vol=225751.005, self.amt=5685133561.35406 
2023-06-15 08:00:01,907:INFO:s_rsrs:main.py:141:handleKline:2218689: self.closeSec=1686787199, self.tradeDate='20230615', self.openTime='040000', self.closeTime='075959',self.symbol='BTCUSDT',self.open=25860.5, self.close=25115.9, self.high=25872.9, self.low=24796.8, self.vol=225751.005, self.amt=5685133561.35406 
2023-06-15 08:00:01,937:INFO:s_rsrs:main.py:142:handleKline:2218689: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime  ...         vol           amt       pct
717  20230614   120000    155959  ...   30116.376  7.800111e+08 -0.003335
718  20230614   160000    195959  ...   28960.713  7.513646e+08  0.003210
719  20230614   200000    235959  ...   41580.783  1.080340e+09  0.000354
720  20230615   000000    035959  ...  105000.310  2.720728e+09 -0.004458
721  20230615   040000    075959  ...  225751.005  5.685134e+09 -0.028797

[5 rows x 11 columns]
2023-06-15 08:00:03,307:INFO:s_rsrs:main.py:151:handleKline:2218689: df_s.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec  ...  index      beta    zscore  signal
717  20230614   120000    155959  1686729599  ...    717  0.001596 -1.874697    -1.0
718  20230614   160000    195959  1686743999  ...    718  0.022247 -1.771563    -1.0
719  20230614   200000    235959  1686758399  ...    719  0.012297 -1.782169    -1.0
720  20230615   000000    035959  1686772799  ...    720  0.004196 -1.811403    -1.0
721  20230615   040000    075959  1686787199  ...    721  0.012039 -1.782105    -1.0

[5 rows x 15 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '55.166', 'enterprice': '27078.6', 'countrevence': '0', 'unrealprofit': '108203.26591010914', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '25117.18779121', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'numpy.int64'>, curSign=-1, self.sign=-1


