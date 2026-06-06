<!DOCTYPE html>
<html lang="ko">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>이동영 | Portfolio</title>

    <link rel="stylesheet" href="style.css">
</head>

<body>

<header>
    <div class="hero">
        <h1>안녕하세요.<br>개발자 <span>이동영</span>입니다.</h1>
        <p>코드를 통해 아이디어를 현실로 만드는 것을 좋아합니다.</p>
        <a href="#about" class="btn">포트폴리오 보기</a>
    </div>
</header>

<section id="about">
    <h2 class="section-title">👋 자기소개</h2>

    <div class="card">
        <p>
            안녕하세요. 이동영입니다.
            새로운 기술을 배우고 직접 구현해보는 것을 좋아합니다.
            사용자에게 도움이 되는 서비스를 만드는 것이 목표이며,
            꾸준한 학습과 도전을 통해 성장하고 있습니다.
        </p>
    </div>
</section>

<section>
    <h2 class="section-title">🎯 프로젝트 목표</h2>

    <div class="card">
        <p>
            웹 개발 기술을 학습하고 실제 서비스를 배포하는 경험을 얻기 위해
            개인 포트폴리오 웹사이트를 제작하였습니다.
        </p>
    </div>
</section>

<section>
    <h2 class="section-title">🛠 사용 기술</h2>

    <div class="skills">
        <div class="skill">HTML5</div>
        <div class="skill">CSS3</div>
        <div class="skill">JavaScript</div>
        <div class="skill">Git</div>
        <div class="skill">GitHub</div>
        <div class="skill">GitHub Pages</div>
    </div>
</section>

<section>
    <h2 class="section-title">🚀 프로젝트</h2>

    <div class="card project">
        <h3>개인 포트폴리오 웹사이트</h3>
        <br>

        <p><strong>제작 기간</strong><br>2026.05 ~ 2026.06</p>
        <br>

        <p><strong>배포 주소</strong><br>
        https://your-github-pages-url.github.io/
        </p>

        <br>

        <p><strong>프로젝트 구조</strong></p>
        <ul>
            <li>html</li>
            <li>css</li>
            <li>script.js</li>
            <li>assets</li>
        </ul>

        <br>

        <p><strong>주요 기능</strong></p>
        <ul>
            <li>자기소개</li>
            <li>기술 스택 소개</li>
            <li>프로젝트 소개</li>
            <li>반응형 웹 지원</li>
            <li>GitHub 연결</li>
        </ul>
    </div>
</section>

<section>
    <h2 class="section-title">📱 반응형 웹</h2>

    <div class="card">
        <p>
            모바일, 태블릿, PC 환경에 맞춰 화면이 자동으로 최적화되도록
            반응형 웹 디자인을 적용했습니다.
        </p>
    </div>
</section>

<section>
    <h2 class="section-title">📚 배운 점</h2>

    <div class="card">
        <p>
            Git과 GitHub를 활용한 버전 관리,
            GitHub Pages를 통한 배포 과정,
            그리고 반응형 웹 제작 경험을 쌓을 수 있었습니다.
        </p>
    </div>
</section>

<section>
    <h2 class="section-title">🔧 트러블 슈팅</h2>

    <div class="card">
        <h3>GitHub Pages 배포 오류</h3>
        <br>
        <p>
            사이트가 열리지 않는 문제가 발생했습니다.
            확인 결과 Pages 브랜치가 설정되지 않았고,
            main 브랜치를 지정하여 해결했습니다.
        </p>
    </div>

    <div class="card">
        <h3>모바일 화면 깨짐</h3>
        <br>
        <p>
            고정 크기 사용으로 인해 레이아웃이 깨졌습니다.
            Flexbox와 미디어쿼리를 활용해 해결했습니다.
        </p>
    </div>
</section>

<footer>
    <p>© 2026 이동영 Portfolio</p>
</footer>

</body>
</html>

*{
    margin:0;
    padding:0;
    box-sizing:border-box;
    scroll-behavior:smooth;
}

body{
    font-family:'Segoe UI', sans-serif;
    background:#0f172a;
    color:#f8fafc;
}

header{
    min-height:100vh;
    display:flex;
    justify-content:center;
    align-items:center;
    text-align:center;
    padding:20px;
    background:linear-gradient(135deg,#0f172a,#1e293b);
}

.hero h1{
    font-size:4rem;
    margin-bottom:10px;
}

.hero span{
    color:#38bdf8;
}

.hero p{
    color:#94a3b8;
    font-size:1.2rem;
    margin-bottom:25px;
}

.btn{
    display:inline-block;
    padding:12px 25px;
    background:#38bdf8;
    color:#0f172a;
    text-decoration:none;
    border-radius:8px;
    font-weight:bold;
    transition:.3s;
}

.btn:hover{
    transform:translateY(-3px);
}

section{
    max-width:1100px;
    margin:auto;
    padding:80px 20px;
}

.section-title{
    text-align:center;
    font-size:2rem;
    margin-bottom:40px;
    color:#38bdf8;
}

.card{
    background:#1e293b;
    padding:25px;
    border-radius:15px;
    margin-bottom:20px;
    transition:.3s;
}

.card:hover{
    transform:translateY(-5px);
}

.skills{
    display:flex;
    flex-wrap:wrap;
    gap:10px;
}

.skill{
    background:#334155;
    padding:10px 15px;
    border-radius:999px;
}

.project{
    border-left:4px solid #38bdf8;
}

footer{
    text-align:center;
    padding:30px;
    color:#94a3b8;
}

@media(max-width:768px){

    .hero h1{
        font-size:2.5rem;
    }

    .section-title{
        font-size:1.7rem;
    }

}
