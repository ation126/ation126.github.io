# 20230301 08:26:01

## /root/FIL/strategy/amihud/log.txt ----- -----

--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=993672.4896432, self.flagDict['side']='sell', self.tradeCount=2, self.count=27004
self.closeSec=1677629999, self.tradeDate='20230301', self.openTime='081500', self.closeTime='081959', self.symbol='BTCUSDT', self.open=23151.2, self.close=23174.0, self.high=23174.0, self.low=23149.9, self.vol=965.344, self.amt=22358905.4745 
127.0.0.1 - - [01/Mar/2023 08:20:01] "POST / HTTP/1.1" 200 -
2023-03-01 08:20:01,625:INFO:amihud:main.py:172:handleKline:200676: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5855  20230301   075500    075959  ...         0.0        0.0       0
5856  20230301   080000    080459  ...         0.0        0.0       0
5857  20230301   080500    080959  ...         0.0        0.0       0
5858  20230301   081000    081459  ...         0.0        0.0       0
5859  20230301   081500    081959  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-03-01 08:20:01,626:INFO:amihud:main.py:175:handleKline:200676: self.closeSec=1677629999, self.tradeDate='20230301', self.openTime='081500', self.closeTime='081959',self.symbol='BTCUSDT',self.open=23151.2, self.close=23174.0, self.high=23174.0, self.low=23149.9, self.vol=965.344, self.amt=22358905.4745, ukdf['pct'].iloc[-1]=0.000981 , ukdf['amount'].iloc[-1]=22358905.4745, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5859, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '60.176', 'enterprice': '16529.3', 'countrevence': '0', 'unrealprofit': '-399875.5376', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '23174.4', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1
--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=993672.4896432, self.flagDict['side']='sell', self.tradeCount=2, self.count=27005
self.closeSec=1677630299, self.tradeDate='20230301', self.openTime='082000', self.closeTime='082459', self.symbol='BTCUSDT', self.open=23173.9, self.close=23192.6, self.high=23209.6, self.low=23163.4, self.vol=2124.665, self.amt=49270185.3121 
127.0.0.1 - - [01/Mar/2023 08:25:01] "POST / HTTP/1.1" 200 -
2023-03-01 08:25:01,591:INFO:amihud:main.py:172:handleKline:200676: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5856  20230301   080000    080459  ...         0.0        0.0       0
5857  20230301   080500    080959  ...         0.0        0.0       0
5858  20230301   081000    081459  ...         0.0        0.0       0
5859  20230301   081500    081959  ...         0.0        0.0       0
5860  20230301   082000    082459  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-03-01 08:25:01,591:INFO:amihud:main.py:175:handleKline:200676: self.closeSec=1677630299, self.tradeDate='20230301', self.openTime='082000', self.closeTime='082459',self.symbol='BTCUSDT',self.open=23173.9, self.close=23192.6, self.high=23209.6, self.low=23163.4, self.vol=2124.665, self.amt=49270185.3121, ukdf['pct'].iloc[-1]=0.000803 , ukdf['amount'].iloc[-1]=49270185.3121, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5860, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '60.176', 'enterprice': '16529.3', 'countrevence': '0', 'unrealprofit': '-401042.48512089344', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '23193.79224144', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1


## /root/FIL/strategy/factorcheck/log.txt ----- -----


self.closeSec=1677629999, self.tradeDate='20230301', self.openTime='081500', self.closeTime='081959', self.symbol='BTCUSDT', self.open=23151.2, self.close=23174.0, self.high=23174.0, self.low=23149.9 
127.0.0.1 - - [01/Mar/2023 08:20:01] "POST / HTTP/1.1" 200 -
2023-03-01 08:20:01,508:INFO:factorcheck2:main.py:126:handleKline:185239: self.closeSec=1677629999, self.tradeDate='20230301', self.openTime='081500', self.closeTime='081959',self.symbol='BTCUSDT',self.open=23151.2, self.close=23174.0, self.high=23174.0, self.low=23149.9   
2023-03-01 08:20:01,577:INFO:factorcheck2:main.py:127:handleKline:185239: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime    closeSec  ...      low       pct  index  idx
1535  20230301   075500    075959  1677628799  ...  23102.0  0.000774   1535    5
1536  20230301   080000    080459  1677629099  ...  23120.3  0.001703   1536    0
1537  20230301   080500    080959  1677629399  ...  23108.4 -0.002585   1537    1
1538  20230301   081000    081459  1677629699  ...  23107.6  0.001826   1538    2
1539  20230301   081500    081959  1677629999  ...  23149.9  0.000981   1539    3

