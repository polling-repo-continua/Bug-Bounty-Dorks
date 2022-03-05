# Bug Bounty Dorks

## Google Dorks
```
site:accounts..com/signin/ intitle:"index of" drupal intitle:"index of" admin inurl:login.cgiPages Containing Login Portals site:/joomla/administrator
inurl:"server-status" intitle:"Apache Status" intext:"Apache Server Status for"
inurl:/login/index.jsp -site:hertz.*
intitle:"Index of" inurl:wp-json/oembed
intitle:"Index of" phpmyadmin
intitle:"Index of" wp-admin
intitle:index.of.?.sql
inurl: /filemanager/dialog.php
s3 site:amazonaws.com filetype:log
inurl:cgi/login.pl
inurl:zoom.us/j and intext:scheduled for
site:*/auth intitle:login
inurl: admin/login.aspxPages Containing Login Portals
"Index of" inurl:webalizer
"Index of" inurl:phpmyadmin
"Index of" inurl:htdocs inurl:xampp
s3 site:amazonaws.com intext:dhcp filetype:txt inurl:apollo
inurl:/index.aspx/login
site:amazonaws.com inurl:login.php
intitle:"IIS Windows Server" -inurl:"IIS Windows Server"
intitle:"Apache2 Ubuntu Default Page: It works"
inurl:/filedown.php?file=
inurl:Dashboard.jspa intext:"Atlassian Jira Project Management Software"
inurl:app/kibana intext:Loading Kibana
site:https://docs.google.com/spreadsheets edit
inurl:8443 AND -intitle:8443 AND -intext:8443 prohibited|restricted|unauthorized
intitle:"index of" unattend.xml
inurl:/admin/index.php
inurl:bc.googleusercontent.com intitle:index of
inurl:office365 AND intitle:"Sign In | Login | Portal"
intext:"@gmail.com" AND intext:"@yahoo.com" filetype:sql
intitle:OmniDB intext:"user. pwd. Sign in."
intitle:"qBittorrent Web UI" inurl:8080
site:com inurl:jboss filetype:log -github.com
intitle:"index of" ".cpanel/caches/config/"
inurl:'/scopia/entry/index.jsp'
inurl:/index.aspx/login
intitle: "index of" "./" "./bitcoin"
inurl:/portal/apis/fileExplorer/
intitle:"index of" "/aws.s3/"
intitle:"index of" hosts.csv | firewalls.csv | linux.csv | windows.csv
intitle:Test Page for the Nginx HTTP Server on Fedora
inurl:_cpanel/forgotpwd
intitle:"index of /" intext:/backup
intitle:"Swagger UI - " + "Show/Hide"
site:drive.google.com /preview intext:movie inurl:flv | wmv | mp4 -pdf -edit -view
intext:"class JConfig {" inurl:configuration.php
"index of" "database.sql.zip"
ext:(doc | pdf | xls | txt | ps | rtf | odt | sxw | psw | ppt | pps | xml) (intext:confidential salary | intext:"budget approved") inurl:confidential
ext:(doc | pdf | xls | txt | ps | rtf | odt | sxw | psw | ppt | pps | xml) (intext:confidential salary | intext:”budget approved”) inurl:confidential
ext:inc "pwd=" "UID="
ext:ini intext:env.ini
ext:ini Version=... password
ext:ini Version=4.0.0.4 password
ext:ini eudora.ini
ext:ini intext:env.ini
ext:log "Software: Microsoft Internet Information Services *.*"
ext:log "Software: Microsoft Internet Information
ext:log "Software: Microsoft Internet Information Services *.*"
ext:log \"Software: Microsoft Internet Information Services *.*\"
ext:mdb   inurl:*.mdb inurl:fpdb shop.mdb
ext:mdb inurl:*.mdb inurl:fpdb shop.mdb
ext:mdb inurl:*.mdb inurl:fpdb shop.mdb
filetype:SWF SWF
filetype:TXT TXT
filetype:XLS XLS
filetype:asp   DBQ=" * Server.MapPath("*.mdb")
filetype:asp "Custom Error Message" Category Source
filetype:asp + "[ODBC SQL"
filetype:asp DBQ=" * Server.MapPath("*.mdb")
filetype:asp DBQ=\" * Server.MapPath(\"*.mdb\") 
filetype:asp “Custom Error Message” Category Source
filetype:bak createobject sa
filetype:bak inurl:"htaccess|passwd|shadow|htusers"
filetype:bak inurl:\"htaccess|passwd|shadow|htusers\" 
filetype:conf inurl:firewall -intitle:cvs 
filetype:conf inurl:proftpd. PROFTP FTP server configuration file reveals
filetype:dat "password.dat
filetype:dat \"password.dat\" 
filetype:eml eml +intext:"Subject" +intext:"From" +intext:"To"
filetype:eml eml +intext:\"Subject\" +intext:\"From\" +intext:\"To\" 
filetype:eml eml +intext:”Subject” +intext:”From” +intext:”To”
filetype:inc dbconn 
filetype:inc intext:mysql_connect
filetype:inc mysql_connect OR mysql_pconnect 
filetype:log inurl:"password.log"
filetype:log username putty PUTTY SSH client logs can reveal usernames
filetype:log “PHP Parse error” | “PHP Warning” | “PHP Error”
filetype:mdb inurl:users.mdb
filetype:ora ora
filetype:ora tnsnames
filetype:pass pass intext:userid
filetype:pdf "Assessment Report" nessus
filetype:pem intext:private
filetype:properties inurl:db intext:password
filetype:pst inurl:"outlook.pst"
filetype:pst pst -from -to -date
filetype:reg reg +intext:"defaultusername" +intext:"defaultpassword"
filetype:reg reg +intext:\"defaultusername\" +intext:\"defaultpassword\" 
filetype:reg reg +intext:â? WINVNC3â?
filetype:reg reg +intext:”defaultusername” +intext:”defaultpassword”
filetype:reg reg HKEY_ Windows Registry exports can reveal
filetype:reg reg HKEY_CURRENT_USER SSHHOSTKEYS
filetype:sql "insert into" (pass|passwd|password)
filetype:sql ("values * MD5" | "values * password" | "values * encrypt")
filetype:sql (\"passwd values\" | \"password values\" | \"pass values\" ) 
filetype:sql (\"values * MD\" | \"values * password\" | \"values * encrypt\") 
filetype:sql +"IDENTIFIED BY" -cvs
filetype:sql password
filetype:sql password 
filetype:sql “insert into” (pass|passwd|password)
filetype:url +inurl:"ftp://" +inurl:";@"
filetype:url +inurl:\"ftp://\" +inurl:\";@\" 
filetype:url +inurl:”ftp://” +inurl:”;@”
filetype:xls inurl:"email.xls"
filetype:xls username password email
index of: intext:Gallery in Configuration mode
index.of passlist
index.of perform.ini mIRC IRC ini file can list IRC usernames and
index.of.dcim 
index.of.password 
intext:" -FrontPage-" ext:pwd inurl:(service | authors | administrators | users)
intext:""BiTBOARD v2.0" BiTSHiFTERS Bulletin Board"
intext:"# -FrontPage-" ext:pwd inurl:(service | authors | administrators | users) "# -FrontPage-" inurl:service.pwd
intext:"#mysql dump" filetype:sql
intext:"#mysql dump" filetype:sql 21232f297a57a5a743894a0e4a801fc3
intext:"A syntax error has occurred" filetype:ihtml
intext:"ASP.NET_SessionId" "data source="
intext:"About Mac OS Personal Web Sharing"
intext:"An illegal character has been found in the statement" -"previous message"
intext:"AutoCreate=TRUE password=*"
intext:"Can't connect to local" intitle:warning
intext:"Certificate Practice Statement" filetype:PDF | DOC
intext:"Certificate Practice Statement" inurl:(PDF | DOC)
intext:"Copyright (c) Tektronix, Inc." "printer status"
intext:"Copyright © Tektronix, Inc." "printer status"
intext:"Emergisoft web applications are a part of our"
intext:"Error Diagnostic Information" intitle:"Error Occurred While"
intext:"Error Message : Error loading required libraries."
intext:"Establishing a secure Integrated Lights Out session with" OR intitle:"Data Frame - Browser not HTTP 1.1 compatible" OR intitle:"HP Integrated Lights-
intext:"Fatal error: Call to undefined function" -reply -the -next
intext:"Fill out the form below completely to change your password and user name. If new username is left blank, your old one will be assumed." -edu
intext:"Generated   by phpSystem"
intext:"Generated by phpSystem"
intext:"Host Vulnerability Summary Report"
intext:"HostingAccelerator" intitle:"login" +"Username" -"news" -demo
intext:"IMail Server Web Messaging" intitle:login
intext:"Incorrect syntax near"
intext:"Index of" /"chat/logs"
intext:"Index of /network" "last modified"
intext:"Index of /" +.htaccess
intext:"Index of /" +passwd
intext:"Index of /" +password.txt
intext:"Index of /admin"
intext:"Index of /backup"
intext:"Index of /mail"
intext:"Index of /password"
intext:"Microsoft (R) Windows * (TM) Version * DrWtsn32 Copyright (C)" ext:log
intext:"Microsoft CRM : Unsupported Browser Version"
intext:"Microsoft ® Windows * ™ Version * DrWtsn32 Copyright ©" ext:log
intext:"Network Host Assessment Report" "Internet Scanner"
intext:"Network Vulnerability   Assessment Report"
intext:"Network Vulnerability Assessment Report"
intext:"Network Vulnerability Assessment Report" 本文来自 pc007.com
intext:"SQL Server Driver][SQL Server]Line 1: Incorrect syntax near"
intext:"Thank you for your order"   +receipt
intext:"Thank you for your order" +receipt
intext:"Thank you for your purchase" +download
intext:"The following report contains confidential information" vulnerability -search
intext:"phpMyAdmin MySQL-Dump" "INSERT INTO" -"the"
intext:"phpMyAdmin MySQL-Dump" filetype:txt
intext:"phpMyAdmin" "running on" inurl:"main.php"
intextpassword | passcode)   intextusername | userid | user) filetype:csv
intextpassword | passcode) intextusername | userid | user) filetype:csv
intitle:"index of" +myd size
intitle:"index of" etc/shadow
intitle:"index of" htpasswd
intitle:"index of" intext:connect.inc
intitle:"index of" intext:globals.inc
intitle:"index of" master.passwd
intitle:"index of" master.passwd 007电脑资讯
intitle:"index of" members OR accounts
intitle:"index of" mysql.conf OR mysql_config
intitle:"index of" passwd
intitle:"index of" people.lst
intitle:"index of" pwd.db
intitle:"index of" spwd
intitle:"index of" user_carts OR user_cart
intitle:"index.of *" admin news.asp configview.asp
intitle:("TrackerCam Live Video")|("TrackerCam Application Login")|("Trackercam Remote") -trackercam.com
intitle:(“TrackerCam Live Video”)|(“TrackerCam Application Login”)|(“Trackercam Remote”) -trackercam.com
inurl:admin inurl:userlist Generic userlist files
inurl:php?=id1
inurl:index.php?id=
inurl:trainers.php?id=
inurl:buy.php?category=
inurl:article.php?ID=
inurl:play_old.php?id=
inurl:declaration_more.php?decl_id=
inurl:pageid=
inurl:games.php?id=
inurl:page.php?file=
inurl:newsDetail.php?id=
inurl:gallery.php?id=
inurl:article.php?id=
inurl:show.php?id=
inurl:staff_id=
inurl:newsitem.php?num= andinurl:index.php?id=
inurl:trainers.php?id=
inurl:buy.php?category=
inurl:article.php?ID=
inurl:play_old.php?id=
inurl:declaration_more.php?decl_id=
inurl:pageid=
inurl:games.php?id=
inurl:page.php?file=
inurl:newsDetail.php?id=
inurl:gallery.php?id=
inurl:article.php?id=
inurl:show.php?id=
inurl:staff_id=
inurl:newsitem.php?num=
	
```

