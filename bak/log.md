# 20230515 08:26:01

## /root/FIL/strategy/amihud/log.txt ----- -----

127.0.0.1 - - [15/May/2023 08:20:00] "POST / HTTP/1.1" 200 -
--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=373746.4768026, self.flagDict['side']='sell', self.tradeCount=2, self.count=256
self.closeSec=1684109999, self.tradeDate='20230515', self.openTime='081500', self.closeTime='081959', self.symbol='BTCUSDT', self.open=26895.7, self.close=26789.9, self.high=26897.6, self.low=26694.4, self.vol=8505.103, self.amt=227740952.16302 
2023-05-15 08:20:00,382:INFO:amihud:main.py:172:handleKline:2219019: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5855  20230515   075500    075959  ...    0.528280   0.192996      -1
5856  20230515   080000    080459  ...    0.528076   0.193166      -1
5857  20230515   080500    080959  ...    0.527870   0.193334      -1
5858  20230515   081000    081459  ...    0.527669   0.193506      -1
5859  20230515   081500    081959  ...    0.527467   0.193677      -1

[5 rows x 18 columns]
2023-05-15 08:20:00,383:INFO:amihud:main.py:175:handleKline:2219019: self.closeSec=1684109999, self.tradeDate='20230515', self.openTime='081500', self.closeTime='081959',self.symbol='BTCUSDT',self.open=26895.7, self.close=26789.9, self.high=26897.6, self.low=26694.4, self.vol=8505.103, self.amt=227740952.16302, ukdf['pct'].iloc[-1]=-0.00393 , ukdf['amount'].iloc[-1]=227740952.16302, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5859, value=0.0, value_mean=0.5274667385134447, signal=-1, value_std=0.19367695185749859 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '13.926', 'enterprice': '26864.9', 'countrevence': '0', 'unrealprofit': '1043.0574', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '26790', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=-1, self.sign=-1
127.0.0.1 - - [15/May/2023 08:25:00] "POST / HTTP/1.1" 200 -
--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=373746.4768026, self.flagDict['side']='sell', self.tradeCount=2, self.count=257
self.closeSec=1684110299, self.tradeDate='20230515', self.openTime='082000', self.closeTime='082459', self.symbol='BTCUSDT', self.open=26790.0, self.close=26806.6, self.high=26814.2, self.low=26770.0, self.vol=1486.596, self.amt=39835373.7615 
2023-05-15 08:25:00,389:INFO:amihud:main.py:172:handleKline:2219019: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5856  20230515   080000    080459  ...    0.528076   0.193166      -1
5857  20230515   080500    080959  ...    0.527870   0.193334      -1
5858  20230515   081000    081459  ...    0.527669   0.193506      -1
5859  20230515   081500    081959  ...    0.527467   0.193677      -1
5860  20230515   082000    082459  ...    0.527265   0.193847      -1

[5 rows x 18 columns]
2023-05-15 08:25:00,398:INFO:amihud:main.py:175:handleKline:2219019: self.closeSec=1684110299, self.tradeDate='20230515', self.openTime='082000', self.closeTime='082459',self.symbol='BTCUSDT',self.open=26790.0, self.close=26806.6, self.high=26814.2, self.low=26770.0, self.vol=1486.596, self.amt=39835373.7615, ukdf['pct'].iloc[-1]=0.000623 , ukdf['amount'].iloc[-1]=39835373.7615, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5860, value=0.0, value_mean=0.5272645165722025, signal=-1, value_std=0.19384745062557027 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '13.926', 'enterprice': '26864.9', 'countrevence': '0', 'unrealprofit': '810.4932', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '26806.7', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=-1, self.sign=-1


## /root/FIL/strategy/factorcheck/log.txt ----- -----

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=42, self.factor=0.45581588138601126, self.count=258 

