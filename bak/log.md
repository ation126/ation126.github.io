# 20230722 08:26:01

## /root/FIL/strategy/amihud/log.txt ----- -----

--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=373746.4768026, self.flagDict['side']='sell', self.tradeCount=2, self.count=19840
self.closeSec=1689985199, self.tradeDate='20230722', self.openTime='081500', self.closeTime='081959', self.symbol='BTCUSDT', self.open=29907.1, self.close=29919.8, self.high=29919.9, self.low=29907.1, self.vol=345.574, self.amt=10337614.7949 
127.0.0.1 - - [22/Jul/2023 08:20:01] "POST / HTTP/1.1" 200 -
2023-07-22 08:20:05,087:INFO:amihud:main.py:172:handleKline:2219019: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5855  20230722   075500    075959  ...         0.0        0.0       0
5856  20230722   080000    080459  ...         0.0        0.0       0
5857  20230722   080500    080959  ...         0.0        0.0       0
5858  20230722   081000    081459  ...         0.0        0.0       0
5859  20230722   081500    081959  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-07-22 08:20:05,107:INFO:amihud:main.py:175:handleKline:2219019: self.closeSec=1689985199, self.tradeDate='20230722', self.openTime='081500', self.closeTime='081959',self.symbol='BTCUSDT',self.open=29907.1, self.close=29919.8, self.high=29919.9, self.low=29907.1, self.vol=345.574, self.amt=10337614.7949, ukdf['pct'].iloc[-1]=0.000498 , ukdf['amount'].iloc[-1]=10337614.7949, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5859, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '13.926', 'enterprice': '26864.9', 'countrevence': '0', 'unrealprofit': '-42557.30056678188', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '29920.86011538', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1
--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=373746.4768026, self.flagDict['side']='sell', self.tradeCount=2, self.count=19841
self.closeSec=1689985499, self.tradeDate='20230722', self.openTime='082000', self.closeTime='082459', self.symbol='BTCUSDT', self.open=29919.9, self.close=29919.9, self.high=29920.0, self.low=29914.9, self.vol=253.779, self.amt=7592610.0171 
127.0.0.1 - - [22/Jul/2023 08:25:00] "POST / HTTP/1.1" 200 -
2023-07-22 08:25:00,784:INFO:amihud:main.py:172:handleKline:2219019: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5856  20230722   080000    080459  ...         0.0        0.0       0
5857  20230722   080500    080959  ...         0.0        0.0       0
5858  20230722   081000    081459  ...         0.0        0.0       0
5859  20230722   081500    081959  ...         0.0        0.0       0
5860  20230722   082000    082459  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-07-22 08:25:00,785:INFO:amihud:main.py:175:handleKline:2219019: self.closeSec=1689985499, self.tradeDate='20230722', self.openTime='082000', self.closeTime='082459',self.symbol='BTCUSDT',self.open=29919.9, self.close=29919.9, self.high=29920.0, self.low=29914.9, self.vol=253.779, self.amt=7592610.0171, ukdf['pct'].iloc[-1]=3e-06 , ukdf['amount'].iloc[-1]=7592610.0171, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5860, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '13.926', 'enterprice': '26864.9', 'countrevence': '0', 'unrealprofit': '-42543.93', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '29919.9', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1


## /root/FIL/strategy/factorcheck/log.txt ----- -----


self.closeSec=1689985199, self.tradeDate='20230722', self.openTime='081500', self.closeTime='081959', self.symbol='BTCUSDT', self.open=29907.1, self.close=29919.8, self.high=29919.9, self.low=29907.1 
127.0.0.1 - - [22/Jul/2023 08:20:01] "POST / HTTP/1.1" 200 -
2023-07-22 08:20:03,706:INFO:factorcheck2:main.py:126:handleKline:2218005: self.closeSec=1689985199, self.tradeDate='20230722', self.openTime='081500', self.closeTime='081959',self.symbol='BTCUSDT',self.open=29907.1, self.close=29919.8, self.high=29919.9, self.low=29907.1   
2023-07-22 08:20:04,626:INFO:factorcheck2:main.py:127:handleKline:2218005: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime    closeSec  ...      low       pct  index  idx
1535  20230722   075500    075959  1689983999  ...  29882.4 -0.000164   1535    5
1536  20230722   080000    080459  1689984299  ...  29888.3  0.000197   1536    0
1537  20230722   080500    080959  1689984599  ...  29890.5  0.000057   1537    1
1538  20230722   081000    081459  1689984899  ...  29889.6  0.000194   1538    2
1539  20230722   081500    081959  1689985199  ...  29907.1  0.000498   1539    3

