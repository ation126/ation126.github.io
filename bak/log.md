# 20230603 08:26:01

## /root/FIL/strategy/amihud/log.txt ----- -----

--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=373746.4768026, self.flagDict['side']='sell', self.tradeCount=2, self.count=5728
self.closeSec=1685751599, self.tradeDate='20230603', self.openTime='081500', self.closeTime='081959', self.symbol='BTCUSDT', self.open=27209.1, self.close=27194.9, self.high=27209.2, self.low=27184.6, self.vol=806.086, self.amt=21920195.139 
127.0.0.1 - - [03/Jun/2023 08:20:01] "POST / HTTP/1.1" 200 -
2023-06-03 08:20:06,341:INFO:amihud:main.py:172:handleKline:2219019: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5855  20230603   075500    075959  ...         0.0        0.0       0
5856  20230603   080000    080459  ...         0.0        0.0       0
5857  20230603   080500    080959  ...         0.0        0.0       0
5858  20230603   081000    081459  ...         0.0        0.0       0
5859  20230603   081500    081959  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-06-03 08:20:06,361:INFO:amihud:main.py:175:handleKline:2219019: self.closeSec=1685751599, self.tradeDate='20230603', self.openTime='081500', self.closeTime='081959',self.symbol='BTCUSDT',self.open=27209.1, self.close=27194.9, self.high=27209.2, self.low=27184.6, self.vol=806.086, self.amt=21920195.139, ukdf['pct'].iloc[-1]=-0.000526 , ukdf['amount'].iloc[-1]=21920195.139, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5859, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '13.926', 'enterprice': '26864.9', 'countrevence': '0', 'unrealprofit': '-4588.617', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '27194.4', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1
127.0.0.1 - - [03/Jun/2023 08:25:00] "POST / HTTP/1.1" 200 -
--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=373746.4768026, self.flagDict['side']='sell', self.tradeCount=2, self.count=5729
self.closeSec=1685751899, self.tradeDate='20230603', self.openTime='082000', self.closeTime='082459', self.symbol='BTCUSDT', self.open=27195.0, self.close=27194.3, self.high=27211.0, self.low=27194.3, self.vol=486.716, self.amt=13239834.4296 
2023-06-03 08:25:00,920:INFO:amihud:main.py:172:handleKline:2219019: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5856  20230603   080000    080459  ...         0.0        0.0       0
5857  20230603   080500    080959  ...         0.0        0.0       0
5858  20230603   081000    081459  ...         0.0        0.0       0
5859  20230603   081500    081959  ...         0.0        0.0       0
5860  20230603   082000    082459  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-06-03 08:25:00,920:INFO:amihud:main.py:175:handleKline:2219019: self.closeSec=1685751899, self.tradeDate='20230603', self.openTime='082000', self.closeTime='082459',self.symbol='BTCUSDT',self.open=27195.0, self.close=27194.3, self.high=27211.0, self.low=27194.3, self.vol=486.716, self.amt=13239834.4296, ukdf['pct'].iloc[-1]=-2.2e-05 , ukdf['amount'].iloc[-1]=13239834.4296, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5860, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '13.926', 'enterprice': '26864.9', 'countrevence': '0', 'unrealprofit': '-4667.67062100834', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '27200.07669259', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1


## /root/FIL/strategy/factorcheck/log.txt ----- -----


