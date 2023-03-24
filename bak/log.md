# 20230324 08:26:02

## /root/FIL/strategy/amihud/log.txt ----- -----

--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=993672.4896432, self.flagDict['side']='sell', self.tradeCount=2, self.count=33628
self.closeSec=1679617199, self.tradeDate='20230324', self.openTime='081500', self.closeTime='081959', self.symbol='BTCUSDT', self.open=28305.0, self.close=28335.2, self.high=28341.2, self.low=28291.8, self.vol=1096.613, self.amt=31048517.7473 
127.0.0.1 - - [24/Mar/2023 08:20:03] "POST / HTTP/1.1" 200 -
2023-03-24 08:20:08,076:INFO:amihud:main.py:172:handleKline:200676: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5855  20230324   075500    075959  ...         0.0        0.0       0
5856  20230324   080000    080459  ...         0.0        0.0       0
5857  20230324   080500    080959  ...         0.0        0.0       0
5858  20230324   081000    081459  ...         0.0        0.0       0
5859  20230324   081500    081959  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-03-24 08:20:08,096:INFO:amihud:main.py:175:handleKline:200676: self.closeSec=1679617199, self.tradeDate='20230324', self.openTime='081500', self.closeTime='081959',self.symbol='BTCUSDT',self.open=28305.0, self.close=28335.2, self.high=28341.2, self.low=28291.8, self.vol=1096.613, self.amt=31048517.7473, ukdf['pct'].iloc[-1]=0.00107 , ukdf['amount'].iloc[-1]=31048517.7473, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5859, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '60.176', 'enterprice': '16529.3', 'countrevence': '0', 'unrealprofit': '-710498.032', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '28336.3', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1
127.0.0.1 - - [24/Mar/2023 08:25:01] "POST / HTTP/1.1" 200 -
--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=993672.4896432, self.flagDict['side']='sell', self.tradeCount=2, self.count=33629
self.closeSec=1679617499, self.tradeDate='20230324', self.openTime='082000', self.closeTime='082459', self.symbol='BTCUSDT', self.open=28335.1, self.close=28350.2, self.high=28369.1, self.low=28333.6, self.vol=1498.379, self.amt=42479485.4246 
2023-03-24 08:25:01,595:INFO:amihud:main.py:172:handleKline:200676: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5856  20230324   080000    080459  ...         0.0        0.0       0
5857  20230324   080500    080959  ...         0.0        0.0       0
5858  20230324   081000    081459  ...         0.0        0.0       0
5859  20230324   081500    081959  ...         0.0        0.0       0
5860  20230324   082000    082459  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-03-24 08:25:01,598:INFO:amihud:main.py:175:handleKline:200676: self.closeSec=1679617499, self.tradeDate='20230324', self.openTime='082000', self.closeTime='082459',self.symbol='BTCUSDT',self.open=28335.1, self.close=28350.2, self.high=28369.1, self.low=28333.6, self.vol=1498.379, self.amt=42479485.4246, ukdf['pct'].iloc[-1]=0.000529 , ukdf['amount'].iloc[-1]=42479485.4246, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5860, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '60.176', 'enterprice': '16529.3', 'countrevence': '0', 'unrealprofit': '-711335.60693889872', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '28350.21875397', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1


## /root/FIL/strategy/factorcheck/log.txt ----- -----


self.closeSec=1679617199, self.tradeDate='20230324', self.openTime='081500', self.closeTime='081959', self.symbol='BTCUSDT', self.open=28305.0, self.close=28335.2, self.high=28341.2, self.low=28291.8 
127.0.0.1 - - [24/Mar/2023 08:20:02] "POST / HTTP/1.1" 200 -
2023-03-24 08:20:04,407:INFO:factorcheck2:main.py:126:handleKline:185239: self.closeSec=1679617199, self.tradeDate='20230324', self.openTime='081500', self.closeTime='081959',self.symbol='BTCUSDT',self.open=28305.0, self.close=28335.2, self.high=28341.2, self.low=28291.8   
2023-03-24 08:20:05,798:INFO:factorcheck2:main.py:127:handleKline:185239: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime    closeSec  ...      low       pct  index  idx
1535  20230324   075500    075959  1679615999  ...  28275.5 -0.001042   1535    5
1536  20230324   080000    080459  1679616299  ...  28278.3 -0.000202   1536    0
1537  20230324   080500    080959  1679616599  ...  28270.8  0.000375   1537    1
1538  20230324   081000    081459  1679616899  ...  28289.3  0.000566   1538    2
1539  20230324   081500    081959  1679617199  ...  28291.8  0.001070   1539    3