self.closeSec=1684109999, self.tradeDate='20230515', self.openTime='081500', self.closeTime='081959', self.symbol='BTCUSDT', self.open=26895.7, self.close=26789.9, self.high=26897.6, self.low=26694.4 
2023-05-15 08:20:00,352:INFO:factorcheck2:main.py:126:handleKline:2218005: self.closeSec=1684109999, self.tradeDate='20230515', self.openTime='081500', self.closeTime='081959',self.symbol='BTCUSDT',self.open=26895.7, self.close=26789.9, self.high=26897.6, self.low=26694.4   
2023-05-15 08:20:00,420:INFO:factorcheck2:main.py:127:handleKline:2218005: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime    closeSec  ...      low       pct  index  idx
1534  20230515   075500    075959  1684108799  ...  26897.3  0.000167   1534    4
1535  20230515   080000    080459  1684109099  ...  26899.5  0.000587   1535    5
1536  20230515   080500    080959  1684109399  ...  26884.5 -0.000977   1536    0
1537  20230515   081000    081459  1684109699  ...  26876.3  0.000156   1537    1
1538  20230515   081500    081959  1684109999  ...  26694.4 -0.003930   1538    2

[5 rows x 11 columns]
2023-05-15 08:20:00,420:INFO:factorcheck2:main.py:128:handleKline:2218005: self.flagDict={'side': '', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': False, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}
127.0.0.1 - - [15/May/2023 08:25:00] "POST / HTTP/1.1" 200 -

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=42, self.factor=0.45581588138601126, self.count=259 

self.closeSec=1684110299, self.tradeDate='20230515', self.openTime='082000', self.closeTime='082459', self.symbol='BTCUSDT', self.open=26790.0, self.close=26806.6, self.high=26814.2, self.low=26770.0 
2023-05-15 08:25:00,367:INFO:factorcheck2:main.py:126:handleKline:2218005: self.closeSec=1684110299, self.tradeDate='20230515', self.openTime='082000', self.closeTime='082459',self.symbol='BTCUSDT',self.open=26790.0, self.close=26806.6, self.high=26814.2, self.low=26770.0   
2023-05-15 08:25:00,379:INFO:factorcheck2:main.py:127:handleKline:2218005: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime    closeSec  ...      low       pct  index  idx
1535  20230515   080000    080459  1684109099  ...  26899.5  0.000587   1535    5
1536  20230515   080500    080959  1684109399  ...  26884.5 -0.000977   1536    0
1537  20230515   081000    081459  1684109699  ...  26876.3  0.000156   1537    1
1538  20230515   081500    081959  1684109999  ...  26694.4 -0.003930   1538    2
1539  20230515   082000    082459  1684110299  ...  26770.0  0.000623   1539    3

[5 rows x 11 columns]
2023-05-15 08:25:00,380:INFO:factorcheck2:main.py:128:handleKline:2218005: self.flagDict={'side': '', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': False, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}


## /root/FIL/strategy/logic/log.txt ----- -----

2023-05-15 08:00:16,189:DEBUG:logic:main.py:463:getModel:2218526: df_s.iloc[-5:,:] :
          date closeTime     open  ...    alpha58   alpha67   alpha72
5770  20230515    052959  26927.7  ...  51.666667  0.514530  0.438103
5771  20230515    055959  26902.9  ...  51.666667  0.512736  0.450068
5772  20230515    062959  26896.0  ...  52.083333  0.513848  0.462560
5773  20230515    065959  26900.4  ...  51.666667  0.510625  0.475950
5774  20230515    072959  26888.2  ...  51.250000  0.508410  0.489624

[5 rows x 33 columns]
0.5415896487985212
acc is : 0.5415896487985212
2023-05-15 08:00:16,253:INFO:logic:main.py:468:getModel:2218526: df_pred.iloc[-5:,:] :
     pred    prob_0    prob_1  actual  ...       nav  sign  cost_        bm
536     1  0.490154  0.509846       0  ...  1.024353   1.0    0.0  0.941654
537     1  0.499242  0.500758       1  ...  1.024525   1.0    0.0  0.941812
538     1  0.498882  0.501118       0  ...  1.024060   1.0    0.0  0.941384
539     1  0.494281  0.505719       0  ...  1.023744   1.0    0.0  0.941094
540     1  0.489513  0.510487       1  ...  1.024582   1.0    0.0  0.941864

[5 rows x 10 columns]
2023-05-15 08:00:16,264:INFO:logic:main.py:478:getModel:2218526: df_panel.iloc[-5:,:] :
    pred    prob_0    prob_1  actual  ...       nav  sign  cost_        bm
38     1  0.489911  0.510089       0  ...  1.024353   1.0    0.0  0.950630
39     1  0.499174  0.500826       1  ...  1.024525   1.0    0.0  0.946707
40     1  0.498742  0.501258       0  ...  1.024060   1.0    0.0  0.944616
41     1  0.494281  0.505719       0  ...  1.023744   1.0    0.0  0.941094
42     1  0.489513  0.510487       1  ...  1.024582   1.0    0.0  0.941864

[5 rows x 10 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '28.199', 'enterprice': '26801.5', 'countrevence': '0', 'unrealprofit': '2915.7766', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '26904.9', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}


## /root/FIL/strategy/modifiedmom/log.txt ----- -----

623  20230515   075000    075959  1684108799  26891.9  26901.9  0.000372
2023-05-15 08:00:00,388:INFO:modifiedmom:main.py:146:handleKline:2218259: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}
127.0.0.1 - - [15/May/2023 08:10:00] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=128 

self.closeSec=1684109399, self.tradeDate='20230515', self.openTime='080000', self.closeTime='080959', self.symbol='BTCUSDT', self.open='26901.9', self.close='26891.4'
2023-05-15 08:10:00,348:INFO:modifiedmom:main.py:144:handleKline:2218259: self.closeSec=1684109399, self.tradeDate='20230515', self.openTime='080000', self.closeTime='080959',self.symbol='BTCUSDT',self.open='26901.9', self.close='26891.4'
2023-05-15 08:10:00,365:INFO:modifiedmom:main.py:145:handleKline:2218259: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec     open    close       pct
620  20230515   072000    072959  1684106999  26861.5  26879.9  0.000681
621  20230515   073000    073959  1684107599    26880    26902  0.000822
622  20230515   074000    074959  1684108199    26902  26891.9 -0.000375
623  20230515   075000    075959  1684108799  26891.9  26901.9  0.000372
624  20230515   080000    080959  1684109399  26901.9  26891.4 -0.000390
2023-05-15 08:10:00,365:INFO:modifiedmom:main.py:146:handleKline:2218259: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}
127.0.0.1 - - [15/May/2023 08:20:00] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=129 

