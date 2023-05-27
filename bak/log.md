# 20230527 08:26:01

## /root/FIL/strategy/amihud/log.txt ----- -----

--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=373746.4768026, self.flagDict['side']='sell', self.tradeCount=2, self.count=3712
self.closeSec=1685146799, self.tradeDate='20230527', self.openTime='081500', self.closeTime='081959', self.symbol='BTCUSDT', self.open=26667.9, self.close=26663.1, self.high=26672.0, self.low=26663.1, self.vol=248.068, self.amt=6615653.9602 
127.0.0.1 - - [27/May/2023 08:20:01] "POST / HTTP/1.1" 200 -
2023-05-27 08:20:06,595:INFO:amihud:main.py:172:handleKline:2219019: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5855  20230527   075500    075959  ...    0.009086   0.111363       0
5856  20230527   080000    080459  ...    0.008551   0.106687       0
5857  20230527   080500    080959  ...    0.008020   0.101853       0
5858  20230527   081000    081459  ...    0.007472   0.096437       0
5859  20230527   081500    081959  ...    0.006931   0.090860       0

[5 rows x 18 columns]
2023-05-27 08:20:06,614:INFO:amihud:main.py:175:handleKline:2219019: self.closeSec=1685146799, self.tradeDate='20230527', self.openTime='081500', self.closeTime='081959',self.symbol='BTCUSDT',self.open=26667.9, self.close=26663.1, self.high=26672.0, self.low=26663.1, self.vol=248.068, self.amt=6615653.9602, ukdf['pct'].iloc[-1]=-0.00018 , ukdf['amount'].iloc[-1]=6615653.9602, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5859, value=0.0, value_mean=0.006930908327421009, signal=0, value_std=0.09085950864561505 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '13.926', 'enterprice': '26864.9', 'countrevence': '0', 'unrealprofit': '2785.79754697398', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '26664.85709127', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1
127.0.0.1 - - [27/May/2023 08:25:00] "POST / HTTP/1.1" 200 -
--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=373746.4768026, self.flagDict['side']='sell', self.tradeCount=2, self.count=3713
self.closeSec=1685147099, self.tradeDate='20230527', self.openTime='082000', self.closeTime='082459', self.symbol='BTCUSDT', self.open=26663.2, self.close=26654.3, self.high=26669.0, self.low=26636.3, self.vol=810.3, self.amt=21598704.11 
2023-05-27 08:25:00,881:INFO:amihud:main.py:172:handleKline:2219019: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5856  20230527   080000    080459  ...    0.008551   0.106687       0
5857  20230527   080500    080959  ...    0.008020   0.101853       0
5858  20230527   081000    081459  ...    0.007472   0.096437       0
5859  20230527   081500    081959  ...    0.006931   0.090860       0
5860  20230527   082000    082459  ...    0.006394   0.084994       0

[5 rows x 18 columns]
2023-05-27 08:25:00,882:INFO:amihud:main.py:175:handleKline:2219019: self.closeSec=1685147099, self.tradeDate='20230527', self.openTime='082000', self.closeTime='082459',self.symbol='BTCUSDT',self.open=26663.2, self.close=26654.3, self.high=26669.0, self.low=26636.3, self.vol=810.3, self.amt=21598704.11, ukdf['pct'].iloc[-1]=-0.00033 , ukdf['amount'].iloc[-1]=21598704.11, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5860, value=0.0, value_mean=0.0063937849028055885, signal=0, value_std=0.08499412716422362 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '13.926', 'enterprice': '26864.9', 'countrevence': '0', 'unrealprofit': '2910.03819025458', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '26655.93560317', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1


## /root/FIL/strategy/factorcheck/log.txt ----- -----


