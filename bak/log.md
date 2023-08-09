# 20230809 08:26:01

## /root/FIL/strategy/amihud/log.txt ----- -----

--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=373746.4768026, self.flagDict['side']='sell', self.tradeCount=2, self.count=25024
self.closeSec=1691540399, self.tradeDate='20230809', self.openTime='081500', self.closeTime='081959', self.symbol='BTCUSDT', self.open=29806.6, self.close=29804.0, self.high=29813.6, self.low=29800.7, self.vol=420.937, self.amt=12546924.9573 
127.0.0.1 - - [09/Aug/2023 08:20:02] "POST / HTTP/1.1" 200 -
2023-08-09 08:20:06,585:INFO:amihud:main.py:172:handleKline:2219019: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5855  20230809   075500    075959  ...         0.0        0.0       0
5856  20230809   080000    080459  ...         0.0        0.0       0
5857  20230809   080500    080959  ...         0.0        0.0       0
5858  20230809   081000    081459  ...         0.0        0.0       0
5859  20230809   081500    081959  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-08-09 08:20:06,606:INFO:amihud:main.py:175:handleKline:2219019: self.closeSec=1691540399, self.tradeDate='20230809', self.openTime='081500', self.closeTime='081959',self.symbol='BTCUSDT',self.open=29806.6, self.close=29804.0, self.high=29813.6, self.low=29800.7, self.vol=420.937, self.amt=12546924.9573, ukdf['pct'].iloc[-1]=-8.4e-05 , ukdf['amount'].iloc[-1]=12546924.9573, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5859, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '13.926', 'enterprice': '26864.9', 'countrevence': '0', 'unrealprofit': '-40979.57949421908', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '29807.56691758', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1
127.0.0.1 - - [09/Aug/2023 08:25:00] "POST / HTTP/1.1" 200 -
--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=373746.4768026, self.flagDict['side']='sell', self.tradeCount=2, self.count=25025
self.closeSec=1691540699, self.tradeDate='20230809', self.openTime='082000', self.closeTime='082459', self.symbol='BTCUSDT', self.open=29804.0, self.close=29812.4, self.high=29812.5, self.low=29799.6, self.vol=528.414, self.amt=15750757.9444 
2023-08-09 08:25:00,794:INFO:amihud:main.py:172:handleKline:2219019: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5856  20230809   080000    080459  ...         0.0        0.0       0
5857  20230809   080500    080959  ...         0.0        0.0       0
5858  20230809   081000    081459  ...         0.0        0.0       0
5859  20230809   081500    081959  ...         0.0        0.0       0
5860  20230809   082000    082459  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-08-09 08:25:00,795:INFO:amihud:main.py:175:handleKline:2219019: self.closeSec=1691540699, self.tradeDate='20230809', self.openTime='082000', self.closeTime='082459',self.symbol='BTCUSDT',self.open=29804.0, self.close=29812.4, self.high=29812.5, self.low=29799.6, self.vol=528.414, self.amt=15750757.9444, ukdf['pct'].iloc[-1]=0.000282 , ukdf['amount'].iloc[-1]=15750757.9444, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5860, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '13.926', 'enterprice': '26864.9', 'countrevence': '0', 'unrealprofit': '-41048.2776', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '29812.5', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1


## /root/FIL/strategy/factorcheck/log.txt ----- -----


self.closeSec=1691540399, self.tradeDate='20230809', self.openTime='081500', self.closeTime='081959', self.symbol='BTCUSDT', self.open=29806.6, self.close=29804.0, self.high=29813.6, self.low=29800.7 
127.0.0.1 - - [09/Aug/2023 08:20:01] "POST / HTTP/1.1" 200 -
2023-08-09 08:20:04,706:INFO:factorcheck2:main.py:126:handleKline:2218005: self.closeSec=1691540399, self.tradeDate='20230809', self.openTime='081500', self.closeTime='081959',self.symbol='BTCUSDT',self.open=29806.6, self.close=29804.0, self.high=29813.6, self.low=29800.7   
2023-08-09 08:20:06,017:INFO:factorcheck2:main.py:127:handleKline:2218005: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime    closeSec  ...      low       pct  index  idx
1535  20230809   075500    075959  1691539199  ...  29756.0  0.000097   1535    5
1536  20230809   080000    080459  1691539499  ...  29758.1  0.001344   1536    0
1537  20230809   080500    080959  1691539799  ...  29779.8 -0.000171   1537    1
1538  20230809   081000    081459  1691540099  ...  29782.9  0.000423   1538    2
1539  20230809   081500    081959  1691540399  ...  29800.7 -0.000084   1539    3

