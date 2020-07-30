# jackson
forworld
<!DOCTYPE html>
<html lang="vi">
<head>
	<title>ON TAP</title>
	<meta charset="uft-8"/>
	<meta name="descriftion" content="khai báo nội dung cho mô tả">
	<meta name="author" content="Jack Son là tác giả">
	<meta name="keyword" content="khai báo từ khóa để tìm kiếm">
</head>
<body background="" bgcolor="" text="" link="" vlink="" alink="">
	<!--
		- thuộc tính của body
		+ backgroud= link của ảnh, nó sẽ hiển thị nền là ảnh, ảnh k đủ to thì nó sẽ gộp nhiều cái để lấp đầy
		+ bgcolor màu nền,
		nếu chỉ định cả 2 thì ảnh sẽ hiển thị trước rồi mới đến nền
		+ text= xác định màu chữ của văn bản, cả đề mục
		+ link, alink là active link là liên kết đang được kích hoạt, vlink là visited link là lk đã kích hoạt
	-->
	<h1>BÀI HỌC</h1>   <-- tiêu đề có thể chỉ định từ h1 tới h6-->
<hr>

	<strong>in đậm</strong>, <i>in nghiêng</i>, <u>gạch chân</u>, <strike>gạch ngang</strike>, <del>gạch ngang</del>,d<s>gạch ngang</s>,<em>in nghiêng</em>, <b>in đậm</b>, <DFN> đánh dấu đoạn văn bản giữa 2 thẻ là định nghĩa của một từ</DFN>, <big><big>in chữ lớn, có thể lồng nhau</big></big>, <small>in nhỏ, lồng nhau</small>, số dưới<sub>16</sub>, số trên <sup>16</sup>
	<basefont> định font đc dùng hết văn bản nhưng chưa hiểu lắm</basefont>
	<font size="7" color="blue">màu và cỡ chữ</font>> 
	<!-- nếu muốn chỉ định cớ chữ tương đối so với cỡ chữ hiện tại thì chọn size= -2, +3 v.v.v -->
<hr>
 
 <!--  thẻ hr
 	<HR
align = LEFT / CENTER / RIGHT
color = color
noshade k có bóng
size = n
width =  độ dày tính bằng px hoặc % bề rộng của cửa sổ trình duyệt
>

  -->
	<pre>chưa hiểu</pre>

<hr>

	để&ensp;cách 4 khoảng trống 半角空白　はんかくくうはく<
	&lt;mở và đóng ngoặc nhọn&gt;
	&amp; là chữ &


	<quote>
		<p>"trích dẫn</p>
		<cite>JACK SƠN</cite>
	</quote>

<hr>

	<pre>thể hiện những đoạn code trên website</pre>
	<code> code và pre thường dùng để soạn thảo văn bản liên quan tới IT </code>

<hr>

	<p style="color: red; background-color: blue; font-size: 16px;font-family:Arial;text-align:justify;  ">  mỗi thuộc tính cách nhau bằng một dấu chấm phẩy, màu văn bản, căn lề left, center, right,justify 2 bên</p>
	<!-- <span> là thuộc tính lồng trong thẻ p -->
	<p> tạo <span style="color: red;">màu đỏ</span> cho thẻ lồng trong thẻ p </p>

<hr>
	<!-- TẠO NHÓM
	- <ol> là có thứ tự, ul là thêm dấu chấm, thuộc tính type để chỉ định kiểu thứ tự A, a,I, i ,1  
	- thẻ <dir> là thẻ phân cấp. <menu> là thẻ menu
	- reversed là thuộc tính của <li> chỉ thứ tự chạy ngược, start 
	- type= disc tròn đậm; circle vòng tròn  ; square vuông cho <li>

	-->

	<ol>
		<li>項目A
			<ul>
				<li>項目A-a</li>
				<li>項目A-b</li>
				<li>項目A-c</li>
			</ul>
		</li>
		<li>項目B
			<ol reversed="3">
				<li>項目B-c</li>
				<li>項目B-b</li>
				<li>項目B-a</li>
			</ol>
		</li>
		<li>項目C
			<ol>
				<li value="1">項目D-b</li>
				<li value="2">項目D-c</li>
				<li value="4">項目D-e</li>
			</ol>
		</li>
	</ol> 

