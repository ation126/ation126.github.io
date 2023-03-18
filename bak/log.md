# 20230318 08:26:02

## /root/FIL/strategy/amihud/log.txt ----- -----

--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=993672.4896432, self.flagDict['side']='sell', self.tradeCount=2, self.count=31900
self.closeSec=1679098799, self.tradeDate='20230318', self.openTime='081500', self.closeTime='081959', self.symbol='BTCUSDT', self.open=27287.7, self.close=27081.6, self.high=27319.5, self.low=27050.0, self.vol=7106.393, self.amt=193165813.52225 
127.0.0.1 - - [18/Mar/2023 08:20:01] "POST / HTTP/1.1" 200 -
2023-03-18 08:20:03,191:INFO:amihud:main.py:172:handleKline:200676: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5855  20230318   075500    075959  ...         0.0        0.0       0
5856  20230318   080000    080459  ...         0.0        0.0       0
5857  20230318   080500    080959  ...         0.0        0.0       0
5858  20230318   081000    081459  ...         0.0        0.0       0
5859  20230318   081500    081959  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-03-18 08:20:03,201:INFO:amihud:main.py:175:handleKline:200676: self.closeSec=1679098799, self.tradeDate='20230318', self.openTime='081500', self.closeTime='081959',self.symbol='BTCUSDT',self.open=27287.7, self.close=27081.6, self.high=27319.5, self.low=27050.0, self.vol=7106.393, self.amt=193165813.52225, ukdf['pct'].iloc[-1]=-0.007549 , ukdf['amount'].iloc[-1]=193165813.52225, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5859, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '60.176', 'enterprice': '16529.3', 'countrevence': '0', 'unrealprofit': '-636613.18462244624', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '27108.48746049', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1
--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=993672.4896432, self.flagDict['side']='sell', self.tradeCount=2, self.count=31901
self.closeSec=1679099099, self.tradeDate='20230318', self.openTime='082000', self.closeTime='082459', self.symbol='BTCUSDT', self.open=27105.9, self.close=27173.7, self.high=27268.5, self.low=27092.7, self.vol=6973.957, self.amt=189622360.3505 
127.0.0.1 - - [18/Mar/2023 08:25:01] "POST / HTTP/1.1" 200 -
2023-03-18 08:25:01,547:INFO:amihud:main.py:172:handleKline:200676: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5856  20230318   080000    080459  ...         0.0        0.0       0
5857  20230318   080500    080959  ...         0.0        0.0       0
5858  20230318   081000    081459  ...         0.0        0.0       0
5859  20230318   081500    081959  ...         0.0        0.0       0
5860  20230318   082000    082459  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-03-18 08:25:01,553:INFO:amihud:main.py:175:handleKline:200676: self.closeSec=1679099099, self.tradeDate='20230318', self.openTime='082000', self.closeTime='082459',self.symbol='BTCUSDT',self.open=27105.9, self.close=27173.7, self.high=27268.5, self.low=27092.7, self.vol=6973.957, self.amt=189622360.3505, ukdf['pct'].iloc[-1]=0.003401 , ukdf['amount'].iloc[-1]=189622360.3505, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5860, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '60.176', 'enterprice': '16529.3', 'countrevence': '0', 'unrealprofit': '-640519.3616', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '27173.4', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1


## /root/FIL/strategy/factorcheck/log.txt ----- -----


self.closeSec=1679098799, self.tradeDate='20230318', self.openTime='081500', self.closeTime='081959', self.symbol='BTCUSDT', self.open=27287.7, self.close=27081.6, self.high=27319.5, self.low=27050.0 
127.0.0.1 - - [18/Mar/2023 08:20:01] "POST / HTTP/1.1" 200 -
2023-03-18 08:20:03,411:INFO:factorcheck2:main.py:126:handleKline:185239: self.closeSec=1679098799, self.tradeDate='20230318', self.openTime='081500', self.closeTime='081959',self.symbol='BTCUSDT',self.open=27287.7, self.close=27081.6, self.high=27319.5, self.low=27050.0   
2023-03-18 08:20:03,864:INFO:factorcheck2:main.py:127:handleKline:185239: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime    closeSec  ...      low       pct  index  idx
1535  20230318   075500    075959  1679097599  ...  27282.5  0.002662   1535    5
1536  20230318   080000    080459  1679097899  ...  27312.3  0.000314   1536    0
1537  20230318   080500    080959  1679098199  ...  27288.0 -0.001730   1537    1
1538  20230318   081000    081459  1679098499  ...  27286.5 -0.002187   1538    2
1539  20230318   081500    081959  1679098799  ...  27050.0 -0.007549   1539    3

