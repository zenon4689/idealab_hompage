---
# Leave the homepage title empty to use the site title
title:
date: 2022-10-24
type: landing

# 홈페이지 배너 부분
sections:
  - block: markdown
    content:
      title:
      subtitle: ''
      text:
    design:
      columns: '1'
      background:
        image: 
          filename: semi3.png
          filters:
            brightness: 1
          parallax: false
          position: center
          size: cover
          text_color_light: true
      spacing:
        padding: ['0', '0', '0', '0']
      css_class: fullscreen
##########################################################
################연구실 소개글##############################
##########################################################
  - block: markdown
    content:
      title: Welcome to INTELLIGENT DATA-CENTRIC EMERGING ARCHITECTURE LAB(IDEA.L) at SKKU.
      subtitle: 
      text: |
        <style>
          .centered-text {
            text-align: center;
          }
        </style>

        <div class="centered-text">
        <br>

        IDEA 연구실에서는 반도체 칩으로 구현되는 System-on-Chip (SoC) 아키텍처와 설계 기술에 관련된 하드웨어와 <br>소프트웨어에서의 다양한 문제들을 연구하고 있습니다. 최근 우리는 빅 데이터와 인공지능 어플리케이션에서 기인하는 <br>메모리 및 스토리지 데이터 병목현상을 해결하기 위한 지능형 데이터 중심 컴퓨팅 아키텍처, optical link를 포함하는 <br>차세대 온칩 인터커넥트 등의 분야에서 시스템 레벨 연구에 초점을 맞추고 있습니다.<br><br>

        The IDEA lab is investigating various hardware and software challenges related to System-on-Chip (SoC) <br>architecture and design technology implemented as semiconductor chips. We have recently focused on <br>system-level research in intelligent data-driven computing architectures to address memory and storage <br>data bottlenecks caused by big data and artificial intelligence applications, as well as next-generation <br>on-chip interconnects including optical links.
        </div>


        <br>
        {{% cta cta_link="./contact/" cta_text="Contact us →" %}}
    design:
      columns: '1'
##########################################################
################Research area#############################
##########################################################
  - block: markdown
    content:
      title: 
      subtitle: 
      text: |
        <style>
          .centered-text {
            text-align: center;
          }
          .image-grid {
            display: flex;
            justify-content: center;
            gap: 50px;
          }
          .image-grid figure {
            text-align: center;
          }
          .image-grid img {
            width: 1000px; /* 원하는 크기로 설정 */
            height: auto;
          }
          .image-grid figcaption {
            margin-top: 10px;
            font-size: 30px;
            color: #666;
          }

        </style>

        <div class="centered-text">
          <h2><b>Research Area</b></h2>
        </div>
        <br>


        <div class="image-grid">
          <figure>
            <img src="image1.jpg" alt="Image 1 Caption">
            <figcaption><b>AI Acceleration</b></figcaption>
          </figure>
          <figure>
            <img src="image2.jpg" alt="Image 2 Caption">
            <figcaption><b>SoC On-Chip Network</b></figcaption>
          </figure>
          <figure>
            <img src="image3.jpg" alt="Image 3 Caption">
            <figcaption><b>Near Data Processing</b></figcaption>
          </figure>
          <figure>
            <img src="image4.jpg" alt="Image 4 Caption">
            <figcaption><b>Next Generation Memory</b></figcaption>
          </figure>
        </div>
    design:
      columns: '1'
