# 20230531 08:26:02

## /root/FIL/strategy/amihud/log.txt ----- -----

--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=373746.4768026, self.flagDict['side']='sell', self.tradeCount=2, self.count=4864
self.closeSec=1685492399, self.tradeDate='20230531', self.openTime='081500', self.closeTime='081959', self.symbol='BTCUSDT', self.open=27679.3, self.close=27675.4, self.high=27689.4, self.low=27672.8, self.vol=486.934, self.amt=13479403.3522 
127.0.0.1 - - [31/May/2023 08:20:01] "POST / HTTP/1.1" 200 -
2023-05-31 08:20:06,871:INFO:amihud:main.py:172:handleKline:2219019: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5855  20230531   075500    075959  ...         0.0        0.0       0
5856  20230531   080000    080459  ...         0.0        0.0       0
5857  20230531   080500    080959  ...         0.0        0.0       0
5858  20230531   081000    081459  ...         0.0        0.0       0
5859  20230531   081500    081959  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-05-31 08:20:06,891:INFO:amihud:main.py:175:handleKline:2219019: self.closeSec=1685492399, self.tradeDate='20230531', self.openTime='081500', self.closeTime='081959',self.symbol='BTCUSDT',self.open=27679.3, self.close=27675.4, self.high=27689.4, self.low=27672.8, self.vol=486.934, self.amt=13479403.3522, ukdf['pct'].iloc[-1]=-0.000141 , ukdf['amount'].iloc[-1]=13479403.3522, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5859, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '13.926', 'enterprice': '26864.9', 'countrevence': '0', 'unrealprofit': '-11288.67942027144', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '27675.51894444', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1
--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=373746.4768026, self.flagDict['side']='sell', self.tradeCount=2, self.count=4865
self.closeSec=1685492699, self.tradeDate='20230531', self.openTime='082000', self.closeTime='082459', self.symbol='BTCUSDT', self.open=27675.4, self.close=27690.1, self.high=27690.1, self.low=27675.0, self.vol=199.048, self.amt=5510196.4405 
127.0.0.1 - - [31/May/2023 08:25:00] "POST / HTTP/1.1" 200 -
2023-05-31 08:25:00,775:INFO:amihud:main.py:172:handleKline:2219019: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5856  20230531   080000    080459  ...         0.0        0.0       0
5857  20230531   080500    080959  ...         0.0        0.0       0
5858  20230531   081000    081459  ...         0.0        0.0       0
5859  20230531   081500    081959  ...         0.0        0.0       0
5860  20230531   082000    082459  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-05-31 08:25:00,776:INFO:amihud:main.py:175:handleKline:2219019: self.closeSec=1685492699, self.tradeDate='20230531', self.openTime='082000', self.closeTime='082459',self.symbol='BTCUSDT',self.open=27675.4, self.close=27690.1, self.high=27690.1, self.low=27675.0, self.vol=199.048, self.amt=5510196.4405, ukdf['pct'].iloc[-1]=0.000531 , ukdf['amount'].iloc[-1]=5510196.4405, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5860, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '13.926', 'enterprice': '26864.9', 'countrevence': '0', 'unrealprofit': '-11496.44125955358', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '27690.43793333', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1


## /root/FIL/strategy/factorcheck/log.txt ----- -----


self.closeSec=1685492399, self.tradeDate='20230531', self.openTime='081500', self.closeTime='081959', self.symbol='BTCUSDT', self.open=27679.3, self.close=27675.4, self.high=27689.4, self.low=27672.8 
127.0.0.1 - - [31/May/2023 08:20:01] "POST / HTTP/1.1" 200 -
2023-05-31 08:20:04,542:INFO:factorcheck2:main.py:126:handleKline:2218005: self.closeSec=1685492399, self.tradeDate='20230531', self.openTime='081500', self.closeTime='081959',self.symbol='BTCUSDT',self.open=27679.3, self.close=27675.4, self.high=27689.4, self.low=27672.8   
2023-05-31 08:20:05,851:INFO:factorcheck2:main.py:127:handleKline:2218005: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime    closeSec  ...      low       pct  index  idx
1535  20230531   075500    075959  1685491199  ...  27671.6  0.000307   1535    5
1536  20230531   080000    080459  1685491499  ...  27673.1 -0.000249   1536    0
1537  20230531   080500    080959  1685491799  ...  27661.6 -0.000029   1537    1
1538  20230531   081000    081459  1685492099  ...  27648.0  0.000249   1538    2
1539  20230531   081500    081959  1685492399  ...  27672.8 -0.000141   1539    3

