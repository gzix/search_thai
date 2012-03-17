การตั้งค่า
==========
คุณมี 2 ทางเลือก ใช้ Drush หรือ Drupal UI

โดย Drush commands
------------------
1. `drush en search_thai -y`
2. `drush search-reindex -y`
3. `drush cron`

โดย Drupal UI
-------------
เปิดใช้งานเหมือน module ทั่วไป แล้วก็ ...

1. ไปที่หน้าตั้งค่าการค้นหา `/admin/config/search/settings`
2. ถ้าต้องการเปลี่ยนจำนวนตัวอักษรที่จะอินเด็กซ์ ก็ระบุที่นั่น ค่า default คือ `3`
3. ถ้า *Simple Thai handling* ยังไม่ได้ติ๊กไว้ ก็ติ๊กซะ
4. Re-index เว็บไซต์ของคุณ
5. รัน cron จนกว่าจะครบ 100%

[ขัดข้องสงสัย?](http://webzer.net/contact)


CONFIGURATION
=============
You have 2 options via Drush Drupal UI

Via Drush commands
------------------
1. `drush en search_thai -y`
2. `drush search-reindex -y`
3. `drush cron`

Via Drupal UI
-------------
Enable the module as usual then ...

1. Go to search settings page `/admin/config/search/settings`
2. If you want to change default *Minimum word length to index*, input it there. Default is `3`.
3. If Simple Thai handling* is not checked by default, tick it there.
4. Re-index your site.
5. Run cron till you get 100% indexed.

[Any question?](http://webzer.net/contact)
