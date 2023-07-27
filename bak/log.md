# 20230727 08:26:02

## /root/FIL/strategy/amihud/log.txt ----- -----

--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=373746.4768026, self.flagDict['side']='sell', self.tradeCount=2, self.count=21280
self.closeSec=1690417199, self.tradeDate='20230727', self.openTime='081500', self.closeTime='081959', self.symbol='BTCUSDT', self.open=29310.4, self.close=29304.8, self.high=29316.5, self.low=29286.8, self.vol=786.983, self.amt=23060742.82 
127.0.0.1 - - [27/Jul/2023 08:20:01] "POST / HTTP/1.1" 200 -
2023-07-27 08:20:06,322:INFO:amihud:main.py:172:handleKline:2219019: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5855  20230727   075500    075959  ...         0.0        0.0       0
5856  20230727   080000    080459  ...         0.0        0.0       0
5857  20230727   080500    080959  ...         0.0        0.0       0
5858  20230727   081000    081459  ...         0.0        0.0       0
5859  20230727   081500    081959  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-07-27 08:20:06,342:INFO:amihud:main.py:175:handleKline:2219019: self.closeSec=1690417199, self.tradeDate='20230727', self.openTime='081500', self.closeTime='081959',self.symbol='BTCUSDT',self.open=29310.4, self.close=29304.8, self.high=29316.5, self.low=29286.8, self.vol=786.983, self.amt=23060742.82, ukdf['pct'].iloc[-1]=-0.000191 , ukdf['amount'].iloc[-1]=23060742.82, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5859, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '13.926', 'enterprice': '26864.9', 'countrevence': '0', 'unrealprofit': '-33978.0474', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '29304.8', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1
127.0.0.1 - - [27/Jul/2023 08:25:00] "POST / HTTP/1.1" 200 -
--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=373746.4768026, self.flagDict['side']='sell', self.tradeCount=2, self.count=21281
self.closeSec=1690417499, self.tradeDate='20230727', self.openTime='082000', self.closeTime='082459', self.symbol='BTCUSDT', self.open=29304.9, self.close=29334.3, self.high=29339.1, self.low=29304.0, self.vol=608.244, self.amt=17838622.3783 
2023-07-27 08:25:00,764:INFO:amihud:main.py:172:handleKline:2219019: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5856  20230727   080000    080459  ...         0.0        0.0       0
5857  20230727   080500    080959  ...         0.0        0.0       0
5858  20230727   081000    081459  ...         0.0        0.0       0
5859  20230727   081500    081959  ...         0.0        0.0       0
5860  20230727   082000    082459  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-07-27 08:25:00,764:INFO:amihud:main.py:175:handleKline:2219019: self.closeSec=1690417499, self.tradeDate='20230727', self.openTime='082000', self.closeTime='082459',self.symbol='BTCUSDT',self.open=29304.9, self.close=29334.3, self.high=29339.1, self.low=29304.0, self.vol=608.244, self.amt=17838622.3783, ukdf['pct'].iloc[-1]=0.001007 , ukdf['amount'].iloc[-1]=17838622.3783, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5860, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '13.926', 'enterprice': '26864.9', 'countrevence': '0', 'unrealprofit': '-34458.5436256248', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '29339.3035348', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1


## /root/FIL/strategy/factorcheck/log.txt ----- -----


self.closeSec=1690417199, self.tradeDate='20230727', self.openTime='081500', self.closeTime='081959', self.symbol='BTCUSDT', self.open=29310.4, self.close=29304.8, self.high=29316.5, self.low=29286.8 
127.0.0.1 - - [27/Jul/2023 08:20:01] "POST / HTTP/1.1" 200 -
2023-07-27 08:20:04,360:INFO:factorcheck2:main.py:126:handleKline:2218005: self.closeSec=1690417199, self.tradeDate='20230727', self.openTime='081500', self.closeTime='081959',self.symbol='BTCUSDT',self.open=29310.4, self.close=29304.8, self.high=29316.5, self.low=29286.8   
2023-07-27 08:20:05,530:INFO:factorcheck2:main.py:127:handleKline:2218005: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime    closeSec  ...      low       pct  index  idx
1535  20230727   075500    075959  1690415999  ...  29330.0  0.000143   1535    5
1536  20230727   080000    080459  1690416299  ...  29317.4 -0.000331   1536    0
1537  20230727   080500    080959  1690416599  ...  29300.2 -0.000887   1537    1
1538  20230727   081000    081459  1690416899  ...  29300.2  0.000345   1538    2
1539  20230727   081500    081959  1690417199  ...  29286.8 -0.000191   1539    3

