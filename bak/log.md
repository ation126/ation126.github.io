# 20230222 08:26:02

## /root/FIL/strategy/amihud/log.txt ----- -----

--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=993672.4896432, self.flagDict['side']='sell', self.tradeCount=2, self.count=24988
self.closeSec=1677025199, self.tradeDate='20230222', self.openTime='081500', self.closeTime='081959', self.symbol='BTCUSDT', self.open=24438.0, self.close=24421.9, self.high=24463.2, self.low=24416.6, self.vol=1091.188, self.amt=26670651.0612 
127.0.0.1 - - [22/Feb/2023 08:20:01] "POST / HTTP/1.1" 200 -
2023-02-22 08:20:01,930:INFO:amihud:main.py:172:handleKline:200676: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5855  20230222   075500    075959  ...         0.0        0.0       0
5856  20230222   080000    080459  ...         0.0        0.0       0
5857  20230222   080500    080959  ...         0.0        0.0       0
5858  20230222   081000    081459  ...         0.0        0.0       0
5859  20230222   081500    081959  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-02-22 08:20:01,934:INFO:amihud:main.py:175:handleKline:200676: self.closeSec=1677025199, self.tradeDate='20230222', self.openTime='081500', self.closeTime='081959',self.symbol='BTCUSDT',self.open=24438.0, self.close=24421.9, self.high=24463.2, self.low=24416.6, self.vol=1091.188, self.amt=26670651.0612, ukdf['pct'].iloc[-1]=-0.000663 , ukdf['amount'].iloc[-1]=26670651.0612, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5859, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '60.176', 'enterprice': '16529.3', 'countrevence': '0', 'unrealprofit': '-474861.57941866048', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '24420.51210148', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1
--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=993672.4896432, self.flagDict['side']='sell', self.tradeCount=2, self.count=24989
self.closeSec=1677025499, self.tradeDate='20230222', self.openTime='082000', self.closeTime='082459', self.symbol='BTCUSDT', self.open=24421.8, self.close=24416.6, self.high=24433.9, self.low=24407.5, self.vol=802.134, self.amt=19585225.5399 
127.0.0.1 - - [22/Feb/2023 08:25:01] "POST / HTTP/1.1" 200 -
2023-02-22 08:25:01,583:INFO:amihud:main.py:172:handleKline:200676: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5856  20230222   080000    080459  ...         0.0        0.0       0
5857  20230222   080500    080959  ...         0.0        0.0       0
5858  20230222   081000    081459  ...         0.0        0.0       0
5859  20230222   081500    081959  ...         0.0        0.0       0
5860  20230222   082000    082459  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-02-22 08:25:01,585:INFO:amihud:main.py:175:handleKline:200676: self.closeSec=1677025499, self.tradeDate='20230222', self.openTime='082000', self.closeTime='082459',self.symbol='BTCUSDT',self.open=24421.8, self.close=24416.6, self.high=24433.9, self.low=24407.5, self.vol=802.134, self.amt=19585225.5399, ukdf['pct'].iloc[-1]=-0.000217 , ukdf['amount'].iloc[-1]=19585225.5399, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5860, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '60.176', 'enterprice': '16529.3', 'countrevence': '0', 'unrealprofit': '-474487.76', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '24414.3', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1


## /root/FIL/strategy/factorcheck/log.txt ----- -----

 version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=0, self.factor=0.6112197785079806, self.count=25554 

self.closeSec=1677025199, self.tradeDate='20230222', self.openTime='081500', self.closeTime='081959', self.symbol='BTCUSDT', self.open=24438.0, self.close=24421.9, self.high=24463.2, self.low=24416.6 
2023-02-22 08:20:01,587:INFO:factorcheck2:main.py:126:handleKline:185239: self.closeSec=1677025199, self.tradeDate='20230222', self.openTime='081500', self.closeTime='081959',self.symbol='BTCUSDT',self.open=24438.0, self.close=24421.9, self.high=24463.2, self.low=24416.6   
2023-02-22 08:20:01,611:INFO:factorcheck2:main.py:127:handleKline:185239: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime    closeSec  ...      low       pct  index  idx
1535  20230222   075500    075959  1677023999  ...  24402.7  0.001151   1535    5
1536  20230222   080000    080459  1677024299  ...  24411.5  0.000016   1536    0
1537  20230222   080500    080959  1677024599  ...  24438.1  0.000949   1537    1
1538  20230222   081000    081459  1677024899  ...  24431.4 -0.001181   1538    2
1539  20230222   081500    081959  1677025199  ...  24416.6 -0.000663   1539    3

