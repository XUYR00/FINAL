# 計算機畢業設計SSM員工宿舍管理系統
## 3.2可行性研究
>通過對系統研究目標及內容的分析審查後，提出可行性方案，並對其進行論述。主要從技術可行性出發，再進一步分析經濟可行性和操作可行性等方面。
### 3.2.1經濟可行性
>開發系統所涉及到的資料，一般是在圖書館查閱，或是在網上進行查找收集。所需要的一些應用軟件也都是在網上可以免費下載的，因此，開發成本幾乎為零。但是開發出來的系統，還是具有高效率，低成本，較高質量的。所以，從經濟可行性的角度，該系統符合標準。
### 3.2.2技術可行性
>技術可行性是考慮在現有的技術條件下，能否順利完成開發任務。以及判斷現有的軟硬件配置是否能滿足開發的需求。而本系統採用的是java技術開發，並非十分困難，所以在技術上是絕對可行的。此外，計算機硬件配置是完全符合發展的需求。
### 3.2.3運行可行性
>當前計算機信息化的知識已經十分普及了，現在的操作人員也都是對系統環境有很強的適應性，各類操作人員大都是有過培訓補充的，因此完全不影響組織結構，所以在運行上也是可行的。
### 3.2.4時間可行性
>從時間上看，在大四的最後一個學期，在實習工作與完成畢設兩件大事相交叉的時間裡，結合之前學習的相關知識，並開發系統，時間上是有點緊，但是也不是完全沒可能實現，通過這段時間的努力功能基本實現。
## 3.3系統業務過程分析
>員工宿舍管理系統是三種身份的用戶，主要涉及管理員、維修員和員工。每個身份都是操作起來都是清楚方便的。對於一些員工信息，這是任何人都可以查看的，但是如果用戶想進入後台進行操作，則必須是已經進行登錄的用戶，或者想修改員工宿舍信息的話，也是需要用戶登錄狀態。這些用戶的基本信息都由管理員對其統一管理。
>
>根據員工宿舍實際過程的分析，網站有以下幾個部分，其中用戶註冊，發布個人信息，修改個人信息；用戶註冊登錄，發布員工宿舍信息；管理員管理用戶信息；一般用戶只可以瀏覽不可以發布信息。以上業務過程從用戶角度可以分為三類 使用本系統的用戶角色，包括管理員、員工和維修員。以下針對各類用戶說明相應的業務過程。
## 3.4系統用例圖
>系統用例圖如下圖3-2所示:
>
> ![image](https://github.com/XUYR00/FINAL/blob/main/image/3.2drawio.png)
>
>圖3-2系統業務用例圖
## 4系統設計
## 4.1數據庫設計
>信息管理系統的效率和實現的效果完全取決於數據庫結構設計的好壞。為了保證數據完整性，提高數據庫存儲的效率，那麼統一合理地設計數據庫結構是必要的。數據庫設計一般包括如下幾個步驟:
#### (1)根據用戶需求，確定數據庫信息進行保存
>對用戶的需求分析是數據庫設計的第一階段，用戶的需求調研，熟悉小區運作流程，系統要求，這些都是以概念模型為基礎的。
#### (2)設計數據的概念模型
>概念模型與數據建模用戶的觀點一致，用於信息世界的建模工具。通過E-R圖可以清楚地描述系統涉及到的實體之間的相互關係。
>
>員工註冊實體圖如圖4-1所示:
>
> ![image](https://github.com/XUYR00/FINAL/blob/main/image/4.1drawio.png)
>
>圖4-1員工註冊實體圖
#
> 宿舍衛生管理實體圖如圖4-2所示:
>
> ![image](https://github.com/XUYR00/FINAL/blob/main/image/4-2.drawio.png)
>
>圖4-2宿舍衛生管理實體圖

### 5.1 登錄註冊模塊
> 員工宿舍管理系統，管理員、員工和維修員通過填寫用戶名、密碼等信息選擇角色進行登錄就可以使用了，如圖5-1所示。
> 
> ![image](https://github.com/XUYR00/FINAL/blob/main/image/5-1.png)
> 
> 圖5-1系統登錄界面圖
#
> 員工註冊，在員工註冊頁面通過填寫員工帳號、員工姓名、密碼、確認密碼、手機號碼、郵箱等信息完成員工註冊、如圖5-2所示。
> 
> ![image](https://github.com/XUYR00/FINAL/blob/main/image/5-2.png)
>  
> 圖5-2員工註冊界面圖
#
> 維修員註冊，通過填寫維修員帳號、維修員帳號、密碼、卻仁密碼、聯繫方式、郵箱等內容進行註冊等操作，如圖5-3所示。
>
> ![image](https://github.com/XUYR00/FINAL/blob/main/image/5-3.png)
> 
> 圖5-3維修員註冊界面圖
### 5.2管理員功能模塊
> 管理員登錄系統後，可以對首頁、個人中心、員工管理、維修員管理、宿舍信息管理、床位信息管理、宿舍衛生管理、員工入住管理、報修信息管理、分配任務管理、維修反饋管理、繳費中心管理、繳費紀錄管理等內容進行詳細操作，如圖5-4所示。
>
> ![image](https://github.com/XUYR00/FINAL/blob/main/image/5-4.png)
> 
> 圖5-4管理員功能界面圖
#
> 員工管理，在員工管理頁面中可以對索引、員工帳號、員工姓名、手機號碼、頭像、性別、郵箱、審核回復、審查狀態、審核等內容進行詳情、修改或刪除等操作，如圖5-5所示。
>
> ![image](https://github.com/XUYR00/FINAL/blob/main/image/5-5.png)
> 
> 圖5-5員工管理界面圖
#
> 維修員管理，在維修員管理頁面中可以對索引、維修員帳號、維修員姓名、聯繫號碼、頭像、性別、郵箱、審核回復、審查狀態、審核等內容進行詳情、修改或刪除等操作，如圖5-6所示。
>
> ![image](https://github.com/XUYR00/FINAL/blob/main/image/5-6.png)
> 
> 圖5-6維修員管理界面圖
# 
> 宿舍信息管理，在宿舍信息管理頁面可以對索引、宿舍名稱、位置、床位數、狀態等內容進行發布、宿舍衛生修改或刪除等操作，如圖5-7所示。
>
> ![image](https://github.com/XUYR00/FINAL/blob/main/image/5-7.png)
> 
> 圖5-7宿舍信息管理界面圖
#
> 床位信息管理，在床位信息管理頁面可以對索引、宿舍名稱、位置、床位數等內容進行詳情、員工入住、修改或刪除等操作，如圖5-8所示。
>
> ![image](https://github.com/XUYR00/FINAL/blob/main/image/5-8.png)
> 
> 圖5-8床位信息管理界面圖
#
> 宿舍衛生管理，在宿舍衛生管理頁面可以對索引、宿舍名稱、位置、是否消毒、消毒時間、時間等內容進行詳情、修改或刪除等操作，如圖5-9所示。
>
> ![image](https://github.com/XUYR00/FINAL/blob/main/image/5-9.png)
> 
> 圖5-9宿舍衛生管理界面圖
#
> 員工入住管理，在員工入住管理頁面可以對索引、宿舍名稱、位置、床位數、員工帳號、員工姓名等內容進行詳情、修改或刪除等操作，如圖5-10所示。
> 
> ![image](https://github.com/XUYR00/FINAL/blob/main/image/5-10.png)
> 
> 圖5-10員工入住管理界面圖
#
> 報修信息管理，在報修信息管理頁面可以對索引、宿舍名稱、位置、報修名稱、員工帳號、員工姓名，上報日期、審核回復、審核狀態，審核等內容進行詳情、分配任務、修改或刪除等操作，如圖5-11所示。
>
> ![image](https://github.com/XUYR00/FINAL/blob/main/image/5-11.png)
> 
> 圖5-11報修信息管理界面圖
#
> 分配任務管理，在分配任務管理頁面可以對索引、宿舍名稱、位置、報修名稱、員工帳號、員工姓名，上報日期、維修員帳號、維修員姓名、分配時間等內容進行詳情、修改或刪除等操作，如圖5-12所示。
>
> ![image](https://github.com/XUYR00/FINAL/blob/main/image/5-12.png)
> 
> 圖5-12分配任務管理界面圖


