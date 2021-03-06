## Geopoint track

This track is based on [PlanetOSM](http://wiki.openstreetmap.org/wiki/Planet.osm) data. 

### Example Document

```json
{
  "location": [
    -0.1485188,
    51.5250666
  ]
}
```

### Parameters

This track allows to overwrite the following parameters with Rally 0.8.0+ using `--track-params`:

* `bulk_size` (default: 5000)
* `bulk_indexing_clients` (default: 8): Number of clients that issue bulk indexing requests.
* `number_of_replicas` (default: 0)

### License

Same license as the original data from PlanetOSM: [Open Database License](http://wiki.openstreetmap.org/wiki/Open_Database_License).