self.closeSec=1684109999, self.tradeDate='20230515', self.openTime='081000', self.closeTime='081959', self.symbol='BTCUSDT', self.open='26891.3', self.close='26789.9'
2023-05-15 08:20:00,352:INFO:modifiedmom:main.py:144:handleKline:2218259: self.closeSec=1684109999, self.tradeDate='20230515', self.openTime='081000', self.closeTime='081959',self.symbol='BTCUSDT',self.open='26891.3', self.close='26789.9'
2023-05-15 08:20:00,410:INFO:modifiedmom:main.py:145:handleKline:2218259: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec     open    close       pct
621  20230515   073000    073959  1684107599    26880    26902  0.000822
622  20230515   074000    074959  1684108199    26902  26891.9 -0.000375
623  20230515   075000    075959  1684108799  26891.9  26901.9  0.000372
624  20230515   080000    080959  1684109399  26901.9  26891.4 -0.000390
625  20230515   081000    081959  1684109999  26891.3  26789.9 -0.003774
2023-05-15 08:20:00,410:INFO:modifiedmom:main.py:146:handleKline:2218259: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}


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

17471  20230515   075000    075959  1684108799  26891.9  26901.9
2023-05-15 08:00:00,400:INFO:pyemd2:main.py:127:handleKline:2217508: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}
127.0.0.1 - - [15/May/2023 08:10:00] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=131 

