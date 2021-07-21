# Analyze
grades

## Density plot

### plot.new()

### plot(density(df$var), 
         col="color",
         main="title",
         xlab="", ylab="",
         ylim=c())

### dev.off()

## Histogram

### hist(x=df$var,
        density=25,
        col="color",
        main="title",
        xlab="", ylab="")

## Load data

### df <- read.csv(file="file.csv",
               sep=",",
               header=TRUE)

### str(df)

## Summary statistics

### summary()

## Panels

### par(mfrow=c(rows,cols)

## Legend

### legend("topright",
       legend=c("item 1", "item 2")
       col=c("col 1", "col 2),
       lty=1)

