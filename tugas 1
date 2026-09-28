x <- c(3, 7, 2, 9, 5)
{
  x_urut <- sort(x)
  banyak_data <- length(x)

  if (banyak_data %% 2 == 0) {
    med <- mean(x_urut[c(banyak_data / 2, (banyak_data / 2) + 1)])
  } else {
    med <- x_urut[(banyak_data + 1) / 2]
  }

  print(paste("Median dari data adalah:", med))
  return(med)
}
 
