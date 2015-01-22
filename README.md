#the first line is equal to all questions
tab = read.csv("msleep_ggplot2.csv")
#question1
colnames(tab)
tab$sleep_total
#question2
summary(tab$sleep_total)
#question3
mean(tab$sleep_total[ tab$sleep_total > 18 ])
#question4
which(tab$sleep_total > 18 & tab$sleep_rem < 3)
#question5
order(tab$sleep_total)
#question6
rank(tab$sleep_total)
#question7
match("Cotton rat", tab$name)
#question8
table(tab$order)
#question9
mean(s[["Rodentia"]])
#question10
tapply(tab$sleep_total, tab$order, sd)
