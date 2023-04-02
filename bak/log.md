# 20230402 08:26:01

## /root/FIL/strategy/amihud/log.txt ----- -----

--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=993672.4896432, self.flagDict['side']='sell', self.tradeCount=2, self.count=36220
self.closeSec=1680394799, self.tradeDate='20230402', self.openTime='081500', self.closeTime='081959', self.symbol='BTCUSDT', self.open=28458.4, self.close=28467.8, self.high=28487.8, self.low=28458.4, self.vol=523.516, self.amt=14908025.2022 
127.0.0.1 - - [02/Apr/2023 08:20:04] "POST / HTTP/1.1" 200 -
2023-04-02 08:20:09,030:INFO:amihud:main.py:172:handleKline:200676: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5855  20230402   075500    075959  ...         0.0        0.0       0
5856  20230402   080000    080459  ...         0.0        0.0       0
5857  20230402   080500    080959  ...         0.0        0.0       0
5858  20230402   081000    081459  ...         0.0        0.0       0
5859  20230402   081500    081959  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-04-02 08:20:09,051:INFO:amihud:main.py:175:handleKline:200676: self.closeSec=1680394799, self.tradeDate='20230402', self.openTime='081500', self.closeTime='081959',self.symbol='BTCUSDT',self.open=28458.4, self.close=28467.8, self.high=28487.8, self.low=28458.4, self.vol=523.516, self.amt=14908025.2022, ukdf['pct'].iloc[-1]=0.00033 , ukdf['amount'].iloc[-1]=14908025.2022, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5859, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '60.176', 'enterprice': '16529.3', 'countrevence': '0', 'unrealprofit': '-718174.05151700688', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '28463.85948413', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1
127.0.0.1 - - [02/Apr/2023 08:25:01] "POST / HTTP/1.1" 200 -
--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=993672.4896432, self.flagDict['side']='sell', self.tradeCount=2, self.count=36221
self.closeSec=1680395099, self.tradeDate='20230402', self.openTime='082000', self.closeTime='082459', self.symbol='BTCUSDT', self.open=28467.7, self.close=28449.6, self.high=28467.8, self.low=28444.4, self.vol=497.429, self.amt=14152067.9159 
2023-04-02 08:25:01,632:INFO:amihud:main.py:172:handleKline:200676: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5856  20230402   080000    080459  ...         0.0        0.0       0
5857  20230402   080500    080959  ...         0.0        0.0       0
5858  20230402   081000    081459  ...         0.0        0.0       0
5859  20230402   081500    081959  ...         0.0        0.0       0
5860  20230402   082000    082459  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-04-02 08:25:01,633:INFO:amihud:main.py:175:handleKline:200676: self.closeSec=1680395099, self.tradeDate='20230402', self.openTime='082000', self.closeTime='082459',self.symbol='BTCUSDT',self.open=28467.7, self.close=28449.6, self.high=28467.8, self.low=28444.4, self.vol=497.429, self.amt=14152067.9159, ukdf['pct'].iloc[-1]=-0.000639 , ukdf['amount'].iloc[-1]=14152067.9159, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5860, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '60.176', 'enterprice': '16529.3', 'countrevence': '0', 'unrealprofit': '-717321.9904', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '28449.7', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1


## /root/FIL/strategy/factorcheck/log.txt ----- -----


self.closeSec=1680394799, self.tradeDate='20230402', self.openTime='081500', self.closeTime='081959', self.symbol='BTCUSDT', self.open=28458.4, self.close=28467.8, self.high=28487.8, self.low=28458.4 
127.0.0.1 - - [02/Apr/2023 08:20:02] "POST / HTTP/1.1" 200 -
2023-04-02 08:20:05,740:INFO:factorcheck2:main.py:126:handleKline:185239: self.closeSec=1680394799, self.tradeDate='20230402', self.openTime='081500', self.closeTime='081959',self.symbol='BTCUSDT',self.open=28458.4, self.close=28467.8, self.high=28487.8, self.low=28458.4   
2023-04-02 08:20:06,911:INFO:factorcheck2:main.py:127:handleKline:185239: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime    closeSec  ...      low       pct  index  idx
1535  20230402   075500    075959  1680393599  ...  28433.2 -0.000155   1535    5
1536  20230402   080000    080459  1680393899  ...  28438.4 -0.000007   1536    0
1537  20230402   080500    080959  1680394199  ...  28443.5  0.000211   1537    1
1538  20230402   081000    081459  1680394499  ...  28449.5  0.000309   1538    2
1539  20230402   081500    081959  1680394799  ...  28458.4  0.000330   1539    3