[5 rows x 11 columns]
2023-03-01 08:20:01,578:INFO:factorcheck2:main.py:128:handleKline:185239: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=84, self.factor=0.5699592308051976, self.count=27571 

self.closeSec=1677630299, self.tradeDate='20230301', self.openTime='082000', self.closeTime='082459', self.symbol='BTCUSDT', self.open=23173.9, self.close=23192.6, self.high=23209.6, self.low=23163.4 
2023-03-01 08:25:01,502:INFO:factorcheck2:main.py:126:handleKline:185239: self.closeSec=1677630299, self.tradeDate='20230301', self.openTime='082000', self.closeTime='082459',self.symbol='BTCUSDT',self.open=23173.9, self.close=23192.6, self.high=23209.6, self.low=23163.4   
127.0.0.1 - - [01/Mar/2023 08:25:01] "POST / HTTP/1.1" 200 -
2023-03-01 08:25:01,552:INFO:factorcheck2:main.py:127:handleKline:185239: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime    closeSec  ...      low       pct  index  idx
1536  20230301   080000    080459  1677629099  ...  23120.3  0.001703   1536    0
1537  20230301   080500    080959  1677629399  ...  23108.4 -0.002585   1537    1
1538  20230301   081000    081459  1677629699  ...  23107.6  0.001826   1538    2
1539  20230301   081500    081959  1677629999  ...  23149.9  0.000981   1539    3
1540  20230301   082000    082459  1677630299  ...  23163.4  0.000803   1540    4

[5 rows x 11 columns]
2023-03-01 08:25:01,554:INFO:factorcheck2:main.py:128:handleKline:185239: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}


## /root/FIL/strategy/logic/log.txt ----- -----

2023-03-01 08:00:32,780:DEBUG:logic:main.py:463:getModel:885513: df_s.iloc[-5:,:] :
          date closeTime     open  ...    alpha58   alpha67   alpha72
5770  20230301    052959  23259.9  ...  48.333333  0.455677  0.540482
5771  20230301    055959  23181.3  ...  48.333333  0.444681  0.557756
5772  20230301    062959  23126.7  ...  48.750000  0.458552  0.567392
5773  20230301    065959  23183.4  ...  48.333333  0.451689  0.580252
5774  20230301    072959  23149.7  ...  47.916667  0.445231  0.595927

[5 rows x 33 columns]
0.532347504621072
acc is : 0.532347504621072
2023-03-01 08:00:32,939:INFO:logic:main.py:468:getModel:885513: df_pred.iloc[-5:,:] :
     pred    prob_0    prob_1  actual  ...       nav  sign  cost_        bm
536     1  0.473462  0.526538       0  ...  0.886165  -1.0    0.0  0.948566
537     1  0.493783  0.506217       1  ...  0.883992  -1.0    0.0  0.950892
538     0  0.514833  0.485167       0  ...  0.885281  -1.0    0.0  0.949505
539     1  0.496048  0.503952       0  ...  0.886509  -1.0    0.0  0.948189
540     1  0.491986  0.508014       1  ...  0.886048  -1.0    0.0  0.948681

[5 rows x 10 columns]
2023-03-01 08:00:32,976:INFO:logic:main.py:478:getModel:885513: df_panel.iloc[-5:,:] :
    pred    prob_0    prob_1  actual  ...       nav  sign  cost_        bm
45     1  0.474094  0.525906       0  ...  0.895322  -1.0    0.0  0.958370
46     1  0.494768  0.505232       1  ...  0.883992  -1.0    0.0  0.965006
47     0  0.515349  0.484651       0  ...  0.885281  -1.0    0.0  0.960939
48     1  0.496017  0.503983       0  ...  0.886509  -1.0    0.0  0.948189
49     1  0.491986  0.508014       1  ...  0.886048  -1.0    0.0  0.948681

[5 rows x 10 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '32.752', 'enterprice': '23379.5', 'countrevence': '0', 'unrealprofit': '8276.4304', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '23126.8', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}


## /root/FIL/strategy/modifiedmom/log.txt ----- -----

623  20230301   075000    075959  1677628799  23125.4  23129.6  0.000186
2023-03-01 08:00:01,930:INFO:modifiedmom:main.py:146:handleKline:185213: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': True, 'isOpen': False, 'isClose': True, 'isTrig': False}

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=13784 

