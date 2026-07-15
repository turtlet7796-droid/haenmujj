<!DOCTYPE html>
<html lang="ko">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>해나무한의원 - 척추 관절, 수술 없이 바르게 치료합니다</title>
    <!-- Pretendard 폰트 불러오기 -->
    <link rel="stylesheet" as="style" crossorigin href="https://cdn.jsdelivr.net/gh/orioncactus/pretendard@v1.3.9/dist/web/static/pretendard.css" />
    <link rel="stylesheet" href="style.css">
</head>
<body>

    <!-- 헤더 / 내비게이션 -->
    <header class="header">
    <div class="container header-wrap">
        <h1 class="logo"><a href="#">해나무<span>한의원</span></a></h1>
        <nav class="nav">
            <a href="#philosophy">진료철학</a>
            <a href="#doctor">의료진소개</a>
            <a href="#subjects">진료과목</a>
            <a href="#hours">진료시간</a>
            <a href="#location">오시는길</a>
        </nav>
    </div>
</header>

    <!-- 1. 메인 대문 (Hero 섹션) -->
    <section class="hero">
        <div class="hero-bg"></div> <!-- 실제 운영 시 배경 이미지 지정 가능 -->
        <div class="container hero-content">
            <h2>해나무한의원</h2>
            <p>척추 관절, 수술 없이 바르게 치료합니다</p>
            <a href="tel:063-277-6688" class="btn btn-primary">전화 상담하기</a>
        </div>
    </section>

    <!-- 2. 진료 철학 섹션 -->
    <section id="philosophy" class="philosophy section">
        <div class="container text-center">
            <span class="sub-title">Philosophy</span>
            <h3 class="section-title">환자를 대하는 우리의 마음</h3>
            <p class="philosophy-text">
                해나무한의원은 일시적인 통증 완화에 그치지 않고, 몸의 자생력을 높여 근본적인 원인을 치료합니다.<br>
                내 가족을 치료하는 마음으로, 언제나 환자분들의 목소리에 귀 기울이며 진심을 다해 소통하겠습니다.<br>
                통증 없는 편안한 일상으로 돌아가실 수 있도록 든든한 건강 동반자가 되겠습니다.
            </p>
        </div>
    </section>

   <section id="doctor" class="doctor section bg-light">
        <div class="container">
            <div class="doctor-wrap">
                <div class="doctor-img">
                    <img alt="해나무한의원 한상희 원장 프로필 사진" src="image/doctor.jpg">
                </div>
                <div class="doctor-info">
                    <span class="sub-title">Medical Staff</span>
                    <h3 class="section-title">원장 한상희</h3>
                    <p class="doctor-intro">"정확한 진단과 올바른 치료로 척추·관절 건강을 지키겠습니다."</p>
                    <ul class="doctor-history">
                        <li>대한한의학회 정회원</li>
                        <li>한방재활관절학회 정회원</li>
                        <li>전) 지리산한방병원 진료원장</li>
                    </ul>
                </div>
            </div>
        </div>
    </section>

    <!-- 4. 진료 과목 안내 섹션 (그리드 형태) -->
    <section id="subjects" class="subjects section">
        <div class="container">
            <span class="sub-title text-center block">Medical Subjects</span>
            <h3 class="section-title text-center">주요 진료 과목</h3>
            <div class="grid-4">
                <div class="card">
                    <div class="card-icon">🚗</div>
                    <h4>교통사고 후유증</h4>
                    <p>어혈을 제거하고 긴장된 근육을 풀어주어 후유증을 최소화합니다.</p>
                </div>
                <div class="card">
                    <div class="card-icon">👐</div>
                    <h4>추나요법</h4>
                    <p>틀어진 척추와 골반을 바로잡아 통증의 원인을 근본적으로 치료합니다.</p>
                </div>
                <div class="card">
    <div class="card-icon">
        <img src="image/살다보면_한약이.jpg" alt="한약 필요 시기 안내" style="width: 100%; border-radius: 8px;">
    </div>
    <h4>한약</h4>
    <p>체질과 증상에 맞춘 1:1 맞춤 처방으로 건강을 되찾아 드립니다.</p>
