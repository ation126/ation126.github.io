# 20230728 00:26:01

## /root/FIL/strategy/amihud/log.txt ----- -----

--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=373746.4768026, self.flagDict['side']='sell', self.tradeCount=2, self.count=21472
127.0.0.1 - - [28/Jul/2023 00:20:01] "POST / HTTP/1.1" 200 -
self.closeSec=1690474799, self.tradeDate='20230728', self.openTime='001500', self.closeTime='001959', self.symbol='BTCUSDT', self.open=29285.1, self.close=29273.4, self.high=29297.5, self.low=29264.0, self.vol=788.45, self.amt=23086473.0877 
2023-07-28 00:20:04,349:INFO:amihud:main.py:172:handleKline:2219019: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5759  20230727   235500    235959  ...         0.0        0.0       0
5760  20230728   000000    000459  ...         0.0        0.0       0
5761  20230728   000500    000959  ...         0.0        0.0       0
5762  20230728   001000    001459  ...         0.0        0.0       0
5763  20230728   001500    001959  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-07-28 00:20:04,369:INFO:amihud:main.py:175:handleKline:2219019: self.closeSec=1690474799, self.tradeDate='20230728', self.openTime='001500', self.closeTime='001959',self.symbol='BTCUSDT',self.open=29285.1, self.close=29273.4, self.high=29297.5, self.low=29264.0, self.vol=788.45, self.amt=23086473.0877, ukdf['pct'].iloc[-1]=-0.000393 , ukdf['amount'].iloc[-1]=23086473.0877, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5763, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '13.926', 'enterprice': '26864.9', 'countrevence': '0', 'unrealprofit': '-33540.771', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '29273.4', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1
--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=373746.4768026, self.flagDict['side']='sell', self.tradeCount=2, self.count=21473
self.closeSec=1690475099, self.tradeDate='20230728', self.openTime='002000', self.closeTime='002459', self.symbol='BTCUSDT', self.open=29273.3, self.close=29276.0, self.high=29279.3, self.low=29247.0, self.vol=1149.225, self.amt=33625680.5443 
127.0.0.1 - - [28/Jul/2023 00:25:00] "POST / HTTP/1.1" 200 -
2023-07-28 00:25:00,776:INFO:amihud:main.py:172:handleKline:2219019: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5760  20230728   000000    000459  ...         0.0        0.0       0
5761  20230728   000500    000959  ...         0.0        0.0       0
5762  20230728   001000    001459  ...         0.0        0.0       0
5763  20230728   001500    001959  ...         0.0        0.0       0
5764  20230728   002000    002459  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-07-28 00:25:00,776:INFO:amihud:main.py:175:handleKline:2219019: self.closeSec=1690475099, self.tradeDate='20230728', self.openTime='002000', self.closeTime='002459',self.symbol='BTCUSDT',self.open=29273.3, self.close=29276.0, self.high=29279.3, self.low=29247.0, self.vol=1149.225, self.amt=33625680.5443, ukdf['pct'].iloc[-1]=8.9e-05 , ukdf['amount'].iloc[-1]=33625680.5443, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5764, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '13.926', 'enterprice': '26864.9', 'countrevence': '0', 'unrealprofit': '-33578.3712', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '29276.1', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1


## /root/FIL/strategy/factorcheck/log.txt ----- -----


self.closeSec=1690474799, self.tradeDate='20230728', self.openTime='001500', self.closeTime='001959', self.symbol='BTCUSDT', self.open=29285.1, self.close=29273.4, self.high=29297.5, self.low=29264.0 
127.0.0.1 - - [28/Jul/2023 00:20:01] "POST / HTTP/1.1" 200 -
2023-07-28 00:20:03,177:INFO:factorcheck2:main.py:126:handleKline:2218005: self.closeSec=1690474799, self.tradeDate='20230728', self.openTime='001500', self.closeTime='001959',self.symbol='BTCUSDT',self.open=29285.1, self.close=29273.4, self.high=29297.5, self.low=29264.0   
2023-07-28 00:20:03,896:INFO:factorcheck2:main.py:127:handleKline:2218005: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime    closeSec  ...      low       pct  index  idx
1439  20230727   235500    235959  1690473599  ...  29278.0 -0.000645   1727    5
1440  20230728   000000    000459  1690473899  ...  29270.1  0.000690   1440    0
1441  20230728   000500    000959  1690474199  ...  29270.0 -0.000959   1441    1
1442  20230728   001000    001459  1690474499  ...  29270.0  0.000506   1442    2
1443  20230728   001500    001959  1690474799  ...  29264.0 -0.000393   1443    3

