# code



refine$company[refine$company == "philips"] <- "Phillips"
refine$company[refine$company == "phllips"] <- "Phillips"
refine$company[refine$company == "phillps"] <- "Phillips"
refine$company[refine$company == "philipS"] <- "Phillips"
refine$company[refine$company == "phillipS"] <- "Phillips"

refine$company[refine$company == "akz0"] <- "Akzo"
refine$company[refine$company == "ak zo"] <- "Akzo"
refine$company[refine$company == "unilver"] <- "Unilever"

refine$company[refine$company == "fillips"] <- "Phillips"
refine$company[refine$company == "phlips"] <- "Phillips"
