# workshop-NII


```{R Basics}

```
**Exercise (1 June, 2022)**

0. Create two vectors, one should be character vector and the other should be numeric vector. And, then compile it in a dataframe:

          ANSWER:
        > a <- c(1,2,3)
        > b <- c('aa','bb','cc')
        > a
        [1] 1 2 3
        > b
        [1] "aa" "bb" "cc"
        > D <- data.frame(x=a,y=b)
        > D
          x  y
        1 1 aa
        2 2 bb
        3 3 cc

1. Why does this code not work?

        my_fav_variable <- c('IL6','LINC','OAS1')
        my_fav_varıable
        #Error: object 'my_fav_varıable' not found
        
        ANSWER: The variable name is not the same. There is spelling mistake

2. Write a R code to create a character vector of your favorite pathway.

        # format ----- 
        # yourname_pathway <- c('gene 1', 'gene 2')
        # ------------
        # example (https://www.genome.jp/entry/N00151)
        # rk_tnf.nfkb <- c('TNF', 'TNFRSF1A', 'RIPK1', 'TRADD', 'TRAF2', 'TRAF5',
          'TAB1', 'TAB2', 'TAB3', 'MAP3K7', 'CHUK', 'IKBKB', 'IKBKG', 'NFKBIA',
          'NFKB1', 'RELA')
        # ------------ 
        
        ANSWER: 
        
        # https://www.genome.jp/entry/hsa00010
        > pathway = c("HK3","HK1","HK2","HKDC1","GCK","GPI","PFKM","PFKP","PFKL","FBP1","FBP2","ALDOC","ALDOA","ALDOB","TPI1","GAPDH","GAPDHS","PGK2","PGK1","PGAM1","PGAM2","PGAM4","ENO3","ENO2","ENO1","ENO4","PKM","PKLR","PDHA2","PDHA1","PDHB","DLAT","DLD","LDHAL6A","LDHAL6B","LDHA","LDHB","LDHC","ADH1A","ADH1B","ADH1C","ADH7","ADH4","ADH5","ADH6","AKR1A1","ALDH2","ALDH3A2","ALDH1B1","ALDH7A1","ALDH9A1","ALDH3B1","ALDH3B2","ALDH3A1","ACSS1","ACSS2","GALM","PGM1","PGM2","G6PC1","G6PC2","G6PC3","ADPGK","BPGM","MINPP1","PCK1","PCK2")
        > 
        > 
        > 
        > pathway
         [1] "HK3"     "HK1"     "HK2"     "HKDC1"   "GCK"     "GPI"    
         [7] "PFKM"    "PFKP"    "PFKL"    "FBP1"    "FBP2"    "ALDOC"  
        [13] "ALDOA"   "ALDOB"   "TPI1"    "GAPDH"   "GAPDHS"  "PGK2"   
        [19] "PGK1"    "PGAM1"   "PGAM2"   "PGAM4"   "ENO3"    "ENO2"   
        [25] "ENO1"    "ENO4"    "PKM"     "PKLR"    "PDHA2"   "PDHA1"  
        [31] "PDHB"    "DLAT"    "DLD"     "LDHAL6A" "LDHAL6B" "LDHA"   
        [37] "LDHB"    "LDHC"    "ADH1A"   "ADH1B"   "ADH1C"   "ADH7"   
        [43] "ADH4"    "ADH5"    "ADH6"    "AKR1A1"  "ALDH2"   "ALDH3A2"
        [49] "ALDH1B1" "ALDH7A1" "ALDH9A1" "ALDH3B1" "ALDH3B2" "ALDH3A1"
        [55] "ACSS1"   "ACSS2"   "GALM"    "PGM1"    "PGM2"    "G6PC1"  
        [61] "G6PC2"   "G6PC3"   "ADPGK"   "BPGM"    "MINPP1"  "PCK1"   
        [67] "PCK2" 
