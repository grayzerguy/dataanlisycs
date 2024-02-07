```python
import pandas as pd
```


```python
gotex = pd.read_excel("../User/Desktop/gotex.xls",sheet_name="QBaldar" )
```


```python
gotex.set_index("מס משלוח")
```




<div>
<style scoped>
    .dataframe tbody tr th:only-of-type {
        vertical-align: middle;
    }

    .dataframe tbody tr th {
        vertical-align: top;
    }

    .dataframe thead th {
        text-align: right;
    }
</style>
<table border="1" class="dataframe">
  <thead>
    <tr style="text-align: right;">
      <th></th>
      <th>תאריך קליטת משלוח</th>
      <th>מס תעודה</th>
      <th>ברקוד</th>
      <th>מס חבילות</th>
      <th>למקום</th>
      <th>שעת איסוף</th>
      <th>סטטוס משלוח</th>
      <th>סיבת כשל</th>
      <th>ממקום</th>
      <th>עיר מוצא</th>
      <th>שם לקוח</th>
      <th>רחוב יעד</th>
      <th>כפולה</th>
      <th>עיר יעד</th>
      <th>שעת ביצוע</th>
      <th>סהכ ללקוח</th>
      <th>מס שליחות שק</th>
      <th>סוג שליחות</th>
    </tr>
    <tr>
      <th>מס משלוח</th>
      <th></th>
      <th></th>
      <th></th>
      <th></th>
      <th></th>
      <th></th>
      <th></th>
      <th></th>
      <th></th>
      <th></th>
      <th></th>
      <th></th>
      <th></th>
      <th></th>
      <th></th>
      <th></th>
      <th></th>
      <th></th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <th>31904237</th>
      <td>2024-01-14 08:28:27.880</td>
      <td>NaN</td>
      <td>30153240032081061222</td>
      <td>0</td>
      <td>REH-REHOVOT MALL</td>
      <td>2024-01-14 11:48:51.010</td>
      <td>בוצע</td>
      <td>NaN</td>
      <td>ZARA לחניות</td>
      <td>רחובות</td>
      <td>ZARA לחניות</td>
      <td>בילו</td>
      <td>לא</td>
      <td>רחובות</td>
      <td>2024-01-28 14:16:51.137</td>
      <td>25.00</td>
      <td>NaN</td>
      <td>שליחות</td>
    </tr>
    <tr>
      <th>31951265</th>
      <td>2024-01-15 15:36:53.743</td>
      <td>5.313357e+10</td>
      <td>21259488111300100037</td>
      <td>1</td>
      <td>אלה אינדמן</td>
      <td>2024-01-15 17:25:57.023</td>
      <td>בוצע</td>
      <td>NaN</td>
      <td>ZARA</td>
      <td>באר שבע</td>
      <td>ZARA express</td>
      <td>שולמית</td>
      <td>כפול רגיל</td>
      <td>באר שבע</td>
      <td>2024-01-28 11:50:58.460</td>
      <td>23.25</td>
      <td>32138561.0</td>
      <td>שליחות</td>
    </tr>
    <tr>
      <th>31973150</th>
      <td>2024-01-16 15:26:46.863</td>
      <td>5.353009e+10</td>
      <td>21259584888700100037</td>
      <td>1</td>
      <td>עמית יעקב</td>
      <td>2024-01-16 17:25:16.527</td>
      <td>בוצע</td>
      <td>NaN</td>
      <td>ZARA</td>
      <td>ירושלים</td>
      <td>ZARA express</td>
      <td>עמק רפאים</td>
      <td>לא</td>
      <td>ירושלים</td>
      <td>2024-01-28 12:22:03.000</td>
      <td>15.50</td>
      <td>NaN</td>
      <td>שליחות</td>
    </tr>
    <tr>
      <th>31988807</th>
      <td>2024-01-17 12:36:58.740</td>
      <td>5.312233e+10</td>
      <td>21259696766900100030</td>
      <td>1</td>
      <td>חגית פוגל</td>
      <td>2024-01-17 14:50:00.443</td>
      <td>בוצע</td>
      <td>NaN</td>
      <td>ZARA</td>
      <td>בני ברק</td>
      <td>ZARA express</td>
      <td>הלוחמים</td>
      <td>לא</td>
      <td>בני ברק</td>
      <td>2024-01-28 12:37:09.000</td>
      <td>15.50</td>
      <td>NaN</td>
      <td>שליחות</td>
    </tr>
    <tr>
      <th>31990704</th>
      <td>2024-01-17 13:27:54.580</td>
      <td>5.312773e+10</td>
      <td>35759697352100100030</td>
      <td>1</td>
      <td>Anna-Maria Kushnarenko</td>
      <td>2024-01-23 22:11:26.380</td>
      <td>בוצע</td>
      <td>NaN</td>
      <td>ZARA</td>
      <td>ראשון לציון</td>
      <td>ZARA online</td>
      <td>אחד העם</td>
      <td>לא</td>
      <td>ראשון לציון</td>
      <td>2024-01-28 14:19:02.233</td>
      <td>15.50</td>
      <td>NaN</td>
      <td>שליחות</td>
    </tr>
    <tr>
      <th>...</th>
      <td>...</td>
      <td>...</td>
      <td>...</td>
      <td>...</td>
      <td>...</td>
      <td>...</td>
      <td>...</td>
      <td>...</td>
      <td>...</td>
      <td>...</td>
      <td>...</td>
      <td>...</td>
      <td>...</td>
      <td>...</td>
      <td>...</td>
      <td>...</td>
      <td>...</td>
      <td>...</td>
    </tr>
    <tr>
      <th>32157986</th>
      <td>2024-01-28 11:27:42.287</td>
      <td>5.303117e+10</td>
      <td>21261370363600100032</td>
      <td>1</td>
      <td>לירון רוזנטל</td>
      <td>2024-01-28 13:42:40.753</td>
      <td>בוצע</td>
      <td>NaN</td>
      <td>ZARA</td>
      <td>תל אביב</td>
      <td>ZARA express</td>
      <td>אייזיק שטרן</td>
      <td>לא</td>
      <td>תל אביב</td>
      <td>2024-01-28 15:34:27.540</td>
      <td>15.50</td>
      <td>NaN</td>
      <td>שליחות</td>
    </tr>
    <tr>
      <th>32158936</th>
      <td>2024-01-28 11:46:51.210</td>
      <td>8.007111e+10</td>
      <td>19360460510100100032</td>
      <td>1</td>
      <td>Shiran Chai</td>
      <td>2024-01-28 14:02:01.010</td>
      <td>בוצע</td>
      <td>NaN</td>
      <td>Zara Home</td>
      <td>רמת גן</td>
      <td>Zara Home</td>
      <td>הרי הגלעד</td>
      <td>לא</td>
      <td>רמת גן</td>
      <td>2024-01-28 17:12:14.783</td>
      <td>15.50</td>
      <td>NaN</td>
      <td>שליחות</td>
    </tr>
    <tr>
      <th>32158979</th>
      <td>2024-01-28 11:47:13.157</td>
      <td>8.007140e+10</td>
      <td>19360713610700100032</td>
      <td>1</td>
      <td>גיל קורדובה</td>
      <td>2024-01-28 13:03:20.910</td>
      <td>בוצע</td>
      <td>NaN</td>
      <td>Zara Home</td>
      <td>תל מונד</td>
      <td>Zara Home</td>
      <td>הכורם</td>
      <td>לא</td>
      <td>תל מונד</td>
      <td>2024-01-28 14:00:58.900</td>
      <td>15.50</td>
      <td>NaN</td>
      <td>שליחות</td>
    </tr>
    <tr>
      <th>32158996</th>
      <td>2024-01-28 11:47:19.690</td>
      <td>8.005155e+10</td>
      <td>19361095363600100036</td>
      <td>1</td>
      <td>Yarden Menachem</td>
      <td>2024-01-28 14:02:01.010</td>
      <td>בוצע</td>
      <td>NaN</td>
      <td>Zara Home</td>
      <td>רמת גן</td>
      <td>Zara Home</td>
      <td>רמבה</td>
      <td>לא</td>
      <td>רמת גן</td>
      <td>2024-01-28 16:54:34.717</td>
      <td>15.50</td>
      <td>NaN</td>
      <td>שליחות</td>
    </tr>
    <tr>
      <th>32158997</th>
      <td>2024-01-28 11:47:20.027</td>
      <td>8.005155e+10</td>
      <td>19361095363600200033</td>
      <td>1</td>
      <td>Yarden Menachem</td>
      <td>2024-01-28 14:02:01.010</td>
      <td>בוצע</td>
      <td>NaN</td>
      <td>Zara Home</td>
      <td>רמת גן</td>
      <td>Zara Home</td>
      <td>רמבה</td>
      <td>לא</td>
      <td>רמת גן</td>
      <td>2024-01-28 16:54:44.107</td>
      <td>15.50</td>
      <td>NaN</td>
      <td>שליחות</td>
    </tr>
  </tbody>
