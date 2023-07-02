# 20230702 08:26:01

## /root/FIL/strategy/amihud/log.txt ----- -----

--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=373746.4768026, self.flagDict['side']='sell', self.tradeCount=2, self.count=14080
self.closeSec=1688257199, self.tradeDate='20230702', self.openTime='081500', self.closeTime='081959', self.symbol='BTCUSDT', self.open=30550.5, self.close=30565.6, self.high=30570.8, self.low=30547.3, self.vol=1145.106, self.amt=34987113.4004 
127.0.0.1 - - [02/Jul/2023 08:20:01] "POST / HTTP/1.1" 200 -
2023-07-02 08:20:07,550:INFO:amihud:main.py:172:handleKline:2219019: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5855  20230702   075500    075959  ...         0.0        0.0       0
5856  20230702   080000    080459  ...         0.0        0.0       0
5857  20230702   080500    080959  ...         0.0        0.0       0
5858  20230702   081000    081459  ...         0.0        0.0       0
5859  20230702   081500    081959  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-07-02 08:20:07,590:INFO:amihud:main.py:175:handleKline:2219019: self.closeSec=1688257199, self.tradeDate='20230702', self.openTime='081500', self.closeTime='081959',self.symbol='BTCUSDT',self.open=30550.5, self.close=30565.6, self.high=30570.8, self.low=30547.3, self.vol=1145.106, self.amt=34987113.4004, ukdf['pct'].iloc[-1]=0.000491 , ukdf['amount'].iloc[-1]=34987113.4004, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5859, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '13.926', 'enterprice': '26864.9', 'countrevence': '0', 'unrealprofit': '-51535.9482', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '30565.6', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1
127.0.0.1 - - [02/Jul/2023 08:25:00] "POST / HTTP/1.1" 200 -
--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=373746.4768026, self.flagDict['side']='sell', self.tradeCount=2, self.count=14081
self.closeSec=1688257499, self.tradeDate='20230702', self.openTime='082000', self.closeTime='082459', self.symbol='BTCUSDT', self.open=30565.6, self.close=30550.7, self.high=30565.6, self.low=30537.1, self.vol=689.918, self.amt=21076615.2698 
2023-07-02 08:25:00,852:INFO:amihud:main.py:172:handleKline:2219019: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5856  20230702   080000    080459  ...         0.0        0.0       0
5857  20230702   080500    080959  ...         0.0        0.0       0
5858  20230702   081000    081459  ...         0.0        0.0       0
5859  20230702   081500    081959  ...         0.0        0.0       0
5860  20230702   082000    082459  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-07-02 08:25:00,853:INFO:amihud:main.py:175:handleKline:2219019: self.closeSec=1688257499, self.tradeDate='20230702', self.openTime='082000', self.closeTime='082459',self.symbol='BTCUSDT',self.open=30565.6, self.close=30550.7, self.high=30565.6, self.low=30537.1, self.vol=689.918, self.amt=21076615.2698, ukdf['pct'].iloc[-1]=-0.000487 , ukdf['amount'].iloc[-1]=21076615.2698, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5860, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '13.926', 'enterprice': '26864.9', 'countrevence': '0', 'unrealprofit': '-51338.199', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '30551.4', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1


## /root/FIL/strategy/factorcheck/log.txt ----- -----


self.closeSec=1688257199, self.tradeDate='20230702', self.openTime='081500', self.closeTime='081959', self.symbol='BTCUSDT', self.open=30550.5, self.close=30565.6, self.high=30570.8, self.low=30547.3 
127.0.0.1 - - [02/Jul/2023 08:20:01] "POST / HTTP/1.1" 200 -
2023-07-02 08:20:04,971:INFO:factorcheck2:main.py:126:handleKline:2218005: self.closeSec=1688257199, self.tradeDate='20230702', self.openTime='081500', self.closeTime='081959',self.symbol='BTCUSDT',self.open=30550.5, self.close=30565.6, self.high=30570.8, self.low=30547.3   
2023-07-02 08:20:06,510:INFO:factorcheck2:main.py:127:handleKline:2218005: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime    closeSec  ...      low       pct  index  idx
1535  20230702   075500    075959  1688255999  ...  30573.5 -0.000190   1535    5
1536  20230702   080000    080459  1688256299  ...  30570.0 -0.000023   1536    0
1537  20230702   080500    080959  1688256599  ...  30564.2 -0.000098   1537    1
1538  20230702   081000    081459  1688256899  ...  30543.0 -0.000631   1538    2
1539  20230702   081500    081959  1688257199  ...  30547.3  0.000491   1539    3

