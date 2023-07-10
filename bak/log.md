# 20230710 08:26:01

## /root/FIL/strategy/amihud/log.txt ----- -----

--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=373746.4768026, self.flagDict['side']='sell', self.tradeCount=2, self.count=16384
self.closeSec=1688948399, self.tradeDate='20230710', self.openTime='081500', self.closeTime='081959', self.symbol='BTCUSDT', self.open=30017.5, self.close=30022.5, self.high=30025.6, self.low=29932.1, self.vol=3548.091, self.amt=106343248.6969 
127.0.0.1 - - [10/Jul/2023 08:20:02] "POST / HTTP/1.1" 200 -
2023-07-10 08:20:07,418:INFO:amihud:main.py:172:handleKline:2219019: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5855  20230710   075500    075959  ...         0.0        0.0       0
5856  20230710   080000    080459  ...         0.0        0.0       0
5857  20230710   080500    080959  ...         0.0        0.0       0
5858  20230710   081000    081459  ...         0.0        0.0       0
5859  20230710   081500    081959  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-07-10 08:20:07,449:INFO:amihud:main.py:175:handleKline:2219019: self.closeSec=1688948399, self.tradeDate='20230710', self.openTime='081500', self.closeTime='081959',self.symbol='BTCUSDT',self.open=30017.5, self.close=30022.5, self.high=30025.6, self.low=29932.1, self.vol=3548.091, self.amt=106343248.6969, ukdf['pct'].iloc[-1]=0.000167 , ukdf['amount'].iloc[-1]=106343248.6969, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5859, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '13.926', 'enterprice': '26864.9', 'countrevence': '0', 'unrealprofit': '-44050.7232', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '30028.1', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1
--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=373746.4768026, self.flagDict['side']='sell', self.tradeCount=2, self.count=16385
self.closeSec=1688948699, self.tradeDate='20230710', self.openTime='082000', self.closeTime='082459', self.symbol='BTCUSDT', self.open=30025.5, self.close=30004.3, self.high=30048.8, self.low=29975.7, self.vol=2105.3, self.amt=63184743.8436 
127.0.0.1 - - [10/Jul/2023 08:25:00] "POST / HTTP/1.1" 200 -
2023-07-10 08:25:00,811:INFO:amihud:main.py:172:handleKline:2219019: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5856  20230710   080000    080459  ...         0.0        0.0       0
5857  20230710   080500    080959  ...         0.0        0.0       0
5858  20230710   081000    081459  ...         0.0        0.0       0
5859  20230710   081500    081959  ...         0.0        0.0       0
5860  20230710   082000    082459  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-07-10 08:25:00,813:INFO:amihud:main.py:175:handleKline:2219019: self.closeSec=1688948699, self.tradeDate='20230710', self.openTime='082000', self.closeTime='082459',self.symbol='BTCUSDT',self.open=30025.5, self.close=30004.3, self.high=30048.8, self.low=29975.7, self.vol=2105.3, self.amt=63184743.8436, ukdf['pct'].iloc[-1]=-0.000606 , ukdf['amount'].iloc[-1]=63184743.8436, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5860, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '13.926', 'enterprice': '26864.9', 'countrevence': '0', 'unrealprofit': '-43719.2844', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '30004.3', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1


## /root/FIL/strategy/factorcheck/log.txt ----- -----


self.closeSec=1688948399, self.tradeDate='20230710', self.openTime='081500', self.closeTime='081959', self.symbol='BTCUSDT', self.open=30017.5, self.close=30022.5, self.high=30025.6, self.low=29932.1 
127.0.0.1 - - [10/Jul/2023 08:20:01] "POST / HTTP/1.1" 200 -
2023-07-10 08:20:04,838:INFO:factorcheck2:main.py:126:handleKline:2218005: self.closeSec=1688948399, self.tradeDate='20230710', self.openTime='081500', self.closeTime='081959',self.symbol='BTCUSDT',self.open=30017.5, self.close=30022.5, self.high=30025.6, self.low=29932.1   
2023-07-10 08:20:06,489:INFO:factorcheck2:main.py:127:handleKline:2218005: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime    closeSec  ...      low       pct  index  idx
1535  20230710   075500    075959  1688947199  ...  30145.6  0.000073   1535    5
1536  20230710   080000    080459  1688947499  ...  30120.6 -0.000770   1536    0
1537  20230710   080500    080959  1688947799  ...  30065.6 -0.001178   1537    1
1538  20230710   081000    081459  1688948099  ...  29928.8 -0.002380   1538    2
1539  20230710   081500    081959  1688948399  ...  29932.1  0.000167   1539    3

