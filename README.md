# Hi, I'm Affifa Taskeen

**Geospatial Data Engineer · GeoAI Engineer**

I turn satellite, raster and vector data into analysis-ready, cloud-native datasets, serve them through OGC web services, and build AI on top so that people can query maps and spatial data in plain English.

6+ years in geospatial engineering and Earth observation · MPhil Remote Sensing & GIS (Gold Medalist) · open to relocation to Germany / Europe

## What I work on

- **Geospatial data pipelines:** ETL/ELT that fuses vector, raster, STAC and API sources into PostGIS and GeoParquet, with CRS harmonisation, NoData handling and data-quality checks
- **Earth observation:** Sentinel-1 SAR and Sentinel-2 processing (SNAP, GDAL, Rasterio, Google Earth Engine), NDVI/NDWI time series, LULC classification, change detection
- **Serving geospatial data:** GeoServer and MapServer (WMS, WMTS, WFS, WCS, OGC API – Features, vector tiles), COG tile servers, OSRM routing, spatial REST APIs
- **GeoAI:** natural-language-to-PostGIS queries with LLM agents, RAG over spatial knowledge bases, and deep learning on imagery (CNN, U-Net, YOLO, TorchGeo)

## Selected work

| Project | What it does | Stack |
|---|---|---|
| Sentinel-2 crop health pipeline | Automated download, SNAP calibration, NDVI/NDWI per farm, COGs on S3, statistics in Redshift; 72% faster per scene (25–30 min → under 8) | Python, SNAP, COG, PostGIS, AWS |
| Flood susceptibility dashboard | Flood zones from Sentinel-1 SAR + DEM over 12,500+ km², 670,000+ buildings in PostGIS, queried in plain English through a local LLM with SQL guardrails | Sentinel-1, PostGIS, Ollama, FastAPI, Leaflet |
| GeoAI geospatial platform | GeoServer + PostGIS backend (WMS/WFS, tile caching, SLD) with LangChain agents and RAG that turn questions into spatial operations | GeoServer, Django, LangChain, Weaviate, React, Leaflet, AWS |
| [Text2SQL-Agent](https://github.com/iamaffifa/Text2SQL-Agent) | LangGraph agent that turns plain-English questions into safe, validated SQL with hybrid retrieval, a sqlglot guard and an execution-based eval suite; runs locally on open-source LLMs | LangGraph, Ollama, sqlglot, Python |
| [dwh_pgsql](https://github.com/iamaffifa/dwh_pgsql) | Data warehouse built on the medallion architecture in PostgreSQL | PostgreSQL, PL/pgSQL |

Most of my production work lives in private client and company repositories. I'm happy to walk through the architecture of any of these on a call.

## Stack

**Geospatial:** GDAL · Rasterio · rioxarray · xarray · GeoPandas · Shapely · STAC · COG · GeoParquet · Zarr · H3 / S2 · QGIS · ArcPy
**Databases & big data:** PostgreSQL/PostGIS · pgRouting · ClickHouse · Redshift · PySpark · Apache Sedona
**Serving:** GeoServer · MapServer · OGC (WMS, WMTS, WFS, WCS, OGC API – Features) · vector tiles · OSRM · FastAPI · Django REST
**Earth observation:** Sentinel-1/2 · Landsat · Planet · Pléiades · SNAP · Google Earth Engine · Planetary Computer
**AI / ML:** PyTorch · TorchGeo · TensorFlow · scikit-learn · LangChain · LangGraph · RAG · Weaviate · pgvector · Ollama
**Pipelines & cloud:** Airflow · dbt · Kafka · Docker · CI/CD · AWS · Azure

## Background

- **Senior Geospatial Data Engineer**, Infotech Groups (2026–present): geospatial data pipelines and AI query layers; leading a team of 7 building an on-premise text-to-SQL assistant on open-source LLMs
- **GeoAI and GIS Developer**, FAAB AI (2023–2026): LLM-powered geospatial portals and RAG systems for clients in Sweden, the US and Malaysia
- **Senior GIS Developer**, Spatial Stack (2021–2023): GeoServer-backed web GIS portals and EO ingestion pipelines
- **ML / GIS Developer**, The Urban Unit (2020–2021): CNN models on Sentinel-2 and drone imagery for agriculture

[Portfolio](https://iamaffifa.github.io) · [LinkedIn](https://linkedin.com/in/affifataskeen)