[5 rows x 11 columns]
2023-05-31 08:20:05,852:INFO:factorcheck2:main.py:128:handleKline:2218005: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}
127.0.0.1 - - [31/May/2023 08:25:00] "POST / HTTP/1.1" 200 -

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=211, self.factor=0.5298644326719395, self.count=4867 

self.closeSec=1685492699, self.tradeDate='20230531', self.openTime='082000', self.closeTime='082459', self.symbol='BTCUSDT', self.open=27675.4, self.close=27690.1, self.high=27690.1, self.low=27675.0 
2023-05-31 08:25:00,773:INFO:factorcheck2:main.py:126:handleKline:2218005: self.closeSec=1685492699, self.tradeDate='20230531', self.openTime='082000', self.closeTime='082459',self.symbol='BTCUSDT',self.open=27675.4, self.close=27690.1, self.high=27690.1, self.low=27675.0   
2023-05-31 08:25:00,815:INFO:factorcheck2:main.py:127:handleKline:2218005: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime    closeSec  ...      low       pct  index  idx
1536  20230531   080000    080459  1685491499  ...  27673.1 -0.000249   1536    0
1537  20230531   080500    080959  1685491799  ...  27661.6 -0.000029   1537    1
1538  20230531   081000    081459  1685492099  ...  27648.0  0.000249   1538    2
1539  20230531   081500    081959  1685492399  ...  27672.8 -0.000141   1539    3
1540  20230531   082000    082459  1685492699  ...  27675.0  0.000531   1540    4

[5 rows x 11 columns]
2023-05-31 08:25:00,815:INFO:factorcheck2:main.py:128:handleKline:2218005: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}


## /root/FIL/strategy/logic/log.txt ----- -----

2023-05-31 08:00:33,015:DEBUG:logic:main.py:463:getModel:2218526: df_s.iloc[-5:,:] :
          date closeTime     open  ...    alpha58   alpha67   alpha72
5770  20230531    052959  27745.7  ...  52.083333  0.529976  0.524667
5771  20230531    055959  27806.9  ...  51.666667  0.507465  0.532749
5772  20230531    062959  27710.0  ...  51.666667  0.507102  0.540501
5773  20230531    065959  27708.4  ...  52.083333  0.510521  0.545732
5774  20230531    072959  27723.7  ...  51.666667  0.503234  0.554716

[5 rows x 33 columns]
0.5249537892791127
acc is : 0.5249537892791127
2023-05-31 08:00:33,179:INFO:logic:main.py:468:getModel:2218526: df_pred.iloc[-5:,:] :
     pred    prob_0    prob_1  actual  ...       nav  sign  cost_        bm
536     0  0.510302  0.489698       0  ...  1.004389  -1.0    0.0  1.029377
537     1  0.473684  0.526316       0  ...  1.004447  -1.0    0.0  1.029317
538     1  0.485132  0.514868       1  ...  1.003893  -1.0    0.0  1.029886
539     1  0.492732  0.507268       0  ...  1.005026  -1.0    0.0  1.028723
540     1  0.486869  0.513131       0  ...  1.005476  -1.0    0.0  1.028262

[5 rows x 10 columns]
2023-05-31 08:00:33,215:INFO:logic:main.py:478:getModel:2218526: df_panel.iloc[-5:,:] :
    pred    prob_0    prob_1  actual  ...       nav  sign  cost_        bm
45     0  0.509963  0.490037       0  ...  1.004389  -1.0    0.0  1.031269
46     1  0.473806  0.526194       0  ...  1.004447  -1.0    0.0  1.030696
47     1  0.485198  0.514802       1  ...  1.003893  -1.0    0.0  1.033606
48     1  0.492732  0.507268       0  ...  1.005026  -1.0    0.0  1.028723
49     1  0.486869  0.513131       0  ...  1.005476  -1.0    0.0  1.028262

[5 rows x 10 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '25.849', 'enterprice': '27935.3', 'countrevence': '0', 'unrealprofit': '6685.08580403543', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '27676.67932593', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}


## /root/FIL/strategy/modifiedmom/log.txt ----- -----

