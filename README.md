#jquery.detailclick

##Description
左・中・右クリックのカスタムイベントを追加するjQueryプラグインです。

---
##Required
###jQuery
http://jquery.com/

---
##Usage

###Step01
jquery.js, jquery.detailclick.jsを順番に読み込ませます。

    <script type="text/javascript" src="jquery.js"></script>
    <script type="text/javascript" src="jquery.detail.click.js"></script>

###Step02
clickなどのイベントと同じようにleftClick, rightClick, wheelClickを使用できます。
たとえば、次のように実行することができます。

    // leftClickメソッド
    $(body).leftClick(function(evt) {
      alert("左クリックされました！"); 
    });

    // bindでwheelClickイベントにfuncA登録
    $(body).bind("wheelClick", funcA);

    // unbindでwheelClickイベントからfuncA削除
    $(body).unbind("wheelClick", funcA);

---
##License
Dual licensed under the MIT and GPL licenses.

##Contact
yuqq (yuqq.js@gmail.com)
