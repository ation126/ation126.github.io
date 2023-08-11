# 20230811 08:26:02

## /root/FIL/strategy/amihud/log.txt ----- -----

--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=373746.4768026, self.flagDict['side']='sell', self.tradeCount=2, self.count=25600
self.closeSec=1691713199, self.tradeDate='20230811', self.openTime='081500', self.closeTime='081959', self.symbol='BTCUSDT', self.open=29449.0, self.close=29459.8, self.high=29459.9, self.low=29445.5, self.vol=400.268, self.amt=11789844.5483 
127.0.0.1 - - [11/Aug/2023 08:20:01] "POST / HTTP/1.1" 200 -
2023-08-11 08:20:07,067:INFO:amihud:main.py:172:handleKline:2219019: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5855  20230811   075500    075959  ...         0.0        0.0       0
5856  20230811   080000    080459  ...         0.0        0.0       0
5857  20230811   080500    080959  ...         0.0        0.0       0
5858  20230811   081000    081459  ...         0.0        0.0       0
5859  20230811   081500    081959  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-08-11 08:20:07,087:INFO:amihud:main.py:175:handleKline:2219019: self.closeSec=1691713199, self.tradeDate='20230811', self.openTime='081500', self.closeTime='081959',self.symbol='BTCUSDT',self.open=29449.0, self.close=29459.8, self.high=29459.9, self.low=29445.5, self.vol=400.268, self.amt=11789844.5483, ukdf['pct'].iloc[-1]=0.000367 , ukdf['amount'].iloc[-1]=11789844.5483, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5859, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '13.926', 'enterprice': '26864.9', 'countrevence': '0', 'unrealprofit': '-36139.3626', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '29460', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1
127.0.0.1 - - [11/Aug/2023 08:25:00] "POST / HTTP/1.1" 200 -
--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=373746.4768026, self.flagDict['side']='sell', self.tradeCount=2, self.count=25601
self.closeSec=1691713499, self.tradeDate='20230811', self.openTime='082000', self.closeTime='082459', self.symbol='BTCUSDT', self.open=29459.9, self.close=29475.0, self.high=29475.0, self.low=29459.9, self.vol=397.21, self.amt=11705826.3621 
2023-08-11 08:25:00,800:INFO:amihud:main.py:172:handleKline:2219019: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5856  20230811   080000    080459  ...         0.0        0.0       0
5857  20230811   080500    080959  ...         0.0        0.0       0
5858  20230811   081000    081459  ...         0.0        0.0       0
5859  20230811   081500    081959  ...         0.0        0.0       0
5860  20230811   082000    082459  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-08-11 08:25:00,801:INFO:amihud:main.py:175:handleKline:2219019: self.closeSec=1691713499, self.tradeDate='20230811', self.openTime='082000', self.closeTime='082459',self.symbol='BTCUSDT',self.open=29459.9, self.close=29475.0, self.high=29475.0, self.low=29459.9, self.vol=397.21, self.amt=11705826.3621, ukdf['pct'].iloc[-1]=0.000516 , ukdf['amount'].iloc[-1]=11705826.3621, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5860, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '13.926', 'enterprice': '26864.9', 'countrevence': '0', 'unrealprofit': '-36348.2526', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '29475', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1


## /root/FIL/strategy/factorcheck/log.txt ----- -----


self.closeSec=1691713199, self.tradeDate='20230811', self.openTime='081500', self.closeTime='081959', self.symbol='BTCUSDT', self.open=29449.0, self.close=29459.8, self.high=29459.9, self.low=29445.5 
127.0.0.1 - - [11/Aug/2023 08:20:01] "POST / HTTP/1.1" 200 -
2023-08-11 08:20:04,986:INFO:factorcheck2:main.py:126:handleKline:2218005: self.closeSec=1691713199, self.tradeDate='20230811', self.openTime='081500', self.closeTime='081959',self.symbol='BTCUSDT',self.open=29449.0, self.close=29459.8, self.high=29459.9, self.low=29445.5   
2023-08-11 08:20:06,306:INFO:factorcheck2:main.py:127:handleKline:2218005: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime    closeSec  ...      low       pct  index  idx
1535  20230811   075500    075959  1691711999  ...  29440.4 -0.000082   1535    5
1536  20230811   080000    080459  1691712299  ...  29439.5 -0.000143   1536    0
1537  20230811   080500    080959  1691712599  ...  29436.0  0.000112   1537    1
1538  20230811   081000    081459  1691712899  ...  29442.8  0.000211   1538    2
1539  20230811   081500    081959  1691713199  ...  29445.5  0.000367   1539    3

