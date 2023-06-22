# 20230622 08:26:01

## /root/FIL/strategy/amihud/log.txt ----- -----

--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=373746.4768026, self.flagDict['side']='sell', self.tradeCount=2, self.count=11200
self.closeSec=1687393199, self.tradeDate='20230622', self.openTime='081500', self.closeTime='081959', self.symbol='BTCUSDT', self.open=29946.7, self.close=29962.7, self.high=29966.7, self.low=29926.0, self.vol=1142.732, self.amt=34228507.7634 
127.0.0.1 - - [22/Jun/2023 08:20:02] "POST / HTTP/1.1" 200 -
2023-06-22 08:20:07,749:INFO:amihud:main.py:172:handleKline:2219019: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5855  20230622   075500    075959  ...         0.0        0.0       0
5856  20230622   080000    080459  ...         0.0        0.0       0
5857  20230622   080500    080959  ...         0.0        0.0       0
5858  20230622   081000    081459  ...         0.0        0.0       0
5859  20230622   081500    081959  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-06-22 08:20:07,791:INFO:amihud:main.py:175:handleKline:2219019: self.closeSec=1687393199, self.tradeDate='20230622', self.openTime='081500', self.closeTime='081959',self.symbol='BTCUSDT',self.open=29946.7, self.close=29962.7, self.high=29966.7, self.low=29926.0, self.vol=1142.732, self.amt=34228507.7634, ukdf['pct'].iloc[-1]=0.000534 , ukdf['amount'].iloc[-1]=34228507.7634, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5859, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '13.926', 'enterprice': '26864.9', 'countrevence': '0', 'unrealprofit': '-43092.62733126582', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '29959.30092857', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1
--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=373746.4768026, self.flagDict['side']='sell', self.tradeCount=2, self.count=11201
self.closeSec=1687393499, self.tradeDate='20230622', self.openTime='082000', self.closeTime='082459', self.symbol='BTCUSDT', self.open=29963.5, self.close=30023.2, self.high=30036.2, self.low=29954.8, self.vol=2198.841, self.amt=65969941.0496 
127.0.0.1 - - [22/Jun/2023 08:25:00] "POST / HTTP/1.1" 200 -
2023-06-22 08:25:00,777:INFO:amihud:main.py:172:handleKline:2219019: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5856  20230622   080000    080459  ...         0.0        0.0       0
5857  20230622   080500    080959  ...         0.0        0.0       0
5858  20230622   081000    081459  ...         0.0        0.0       0
5859  20230622   081500    081959  ...         0.0        0.0       0
5860  20230622   082000    082459  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-06-22 08:25:00,777:INFO:amihud:main.py:175:handleKline:2219019: self.closeSec=1687393499, self.tradeDate='20230622', self.openTime='082000', self.closeTime='082459',self.symbol='BTCUSDT',self.open=29963.5, self.close=30023.2, self.high=30036.2, self.low=29954.8, self.vol=2198.841, self.amt=65969941.0496, ukdf['pct'].iloc[-1]=0.002019 , ukdf['amount'].iloc[-1]=65969941.0496, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5860, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '13.926', 'enterprice': '26864.9', 'countrevence': '0', 'unrealprofit': '-43981.0932', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '30023.1', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1


## /root/FIL/strategy/factorcheck/log.txt ----- -----


self.closeSec=1687393199, self.tradeDate='20230622', self.openTime='081500', self.closeTime='081959', self.symbol='BTCUSDT', self.open=29946.7, self.close=29962.7, self.high=29966.7, self.low=29926.0 
127.0.0.1 - - [22/Jun/2023 08:20:01] "POST / HTTP/1.1" 200 -
2023-06-22 08:20:04,919:INFO:factorcheck2:main.py:126:handleKline:2218005: self.closeSec=1687393199, self.tradeDate='20230622', self.openTime='081500', self.closeTime='081959',self.symbol='BTCUSDT',self.open=29946.7, self.close=29962.7, self.high=29966.7, self.low=29926.0   
2023-06-22 08:20:06,529:INFO:factorcheck2:main.py:127:handleKline:2218005: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime    closeSec  ...      low       pct  index  idx
1535  20230622   075500    075959  1687391999  ...  29967.2 -0.002050   1535    5
1536  20230622   080000    080459  1687392299  ...  29953.3 -0.000047   1536    0
1537  20230622   080500    080959  1687392599  ...  29925.8 -0.001874   1537    1
1538  20230622   081000    081459  1687392899  ...  29880.0  0.000531   1538    2
1539  20230622   081500    081959  1687393199  ...  29926.0  0.000534   1539    3