[5 rows x 11 columns]
2023-03-24 08:20:05,807:INFO:factorcheck2:main.py:128:handleKline:185239: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=316, self.factor=0.42013268480660765, self.count=34195 

self.closeSec=1679617499, self.tradeDate='20230324', self.openTime='082000', self.closeTime='082459', self.symbol='BTCUSDT', self.open=28335.1, self.close=28350.2, self.high=28369.1, self.low=28333.6 
127.0.0.1 - - [24/Mar/2023 08:25:01] "POST / HTTP/1.1" 200 -
2023-03-24 08:25:01,517:INFO:factorcheck2:main.py:126:handleKline:185239: self.closeSec=1679617499, self.tradeDate='20230324', self.openTime='082000', self.closeTime='082459',self.symbol='BTCUSDT',self.open=28335.1, self.close=28350.2, self.high=28369.1, self.low=28333.6   
2023-03-24 08:25:01,566:INFO:factorcheck2:main.py:127:handleKline:185239: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime    closeSec  ...      low       pct  index  idx
1536  20230324   080000    080459  1679616299  ...  28278.3 -0.000202   1536    0
1537  20230324   080500    080959  1679616599  ...  28270.8  0.000375   1537    1
1538  20230324   081000    081459  1679616899  ...  28289.3  0.000566   1538    2
1539  20230324   081500    081959  1679617199  ...  28291.8  0.001070   1539    3
1540  20230324   082000    082459  1679617499  ...  28333.6  0.000529   1540    4

[5 rows x 11 columns]
2023-03-24 08:25:01,566:INFO:factorcheck2:main.py:128:handleKline:185239: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}


## /root/FIL/strategy/logic/log.txt ----- -----

2023-03-24 08:00:34,655:DEBUG:logic:main.py:463:getModel:885513: df_s.iloc[-5:,:] :
          date closeTime     open  ...    alpha58   alpha67   alpha72
5770  20230324    052959  28276.9  ...  52.916667  0.524111  0.416440
5771  20230324    055959  28115.5  ...  53.333333  0.527913  0.413582
5772  20230324    062959  28161.9  ...  53.333333  0.525096  0.413860
5773  20230324    065959  28131.3  ...  53.750000  0.531310  0.410905
5774  20230324    072959  28205.7  ...  54.166667  0.543484  0.401730

[5 rows x 33 columns]
0.5341959334565619
acc is : 0.5341959334565619
2023-03-24 08:00:34,822:INFO:logic:main.py:468:getModel:885513: df_pred.iloc[-5:,:] :
     pred    prob_0    prob_1  actual  ...       nav  sign  cost_        bm
536     0  0.508093  0.491907       1  ...  1.263103   1.0    0.0  1.365101
537     0  0.573473  0.426527       0  ...  1.261730   1.0    0.0  1.363618
538     1  0.499616  0.500384       1  ...  1.265072   1.0    0.0  1.367229
539     0  0.559775  0.440225       1  ...  1.271746   1.0    0.0  1.374442
540     0  0.581805  0.418195       0  ...  1.268579   1.0    0.0  1.371020

[5 rows x 10 columns]
2023-03-24 08:00:34,848:INFO:logic:main.py:478:getModel:885513: df_panel.iloc[-5:,:] :
    pred    prob_0    prob_1  actual  ...       nav  sign  cost_        bm
45     0  0.508378  0.491622       1  ...  1.263103   1.0    0.0  1.384020
46     0  0.574036  0.425964       0  ...  1.261730   1.0    0.0  1.381579
47     0  0.500254  0.499746       1  ...  1.265072   1.0    0.0  1.383987
48     0  0.559775  0.440225       1  ...  1.271746   1.0    0.0  1.374442
49     0  0.581805  0.418195       0  ...  1.268579   1.0    0.0  1.371020