[5 rows x 11 columns]
2023-07-10 08:20:06,508:INFO:factorcheck2:main.py:128:handleKline:2218005: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}
127.0.0.1 - - [10/Jul/2023 08:25:00] "POST / HTTP/1.1" 200 -

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=63, self.factor=0.5139841382536728, self.count=16387 

self.closeSec=1688948699, self.tradeDate='20230710', self.openTime='082000', self.closeTime='082459', self.symbol='BTCUSDT', self.open=30025.5, self.close=30004.3, self.high=30048.8, self.low=29975.7 
2023-07-10 08:25:00,740:INFO:factorcheck2:main.py:126:handleKline:2218005: self.closeSec=1688948699, self.tradeDate='20230710', self.openTime='082000', self.closeTime='082459',self.symbol='BTCUSDT',self.open=30025.5, self.close=30004.3, self.high=30048.8, self.low=29975.7   
2023-07-10 08:25:00,789:INFO:factorcheck2:main.py:127:handleKline:2218005: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime    closeSec  ...      low       pct  index  idx
1536  20230710   080000    080459  1688947499  ...  30120.6 -0.000770   1536    0
1537  20230710   080500    080959  1688947799  ...  30065.6 -0.001178   1537    1
1538  20230710   081000    081459  1688948099  ...  29928.8 -0.002380   1538    2
1539  20230710   081500    081959  1688948399  ...  29932.1  0.000167   1539    3
1540  20230710   082000    082459  1688948699  ...  29975.7 -0.000606   1540    4

[5 rows x 11 columns]
2023-07-10 08:25:00,789:INFO:factorcheck2:main.py:128:handleKline:2218005: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}


## /root/FIL/strategy/logic/log.txt ----- -----

2023-07-10 08:00:20,529:DEBUG:logic:main.py:463:getModel:2218526: df_s.iloc[-5:,:] :
          date closeTime     open  ...    alpha58   alpha67   alpha72
5770  20230710    052959  30176.4  ...  46.250000  0.475125  0.535711
5771  20230710    055959  30194.0  ...  45.833333  0.457207  0.556562
5772  20230710    062959  30142.6  ...  45.833333  0.448196  0.573851
5773  20230710    065959  30116.0  ...  45.833333  0.465988  0.582613
5774  20230710    072959  30160.2  ...  45.833333  0.461508  0.592967

[5 rows x 33 columns]
0.5841035120147874
acc is : 0.5841035120147874
2023-07-10 08:00:20,646:INFO:logic:main.py:468:getModel:2218526: df_pred.iloc[-5:,:] :
     pred    prob_0    prob_1  actual  ...       nav  sign  cost_        bm
536     0  0.506835  0.493165       0  ...  0.957911  -1.0    0.0  0.998923
537     1  0.487882  0.512118       0  ...  0.958763  -1.0    0.0  0.998035
538     1  0.490927  0.509073       1  ...  0.957349  -1.0    0.0  0.999506
539     0  0.512525  0.487475       0  ...  0.957765  -1.0    0.0  0.999072
540     0  0.502631  0.497369       0  ...  0.957746  -1.0    0.0  0.999092

[5 rows x 10 columns]
2023-07-10 08:00:20,676:INFO:logic:main.py:478:getModel:2218526: df_panel.iloc[-5:,:] :
    pred    prob_0    prob_1  actual  ...       nav  sign  cost_        bm
45     0  0.505322  0.494678       0  ...  0.975320  -1.0    0.0  0.991543
46     1  0.487278  0.512722       0  ...  0.958763  -1.0    0.0  0.992185
47     1  0.490143  0.509857       1  ...  0.957349  -1.0    0.0  0.997285
48     0  0.512352  0.487648       0  ...  0.957765  -1.0    0.0  0.999072
49     0  0.502631  0.497369       0  ...  0.957746  -1.0    0.0  0.999092

[5 rows x 10 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '24.725', 'enterprice': '30166.1', 'countrevence': '0', 'unrealprofit': '429.36325342', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '30148.7344488', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}


## /root/FIL/strategy/modifiedmom/log.txt ----- -----

623  20230710   075000    075959  1688947199  30135.7  30147.8  0.000402
2023-07-10 08:00:02,167:INFO:modifiedmom:main.py:146:handleKline:2218259: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': True, 'isOpen': False, 'isClose': True, 'isTrig': False}

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=8192 

