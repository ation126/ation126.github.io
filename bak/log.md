# 20230528 08:26:01

## /root/FIL/strategy/amihud/log.txt ----- -----

--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=373746.4768026, self.flagDict['side']='sell', self.tradeCount=2, self.count=4000
self.closeSec=1685233199, self.tradeDate='20230528', self.openTime='081500', self.closeTime='081959', self.symbol='BTCUSDT', self.open=26830.7, self.close=26780.0, self.high=26830.7, self.low=26746.0, self.vol=2190.808, self.amt=58676775.9584 
127.0.0.1 - - [28/May/2023 08:20:01] "POST / HTTP/1.1" 200 -
2023-05-28 08:20:06,634:INFO:amihud:main.py:172:handleKline:2219019: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5855  20230528   075500    075959  ...         0.0        0.0       0
5856  20230528   080000    080459  ...         0.0        0.0       0
5857  20230528   080500    080959  ...         0.0        0.0       0
5858  20230528   081000    081459  ...         0.0        0.0       0
5859  20230528   081500    081959  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-05-28 08:20:06,664:INFO:amihud:main.py:175:handleKline:2219019: self.closeSec=1685233199, self.tradeDate='20230528', self.openTime='081500', self.closeTime='081959',self.symbol='BTCUSDT',self.open=26830.7, self.close=26780.0, self.high=26830.7, self.low=26746.0, self.vol=2190.808, self.amt=58676775.9584, ukdf['pct'].iloc[-1]=-0.001886 , ukdf['amount'].iloc[-1]=58676775.9584, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5859, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '13.926', 'enterprice': '26864.9', 'countrevence': '0', 'unrealprofit': '1114.08', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '26784.9', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1
--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=373746.4768026, self.flagDict['side']='sell', self.tradeCount=2, self.count=4001
self.closeSec=1685233499, self.tradeDate='20230528', self.openTime='082000', self.closeTime='082459', self.symbol='BTCUSDT', self.open=26779.9, self.close=26809.9, self.high=26809.9, self.low=26778.4, self.vol=557.14, self.amt=14926914.3467 
127.0.0.1 - - [28/May/2023 08:25:00] "POST / HTTP/1.1" 200 -
2023-05-28 08:25:00,773:INFO:amihud:main.py:172:handleKline:2219019: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5856  20230528   080000    080459  ...         0.0        0.0       0
5857  20230528   080500    080959  ...         0.0        0.0       0
5858  20230528   081000    081459  ...         0.0        0.0       0
5859  20230528   081500    081959  ...         0.0        0.0       0
5860  20230528   082000    082459  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-05-28 08:25:00,773:INFO:amihud:main.py:175:handleKline:2219019: self.closeSec=1685233499, self.tradeDate='20230528', self.openTime='082000', self.closeTime='082459',self.symbol='BTCUSDT',self.open=26779.9, self.close=26809.9, self.high=26809.9, self.low=26778.4, self.vol=557.14, self.amt=14926914.3467, ukdf['pct'].iloc[-1]=0.001117 , ukdf['amount'].iloc[-1]=14926914.3467, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5860, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '13.926', 'enterprice': '26864.9', 'countrevence': '0', 'unrealprofit': '767.3226', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '26809.8', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1


## /root/FIL/strategy/factorcheck/log.txt ----- -----


self.closeSec=1685233199, self.tradeDate='20230528', self.openTime='081500', self.closeTime='081959', self.symbol='BTCUSDT', self.open=26830.7, self.close=26780.0, self.high=26830.7, self.low=26746.0 
127.0.0.1 - - [28/May/2023 08:20:01] "POST / HTTP/1.1" 200 -
2023-05-28 08:20:04,384:INFO:factorcheck2:main.py:126:handleKline:2218005: self.closeSec=1685233199, self.tradeDate='20230528', self.openTime='081500', self.closeTime='081959',self.symbol='BTCUSDT',self.open=26830.7, self.close=26780.0, self.high=26830.7, self.low=26746.0   
2023-05-28 08:20:05,383:INFO:factorcheck2:main.py:127:handleKline:2218005: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime    closeSec  ...      low       pct  index  idx
1535  20230528   075500    075959  1685231999  ...  26836.6  0.000108   1535    5
1536  20230528   080000    080459  1685232299  ...  26826.7 -0.000335   1536    0
1537  20230528   080500    080959  1685232599  ...  26821.5  0.000011   1537    1
1538  20230528   081000    081459  1685232899  ...  26827.8 -0.000089   1538    2
1539  20230528   081500    081959  1685233199  ...  26746.0 -0.001886   1539    3

