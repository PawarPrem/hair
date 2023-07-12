# hair-salon

Notes:
	
	I) Run composer install
		--If got bootstrap cache error then goes to following steps.	

		1) Create cache folder in bootstrap.
			--mkdir bootstrap/cache
			--run chmod 766 -R bootstrap.

		2) Create following folders.
			--mkdir storage/framework/{sessions,views,cache}
			--run chmod 766 -R storage.

		3) Add .env file.