self.closeSec=1685751599, self.tradeDate='20230603', self.openTime='081500', self.closeTime='081959', self.symbol='BTCUSDT', self.open=27209.1, self.close=27194.9, self.high=27209.2, self.low=27184.6 
127.0.0.1 - - [03/Jun/2023 08:20:01] "POST / HTTP/1.1" 200 -
2023-06-03 08:20:04,142:INFO:factorcheck2:main.py:126:handleKline:2218005: self.closeSec=1685751599, self.tradeDate='20230603', self.openTime='081500', self.closeTime='081959',self.symbol='BTCUSDT',self.open=27209.1, self.close=27194.9, self.high=27209.2, self.low=27184.6   
2023-06-03 08:20:05,561:INFO:factorcheck2:main.py:127:handleKline:2218005: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime    closeSec  ...      low       pct  index  idx
1535  20230603   075500    075959  1685750399  ...  27219.9  0.000287   1535    5
1536  20230603   080000    080459  1685750699  ...  27206.0 -0.000757   1536    0
1537  20230603   080500    080959  1685750999  ...  27195.9 -0.000415   1537    1
1538  20230603   081000    081459  1685751299  ...  27195.9  0.000489   1538    2
1539  20230603   081500    081959  1685751599  ...  27184.6 -0.000526   1539    3

[5 rows x 11 columns]
2023-06-03 08:20:05,571:INFO:factorcheck2:main.py:128:handleKline:2218005: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': True, 'isOpenSell': False, 'isCloseBuy': False, 'isCloseSell': False, 'isOpen': True, 'isClose': False, 'isTrig': True}
127.0.0.1 - - [03/Jun/2023 08:25:00] "POST / HTTP/1.1" 200 -

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=36, self.factor=0.35308215996363673, self.count=5731 

self.closeSec=1685751899, self.tradeDate='20230603', self.openTime='082000', self.closeTime='082459', self.symbol='BTCUSDT', self.open=27195.0, self.close=27194.3, self.high=27211.0, self.low=27194.3 
2023-06-03 08:25:00,759:INFO:factorcheck2:main.py:126:handleKline:2218005: self.closeSec=1685751899, self.tradeDate='20230603', self.openTime='082000', self.closeTime='082459',self.symbol='BTCUSDT',self.open=27195.0, self.close=27194.3, self.high=27211.0, self.low=27194.3   
2023-06-03 08:25:00,886:INFO:factorcheck2:main.py:127:handleKline:2218005: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime    closeSec  ...      low       pct  index  idx
1536  20230603   080000    080459  1685750699  ...  27206.0 -0.000757   1536    0
1537  20230603   080500    080959  1685750999  ...  27195.9 -0.000415   1537    1
1538  20230603   081000    081459  1685751299  ...  27195.9  0.000489   1538    2
1539  20230603   081500    081959  1685751599  ...  27184.6 -0.000526   1539    3
1540  20230603   082000    082459  1685751899  ...  27194.3 -0.000022   1540    4

[5 rows x 11 columns]
2023-06-03 08:25:00,887:INFO:factorcheck2:main.py:128:handleKline:2218005: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': True, 'isOpenSell': False, 'isCloseBuy': False, 'isCloseSell': False, 'isOpen': True, 'isClose': False, 'isTrig': True}


## /root/FIL/strategy/logic/log.txt ----- -----

2023-06-03 08:00:32,930:DEBUG:logic:main.py:463:getModel:2218526: df_s.iloc[-5:,:] :
          date closeTime     open  ...    alpha58   alpha67   alpha72
5770  20230603    052959  27159.4  ...  47.916667  0.520520  0.234155
5771  20230603    055959  27152.9  ...  47.916667  0.528171  0.230937
5772  20230603    062959  27189.9  ...  47.916667  0.536031  0.223204
5773  20230603    065959  27228.6  ...  47.916667  0.541083  0.213722
5774  20230603    072959  27253.7  ...  47.500000  0.533917  0.209352

[5 rows x 33 columns]
0.512014787430684
acc is : 0.512014787430684
2023-06-03 08:00:33,145:INFO:logic:main.py:468:getModel:2218526: df_pred.iloc[-5:,:] :
     pred    prob_0    prob_1  actual  ...       nav  sign  cost_        bm
