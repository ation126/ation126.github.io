# 20230325 16:26:01

## /root/FIL/strategy/amihud/log.txt ----- -----

--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=993672.4896432, self.flagDict['side']='sell', self.tradeCount=2, self.count=34012
self.closeSec=1679732399, self.tradeDate='20230325', self.openTime='161500', self.closeTime='161959', self.symbol='BTCUSDT', self.open=27482.3, self.close=27466.2, self.high=27496.3, self.low=27463.0, self.vol=508.519, self.amt=13974256.7769 
127.0.0.1 - - [25/Mar/2023 16:20:04] "POST / HTTP/1.1" 200 -
2023-03-25 16:20:08,602:INFO:amihud:main.py:172:handleKline:200676: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5951  20230325   155500    155959  ...         0.0        0.0       0
5952  20230325   160000    160459  ...         0.0        0.0       0
5953  20230325   160500    160959  ...         0.0        0.0       0
5954  20230325   161000    161459  ...         0.0        0.0       0
5955  20230325   161500    161959  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-03-25 16:20:08,613:INFO:amihud:main.py:175:handleKline:200676: self.closeSec=1679732399, self.tradeDate='20230325', self.openTime='161500', self.closeTime='161959',self.symbol='BTCUSDT',self.open=27482.3, self.close=27466.2, self.high=27496.3, self.low=27463.0, self.vol=508.519, self.amt=13974256.7769, ukdf['pct'].iloc[-1]=-0.000582 , ukdf['amount'].iloc[-1]=13974256.7769, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5955, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '60.176', 'enterprice': '16529.3', 'countrevence': '0', 'unrealprofit': '-658230.36963516496', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '27467.72012821', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1
127.0.0.1 - - [25/Mar/2023 16:25:01] "POST / HTTP/1.1" 200 -
--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=993672.4896432, self.flagDict['side']='sell', self.tradeCount=2, self.count=34013
self.closeSec=1679732699, self.tradeDate='20230325', self.openTime='162000', self.closeTime='162459', self.symbol='BTCUSDT', self.open=27466.3, self.close=27434.2, self.high=27469.5, self.low=27434.2, self.vol=800.024, self.amt=21959814.273 
2023-03-25 16:25:01,614:INFO:amihud:main.py:172:handleKline:200676: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5952  20230325   160000    160459  ...         0.0        0.0       0
5953  20230325   160500    160959  ...         0.0        0.0       0
5954  20230325   161000    161459  ...         0.0        0.0       0
5955  20230325   161500    161959  ...         0.0        0.0       0
5956  20230325   162000    162459  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-03-25 16:25:01,615:INFO:amihud:main.py:175:handleKline:200676: self.closeSec=1679732699, self.tradeDate='20230325', self.openTime='162000', self.closeTime='162459',self.symbol='BTCUSDT',self.open=27466.3, self.close=27434.2, self.high=27469.5, self.low=27434.2, self.vol=800.024, self.amt=21959814.273, ukdf['pct'].iloc[-1]=-0.001165 , ukdf['amount'].iloc[-1]=21959814.273, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5956, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '60.176', 'enterprice': '16529.3', 'countrevence': '0', 'unrealprofit': '-656359.08067739808', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '27436.62319658', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1


## /root/FIL/strategy/factorcheck/log.txt ----- -----


self.closeSec=1679732399, self.tradeDate='20230325', self.openTime='161500', self.closeTime='161959', self.symbol='BTCUSDT', self.open=27482.3, self.close=27466.2, self.high=27496.3, self.low=27463.0 
127.0.0.1 - - [25/Mar/2023 16:20:03] "POST / HTTP/1.1" 200 -
2023-03-25 16:20:06,712:INFO:factorcheck2:main.py:126:handleKline:185239: self.closeSec=1679732399, self.tradeDate='20230325', self.openTime='161500', self.closeTime='161959',self.symbol='BTCUSDT',self.open=27482.3, self.close=27466.2, self.high=27496.3, self.low=27463.0   
2023-03-25 16:20:07,603:INFO:factorcheck2:main.py:127:handleKline:185239: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime    closeSec  ...      low       pct  index  idx
1631  20230325   155500    155959  1679731199  ...  27464.2 -0.000746   1631    5
1632  20230325   160000    160459  1679731499  ...  27438.0 -0.000364   1632    0
1633  20230325   160500    160959  1679731799  ...  27463.4  0.000557   1633    1
1634  20230325   161000    161459  1679732099  ...  27478.8  0.000124   1634    2
1635  20230325   161500    161959  1679732399  ...  27463.0 -0.000582   1635    3