[5 rows x 11 columns]
2023-03-18 08:20:03,864:INFO:factorcheck2:main.py:128:handleKline:185239: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}
127.0.0.1 - - [18/Mar/2023 08:25:01] "POST / HTTP/1.1" 200 -

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=28, self.factor=0.21965178392183654, self.count=32467 

self.closeSec=1679099099, self.tradeDate='20230318', self.openTime='082000', self.closeTime='082459', self.symbol='BTCUSDT', self.open=27105.9, self.close=27173.7, self.high=27268.5, self.low=27092.7 
2023-03-18 08:25:01,483:INFO:factorcheck2:main.py:126:handleKline:185239: self.closeSec=1679099099, self.tradeDate='20230318', self.openTime='082000', self.closeTime='082459',self.symbol='BTCUSDT',self.open=27105.9, self.close=27173.7, self.high=27268.5, self.low=27092.7   
2023-03-18 08:25:01,542:INFO:factorcheck2:main.py:127:handleKline:185239: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime    closeSec  ...      low       pct  index  idx
1536  20230318   080000    080459  1679097899  ...  27312.3  0.000314   1536    0
1537  20230318   080500    080959  1679098199  ...  27288.0 -0.001730   1537    1
1538  20230318   081000    081459  1679098499  ...  27286.5 -0.002187   1538    2
1539  20230318   081500    081959  1679098799  ...  27050.0 -0.007549   1539    3
1540  20230318   082000    082459  1679099099  ...  27092.7  0.003401   1540    4

[5 rows x 11 columns]
2023-03-18 08:25:01,543:INFO:factorcheck2:main.py:128:handleKline:185239: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}


## /root/FIL/strategy/logic/log.txt ----- -----

2023-03-18 08:00:33,274:DEBUG:logic:main.py:463:getModel:885513: df_s.iloc[-5:,:] :
          date closeTime     open  ...    alpha58   alpha67   alpha72
5770  20230318    052959  26761.8  ...  51.666667  0.622698  0.162642
5771  20230318    055959  26829.4  ...  51.666667  0.640811  0.157504
5772  20230318    062959  27089.5  ...  51.666667  0.659700  0.149070
5773  20230318    065959  27371.4  ...  52.083333  0.667429  0.146716
5774  20230318    072959  27511.6  ...  51.666667  0.649543  0.149515

[5 rows x 33 columns]
0.55637707948244
acc is : 0.55637707948244
2023-03-18 08:00:33,475:INFO:logic:main.py:468:getModel:885513: df_pred.iloc[-5:,:] :
     pred    prob_0    prob_1  actual  ...       nav  sign  cost_        bm
536     0  0.526741  0.473259       1  ...  1.194600   1.0    0.0  1.203963
537     0  0.589682  0.410318       1  ...  1.207592   1.0    0.0  1.217056
538     0  0.628396  0.371604       1  ...  1.213219   1.0    0.0  1.222727
539     0  0.594943  0.405057       0  ...  1.206533   1.0    0.0  1.215989
540     1  0.489579  0.510421       1  ...  1.207592   1.0    0.0  1.217056

[5 rows x 10 columns]
2023-03-18 08:00:33,508:INFO:logic:main.py:478:getModel:885513: df_panel.iloc[-5:,:] :
    pred    prob_0    prob_1  actual  ...       nav  sign  cost_        bm
45     0  0.526372  0.473628       1  ...  1.184827   1.0    0.0  1.201645
46     0  0.589293  0.410707       1  ...  1.207592   1.0    0.0  1.217987
47     0  0.627984  0.372016       1  ...  1.213219   1.0    0.0  1.221901
48     0  0.594597  0.405403       0  ...  1.206533   1.0    0.0  1.215989
49     1  0.489579  0.510421       1  ...  1.207592   1.0    0.0  1.217056

