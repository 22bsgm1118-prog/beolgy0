<!DOCTYPE html>
<html lang="ko">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>우리학교 통합 포털</title>
    <style>
        /* 깔끔한 디자인을 위한 스타일 설정 */
        body {
            font-family: 'Malgun Gothic', sans-serif;
            margin: 0;
            padding: 0;
            background-color: #f5f7fa;
            color: #333;
        }
        header {
            background-color: #4a90e2;
            color: white;
            text-align: center;
            padding: 2rem 1rem;
        }
        header h1 {
            margin: 0;
            font-size: 1.8rem;
        }
        header p {
            margin: 0.5rem 0 0 0;
            opacity: 0.9;
        }
        .container {
            max-width: 800px;
            margin: 2rem auto;
            padding: 0 1rem;
        }
        .grid {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(150px, 1fr));
            gap: 1rem;
        }
        /* 버튼 역할을 하는 카드 디자인 */
        .card {
            background: white;
            padding: 1.5rem;
            border-radius: 12px;
            text-align: center;
            text-decoration: none;
            color: #333;
            box-shadow: 0 4px 6px rgba(0,0,0,0.05);
            transition: transform 0.2s, box-shadow 0.2s;
            border: 1px solid #e1e4e8;
        }
        .card:hover {
            transform: translateY(-5px);
            box-shadow: 0 8px 12px rgba(0,0,0,0.1);
            border-color: #4a90e2;
        }
        .card .icon {
            font-size: 2rem;
            margin-bottom: 0.5rem;
        }
        .card .title {
            font-weight: bold;
            font-size: 1rem;
        }
        footer {
            text-align: center;
            padding: 2rem;
            color: #888;
            font-size: 0.9rem;
        }
    </style>
</head>
<body>

    <!-- 상단 헤더 영역 -->
    <header>
        <h1>🏫 고등학교 학생 통합 포털</h1>
        <p>학생들을 위한 링크 모음 서비스</p>
    </header>

    <!-- 메인 메뉴 버튼 영역 -->
    <div class="container">
        <div class="grid">
            <!-- 나중에 href="여기에 링크"를 넣으면 그 사이트로 이동합니다 -->
            <a href="https://www.neis.go.kr" target="_blank" class="card">
                <div class="icon">🍱</div>
                <div class="title">오늘의 급식</div>
            </a>
            <a href="#" class="card">
                <div class="icon">📅</div>
                <div class="title">학사 일정</div>
            </a>
            <a href="#" class="card">
                <div class="icon">📝</div>
                <div class="title">수행평가 정보</div>
            </a>
            <a href="#" class="card">
                <div class="icon">📣</div>
                <div class="title">학생회 공지</div>
            </a>
            <a href="#" class="card">
                <div class="icon">💬</div>
                <div class="title">익명 건의함</div>
            </a>
            <a href="#" class="card">
                <div class="icon">🎒</div>
                <div class="title">동아리 안내</div>
            </a>
        </div>
    </div>

    <!-- 하단 정보 영역 -->
    <footer>
        <p>© 2026 학생 자치회 크루. All rights reserved.</p>
    </footer>

</body>
</html>