<hr>

	<!-- danh sách có mô tả dl, dt là phần tử, dd là mô tả-->
    <dl>
		<dt> anh </dt>
			<dd>la ai</dd>
		<dt>anh là Sơn</dt>
			<dd>ừ</dd>
	</dl>

	<hr>

	<!-- thẻ tạo liên kết , _blank là mở trên cửa sổ mới, _sefl là cửa sổ này-->
	<ul>
		<li><a href="1.html" title="VÀO html" target="_blank"> đi tới 1.html </a></li>
		<li><a href="#abc">ĐỌC NỘI DUNG</a></li>
		<!--nó chạy đến phần nội dung đc đánh dấu -->
		<p id="abc"> đây là nội dung</p>
	</ul>	
	<!-- chèn ảnh,  width="5" height="15" border= px là viền ảnh, title= là ghi chữ sẽ hiển thị khi di chuyển chuột vào ảnh-->
	<img src="https://genk.mediacdn.vn/thumb_w/660/2019/10/16/pixel-image-2-15711948680972055689544.jpg" alt="ảnh thôi" title="đây là ảnh">
	 <!-- <img src="C:\Users\ASUS\Pictures\received_2233449803647372.jpeg" -->
	<!-- chèn video -->
	<video width="" height="">
		<source src="đường dẫn video" type="video/mp4">
	</video>

<hr>

	<!-- TẠO BẢNG table
		<caption> tiêu đề của bảng</captiom>
		<TABLE
ALIGN = LEFT / CENTER / RIGHT căn lề cho bảng và nội dung trong ô
VALIGN = TOP / MIDDLE / BOTTOM
BORDER = kích thước đường kẻ chia ô trong bảng, được đo theo px, 0 là 0 xác định lề, giữa các ô trong bảng chỉ có 1 khoảng cách nhỏ để phân biệt. nếu chỉ để border thì auto=1
BORDERCOLOR = cmàu đường kẻ
BORDERCOLORDARK =  màu phía tối và phía sáng cho đường kẻ nổi
BORDERCOLORLIGHT = // //
BACKGROUND = link ảnh nền
BGCOLOR = màu nền
CELLSPACING = spacing khoảng cách giữa các ô 
CELLPADDING = pading khoảng cách giữa nội dung và đường kẻ



	 -->
	<style>
		table {
			border-collapse: collapse;
		}
		td {
			border: 1px dotted gray;
			padding: 10px;
		}
	</style>
</head>
<body>
	<table>
		<tr>
			<td>A1</td>
			<td>B1</td>
			<td>C1</td>
		</tr>
		<tr>
			<td>A2</td>
			<td>B2</td>
			<td>C2</td>
		</tr>
		
	</table>
	<br>
	<table>
		<tr>
			<td rowspan="2">A1+A2</td>
			<td colspan="2">B1+C1</td>
		</tr>
		<tr>
			<td>B2</td>
			<td>C2</td>
		</tr>
	</table>
<hr>

<!-- YẾU TỐ FORM -->

<form action="#" method="GET">

	ID:<input type="text" name="id" value="sugawara"><br>
	 <!-- type =種類,name=urlのパラメーター(thông số),value= -->
	PW:<input type="password" name="pw"><br>
<!-- ZZ入力値は、URLパラメーターとししてwebサーバーへ送信 -->
	<button type="submit">ログイン</button>
<!-- ボタンの種類 -->
<hr>
	<form name="method">
	<textarea name="comment">
hộp comment
	</textarea>
<br>
	<select name="measure">
		<option value="XL" selected>大</option>??
		<option value="L">中</option>
		<option value="M">小</option>
	</select><br>
		<button type="submit">送信</button>
		<button type="reset">リセット</button>
		<button type="submit" name="action" value="delete">削除</button>
		<button type="submit" name="action" value="modify">修正</button>
	<input type="text" name="id" value="user">
<br>

	<input type="radio" name="size" value="L">大
	<input type="radio" name="size" value="M">中
	<input type="radio" name="size" value="S">小
<br>

	<input type="checkbox" name="fruits" value="apple">りんご
	<input type="checkbox" name="fruits" value="orange">みかん
	<input type="checkbox" name="fruits" value="banana">ばなな 

<br>

	<input type="file" name="upload">
	<input type="hidden" name="userid" value="hoge"><br>
	<input type="date" name="birthday" value="1988-04-01">
<br>
	<input type="time" name="start" value="09:20">
<br>
	<input type="number" name="score" value="20">
<br>       
	<input type="range" name="volume" value="80">
</form>
</body>
</html>

	
	</table>
</body>
</html>
