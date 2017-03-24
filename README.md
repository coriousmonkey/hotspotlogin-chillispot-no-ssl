# hotspotlogin-chillispot-no-ssl
hotspotlogin for chillispot without using ssl

place hotspotlogin.php & js folder in /var/www/

edit /etc/chilli.conf
with "uamserver http://192.168.182.1/hotspotlogin.php"

it's default setting when you're using easyhotspot always careful with this configuration

$uamsecret = "easyhotpot";
$loginpath = "/hotspotlogin.php";
$hostname="localhost"; //mysql hostname
$sql_user="easyhotspot"; //mysql user
$sql_pass="easyhotspot"; //mysql password
$sql_dbname="easyhotspot_opensource"; //database which storage user and password
$user_tabel="postpaid_account"; //tabel user
$user_tb_col="username"; //username column name