self.closeSec=1677629399, self.tradeDate='20230301', self.openTime='080000', self.closeTime='080959', self.symbol='BTCUSDT', self.open='23129.7', self.close='23109.1'
2023-03-01 08:10:01,733:INFO:modifiedmom:main.py:144:handleKline:185213: self.closeSec=1677629399, self.tradeDate='20230301', self.openTime='080000', self.closeTime='080959',self.symbol='BTCUSDT',self.open='23129.7', self.close='23109.1'
2023-03-01 08:10:01,743:INFO:modifiedmom:main.py:145:handleKline:185213: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec     open    close       pct
620  20230301   072000    072959  1677626999  23171.9  23117.6 -0.002343
621  20230301   073000    073959  1677627599  23117.6  23141.4  0.001030
622  20230301   074000    074959  1677628199  23141.4  23125.3 -0.000696
623  20230301   075000    075959  1677628799  23125.4  23129.6  0.000186
624  20230301   080000    080959  1677629399  23129.7  23109.1 -0.000886
2023-03-01 08:10:01,743:INFO:modifiedmom:main.py:146:handleKline:185213: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': True, 'isOpen': False, 'isClose': True, 'isTrig': False}
127.0.0.1 - - [01/Mar/2023 08:10:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=13785 

self.closeSec=1677629999, self.tradeDate='20230301', self.openTime='081000', self.closeTime='081959', self.symbol='BTCUSDT', self.open='23108.4', self.close='23174'
2023-03-01 08:20:01,615:INFO:modifiedmom:main.py:144:handleKline:185213: self.closeSec=1677629999, self.tradeDate='20230301', self.openTime='081000', self.closeTime='081959',self.symbol='BTCUSDT',self.open='23108.4', self.close='23174'
127.0.0.1 - - [01/Mar/2023 08:20:01] "POST / HTTP/1.1" 200 -
2023-03-01 08:20:01,652:INFO:modifiedmom:main.py:145:handleKline:185213: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec     open    close       pct
621  20230301   073000    073959  1677627599  23117.6  23141.4  0.001030
622  20230301   074000    074959  1677628199  23141.4  23125.3 -0.000696
623  20230301   075000    075959  1677628799  23125.4  23129.6  0.000186
624  20230301   080000    080959  1677629399  23129.7  23109.1 -0.000886
625  20230301   081000    081959  1677629999  23108.4    23174  0.002808
2023-03-01 08:20:01,653:INFO:modifiedmom:main.py:146:handleKline:185213: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': True, 'isOpen': False, 'isClose': True, 'isTrig': False}


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

17471  20230301   075000    075959  1677628799  23125.4  23129.6
2023-03-01 08:00:01,943:INFO:pyemd2:main.py:127:handleKline:185189: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}
127.0.0.1 - - [01/Mar/2023 08:10:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=13785 

self.closeSec=1677629399, self.tradeDate='20230301', self.openTime='080000', self.closeTime='080959', self.symbol='BTCUSDT', self.open='23129.7', self.close='23109.1'
2023-03-01 08:10:01,743:INFO:pyemd2:main.py:125:handleKline:185189: self.closeSec=1677629399, self.tradeDate='20230301', self.openTime='080000', self.closeTime='080959',self.symbol='BTCUSDT',self.open='23129.7', self.close='23109.1'
2023-03-01 08:10:01,769:INFO:pyemd2:main.py:126:handleKline:185189: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
17468  20230301   072000    072959  1677626999  23171.9  23117.6
17469  20230301   073000    073959  1677627599  23117.6  23141.4
17470  20230301   074000    074959  1677628199  23141.4  23125.3
17471  20230301   075000    075959  1677628799  23125.4  23129.6
17472  20230301   080000    080959  1677629399  23129.7  23109.1
2023-03-01 08:10:01,771:INFO:pyemd2:main.py:127:handleKline:185189: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}
127.0.0.1 - - [01/Mar/2023 08:20:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=13786 

self.closeSec=1677629999, self.tradeDate='20230301', self.openTime='081000', self.closeTime='081959', self.symbol='BTCUSDT', self.open='23108.4', self.close='23174'
2023-03-01 08:20:01,645:INFO:pyemd2:main.py:125:handleKline:185189: self.closeSec=1677629999, self.tradeDate='20230301', self.openTime='081000', self.closeTime='081959',self.symbol='BTCUSDT',self.open='23108.4', self.close='23174'
2023-03-01 08:20:01,684:INFO:pyemd2:main.py:126:handleKline:185189: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
17469  20230301   073000    073959  1677627599  23117.6  23141.4
17470  20230301   074000    074959  1677628199  23141.4  23125.3
17471  20230301   075000    075959  1677628799  23125.4  23129.6
17472  20230301   080000    080959  1677629399  23129.7  23109.1
17473  20230301   081000    081959  1677629999  23108.4    23174
2023-03-01 08:20:01,684:INFO:pyemd2:main.py:127:handleKline:185189: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}