536     1  0.494559  0.505441       1  ...  1.022032   1.0    0.0  1.015268
537     0  0.506183  0.493817       1  ...  1.023483   1.0    0.0  1.016710
538     0  0.504024  0.495976       1  ...  1.024423   1.0    0.0  1.017643
539     0  0.503851  0.496149       0  ...  1.023288   1.0    0.0  1.016515
540     1  0.497395  0.502605       1  ...  1.023453   1.0    0.0  1.016680

[5 rows x 10 columns]
2023-06-03 08:00:33,186:INFO:logic:main.py:478:getModel:2218526: df_panel.iloc[-5:,:] :
    pred    prob_0    prob_1  actual  ...       nav  sign  cost_        bm
45     1  0.494485  0.505515       1  ...  1.022032   1.0    0.0  1.012165
46     0  0.506434  0.493566       1  ...  1.023483   1.0    0.0  1.013757
47     0  0.503913  0.496087       1  ...  1.024423   1.0    0.0  1.014559
48     0  0.504019  0.495981       0  ...  1.023288   1.0    0.0  1.016515
49     1  0.497395  0.502605       1  ...  1.023453   1.0    0.0  1.016680

[5 rows x 10 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '27.623', 'enterprice': '26988.6', 'countrevence': '0', 'unrealprofit': '6680.76035810847', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '27230.45498889', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}


## /root/FIL/strategy/modifiedmom/log.txt ----- -----