[5 rows x 11 columns]
2023-08-11 08:20:06,307:INFO:factorcheck2:main.py:128:handleKline:2218005: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': True, 'isOpenSell': False, 'isCloseBuy': False, 'isCloseSell': False, 'isOpen': True, 'isClose': False, 'isTrig': True}
127.0.0.1 - - [11/Aug/2023 08:25:00] "POST / HTTP/1.1" 200 -

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=0, self.factor=0.6653343625651587, self.count=25603 

self.closeSec=1691713499, self.tradeDate='20230811', self.openTime='082000', self.closeTime='082459', self.symbol='BTCUSDT', self.open=29459.9, self.close=29475.0, self.high=29475.0, self.low=29459.9 
2023-08-11 08:25:00,771:INFO:factorcheck2:main.py:126:handleKline:2218005: self.closeSec=1691713499, self.tradeDate='20230811', self.openTime='082000', self.closeTime='082459',self.symbol='BTCUSDT',self.open=29459.9, self.close=29475.0, self.high=29475.0, self.low=29459.9   
2023-08-11 08:25:00,785:INFO:factorcheck2:main.py:127:handleKline:2218005: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime    closeSec  ...      low       pct  index  idx
1536  20230811   080000    080459  1691712299  ...  29439.5 -0.000143   1536    0
1537  20230811   080500    080959  1691712599  ...  29436.0  0.000112   1537    1
1538  20230811   081000    081459  1691712899  ...  29442.8  0.000211   1538    2
1539  20230811   081500    081959  1691713199  ...  29445.5  0.000367   1539    3
1540  20230811   082000    082459  1691713499  ...  29459.9  0.000516   1540    4

[5 rows x 11 columns]
2023-08-11 08:25:00,785:INFO:factorcheck2:main.py:128:handleKline:2218005: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': True, 'isOpenSell': False, 'isCloseBuy': False, 'isCloseSell': False, 'isOpen': True, 'isClose': False, 'isTrig': True}


## /root/FIL/strategy/logic/log.txt ----- -----

2023-08-11 08:00:17,975:DEBUG:logic:main.py:463:getModel:2218526: df_s.iloc[-5:,:] :
          date closeTime     open  ...    alpha58   alpha67   alpha72
5770  20230811    052959  29446.5  ...  48.333333  0.477228  0.682715
5771  20230811    055959  29444.6  ...  48.333333  0.479762  0.680461
5772  20230811    062959  29453.4  ...  48.750000  0.480956  0.677732
5773  20230811    065959  29457.2  ...  48.333333  0.478240  0.676702
5774  20230811    072959  29447.5  ...  48.750000  0.479230  0.675240

[5 rows x 33 columns]
0.5101663585951941
acc is : 0.5101663585951941
2023-08-11 08:00:18,042:INFO:logic:main.py:468:getModel:2218526: df_pred.iloc[-5:,:] :
     pred    prob_0    prob_1  actual  ...       nav  sign  cost_        bm
536     1  0.499554  0.500446       1  ...  0.962214  -1.0    0.0  1.003116
537     0  0.503979  0.496021       1  ...  0.962084  -1.0    0.0  1.003253
538     0  0.503177  0.496823       0  ...  0.962401  -1.0    0.0  1.002922
539     0  0.502648  0.497352       1  ...  0.962296  -1.0    0.0  1.003031
540     0  0.508236  0.491764       0  ...  0.962528  -1.0    0.0  1.002789

[5 rows x 10 columns]
2023-08-11 08:00:18,054:INFO:logic:main.py:478:getModel:2218526: df_panel.iloc[-5:,:] :
    pred    prob_0    prob_1  actual  ...       nav  sign  cost_        bm
45     1  0.499693  0.500307       1  ...  0.962214  -1.0    0.0  1.003961
46     0  0.504005  0.495995       1  ...  0.962084  -1.0    0.0  1.003410
47     0  0.503052  0.496948       0  ...  0.962401  -1.0    0.0  1.002731
48     0  0.502764  0.497236       1  ...  0.962296  -1.0    0.0  1.003031
49     0  0.508236  0.491764       0  ...  0.962528  -1.0    0.0  1.002789

[5 rows x 10 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '24.049', 'enterprice': '29479.7', 'countrevence': '0', 'unrealprofit': '865.764', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '29443.7', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}


## /root/FIL/strategy/modifiedmom/log.txt ----- -----

623  20230811   075000    075959  1691711999    29440  29443.7  0.000129
2023-08-11 08:00:02,209:INFO:modifiedmom:main.py:146:handleKline:2218259: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': True, 'isOpen': False, 'isClose': True, 'isTrig': False}

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=12800 

