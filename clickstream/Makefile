
data:
	kcat -P -l -b 127.0.0.1:64881 -t clicks data.json

table:
	pinot-admin AddTable \
		 -tableConfigFile click-table-kafka.json \
		 -schemaFile click-schema.json \
		 -controllerProtocol http \
		 -controllerHost localhost \
		 -controllerPort 9000 \
		 -exec
