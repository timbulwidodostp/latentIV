# Olah Data Semarang
# WhatsApp : +6285227746673
# IG : @olahdatasemarang_
# Fitting Linear Models with one Endogenous Regressor using Latent Instrumental Variables Use latentIV (REndo) With (In) R Software
install.packages("REndo")
library("REndo")
# Estimation Fitting Linear Models with one Endogenous Regressor using Latent Instrumental Variables Use latentIV (REndo) With (In) R Software
latentIV = read.csv("https://raw.githubusercontent.com/timbulwidodostp/latentIV/main/latentIV/latentIV.csv",sep = ";")
latentIV  <- latentIV(Dependen ~ Independen, data = latentIV)
summary(latentIV)
# Fitting Linear Models with one Endogenous Regressor using Latent Instrumental Variables Use latentIV (REndo) With (In) R Software
# Olah Data Semarang
# WhatsApp : +6285227746673
# IG : @olahdatasemarang_
# Finished