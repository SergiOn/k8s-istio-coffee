FROM sdaschner/open-liberty:javaee8-tracing-jdk11-b5

COPY liberty/default-config.xml $CONFIG_DIR/configDropins/defaults/server.xml
COPY liberty/server.xml $CONFIG_DIR

COPY target/barista.war $DEPLOYMENT_DIR