self.closeSec=1691712599, self.tradeDate='20230811', self.openTime='080000', self.closeTime='080959', self.symbol='BTCUSDT', self.open='29443.7', self.close='29442.8'
2023-08-11 08:10:01,130:INFO:modifiedmom:main.py:144:handleKline:2218259: self.closeSec=1691712599, self.tradeDate='20230811', self.openTime='080000', self.closeTime='080959',self.symbol='BTCUSDT',self.open='29443.7', self.close='29442.8'
127.0.0.1 - - [11/Aug/2023 08:10:01] "POST / HTTP/1.1" 200 -
2023-08-11 08:10:01,142:INFO:modifiedmom:main.py:145:handleKline:2218259: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec     open    close       pct
620  20230811   072000    072959  1691710199  29438.8  29450.8  0.000408
621  20230811   073000    073959  1691710799  29450.7  29439.4 -0.000387
622  20230811   074000    074959  1691711399  29439.4  29439.9  0.000017
623  20230811   075000    075959  1691711999    29440  29443.7  0.000129
624  20230811   080000    080959  1691712599  29443.7  29442.8 -0.000031
2023-08-11 08:10:01,142:INFO:modifiedmom:main.py:146:handleKline:2218259: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': True, 'isOpen': False, 'isClose': True, 'isTrig': False}

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=12801 

self.closeSec=1691713199, self.tradeDate='20230811', self.openTime='081000', self.closeTime='081959', self.symbol='BTCUSDT', self.open='29442.8', self.close='29459.8'
127.0.0.1 - - [11/Aug/2023 08:20:04] "POST / HTTP/1.1" 200 -
2023-08-11 08:20:07,347:INFO:modifiedmom:main.py:144:handleKline:2218259: self.closeSec=1691713199, self.tradeDate='20230811', self.openTime='081000', self.closeTime='081959',self.symbol='BTCUSDT',self.open='29442.8', self.close='29459.8'
2023-08-11 08:20:07,946:INFO:modifiedmom:main.py:145:handleKline:2218259: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec     open    close       pct
621  20230811   073000    073959  1691710799  29450.7  29439.4 -0.000387
622  20230811   074000    074959  1691711399  29439.4  29439.9  0.000017
623  20230811   075000    075959  1691711999    29440  29443.7  0.000129
624  20230811   080000    080959  1691712599  29443.7  29442.8 -0.000031
625  20230811   081000    081959  1691713199  29442.8  29459.8  0.000577
2023-08-11 08:20:07,956:INFO:modifiedmom:main.py:146:handleKline:2218259: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': True, 'isOpen': False, 'isClose': True, 'isTrig': False}


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

17471  20230811   075000    075959  1691711999    29440  29443.7
2023-08-11 08:00:02,219:INFO:pyemd2:main.py:127:handleKline:2217508: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=12803 

self.closeSec=1691712599, self.tradeDate='20230811', self.openTime='080000', self.closeTime='080959', self.symbol='BTCUSDT', self.open='29443.7', self.close='29442.8'
2023-08-11 08:10:01,126:INFO:pyemd2:main.py:125:handleKline:2217508: self.closeSec=1691712599, self.tradeDate='20230811', self.openTime='080000', self.closeTime='080959',self.symbol='BTCUSDT',self.open='29443.7', self.close='29442.8'
127.0.0.1 - - [11/Aug/2023 08:10:01] "POST / HTTP/1.1" 200 -
2023-08-11 08:10:01,132:INFO:pyemd2:main.py:126:handleKline:2217508: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
17468  20230811   072000    072959  1691710199  29438.8  29450.8
17469  20230811   073000    073959  1691710799  29450.7  29439.4
17470  20230811   074000    074959  1691711399  29439.4  29439.9
17471  20230811   075000    075959  1691711999    29440  29443.7
17472  20230811   080000    080959  1691712599  29443.7  29442.8
2023-08-11 08:10:01,133:INFO:pyemd2:main.py:127:handleKline:2217508: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=12804 

self.closeSec=1691713199, self.tradeDate='20230811', self.openTime='081000', self.closeTime='081959', self.symbol='BTCUSDT', self.open='29442.8', self.close='29459.8'
127.0.0.1 - - [11/Aug/2023 08:20:04] "POST / HTTP/1.1" 200 -
2023-08-11 08:20:09,147:INFO:pyemd2:main.py:125:handleKline:2217508: self.closeSec=1691713199, self.tradeDate='20230811', self.openTime='081000', self.closeTime='081959',self.symbol='BTCUSDT',self.open='29442.8', self.close='29459.8'
2023-08-11 08:20:09,246:INFO:pyemd2:main.py:126:handleKline:2217508: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
17469  20230811   073000    073959  1691710799  29450.7  29439.4
17470  20230811   074000    074959  1691711399  29439.4  29439.9
17471  20230811   075000    075959  1691711999    29440  29443.7
17472  20230811   080000    080959  1691712599  29443.7  29442.8
17473  20230811   081000    081959  1691713199  29442.8  29459.8
2023-08-11 08:20:09,247:INFO:pyemd2:main.py:127:handleKline:2217508: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}


