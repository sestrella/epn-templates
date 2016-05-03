build:
	@pdflatex --output-directory=out main
	@makeglossaries -d out main
	@biber --output-directory=out main
	@pdflatex --output-directory=out main

clean:
	@rm -rf out/*
