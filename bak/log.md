# 20230620 08:26:01

## /root/FIL/strategy/amihud/log.txt ----- -----

--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=373746.4768026, self.flagDict['side']='sell', self.tradeCount=2, self.count=10624
self.closeSec=1687220399, self.tradeDate='20230620', self.openTime='081500', self.closeTime='081959', self.symbol='BTCUSDT', self.open=26795.8, self.close=26813.3, self.high=26823.9, self.low=26782.6, self.vol=675.509, self.amt=18101016.8641 
127.0.0.1 - - [20/Jun/2023 08:20:01] "POST / HTTP/1.1" 200 -
2023-06-20 08:20:07,711:INFO:amihud:main.py:172:handleKline:2219019: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5855  20230620   075500    075959  ...         0.0        0.0       0
5856  20230620   080000    080459  ...         0.0        0.0       0
5857  20230620   080500    080959  ...         0.0        0.0       0
5858  20230620   081000    081459  ...         0.0        0.0       0
5859  20230620   081500    081959  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-06-20 08:20:07,733:INFO:amihud:main.py:175:handleKline:2219019: self.closeSec=1687220399, self.tradeDate='20230620', self.openTime='081500', self.closeTime='081959',self.symbol='BTCUSDT',self.open=26795.8, self.close=26813.3, self.high=26823.9, self.low=26782.6, self.vol=675.509, self.amt=18101016.8641, ukdf['pct'].iloc[-1]=0.000649 , ukdf['amount'].iloc[-1]=18101016.8641, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5859, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '13.926', 'enterprice': '26864.9', 'countrevence': '0', 'unrealprofit': '741.36803031192', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '26811.66374908', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1
--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=373746.4768026, self.flagDict['side']='sell', self.tradeCount=2, self.count=10625
self.closeSec=1687220699, self.tradeDate='20230620', self.openTime='082000', self.closeTime='082459', self.symbol='BTCUSDT', self.open=26813.3, self.close=26902.6, self.high=27000.0, self.low=26805.2, self.vol=7879.91, self.amt=212087033.8804 
127.0.0.1 - - [20/Jun/2023 08:25:00] "POST / HTTP/1.1" 200 -
2023-06-20 08:25:00,790:INFO:amihud:main.py:172:handleKline:2219019: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5856  20230620   080000    080459  ...         0.0        0.0       0
5857  20230620   080500    080959  ...         0.0        0.0       0
5858  20230620   081000    081459  ...         0.0        0.0       0
5859  20230620   081500    081959  ...         0.0        0.0       0
5860  20230620   082000    082459  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-06-20 08:25:00,791:INFO:amihud:main.py:175:handleKline:2219019: self.closeSec=1687220699, self.tradeDate='20230620', self.openTime='082000', self.closeTime='082459',self.symbol='BTCUSDT',self.open=26813.3, self.close=26902.6, self.high=27000.0, self.low=26805.2, self.vol=7879.91, self.amt=212087033.8804, ukdf['pct'].iloc[-1]=0.00333 , ukdf['amount'].iloc[-1]=212087033.8804, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5860, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '13.926', 'enterprice': '26864.9', 'countrevence': '0', 'unrealprofit': '-633.633', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '26910.4', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1


## /root/FIL/strategy/factorcheck/log.txt ----- -----


self.closeSec=1687220399, self.tradeDate='20230620', self.openTime='081500', self.closeTime='081959', self.symbol='BTCUSDT', self.open=26795.8, self.close=26813.3, self.high=26823.9, self.low=26782.6 
127.0.0.1 - - [20/Jun/2023 08:20:01] "POST / HTTP/1.1" 200 -
2023-06-20 08:20:04,831:INFO:factorcheck2:main.py:126:handleKline:2218005: self.closeSec=1687220399, self.tradeDate='20230620', self.openTime='081500', self.closeTime='081959',self.symbol='BTCUSDT',self.open=26795.8, self.close=26813.3, self.high=26823.9, self.low=26782.6   
2023-06-20 08:20:06,551:INFO:factorcheck2:main.py:127:handleKline:2218005: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime    closeSec  ...      low       pct  index  idx
1535  20230620   075500    075959  1687219199  ...  26776.0  0.001964   1535    5
1536  20230620   080000    080459  1687219499  ...  26790.2 -0.001189   1536    0
1537  20230620   080500    080959  1687219799  ...  26788.9 -0.000078   1537    1
1538  20230620   081000    081459  1687220099  ...  26787.2  0.000049   1538    2
1539  20230620   081500    081959  1687220399  ...  26782.6  0.000649   1539    3

