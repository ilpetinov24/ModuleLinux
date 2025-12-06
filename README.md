1. sudo lsmod | grep tsulab                             // для просмотра модуля
2. sudo insmod tsulab.ko                                // загрузка модуля
3. sudo rmmod tsulab                                    // выгрузка модуля
4. modinfo tsulab.ko                                    // информация о модуле
5. sudo journalctl --since "1 hour ago" | grep kernel   // просмотр логов
