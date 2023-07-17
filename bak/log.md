# 20230717 08:26:02

## /root/FIL/strategy/amihud/log.txt ----- -----

--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=373746.4768026, self.flagDict['side']='sell', self.tradeCount=2, self.count=18400
self.closeSec=1689553199, self.tradeDate='20230717', self.openTime='081500', self.closeTime='081959', self.symbol='BTCUSDT', self.open=30243.7, self.close=30280.1, self.high=30299.6, self.low=30243.6, self.vol=1235.326, self.amt=37405005.606 
127.0.0.1 - - [17/Jul/2023 08:20:01] "POST / HTTP/1.1" 200 -
2023-07-17 08:20:06,286:INFO:amihud:main.py:172:handleKline:2219019: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5855  20230717   075500    075959  ...         0.0        0.0       0
5856  20230717   080000    080459  ...         0.0        0.0       0
5857  20230717   080500    080959  ...         0.0        0.0       0
5858  20230717   081000    081459  ...         0.0        0.0       0
5859  20230717   081500    081959  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-07-17 08:20:06,304:INFO:amihud:main.py:175:handleKline:2219019: self.closeSec=1689553199, self.tradeDate='20230717', self.openTime='081500', self.closeTime='081959',self.symbol='BTCUSDT',self.open=30243.7, self.close=30280.1, self.high=30299.6, self.low=30243.6, self.vol=1235.326, self.amt=37405005.606, ukdf['pct'].iloc[-1]=0.0012 , ukdf['amount'].iloc[-1]=37405005.606, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5859, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '13.926', 'enterprice': '26864.9', 'countrevence': '0', 'unrealprofit': '-47577.25488498378', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '30281.33364103', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1
127.0.0.1 - - [17/Jul/2023 08:25:00] "POST / HTTP/1.1" 200 -
--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=373746.4768026, self.flagDict['side']='sell', self.tradeCount=2, self.count=18401
self.closeSec=1689553499, self.tradeDate='20230717', self.openTime='082000', self.closeTime='082459', self.symbol='BTCUSDT', self.open=30280.0, self.close=30266.5, self.high=30280.1, self.low=30255.5, self.vol=402.505, self.amt=12183372.0839 
2023-07-17 08:25:00,732:INFO:amihud:main.py:172:handleKline:2219019: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5856  20230717   080000    080459  ...         0.0        0.0       0
5857  20230717   080500    080959  ...         0.0        0.0       0
5858  20230717   081000    081459  ...         0.0        0.0       0
5859  20230717   081500    081959  ...         0.0        0.0       0
5860  20230717   082000    082459  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-07-17 08:25:00,732:INFO:amihud:main.py:175:handleKline:2219019: self.closeSec=1689553499, self.tradeDate='20230717', self.openTime='082000', self.closeTime='082459',self.symbol='BTCUSDT',self.open=30280.0, self.close=30266.5, self.high=30280.1, self.low=30255.5, self.vol=402.505, self.amt=12183372.0839, ukdf['pct'].iloc[-1]=-0.000449 , ukdf['amount'].iloc[-1]=12183372.0839, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5860, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '13.926', 'enterprice': '26864.9', 'countrevence': '0', 'unrealprofit': '-47389.71571292178', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '30267.86680403', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1


## /root/FIL/strategy/factorcheck/log.txt ----- -----


