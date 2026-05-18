# in .Rprofile of the website project
#
# Keep project startup independent of machine-level R profile settings. To opt in
# to sourcing ~/.Rprofile for this project, set:
# AARONKESSLER_SOURCE_USER_RPROFILE=true
if (identical(Sys.getenv("AARONKESSLER_SOURCE_USER_RPROFILE"), "true") && file.exists("~/.Rprofile")) {
  base::sys.source("~/.Rprofile", envir = environment())
}

options(
  blogdown.author = "Aaron M. Kessler",
  blogdown.ext = ".Rmd",
  blogdown.subdir = "post",
  blogdown.yaml.empty = TRUE,
  blogdown.new_bundle = TRUE,
  blogdown.title_case = TRUE,
  blogdown.hugo.version = "0.59.1"
)