## /root/FIL/strategy/similarity/log.txt ----- -----

12143  20230301   075000    075959  1677628799  23125.4  23129.6
2023-03-01 08:00:01,938:INFO:testStrategy:main.py:103:handleKline:185174: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': True, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True, 'isCorr': False}
127.0.0.1 - - [01/Mar/2023 08:10:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=13785 

self.closeSec=1677629399, self.tradeDate='20230301', self.openTime='080000', self.closeTime='080959', self.symbol='BTCUSDT', self.open='23129.7', self.close='23109.1'
2023-03-01 08:10:01,741:INFO:testStrategy:main.py:101:handleKline:185174: self.closeSec=1677629399, self.tradeDate='20230301', self.openTime='080000', self.closeTime='080959',self.symbol='BTCUSDT',self.open='23129.7', self.close='23109.1'
2023-03-01 08:10:01,767:INFO:testStrategy:main.py:102:handleKline:185174: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
12140  20230301   072000    072959  1677626999  23171.9  23117.6
12141  20230301   073000    073959  1677627599  23117.6  23141.4
12142  20230301   074000    074959  1677628199  23141.4  23125.3
12143  20230301   075000    075959  1677628799  23125.4  23129.6
12144  20230301   080000    080959  1677629399  23129.7  23109.1
2023-03-01 08:10:01,768:INFO:testStrategy:main.py:103:handleKline:185174: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': True, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True, 'isCorr': False}
127.0.0.1 - - [01/Mar/2023 08:20:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=13786 

self.closeSec=1677629999, self.tradeDate='20230301', self.openTime='081000', self.closeTime='081959', self.symbol='BTCUSDT', self.open='23108.4', self.close='23174'
2023-03-01 08:20:01,623:INFO:testStrategy:main.py:101:handleKline:185174: self.closeSec=1677629999, self.tradeDate='20230301', self.openTime='081000', self.closeTime='081959',self.symbol='BTCUSDT',self.open='23108.4', self.close='23174'
2023-03-01 08:20:01,672:INFO:testStrategy:main.py:102:handleKline:185174: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
12141  20230301   073000    073959  1677627599  23117.6  23141.4
12142  20230301   074000    074959  1677628199  23141.4  23125.3
12143  20230301   075000    075959  1677628799  23125.4  23129.6
12144  20230301   080000    080959  1677629399  23129.7  23109.1
12145  20230301   081000    081959  1677629999  23108.4    23174
2023-03-01 08:20:01,673:INFO:testStrategy:main.py:103:handleKline:185174: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': True, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True, 'isCorr': False}


## /root/FIL/strategy/sr_min/log.txt ----- -----

127.0.0.1 - - [01/Mar/2023 08:20:01] "POST / HTTP/1.1" 200 -
--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=0, self.total=1000000.0, self.flagDict['side']='', self.tradeCount=0, self.count=23002
self.closeSec=1677629999, self.tradeDate='20230301', self.openTime='081500', self.closeTime='081959', self.symbol='BTCUSDT', self.open=23151.2, self.close=23174.0, self.high=23174.0, self.low=23149.9, self.vol=965.344, self.amt=22358905.4745 
2023-03-01 08:20:01,619:INFO:sr_min:main.py:172:handleKline:449472: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5855  20230301   075500    075959  ...         0.0        0.0       0
5856  20230301   080000    080459  ...         0.0        0.0       0
5857  20230301   080500    080959  ...         0.0        0.0       0
5858  20230301   081000    081459  ...         0.0        0.0       0
5859  20230301   081500    081959  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-03-01 08:20:01,619:INFO:sr_min:main.py:175:handleKline:449472: self.closeSec=1677629999, self.tradeDate='20230301', self.openTime='081500', self.closeTime='081959',self.symbol='BTCUSDT',self.open=23151.2, self.close=23174.0, self.high=23174.0, self.low=23149.9, self.vol=965.344, self.amt=22358905.4745, ukdf['pct'].iloc[-1]=0.000981 , ukdf['amount'].iloc[-1]=22358905.4745, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5859, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': []}
type(curSign)=<class 'int'>, curSign=0, self.sign=0
127.0.0.1 - - [01/Mar/2023 08:25:01] "POST / HTTP/1.1" 200 -
--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=0, self.total=1000000.0, self.flagDict['side']='', self.tradeCount=0, self.count=23003
self.closeSec=1677630299, self.tradeDate='20230301', self.openTime='082000', self.closeTime='082459', self.symbol='BTCUSDT', self.open=23173.9, self.close=23192.6, self.high=23209.6, self.low=23163.4, self.vol=2124.665, self.amt=49270185.3121 
2023-03-01 08:25:01,582:INFO:sr_min:main.py:172:handleKline:449472: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5856  20230301   080000    080459  ...         0.0        0.0       0
5857  20230301   080500    080959  ...         0.0        0.0       0
5858  20230301   081000    081459  ...         0.0        0.0       0
5859  20230301   081500    081959  ...         0.0        0.0       0
5860  20230301   082000    082459  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-03-01 08:25:01,584:INFO:sr_min:main.py:175:handleKline:449472: self.closeSec=1677630299, self.tradeDate='20230301', self.openTime='082000', self.closeTime='082459',self.symbol='BTCUSDT',self.open=23173.9, self.close=23192.6, self.high=23209.6, self.low=23163.4, self.vol=2124.665, self.amt=49270185.3121, ukdf['pct'].iloc[-1]=0.000803 , ukdf['amount'].iloc[-1]=49270185.3121, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5860, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': []}
type(curSign)=<class 'int'>, curSign=0, self.sign=0


## /root/FIL/strategy/s_rsrs/log.txt ----- -----

719  20230228   200000    235959  1677599999  ...    719  0.558675 -0.210626     NaN
720  20230301   000000    035959  1677614399  ...    720  0.490960 -0.389624     NaN

[5 rows x 15 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '42.179', 'enterprice': '23108.8', 'countrevence': '0', 'unrealprofit': '5758.02167603204', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '23245.31394476', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'numpy.int64'>, curSign=-9223372036854775808, self.sign=1
--handleKline--:  version='2.0.0', self.name='s_rsrs', self.symbol='BTCUSDT', interval='4h', intervalSec=14400, wid=25, thd=0.6, self.sign=1, self.total=973731.3691248, self.flagDict['side']='buy', self.tradeCount=22, self.count=574
self.closeSec=1677628799, self.tradeDate='20230301', self.openTime='040000', self.closeTime='075959', self.symbol='BTCUSDT', self.open=23251.1, self.close=23129.6, self.high=23333.4, self.low=23010.0, self.vol=100091.272, self.amt=2318269477.74691 
127.0.0.1 - - [01/Mar/2023 08:00:01] "POST / HTTP/1.1" 200 -
2023-03-01 08:00:01,778:INFO:s_rsrs:main.py:141:handleKline:185271: self.closeSec=1677628799, self.tradeDate='20230301', self.openTime='040000', self.closeTime='075959',self.symbol='BTCUSDT',self.open=23251.1, self.close=23129.6, self.high=23333.4, self.low=23010.0, self.vol=100091.272, self.amt=2318269477.74691 
2023-03-01 08:00:01,816:INFO:s_rsrs:main.py:142:handleKline:185271: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime  ...         vol           amt       pct
717  20230228   120000    155959  ...   44074.367  1.028988e+09 -0.009849
718  20230228   160000    195959  ...   51908.370  1.209622e+09  0.006816
719  20230228   200000    235959  ...  126298.911  2.961352e+09  0.005543
720  20230301   000000    035959  ...   90462.656  2.118301e+09 -0.011067
721  20230301   040000    075959  ...  100091.272  2.318269e+09 -0.005221

[5 rows x 11 columns]
2023-03-01 08:00:04,282:INFO:s_rsrs:main.py:151:handleKline:185271: df_s.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec  ...  index      beta    zscore  signal
717  20230228   120000    155959  1677571199  ...    717  0.613378 -0.076614     NaN
718  20230228   160000    195959  1677585599  ...    718  0.590085 -0.133811     NaN
719  20230228   200000    235959  1677599999  ...    719  0.558675 -0.210626     NaN
720  20230301   000000    035959  1677614399  ...    720  0.490960 -0.389624     NaN
721  20230301   040000    075959  1677628799  ...    721  0.635610 -0.042715     NaN

[5 rows x 15 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '42.179', 'enterprice': '23108.8', 'countrevence': '0', 'unrealprofit': '877.3232', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '23129.6', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'numpy.int64'>, curSign=-9223372036854775808, self.sign=1