[5 rows x 11 columns]
2023-05-28 08:20:05,384:INFO:factorcheck2:main.py:128:handleKline:2218005: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=67, self.factor=0.289461661533645, self.count=4003 

self.closeSec=1685233499, self.tradeDate='20230528', self.openTime='082000', self.closeTime='082459', self.symbol='BTCUSDT', self.open=26779.9, self.close=26809.9, self.high=26809.9, self.low=26778.4 
2023-05-28 08:25:00,704:INFO:factorcheck2:main.py:126:handleKline:2218005: self.closeSec=1685233499, self.tradeDate='20230528', self.openTime='082000', self.closeTime='082459',self.symbol='BTCUSDT',self.open=26779.9, self.close=26809.9, self.high=26809.9, self.low=26778.4   
127.0.0.1 - - [28/May/2023 08:25:00] "POST / HTTP/1.1" 200 -
2023-05-28 08:25:00,746:INFO:factorcheck2:main.py:127:handleKline:2218005: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime    closeSec  ...      low       pct  index  idx
1536  20230528   080000    080459  1685232299  ...  26826.7 -0.000335   1536    0
1537  20230528   080500    080959  1685232599  ...  26821.5  0.000011   1537    1
1538  20230528   081000    081459  1685232899  ...  26827.8 -0.000089   1538    2
1539  20230528   081500    081959  1685233199  ...  26746.0 -0.001886   1539    3
1540  20230528   082000    082459  1685233499  ...  26778.4  0.001117   1540    4

[5 rows x 11 columns]
2023-05-28 08:25:00,746:INFO:factorcheck2:main.py:128:handleKline:2218005: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}


## /root/FIL/strategy/logic/log.txt ----- -----

2023-05-28 08:00:31,770:DEBUG:logic:main.py:463:getModel:2218526: df_s.iloc[-5:,:] :
          date closeTime     open  ...    alpha58   alpha67   alpha72
5770  20230528    052959  26744.0  ...  46.250000  0.529522  0.413691
5771  20230528    055959  26725.3  ...  46.666667  0.540087  0.404270
5772  20230528    062959  26759.5  ...  47.083333  0.545915  0.391464
5773  20230528    065959  26778.5  ...  47.500000  0.549634  0.376946
5774  20230528    072959  26790.8  ...  47.916667  0.558231  0.357428

[5 rows x 33 columns]
0.5341959334565619
acc is : 0.5341959334565619
2023-05-28 08:00:31,912:INFO:logic:main.py:468:getModel:2218526: df_pred.iloc[-5:,:] :
     pred    prob_0    prob_1  actual  ...       nav  sign  cost_        bm
536     1  0.498396  0.501604       1  ...  0.908424   1.0    0.0  0.991592
537     0  0.505841  0.494159       1  ...  0.909072   1.0    0.0  0.992300
538     0  0.506547  0.493453       1  ...  0.909486   1.0    0.0  0.992752
539     0  0.505151  0.494849       1  ...  0.910451   1.0    0.0  0.993804
540     0  0.508865  0.491135       1  ...  0.911214   1.0    0.0  0.994638

[5 rows x 10 columns]
2023-05-28 08:00:31,950:INFO:logic:main.py:478:getModel:2218526: df_panel.iloc[-5:,:] :
    pred    prob_0    prob_1  actual  ...       nav  sign  cost_        bm
45     1  0.498465  0.501535       1  ...  0.908424   1.0    0.0  0.990066
46     0  0.506009  0.493991       1  ...  0.909072   1.0    0.0  0.991550
47     0  0.506351  0.493649       1  ...  0.909486   1.0    0.0  0.990648
48     0  0.505379  0.494621       1  ...  0.910451   1.0    0.0  0.993804
49     0  0.508865  0.491135       1  ...  0.911214   1.0    0.0  0.994638

[5 rows x 10 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '25.918', 'enterprice': '26792.4', 'countrevence': '0', 'unrealprofit': '1601.7324', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '26854.2', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}


## /root/FIL/strategy/modifiedmom/log.txt ----- -----

623  20230528   075000    075959  1685231999  26829.2  26841.6  0.000462
2023-05-28 08:00:02,174:INFO:modifiedmom:main.py:146:handleKline:2218259: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': True, 'isOpen': False, 'isClose': True, 'isTrig': False}

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=2000 