[5 rows x 11 columns]
2023-04-02 08:20:06,920:INFO:factorcheck2:main.py:128:handleKline:185239: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=21, self.factor=0.49844370134763516, self.count=36787 

self.closeSec=1680395099, self.tradeDate='20230402', self.openTime='082000', self.closeTime='082459', self.symbol='BTCUSDT', self.open=28467.7, self.close=28449.6, self.high=28467.8, self.low=28444.4 
127.0.0.1 - - [02/Apr/2023 08:25:01] "POST / HTTP/1.1" 200 -
2023-04-02 08:25:01,525:INFO:factorcheck2:main.py:126:handleKline:185239: self.closeSec=1680395099, self.tradeDate='20230402', self.openTime='082000', self.closeTime='082459',self.symbol='BTCUSDT',self.open=28467.7, self.close=28449.6, self.high=28467.8, self.low=28444.4   
2023-04-02 08:25:01,583:INFO:factorcheck2:main.py:127:handleKline:185239: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime    closeSec  ...      low       pct  index  idx
1536  20230402   080000    080459  1680393899  ...  28438.4 -0.000007   1536    0
1537  20230402   080500    080959  1680394199  ...  28443.5  0.000211   1537    1
1538  20230402   081000    081459  1680394499  ...  28449.5  0.000309   1538    2
1539  20230402   081500    081959  1680394799  ...  28458.4  0.000330   1539    3
1540  20230402   082000    082459  1680395099  ...  28444.4 -0.000639   1540    4

[5 rows x 11 columns]
2023-04-02 08:25:01,583:INFO:factorcheck2:main.py:128:handleKline:185239: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}


## /root/FIL/strategy/logic/log.txt ----- -----

2023-04-02 08:00:35,657:DEBUG:logic:main.py:463:getModel:885513: df_s.iloc[-5:,:] :
          date closeTime     open  ...    alpha58   alpha67   alpha72
5770  20230402    052959  28435.1  ...  52.916667  0.528036  0.642546
5771  20230402    055959  28462.7  ...  52.916667  0.528442  0.637848
5772  20230402    062959  28464.8  ...  53.333333  0.536159  0.612578
5773  20230402    065959  28504.5  ...  53.333333  0.536114  0.589022
5774  20230402    072959  28504.3  ...  52.916667  0.532353  0.569550

[5 rows x 33 columns]
0.5231053604436229
acc is : 0.5231053604436229
2023-04-02 08:00:35,823:INFO:logic:main.py:468:getModel:885513: df_pred.iloc[-5:,:] :
     pred    prob_0    prob_1  actual  ...       nav  sign  cost_        bm
536     0  0.535239  0.464761       1  ...  0.958327   1.0    0.0  1.009161
537     0  0.532456  0.467544       1  ...  0.959667   1.0    0.0  1.010572
538     0  0.540218  0.459782       1  ...  0.959660   1.0    0.0  1.010565
539     0  0.529793  0.470207       0  ...  0.959105   1.0    0.0  1.009980
540     0  0.523520  0.476480       0  ...  0.957623   1.0    0.0  1.008420

[5 rows x 10 columns]
2023-04-02 08:00:35,855:INFO:logic:main.py:478:getModel:885513: df_panel.iloc[-5:,:] :
    pred    prob_0    prob_1  actual  ...       nav  sign  cost_        bm
45     0  0.535498  0.464502       1  ...  0.950606   1.0    0.0  1.015581
46     0  0.532609  0.467391       1  ...  1.001304   1.0    0.0  1.014092
47     0  0.539608  0.460392       1  ...  0.951929   1.0    0.0  1.005762
48     0  0.529373  0.470627       0  ...  0.959105   1.0    0.0  1.009980
49     0  0.523520  0.476480       0  ...  0.957623   1.0    0.0  1.008420