[5 rows x 11 columns]
2023-06-22 08:20:06,540:INFO:factorcheck2:main.py:128:handleKline:2218005: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=245, self.factor=0.20290398366682363, self.count=11203 

self.closeSec=1687393499, self.tradeDate='20230622', self.openTime='082000', self.closeTime='082459', self.symbol='BTCUSDT', self.open=29963.5, self.close=30023.2, self.high=30036.2, self.low=29954.8 
127.0.0.1 - - [22/Jun/2023 08:25:00] "POST / HTTP/1.1" 200 -
2023-06-22 08:25:00,741:INFO:factorcheck2:main.py:126:handleKline:2218005: self.closeSec=1687393499, self.tradeDate='20230622', self.openTime='082000', self.closeTime='082459',self.symbol='BTCUSDT',self.open=29963.5, self.close=30023.2, self.high=30036.2, self.low=29954.8   
2023-06-22 08:25:00,767:INFO:factorcheck2:main.py:127:handleKline:2218005: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime    closeSec  ...      low       pct  index  idx
1536  20230622   080000    080459  1687392299  ...  29953.3 -0.000047   1536    0
1537  20230622   080500    080959  1687392599  ...  29925.8 -0.001874   1537    1
1538  20230622   081000    081459  1687392899  ...  29880.0  0.000531   1538    2
1539  20230622   081500    081959  1687393199  ...  29926.0  0.000534   1539    3
1540  20230622   082000    082459  1687393499  ...  29954.8  0.002019   1540    4

[5 rows x 11 columns]
2023-06-22 08:25:00,767:INFO:factorcheck2:main.py:128:handleKline:2218005: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}


## /root/FIL/strategy/logic/log.txt ----- -----

2023-06-22 08:00:18,839:DEBUG:logic:main.py:463:getModel:2218526: df_s.iloc[-5:,:] :
          date closeTime     open  ...    alpha58   alpha67   alpha72
5770  20230622    052959  29977.7  ...  57.083333  0.646792  0.202317
5771  20230622    055959  29932.0  ...  57.083333  0.640039  0.218077
5772  20230622    062959  29876.4  ...  57.083333  0.645664  0.230219
5773  20230622    065959  29958.5  ...  57.500000  0.655127  0.237136
5774  20230622    072959  30103.2  ...  57.916667  0.656301  0.243059

[5 rows x 33 columns]
0.5674676524953789
acc is : 0.5674676524953789
2023-06-22 08:00:18,904:INFO:logic:main.py:468:getModel:2218526: df_pred.iloc[-5:,:] :
     pred    prob_0    prob_1  actual  ...       nav  sign  cost_        bm
536     1  0.468994  0.531006       0  ...  1.097630  -1.0    0.0  1.157503
537     1  0.473974  0.526026       1  ...  1.094581  -1.0    0.0  1.160718
538     1  0.488039  0.511961       1  ...  1.089364  -1.0    0.0  1.166251
539     0  0.509660  0.490340       1  ...  1.088716  -1.0    0.0  1.166944
540     1  0.497838  0.502162       0  ...  1.093473  -1.0    0.0  1.161846

[5 rows x 10 columns]
2023-06-22 08:00:18,917:INFO:logic:main.py:478:getModel:2218526: df_panel.iloc[-5:,:] :
    pred    prob_0    prob_1  actual  ...       nav  sign  cost_        bm
45     1  0.473822  0.526178       0  ...  1.133615  -1.0    0.0  1.166132
46     1  0.477688  0.522312       1  ...  1.130466  -1.0    0.0  1.170349
47     1  0.487522  0.512478       1  ...  1.089364  -1.0    0.0  1.176760
48     0  0.509660  0.490340       1  ...  1.088716  -1.0    0.0  1.166944
49     1  0.497838  0.502162       0  ...  1.093473  -1.0    0.0  1.161846

[5 rows x 10 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '26.839', 'enterprice': '29991.1', 'countrevence': '0', 'unrealprofit': '310.80815461817', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '29979.51953297', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}


## /root/FIL/strategy/modifiedmom/log.txt ----- -----

623  20230622   075000    075959  1687391999  30054.9  29988.4 -0.002213
2023-06-22 08:00:02,155:INFO:modifiedmom:main.py:146:handleKline:2218259: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': True, 'isOpen': False, 'isClose': True, 'isTrig': False}

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=5600 