[5 rows x 11 columns]
2023-07-02 08:20:06,520:INFO:factorcheck2:main.py:128:handleKline:2218005: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}
127.0.0.1 - - [02/Jul/2023 08:25:00] "POST / HTTP/1.1" 200 -

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=78, self.factor=0.32940380359623556, self.count=14083 

self.closeSec=1688257499, self.tradeDate='20230702', self.openTime='082000', self.closeTime='082459', self.symbol='BTCUSDT', self.open=30565.6, self.close=30550.7, self.high=30565.6, self.low=30537.1 
2023-07-02 08:25:00,759:INFO:factorcheck2:main.py:126:handleKline:2218005: self.closeSec=1688257499, self.tradeDate='20230702', self.openTime='082000', self.closeTime='082459',self.symbol='BTCUSDT',self.open=30565.6, self.close=30550.7, self.high=30565.6, self.low=30537.1   
2023-07-02 08:25:00,829:INFO:factorcheck2:main.py:127:handleKline:2218005: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime    closeSec  ...      low       pct  index  idx
1536  20230702   080000    080459  1688256299  ...  30570.0 -0.000023   1536    0
1537  20230702   080500    080959  1688256599  ...  30564.2 -0.000098   1537    1
1538  20230702   081000    081459  1688256899  ...  30543.0 -0.000631   1538    2
1539  20230702   081500    081959  1688257199  ...  30547.3  0.000491   1539    3
1540  20230702   082000    082459  1688257499  ...  30537.1 -0.000487   1540    4

[5 rows x 11 columns]
2023-07-02 08:25:00,829:INFO:factorcheck2:main.py:128:handleKline:2218005: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}


## /root/FIL/strategy/logic/log.txt ----- -----

2023-07-02 08:00:17,966:DEBUG:logic:main.py:463:getModel:2218526: df_s.iloc[-5:,:] :
          date closeTime     open  ...    alpha58   alpha67   alpha72
5770  20230702    052959  30577.8  ...  53.333333  0.517925  0.287701
5771  20230702    055959  30577.2  ...  53.333333  0.517330  0.285986
5772  20230702    062959  30574.7  ...  53.333333  0.521860  0.280612
5773  20230702    065959  30595.0  ...  52.916667  0.515578  0.280397
5774  20230702    072959  30569.2  ...  52.500000  0.515430  0.280309

[5 rows x 33 columns]
0.5157116451016636
acc is : 0.5157116451016636
2023-07-02 08:00:18,035:INFO:logic:main.py:468:getModel:2218526: df_pred.iloc[-5:,:] :
     pred    prob_0    prob_1  actual  ...       nav  sign  cost_        bm
536     0  0.525387  0.474613       0  ...  1.069146   1.0    0.0  1.116313
537     0  0.523778  0.476222       1  ...  1.069853   1.0    0.0  1.117051
538     0  0.528775  0.471225       0  ...  1.068954   1.0    0.0  1.116112
539     0  0.518400  0.481600       0  ...  1.068933   1.0    0.0  1.116090
540     0  0.520932  0.479068       1  ...  1.069108   1.0    0.0  1.116273

[5 rows x 10 columns]
2023-07-02 08:00:18,047:INFO:logic:main.py:478:getModel:2218526: df_panel.iloc[-5:,:] :
    pred    prob_0    prob_1  actual  ...       nav  sign  cost_        bm
45     0  0.525455  0.474545       0  ...  1.082361   1.0    0.0  1.130128
46     0  0.523814  0.476186       1  ...  1.077749   1.0    0.0  1.125309
47     0  0.528750  0.471250       0  ...  1.069849   1.0    0.0  1.117071
48     0  0.518400  0.481600       0  ...  1.068933   1.0    0.0  1.116090
49     0  0.520932  0.479068       1  ...  1.069108   1.0    0.0  1.116273

[5 rows x 10 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '25.53', 'enterprice': '30560', 'countrevence': '0', 'unrealprofit': '416.0993148915', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '30576.29844555', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}


## /root/FIL/strategy/modifiedmom/log.txt ----- -----

