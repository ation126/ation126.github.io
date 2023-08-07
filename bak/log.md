# 20230807 08:26:02

## /root/FIL/strategy/amihud/log.txt ----- -----

--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=373746.4768026, self.flagDict['side']='sell', self.tradeCount=2, self.count=24448
self.closeSec=1691367599, self.tradeDate='20230807', self.openTime='081500', self.closeTime='081959', self.symbol='BTCUSDT', self.open=29087.8, self.close=29070.6, self.high=29088.9, self.low=29070.6, self.vol=327.797, self.amt=9533357.4661 
127.0.0.1 - - [07/Aug/2023 08:20:01] "POST / HTTP/1.1" 200 -
2023-08-07 08:20:06,615:INFO:amihud:main.py:172:handleKline:2219019: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5855  20230807   075500    075959  ...         0.0        0.0       0
5856  20230807   080000    080459  ...         0.0        0.0       0
5857  20230807   080500    080959  ...         0.0        0.0       0
5858  20230807   081000    081459  ...         0.0        0.0       0
5859  20230807   081500    081959  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-08-07 08:20:06,645:INFO:amihud:main.py:175:handleKline:2219019: self.closeSec=1691367599, self.tradeDate='20230807', self.openTime='081500', self.closeTime='081959',self.symbol='BTCUSDT',self.open=29087.8, self.close=29070.6, self.high=29088.9, self.low=29070.6, self.vol=327.797, self.amt=9533357.4661, ukdf['pct'].iloc[-1]=-0.000591 , ukdf['amount'].iloc[-1]=9533357.4661, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5859, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '13.926', 'enterprice': '26864.9', 'countrevence': '0', 'unrealprofit': '-30736.22526093768', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '29072.01081868', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1
127.0.0.1 - - [07/Aug/2023 08:25:00] "POST / HTTP/1.1" 200 -
--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=373746.4768026, self.flagDict['side']='sell', self.tradeCount=2, self.count=24449
self.closeSec=1691367899, self.tradeDate='20230807', self.openTime='082000', self.closeTime='082459', self.symbol='BTCUSDT', self.open=29070.6, self.close=29063.3, self.high=29070.7, self.low=29056.0, self.vol=385.269, self.amt=11196770.6217 
2023-08-07 08:25:00,837:INFO:amihud:main.py:172:handleKline:2219019: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5856  20230807   080000    080459  ...         0.0        0.0       0
5857  20230807   080500    080959  ...         0.0        0.0       0
5858  20230807   081000    081459  ...         0.0        0.0       0
5859  20230807   081500    081959  ...         0.0        0.0       0
5860  20230807   082000    082459  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-08-07 08:25:00,837:INFO:amihud:main.py:175:handleKline:2219019: self.closeSec=1691367899, self.tradeDate='20230807', self.openTime='082000', self.closeTime='082459',self.symbol='BTCUSDT',self.open=29070.6, self.close=29063.3, self.high=29070.7, self.low=29056.0, self.vol=385.269, self.amt=11196770.6217, ukdf['pct'].iloc[-1]=-0.000251 , ukdf['amount'].iloc[-1]=11196770.6217, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5860, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '13.926', 'enterprice': '26864.9', 'countrevence': '0', 'unrealprofit': '-30614.9184', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '29063.3', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1


## /root/FIL/strategy/factorcheck/log.txt ----- -----


self.closeSec=1691367599, self.tradeDate='20230807', self.openTime='081500', self.closeTime='081959', self.symbol='BTCUSDT', self.open=29087.8, self.close=29070.6, self.high=29088.9, self.low=29070.6 
127.0.0.1 - - [07/Aug/2023 08:20:01] "POST / HTTP/1.1" 200 -
2023-08-07 08:20:04,674:INFO:factorcheck2:main.py:126:handleKline:2218005: self.closeSec=1691367599, self.tradeDate='20230807', self.openTime='081500', self.closeTime='081959',self.symbol='BTCUSDT',self.open=29087.8, self.close=29070.6, self.high=29088.9, self.low=29070.6   
2023-08-07 08:20:05,785:INFO:factorcheck2:main.py:127:handleKline:2218005: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime    closeSec  ...      low       pct  index  idx
1535  20230807   075500    075959  1691366399  ...  29074.5 -0.000062   1535    5
1536  20230807   080000    080459  1691366699  ...  29073.9  0.000034   1536    0
1537  20230807   080500    080959  1691366999  ...  29064.3 -0.000433   1537    1
1538  20230807   081000    081459  1691367299  ...  29064.3  0.000809   1538    2
1539  20230807   081500    081959  1691367599  ...  29070.6 -0.000591   1539    3

