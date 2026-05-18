MoriFlow Commerce OS v18 — 多商家 SaaS 主帳號 / 子帳號 / 客戶端商城網址版

本版升級內容：
1. 賣家註冊後可建立自己的專屬商店。
2. 系統會產生客戶端商城網址，例如：?store=demo-store&mode=shop。
3. 賣家主帳號可在「帳號與商城」中新增商店、查看商城網址、預覽客戶端商城。
4. 主帳號可在「子帳號管理」新增後台子帳號並分配權限。
5. 子帳號可依權限管理訂單、商品、會員、廠商、支出、報表、設定。
6. 買家註冊會綁定目前所在商城，只會看到該賣家的商城與自己的會員資料。
7. 商品、訂單、會員、廠商、支出、設定以目前 store_id 做前端 Demo 隔離。

正式上線建議：
- Supabase Auth：Email / Google 登入、驗證碼、忘記密碼。
- Supabase Database：stores, store_users, products, orders, members, expenses, settings。
- Supabase RLS：用 store_id 隔離不同賣家的資料。
- Netlify：部署前端。

部署方式：
將此 ZIP 直接拖曳到 Netlify Deploy，或解壓後將資料夾內容上傳。