623  20230702   075000    075959  1688255999  30562.9  30573.6  0.000350
2023-07-02 08:00:02,085:INFO:modifiedmom:main.py:146:handleKline:2218259: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': True, 'isOpen': False, 'isClose': True, 'isTrig': False}
127.0.0.1 - - [02/Jul/2023 08:10:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=7040 

self.closeSec=1688256599, self.tradeDate='20230702', self.openTime='080000', self.closeTime='080959', self.symbol='BTCUSDT', self.open='30573.6', self.close='30569.9'
2023-07-02 08:10:01,082:INFO:modifiedmom:main.py:144:handleKline:2218259: self.closeSec=1688256599, self.tradeDate='20230702', self.openTime='080000', self.closeTime='080959',self.symbol='BTCUSDT',self.open='30573.6', self.close='30569.9'
2023-07-02 08:10:01,089:INFO:modifiedmom:main.py:145:handleKline:2218259: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec     open    close       pct
620  20230702   072000    072959  1688254199  30562.4  30568.6  0.000200
621  20230702   073000    073959  1688254799  30568.6  30569.6  0.000033
622  20230702   074000    074959  1688255399  30569.5  30562.9 -0.000219
623  20230702   075000    075959  1688255999  30562.9  30573.6  0.000350
624  20230702   080000    080959  1688256599  30573.6  30569.9 -0.000121
2023-07-02 08:10:01,089:INFO:modifiedmom:main.py:146:handleKline:2218259: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': True, 'isOpen': False, 'isClose': True, 'isTrig': False}

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=7041 

self.closeSec=1688257199, self.tradeDate='20230702', self.openTime='081000', self.closeTime='081959', self.symbol='BTCUSDT', self.open='30569.9', self.close='30565.6'
127.0.0.1 - - [02/Jul/2023 08:20:04] "POST / HTTP/1.1" 200 -
2023-07-02 08:20:07,451:INFO:modifiedmom:main.py:144:handleKline:2218259: self.closeSec=1688257199, self.tradeDate='20230702', self.openTime='081000', self.closeTime='081959',self.symbol='BTCUSDT',self.open='30569.9', self.close='30565.6'
2023-07-02 08:20:08,400:INFO:modifiedmom:main.py:145:handleKline:2218259: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec     open    close       pct
621  20230702   073000    073959  1688254799  30568.6  30569.6  0.000033
622  20230702   074000    074959  1688255399  30569.5  30562.9 -0.000219
623  20230702   075000    075959  1688255999  30562.9  30573.6  0.000350
624  20230702   080000    080959  1688256599  30573.6  30569.9 -0.000121
625  20230702   081000    081959  1688257199  30569.9  30565.6 -0.000141
2023-07-02 08:20:08,410:INFO:modifiedmom:main.py:146:handleKline:2218259: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': True, 'isOpen': False, 'isClose': True, 'isTrig': False}


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

17471  20230702   075000    075959  1688255999  30562.9  30573.6
2023-07-02 08:00:02,138:INFO:pyemd2:main.py:127:handleKline:2217508: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=7043 

self.closeSec=1688256599, self.tradeDate='20230702', self.openTime='080000', self.closeTime='080959', self.symbol='BTCUSDT', self.open='30573.6', self.close='30569.9'
2023-07-02 08:10:01,076:INFO:pyemd2:main.py:125:handleKline:2217508: self.closeSec=1688256599, self.tradeDate='20230702', self.openTime='080000', self.closeTime='080959',self.symbol='BTCUSDT',self.open='30573.6', self.close='30569.9'
127.0.0.1 - - [02/Jul/2023 08:10:01] "POST / HTTP/1.1" 200 -
2023-07-02 08:10:01,091:INFO:pyemd2:main.py:126:handleKline:2217508: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
17468  20230702   072000    072959  1688254199  30562.4  30568.6
17469  20230702   073000    073959  1688254799  30568.6  30569.6
17470  20230702   074000    074959  1688255399  30569.5  30562.9
17471  20230702   075000    075959  1688255999  30562.9  30573.6
17472  20230702   080000    080959  1688256599  30573.6  30569.9
2023-07-02 08:10:01,091:INFO:pyemd2:main.py:127:handleKline:2217508: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=7044 

self.closeSec=1688257199, self.tradeDate='20230702', self.openTime='081000', self.closeTime='081959', self.symbol='BTCUSDT', self.open='30569.9', self.close='30565.6'
127.0.0.1 - - [02/Jul/2023 08:20:04] "POST / HTTP/1.1" 200 -
2023-07-02 08:20:09,781:INFO:pyemd2:main.py:125:handleKline:2217508: self.closeSec=1688257199, self.tradeDate='20230702', self.openTime='081000', self.closeTime='081959',self.symbol='BTCUSDT',self.open='30569.9', self.close='30565.6'
2023-07-02 08:20:09,920:INFO:pyemd2:main.py:126:handleKline:2217508: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
17469  20230702   073000    073959  1688254799  30568.6  30569.6
17470  20230702   074000    074959  1688255399  30569.5  30562.9
17471  20230702   075000    075959  1688255999  30562.9  30573.6
17472  20230702   080000    080959  1688256599  30573.6  30569.9
17473  20230702   081000    081959  1688257199  30569.9  30565.6
2023-07-02 08:20:09,921:INFO:pyemd2:main.py:127:handleKline:2217508: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}