self.closeSec=1689553199, self.tradeDate='20230717', self.openTime='081500', self.closeTime='081959', self.symbol='BTCUSDT', self.open=30243.7, self.close=30280.1, self.high=30299.6, self.low=30243.6 
127.0.0.1 - - [17/Jul/2023 08:20:01] "POST / HTTP/1.1" 200 -
2023-07-17 08:20:04,032:INFO:factorcheck2:main.py:126:handleKline:2218005: self.closeSec=1689553199, self.tradeDate='20230717', self.openTime='081500', self.closeTime='081959',self.symbol='BTCUSDT',self.open=30243.7, self.close=30280.1, self.high=30299.6, self.low=30243.6   
2023-07-17 08:20:05,323:INFO:factorcheck2:main.py:127:handleKline:2218005: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime    closeSec  ...      low       pct  index  idx
1535  20230717   075500    075959  1689551999  ...  30184.7  0.000348   1535    5
1536  20230717   080000    080459  1689552299  ...  30186.5 -0.000781   1536    0
1537  20230717   080500    080959  1689552599  ...  30177.9  0.000301   1537    1
1538  20230717   081000    081459  1689552899  ...  30199.0  0.001374   1538    2
1539  20230717   081500    081959  1689553199  ...  30243.6  0.001200   1539    3

[5 rows x 11 columns]
2023-07-17 08:20:05,342:INFO:factorcheck2:main.py:128:handleKline:2218005: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': True, 'isOpenSell': False, 'isCloseBuy': False, 'isCloseSell': False, 'isOpen': True, 'isClose': False, 'isTrig': True}

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=36, self.factor=0.45679789501623824, self.count=18403 

self.closeSec=1689553499, self.tradeDate='20230717', self.openTime='082000', self.closeTime='082459', self.symbol='BTCUSDT', self.open=30280.0, self.close=30266.5, self.high=30280.1, self.low=30255.5 
127.0.0.1 - - [17/Jul/2023 08:25:00] "POST / HTTP/1.1" 200 -
2023-07-17 08:25:00,722:INFO:factorcheck2:main.py:126:handleKline:2218005: self.closeSec=1689553499, self.tradeDate='20230717', self.openTime='082000', self.closeTime='082459',self.symbol='BTCUSDT',self.open=30280.0, self.close=30266.5, self.high=30280.1, self.low=30255.5   
2023-07-17 08:25:00,746:INFO:factorcheck2:main.py:127:handleKline:2218005: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime    closeSec  ...      low       pct  index  idx
1536  20230717   080000    080459  1689552299  ...  30186.5 -0.000781   1536    0
1537  20230717   080500    080959  1689552599  ...  30177.9  0.000301   1537    1
1538  20230717   081000    081459  1689552899  ...  30199.0  0.001374   1538    2
1539  20230717   081500    081959  1689553199  ...  30243.6  0.001200   1539    3
1540  20230717   082000    082459  1689553499  ...  30255.5 -0.000449   1540    4

[5 rows x 11 columns]
2023-07-17 08:25:00,746:INFO:factorcheck2:main.py:128:handleKline:2218005: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': True, 'isOpenSell': False, 'isCloseBuy': False, 'isCloseSell': False, 'isOpen': True, 'isClose': False, 'isTrig': True}


## /root/FIL/strategy/logic/log.txt ----- -----

2023-07-17 08:00:17,464:DEBUG:logic:main.py:463:getModel:2218526: df_s.iloc[-5:,:] :
          date closeTime     open  ...    alpha58   alpha67   alpha72
5770  20230717    052959  30254.9  ...  53.750000  0.471539  0.338269
5771  20230717    055959  30288.9  ...  53.333333  0.466924  0.344097
5772  20230717    062959  30274.9  ...  53.750000  0.477618  0.347473
5773  20230717    065959  30303.5  ...  53.750000  0.479807  0.351692
5774  20230717    072959  30309.5  ...  53.333333  0.441358  0.380547

[5 rows x 33 columns]
0.5175600739371534
acc is : 0.5175600739371534
2023-07-17 08:00:17,534:INFO:logic:main.py:468:getModel:2218526: df_pred.iloc[-5:,:] :
     pred    prob_0    prob_1  actual  ...       nav  sign  cost_        bm
