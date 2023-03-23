# 20230323 16:26:01

## /root/FIL/strategy/amihud/log.txt ----- -----

--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=993672.4896432, self.flagDict['side']='sell', self.tradeCount=2, self.count=33436
self.closeSec=1679559599, self.tradeDate='20230323', self.openTime='161500', self.closeTime='161959', self.symbol='BTCUSDT', self.open=27606.1, self.close=27597.5, self.high=27620.9, self.low=27571.4, self.vol=2125.882, self.amt=58663773.585 
127.0.0.1 - - [23/Mar/2023 16:20:04] "POST / HTTP/1.1" 200 -
2023-03-23 16:20:10,520:INFO:amihud:main.py:172:handleKline:200676: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5951  20230323   155500    155959  ...         0.0        0.0       0
5952  20230323   160000    160459  ...         0.0        0.0       0
5953  20230323   160500    160959  ...         0.0        0.0       0
5954  20230323   161000    161459  ...         0.0        0.0       0
5955  20230323   161500    161959  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-03-23 16:20:10,539:INFO:amihud:main.py:175:handleKline:200676: self.closeSec=1679559599, self.tradeDate='20230323', self.openTime='161500', self.closeTime='161959',self.symbol='BTCUSDT',self.open=27606.1, self.close=27597.5, self.high=27620.9, self.low=27571.4, self.vol=2125.882, self.amt=58663773.585, ukdf['pct'].iloc[-1]=-0.000312 , ukdf['amount'].iloc[-1]=58663773.585, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5955, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '60.176', 'enterprice': '16529.3', 'countrevence': '0', 'unrealprofit': '-666358.936', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '27602.8', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1
127.0.0.1 - - [23/Mar/2023 16:25:01] "POST / HTTP/1.1" 200 -
--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=993672.4896432, self.flagDict['side']='sell', self.tradeCount=2, self.count=33437
self.closeSec=1679559899, self.tradeDate='20230323', self.openTime='162000', self.closeTime='162459', self.symbol='BTCUSDT', self.open=27597.5, self.close=27570.9, self.high=27635.5, self.low=27567.1, self.vol=1850.204, self.amt=51072583.2112 
2023-03-23 16:25:01,591:INFO:amihud:main.py:172:handleKline:200676: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5952  20230323   160000    160459  ...         0.0        0.0       0
5953  20230323   160500    160959  ...         0.0        0.0       0
5954  20230323   161000    161459  ...         0.0        0.0       0
5955  20230323   161500    161959  ...         0.0        0.0       0
5956  20230323   162000    162459  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-03-23 16:25:01,592:INFO:amihud:main.py:175:handleKline:200676: self.closeSec=1679559899, self.tradeDate='20230323', self.openTime='162000', self.closeTime='162459',self.symbol='BTCUSDT',self.open=27597.5, self.close=27570.9, self.high=27635.5, self.low=27567.1, self.vol=1850.204, self.amt=51072583.2112, ukdf['pct'].iloc[-1]=-0.000964 , ukdf['amount'].iloc[-1]=51072583.2112, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5956, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '60.176', 'enterprice': '16529.3', 'countrevence': '0', 'unrealprofit': '-664445.3392', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '27571', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1


## /root/FIL/strategy/factorcheck/log.txt ----- -----


self.closeSec=1679559599, self.tradeDate='20230323', self.openTime='161500', self.closeTime='161959', self.symbol='BTCUSDT', self.open=27606.1, self.close=27597.5, self.high=27620.9, self.low=27571.4 
127.0.0.1 - - [23/Mar/2023 16:20:02] "POST / HTTP/1.1" 200 -
2023-03-23 16:20:06,440:INFO:factorcheck2:main.py:126:handleKline:185239: self.closeSec=1679559599, self.tradeDate='20230323', self.openTime='161500', self.closeTime='161959',self.symbol='BTCUSDT',self.open=27606.1, self.close=27597.5, self.high=27620.9, self.low=27571.4   
2023-03-23 16:20:08,220:INFO:factorcheck2:main.py:127:handleKline:185239: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime    closeSec  ...      low       pct  index  idx
1631  20230323   155500    155959  1679558399  ...  27589.3  0.000979   1631    5
1632  20230323   160000    160459  1679558699  ...  27611.8  0.000753   1632    0
1633  20230323   160500    160959  1679558999  ...  27623.1  0.001324   1633    1
1634  20230323   161000    161459  1679559299  ...  27606.0 -0.002446   1634    2
1635  20230323   161500    161959  1679559599  ...  27571.4 -0.000312   1635    3

