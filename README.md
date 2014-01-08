angular-client-directoy
=======================

angular 專案開發 client 的目錄結構


### 目錄結構說明:

- <client> (前端程式)
  - <src> (程式放置目錄)
    - <app> (主要程式目錄)
      - <依功能區分目錄> (如: user/、product/)
        - xxxController.js (Controller)
        - <templates> ( View 模版)
    - <assets> (網站素材)
      - <css> (css 檔案)
      - <sass> (sass 檔案)
      - <images> (使用圖片)
      - <fonts> (使用字型)
      - favicon.ico
    - <common> (共用程式)
      - <directive> (所有自訂的 Directive)
      - <filter> (所有自訂的 Filter)
      - <model> (所有自訂的 Model，商業邏輯處理)
      - <service> (所有自訂的 Service，HTTP/JSON 的資料取得終端)
      - <route> (所有自訂的 Route，路由設定)
  - <test> (測試程式)
  - <vendor> (第三方套件)
    - <bower_components> (bower 安裝套件目錄)
  - <dist> (Grunt 打包最終結果)   
  - <build> (放置 Grunt 打包自訂任務)
  - <node_modules> (npm 套件目錄)
  - package.json (npm 套件安裝描述檔)
  - .bowerrc (bower 安裝目錄路徑設定檔)
  - .gitignore
  - gruntFile.js (grunt 設定配置檔)
  
### 檔案命名說明:

- 模板命名方式為 **模板名稱**+**.tpl**+**.html**，如: _header.tpl.html_
- 模板檔案統一放置於 `templates` 目錄
- Model 的命名方式為 **功能名稱**+**Model.js**，如: _UserModel.js_
- Service 的命名方式為 **功能名稱**+**Service.js**，如: _UserService.js_
- Controller 的命名方式為 **功能名稱**+**Controller.js**，如: _UserController.js_

