---
layout: archive
title: "Research"
permalink: /research/
author_profile: true
header:
  og_image: "images/Solid_black.png"
---

## Working Papers
*Note: Manuscripts for the following works are available upon request.*
- Quantifying Seller Revenue Impact on Two-sided Digital Market: A Network-Based Deep Learning Approach.
    - *with* Yi Zhao, Ying Zhao
    - **Job Market Paper**
        - <small> **Abstract** A key decision for two-sided digital platforms involves the selection of sellers to host, as the right sellers offering suitable products are crucial for attracting and retaining customers, thereby driving revenue growth. Platforms typically assess sellers based on their revenue contributions, which are influenced by the market relationships among sellers and buyers. A unit-based approach to evaluate a seller’s revenue contribution can lead to biased conclusions, as it does not account for the interdependence among sellers and buyers, where a seller’s performance is influenced by both its own actions and its interactions within the platform’s network. This paper proposes a network-based approach that captures the sellers’ revenue contributions to the platform, considering the interdependencies among sellers and buyers. The approach integrates multiple machine learning methods, including Variational Autoencoders (VAE), Graph Neural Networks (GNN), and Gated Recurrent Units (GRU). This allows us to analyze how the seller-seller, buyer-buyer and seller-buyer interconnectedness, as well as the evolution of these connections over time, affect a seller’s revenue contribution to the platform. By applying this method to a major food delivery platform in China, we find that our proposed model that accounts for network effects outperforms the non-network-based models. Counterfactual experiments based on the estimated model provide insights into the platform’s strategies for inviting new sellers and the strategies of sellers in product offerings.

- How News from Different Media Channels Shape Consumer Purchase: Causal Evidence from the Chinese Pharmaceutical Market.
    - *with* Ying Zhao, Yi Zhao, Yang Shi
    - Reject & Resubmit at **Marketing Science**
        - <small> **Abstract** Inferring the causal impact of news on consumer preference is challenging due to potential endogeneity issues, such as omitted variable bias and reverse causality. We leverage the unique context of the pharmaceutical market in China during COVID-19, characterized by high intensity and variation in news coverage across time and media channels regarding the effectiveness of Chinese medicine in combating COVID-19, to make causal inferences about the differing impacts of news from various channels (TV, online news platforms and social media) on consumer preferences and purchasing behaviors in the pharmaceutical categories unrelated to COVID-19. During this period, a significant portion of news coverage is driven by external events related to research breakthroughs and clinical findings on the effectiveness of Chinese medicine. This provides strong instrument variables that enable us to address endogeneity concerns in making causal inferences. Our findings suggest that the three media channels affect consumer purchases differently. The popularity of news about Chinese medicine from social media, irrespective of its sentiment, positively affects the sales of Chinese medicine. In contrast, both the popularity and positivity of news from online news platforms play a positive role. Further analysis suggests that these effects exhibit different interactive patterns with consumers’ pre- existing preferences.

- Show Me Some Effort! The Effect of Liking versus Comments and Their Presentation Format on User-Generated Content.
    - *with* Ying Zhao, Min Zhao
         - <small> **Abstract** Motivated by the challenge of content under-provision on the User-Generated Content (UGC) platforms, the current work draws upon research on reciprocation and unpacking to examine the differentiating effects of likes versus comments on creators’ content-generation behavior. Using field data from NetEase Cloud Music (NCM), the authors demonstrate that comments from viewers are more effective at eliciting subsequent content generation compared with likes. Two follow-up experiments further examine how different presentation formats of feedback impact creators’ reactions, and show that unpacked presentation (i.e., displaying aggregated feedback as separate individual feedbacks) increases positive attitude and content generation of the creators. In addition, the experiments identify perceived effort as the underlying process by testing its mediating role (Experiment 1) or manipulating effort involved in comments and showing the attenuation of unpacking effect for low-effort comments (Experiment 2). This research provides insights into the motivation behind UGC and offers interesting implications on designing feedback mechanisms that better engage both viewers and content generators on UGC platforms.

- Ride The Wave or Not? The Spillover Effect of Online Shopping Festivals and Best Timing for Advertising.
    - *with* Xiaobei Shen, Xiabing Zheng
        - <small> **Abstract** This study investigates the spillover effect of online shopping festivals (hosted by e-commerce platforms) on viewers’ reactions to short-video advertising (on media platforms) using a natural experiment. As e-commerce shopping festivals are now spanning longer periods, coupled with firms having the ability to customize the release time of short-video ads on media platforms, it is valuable to explore how the spillover effect changes over time. We do find the existence of the spillover effect. During the warm-up and general-promotion periods of the shopping festival, the spillover effect is positive, resulting in increased click-through rates of ads. However, during the peak-promotion and post-promotion periods, the spillover effect becomes negative. We explain the spillover effect as a joint result of the stimulating effect of the festival’s environmental cues and the inhibiting effect of financial constraints on consumers. The proposed theoretical mechanisms are verified through a field experiment and a post-hoc analysis. As firms can tailor the time to release their ads, they may ride the wave of exogenous e-commerce shopping festivals, but shall carefully choose the best timing for their advertising on media platforms.


<!---
<nbsp>

{% include base_path %}

{% assign ordered_pages = site.research | sort:"order_number" %}

{% for post in ordered_pages %}
  {% include archive-single.html type="grid" %}
{% endfor %}
-->