self.closeSec=1687392599, self.tradeDate='20230622', self.openTime='080000', self.closeTime='080959', self.symbol='BTCUSDT', self.open='29988.5', self.close='29930.8'
2023-06-22 08:10:01,149:INFO:modifiedmom:main.py:144:handleKline:2218259: self.closeSec=1687392599, self.tradeDate='20230622', self.openTime='080000', self.closeTime='080959',self.symbol='BTCUSDT',self.open='29988.5', self.close='29930.8'
127.0.0.1 - - [22/Jun/2023 08:10:01] "POST / HTTP/1.1" 200 -
2023-06-22 08:10:01,165:INFO:modifiedmom:main.py:145:handleKline:2218259: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec     open    close       pct
620  20230622   072000    072959  1687390199  30135.5    30120 -0.000279
621  20230622   073000    073959  1687390799    30120  30125.3  0.000176
622  20230622   074000    074959  1687391399  30125.3  30054.9 -0.002337
623  20230622   075000    075959  1687391999  30054.9  29988.4 -0.002213
624  20230622   080000    080959  1687392599  29988.5  29930.8 -0.001921
2023-06-22 08:10:01,165:INFO:modifiedmom:main.py:146:handleKline:2218259: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': True, 'isOpen': False, 'isClose': True, 'isTrig': False}

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=5601 

self.closeSec=1687393199, self.tradeDate='20230622', self.openTime='081000', self.closeTime='081959', self.symbol='BTCUSDT', self.open='29930.9', self.close='29963.5'
127.0.0.1 - - [22/Jun/2023 08:20:04] "POST / HTTP/1.1" 200 -
2023-06-22 08:20:07,411:INFO:modifiedmom:main.py:144:handleKline:2218259: self.closeSec=1687393199, self.tradeDate='20230622', self.openTime='081000', self.closeTime='081959',self.symbol='BTCUSDT',self.open='29930.9', self.close='29963.5'
2023-06-22 08:20:08,287:INFO:modifiedmom:main.py:145:handleKline:2218259: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec     open    close       pct
621  20230622   073000    073959  1687390799    30120  30125.3  0.000176
622  20230622   074000    074959  1687391399  30125.3  30054.9 -0.002337
623  20230622   075000    075959  1687391999  30054.9  29988.4 -0.002213
624  20230622   080000    080959  1687392599  29988.5  29930.8 -0.001921
625  20230622   081000    081959  1687393199  29930.9  29963.5  0.001093
2023-06-22 08:20:08,297:INFO:modifiedmom:main.py:146:handleKline:2218259: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': True, 'isOpen': False, 'isClose': True, 'isTrig': False}


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

17471  20230622   075000    075959  1687391999  30054.9  29988.4
2023-06-22 08:00:02,179:INFO:pyemd2:main.py:127:handleKline:2217508: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=5603 

self.closeSec=1687392599, self.tradeDate='20230622', self.openTime='080000', self.closeTime='080959', self.symbol='BTCUSDT', self.open='29988.5', self.close='29930.8'
2023-06-22 08:10:01,145:INFO:pyemd2:main.py:125:handleKline:2217508: self.closeSec=1687392599, self.tradeDate='20230622', self.openTime='080000', self.closeTime='080959',self.symbol='BTCUSDT',self.open='29988.5', self.close='29930.8'
127.0.0.1 - - [22/Jun/2023 08:10:01] "POST / HTTP/1.1" 200 -
2023-06-22 08:10:01,176:INFO:pyemd2:main.py:126:handleKline:2217508: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
17468  20230622   072000    072959  1687390199  30135.5    30120
17469  20230622   073000    073959  1687390799    30120  30125.3
17470  20230622   074000    074959  1687391399  30125.3  30054.9
17471  20230622   075000    075959  1687391999  30054.9  29988.4
17472  20230622   080000    080959  1687392599  29988.5  29930.8
2023-06-22 08:10:01,177:INFO:pyemd2:main.py:127:handleKline:2217508: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=5604 

self.closeSec=1687393199, self.tradeDate='20230622', self.openTime='081000', self.closeTime='081959', self.symbol='BTCUSDT', self.open='29930.9', self.close='29963.5'
127.0.0.1 - - [22/Jun/2023 08:20:04] "POST / HTTP/1.1" 200 -
2023-06-22 08:20:09,549:INFO:pyemd2:main.py:125:handleKline:2217508: self.closeSec=1687393199, self.tradeDate='20230622', self.openTime='081000', self.closeTime='081959',self.symbol='BTCUSDT',self.open='29930.9', self.close='29963.5'
2023-06-22 08:20:09,671:INFO:pyemd2:main.py:126:handleKline:2217508: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
17469  20230622   073000    073959  1687390799    30120  30125.3
17470  20230622   074000    074959  1687391399  30125.3  30054.9
17471  20230622   075000    075959  1687391999  30054.9  29988.4
17472  20230622   080000    080959  1687392599  29988.5  29930.8
17473  20230622   081000    081959  1687393199  29930.9  29963.5
2023-06-22 08:20:09,672:INFO:pyemd2:main.py:127:handleKline:2217508: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}