self.closeSec=1685146799, self.tradeDate='20230527', self.openTime='081500', self.closeTime='081959', self.symbol='BTCUSDT', self.open=26667.9, self.close=26663.1, self.high=26672.0, self.low=26663.1 
127.0.0.1 - - [27/May/2023 08:20:01] "POST / HTTP/1.1" 200 -
2023-05-27 08:20:04,285:INFO:factorcheck2:main.py:126:handleKline:2218005: self.closeSec=1685146799, self.tradeDate='20230527', self.openTime='081500', self.closeTime='081959',self.symbol='BTCUSDT',self.open=26667.9, self.close=26663.1, self.high=26672.0, self.low=26663.1   
2023-05-27 08:20:05,667:INFO:factorcheck2:main.py:127:handleKline:2218005: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime    closeSec  ...      low       pct  index  idx
1535  20230527   075500    075959  1685145599  ...  26689.8 -0.000322   1535    5
1536  20230527   080000    080459  1685145899  ...  26675.4 -0.000495   1536    0
1537  20230527   080500    080959  1685146199  ...  26666.0  0.000337   1537    1
1538  20230527   081000    081459  1685146499  ...  26665.1 -0.000667   1538    2
1539  20230527   081500    081959  1685146799  ...  26663.1 -0.000180   1539    3

[5 rows x 11 columns]
2023-05-27 08:20:05,675:INFO:factorcheck2:main.py:128:handleKline:2218005: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=19, self.factor=0.2965101005821497, self.count=3715 

self.closeSec=1685147099, self.tradeDate='20230527', self.openTime='082000', self.closeTime='082459', self.symbol='BTCUSDT', self.open=26663.2, self.close=26654.3, self.high=26669.0, self.low=26636.3 
127.0.0.1 - - [27/May/2023 08:25:00] "POST / HTTP/1.1" 200 -
2023-05-27 08:25:00,752:INFO:factorcheck2:main.py:126:handleKline:2218005: self.closeSec=1685147099, self.tradeDate='20230527', self.openTime='082000', self.closeTime='082459',self.symbol='BTCUSDT',self.open=26663.2, self.close=26654.3, self.high=26669.0, self.low=26636.3   
2023-05-27 08:25:00,826:INFO:factorcheck2:main.py:127:handleKline:2218005: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime    closeSec  ...      low       pct  index  idx
1536  20230527   080000    080459  1685145899  ...  26675.4 -0.000495   1536    0
1537  20230527   080500    080959  1685146199  ...  26666.0  0.000337   1537    1
1538  20230527   081000    081459  1685146499  ...  26665.1 -0.000667   1538    2
1539  20230527   081500    081959  1685146799  ...  26663.1 -0.000180   1539    3
1540  20230527   082000    082459  1685147099  ...  26636.3 -0.000330   1540    4

[5 rows x 11 columns]
2023-05-27 08:25:00,827:INFO:factorcheck2:main.py:128:handleKline:2218005: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}


## /root/FIL/strategy/logic/log.txt ----- -----

2023-05-27 08:00:35,081:DEBUG:logic:main.py:463:getModel:2218526: df_s.iloc[-5:,:] :
          date closeTime     open  ...    alpha58   alpha67   alpha72
5770  20230527    052959  26735.5  ...  47.916667  0.549483  0.340684
5771  20230527    055959  26711.6  ...  47.500000  0.549452  0.341274
5772  20230527    062959  26711.3  ...  47.500000  0.552831  0.340385
5773  20230527    065959  26724.6  ...  47.500000  0.535869  0.345511
5774  20230527    072959  26670.1  ...  47.500000  0.540636  0.348321

[5 rows x 33 columns]
0.5341959334565619
acc is : 0.5341959334565619
2023-05-27 08:00:35,214:INFO:logic:main.py:468:getModel:2218526: df_pred.iloc[-5:,:] :
     pred    prob_0    prob_1  actual  ...       nav  sign  cost_        bm