self.closeSec=1688947799, self.tradeDate='20230710', self.openTime='080000', self.closeTime='080959', self.symbol='BTCUSDT', self.open='30147.8', self.close='30087'
2023-07-10 08:10:01,095:INFO:modifiedmom:main.py:144:handleKline:2218259: self.closeSec=1688947799, self.tradeDate='20230710', self.openTime='080000', self.closeTime='080959',self.symbol='BTCUSDT',self.open='30147.8', self.close='30087'
2023-07-10 08:10:01,105:INFO:modifiedmom:main.py:145:handleKline:2218259: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec     open    close       pct
620  20230710   072000    072959  1688945399  30139.6  30147.2  0.000252
621  20230710   073000    073959  1688945999  30147.1  30137.3 -0.000328
622  20230710   074000    074959  1688946599  30137.2  30135.7 -0.000053
623  20230710   075000    075959  1688947199  30135.7  30147.8  0.000402
624  20230710   080000    080959  1688947799  30147.8    30087 -0.002017
2023-07-10 08:10:01,105:INFO:modifiedmom:main.py:146:handleKline:2218259: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': True, 'isOpen': False, 'isClose': True, 'isTrig': False}
127.0.0.1 - - [10/Jul/2023 08:10:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=8193 

self.closeSec=1688948399, self.tradeDate='20230710', self.openTime='081000', self.closeTime='081959', self.symbol='BTCUSDT', self.open='30086.9', self.close='30022.5'
127.0.0.1 - - [10/Jul/2023 08:20:04] "POST / HTTP/1.1" 200 -
2023-07-10 08:20:07,338:INFO:modifiedmom:main.py:144:handleKline:2218259: self.closeSec=1688948399, self.tradeDate='20230710', self.openTime='081000', self.closeTime='081959',self.symbol='BTCUSDT',self.open='30086.9', self.close='30022.5'
2023-07-10 08:20:08,191:INFO:modifiedmom:main.py:145:handleKline:2218259: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec     open    close       pct
621  20230710   073000    073959  1688945999  30147.1  30137.3 -0.000328
622  20230710   074000    074959  1688946599  30137.2  30135.7 -0.000053
623  20230710   075000    075959  1688947199  30135.7  30147.8  0.000402
624  20230710   080000    080959  1688947799  30147.8    30087 -0.002017
625  20230710   081000    081959  1688948399  30086.9  30022.5 -0.002144
2023-07-10 08:20:08,191:INFO:modifiedmom:main.py:146:handleKline:2218259: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': True, 'isOpen': False, 'isClose': True, 'isTrig': False}


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

17471  20230710   075000    075959  1688947199  30135.7  30147.8
2023-07-10 08:00:02,190:INFO:pyemd2:main.py:127:handleKline:2217508: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}
127.0.0.1 - - [10/Jul/2023 08:10:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=8195 

self.closeSec=1688947799, self.tradeDate='20230710', self.openTime='080000', self.closeTime='080959', self.symbol='BTCUSDT', self.open='30147.8', self.close='30087'
2023-07-10 08:10:01,153:INFO:pyemd2:main.py:125:handleKline:2217508: self.closeSec=1688947799, self.tradeDate='20230710', self.openTime='080000', self.closeTime='080959',self.symbol='BTCUSDT',self.open='30147.8', self.close='30087'
2023-07-10 08:10:01,198:INFO:pyemd2:main.py:126:handleKline:2217508: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
17468  20230710   072000    072959  1688945399  30139.6  30147.2
17469  20230710   073000    073959  1688945999  30147.1  30137.3
17470  20230710   074000    074959  1688946599  30137.2  30135.7
17471  20230710   075000    075959  1688947199  30135.7  30147.8
17472  20230710   080000    080959  1688947799  30147.8    30087
2023-07-10 08:10:01,198:INFO:pyemd2:main.py:127:handleKline:2217508: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=8196 

self.closeSec=1688948399, self.tradeDate='20230710', self.openTime='081000', self.closeTime='081959', self.symbol='BTCUSDT', self.open='30086.9', self.close='30022.5'
127.0.0.1 - - [10/Jul/2023 08:20:04] "POST / HTTP/1.1" 200 -
2023-07-10 08:20:09,019:INFO:pyemd2:main.py:125:handleKline:2217508: self.closeSec=1688948399, self.tradeDate='20230710', self.openTime='081000', self.closeTime='081959',self.symbol='BTCUSDT',self.open='30086.9', self.close='30022.5'
2023-07-10 08:20:09,216:INFO:pyemd2:main.py:126:handleKline:2217508: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
17469  20230710   073000    073959  1688945999  30147.1  30137.3
17470  20230710   074000    074959  1688946599  30137.2  30135.7
17471  20230710   075000    075959  1688947199  30135.7  30147.8
17472  20230710   080000    080959  1688947799  30147.8    30087
17473  20230710   081000    081959  1688948399  30086.9  30022.5
2023-07-10 08:20:09,217:INFO:pyemd2:main.py:127:handleKline:2217508: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}