[5 rows x 11 columns]
2023-07-27 08:20:05,541:INFO:factorcheck2:main.py:128:handleKline:2218005: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}
127.0.0.1 - - [27/Jul/2023 08:25:00] "POST / HTTP/1.1" 200 -

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=19, self.factor=0.3863179626111099, self.count=21283 

self.closeSec=1690417499, self.tradeDate='20230727', self.openTime='082000', self.closeTime='082459', self.symbol='BTCUSDT', self.open=29304.9, self.close=29334.3, self.high=29339.1, self.low=29304.0 
2023-07-27 08:25:00,716:INFO:factorcheck2:main.py:126:handleKline:2218005: self.closeSec=1690417499, self.tradeDate='20230727', self.openTime='082000', self.closeTime='082459',self.symbol='BTCUSDT',self.open=29304.9, self.close=29334.3, self.high=29339.1, self.low=29304.0   
2023-07-27 08:25:00,735:INFO:factorcheck2:main.py:127:handleKline:2218005: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime    closeSec  ...      low       pct  index  idx
1536  20230727   080000    080459  1690416299  ...  29317.4 -0.000331   1536    0
1537  20230727   080500    080959  1690416599  ...  29300.2 -0.000887   1537    1
1538  20230727   081000    081459  1690416899  ...  29300.2  0.000345   1538    2
1539  20230727   081500    081959  1690417199  ...  29286.8 -0.000191   1539    3
1540  20230727   082000    082459  1690417499  ...  29304.0  0.001007   1540    4

[5 rows x 11 columns]
2023-07-27 08:25:00,736:INFO:factorcheck2:main.py:128:handleKline:2218005: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}


## /root/FIL/strategy/logic/log.txt ----- -----

2023-07-27 08:00:17,565:DEBUG:logic:main.py:463:getModel:2218526: df_s.iloc[-5:,:] :
          date closeTime     open  ...    alpha58   alpha67   alpha72
5770  20230727    052959  29562.1  ...  50.833333  0.567040  0.427122
5771  20230727    055959  29495.6  ...  50.833333  0.551716  0.424017
5772  20230727    062959  29453.5  ...  50.416667  0.548668  0.422112
5773  20230727    065959  29444.9  ...  50.416667  0.552143  0.418967
5774  20230727    072959  29456.6  ...  50.000000  0.522365  0.425952

[5 rows x 33 columns]
0.5637707948243993
acc is : 0.5637707948243993
2023-07-27 08:00:17,631:INFO:logic:main.py:468:getModel:2218526: df_pred.iloc[-5:,:] :
     pred    prob_0    prob_1  actual  ...       nav  sign  cost_        bm
536     0  0.503457  0.496543       0  ...  0.927934   1.0    0.0  0.972095
537     0  0.504381  0.495619       0  ...  0.927666   1.0    0.0  0.971814
538     0  0.504697  0.495303       1  ...  0.928034   1.0    0.0  0.972200
539     0  0.503516  0.496484       0  ...  0.925360   1.0    0.0  0.969398
540     1  0.464391  0.535609       0  ...  0.924235   1.0    0.0  0.968220

[5 rows x 10 columns]
2023-07-27 08:00:17,642:INFO:logic:main.py:478:getModel:2218526: df_panel.iloc[-5:,:] :
    pred    prob_0    prob_1  actual  ...       nav  sign  cost_        bm
45     0  0.503297  0.496703       0  ...  0.927934   1.0    0.0  0.972364
46     0  0.504744  0.495256       0  ...  0.927666   1.0    0.0  0.972809
47     0  0.504525  0.495475       1  ...  0.928034   1.0    0.0  0.973161
48     0  0.503516  0.496484       0  ...  0.925360   1.0    0.0  0.969398
49     1  0.464391  0.535609       0  ...  0.924235   1.0    0.0  0.968220

[5 rows x 10 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '23.818', 'enterprice': '29478', 'countrevence': '0', 'unrealprofit': '-3365.7965674003', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '29336.68685165', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}


## /root/FIL/strategy/modifiedmom/log.txt ----- -----

623  20230727   075000    075959  1690415999  29323.2    29336  0.000437
2023-07-27 08:00:02,123:INFO:modifiedmom:main.py:146:handleKline:2218259: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': True, 'isOpen': False, 'isClose': True, 'isTrig': False}

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=10640 