[5 rows x 11 columns]
2023-08-09 08:20:06,026:INFO:factorcheck2:main.py:128:handleKline:2218005: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}
127.0.0.1 - - [09/Aug/2023 08:25:00] "POST / HTTP/1.1" 200 -

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=219, self.factor=0.2519527551934654, self.count=25027 

self.closeSec=1691540699, self.tradeDate='20230809', self.openTime='082000', self.closeTime='082459', self.symbol='BTCUSDT', self.open=29804.0, self.close=29812.4, self.high=29812.5, self.low=29799.6 
2023-08-09 08:25:00,762:INFO:factorcheck2:main.py:126:handleKline:2218005: self.closeSec=1691540699, self.tradeDate='20230809', self.openTime='082000', self.closeTime='082459',self.symbol='BTCUSDT',self.open=29804.0, self.close=29812.4, self.high=29812.5, self.low=29799.6   
2023-08-09 08:25:00,776:INFO:factorcheck2:main.py:127:handleKline:2218005: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime    closeSec  ...      low       pct  index  idx
1536  20230809   080000    080459  1691539499  ...  29758.1  0.001344   1536    0
1537  20230809   080500    080959  1691539799  ...  29779.8 -0.000171   1537    1
1538  20230809   081000    081459  1691540099  ...  29782.9  0.000423   1538    2
1539  20230809   081500    081959  1691540399  ...  29800.7 -0.000084   1539    3
1540  20230809   082000    082459  1691540699  ...  29799.6  0.000282   1540    4

[5 rows x 11 columns]
2023-08-09 08:25:00,776:INFO:factorcheck2:main.py:128:handleKline:2218005: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}


## /root/FIL/strategy/logic/log.txt ----- -----

2023-08-09 08:00:16,859:DEBUG:logic:main.py:463:getModel:2218526: df_s.iloc[-5:,:] :
          date closeTime     open  ...    alpha58   alpha67   alpha72
5770  20230809    052959  29966.9  ...  49.583333  0.647716  0.166729
5771  20230809    055959  29925.2  ...  49.583333  0.624931  0.179588
5772  20230809    062959  29848.2  ...  49.583333  0.605151  0.196171
5773  20230809    065959  29780.0  ...  49.166667  0.598490  0.213283
5774  20230809    072959  29756.4  ...  49.583333  0.608281  0.226055

[5 rows x 33 columns]
0.5341959334565619
acc is : 0.5341959334565619
2023-08-09 08:00:16,924:INFO:logic:main.py:468:getModel:2218526: df_pred.iloc[-5:,:] :
     pred    prob_0    prob_1  actual  ...       nav  sign  cost_        bm
536     0  0.515871  0.484129       0  ...  0.973522   1.0    0.0  1.019026
537     1  0.499934  0.500066       0  ...  0.971297   1.0    0.0  1.016698
538     1  0.493534  0.506466       0  ...  0.970531   1.0    0.0  1.015896
539     1  0.495380  0.504620       1  ...  0.972237   1.0    0.0  1.017681
540     0  0.520736  0.479264       0  ...  0.970616   1.0    0.0  1.015985

[5 rows x 10 columns]
2023-08-09 08:00:16,936:INFO:logic:main.py:478:getModel:2218526: df_panel.iloc[-5:,:] :
    pred    prob_0    prob_1  actual  ...       nav  sign  cost_        bm
45     0  0.515968  0.484032       0  ...  0.973522   1.0    0.0  1.015991
46     0  0.500206  0.499794       0  ...  0.971297   1.0    0.0  1.014022
47     1  0.493670  0.506330       0  ...  0.970531   1.0    0.0  1.013957
48     1  0.495745  0.504255       1  ...  0.972237   1.0    0.0  1.017681
49     0  0.520736  0.479264       0  ...  0.970616   1.0    0.0  1.015985

[5 rows x 10 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '24.06', 'enterprice': '29131.5', 'countrevence': '0', 'unrealprofit': '15347.8429334874', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '29769.39870879', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}