623  20230603   075000    075959  1685750399  27232.6  27227.8 -0.000173
2023-06-03 08:00:02,331:INFO:modifiedmom:main.py:146:handleKline:2218259: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': True, 'isOpen': False, 'isClose': True, 'isTrig': False}
127.0.0.1 - - [03/Jun/2023 08:10:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=2864 

self.closeSec=1685750999, self.tradeDate='20230603', self.openTime='080000', self.closeTime='080959', self.symbol='BTCUSDT', self.open='27227.8', self.close='27195.9'
2023-06-03 08:10:01,180:INFO:modifiedmom:main.py:144:handleKline:2218259: self.closeSec=1685750999, self.tradeDate='20230603', self.openTime='080000', self.closeTime='080959',self.symbol='BTCUSDT',self.open='27227.8', self.close='27195.9'
2023-06-03 08:10:01,241:INFO:modifiedmom:main.py:145:handleKline:2218259: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec     open    close       pct
620  20230603   072000    072959  1685748599    27230  27223.4 -0.000242
621  20230603   073000    073959  1685749199  27223.4  27226.4  0.000110
622  20230603   074000    074959  1685749799  27226.3  27232.5  0.000224
623  20230603   075000    075959  1685750399  27232.6  27227.8 -0.000173
624  20230603   080000    080959  1685750999  27227.8  27195.9 -0.001172
2023-06-03 08:10:01,241:INFO:modifiedmom:main.py:146:handleKline:2218259: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': True, 'isOpen': False, 'isClose': True, 'isTrig': False}

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=2865 

self.closeSec=1685751599, self.tradeDate='20230603', self.openTime='081000', self.closeTime='081959', self.symbol='BTCUSDT', self.open='27195.9', self.close='27194.9'
127.0.0.1 - - [03/Jun/2023 08:20:04] "POST / HTTP/1.1" 200 -
2023-06-03 08:20:06,602:INFO:modifiedmom:main.py:144:handleKline:2218259: self.closeSec=1685751599, self.tradeDate='20230603', self.openTime='081000', self.closeTime='081959',self.symbol='BTCUSDT',self.open='27195.9', self.close='27194.9'
2023-06-03 08:20:07,231:INFO:modifiedmom:main.py:145:handleKline:2218259: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec     open    close       pct
621  20230603   073000    073959  1685749199  27223.4  27226.4  0.000110
622  20230603   074000    074959  1685749799  27226.3  27232.5  0.000224
623  20230603   075000    075959  1685750399  27232.6  27227.8 -0.000173
624  20230603   080000    080959  1685750999  27227.8  27195.9 -0.001172
625  20230603   081000    081959  1685751599  27195.9  27194.9 -0.000037
2023-06-03 08:20:07,231:INFO:modifiedmom:main.py:146:handleKline:2218259: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': True, 'isOpen': False, 'isClose': True, 'isTrig': False}


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

17471  20230603   075000    075959  1685750399  27232.6  27227.8
2023-06-03 08:00:02,277:INFO:pyemd2:main.py:127:handleKline:2217508: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}
127.0.0.1 - - [03/Jun/2023 08:10:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=2867 

self.closeSec=1685750999, self.tradeDate='20230603', self.openTime='080000', self.closeTime='080959', self.symbol='BTCUSDT', self.open='27227.8', self.close='27195.9'
2023-06-03 08:10:01,215:INFO:pyemd2:main.py:125:handleKline:2217508: self.closeSec=1685750999, self.tradeDate='20230603', self.openTime='080000', self.closeTime='080959',self.symbol='BTCUSDT',self.open='27227.8', self.close='27195.9'
2023-06-03 08:10:01,253:INFO:pyemd2:main.py:126:handleKline:2217508: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
17468  20230603   072000    072959  1685748599    27230  27223.4
17469  20230603   073000    073959  1685749199  27223.4  27226.4
17470  20230603   074000    074959  1685749799  27226.3  27232.5
17471  20230603   075000    075959  1685750399  27232.6  27227.8
17472  20230603   080000    080959  1685750999  27227.8  27195.9
2023-06-03 08:10:01,254:INFO:pyemd2:main.py:127:handleKline:2217508: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=2868 

self.closeSec=1685751599, self.tradeDate='20230603', self.openTime='081000', self.closeTime='081959', self.symbol='BTCUSDT', self.open='27195.9', self.close='27194.9'
127.0.0.1 - - [03/Jun/2023 08:20:04] "POST / HTTP/1.1" 200 -
2023-06-03 08:20:08,084:INFO:pyemd2:main.py:125:handleKline:2217508: self.closeSec=1685751599, self.tradeDate='20230603', self.openTime='081000', self.closeTime='081959',self.symbol='BTCUSDT',self.open='27195.9', self.close='27194.9'
2023-06-03 08:20:08,215:INFO:pyemd2:main.py:126:handleKline:2217508: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
17469  20230603   073000    073959  1685749199  27223.4  27226.4
17470  20230603   074000    074959  1685749799  27226.3  27232.5
17471  20230603   075000    075959  1685750399  27232.6  27227.8
17472  20230603   080000    080959  1685750999  27227.8  27195.9
17473  20230603   081000    081959  1685751599  27195.9  27194.9
2023-06-03 08:20:08,216:INFO:pyemd2:main.py:127:handleKline:2217508: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}


## /root/FIL/strategy/similarity/log.txt ----- -----