[5 rows x 11 columns]
2023-03-23 16:20:08,220:INFO:factorcheck2:main.py:128:handleKline:185239: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}
127.0.0.1 - - [23/Mar/2023 16:25:01] "POST / HTTP/1.1" 200 -

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=284, self.factor=0.5073109304784047, self.count=34003 

self.closeSec=1679559899, self.tradeDate='20230323', self.openTime='162000', self.closeTime='162459', self.symbol='BTCUSDT', self.open=27597.5, self.close=27570.9, self.high=27635.5, self.low=27567.1 
2023-03-23 16:25:01,516:INFO:factorcheck2:main.py:126:handleKline:185239: self.closeSec=1679559899, self.tradeDate='20230323', self.openTime='162000', self.closeTime='162459',self.symbol='BTCUSDT',self.open=27597.5, self.close=27570.9, self.high=27635.5, self.low=27567.1   
2023-03-23 16:25:01,581:INFO:factorcheck2:main.py:127:handleKline:185239: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime    closeSec  ...      low       pct  index  idx
1632  20230323   160000    160459  1679558699  ...  27611.8  0.000753   1632    0
1633  20230323   160500    160959  1679558999  ...  27623.1  0.001324   1633    1
1634  20230323   161000    161459  1679559299  ...  27606.0 -0.002446   1634    2
1635  20230323   161500    161959  1679559599  ...  27571.4 -0.000312   1635    3
1636  20230323   162000    162459  1679559899  ...  27567.1 -0.000964   1636    4

[5 rows x 11 columns]
2023-03-23 16:25:01,581:INFO:factorcheck2:main.py:128:handleKline:185239: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}


## /root/FIL/strategy/logic/log.txt ----- -----

2023-03-23 16:00:33,904:DEBUG:logic:main.py:463:getModel:885513: df_s.iloc[-5:,:] :
          date closeTime     open  ...    alpha58   alpha67   alpha72
5786  20230323    132959  27262.5  ...  52.500000  0.461315  0.626212
5787  20230323    135959  27384.5  ...  52.500000  0.484023  0.621508
5788  20230323    142959  27608.0  ...  52.916667  0.486228  0.616469
5789  20230323    145959  27630.3  ...  52.916667  0.486489  0.611690
5790  20230323    152959  27633.0  ...  52.916667  0.481030  0.608885

[5 rows x 33 columns]
0.5239852398523985
acc is : 0.5239852398523985
2023-03-23 16:00:34,054:INFO:logic:main.py:468:getModel:885513: df_pred.iloc[-5:,:] :
     pred    prob_0    prob_1  actual  ...       nav  sign  cost_        bm
537     0  0.582674  0.417326       1  ...  1.236545   1.0    0.0  1.350381
538     0  0.637117  0.362883       1  ...  1.237544   1.0    0.0  1.351472
539     0  0.573440  0.426560       1  ...  1.237660   1.0    0.0  1.351599
540     0  0.563697  0.436303       0  ...  1.235112   1.0    0.0  1.348816
541     0  0.551816  0.448184       1  ...  1.236921   1.0    0.0  1.350792

[5 rows x 10 columns]
2023-03-23 16:00:34,092:INFO:logic:main.py:478:getModel:885513: df_panel.iloc[-5:,:] :
    pred    prob_0    prob_1  actual  ...       nav  sign  cost_        bm
45     0  0.582162  0.417838       1  ...  1.297293   1.0    0.0  1.358441
46     0  0.636819  0.363181       1  ...  1.271169   1.0    0.0  1.354745
47     0  0.573305  0.426695       1  ...  1.237660   1.0    0.0  1.351420
48     0  0.563465  0.436535       0  ...  1.252446   1.0    0.0  1.353616
49     0  0.551816  0.448184       1  ...  1.236921   1.0    0.0  1.350792