[5 rows x 10 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': []}


## /root/FIL/strategy/modifiedmom/log.txt ----- -----

623  20230402   075000    075959  1680393599  28461.9  28443.8 -0.000636
2023-04-02 08:00:01,902:INFO:modifiedmom:main.py:146:handleKline:185213: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': True, 'isOpen': False, 'isClose': True, 'isTrig': False}
127.0.0.1 - - [02/Apr/2023 08:10:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=18392 

self.closeSec=1680394199, self.tradeDate='20230402', self.openTime='080000', self.closeTime='080959', self.symbol='BTCUSDT', self.open='28443.7', self.close='28449.6'
2023-04-02 08:10:01,622:INFO:modifiedmom:main.py:144:handleKline:185213: self.closeSec=1680394199, self.tradeDate='20230402', self.openTime='080000', self.closeTime='080959',self.symbol='BTCUSDT',self.open='28443.7', self.close='28449.6'
2023-04-02 08:10:01,680:INFO:modifiedmom:main.py:145:handleKline:185213: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec     open    close       pct
620  20230402   072000    072959  1680391799  28529.7  28487.8 -0.001469
621  20230402   073000    073959  1680392399  28487.9  28463.1 -0.000867
622  20230402   074000    074959  1680392999  28463.1  28461.9 -0.000042
623  20230402   075000    075959  1680393599  28461.9  28443.8 -0.000636
624  20230402   080000    080959  1680394199  28443.7  28449.6  0.000204
2023-04-02 08:10:01,680:INFO:modifiedmom:main.py:146:handleKline:185213: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': True, 'isOpen': False, 'isClose': True, 'isTrig': False}

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=18393 

self.closeSec=1680394799, self.tradeDate='20230402', self.openTime='081000', self.closeTime='081959', self.symbol='BTCUSDT', self.open='28449.6', self.close='28467.7'
127.0.0.1 - - [02/Apr/2023 08:20:04] "POST / HTTP/1.1" 200 -
2023-04-02 08:20:07,391:INFO:modifiedmom:main.py:144:handleKline:185213: self.closeSec=1680394799, self.tradeDate='20230402', self.openTime='081000', self.closeTime='081959',self.symbol='BTCUSDT',self.open='28449.6', self.close='28467.7'
2023-04-02 08:20:08,280:INFO:modifiedmom:main.py:145:handleKline:185213: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec     open    close       pct
621  20230402   073000    073959  1680392399  28487.9  28463.1 -0.000867
622  20230402   074000    074959  1680392999  28463.1  28461.9 -0.000042
623  20230402   075000    075959  1680393599  28461.9  28443.8 -0.000636
624  20230402   080000    080959  1680394199  28443.7  28449.6  0.000204
625  20230402   081000    081959  1680394799  28449.6  28467.7  0.000636
2023-04-02 08:20:08,281:INFO:modifiedmom:main.py:146:handleKline:185213: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': True, 'isOpen': False, 'isClose': True, 'isTrig': False}


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

17471  20230402   075000    075959  1680393599  28461.9  28443.8
2023-04-02 08:00:01,949:INFO:pyemd2:main.py:127:handleKline:185189: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}
127.0.0.1 - - [02/Apr/2023 08:10:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=18393 

self.closeSec=1680394199, self.tradeDate='20230402', self.openTime='080000', self.closeTime='080959', self.symbol='BTCUSDT', self.open='28443.7', self.close='28449.6'
2023-04-02 08:10:01,657:INFO:pyemd2:main.py:125:handleKline:185189: self.closeSec=1680394199, self.tradeDate='20230402', self.openTime='080000', self.closeTime='080959',self.symbol='BTCUSDT',self.open='28443.7', self.close='28449.6'
2023-04-02 08:10:01,699:INFO:pyemd2:main.py:126:handleKline:185189: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
17468  20230402   072000    072959  1680391799  28529.7  28487.8
17469  20230402   073000    073959  1680392399  28487.9  28463.1
17470  20230402   074000    074959  1680392999  28463.1  28461.9
17471  20230402   075000    075959  1680393599  28461.9  28443.8
17472  20230402   080000    080959  1680394199  28443.7  28449.6
2023-04-02 08:10:01,700:INFO:pyemd2:main.py:127:handleKline:185189: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=18394 

self.closeSec=1680394799, self.tradeDate='20230402', self.openTime='081000', self.closeTime='081959', self.symbol='BTCUSDT', self.open='28449.6', self.close='28467.7'
127.0.0.1 - - [02/Apr/2023 08:20:04] "POST / HTTP/1.1" 200 -
2023-04-02 08:20:10,830:INFO:pyemd2:main.py:125:handleKline:185189: self.closeSec=1680394799, self.tradeDate='20230402', self.openTime='081000', self.closeTime='081959',self.symbol='BTCUSDT',self.open='28449.6', self.close='28467.7'
2023-04-02 08:20:10,937:INFO:pyemd2:main.py:126:handleKline:185189: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
17469  20230402   073000    073959  1680392399  28487.9  28463.1
17470  20230402   074000    074959  1680392999  28463.1  28461.9
17471  20230402   075000    075959  1680393599  28461.9  28443.8
17472  20230402   080000    080959  1680394199  28443.7  28449.6
17473  20230402   081000    081959  1680394799  28449.6  28467.7
2023-04-02 08:20:10,937:INFO:pyemd2:main.py:127:handleKline:185189: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}


## /root/FIL/strategy/similarity/log.txt ----- -----

12143  20230402   075000    075959  1680393599  28461.9  28443.8
2023-04-02 08:00:01,931:INFO:testStrategy:main.py:103:handleKline:185174: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': True, 'isOpenSell': False, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True, 'isCorr': False}
127.0.0.1 - - [02/Apr/2023 08:10:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=18393 

self.closeSec=1680394199, self.tradeDate='20230402', self.openTime='080000', self.closeTime='080959', self.symbol='BTCUSDT', self.open='28443.7', self.close='28449.6'
2023-04-02 08:10:01,653:INFO:testStrategy:main.py:101:handleKline:185174: self.closeSec=1680394199, self.tradeDate='20230402', self.openTime='080000', self.closeTime='080959',self.symbol='BTCUSDT',self.open='28443.7', self.close='28449.6'
2023-04-02 08:10:01,687:INFO:testStrategy:main.py:102:handleKline:185174: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
12140  20230402   072000    072959  1680391799  28529.7  28487.8
12141  20230402   073000    073959  1680392399  28487.9  28463.1
12142  20230402   074000    074959  1680392999  28463.1  28461.9
12143  20230402   075000    075959  1680393599  28461.9  28443.8
12144  20230402   080000    080959  1680394199  28443.7  28449.6
2023-04-02 08:10:01,687:INFO:testStrategy:main.py:103:handleKline:185174: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': True, 'isOpenSell': False, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True, 'isCorr': False}

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=18394 

self.closeSec=1680394799, self.tradeDate='20230402', self.openTime='081000', self.closeTime='081959', self.symbol='BTCUSDT', self.open='28449.6', self.close='28467.7'
127.0.0.1 - - [02/Apr/2023 08:20:04] "POST / HTTP/1.1" 200 -
2023-04-02 08:20:10,234:INFO:testStrategy:main.py:101:handleKline:185174: self.closeSec=1680394799, self.tradeDate='20230402', self.openTime='081000', self.closeTime='081959',self.symbol='BTCUSDT',self.open='28449.6', self.close='28467.7'
2023-04-02 08:20:10,570:INFO:testStrategy:main.py:102:handleKline:185174: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
12141  20230402   073000    073959  1680392399  28487.9  28463.1
12142  20230402   074000    074959  1680392999  28463.1  28461.9
12143  20230402   075000    075959  1680393599  28461.9  28443.8
12144  20230402   080000    080959  1680394199  28443.7  28449.6
12145  20230402   081000    081959  1680394799  28449.6  28467.7
2023-04-02 08:20:10,571:INFO:testStrategy:main.py:103:handleKline:185174: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': True, 'isOpenSell': False, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True, 'isCorr': False}


## /root/FIL/strategy/sr_min/log.txt ----- -----

--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=0, self.total=1000000.0, self.flagDict['side']='', self.tradeCount=0, self.count=32218
self.closeSec=1680394799, self.tradeDate='20230402', self.openTime='081500', self.closeTime='081959', self.symbol='BTCUSDT', self.open=28458.4, self.close=28467.8, self.high=28487.8, self.low=28458.4, self.vol=523.516, self.amt=14908025.2022 
127.0.0.1 - - [02/Apr/2023 08:20:02] "POST / HTTP/1.1" 200 -
2023-04-02 08:20:07,740:INFO:sr_min:main.py:172:handleKline:449472: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5855  20230402   075500    075959  ...         0.0        0.0       0
5856  20230402   080000    080459  ...         0.0        0.0       0
5857  20230402   080500    080959  ...         0.0        0.0       0
5858  20230402   081000    081459  ...         0.0        0.0       0
5859  20230402   081500    081959  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-04-02 08:20:07,772:INFO:sr_min:main.py:175:handleKline:449472: self.closeSec=1680394799, self.tradeDate='20230402', self.openTime='081500', self.closeTime='081959',self.symbol='BTCUSDT',self.open=28458.4, self.close=28467.8, self.high=28487.8, self.low=28458.4, self.vol=523.516, self.amt=14908025.2022, ukdf['pct'].iloc[-1]=0.00033 , ukdf['amount'].iloc[-1]=14908025.2022, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5859, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': []}
type(curSign)=<class 'int'>, curSign=0, self.sign=0
--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=0, self.total=1000000.0, self.flagDict['side']='', self.tradeCount=0, self.count=32219
self.closeSec=1680395099, self.tradeDate='20230402', self.openTime='082000', self.closeTime='082459', self.symbol='BTCUSDT', self.open=28467.7, self.close=28449.6, self.high=28467.8, self.low=28444.4, self.vol=497.429, self.amt=14152067.9159 
127.0.0.1 - - [02/Apr/2023 08:25:01] "POST / HTTP/1.1" 200 -
2023-04-02 08:25:01,615:INFO:sr_min:main.py:172:handleKline:449472: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5856  20230402   080000    080459  ...         0.0        0.0       0
5857  20230402   080500    080959  ...         0.0        0.0       0
5858  20230402   081000    081459  ...         0.0        0.0       0
5859  20230402   081500    081959  ...         0.0        0.0       0
5860  20230402   082000    082459  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-04-02 08:25:01,618:INFO:sr_min:main.py:175:handleKline:449472: self.closeSec=1680395099, self.tradeDate='20230402', self.openTime='082000', self.closeTime='082459',self.symbol='BTCUSDT',self.open=28467.7, self.close=28449.6, self.high=28467.8, self.low=28444.4, self.vol=497.429, self.amt=14152067.9159, ukdf['pct'].iloc[-1]=-0.000639 , ukdf['amount'].iloc[-1]=14152067.9159, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5860, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': []}
type(curSign)=<class 'int'>, curSign=0, self.sign=0


## /root/FIL/strategy/s_rsrs/log.txt ----- -----

719  20230401   200000    235959  1680364799  ...    719  0.553578  0.328353     NaN
720  20230402   000000    035959  1680379199  ...    720  0.429529 -0.014972     NaN

[5 rows x 15 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '52.153', 'enterprice': '28496', 'countrevence': '0', 'unrealprofit': '-6610.96482355842', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '28369.23903086', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'numpy.int64'>, curSign=-9223372036854775808, self.sign=1
--handleKline--:  version='2.0.0', self.name='s_rsrs', self.symbol='BTCUSDT', interval='4h', intervalSec=14400, wid=25, thd=0.6, self.sign=1, self.total=1484665.736112, self.flagDict['side']='buy', self.tradeCount=28, self.count=766
self.closeSec=1680393599, self.tradeDate='20230402', self.openTime='040000', self.closeTime='075959', self.symbol='BTCUSDT', self.open=28368.4, self.close=28443.8, self.high=28575.0, self.low=28365.0, self.vol=36734.183, self.amt=1046074192.59686 
127.0.0.1 - - [02/Apr/2023 08:00:01] "POST / HTTP/1.1" 200 -
2023-04-02 08:00:01,790:INFO:s_rsrs:main.py:141:handleKline:185271: self.closeSec=1680393599, self.tradeDate='20230402', self.openTime='040000', self.closeTime='075959',self.symbol='BTCUSDT',self.open=28368.4, self.close=28443.8, self.high=28575.0, self.low=28365.0, self.vol=36734.183, self.amt=1046074192.59686 
2023-04-02 08:00:01,855:INFO:s_rsrs:main.py:142:handleKline:185271: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime  ...        vol           amt       pct
717  20230401   120000    155959  ...  46755.745  1.330723e+09 -0.004062
718  20230401   160000    195959  ...  28874.662  8.206232e+08 -0.001781
719  20230401   200000    235959  ...  49661.974  1.407624e+09  0.000765
720  20230402   000000    035959  ...  28679.320  8.133134e+08 -0.000666
721  20230402   040000    075959  ...  36734.183  1.046074e+09  0.002661

[5 rows x 11 columns]
2023-04-02 08:00:04,754:INFO:s_rsrs:main.py:151:handleKline:185271: df_s.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec  ...  index      beta    zscore  signal
717  20230401   120000    155959  1680335999  ...    717  0.730416  0.849276     1.0
718  20230401   160000    195959  1680350399  ...    718  0.624758  0.539265     NaN
719  20230401   200000    235959  1680364799  ...    719  0.553578  0.328353     NaN
720  20230402   000000    035959  1680379199  ...    720  0.429529 -0.014972     NaN
721  20230402   040000    075959  1680393599  ...    721  0.388136 -0.118582     NaN

[5 rows x 15 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '52.153', 'enterprice': '28496', 'countrevence': '0', 'unrealprofit': '-2722.3866', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '28443.8', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'numpy.int64'>, curSign=-9223372036854775808, self.sign=1


