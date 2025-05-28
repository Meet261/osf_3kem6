if (Sys.getenv("ENABLE_FLOWR") == "true") {
  message("ENABLE_FLOWR is true — installing FlowR addin...")

  if (!requireNamespace("remotes", quietly = TRUE)) {
    install.packages("remotes", repos = "https://cloud.r-project.org")
  }

  remotes::install_github("flowr-analysis/rstudio-addin-flowr@v0.1.2")
}