[5 rows x 10 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': []}


## /root/FIL/strategy/modifiedmom/log.txt ----- -----

527  20230323   155000    155959  1679558399  27589.1  27616.4  0.000990
2023-03-23 16:00:02,195:INFO:modifiedmom:main.py:146:handleKline:185213: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': True, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True}
127.0.0.1 - - [23/Mar/2023 16:10:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=17000 

self.closeSec=1679558999, self.tradeDate='20230323', self.openTime='160000', self.closeTime='160959', self.symbol='BTCUSDT', self.open='27616.3', self.close='27673.8'
2023-03-23 16:10:01,737:INFO:modifiedmom:main.py:144:handleKline:185213: self.closeSec=1679558999, self.tradeDate='20230323', self.openTime='160000', self.closeTime='160959',self.symbol='BTCUSDT',self.open='27616.3', self.close='27673.8'
2023-03-23 16:10:01,805:INFO:modifiedmom:main.py:145:handleKline:185213: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec     open    close       pct
524  20230323   152000    152959  1679556599  27591.8    27576 -0.000569
525  20230323   153000    153959  1679557199    27576  27622.5  0.001686
526  20230323   154000    154959  1679557799  27622.5  27589.1 -0.001209
527  20230323   155000    155959  1679558399  27589.1  27616.4  0.000990
528  20230323   160000    160959  1679558999  27616.3  27673.8  0.002078
2023-03-23 16:10:01,806:INFO:modifiedmom:main.py:146:handleKline:185213: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': True, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True}

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=17001 

self.closeSec=1679559599, self.tradeDate='20230323', self.openTime='161000', self.closeTime='161959', self.symbol='BTCUSDT', self.open='27673.9', self.close='27597.5'
127.0.0.1 - - [23/Mar/2023 16:20:04] "POST / HTTP/1.1" 200 -
2023-03-23 16:20:08,589:INFO:modifiedmom:main.py:144:handleKline:185213: self.closeSec=1679559599, self.tradeDate='20230323', self.openTime='161000', self.closeTime='161959',self.symbol='BTCUSDT',self.open='27673.9', self.close='27597.5'
2023-03-23 16:20:09,499:INFO:modifiedmom:main.py:145:handleKline:185213: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec     open    close       pct
525  20230323   153000    153959  1679557199    27576  27622.5  0.001686
526  20230323   154000    154959  1679557799  27622.5  27589.1 -0.001209
527  20230323   155000    155959  1679558399  27589.1  27616.4  0.000990
528  20230323   160000    160959  1679558999  27616.3  27673.8  0.002078
529  20230323   161000    161959  1679559599  27673.9  27597.5 -0.002757
2023-03-23 16:20:09,500:INFO:modifiedmom:main.py:146:handleKline:185213: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': True, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True}


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

17519  20230323   155000    155959  1679558399  27589.1  27616.4
2023-03-23 16:00:02,217:INFO:pyemd2:main.py:127:handleKline:185189: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}
127.0.0.1 - - [23/Mar/2023 16:10:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=17001 

self.closeSec=1679558999, self.tradeDate='20230323', self.openTime='160000', self.closeTime='160959', self.symbol='BTCUSDT', self.open='27616.3', self.close='27673.8'
2023-03-23 16:10:01,763:INFO:pyemd2:main.py:125:handleKline:185189: self.closeSec=1679558999, self.tradeDate='20230323', self.openTime='160000', self.closeTime='160959',self.symbol='BTCUSDT',self.open='27616.3', self.close='27673.8'
2023-03-23 16:10:01,811:INFO:pyemd2:main.py:126:handleKline:185189: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
17516  20230323   152000    152959  1679556599  27591.8    27576
17517  20230323   153000    153959  1679557199    27576  27622.5
17518  20230323   154000    154959  1679557799  27622.5  27589.1
17519  20230323   155000    155959  1679558399  27589.1  27616.4
17520  20230323   160000    160959  1679558999  27616.3  27673.8
2023-03-23 16:10:01,811:INFO:pyemd2:main.py:127:handleKline:185189: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=17002 

self.closeSec=1679559599, self.tradeDate='20230323', self.openTime='161000', self.closeTime='161959', self.symbol='BTCUSDT', self.open='27673.9', self.close='27597.5'
127.0.0.1 - - [23/Mar/2023 16:20:05] "POST / HTTP/1.1" 200 -
2023-03-23 16:20:12,113:INFO:pyemd2:main.py:125:handleKline:185189: self.closeSec=1679559599, self.tradeDate='20230323', self.openTime='161000', self.closeTime='161959',self.symbol='BTCUSDT',self.open='27673.9', self.close='27597.5'
2023-03-23 16:20:12,272:INFO:pyemd2:main.py:126:handleKline:185189: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
17517  20230323   153000    153959  1679557199    27576  27622.5
17518  20230323   154000    154959  1679557799  27622.5  27589.1
17519  20230323   155000    155959  1679558399  27589.1  27616.4
17520  20230323   160000    160959  1679558999  27616.3  27673.8
17521  20230323   161000    161959  1679559599  27673.9  27597.5
2023-03-23 16:20:12,273:INFO:pyemd2:main.py:127:handleKline:185189: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}


## /root/FIL/strategy/similarity/log.txt ----- -----

12191  20230323   155000    155959  1679558399  27589.1  27616.4
2023-03-23 16:00:02,184:INFO:testStrategy:main.py:103:handleKline:185174: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': True, 'isOpenSell': False, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True, 'isCorr': False}
127.0.0.1 - - [23/Mar/2023 16:10:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=17001 

self.closeSec=1679558999, self.tradeDate='20230323', self.openTime='160000', self.closeTime='160959', self.symbol='BTCUSDT', self.open='27616.3', self.close='27673.8'
2023-03-23 16:10:01,751:INFO:testStrategy:main.py:101:handleKline:185174: self.closeSec=1679558999, self.tradeDate='20230323', self.openTime='160000', self.closeTime='160959',self.symbol='BTCUSDT',self.open='27616.3', self.close='27673.8'
2023-03-23 16:10:01,808:INFO:testStrategy:main.py:102:handleKline:185174: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
12188  20230323   152000    152959  1679556599  27591.8    27576
12189  20230323   153000    153959  1679557199    27576  27622.5
12190  20230323   154000    154959  1679557799  27622.5  27589.1
12191  20230323   155000    155959  1679558399  27589.1  27616.4
12192  20230323   160000    160959  1679558999  27616.3  27673.8
2023-03-23 16:10:01,808:INFO:testStrategy:main.py:103:handleKline:185174: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': True, 'isOpenSell': False, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True, 'isCorr': False}

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=17002 

self.closeSec=1679559599, self.tradeDate='20230323', self.openTime='161000', self.closeTime='161959', self.symbol='BTCUSDT', self.open='27673.9', self.close='27597.5'
127.0.0.1 - - [23/Mar/2023 16:20:05] "POST / HTTP/1.1" 200 -
2023-03-23 16:20:11,600:INFO:testStrategy:main.py:101:handleKline:185174: self.closeSec=1679559599, self.tradeDate='20230323', self.openTime='161000', self.closeTime='161959',self.symbol='BTCUSDT',self.open='27673.9', self.close='27597.5'
2023-03-23 16:20:11,994:INFO:testStrategy:main.py:102:handleKline:185174: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
12189  20230323   153000    153959  1679557199    27576  27622.5
12190  20230323   154000    154959  1679557799  27622.5  27589.1
12191  20230323   155000    155959  1679558399  27589.1  27616.4
12192  20230323   160000    160959  1679558999  27616.3  27673.8
12193  20230323   161000    161959  1679559599  27673.9  27597.5
2023-03-23 16:20:11,999:INFO:testStrategy:main.py:103:handleKline:185174: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': True, 'isOpenSell': False, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True, 'isCorr': False}


## /root/FIL/strategy/sr_min/log.txt ----- -----

--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=0, self.total=1000000.0, self.flagDict['side']='', self.tradeCount=0, self.count=29434
self.closeSec=1679559599, self.tradeDate='20230323', self.openTime='161500', self.closeTime='161959', self.symbol='BTCUSDT', self.open=27606.1, self.close=27597.5, self.high=27620.9, self.low=27571.4, self.vol=2125.882, self.amt=58663773.585 
127.0.0.1 - - [23/Mar/2023 16:20:03] "POST / HTTP/1.1" 200 -
2023-03-23 16:20:08,799:INFO:sr_min:main.py:172:handleKline:449472: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5951  20230323   155500    155959  ...         0.0        0.0       0
5952  20230323   160000    160459  ...         0.0        0.0       0
5953  20230323   160500    160959  ...         0.0        0.0       0
5954  20230323   161000    161459  ...         0.0        0.0       0
5955  20230323   161500    161959  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-03-23 16:20:08,820:INFO:sr_min:main.py:175:handleKline:449472: self.closeSec=1679559599, self.tradeDate='20230323', self.openTime='161500', self.closeTime='161959',self.symbol='BTCUSDT',self.open=27606.1, self.close=27597.5, self.high=27620.9, self.low=27571.4, self.vol=2125.882, self.amt=58663773.585, ukdf['pct'].iloc[-1]=-0.000312 , ukdf['amount'].iloc[-1]=58663773.585, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5955, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': []}
type(curSign)=<class 'int'>, curSign=0, self.sign=0
127.0.0.1 - - [23/Mar/2023 16:25:01] "POST / HTTP/1.1" 200 -
--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=0, self.total=1000000.0, self.flagDict['side']='', self.tradeCount=0, self.count=29435
self.closeSec=1679559899, self.tradeDate='20230323', self.openTime='162000', self.closeTime='162459', self.symbol='BTCUSDT', self.open=27597.5, self.close=27570.9, self.high=27635.5, self.low=27567.1, self.vol=1850.204, self.amt=51072583.2112 
2023-03-23 16:25:01,566:INFO:sr_min:main.py:172:handleKline:449472: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5952  20230323   160000    160459  ...         0.0        0.0       0
5953  20230323   160500    160959  ...         0.0        0.0       0
5954  20230323   161000    161459  ...         0.0        0.0       0
5955  20230323   161500    161959  ...         0.0        0.0       0
5956  20230323   162000    162459  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-03-23 16:25:01,567:INFO:sr_min:main.py:175:handleKline:449472: self.closeSec=1679559899, self.tradeDate='20230323', self.openTime='162000', self.closeTime='162459',self.symbol='BTCUSDT',self.open=27597.5, self.close=27570.9, self.high=27635.5, self.low=27567.1, self.vol=1850.204, self.amt=51072583.2112, ukdf['pct'].iloc[-1]=-0.000964 , ukdf['amount'].iloc[-1]=51072583.2112, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5956, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': []}
type(curSign)=<class 'int'>, curSign=0, self.sign=0


## /root/FIL/strategy/s_rsrs/log.txt ----- -----

721  20230323   040000    075959  1679529599  ...    721  0.129752 -1.963301    -1.0
722  20230323   080000    115959  1679543999  ...    722  0.120047 -2.014558    -1.0

[5 rows x 15 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '53.706', 'enterprice': '28091.1', 'countrevence': '0', 'unrealprofit': '40021.7112', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '27345.9', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'numpy.int64'>, curSign=-1, self.sign=-1
--handleKline--:  version='2.0.0', self.name='s_rsrs', self.symbol='BTCUSDT', interval='4h', intervalSec=14400, wid=25, thd=0.6, self.sign=-1, self.total=1507151.9559834, self.flagDict['side']='sell', self.tradeCount=27, self.count=708
self.closeSec=1679558399, self.tradeDate='20230323', self.openTime='120000', self.closeTime='155959', self.symbol='BTCUSDT', self.open=27343.7, self.close=27616.4, self.high=27680.0, self.low=27231.3, self.vol=84538.137, self.amt=2326729062.95938 
127.0.0.1 - - [23/Mar/2023 16:00:02] "POST / HTTP/1.1" 200 -
2023-03-23 16:00:02,047:INFO:s_rsrs:main.py:141:handleKline:185271: self.closeSec=1679558399, self.tradeDate='20230323', self.openTime='120000', self.closeTime='155959',self.symbol='BTCUSDT',self.open=27343.7, self.close=27616.4, self.high=27680.0, self.low=27231.3, self.vol=84538.137, self.amt=2326729062.95938 
2023-03-23 16:00:02,154:INFO:s_rsrs:main.py:142:handleKline:185271: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime  ...         vol           amt       pct
719  20230322   200000    235959  ...  220961.586  6.291735e+09  0.016814
720  20230323   000000    035959  ...  512199.027  1.430242e+10 -0.067214
721  20230323   040000    075959  ...  168601.777  4.570693e+09  0.021339
722  20230323   080000    115959  ...   63845.694  1.742141e+09  0.004035
723  20230323   120000    155959  ...   84538.137  2.326729e+09  0.009973

[5 rows x 11 columns]
2023-03-23 16:00:04,416:INFO:s_rsrs:main.py:151:handleKline:185271: df_s.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec  ...  index      beta    zscore  signal
719  20230322   200000    235959  1679500799  ...    719  0.475192 -0.815555    -1.0
720  20230323   000000    035959  1679515199  ...    720  0.122268 -1.965458    -1.0
721  20230323   040000    075959  1679529599  ...    721  0.129752 -1.963301    -1.0
722  20230323   080000    115959  1679543999  ...    722  0.120047 -2.014558    -1.0
723  20230323   120000    155959  1679558399  ...    723  0.092907 -2.108669    -1.0

[5 rows x 15 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '53.706', 'enterprice': '28091.1', 'countrevence': '0', 'unrealprofit': '25399.27789367226', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '27618.16815079', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'numpy.int64'>, curSign=-1, self.sign=-1


