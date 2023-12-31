<!DOCTYPE html>
<html lang="en">

<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>2023 Bucket-List</title>
    <style>
        @import url('https://fonts.googleapis.com/css2?family=Noto+Sans+KR:wght@400;500;700&display=swap');

        * {
            font-family: 'Noto Sans KR', sans-serif;
        }

        .title {
            color: aliceblue;
            background-color: tomato;
            font-size: 24px;
            padding: 4px 14px;
            /* padding은 여백: 위아래 양옆 순, *{} 전체 다 적용 */
            border-radius: 8px;
        }

        .bg {
            width: 360px;
            background-image: url("https://s3.ap-northeast-2.amazonaws.com/materials.spartacodingclub.kr/bucketList/bg-grid.png");
        }

        .msg {
            font-weight: bold;
        }

        .bucket {
            width: 160px;
            height: 160px;
        }

        ,
        .img1 {
            background-image: url("https://s3.ap-northeast-2.amazonaws.com/materials.spartacodingclub.kr/bucketList/bucket-red.png");
            background-size: cover;
            background-position: center;
        }

        .img2 {
            background-image: url("https://s3.ap-northeast-2.amazonaws.com/materials.spartacodingclub.kr/bucketList/bucket-lightred.png");
            background-size: cover;
            background-position: center;
        }
    </style>
    <link rel="stylesheet" type="text/css" href="https://s3.ap-northeast-2.amazonaws.com/materials.spartacodingclub.kr/bucketList/sparta-bucket2.css">
</head>

<body class="bg center">
    <h1 class="title">2024 MECE</h1>
    <!--h는 제목, p는 문단, div는 박스-->
    <p class="msg">Once move forward, results must follow you.</p>
    <div class="row flex-row wrap">
        <div class="bucket img1-t2 center">1월: 토익 900</div>
        <div class="bucket img2-t2 center">2월: 테셋, 컴활 1급</div>
        <div class="bucket img2-t2 center">첨삭&프로젝트 진행(코멘토)</div>
        <!-- 완료시 done 추가 -->
        <div class="bucket img1-t2 center">크리에이터 활동 확대(매체별 관리)</div>
        <div class="bucket img1-t2 center">부모님 여행 보내드리기(200만원)</div>
        <div class="bucket img2-t2 center">상반기 대기업 취업</div>
    </div>
</body>

</html>