self.closeSec=1685232599, self.tradeDate='20230528', self.openTime='080000', self.closeTime='080959', self.symbol='BTCUSDT', self.open='26841.6', self.close='26832.9'
2023-05-28 08:10:01,070:INFO:modifiedmom:main.py:144:handleKline:2218259: self.closeSec=1685232599, self.tradeDate='20230528', self.openTime='080000', self.closeTime='080959',self.symbol='BTCUSDT',self.open='26841.6', self.close='26832.9'
127.0.0.1 - - [28/May/2023 08:10:01] "POST / HTTP/1.1" 200 -
2023-05-28 08:10:01,086:INFO:modifiedmom:main.py:145:handleKline:2218259: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec     open    close       pct
620  20230528   072000    072959  1685230199  26805.7  26819.1  0.000500
621  20230528   073000    073959  1685230799  26819.2  26825.4  0.000235
622  20230528   074000    074959  1685231399  26825.4  26829.2  0.000142
623  20230528   075000    075959  1685231999  26829.2  26841.6  0.000462
624  20230528   080000    080959  1685232599  26841.6  26832.9 -0.000324
2023-05-28 08:10:01,086:INFO:modifiedmom:main.py:146:handleKline:2218259: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': True, 'isOpen': False, 'isClose': True, 'isTrig': False}

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=2001 

self.closeSec=1685233199, self.tradeDate='20230528', self.openTime='081000', self.closeTime='081959', self.symbol='BTCUSDT', self.open='26833', self.close='26780'
127.0.0.1 - - [28/May/2023 08:20:04] "POST / HTTP/1.1" 200 -
2023-05-28 08:20:06,614:INFO:modifiedmom:main.py:144:handleKline:2218259: self.closeSec=1685233199, self.tradeDate='20230528', self.openTime='081000', self.closeTime='081959',self.symbol='BTCUSDT',self.open='26833', self.close='26780'
2023-05-28 08:20:07,434:INFO:modifiedmom:main.py:145:handleKline:2218259: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec     open    close       pct
621  20230528   073000    073959  1685230799  26819.2  26825.4  0.000235
622  20230528   074000    074959  1685231399  26825.4  26829.2  0.000142
623  20230528   075000    075959  1685231999  26829.2  26841.6  0.000462
624  20230528   080000    080959  1685232599  26841.6  26832.9 -0.000324
625  20230528   081000    081959  1685233199    26833    26780 -0.001971
2023-05-28 08:20:07,443:INFO:modifiedmom:main.py:146:handleKline:2218259: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': True, 'isOpen': False, 'isClose': True, 'isTrig': False}


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

17471  20230528   075000    075959  1685231999  26829.2  26841.6
2023-05-28 08:00:02,194:INFO:pyemd2:main.py:127:handleKline:2217508: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=2003 

self.closeSec=1685232599, self.tradeDate='20230528', self.openTime='080000', self.closeTime='080959', self.symbol='BTCUSDT', self.open='26841.6', self.close='26832.9'
2023-05-28 08:10:01,095:INFO:pyemd2:main.py:125:handleKline:2217508: self.closeSec=1685232599, self.tradeDate='20230528', self.openTime='080000', self.closeTime='080959',self.symbol='BTCUSDT',self.open='26841.6', self.close='26832.9'
127.0.0.1 - - [28/May/2023 08:10:01] "POST / HTTP/1.1" 200 -
2023-05-28 08:10:01,117:INFO:pyemd2:main.py:126:handleKline:2217508: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
17468  20230528   072000    072959  1685230199  26805.7  26819.1
17469  20230528   073000    073959  1685230799  26819.2  26825.4
17470  20230528   074000    074959  1685231399  26825.4  26829.2
17471  20230528   075000    075959  1685231999  26829.2  26841.6
17472  20230528   080000    080959  1685232599  26841.6  26832.9
2023-05-28 08:10:01,117:INFO:pyemd2:main.py:127:handleKline:2217508: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=2004 

self.closeSec=1685233199, self.tradeDate='20230528', self.openTime='081000', self.closeTime='081959', self.symbol='BTCUSDT', self.open='26833', self.close='26780'
127.0.0.1 - - [28/May/2023 08:20:04] "POST / HTTP/1.1" 200 -
2023-05-28 08:20:08,486:INFO:pyemd2:main.py:125:handleKline:2217508: self.closeSec=1685233199, self.tradeDate='20230528', self.openTime='081000', self.closeTime='081959',self.symbol='BTCUSDT',self.open='26833', self.close='26780'
2023-05-28 08:20:08,615:INFO:pyemd2:main.py:126:handleKline:2217508: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
17469  20230528   073000    073959  1685230799  26819.2  26825.4
17470  20230528   074000    074959  1685231399  26825.4  26829.2
17471  20230528   075000    075959  1685231999  26829.2  26841.6
17472  20230528   080000    080959  1685232599  26841.6  26832.9
17473  20230528   081000    081959  1685233199    26833    26780
2023-05-28 08:20:08,616:INFO:pyemd2:main.py:127:handleKline:2217508: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}


