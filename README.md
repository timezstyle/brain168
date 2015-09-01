# Global





* * *

## buyNextBar(price, value, method) 

**解釋:**

買下一根K棒的指定價格

**參數說明:**

**price**: `float`, 購買價格

**value**: `int`, 購買量(傳入負值會自動取決對值); 預設:1

**method**: `string`, 'limit':限價單,'stop':觸價單(market if touch); 預設:'limit'



## sellNextBar(price, value, method) 

**解釋:**

賣下一根K棒的指定價格

**參數說明:**

**price**: `float`, 賣出價格

**value**: `int`, 賣出量(傳入負值會自動取決對值); 預設:1

**method**: `string`, 'limit':限價單,'stop':觸價單(market if touch); 預設:'limit'



## buyStop(price, value) 

**解釋:**

觸價買進下一根K棒的指定價格

**參數說明:**

**price**: `float`, 買進價格

**value**: `int`, 買進量(傳入負值會自動取決對值); 預設:1



## buyLimit(price, value) 

**解釋:**

限價買進下一根K棒的指定價格

**參數說明:**

**price**: `float`, 買進價格

**value**: `int`, 買進量(傳入負值會自動取決對值); 預設:1



## sellStop(price, value) 

**解釋:**

觸價賣出下一根K棒的指定價格

**參數說明:**

**price**: `float`, 賣出價格

**value**: `int`, 賣出量(傳入負值會自動取決對值); 預設:1



## sellLimit(price, value) 

**解釋:**

限價賣出下一根K棒的指定價格

**參數說明:**

**price**: `float`, 賣出價格

**value**: `int`, 賣出量(傳入負值會自動取決對值); 預設:1



## win(price) 

**解釋:**

贏幾點

**參數說明:**

**price**: `float`, 贏多少點



## lose(price) 

**解釋:**

輸幾點

**參數說明:**

**price**: `float`, 輸多少點



## sum(n, column, before_days) 

**解釋:**

某欄位的加總

**參數說明:**

**n**: `int`, 幾根K棒

**column**: `string`, 欄位, 目前支援 'o','h','l','c','v'分別代表開盤,最高,最低,收盤,成交量; 預設:'c'

**before_days**: `int`, 前幾天



## avg(n, column, before_days) 

**解釋:**

某欄位的平均值

**參數說明:**

**n**: `int`, 幾根K棒

**column**: `string`, 欄位, 目前支援 'o','h','l','c','v'分別代表開盤,最高,最低,收盤,成交量; 預設:'c'

**before_days**: `int`, 前幾天



## max(n, column, before_days) 

**解釋:**

某欄位的最大值

**參數說明:**

**n**: `int`, 幾根K棒

**column**: `string`, 欄位, 目前支援 'o','h','l','c','v'分別代表開盤,最高,最低,收盤,成交量; 預設:'c'

**before_days**: `int`, 前幾天



## min(n, column, before_days) 

**解釋:**

某欄位的最小值

**參數說明:**

**n**: `int`, 幾根K棒

**column**: `string`, 欄位, 目前支援 'o','h','l','c','v'分別代表開盤,最高,最低,收盤,成交量; 預設:'c'

**before_days**: `int`, 前幾天



## before(before_days, column) 

**解釋:**

前幾天的某欄位值

**參數說明:**

**before_days**: `int`, 前幾天

**column**: `string`, 欄位, 目前支援 'o','h','l','c','v'分別代表開盤,最高,最低,收盤,成交量; 預設:'c'



## open(before_days) 

**解釋:**

前幾天的開盤價; 同before(before_days, 'o')

**參數說明:**

**before_days**: `int`, 前幾天



## high(before_days) 

**解釋:**

前幾天的最高價; 同before(before_days, 'h')

**參數說明:**

**before_days**: `int`, 前幾天



## low(before_days) 

**解釋:**

前幾天的最低價; 同before(before_days, 'l')

**參數說明:**

**before_days**: `int`, 前幾天



## close(before_days) 

**解釋:**

前幾天的收盤價; 同before(before_days, 'c')

**參數說明:**

**before_days**: `int`, 前幾天



## volume(before_days) 

**解釋:**

前幾天的成交量; 同before(before_days, 'v')

**參數說明:**

**before_days**: `int`, 前幾天



## carryDays() 

**解釋:**

持有天數




* * *










