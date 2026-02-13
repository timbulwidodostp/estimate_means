# Olah Data Semarang
# WhatsApp : +6285227746673
# IG : @olahdatasemarang_
# Estimate marginal means Use estimate_means (modelbased) With (In) R Software
install.packages("modelbased")
install.packages("marginaleffects")
install.packages("lme4")
library("modelbased")
library("marginaleffects")
library("lme4")
# Estimate marginal means Use estimate_means (modelbased) With (In) R Software
estimate_means = read.csv("https://raw.githubusercontent.com/timbulwidodostp/estimate_means/main/estimate_means/estimate_means.csv", sep = ";")
lm <- lm(Petal.Length ~ Sepal.Width * Species, data = estimate_means)
estimate_means <- estimate_means(lm)
estimate_means
# Estimate marginal means Use estimate_means (modelbased) With (In) R Software
# Olah Data Semarang
# WhatsApp : +6285227746673
# IG : @olahdatasemarang_
# Finished