[5 rows x 11 columns]
2023-07-28 00:20:03,897:INFO:factorcheck2:main.py:128:handleKline:2218005: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}
127.0.0.1 - - [28/Jul/2023 00:25:00] "POST / HTTP/1.1" 200 -

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=51, self.factor=0.47705423678802056, self.count=21475 

self.closeSec=1690475099, self.tradeDate='20230728', self.openTime='002000', self.closeTime='002459', self.symbol='BTCUSDT', self.open=29273.3, self.close=29276.0, self.high=29279.3, self.low=29247.0 
2023-07-28 00:25:00,739:INFO:factorcheck2:main.py:126:handleKline:2218005: self.closeSec=1690475099, self.tradeDate='20230728', self.openTime='002000', self.closeTime='002459',self.symbol='BTCUSDT',self.open=29273.3, self.close=29276.0, self.high=29279.3, self.low=29247.0   
2023-07-28 00:25:00,752:INFO:factorcheck2:main.py:127:handleKline:2218005: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime    closeSec  ...      low       pct  index  idx
1440  20230728   000000    000459  1690473899  ...  29270.1  0.000690   1440    0
1441  20230728   000500    000959  1690474199  ...  29270.0 -0.000959   1441    1
1442  20230728   001000    001459  1690474499  ...  29270.0  0.000506   1442    2
1443  20230728   001500    001959  1690474799  ...  29264.0 -0.000393   1443    3
1444  20230728   002000    002459  1690475099  ...  29247.0  0.000089   1444    4

[5 rows x 11 columns]
2023-07-28 00:25:00,752:INFO:factorcheck2:main.py:128:handleKline:2218005: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}


## /root/FIL/strategy/logic/log.txt ----- -----

2023-07-28 00:00:18,167:DEBUG:logic:main.py:463:getModel:2218526: df_s.iloc[-5:,:] :
          date closeTime     open  ...    alpha58   alpha67   alpha72
5802  20230727    212959  29486.5  ...  49.166667  0.529850  0.428661
5803  20230727    215959  29450.0  ...  49.166667  0.523120  0.432166
5804  20230727    222959  29430.5  ...  49.166667  0.504418  0.442860
5805  20230727    225959  29375.0  ...  48.750000  0.491779  0.458071
5806  20230727    232959  29335.9  ...  48.750000  0.485242  0.479861

[5 rows x 33 columns]
0.5735294117647058
acc is : 0.5735294117647058
2023-07-28 00:00:18,226:INFO:logic:main.py:468:getModel:2218526: df_pred.iloc[-5:,:] :
     pred    prob_0    prob_1  actual  ...       nav  sign  cost_        bm
539     1  0.497046  0.502954       0  ...  0.927215   1.0    0.0  0.972816
540     1  0.499093  0.500907       0  ...  0.925467   1.0    0.0  0.970981
541     1  0.481541  0.518459       0  ...  0.924235   1.0    0.0  0.969689
542     1  0.482642  0.517358       0  ...  0.923586   1.0    0.0  0.969008
543     1  0.483476  0.516524       0  ...  0.922408   1.0    0.0  0.967772

[5 rows x 10 columns]
2023-07-28 00:00:18,238:INFO:logic:main.py:478:getModel:2218526: df_panel.iloc[-5:,:] :
    pred    prob_0    prob_1  actual  ...       nav  sign  cost_        bm
45     1  0.496863  0.503137       0  ...  0.927215   1.0    0.0  0.973109
46     1  0.498760  0.501240       0  ...  0.925467   1.0    0.0  0.971238
47     1  0.481599  0.518401       0  ...  0.924235   1.0    0.0  0.969945
48     1  0.482521  0.517479       0  ...  0.923586   1.0    0.0  0.968505
49     1  0.483476  0.516524       0  ...  0.922408   1.0    0.0  0.967772

[5 rows x 10 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '23.818', 'enterprice': '29478', 'countrevence': '0', 'unrealprofit': '-4820.98881671954', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '29275.59052747', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}