623  20230531   075000    075959  1685491199    27695  27680.1 -0.000534
2023-05-31 08:00:02,304:INFO:modifiedmom:main.py:146:handleKline:2218259: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': True, 'isOpen': False, 'isClose': True, 'isTrig': False}
127.0.0.1 - - [31/May/2023 08:10:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=2432 

self.closeSec=1685491799, self.tradeDate='20230531', self.openTime='080000', self.closeTime='080959', self.symbol='BTCUSDT', self.open='27680', self.close='27672.4'
2023-05-31 08:10:01,149:INFO:modifiedmom:main.py:144:handleKline:2218259: self.closeSec=1685491799, self.tradeDate='20230531', self.openTime='080000', self.closeTime='080959',self.symbol='BTCUSDT',self.open='27680', self.close='27672.4'
2023-05-31 08:10:01,170:INFO:modifiedmom:main.py:145:handleKline:2218259: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec     open    close       pct
620  20230531   072000    072959  1685489399  27674.7  27692.5  0.000643
621  20230531   073000    073959  1685489999  27692.5  27712.6  0.000726
622  20230531   074000    074959  1685490599  27712.6  27694.9 -0.000639
623  20230531   075000    075959  1685491199    27695  27680.1 -0.000534
624  20230531   080000    080959  1685491799    27680  27672.4 -0.000278
2023-05-31 08:10:01,174:INFO:modifiedmom:main.py:146:handleKline:2218259: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': True, 'isOpen': False, 'isClose': True, 'isTrig': False}

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=2433 

self.closeSec=1685492399, self.tradeDate='20230531', self.openTime='081000', self.closeTime='081959', self.symbol='BTCUSDT', self.open='27672.4', self.close='27675.3'
127.0.0.1 - - [31/May/2023 08:20:04] "POST / HTTP/1.1" 200 -
2023-05-31 08:20:07,001:INFO:modifiedmom:main.py:144:handleKline:2218259: self.closeSec=1685492399, self.tradeDate='20230531', self.openTime='081000', self.closeTime='081959',self.symbol='BTCUSDT',self.open='27672.4', self.close='27675.3'
2023-05-31 08:20:07,640:INFO:modifiedmom:main.py:145:handleKline:2218259: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec     open    close       pct
621  20230531   073000    073959  1685489999  27692.5  27712.6  0.000726
622  20230531   074000    074959  1685490599  27712.6  27694.9 -0.000639
623  20230531   075000    075959  1685491199    27695  27680.1 -0.000534
624  20230531   080000    080959  1685491799    27680  27672.4 -0.000278
625  20230531   081000    081959  1685492399  27672.4  27675.3  0.000105
2023-05-31 08:20:07,641:INFO:modifiedmom:main.py:146:handleKline:2218259: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': True, 'isOpen': False, 'isClose': True, 'isTrig': False}


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

17471  20230531   075000    075959  1685491199    27695  27680.1
2023-05-31 08:00:02,328:INFO:pyemd2:main.py:127:handleKline:2217508: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=2435 

self.closeSec=1685491799, self.tradeDate='20230531', self.openTime='080000', self.closeTime='080959', self.symbol='BTCUSDT', self.open='27680', self.close='27672.4'
2023-05-31 08:10:01,180:INFO:pyemd2:main.py:125:handleKline:2217508: self.closeSec=1685491799, self.tradeDate='20230531', self.openTime='080000', self.closeTime='080959',self.symbol='BTCUSDT',self.open='27680', self.close='27672.4'
127.0.0.1 - - [31/May/2023 08:10:01] "POST / HTTP/1.1" 200 -
2023-05-31 08:10:01,195:INFO:pyemd2:main.py:126:handleKline:2217508: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
17468  20230531   072000    072959  1685489399  27674.7  27692.5
17469  20230531   073000    073959  1685489999  27692.5  27712.6
17470  20230531   074000    074959  1685490599  27712.6  27694.9
17471  20230531   075000    075959  1685491199    27695  27680.1
17472  20230531   080000    080959  1685491799    27680  27672.4
2023-05-31 08:10:01,195:INFO:pyemd2:main.py:127:handleKline:2217508: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=2436 

self.closeSec=1685492399, self.tradeDate='20230531', self.openTime='081000', self.closeTime='081959', self.symbol='BTCUSDT', self.open='27672.4', self.close='27675.3'
127.0.0.1 - - [31/May/2023 08:20:04] "POST / HTTP/1.1" 200 -
2023-05-31 08:20:08,435:INFO:pyemd2:main.py:125:handleKline:2217508: self.closeSec=1685492399, self.tradeDate='20230531', self.openTime='081000', self.closeTime='081959',self.symbol='BTCUSDT',self.open='27672.4', self.close='27675.3'
2023-05-31 08:20:08,521:INFO:pyemd2:main.py:126:handleKline:2217508: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
17469  20230531   073000    073959  1685489999  27692.5  27712.6
17470  20230531   074000    074959  1685490599  27712.6  27694.9
17471  20230531   075000    075959  1685491199    27695  27680.1
17472  20230531   080000    080959  1685491799    27680  27672.4
17473  20230531   081000    081959  1685492399  27672.4  27675.3
2023-05-31 08:20:08,521:INFO:pyemd2:main.py:127:handleKline:2217508: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}