536     1  0.486601  0.513399       1  ...  0.907243   1.0    0.0  0.971790
537     1  0.488310  0.511690       1  ...  0.907691   1.0    0.0  0.972270
538     1  0.491179  0.508821       0  ...  0.905836   1.0    0.0  0.970284
539     1  0.477355  0.522645       1  ...  0.906451   1.0    0.0  0.970942
540     1  0.492427  0.507573       1  ...  0.906512   1.0    0.0  0.971008

[5 rows x 10 columns]
2023-05-27 08:00:35,238:INFO:logic:main.py:478:getModel:2218526: df_panel.iloc[-5:,:] :
    pred    prob_0    prob_1  actual  ...       nav  sign  cost_        bm
45     1  0.486885  0.513115       1  ...  0.898539   1.0    0.0  0.975474
46     1  0.488460  0.511540       1  ...  0.898983   1.0    0.0  0.972961
47     1  0.491146  0.508854       0  ...  0.905836   1.0    0.0  0.970962
48     1  0.477355  0.522645       1  ...  0.906451   1.0    0.0  0.970942
49     1  0.492427  0.507573       1  ...  0.906512   1.0    0.0  0.971008

[5 rows x 10 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '25.918', 'enterprice': '26792.4', 'countrevence': '0', 'unrealprofit': '-2314.4774', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '26703.1', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}


## /root/FIL/strategy/modifiedmom/log.txt ----- -----

