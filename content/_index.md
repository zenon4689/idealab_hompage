---
# Leave the homepage title empty to use the site title
title:
date: 2022-10-24
type: landing

sections:
  - block: markdown
    content:
      title: 
      subtitle: 
      text: |
        <style>
          .banner-image {
            width: 100%;
            height: auto;
          }
          .banner-container {
            text-align: center;
            margin-bottom: 0px;
          }
        </style>

        <div class="banner-container">
          <img class="banner-image" src="semi3.png" alt="Banner Image">
        </div>
    design:
      columns: '1'





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

  - block: markdown
    content: Recent NEWS
      title: 
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
                  width: 600px; /* 배너의 너비를 늘립니다 */
                  margin: 20px auto;
              }
              .banner-item {
                  background-color: #f0f0f0;
                  margin: 20px 0; /* 간격을 넓힙니다 */
                  padding: 30px; /* 패딩을 늘립니다 */
                  border-radius: 10px;
                  transition: transform 0.3s;
                  box-shadow: 0 4px 8px rgba(0, 0, 0, 0.1); /* 그림자 추가 */
              }
              .banner-item:hover {
                  transform: scale(1.05);
              }
          </style>
        </head>
        <body>
          <div class="banner">
              <div class="banner-item">
                  <p>(2024-04) <strong>Yong Wook Kim</strong>'s paper is accepted by the IEEE Access.</p>
              </div>
              <div class="banner-item">
                  <p>(2024-03) <strong>Ho Jung Yoo</strong>'s paper is selected as the featured article in IEEE Access.</p>
              </div>
              <div class="banner-item">
                  <p>(2024-02) <strong>Won Hyeok Kim</strong>'s paper is accepted by the ICAIIC.</p>
              </div>
          </div>
        </body>
    design:
      columns: '1'
      
  
  - block: collection
    content:
      title: News
      subtitle:
      text:
      count: 5
      filters:
        author: ''
        category: ''
        exclude_featured: false
        publication_type: ''
        tag: ''
      offset: 0
      order: desc
      page_type: post
    design:
      view: card
      columns: '1'

##
  - block: collection
    content:
      title: Latest Preprints
      text: ""
      count: 5
      filters:
        folders:
          - publication
        publication_type: 'article'
    design:
      view: citation
      columns: '1'

---