## /root/FIL/strategy/similarity/log.txt ----- -----

12143  20230811   075000    075959  1691711999    29440  29443.7
2023-08-11 08:00:02,214:INFO:testStrategy:main.py:103:handleKline:2217133: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': True, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True, 'isCorr': False}
127.0.0.1 - - [11/Aug/2023 08:10:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=12803 

self.closeSec=1691712599, self.tradeDate='20230811', self.openTime='080000', self.closeTime='080959', self.symbol='BTCUSDT', self.open='29443.7', self.close='29442.8'
2023-08-11 08:10:01,124:INFO:testStrategy:main.py:101:handleKline:2217133: self.closeSec=1691712599, self.tradeDate='20230811', self.openTime='080000', self.closeTime='080959',self.symbol='BTCUSDT',self.open='29443.7', self.close='29442.8'
2023-08-11 08:10:01,144:INFO:testStrategy:main.py:102:handleKline:2217133: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
12140  20230811   072000    072959  1691710199  29438.8  29450.8
12141  20230811   073000    073959  1691710799  29450.7  29439.4
12142  20230811   074000    074959  1691711399  29439.4  29439.9
12143  20230811   075000    075959  1691711999    29440  29443.7
12144  20230811   080000    080959  1691712599  29443.7  29442.8
2023-08-11 08:10:01,144:INFO:testStrategy:main.py:103:handleKline:2217133: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': True, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True, 'isCorr': False}

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=12804 

self.closeSec=1691713199, self.tradeDate='20230811', self.openTime='081000', self.closeTime='081959', self.symbol='BTCUSDT', self.open='29442.8', self.close='29459.8'
127.0.0.1 - - [11/Aug/2023 08:20:04] "POST / HTTP/1.1" 200 -
2023-08-11 08:20:08,970:INFO:testStrategy:main.py:101:handleKline:2217133: self.closeSec=1691713199, self.tradeDate='20230811', self.openTime='081000', self.closeTime='081959',self.symbol='BTCUSDT',self.open='29442.8', self.close='29459.8'
2023-08-11 08:20:09,137:INFO:testStrategy:main.py:102:handleKline:2217133: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
12141  20230811   073000    073959  1691710799  29450.7  29439.4
12142  20230811   074000    074959  1691711399  29439.4  29439.9
12143  20230811   075000    075959  1691711999    29440  29443.7
12144  20230811   080000    080959  1691712599  29443.7  29442.8
12145  20230811   081000    081959  1691713199  29442.8  29459.8
2023-08-11 08:20:09,137:INFO:testStrategy:main.py:103:handleKline:2217133: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': True, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True, 'isCorr': False}


## /root/FIL/strategy/sr_min/log.txt ----- -----

--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=1, self.total=996015.990996, self.flagDict['side']='buy', self.tradeCount=1, self.count=25600
self.closeSec=1691713199, self.tradeDate='20230811', self.openTime='081500', self.closeTime='081959', self.symbol='BTCUSDT', self.open=29449.0, self.close=29459.8, self.high=29459.9, self.low=29445.5, self.vol=400.268, self.amt=11789844.5483 
127.0.0.1 - - [11/Aug/2023 08:20:01] "POST / HTTP/1.1" 200 -
2023-08-11 08:20:07,085:INFO:sr_min:main.py:172:handleKline:2219263: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5855  20230811   075500    075959  ...         0.0        0.0       0
5856  20230811   080000    080459  ...         0.0        0.0       0
5857  20230811   080500    080959  ...         0.0        0.0       0
5858  20230811   081000    081459  ...         0.0        0.0       0
5859  20230811   081500    081959  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-08-11 08:20:07,097:INFO:sr_min:main.py:175:handleKline:2219263: self.closeSec=1691713199, self.tradeDate='20230811', self.openTime='081500', self.closeTime='081959',self.symbol='BTCUSDT',self.open=29449.0, self.close=29459.8, self.high=29459.9, self.low=29445.5, self.vol=400.268, self.amt=11789844.5483, ukdf['pct'].iloc[-1]=0.000367 , ukdf['amount'].iloc[-1]=11789844.5483, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5859, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '37.141', 'enterprice': '26844', 'countrevence': '0', 'unrealprofit': '97160.856', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '29460', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=1
127.0.0.1 - - [11/Aug/2023 08:25:00] "POST / HTTP/1.1" 200 -
--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=1, self.total=996015.990996, self.flagDict['side']='buy', self.tradeCount=1, self.count=25601
self.closeSec=1691713499, self.tradeDate='20230811', self.openTime='082000', self.closeTime='082459', self.symbol='BTCUSDT', self.open=29459.9, self.close=29475.0, self.high=29475.0, self.low=29459.9, self.vol=397.21, self.amt=11705826.3621 
2023-08-11 08:25:00,811:INFO:sr_min:main.py:172:handleKline:2219263: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5856  20230811   080000    080459  ...         0.0        0.0       0
5857  20230811   080500    080959  ...         0.0        0.0       0
5858  20230811   081000    081459  ...         0.0        0.0       0
5859  20230811   081500    081959  ...         0.0        0.0       0
5860  20230811   082000    082459  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-08-11 08:25:00,811:INFO:sr_min:main.py:175:handleKline:2219263: self.closeSec=1691713499, self.tradeDate='20230811', self.openTime='082000', self.closeTime='082459',self.symbol='BTCUSDT',self.open=29459.9, self.close=29475.0, self.high=29475.0, self.low=29459.9, self.vol=397.21, self.amt=11705826.3621, ukdf['pct'].iloc[-1]=0.000516 , ukdf['amount'].iloc[-1]=11705826.3621, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5860, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '37.141', 'enterprice': '26844', 'countrevence': '0', 'unrealprofit': '97717.971', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '29475', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=1


## /root/FIL/strategy/s_rsrs/log.txt ----- -----

719  20230810   200000    235959  1691683199  ...    719  0.947260  1.593051     1.0
720  20230811   000000    035959  1691697599  ...    720  0.899898  1.433502     1.0

[5 rows x 15 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '51.457', 'enterprice': '29884.4', 'countrevence': '0', 'unrealprofit': '-23104.193', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '29435.4', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'numpy.int64'>, curSign=1, self.sign=1
--handleKline--:  version='2.0.0', self.name='s_rsrs', self.symbol='BTCUSDT', interval='4h', intervalSec=14400, wid=25, thd=0.6, self.sign=1, self.total=1536223.8092292, self.flagDict['side']='buy', self.tradeCount=19, self.count=533
self.closeSec=1691711999, self.tradeDate='20230811', self.openTime='040000', self.closeTime='075959', self.symbol='BTCUSDT', self.open=29435.4, self.close=29443.7, self.high=29480.0, self.low=29413.7, self.vol=13216.051, self.amt=389216478.9213 127.0.0.1 - - [11/Aug/2023 08:00:01] "POST / HTTP/1.1" 200 -

2023-08-11 08:00:01,759:INFO:s_rsrs:main.py:141:handleKline:2218689: self.closeSec=1691711999, self.tradeDate='20230811', self.openTime='040000', self.closeTime='075959',self.symbol='BTCUSDT',self.open=29435.4, self.close=29443.7, self.high=29480.0, self.low=29413.7, self.vol=13216.051, self.amt=389216478.9213 
2023-08-11 08:00:01,772:INFO:s_rsrs:main.py:142:handleKline:2218689: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime  ...         vol           amt       pct
717  20230810   120000    155959  ...   26122.949  7.715556e+08 -0.002198
718  20230810   160000    195959  ...   21083.327  6.221257e+08 -0.000475
719  20230810   200000    235959  ...  101443.007  2.997258e+09 -0.001261
720  20230811   000000    035959  ...   46278.886  1.361132e+09 -0.000587
721  20230811   040000    075959  ...   13216.051  3.892165e+08  0.000279

[5 rows x 11 columns]
2023-08-11 08:00:02,512:INFO:s_rsrs:main.py:151:handleKline:2218689: df_s.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec  ...  index      beta    zscore  signal
717  20230810   120000    155959  1691654399  ...    717  1.035430  1.920660     1.0
718  20230810   160000    195959  1691668799  ...    718  0.966686  1.680627     1.0
719  20230810   200000    235959  1691683199  ...    719  0.947260  1.593051     1.0
720  20230811   000000    035959  1691697599  ...    720  0.899898  1.433502     1.0
721  20230811   040000    075959  1691711999  ...    721  0.823996  1.202551     1.0

[5 rows x 15 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '51.457', 'enterprice': '29884.4', 'countrevence': '0', 'unrealprofit': '-22677.0999', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '29443.7', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'numpy.int64'>, curSign=1, self.sign=1


