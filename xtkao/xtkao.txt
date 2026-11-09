# Olah Data Semarang
# WhatsApp : +6285227746673
# IG : @olahdatasemarang_
# Kao (1999) Panel Cointegration Tests Use xtkao (paneltests) With (In) R Software
install.packages("paneltests")
library("paneltests")
# Estimate Kao (1999) Panel Cointegration Tests Use xtkao (paneltests) With (In) R Software
xtkao = read.csv("https://raw.githubusercontent.com/timbulwidodostp/xtkao/main/xtkao/xtkao.csv",sep = ";")
xtkao <- xtkao(xtkao, xtkao ~ xtkao_, index = c("id", "t"), kernel_lags = 1)
xtkao
# Kao (1999) Panel Cointegration Tests Use xtkao (paneltests) With (In) R Software
# Olah Data Semarang
# WhatsApp : +6285227746673
# IG : @olahdatasemarang_
# Finished