[5 rows x 11 columns]
2023-07-22 08:20:04,636:INFO:factorcheck2:main.py:128:handleKline:2218005: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}
127.0.0.1 - - [22/Jul/2023 08:25:00] "POST / HTTP/1.1" 200 -

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=92, self.factor=0.46171188797366336, self.count=19843 

self.closeSec=1689985499, self.tradeDate='20230722', self.openTime='082000', self.closeTime='082459', self.symbol='BTCUSDT', self.open=29919.9, self.close=29919.9, self.high=29920.0, self.low=29914.9 
2023-07-22 08:25:00,754:INFO:factorcheck2:main.py:126:handleKline:2218005: self.closeSec=1689985499, self.tradeDate='20230722', self.openTime='082000', self.closeTime='082459',self.symbol='BTCUSDT',self.open=29919.9, self.close=29919.9, self.high=29920.0, self.low=29914.9   
2023-07-22 08:25:00,774:INFO:factorcheck2:main.py:127:handleKline:2218005: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime    closeSec  ...      low       pct  index  idx
1536  20230722   080000    080459  1689984299  ...  29888.3  0.000197   1536    0
1537  20230722   080500    080959  1689984599  ...  29890.5  0.000057   1537    1
1538  20230722   081000    081459  1689984899  ...  29889.6  0.000194   1538    2
1539  20230722   081500    081959  1689985199  ...  29907.1  0.000498   1539    3
1540  20230722   082000    082459  1689985499  ...  29914.9  0.000003   1540    4

[5 rows x 11 columns]
2023-07-22 08:25:00,774:INFO:factorcheck2:main.py:128:handleKline:2218005: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}


## /root/FIL/strategy/logic/log.txt ----- -----

2023-07-22 08:00:18,296:DEBUG:logic:main.py:463:getModel:2218526: df_s.iloc[-5:,:] :
          date closeTime     open  ...    alpha58   alpha67   alpha72
5770  20230722    052959  29867.6  ...  50.000000  0.501037  0.440486
5771  20230722    055959  29895.4  ...  50.000000  0.498595  0.443847
5772  20230722    062959  29886.4  ...  50.000000  0.502390  0.444324
5773  20230722    065959  29900.2  ...  50.000000  0.505214  0.442803
5774  20230722    072959  29910.5  ...  50.416667  0.506783  0.440304

[5 rows x 33 columns]
0.5083179297597042
acc is : 0.5083179297597042
2023-07-22 08:00:18,367:INFO:logic:main.py:468:getModel:2218526: df_pred.iloc[-5:,:] :
     pred    prob_0    prob_1  actual  ...       nav  sign  cost_        bm
536     0  0.507710  0.492290       0  ...  0.953184   1.0    0.0  0.985728
537     0  0.509195  0.490805       1  ...  0.953624   1.0    0.0  0.986184
538     0  0.516100  0.483900       1  ...  0.953950   1.0    0.0  0.986520
539     0  0.515731  0.484269       1  ...  0.954128   1.0    0.0  0.986705
540     0  0.516590  0.483410       0  ...  0.953347   1.0    0.0  0.985897

[5 rows x 10 columns]
2023-07-22 08:00:18,380:INFO:logic:main.py:478:getModel:2218526: df_panel.iloc[-5:,:] :
    pred    prob_0    prob_1  actual  ...       nav  sign  cost_        bm
45     0  0.507501  0.492499       0  ...  0.953184   1.0    0.0  0.986428
46     0  0.509846  0.490154       1  ...  0.953624   1.0    0.0  0.987852
47     0  0.515837  0.484163       1  ...  0.953950   1.0    0.0  0.985970
48     0  0.516417  0.483583       1  ...  0.954128   1.0    0.0  0.986705
49     0  0.516590  0.483410       0  ...  0.953347   1.0    0.0  0.985897

[5 rows x 10 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '23.444', 'enterprice': '29839.3', 'countrevence': '0', 'unrealprofit': '1200.3328', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '29890.5', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}


## /root/FIL/strategy/modifiedmom/log.txt ----- -----