## /root/FIL/strategy/similarity/log.txt ----- -----

12143  20230710   075000    075959  1688947199  30135.7  30147.8
2023-07-10 08:00:02,110:INFO:testStrategy:main.py:103:handleKline:2217133: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': True, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True, 'isCorr': False}

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=8195 

self.closeSec=1688947799, self.tradeDate='20230710', self.openTime='080000', self.closeTime='080959', self.symbol='BTCUSDT', self.open='30147.8', self.close='30087'
127.0.0.1 - - [10/Jul/2023 08:10:01] "POST / HTTP/1.1" 200 -
2023-07-10 08:10:01,141:INFO:testStrategy:main.py:101:handleKline:2217133: self.closeSec=1688947799, self.tradeDate='20230710', self.openTime='080000', self.closeTime='080959',self.symbol='BTCUSDT',self.open='30147.8', self.close='30087'
2023-07-10 08:10:01,188:INFO:testStrategy:main.py:102:handleKline:2217133: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
12140  20230710   072000    072959  1688945399  30139.6  30147.2
12141  20230710   073000    073959  1688945999  30147.1  30137.3
12142  20230710   074000    074959  1688946599  30137.2  30135.7
12143  20230710   075000    075959  1688947199  30135.7  30147.8
12144  20230710   080000    080959  1688947799  30147.8    30087
2023-07-10 08:10:01,188:INFO:testStrategy:main.py:103:handleKline:2217133: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': True, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True, 'isCorr': False}

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=8196 

self.closeSec=1688948399, self.tradeDate='20230710', self.openTime='081000', self.closeTime='081959', self.symbol='BTCUSDT', self.open='30086.9', self.close='30022.5'
127.0.0.1 - - [10/Jul/2023 08:20:04] "POST / HTTP/1.1" 200 -
2023-07-10 08:20:08,769:INFO:testStrategy:main.py:101:handleKline:2217133: self.closeSec=1688948399, self.tradeDate='20230710', self.openTime='081000', self.closeTime='081959',self.symbol='BTCUSDT',self.open='30086.9', self.close='30022.5'
2023-07-10 08:20:09,059:INFO:testStrategy:main.py:102:handleKline:2217133: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
12141  20230710   073000    073959  1688945999  30147.1  30137.3
12142  20230710   074000    074959  1688946599  30137.2  30135.7
12143  20230710   075000    075959  1688947199  30135.7  30147.8
12144  20230710   080000    080959  1688947799  30147.8    30087
12145  20230710   081000    081959  1688948399  30086.9  30022.5
2023-07-10 08:20:09,061:INFO:testStrategy:main.py:103:handleKline:2217133: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': True, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True, 'isCorr': False}


## /root/FIL/strategy/sr_min/log.txt ----- -----