[5 rows x 11 columns]
2023-02-22 08:20:01,612:INFO:factorcheck2:main.py:128:handleKline:185239: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': True, 'isOpenSell': False, 'isCloseBuy': False, 'isCloseSell': False, 'isOpen': True, 'isClose': False, 'isTrig': True}

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=0, self.factor=0.6112197785079806, self.count=25555 

self.closeSec=1677025499, self.tradeDate='20230222', self.openTime='082000', self.closeTime='082459', self.symbol='BTCUSDT', self.open=24421.8, self.close=24416.6, self.high=24433.9, self.low=24407.5 
2023-02-22 08:25:01,504:INFO:factorcheck2:main.py:126:handleKline:185239: self.closeSec=1677025499, self.tradeDate='20230222', self.openTime='082000', self.closeTime='082459',self.symbol='BTCUSDT',self.open=24421.8, self.close=24416.6, self.high=24433.9, self.low=24407.5   
127.0.0.1 - - [22/Feb/2023 08:25:01] "POST / HTTP/1.1" 200 -
2023-02-22 08:25:01,546:INFO:factorcheck2:main.py:127:handleKline:185239: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime    closeSec  ...      low       pct  index  idx
1536  20230222   080000    080459  1677024299  ...  24411.5  0.000016   1536    0
1537  20230222   080500    080959  1677024599  ...  24438.1  0.000949   1537    1
1538  20230222   081000    081459  1677024899  ...  24431.4 -0.001181   1538    2
1539  20230222   081500    081959  1677025199  ...  24416.6 -0.000663   1539    3
1540  20230222   082000    082459  1677025499  ...  24407.5 -0.000217   1540    4

[5 rows x 11 columns]
2023-02-22 08:25:01,547:INFO:factorcheck2:main.py:128:handleKline:185239: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': True, 'isOpenSell': False, 'isCloseBuy': False, 'isCloseSell': False, 'isOpen': True, 'isClose': False, 'isTrig': True}


## /root/FIL/strategy/logic/log.txt ----- -----

2023-02-22 08:00:34,859:DEBUG:logic:main.py:463:getModel:885513: df_s.iloc[-5:,:] :
          date closeTime     open  ...    alpha58   alpha67   alpha72
5770  20230222    052959  24468.1  ...  49.583333  0.432614  0.709830
5771  20230222    055959  24222.1  ...  49.166667  0.428339  0.726882
5772  20230222    062959  24195.3  ...  49.583333  0.445321  0.737252
5773  20230222    065959  24290.8  ...  50.000000  0.459804  0.742026
5774  20230222    072959  24379.0  ...  50.000000  0.455752  0.748119

[5 rows x 33 columns]
0.5249537892791127
acc is : 0.5249537892791127
2023-02-22 08:00:35,059:INFO:logic:main.py:468:getModel:885513: df_pred.iloc[-5:,:] :
     pred    prob_0    prob_1  actual  ...       nav  sign   cost_        bm
536     1  0.433146  0.566854       0  ...  1.037428  -1.0 -0.0016  1.121765
537     1  0.466518  0.533482       1  ...  1.033157  -1.0  0.0000  1.126384
538     1  0.499038  0.500962       1  ...  1.029410  -1.0  0.0000  1.130469
539     0  0.519912  0.480088       0  ...  1.030651  -1.0  0.0000  1.129106
540     1  0.496773  0.503227       1  ...  1.026677  -1.0  0.0000  1.133460

[5 rows x 10 columns]
2023-02-22 08:00:35,102:INFO:logic:main.py:478:getModel:885513: df_panel.iloc[-5:,:] :
    pred    prob_0    prob_1  actual  ...       nav  sign   cost_        bm
45     1  0.431070  0.568930       0  ...  1.085917  -1.0 -0.0016  1.117433
46     1  0.465264  0.534736       1  ...  1.081446  -1.0  0.0000  1.123295
47     1  0.498537  0.501463       1  ...  1.029410  -1.0  0.0000  1.128543
48     0  0.519830  0.480170       0  ...  1.030651  -1.0  0.0000  1.129106
49     1  0.496773  0.503227       1  ...  1.026677  -1.0  0.0000  1.133460

[5 rows x 10 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '34.462', 'enterprice': '24198', 'countrevence': '0', 'unrealprofit': '-8199.85631511652', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '24435.93907246', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}


## /root/FIL/strategy/modifiedmom/log.txt ----- -----

623  20230222   075000    075959  1677023999  24387.2  24443.4  0.002309
2023-02-22 08:00:02,432:INFO:modifiedmom:main.py:146:handleKline:185213: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': True, 'isOpen': False, 'isClose': True, 'isTrig': False}

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=12776 