[5 rows x 11 columns]
2023-06-20 08:20:06,561:INFO:factorcheck2:main.py:128:handleKline:2218005: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}
127.0.0.1 - - [20/Jun/2023 08:25:00] "POST / HTTP/1.1" 200 -

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=149, self.factor=0.42378250950959073, self.count=10627 

self.closeSec=1687220699, self.tradeDate='20230620', self.openTime='082000', self.closeTime='082459', self.symbol='BTCUSDT', self.open=26813.3, self.close=26902.6, self.high=27000.0, self.low=26805.2 
2023-06-20 08:25:00,728:INFO:factorcheck2:main.py:126:handleKline:2218005: self.closeSec=1687220699, self.tradeDate='20230620', self.openTime='082000', self.closeTime='082459',self.symbol='BTCUSDT',self.open=26813.3, self.close=26902.6, self.high=27000.0, self.low=26805.2   
2023-06-20 08:25:00,768:INFO:factorcheck2:main.py:127:handleKline:2218005: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime    closeSec  ...      low       pct  index  idx
1536  20230620   080000    080459  1687219499  ...  26790.2 -0.001189   1536    0
1537  20230620   080500    080959  1687219799  ...  26788.9 -0.000078   1537    1
1538  20230620   081000    081459  1687220099  ...  26787.2  0.000049   1538    2
1539  20230620   081500    081959  1687220399  ...  26782.6  0.000649   1539    3
1540  20230620   082000    082459  1687220699  ...  26805.2  0.003330   1540    4

[5 rows x 11 columns]
2023-06-20 08:25:00,768:INFO:factorcheck2:main.py:128:handleKline:2218005: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}


## /root/FIL/strategy/logic/log.txt ----- -----

2023-06-20 08:00:17,902:DEBUG:logic:main.py:463:getModel:2218526: df_s.iloc[-5:,:] :
          date closeTime     open  ...    alpha58   alpha67   alpha72
5770  20230620    052959  26711.6  ...  53.750000  0.546972  0.478960
5771  20230620    055959  26670.1  ...  53.750000  0.563460  0.474054
5772  20230620    062959  26758.6  ...  54.166667  0.569618  0.466602
5773  20230620    065959  26792.0  ...  54.166667  0.558148  0.463748
5774  20230620    072959  26743.5  ...  54.166667  0.562237  0.459220

[5 rows x 33 columns]
0.5600739371534196
acc is : 0.5600739371534196
2023-06-20 08:00:18,011:INFO:logic:main.py:468:getModel:2218526: df_pred.iloc[-5:,:] :
     pred    prob_0    prob_1  actual  ...       nav  sign  cost_        bm
536     0  0.508097  0.491903       1  ...  1.023547  -1.0    0.0  1.009984
537     0  0.521257  0.478743       1  ...  1.022251  -1.0    0.0  1.011263
538     0  0.512895  0.487105       0  ...  1.024097  -1.0    0.0  1.009436
539     1  0.489425  0.510575       1  ...  1.023255  -1.0    0.0  1.010267
540     0  0.506062  0.493938       1  ...  1.020846  -1.0    0.0  1.012645

[5 rows x 10 columns]
2023-06-20 08:00:18,039:INFO:logic:main.py:478:getModel:2218526: df_panel.iloc[-5:,:] :
    pred    prob_0    prob_1  actual  ...       nav  sign  cost_        bm
45     0  0.508130  0.491870       1  ...  1.023547  -1.0    0.0  1.001947
46     0  0.521079  0.478921       1  ...  1.022251  -1.0    0.0  1.007540
47     0  0.513014  0.486986       0  ...  1.024097  -1.0    0.0  1.009650
48     1  0.489425  0.510575       1  ...  1.023255  -1.0    0.0  1.010267
49     0  0.506062  0.493938       1  ...  1.020846  -1.0    0.0  1.012645

[5 rows x 10 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '28.089', 'enterprice': '26626.6', 'countrevence': '0', 'unrealprofit': '-5894.7892440543', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '26836.4611287', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}


## /root/FIL/strategy/modifiedmom/log.txt ----- -----