536     0  0.520236  0.479764       0  ...  1.016058   1.0    0.0  0.990784
537     0  0.507314  0.492686       1  ...  1.017021   1.0    0.0  0.991724
538     0  0.523248  0.476752       1  ...  1.017219   1.0    0.0  0.991917
539     0  0.516521  0.483479       0  ...  1.013185   1.0    0.0  0.987983
540     1  0.470591  0.529409       1  ...  1.014108   1.0    0.0  0.988883

[5 rows x 10 columns]
2023-07-17 08:00:17,545:INFO:logic:main.py:478:getModel:2218526: df_panel.iloc[-5:,:] :
    pred    prob_0    prob_1  actual  ...       nav  sign  cost_        bm
45     0  0.521698  0.478302       0  ...  1.016058   1.0    0.0  0.997690
46     0  0.508270  0.491730       1  ...  1.017021   1.0    0.0  0.995689
47     0  0.523738  0.476262       1  ...  1.017219   1.0    0.0  0.995477
48     0  0.516521  0.483479       0  ...  1.013185   1.0    0.0  0.987983
49     1  0.470591  0.529409       1  ...  1.014108   1.0    0.0  0.988883

[5 rows x 10 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '24.219', 'enterprice': '30360.8', 'countrevence': '0', 'unrealprofit': '-3669.70874521563', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '30209.27810623', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}


## /root/FIL/strategy/modifiedmom/log.txt ----- -----

