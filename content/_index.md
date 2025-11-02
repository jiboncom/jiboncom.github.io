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
        url: boncompte-jmp.pdf
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

        [**Shaping More Than Prices: Corrective Taxes with Product Reformulation** ](boncompte-jmp.pdf)
        <br />[[{{< icon name="hero/inbox-arrow-down" >}} Download]](boncompte-jmp.pdf) 

        > How do corrective taxes work when firms can reformulate products to avoid them? I develop an equilibrium model of product reformulation to study product responses to the 2018 UK Soft Drinks Industry Levy, a multi-tiered tax targeting excessive sugar content. The model isolates the role of reformulation by using interactive fixed effects to account for multiple endogenous unobserved product characteristics, allowing counterfactuals that revert products to their pre-reformulation attributes. I find the levy reduced sugar sales by 22% and led firms to reformulate more than one-third of products, cutting average sugar content by 40% while lowering product quality, differentiation and tax liabilities. Reformulation benefits nearly all consumers, with gains concentrated among lower-income households and modest losses at the top. Larger firms reformulate a greater share of their products and protect profits more effectively than smaller ones. Overall, reformulation reduced sugar intake relative to a no-tax baseline but also constrained the tax’s ability to further curb consumption. My results show product responses are first-order for welfare and harm reduction, and that multi-tier taxes leverage them more effectively than the non-tiered taxes commonly applied to sugar-sweetened beverages. 
    #{{< toggler show-text="Show Full Abstract">}}{{< /toggler >}} 

    design:
      columns: '1'
      css_style: ''
  - block: markdown
    id: papers
    content:
      title: 'Working Papers'
      subtitle: ''
      text: |-

        [**Customer Uptrading, Relational Frictions, and Exporters’ Growth** ](BP-exporters.pdf)
        <br /> [[{{< icon name="hero/inbox-arrow-down" >}} Download]](BP-exporters.pdf) *with Oscar Perello*
        
        {{< toggler >}}
        > How do exporters grow their customer networks when maintaining relationships is costly? We study the role of customer churning in exporters’ growth. Using detailed firm-to-firm data from Chilean customs, we show that fast-growing exporters systematically drop buyers that purchase smaller volumes and replace them with large customers, a process we term *Customer Uptrading*. A formal decomposition reveals that uptrading, rather than selling more to existing customers or expanding the number of buyers, is the main driver of exporters’ growth. Exploiting variation in direct flight availability, we find that exporters maintain longer relationships when better connected to their buyers, linking uptrading to the upkeep costs of managing multiple trade relationships. We rationalize these findings with a dynamic model of network formation in which firms engage in costly customer search and actively decide which relationships to keep or sever, taking into account the upkeep costs of their network. The model predicts that more productive firms both search more intensively and replace more customers than less productive ones, highlighting the central role of search in exporters’ growth and also its limits.
        {{< /toggler >}}

        <hr style="margin: 1rem 0;" />

        **The Diffusion of Tracking Technologies and the Online Advertising Market**
        <br />*with Simeon Duckworth, Giuseppe Forte, and Lars Nesheim*
        
        
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

        <hr style="margin: 1rem 0;" />

        [**CORE Econ Interactive Lecture on Inflation {{< icon name="hero/arrow-top-right-on-square" >}}**](https://coreecon.github.io/voici/render/inflation.html?)

        Interactive lecture on inflation and central banks designed for [CORE Econ{{< icon name="hero/arrow-top-right-on-square" >}}](https://www.core-econ.org/), featuring dynamic visualizations and real-time Q&A powered by Voici; a free, open-source, serverless tool for delivering interactive R and Python simulations to large scale classrooms. Successfully tested with over 80 students simultaneously. 

    design:
      columns: '1'
      css_style: ''
---
