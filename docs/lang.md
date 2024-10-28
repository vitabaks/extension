# LANG


> LANG: Develop, Test, Package, and Deliver Stored Procedures written in various PL/Lanaguages: Java, Js, Lua, R, Sh, PRQL, ...
## Extensions


There are 31 available extensions in this category:

[`pg_tle`](/pg_tle) [`plv8`](/plv8) [`pllua`](/pllua) [`hstore_pllua`](/hstore_pllua) [`plluau`](/plluau) [`hstore_plluau`](/hstore_plluau) [`plprql`](/plprql) [`pldbgapi`](/pldbgapi) [`plpgsql_check`](/plpgsql_check) [`plprofiler`](/plprofiler) [`plsh`](/plsh) [`pljava`](/pljava) [`plr`](/plr) [`pgtap`](/pgtap) [`faker`](/faker) [`dbt2`](/dbt2) [`pltcl`](/pltcl) [`pltclu`](/pltclu) [`plperl`](/plperl) [`bool_plperl`](/bool_plperl) [`hstore_plperl`](/hstore_plperl) [`jsonb_plperl`](/jsonb_plperl) [`plperlu`](/plperlu) [`bool_plperlu`](/bool_plperlu) [`jsonb_plperlu`](/jsonb_plperlu) [`hstore_plperlu`](/hstore_plperlu) [`plpgsql`](/plpgsql) [`plpython3u`](/plpython3u) [`jsonb_plpython3u`](/jsonb_plpython3u) [`ltree_plpython3u`](/ltree_plpython3u) [`hstore_plpython3u`](/hstore_plpython3u)