[5 rows x 10 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': []}


## /root/FIL/strategy/modifiedmom/log.txt ----- -----

623  20230318   075000    075959  1679097599  27299.2    27384  0.003106
2023-03-18 08:00:02,086:INFO:modifiedmom:main.py:146:handleKline:185213: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': True, 'isOpen': False, 'isClose': True, 'isTrig': False}

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=16232 

self.closeSec=1679098199, self.tradeDate='20230318', self.openTime='080000', self.closeTime='080959', self.symbol='BTCUSDT', self.open='27383.9', self.close='27347.4'
2023-03-18 08:10:01,727:INFO:modifiedmom:main.py:144:handleKline:185213: self.closeSec=1679098199, self.tradeDate='20230318', self.openTime='080000', self.closeTime='080959',self.symbol='BTCUSDT',self.open='27383.9', self.close='27347.4'
127.0.0.1 - - [18/Mar/2023 08:10:01] "POST / HTTP/1.1" 200 -
2023-03-18 08:10:01,738:INFO:modifiedmom:main.py:145:handleKline:185213: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec     open    close       pct
620  20230318   072000    072959  1679095799    27540    27360 -0.006536
621  20230318   073000    073959  1679096399    27359    27385  0.000914
622  20230318   074000    074959  1679096999    27385  27299.2 -0.003133
623  20230318   075000    075959  1679097599  27299.2    27384  0.003106
624  20230318   080000    080959  1679098199  27383.9  27347.4 -0.001337
2023-03-18 08:10:01,738:INFO:modifiedmom:main.py:146:handleKline:185213: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': True, 'isOpen': False, 'isClose': True, 'isTrig': False}

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=16233 

self.closeSec=1679098799, self.tradeDate='20230318', self.openTime='081000', self.closeTime='081959', self.symbol='BTCUSDT', self.open='27347.4', self.close='27081.6'
127.0.0.1 - - [18/Mar/2023 08:20:02] "POST / HTTP/1.1" 200 -
2023-03-18 08:20:03,132:INFO:modifiedmom:main.py:144:handleKline:185213: self.closeSec=1679098799, self.tradeDate='20230318', self.openTime='081000', self.closeTime='081959',self.symbol='BTCUSDT',self.open='27347.4', self.close='27081.6'
2023-03-18 08:20:03,402:INFO:modifiedmom:main.py:145:handleKline:185213: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec     open    close       pct
621  20230318   073000    073959  1679096399    27359    27385  0.000914
622  20230318   074000    074959  1679096999    27385  27299.2 -0.003133
623  20230318   075000    075959  1679097599  27299.2    27384  0.003106
624  20230318   080000    080959  1679098199  27383.9  27347.4 -0.001337
625  20230318   081000    081959  1679098799  27347.4  27081.6 -0.009719
2023-03-18 08:20:03,402:INFO:modifiedmom:main.py:146:handleKline:185213: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': True, 'isOpen': False, 'isClose': True, 'isTrig': False}


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

17471  20230318   075000    075959  1679097599  27299.2    27384
2023-03-18 08:00:02,088:INFO:pyemd2:main.py:127:handleKline:185189: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=16233 

self.closeSec=1679098199, self.tradeDate='20230318', self.openTime='080000', self.closeTime='080959', self.symbol='BTCUSDT', self.open='27383.9', self.close='27347.4'
127.0.0.1 - - [18/Mar/2023 08:10:01] "POST / HTTP/1.1" 200 -
2023-03-18 08:10:01,790:INFO:pyemd2:main.py:125:handleKline:185189: self.closeSec=1679098199, self.tradeDate='20230318', self.openTime='080000', self.closeTime='080959',self.symbol='BTCUSDT',self.open='27383.9', self.close='27347.4'
2023-03-18 08:10:01,826:INFO:pyemd2:main.py:126:handleKline:185189: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
17468  20230318   072000    072959  1679095799    27540    27360
17469  20230318   073000    073959  1679096399    27359    27385
17470  20230318   074000    074959  1679096999    27385  27299.2
17471  20230318   075000    075959  1679097599  27299.2    27384
17472  20230318   080000    080959  1679098199  27383.9  27347.4
2023-03-18 08:10:01,827:INFO:pyemd2:main.py:127:handleKline:185189: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=16234 

self.closeSec=1679098799, self.tradeDate='20230318', self.openTime='081000', self.closeTime='081959', self.symbol='BTCUSDT', self.open='27347.4', self.close='27081.6'
127.0.0.1 - - [18/Mar/2023 08:20:02] "POST / HTTP/1.1" 200 -
2023-03-18 08:20:04,541:INFO:pyemd2:main.py:125:handleKline:185189: self.closeSec=1679098799, self.tradeDate='20230318', self.openTime='081000', self.closeTime='081959',self.symbol='BTCUSDT',self.open='27347.4', self.close='27081.6'
2023-03-18 08:20:04,660:INFO:pyemd2:main.py:126:handleKline:185189: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
17469  20230318   073000    073959  1679096399    27359    27385
17470  20230318   074000    074959  1679096999    27385  27299.2
17471  20230318   075000    075959  1679097599  27299.2    27384
17472  20230318   080000    080959  1679098199  27383.9  27347.4
17473  20230318   081000    081959  1679098799  27347.4  27081.6
2023-03-18 08:20:04,661:INFO:pyemd2:main.py:127:handleKline:185189: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}