## /root/FIL/strategy/modifiedmom/log.txt ----- -----

623  20230809   075000    075959  1691539199    29779    29759 -0.000675
2023-08-09 08:00:02,148:INFO:modifiedmom:main.py:146:handleKline:2218259: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': True, 'isOpen': False, 'isClose': True, 'isTrig': False}

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=12512 

self.closeSec=1691539799, self.tradeDate='20230809', self.openTime='080000', self.closeTime='080959', self.symbol='BTCUSDT', self.open='29758.9', self.close='29793.9'
2023-08-09 08:10:01,155:INFO:modifiedmom:main.py:144:handleKline:2218259: self.closeSec=1691539799, self.tradeDate='20230809', self.openTime='080000', self.closeTime='080959',self.symbol='BTCUSDT',self.open='29758.9', self.close='29793.9'
127.0.0.1 - - [09/Aug/2023 08:10:01] "POST / HTTP/1.1" 200 -
2023-08-09 08:10:01,174:INFO:modifiedmom:main.py:145:handleKline:2218259: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec     open    close       pct
620  20230809   072000    072959  1691537399  29794.6  29808.7  0.000473
621  20230809   073000    073959  1691537999  29808.7  29768.3 -0.001355
622  20230809   074000    074959  1691538599  29768.5  29779.1  0.000363
623  20230809   075000    075959  1691539199    29779    29759 -0.000675
624  20230809   080000    080959  1691539799  29758.9  29793.9  0.001173
2023-08-09 08:10:01,174:INFO:modifiedmom:main.py:146:handleKline:2218259: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': True, 'isOpen': False, 'isClose': True, 'isTrig': False}

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=12513 

self.closeSec=1691540399, self.tradeDate='20230809', self.openTime='081000', self.closeTime='081959', self.symbol='BTCUSDT', self.open='29793.8', self.close='29804'
127.0.0.1 - - [09/Aug/2023 08:20:04] "POST / HTTP/1.1" 200 -
2023-08-09 08:20:06,855:INFO:modifiedmom:main.py:144:handleKline:2218259: self.closeSec=1691540399, self.tradeDate='20230809', self.openTime='081000', self.closeTime='081959',self.symbol='BTCUSDT',self.open='29793.8', self.close='29804'
2023-08-09 08:20:07,435:INFO:modifiedmom:main.py:145:handleKline:2218259: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec     open    close       pct
621  20230809   073000    073959  1691537999  29808.7  29768.3 -0.001355
622  20230809   074000    074959  1691538599  29768.5  29779.1  0.000363
623  20230809   075000    075959  1691539199    29779    29759 -0.000675
624  20230809   080000    080959  1691539799  29758.9  29793.9  0.001173
625  20230809   081000    081959  1691540399  29793.8    29804  0.000339
2023-08-09 08:20:07,435:INFO:modifiedmom:main.py:146:handleKline:2218259: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': True, 'isOpen': False, 'isClose': True, 'isTrig': False}


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

17471  20230809   075000    075959  1691539199    29779    29759
2023-08-09 08:00:02,156:INFO:pyemd2:main.py:127:handleKline:2217508: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=12515 

self.closeSec=1691539799, self.tradeDate='20230809', self.openTime='080000', self.closeTime='080959', self.symbol='BTCUSDT', self.open='29758.9', self.close='29793.9'
2023-08-09 08:10:01,170:INFO:pyemd2:main.py:125:handleKline:2217508: self.closeSec=1691539799, self.tradeDate='20230809', self.openTime='080000', self.closeTime='080959',self.symbol='BTCUSDT',self.open='29758.9', self.close='29793.9'
127.0.0.1 - - [09/Aug/2023 08:10:01] "POST / HTTP/1.1" 200 -
2023-08-09 08:10:01,178:INFO:pyemd2:main.py:126:handleKline:2217508: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
17468  20230809   072000    072959  1691537399  29794.6  29808.7
17469  20230809   073000    073959  1691537999  29808.7  29768.3
17470  20230809   074000    074959  1691538599  29768.5  29779.1
17471  20230809   075000    075959  1691539199    29779    29759
17472  20230809   080000    080959  1691539799  29758.9  29793.9
2023-08-09 08:10:01,179:INFO:pyemd2:main.py:127:handleKline:2217508: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=12516 

