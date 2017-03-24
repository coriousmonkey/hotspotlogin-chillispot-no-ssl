# hotspotlogin-chillispot-no-ssl
<br>
hotspotlogin for chillispot without using ssl<br>
place hotspotlogin.php & js folder in /var/www/<br><br>
edit /etc/chilli.conf<br>
with "uamserver http://192.168.182.1/hotspotlogin.php"<br>
it's default setting when you're using easyhotspot always careful with this configuration

$uamsecret = "easyhotpot";<br>
$loginpath = "/hotspotlogin.php";<br>
$hostname="localhost"; //mysql hostname<br>
$sql_user="easyhotspot"; //mysql user<br>
$sql_pass="easyhotspot"; //mysql password<br>
$sql_dbname="easyhotspot_opensource"; //database which storage user and password<br>
$user_tabel="postpaid_account"; //tabel user<br>
$user_tb_col="username"; //username column name
