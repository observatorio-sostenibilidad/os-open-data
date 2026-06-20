# os-open-data

Public open data catalog and distributable datasets for Observatorio de Sostenibilidad.

Licensed under **CC-BY 4.0** unless otherwise noted per dataset.

**Architecture spec:** [os-workspace/SPEC.md](https://github.com/observatorio-sostenibilidad/os-workspace/blob/main/SPEC.md) (v0.1 prototype)

## Layout

```
catalog/index.yaml     DCAT-AP-compatible catalog
datasets/{id}/         Frictionless Data packages + Parquet
```

## Standards

- DCAT-AP 3.0 catalog metadata
- Frictionless Data Package manifests
- Canonical format: Parquet / GeoParquet
