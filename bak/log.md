# 20230619 08:26:01

## /root/FIL/strategy/amihud/log.txt ----- -----

--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=373746.4768026, self.flagDict['side']='sell', self.tradeCount=2, self.count=10336
self.closeSec=1687133999, self.tradeDate='20230619', self.openTime='081500', self.closeTime='081959', self.symbol='BTCUSDT', self.open=26371.5, self.close=26368.0, self.high=26379.8, self.low=26349.9, self.vol=744.286, self.amt=19624491.4068 
127.0.0.1 - - [19/Jun/2023 08:20:01] "POST / HTTP/1.1" 200 -
2023-06-19 08:20:08,095:INFO:amihud:main.py:172:handleKline:2219019: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5855  20230619   075500    075959  ...         0.0        0.0       0
5856  20230619   080000    080459  ...         0.0        0.0       0
5857  20230619   080500    080959  ...         0.0        0.0       0
5858  20230619   081000    081459  ...         0.0        0.0       0
5859  20230619   081500    081959  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-06-19 08:20:08,126:INFO:amihud:main.py:175:handleKline:2219019: self.closeSec=1687133999, self.tradeDate='20230619', self.openTime='081500', self.closeTime='081959',self.symbol='BTCUSDT',self.open=26371.5, self.close=26368.0, self.high=26379.8, self.low=26349.9, self.vol=744.286, self.amt=19624491.4068, ukdf['pct'].iloc[-1]=-0.000129 , ukdf['amount'].iloc[-1]=19624491.4068, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5859, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '13.926', 'enterprice': '26864.9', 'countrevence': '0', 'unrealprofit': '6930.07332479682', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '26367.26440293', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1
127.0.0.1 - - [19/Jun/2023 08:25:00] "POST / HTTP/1.1" 200 -
--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=373746.4768026, self.flagDict['side']='sell', self.tradeCount=2, self.count=10337
self.closeSec=1687134299, self.tradeDate='20230619', self.openTime='082000', self.closeTime='082459', self.symbol='BTCUSDT', self.open=26368.0, self.close=26375.4, self.high=26378.0, self.low=26347.5, self.vol=813.874, self.amt=21452754.8459 
2023-06-19 08:25:00,795:INFO:amihud:main.py:172:handleKline:2219019: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5856  20230619   080000    080459  ...         0.0        0.0       0
5857  20230619   080500    080959  ...         0.0        0.0       0
5858  20230619   081000    081459  ...         0.0        0.0       0
5859  20230619   081500    081959  ...         0.0        0.0       0
5860  20230619   082000    082459  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-06-19 08:25:00,795:INFO:amihud:main.py:175:handleKline:2219019: self.closeSec=1687134299, self.tradeDate='20230619', self.openTime='082000', self.closeTime='082459',self.symbol='BTCUSDT',self.open=26368.0, self.close=26375.4, self.high=26378.0, self.low=26347.5, self.vol=813.874, self.amt=21452754.8459, ukdf['pct'].iloc[-1]=0.000281 , ukdf['amount'].iloc[-1]=21452754.8459, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5860, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '13.926', 'enterprice': '26864.9', 'countrevence': '0', 'unrealprofit': '6818.1696', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '26375.3', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1


## /root/FIL/strategy/factorcheck/log.txt ----- -----


self.closeSec=1687133999, self.tradeDate='20230619', self.openTime='081500', self.closeTime='081959', self.symbol='BTCUSDT', self.open=26371.5, self.close=26368.0, self.high=26379.8, self.low=26349.9 
127.0.0.1 - - [19/Jun/2023 08:20:01] "POST / HTTP/1.1" 200 -
2023-06-19 08:20:05,155:INFO:factorcheck2:main.py:126:handleKline:2218005: self.closeSec=1687133999, self.tradeDate='20230619', self.openTime='081500', self.closeTime='081959',self.symbol='BTCUSDT',self.open=26371.5, self.close=26368.0, self.high=26379.8, self.low=26349.9   
2023-06-19 08:20:06,915:INFO:factorcheck2:main.py:127:handleKline:2218005: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime    closeSec  ...      low       pct  index  idx
1535  20230619   075500    075959  1687132799  ...  26314.5  0.000224   1535    5
1536  20230619   080000    080459  1687133099  ...  26308.8  0.000623   1536    0
1537  20230619   080500    080959  1687133399  ...  26346.1  0.001051   1537    1
1538  20230619   081000    081459  1687133699  ...  26351.6 -0.000091   1538    2
1539  20230619   081500    081959  1687133999  ...  26349.9 -0.000129   1539    3

