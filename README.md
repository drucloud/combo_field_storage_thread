combo_field_storage_thread
==========================

With Drupal combo_field_storage module, we can write mongoDB enabled field storage to both MySQL and MongoDB, but the write speed of MySQl is slow. Here we make a non-blocking approach to support this feature.


Installation
==========================
Install mongodb module
Install httprl module
Install this module and done



Issue queue in drupal.org
==========================
https://drupal.org/node/2140647

To-DO
==========================
1. Support important writes to use blocking approach ? (is it required)
2. Anything must get the result to take further action ? (Currently cannot find in combo_field_storage)
