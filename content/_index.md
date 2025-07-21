---
# Leave the homepage title empty to use the site title
title: ""
date: 2025-05-20
type: landing

design:
  # Default section spacing
  spacing: "1rem"

sections:
  - block: resume-biography-3
    content:
      # Choose a user profile to display (a folder name within `content/authors/`)
      username: jiboncom
      text: ""
      # Show a call-to-action button under your biography? (optional)
      button:
        text: JMP
        url: uploads/Boncompte-resume.pdf
    design:
      css_class: dark
      background:
        color: black
        image:
          # Add your image background to `assets/media/`.
          filename: stacked-peaks.svg
          filters:
            brightness: 1.0
          size: cover
          position: center
          parallax: true
  - block: markdown
    id: jmp
    content:
      title: 'Job Market Paper'
      subtitle: ''
      text: |-

        [**Partially Observed Reformulation and Equilibrium Effects of Corrective Taxes** ](uploads/Boncompte-resume.pdf)
        <br />[[{{< icon name="hero/inbox-arrow-down" >}} Download]](uploads/Boncompte-resume.pdf) 

        > Corrective taxes aim to align private choices with social costs but often fall short of reducing these costs. This paper examines the 2018 UK Soft Drinks Industry Levy and finds that its multi-tiered design led to a 22% drop in sugar intake from soft drinks, driven by higher prices and a 40% reduction in products’ sugar content. However, reformulation also affected unobserved product attributes that consumers value highly, such as taste. {{< toggler show-text="Show Full Abstract">}}
        Using a factor structure within an equilibrium model of product reformulation, I capture the endogenous link between sugar content and unobserved characteristics and estimate that reformulation prevented an additional 10% price increase, significantly reducing the tax burden on consumers, but at the cost of lower product quality. Smaller firms were more adversely affected, while larger firms adopted new technologies and reformulated a greater share of their portfolios. These results underscore how effective tax design can promote innovation and reduce the harm potential of products, lessening the need for further corrective measures and aligning economic efficiency with equity.
        {{< /toggler >}}
        

    design:
      columns: '1'
      css_style: ''
  - block: markdown
    id: papers
    content:
      title: 'Working Papers'
      subtitle: ''
      text: |-

        [**Growing in Foreign Markets: Customer Churning and Bilateral Bargaining** ](uploads/Boncompte-resume.pdf)
        <br />[[{{< icon name="hero/inbox-arrow-down" >}} Download]](uploads/Boncompte-resume.pdf)  *with Oscar Perello*
        
        {{< toggler >}}
        > Using a factor structure within an equilibrium model of product reformulation, I capture the endogenous link between sugar content and unobserved characteristics and estimate that reformulation prevented an additional 10% price increase, significantly reducing the tax burden on consumers, but at the cost of lower product quality. Smaller firms were more adversely affected, while larger firms adopted new technologies and reformulated a greater share of their portfolios. These results underscore how effective tax design can promote innovation and reduce the harm potential of products, lessening the need for further corrective measures and aligning economic efficiency with equity.
        {{< /toggler >}}

        [**Compatibility Choices of Websites and the Demand for Web Browsers** ](uploads/Boncompte-resume.pdf)
        <br />[[{{< icon name="hero/inbox-arrow-down" >}} Download]](uploads/Boncompte-resume.pdf)  *with Giussepe Forte*
        
        
        {{< toggler >}}
        > Using a factor structure within an equilibrium model of product reformulation, I capture the endogenous link between sugar content and unobserved characteristics and estimate that reformulation prevented an additional 10% price increase, significantly reducing the tax burden on consumers, but at the cost of lower product quality. Smaller firms were more adversely affected, while larger firms adopted new technologies and reformulated a greater share of their portfolios. These results underscore how effective tax design can promote innovation and reduce the harm potential of products, lessening the need for further corrective measures and aligning economic efficiency with equity.
        {{< /toggler >}}
        
        
    design:
      columns: '1'
      css_style: ''
  - block: markdown
    id: software
    content:
      title: 'Software'
      subtitle: ''
      text: |-

        [**PyInteractiveFixedEffects{{< icon name="hero/arrow-top-right-on-square" >}}**](https://github.com/jiboncom/pyInteractiveFixedEffects)
        
        Python implementation of several Interactive Fixed Effects (IFE) estimators for panel data. Includes methods for both balanced panels (Bai, 2009) and unbalanced panels (Bai et al., 2015; Cui et al., 2022), with a focus on computational efficiency.

        [**CORE Econ Interactive Lecture on Inflation {{< icon name="hero/arrow-top-right-on-square" >}}**](https://coreecon.github.io/voici/render/inflation.html?)

        Interactive lecture on inflation and central banks designed for [CORE Econ{{< icon name="hero/arrow-top-right-on-square" >}}](https://www.core-econ.org/), featuring dynamic visualizations and real-time Q&A powered by Voici; a free, open-source, serverless tool for delivering interactive R and Python simulations to large scale classrooms. Successfully tested with over 80 students simultaneously. 

    design:
      columns: '1'
      css_style: ''
---