## /root/FIL/strategy/similarity/log.txt ----- -----

12143  20230528   075000    075959  1685231999  26829.2  26841.6
2023-05-28 08:00:02,183:INFO:testStrategy:main.py:103:handleKline:2217133: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': True, 'isOpenSell': False, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True, 'isCorr': False}
127.0.0.1 - - [28/May/2023 08:10:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=2003 

self.closeSec=1685232599, self.tradeDate='20230528', self.openTime='080000', self.closeTime='080959', self.symbol='BTCUSDT', self.open='26841.6', self.close='26832.9'
2023-05-28 08:10:01,059:INFO:testStrategy:main.py:101:handleKline:2217133: self.closeSec=1685232599, self.tradeDate='20230528', self.openTime='080000', self.closeTime='080959',self.symbol='BTCUSDT',self.open='26841.6', self.close='26832.9'
2023-05-28 08:10:01,079:INFO:testStrategy:main.py:102:handleKline:2217133: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
12140  20230528   072000    072959  1685230199  26805.7  26819.1
12141  20230528   073000    073959  1685230799  26819.2  26825.4
12142  20230528   074000    074959  1685231399  26825.4  26829.2
12143  20230528   075000    075959  1685231999  26829.2  26841.6
12144  20230528   080000    080959  1685232599  26841.6  26832.9
2023-05-28 08:10:01,082:INFO:testStrategy:main.py:103:handleKline:2217133: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': True, 'isOpenSell': False, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True, 'isCorr': False}

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=2004 

self.closeSec=1685233199, self.tradeDate='20230528', self.openTime='081000', self.closeTime='081959', self.symbol='BTCUSDT', self.open='26833', self.close='26780'
127.0.0.1 - - [28/May/2023 08:20:04] "POST / HTTP/1.1" 200 -
2023-05-28 08:20:08,225:INFO:testStrategy:main.py:101:handleKline:2217133: self.closeSec=1685233199, self.tradeDate='20230528', self.openTime='081000', self.closeTime='081959',self.symbol='BTCUSDT',self.open='26833', self.close='26780'
2023-05-28 08:20:08,455:INFO:testStrategy:main.py:102:handleKline:2217133: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
12141  20230528   073000    073959  1685230799  26819.2  26825.4
12142  20230528   074000    074959  1685231399  26825.4  26829.2
12143  20230528   075000    075959  1685231999  26829.2  26841.6
12144  20230528   080000    080959  1685232599  26841.6  26832.9
12145  20230528   081000    081959  1685233199    26833    26780
2023-05-28 08:20:08,455:INFO:testStrategy:main.py:103:handleKline:2217133: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': True, 'isOpenSell': False, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True, 'isCorr': False}


## /root/FIL/strategy/sr_min/log.txt ----- -----

--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=1, self.total=996015.990996, self.flagDict['side']='buy', self.tradeCount=1, self.count=4000
self.closeSec=1685233199, self.tradeDate='20230528', self.openTime='081500', self.closeTime='081959', self.symbol='BTCUSDT', self.open=26830.7, self.close=26780.0, self.high=26830.7, self.low=26746.0, self.vol=2190.808, self.amt=58676775.9584 
127.0.0.1 - - [28/May/2023 08:20:01] "POST / HTTP/1.1" 200 -
2023-05-28 08:20:06,504:INFO:sr_min:main.py:172:handleKline:2219263: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5855  20230528   075500    075959  ...         0.0        0.0       0
5856  20230528   080000    080459  ...         0.0        0.0       0
5857  20230528   080500    080959  ...         0.0        0.0       0
5858  20230528   081000    081459  ...         0.0        0.0       0
5859  20230528   081500    081959  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-05-28 08:20:06,544:INFO:sr_min:main.py:175:handleKline:2219263: self.closeSec=1685233199, self.tradeDate='20230528', self.openTime='081500', self.closeTime='081959',self.symbol='BTCUSDT',self.open=26830.7, self.close=26780.0, self.high=26830.7, self.low=26746.0, self.vol=2190.808, self.amt=58676775.9584, ukdf['pct'].iloc[-1]=-0.001886 , ukdf['amount'].iloc[-1]=58676775.9584, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5859, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '37.141', 'enterprice': '26844', 'countrevence': '0', 'unrealprofit': '-2195.0331', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '26784.9', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=1
--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=1, self.total=996015.990996, self.flagDict['side']='buy', self.tradeCount=1, self.count=4001
self.closeSec=1685233499, self.tradeDate='20230528', self.openTime='082000', self.closeTime='082459', self.symbol='BTCUSDT', self.open=26779.9, self.close=26809.9, self.high=26809.9, self.low=26778.4, self.vol=557.14, self.amt=14926914.3467 
127.0.0.1 - - [28/May/2023 08:25:00] "POST / HTTP/1.1" 200 -
2023-05-28 08:25:00,769:INFO:sr_min:main.py:172:handleKline:2219263: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5856  20230528   080000    080459  ...         0.0        0.0       0
5857  20230528   080500    080959  ...         0.0        0.0       0
5858  20230528   081000    081459  ...         0.0        0.0       0
5859  20230528   081500    081959  ...         0.0        0.0       0
5860  20230528   082000    082459  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-05-28 08:25:00,769:INFO:sr_min:main.py:175:handleKline:2219263: self.closeSec=1685233499, self.tradeDate='20230528', self.openTime='082000', self.closeTime='082459',self.symbol='BTCUSDT',self.open=26779.9, self.close=26809.9, self.high=26809.9, self.low=26778.4, self.vol=557.14, self.amt=14926914.3467, ukdf['pct'].iloc[-1]=0.001117 , ukdf['amount'].iloc[-1]=14926914.3467, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5860, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '37.141', 'enterprice': '26844', 'countrevence': '0', 'unrealprofit': '-1270.2222', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '26809.8', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=1


## /root/FIL/strategy/s_rsrs/log.txt ----- -----

719  20230527   200000    235959  1685203199  ...    719  0.462421  0.346905     NaN
720  20230528   000000    035959  1685217599  ...    720  0.395964 -0.029926     NaN

[5 rows x 15 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '55.249', 'enterprice': '26128.2', 'countrevence': '0', 'unrealprofit': '32790.2815', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '26721.7', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'numpy.int64'>, curSign=-9223372036854775808, self.sign=1
127.0.0.1 - - [28/May/2023 08:00:01] "POST / HTTP/1.1" 200 -
--handleKline--:  version='2.0.0', self.name='s_rsrs', self.symbol='BTCUSDT', interval='4h', intervalSec=14400, wid=25, thd=0.6, self.sign=1, self.total=1442113.3648782002, self.flagDict['side']='buy', self.tradeCount=3, self.count=83
self.closeSec=1685231999, self.tradeDate='20230528', self.openTime='040000', self.closeTime='075959', self.symbol='BTCUSDT', self.open=26721.7, self.close=26841.6, self.high=26890.0, self.low=26714.5, self.vol=21946.952, self.amt=587902781.7877 
2023-05-28 08:00:01,725:INFO:s_rsrs:main.py:141:handleKline:2218689: self.closeSec=1685231999, self.tradeDate='20230528', self.openTime='040000', self.closeTime='075959',self.symbol='BTCUSDT',self.open=26721.7, self.close=26841.6, self.high=26890.0, self.low=26714.5, self.vol=21946.952, self.amt=587902781.7877 
2023-05-28 08:00:01,783:INFO:s_rsrs:main.py:142:handleKline:2218689: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime  ...        vol           amt       pct
717  20230527   120000    155959  ...  15097.708  4.035509e+08 -0.000905
718  20230527   160000    195959  ...  19863.179  5.300554e+08 -0.001033
719  20230527   200000    235959  ...  47080.958  1.255307e+09 -0.000210
720  20230528   000000    035959  ...  38259.082  1.022615e+09  0.001480
721  20230528   040000    075959  ...  21946.952  5.879028e+08  0.004491

[5 rows x 11 columns]
2023-05-28 08:00:03,661:INFO:s_rsrs:main.py:151:handleKline:2218689: df_s.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec  ...  index      beta    zscore  signal
717  20230527   120000    155959  1685174399  ...    717  0.565573  0.949284     1.0
718  20230527   160000    195959  1685188799  ...    718  0.484661  0.477806     NaN
719  20230527   200000    235959  1685203199  ...    719  0.462421  0.346905     NaN
720  20230528   000000    035959  1685217599  ...    720  0.395964 -0.029926     NaN
721  20230528   040000    075959  1685231999  ...    721  0.320607 -0.451685     NaN

[5 rows x 15 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '55.249', 'enterprice': '26128.2', 'countrevence': '0', 'unrealprofit': '39465.72520333766', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '26842.52469734', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'numpy.int64'>, curSign=-9223372036854775808, self.sign=1