## /root/FIL/strategy/similarity/log.txt ----- -----

12143  20230702   075000    075959  1688255999  30562.9  30573.6
2023-07-02 08:00:02,148:INFO:testStrategy:main.py:103:handleKline:2217133: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': True, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True, 'isCorr': False}

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=7043 

self.closeSec=1688256599, self.tradeDate='20230702', self.openTime='080000', self.closeTime='080959', self.symbol='BTCUSDT', self.open='30573.6', self.close='30569.9'
2023-07-02 08:10:01,067:INFO:testStrategy:main.py:101:handleKline:2217133: self.closeSec=1688256599, self.tradeDate='20230702', self.openTime='080000', self.closeTime='080959',self.symbol='BTCUSDT',self.open='30573.6', self.close='30569.9'
127.0.0.1 - - [02/Jul/2023 08:10:01] "POST / HTTP/1.1" 200 -
2023-07-02 08:10:01,073:INFO:testStrategy:main.py:102:handleKline:2217133: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
12140  20230702   072000    072959  1688254199  30562.4  30568.6
12141  20230702   073000    073959  1688254799  30568.6  30569.6
12142  20230702   074000    074959  1688255399  30569.5  30562.9
12143  20230702   075000    075959  1688255999  30562.9  30573.6
12144  20230702   080000    080959  1688256599  30573.6  30569.9
2023-07-02 08:10:01,074:INFO:testStrategy:main.py:103:handleKline:2217133: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': True, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True, 'isCorr': False}

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=7044 

self.closeSec=1688257199, self.tradeDate='20230702', self.openTime='081000', self.closeTime='081959', self.symbol='BTCUSDT', self.open='30569.9', self.close='30565.6'
127.0.0.1 - - [02/Jul/2023 08:20:04] "POST / HTTP/1.1" 200 -
2023-07-02 08:20:09,262:INFO:testStrategy:main.py:101:handleKline:2217133: self.closeSec=1688257199, self.tradeDate='20230702', self.openTime='081000', self.closeTime='081959',self.symbol='BTCUSDT',self.open='30569.9', self.close='30565.6'
2023-07-02 08:20:09,630:INFO:testStrategy:main.py:102:handleKline:2217133: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
12141  20230702   073000    073959  1688254799  30568.6  30569.6
12142  20230702   074000    074959  1688255399  30569.5  30562.9
12143  20230702   075000    075959  1688255999  30562.9  30573.6
12144  20230702   080000    080959  1688256599  30573.6  30569.9
12145  20230702   081000    081959  1688257199  30569.9  30565.6
2023-07-02 08:20:09,632:INFO:testStrategy:main.py:103:handleKline:2217133: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': True, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True, 'isCorr': False}


## /root/FIL/strategy/sr_min/log.txt ----- -----

