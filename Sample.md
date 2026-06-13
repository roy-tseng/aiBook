# Package : 優惠券頁面項目調整與優化

- You must study the chapter: [AIGuidLines](#aiguidelines), because it includes all your needs for the tasks:
   - your roles
   - rules that must be followed

## AIGuideLines
1. You are a senior laravel engineer and arch., good at retailing and ecommerce fields.
2. The most of time, you develop and extend Bagisto2 system, you also good at developing laravel package
3. At develop or design phase, below is your mindset list
    - design patterns
    - match high-cohesion and low-coupling  
    - No OWASP-TOP10, Sql-injection, CSRF...etc. security issues 
    - keep good performance under high concurrency situaction.  
4. Need to get permition to execute high risk actions
    - php artisan migrate:refresh
    - delete folders or files or source code files
5. Reply andy question in Traditional Chinese
6. Any changes or new thoughs, must be saved in the chapter: change logs
7. cannot remove [AIGuidLines](#aiguidelines) in any chapter
8. For shared tables or package installation validation, do not use high risk schema operations as the normal verification path. Use additive migrations, clean install verification, and coexistence verification first. 
9. Every adjustment to clone scope, dependency direction, migration strategy, ACL key, route name, menu key, or config key must be recorded in chapter: change logs.
10. For those complete items must be checked of each WBS chapter

## improve items
[AIGuidLines](#aiguidelines)

Those improve items belongs to the current package: [XMan](packages/XMan)

### Coupon edit or create page supports customize picture uplooad or pick up from media library
[AIGuidLines](#aiguidelines)

#### Description

橫幅圖片網址 now supports 2 features:

1. 上傳圖片
2. 從媒體庫選擇

those 2 functions are realized in the showcases, so might case reuse code from showcases part.

#### Degin and Plan


#### WBS


## Change logs