## /root/FIL/strategy/modifiedmom/log.txt ----- -----

127.0.0.1 - - [28/Jul/2023 00:00:04] "POST / HTTP/1.1" 200 -
2023-07-28 00:00:04,400:INFO:modifiedmom:main.py:319:handleOrderFilled:2218259: handleOrderFilled: data=OrderType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'clientorderid': '42746F1690473603622I0L59', 'symbol': 'BTCUSDT', 'gatewayorderid': 1690473604060368, 'quantity': '25.461', 'price': '29278', 'stopprice': '0', 'ordertype': '', 'side': 'SELL', 'status': 'FILLED', 'positionside': 'SHORT', 'createtime': 1690473602680, 'updatetime': 1690473604060, 'tradetype': 'usdt', 'selfid': 42746, 'filltrades': [TradeType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'tradeid': 1690473604060, 'clientorderid': '42746F1690473603622I0L59', 'price': '29278', 'quantity': '25.461', 'commission': '745.447158', 'commissionasset': 'USDT', 'tradetime': 1690473604060, 'tradetype': 'usdt', 'gatetype': 'simulator', 'handletime': 1690473604060}], 'gatetype': 'simulator', 'handletime': 0}
127.0.0.1 - - [28/Jul/2023 00:10:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=10736 

self.closeSec=1690474199, self.tradeDate='20230728', self.openTime='000000', self.closeTime='000959', self.symbol='BTCUSDT', self.open='29278', self.close='29270.1'
2023-07-28 00:10:01,104:INFO:modifiedmom:main.py:144:handleKline:2218259: self.closeSec=1690474199, self.tradeDate='20230728', self.openTime='000000', self.closeTime='000959',self.symbol='BTCUSDT',self.open='29278', self.close='29270.1'
2023-07-28 00:10:01,111:INFO:modifiedmom:main.py:145:handleKline:2218259: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec     open    close       pct
572  20230727   232000    232959  1690471799  29272.3  29315.4  0.001476
573  20230727   233000    233959  1690472399  29315.4  29305.9 -0.000324
574  20230727   234000    234959  1690472999  29305.9  29320.1  0.000485
575  20230727   235000    235959  1690473599  29320.1    29278 -0.001436
576  20230728   000000    000959  1690474199    29278  29270.1 -0.000270
2023-07-28 00:10:01,111:INFO:modifiedmom:main.py:146:handleKline:2218259: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': True, 'isOpen': False, 'isClose': True, 'isTrig': False}

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=10737 

self.closeSec=1690474799, self.tradeDate='20230728', self.openTime='001000', self.closeTime='001959', self.symbol='BTCUSDT', self.open='29271.7', self.close='29273.4'
127.0.0.1 - - [28/Jul/2023 00:20:03] "POST / HTTP/1.1" 200 -
2023-07-28 00:20:04,946:INFO:modifiedmom:main.py:144:handleKline:2218259: self.closeSec=1690474799, self.tradeDate='20230728', self.openTime='001000', self.closeTime='001959',self.symbol='BTCUSDT',self.open='29271.7', self.close='29273.4'
2023-07-28 00:20:05,197:INFO:modifiedmom:main.py:145:handleKline:2218259: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec     open    close       pct
573  20230727   233000    233959  1690472399  29315.4  29305.9 -0.000324
574  20230727   234000    234959  1690472999  29305.9  29320.1  0.000485
575  20230727   235000    235959  1690473599  29320.1    29278 -0.001436
576  20230728   000000    000959  1690474199    29278  29270.1 -0.000270
577  20230728   001000    001959  1690474799  29271.7  29273.4  0.000113
2023-07-28 00:20:05,197:INFO:modifiedmom:main.py:146:handleKline:2218259: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': True, 'isOpen': False, 'isClose': True, 'isTrig': False}


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

127.0.0.1 - - [28/Jul/2023 00:00:04] "POST / HTTP/1.1" 200 -
2023-07-28 00:00:04,105:INFO:pyemd2:main.py:303:handleOrderFilled:2217508: handleOrderFilled: data=OrderType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'clientorderid': '42745F1690473603534I0L57', 'symbol': 'BTCUSDT', 'gatewayorderid': 1690473603934882, 'quantity': '34.039', 'price': '29278', 'stopprice': '0', 'ordertype': '', 'side': 'SELL', 'status': 'FILLED', 'positionside': 'SHORT', 'createtime': 1690473602626, 'updatetime': 1690473603934, 'tradetype': 'usdt', 'selfid': 42745, 'filltrades': [TradeType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'tradeid': 1690473603934, 'clientorderid': '42745F1690473603534I0L57', 'price': '29278', 'quantity': '34.039', 'commission': '996.593842', 'commissionasset': 'USDT', 'tradetime': 1690473603934, 'tradetype': 'usdt', 'gatetype': 'simulator', 'handletime': 1690473603934}], 'gatetype': 'simulator', 'handletime': 0}

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=10739 