## GitHub Dorks

```
"access_key"
access_key
"access_token"
access-token
access_token
accesstoken
access_token_secret
admin
admin_pass
admin_user
algolia_admin_key
algolia_api_key
alias_pass
alicloud_access_key
"amazonaws"
amazonaws
amazon_secret_access_key
ansible_vault_password
aos_key
"apidocs"
apidocs
"api.googlemaps AIza"
api.googlemaps AIza
api.googlemaps+AIza
"api_key"
"apikey"
api-key
api_key
apikey
“api keys”
api_key_secret
api_key_sid
"api_secret"
api_secret
"apiSecret"
apiSecret
api_secret_key
“api token”
api_token
api_token:
app_debug
app_id
"app_key"
"appkey"
app_key
appkey
"appkeysecret"
appkeysecret
"application_key"
application_key
app_log_level
"app_secret"
"appsecret"
app_secret
appsecret
"appspot"
appspot
"auth"
auth
authentication
authkey
authorization
authorization_bearer:
authorization_key
authorization_token
"authorizationToken"
authorizationToken
authsecret
"auth_token"
auth_token
authtoken
"aws_access"
aws_access
"aws_access_key_id"
aws_access_key_id
aws_bucket
"aws_key"
aws_key
"aws_secret"
aws_secret
aws_secret_access_key
aws_secret_key
"AWSSecretKey"
AWSSecretKey
"aws_token"
aws_token
b2_app_key
"bashrc password"
bashrc password
bashrc+password
bearer
bintray_apikey
bintray_gpg_password
bintray_key
bintraykey
bluemix_api_key
bluemix_pass
bot_access_token
browserstack_access_key
bucket
bucketeer_aws_access_key_id
bucketeer_aws_secret_access_key
"bucket_password"
bucket_password
built_branch_deploy_key
bx_password
cache_driver
cache_s3_secret_key
cattle_access_key
cattle_secret_key
certificate_password
ci_deploy_password
client_id
client_key
"client_secret"
client-secret
client_secret
clientsecret
client_zpk_secret_key
clojars_password
cloudant_password
cloud_api_key
cloudflare_api_key
cloudflare_auth_key
"cloudfront"
cloudinary_api_secret
cloudinary_name
cloud_watch_aws_access_key
"codecov_token"
codecov_token
"config"
config
"connectionstring"
connectionstring
"conn.login"
conn.login
"consumer_key"
consumer_key
ConsumerKey
consumer_secret
ConsumerSecret
"credentials"
credentials
cypress_record_key
"database_password"
database_password
database_schema_test
datadog_api_key
datadog_app_key
DB_DATABASE=
DB_HOST=
"dbpasswd"
dbpasswd
"db_password"
"dbpassword"
db_password
dbpassword
DB_PASSWORD=
DB_PORT=
DB_PW=
db_server
"dbuser"
dbuser
DB_USER=
"db_username"
db_username
DB_USERNAME
deploy_password
digitalocean_ssh_key_body
digitalocean_ssh_key_ids
docker_hub_password
dockerhub_password
dockerhubpassword
docker_key
docker_pass
docker_passwd
docker_password
"dot-files"
"dotfiles"
dot-files
dotfiles
droplet_travis_password
dynamoaccesskeyid
dynamosecretaccesskey
elastica_host
elastica_port
elasticsearch_password
email
"encryption_key"
encryption-key
encryption_key
encryptionkey
encryption_password
env.heroku_api_key
env.sonatype_password
eureka.awssecretkey
extension:avastlic "support.avast.com"
extension:avastlic support.avast.com
extension:avastlic+support.avast.com
extension:bat
extension:cfg
extension:dbeaver-data-sources.xml
extension:env
extension:exs
extension:ini
extension:json api.forecast.io
extension:json+api.forecast.io
extension:json googleusercontent client_secret
extension:json+googleusercontent+client_secret
extension:json mongolab.com
extension:json+mongolab.com
extension:pem
extension:pem private
extension:pem+private
extension:ppk
extension:ppk private
extension:ppk+private
extension:properties
extension:sh
extension:sls
extension:sql
extension:sql mysql dump
extension:sql+mysql+dump
extension:sql mysql dump password
extension:sql+mysql+dump+password
extension:yaml mongolab.com
extension:yaml+mongolab.com
extension:zsh
"fabricApiSecret"
fabricApiSecret
facebook_secret
"fb_secret"
fb_secret
filename:bash
filename:.bash_history
filename:bash_history
filename:bash_profile
filename:.bash_profile aws
filename:.bash_profile+aws
filename:bashrc
filename:.bashrc mailchimp
filename:.bashrc+mailchimp
filename:.bashrc password
filename:.bashrc+password
filename:beanstalkd.yml
filename:CCCam.cfg
filename:composer.json
filename:config
filename:config irc_pass
filename:config+irc_pass
filename:config.json auths
filename:config.json+auths
filename:config.php dbpasswd
filename:config.php+dbpasswd
filename:configuration.php JConfig password
filename:configuration.php+JConfig+password
filename:connections
filename:connections.xml
filename:constants
filename:credentials
filename:credentials aws_access_key_id
filename:credentials+aws_access_key_id
filename:.cshrc
filename:cshrc
filename:database
filename:dbeaver-data-sources.xml
filename:deployment-config.json
filename:deploy.rake
filename:dhcpd.conf
filename:dockercfg
filename:.dockercfg auth
filename:.dockercfg+auth
filename:env
filename:.env DB_USERNAME NOT homestead
filename:.env+DB_USERNAME+NOT+homestead
filename:environment
filename:.env MAIL_HOST=smtp.gmail.com
filename:.env MAIL_HOSTsmtp.gmail.com
filename:.env+MAIL_HOSTsmtp.gmail.com
filename:.esmtprc password
filename:.esmtprc+password
filename:express.conf
filename:express.conf path:.openshift
filename:express.conf+path:.openshift
filename:filezilla.xml
filename:filezilla.xml Pass
filename:filezilla.xml+Pass
filename:.ftpconfig
filename:gitconfig
filename:.git-credentials
filename:git-credentials
filename:global
filename:.history
filename:history
filename:.htpasswd
filename:htpasswd
filename:hub oauth_token
filename:hub+oauth_token
filename:id_dsa
filename:idea14.key
filename:id_rsa
filename:id_rsa or filename:id_dsa
filename:id_rsa+or+filename:id_dsa
filename:known_hosts
filename:logins.json
filename:makefile
filename:master.key path:config
filename:master.key+path:config
filename:netrc
filename:.netrc password
filename:.netrc+password
filename:_netrc password
filename:_netrc+password
filename:npmrc
filename:.npmrc _auth
filename:.npmrc+_auth
filename:pass
filename:passwd path:etc
filename:passwd+path:etc
filename:.pgpass
filename:pgpass
filename:prod.exs
filename:prod.exs NOT prod.secret.exs
filename:prod.exs+NOT+prod.secret.exs
filename:prod.secret.exs
filename:proftpdpasswd
filename:recentservers.xml
filename:recentservers.xml Pass
filename:recentservers.xml+Pass
filename:.remote-sync.json
filename:robomongo.json
filename:.s3cfg
filename:s3cfg
filename:secrets.yml password
filename:secrets.yml+password
filename:server.cfg
filename:server.cfg rcon password
filename:server.cfg+rcon+password
filename:settings
filename:settings.py SECRET_KEY
filename:settings.py+SECRET_KEY
filename:sftp-config.json
filename:sftp-config.json password
filename:sftp.json path:.vscode
filename:sftp.json+path:.vscode
filename:shadow
filename:shadow path:etc
filename:shadow+path:etc
filename:.sh_history
filename:spec
filename:sshd_config
filename:travis.yml
filename:tugboat
filename:.tugboat NOT _tugboat
filename:.tugboat+NOT+_tugboat
filename:ventrilo_srv.ini
filename:vim_settings.xml
filename:WebServers.xml
filename:wp-config
filename:wp-config.php
filename:zhrc
"firebase"
firebase
flickr_api_key
fossa_api_key
"ftp"
ftp
ftp_password
FTP_PASSWORD
FTP_PORT
gatsby_wordpress_base_url
gatsby_wordpress_client_id
gatsby_wordpress_user
gh_api_key
ghost_api_key
"gh_token"
gh_token
github_api_key
github_deploy_hb_doc_pass
github_id
"github_key"
github_key
github_password
"github_token"
github_token
"gitlab"
gitlab
"gmail_password"
gmail_password
"gmail_username"
gmail_username
google_maps_api_key
google_private_key
google_secret
google_server_key
gpg_key_name
gpg_keyname
gpg_passphrase
HEROKU_API_KEY
HEROKU_API_KEY language:json
HEROKU_API_KEY+language:json
HEROKU_API_KEY language:shell
HEROKU_API_KEY+language:shell
"herokuapp"
herokuapp
heroku_oauth
heroku_oauth_secret
heroku_oauth_token
heroku_secret
heroku_secret_token
HOMEBREW_GITHUB_API_TOKEN
HOMEBREW_GITHUB_API_TOKEN language:shell
HOMEBREW_GITHUB_API_TOKEN+language:shell
htaccess_pass
htaccess_user
id_dsa
incident_channel_name
"internal"
internal
"irc_pass"
irc_pass
"JEKYLL_GITHUB_TOKEN"
JEKYLL_GITHUB_TOKEN
jsforce extension:js conn.login
jsforce+extension:js+conn.login
jwt_client_secret_key
jwt_lookup_secert_key
jwt_password
jwt_secret
jwt_secret_key
jwt_token
jwt_user
jwt_web_secert_key
jwt_xmpp_secert_key
"key"
key
"keyPassword"
keyPassword
language:bash ftp
language:python ftp
language:shell username
language:sql username
language:yaml -filename:travis
language:yaml+-filename:travis
"ldap_password"
ldap_password
"ldap_username"
ldap_username
linux_signing_key
ll_shared_key
location_protocol
log
log_channel
"login"
login
lottie_happo_api_key
lottie_happo_secret_key
lottie_s3_api_key
lottie_s3_secret_key
magento password
magento+password
"mailchimp"
mailchimp
mailchimp_api_key
mailchimp_key
"mailgun"
mailgun
mailgun apikey
mailgun+apikey
mailgun_key
mailgun_password
mailgun_priv_key
mailgun_secret_api_key
mail_password
mail_port
manage_key
mandrill_api_key
mapbox api key
mapbox+api+key
"master_key"
master_key
mg_api_key
mg_public_api_key
mh_apikey
mh_password
mile_zero_key
minio_access_key
minio_secret_key
mix_pusher_app_cluster
mix_pusher_app_key
".mlab.com password"
.mlab.com password
.mlab.com+password
msg nickserv identify filename:config
msg+nickserv+identify+filename:config
"mydotfiles"
mydotfiles
"mysql"
mysql
mysql password
mysql+password
mysql_root_password
netlify_api_key
nexus password
nexus+password
nexus_password
"node_env"
node_env
node_pre_gyp_accesskeyid
node_pre_gyp_secretaccesskey
npm_api_key
npm_password
"npmrc _auth"
npmrc _auth
npmrc+_auth
npm_secret_key
nuget_api_key
nuget_apikey
nuget_key
number
oauth
"oauth_token"
oauth_token
object_storage_password
octest_app_password
octest_password
okta_key
omise_key
onesignal_api_key
onesignal_user_auth_key
openwhisk_key
org_gradle_project_sonatype_nexus_password
org_project_gradle_sonatype_nexus_password
os_password
ossrh_jira_password
ossrh_pass
ossrh_password
OTP
pagerduty_apikey
parse_js_key
"pass"
pass
passcode
"passwd"
passwd
"password"
password
password hash
"passwords"
passwords
password travis
password+travis
path:sites databases password
path:sites+databases+password
paypal_secret
paypal_token
"pem private"
pem private
pem+private
personal_key
playbooks_url
plotly_apikey
plugin_password
postgres_env_postgres_password
postgresql_pass
"preprod"
preprod
private
"private_key"
private-key
private_key
privatekey
private -language:java
private+-language:java
private_signing_password
"prod"
prod
prod.access.key.id
prod_password
prod.secret.key
PT_TOKEN
PT_TOKEN language:bash
PT_TOKEN+language:bash
publish_key
pusher_app_id
"pwd"
pwd
"pwds"
queue_driver
rabbitmq_password
"rds.amazonaws.com password"
rds.amazonaws.com password
rds.amazonaws.com+password
"redis_password"
redis_password
remove password
response_auth_jwt_secret
rest_api_key
rinkeby_private_key
root
"root_password"
root_password
ropsten_private_key
route53_access_key_id
rtd_key_pass
rtd_store_pass
s3_access_key
s3_access_key_id
s3_key
s3_key_app_logs
s3_key_assets
s3_secret_key
salesforce_password
sandbox_aws_access_key_id
sandbox_aws_secret_access_key
sauce_access_key
"secret"
secret
"secret_access_key"
secret access key
secret+access+key
secret_access_key
secretaccesskey
secret_bearer
"secret_key"
secret-key
secret_key
secretkey
secret_key_base
"secret.password"
secret.password
"secrets"
secrets
"secret_token"
secret_token
"secure"
secure
"security_credentials"
security_credentials
sendgrid_api_key
sendgrid_key
sendgrid_password
"send.keys"
"send_keys"
"sendkeys"
send.keys
send_keys
sendkeys
ses_access_key
ses_secret_key
session_key
session_secret
SESSION_TOKEN
setdstaccesskey
setsecretkey
"sf_username"
sf_username
SF_USERNAME
"SF_USERNAME salesforce"
SF_USERNAME salesforce
SF_USERNAME+salesforce
shodan_api_key language:python
shodan_api_key+language:python
sid_token
signing_key_password
signing_key_secret
"slack_api"
slack_api
slack_api_token
SLACK_BOT_TOKEN
slack_channel
slack_key
slack_outgoing_token
slack_secret_token
slack_signing_secret
"slack_token"
slack_token
slack_webhook
slash_developer_space_key
snoowrap_password
socrata_password
sonar_organization_key
sonar_project_key
sonatype_password
sonatype_token_password
soundcloud_password
"sql_password"
sql_password
sqsaccesskey
square_access_token
squareSecret
square_token
"ssh"
ssh
"ssh2_auth_password"
ssh2_auth_password
ssh-key
ssh_key
sshkey
"sshpass"
sshpass
"staging"
staging
"stg"
stg
"storePassword"
storePassword
stormpath_api_key_id
stormpath_api_key_secret
"stripe"
stripe
stripe_key
stripe_secret
strip_key
strip_secret_key
stripToken
svn_pass
"swagger"
swagger
tesco_api_key
tester_keys_password
"testuser"
testuser
thera_oss_access_key
"token"
token
trash
trusted_hosts
twilio_account_id
twilio_account_secret
twilio_account_sid
twilio_accountsid
twilio_acount_sid NOT env
twilio_acount_sid+NOT+env
twilio_api
twilio_api_auth
twilioapiauth
twilio_api_key
twilio_api_secret
twilio_api_sid
twilio_api_token
twilio secret
twilio+secret
twilio_secret
twiliosecret
twilio_secret_token
TWILIO_SID NOT env
TWILIO_SID+NOT+env
twilio_token
twine_password
twitterKey
twitter_secret
user auth
username
user_pass
user_password
[WFClient] Password= extension:ica
WFClient Password extension:ica
WFClient+Password+extension:ica
"x-api-key"
x-api-key
xoxa-2
"xoxb "
xoxb 
xoxb+
"xoxp"
xoxp
xoxr
zendesk_api_token
zendesk_key
zendesk_token
zendesk_url
zendesk_username
zen_key
zen_tkn
zen_token
```

