source("renv/activate.R")
venv_path <- file.path(getwd(), ".venv", "Scripts", "python.exe")
if (file.exists(venv_path)) {
  Sys.setenv(RETICULATE_PYTHON = venv_path)
}
Sys.setenv(QUARTO_PYTHON = "C:/git/ITM/itm_nb/.venv/Scripts/python.exe")


tinytex_bin <- "C:/git/ITM/itm_nb/.venv/TinyTeX/bin/win64"
Sys.setenv(PATH = paste(tinytex_bin, Sys.getenv("PATH"), sep = .Platform$path.sep))
