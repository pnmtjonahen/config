#Config Server

configure the service using:

- cf create-service p-config-server trial myConfigServer -c '{"git": { "uri": "https://github.com/pnmtjonahen/config.git"} }'
