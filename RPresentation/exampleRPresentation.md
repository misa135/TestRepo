exampleRPresentation
========================================================
author: Misael Santana
date: 10/17/16
autosize: true

 Data Science Profile 
========================================================


```r
Category<-c("Computer Programming", "Math", "Statistics", "Machine Learning", "Domain Expertise", "Comunication and Presentation Skills", "Data Visualization")
Ranking<-c(4,4,2,1,4,3,3)
Misael <- data.frame(Category,Ranking)
Misael
```

```
                              Category Ranking
1                 Computer Programming       4
2                                 Math       4
3                           Statistics       2
4                     Machine Learning       1
5                     Domain Expertise       4
6 Comunication and Presentation Skills       3
7                   Data Visualization       3
```

```r
barplot(Misael$Ranking , xlab="" , ylab = "Ranking", main = "Misael" , col= "#009999")
text(seq(0.50,8,by=1.25),2,labels=Misael$Category,srt=90)
```

![plot of chunk unnamed-chunk-2](exampleRPresentation-figure/unnamed-chunk-2-1.png)