--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=1, self.total=996015.990996, self.flagDict['side']='buy', self.tradeCount=1, self.count=16384
self.closeSec=1688948399, self.tradeDate='20230710', self.openTime='081500', self.closeTime='081959', self.symbol='BTCUSDT', self.open=30017.5, self.close=30022.5, self.high=30025.6, self.low=29932.1, self.vol=3548.091, self.amt=106343248.6969 
127.0.0.1 - - [10/Jul/2023 08:20:01] "POST / HTTP/1.1" 200 -
2023-07-10 08:20:07,418:INFO:sr_min:main.py:172:handleKline:2219263: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5855  20230710   075500    075959  ...         0.0        0.0       0
5856  20230710   080000    080459  ...         0.0        0.0       0
5857  20230710   080500    080959  ...         0.0        0.0       0
5858  20230710   081000    081459  ...         0.0        0.0       0
5859  20230710   081500    081959  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-07-10 08:20:07,449:INFO:sr_min:main.py:175:handleKline:2219263: self.closeSec=1688948399, self.tradeDate='20230710', self.openTime='081500', self.closeTime='081959',self.symbol='BTCUSDT',self.open=30017.5, self.close=30022.5, self.high=30025.6, self.low=29932.1, self.vol=3548.091, self.amt=106343248.6969, ukdf['pct'].iloc[-1]=0.000167 , ukdf['amount'].iloc[-1]=106343248.6969, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5859, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '37.141', 'enterprice': '26844', 'countrevence': '0', 'unrealprofit': '118260.6581', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '30028.1', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=1
--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=1, self.total=996015.990996, self.flagDict['side']='buy', self.tradeCount=1, self.count=16385
self.closeSec=1688948699, self.tradeDate='20230710', self.openTime='082000', self.closeTime='082459', self.symbol='BTCUSDT', self.open=30025.5, self.close=30004.3, self.high=30048.8, self.low=29975.7, self.vol=2105.3, self.amt=63184743.8436 
127.0.0.1 - - [10/Jul/2023 08:25:00] "POST / HTTP/1.1" 200 -
2023-07-10 08:25:00,812:INFO:sr_min:main.py:172:handleKline:2219263: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5856  20230710   080000    080459  ...         0.0        0.0       0
5857  20230710   080500    080959  ...         0.0        0.0       0
5858  20230710   081000    081459  ...         0.0        0.0       0
5859  20230710   081500    081959  ...         0.0        0.0       0
5860  20230710   082000    082459  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-07-10 08:25:00,813:INFO:sr_min:main.py:175:handleKline:2219263: self.closeSec=1688948699, self.tradeDate='20230710', self.openTime='082000', self.closeTime='082459',self.symbol='BTCUSDT',self.open=30025.5, self.close=30004.3, self.high=30048.8, self.low=29975.7, self.vol=2105.3, self.amt=63184743.8436, ukdf['pct'].iloc[-1]=-0.000606 , ukdf['amount'].iloc[-1]=63184743.8436, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5860, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '37.141', 'enterprice': '26844', 'countrevence': '0', 'unrealprofit': '117376.7023', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '30004.3', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=1


## /root/FIL/strategy/s_rsrs/log.txt ----- -----

719  20230709   200000    235959  1688918399  ...    719  0.307437  0.097427     NaN
720  20230710   000000    035959  1688932799  ...    720  0.299840  0.080464     NaN

[5 rows x 15 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '53.05', 'enterprice': '30750.9', 'countrevence': '0', 'unrealprofit': '-27532.95', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '30231.9', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'numpy.int64'>, curSign=-9223372036854775808, self.sign=1
--handleKline--:  version='2.0.0', self.name='s_rsrs', self.symbol='BTCUSDT', interval='4h', intervalSec=14400, wid=25, thd=0.6, self.sign=1, self.total=1629703.909755, self.flagDict['side']='buy', self.tradeCount=9, self.count=341
self.closeSec=1688947199, self.tradeDate='20230710', self.openTime='040000', self.closeTime='075959', self.symbol='BTCUSDT', self.open=30227.7, self.close=30147.8, self.high=30238.3, self.low=30042.0, self.vol=32675.435, self.amt=984761556.28002 
127.0.0.1 - - [10/Jul/2023 08:00:01] "POST / HTTP/1.1" 200 -
2023-07-10 08:00:01,745:INFO:s_rsrs:main.py:141:handleKline:2218689: self.closeSec=1688947199, self.tradeDate='20230710', self.openTime='040000', self.closeTime='075959',self.symbol='BTCUSDT',self.open=30227.7, self.close=30147.8, self.high=30238.3, self.low=30042.0, self.vol=32675.435, self.amt=984761556.28002 
2023-07-10 08:00:01,769:INFO:s_rsrs:main.py:142:handleKline:2218689: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime  ...        vol           amt       pct
717  20230709   120000    155959  ...  12970.718  3.924279e+08 -0.000912
718  20230709   160000    195959  ...  13831.500  4.185744e+08  0.000241
719  20230709   200000    235959  ...  52366.130  1.586752e+09  0.002627
720  20230710   000000    035959  ...  20913.947  6.328149e+08 -0.003596
721  20230710   040000    075959  ...  32675.435  9.847616e+08 -0.002643

[5 rows x 11 columns]
2023-07-10 08:00:03,234:INFO:s_rsrs:main.py:151:handleKline:2218689: df_s.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec  ...  index      beta    zscore  signal
717  20230709   120000    155959  1688889599  ...    717  0.342819  0.197953     NaN
718  20230709   160000    195959  1688903999  ...    718  0.344940  0.236151     NaN
719  20230709   200000    235959  1688918399  ...    719  0.307437  0.097427     NaN
720  20230710   000000    035959  1688932799  ...    720  0.299840  0.080464     NaN
721  20230710   040000    075959  1688947199  ...    721  0.309598  0.140969     NaN

[5 rows x 15 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '53.05', 'enterprice': '30750.9', 'countrevence': '0', 'unrealprofit': '-31994.455', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '30147.8', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'numpy.int64'>, curSign=-9223372036854775808, self.sign=1