self.closeSec=1690416599, self.tradeDate='20230727', self.openTime='080000', self.closeTime='080959', self.symbol='BTCUSDT', self.open='29336', self.close='29300.3'
127.0.0.1 - - [27/Jul/2023 08:10:01] "POST / HTTP/1.1" 200 -
2023-07-27 08:10:01,080:INFO:modifiedmom:main.py:144:handleKline:2218259: self.closeSec=1690416599, self.tradeDate='20230727', self.openTime='080000', self.closeTime='080959',self.symbol='BTCUSDT',self.open='29336', self.close='29300.3'
2023-07-27 08:10:01,089:INFO:modifiedmom:main.py:145:handleKline:2218259: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec     open    close       pct
620  20230727   072000    072959  1690414199  29421.1  29371.7 -0.001682
621  20230727   073000    073959  1690414799  29371.8  29318.1 -0.001825
622  20230727   074000    074959  1690415399  29318.1  29323.2  0.000174
623  20230727   075000    075959  1690415999  29323.2    29336  0.000437
624  20230727   080000    080959  1690416599    29336  29300.3 -0.001217
2023-07-27 08:10:01,090:INFO:modifiedmom:main.py:146:handleKline:2218259: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': True, 'isOpen': False, 'isClose': True, 'isTrig': False}

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=10641 

self.closeSec=1690417199, self.tradeDate='20230727', self.openTime='081000', self.closeTime='081959', self.symbol='BTCUSDT', self.open='29300.3', self.close='29304.9'
127.0.0.1 - - [27/Jul/2023 08:20:04] "POST / HTTP/1.1" 200 -
2023-07-27 08:20:06,862:INFO:modifiedmom:main.py:144:handleKline:2218259: self.closeSec=1690417199, self.tradeDate='20230727', self.openTime='081000', self.closeTime='081959',self.symbol='BTCUSDT',self.open='29300.3', self.close='29304.9'
2023-07-27 08:20:07,432:INFO:modifiedmom:main.py:145:handleKline:2218259: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec     open    close       pct
621  20230727   073000    073959  1690414799  29371.8  29318.1 -0.001825
622  20230727   074000    074959  1690415399  29318.1  29323.2  0.000174
623  20230727   075000    075959  1690415999  29323.2    29336  0.000437
624  20230727   080000    080959  1690416599    29336  29300.3 -0.001217
625  20230727   081000    081959  1690417199  29300.3  29304.9  0.000157
2023-07-27 08:20:07,432:INFO:modifiedmom:main.py:146:handleKline:2218259: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': True, 'isOpen': False, 'isClose': True, 'isTrig': False}


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

17471  20230727   075000    075959  1690415999  29323.2    29336
2023-07-27 08:00:02,143:INFO:pyemd2:main.py:127:handleKline:2217508: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=10643 

self.closeSec=1690416599, self.tradeDate='20230727', self.openTime='080000', self.closeTime='080959', self.symbol='BTCUSDT', self.open='29336', self.close='29300.3'
2023-07-27 08:10:01,090:INFO:pyemd2:main.py:125:handleKline:2217508: self.closeSec=1690416599, self.tradeDate='20230727', self.openTime='080000', self.closeTime='080959',self.symbol='BTCUSDT',self.open='29336', self.close='29300.3'
127.0.0.1 - - [27/Jul/2023 08:10:01] "POST / HTTP/1.1" 200 -
2023-07-27 08:10:01,097:INFO:pyemd2:main.py:126:handleKline:2217508: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
17468  20230727   072000    072959  1690414199  29421.1  29371.7
17469  20230727   073000    073959  1690414799  29371.8  29318.1
17470  20230727   074000    074959  1690415399  29318.1  29323.2
17471  20230727   075000    075959  1690415999  29323.2    29336
17472  20230727   080000    080959  1690416599    29336  29300.3
2023-07-27 08:10:01,097:INFO:pyemd2:main.py:127:handleKline:2217508: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=10644 

self.closeSec=1690417199, self.tradeDate='20230727', self.openTime='081000', self.closeTime='081959', self.symbol='BTCUSDT', self.open='29300.3', self.close='29304.9'
127.0.0.1 - - [27/Jul/2023 08:20:04] "POST / HTTP/1.1" 200 -
2023-07-27 08:20:08,301:INFO:pyemd2:main.py:125:handleKline:2217508: self.closeSec=1690417199, self.tradeDate='20230727', self.openTime='081000', self.closeTime='081959',self.symbol='BTCUSDT',self.open='29300.3', self.close='29304.9'
2023-07-27 08:20:08,434:INFO:pyemd2:main.py:126:handleKline:2217508: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
17469  20230727   073000    073959  1690414799  29371.8  29318.1
17470  20230727   074000    074959  1690415399  29318.1  29323.2
17471  20230727   075000    075959  1690415999  29323.2    29336
17472  20230727   080000    080959  1690416599    29336  29300.3
17473  20230727   081000    081959  1690417199  29300.3  29304.9
2023-07-27 08:20:08,435:INFO:pyemd2:main.py:127:handleKline:2217508: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}