623  20230717   075000    075959  1689551999  30230.1  30216.8 -0.000440
2023-07-17 08:00:02,150:INFO:modifiedmom:main.py:146:handleKline:2218259: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': True, 'isOpen': False, 'isClose': True, 'isTrig': False}
127.0.0.1 - - [17/Jul/2023 08:10:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=9200 

self.closeSec=1689552599, self.tradeDate='20230717', self.openTime='080000', self.closeTime='080959', self.symbol='BTCUSDT', self.open='30216.9', self.close='30202.3'
2023-07-17 08:10:01,160:INFO:modifiedmom:main.py:144:handleKline:2218259: self.closeSec=1689552599, self.tradeDate='20230717', self.openTime='080000', self.closeTime='080959',self.symbol='BTCUSDT',self.open='30216.9', self.close='30202.3'
2023-07-17 08:10:01,168:INFO:modifiedmom:main.py:145:handleKline:2218259: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec     open    close       pct
620  20230717   072000    072959  1689550199    30283  30189.3 -0.003094
621  20230717   073000    073959  1689550799  30189.4  30206.9  0.000583
622  20230717   074000    074959  1689551399  30206.9  30230.1  0.000768
623  20230717   075000    075959  1689551999  30230.1  30216.8 -0.000440
624  20230717   080000    080959  1689552599  30216.9  30202.3 -0.000480
2023-07-17 08:10:01,168:INFO:modifiedmom:main.py:146:handleKline:2218259: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': True, 'isOpen': False, 'isClose': True, 'isTrig': False}

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=9201 

self.closeSec=1689553199, self.tradeDate='20230717', self.openTime='081000', self.closeTime='081959', self.symbol='BTCUSDT', self.open='30202.4', self.close='30280.1'
127.0.0.1 - - [17/Jul/2023 08:20:04] "POST / HTTP/1.1" 200 -
2023-07-17 08:20:06,914:INFO:modifiedmom:main.py:144:handleKline:2218259: self.closeSec=1689553199, self.tradeDate='20230717', self.openTime='081000', self.closeTime='081959',self.symbol='BTCUSDT',self.open='30202.4', self.close='30280.1'
2023-07-17 08:20:07,614:INFO:modifiedmom:main.py:145:handleKline:2218259: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec     open    close       pct
621  20230717   073000    073959  1689550799  30189.4  30206.9  0.000583
622  20230717   074000    074959  1689551399  30206.9  30230.1  0.000768
623  20230717   075000    075959  1689551999  30230.1  30216.8 -0.000440
624  20230717   080000    080959  1689552599  30216.9  30202.3 -0.000480
625  20230717   081000    081959  1689553199  30202.4  30280.1  0.002576
2023-07-17 08:20:07,614:INFO:modifiedmom:main.py:146:handleKline:2218259: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': True, 'isOpen': False, 'isClose': True, 'isTrig': False}


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

17471  20230717   075000    075959  1689551999  30230.1  30216.8
2023-07-17 08:00:02,147:INFO:pyemd2:main.py:127:handleKline:2217508: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=9203 

self.closeSec=1689552599, self.tradeDate='20230717', self.openTime='080000', self.closeTime='080959', self.symbol='BTCUSDT', self.open='30216.9', self.close='30202.3'
2023-07-17 08:10:01,169:INFO:pyemd2:main.py:125:handleKline:2217508: self.closeSec=1689552599, self.tradeDate='20230717', self.openTime='080000', self.closeTime='080959',self.symbol='BTCUSDT',self.open='30216.9', self.close='30202.3'
127.0.0.1 - - [17/Jul/2023 08:10:01] "POST / HTTP/1.1" 200 -
2023-07-17 08:10:01,176:INFO:pyemd2:main.py:126:handleKline:2217508: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
17468  20230717   072000    072959  1689550199    30283  30189.3
17469  20230717   073000    073959  1689550799  30189.4  30206.9
17470  20230717   074000    074959  1689551399  30206.9  30230.1
17471  20230717   075000    075959  1689551999  30230.1  30216.8
17472  20230717   080000    080959  1689552599  30216.9  30202.3
2023-07-17 08:10:01,176:INFO:pyemd2:main.py:127:handleKline:2217508: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=9204 

self.closeSec=1689553199, self.tradeDate='20230717', self.openTime='081000', self.closeTime='081959', self.symbol='BTCUSDT', self.open='30202.4', self.close='30280.1'
127.0.0.1 - - [17/Jul/2023 08:20:04] "POST / HTTP/1.1" 200 -
2023-07-17 08:20:08,435:INFO:pyemd2:main.py:125:handleKline:2217508: self.closeSec=1689553199, self.tradeDate='20230717', self.openTime='081000', self.closeTime='081959',self.symbol='BTCUSDT',self.open='30202.4', self.close='30280.1'
2023-07-17 08:20:08,667:INFO:pyemd2:main.py:126:handleKline:2217508: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
17469  20230717   073000    073959  1689550799  30189.4  30206.9
17470  20230717   074000    074959  1689551399  30206.9  30230.1
17471  20230717   075000    075959  1689551999  30230.1  30216.8
17472  20230717   080000    080959  1689552599  30216.9  30202.3
17473  20230717   081000    081959  1689553199  30202.4  30280.1
2023-07-17 08:20:08,667:INFO:pyemd2:main.py:127:handleKline:2217508: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}


## /root/FIL/strategy/similarity/log.txt ----- -----

