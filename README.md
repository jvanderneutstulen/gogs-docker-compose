# gogs-docker-compose
docker-compose examples for jvanderneutstulen/gogs


## Usage

* Clone this repo
* Adjust settings in docker-compose.yml
* `docker-compose up`
* Open the ROOT_URL
* Verify settings, create user if needed
* Done


## Settings

See the [Gogs configuration cheat sheet][1] for more information.

### GOGS_APP_NAME
Default value: DockerGogs

### GOGS_RUN_USER
Default value: git

Do not change.

### GOGS_RUN_MODE
Default value: prod

Do not change.

### GOGS_DB_TYPE
Default value: sqlite3

### GOGS_DB_HOST
Default value: 127.0.0.1:5432

Not used for sqlite3

### GOGS_DB_NAME
Default value: gogs

Not used for sqlite3

### GOGS_DB_USER
Default value: root

Not used for sqlite3

### GOGS_DB_PASSWORD
No default value.

Not used for sqlite3

### GOGS_DB_SSL_MODE
Default value: disable

Only for postgresql

### GOGS_DB_PATH
Default value: data/gogs.db

For sqlite3, do not change.

### GOGS_ROOT
Default value: /data/git/gogs-repositories

Do not change.

### GOGS_DOMAIN
Default value: localhost

Should be the public hostname for cloning via ssh

### GOGS_HTTP_PORT
Default value: 3000

This port number must be exposed by docker. Should not be changed.

### GOGS_ROOT_URL
Default value: "http://localhost:3000/"

Should be the public website url.

### GOGS_DISABLE_SSH
Default value: false

### GOGS_SSH_PORT
Default value: 22

This port number must be exposed by docker. Should not be changed.

### GOGS_OFFLINE_MODE
Default value: false

### GOGS_MAIL_ENABLED
Default value: false

### GOGS_MAIL_HOST
Address of SMTP server, format hostname:port

### GOGS_MAIL_FROM

### GOGS_MAIL_USER

### GOGS_MAIL_PASSWD

### GOGS_MAIL_SKIP_VERIFY
Default value: false

### GOGS_REGISTER_EMAIL_CONFIRM
Default value: false

### GOGS_ENABLE_NOTIFY_MAIL
Default value: false

### GOGS_DISABLE_REGISTRATION
Default value: true

### GOGS_ENABLE_CAPTCHA
Default value: false

### GOGS_REQUIRE_SIGNIN_VIEW
Default value: true

### GOGS_DISABLE_GRAVATAR
Default value: true


[1]: https://gogs.io/docs/advanced/configuration_cheat_sheet "Gogs cheat sheet"
