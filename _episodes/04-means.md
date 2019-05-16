---
title: "Understanding Mean Structure"
teaching: 10
exercises: 0
questions:
objectives:
keypoints: "Statistical thinking is essential to scientific thinking"
           "Blocking factors and experimental factors both influence a response" 
           
---

> ## forest exercise
> ~~~
> # import your data
> library(tidyverse)
> forest <- read_csv("data/forest.csv")
> str(forest)
> View(forest)
> ~~~
> {: .language-R}
>
> ~~~
> # visualise your data
> ggplot(forest, aes(x=QuadDiam, y=Density, colour=StandType)) +
>  geom_point()+
>  geom_smooth(method='lm', alpha=0.2)
> ~~~
> {: .language-R}
{% include links.md %}