self.closeSec=1690474199, self.tradeDate='20230728', self.openTime='000000', self.closeTime='000959', self.symbol='BTCUSDT', self.open='29278', self.close='29270.1'
2023-07-28 00:10:01,115:INFO:pyemd2:main.py:125:handleKline:2217508: self.closeSec=1690474199, self.tradeDate='20230728', self.openTime='000000', self.closeTime='000959',self.symbol='BTCUSDT',self.open='29278', self.close='29270.1'
127.0.0.1 - - [28/Jul/2023 00:10:01] "POST / HTTP/1.1" 200 -
2023-07-28 00:10:01,131:INFO:pyemd2:main.py:126:handleKline:2217508: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
17420  20230727   232000    232959  1690471799  29272.3  29315.4
17421  20230727   233000    233959  1690472399  29315.4  29305.9
17422  20230727   234000    234959  1690472999  29305.9  29320.1
17423  20230727   235000    235959  1690473599  29320.1    29278
17424  20230728   000000    000959  1690474199    29278  29270.1
2023-07-28 00:10:01,131:INFO:pyemd2:main.py:127:handleKline:2217508: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=10740 

self.closeSec=1690474799, self.tradeDate='20230728', self.openTime='001000', self.closeTime='001959', self.symbol='BTCUSDT', self.open='29271.7', self.close='29273.4'
127.0.0.1 - - [28/Jul/2023 00:20:03] "POST / HTTP/1.1" 200 -
2023-07-28 00:20:05,838:INFO:pyemd2:main.py:125:handleKline:2217508: self.closeSec=1690474799, self.tradeDate='20230728', self.openTime='001000', self.closeTime='001959',self.symbol='BTCUSDT',self.open='29271.7', self.close='29273.4'
2023-07-28 00:20:05,945:INFO:pyemd2:main.py:126:handleKline:2217508: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
17421  20230727   233000    233959  1690472399  29315.4  29305.9
17422  20230727   234000    234959  1690472999  29305.9  29320.1
17423  20230727   235000    235959  1690473599  29320.1    29278
17424  20230728   000000    000959  1690474199    29278  29270.1
17425  20230728   001000    001959  1690474799  29271.7  29273.4
2023-07-28 00:20:05,946:INFO:pyemd2:main.py:127:handleKline:2217508: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}


## /root/FIL/strategy/similarity/log.txt ----- -----

