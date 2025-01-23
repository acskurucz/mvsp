all: site document target

all-doc: document target

site:
	metanorma site generate

document:
	metanorma x.mvsp/document.adoc

target:
	metanorma x.mvsp/target.adoc


clean:
	rm -rf xxxx_*
	rm -rf iev/
	rm -rf relaton/
	rm -rf _site/
	rm -rf x.mvsp/*.err.html
	rm -rf x.mvsp/*.pdf
	rm -rf x.mvsp/*.pdf.err
	rm -rf x.mvsp/*.xml
	rm -rf x.mvsp/*.pdf
