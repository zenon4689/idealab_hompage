---
# Leave the homepage title empty to use the site title
title: media
date: 2022-10-24
type: landing

# 홈페이지 배너 부분
sections:
  - block: markdown
    content: 
      title: Media
      subtitle: 
      text: |
        <head>
            <meta charset="UTF-8">
            <meta name="viewport" content="width=device-width, initial-scale=1.0">
            <title>Banner Example</title>
            <style>
                body {
                    font-family: Arial, sans-serif;
                    background-color: #f7f7f7;
                }
                .banner {
                    display: flex;
                    flex-direction: column;
                    width: 1200px;
                    margin: 10px auto;
                }
                .year-divider {
                    display: flex;
                    align-items: center;
                    margin: 20px 0;
                }
                .year-divider::before {
                    content: "";
                    flex-grow: 1;
                    height: 1px;
                    background: #000;
                    margin-right: 10px;
                }
                .year-divider::after {
                    content: "";
                    flex-grow: 1;
                    height: 1px;
                    background: #000;
                    margin-left: 10px;
                }
                .year {
                    font-weight: bold;
                    font-size: 1.5em;
                }
                .banner-item {
                    background-color: #f0f0f0;
                    margin: 10px 0;
                    padding: 30px;
                    border-radius: 10px;
                    transition: transform 0.3s;
                    box-shadow: 0 4px 8px rgba(0, 0, 0, 0.1);
                }
                .banner-item:hover {
                    transform: scale(1.05);
                }
                .banner-item a {
                    text-decoration: none;
                    color: inherit;
                }
            </style>
        </head>
        <body>
            <div class="banner">
                <div class="year-divider"><span class="year">2022</span></div>
                <div class="banner-item">
                    <a href="#"><p>(2022-05-12) <strong>Prof. Tae Hee Han</strong> is awarded the SKKU Teaching Award.</p></a>
                </div>
                <div class="banner-item">
                    <a href="#"><p>(2022-01-10) <strong>Related News</strong>: 삼성전자 올해 파운드리 설비투자 전망치 15조원… TSMC는 50조원 - 시사저널이코노미</p></a>
                </div>
                <div class="banner-item">
                    <a href="#"><p>(2021-11-15) <strong>Related News</strong>: [창간 14주년 기획-2022 리스타트 원년] 반도체·AI·배터리… 미래기술 패권경쟁 불붙었다 - 아주경제</p></a>
                </div>
                <div class="banner-item">
                    <a href="#"><p>(2021-09-29) <strong>Related News</strong>: 투자 확대하는 반도체 후공정 업체들… 외형 성장으로 이어질까 - 시사저널이코노미</p></a>
                </div>
                <div class="banner-item">
                    <a href="#"><p>(2021-08-20) <strong>Related News</strong>: K-반도체, 글로벌 종합반도체 1위 비전 빨라진다 - 머니S</p></a>
                </div>
                <div class="banner-item">
                    <a href="#"><p>(2021-08-20) <strong>Related News</strong>: "반도체 겨울은 오지 않았다"… 전문가 "수요 견조" 이구동성 - 뉴스1</p></a>
                </div>
                <div class="banner-item">
                    <a href="#"><p>(2021-01-05) <strong>Related News</strong>: '수출 1000억#' 반도체 빅4가 온다… 정부, 사상 첫 반도체 전략지 발표 - 조선비즈</p></a>
                </div>
                <div class="year-divider"><span class="year">2020</span></div>
                <div class="banner-item">
                    <a href="#"><p>(2020-06-24) <strong>인터뷰</strong>: "반도체 생태계 조성 통해 고용창출 효과와 성장 기반 다져야" - 테크월드뉴스</p></a>
                </div>
                <div class="banner-item">
                    <a href="#"><p>(2020-06-07) <strong>한태희 교수</strong>의 IDEAL (Intelligent Data-centric Emerging Architecture Lab) - 성균웹진</p></a>
                </div>
                <div class="year-divider"><span class="year">2019</span></div>
                <div class="banner-item">
                    <a href="#"><p>(2019-11-05) <strong>Related News</strong>: 삼성 CPU 핵심기술 개발 중단?... 차세대 AP 집중하나 - SBS Biz</p></a>
                </div>
                <div class="banner-item">
                    <a href="#"><p>(2019-05-20) <strong>Related News</strong>: 퀄컴·ARM·인텔·화웨이·삼성의 '더 큰 미래' 죽음 - 이코노미조선</p></a>
                </div>
                <div class="banner-item">
                    <a href="#"><p>(2019-02-25) <strong>인터뷰</strong>: "빅메모리 강화는 삼성의 숙명…AP부터 잡아라" - 이코노미조선</p></a>
                </div>
                <div class="banner-item">
                    <a href="#"><p>(2019-05-13) <strong>Related News</strong>: 한국 경제의 Last shot 시스템 반도체·삼성 "2030년 세계 1위" 호 "적극 돕겠다" - 매경 이코노미</p></a>
                </div>
                <div class="banner-item">
                    <a href="#"><p>(2019-05-13) <strong>Related News</strong>: 35년간의 R&D 쌓은 韓 반도체 '종대 기밀' - 파이낸셜뉴스</p></a>
                </div>
                <div class="year-divider"><span class="year">2018</span></div>
                <div class="banner-item">
                    <a href="#"><p>(2018-12-31) <strong>Related News</strong>: 위기의 韓 화웨이 '반도체 코리아' 운영 3년이 좌우한다 - 주간조선</p></a>
                </div>
                <div class="banner-item">
                    <a href="#"><p>(2018-12-31) <strong>Related News</strong>: 인간의 뇌 닮은 AI반도체 경쟁… 112조원 시장을 잡아라 - 조선비즈</p></a>
                </div>
                <div class="year-divider"><span class="year">2016</span></div>
                <div class="banner-item">
                    <a href="#"><p>(2016-07-06) <strong>수상</strong>: 한국과학기술한림원 과학기술 우수논문상 수상</p></a>
                </div>
                <div class="year-divider"><span class="year">2015</span></div>
                <div class="banner-item">
                    <a href="#"><p>(2015-01-09) <strong>Related News</strong>: 서울인터넷에 반도체 업계 왜 반색하나 - 한국경제매거진</p></a>
                </div>
            </div>
        </body>
    design:
      columns: '1'
      
  
---