## /root/FIL/strategy/similarity/log.txt ----- -----

12143  20230727   075000    075959  1690415999  29323.2    29336
2023-07-27 08:00:02,141:INFO:testStrategy:main.py:103:handleKline:2217133: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': True, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True, 'isCorr': False}
127.0.0.1 - - [27/Jul/2023 08:10:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=10643 

self.closeSec=1690416599, self.tradeDate='20230727', self.openTime='080000', self.closeTime='080959', self.symbol='BTCUSDT', self.open='29336', self.close='29300.3'
2023-07-27 08:10:01,082:INFO:testStrategy:main.py:101:handleKline:2217133: self.closeSec=1690416599, self.tradeDate='20230727', self.openTime='080000', self.closeTime='080959',self.symbol='BTCUSDT',self.open='29336', self.close='29300.3'
2023-07-27 08:10:01,097:INFO:testStrategy:main.py:102:handleKline:2217133: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
12140  20230727   072000    072959  1690414199  29421.1  29371.7
12141  20230727   073000    073959  1690414799  29371.8  29318.1
12142  20230727   074000    074959  1690415399  29318.1  29323.2
12143  20230727   075000    075959  1690415999  29323.2    29336
12144  20230727   080000    080959  1690416599    29336  29300.3
2023-07-27 08:10:01,098:INFO:testStrategy:main.py:103:handleKline:2217133: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': True, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True, 'isCorr': False}

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=10644 

self.closeSec=1690417199, self.tradeDate='20230727', self.openTime='081000', self.closeTime='081959', self.symbol='BTCUSDT', self.open='29300.3', self.close='29304.9'
127.0.0.1 - - [27/Jul/2023 08:20:04] "POST / HTTP/1.1" 200 -
2023-07-27 08:20:08,136:INFO:testStrategy:main.py:101:handleKline:2217133: self.closeSec=1690417199, self.tradeDate='20230727', self.openTime='081000', self.closeTime='081959',self.symbol='BTCUSDT',self.open='29300.3', self.close='29304.9'
2023-07-27 08:20:08,321:INFO:testStrategy:main.py:102:handleKline:2217133: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
12141  20230727   073000    073959  1690414799  29371.8  29318.1
12142  20230727   074000    074959  1690415399  29318.1  29323.2
12143  20230727   075000    075959  1690415999  29323.2    29336
12144  20230727   080000    080959  1690416599    29336  29300.3
12145  20230727   081000    081959  1690417199  29300.3  29304.9
2023-07-27 08:20:08,322:INFO:testStrategy:main.py:103:handleKline:2217133: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': True, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True, 'isCorr': False}


## /root/FIL/strategy/sr_min/log.txt ----- -----

--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=1, self.total=996015.990996, self.flagDict['side']='buy', self.tradeCount=1, self.count=21280
self.closeSec=1690417199, self.tradeDate='20230727', self.openTime='081500', self.closeTime='081959', self.symbol='BTCUSDT', self.open=29310.4, self.close=29304.8, self.high=29316.5, self.low=29286.8, self.vol=786.983, self.amt=23060742.82 
127.0.0.1 - - [27/Jul/2023 08:20:01] "POST / HTTP/1.1" 200 -
2023-07-27 08:20:06,311:INFO:sr_min:main.py:172:handleKline:2219263: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5855  20230727   075500    075959  ...         0.0        0.0       0
5856  20230727   080000    080459  ...         0.0        0.0       0
5857  20230727   080500    080959  ...         0.0        0.0       0
5858  20230727   081000    081459  ...         0.0        0.0       0
5859  20230727   081500    081959  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-07-27 08:20:06,332:INFO:sr_min:main.py:175:handleKline:2219263: self.closeSec=1690417199, self.tradeDate='20230727', self.openTime='081500', self.closeTime='081959',self.symbol='BTCUSDT',self.open=29310.4, self.close=29304.8, self.high=29316.5, self.low=29286.8, self.vol=786.983, self.amt=23060742.82, ukdf['pct'].iloc[-1]=-0.000191 , ukdf['amount'].iloc[-1]=23060742.82, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5859, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '37.141', 'enterprice': '26844', 'countrevence': '0', 'unrealprofit': '91396.5728', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '29304.8', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=1
127.0.0.1 - - [27/Jul/2023 08:25:00] "POST / HTTP/1.1" 200 -
--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=1, self.total=996015.990996, self.flagDict['side']='buy', self.tradeCount=1, self.count=21281
self.closeSec=1690417499, self.tradeDate='20230727', self.openTime='082000', self.closeTime='082459', self.symbol='BTCUSDT', self.open=29304.9, self.close=29334.3, self.high=29339.1, self.low=29304.0, self.vol=608.244, self.amt=17838622.3783 
2023-07-27 08:25:00,762:INFO:sr_min:main.py:172:handleKline:2219263: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5856  20230727   080000    080459  ...         0.0        0.0       0
5857  20230727   080500    080959  ...         0.0        0.0       0
5858  20230727   081000    081459  ...         0.0        0.0       0
5859  20230727   081500    081959  ...         0.0        0.0       0
5860  20230727   082000    082459  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-07-27 08:25:00,763:INFO:sr_min:main.py:175:handleKline:2219263: self.closeSec=1690417499, self.tradeDate='20230727', self.openTime='082000', self.closeTime='082459',self.symbol='BTCUSDT',self.open=29304.9, self.close=29334.3, self.high=29339.1, self.low=29304.0, self.vol=608.244, self.amt=17838622.3783, ukdf['pct'].iloc[-1]=0.001007 , ukdf['amount'].iloc[-1]=17838622.3783, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5860, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '37.141', 'enterprice': '26844', 'countrevence': '0', 'unrealprofit': '92678.0685860068', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '29339.3035348', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=1


## /root/FIL/strategy/s_rsrs/log.txt ----- -----

719  20230726   200000    235959  1690387199  ...    719  0.609597  0.931236     1.0
720  20230727   000000    035959  1690401599  ...    720  0.618229  0.945891     1.0

[5 rows x 15 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '54.821', 'enterprice': '29117.6', 'countrevence': '0', 'unrealprofit': '15360.8442', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '29397.8', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'numpy.int64'>, curSign=1, self.sign=1
127.0.0.1 - - [27/Jul/2023 08:00:01] "POST / HTTP/1.1" 200 -
--handleKline--:  version='2.0.0', self.name='s_rsrs', self.symbol='BTCUSDT', interval='4h', intervalSec=14400, wid=25, thd=0.6, self.sign=1, self.total=1594659.6936504, self.flagDict['side']='buy', self.tradeCount=13, self.count=443
self.closeSec=1690415999, self.tradeDate='20230727', self.openTime='040000', self.closeTime='075959', self.symbol='BTCUSDT', self.open=29390.3, self.close=29336.0, self.high=29670.5, self.low=29260.0, self.vol=90685.517, self.amt=2674287321.87763 
2023-07-27 08:00:01,685:INFO:s_rsrs:main.py:141:handleKline:2218689: self.closeSec=1690415999, self.tradeDate='20230727', self.openTime='040000', self.closeTime='075959',self.symbol='BTCUSDT',self.open=29390.3, self.close=29336.0, self.high=29670.5, self.low=29260.0, self.vol=90685.517, self.amt=2674287321.87763 
2023-07-27 08:00:01,700:INFO:s_rsrs:main.py:142:handleKline:2218689: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime  ...        vol           amt       pct
717  20230726   120000    155959  ...  27037.859  7.900565e+08 -0.000777
718  20230726   160000    195959  ...  16394.134  4.784539e+08 -0.001418
719  20230726   200000    235959  ...  42475.796  1.242892e+09  0.004914
720  20230727   000000    035959  ...  94415.230  2.768011e+09  0.002835
721  20230727   040000    075959  ...  90685.517  2.674287e+09 -0.001848

[5 rows x 11 columns]
2023-07-27 08:00:02,473:INFO:s_rsrs:main.py:151:handleKline:2218689: df_s.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec  ...  index      beta    zscore  signal
717  20230726   120000    155959  1690358399  ...    717  0.582017  0.862747     1.0
718  20230726   160000    195959  1690372799  ...    718  0.597699  0.904712     1.0
719  20230726   200000    235959  1690387199  ...    719  0.609597  0.931236     1.0
720  20230727   000000    035959  1690401599  ...    720  0.618229  0.945891     1.0
721  20230727   040000    075959  1690415999  ...    721  0.621201  0.937997     1.0

[5 rows x 15 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '54.821', 'enterprice': '29117.6', 'countrevence': '0', 'unrealprofit': '12005.85372067757', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '29336.60099817', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'numpy.int64'>, curSign=1, self.sign=1