self.closeSec=1677024599, self.tradeDate='20230222', self.openTime='080000', self.closeTime='080959', self.symbol='BTCUSDT', self.open='24443.3', self.close='24467'
2023-02-22 08:10:01,590:INFO:modifiedmom:main.py:144:handleKline:185213: self.closeSec=1677024599, self.tradeDate='20230222', self.openTime='080000', self.closeTime='080959',self.symbol='BTCUSDT',self.open='24443.3', self.close='24467'
127.0.0.1 - - [22/Feb/2023 08:10:01] "POST / HTTP/1.1" 200 -
2023-02-22 08:10:01,628:INFO:modifiedmom:main.py:145:handleKline:185213: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec     open    close       pct
620  20230222   072000    072959  1677022199  24357.8  24349.5 -0.000353
621  20230222   073000    073959  1677022799  24349.5  24387.3  0.001552
622  20230222   074000    074959  1677023399  24387.3  24387.1 -0.000008
623  20230222   075000    075959  1677023999  24387.2  24443.4  0.002309
624  20230222   080000    080959  1677024599  24443.3    24467  0.000965
2023-02-22 08:10:01,628:INFO:modifiedmom:main.py:146:handleKline:185213: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': True, 'isOpen': False, 'isClose': True, 'isTrig': False}

--handleKline--: 127.0.0.1 - - [22/Feb/2023 08:20:01] "POST / HTTP/1.1" 200 -
 self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=12777 

self.closeSec=1677025199, self.tradeDate='20230222', self.openTime='081000', self.closeTime='081959', self.symbol='BTCUSDT', self.open='24467', self.close='24421.9'
2023-02-22 08:20:01,788:INFO:modifiedmom:main.py:144:handleKline:185213: self.closeSec=1677025199, self.tradeDate='20230222', self.openTime='081000', self.closeTime='081959',self.symbol='BTCUSDT',self.open='24467', self.close='24421.9'
2023-02-22 08:20:01,807:INFO:modifiedmom:main.py:145:handleKline:185213: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec     open    close       pct
621  20230222   073000    073959  1677022799  24349.5  24387.3  0.001552
622  20230222   074000    074959  1677023399  24387.3  24387.1 -0.000008
623  20230222   075000    075959  1677023999  24387.2  24443.4  0.002309
624  20230222   080000    080959  1677024599  24443.3    24467  0.000965
625  20230222   081000    081959  1677025199    24467  24421.9 -0.001843
2023-02-22 08:20:01,807:INFO:modifiedmom:main.py:146:handleKline:185213: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': True, 'isOpen': False, 'isClose': True, 'isTrig': False}


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

17471  20230222   075000    075959  1677023999  24387.2  24443.4
2023-02-22 08:00:02,379:INFO:pyemd2:main.py:127:handleKline:185189: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=12777 

self.closeSec=1677024599, self.tradeDate='20230222', self.openTime='080000', self.closeTime='080959', self.symbol='BTCUSDT', self.open='24443.3', self.close='24467'
2023-02-22 08:10:01,596:INFO:pyemd2:main.py:125:handleKline:185189: self.closeSec=1677024599, self.tradeDate='20230222', self.openTime='080000', self.closeTime='080959',self.symbol='BTCUSDT',self.open='24443.3', self.close='24467'
127.0.0.1 - - [22/Feb/2023 08:10:01] "POST / HTTP/1.1" 200 -
2023-02-22 08:10:01,656:INFO:pyemd2:main.py:126:handleKline:185189: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
17468  20230222   072000    072959  1677022199  24357.8  24349.5
17469  20230222   073000    073959  1677022799  24349.5  24387.3
17470  20230222   074000    074959  1677023399  24387.3  24387.1
17471  20230222   075000    075959  1677023999  24387.2  24443.4
17472  20230222   080000    080959  1677024599  24443.3    24467
2023-02-22 08:10:01,656:INFO:pyemd2:main.py:127:handleKline:185189: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=12778 

self.closeSec=1677025199, self.tradeDate='20230222', self.openTime='081000', self.closeTime='081959', self.symbol='BTCUSDT', self.open='24467', self.close='24421.9'
127.0.0.1 - - [22/Feb/2023 08:20:01] "POST / HTTP/1.1" 200 -
2023-02-22 08:20:01,865:INFO:pyemd2:main.py:125:handleKline:185189: self.closeSec=1677025199, self.tradeDate='20230222', self.openTime='081000', self.closeTime='081959',self.symbol='BTCUSDT',self.open='24467', self.close='24421.9'
2023-02-22 08:20:01,894:INFO:pyemd2:main.py:126:handleKline:185189: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
17469  20230222   073000    073959  1677022799  24349.5  24387.3
17470  20230222   074000    074959  1677023399  24387.3  24387.1
17471  20230222   075000    075959  1677023999  24387.2  24443.4
17472  20230222   080000    080959  1677024599  24443.3    24467
17473  20230222   081000    081959  1677025199    24467  24421.9
2023-02-22 08:20:01,897:INFO:pyemd2:main.py:127:handleKline:185189: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}