## /root/FIL/strategy/similarity/log.txt ----- -----

12143  20230531   075000    075959  1685491199    27695  27680.1
2023-05-31 08:00:02,321:INFO:testStrategy:main.py:103:handleKline:2217133: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': True, 'isOpenSell': False, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True, 'isCorr': False}

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=2435 

self.closeSec=1685491799, self.tradeDate='20230531', self.openTime='080000', self.closeTime='080959', self.symbol='BTCUSDT', self.open='27680', self.close='27672.4'
2023-05-31 08:10:01,165:INFO:testStrategy:main.py:101:handleKline:2217133: self.closeSec=1685491799, self.tradeDate='20230531', self.openTime='080000', self.closeTime='080959',self.symbol='BTCUSDT',self.open='27680', self.close='27672.4'
127.0.0.1 - - [31/May/2023 08:10:01] "POST / HTTP/1.1" 200 -
2023-05-31 08:10:01,173:INFO:testStrategy:main.py:102:handleKline:2217133: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
12140  20230531   072000    072959  1685489399  27674.7  27692.5
12141  20230531   073000    073959  1685489999  27692.5  27712.6
12142  20230531   074000    074959  1685490599  27712.6  27694.9
12143  20230531   075000    075959  1685491199    27695  27680.1
12144  20230531   080000    080959  1685491799    27680  27672.4
2023-05-31 08:10:01,191:INFO:testStrategy:main.py:103:handleKline:2217133: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': True, 'isOpenSell': False, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True, 'isCorr': False}

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=2436 

self.closeSec=1685492399, self.tradeDate='20230531', self.openTime='081000', self.closeTime='081959', self.symbol='BTCUSDT', self.open='27672.4', self.close='27675.3'
127.0.0.1 - - [31/May/2023 08:20:04] "POST / HTTP/1.1" 200 -
2023-05-31 08:20:08,201:INFO:testStrategy:main.py:101:handleKline:2217133: self.closeSec=1685492399, self.tradeDate='20230531', self.openTime='081000', self.closeTime='081959',self.symbol='BTCUSDT',self.open='27672.4', self.close='27675.3'
2023-05-31 08:20:08,383:INFO:testStrategy:main.py:102:handleKline:2217133: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
12141  20230531   073000    073959  1685489999  27692.5  27712.6
12142  20230531   074000    074959  1685490599  27712.6  27694.9
12143  20230531   075000    075959  1685491199    27695  27680.1
12144  20230531   080000    080959  1685491799    27680  27672.4
12145  20230531   081000    081959  1685492399  27672.4  27675.3
2023-05-31 08:20:08,385:INFO:testStrategy:main.py:103:handleKline:2217133: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': True, 'isOpenSell': False, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True, 'isCorr': False}


## /root/FIL/strategy/sr_min/log.txt ----- -----