[5 rows x 11 columns]
2023-06-19 08:20:06,925:INFO:factorcheck2:main.py:128:handleKline:2218005: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=101, self.factor=0.44709791308877606, self.count=10339 

self.closeSec=1687134299, self.tradeDate='20230619', self.openTime='082000', self.closeTime='082459', self.symbol='BTCUSDT', self.open=26368.0, self.close=26375.4, self.high=26378.0, self.low=26347.5 
127.0.0.1 - - [19/Jun/2023 08:25:00] "POST / HTTP/1.1" 200 -
2023-06-19 08:25:00,743:INFO:factorcheck2:main.py:126:handleKline:2218005: self.closeSec=1687134299, self.tradeDate='20230619', self.openTime='082000', self.closeTime='082459',self.symbol='BTCUSDT',self.open=26368.0, self.close=26375.4, self.high=26378.0, self.low=26347.5   
2023-06-19 08:25:00,774:INFO:factorcheck2:main.py:127:handleKline:2218005: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime    closeSec  ...      low       pct  index  idx
1536  20230619   080000    080459  1687133099  ...  26308.8  0.000623   1536    0
1537  20230619   080500    080959  1687133399  ...  26346.1  0.001051   1537    1
1538  20230619   081000    081459  1687133699  ...  26351.6 -0.000091   1538    2
1539  20230619   081500    081959  1687133999  ...  26349.9 -0.000129   1539    3
1540  20230619   082000    082459  1687134299  ...  26347.5  0.000281   1540    4

[5 rows x 11 columns]
2023-06-19 08:25:00,775:INFO:factorcheck2:main.py:128:handleKline:2218005: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}


## /root/FIL/strategy/logic/log.txt ----- -----

2023-06-19 08:00:17,817:DEBUG:logic:main.py:463:getModel:2218526: df_s.iloc[-5:,:] :
          date closeTime     open  ...    alpha58   alpha67   alpha72
5770  20230619    052959  26461.8  ...  52.916667  0.511814  0.429049
5771  20230619    055959  26430.2  ...  52.916667  0.504511  0.456129
5772  20230619    062959  26403.3  ...  53.333333  0.505870  0.480476
5773  20230619    065959  26408.2  ...  52.916667  0.500921  0.506473
5774  20230619    072959  26390.4  ...  52.500000  0.489707  0.522920

[5 rows x 33 columns]
0.5693160813308688
acc is : 0.5693160813308688
2023-06-19 08:00:17,888:INFO:logic:main.py:468:getModel:2218526: df_pred.iloc[-5:,:] :
     pred    prob_0    prob_1  actual  ...       nav  sign  cost_        bm
536     1  0.480931  0.519069       0  ...  1.044716   1.0    0.0  0.999864
537     1  0.478873  0.521127       1  ...  1.044918   1.0    0.0  1.000057
538     1  0.483982  0.516018       0  ...  1.044206   1.0    0.0  0.999375
539     1  0.493226  0.506774       0  ...  1.042572   1.0    0.0  0.997811
540     1  0.485347  0.514653       0  ...  1.041808   1.0    0.0  0.997080

[5 rows x 10 columns]
2023-06-19 08:00:17,900:INFO:logic:main.py:478:getModel:2218526: df_panel.iloc[-5:,:] :
    pred    prob_0    prob_1  actual  ...       nav  sign  cost_        bm
45     1  0.481108  0.518892       0  ...  1.044716   1.0    0.0  1.002632
46     1  0.479448  0.520552       1  ...  1.044918   1.0    0.0  1.003885
47     1  0.484024  0.515976       0  ...  1.044206   1.0    0.0  1.002919
48     1  0.493226  0.506774       0  ...  1.042572   1.0    0.0  0.997811
49     1  0.485347  0.514653       0  ...  1.041808   1.0    0.0  0.997080

[5 rows x 10 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '28.127', 'enterprice': '25424', 'countrevence': '0', 'unrealprofit': '25250.27589037316', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '26321.72374908', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}


## /root/FIL/strategy/modifiedmom/log.txt ----- -----

