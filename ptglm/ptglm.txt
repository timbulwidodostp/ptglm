# Olah Data Semarang
# WhatsApp : +6285227746673
# IG : @olahdatasemarang_
# Poisson-Tweedie generalized linear model Use ptglm (ptmixed) With (In) R Software
install.packages("ptmixed")
install.packages("statmod")
install.packages("locfit")
install.packages("nor1mix")
install.packages("mclust")
install.packages("quantreg")
install.packages("https://raw.githubusercontent.com/timbulwidodostp/ptglm/main/ptglm/cqn_1.52.0.zip", repos=NULL, type="source")
install.packages("https://raw.githubusercontent.com/timbulwidodostp/ptglm/main/ptglm/edgeR_4.4.2.zip", repos=NULL, type="source")
install.packages("https://raw.githubusercontent.com/timbulwidodostp/ptglm/main/ptglm/limma_3.62.2.zip", repos=NULL, type="source")
install.packages("https://raw.githubusercontent.com/timbulwidodostp/ptglm/main/ptglm/tweeDEseq_1.52.0.zip", repos=NULL, type="source")
library("ptmixed")
ptglm = read.csv("https://raw.githubusercontent.com/timbulwidodostp/ptglm/main/ptglm/ptglm.csv",sep = ";")
# Estimation Poisson-Tweedie generalized linear model Use ptglm (ptmixed) With (In) R Software
ptglm = ptglm(formula = y ~ group*time, data = ptglm)
summary(ptglm)
# Poisson-Tweedie generalized linear model Use ptglm (ptmixed) With (In) R Software
# Olah Data Semarang
# WhatsApp : +6285227746673
# IG : @olahdatasemarang_
# Finished