623  20230722   075000    075959  1689983999  29908.9  29891.4 -0.000582
2023-07-22 08:00:02,238:INFO:modifiedmom:main.py:146:handleKline:2218259: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': True, 'isOpen': False, 'isClose': True, 'isTrig': False}
127.0.0.1 - - [22/Jul/2023 08:10:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=9920 

self.closeSec=1689984599, self.tradeDate='20230722', self.openTime='080000', self.closeTime='080959', self.symbol='BTCUSDT', self.open='29891.5', self.close='29899.1'
2023-07-22 08:10:01,105:INFO:modifiedmom:main.py:144:handleKline:2218259: self.closeSec=1689984599, self.tradeDate='20230722', self.openTime='080000', self.closeTime='080959',self.symbol='BTCUSDT',self.open='29891.5', self.close='29899.1'
2023-07-22 08:10:01,121:INFO:modifiedmom:main.py:145:handleKline:2218259: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec     open    close       pct
620  20230722   072000    072959  1689982199    29904    29916  0.000401
621  20230722   073000    073959  1689982799    29916  29912.9 -0.000104
622  20230722   074000    074959  1689983399    29913  29908.8 -0.000137
623  20230722   075000    075959  1689983999  29908.9  29891.4 -0.000582
624  20230722   080000    080959  1689984599  29891.5  29899.1  0.000258
2023-07-22 08:10:01,121:INFO:modifiedmom:main.py:146:handleKline:2218259: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': True, 'isOpen': False, 'isClose': True, 'isTrig': False}

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=9921 

self.closeSec=1689985199, self.tradeDate='20230722', self.openTime='081000', self.closeTime='081959', self.symbol='BTCUSDT', self.open='29899', self.close='29919.8'
127.0.0.1 - - [22/Jul/2023 08:20:04] "POST / HTTP/1.1" 200 -
2023-07-22 08:20:05,616:INFO:modifiedmom:main.py:144:handleKline:2218259: self.closeSec=1689985199, self.tradeDate='20230722', self.openTime='081000', self.closeTime='081959',self.symbol='BTCUSDT',self.open='29899', self.close='29919.8'
2023-07-22 08:20:06,226:INFO:modifiedmom:main.py:145:handleKline:2218259: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec     open    close       pct
621  20230722   073000    073959  1689982799    29916  29912.9 -0.000104
622  20230722   074000    074959  1689983399    29913  29908.8 -0.000137
623  20230722   075000    075959  1689983999  29908.9  29891.4 -0.000582
624  20230722   080000    080959  1689984599  29891.5  29899.1  0.000258
625  20230722   081000    081959  1689985199    29899  29919.8  0.000692
2023-07-22 08:20:06,226:INFO:modifiedmom:main.py:146:handleKline:2218259: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': True, 'isOpen': False, 'isClose': True, 'isTrig': False}


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

17471  20230722   075000    075959  1689983999  29908.9  29891.4
2023-07-22 08:00:02,244:INFO:pyemd2:main.py:127:handleKline:2217508: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=9923 

self.closeSec=1689984599, self.tradeDate='20230722', self.openTime='080000', self.closeTime='080959', self.symbol='BTCUSDT', self.open='29891.5', self.close='29899.1'
2023-07-22 08:10:01,116:INFO:pyemd2:main.py:125:handleKline:2217508: self.closeSec=1689984599, self.tradeDate='20230722', self.openTime='080000', self.closeTime='080959',self.symbol='BTCUSDT',self.open='29891.5', self.close='29899.1'
127.0.0.1 - - [22/Jul/2023 08:10:01] "POST / HTTP/1.1" 200 -
2023-07-22 08:10:01,127:INFO:pyemd2:main.py:126:handleKline:2217508: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
17468  20230722   072000    072959  1689982199    29904    29916
17469  20230722   073000    073959  1689982799    29916  29912.9
17470  20230722   074000    074959  1689983399    29913  29908.8
17471  20230722   075000    075959  1689983999  29908.9  29891.4
17472  20230722   080000    080959  1689984599  29891.5  29899.1
2023-07-22 08:10:01,127:INFO:pyemd2:main.py:127:handleKline:2217508: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=9924 

self.closeSec=1689985199, self.tradeDate='20230722', self.openTime='081000', self.closeTime='081959', self.symbol='BTCUSDT', self.open='29899', self.close='29919.8'
127.0.0.1 - - [22/Jul/2023 08:20:04] "POST / HTTP/1.1" 200 -
2023-07-22 08:20:06,817:INFO:pyemd2:main.py:125:handleKline:2217508: self.closeSec=1689985199, self.tradeDate='20230722', self.openTime='081000', self.closeTime='081959',self.symbol='BTCUSDT',self.open='29899', self.close='29919.8'
2023-07-22 08:20:07,006:INFO:pyemd2:main.py:126:handleKline:2217508: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
17469  20230722   073000    073959  1689982799    29916  29912.9
17470  20230722   074000    074959  1689983399    29913  29908.8
17471  20230722   075000    075959  1689983999  29908.9  29891.4
17472  20230722   080000    080959  1689984599  29891.5  29899.1
17473  20230722   081000    081959  1689985199    29899  29919.8
2023-07-22 08:20:07,006:INFO:pyemd2:main.py:127:handleKline:2217508: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}


