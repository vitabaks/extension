# earthdistance


> [earthdistance](https://www.postgresql.org/docs/current/earthdistance.html): calculate great-circle distances on the surface of the Earth
>
> https://www.postgresql.org/docs/current/earthdistance.html


-------


## Extension


| Extension | Version | License | RPM | DEB | PL | `Bin` | `LOAD` | `DYLIB` | `DDL` | `TRUST` | `RELOC` |
|-----------|:-------:|:-------:|:---:|:---:|:--:|:-----:|:------:|:-------:|:-----:|:-------:|:-------:|
| [earthdistance](https://www.postgresql.org/docs/current/earthdistance.html) | 1.1 | **<span class="tcblue">PostgreSQL</span>** | **<span class="tcblue">CONTRIB</span>** | **<span class="tcblue">CONTRIB</span>** | `C` |  |  | <span class="tcblue">✔</span> | <span class="tcblue">✔</span> | <span class="tcwarn">✘</span> |  |



| Package | Tags | Schemas | Requires | Required by | Comment | Description |
|---------|------|---------|----------|-------------|:-------:|-------------|
| [earthdistance](/earthdistance) |  |  | [`cube`](cube) |  |  | calculate great-circle distances on the surface of the Earth |





```sql
CREATE EXTENSION earthdistance CASCADE;
```

-----------


## Packages


| OS | Version | License | REPO | Package Pattern | 17 | 16 | 15 | 14 | 13 | 12 | Dependency |
|:--:|---------|:-------:|:----:|-----------------|:--:|:--:|:--:|:--:|:--:|:--:|------------|
| [RPM](/rpm) | 1.1 | **<span class="tcblue">PostgreSQL</span>** | **<span class="tcblue">CONTRIB</span>** | `postgresql$v-contrib` | <span class="tcblue">✔</span> | <span class="tcblue">✔</span> | <span class="tcblue">✔</span> | <span class="tcblue">✔</span> | <span class="tcblue">✔</span> | <span class="tcblue">✔</span> | `postgresql$v-server` |
| [DEB](/deb) | 1.1 | **<span class="tcblue">PostgreSQL</span>** | **<span class="tcblue">CONTRIB</span>** | `postgresql-$v` | <span class="tcblue">✔</span> | <span class="tcblue">✔</span> | <span class="tcblue">✔</span> | <span class="tcblue">✔</span> | <span class="tcblue">✔</span> | <span class="tcblue">✔</span> |  |



Install `earthdistance` via [Pigsty](https://pigsty.cc/docs/pgext/usage/install/) playbook:

```bash
./pgsql.yml -t pg_extension -e '{"pg_extensions": ["earthdistance"]}'
```


Install `earthdistance` [RPM](/rpm) from the **<span class="tcblue">CONTRIB</span>** **YUM** repo:

```bash
dnf install postgresql17-contrib;
dnf install postgresql16-contrib;
dnf install postgresql15-contrib;
dnf install postgresql14-contrib;
dnf install postgresql13-contrib;
dnf install postgresql12-contrib;
```


Install `earthdistance` [DEB](/deb) from the **<span class="tcblue">CONTRIB</span>** **APT** repo:

```bash
apt install postgresql-17;
apt install postgresql-16;
apt install postgresql-15;
apt install postgresql-14;
apt install postgresql-13;
apt install postgresql-12;
```


-----------


## Category: GIS


| ID | Extension | Version | Package | License | RPM | DEB | PL | Tags | Schemas | Requires | `LOAD` | `DYLIB` | `DDL` | `TRUST` | `RELOC` |
|:--:|-----------|:-------:|---------|:-------:|:---:|:---:|:--:|------|---------|----------|:------:|:-------:|:-----:|:-------:|:-------:|
| 1100 | [postgis](/postgis) | 3.5.0 | [postgis](/postgis) | **<span class="tcwarn">GPLv2</span>** | **<span class="tccyan">PGDG</span>** | **<span class="tccyan">PGDG</span>** |  |  |  |  |  | <span class="tcblue">✔</span> | <span class="tcblue">✔</span> | <span class="tcwarn">✘</span> | <span class="tcwarn">✘</span> |
| 1101 | [postgis_topology](/postgis_topology) | 3.5.0 | [postgis](/postgis_topology) | **<span class="tcwarn">GPLv2</span>** | **<span class="tccyan">PGDG</span>** | **<span class="tccyan">PGDG</span>** |  |  | `topology` | [`postgis`](postgis) |  | <span class="tcblue">✔</span> | <span class="tcblue">✔</span> | <span class="tcwarn">✘</span> | <span class="tcwarn">✘</span> |
| 1102 | [postgis_raster](/postgis_raster) | 3.5.0 | [postgis](/postgis_raster) | **<span class="tcwarn">GPLv2</span>** | **<span class="tccyan">PGDG</span>** | **<span class="tccyan">PGDG</span>** |  |  |  | [`postgis`](postgis) |  | <span class="tcblue">✔</span> | <span class="tcblue">✔</span> | <span class="tcwarn">✘</span> | <span class="tcwarn">✘</span> |
| 1103 | [postgis_sfcgal](/postgis_sfcgal) | 3.5.0 | [postgis](/postgis_sfcgal) | **<span class="tcwarn">GPLv2</span>** | **<span class="tccyan">PGDG</span>** | **<span class="tccyan">PGDG</span>** |  |  |  | [`postgis`](postgis) |  | <span class="tcblue">✔</span> | <span class="tcblue">✔</span> | <span class="tcwarn">✘</span> | <span class="tcblue">✔</span> |
| 1104 | [postgis_tiger_geocoder](/postgis_tiger_geocoder) | 3.5.0 | [postgis](/postgis_tiger_geocoder) | **<span class="tcwarn">GPLv2</span>** | **<span class="tccyan">PGDG</span>** | **<span class="tccyan">PGDG</span>** |  |  | `tiger` | [`postgis`](postgis), [`fuzzystrmatch`](fuzzystrmatch) |  | <span class="tcblue">✔</span> | <span class="tcblue">✔</span> | <span class="tcblue">✔</span> | <span class="tcwarn">✘</span> |
| 1105 | [address_standardizer](/address_standardizer) | 3.5.0 | [postgis](/address_standardizer) | **<span class="tcwarn">GPLv2</span>** | **<span class="tccyan">PGDG</span>** | **<span class="tccyan">PGDG</span>** |  |  |  |  |  | <span class="tcblue">✔</span> | <span class="tcblue">✔</span> | <span class="tcwarn">✘</span> | <span class="tcblue">✔</span> |
| 1106 | [address_standardizer_data_us](/address_standardizer_data_us) | 3.5.0 | [postgis](/address_standardizer_data_us) | **<span class="tcwarn">GPLv2</span>** | **<span class="tccyan">PGDG</span>** | **<span class="tccyan">PGDG</span>** |  |  |  |  |  | <span class="tcblue">✔</span> | <span class="tcblue">✔</span> | <span class="tcwarn">✘</span> | <span class="tcblue">✔</span> |
| 1110 | [pgrouting](/pgrouting) | 3.6.0 | [pgrouting](/pgrouting) | **<span class="tcwarn">GPLv2</span>** | **<span class="tccyan">PGDG</span>** | **<span class="tccyan">PGDG</span>** |  |  |  | [`postgis`](postgis) |  | <span class="tcblue">✔</span> | <span class="tcblue">✔</span> | <span class="tcwarn">✘</span> | <span class="tcblue">✔</span> |
| 1120 | [pointcloud](/pointcloud) | 1.2.5 | [pointcloud](/pointcloud) | **<span class="tcblue">BSD-3</span>** | **<span class="tcwarn">PIGSTY</span>** | **<span class="tccyan">PGDG</span>** |  |  |  |  |  | <span class="tcblue">✔</span> | <span class="tcblue">✔</span> | <span class="tcwarn">✘</span> | <span class="tcwarn">✘</span> |
| 1121 | [pointcloud_postgis](/pointcloud_postgis) | 1.2.5 | [pointcloud](/pointcloud_postgis) | **<span class="tcblue">BSD-3</span>** | **<span class="tccyan">PGDG</span>** | **<span class="tccyan">PGDG</span>** |  |  |  | [`postgis`](postgis), [`pointcloud`](pointcloud) |  | <span class="tcblue">✔</span> | <span class="tcblue">✔</span> | <span class="tcblue">✔</span> | <span class="tcwarn">✘</span> |
| 1130 | [h3](/h3) | 4.1.3 | [pg_h3](/h3) | **<span class="tccyan">Apache-2</span>** | **<span class="tccyan">PGDG</span>** | **<span class="tccyan">PGDG</span>** |  |  |  |  |  | <span class="tcblue">✔</span> | <span class="tcblue">✔</span> | <span class="tcwarn">✘</span> | <span class="tcblue">✔</span> |
| 1131 | [h3_postgis](/h3_postgis) | 4.1.3 | [pg_h3](/h3_postgis) | **<span class="tccyan">Apache-2</span>** | **<span class="tccyan">PGDG</span>** | **<span class="tccyan">PGDG</span>** |  |  |  | [`h3`](h3), [`postgis`](postgis), [`postgis_raster`](postgis_raster) |  | <span class="tcblue">✔</span> | <span class="tcblue">✔</span> | <span class="tcwarn">✘</span> | <span class="tcblue">✔</span> |
| 1140 | [q3c](/q3c) | 2.0.1 | [q3c](/q3c) | **<span class="tcwarn">GPLv2</span>** | **<span class="tcwarn">PIGSTY</span>** | **<span class="tccyan">PGDG</span>** |  |  |  |  |  | <span class="tcblue">✔</span> | <span class="tcblue">✔</span> | <span class="tcwarn">✘</span> | <span class="tcblue">✔</span> |
| 1150 | [ogr_fdw](/ogr_fdw) | 1.1 | [ogr_fdw](/ogr_fdw) | **<span class="tcblue">MIT</span>** | **<span class="tccyan">PGDG</span>** | **<span class="tccyan">PGDG</span>** |  |  |  |  |  | <span class="tcblue">✔</span> | <span class="tcblue">✔</span> | <span class="tcwarn">✘</span> | <span class="tcblue">✔</span> |
| 1155 | [geoip](/geoip) | 0.3.0 | [geoip](/geoip) | **<span class="tcblue">BSD-2</span>** | **<span class="tccyan">PGDG</span>** | **<span class="tcwarn">PIGSTY</span>** |  |  | `geoip` | [`ip4r`](ip4r) |  | <span class="tcblue">✔</span> | <span class="tcblue">✔</span> | <span class="tcwarn">✘</span> | <span class="tcwarn">✘</span> |
| 1160 | [pg_polyline](/pg_polyline) | 0.0.0 | [pg_polyline](/pg_polyline) | **<span class="tcblue">MIT</span>** | **<span class="tcwarn">PIGSTY</span>** | **<span class="tcwarn">PIGSTY</span>** | `Rust` | `pgrx` |  |  |  | <span class="tcblue">✔</span> | <span class="tcblue">✔</span> | <span class="tcblue">✔</span> | <span class="tcwarn">✘</span> |
| 1170 | [pg_geohash](/pg_geohash) | 1.0 | [pg_geohash](/pg_geohash) | **<span class="tcblue">MIT</span>** | **<span class="tcwarn">PIGSTY</span>** | **<span class="tcwarn">PIGSTY</span>** | `C` | `nil-lic` |  |  |  | <span class="tcblue">✔</span> | <span class="tcblue">✔</span> | <span class="tcwarn">✘</span> | <span class="tcblue">✔</span> |
| 1180 | [mobilitydb](/mobilitydb) | 1.1.1 | [mobilitydb](/mobilitydb) | **<span class="tcwarn">GPLv3</span>** |  | **<span class="tccyan">PGDG</span>** |  |  |  | [`postgis`](postgis) |  | <span class="tcblue">✔</span> | <span class="tcblue">✔</span> | <span class="tcwarn">✘</span> | <span class="tcblue">✔</span> |
| 1190 | [earthdistance](/earthdistance) | 1.1 | [earthdistance](/earthdistance) | **<span class="tcblue">PostgreSQL</span>** | **<span class="tcblue">CONTRIB</span>** | **<span class="tcblue">CONTRIB</span>** | `C` |  |  | [`cube`](cube) |  | <span class="tcblue">✔</span> | <span class="tcblue">✔</span> | <span class="tcwarn">✘</span> |  |



