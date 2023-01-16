# POIBERT: A Transformer-based Model for the Tour Recommendation Problem
### Ngai Lam Ho, Kwan Hui Lim


Tour itinerary planning and recommendation are challenging problems for tourists visiting unfamiliar cities. Many tour recommendation algorithms only consider factors such as the location and popularity of Points of Interest (POIs) but their solutions may not align well with the user's own preferences and other location constraints. Additionally, these solutions do not take into consideration of the users' preference based on their past POIs selection. In this paper, we propose POIBERT, an algorithm for recommending personalized itineraries using the BERT language model on POIs. POIBERT builds upon the highly successful BERT language model with the novel adaptation of a language model to our itinerary recommendation task, alongside an iterative approach to generate consecutive POIs.

Our recommendation algorithm is able to generate a sequence of POIs that optimizes time and users' preference in POI categories based on past trajectories from similar tourists. Our tour recommendation algorithm is modeled by adapting the itinerary recommendation problem to the sentence completion problem in natural language processing (NLP). We also innovate an iterative algorithm to generate travel itineraries that satisfies the time constraints which is most likely from past trajectories. Using a Flickr dataset of seven cities, experimental results show that our algorithm out-performs many sequence prediction algorithms based on measures in recall, precision and F1-scores.

Accepted to the 2022 IEEE International Conference on Big Data (BigData2022)

Paper: https://arxiv.org/abs/2212.13900

Source code: https://github.com/nxh912/POIBERT_IEEE_Bigdata22