## Shodam Dorks

```
ssl:"target.com" http.html:"Login, username, password"
ssl:"target.com" http.html:"Login, username,password" -http.html:"403 Forbidden"
http.title:"Admin"
ssl:"target.com" port:"2082"
ssl:"target.com" org:"Cloudflare, Inc."
ssl:"target.com" product:"nginx"
ssl:"target.com" org:"Cloudflare, Inc." product:"nginx" 200
kibana content-length:217 net:”cidr”
org:”Amazon” ssl:”target”
ssl:”target”
html:”Dashboard Jenkins” http.component:”jenkins”
http.title:”302 Found”
http.component%3A”java”
https://www.shodan.io/host/ip#9200
https://www.shodan.io/host/ip
X-Redirect-By: WordPress ssl:”name”
query: html:”eBay Inc. All Right Reserved”
X-Amz-Bucket-Region
x-jenkins 200
X-Generator: Drupal 7
ssl:Google
org:’Name’ port:’80’
all:”mongodb server information” all:”metrics”
port:27017 -all:”partially” all:”fs.files”
port:”9200" all:”elastic indices”
product:elastic port:9200
product: CouchDB
title:”system dashboard” html:jira
product: “apache tomcat”
ssl%3A”development”+org%3A”Amazon.com”+port%3A”number”
http.component:ruby port:3000
html:”secret_key_base”
html:”rack.version”
http.html:QUERY ssl:”domain.com”
http.favicon.hash:81586312 200
html:/dana-na/ Pulse Secure VPN exploit
"MongoDB Server Information" port:27017 -authentication
"Set-Cookie: mongo-express=" "200 OK"
mysql port:"3306"
port:"9200" all:"elastic indices"
port:5432 PostgreSQL
"220" "230 Login successful." port:21
proftpd port:21
port:"25" product:"exim"
port:"11211" product:"Memcached"
"X-Jenkins" "Set-Cookie: JSESSIONID" http.title:"Dashboard"
"port: 53" Recursion: Enabled
product:"Apache httpd" port:"80"
product:"Microsoft IIS httpd"
ssl.cert.issuer.cn:example.com ssl.cert.subject.cn:example.com
ssl.cert.expired:true
"Authentication: disabled" port:445
"220" "230 Login successful." port:21
```

## Thank You ❤

[![image](https://img.shields.io/badge/Twitter-1DA1F2?style=for-the-badge&logo=twitter&logoColor=white)](https://twitter.com/NandanLohitaksh) [![](https://img.shields.io/badge/Instagram-E4405F?style=for-the-badge&logo=instagram&logoColor=white)](https://instagram.com/lohitakshnandan) [![](https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/lohitakshnandan)

</div>
