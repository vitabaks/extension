# pg_h3


> [pg_h3](https://github.com/zachasme/h3-pg): H3 PostGIS integration
>
> https://github.com/zachasme/h3-pg





[GIS](/gis) extensions: [`postgis`](/postgis), [`postgis_topology`](/postgis_topology), [`postgis_raster`](/postgis_raster), [`postgis_sfcgal`](/postgis_sfcgal), [`postgis_tiger_geocoder`](/postgis_tiger_geocoder), [`address_standardizer`](/address_standardizer), [`address_standardizer_data_us`](/address_standardizer_data_us), [`pgrouting`](/pgrouting), [`pointcloud`](/pointcloud), [`pointcloud_postgis`](/pointcloud_postgis), [`h3`](/h3), [`h3_postgis`](/h3_postgis), [`q3c`](/q3c), [`ogr_fdw`](/ogr_fdw), [`geoip`](/geoip), [`pg_polyline`](/pg_polyline), [`pg_geohash`](/pg_geohash), [`mobilitydb`](/mobilitydb), [`earthdistance`](/earthdistance)


-------
## Extension


| Extension | Version | License | RPM | DEB | PL | `Bin` | `LOAD` | `DYLIB` | `DDL` | `TRUST` | `RELOC` |
|-----------|:-------:|:-------:|:---:|:---:|:--:|:-----:|:------:|:-------:|:-----:|:-------:|:-------:|
| [h3_postgis](https://github.com/zachasme/h3-pg) | 4.1.3 | **<span class="tccyan">Apache-2</span>** | **<span class="tccyan">PGDG</span>** | **<span class="tccyan">PGDG</span>** |  |  |  | <span class="tcblue">✔</span> | <span class="tcblue">✔</span> | <span class="tcwarn">✘</span> | <span class="tcblue">✔</span> |



| Package | Tags | Schemas | Requires | Required by |
|---------|------|---------|----------|-------------|
| [pg_h3](/h3_postgis) |  |  | [`h3`](h3), [`postgis`](postgis), [`postgis_raster`](postgis_raster) |  |





```sql
CREATE EXTENSION h3_postgis CASCADE;
```
> **Comment**: pg17 on el8/9 not ready yet
-----------


## Packages


| OS | Version | License | REPO | Package Pattern | 17 | 16 | 15 | 14 | 13 | 12 | Dependency |
|:--:|---------|:-------:|:----:|-----------------|:--:|:--:|:--:|:--:|:--:|:--:|------------|
| Distro-h3 | 4.1.3 | **<span class="tccyan">Apache-2</span>** | **<span class="tccyan">PGDG</span>** | `h3-pg_$v*` |  | **<span class="tccyan">✔</span>** | **<span class="tccyan">✔</span>** | **<span class="tccyan">✔</span>** | **<span class="tccyan">✔</span>** | **<span class="tccyan">✔</span>** |  |
| Distro-h3 | 4.1.3 | **<span class="tccyan">Apache-2</span>** | **<span class="tccyan">PGDG</span>** | `postgresql-$v-h3` |  | **<span class="tccyan">✔</span>** | **<span class="tccyan">✔</span>** | **<span class="tccyan">✔</span>** | **<span class="tccyan">✔</span>** | **<span class="tccyan">✔</span>** |  |



Install `pg_h3` via [Pigsty](https://pigsty.cc/docs/pgext/usage/install/) playbook:

```bash
./pgsql.yml -t pg_extension -e '{"pg_extensions": ["pg_h3"]}'
```


Install `pg_h3` [RPM](/rpm) from the **<span class="tccyan">PGDG</span>** **YUM** repo:

```bash
dnf install h3-pg_16*;
dnf install h3-pg_15*;
dnf install h3-pg_14*;
dnf install h3-pg_13*;
dnf install h3-pg_12*;
```


Install `pg_h3` [DEB](/deb) from the **<span class="tccyan">PGDG</span>** **APT** repo:

```bash
apt install postgresql-17-h3;
apt install postgresql-16-h3;
apt install postgresql-15-h3;
apt install postgresql-14-h3;
apt install postgresql-13-h3;
apt install postgresql-12-h3;
```