--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=1, self.total=996015.990996, self.flagDict['side']='buy', self.tradeCount=1, self.count=14080
self.closeSec=1688257199, self.tradeDate='20230702', self.openTime='081500', self.closeTime='081959', self.symbol='BTCUSDT', self.open=30550.5, self.close=30565.6, self.high=30570.8, self.low=30547.3, self.vol=1145.106, self.amt=34987113.4004 
127.0.0.1 - - [02/Jul/2023 08:20:01] "POST / HTTP/1.1" 200 -
2023-07-02 08:20:07,550:INFO:sr_min:main.py:172:handleKline:2219263: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5855  20230702   075500    075959  ...         0.0        0.0       0
5856  20230702   080000    080459  ...         0.0        0.0       0
5857  20230702   080500    080959  ...         0.0        0.0       0
5858  20230702   081000    081459  ...         0.0        0.0       0
5859  20230702   081500    081959  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-07-02 08:20:07,591:INFO:sr_min:main.py:175:handleKline:2219263: self.closeSec=1688257199, self.tradeDate='20230702', self.openTime='081500', self.closeTime='081959',self.symbol='BTCUSDT',self.open=30550.5, self.close=30565.6, self.high=30570.8, self.low=30547.3, self.vol=1145.106, self.amt=34987113.4004, ukdf['pct'].iloc[-1]=0.000491 , ukdf['amount'].iloc[-1]=34987113.4004, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5859, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '37.141', 'enterprice': '26844', 'countrevence': '0', 'unrealprofit': '138223.9456', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '30565.6', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=1
127.0.0.1 - - [02/Jul/2023 08:25:00] "POST / HTTP/1.1" 200 -
--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=1, self.total=996015.990996, self.flagDict['side']='buy', self.tradeCount=1, self.count=14081
self.closeSec=1688257499, self.tradeDate='20230702', self.openTime='082000', self.closeTime='082459', self.symbol='BTCUSDT', self.open=30565.6, self.close=30550.7, self.high=30565.6, self.low=30537.1, self.vol=689.918, self.amt=21076615.2698 
2023-07-02 08:25:00,852:INFO:sr_min:main.py:172:handleKline:2219263: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5856  20230702   080000    080459  ...         0.0        0.0       0
5857  20230702   080500    080959  ...         0.0        0.0       0
5858  20230702   081000    081459  ...         0.0        0.0       0
5859  20230702   081500    081959  ...         0.0        0.0       0
5860  20230702   082000    082459  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-07-02 08:25:00,853:INFO:sr_min:main.py:175:handleKline:2219263: self.closeSec=1688257499, self.tradeDate='20230702', self.openTime='082000', self.closeTime='082459',self.symbol='BTCUSDT',self.open=30565.6, self.close=30550.7, self.high=30565.6, self.low=30537.1, self.vol=689.918, self.amt=21076615.2698, ukdf['pct'].iloc[-1]=-0.000487 , ukdf['amount'].iloc[-1]=21076615.2698, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5860, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '37.141', 'enterprice': '26844', 'countrevence': '0', 'unrealprofit': '137696.5434', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '30551.4', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=1


## /root/FIL/strategy/s_rsrs/log.txt ----- -----

719  20230701   200000    235959  1688227199  ...    719  0.008270 -1.421216    -1.0
720  20230702   000000    035959  1688241599  ...    720  0.005554 -1.402073    -1.0

[5 rows x 15 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '53.268', 'enterprice': '30707', 'countrevence': '0', 'unrealprofit': '5521.5416475558', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '30603.34411565', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'numpy.int64'>, curSign=-1, self.sign=-1
--handleKline--:  version='2.0.0', self.name='s_rsrs', self.symbol='BTCUSDT', interval='4h', intervalSec=14400, wid=25, thd=0.6, self.sign=-1, self.total=1634064.775524, self.flagDict['side']='sell', self.tradeCount=8, self.count=293
self.closeSec=1688255999, self.tradeDate='20230702', self.openTime='040000', self.closeTime='075959', self.symbol='BTCUSDT', self.open=30600.5, self.close=30573.6, self.high=30605.1, self.low=30534.3, self.vol=9534.474, self.amt=291514947.1697 
127.0.0.1 - - [02/Jul/2023 08:00:01] "POST / HTTP/1.1" 200 -
2023-07-02 08:00:01,653:INFO:s_rsrs:main.py:141:handleKline:2218689: self.closeSec=1688255999, self.tradeDate='20230702', self.openTime='040000', self.closeTime='075959',self.symbol='BTCUSDT',self.open=30600.5, self.close=30573.6, self.high=30605.1, self.low=30534.3, self.vol=9534.474, self.amt=291514947.1697 
2023-07-02 08:00:01,674:INFO:s_rsrs:main.py:142:handleKline:2218689: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime  ...        vol           amt       pct
717  20230701   120000    155959  ...  23531.509  7.153048e+08  0.001872
718  20230701   160000    195959  ...  23695.114  7.221367e+08  0.001984
719  20230701   200000    235959  ...  32888.967  1.005598e+09  0.001737
720  20230702   000000    035959  ...  16091.915  4.920571e+08  0.001276
721  20230702   040000    075959  ...   9534.474  2.915149e+08 -0.000879

[5 rows x 11 columns]
2023-07-02 08:00:02,877:INFO:s_rsrs:main.py:151:handleKline:2218689: df_s.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec  ...  index      beta    zscore  signal
717  20230701   120000    155959  1688198399  ...    717  0.011212 -1.469111    -1.0
718  20230701   160000    195959  1688212799  ...    718  0.009735 -1.443327    -1.0
719  20230701   200000    235959  1688227199  ...    719  0.008270 -1.421216    -1.0
720  20230702   000000    035959  1688241599  ...    720  0.005554 -1.402073    -1.0
721  20230702   040000    075959  1688255999  ...    721  0.003916 -1.380020    -1.0

[5 rows x 15 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '53.268', 'enterprice': '30707', 'countrevence': '0', 'unrealprofit': '7044.73736585184', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '30574.74916712', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'numpy.int64'>, curSign=-1, self.sign=-1