self.closeSec=1684109399, self.tradeDate='20230515', self.openTime='080000', self.closeTime='080959', self.symbol='BTCUSDT', self.open='26901.9', self.close='26891.4'
2023-05-15 08:10:00,356:INFO:pyemd2:main.py:125:handleKline:2217508: self.closeSec=1684109399, self.tradeDate='20230515', self.openTime='080000', self.closeTime='080959',self.symbol='BTCUSDT',self.open='26901.9', self.close='26891.4'
2023-05-15 08:10:00,368:INFO:pyemd2:main.py:126:handleKline:2217508: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
17468  20230515   072000    072959  1684106999  26861.5  26879.9
17469  20230515   073000    073959  1684107599    26880    26902
17470  20230515   074000    074959  1684108199    26902  26891.9
17471  20230515   075000    075959  1684108799  26891.9  26901.9
17472  20230515   080000    080959  1684109399  26901.9  26891.4
2023-05-15 08:10:00,368:INFO:pyemd2:main.py:127:handleKline:2217508: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}
127.0.0.1 - - [15/May/2023 08:20:00] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=132 

self.closeSec=1684109999, self.tradeDate='20230515', self.openTime='081000', self.closeTime='081959', self.symbol='BTCUSDT', self.open='26891.3', self.close='26789.9'
2023-05-15 08:20:00,375:INFO:pyemd2:main.py:125:handleKline:2217508: self.closeSec=1684109999, self.tradeDate='20230515', self.openTime='081000', self.closeTime='081959',self.symbol='BTCUSDT',self.open='26891.3', self.close='26789.9'
2023-05-15 08:20:00,409:INFO:pyemd2:main.py:126:handleKline:2217508: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
17469  20230515   073000    073959  1684107599    26880    26902
17470  20230515   074000    074959  1684108199    26902  26891.9
17471  20230515   075000    075959  1684108799  26891.9  26901.9
17472  20230515   080000    080959  1684109399  26901.9  26891.4
17473  20230515   081000    081959  1684109999  26891.3  26789.9
2023-05-15 08:20:00,409:INFO:pyemd2:main.py:127:handleKline:2217508: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}


## /root/FIL/strategy/similarity/log.txt ----- -----

12143  20230515   075000    075959  1684108799  26891.9  26901.9
2023-05-15 08:00:00,367:INFO:testStrategy:main.py:103:handleKline:2217133: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': True, 'isOpenSell': False, 'isCloseBuy': False, 'isCloseSell': False, 'isOpen': True, 'isClose': False, 'isTrig': True, 'isCorr': False}
127.0.0.1 - - [15/May/2023 08:10:00] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=131 

self.closeSec=1684109399, self.tradeDate='20230515', self.openTime='080000', self.closeTime='080959', self.symbol='BTCUSDT', self.open='26901.9', self.close='26891.4'
2023-05-15 08:10:00,391:INFO:testStrategy:main.py:101:handleKline:2217133: self.closeSec=1684109399, self.tradeDate='20230515', self.openTime='080000', self.closeTime='080959',self.symbol='BTCUSDT',self.open='26901.9', self.close='26891.4'
2023-05-15 08:10:00,405:INFO:testStrategy:main.py:102:handleKline:2217133: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
12140  20230515   072000    072959  1684106999  26861.5  26879.9
12141  20230515   073000    073959  1684107599    26880    26902
12142  20230515   074000    074959  1684108199    26902  26891.9
12143  20230515   075000    075959  1684108799  26891.9  26901.9
12144  20230515   080000    080959  1684109399  26901.9  26891.4
2023-05-15 08:10:00,410:INFO:testStrategy:main.py:103:handleKline:2217133: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': True, 'isOpenSell': False, 'isCloseBuy': False, 'isCloseSell': False, 'isOpen': True, 'isClose': False, 'isTrig': True, 'isCorr': False}
127.0.0.1 - - [15/May/2023 08:20:00] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=132 