623  20230620   075000    075959  1687219199  26766.3  26828.5  0.002324
2023-06-20 08:00:01,984:INFO:modifiedmom:main.py:146:handleKline:2218259: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': True, 'isOpen': False, 'isClose': True, 'isTrig': False}
127.0.0.1 - - [20/Jun/2023 08:10:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=5312 

self.closeSec=1687219799, self.tradeDate='20230620', self.openTime='080000', self.closeTime='080959', self.symbol='BTCUSDT', self.open='26828.6', self.close='26794.6'
2023-06-20 08:10:01,075:INFO:modifiedmom:main.py:144:handleKline:2218259: self.closeSec=1687219799, self.tradeDate='20230620', self.openTime='080000', self.closeTime='080959',self.symbol='BTCUSDT',self.open='26828.6', self.close='26794.6'
2023-06-20 08:10:01,123:INFO:modifiedmom:main.py:145:handleKline:2218259: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec     open    close       pct
620  20230620   072000    072959  1687217399    26728    26764  0.001343
621  20230620   073000    073959  1687217999  26764.1  26755.1 -0.000333
622  20230620   074000    074959  1687218599  26755.1  26766.3  0.000419
623  20230620   075000    075959  1687219199  26766.3  26828.5  0.002324
624  20230620   080000    080959  1687219799  26828.6  26794.6 -0.001264
2023-06-20 08:10:01,123:INFO:modifiedmom:main.py:146:handleKline:2218259: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': True, 'isOpen': False, 'isClose': True, 'isTrig': False}

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=5313 

self.closeSec=1687220399, self.tradeDate='20230620', self.openTime='081000', self.closeTime='081959', self.symbol='BTCUSDT', self.open='26794.6', self.close='26813.3'
127.0.0.1 - - [20/Jun/2023 08:20:04] "POST / HTTP/1.1" 200 -
2023-06-20 08:20:07,391:INFO:modifiedmom:main.py:144:handleKline:2218259: self.closeSec=1687220399, self.tradeDate='20230620', self.openTime='081000', self.closeTime='081959',self.symbol='BTCUSDT',self.open='26794.6', self.close='26813.3'
2023-06-20 08:20:08,280:INFO:modifiedmom:main.py:145:handleKline:2218259: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec     open    close       pct
621  20230620   073000    073959  1687217999  26764.1  26755.1 -0.000333
622  20230620   074000    074959  1687218599  26755.1  26766.3  0.000419
623  20230620   075000    075959  1687219199  26766.3  26828.5  0.002324
624  20230620   080000    080959  1687219799  26828.6  26794.6 -0.001264
625  20230620   081000    081959  1687220399  26794.6  26813.3  0.000698
2023-06-20 08:20:08,281:INFO:modifiedmom:main.py:146:handleKline:2218259: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': True, 'isOpen': False, 'isClose': True, 'isTrig': False}


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

17471  20230620   075000    075959  1687219199  26766.3  26828.5
2023-06-20 08:00:01,992:INFO:pyemd2:main.py:127:handleKline:2217508: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}
127.0.0.1 - - [20/Jun/2023 08:10:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=5315 

self.closeSec=1687219799, self.tradeDate='20230620', self.openTime='080000', self.closeTime='080959', self.symbol='BTCUSDT', self.open='26828.6', self.close='26794.6'
2023-06-20 08:10:01,081:INFO:pyemd2:main.py:125:handleKline:2217508: self.closeSec=1687219799, self.tradeDate='20230620', self.openTime='080000', self.closeTime='080959',self.symbol='BTCUSDT',self.open='26828.6', self.close='26794.6'
2023-06-20 08:10:01,130:INFO:pyemd2:main.py:126:handleKline:2217508: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
17468  20230620   072000    072959  1687217399    26728    26764
17469  20230620   073000    073959  1687217999  26764.1  26755.1
17470  20230620   074000    074959  1687218599  26755.1  26766.3
17471  20230620   075000    075959  1687219199  26766.3  26828.5
17472  20230620   080000    080959  1687219799  26828.6  26794.6
2023-06-20 08:10:01,131:INFO:pyemd2:main.py:127:handleKline:2217508: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=5316 

self.closeSec=1687220399, self.tradeDate='20230620', self.openTime='081000', self.closeTime='081959', self.symbol='BTCUSDT', self.open='26794.6', self.close='26813.3'
127.0.0.1 - - [20/Jun/2023 08:20:04] "POST / HTTP/1.1" 200 -
2023-06-20 08:20:09,493:INFO:pyemd2:main.py:125:handleKline:2217508: self.closeSec=1687220399, self.tradeDate='20230620', self.openTime='081000', self.closeTime='081959',self.symbol='BTCUSDT',self.open='26794.6', self.close='26813.3'
2023-06-20 08:20:09,631:INFO:pyemd2:main.py:126:handleKline:2217508: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
17469  20230620   073000    073959  1687217999  26764.1  26755.1
17470  20230620   074000    074959  1687218599  26755.1  26766.3
17471  20230620   075000    075959  1687219199  26766.3  26828.5
17472  20230620   080000    080959  1687219799  26828.6  26794.6
17473  20230620   081000    081959  1687220399  26794.6  26813.3
2023-06-20 08:20:09,631:INFO:pyemd2:main.py:127:handleKline:2217508: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}