</table>
<p>922 rows × 18 columns</p>
</div>




```python
gotexb = pd.read_excel("../User/Desktop/זארה איסופים 6.2.xlsx")
```


```python
gotexb
```




<div>
<style scoped>
    .dataframe tbody tr th:only-of-type {
        vertical-align: middle;
    }

    .dataframe tbody tr th {
        vertical-align: top;
    }

    .dataframe thead th {
        text-align: right;
    }
</style>
<table border="1" class="dataframe">
  <thead>
    <tr style="text-align: right;">
      <th></th>
      <th>מס משלוח</th>
      <th>תאריך קליטת משלוח</th>
      <th>מס תעודה</th>
      <th>ברקוד</th>
      <th>מס חבילות</th>
      <th>למקום</th>
      <th>שעת איסוף</th>
      <th>סטטוס משלוח</th>
      <th>סיבת כשל</th>
      <th>ממקום</th>
      <th>עיר מוצא</th>
      <th>שם לקוח</th>
      <th>רחוב יעד</th>
      <th>כפולה</th>
      <th>עיר יעד</th>
      <th>שעת ביצוע</th>
      <th>סהכ ללקוח</th>
      <th>מס שליחות שק</th>
      <th>סוג שליחות</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <th>0</th>
      <td>32124078</td>
      <td>2024-01-25 01:36:49.577</td>
      <td>53138224525</td>
      <td>193752588001</td>
      <td>1</td>
      <td>HADE-ENERGY PARK</td>
      <td>2024-02-06 11:09:47.913</td>
      <td>נאסף</td>
      <td>אין מענה</td>
      <td>שני  קריקב</td>
      <td>חדרה</td>
      <td>ZARA online</td>
      <td>פרופ דן שכטמן</td>
      <td>לא</td>
      <td>חדרה</td>
      <td>NaN</td>
      <td>NaN</td>
      <td>NaN</td>
      <td>איסוף</td>
    </tr>
    <tr>
      <th>1</th>
      <td>32145915</td>
      <td>2024-01-27 13:56:52.483</td>
      <td>80050870330</td>
      <td>193999653001</td>
      <td>1</td>
      <td>TA-TLV SHOPPING MALL</td>
      <td>2024-02-06 13:16:52.210</td>
      <td>נאסף</td>
      <td>אין מענה</td>
      <td>כרמל  ברקוביץ</td>
      <td>תל אביב</td>
      <td>Zara Home</td>
      <td>חשמונאים</td>
      <td>לא</td>
      <td>תל אביב</td>
      <td>NaN</td>
      <td>NaN</td>
      <td>NaN</td>
      <td>איסוף</td>
    </tr>
    <tr>
      <th>2</th>
      <td>32177867</td>
      <td>2024-01-29 01:26:48.700</td>
      <td>53538810260</td>
      <td>194110272001</td>
      <td>1</td>
      <td>HADE-ENERGY PARK</td>
      <td>2024-02-06 19:48:36.910</td>
      <td>נאסף</td>
      <td>לקוח לא נכח בכתובת</td>
      <td>ליאור  פורת</td>
      <td>חדרה</td>
      <td>ZARA online</td>
      <td>פרופ דן שכטמן</td>
      <td>לא</td>
      <td>חדרה</td>
      <td>NaN</td>
      <td>NaN</td>
      <td>NaN</td>
      <td>איסוף</td>
    </tr>
    <tr>
      <th>3</th>
      <td>32183903</td>
      <td>2024-01-29 10:26:58.617</td>
      <td>53135431303</td>
      <td>194126445001</td>
      <td>1</td>
      <td>HADE-ENERGY PARK</td>
      <td>2024-02-06 12:21:02.427</td>
      <td>נאסף</td>
      <td>אין מענה</td>
      <td>Michele  Melloul</td>
      <td>חדרה</td>
      <td>ZARA online</td>
      <td>פרופ דן שכטמן</td>
      <td>לא</td>
      <td>חדרה</td>
      <td>NaN</td>
      <td>NaN</td>
      <td>NaN</td>
      <td>איסוף</td>
    </tr>
    <tr>
      <th>4</th>
      <td>32192518</td>
      <td>2024-01-29 14:36:54.213</td>
      <td>53121724709</td>
      <td>194152510001</td>
      <td>1</td>
      <td>HADE-ENERGY PARK</td>
      <td>2024-02-06 10:50:32.093</td>
      <td>נאסף</td>
      <td>אין מענה</td>
      <td>שרה  מילר</td>
      <td>חדרה</td>
      <td>ZARA online</td>
      <td>פרופ דן שכטמן</td>
      <td>לא</td>
      <td>חדרה</td>
      <td>NaN</td>
      <td>NaN</td>
      <td>NaN</td>
      <td>איסוף</td>
    </tr>
    <tr>
      <th>...</th>
      <td>...</td>
      <td>...</td>
      <td>...</td>
      <td>...</td>
      <td>...</td>
      <td>...</td>
      <td>...</td>
      <td>...</td>
      <td>...</td>
      <td>...</td>
      <td>...</td>
      <td>...</td>
      <td>...</td>
      <td>...</td>
      <td>...</td>
      <td>...</td>
      <td>...</td>
      <td>...</td>
      <td>...</td>
    </tr>
    <tr>
      <th>209</th>
      <td>32318232</td>
      <td>2024-02-06 10:56:50.927</td>
      <td>53122678111</td>
      <td>194862396001</td>
      <td>1</td>
      <td>HADE-ENERGY PARK</td>
      <td>2024-02-06 13:38:17.543</td>
      <td>נאסף</td>
      <td>NaN</td>
      <td>נטלי  אטיאס</td>
      <td>חדרה</td>
      <td>ZARA online</td>
      <td>פרופ דן שכטמן</td>
      <td>לא</td>
      <td>חדרה</td>
      <td>NaN</td>
      <td>NaN</td>
      <td>NaN</td>
      <td>איסוף</td>
    </tr>
    <tr>
      <th>210</th>
      <td>32318237</td>
      <td>2024-02-06 10:56:52.280</td>
      <td>53524589638</td>
      <td>194863894001</td>
      <td>1</td>
      <td>HADE-ENERGY PARK</td>
      <td>2024-02-06 13:47:34.450</td>
      <td>נאסף</td>
      <td>NaN</td>
      <td>עמית  אליפור</td>
      <td>חדרה</td>
      <td>ZARA online</td>
      <td>פרופ דן שכטמן</td>
      <td>לא</td>
      <td>חדרה</td>
      <td>NaN</td>
      <td>NaN</td>
      <td>NaN</td>
      <td>איסוף</td>
    </tr>
    <tr>
      <th>211</th>
      <td>32322037</td>
      <td>2024-02-06 13:06:50.130</td>
      <td>53566871848</td>
      <td>194870315001</td>
      <td>1</td>
      <td>HADE-ENERGY PARK</td>
      <td>2024-02-06 21:00:21.500</td>
      <td>נאסף</td>
      <td>NaN</td>
      <td>אפרת  אבוחצירא</td>
      <td>חדרה</td>
      <td>ZARA online</td>
      <td>פרופ דן שכטמן</td>
      <td>לא</td>
      <td>חדרה</td>
      <td>NaN</td>
      <td>NaN</td>
      <td>NaN</td>
      <td>איסוף</td>
    </tr>
    <tr>
      <th>212</th>
      <td>32322038</td>
      <td>2024-02-06 13:06:50.460</td>
      <td>53127725579</td>
      <td>194870316001</td>
      <td>1</td>
      <td>HADE-ENERGY PARK</td>
      <td>2024-02-06 21:00:04.103</td>
      <td>נאסף</td>
      <td>NaN</td>
      <td>אפרת  אבוחצירא</td>
      <td>חדרה</td>
      <td>ZARA online</td>
      <td>פרופ דן שכטמן</td>
      <td>לא</td>
      <td>חדרה</td>
      <td>NaN</td>
      <td>NaN</td>
      <td>NaN</td>
      <td>איסוף</td>
    </tr>
    <tr>
      <th>213</th>
      <td>32322040</td>
      <td>2024-02-06 13:06:51.070</td>
      <td>53577264942</td>
      <td>194870318001</td>
      <td>1</td>
      <td>HADE-ENERGY PARK</td>
      <td>2024-02-06 17:16:01.283</td>
      <td>נאסף</td>
      <td>NaN</td>
      <td>אילה  ברנשטיין</td>
      <td>חדרה</td>
      <td>ZARA online</td>
      <td>פרופ דן שכטמן</td>
      <td>לא</td>
      <td>חדרה</td>
      <td>NaN</td>
      <td>NaN</td>
      <td>NaN</td>
      <td>איסוף</td>
    </tr>
  </tbody>
</table>
<p>214 rows × 19 columns</p>
</div>




```python
gotexb.value_counts(["שם לקוח"])

```




    שם לקוח    
    ZARA online    202
    Zara Home       12
    Name: count, dtype: int64




```python
gotex.value_counts(["שם לקוח"])
```




    שם לקוח     
    ZARA express    433
    ZARA online     385
    ZARA לחניות      64
    Zara Home        40
    Name: count, dtype: int64




```python

```