## /root/FIL/strategy/similarity/log.txt ----- -----

12143  20230222   075000    075959  1677023999  24387.2  24443.4
2023-02-22 08:00:02,443:INFO:testStrategy:main.py:103:handleKline:185174: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': True, 'isOpenSell': False, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True, 'isCorr': False}

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=12777 

self.closeSec=1677024599, self.tradeDate='20230222', self.openTime='080000', self.closeTime='080959', self.symbol='BTCUSDT', self.open='24443.3', self.close='24467'
2023-02-22 08:10:01,630:INFO:testStrategy:main.py:101:handleKline:185174: self.closeSec=1677024599, self.tradeDate='20230222', self.openTime='080000', self.closeTime='080959',self.symbol='BTCUSDT',self.open='24443.3', self.close='24467'
127.0.0.1 - - [22/Feb/2023 08:10:01] "POST / HTTP/1.1" 200 -
2023-02-22 08:10:01,688:INFO:testStrategy:main.py:102:handleKline:185174: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
12140  20230222   072000    072959  1677022199  24357.8  24349.5
12141  20230222   073000    073959  1677022799  24349.5  24387.3
12142  20230222   074000    074959  1677023399  24387.3  24387.1
12143  20230222   075000    075959  1677023999  24387.2  24443.4
12144  20230222   080000    080959  1677024599  24443.3    24467
2023-02-22 08:10:01,689:INFO:testStrategy:main.py:103:handleKline:185174: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': True, 'isOpenSell': False, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True, 'isCorr': False}

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=12778 

self.closeSec=1677025199, self.tradeDate='20230222', self.openTime='081000', self.closeTime='081959', self.symbol='BTCUSDT', self.open='24467', self.close='24421.9'
127.0.0.1 - - [22/Feb/2023 08:20:01] "POST / HTTP/1.1" 200 -
2023-02-22 08:20:01,860:INFO:testStrategy:main.py:101:handleKline:185174: self.closeSec=1677025199, self.tradeDate='20230222', self.openTime='081000', self.closeTime='081959',self.symbol='BTCUSDT',self.open='24467', self.close='24421.9'
2023-02-22 08:20:01,886:INFO:testStrategy:main.py:102:handleKline:185174: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
12141  20230222   073000    073959  1677022799  24349.5  24387.3
12142  20230222   074000    074959  1677023399  24387.3  24387.1
12143  20230222   075000    075959  1677023999  24387.2  24443.4
12144  20230222   080000    080959  1677024599  24443.3    24467
12145  20230222   081000    081959  1677025199    24467  24421.9
2023-02-22 08:20:01,886:INFO:testStrategy:main.py:103:handleKline:185174: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': True, 'isOpenSell': False, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True, 'isCorr': False}


## /root/FIL/strategy/sr_min/log.txt ----- -----