[5 rows x 10 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': []}


## /root/FIL/strategy/modifiedmom/log.txt ----- -----

623  20230324   075000    075959  1679615999  28302.7  28284.1 -0.000622
2023-03-24 08:00:02,102:INFO:modifiedmom:main.py:146:handleKline:185213: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': True, 'isOpen': False, 'isClose': True, 'isTrig': False}
127.0.0.1 - - [24/Mar/2023 08:10:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=17096 

self.closeSec=1679616599, self.tradeDate='20230324', self.openTime='080000', self.closeTime='080959', self.symbol='BTCUSDT', self.open='28284', self.close='28288.9'
2023-03-24 08:10:01,717:INFO:modifiedmom:main.py:144:handleKline:185213: self.closeSec=1679616599, self.tradeDate='20230324', self.openTime='080000', self.closeTime='080959',self.symbol='BTCUSDT',self.open='28284', self.close='28288.9'
2023-03-24 08:10:01,751:INFO:modifiedmom:main.py:145:handleKline:185213: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec     open    close       pct
620  20230324   072000    072959  1679614199  28374.2  28354.6 -0.000694
621  20230324   073000    073959  1679614799  28354.6  28327.4 -0.000959
622  20230324   074000    074959  1679615399  28327.4  28301.7 -0.000907
623  20230324   075000    075959  1679615999  28302.7  28284.1 -0.000622
624  20230324   080000    080959  1679616599    28284  28288.9  0.000170
2023-03-24 08:10:01,751:INFO:modifiedmom:main.py:146:handleKline:185213: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': True, 'isOpen': False, 'isClose': True, 'isTrig': False}

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=17097 

self.closeSec=1679617199, self.tradeDate='20230324', self.openTime='081000', self.closeTime='081959', self.symbol='BTCUSDT', self.open='28293.6', self.close='28335.2'
127.0.0.1 - - [24/Mar/2023 08:20:03] "POST / HTTP/1.1" 200 -
2023-03-24 08:20:06,536:INFO:modifiedmom:main.py:144:handleKline:185213: self.closeSec=1679617199, self.tradeDate='20230324', self.openTime='081000', self.closeTime='081959',self.symbol='BTCUSDT',self.open='28293.6', self.close='28335.2'
2023-03-24 08:20:07,458:INFO:modifiedmom:main.py:145:handleKline:185213: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec     open    close       pct
621  20230324   073000    073959  1679614799  28354.6  28327.4 -0.000959
622  20230324   074000    074959  1679615399  28327.4  28301.7 -0.000907
623  20230324   075000    075959  1679615999  28302.7  28284.1 -0.000622
624  20230324   080000    080959  1679616599    28284  28288.9  0.000170
625  20230324   081000    081959  1679617199  28293.6  28335.2  0.001637
2023-03-24 08:20:07,466:INFO:modifiedmom:main.py:146:handleKline:185213: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': True, 'isOpen': False, 'isClose': True, 'isTrig': False}


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

17471  20230324   075000    075959  1679615999  28302.7  28284.1
2023-03-24 08:00:02,146:INFO:pyemd2:main.py:127:handleKline:185189: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}
127.0.0.1 - - [24/Mar/2023 08:10:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=17097 

self.closeSec=1679616599, self.tradeDate='20230324', self.openTime='080000', self.closeTime='080959', self.symbol='BTCUSDT', self.open='28284', self.close='28288.9'
2023-03-24 08:10:01,725:INFO:pyemd2:main.py:125:handleKline:185189: self.closeSec=1679616599, self.tradeDate='20230324', self.openTime='080000', self.closeTime='080959',self.symbol='BTCUSDT',self.open='28284', self.close='28288.9'
2023-03-24 08:10:01,767:INFO:pyemd2:main.py:126:handleKline:185189: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
17468  20230324   072000    072959  1679614199  28374.2  28354.6
17469  20230324   073000    073959  1679614799  28354.6  28327.4
17470  20230324   074000    074959  1679615399  28327.4  28301.7
17471  20230324   075000    075959  1679615999  28302.7  28284.1
17472  20230324   080000    080959  1679616599    28284  28288.9
2023-03-24 08:10:01,767:INFO:pyemd2:main.py:127:handleKline:185189: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=17098 

self.closeSec=1679617199, self.tradeDate='20230324', self.openTime='081000', self.closeTime='081959', self.symbol='BTCUSDT', self.open='28293.6', self.close='28335.2'
127.0.0.1 - - [24/Mar/2023 08:20:03] "POST / HTTP/1.1" 200 -
2023-03-24 08:20:09,923:INFO:pyemd2:main.py:125:handleKline:185189: self.closeSec=1679617199, self.tradeDate='20230324', self.openTime='081000', self.closeTime='081959',self.symbol='BTCUSDT',self.open='28293.6', self.close='28335.2'
2023-03-24 08:20:10,059:INFO:pyemd2:main.py:126:handleKline:185189: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
17469  20230324   073000    073959  1679614799  28354.6  28327.4
17470  20230324   074000    074959  1679615399  28327.4  28301.7
17471  20230324   075000    075959  1679615999  28302.7  28284.1
17472  20230324   080000    080959  1679616599    28284  28288.9
17473  20230324   081000    081959  1679617199  28293.6  28335.2
2023-03-24 08:20:10,060:INFO:pyemd2:main.py:127:handleKline:185189: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}


## /root/FIL/strategy/similarity/log.txt ----- -----

12143  20230324   075000    075959  1679615999  28302.7  28284.1
2023-03-24 08:00:02,159:INFO:testStrategy:main.py:103:handleKline:185174: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': True, 'isOpenSell': False, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True, 'isCorr': False}

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=17097 

self.closeSec=1679616599, self.tradeDate='20230324', self.openTime='080000', self.closeTime='080959', self.symbol='BTCUSDT', self.open='28284', self.close='28288.9'
2023-03-24 08:10:01,758:INFO:testStrategy:main.py:101:handleKline:185174: self.closeSec=1679616599, self.tradeDate='20230324', self.openTime='080000', self.closeTime='080959',self.symbol='BTCUSDT',self.open='28284', self.close='28288.9'
127.0.0.1 - - [24/Mar/2023 08:10:01] "POST / HTTP/1.1" 200 -
2023-03-24 08:10:01,775:INFO:testStrategy:main.py:102:handleKline:185174: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
12140  20230324   072000    072959  1679614199  28374.2  28354.6
12141  20230324   073000    073959  1679614799  28354.6  28327.4
12142  20230324   074000    074959  1679615399  28327.4  28301.7
12143  20230324   075000    075959  1679615999  28302.7  28284.1
12144  20230324   080000    080959  1679616599    28284  28288.9
2023-03-24 08:10:01,776:INFO:testStrategy:main.py:103:handleKline:185174: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': True, 'isOpenSell': False, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True, 'isCorr': False}

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=17098 

self.closeSec=1679617199, self.tradeDate='20230324', self.openTime='081000', self.closeTime='081959', self.symbol='BTCUSDT', self.open='28293.6', self.close='28335.2'
127.0.0.1 - - [24/Mar/2023 08:20:03] "POST / HTTP/1.1" 200 -
2023-03-24 08:20:09,371:INFO:testStrategy:main.py:101:handleKline:185174: self.closeSec=1679617199, self.tradeDate='20230324', self.openTime='081000', self.closeTime='081959',self.symbol='BTCUSDT',self.open='28293.6', self.close='28335.2'
2023-03-24 08:20:09,750:INFO:testStrategy:main.py:102:handleKline:185174: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
12141  20230324   073000    073959  1679614799  28354.6  28327.4
12142  20230324   074000    074959  1679615399  28327.4  28301.7
12143  20230324   075000    075959  1679615999  28302.7  28284.1
12144  20230324   080000    080959  1679616599    28284  28288.9
12145  20230324   081000    081959  1679617199  28293.6  28335.2
2023-03-24 08:20:09,750:INFO:testStrategy:main.py:103:handleKline:185174: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': True, 'isOpenSell': False, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True, 'isCorr': False}


## /root/FIL/strategy/sr_min/log.txt ----- -----

--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=0, self.total=1000000.0, self.flagDict['side']='', self.tradeCount=0, self.count=29626
self.closeSec=1679617199, self.tradeDate='20230324', self.openTime='081500', self.closeTime='081959', self.symbol='BTCUSDT', self.open=28305.0, self.close=28335.2, self.high=28341.2, self.low=28291.8, self.vol=1096.613, self.amt=31048517.7473 
127.0.0.1 - - [24/Mar/2023 08:20:02] "POST / HTTP/1.1" 200 -
2023-03-24 08:20:06,527:INFO:sr_min:main.py:172:handleKline:449472: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5855  20230324   075500    075959  ...         0.0        0.0       0
5856  20230324   080000    080459  ...         0.0        0.0       0
5857  20230324   080500    080959  ...         0.0        0.0       0
5858  20230324   081000    081459  ...         0.0        0.0       0
5859  20230324   081500    081959  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-03-24 08:20:06,557:INFO:sr_min:main.py:175:handleKline:449472: self.closeSec=1679617199, self.tradeDate='20230324', self.openTime='081500', self.closeTime='081959',self.symbol='BTCUSDT',self.open=28305.0, self.close=28335.2, self.high=28341.2, self.low=28291.8, self.vol=1096.613, self.amt=31048517.7473, ukdf['pct'].iloc[-1]=0.00107 , ukdf['amount'].iloc[-1]=31048517.7473, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5859, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': []}
type(curSign)=<class 'int'>, curSign=0, self.sign=0
--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=0, self.total=1000000.0, self.flagDict['side']='', self.tradeCount=0, self.count=29627
self.closeSec=1679617499, self.tradeDate='20230324', self.openTime='082000', self.closeTime='082459', self.symbol='BTCUSDT', self.open=28335.1, self.close=28350.2, self.high=28369.1, self.low=28333.6, self.vol=1498.379, self.amt=42479485.4246 
127.0.0.1 - - [24/Mar/2023 08:25:01] "POST / HTTP/1.1" 200 -
2023-03-24 08:25:01,602:INFO:sr_min:main.py:172:handleKline:449472: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5856  20230324   080000    080459  ...         0.0        0.0       0
5857  20230324   080500    080959  ...         0.0        0.0       0
5858  20230324   081000    081459  ...         0.0        0.0       0
5859  20230324   081500    081959  ...         0.0        0.0       0
5860  20230324   082000    082459  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-03-24 08:25:01,603:INFO:sr_min:main.py:175:handleKline:449472: self.closeSec=1679617499, self.tradeDate='20230324', self.openTime='082000', self.closeTime='082459',self.symbol='BTCUSDT',self.open=28335.1, self.close=28350.2, self.high=28369.1, self.low=28333.6, self.vol=1498.379, self.amt=42479485.4246, ukdf['pct'].iloc[-1]=0.000529 , ukdf['amount'].iloc[-1]=42479485.4246, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5860, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': []}
type(curSign)=<class 'int'>, curSign=0, self.sign=0


## /root/FIL/strategy/s_rsrs/log.txt ----- -----

719  20230323   200000    235959  1679587199  ...    719  0.015358 -2.323733    -1.0
720  20230324   000000    035959  1679601599  ...    720  0.014481 -2.293799    -1.0

[5 rows x 15 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '53.706', 'enterprice': '28091.1', 'countrevence': '0', 'unrealprofit': '-14015.08893491568', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '28352.05946328', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'numpy.int64'>, curSign=-1, self.sign=-1
--handleKline--:  version='2.0.0', self.name='s_rsrs', self.symbol='BTCUSDT', interval='4h', intervalSec=14400, wid=25, thd=0.6, self.sign=-1, self.total=1507151.9559834, self.flagDict['side']='sell', self.tradeCount=27, self.count=712
self.closeSec=1679615999, self.tradeDate='20230324', self.openTime='040000', self.closeTime='075959', self.symbol='BTCUSDT', self.open=28362.5, self.close=28284.1, self.high=28439.0, self.low=27945.8, self.vol=89487.014, self.amt=2524258106.575 
127.0.0.1 - - [24/Mar/2023 08:00:01] "POST / HTTP/1.1" 200 -
2023-03-24 08:00:01,967:INFO:s_rsrs:main.py:141:handleKline:185271: self.closeSec=1679615999, self.tradeDate='20230324', self.openTime='040000', self.closeTime='075959',self.symbol='BTCUSDT',self.open=28362.5, self.close=28284.1, self.high=28439.0, self.low=27945.8, self.vol=89487.014, self.amt=2524258106.575 
2023-03-24 08:00:02,037:INFO:s_rsrs:main.py:142:handleKline:185271: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime  ...         vol           amt       pct
717  20230323   120000    155959  ...   84538.137  2.326729e+09  0.009973
718  20230323   160000    195959  ...   67047.240  1.848970e+09 -0.001557
719  20230323   200000    235959  ...  280955.401  7.873060e+09  0.036307
720  20230324   000000    035959  ...  222300.561  6.267989e+09 -0.007419
721  20230324   040000    075959  ...   89487.014  2.524258e+09 -0.002764

[5 rows x 11 columns]
2023-03-24 08:00:04,640:INFO:s_rsrs:main.py:151:handleKline:185271: df_s.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec  ...  index      beta    zscore  signal
717  20230323   120000    155959  1679558399  ...    717  0.092907 -2.108669    -1.0
718  20230323   160000    195959  1679572799  ...    718  0.057176 -2.214658    -1.0
719  20230323   200000    235959  1679587199  ...    719  0.015358 -2.323733    -1.0
720  20230324   000000    035959  1679601599  ...    720  0.014481 -2.293799    -1.0
721  20230324   040000    075959  1679615999  ...    721  0.017394 -2.254048    -1.0

[5 rows x 15 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '53.706', 'enterprice': '28091.1', 'countrevence': '0', 'unrealprofit': '-10359.8874', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '28284', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'numpy.int64'>, curSign=-1, self.sign=-1