## /root/FIL/strategy/similarity/log.txt ----- -----

12143  20230622   075000    075959  1687391999  30054.9  29988.4
2023-06-22 08:00:02,160:INFO:testStrategy:main.py:103:handleKline:2217133: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': True, 'isOpenSell': False, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True, 'isCorr': False}
127.0.0.1 - - [22/Jun/2023 08:10:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=5603 

self.closeSec=1687392599, self.tradeDate='20230622', self.openTime='080000', self.closeTime='080959', self.symbol='BTCUSDT', self.open='29988.5', self.close='29930.8'
2023-06-22 08:10:01,134:INFO:testStrategy:main.py:101:handleKline:2217133: self.closeSec=1687392599, self.tradeDate='20230622', self.openTime='080000', self.closeTime='080959',self.symbol='BTCUSDT',self.open='29988.5', self.close='29930.8'
2023-06-22 08:10:01,177:INFO:testStrategy:main.py:102:handleKline:2217133: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
12140  20230622   072000    072959  1687390199  30135.5    30120
12141  20230622   073000    073959  1687390799    30120  30125.3
12142  20230622   074000    074959  1687391399  30125.3  30054.9
12143  20230622   075000    075959  1687391999  30054.9  29988.4
12144  20230622   080000    080959  1687392599  29988.5  29930.8
2023-06-22 08:10:01,177:INFO:testStrategy:main.py:103:handleKline:2217133: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': True, 'isOpenSell': False, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True, 'isCorr': False}

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=5604 

self.closeSec=1687393199, self.tradeDate='20230622', self.openTime='081000', self.closeTime='081959', self.symbol='BTCUSDT', self.open='29930.9', self.close='29963.5'
127.0.0.1 - - [22/Jun/2023 08:20:04] "POST / HTTP/1.1" 200 -
2023-06-22 08:20:09,069:INFO:testStrategy:main.py:101:handleKline:2217133: self.closeSec=1687393199, self.tradeDate='20230622', self.openTime='081000', self.closeTime='081959',self.symbol='BTCUSDT',self.open='29930.9', self.close='29963.5'
2023-06-22 08:20:09,371:INFO:testStrategy:main.py:102:handleKline:2217133: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
12141  20230622   073000    073959  1687390799    30120  30125.3
12142  20230622   074000    074959  1687391399  30125.3  30054.9
12143  20230622   075000    075959  1687391999  30054.9  29988.4
12144  20230622   080000    080959  1687392599  29988.5  29930.8
12145  20230622   081000    081959  1687393199  29930.9  29963.5
2023-06-22 08:20:09,377:INFO:testStrategy:main.py:103:handleKline:2217133: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': True, 'isOpenSell': False, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True, 'isCorr': False}


## /root/FIL/strategy/sr_min/log.txt ----- -----

--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=1, self.total=996015.990996, self.flagDict['side']='buy', self.tradeCount=1, self.count=11200
self.closeSec=1687393199, self.tradeDate='20230622', self.openTime='081500', self.closeTime='081959', self.symbol='BTCUSDT', self.open=29946.7, self.close=29962.7, self.high=29966.7, self.low=29926.0, self.vol=1142.732, self.amt=34228507.7634 
127.0.0.1 - - [22/Jun/2023 08:20:01] "POST / HTTP/1.1" 200 -
2023-06-22 08:20:07,770:INFO:sr_min:main.py:172:handleKline:2219263: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5855  20230622   075500    075959  ...         0.0        0.0       0
5856  20230622   080000    080459  ...         0.0        0.0       0
5857  20230622   080500    080959  ...         0.0        0.0       0
5858  20230622   081000    081459  ...         0.0        0.0       0
5859  20230622   081500    081959  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-06-22 08:20:07,810:INFO:sr_min:main.py:175:handleKline:2219263: self.closeSec=1687393199, self.tradeDate='20230622', self.openTime='081500', self.closeTime='081959',self.symbol='BTCUSDT',self.open=29946.7, self.close=29962.7, self.high=29966.7, self.low=29926.0, self.vol=1142.732, self.amt=34228507.7634, ukdf['pct'].iloc[-1]=0.000534 , ukdf['amount'].iloc[-1]=34228507.7634, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5859, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '37.141', 'enterprice': '26844', 'countrevence': '0', 'unrealprofit': '115708.08553078164', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '29959.37345604', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=1
127.0.0.1 - - [22/Jun/2023 08:25:00] "POST / HTTP/1.1" 200 -
--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=1, self.total=996015.990996, self.flagDict['side']='buy', self.tradeCount=1, self.count=11201
self.closeSec=1687393499, self.tradeDate='20230622', self.openTime='082000', self.closeTime='082459', self.symbol='BTCUSDT', self.open=29963.5, self.close=30023.2, self.high=30036.2, self.low=29954.8, self.vol=2198.841, self.amt=65969941.0496 
2023-06-22 08:25:00,807:INFO:sr_min:main.py:172:handleKline:2219263: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5856  20230622   080000    080459  ...         0.0        0.0       0
5857  20230622   080500    080959  ...         0.0        0.0       0
5858  20230622   081000    081459  ...         0.0        0.0       0
5859  20230622   081500    081959  ...         0.0        0.0       0
5860  20230622   082000    082459  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-06-22 08:25:00,808:INFO:sr_min:main.py:175:handleKline:2219263: self.closeSec=1687393499, self.tradeDate='20230622', self.openTime='082000', self.closeTime='082459',self.symbol='BTCUSDT',self.open=29963.5, self.close=30023.2, self.high=30036.2, self.low=29954.8, self.vol=2198.841, self.amt=65969941.0496, ukdf['pct'].iloc[-1]=0.002019 , ukdf['amount'].iloc[-1]=65969941.0496, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5860, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '37.141', 'enterprice': '26844', 'countrevence': '0', 'unrealprofit': '118074.9531', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '30023.1', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=1


## /root/FIL/strategy/s_rsrs/log.txt ----- -----

719  20230621   200000    235959  1687363199  ...    719  1.341041  3.423802     1.0
720  20230622   000000    035959  1687377599  ...    720  1.404152  3.390565     1.0

[5 rows x 15 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '53.344', 'enterprice': '27977.7', 'countrevence': '0', 'unrealprofit': '114028.1344', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '30115.3', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'numpy.int64'>, curSign=1, self.sign=1
127.0.0.1 - - [22/Jun/2023 08:00:01] "POST / HTTP/1.1" 200 -
--handleKline--:  version='2.0.0', self.name='s_rsrs', self.symbol='BTCUSDT', interval='4h', intervalSec=14400, wid=25, thd=0.6, self.sign=1, self.total=1490949.9863712, self.flagDict['side']='buy', self.tradeCount=7, self.count=233
self.closeSec=1687391999, self.tradeDate='20230622', self.openTime='040000', self.closeTime='075959', self.symbol='BTCUSDT', self.open=30105.6, self.close=29988.4, self.high=30195.8, self.low=29766.0, self.vol=81982.531, self.amt=2459183386.1142 
2023-06-22 08:00:01,691:INFO:s_rsrs:main.py:141:handleKline:2218689: self.closeSec=1687391999, self.tradeDate='20230622', self.openTime='040000', self.closeTime='075959',self.symbol='BTCUSDT',self.open=30105.6, self.close=29988.4, self.high=30195.8, self.low=29766.0, self.vol=81982.531, self.amt=2459183386.1142 
2023-06-22 08:00:01,714:INFO:s_rsrs:main.py:142:handleKline:2218689: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime  ...         vol           amt       pct
717  20230621   120000    155959  ...   75606.358  2.179678e+09  0.005428
718  20230621   160000    195959  ...  108461.131  3.137990e+09  0.001840
719  20230621   200000    235959  ...  322372.247  9.486852e+09  0.031940
720  20230622   000000    035959  ...  365241.928  1.103374e+10  0.008999
721  20230622   040000    075959  ...   81982.531  2.459183e+09 -0.003890

[5 rows x 11 columns]
2023-06-22 08:00:02,905:INFO:s_rsrs:main.py:151:handleKline:2218689: df_s.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec  ...  index      beta    zscore  signal
717  20230621   120000    155959  1687334399  ...    717  1.191168  3.252635     1.0
718  20230621   160000    195959  1687348799  ...    718  1.195252  3.080212     1.0
719  20230621   200000    235959  1687363199  ...    719  1.341041  3.423802     1.0
720  20230622   000000    035959  1687377599  ...    720  1.404152  3.390565     1.0
721  20230622   040000    075959  1687391999  ...    721  1.294642  2.812975     1.0

[5 rows x 15 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '53.344', 'enterprice': '27977.7', 'countrevence': '0', 'unrealprofit': '107264.1152', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '29988.5', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'numpy.int64'>, curSign=1, self.sign=1