[5 rows x 11 columns]
2023-03-25 16:20:07,603:INFO:factorcheck2:main.py:128:handleKline:185239: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=380, self.factor=0.5625630265134252, self.count=34579 

self.closeSec=1679732699, self.tradeDate='20230325', self.openTime='162000', self.closeTime='162459', self.symbol='BTCUSDT', self.open=27466.3, self.close=27434.2, self.high=27469.5, self.low=27434.2 
127.0.0.1 - - [25/Mar/2023 16:25:01] "POST / HTTP/1.1" 200 -
2023-03-25 16:25:01,571:INFO:factorcheck2:main.py:126:handleKline:185239: self.closeSec=1679732699, self.tradeDate='20230325', self.openTime='162000', self.closeTime='162459',self.symbol='BTCUSDT',self.open=27466.3, self.close=27434.2, self.high=27469.5, self.low=27434.2   
2023-03-25 16:25:01,602:INFO:factorcheck2:main.py:127:handleKline:185239: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime    closeSec  ...      low       pct  index  idx
1632  20230325   160000    160459  1679731499  ...  27438.0 -0.000364   1632    0
1633  20230325   160500    160959  1679731799  ...  27463.4  0.000557   1633    1
1634  20230325   161000    161459  1679732099  ...  27478.8  0.000124   1634    2
1635  20230325   161500    161959  1679732399  ...  27463.0 -0.000582   1635    3
1636  20230325   162000    162459  1679732699  ...  27434.2 -0.001165   1636    4

[5 rows x 11 columns]
2023-03-25 16:25:01,602:INFO:factorcheck2:main.py:128:handleKline:185239: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}


## /root/FIL/strategy/logic/log.txt ----- -----

2023-03-25 16:00:39,706:DEBUG:logic:main.py:463:getModel:885513: df_s.iloc[-5:,:] :
          date closeTime     open  ...    alpha58   alpha67   alpha72
5786  20230325    132959  27524.9  ...  50.833333  0.468130  0.577202
5787  20230325    135959  27506.5  ...  50.416667  0.462460  0.580281
5788  20230325    142959  27449.5  ...  50.416667  0.464743  0.582150
5789  20230325    145959  27469.2  ...  50.416667  0.466136  0.583288
5790  20230325    152959  27480.9  ...  50.416667  0.471605  0.581992

[5 rows x 33 columns]
0.5239852398523985
acc is : 0.5239852398523985
2023-03-25 16:00:39,896:INFO:logic:main.py:468:getModel:885513: df_pred.iloc[-5:,:] :
     pred    prob_0    prob_1  actual  ...       nav  sign  cost_        bm
537     0  0.527841  0.472159       0  ...  0.937866   1.0    0.0  1.135567
538     0  0.512584  0.487416       1  ...  0.938536   1.0    0.0  1.136378
539     0  0.537228  0.462772       1  ...  0.938939   1.0    0.0  1.136866
540     0  0.533128  0.466872       1  ...  0.940511   1.0    0.0  1.138769
541     0  0.552530  0.447470       0  ...  0.938683   1.0    0.0  1.136555

[5 rows x 10 columns]
2023-03-25 16:00:39,936:INFO:logic:main.py:478:getModel:885513: df_panel.iloc[-5:,:] :
    pred    prob_0    prob_1  actual  ...       nav  sign  cost_        bm
45     0  0.527596  0.472404       0  ...  0.971818   1.0    0.0  1.133527
46     0  0.512194  0.487806       1  ...  0.977639   1.0    0.0  1.141985
47     0  0.536177  0.463823       1  ...  0.969439   1.0    0.0  1.139444
48     0  0.532955  0.467045       1  ...  0.971062   1.0    0.0  1.140859
49     0  0.552530  0.447470       0  ...  0.938683   1.0    0.0  1.136555