[5 rows x 11 columns]
2023-08-07 08:20:05,786:INFO:factorcheck2:main.py:128:handleKline:2218005: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=123, self.factor=0.4946764069762203, self.count=24451 

self.closeSec=1691367899, self.tradeDate='20230807', self.openTime='082000', self.closeTime='082459', self.symbol='BTCUSDT', self.open=29070.6, self.close=29063.3, self.high=29070.7, self.low=29056.0 
127.0.0.1 - - [07/Aug/2023 08:25:00] "POST / HTTP/1.1" 200 -
2023-08-07 08:25:00,806:INFO:factorcheck2:main.py:126:handleKline:2218005: self.closeSec=1691367899, self.tradeDate='20230807', self.openTime='082000', self.closeTime='082459',self.symbol='BTCUSDT',self.open=29070.6, self.close=29063.3, self.high=29070.7, self.low=29056.0   
2023-08-07 08:25:00,826:INFO:factorcheck2:main.py:127:handleKline:2218005: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime    closeSec  ...      low       pct  index  idx
1536  20230807   080000    080459  1691366699  ...  29073.9  0.000034   1536    0
1537  20230807   080500    080959  1691366999  ...  29064.3 -0.000433   1537    1
1538  20230807   081000    081459  1691367299  ...  29064.3  0.000809   1538    2
1539  20230807   081500    081959  1691367599  ...  29070.6 -0.000591   1539    3
1540  20230807   082000    082459  1691367899  ...  29056.0 -0.000251   1540    4

[5 rows x 11 columns]
2023-08-07 08:25:00,826:INFO:factorcheck2:main.py:128:handleKline:2218005: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}


## /root/FIL/strategy/logic/log.txt ----- -----

2023-08-07 08:00:16,549:DEBUG:logic:main.py:463:getModel:2218526: df_s.iloc[-5:,:] :
          date closeTime     open  ...    alpha58   alpha67   alpha72
5770  20230807    052959  29126.2  ...  50.000000  0.550565  0.443753
5771  20230807    055959  29168.1  ...  50.000000  0.499547  0.450935
5772  20230807    062959  29077.4  ...  50.416667  0.521853  0.444123
5773  20230807    065959  29122.2  ...  50.000000  0.503265  0.448740
5774  20230807    072959  29085.9  ...  49.583333  0.501608  0.454047

[5 rows x 33 columns]
0.5452865064695009
acc is : 0.5452865064695009
2023-08-07 08:00:16,607:INFO:logic:main.py:468:getModel:2218526: df_pred.iloc[-5:,:] :
     pred    prob_0    prob_1  actual  ...       nav  sign  cost_        bm
536     0  0.523395  0.476605       0  ...  0.984656   1.0    0.0  0.993125
537     1  0.480866  0.519134       1  ...  0.986169   1.0    0.0  0.994651
538     0  0.519961  0.480039       0  ...  0.984940   1.0    0.0  0.993412
539     1  0.496555  0.503445       0  ...  0.984828   1.0    0.0  0.993299
540     0  0.500041  0.499959       0  ...  0.984608   1.0    0.0  0.993077

[5 rows x 10 columns]
2023-08-07 08:00:16,618:INFO:logic:main.py:478:getModel:2218526: df_panel.iloc[-5:,:] :
    pred    prob_0    prob_1  actual  ...       nav  sign  cost_        bm
45     0  0.523250  0.476750       0  ...  0.984656   1.0    0.0  0.992159
46     1  0.481166  0.518834       1  ...  0.986169   1.0    0.0  0.994628
47     0  0.519819  0.480181       0  ...  0.984940   1.0    0.0  0.993028
48     1  0.496850  0.503150       0  ...  0.984828   1.0    0.0  0.993299
49     0  0.500041  0.499959       0  ...  0.984608   1.0    0.0  0.993077

[5 rows x 10 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '24.06', 'enterprice': '29131.5', 'countrevence': '0', 'unrealprofit': '-1343.3407594362', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '29075.66705073', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}


## /root/FIL/strategy/modifiedmom/log.txt ----- -----

