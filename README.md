This repository contains an ontology for mean sea level changes recorded by National Oceanic and Atmospheric Administration (NOAA) stations, built using the gist upper ontology.

        MeanSeaLevel.ttl: The ontology file.
        MeanSeaLevel_InstanceData.ttl: Instance data based on the ontology.
        USStationsLinearSeaLevelTrends.csv: The original CSV file from NOAA.
        tarql_ready_USStationsLinearSeaLevelTrends.csv: The CSV with modified column headings for easier triple construction.
        tarql_MeanSeaLevel.rq: The SPARQL query used with Tarql to generate the triples.

The instance data triples were created using Tarql from the NOAA CSV file.