623  20230527   075000    075959  1685145599  26694.7  26689.9 -0.000180
2023-05-27 08:00:02,293:INFO:modifiedmom:main.py:146:handleKline:2218259: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': True, 'isOpen': False, 'isClose': True, 'isTrig': False}
127.0.0.1 - - [27/May/2023 08:10:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=1856 

self.closeSec=1685146199, self.tradeDate='20230527', self.openTime='080000', self.closeTime='080959', self.symbol='BTCUSDT', self.open='26689.8', self.close='26685.7'
2023-05-27 08:10:01,098:INFO:modifiedmom:main.py:144:handleKline:2218259: self.closeSec=1685146199, self.tradeDate='20230527', self.openTime='080000', self.closeTime='080959',self.symbol='BTCUSDT',self.open='26689.8', self.close='26685.7'
2023-05-27 08:10:01,141:INFO:modifiedmom:main.py:145:handleKline:2218259: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec     open    close       pct
620  20230527   072000    072959  1685143799  26716.7  26688.1 -0.001067
621  20230527   073000    073959  1685144399  26688.1  26695.1  0.000262
622  20230527   074000    074959  1685144999  26695.1  26694.7 -0.000015
623  20230527   075000    075959  1685145599  26694.7  26689.9 -0.000180
624  20230527   080000    080959  1685146199  26689.8  26685.7 -0.000157
2023-05-27 08:10:01,141:INFO:modifiedmom:main.py:146:handleKline:2218259: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': True, 'isOpen': False, 'isClose': True, 'isTrig': False}

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=1857 

self.closeSec=1685146799, self.tradeDate='20230527', self.openTime='081000', self.closeTime='081959', self.symbol='BTCUSDT', self.open='26685.6', self.close='26663.1'
127.0.0.1 - - [27/May/2023 08:20:04] "POST / HTTP/1.1" 200 -
2023-05-27 08:20:06,694:INFO:modifiedmom:main.py:144:handleKline:2218259: self.closeSec=1685146799, self.tradeDate='20230527', self.openTime='081000', self.closeTime='081959',self.symbol='BTCUSDT',self.open='26685.6', self.close='26663.1'
2023-05-27 08:20:07,324:INFO:modifiedmom:main.py:145:handleKline:2218259: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec     open    close       pct
621  20230527   073000    073959  1685144399  26688.1  26695.1  0.000262
622  20230527   074000    074959  1685144999  26695.1  26694.7 -0.000015
623  20230527   075000    075959  1685145599  26694.7  26689.9 -0.000180
624  20230527   080000    080959  1685146199  26689.8  26685.7 -0.000157
625  20230527   081000    081959  1685146799  26685.6  26663.1 -0.000847
2023-05-27 08:20:07,325:INFO:modifiedmom:main.py:146:handleKline:2218259: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': True, 'isOpen': False, 'isClose': True, 'isTrig': False}


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

17471  20230527   075000    075959  1685145599  26694.7  26689.9
2023-05-27 08:00:02,291:INFO:pyemd2:main.py:127:handleKline:2217508: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}
127.0.0.1 - - [27/May/2023 08:10:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=1859 

self.closeSec=1685146199, self.tradeDate='20230527', self.openTime='080000', self.closeTime='080959', self.symbol='BTCUSDT', self.open='26689.8', self.close='26685.7'
2023-05-27 08:10:01,139:INFO:pyemd2:main.py:125:handleKline:2217508: self.closeSec=1685146199, self.tradeDate='20230527', self.openTime='080000', self.closeTime='080959',self.symbol='BTCUSDT',self.open='26689.8', self.close='26685.7'
2023-05-27 08:10:01,181:INFO:pyemd2:main.py:126:handleKline:2217508: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
17468  20230527   072000    072959  1685143799  26716.7  26688.1
17469  20230527   073000    073959  1685144399  26688.1  26695.1
17470  20230527   074000    074959  1685144999  26695.1  26694.7
17471  20230527   075000    075959  1685145599  26694.7  26689.9
17472  20230527   080000    080959  1685146199  26689.8  26685.7
2023-05-27 08:10:01,181:INFO:pyemd2:main.py:127:handleKline:2217508: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=1860 

self.closeSec=1685146799, self.tradeDate='20230527', self.openTime='081000', self.closeTime='081959', self.symbol='BTCUSDT', self.open='26685.6', self.close='26663.1'
127.0.0.1 - - [27/May/2023 08:20:04] "POST / HTTP/1.1" 200 -
2023-05-27 08:20:08,298:INFO:pyemd2:main.py:125:handleKline:2217508: self.closeSec=1685146799, self.tradeDate='20230527', self.openTime='081000', self.closeTime='081959',self.symbol='BTCUSDT',self.open='26685.6', self.close='26663.1'
2023-05-27 08:20:08,443:INFO:pyemd2:main.py:126:handleKline:2217508: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
17469  20230527   073000    073959  1685144399  26688.1  26695.1
17470  20230527   074000    074959  1685144999  26695.1  26694.7
17471  20230527   075000    075959  1685145599  26694.7  26689.9
17472  20230527   080000    080959  1685146199  26689.8  26685.7
17473  20230527   081000    081959  1685146799  26685.6  26663.1
2023-05-27 08:20:08,445:INFO:pyemd2:main.py:127:handleKline:2217508: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}


## /root/FIL/strategy/similarity/log.txt ----- -----

