# FUNC


> FUNC: Functionality such as sync/async HTTP, GZIP, JWT, SaltedHash, Extra Window Aggs, PCRE, ICU, ID & Rand Generator, etc...
## Extensions


There are 56 available extensions in this category:

[`topn`](/topn) [`gzip`](/gzip) [`zstd`](/zstd) [`http`](/http) [`pg_net`](/pg_net) [`pg_html5_email_address`](/pg_html5_email_address) [`pgsql_tweaks`](/pgsql_tweaks) [`pg_extra_time`](/pg_extra_time) [`timeit`](/timeit) [`count_distinct`](/count_distinct) [`extra_window_functions`](/extra_window_functions) [`first_last_agg`](/first_last_agg) [`tdigest`](/tdigest) [`aggs_for_vecs`](/aggs_for_vecs) [`aggs_for_arrays`](/aggs_for_arrays) [`arraymath`](/arraymath) [`quantile`](/quantile) [`lower_quantile`](/lower_quantile) [`pg_idkit`](/pg_idkit) [`pg_uuidv7`](/pg_uuidv7) [`permuteseq`](/permuteseq) [`pg_hashids`](/pg_hashids) [`sequential_uuids`](/sequential_uuids) [`pg_math`](/pg_math) [`random`](/random) [`base36`](/base36) [`base62`](/base62) [`pg_base58`](/pg_base58) [`floatvec`](/floatvec) [`financial`](/financial) [`pgjwt`](/pgjwt) [`pg_hashlib`](/pg_hashlib) [`shacrypt`](/shacrypt) [`cryptint`](/cryptint) [`pguecc`](/pguecc) [`pgpcre`](/pgpcre) [`icu_ext`](/icu_ext) [`pgqr`](/pgqr) [`envvar`](/envvar) [`pg_protobuf`](/pg_protobuf) [`url_encode`](/url_encode) [`refint`](/refint) [`autoinc`](/autoinc) [`insert_username`](/insert_username) [`moddatetime`](/moddatetime) [`tsm_system_time`](/tsm_system_time) [`dict_xsyn`](/dict_xsyn) [`tsm_system_rows`](/tsm_system_rows) [`tcn`](/tcn) [`uuid-ossp`](/uuid-ossp) [`btree_gist`](/btree_gist) [`btree_gin`](/btree_gin) [`intarray`](/intarray) [`intagg`](/intagg) [`dict_int`](/dict_int) [`unaccent`](/unaccent)


