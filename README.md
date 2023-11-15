<!DOCTYPE html>
<html>
    <head>
        <title>jQuery Basic</title>
        <style>
            #box {
                width: 100px; height: 100px;
                background-color: skyblue;
            }
    
            #box.hover {
                background-color: greenyellow;
                border-radius: 50px;
            }
        </style>
        <script src="https://code.jquery.com/jquery-3.1.0.js"></script>
        <script>
            $(document).ready(function () {
                $('#box').hover(function () {
                    // 스타일을 변경합니다.
                    $('#box').addClass('hover');
                }, function () {
                    // 스타일을 변경합니다.
                    $('#box').removeClass('hover');
                });
            });
        </script>
    </head>
    <body>
        <div id="box"></div>
    </body>
    <head>
        <title>Event Basic</title>
        <script src="https://code.jquery.com/jquery-3.1.0.js"></script>
        <script>
            // 이벤트를 연결합니다.
            $(document).ready(function () {
                // 이벤트를 연결합니다.
                $('button').click(function () {
                    // 간단한 효과를 적용합니다.
                    $('.page').fadeToggle('slow');
                });
            });
        </script>
    </head>
    <body>
        <button>Toggle Show</button>
        <div class="page">
            <h1>집에 가고싶다</h1>
            <p>집에 보내주세요 제발제발제발제발제발제발제발제발제발제발제발제발 </p>
        </div>
    </body>
<head>
    <title>집에가고싶다.</title>
    <script src="https://code.jquery.com/jquery-3.1.0.js"></script>
    <head>
        <title>Clock</title>
        <script>
           // 이벤트를 연결합니다.
           window.onload = function () {
              // 변수를 선언합니다.
              var clock = document.getElementById('clock');
  
              // 1초마다 함수를 실행합니다.
              setInterval(function () {
                 var now = new Date();
                 clock.innerHTML = now.toString();
  
              }, 1000);
           };
        </script>
     </head>
     <body>
        <h1 id="clock"></h1>
     </body>
    <script>
        // 이벤트를 연결합니다.
        $(document).ready(function () {
            // 스타일 속성을 변경합니다.
            $('h1').css('color', 'pink');
            $('h1').css('background', 'skyblue');
        });
    </script>
</head>
<body>
    <h1>집에</h1>
    <h1>가고</h1>
    <h1>싶다</h1>
</body>
<head>
    <title>Animate Basic</title>
    <script src="https://code.jquery.com/jquery-3.1.0.js"></script>
    <script>
        // 이벤트를 연결합니다.
        $(document).ready(function () {
            // 이벤트를 연결합니다.
            $('h1').hover(function () {
                // 색상을 변경합니다.
                $(this).css({
                    background: 'skyblue',
                    color: 'white'
                });
            }, function () {
                // 색상을 제거합니다.
                $(this).css({
                    background: '',
                    color: ''
                });
            });
        });
    </script>
</head>
<body>
    <h1>Click</h1>
</body>
<head>
    <title>jQuery Basic</title>
    <script src="https://code.jquery.com/jquery-3.1.0.js"></script>
    <script>
        $(document).ready(function () {
            // 스타일을 적용합니다.
            $('.box').css('float', 'left');
            $('.box').css('margin', 10);
            $('.box').css('width', 100);
            $('.box').css('height', 100);
            $('.box').css('backgroundColor', 'skyblue');
        });
    </script>
    
</head>
<body>
    <div class="box"><h1>집에</h1></div>
    <div class="box"><h1>가고</h1></div>
    <div class="box"><h1>싶다</h1></div>
</body>
</html>