127.0.0.1 - - [28/Jul/2023 00:00:04] "POST / HTTP/1.1" 200 -
2023-07-28 00:00:04,265:INFO:testStrategy:main.py:308:handleOrderFilled:2217133: handleOrderFilled: data=OrderType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'clientorderid': '42747F1690473603637I0L2', 'symbol': 'BTCUSDT', 'gatewayorderid': 1690473604046477, 'quantity': '37.01', 'price': '29278.1', 'stopprice': '0', 'ordertype': '', 'side': 'BUY', 'status': 'FILLED', 'positionside': 'LONG', 'createtime': 1690473602721, 'updatetime': 1690473604046, 'tradetype': 'usdt', 'selfid': 42747, 'filltrades': [TradeType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'tradeid': 1690473604046, 'clientorderid': '42747F1690473603637I0L2', 'price': '29278.1', 'quantity': '37.01', 'commission': '1083.582481', 'commissionasset': 'USDT', 'tradetime': 1690473604046, 'tradetype': 'usdt', 'gatetype': 'simulator', 'handletime': 1690473604046}], 'gatetype': 'simulator', 'handletime': 0}
127.0.0.1 - - [28/Jul/2023 00:10:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=10739 

self.closeSec=1690474199, self.tradeDate='20230728', self.openTime='000000', self.closeTime='000959', self.symbol='BTCUSDT', self.open='29278', self.close='29270.1'
2023-07-28 00:10:01,106:INFO:testStrategy:main.py:101:handleKline:2217133: self.closeSec=1690474199, self.tradeDate='20230728', self.openTime='000000', self.closeTime='000959',self.symbol='BTCUSDT',self.open='29278', self.close='29270.1'
2023-07-28 00:10:01,125:INFO:testStrategy:main.py:102:handleKline:2217133: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
12236  20230727   232000    232959  1690471799  29272.3  29315.4
12237  20230727   233000    233959  1690472399  29315.4  29305.9
12238  20230727   234000    234959  1690472999  29305.9  29320.1
12239  20230727   235000    235959  1690473599  29320.1    29278
12240  20230728   000000    000959  1690474199    29278  29270.1
2023-07-28 00:10:01,125:INFO:testStrategy:main.py:103:handleKline:2217133: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': True, 'isOpen': False, 'isClose': True, 'isTrig': False, 'isCorr': False}

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=10740 

self.closeSec=1690474799, self.tradeDate='20230728', self.openTime='001000', self.closeTime='001959', self.symbol='BTCUSDT', self.open='29271.7', self.close='29273.4'
127.0.0.1 - - [28/Jul/2023 00:20:03] "POST / HTTP/1.1" 200 -
2023-07-28 00:20:05,727:INFO:testStrategy:main.py:101:handleKline:2217133: self.closeSec=1690474799, self.tradeDate='20230728', self.openTime='001000', self.closeTime='001959',self.symbol='BTCUSDT',self.open='29271.7', self.close='29273.4'
2023-07-28 00:20:05,847:INFO:testStrategy:main.py:102:handleKline:2217133: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
12237  20230727   233000    233959  1690472399  29315.4  29305.9
12238  20230727   234000    234959  1690472999  29305.9  29320.1
12239  20230727   235000    235959  1690473599  29320.1    29278
12240  20230728   000000    000959  1690474199    29278  29270.1
12241  20230728   001000    001959  1690474799  29271.7  29273.4
2023-07-28 00:20:05,847:INFO:testStrategy:main.py:103:handleKline:2217133: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': True, 'isOpen': False, 'isClose': True, 'isTrig': False, 'isCorr': False}


## /root/FIL/strategy/sr_min/log.txt ----- -----

--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=1, self.total=996015.990996, self.flagDict['side']='buy', self.tradeCount=1, self.count=21472
self.closeSec=1690474799, self.tradeDate='20230728', self.openTime='001500', self.closeTime='001959', self.symbol='BTCUSDT', self.open=29285.1, self.close=29273.4, self.high=29297.5, self.low=29264.0, self.vol=788.45, self.amt=23086473.0877 
127.0.0.1 - - [28/Jul/2023 00:20:01] "POST / HTTP/1.1" 200 -
2023-07-28 00:20:04,367:INFO:sr_min:main.py:172:handleKline:2219263: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5759  20230727   235500    235959  ...         0.0        0.0       0
5760  20230728   000000    000459  ...         0.0        0.0       0
5761  20230728   000500    000959  ...         0.0        0.0       0
5762  20230728   001000    001459  ...         0.0        0.0       0
5763  20230728   001500    001959  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-07-28 00:20:04,377:INFO:sr_min:main.py:175:handleKline:2219263: self.closeSec=1690474799, self.tradeDate='20230728', self.openTime='001500', self.closeTime='001959',self.symbol='BTCUSDT',self.open=29285.1, self.close=29273.4, self.high=29297.5, self.low=29264.0, self.vol=788.45, self.amt=23086473.0877, ukdf['pct'].iloc[-1]=-0.000393 , ukdf['amount'].iloc[-1]=23086473.0877, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5763, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '37.141', 'enterprice': '26844', 'countrevence': '0', 'unrealprofit': '90230.3454', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '29273.4', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=1
127.0.0.1 - - [28/Jul/2023 00:25:00] "POST / HTTP/1.1" 200 -
--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=1, self.total=996015.990996, self.flagDict['side']='buy', self.tradeCount=1, self.count=21473
self.closeSec=1690475099, self.tradeDate='20230728', self.openTime='002000', self.closeTime='002459', self.symbol='BTCUSDT', self.open=29273.3, self.close=29276.0, self.high=29279.3, self.low=29247.0, self.vol=1149.225, self.amt=33625680.5443 
2023-07-28 00:25:00,780:INFO:sr_min:main.py:172:handleKline:2219263: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5760  20230728   000000    000459  ...         0.0        0.0       0
5761  20230728   000500    000959  ...         0.0        0.0       0
5762  20230728   001000    001459  ...         0.0        0.0       0
5763  20230728   001500    001959  ...         0.0        0.0       0
5764  20230728   002000    002459  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-07-28 00:25:00,781:INFO:sr_min:main.py:175:handleKline:2219263: self.closeSec=1690475099, self.tradeDate='20230728', self.openTime='002000', self.closeTime='002459',self.symbol='BTCUSDT',self.open=29273.3, self.close=29276.0, self.high=29279.3, self.low=29247.0, self.vol=1149.225, self.amt=33625680.5443, ukdf['pct'].iloc[-1]=8.9e-05 , ukdf['amount'].iloc[-1]=33625680.5443, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5764, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '37.141', 'enterprice': '26844', 'countrevence': '0', 'unrealprofit': '90330.6261', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '29276.1', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=1


## /root/FIL/strategy/s_rsrs/log.txt ----- -----

723  20230727   120000    155959  1690444799  ...    723  0.611399  0.866264     1.0
724  20230727   160000    195959  1690459199  ...    724  0.610258  0.847065     1.0

[5 rows x 15 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '54.821', 'enterprice': '29117.6', 'countrevence': '0', 'unrealprofit': '20634.6244', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '29494', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'numpy.int64'>, curSign=1, self.sign=1
127.0.0.1 - - [28/Jul/2023 00:00:01] "POST / HTTP/1.1" 200 -
--handleKline--:  version='2.0.0', self.name='s_rsrs', self.symbol='BTCUSDT', interval='4h', intervalSec=14400, wid=25, thd=0.6, self.sign=1, self.total=1594659.6936504, self.flagDict['side']='buy', self.tradeCount=13, self.count=447
self.closeSec=1690473599, self.tradeDate='20230727', self.openTime='200000', self.closeTime='235959', self.symbol='BTCUSDT', self.open=29494.0, self.close=29278.0, self.high=29495.1, self.low=29218.1, self.vol=55283.047, self.amt=1623141566.15658 
2023-07-28 00:00:01,737:INFO:s_rsrs:main.py:141:handleKline:2218689: self.closeSec=1690473599, self.tradeDate='20230727', self.openTime='200000', self.closeTime='235959',self.symbol='BTCUSDT',self.open=29494.0, self.close=29278.0, self.high=29495.1, self.low=29218.1, self.vol=55283.047, self.amt=1623141566.15658 
2023-07-28 00:00:01,754:INFO:s_rsrs:main.py:142:handleKline:2218689: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime  ...        vol           amt       pct
721  20230727   040000    075959  ...  90685.517  2.674287e+09 -0.001848
722  20230727   080000    115959  ...  22249.763  6.533111e+08  0.001776
723  20230727   120000    155959  ...  27656.693  8.140954e+08  0.000299
724  20230727   160000    195959  ...  34054.531  1.003948e+09  0.003300
725  20230727   200000    235959  ...  55283.047  1.623142e+09 -0.007320

[5 rows x 11 columns]
2023-07-28 00:00:02,519:INFO:s_rsrs:main.py:151:handleKline:2218689: df_s.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec  ...  index      beta    zscore  signal
721  20230727   040000    075959  1690415999  ...    721  0.621201  0.937997     1.0
722  20230727   080000    115959  1690430399  ...    722  0.616412  0.900702     1.0
723  20230727   120000    155959  1690444799  ...    723  0.611399  0.866264     1.0
724  20230727   160000    195959  1690459199  ...    724  0.610258  0.847065     1.0
725  20230727   200000    235959  1690473599  ...    725  0.644596  0.965451     1.0

[5 rows x 15 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '54.821', 'enterprice': '29117.6', 'countrevence': '0', 'unrealprofit': '8800.34396192601', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '29278.12870181', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'numpy.int64'>, curSign=1, self.sign=1