623  20230619   075000    075959  1687132799  26338.5  26329.7 -0.000319
2023-06-19 08:00:02,187:INFO:modifiedmom:main.py:146:handleKline:2218259: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': True, 'isOpen': False, 'isClose': True, 'isTrig': False}
127.0.0.1 - - [19/Jun/2023 08:10:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=5168 

self.closeSec=1687133399, self.tradeDate='20230619', self.openTime='080000', self.closeTime='080959', self.symbol='BTCUSDT', self.open='26329.6', self.close='26373.8'
2023-06-19 08:10:01,158:INFO:modifiedmom:main.py:144:handleKline:2218259: self.closeSec=1687133399, self.tradeDate='20230619', self.openTime='080000', self.closeTime='080959',self.symbol='BTCUSDT',self.open='26329.6', self.close='26373.8'
2023-06-19 08:10:01,182:INFO:modifiedmom:main.py:145:handleKline:2218259: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec     open    close       pct
620  20230619   072000    072959  1687130999  26383.3    26349 -0.001300
621  20230619   073000    073959  1687131599    26349  26358.5  0.000361
622  20230619   074000    074959  1687132199  26358.6  26338.1 -0.000774
623  20230619   075000    075959  1687132799  26338.5  26329.7 -0.000319
624  20230619   080000    080959  1687133399  26329.6  26373.8  0.001675
2023-06-19 08:10:01,182:INFO:modifiedmom:main.py:146:handleKline:2218259: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': True, 'isOpen': False, 'isClose': True, 'isTrig': False}

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=5169 

self.closeSec=1687133999, self.tradeDate='20230619', self.openTime='081000', self.closeTime='081959', self.symbol='BTCUSDT', self.open='26374.9', self.close='26368'
127.0.0.1 - - [19/Jun/2023 08:20:05] "POST / HTTP/1.1" 200 -
2023-06-19 08:20:07,935:INFO:modifiedmom:main.py:144:handleKline:2218259: self.closeSec=1687133999, self.tradeDate='20230619', self.openTime='081000', self.closeTime='081959',self.symbol='BTCUSDT',self.open='26374.9', self.close='26368'
2023-06-19 08:20:08,784:INFO:modifiedmom:main.py:145:handleKline:2218259: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec     open    close       pct
621  20230619   073000    073959  1687131599    26349  26358.5  0.000361
622  20230619   074000    074959  1687132199  26358.6  26338.1 -0.000774
623  20230619   075000    075959  1687132799  26338.5  26329.7 -0.000319
624  20230619   080000    080959  1687133399  26329.6  26373.8  0.001675
625  20230619   081000    081959  1687133999  26374.9    26368 -0.000220
2023-06-19 08:20:08,794:INFO:modifiedmom:main.py:146:handleKline:2218259: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': True, 'isOpen': False, 'isClose': True, 'isTrig': False}


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

17471  20230619   075000    075959  1687132799  26338.5  26329.7
2023-06-19 08:00:02,245:INFO:pyemd2:main.py:127:handleKline:2217508: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}
127.0.0.1 - - [19/Jun/2023 08:10:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=5171 

self.closeSec=1687133399, self.tradeDate='20230619', self.openTime='080000', self.closeTime='080959', self.symbol='BTCUSDT', self.open='26329.6', self.close='26373.8'
2023-06-19 08:10:01,151:INFO:pyemd2:main.py:125:handleKline:2217508: self.closeSec=1687133399, self.tradeDate='20230619', self.openTime='080000', self.closeTime='080959',self.symbol='BTCUSDT',self.open='26329.6', self.close='26373.8'
2023-06-19 08:10:01,178:INFO:pyemd2:main.py:126:handleKline:2217508: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
17468  20230619   072000    072959  1687130999  26383.3    26349
17469  20230619   073000    073959  1687131599    26349  26358.5
17470  20230619   074000    074959  1687132199  26358.6  26338.1
17471  20230619   075000    075959  1687132799  26338.5  26329.7
17472  20230619   080000    080959  1687133399  26329.6  26373.8
2023-06-19 08:10:01,178:INFO:pyemd2:main.py:127:handleKline:2217508: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=5172 

self.closeSec=1687133999, self.tradeDate='20230619', self.openTime='081000', self.closeTime='081959', self.symbol='BTCUSDT', self.open='26374.9', self.close='26368'
127.0.0.1 - - [19/Jun/2023 08:20:05] "POST / HTTP/1.1" 200 -
2023-06-19 08:20:10,197:INFO:pyemd2:main.py:125:handleKline:2217508: self.closeSec=1687133999, self.tradeDate='20230619', self.openTime='081000', self.closeTime='081959',self.symbol='BTCUSDT',self.open='26374.9', self.close='26368'
2023-06-19 08:20:10,343:INFO:pyemd2:main.py:126:handleKline:2217508: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
17469  20230619   073000    073959  1687131599    26349  26358.5
17470  20230619   074000    074959  1687132199  26358.6  26338.1
17471  20230619   075000    075959  1687132799  26338.5  26329.7
17472  20230619   080000    080959  1687133399  26329.6  26373.8
17473  20230619   081000    081959  1687133999  26374.9    26368
2023-06-19 08:20:10,344:INFO:pyemd2:main.py:127:handleKline:2217508: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}