12143  20230603   075000    075959  1685750399  27232.6  27227.8
2023-06-03 08:00:02,352:INFO:testStrategy:main.py:103:handleKline:2217133: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': True, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True, 'isCorr': False}
127.0.0.1 - - [03/Jun/2023 08:10:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=2867 

self.closeSec=1685750999, self.tradeDate='20230603', self.openTime='080000', self.closeTime='080959', self.symbol='BTCUSDT', self.open='27227.8', self.close='27195.9'
2023-06-03 08:10:01,204:INFO:testStrategy:main.py:101:handleKline:2217133: self.closeSec=1685750999, self.tradeDate='20230603', self.openTime='080000', self.closeTime='080959',self.symbol='BTCUSDT',self.open='27227.8', self.close='27195.9'
2023-06-03 08:10:01,248:INFO:testStrategy:main.py:102:handleKline:2217133: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
12140  20230603   072000    072959  1685748599    27230  27223.4
12141  20230603   073000    073959  1685749199  27223.4  27226.4
12142  20230603   074000    074959  1685749799  27226.3  27232.5
12143  20230603   075000    075959  1685750399  27232.6  27227.8
12144  20230603   080000    080959  1685750999  27227.8  27195.9
2023-06-03 08:10:01,248:INFO:testStrategy:main.py:103:handleKline:2217133: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': True, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True, 'isCorr': False}

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=2868 

self.closeSec=1685751599, self.tradeDate='20230603', self.openTime='081000', self.closeTime='081959', self.symbol='BTCUSDT', self.open='27195.9', self.close='27194.9'
127.0.0.1 - - [03/Jun/2023 08:20:04] "POST / HTTP/1.1" 200 -
2023-06-03 08:20:07,802:INFO:testStrategy:main.py:101:handleKline:2217133: self.closeSec=1685751599, self.tradeDate='20230603', self.openTime='081000', self.closeTime='081959',self.symbol='BTCUSDT',self.open='27195.9', self.close='27194.9'
2023-06-03 08:20:08,022:INFO:testStrategy:main.py:102:handleKline:2217133: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
12141  20230603   073000    073959  1685749199  27223.4  27226.4
12142  20230603   074000    074959  1685749799  27226.3  27232.5
12143  20230603   075000    075959  1685750399  27232.6  27227.8
12144  20230603   080000    080959  1685750999  27227.8  27195.9
12145  20230603   081000    081959  1685751599  27195.9  27194.9
2023-06-03 08:20:08,023:INFO:testStrategy:main.py:103:handleKline:2217133: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': True, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True, 'isCorr': False}


## /root/FIL/strategy/sr_min/log.txt ----- -----

--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=1, self.total=996015.990996, self.flagDict['side']='buy', self.tradeCount=1, self.count=5728
self.closeSec=1685751599, self.tradeDate='20230603', self.openTime='081500', self.closeTime='081959', self.symbol='BTCUSDT', self.open=27209.1, self.close=27194.9, self.high=27209.2, self.low=27184.6, self.vol=806.086, self.amt=21920195.139 
127.0.0.1 - - [03/Jun/2023 08:20:01] "POST / HTTP/1.1" 200 -
2023-06-03 08:20:06,341:INFO:sr_min:main.py:172:handleKline:2219263: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5855  20230603   075500    075959  ...         0.0        0.0       0
5856  20230603   080000    080459  ...         0.0        0.0       0
5857  20230603   080500    080959  ...         0.0        0.0       0
5858  20230603   081000    081459  ...         0.0        0.0       0
5859  20230603   081500    081959  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-06-03 08:20:06,352:INFO:sr_min:main.py:175:handleKline:2219263: self.closeSec=1685751599, self.tradeDate='20230603', self.openTime='081500', self.closeTime='081959',self.symbol='BTCUSDT',self.open=27209.1, self.close=27194.9, self.high=27209.2, self.low=27184.6, self.vol=806.086, self.amt=21920195.139, ukdf['pct'].iloc[-1]=-0.000526 , ukdf['amount'].iloc[-1]=21920195.139, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5859, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '37.141', 'enterprice': '26844', 'countrevence': '0', 'unrealprofit': '13014.2064', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '27194.4', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=1
127.0.0.1 - - [03/Jun/2023 08:25:00] "POST / HTTP/1.1" 200 -
--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=1, self.total=996015.990996, self.flagDict['side']='buy', self.tradeCount=1, self.count=5729
self.closeSec=1685751899, self.tradeDate='20230603', self.openTime='082000', self.closeTime='082459', self.symbol='BTCUSDT', self.open=27195.0, self.close=27194.3, self.high=27211.0, self.low=27194.3, self.vol=486.716, self.amt=13239834.4296 
2023-06-03 08:25:00,921:INFO:sr_min:main.py:172:handleKline:2219263: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5856  20230603   080000    080459  ...         0.0        0.0       0
5857  20230603   080500    080959  ...         0.0        0.0       0
5858  20230603   081000    081459  ...         0.0        0.0       0
5859  20230603   081500    081959  ...         0.0        0.0       0
5860  20230603   082000    082459  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-06-03 08:25:00,923:INFO:sr_min:main.py:175:handleKline:2219263: self.closeSec=1685751899, self.tradeDate='20230603', self.openTime='082000', self.closeTime='082459',self.symbol='BTCUSDT',self.open=27195.0, self.close=27194.3, self.high=27211.0, self.low=27194.3, self.vol=486.716, self.amt=13239834.4296, ukdf['pct'].iloc[-1]=-2.2e-05 , ukdf['amount'].iloc[-1]=13239834.4296, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5860, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '37.141', 'enterprice': '26844', 'countrevence': '0', 'unrealprofit': '13225.04443948519', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '27200.07669259', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=1


## /root/FIL/strategy/s_rsrs/log.txt ----- -----

719  20230602   200000    235959  1685721599  ...    719  0.666727  0.377153     NaN
720  20230603   000000    035959  1685735999  ...    720  0.645171  0.301626     NaN

[5 rows x 15 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '55.249', 'enterprice': '26128.2', 'countrevence': '0', 'unrealprofit': '61033.5703', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '27232.9', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'numpy.int64'>, curSign=-9223372036854775808, self.sign=1
127.0.0.1 - - [03/Jun/2023 08:00:01] "POST / HTTP/1.1" 200 -
--handleKline--:  version='2.0.0', self.name='s_rsrs', self.symbol='BTCUSDT', interval='4h', intervalSec=14400, wid=25, thd=0.6, self.sign=1, self.total=1442113.3648782002, self.flagDict['side']='buy', self.tradeCount=3, self.count=119
self.closeSec=1685750399, self.tradeDate='20230603', self.openTime='040000', self.closeTime='075959', self.symbol='BTCUSDT', self.open=27231.5, self.close=27227.8, self.high=27290.0, self.low=27132.0, self.vol=30013.032, self.amt=816771297.4238 
2023-06-03 08:00:01,874:INFO:s_rsrs:main.py:141:handleKline:2218689: self.closeSec=1685750399, self.tradeDate='20230603', self.openTime='040000', self.closeTime='075959',self.symbol='BTCUSDT',self.open=27231.5, self.close=27227.8, self.high=27290.0, self.low=27132.0, self.vol=30013.032, self.amt=816771297.4238 
2023-06-03 08:00:01,917:INFO:s_rsrs:main.py:142:handleKline:2218689: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime  ...         vol           amt       pct
717  20230602   120000    155959  ...   61632.613  1.669195e+09  0.001971
718  20230602   160000    195959  ...   36192.899  9.809580e+08  0.002966
719  20230602   200000    235959  ...  120542.039  3.257226e+09 -0.001372
720  20230603   000000    035959  ...   57272.534  1.553672e+09  0.005550
721  20230603   040000    075959  ...   30013.032  8.167713e+08 -0.000140

[5 rows x 11 columns]
2023-06-03 08:00:03,943:INFO:s_rsrs:main.py:151:handleKline:2218689: df_s.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec  ...  index      beta    zscore  signal
717  20230602   120000    155959  1685692799  ...    717  0.670010  0.405017     NaN
718  20230602   160000    195959  1685707199  ...    718  0.673301  0.405992     NaN
719  20230602   200000    235959  1685721599  ...    719  0.666727  0.377153     NaN
720  20230603   000000    035959  1685735999  ...    720  0.645171  0.301626     NaN
721  20230603   040000    075959  1685750399  ...    721  0.642910  0.283739     NaN

[5 rows x 15 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '55.249', 'enterprice': '26128.2', 'countrevence': '0', 'unrealprofit': '61086.24060430657', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '27233.85332593', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'numpy.int64'>, curSign=-9223372036854775808, self.sign=1


