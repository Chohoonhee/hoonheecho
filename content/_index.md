---
# Leave the homepage title empty to use the site title
title: ''
date: 2022-10-24
type: landing

design:
  # Default section spacing
  spacing: '6rem'

sections:
  - block: resume-biography-3
    content:
      # Choose a user profile to display (a folder name within `content/authors/`)
      username: admin
      text: ''
      # Show a call-to-action button under your biography? (optional)
      button:
        text: Download CV
        url: uploads/cv_251129.pdf
      headings:
        about: ''
        education: ''
        interests: ''
    design:
      # Apply a gradient background
      css_class: hbx-bg-gradient
      # Avatar customization
      avatar:
        size: medium # Options: small (150px), medium (200px, default), large (320px), xl (400px), xxl (500px)
        shape: circle # Options: circle (default), square, rounded
  # - block: collection
  #   id: papers
  #   content:
  #     title: Recent Publications
  #     filters:
  #       folders:
  #         - publication
  #       featured_only: true
  #   design:
  #     view: article-grid
  #     columns: 3
  # - block: collection
  #   id: papers
  #   content:
  #     title: Recent Publications        # 이름도 원하면 여기서 변경
  #     filters:
  #       folders:
  #         - publication
  #       featured_only: true               # featured=true 인 논문만
  #   design:
  #     view: card                          # ✅ 핵심: article-grid → card
  #     columns: 3                          # 데스크탑에서 3개 카드씩
  #     spacing:
  #       padding: 1.5rem                   # 위아래 여백 조금
  # - block: collection
  #   id: papers
  #   content:
  #     title: Recent Publications
  #     filters:
  #       folders:
  #         - publication
  #       featured_only: true
  #   design:
  #     view: article-grid   # 우리가 방금 고친 view
  #     columns: "3"
  - block: markdown
    id: recent-pubs
    content:
      title: "Recent Publications"
      subtitle: ""
      text: '{{< recent-pubs >}}'




  - block: collection
    content:
      title: All Publications
      text: ''
      # 0 = 모든 publication 다 보여주기
      count: 0
      # "See all publications" 버튼 끄기
      archive:
        enable: false
      filters:
        folders:
          - publication
        exclude_featured: false
    design:
      view: citation



  
      
  - block: markdown
    content:
      title: '📚 Academic Service'
      subtitle: ''
      text: |-
        <div class="text-sm leading-relaxed">
          I have been serving the research community as a reviewer for:

          <ul class="list-disc ml-6">
            <li>2021 · IEEE Transactions on Instrumentation & Measurement</li>
            <li>2023 · AAAI Conference on Artificial Intelligence (AAAI)</li>
            <li>2023 · International Conference on Computer Vision (ICCV)</li>
            <li>2024 · AAAI Conference on Artificial Intelligence (AAAI)</li>
            <li>2024 · IEEE/CVF Conference on Computer Vision and Pattern Recognition (CVPR)</li>
            <li>2024 · IEEE Transactions on Pattern Analysis and Machine Intelligence (TPAMI)</li>
            <li>2024 · European Conference on Computer Vision (ECCV)</li>
            <li>2025 · AAAI Conference on Artificial Intelligence (AAAI)</li>
            <li>2025 · IEEE/CVF Conference on Computer Vision and Pattern Recognition (CVPR)</li>
            <li>2025 · IEEE Transactions on Pattern Analysis and Machine Intelligence (TPAMI)</li>
            <li>2025 · International Conference on Computer Vision (ICCV) (Outstanding Reviewers)</li>
            <li>2025 · Conference on Neural Information Processing Systems (NeurIPS) (Top Reviewers)</li>
            <li>2026 · AAAI Conference on Artificial Intelligence (AAAI)</li>
            <li>2026 · IEEE Transactions on Pattern Analysis and Machine Intelligence (TPAMI)</li>
          </ul>
        </div>

  #     text: |-
  #       <div style="font-size:1.0rem;">
  #       I have been serving the research community as a reviewer for:

  #       <ul style="list-style-position: outside; padding-left: 1.5rem; white-space: nowrap;">
  #         <li>2021 · IEEE Transactions on Instrumentation & Measurement</li>
  #         <li>2023 · AAAI Conference on Artificial Intelligence (AAAI)</li>
  #         <li>2023 · International Conference on Computer Vision (ICCV)</li>
  #         <li>2024 · AAAI Conference on Artificial Intelligence (AAAI)</li>
  #         <li>2024 · IEEE/CVF Conference on Computer Vision and Pattern Recognition (CVPR)</li>
  #         <li>2024 · IEEE Transactions on Pattern Analysis and Machine Intelligence (TPAMI)</li>
  #         <li>2024 · European Conference on Computer Vision (ECCV)</li>
  #         <li>2025 · AAAI Conference on Artificial Intelligence (AAAI)</li>
  #         <li>2025 · IEEE/CVF Conference on Computer Vision and Pattern Recognition (CVPR)</li>
  #         <li>2025 · IEEE Transactions on Pattern Analysis and Machine Intelligence (TPAMI)</li>
  #         <li>2025 · International Conference on Computer Vision (ICCV) (Outstanding Reviewers)</li>
  #         <li>2025 · Conference on Neural Information Processing Systems (NeurIPS) (Top Reviewers)</li>
  #         <li>2026 · AAAI Conference on Artificial Intelligence (AAAI)</li>
  #       </ul>
  #       </div>
  #   design:
  #     columns: '1'
  #     spacing:
  #       padding: 0.5rem

  - block: markdown
    content:
      title: '🏅 Honors & News'
      subtitle: ''
      text: |-
        <div style="font-size:1.0rem;">
        <ul style="list-style-position: outside; padding-left: 1.5rem;">
          <li>
            <strong>IEEE SPECTRUM News, August 2021</strong><br>
            Event-based Omnidirectional Multi-view Stereo (EOMVS) was introduced in IEEE Spectrum,
            “This Camera Can ‘See’ the Bigger Picture: Researchers’ new camera spots fast-moving objects over a wide angle of view.”
          </li>
          <li>
            <strong>Vision Systems Design Main News, November 2021</strong><br>
            EOMVS introduced as a main news article in Vision Systems Design.
          </li>
          <li>
            <strong>MBZIRC Final Team, December 2022</strong><br>
            Finalist team in the Mohamed Bin Zayed International Robotics Challenge (MBZIRC).
          </li>
          <li>
            <strong>Recipient of the KAIST KI Excellent Researcher Award, 2024</strong><br>
            Awarded by KAIST KI to outstanding researchers with notable research achievements.
          </li>
          <li>
            <strong>Qualcomm Innovation Fellowship (QIF) Finalist, 2025</strong><br>
            Selected as a finalist for innovative PhD-level research proposals by Qualcomm, representing South Korea.
          </li>
        </ul>
        </div>
    design:
      columns: '1'
      spacing:
        padding: 0.5rem



  - block: cta-card
    demo: true # Only display this section in the Hugo Blox Builder demo site
    content:
      title: 👉 Build your own academic website like this
      text: |-
        This site is generated by Hugo Blox Builder - the FREE, Hugo-based open source website builder trusted by 250,000+ academics like you.

        <a class="github-button" href="https://github.com/HugoBlox/hugo-blox-builder" data-color-scheme="no-preference: light; light: light; dark: dark;" data-icon="octicon-star" data-size="large" data-show-count="true" aria-label="Star HugoBlox/hugo-blox-builder on GitHub">Star</a>

        Easily build anything with blocks - no-code required!

        From landing pages, second brains, and courses to academic resumés, conferences, and tech blogs.
      button:
        text: Get Started
        url: https://hugoblox.com/templates/
    design:
      card:
        # Card background color (CSS class)
        css_class: 'bg-primary-300 dark:bg-primary-700'
        css_style: ''
---