623  20230807   075000    075959  1691366399  29081.7    29076 -0.000193
2023-08-07 08:00:02,069:INFO:modifiedmom:main.py:146:handleKline:2218259: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': True, 'isOpen': False, 'isClose': True, 'isTrig': False}
127.0.0.1 - - [07/Aug/2023 08:10:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=12224 

self.closeSec=1691366999, self.tradeDate='20230807', self.openTime='080000', self.closeTime='080959', self.symbol='BTCUSDT', self.open='29075.9', self.close='29064.3'
2023-08-07 08:10:01,134:INFO:modifiedmom:main.py:144:handleKline:2218259: self.closeSec=1691366999, self.tradeDate='20230807', self.openTime='080000', self.closeTime='080959',self.symbol='BTCUSDT',self.open='29075.9', self.close='29064.3'
2023-08-07 08:10:01,148:INFO:modifiedmom:main.py:145:handleKline:2218259: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec     open    close       pct
620  20230807   072000    072959  1691364599  29078.8  29082.5  0.000131
621  20230807   073000    073959  1691365199  29082.6  29087.6  0.000175
622  20230807   074000    074959  1691365799  29087.6  29081.6 -0.000206
623  20230807   075000    075959  1691366399  29081.7    29076 -0.000193
624  20230807   080000    080959  1691366999  29075.9  29064.3 -0.000402
2023-08-07 08:10:01,148:INFO:modifiedmom:main.py:146:handleKline:2218259: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': True, 'isOpen': False, 'isClose': True, 'isTrig': False}

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=12225 

self.closeSec=1691367599, self.tradeDate='20230807', self.openTime='081000', self.closeTime='081959', self.symbol='BTCUSDT', self.open='29064.3', self.close='29070.6'
127.0.0.1 - - [07/Aug/2023 08:20:04] "POST / HTTP/1.1" 200 -
2023-08-07 08:20:06,875:INFO:modifiedmom:main.py:144:handleKline:2218259: self.closeSec=1691367599, self.tradeDate='20230807', self.openTime='081000', self.closeTime='081959',self.symbol='BTCUSDT',self.open='29064.3', self.close='29070.6'
2023-08-07 08:20:07,495:INFO:modifiedmom:main.py:145:handleKline:2218259: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec     open    close       pct
621  20230807   073000    073959  1691365199  29082.6  29087.6  0.000175
622  20230807   074000    074959  1691365799  29087.6  29081.6 -0.000206
623  20230807   075000    075959  1691366399  29081.7    29076 -0.000193
624  20230807   080000    080959  1691366999  29075.9  29064.3 -0.000402
625  20230807   081000    081959  1691367599  29064.3  29070.6  0.000217
2023-08-07 08:20:07,504:INFO:modifiedmom:main.py:146:handleKline:2218259: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': True, 'isOpen': False, 'isClose': True, 'isTrig': False}


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

17471  20230807   075000    075959  1691366399  29081.7    29076
2023-08-07 08:00:02,074:INFO:pyemd2:main.py:127:handleKline:2217508: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}
127.0.0.1 - - [07/Aug/2023 08:10:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=12227 

self.closeSec=1691366999, self.tradeDate='20230807', self.openTime='080000', self.closeTime='080959', self.symbol='BTCUSDT', self.open='29075.9', self.close='29064.3'
2023-08-07 08:10:01,142:INFO:pyemd2:main.py:125:handleKline:2217508: self.closeSec=1691366999, self.tradeDate='20230807', self.openTime='080000', self.closeTime='080959',self.symbol='BTCUSDT',self.open='29075.9', self.close='29064.3'
2023-08-07 08:10:01,151:INFO:pyemd2:main.py:126:handleKline:2217508: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
17468  20230807   072000    072959  1691364599  29078.8  29082.5
17469  20230807   073000    073959  1691365199  29082.6  29087.6
17470  20230807   074000    074959  1691365799  29087.6  29081.6
17471  20230807   075000    075959  1691366399  29081.7    29076
17472  20230807   080000    080959  1691366999  29075.9  29064.3
2023-08-07 08:10:01,151:INFO:pyemd2:main.py:127:handleKline:2217508: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=12228 

self.closeSec=1691367599, self.tradeDate='20230807', self.openTime='081000', self.closeTime='081959', self.symbol='BTCUSDT', self.open='29064.3', self.close='29070.6'
127.0.0.1 - - [07/Aug/2023 08:20:04] "POST / HTTP/1.1" 200 -
2023-08-07 08:20:08,578:INFO:pyemd2:main.py:125:handleKline:2217508: self.closeSec=1691367599, self.tradeDate='20230807', self.openTime='081000', self.closeTime='081959',self.symbol='BTCUSDT',self.open='29064.3', self.close='29070.6'
2023-08-07 08:20:08,669:INFO:pyemd2:main.py:126:handleKline:2217508: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
17469  20230807   073000    073959  1691365199  29082.6  29087.6
17470  20230807   074000    074959  1691365799  29087.6  29081.6
17471  20230807   075000    075959  1691366399  29081.7    29076
17472  20230807   080000    080959  1691366999  29075.9  29064.3
17473  20230807   081000    081959  1691367599  29064.3  29070.6
2023-08-07 08:20:08,671:INFO:pyemd2:main.py:127:handleKline:2217508: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}


