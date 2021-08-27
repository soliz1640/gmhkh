<!DOCTYPE html>
<html lang="zh-cn">
<head>
<meta http-equiv="Content-Type" content="text/html; charset=UTF-8">
<meta name="renderer" content="webkit">
<meta http-equiv="X-UA-Compatible" content="IE=edge">
<meta name="viewport" content="width=device-width, initial-scale=1, maximum-scale=1, user-scalable=no">
<title>HKH</title>
<link href="https://cdn.staticfile.org/twitter-bootstrap/3.4.1/css/bootstrap.min.css" rel="stylesheet">
<link href="https://cdn.staticfile.org/bootstrap-select/1.13.10/css/bootstrap-select.min.css" rel="stylesheet">
<link href="images/main.css" rel="stylesheet">
<script type="text/javascript" src="https://cdn.staticfile.org/jquery/2.0.0/jquery.min.js"></script>
<script type="text/javascript" src="https://cdn.staticfile.org/bootbox.js/4.4.0/bootbox.min.js"></script>
<script type="text/javascript" src="https://cdn.staticfile.org/twitter-bootstrap/3.4.1/js/bootstrap.min.js"></script>
<script type="text/javascript" src="https://cdn.staticfile.org/bootstrap-select/1.13.10/js/bootstrap-select.min.js"></script>
<script type="text/javascript" src="https://cdn.staticfile.org/bootstrap-select/1.13.10/js/i18n/defaults-zh_CN.js"></script>
</head>
<body>
  <div class="intro" style="margin-top:100px;">
  	 &nbsp;
    <div style="color:#F00" class="validator-tips"><b>Hiệp Khách Hành-SLTeam</b></div>
    <div class="container">
      <div class="row">
        <div class="col-md-3 col-sm-8 col-centered">
          <form method="post" id="register-form" autocomplete="off" action="http://82.156.19.201:30000/xkx/" class="nice-validator n-default" novalidate>
            &nbsp;
			<div class="form-group">
			<div class="form-group">
              <input type="hidden" id="qu" class="form-control" name="qu" value="1" id = 'qu'>
			  			  </input>
            </div>
			<div class="input-group">
			  <input type="text" class="form-control" id="sqm" name="sqm" placeholder="Tên Tài Khoản"  autocomplete="off">
			    <span class="input-group-btn"><button class="btn btn-primary" type="button" id='searchs' >Nhập Tài Khoản</button></span>
            </div></div>
			<div class="form-group " id = 'jscx' style="display:none;">
			<select id='uid' class="form-control"><option value='0'>Mời giành trước nhập</option></select>
			</div>
            <div class="form-group">
              <select id="gnxz" class="form-control" name="gnxz">
			  <option value="0">Chọn Công Năng</option>
			  <option value="1">Nạp Tiền</option>
			  <option value="2">Vật Phẩm</option>
			  </select>
            </div>
			<!--  -----分线--------->		
            <div class="form-group" id = 'xpay' style="display:none;">
			<div class="form-group">
			  <select id="payid" class="form-control" name="payid">
                array(26) {
  ["@id"]=>
  string(1) "1"
  ["@KeyID"]=>
  string(4) "3002"
  ["@icon"]=>
  string(18) "MallRechargeLiBao2"
  ["@price"]=>
  string(1) "1"
  ["@currency"]=>
  string(1) "1"
  ["@titleName"]=>
  string(10) "1元特购"
  ["@getMoneyNum"]=>
  string(19) "100004|60,102001|20"
  ["@firstReward"]=>
  string(0) ""
  ["@reward"]=>
  string(0) ""
  ["@subtype"]=>
  string(1) "5"
  ["@num"]=>
  string(1) "0"
  ["@people"]=>
  string(2) "10"
  ["@info"]=>
  string(21) "特权礼包送祝福"
  ["@des"]=>
  string(66) "特权达到2级可以每天购买1次（60元宝、玄铁20个）"
  ["@recommond"]=>
  string(1) "2"
  ["@limitCount"]=>
  string(1) "0"
  ["@monthLimitCount"]=>
  string(1) "0"
  ["@weekLimitCount"]=>
  string(1) "0"
  ["@dayLimitCount"]=>
  string(1) "1"
  ["@remark"]=>
  string(0) ""
  ["@isShow"]=>
  string(1) "1"
  ["@appleID1"]=>
  string(10) "fkgame38.1"
  ["@appleID2"]=>
  string(4) "mrlb"
  ["@androidID"]=>
  string(6) "xkx1lb"
  ["@coolpad"]=>
  string(2) "14"
  ["@lenovo"]=>
  string(6) "249930"
}
<option value="1">1 Nguyên đặc biệt mua</option>array(26) {
  ["@id"]=>
  string(1) "2"
  ["@KeyID"]=>
  string(4) "3003"
  ["@icon"]=>
  string(18) "MallRechargeLiBao2"
  ["@price"]=>
  string(1) "6"
  ["@currency"]=>
  string(1) "1"
  ["@titleName"]=>
  string(10) "6元礼包"
  ["@getMoneyNum"]=>
  string(19) "100004|200,100031|2"
  ["@firstReward"]=>
  string(0) ""
  ["@reward"]=>
  string(0) ""
  ["@subtype"]=>
  string(1) "5"
  ["@num"]=>
  string(1) "0"
  ["@people"]=>
  string(2) "10"
  ["@info"]=>
  string(15) "礼轻情意重"
  ["@des"]=>
  string(50) "每天购买1次（200元宝、百年仙酿2个）"
  ["@recommond"]=>
  string(1) "2"
  ["@limitCount"]=>
  string(1) "0"
  ["@monthLimitCount"]=>
  string(1) "0"
  ["@weekLimitCount"]=>
  string(1) "0"
  ["@dayLimitCount"]=>
  string(1) "1"
  ["@remark"]=>
  string(0) ""
  ["@isShow"]=>
  string(1) "1"
  ["@appleID1"]=>
  string(10) "fkgame38.6"
  ["@appleID2"]=>
  string(4) "mrlb"
  ["@androidID"]=>
  string(6) "xkx6lb"
  ["@coolpad"]=>
  string(2) "15"
  ["@lenovo"]=>
  string(6) "249931"
}
<option value="2">6 Nguyên Gói Quà</option>array(26) {
  ["@id"]=>
  string(1) "3"
  ["@KeyID"]=>
  string(4) "3004"
  ["@icon"]=>
  string(18) "MallRechargeLiBao2"
  ["@price"]=>
  string(2) "12"
  ["@currency"]=>
  string(1) "1"
  ["@titleName"]=>
  string(11) "12元礼包"
  ["@getMoneyNum"]=>
  string(19) "100004|250,103016|1"
  ["@firstReward"]=>
  string(0) ""
  ["@reward"]=>
  string(0) ""
  ["@subtype"]=>
  string(1) "5"
  ["@num"]=>
  string(1) "0"
  ["@people"]=>
  string(2) "15"
  ["@info"]=>
  string(21) "每日礼包送温暖"
  ["@des"]=>
  string(50) "每天购买1次（250元宝、彩霞霓虹1个）"
  ["@recommond"]=>
  string(1) "2"
  ["@limitCount"]=>
  string(1) "0"
  ["@monthLimitCount"]=>
  string(1) "0"
  ["@weekLimitCount"]=>
  string(1) "0"
  ["@dayLimitCount"]=>
  string(1) "1"
  ["@remark"]=>
  string(0) ""
  ["@isShow"]=>
  string(1) "1"
  ["@appleID1"]=>
  string(11) "fkgame38.12"
  ["@appleID2"]=>
  string(4) "mrlb"
  ["@androidID"]=>
  string(7) "xkx12lb"
  ["@coolpad"]=>
  string(2) "16"
  ["@lenovo"]=>
  string(6) "249932"
}
<option value="3">12 Nguyên Gói Quà</option>array(26) {
  ["@id"]=>
  string(1) "4"
  ["@KeyID"]=>
  string(4) "2001"
  ["@icon"]=>
  string(18) "MallRechargeLiBao5"
  ["@price"]=>
  string(1) "6"
  ["@currency"]=>
  string(1) "1"
  ["@titleName"]=>
  string(4) "6元"
  ["@getMoneyNum"]=>
  string(9) "100004|60"
  ["@firstReward"]=>
  string(9) "100004|60"
  ["@reward"]=>
  string(8) "100004|6"
  ["@subtype"]=>
  string(1) "5"
  ["@num"]=>
  string(1) "0"
  ["@people"]=>
  string(2) "10"
  ["@info"]=>
  string(9) "送祝福"
  ["@des"]=>
  string(20) "充值获得60元宝"
  ["@recommond"]=>
  string(1) "0"
  ["@limitCount"]=>
  string(1) "0"
  ["@monthLimitCount"]=>
  string(1) "0"
  ["@weekLimitCount"]=>
  string(1) "0"
  ["@dayLimitCount"]=>
  string(1) "0"
  ["@remark"]=>
  string(0) ""
  ["@isShow"]=>
  string(1) "1"
  ["@appleID1"]=>
  string(10) "fkgame38.6"
  ["@appleID2"]=>
  string(2) "yb"
  ["@androidID"]=>
  string(4) "xkx6"
  ["@coolpad"]=>
  string(1) "1"
  ["@lenovo"]=>
  string(6) "249934"
}
<option value="4">6 Nguyên</option>array(26) {
  ["@id"]=>
  string(1) "5"
  ["@KeyID"]=>
  string(4) "2002"
  ["@icon"]=>
  string(18) "MallRechargeLiBao6"
  ["@price"]=>
  string(2) "25"
  ["@currency"]=>
  string(1) "1"
  ["@titleName"]=>
  string(5) "25元"
  ["@getMoneyNum"]=>
  string(10) "100004|250"
  ["@firstReward"]=>
  string(10) "100004|250"
  ["@reward"]=>
  string(9) "100004|25"
  ["@subtype"]=>
  string(1) "5"
  ["@num"]=>
  string(1) "0"
  ["@people"]=>
  string(2) "20"
  ["@info"]=>
  string(9) "送温暖"
  ["@des"]=>
  string(21) "充值获得250元宝"
  ["@recommond"]=>
  string(1) "1"
  ["@limitCount"]=>
  string(1) "0"
  ["@monthLimitCount"]=>
  string(1) "0"
  ["@weekLimitCount"]=>
  string(1) "0"
  ["@dayLimitCount"]=>
  string(1) "0"
  ["@remark"]=>
  string(0) ""
  ["@isShow"]=>
  string(1) "1"
  ["@appleID1"]=>
  string(11) "fkgame38.25"
  ["@appleID2"]=>
  string(2) "yb"
  ["@androidID"]=>
  string(5) "xkx25"
  ["@coolpad"]=>
  string(1) "6"
  ["@lenovo"]=>
  string(6) "249936"
}
<option value="5">25 Nguyên</option>array(26) {
  ["@id"]=>
  string(1) "6"
  ["@KeyID"]=>
  string(4) "2003"
  ["@icon"]=>
  string(18) "MallRechargeLiBao6"
  ["@price"]=>
  string(2) "98"
  ["@currency"]=>
  string(1) "1"
  ["@titleName"]=>
  string(5) "98元"
  ["@getMoneyNum"]=>
  string(10) "100004|980"
  ["@firstReward"]=>
  string(10) "100004|980"
  ["@reward"]=>
  string(9) "100004|98"
  ["@subtype"]=>
  string(1) "5"
  ["@num"]=>
  string(1) "0"
  ["@people"]=>
  string(2) "30"
  ["@info"]=>
  string(9) "送关爱"
  ["@des"]=>
  string(21) "充值获得980元宝"
  ["@recommond"]=>
  string(1) "0"
  ["@limitCount"]=>
  string(1) "0"
  ["@monthLimitCount"]=>
  string(1) "0"
  ["@weekLimitCount"]=>
  string(1) "0"
  ["@dayLimitCount"]=>
  string(1) "0"
  ["@remark"]=>
  string(0) ""
  ["@isShow"]=>
  string(1) "1"
  ["@appleID1"]=>
  string(11) "fkgame38.98"
  ["@appleID2"]=>
  string(2) "yb"
  ["@androidID"]=>
  string(5) "xkx98"
  ["@coolpad"]=>
  string(1) "7"
  ["@lenovo"]=>
  string(6) "249937"
}
<option value="6">98 Nguyên</option>array(26) {
  ["@id"]=>
  string(1) "7"
  ["@KeyID"]=>
  string(4) "2004"
  ["@icon"]=>
  string(18) "MallRechargeLiBao1"
  ["@price"]=>
  string(3) "128"
  ["@currency"]=>
  string(1) "1"
  ["@titleName"]=>
  string(6) "128元"
  ["@getMoneyNum"]=>
  string(11) "100004|1280"
  ["@firstReward"]=>
  string(11) "100004|1280"
  ["@reward"]=>
  string(10) "100004|128"
  ["@subtype"]=>
  string(1) "5"
  ["@num"]=>
  string(7) "1000000"
  ["@people"]=>
  string(2) "30"
  ["@info"]=>
  string(18) "同享充值有礼"
  ["@des"]=>
  string(22) "充值获得1280元宝"
  ["@recommond"]=>
  string(1) "1"
  ["@limitCount"]=>
  string(1) "0"
  ["@monthLimitCount"]=>
  string(1) "0"
  ["@weekLimitCount"]=>
  string(1) "0"
  ["@dayLimitCount"]=>
  string(1) "0"
  ["@remark"]=>
  string(0) ""
  ["@isShow"]=>
  string(1) "1"
  ["@appleID1"]=>
  string(12) "fkgame38.128"
  ["@appleID2"]=>
  string(2) "yb"
  ["@androidID"]=>
  string(6) "xkx128"
  ["@coolpad"]=>
  string(1) "5"
  ["@lenovo"]=>
  string(6) "249938"
}
<option value="7">128 Nguyên</option>array(26) {
  ["@id"]=>
  string(1) "8"
  ["@KeyID"]=>
  string(4) "2005"
  ["@icon"]=>
  string(18) "MallRechargeLiBao1"
  ["@price"]=>
  string(3) "198"
  ["@currency"]=>
  string(1) "1"
  ["@titleName"]=>
  string(6) "198元"
  ["@getMoneyNum"]=>
  string(11) "100004|1980"
  ["@firstReward"]=>
  string(11) "100004|1980"
  ["@reward"]=>
  string(10) "100004|198"
  ["@subtype"]=>
  string(1) "6"
  ["@num"]=>
  string(4) "3000"
  ["@people"]=>
  string(2) "50"
  ["@info"]=>
  string(18) "恭祝财运亨通"
  ["@des"]=>
  string(22) "充值获得1980元宝"
  ["@recommond"]=>
  string(1) "0"
  ["@limitCount"]=>
  string(1) "0"
  ["@monthLimitCount"]=>
  string(1) "0"
  ["@weekLimitCount"]=>
  string(1) "0"
  ["@dayLimitCount"]=>
  string(1) "0"
  ["@remark"]=>
  string(0) ""
  ["@isShow"]=>
  string(1) "1"
  ["@appleID1"]=>
  string(12) "fkgame38.198"
  ["@appleID2"]=>
  string(2) "yb"
  ["@androidID"]=>
  string(6) "xkx198"
  ["@coolpad"]=>
  string(1) "8"
  ["@lenovo"]=>
  string(6) "252176"
}
<option value="8">198 Nguyên</option>array(26) {
  ["@id"]=>
  string(1) "9"
  ["@KeyID"]=>
  string(4) "2006"
  ["@icon"]=>
  string(18) "MallRechargeLiBao3"
  ["@price"]=>
  string(3) "328"
  ["@currency"]=>
  string(1) "1"
  ["@titleName"]=>
  string(6) "328元"
  ["@getMoneyNum"]=>
  string(11) "100004|3280"
  ["@firstReward"]=>
  string(11) "100004|3280"
  ["@reward"]=>
  string(10) "100004|328"
  ["@subtype"]=>
  string(1) "6"
  ["@num"]=>
  string(4) "6000"
  ["@people"]=>
  string(2) "60"
  ["@info"]=>
  string(18) "红包欢乐同享"
  ["@des"]=>
  string(22) "充值获得3280元宝"
  ["@recommond"]=>
  string(1) "0"
  ["@limitCount"]=>
  string(1) "0"
  ["@monthLimitCount"]=>
  string(1) "0"
  ["@weekLimitCount"]=>
  string(1) "0"
  ["@dayLimitCount"]=>
  string(1) "0"
  ["@remark"]=>
  string(0) ""
  ["@isShow"]=>
  string(1) "1"
  ["@appleID1"]=>
  string(12) "fkgame38.328"
  ["@appleID2"]=>
  string(2) "yb"
  ["@androidID"]=>
  string(6) "xkx328"
  ["@coolpad"]=>
  string(1) "9"
  ["@lenovo"]=>
  string(6) "249939"
}
<option value="9">328 Nguyên</option>array(26) {
  ["@id"]=>
  string(2) "10"
  ["@KeyID"]=>
  string(4) "2007"
  ["@icon"]=>
  string(18) "MallRechargeLiBao4"
  ["@price"]=>
  string(3) "648"
  ["@currency"]=>
  string(1) "1"
  ["@titleName"]=>
  string(6) "648元"
  ["@getMoneyNum"]=>
  string(11) "100004|6480"
  ["@firstReward"]=>
  string(11) "100004|6480"
  ["@reward"]=>
  string(10) "100004|648"
  ["@subtype"]=>
  string(1) "6"
  ["@num"]=>
  string(5) "15000"
  ["@people"]=>
  string(3) "100"
  ["@info"]=>
  string(24) "普天同庆红包放送"
  ["@des"]=>
  string(22) "充值获得6480元宝"
  ["@recommond"]=>
  string(1) "1"
  ["@limitCount"]=>
  string(1) "0"
  ["@monthLimitCount"]=>
  string(1) "0"
  ["@weekLimitCount"]=>
  string(1) "0"
  ["@dayLimitCount"]=>
  string(1) "0"
  ["@remark"]=>
  string(0) ""
  ["@isShow"]=>
  string(1) "1"
  ["@appleID1"]=>
  string(12) "fkgame38.648"
  ["@appleID2"]=>
  string(2) "yb"
  ["@androidID"]=>
  string(6) "xkx648"
  ["@coolpad"]=>
  string(2) "10"
  ["@lenovo"]=>
  string(6) "249940"
}
<option value="10">648 Nguyên</option>array(26) {
  ["@id"]=>
  string(2) "11"
  ["@KeyID"]=>
  string(4) "1003"
  ["@icon"]=>
  string(18) "MallRechargeZhouKa"
  ["@price"]=>
  string(2) "12"
  ["@currency"]=>
  string(1) "1"
  ["@titleName"]=>
  string(5) "12元"
  ["@getMoneyNum"]=>
  string(10) "100004|120"
  ["@firstReward"]=>
  string(0) ""
  ["@reward"]=>
  string(0) ""
  ["@subtype"]=>
  string(1) "5"
  ["@num"]=>
  string(1) "0"
  ["@people"]=>
  string(2) "10"
  ["@info"]=>
  string(15) "周卡送祝福"
  ["@des"]=>
  string(57) "即送120元宝。每日领取1000绑定银、50万铜钱"
  ["@recommond"]=>
  string(1) "1"
  ["@limitCount"]=>
  string(1) "0"
  ["@monthLimitCount"]=>
  string(1) "0"
  ["@weekLimitCount"]=>
  string(1) "0"
  ["@dayLimitCount"]=>
  string(1) "0"
  ["@remark"]=>
  string(0) ""
  ["@isShow"]=>
  string(1) "1"
  ["@appleID1"]=>
  string(11) "fkgame38.12"
  ["@appleID2"]=>
  string(2) "zk"
  ["@androidID"]=>
  string(6) "xkx12a"
  ["@coolpad"]=>
  string(2) "17"
  ["@lenovo"]=>
  string(6) "249929"
}
<option value="11">12 Nguyên</option>array(26) {
  ["@id"]=>
  string(2) "12"
  ["@KeyID"]=>
  string(4) "1001"
  ["@icon"]=>
  string(21) "MallRechargeShouYueKa"
  ["@price"]=>
  string(2) "30"
  ["@currency"]=>
  string(1) "1"
  ["@titleName"]=>
  string(5) "30元"
  ["@getMoneyNum"]=>
  string(10) "100004|300"
  ["@firstReward"]=>
  string(0) ""
  ["@reward"]=>
  string(0) ""
  ["@subtype"]=>
  string(1) "5"
  ["@num"]=>
  string(1) "0"
  ["@people"]=>
  string(2) "15"
  ["@info"]=>
  string(15) "月卡送温暖"
  ["@des"]=>
  string(68) "即送300元宝。每日领取10000绑定银两并解锁月卡商店"
  ["@recommond"]=>
  string(1) "1"
  ["@limitCount"]=>
  string(1) "0"
  ["@monthLimitCount"]=>
  string(1) "0"
  ["@weekLimitCount"]=>
  string(1) "0"
  ["@dayLimitCount"]=>
  string(1) "0"
  ["@remark"]=>
  string(0) ""
  ["@isShow"]=>
  string(1) "1"
  ["@appleID1"]=>
  string(11) "fkgame38.30"
  ["@appleID2"]=>
  string(2) "yk"
  ["@androidID"]=>
  string(6) "xkx30a"
  ["@coolpad"]=>
  string(1) "4"
  ["@lenovo"]=>
  string(6) "249933"
}
<option value="12">30 Nguyên</option>array(26) {
  ["@id"]=>
  string(2) "13"
  ["@KeyID"]=>
  string(4) "1002"
  ["@icon"]=>
  string(23) "MallRechargeZhongShenka"
  ["@price"]=>
  string(3) "128"
  ["@currency"]=>
  string(1) "1"
  ["@titleName"]=>
  string(6) "128元"
  ["@getMoneyNum"]=>
  string(11) "100004|1280"
  ["@firstReward"]=>
  string(0) ""
  ["@reward"]=>
  string(0) ""
  ["@subtype"]=>
  string(1) "5"
  ["@num"]=>
  string(6) "300000"
  ["@people"]=>
  string(2) "25"
  ["@info"]=>
  string(15) "礼包送关爱"
  ["@des"]=>
  string(48) "即送1280元宝。每日领取10000绑定银两"
  ["@recommond"]=>
  string(1) "1"
  ["@limitCount"]=>
  string(1) "1"
  ["@monthLimitCount"]=>
  string(1) "0"
  ["@weekLimitCount"]=>
  string(1) "0"
  ["@dayLimitCount"]=>
  string(1) "0"
  ["@remark"]=>
  string(0) ""
  ["@isShow"]=>
  string(1) "0"
  ["@appleID1"]=>
  string(12) "fkgame38.128"
  ["@appleID2"]=>
  string(3) "zzk"
  ["@androidID"]=>
  string(7) "xkx128a"
  ["@coolpad"]=>
  string(2) "13"
  ["@lenovo"]=>
  string(6) "249935"
}
<option value="13">128 Nguyên</option>array(26) {
  ["@id"]=>
  string(2) "14"
  ["@KeyID"]=>
  string(4) "3001"
  ["@icon"]=>
  string(23) "MallRechargeZhongShenka"
  ["@price"]=>
  string(2) "25"
  ["@currency"]=>
  string(1) "1"
  ["@titleName"]=>
  string(15) "神秘大礼包"
  ["@getMoneyNum"]=>
  string(17) "104015|1,104016|1"
  ["@firstReward"]=>
  string(0) ""
  ["@reward"]=>
  string(10) "100004|250"
  ["@subtype"]=>
  string(1) "5"
  ["@num"]=>
  string(1) "0"
  ["@people"]=>
  string(2) "10"
  ["@info"]=>
  string(21) "月度礼包超值送"
  ["@des"]=>
  string(58) "购买即得250元宝和珍惜道具，每月限购1个！"
  ["@recommond"]=>
  string(1) "1"
  ["@limitCount"]=>
  string(1) "0"
  ["@monthLimitCount"]=>
  string(1) "1"
  ["@weekLimitCount"]=>
  string(1) "0"
  ["@dayLimitCount"]=>
  string(1) "0"
  ["@remark"]=>
  string(0) ""
  ["@isShow"]=>
  string(1) "0"
  ["@appleID1"]=>
  string(6) "xkx12b"
  ["@appleID2"]=>
  string(6) "xkx12b"
  ["@androidID"]=>
  string(6) "xkx12b"
  ["@coolpad"]=>
  string(1) "3"
  ["@lenovo"]=>
  string(6) "249941"
}
<option value="14">Thần Bí Gói Quà</option>array(26) {
  ["@id"]=>
  string(2) "15"
  ["@KeyID"]=>
  string(4) "5001"
  ["@icon"]=>
  string(18) "MallRechargeLiBao2"
  ["@price"]=>
  string(2) "25"
  ["@currency"]=>
  string(1) "1"
  ["@titleName"]=>
  string(5) "25元"
  ["@getMoneyNum"]=>
  string(0) ""
  ["@firstReward"]=>
  string(0) ""
  ["@reward"]=>
  string(0) ""
  ["@subtype"]=>
  string(1) "5"
  ["@num"]=>
  string(1) "0"
  ["@people"]=>
  string(2) "15"
  ["@info"]=>
  string(21) "七日聚宝财气旺"
  ["@des"]=>
  string(60) "开启聚宝盆，连续登录七天，海量豪礼等你拿"
  ["@recommond"]=>
  string(1) "1"
  ["@limitCount"]=>
  string(1) "1"
  ["@monthLimitCount"]=>
  string(1) "0"
  ["@weekLimitCount"]=>
  string(1) "0"
  ["@dayLimitCount"]=>
  string(1) "0"
  ["@remark"]=>
  string(0) ""
  ["@isShow"]=>
  string(1) "0"
  ["@appleID1"]=>
  string(11) "fkgame38.25"
  ["@appleID2"]=>
  string(3) "jbp"
  ["@androidID"]=>
  string(7) "xkx68aa"
  ["@coolpad"]=>
  string(2) "11"
  ["@lenovo"]=>
  string(6) "249942"
}
<option value="15">25 Nguyên</option>array(26) {
  ["@id"]=>
  string(2) "16"
  ["@KeyID"]=>
  string(4) "4001"
  ["@icon"]=>
  string(18) "MallRechargeLiBao2"
  ["@price"]=>
  string(2) "60"
  ["@currency"]=>
  string(1) "1"
  ["@titleName"]=>
  string(5) "60元"
  ["@getMoneyNum"]=>
  string(0) ""
  ["@firstReward"]=>
  string(0) ""
  ["@reward"]=>
  string(0) ""
  ["@subtype"]=>
  string(1) "6"
  ["@num"]=>
  string(1) "0"
  ["@people"]=>
  string(2) "30"
  ["@info"]=>
  string(21) "等级基金有好礼"
  ["@des"]=>
  string(51) "立即激活等级基金，超值元宝伴你成长"
  ["@recommond"]=>
  string(1) "1"
  ["@limitCount"]=>
  string(1) "1"
  ["@monthLimitCount"]=>
  string(1) "0"
  ["@weekLimitCount"]=>
  string(1) "0"
  ["@dayLimitCount"]=>
  string(1) "0"
  ["@remark"]=>
  string(0) ""
  ["@isShow"]=>
  string(1) "0"
  ["@appleID1"]=>
  string(11) "fkgame38.60"
  ["@appleID2"]=>
  string(4) "czjj"
  ["@androidID"]=>
  string(6) "xkx88a"
  ["@coolpad"]=>
  string(2) "12"
  ["@lenovo"]=>
  string(6) "249943"
}
<option value="16">60 Nguyên</option>            </select>
            </div>
			 <div class="form-center-button">
			 <input class="btn btn-danger" name='charge' id="charge" value="Gửi [Tải lại 5 giây]" type="button" onclick= "setTimeout((function(me){me.disabled=true;return function(){me.disabled=false;};})(this),5000);chargebtn()">
			</div><br>
			</div>
		<!--  -----分线--------->		
            <div class="form-group" id = 'wupin' style="display:none;">
			<div class="form-group"><div class="input-group">
            <input type='text' class="form-control" value='' id='searchipt' placeholder='Tìm Vật Phẩm'>
			<span class="input-group-btn"><button class="btn btn-info" type="button" id='search' >Tìm Kiếm</button></span>	
			</div></div>
			<div class="form-group">
			<select id='mailid' class="form-control">
            <option value="0">chọn vật phẩm