##########################################################
################연구실 소식################################
##########################################################
  - block: markdown
    content: 
      title: Recent NEWS
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
            </style>
        </head>
        <body>
            <div class="banner">
                <div class="year-divider"><span class="year">2024</span></div>
                <div class="banner-item">
                    <p>(2024-04) <strong>Yong Wook Kim</strong>'s paper is accepted by the IEEE Access.</p>
                </div>
                <div class="banner-item">
                    <p>(2024-03) <strong>Ho Jung Yoo</strong>'s paper is selected as the featured article in IEEE Access.</p>
                </div>
                <div class="banner-item">
                    <p>(2024-02) <strong>Won Hyeok Kim</strong>'s paper is accepted by the ICAIIC.</p>
                </div>
                <div class="banner-item">
                    <p>(2024-02) Welcome! <strong>Woo Hyun Kim, Sung Ryong Yoo, and Min Jun Kim</strong> have joined our group as graduate students.</p>
                </div>
                <div class="year-divider"><span class="year">2023</span></div>
                <div class="banner-item">
                    <p>(2023-12) <strong>Ho Jung Yoo</strong>'s paper is accepted by the IEEE Access.</p>
                </div>
                <div class="banner-item">
                    <p>(2023-11) <strong>Ju Yeon Kang</strong>'s paper is accepted by the IEEE Access.</p>
                </div>
                <div class="banner-item">
                    <p>(2023-08) Welcome! <strong>Hyung Jin Kim and Ji Hun Choi</strong> have joined our group as graduate students.</p>
                </div>
                <div class="banner-item">
                    <p>(2023-02) Welcome! <strong>Han Sol Kim and Won Hyeok Kim</strong> have joined our group as graduate students.</p>
                </div>
                <div class="banner-item">
                    <p>(2023-01) <strong>Ju Yeon Kang</strong>'s paper is accepted by the IEEE Access.</p>
                </div>
                <div class="banner-item">
                    <p>(2023-01) <strong>Jae Eun Shim</strong>'s paper is accepted by the IEEE Access.</p>
                </div>
                <div class="year-divider"><span class="year">2022</span></div>
                <div class="banner-item">
                    <p>(2022-12) <strong>Hyun Jo Lim</strong>'s paper is accepted by the MDPI Electronics.</p>
                </div>
                <div class="banner-item">
                    <p>(2022-10) <strong>Young Sik Lee</strong>'s paper is accepted by the IEEE Transactions on Parallel and Distributed Systems (TPDS).</p>
                </div>
                <div class="banner-item">
                    <p>(2022-09) <strong>Prof. Tae Hee Han</strong> has been elevated to the senior member of the IEEE.</p>
                </div>
                <div class="banner-item">
                    <p>(2022-08) Welcome! <strong>Suk Bong Kang and Hui Ze Hong</strong> have joined our group as graduate students.</p>
                </div>
                <div class="banner-item">
                    <p>(2022-08) <strong>Sang Min Hyun</strong>'s paper is accepted by the MDPI Electronics.</p>
                </div>
                <div class="banner-item">
                    <p>(2022-07) <strong>Min Gu Kang</strong>'s paper is accepted by the IEEE Access.</p>
                </div>
                <div class="banner-item">
                    <p>(2022-05) <strong>Prof. Tae Hee Han</strong> is awarded the SKKU Teaching Award.</p>
                </div>
                <div class="banner-item">
                    <p>(2022-02) Welcome! <strong>Chang Ho Ryu and Ho Jung Yoo</strong> have joined our group as graduate students.</p>
                </div>
                <div class="year-divider"><span class="year">2021</span></div>
                <div class="banner-item">
                    <p>(2021-12) <strong>Min Chae Yang</strong> is accepted by the Samsung Electronics Memory business.</p>
                </div>
                <div class="banner-item">
                    <p>(2021-12) <strong>Min Chae Yang</strong>'s paper is accepted by the IEEE Access.</p>
                </div>
                <div class="banner-item">
                    <p>(2021-11) <strong>Prof. Tae Hee Han</strong> serves as the Program Manager in Computer System & Processing, National Research Foundation of Korea.</p>
                </div>
                <div class="banner-item">
                    <p>(2021-08) <strong>Yong Wook Kim</strong>'s paper is accepted by the IEEE Access.</p>
                </div>
                <div class="banner-item">
                    <p>(2021-05) <strong>Young Sik Lee</strong>'s paper is accepted by the IEEE Access.</p>
                </div>
            </div>
        </body>
    design:
      columns: '1'
      
  
---