| ID | Extension | Version | Package | License | RPM | DEB | Website | `LOAD` | `DYLIB` | `DDL` | Description |
|:--:|-----------|:-------:|---------|:-------:|:---:|:---:|:-------:|:------:|:-------:|:-----:|-------------|
| 3000 | [topn](/topn) | 2.6.0 | [topn](/topn) | **<span class="tcwarn">AGPLv3</span>** | **<span class="tccyan">PGDG</span>** | **<span class="tccyan">PGDG</span>** | [LINK](https://github.com/citusdata/postgresql-topn) |  | <span class="tcblue">✔</span> | <span class="tcblue">✔</span> | type for top-n JSONB |
| 3010 | [gzip](/gzip) | 1.0 | [pg_gzip](/gzip) | **<span class="tcblue">MIT</span>** | **<span class="tccyan">PGDG</span>** | **<span class="tcwarn">PIGSTY</span>** | [LINK](https://github.com/pramsey/pgsql-gzip) |  | <span class="tcblue">✔</span> | <span class="tcblue">✔</span> | gzip and gunzip functions. |
| 3020 | [zstd](/zstd) | 1.1.0 | [pg_zstd](/zstd) | **<span class="tcblue">ISC</span>** | **<span class="tcwarn">PIGSTY</span>** | **<span class="tcwarn">PIGSTY</span>** | [LINK](https://github.com/grahamedgecombe/pgzstd) |  | <span class="tcblue">✔</span> | <span class="tcblue">✔</span> | Zstandard compression algorithm implementation in PostgreSQL |
| 3030 | [http](/http) | 1.6 | [pg_http](/http) | **<span class="tcblue">MIT</span>** | **<span class="tccyan">PGDG</span>** | **<span class="tccyan">PGDG</span>** | [LINK](https://github.com/pramsey/pgsql-http) |  | <span class="tcblue">✔</span> | <span class="tcblue">✔</span> | HTTP client for PostgreSQL, allows web page retrieval inside the database. |
| 3040 | [pg_net](/pg_net) | 0.9.2 | [pg_net](/pg_net) | **<span class="tccyan">Apache-2</span>** | **<span class="tcwarn">PIGSTY</span>** | **<span class="tcwarn">PIGSTY</span>** | [LINK](https://github.com/supabase/pg_net) | <span class="tcred">❗</span> | <span class="tcblue">✔</span> | <span class="tcblue">✔</span> | Async HTTP Requests |
| 3050 | [pg_html5_email_address](/pg_html5_email_address) | 1.2.3 | [pg_html5_email_address](/pg_html5_email_address) | **<span class="tcblue">PostgreSQL</span>** | **<span class="tcwarn">PIGSTY</span>** | **<span class="tcwarn">PIGSTY</span>** | [LINK](https://github.com/bigsmoke/pg_html5_email_address) |  | <span class="tcwarn">✘</span> | <span class="tcblue">✔</span> | PostgreSQL email validation that is consistent with the HTML5 spec |
| 3060 | [pgsql_tweaks](/pgsql_tweaks) | 0.10.6 | [pgsql_tweaks](/pgsql_tweaks) | **<span class="tcblue">PostgreSQL</span>** | **<span class="tccyan">PGDG</span>** | **<span class="tcwarn">PIGSTY</span>** | [LINK](https://github.com/sjstoelting/pgsql-tweaks) |  | <span class="tcblue">✔</span> | <span class="tcblue">✔</span> | Some functions and views for daily usage |
| 3070 | [pg_extra_time](/pg_extra_time) | 1.1.3 | [pg_extra_time](/pg_extra_time) | **<span class="tcblue">PostgreSQL</span>** | **<span class="tccyan">PGDG</span>** | **<span class="tcwarn">PIGSTY</span>** | [LINK](https://github.com/bigsmoke/pg_extra_time) |  | <span class="tcblue">✔</span> | <span class="tcblue">✔</span> | Some date time functions and operators that, |
| 3080 | [timeit](/timeit) | 1.0 | [pg_timeit](/timeit) | **<span class="tcblue">PostgreSQL</span>** | **<span class="tcwarn">PIGSTY</span>** | **<span class="tcwarn">PIGSTY</span>** | [LINK](https://github.com/joelonsql/pg-timeit) |  | <span class="tcblue">✔</span> | <span class="tcblue">✔</span> | High-accuracy timing of SQL expressions |
| 3100 | [count_distinct](/count_distinct) | 3.0.1 | [count_distinct](/count_distinct) | **<span class="tcblue">BSD-2</span>** | **<span class="tccyan">PGDG</span>** | **<span class="tcwarn">PIGSTY</span>** | [LINK](https://github.com/tvondra/count_distinct) |  | <span class="tcblue">✔</span> | <span class="tcblue">✔</span> | An alternative to COUNT(DISTINCT …) aggregate, usable with HashAggregate |
| 3110 | [extra_window_functions](/extra_window_functions) | 1.0 | [extra_window_functions](/extra_window_functions) | **<span class="tcblue">PostgreSQL</span>** | **<span class="tccyan">PGDG</span>** | **<span class="tccyan">PGDG</span>** | [LINK](https://github.com/xocolatl/extra_window_functions) |  | <span class="tcblue">✔</span> | <span class="tcblue">✔</span> | Extra Window Functions for PostgreSQL |
| 3120 | [first_last_agg](/first_last_agg) | 0.1.4 | [first_last_agg](/first_last_agg) | **<span class="tcblue">PostgreSQL</span>** | **<span class="tcwarn">PIGSTY</span>** | **<span class="tccyan">PGDG</span>** | [LINK](https://github.com/wulczer/first_last_agg) |  | <span class="tcblue">✔</span> | <span class="tcblue">✔</span> | first() and last() aggregate functions |
| 3130 | [tdigest](/tdigest) | 1.4.1 | [tdigest](/tdigest) | **<span class="tccyan">Apache-2</span>** | **<span class="tccyan">PGDG</span>** | **<span class="tccyan">PGDG</span>** | [LINK](https://github.com/tdunning/t-digest) |  | <span class="tcblue">✔</span> | <span class="tcblue">✔</span> | Provides tdigest aggregate function. |
| 3140 | [aggs_for_vecs](/aggs_for_vecs) | 1.3.0 | [aggs_for_vecs](/aggs_for_vecs) | **<span class="tcblue">MIT</span>** | **<span class="tcwarn">PIGSTY</span>** | **<span class="tcwarn">PIGSTY</span>** | [LINK](https://github.com/pjungwir/aggs_for_vecs) |  | <span class="tcblue">✔</span> | <span class="tcblue">✔</span> | Aggregate functions for array inputs |
| 3150 | [aggs_for_arrays](/aggs_for_arrays) | 1.3.2 | [aggs_for_arrays](/aggs_for_arrays) | **<span class="tcblue">MIT</span>** | **<span class="tcwarn">PIGSTY</span>** | **<span class="tcwarn">PIGSTY</span>** | [LINK](https://github.com/pjungwir/aggs_for_arrays) |  | <span class="tcblue">✔</span> | <span class="tcblue">✔</span> | Various functions for computing statistics on arrays of numbers |
| 3160 | [arraymath](/arraymath) | 1.1 | [pg_arraymath](/arraymath) | **<span class="tcblue">MIT</span>** | **<span class="tcwarn">PIGSTY</span>** | **<span class="tcwarn">PIGSTY</span>** | [LINK](https://github.com/pramsey/pgsql-arraymath) |  | <span class="tcblue">✔</span> | <span class="tcblue">✔</span> | Array math and operators that work element by element on the contents of arrays |
| 3170 | [quantile](/quantile) | 1.1.7 | [quantile](/quantile) | **<span class="tcblue">BSD-2</span>** | **<span class="tcwarn">PIGSTY</span>** | **<span class="tcwarn">PIGSTY</span>** | [LINK](https://github.com/tvondra/quantile) |  | <span class="tcblue">✔</span> | <span class="tcblue">✔</span> | Quantile aggregation function |
| 3180 | [lower_quantile](/lower_quantile) | 1.0.0 | [lower_quantile](/lower_quantile) | **<span class="tcblue">BSD-2</span>** | **<span class="tcwarn">PIGSTY</span>** | **<span class="tcwarn">PIGSTY</span>** | [LINK](https://github.com/tvondra/lower_quantile) |  | <span class="tcblue">✔</span> | <span class="tcblue">✔</span> | Lower quantile aggregate function |
| 3200 | [pg_idkit](/pg_idkit) | 0.2.4 | [pg_idkit](/pg_idkit) | **<span class="tccyan">Apache-2</span>** | **<span class="tcwarn">PIGSTY</span>** | **<span class="tcwarn">PIGSTY</span>** | [LINK](https://github.com/VADOSWARE/pg_idkit) |  | <span class="tcblue">✔</span> | <span class="tcblue">✔</span> | multi-tool for generating new/niche universally unique identifiers (ex. UUIDv6, ULID, KSUID) |
| 3210 | [pg_uuidv7](/pg_uuidv7) | 1.6 | [pg_uuidv7](/pg_uuidv7) | **<span class="tccyan">MPLv2</span>** | **<span class="tccyan">PGDG</span>** | **<span class="tcwarn">PIGSTY</span>** | [LINK](https://github.com/fboulnois/pg_uuidv7) |  | <span class="tcblue">✔</span> | <span class="tcblue">✔</span> | pg_uuidv7: create UUIDv7 values in postgres |
| 3220 | [permuteseq](/permuteseq) | 1.2 | [permuteseq](/permuteseq) | **<span class="tcblue">PostgreSQL</span>** | **<span class="tcwarn">PIGSTY</span>** | **<span class="tcwarn">PIGSTY</span>** | [LINK](https://github.com/dverite/permuteseq) |  | <span class="tcblue">✔</span> | <span class="tcblue">✔</span> | Pseudo-randomly permute sequences with a format-preserving encryption on elements |
| 3230 | [pg_hashids](/pg_hashids) | 1.3 | [pg_hashids](/pg_hashids) | **<span class="tcblue">MIT</span>** | **<span class="tcwarn">PIGSTY</span>** | **<span class="tcwarn">PIGSTY</span>** | [LINK](https://github.com/iCyberon/pg_hashids) |  | <span class="tcblue">✔</span> | <span class="tcblue">✔</span> | Short unique id generator for PostgreSQL, using hashids |
| 3240 | [sequential_uuids](/sequential_uuids) | 1.0.2 | [sequential_uuids](/sequential_uuids) | **<span class="tcblue">MIT</span>** | **<span class="tccyan">PGDG</span>** | **<span class="tcwarn">PIGSTY</span>** | [LINK](https://github.com/tvondra/sequential-uuids) |  | <span class="tcblue">✔</span> | <span class="tcblue">✔</span> | generator of sequential UUIDs |
| 3300 | [pg_math](/pg_math) | 1.0 | [pg_math](/pg_math) | **<span class="tcwarn">GPLv3</span>** | **<span class="tcwarn">PIGSTY</span>** | **<span class="tcwarn">PIGSTY</span>** | [LINK](https://github.com/chanukyasds/pg_math) |  | <span class="tcblue">✔</span> | <span class="tcblue">✔</span> | GSL statistical functions for postgresql |
| 3310 | [random](/random) | 2.0.0-dev | [pg_random](/random) | **<span class="tcblue">PostgreSQL</span>** | **<span class="tcwarn">PIGSTY</span>** | **<span class="tcwarn">PIGSTY</span>** | [LINK](https://github.com/tvondra/random) |  | <span class="tcblue">✔</span> | <span class="tcblue">✔</span> | random data generator |
| 3320 | [base36](/base36) | 1.0.0 | [pg_base36](/base36) | **<span class="tcblue">MIT</span>** | **<span class="tcwarn">PIGSTY</span>** | **<span class="tcwarn">PIGSTY</span>** | [LINK](https://github.com/adjust/pg-base36) |  | <span class="tcblue">✔</span> | <span class="tcblue">✔</span> | Integer Base36 types |
| 3330 | [base62](/base62) | 0.0.1 | [pg_base62](/base62) | **<span class="tcblue">MIT</span>** | **<span class="tcwarn">PIGSTY</span>** | **<span class="tcwarn">PIGSTY</span>** | [LINK](https://github.com/adjust/pg-base62) |  | <span class="tcblue">✔</span> | <span class="tcblue">✔</span> | Base62 extension for PostgreSQL |
| 3340 | [pg_base58](/pg_base58) | 0.0.1 | [pg_base58](/pg_base58) | **<span class="tcblue">MIT</span>** | **<span class="tcwarn">PIGSTY</span>** | **<span class="tcwarn">PIGSTY</span>** | [LINK](https://github.com/Fell-x27/pg_base58) |  | <span class="tcblue">✔</span> | <span class="tcblue">✔</span> | Base58 Encoder/Decoder Extension for PostgreSQL |
| 3350 | [floatvec](/floatvec) | 1.0.1 | [floatvec](/floatvec) | **<span class="tcblue">MIT</span>** | **<span class="tcwarn">PIGSTY</span>** | **<span class="tcwarn">PIGSTY</span>** | [LINK](https://github.com/pjungwir/floatvec) |  | <span class="tcblue">✔</span> | <span class="tcblue">✔</span> | Math for vectors (arrays) of numbers |
| 3360 | [financial](/financial) | 1.0.1 | [pg_financial](/financial) | **<span class="tcblue">PostgreSQL</span>** | **<span class="tcwarn">PIGSTY</span>** | **<span class="tcwarn">PIGSTY</span>** | [LINK](https://github.com/intgr/pg_financial) |  | <span class="tcblue">✔</span> | <span class="tcblue">✔</span> | Financial aggregate functions |
| 3400 | [pgjwt](/pgjwt) | 0.2.0 | [pgjwt](/pgjwt) | **<span class="tcblue">MIT</span>** | **<span class="tcwarn">PIGSTY</span>** | **<span class="tcwarn">PIGSTY</span>** | [LINK](https://github.com/michelp/pgjwt) |  | <span class="tcblue">✔</span> | <span class="tcblue">✔</span> | JSON Web Token API for Postgresql |
| 3410 | [pg_hashlib](/pg_hashlib) | 1.1 | [pg_hashlib](/pg_hashlib) | **<span class="tcblue">PostgreSQL</span>** | **<span class="tcwarn">PIGSTY</span>** | **<span class="tcwarn">PIGSTY</span>** | [LINK](https://github.com/markokr/pghashlib) |  | <span class="tcblue">✔</span> | <span class="tcblue">✔</span> | Stable hash functions for Postgres |
| 3420 | [shacrypt](/shacrypt) | 1.1 | [shacrypt](/shacrypt) | **<span class="tcblue">PostgreSQL</span>** | **<span class="tcwarn">PIGSTY</span>** | **<span class="tcwarn">PIGSTY</span>** | [LINK](https://github.com/dverite/postgres-shacrypt) |  | <span class="tcblue">✔</span> | <span class="tcblue">✔</span> | Implements SHA256-CRYPT and SHA512-CRYPT password encryption schemes |
| 3430 | [cryptint](/cryptint) | 1.0.0 | [cryptint](/cryptint) | **<span class="tcblue">PostgreSQL</span>** | **<span class="tcwarn">PIGSTY</span>** | **<span class="tcwarn">PIGSTY</span>** | [LINK](https://github.com/dverite/cryptint) |  | <span class="tcblue">✔</span> | <span class="tcblue">✔</span> | Encryption functions for int and bigint values |
| 3440 | [pguecc](/pguecc) | 1.0 | [pg_ecdsa](/pguecc) | **<span class="tcblue">BSD-2</span>** | **<span class="tcwarn">PIGSTY</span>** | **<span class="tcwarn">PIGSTY</span>** | [LINK](https://github.com/ameensol/pg-ecdsa) |  | <span class="tcblue">✔</span> | <span class="tcblue">✔</span> | uECC bindings for Postgres |
| 3500 | [pgpcre](/pgpcre) | 1 | [pgpcre](/pgpcre) | **<span class="tcblue">PostgreSQL</span>** | **<span class="tcwarn">PIGSTY</span>** | **<span class="tccyan">PGDG</span>** | [LINK](https://github.com/petere/pgpcre) |  | <span class="tcblue">✔</span> | <span class="tcblue">✔</span> | Perl Compatible Regular Expression functions |
| 3510 | [icu_ext](/icu_ext) | 1.9 | [icu_ext](/icu_ext) | **<span class="tcblue">PostgreSQL</span>** | **<span class="tcwarn">PIGSTY</span>** | **<span class="tccyan">PGDG</span>** | [LINK](https://github.com/dverite/icu_ext) |  | <span class="tcblue">✔</span> | <span class="tcblue">✔</span> | Access ICU functions |
| 3520 | [pgqr](/pgqr) | 1.0 | [pgqr](/pgqr) | **<span class="tcblue">BSD-3</span>** | **<span class="tcwarn">PIGSTY</span>** | **<span class="tcwarn">PIGSTY</span>** | [LINK](https://github.com/AbdulYadi/pgqr) |  | <span class="tcblue">✔</span> | <span class="tcblue">✔</span> | QR Code generator from PostgreSQL |
| 3530 | [envvar](/envvar) | 1.0.0 | [envvar](/envvar) | **<span class="tcblue">PostgreSQL</span>** | **<span class="tcwarn">PIGSTY</span>** | **<span class="tcwarn">PIGSTY</span>** | [LINK](https://github.com/theory/pg-envvar) |  | <span class="tcblue">✔</span> | <span class="tcblue">✔</span> | Fetch the value of an environment variable |
| 3540 | [pg_protobuf](/pg_protobuf) | 1.0 | [pg_protobuf](/pg_protobuf) | **<span class="tcblue">MIT</span>** | **<span class="tcwarn">PIGSTY</span>** | **<span class="tcwarn">PIGSTY</span>** | [LINK](https://github.com/afiskon/pg_protobuf) |  | <span class="tcblue">✔</span> | <span class="tcblue">✔</span> | Protobuf support for PostgreSQL |
| 3550 | [url_encode](/url_encode) | 1.2 | [url_encode](/url_encode) | **<span class="tcblue">PostgreSQL</span>** | **<span class="tcwarn">PIGSTY</span>** | **<span class="tcwarn">PIGSTY</span>** | [LINK](https://github.com/okbob/url_encode) |  | <span class="tcblue">✔</span> | <span class="tcblue">✔</span> | url_encode, url_decode functions |
| 3840 | [refint](/refint) | 1.0 | [refint](/refint) | **<span class="tcblue">PostgreSQL</span>** | **<span class="tcblue">CONTRIB</span>** | **<span class="tcblue">CONTRIB</span>** | [LINK](https://www.postgresql.org/docs/current/contrib-spi.html#CONTRIB-SPI-REFINT) |  | <span class="tcblue">✔</span> | <span class="tcblue">✔</span> | functions for implementing referential integrity (obsolete) |
| 3841 | [autoinc](/autoinc) | 1.0 | [autoinc](/autoinc) | **<span class="tcblue">PostgreSQL</span>** | **<span class="tcblue">CONTRIB</span>** | **<span class="tcblue">CONTRIB</span>** | [LINK](https://www.postgresql.org/docs/current/contrib-spi.html#CONTRIB-SPI-AUTOINC) |  | <span class="tcblue">✔</span> | <span class="tcblue">✔</span> | functions for autoincrementing fields |
| 3842 | [insert_username](/insert_username) | 1.0 | [insert_username](/insert_username) | **<span class="tcblue">PostgreSQL</span>** | **<span class="tcblue">CONTRIB</span>** | **<span class="tcblue">CONTRIB</span>** | [LINK](https://www.postgresql.org/docs/current/contrib-spi.html#CONTRIB-SPI-INSERT-USERNAME) |  | <span class="tcblue">✔</span> | <span class="tcblue">✔</span> | functions for tracking who changed a table |
| 3843 | [moddatetime](/moddatetime) | 1.0 | [moddatetime](/moddatetime) | **<span class="tcblue">PostgreSQL</span>** | **<span class="tcblue">CONTRIB</span>** | **<span class="tcblue">CONTRIB</span>** | [LINK](https://www.postgresql.org/docs/current/contrib-spi.html#CONTRIB-SPI-MODDATETIME) |  | <span class="tcblue">✔</span> | <span class="tcblue">✔</span> | functions for tracking last modification time |
| 3850 | [tsm_system_time](/tsm_system_time) | 1.0 | [tsm_system_time](/tsm_system_time) | **<span class="tcblue">PostgreSQL</span>** | **<span class="tcblue">CONTRIB</span>** | **<span class="tcblue">CONTRIB</span>** | [LINK](https://www.postgresql.org/docs/current/tsm-system-time.html) |  | <span class="tcblue">✔</span> | <span class="tcblue">✔</span> | TABLESAMPLE method which accepts time in milliseconds as a limit |
| 3870 | [dict_xsyn](/dict_xsyn) | 1.0 | [dict_xsyn](/dict_xsyn) | **<span class="tcblue">PostgreSQL</span>** | **<span class="tcblue">CONTRIB</span>** | **<span class="tcblue">CONTRIB</span>** | [LINK](https://www.postgresql.org/docs/current/dict-xsyn.html) |  | <span class="tcblue">✔</span> | <span class="tcblue">✔</span> | text search dictionary template for extended synonym processing |
| 3880 | [tsm_system_rows](/tsm_system_rows) | 1.0 | [tsm_system_rows](/tsm_system_rows) | **<span class="tcblue">PostgreSQL</span>** | **<span class="tcblue">CONTRIB</span>** | **<span class="tcblue">CONTRIB</span>** | [LINK](https://www.postgresql.org/docs/current/tsm-system-rows.html) |  | <span class="tcblue">✔</span> | <span class="tcblue">✔</span> | TABLESAMPLE method which accepts number of rows as a limit |
| 3890 | [tcn](/tcn) | 1.0 | [tcn](/tcn) | **<span class="tcblue">PostgreSQL</span>** | **<span class="tcblue">CONTRIB</span>** | **<span class="tcblue">CONTRIB</span>** | [LINK](https://www.postgresql.org/docs/current/tcn.html) |  | <span class="tcblue">✔</span> | <span class="tcblue">✔</span> | Triggered change notifications |
| 3900 | [uuid-ossp](/uuid-ossp) | 1.1 | [uuid-ossp](/uuid-ossp) | **<span class="tcblue">PostgreSQL</span>** | **<span class="tcblue">CONTRIB</span>** | **<span class="tcblue">CONTRIB</span>** | [LINK](https://www.postgresql.org/docs/current/uuid-ossp.html) |  | <span class="tcblue">✔</span> | <span class="tcblue">✔</span> | generate universally unique identifiers (UUIDs) |
| 3910 | [btree_gist](/btree_gist) | 1.7 | [btree_gist](/btree_gist) | **<span class="tcblue">PostgreSQL</span>** | **<span class="tcblue">CONTRIB</span>** | **<span class="tcblue">CONTRIB</span>** | [LINK](https://www.postgresql.org/docs/current/btree-gist.html) |  | <span class="tcblue">✔</span> | <span class="tcblue">✔</span> | support for indexing common datatypes in GiST |
| 3920 | [btree_gin](/btree_gin) | 1.3 | [btree_gin](/btree_gin) | **<span class="tcblue">PostgreSQL</span>** | **<span class="tcblue">CONTRIB</span>** | **<span class="tcblue">CONTRIB</span>** | [LINK](https://www.postgresql.org/docs/current/btree-gin.html) |  | <span class="tcblue">✔</span> | <span class="tcblue">✔</span> | support for indexing common datatypes in GIN |
| 3930 | [intarray](/intarray) | 1.5 | [intarray](/intarray) | **<span class="tcblue">PostgreSQL</span>** | **<span class="tcblue">CONTRIB</span>** | **<span class="tcblue">CONTRIB</span>** | [LINK](https://www.postgresql.org/docs/current/intarray.html) |  | <span class="tcwarn">✘</span> | <span class="tcblue">✔</span> | functions, operators, and index support for 1-D arrays of integers |
| 3950 | [intagg](/intagg) | 1.1 | [intagg](/intagg) | **<span class="tcblue">PostgreSQL</span>** | **<span class="tcblue">CONTRIB</span>** | **<span class="tcblue">CONTRIB</span>** | [LINK](https://www.postgresql.org/docs/current/intagg.html) |  | <span class="tcwarn">✘</span> | <span class="tcblue">✔</span> | integer aggregator and enumerator (obsolete) |
| 3960 | [dict_int](/dict_int) | 1.0 | [dict_int](/dict_int) | **<span class="tcblue">PostgreSQL</span>** | **<span class="tcblue">CONTRIB</span>** | **<span class="tcblue">CONTRIB</span>** | [LINK](https://www.postgresql.org/docs/current/dict-int.html) |  | <span class="tcblue">✔</span> | <span class="tcblue">✔</span> | text search dictionary template for integers |
| 3990 | [unaccent](/unaccent) | 1.1 | [unaccent](/unaccent) | **<span class="tcblue">PostgreSQL</span>** | **<span class="tcblue">CONTRIB</span>** | **<span class="tcblue">CONTRIB</span>** | [LINK](https://www.postgresql.org/docs/current/unaccent.html) |  | <span class="tcblue">✔</span> | <span class="tcblue">✔</span> | text search dictionary that removes accents |



```yaml
pg17: topn pg_gzip pg_zstd pg_http pg_net pg_html5_email_address pgsql_tweaks pg_extra_time pg_timeit count_distinct extra_window_functions first_last_agg tdigest aggs_for_vecs aggs_for_arrays pg_arraymath quantile lower_quantile pg_idkit pg_uuidv7 permuteseq pg_hashids sequential_uuids pg_math pg_random pg_base36 pg_base62 pg_base58 floatvec pg_financial pgjwt pg_hashlib shacrypt cryptint pg_ecdsa pgpcre icu_ext pgqr envvar pg_protobuf url_encode 
pg16: topn pg_gzip pg_zstd pg_http pg_net pg_html5_email_address pgsql_tweaks pg_extra_time pg_timeit count_distinct extra_window_functions first_last_agg tdigest aggs_for_vecs aggs_for_arrays pg_arraymath quantile lower_quantile pg_idkit pg_uuidv7 permuteseq pg_hashids sequential_uuids pg_math pg_random pg_base36 pg_base62 pg_base58 floatvec pg_financial pgjwt pg_hashlib shacrypt cryptint pg_ecdsa pgpcre icu_ext pgqr envvar pg_protobuf url_encode 
pg15: topn pg_gzip pg_zstd pg_http pg_net pg_html5_email_address pgsql_tweaks pg_extra_time pg_timeit count_distinct extra_window_functions first_last_agg tdigest aggs_for_vecs aggs_for_arrays pg_arraymath quantile lower_quantile pg_idkit pg_uuidv7 permuteseq pg_hashids sequential_uuids pg_math pg_random pg_base36 pg_base62 pg_base58 floatvec pg_financial pgjwt pg_hashlib shacrypt cryptint pg_ecdsa pgpcre icu_ext pgqr envvar pg_protobuf url_encode 
pg14: topn pg_gzip pg_zstd pg_http pg_net pg_html5_email_address pgsql_tweaks pg_extra_time pg_timeit count_distinct extra_window_functions first_last_agg tdigest aggs_for_vecs aggs_for_arrays pg_arraymath quantile lower_quantile pg_idkit pg_uuidv7 permuteseq pg_hashids sequential_uuids pg_math pg_random pg_base36 pg_base62 pg_base58 floatvec pg_financial pgjwt pg_hashlib shacrypt cryptint pg_ecdsa pgpcre icu_ext pgqr envvar pg_protobuf url_encode 
pg13: topn pg_gzip pg_zstd pg_http pg_net pg_html5_email_address pgsql_tweaks pg_extra_time pg_timeit count_distinct extra_window_functions first_last_agg tdigest aggs_for_vecs aggs_for_arrays pg_arraymath quantile lower_quantile pg_idkit pg_uuidv7 permuteseq pg_hashids sequential_uuids pg_math pg_random pg_base36 pg_base62 pg_base58 floatvec pg_financial pgjwt pg_hashlib shacrypt cryptint pg_ecdsa pgpcre icu_ext pgqr envvar pg_protobuf url_encode 
pg12: topn pg_gzip pg_zstd pg_http pg_net pg_html5_email_address pgsql_tweaks pg_extra_time pg_timeit count_distinct extra_window_functions first_last_agg tdigest aggs_for_vecs aggs_for_arrays pg_arraymath quantile lower_quantile pg_idkit pg_uuidv7 permuteseq pg_hashids sequential_uuids pg_math pg_random pg_base36 pg_base62 pg_base58 floatvec pg_financial pgjwt pg_hashlib shacrypt cryptint pg_ecdsa pgpcre icu_ext pgqr envvar pg_protobuf url_encode 
```



--------

## RPM Packages


| Package | Version | License | RPM | RPM Package | 17 | 16 | 15 | 14 | 13 | 12 | Description |
|---------|---------|:-------:|:---:|-------------|:--:|:--:|:--:|:--:|:--:|:--:|-------------|
| [topn](/topn) | 2.6.0 | **<span class="tcwarn">AGPLv3</span>** | **<span class="tccyan">PGDG</span>** | `topn_$v*` | <span class="tcblue">✔</span> | <span class="tcblue">✔</span> | <span class="tcblue">✔</span> | <span class="tcblue">✔</span> | <span class="tcblue">✔</span> | <span class="tcblue">✔</span> | type for top-n JSONB |
| [pg_gzip](/gzip) | 1.0 | **<span class="tcblue">MIT</span>** | **<span class="tccyan">PGDG</span>** | `pgsql_gzip_$v*` | <span class="tcblue">✔</span> | <span class="tcblue">✔</span> | <span class="tcblue">✔</span> | <span class="tcblue">✔</span> | <span class="tcblue">✔</span> | <span class="tcblue">✔</span> | gzip and gunzip functions. |
| [pg_zstd](/zstd) | 1.1.0 | **<span class="tcblue">ISC</span>** | **<span class="tcwarn">PIGSTY</span>** | `pg_zstd_$v*` | <span class="tcblue">✔</span> | <span class="tcblue">✔</span> | <span class="tcblue">✔</span> | <span class="tcblue">✔</span> | <span class="tcblue">✔</span> | <span class="tcblue">✔</span> | Zstandard compression algorithm implementation in PostgreSQL |
| [pg_http](/http) | 1.6 | **<span class="tcblue">MIT</span>** | **<span class="tccyan">PGDG</span>** | `pgsql_http_$v*` | <span class="tcblue">✔</span> | <span class="tcblue">✔</span> | <span class="tcblue">✔</span> | <span class="tcblue">✔</span> | <span class="tcblue">✔</span> | <span class="tcblue">✔</span> | HTTP client for PostgreSQL, allows web page retrieval inside the database. |
| [pg_net](/pg_net) | 0.9.2 | **<span class="tccyan">Apache-2</span>** | **<span class="tcwarn">PIGSTY</span>** | `pg_net_$v*` | <span class="tcblue">✔</span> | <span class="tcblue">✔</span> | <span class="tcblue">✔</span> | <span class="tcblue">✔</span> | <span class="tcblue">✔</span> | <span class="tcblue">✔</span> | Async HTTP Requests |
| [pg_html5_email_address](/pg_html5_email_address) | 1.2.3 | **<span class="tcblue">PostgreSQL</span>** | **<span class="tcwarn">PIGSTY</span>** | `pg_html5_email_address_$v` | <span class="tcblue">✔</span> | <span class="tcblue">✔</span> | <span class="tcblue">✔</span> | <span class="tcblue">✔</span> | <span class="tcblue">✔</span> | <span class="tcblue">✔</span> | PostgreSQL email validation that is consistent with the HTML5 spec |
| [pgsql_tweaks](/pgsql_tweaks) | 0.10.6 | **<span class="tcblue">PostgreSQL</span>** | **<span class="tccyan">PGDG</span>** | `pgsql_tweaks_$v*` | <span class="tcblue">✔</span> | <span class="tcblue">✔</span> | <span class="tcblue">✔</span> | <span class="tcblue">✔</span> | <span class="tcblue">✔</span> | <span class="tcblue">✔</span> | Some functions and views for daily usage |
| [pg_extra_time](/pg_extra_time) | 1.1.3 | **<span class="tcblue">PostgreSQL</span>** | **<span class="tccyan">PGDG</span>** | `pg_extra_time_$v*` | <span class="tcblue">✔</span> | <span class="tcblue">✔</span> | <span class="tcblue">✔</span> | <span class="tcblue">✔</span> | <span class="tcblue">✔</span> | <span class="tcblue">✔</span> | Some date time functions and operators that, |
| [pg_timeit](/timeit) | 1.0 | **<span class="tcblue">PostgreSQL</span>** | **<span class="tcwarn">PIGSTY</span>** | `pg_timeit_$v*` | <span class="tcblue">✔</span> | <span class="tcblue">✔</span> | <span class="tcblue">✔</span> | <span class="tcblue">✔</span> | <span class="tcblue">✔</span> | <span class="tcblue">✔</span> | High-accuracy timing of SQL expressions |
| [count_distinct](/count_distinct) | 3.0.1 | **<span class="tcblue">BSD-2</span>** | **<span class="tccyan">PGDG</span>** | `count_distinct_$v*` | <span class="tcblue">✔</span> | <span class="tcblue">✔</span> | <span class="tcblue">✔</span> | <span class="tcblue">✔</span> | <span class="tcblue">✔</span> | <span class="tcblue">✔</span> | An alternative to COUNT(DISTINCT …) aggregate, usable with HashAggregate |
| [extra_window_functions](/extra_window_functions) | 1.0 | **<span class="tcblue">PostgreSQL</span>** | **<span class="tccyan">PGDG</span>** | `extra_window_functions_$v*` | <span class="tcblue">✔</span> | <span class="tcblue">✔</span> | <span class="tcblue">✔</span> | <span class="tcblue">✔</span> | <span class="tcblue">✔</span> | <span class="tcblue">✔</span> | Extra Window Functions for PostgreSQL |
| [first_last_agg](/first_last_agg) | 0.1.4 | **<span class="tcblue">PostgreSQL</span>** | **<span class="tcwarn">PIGSTY</span>** | `first_last_agg_$v` | <span class="tcblue">✔</span> | <span class="tcblue">✔</span> | <span class="tcblue">✔</span> | <span class="tcblue">✔</span> | <span class="tcblue">✔</span> | <span class="tcblue">✔</span> | first() and last() aggregate functions |
| [tdigest](/tdigest) | 1.4.1 | **<span class="tccyan">Apache-2</span>** | **<span class="tccyan">PGDG</span>** | `tdigest_$v*` | <span class="tcblue">✔</span> | <span class="tcblue">✔</span> | <span class="tcblue">✔</span> | <span class="tcblue">✔</span> | <span class="tcblue">✔</span> | <span class="tcblue">✔</span> | Provides tdigest aggregate function. |
| [aggs_for_vecs](/aggs_for_vecs) | 1.3.0 | **<span class="tcblue">MIT</span>** | **<span class="tcwarn">PIGSTY</span>** | `aggs_for_vecs_$v*` | <span class="tcblue">✔</span> | <span class="tcblue">✔</span> | <span class="tcblue">✔</span> | <span class="tcblue">✔</span> | <span class="tcblue">✔</span> | <span class="tcblue">✔</span> | Aggregate functions for array inputs |
| [aggs_for_arrays](/aggs_for_arrays) | 1.3.2 | **<span class="tcblue">MIT</span>** | **<span class="tcwarn">PIGSTY</span>** | `aggs_for_arrays_$v*` | <span class="tcblue">✔</span> | <span class="tcblue">✔</span> | <span class="tcblue">✔</span> | <span class="tcblue">✔</span> | <span class="tcblue">✔</span> | <span class="tcblue">✔</span> | Various functions for computing statistics on arrays of numbers |
| [pg_arraymath](/arraymath) | 1.1 | **<span class="tcblue">MIT</span>** | **<span class="tcwarn">PIGSTY</span>** | `pg_arraymath_$v*` | <span class="tcblue">✔</span> | <span class="tcblue">✔</span> | <span class="tcblue">✔</span> | <span class="tcblue">✔</span> | <span class="tcblue">✔</span> | <span class="tcblue">✔</span> | Array math and operators that work element by element on the contents of arrays |
| [quantile](/quantile) | 1.1.7 | **<span class="tcblue">BSD-2</span>** | **<span class="tcwarn">PIGSTY</span>** | `quantile_$v*` | <span class="tcblue">✔</span> | <span class="tcblue">✔</span> | <span class="tcblue">✔</span> | <span class="tcblue">✔</span> | <span class="tcblue">✔</span> | <span class="tcblue">✔</span> | Quantile aggregation function |
| [lower_quantile](/lower_quantile) | 1.0.0 | **<span class="tcblue">BSD-2</span>** | **<span class="tcwarn">PIGSTY</span>** | `lower_quantile_$v*` | <span class="tcblue">✔</span> | <span class="tcblue">✔</span> | <span class="tcblue">✔</span> | <span class="tcblue">✔</span> | <span class="tcblue">✔</span> | <span class="tcblue">✔</span> | Lower quantile aggregate function |
| [pg_idkit](/pg_idkit) | 0.2.4 | **<span class="tccyan">Apache-2</span>** | **<span class="tcwarn">PIGSTY</span>** | `pg_idkit_$v` | <span class="tcblue">✔</span> | <span class="tcblue">✔</span> | <span class="tcblue">✔</span> | <span class="tcblue">✔</span> | <span class="tcblue">✔</span> | <span class="tcblue">✔</span> | multi-tool for generating new/niche universally unique identifiers (ex. UUIDv6, ULID, KSUID) |
| [pg_uuidv7](/pg_uuidv7) | 1.6 | **<span class="tccyan">MPLv2</span>** | **<span class="tccyan">PGDG</span>** | `pg_uuidv7_$v*` | <span class="tcblue">✔</span> | <span class="tcblue">✔</span> | <span class="tcblue">✔</span> | <span class="tcblue">✔</span> | <span class="tcblue">✔</span> | <span class="tcblue">✔</span> | pg_uuidv7: create UUIDv7 values in postgres |
| [permuteseq](/permuteseq) | 1.2 | **<span class="tcblue">PostgreSQL</span>** | **<span class="tcwarn">PIGSTY</span>** | `permuteseq_$v*` | <span class="tcblue">✔</span> | <span class="tcblue">✔</span> | <span class="tcblue">✔</span> | <span class="tcblue">✔</span> | <span class="tcblue">✔</span> | <span class="tcblue">✔</span> | Pseudo-randomly permute sequences with a format-preserving encryption on elements |
| [pg_hashids](/pg_hashids) | 1.3 | **<span class="tcblue">MIT</span>** | **<span class="tcwarn">PIGSTY</span>** | `pg_hashids_$v*` | <span class="tcblue">✔</span> | <span class="tcblue">✔</span> | <span class="tcblue">✔</span> | <span class="tcblue">✔</span> | <span class="tcblue">✔</span> | <span class="tcblue">✔</span> | Short unique id generator for PostgreSQL, using hashids |
| [sequential_uuids](/sequential_uuids) | 1.0.2 | **<span class="tcblue">MIT</span>** | **<span class="tccyan">PGDG</span>** | `sequential_uuids_$v*` | <span class="tcblue">✔</span> | <span class="tcblue">✔</span> | <span class="tcblue">✔</span> | <span class="tcblue">✔</span> | <span class="tcblue">✔</span> | <span class="tcblue">✔</span> | generator of sequential UUIDs |
| [pg_math](/pg_math) | 1.0 | **<span class="tcwarn">GPLv3</span>** | **<span class="tcwarn">PIGSTY</span>** | `pg_math_$v*` | <span class="tcblue">✔</span> | <span class="tcblue">✔</span> | <span class="tcblue">✔</span> | <span class="tcblue">✔</span> | <span class="tcblue">✔</span> | <span class="tcblue">✔</span> | GSL statistical functions for postgresql |
| [pg_random](/random) | 2.0.0-dev | **<span class="tcblue">PostgreSQL</span>** | **<span class="tcwarn">PIGSTY</span>** | `pg_random_$v*` | <span class="tcblue">✔</span> | <span class="tcblue">✔</span> | <span class="tcblue">✔</span> | <span class="tcblue">✔</span> | <span class="tcblue">✔</span> | <span class="tcblue">✔</span> | random data generator |
| [pg_base36](/base36) | 1.0.0 | **<span class="tcblue">MIT</span>** | **<span class="tcwarn">PIGSTY</span>** | `pg_base36_$v*` | <span class="tcblue">✔</span> | <span class="tcblue">✔</span> | <span class="tcblue">✔</span> | <span class="tcblue">✔</span> | <span class="tcblue">✔</span> | <span class="tcblue">✔</span> | Integer Base36 types |
| [pg_base62](/base62) | 0.0.1 | **<span class="tcblue">MIT</span>** | **<span class="tcwarn">PIGSTY</span>** | `pg_base62_$v*` | <span class="tcblue">✔</span> | <span class="tcblue">✔</span> | <span class="tcblue">✔</span> | <span class="tcblue">✔</span> | <span class="tcblue">✔</span> | <span class="tcblue">✔</span> | Base62 extension for PostgreSQL |
| [pg_base58](/pg_base58) | 0.0.1 | **<span class="tcblue">MIT</span>** | **<span class="tcwarn">PIGSTY</span>** | `pg_base58_$v` | <span class="tcblue">✔</span> | <span class="tcblue">✔</span> | <span class="tcblue">✔</span> | <span class="tcblue">✔</span> | <span class="tcblue">✔</span> | <span class="tcblue">✔</span> | Base58 Encoder/Decoder Extension for PostgreSQL |
| [floatvec](/floatvec) | 1.0.1 | **<span class="tcblue">MIT</span>** | **<span class="tcwarn">PIGSTY</span>** | `floatvec_$v*` | <span class="tcblue">✔</span> | <span class="tcblue">✔</span> | <span class="tcblue">✔</span> | <span class="tcblue">✔</span> | <span class="tcblue">✔</span> | <span class="tcblue">✔</span> | Math for vectors (arrays) of numbers |
| [pg_financial](/financial) | 1.0.1 | **<span class="tcblue">PostgreSQL</span>** | **<span class="tcwarn">PIGSTY</span>** | `pg_financial_$v*` | <span class="tcblue">✔</span> | <span class="tcblue">✔</span> | <span class="tcblue">✔</span> | <span class="tcblue">✔</span> | <span class="tcblue">✔</span> | <span class="tcblue">✔</span> | Financial aggregate functions |
| [pgjwt](/pgjwt) | 0.2.0 | **<span class="tcblue">MIT</span>** | **<span class="tcwarn">PIGSTY</span>** | `pgjwt_$v*` | <span class="tcblue">✔</span> | <span class="tcblue">✔</span> | <span class="tcblue">✔</span> | <span class="tcblue">✔</span> | <span class="tcblue">✔</span> | <span class="tcblue">✔</span> | JSON Web Token API for Postgresql |
| [pg_hashlib](/pg_hashlib) | 1.1 | **<span class="tcblue">PostgreSQL</span>** | **<span class="tcwarn">PIGSTY</span>** | `pg_hashlib_$v` | <span class="tcblue">✔</span> | <span class="tcblue">✔</span> | <span class="tcblue">✔</span> | <span class="tcblue">✔</span> | <span class="tcblue">✔</span> | <span class="tcblue">✔</span> | Stable hash functions for Postgres |
| [shacrypt](/shacrypt) | 1.1 | **<span class="tcblue">PostgreSQL</span>** | **<span class="tcwarn">PIGSTY</span>** | `postgres_shacrypt_$v*` | <span class="tcblue">✔</span> | <span class="tcblue">✔</span> | <span class="tcblue">✔</span> | <span class="tcblue">✔</span> | <span class="tcblue">✔</span> | <span class="tcblue">✔</span> | Implements SHA256-CRYPT and SHA512-CRYPT password encryption schemes |
| [cryptint](/cryptint) | 1.0.0 | **<span class="tcblue">PostgreSQL</span>** | **<span class="tcwarn">PIGSTY</span>** | `cryptint_$v*` | <span class="tcblue">✔</span> | <span class="tcblue">✔</span> | <span class="tcblue">✔</span> | <span class="tcblue">✔</span> | <span class="tcblue">✔</span> | <span class="tcblue">✔</span> | Encryption functions for int and bigint values |
| [pg_ecdsa](/pguecc) | 1.0 | **<span class="tcblue">BSD-2</span>** | **<span class="tcwarn">PIGSTY</span>** | `pg_ecdsa_$v*` | <span class="tcblue">✔</span> | <span class="tcblue">✔</span> | <span class="tcblue">✔</span> | <span class="tcblue">✔</span> | <span class="tcblue">✔</span> | <span class="tcblue">✔</span> | uECC bindings for Postgres |
| [pgpcre](/pgpcre) | 1 | **<span class="tcblue">PostgreSQL</span>** | **<span class="tcwarn">PIGSTY</span>** | `pgpcre_$v` | <span class="tcblue">✔</span> | <span class="tcblue">✔</span> | <span class="tcblue">✔</span> | <span class="tcblue">✔</span> | <span class="tcblue">✔</span> | <span class="tcblue">✔</span> | Perl Compatible Regular Expression functions |
| [icu_ext](/icu_ext) | 1.9 | **<span class="tcblue">PostgreSQL</span>** | **<span class="tcwarn">PIGSTY</span>** | `icu_ext_$v*` | <span class="tcblue">✔</span> | <span class="tcblue">✔</span> | <span class="tcblue">✔</span> | <span class="tcblue">✔</span> | <span class="tcblue">✔</span> | <span class="tcblue">✔</span> | Access ICU functions |
| [pgqr](/pgqr) | 1.0 | **<span class="tcblue">BSD-3</span>** | **<span class="tcwarn">PIGSTY</span>** | `pgqr_$v*` | <span class="tcblue">✔</span> | <span class="tcblue">✔</span> | <span class="tcblue">✔</span> | <span class="tcblue">✔</span> | <span class="tcblue">✔</span> | <span class="tcblue">✔</span> | QR Code generator from PostgreSQL |
| [envvar](/envvar) | 1.0.0 | **<span class="tcblue">PostgreSQL</span>** | **<span class="tcwarn">PIGSTY</span>** | `pg_envvar_$v*` | <span class="tcblue">✔</span> | <span class="tcblue">✔</span> | <span class="tcblue">✔</span> | <span class="tcblue">✔</span> | <span class="tcblue">✔</span> | <span class="tcblue">✔</span> | Fetch the value of an environment variable |
| [pg_protobuf](/pg_protobuf) | 1.0 | **<span class="tcblue">MIT</span>** | **<span class="tcwarn">PIGSTY</span>** | `pg_protobuf_$v` | <span class="tcblue">✔</span> | <span class="tcblue">✔</span> | <span class="tcblue">✔</span> | <span class="tcblue">✔</span> | <span class="tcblue">✔</span> | <span class="tcblue">✔</span> | Protobuf support for PostgreSQL |
| [url_encode](/url_encode) | 1.2 | **<span class="tcblue">PostgreSQL</span>** | **<span class="tcwarn">PIGSTY</span>** | `url_encode_$v*` | <span class="tcblue">✔</span> | <span class="tcblue">✔</span> | <span class="tcblue">✔</span> | <span class="tcblue">✔</span> | <span class="tcblue">✔</span> | <span class="tcblue">✔</span> | url_encode, url_decode functions |
| [refint](/refint) | 1.0 | **<span class="tcblue">PostgreSQL</span>** | **<span class="tcblue">CONTRIB</span>** | `postgresql$v-contrib` | <span class="tcblue">✔</span> | <span class="tcblue">✔</span> | <span class="tcblue">✔</span> | <span class="tcblue">✔</span> | <span class="tcblue">✔</span> | <span class="tcblue">✔</span> | functions for implementing referential integrity (obsolete) |
| [autoinc](/autoinc) | 1.0 | **<span class="tcblue">PostgreSQL</span>** | **<span class="tcblue">CONTRIB</span>** | `postgresql$v-contrib` | <span class="tcblue">✔</span> | <span class="tcblue">✔</span> | <span class="tcblue">✔</span> | <span class="tcblue">✔</span> | <span class="tcblue">✔</span> | <span class="tcblue">✔</span> | functions for autoincrementing fields |
| [insert_username](/insert_username) | 1.0 | **<span class="tcblue">PostgreSQL</span>** | **<span class="tcblue">CONTRIB</span>** | `postgresql$v-contrib` | <span class="tcblue">✔</span> | <span class="tcblue">✔</span> | <span class="tcblue">✔</span> | <span class="tcblue">✔</span> | <span class="tcblue">✔</span> | <span class="tcblue">✔</span> | functions for tracking who changed a table |
| [moddatetime](/moddatetime) | 1.0 | **<span class="tcblue">PostgreSQL</span>** | **<span class="tcblue">CONTRIB</span>** | `postgresql$v-contrib` | <span class="tcblue">✔</span> | <span class="tcblue">✔</span> | <span class="tcblue">✔</span> | <span class="tcblue">✔</span> | <span class="tcblue">✔</span> | <span class="tcblue">✔</span> | functions for tracking last modification time |
| [tsm_system_time](/tsm_system_time) | 1.0 | **<span class="tcblue">PostgreSQL</span>** | **<span class="tcblue">CONTRIB</span>** | `postgresql$v-contrib` | <span class="tcblue">✔</span> | <span class="tcblue">✔</span> | <span class="tcblue">✔</span> | <span class="tcblue">✔</span> | <span class="tcblue">✔</span> | <span class="tcblue">✔</span> | TABLESAMPLE method which accepts time in milliseconds as a limit |
| [dict_xsyn](/dict_xsyn) | 1.0 | **<span class="tcblue">PostgreSQL</span>** | **<span class="tcblue">CONTRIB</span>** | `postgresql$v-contrib` | <span class="tcblue">✔</span> | <span class="tcblue">✔</span> | <span class="tcblue">✔</span> | <span class="tcblue">✔</span> | <span class="tcblue">✔</span> | <span class="tcblue">✔</span> | text search dictionary template for extended synonym processing |
| [tsm_system_rows](/tsm_system_rows) | 1.0 | **<span class="tcblue">PostgreSQL</span>** | **<span class="tcblue">CONTRIB</span>** | `postgresql$v-contrib` | <span class="tcblue">✔</span> | <span class="tcblue">✔</span> | <span class="tcblue">✔</span> | <span class="tcblue">✔</span> | <span class="tcblue">✔</span> | <span class="tcblue">✔</span> | TABLESAMPLE method which accepts number of rows as a limit |
| [tcn](/tcn) | 1.0 | **<span class="tcblue">PostgreSQL</span>** | **<span class="tcblue">CONTRIB</span>** | `postgresql$v-contrib` | <span class="tcblue">✔</span> | <span class="tcblue">✔</span> | <span class="tcblue">✔</span> | <span class="tcblue">✔</span> | <span class="tcblue">✔</span> | <span class="tcblue">✔</span> | Triggered change notifications |
| [uuid-ossp](/uuid-ossp) | 1.1 | **<span class="tcblue">PostgreSQL</span>** | **<span class="tcblue">CONTRIB</span>** | `postgresql$v-contrib` | <span class="tcblue">✔</span> | <span class="tcblue">✔</span> | <span class="tcblue">✔</span> | <span class="tcblue">✔</span> | <span class="tcblue">✔</span> | <span class="tcblue">✔</span> | generate universally unique identifiers (UUIDs) |
| [btree_gist](/btree_gist) | 1.7 | **<span class="tcblue">PostgreSQL</span>** | **<span class="tcblue">CONTRIB</span>** | `postgresql$v-contrib` | <span class="tcblue">✔</span> | <span class="tcblue">✔</span> | <span class="tcblue">✔</span> | <span class="tcblue">✔</span> | <span class="tcblue">✔</span> | <span class="tcblue">✔</span> | support for indexing common datatypes in GiST |
| [btree_gin](/btree_gin) | 1.3 | **<span class="tcblue">PostgreSQL</span>** | **<span class="tcblue">CONTRIB</span>** | `postgresql$v-contrib` | <span class="tcblue">✔</span> | <span class="tcblue">✔</span> | <span class="tcblue">✔</span> | <span class="tcblue">✔</span> | <span class="tcblue">✔</span> | <span class="tcblue">✔</span> | support for indexing common datatypes in GIN |
| [intarray](/intarray) | 1.5 | **<span class="tcblue">PostgreSQL</span>** | **<span class="tcblue">CONTRIB</span>** | `postgresql$v-contrib` | <span class="tcblue">✔</span> | <span class="tcblue">✔</span> | <span class="tcblue">✔</span> | <span class="tcblue">✔</span> | <span class="tcblue">✔</span> | <span class="tcblue">✔</span> | functions, operators, and index support for 1-D arrays of integers |
| [intagg](/intagg) | 1.1 | **<span class="tcblue">PostgreSQL</span>** | **<span class="tcblue">CONTRIB</span>** | `postgresql$v-contrib` | <span class="tcblue">✔</span> | <span class="tcblue">✔</span> | <span class="tcblue">✔</span> | <span class="tcblue">✔</span> | <span class="tcblue">✔</span> | <span class="tcblue">✔</span> | integer aggregator and enumerator (obsolete) |
| [dict_int](/dict_int) | 1.0 | **<span class="tcblue">PostgreSQL</span>** | **<span class="tcblue">CONTRIB</span>** | `postgresql$v-contrib` | <span class="tcblue">✔</span> | <span class="tcblue">✔</span> | <span class="tcblue">✔</span> | <span class="tcblue">✔</span> | <span class="tcblue">✔</span> | <span class="tcblue">✔</span> | text search dictionary template for integers |
| [unaccent](/unaccent) | 1.1 | **<span class="tcblue">PostgreSQL</span>** | **<span class="tcblue">CONTRIB</span>** | `postgresql$v-contrib` | <span class="tcblue">✔</span> | <span class="tcblue">✔</span> | <span class="tcblue">✔</span> | <span class="tcblue">✔</span> | <span class="tcblue">✔</span> | <span class="tcblue">✔</span> | text search dictionary that removes accents |



```yaml
pg17: topn_17* pgsql_gzip_17* pg_zstd_17* pgsql_http_17* pg_net_17* pg_html5_email_address_17 pgsql_tweaks_17* pg_extra_time_17* pg_timeit_17* count_distinct_17* extra_window_functions_17* first_last_agg_17 tdigest_17* aggs_for_vecs_17* aggs_for_arrays_17* pg_arraymath_17* quantile_17* lower_quantile_17* pg_idkit_17 pg_uuidv7_17* permuteseq_17* pg_hashids_17* sequential_uuids_17* pg_math_17* pg_random_17* pg_base36_17* pg_base62_17* pg_base58_17 floatvec_17* pg_financial_17* pgjwt_17* pg_hashlib_17 postgres_shacrypt_17* cryptint_17* pg_ecdsa_17* pgpcre_17 icu_ext_17* pgqr_17* pg_envvar_17* pg_protobuf_17 url_encode_17* 
pg16: topn_16* pgsql_gzip_16* pg_zstd_16* pgsql_http_16* pg_net_16* pg_html5_email_address_16 pgsql_tweaks_16* pg_extra_time_16* pg_timeit_16* count_distinct_16* extra_window_functions_16* first_last_agg_16 tdigest_16* aggs_for_vecs_16* aggs_for_arrays_16* pg_arraymath_16* quantile_16* lower_quantile_16* pg_idkit_16 pg_uuidv7_16* permuteseq_16* pg_hashids_16* sequential_uuids_16* pg_math_16* pg_random_16* pg_base36_16* pg_base62_16* pg_base58_16 floatvec_16* pg_financial_16* pgjwt_16* pg_hashlib_16 postgres_shacrypt_16* cryptint_16* pg_ecdsa_16* pgpcre_16 icu_ext_16* pgqr_16* pg_envvar_16* pg_protobuf_16 url_encode_16* 
pg15: topn_15* pgsql_gzip_15* pg_zstd_15* pgsql_http_15* pg_net_15* pg_html5_email_address_15 pgsql_tweaks_15* pg_extra_time_15* pg_timeit_15* count_distinct_15* extra_window_functions_15* first_last_agg_15 tdigest_15* aggs_for_vecs_15* aggs_for_arrays_15* pg_arraymath_15* quantile_15* lower_quantile_15* pg_idkit_15 pg_uuidv7_15* permuteseq_15* pg_hashids_15* sequential_uuids_15* pg_math_15* pg_random_15* pg_base36_15* pg_base62_15* pg_base58_15 floatvec_15* pg_financial_15* pgjwt_15* pg_hashlib_15 postgres_shacrypt_15* cryptint_15* pg_ecdsa_15* pgpcre_15 icu_ext_15* pgqr_15* pg_envvar_15* pg_protobuf_15 url_encode_15* 
pg14: topn_14* pgsql_gzip_14* pg_zstd_14* pgsql_http_14* pg_net_14* pg_html5_email_address_14 pgsql_tweaks_14* pg_extra_time_14* pg_timeit_14* count_distinct_14* extra_window_functions_14* first_last_agg_14 tdigest_14* aggs_for_vecs_14* aggs_for_arrays_14* pg_arraymath_14* quantile_14* lower_quantile_14* pg_idkit_14 pg_uuidv7_14* permuteseq_14* pg_hashids_14* sequential_uuids_14* pg_math_14* pg_random_14* pg_base36_14* pg_base62_14* pg_base58_14 floatvec_14* pg_financial_14* pgjwt_14* pg_hashlib_14 postgres_shacrypt_14* cryptint_14* pg_ecdsa_14* pgpcre_14 icu_ext_14* pgqr_14* pg_envvar_14* pg_protobuf_14 url_encode_14* 
pg13: topn_13* pgsql_gzip_13* pg_zstd_13* pgsql_http_13* pg_net_13* pg_html5_email_address_13 pgsql_tweaks_13* pg_extra_time_13* pg_timeit_13* count_distinct_13* extra_window_functions_13* first_last_agg_13 tdigest_13* aggs_for_vecs_13* aggs_for_arrays_13* pg_arraymath_13* quantile_13* lower_quantile_13* pg_idkit_13 pg_uuidv7_13* permuteseq_13* pg_hashids_13* sequential_uuids_13* pg_math_13* pg_random_13* pg_base36_13* pg_base62_13* pg_base58_13 floatvec_13* pg_financial_13* pgjwt_13* pg_hashlib_13 postgres_shacrypt_13* cryptint_13* pg_ecdsa_13* pgpcre_13 icu_ext_13* pgqr_13* pg_envvar_13* pg_protobuf_13 url_encode_13* 
pg12: topn_12* pgsql_gzip_12* pg_zstd_12* pgsql_http_12* pg_net_12* pg_html5_email_address_12 pgsql_tweaks_12* pg_extra_time_12* pg_timeit_12* count_distinct_12* extra_window_functions_12* first_last_agg_12 tdigest_12* aggs_for_vecs_12* aggs_for_arrays_12* pg_arraymath_12* quantile_12* lower_quantile_12* pg_idkit_12 pg_uuidv7_12* permuteseq_12* pg_hashids_12* sequential_uuids_12* pg_math_12* pg_random_12* pg_base36_12* pg_base62_12* pg_base58_12 floatvec_12* pg_financial_12* pgjwt_12* pg_hashlib_12 postgres_shacrypt_12* cryptint_12* pg_ecdsa_12* pgpcre_12 icu_ext_12* pgqr_12* pg_envvar_12* pg_protobuf_12 url_encode_12* 
```



--------

## DEB Packages


| Package | Version | License | DEB | DEB Package | 17 | 16 | 15 | 14 | 13 | 12 | Description |
|---------|---------|:-------:|:---:|-------------|:--:|:--:|:--:|:--:|:--:|:--:|-------------|
| [topn](/topn) | 2.6.0 | **<span class="tcwarn">AGPLv3</span>** | **<span class="tccyan">PGDG</span>** | `postgresql-$v-topn` | <span class="tcblue">✔</span> | <span class="tcblue">✔</span> | <span class="tcblue">✔</span> | <span class="tcblue">✔</span> | <span class="tcblue">✔</span> | <span class="tcblue">✔</span> | type for top-n JSONB |
| [pg_gzip](/gzip) | 1.0 | **<span class="tcblue">MIT</span>** | **<span class="tcwarn">PIGSTY</span>** | `postgresql-$v-gzip` | <span class="tcblue">✔</span> | <span class="tcblue">✔</span> | <span class="tcblue">✔</span> | <span class="tcblue">✔</span> | <span class="tcblue">✔</span> | <span class="tcblue">✔</span> | gzip and gunzip functions. |
| [pg_zstd](/zstd) | 1.1.0 | **<span class="tcblue">ISC</span>** | **<span class="tcwarn">PIGSTY</span>** | `postgresql-$v-pg-zstd` | <span class="tcblue">✔</span> | <span class="tcblue">✔</span> | <span class="tcblue">✔</span> | <span class="tcblue">✔</span> | <span class="tcblue">✔</span> | <span class="tcblue">✔</span> | Zstandard compression algorithm implementation in PostgreSQL |
| [pg_http](/http) | 1.6 | **<span class="tcblue">MIT</span>** | **<span class="tccyan">PGDG</span>** | `postgresql-$v-http` | <span class="tcblue">✔</span> | <span class="tcblue">✔</span> | <span class="tcblue">✔</span> | <span class="tcblue">✔</span> | <span class="tcblue">✔</span> | <span class="tcblue">✔</span> | HTTP client for PostgreSQL, allows web page retrieval inside the database. |
| [pg_net](/pg_net) | 0.9.2 | **<span class="tccyan">Apache-2</span>** | **<span class="tcwarn">PIGSTY</span>** | `postgresql-$v-pg-net` | <span class="tcblue">✔</span> | <span class="tcblue">✔</span> | <span class="tcblue">✔</span> | <span class="tcblue">✔</span> | <span class="tcblue">✔</span> | <span class="tcblue">✔</span> | Async HTTP Requests |
| [pg_html5_email_address](/pg_html5_email_address) | 1.2.3 | **<span class="tcblue">PostgreSQL</span>** | **<span class="tcwarn">PIGSTY</span>** | `postgresql-$v-pg-html5-email-address` | <span class="tcblue">✔</span> | <span class="tcblue">✔</span> | <span class="tcblue">✔</span> | <span class="tcblue">✔</span> | <span class="tcblue">✔</span> | <span class="tcblue">✔</span> | PostgreSQL email validation that is consistent with the HTML5 spec |
| [pgsql_tweaks](/pgsql_tweaks) | 0.10.4 | **<span class="tcblue">PostgreSQL</span>** | **<span class="tcwarn">PIGSTY</span>** | `postgresql-$v-pgsql-tweaks` | <span class="tcblue">✔</span> | <span class="tcblue">✔</span> | <span class="tcblue">✔</span> | <span class="tcblue">✔</span> | <span class="tcblue">✔</span> | <span class="tcblue">✔</span> | Some functions and views for daily usage |
| [pg_extra_time](/pg_extra_time) | 1.1.3 | **<span class="tcblue">PostgreSQL</span>** | **<span class="tcwarn">PIGSTY</span>** | `postgresql-$v-pg-extra-time` | <span class="tcblue">✔</span> | <span class="tcblue">✔</span> | <span class="tcblue">✔</span> | <span class="tcblue">✔</span> | <span class="tcblue">✔</span> | <span class="tcblue">✔</span> | Some date time functions and operators that, |
| [pg_timeit](/timeit) | 1.0 | **<span class="tcblue">PostgreSQL</span>** | **<span class="tcwarn">PIGSTY</span>** | `postgresql-$v-pg-timeit` | <span class="tcblue">✔</span> | <span class="tcblue">✔</span> | <span class="tcblue">✔</span> | <span class="tcblue">✔</span> | <span class="tcblue">✔</span> | <span class="tcblue">✔</span> | High-accuracy timing of SQL expressions |
| [count_distinct](/count_distinct) | 3.0.2 | **<span class="tcblue">BSD-2</span>** | **<span class="tcwarn">PIGSTY</span>** | `postgresql-$v-count-distinct` | <span class="tcblue">✔</span> | <span class="tcblue">✔</span> | <span class="tcblue">✔</span> | <span class="tcblue">✔</span> | <span class="tcblue">✔</span> | <span class="tcblue">✔</span> | An alternative to COUNT(DISTINCT …) aggregate, usable with HashAggregate |
| [extra_window_functions](/extra_window_functions) | 1.0 | **<span class="tcblue">PostgreSQL</span>** | **<span class="tccyan">PGDG</span>** | `postgresql-$v-extra-window-functions` | <span class="tcblue">✔</span> | <span class="tcblue">✔</span> | <span class="tcblue">✔</span> | <span class="tcblue">✔</span> | <span class="tcblue">✔</span> | <span class="tcblue">✔</span> | Extra Window Functions for PostgreSQL |
| [first_last_agg](/first_last_agg) | 0.1.4 | **<span class="tcblue">PostgreSQL</span>** | **<span class="tccyan">PGDG</span>** | `postgresql-$v-first-last-agg` | <span class="tcblue">✔</span> | <span class="tcblue">✔</span> | <span class="tcblue">✔</span> | <span class="tcblue">✔</span> | <span class="tcblue">✔</span> | <span class="tcblue">✔</span> | first() and last() aggregate functions |
| [tdigest](/tdigest) | 1.4.1 | **<span class="tccyan">Apache-2</span>** | **<span class="tccyan">PGDG</span>** | `postgresql-$v-tdigest` | <span class="tcblue">✔</span> | <span class="tcblue">✔</span> | <span class="tcblue">✔</span> | <span class="tcblue">✔</span> | <span class="tcblue">✔</span> | <span class="tcblue">✔</span> | Provides tdigest aggregate function. |
| [aggs_for_vecs](/aggs_for_vecs) | 1.3.0 | **<span class="tcblue">MIT</span>** | **<span class="tcwarn">PIGSTY</span>** | `postgresql-$v-aggs-for-vecs` | <span class="tcblue">✔</span> | <span class="tcblue">✔</span> | <span class="tcblue">✔</span> | <span class="tcblue">✔</span> | <span class="tcblue">✔</span> | <span class="tcblue">✔</span> | Aggregate functions for array inputs |
| [aggs_for_arrays](/aggs_for_arrays) | 1.3.2 | **<span class="tcblue">MIT</span>** | **<span class="tcwarn">PIGSTY</span>** | `postgresql-$v-aggs-for-arrays` | <span class="tcblue">✔</span> | <span class="tcblue">✔</span> | <span class="tcblue">✔</span> | <span class="tcblue">✔</span> | <span class="tcblue">✔</span> | <span class="tcblue">✔</span> | Various functions for computing statistics on arrays of numbers |
| [pg_arraymath](/arraymath) | 1.1 | **<span class="tcblue">MIT</span>** | **<span class="tcwarn">PIGSTY</span>** | `postgresql-$v-pg-arraymath` | <span class="tcblue">✔</span> | <span class="tcblue">✔</span> | <span class="tcblue">✔</span> | <span class="tcblue">✔</span> | <span class="tcblue">✔</span> | <span class="tcblue">✔</span> | Array math and operators that work element by element on the contents of arrays |
| [quantile](/quantile) | 1.1.7 | **<span class="tcblue">BSD-2</span>** | **<span class="tcwarn">PIGSTY</span>** | `postgresql-$v-quantile` | <span class="tcblue">✔</span> | <span class="tcblue">✔</span> | <span class="tcblue">✔</span> | <span class="tcblue">✔</span> | <span class="tcblue">✔</span> | <span class="tcblue">✔</span> | Quantile aggregation function |
| [lower_quantile](/lower_quantile) | 1.0.0 | **<span class="tcblue">BSD-2</span>** | **<span class="tcwarn">PIGSTY</span>** | `postgresql-$v-lower-quantile` | <span class="tcblue">✔</span> | <span class="tcblue">✔</span> | <span class="tcblue">✔</span> | <span class="tcblue">✔</span> | <span class="tcblue">✔</span> | <span class="tcblue">✔</span> | Lower quantile aggregate function |
| [pg_idkit](/pg_idkit) | 0.2.4 | **<span class="tccyan">Apache-2</span>** | **<span class="tcwarn">PIGSTY</span>** | `postgresql-$v-pg-idkit` | <span class="tcblue">✔</span> | <span class="tcblue">✔</span> | <span class="tcblue">✔</span> | <span class="tcblue">✔</span> | <span class="tcblue">✔</span> | <span class="tcblue">✔</span> | multi-tool for generating new/niche universally unique identifiers (ex. UUIDv6, ULID, KSUID) |
| [pg_uuidv7](/pg_uuidv7) | 1.6 | **<span class="tccyan">MPLv2</span>** | **<span class="tcwarn">PIGSTY</span>** | `postgresql-$v-pg-uuidv7` | <span class="tcblue">✔</span> | <span class="tcblue">✔</span> | <span class="tcblue">✔</span> | <span class="tcblue">✔</span> | <span class="tcblue">✔</span> | <span class="tcblue">✔</span> | pg_uuidv7: create UUIDv7 values in postgres |
| [permuteseq](/permuteseq) | 1.2 | **<span class="tcblue">PostgreSQL</span>** | **<span class="tcwarn">PIGSTY</span>** | `postgresql-$v-permuteseq` | <span class="tcblue">✔</span> | <span class="tcblue">✔</span> | <span class="tcblue">✔</span> | <span class="tcblue">✔</span> | <span class="tcblue">✔</span> | <span class="tcblue">✔</span> | Pseudo-randomly permute sequences with a format-preserving encryption on elements |
| [pg_hashids](/pg_hashids) | 1.3 | **<span class="tcblue">MIT</span>** | **<span class="tcwarn">PIGSTY</span>** | `postgresql-$v-pg-hashids` | <span class="tcblue">✔</span> | <span class="tcblue">✔</span> | <span class="tcblue">✔</span> | <span class="tcblue">✔</span> | <span class="tcblue">✔</span> | <span class="tcblue">✔</span> | Short unique id generator for PostgreSQL, using hashids |
| [sequential_uuids](/sequential_uuids) | 1.0.2 | **<span class="tcblue">MIT</span>** | **<span class="tcwarn">PIGSTY</span>** | `postgresql-$v-sequential-uuids` | <span class="tcblue">✔</span> | <span class="tcblue">✔</span> | <span class="tcblue">✔</span> | <span class="tcblue">✔</span> | <span class="tcblue">✔</span> | <span class="tcblue">✔</span> | generator of sequential UUIDs |
| [pg_math](/pg_math) | 1.0 | **<span class="tcwarn">GPLv3</span>** | **<span class="tcwarn">PIGSTY</span>** | `postgresql-$v-pg-math` | <span class="tcblue">✔</span> | <span class="tcblue">✔</span> | <span class="tcblue">✔</span> | <span class="tcblue">✔</span> | <span class="tcblue">✔</span> | <span class="tcblue">✔</span> | GSL statistical functions for postgresql |
| [pg_random](/random) | 2.0.0-dev | **<span class="tcblue">PostgreSQL</span>** | **<span class="tcwarn">PIGSTY</span>** | `postgresql-$v-random` | <span class="tcblue">✔</span> | <span class="tcblue">✔</span> | <span class="tcblue">✔</span> | <span class="tcblue">✔</span> | <span class="tcblue">✔</span> | <span class="tcblue">✔</span> | random data generator |
| [pg_base36](/base36) | 1.0.0 | **<span class="tcblue">MIT</span>** | **<span class="tcwarn">PIGSTY</span>** | `postgresql-$v-base36` | <span class="tcblue">✔</span> | <span class="tcblue">✔</span> | <span class="tcblue">✔</span> | <span class="tcblue">✔</span> | <span class="tcblue">✔</span> | <span class="tcblue">✔</span> | Integer Base36 types |
| [pg_base62](/base62) | 0.0.1 | **<span class="tcblue">MIT</span>** | **<span class="tcwarn">PIGSTY</span>** | `postgresql-$v-base62` | <span class="tcblue">✔</span> | <span class="tcblue">✔</span> | <span class="tcblue">✔</span> | <span class="tcblue">✔</span> | <span class="tcblue">✔</span> | <span class="tcblue">✔</span> | Base62 extension for PostgreSQL |
| [pg_base58](/pg_base58) | 0.0.1 | **<span class="tcblue">MIT</span>** | **<span class="tcwarn">PIGSTY</span>** | `postgresql-$v-pg-base58` | <span class="tcblue">✔</span> | <span class="tcblue">✔</span> | <span class="tcblue">✔</span> | <span class="tcblue">✔</span> | <span class="tcblue">✔</span> | <span class="tcblue">✔</span> | Base58 Encoder/Decoder Extension for PostgreSQL |
| [floatvec](/floatvec) | 1.0.1 | **<span class="tcblue">MIT</span>** | **<span class="tcwarn">PIGSTY</span>** | `postgresql-$v-floatvec` | <span class="tcblue">✔</span> | <span class="tcblue">✔</span> | <span class="tcblue">✔</span> | <span class="tcblue">✔</span> | <span class="tcblue">✔</span> | <span class="tcblue">✔</span> | Math for vectors (arrays) of numbers |
| [pg_financial](/financial) | 1.0.1 | **<span class="tcblue">PostgreSQL</span>** | **<span class="tcwarn">PIGSTY</span>** | `postgresql-$v-pg-financial` | <span class="tcblue">✔</span> | <span class="tcblue">✔</span> | <span class="tcblue">✔</span> | <span class="tcblue">✔</span> | <span class="tcblue">✔</span> | <span class="tcblue">✔</span> | Financial aggregate functions |
| [pgjwt](/pgjwt) | 0.2.0 | **<span class="tcblue">MIT</span>** | **<span class="tcwarn">PIGSTY</span>** | `postgresql-$v-pgjwt` | <span class="tcblue">✔</span> | <span class="tcblue">✔</span> | <span class="tcblue">✔</span> | <span class="tcblue">✔</span> | <span class="tcblue">✔</span> | <span class="tcblue">✔</span> | JSON Web Token API for Postgresql |
| [pg_hashlib](/pg_hashlib) | 1.1 | **<span class="tcblue">PostgreSQL</span>** | **<span class="tcwarn">PIGSTY</span>** | `postgresql-$v-pg-hashlib` | <span class="tcblue">✔</span> | <span class="tcblue">✔</span> | <span class="tcblue">✔</span> | <span class="tcblue">✔</span> | <span class="tcblue">✔</span> | <span class="tcblue">✔</span> | Stable hash functions for Postgres |
| [shacrypt](/shacrypt) | 1.1 | **<span class="tcblue">PostgreSQL</span>** | **<span class="tcwarn">PIGSTY</span>** | `postgresql-$v-shacrypt` | <span class="tcblue">✔</span> | <span class="tcblue">✔</span> | <span class="tcblue">✔</span> | <span class="tcblue">✔</span> | <span class="tcblue">✔</span> | <span class="tcblue">✔</span> | Implements SHA256-CRYPT and SHA512-CRYPT password encryption schemes |
| [cryptint](/cryptint) | 1.0.0 | **<span class="tcblue">PostgreSQL</span>** | **<span class="tcwarn">PIGSTY</span>** | `postgresql-$v-cryptint` | <span class="tcblue">✔</span> | <span class="tcblue">✔</span> | <span class="tcblue">✔</span> | <span class="tcblue">✔</span> | <span class="tcblue">✔</span> | <span class="tcblue">✔</span> | Encryption functions for int and bigint values |
| [pg_ecdsa](/pguecc) | 1.0 | **<span class="tcblue">BSD-2</span>** | **<span class="tcwarn">PIGSTY</span>** | `postgresql-$v-pg-ecdsa` | <span class="tcblue">✔</span> | <span class="tcblue">✔</span> | <span class="tcblue">✔</span> | <span class="tcblue">✔</span> | <span class="tcblue">✔</span> | <span class="tcblue">✔</span> | uECC bindings for Postgres |
| [pgpcre](/pgpcre) | 1 | **<span class="tcblue">PostgreSQL</span>** | **<span class="tccyan">PGDG</span>** | `postgresql-$v-pgpcre` | <span class="tcblue">✔</span> | <span class="tcblue">✔</span> | <span class="tcblue">✔</span> | <span class="tcblue">✔</span> | <span class="tcblue">✔</span> | <span class="tcblue">✔</span> | Perl Compatible Regular Expression functions |
| [icu_ext](/icu_ext) | 1.9 | **<span class="tcblue">PostgreSQL</span>** | **<span class="tccyan">PGDG</span>** | `postgresql-$v-icu-ext` | <span class="tcblue">✔</span> | <span class="tcblue">✔</span> | <span class="tcblue">✔</span> | <span class="tcblue">✔</span> | <span class="tcblue">✔</span> | <span class="tcblue">✔</span> | Access ICU functions |
| [pgqr](/pgqr) | 1.0 | **<span class="tcblue">BSD-3</span>** | **<span class="tcwarn">PIGSTY</span>** | `postgresql-$v-pgqr` | <span class="tcblue">✔</span> | <span class="tcblue">✔</span> | <span class="tcblue">✔</span> | <span class="tcblue">✔</span> | <span class="tcblue">✔</span> | <span class="tcblue">✔</span> | QR Code generator from PostgreSQL |
| [envvar](/envvar) | 1.0.0 | **<span class="tcblue">PostgreSQL</span>** | **<span class="tcwarn">PIGSTY</span>** | `postgresql-$v-pg-envvar` | <span class="tcblue">✔</span> | <span class="tcblue">✔</span> | <span class="tcblue">✔</span> | <span class="tcblue">✔</span> | <span class="tcblue">✔</span> | <span class="tcblue">✔</span> | Fetch the value of an environment variable |
| [pg_protobuf](/pg_protobuf) | 1.0 | **<span class="tcblue">MIT</span>** | **<span class="tcwarn">PIGSTY</span>** | `postgresql-$v-pg-protobuf` | <span class="tcblue">✔</span> | <span class="tcblue">✔</span> | <span class="tcblue">✔</span> | <span class="tcblue">✔</span> | <span class="tcblue">✔</span> | <span class="tcblue">✔</span> | Protobuf support for PostgreSQL |
| [url_encode](/url_encode) | 1.2 | **<span class="tcblue">PostgreSQL</span>** | **<span class="tcwarn">PIGSTY</span>** | `postgresql-$v-url-encode` | <span class="tcblue">✔</span> | <span class="tcblue">✔</span> | <span class="tcblue">✔</span> | <span class="tcblue">✔</span> | <span class="tcblue">✔</span> | <span class="tcblue">✔</span> | url_encode, url_decode functions |
| [refint](/refint) | 1.0 | **<span class="tcblue">PostgreSQL</span>** | **<span class="tcblue">CONTRIB</span>** | `postgresql-$v` | <span class="tcblue">✔</span> | <span class="tcblue">✔</span> | <span class="tcblue">✔</span> | <span class="tcblue">✔</span> | <span class="tcblue">✔</span> | <span class="tcblue">✔</span> | functions for implementing referential integrity (obsolete) |
| [autoinc](/autoinc) | 1.0 | **<span class="tcblue">PostgreSQL</span>** | **<span class="tcblue">CONTRIB</span>** | `postgresql-$v` | <span class="tcblue">✔</span> | <span class="tcblue">✔</span> | <span class="tcblue">✔</span> | <span class="tcblue">✔</span> | <span class="tcblue">✔</span> | <span class="tcblue">✔</span> | functions for autoincrementing fields |
| [insert_username](/insert_username) | 1.0 | **<span class="tcblue">PostgreSQL</span>** | **<span class="tcblue">CONTRIB</span>** | `postgresql-$v` | <span class="tcblue">✔</span> | <span class="tcblue">✔</span> | <span class="tcblue">✔</span> | <span class="tcblue">✔</span> | <span class="tcblue">✔</span> | <span class="tcblue">✔</span> | functions for tracking who changed a table |
| [moddatetime](/moddatetime) | 1.0 | **<span class="tcblue">PostgreSQL</span>** | **<span class="tcblue">CONTRIB</span>** | `postgresql-$v` | <span class="tcblue">✔</span> | <span class="tcblue">✔</span> | <span class="tcblue">✔</span> | <span class="tcblue">✔</span> | <span class="tcblue">✔</span> | <span class="tcblue">✔</span> | functions for tracking last modification time |
| [tsm_system_time](/tsm_system_time) | 1.0 | **<span class="tcblue">PostgreSQL</span>** | **<span class="tcblue">CONTRIB</span>** | `postgresql-$v` | <span class="tcblue">✔</span> | <span class="tcblue">✔</span> | <span class="tcblue">✔</span> | <span class="tcblue">✔</span> | <span class="tcblue">✔</span> | <span class="tcblue">✔</span> | TABLESAMPLE method which accepts time in milliseconds as a limit |
| [dict_xsyn](/dict_xsyn) | 1.0 | **<span class="tcblue">PostgreSQL</span>** | **<span class="tcblue">CONTRIB</span>** | `postgresql-$v` | <span class="tcblue">✔</span> | <span class="tcblue">✔</span> | <span class="tcblue">✔</span> | <span class="tcblue">✔</span> | <span class="tcblue">✔</span> | <span class="tcblue">✔</span> | text search dictionary template for extended synonym processing |
| [tsm_system_rows](/tsm_system_rows) | 1.0 | **<span class="tcblue">PostgreSQL</span>** | **<span class="tcblue">CONTRIB</span>** | `postgresql-$v` | <span class="tcblue">✔</span> | <span class="tcblue">✔</span> | <span class="tcblue">✔</span> | <span class="tcblue">✔</span> | <span class="tcblue">✔</span> | <span class="tcblue">✔</span> | TABLESAMPLE method which accepts number of rows as a limit |
| [tcn](/tcn) | 1.0 | **<span class="tcblue">PostgreSQL</span>** | **<span class="tcblue">CONTRIB</span>** | `postgresql-$v` | <span class="tcblue">✔</span> | <span class="tcblue">✔</span> | <span class="tcblue">✔</span> | <span class="tcblue">✔</span> | <span class="tcblue">✔</span> | <span class="tcblue">✔</span> | Triggered change notifications |
| [uuid-ossp](/uuid-ossp) | 1.1 | **<span class="tcblue">PostgreSQL</span>** | **<span class="tcblue">CONTRIB</span>** | `postgresql-$v` | <span class="tcblue">✔</span> | <span class="tcblue">✔</span> | <span class="tcblue">✔</span> | <span class="tcblue">✔</span> | <span class="tcblue">✔</span> | <span class="tcblue">✔</span> | generate universally unique identifiers (UUIDs) |
| [btree_gist](/btree_gist) | 1.7 | **<span class="tcblue">PostgreSQL</span>** | **<span class="tcblue">CONTRIB</span>** | `postgresql-$v` | <span class="tcblue">✔</span> | <span class="tcblue">✔</span> | <span class="tcblue">✔</span> | <span class="tcblue">✔</span> | <span class="tcblue">✔</span> | <span class="tcblue">✔</span> | support for indexing common datatypes in GiST |
| [btree_gin](/btree_gin) | 1.3 | **<span class="tcblue">PostgreSQL</span>** | **<span class="tcblue">CONTRIB</span>** | `postgresql-$v` | <span class="tcblue">✔</span> | <span class="tcblue">✔</span> | <span class="tcblue">✔</span> | <span class="tcblue">✔</span> | <span class="tcblue">✔</span> | <span class="tcblue">✔</span> | support for indexing common datatypes in GIN |
| [intarray](/intarray) | 1.5 | **<span class="tcblue">PostgreSQL</span>** | **<span class="tcblue">CONTRIB</span>** | `postgresql-$v` | <span class="tcblue">✔</span> | <span class="tcblue">✔</span> | <span class="tcblue">✔</span> | <span class="tcblue">✔</span> | <span class="tcblue">✔</span> | <span class="tcblue">✔</span> | functions, operators, and index support for 1-D arrays of integers |
| [intagg](/intagg) | 1.1 | **<span class="tcblue">PostgreSQL</span>** | **<span class="tcblue">CONTRIB</span>** | `postgresql-$v` | <span class="tcblue">✔</span> | <span class="tcblue">✔</span> | <span class="tcblue">✔</span> | <span class="tcblue">✔</span> | <span class="tcblue">✔</span> | <span class="tcblue">✔</span> | integer aggregator and enumerator (obsolete) |
| [dict_int](/dict_int) | 1.0 | **<span class="tcblue">PostgreSQL</span>** | **<span class="tcblue">CONTRIB</span>** | `postgresql-$v` | <span class="tcblue">✔</span> | <span class="tcblue">✔</span> | <span class="tcblue">✔</span> | <span class="tcblue">✔</span> | <span class="tcblue">✔</span> | <span class="tcblue">✔</span> | text search dictionary template for integers |
| [unaccent](/unaccent) | 1.1 | **<span class="tcblue">PostgreSQL</span>** | **<span class="tcblue">CONTRIB</span>** | `postgresql-$v` | <span class="tcblue">✔</span> | <span class="tcblue">✔</span> | <span class="tcblue">✔</span> | <span class="tcblue">✔</span> | <span class="tcblue">✔</span> | <span class="tcblue">✔</span> | text search dictionary that removes accents |



```yaml
pg17: topn_17* pgsql_gzip_17* pg_zstd_17* pgsql_http_17* pg_net_17* pg_html5_email_address_17 pgsql_tweaks_17* pg_extra_time_17* pg_timeit_17* count_distinct_17* extra_window_functions_17* first_last_agg_17 tdigest_17* aggs_for_vecs_17* aggs_for_arrays_17* pg_arraymath_17* quantile_17* lower_quantile_17* pg_idkit_17 pg_uuidv7_17* permuteseq_17* pg_hashids_17* sequential_uuids_17* pg_math_17* pg_random_17* pg_base36_17* pg_base62_17* pg_base58_17 floatvec_17* pg_financial_17* pgjwt_17* pg_hashlib_17 postgres_shacrypt_17* cryptint_17* pg_ecdsa_17* pgpcre_17 icu_ext_17* pgqr_17* pg_envvar_17* pg_protobuf_17 url_encode_17* 
pg16: topn_16* pgsql_gzip_16* pg_zstd_16* pgsql_http_16* pg_net_16* pg_html5_email_address_16 pgsql_tweaks_16* pg_extra_time_16* pg_timeit_16* count_distinct_16* extra_window_functions_16* first_last_agg_16 tdigest_16* aggs_for_vecs_16* aggs_for_arrays_16* pg_arraymath_16* quantile_16* lower_quantile_16* pg_idkit_16 pg_uuidv7_16* permuteseq_16* pg_hashids_16* sequential_uuids_16* pg_math_16* pg_random_16* pg_base36_16* pg_base62_16* pg_base58_16 floatvec_16* pg_financial_16* pgjwt_16* pg_hashlib_16 postgres_shacrypt_16* cryptint_16* pg_ecdsa_16* pgpcre_16 icu_ext_16* pgqr_16* pg_envvar_16* pg_protobuf_16 url_encode_16* 
pg15: topn_15* pgsql_gzip_15* pg_zstd_15* pgsql_http_15* pg_net_15* pg_html5_email_address_15 pgsql_tweaks_15* pg_extra_time_15* pg_timeit_15* count_distinct_15* extra_window_functions_15* first_last_agg_15 tdigest_15* aggs_for_vecs_15* aggs_for_arrays_15* pg_arraymath_15* quantile_15* lower_quantile_15* pg_idkit_15 pg_uuidv7_15* permuteseq_15* pg_hashids_15* sequential_uuids_15* pg_math_15* pg_random_15* pg_base36_15* pg_base62_15* pg_base58_15 floatvec_15* pg_financial_15* pgjwt_15* pg_hashlib_15 postgres_shacrypt_15* cryptint_15* pg_ecdsa_15* pgpcre_15 icu_ext_15* pgqr_15* pg_envvar_15* pg_protobuf_15 url_encode_15* 
pg14: topn_14* pgsql_gzip_14* pg_zstd_14* pgsql_http_14* pg_net_14* pg_html5_email_address_14 pgsql_tweaks_14* pg_extra_time_14* pg_timeit_14* count_distinct_14* extra_window_functions_14* first_last_agg_14 tdigest_14* aggs_for_vecs_14* aggs_for_arrays_14* pg_arraymath_14* quantile_14* lower_quantile_14* pg_idkit_14 pg_uuidv7_14* permuteseq_14* pg_hashids_14* sequential_uuids_14* pg_math_14* pg_random_14* pg_base36_14* pg_base62_14* pg_base58_14 floatvec_14* pg_financial_14* pgjwt_14* pg_hashlib_14 postgres_shacrypt_14* cryptint_14* pg_ecdsa_14* pgpcre_14 icu_ext_14* pgqr_14* pg_envvar_14* pg_protobuf_14 url_encode_14* 
pg13: topn_13* pgsql_gzip_13* pg_zstd_13* pgsql_http_13* pg_net_13* pg_html5_email_address_13 pgsql_tweaks_13* pg_extra_time_13* pg_timeit_13* count_distinct_13* extra_window_functions_13* first_last_agg_13 tdigest_13* aggs_for_vecs_13* aggs_for_arrays_13* pg_arraymath_13* quantile_13* lower_quantile_13* pg_idkit_13 pg_uuidv7_13* permuteseq_13* pg_hashids_13* sequential_uuids_13* pg_math_13* pg_random_13* pg_base36_13* pg_base62_13* pg_base58_13 floatvec_13* pg_financial_13* pgjwt_13* pg_hashlib_13 postgres_shacrypt_13* cryptint_13* pg_ecdsa_13* pgpcre_13 icu_ext_13* pgqr_13* pg_envvar_13* pg_protobuf_13 url_encode_13* 
pg12: topn_12* pgsql_gzip_12* pg_zstd_12* pgsql_http_12* pg_net_12* pg_html5_email_address_12 pgsql_tweaks_12* pg_extra_time_12* pg_timeit_12* count_distinct_12* extra_window_functions_12* first_last_agg_12 tdigest_12* aggs_for_vecs_12* aggs_for_arrays_12* pg_arraymath_12* quantile_12* lower_quantile_12* pg_idkit_12 pg_uuidv7_12* permuteseq_12* pg_hashids_12* sequential_uuids_12* pg_math_12* pg_random_12* pg_base36_12* pg_base62_12* pg_base58_12 floatvec_12* pg_financial_12* pgjwt_12* pg_hashlib_12 postgres_shacrypt_12* cryptint_12* pg_ecdsa_12* pgpcre_12 icu_ext_12* pgqr_12* pg_envvar_12* pg_protobuf_12 url_encode_12* 
```



--------

## topn

[`topn`](/topn): type for top-n JSONB

## gzip

[`gzip`](/gzip): (package alias: `pg_gzip`) gzip and gunzip functions.

## zstd

[`zstd`](/zstd): (package alias: `pg_zstd`) Zstandard compression algorithm implementation in PostgreSQL

## http

[`http`](/http): (package alias: `pg_http`) HTTP client for PostgreSQL, allows web page retrieval inside the database.

## pg_net

[`pg_net`](/pg_net): Async HTTP Requests

## pg_html5_email_address

[`pg_html5_email_address`](/pg_html5_email_address): PostgreSQL email validation that is consistent with the HTML5 spec

## pgsql_tweaks

[`pgsql_tweaks`](/pgsql_tweaks): Some functions and views for daily usage

## pg_extra_time

[`pg_extra_time`](/pg_extra_time): Some date time functions and operators that,

## timeit

[`timeit`](/timeit): (package alias: `pg_timeit`) High-accuracy timing of SQL expressions

## count_distinct

[`count_distinct`](/count_distinct): An alternative to COUNT(DISTINCT …) aggregate, usable with HashAggregate

## extra_window_functions

[`extra_window_functions`](/extra_window_functions): Extra Window Functions for PostgreSQL

## first_last_agg

[`first_last_agg`](/first_last_agg): first() and last() aggregate functions

## tdigest

[`tdigest`](/tdigest): Provides tdigest aggregate function.

## aggs_for_vecs

[`aggs_for_vecs`](/aggs_for_vecs): Aggregate functions for array inputs

## aggs_for_arrays

[`aggs_for_arrays`](/aggs_for_arrays): Various functions for computing statistics on arrays of numbers

## arraymath

[`arraymath`](/arraymath): (package alias: `pg_arraymath`) Array math and operators that work element by element on the contents of arrays

## quantile

[`quantile`](/quantile): Quantile aggregation function

## lower_quantile

[`lower_quantile`](/lower_quantile): Lower quantile aggregate function

## pg_idkit

[`pg_idkit`](/pg_idkit): multi-tool for generating new/niche universally unique identifiers (ex. UUIDv6, ULID, KSUID)

## pg_uuidv7

[`pg_uuidv7`](/pg_uuidv7): pg_uuidv7: create UUIDv7 values in postgres

## permuteseq

[`permuteseq`](/permuteseq): Pseudo-randomly permute sequences with a format-preserving encryption on elements

## pg_hashids

[`pg_hashids`](/pg_hashids): Short unique id generator for PostgreSQL, using hashids

## sequential_uuids

[`sequential_uuids`](/sequential_uuids): generator of sequential UUIDs

## pg_math

[`pg_math`](/pg_math): GSL statistical functions for postgresql

## random

[`random`](/random): (package alias: `pg_random`) random data generator

## base36

[`base36`](/base36): (package alias: `pg_base36`) Integer Base36 types

## base62

[`base62`](/base62): (package alias: `pg_base62`) Base62 extension for PostgreSQL

## pg_base58

[`pg_base58`](/pg_base58): Base58 Encoder/Decoder Extension for PostgreSQL

## floatvec

[`floatvec`](/floatvec): Math for vectors (arrays) of numbers

## financial

[`financial`](/financial): (package alias: `pg_financial`) Financial aggregate functions

## pgjwt

[`pgjwt`](/pgjwt): JSON Web Token API for Postgresql

## pg_hashlib

[`pg_hashlib`](/pg_hashlib): Stable hash functions for Postgres

## shacrypt

[`shacrypt`](/shacrypt): Implements SHA256-CRYPT and SHA512-CRYPT password encryption schemes

## cryptint

[`cryptint`](/cryptint): Encryption functions for int and bigint values

## pguecc

[`pguecc`](/pguecc): (package alias: `pg_ecdsa`) uECC bindings for Postgres

## pgpcre

[`pgpcre`](/pgpcre): Perl Compatible Regular Expression functions

## icu_ext

[`icu_ext`](/icu_ext): Access ICU functions

## pgqr

[`pgqr`](/pgqr): QR Code generator from PostgreSQL

## envvar

[`envvar`](/envvar): Fetch the value of an environment variable

## pg_protobuf

[`pg_protobuf`](/pg_protobuf): Protobuf support for PostgreSQL

## url_encode

[`url_encode`](/url_encode): url_encode, url_decode functions

## refint

[`refint`](/refint): functions for implementing referential integrity (obsolete)

## autoinc

[`autoinc`](/autoinc): functions for autoincrementing fields

## insert_username

[`insert_username`](/insert_username): functions for tracking who changed a table

## moddatetime

[`moddatetime`](/moddatetime): functions for tracking last modification time

## tsm_system_time

[`tsm_system_time`](/tsm_system_time): TABLESAMPLE method which accepts time in milliseconds as a limit

## dict_xsyn

[`dict_xsyn`](/dict_xsyn): text search dictionary template for extended synonym processing

## tsm_system_rows

[`tsm_system_rows`](/tsm_system_rows): TABLESAMPLE method which accepts number of rows as a limit

## tcn

[`tcn`](/tcn): Triggered change notifications

## uuid-ossp

[`uuid-ossp`](/uuid-ossp): generate universally unique identifiers (UUIDs)

## btree_gist

[`btree_gist`](/btree_gist): support for indexing common datatypes in GiST

## btree_gin

[`btree_gin`](/btree_gin): support for indexing common datatypes in GIN

## intarray

[`intarray`](/intarray): functions, operators, and index support for 1-D arrays of integers

## intagg

[`intagg`](/intagg): integer aggregator and enumerator (obsolete)

## dict_int

[`dict_int`](/dict_int): text search dictionary template for integers

## unaccent

[`unaccent`](/unaccent): text search dictionary that removes accents