## /root/FIL/strategy/similarity/log.txt ----- -----

12143  20230619   075000    075959  1687132799  26338.5  26329.7
2023-06-19 08:00:02,250:INFO:testStrategy:main.py:103:handleKline:2217133: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': True, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True, 'isCorr': False}

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=5171 

self.closeSec=1687133399, self.tradeDate='20230619', self.openTime='080000', self.closeTime='080959', self.symbol='BTCUSDT', self.open='26329.6', self.close='26373.8'
2023-06-19 08:10:01,169:INFO:testStrategy:main.py:101:handleKline:2217133: self.closeSec=1687133399, self.tradeDate='20230619', self.openTime='080000', self.closeTime='080959',self.symbol='BTCUSDT',self.open='26329.6', self.close='26373.8'
127.0.0.1 - - [19/Jun/2023 08:10:01] "POST / HTTP/1.1" 200 -
2023-06-19 08:10:01,184:INFO:testStrategy:main.py:102:handleKline:2217133: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
12140  20230619   072000    072959  1687130999  26383.3    26349
12141  20230619   073000    073959  1687131599    26349  26358.5
12142  20230619   074000    074959  1687132199  26358.6  26338.1
12143  20230619   075000    075959  1687132799  26338.5  26329.7
12144  20230619   080000    080959  1687133399  26329.6  26373.8
2023-06-19 08:10:01,185:INFO:testStrategy:main.py:103:handleKline:2217133: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': True, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True, 'isCorr': False}

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=5172 

self.closeSec=1687133999, self.tradeDate='20230619', self.openTime='081000', self.closeTime='081959', self.symbol='BTCUSDT', self.open='26374.9', self.close='26368'
127.0.0.1 - - [19/Jun/2023 08:20:04] "POST / HTTP/1.1" 200 -
2023-06-19 08:20:09,756:INFO:testStrategy:main.py:101:handleKline:2217133: self.closeSec=1687133999, self.tradeDate='20230619', self.openTime='081000', self.closeTime='081959',self.symbol='BTCUSDT',self.open='26374.9', self.close='26368'
2023-06-19 08:20:10,094:INFO:testStrategy:main.py:102:handleKline:2217133: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
12141  20230619   073000    073959  1687131599    26349  26358.5
12142  20230619   074000    074959  1687132199  26358.6  26338.1
12143  20230619   075000    075959  1687132799  26338.5  26329.7
12144  20230619   080000    080959  1687133399  26329.6  26373.8
12145  20230619   081000    081959  1687133999  26374.9    26368
2023-06-19 08:20:10,095:INFO:testStrategy:main.py:103:handleKline:2217133: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': True, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True, 'isCorr': False}


## /root/FIL/strategy/sr_min/log.txt ----- -----