127.0.0.1 - - [22/Feb/2023 08:20:01] "POST / HTTP/1.1" 200 -
--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=0, self.total=1000000.0, self.flagDict['side']='', self.tradeCount=0, self.count=20986
self.closeSec=1677025199, self.tradeDate='20230222', self.openTime='081500', self.closeTime='081959', self.symbol='BTCUSDT', self.open=24438.0, self.close=24421.9, self.high=24463.2, self.low=24416.6, self.vol=1091.188, self.amt=26670651.0612 
2023-02-22 08:20:01,608:INFO:sr_min:main.py:172:handleKline:449472: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5855  20230222   075500    075959  ...         0.0        0.0       0
5856  20230222   080000    080459  ...         0.0        0.0       0
5857  20230222   080500    080959  ...         0.0        0.0       0
5858  20230222   081000    081459  ...         0.0        0.0       0
5859  20230222   081500    081959  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-02-22 08:20:01,616:INFO:sr_min:main.py:175:handleKline:449472: self.closeSec=1677025199, self.tradeDate='20230222', self.openTime='081500', self.closeTime='081959',self.symbol='BTCUSDT',self.open=24438.0, self.close=24421.9, self.high=24463.2, self.low=24416.6, self.vol=1091.188, self.amt=26670651.0612, ukdf['pct'].iloc[-1]=-0.000663 , ukdf['amount'].iloc[-1]=26670651.0612, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5859, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': []}
type(curSign)=<class 'int'>, curSign=0, self.sign=0
--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=0, self.total=1000000.0, self.flagDict['side']='', self.tradeCount=0, self.count=20987
self.closeSec=1677025499, self.tradeDate='20230222', self.openTime='082000', self.closeTime='082459', self.symbol='BTCUSDT', self.open=24421.8, self.close=24416.6, self.high=24433.9, self.low=24407.5, self.vol=802.134, self.amt=19585225.5399 
127.0.0.1 - - [22/Feb/2023 08:25:01] "POST / HTTP/1.1" 200 -
2023-02-22 08:25:01,576:INFO:sr_min:main.py:172:handleKline:449472: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5856  20230222   080000    080459  ...         0.0        0.0       0
5857  20230222   080500    080959  ...         0.0        0.0       0
5858  20230222   081000    081459  ...         0.0        0.0       0
5859  20230222   081500    081959  ...         0.0        0.0       0
5860  20230222   082000    082459  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-02-22 08:25:01,577:INFO:sr_min:main.py:175:handleKline:449472: self.closeSec=1677025499, self.tradeDate='20230222', self.openTime='082000', self.closeTime='082459',self.symbol='BTCUSDT',self.open=24421.8, self.close=24416.6, self.high=24433.9, self.low=24407.5, self.vol=802.134, self.amt=19585225.5399, ukdf['pct'].iloc[-1]=-0.000217 , ukdf['amount'].iloc[-1]=19585225.5399, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5860, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': []}
type(curSign)=<class 'int'>, curSign=0, self.sign=0


## /root/FIL/strategy/s_rsrs/log.txt ----- -----

719  20230221   200000    235959  1676995199  ...    719  0.092406 -1.360631    -1.0
720  20230222   000000    035959  1677009599  ...    720  0.043129 -1.451441    -1.0

[5 rows x 15 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '36.465', 'enterprice': '24934.8', 'countrevence': '0', 'unrealprofit': '12044.5392850926', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '24604.49589236', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'numpy.int64'>, curSign=-1, self.sign=-1
127.0.0.1 - - [22/Feb/2023 08:00:02] "POST / HTTP/1.1" 200 -
--handleKline--:  version='2.0.0', self.name='s_rsrs', self.symbol='BTCUSDT', interval='4h', intervalSec=14400, wid=25, thd=0.6, self.sign=-1, self.total=908338.234518, self.flagDict['side']='sell', self.tradeCount=21, self.count=532
self.closeSec=1677023999, self.tradeDate='20230222', self.openTime='040000', self.closeTime='075959', self.symbol='BTCUSDT', self.open=24607.7, self.close=24443.4, self.high=24640.2, self.low=24150.0, self.vol=105687.69, self.amt=2571925388.03268 
2023-02-22 08:00:02,094:INFO:s_rsrs:main.py:141:handleKline:185271: self.closeSec=1677023999, self.tradeDate='20230222', self.openTime='040000', self.closeTime='075959',self.symbol='BTCUSDT',self.open=24607.7, self.close=24443.4, self.high=24640.2, self.low=24150.0, self.vol=105687.69, self.amt=2571925388.03268 
2023-02-22 08:00:02,156:INFO:s_rsrs:main.py:142:handleKline:185271: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime  ...         vol           amt       pct
717  20230221   120000    155959  ...   46758.131  1.167208e+09  0.003145
718  20230221   160000    195959  ...  217838.830  5.409969e+09 -0.017273
719  20230221   200000    235959  ...  141571.537  3.482794e+09 -0.000761
720  20230222   000000    035959  ...  140748.886  3.451157e+09  0.002187
721  20230222   040000    075959  ...  105687.690  2.571925e+09 -0.006677

[5 rows x 11 columns]
2023-02-22 08:00:04,748:INFO:s_rsrs:main.py:151:handleKline:185271: df_s.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec  ...  index      beta    zscore  signal
717  20230221   120000    155959  1676966399  ...    717  0.332460 -0.788208    -1.0
718  20230221   160000    195959  1676980799  ...    718  0.230000 -1.036031    -1.0
719  20230221   200000    235959  1676995199  ...    719  0.092406 -1.360631    -1.0
720  20230222   000000    035959  1677009599  ...    720  0.043129 -1.451441    -1.0
721  20230222   040000    075959  1677023999  ...    721  0.037081 -1.436210    -1.0

[5 rows x 15 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '36.465', 'enterprice': '24934.8', 'countrevence': '0', 'unrealprofit': '17918.901', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '24443.4', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'numpy.int64'>, curSign=-1, self.sign=-1


