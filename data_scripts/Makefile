all: data_preprocess data_analysis data_outliers synthetic_data fix_received_data rtss_reg

data_preprocess: data_preprocess.ipynb
	jupyter nbconvert --to script $<

data_analysis: data_analysis.ipynb
	jupyter nbconvert --to script $<

data_outliers: data_outliers.ipynb
	jupyter nbconvert --to script $<

synthetic_data: synthetic_data.ipynb
	jupyter nbconvert --to script $<

fix_received_data: fix_received_data.ipynb
	jupyter nbconvert --to script $<

rtss_reg: rtss_reg.ipynb
	jupyter nbconvert --to script $<

clean:
	rm *.py