--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=1, self.total=996015.990996, self.flagDict['side']='buy', self.tradeCount=1, self.count=4864
self.closeSec=1685492399, self.tradeDate='20230531', self.openTime='081500', self.closeTime='081959', self.symbol='BTCUSDT', self.open=27679.3, self.close=27675.4, self.high=27689.4, self.low=27672.8, self.vol=486.934, self.amt=13479403.3522 
127.0.0.1 - - [31/May/2023 08:20:01] "POST / HTTP/1.1" 200 -
2023-05-31 08:20:06,861:INFO:sr_min:main.py:172:handleKline:2219263: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5855  20230531   075500    075959  ...         0.0        0.0       0
5856  20230531   080000    080459  ...         0.0        0.0       0
5857  20230531   080500    080959  ...         0.0        0.0       0
5858  20230531   081000    081459  ...         0.0        0.0       0
5859  20230531   081500    081959  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-05-31 08:20:06,871:INFO:sr_min:main.py:175:handleKline:2219263: self.closeSec=1685492399, self.tradeDate='20230531', self.openTime='081500', self.closeTime='081959',self.symbol='BTCUSDT',self.open=27679.3, self.close=27675.4, self.high=27689.4, self.low=27672.8, self.vol=486.934, self.amt=13479403.3522, ukdf['pct'].iloc[-1]=-0.000141 , ukdf['amount'].iloc[-1]=13479403.3522, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5859, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '37.141', 'enterprice': '26844', 'countrevence': '0', 'unrealprofit': '30883.44511544604', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '27675.51894444', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=1
127.0.0.1 - - [31/May/2023 08:25:00] "POST / HTTP/1.1" 200 -
--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=1, self.total=996015.990996, self.flagDict['side']='buy', self.tradeCount=1, self.count=4865
self.closeSec=1685492699, self.tradeDate='20230531', self.openTime='082000', self.closeTime='082459', self.symbol='BTCUSDT', self.open=27675.4, self.close=27690.1, self.high=27690.1, self.low=27675.0, self.vol=199.048, self.amt=5510196.4405 
2023-05-31 08:25:00,816:INFO:sr_min:main.py:172:handleKline:2219263: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5856  20230531   080000    080459  ...         0.0        0.0       0
5857  20230531   080500    080959  ...         0.0        0.0       0
5858  20230531   081000    081459  ...         0.0        0.0       0
5859  20230531   081500    081959  ...         0.0        0.0       0
5860  20230531   082000    082459  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-05-31 08:25:00,816:INFO:sr_min:main.py:175:handleKline:2219263: self.closeSec=1685492699, self.tradeDate='20230531', self.openTime='082000', self.closeTime='082459',self.symbol='BTCUSDT',self.open=27675.4, self.close=27690.1, self.high=27690.1, self.low=27675.0, self.vol=199.048, self.amt=5510196.4405, ukdf['pct'].iloc[-1]=0.000531 , ukdf['amount'].iloc[-1]=5510196.4405, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5860, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '37.141', 'enterprice': '26844', 'countrevence': '0', 'unrealprofit': '31437.38621086349', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '27690.43348889', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=1


## /root/FIL/strategy/s_rsrs/log.txt ----- -----

719  20230530   200000    235959  1685462399  ...    719  1.086280  2.058788     1.0
720  20230531   000000    035959  1685476799  ...    720  1.226887  2.422773     1.0

[5 rows x 15 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '55.249', 'enterprice': '26128.2', 'countrevence': '0', 'unrealprofit': '94387.3916', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '27836.6', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'numpy.int64'>, curSign=1, self.sign=1
127.0.0.1 - - [31/May/2023 08:00:01] "POST / HTTP/1.1" 200 -
--handleKline--:  version='2.0.0', self.name='s_rsrs', self.symbol='BTCUSDT', interval='4h', intervalSec=14400, wid=25, thd=0.6, self.sign=1, self.total=1442113.3648782002, self.flagDict['side']='buy', self.tradeCount=3, self.count=101
self.closeSec=1685491199, self.tradeDate='20230531', self.openTime='040000', self.closeTime='075959', self.symbol='BTCUSDT', self.open=27836.4, self.close=27680.1, self.high=27846.0, self.low=27636.0, self.vol=29233.913, self.amt=810667381.9916 
2023-05-31 08:00:01,817:INFO:s_rsrs:main.py:141:handleKline:2218689: self.closeSec=1685491199, self.tradeDate='20230531', self.openTime='040000', self.closeTime='075959',self.symbol='BTCUSDT',self.open=27836.4, self.close=27680.1, self.high=27846.0, self.low=27636.0, self.vol=29233.913, self.amt=810667381.9916 
2023-05-31 08:00:01,845:INFO:s_rsrs:main.py:142:handleKline:2218689: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime  ...         vol           amt       pct
717  20230530   120000    155959  ...   36390.572  1.010080e+09 -0.003376
718  20230530   160000    195959  ...   63354.986  1.767803e+09  0.010274
719  20230530   200000    235959  ...  102527.366  2.848859e+09 -0.012172
720  20230531   000000    035959  ...   56921.116  1.576800e+09  0.006127
721  20230531   040000    075959  ...   29233.913  8.106674e+08 -0.005547

[5 rows x 11 columns]
2023-05-31 08:00:03,898:INFO:s_rsrs:main.py:151:handleKline:2218689: df_s.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec  ...  index      beta    zscore  signal
717  20230530   120000    155959  1685433599  ...    717  1.104430  2.288963     1.0
718  20230530   160000    195959  1685447999  ...    718  1.101142  2.187779     1.0
719  20230530   200000    235959  1685462399  ...    719  1.086280  2.058788     1.0
720  20230531   000000    035959  1685476799  ...    720  1.226887  2.422773     1.0
721  20230531   040000    075959  1685491199  ...    721  1.202865  2.249407     1.0

[5 rows x 15 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '55.249', 'enterprice': '26128.2', 'countrevence': '0', 'unrealprofit': '85847.39863964853', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '27682.02719397', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'numpy.int64'>, curSign=1, self.sign=1