## /root/FIL/strategy/similarity/log.txt ----- -----

12143  20230318   075000    075959  1679097599  27299.2    27384
2023-03-18 08:00:02,101:INFO:testStrategy:main.py:103:handleKline:185174: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': True, 'isOpenSell': False, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True, 'isCorr': False}
127.0.0.1 - - [18/Mar/2023 08:10:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=16233 

self.closeSec=1679098199, self.tradeDate='20230318', self.openTime='080000', self.closeTime='080959', self.symbol='BTCUSDT', self.open='27383.9', self.close='27347.4'
2023-03-18 08:10:01,750:INFO:testStrategy:main.py:101:handleKline:185174: self.closeSec=1679098199, self.tradeDate='20230318', self.openTime='080000', self.closeTime='080959',self.symbol='BTCUSDT',self.open='27383.9', self.close='27347.4'
2023-03-18 08:10:01,789:INFO:testStrategy:main.py:102:handleKline:185174: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
12140  20230318   072000    072959  1679095799    27540    27360
12141  20230318   073000    073959  1679096399    27359    27385
12142  20230318   074000    074959  1679096999    27385  27299.2
12143  20230318   075000    075959  1679097599  27299.2    27384
12144  20230318   080000    080959  1679098199  27383.9  27347.4
2023-03-18 08:10:01,789:INFO:testStrategy:main.py:103:handleKline:185174: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': True, 'isOpenSell': False, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True, 'isCorr': False}

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=16234 

self.closeSec=1679098799, self.tradeDate='20230318', self.openTime='081000', self.closeTime='081959', self.symbol='BTCUSDT', self.open='27347.4', self.close='27081.6'
127.0.0.1 - - [18/Mar/2023 08:20:02] "POST / HTTP/1.1" 200 -
2023-03-18 08:20:04,245:INFO:testStrategy:main.py:101:handleKline:185174: self.closeSec=1679098799, self.tradeDate='20230318', self.openTime='081000', self.closeTime='081959',self.symbol='BTCUSDT',self.open='27347.4', self.close='27081.6'
2023-03-18 08:20:04,482:INFO:testStrategy:main.py:102:handleKline:185174: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
12141  20230318   073000    073959  1679096399    27359    27385
12142  20230318   074000    074959  1679096999    27385  27299.2
12143  20230318   075000    075959  1679097599  27299.2    27384
12144  20230318   080000    080959  1679098199  27383.9  27347.4
12145  20230318   081000    081959  1679098799  27347.4  27081.6
2023-03-18 08:20:04,482:INFO:testStrategy:main.py:103:handleKline:185174: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': True, 'isOpenSell': False, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True, 'isCorr': False}


## /root/FIL/strategy/sr_min/log.txt ----- -----

127.0.0.1 - - [18/Mar/2023 08:20:01] "POST / HTTP/1.1" 200 -
--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=0, self.total=1000000.0, self.flagDict['side']='', self.tradeCount=0, self.count=27898
self.closeSec=1679098799, self.tradeDate='20230318', self.openTime='081500', self.closeTime='081959', self.symbol='BTCUSDT', self.open=27287.7, self.close=27081.6, self.high=27319.5, self.low=27050.0, self.vol=7106.393, self.amt=193165813.52225 
2023-03-18 08:20:01,759:INFO:sr_min:main.py:172:handleKline:449472: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5855  20230318   075500    075959  ...         0.0        0.0       0
5856  20230318   080000    080459  ...         0.0        0.0       0
5857  20230318   080500    080959  ...         0.0        0.0       0
5858  20230318   081000    081459  ...         0.0        0.0       0
5859  20230318   081500    081959  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-03-18 08:20:01,763:INFO:sr_min:main.py:175:handleKline:449472: self.closeSec=1679098799, self.tradeDate='20230318', self.openTime='081500', self.closeTime='081959',self.symbol='BTCUSDT',self.open=27287.7, self.close=27081.6, self.high=27319.5, self.low=27050.0, self.vol=7106.393, self.amt=193165813.52225, ukdf['pct'].iloc[-1]=-0.007549 , ukdf['amount'].iloc[-1]=193165813.52225, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5859, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': []}
type(curSign)=<class 'int'>, curSign=0, self.sign=0
127.0.0.1 - - [18/Mar/2023 08:25:01] "POST / HTTP/1.1" 200 -
--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=0, self.total=1000000.0, self.flagDict['side']='', self.tradeCount=0, self.count=27899
self.closeSec=1679099099, self.tradeDate='20230318', self.openTime='082000', self.closeTime='082459', self.symbol='BTCUSDT', self.open=27105.9, self.close=27173.7, self.high=27268.5, self.low=27092.7, self.vol=6973.957, self.amt=189622360.3505 
2023-03-18 08:25:01,552:INFO:sr_min:main.py:172:handleKline:449472: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5856  20230318   080000    080459  ...         0.0        0.0       0
5857  20230318   080500    080959  ...         0.0        0.0       0
5858  20230318   081000    081459  ...         0.0        0.0       0
5859  20230318   081500    081959  ...         0.0        0.0       0
5860  20230318   082000    082459  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-03-18 08:25:01,552:INFO:sr_min:main.py:175:handleKline:449472: self.closeSec=1679099099, self.tradeDate='20230318', self.openTime='082000', self.closeTime='082459',self.symbol='BTCUSDT',self.open=27105.9, self.close=27173.7, self.high=27268.5, self.low=27092.7, self.vol=6973.957, self.amt=189622360.3505, ukdf['pct'].iloc[-1]=0.003401 , ukdf['amount'].iloc[-1]=189622360.3505, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5860, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': []}
type(curSign)=<class 'int'>, curSign=0, self.sign=0


## /root/FIL/strategy/s_rsrs/log.txt ----- -----

718  20230317   160000    195959  ...  276532.318  7.318397e+09  0.033202
719  20230317   200000    235959  ...  264742.761  7.010303e+09 -0.018546
720  20230318   000000    035959  ...  166484.320  4.421618e+09  0.015141
721  20230318   040000    075959  ...  271230.892  7.389118e+09  0.021315

[5 rows x 11 columns]
2023-03-18 08:00:04,603:INFO:s_rsrs:main.py:151:handleKline:185271: df_s.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec  ...  index      beta    zscore  signal
717  20230317   120000    155959  1679039999  ...    717  0.437985 -0.501484     NaN
718  20230317   160000    195959  1679054399  ...    718  0.393393 -0.626256    -1.0
719  20230317   200000    235959  1679068799  ...    719  0.301906 -0.883417    -1.0
720  20230318   000000    035959  1679083199  ...    720  0.764404  0.443770     NaN
721  20230318   040000    075959  1679097599  ...    721  0.897811  0.812698     1.0

[5 rows x 15 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '55.764', 'enterprice': '26915.4', 'countrevence': '0', 'unrealprofit': '-26238.96811937988', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '27385.93597517', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'numpy.int64'>, curSign=1, self.sign=-1
handlebackTrade > queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '55.764', 'enterprice': '26915.4', 'countrevence': '0', 'unrealprofit': '-26238.96811937988', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '27385.93597517', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
2023-03-18 08:00:10,552:INFO:s_rsrs:main.py:182:queryContractAssets:185271: queryContractAssets: assets=ContractAssetReturn{'result': [ContractAsset{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'asset': 'USDT', 'free': '1477566.9689989', 'total': '1477566.9689989', 'margin': '0', 'unreal': '0', 'type': 'AssetType_ucontract'}]}
2023-03-18 08:00:10,778:DEBUG:s_rsrs:main.py:253:openBuy:185271: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': True, 'isOpenSell': True, 'isCloseBuy': False, 'isCloseSell': False, 'isOpen': True, 'isClose': False, 'isTrig': False}
2023-03-18 08:00:10,779:INFO:s_rsrs:main.py:254:openBuy:185271: ret = self.client.insertMarketUOrder("simulator", "BTCUSDT", 53.795, "buy"), ret=InsertOrderReturn{'result': 'success', 'clientorderid': '42016F1679097610778I0L65'}
2023-03-18 08:00:10,803:INFO:s_rsrs:main.py:176:insertFactor:185271: curDateTime:3180800, name:s_rsrs, symbol:BTCUSDT, tradeDate:20230318, closeTime:075959, close:27384.0, sign:1, total:1477566.9689989, side:buy  
127.0.0.1 - - [18/Mar/2023 08:00:10] "POST / HTTP/1.1" 200 -
2023-03-18 08:00:10,805:INFO:s_rsrs:main.py:343:handleOrderNew:185271: handleOrderNew: data=OrderType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'clientorderid': '42015F1679097605463I0L65', 'symbol': 'BTCUSDT', 'gatewayorderid': 1679097605562270, 'quantity': '55.764', 'price': '27384', 'stopprice': '0', 'ordertype': '', 'side': 'BUY', 'status': 'FILLED', 'positionside': 'LONG', 'createtime': 1679097604886, 'updatetime': 1679097605562, 'tradetype': 'usdt', 'selfid': 42015, 'filltrades': [TradeType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'tradeid': 1679097605562, 'clientorderid': '42015F1679097605463I0L65', 'price': '27384', 'quantity': '55.764', 'commission': '1527.041376', 'commissionasset': 'USDT', 'tradetime': 1679097605562, 'tradetype': 'usdt', 'gatetype': 'simulator', 'handletime': 1679097605562}], 'gatetype': 'simulator', 'handletime': 0}
2023-03-18 08:00:10,806:INFO:s_rsrs:main.py:346:handleOrderFilled:185271: handleOrderFilled: data=OrderType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'clientorderid': '42015F1679097605463I0L65', 'symbol': 'BTCUSDT', 'gatewayorderid': 1679097605562270, 'quantity': '55.764', 'price': '27384', 'stopprice': '0', 'ordertype': '', 'side': 'BUY', 'status': 'FILLED', 'positionside': 'LONG', 'createtime': 1679097604886, 'updatetime': 1679097605562, 'tradetype': 'usdt', 'selfid': 42015, 'filltrades': [TradeType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'tradeid': 1679097605562, 'clientorderid': '42015F1679097605463I0L65', 'price': '27384', 'quantity': '55.764', 'commission': '1527.041376', 'commissionasset': 'USDT', 'tradetime': 1679097605562, 'tradetype': 'usdt', 'gatetype': 'simulator', 'handletime': 1679097605562}], 'gatetype': 'simulator', 'handletime': 0}
127.0.0.1 - - [18/Mar/2023 08:00:10] "POST / HTTP/1.1" 200 -
2023-03-18 08:00:10,972:INFO:s_rsrs:main.py:343:handleOrderNew:185271: handleOrderNew: data=OrderType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'clientorderid': '42016F1679097610778I0L65', 'symbol': 'BTCUSDT', 'gatewayorderid': 1679097610940533, 'quantity': '53.795', 'price': '27400', 'stopprice': '0', 'ordertype': '', 'side': 'BUY', 'status': 'FILLED', 'positionside': 'LONG', 'createtime': 1679097610574, 'updatetime': 1679097610940, 'tradetype': 'usdt', 'selfid': 42016, 'filltrades': [TradeType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'tradeid': 1679097610940, 'clientorderid': '42016F1679097610778I0L65', 'price': '27400', 'quantity': '53.795', 'commission': '1473.983', 'commissionasset': 'USDT', 'tradetime': 1679097610940, 'tradetype': 'usdt', 'gatetype': 'simulator', 'handletime': 1679097610940}], 'gatetype': 'simulator', 'handletime': 0}
127.0.0.1 - - [18/Mar/2023 08:00:10] "POST / HTTP/1.1" 200 -
127.0.0.1 - - [18/Mar/2023 08:00:11] "POST / HTTP/1.1" 200 -
2023-03-18 08:00:11,157:INFO:s_rsrs:main.py:346:handleOrderFilled:185271: handleOrderFilled: data=OrderType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'clientorderid': '42016F1679097610778I0L65', 'symbol': 'BTCUSDT', 'gatewayorderid': 1679097610940533, 'quantity': '53.795', 'price': '27400', 'stopprice': '0', 'ordertype': '', 'side': 'BUY', 'status': 'FILLED', 'positionside': 'LONG', 'createtime': 1679097610574, 'updatetime': 1679097610940, 'tradetype': 'usdt', 'selfid': 42016, 'filltrades': [TradeType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'tradeid': 1679097610940, 'clientorderid': '42016F1679097610778I0L65', 'price': '27400', 'quantity': '53.795', 'commission': '1473.983', 'commissionasset': 'USDT', 'tradetime': 1679097610940, 'tradetype': 'usdt', 'gatetype': 'simulator', 'handletime': 1679097610940}], 'gatetype': 'simulator', 'handletime': 0}


