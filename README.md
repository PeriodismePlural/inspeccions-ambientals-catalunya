# Inspeccions ambientals a Catalunya

A <a href="http://catalunyaplural.cat/ca/8-de-cada-10-empreses-incompleixen-algun-requisit-ambiental-a-catalunya/" target="_blank">Catalunya Plural</a>, hem analitzat les inspeccions ambientals que va fer el Departament de Territori i Sostenibilitat el 2018 i hem vist que 8 de cada 10 empreses incompleixen algun dels seus requisit ambiental.

Els informes de les inspeccions ambientals es publiquen en format PDF, <a href=http://mediambient.gencat.cat/web/.content/home/ambits_dactuacio/empresa_i_produccio_sostenible/prevencio_i_control_dactivitats/la_llei_de_prev_i_control_amb_dact/control_ambiental_i_accio_inspectora/Inspeccio_ambiental/Informes_inspeccio_ambiental_integrada/Programa_2018/barcelona/M/W-00890-B1INS180582.pdf>com aquest</a>. Per això, hem agut de fer servir funcions d'extracció de textos i de reconeixement òptic de caràcters (OCR) de la llibreria **pdftools** per extreure la informació de les caselles marcades.

Podeu veure com hem fet l'scrapping de meS de 500 PDFs i l'anàlisi amb el llenguatge d'anàlisi de dades R <a href="https://github.com/PeriodismePlural/inspeccions-ambientals-catalunya/blob/master/inspeccions-ambientals-catalunya.Rmd" target="_blank">en aquest document</a> i reproduir-lo. 