## /root/FIL/strategy/similarity/log.txt ----- -----

12143  20230620   075000    075959  1687219199  26766.3  26828.5
2023-06-20 08:00:02,016:INFO:testStrategy:main.py:103:handleKline:2217133: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': True, 'isOpenSell': False, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True, 'isCorr': False}
127.0.0.1 - - [20/Jun/2023 08:10:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=5315 

self.closeSec=1687219799, self.tradeDate='20230620', self.openTime='080000', self.closeTime='080959', self.symbol='BTCUSDT', self.open='26828.6', self.close='26794.6'
2023-06-20 08:10:01,122:INFO:testStrategy:main.py:101:handleKline:2217133: self.closeSec=1687219799, self.tradeDate='20230620', self.openTime='080000', self.closeTime='080959',self.symbol='BTCUSDT',self.open='26828.6', self.close='26794.6'
2023-06-20 08:10:01,127:INFO:testStrategy:main.py:102:handleKline:2217133: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
12140  20230620   072000    072959  1687217399    26728    26764
12141  20230620   073000    073959  1687217999  26764.1  26755.1
12142  20230620   074000    074959  1687218599  26755.1  26766.3
12143  20230620   075000    075959  1687219199  26766.3  26828.5
12144  20230620   080000    080959  1687219799  26828.6  26794.6
2023-06-20 08:10:01,128:INFO:testStrategy:main.py:103:handleKline:2217133: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': True, 'isOpenSell': False, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True, 'isCorr': False}

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=5316 

self.closeSec=1687220399, self.tradeDate='20230620', self.openTime='081000', self.closeTime='081959', self.symbol='BTCUSDT', self.open='26794.6', self.close='26813.3'
127.0.0.1 - - [20/Jun/2023 08:20:04] "POST / HTTP/1.1" 200 -
2023-06-20 08:20:09,102:INFO:testStrategy:main.py:101:handleKline:2217133: self.closeSec=1687220399, self.tradeDate='20230620', self.openTime='081000', self.closeTime='081959',self.symbol='BTCUSDT',self.open='26794.6', self.close='26813.3'
2023-06-20 08:20:09,411:INFO:testStrategy:main.py:102:handleKline:2217133: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
12141  20230620   073000    073959  1687217999  26764.1  26755.1
12142  20230620   074000    074959  1687218599  26755.1  26766.3
12143  20230620   075000    075959  1687219199  26766.3  26828.5
12144  20230620   080000    080959  1687219799  26828.6  26794.6
12145  20230620   081000    081959  1687220399  26794.6  26813.3
2023-06-20 08:20:09,411:INFO:testStrategy:main.py:103:handleKline:2217133: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': True, 'isOpenSell': False, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True, 'isCorr': False}


## /root/FIL/strategy/sr_min/log.txt ----- -----

--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=1, self.total=996015.990996, self.flagDict['side']='buy', self.tradeCount=1, self.count=10624
self.closeSec=1687220399, self.tradeDate='20230620', self.openTime='081500', self.closeTime='081959', self.symbol='BTCUSDT', self.open=26795.8, self.close=26813.3, self.high=26823.9, self.low=26782.6, self.vol=675.509, self.amt=18101016.8641 
127.0.0.1 - - [20/Jun/2023 08:20:01] "POST / HTTP/1.1" 200 -
2023-06-20 08:20:07,712:INFO:sr_min:main.py:172:handleKline:2219263: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5855  20230620   075500    075959  ...         0.0        0.0       0
5856  20230620   080000    080459  ...         0.0        0.0       0
5857  20230620   080500    080959  ...         0.0        0.0       0
5858  20230620   081000    081459  ...         0.0        0.0       0
5859  20230620   081500    081959  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-06-20 08:20:07,742:INFO:sr_min:main.py:175:handleKline:2219263: self.closeSec=1687220399, self.tradeDate='20230620', self.openTime='081500', self.closeTime='081959',self.symbol='BTCUSDT',self.open=26795.8, self.close=26813.3, self.high=26823.9, self.low=26782.6, self.vol=675.509, self.amt=18101016.8641, ukdf['pct'].iloc[-1]=0.000649 , ukdf['amount'].iloc[-1]=18101016.8641, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5859, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '37.141', 'enterprice': '26844', 'countrevence': '0', 'unrealprofit': '-1201.00069541972', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '26811.66374908', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=1
--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=1, self.total=996015.990996, self.flagDict['side']='buy', self.tradeCount=1, self.count=10625
self.closeSec=1687220699, self.tradeDate='20230620', self.openTime='082000', self.closeTime='082459', self.symbol='BTCUSDT', self.open=26813.3, self.close=26902.6, self.high=27000.0, self.low=26805.2, self.vol=7879.91, self.amt=212087033.8804 
127.0.0.1 - - [20/Jun/2023 08:25:00] "POST / HTTP/1.1" 200 -
2023-06-20 08:25:00,789:INFO:sr_min:main.py:172:handleKline:2219263: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5856  20230620   080000    080459  ...         0.0        0.0       0
5857  20230620   080500    080959  ...         0.0        0.0       0
5858  20230620   081000    081459  ...         0.0        0.0       0
5859  20230620   081500    081959  ...         0.0        0.0       0
5860  20230620   082000    082459  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-06-20 08:25:00,790:INFO:sr_min:main.py:175:handleKline:2219263: self.closeSec=1687220699, self.tradeDate='20230620', self.openTime='082000', self.closeTime='082459',self.symbol='BTCUSDT',self.open=26813.3, self.close=26902.6, self.high=27000.0, self.low=26805.2, self.vol=7879.91, self.amt=212087033.8804, ukdf['pct'].iloc[-1]=0.00333 , ukdf['amount'].iloc[-1]=212087033.8804, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5860, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '37.141', 'enterprice': '26844', 'countrevence': '0', 'unrealprofit': '2466.1624', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '26910.4', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=1


## /root/FIL/strategy/s_rsrs/log.txt ----- -----

719  20230619   200000    235959  1687190399  ...    719  0.568553  0.797705     1.0
720  20230620   000000    035959  1687204799  ...    720  0.473511  0.256385     NaN

[5 rows x 15 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '57.175', 'enterprice': '26590', 'countrevence': '0', 'unrealprofit': '5134.315', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '26679.8', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'numpy.int64'>, curSign=-9223372036854775808, self.sign=1
127.0.0.1 - - [20/Jun/2023 08:00:01] "POST / HTTP/1.1" 200 -
--handleKline--:  version='2.0.0', self.name='s_rsrs', self.symbol='BTCUSDT', interval='4h', intervalSec=14400, wid=25, thd=0.6, self.sign=1, self.total=1518762.96675, self.flagDict['side']='buy', self.tradeCount=5, self.count=221
self.closeSec=1687219199, self.tradeDate='20230620', self.openTime='040000', self.closeTime='075959', self.symbol='BTCUSDT', self.open=26672.8, self.close=26828.6, self.high=26852.8, self.low=26638.9, self.vol=57994.516, self.amt=1551427182.12312 
2023-06-20 08:00:01,573:INFO:s_rsrs:main.py:141:handleKline:2218689: self.closeSec=1687219199, self.tradeDate='20230620', self.openTime='040000', self.closeTime='075959',self.symbol='BTCUSDT',self.open=26672.8, self.close=26828.6, self.high=26852.8, self.low=26638.9, self.vol=57994.516, self.amt=1551427182.12312 
2023-06-20 08:00:01,599:INFO:s_rsrs:main.py:142:handleKline:2218689: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime  ...         vol           amt       pct
717  20230619   120000    155959  ...   19572.100  5.169974e+08  0.000826
718  20230619   160000    195959  ...   24996.502  6.598964e+08  0.000882
719  20230619   200000    235959  ...   65548.161  1.734847e+09 -0.000284
720  20230620   000000    035959  ...  200219.917  5.338475e+09  0.009145
721  20230620   040000    075959  ...   57994.516  1.551427e+09  0.005841

[5 rows x 11 columns]
2023-06-20 08:00:02,636:INFO:s_rsrs:main.py:151:handleKline:2218689: df_s.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec  ...  index      beta    zscore  signal
717  20230619   120000    155959  1687161599  ...    717  0.696930  1.516073     1.0
718  20230619   160000    195959  1687175999  ...    718  0.633896  1.164566     1.0
719  20230619   200000    235959  1687190399  ...    719  0.568553  0.797705     1.0
720  20230620   000000    035959  1687204799  ...    720  0.473511  0.256385     NaN
721  20230620   040000    075959  1687219199  ...    721  0.469583  0.213430     NaN

[5 rows x 15 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '57.175', 'enterprice': '26590', 'countrevence': '0', 'unrealprofit': '13821.315383211', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '26831.73704212', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'numpy.int64'>, curSign=-9223372036854775808, self.sign=1