--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=1, self.total=996015.990996, self.flagDict['side']='buy', self.tradeCount=1, self.count=10336
self.closeSec=1687133999, self.tradeDate='20230619', self.openTime='081500', self.closeTime='081959', self.symbol='BTCUSDT', self.open=26371.5, self.close=26368.0, self.high=26379.8, self.low=26349.9, self.vol=744.286, self.amt=19624491.4068 
127.0.0.1 - - [19/Jun/2023 08:20:01] "POST / HTTP/1.1" 200 -
2023-06-19 08:20:08,085:INFO:sr_min:main.py:172:handleKline:2219263: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5855  20230619   075500    075959  ...         0.0        0.0       0
5856  20230619   080000    080459  ...         0.0        0.0       0
5857  20230619   080500    080959  ...         0.0        0.0       0
5858  20230619   081000    081459  ...         0.0        0.0       0
5859  20230619   081500    081959  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-06-19 08:20:08,124:INFO:sr_min:main.py:175:handleKline:2219263: self.closeSec=1687133999, self.tradeDate='20230619', self.openTime='081500', self.closeTime='081959',self.symbol='BTCUSDT',self.open=26371.5, self.close=26368.0, self.high=26379.8, self.low=26349.9, self.vol=744.286, self.amt=19624491.4068, ukdf['pct'].iloc[-1]=-0.000129 , ukdf['amount'].iloc[-1]=19624491.4068, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5859, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '37.141', 'enterprice': '26844', 'countrevence': '0', 'unrealprofit': '-17706.43681077687', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '26367.26440293', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=1
127.0.0.1 - - [19/Jun/2023 08:25:00] "POST / HTTP/1.1" 200 -
--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=1, self.total=996015.990996, self.flagDict['side']='buy', self.tradeCount=1, self.count=10337
self.closeSec=1687134299, self.tradeDate='20230619', self.openTime='082000', self.closeTime='082459', self.symbol='BTCUSDT', self.open=26368.0, self.close=26375.4, self.high=26378.0, self.low=26347.5, self.vol=813.874, self.amt=21452754.8459 
2023-06-19 08:25:00,796:INFO:sr_min:main.py:172:handleKline:2219263: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5856  20230619   080000    080459  ...         0.0        0.0       0
5857  20230619   080500    080959  ...         0.0        0.0       0
5858  20230619   081000    081459  ...         0.0        0.0       0
5859  20230619   081500    081959  ...         0.0        0.0       0
5860  20230619   082000    082459  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-06-19 08:25:00,796:INFO:sr_min:main.py:175:handleKline:2219263: self.closeSec=1687134299, self.tradeDate='20230619', self.openTime='082000', self.closeTime='082459',self.symbol='BTCUSDT',self.open=26368.0, self.close=26375.4, self.high=26378.0, self.low=26347.5, self.vol=813.874, self.amt=21452754.8459, ukdf['pct'].iloc[-1]=0.000281 , ukdf['amount'].iloc[-1]=21452754.8459, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5860, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '37.141', 'enterprice': '26844', 'countrevence': '0', 'unrealprofit': '-17407.9867', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '26375.3', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=1


## /root/FIL/strategy/s_rsrs/log.txt ----- -----

719  20230618   200000    235959  1687103999  ...    719  0.592151  1.080556     1.0
720  20230619   000000    035959  1687118399  ...    720  0.594437  1.072011     1.0

[5 rows x 15 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '57.175', 'enterprice': '26590', 'countrevence': '0', 'unrealprofit': '2950.23', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '26641.6', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'numpy.int64'>, curSign=1, self.sign=1
--handleKline--:  version='2.0.0', self.name='s_rsrs', self.symbol='BTCUSDT', interval='4h', intervalSec=14400, wid=25, thd=0.6, self.sign=1, self.total=1518762.96675, self.flagDict['side']='buy', self.tradeCount=5, self.count=215
self.closeSec=1687132799, self.tradeDate='20230619', self.openTime='040000', self.closeTime='075959', self.symbol='BTCUSDT', self.open=26641.6, self.close=26329.7, self.high=26709.4, self.low=26230.9, self.vol=80903.422, self.amt=2137749511.65474 127.0.0.1 - - [19/Jun/2023 08:00:01] "POST / HTTP/1.1" 200 -

2023-06-19 08:00:01,770:INFO:s_rsrs:main.py:141:handleKline:2218689: self.closeSec=1687132799, self.tradeDate='20230619', self.openTime='040000', self.closeTime='075959',self.symbol='BTCUSDT',self.open=26641.6, self.close=26329.7, self.high=26709.4, self.low=26230.9, self.vol=80903.422, self.amt=2137749511.65474 
2023-06-19 08:00:01,782:INFO:s_rsrs:main.py:142:handleKline:2218689: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime  ...        vol           amt       pct
717  20230618   120000    155959  ...  40704.717  1.081643e+09  0.001266
718  20230618   160000    195959  ...  27593.456  7.312376e+08 -0.003142
719  20230618   200000    235959  ...  33224.650  8.807581e+08  0.002227
720  20230619   000000    035959  ...  32518.414  8.648519e+08  0.003545
721  20230619   040000    075959  ...  80903.422  2.137750e+09 -0.011707

[5 rows x 11 columns]
2023-06-19 08:00:03,014:INFO:s_rsrs:main.py:151:handleKline:2218689: df_s.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec  ...  index      beta    zscore  signal
717  20230618   120000    155959  1687075199  ...    717  0.589647  1.084178     1.0
718  20230618   160000    195959  1687089599  ...    718  0.590845  1.086669     1.0
719  20230618   200000    235959  1687103999  ...    719  0.592151  1.080556     1.0
720  20230619   000000    035959  1687118399  ...    720  0.594437  1.072011     1.0
721  20230619   040000    075959  1687132799  ...    721  0.609595  1.127262     1.0

[5 rows x 15 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '57.175', 'enterprice': '26590', 'countrevence': '0', 'unrealprofit': '-14795.8418095815', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '26331.21833302', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'numpy.int64'>, curSign=1, self.sign=1