self.closeSec=1684109999, self.tradeDate='20230515', self.openTime='081000', self.closeTime='081959', self.symbol='BTCUSDT', self.open='26891.3', self.close='26789.9'
2023-05-15 08:20:00,373:INFO:testStrategy:main.py:101:handleKline:2217133: self.closeSec=1684109999, self.tradeDate='20230515', self.openTime='081000', self.closeTime='081959',self.symbol='BTCUSDT',self.open='26891.3', self.close='26789.9'
2023-05-15 08:20:00,411:INFO:testStrategy:main.py:102:handleKline:2217133: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
12141  20230515   073000    073959  1684107599    26880    26902
12142  20230515   074000    074959  1684108199    26902  26891.9
12143  20230515   075000    075959  1684108799  26891.9  26901.9
12144  20230515   080000    080959  1684109399  26901.9  26891.4
12145  20230515   081000    081959  1684109999  26891.3  26789.9
2023-05-15 08:20:00,411:INFO:testStrategy:main.py:103:handleKline:2217133: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': True, 'isOpenSell': False, 'isCloseBuy': False, 'isCloseSell': False, 'isOpen': True, 'isClose': False, 'isTrig': True, 'isCorr': False}


## /root/FIL/strategy/sr_min/log.txt ----- -----

--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=1, self.total=996015.990996, self.flagDict['side']='buy', self.tradeCount=1, self.count=256
self.closeSec=1684109999, self.tradeDate='20230515', self.openTime='081500', self.closeTime='081959', self.symbol='BTCUSDT', self.open=26895.7, self.close=26789.9, self.high=26897.6, self.low=26694.4, self.vol=8505.103, self.amt=227740952.16302 
127.0.0.1 - - [15/May/2023 08:20:00] "POST / HTTP/1.1" 200 -
2023-05-15 08:20:00,430:INFO:sr_min:main.py:172:handleKline:2219263: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5855  20230515   075500    075959  ...    0.486294   0.169853       0
5856  20230515   080000    080459  ...    0.486083   0.170205       0
5857  20230515   080500    080959  ...    0.485880   0.170552       0
5858  20230515   081000    081459  ...    0.485680   0.170896       0
5859  20230515   081500    081959  ...    0.485475   0.171242       0

[5 rows x 18 columns]
2023-05-15 08:20:00,430:INFO:sr_min:main.py:175:handleKline:2219263: self.closeSec=1684109999, self.tradeDate='20230515', self.openTime='081500', self.closeTime='081959',self.symbol='BTCUSDT',self.open=26895.7, self.close=26789.9, self.high=26897.6, self.low=26694.4, self.vol=8505.103, self.amt=227740952.16302, ukdf['pct'].iloc[-1]=-0.00393 , ukdf['amount'].iloc[-1]=227740952.16302, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5859, value=0.0, value_mean=0.48547461704070755, signal=0, value_std=0.17124229241065328 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '37.141', 'enterprice': '26844', 'countrevence': '0', 'unrealprofit': '-2005.614', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '26790', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=1
127.0.0.1 - - [15/May/2023 08:25:00] "POST / HTTP/1.1" 200 -
--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=1, self.total=996015.990996, self.flagDict['side']='buy', self.tradeCount=1, self.count=257
self.closeSec=1684110299, self.tradeDate='20230515', self.openTime='082000', self.closeTime='082459', self.symbol='BTCUSDT', self.open=26790.0, self.close=26806.6, self.high=26814.2, self.low=26770.0, self.vol=1486.596, self.amt=39835373.7615 
2023-05-15 08:25:00,396:INFO:sr_min:main.py:172:handleKline:2219263: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5856  20230515   080000    080459  ...    0.486083   0.170205       0
5857  20230515   080500    080959  ...    0.485880   0.170552       0
5858  20230515   081000    081459  ...    0.485680   0.170896       0
5859  20230515   081500    081959  ...    0.485475   0.171242       0
5860  20230515   082000    082459  ...    0.485269   0.171588       0

