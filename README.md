|TABLE|COLUMN NAME|TYPE|DESCRIPTION|
|:---------|----------:|:----------:|:----------:|
|contents_sets|_id |integer primary key autoincrement||
||contentSetsId|integer|use _id of content_sets on base.db|
||name|varchar||
||version|integer||
||date|varchar||
||thumb|varchar||
||tag|varchar||
||category|varchar||
||size|integer||
|||||
|marker|_id|integer primary key autoincrement||
||name|varchar||
||media_ids|varchar|1 Marker- (1,n) Media saved in 1/2/3…|
||active|varchar||
||contentSetId|varchar|1 contentset-(1,n) marker|
|||||
|media|_id|integer primary key autoincrement||
||unique_name|varchar||
||name|varchar||
||type|integer||
||immediate|varchar||
||dx|varchar||
||dy|varchar||
||dz|varchar||
||rotatex|varchar||
||rotatey|varchar||
||rotatez|varchar||
||scalex|varchar||
||scaley|varchar||
||scalez|varchar||
||url|varchar||
|||||
|content|_id|integer primary key autoincrement||
||contentSetsId|varchar||
||url|varchar||
||url|varchar||
||url|varchar||
||url|varchar||
||url|varchar||
||url|varchar||
||url|varchar||

