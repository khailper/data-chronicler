if (file.exists("~/.Rprofile")) {
  base::sys.source("~/.Rprofile", envir = environment())
}

options(
  blogdown.author = "Karl Hailperin",
  blogdown.ext = ".Rmd",
  blogdown.subdir = "post",
  blogdown.yaml.empty = TRUE,
  blogdown.new_bundle = TRUE,
  blogdown.title_case = TRUE
)

if (interactive()) {
  suppressMessages(require(blogdown))
}