[5 rows x 18 columns]
2023-05-15 08:25:00,397:INFO:sr_min:main.py:175:handleKline:2219263: self.closeSec=1684110299, self.tradeDate='20230515', self.openTime='082000', self.closeTime='082459',self.symbol='BTCUSDT',self.open=26790.0, self.close=26806.6, self.high=26814.2, self.low=26770.0, self.vol=1486.596, self.amt=39835373.7615, ukdf['pct'].iloc[-1]=0.000623 , ukdf['amount'].iloc[-1]=39835373.7615, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5860, value=0.0, value_mean=0.4852689328371783, signal=0, value_std=0.17158776710507975 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '37.141', 'enterprice': '26844', 'countrevence': '0', 'unrealprofit': '-1385.3593', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '26806.7', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=1


## /root/FIL/strategy/s_rsrs/log.txt ----- -----

719  20230514   200000    235959  1684079999  ...    719  0.492854  0.222064     NaN
720  20230515   000000    035959  1684094399  ...    720  0.333023 -0.499666     NaN

[5 rows x 15 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '52.436', 'enterprice': '26818.7', 'countrevence': '0', 'unrealprofit': '-2498.76684278728', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '26866.35365098', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'numpy.int64'>, curSign=-9223372036854775808, self.sign=-1
127.0.0.1 - - [15/May/2023 08:00:00] "POST / HTTP/1.1" 200 -
--handleKline--:  version='2.0.0', self.name='s_rsrs', self.symbol='BTCUSDT', interval='4h', intervalSec=14400, wid=25, thd=0.6, self.sign=-1, self.total=6897.9369698, self.flagDict['side']='', self.tradeCount=0, self.count=5
self.closeSec=1684108799, self.tradeDate='20230515', self.openTime='040000', self.closeTime='075959', self.symbol='BTCUSDT', self.open=26865.0, self.close=26901.9, self.high=26947.2, self.low=26826.6, self.vol=21451.127, self.amt=576867827.8844 
2023-05-15 08:00:00,365:INFO:s_rsrs:main.py:141:handleKline:2218689: self.closeSec=1684108799, self.tradeDate='20230515', self.openTime='040000', self.closeTime='075959',self.symbol='BTCUSDT',self.open=26865.0, self.close=26901.9, self.high=26947.2, self.low=26826.6, self.vol=21451.127, self.amt=576867827.8844 
2023-05-15 08:00:00,407:INFO:s_rsrs:main.py:142:handleKline:2218689: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime  ...        vol           amt       pct
717  20230514   120000    155959  ...  20315.573  5.451243e+08 -0.000473
718  20230514   160000    195959  ...  18182.978  4.876535e+08 -0.001680
719  20230514   200000    235959  ...  86298.935  2.327455e+09  0.010323
720  20230515   000000    035959  ...  53779.117  1.448718e+09 -0.007624
721  20230515   040000    075959  ...  21451.127  5.768678e+08  0.001374

[5 rows x 11 columns]
2023-05-15 08:00:01,197:INFO:s_rsrs:main.py:151:handleKline:2218689: df_s.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec  ...  index      beta    zscore  signal
717  20230514   120000    155959  1684051199  ...    717  0.480029  0.185044     NaN
718  20230514   160000    195959  1684065599  ...    718  0.480727  0.180878     NaN
719  20230514   200000    235959  1684079999  ...    719  0.492854  0.222064     NaN
720  20230515   000000    035959  1684094399  ...    720  0.333023 -0.499666     NaN
721  20230515   040000    075959  1684108799  ...    721  0.488492  0.175305     NaN

[5 rows x 15 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '52.436', 'enterprice': '26818.7', 'countrevence': '0', 'unrealprofit': '-4485.9198620136', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '26904.2503826', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'numpy.int64'>, curSign=-9223372036854775808, self.sign=-1


