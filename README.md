# Estimating basins of attraction

The following github repository holds the data and code to estimate basins of attraction around sleeping sites, and serves to support the scientific article: 

**Sleeping sites as basins of attraction: when and where are movements more predictable?**

**Abstract**:	

   Animals’ use of space can have important implications for fitness. There is increasing interest in the drivers of space use and the ecological consequences of resulting spatial patterns, many of which are relevant to the conservation and management of wild populations. One pattern that has so far received little attention is the degree to which movement over the landscape is predictable. This can be quantified in both time and space, where, for example, more predictable movements are seen in certain regions and/or at particular times. To test for structure in movement predictability, and to highlight its relevance as an exploratory approach to identify hot spots of predictability, we make use of movement data from a long-term study of Assamese macaques (Macaca assamensis). We use these data, and a generalized additive modelling approach, to quantify and visualize the predictability of habitat use in both space and time. We then compare patterns of predictability between observed and simulated movements to test whether patterns of predictability can be explained by the group choosing a sleeping site based on proximity alone. We found that the group showed a distinct cone-shaped pattern of predictable habitat use in space and time, with reduced predictability earlier in the day and as distance from a potential sleeping site increased. We also found variation in predictability between sleeping sites, with predictability varying more than expected relative to sleeping site choice based on proximity alone. We suggest that the ability to quantify structure in the predictability of movement raises questions regarding both the role of the social and physical environment in shaping movement, and the potential consequences of there being areas and times where movements are more predictable.

</br>
</br>

<p align="center">
<img src="https://github.com/tbonne/basins_of_attraction/blob/main/images/observed_tracks_sep22_2023.png" width="75%" height="75%" align="center">
   </p>

*Figure 3: a) Basins of attraction around each sleeping site based on simulated movement and random sleeping site choice. Points are added where the model predicts with >80% probability that the group will sleeping at a sleeping tree. Sleeping tree sites are colour coded. The time axis provides the prediction at hourly intervals, from 8am to 6pm. b) Simulated group movement using a biased correlated random walk model fit to the observed data.*

</br>
</br>

<p align="center">
<img src="https://github.com/tbonne/basins_of_attraction/blob/main/images/BasinDiff_2.png" width="75%" height="75%" align="center">
   </p>

*Figure 5: Region where the probability of sleeping at a particular site is >80% and differed between the simulated and observed basins of attraction: a) time = 11:00, b) time = 13:00, c) time = 15:00, and d) time = 17:00.  Orange points represent areas which are predicted to lead to a sleeping site with >80% probability in the observed but not the simulated basin of attraction (surrounding a hot spot). Blue points represent areas which are predicted to lead to a sleeping site with >80% probability in the simulated but not the observed basin of attraction (cold spot). Finally, grey points represent areas of similar predictability across both basins of attraction. Sleeping sites are represented as solid white points with labels.*






