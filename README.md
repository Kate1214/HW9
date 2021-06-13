<html lang="zh-tw">

<head>
    <!-- Required meta tags -->
    <meta charset="utf-8">
    <meta name="viewport" content="width=device-width, initial-scale=1">

    <!-- Bootstrap CSS -->
    <link href="https://cdn.jsdelivr.net/npm/bootstrap@5.0.1/dist/css/bootstrap.min.css" rel="stylesheet" integrity="sha384-+0n0xVW2eSR5OomGNYDnhzAbDsOXxcvSN1TPprVMTNDbiYZCxYbOOl7+AMvyTG2x" crossorigin="anonymous">
    <style>
        .well,
        .panel {
            text-align: center;
        }
    </style>

    <title>HW09</title>

</head>

<body>
    <h1 style="text-align: center;">HW09</h1>

    <div class="container-fluid">
        <div class="row">
            <div class="col-sm-4">
                <div class="panel panel-default">
                    <div class="panel-heading">這是網頁作業區</div>
                    <div class="panel-body">
                        <div style="text-align: center;border-radius:10px;border:2px rgb(38, 0, 255) solid;">基本個人資料表列</div>
                        <div style="text-align: center;border-radius:10px;border:2px rgb(38, 0, 255);">
                            <span style="box-shadow:3px 3px 5px 6px #cccccc;text-align: center;border-radius:10px;border:2px rgb(0, 255, 221) solid;width:49.5%;display: inline-block;">學號</span>
                            <span style="box-shadow:3px 3px 5px 6px #cccccc;text-align: center;border-radius:10px;border:2px rgb(0, 255, 221) solid;width:49%;display: inline-block;">1064410</span>

                            <span style="box-shadow:3px 3px 5px 6px #cccccc;text-align: center;border-radius:10px;border:2px rgb(0, 255, 34) solid;width:49.5%;display: inline-block;">姓名</span>
                            <span style="box-shadow:3px 3px 5px 6px #cccccc;text-align: center;border-radius:10px;border:2px rgb(0, 255, 34) solid;width:49%;display: inline-block;">陳乃宇</span>

                        </div>
                        <br>
                        <br>
                        <div style="text-align: center;border-radius:10px;border:2px red solid;">作業表列</div>
                        <div style="text-align: center;border-radius:10px;border:2px blue solid;">
                            <span style="box-shadow:3px 3px 5px 6px #cccccc;text-align: center;border-radius:10px;border:2px rgb(0, 255, 221) solid;width:49.5%;display: inline-block;">Deadline</span>
                            <span style="box-shadow:3px 3px 5px 6px #cccccc;text-align: center;border-radius:10px;border:2px rgb(0, 255, 221) solid;width:49.5%;display: inline-block;">2021/0323</span>
                            <span style="box-shadow:3px 3px 5px 6px #cccccc;text-align: center;border-radius:10px;border:2px rgb(0, 255, 34) solid;width:49.5%;display: inline-block;">作業編號</span>
                            <span style="box-shadow:3px 3px 5px 6px #cccccc;text-align: center;border-radius:10px;border:2px rgb(0, 255, 34) solid;width:49.5%;display: inline-block;">HW01</span>
                            <span style="box-shadow:3px 3px 5px 6px #cccccc;text-align: center;border-radius:10px;border:2px blue solid;width:49.5%;display: inline-block;">作業主要練習議題</span>
                            <span style="box-shadow:3px 3px 5px 6px #cccccc;text-align: center;border-radius:10px;border:2px blue solid;width:49.5%;display: inline-block;">練習平台線上作業</span>
                        </div>
                    </div>
                </div>
            </div>
            <div class="col-sm-8">
                <div class="panel panel-default">
                    <div class="panel-heading">BMI計算<br>請分別輸入體重(kg)、身高(cm)</div>
                    <div class="panel-body">
                        <form oninput="result.value=((parseFloat(b.value))/(parseFloat(a.value)/100)/(parseFloat(a.value)/100))">
                            <p>體重<input type="number" id="b" name="b" value="52" />kg</p>
                            <p>身高<input type="number" id="a" name="a" value="155" />cm</p>
                            <p>bmi=<output name="result" for="a b">21.6</output></p>
                            <button onclick="start()">回到初始值</button>
                            <script>
                                function start(){
                                    result.value=((parseFloat(b.value))/(parseFloat(a.value)/100)/(parseFloat(a.value)/100));
                                }
                            </script>
                        </form>
                    </div>
                </div>
            </div>
        </div>
    </div>
    <!-- Optional JavaScript; choose one of the two! -->

    <!-- Option 1: Bootstrap Bundle with Popper -->
    <script src="https://cdn.jsdelivr.net/npm/bootstrap@5.0.1/dist/js/bootstrap.bundle.min.js" integrity="sha384-gtEjrD/SeCtmISkJkNUaaKMoLD0//ElJ19smozuHV6z3Iehds+3Ulb9Bn9Plx0x4" crossorigin="anonymous"></script>

    <!-- Option 2: Separate Popper and Bootstrap JS -->
    <!--
        <script src="https://cdn.jsdelivr.net/npm/@popperjs/core@2.9.2/dist/umd/popper.min.js" integrity="sha384-IQsoLXl5PILFhosVNubq5LC7Qb9DXgDA9i+tQ8Zj3iwWAwPtgFTxbJ8NT4GN1R8p" crossorigin="anonymous"></script>
        <script src="https://cdn.jsdelivr.net/npm/bootstrap@5.0.1/dist/js/bootstrap.min.js" integrity="sha384-Atwg2Pkwv9vp0ygtn1JAojH0nYbwNJLPhwyoVbhoPwBhjQPR5VtM2+xf0Uwh9KtT" crossorigin="anonymous"></script>
        -->
</body>

</html>