</div>
                <div class="card">
                    <div class="card-icon">🏥</div>
                    <h4>산재치료</h4>
                    <p>근로 중 발생한 부상을 부담 없이, 체계적인 한방 치료로 회복합니다.</p>
                </div>
            </div>
        </div>
    </section>

    <!-- 5. 진료 시간표 섹션 -->
    <section id="hours" class="hours section bg-light">
        <div class="container">
            <span class="sub-title text-center block">Time & Notice</span>
            <h3 class="section-title text-center">진료 시간 안내</h3>
            
            <div class="table-responsive">
                <table class="time-table">
                    <thead>
                        <tr>
                            <th>월·수·금 (야간)</th>
                            <th>화·목</th>
                            <th>일요일 (주말진료)</th>
                            <th>점심시간</th>
                            <th>토요일·공휴일</th>
                        </tr>
                    </thead>
                    <tbody>
                        <tr>
                            <td>09:30 ~ <span class="highlight">20:30</span></td>
                            <td>09:30 ~ 19:00</td>
                            <td><span class="highlight">13:00 ~ 17:00</span></td>
                            <td>13:00 ~ 14:00</td>
                            <td><span class="text-muted">휴진</span></td>
                        </tr>
                    </tbody>
                </table>
            </div>
            <p class="table-notice">* 일요일은 점심시간 없이 진료합니다. 평일 야간진료로 퇴근 후에도 편하게 내원하세요.</p>
        </div>
    </section>

    <!-- 6. 오시는 길 섹션 -->
    <section id="location" class="location section">
        <div class="container">
            <span class="sub-title text-center block">Directions</span>
            <h3 class="section-title text-center">오시는 길</h3>
            
            <div class="location-wrap">
                <!-- 네이버 지도 API 혹은 iframe 들어갈 자리 -->
               <div class="map-area">
    <iframe src="https://map.naver.com/p/search/%ED%95%B4%EB%82%98%EB%AC%B4%ED%95%9C%EC%9D%98%EC%9B%90/place/815486299?c=15.00,0,0,0,dh" width="100%" height="400" frameborder="0" style="border:0;" allowfullscreen></iframe>
</div>
                <div class="location-info">
                    <h4>해나무한의원</h4>
                    <p class="address"><strong>주소:</strong> 전주시 덕진구 솔내로 152, 푸른시티 2층</p>
                    <hr>
                    <div class="transport">
                        <h5>🚍 대중교통 이용 시</h5>
                        <p>일반버스 100번, 200번 승차 후 '푸른시티 앞' 정류장 하차 (도보 1분)</p>
                        <h5>🚗 주차 안내</h5>
                        <p>건물 지하 주차장 및 후면 전용 주차장 무료 이용 가능 (최대 2시간 지원)</p>
                    </div>
                </div>
            </div>
        </div>
    </section>

    <!-- 푸터 (하단 정보란) -->
    <footer class="footer">
        <div class="container footer-wrap">
            <div class="footer-info">
                <p class="footer-logo">해나무한의원</p>
                <p>대표자: 한상희 | 사업자등록번호: 232-92-00335 | 대표전화: <a href="tel:063-277-6688">063-277-6688</a></p>
                <p>주소: 전주시 덕진구 솔내로 152, 푸른시티 2층 | 이메일: contact@henamu.com</p>
                <p class="copyright">&copy; 2026 해나무한의원. All Rights Reserved.</p>
            </div>
            <div class="footer-links">
                <a href="non-benefit.html" class="btn-link">비급여 목록표 보기 &rarr;</a>
            </div>
        </div>
    </footer>

    <!-- 플로팅 버튼 -->
    <div class="floating-buttons">
        <a href="https://booking.naver.com" target="_blank" class="float-btn float-naver">
            <span>💚 네이버 예약</span>
        </a>
        <a href="tel:063-277-6688" class="float-btn float-phone">
            <span>📞 전화 문의</span>
        </a>
    </div>

</body>
</html>
