# minnnjiii.github.io
<html>
<head>
    <meta charset="UTF-8">
    <title>project</title>

    <style>
        /* Modify the background color */
        .navbar-custom {
            background-color:  #99ccff;
            background-color: #99ccff;
        }

        .right-box {
            position: absolute;
            top: 20px;
            right: 70px;
        }
    </style>
    <link rel="stylesheet" href="https://cdn.jsdelivr.net/npm/bootstrap@4.6.2/dist/css/bootstrap.min.css" integrity="sha384-xOolHFLEh07PJGoPkLv1IbcEPTNtaed2xpHsD9ESMhqIYd0nLMwNLD69Npy4HI+N" crossorigin="anonymous">
</head>

<body>
    <nav class="navbar navbar-expand-lg navbar-light navbar-custom">
  <a class="navbar-brand" href="#"><img src="/symbol.jpg" alt="" style="width: 60px"></a>
  <button class="navbar-toggler" type="button" data-toggle="collapse" data-target="#navbarNavAltMarkup" aria-controls="navbarNavAltMarkup" aria-expanded="false" aria-label="Toggle navigation">
    <span class="navbar-toggler-icon"></span>
  </button>
  <div class="collapse navbar-collapse" id="navbarNavAltMarkup">
    <div class="navbar-nav">
      <a class="nav-link active" href="#">Home <span class="sr-only">(current)</span></a>
      <a class="nav-link" href="#">시간표</a>
      <a class="nav-link" href="#">학식 메뉴</a>
      <a class="nav-link" href="#">학점 계산기</a>
        <a class="nav-link" href="#">버스 시간표</a>
    </div>
  </div>
</nav>
<script src="https://cdn.jsdelivr.net/npm/jquery@3.5.1/dist/jquery.slim.min.js" integrity="sha384-DfXdz2htPH0lsSSs5nCTpuj/zy4C+OGpamoFVy38MVBnE+IbbVYUew+OrCXaRkfj" crossorigin="anonymous"></script>
<script src="https://cdn.jsdelivr.net/npm/bootstrap@4.6.2/dist/js/bootstrap.bundle.min.js" integrity="sha384-Fy6S3B9q64WdZWQUiU+q4/2Lc9npb8tCaSX9FK7E8HnRr0Jz8D6OP9dO5Vg3Q9ct" crossorigin="anonymous"></script>
</body>
</html>
        <a class="navbar-brand" href="#"><img src="/symbol.jpg" alt="" style="width: 60px"></a>
        <a class="nav-link active right-box" href="#">Log-in</a>
        <button class="navbar-toggler" type="button" data-toggle="collapse" data-target="#navbarNavAltMarkup" aria-controls="navbarNavAltMarkup" aria-expanded="false" aria-label="Toggle navigation">
            <span class="navbar-toggler-icon"></span>
        </button>
        <div class="collapse navbar-collapse" id="navbarNavAltMarkup">
            <div class="navbar-nav">
                <a class="nav-link active" href="#">Home <span class="sr-only">(current)</span></a>
                <a class="nav-link" href="#">시간표</a>
                <a class="nav-link" href="#">학식 메뉴</a>
                <a class="nav-link" href="#">학점 계산기</a>
                <a class="nav-link" href="#">버스 시간표</a>
            </div>
        </div>

    </nav>
    <script src="https://cdn.jsdelivr.net/npm/jquery@3.5.1/dist/jquery.slim.min.js" integrity="sha384-DfXdz2htPH0lsSSs5nCTpuj/zy4C+OGpamoFVy38MVBnE+IbbVYUew+OrCXaRkfj" crossorigin="anonymous"></script>
    <script src="https://cdn.jsdelivr.net/npm/bootstrap@4.6.2/dist/js/bootstrap.bundle.min.js" integrity="sha384-Fy6S3B9q64WdZWQUiU+q4/2Lc9npb8tCaSX9FK7E8HnRr0Jz8D6OP9dO5Vg3Q9ct" crossorigin="anonymous"></script>

    <!-- 나나나나    -->
    <table summary = "테이블" style = "width:300px; height:250px;"> 
        <caption>조대 전자 컴공 귀염이들</caption>
        <tr>
            <th  style ="font-size:9px;">전공</th>
            <th  style ="font-size:9px;">수강</th>
            <th  style ="font-size:9px;">랄라</th>
        </tr>
        <tr>
            <td>
                <form>
                    <input type = "text" style ="font-size:9px;">
            </td>
            <td> <input type = "text" style ="font-size:9px;"> </td>
            <td><input type = "checkbox" style ="font-size:40px;">수강<imput></br></td>
        </tr>
        <tr class=""> 
            <td class="_subject">
                <input type="text" class="input_text end" title="과목"></td> 
            <td>
                <select title="과목별 점수 선택" style="width:64px;" onchange="tCR('a=nco_x3e*5.score&amp;r=1&amp;i=00138264_00000009F282');">
                    <option value="-1">선택</option>
                    <option value="4.5">A+</option>
                    <option value="4">A</option>
                    <option value="3.5">B+</option>
                    <option value="3">B</option>
                    <option value="2.5">C+</option>
                    <option value="2">C</option>
                    <option value="1.5">D+</option>
                    <option value="1">D</option>
                    <option value="0">F</option>
                </select></td> 

                <td class="tc">
                    <input type="text" class="input_text end" title="학점" maxlength="4" style="ime-mode:disabled;"></td> 
                    <td><input type="checkbox" title="전공" onclick="goOtherTCR(this, 'a=nco_x3e*5.major&amp;r=1&amp;i=00138264_00000009F282');"></td> </tr>
        <button type="button" class="btn_account_credit" onclick="goOtherTCR(this, 'a=nco_x3e*5.cal&amp;r=1&amp;i=00138264_00000009F282');">계산</button>
    </table>
    <div class="cal_result _result" style="display: block;"><dl class="credit"><dt>총 평점</dt><dd>3.38</dd><dt>전공평점</dt><dd>0</dd><dt>이수학점</dt><dd>8</dd><dt>전공이수</dt><dd>0</dd></dl><dl class="credit_chg"><dt>학점변환</dt><dd><strong>3</strong>/4.0<span class="blind">만점</span></dd><dd><strong>3.22</strong>/4.3<span class="blind">만점</span></dd><dd><strong>75</strong>/100<span class="blind">만점</span></dd></dl></div>
    <select name ="coffee">
        <option value = "1">아메리카노</option>
        <option value = "2">아리카노</option>
        <option value = "3">아메노</option>

    </select>
</body>
</html>