| ID | Extension | Version | Package | License | RPM | DEB | Website | `LOAD` | `DYLIB` | `DDL` | Description |
|:--:|-----------|:-------:|---------|:-------:|:---:|:---:|:-------:|:------:|:-------:|:-----:|-------------|
| 2000 | [pg_tle](/pg_tle) | 1.2.0 | [pg_tle](/pg_tle) | **<span class="tccyan">Apache-2</span>** | **<span class="tcwarn">PIGSTY</span>** | **<span class="tcwarn">PIGSTY</span>** | [LINK](https://github.com/aws/pg_tle) | <span class="tcred">❗</span> | <span class="tcblue">✔</span> | <span class="tcblue">✔</span> | Trusted Language Extensions for PostgreSQL |
| 2010 | [plv8](/plv8) | 3.2.3 | [plv8](/plv8) | **<span class="tcblue">PostgreSQL</span>** | **<span class="tcwarn">PIGSTY</span>** | **<span class="tcwarn">PIGSTY</span>** | [LINK](https://github.com/plv8/plv8) |  | <span class="tcblue">✔</span> | <span class="tcblue">✔</span> | PL/JavaScript (v8) trusted procedural language |
| 2020 | [pllua](/pllua) | 2.0 | [pllua](/pllua) | **<span class="tcblue">MIT</span>** | **<span class="tccyan">PGDG</span>** | **<span class="tccyan">PGDG</span>** | [LINK](https://github.com/pllua/pllua) |  | <span class="tcblue">✔</span> | <span class="tcblue">✔</span> | Lua as a procedural language |
| 2021 | [hstore_pllua](/hstore_pllua) | 1.0 | [pllua](/hstore_pllua) | **<span class="tcblue">MIT</span>** |  | **<span class="tccyan">PGDG</span>** | [LINK](https://github.com/pllua/pllua) |  | <span class="tcblue">✔</span> | <span class="tcblue">✔</span> | Hstore transform for Lua |
| 2030 | [plluau](/plluau) | 2.0 | [pllua](/plluau) | **<span class="tcblue">MIT</span>** | **<span class="tccyan">PGDG</span>** | **<span class="tccyan">PGDG</span>** | [LINK](https://github.com/pllua/pllua) |  | <span class="tcblue">✔</span> | <span class="tcblue">✔</span> | Lua as an untrusted procedural language |
| 2031 | [hstore_plluau](/hstore_plluau) | 1.0 | [pllua](/hstore_plluau) | **<span class="tcblue">MIT</span>** |  | **<span class="tccyan">PGDG</span>** | [LINK](https://github.com/pllua/pllua) |  | <span class="tcblue">✔</span> | <span class="tcblue">✔</span> | Hstore transform for untrusted Lua |
| 2040 | [plprql](/plprql) | 0.1.0 | [plprql](/plprql) | **<span class="tccyan">Apache-2</span>** | **<span class="tcwarn">PIGSTY</span>** | **<span class="tcwarn">PIGSTY</span>** | [LINK](https://github.com/kaspermarstal/plprql) |  | <span class="tcblue">✔</span> | <span class="tcblue">✔</span> | Use PRQL in PostgreSQL - Pipelined Relational Query Language |
| 2050 | [pldbgapi](/pldbgapi) | 1.1 | [pldebugger](/pldbgapi) | **<span class="tccyan">Artistic</span>** | **<span class="tccyan">PGDG</span>** | **<span class="tccyan">PGDG</span>** | [LINK](https://github.com/EnterpriseDB/pldebugger) |  | <span class="tcblue">✔</span> | <span class="tcblue">✔</span> | server-side support for debugging PL/pgSQL functions |
| 2060 | [plpgsql_check](/plpgsql_check) | 2.7 | [plpgsql_check](/plpgsql_check) | **<span class="tcblue">MIT</span>** | **<span class="tccyan">PGDG</span>** | **<span class="tccyan">PGDG</span>** | [LINK](https://github.com/okbob/plpgsql_check) | <span class="tcred">❗</span> | <span class="tcblue">✔</span> | <span class="tcblue">✔</span> | extended check for plpgsql functions |
| 2070 | [plprofiler](/plprofiler) | 4.2 | [plprofiler](/plprofiler) | **<span class="tccyan">Artistic</span>** | **<span class="tccyan">PGDG</span>** | **<span class="tccyan">PGDG</span>** | [LINK](https://github.com/bigsql/plprofiler) |  | <span class="tcblue">✔</span> | <span class="tcblue">✔</span> | server-side support for profiling PL/pgSQL functions |
| 2080 | [plsh](/plsh) | 2 | [plsh](/plsh) | **<span class="tcblue">MIT</span>** | **<span class="tccyan">PGDG</span>** | **<span class="tccyan">PGDG</span>** | [LINK](https://github.com/petere/plsh) |  | <span class="tcblue">✔</span> | <span class="tcblue">✔</span> | PL/sh procedural language |
| 2090 | [pljava](/pljava) | 1.6.6 | [pljava](/pljava) | **<span class="tcblue">BSD-3</span>** | **<span class="tccyan">PGDG</span>** | **<span class="tccyan">PGDG</span>** | [LINK](https://github.com/tada/pljava) |  | <span class="tcblue">✔</span> | <span class="tcblue">✔</span> | PL/Java procedural language (https://tada.github.io/pljava/) |
| 2100 | [plr](/plr) | 8.4.6 | [plr](/plr) | **<span class="tcwarn">GPLv2</span>** | **<span class="tccyan">PGDG</span>** | **<span class="tccyan">PGDG</span>** | [LINK](https://github.com/postgres-plr/plr) |  | <span class="tcblue">✔</span> | <span class="tcblue">✔</span> | load R interpreter and execute R script from within a database |
| 2200 | [pgtap](/pgtap) | 1.3.1 | [pgtap](/pgtap) | **<span class="tcblue">PostgreSQL</span>** | **<span class="tccyan">PGDG</span>** | **<span class="tccyan">PGDG</span>** | [LINK](https://github.com/theory/pgtap) |  | <span class="tcblue">✔</span> | <span class="tcblue">✔</span> | Unit testing for PostgreSQL |
| 2210 | [faker](/faker) | 0.5.3 | [faker](/faker) | **<span class="tcblue">PostgreSQL</span>** | **<span class="tccyan">PGDG</span>** | PGDG | [LINK](https://github.com/anpandu/postgresql_faker) |  | <span class="tcblue">✔</span> | <span class="tcblue">✔</span> | Wrapper for the Faker Python library |
| 2220 | [dbt2](/dbt2) | 0.45.0 | [dbt2](/dbt2) | **<span class="tccyan">Artistic</span>** | **<span class="tccyan">PGDG</span>** | PGDG | [LINK](https://github.com/nuodb/dbt2/tree/master) |  | <span class="tcblue">✔</span> | <span class="tcblue">✔</span> | OSDL-DBT-2 test kit |
| 2240 | [pltcl](/pltcl) | 1.0 | [pltcl](/pltcl) | **<span class="tcblue">PostgreSQL</span>** | **<span class="tcblue">CONTRIB</span>** | **<span class="tcblue">CONTRIB</span>** | [LINK](https://www.postgresql.org/docs/current/pltcl.html) |  | <span class="tcblue">✔</span> | <span class="tcblue">✔</span> | PL/Tcl procedural language |
| 2250 | [pltclu](/pltclu) | 1.0 | [pltcl](/pltclu) | **<span class="tcblue">PostgreSQL</span>** | **<span class="tcblue">CONTRIB</span>** | **<span class="tcblue">CONTRIB</span>** | [LINK](https://www.postgresql.org/docs/current/pltcl.html) |  | <span class="tcwarn">✘</span> | <span class="tcblue">✔</span> | PL/TclU untrusted procedural language |
| 2260 | [plperl](/plperl) | 1.0 | [plperl](/plperl) | **<span class="tcblue">PostgreSQL</span>** | **<span class="tcblue">CONTRIB</span>** | **<span class="tcblue">CONTRIB</span>** | [LINK](https://www.postgresql.org/docs/current/plperl.html) |  | <span class="tcblue">✔</span> | <span class="tcblue">✔</span> | PL/Perl procedural language |
| 2261 | [bool_plperl](/bool_plperl) | 1.0 | [plperl](/bool_plperl) | **<span class="tcblue">PostgreSQL</span>** | **<span class="tcblue">CONTRIB</span>** | **<span class="tcblue">CONTRIB</span>** | [LINK](https://www.postgresql.org/docs/current/plperl.html) |  | <span class="tcblue">✔</span> | <span class="tcblue">✔</span> | transform between bool and plperl |
| 2262 | [hstore_plperl](/hstore_plperl) | 1.0 | [plperl](/hstore_plperl) | **<span class="tcblue">PostgreSQL</span>** | **<span class="tcblue">CONTRIB</span>** | **<span class="tcblue">CONTRIB</span>** | [LINK](https://www.postgresql.org/docs/current/plperl.html) |  | <span class="tcblue">✔</span> | <span class="tcblue">✔</span> | transform between hstore and plperl |
| 2263 | [jsonb_plperl](/jsonb_plperl) | 1.0 | [plperl](/jsonb_plperl) | **<span class="tcblue">PostgreSQL</span>** | **<span class="tcblue">CONTRIB</span>** | **<span class="tcblue">CONTRIB</span>** | [LINK](https://www.postgresql.org/docs/current/plperl.html) |  | <span class="tcwarn">✘</span> | <span class="tcblue">✔</span> | transform between jsonb and plperl |
| 2270 | [plperlu](/plperlu) | 1.0 | [plperlu](/plperlu) | **<span class="tcblue">PostgreSQL</span>** | **<span class="tcblue">CONTRIB</span>** | **<span class="tcblue">CONTRIB</span>** | [LINK](https://www.postgresql.org/docs/current/plperl.html) |  | <span class="tcblue">✔</span> | <span class="tcblue">✔</span> | PL/PerlU untrusted procedural language |
| 2271 | [bool_plperlu](/bool_plperlu) | 1.0 | [plperlu](/bool_plperlu) | **<span class="tcblue">PostgreSQL</span>** | **<span class="tcblue">CONTRIB</span>** | **<span class="tcblue">CONTRIB</span>** | [LINK](https://www.postgresql.org/docs/current/plperl.html) |  | <span class="tcwarn">✘</span> | <span class="tcblue">✔</span> | transform between bool and plperlu |
| 2272 | [jsonb_plperlu](/jsonb_plperlu) | 1.0 | [plperlu](/jsonb_plperlu) | **<span class="tcblue">PostgreSQL</span>** | **<span class="tcblue">CONTRIB</span>** | **<span class="tcblue">CONTRIB</span>** | [LINK](https://www.postgresql.org/docs/current/plperl.html) |  | <span class="tcwarn">✘</span> | <span class="tcblue">✔</span> | transform between jsonb and plperlu |
| 2273 | [hstore_plperlu](/hstore_plperlu) | 1.0 | [plperlu](/hstore_plperlu) | **<span class="tcblue">PostgreSQL</span>** | **<span class="tcblue">CONTRIB</span>** | **<span class="tcblue">CONTRIB</span>** | [LINK](https://www.postgresql.org/docs/current/plperl.html) |  | <span class="tcwarn">✘</span> | <span class="tcblue">✔</span> | transform between hstore and plperlu |
| 2280 | [plpgsql](/plpgsql) | 1.0 | [plpgsql](/plpgsql) | **<span class="tcblue">PostgreSQL</span>** | **<span class="tcblue">CONTRIB</span>** | **<span class="tcblue">CONTRIB</span>** | [LINK](https://www.postgresql.org/docs/current/plpgsql.html) |  | <span class="tcblue">✔</span> | <span class="tcblue">✔</span> | PL/pgSQL procedural language |
| 2290 | [plpython3u](/plpython3u) | 1.0 | [plpython3u](/plpython3u) | **<span class="tcblue">PostgreSQL</span>** | **<span class="tcblue">CONTRIB</span>** | **<span class="tcblue">CONTRIB</span>** | [LINK](https://www.postgresql.org/docs/current/plpython.html) |  | <span class="tcblue">✔</span> | <span class="tcblue">✔</span> | PL/Python3U untrusted procedural language |
| 2291 | [jsonb_plpython3u](/jsonb_plpython3u) | 1.0 | [plpython3u](/jsonb_plpython3u) | **<span class="tcblue">PostgreSQL</span>** | **<span class="tcblue">CONTRIB</span>** | **<span class="tcblue">CONTRIB</span>** | [LINK](https://www.postgresql.org/docs/current/plpython.html) |  | <span class="tcwarn">✘</span> | <span class="tcblue">✔</span> | transform between jsonb and plpython3u |
| 2292 | [ltree_plpython3u](/ltree_plpython3u) | 1.0 | [plpython3u](/ltree_plpython3u) | **<span class="tcblue">PostgreSQL</span>** | **<span class="tcblue">CONTRIB</span>** | **<span class="tcblue">CONTRIB</span>** | [LINK](https://www.postgresql.org/docs/current/plpython.html) |  | <span class="tcwarn">✘</span> | <span class="tcblue">✔</span> | transform between ltree and plpython3u |
| 2293 | [hstore_plpython3u](/hstore_plpython3u) | 1.0 | [plpython3u](/hstore_plpython3u) | **<span class="tcblue">PostgreSQL</span>** | **<span class="tcblue">CONTRIB</span>** | **<span class="tcblue">CONTRIB</span>** | [LINK](https://www.postgresql.org/docs/current/plpython.html) |  | <span class="tcwarn">✘</span> | <span class="tcblue">✔</span> | transform between hstore and plpython3u |



```yaml
pg17: pg_tle plv8 pllua pldebugger plpgsql_check plprofiler plsh #pllua #plprql #pljava #plr #pgtap #faker #dbt2
pg16: pg_tle plv8 pllua plprql pldebugger plpgsql_check plprofiler plsh #pllua #pljava #plr #pgtap #faker #dbt2
pg15: pg_tle plv8 pllua plprql pldebugger plpgsql_check plprofiler plsh #pllua #pljava #plr #pgtap #faker #dbt2
pg14: pg_tle plv8 pllua plprql pldebugger plpgsql_check plprofiler plsh #pllua #pljava #plr #pgtap #faker #dbt2
pg13: pg_tle plv8 pllua plprql pldebugger plpgsql_check plprofiler plsh #pllua #pljava #plr #pgtap #faker #dbt2
pg12: pg_tle plv8 pllua plprql pldebugger plpgsql_check plprofiler plsh #pllua #pljava #plr #pgtap #faker #dbt2
```



--------

## RPM Packages


| Package | Version | License | RPM | RPM Package | 17 | 16 | 15 | 14 | 13 | 12 | Description |
|---------|---------|:-------:|:---:|-------------|:--:|:--:|:--:|:--:|:--:|:--:|-------------|
| [pg_tle](/pg_tle) | 1.2.0 | **<span class="tccyan">Apache-2</span>** | **<span class="tcwarn">PIGSTY</span>** | `pg_tle_$v*` | <span class="tcblue">✔</span> | <span class="tcblue">✔</span> | <span class="tcblue">✔</span> | <span class="tcblue">✔</span> | <span class="tcblue">✔</span> | <span class="tcblue">✔</span> | Trusted Language Extensions for PostgreSQL |
| [plv8](/plv8) | 3.2.3 | **<span class="tcblue">PostgreSQL</span>** | **<span class="tcwarn">PIGSTY</span>** | `plv8_$v*` | <span class="tcblue">✔</span> | <span class="tcblue">✔</span> | <span class="tcblue">✔</span> | <span class="tcblue">✔</span> | <span class="tcblue">✔</span> | <span class="tcblue">✔</span> | PL/JavaScript (v8) trusted procedural language |
| [pllua](/pllua) | 2.0 | **<span class="tcblue">MIT</span>** | **<span class="tccyan">PGDG</span>** | `pllua_$v*` | <span class="tcblue">✔</span> | <span class="tcblue">✔</span> | <span class="tcblue">✔</span> | <span class="tcblue">✔</span> | <span class="tcblue">✔</span> | <span class="tcblue">✔</span> | Lua as a procedural language |
| [plprql](/plprql) | 0.1.0 | **<span class="tccyan">Apache-2</span>** | **<span class="tcwarn">PIGSTY</span>** | `plprql_$v` |  | <span class="tcblue">✔</span> | <span class="tcblue">✔</span> | <span class="tcblue">✔</span> | <span class="tcblue">✔</span> | <span class="tcblue">✔</span> | Use PRQL in PostgreSQL - Pipelined Relational Query Language |
| [pldebugger](/pldbgapi) | 1.1 | **<span class="tccyan">Artistic</span>** | **<span class="tccyan">PGDG</span>** | `pldebugger_$v*` | <span class="tcblue">✔</span> | <span class="tcblue">✔</span> | <span class="tcblue">✔</span> | <span class="tcblue">✔</span> | <span class="tcblue">✔</span> | <span class="tcblue">✔</span> | server-side support for debugging PL/pgSQL functions |
| [plpgsql_check](/plpgsql_check) | 2.7 | **<span class="tcblue">MIT</span>** | **<span class="tccyan">PGDG</span>** | `plpgsql_check_$v*` | <span class="tcblue">✔</span> | <span class="tcblue">✔</span> | <span class="tcblue">✔</span> | <span class="tcblue">✔</span> | <span class="tcblue">✔</span> | <span class="tcblue">✔</span> | extended check for plpgsql functions |
| [plprofiler](/plprofiler) | 4.2 | **<span class="tccyan">Artistic</span>** | **<span class="tccyan">PGDG</span>** | `plprofiler_$v*` | <span class="tcblue">✔</span> | <span class="tcblue">✔</span> | <span class="tcblue">✔</span> | <span class="tcblue">✔</span> | <span class="tcblue">✔</span> | <span class="tcblue">✔</span> | server-side support for profiling PL/pgSQL functions |
| [plsh](/plsh) | 2 | **<span class="tcblue">MIT</span>** | **<span class="tccyan">PGDG</span>** | `plsh_$v*` | <span class="tcblue">✔</span> | <span class="tcblue">✔</span> | <span class="tcblue">✔</span> | <span class="tcblue">✔</span> | <span class="tcblue">✔</span> | <span class="tcblue">✔</span> | PL/sh procedural language |
| [pljava](/pljava) | 1.6.6 | **<span class="tcblue">BSD-3</span>** | **<span class="tccyan">PGDG</span>** | `pljava_$v*` |  | <span class="tcblue">✔</span> | <span class="tcblue">✔</span> | <span class="tcblue">✔</span> | <span class="tcblue">✔</span> | <span class="tcblue">✔</span> | PL/Java procedural language (https://tada.github.io/pljava/) |
| [plr](/plr) | 8.4.6 | **<span class="tcwarn">GPLv2</span>** | **<span class="tccyan">PGDG</span>** | `plr_$v*` | <span class="tcblue">✔</span> | <span class="tcblue">✔</span> | <span class="tcblue">✔</span> | <span class="tcblue">✔</span> | <span class="tcblue">✔</span> | <span class="tcblue">✔</span> | load R interpreter and execute R script from within a database |
| [pgtap](/pgtap) | 1.3.1 | **<span class="tcblue">PostgreSQL</span>** | **<span class="tccyan">PGDG</span>** | `pgtap_$v*` |  | <span class="tcblue">✔</span> | <span class="tcblue">✔</span> | <span class="tcblue">✔</span> | <span class="tcblue">✔</span> | <span class="tcblue">✔</span> | Unit testing for PostgreSQL |
| [faker](/faker) | 0.5.3 | **<span class="tcblue">PostgreSQL</span>** | **<span class="tccyan">PGDG</span>** | `postgresql_faker_$v*` | <span class="tcblue">✔</span> | <span class="tcblue">✔</span> | <span class="tcblue">✔</span> | <span class="tcblue">✔</span> | <span class="tcblue">✔</span> | <span class="tcblue">✔</span> | Wrapper for the Faker Python library |
| [dbt2](/dbt2) | 0.45.0 | **<span class="tccyan">Artistic</span>** | **<span class="tccyan">PGDG</span>** | `dbt2-pg$v-extensions*` | <span class="tcblue">✔</span> | <span class="tcblue">✔</span> | <span class="tcblue">✔</span> | <span class="tcblue">✔</span> | <span class="tcblue">✔</span> | <span class="tcblue">✔</span> | OSDL-DBT-2 test kit |
| [pltcl](/pltcl) | 1.0 | **<span class="tcblue">PostgreSQL</span>** | **<span class="tcblue">CONTRIB</span>** | `postgresql$v-contrib` | <span class="tcblue">✔</span> | <span class="tcblue">✔</span> | <span class="tcblue">✔</span> | <span class="tcblue">✔</span> | <span class="tcblue">✔</span> | <span class="tcblue">✔</span> | PL/Tcl procedural language |
| [plperl](/plperl) | 1.0 | **<span class="tcblue">PostgreSQL</span>** | **<span class="tcblue">CONTRIB</span>** | `postgresql$v-contrib` | <span class="tcblue">✔</span> | <span class="tcblue">✔</span> | <span class="tcblue">✔</span> | <span class="tcblue">✔</span> | <span class="tcblue">✔</span> | <span class="tcblue">✔</span> | PL/Perl procedural language |
| [plperlu](/plperlu) | 1.0 | **<span class="tcblue">PostgreSQL</span>** | **<span class="tcblue">CONTRIB</span>** | `postgresql$v-contrib` | <span class="tcblue">✔</span> | <span class="tcblue">✔</span> | <span class="tcblue">✔</span> | <span class="tcblue">✔</span> | <span class="tcblue">✔</span> | <span class="tcblue">✔</span> | PL/PerlU untrusted procedural language |
| [plpgsql](/plpgsql) | 1.0 | **<span class="tcblue">PostgreSQL</span>** | **<span class="tcblue">CONTRIB</span>** | `postgresql$v-contrib` | <span class="tcblue">✔</span> | <span class="tcblue">✔</span> | <span class="tcblue">✔</span> | <span class="tcblue">✔</span> | <span class="tcblue">✔</span> | <span class="tcblue">✔</span> | PL/pgSQL procedural language |
| [plpython3u](/plpython3u) | 1.0 | **<span class="tcblue">PostgreSQL</span>** | **<span class="tcblue">CONTRIB</span>** | `postgresql$v-contrib` | <span class="tcblue">✔</span> | <span class="tcblue">✔</span> | <span class="tcblue">✔</span> | <span class="tcblue">✔</span> | <span class="tcblue">✔</span> | <span class="tcblue">✔</span> | PL/Python3U untrusted procedural language |



```yaml
pg17: pg_tle_17* plv8_17* pllua_17* pldebugger_17* plpgsql_check_17* plprofiler_17* plsh_17* # #plprql_17 #pljava_17* #plr_17* #pgtap_17* #postgresql_faker_17* #dbt2-pg17-extensions*
pg16: pg_tle_16* plv8_16* pllua_16* plprql_16 pldebugger_16* plpgsql_check_16* plprofiler_16* plsh_16* # #pljava_16* #plr_16* #pgtap_16* #postgresql_faker_16* #dbt2-pg16-extensions*
pg15: pg_tle_15* plv8_15* pllua_15* plprql_15 pldebugger_15* plpgsql_check_15* plprofiler_15* plsh_15* # #pljava_15* #plr_15* #pgtap_15* #postgresql_faker_15* #dbt2-pg15-extensions*
pg14: pg_tle_14* plv8_14* pllua_14* plprql_14 pldebugger_14* plpgsql_check_14* plprofiler_14* plsh_14* # #pljava_14* #plr_14* #pgtap_14* #postgresql_faker_14* #dbt2-pg14-extensions*
pg13: pg_tle_13* plv8_13* pllua_13* plprql_13 pldebugger_13* plpgsql_check_13* plprofiler_13* plsh_13* # #pljava_13* #plr_13* #pgtap_13* #postgresql_faker_13* #dbt2-pg13-extensions*
pg12: pg_tle_12* plv8_12* pllua_12* plprql_12 pldebugger_12* plpgsql_check_12* plprofiler_12* plsh_12* # #pljava_12* #plr_12* #pgtap_12* #postgresql_faker_12* #dbt2-pg12-extensions*
```



--------

## DEB Packages


| Package | Version | License | DEB | DEB Package | 17 | 16 | 15 | 14 | 13 | 12 | Description |
|---------|---------|:-------:|:---:|-------------|:--:|:--:|:--:|:--:|:--:|:--:|-------------|
| [pg_tle](/pg_tle) | 1.4.0 | **<span class="tccyan">Apache-2</span>** | **<span class="tcwarn">PIGSTY</span>** | `postgresql-$v-pg-tle` | <span class="tcblue">✔</span> | <span class="tcblue">✔</span> | <span class="tcblue">✔</span> | <span class="tcblue">✔</span> | <span class="tcblue">✔</span> | <span class="tcblue">✔</span> | Trusted Language Extensions for PostgreSQL |
| [plv8](/plv8) | 3.2.3 | **<span class="tcblue">PostgreSQL</span>** | **<span class="tcwarn">PIGSTY</span>** | `postgresql-$v-plv8` | <span class="tcblue">✔</span> | <span class="tcblue">✔</span> | <span class="tcblue">✔</span> | <span class="tcblue">✔</span> | <span class="tcblue">✔</span> | <span class="tcblue">✔</span> | PL/JavaScript (v8) trusted procedural language |
| [pllua](/pllua) | 2.0 | **<span class="tcblue">MIT</span>** | **<span class="tccyan">PGDG</span>** | `postgresql-$v-pllua` | <span class="tcblue">✔</span> | <span class="tcblue">✔</span> | <span class="tcblue">✔</span> | <span class="tcblue">✔</span> | <span class="tcblue">✔</span> | <span class="tcblue">✔</span> | Lua as a procedural language |
| [plprql](/plprql) | 0.1.0 | **<span class="tccyan">Apache-2</span>** | **<span class="tcwarn">PIGSTY</span>** | `postgresql-$v-plprql` |  | <span class="tcblue">✔</span> | <span class="tcblue">✔</span> | <span class="tcblue">✔</span> | <span class="tcblue">✔</span> | <span class="tcblue">✔</span> | Use PRQL in PostgreSQL - Pipelined Relational Query Language |
| [pldebugger](/pldbgapi) | 1.1 | **<span class="tccyan">Artistic</span>** | **<span class="tccyan">PGDG</span>** | `postgresql-$v-pldebugger` | <span class="tcblue">✔</span> | <span class="tcblue">✔</span> | <span class="tcblue">✔</span> | <span class="tcblue">✔</span> | <span class="tcblue">✔</span> | <span class="tcblue">✔</span> | server-side support for debugging PL/pgSQL functions |
| [plpgsql_check](/plpgsql_check) | 2.7 | **<span class="tcblue">MIT</span>** | **<span class="tccyan">PGDG</span>** | `postgresql-$v-plpgsql-check` | <span class="tcblue">✔</span> | <span class="tcblue">✔</span> | <span class="tcblue">✔</span> | <span class="tcblue">✔</span> | <span class="tcblue">✔</span> | <span class="tcblue">✔</span> | extended check for plpgsql functions |
| [plprofiler](/plprofiler) | 4.2 | **<span class="tccyan">Artistic</span>** | **<span class="tccyan">PGDG</span>** | `postgresql-$v-plprofiler` | <span class="tcblue">✔</span> | <span class="tcblue">✔</span> | <span class="tcblue">✔</span> | <span class="tcblue">✔</span> | <span class="tcblue">✔</span> | <span class="tcblue">✔</span> | server-side support for profiling PL/pgSQL functions |
| [plsh](/plsh) | 2 | **<span class="tcblue">MIT</span>** | **<span class="tccyan">PGDG</span>** | `postgresql-$v-plsh` | <span class="tcblue">✔</span> | <span class="tcblue">✔</span> | <span class="tcblue">✔</span> | <span class="tcblue">✔</span> | <span class="tcblue">✔</span> | <span class="tcblue">✔</span> | PL/sh procedural language |
| [pljava](/pljava) | 1.6.7 | **<span class="tcblue">BSD-3</span>** | **<span class="tccyan">PGDG</span>** | `postgresql-$v-pljava` |  | <span class="tcblue">✔</span> | <span class="tcblue">✔</span> | <span class="tcblue">✔</span> | <span class="tcblue">✔</span> | <span class="tcblue">✔</span> | PL/Java procedural language (https://tada.github.io/pljava/) |
| [plr](/plr) | 8.4.6 | **<span class="tcwarn">GPLv2</span>** | **<span class="tccyan">PGDG</span>** | `postgresql-$v-plr` | <span class="tcblue">✔</span> | <span class="tcblue">✔</span> | <span class="tcblue">✔</span> | <span class="tcblue">✔</span> | <span class="tcblue">✔</span> | <span class="tcblue">✔</span> | load R interpreter and execute R script from within a database |
| [pgtap](/pgtap) | 1.3.3 | **<span class="tcblue">PostgreSQL</span>** | **<span class="tccyan">PGDG</span>** | `postgresql-$v-pgtap` |  | <span class="tcblue">✔</span> | <span class="tcblue">✔</span> | <span class="tcblue">✔</span> | <span class="tcblue">✔</span> | <span class="tcblue">✔</span> | Unit testing for PostgreSQL |
| [pltcl](/pltcl) | 1.0 | **<span class="tcblue">PostgreSQL</span>** | **<span class="tcblue">CONTRIB</span>** | `postgresql-$v` | <span class="tcblue">✔</span> | <span class="tcblue">✔</span> | <span class="tcblue">✔</span> | <span class="tcblue">✔</span> | <span class="tcblue">✔</span> | <span class="tcblue">✔</span> | PL/Tcl procedural language |
| [plperl](/plperl) | 1.0 | **<span class="tcblue">PostgreSQL</span>** | **<span class="tcblue">CONTRIB</span>** | `postgresql-$v` | <span class="tcblue">✔</span> | <span class="tcblue">✔</span> | <span class="tcblue">✔</span> | <span class="tcblue">✔</span> | <span class="tcblue">✔</span> | <span class="tcblue">✔</span> | PL/Perl procedural language |
| [plperlu](/plperlu) | 1.0 | **<span class="tcblue">PostgreSQL</span>** | **<span class="tcblue">CONTRIB</span>** | `postgresql-$v` | <span class="tcblue">✔</span> | <span class="tcblue">✔</span> | <span class="tcblue">✔</span> | <span class="tcblue">✔</span> | <span class="tcblue">✔</span> | <span class="tcblue">✔</span> | PL/PerlU untrusted procedural language |
| [plpgsql](/plpgsql) | 1.0 | **<span class="tcblue">PostgreSQL</span>** | **<span class="tcblue">CONTRIB</span>** | `postgresql-$v` | <span class="tcblue">✔</span> | <span class="tcblue">✔</span> | <span class="tcblue">✔</span> | <span class="tcblue">✔</span> | <span class="tcblue">✔</span> | <span class="tcblue">✔</span> | PL/pgSQL procedural language |
| [plpython3u](/plpython3u) | 1.0 | **<span class="tcblue">PostgreSQL</span>** | **<span class="tcblue">CONTRIB</span>** | `postgresql-$v` | <span class="tcblue">✔</span> | <span class="tcblue">✔</span> | <span class="tcblue">✔</span> | <span class="tcblue">✔</span> | <span class="tcblue">✔</span> | <span class="tcblue">✔</span> | PL/Python3U untrusted procedural language |



```yaml
pg17: pg_tle_17* plv8_17* pllua_17* pldebugger_17* plpgsql_check_17* plprofiler_17* plsh_17* # #plprql_17 #pljava_17* #plr_17* #pgtap_17* #postgresql_faker_17* #dbt2-pg17-extensions*
pg16: pg_tle_16* plv8_16* pllua_16* plprql_16 pldebugger_16* plpgsql_check_16* plprofiler_16* plsh_16* # #pljava_16* #plr_16* #pgtap_16* #postgresql_faker_16* #dbt2-pg16-extensions*
pg15: pg_tle_15* plv8_15* pllua_15* plprql_15 pldebugger_15* plpgsql_check_15* plprofiler_15* plsh_15* # #pljava_15* #plr_15* #pgtap_15* #postgresql_faker_15* #dbt2-pg15-extensions*
pg14: pg_tle_14* plv8_14* pllua_14* plprql_14 pldebugger_14* plpgsql_check_14* plprofiler_14* plsh_14* # #pljava_14* #plr_14* #pgtap_14* #postgresql_faker_14* #dbt2-pg14-extensions*
pg13: pg_tle_13* plv8_13* pllua_13* plprql_13 pldebugger_13* plpgsql_check_13* plprofiler_13* plsh_13* # #pljava_13* #plr_13* #pgtap_13* #postgresql_faker_13* #dbt2-pg13-extensions*
pg12: pg_tle_12* plv8_12* pllua_12* plprql_12 pldebugger_12* plpgsql_check_12* plprofiler_12* plsh_12* # #pljava_12* #plr_12* #pgtap_12* #postgresql_faker_12* #dbt2-pg12-extensions*
```



--------

## pg_tle

[`pg_tle`](/pg_tle): Trusted Language Extensions for PostgreSQL

## plv8

[`plv8`](/plv8): PL/JavaScript (v8) trusted procedural language

## pllua

[`pllua`](/pllua): Lua as a procedural language

## hstore_pllua

[`hstore_pllua`](/hstore_pllua): (package alias: `pllua`) Hstore transform for Lua

## plluau

[`plluau`](/plluau): (package alias: `pllua`) Lua as an untrusted procedural language

## hstore_plluau

[`hstore_plluau`](/hstore_plluau): (package alias: `pllua`) Hstore transform for untrusted Lua

## plprql

[`plprql`](/plprql): Use PRQL in PostgreSQL - Pipelined Relational Query Language

## pldbgapi

[`pldbgapi`](/pldbgapi): (package alias: `pldebugger`) server-side support for debugging PL/pgSQL functions

## plpgsql_check

[`plpgsql_check`](/plpgsql_check): extended check for plpgsql functions

## plprofiler

[`plprofiler`](/plprofiler): server-side support for profiling PL/pgSQL functions

## plsh

[`plsh`](/plsh): PL/sh procedural language

## pljava

[`pljava`](/pljava): PL/Java procedural language (https://tada.github.io/pljava/)

## plr

[`plr`](/plr): load R interpreter and execute R script from within a database

## pgtap

[`pgtap`](/pgtap): Unit testing for PostgreSQL

## faker

[`faker`](/faker): Wrapper for the Faker Python library

## dbt2

[`dbt2`](/dbt2): OSDL-DBT-2 test kit

## pltcl

[`pltcl`](/pltcl): PL/Tcl procedural language

## pltclu

[`pltclu`](/pltclu): (package alias: `pltcl`) PL/TclU untrusted procedural language

## plperl

[`plperl`](/plperl): PL/Perl procedural language

## bool_plperl

[`bool_plperl`](/bool_plperl): (package alias: `plperl`) transform between bool and plperl

## hstore_plperl

[`hstore_plperl`](/hstore_plperl): (package alias: `plperl`) transform between hstore and plperl

## jsonb_plperl

[`jsonb_plperl`](/jsonb_plperl): (package alias: `plperl`) transform between jsonb and plperl

## plperlu

[`plperlu`](/plperlu): PL/PerlU untrusted procedural language

## bool_plperlu

[`bool_plperlu`](/bool_plperlu): (package alias: `plperlu`) transform between bool and plperlu

## jsonb_plperlu

[`jsonb_plperlu`](/jsonb_plperlu): (package alias: `plperlu`) transform between jsonb and plperlu

## hstore_plperlu

[`hstore_plperlu`](/hstore_plperlu): (package alias: `plperlu`) transform between hstore and plperlu

## plpgsql

[`plpgsql`](/plpgsql): PL/pgSQL procedural language

## plpython3u

[`plpython3u`](/plpython3u): PL/Python3U untrusted procedural language

## jsonb_plpython3u

[`jsonb_plpython3u`](/jsonb_plpython3u): (package alias: `plpython3u`) transform between jsonb and plpython3u

## ltree_plpython3u

[`ltree_plpython3u`](/ltree_plpython3u): (package alias: `plpython3u`) transform between ltree and plpython3u

## hstore_plpython3u

[`hstore_plpython3u`](/hstore_plpython3u): (package alias: `plpython3u`) transform between hstore and plpython3u