12143  20230717   075000    075959  1689551999  30230.1  30216.8
2023-07-17 08:00:02,152:INFO:testStrategy:main.py:103:handleKline:2217133: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': True, 'isOpenSell': False, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True, 'isCorr': False}
127.0.0.1 - - [17/Jul/2023 08:10:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=9203 

self.closeSec=1689552599, self.tradeDate='20230717', self.openTime='080000', self.closeTime='080959', self.symbol='BTCUSDT', self.open='30216.9', self.close='30202.3'
2023-07-17 08:10:01,161:INFO:testStrategy:main.py:101:handleKline:2217133: self.closeSec=1689552599, self.tradeDate='20230717', self.openTime='080000', self.closeTime='080959',self.symbol='BTCUSDT',self.open='30216.9', self.close='30202.3'
2023-07-17 08:10:01,174:INFO:testStrategy:main.py:102:handleKline:2217133: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
12140  20230717   072000    072959  1689550199    30283  30189.3
12141  20230717   073000    073959  1689550799  30189.4  30206.9
12142  20230717   074000    074959  1689551399  30206.9  30230.1
12143  20230717   075000    075959  1689551999  30230.1  30216.8
12144  20230717   080000    080959  1689552599  30216.9  30202.3
2023-07-17 08:10:01,174:INFO:testStrategy:main.py:103:handleKline:2217133: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': True, 'isOpenSell': False, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True, 'isCorr': False}

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=9204 

self.closeSec=1689553199, self.tradeDate='20230717', self.openTime='081000', self.closeTime='081959', self.symbol='BTCUSDT', self.open='30202.4', self.close='30280.1'
127.0.0.1 - - [17/Jul/2023 08:20:04] "POST / HTTP/1.1" 200 -
2023-07-17 08:20:08,279:INFO:testStrategy:main.py:101:handleKline:2217133: self.closeSec=1689553199, self.tradeDate='20230717', self.openTime='081000', self.closeTime='081959',self.symbol='BTCUSDT',self.open='30202.4', self.close='30280.1'
2023-07-17 08:20:08,530:INFO:testStrategy:main.py:102:handleKline:2217133: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
12141  20230717   073000    073959  1689550799  30189.4  30206.9
12142  20230717   074000    074959  1689551399  30206.9  30230.1
12143  20230717   075000    075959  1689551999  30230.1  30216.8
12144  20230717   080000    080959  1689552599  30216.9  30202.3
12145  20230717   081000    081959  1689553199  30202.4  30280.1
2023-07-17 08:20:08,531:INFO:testStrategy:main.py:103:handleKline:2217133: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': True, 'isOpenSell': False, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True, 'isCorr': False}


## /root/FIL/strategy/sr_min/log.txt ----- -----

--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=1, self.total=996015.990996, self.flagDict['side']='buy', self.tradeCount=1, self.count=18400
self.closeSec=1689553199, self.tradeDate='20230717', self.openTime='081500', self.closeTime='081959', self.symbol='BTCUSDT', self.open=30243.7, self.close=30280.1, self.high=30299.6, self.low=30243.6, self.vol=1235.326, self.amt=37405005.606 
127.0.0.1 - - [17/Jul/2023 08:20:01] "POST / HTTP/1.1" 200 -
2023-07-17 08:20:06,424:INFO:sr_min:main.py:172:handleKline:2219263: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5855  20230717   075500    075959  ...         0.0        0.0       0
5856  20230717   080000    080459  ...         0.0        0.0       0
5857  20230717   080500    080959  ...         0.0        0.0       0
5858  20230717   081000    081459  ...         0.0        0.0       0
5859  20230717   081500    081959  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-07-17 08:20:06,454:INFO:sr_min:main.py:175:handleKline:2219263: self.closeSec=1689553199, self.tradeDate='20230717', self.openTime='081500', self.closeTime='081959',self.symbol='BTCUSDT',self.open=30243.7, self.close=30280.1, self.high=30299.6, self.low=30243.6, self.vol=1235.326, self.amt=37405005.606, ukdf['pct'].iloc[-1]=0.0012 , ukdf['amount'].iloc[-1]=37405005.606, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5859, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '37.141', 'enterprice': '26844', 'countrevence': '0', 'unrealprofit': '127666.00876149523', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '30281.33364103', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=1
127.0.0.1 - - [17/Jul/2023 08:25:00] "POST / HTTP/1.1" 200 -
--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=1, self.total=996015.990996, self.flagDict['side']='buy', self.tradeCount=1, self.count=18401
self.closeSec=1689553499, self.tradeDate='20230717', self.openTime='082000', self.closeTime='082459', self.symbol='BTCUSDT', self.open=30280.0, self.close=30266.5, self.high=30280.1, self.low=30255.5, self.vol=402.505, self.amt=12183372.0839 
2023-07-17 08:25:00,753:INFO:sr_min:main.py:172:handleKline:2219263: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5856  20230717   080000    080459  ...         0.0        0.0       0
5857  20230717   080500    080959  ...         0.0        0.0       0
5858  20230717   081000    081459  ...         0.0        0.0       0
5859  20230717   081500    081959  ...         0.0        0.0       0
5860  20230717   082000    082459  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-07-17 08:25:00,754:INFO:sr_min:main.py:175:handleKline:2219263: self.closeSec=1689553499, self.tradeDate='20230717', self.openTime='082000', self.closeTime='082459',self.symbol='BTCUSDT',self.open=30280.0, self.close=30266.5, self.high=30280.1, self.low=30255.5, self.vol=402.505, self.amt=12183372.0839, ukdf['pct'].iloc[-1]=-0.000449 , ukdf['amount'].iloc[-1]=12183372.0839, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5860, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '37.141', 'enterprice': '26844', 'countrevence': '0', 'unrealprofit': '127165.83696847823', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '30267.86680403', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=1


## /root/FIL/strategy/s_rsrs/log.txt ----- -----

719  20230716   200000    235959  1689523199  ...    719  0.710944  1.318667     1.0
720  20230717   000000    035959  1689537599  ...    720  0.725889  1.344754     1.0

[5 rows x 15 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '52.241', 'enterprice': '30511.1', 'countrevence': '0', 'unrealprofit': '-14208.19153360908', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '30239.12604212', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'numpy.int64'>, curSign=1, self.sign=1
--handleKline--:  version='2.0.0', self.name='s_rsrs', self.symbol='BTCUSDT', interval='4h', intervalSec=14400, wid=25, thd=0.6, self.sign=1, self.total=1592336.4447248997, self.flagDict['side']='buy', self.tradeCount=11, self.count=383
self.closeSec=1689551999, self.tradeDate='20230717', self.openTime='040000', self.closeTime='075959', self.symbol='BTCUSDT', self.open=30239.6, self.close=30216.8, self.high=30349.6, self.low=30110.6, self.vol=25379.658, self.amt=767428146.87912 
127.0.0.1 - - [17/Jul/2023 08:00:01] "POST / HTTP/1.1" 200 -
2023-07-17 08:00:01,731:INFO:s_rsrs:main.py:141:handleKline:2218689: self.closeSec=1689551999, self.tradeDate='20230717', self.openTime='040000', self.closeTime='075959',self.symbol='BTCUSDT',self.open=30239.6, self.close=30216.8, self.high=30349.6, self.low=30110.6, self.vol=25379.658, self.amt=767428146.87912 
2023-07-17 08:00:01,748:INFO:s_rsrs:main.py:142:handleKline:2218689: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime  ...        vol           amt       pct
717  20230716   120000    155959  ...  20092.465  6.069392e+08  0.002615
718  20230716   160000    195959  ...  19595.425  5.935232e+08  0.001342
719  20230716   200000    235959  ...  36284.911  1.101480e+09  0.002390
720  20230717   000000    035959  ...  29423.897  8.914104e+08 -0.004166
721  20230717   040000    075959  ...  25379.658  7.674281e+08 -0.000751

[5 rows x 11 columns]
2023-07-17 08:00:02,522:INFO:s_rsrs:main.py:151:handleKline:2218689: df_s.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec  ...  index      beta    zscore  signal
717  20230716   120000    155959  1689494399  ...    717  0.655815  1.167779     1.0
718  20230716   160000    195959  1689508799  ...    718  0.677478  1.222248     1.0
719  20230716   200000    235959  1689523199  ...    719  0.710944  1.318667     1.0
720  20230717   000000    035959  1689537599  ...    720  0.725889  1.344754     1.0
721  20230717   040000    075959  1689551999  ...    721  0.741507  1.372828     1.0

[5 rows x 15 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '52.241', 'enterprice': '30511.1', 'countrevence': '0', 'unrealprofit': '-15380.19818007463', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '30216.69142857', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'numpy.int64'>, curSign=1, self.sign=1