12143  20230527   075000    075959  1685145599  26694.7  26689.9
2023-05-27 08:00:02,285:INFO:testStrategy:main.py:103:handleKline:2217133: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': True, 'isOpenSell': False, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True, 'isCorr': False}
127.0.0.1 - - [27/May/2023 08:10:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=1859 

self.closeSec=1685146199, self.tradeDate='20230527', self.openTime='080000', self.closeTime='080959', self.symbol='BTCUSDT', self.open='26689.8', self.close='26685.7'
2023-05-27 08:10:01,132:INFO:testStrategy:main.py:101:handleKline:2217133: self.closeSec=1685146199, self.tradeDate='20230527', self.openTime='080000', self.closeTime='080959',self.symbol='BTCUSDT',self.open='26689.8', self.close='26685.7'
2023-05-27 08:10:01,172:INFO:testStrategy:main.py:102:handleKline:2217133: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
12140  20230527   072000    072959  1685143799  26716.7  26688.1
12141  20230527   073000    073959  1685144399  26688.1  26695.1
12142  20230527   074000    074959  1685144999  26695.1  26694.7
12143  20230527   075000    075959  1685145599  26694.7  26689.9
12144  20230527   080000    080959  1685146199  26689.8  26685.7
2023-05-27 08:10:01,177:INFO:testStrategy:main.py:103:handleKline:2217133: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': True, 'isOpenSell': False, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True, 'isCorr': False}

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=1860 

self.closeSec=1685146799, self.tradeDate='20230527', self.openTime='081000', self.closeTime='081959', self.symbol='BTCUSDT', self.open='26685.6', self.close='26663.1'
127.0.0.1 - - [27/May/2023 08:20:04] "POST / HTTP/1.1" 200 -
2023-05-27 08:20:08,027:INFO:testStrategy:main.py:101:handleKline:2217133: self.closeSec=1685146799, self.tradeDate='20230527', self.openTime='081000', self.closeTime='081959',self.symbol='BTCUSDT',self.open='26685.6', self.close='26663.1'
2023-05-27 08:20:08,286:INFO:testStrategy:main.py:102:handleKline:2217133: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
12141  20230527   073000    073959  1685144399  26688.1  26695.1
12142  20230527   074000    074959  1685144999  26695.1  26694.7
12143  20230527   075000    075959  1685145599  26694.7  26689.9
12144  20230527   080000    080959  1685146199  26689.8  26685.7
12145  20230527   081000    081959  1685146799  26685.6  26663.1
2023-05-27 08:20:08,294:INFO:testStrategy:main.py:103:handleKline:2217133: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': True, 'isOpenSell': False, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True, 'isCorr': False}


## /root/FIL/strategy/sr_min/log.txt ----- -----

--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=1, self.total=996015.990996, self.flagDict['side']='buy', self.tradeCount=1, self.count=3712
self.closeSec=1685146799, self.tradeDate='20230527', self.openTime='081500', self.closeTime='081959', self.symbol='BTCUSDT', self.open=26667.9, self.close=26663.1, self.high=26672.0, self.low=26663.1, self.vol=248.068, self.amt=6615653.9602 
127.0.0.1 - - [27/May/2023 08:20:01] "POST / HTTP/1.1" 200 -
2023-05-27 08:20:06,587:INFO:sr_min:main.py:172:handleKline:2219263: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5855  20230527   075500    075959  ...         0.0        0.0       0
5856  20230527   080000    080459  ...         0.0        0.0       0
5857  20230527   080500    080959  ...         0.0        0.0       0
5858  20230527   081000    081459  ...         0.0        0.0       0
5859  20230527   081500    081959  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-05-27 08:20:06,605:INFO:sr_min:main.py:175:handleKline:2219263: self.closeSec=1685146799, self.tradeDate='20230527', self.openTime='081500', self.closeTime='081959',self.symbol='BTCUSDT',self.open=26667.9, self.close=26663.1, self.high=26672.0, self.low=26663.1, self.vol=248.068, self.amt=6615653.9602, ukdf['pct'].iloc[-1]=-0.00018 , ukdf['amount'].iloc[-1]=6615653.9602, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5859, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '37.141', 'enterprice': '26844', 'countrevence': '0', 'unrealprofit': '-6653.54677314093', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '26664.85709127', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=1
127.0.0.1 - - [27/May/2023 08:25:00] "POST / HTTP/1.1" 200 -
--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=1, self.total=996015.990996, self.flagDict['side']='buy', self.tradeCount=1, self.count=3713
self.closeSec=1685147099, self.tradeDate='20230527', self.openTime='082000', self.closeTime='082459', self.symbol='BTCUSDT', self.open=26663.2, self.close=26654.3, self.high=26669.0, self.low=26636.3, self.vol=810.3, self.amt=21598704.11 
2023-05-27 08:25:00,886:INFO:sr_min:main.py:172:handleKline:2219263: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5856  20230527   080000    080459  ...         0.0        0.0       0
5857  20230527   080500    080959  ...         0.0        0.0       0
5858  20230527   081000    081459  ...         0.0        0.0       0
5859  20230527   081500    081959  ...         0.0        0.0       0
5860  20230527   082000    082459  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-05-27 08:25:00,886:INFO:sr_min:main.py:175:handleKline:2219263: self.closeSec=1685147099, self.tradeDate='20230527', self.openTime='082000', self.closeTime='082459',self.symbol='BTCUSDT',self.open=26663.2, self.close=26654.3, self.high=26669.0, self.low=26636.3, self.vol=810.3, self.amt=21598704.11, ukdf['pct'].iloc[-1]=-0.00033 , ukdf['amount'].iloc[-1]=21598704.11, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5860, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '37.141', 'enterprice': '26844', 'countrevence': '0', 'unrealprofit': '-6984.89976266303', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '26655.93560317', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=1


## /root/FIL/strategy/s_rsrs/log.txt ----- -----

719  20230526   200000    235959  1685116799  ...    719  0.605951  1.281364     1.0
720  20230527   000000    035959  1685131199  ...    720  0.597411  1.205087     1.0

[5 rows x 15 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '55.249', 'enterprice': '26128.2', 'countrevence': '0', 'unrealprofit': '34646.6479', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '26755.3', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'numpy.int64'>, curSign=1, self.sign=1
127.0.0.1 - - [27/May/2023 08:00:01] "POST / HTTP/1.1" 200 -
--handleKline--:  version='2.0.0', self.name='s_rsrs', self.symbol='BTCUSDT', interval='4h', intervalSec=14400, wid=25, thd=0.6, self.sign=1, self.total=1442113.3648782002, self.flagDict['side']='buy', self.tradeCount=3, self.count=77
self.closeSec=1685145599, self.tradeDate='20230527', self.openTime='040000', self.closeTime='075959', self.symbol='BTCUSDT', self.open=26755.3, self.close=26689.9, self.high=26796.6, self.low=26670.0, self.vol=18689.388, self.amt=499521774.8856 
2023-05-27 08:00:01,828:INFO:s_rsrs:main.py:141:handleKline:2218689: self.closeSec=1685145599, self.tradeDate='20230527', self.openTime='040000', self.closeTime='075959',self.symbol='BTCUSDT',self.open=26755.3, self.close=26689.9, self.high=26796.6, self.low=26670.0, self.vol=18689.388, self.amt=499521774.8856 
2023-05-27 08:00:01,855:INFO:s_rsrs:main.py:142:handleKline:2218689: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime  ...         vol           amt       pct
717  20230526   120000    155959  ...   34980.918  9.238922e+08  0.002482
718  20230526   160000    195959  ...   32939.619  8.717101e+08 -0.001487
719  20230526   200000    235959  ...  137774.544  3.674536e+09  0.010793
720  20230527   000000    035959  ...   61511.083  1.644152e+09  0.000666
721  20230527   040000    075959  ...   18689.388  4.995218e+08 -0.002441

[5 rows x 11 columns]
2023-05-27 08:00:03,703:INFO:s_rsrs:main.py:151:handleKline:2218689: df_s.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec  ...  index      beta    zscore  signal
717  20230526   120000    155959  1685087999  ...    717  0.620975  1.427004     1.0
718  20230526   160000    195959  1685102399  ...    718  0.627112  1.432435     1.0
719  20230526   200000    235959  1685116799  ...    719  0.605951  1.281364     1.0
720  20230527   000000    035959  1685131199  ...    720  0.597411  1.205087     1.0
721  20230527   040000    075959  1685145599  ...    721  0.595322  1.166378     1.0

[5 rows x 15 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '55.249', 'enterprice': '26128.2', 'countrevence': '0', 'unrealprofit': '31315.1332', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '26695', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'numpy.int64'>, curSign=1, self.sign=1


