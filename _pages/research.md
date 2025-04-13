---
layout: archive
title: "Research"
permalink: /research/
author_profile: true
header:
  og_image: "images/Solid_black.png"
---

## Working Papers
- Demand Structure in Two-Sided Markets: A Network Based Revenue Analysis Approach.
    - *with* Yi Zhao, Ying Zhao
    - **Job Market Paper**
        - <small> **Abstract** Online food delivery platforms, a typical two-sided market, can be viewed as a network structure where restaurants serve multiple areas, and various areas are served by numerous of restaurants on the platform. Within this network structure, the revenue contribution of a restaurant to the platform depends not only on its own generated income, but also on the revenue impacts it has on other restaurants through the network. Similarly, the revenue impact of a new product offering to a restaurant may vary depends on the restaurant type and its position in the network. This paper proposes a network-based machine learning approach that integrates Variational Autoencoders (VAE), Graph Neural Networks (GNN), and Gated Recurrent Units (GRU) to capture the structure of the revenue in the two-sided markets, using online food delivery platform as an empirical context. VAE is employed to extract interpretable dimensions from the high-dimensional input vectors, GNN captures the network in the two-sided market considering multiple types of relationships, while GRU handles the network dynamics. The proposed model allows the platform to evaluate a seller by considering both its direct revenue generation and its revenue impact on neighboring sellers. Using the model structure, the platform can also assess the revenue impact of sellers’ product offerings considering those offered by neighboring sellers. Simulations exercises based on the estimated model provides insights into platform’s strategies for inviting new seller, as well as recommendations for product offerings to existing sellers on the platform.
        
- The Influence of News from Different Media Channels on Consumer Purchase: Insights from the Chinese Pharmaceutical Market.
    - *with* Ying Zhao, Yi Zhao, Yang Shi
        - <small> **Abstract** As news consumption increasingly shifts from traditional outlets to digital platforms, understanding the diverse roles that news from different media channels plays in shaping consumer behavior is essential. Using a unique dataset comprising weekly news content and sales data across multiple cities from the pharmaceutical market in China during the Covid-19 pandemics, we study the influence of news from television, online commercial news platforms, and social media regarding the effectiveness of Chinese medicine in combating COVID-19 on consumer preferences for Chinese versus Western drugs in pharmaceutical categories that are not associated with the pandemic. This unique empirical setting allows for the alleviation of endogeneity concerns. Our findings suggest that popularity of news, irrespective of news sentiment, on social media and online news platforms positively influence consumer preference for the focal product. Additionally, positive news from television and online news platform contributes to the increased sales of the focal products. Further analysis suggests that these effects exhibit different interactive patterns with consumers’ pre-existing preferences. Finally, the authors conduct simulation exercises based on estimation results and provide insights to managers on promotional and media planning.

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
