# semantic-web-disease-location-correlation

Have your Apache Jena Fuseki server running.

Since our data was not taken from the LOGD site and instead from data.gov, we upload RDFs
of data to a data directory in the Fuseki server using the command line, and then accessed it
using http://localhost:3030/ from the browser. The local endpoint should be made as the
endpoint mentioned for the charts and instance of Google API visualisation table to work.

Upload RDF data files taken from to a persistent data store 'ds':
https://catalog.data.gov/dataset/nndss-table-1ii-tetanus-to-trichinellosis-bdb61
https://catalog.data.gov/dataset/nndss-table-1gg-spotted-fever-rickettsiosis-confirmed-tosmallpox-e25d3
https://catalog.data.gov/dataset/nndss-table-1h-cholera-to-coccidioidomycosis-43b90
https://catalog.data.gov/dataset/nndss-table-1e-botulism-foodborne-to-botulism-other-c466c

Run 'main.html' (the SPARQL queries have been written in the html code to query insights)

