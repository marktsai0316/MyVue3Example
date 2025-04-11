# MyVue3Example
### vue3helloworld.html
### vue3helloworld1.html
### vue3Apps.html
![image](https://github.com/user-attachments/assets/f4eea58c-d02c-4c0e-8590-62473fa94b90)

### vue3AppsCommEventBus.html
|  通信方法   | 優點  | 缺點 | 適用場景 |
|  ----  | ----  | ----  | ----  |
| 瀏覽器全域事件系統 (Event Bus)  | 輕量、簡單 | 需手動管理事件、較難除錯 | 簡單小應用

### vue3AppsCommSharedState.html
|  通信方法   | 優點  | 缺點 | 適用場景 |
|  ----  | ----  | ----  | ----  |
| 共享狀態	| 直接訪問數據	| 需手動保持響應性 |	父子容器結構 |

### vue3AppsCommLocalstorge.html
|  通信方法   | 優點  | 缺點 | 適用場景 |
|  ----  | ----  | ----  | ----  |
| localStorage  | 跨瀏覽器頁面通信	| 非即時、有安全性限制,須跨頁面	| 需要持久化的數據 |


### vue3Components.html
![image](https://github.com/user-attachments/assets/69da3cd3-0f11-4cbe-82b0-00cea9309c5b)

### vue3chartjs.html
![image](https://github.com/user-attachments/assets/814cdb20-420d-456f-8915-03911dfc97e9)

### vue3_Echarts_Chartjs.html
![image](https://github.com/user-attachments/assets/851f21d7-89a4-4762-9dab-4e48ce7d0356)

### vue3Localstorage.html
![image](https://github.com/user-attachments/assets/81bdbfae-ce4e-433f-9192-820664f32ebb)

### vue3LocalstorageEventLog.html
```
window.addEventListener('storage', handleStorageChange);
Note:僅會收到跨頁面storage changed Event,自己頁面handler不會收到
```
![image](https://github.com/user-attachments/assets/d8feb41a-df1f-4a6b-9203-50a11e886c7a)


