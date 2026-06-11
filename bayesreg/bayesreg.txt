# Olah Data Semarang
# WhatsApp : +6285227746673
# IG : @olahdatasemarang_
#  Bayesian Regression Models with Continuous Shrinkage Priors Use bayesreg With (In) R Software
install.packages("bayesreg")
library("bayesreg")
# Estimate  Bayesian Regression Models with Continuous Shrinkage Priors Use bayesreg With (In) R Software
bayesreg = read.csv("https://raw.githubusercontent.com/timbulwidodostp/bayesreg_/main/bayesreg/bayesreg.csv",sep = ";")
bayesreg_1 <- bayesreg(bayesreg ~ bayesreg_1 + bayesreg_2 + bayesreg_3, bayesreg, prior = "hs", n.cores = 4)
bayesreg_1$n.cores
bayesreg_2 <- bayesreg(bayesreg ~ bayesreg_1 + bayesreg_2 + bayesreg_3, bayesreg, model = "gaussian", prior = "ridge", n.samples = 1e3)
bayesreg_3 <- bayesreg(bayesreg ~ bayesreg_1 + bayesreg_2 + bayesreg_3, bayesreg, model = "t", prior = "ridge", t.dof = 5, n.samples = 1e3)
bayesreg_1 <- summary(bayesreg_1)
bayesreg_2 <- summary(bayesreg_2)
bayesreg_3 <- summary(bayesreg_3)
#  Bayesian Regression Models with Continuous Shrinkage Priors Use bayesreg With (In) R Software
# Olah Data Semarang
# WhatsApp : +6285227746673
# IG : @olahdatasemarang_
# Finished