[5 rows x 10 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': []}


## /root/FIL/strategy/modifiedmom/log.txt ----- -----

527  20230325   155000    155959  1679731199  27521.4  27473.5 -0.001740
2023-03-25 16:00:01,929:INFO:modifiedmom:main.py:146:handleKline:185213: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': True, 'isOpenSell': False, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True}
127.0.0.1 - - [25/Mar/2023 16:10:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=17288 

self.closeSec=1679731799, self.tradeDate='20230325', self.openTime='160000', self.closeTime='160959', self.symbol='BTCUSDT', self.open='27473.5', self.close='27478.8'
2023-03-25 16:10:01,595:INFO:modifiedmom:main.py:144:handleKline:185213: self.closeSec=1679731799, self.tradeDate='20230325', self.openTime='160000', self.closeTime='160959',self.symbol='BTCUSDT',self.open='27473.5', self.close='27478.8'
2023-03-25 16:10:01,631:INFO:modifiedmom:main.py:145:handleKline:185213: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec     open    close       pct
524  20230325   152000    152959  1679729399  27491.9    27527  0.001280
525  20230325   153000    153959  1679729999  27527.8  27534.9  0.000287
526  20230325   154000    154959  1679730599  27534.8  27521.4 -0.000490
527  20230325   155000    155959  1679731199  27521.4  27473.5 -0.001740
528  20230325   160000    160959  1679731799  27473.5  27478.8  0.000193
2023-03-25 16:10:01,631:INFO:modifiedmom:main.py:146:handleKline:185213: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': True, 'isOpenSell': False, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True}

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=17289 

self.closeSec=1679732399, self.tradeDate='20230325', self.openTime='161000', self.closeTime='161959', self.symbol='BTCUSDT', self.open='27478.8', self.close='27466.2'
127.0.0.1 - - [25/Mar/2023 16:20:04] "POST / HTTP/1.1" 200 -
2023-03-25 16:20:07,422:INFO:modifiedmom:main.py:144:handleKline:185213: self.closeSec=1679732399, self.tradeDate='20230325', self.openTime='161000', self.closeTime='161959',self.symbol='BTCUSDT',self.open='27478.8', self.close='27466.2'
2023-03-25 16:20:08,183:INFO:modifiedmom:main.py:145:handleKline:185213: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec     open    close       pct
525  20230325   153000    153959  1679729999  27527.8  27534.9  0.000287
526  20230325   154000    154959  1679730599  27534.8  27521.4 -0.000490
527  20230325   155000    155959  1679731199  27521.4  27473.5 -0.001740
528  20230325   160000    160959  1679731799  27473.5  27478.8  0.000193
529  20230325   161000    161959  1679732399  27478.8  27466.2 -0.000459
2023-03-25 16:20:08,192:INFO:modifiedmom:main.py:146:handleKline:185213: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': True, 'isOpenSell': False, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True}


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

17519  20230325   155000    155959  1679731199  27521.4  27473.5
2023-03-25 16:00:01,985:INFO:pyemd2:main.py:127:handleKline:185189: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=17289 

self.closeSec=1679731799, self.tradeDate='20230325', self.openTime='160000', self.closeTime='160959', self.symbol='BTCUSDT', self.open='27473.5', self.close='27478.8'
2023-03-25 16:10:01,606:INFO:pyemd2:main.py:125:handleKline:185189: self.closeSec=1679731799, self.tradeDate='20230325', self.openTime='160000', self.closeTime='160959',self.symbol='BTCUSDT',self.open='27473.5', self.close='27478.8'
127.0.0.1 - - [25/Mar/2023 16:10:01] "POST / HTTP/1.1" 200 -
2023-03-25 16:10:01,656:INFO:pyemd2:main.py:126:handleKline:185189: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
17516  20230325   152000    152959  1679729399  27491.9    27527
17517  20230325   153000    153959  1679729999  27527.8  27534.9
17518  20230325   154000    154959  1679730599  27534.8  27521.4
17519  20230325   155000    155959  1679731199  27521.4  27473.5
17520  20230325   160000    160959  1679731799  27473.5  27478.8
2023-03-25 16:10:01,656:INFO:pyemd2:main.py:127:handleKline:185189: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=17290 

self.closeSec=1679732399, self.tradeDate='20230325', self.openTime='161000', self.closeTime='161959', self.symbol='BTCUSDT', self.open='27478.8', self.close='27466.2'
127.0.0.1 - - [25/Mar/2023 16:20:04] "POST / HTTP/1.1" 200 -
2023-03-25 16:20:10,354:INFO:pyemd2:main.py:125:handleKline:185189: self.closeSec=1679732399, self.tradeDate='20230325', self.openTime='161000', self.closeTime='161959',self.symbol='BTCUSDT',self.open='27478.8', self.close='27466.2'
2023-03-25 16:20:10,494:INFO:pyemd2:main.py:126:handleKline:185189: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
17517  20230325   153000    153959  1679729999  27527.8  27534.9
17518  20230325   154000    154959  1679730599  27534.8  27521.4
17519  20230325   155000    155959  1679731199  27521.4  27473.5
17520  20230325   160000    160959  1679731799  27473.5  27478.8
17521  20230325   161000    161959  1679732399  27478.8  27466.2
2023-03-25 16:20:10,495:INFO:pyemd2:main.py:127:handleKline:185189: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}


## /root/FIL/strategy/similarity/log.txt ----- -----

12191  20230325   155000    155959  1679731199  27521.4  27473.5
2023-03-25 16:00:01,981:INFO:testStrategy:main.py:103:handleKline:185174: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': True, 'isOpenSell': False, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True, 'isCorr': False}
127.0.0.1 - - [25/Mar/2023 16:10:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=17289 

self.closeSec=1679731799, self.tradeDate='20230325', self.openTime='160000', self.closeTime='160959', self.symbol='BTCUSDT', self.open='27473.5', self.close='27478.8'
2023-03-25 16:10:01,605:INFO:testStrategy:main.py:101:handleKline:185174: self.closeSec=1679731799, self.tradeDate='20230325', self.openTime='160000', self.closeTime='160959',self.symbol='BTCUSDT',self.open='27473.5', self.close='27478.8'
2023-03-25 16:10:01,646:INFO:testStrategy:main.py:102:handleKline:185174: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
12188  20230325   152000    152959  1679729399  27491.9    27527
12189  20230325   153000    153959  1679729999  27527.8  27534.9
12190  20230325   154000    154959  1679730599  27534.8  27521.4
12191  20230325   155000    155959  1679731199  27521.4  27473.5
12192  20230325   160000    160959  1679731799  27473.5  27478.8
2023-03-25 16:10:01,647:INFO:testStrategy:main.py:103:handleKline:185174: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': True, 'isOpenSell': False, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True, 'isCorr': False}

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=17290 

self.closeSec=1679732399, self.tradeDate='20230325', self.openTime='161000', self.closeTime='161959', self.symbol='BTCUSDT', self.open='27478.8', self.close='27466.2'
127.0.0.1 - - [25/Mar/2023 16:20:04] "POST / HTTP/1.1" 200 -
2023-03-25 16:20:09,812:INFO:testStrategy:main.py:101:handleKline:185174: self.closeSec=1679732399, self.tradeDate='20230325', self.openTime='161000', self.closeTime='161959',self.symbol='BTCUSDT',self.open='27478.8', self.close='27466.2'
2023-03-25 16:20:10,136:INFO:testStrategy:main.py:102:handleKline:185174: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
12189  20230325   153000    153959  1679729999  27527.8  27534.9
12190  20230325   154000    154959  1679730599  27534.8  27521.4
12191  20230325   155000    155959  1679731199  27521.4  27473.5
12192  20230325   160000    160959  1679731799  27473.5  27478.8
12193  20230325   161000    161959  1679732399  27478.8  27466.2
2023-03-25 16:20:10,142:INFO:testStrategy:main.py:103:handleKline:185174: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': True, 'isOpenSell': False, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True, 'isCorr': False}


## /root/FIL/strategy/sr_min/log.txt ----- -----

--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=0, self.total=1000000.0, self.flagDict['side']='', self.tradeCount=0, self.count=30010
self.closeSec=1679732399, self.tradeDate='20230325', self.openTime='161500', self.closeTime='161959', self.symbol='BTCUSDT', self.open=27482.3, self.close=27466.2, self.high=27496.3, self.low=27463.0, self.vol=508.519, self.amt=13974256.7769 
127.0.0.1 - - [25/Mar/2023 16:20:02] "POST / HTTP/1.1" 200 -
2023-03-25 16:20:04,994:INFO:sr_min:main.py:172:handleKline:449472: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5951  20230325   155500    155959  ...         0.0        0.0       0
5952  20230325   160000    160459  ...         0.0        0.0       0
5953  20230325   160500    160959  ...         0.0        0.0       0
5954  20230325   161000    161459  ...         0.0        0.0       0
5955  20230325   161500    161959  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-03-25 16:20:05,014:INFO:sr_min:main.py:175:handleKline:449472: self.closeSec=1679732399, self.tradeDate='20230325', self.openTime='161500', self.closeTime='161959',self.symbol='BTCUSDT',self.open=27482.3, self.close=27466.2, self.high=27496.3, self.low=27463.0, self.vol=508.519, self.amt=13974256.7769, ukdf['pct'].iloc[-1]=-0.000582 , ukdf['amount'].iloc[-1]=13974256.7769, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5955, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': []}
type(curSign)=<class 'int'>, curSign=0, self.sign=0
--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=0, self.total=1000000.0, self.flagDict['side']='', self.tradeCount=0, self.count=30011
self.closeSec=1679732699, self.tradeDate='20230325', self.openTime='162000', self.closeTime='162459', self.symbol='BTCUSDT', self.open=27466.3, self.close=27434.2, self.high=27469.5, self.low=27434.2, self.vol=800.024, self.amt=21959814.273 
127.0.0.1 - - [25/Mar/2023 16:25:01] "POST / HTTP/1.1" 200 -
2023-03-25 16:25:01,560:INFO:sr_min:main.py:172:handleKline:449472: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5952  20230325   160000    160459  ...         0.0        0.0       0
5953  20230325   160500    160959  ...         0.0        0.0       0
5954  20230325   161000    161459  ...         0.0        0.0       0
5955  20230325   161500    161959  ...         0.0        0.0       0
5956  20230325   162000    162459  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-03-25 16:25:01,560:INFO:sr_min:main.py:175:handleKline:449472: self.closeSec=1679732699, self.tradeDate='20230325', self.openTime='162000', self.closeTime='162459',self.symbol='BTCUSDT',self.open=27466.3, self.close=27434.2, self.high=27469.5, self.low=27434.2, self.vol=800.024, self.amt=21959814.273, ukdf['pct'].iloc[-1]=-0.001165 , ukdf['amount'].iloc[-1]=21959814.273, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5956, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': []}
type(curSign)=<class 'int'>, curSign=0, self.sign=0


## /root/FIL/strategy/s_rsrs/log.txt ----- -----

721  20230325   040000    075959  1679702399  ...    721  0.018761 -1.935128    -1.0
722  20230325   080000    115959  1679716799  ...    722  0.020811 -1.877930    -1.0

[5 rows x 15 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '53.706', 'enterprice': '28091.1', 'countrevence': '0', 'unrealprofit': '27911.0082', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '27571.4', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'numpy.int64'>, curSign=-1, self.sign=-1
127.0.0.1 - - [25/Mar/2023 16:00:01] "POST / HTTP/1.1" 200 -
--handleKline--:  version='2.0.0', self.name='s_rsrs', self.symbol='BTCUSDT', interval='4h', intervalSec=14400, wid=25, thd=0.6, self.sign=-1, self.total=1507151.9559834, self.flagDict['side']='sell', self.tradeCount=27, self.count=720
self.closeSec=1679731199, self.tradeDate='20230325', self.openTime='120000', self.closeTime='155959', self.symbol='BTCUSDT', self.open=27568.6, self.close=27473.5, self.high=27598.0, self.low=27360.0, self.vol=39018.021, self.amt=1072443518.4171 
2023-03-25 16:00:01,809:INFO:s_rsrs:main.py:141:handleKline:185271: self.closeSec=1679731199, self.tradeDate='20230325', self.openTime='120000', self.closeTime='155959',self.symbol='BTCUSDT',self.open=27568.6, self.close=27473.5, self.high=27598.0, self.low=27360.0, self.vol=39018.021, self.amt=1072443518.4171 
2023-03-25 16:00:01,842:INFO:s_rsrs:main.py:142:handleKline:185271: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime  ...         vol           amt       pct
719  20230324   200000    235959  ...  208669.320  5.828417e+09  0.015296
720  20230325   000000    035959  ...  128438.580  3.563114e+09 -0.006640
721  20230325   040000    075959  ...  124877.686  3.416321e+09 -0.013390
722  20230325   080000    115959  ...   42513.558  1.170165e+09  0.004727
723  20230325   120000    155959  ...   39018.021  1.072444e+09 -0.003450

[5 rows x 11 columns]
2023-03-25 16:00:05,102:INFO:s_rsrs:main.py:151:handleKline:185271: df_s.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec  ...  index      beta    zscore  signal
719  20230324   200000    235959  1679673599  ...    719  0.014419 -2.039357    -1.0
720  20230325   000000    035959  1679687999  ...    720  0.014771 -1.994090    -1.0
721  20230325   040000    075959  1679702399  ...    721  0.018761 -1.935128    -1.0
722  20230325   080000    115959  1679716799  ...    722  0.020811 -1.877930    -1.0
723  20230325   120000    155959  1679731199  ...    723  0.025766 -1.811750    -1.0

[5 rows x 15 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '53.706', 'enterprice': '28091.1', 'countrevence': '0', 'unrealprofit': '33276.2376', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '27471.5', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'numpy.int64'>, curSign=-1, self.sign=-1