## /root/FIL/strategy/similarity/log.txt ----- -----

12143  20230722   075000    075959  1689983999  29908.9  29891.4
2023-07-22 08:00:02,237:INFO:testStrategy:main.py:103:handleKline:2217133: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': True, 'isOpenSell': False, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True, 'isCorr': False}
127.0.0.1 - - [22/Jul/2023 08:10:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=9923 

self.closeSec=1689984599, self.tradeDate='20230722', self.openTime='080000', self.closeTime='080959', self.symbol='BTCUSDT', self.open='29891.5', self.close='29899.1'
2023-07-22 08:10:01,107:INFO:testStrategy:main.py:101:handleKline:2217133: self.closeSec=1689984599, self.tradeDate='20230722', self.openTime='080000', self.closeTime='080959',self.symbol='BTCUSDT',self.open='29891.5', self.close='29899.1'
2023-07-22 08:10:01,113:INFO:testStrategy:main.py:102:handleKline:2217133: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
12140  20230722   072000    072959  1689982199    29904    29916
12141  20230722   073000    073959  1689982799    29916  29912.9
12142  20230722   074000    074959  1689983399    29913  29908.8
12143  20230722   075000    075959  1689983999  29908.9  29891.4
12144  20230722   080000    080959  1689984599  29891.5  29899.1
2023-07-22 08:10:01,113:INFO:testStrategy:main.py:103:handleKline:2217133: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': True, 'isOpenSell': False, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True, 'isCorr': False}

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=9924 

self.closeSec=1689985199, self.tradeDate='20230722', self.openTime='081000', self.closeTime='081959', self.symbol='BTCUSDT', self.open='29899', self.close='29919.8'
127.0.0.1 - - [22/Jul/2023 08:20:04] "POST / HTTP/1.1" 200 -
2023-07-22 08:20:06,709:INFO:testStrategy:main.py:101:handleKline:2217133: self.closeSec=1689985199, self.tradeDate='20230722', self.openTime='081000', self.closeTime='081959',self.symbol='BTCUSDT',self.open='29899', self.close='29919.8'
2023-07-22 08:20:06,910:INFO:testStrategy:main.py:102:handleKline:2217133: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
12141  20230722   073000    073959  1689982799    29916  29912.9
12142  20230722   074000    074959  1689983399    29913  29908.8
12143  20230722   075000    075959  1689983999  29908.9  29891.4
12144  20230722   080000    080959  1689984599  29891.5  29899.1
12145  20230722   081000    081959  1689985199    29899  29919.8
2023-07-22 08:20:06,915:INFO:testStrategy:main.py:103:handleKline:2217133: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': True, 'isOpenSell': False, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True, 'isCorr': False}


## /root/FIL/strategy/sr_min/log.txt ----- -----

--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=1, self.total=996015.990996, self.flagDict['side']='buy', self.tradeCount=1, self.count=19840
self.closeSec=1689985199, self.tradeDate='20230722', self.openTime='081500', self.closeTime='081959', self.symbol='BTCUSDT', self.open=29907.1, self.close=29919.8, self.high=29919.9, self.low=29907.1, self.vol=345.574, self.amt=10337614.7949 
127.0.0.1 - - [22/Jul/2023 08:20:01] "POST / HTTP/1.1" 200 -
2023-07-22 08:20:05,106:INFO:sr_min:main.py:172:handleKline:2219263: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5855  20230722   075500    075959  ...         0.0        0.0       0
5856  20230722   080000    080459  ...         0.0        0.0       0
5857  20230722   080500    080959  ...         0.0        0.0       0
5858  20230722   081000    081459  ...         0.0        0.0       0
5859  20230722   081500    081959  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-07-22 08:20:05,117:INFO:sr_min:main.py:175:handleKline:2219263: self.closeSec=1689985199, self.tradeDate='20230722', self.openTime='081500', self.closeTime='081959',self.symbol='BTCUSDT',self.open=29907.1, self.close=29919.8, self.high=29919.9, self.low=29907.1, self.vol=345.574, self.amt=10337614.7949, ukdf['pct'].iloc[-1]=0.000498 , ukdf['amount'].iloc[-1]=10337614.7949, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5859, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '37.141', 'enterprice': '26844', 'countrevence': '0', 'unrealprofit': '114277.66154532858', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '29920.86011538', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=1
127.0.0.1 - - [22/Jul/2023 08:25:00] "POST / HTTP/1.1" 200 -
--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=1, self.total=996015.990996, self.flagDict['side']='buy', self.tradeCount=1, self.count=19841
self.closeSec=1689985499, self.tradeDate='20230722', self.openTime='082000', self.closeTime='082459', self.symbol='BTCUSDT', self.open=29919.9, self.close=29919.9, self.high=29920.0, self.low=29914.9, self.vol=253.779, self.amt=7592610.0171 
2023-07-22 08:25:00,774:INFO:sr_min:main.py:172:handleKline:2219263: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5856  20230722   080000    080459  ...         0.0        0.0       0
5857  20230722   080500    080959  ...         0.0        0.0       0
5858  20230722   081000    081459  ...         0.0        0.0       0
5859  20230722   081500    081959  ...         0.0        0.0       0
5860  20230722   082000    082459  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-07-22 08:25:00,774:INFO:sr_min:main.py:175:handleKline:2219263: self.closeSec=1689985499, self.tradeDate='20230722', self.openTime='082000', self.closeTime='082459',self.symbol='BTCUSDT',self.open=29919.9, self.close=29919.9, self.high=29920.0, self.low=29914.9, self.vol=253.779, self.amt=7592610.0171, ukdf['pct'].iloc[-1]=3e-06 , ukdf['amount'].iloc[-1]=7592610.0171, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5860, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '37.141', 'enterprice': '26844', 'countrevence': '0', 'unrealprofit': '114242.0019', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '29919.9', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=1


## /root/FIL/strategy/s_rsrs/log.txt ----- -----

719  20230721   200000    235959  1689955199  ...    719  0.127920 -1.135281    -1.0
720  20230722   000000    035959  1689969599  ...    720  0.102436 -1.226806    -1.0

[5 rows x 15 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '52.176', 'enterprice': '29870.6', 'countrevence': '0', 'unrealprofit': '140.8752', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '29867.9', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'numpy.int64'>, curSign=-1, self.sign=-1
127.0.0.1 - - [22/Jul/2023 08:00:01] "POST / HTTP/1.1" 200 -
--handleKline--:  version='2.0.0', self.name='s_rsrs', self.symbol='BTCUSDT', interval='4h', intervalSec=14400, wid=25, thd=0.6, self.sign=-1, self.total=1556969.8971744, self.flagDict['side']='sell', self.tradeCount=12, self.count=413
self.closeSec=1689983999, self.tradeDate='20230722', self.openTime='040000', self.closeTime='075959', self.symbol='BTCUSDT', self.open=29865.1, self.close=29891.4, self.high=29942.7, self.low=29819.4, self.vol=17712.508, self.amt=529379766.355 
2023-07-22 08:00:01,791:INFO:s_rsrs:main.py:141:handleKline:2218689: self.closeSec=1689983999, self.tradeDate='20230722', self.openTime='040000', self.closeTime='075959',self.symbol='BTCUSDT',self.open=29865.1, self.close=29891.4, self.high=29942.7, self.low=29819.4, self.vol=17712.508, self.amt=529379766.355 
2023-07-22 08:00:01,804:INFO:s_rsrs:main.py:142:handleKline:2218689: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime  ...        vol           amt       pct
717  20230721   120000    155959  ...  26891.176  8.016709e+08 -0.004233
718  20230721   160000    195959  ...  28024.428  8.344178e+08  0.000235
719  20230721   200000    235959  ...  46739.642  1.394602e+09  0.002930
720  20230722   000000    035959  ...  63156.101  1.888720e+09  0.000439
721  20230722   040000    075959  ...  17712.508  5.293798e+08  0.000881

[5 rows x 11 columns]
2023-07-22 08:00:02,464:INFO:s_rsrs:main.py:151:handleKline:2218689: df_s.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec  ...  index      beta    zscore  signal
717  20230721   120000    155959  1689926399  ...    717  0.141051 -1.114406    -1.0
718  20230721   160000    195959  1689940799  ...    718  0.146010 -1.068862    -1.0
719  20230721   200000    235959  1689955199  ...    719  0.127920 -1.135281    -1.0
720  20230722   000000    035959  1689969599  ...    720  0.102436 -1.226806    -1.0
721  20230722   040000    075959  1689983999  ...    721  0.140332 -1.050430    -1.0

[5 rows x 15 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '52.176', 'enterprice': '29870.6', 'countrevence': '0', 'unrealprofit': '-1090.4784', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '29891.5', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'numpy.int64'>, curSign=-1, self.sign=-1