## /root/FIL/strategy/similarity/log.txt ----- -----

12143  20230807   075000    075959  1691366399  29081.7    29076
2023-08-07 08:00:02,081:INFO:testStrategy:main.py:103:handleKline:2217133: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': True, 'isOpenSell': False, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True, 'isCorr': False}
127.0.0.1 - - [07/Aug/2023 08:10:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=12227 

self.closeSec=1691366999, self.tradeDate='20230807', self.openTime='080000', self.closeTime='080959', self.symbol='BTCUSDT', self.open='29075.9', self.close='29064.3'
2023-08-07 08:10:01,133:INFO:testStrategy:main.py:101:handleKline:2217133: self.closeSec=1691366999, self.tradeDate='20230807', self.openTime='080000', self.closeTime='080959',self.symbol='BTCUSDT',self.open='29075.9', self.close='29064.3'
2023-08-07 08:10:01,139:INFO:testStrategy:main.py:102:handleKline:2217133: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
12140  20230807   072000    072959  1691364599  29078.8  29082.5
12141  20230807   073000    073959  1691365199  29082.6  29087.6
12142  20230807   074000    074959  1691365799  29087.6  29081.6
12143  20230807   075000    075959  1691366399  29081.7    29076
12144  20230807   080000    080959  1691366999  29075.9  29064.3
2023-08-07 08:10:01,139:INFO:testStrategy:main.py:103:handleKline:2217133: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': True, 'isOpenSell': False, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True, 'isCorr': False}

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=12228 

self.closeSec=1691367599, self.tradeDate='20230807', self.openTime='081000', self.closeTime='081959', self.symbol='BTCUSDT', self.open='29064.3', self.close='29070.6'
127.0.0.1 - - [07/Aug/2023 08:20:04] "POST / HTTP/1.1" 200 -
2023-08-07 08:20:08,338:INFO:testStrategy:main.py:101:handleKline:2217133: self.closeSec=1691367599, self.tradeDate='20230807', self.openTime='081000', self.closeTime='081959',self.symbol='BTCUSDT',self.open='29064.3', self.close='29070.6'
2023-08-07 08:20:08,534:INFO:testStrategy:main.py:102:handleKline:2217133: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
12141  20230807   073000    073959  1691365199  29082.6  29087.6
12142  20230807   074000    074959  1691365799  29087.6  29081.6
12143  20230807   075000    075959  1691366399  29081.7    29076
12144  20230807   080000    080959  1691366999  29075.9  29064.3
12145  20230807   081000    081959  1691367599  29064.3  29070.6
2023-08-07 08:20:08,545:INFO:testStrategy:main.py:103:handleKline:2217133: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': True, 'isOpenSell': False, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True, 'isCorr': False}


## /root/FIL/strategy/sr_min/log.txt ----- -----

--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=1, self.total=996015.990996, self.flagDict['side']='buy', self.tradeCount=1, self.count=24448
self.closeSec=1691367599, self.tradeDate='20230807', self.openTime='081500', self.closeTime='081959', self.symbol='BTCUSDT', self.open=29087.8, self.close=29070.6, self.high=29088.9, self.low=29070.6, self.vol=327.797, self.amt=9533357.4661 
127.0.0.1 - - [07/Aug/2023 08:20:01] "POST / HTTP/1.1" 200 -
2023-08-07 08:20:06,654:INFO:sr_min:main.py:172:handleKline:2219263: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5855  20230807   075500    075959  ...         0.0        0.0       0
5856  20230807   080000    080459  ...         0.0        0.0       0
5857  20230807   080500    080959  ...         0.0        0.0       0
5858  20230807   081000    081459  ...         0.0        0.0       0
5859  20230807   081500    081959  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-08-07 08:20:06,666:INFO:sr_min:main.py:175:handleKline:2219263: self.closeSec=1691367599, self.tradeDate='20230807', self.openTime='081500', self.closeTime='081959',self.symbol='BTCUSDT',self.open=29087.8, self.close=29070.6, self.high=29088.9, self.low=29070.6, self.vol=327.797, self.amt=9533357.4661, ukdf['pct'].iloc[-1]=-0.000591 , ukdf['amount'].iloc[-1]=9533357.4661, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5859, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '37.141', 'enterprice': '26844', 'countrevence': '0', 'unrealprofit': '82750.23146511225', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '29072.00224725', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=1
--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=1, self.total=996015.990996, self.flagDict['side']='buy', self.tradeCount=1, self.count=24449
self.closeSec=1691367899, self.tradeDate='20230807', self.openTime='082000', self.closeTime='082459', self.symbol='BTCUSDT', self.open=29070.6, self.close=29063.3, self.high=29070.7, self.low=29056.0, self.vol=385.269, self.amt=11196770.6217 
127.0.0.1 - - [07/Aug/2023 08:25:00] "POST / HTTP/1.1" 200 -
2023-08-07 08:25:00,825:INFO:sr_min:main.py:172:handleKline:2219263: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5856  20230807   080000    080459  ...         0.0        0.0       0
5857  20230807   080500    080959  ...         0.0        0.0       0
5858  20230807   081000    081459  ...         0.0        0.0       0
5859  20230807   081500    081959  ...         0.0        0.0       0
5860  20230807   082000    082459  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-08-07 08:25:00,825:INFO:sr_min:main.py:175:handleKline:2219263: self.closeSec=1691367899, self.tradeDate='20230807', self.openTime='082000', self.closeTime='082459',self.symbol='BTCUSDT',self.open=29070.6, self.close=29063.3, self.high=29070.7, self.low=29056.0, self.vol=385.269, self.amt=11196770.6217, ukdf['pct'].iloc[-1]=-0.000251 , ukdf['amount'].iloc[-1]=11196770.6217, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5860, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '37.141', 'enterprice': '26844', 'countrevence': '0', 'unrealprofit': '82427.0213', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '29063.3', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=1


## /root/FIL/strategy/s_rsrs/log.txt ----- -----

719  20230806   200000    235959  1691337599  ...    719  0.119670 -0.943544    -1.0
720  20230807   000000    035959  1691351999  ...    720  0.042674 -1.290322    -1.0

[5 rows x 15 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '54.719', 'enterprice': '28996.8', 'countrevence': '0', 'unrealprofit': '-4392.16065120735', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '29077.06756065', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'numpy.int64'>, curSign=-1, self.sign=-1
127.0.0.1 - - [07/Aug/2023 08:00:01] "POST / HTTP/1.1" 200 -
--handleKline--:  version='2.0.0', self.name='s_rsrs', self.symbol='BTCUSDT', interval='4h', intervalSec=14400, wid=25, thd=0.6, self.sign=-1, self.total=1585089.2233008002, self.flagDict['side']='sell', self.tradeCount=18, self.count=509
self.closeSec=1691366399, self.tradeDate='20230807', self.openTime='040000', self.closeTime='075959', self.symbol='BTCUSDT', self.open=29077.0, self.close=29076.0, self.high=29199.0, self.low=29025.0, self.vol=30590.873, self.amt=890895227.593 
2023-08-07 08:00:01,647:INFO:s_rsrs:main.py:141:handleKline:2218689: self.closeSec=1691366399, self.tradeDate='20230807', self.openTime='040000', self.closeTime='075959',self.symbol='BTCUSDT',self.open=29077.0, self.close=29076.0, self.high=29199.0, self.low=29025.0, self.vol=30590.873, self.amt=890895227.593 
2023-08-07 08:00:01,661:INFO:s_rsrs:main.py:142:handleKline:2218689: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime  ...        vol           amt       pct
717  20230806   120000    155959  ...  11457.436  3.330443e+08  0.000957
718  20230806   160000    195959  ...  15861.601  4.612386e+08 -0.000492
719  20230806   200000    235959  ...  18943.151  5.497474e+08 -0.002271
720  20230807   000000    035959  ...  18067.007  5.250492e+08  0.002617
721  20230807   040000    075959  ...  30590.873  8.908952e+08 -0.000031

[5 rows x 11 columns]
2023-08-07 08:00:02,339:INFO:s_rsrs:main.py:151:handleKline:2218689: df_s.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec  ...  index      beta    zscore  signal
717  20230806   120000    155959  1691308799  ...    717  0.439198  0.519806     NaN
718  20230806   160000    195959  1691323199  ...    718  0.256337 -0.317274     NaN
719  20230806   200000    235959  1691337599  ...    719  0.119670 -0.943544    -1.0
720  20230807   000000    035959  1691351999  ...    720  0.042674 -1.290322    -1.0
721  20230807   040000    075959  1691366399  ...    721  0.143837 -0.828316    -1.0

[5 rows x 15 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '54.719', 'enterprice': '28996.8', 'countrevence': '0', 'unrealprofit': '-4400.73915512798', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '29077.22433442', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'numpy.int64'>, curSign=-1, self.sign=-1