self.closeSec=1691540399, self.tradeDate='20230809', self.openTime='081000', self.closeTime='081959', self.symbol='BTCUSDT', self.open='29793.8', self.close='29804'
127.0.0.1 - - [09/Aug/2023 08:20:04] "POST / HTTP/1.1" 200 -
2023-08-09 08:20:08,560:INFO:pyemd2:main.py:125:handleKline:2217508: self.closeSec=1691540399, self.tradeDate='20230809', self.openTime='081000', self.closeTime='081959',self.symbol='BTCUSDT',self.open='29793.8', self.close='29804'
2023-08-09 08:20:08,655:INFO:pyemd2:main.py:126:handleKline:2217508: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
17469  20230809   073000    073959  1691537999  29808.7  29768.3
17470  20230809   074000    074959  1691538599  29768.5  29779.1
17471  20230809   075000    075959  1691539199    29779    29759
17472  20230809   080000    080959  1691539799  29758.9  29793.9
17473  20230809   081000    081959  1691540399  29793.8    29804
2023-08-09 08:20:08,655:INFO:pyemd2:main.py:127:handleKline:2217508: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}


## /root/FIL/strategy/similarity/log.txt ----- -----

12143  20230809   075000    075959  1691539199    29779    29759
2023-08-09 08:00:02,154:INFO:testStrategy:main.py:103:handleKline:2217133: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': True, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True, 'isCorr': False}
127.0.0.1 - - [09/Aug/2023 08:10:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=12515 

self.closeSec=1691539799, self.tradeDate='20230809', self.openTime='080000', self.closeTime='080959', self.symbol='BTCUSDT', self.open='29758.9', self.close='29793.9'
2023-08-09 08:10:01,155:INFO:testStrategy:main.py:101:handleKline:2217133: self.closeSec=1691539799, self.tradeDate='20230809', self.openTime='080000', self.closeTime='080959',self.symbol='BTCUSDT',self.open='29758.9', self.close='29793.9'
2023-08-09 08:10:01,161:INFO:testStrategy:main.py:102:handleKline:2217133: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
12140  20230809   072000    072959  1691537399  29794.6  29808.7
12141  20230809   073000    073959  1691537999  29808.7  29768.3
12142  20230809   074000    074959  1691538599  29768.5  29779.1
12143  20230809   075000    075959  1691539199    29779    29759
12144  20230809   080000    080959  1691539799  29758.9  29793.9
2023-08-09 08:10:01,161:INFO:testStrategy:main.py:103:handleKline:2217133: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': True, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True, 'isCorr': False}

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=12516 

self.closeSec=1691540399, self.tradeDate='20230809', self.openTime='081000', self.closeTime='081959', self.symbol='BTCUSDT', self.open='29793.8', self.close='29804'
127.0.0.1 - - [09/Aug/2023 08:20:04] "POST / HTTP/1.1" 200 -
2023-08-09 08:20:08,388:INFO:testStrategy:main.py:101:handleKline:2217133: self.closeSec=1691540399, self.tradeDate='20230809', self.openTime='081000', self.closeTime='081959',self.symbol='BTCUSDT',self.open='29793.8', self.close='29804'
2023-08-09 08:20:08,536:INFO:testStrategy:main.py:102:handleKline:2217133: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
12141  20230809   073000    073959  1691537999  29808.7  29768.3
12142  20230809   074000    074959  1691538599  29768.5  29779.1
12143  20230809   075000    075959  1691539199    29779    29759
12144  20230809   080000    080959  1691539799  29758.9  29793.9
12145  20230809   081000    081959  1691540399  29793.8    29804
2023-08-09 08:20:08,536:INFO:testStrategy:main.py:103:handleKline:2217133: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': True, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True, 'isCorr': False}


## /root/FIL/strategy/sr_min/log.txt ----- -----

--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=1, self.total=996015.990996, self.flagDict['side']='buy', self.tradeCount=1, self.count=25024
self.closeSec=1691540399, self.tradeDate='20230809', self.openTime='081500', self.closeTime='081959', self.symbol='BTCUSDT', self.open=29806.6, self.close=29804.0, self.high=29813.6, self.low=29800.7, self.vol=420.937, self.amt=12546924.9573 
127.0.0.1 - - [09/Aug/2023 08:20:01] "POST / HTTP/1.1" 200 -
2023-08-09 08:20:06,556:INFO:sr_min:main.py:172:handleKline:2219263: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5855  20230809   075500    075959  ...         0.0        0.0       0
5856  20230809   080000    080459  ...         0.0        0.0       0
5857  20230809   080500    080959  ...         0.0        0.0       0
5858  20230809   081000    081459  ...         0.0        0.0       0
5859  20230809   081500    081959  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-08-09 08:20:06,585:INFO:sr_min:main.py:175:handleKline:2219263: self.closeSec=1691540399, self.tradeDate='20230809', self.openTime='081500', self.closeTime='081959',self.symbol='BTCUSDT',self.open=29806.6, self.close=29804.0, self.high=29813.6, self.low=29800.7, self.vol=420.937, self.amt=12546924.9573, ukdf['pct'].iloc[-1]=-8.4e-05 , ukdf['amount'].iloc[-1]=12546924.9573, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5859, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '37.141', 'enterprice': '26844', 'countrevence': '0', 'unrealprofit': '110069.83888583878', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '29807.56691758', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=1
127.0.0.1 - - [09/Aug/2023 08:25:00] "POST / HTTP/1.1" 200 -
--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=1, self.total=996015.990996, self.flagDict['side']='buy', self.tradeCount=1, self.count=25025
self.closeSec=1691540699, self.tradeDate='20230809', self.openTime='082000', self.closeTime='082459', self.symbol='BTCUSDT', self.open=29804.0, self.close=29812.4, self.high=29812.5, self.low=29799.6, self.vol=528.414, self.amt=15750757.9444 
2023-08-09 08:25:00,794:INFO:sr_min:main.py:172:handleKline:2219263: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5856  20230809   080000    080459  ...         0.0        0.0       0
5857  20230809   080500    080959  ...         0.0        0.0       0
5858  20230809   081000    081459  ...         0.0        0.0       0
5859  20230809   081500    081959  ...         0.0        0.0       0
5860  20230809   082000    082459  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-08-09 08:25:00,795:INFO:sr_min:main.py:175:handleKline:2219263: self.closeSec=1691540699, self.tradeDate='20230809', self.openTime='082000', self.closeTime='082459',self.symbol='BTCUSDT',self.open=29804.0, self.close=29812.4, self.high=29812.5, self.low=29799.6, self.vol=528.414, self.amt=15750757.9444, ukdf['pct'].iloc[-1]=0.000282 , ukdf['amount'].iloc[-1]=15750757.9444, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5860, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '37.141', 'enterprice': '26844', 'countrevence': '0', 'unrealprofit': '110253.0585', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '29812.5', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=1


## /root/FIL/strategy/s_rsrs/log.txt ----- -----

127.0.0.1 - - [09/Aug/2023 04:00:10] "POST / HTTP/1.1" 200 -
2023-08-09 04:00:10,652:INFO:s_rsrs:main.py:346:handleOrderFilled:2218689: handleOrderFilled: data=OrderType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'clientorderid': '42828F1691524805028I0L65', 'symbol': 'BTCUSDT', 'gatewayorderid': 1691524805435305, 'quantity': '54.719', 'price': '29884', 'stopprice': '0', 'ordertype': '', 'side': 'BUY', 'status': 'FILLED', 'positionside': 'LONG', 'createtime': 1691524804097, 'updatetime': 1691524805435, 'tradetype': 'usdt', 'selfid': 42828, 'filltrades': [TradeType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'tradeid': 1691524805435, 'clientorderid': '42828F1691524805028I0L65', 'price': '29884', 'quantity': '54.719', 'commission': '1635.222596', 'commissionasset': 'USDT', 'tradetime': 1691524805435, 'tradetype': 'usdt', 'gatetype': 'simulator', 'handletime': 1691524805435}], 'gatetype': 'simulator', 'handletime': 0}
2023-08-09 04:00:11,083:INFO:s_rsrs:main.py:343:handleOrderNew:2218689: handleOrderNew: data=OrderType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'clientorderid': '42829F1691524810610I0L65', 'symbol': 'BTCUSDT', 'gatewayorderid': 1691524811034927, 'quantity': '51.457', 'price': '29884.4', 'stopprice': '0', 'ordertype': '', 'side': 'BUY', 'status': 'FILLED', 'positionside': 'LONG', 'createtime': 1691524810117, 'updatetime': 1691524811034, 'tradetype': 'usdt', 'selfid': 42829, 'filltrades': [TradeType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'tradeid': 1691524811034, 'clientorderid': '42829F1691524810610I0L65', 'price': '29884.4', 'quantity': '51.457', 'commission': '1537.7615708', 'commissionasset': 'USDT', 'tradetime': 1691524811034, 'tradetype': 'usdt', 'gatetype': 'simulator', 'handletime': 1691524811034}], 'gatetype': 'simulator', 'handletime': 0}
127.0.0.1 - - [09/Aug/2023 04:00:11] "POST / HTTP/1.1" 200 -
127.0.0.1 - - [09/Aug/2023 04:00:11] "POST / HTTP/1.1" 200 -
2023-08-09 04:00:11,454:INFO:s_rsrs:main.py:346:handleOrderFilled:2218689: handleOrderFilled: data=OrderType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'clientorderid': '42829F1691524810610I0L65', 'symbol': 'BTCUSDT', 'gatewayorderid': 1691524811034927, 'quantity': '51.457', 'price': '29884.4', 'stopprice': '0', 'ordertype': '', 'side': 'BUY', 'status': 'FILLED', 'positionside': 'LONG', 'createtime': 1691524810117, 'updatetime': 1691524811034, 'tradetype': 'usdt', 'selfid': 42829, 'filltrades': [TradeType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'tradeid': 1691524811034, 'clientorderid': '42829F1691524810610I0L65', 'price': '29884.4', 'quantity': '51.457', 'commission': '1537.7615708', 'commissionasset': 'USDT', 'tradetime': 1691524811034, 'tradetype': 'usdt', 'gatetype': 'simulator', 'handletime': 1691524811034}], 'gatetype': 'simulator', 'handletime': 0}
--handleKline--:  version='2.0.0', self.name='s_rsrs', self.symbol='BTCUSDT', interval='4h', intervalSec=14400, wid=25, thd=0.6, self.sign=1, self.total=1536223.8092292, self.flagDict['side']='buy', self.tradeCount=19, self.count=521
self.closeSec=1691539199, self.tradeDate='20230809', self.openTime='040000', self.closeTime='075959', self.symbol='BTCUSDT', self.open=29866.4, self.close=29759.0, self.high=30250.0, self.low=29674.1, self.vol=94730.676, self.amt=2834460861.68981 
127.0.0.1 - - [09/Aug/2023 08:00:01] "POST / HTTP/1.1" 200 -
2023-08-09 08:00:01,700:INFO:s_rsrs:main.py:141:handleKline:2218689: self.closeSec=1691539199, self.tradeDate='20230809', self.openTime='040000', self.closeTime='075959',self.symbol='BTCUSDT',self.open=29866.4, self.close=29759.0, self.high=30250.0, self.low=29674.1, self.vol=94730.676, self.amt=2834460861.68981 
2023-08-09 08:00:01,715:INFO:s_rsrs:main.py:142:handleKline:2218689: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime  ...         vol           amt       pct
717  20230808   120000    155959  ...   30110.449  8.803045e+08 -0.000199
718  20230808   160000    195959  ...   46193.521  1.353444e+09  0.008603
719  20230808   200000    235959  ...  130655.635  3.852245e+09  0.003041
720  20230809   000000    035959  ...  136364.608  4.060005e+09  0.011847
721  20230809   040000    075959  ...   94730.676  2.834461e+09 -0.003623

[5 rows x 11 columns]
2023-08-09 08:00:02,519:INFO:s_rsrs:main.py:151:handleKline:2218689: df_s.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec  ...  index      beta    zscore  signal
717  20230808   120000    155959  1691481599  ...    717  0.010176 -1.364017    -1.0
718  20230808   160000    195959  1691495999  ...    718  0.023725 -1.303872    -1.0
719  20230808   200000    235959  1691510399  ...    719  0.146329 -0.768183    -1.0
720  20230809   000000    035959  1691524799  ...    720  0.525217  0.887531     1.0
721  20230809   040000    075959  1691539199  ...    721  1.132475  3.295378     1.0

[5 rows x 15 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '51.457', 'enterprice': '29884.4', 'countrevence': '0', 'unrealprofit': '-6375.87326298307', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '29760.49317949', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'numpy.int64'>, curSign=1, self.sign=1


