---
title: Home
sections:
  - type: hero_section
    title: PID Tuning
    subtitle: A modern approach via the Weighted Sensitivity Problem
    content: >
      This is a book on PID tuning with emphasis on analytical procedures. The
      main objective is to show how robustness, performance, and
      servo/regulation requirements translate into the tuning expressions. As
      for the Weighted Sensitivity Problem formulation, we the authors have
      found that it serves the main purpose very well, allowing us to blend
      ideas from H∞ and IMC theories. So, the book can also serve as an
      introduction to these more advanced topics.
    actions:
      - label: Buy Now
        url: 'https://www.amazon.com/dp/036734372X'
        style: primary
        has_icon: false
        icon: arrow-right
        icon_position: right
    image: images/9780367343729.tif
    image_alt: Marketing Playbook preview
    media_position: left
    media_width: fourty
    align: left
    padding_top: large
    padding_bottom: large
    background_color: none
  - type: features_section
    features:
      - title: Highlights
        content: "The PID controller is the most common option in the realm of control applications and is dominant in the process control industry. Among the related analytical methods, Internal Model Control (IMC) has gained remarkable industrial acceptance due to its robust nature and good set-point responses. However, the traditional application of IMC results in poor load disturbance rejection for lag-dominant and integrating plants. This book presents an IMC-like design method which avoids this common pitfall and is devised to work well for plants of modest complexity, for which analytical PID tuning is plausible. For simplicity, the design only focuses on the closed-loop sensitivity function, including formulations for the H∞\_and H2\_norms. Aimed at graduate students and researchers in control engineering, this book:\n\n*   Considers both the robustness/performance and the servo/regulation trade-offs\n*   Presents a systematic, optimization-based approach, ultimately leading to well-motivated, model-based, and analytically derived tuning rules\n*   Shows how to tune PID controllers in a unified way, encompassing stable, integrating, and unstable processes\n*   Finds in the Weighted Sensitivity Problem the sweet spot of robust, optimal, and PID control\n*   Provides a common analytical framework that generalizes existing tuning proposals\n"
        actions:
          - label: Learn more
            url: >-
              https://www.ifac2020.org/fileadmin/public/Redaktion/Dokumente/Workshopslides/Slides_Workshop_Vilanova.pdf
            style: primary
            has_icon: true
            icon: arrow-right
            icon_position: right
        image: images/PID Tuning (4).png
        image_alt: Look inside Marketing Playbook
        media_position: right
        media_width: fifty
    feature_padding_vert: small
    align: center
    background_color: none
  - type: features_section
    features:
      - title: >-
          “The analytical method proposed by the book yields good performance,
          is motivated by a rigorous framework, and simplifies the design
          process as much as possible. This is the concern of engineers.”
        subtitle: 'Professor Weidong Zhang, Shanghai Jiao Tong University'
        image: images/weidong.jpg
        image_alt: Brandon Guidelines
        media_position: left
        media_width: thirty-three
    feature_padding_vert: small
    background_color: primary
    background_image: images/tuning-sample.svg
    background_image_repeat: no-repeat
    background_image_size: cover
    background_image_opacity: 10
  - type: grid_section
    title: Full Chapter  Overview
    grid_items:
      - content: >
          ### Introduction


          The book starts with a bird's-eye view of the contents. This chapter
          serves as a summary of the main ideas within the chapters to come.
          Although the book has been laid out to be read linearly, this elevated
          view will help you decide the exact route you want to follow,
          depending on your background and interests.
      - content: >
          ### Simple model-matching approach to robust PID design


          A servo-oriented design is presented under the light of the simplest
          Model Matching Problem. The resulting PID tuning rules are very
          similar to the Lambda Tuning ones.
      - content: >
          ### Alternative design for load disturbance improvement


          In the previous chapter, we obtained tuning rules aimed at good
          set-point responses. However, as it happens with traditional IMC-based
          tuning rules, the response to load disturbances can be sluggish. This
          chapter proposes a modified Model Matching Problem which is better for
          regulatory purposes. A new parameter, Gamma, is introduced.
      - content: >
          ### Analysis of the smooth/tight-servo/regulation tuning approaches


          It makes sense to compare the two approaches seen so far. The first
          one, as in traditional IMC, is referred to as Lambda Tuning, while the
          second one is called Gamma Tuning. This chapter explores the limits of
          each approach.
      - content: >
          ### H∞ design with application to PI tuning


          Based on the accumulated know-how, this chapter proposes a new design
          which combines the strenghts of both the Lambda and Gamma Tuning
          approaches. The formulation relies on the H∞, or supremum, norm. For
          simplicity, the discussion considers the application to PI tuning
          only, leaving the more general PID case for later.
      - content: >
          ### Generalized IMC design and H2 approach


          The IMC design philosophy, sometimes called Lambda Tuning in the PID
          context, is very popular within the control community. How does the
          proposed method compare to conventional IMC? In particular, this
          chapter presents an interpretation of the proposed sensitivity weight
          in terms of IMC filters. To make the analogy closer, the design is
          reformulated using the H2 norm.
      - content: >
          ### PID design as a Weighted Sensitivity Problem


          This chapter retakes the H∞ design to consider the full PID case.
          Tuning rules are given for the most typical first and second order
          models found in practice.
      - content: >
          ### PID tuning guidelines for balanced operation


          Finally, how to tune the two knobs at hand, namely Lambda and Gamma,
          in order to obtain a *balanced* closed-loop? This is the question
          tackled in this final chapter.
    grid_cols: two
    grid_gap_horiz: medium
    grid_gap_vert: small
    enable_cards: false
    align: center
    background_color: none
  - type: grid_section
    title: Who Should Read This Book?
    grid_items:
      - content: |
          #### Undergraduate students

          *   Learn about PID control
          *   Tackle robustness/performance issues
          *   Tackle servo/regulation issues
          *   Gain insight into the tuning task
      - content: |
          #### Graduate students

          *   Learn about H∞ and IMC methodologies
          *   Understand their shortcomings and limitations
          *   Systematically blend those approaches
          *   Go from classic to more advanced control theory
      - content: |
          #### Control researchers

          *   Review basic optimal and robust control theory
          *   Review PID tuning from optimal and robust principles
          *   Review existing methods in the literature
          *   Inspire new designs
      - content: |
          #### Control practitioners

          *   Learn optimal and robust control at the PID level
          *   Consider new tuning rules
          *   Compare with Lambda Tuning, Ziegler–Nichols, etc
          *   Benefit from additional insights
    grid_cols: two
    grid_gap_horiz: medium
    grid_gap_vert: large
    align: center
    background_color: primary
    background_image: images/norbert_wiener.jpg
    background_image_repeat: no-repeat
    background_image_size: cover
    background_image_opacity: 10
  - type: features_section
    features:
      - title: Why This Book
        subtitle: 'Salva Alcántara, PhD'
        content: >
          **Feedback Control is ubiquitous.** Lately, it has even started to pop
          up in more unexpected places, such as in software systems under the
          guise of reconciliation-engine techniques, e.g.,
          [Kubernetes](https://kubernetes.io/docs/concepts/architecture/controller/),
          which, for those who don't know, essentially means
          [Cybernetics](https://en.wikipedia.org/wiki/Cybernetics).


          > **It's interesting how reconciliation-engine techniques have become
          widespread. React.js for UI, Kubernetes for container fleets,
          Cloudformation/Terraform for cloud resources. I wonder where else
          these techniques can be used?"—Li Haoyi** (see the original
          [tweet](https://twitter.com/li_haoyi/status/1274844647966117888?s=20))


          Definitely, there is still room for truly original and unconventional
          applications of the feedback principle. You and I will witness that in
          the years to come. In the meantime, in this short book I am sharing
          with you how to tune PID controllers, by far the most common form of
          feedback, in order to obtain *well-balanced* loops in a rather
          unconventional—somewhat original—way. Ultimately, I am quite confident
          that the book will be useful and interesting to a wide audience.
        image: images/myFace.jpg
        image_alt: Brandon Guidelines Photo
        media_position: right
        media_width: fourty
    feature_padding_vert: small
    align: center
    background_color: none
  - type: cta_section
    title: Get the book and stay tuned!
    actions:
      - label: Buy Now
        url: 'https://www.amazon.com/dp/036734372X'
        style: primary
    actions_position: bottom
    align: center
    padding_top: large
    padding_bottom: large
    background_color: primary
    background_image: images/Screenshot 2021-03-03 at 04.12.13.png
    background_image_repeat: no-repeat
    background_image_size: cover
    background_image_opacity: 10
seo:
  title: PID Tuning
  description: PID Tuning preview
  extra:
    - name: 'og:type'
      value: website
      keyName: property
    - name: 'og:title'
      value: PID Tuning
      keyName: property
    - name: 'og:description'
      value: PID Tuning preview
      keyName: property
    - name: 'og:image'
      value: images/9780367343729.tif
      keyName: property
      relativeUrl: true
    - name: 'twitter:card'
      value: summary_large_image
    - name: 'twitter:title'
      value: PID Tuning
    - name: 'twitter:description'
      value: PID Tuning preview
    - name: 'twitter:image'
      value: images/book-preview.png
      relativeUrl: true
template: advanced
---