</option><option value="100001"> kinh nghiệm
</option><option value="100002"> đồng tiền
</option><option value="100003"> ngân lưỡng
</option><option value="100004"> nguyên bảo
</option><option value="100005"> bảng định ngân lưỡng
</option><option value="100006"> bang cống
</option><option value="100007"> chiến công
</option><option value="100008"> hiệp nghĩa trị
</option><option value="100009"> môn phái cống hiến
</option><option value="100010"> tiễu phỉ ấn
</option><option value="100011"> lịch luyện
</option><option value="100012"> tinh lực
</option><option value="100013"> lưu phái điểm
</option><option value="100014"> đẳng cấp kinh nghiệm
</option><option value="100015"> đẳng cấp lịch luyện
</option><option value="100016"> vũ đạo
</option><option value="100017"> bang hội tư kim
</option><option value="100018"> bang hội vân mộc
</option><option value="100019"> tâm ma tích phân
</option><option value="100020"> song bội kinh nghiệm
</option><option value="100021"> phồn vinh độ
</option><option value="100025"> đại trung thiên
</option><option value="100030"> thập niên giai nhưỡng
</option><option value="100031"> bách niên tiên nhưỡng
</option><option value="100032"> chuyển sinh đan
</option><option value="100033"> phàm cấp vạn năng toái phiến
</option><option value="100034"> linh cấp vạn năng toái phiến
</option><option value="100035"> thiên cấp vạn năng toái phiến
</option><option value="100036"> đế cấp vạn năng toái phiến
</option><option value="100037"> thần binh điểm ( thống kế dụng )
</option><option value="100040"> đặc quyền kinh nghiệm ( tiểu )
</option><option value="100041"> đặc quyền kinh nghiệm ( đại )
</option><option value="100042"> đặc quyền đẳng cấp 1
</option><option value="100043"> đặc quyền đẳng cấp 2
</option><option value="100044"> đặc quyền đẳng cấp 3
</option><option value="100045"> đặc quyền đẳng cấp 4
</option><option value="100046"> đặc quyền đẳng cấp 5
</option><option value="100047"> đặc quyền đẳng cấp 6
</option><option value="100048"> đặc quyền đẳng cấp 7
</option><option value="100049"> đặc quyền đẳng cấp 8
</option><option value="100050"> đặc quyền đẳng cấp 9
</option><option value="100051"> đặc quyền đẳng cấp 10
</option><option value="100052"> đặc quyền đẳng cấp 11
</option><option value="100053"> đặc quyền đẳng cấp 12
</option><option value="100054"> đặc quyền đẳng cấp 13
</option><option value="100055"> đặc quyền đẳng cấp 14
</option><option value="100056"> đặc quyền đẳng cấp 15
</option><option value="100101"> tiểu y tiên toái phiến
</option><option value="100102"> khâu sơn phong toái phiến
</option><option value="100103"> bạch a tú toái phiến
</option><option value="100104"> đinh đang toái phiến
</option><option value="100105"> triển phi toái phiến
</option><option value="100106"> sử tiểu thúy toái phiến
</option><option value="100107"> đinh bất tứ toái phiến
</option><option value="100108"> mai văn hinh toái phiến
</option><option value="100109"> thạch thanh toái phiến
</option><option value="100110"> ngân nguyệt toái phiến
</option><option value="100111"> Bạch Tự Tại mảnh vỡ
</option><option value="100112"> Trương Tam mảnh vỡ
</option><option value="100113"> Tạ khói khách mảnh vỡ
</option><option value="100114"> Thạch Phá Thiên mảnh vỡ
</option><option value="100115"> Đại bi lão nhân mảnh vỡ
</option><option value="100116"> Long đảo chủ mảnh vỡ
</option><option value="100117"> Mộc đảo chủ mảnh vỡ
</option><option value="100118"> Tiểu Y Tiên mảnh vỡ
</option><option value="100119"> Khâu gió núi mảnh vỡ
</option><option value="100120"> Bạch a thêu mảnh vỡ
</option><option value="100121"> Đinh đang mảnh vỡ
</option><option value="100122"> Triển bay nát phiến
</option><option value="100123"> Sử Tiểu Thúy mảnh vỡ
</option><option value="100124"> Đinh không bốn mảnh vỡ
</option><option value="100125"> Meven hinh mảnh vỡ
</option><option value="100126"> Thạch Thanh mảnh vỡ
</option><option value="100127"> Ngân Nguyệt mảnh vỡ
</option><option value="100128"> Bạch Tự Tại mảnh vỡ
</option><option value="100129"> Trương Tam mảnh vỡ
</option><option value="100130"> Tạ khói khách mảnh vỡ
</option><option value="100131"> Thạch Phá Thiên mảnh vỡ
</option><option value="100132"> Đại bi lão nhân mảnh vỡ
</option><option value="100133"> Bạch a thêu mảnh vỡ
</option><option value="100134"> Đinh đang mảnh vỡ
</option><option value="100135"> Triển bay nát phiến
</option><option value="100136"> Sử Tiểu Thúy mảnh vỡ
</option><option value="100137"> Đinh không bốn mảnh vỡ
</option><option value="100138"> Đinh không ba mảnh vỡ
</option><option value="100139"> Tạ khói khách mảnh vỡ
</option><option value="100140"> Bối Hải Thạch mảnh vỡ
</option><option value="100141"> Trương Tam mảnh vỡ
</option><option value="100142"> Lý Tứ mảnh vỡ
</option><option value="100143"> Thạch Thanh mảnh vỡ
</option><option value="100144"> Bạch Tự Tại mảnh vỡ
</option><option value="100145"> Thạch Phá Thiên mảnh vỡ
</option><option value="100146"> Thạch Trung Ngọc mảnh vỡ
</option><option value="100147"> Đại bi lão nhân mảnh vỡ
</option><option value="100148"> Long đảo chủ mảnh vỡ
</option><option value="100149"> Mộc đảo chủ mảnh vỡ
</option><option value="100150"> Đế cấp luyện công hiệp khách mảnh vỡ
</option><option value="100151"> Tiểu Y Tiên mảnh vỡ
</option><option value="100152"> Khâu gió núi mảnh vỡ
</option><option value="100153"> An phụng nhật mảnh vỡ
</option><option value="100154"> Hách sắt mảnh vỡ
</option><option value="100155"> Mị nhi mảnh vỡ
</option><option value="100156"> Meven hinh mảnh vỡ
</option><option value="100157"> Thích khách đinh đang mảnh vỡ
</option><option value="100158"> Bạch Vạn Kiếm mảnh vỡ
</option><option value="100159"> Thiên cấp luyện công hiệp khách mảnh vỡ
</option><option value="100160"> Càng đắc thắng mảnh vỡ
</option><option value="100161"> Cảnh vạn chuông mảnh vỡ
</option><option value="100162"> Sát sinh tăng mảnh vỡ
</option><option value="100163"> Nguyễn luyện váy mảnh vỡ
</option><option value="100164"> Hồng Tụ khuynh thành mảnh vỡ
</option><option value="100165"> Linh cấp luyện công hiệp khách mảnh vỡ
</option><option value="100166"> Lăng Tiêu đệ tử mảnh vỡ
</option><option value="100167"> Nga Mi đệ tử mảnh vỡ
</option><option value="100168"> Định thiền đệ tử mảnh vỡ
</option><option value="100169"> Ngũ độc đệ tử mảnh vỡ
</option><option value="100170"> Phàm cấp luyện công hiệp khách mảnh vỡ
</option><option value="101034">30 Cấp lên thẳng
</option><option value="101035">40 Cấp lên thẳng
</option><option value="101036">50 Cấp lên thẳng
</option><option value="101037">60 Cấp lên thẳng
</option><option value="101038">100 Cấp lên thẳng
</option><option value="102001"> Huyền thiết
</option><option value="102002"> Ngọc Linh Lung
</option><option value="102003"> Ngọc như ý
</option><option value="102101"> Tinh thiết búa rèn
</option><option value="102102"> Huyền thiết búa rèn
</option><option value="102103"> Vẫn thạch búa rèn
</option><option value="102201"> Sắt chiên
</option><option value="102202"> Lạnh sắt thép chiên
</option><option value="102203"> Sao băng sắt chiên
</option><option value="102301"> Khuôn đúc
</option><option value="102302"> Huyền thiết khuôn đúc
</option><option value="102303"> Vẫn thạch khuôn đúc
</option><option value="102401"> Khôi thạch
</option><option value="102402"> Thưởng thiện thạch
</option><option value="102403"> Dũng thạch
</option><option value="102404"> Kiệt thạch
</option><option value="102405"> Thiên Khôi thạch
</option><option value="102406"> Thiên Sát thạch
</option><option value="102407"> Trời dũng thạch
</option><option value="102408"> Thiên kiệt thạch
</option><option value="102501"> Địa hỏa tinh · Đồ phòng ngự
</option><option value="102502"> Địa hỏa tinh · Vũ khí
</option><option value="102503"> Địa hỏa tinh · Trang sức
</option><option value="102504"> Cao cấp địa hỏa tinh · Đồ phòng ngự
</option><option value="102505"> Cao cấp địa hỏa tinh · Vũ khí
</option><option value="102506"> Cao cấp địa hỏa tinh · Trang sức
</option><option value="103001"> Đại Hoàn đan
</option><option value="103002"> Bút lông sói
</option><option value="103003"> Đỏ chót mứt táo
</option><option value="103004"> Thải Điệp bay múa
</option><option value="103005"> Bạch đầu giai lão
</option><option value="103006"> Đổi tên giản
</option><option value="103007"> Kỳ Lân giáp
</option><option value="103008"> Hoa cương
</option><option value="103009"> Trầm hương hoa
</option><option value="103010"> Trống lúc lắc
</option><option value="103011"> Tiêu dao sênh
</option><option value="103012"> Khí vận trúc tía ký
</option><option value="103013"> Trong túi trời
</option><option value="103014"> Định huyệt bàn
</option><option value="103015"> Thanh Long thạch
</option><option value="103016"> Thải hà nghê hồng
</option><option value="103017"> Tình nghĩa Hạnh Hoa rượu
</option><option value="103018"> Thanh tỉnh lộ
</option><option value="103020"> Thiện ác khiến · Kim
</option><option value="103021"> Cao cấp giáo sư xưng hào
</option><option value="103022"> Đặc cấp giáo sư xưng hào
</option><option value="103023"> Cuồng chiến dị hổ
</option><option value="103024"> Thiên tuyển danh sư xưng hào
</option><option value="103025"> Thiện ác khiến · Ngân
</option><option value="103026"> Kẹo mừng
</option><option value="103027"> Cao cấp kẹo mừng
</option><option value="104001">10000 Đồng tiền
</option><option value="104002">10 Vạn đồng tiền
</option><option value="104003">100 Vạn đồng tiền
</option><option value="104004">1000 Vạn đồng tiền
</option><option value="104005"> Sơ cấp tiềm năng quả
</option><option value="104006"> Trung cấp tiềm năng quả
</option><option value="104007"> Cao cấp tiềm năng quả
</option><option value="104008"> Học đồ Lỗ Ban tập
</option><option value="104009"> Đại sư Lỗ Ban tập
</option><option value="104010"> Lỗ Ban tập
</option><option value="104011"> Kim lan hoa
</option><option value="104012"> Hoa hồng đỏ
</option><option value="104013"> Yêu cơ xanh lam
</option><option value="104014"> Tinh lực cỏ
</option><option value="104015"> Tàng bảo đồ
</option><option value="104016"> Chu quả
</option><option value="104017"> Trăm năm chu quả
</option><option value="104018"> Chỉ Huyết Tán
</option><option value="104019"> Kim sang dược
</option><option value="104020"> Cá mập gan tán
</option><option value="104021"> Cửu chuyển gấu rắn hoàn
</option><option value="104022"> Cửu Hoa Ngọc Lộ hoàn
</option><option value="104023"> Sinh Sinh Tạo Hóa đan
</option><option value="104024"> Ngọc Linh tán
</option><option value="104025"> Kéo dài tính mạng tám hoàn
</option><option value="104026"> Thiên hương thỉnh thoảng nhựa cây
</option><option value="104027"> Cửu chuyển hồi xuân canh
</option><option value="104028"> Sen dung bao
</option><option value="104029"> Thập cẩm cháo
</option><option value="104030"> Bát Bảo vịt hoang
</option><option value="104031"> Cua nước
</option><option value="104032"> Cá trích đậu hũ
</option><option value="104033"> Phù dung nướng tôm
</option><option value="104034"> Tam tiên long phượng quái
</option><option value="104035"> Kim Thiềm ngọc bảo
</option><option value="104036"> Minh châu đậu hũ
</option><option value="104037"> Sơ cấp vũ khí Minh Văn
</option><option value="104038"> Sơ cấp quần áo Minh Văn
</option><option value="104039"> Sơ cấp hộ thối Minh Văn
</option><option value="104040"> Sơ cấp mũ giáp Minh Văn
</option><option value="104041"> Sơ cấp giày Minh Văn
</option><option value="104042"> Sơ cấp chiếc nhẫn Minh Văn
</option><option value="104043"> Sơ cấp eo rơi Minh Văn
</option><option value="104044"> Sơ cấp dây chuyền Minh Văn
</option><option value="104045"> Trung cấp vũ khí Minh Văn
</option><option value="104046"> Trung cấp quần áo Minh Văn
</option><option value="104047"> Trung cấp hộ thối Minh Văn
</option><option value="104048"> Trung cấp mũ giáp Minh Văn
</option><option value="104049"> Trung cấp giày Minh Văn
</option><option value="104050"> Trung cấp chiếc nhẫn Minh Văn
</option><option value="104051"> Trung cấp eo rơi Minh Văn
</option><option value="104052"> Trung cấp dây chuyền Minh Văn
</option><option value="104053"> Cao cấp vũ khí Minh Văn
</option><option value="104054"> Cao cấp quần áo Minh Văn
</option><option value="104055"> Cao cấp hộ thối Minh Văn
</option><option value="104056"> Cao cấp mũ giáp Minh Văn
</option><option value="104057"> Cao cấp giày Minh Văn
</option><option value="104058"> Cao cấp chiếc nhẫn Minh Văn
</option><option value="104059"> Cao cấp eo rơi Minh Văn
</option><option value="104060"> Cao cấp dây chuyền Minh Văn
</option><option value="104061"> Đỉnh cấp vũ khí Minh Văn
</option><option value="104062"> Đỉnh cấp quần áo Minh Văn
</option><option value="104063"> Đỉnh cấp hộ thối Minh Văn
</option><option value="104064"> Đỉnh cấp mũ giáp Minh Văn
</option><option value="104065"> Đỉnh cấp giày Minh Văn
</option><option value="104066"> Đỉnh cấp chiếc nhẫn Minh Văn
</option><option value="104067"> Đỉnh cấp eo rơi Minh Văn
</option><option value="104068"> Đỉnh cấp dây chuyền Minh Văn
</option><option value="104069"> Hồng bao
</option><option value="104070"> Sơ cấp Minh Văn
</option><option value="104071"> Trung cấp Minh Văn
</option><option value="104072"> Cao cấp Minh Văn
</option><option value="104073"> Đỉnh cấp Minh Văn
</option><option value="104074"> Sơ cấp tu luyện đan
</option><option value="104075"> Trung cấp tu luyện đan
</option><option value="104076"> Cao cấp tu luyện đan
</option><option value="104077"> Hồng Mông Tử Khí
</option><option value="104078"> Loa
</option><option value="104079"> Hư Linh đan
</option><option value="104080"> Mộ anh hùng
</option><option value="104081"> Lệnh bài · Khoa cử thi đấu
</option><option value="104082"> Lệnh bài · Phúc địa động thiên
</option><option value="104083"> Lệnh bài · Kỳ trân dị bảo
</option><option value="104084"> Lệnh bài · Trận doanh hoạt động
</option><option value="104085"> Lệnh bài · Võ lâm thương
</option><option value="104086"> Lệnh bài · Vượt nóc băng tường
</option><option value="104087"> Lệnh bài · Bang chiến
</option><option value="104088"> Lệnh bài · Bang hội Đãng Khấu
</option><option value="104089"> Lệnh bài · Trăm khí thần quyết
</option><option value="104090"> Thiêu đốt · Trừng phạt hung trừ ác
</option><option value="104091"> Thiêu đốt · Thần binh đảo
</option><option value="104092"> Mèo cầu tài
</option><option value="104093">1000 Ngân lượng
</option><option value="105001"> Trương Tam nguyên hồn
</option><option value="105002"> Thạch Phá Thiên nguyên hồn
</option><option value="105003"> Tạ khói khách nguyên hồn
</option><option value="105004"> Long đảo chủ nguyên hồn
</option><option value="105005"> Mộc đảo chủ nguyên hồn
</option><option value="105006"> Phượng Hoàng vũ
</option><option value="105007"> Thanh Long vảy
</option><option value="105008"> Huyền Vũ hồn
</option><option value="105009"> Băng cơ quả
</option><option value="105010"> Tụ tập tâm
</option><option value="105011"> Tâm sen khổ
</option><option value="105012"> Tuyến nhân quả
</option><option value="105013"> Đáy động chỉ riêng
</option><option value="105014"> Nguyên tạo ra hóa châu
</option><option value="105015"> Sơ cấp sách kỹ năng mảnh vỡ
</option><option value="105016"> Cao cấp sách kỹ năng mảnh vỡ
</option><option value="105017">40 Cấp vũ khí chế tạo khuôn đúc
</option><option value="105018">50 Cấp vũ khí chế tạo khuôn đúc
</option><option value="105019">60 Cấp vũ khí chế tạo khuôn đúc
</option><option value="105020">70 Cấp vũ khí chế tạo khuôn đúc
</option><option value="105021">80 Cấp vũ khí chế tạo khuôn đúc
</option><option value="105022">90 Cấp vũ khí chế tạo khuôn đúc
</option><option value="105023">100 Cấp vũ khí chế tạo khuôn đúc
</option><option value="105024">40 Cấp đồ phòng ngự chế tạo khuôn đúc
</option><option value="105025">50 Cấp đồ phòng ngự chế tạo khuôn đúc
</option><option value="105026">60 Cấp đồ phòng ngự chế tạo khuôn đúc
</option><option value="105027">70 Cấp đồ phòng ngự chế tạo khuôn đúc
</option><option value="105028">80 Cấp đồ phòng ngự chế tạo khuôn đúc
</option><option value="105029">90 Cấp đồ phòng ngự chế tạo khuôn đúc
</option><option value="105030">100 Cấp đồ phòng ngự chế tạo khuôn đúc
</option><option value="105031">40 Cấp trang sức chế tạo khuôn đúc
</option><option value="105032">50 Cấp trang sức chế tạo khuôn đúc
</option><option value="105033">60 Cấp trang sức chế tạo khuôn đúc
</option><option value="105034">70 Cấp trang sức chế tạo khuôn đúc
</option><option value="105035">80 Cấp trang sức chế tạo khuôn đúc
</option><option value="105036">90 Cấp trang sức chế tạo khuôn đúc
</option><option value="105037">100 Cấp trang sức chế tạo khuôn đúc
</option><option value="105038"> Mực thép
</option><option value="105039"> Hàn thiết
</option><option value="105040"> Vẫn thạch
</option><option value="105041"> Tinh thiết
</option><option value="105042">60 Cấp vũ khí chế tạo bản vẽ
</option><option value="105043">70 Cấp vũ khí chế tạo bản vẽ
</option><option value="105044">80 Cấp vũ khí chế tạo bản vẽ
</option><option value="105045">90 Cấp vũ khí chế tạo bản vẽ
</option><option value="105046">100 Cấp vũ khí chế tạo bản vẽ
</option><option value="105047">60 Cấp quần áo chế tạo bản vẽ
</option><option value="105048">70 Cấp quần áo chế tạo bản vẽ
</option><option value="105049">80 Cấp quần áo chế tạo bản vẽ
</option><option value="105050">90 Cấp quần áo chế tạo bản vẽ
</option><option value="105051">100 Cấp quần áo chế tạo bản vẽ
</option><option value="105052">60 Cấp hộ thối chế tạo bản vẽ
</option><option value="105053">70 Cấp hộ thối chế tạo bản vẽ
</option><option value="105054">80 Cấp hộ thối chế tạo bản vẽ
</option><option value="105055">90 Cấp hộ thối chế tạo bản vẽ
</option><option value="105056">100 Cấp hộ thối chế tạo bản vẽ
</option><option value="105057"> Càn Khôn Đỉnh
</option><option value="105058"> Sơ cấp hiệp khách bí tịch
</option><option value="105059"> Cao cấp hiệp khách bí tịch
</option><option value="105060">40 Cấp vũ khí bảo hạp
</option><option value="105061">40 Cấp áo bảo hạp
</option><option value="105062">40 Cấp hộ thối bảo hạp
</option><option value="105063">40 Cấp giày bảo hạp
</option><option value="105064">40 Cấp khăn trùm đầu bảo hạp
</option><option value="105065">40 Cấp chiếc nhẫn bảo hạp
</option><option value="105066">40 Cấp eo rơi bảo hạp
</option><option value="105067">40 Cấp dây chuyền bảo hạp
</option><option value="105068">50 Cấp vũ khí bảo hạp
</option><option value="105069">50 Cấp áo bảo hạp
</option><option value="105070">50 Cấp hộ thối bảo hạp
</option><option value="105071">50 Cấp giày bảo hạp
</option><option value="105072">50 Cấp khăn trùm đầu bảo hạp
</option><option value="105073">50 Cấp chiếc nhẫn bảo hạp
</option><option value="105074">50 Cấp eo rơi bảo hạp
</option><option value="105075">50 Cấp dây chuyền bảo hạp
</option><option value="105076">60 Cấp vũ khí hộp
</option><option value="105077">60 Cấp áo rương
</option><option value="105078">60 Cấp hộ thối rương
</option><option value="105079">60 Cấp giày rương
</option><option value="105080">60 Cấp khăn trùm đầu rương
</option><option value="105081">60 Cấp chiếc nhẫn rương
</option><option value="105082">60 Cấp eo rơi rương
</option><option value="105083">60 Cấp dây chuyền rương
</option><option value="105084"> Sinh tử thanh đồng chu lễ bao
</option><option value="105085"> Sinh tử bạch ngân chu lễ bao
</option><option value="105086"> Sinh tử tuần lễ vàng gói quà
</option><option value="105087"> Sinh tử kim cương chu lễ bao
</option><option value="105088"> Sinh tử tông sư chu lễ bao
</option><option value="105089"> Sinh tử truyền kỳ chu lễ bao
</option><option value="105090"> Sinh tử thanh đồng nguyệt gói quà
</option><option value="105091"> Sinh tử bạch Ngân Nguyệt gói quà
</option><option value="105092"> Sinh tử hoàng Kim Nguyệt gói quà
</option><option value="105093"> Sinh tử kim cương nguyệt gói quà
</option><option value="105094"> Sinh tử tông sư nguyệt gói quà
</option><option value="105095"> Sinh tử truyền kỳ nguyệt gói quà
</option><option value="105096"> Hoa Sơn thanh đồng chu lễ bao
</option><option value="105097"> Hoa Sơn bạch ngân chu lễ bao
</option><option value="105098"> Hoa Sơn tuần lễ vàng gói quà
</option><option value="105099"> Hoa Sơn kim cương chu lễ bao
</option><option value="105100"> Hoa Sơn tông sư chu lễ bao
</option><option value="105101"> Hoa Sơn truyền kỳ chu lễ bao
</option><option value="105102"> Hoa Sơn thanh đồng nguyệt gói quà
</option><option value="105103"> Hoa Sơn bạch Ngân Nguyệt gói quà
</option><option value="105104"> Hoa Sơn hoàng Kim Nguyệt gói quà
</option><option value="105105"> Hoa Sơn kim cương nguyệt gói quà
</option><option value="105106"> Hoa Sơn tông sư nguyệt gói quà
</option><option value="105107"> Hoa Sơn truyền kỳ nguyệt gói quà
</option><option value="105108">60 Cấp mũ giáp chế tạo bản vẽ
</option><option value="105109">70 Cấp mũ giáp chế tạo bản vẽ
</option><option value="105110">80 Cấp mũ giáp chế tạo bản vẽ
</option><option value="105111">90 Cấp mũ giáp chế tạo bản vẽ
</option><option value="105112">100 Cấp mũ giáp chế tạo bản vẽ
</option><option value="105113">60 Cấp giày chế tạo bản vẽ
</option><option value="105114">70 Cấp giày chế tạo bản vẽ
</option><option value="105115">80 Cấp giày chế tạo bản vẽ
</option><option value="105116">90 Cấp giày chế tạo bản vẽ
</option><option value="105117">100 Cấp giày chế tạo bản vẽ
</option><option value="105118">60 Cấp chiếc nhẫn chế tạo bản vẽ
</option><option value="105119">70 Cấp chiếc nhẫn chế tạo bản vẽ
</option><option value="105120">80 Cấp chiếc nhẫn chế tạo bản vẽ
</option><option value="105121">90 Cấp chiếc nhẫn chế tạo bản vẽ
</option><option value="105122">100 Cấp chiếc nhẫn chế tạo bản vẽ
</option><option value="105123">60 Cấp eo rơi chế tạo bản vẽ
</option><option value="105124">70 Cấp eo rơi chế tạo bản vẽ
</option><option value="105125">80 Cấp eo rơi chế tạo bản vẽ
</option><option value="105126">90 Cấp eo rơi chế tạo bản vẽ
</option><option value="105127">100 Cấp eo rơi chế tạo bản vẽ
</option><option value="105128">60 Cấp dây chuyền chế tạo bản vẽ
</option><option value="105129">70 Cấp dây chuyền chế tạo bản vẽ
</option><option value="105130">80 Cấp dây chuyền chế tạo bản vẽ
</option><option value="105131">90 Cấp dây chuyền chế tạo bản vẽ
</option><option value="105132">100 Cấp dây chuyền chế tạo bản vẽ
</option><option value="105148"> Gấp đôi kinh nghiệm dược thủy
</option><option value="105173"> Bánh chưng
</option><option value="105174"> Ngân phiếu
</option><option value="105175"> Sô cô la
</option><option value="105176"> Anh đào mousse
</option><option value="105177"> Thủy tinh cầu
</option><option value="105178"> Kẹo que
</option><option value="105179"> Siêu cấp kẹo que
</option><option value="105180"> Nhỏ tường vi
</option><option value="105181"> Hoa hồng đỏ
</option><option value="105182"> Ngự thủ
</option><option value="105194"> Đạp tuyết vô ngân (1 Nhật )
</option><option value="105195"> Kẹo mừng
</option><option value="105196"> Nhập học vỡ lòng
</option><option value="105197"> Cao cấp giáo sư
</option><option value="105198"> Đặc cấp giáo sư
</option><option value="105199"> Thiên tuyển danh sư
</option><option value="105200">1 Cấp bảo thạch túi
</option><option value="105201"> Kết hôn lễ phục
</option><option value="105202"> Ảm đạm linh hồn
</option><option value="105203"> Xán lạn linh hồn
</option><option value="105204"> Hướng nhan
</option><option value="105205"> Phục linh
</option><option value="105206"> Bạch chỉ
</option><option value="105207"> Thuỷ cúc
</option><option value="105208"> Cây chùm ớt
</option><option value="105209"> Mộc lan
</option><option value="105210"> Thiên tài địa bảo
</option><option value="105211"> Hoàng Trung Lý
</option><option value="105212"> Dung luyện lô
</option><option value="105213"> Võ học tinh yếu
</option><option value="105214"> Băng ngọc lộ
</option><option value="105215"> Bồ Đề hoa
</option><option value="105216">70 Cấp chế tạo đồ hộp
</option><option value="105237"> Truyền công quyển trục
</option><option value="105238"> Sơ cấp thời trang
</option><option value="105239"> Cuồng chiến dị hổ (7 Nhật )
</option><option value="105259"> Gió táp
</option><option value="105260"> Tử Anh
</option><option value="105261"> Cà sa
</option><option value="105262"> Cạn chỉ bích lạc
</option><option value="105263"> Ngũ độc thiếu nữ
</option><option value="105264"> Quân tử
</option><option value="105265"> Lăng lửa
</option><option value="105266"> Kiêm gia
</option><option value="105267"> Thị linh
</option><option value="105268"> Thần thú dê còng
</option><option value="105269"> Ngàn dặm truy phong
</option><option value="105270"> Con la lưu cá
</option><option value="105271"> Kim Mao Sư Vương
</option><option value="105272"> La Sát
</option><option value="105273"> Quán nhật
</option><option value="105274"> Mẫn diệt
</option><option value="105275"> Trăng sáng
</option><option value="105276"> Thiên Cương
</option><option value="105277"> Huyền hoàng vũ y
</option><option value="105278"> Tử ngọc yên la
</option><option value="105279"> Thiên mệnh thật nữ
</option><option value="105280"> Con nai
</option><option value="105281"> Như ý
</option><option value="105282"> Chấn thiên
</option><option value="105283"> Cầu Long
</option><option value="105284"> Chúc tuổi
</option><option value="105285"> Năm thú tinh hoa
</option><option value="105286"> Tân xuân
</option><option value="105287"> Đón người mới đến
</option><option value="105288"> Từ cũ
</option><option value="105289"> Dục hỏa
</option><option value="105290"> Băng tinh
</option><option value="105400"> Huyền hoàng vũ y (7 Nhật )
</option><option value="105401"> Cà sa (7 Nhật )
</option><option value="105402"> Thiên mệnh thật nữ (7 Nhật )
</option><option value="105403"> Tử ngọc yên la (7 Nhật )
</option><option value="105404"> Quân tử (7 Nhật )
</option><option value="105405"> Lăng lửa (7 Nhật )
</option><option value="105406"> Kiêm gia (7 Nhật )
</option><option value="105407"> Thị linh (7 Nhật )
</option><option value="105408"> Huyền hoàng vũ y (1 Nhật )
</option><option value="105409"> Cà sa (1 Nhật )
</option><option value="105410"> Thiên mệnh thật nữ (1 Nhật )
</option><option value="105411"> Tử ngọc yên la (1 Nhật )
</option><option value="105412"> Quân tử (1 Nhật )
</option><option value="105413"> Lăng lửa (1 Nhật )
</option><option value="105414"> Kiêm gia (1 Nhật )
</option><option value="105415"> Thị linh (1 Nhật )
</option><option value="105240">40 Cấp cam trang bảo hạp
</option><option value="105241">50 Cấp cam trang bảo hạp
</option><option value="105242">60 Cấp cam trang bảo hạp
</option><option value="105243"> Cao cấp hiệp khách sách kỹ năng
</option><option value="105244"> Cao cấp hiệp khách sách kỹ năng
</option><option value="105245"> Nhiệt tình
</option><option value="105246"> Lạnh lùng
</option><option value="105247"> Vô tư
</option><option value="105248"> Tự tư
</option><option value="105249"> Cẩn thận
</option><option value="105250"> Lỗ mãng
</option><option value="105251"> Nhân từ
</option><option value="105252"> Tàn nhẫn
</option><option value="105253"> Tha thứ
</option><option value="105254"> Nhỏ hẹp
</option><option value="105255"> Vong ngã đan
</option><option value="105256">3 Cấp bảo thạch túi
</option><option value="105257">5 Cấp bảo thạch túi
</option><option value="105258">7 Cấp bảo thạch túi
</option><option value="106001"> Kiện xương tán
</option><option value="106002"> Mạnh gân đan
</option><option value="106003"> Dễ huyết đan
</option><option value="106004"> Quỳnh hoa lộ
</option><option value="106009"> Tất sát
</option><option value="106010"> Trí mạng
</option><option value="106011"> Phá giáp
</option><option value="106012"> Đâm xuyên
</option><option value="106013"> Trảm cức
</option><option value="106014"> Bụi gai
</option><option value="106015"> Cường lực
</option><option value="106016"> Trú đóng ở
</option><option value="106017"> Nội khí
</option><option value="106018"> Cương khí
</option><option value="106019"> Viện hộ
</option><option value="106020"> Phù hộ
</option><option value="106021"> Thần tích
</option><option value="106022"> Thần diệt
</option><option value="106026"> Di hình
</option><option value="106027"> Kéo dài tính mạng
</option><option value="106028"> Phản kích
</option><option value="106029"> Cứu viện
</option><option value="106030"> Hút máu
</option><option value="106031"> Chiếu cố
</option><option value="106032"> Ăn mòn
</option><option value="106033"> Đóng băng
</option><option value="106034"> Suy yếu
</option><option value="106035"> Xua tan
</option><option value="106036"> Phá bích
</option><option value="106037"> Anh linh
</option><option value="106038"> Bất khuất
</option><option value="106039"> Trùng sinh
</option><option value="106040"> Thiết cốt
</option><option value="106041"> Gãy xương
</option><option value="106042"> Dũng chiến
</option><option value="106043"> Tập kích bất ngờ
</option><option value="106044"> To lớn
</option><option value="106045"> Tập trí
</option><option value="106046"> Nhanh chóng mẫn
</option><option value="106047"> Hợp thành thần
</option><option value="106048"> Kiện thể
</option><option value="106049"> Oai hùng
</option><option value="106050"> Trầm mặc trúng đích
</option><option value="106051"> Giam cầm trúng đích
</option><option value="106052"> Mê muội trúng đích
</option><option value="106053"> Cấm liệu trúng đích
</option><option value="106054"> Chấn nhiếp trúng đích
</option><option value="106055"> Tịnh hóa trúng đích
</option><option value="106056"> Khép lại
</option><option value="106057"> Chống cự
</option><option value="106058"> Căm hận
</option><option value="106059"> Lẫn nhau tổn thương
</option><option value="106060"> Cầm nã
</option><option value="106061"> Chuyên chú đả kích
</option><option value="106062"> Cao cấp tất sát
</option><option value="106063"> Cao cấp trí mạng
</option><option value="106064"> Cao cấp phá giáp
</option><option value="106065"> Cao cấp đâm xuyên
</option><option value="106066"> Cao cấp trảm cức
</option><option value="106067"> Cao cấp bụi gai
</option><option value="106068"> Cao cấp cường lực
</option><option value="106069"> Cao cấp trú đóng ở
</option><option value="106070"> Cao cấp nội khí
</option><option value="106071"> Cao cấp cương khí
</option><option value="106072"> Cao cấp viện hộ
</option><option value="106073"> Cao cấp phù hộ
</option><option value="106074"> Cao cấp thần tích
</option><option value="106075"> Cao cấp thần diệt
</option><option value="106079"> Cao cấp di hình
</option><option value="106080"> Cao cấp kéo dài tính mạng
</option><option value="106081"> Cao cấp phản kích
</option><option value="106082"> Cao cấp cứu viện
</option><option value="106083"> Cao cấp hút máu
</option><option value="106084"> Cao cấp chiếu cố
</option><option value="106085"> Cao cấp ăn mòn
</option><option value="106086"> Cao cấp đóng băng
</option><option value="106087"> Cao cấp suy yếu
</option><option value="106088"> Cao cấp xua tan
</option><option value="106089"> Cao cấp phá bích
</option><option value="106090"> Cao cấp anh linh
</option><option value="106091"> Cao cấp bất khuất
</option><option value="106092"> Cao cấp trùng sinh
</option><option value="106093"> Cao cấp thiết cốt
</option><option value="106094"> Cao cấp gãy xương
</option><option value="106095"> Cao cấp dũng chiến
</option><option value="106096"> Cao cấp tập kích bất ngờ
</option><option value="106097"> Cao cấp to lớn
</option><option value="106098"> Cao cấp tập trí
</option><option value="106099"> Cao cấp nhanh chóng mẫn
</option><option value="106100"> Cao cấp hợp thành thần
</option><option value="106101"> Cao cấp kiện thể
</option><option value="106102"> Cao cấp oai hùng
</option><option value="106103"> Cao cấp trầm mặc trúng đích
</option><option value="106104"> Cao cấp giam cầm trúng đích
</option><option value="106105"> Cao cấp mê muội trúng đích
</option><option value="106106"> Cao cấp cấm liệu trúng đích
</option><option value="106107"> Cao cấp chấn nhiếp trúng đích
</option><option value="106108"> Cao cấp tịnh hóa trúng đích
</option><option value="106109"> Cao cấp khép lại
</option><option value="106110"> Cao cấp chống cự
</option><option value="106111"> Cao cấp căm hận
</option><option value="106112"> Cao cấp lẫn nhau tổn thương
</option><option value="106113"> Cao cấp cầm nã
</option><option value="106114"> Cao cấp chuyên chú đả kích
</option><option value="106115"> Tiểu Y Tiên
</option><option value="106116"> Khâu gió núi
</option><option value="106117"> Bạch a thêu
</option><option value="106118"> Đinh đang
</option><option value="106119"> Triển bay
</option><option value="106120"> Sử Tiểu Thúy
</option><option value="106121"> Đinh không bốn
</option><option value="106122"> Meven hinh
</option><option value="106123"> Thạch Thanh
</option><option value="106124"> Bạch Tự Tại
</option><option value="106125"> Trương Tam
</option><option value="106126"> Tạ khói khách
</option><option value="106127"> Thạch Phá Thiên
</option><option value="106128"> Đại bi lão nhân
</option><option value="106129"> Long đảo chủ
</option><option value="106130"> Mộc đảo chủ
</option><option value="106131"> Bồ tư khúc mật rắn
</option><option value="106132"> Tiểu Y Tiên
</option><option value="106133"> Khâu gió núi
</option><option value="106134"> Bạch a thêu
</option><option value="106135"> Đinh đang
</option><option value="106136"> Triển bay
</option><option value="106137"> Sử Tiểu Thúy
</option><option value="106138"> Đinh không bốn
</option><option value="106139"> Meven hinh
</option><option value="106140"> Thạch Thanh
</option><option value="106141"> Bạch Tự Tại
</option><option value="106142"> Trương Tam
</option><option value="106143"> Tạ khói khách
</option><option value="106144"> Thạch Phá Thiên
</option><option value="106145"> Đại bi lão nhân
</option><option value="106146"> Trương Tam tín vật
</option><option value="106147"> Thạch Phá Thiên tín vật
</option><option value="106148"> Tạ khói khách tín vật
</option><option value="106149"> Long đảo chủ tín vật
</option><option value="106150"> Mộc đảo chủ tín vật
</option><option value="106151"> Ngân Nguyệt
</option><option value="106152"> Ngân Nguyệt
</option><option value="106153"> Ngân Nguyệt tín vật
</option><option value="106201"> Bạch a thêu
</option><option value="106202"> Đinh đang
</option><option value="106203"> Triển bay
</option><option value="106204"> Sử Tiểu Thúy
</option><option value="106205"> Đinh không bốn
</option><option value="106206"> Đinh không ba
</option><option value="106207"> Tạ khói khách
</option><option value="106208"> Bối Hải Thạch
</option><option value="106209"> Trương Tam
</option><option value="106210"> Lý Tứ
</option><option value="106211"> Thạch Thanh
</option><option value="106212"> Bạch Tự Tại
</option><option value="106213"> Thạch Phá Thiên
</option><option value="106214"> Thạch Trung Ngọc
</option><option value="106215"> Đại bi lão nhân
</option><option value="106216"> Long đảo chủ
</option><option value="106217"> Mộc đảo chủ
</option><option value="106218"> Truyền công hiệp khách
</option><option value="106219"> Tiểu Y Tiên
</option><option value="106220"> Khâu gió núi
</option><option value="106221"> An phụng nhật
</option><option value="106222"> Hách sắt
</option><option value="106223"> Mị nhi
</option><option value="106224"> Meven hinh
</option><option value="106225"> Thích khách đinh đang
</option><option value="106226"> Bạch Vạn Kiếm
</option><option value="106227"> Truyền công hiệp khách
</option><option value="106228"> Càng đắc thắng
</option><option value="106229"> Cảnh vạn chuông
</option><option value="106230"> Sát sinh tăng
</option><option value="106231"> Nguyễn luyện váy
</option><option value="106232"> Hồng Tụ khuynh thành
</option><option value="106233"> Truyền công hiệp khách
</option><option value="106234"> Lăng Tiêu đệ tử
</option><option value="106235"> Nga Mi đệ tử
</option><option value="106236"> Định thiền đệ tử
</option><option value="106237"> Ngũ độc đệ tử
</option><option value="106238"> Truyền công hiệp khách
</option><option value="107001"> Xem xét cơ quan
</option><option value="107002"> Nội công hộp gỗ
</option><option value="107003"> Truyền tống quyển trục
</option><option value="107004"> Thỏi bạc ròng
</option><option value="107005"> Bách Hoa tửu
</option><option value="107006"> Hiệp khách khiến
</option><option value="107007"> Pháo hoa
</option><option value="107008"> Hồng bao
</option><option value="107009"> Rượu giao bôi
</option><option value="107010"> Thiên diện ngọc bài
</option><option value="107011"> Cửu chuyển hồi xuân
</option><option value="107012"> Đồng tâm ngọc bội
</option><option value="107013"> Thư
</option><option value="107014"> Thần bí hồ lô
</option><option value="107015"> Bách bảo rương
</option><option value="107016"> Bao phục
</option><option value="107110"> Khai ngộ thạch
</option><option value="107120"> Đẩu văn bia đá
</option><option value="107130"> Chân kinh điển tịch
</option><option value="108401"> Bí tịch · Trời lạnh Tây Bắc
</option><option value="108402"> Bí tịch · Thủy Vân đoạn
</option><option value="108403"> Bí tịch · Phá Khí thức
</option><option value="108404"> Bí tịch · Ngựa xúc hoa rơi
</option><option value="108405"> Bí tịch · Quét rồng thế
</option><option value="108406"> Bí tịch · Cực hàn chi khí
</option><option value="108407"> Bí tịch · Đúng ngay vào mặt thế
</option><option value="108408"> Bí tịch · Thiên ý như kiếm
</option><option value="108409"> Bí tịch · Bạch hồng quán nhật
</option><option value="108410"> Bí tịch · Lãng tử hồi đầu
</option><option value="108411"> Bí tịch · Vạn Nhạc Triều Tông
</option><option value="108412"> Bí tịch · Dò xét tuyết
</option><option value="108413"> Bí tịch · Khí ngưng băng đâm
</option><option value="108414"> Bí tịch · Đoạn tuyết bổ
</option><option value="108415"> Bí tịch · Mây trắng ra tụ
</option><option value="108416"> Bí tịch · Gió quét hoa mai
</option><option value="108417"> Bí tịch · Một kiếm quang lạnh
</option><option value="108418"> Bí tịch · Trăm bước Lăng Ba
</option><option value="108419"> Bí tịch · Kiếm hiệp đầy trời
</option><option value="108420"> Bí tịch · Cổ thụ cuộn rễ
</option><option value="108421"> Bí tịch · Hàng Long thức
</option><option value="108422"> Bí tịch · Say mai
</option><option value="108423"> Bí tịch · Tứ tuyệt kiếm trận
</option><option value="108424"> Bí tịch · Gió đến Xuy Tuyết
</option><option value="108431"> Bí tịch · Lôi Điểu
</option><option value="108432"> Bí tịch · Thốc tổn thương
</option><option value="108433"> Bí tịch · Thấu xương
</option><option value="108434"> Bí tịch · Giương cánh
</option><option value="108435"> Bí tịch · Bạo kích
</option><option value="108436"> Bí tịch · Thiên Lôi rơi
</option><option value="108437"> Bí tịch · Tê liệt
</option><option value="108438"> Bí tịch · Bắn nhanh
</option><option value="108439"> Bí tịch · Thần lực
</option><option value="108440"> Bí tịch · Ngắm bắn
</option><option value="108441"> Bí tịch · Tiễn lam
</option><option value="108442"> Bí tịch · Mau lẹ
</option><option value="108443"> Bí tịch · Trời thú
</option><option value="108444"> Bí tịch · Liên xạ
</option><option value="108445"> Bí tịch · Cuồng ưng
</option><option value="108446"> Bí tịch · Sương giá
</option><option value="108447"> Bí tịch · Phá giáp
</option><option value="108448"> Bí tịch · Thú tâm tiễn
</option><option value="108449"> Bí tịch · Tru tâm
</option><option value="108450"> Bí tịch · Bạo kích
</option><option value="108451"> Bí tịch · Nứt sọ
</option><option value="108452"> Bí tịch · Cầu sinh
</option><option value="108453"> Bí tịch · Du hiệp
</option><option value="108454"> Bí tịch · Ám sát
</option><option value="108461"> Bí tịch · Phi nhận
</option><option value="108462"> Bí tịch · Múa kiếm
</option><option value="108463"> Bí tịch · Phệ huyết
</option><option value="108464"> Bí tịch · Xé rách
</option><option value="108465"> Bí tịch · Bạo kích
</option><option value="108466"> Bí tịch · Quỷ hầu liên trảm
</option><option value="108467"> Bí tịch · Gọt giáp
</option><option value="108468"> Bí tịch · Ảnh nhận
</option><option value="108469"> Bí tịch · Quỷ cắt
</option><option value="108470"> Bí tịch · Nhanh công
</option><option value="108471"> Bí tịch · Khát máu
</option><option value="108472"> Bí tịch · Mau lẹ
</option><option value="108473"> Bí tịch · Gió trảm
</option><option value="108474"> Bí tịch · Liên kích
</option><option value="108475"> Bí tịch · Thuận gió
</option><option value="108476"> Bí tịch · Nát sọ
</option><option value="108477"> Bí tịch · Bạo kích
</option><option value="108478"> Bí tịch · Thú hồn
</option><option value="108479"> Bí tịch · Nhanh chóng gió
</option><option value="108480"> Bí tịch · Hồn trói
</option><option value="108481"> Bí tịch · Ẩn thân
</option><option value="108482"> Bí tịch · Uống máu
</option><option value="108483"> Bí tịch · Liên trảm
</option><option value="108484"> Bí tịch · Bất diệt
</option><option value="108491"> Bí tịch · Phục hổ nghe gió
</option><option value="108492"> Bí tịch · Kim cương phục ma
</option><option value="108493"> Bí tịch · Trào phúng
</option><option value="108494"> Bí tịch · Phật môn rộng độ
</option><option value="108495"> Bí tịch · Phật pháp vô biên
</option><option value="108496"> Bí tịch · Phổ độ tứ phương
</option><option value="108497"> Bí tịch · Vạn phật quy tông
</option><option value="108498"> Bí tịch · Phật hải vô biên
</option><option value="108499"> Bí tịch · Kim Chung Tráo
</option><option value="108500"> Bí tịch · Đại bàng giương cánh
</option><option value="108501"> Bí tịch · Từ bi
</option><option value="108502"> Bí tịch · Cường thân
</option><option value="108503"> Bí tịch · Cầm long trảo
</option><option value="108504"> Bí tịch · Hàng phục tâm
</option><option value="108505"> Bí tịch · Mượn rượu lực hút
</option><option value="108506"> Bí tịch · Say nằm càn khôn
</option><option value="108507"> Bí tịch · Long Trảo Thủ
</option><option value="108508"> Bí tịch · Hoành tảo thiên quân
</option><option value="108509"> Bí tịch · Say nằm sa trường
</option><option value="108510"> Bí tịch · Nhân côn hợp nhất
</option><option value="108511"> Bí tịch · Túy Bát Tiên
</option><option value="108512"> Bí tịch · Sống mơ mơ màng màng
</option><option value="108513"> Bí tịch · Một say tiêu dao
</option><option value="108514"> Bí tịch · Tửu tiên
</option><option value="108521"> Bí tịch · Phổ chiếu
</option><option value="108522"> Bí tịch · Thu Nguyệt
</option><option value="108523"> Bí tịch · Xung Hư dưỡng khí
</option><option value="108524"> Bí tịch · Nguyệt ra Đông Sơn
</option><option value="108525"> Bí tịch · Chiêu quân biên cương xa xôi
</option><option value="108526"> Bí tịch · Kéo dài tuổi thọ
</option><option value="108527"> Bí tịch · Kim châm độ kiếp
</option><option value="108528"> Bí tịch · Xoay chuyển trời đất thuật
</option><option value="108529"> Bí tịch · Hộ tâm quyết
</option><option value="108530"> Bí tịch · Phổ thiện chú
</option><option value="108531"> Bí tịch · Xuân hoa
</option><option value="108532"> Bí tịch · Phong huyệt
</option><option value="108533"> Bí tịch · Thanh tâm chú
</option><option value="108534"> Bí tịch · Phù dung tịnh đế
</option><option value="108535"> Bí tịch · Ngọc gãy
</option><option value="108536"> Bí tịch · Thanh tuyền
</option><option value="108537"> Bí tịch · Xuyên tim tận xương
</option><option value="108538"> Bí tịch · Đập nồi dìm thuyền
</option><option value="108539"> Bí tịch · Xuyên thấu
</option><option value="108540"> Bí tịch · Quân cần yêu ta
</option><option value="108541"> Bí tịch · Mẫn diệt
</option><option value="108542"> Bí tịch · Tĩnh khí
</option><option value="108543"> Bí tịch · Cơ trí
</option><option value="108544"> Bí tịch · Hộ thân
</option><option value="108551"> Bí tịch · Luân hồi trời sinh
</option><option value="108552"> Bí tịch · Ong độc
</option><option value="108553"> Bí tịch · Vạn thú
</option><option value="108554"> Bí tịch · Cố hồn
</option><option value="108555"> Bí tịch · Cường lực
</option><option value="108556"> Bí tịch · Tà y thánh thủ
</option><option value="108557"> Bí tịch · Linh thông
</option><option value="108558"> Bí tịch · Kim cương
</option><option value="108559"> Bí tịch · Khôi phục
</option><option value="108560"> Bí tịch · Cứng cỏi
</option><option value="108561"> Bí tịch · Khôi phục
</option><option value="108562"> Bí tịch · Linh lưu
</option><option value="108563"> Bí tịch · Ma linh nhện
</option><option value="108564"> Bí tịch · Ong ngủ đông
</option><option value="108565"> Bí tịch · Chín mệnh
</option><option value="108566"> Bí tịch · Linh sủng
</option><option value="108567"> Bí tịch · Quả đâm
</option><option value="108568"> Bí tịch · Máu dẫn bọ cạp
</option><option value="108569"> Bí tịch · Cộng sinh
</option><option value="108570"> Bí tịch · Mạnh điện
</option><option value="108571"> Bí tịch · Quân đoàn
</option><option value="108572"> Bí tịch · Chung Linh
</option><option value="108573"> Bí tịch · Linh tâm
</option><option value="108574"> Bí tịch · Anh dũng
</option><option value="108823"> Trời lạnh Tây Bắc · Bên trên
</option><option value="108824"> Trời lạnh Tây Bắc · Hạ
</option><option value="108825"> Lôi Điểu · Bên trên
</option><option value="108826"> Lôi Điểu · Hạ
</option><option value="108827"> Phi nhận · Bên trên
</option><option value="108828"> Phi nhận · Hạ
</option><option value="108829"> Cầm long trảo · Bên trên
</option><option value="108830"> Cầm long trảo · Hạ
</option><option value="108831"> Thanh tâm chú · Bên trên
</option><option value="108832"> Thanh tâm chú · Hạ
</option><option value="108833"> Ma linh nhện · Bên trên
</option><option value="108834"> Ma linh nhện · Hạ
</option><option value="108835"> Cũ nát bí tịch
</option><option value="108836"> Cũ nát bí tịch
</option><option value="109001"> Thổ nạp tâm pháp
</option><option value="109002"> Hàn băng chân khí
</option><option value="109003"> Võ Đang tâm pháp
</option><option value="109004"> Thanh Tâm quyết
</option><option value="109005"> Núi tuyết tâm pháp
</option><option value="109006"> Bàn Nhược công
</option><option value="109007"> Đoạn long kình
</option><option value="109008"> Thiên Cương tâm pháp
</option><option value="109009"> La Hán phục ma
</option><option value="109010"> Ngấm ngầm hại người
</option><option value="109011"> Long Tượng Bàn Nhược
</option><option value="109012"> Vô tướng thần công
</option><option value="109013"> Bắc Minh chân kinh
</option><option value="109014"> Thái Cực tâm pháp
</option><option value="109015"> Dịch Cân Kinh
</option><option value="109016"> Tẩy Tủy Kinh
</option><option value="109101"> Thổ nạp tâm pháp
</option><option value="109102"> Hàn băng chân khí
</option><option value="109103"> Võ Đang tâm pháp
</option><option value="109104"> Thanh Tâm quyết
</option><option value="109105"> Núi tuyết tâm pháp
</option><option value="109106"> Bàn Nhược công
</option><option value="109107"> Đoạn long kình
</option><option value="109108"> Thiên Cương tâm pháp
</option><option value="109109"> La Hán phục ma
</option><option value="109110"> Ngấm ngầm hại người
</option><option value="109111"> Long Tượng Bàn Nhược
</option><option value="109112"> Vô tướng thần công
</option><option value="109113"> Bắc Minh chân kinh
</option><option value="109114"> Thái Cực tâm pháp
</option><option value="109115"> Dịch Cân Kinh
</option><option value="109116"> Tẩy Tủy Kinh
</option><option value="109201"> Thổ nạp tâm pháp
</option><option value="109202"> Hàn băng chân khí
</option><option value="109203"> Võ Đang tâm pháp
</option><option value="109204"> Thanh Tâm quyết
</option><option value="109205"> Núi tuyết tâm pháp
</option><option value="109206"> Bàn Nhược công
</option><option value="109207"> Đoạn long kình
</option><option value="109208"> Thiên Cương tâm pháp
</option><option value="109209"> La Hán phục ma
</option><option value="109210"> Ngấm ngầm hại người
</option><option value="109211"> Long Tượng Bàn Nhược
</option><option value="109212"> Vô tướng thần công
</option><option value="109213"> Bắc Minh chân kinh
</option><option value="109214"> Thái Cực tâm pháp
</option><option value="109215"> Dịch Cân Kinh
</option><option value="109216"> Tẩy Tủy Kinh
</option><option value="109301"> Tý Thử · Chân nghĩa
</option><option value="109302"> Sửu Ngưu · Chân nghĩa
</option><option value="109303"> Dần Hổ · Chân nghĩa
</option><option value="109304"> Mão Thỏ · Chân nghĩa
</option><option value="109305"> Thìn Long · Chân nghĩa
</option><option value="109306"> Tị Xà · Chân nghĩa
</option><option value="109307"> Buổi trưa ngựa · Chân nghĩa
</option><option value="109308"> Vị Dương · Chân nghĩa
</option><option value="109309"> Thân Hầu · Chân nghĩa
</option><option value="109310"> Dậu Kê · Chân nghĩa
</option><option value="109311"> Tuất Cẩu · Chân nghĩa
</option><option value="109312"> Chu Tước · Chân nghĩa
</option><option value="109313"> Thanh Long · Chân nghĩa
</option><option value="109314"> Bạch Hổ · Chân nghĩa
</option><option value="109315"> Huyền Vũ · Chân nghĩa
</option><option value="111001"> Hồng Mã Não 1 Cấp
</option><option value="111002"> Hồng Mã Não 2 Cấp
</option><option value="111003"> Hồng Mã Não 3 Cấp
</option><option value="111004"> Hồng Mã Não 4 Cấp
</option><option value="111005"> Hồng Mã Não 5 Cấp
</option><option value="111006"> Hồng Mã Não 6 Cấp
</option><option value="111007"> Hồng Mã Não 7 Cấp
</option><option value="111008"> Hồng Mã Não 8 Cấp
</option><option value="111009"> Hồng Mã Não 9 Cấp
</option><option value="111010"> Hồng Mã Não 10 Cấp
</option><option value="111011"> Hồng Mã Não 11 Cấp
</option><option value="111012"> Hồng Mã Não 12 Cấp
</option><option value="111013"> Hồng Mã Não 13 Cấp
</option><option value="111014"> Hồng Mã Não 14 Cấp
</option><option value="111015"> Hồng Mã Não 15 Cấp
</option><option value="111016"> Hoàng bích tỉ 1 Cấp
</option><option value="111017"> Hoàng bích tỉ 2 Cấp
</option><option value="111018"> Hoàng bích tỉ 3 Cấp
</option><option value="111019"> Hoàng bích tỉ 4 Cấp
</option><option value="111020"> Hoàng bích tỉ 5 Cấp
</option><option value="111021"> Hoàng bích tỉ 6 Cấp
</option><option value="111022"> Hoàng bích tỉ 7 Cấp
</option><option value="111023"> Hoàng bích tỉ 8 Cấp
</option><option value="111024"> Hoàng bích tỉ 9 Cấp
</option><option value="111025"> Hoàng bích tỉ 10 Cấp
</option><option value="111026"> Hoàng bích tỉ 11 Cấp
</option><option value="111027"> Hoàng bích tỉ 12 Cấp
</option><option value="111028"> Hoàng bích tỉ 13 Cấp
</option><option value="111029"> Hoàng bích tỉ 14 Cấp
</option><option value="111030"> Hoàng bích tỉ 15 Cấp
</option><option value="111031"> Lục lỏng thạch 1 Cấp
</option><option value="111032"> Lục lỏng thạch 2 Cấp
</option><option value="111033"> Lục lỏng thạch 3 Cấp
</option><option value="111034"> Lục lỏng thạch 4 Cấp
</option><option value="111035"> Lục lỏng thạch 5 Cấp
</option><option value="111036"> Lục lỏng thạch 6 Cấp
</option><option value="111037"> Lục lỏng thạch 7 Cấp
</option><option value="111038"> Lục lỏng thạch 8 Cấp
</option><option value="111039"> Lục lỏng thạch 9 Cấp
</option><option value="111040"> Lục lỏng thạch 10 Cấp
</option><option value="111041"> Lục lỏng thạch 11 Cấp
</option><option value="111042"> Lục lỏng thạch 12 Cấp
</option><option value="111043"> Lục lỏng thạch 13 Cấp
</option><option value="111044"> Lục lỏng thạch 14 Cấp
</option><option value="111045"> Lục lỏng thạch 15 Cấp
</option><option value="111046"> Lam zirconium thạch 1 Cấp
</option><option value="111047"> Lam zirconium thạch 2 Cấp
</option><option value="111048"> Lam zirconium thạch 3 Cấp
</option><option value="111049"> Lam zirconium thạch 4 Cấp
</option><option value="111050"> Lam zirconium thạch 5 Cấp
</option><option value="111051"> Lam zirconium thạch 6 Cấp
</option><option value="111052"> Lam zirconium thạch 7 Cấp
</option><option value="111053"> Lam zirconium thạch 8 Cấp
</option><option value="111054"> Lam zirconium thạch 9 Cấp
</option><option value="111055"> Lam zirconium thạch 10 Cấp
</option><option value="111056"> Lam zirconium thạch 11 Cấp
</option><option value="111057"> Lam zirconium thạch 12 Cấp
</option><option value="111058"> Lam zirconium thạch 13 Cấp
</option><option value="111059"> Lam zirconium thạch 14 Cấp
</option><option value="111060"> Lam zirconium thạch 15 Cấp
</option><option value="120001"> Gang trường kiếm
</option><option value="120002"> Cũ nát thủ nỏ
</option><option value="120003"> Răng nanh chủy thủ
</option><option value="120004"> Thô mộc trường côn
</option><option value="120005"> Xích Đồng đoản kiếm
</option><option value="120006"> Xích Đồng đoản kiếm
</option><option value="120007"> Sáo trúc
</option><option value="120008"> Sáo trúc
</option><option value="120009"> Vải thô áo
</option><option value="120010"> Vải thô hộ thối
</option><option value="120011"> Vải thô khăn trùm đầu ( Vật )
</option><option value="120012"> Vải thô khăn trùm đầu ( Pháp )
</option><option value="120013"> Vải thô giày
</option><option value="120014"> Mộc chiếc nhẫn ( Vật )
</option><option value="120015"> Mộc chiếc nhẫn ( Pháp )
</option><option value="120016"> Mộc điêu eo rơi ( Vật )
</option><option value="120017"> Mộc điêu eo rơi ( Pháp )
</option><option value="120018"> Mộc điêu dây chuyền
</option><option value="120019"> Gang trường kiếm
</option><option value="120020"> Cũ nát thủ nỏ
</option><option value="120021"> Răng nanh chủy thủ
</option><option value="120022"> Thô mộc trường côn
</option><option value="120023"> Xích Đồng đoản kiếm
</option><option value="120024"> Xích Đồng đoản kiếm
</option><option value="120025"> Sáo trúc
</option><option value="120026"> Sáo trúc
</option><option value="120027"> Vải thô áo
</option><option value="120028"> Vải thô hộ thối
</option><option value="120029"> Vải thô khăn trùm đầu ( Vật )
</option><option value="120030"> Vải thô khăn trùm đầu ( Pháp )
</option><option value="120031"> Vải thô giày
</option><option value="120032"> Mộc chiếc nhẫn ( Vật )
</option><option value="120033"> Mộc chiếc nhẫn ( Pháp )
</option><option value="120034"> Mộc điêu eo rơi ( Vật )
</option><option value="120035"> Mộc điêu eo rơi ( Pháp )
</option><option value="120036"> Mộc điêu dây chuyền
</option><option value="121001"> Gang trường kiếm
</option><option value="121002"> Cũ nát thủ nỏ
</option><option value="121003"> Răng nanh chủy thủ
</option><option value="121004"> Thô mộc trường côn
</option><option value="121005"> Xích Đồng đoản kiếm
</option><option value="121006"> Xích Đồng đoản kiếm
</option><option value="121007"> Sáo trúc
</option><option value="121008"> Sáo trúc
</option><option value="121009"> Vải thô áo
</option><option value="121010"> Vải thô hộ thối
</option><option value="121011"> Vải thô khăn trùm đầu ( Vật )
</option><option value="121012"> Vải thô khăn trùm đầu ( Pháp )
</option><option value="121013"> Vải thô giày
</option><option value="121014"> Mộc chiếc nhẫn ( Vật )
</option><option value="121015"> Mộc chiếc nhẫn ( Pháp )
</option><option value="121016"> Mộc điêu eo rơi ( Vật )
</option><option value="121017"> Mộc điêu eo rơi ( Pháp )
</option><option value="121018"> Mộc điêu dây chuyền
</option><option value="121019"> Gang trường kiếm
</option><option value="121020"> Cũ nát thủ nỏ
</option><option value="121021"> Răng nanh chủy thủ
</option><option value="121022"> Thô mộc trường côn
</option><option value="121023"> Xích Đồng đoản kiếm
</option><option value="121024"> Xích Đồng đoản kiếm
</option><option value="121025"> Sáo trúc
</option><option value="121026"> Sáo trúc
</option><option value="121027"> Vải thô áo
</option><option value="121028"> Vải thô hộ thối
</option><option value="121029"> Vải thô khăn trùm đầu ( Vật )
</option><option value="121030"> Vải thô khăn trùm đầu ( Pháp )
</option><option value="121031"> Vải thô giày
</option><option value="121032"> Mộc chiếc nhẫn ( Vật )
</option><option value="121033"> Mộc chiếc nhẫn ( Pháp )
</option><option value="121034"> Mộc điêu eo rơi ( Vật )
</option><option value="121035"> Mộc điêu eo rơi ( Pháp )
</option><option value="121036"> Mộc điêu dây chuyền
</option><option value="121037"> Gang trường kiếm
</option><option value="121038"> Cũ nát thủ nỏ
</option><option value="121039"> Răng nanh chủy thủ
</option><option value="121040"> Thô mộc trường côn
</option><option value="121041"> Xích Đồng đoản kiếm
</option><option value="121042"> Xích Đồng đoản kiếm
</option><option value="121043"> Sáo trúc
</option><option value="121044"> Sáo trúc
</option><option value="121045"> Vải thô áo
</option><option value="121046"> Vải thô hộ thối
</option><option value="121047"> Vải thô khăn trùm đầu ( Vật )
</option><option value="121048"> Vải thô khăn trùm đầu ( Pháp )
</option><option value="121049"> Vải thô giày
</option><option value="121050"> Mộc chiếc nhẫn ( Vật )
</option><option value="121051"> Mộc chiếc nhẫn ( Pháp )
</option><option value="121052"> Mộc điêu eo rơi ( Vật )
</option><option value="121053"> Mộc điêu eo rơi ( Pháp )
</option><option value="121054"> Mộc điêu dây chuyền
</option><option value="121055"> Gang trường kiếm
</option><option value="121056"> Cũ nát thủ nỏ
</option><option value="121057"> Răng nanh chủy thủ
</option><option value="121058"> Thô mộc trường côn
</option><option value="121059"> Xích Đồng đoản kiếm
</option><option value="121060"> Xích Đồng đoản kiếm
</option><option value="121061"> Sáo trúc
</option><option value="121062"> Sáo trúc
</option><option value="121063"> Vải thô áo
</option><option value="121064"> Vải thô hộ thối
</option><option value="121065"> Vải thô khăn trùm đầu ( Vật )
</option><option value="121066"> Vải thô khăn trùm đầu ( Pháp )
</option><option value="121067"> Vải thô giày
</option><option value="121068"> Mộc chiếc nhẫn ( Vật )
</option><option value="121069"> Mộc chiếc nhẫn ( Pháp )
</option><option value="121070"> Mộc điêu eo rơi ( Vật )
</option><option value="121071"> Mộc điêu eo rơi ( Pháp )
</option><option value="121072"> Mộc điêu dây chuyền
</option><option value="122001"> Gang trường kiếm
</option><option value="122002"> Cũ nát thủ nỏ
</option><option value="122003"> Răng nanh chủy thủ
</option><option value="122004"> Thô mộc trường côn
</option><option value="122005"> Xích Đồng đoản kiếm
</option><option value="122006"> Xích Đồng đoản kiếm
</option><option value="122007"> Sáo trúc
</option><option value="122008"> Sáo trúc
</option><option value="122009"> Vải thô áo
</option><option value="122010"> Vải thô hộ thối
</option><option value="122011"> Vải thô khăn trùm đầu ( Vật )
</option><option value="122012"> Vải thô khăn trùm đầu ( Pháp )
</option><option value="122013"> Vải thô giày
</option><option value="122014"> Mộc chiếc nhẫn ( Vật )
</option><option value="122015"> Mộc chiếc nhẫn ( Pháp )
</option><option value="122016"> Mộc điêu eo rơi ( Vật )
</option><option value="122017"> Mộc điêu eo rơi ( Pháp )
</option><option value="122018"> Mộc điêu dây chuyền
</option><option value="122019"> Gang trường kiếm
</option><option value="122020"> Cũ nát thủ nỏ
</option><option value="122021"> Răng nanh chủy thủ
</option><option value="122022"> Thô mộc trường côn
</option><option value="122023"> Xích Đồng đoản kiếm
</option><option value="122024"> Xích Đồng đoản kiếm
</option><option value="122025"> Sáo trúc
</option><option value="122026"> Sáo trúc
</option><option value="122027"> Vải thô áo
</option><option value="122028"> Vải thô hộ thối
</option><option value="122029"> Vải thô khăn trùm đầu ( Vật )
</option><option value="122030"> Vải thô khăn trùm đầu ( Pháp )
</option><option value="122031"> Vải thô giày
</option><option value="122032"> Mộc chiếc nhẫn ( Vật )
</option><option value="122033"> Mộc chiếc nhẫn ( Pháp )
</option><option value="122034"> Mộc điêu eo rơi ( Vật )
</option><option value="122035"> Mộc điêu eo rơi ( Pháp )
</option><option value="122036"> Mộc điêu dây chuyền
</option><option value="122037"> Gang trường kiếm
</option><option value="122038"> Cũ nát thủ nỏ
</option><option value="122039"> Răng nanh chủy thủ
</option><option value="122040"> Thô mộc trường côn
</option><option value="122041"> Xích Đồng đoản kiếm
</option><option value="122042"> Xích Đồng đoản kiếm
</option><option value="122043"> Sáo trúc
</option><option value="122044"> Sáo trúc
</option><option value="122045"> Vải thô áo
</option><option value="122046"> Vải thô hộ thối
</option><option value="122047"> Vải thô khăn trùm đầu ( Vật )
</option><option value="122048"> Vải thô khăn trùm đầu ( Pháp )
</option><option value="122049"> Vải thô giày
</option><option value="122050"> Mộc chiếc nhẫn ( Vật )
</option><option value="122051"> Mộc chiếc nhẫn ( Pháp )
</option><option value="122052"> Mộc điêu eo rơi ( Vật )
</option><option value="122053"> Mộc điêu eo rơi ( Pháp )
</option><option value="122054"> Mộc điêu dây chuyền
</option><option value="122055"> Gang trường kiếm
</option><option value="122056"> Cũ nát thủ nỏ
</option><option value="122057"> Răng nanh chủy thủ
</option><option value="122058"> Thô mộc trường côn
</option><option value="122059"> Xích Đồng đoản kiếm
</option><option value="122060"> Xích Đồng đoản kiếm
</option><option value="122061"> Sáo trúc
</option><option value="122062"> Sáo trúc
</option><option value="122063"> Vải thô áo
</option><option value="122064"> Vải thô hộ thối
</option><option value="122065"> Vải thô khăn trùm đầu ( Vật )
</option><option value="122066"> Vải thô khăn trùm đầu ( Pháp )
</option><option value="122067"> Vải thô giày
</option><option value="122068"> Mộc chiếc nhẫn ( Vật )
</option><option value="122069"> Mộc chiếc nhẫn ( Pháp )
</option><option value="122070"> Mộc điêu eo rơi ( Vật )
</option><option value="122071"> Mộc điêu eo rơi ( Pháp )
</option><option value="122072"> Mộc điêu dây chuyền
</option><option value="122073"> Gang trường kiếm
</option><option value="122074"> Cũ nát thủ nỏ
</option><option value="122075"> Răng nanh chủy thủ
</option><option value="122076"> Thô mộc trường côn
</option><option value="122077"> Xích Đồng đoản kiếm
</option><option value="122078"> Xích Đồng đoản kiếm
</option><option value="122079"> Sáo trúc
</option><option value="122080"> Sáo trúc
</option><option value="122081"> Vải thô áo
</option><option value="122082"> Vải thô hộ thối
</option><option value="122083"> Vải thô khăn trùm đầu ( Vật )
</option><option value="122084"> Vải thô khăn trùm đầu ( Pháp )
</option><option value="122085"> Vải thô giày
</option><option value="122086"> Mộc chiếc nhẫn ( Vật )
</option><option value="122087"> Mộc chiếc nhẫn ( Pháp )
</option><option value="122088"> Mộc điêu eo rơi ( Vật )
</option><option value="122089"> Mộc điêu eo rơi ( Pháp )
</option><option value="122090"> Mộc điêu dây chuyền
</option><option value="123001"> Thép ròng trường kiếm
</option><option value="123002"> Giản dị thủ nỏ
</option><option value="123003"> Trong tay áo kiếm
</option><option value="123004"> Đủ lông mày trường côn
</option><option value="123005"> Bách luyện đoản kiếm
</option><option value="123006"> Bách luyện đoản kiếm
</option><option value="123007"> Khổ Trúc địch
</option><option value="123008"> Khổ Trúc địch
</option><option value="123009"> Vải bông áo
</option><option value="123010"> Da trâu hộ thối
</option><option value="123011"> Vải bông khăn trùm đầu ( Vật )
</option><option value="123012"> Vải bông khăn trùm đầu ( Pháp )
</option><option value="123013"> Da hươu giày
</option><option value="123014"> Đồng thau chiếc nhẫn ( Vật )
</option><option value="123015"> Đồng thau chiếc nhẫn ( Pháp )
</option><option value="123016"> Đồng thau eo rơi ( Vật )
</option><option value="123017"> Đồng thau eo rơi ( Pháp )
</option><option value="123018"> Đồng thau dây chuyền
</option><option value="123019"> Thép ròng trường kiếm
</option><option value="123020"> Giản dị thủ nỏ
</option><option value="123021"> Trong tay áo kiếm
</option><option value="123022"> Đủ lông mày trường côn
</option><option value="123023"> Bách luyện đoản kiếm
</option><option value="123024"> Bách luyện đoản kiếm
</option><option value="123025"> Khổ Trúc địch
</option><option value="123026"> Khổ Trúc địch
</option><option value="123027"> Vải bông áo
</option><option value="123028"> Da trâu hộ thối
</option><option value="123029"> Vải bông khăn trùm đầu ( Vật )
</option><option value="123030"> Vải bông khăn trùm đầu ( Pháp )
</option><option value="123031"> Da hươu giày
</option><option value="123032"> Đồng thau chiếc nhẫn ( Vật )
</option><option value="123033"> Đồng thau chiếc nhẫn ( Pháp )
</option><option value="123034"> Đồng thau eo rơi ( Vật )
</option><option value="123035"> Đồng thau eo rơi ( Pháp )
</option><option value="123036"> Đồng thau dây chuyền
</option><option value="123037"> Thép ròng trường kiếm
</option><option value="123038"> Giản dị thủ nỏ
</option><option value="123039"> Trong tay áo kiếm
</option><option value="123040"> Đủ lông mày trường côn
</option><option value="123041"> Bách luyện đoản kiếm
</option><option value="123042"> Bách luyện đoản kiếm
</option><option value="123043"> Khổ Trúc địch
</option><option value="123044"> Khổ Trúc địch
</option><option value="123045"> Vải bông áo
</option><option value="123046"> Da trâu hộ thối
</option><option value="123047"> Vải bông khăn trùm đầu ( Vật )
</option><option value="123048"> Vải bông khăn trùm đầu ( Pháp )
</option><option value="123049"> Da hươu giày
</option><option value="123050"> Đồng thau chiếc nhẫn ( Vật )
</option><option value="123051"> Đồng thau chiếc nhẫn ( Pháp )
</option><option value="123052"> Đồng thau eo rơi ( Vật )
</option><option value="123053"> Đồng thau eo rơi ( Pháp )
</option><option value="123054"> Đồng thau dây chuyền
</option><option value="123055"> Thép ròng trường kiếm
</option><option value="123056"> Giản dị thủ nỏ
</option><option value="123057"> Trong tay áo kiếm
</option><option value="123058"> Đủ lông mày trường côn
</option><option value="123059"> Bách luyện đoản kiếm
</option><option value="123060"> Bách luyện đoản kiếm
</option><option value="123061"> Khổ Trúc địch
</option><option value="123062"> Khổ Trúc địch
</option><option value="123063"> Vải bông áo
</option><option value="123064"> Da trâu hộ thối
</option><option value="123065"> Vải bông khăn trùm đầu ( Vật )
</option><option value="123066"> Vải bông khăn trùm đầu ( Pháp )
</option><option value="123067"> Da hươu giày
</option><option value="123068"> Đồng thau chiếc nhẫn ( Vật )
</option><option value="123069"> Đồng thau chiếc nhẫn ( Pháp )
</option><option value="123070"> Đồng thau eo rơi ( Vật )
</option><option value="123071"> Đồng thau eo rơi ( Pháp )
</option><option value="123072"> Đồng thau dây chuyền
</option><option value="123073"> Du long bảo kiếm
</option><option value="123074"> Trăm cánh tay nỏ
</option><option value="123075"> Trong tay áo kiếm
</option><option value="123076"> Đủ lông mày trường côn
</option><option value="123077"> Bách luyện đoản kiếm
</option><option value="123078"> Bách luyện đoản kiếm
</option><option value="123079"> Khổ Trúc địch
</option><option value="123080"> Khổ Trúc địch
</option><option value="123081"> Vải bông áo
</option><option value="123082"> Da trâu hộ thối
</option><option value="123083"> Vải bông khăn trùm đầu ( Vật )
</option><option value="123084"> Vải bông khăn trùm đầu ( Pháp )
</option><option value="123085"> Da hươu giày
</option><option value="123086"> Đồng thau chiếc nhẫn ( Vật )
</option><option value="123087"> Đồng thau chiếc nhẫn ( Pháp )
</option><option value="123088"> Đồng thau eo rơi ( Vật )
</option><option value="123089"> Đồng thau eo rơi ( Pháp )
</option><option value="123090"> Đồng thau dây chuyền
</option><option value="123091"> Phi sương áo ngắn
</option><option value="123092"> Phi sương hộ thối
</option><option value="123093"> Mây trôi áo ngắn
</option><option value="123094"> Mây trôi hộ thối
</option><option value="123095"> Huyết ảnh áo ngắn
</option><option value="123096"> Huyết ảnh hộ thối
</option><option value="123097"> Thiền ý áo ngắn
</option><option value="123098"> Thiền ý hộ thối
</option><option value="123099"> Thiền định áo ngắn
</option><option value="123100"> Thiền định hộ thối
</option><option value="123101"> Năm bảo áo ngắn
</option><option value="123102"> Năm bảo hộ thối
</option><option value="124001"> Cổ định kiếm
</option><option value="124002"> Thần tí cung
</option><option value="124003"> Ô chùy đâm
</option><option value="124004"> Côn thép
</option><option value="124005"> Liễu Diệp kiếm
</option><option value="124006"> Liễu Diệp kiếm
</option><option value="124007"> Trúc tía địch
</option><option value="124008"> Trúc tía địch
</option><option value="124009"> Lỏng văn cẩm y
</option><option value="124010"> Lỏng văn hộ thối
</option><option value="124011"> Đỏ trách ( Vật )
</option><option value="124012"> Đỏ trách ( Pháp )
</option><option value="124013"> Lỏng văn giày
</option><option value="124014"> Bạch ngọc ban chỉ ( Vật )
</option><option value="124015"> Bạch ngọc ban chỉ ( Pháp )
</option><option value="124016"> Bạch ngọc eo rơi ( Vật )
</option><option value="124017"> Bạch ngọc eo rơi ( Pháp )
</option><option value="124018"> Bạch ngọc dây chuyền
</option><option value="124019"> Cổ định kiếm
</option><option value="124020"> Thần tí cung
</option><option value="124021"> Ô chùy đâm
</option><option value="124022"> Côn thép
</option><option value="124023"> Liễu Diệp kiếm
</option><option value="124024"> Liễu Diệp kiếm
</option><option value="124025"> Trúc tía địch
</option><option value="124026"> Trúc tía địch
</option><option value="124027"> Lỏng văn cẩm y
</option><option value="124028"> Lỏng văn hộ thối
</option><option value="124029"> Đỏ trách ( Vật )
</option><option value="124030"> Đỏ trách ( Pháp )
</option><option value="124031"> Lỏng văn giày
</option><option value="124032"> Bạch ngọc ban chỉ ( Vật )
</option><option value="124033"> Bạch ngọc ban chỉ ( Pháp )
</option><option value="124034"> Bạch ngọc eo rơi ( Vật )
</option><option value="124035"> Bạch ngọc eo rơi ( Pháp )
</option><option value="124036"> Bạch ngọc dây chuyền
</option><option value="124037"> Cổ định kiếm
</option><option value="124038"> Thần tí cung
</option><option value="124039"> Ô chùy đâm
</option><option value="124040"> Côn thép
</option><option value="124041"> Liễu Diệp kiếm
</option><option value="124042"> Liễu Diệp kiếm
</option><option value="124043"> Trúc tía địch
</option><option value="124044"> Trúc tía địch
</option><option value="124045"> Lỏng văn cẩm y
</option><option value="124046"> Lỏng văn hộ thối
</option><option value="124047"> Đỏ trách ( Vật )
</option><option value="124048"> Đỏ trách ( Pháp )
</option><option value="124049"> Lỏng văn giày
</option><option value="124050"> Bạch ngọc ban chỉ ( Vật )
</option><option value="124051"> Bạch ngọc ban chỉ ( Pháp )
</option><option value="124052"> Bạch ngọc eo rơi ( Vật )
</option><option value="124053"> Bạch ngọc eo rơi ( Pháp )
</option><option value="124054"> Bạch ngọc dây chuyền
</option><option value="124055"> Cổ định kiếm
</option><option value="124056"> Nằm nỏ
</option><option value="124057"> Ô chùy đâm
</option><option value="124058"> Côn thép
</option><option value="124059"> Liễu Diệp kiếm
</option><option value="124060"> Liễu Diệp kiếm
</option><option value="124061"> Trúc tía địch
</option><option value="124062"> Trúc tía địch
</option><option value="124063"> Lỏng văn cẩm y
</option><option value="124064"> Lỏng văn hộ thối
</option><option value="124065"> Đỏ trách ( Vật )
</option><option value="124066"> Đỏ trách ( Pháp )
</option><option value="124067"> Lỏng văn giày
</option><option value="124068"> Bạch ngọc ban chỉ ( Vật )
</option><option value="124069"> Bạch ngọc ban chỉ ( Pháp )
</option><option value="124070"> Bạch ngọc eo rơi ( Vật )
</option><option value="124071"> Bạch ngọc eo rơi ( Pháp )
</option><option value="124072"> Bạch ngọc dây chuyền
</option><option value="124073"> Cổ định kiếm
</option><option value="124074"> Nằm nỏ
</option><option value="124075"> Ô chùy đâm
</option><option value="124076"> Côn thép
</option><option value="124077"> Liễu Diệp kiếm
</option><option value="124078"> Liễu Diệp kiếm
</option><option value="124079"> Trúc tía địch
</option><option value="124080"> Trúc tía địch
</option><option value="124081"> Lỏng văn cẩm y
</option><option value="124082"> Lỏng văn hộ thối
</option><option value="124083"> Đỏ trách ( Vật )
</option><option value="124084"> Đỏ trách ( Pháp )
</option><option value="124085"> Lỏng văn giày
</option><option value="124086"> Bạch ngọc ban chỉ ( Vật )
</option><option value="124087"> Bạch ngọc ban chỉ ( Pháp )
</option><option value="124088"> Bạch ngọc eo rơi ( Vật )
</option><option value="124089"> Bạch ngọc eo rơi ( Pháp )
</option><option value="124090"> Bạch ngọc dây chuyền
</option><option value="124091"> Hàn mai áo ngắn
</option><option value="124092"> Hàn mai hộ thối
</option><option value="124093"> Long văn trường kiếm
</option><option value="124094"> Long văn bào
</option><option value="124095"> Long văn hộ thối
</option><option value="124096"> Long văn eo rơi
</option><option value="124097"> Long văn dây chuyền
</option><option value="124098"> Truy nguyệt nỏ
</option><option value="124099"> Truy nguyệt phục
</option><option value="124100"> Truy nguyệt hộ thối
</option><option value="124101"> Truy nguyệt eo rơi
</option><option value="124102"> Truy nguyệt dây chuyền
</option><option value="124103"> Vảy rồng chủy thủ
</option><option value="124104"> Vảy rồng áo ngắn
</option><option value="124105"> Vảy rồng hộ thối
</option><option value="124106"> Vảy rồng eo rơi
</option><option value="124107"> Vảy rồng dây chuyền
</option><option value="124108"> Hành giả côn
</option><option value="124109"> Hành giả đoản đả
</option><option value="124110"> Hành giả hộ thối
</option><option value="124111"> Hành giả eo rơi
</option><option value="124112"> Hành giả dây chuyền
</option><option value="124113"> Giương văn đoản kiếm
</option><option value="124114"> Giương văn sa y
</option><option value="124115"> Giương văn váy ngắn
</option><option value="124116"> Giương văn eo rơi
</option><option value="124117"> Giương văn dây chuyền
</option><option value="124118"> Trúc tương phi địch
</option><option value="124119"> Tương phi áo đuôi ngắn
</option><option value="124120"> Tương phi hộ thối
</option><option value="124121"> Tương phi eo rơi
</option><option value="124122"> Tương phi dây chuyền
</option><option value="124123"> Huyết Sát bào
</option><option value="124124"> Huyết Sát hộ thối
</option><option value="124125"> Huyết Mãng bào
</option><option value="124126"> Huyết Mãng hộ thối
</option><option value="124127"> Khổ hạnh áo ngắn
</option><option value="124128"> Khổ hạnh hộ thối
</option><option value="124129"> Cầm pháp nạp áo
</option><option value="124130"> Cầm pháp hộ thối
</option><option value="124131"> Bách hoa ô bày
</option><option value="124132"> Bách hoa hộ thối
</option><option value="125001"> Cự Khuyết Kiếm
</option><option value="125002"> Đại Hoàng nỏ
</option><option value="125003"> Thanh vừa
</option><option value="125004"> Đuôi chuột côn
</option><option value="125005"> Hàn quang kiếm
</option><option value="125006"> Hàn quang kiếm
</option><option value="125007"> Bạch ngọc ống sáo
</option><option value="125008"> Bạch ngọc ống sáo
</option><option value="125009"> Gấm hoa bào phục
</option><option value="125010"> Gấm hoa hộ thối
</option><option value="125011"> Hạo nhiên khăn ( Vật )
</option><option value="125012"> Hạo nhiên khăn ( Pháp )
</option><option value="125013"> Gấm hoa giày
</option><option value="125014"> Phỉ thúy ban chỉ ( Vật )
</option><option value="125015"> Phỉ thúy ban chỉ ( Pháp )
</option><option value="125016"> Phỉ thúy eo rơi ( Vật )
</option><option value="125017"> Phỉ thúy eo rơi ( Pháp )
</option><option value="125018"> Dây chuyền phỉ thúy
</option><option value="125019"> Cự Khuyết Kiếm
</option><option value="125020"> Đại Hoàng nỏ
</option><option value="125021"> Thanh vừa
</option><option value="125022"> Đuôi chuột côn
</option><option value="125023"> Hàn quang kiếm
</option><option value="125024"> Hàn quang kiếm
</option><option value="125025"> Bạch ngọc ống sáo
</option><option value="125026"> Bạch ngọc ống sáo
</option><option value="125027"> Gấm hoa bào phục
</option><option value="125028"> Gấm hoa hộ thối
</option><option value="125029"> Hạo nhiên khăn ( Vật )
</option><option value="125030"> Hạo nhiên khăn ( Pháp )
</option><option value="125031"> Gấm hoa giày
</option><option value="125032"> Phỉ thúy ban chỉ ( Vật )
</option><option value="125033"> Phỉ thúy ban chỉ ( Pháp )
</option><option value="125034"> Phỉ thúy eo rơi ( Vật )
</option><option value="125035"> Phỉ thúy eo rơi ( Pháp )
</option><option value="125036"> Dây chuyền phỉ thúy
</option><option value="125037"> Cự Khuyết Kiếm
</option><option value="125038"> Đại Hoàng nỏ
</option><option value="125039"> Thanh vừa
</option><option value="125040"> Đuôi chuột côn
</option><option value="125041"> Hàn quang kiếm
</option><option value="125042"> Hàn quang kiếm
</option><option value="125043"> Bạch ngọc ống sáo
</option><option value="125044"> Bạch ngọc ống sáo
</option><option value="125045"> Trăm tích cẩm y
</option><option value="125046"> Trăm tích hộ thối
</option><option value="125047"> Hạo nhiên khăn ( Vật )
</option><option value="125048"> Hạo nhiên khăn ( Pháp )
</option><option value="125049"> Trăm tích hộ thủ
</option><option value="125050"> Phỉ thúy ban chỉ ( Vật )
</option><option value="125051"> Phỉ thúy ban chỉ ( Pháp )
</option><option value="125052"> Phỉ thúy eo rơi ( Vật )
</option><option value="125053"> Phỉ thúy eo rơi ( Pháp )
</option><option value="125054"> Dây chuyền phỉ thúy
</option><option value="125055"> Long Uyên kiếm
</option><option value="125056"> Nằm nỏ
</option><option value="125057"> Sừng dê chủy thủ
</option><option value="125058"> Lưu kim côn
</option><option value="125059"> Trăm tích đoản kiếm
</option><option value="125060"> Trăm tích đoản kiếm
</option><option value="125061"> Bạch ngân sáo ngắn
</option><option value="125062"> Bạch ngân sáo ngắn
</option><option value="125063"> Gấm hoa bào phục
</option><option value="125064"> Gấm hoa hộ thối
</option><option value="125065"> Lôi khăn ( Vật )
</option><option value="125066"> Lôi khăn ( Pháp )
</option><option value="125067"> Gấm hoa giày
</option><option value="125068"> Huyết ngọc ban chỉ ( Vật )
</option><option value="125069"> Huyết ngọc ban chỉ ( Pháp )
</option><option value="125070"> Huyết ngọc eo rơi ( Vật )
</option><option value="125071"> Huyết ngọc eo rơi ( Pháp )
</option><option value="125072"> Huyết ngọc dây chuyền
</option><option value="125073"> Long Uyên kiếm
</option><option value="125074"> Nằm nỏ
</option><option value="125075"> Sừng dê chủy thủ
</option><option value="125076"> Lưu kim côn
</option><option value="125077"> Trăm tích đoản kiếm
</option><option value="125078"> Trăm tích đoản kiếm
</option><option value="125079"> Bạch ngân sáo ngắn
</option><option value="125080"> Bạch ngân sáo ngắn
</option><option value="125081"> Gấm hoa bào phục
</option><option value="125082"> Gấm hoa hộ thối
</option><option value="125083"> Lôi khăn ( Vật )
</option><option value="125084"> Lôi khăn ( Pháp )
</option><option value="125085"> Gấm hoa giày
</option><option value="125086"> Huyết ngọc ban chỉ ( Vật )
</option><option value="125087"> Huyết ngọc ban chỉ ( Pháp )
</option><option value="125088"> Huyết ngọc eo rơi ( Vật )
</option><option value="125089"> Huyết ngọc eo rơi ( Pháp )
</option><option value="125090"> Huyết ngọc dây chuyền
</option><option value="125091"> Long văn bào
</option><option value="125092"> Long văn hộ thối
</option><option value="125093"> Long văn giày
</option><option value="125094"> Long văn ban chỉ
</option><option value="125095"> Côn Ngô Kiếm
</option><option value="125096"> Côn Ngô bào
</option><option value="125097"> Côn Ngô hộ thối
</option><option value="125098"> Côn Ngô eo rơi
</option><option value="125099"> Côn Ngô dây chuyền
</option><option value="125100"> Mặt trời lặn nỏ
</option><option value="125101"> Mặt trời lặn áo ngắn
</option><option value="125102"> Mặt trời lặn hộ thối
</option><option value="125103"> Mặt trời lặn eo rơi
</option><option value="125104"> Mặt trời lặn dây chuyền
</option><option value="125105"> Hoa mai chủy thủ
</option><option value="125106"> Hoa mai áo ngắn
</option><option value="125107"> Hoa mai hộ thối
</option><option value="125108"> Hoa mai eo rơi
</option><option value="125109"> Hoa mai dây chuyền
</option><option value="125110"> Bàn Long côn
</option><option value="125111"> Bàn Long nạp áo
</option><option value="125112"> Bàn Long hộ thối
</option><option value="125113"> Bàn Long eo rơi
</option><option value="125114"> Bàn Long dây chuyền
</option><option value="125115"> Xích Hà kiếm
</option><option value="125116"> Xích Hà pháp y
</option><option value="125117"> Xích Hà váy ngắn
</option><option value="125118"> Xích Hà eo rơi
</option><option value="125119"> Xích Hà dây chuyền
</option><option value="125120"> Nghe sênh
</option><option value="125121"> Nghe sênh ô bày
</option><option value="125122"> Nghe sênh váy xếp nếp
</option><option value="125123"> Nghe sênh eo rơi
</option><option value="125124"> Nghe sênh dây chuyền
</option><option value="125125"> Sương hoa mũ túi
</option><option value="125126"> Sương hoa giày
</option><option value="125127"> Sương hoa ban chỉ
</option><option value="125128"> Sương hoa eo rơi
</option><option value="125129"> Sương hoa dây chuyền
</option><option value="125130"> Lưu tinh mũ túi
</option><option value="125131"> Lưu tinh giày
</option><option value="125132"> Lưu tinh ban chỉ
</option><option value="125133"> Lưu tinh eo rơi
</option><option value="125134"> Lưu tinh dây chuyền
</option><option value="125135"> Ẩn diệu mũ túi
</option><option value="125136"> Ẩn diệu giày
</option><option value="125137"> Ẩn diệu ban chỉ
</option><option value="125138"> Ẩn diệu eo rơi
</option><option value="125139"> Ẩn diệu dây chuyền
</option><option value="125140"> Diệu dương Bì Lô mũ
</option><option value="125141"> Diệu dương giày
</option><option value="125142"> Diệu dương ban chỉ
</option><option value="125143"> Diệu dương eo rơi
</option><option value="125144"> Diệu dương dây chuyền
</option><option value="125145"> Thất tinh Bì Lô mũ
</option><option value="125146"> Thất tinh giày
</option><option value="125147"> Thất tinh ban chỉ
</option><option value="125148"> Thất tinh eo rơi
</option><option value="125149"> Thất tinh dây chuyền
</option><option value="125150"> Đan Phượng ngân hoa chải
</option><option value="125151"> Đan Phượng giày
</option><option value="125152"> Đan Phượng ban chỉ
</option><option value="125153"> Đan Phượng eo rơi
</option><option value="125154"> Đan Phượng dây chuyền
</option><option value="125155"> Xạ Nhật áo ngắn
</option><option value="125156"> Xạ Nhật hộ thối
</option><option value="125157"> Xạ Nhật giày
</option><option value="125158"> Xạ Nhật ban chỉ
</option><option value="125159"> Ánh trăng áo ngắn
</option><option value="125160"> Ánh trăng hộ thối
</option><option value="125161"> Ánh trăng giày
</option><option value="125162"> Ánh trăng ban chỉ
</option><option value="125163"> Tế thế nạp áo
</option><option value="125164"> Tế thế hộ thối
</option><option value="125165"> Tế thế giày
</option><option value="125166"> Tế thế ban chỉ
</option><option value="125167"> Phổ độ pháp y
</option><option value="125168"> Phổ độ váy ngắn
</option><option value="125169"> Phổ độ giày
</option><option value="125170"> Phổ độ ban chỉ
</option><option value="125171"> Phượng hà ô bày
</option><option value="125172"> Phượng hà váy xếp nếp
</option><option value="125173"> Phượng hà giày
</option><option value="125174"> Phượng hà ban chỉ
</option><option value="126001"> Từng ngày kiếm
</option><option value="126002"> Lưu huỳnh nỏ
</option><option value="126003"> Kinh bụi lưỡi đao
</option><option value="126004"> Trấn sơn côn
</option><option value="126005"> Nguyệt Ảnh kiếm
</option><option value="126006"> Nguyệt Ảnh kiếm
</option><option value="126007"> Mực đàn địch
</option><option value="126008"> Mực đàn địch
</option><option value="126009"> Lụa mỏng trường bào
</option><option value="126010"> Lụa mỏng hộ thối
</option><option value="126011"> Danh sĩ khăn trùm đầu ( Vật )
</option><option value="126012"> Danh sĩ khăn trùm đầu ( Pháp )
</option><option value="126013"> Lụa mỏng giày
</option><option value="126014"> Thanh phách chiếc nhẫn ( Vật )
</option><option value="126015"> Thanh phách chiếc nhẫn ( Pháp )
</option><option value="126016"> Thanh phách eo rơi ( Vật )
</option><option value="126017"> Thanh phách eo rơi ( Pháp )
</option><option value="126018"> Thanh phách dây chuyền
</option><option value="126019"> Từng ngày kiếm
</option><option value="126020"> Lưu huỳnh nỏ
</option><option value="126021"> Kinh bụi lưỡi đao
</option><option value="126022"> Trấn sơn côn
</option><option value="126023"> Nguyệt Ảnh kiếm
</option><option value="126024"> Nguyệt Ảnh kiếm
</option><option value="126025"> Mực đàn địch
</option><option value="126026"> Mực đàn địch
</option><option value="126027"> Lụa mỏng trường bào
</option><option value="126028"> Lụa mỏng hộ thối
</option><option value="126029"> Danh sĩ khăn trùm đầu ( Vật )
</option><option value="126030"> Danh sĩ khăn trùm đầu ( Pháp )
</option><option value="126031"> Lụa mỏng giày
</option><option value="126032"> Thanh phách chiếc nhẫn ( Vật )
</option><option value="126033"> Thanh phách chiếc nhẫn ( Pháp )
</option><option value="126034"> Thanh phách eo rơi ( Vật )
</option><option value="126035"> Thanh phách eo rơi ( Pháp )
</option><option value="126036"> Thanh phách dây chuyền
</option><option value="126037"> Từng ngày kiếm
</option><option value="126038"> Lưu huỳnh nỏ
</option><option value="126039"> Kinh bụi lưỡi đao
</option><option value="126040"> Trấn sơn côn
</option><option value="126041"> Nguyệt Ảnh kiếm
</option><option value="126042"> Nguyệt Ảnh kiếm
</option><option value="126043"> Mực đàn địch
</option><option value="126044"> Mực đàn địch
</option><option value="126045"> Lụa mỏng trường bào
</option><option value="126046"> Lụa mỏng hộ thối
</option><option value="126047"> Danh sĩ khăn trùm đầu ( Vật )
</option><option value="126048"> Danh sĩ khăn trùm đầu ( Pháp )
</option><option value="126049"> Lụa mỏng giày
</option><option value="126050"> Thanh phách chiếc nhẫn ( Vật )
</option><option value="126051"> Thanh phách chiếc nhẫn ( Pháp )
</option><option value="126052"> Thanh phách eo rơi ( Vật )
</option><option value="126053"> Thanh phách eo rơi ( Pháp )
</option><option value="126054"> Thanh phách dây chuyền
</option><option value="126055"> Thuần Quân kiếm
</option><option value="126056"> Thiên Cơ nỏ
</option><option value="126057"> Trục phong nhận
</option><option value="126058"> Bàn Long côn
</option><option value="126059"> Tuyệt phong kiếm
</option><option value="126060"> Tuyệt phong kiếm
</option><option value="126061"> Phi ly địch
</option><option value="126062"> Phi ly địch
</option><option value="126063"> Hoa áo sợi
</option><option value="126064"> Hoa tia hộ thối
</option><option value="126065"> Tán bụi mũ ( Vật )
</option><option value="126066"> Tán bụi mũ ( Pháp )
</option><option value="126067"> Hoa tia giày
</option><option value="126068"> Không lo chiếc nhẫn ( Vật )
</option><option value="126069"> Không lo chiếc nhẫn ( Pháp )
</option><option value="126070"> Không lo eo rơi ( Vật )
</option><option value="126071"> Không lo eo rơi ( Pháp )
</option><option value="126072"> Không lo dây chuyền
</option><option value="126073"> Thuần Quân kiếm
</option><option value="126074"> Thiên Cơ nỏ
</option><option value="126075"> Trục phong nhận
</option><option value="126076"> Bàn Long côn
</option><option value="126077"> Tuyệt phong kiếm
</option><option value="126078"> Tuyệt phong kiếm
</option><option value="126079"> Phi ly địch
</option><option value="126080"> Phi ly địch
</option><option value="126081"> Hoa áo sợi
</option><option value="126082"> Hoa tia hộ thối
</option><option value="126083"> Tán bụi mũ ( Vật )
</option><option value="126084"> Tán bụi mũ ( Pháp )
</option><option value="126085"> Hoa tia giày
</option><option value="126086"> Không lo chiếc nhẫn ( Vật )
</option><option value="126087"> Không lo chiếc nhẫn ( Pháp )
</option><option value="126088"> Không lo eo rơi ( Vật )
</option><option value="126089"> Không lo eo rơi ( Pháp )
</option><option value="126090"> Không lo dây chuyền
</option><option value="126091"> Kỳ Lân bào
</option><option value="126092"> Kỳ Lân hộ thối
</option><option value="126093"> Kỳ Lân giày
</option><option value="126094"> Kỳ Lân chiếc nhẫn
</option><option value="126095"> Xích Tiêu Kiếm
</option><option value="126096"> Xích Tiêu trường bào
</option><option value="126097"> Xích Tiêu hộ thối
</option><option value="126098"> Xích Tiêu eo rơi
</option><option value="126099"> Xích Tiêu dây chuyền
</option><option value="126100"> Chấn thiên nỏ
</option><option value="126101"> Chấn thiên khải
</option><option value="126102"> Chấn thiên hộ thối
</option><option value="126103"> Chấn thiên eo rơi
</option><option value="126104"> Chấn thiên dây chuyền
</option><option value="126105"> Côn Luân lưỡi đao
</option><option value="126106"> Côn Luân dài phục
</option><option value="126107"> Côn Luân hộ thối
</option><option value="126108"> Côn Luân eo rơi
</option><option value="126109"> Côn Luân dây chuyền
</option><option value="126110"> Đông Hoàng pháp côn
</option><option value="126111"> Đông Hoàng bảo y
</option><option value="126112"> Đông Hoàng hộ thối
</option><option value="126113"> Đông Hoàng eo rơi
</option><option value="126114"> Đông Hoàng dây chuyền
</option><option value="126115"> Thần Vũ
</option><option value="126116"> Thần Vũ váy lụa
</option><option value="126117"> Thần Vũ hộ thối
</option><option value="126118"> Thần Vũ eo rơi
</option><option value="126119"> Thần Vũ dây chuyền
</option><option value="126120"> Cổ Linh Vu địch
</option><option value="126121"> Cổ linh áo ngắn
</option><option value="126122"> Cổ linh hộ thối
</option><option value="126123"> Cổ linh eo rơi
</option><option value="126124"> Cổ linh dây chuyền
</option><option value="126125"> Kim Hà túi
</option><option value="126126"> Kim Hà giày
</option><option value="126127"> Kim Hà chiếc nhẫn
</option><option value="126128"> Kim Hà eo rơi
</option><option value="126129"> Kim Hà dây chuyền
</option><option value="126130"> Tử hoàng nón trụ
</option><option value="126131"> Tử hoàng giày
</option><option value="126132"> Tử hoàng chiếc nhẫn
</option><option value="126133"> Tử hoàng eo rơi
</option><option value="126134"> Tử hoàng dây chuyền
</option><option value="126135"> Rơi tiêu thao khăn
</option><option value="126136"> Rơi tiêu giày
</option><option value="126137"> Rơi tiêu chiếc nhẫn
</option><option value="126138"> Rơi tiêu eo rơi
</option><option value="126139"> Rơi tiêu dây chuyền
</option><option value="126140"> Luân hồi mũ rộng vành
</option><option value="126141"> Luân hồi giày
</option><option value="126142"> Luân hồi chiếc nhẫn
</option><option value="126143"> Luân hồi eo rơi
</option><option value="126144"> Luân hồi dây chuyền
</option><option value="126145"> Giáng Châu quan
</option><option value="126146"> Giáng Châu giày
</option><option value="126147"> Giáng Châu chiếc nhẫn
</option><option value="126148"> Giáng Châu eo rơi
</option><option value="126149"> Giáng Châu dây chuyền
</option><option value="126150"> Hoán âm ngân mũ
</option><option value="126151"> Hoán âm giày
</option><option value="126152"> Hoán âm chiếc nhẫn
</option><option value="126153"> Hoán âm eo rơi
</option><option value="126154"> Hoán âm dây chuyền
</option><option value="126155"> Tất Phương nhuyễn giáp
</option><option value="126156"> Tất Phương hộ thối
</option><option value="126157"> Tất Phương giày
</option><option value="126158"> Tất Phương chiếc nhẫn
</option><option value="126159"> Bạch Trạch dài phục
</option><option value="126160"> Bạch Trạch hộ thối
</option><option value="126161"> Bạch Trạch giày
</option><option value="126162"> Bạch Trạch chiếc nhẫn
</option><option value="126163"> Kim Bằng bảo y
</option><option value="126164"> Kim Bằng hộ thối
</option><option value="126165"> Kim Bằng giày
</option><option value="126166"> Kim Bằng chiếc nhẫn
</option><option value="126167"> Thanh Loan váy lụa
</option><option value="126168"> Thanh Loan hộ thối
</option><option value="126169"> Thanh Loan giày
</option><option value="126170"> Thanh Loan chiếc nhẫn
</option><option value="126171"> Băng tằm áo ngắn
</option><option value="126172"> Băng tằm hộ thối
</option><option value="126173"> Băng tằm giày
</option><option value="126174"> Băng tằm chiếc nhẫn
</option><option value="127001"> Thừa Ảnh Kiếm
</option><option value="127002"> Nam Hoa nỏ
</option><option value="127003"> Bích quang lưỡi đao
</option><option value="127004"> Thanh minh côn
</option><option value="127005"> Bích quang kiếm
</option><option value="127006"> Bích quang kiếm
</option><option value="127007"> Linh hơi thở sáo ngọc
</option><option value="127008"> Linh hơi thở sáo ngọc
</option><option value="127009"> Lăng la bào
</option><option value="127010"> Lăng la hộ thối
</option><option value="127011"> Ti tán rừng ( Vật )
</option><option value="127012"> Ti tán rừng ( Pháp )
</option><option value="127013"> Lăng la giày
</option><option value="127014"> Diệu Tinh chiếc nhẫn ( Vật )
</option><option value="127015"> Diệu Tinh chiếc nhẫn ( Pháp )
</option><option value="127016"> Diệu Tinh eo rơi ( Vật )
</option><option value="127017"> Diệu Tinh eo rơi ( Pháp )
</option><option value="127018"> Diệu Tinh dây chuyền
</option><option value="127019"> Thừa Ảnh Kiếm
</option><option value="127020"> Nam Hoa nỏ
</option><option value="127021"> Bích quang lưỡi đao
</option><option value="127022"> Thanh minh côn
</option><option value="127023"> Bích quang kiếm
</option><option value="127024"> Bích quang kiếm
</option><option value="127025"> Linh hơi thở sáo ngọc
</option><option value="127026"> Linh hơi thở sáo ngọc
</option><option value="127027"> Lăng la bào
</option><option value="127028"> Lăng la hộ thối
</option><option value="127029"> Ti tán rừng ( Vật )
</option><option value="127030"> Ti tán rừng ( Pháp )
</option><option value="127031"> Lăng la giày
</option><option value="127032"> Diệu Tinh chiếc nhẫn ( Vật )
</option><option value="127033"> Diệu Tinh chiếc nhẫn ( Pháp )
</option><option value="127034"> Diệu Tinh eo rơi ( Vật )
</option><option value="127035"> Diệu Tinh eo rơi ( Pháp )
</option><option value="127036"> Diệu Tinh dây chuyền
</option><option value="127037"> Thừa Ảnh Kiếm
</option><option value="127038"> Nam Hoa nỏ
</option><option value="127039"> Bích quang lưỡi đao
</option><option value="127040"> Thanh minh côn
</option><option value="127041"> Bích quang kiếm
</option><option value="127042"> Bích quang kiếm
</option><option value="127043"> Linh hơi thở sáo ngọc
</option><option value="127044"> Linh hơi thở sáo ngọc
</option><option value="127045"> Lăng la bào
</option><option value="127046"> Lăng la hộ thối
</option><option value="127047"> Ti tán rừng ( Vật )
</option><option value="127048"> Ti tán rừng ( Pháp )
</option><option value="127049"> Lăng la giày
</option><option value="127050"> Diệu Tinh chiếc nhẫn ( Vật )
</option><option value="127051"> Diệu Tinh chiếc nhẫn ( Pháp )
</option><option value="127052"> Diệu Tinh eo rơi ( Vật )
</option><option value="127053"> Diệu Tinh eo rơi ( Pháp )
</option><option value="127054"> Diệu Tinh dây chuyền
</option><option value="127055"> Phạt ác kiếm
</option><option value="127056"> Tinh mây nỏ
</option><option value="127057"> Khám cách lưỡi đao
</option><option value="127058"> Nằm tâm côn
</option><option value="127059"> Lưu cầu vồng kiếm
</option><option value="127060"> Lưu cầu vồng kiếm
</option><option value="127061"> Linh lung sáo ngắn
</option><option value="127062"> Linh lung sáo ngắn
</option><option value="127063"> Thanh Sương bào
</option><option value="127064"> Thanh Sương hộ thối
</option><option value="127065"> Chân Vũ quan ( Vật )
</option><option value="127066"> Chân Vũ quan ( Pháp )
</option><option value="127067"> Thanh Sương giày
</option><option value="127068"> Công khanh chiếc nhẫn ( Vật )
</option><option value="127069"> Công khanh chiếc nhẫn ( Pháp )
</option><option value="127070"> Công khanh eo rơi ( Vật )
</option><option value="127071"> Công khanh eo rơi ( Pháp )
</option><option value="127072"> Công khanh dây chuyền
</option><option value="127073"> Phạt ác kiếm
</option><option value="127074"> Tinh mây nỏ
</option><option value="127075"> Khám cách lưỡi đao
</option><option value="127076"> Nằm tâm côn
</option><option value="127077"> Lưu cầu vồng kiếm
</option><option value="127078"> Lưu cầu vồng kiếm
</option><option value="127079"> Linh lung sáo ngắn
</option><option value="127080"> Linh lung sáo ngắn
</option><option value="127081"> Thanh Sương bào
</option><option value="127082"> Thanh Sương hộ thối
</option><option value="127083"> Chân Vũ quan ( Vật )
</option><option value="127084"> Chân Vũ quan ( Pháp )
</option><option value="127085"> Thanh Sương giày
</option><option value="127086"> Công khanh chiếc nhẫn ( Vật )
</option><option value="127087"> Công khanh chiếc nhẫn ( Pháp )
</option><option value="127088"> Công khanh eo rơi ( Vật )
</option><option value="127089"> Công khanh eo rơi ( Pháp )
</option><option value="127090"> Công khanh dây chuyền
</option><option value="127091"> Lạnh khe bào
</option><option value="127092"> Lạnh khe hộ thối
</option><option value="127093"> Lạnh khe giày
</option><option value="127094"> Lạnh khe chiếc nhẫn
</option><option value="127095"> Thái A kiếm
</option><option value="127096"> Thái A bào
</option><option value="127097"> Thái A hộ thối
</option><option value="127098"> Thái A eo rơi
</option><option value="127099"> Thái A dây chuyền
</option><option value="127100"> Lạc Thần nỏ
</option><option value="127101"> Lạc Thần giáp
</option><option value="127102"> Lạc Thần hộ thối
</option><option value="127103"> Lạc Thần eo rơi
</option><option value="127104"> Lạc Thần dây chuyền
</option><option value="127105"> Sơn hà lưỡi đao
</option><option value="127106"> Sơn hà dài phục
</option><option value="127107"> Sơn hà hộ thối
</option><option value="127108"> Sơn hà eo rơi
</option><option value="127109"> Sơn hà dây chuyền
</option><option value="127110"> Ma Ha pháp côn
</option><option value="127111"> Ma Ha bảo y
</option><option value="127112"> Ma Ha hộ thối
</option><option value="127113"> Ma Ha eo rơi
</option><option value="127114"> Ma Ha dây chuyền
</option><option value="127115"> Ỷ Thiên Kiếm
</option><option value="127116"> Ỷ Thiên váy lụa
</option><option value="127117"> Ỷ Thiên hộ thối
</option><option value="127118"> Ỷ Thiên eo rơi
</option><option value="127119"> Ỷ Thiên dây chuyền
</option><option value="127120"> Lông mày núi xương địch
</option><option value="127121"> Lông mày núi áo ngắn
</option><option value="127122"> Lông mày núi hộ thối
</option><option value="127123"> Lông mày sườn núi rơi
</option><option value="127124"> Lông mày núi dây chuyền
</option><option value="127125"> Thiên Xu chi quan
</option><option value="127126"> Thiên Xu giày
</option><option value="127127"> Thiên Xu chiếc nhẫn
</option><option value="127128"> Thiên Xu eo rơi
</option><option value="127129"> Thiên Xu dây chuyền
</option><option value="127130"> Thiên Toàn nón trụ
</option><option value="127131"> Thiên Toàn giày
</option><option value="127132"> Thiên Toàn chiếc nhẫn
</option><option value="127133"> Thiên Toàn eo rơi
</option><option value="127134"> Thiên Toàn dây chuyền
</option><option value="127135"> Thiên Toàn thao khăn
</option><option value="127136"> Thiên Toàn giày
</option><option value="127137"> Thiên Toàn chiếc nhẫn
</option><option value="127138"> Thiên Toàn eo rơi
</option><option value="127139"> Thiên Toàn dây chuyền
</option><option value="127140"> Khai Dương mũ rộng vành
</option><option value="127141"> Khai Dương giày
</option><option value="127142"> Khai Dương chiếc nhẫn
</option><option value="127143"> Khai Dương eo rơi
</option><option value="127144"> Khai Dương dây chuyền
</option><option value="127145"> Ngọc Hành quan
</option><option value="127146"> Ngọc Hành giày
</option><option value="127147"> Ngọc Hành chiếc nhẫn
</option><option value="127148"> Ngọc Hành eo rơi
</option><option value="127149"> Ngọc Hành dây chuyền
</option><option value="127150"> Dao Quang ngân mũ
</option><option value="127151"> Dao Quang giày
</option><option value="127152"> Dao Quang chiếc nhẫn
</option><option value="127153"> Dao Quang eo rơi
</option><option value="127154"> Dao Quang dây chuyền
</option><option value="127155"> Thương linh khải
</option><option value="127156"> Thương linh hộ thối
</option><option value="127157"> Thương linh giày
</option><option value="127158"> Thương linh chiếc nhẫn
</option><option value="127159"> Nhạn cách dài phục
</option><option value="127160"> Nhạn cách hộ thối
</option><option value="127161"> Nhạn cách giày
</option><option value="127162"> Nhạn cách chiếc nhẫn
</option><option value="127163"> Vô tướng bảo y
</option><option value="127164"> Vô tướng hộ thối
</option><option value="127165"> Vô tướng giày
</option><option value="127166"> Vô tướng chiếc nhẫn
</option><option value="127167"> Diệu chỉ váy lụa
</option><option value="127168"> Diệu chỉ hộ thối
</option><option value="127169"> Diệu chỉ giày
</option><option value="127170"> Diệu chỉ chiếc nhẫn
</option><option value="127171"> Tử lạc áo ngắn
</option><option value="127172"> Tử lạc hộ thối
</option><option value="127173"> Tử lạc giày
</option><option value="127174"> Tử lạc chiếc nhẫn
</option><option value="128001"> Ngưng băng kiếm
</option><option value="128002"> Sao băng nỏ
</option><option value="128003"> Nỗi buồn ly biệt đâm
</option><option value="128004"> Cương rồng côn
</option><option value="128005"> Nguyệt diệu kiếm
</option><option value="128006"> Nguyệt diệu kiếm
</option><option value="128007"> Minh đạo địch
</option><option value="128008"> Minh đạo địch
</option><option value="128009"> Thiên Cương áo khoác
</option><option value="128010"> Thiên Cương hộ thối
</option><option value="128011"> Thiên Cương quan ( Vật )
</option><option value="128012"> Thiên Cương quan ( Pháp )
</option><option value="128013"> Thất tinh giày
</option><option value="128014"> Địa Sát giới ( Vật )
</option><option value="128015"> Địa Sát giới ( Pháp )
</option><option value="128016"> Địa Sát vòng ( Vật )
</option><option value="128017"> Địa Sát vòng ( Pháp )
</option><option value="128018"> Địa Sát dây chuyền
</option><option value="128019"> Ngưng băng kiếm
</option><option value="128020"> Sao băng nỏ
</option><option value="128021"> Nỗi buồn ly biệt đâm
</option><option value="128022"> Cương rồng côn
</option><option value="128023"> Nguyệt diệu kiếm
</option><option value="128024"> Nguyệt diệu kiếm
</option><option value="128025"> Minh đạo địch
</option><option value="128026"> Minh đạo địch
</option><option value="128027"> Thiên Cương áo khoác
</option><option value="128028"> Thiên Cương hộ thối
</option><option value="128029"> Thiên Cương quan ( Vật )
</option><option value="128030"> Thiên Cương quan ( Pháp )
</option><option value="128031"> Thất tinh giày
</option><option value="128032"> Địa Sát giới ( Vật )
</option><option value="128033"> Địa Sát giới ( Pháp )
</option><option value="128034"> Địa Sát vòng ( Vật )
</option><option value="128035"> Địa Sát vòng ( Pháp )
</option><option value="128036"> Địa Sát dây chuyền
</option><option value="128037"> Ngưng băng kiếm
</option><option value="128038"> Sao băng nỏ
</option><option value="128039"> Nỗi buồn ly biệt đâm
</option><option value="128040"> Cương rồng côn
</option><option value="128041"> Nguyệt diệu kiếm
</option><option value="128042"> Nguyệt diệu kiếm
</option><option value="128043"> Minh đạo địch
</option><option value="128044"> Minh đạo địch
</option><option value="128045"> Thiên Cương áo khoác
</option><option value="128046"> Thiên Cương hộ thối
</option><option value="128047"> Thiên Cương quan ( Vật )
</option><option value="128048"> Thiên Cương quan ( Pháp )
</option><option value="128049"> Thất tinh giày
</option><option value="128050"> Địa Sát giới ( Vật )
</option><option value="128051"> Địa Sát giới ( Pháp )
</option><option value="128052"> Địa Sát vòng ( Vật )
</option><option value="128053"> Địa Sát vòng ( Pháp )
</option><option value="128054"> Địa Sát dây chuyền
</option><option value="128055"> Ngưng băng kiếm
</option><option value="128056"> Sao băng nỏ
</option><option value="128057"> Nỗi buồn ly biệt đâm
</option><option value="128058"> Cương rồng côn
</option><option value="128059"> Nguyệt diệu kiếm
</option><option value="128060"> Nguyệt diệu kiếm
</option><option value="128061"> Minh đạo địch
</option><option value="128062"> Minh đạo địch
</option><option value="128063"> Thiên Cương áo khoác
</option><option value="128064"> Thiên Cương hộ thối
</option><option value="128065"> Thiên Cương quan ( Vật )
</option><option value="128066"> Thiên Cương quan ( Pháp )
</option><option value="128067"> Thất tinh giày
</option><option value="128068"> Địa Sát giới ( Vật )
</option><option value="128069"> Địa Sát giới ( Pháp )
</option><option value="128070"> Địa Sát vòng ( Vật )
</option><option value="128071"> Địa Sát vòng ( Pháp )
</option><option value="128072"> Địa Sát dây chuyền
</option><option value="128073"> Ngưng băng kiếm
</option><option value="128074"> Sao băng nỏ
</option><option value="128075"> Nỗi buồn ly biệt đâm
</option><option value="128076"> Cương rồng côn
</option><option value="128077"> Nguyệt diệu kiếm
</option><option value="128078"> Nguyệt diệu kiếm
</option><option value="128079"> Minh đạo địch
</option><option value="128080"> Minh đạo địch
</option><option value="128081"> Thiên Cương áo khoác
</option><option value="128082"> Thiên Cương hộ thối
</option><option value="128083"> Thiên Cương quan ( Vật )
</option><option value="128084"> Thiên Cương quan ( Pháp )
</option><option value="128085"> Thất tinh giày
</option><option value="128086"> Địa Sát giới ( Vật )
</option><option value="128087"> Địa Sát giới ( Pháp )
</option><option value="128088"> Địa Sát vòng ( Vật )
</option><option value="128089"> Địa Sát vòng ( Pháp )
</option><option value="128090"> Địa Sát dây chuyền
</option><option value="128091"> Sương hàn trường bào
</option><option value="128092"> Sương hàn quần dài
</option><option value="128093"> Sương hàn giày
</option><option value="128094"> Sương hàn giới
</option><option value="128095"> Thái Ất phá khuyết
</option><option value="128096"> Thái Ất chiến bào
</option><option value="128097"> Thái Ất buộc quần
</option><option value="128098"> Thái Ất vòng
</option><option value="128099"> Thái Ất thật liên
</option><option value="128100"> Sáo trang vũ khí
</option><option value="128101"> Sáo trang quần áo
</option><option value="128102"> Sáo trang quần
</option><option value="128103"> Sáo trang vòng tai
</option><option value="128104"> Sáo trang dây chuyền
</option><option value="128105"> Sáo trang vũ khí
</option><option value="128106"> Sáo trang quần áo
</option><option value="128107"> Sáo trang quần
</option><option value="128108"> Sáo trang vòng tai
</option><option value="128109"> Sáo trang dây chuyền
</option><option value="128110"> Sáo trang vũ khí
</option><option value="128111"> Sáo trang quần áo
</option><option value="128112"> Sáo trang quần
</option><option value="128113"> Sáo trang vòng tai
</option><option value="128114"> Sáo trang dây chuyền
</option><option value="128115"> Sáo trang vũ khí
</option><option value="128116"> Sáo trang quần áo
</option><option value="128117"> Sáo trang quần
</option><option value="128118"> Sáo trang vòng tai
</option><option value="128119"> Sáo trang dây chuyền
</option><option value="128120"> Sáo trang vũ khí
</option><option value="128121"> Sáo trang quần áo
</option><option value="128122"> Sáo trang quần
</option><option value="128123"> Sáo trang vòng tai
</option><option value="128124"> Sáo trang dây chuyền
</option><option value="128125"> Sáo trang mũ giáp
</option><option value="128126"> Sáo trang giày
</option><option value="128127"> Sáo trang chiếc nhẫn
</option><option value="128128"> Sáo trang vòng tai
</option><option value="128129"> Sáo trang dây chuyền
</option><option value="128130"> Sáo trang mũ giáp
</option><option value="128131"> Sáo trang giày
</option><option value="128132"> Sáo trang chiếc nhẫn
</option><option value="128133"> Sáo trang vòng tai
</option><option value="128134"> Sáo trang dây chuyền
</option><option value="128135"> Sáo trang mũ giáp
</option><option value="128136"> Sáo trang giày
</option><option value="128137"> Sáo trang chiếc nhẫn
</option><option value="128138"> Sáo trang vòng tai
</option><option value="128139"> Sáo trang dây chuyền
</option><option value="128140"> Sáo trang mũ giáp
</option><option value="128141"> Sáo trang giày
</option><option value="128142"> Sáo trang chiếc nhẫn
</option><option value="128143"> Sáo trang vòng tai
</option><option value="128144"> Sáo trang dây chuyền
</option><option value="128145"> Sáo trang mũ giáp
</option><option value="128146"> Sáo trang giày
</option><option value="128147"> Sáo trang chiếc nhẫn
</option><option value="128148"> Sáo trang vòng tai
</option><option value="128149"> Sáo trang dây chuyền
</option><option value="128150"> Sáo trang mũ giáp
</option><option value="128151"> Sáo trang giày
</option><option value="128152"> Sáo trang chiếc nhẫn
</option><option value="128153"> Sáo trang vòng tai
</option><option value="128154"> Sáo trang dây chuyền
</option><option value="128155"> Sáo trang - Quần áo
</option><option value="128156"> Sáo trang - Hộ thối
</option><option value="128157"> Sáo trang - Giày
</option><option value="128158"> Sáo trang - Chiếc nhẫn
</option><option value="128159"> Sáo trang - Quần áo
</option><option value="128160"> Sáo trang - Hộ thối
</option><option value="128161"> Sáo trang - Giày
</option><option value="128162"> Sáo trang - Chiếc nhẫn
</option><option value="128163"> Sáo trang - Quần áo
</option><option value="128164"> Sáo trang - Hộ thối
</option><option value="128165"> Sáo trang - Giày
</option><option value="128166"> Sáo trang - Chiếc nhẫn
</option><option value="128167"> Sáo trang - Quần áo
</option><option value="128168"> Sáo trang - Hộ thối
</option><option value="128169"> Sáo trang - Giày
</option><option value="128170"> Sáo trang - Chiếc nhẫn
</option><option value="128171"> Sáo trang - Quần áo
</option><option value="128172"> Sáo trang - Hộ thối
</option><option value="128173"> Sáo trang - Giày
</option><option value="128174"> Sáo trang - Chiếc nhẫn
</option><option value="129001"> Vũ khí 1
</option><option value="129002"> Vũ khí 2
</option><option value="129003"> Vũ khí 3
</option><option value="129004"> Vũ khí 4
</option><option value="129005"> Vũ khí 5-1
</option><option value="129006"> Vũ khí 5-2
</option><option value="129007"> Vũ khí 6-1
</option><option value="129008"> Vũ khí 6-2
</option><option value="129009"> Quần áo
</option><option value="129010"> Hộ thối
</option><option value="129011"> Mũ giáp ( Vật )
</option><option value="129012"> Mũ giáp ( Pháp )
</option><option value="129013"> Giày
</option><option value="129014"> Chiếc nhẫn ( Vật )
</option><option value="129015"> Chiếc nhẫn ( Pháp )
</option><option value="129016"> Vòng tai ( Vật )
</option><option value="129017"> Vòng tai ( Pháp )
</option><option value="129018"> Dây chuyền
</option><option value="
