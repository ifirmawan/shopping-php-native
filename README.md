# shopping-php-native
aplikasi toko onlen dari php native sebagai tugas TKJI kampus ITTelkom Purwokerto (collage assignment)

## Konfigurasi
1. Change database config in db.php

2. Change database name in:
	* cart/data.php
	* include/admin/header.php
	* include/home/header.php

	> ex. select * from petshop.order;
	> change it to: select * from databasename.order
	
	reason: in my situation, there is an error if you dont put the databasename before the table.

**Note:** You can find sql file in database folder
